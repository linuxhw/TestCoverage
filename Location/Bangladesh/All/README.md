Linux in Bangladesh - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Bangladesh.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bangladesh/Desktop/README.md) and [notebooks](/Location/Bangladesh/Notebook/README.md).

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

Total: 316

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | A320M-A PRO MAX             | Desktop     | [9a35c1249b](https://linux-hardware.org/?probe=9a35c1249b) | Jun 30, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c8f0217b26](https://linux-hardware.org/?probe=c8f0217b26) | Jun 29, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [0cafb4009d](https://linux-hardware.org/?probe=0cafb4009d) | Jun 29, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [68d1c799f2](https://linux-hardware.org/?probe=68d1c799f2) | Jun 29, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [d3af5b938a](https://linux-hardware.org/?probe=d3af5b938a) | Jun 29, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| ASUSTek       | X507UB                      | Notebook    | [0ba0fc4089](https://linux-hardware.org/?probe=0ba0fc4089) | Jun 28, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [4b202c1285](https://linux-hardware.org/?probe=4b202c1285) | Jun 22, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [7b8cc6556b](https://linux-hardware.org/?probe=7b8cc6556b) | Jun 12, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [dce8b618f8](https://linux-hardware.org/?probe=dce8b618f8) | May 22, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [758bdaefe9](https://linux-hardware.org/?probe=758bdaefe9) | May 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [99283be07b](https://linux-hardware.org/?probe=99283be07b) | May 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b85af00b16](https://linux-hardware.org/?probe=b85af00b16) | May 18, 2022 |
| Dell          | Latitude 5580               | Notebook    | [18cefe0718](https://linux-hardware.org/?probe=18cefe0718) | May 17, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [c1353ba170](https://linux-hardware.org/?probe=c1353ba170) | May 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [f09183023d](https://linux-hardware.org/?probe=f09183023d) | May 10, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [71e0ef1fc9](https://linux-hardware.org/?probe=71e0ef1fc9) | May 07, 2022 |
| HP            | 240 G3                      | Notebook    | [7062083e69](https://linux-hardware.org/?probe=7062083e69) | May 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3055b0e95f](https://linux-hardware.org/?probe=3055b0e95f) | May 05, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [88f6586c4b](https://linux-hardware.org/?probe=88f6586c4b) | May 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ab11d6ac2f](https://linux-hardware.org/?probe=ab11d6ac2f) | Apr 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6577346b8](https://linux-hardware.org/?probe=c6577346b8) | Apr 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e993bc145](https://linux-hardware.org/?probe=6e993bc145) | Apr 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [73abf1d6fd](https://linux-hardware.org/?probe=73abf1d6fd) | Apr 08, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [19623aa8b6](https://linux-hardware.org/?probe=19623aa8b6) | Apr 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [287aa3ba8e](https://linux-hardware.org/?probe=287aa3ba8e) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [14a3433a91](https://linux-hardware.org/?probe=14a3433a91) | Apr 03, 2022 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | Notebook    | [8199781e64](https://linux-hardware.org/?probe=8199781e64) | Mar 28, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [33d1544ea1](https://linux-hardware.org/?probe=33d1544ea1) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [52ce856be5](https://linux-hardware.org/?probe=52ce856be5) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [1dd07eeee0](https://linux-hardware.org/?probe=1dd07eeee0) | Mar 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [321d0c1b4a](https://linux-hardware.org/?probe=321d0c1b4a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [5db5bac582](https://linux-hardware.org/?probe=5db5bac582) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [cb949f34eb](https://linux-hardware.org/?probe=cb949f34eb) | Mar 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [da23c76a90](https://linux-hardware.org/?probe=da23c76a90) | Mar 19, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [a3ad6439b8](https://linux-hardware.org/?probe=a3ad6439b8) | Mar 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [fd9e66788c](https://linux-hardware.org/?probe=fd9e66788c) | Mar 17, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e141c99bf2](https://linux-hardware.org/?probe=e141c99bf2) | Mar 09, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [87d97b3c00](https://linux-hardware.org/?probe=87d97b3c00) | Mar 05, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [d7a873bf3d](https://linux-hardware.org/?probe=d7a873bf3d) | Feb 27, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [87f30f494f](https://linux-hardware.org/?probe=87f30f494f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [62c028a881](https://linux-hardware.org/?probe=62c028a881) | Feb 16, 2022 |
| Biostar       | H55 HD                      | Desktop     | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [42647bc4b3](https://linux-hardware.org/?probe=42647bc4b3) | Feb 12, 2022 |
| HP            | 339A                        | Desktop     | [6f8e63bfb0](https://linux-hardware.org/?probe=6f8e63bfb0) | Feb 11, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [8e73dc39ab](https://linux-hardware.org/?probe=8e73dc39ab) | Feb 09, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [42e37d6172](https://linux-hardware.org/?probe=42e37d6172) | Feb 07, 2022 |
| Biostar       | H55 HD                      | Desktop     | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [47c47a0121](https://linux-hardware.org/?probe=47c47a0121) | Feb 02, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [d7431ab69e](https://linux-hardware.org/?probe=d7431ab69e) | Jan 31, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [76d17811e3](https://linux-hardware.org/?probe=76d17811e3) | Jan 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [caca9680a9](https://linux-hardware.org/?probe=caca9680a9) | Jan 25, 2022 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [be92c29259](https://linux-hardware.org/?probe=be92c29259) | Jan 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1e89749691](https://linux-hardware.org/?probe=1e89749691) | Jan 22, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [ac35b74090](https://linux-hardware.org/?probe=ac35b74090) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [88f62c8333](https://linux-hardware.org/?probe=88f62c8333) | Jan 15, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [38a7870ece](https://linux-hardware.org/?probe=38a7870ece) | Jan 13, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [2fb0411785](https://linux-hardware.org/?probe=2fb0411785) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [0d69dca8f3](https://linux-hardware.org/?probe=0d69dca8f3) | Jan 04, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [692274162f](https://linux-hardware.org/?probe=692274162f) | Jan 04, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e6a4a21d5c](https://linux-hardware.org/?probe=e6a4a21d5c) | Jan 02, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [8e8da56e93](https://linux-hardware.org/?probe=8e8da56e93) | Jan 01, 2022 |
| OEM           | Unknown                     | Desktop     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [b674024789](https://linux-hardware.org/?probe=b674024789) | Dec 30, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [209e15690e](https://linux-hardware.org/?probe=209e15690e) | Dec 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [00696e3398](https://linux-hardware.org/?probe=00696e3398) | Dec 28, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [7280895518](https://linux-hardware.org/?probe=7280895518) | Dec 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [56d5bb8659](https://linux-hardware.org/?probe=56d5bb8659) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [6ab6a89db8](https://linux-hardware.org/?probe=6ab6a89db8) | Dec 12, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3cd505591d](https://linux-hardware.org/?probe=3cd505591d) | Dec 11, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Dell          | Latitude 7480               | Notebook    | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [42edbb20ce](https://linux-hardware.org/?probe=42edbb20ce) | Dec 04, 2021 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [07bcad31f5](https://linux-hardware.org/?probe=07bcad31f5) | Dec 02, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [cf0cd5c862](https://linux-hardware.org/?probe=cf0cd5c862) | Dec 01, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [5cd208a361](https://linux-hardware.org/?probe=5cd208a361) | Dec 01, 2021 |
| ASUSTek       | P453UJ                      | Notebook    | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [aa0a0e67b3](https://linux-hardware.org/?probe=aa0a0e67b3) | Nov 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [9bffff74e0](https://linux-hardware.org/?probe=9bffff74e0) | Nov 26, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [09b0e5058d](https://linux-hardware.org/?probe=09b0e5058d) | Nov 23, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [623b2b0ba9](https://linux-hardware.org/?probe=623b2b0ba9) | Nov 19, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [47d816d00f](https://linux-hardware.org/?probe=47d816d00f) | Nov 12, 2021 |
| MSI           | 990FXA-GD65                 | Desktop     | [6d2cade66c](https://linux-hardware.org/?probe=6d2cade66c) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [312e04d7f9](https://linux-hardware.org/?probe=312e04d7f9) | Nov 09, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f1f7ca30e5](https://linux-hardware.org/?probe=f1f7ca30e5) | Nov 05, 2021 |
| ASUSTek       | X442UAR                     | Notebook    | [0db140fa3d](https://linux-hardware.org/?probe=0db140fa3d) | Nov 03, 2021 |
| OEM           | Intel H81                   | Desktop     | [a4e298caf1](https://linux-hardware.org/?probe=a4e298caf1) | Nov 02, 2021 |
| OEM           | Intel H81                   | Desktop     | [50758cfaf3](https://linux-hardware.org/?probe=50758cfaf3) | Oct 26, 2021 |
| OEM           | Intel H81                   | Desktop     | [e997f638bc](https://linux-hardware.org/?probe=e997f638bc) | Oct 26, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [356632b328](https://linux-hardware.org/?probe=356632b328) | Oct 19, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [d377aa2b23](https://linux-hardware.org/?probe=d377aa2b23) | Oct 17, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [7447071c00](https://linux-hardware.org/?probe=7447071c00) | Oct 16, 2021 |
| MSI           | Boston                      | Desktop     | [77d385bc09](https://linux-hardware.org/?probe=77d385bc09) | Oct 13, 2021 |
| MSI           | Boston                      | Desktop     | [14528f628a](https://linux-hardware.org/?probe=14528f628a) | Oct 13, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [0bf0387391](https://linux-hardware.org/?probe=0bf0387391) | Oct 07, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [883e0dec71](https://linux-hardware.org/?probe=883e0dec71) | Sep 19, 2021 |
| Dell          | Latitude E7250              | Notebook    | [275b9204f5](https://linux-hardware.org/?probe=275b9204f5) | Sep 13, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [8109d84e42](https://linux-hardware.org/?probe=8109d84e42) | Sep 12, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [6a9842e166](https://linux-hardware.org/?probe=6a9842e166) | Sep 06, 2021 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [752964e357](https://linux-hardware.org/?probe=752964e357) | Sep 05, 2021 |
| ASUSTek       | X456UQ                      | Notebook    | [6ce8e44ad3](https://linux-hardware.org/?probe=6ce8e44ad3) | Sep 02, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [7a654e5473](https://linux-hardware.org/?probe=7a654e5473) | Aug 28, 2021 |
| Acer          | Aspire 4349                 | Notebook    | [527e511232](https://linux-hardware.org/?probe=527e511232) | Aug 27, 2021 |
| Gigabyte      | B250M-Gaming5-CF            | Desktop     | [c34514576a](https://linux-hardware.org/?probe=c34514576a) | Aug 17, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [460fc8dfd4](https://linux-hardware.org/?probe=460fc8dfd4) | Aug 08, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [48853e253b](https://linux-hardware.org/?probe=48853e253b) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | Notebook    | [c22e4ce5b4](https://linux-hardware.org/?probe=c22e4ce5b4) | Jul 29, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| ASUSTek       | X550JK                      | Notebook    | [ebd01f2605](https://linux-hardware.org/?probe=ebd01f2605) | Jul 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [c6dea4c88d](https://linux-hardware.org/?probe=c6dea4c88d) | Jul 19, 2021 |
| Biostar       | TZ68K+                      | Desktop     | [52ef8197ad](https://linux-hardware.org/?probe=52ef8197ad) | Jul 13, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [3b153ae2f9](https://linux-hardware.org/?probe=3b153ae2f9) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [988fc9a599](https://linux-hardware.org/?probe=988fc9a599) | Jun 24, 2021 |
| HP            | 15                          | Notebook    | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [406cb898f1](https://linux-hardware.org/?probe=406cb898f1) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [1927d0abfe](https://linux-hardware.org/?probe=1927d0abfe) | Jun 13, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [23e735bb8f](https://linux-hardware.org/?probe=23e735bb8f) | Jun 08, 2021 |
| Dell          | 0VHWTR A02                  | Desktop     | [ec7174828a](https://linux-hardware.org/?probe=ec7174828a) | Jun 04, 2021 |
| ASUSTek       | UX310UAK                    | Notebook    | [4a79148721](https://linux-hardware.org/?probe=4a79148721) | Jun 03, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6b5f1170f9](https://linux-hardware.org/?probe=6b5f1170f9) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [e2389864db](https://linux-hardware.org/?probe=e2389864db) | Jun 02, 2021 |
| HP            | ENVY TS 14 Sleekbook        | Notebook    | [f52091e51e](https://linux-hardware.org/?probe=f52091e51e) | May 31, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [0226c84811](https://linux-hardware.org/?probe=0226c84811) | May 25, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [b2c4e6f3a5](https://linux-hardware.org/?probe=b2c4e6f3a5) | May 25, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [b34d6d63d9](https://linux-hardware.org/?probe=b34d6d63d9) | May 22, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [4d2529b647](https://linux-hardware.org/?probe=4d2529b647) | May 22, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [8f1510061b](https://linux-hardware.org/?probe=8f1510061b) | May 18, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [e78b76fcf3](https://linux-hardware.org/?probe=e78b76fcf3) | May 18, 2021 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [aba051d387](https://linux-hardware.org/?probe=aba051d387) | May 15, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [fa9f8b7f7e](https://linux-hardware.org/?probe=fa9f8b7f7e) | May 10, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [db1a234412](https://linux-hardware.org/?probe=db1a234412) | May 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [b7e4895fd8](https://linux-hardware.org/?probe=b7e4895fd8) | May 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [1254eab2b7](https://linux-hardware.org/?probe=1254eab2b7) | May 04, 2021 |
| HP            | 15                          | Notebook    | [fd4d562cd2](https://linux-hardware.org/?probe=fd4d562cd2) | May 04, 2021 |
| MSI           | Summit B14 A11MOT           | Notebook    | [9bdd91f198](https://linux-hardware.org/?probe=9bdd91f198) | May 02, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [dbcbb68258](https://linux-hardware.org/?probe=dbcbb68258) | Apr 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [b2600d2372](https://linux-hardware.org/?probe=b2600d2372) | Apr 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [367455807e](https://linux-hardware.org/?probe=367455807e) | Mar 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1de185d0da](https://linux-hardware.org/?probe=1de185d0da) | Mar 22, 2021 |
| Dell          | Latitude E4300              | Notebook    | [2ccfcf6a1b](https://linux-hardware.org/?probe=2ccfcf6a1b) | Mar 22, 2021 |
| HP            | 15                          | Notebook    | [860412bddc](https://linux-hardware.org/?probe=860412bddc) | Mar 20, 2021 |
| HP            | 15                          | Notebook    | [62447250f9](https://linux-hardware.org/?probe=62447250f9) | Mar 17, 2021 |
| ASUSTek       | H110M-CS                    | Desktop     | [ac52c3630c](https://linux-hardware.org/?probe=ac52c3630c) | Mar 12, 2021 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | Notebook    | [4ee1271923](https://linux-hardware.org/?probe=4ee1271923) | Mar 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [6343267ab7](https://linux-hardware.org/?probe=6343267ab7) | Mar 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [47123299d4](https://linux-hardware.org/?probe=47123299d4) | Mar 09, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [a8091a8c28](https://linux-hardware.org/?probe=a8091a8c28) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8f8fe2c911](https://linux-hardware.org/?probe=8f8fe2c911) | Mar 06, 2021 |
| ASUSTek       | X411UNV                     | Notebook    | [009f3bb5e5](https://linux-hardware.org/?probe=009f3bb5e5) | Feb 27, 2021 |
| HP            | 15                          | Notebook    | [e74fa488e9](https://linux-hardware.org/?probe=e74fa488e9) | Feb 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| ASUSTek       | ZenBook UX461FA_UX461FA     | Convertible | [8efc8caada](https://linux-hardware.org/?probe=8efc8caada) | Feb 27, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [b414109f66](https://linux-hardware.org/?probe=b414109f66) | Feb 07, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [08a1160725](https://linux-hardware.org/?probe=08a1160725) | Feb 07, 2021 |
| HP            | Notebook                    | Notebook    | [df39c8aaf8](https://linux-hardware.org/?probe=df39c8aaf8) | Feb 02, 2021 |
| ASUSTek       | X45C                        | Notebook    | [349beec2d5](https://linux-hardware.org/?probe=349beec2d5) | Jan 27, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [474d61d1a7](https://linux-hardware.org/?probe=474d61d1a7) | Jan 27, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [c9e8f99464](https://linux-hardware.org/?probe=c9e8f99464) | Jan 21, 2021 |
| Lenovo        | ThinkPad T450 20BUS2021M    | Notebook    | [60929bb3d1](https://linux-hardware.org/?probe=60929bb3d1) | Jan 21, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [32878b3dae](https://linux-hardware.org/?probe=32878b3dae) | Jan 20, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [03b73f8223](https://linux-hardware.org/?probe=03b73f8223) | Jan 20, 2021 |
| HP            | Notebook                    | Notebook    | [d14d8fe5db](https://linux-hardware.org/?probe=d14d8fe5db) | Jan 19, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [0bfbe639fc](https://linux-hardware.org/?probe=0bfbe639fc) | Jan 18, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [e053ef39b6](https://linux-hardware.org/?probe=e053ef39b6) | Jan 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [5ee0809420](https://linux-hardware.org/?probe=5ee0809420) | Jan 16, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [4c2ddc3c14](https://linux-hardware.org/?probe=4c2ddc3c14) | Jan 10, 2021 |
| HP            | 15                          | Notebook    | [1b3597829c](https://linux-hardware.org/?probe=1b3597829c) | Jan 05, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [150aed5937](https://linux-hardware.org/?probe=150aed5937) | Dec 28, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [f3aaccf16d](https://linux-hardware.org/?probe=f3aaccf16d) | Dec 19, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [eff007611b](https://linux-hardware.org/?probe=eff007611b) | Dec 16, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [1eec63b277](https://linux-hardware.org/?probe=1eec63b277) | Dec 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da59a1c5a8](https://linux-hardware.org/?probe=da59a1c5a8) | Dec 07, 2020 |
| MSI           | GS63 7RD                    | Notebook    | [51929f5d16](https://linux-hardware.org/?probe=51929f5d16) | Dec 05, 2020 |
| Gigabyte      | B85M-HD3                    | Desktop     | [983f59c8ba](https://linux-hardware.org/?probe=983f59c8ba) | Nov 17, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [4d0297d500](https://linux-hardware.org/?probe=4d0297d500) | Nov 15, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [2898db77af](https://linux-hardware.org/?probe=2898db77af) | Nov 14, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [399693b152](https://linux-hardware.org/?probe=399693b152) | Nov 04, 2020 |
| HP            | 15                          | Notebook    | [751dbba280](https://linux-hardware.org/?probe=751dbba280) | Nov 04, 2020 |
| Unknown       | Unknown                     | Desktop     | [49351fb74d](https://linux-hardware.org/?probe=49351fb74d) | Nov 03, 2020 |
| Unknown       | Unknown                     | Desktop     | [a5450c668e](https://linux-hardware.org/?probe=a5450c668e) | Oct 30, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [7e48c5dac7](https://linux-hardware.org/?probe=7e48c5dac7) | Oct 30, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [20da8831d7](https://linux-hardware.org/?probe=20da8831d7) | Oct 29, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [6abbe0be7c](https://linux-hardware.org/?probe=6abbe0be7c) | Oct 29, 2020 |
| Notebook      | DCL C483                    | Notebook    | [ed2bb10c86](https://linux-hardware.org/?probe=ed2bb10c86) | Oct 29, 2020 |
| ASUSTek       | H110M-CS                    | Desktop     | [4bc7a25c4b](https://linux-hardware.org/?probe=4bc7a25c4b) | Oct 29, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [7a6ee90819](https://linux-hardware.org/?probe=7a6ee90819) | Oct 29, 2020 |
| HP            | ENVY Sleekbook 4            | Notebook    | [b2377a6388](https://linux-hardware.org/?probe=b2377a6388) | Oct 29, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [1f7d96b34a](https://linux-hardware.org/?probe=1f7d96b34a) | Oct 27, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [76e61701fa](https://linux-hardware.org/?probe=76e61701fa) | Oct 24, 2020 |
| ASUSTek       | P453UA                      | Notebook    | [a376addbeb](https://linux-hardware.org/?probe=a376addbeb) | Oct 21, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [218b3ce742](https://linux-hardware.org/?probe=218b3ce742) | Oct 12, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [da1765fe36](https://linux-hardware.org/?probe=da1765fe36) | Oct 11, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [a9c53146fc](https://linux-hardware.org/?probe=a9c53146fc) | Oct 10, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [be8091856c](https://linux-hardware.org/?probe=be8091856c) | Oct 09, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [a6f1865423](https://linux-hardware.org/?probe=a6f1865423) | Oct 07, 2020 |
| ASUSTek       | X510UQ                      | Notebook    | [75933321b6](https://linux-hardware.org/?probe=75933321b6) | Oct 02, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [ae7fe5907d](https://linux-hardware.org/?probe=ae7fe5907d) | Sep 27, 2020 |
| ASUSTek       | X555LF                      | Notebook    | [ed0ef70a05](https://linux-hardware.org/?probe=ed0ef70a05) | Sep 19, 2020 |
| Gigabyte      | GA-E350N                    | Desktop     | [871d27c2e8](https://linux-hardware.org/?probe=871d27c2e8) | Sep 18, 2020 |
| Gigabyte      | GA-E350N                    | Desktop     | [3f442c236c](https://linux-hardware.org/?probe=3f442c236c) | Sep 18, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [d7b1ce1a01](https://linux-hardware.org/?probe=d7b1ce1a01) | Sep 15, 2020 |
| Notebook      | N2x0LU                      | Notebook    | [86354a1c26](https://linux-hardware.org/?probe=86354a1c26) | Sep 14, 2020 |
| ASUSTek       | X510UQ                      | Notebook    | [e289d19d20](https://linux-hardware.org/?probe=e289d19d20) | Sep 14, 2020 |
| ASRock        | Z77 Pro3                    | Desktop     | [8d6db6e2d3](https://linux-hardware.org/?probe=8d6db6e2d3) | Sep 09, 2020 |
| ASUSTek       | X555LF                      | Notebook    | [22629ba9b2](https://linux-hardware.org/?probe=22629ba9b2) | Sep 07, 2020 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | Notebook    | [43ddcf3c95](https://linux-hardware.org/?probe=43ddcf3c95) | Sep 06, 2020 |
| Unknown       | Unknown                     | Phone       | [d4a5776865](https://linux-hardware.org/?probe=d4a5776865) | Sep 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [38548d7877](https://linux-hardware.org/?probe=38548d7877) | Sep 01, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [3edf866f94](https://linux-hardware.org/?probe=3edf866f94) | Aug 22, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [3a9beeb9f4](https://linux-hardware.org/?probe=3a9beeb9f4) | Aug 16, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [3c3b21f81b](https://linux-hardware.org/?probe=3c3b21f81b) | Aug 15, 2020 |
| HP            | 14                          | Notebook    | [b7289075c1](https://linux-hardware.org/?probe=b7289075c1) | Aug 08, 2020 |
| SYS           | H310CH5-TI2                 | Desktop     | [fb33742784](https://linux-hardware.org/?probe=fb33742784) | Aug 06, 2020 |
| HP            | EliteBook 850 G2            | Notebook    | [1c81c3c24d](https://linux-hardware.org/?probe=1c81c3c24d) | Jul 30, 2020 |
| Acer          | Aspire E5-473               | Notebook    | [27a9cd08a6](https://linux-hardware.org/?probe=27a9cd08a6) | Jul 26, 2020 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [f1ef1518c4](https://linux-hardware.org/?probe=f1ef1518c4) | Jul 25, 2020 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [bf80f266b6](https://linux-hardware.org/?probe=bf80f266b6) | Jul 25, 2020 |
| Acer          | Aspire E5-473               | Notebook    | [9c3656a710](https://linux-hardware.org/?probe=9c3656a710) | Jul 24, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [3c50b289eb](https://linux-hardware.org/?probe=3c50b289eb) | Jul 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e800855127](https://linux-hardware.org/?probe=e800855127) | Jul 21, 2020 |
| Dell          | Latitude E7470              | Notebook    | [74e59971a2](https://linux-hardware.org/?probe=74e59971a2) | Jul 09, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [eb79a1863c](https://linux-hardware.org/?probe=eb79a1863c) | Jul 08, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [374493e07f](https://linux-hardware.org/?probe=374493e07f) | Jul 08, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [04f260c99a](https://linux-hardware.org/?probe=04f260c99a) | Jul 06, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [aa5a987949](https://linux-hardware.org/?probe=aa5a987949) | Jul 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [e8be3d4a45](https://linux-hardware.org/?probe=e8be3d4a45) | Jul 02, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [d59cf3e39f](https://linux-hardware.org/?probe=d59cf3e39f) | Jun 21, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | Notebook    | [bedb334316](https://linux-hardware.org/?probe=bedb334316) | Jun 11, 2020 |
| Gigabyte      | B75MS                       | Desktop     | [116d7e4473](https://linux-hardware.org/?probe=116d7e4473) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [0690307575](https://linux-hardware.org/?probe=0690307575) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [2d68573dcb](https://linux-hardware.org/?probe=2d68573dcb) | Jun 04, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [24ebee7f8d](https://linux-hardware.org/?probe=24ebee7f8d) | Jun 03, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e10a133997](https://linux-hardware.org/?probe=e10a133997) | Jun 02, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [7b57cf3668](https://linux-hardware.org/?probe=7b57cf3668) | May 30, 2020 |
| ASUSTek       | H61M-A                      | Desktop     | [821df8e348](https://linux-hardware.org/?probe=821df8e348) | May 25, 2020 |
| ASUSTek       | H61M-A                      | Desktop     | [6118e39327](https://linux-hardware.org/?probe=6118e39327) | May 25, 2020 |
| HP            | Notebook                    | Notebook    | [024a28eb0b](https://linux-hardware.org/?probe=024a28eb0b) | May 23, 2020 |
| Dell          | Latitude E7450              | Notebook    | [f3e9ca7a40](https://linux-hardware.org/?probe=f3e9ca7a40) | May 21, 2020 |
| Lenovo        | ThinkPad E470 20H1A029SG    | Notebook    | [6afaed7f7f](https://linux-hardware.org/?probe=6afaed7f7f) | May 21, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e6818ffd7d](https://linux-hardware.org/?probe=e6818ffd7d) | May 21, 2020 |
| Notebook      | W9x0LU                      | Notebook    | [c7455fcb18](https://linux-hardware.org/?probe=c7455fcb18) | May 17, 2020 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [5d81beb457](https://linux-hardware.org/?probe=5d81beb457) | May 17, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [7b1a18ebf9](https://linux-hardware.org/?probe=7b1a18ebf9) | May 09, 2020 |
| ASUSTek       | X556URK                     | Notebook    | [63c6b5a357](https://linux-hardware.org/?probe=63c6b5a357) | May 08, 2020 |
| Foxconn       | 17A0                        | Desktop     | [167cb26122](https://linux-hardware.org/?probe=167cb26122) | May 03, 2020 |
| Notebook      | N750BU                      | Notebook    | [e3f870729f](https://linux-hardware.org/?probe=e3f870729f) | Apr 23, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [de6fa960ad](https://linux-hardware.org/?probe=de6fa960ad) | Apr 23, 2020 |
| I-Life Dig... | ZED_AIR_PLUS                | Convertible | [b1a911e13e](https://linux-hardware.org/?probe=b1a911e13e) | Mar 27, 2020 |
| MSI           | H61M-P31/W8                 | Desktop     | [26d8323c91](https://linux-hardware.org/?probe=26d8323c91) | Mar 25, 2020 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [baa90e0762](https://linux-hardware.org/?probe=baa90e0762) | Mar 22, 2020 |
| Gigabyte      | X299 AORUS Gaming 3 Pro-... | Desktop     | [34ced022e3](https://linux-hardware.org/?probe=34ced022e3) | Feb 29, 2020 |
| HP            | Mini 210-4000               | Notebook    | [61c0ab33d8](https://linux-hardware.org/?probe=61c0ab33d8) | Feb 28, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [729f8e494d](https://linux-hardware.org/?probe=729f8e494d) | Feb 14, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [357823f120](https://linux-hardware.org/?probe=357823f120) | Feb 03, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e9a4da7f1c](https://linux-hardware.org/?probe=e9a4da7f1c) | Jan 31, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [4fad937155](https://linux-hardware.org/?probe=4fad937155) | Jan 10, 2020 |
| Lenovo        | ThinkPad L380 20M6S22500    | Notebook    | [15c43def70](https://linux-hardware.org/?probe=15c43def70) | Jan 09, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [9d4e0d1911](https://linux-hardware.org/?probe=9d4e0d1911) | Jan 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [2d0bca85ea](https://linux-hardware.org/?probe=2d0bca85ea) | Dec 29, 2019 |
| Gigabyte      | B85M-D3H                    | Desktop     | [753205d5df](https://linux-hardware.org/?probe=753205d5df) | Dec 27, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [d85b25cd22](https://linux-hardware.org/?probe=d85b25cd22) | Dec 24, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [30c00cb837](https://linux-hardware.org/?probe=30c00cb837) | Dec 14, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [e004d9f500](https://linux-hardware.org/?probe=e004d9f500) | Dec 14, 2019 |
| ASUSTek       | E202SA                      | Notebook    | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [44d09b2105](https://linux-hardware.org/?probe=44d09b2105) | Nov 19, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [3fc910f23c](https://linux-hardware.org/?probe=3fc910f23c) | Nov 19, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [afc9fdb4b3](https://linux-hardware.org/?probe=afc9fdb4b3) | Nov 14, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [7914862967](https://linux-hardware.org/?probe=7914862967) | Nov 14, 2019 |
| MSI           | PH67A-C43                   | Desktop     | [b472118c5a](https://linux-hardware.org/?probe=b472118c5a) | Oct 29, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [73a0de63c0](https://linux-hardware.org/?probe=73a0de63c0) | Sep 27, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [4299e1c036](https://linux-hardware.org/?probe=4299e1c036) | Sep 27, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [671ea53b31](https://linux-hardware.org/?probe=671ea53b31) | Sep 22, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [53b4bf1914](https://linux-hardware.org/?probe=53b4bf1914) | Sep 22, 2019 |
| ASUSTek       | X441UA                      | Notebook    | [6022620aee](https://linux-hardware.org/?probe=6022620aee) | Sep 17, 2019 |
| ASUSTek       | X441UA                      | Notebook    | [d0632368ab](https://linux-hardware.org/?probe=d0632368ab) | Sep 04, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [ede7f2c199](https://linux-hardware.org/?probe=ede7f2c199) | Aug 30, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [e3c13fc2d8](https://linux-hardware.org/?probe=e3c13fc2d8) | Aug 20, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d0d6cd20b1](https://linux-hardware.org/?probe=d0d6cd20b1) | Jul 26, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [f9b65f1415](https://linux-hardware.org/?probe=f9b65f1415) | Jul 14, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a6f5bc1b0f](https://linux-hardware.org/?probe=a6f5bc1b0f) | Jul 13, 2019 |
| HP            | Notebook                    | Notebook    | [2ce0b2ff35](https://linux-hardware.org/?probe=2ce0b2ff35) | Jul 04, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [298e510c05](https://linux-hardware.org/?probe=298e510c05) | Jun 22, 2019 |
| Lenovo        | ThinkPad X230 2324F51       | Notebook    | [9291e8f5f3](https://linux-hardware.org/?probe=9291e8f5f3) | Jun 22, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [70fecd4e42](https://linux-hardware.org/?probe=70fecd4e42) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [ee5c9fcc02](https://linux-hardware.org/?probe=ee5c9fcc02) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [424ee39d57](https://linux-hardware.org/?probe=424ee39d57) | Jun 04, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [37a334e523](https://linux-hardware.org/?probe=37a334e523) | Jun 02, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [cb301afe49](https://linux-hardware.org/?probe=cb301afe49) | Jun 02, 2019 |
| Lenovo        | S10-3                       | Notebook    | [09f132c2fa](https://linux-hardware.org/?probe=09f132c2fa) | May 27, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [24c1251a9a](https://linux-hardware.org/?probe=24c1251a9a) | May 09, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [0f42a3ea73](https://linux-hardware.org/?probe=0f42a3ea73) | May 09, 2019 |
| Daffodil C... | DCL S4                      | Notebook    | [291cd2445c](https://linux-hardware.org/?probe=291cd2445c) | May 08, 2019 |
| HP            | ProBook 4540s               | Notebook    | [a8b0fbe3a8](https://linux-hardware.org/?probe=a8b0fbe3a8) | Apr 22, 2019 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [83303ad448](https://linux-hardware.org/?probe=83303ad448) | Apr 07, 2019 |
| Intel         | Unknown                     | Desktop     | [6abdeb3169](https://linux-hardware.org/?probe=6abdeb3169) | Mar 10, 2019 |
| Intel         | Unknown                     | Desktop     | [d27842b77f](https://linux-hardware.org/?probe=d27842b77f) | Mar 10, 2019 |
| Intel         | Unknown                     | Desktop     | [1c484063a6](https://linux-hardware.org/?probe=1c484063a6) | Mar 09, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| MSI           | P55A-G55                    | Desktop     | [8bc6ce2174](https://linux-hardware.org/?probe=8bc6ce2174) | Dec 08, 2018 |
| MSI           | P55A-G55                    | Desktop     | [24654f4990](https://linux-hardware.org/?probe=24654f4990) | Dec 07, 2018 |
| Gigabyte      | P55-USB3                    | Desktop     | [3cf949c024](https://linux-hardware.org/?probe=3cf949c024) | Jul 21, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 45        | 19.48%  |
| Ubuntu 18.04                 | 11        | 4.76%   |
| Arch                         | 11        | 4.76%   |
| ArcoLinux Rolling            | 9         | 3.9%    |
| Ubuntu 19.10                 | 8         | 3.46%   |
| Manjaro                      | 6         | 2.6%    |
| KDE neon 20.04               | 6         | 2.6%    |
| OpenMandriva 4.2             | 5         | 2.16%   |
| Fedora 33                    | 5         | 2.16%   |
| Debian 11                    | 5         | 2.16%   |
| Zorin 16                     | 4         | 1.73%   |
| Zorin 15                     | 4         | 1.73%   |
| Manjaro 20.0.1               | 4         | 1.73%   |
| Linux Mint 20.2              | 4         | 1.73%   |
| Ubuntu 22.04                 | 3         | 1.3%    |
| Ubuntu 19.04                 | 3         | 1.3%    |
| Pop!_OS 21.10                | 3         | 1.3%    |
| Pop!_OS 21.04                | 3         | 1.3%    |
| Manjaro 20.1.2               | 3         | 1.3%    |
| Linux Mint 20.1              | 3         | 1.3%    |
| Linux Mint 20                | 3         | 1.3%    |
| Kubuntu 20.04                | 3         | 1.3%    |
| Arch Rolling                 | 3         | 1.3%    |
| Ubuntu 21.04                 | 2         | 0.87%   |
| Ubuntu 20.10                 | 2         | 0.87%   |
| Ubuntu 18.10                 | 2         | 0.87%   |
| Ubuntu 16.04                 | 2         | 0.87%   |
| Pop!_OS 20.10                | 2         | 0.87%   |
| OpenMandriva 4.3             | 2         | 0.87%   |
| Manjaro 21.2.6               | 2         | 0.87%   |
| Manjaro 21.0.3               | 2         | 0.87%   |
| Manjaro 18.0.4               | 2         | 0.87%   |
| LMDE 4                       | 2         | 0.87%   |
| Fedora 34                    | 2         | 0.87%   |
| Fedora 32                    | 2         | 0.87%   |
| CentOS 8                     | 2         | 0.87%   |
| BlackPanther 18.1            | 2         | 0.87%   |
| Void Linux Rolling           | 1         | 0.43%   |
| Void Linux                   | 1         | 0.43%   |
| Ubuntu MATE 18.04            | 1         | 0.43%   |
| Ubuntu 21.10                 | 1         | 0.43%   |
| Ubuntu 17.10                 | 1         | 0.43%   |
| ROSA R9                      | 1         | 0.43%   |
| Pragma                       | 1         | 0.43%   |
| Pop!_OS 20.04                | 1         | 0.43%   |
| Parrot 4.5                   | 1         | 0.43%   |
| Parrot 4.11                  | 1         | 0.43%   |
| Parrot 4.10                  | 1         | 0.43%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.43%   |
| Manjaro 21.2.5               | 1         | 0.43%   |
| Manjaro 21.2.1               | 1         | 0.43%   |
| Manjaro 21.1.2               | 1         | 0.43%   |
| Manjaro 21.1.0               | 1         | 0.43%   |
| Manjaro 21.0.5               | 1         | 0.43%   |
| Manjaro 21.0.4               | 1         | 0.43%   |
| Manjaro 21.0                 | 1         | 0.43%   |
| Manjaro 20.2.1               | 1         | 0.43%   |
| Manjaro 20.2                 | 1         | 0.43%   |
| Manjaro 20.1.1               | 1         | 0.43%   |
| Manjaro 20.1                 | 1         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 78        | 36.62%  |
| Manjaro      | 24        | 11.27%  |
| Arch         | 14        | 6.57%   |
| Linux Mint   | 12        | 5.63%   |
| Fedora       | 9         | 4.23%   |
| ArcoLinux    | 9         | 4.23%   |
| Zorin        | 8         | 3.76%   |
| Pop!_OS      | 7         | 3.29%   |
| OpenMandriva | 7         | 3.29%   |
| Kubuntu      | 7         | 3.29%   |
| KDE neon     | 6         | 2.82%   |
| Debian       | 6         | 2.82%   |
| Endless      | 4         | 1.88%   |
| Parrot       | 2         | 0.94%   |
| LMDE         | 2         | 0.94%   |
| Deepin       | 2         | 0.94%   |
| CentOS       | 2         | 0.94%   |
| BlackPanther | 2         | 0.94%   |
| Void Linux   | 1         | 0.47%   |
| Ubuntu MATE  | 1         | 0.47%   |
| ROSA         | 1         | 0.47%   |
| Pragma       | 1         | 0.47%   |
| openSUSE     | 1         | 0.47%   |
| Kali         | 1         | 0.47%   |
| Gentoo       | 1         | 0.47%   |
| EndeavourOS  | 1         | 0.47%   |
| Elementary   | 1         | 0.47%   |
| Clear Linux  | 1         | 0.47%   |
| Artix        | 1         | 0.47%   |
| Android      | 1         | 0.47%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.4.0-42-generic          | 8         | 3.16%   |
| 5.4.0-52-generic          | 6         | 2.37%   |
| 5.10.14-desktop-1omv4002  | 5         | 1.98%   |
| 5.13.0-28-generic         | 4         | 1.58%   |
| 5.9.16-1-MANJARO          | 3         | 1.19%   |
| 5.8.0-55-generic          | 3         | 1.19%   |
| 5.8.0-41-generic          | 3         | 1.19%   |
| 5.6.11-1-MANJARO          | 3         | 1.19%   |
| 5.4.0-53-generic          | 3         | 1.19%   |
| 5.4.0-40-generic          | 3         | 1.19%   |
| 5.4.0-29-generic          | 3         | 1.19%   |
| 5.11.0-37-generic         | 3         | 1.19%   |
| 5.11.0-16-generic         | 3         | 1.19%   |
| 5.8.16-2-MANJARO          | 2         | 0.79%   |
| 5.8.0-50-generic          | 2         | 0.79%   |
| 5.8.0-44-generic          | 2         | 0.79%   |
| 5.8.0-38-generic          | 2         | 0.79%   |
| 5.8.0-14-generic          | 2         | 0.79%   |
| 5.7.19-2-MANJARO          | 2         | 0.79%   |
| 5.4.8-arch1-1             | 2         | 0.79%   |
| 5.4.0-90-generic          | 2         | 0.79%   |
| 5.4.0-73-generic          | 2         | 0.79%   |
| 5.4.0-47-generic          | 2         | 0.79%   |
| 5.4.0-26-generic          | 2         | 0.79%   |
| 5.4.0-19-generic          | 2         | 0.79%   |
| 5.3.0-40-generic          | 2         | 0.79%   |
| 5.3.0-24-generic          | 2         | 0.79%   |
| 5.3.0-23-generic          | 2         | 0.79%   |
| 5.3.0-18-generic          | 2         | 0.79%   |
| 5.16.7-desktop-1omv4003   | 2         | 0.79%   |
| 5.13.0-51-generic         | 2         | 0.79%   |
| 5.13.0-35-generic         | 2         | 0.79%   |
| 5.11.0-40-generic         | 2         | 0.79%   |
| 5.11.0-27-generic         | 2         | 0.79%   |
| 5.10.52-1-lts             | 2         | 0.79%   |
| 5.10.0-8-amd64            | 2         | 0.79%   |
| 5.10.0-10-amd64           | 2         | 0.79%   |
| 5.0.0-32-generic          | 2         | 0.79%   |
| 5.0.0-25-generic          | 2         | 0.79%   |
| 4.15.0-47-generic         | 2         | 0.79%   |
| 4.15.0-42-generic         | 2         | 0.79%   |
| 6.0.0-Phaco-g8f10ff49057f | 1         | 0.4%    |
| 5.9.16-200.fc33.x86_64    | 1         | 0.4%    |
| 5.9.11-200.fc33.x86_64    | 1         | 0.4%    |
| 5.8.6-1-MANJARO           | 1         | 0.4%    |
| 5.8.4-200.fc32.x86_64     | 1         | 0.4%    |
| 5.8.16.a-1-hardened       | 1         | 0.4%    |
| 5.8.16-300.fc33.x86_64    | 1         | 0.4%    |
| 5.8.12-1-default          | 1         | 0.4%    |
| 5.8.0-7630-generic        | 1         | 0.4%    |
| 5.8.0-63-generic          | 1         | 0.4%    |
| 5.8.0-43-generic          | 1         | 0.4%    |
| 5.8.0-40-generic          | 1         | 0.4%    |
| 5.7.17-200.fc32.x86_64    | 1         | 0.4%    |
| 5.7.15-ck                 | 1         | 0.4%    |
| 5.7.0-2parrot2-amd64      | 1         | 0.4%    |
| 5.6.15-1-MANJARO          | 1         | 0.4%    |
| 5.6.14-desktop-2bP        | 1         | 0.4%    |
| 5.4.81-1-lts              | 1         | 0.4%    |
| 5.4.70-amd64-desktop      | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 39        | 16.39%  |
| 5.8.0   | 18        | 7.56%   |
| 5.11.0  | 17        | 7.14%   |
| 5.13.0  | 16        | 6.72%   |
| 5.3.0   | 13        | 5.46%   |
| 5.10.0  | 7         | 2.94%   |
| 5.0.0   | 7         | 2.94%   |
| 4.18.0  | 7         | 2.94%   |
| 4.15.0  | 7         | 2.94%   |
| 5.10.14 | 5         | 2.1%    |
| 5.9.16  | 4         | 1.68%   |
| 5.8.16  | 4         | 1.68%   |
| 5.15.0  | 4         | 1.68%   |
| 4.19.0  | 4         | 1.68%   |
| 5.6.11  | 3         | 1.26%   |
| 5.7.19  | 2         | 0.84%   |
| 5.4.8   | 2         | 0.84%   |
| 5.16.7  | 2         | 0.84%   |
| 5.16.15 | 2         | 0.84%   |
| 5.16.11 | 2         | 0.84%   |
| 5.15.7  | 2         | 0.84%   |
| 5.15.5  | 2         | 0.84%   |
| 5.15.13 | 2         | 0.84%   |
| 5.11.6  | 2         | 0.84%   |
| 5.10.52 | 2         | 0.84%   |
| 6.0.0   | 1         | 0.42%   |
| 5.9.11  | 1         | 0.42%   |
| 5.8.6   | 1         | 0.42%   |
| 5.8.4   | 1         | 0.42%   |
| 5.8.12  | 1         | 0.42%   |
| 5.7.17  | 1         | 0.42%   |
| 5.7.15  | 1         | 0.42%   |
| 5.7.0   | 1         | 0.42%   |
| 5.6.15  | 1         | 0.42%   |
| 5.6.14  | 1         | 0.42%   |
| 5.4.81  | 1         | 0.42%   |
| 5.4.70  | 1         | 0.42%   |
| 5.4.68  | 1         | 0.42%   |
| 5.4.64  | 1         | 0.42%   |
| 5.4.40  | 1         | 0.42%   |
| 5.4.15  | 1         | 0.42%   |
| 5.18.6  | 1         | 0.42%   |
| 5.17.9  | 1         | 0.42%   |
| 5.17.5  | 1         | 0.42%   |
| 5.17.4  | 1         | 0.42%   |
| 5.17.0  | 1         | 0.42%   |
| 5.16.20 | 1         | 0.42%   |
| 5.16.14 | 1         | 0.42%   |
| 5.16.13 | 1         | 0.42%   |
| 5.16.12 | 1         | 0.42%   |
| 5.16.1  | 1         | 0.42%   |
| 5.16.0  | 1         | 0.42%   |
| 5.15.8  | 1         | 0.42%   |
| 5.15.6  | 1         | 0.42%   |
| 5.15.41 | 1         | 0.42%   |
| 5.15.38 | 1         | 0.42%   |
| 5.15.28 | 1         | 0.42%   |
| 5.15.21 | 1         | 0.42%   |
| 5.15.15 | 1         | 0.42%   |
| 5.15.12 | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 46        | 20%     |
| 5.8     | 25        | 10.87%  |
| 5.11    | 22        | 9.57%   |
| 5.10    | 19        | 8.26%   |
| 5.13    | 18        | 7.83%   |
| 5.15    | 17        | 7.39%   |
| 5.3     | 13        | 5.65%   |
| 5.16    | 11        | 4.78%   |
| 4.18    | 8         | 3.48%   |
| 5.0     | 7         | 3.04%   |
| 4.15    | 7         | 3.04%   |
| 5.9     | 5         | 2.17%   |
| 5.7     | 5         | 2.17%   |
| 5.6     | 5         | 2.17%   |
| 4.19    | 5         | 2.17%   |
| 5.17    | 4         | 1.74%   |
| 5.14    | 3         | 1.3%    |
| 5.12    | 2         | 0.87%   |
| 5.1     | 2         | 0.87%   |
| 6.0     | 1         | 0.43%   |
| 5.18    | 1         | 0.43%   |
| 4.9     | 1         | 0.43%   |
| 4.4     | 1         | 0.43%   |
| 4.13    | 1         | 0.43%   |
| 3.18    | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 199       | 97.07%  |
| i686    | 4         | 1.95%   |
| aarch64 | 2         | 0.98%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 104       | 48.37%  |
| KDE5            | 40        | 18.6%   |
| Unknown         | 28        | 13.02%  |
| X-Cinnamon      | 12        | 5.58%   |
| XFCE            | 8         | 3.72%   |
| awesome         | 5         | 2.33%   |
| KDE             | 4         | 1.86%   |
| MATE            | 3         | 1.4%    |
| i3-with-shmlog  | 2         | 0.93%   |
| Deepin          | 2         | 0.93%   |
| Unity           | 1         | 0.47%   |
| Pantheon        | 1         | 0.47%   |
| i3              | 1         | 0.47%   |
| GNOME Flashback | 1         | 0.47%   |
| DWM             | 1         | 0.47%   |
| Cinnamon        | 1         | 0.47%   |
| bspwm           | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 173       | 80.84%  |
| Wayland | 23        | 10.75%  |
| Unknown | 16        | 7.48%   |
| Tty     | 2         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 113       | 52.8%   |
| GDM     | 37        | 17.29%  |
| SDDM    | 31        | 14.49%  |
| LightDM | 13        | 6.07%   |
| GDM3    | 11        | 5.14%   |
| TDM     | 9         | 4.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 167       | 79.9%   |
| Unknown | 28        | 13.4%   |
| en_GB   | 7         | 3.35%   |
| C       | 5         | 2.39%   |
| en_IE   | 1         | 0.48%   |
| en_CA   | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 110       | 51.4%   |
| BIOS | 104       | 48.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 169       | 80.48%  |
| Overlay | 18        | 8.57%   |
| Btrfs   | 14        | 6.67%   |
| Unknown | 5         | 2.38%   |
| Xfs     | 3         | 1.43%   |
| Zfs     | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 123       | 58.02%  |
| GPT     | 70        | 33.02%  |
| MBR     | 19        | 8.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 173       | 81.99%  |
| Yes       | 38        | 18.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 113       | 53.55%  |
| Yes       | 98        | 46.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 49        | 23.9%   |
| Hewlett-Packard             | 39        | 19.02%  |
| MSI                         | 21        | 10.24%  |
| Gigabyte Technology         | 18        | 8.78%   |
| Lenovo                      | 16        | 7.8%    |
| Dell                        | 16        | 7.8%    |
| Acer                        | 13        | 6.34%   |
| Unknown                     | 7         | 3.41%   |
| ASRock                      | 5         | 2.44%   |
| Notebook                    | 4         | 1.95%   |
| Intel                       | 4         | 1.95%   |
| OEM                         | 3         | 1.46%   |
| Foxconn                     | 2         | 0.98%   |
| Biostar                     | 2         | 0.98%   |
| SYS                         | 1         | 0.49%   |
| Samsung Electronics         | 1         | 0.49%   |
| Raspberry Pi Foundation     | 1         | 0.49%   |
| I-Life Digital Technologies | 1         | 0.49%   |
| Daffodil Computers          | 1         | 0.49%   |
| Apple                       | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 9         | 4.39%   |
| HP ProBook 450 G4                                     | 5         | 2.44%   |
| MSI MS-7C52                                           | 4         | 1.95%   |
| ASUS All Series                                       | 3         | 1.46%   |
| OEM Intel H81                                         | 2         | 0.98%   |
| MSI MS-7B89                                           | 2         | 0.98%   |
| MSI MS-7788                                           | 2         | 0.98%   |
| MSI MS-7668                                           | 2         | 0.98%   |
| Intel DG41RQ AAE54511-203                             | 2         | 0.98%   |
| HP ProBook 450 G2                                     | 2         | 0.98%   |
| HP Notebook                                           | 2         | 0.98%   |
| HP EliteBook 840 G3                                   | 2         | 0.98%   |
| ASUS X510UQ                                           | 2         | 0.98%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                | 2         | 0.98%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA                | 2         | 0.98%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA                | 2         | 0.98%   |
| ASUS VivoBook 14_ASUS Laptop X407UA                   | 2         | 0.98%   |
| SYS H310CH5-TI2                                       | 1         | 0.49%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.49%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                    | 1         | 0.49%   |
| Notebook W9x0LU                                       | 1         | 0.49%   |
| Notebook N750BU                                       | 1         | 0.49%   |
| Notebook N2x0LU                                       | 1         | 0.49%   |
| Notebook DCL C483                                     | 1         | 0.49%   |
| MSI Summit B14 A11MOT                                 | 1         | 0.49%   |
| MSI MS-7C91                                           | 1         | 0.49%   |
| MSI MS-7C88                                           | 1         | 0.49%   |
| MSI MS-7C08                                           | 1         | 0.49%   |
| MSI MS-7B79                                           | 1         | 0.49%   |
| MSI MS-7823                                           | 1         | 0.49%   |
| MSI MS-7721                                           | 1         | 0.49%   |
| MSI MS-7673                                           | 1         | 0.49%   |
| MSI MS-7640                                           | 1         | 0.49%   |
| MSI KY722AA-AB4 CQ3012L                               | 1         | 0.49%   |
| MSI GS63 7RD                                          | 1         | 0.49%   |
| Lenovo V330-14IKB 81B0                                | 1         | 0.49%   |
| Lenovo ThinkPad X230 2324F51                          | 1         | 0.49%   |
| Lenovo ThinkPad X230 2324A82                          | 1         | 0.49%   |
| Lenovo ThinkPad T450 20BUS2021M                       | 1         | 0.49%   |
| Lenovo ThinkPad T430s 2356GPU                         | 1         | 0.49%   |
| Lenovo ThinkPad L380 20M6S22500                       | 1         | 0.49%   |
| Lenovo ThinkPad E490 20N9S1XE00                       | 1         | 0.49%   |
| Lenovo ThinkPad E470 20H1A029SG                       | 1         | 0.49%   |
| Lenovo S10-3                                          | 1         | 0.49%   |
| Lenovo Legion 5 15ARH05H 82B1                         | 1         | 0.49%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                      | 1         | 0.49%   |
| Lenovo IdeaPad 330-15IKB 81DE                         | 1         | 0.49%   |
| Lenovo IdeaPad 320-15IKB 81BG                         | 1         | 0.49%   |
| Lenovo IdeaPad 320-15IKB 80XL                         | 1         | 0.49%   |
| Lenovo IdeaPad 310-14ISK 80SL                         | 1         | 0.49%   |
| Lenovo IdeaPad 110-15IBR 80T7                         | 1         | 0.49%   |
| Intel DG31PR AAD97573-302                             | 1         | 0.49%   |
| I-Life Digital ZED_AIR_PLUS                           | 1         | 0.49%   |
| HP ZHAN 66 Pro A 14 G4 Notebook PC                    | 1         | 0.49%   |
| HP ProBook 4540s                                      | 1         | 0.49%   |
| HP ProBook 450 G8 Notebook PC                         | 1         | 0.49%   |
| HP ProBook 450 G5                                     | 1         | 0.49%   |
| HP ProBook 450 G1                                     | 1         | 0.49%   |
| HP ProBook 440 G8 Notebook PC                         | 1         | 0.49%   |
| HP ProBook 440 G7                                     | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS VivoBook      | 17        | 8.29%   |
| HP ProBook         | 15        | 7.32%   |
| Acer Aspire        | 11        | 5.37%   |
| Unknown            | 9         | 4.39%   |
| Dell Inspiron      | 8         | 3.9%    |
| Lenovo ThinkPad    | 7         | 3.41%   |
| Lenovo IdeaPad     | 6         | 2.93%   |
| HP EliteBook       | 6         | 2.93%   |
| Dell Latitude      | 6         | 2.93%   |
| MSI MS-7C52        | 4         | 1.95%   |
| ASUS TUF           | 3         | 1.46%   |
| ASUS All           | 3         | 1.46%   |
| OEM Intel          | 2         | 0.98%   |
| MSI MS-7B89        | 2         | 0.98%   |
| MSI MS-7788        | 2         | 0.98%   |
| MSI MS-7668        | 2         | 0.98%   |
| Intel DG41RQ       | 2         | 0.98%   |
| HP Pavilion        | 2         | 0.98%   |
| HP Notebook        | 2         | 0.98%   |
| HP Laptop          | 2         | 0.98%   |
| HP ENVY            | 2         | 0.98%   |
| HP Compaq          | 2         | 0.98%   |
| HP 15              | 2         | 0.98%   |
| ASUS ZenBook       | 2         | 0.98%   |
| ASUS X510UQ        | 2         | 0.98%   |
| SYS H310CH5-TI2    | 1         | 0.49%   |
| Samsung 300E5EV    | 1         | 0.49%   |
| RPi Raspberry      | 1         | 0.49%   |
| Notebook W9x0LU    | 1         | 0.49%   |
| Notebook N750BU    | 1         | 0.49%   |
| Notebook N2x0LU    | 1         | 0.49%   |
| Notebook DCL       | 1         | 0.49%   |
| MSI Summit         | 1         | 0.49%   |
| MSI MS-7C91        | 1         | 0.49%   |
| MSI MS-7C88        | 1         | 0.49%   |
| MSI MS-7C08        | 1         | 0.49%   |
| MSI MS-7B79        | 1         | 0.49%   |
| MSI MS-7823        | 1         | 0.49%   |
| MSI MS-7721        | 1         | 0.49%   |
| MSI MS-7673        | 1         | 0.49%   |
| MSI MS-7640        | 1         | 0.49%   |
| MSI KY722AA-AB4    | 1         | 0.49%   |
| MSI GS63           | 1         | 0.49%   |
| Lenovo V330-14IKB  | 1         | 0.49%   |
| Lenovo S10-3       | 1         | 0.49%   |
| Lenovo Legion      | 1         | 0.49%   |
| Intel DG31PR       | 1         | 0.49%   |
| I-Life Digital ZED | 1         | 0.49%   |
| HP ZHAN            | 1         | 0.49%   |
| HP Mini            | 1         | 0.49%   |
| HP Elite           | 1         | 0.49%   |
| HP 250             | 1         | 0.49%   |
| HP 240             | 1         | 0.49%   |
| HP 14              | 1         | 0.49%   |
| Gigabyte X299      | 1         | 0.49%   |
| Gigabyte P55-USB3  | 1         | 0.49%   |
| Gigabyte H81M-S    | 1         | 0.49%   |
| Gigabyte H61M-S2PV | 1         | 0.49%   |
| Gigabyte GA-E350N  | 1         | 0.49%   |
| Gigabyte G41M-ES2L | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 28        | 13.66%  |
| 2017    | 27        | 13.17%  |
| 2018    | 25        | 12.2%   |
| 2016    | 25        | 12.2%   |
| 2012    | 20        | 9.76%   |
| 2015    | 19        | 9.27%   |
| 2013    | 12        | 5.85%   |
| 2014    | 11        | 5.37%   |
| 2020    | 8         | 3.9%    |
| 2011    | 8         | 3.9%    |
| 2021    | 7         | 3.41%   |
| 2010    | 6         | 2.93%   |
| 2009    | 4         | 1.95%   |
| 2008    | 3         | 1.46%   |
| Unknown | 2         | 0.98%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 127       | 61.95%  |
| Desktop        | 73        | 35.61%  |
| Convertible    | 2         | 0.98%   |
| Phone          | 1         | 0.49%   |
| System on chip | 1         | 0.49%   |
| Tablet         | 1         | 0.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 192       | 92.31%  |
| Enabled  | 16        | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 205       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 76        | 36.02%  |
| 3.01-4.0   | 59        | 27.96%  |
| 8.01-16.0  | 34        | 16.11%  |
| 16.01-24.0 | 26        | 12.32%  |
| 1.01-2.0   | 11        | 5.21%   |
| 32.01-64.0 | 3         | 1.42%   |
| 2.01-3.0   | 1         | 0.47%   |
| 0.51-1.0   | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 87        | 37.66%  |
| 2.01-3.0  | 76        | 32.9%   |
| 3.01-4.0  | 28        | 12.12%  |
| 4.01-8.0  | 22        | 9.52%   |
| 0.51-1.0  | 11        | 4.76%   |
| 8.01-16.0 | 4         | 1.73%   |
| 0.01-0.5  | 3         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 133       | 63.64%  |
| 2      | 63        | 30.14%  |
| 3      | 11        | 5.26%   |
| 5      | 1         | 0.48%   |
| 4      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 141       | 68.12%  |
| Yes       | 66        | 31.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 173       | 83.98%  |
| No        | 33        | 16.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 74.64%  |
| No        | 53        | 25.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 58.65%  |
| No        | 86        | 41.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Bangladesh | 205       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Dhaka             | 128       | 59.26%  |
| Chittagong        | 14        | 6.48%   |
| Rajshahi          | 8         | 3.7%    |
| Jessore           | 8         | 3.7%    |
| Tongi             | 6         | 2.78%   |
| Comilla           | 5         | 2.31%   |
| Pabna             | 3         | 1.39%   |
| Narayanganj       | 3         | 1.39%   |
| Mirpur            | 3         | 1.39%   |
| Azimpur           | 3         | 1.39%   |
| Wari              | 2         | 0.93%   |
| Sherpur           | 2         | 0.93%   |
| Khulna            | 2         | 0.93%   |
| Feni              | 2         | 0.93%   |
| Bogra             | 2         | 0.93%   |
| Uttara            | 1         | 0.46%   |
| Sylhet            | 1         | 0.46%   |
| Savar Upazila     | 1         | 0.46%   |
| Rangpur City      | 1         | 0.46%   |
| Pirganj           | 1         | 0.46%   |
| Patnitala         | 1         | 0.46%   |
| Paltan            | 1         | 0.46%   |
| Pabna Sadar       | 1         | 0.46%   |
| N????r????yanganj | 1         | 0.46%   |
| Nilphamari        | 1         | 0.46%   |
| Narsingdi         | 1         | 0.46%   |
| Nalitabari        | 1         | 0.46%   |
| N??garpur         | 1         | 0.46%   |
| Mymensingh        | 1         | 0.46%   |
| L????ksh????m     | 1         | 0.46%   |
| Jamalpur          | 1         | 0.46%   |
| Hurua             | 1         | 0.46%   |
| Gulshan           | 1         | 0.46%   |
| Faridpur          | 1         | 0.46%   |
| Dinajpur          | 1         | 0.46%   |
| Dewangonj         | 1         | 0.46%   |
| Chhatak           | 1         | 0.46%   |
| Chhagalnaiya      | 1         | 0.46%   |
| Brahmanbaria      | 1         | 0.46%   |
| Belkuchi          | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 58        | 82     | 20.57%  |
| Seagate             | 49        | 63     | 17.38%  |
| Toshiba             | 47        | 58     | 16.67%  |
| Samsung Electronics | 21        | 32     | 7.45%   |
| Transcend           | 18        | 19     | 6.38%   |
| Hitachi             | 11        | 14     | 3.9%    |
| HGST                | 10        | 10     | 3.55%   |
| SanDisk             | 8         | 8      | 2.84%   |
| A-DATA Technology   | 6         | 7      | 2.13%   |
| Micron Technology   | 4         | 4      | 1.42%   |
| Corsair             | 4         | 6      | 1.42%   |
| SK hynix            | 3         | 3      | 1.06%   |
| Silicon Motion      | 3         | 7      | 1.06%   |
| Phison              | 3         | 3      | 1.06%   |
| Kingston            | 3         | 4      | 1.06%   |
| Intel               | 3         | 4      | 1.06%   |
| Hewlett-Packard     | 3         | 3      | 1.06%   |
| Unknown             | 2         | 3      | 0.71%   |
| TwinMOS             | 2         | 2      | 0.71%   |
| Teutons             | 2         | 6      | 0.71%   |
| PNY                 | 2         | 2      | 0.71%   |
| KingSpec            | 2         | 2      | 0.71%   |
| HS-SSD-E100         | 2         | 3      | 0.71%   |
| Unknown             | 2         | 3      | 0.71%   |
| WDC WDS4            | 1         | 1      | 0.35%   |
| Team                | 1         | 1      | 0.35%   |
| Ramsta              | 1         | 1      | 0.35%   |
| Phison Electronics  | 1         | 1      | 0.35%   |
| Patriot             | 1         | 1      | 0.35%   |
| OCZ                 | 1         | 1      | 0.35%   |
| Lexar               | 1         | 2      | 0.35%   |
| KingFast            | 1         | 1      | 0.35%   |
| Gigabyte Technology | 1         | 2      | 0.35%   |
| Crucial             | 1         | 2      | 0.35%   |
| Colorful            | 1         | 1      | 0.35%   |
| China               | 1         | 1      | 0.35%   |
| BIWIN               | 1         | 1      | 0.35%   |
| Apacer              | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 15        | 5.14%   |
| Toshiba MQ04ABF100 1TB               | 14        | 4.79%   |
| Toshiba DT01ACA100 1TB               | 9         | 3.08%   |
| Seagate ST500DM002-1BD142 500GB      | 7         | 2.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 6         | 2.05%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 5         | 1.71%   |
| WDC WD10JPVX-60JC3T0 1TB             | 5         | 1.71%   |
| Toshiba HDWD110 1TB                  | 5         | 1.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 1.71%   |
| Seagate ST1000DM010-2EP102 1TB       | 5         | 1.71%   |
| Toshiba MQ01ABD100 1TB               | 4         | 1.37%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 3         | 1.03%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 3         | 1.03%   |
| WDC WD10JPVX-60JC3T1 1TB             | 3         | 1.03%   |
| WDC WD10EZEX-60WN4A0 1TB             | 3         | 1.03%   |
| Transcend TS256GSSD230S 256GB        | 3         | 1.03%   |
| Transcend TS120GMTS420S 120GB SSD    | 3         | 1.03%   |
| Toshiba DT01ACA200 2TB               | 3         | 1.03%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 1.03%   |
| Samsung HD502HJ 500GB                | 3         | 1.03%   |
| Intel NVMe SSD Drive 512GB           | 3         | 1.03%   |
| HGST HTS541010A9E680 1TB             | 3         | 1.03%   |
| Corsair Force MP510 240GB            | 3         | 1.03%   |
| A-DATA SU650 240GB SSD               | 3         | 1.03%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 0.68%   |
| WDC WD40PURX-64N96Y0 4TB             | 2         | 0.68%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 0.68%   |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 0.68%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2         | 0.68%   |
| WDC WD10EZEX-00BN5A0 1TB             | 2         | 0.68%   |
| WDC WD SSD 120GB                     | 2         | 0.68%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 2         | 0.68%   |
| Transcend TS240GSSD220S 240GB        | 2         | 0.68%   |
| Transcend TS240GMTS820S 240GB SSD    | 2         | 0.68%   |
| Transcend TS128GSSD370S 128GB        | 2         | 0.68%   |
| Transcend TS120GSSD220S 120GB        | 2         | 0.68%   |
| Toshiba THNSNK128GVN8 128GB SSD      | 2         | 0.68%   |
| Silicon Motion NVMe SSD Drive 256GB  | 2         | 0.68%   |
| Seagate ST9500325AS 500GB            | 2         | 0.68%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.68%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.68%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.68%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.68%   |
| Samsung SP2504C 250GB                | 2         | 0.68%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.68%   |
| Hitachi HDS721050CLA362 500GB        | 2         | 0.68%   |
| HGST HTS545050A7E680 500GB           | 2         | 0.68%   |
| HGST HTS541010B7E610 1TB             | 2         | 0.68%   |
| HP SSD S700 250GB                    | 2         | 0.68%   |
| Unknown                              | 2         | 0.68%   |
| WDC WDS4 80G2G0B-00EPW0 480GB SSD    | 1         | 0.34%   |
| WDC WDS240GS2G0A-00JH30 240GB SSD    | 1         | 0.34%   |
| WDC WDS240G2G0A 240GB SSD            | 1         | 0.34%   |
| WDC WDS120G2G0B-00EPWP 120GB SSD     | 1         | 0.34%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.34%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.34%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.34%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.34%   |
| WDC WD40EFRX-68WT0N0 4TB             | 1         | 0.34%   |
| WDC WD3200BPVT-60JJ5T0 320GB         | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 63     | 30.06%  |
| Toshiba             | 42        | 52     | 25.77%  |
| WDC                 | 39        | 55     | 23.93%  |
| Samsung Electronics | 12        | 20     | 7.36%   |
| Hitachi             | 11        | 14     | 6.75%   |
| HGST                | 10        | 10     | 6.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 23     | 22.09%  |
| Transcend           | 17        | 18     | 19.77%  |
| Samsung Electronics | 6         | 8      | 6.98%   |
| A-DATA Technology   | 6         | 7      | 6.98%   |
| SanDisk             | 5         | 5      | 5.81%   |
| Micron Technology   | 4         | 4      | 4.65%   |
| Toshiba             | 3         | 4      | 3.49%   |
| Hewlett-Packard     | 3         | 3      | 3.49%   |
| TwinMOS             | 2         | 2      | 2.33%   |
| Teutons             | 2         | 6      | 2.33%   |
| PNY                 | 2         | 2      | 2.33%   |
| KingSpec            | 2         | 2      | 2.33%   |
| HS-SSD-E100         | 2         | 2      | 2.33%   |
| WDC WDS4            | 1         | 1      | 1.16%   |
| Team                | 1         | 1      | 1.16%   |
| SK hynix            | 1         | 1      | 1.16%   |
| Ramsta              | 1         | 1      | 1.16%   |
| Patriot             | 1         | 1      | 1.16%   |
| OCZ                 | 1         | 1      | 1.16%   |
| Kingston            | 1         | 1      | 1.16%   |
| Gigabyte Technology | 1         | 2      | 1.16%   |
| Crucial             | 1         | 2      | 1.16%   |
| Corsair             | 1         | 2      | 1.16%   |
| China               | 1         | 1      | 1.16%   |
| Apacer              | 1         | 1      | 1.16%   |
| Unknown             | 1         | 2      | 1.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 155       | 214    | 56.36%  |
| SSD     | 83        | 103    | 30.18%  |
| NVMe    | 31        | 41     | 11.27%  |
| Unknown | 4         | 4      | 1.45%   |
| MMC     | 2         | 3      | 0.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 186       | 320    | 84.55%  |
| NVMe | 31        | 41     | 14.09%  |
| MMC  | 2         | 3      | 0.91%   |
| SAS  | 1         | 1      | 0.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 123       | 172    | 53.02%  |
| 0.51-1.0   | 97        | 129    | 41.81%  |
| 1.01-2.0   | 8         | 8      | 3.45%   |
| 3.01-4.0   | 2         | 3      | 0.86%   |
| 2.01-3.0   | 1         | 4      | 0.43%   |
| 4.01-10.0  | 1         | 1      | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 64        | 29.09%  |
| 251-500        | 45        | 20.45%  |
| 501-1000       | 42        | 19.09%  |
| 1001-2000      | 23        | 10.45%  |
| 51-100         | 20        | 9.09%   |
| 21-50          | 11        | 5%      |
| 1-20           | 9         | 4.09%   |
| Unknown        | 4         | 1.82%   |
| More than 3000 | 2         | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 81        | 35.84%  |
| 21-50          | 49        | 21.68%  |
| 101-250        | 34        | 15.04%  |
| 51-100         | 31        | 13.72%  |
| 251-500        | 12        | 5.31%   |
| 501-1000       | 10        | 4.42%   |
| 1001-2000      | 4         | 1.77%   |
| Unknown        | 4         | 1.77%   |
| More than 3000 | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 2         | 4      | 6.45%   |
| Seagate ST500DM002-1BD142 500GB                | 2         | 2      | 6.45%   |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 6.45%   |
| WDC WD5000LPCX-22VHAT0 500GB                   | 1         | 1      | 3.23%   |
| WDC WD5000BPVT-22HXZT3 500GB                   | 1         | 1      | 3.23%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 1      | 3.23%   |
| WDC WD10JPVX-60JC3T0 1TB                       | 1         | 2      | 3.23%   |
| WDC WD10JPVT-00MS8T0 1TB                       | 1         | 1      | 3.23%   |
| WDC WD10EZEX-60WN4A0 1TB                       | 1         | 1      | 3.23%   |
| WDC WD10EZEX-22MFCA0 1TB                       | 1         | 1      | 3.23%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 3.23%   |
| Toshiba HDWD110 1TB                            | 1         | 1      | 3.23%   |
| Toshiba DT01ACA200 2TB                         | 1         | 1      | 3.23%   |
| Toshiba DT01ACA100 1TB                         | 1         | 1      | 3.23%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD          | 1         | 1      | 3.23%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 3.23%   |
| Seagate ST3500418AS 500GB                      | 1         | 1      | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 3.23%   |
| Samsung Electronics HM160HI 160GB              | 1         | 1      | 3.23%   |
| Samsung Electronics HD161HJ 160GB              | 1         | 2      | 3.23%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 3.23%   |
| HS-SSD-E100 SSD 128G                           | 1         | 1      | 3.23%   |
| Hitachi HDT725050VLA380 500GB                  | 1         | 1      | 3.23%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 3.23%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 3.23%   |
| Hewlett-Packard SSD S600 240GB                 | 1         | 1      | 3.23%   |
| A-DATA Technology SU650 240GB SSD              | 1         | 2      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 25.81%  |
| Toshiba             | 6         | 8      | 19.35%  |
| Seagate             | 5         | 5      | 16.13%  |
| HGST                | 4         | 4      | 12.9%   |
| Samsung Electronics | 2         | 3      | 6.45%   |
| SK hynix            | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| HS-SSD-E100         | 1         | 1      | 3.23%   |
| Hitachi             | 1         | 1      | 3.23%   |
| Hewlett-Packard     | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 2      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 9      | 30.77%  |
| Toshiba             | 6         | 8      | 23.08%  |
| Seagate             | 5         | 5      | 19.23%  |
| HGST                | 4         | 4      | 15.38%  |
| Samsung Electronics | 2         | 3      | 7.69%   |
| Hitachi             | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 30     | 83.33%  |
| SSD  | 5         | 6      | 16.67%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Computers | Drives | Percent |
|------------------------|-----------|--------|---------|
| Toshiba DT01ACA200 2TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 125       | 207    | 54.82%  |
| Works    | 72        | 121    | 31.58%  |
| Malfunc  | 30        | 36     | 13.16%  |
| Failed   | 1         | 1      | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 171       | 73.39%  |
| AMD                          | 26        | 11.16%  |
| SanDisk                      | 7         | 3%      |
| Phison Electronics           | 7         | 3%      |
| Samsung Electronics          | 4         | 1.72%   |
| Silicon Motion               | 3         | 1.29%   |
| Marvell Technology Group     | 3         | 1.29%   |
| Toshiba America Info Systems | 2         | 0.86%   |
| SK hynix                     | 2         | 0.86%   |
| Kingston Technology Company  | 2         | 0.86%   |
| ASMedia Technology           | 2         | 0.86%   |
| VIA Technologies             | 1         | 0.43%   |
| Unknown                      | 1         | 0.43%   |
| Shenzhen Longsys Electronics | 1         | 0.43%   |
| Biwin Storage Technology     | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 48        | 17.58%  |
| AMD FCH SATA Controller [AHCI mode]                                                     | 19        | 6.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 13        | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 4.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 10        | 3.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10        | 3.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 9         | 3.3%    |
| AMD 400 Series Chipset SATA Controller                                                  | 9         | 3.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 8         | 2.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 7         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 2.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 1.83%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 4         | 1.47%   |
| Phison E12 NVMe Controller                                                              | 4         | 1.47%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4         | 1.47%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 1.1%    |
| Intel SSD 660P Series                                                                   | 3         | 1.1%    |
| AMD FCH SATA Controller D                                                               | 3         | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 0.73%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 2         | 0.73%   |
| Marvell Group 88SE912x IDE Controller                                                   | 2         | 0.73%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 0.73%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 0.73%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 0.73%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.37%   |
| Unknown Non-Volatile memory controller                                                  | 1         | 0.37%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 0.37%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.37%   |
| SK hynix Non-Volatile memory controller                                                 | 1         | 0.37%   |
| SK hynix BC511                                                                          | 1         | 0.37%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1         | 0.37%   |
| Shenzhen Longsys Non-Volatile memory controller                                         | 1         | 0.37%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.37%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.37%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1         | 0.37%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 0.37%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 0.37%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 1         | 0.37%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                        | 1         | 0.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.37%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.37%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1         | 0.37%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1         | 0.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 154       | 66.38%  |
| NVMe | 32        | 13.79%  |
| IDE  | 27        | 11.64%  |
| RAID | 19        | 8.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 175       | 85.37%  |
| AMD    | 28        | 13.66%  |
| ARM    | 2         | 0.98%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 10        | 4.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 3.4%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 7         | 3.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 2.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 2.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 2.43%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 2.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.94%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 1.94%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 4         | 1.94%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 1.94%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 1.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.94%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.46%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.46%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 1.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.46%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 1.46%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.46%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 3         | 1.46%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 3         | 1.46%   |
| Intel Xeon CPU X3440 @ 2.53GHz                | 2         | 0.97%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 2         | 0.97%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 2         | 0.97%   |
| Intel Pentium CPU G3260 @ 3.30GHz             | 2         | 0.97%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 2         | 0.97%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 2         | 0.97%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.97%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 2         | 0.97%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.97%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.97%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.97%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.97%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 2         | 0.97%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz          | 2         | 0.97%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 0.97%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 0.97%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.97%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.49%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1         | 0.49%   |
| Intel Pentium CPU G3240 @ 3.10GHz             | 1         | 0.49%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 1         | 0.49%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.49%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.49%   |
| Intel Core i7-7800X CPU @ 3.50GHz             | 1         | 0.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.49%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1         | 0.49%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.49%   |
| Intel Core i5-8600K CPU @ 3.60GHz             | 1         | 0.49%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1         | 0.49%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 1         | 0.49%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.49%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 0.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.49%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 0.49%   |
| Intel Core i5-4200H CPU @ 2.80GHz             | 1         | 0.49%   |
| Intel Core i5-3550 CPU @ 3.30GHz              | 1         | 0.49%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 80        | 39.02%  |
| Intel Core i3           | 40        | 19.51%  |
| Intel Core i7           | 15        | 7.32%   |
| AMD Ryzen 5             | 15        | 7.32%   |
| Intel Pentium           | 12        | 5.85%   |
| Other                   | 7         | 3.41%   |
| Intel Core 2 Duo        | 7         | 3.41%   |
| Intel Celeron           | 6         | 2.93%   |
| AMD Ryzen 7             | 5         | 2.44%   |
| AMD Ryzen 3             | 4         | 1.95%   |
| Intel Xeon              | 3         | 1.46%   |
| Intel Pentium Dual-Core | 3         | 1.46%   |
| Intel Atom              | 2         | 0.98%   |
| Intel Core 2 Quad       | 1         | 0.49%   |
| ARM AArch64             | 1         | 0.49%   |
| AMD FX                  | 1         | 0.49%   |
| AMD E2                  | 1         | 0.49%   |
| AMD E                   | 1         | 0.49%   |
| AMD A8                  | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 118       | 57.28%  |
| 4       | 66        | 32.04%  |
| 6       | 13        | 6.31%   |
| 8       | 5         | 2.43%   |
| 1       | 2         | 0.97%   |
| 10      | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 204       | 99.51%  |
| Unknown | 1         | 0.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 145       | 70.73%  |
| 1       | 59        | 28.78%  |
| Unknown | 1         | 0.49%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 204       | 99.51%  |
| Unknown        | 1         | 0.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 20.09%  |
| 0x806e9    | 23        | 10.75%  |
| 0x806ea    | 15        | 7.01%   |
| 0x306a9    | 14        | 6.54%   |
| 0x406e3    | 10        | 4.67%   |
| 0x206a7    | 10        | 4.67%   |
| 0x306d4    | 9         | 4.21%   |
| 0x306c3    | 9         | 4.21%   |
| 0x08108109 | 6         | 2.8%    |
| 0x906e9    | 5         | 2.34%   |
| 0x806ec    | 5         | 2.34%   |
| 0x806eb    | 5         | 2.34%   |
| 0x40651    | 5         | 2.34%   |
| 0x1067a    | 5         | 2.34%   |
| 0x406c4    | 4         | 1.87%   |
| 0x806c1    | 3         | 1.4%    |
| 0x706e5    | 3         | 1.4%    |
| 0x106e5    | 3         | 1.4%    |
| 0x10676    | 3         | 1.4%    |
| 0x08701021 | 3         | 1.4%    |
| 0x08108102 | 3         | 1.4%    |
| 0x906eb    | 2         | 0.93%   |
| 0x906ea    | 2         | 0.93%   |
| 0x6fb      | 2         | 0.93%   |
| 0x506e3    | 2         | 0.93%   |
| 0x20652    | 2         | 0.93%   |
| 0x0a50000c | 2         | 0.93%   |
| 0x0810100b | 2         | 0.93%   |
| 0x90672    | 1         | 0.47%   |
| 0x506c9    | 1         | 0.47%   |
| 0x50654    | 1         | 0.47%   |
| 0x406c3    | 1         | 0.47%   |
| 0x30678    | 1         | 0.47%   |
| 0x30661    | 1         | 0.47%   |
| 0x106ca    | 1         | 0.47%   |
| 0x10661    | 1         | 0.47%   |
| 0x08701013 | 1         | 0.47%   |
| 0x08600104 | 1         | 0.47%   |
| 0x08001137 | 1         | 0.47%   |
| 0x06006705 | 1         | 0.47%   |
| 0x06001119 | 1         | 0.47%   |
| 0x05000029 | 1         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 64        | 31.07%  |
| IvyBridge        | 18        | 8.74%   |
| Haswell          | 17        | 8.25%   |
| Skylake          | 16        | 7.77%   |
| SandyBridge      | 13        | 6.31%   |
| Broadwell        | 11        | 5.34%   |
| Zen+             | 10        | 4.85%   |
| Penryn           | 9         | 4.37%   |
| Zen 2            | 7         | 3.4%    |
| Silvermont       | 6         | 2.91%   |
| TigerLake        | 5         | 2.43%   |
| Zen 3            | 4         | 1.94%   |
| Core             | 4         | 1.94%   |
| Zen              | 3         | 1.46%   |
| Nehalem          | 3         | 1.46%   |
| IceLake          | 3         | 1.46%   |
| Westmere         | 2         | 0.97%   |
| Piledriver       | 2         | 0.97%   |
| Bonnell          | 2         | 0.97%   |
| Unknown          | 2         | 0.97%   |
| Goldmont         | 1         | 0.49%   |
| Excavator        | 1         | 0.49%   |
| CometLake        | 1         | 0.49%   |
| Bobcat           | 1         | 0.49%   |
| Alderlake Hybrid | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 161       | 65.98%  |
| Nvidia | 48        | 19.67%  |
| AMD    | 35        | 14.34%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 26        | 10.53%  |
| Intel UHD Graphics 620                                                                   | 15        | 6.07%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 5.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 4.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4.45%   |
| Intel HD Graphics 5500                                                                   | 10        | 4.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 4.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 3.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 2.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 2.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 2.43%   |
| Intel HD Graphics 630                                                                    | 5         | 2.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.02%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 2.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.02%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 1.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.62%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.62%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4         | 1.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.62%   |
| AMD Cezanne                                                                              | 4         | 1.62%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.21%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 1.21%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.21%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.81%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 2         | 0.81%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.81%   |
| AMD Renoir                                                                               | 2         | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.81%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 2         | 0.81%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.81%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.4%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.4%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.4%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 0.4%    |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.4%    |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 0.4%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.4%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.4%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.4%    |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.4%    |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.4%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.4%    |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.4%    |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 0.4%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.4%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.4%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.4%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 0.4%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.4%    |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1         | 0.4%    |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.4%    |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.4%    |
| Intel HD Graphics 500                                                                    | 1         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 126       | 60.87%  |
| Intel + Nvidia | 27        | 13.04%  |
| 1 x AMD        | 24        | 11.59%  |
| 1 x Nvidia     | 17        | 8.21%   |
| Intel + AMD    | 5         | 2.42%   |
| AMD + Nvidia   | 4         | 1.93%   |
| Other          | 2         | 0.97%   |
| 2 x AMD        | 2         | 0.97%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 175       | 83.33%  |
| Proprietary | 26        | 12.38%  |
| Unknown     | 9         | 4.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 148       | 70.48%  |
| 1.01-2.0   | 30        | 14.29%  |
| 3.01-4.0   | 13        | 6.19%   |
| 0.51-1.0   | 8         | 3.81%   |
| 0.01-0.5   | 7         | 3.33%   |
| 7.01-8.0   | 2         | 0.95%   |
| 5.01-6.0   | 2         | 0.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 36        | 16.9%   |
| AU Optronics            | 33        | 15.49%  |
| Chimei Innolux          | 30        | 14.08%  |
| LG Display              | 22        | 10.33%  |
| Samsung Electronics     | 21        | 9.86%   |
| Dell                    | 19        | 8.92%   |
| Goldstar                | 12        | 5.63%   |
| Hewlett-Packard         | 11        | 5.16%   |
| ViewSonic               | 4         | 1.88%   |
| Philips                 | 3         | 1.41%   |
| ASUSTek Computer        | 3         | 1.41%   |
| Ancor Communications    | 3         | 1.41%   |
| MSI                     | 2         | 0.94%   |
| Chi Mei Optoelectronics | 2         | 0.94%   |
| ___                     | 1         | 0.47%   |
| UTV                     | 1         | 0.47%   |
| Unknown                 | 1         | 0.47%   |
| Sony                    | 1         | 0.47%   |
| Sharp                   | 1         | 0.47%   |
| QXS                     | 1         | 0.47%   |
| PANDA                   | 1         | 0.47%   |
| FSR                     | 1         | 0.47%   |
| CND                     | 1         | 0.47%   |
| CHR                     | 1         | 0.47%   |
| Apple                   | 1         | 0.47%   |
| AOC                     | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 8         | 3.67%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6         | 2.75%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 4         | 1.83%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch             | 3         | 1.38%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch            | 3         | 1.38%   |
| Dell SE2219HX DELF10F 1920x1080 476x268mm 21.5-inch                   | 3         | 1.38%   |
| Dell S2240L DELD054 1920x1080 476x267mm 21.5-inch                     | 3         | 1.38%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 3         | 1.38%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 3         | 1.38%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.38%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch   | 2         | 0.92%   |
| Samsung Electronics S22R35x SAM103A 1920x1080 476x268mm 21.5-inch     | 2         | 0.92%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 0.92%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.92%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 2         | 0.92%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch           | 2         | 0.92%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 2         | 0.92%   |
| Hewlett-Packard v185w HWP2820 1366x768 410x230mm 18.5-inch            | 2         | 0.92%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2         | 0.92%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                     | 2         | 0.92%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 2         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch       | 2         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.92%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 2         | 0.92%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 0.92%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 2         | 0.92%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 0.92%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.92%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 2         | 0.92%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 0.92%   |
| ___ AAA ___1062 1440x900 410x260mm 19.1-inch                          | 1         | 0.46%   |
| ViewSonic VX2276 Series VSC2F32 1920x1080 476x268mm 21.5-inch         | 1         | 0.46%   |
| ViewSonic VX2263 Series VSC692F 1920x1080 476x268mm 21.5-inch         | 1         | 0.46%   |
| ViewSonic VX1951m VSCD627 1600x900 410x260mm 19.1-inch                | 1         | 0.46%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1         | 0.46%   |
| UTV MONITOR UTV0030 1920x1080 580x330mm 26.3-inch                     | 1         | 0.46%   |
| Unknown AAA 1062 1440x900 341x256mm 16.8-inch                         | 1         | 0.46%   |
| Sony TV SNYAB03 1920x1080                                             | 1         | 0.46%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM043E 1600x1200 520x320mm 24.0-inch  | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 267x200mm 13.1-inch   | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM0107 1280x1024 312x234mm 15.4-inch  | 1         | 0.46%   |
| Samsung Electronics SMS16A100 SAM0880 1366x768 344x194mm 15.5-inch    | 1         | 0.46%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch     | 1         | 0.46%   |
| Samsung Electronics S22E390 SAM0C17 1920x1080 477x268mm 21.5-inch     | 1         | 0.46%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch     | 1         | 0.46%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch      | 1         | 0.46%   |
| Samsung Electronics S19B150 SAM0980 1366x768 410x230mm 18.5-inch      | 1         | 0.46%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4751 1366x768 344x194mm 15.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor S22R35x 1920x1080                     | 1         | 0.46%   |
| QXS QUHMINEI185 QXS1850 1366x768 410x230mm 18.5-inch                  | 1         | 0.46%   |
| Philips PHL 226E9Q PHLC17D 1920x1080 476x268mm 21.5-inch              | 1         | 0.46%   |
| Philips 224EL PHLC054 1920x1080 476x268mm 21.5-inch                   | 1         | 0.46%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                    | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 88        | 43.78%  |
| 1920x1080 (FHD)   | 82        | 40.8%   |
| 3840x2160 (4K)    | 7         | 3.48%   |
| 1440x900 (WXGA+)  | 6         | 2.99%   |
| 1600x900 (HD+)    | 4         | 1.99%   |
| 1280x800 (WXGA)   | 2         | 1%      |
| 1280x1024 (SXGA)  | 2         | 1%      |
| 1024x600          | 2         | 1%      |
| 3440x1440         | 1         | 0.5%    |
| 3360x1080         | 1         | 0.5%    |
| 2736x1824         | 1         | 0.5%    |
| 2560x1440 (QHD)   | 1         | 0.5%    |
| 2240x1400         | 1         | 0.5%    |
| 1920x1200 (WUXGA) | 1         | 0.5%    |
| 1024x768 (XGA)    | 1         | 0.5%    |
| Unknown           | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 63        | 29.58%  |
| 13      | 38        | 17.84%  |
| 21      | 32        | 15.02%  |
| 18      | 23        | 10.8%   |
| 14      | 23        | 10.8%   |
| 23      | 6         | 2.82%   |
| 12      | 5         | 2.35%   |
| 19      | 4         | 1.88%   |
| 17      | 4         | 1.88%   |
| Unknown | 3         | 1.41%   |
| 24      | 2         | 0.94%   |
| 11      | 2         | 0.94%   |
| 10      | 2         | 0.94%   |
| 84      | 1         | 0.47%   |
| 72      | 1         | 0.47%   |
| 34      | 1         | 0.47%   |
| 27      | 1         | 0.47%   |
| 20      | 1         | 0.47%   |
| 16      | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 116       | 54.98%  |
| 401-500     | 62        | 29.38%  |
| 201-300     | 18        | 8.53%   |
| 501-600     | 6         | 2.84%   |
| 351-400     | 3         | 1.42%   |
| Unknown     | 3         | 1.42%   |
| 1501-2000   | 2         | 0.95%   |
| 701-800     | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 172       | 89.12%  |
| 16/10   | 11        | 5.7%    |
| 4/3     | 4         | 2.07%   |
| Unknown | 3         | 1.55%   |
| 5/4     | 1         | 0.52%   |
| 3/2     | 1         | 0.52%   |
| 21/9    | 1         | 0.52%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 63        | 29.72%  |
| 81-90          | 54        | 25.47%  |
| 201-250        | 28        | 13.21%  |
| 141-150        | 24        | 11.32%  |
| 151-200        | 14        | 6.6%    |
| 71-80          | 6         | 2.83%   |
| 61-70          | 5         | 2.36%   |
| 131-140        | 4         | 1.89%   |
| Unknown        | 3         | 1.42%   |
| More than 1000 | 2         | 0.94%   |
| 51-60          | 2         | 0.94%   |
| 41-50          | 2         | 0.94%   |
| 251-300        | 2         | 0.94%   |
| 351-500        | 1         | 0.47%   |
| 301-350        | 1         | 0.47%   |
| 111-120        | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 99        | 47.6%   |
| 121-160       | 57        | 27.4%   |
| 51-100        | 42        | 20.19%  |
| 161-240       | 5         | 2.4%    |
| Unknown       | 3         | 1.44%   |
| More than 240 | 1         | 0.48%   |
| 1-50          | 1         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 176       | 84.21%  |
| 2     | 23        | 11%     |
| 0     | 8         | 3.83%   |
| 3     | 2         | 0.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 154       | 50.49%  |
| Intel                             | 75        | 24.59%  |
| Qualcomm Atheros                  | 35        | 11.48%  |
| Ralink Technology                 | 12        | 3.93%   |
| Xiaomi                            | 7         | 2.3%    |
| TP-Link                           | 5         | 1.64%   |
| Broadcom                          | 3         | 0.98%   |
| Ralink                            | 2         | 0.66%   |
| Qualcomm                          | 2         | 0.66%   |
| Sundance Technology Inc / IC Plus | 1         | 0.33%   |
| Samsung Electronics               | 1         | 0.33%   |
| NetGear                           | 1         | 0.33%   |
| MediaTek                          | 1         | 0.33%   |
| HMD Global                        | 1         | 0.33%   |
| Dell                              | 1         | 0.33%   |
| D-Link                            | 1         | 0.33%   |
| ASIX Electronics                  | 1         | 0.33%   |
| Arduino SA                        | 1         | 0.33%   |
| AboCom Systems                    | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 109       | 31.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 8.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 4.32%   |
| Intel Wireless 8265 / 8275                                        | 14        | 4.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 3.46%   |
| Ralink MT7601U Wireless Adapter                                   | 10        | 2.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 2.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 2.02%   |
| Intel Wireless 3165                                               | 7         | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.02%   |
| Intel Wireless 8260                                               | 5         | 1.44%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.44%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.15%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.86%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                 | 3         | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3         | 0.86%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3         | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.86%   |
| Intel Wireless 7265                                               | 3         | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.58%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 2         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.58%   |
| Qualcomm Redmi 9T                                                 | 2         | 0.58%   |
| Intel Wireless 3160                                               | 2         | 0.58%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.58%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.29%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.29%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet             | 1         | 0.29%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.29%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.29%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.29%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.29%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.29%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.29%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1         | 0.29%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1         | 0.29%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.29%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.29%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.29%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.29%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.29%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]               | 1         | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 66        | 40.49%  |
| Qualcomm Atheros      | 35        | 21.47%  |
| Realtek Semiconductor | 33        | 20.25%  |
| Ralink Technology     | 12        | 7.36%   |
| TP-Link               | 5         | 3.07%   |
| Xiaomi                | 3         | 1.84%   |
| Ralink                | 2         | 1.23%   |
| Broadcom              | 2         | 1.23%   |
| NetGear               | 1         | 0.61%   |
| MediaTek              | 1         | 0.61%   |
| Dell                  | 1         | 0.61%   |
| D-Link                | 1         | 0.61%   |
| AboCom Systems        | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 15        | 9.2%    |
| Intel Wireless 8265 / 8275                                                 | 14        | 8.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 12        | 7.36%   |
| Ralink MT7601U Wireless Adapter                                            | 10        | 6.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 10        | 6.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 7         | 4.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 7         | 4.29%   |
| Intel Wireless 3165                                                        | 7         | 4.29%   |
| Intel Wireless 8260                                                        | 5         | 3.07%   |
| Intel Wi-Fi 6 AX201                                                        | 5         | 3.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4         | 2.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 4         | 2.45%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                          | 3         | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 3         | 1.84%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 3         | 1.84%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 3         | 1.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 3         | 1.84%   |
| Intel Wireless 7265                                                        | 3         | 1.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                            | 3         | 1.84%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 2         | 1.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                 | 2         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.23%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                  | 2         | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 2         | 1.23%   |
| Intel Wireless 3160                                                        | 2         | 1.23%   |
| Intel Wi-Fi 6 AX200                                                        | 2         | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                            | 2         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 2         | 1.23%   |
| TP-Link Archer T4U ver.3                                                   | 1         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.61%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                 | 1         | 0.61%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                     | 1         | 0.61%   |
| Realtek RTL8187 Wireless Adapter                                           | 1         | 0.61%   |
| Ralink RT5370 Wireless Adapter                                             | 1         | 0.61%   |
| Ralink RT2501/RT2573 Wireless Adapter                                      | 1         | 0.61%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                | 1         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 0.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1         | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 0.61%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                        | 1         | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 1         | 0.61%   |
| Intel Wireless 7260                                                        | 1         | 0.61%   |
| Intel Ultimate N WiFi Link 5300                                            | 1         | 0.61%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                              | 1         | 0.61%   |
| Intel Centrino Ultimate-N 6300                                             | 1         | 0.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 1         | 0.61%   |
| Dell DW5811e Snapdragon?????? X7 LTE                                       | 1         | 0.61%   |
| D-Link DWA-171                                                             | 1         | 0.61%   |
| Broadcom BCM4331 802.11a/b/g/n                                             | 1         | 0.61%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1         | 0.61%   |
| AboCom Systems AboCom Systems Inc [WN2001 Prolink Wireless-N Nano Adapter] | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 142       | 78.45%  |
| Intel                             | 24        | 13.26%  |
| Xiaomi                            | 4         | 2.21%   |
| Qualcomm Atheros                  | 3         | 1.66%   |
| Qualcomm                          | 2         | 1.1%    |
| Broadcom                          | 2         | 1.1%    |
| Sundance Technology Inc / IC Plus | 1         | 0.55%   |
| Samsung Electronics               | 1         | 0.55%   |
| HMD Global                        | 1         | 0.55%   |
| ASIX Electronics                  | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 109       | 59.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 15.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.83%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 2.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.19%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.64%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.09%   |
| Qualcomm Redmi 9T                                                 | 2         | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.55%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet             | 1         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.55%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.55%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.55%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.55%   |
| HMD Global SDM439-QRD _SN:609DB907                                | 1         | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.55%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 173       | 52.58%  |
| WiFi     | 155       | 47.11%  |
| Modem    | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 129       | 62.93%  |
| Ethernet | 76        | 37.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 104       | 50.73%  |
| 2     | 98        | 47.8%   |
| 0     | 3         | 1.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 204       | 99.51%  |
| Yes  | 1         | 0.49%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 43.09%  |
| IMC Networks                    | 18        | 14.63%  |
| Realtek Semiconductor           | 13        | 10.57%  |
| Qualcomm Atheros Communications | 9         | 7.32%   |
| Lite-On Technology              | 9         | 7.32%   |
| Cambridge Silicon Radio         | 9         | 7.32%   |
| Broadcom                        | 6         | 4.88%   |
| Foxconn / Hon Hai               | 2         | 1.63%   |
| Toshiba                         | 1         | 0.81%   |
| Ralink                          | 1         | 0.81%   |
| Hewlett-Packard                 | 1         | 0.81%   |
| Unknown                         | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 32        | 26.02%  |
| IMC Networks Bluetooth Device                       | 11        | 8.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 8.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 7.32%   |
| Realtek Bluetooth Radio                             | 7         | 5.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 4.88%   |
| IMC Networks Bluetooth Radio                        | 6         | 4.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 3.25%   |
| Intel Bluetooth Device                              | 4         | 3.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 3.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 2.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.63%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.63%   |
| Lite-On Bluetooth Device                            | 2         | 1.63%   |
| Intel AX200 Bluetooth                               | 2         | 1.63%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.63%   |
| Toshiba Bluetooth Radio                             | 1         | 0.81%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.81%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.81%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.81%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.81%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.81%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.81%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.81%   |
| Unknown                                             | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 173       | 71.78%  |
| AMD                    | 35        | 14.52%  |
| Nvidia                 | 21        | 8.71%   |
| Generalplus Technology | 7         | 2.9%    |
| Logitech               | 1         | 0.41%   |
| JMTek                  | 1         | 0.41%   |
| iCreate Technologies   | 1         | 0.41%   |
| Creative Labs          | 1         | 0.41%   |
| C-Media Electronics    | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 54        | 18.69%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 18        | 6.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 5.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 4.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 4.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 3.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 3.81%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 3.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 3.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 3.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.77%   |
| Intel 200 Series PCH HD Audio                                                                     | 7         | 2.42%   |
| Generalplus Technology IMYB 7.1 Channel                                                           | 7         | 2.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.73%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.73%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.73%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.73%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.73%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.38%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.04%   |
| Intel USB PnP Sound Device                                                                        | 3         | 1.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.04%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.69%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.35%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.35%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.35%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Logitech Headset H390                                                                             | 1         | 0.35%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.35%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.35%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.35%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 0.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.35%   |
| iCreate Technologies ASUS BE/C6 webcam series                                                     | 1         | 0.35%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 1         | 0.35%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.35%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.35%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.35%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.35%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.35%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.35%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.35%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1         | 0.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 23.02%  |
| SK hynix            | 25        | 19.84%  |
| Micron Technology   | 11        | 8.73%   |
| Kingston            | 8         | 6.35%   |
| Unknown             | 7         | 5.56%   |
| G.Skill             | 7         | 5.56%   |
| A-DATA Technology   | 7         | 5.56%   |
| Transcend           | 6         | 4.76%   |
| Corsair             | 6         | 4.76%   |
| Team                | 5         | 3.97%   |
| Ramaxel Technology  | 4         | 3.17%   |
| SemsoTai            | 2         | 1.59%   |
| Unknown (C509)      | 1         | 0.79%   |
| Unknown (768A)      | 1         | 0.79%   |
| TwinMOS             | 1         | 0.79%   |
| Ramos Technology    | 1         | 0.79%   |
| Qumo                | 1         | 0.79%   |
| Nanya Technology    | 1         | 0.79%   |
| GeIL                | 1         | 0.79%   |
| Crucial             | 1         | 0.79%   |
| Unknown             | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 3.08%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 4         | 3.08%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 2.31%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 2.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 1.54%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.54%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 2         | 1.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 1.54%   |
| Samsung RAM M471A1K44BM0-CRC 8192MB SODIMM DDR4 2400MT/s            | 2         | 1.54%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 1.54%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 2         | 1.54%   |
| Corsair RAM CMK8GX4M1E3200C16 8GB DIMM DDR4 3200MT/s                | 2         | 1.54%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s                | 2         | 1.54%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                           | 1         | 0.77%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.77%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                         | 1         | 0.77%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.77%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 1         | 0.77%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s                             | 1         | 0.77%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 1         | 0.77%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                             | 1         | 0.77%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                             | 1         | 0.77%   |
| Unknown (C509) RAM Module 4GB SODIMM DDR4 2400MT/s                  | 1         | 0.77%   |
| Unknown (768A) RAM Module 8192MB SODIMM DDR4 3200MT/s               | 1         | 0.77%   |
| TwinMOS RAM 9DEPBMZ8-TATP 2048MB DIMM DDR3 1333MT/s                 | 1         | 0.77%   |
| Transcend RAM TX2133KLN-8GK 4096MB DIMM DDR3 2000MT/s               | 1         | 0.77%   |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s                 | 1         | 0.77%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s                 | 1         | 0.77%   |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s                 | 1         | 0.77%   |
| Transcend RAM JM1600KLN-4GK 2GB DIMM DDR3 1600MT/s                  | 1         | 0.77%   |
| Transcend RAM JM1600KLN-4G 4096MB DIMM DDR3 1600MT/s                | 1         | 0.77%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s                 | 1         | 0.77%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s               | 1         | 0.77%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s               | 1         | 0.77%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s               | 1         | 0.77%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                          | 1         | 0.77%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 1         | 0.77%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s                | 1         | 0.77%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2133MT/s                     | 1         | 0.77%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.77%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.77%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.77%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.77%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.77%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.77%   |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 0.77%   |
| SemsoTai RAM Module 4GB DIMM DDR4 2400MT/s                          | 1         | 0.77%   |
| SemsoTai RAM Module 4GB DIMM DDR3 1600MT/s                          | 1         | 0.77%   |
| SemsoTai RAM Module 4096MB DIMM DDR4 2400MT/s                       | 1         | 0.77%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 0.77%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 0.77%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                      | 1         | 0.77%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 0.77%   |
| Samsung RAM M471B5673DZ1-CF8 2048MB SODIMM DDR3 1067MT/s            | 1         | 0.77%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.77%   |
| Samsung RAM M471A5244BB0-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 0.77%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s               | 1         | 0.77%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 60        | 61.22%  |
| DDR3    | 29        | 29.59%  |
| LPDDR4  | 3         | 3.06%   |
| LPDDR3  | 3         | 3.06%   |
| Unknown | 2         | 2.04%   |
| DDR2    | 1         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 65        | 68.42%  |
| DIMM         | 27        | 28.42%  |
| Row Of Chips | 3         | 3.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 51        | 46.79%  |
| 8192  | 40        | 36.7%   |
| 16384 | 9         | 8.26%   |
| 2048  | 7         | 6.42%   |
| 32768 | 2         | 1.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 26        | 24.07%  |
| 1600  | 23        | 21.3%   |
| 2400  | 14        | 12.96%  |
| 3200  | 13        | 12.04%  |
| 2133  | 10        | 9.26%   |
| 1333  | 4         | 3.7%    |
| 2800  | 3         | 2.78%   |
| 1867  | 3         | 2.78%   |
| 3266  | 2         | 1.85%   |
| 1067  | 2         | 1.85%   |
| 8400  | 1         | 0.93%   |
| 3333  | 1         | 0.93%   |
| 3151  | 1         | 0.93%   |
| 3000  | 1         | 0.93%   |
| 2000  | 1         | 0.93%   |
| 1334  | 1         | 0.93%   |
| 1066  | 1         | 0.93%   |
| 800   | 1         | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L132 Series | 2         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 20.61%  |
| IMC Networks                           | 26        | 19.85%  |
| Cheng Uei Precision Industry (Foxlink) | 14        | 10.69%  |
| Realtek Semiconductor                  | 11        | 8.4%    |
| Quanta                                 | 8         | 6.11%   |
| Sunplus Innovation Technology          | 7         | 5.34%   |
| Acer                                   | 6         | 4.58%   |
| Lite-On Technology                     | 5         | 3.82%   |
| Suyin                                  | 4         | 3.05%   |
| Microdia                               | 4         | 3.05%   |
| Luxvisions Innotech Limited            | 4         | 3.05%   |
| Z-Star Microelectronics                | 2         | 1.53%   |
| Silicon Motion                         | 2         | 1.53%   |
| Primax Electronics                     | 2         | 1.53%   |
| Logitech                               | 2         | 1.53%   |
| Alcor Micro                            | 2         | 1.53%   |
| WCM_USB                                | 1         | 0.76%   |
| Syntek                                 | 1         | 0.76%   |
| SiGma Micro                            | 1         | 0.76%   |
| Apple                                  | 1         | 0.76%   |
| ANYKA                                  | 1         | 0.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 9         | 6.87%   |
| Chicony USB2.0 VGA UVC WebCam                           | 8         | 6.11%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 7         | 5.34%   |
| IMC Networks VGA UVC WebCam                             | 5         | 3.82%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 4         | 3.05%   |
| Luxvisions Innotech Limited HP HD Camera                | 3         | 2.29%   |
| Lite-On HP HD Camera                                    | 3         | 2.29%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 2.29%   |
| Chicony HD WebCam                                       | 3         | 2.29%   |
| Chicony EasyCamera                                      | 3         | 2.29%   |
| Z-Star A4 TECH USB2.0 PC Camera J                       | 2         | 1.53%   |
| Suyin Integrated_Webcam_HD                              | 2         | 1.53%   |
| Suyin HP Truevision HD                                  | 2         | 1.53%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.53%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 1.53%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.53%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.53%   |
| Quanta VGA WebCam                                       | 2         | 1.53%   |
| Quanta HD Webcam                                        | 2         | 1.53%   |
| Primax HP HD Webcam [Fixed]                             | 2         | 1.53%   |
| Logitech Webcam C270                                    | 2         | 1.53%   |
| Lite-On Integrated Camera                               | 2         | 1.53%   |
| IMC Networks Integrated Camera                          | 2         | 1.53%   |
| Chicony USB2.0 Camera                                   | 2         | 1.53%   |
| Chicony Integrated Camera                               | 2         | 1.53%   |
| Chicony HP HD Webcam                                    | 2         | 1.53%   |
| Chicony HP HD Camera                                    | 2         | 1.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.53%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 2         | 1.53%   |
| Acer HD Webcam                                          | 2         | 1.53%   |
| WCM_USB WEB CAM                                         | 1         | 0.76%   |
| Syntek Integrated Camera                                | 1         | 0.76%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.76%   |
| Sunplus Integrated Webcam                               | 1         | 0.76%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.76%   |
| Sunplus Dell HD Webcam                                  | 1         | 0.76%   |
| Sunplus Asus Webcam                                     | 1         | 0.76%   |
| Silicon Motion WebCam SC-10HDD12636N                    | 1         | 0.76%   |
| Silicon Motion Endoscope camera                         | 1         | 0.76%   |
| SiGma Micro WebCam SiGma Micro                          | 1         | 0.76%   |
| Realtek USB Camera                                      | 1         | 0.76%   |
| Realtek Lenovo easy camera                              | 1         | 0.76%   |
| Realtek Integrated_Webcam_FHD                           | 1         | 0.76%   |
| Realtek Integrated Webcam_HD                            | 1         | 0.76%   |
| Realtek HD WebCam                                       | 1         | 0.76%   |
| Quanta HP Webcam                                        | 1         | 0.76%   |
| Quanta HP TrueVision HD Camera                          | 1         | 0.76%   |
| Quanta HP HD Camera                                     | 1         | 0.76%   |
| Quanta HD User Facing                                   | 1         | 0.76%   |
| Microdia Laptop_Integrated_Webcam_0.3M                  | 1         | 0.76%   |
| Microdia Integrated_Webcam_HD                           | 1         | 0.76%   |
| Microdia Integrated Webcam HD                           | 1         | 0.76%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 0.76%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 1         | 0.76%   |
| Chicony WebCam                                          | 1         | 0.76%   |
| Chicony thinkpad t430s camera                           | 1         | 0.76%   |
| Chicony Integrated Camera (1280x720@30)                 | 1         | 0.76%   |
| Chicony HP Webcam-50                                    | 1         | 0.76%   |
| Chicony HP Truevision HD camera                         | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 24        | 82.76%  |
| Synaptics             | 3         | 10.34%  |
| Elan Microelectronics | 2         | 6.9%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 44.83%  |
| Validity Sensors VFS491                                                    | 3         | 10.34%  |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 6.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 6.9%    |
| Elan ELAN:Fingerprint                                                      | 2         | 6.9%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 3.45%   |
| Synaptics  WBDI                                                            | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 40%     |
| Broadcom 5880                                                                | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 148       | 69.48%  |
| 1     | 57        | 26.76%  |
| 2     | 6         | 2.82%   |
| 3     | 2         | 0.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 29        | 42.03%  |
| Graphics card            | 17        | 24.64%  |
| Net/wireless             | 9         | 13.04%  |
| Chipcard                 | 5         | 7.25%   |
| Camera                   | 4         | 5.8%    |
| Multimedia controller    | 2         | 2.9%    |
| Communication controller | 1         | 1.45%   |
| Card reader              | 1         | 1.45%   |
| Bluetooth                | 1         | 1.45%   |

