Kubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Kubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu/Desktop/README.md) and [notebooks](/Dist/Kubuntu/Notebook/README.md).

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

Total: 3804

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550M-K               | Desktop     | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [75362e2061](https://linux-hardware.org/?probe=75362e2061) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [9f7923bcd2](https://linux-hardware.org/?probe=9f7923bcd2) | Apr 29, 2022 |
| HP            | 3396                        | Desktop     | [bd2e5eb69c](https://linux-hardware.org/?probe=bd2e5eb69c) | Apr 29, 2022 |
| HP            | 3396                        | Desktop     | [705baf56a1](https://linux-hardware.org/?probe=705baf56a1) | Apr 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [12a0105da3](https://linux-hardware.org/?probe=12a0105da3) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [3206e0f075](https://linux-hardware.org/?probe=3206e0f075) | Apr 27, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [a7061bdb08](https://linux-hardware.org/?probe=a7061bdb08) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [e77a313003](https://linux-hardware.org/?probe=e77a313003) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [e4ecdec958](https://linux-hardware.org/?probe=e4ecdec958) | Apr 27, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [fa33f58948](https://linux-hardware.org/?probe=fa33f58948) | Apr 27, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [fcd8a2962e](https://linux-hardware.org/?probe=fcd8a2962e) | Apr 26, 2022 |
| HP            | ENVY 17                     | Notebook    | [c33b35becc](https://linux-hardware.org/?probe=c33b35becc) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | Notebook    | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [98251fced6](https://linux-hardware.org/?probe=98251fced6) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [e466d79804](https://linux-hardware.org/?probe=e466d79804) | Apr 26, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [89debf3e0e](https://linux-hardware.org/?probe=89debf3e0e) | Apr 25, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [82c13f2b01](https://linux-hardware.org/?probe=82c13f2b01) | Apr 25, 2022 |
| HP            | 0AACh                       | Desktop     | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| Dell          | Studio 1558                 | Notebook    | [b31435ef0c](https://linux-hardware.org/?probe=b31435ef0c) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [ef1e814871](https://linux-hardware.org/?probe=ef1e814871) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [3ea846ae2a](https://linux-hardware.org/?probe=3ea846ae2a) | Apr 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [9877ddeaf6](https://linux-hardware.org/?probe=9877ddeaf6) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [99e25e855e](https://linux-hardware.org/?probe=99e25e855e) | Apr 23, 2022 |
| Intel         | NUC6CAYB J23203-402         | Mini pc     | [86964dccfd](https://linux-hardware.org/?probe=86964dccfd) | Apr 23, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [848b9d8f5c](https://linux-hardware.org/?probe=848b9d8f5c) | Apr 22, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [da630d58cf](https://linux-hardware.org/?probe=da630d58cf) | Apr 22, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [8ee6cabf43](https://linux-hardware.org/?probe=8ee6cabf43) | Apr 22, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [28690580aa](https://linux-hardware.org/?probe=28690580aa) | Apr 22, 2022 |
| HP            | 2B4B                        | Desktop     | [c3dd8ed52a](https://linux-hardware.org/?probe=c3dd8ed52a) | Apr 22, 2022 |
| ASRock        | Z87 Pro4                    | Desktop     | [0c4cc8712f](https://linux-hardware.org/?probe=0c4cc8712f) | Apr 22, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [8c7c0bd289](https://linux-hardware.org/?probe=8c7c0bd289) | Apr 21, 2022 |
| Dynabook      | PORTEGE X30L-J              | Notebook    | [5894fd3a34](https://linux-hardware.org/?probe=5894fd3a34) | Apr 21, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Positivo      | W940TU                      | Notebook    | [4d03effd28](https://linux-hardware.org/?probe=4d03effd28) | Apr 20, 2022 |
| Positivo      | W940TU                      | Notebook    | [971493b883](https://linux-hardware.org/?probe=971493b883) | Apr 20, 2022 |
| Dell          | Latitude XT3                | Notebook    | [6db9585e20](https://linux-hardware.org/?probe=6db9585e20) | Apr 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [b925b403ca](https://linux-hardware.org/?probe=b925b403ca) | Apr 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [53199db8c8](https://linux-hardware.org/?probe=53199db8c8) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | Notebook    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f8e7d70919](https://linux-hardware.org/?probe=f8e7d70919) | Apr 18, 2022 |
| Shuttle       | FH61V                       | Desktop     | [2fae1ee493](https://linux-hardware.org/?probe=2fae1ee493) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | Notebook    | [4ed718df3e](https://linux-hardware.org/?probe=4ed718df3e) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | Notebook    | [402c31b107](https://linux-hardware.org/?probe=402c31b107) | Apr 18, 2022 |
| ASUSTek       | S551LB                      | Notebook    | [bb1d6d3623](https://linux-hardware.org/?probe=bb1d6d3623) | Apr 17, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ff9197cd63](https://linux-hardware.org/?probe=ff9197cd63) | Apr 17, 2022 |
| Dell          | Latitude XT3                | Notebook    | [c4d7d751b7](https://linux-hardware.org/?probe=c4d7d751b7) | Apr 17, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| Dell          | Latitude 7410               | Notebook    | [da82f8bba8](https://linux-hardware.org/?probe=da82f8bba8) | Apr 15, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [840ffde0c4](https://linux-hardware.org/?probe=840ffde0c4) | Apr 15, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c00611352d](https://linux-hardware.org/?probe=c00611352d) | Apr 15, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [78a785e4a9](https://linux-hardware.org/?probe=78a785e4a9) | Apr 15, 2022 |
| Dell          | Latitude XT3                | Notebook    | [ce6c2e43a0](https://linux-hardware.org/?probe=ce6c2e43a0) | Apr 15, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [f52ef2faf2](https://linux-hardware.org/?probe=f52ef2faf2) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [2ee68b5f38](https://linux-hardware.org/?probe=2ee68b5f38) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [6846ee88e0](https://linux-hardware.org/?probe=6846ee88e0) | Apr 14, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [e172be90b8](https://linux-hardware.org/?probe=e172be90b8) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [45b8eba74c](https://linux-hardware.org/?probe=45b8eba74c) | Apr 14, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [3e09de906e](https://linux-hardware.org/?probe=3e09de906e) | Apr 14, 2022 |
| Lenovo        | ThinkPad T420 41786UU       | Notebook    | [2211278055](https://linux-hardware.org/?probe=2211278055) | Apr 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [4434290159](https://linux-hardware.org/?probe=4434290159) | Apr 14, 2022 |
| Lenovo        | ThinkPad P51 20HH000AUS     | Notebook    | [b7365a4abd](https://linux-hardware.org/?probe=b7365a4abd) | Apr 14, 2022 |
| Samsung       | R425D/R525D                 | Notebook    | [bd5a2f5943](https://linux-hardware.org/?probe=bd5a2f5943) | Apr 14, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [a21bd26d1e](https://linux-hardware.org/?probe=a21bd26d1e) | Apr 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [8888d86504](https://linux-hardware.org/?probe=8888d86504) | Apr 13, 2022 |
| Lenovo        | IdeaPad 710S Plus Touch-... | Notebook    | [f4578ea652](https://linux-hardware.org/?probe=f4578ea652) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [744144c472](https://linux-hardware.org/?probe=744144c472) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [479b8d48fc](https://linux-hardware.org/?probe=479b8d48fc) | Apr 13, 2022 |
| MSI           | Z270 SLI PLUS               | Desktop     | [fa00f6ccd6](https://linux-hardware.org/?probe=fa00f6ccd6) | Apr 13, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [74191e7ffb](https://linux-hardware.org/?probe=74191e7ffb) | Apr 13, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [2d44f4a10b](https://linux-hardware.org/?probe=2d44f4a10b) | Apr 13, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [6c01bb2cc3](https://linux-hardware.org/?probe=6c01bb2cc3) | Apr 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [f74831788b](https://linux-hardware.org/?probe=f74831788b) | Apr 13, 2022 |
| Dell          | Latitude 5591               | Notebook    | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5923be4543](https://linux-hardware.org/?probe=5923be4543) | Apr 13, 2022 |
| Dell          | Latitude 7400               | Notebook    | [2c32d69a57](https://linux-hardware.org/?probe=2c32d69a57) | Apr 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [44035cfa83](https://linux-hardware.org/?probe=44035cfa83) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [db6bf8f1b9](https://linux-hardware.org/?probe=db6bf8f1b9) | Apr 13, 2022 |
| Dell          | Precision 5520              | Notebook    | [eb5bfc87ed](https://linux-hardware.org/?probe=eb5bfc87ed) | Apr 12, 2022 |
| Lenovo        | ThinkPad T430 2349T2A       | Notebook    | [344710cc3a](https://linux-hardware.org/?probe=344710cc3a) | Apr 12, 2022 |
| Dell          | Precision 5520              | Notebook    | [0c7ae3171f](https://linux-hardware.org/?probe=0c7ae3171f) | Apr 12, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [090560f0c5](https://linux-hardware.org/?probe=090560f0c5) | Apr 12, 2022 |
| Dell          | Inspiron 7786               | Convertible | [cdf7aa0cb8](https://linux-hardware.org/?probe=cdf7aa0cb8) | Apr 11, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [c3d5951840](https://linux-hardware.org/?probe=c3d5951840) | Apr 10, 2022 |
| Lenovo        | IdeaPad Z585                | Notebook    | [5f84c70657](https://linux-hardware.org/?probe=5f84c70657) | Apr 10, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [cf76bb9e39](https://linux-hardware.org/?probe=cf76bb9e39) | Apr 10, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [13dff6f000](https://linux-hardware.org/?probe=13dff6f000) | Apr 10, 2022 |
| Dell          | G7 7790                     | Notebook    | [6cdb296d8e](https://linux-hardware.org/?probe=6cdb296d8e) | Apr 10, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [848a486145](https://linux-hardware.org/?probe=848a486145) | Apr 10, 2022 |
| eMachines     | G525                        | Notebook    | [6ba45c519c](https://linux-hardware.org/?probe=6ba45c519c) | Apr 09, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [18045cb759](https://linux-hardware.org/?probe=18045cb759) | Apr 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [272c9f107a](https://linux-hardware.org/?probe=272c9f107a) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| Positivo      | N1250                       | Notebook    | [c64a47d6fc](https://linux-hardware.org/?probe=c64a47d6fc) | Apr 09, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [ea109b146b](https://linux-hardware.org/?probe=ea109b146b) | Apr 08, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [aa210dfd36](https://linux-hardware.org/?probe=aa210dfd36) | Apr 08, 2022 |
| Sony          | SVE1511W1ESI                | Notebook    | [403773664b](https://linux-hardware.org/?probe=403773664b) | Apr 08, 2022 |
| Dell          | Latitude 5480               | Notebook    | [6891954221](https://linux-hardware.org/?probe=6891954221) | Apr 08, 2022 |
| HP            | ENVY 15                     | Notebook    | [cdd8aea3c3](https://linux-hardware.org/?probe=cdd8aea3c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [dea231bf61](https://linux-hardware.org/?probe=dea231bf61) | Apr 07, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b02ac7d8ce](https://linux-hardware.org/?probe=b02ac7d8ce) | Apr 07, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [64c2c15492](https://linux-hardware.org/?probe=64c2c15492) | Apr 05, 2022 |
| HP            | 3047h                       | Desktop     | [6766d428ef](https://linux-hardware.org/?probe=6766d428ef) | Apr 05, 2022 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [ee8ada5124](https://linux-hardware.org/?probe=ee8ada5124) | Apr 05, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [e7576083a0](https://linux-hardware.org/?probe=e7576083a0) | Apr 05, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [f98a0cf73b](https://linux-hardware.org/?probe=f98a0cf73b) | Apr 05, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | Notebook    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6530              | Notebook    | [a63f363043](https://linux-hardware.org/?probe=a63f363043) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| HP            | 805D                        | Desktop     | [198cff1b8e](https://linux-hardware.org/?probe=198cff1b8e) | Apr 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [73ecbc62b1](https://linux-hardware.org/?probe=73ecbc62b1) | Apr 04, 2022 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [9aea13fa1b](https://linux-hardware.org/?probe=9aea13fa1b) | Apr 04, 2022 |
| HP            | 1790                        | Desktop     | [5fd16b3e1e](https://linux-hardware.org/?probe=5fd16b3e1e) | Apr 03, 2022 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [ec2fb21c00](https://linux-hardware.org/?probe=ec2fb21c00) | Apr 03, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [5a4174b74d](https://linux-hardware.org/?probe=5a4174b74d) | Apr 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| MSI           | H81M-E35 V2                 | Desktop     | [a3aea1cbf5](https://linux-hardware.org/?probe=a3aea1cbf5) | Apr 02, 2022 |
| HP            | 805D                        | Desktop     | [709488e1da](https://linux-hardware.org/?probe=709488e1da) | Mar 31, 2022 |
| Lenovo        | ThinkPad T540p 20BEA00FR... | Notebook    | [c9323a9c40](https://linux-hardware.org/?probe=c9323a9c40) | Mar 31, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [946628cb20](https://linux-hardware.org/?probe=946628cb20) | Mar 30, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [3d76ab6a14](https://linux-hardware.org/?probe=3d76ab6a14) | Mar 30, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [b61b3e31e7](https://linux-hardware.org/?probe=b61b3e31e7) | Mar 30, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [f47336bbed](https://linux-hardware.org/?probe=f47336bbed) | Mar 30, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f398041b40](https://linux-hardware.org/?probe=f398041b40) | Mar 29, 2022 |
| Intel         | DP965LT AAD41694-206        | Desktop     | [b6f8d31fa5](https://linux-hardware.org/?probe=b6f8d31fa5) | Mar 28, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [5dae1dd2a5](https://linux-hardware.org/?probe=5dae1dd2a5) | Mar 28, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [323ca65327](https://linux-hardware.org/?probe=323ca65327) | Mar 28, 2022 |
| HP            | Pavilion 14                 | Notebook    | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [f457ad3a65](https://linux-hardware.org/?probe=f457ad3a65) | Mar 27, 2022 |
| HP            | Stream Notebook PC 14       | Notebook    | [9fc309dcaf](https://linux-hardware.org/?probe=9fc309dcaf) | Mar 27, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [7cff95afcb](https://linux-hardware.org/?probe=7cff95afcb) | Mar 27, 2022 |
| HP            | Stream Notebook PC 14       | Notebook    | [bcf7252530](https://linux-hardware.org/?probe=bcf7252530) | Mar 27, 2022 |
| Positivo      | Q232A                       | Notebook    | [fe29ba6b10](https://linux-hardware.org/?probe=fe29ba6b10) | Mar 27, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [d5f059e17d](https://linux-hardware.org/?probe=d5f059e17d) | Mar 26, 2022 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [a9a4291601](https://linux-hardware.org/?probe=a9a4291601) | Mar 26, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [dc2a2c1054](https://linux-hardware.org/?probe=dc2a2c1054) | Mar 25, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [f0a08eb35b](https://linux-hardware.org/?probe=f0a08eb35b) | Mar 25, 2022 |
| Dell          | Inspiron 5379               | Notebook    | [85c7a99f91](https://linux-hardware.org/?probe=85c7a99f91) | Mar 25, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [eef252e4f2](https://linux-hardware.org/?probe=eef252e4f2) | Mar 25, 2022 |
| Avell High... | B.ON                        | Notebook    | [19b689aa12](https://linux-hardware.org/?probe=19b689aa12) | Mar 25, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [c3cd38fd2d](https://linux-hardware.org/?probe=c3cd38fd2d) | Mar 25, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [a2db3c2cab](https://linux-hardware.org/?probe=a2db3c2cab) | Mar 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [cb089466a3](https://linux-hardware.org/?probe=cb089466a3) | Mar 24, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [b48b1f0de3](https://linux-hardware.org/?probe=b48b1f0de3) | Mar 24, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [43e7eab371](https://linux-hardware.org/?probe=43e7eab371) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [c136393c4b](https://linux-hardware.org/?probe=c136393c4b) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [713ff9dcb8](https://linux-hardware.org/?probe=713ff9dcb8) | Mar 23, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96244433f0](https://linux-hardware.org/?probe=96244433f0) | Mar 23, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [b886cf0849](https://linux-hardware.org/?probe=b886cf0849) | Mar 23, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [615009b8ee](https://linux-hardware.org/?probe=615009b8ee) | Mar 23, 2022 |
| ASUSTek       | N550LF                      | Notebook    | [5e5462ce64](https://linux-hardware.org/?probe=5e5462ce64) | Mar 23, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [e5fe628a7b](https://linux-hardware.org/?probe=e5fe628a7b) | Mar 23, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [5b74db2557](https://linux-hardware.org/?probe=5b74db2557) | Mar 22, 2022 |
| MSI           | GP76 Leopard 11UH           | Notebook    | [d398e3284e](https://linux-hardware.org/?probe=d398e3284e) | Mar 22, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [c90c0f1819](https://linux-hardware.org/?probe=c90c0f1819) | Mar 22, 2022 |
| ASUSTek       | X555LNB                     | Notebook    | [ae49172b0f](https://linux-hardware.org/?probe=ae49172b0f) | Mar 21, 2022 |
| ASRock        | FM2A75 Pro4+                | Desktop     | [0d7edce12d](https://linux-hardware.org/?probe=0d7edce12d) | Mar 21, 2022 |
| ASUSTek       | X555LNB                     | Notebook    | [33e081f100](https://linux-hardware.org/?probe=33e081f100) | Mar 21, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d3b1757cf5](https://linux-hardware.org/?probe=d3b1757cf5) | Mar 21, 2022 |
| ASUSTek       | K73E                        | Notebook    | [75069bd642](https://linux-hardware.org/?probe=75069bd642) | Mar 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [0e4992c717](https://linux-hardware.org/?probe=0e4992c717) | Mar 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [789a97d437](https://linux-hardware.org/?probe=789a97d437) | Mar 20, 2022 |
| HP            | 212B                        | Desktop     | [fd6a569226](https://linux-hardware.org/?probe=fd6a569226) | Mar 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [3607969e9d](https://linux-hardware.org/?probe=3607969e9d) | Mar 20, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [b1a437de4c](https://linux-hardware.org/?probe=b1a437de4c) | Mar 19, 2022 |
| HP            | 212B                        | Desktop     | [a85896bd48](https://linux-hardware.org/?probe=a85896bd48) | Mar 19, 2022 |
| HP            | 1589                        | Desktop     | [998f465bfc](https://linux-hardware.org/?probe=998f465bfc) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [05780b53fa](https://linux-hardware.org/?probe=05780b53fa) | Mar 19, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [d1f5b906e4](https://linux-hardware.org/?probe=d1f5b906e4) | Mar 19, 2022 |
| Panasonic     | FZ-M1CC-51BE                | Notebook    | [94e014ee40](https://linux-hardware.org/?probe=94e014ee40) | Mar 18, 2022 |
| Dell          | 0RY206                      | Desktop     | [df958219ab](https://linux-hardware.org/?probe=df958219ab) | Mar 18, 2022 |
| Dell          | 0RY206                      | Desktop     | [d46b854bd5](https://linux-hardware.org/?probe=d46b854bd5) | Mar 18, 2022 |
| ASUSTek       | K52Jr                       | Notebook    | [b05ec1dbda](https://linux-hardware.org/?probe=b05ec1dbda) | Mar 18, 2022 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [cd5c0f974e](https://linux-hardware.org/?probe=cd5c0f974e) | Mar 18, 2022 |
| Dell          | Precision M6300             | Notebook    | [aac71b9e66](https://linux-hardware.org/?probe=aac71b9e66) | Mar 17, 2022 |
| ASUSTek       | K52Jr                       | Notebook    | [77c6485b0f](https://linux-hardware.org/?probe=77c6485b0f) | Mar 17, 2022 |
| Packard Be... | IMEDIA S2885                | Desktop     | [1cf614db1e](https://linux-hardware.org/?probe=1cf614db1e) | Mar 17, 2022 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [c0db7c9966](https://linux-hardware.org/?probe=c0db7c9966) | Mar 17, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [8713806c38](https://linux-hardware.org/?probe=8713806c38) | Mar 17, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [42b5f424ce](https://linux-hardware.org/?probe=42b5f424ce) | Mar 17, 2022 |
| ASUSTek       | Zenbook UN5401QA_UN5401Q... | Convertible | [d0253d1ffc](https://linux-hardware.org/?probe=d0253d1ffc) | Mar 16, 2022 |
| GEO           | GeoFlex 110                 | Convertible | [763a31bbc5](https://linux-hardware.org/?probe=763a31bbc5) | Mar 16, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [e2ad81141c](https://linux-hardware.org/?probe=e2ad81141c) | Mar 16, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [acdee8aa65](https://linux-hardware.org/?probe=acdee8aa65) | Mar 15, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [bf80f02a40](https://linux-hardware.org/?probe=bf80f02a40) | Mar 15, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [c8809e0561](https://linux-hardware.org/?probe=c8809e0561) | Mar 15, 2022 |
| ASRock        | B85M DASH/OL R2.0           | Desktop     | [162abf1031](https://linux-hardware.org/?probe=162abf1031) | Mar 15, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [95c6b15672](https://linux-hardware.org/?probe=95c6b15672) | Mar 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [96b413780f](https://linux-hardware.org/?probe=96b413780f) | Mar 13, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [8ab5133b14](https://linux-hardware.org/?probe=8ab5133b14) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [9918c132f0](https://linux-hardware.org/?probe=9918c132f0) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [fd9ec44205](https://linux-hardware.org/?probe=fd9ec44205) | Mar 13, 2022 |
| Dell          | Latitude E6430              | Notebook    | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [4998fff0f9](https://linux-hardware.org/?probe=4998fff0f9) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [39cdee5411](https://linux-hardware.org/?probe=39cdee5411) | Mar 11, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [09d876ab23](https://linux-hardware.org/?probe=09d876ab23) | Mar 11, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [e0e30a9273](https://linux-hardware.org/?probe=e0e30a9273) | Mar 11, 2022 |
| ASRock        | B360 Gaming K4              | Desktop     | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| HP            | 82F1                        | Desktop     | [390462d20a](https://linux-hardware.org/?probe=390462d20a) | Mar 10, 2022 |
| HP            | 82F1                        | Desktop     | [63273af14a](https://linux-hardware.org/?probe=63273af14a) | Mar 10, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [066fecf595](https://linux-hardware.org/?probe=066fecf595) | Mar 10, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [e7a3d16cc0](https://linux-hardware.org/?probe=e7a3d16cc0) | Mar 09, 2022 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [2032fbba77](https://linux-hardware.org/?probe=2032fbba77) | Mar 09, 2022 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [508a68f09e](https://linux-hardware.org/?probe=508a68f09e) | Mar 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c7b32ff620](https://linux-hardware.org/?probe=c7b32ff620) | Mar 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [257f76a0df](https://linux-hardware.org/?probe=257f76a0df) | Mar 09, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [8dbe399133](https://linux-hardware.org/?probe=8dbe399133) | Mar 08, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [c7025ac75e](https://linux-hardware.org/?probe=c7025ac75e) | Mar 08, 2022 |
| Dell          | 0RW203 A00                  | Desktop     | [e06660b923](https://linux-hardware.org/?probe=e06660b923) | Mar 08, 2022 |
| Medion        | E2292 MD63390               | Convertible | [6f0eb8e6d7](https://linux-hardware.org/?probe=6f0eb8e6d7) | Mar 07, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [f0f74fc82a](https://linux-hardware.org/?probe=f0f74fc82a) | Mar 07, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [bde9b00de4](https://linux-hardware.org/?probe=bde9b00de4) | Mar 07, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [9f17c99bb5](https://linux-hardware.org/?probe=9f17c99bb5) | Mar 06, 2022 |
| ASUSTek       | UX331UN                     | Notebook    | [f1cf640532](https://linux-hardware.org/?probe=f1cf640532) | Mar 06, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [0f5c637f94](https://linux-hardware.org/?probe=0f5c637f94) | Mar 06, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [456b0dd391](https://linux-hardware.org/?probe=456b0dd391) | Mar 06, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [052e483cb5](https://linux-hardware.org/?probe=052e483cb5) | Mar 06, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [19c66b47da](https://linux-hardware.org/?probe=19c66b47da) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [e66faafcce](https://linux-hardware.org/?probe=e66faafcce) | Mar 06, 2022 |
| HP            | 8266                        | Desktop     | [e0991ef205](https://linux-hardware.org/?probe=e0991ef205) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [949d0886a1](https://linux-hardware.org/?probe=949d0886a1) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [f5241bc829](https://linux-hardware.org/?probe=f5241bc829) | Mar 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [7a52c91d68](https://linux-hardware.org/?probe=7a52c91d68) | Mar 05, 2022 |
| Unknown       | KN12A                       | Notebook    | [3ba6165509](https://linux-hardware.org/?probe=3ba6165509) | Mar 05, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [1fb41e944f](https://linux-hardware.org/?probe=1fb41e944f) | Mar 05, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [1c879cd60e](https://linux-hardware.org/?probe=1c879cd60e) | Mar 04, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [7d46bb8f25](https://linux-hardware.org/?probe=7d46bb8f25) | Mar 03, 2022 |
| Dell          | 0K240Y A02                  | Desktop     | [b5783c7fa0](https://linux-hardware.org/?probe=b5783c7fa0) | Mar 03, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [fda73ff759](https://linux-hardware.org/?probe=fda73ff759) | Mar 02, 2022 |
| Dell          | Latitude E6530              | Notebook    | [f13c84346e](https://linux-hardware.org/?probe=f13c84346e) | Mar 02, 2022 |
| ASUSTek       | UX331UN                     | Notebook    | [463899cdb7](https://linux-hardware.org/?probe=463899cdb7) | Mar 02, 2022 |
| ASUSTek       | K55N                        | Notebook    | [6143b27a96](https://linux-hardware.org/?probe=6143b27a96) | Mar 02, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [880490eb1e](https://linux-hardware.org/?probe=880490eb1e) | Mar 01, 2022 |
| MSI           | H81M-E34                    | Desktop     | [563e906e47](https://linux-hardware.org/?probe=563e906e47) | Mar 01, 2022 |
| MSI           | 09AC                        | Desktop     | [a5c7015fca](https://linux-hardware.org/?probe=a5c7015fca) | Mar 01, 2022 |
| Schenker      | VIA 15                      | Notebook    | [c84aacc342](https://linux-hardware.org/?probe=c84aacc342) | Feb 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [f2e18241da](https://linux-hardware.org/?probe=f2e18241da) | Feb 28, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [25c0e14020](https://linux-hardware.org/?probe=25c0e14020) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [79cc0b97a4](https://linux-hardware.org/?probe=79cc0b97a4) | Feb 28, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [d3f2971c3c](https://linux-hardware.org/?probe=d3f2971c3c) | Feb 27, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [74bc866ab2](https://linux-hardware.org/?probe=74bc866ab2) | Feb 27, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c7db8c9806](https://linux-hardware.org/?probe=c7db8c9806) | Feb 27, 2022 |
| HP            | Notebook                    | Notebook    | [bcc74ebe77](https://linux-hardware.org/?probe=bcc74ebe77) | Feb 27, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [e0d39731a0](https://linux-hardware.org/?probe=e0d39731a0) | Feb 27, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [2e06b2fed8](https://linux-hardware.org/?probe=2e06b2fed8) | Feb 27, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [f86d99b8a1](https://linux-hardware.org/?probe=f86d99b8a1) | Feb 27, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [83dec4f285](https://linux-hardware.org/?probe=83dec4f285) | Feb 26, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [3f97cefeb4](https://linux-hardware.org/?probe=3f97cefeb4) | Feb 26, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [17586d38de](https://linux-hardware.org/?probe=17586d38de) | Feb 26, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [fb4c469104](https://linux-hardware.org/?probe=fb4c469104) | Feb 26, 2022 |
| Biostar       | B450MH                      | Desktop     | [40f413ddcb](https://linux-hardware.org/?probe=40f413ddcb) | Feb 26, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9013eb37ee](https://linux-hardware.org/?probe=9013eb37ee) | Feb 25, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [8e648c583a](https://linux-hardware.org/?probe=8e648c583a) | Feb 25, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4c72ebcb41](https://linux-hardware.org/?probe=4c72ebcb41) | Feb 25, 2022 |
| MSI           | MS-7502 Fab D               | Desktop     | [0149efd00d](https://linux-hardware.org/?probe=0149efd00d) | Feb 25, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [fbed153592](https://linux-hardware.org/?probe=fbed153592) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [eed2589bd2](https://linux-hardware.org/?probe=eed2589bd2) | Feb 25, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [013e049a4d](https://linux-hardware.org/?probe=013e049a4d) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [885239a137](https://linux-hardware.org/?probe=885239a137) | Feb 24, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [904717059e](https://linux-hardware.org/?probe=904717059e) | Feb 24, 2022 |
| Unknown       | TB-4000                     | Desktop     | [70155eb876](https://linux-hardware.org/?probe=70155eb876) | Feb 24, 2022 |
| Toshiba       | IS 1412                     | Notebook    | [3621d1064d](https://linux-hardware.org/?probe=3621d1064d) | Feb 24, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [9d9c4fe241](https://linux-hardware.org/?probe=9d9c4fe241) | Feb 23, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [84b8eefa6d](https://linux-hardware.org/?probe=84b8eefa6d) | Feb 23, 2022 |
| Supermicro    | X10DAI                      | Desktop     | [4de85d4700](https://linux-hardware.org/?probe=4de85d4700) | Feb 23, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [ec93ded12b](https://linux-hardware.org/?probe=ec93ded12b) | Feb 23, 2022 |
| Lenovo        | ThinkPad T430 23495P8       | Notebook    | [03266eea0a](https://linux-hardware.org/?probe=03266eea0a) | Feb 23, 2022 |
| HP            | Notebook                    | Notebook    | [93a85593c3](https://linux-hardware.org/?probe=93a85593c3) | Feb 23, 2022 |
| Dell          | Latitude E5570              | Notebook    | [f132300275](https://linux-hardware.org/?probe=f132300275) | Feb 23, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c4b59e08bc](https://linux-hardware.org/?probe=c4b59e08bc) | Feb 22, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [e1e83bde9c](https://linux-hardware.org/?probe=e1e83bde9c) | Feb 22, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [cc9d99be2a](https://linux-hardware.org/?probe=cc9d99be2a) | Feb 22, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [d31201b74c](https://linux-hardware.org/?probe=d31201b74c) | Feb 22, 2022 |
| Lenovo        | ThinkPad T460s 20F9S1G20... | Notebook    | [6a6c0b0b39](https://linux-hardware.org/?probe=6a6c0b0b39) | Feb 21, 2022 |
| Medion        | TJ4125                      | Desktop     | [04d5f95a16](https://linux-hardware.org/?probe=04d5f95a16) | Feb 21, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [0ee9dcd568](https://linux-hardware.org/?probe=0ee9dcd568) | Feb 20, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [a73c8072f9](https://linux-hardware.org/?probe=a73c8072f9) | Feb 20, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [a457ae32df](https://linux-hardware.org/?probe=a457ae32df) | Feb 20, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [e12ba75c05](https://linux-hardware.org/?probe=e12ba75c05) | Feb 19, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [5ee5668ab1](https://linux-hardware.org/?probe=5ee5668ab1) | Feb 19, 2022 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [a4a57f2b26](https://linux-hardware.org/?probe=a4a57f2b26) | Feb 19, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [259dd8bc78](https://linux-hardware.org/?probe=259dd8bc78) | Feb 19, 2022 |
| Lenovo        | ThinkPad L430 2468CTO       | Notebook    | [9244a0f8f9](https://linux-hardware.org/?probe=9244a0f8f9) | Feb 18, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [59a321d574](https://linux-hardware.org/?probe=59a321d574) | Feb 18, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [83a05f5d1e](https://linux-hardware.org/?probe=83a05f5d1e) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [ff74abc44d](https://linux-hardware.org/?probe=ff74abc44d) | Feb 18, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [ffb9eb537e](https://linux-hardware.org/?probe=ffb9eb537e) | Feb 17, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [7f55b1fa12](https://linux-hardware.org/?probe=7f55b1fa12) | Feb 17, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [f7cce89284](https://linux-hardware.org/?probe=f7cce89284) | Feb 17, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [9628754bf4](https://linux-hardware.org/?probe=9628754bf4) | Feb 17, 2022 |
| Dell          | 0J8G6F A03                  | Desktop     | [c4314fa1c4](https://linux-hardware.org/?probe=c4314fa1c4) | Feb 17, 2022 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [4b198a6b46](https://linux-hardware.org/?probe=4b198a6b46) | Feb 17, 2022 |
| ASUSTek       | Vivobook_ASUSLaptop X350... | Notebook    | [5d2de5cd73](https://linux-hardware.org/?probe=5d2de5cd73) | Feb 17, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [9fdad76c68](https://linux-hardware.org/?probe=9fdad76c68) | Feb 16, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [d1f8637478](https://linux-hardware.org/?probe=d1f8637478) | Feb 16, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [9773bc9c72](https://linux-hardware.org/?probe=9773bc9c72) | Feb 16, 2022 |
| Dell          | Latitude E6320              | Notebook    | [ae7b660be1](https://linux-hardware.org/?probe=ae7b660be1) | Feb 16, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [88c9f0db96](https://linux-hardware.org/?probe=88c9f0db96) | Feb 16, 2022 |
| Gateway       | IPISB-VR                    | Desktop     | [af56b8d361](https://linux-hardware.org/?probe=af56b8d361) | Feb 16, 2022 |
| MSI           | H81M-E35 V2                 | Desktop     | [20aafa92dd](https://linux-hardware.org/?probe=20aafa92dd) | Feb 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [4e3b8bfbb1](https://linux-hardware.org/?probe=4e3b8bfbb1) | Feb 16, 2022 |
| Jumper        | EZbook                      | Notebook    | [f27f93bafe](https://linux-hardware.org/?probe=f27f93bafe) | Feb 16, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [725807db6f](https://linux-hardware.org/?probe=725807db6f) | Feb 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [3db88acec8](https://linux-hardware.org/?probe=3db88acec8) | Feb 15, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [905ad02036](https://linux-hardware.org/?probe=905ad02036) | Feb 14, 2022 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [d42d70a45a](https://linux-hardware.org/?probe=d42d70a45a) | Feb 14, 2022 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [b4db24332b](https://linux-hardware.org/?probe=b4db24332b) | Feb 14, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [5768ab0770](https://linux-hardware.org/?probe=5768ab0770) | Feb 13, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [9df9f66476](https://linux-hardware.org/?probe=9df9f66476) | Feb 13, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [fc4efd1eff](https://linux-hardware.org/?probe=fc4efd1eff) | Feb 13, 2022 |
| Intel         | NUC7i7BNB J31145-310        | Mini pc     | [524246985d](https://linux-hardware.org/?probe=524246985d) | Feb 13, 2022 |
| MSI           | H81M-E35 V2                 | Desktop     | [fdba4d1aab](https://linux-hardware.org/?probe=fdba4d1aab) | Feb 13, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [c756082899](https://linux-hardware.org/?probe=c756082899) | Feb 13, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [f7d1fc012c](https://linux-hardware.org/?probe=f7d1fc012c) | Feb 13, 2022 |
| Google        | Homestar (rev3)             | Soc         | [313894dec8](https://linux-hardware.org/?probe=313894dec8) | Feb 12, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a98c8db3ad](https://linux-hardware.org/?probe=a98c8db3ad) | Feb 12, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [5795d9b341](https://linux-hardware.org/?probe=5795d9b341) | Feb 12, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [a9271fbd9f](https://linux-hardware.org/?probe=a9271fbd9f) | Feb 12, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [ed39168e58](https://linux-hardware.org/?probe=ed39168e58) | Feb 12, 2022 |
| Dell          | Latitude 5580               | Notebook    | [77466f0d8f](https://linux-hardware.org/?probe=77466f0d8f) | Feb 11, 2022 |
| Dell          | Latitude 5580               | Notebook    | [8d65e0f7c7](https://linux-hardware.org/?probe=8d65e0f7c7) | Feb 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [5061491140](https://linux-hardware.org/?probe=5061491140) | Feb 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [cd89130dcd](https://linux-hardware.org/?probe=cd89130dcd) | Feb 11, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [0f7da36e7e](https://linux-hardware.org/?probe=0f7da36e7e) | Feb 11, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [11d24586e8](https://linux-hardware.org/?probe=11d24586e8) | Feb 11, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [2885a7e3ed](https://linux-hardware.org/?probe=2885a7e3ed) | Feb 11, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [aba110f180](https://linux-hardware.org/?probe=aba110f180) | Feb 10, 2022 |
| MSI           | Prestige 14 A10RB           | Notebook    | [7195cacd54](https://linux-hardware.org/?probe=7195cacd54) | Feb 10, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [fe18f09b36](https://linux-hardware.org/?probe=fe18f09b36) | Feb 10, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [5e071a1807](https://linux-hardware.org/?probe=5e071a1807) | Feb 09, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [df5a829402](https://linux-hardware.org/?probe=df5a829402) | Feb 09, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [791eb690fd](https://linux-hardware.org/?probe=791eb690fd) | Feb 09, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [86e83850e6](https://linux-hardware.org/?probe=86e83850e6) | Feb 09, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [1564cdd40b](https://linux-hardware.org/?probe=1564cdd40b) | Feb 09, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [b53861af9b](https://linux-hardware.org/?probe=b53861af9b) | Feb 09, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [60c47d2f55](https://linux-hardware.org/?probe=60c47d2f55) | Feb 09, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [bca05a8467](https://linux-hardware.org/?probe=bca05a8467) | Feb 09, 2022 |
| SUPoX COMP... | B250A-BTC PRO               | Desktop     | [780b5cb42e](https://linux-hardware.org/?probe=780b5cb42e) | Feb 09, 2022 |
| Dell          | Latitude E5440              | Notebook    | [8ddea24991](https://linux-hardware.org/?probe=8ddea24991) | Feb 08, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [011e0963bd](https://linux-hardware.org/?probe=011e0963bd) | Feb 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9c3722a690](https://linux-hardware.org/?probe=9c3722a690) | Feb 07, 2022 |
| HP            | 0A60h                       | Desktop     | [8c9b5ec56f](https://linux-hardware.org/?probe=8c9b5ec56f) | Feb 06, 2022 |
| HP            | 843C                        | Desktop     | [65121c676e](https://linux-hardware.org/?probe=65121c676e) | Feb 06, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [0c22c792a0](https://linux-hardware.org/?probe=0c22c792a0) | Feb 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [4f80537faf](https://linux-hardware.org/?probe=4f80537faf) | Feb 06, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [784b1b0c3b](https://linux-hardware.org/?probe=784b1b0c3b) | Feb 06, 2022 |
| Dell          | System XPS L502X            | Notebook    | [c2a3b5d930](https://linux-hardware.org/?probe=c2a3b5d930) | Feb 05, 2022 |
| Medion        | E4241 MD60996               | Notebook    | [d89f5e4089](https://linux-hardware.org/?probe=d89f5e4089) | Feb 05, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [f9a64bf682](https://linux-hardware.org/?probe=f9a64bf682) | Feb 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [36bac5a046](https://linux-hardware.org/?probe=36bac5a046) | Feb 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [e4e8e488a2](https://linux-hardware.org/?probe=e4e8e488a2) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [1f4e97ac28](https://linux-hardware.org/?probe=1f4e97ac28) | Feb 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3e8a21888f](https://linux-hardware.org/?probe=3e8a21888f) | Feb 04, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [8b9e72e0ed](https://linux-hardware.org/?probe=8b9e72e0ed) | Feb 03, 2022 |
| HP            | Laptop 15g-br1xx            | Notebook    | [092ea39c7e](https://linux-hardware.org/?probe=092ea39c7e) | Feb 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [df711c6514](https://linux-hardware.org/?probe=df711c6514) | Feb 03, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [4c55c42084](https://linux-hardware.org/?probe=4c55c42084) | Feb 03, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [a2fbd7d84e](https://linux-hardware.org/?probe=a2fbd7d84e) | Feb 03, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | Notebook    | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| Toshiba       | Satellite S55-C             | Notebook    | [ba1cbdf586](https://linux-hardware.org/?probe=ba1cbdf586) | Feb 03, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [3df622872c](https://linux-hardware.org/?probe=3df622872c) | Feb 03, 2022 |
| HP            | Pavilion dv6                | Notebook    | [63c8ab5447](https://linux-hardware.org/?probe=63c8ab5447) | Feb 03, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [3035fdad91](https://linux-hardware.org/?probe=3035fdad91) | Feb 03, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [99abdcb1fe](https://linux-hardware.org/?probe=99abdcb1fe) | Feb 02, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [46a851b841](https://linux-hardware.org/?probe=46a851b841) | Feb 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [c51e8a279f](https://linux-hardware.org/?probe=c51e8a279f) | Feb 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [19cb128817](https://linux-hardware.org/?probe=19cb128817) | Feb 02, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | Notebook    | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| ASUSTek       | Vivobook_ASUSLaptop X350... | Notebook    | [1e330f1e0e](https://linux-hardware.org/?probe=1e330f1e0e) | Feb 02, 2022 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [0404256996](https://linux-hardware.org/?probe=0404256996) | Feb 01, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [8f83ae693d](https://linux-hardware.org/?probe=8f83ae693d) | Jan 31, 2022 |
| Dell          | Latitude 7410               | Notebook    | [5f60c8df83](https://linux-hardware.org/?probe=5f60c8df83) | Jan 31, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [be02f0bd97](https://linux-hardware.org/?probe=be02f0bd97) | Jan 31, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [e8b6865345](https://linux-hardware.org/?probe=e8b6865345) | Jan 31, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [1c6777fb1a](https://linux-hardware.org/?probe=1c6777fb1a) | Jan 31, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [16f2c58e8a](https://linux-hardware.org/?probe=16f2c58e8a) | Jan 30, 2022 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [255ffc0493](https://linux-hardware.org/?probe=255ffc0493) | Jan 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [9d24496181](https://linux-hardware.org/?probe=9d24496181) | Jan 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e618d0e8f6](https://linux-hardware.org/?probe=e618d0e8f6) | Jan 30, 2022 |
| Lenovo        | ThinkCentre M58 3231W2Y     | Desktop     | [69b300dfb1](https://linux-hardware.org/?probe=69b300dfb1) | Jan 29, 2022 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c4a65986af](https://linux-hardware.org/?probe=c4a65986af) | Jan 29, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [b864987207](https://linux-hardware.org/?probe=b864987207) | Jan 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cd876e95b9](https://linux-hardware.org/?probe=cd876e95b9) | Jan 29, 2022 |
| System76      | Serval WS                   | Notebook    | [a6e447aa98](https://linux-hardware.org/?probe=a6e447aa98) | Jan 28, 2022 |
| System76      | Serval WS                   | Notebook    | [371fbc5a98](https://linux-hardware.org/?probe=371fbc5a98) | Jan 28, 2022 |
| Dell          | G5 5500                     | Notebook    | [4917524046](https://linux-hardware.org/?probe=4917524046) | Jan 28, 2022 |
| Sony          | VPCSB1B9E                   | Notebook    | [2b1ede014c](https://linux-hardware.org/?probe=2b1ede014c) | Jan 28, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [aa8f4035b5](https://linux-hardware.org/?probe=aa8f4035b5) | Jan 27, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [c346ce1a75](https://linux-hardware.org/?probe=c346ce1a75) | Jan 27, 2022 |
| Fujitsu Si... | AMILO Xi 1526               | Notebook    | [5acf0f5805](https://linux-hardware.org/?probe=5acf0f5805) | Jan 27, 2022 |
| HP            | Compaq Presario CQ40        | Notebook    | [2e8ff0310b](https://linux-hardware.org/?probe=2e8ff0310b) | Jan 27, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [7daa77d5ba](https://linux-hardware.org/?probe=7daa77d5ba) | Jan 27, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [256f789c6d](https://linux-hardware.org/?probe=256f789c6d) | Jan 27, 2022 |
| Fujitsu Si... | AMILO Xi 1526               | Notebook    | [0b4735d586](https://linux-hardware.org/?probe=0b4735d586) | Jan 27, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [bb36894a2c](https://linux-hardware.org/?probe=bb36894a2c) | Jan 27, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [a23be61a14](https://linux-hardware.org/?probe=a23be61a14) | Jan 26, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [c3278bb973](https://linux-hardware.org/?probe=c3278bb973) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [3e03426280](https://linux-hardware.org/?probe=3e03426280) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [4283316d8a](https://linux-hardware.org/?probe=4283316d8a) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5edb2eb3](https://linux-hardware.org/?probe=4d5edb2eb3) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X532... | Notebook    | [bc4d814298](https://linux-hardware.org/?probe=bc4d814298) | Jan 24, 2022 |
| Dell          | Precision 5520              | Notebook    | [315d733003](https://linux-hardware.org/?probe=315d733003) | Jan 24, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [a6e7a03b85](https://linux-hardware.org/?probe=a6e7a03b85) | Jan 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [5310be8910](https://linux-hardware.org/?probe=5310be8910) | Jan 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [12d652c14a](https://linux-hardware.org/?probe=12d652c14a) | Jan 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [986d94fa44](https://linux-hardware.org/?probe=986d94fa44) | Jan 23, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [5f82282e71](https://linux-hardware.org/?probe=5f82282e71) | Jan 23, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [bd43e4b748](https://linux-hardware.org/?probe=bd43e4b748) | Jan 22, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [fec419577b](https://linux-hardware.org/?probe=fec419577b) | Jan 22, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [b8b6a312b1](https://linux-hardware.org/?probe=b8b6a312b1) | Jan 21, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [f348809f89](https://linux-hardware.org/?probe=f348809f89) | Jan 21, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [bdf7199e93](https://linux-hardware.org/?probe=bdf7199e93) | Jan 21, 2022 |
| Sony          | SVD13213SGW                 | Notebook    | [ee9e63ab7c](https://linux-hardware.org/?probe=ee9e63ab7c) | Jan 21, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [81e03a6b48](https://linux-hardware.org/?probe=81e03a6b48) | Jan 21, 2022 |
| Acer          | Aspire F5-771G              | Notebook    | [dd9a69f04d](https://linux-hardware.org/?probe=dd9a69f04d) | Jan 20, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [ffedf62905](https://linux-hardware.org/?probe=ffedf62905) | Jan 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [24c10d9f2d](https://linux-hardware.org/?probe=24c10d9f2d) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK E753               | Notebook    | [d44da01e91](https://linux-hardware.org/?probe=d44da01e91) | Jan 20, 2022 |
| Toshiba       | Satellite S55-C             | Notebook    | [cc43e1a269](https://linux-hardware.org/?probe=cc43e1a269) | Jan 20, 2022 |
| Dell          | Latitude E5430 vPro         | Notebook    | [279789817e](https://linux-hardware.org/?probe=279789817e) | Jan 20, 2022 |
| Toshiba       | Satellite S55-C             | Notebook    | [8821f2145e](https://linux-hardware.org/?probe=8821f2145e) | Jan 20, 2022 |
| MSI           | FM2-A75IA-E53               | Desktop     | [e2b013c3eb](https://linux-hardware.org/?probe=e2b013c3eb) | Jan 19, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4cdd6daf44](https://linux-hardware.org/?probe=4cdd6daf44) | Jan 19, 2022 |
| Lenovo        | ThinkPad L440 20AT002YGE    | Notebook    | [303ee02c20](https://linux-hardware.org/?probe=303ee02c20) | Jan 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [5ba89b6e26](https://linux-hardware.org/?probe=5ba89b6e26) | Jan 18, 2022 |
| HP            | 0B40h                       | Desktop     | [d5bd9c64af](https://linux-hardware.org/?probe=d5bd9c64af) | Jan 18, 2022 |
| Dell          | Latitude 7490               | Notebook    | [66984a4e2b](https://linux-hardware.org/?probe=66984a4e2b) | Jan 18, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [1f699a9a4d](https://linux-hardware.org/?probe=1f699a9a4d) | Jan 17, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [2fdc6503ab](https://linux-hardware.org/?probe=2fdc6503ab) | Jan 17, 2022 |
| HP            | G60                         | Notebook    | [0c45a490c6](https://linux-hardware.org/?probe=0c45a490c6) | Jan 17, 2022 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [8f9db79811](https://linux-hardware.org/?probe=8f9db79811) | Jan 16, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [e3486517d4](https://linux-hardware.org/?probe=e3486517d4) | Jan 16, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [44e656894a](https://linux-hardware.org/?probe=44e656894a) | Jan 16, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [649e14be7d](https://linux-hardware.org/?probe=649e14be7d) | Jan 16, 2022 |
| ASUSTek       | S400CA                      | Notebook    | [3d2d24d90e](https://linux-hardware.org/?probe=3d2d24d90e) | Jan 15, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [bc00e00b3d](https://linux-hardware.org/?probe=bc00e00b3d) | Jan 15, 2022 |
| Dell          | Latitude D830               | Notebook    | [3824b91be9](https://linux-hardware.org/?probe=3824b91be9) | Jan 15, 2022 |
| MSI           | B85I                        | Desktop     | [dc1862e477](https://linux-hardware.org/?probe=dc1862e477) | Jan 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d19a03f3b4](https://linux-hardware.org/?probe=d19a03f3b4) | Jan 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [31cd8dd167](https://linux-hardware.org/?probe=31cd8dd167) | Jan 14, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ef391b2ba](https://linux-hardware.org/?probe=8ef391b2ba) | Jan 13, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [232d1f1cb4](https://linux-hardware.org/?probe=232d1f1cb4) | Jan 12, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [1bc317c3e4](https://linux-hardware.org/?probe=1bc317c3e4) | Jan 12, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [a4054331dc](https://linux-hardware.org/?probe=a4054331dc) | Jan 12, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [20cc8ef2ea](https://linux-hardware.org/?probe=20cc8ef2ea) | Jan 11, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [a7be44496a](https://linux-hardware.org/?probe=a7be44496a) | Jan 11, 2022 |
| Lenovo        | ThinkPad E595 20NF0000GE    | Notebook    | [c78518f0ac](https://linux-hardware.org/?probe=c78518f0ac) | Jan 10, 2022 |
| Biostar       | H81MGV3                     | Desktop     | [533d05d210](https://linux-hardware.org/?probe=533d05d210) | Jan 09, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c09f135f63](https://linux-hardware.org/?probe=c09f135f63) | Jan 09, 2022 |
| Dell          | 0MX4YF A01                  | Server      | [2953317989](https://linux-hardware.org/?probe=2953317989) | Jan 08, 2022 |
| Dell          | 0DR845                      | Desktop     | [daa833f06d](https://linux-hardware.org/?probe=daa833f06d) | Jan 08, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [c4d40f6344](https://linux-hardware.org/?probe=c4d40f6344) | Jan 08, 2022 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [82aa762a97](https://linux-hardware.org/?probe=82aa762a97) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [13c6bafd04](https://linux-hardware.org/?probe=13c6bafd04) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e50bae67a6](https://linux-hardware.org/?probe=e50bae67a6) | Jan 08, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [2aefd7833a](https://linux-hardware.org/?probe=2aefd7833a) | Jan 07, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [4538696d8c](https://linux-hardware.org/?probe=4538696d8c) | Jan 07, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [21a3c77b79](https://linux-hardware.org/?probe=21a3c77b79) | Jan 07, 2022 |
| Dell          | Precision 5510              | Notebook    | [98a122eac7](https://linux-hardware.org/?probe=98a122eac7) | Jan 07, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [a9bef5b272](https://linux-hardware.org/?probe=a9bef5b272) | Jan 07, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [738a38c219](https://linux-hardware.org/?probe=738a38c219) | Jan 07, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [346c27c2c3](https://linux-hardware.org/?probe=346c27c2c3) | Jan 07, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [960db118f1](https://linux-hardware.org/?probe=960db118f1) | Jan 07, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [5cd2548a30](https://linux-hardware.org/?probe=5cd2548a30) | Jan 07, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [5e77633e52](https://linux-hardware.org/?probe=5e77633e52) | Jan 07, 2022 |
| MSI           | GE62 2QD                    | Notebook    | [5f35b0b1ab](https://linux-hardware.org/?probe=5f35b0b1ab) | Jan 07, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [b44e84f8a6](https://linux-hardware.org/?probe=b44e84f8a6) | Jan 06, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [eb38386cfe](https://linux-hardware.org/?probe=eb38386cfe) | Jan 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [bab91e3b63](https://linux-hardware.org/?probe=bab91e3b63) | Jan 06, 2022 |
| ASRock        | B75 Pro3-M                  | Desktop     | [2daf055722](https://linux-hardware.org/?probe=2daf055722) | Jan 05, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [46ac9baf07](https://linux-hardware.org/?probe=46ac9baf07) | Jan 05, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [843345dfe6](https://linux-hardware.org/?probe=843345dfe6) | Jan 04, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [4717c4fff3](https://linux-hardware.org/?probe=4717c4fff3) | Jan 04, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [c3ddad9a30](https://linux-hardware.org/?probe=c3ddad9a30) | Jan 03, 2022 |
| Samsung       | R538/R578/R778              | Notebook    | [617d9d3835](https://linux-hardware.org/?probe=617d9d3835) | Jan 03, 2022 |
| Dell          | Latitude 5411               | Notebook    | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| Sony          | VPCCA35FA                   | Notebook    | [85f4fcc0b6](https://linux-hardware.org/?probe=85f4fcc0b6) | Jan 03, 2022 |
| Sony          | VPCCA35FA                   | Notebook    | [f69299cbfb](https://linux-hardware.org/?probe=f69299cbfb) | Jan 03, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [0d987db3d0](https://linux-hardware.org/?probe=0d987db3d0) | Jan 02, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c8e2178f07](https://linux-hardware.org/?probe=c8e2178f07) | Jan 02, 2022 |
| ASRock        | G41C-GS                     | Desktop     | [841dc47501](https://linux-hardware.org/?probe=841dc47501) | Jan 01, 2022 |
| Irbis         | NB120                       | Notebook    | [82fdabd91d](https://linux-hardware.org/?probe=82fdabd91d) | Jan 01, 2022 |
| HP            | 0A60h                       | Desktop     | [2812050060](https://linux-hardware.org/?probe=2812050060) | Jan 01, 2022 |
| Lenovo        | ThinkPad T590 20N5S0MR00    | Notebook    | [29040ecce5](https://linux-hardware.org/?probe=29040ecce5) | Jan 01, 2022 |
| ASUSTek       | G771JMC                     | Notebook    | [8a937cb99d](https://linux-hardware.org/?probe=8a937cb99d) | Jan 01, 2022 |
| HP            | Laptop 15z-ef1xxx           | Notebook    | [65ddec042b](https://linux-hardware.org/?probe=65ddec042b) | Jan 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b3a76ceb99](https://linux-hardware.org/?probe=b3a76ceb99) | Dec 31, 2021 |
| Dell          | Latitude 3420               | Notebook    | [a248c25326](https://linux-hardware.org/?probe=a248c25326) | Dec 31, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [8d56c47c8d](https://linux-hardware.org/?probe=8d56c47c8d) | Dec 31, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [4e0fbd63d6](https://linux-hardware.org/?probe=4e0fbd63d6) | Dec 31, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [9d97b2d4c1](https://linux-hardware.org/?probe=9d97b2d4c1) | Dec 31, 2021 |
| Lenovo        | V580c 20160                 | Notebook    | [c35aa8eb06](https://linux-hardware.org/?probe=c35aa8eb06) | Dec 30, 2021 |
| Mediacom      | M-SB151                     | Notebook    | [ebfc37b77e](https://linux-hardware.org/?probe=ebfc37b77e) | Dec 30, 2021 |
| Lenovo        | V580c 20160                 | Notebook    | [9f9fe096db](https://linux-hardware.org/?probe=9f9fe096db) | Dec 30, 2021 |
| HP            | ZBook 15 G4                 | Notebook    | [45c3b9ac54](https://linux-hardware.org/?probe=45c3b9ac54) | Dec 30, 2021 |
| HP            | ZBook 15 G4                 | Notebook    | [18501c3084](https://linux-hardware.org/?probe=18501c3084) | Dec 30, 2021 |
| ASRock        | X370 Killer SLI             | Desktop     | [7c10b6f7ae](https://linux-hardware.org/?probe=7c10b6f7ae) | Dec 30, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [6324598512](https://linux-hardware.org/?probe=6324598512) | Dec 30, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [38dda4af6b](https://linux-hardware.org/?probe=38dda4af6b) | Dec 30, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [b93b965f55](https://linux-hardware.org/?probe=b93b965f55) | Dec 30, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [1d3389845e](https://linux-hardware.org/?probe=1d3389845e) | Dec 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [d39214a966](https://linux-hardware.org/?probe=d39214a966) | Dec 29, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f5d7590fc7](https://linux-hardware.org/?probe=f5d7590fc7) | Dec 28, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [21a8a676d1](https://linux-hardware.org/?probe=21a8a676d1) | Dec 28, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [61561f50ba](https://linux-hardware.org/?probe=61561f50ba) | Dec 28, 2021 |
| HP            | 828A                        | Desktop     | [c5e0a5a464](https://linux-hardware.org/?probe=c5e0a5a464) | Dec 28, 2021 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [6f2dc843e9](https://linux-hardware.org/?probe=6f2dc843e9) | Dec 27, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d0059fcd5a](https://linux-hardware.org/?probe=d0059fcd5a) | Dec 27, 2021 |
| ASRock        | Z87 Pro4                    | Desktop     | [8459ac43a8](https://linux-hardware.org/?probe=8459ac43a8) | Dec 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [d88cb8b5ae](https://linux-hardware.org/?probe=d88cb8b5ae) | Dec 27, 2021 |
| Acer          | Aspire T3-605               | Desktop     | [7acbb546e6](https://linux-hardware.org/?probe=7acbb546e6) | Dec 26, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [961341534c](https://linux-hardware.org/?probe=961341534c) | Dec 26, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2a7c56982c](https://linux-hardware.org/?probe=2a7c56982c) | Dec 26, 2021 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [4e4cc2bfb3](https://linux-hardware.org/?probe=4e4cc2bfb3) | Dec 26, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [dc6fd4bfc7](https://linux-hardware.org/?probe=dc6fd4bfc7) | Dec 25, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [fc814dc489](https://linux-hardware.org/?probe=fc814dc489) | Dec 25, 2021 |
| HP            | ProBook 640 G4              | Notebook    | [f1fa3d65b1](https://linux-hardware.org/?probe=f1fa3d65b1) | Dec 25, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6c56118d24](https://linux-hardware.org/?probe=6c56118d24) | Dec 25, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [70287063b9](https://linux-hardware.org/?probe=70287063b9) | Dec 24, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [508decf868](https://linux-hardware.org/?probe=508decf868) | Dec 24, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [4e8b9c1c51](https://linux-hardware.org/?probe=4e8b9c1c51) | Dec 24, 2021 |
| Gigabyte      | B150M-HD3-CF                | Desktop     | [1f8dbcbdc7](https://linux-hardware.org/?probe=1f8dbcbdc7) | Dec 24, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [ae7af1351c](https://linux-hardware.org/?probe=ae7af1351c) | Dec 24, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [286b87e3ee](https://linux-hardware.org/?probe=286b87e3ee) | Dec 23, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [dcbbdb5fc5](https://linux-hardware.org/?probe=dcbbdb5fc5) | Dec 23, 2021 |
| MSI           | Delta 15 A5EFK              | Notebook    | [68010a3af5](https://linux-hardware.org/?probe=68010a3af5) | Dec 23, 2021 |
| MSI           | Delta 15 A5EFK              | Notebook    | [2d4a0a1823](https://linux-hardware.org/?probe=2d4a0a1823) | Dec 23, 2021 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [8fdab6dc11](https://linux-hardware.org/?probe=8fdab6dc11) | Dec 23, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [a53f185048](https://linux-hardware.org/?probe=a53f185048) | Dec 22, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [08a0d84e0a](https://linux-hardware.org/?probe=08a0d84e0a) | Dec 22, 2021 |
| Timi          | Mi Gaming Laptop 15.6       | Notebook    | [0001a4fb5e](https://linux-hardware.org/?probe=0001a4fb5e) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [36431daa99](https://linux-hardware.org/?probe=36431daa99) | Dec 22, 2021 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [c72566a702](https://linux-hardware.org/?probe=c72566a702) | Dec 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [fe1f7f03e2](https://linux-hardware.org/?probe=fe1f7f03e2) | Dec 21, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [88a4b38685](https://linux-hardware.org/?probe=88a4b38685) | Dec 21, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [1d27772094](https://linux-hardware.org/?probe=1d27772094) | Dec 21, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [992c6c4350](https://linux-hardware.org/?probe=992c6c4350) | Dec 21, 2021 |
| Lenovo        | ThinkPad E480 20KN001QRT    | Notebook    | [85fbd45c1f](https://linux-hardware.org/?probe=85fbd45c1f) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [9923367f59](https://linux-hardware.org/?probe=9923367f59) | Dec 21, 2021 |
| Dell          | Latitude D830               | Notebook    | [e3d7d2ff2c](https://linux-hardware.org/?probe=e3d7d2ff2c) | Dec 21, 2021 |
| LattePanda    | Alpha                       | Desktop     | [73f961d1b6](https://linux-hardware.org/?probe=73f961d1b6) | Dec 21, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [6748ebc68a](https://linux-hardware.org/?probe=6748ebc68a) | Dec 20, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [5c05fe22a6](https://linux-hardware.org/?probe=5c05fe22a6) | Dec 20, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c64c369808](https://linux-hardware.org/?probe=c64c369808) | Dec 19, 2021 |
| Lenovo        | G505 20240                  | Notebook    | [e29df1e2a0](https://linux-hardware.org/?probe=e29df1e2a0) | Dec 19, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [9b42a0346b](https://linux-hardware.org/?probe=9b42a0346b) | Dec 18, 2021 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [e17d64b34b](https://linux-hardware.org/?probe=e17d64b34b) | Dec 18, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f68d8e194a](https://linux-hardware.org/?probe=f68d8e194a) | Dec 18, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [c4b9060346](https://linux-hardware.org/?probe=c4b9060346) | Dec 18, 2021 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [e91c344097](https://linux-hardware.org/?probe=e91c344097) | Dec 18, 2021 |
| MSI           | GE75 Raider 10SE            | Notebook    | [8cd363d60f](https://linux-hardware.org/?probe=8cd363d60f) | Dec 17, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [0bc101f563](https://linux-hardware.org/?probe=0bc101f563) | Dec 17, 2021 |
| Intel         | X99 V1.0                    | Desktop     | [49bca842a4](https://linux-hardware.org/?probe=49bca842a4) | Dec 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [1892cdff8d](https://linux-hardware.org/?probe=1892cdff8d) | Dec 17, 2021 |
| Lenovo        | Product                     | Desktop     | [64951d70ab](https://linux-hardware.org/?probe=64951d70ab) | Dec 16, 2021 |
| Dell          | Latitude 5590               | Notebook    | [db16174d3a](https://linux-hardware.org/?probe=db16174d3a) | Dec 16, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [717b9f1dd0](https://linux-hardware.org/?probe=717b9f1dd0) | Dec 16, 2021 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [571b3e92fc](https://linux-hardware.org/?probe=571b3e92fc) | Dec 16, 2021 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [0cee48a6a7](https://linux-hardware.org/?probe=0cee48a6a7) | Dec 16, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [21ea8cfa3b](https://linux-hardware.org/?probe=21ea8cfa3b) | Dec 16, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [9ed21194f5](https://linux-hardware.org/?probe=9ed21194f5) | Dec 15, 2021 |
| Dell          | 0290HC A00                  | All in one  | [3f067e729f](https://linux-hardware.org/?probe=3f067e729f) | Dec 15, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [2015948e6d](https://linux-hardware.org/?probe=2015948e6d) | Dec 15, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a0a907bbb9](https://linux-hardware.org/?probe=a0a907bbb9) | Dec 13, 2021 |
| HP            | Pavilion g6                 | Notebook    | [a39e3fe72e](https://linux-hardware.org/?probe=a39e3fe72e) | Dec 13, 2021 |
| ASRock        | B560M Pro4                  | Desktop     | [f03914de42](https://linux-hardware.org/?probe=f03914de42) | Dec 13, 2021 |
| Dell          | Precision 5520              | Notebook    | [2b1ae8f2cc](https://linux-hardware.org/?probe=2b1ae8f2cc) | Dec 12, 2021 |
| Dell          | Precision 5510              | Notebook    | [787e9271a8](https://linux-hardware.org/?probe=787e9271a8) | Dec 12, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [bf66a9a6b8](https://linux-hardware.org/?probe=bf66a9a6b8) | Dec 12, 2021 |
| MSI           | Pulse GL76 11UEK            | Notebook    | [e9ea02a9ca](https://linux-hardware.org/?probe=e9ea02a9ca) | Dec 10, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [463119e0f9](https://linux-hardware.org/?probe=463119e0f9) | Dec 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3cb01a3418](https://linux-hardware.org/?probe=3cb01a3418) | Dec 09, 2021 |
| ASRock        | B560M Pro4                  | Desktop     | [ca363e419b](https://linux-hardware.org/?probe=ca363e419b) | Dec 09, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6ad7a31369](https://linux-hardware.org/?probe=6ad7a31369) | Dec 08, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [8473dd1cc0](https://linux-hardware.org/?probe=8473dd1cc0) | Dec 08, 2021 |
| Dell          | Latitude 5590               | Notebook    | [91d343a4d2](https://linux-hardware.org/?probe=91d343a4d2) | Dec 08, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [1540cd62c4](https://linux-hardware.org/?probe=1540cd62c4) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [d0e3422cba](https://linux-hardware.org/?probe=d0e3422cba) | Dec 08, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [4fa997809c](https://linux-hardware.org/?probe=4fa997809c) | Dec 08, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [53a5915a78](https://linux-hardware.org/?probe=53a5915a78) | Dec 08, 2021 |
| Acer          | Aspire TC-105               | Desktop     | [9b258cda27](https://linux-hardware.org/?probe=9b258cda27) | Dec 07, 2021 |
| HP            | 8750                        | Desktop     | [b6c8c71af0](https://linux-hardware.org/?probe=b6c8c71af0) | Dec 07, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [1c3a187ec6](https://linux-hardware.org/?probe=1c3a187ec6) | Dec 07, 2021 |
| HP            | 8750                        | Desktop     | [5c912921e0](https://linux-hardware.org/?probe=5c912921e0) | Dec 07, 2021 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [0114082cf9](https://linux-hardware.org/?probe=0114082cf9) | Dec 07, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [69f260930e](https://linux-hardware.org/?probe=69f260930e) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c12810a81](https://linux-hardware.org/?probe=1c12810a81) | Dec 06, 2021 |
| HP            | Presario CQ57               | Notebook    | [38f630bbc9](https://linux-hardware.org/?probe=38f630bbc9) | Dec 06, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [c4beb99c9c](https://linux-hardware.org/?probe=c4beb99c9c) | Dec 05, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [cd47b9ae21](https://linux-hardware.org/?probe=cd47b9ae21) | Dec 05, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [3fd9c8a1f8](https://linux-hardware.org/?probe=3fd9c8a1f8) | Dec 05, 2021 |
| MSI           | GE62 2QD                    | Notebook    | [f37c114570](https://linux-hardware.org/?probe=f37c114570) | Dec 05, 2021 |
| ASRock        | H55M-LE                     | Desktop     | [350e86d2a2](https://linux-hardware.org/?probe=350e86d2a2) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [4c55363bc2](https://linux-hardware.org/?probe=4c55363bc2) | Dec 04, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [10bd6955bd](https://linux-hardware.org/?probe=10bd6955bd) | Dec 04, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [2c7c189ffa](https://linux-hardware.org/?probe=2c7c189ffa) | Dec 04, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [fd97325649](https://linux-hardware.org/?probe=fd97325649) | Dec 04, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [dac924cd16](https://linux-hardware.org/?probe=dac924cd16) | Dec 04, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [8aadcee8ff](https://linux-hardware.org/?probe=8aadcee8ff) | Dec 04, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [1e8e0ca774](https://linux-hardware.org/?probe=1e8e0ca774) | Dec 03, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [dfc664e15c](https://linux-hardware.org/?probe=dfc664e15c) | Dec 03, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [bebf658c63](https://linux-hardware.org/?probe=bebf658c63) | Dec 03, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGS... | Notebook    | [0faa779766](https://linux-hardware.org/?probe=0faa779766) | Dec 03, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [f0e9159f45](https://linux-hardware.org/?probe=f0e9159f45) | Dec 03, 2021 |
| Dell          | Inspiron N4050              | Notebook    | [46f1d21cbc](https://linux-hardware.org/?probe=46f1d21cbc) | Dec 02, 2021 |
| Acer          | Aspire VN7-572TG            | Notebook    | [b930282529](https://linux-hardware.org/?probe=b930282529) | Dec 02, 2021 |
| MSI           | GE75 Raider 10SE            | Notebook    | [ad71232894](https://linux-hardware.org/?probe=ad71232894) | Dec 02, 2021 |
| HP            | 829A                        | Mini pc     | [a790174646](https://linux-hardware.org/?probe=a790174646) | Dec 02, 2021 |
| MSI           | GE75 Raider 10SE            | Notebook    | [a60a276dff](https://linux-hardware.org/?probe=a60a276dff) | Dec 02, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [4993feea8f](https://linux-hardware.org/?probe=4993feea8f) | Dec 02, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [4b1e061cf3](https://linux-hardware.org/?probe=4b1e061cf3) | Nov 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [acadafa3aa](https://linux-hardware.org/?probe=acadafa3aa) | Nov 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [fc34582970](https://linux-hardware.org/?probe=fc34582970) | Nov 29, 2021 |
| HP            | ProBook 640 G4              | Notebook    | [e58b0e7945](https://linux-hardware.org/?probe=e58b0e7945) | Nov 29, 2021 |
| ASUSTek       | P552LJ                      | Notebook    | [6dbe422798](https://linux-hardware.org/?probe=6dbe422798) | Nov 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [08926b737d](https://linux-hardware.org/?probe=08926b737d) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [6d9c31a411](https://linux-hardware.org/?probe=6d9c31a411) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [e005ddb405](https://linux-hardware.org/?probe=e005ddb405) | Nov 28, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [5e81a55ce3](https://linux-hardware.org/?probe=5e81a55ce3) | Nov 28, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [58d43162d2](https://linux-hardware.org/?probe=58d43162d2) | Nov 28, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [8b5b1397b4](https://linux-hardware.org/?probe=8b5b1397b4) | Nov 28, 2021 |
| Dell          | 0N4YC8 A00                  | Desktop     | [6960aecc48](https://linux-hardware.org/?probe=6960aecc48) | Nov 28, 2021 |
| Dell          | 0K240Y A01                  | Desktop     | [db19440955](https://linux-hardware.org/?probe=db19440955) | Nov 27, 2021 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [dc1f8255a1](https://linux-hardware.org/?probe=dc1f8255a1) | Nov 27, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [4aefcd6dd3](https://linux-hardware.org/?probe=4aefcd6dd3) | Nov 27, 2021 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [109d14527f](https://linux-hardware.org/?probe=109d14527f) | Nov 27, 2021 |
| Dell          | Precision 5530              | Notebook    | [6095ea15d2](https://linux-hardware.org/?probe=6095ea15d2) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [d63786632f](https://linux-hardware.org/?probe=d63786632f) | Nov 26, 2021 |
| HP            | 1497                        | Desktop     | [4fcff3a9a1](https://linux-hardware.org/?probe=4fcff3a9a1) | Nov 26, 2021 |
| MSI           | B460M PRO-VDH               | Desktop     | [4c7d18cb37](https://linux-hardware.org/?probe=4c7d18cb37) | Nov 26, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [74626859f8](https://linux-hardware.org/?probe=74626859f8) | Nov 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [432a7b645a](https://linux-hardware.org/?probe=432a7b645a) | Nov 25, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f0c1e81fb5](https://linux-hardware.org/?probe=f0c1e81fb5) | Nov 25, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [f62619c698](https://linux-hardware.org/?probe=f62619c698) | Nov 24, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [896279284e](https://linux-hardware.org/?probe=896279284e) | Nov 24, 2021 |
| HP            | 212B                        | Desktop     | [0377d5dc76](https://linux-hardware.org/?probe=0377d5dc76) | Nov 23, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [c4eed7c2d5](https://linux-hardware.org/?probe=c4eed7c2d5) | Nov 23, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [10455f4980](https://linux-hardware.org/?probe=10455f4980) | Nov 23, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [8c5bc064e9](https://linux-hardware.org/?probe=8c5bc064e9) | Nov 21, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [d49eff3d64](https://linux-hardware.org/?probe=d49eff3d64) | Nov 21, 2021 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [d2c07efc8b](https://linux-hardware.org/?probe=d2c07efc8b) | Nov 21, 2021 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [5c46d85473](https://linux-hardware.org/?probe=5c46d85473) | Nov 20, 2021 |
| HP            | 304Ah                       | Desktop     | [ff34cb9fb8](https://linux-hardware.org/?probe=ff34cb9fb8) | Nov 20, 2021 |
| Lenovo        | V155-15API 81V5             | Notebook    | [2fa6ddfb10](https://linux-hardware.org/?probe=2fa6ddfb10) | Nov 20, 2021 |
| HP            | 829A                        | Mini pc     | [a906b7c0d4](https://linux-hardware.org/?probe=a906b7c0d4) | Nov 20, 2021 |
| HP            | 829A                        | Mini pc     | [0eabb0317b](https://linux-hardware.org/?probe=0eabb0317b) | Nov 20, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [0cb154dc0b](https://linux-hardware.org/?probe=0cb154dc0b) | Nov 20, 2021 |
| MSI           | GE66 Raider 11UG            | Notebook    | [fe677aa4e9](https://linux-hardware.org/?probe=fe677aa4e9) | Nov 20, 2021 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [571e7e5de4](https://linux-hardware.org/?probe=571e7e5de4) | Nov 19, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [cbdd4628d6](https://linux-hardware.org/?probe=cbdd4628d6) | Nov 19, 2021 |
| HP            | 8599                        | Desktop     | [4103117abb](https://linux-hardware.org/?probe=4103117abb) | Nov 18, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [4b7026b949](https://linux-hardware.org/?probe=4b7026b949) | Nov 18, 2021 |
| Google        | Soraka                      | Tablet      | [72ccad3aa6](https://linux-hardware.org/?probe=72ccad3aa6) | Nov 18, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e4a9f9a630](https://linux-hardware.org/?probe=e4a9f9a630) | Nov 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e85f83dd93](https://linux-hardware.org/?probe=e85f83dd93) | Nov 17, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [ed3c10b44f](https://linux-hardware.org/?probe=ed3c10b44f) | Nov 16, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [70cffc5595](https://linux-hardware.org/?probe=70cffc5595) | Nov 16, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [941a3ff2ca](https://linux-hardware.org/?probe=941a3ff2ca) | Nov 15, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [3f989c08c0](https://linux-hardware.org/?probe=3f989c08c0) | Nov 15, 2021 |
| ASUSTek       | Strix GL703GS_GL703GS       | Notebook    | [6eb0749ee8](https://linux-hardware.org/?probe=6eb0749ee8) | Nov 15, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [6d92264040](https://linux-hardware.org/?probe=6d92264040) | Nov 14, 2021 |
| MSI           | GE75 Raider 10SF            | Notebook    | [140e781aa9](https://linux-hardware.org/?probe=140e781aa9) | Nov 14, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b7cdb93074](https://linux-hardware.org/?probe=b7cdb93074) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ed343e426b](https://linux-hardware.org/?probe=ed343e426b) | Nov 13, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [b3836e81d2](https://linux-hardware.org/?probe=b3836e81d2) | Nov 13, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [8394f01b73](https://linux-hardware.org/?probe=8394f01b73) | Nov 13, 2021 |
| SUPoX COMP... | B250A-BTC PRO               | Desktop     | [523a272559](https://linux-hardware.org/?probe=523a272559) | Nov 13, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [da9478b174](https://linux-hardware.org/?probe=da9478b174) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 20RD004FMH     | Notebook    | [898d6c5381](https://linux-hardware.org/?probe=898d6c5381) | Nov 12, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [86333ab8cf](https://linux-hardware.org/?probe=86333ab8cf) | Nov 12, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d455226b81](https://linux-hardware.org/?probe=d455226b81) | Nov 12, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [e5c77a35e6](https://linux-hardware.org/?probe=e5c77a35e6) | Nov 11, 2021 |
| ASUSTek       | S451LB                      | Notebook    | [996eef15cb](https://linux-hardware.org/?probe=996eef15cb) | Nov 11, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [752b6b8c82](https://linux-hardware.org/?probe=752b6b8c82) | Nov 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [eb66540889](https://linux-hardware.org/?probe=eb66540889) | Nov 10, 2021 |
| Dell          | Latitude E7250              | Notebook    | [5c22b9ed65](https://linux-hardware.org/?probe=5c22b9ed65) | Nov 10, 2021 |
| Google        | Banjo                       | Notebook    | [0fb0b07bf3](https://linux-hardware.org/?probe=0fb0b07bf3) | Nov 09, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [de7daa7785](https://linux-hardware.org/?probe=de7daa7785) | Nov 09, 2021 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [a9a66b59f1](https://linux-hardware.org/?probe=a9a66b59f1) | Nov 09, 2021 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [ffb993e97f](https://linux-hardware.org/?probe=ffb993e97f) | Nov 09, 2021 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [ac46929783](https://linux-hardware.org/?probe=ac46929783) | Nov 09, 2021 |
| Supermicro    | X9DRL-7F                    | Server      | [7e6079e076](https://linux-hardware.org/?probe=7e6079e076) | Nov 08, 2021 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [6f5959b193](https://linux-hardware.org/?probe=6f5959b193) | Nov 08, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [292992ce5a](https://linux-hardware.org/?probe=292992ce5a) | Nov 07, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [2c9f00ee14](https://linux-hardware.org/?probe=2c9f00ee14) | Nov 07, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [dda9f712f8](https://linux-hardware.org/?probe=dda9f712f8) | Nov 07, 2021 |
| Acer          | Aspire 1810TZ               | Notebook    | [b7e445953f](https://linux-hardware.org/?probe=b7e445953f) | Nov 06, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [e05f9fb40e](https://linux-hardware.org/?probe=e05f9fb40e) | Nov 06, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [1b7032f3a3](https://linux-hardware.org/?probe=1b7032f3a3) | Nov 06, 2021 |
| Dell          | Studio 1735                 | Notebook    | [6a444456ef](https://linux-hardware.org/?probe=6a444456ef) | Nov 06, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [056c5c6007](https://linux-hardware.org/?probe=056c5c6007) | Nov 06, 2021 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [44642a2fa4](https://linux-hardware.org/?probe=44642a2fa4) | Nov 06, 2021 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [73cf10090b](https://linux-hardware.org/?probe=73cf10090b) | Nov 06, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [8e3176012c](https://linux-hardware.org/?probe=8e3176012c) | Nov 05, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [43d9b0df9e](https://linux-hardware.org/?probe=43d9b0df9e) | Nov 05, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d6e0b55e4c](https://linux-hardware.org/?probe=d6e0b55e4c) | Nov 04, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | Notebook    | [d6be5f45ee](https://linux-hardware.org/?probe=d6be5f45ee) | Nov 04, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4f70ff5761](https://linux-hardware.org/?probe=4f70ff5761) | Nov 04, 2021 |
| Lenovo        | ThinkPad X230 23252UU       | Notebook    | [8e8f78281b](https://linux-hardware.org/?probe=8e8f78281b) | Nov 04, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [9949b4d2b4](https://linux-hardware.org/?probe=9949b4d2b4) | Nov 03, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [c2e407becb](https://linux-hardware.org/?probe=c2e407becb) | Nov 03, 2021 |
| ASUSTek       | EB1501P                     | Desktop     | [b4407d37ce](https://linux-hardware.org/?probe=b4407d37ce) | Nov 03, 2021 |
| Biostar       | A68MD PRO                   | Desktop     | [19a6612e0a](https://linux-hardware.org/?probe=19a6612e0a) | Nov 03, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [b2e6c63aec](https://linux-hardware.org/?probe=b2e6c63aec) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | Notebook    | [d7c67d8ce7](https://linux-hardware.org/?probe=d7c67d8ce7) | Nov 02, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [6376d7464b](https://linux-hardware.org/?probe=6376d7464b) | Nov 02, 2021 |
| Supermicro    | X9DRL-7F                    | Server      | [bfd8a85a69](https://linux-hardware.org/?probe=bfd8a85a69) | Nov 02, 2021 |
| Biostar       | A68MD PRO                   | Desktop     | [417cbcba6a](https://linux-hardware.org/?probe=417cbcba6a) | Nov 02, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1a8d172b1a](https://linux-hardware.org/?probe=1a8d172b1a) | Nov 02, 2021 |
| Dell          | G3 3579                     | Notebook    | [a616f7e8bb](https://linux-hardware.org/?probe=a616f7e8bb) | Nov 02, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [905e53768d](https://linux-hardware.org/?probe=905e53768d) | Nov 02, 2021 |
| Acer          | Aspire F5-771G              | Notebook    | [d245e85553](https://linux-hardware.org/?probe=d245e85553) | Nov 02, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3a0bd3fa08](https://linux-hardware.org/?probe=3a0bd3fa08) | Nov 01, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [dfc6f722bc](https://linux-hardware.org/?probe=dfc6f722bc) | Nov 01, 2021 |
| Dell          | Inspiron 14 5410            | Notebook    | [6a3d844d87](https://linux-hardware.org/?probe=6a3d844d87) | Oct 30, 2021 |
| Dell          | Inspiron 14 5410            | Notebook    | [2a7532fb18](https://linux-hardware.org/?probe=2a7532fb18) | Oct 30, 2021 |
| Lenovo        | ThinkPad X230 2325L19       | Notebook    | [a120083d3c](https://linux-hardware.org/?probe=a120083d3c) | Oct 30, 2021 |
| Gigabyte      | H55N-USB3                   | Desktop     | [02dffbfea8](https://linux-hardware.org/?probe=02dffbfea8) | Oct 30, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [3abf73fb8a](https://linux-hardware.org/?probe=3abf73fb8a) | Oct 30, 2021 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [1db80a4db5](https://linux-hardware.org/?probe=1db80a4db5) | Oct 30, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [73f2c9ee59](https://linux-hardware.org/?probe=73f2c9ee59) | Oct 30, 2021 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [545eb61311](https://linux-hardware.org/?probe=545eb61311) | Oct 30, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [50b1b1a6c5](https://linux-hardware.org/?probe=50b1b1a6c5) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [a01e524a66](https://linux-hardware.org/?probe=a01e524a66) | Oct 29, 2021 |
| Dell          | Precision 3551              | Notebook    | [f4b1efa60f](https://linux-hardware.org/?probe=f4b1efa60f) | Oct 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [a1d5ea2503](https://linux-hardware.org/?probe=a1d5ea2503) | Oct 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [6d213c2974](https://linux-hardware.org/?probe=6d213c2974) | Oct 29, 2021 |
| HP            | 212B                        | Desktop     | [9d2a807f08](https://linux-hardware.org/?probe=9d2a807f08) | Oct 29, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [b91315ee52](https://linux-hardware.org/?probe=b91315ee52) | Oct 28, 2021 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [c3581d7f8f](https://linux-hardware.org/?probe=c3581d7f8f) | Oct 28, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [03af7df5b2](https://linux-hardware.org/?probe=03af7df5b2) | Oct 28, 2021 |
| HP            | 245 G8 Notebook PC          | Notebook    | [a94d17f64b](https://linux-hardware.org/?probe=a94d17f64b) | Oct 28, 2021 |
| Dell          | Inspiron 3502               | Notebook    | [2f836bc22f](https://linux-hardware.org/?probe=2f836bc22f) | Oct 27, 2021 |
| Dell          | Inspiron 3502               | Notebook    | [252d07f9f5](https://linux-hardware.org/?probe=252d07f9f5) | Oct 27, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [e07abb010e](https://linux-hardware.org/?probe=e07abb010e) | Oct 27, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [e6d67ebc2e](https://linux-hardware.org/?probe=e6d67ebc2e) | Oct 27, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [5bb4e443f9](https://linux-hardware.org/?probe=5bb4e443f9) | Oct 26, 2021 |
| Lenovo        | ThinkCentre M71e 3157RV2    | Desktop     | [6d4dc3e8af](https://linux-hardware.org/?probe=6d4dc3e8af) | Oct 26, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [f20f2bfc32](https://linux-hardware.org/?probe=f20f2bfc32) | Oct 26, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [4a9e20c522](https://linux-hardware.org/?probe=4a9e20c522) | Oct 26, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [0ad7e689f1](https://linux-hardware.org/?probe=0ad7e689f1) | Oct 26, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [633fc31d82](https://linux-hardware.org/?probe=633fc31d82) | Oct 26, 2021 |
| Dell          | Latitude 7390               | Notebook    | [92dcb677f7](https://linux-hardware.org/?probe=92dcb677f7) | Oct 26, 2021 |
| HP            | 212B                        | Desktop     | [b72e4a7240](https://linux-hardware.org/?probe=b72e4a7240) | Oct 26, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [39f15bd886](https://linux-hardware.org/?probe=39f15bd886) | Oct 26, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [984d3d9933](https://linux-hardware.org/?probe=984d3d9933) | Oct 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [111b26a250](https://linux-hardware.org/?probe=111b26a250) | Oct 25, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | Desktop     | [afbb381cf3](https://linux-hardware.org/?probe=afbb381cf3) | Oct 25, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [3134454d4f](https://linux-hardware.org/?probe=3134454d4f) | Oct 24, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [101ca7800d](https://linux-hardware.org/?probe=101ca7800d) | Oct 24, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [eb97afcaa6](https://linux-hardware.org/?probe=eb97afcaa6) | Oct 24, 2021 |
| Lenovo        | G50-45 80MQ                 | Notebook    | [0d0aa3b82b](https://linux-hardware.org/?probe=0d0aa3b82b) | Oct 24, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [cb8bcc4d2d](https://linux-hardware.org/?probe=cb8bcc4d2d) | Oct 22, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [8e1fa1f2af](https://linux-hardware.org/?probe=8e1fa1f2af) | Oct 22, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [0da96530a0](https://linux-hardware.org/?probe=0da96530a0) | Oct 22, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [51162ce3fb](https://linux-hardware.org/?probe=51162ce3fb) | Oct 22, 2021 |
| HP            | ProBook 5320m               | Notebook    | [c3f92d48e5](https://linux-hardware.org/?probe=c3f92d48e5) | Oct 21, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [2d60265f85](https://linux-hardware.org/?probe=2d60265f85) | Oct 21, 2021 |
| Notebook      | NS50MU                      | Notebook    | [ad8b0e22a7](https://linux-hardware.org/?probe=ad8b0e22a7) | Oct 21, 2021 |
| ASUSTek       | ZenBook UX562FAC            | Convertible | [49b0f21555](https://linux-hardware.org/?probe=49b0f21555) | Oct 20, 2021 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [25c0517a63](https://linux-hardware.org/?probe=25c0517a63) | Oct 20, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [273a5ff27d](https://linux-hardware.org/?probe=273a5ff27d) | Oct 20, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [6214c9eb86](https://linux-hardware.org/?probe=6214c9eb86) | Oct 20, 2021 |
| Gateway       | NV55S                       | Notebook    | [0781065494](https://linux-hardware.org/?probe=0781065494) | Oct 20, 2021 |
| Gateway       | NV55S                       | Notebook    | [562bd81383](https://linux-hardware.org/?probe=562bd81383) | Oct 20, 2021 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [ec41eeb7c0](https://linux-hardware.org/?probe=ec41eeb7c0) | Oct 20, 2021 |
| Acer          | Aspire V5-571PG             | Notebook    | [7302dc6be1](https://linux-hardware.org/?probe=7302dc6be1) | Oct 19, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [a478cf02e1](https://linux-hardware.org/?probe=a478cf02e1) | Oct 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [bfadd59ae5](https://linux-hardware.org/?probe=bfadd59ae5) | Oct 18, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [57ee9bd872](https://linux-hardware.org/?probe=57ee9bd872) | Oct 18, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [696a85e281](https://linux-hardware.org/?probe=696a85e281) | Oct 18, 2021 |
| Intel         | D54250WYK H13922-303        | Desktop     | [21b715e26a](https://linux-hardware.org/?probe=21b715e26a) | Oct 17, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [4c643fc684](https://linux-hardware.org/?probe=4c643fc684) | Oct 17, 2021 |
| Timi          | A35                         | Notebook    | [318b31ee5d](https://linux-hardware.org/?probe=318b31ee5d) | Oct 17, 2021 |
| Timi          | A34                         | Notebook    | [e2fbec93e6](https://linux-hardware.org/?probe=e2fbec93e6) | Oct 17, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [cb6caefa10](https://linux-hardware.org/?probe=cb6caefa10) | Oct 17, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8b87eef23f](https://linux-hardware.org/?probe=8b87eef23f) | Oct 16, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [57eaf5a3e0](https://linux-hardware.org/?probe=57eaf5a3e0) | Oct 15, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [80c959f7ca](https://linux-hardware.org/?probe=80c959f7ca) | Oct 15, 2021 |
| Samsung       | DP505A2G-K01CH SAMSUNG_S... | All in one  | [4939b251f2](https://linux-hardware.org/?probe=4939b251f2) | Oct 15, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [4603126532](https://linux-hardware.org/?probe=4603126532) | Oct 15, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8c2ed0d838](https://linux-hardware.org/?probe=8c2ed0d838) | Oct 15, 2021 |
| Notebook      | P775DM3(-G)                 | Notebook    | [9403539acc](https://linux-hardware.org/?probe=9403539acc) | Oct 15, 2021 |
| MSI           | H61M-P20                    | Desktop     | [4c9df75eee](https://linux-hardware.org/?probe=4c9df75eee) | Oct 15, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [0a8aa1439f](https://linux-hardware.org/?probe=0a8aa1439f) | Oct 15, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [ae1729d840](https://linux-hardware.org/?probe=ae1729d840) | Oct 15, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [0a048a009d](https://linux-hardware.org/?probe=0a048a009d) | Oct 15, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [831fff897a](https://linux-hardware.org/?probe=831fff897a) | Oct 15, 2021 |
| ASRock        | A520M-ITX/ac                | Desktop     | [6a9bd62b2a](https://linux-hardware.org/?probe=6a9bd62b2a) | Oct 14, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [fb676e6e3f](https://linux-hardware.org/?probe=fb676e6e3f) | Oct 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [e9abe9397f](https://linux-hardware.org/?probe=e9abe9397f) | Oct 14, 2021 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [b5c229711c](https://linux-hardware.org/?probe=b5c229711c) | Oct 14, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0b5ca0df4e](https://linux-hardware.org/?probe=0b5ca0df4e) | Oct 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [26c1610442](https://linux-hardware.org/?probe=26c1610442) | Oct 14, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [e5391d41e0](https://linux-hardware.org/?probe=e5391d41e0) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [3f6e406107](https://linux-hardware.org/?probe=3f6e406107) | Oct 14, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a0c897a604](https://linux-hardware.org/?probe=a0c897a604) | Oct 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6559ae09ed](https://linux-hardware.org/?probe=6559ae09ed) | Oct 13, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [cc3e4f0eb1](https://linux-hardware.org/?probe=cc3e4f0eb1) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [da1bab4a9c](https://linux-hardware.org/?probe=da1bab4a9c) | Oct 13, 2021 |
| Dell          | Latitude E6320              | Notebook    | [4bea60d049](https://linux-hardware.org/?probe=4bea60d049) | Oct 12, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [928665d302](https://linux-hardware.org/?probe=928665d302) | Oct 12, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [edd8f01f22](https://linux-hardware.org/?probe=edd8f01f22) | Oct 12, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9dc8d76ce0](https://linux-hardware.org/?probe=9dc8d76ce0) | Oct 12, 2021 |
| SHENZHEN X... | ST106                       | Notebook    | [5ca1710273](https://linux-hardware.org/?probe=5ca1710273) | Oct 11, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [138c57899f](https://linux-hardware.org/?probe=138c57899f) | Oct 11, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f4cbdf70ef](https://linux-hardware.org/?probe=f4cbdf70ef) | Oct 11, 2021 |
| ASUSTek       | X58L                        | Notebook    | [41130a006f](https://linux-hardware.org/?probe=41130a006f) | Oct 11, 2021 |
| ASUSTek       | X58L                        | Notebook    | [d2a76fcd0f](https://linux-hardware.org/?probe=d2a76fcd0f) | Oct 11, 2021 |
| HP            | 8767 A                      | Desktop     | [9e052340b3](https://linux-hardware.org/?probe=9e052340b3) | Oct 11, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [1f8f531e26](https://linux-hardware.org/?probe=1f8f531e26) | Oct 11, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [24dfac2738](https://linux-hardware.org/?probe=24dfac2738) | Oct 10, 2021 |
| HP            | EliteBook 2760p             | Notebook    | [0b1f6a34ce](https://linux-hardware.org/?probe=0b1f6a34ce) | Oct 10, 2021 |
| Dell          | Latitude 7490               | Notebook    | [8462c89ad6](https://linux-hardware.org/?probe=8462c89ad6) | Oct 10, 2021 |
| Google        | Kohaku                      | Notebook    | [7237ede542](https://linux-hardware.org/?probe=7237ede542) | Oct 10, 2021 |
| Dell          | Precision 5530              | Notebook    | [7f78c88ea8](https://linux-hardware.org/?probe=7f78c88ea8) | Oct 10, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [dd465bf3e8](https://linux-hardware.org/?probe=dd465bf3e8) | Oct 10, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [b00a9b9ff3](https://linux-hardware.org/?probe=b00a9b9ff3) | Oct 09, 2021 |
| HP            | Notebook                    | Notebook    | [8051753f57](https://linux-hardware.org/?probe=8051753f57) | Oct 09, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [97dbb56e7f](https://linux-hardware.org/?probe=97dbb56e7f) | Oct 08, 2021 |
| HP            | ProBook 4530s               | Notebook    | [1e0b067117](https://linux-hardware.org/?probe=1e0b067117) | Oct 07, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [bc7f078524](https://linux-hardware.org/?probe=bc7f078524) | Oct 07, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [26501031e8](https://linux-hardware.org/?probe=26501031e8) | Oct 07, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [07b92ffa9f](https://linux-hardware.org/?probe=07b92ffa9f) | Oct 06, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [90c1b2e414](https://linux-hardware.org/?probe=90c1b2e414) | Oct 06, 2021 |
| Dell          | Precision M6800             | Notebook    | [24e7a40a7a](https://linux-hardware.org/?probe=24e7a40a7a) | Oct 06, 2021 |
| GPU Compan... | GWTC116-2                   | Notebook    | [f6025d3bd2](https://linux-hardware.org/?probe=f6025d3bd2) | Oct 05, 2021 |
| GPU Compan... | GWTC116-2                   | Notebook    | [76ffc45c2b](https://linux-hardware.org/?probe=76ffc45c2b) | Oct 05, 2021 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [459d0f2e53](https://linux-hardware.org/?probe=459d0f2e53) | Oct 04, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [03ba78f145](https://linux-hardware.org/?probe=03ba78f145) | Oct 04, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [29322bf1de](https://linux-hardware.org/?probe=29322bf1de) | Oct 04, 2021 |
| CyberPower... | TRACER V                    | Notebook    | [3f47af726f](https://linux-hardware.org/?probe=3f47af726f) | Oct 04, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [23c12340c8](https://linux-hardware.org/?probe=23c12340c8) | Oct 04, 2021 |
| MSI           | Traveller 1591              | Notebook    | [46430a6e00](https://linux-hardware.org/?probe=46430a6e00) | Oct 04, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [d350652289](https://linux-hardware.org/?probe=d350652289) | Oct 03, 2021 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | Desktop     | [a667195cd1](https://linux-hardware.org/?probe=a667195cd1) | Oct 03, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [e3d2756797](https://linux-hardware.org/?probe=e3d2756797) | Oct 03, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [cdb8dd9b53](https://linux-hardware.org/?probe=cdb8dd9b53) | Oct 03, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bea39ba8be](https://linux-hardware.org/?probe=bea39ba8be) | Oct 03, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [6b9d5f5444](https://linux-hardware.org/?probe=6b9d5f5444) | Oct 02, 2021 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [fd46c16bb7](https://linux-hardware.org/?probe=fd46c16bb7) | Oct 01, 2021 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [9aafd5b0ae](https://linux-hardware.org/?probe=9aafd5b0ae) | Sep 30, 2021 |
| Positivo      | Mobile                      | Notebook    | [fb85092913](https://linux-hardware.org/?probe=fb85092913) | Sep 30, 2021 |
| Positivo      | Mobile                      | Notebook    | [e45a4b5186](https://linux-hardware.org/?probe=e45a4b5186) | Sep 30, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [2e1b563aa1](https://linux-hardware.org/?probe=2e1b563aa1) | Sep 29, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [fbc7a613a6](https://linux-hardware.org/?probe=fbc7a613a6) | Sep 29, 2021 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [8366a7edd1](https://linux-hardware.org/?probe=8366a7edd1) | Sep 29, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [569dd82022](https://linux-hardware.org/?probe=569dd82022) | Sep 28, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [8641901755](https://linux-hardware.org/?probe=8641901755) | Sep 27, 2021 |
| Dell          | System XPS L502X            | Notebook    | [1bb2d0be95](https://linux-hardware.org/?probe=1bb2d0be95) | Sep 26, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | Desktop     | [c91a5b0d8d](https://linux-hardware.org/?probe=c91a5b0d8d) | Sep 25, 2021 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [628b05680b](https://linux-hardware.org/?probe=628b05680b) | Sep 25, 2021 |
| ASUSTek       | UX330UA                     | Notebook    | [175fc7f169](https://linux-hardware.org/?probe=175fc7f169) | Sep 25, 2021 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [a08b313e62](https://linux-hardware.org/?probe=a08b313e62) | Sep 25, 2021 |
| Lenovo        | ThinkPad X61s 7667DE3       | Notebook    | [9d3daab4b3](https://linux-hardware.org/?probe=9d3daab4b3) | Sep 25, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [fe24c7bac1](https://linux-hardware.org/?probe=fe24c7bac1) | Sep 25, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [24edfcf0ef](https://linux-hardware.org/?probe=24edfcf0ef) | Sep 25, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [6178de862b](https://linux-hardware.org/?probe=6178de862b) | Sep 24, 2021 |
| MSI           | GS60 2PE Ghost Pro          | Notebook    | [edb53f3a06](https://linux-hardware.org/?probe=edb53f3a06) | Sep 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e4c16022ab](https://linux-hardware.org/?probe=e4c16022ab) | Sep 24, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [0a2987d902](https://linux-hardware.org/?probe=0a2987d902) | Sep 24, 2021 |
| Positivo      | Smash3                      | Notebook    | [9789e38ff6](https://linux-hardware.org/?probe=9789e38ff6) | Sep 23, 2021 |
| Gigabyte      | H410M S2H V2                | Desktop     | [970a619e86](https://linux-hardware.org/?probe=970a619e86) | Sep 23, 2021 |
| Lenovo        | ThinkPad T580 20L90026RT    | Notebook    | [227465cf98](https://linux-hardware.org/?probe=227465cf98) | Sep 23, 2021 |
| Dell          | Inspiron 3531               | Notebook    | [43e74b0bbb](https://linux-hardware.org/?probe=43e74b0bbb) | Sep 23, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6ebd72e8d5](https://linux-hardware.org/?probe=6ebd72e8d5) | Sep 23, 2021 |
| ASRock        | Z97 Pro4                    | Desktop     | [25e00fc504](https://linux-hardware.org/?probe=25e00fc504) | Sep 23, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [abdedf857f](https://linux-hardware.org/?probe=abdedf857f) | Sep 23, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [1473ddbea8](https://linux-hardware.org/?probe=1473ddbea8) | Sep 22, 2021 |
| Lenovo        | ThinkPad T520 42406AG       | Notebook    | [ca498dc06d](https://linux-hardware.org/?probe=ca498dc06d) | Sep 22, 2021 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | Notebook    | [0a99b9ac87](https://linux-hardware.org/?probe=0a99b9ac87) | Sep 22, 2021 |
| Lenovo        | ThinkPad E555 20DHA01MCD    | Notebook    | [ea86578390](https://linux-hardware.org/?probe=ea86578390) | Sep 22, 2021 |
| Intel         | Eaglelake Fab D             | Desktop     | [acd05f91f6](https://linux-hardware.org/?probe=acd05f91f6) | Sep 21, 2021 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [f18ba9c670](https://linux-hardware.org/?probe=f18ba9c670) | Sep 21, 2021 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [a5dea4108e](https://linux-hardware.org/?probe=a5dea4108e) | Sep 21, 2021 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | Notebook    | [1b82bac47b](https://linux-hardware.org/?probe=1b82bac47b) | Sep 21, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [c1b1b6661d](https://linux-hardware.org/?probe=c1b1b6661d) | Sep 20, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [d8df9a881c](https://linux-hardware.org/?probe=d8df9a881c) | Sep 20, 2021 |
| Lenovo        | ThinkBook 14s-IML 20RS      | Notebook    | [f93df3c890](https://linux-hardware.org/?probe=f93df3c890) | Sep 19, 2021 |
| ASUSTek       | K73SJ                       | Notebook    | [ac01f64caa](https://linux-hardware.org/?probe=ac01f64caa) | Sep 19, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [1a8706e831](https://linux-hardware.org/?probe=1a8706e831) | Sep 18, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [0362443cc0](https://linux-hardware.org/?probe=0362443cc0) | Sep 18, 2021 |
| Gigabyte      | A520M S2H                   | Desktop     | [1db5fc32c3](https://linux-hardware.org/?probe=1db5fc32c3) | Sep 18, 2021 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [2bffdf4c3d](https://linux-hardware.org/?probe=2bffdf4c3d) | Sep 18, 2021 |
| Acer          | Aspire XC-830               | Desktop     | [c2479661bc](https://linux-hardware.org/?probe=c2479661bc) | Sep 18, 2021 |
| ASUSTek       | P8P67                       | Desktop     | [8c1582c3ed](https://linux-hardware.org/?probe=8c1582c3ed) | Sep 18, 2021 |
| Dell          | 0RW199                      | Desktop     | [0e6d4730fc](https://linux-hardware.org/?probe=0e6d4730fc) | Sep 17, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [fb99d0767d](https://linux-hardware.org/?probe=fb99d0767d) | Sep 17, 2021 |
| HP            | 304Ah                       | Desktop     | [77079c1ca7](https://linux-hardware.org/?probe=77079c1ca7) | Sep 16, 2021 |
| ASUSTek       | TP500LN                     | Notebook    | [5e377590c7](https://linux-hardware.org/?probe=5e377590c7) | Sep 16, 2021 |
| Unknown       | Unknown                     | Notebook    | [d7b86e803f](https://linux-hardware.org/?probe=d7b86e803f) | Sep 16, 2021 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [c70024afd4](https://linux-hardware.org/?probe=c70024afd4) | Sep 16, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [0f8479d13d](https://linux-hardware.org/?probe=0f8479d13d) | Sep 15, 2021 |
| Dell          | 0J8H4R A00                  | Desktop     | [d482d475f7](https://linux-hardware.org/?probe=d482d475f7) | Sep 15, 2021 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [21c50317b2](https://linux-hardware.org/?probe=21c50317b2) | Sep 14, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [2e48186431](https://linux-hardware.org/?probe=2e48186431) | Sep 14, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [15fa98aa93](https://linux-hardware.org/?probe=15fa98aa93) | Sep 14, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e84546c757](https://linux-hardware.org/?probe=e84546c757) | Sep 14, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [f574cad138](https://linux-hardware.org/?probe=f574cad138) | Sep 13, 2021 |
| HP            | 0AECh D                     | Desktop     | [42d762e479](https://linux-hardware.org/?probe=42d762e479) | Sep 12, 2021 |
| ASUSTek       | TUF Gaming FA506IV_TUF56... | Notebook    | [9cdec29684](https://linux-hardware.org/?probe=9cdec29684) | Sep 12, 2021 |
| Sony          | VPCCW25FL                   | Notebook    | [5dcd7a6c93](https://linux-hardware.org/?probe=5dcd7a6c93) | Sep 12, 2021 |
| Lenovo        | ThinkPad T550 20CJS03300    | Notebook    | [2b53cd0d2d](https://linux-hardware.org/?probe=2b53cd0d2d) | Sep 11, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [ea741ff4f6](https://linux-hardware.org/?probe=ea741ff4f6) | Sep 10, 2021 |
| Pegatron      | Narra6                      | Desktop     | [197972681f](https://linux-hardware.org/?probe=197972681f) | Sep 09, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [8a2814fe20](https://linux-hardware.org/?probe=8a2814fe20) | Sep 09, 2021 |
| Google        | Kohaku                      | Notebook    | [787dfdb77f](https://linux-hardware.org/?probe=787dfdb77f) | Sep 09, 2021 |
| Google        | Kohaku                      | Notebook    | [548837aac5](https://linux-hardware.org/?probe=548837aac5) | Sep 09, 2021 |
| Gigabyte      | Z170M-D3H DDR3-CF           | Desktop     | [e81b4b3e42](https://linux-hardware.org/?probe=e81b4b3e42) | Sep 09, 2021 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [fb3c4b683c](https://linux-hardware.org/?probe=fb3c4b683c) | Sep 08, 2021 |
| HP            | ENVY Notebook               | Notebook    | [5dbf3a9523](https://linux-hardware.org/?probe=5dbf3a9523) | Sep 08, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [df37af4740](https://linux-hardware.org/?probe=df37af4740) | Sep 08, 2021 |
| HP            | 0AECh D                     | Desktop     | [be336df1da](https://linux-hardware.org/?probe=be336df1da) | Sep 08, 2021 |
| HP            | ENVY Notebook               | Notebook    | [3f338ee0d6](https://linux-hardware.org/?probe=3f338ee0d6) | Sep 08, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [846ba30d43](https://linux-hardware.org/?probe=846ba30d43) | Sep 07, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [014c8bb745](https://linux-hardware.org/?probe=014c8bb745) | Sep 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [99898b4c58](https://linux-hardware.org/?probe=99898b4c58) | Sep 07, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | Desktop     | [922e1625b6](https://linux-hardware.org/?probe=922e1625b6) | Sep 07, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [07db84c018](https://linux-hardware.org/?probe=07db84c018) | Sep 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [aad125e760](https://linux-hardware.org/?probe=aad125e760) | Sep 07, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [0ab8136443](https://linux-hardware.org/?probe=0ab8136443) | Sep 07, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [48a05b1697](https://linux-hardware.org/?probe=48a05b1697) | Sep 07, 2021 |
| Dell          | Latitude 7490               | Notebook    | [5a238ecfcc](https://linux-hardware.org/?probe=5a238ecfcc) | Sep 06, 2021 |
| Pegatron      | Eureka3                     | Desktop     | [1a6858321a](https://linux-hardware.org/?probe=1a6858321a) | Sep 06, 2021 |
| Pegatron      | Eureka3                     | Desktop     | [c68cf534fd](https://linux-hardware.org/?probe=c68cf534fd) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c5fbf3298a](https://linux-hardware.org/?probe=c5fbf3298a) | Sep 06, 2021 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [b34b284f99](https://linux-hardware.org/?probe=b34b284f99) | Sep 06, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [6da34b890e](https://linux-hardware.org/?probe=6da34b890e) | Sep 06, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [889fd56c8b](https://linux-hardware.org/?probe=889fd56c8b) | Sep 05, 2021 |
| ASUSTek       | F1A55-M LX R2.0             | Desktop     | [7a0ea791be](https://linux-hardware.org/?probe=7a0ea791be) | Sep 05, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [10f34cd263](https://linux-hardware.org/?probe=10f34cd263) | Sep 05, 2021 |
| ASUSTek       | F1A55-M LX R2.0             | Desktop     | [559710589f](https://linux-hardware.org/?probe=559710589f) | Sep 05, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | Desktop     | [0cb477dc5b](https://linux-hardware.org/?probe=0cb477dc5b) | Sep 05, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [2e4363f1bc](https://linux-hardware.org/?probe=2e4363f1bc) | Sep 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fe1d6870db](https://linux-hardware.org/?probe=fe1d6870db) | Sep 05, 2021 |
| ASUSTek       | TUF Gaming FA506IV_TUF56... | Notebook    | [7366162a3e](https://linux-hardware.org/?probe=7366162a3e) | Sep 05, 2021 |
| MSI           | GS63 7RE                    | Notebook    | [db1e9a9bd4](https://linux-hardware.org/?probe=db1e9a9bd4) | Sep 04, 2021 |
| Lenovo        | ThinkPad T540p 20BE0084B... | Notebook    | [45914d6e06](https://linux-hardware.org/?probe=45914d6e06) | Sep 04, 2021 |
| Panasonic     | CFSX4-1                     | Notebook    | [d474bc1b91](https://linux-hardware.org/?probe=d474bc1b91) | Sep 03, 2021 |
| Panasonic     | CFSX4-1                     | Notebook    | [bee71431a0](https://linux-hardware.org/?probe=bee71431a0) | Sep 03, 2021 |
| Google        | Panther                     | Desktop     | [aef76824a2](https://linux-hardware.org/?probe=aef76824a2) | Sep 02, 2021 |
| FUJITSU CL... | LIFEBOOK U9310              | Notebook    | [48113d6636](https://linux-hardware.org/?probe=48113d6636) | Sep 02, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [a9c5f44138](https://linux-hardware.org/?probe=a9c5f44138) | Sep 02, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [ba7977bacc](https://linux-hardware.org/?probe=ba7977bacc) | Sep 01, 2021 |
| Lenovo        | ThinkPad E14 20RA004YUS     | Notebook    | [2eed4a9229](https://linux-hardware.org/?probe=2eed4a9229) | Sep 01, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | Desktop     | [f9084037fb](https://linux-hardware.org/?probe=f9084037fb) | Sep 01, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [67f170c148](https://linux-hardware.org/?probe=67f170c148) | Sep 01, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | Desktop     | [6cc08cc5fb](https://linux-hardware.org/?probe=6cc08cc5fb) | Sep 01, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [0a38ee6028](https://linux-hardware.org/?probe=0a38ee6028) | Sep 01, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | Desktop     | [cd40ede4b6](https://linux-hardware.org/?probe=cd40ede4b6) | Sep 01, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [9a8b3b3880](https://linux-hardware.org/?probe=9a8b3b3880) | Sep 01, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | Desktop     | [e0439d7048](https://linux-hardware.org/?probe=e0439d7048) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b409334e94](https://linux-hardware.org/?probe=b409334e94) | Aug 30, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | Desktop     | [969162fe45](https://linux-hardware.org/?probe=969162fe45) | Aug 30, 2021 |
| Lenovo        | SDK0J40705 WIN 342503681... | Desktop     | [d532b9c69c](https://linux-hardware.org/?probe=d532b9c69c) | Aug 30, 2021 |
| Dell          | Latitude 5420               | Notebook    | [335717eb52](https://linux-hardware.org/?probe=335717eb52) | Aug 30, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [c56901e13e](https://linux-hardware.org/?probe=c56901e13e) | Aug 30, 2021 |
| ASRock        | B550 Extreme4               | Desktop     | [07024d83ca](https://linux-hardware.org/?probe=07024d83ca) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7097749e7d](https://linux-hardware.org/?probe=7097749e7d) | Aug 30, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [d2ce2247c6](https://linux-hardware.org/?probe=d2ce2247c6) | Aug 30, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [153ad5ee53](https://linux-hardware.org/?probe=153ad5ee53) | Aug 30, 2021 |
| Gigabyte      | A520M S2H                   | Desktop     | [1c95ab3662](https://linux-hardware.org/?probe=1c95ab3662) | Aug 29, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [7b8f7d0fb9](https://linux-hardware.org/?probe=7b8f7d0fb9) | Aug 29, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [a113806a4a](https://linux-hardware.org/?probe=a113806a4a) | Aug 29, 2021 |
| SUPoX COMP... | B250A-BTC PRO               | Desktop     | [106ea40927](https://linux-hardware.org/?probe=106ea40927) | Aug 29, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [13142f679a](https://linux-hardware.org/?probe=13142f679a) | Aug 28, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [b79861fda0](https://linux-hardware.org/?probe=b79861fda0) | Aug 28, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [7f53bb7787](https://linux-hardware.org/?probe=7f53bb7787) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [4d249ae75f](https://linux-hardware.org/?probe=4d249ae75f) | Aug 28, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [f15a7392b9](https://linux-hardware.org/?probe=f15a7392b9) | Aug 27, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [63cfcbea30](https://linux-hardware.org/?probe=63cfcbea30) | Aug 27, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [5374669067](https://linux-hardware.org/?probe=5374669067) | Aug 26, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [3129839a3b](https://linux-hardware.org/?probe=3129839a3b) | Aug 26, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0a3ff1ead5](https://linux-hardware.org/?probe=0a3ff1ead5) | Aug 25, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8091745305](https://linux-hardware.org/?probe=8091745305) | Aug 25, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [97244fc520](https://linux-hardware.org/?probe=97244fc520) | Aug 24, 2021 |
| HP            | Pavilion g7                 | Notebook    | [bd69b29a21](https://linux-hardware.org/?probe=bd69b29a21) | Aug 24, 2021 |
| Google        | Cyan                        | Notebook    | [b8b9ee3f4b](https://linux-hardware.org/?probe=b8b9ee3f4b) | Aug 24, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [2cd4785aec](https://linux-hardware.org/?probe=2cd4785aec) | Aug 23, 2021 |
| Dell          | Latitude E6510              | Notebook    | [79b48c22ef](https://linux-hardware.org/?probe=79b48c22ef) | Aug 23, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [d0d5aa4d58](https://linux-hardware.org/?probe=d0d5aa4d58) | Aug 23, 2021 |
| Lenovo        | IdeaPad U530 Touch 20289    | Notebook    | [21f27a86e7](https://linux-hardware.org/?probe=21f27a86e7) | Aug 23, 2021 |
| ASUSTek       | H61-PLUS                    | Desktop     | [806118d8b3](https://linux-hardware.org/?probe=806118d8b3) | Aug 22, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [b1923f2545](https://linux-hardware.org/?probe=b1923f2545) | Aug 22, 2021 |
| Dell          | Latitude E6400              | Notebook    | [89bdf7b44a](https://linux-hardware.org/?probe=89bdf7b44a) | Aug 21, 2021 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [d9a6f9c739](https://linux-hardware.org/?probe=d9a6f9c739) | Aug 21, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [1114f42cd0](https://linux-hardware.org/?probe=1114f42cd0) | Aug 21, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [44188d0e94](https://linux-hardware.org/?probe=44188d0e94) | Aug 21, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ba857882e8](https://linux-hardware.org/?probe=ba857882e8) | Aug 20, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [6f08d0dd20](https://linux-hardware.org/?probe=6f08d0dd20) | Aug 20, 2021 |
| Dell          | 0RY007                      | Desktop     | [c0cc6172aa](https://linux-hardware.org/?probe=c0cc6172aa) | Aug 20, 2021 |
| Dell          | Latitude E4200              | Notebook    | [db5bad5ade](https://linux-hardware.org/?probe=db5bad5ade) | Aug 20, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [b708963e17](https://linux-hardware.org/?probe=b708963e17) | Aug 20, 2021 |
| Gigabyte      | M61SME-S2L                  | Desktop     | [8108bbbd72](https://linux-hardware.org/?probe=8108bbbd72) | Aug 20, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [85b8505955](https://linux-hardware.org/?probe=85b8505955) | Aug 20, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [4f52520969](https://linux-hardware.org/?probe=4f52520969) | Aug 20, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [d5124a46f4](https://linux-hardware.org/?probe=d5124a46f4) | Aug 20, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [82ff6985ce](https://linux-hardware.org/?probe=82ff6985ce) | Aug 18, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [a43f59c4ab](https://linux-hardware.org/?probe=a43f59c4ab) | Aug 18, 2021 |
| ASUSTek       | Z170-WS                     | Desktop     | [ac73f29c0f](https://linux-hardware.org/?probe=ac73f29c0f) | Aug 18, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [49eb3e8236](https://linux-hardware.org/?probe=49eb3e8236) | Aug 18, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [4f0fc1bae7](https://linux-hardware.org/?probe=4f0fc1bae7) | Aug 18, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [94f71656d6](https://linux-hardware.org/?probe=94f71656d6) | Aug 18, 2021 |
| Lenovo        | ThinkPad E580 20KS0039GE    | Notebook    | [cbef0f044d](https://linux-hardware.org/?probe=cbef0f044d) | Aug 17, 2021 |
| PC Special... | N130BU                      | Notebook    | [5fee63c283](https://linux-hardware.org/?probe=5fee63c283) | Aug 17, 2021 |
| Lenovo        | ThinkPad X230 2325V1K       | Notebook    | [7d414b5aee](https://linux-hardware.org/?probe=7d414b5aee) | Aug 17, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [05e4a8bcb2](https://linux-hardware.org/?probe=05e4a8bcb2) | Aug 16, 2021 |
| Dell          | XPS 17 9710                 | Notebook    | [c872a17921](https://linux-hardware.org/?probe=c872a17921) | Aug 16, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [56d35bbff9](https://linux-hardware.org/?probe=56d35bbff9) | Aug 16, 2021 |
| HP            | Pavilion g7                 | Notebook    | [1767745263](https://linux-hardware.org/?probe=1767745263) | Aug 15, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [de8b0ced34](https://linux-hardware.org/?probe=de8b0ced34) | Aug 15, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [39c2edeacd](https://linux-hardware.org/?probe=39c2edeacd) | Aug 15, 2021 |
| Dell          | Vostro 14 5401              | Notebook    | [af21a56956](https://linux-hardware.org/?probe=af21a56956) | Aug 14, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [599f91ad85](https://linux-hardware.org/?probe=599f91ad85) | Aug 14, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [cf6e706210](https://linux-hardware.org/?probe=cf6e706210) | Aug 14, 2021 |
| HP            | Notebook                    | Notebook    | [53235618da](https://linux-hardware.org/?probe=53235618da) | Aug 13, 2021 |
| HP            | 8653 A                      | Desktop     | [7ba975c504](https://linux-hardware.org/?probe=7ba975c504) | Aug 13, 2021 |
| HP            | Pavilion dv7                | Notebook    | [bfb43959b7](https://linux-hardware.org/?probe=bfb43959b7) | Aug 13, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [3e73238fc6](https://linux-hardware.org/?probe=3e73238fc6) | Aug 13, 2021 |
| SYWZ          | S210H Series                | Desktop     | [72d2c9aafc](https://linux-hardware.org/?probe=72d2c9aafc) | Aug 13, 2021 |
| ASUSTek       | UX21E                       | Notebook    | [d334eaddee](https://linux-hardware.org/?probe=d334eaddee) | Aug 13, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [bf1444d4f9](https://linux-hardware.org/?probe=bf1444d4f9) | Aug 12, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [e898a5da94](https://linux-hardware.org/?probe=e898a5da94) | Aug 12, 2021 |
| ASUSTek       | M4A87TD                     | Desktop     | [c5c19a5f46](https://linux-hardware.org/?probe=c5c19a5f46) | Aug 11, 2021 |
| Dell          | 0XGMD0 A00                  | All in one  | [cd01c1ddbd](https://linux-hardware.org/?probe=cd01c1ddbd) | Aug 11, 2021 |
| Dell          | 0XGMD0 A00                  | All in one  | [9fe670524b](https://linux-hardware.org/?probe=9fe670524b) | Aug 11, 2021 |
| MSI           | B450M GAMING PLUS           | Desktop     | [18ff34f941](https://linux-hardware.org/?probe=18ff34f941) | Aug 10, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [e3508d3cd3](https://linux-hardware.org/?probe=e3508d3cd3) | Aug 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [a9baf23c04](https://linux-hardware.org/?probe=a9baf23c04) | Aug 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [76ef4ade5e](https://linux-hardware.org/?probe=76ef4ade5e) | Aug 10, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f2c3f335f8](https://linux-hardware.org/?probe=f2c3f335f8) | Aug 09, 2021 |
| Lenovo        | ThinkPad E15 20RD003JRT     | Notebook    | [761bc4f353](https://linux-hardware.org/?probe=761bc4f353) | Aug 09, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [fed696b5e3](https://linux-hardware.org/?probe=fed696b5e3) | Aug 08, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [3a25064fc2](https://linux-hardware.org/?probe=3a25064fc2) | Aug 08, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [02bdf9e250](https://linux-hardware.org/?probe=02bdf9e250) | Aug 08, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [31891cbc13](https://linux-hardware.org/?probe=31891cbc13) | Aug 08, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [e5a87d0b14](https://linux-hardware.org/?probe=e5a87d0b14) | Aug 08, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [09efdaba88](https://linux-hardware.org/?probe=09efdaba88) | Aug 08, 2021 |
| ASUSTek       | FX503VD                     | Notebook    | [7c2b153867](https://linux-hardware.org/?probe=7c2b153867) | Aug 08, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [bd0ee7aa7f](https://linux-hardware.org/?probe=bd0ee7aa7f) | Aug 08, 2021 |
| Dell          | Latitude E5440              | Notebook    | [cf175f4a5d](https://linux-hardware.org/?probe=cf175f4a5d) | Aug 08, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c64960a834](https://linux-hardware.org/?probe=c64960a834) | Aug 07, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [3bde2e73c1](https://linux-hardware.org/?probe=3bde2e73c1) | Aug 07, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [d701717927](https://linux-hardware.org/?probe=d701717927) | Aug 07, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [af29cc7bcf](https://linux-hardware.org/?probe=af29cc7bcf) | Aug 07, 2021 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [c98a94e99c](https://linux-hardware.org/?probe=c98a94e99c) | Aug 06, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [87717d0c5d](https://linux-hardware.org/?probe=87717d0c5d) | Aug 06, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a319e4cbd9](https://linux-hardware.org/?probe=a319e4cbd9) | Aug 06, 2021 |
| Gigabyte      | H310M M.2                   | Desktop     | [9218549ef6](https://linux-hardware.org/?probe=9218549ef6) | Aug 06, 2021 |
| Gigabyte      | H310M M.2                   | Desktop     | [1f289dd5ed](https://linux-hardware.org/?probe=1f289dd5ed) | Aug 06, 2021 |
| HP            | ENVY TS m7                  | Notebook    | [3edfb9b561](https://linux-hardware.org/?probe=3edfb9b561) | Aug 06, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [8fdb3563d5](https://linux-hardware.org/?probe=8fdb3563d5) | Aug 05, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [1957e721bb](https://linux-hardware.org/?probe=1957e721bb) | Aug 05, 2021 |
| Unknown       | Unknown                     | Notebook    | [608425d791](https://linux-hardware.org/?probe=608425d791) | Aug 05, 2021 |
| MSI           | B85M-E45                    | Desktop     | [85f98480a8](https://linux-hardware.org/?probe=85f98480a8) | Aug 05, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [8fed2c87c2](https://linux-hardware.org/?probe=8fed2c87c2) | Aug 05, 2021 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [aa28a89c93](https://linux-hardware.org/?probe=aa28a89c93) | Aug 05, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [73e2aa30a9](https://linux-hardware.org/?probe=73e2aa30a9) | Aug 04, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [75944f340e](https://linux-hardware.org/?probe=75944f340e) | Aug 04, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [446300d07d](https://linux-hardware.org/?probe=446300d07d) | Aug 04, 2021 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [4c65635b12](https://linux-hardware.org/?probe=4c65635b12) | Aug 04, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [4f09def22f](https://linux-hardware.org/?probe=4f09def22f) | Aug 04, 2021 |
| ASUSTek       | G55VW                       | Notebook    | [9e7dc8e8cf](https://linux-hardware.org/?probe=9e7dc8e8cf) | Aug 03, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [57f0c24236](https://linux-hardware.org/?probe=57f0c24236) | Aug 03, 2021 |
| HP            | ENVY TS m7                  | Notebook    | [8418d1a788](https://linux-hardware.org/?probe=8418d1a788) | Aug 03, 2021 |
| Lenovo        | ThinkPad T460 20FN002VUS    | Notebook    | [7e1580d21a](https://linux-hardware.org/?probe=7e1580d21a) | Aug 03, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [ffa6b89ed0](https://linux-hardware.org/?probe=ffa6b89ed0) | Aug 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0d83a1132d](https://linux-hardware.org/?probe=0d83a1132d) | Aug 02, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [8486506e51](https://linux-hardware.org/?probe=8486506e51) | Aug 01, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [b1d019f3cd](https://linux-hardware.org/?probe=b1d019f3cd) | Aug 01, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [3d97d80723](https://linux-hardware.org/?probe=3d97d80723) | Aug 01, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [35e6393ea4](https://linux-hardware.org/?probe=35e6393ea4) | Aug 01, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [f1cd4939b9](https://linux-hardware.org/?probe=f1cd4939b9) | Aug 01, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [8c45da134f](https://linux-hardware.org/?probe=8c45da134f) | Aug 01, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [69226516bc](https://linux-hardware.org/?probe=69226516bc) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2a9fe5f63c](https://linux-hardware.org/?probe=2a9fe5f63c) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c5dccfd22](https://linux-hardware.org/?probe=1c5dccfd22) | Jul 31, 2021 |
| Lenovo        | ThinkPad W540 20BG001SGE    | Notebook    | [501513f8db](https://linux-hardware.org/?probe=501513f8db) | Jul 31, 2021 |
| Lenovo        | G400s VILG1                 | Notebook    | [48553f1ff1](https://linux-hardware.org/?probe=48553f1ff1) | Jul 30, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [8620581b0d](https://linux-hardware.org/?probe=8620581b0d) | Jul 30, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [7c3d5f062e](https://linux-hardware.org/?probe=7c3d5f062e) | Jul 30, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [30e4889c5a](https://linux-hardware.org/?probe=30e4889c5a) | Jul 30, 2021 |
| Alienware     | 17 R2                       | Notebook    | [897bcbbe33](https://linux-hardware.org/?probe=897bcbbe33) | Jul 30, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [5fc4fcd616](https://linux-hardware.org/?probe=5fc4fcd616) | Jul 30, 2021 |
| HP            | Notebook                    | Notebook    | [79da18091b](https://linux-hardware.org/?probe=79da18091b) | Jul 30, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [7fa1f6acee](https://linux-hardware.org/?probe=7fa1f6acee) | Jul 30, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [f6d0f79499](https://linux-hardware.org/?probe=f6d0f79499) | Jul 29, 2021 |
| Dell          | Latitude E5430 vPro         | Notebook    | [2bd47e953e](https://linux-hardware.org/?probe=2bd47e953e) | Jul 29, 2021 |
| Timi          | A35S                        | Notebook    | [934e38533a](https://linux-hardware.org/?probe=934e38533a) | Jul 28, 2021 |
| MSI           | P67A-G43                    | Desktop     | [c6c1cfc214](https://linux-hardware.org/?probe=c6c1cfc214) | Jul 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c027708276](https://linux-hardware.org/?probe=c027708276) | Jul 28, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [1e96b02bf3](https://linux-hardware.org/?probe=1e96b02bf3) | Jul 28, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [8b5af8c088](https://linux-hardware.org/?probe=8b5af8c088) | Jul 28, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [4b49f7026f](https://linux-hardware.org/?probe=4b49f7026f) | Jul 27, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [2bd8f0dd2e](https://linux-hardware.org/?probe=2bd8f0dd2e) | Jul 27, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [6cd0733dae](https://linux-hardware.org/?probe=6cd0733dae) | Jul 27, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [7c880b70f2](https://linux-hardware.org/?probe=7c880b70f2) | Jul 27, 2021 |
| Samsung       | 350U2A/350U2B/300U1A/351... | Notebook    | [f32f0b6219](https://linux-hardware.org/?probe=f32f0b6219) | Jul 27, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [6df63b2eac](https://linux-hardware.org/?probe=6df63b2eac) | Jul 27, 2021 |
| HP            | Pavilion 15                 | Notebook    | [8958e486f3](https://linux-hardware.org/?probe=8958e486f3) | Jul 27, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0ccf971558](https://linux-hardware.org/?probe=0ccf971558) | Jul 26, 2021 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [5d118fd4cc](https://linux-hardware.org/?probe=5d118fd4cc) | Jul 26, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [ebaa9a7e7a](https://linux-hardware.org/?probe=ebaa9a7e7a) | Jul 26, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [54207766a6](https://linux-hardware.org/?probe=54207766a6) | Jul 26, 2021 |
| MSI           | B85M-E45                    | Desktop     | [d06bc5e141](https://linux-hardware.org/?probe=d06bc5e141) | Jul 26, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [2ce8f90f70](https://linux-hardware.org/?probe=2ce8f90f70) | Jul 26, 2021 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [d07052119d](https://linux-hardware.org/?probe=d07052119d) | Jul 26, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [021f8f6a56](https://linux-hardware.org/?probe=021f8f6a56) | Jul 25, 2021 |
| HP            | Pavilion g6                 | Notebook    | [41b431df89](https://linux-hardware.org/?probe=41b431df89) | Jul 25, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [4ae6eba2f6](https://linux-hardware.org/?probe=4ae6eba2f6) | Jul 25, 2021 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [abb23e508c](https://linux-hardware.org/?probe=abb23e508c) | Jul 25, 2021 |
| Google        | Cyan                        | Notebook    | [46266a438c](https://linux-hardware.org/?probe=46266a438c) | Jul 24, 2021 |
| Fujitsu       | FMVS03004                   | Notebook    | [0182178989](https://linux-hardware.org/?probe=0182178989) | Jul 24, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [77b7f1787c](https://linux-hardware.org/?probe=77b7f1787c) | Jul 23, 2021 |
| Dell          | Precision 7530              | Notebook    | [ae6bf75479](https://linux-hardware.org/?probe=ae6bf75479) | Jul 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6c1a9d102e](https://linux-hardware.org/?probe=6c1a9d102e) | Jul 23, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [c1463a2843](https://linux-hardware.org/?probe=c1463a2843) | Jul 23, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [b40b338aac](https://linux-hardware.org/?probe=b40b338aac) | Jul 23, 2021 |
| Foxconn       | ELA01                       | Desktop     | [13bcd06d5f](https://linux-hardware.org/?probe=13bcd06d5f) | Jul 23, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [e05ed6b947](https://linux-hardware.org/?probe=e05ed6b947) | Jul 23, 2021 |
| Foxconn       | ELA01                       | Desktop     | [a73982649a](https://linux-hardware.org/?probe=a73982649a) | Jul 22, 2021 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [5d8057c74b](https://linux-hardware.org/?probe=5d8057c74b) | Jul 22, 2021 |
| Lenovo        | V130-14IGM 81HM             | Notebook    | [97e870f1da](https://linux-hardware.org/?probe=97e870f1da) | Jul 22, 2021 |
| Shuttle       | FH67                        | Desktop     | [611a7c28dc](https://linux-hardware.org/?probe=611a7c28dc) | Jul 22, 2021 |
| Shuttle       | FH67                        | Desktop     | [3d3fb6c381](https://linux-hardware.org/?probe=3d3fb6c381) | Jul 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [426f611521](https://linux-hardware.org/?probe=426f611521) | Jul 22, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [09f145783b](https://linux-hardware.org/?probe=09f145783b) | Jul 22, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [d3941eaea3](https://linux-hardware.org/?probe=d3941eaea3) | Jul 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [0814f9bb87](https://linux-hardware.org/?probe=0814f9bb87) | Jul 21, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | Notebook    | [704fb2e1d1](https://linux-hardware.org/?probe=704fb2e1d1) | Jul 21, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [3a8e9b23c0](https://linux-hardware.org/?probe=3a8e9b23c0) | Jul 21, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [f2657e5c9a](https://linux-hardware.org/?probe=f2657e5c9a) | Jul 21, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [5e436e1ce2](https://linux-hardware.org/?probe=5e436e1ce2) | Jul 21, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [49660ef55a](https://linux-hardware.org/?probe=49660ef55a) | Jul 21, 2021 |
| Colorful T... | C.H81A-BTC V20              | Desktop     | [1196c4098b](https://linux-hardware.org/?probe=1196c4098b) | Jul 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9d8c462df3](https://linux-hardware.org/?probe=9d8c462df3) | Jul 20, 2021 |
| ASRock        | B550 Extreme4               | Desktop     | [9a73f63205](https://linux-hardware.org/?probe=9a73f63205) | Jul 20, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [1a3712c974](https://linux-hardware.org/?probe=1a3712c974) | Jul 19, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [98bf3c76c1](https://linux-hardware.org/?probe=98bf3c76c1) | Jul 19, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [68d21d8f50](https://linux-hardware.org/?probe=68d21d8f50) | Jul 18, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [696645fa69](https://linux-hardware.org/?probe=696645fa69) | Jul 17, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [40d1ea391b](https://linux-hardware.org/?probe=40d1ea391b) | Jul 17, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [fc0d0dfa77](https://linux-hardware.org/?probe=fc0d0dfa77) | Jul 16, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [cd66889919](https://linux-hardware.org/?probe=cd66889919) | Jul 16, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [f0027b8414](https://linux-hardware.org/?probe=f0027b8414) | Jul 16, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [1c944ecf6b](https://linux-hardware.org/?probe=1c944ecf6b) | Jul 16, 2021 |
| Lenovo        | ThinkPad L390 20NR001EGE    | Notebook    | [b808df1ed1](https://linux-hardware.org/?probe=b808df1ed1) | Jul 16, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [9ca490ae55](https://linux-hardware.org/?probe=9ca490ae55) | Jul 16, 2021 |
| Dell          | G3 3579                     | Notebook    | [04e1e60c32](https://linux-hardware.org/?probe=04e1e60c32) | Jul 16, 2021 |
| MSI           | 970A-G46                    | Desktop     | [21cebf6095](https://linux-hardware.org/?probe=21cebf6095) | Jul 16, 2021 |
| MSI           | 970A-G46                    | Desktop     | [8f1810f8a3](https://linux-hardware.org/?probe=8f1810f8a3) | Jul 16, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a6d2fe96d0](https://linux-hardware.org/?probe=a6d2fe96d0) | Jul 16, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [65f1f58d93](https://linux-hardware.org/?probe=65f1f58d93) | Jul 15, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [900e6f03ed](https://linux-hardware.org/?probe=900e6f03ed) | Jul 14, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [14b9ddda83](https://linux-hardware.org/?probe=14b9ddda83) | Jul 14, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [ac92e036fe](https://linux-hardware.org/?probe=ac92e036fe) | Jul 12, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [380f5c41bf](https://linux-hardware.org/?probe=380f5c41bf) | Jul 12, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [b0ed7c660f](https://linux-hardware.org/?probe=b0ed7c660f) | Jul 12, 2021 |
| Notebook      | P65_P67RGRERA               | Notebook    | [447e30ec88](https://linux-hardware.org/?probe=447e30ec88) | Jul 12, 2021 |
| Dell          | Latitude 3400               | Notebook    | [3591aab2e5](https://linux-hardware.org/?probe=3591aab2e5) | Jul 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [81a878aea5](https://linux-hardware.org/?probe=81a878aea5) | Jul 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [90c5a647cc](https://linux-hardware.org/?probe=90c5a647cc) | Jul 12, 2021 |
| Purism        | Librem 15 v3                | Notebook    | [1f97243626](https://linux-hardware.org/?probe=1f97243626) | Jul 11, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [72f5d673d9](https://linux-hardware.org/?probe=72f5d673d9) | Jul 11, 2021 |
| Dell          | Latitude E6430              | Notebook    | [089735a3b4](https://linux-hardware.org/?probe=089735a3b4) | Jul 11, 2021 |
| ASRock        | 760GM-HDV                   | Desktop     | [f58961af45](https://linux-hardware.org/?probe=f58961af45) | Jul 11, 2021 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [1c4febdfb6](https://linux-hardware.org/?probe=1c4febdfb6) | Jul 11, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [bf0935f2ef](https://linux-hardware.org/?probe=bf0935f2ef) | Jul 11, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [07c39de2b3](https://linux-hardware.org/?probe=07c39de2b3) | Jul 11, 2021 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Notebook    | [6279f113cf](https://linux-hardware.org/?probe=6279f113cf) | Jul 10, 2021 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Notebook    | [577f7a44f7](https://linux-hardware.org/?probe=577f7a44f7) | Jul 10, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [472f5ec6b6](https://linux-hardware.org/?probe=472f5ec6b6) | Jul 09, 2021 |
| Dell          | G3 3579                     | Notebook    | [d5f51334ef](https://linux-hardware.org/?probe=d5f51334ef) | Jul 09, 2021 |
| Dell          | G3 3579                     | Notebook    | [8a7d8d5919](https://linux-hardware.org/?probe=8a7d8d5919) | Jul 09, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [752faee05e](https://linux-hardware.org/?probe=752faee05e) | Jul 09, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [3758d2a6b8](https://linux-hardware.org/?probe=3758d2a6b8) | Jul 09, 2021 |
| MSI           | H81M-P33                    | Desktop     | [48a72375f0](https://linux-hardware.org/?probe=48a72375f0) | Jul 08, 2021 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [a0aa040344](https://linux-hardware.org/?probe=a0aa040344) | Jul 08, 2021 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [f463800460](https://linux-hardware.org/?probe=f463800460) | Jul 08, 2021 |
| MSI           | H61M-P31/W8                 | Desktop     | [34e19b7f44](https://linux-hardware.org/?probe=34e19b7f44) | Jul 07, 2021 |
| ASUSTek       | F1A55-M LX R2.0             | Desktop     | [3db1fed912](https://linux-hardware.org/?probe=3db1fed912) | Jul 07, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [f485424ae4](https://linux-hardware.org/?probe=f485424ae4) | Jul 07, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [7e2f0e6a10](https://linux-hardware.org/?probe=7e2f0e6a10) | Jul 06, 2021 |
| Lenovo        | ThinkPad T410 2537VTZ       | Notebook    | [303bbd18b2](https://linux-hardware.org/?probe=303bbd18b2) | Jul 06, 2021 |
| Entroware     | Apollo                      | Notebook    | [e707e4f502](https://linux-hardware.org/?probe=e707e4f502) | Jul 06, 2021 |
| Dell          | Latitude 5320               | Notebook    | [460e8274ff](https://linux-hardware.org/?probe=460e8274ff) | Jul 05, 2021 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [abf5e04bd3](https://linux-hardware.org/?probe=abf5e04bd3) | Jul 05, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [f4d326f499](https://linux-hardware.org/?probe=f4d326f499) | Jul 05, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [d37ee6f754](https://linux-hardware.org/?probe=d37ee6f754) | Jul 04, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [2d6120fa61](https://linux-hardware.org/?probe=2d6120fa61) | Jul 04, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [4358b4fdea](https://linux-hardware.org/?probe=4358b4fdea) | Jul 04, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [3cf2658ea3](https://linux-hardware.org/?probe=3cf2658ea3) | Jul 04, 2021 |
| PC Special... | N550RN                      | Notebook    | [dc21c20be8](https://linux-hardware.org/?probe=dc21c20be8) | Jul 04, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [1039b9c2f5](https://linux-hardware.org/?probe=1039b9c2f5) | Jul 04, 2021 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [1567387500](https://linux-hardware.org/?probe=1567387500) | Jul 04, 2021 |
| ASUSTek       | N550JK                      | Notebook    | [648f48c253](https://linux-hardware.org/?probe=648f48c253) | Jul 03, 2021 |
| Acer          | Predator G3-571             | Notebook    | [c812432d06](https://linux-hardware.org/?probe=c812432d06) | Jul 02, 2021 |
| ASRock        | B85 Pro4                    | Desktop     | [62a7b004a4](https://linux-hardware.org/?probe=62a7b004a4) | Jul 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [5f8aa07d0a](https://linux-hardware.org/?probe=5f8aa07d0a) | Jul 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [730eb45ad2](https://linux-hardware.org/?probe=730eb45ad2) | Jul 02, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [c198cbd693](https://linux-hardware.org/?probe=c198cbd693) | Jul 02, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [d1fef5f2de](https://linux-hardware.org/?probe=d1fef5f2de) | Jul 02, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f23be94d69](https://linux-hardware.org/?probe=f23be94d69) | Jul 02, 2021 |
| HP            | Pavilion dv6                | Notebook    | [d4fedbdd8f](https://linux-hardware.org/?probe=d4fedbdd8f) | Jul 02, 2021 |
| HP            | Pavilion dv6                | Notebook    | [6fd95d88a4](https://linux-hardware.org/?probe=6fd95d88a4) | Jul 02, 2021 |
| Gigabyte      | X58-USB3                    | Desktop     | [ec21765442](https://linux-hardware.org/?probe=ec21765442) | Jul 02, 2021 |
| Acer          | Aspire E5-771G              | Notebook    | [75dbf43fd0](https://linux-hardware.org/?probe=75dbf43fd0) | Jul 02, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [94c42f1e1d](https://linux-hardware.org/?probe=94c42f1e1d) | Jul 02, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [ab9083ed9e](https://linux-hardware.org/?probe=ab9083ed9e) | Jul 02, 2021 |
| Gigabyte      | P67A-UD7-B3                 | Desktop     | [addc902804](https://linux-hardware.org/?probe=addc902804) | Jul 02, 2021 |
| Gigabyte      | P67A-UD7-B3                 | Desktop     | [324f73d0c1](https://linux-hardware.org/?probe=324f73d0c1) | Jul 02, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [318497ce75](https://linux-hardware.org/?probe=318497ce75) | Jul 02, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [fb97d82a6b](https://linux-hardware.org/?probe=fb97d82a6b) | Jul 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002VUS    | Notebook    | [13ca6385ce](https://linux-hardware.org/?probe=13ca6385ce) | Jul 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002VUS    | Notebook    | [fbb0cc180c](https://linux-hardware.org/?probe=fbb0cc180c) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e42003e8ce](https://linux-hardware.org/?probe=e42003e8ce) | Jul 01, 2021 |
| HP            | 17E2                        | Mini pc     | [e53c1d5e09](https://linux-hardware.org/?probe=e53c1d5e09) | Jul 01, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [d95ce95021](https://linux-hardware.org/?probe=d95ce95021) | Jul 01, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1b0f28087e](https://linux-hardware.org/?probe=1b0f28087e) | Jul 01, 2021 |
| HP            | Pavilion 15                 | Notebook    | [1164b570da](https://linux-hardware.org/?probe=1164b570da) | Jul 01, 2021 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [e214ce4b74](https://linux-hardware.org/?probe=e214ce4b74) | Jun 30, 2021 |
| Biostar       | TA790GXB A2+                | Desktop     | [9fb8b9219e](https://linux-hardware.org/?probe=9fb8b9219e) | Jun 30, 2021 |
| System76      | Oryx Pro                    | Notebook    | [fd3cc0ad52](https://linux-hardware.org/?probe=fd3cc0ad52) | Jun 30, 2021 |
| Lenovo        | ThinkPad T470p 20J60042M... | Notebook    | [6ce76d671e](https://linux-hardware.org/?probe=6ce76d671e) | Jun 29, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [ee3e0d4c67](https://linux-hardware.org/?probe=ee3e0d4c67) | Jun 29, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [a861d1164e](https://linux-hardware.org/?probe=a861d1164e) | Jun 29, 2021 |
| Dell          | G3 3590                     | Notebook    | [9a7cfa92a8](https://linux-hardware.org/?probe=9a7cfa92a8) | Jun 28, 2021 |
| ASRock        | B85 Pro4                    | Desktop     | [90aab519a6](https://linux-hardware.org/?probe=90aab519a6) | Jun 27, 2021 |
| ASRock        | N68-S3 UCC                  | Desktop     | [da689c7012](https://linux-hardware.org/?probe=da689c7012) | Jun 26, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [dfa95a4efd](https://linux-hardware.org/?probe=dfa95a4efd) | Jun 26, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a26c01da62](https://linux-hardware.org/?probe=a26c01da62) | Jun 26, 2021 |
| Acer          | Extensa 2540                | Notebook    | [25d9dc3339](https://linux-hardware.org/?probe=25d9dc3339) | Jun 26, 2021 |
| Lenovo        | Yoga 14sACH 2021 82MS       | Notebook    | [0278ab88e1](https://linux-hardware.org/?probe=0278ab88e1) | Jun 26, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [69b129d658](https://linux-hardware.org/?probe=69b129d658) | Jun 26, 2021 |
| Dell          | Latitude 5580               | Notebook    | [da9c2daba5](https://linux-hardware.org/?probe=da9c2daba5) | Jun 26, 2021 |
| Dell          | Latitude 5580               | Notebook    | [0464095111](https://linux-hardware.org/?probe=0464095111) | Jun 25, 2021 |
| SUPoX COMP... | B250A-BTC PRO               | Desktop     | [faf606a1e6](https://linux-hardware.org/?probe=faf606a1e6) | Jun 25, 2021 |
| SUPoX COMP... | B250A-BTC PRO               | Desktop     | [c33f19e525](https://linux-hardware.org/?probe=c33f19e525) | Jun 25, 2021 |
| MSI           | H61M-P31/W8                 | Desktop     | [a8479de901](https://linux-hardware.org/?probe=a8479de901) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7b98c8285d](https://linux-hardware.org/?probe=7b98c8285d) | Jun 24, 2021 |
| Gigabyte      | P67A-UD4                    | Desktop     | [11cdfd6b79](https://linux-hardware.org/?probe=11cdfd6b79) | Jun 24, 2021 |
| Fujitsu       | LIFEBOOK T901               | Notebook    | [fac68d6d96](https://linux-hardware.org/?probe=fac68d6d96) | Jun 23, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [da4c434f55](https://linux-hardware.org/?probe=da4c434f55) | Jun 23, 2021 |
| MSI           | H61M-P31/W8                 | Desktop     | [2f94e6e262](https://linux-hardware.org/?probe=2f94e6e262) | Jun 22, 2021 |
| HP            | 82FE 11                     | Desktop     | [acabfe917b](https://linux-hardware.org/?probe=acabfe917b) | Jun 22, 2021 |
| Dell          | Latitude 5501               | Notebook    | [93207f51d2](https://linux-hardware.org/?probe=93207f51d2) | Jun 22, 2021 |
| Dell          | Latitude 5501               | Notebook    | [40a42a978d](https://linux-hardware.org/?probe=40a42a978d) | Jun 22, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [fca4787959](https://linux-hardware.org/?probe=fca4787959) | Jun 22, 2021 |
| Intel         | X99                         | Desktop     | [436dda258b](https://linux-hardware.org/?probe=436dda258b) | Jun 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [02161cf811](https://linux-hardware.org/?probe=02161cf811) | Jun 21, 2021 |
| ASRock        | B360M IB-R1                 | Desktop     | [3c4ee680cf](https://linux-hardware.org/?probe=3c4ee680cf) | Jun 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [98be9faa06](https://linux-hardware.org/?probe=98be9faa06) | Jun 21, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [ffd6111ce0](https://linux-hardware.org/?probe=ffd6111ce0) | Jun 21, 2021 |
| Dell          | 0XCR8D A03                  | Desktop     | [7a94c5e5b2](https://linux-hardware.org/?probe=7a94c5e5b2) | Jun 21, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [5cdcacb2f2](https://linux-hardware.org/?probe=5cdcacb2f2) | Jun 20, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [6c9f9a3c6f](https://linux-hardware.org/?probe=6c9f9a3c6f) | Jun 20, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [270961254a](https://linux-hardware.org/?probe=270961254a) | Jun 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [b845fbd6b0](https://linux-hardware.org/?probe=b845fbd6b0) | Jun 20, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [64c8a86c5b](https://linux-hardware.org/?probe=64c8a86c5b) | Jun 19, 2021 |
| Acer          | Aspire E5-771G              | Notebook    | [6514c21190](https://linux-hardware.org/?probe=6514c21190) | Jun 19, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [441c0bb81f](https://linux-hardware.org/?probe=441c0bb81f) | Jun 19, 2021 |
| Dell          | 0X2MKR A00                  | All in one  | [41fa85048c](https://linux-hardware.org/?probe=41fa85048c) | Jun 19, 2021 |
| Dell          | 0X2MKR A00                  | All in one  | [0050574359](https://linux-hardware.org/?probe=0050574359) | Jun 18, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [a69ed7dfd9](https://linux-hardware.org/?probe=a69ed7dfd9) | Jun 18, 2021 |
| System76      | Kudu Professional           | Notebook    | [3efac330f0](https://linux-hardware.org/?probe=3efac330f0) | Jun 18, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [cb1c07fa68](https://linux-hardware.org/?probe=cb1c07fa68) | Jun 17, 2021 |
| Dell          | Latitude E6520              | Notebook    | [718e90b724](https://linux-hardware.org/?probe=718e90b724) | Jun 17, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [acd35c74b5](https://linux-hardware.org/?probe=acd35c74b5) | Jun 17, 2021 |
| HP            | 1495                        | Desktop     | [56251d62e1](https://linux-hardware.org/?probe=56251d62e1) | Jun 17, 2021 |
| Dell          | Latitude E5570              | Notebook    | [6134f58e73](https://linux-hardware.org/?probe=6134f58e73) | Jun 17, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [dac3d6b5f5](https://linux-hardware.org/?probe=dac3d6b5f5) | Jun 17, 2021 |
| Dell          | Latitude 3400               | Notebook    | [32064bd8b8](https://linux-hardware.org/?probe=32064bd8b8) | Jun 17, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [073ee459eb](https://linux-hardware.org/?probe=073ee459eb) | Jun 16, 2021 |
| Intel         | H55                         | Desktop     | [c6c7036ebd](https://linux-hardware.org/?probe=c6c7036ebd) | Jun 16, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [f6b05efbb8](https://linux-hardware.org/?probe=f6b05efbb8) | Jun 16, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [3eb01e93e5](https://linux-hardware.org/?probe=3eb01e93e5) | Jun 16, 2021 |
| Intel         | ChiefRiver                  | Notebook    | [72aa2e75fc](https://linux-hardware.org/?probe=72aa2e75fc) | Jun 15, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [85c3988842](https://linux-hardware.org/?probe=85c3988842) | Jun 15, 2021 |
| HP            | EliteBook 850 G1            | Notebook    | [75e4118519](https://linux-hardware.org/?probe=75e4118519) | Jun 15, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [89fd130ff2](https://linux-hardware.org/?probe=89fd130ff2) | Jun 15, 2021 |
| Dell          | Latitude 5590               | Notebook    | [ddf8c05b96](https://linux-hardware.org/?probe=ddf8c05b96) | Jun 15, 2021 |
| Acer          | Extensa 2540                | Notebook    | [505cc98c20](https://linux-hardware.org/?probe=505cc98c20) | Jun 14, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [b90af008d3](https://linux-hardware.org/?probe=b90af008d3) | Jun 14, 2021 |
| Gigabyte      | B360M HD3                   | Desktop     | [bed714271e](https://linux-hardware.org/?probe=bed714271e) | Jun 14, 2021 |
| HP            | 198E                        | Desktop     | [4d38d777c3](https://linux-hardware.org/?probe=4d38d777c3) | Jun 13, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ba473cd8fd](https://linux-hardware.org/?probe=ba473cd8fd) | Jun 13, 2021 |
| HP            | 198E                        | Desktop     | [056f258949](https://linux-hardware.org/?probe=056f258949) | Jun 13, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [d37cfc0abc](https://linux-hardware.org/?probe=d37cfc0abc) | Jun 13, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [f0a5e0cbb6](https://linux-hardware.org/?probe=f0a5e0cbb6) | Jun 13, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [9a18a08c1f](https://linux-hardware.org/?probe=9a18a08c1f) | Jun 13, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [ead58254b2](https://linux-hardware.org/?probe=ead58254b2) | Jun 12, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [885df6a45b](https://linux-hardware.org/?probe=885df6a45b) | Jun 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f70719c970](https://linux-hardware.org/?probe=f70719c970) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [676f8cfa11](https://linux-hardware.org/?probe=676f8cfa11) | Jun 12, 2021 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [d99f5ee668](https://linux-hardware.org/?probe=d99f5ee668) | Jun 12, 2021 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [cfa0cf242c](https://linux-hardware.org/?probe=cfa0cf242c) | Jun 11, 2021 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [32e7e7d668](https://linux-hardware.org/?probe=32e7e7d668) | Jun 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [16d75c0003](https://linux-hardware.org/?probe=16d75c0003) | Jun 11, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [073273f6a4](https://linux-hardware.org/?probe=073273f6a4) | Jun 11, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [174ef2fee6](https://linux-hardware.org/?probe=174ef2fee6) | Jun 11, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [955f2768da](https://linux-hardware.org/?probe=955f2768da) | Jun 11, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [c9549be0ad](https://linux-hardware.org/?probe=c9549be0ad) | Jun 11, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [4342f2eefd](https://linux-hardware.org/?probe=4342f2eefd) | Jun 11, 2021 |
| Gigabyte      | H61MS                       | Desktop     | [c74e490e4d](https://linux-hardware.org/?probe=c74e490e4d) | Jun 11, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bd7d3a3b09](https://linux-hardware.org/?probe=bd7d3a3b09) | Jun 11, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3515fe7908](https://linux-hardware.org/?probe=3515fe7908) | Jun 10, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [442ebaf444](https://linux-hardware.org/?probe=442ebaf444) | Jun 10, 2021 |
| HP            | 198E                        | Desktop     | [683e970f55](https://linux-hardware.org/?probe=683e970f55) | Jun 10, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [1fb08e646c](https://linux-hardware.org/?probe=1fb08e646c) | Jun 10, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [ce2eb9d95f](https://linux-hardware.org/?probe=ce2eb9d95f) | Jun 09, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [851f20cb74](https://linux-hardware.org/?probe=851f20cb74) | Jun 09, 2021 |
| Acer          | Aspire V5-572G              | Notebook    | [d1a38eaf28](https://linux-hardware.org/?probe=d1a38eaf28) | Jun 09, 2021 |
| Acer          | Aspire E5-771G              | Notebook    | [292f75ec92](https://linux-hardware.org/?probe=292f75ec92) | Jun 08, 2021 |
| HP            | EliteBook 850 G1            | Notebook    | [4c0ae26777](https://linux-hardware.org/?probe=4c0ae26777) | Jun 08, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [11016c6ad2](https://linux-hardware.org/?probe=11016c6ad2) | Jun 08, 2021 |
| Lenovo        | Tilapia CRB                 | Desktop     | [1b9acc3bdf](https://linux-hardware.org/?probe=1b9acc3bdf) | Jun 08, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [cfc0aceaf9](https://linux-hardware.org/?probe=cfc0aceaf9) | Jun 08, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [60b4c707ad](https://linux-hardware.org/?probe=60b4c707ad) | Jun 07, 2021 |
| SUPoX COMP... | B250A-BTC PRO               | Desktop     | [52abd4b7d3](https://linux-hardware.org/?probe=52abd4b7d3) | Jun 07, 2021 |
| SUPoX COMP... | B250A-BTC PRO               | Desktop     | [660295a933](https://linux-hardware.org/?probe=660295a933) | Jun 07, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [485a6fe2dd](https://linux-hardware.org/?probe=485a6fe2dd) | Jun 06, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5e73374bbc](https://linux-hardware.org/?probe=5e73374bbc) | Jun 06, 2021 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [fa126d0d5f](https://linux-hardware.org/?probe=fa126d0d5f) | Jun 05, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [64ed40d969](https://linux-hardware.org/?probe=64ed40d969) | Jun 05, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [dcae361982](https://linux-hardware.org/?probe=dcae361982) | Jun 05, 2021 |
| AMD           | AOPW-PLUS                   | Server      | [8bf97b9982](https://linux-hardware.org/?probe=8bf97b9982) | Jun 05, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [62612abd09](https://linux-hardware.org/?probe=62612abd09) | Jun 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [8cbe8c75f8](https://linux-hardware.org/?probe=8cbe8c75f8) | Jun 04, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a580ef9f5c](https://linux-hardware.org/?probe=a580ef9f5c) | Jun 04, 2021 |
| HP            | 304Bh                       | Desktop     | [4f331fec6f](https://linux-hardware.org/?probe=4f331fec6f) | Jun 04, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [fe8cc5a05e](https://linux-hardware.org/?probe=fe8cc5a05e) | Jun 04, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [08473a1b95](https://linux-hardware.org/?probe=08473a1b95) | Jun 04, 2021 |
| Dell          | Latitude E6330              | Notebook    | [eaef8796a5](https://linux-hardware.org/?probe=eaef8796a5) | Jun 04, 2021 |
| HP            | 304Bh                       | Desktop     | [a41a097984](https://linux-hardware.org/?probe=a41a097984) | Jun 04, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [0d2cfdc2d8](https://linux-hardware.org/?probe=0d2cfdc2d8) | Jun 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [59e0d6d4ab](https://linux-hardware.org/?probe=59e0d6d4ab) | Jun 03, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c540bad35d](https://linux-hardware.org/?probe=c540bad35d) | Jun 03, 2021 |
| Dell          | Latitude E6330              | Notebook    | [4a51b670ac](https://linux-hardware.org/?probe=4a51b670ac) | Jun 03, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d2185ebe9f](https://linux-hardware.org/?probe=d2185ebe9f) | Jun 03, 2021 |
| Dell          | Latitude E6410              | Notebook    | [dd2824f257](https://linux-hardware.org/?probe=dd2824f257) | Jun 03, 2021 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [eb72e1d1c7](https://linux-hardware.org/?probe=eb72e1d1c7) | Jun 01, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [db42b43d7e](https://linux-hardware.org/?probe=db42b43d7e) | Jun 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d3a001e377](https://linux-hardware.org/?probe=d3a001e377) | Jun 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a4d00095a1](https://linux-hardware.org/?probe=a4d00095a1) | Jun 01, 2021 |
| Purism        | Librem 15 v3                | Notebook    | [1ab69568a5](https://linux-hardware.org/?probe=1ab69568a5) | Jun 01, 2021 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [8961ca91b3](https://linux-hardware.org/?probe=8961ca91b3) | May 31, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [bfa6d609ba](https://linux-hardware.org/?probe=bfa6d609ba) | May 31, 2021 |
| Huanan        | X99-TF                      | Desktop     | [b92f4485e6](https://linux-hardware.org/?probe=b92f4485e6) | May 31, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [0fc3abdb1c](https://linux-hardware.org/?probe=0fc3abdb1c) | May 31, 2021 |
| HP            | ENVY TS 14 Sleekbook        | Notebook    | [f52091e51e](https://linux-hardware.org/?probe=f52091e51e) | May 31, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [c1bf9c169d](https://linux-hardware.org/?probe=c1bf9c169d) | May 31, 2021 |
| Lenovo        | Z40-70 20366                | Notebook    | [b1b8196f26](https://linux-hardware.org/?probe=b1b8196f26) | May 31, 2021 |
| HP            | ENVY TS 15                  | Notebook    | [8369c42ce2](https://linux-hardware.org/?probe=8369c42ce2) | May 31, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d71af3d423](https://linux-hardware.org/?probe=d71af3d423) | May 31, 2021 |
| Cube          | SurfTab twin 11.6           | Convertible | [1866d29174](https://linux-hardware.org/?probe=1866d29174) | May 30, 2021 |
| Acer          | AO722                       | Notebook    | [8a6d18ebad](https://linux-hardware.org/?probe=8a6d18ebad) | May 30, 2021 |
| Acer          | AO722                       | Notebook    | [bc3de3323b](https://linux-hardware.org/?probe=bc3de3323b) | May 30, 2021 |
| Gigabyte      | Z270X-UD3-CF                | Desktop     | [834a7ae73b](https://linux-hardware.org/?probe=834a7ae73b) | May 30, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [61b0c0fce0](https://linux-hardware.org/?probe=61b0c0fce0) | May 29, 2021 |
| Purism        | Librem 15 v3                | Notebook    | [c867c6dd96](https://linux-hardware.org/?probe=c867c6dd96) | May 29, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [f39108e22f](https://linux-hardware.org/?probe=f39108e22f) | May 29, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [9673f97e2a](https://linux-hardware.org/?probe=9673f97e2a) | May 28, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [243cdc0172](https://linux-hardware.org/?probe=243cdc0172) | May 28, 2021 |
| Positivo      | Serie AT300                 | Notebook    | [38a0173a4a](https://linux-hardware.org/?probe=38a0173a4a) | May 28, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [d0fd1ce0e8](https://linux-hardware.org/?probe=d0fd1ce0e8) | May 28, 2021 |
| Unknown       | Unknown                     | Notebook    | [f36322ada4](https://linux-hardware.org/?probe=f36322ada4) | May 27, 2021 |
| Lenovo        | IdeaPad Z400 VIWZ1          | Notebook    | [635eb2015b](https://linux-hardware.org/?probe=635eb2015b) | May 27, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [56b16c9c71](https://linux-hardware.org/?probe=56b16c9c71) | May 26, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [849be7da3e](https://linux-hardware.org/?probe=849be7da3e) | May 26, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [3ff174d668](https://linux-hardware.org/?probe=3ff174d668) | May 26, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [57ffe115ac](https://linux-hardware.org/?probe=57ffe115ac) | May 26, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [3de199f8f3](https://linux-hardware.org/?probe=3de199f8f3) | May 26, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [98f9559b42](https://linux-hardware.org/?probe=98f9559b42) | May 25, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [8b41a0da23](https://linux-hardware.org/?probe=8b41a0da23) | May 25, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [5822d31941](https://linux-hardware.org/?probe=5822d31941) | May 25, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [1bbdf4baa5](https://linux-hardware.org/?probe=1bbdf4baa5) | May 25, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [4bd51e385d](https://linux-hardware.org/?probe=4bd51e385d) | May 25, 2021 |
| HP            | 1998                        | Desktop     | [639725c8af](https://linux-hardware.org/?probe=639725c8af) | May 24, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [da566f34dd](https://linux-hardware.org/?probe=da566f34dd) | May 24, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [2951d8e0c3](https://linux-hardware.org/?probe=2951d8e0c3) | May 24, 2021 |
| Positivo      | Serie AT300                 | Notebook    | [a021ecf0dd](https://linux-hardware.org/?probe=a021ecf0dd) | May 24, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [21c989b928](https://linux-hardware.org/?probe=21c989b928) | May 24, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [77d9207a29](https://linux-hardware.org/?probe=77d9207a29) | May 24, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [3ae2f83c9f](https://linux-hardware.org/?probe=3ae2f83c9f) | May 23, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [e034d1b339](https://linux-hardware.org/?probe=e034d1b339) | May 23, 2021 |
| Intel         | NUC7i7BNB J31145-309        | Mini pc     | [1bc6e7aca3](https://linux-hardware.org/?probe=1bc6e7aca3) | May 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [de75ca92a2](https://linux-hardware.org/?probe=de75ca92a2) | May 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [292fe218cd](https://linux-hardware.org/?probe=292fe218cd) | May 23, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [0b7b90bb5d](https://linux-hardware.org/?probe=0b7b90bb5d) | May 22, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [e5974ee826](https://linux-hardware.org/?probe=e5974ee826) | May 22, 2021 |
| Dell          | 0XHYJF A01                  | All in one  | [f61158882e](https://linux-hardware.org/?probe=f61158882e) | May 21, 2021 |
| Dell          | Vostro 14-3468              | Notebook    | [1742ee5823](https://linux-hardware.org/?probe=1742ee5823) | May 21, 2021 |
| GPU Compan... | GWTC116-2                   | Notebook    | [bb53a458d4](https://linux-hardware.org/?probe=bb53a458d4) | May 21, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [fdff074ae2](https://linux-hardware.org/?probe=fdff074ae2) | May 21, 2021 |
| HP            | 158B                        | Desktop     | [e7d78d4e6c](https://linux-hardware.org/?probe=e7d78d4e6c) | May 21, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [fc4a208720](https://linux-hardware.org/?probe=fc4a208720) | May 20, 2021 |
| Samsung       | 530U3C/530U4C               | Notebook    | [a7aa09da10](https://linux-hardware.org/?probe=a7aa09da10) | May 20, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [bc4cdd85ce](https://linux-hardware.org/?probe=bc4cdd85ce) | May 20, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [1a9761824e](https://linux-hardware.org/?probe=1a9761824e) | May 20, 2021 |
| Dell          | 0XHYJF A01                  | All in one  | [0d1f1e6906](https://linux-hardware.org/?probe=0d1f1e6906) | May 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [290d3af922](https://linux-hardware.org/?probe=290d3af922) | May 19, 2021 |
| MSI           | H81M-E34                    | Desktop     | [ea9b132e77](https://linux-hardware.org/?probe=ea9b132e77) | May 19, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [7806332395](https://linux-hardware.org/?probe=7806332395) | May 19, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [d4b2f66b68](https://linux-hardware.org/?probe=d4b2f66b68) | May 19, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [6bfdd9fda4](https://linux-hardware.org/?probe=6bfdd9fda4) | May 19, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [54a21bec35](https://linux-hardware.org/?probe=54a21bec35) | May 19, 2021 |
| MSI           | 2AE0                        | Desktop     | [cdddabf42c](https://linux-hardware.org/?probe=cdddabf42c) | May 19, 2021 |
| MSI           | Z170A GAMING M5             | Desktop     | [7493d31acb](https://linux-hardware.org/?probe=7493d31acb) | May 18, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [f12c26f48d](https://linux-hardware.org/?probe=f12c26f48d) | May 18, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [b4a3ede65b](https://linux-hardware.org/?probe=b4a3ede65b) | May 18, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [015bfe4f6d](https://linux-hardware.org/?probe=015bfe4f6d) | May 18, 2021 |
| ASRock        | B550 Extreme4               | Desktop     | [6c7317e728](https://linux-hardware.org/?probe=6c7317e728) | May 18, 2021 |
| HP            | 21B4 A01                    | Desktop     | [45752d3232](https://linux-hardware.org/?probe=45752d3232) | May 18, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [9ccc881af0](https://linux-hardware.org/?probe=9ccc881af0) | May 18, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [b8de97b4c0](https://linux-hardware.org/?probe=b8de97b4c0) | May 17, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [426ecdf62e](https://linux-hardware.org/?probe=426ecdf62e) | May 17, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [d01af38384](https://linux-hardware.org/?probe=d01af38384) | May 17, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [72441939be](https://linux-hardware.org/?probe=72441939be) | May 17, 2021 |
| Supermicro    | H8QG6                       | Server      | [d5563e325c](https://linux-hardware.org/?probe=d5563e325c) | May 17, 2021 |
| Dell          | Latitude 5480               | Notebook    | [1c717313bc](https://linux-hardware.org/?probe=1c717313bc) | May 17, 2021 |
| Intel         | DX79SI AAG28808-600         | Desktop     | [4d5e452411](https://linux-hardware.org/?probe=4d5e452411) | May 16, 2021 |
| Toshiba       | Satellite L850-1C9          | Notebook    | [1c040e75dd](https://linux-hardware.org/?probe=1c040e75dd) | May 16, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [e5a3726b96](https://linux-hardware.org/?probe=e5a3726b96) | May 16, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [80ca4b15a5](https://linux-hardware.org/?probe=80ca4b15a5) | May 16, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [6e96a8df5f](https://linux-hardware.org/?probe=6e96a8df5f) | May 16, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [57b918a36e](https://linux-hardware.org/?probe=57b918a36e) | May 15, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [636edc34ba](https://linux-hardware.org/?probe=636edc34ba) | May 15, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [22b412f033](https://linux-hardware.org/?probe=22b412f033) | May 15, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2c5c989a79](https://linux-hardware.org/?probe=2c5c989a79) | May 14, 2021 |
| Lenovo        | ThinkPad E550 20DF00CPFR    | Notebook    | [0afb5fd49d](https://linux-hardware.org/?probe=0afb5fd49d) | May 14, 2021 |
| Lenovo        | ThinkPad E550 20DF00CPFR    | Notebook    | [af28d9b401](https://linux-hardware.org/?probe=af28d9b401) | May 14, 2021 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [acdc104331](https://linux-hardware.org/?probe=acdc104331) | May 14, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [609b25a62b](https://linux-hardware.org/?probe=609b25a62b) | May 13, 2021 |
| Dell          | Latitude 5590               | Notebook    | [9b726ce28d](https://linux-hardware.org/?probe=9b726ce28d) | May 13, 2021 |
| Dell          | Latitude 5590               | Notebook    | [8ee7e45cd4](https://linux-hardware.org/?probe=8ee7e45cd4) | May 13, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [8fcf99f057](https://linux-hardware.org/?probe=8fcf99f057) | May 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [0f0153e2db](https://linux-hardware.org/?probe=0f0153e2db) | May 12, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [29ad7fb8e1](https://linux-hardware.org/?probe=29ad7fb8e1) | May 12, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [3fd70c5b87](https://linux-hardware.org/?probe=3fd70c5b87) | May 12, 2021 |
| HP            | Pavilion dm4                | Notebook    | [12873cce8e](https://linux-hardware.org/?probe=12873cce8e) | May 12, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [057df01811](https://linux-hardware.org/?probe=057df01811) | May 11, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [3a544adcc9](https://linux-hardware.org/?probe=3a544adcc9) | May 11, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [501fef8ecf](https://linux-hardware.org/?probe=501fef8ecf) | May 10, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [740af6c089](https://linux-hardware.org/?probe=740af6c089) | May 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [3e034cbfe1](https://linux-hardware.org/?probe=3e034cbfe1) | May 10, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [fa9f8b7f7e](https://linux-hardware.org/?probe=fa9f8b7f7e) | May 10, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [db1a234412](https://linux-hardware.org/?probe=db1a234412) | May 10, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [9e701873b1](https://linux-hardware.org/?probe=9e701873b1) | May 09, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [59a6774cd5](https://linux-hardware.org/?probe=59a6774cd5) | May 09, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [987181b525](https://linux-hardware.org/?probe=987181b525) | May 09, 2021 |
| ASUSTek       | GL752VW                     | Notebook    | [6ca916356b](https://linux-hardware.org/?probe=6ca916356b) | May 09, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | Desktop     | [9ad8acccaa](https://linux-hardware.org/?probe=9ad8acccaa) | May 08, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [3672ef87de](https://linux-hardware.org/?probe=3672ef87de) | May 08, 2021 |
| Lenovo        | XiaoXin Air 12 80UN         | Notebook    | [210f81171b](https://linux-hardware.org/?probe=210f81171b) | May 08, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [6300246c13](https://linux-hardware.org/?probe=6300246c13) | May 07, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [31732d19ac](https://linux-hardware.org/?probe=31732d19ac) | May 07, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d4cf6a320b](https://linux-hardware.org/?probe=d4cf6a320b) | May 07, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [640f11cd69](https://linux-hardware.org/?probe=640f11cd69) | May 07, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [36a21dabee](https://linux-hardware.org/?probe=36a21dabee) | May 06, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [86167086f7](https://linux-hardware.org/?probe=86167086f7) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [4a03c325a9](https://linux-hardware.org/?probe=4a03c325a9) | May 06, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [6367a7db0a](https://linux-hardware.org/?probe=6367a7db0a) | May 06, 2021 |
| Dell          | XPS 15 9550                 | Notebook    | [5f5bb678ea](https://linux-hardware.org/?probe=5f5bb678ea) | May 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6654328a0f](https://linux-hardware.org/?probe=6654328a0f) | May 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [c686837768](https://linux-hardware.org/?probe=c686837768) | May 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8721931b25](https://linux-hardware.org/?probe=8721931b25) | May 05, 2021 |
| Dell          | Latitude E6410              | Notebook    | [5c29371d72](https://linux-hardware.org/?probe=5c29371d72) | May 05, 2021 |
| Standard      | Unknown                     | Notebook    | [713ab93267](https://linux-hardware.org/?probe=713ab93267) | May 04, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [818bb34eae](https://linux-hardware.org/?probe=818bb34eae) | May 04, 2021 |
| ASRock        | B450M Gaming                | Desktop     | [2126036020](https://linux-hardware.org/?probe=2126036020) | May 04, 2021 |
| Lenovo        | Yoga 510-15IKB 80VC         | Convertible | [a4d6f3cce4](https://linux-hardware.org/?probe=a4d6f3cce4) | May 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [0a82b79706](https://linux-hardware.org/?probe=0a82b79706) | May 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [4c91d3d2b0](https://linux-hardware.org/?probe=4c91d3d2b0) | May 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [735f58d176](https://linux-hardware.org/?probe=735f58d176) | May 04, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [d0f897fbd4](https://linux-hardware.org/?probe=d0f897fbd4) | May 04, 2021 |
| Fujitsu       | LIFEBOOK UH572              | Notebook    | [47eae809a0](https://linux-hardware.org/?probe=47eae809a0) | May 03, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6c6c5bf2ea](https://linux-hardware.org/?probe=6c6c5bf2ea) | May 03, 2021 |
| Dell          | G7 7700                     | Notebook    | [b9bdfabacd](https://linux-hardware.org/?probe=b9bdfabacd) | May 02, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [1e8acae283](https://linux-hardware.org/?probe=1e8acae283) | May 01, 2021 |
| HP            | Pavilion 15                 | Notebook    | [882223f1be](https://linux-hardware.org/?probe=882223f1be) | May 01, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [7de0627698](https://linux-hardware.org/?probe=7de0627698) | May 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d1ea8cdcf](https://linux-hardware.org/?probe=3d1ea8cdcf) | May 01, 2021 |
| Dell          | Precision M4700             | Notebook    | [908638c5f1](https://linux-hardware.org/?probe=908638c5f1) | May 01, 2021 |
| Dell          | Precision M4700             | Notebook    | [ab9d973854](https://linux-hardware.org/?probe=ab9d973854) | May 01, 2021 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [18aac22ace](https://linux-hardware.org/?probe=18aac22ace) | May 01, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [c35116c9fa](https://linux-hardware.org/?probe=c35116c9fa) | Apr 30, 2021 |
| Gigabyte      | AORUS 5 SB                  | Notebook    | [ace32de58d](https://linux-hardware.org/?probe=ace32de58d) | Apr 29, 2021 |
| Dell          | 0M858N A01                  | Desktop     | [5cf29d108d](https://linux-hardware.org/?probe=5cf29d108d) | Apr 29, 2021 |
| Dell          | 0M858N A01                  | Desktop     | [6db1d18e09](https://linux-hardware.org/?probe=6db1d18e09) | Apr 29, 2021 |
| Dell          | 0N13T1 A01                  | Desktop     | [7c02e11615](https://linux-hardware.org/?probe=7c02e11615) | Apr 28, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [f8b00a2f85](https://linux-hardware.org/?probe=f8b00a2f85) | Apr 27, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [731d132b14](https://linux-hardware.org/?probe=731d132b14) | Apr 26, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [0113cc8ad1](https://linux-hardware.org/?probe=0113cc8ad1) | Apr 26, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [59c2086399](https://linux-hardware.org/?probe=59c2086399) | Apr 26, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [48953fbb84](https://linux-hardware.org/?probe=48953fbb84) | Apr 26, 2021 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [303f687cb8](https://linux-hardware.org/?probe=303f687cb8) | Apr 26, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [747f7a1fc0](https://linux-hardware.org/?probe=747f7a1fc0) | Apr 26, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [be76a90df9](https://linux-hardware.org/?probe=be76a90df9) | Apr 26, 2021 |
| Gigabyte      | AORUS 5 SB                  | Notebook    | [186fd87862](https://linux-hardware.org/?probe=186fd87862) | Apr 26, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [e909bbda9e](https://linux-hardware.org/?probe=e909bbda9e) | Apr 26, 2021 |
| ASUSTek       | X555YI                      | Notebook    | [66780ed1f3](https://linux-hardware.org/?probe=66780ed1f3) | Apr 25, 2021 |
| HP            | ENVY 17                     | Notebook    | [d1edd93e74](https://linux-hardware.org/?probe=d1edd93e74) | Apr 25, 2021 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [00e650f868](https://linux-hardware.org/?probe=00e650f868) | Apr 25, 2021 |
| ASUSTek       | X510UAR                     | Notebook    | [706b7d707b](https://linux-hardware.org/?probe=706b7d707b) | Apr 24, 2021 |
| Gigabyte      | Z170X-Gaming 5              | Desktop     | [54a619054a](https://linux-hardware.org/?probe=54a619054a) | Apr 24, 2021 |
| Lenovo        | ThinkPad T440s 20ARS45U0... | Notebook    | [4316a83fc7](https://linux-hardware.org/?probe=4316a83fc7) | Apr 24, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [8ed2b2284e](https://linux-hardware.org/?probe=8ed2b2284e) | Apr 24, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [ebbe6aadd7](https://linux-hardware.org/?probe=ebbe6aadd7) | Apr 24, 2021 |
| ASUSTek       | K53E                        | Notebook    | [54fb711c08](https://linux-hardware.org/?probe=54fb711c08) | Apr 23, 2021 |
| HP            | Pavilion dv7                | Notebook    | [b8ddcf6f1e](https://linux-hardware.org/?probe=b8ddcf6f1e) | Apr 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | Notebook    | [101cc9e3ae](https://linux-hardware.org/?probe=101cc9e3ae) | Apr 23, 2021 |
| HP            | 1497                        | Desktop     | [cfa3220a15](https://linux-hardware.org/?probe=cfa3220a15) | Apr 23, 2021 |
| HP            | 1497                        | Desktop     | [6d68a38b71](https://linux-hardware.org/?probe=6d68a38b71) | Apr 23, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [092f84c945](https://linux-hardware.org/?probe=092f84c945) | Apr 23, 2021 |
| HP            | 3397                        | Desktop     | [cbbaaa3476](https://linux-hardware.org/?probe=cbbaaa3476) | Apr 23, 2021 |
| Gigabyte      | F2A88X-D3HP                 | Desktop     | [9f418e1758](https://linux-hardware.org/?probe=9f418e1758) | Apr 23, 2021 |
| Gigabyte      | F2A88X-D3HP                 | Desktop     | [f05632d235](https://linux-hardware.org/?probe=f05632d235) | Apr 23, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [e3b22a36fb](https://linux-hardware.org/?probe=e3b22a36fb) | Apr 22, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [f5715022b7](https://linux-hardware.org/?probe=f5715022b7) | Apr 22, 2021 |
| Apple         | Mac-F2218FA9                | All in one  | [df46bff297](https://linux-hardware.org/?probe=df46bff297) | Apr 22, 2021 |
| Alienware     | 17 R2                       | Notebook    | [494e22b607](https://linux-hardware.org/?probe=494e22b607) | Apr 22, 2021 |
| HP            | 21B4 A01                    | Desktop     | [399b0bbaf6](https://linux-hardware.org/?probe=399b0bbaf6) | Apr 22, 2021 |
| ASUSTek       | X401U                       | Notebook    | [c2a6402a22](https://linux-hardware.org/?probe=c2a6402a22) | Apr 22, 2021 |
| Dell          | Latitude 5590               | Notebook    | [ae217762e2](https://linux-hardware.org/?probe=ae217762e2) | Apr 21, 2021 |
| Dell          | Latitude 5590               | Notebook    | [30a547c92d](https://linux-hardware.org/?probe=30a547c92d) | Apr 21, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [95caa8f42f](https://linux-hardware.org/?probe=95caa8f42f) | Apr 21, 2021 |
| Lenovo        | ThinkPad T420s 4170CTO      | Notebook    | [ae9bb97851](https://linux-hardware.org/?probe=ae9bb97851) | Apr 21, 2021 |
| Dell          | Latitude 5480               | Notebook    | [5c55627582](https://linux-hardware.org/?probe=5c55627582) | Apr 21, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [3a850efa15](https://linux-hardware.org/?probe=3a850efa15) | Apr 20, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [ce5e3cecc1](https://linux-hardware.org/?probe=ce5e3cecc1) | Apr 20, 2021 |
| Entroware     | Proteus                     | Notebook    | [2704b270f4](https://linux-hardware.org/?probe=2704b270f4) | Apr 20, 2021 |
| Unknown       | Unknown                     | Desktop     | [39a0744819](https://linux-hardware.org/?probe=39a0744819) | Apr 20, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [763cd9b744](https://linux-hardware.org/?probe=763cd9b744) | Apr 20, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [724f9724ae](https://linux-hardware.org/?probe=724f9724ae) | Apr 20, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [ddf7e5250e](https://linux-hardware.org/?probe=ddf7e5250e) | Apr 19, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [6558dfd5fd](https://linux-hardware.org/?probe=6558dfd5fd) | Apr 19, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [745a4b18f5](https://linux-hardware.org/?probe=745a4b18f5) | Apr 19, 2021 |
| Dell          | 0G7W4R A00                  | Desktop     | [477ba6a2a6](https://linux-hardware.org/?probe=477ba6a2a6) | Apr 19, 2021 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [5bf2da0f2e](https://linux-hardware.org/?probe=5bf2da0f2e) | Apr 19, 2021 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [9bb274bf17](https://linux-hardware.org/?probe=9bb274bf17) | Apr 19, 2021 |
| HP            | Pavilion g6                 | Notebook    | [ee6b00c1a9](https://linux-hardware.org/?probe=ee6b00c1a9) | Apr 18, 2021 |
| Dell          | Latitude E6410              | Notebook    | [4c36275b5f](https://linux-hardware.org/?probe=4c36275b5f) | Apr 18, 2021 |
| Acer          | Aspire A514-53              | Notebook    | [2a5c4baa8f](https://linux-hardware.org/?probe=2a5c4baa8f) | Apr 18, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [93f314efa4](https://linux-hardware.org/?probe=93f314efa4) | Apr 18, 2021 |
| MSI           | X370 GAMING PLUS            | Desktop     | [4b65b5304b](https://linux-hardware.org/?probe=4b65b5304b) | Apr 18, 2021 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [900e3beebb](https://linux-hardware.org/?probe=900e3beebb) | Apr 18, 2021 |
| ASRock        | B550 Extreme4               | Desktop     | [a221421eba](https://linux-hardware.org/?probe=a221421eba) | Apr 17, 2021 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c5109bab9c](https://linux-hardware.org/?probe=c5109bab9c) | Apr 17, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [aea69bc610](https://linux-hardware.org/?probe=aea69bc610) | Apr 17, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [55c74fc3ae](https://linux-hardware.org/?probe=55c74fc3ae) | Apr 17, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [28c95d7c77](https://linux-hardware.org/?probe=28c95d7c77) | Apr 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1bd86cbcae](https://linux-hardware.org/?probe=1bd86cbcae) | Apr 17, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [9f6aba2632](https://linux-hardware.org/?probe=9f6aba2632) | Apr 16, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [f77abb46a7](https://linux-hardware.org/?probe=f77abb46a7) | Apr 16, 2021 |
| Dell          | Inspiron 5565               | Notebook    | [8f75eda1de](https://linux-hardware.org/?probe=8f75eda1de) | Apr 16, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [d01dac7a8f](https://linux-hardware.org/?probe=d01dac7a8f) | Apr 16, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [1749421eaa](https://linux-hardware.org/?probe=1749421eaa) | Apr 16, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [382673d3f6](https://linux-hardware.org/?probe=382673d3f6) | Apr 15, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [632b6526f7](https://linux-hardware.org/?probe=632b6526f7) | Apr 15, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [21e6f57ac5](https://linux-hardware.org/?probe=21e6f57ac5) | Apr 14, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [43a70e3901](https://linux-hardware.org/?probe=43a70e3901) | Apr 14, 2021 |
| MSI           | GX60 3CC                    | Notebook    | [0725dd67d5](https://linux-hardware.org/?probe=0725dd67d5) | Apr 14, 2021 |
| ASRock        | X79 Extreme4-M              | Desktop     | [80d1c14a8c](https://linux-hardware.org/?probe=80d1c14a8c) | Apr 13, 2021 |
| Unknown       | Unknown                     | Desktop     | [5ed47267b8](https://linux-hardware.org/?probe=5ed47267b8) | Apr 13, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [346db366ae](https://linux-hardware.org/?probe=346db366ae) | Apr 13, 2021 |
| HP            | 18E7                        | Desktop     | [81ec312d3f](https://linux-hardware.org/?probe=81ec312d3f) | Apr 13, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [55e5b4f8be](https://linux-hardware.org/?probe=55e5b4f8be) | Apr 12, 2021 |
| HP            | 255 G1                      | Notebook    | [0244337bdd](https://linux-hardware.org/?probe=0244337bdd) | Apr 12, 2021 |
| HP            | 255 G1                      | Notebook    | [df0d528c9c](https://linux-hardware.org/?probe=df0d528c9c) | Apr 12, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [163f6d6042](https://linux-hardware.org/?probe=163f6d6042) | Apr 12, 2021 |
| Acer          | Aspire A514-53              | Notebook    | [f56ecc6299](https://linux-hardware.org/?probe=f56ecc6299) | Apr 12, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [43cb3af3a5](https://linux-hardware.org/?probe=43cb3af3a5) | Apr 12, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [834cdeef2d](https://linux-hardware.org/?probe=834cdeef2d) | Apr 12, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [bf5944a98e](https://linux-hardware.org/?probe=bf5944a98e) | Apr 12, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [312edcd189](https://linux-hardware.org/?probe=312edcd189) | Apr 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [779ffb190e](https://linux-hardware.org/?probe=779ffb190e) | Apr 11, 2021 |
| HP            | ENVY 17                     | Notebook    | [d548035b69](https://linux-hardware.org/?probe=d548035b69) | Apr 11, 2021 |
| HP            | ENVY 17                     | Notebook    | [a4ee48d831](https://linux-hardware.org/?probe=a4ee48d831) | Apr 11, 2021 |
| Toshiba       | Satellite C850-BLK          | Notebook    | [9c4c8a260c](https://linux-hardware.org/?probe=9c4c8a260c) | Apr 11, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [b7de9b1f0c](https://linux-hardware.org/?probe=b7de9b1f0c) | Apr 11, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [850e9ad783](https://linux-hardware.org/?probe=850e9ad783) | Apr 10, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [9fec121fac](https://linux-hardware.org/?probe=9fec121fac) | Apr 10, 2021 |
| MSI           | PH67S-C43                   | Desktop     | [bf84a891cc](https://linux-hardware.org/?probe=bf84a891cc) | Apr 10, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [88c4aeb7cb](https://linux-hardware.org/?probe=88c4aeb7cb) | Apr 10, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [cc2dcd8258](https://linux-hardware.org/?probe=cc2dcd8258) | Apr 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c367f0f682](https://linux-hardware.org/?probe=c367f0f682) | Apr 10, 2021 |
| HP            | 15                          | Notebook    | [27bcfc6f15](https://linux-hardware.org/?probe=27bcfc6f15) | Apr 10, 2021 |
| HP            | 15                          | Notebook    | [aebfb75282](https://linux-hardware.org/?probe=aebfb75282) | Apr 10, 2021 |
| Wortmann      | TERRA_PC                    | Desktop     | [9224f13a87](https://linux-hardware.org/?probe=9224f13a87) | Apr 09, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [59cb82d24c](https://linux-hardware.org/?probe=59cb82d24c) | Apr 09, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9a9c3c8d26](https://linux-hardware.org/?probe=9a9c3c8d26) | Apr 09, 2021 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [e7997ebffd](https://linux-hardware.org/?probe=e7997ebffd) | Apr 09, 2021 |
| Gigabyte      | B75M-HD3                    | Desktop     | [82dd7f530a](https://linux-hardware.org/?probe=82dd7f530a) | Apr 09, 2021 |
| Gigabyte      | B75M-HD3                    | Desktop     | [f97ecb74c0](https://linux-hardware.org/?probe=f97ecb74c0) | Apr 09, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [a1f4d1a0e6](https://linux-hardware.org/?probe=a1f4d1a0e6) | Apr 09, 2021 |
| Dell          | Latitude E7450              | Notebook    | [3a553eafc9](https://linux-hardware.org/?probe=3a553eafc9) | Apr 08, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [97ea0f0897](https://linux-hardware.org/?probe=97ea0f0897) | Apr 08, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [035b6fca1d](https://linux-hardware.org/?probe=035b6fca1d) | Apr 08, 2021 |
| Lenovo        | ThinkPad T470 20HES18S03    | Notebook    | [8b6474986c](https://linux-hardware.org/?probe=8b6474986c) | Apr 08, 2021 |
| Dell          | Latitude E6410              | Notebook    | [eeecd5d68a](https://linux-hardware.org/?probe=eeecd5d68a) | Apr 08, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [60168d5b6d](https://linux-hardware.org/?probe=60168d5b6d) | Apr 07, 2021 |
| Lenovo        | XiaoXin Air 12 80UN         | Notebook    | [decdc93f63](https://linux-hardware.org/?probe=decdc93f63) | Apr 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8de936a2ca](https://linux-hardware.org/?probe=8de936a2ca) | Apr 07, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [8a34a292e5](https://linux-hardware.org/?probe=8a34a292e5) | Apr 07, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [969b2e9724](https://linux-hardware.org/?probe=969b2e9724) | Apr 07, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [37a29de2c0](https://linux-hardware.org/?probe=37a29de2c0) | Apr 07, 2021 |
| Intel         | DP965LT AAD41694-206        | Desktop     | [16c0660c6b](https://linux-hardware.org/?probe=16c0660c6b) | Apr 07, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [472e239d8d](https://linux-hardware.org/?probe=472e239d8d) | Apr 07, 2021 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [fcbaa285ef](https://linux-hardware.org/?probe=fcbaa285ef) | Apr 07, 2021 |
| Dell          | Latitude E7450              | Notebook    | [6bbbb32ae9](https://linux-hardware.org/?probe=6bbbb32ae9) | Apr 06, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [52053aadc4](https://linux-hardware.org/?probe=52053aadc4) | Apr 06, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [8f3bd77b70](https://linux-hardware.org/?probe=8f3bd77b70) | Apr 06, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [c55d72e928](https://linux-hardware.org/?probe=c55d72e928) | Apr 06, 2021 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [f0b779a05d](https://linux-hardware.org/?probe=f0b779a05d) | Apr 05, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [830633eff6](https://linux-hardware.org/?probe=830633eff6) | Apr 05, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [332a730e31](https://linux-hardware.org/?probe=332a730e31) | Apr 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [de28910ce1](https://linux-hardware.org/?probe=de28910ce1) | Apr 05, 2021 |
| HP            | 86F0 11000                  | All in one  | [5fd801909f](https://linux-hardware.org/?probe=5fd801909f) | Apr 05, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [f7a69f2819](https://linux-hardware.org/?probe=f7a69f2819) | Apr 04, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b7ca2f4a18](https://linux-hardware.org/?probe=b7ca2f4a18) | Apr 04, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [bc92089206](https://linux-hardware.org/?probe=bc92089206) | Apr 04, 2021 |
| Dell          | Latitude E6410              | Notebook    | [a8a00914e7](https://linux-hardware.org/?probe=a8a00914e7) | Apr 04, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [0b31a00f14](https://linux-hardware.org/?probe=0b31a00f14) | Apr 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [831b3f8c68](https://linux-hardware.org/?probe=831b3f8c68) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [e8c59a070a](https://linux-hardware.org/?probe=e8c59a070a) | Apr 04, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2ca16685f0](https://linux-hardware.org/?probe=2ca16685f0) | Apr 03, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [0eaf54f4f5](https://linux-hardware.org/?probe=0eaf54f4f5) | Apr 03, 2021 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [819d6e7ad3](https://linux-hardware.org/?probe=819d6e7ad3) | Apr 03, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [51543dbb4d](https://linux-hardware.org/?probe=51543dbb4d) | Apr 03, 2021 |
| ASUSTek       | H110M-C                     | Desktop     | [5809742ae4](https://linux-hardware.org/?probe=5809742ae4) | Apr 02, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [ee6713c200](https://linux-hardware.org/?probe=ee6713c200) | Apr 02, 2021 |
| ASRock        | Z270 Gaming-ITX/ac          | Desktop     | [c4b61cff94](https://linux-hardware.org/?probe=c4b61cff94) | Apr 02, 2021 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [a487078d9f](https://linux-hardware.org/?probe=a487078d9f) | Apr 02, 2021 |
| Dell          | Studio 1747                 | Notebook    | [31c1b6a828](https://linux-hardware.org/?probe=31c1b6a828) | Apr 01, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [f74fdee693](https://linux-hardware.org/?probe=f74fdee693) | Apr 01, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [4080e1b43f](https://linux-hardware.org/?probe=4080e1b43f) | Apr 01, 2021 |
| Wortmann      | TERRA_PC                    | Desktop     | [dfb7105a9a](https://linux-hardware.org/?probe=dfb7105a9a) | Mar 31, 2021 |
| Wortmann      | TERRA_PC                    | Desktop     | [c107b4f1a1](https://linux-hardware.org/?probe=c107b4f1a1) | Mar 31, 2021 |
| HP            | 8299                        | Desktop     | [12120a16f6](https://linux-hardware.org/?probe=12120a16f6) | Mar 30, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [d4f182e3de](https://linux-hardware.org/?probe=d4f182e3de) | Mar 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [07ad242a41](https://linux-hardware.org/?probe=07ad242a41) | Mar 30, 2021 |
| Dell          | Precision 5550              | Notebook    | [76fb436ef0](https://linux-hardware.org/?probe=76fb436ef0) | Mar 29, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [4caff5f0c4](https://linux-hardware.org/?probe=4caff5f0c4) | Mar 29, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b64ef3b76d](https://linux-hardware.org/?probe=b64ef3b76d) | Mar 29, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6ae91d7edf](https://linux-hardware.org/?probe=6ae91d7edf) | Mar 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [26427e6d23](https://linux-hardware.org/?probe=26427e6d23) | Mar 29, 2021 |
| HP            | Pavilion g6                 | Notebook    | [4bbe96d0c3](https://linux-hardware.org/?probe=4bbe96d0c3) | Mar 29, 2021 |
| HP            | Pavilion g6                 | Notebook    | [509c863d2e](https://linux-hardware.org/?probe=509c863d2e) | Mar 29, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [262c2c82c1](https://linux-hardware.org/?probe=262c2c82c1) | Mar 29, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [4d05114173](https://linux-hardware.org/?probe=4d05114173) | Mar 28, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [5ff7a11404](https://linux-hardware.org/?probe=5ff7a11404) | Mar 28, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [300de99867](https://linux-hardware.org/?probe=300de99867) | Mar 28, 2021 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [9e88c8329e](https://linux-hardware.org/?probe=9e88c8329e) | Mar 28, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [39d2fcc25c](https://linux-hardware.org/?probe=39d2fcc25c) | Mar 28, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [a8d52f4df8](https://linux-hardware.org/?probe=a8d52f4df8) | Mar 28, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [8253b82c52](https://linux-hardware.org/?probe=8253b82c52) | Mar 28, 2021 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [c849cdad45](https://linux-hardware.org/?probe=c849cdad45) | Mar 27, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [04469024ca](https://linux-hardware.org/?probe=04469024ca) | Mar 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [151e709efd](https://linux-hardware.org/?probe=151e709efd) | Mar 25, 2021 |
| Dell          | Latitude 5590               | Notebook    | [68c7d0b5f9](https://linux-hardware.org/?probe=68c7d0b5f9) | Mar 25, 2021 |
| Dell          | Latitude E4310              | Notebook    | [9e4e10b6ac](https://linux-hardware.org/?probe=9e4e10b6ac) | Mar 25, 2021 |
| MSI           | GL75 Leopard 10SCSR         | Notebook    | [056f4dde93](https://linux-hardware.org/?probe=056f4dde93) | Mar 25, 2021 |
| Notebook      | W65_67SF                    | Notebook    | [18494a4239](https://linux-hardware.org/?probe=18494a4239) | Mar 25, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bb2ba9b142](https://linux-hardware.org/?probe=bb2ba9b142) | Mar 24, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [973d60c63e](https://linux-hardware.org/?probe=973d60c63e) | Mar 24, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [5d6376b524](https://linux-hardware.org/?probe=5d6376b524) | Mar 24, 2021 |
| Acer          | FIH57                       | Desktop     | [ddb03d82a0](https://linux-hardware.org/?probe=ddb03d82a0) | Mar 24, 2021 |
| Samsung       | RV415/RV515                 | Notebook    | [1e7bd01136](https://linux-hardware.org/?probe=1e7bd01136) | Mar 23, 2021 |
| Dell          | Latitude 5590               | Notebook    | [65a8093ecc](https://linux-hardware.org/?probe=65a8093ecc) | Mar 23, 2021 |
| Acer          | Aspire A515-44G             | Notebook    | [cee95b2125](https://linux-hardware.org/?probe=cee95b2125) | Mar 23, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [39ca68ed11](https://linux-hardware.org/?probe=39ca68ed11) | Mar 23, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [c434219563](https://linux-hardware.org/?probe=c434219563) | Mar 22, 2021 |
| MSI           | B365M PRO-VDH               | Desktop     | [85eae8241f](https://linux-hardware.org/?probe=85eae8241f) | Mar 22, 2021 |
| Sony          | VPCCW25FL                   | Notebook    | [b0f9776d13](https://linux-hardware.org/?probe=b0f9776d13) | Mar 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [86b43bd4f4](https://linux-hardware.org/?probe=86b43bd4f4) | Mar 21, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b139612360](https://linux-hardware.org/?probe=b139612360) | Mar 21, 2021 |
| Positivo      | C14CR01                     | Notebook    | [80a20c54ab](https://linux-hardware.org/?probe=80a20c54ab) | Mar 21, 2021 |
| Sony          | VPCCW25FL                   | Notebook    | [6ac0416576](https://linux-hardware.org/?probe=6ac0416576) | Mar 21, 2021 |
| Gigabyte      | P61-S3                      | Desktop     | [b146f03965](https://linux-hardware.org/?probe=b146f03965) | Mar 20, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [6270efa573](https://linux-hardware.org/?probe=6270efa573) | Mar 20, 2021 |
| ASUSTek       | ZN242GD                     | All in one  | [608d0ce708](https://linux-hardware.org/?probe=608d0ce708) | Mar 20, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [af1f2a3c0d](https://linux-hardware.org/?probe=af1f2a3c0d) | Mar 20, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [cac842cdbb](https://linux-hardware.org/?probe=cac842cdbb) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e2f4d3b86f](https://linux-hardware.org/?probe=e2f4d3b86f) | Mar 20, 2021 |
| Seco          | C40 C                       | Desktop     | [70a92f2d8a](https://linux-hardware.org/?probe=70a92f2d8a) | Mar 19, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [ac215043f1](https://linux-hardware.org/?probe=ac215043f1) | Mar 19, 2021 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [edac373896](https://linux-hardware.org/?probe=edac373896) | Mar 19, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [45cb6a5741](https://linux-hardware.org/?probe=45cb6a5741) | Mar 18, 2021 |
| Intel         | Tiger Lake Client Platfo... | Notebook    | [da214bbadb](https://linux-hardware.org/?probe=da214bbadb) | Mar 18, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [4c78db6d10](https://linux-hardware.org/?probe=4c78db6d10) | Mar 18, 2021 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [42afab4523](https://linux-hardware.org/?probe=42afab4523) | Mar 18, 2021 |
| ASRock        | H67DE3                      | Desktop     | [14e5916050](https://linux-hardware.org/?probe=14e5916050) | Mar 18, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [b39a7d0921](https://linux-hardware.org/?probe=b39a7d0921) | Mar 17, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [23762cf400](https://linux-hardware.org/?probe=23762cf400) | Mar 17, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e373906f4c](https://linux-hardware.org/?probe=e373906f4c) | Mar 17, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [af8d6ec07e](https://linux-hardware.org/?probe=af8d6ec07e) | Mar 17, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [771a7d83ec](https://linux-hardware.org/?probe=771a7d83ec) | Mar 17, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [39fe1b14e2](https://linux-hardware.org/?probe=39fe1b14e2) | Mar 17, 2021 |
| Gigabyte      | Z87-HD3                     | Desktop     | [ff76102e23](https://linux-hardware.org/?probe=ff76102e23) | Mar 17, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [5b66ed3114](https://linux-hardware.org/?probe=5b66ed3114) | Mar 17, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [f6316adf72](https://linux-hardware.org/?probe=f6316adf72) | Mar 17, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [e323f3efa7](https://linux-hardware.org/?probe=e323f3efa7) | Mar 17, 2021 |
| Dell          | Latitude 5501               | Notebook    | [ec0cbf54dd](https://linux-hardware.org/?probe=ec0cbf54dd) | Mar 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4d8d7a3551](https://linux-hardware.org/?probe=4d8d7a3551) | Mar 17, 2021 |
| HP            | ProBook 4730s               | Notebook    | [5809a45a9a](https://linux-hardware.org/?probe=5809a45a9a) | Mar 17, 2021 |
| ASUSTek       | N551JM                      | Notebook    | [7faf90e652](https://linux-hardware.org/?probe=7faf90e652) | Mar 17, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [285b5b2d08](https://linux-hardware.org/?probe=285b5b2d08) | Mar 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [8d658bd869](https://linux-hardware.org/?probe=8d658bd869) | Mar 17, 2021 |
| Timi          | TM1607                      | Notebook    | [d2c709792b](https://linux-hardware.org/?probe=d2c709792b) | Mar 16, 2021 |
| ASRock        | G41C-VS                     | Desktop     | [6ef4d0ea12](https://linux-hardware.org/?probe=6ef4d0ea12) | Mar 16, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [ac92ab9404](https://linux-hardware.org/?probe=ac92ab9404) | Mar 15, 2021 |
| Dell          | XPS L701X                   | Notebook    | [a5c9be727c](https://linux-hardware.org/?probe=a5c9be727c) | Mar 15, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [d189562952](https://linux-hardware.org/?probe=d189562952) | Mar 15, 2021 |
| Google        | Coral                       | Notebook    | [6cd9280b52](https://linux-hardware.org/?probe=6cd9280b52) | Mar 15, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [402cbaf164](https://linux-hardware.org/?probe=402cbaf164) | Mar 15, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [1c87cc6728](https://linux-hardware.org/?probe=1c87cc6728) | Mar 15, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e34ec3b73f](https://linux-hardware.org/?probe=e34ec3b73f) | Mar 15, 2021 |
| Dell          | Inspiron N7110              | Notebook    | [fe4bf0f1bb](https://linux-hardware.org/?probe=fe4bf0f1bb) | Mar 15, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [3bf2664982](https://linux-hardware.org/?probe=3bf2664982) | Mar 14, 2021 |
| MSI           | MPG Z490M GAMING EDGE WI... | Desktop     | [b8d7e8ae57](https://linux-hardware.org/?probe=b8d7e8ae57) | Mar 14, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [50735eb518](https://linux-hardware.org/?probe=50735eb518) | Mar 13, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [08501b7f5a](https://linux-hardware.org/?probe=08501b7f5a) | Mar 13, 2021 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | Notebook    | [f784781973](https://linux-hardware.org/?probe=f784781973) | Mar 13, 2021 |
| HUAWEI        | MACHR-WX9                   | Notebook    | [32ddd24929](https://linux-hardware.org/?probe=32ddd24929) | Mar 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [640a0a3857](https://linux-hardware.org/?probe=640a0a3857) | Mar 13, 2021 |
| Dell          | 0KRC95 A02                  | Desktop     | [ced325be18](https://linux-hardware.org/?probe=ced325be18) | Mar 12, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [8e8f1a2dee](https://linux-hardware.org/?probe=8e8f1a2dee) | Mar 12, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [8027a5eab2](https://linux-hardware.org/?probe=8027a5eab2) | Mar 12, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [d0b9267af6](https://linux-hardware.org/?probe=d0b9267af6) | Mar 12, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [5a3ce75489](https://linux-hardware.org/?probe=5a3ce75489) | Mar 12, 2021 |
| Acer          | Aspire 5742                 | Notebook    | [61d8c3bf71](https://linux-hardware.org/?probe=61d8c3bf71) | Mar 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [66de852009](https://linux-hardware.org/?probe=66de852009) | Mar 11, 2021 |
| Dell          | Latitude 5590               | Notebook    | [85ab1b4349](https://linux-hardware.org/?probe=85ab1b4349) | Mar 11, 2021 |
| ASRock        | B550 Extreme4               | Desktop     | [79444a2f75](https://linux-hardware.org/?probe=79444a2f75) | Mar 11, 2021 |
| Dell          | Latitude 5590               | Notebook    | [d2b562137b](https://linux-hardware.org/?probe=d2b562137b) | Mar 11, 2021 |
| ASRock        | B550 Extreme4               | Desktop     | [93620deb05](https://linux-hardware.org/?probe=93620deb05) | Mar 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [3315bb8f22](https://linux-hardware.org/?probe=3315bb8f22) | Mar 08, 2021 |
| Notebook      | W54_55_94_95_97AU,AUQ       | Notebook    | [1a4c02ee0c](https://linux-hardware.org/?probe=1a4c02ee0c) | Mar 08, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [b7e979c3a3](https://linux-hardware.org/?probe=b7e979c3a3) | Mar 07, 2021 |
| HP            | Stream Notebook PC 14       | Notebook    | [72a34a3dd4](https://linux-hardware.org/?probe=72a34a3dd4) | Mar 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ad1380deaa](https://linux-hardware.org/?probe=ad1380deaa) | Mar 05, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d63ded0915](https://linux-hardware.org/?probe=d63ded0915) | Mar 05, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7e69e82879](https://linux-hardware.org/?probe=7e69e82879) | Mar 05, 2021 |
| ASRock        | 990FX Extreme3              | Desktop     | [ee5505ce8e](https://linux-hardware.org/?probe=ee5505ce8e) | Mar 05, 2021 |
| Samsung       | 370E4K                      | Notebook    | [5f1f92fd09](https://linux-hardware.org/?probe=5f1f92fd09) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [28a8889148](https://linux-hardware.org/?probe=28a8889148) | Mar 04, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [67054a2b55](https://linux-hardware.org/?probe=67054a2b55) | Mar 04, 2021 |
| Dell          | XPS M1530                   | Notebook    | [9f9d1a39f5](https://linux-hardware.org/?probe=9f9d1a39f5) | Mar 03, 2021 |
| HP            | ProBook 6470b               | Notebook    | [81a0b5f406](https://linux-hardware.org/?probe=81a0b5f406) | Mar 03, 2021 |
| HP            | ProBook 6470b               | Notebook    | [169cf86ae0](https://linux-hardware.org/?probe=169cf86ae0) | Mar 03, 2021 |
| Gigabyte      | GA-970-Gaming SLI-CF        | Desktop     | [e3f7effc1c](https://linux-hardware.org/?probe=e3f7effc1c) | Mar 03, 2021 |
| Acer          | Aspire X3400                | Desktop     | [37dca6b989](https://linux-hardware.org/?probe=37dca6b989) | Mar 03, 2021 |
| Biostar       | A78MD                       | Desktop     | [0bd08c0771](https://linux-hardware.org/?probe=0bd08c0771) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [97a0014c21](https://linux-hardware.org/?probe=97a0014c21) | Mar 02, 2021 |
| HP            | 8299                        | Desktop     | [e8e31dfc6e](https://linux-hardware.org/?probe=e8e31dfc6e) | Mar 01, 2021 |
| HP            | Pavilion 15                 | Notebook    | [7899110cfa](https://linux-hardware.org/?probe=7899110cfa) | Mar 01, 2021 |
| HP            | 2000                        | Notebook    | [48946efc8f](https://linux-hardware.org/?probe=48946efc8f) | Mar 01, 2021 |
| Dell          | 0NK70N A03                  | Desktop     | [f62aef3e7a](https://linux-hardware.org/?probe=f62aef3e7a) | Feb 28, 2021 |
| ZOTAC         | ZBOX-ID92/ZBOX-IQ01         | Mini pc     | [fcaa602427](https://linux-hardware.org/?probe=fcaa602427) | Feb 28, 2021 |
| Biostar       | A78MD                       | Desktop     | [06b1319f09](https://linux-hardware.org/?probe=06b1319f09) | Feb 28, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [6cc823cf63](https://linux-hardware.org/?probe=6cc823cf63) | Feb 28, 2021 |
| Biostar       | A78MD                       | Desktop     | [c468e84e6d](https://linux-hardware.org/?probe=c468e84e6d) | Feb 28, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [94f5daf626](https://linux-hardware.org/?probe=94f5daf626) | Feb 28, 2021 |
| HP            | 15                          | Notebook    | [3d3d11173c](https://linux-hardware.org/?probe=3d3d11173c) | Feb 27, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [88dfa8bfe4](https://linux-hardware.org/?probe=88dfa8bfe4) | Feb 27, 2021 |
| Acer          | Aspire A515-52G             | Notebook    | [b36a5467df](https://linux-hardware.org/?probe=b36a5467df) | Feb 27, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [3c6f2b954f](https://linux-hardware.org/?probe=3c6f2b954f) | Feb 27, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [0560c0ea42](https://linux-hardware.org/?probe=0560c0ea42) | Feb 27, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [3e7cc43118](https://linux-hardware.org/?probe=3e7cc43118) | Feb 27, 2021 |
| Dell          | 07PR60 A01                  | Desktop     | [fd52f038fb](https://linux-hardware.org/?probe=fd52f038fb) | Feb 26, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [12ac027d4a](https://linux-hardware.org/?probe=12ac027d4a) | Feb 26, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [eca76d9f64](https://linux-hardware.org/?probe=eca76d9f64) | Feb 25, 2021 |
| Dell          | G5 5500                     | Notebook    | [786bdf5cec](https://linux-hardware.org/?probe=786bdf5cec) | Feb 25, 2021 |
| Dell          | 0FH884                      | Desktop     | [3f73f703ea](https://linux-hardware.org/?probe=3f73f703ea) | Feb 25, 2021 |
| ASUSTek       | GL502VY                     | Notebook    | [8dddc7e74c](https://linux-hardware.org/?probe=8dddc7e74c) | Feb 24, 2021 |
| Lenovo        | ThinkPad E15 20RD003JRT     | Notebook    | [7c9fd9dde4](https://linux-hardware.org/?probe=7c9fd9dde4) | Feb 24, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [9bec1814a1](https://linux-hardware.org/?probe=9bec1814a1) | Feb 24, 2021 |
| Lenovo        | ThinkPad E15 20RD003JRT     | Notebook    | [933bd46a35](https://linux-hardware.org/?probe=933bd46a35) | Feb 24, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [08723d28a4](https://linux-hardware.org/?probe=08723d28a4) | Feb 24, 2021 |
| Dell          | 0FH884                      | Desktop     | [9ef7d7ac26](https://linux-hardware.org/?probe=9ef7d7ac26) | Feb 24, 2021 |
| Dell          | Latitude E6430s             | Notebook    | [cb9032f7b7](https://linux-hardware.org/?probe=cb9032f7b7) | Feb 24, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [fc1cb7dbc8](https://linux-hardware.org/?probe=fc1cb7dbc8) | Feb 23, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [f3e1294a65](https://linux-hardware.org/?probe=f3e1294a65) | Feb 23, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [6950c83451](https://linux-hardware.org/?probe=6950c83451) | Feb 22, 2021 |
| Sony          | VGN-TZ150N                  | Notebook    | [213e5e739e](https://linux-hardware.org/?probe=213e5e739e) | Feb 22, 2021 |
| HP            | 1589                        | Desktop     | [8784e0d9ad](https://linux-hardware.org/?probe=8784e0d9ad) | Feb 22, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [9493316900](https://linux-hardware.org/?probe=9493316900) | Feb 22, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [fce5467293](https://linux-hardware.org/?probe=fce5467293) | Feb 21, 2021 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [19bc1494c6](https://linux-hardware.org/?probe=19bc1494c6) | Feb 21, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e6bcb06746](https://linux-hardware.org/?probe=e6bcb06746) | Feb 20, 2021 |
| HP            | Pavilion 15                 | Notebook    | [5ae0982f1c](https://linux-hardware.org/?probe=5ae0982f1c) | Feb 20, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [80bebb61bc](https://linux-hardware.org/?probe=80bebb61bc) | Feb 20, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [0abecd63a7](https://linux-hardware.org/?probe=0abecd63a7) | Feb 19, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [25a2434de6](https://linux-hardware.org/?probe=25a2434de6) | Feb 19, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [cc6c16c095](https://linux-hardware.org/?probe=cc6c16c095) | Feb 19, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [91775ad60e](https://linux-hardware.org/?probe=91775ad60e) | Feb 19, 2021 |
| Unknown       | Unknown                     | Notebook    | [b5c80cfa67](https://linux-hardware.org/?probe=b5c80cfa67) | Feb 19, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [5c5b3ce155](https://linux-hardware.org/?probe=5c5b3ce155) | Feb 19, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [3554afd877](https://linux-hardware.org/?probe=3554afd877) | Feb 19, 2021 |
| HP            | 8433 11                     | Desktop     | [32c974b562](https://linux-hardware.org/?probe=32c974b562) | Feb 19, 2021 |
| HP            | 8433 11                     | Desktop     | [a48247a3c8](https://linux-hardware.org/?probe=a48247a3c8) | Feb 19, 2021 |
| Gigabyte      | PH67-DS3-B3                 | Desktop     | [bc80a6485e](https://linux-hardware.org/?probe=bc80a6485e) | Feb 18, 2021 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [2caf18393e](https://linux-hardware.org/?probe=2caf18393e) | Feb 18, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [dccd0e25f6](https://linux-hardware.org/?probe=dccd0e25f6) | Feb 18, 2021 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [ea95229d12](https://linux-hardware.org/?probe=ea95229d12) | Feb 18, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [acdf8601fd](https://linux-hardware.org/?probe=acdf8601fd) | Feb 18, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [51e50d143a](https://linux-hardware.org/?probe=51e50d143a) | Feb 18, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [4275f330af](https://linux-hardware.org/?probe=4275f330af) | Feb 18, 2021 |
| Dell          | 040DDP A00                  | Desktop     | [5bdc232dbb](https://linux-hardware.org/?probe=5bdc232dbb) | Feb 18, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [31612033c1](https://linux-hardware.org/?probe=31612033c1) | Feb 18, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [aa1126a11b](https://linux-hardware.org/?probe=aa1126a11b) | Feb 17, 2021 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [494fd3428d](https://linux-hardware.org/?probe=494fd3428d) | Feb 17, 2021 |
| Notebook      | W65_67SJ                    | Notebook    | [27f2a581af](https://linux-hardware.org/?probe=27f2a581af) | Feb 17, 2021 |
| Notebook      | W65_67SJ                    | Notebook    | [d9841ed6c0](https://linux-hardware.org/?probe=d9841ed6c0) | Feb 17, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [65b32aa4a5](https://linux-hardware.org/?probe=65b32aa4a5) | Feb 16, 2021 |
| Intel         | H55                         | Desktop     | [695737f53f](https://linux-hardware.org/?probe=695737f53f) | Feb 16, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [fb6179a8ee](https://linux-hardware.org/?probe=fb6179a8ee) | Feb 16, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [c35cacb0a2](https://linux-hardware.org/?probe=c35cacb0a2) | Feb 15, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [ef1ee4c17d](https://linux-hardware.org/?probe=ef1ee4c17d) | Feb 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [0954aa8af0](https://linux-hardware.org/?probe=0954aa8af0) | Feb 15, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [848bce680c](https://linux-hardware.org/?probe=848bce680c) | Feb 15, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [823717302d](https://linux-hardware.org/?probe=823717302d) | Feb 15, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [c364bd22bf](https://linux-hardware.org/?probe=c364bd22bf) | Feb 14, 2021 |
| JINGSHA       | Unknown                     | Desktop     | [8f0c5a3c20](https://linux-hardware.org/?probe=8f0c5a3c20) | Feb 14, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [22f56fdeda](https://linux-hardware.org/?probe=22f56fdeda) | Feb 14, 2021 |
| Lenovo        | ThinkCentre M90p 5498PK8    | Desktop     | [df39a8847b](https://linux-hardware.org/?probe=df39a8847b) | Feb 14, 2021 |
| Hampoo        | I1D6_C109K                  | Tablet      | [41b4b04e73](https://linux-hardware.org/?probe=41b4b04e73) | Feb 13, 2021 |
| Acer          | Aspire 5732Z                | Notebook    | [7ad83acc43](https://linux-hardware.org/?probe=7ad83acc43) | Feb 13, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [c7f9230c06](https://linux-hardware.org/?probe=c7f9230c06) | Feb 13, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [99b31bd894](https://linux-hardware.org/?probe=99b31bd894) | Feb 13, 2021 |
| MSI           | B85M-E45                    | Desktop     | [16c99d1061](https://linux-hardware.org/?probe=16c99d1061) | Feb 13, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [5c51e139e0](https://linux-hardware.org/?probe=5c51e139e0) | Feb 12, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [67abd4509a](https://linux-hardware.org/?probe=67abd4509a) | Feb 12, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [0b9e39df3d](https://linux-hardware.org/?probe=0b9e39df3d) | Feb 12, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [13d6b7a012](https://linux-hardware.org/?probe=13d6b7a012) | Feb 12, 2021 |
| MSI           | X58 Pro                     | Desktop     | [335083a19f](https://linux-hardware.org/?probe=335083a19f) | Feb 12, 2021 |
| Lenovo        | ThinkPad P53 20QQ000WBR     | Notebook    | [b9e89297b4](https://linux-hardware.org/?probe=b9e89297b4) | Feb 11, 2021 |
| ASRock        | X570 Extreme4               | Desktop     | [3f2929b8fd](https://linux-hardware.org/?probe=3f2929b8fd) | Feb 11, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [b0adc07739](https://linux-hardware.org/?probe=b0adc07739) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d993271043](https://linux-hardware.org/?probe=d993271043) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ab8c311c17](https://linux-hardware.org/?probe=ab8c311c17) | Feb 11, 2021 |
| HP            | Pavilion dv5                | Notebook    | [a1d8a0b99b](https://linux-hardware.org/?probe=a1d8a0b99b) | Feb 10, 2021 |
| HP            | Pavilion dv5                | Notebook    | [fe4b5ef832](https://linux-hardware.org/?probe=fe4b5ef832) | Feb 10, 2021 |
| Dell          | Precision M4700             | Notebook    | [fb357e9f90](https://linux-hardware.org/?probe=fb357e9f90) | Feb 10, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [4f0639f7c9](https://linux-hardware.org/?probe=4f0639f7c9) | Feb 10, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [e3d953f88d](https://linux-hardware.org/?probe=e3d953f88d) | Feb 10, 2021 |
| DBM           | W54_W94_W955TU,-T,-C        | Notebook    | [2c4b40e7db](https://linux-hardware.org/?probe=2c4b40e7db) | Feb 10, 2021 |
| Dell          | Latitude 7480               | Notebook    | [fdcec0b826](https://linux-hardware.org/?probe=fdcec0b826) | Feb 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [f9cd3234a8](https://linux-hardware.org/?probe=f9cd3234a8) | Feb 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [55f9a9c65d](https://linux-hardware.org/?probe=55f9a9c65d) | Feb 10, 2021 |
| MSI           | GE66 Raider 10SF            | Notebook    | [a9bc0b88b6](https://linux-hardware.org/?probe=a9bc0b88b6) | Feb 10, 2021 |
| Dell          | 0F896N A03                  | Desktop     | [2dd5786964](https://linux-hardware.org/?probe=2dd5786964) | Feb 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [84cb0d787d](https://linux-hardware.org/?probe=84cb0d787d) | Feb 09, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [a82b69905f](https://linux-hardware.org/?probe=a82b69905f) | Feb 09, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [6679a796a7](https://linux-hardware.org/?probe=6679a796a7) | Feb 09, 2021 |
| Dell          | Precision M4700             | Notebook    | [f674f91052](https://linux-hardware.org/?probe=f674f91052) | Feb 08, 2021 |
| AZW           | Gemini M                    | Desktop     | [a610efb6d7](https://linux-hardware.org/?probe=a610efb6d7) | Feb 08, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [dd9e4c1dde](https://linux-hardware.org/?probe=dd9e4c1dde) | Feb 07, 2021 |
| Dell          | Inspiron 17-7779            | Notebook    | [f579f7a11c](https://linux-hardware.org/?probe=f579f7a11c) | Feb 06, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [38121d8789](https://linux-hardware.org/?probe=38121d8789) | Feb 06, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [1835552ae4](https://linux-hardware.org/?probe=1835552ae4) | Feb 06, 2021 |
| HP            | 2000                        | Notebook    | [cd28e0c1a6](https://linux-hardware.org/?probe=cd28e0c1a6) | Feb 06, 2021 |
| Intel         | D33217GKE G76540-205        | Desktop     | [acd358e227](https://linux-hardware.org/?probe=acd358e227) | Feb 06, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c40d5bfeff](https://linux-hardware.org/?probe=c40d5bfeff) | Feb 05, 2021 |
| MSI           | G31TM-P21                   | Desktop     | [32a55d5e20](https://linux-hardware.org/?probe=32a55d5e20) | Feb 05, 2021 |
| Dell          | Inspiron 17-7779            | Notebook    | [e146e67342](https://linux-hardware.org/?probe=e146e67342) | Feb 05, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [ceda1f734f](https://linux-hardware.org/?probe=ceda1f734f) | Feb 04, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [42eea1df17](https://linux-hardware.org/?probe=42eea1df17) | Feb 04, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [d14e71b6b4](https://linux-hardware.org/?probe=d14e71b6b4) | Feb 03, 2021 |
| Dell          | Latitude 5480               | Notebook    | [d4927a9f76](https://linux-hardware.org/?probe=d4927a9f76) | Feb 02, 2021 |
| Sony          | SVE15126CXS                 | Notebook    | [8a27b129a3](https://linux-hardware.org/?probe=8a27b129a3) | Feb 02, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [c46120b50e](https://linux-hardware.org/?probe=c46120b50e) | Feb 01, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [d88bfb96f9](https://linux-hardware.org/?probe=d88bfb96f9) | Feb 01, 2021 |
| Gigabyte      | EX58-UD5                    | Desktop     | [9743cd82ce](https://linux-hardware.org/?probe=9743cd82ce) | Feb 01, 2021 |
| MSI           | Z170A SLI PLUS              | Desktop     | [2e49a21374](https://linux-hardware.org/?probe=2e49a21374) | Feb 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2ed96135f2](https://linux-hardware.org/?probe=2ed96135f2) | Feb 01, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [1292b81dfa](https://linux-hardware.org/?probe=1292b81dfa) | Feb 01, 2021 |
| HP            | 8299                        | Desktop     | [16e50ec1cd](https://linux-hardware.org/?probe=16e50ec1cd) | Jan 31, 2021 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [d0cfe35dee](https://linux-hardware.org/?probe=d0cfe35dee) | Jan 31, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [9b8f5ee4b1](https://linux-hardware.org/?probe=9b8f5ee4b1) | Jan 31, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [bc856a8f93](https://linux-hardware.org/?probe=bc856a8f93) | Jan 31, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [8f8b3ad8e1](https://linux-hardware.org/?probe=8f8b3ad8e1) | Jan 31, 2021 |
| ASUSTek       | N56JN                       | Notebook    | [02008fdd48](https://linux-hardware.org/?probe=02008fdd48) | Jan 31, 2021 |
| HP            | 8768 A                      | Desktop     | [d3d1523106](https://linux-hardware.org/?probe=d3d1523106) | Jan 31, 2021 |
| ASRock        | E350M1/USB3                 | Desktop     | [fc0abf0e10](https://linux-hardware.org/?probe=fc0abf0e10) | Jan 30, 2021 |
| Schenker      | SCHENKER VIA 15 Pro         | Notebook    | [4f091c50f8](https://linux-hardware.org/?probe=4f091c50f8) | Jan 30, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b9b9477857](https://linux-hardware.org/?probe=b9b9477857) | Jan 30, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [203f2abb14](https://linux-hardware.org/?probe=203f2abb14) | Jan 30, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [f1d00fff81](https://linux-hardware.org/?probe=f1d00fff81) | Jan 30, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [9415eb01f4](https://linux-hardware.org/?probe=9415eb01f4) | Jan 29, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [505a889ab1](https://linux-hardware.org/?probe=505a889ab1) | Jan 29, 2021 |
| Dell          | Latitude E7240              | Notebook    | [27236969c7](https://linux-hardware.org/?probe=27236969c7) | Jan 29, 2021 |
| Lenovo        | ThinkPad L430 2466EC5       | Notebook    | [8f5111df1d](https://linux-hardware.org/?probe=8f5111df1d) | Jan 28, 2021 |
| Acer          | Extensa 5230                | Notebook    | [7a92f28b53](https://linux-hardware.org/?probe=7a92f28b53) | Jan 28, 2021 |
| ASUSTek       | UX331UA                     | Notebook    | [6360711ded](https://linux-hardware.org/?probe=6360711ded) | Jan 28, 2021 |
| HP            | 250 G3                      | Notebook    | [19a1d2d008](https://linux-hardware.org/?probe=19a1d2d008) | Jan 28, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [77c2137bbd](https://linux-hardware.org/?probe=77c2137bbd) | Jan 28, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [81b93f4513](https://linux-hardware.org/?probe=81b93f4513) | Jan 27, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [eac34165b9](https://linux-hardware.org/?probe=eac34165b9) | Jan 27, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [f8f1db15da](https://linux-hardware.org/?probe=f8f1db15da) | Jan 26, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8c7c26863a](https://linux-hardware.org/?probe=8c7c26863a) | Jan 26, 2021 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [1a3802ce22](https://linux-hardware.org/?probe=1a3802ce22) | Jan 26, 2021 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [78e47079a6](https://linux-hardware.org/?probe=78e47079a6) | Jan 26, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [e576c1b644](https://linux-hardware.org/?probe=e576c1b644) | Jan 26, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [eb08059af1](https://linux-hardware.org/?probe=eb08059af1) | Jan 25, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [3ae7d1367d](https://linux-hardware.org/?probe=3ae7d1367d) | Jan 25, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [14e98bee82](https://linux-hardware.org/?probe=14e98bee82) | Jan 25, 2021 |
| Intel         | HuronRiver Platform         | Notebook    | [1ace53e871](https://linux-hardware.org/?probe=1ace53e871) | Jan 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4cacca5cdf](https://linux-hardware.org/?probe=4cacca5cdf) | Jan 25, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a2454e8838](https://linux-hardware.org/?probe=a2454e8838) | Jan 24, 2021 |
| Sony          | SVE1711V1RB                 | Notebook    | [47cc12535d](https://linux-hardware.org/?probe=47cc12535d) | Jan 24, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [f44186ef76](https://linux-hardware.org/?probe=f44186ef76) | Jan 24, 2021 |
| Dell          | Latitude E6430              | Notebook    | [f5bb578cc8](https://linux-hardware.org/?probe=f5bb578cc8) | Jan 24, 2021 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [c102ffe8b4](https://linux-hardware.org/?probe=c102ffe8b4) | Jan 24, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [54bfedf54f](https://linux-hardware.org/?probe=54bfedf54f) | Jan 24, 2021 |
| Pegatron      | A15                         | Notebook    | [6b61b060a2](https://linux-hardware.org/?probe=6b61b060a2) | Jan 23, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [b1f5eac9a6](https://linux-hardware.org/?probe=b1f5eac9a6) | Jan 23, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [d8b9528d50](https://linux-hardware.org/?probe=d8b9528d50) | Jan 23, 2021 |
| Dell          | Latitude E6540              | Notebook    | [a68f5a5125](https://linux-hardware.org/?probe=a68f5a5125) | Jan 23, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [02ad674822](https://linux-hardware.org/?probe=02ad674822) | Jan 23, 2021 |
| MSI           | X58 Pro-E                   | Desktop     | [b5a0f60525](https://linux-hardware.org/?probe=b5a0f60525) | Jan 22, 2021 |
| ZOTAC         | ZBOX-CI620/CI640/CI660      | Mini pc     | [d391c49614](https://linux-hardware.org/?probe=d391c49614) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [c1c71784f0](https://linux-hardware.org/?probe=c1c71784f0) | Jan 22, 2021 |
| HP            | ProBook 445R G6             | Notebook    | [e5137128ac](https://linux-hardware.org/?probe=e5137128ac) | Jan 21, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [4296bcfa3c](https://linux-hardware.org/?probe=4296bcfa3c) | Jan 21, 2021 |
| Pegatron      | M2N-VM1394                  | Desktop     | [5405301d47](https://linux-hardware.org/?probe=5405301d47) | Jan 21, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [4f8794ed64](https://linux-hardware.org/?probe=4f8794ed64) | Jan 21, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [785ae57d8b](https://linux-hardware.org/?probe=785ae57d8b) | Jan 21, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [c1bf2c43e1](https://linux-hardware.org/?probe=c1bf2c43e1) | Jan 21, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [c9e8f99464](https://linux-hardware.org/?probe=c9e8f99464) | Jan 21, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [2c8605f94a](https://linux-hardware.org/?probe=2c8605f94a) | Jan 21, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [c5e2124079](https://linux-hardware.org/?probe=c5e2124079) | Jan 21, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [32878b3dae](https://linux-hardware.org/?probe=32878b3dae) | Jan 20, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [03b73f8223](https://linux-hardware.org/?probe=03b73f8223) | Jan 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [62e4ff5be8](https://linux-hardware.org/?probe=62e4ff5be8) | Jan 20, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [09f7b419ec](https://linux-hardware.org/?probe=09f7b419ec) | Jan 20, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [27383e3edf](https://linux-hardware.org/?probe=27383e3edf) | Jan 20, 2021 |
| ASUSTek       | PRIME Q270M-C               | Desktop     | [c485dcca0d](https://linux-hardware.org/?probe=c485dcca0d) | Jan 20, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [c4e5a119a6](https://linux-hardware.org/?probe=c4e5a119a6) | Jan 19, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [41ccaa294c](https://linux-hardware.org/?probe=41ccaa294c) | Jan 19, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [3a415134f0](https://linux-hardware.org/?probe=3a415134f0) | Jan 19, 2021 |
| Pegatron      | M2N-VM1394                  | Desktop     | [837561f3bf](https://linux-hardware.org/?probe=837561f3bf) | Jan 19, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [eb0f03d187](https://linux-hardware.org/?probe=eb0f03d187) | Jan 18, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [c765adbbfc](https://linux-hardware.org/?probe=c765adbbfc) | Jan 18, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [293421172c](https://linux-hardware.org/?probe=293421172c) | Jan 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [27932b28cd](https://linux-hardware.org/?probe=27932b28cd) | Jan 18, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a69f5fa59f](https://linux-hardware.org/?probe=a69f5fa59f) | Jan 17, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a2d9b3dfda](https://linux-hardware.org/?probe=a2d9b3dfda) | Jan 17, 2021 |
| HP            | EliteBook 1040 G4           | Notebook    | [b7ba6238f6](https://linux-hardware.org/?probe=b7ba6238f6) | Jan 17, 2021 |
| Lenovo        | ThinkPad X395 20NL000TCD    | Notebook    | [08990229db](https://linux-hardware.org/?probe=08990229db) | Jan 17, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [3e6aa74bb1](https://linux-hardware.org/?probe=3e6aa74bb1) | Jan 17, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [3b0c45f89b](https://linux-hardware.org/?probe=3b0c45f89b) | Jan 16, 2021 |
| ASUSTek       | UL50VT                      | Notebook    | [ca605a1715](https://linux-hardware.org/?probe=ca605a1715) | Jan 16, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [529b9189ee](https://linux-hardware.org/?probe=529b9189ee) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [866d489976](https://linux-hardware.org/?probe=866d489976) | Jan 15, 2021 |
| MSI           | MEG X299 CREATION           | Desktop     | [589f688e41](https://linux-hardware.org/?probe=589f688e41) | Jan 15, 2021 |
| Huanan        | X79 VAA1                    | Desktop     | [d88d20e6fc](https://linux-hardware.org/?probe=d88d20e6fc) | Jan 15, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [e6edb893f5](https://linux-hardware.org/?probe=e6edb893f5) | Jan 15, 2021 |
| Dell          | Latitude 5580               | Notebook    | [eba5e925b8](https://linux-hardware.org/?probe=eba5e925b8) | Jan 14, 2021 |
| MSI           | MS-7502 Fab D               | Desktop     | [3f422e0757](https://linux-hardware.org/?probe=3f422e0757) | Jan 14, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [07a2135984](https://linux-hardware.org/?probe=07a2135984) | Jan 14, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [dbfdc51ac7](https://linux-hardware.org/?probe=dbfdc51ac7) | Jan 14, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [7af78d386a](https://linux-hardware.org/?probe=7af78d386a) | Jan 14, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5aa7b5f881](https://linux-hardware.org/?probe=5aa7b5f881) | Jan 14, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [c121653064](https://linux-hardware.org/?probe=c121653064) | Jan 14, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [07bd3ed250](https://linux-hardware.org/?probe=07bd3ed250) | Jan 14, 2021 |
| Sony          | VPCEE4J1E                   | Notebook    | [d919affcfd](https://linux-hardware.org/?probe=d919affcfd) | Jan 14, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [86998ce7eb](https://linux-hardware.org/?probe=86998ce7eb) | Jan 13, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [f631333cfc](https://linux-hardware.org/?probe=f631333cfc) | Jan 13, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [a732f970ee](https://linux-hardware.org/?probe=a732f970ee) | Jan 13, 2021 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | Desktop     | [3bd076e0fa](https://linux-hardware.org/?probe=3bd076e0fa) | Jan 13, 2021 |
| Gigabyte      | G33-DS3R                    | Desktop     | [490a799d8b](https://linux-hardware.org/?probe=490a799d8b) | Jan 13, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c413917ed5](https://linux-hardware.org/?probe=c413917ed5) | Jan 13, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [9458ed8ab7](https://linux-hardware.org/?probe=9458ed8ab7) | Jan 13, 2021 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [ba007a35a6](https://linux-hardware.org/?probe=ba007a35a6) | Jan 12, 2021 |
| ASUSTek       | Berkeley                    | Desktop     | [4db5f0b0aa](https://linux-hardware.org/?probe=4db5f0b0aa) | Jan 12, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [637d6c6ea6](https://linux-hardware.org/?probe=637d6c6ea6) | Jan 11, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [49e7904b04](https://linux-hardware.org/?probe=49e7904b04) | Jan 11, 2021 |
| Lenovo        | ThinkPad T430 2347AG4       | Notebook    | [01c5b6209d](https://linux-hardware.org/?probe=01c5b6209d) | Jan 11, 2021 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [772bf2459f](https://linux-hardware.org/?probe=772bf2459f) | Jan 11, 2021 |
| HP            | 620                         | Notebook    | [23ef7f9a59](https://linux-hardware.org/?probe=23ef7f9a59) | Jan 11, 2021 |
| HP            | 620                         | Notebook    | [0a3e3591a1](https://linux-hardware.org/?probe=0a3e3591a1) | Jan 11, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [731a3aef2a](https://linux-hardware.org/?probe=731a3aef2a) | Jan 10, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [5e935457bc](https://linux-hardware.org/?probe=5e935457bc) | Jan 10, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [cc6c7e2617](https://linux-hardware.org/?probe=cc6c7e2617) | Jan 10, 2021 |
| HP            | Presario CQ57               | Notebook    | [f87fc12d71](https://linux-hardware.org/?probe=f87fc12d71) | Jan 10, 2021 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [a0041407c9](https://linux-hardware.org/?probe=a0041407c9) | Jan 09, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [224e801996](https://linux-hardware.org/?probe=224e801996) | Jan 09, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9c6ca52484](https://linux-hardware.org/?probe=9c6ca52484) | Jan 09, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [e4e57a4d65](https://linux-hardware.org/?probe=e4e57a4d65) | Jan 09, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [68910248cd](https://linux-hardware.org/?probe=68910248cd) | Jan 09, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [7fdf42857e](https://linux-hardware.org/?probe=7fdf42857e) | Jan 08, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [e1b42ecbe7](https://linux-hardware.org/?probe=e1b42ecbe7) | Jan 08, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [73f1457335](https://linux-hardware.org/?probe=73f1457335) | Jan 08, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [28aad77d5f](https://linux-hardware.org/?probe=28aad77d5f) | Jan 08, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [0d9ac8d9d9](https://linux-hardware.org/?probe=0d9ac8d9d9) | Jan 08, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [fccfe06a0d](https://linux-hardware.org/?probe=fccfe06a0d) | Jan 07, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [cccd6e2d9f](https://linux-hardware.org/?probe=cccd6e2d9f) | Jan 07, 2021 |
| HP            | 250 G3                      | Notebook    | [edc02e19eb](https://linux-hardware.org/?probe=edc02e19eb) | Jan 07, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ea9171b574](https://linux-hardware.org/?probe=ea9171b574) | Jan 07, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [235c23f313](https://linux-hardware.org/?probe=235c23f313) | Jan 07, 2021 |
| Huanan        | X99-F8                      | Desktop     | [3cf5084317](https://linux-hardware.org/?probe=3cf5084317) | Jan 07, 2021 |
| Huanan        | X99-F8                      | Desktop     | [f972c4183a](https://linux-hardware.org/?probe=f972c4183a) | Jan 07, 2021 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [c040346718](https://linux-hardware.org/?probe=c040346718) | Jan 07, 2021 |
| Lenovo        | G560e 20107                 | Notebook    | [aa92d6896e](https://linux-hardware.org/?probe=aa92d6896e) | Jan 07, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [82106ee656](https://linux-hardware.org/?probe=82106ee656) | Jan 06, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [2641a0bb89](https://linux-hardware.org/?probe=2641a0bb89) | Jan 06, 2021 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [d681950f18](https://linux-hardware.org/?probe=d681950f18) | Jan 06, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [37610922c3](https://linux-hardware.org/?probe=37610922c3) | Jan 06, 2021 |
| MSI           | B75A-G43                    | Desktop     | [23c8b4ee0a](https://linux-hardware.org/?probe=23c8b4ee0a) | Jan 06, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [ee6e390e3c](https://linux-hardware.org/?probe=ee6e390e3c) | Jan 06, 2021 |
| Digma         | ES6021EW                    | Notebook    | [27c6d34c4f](https://linux-hardware.org/?probe=27c6d34c4f) | Jan 05, 2021 |
| MSI           | B150 GAMING M3              | Desktop     | [000a2f3003](https://linux-hardware.org/?probe=000a2f3003) | Jan 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [7fa2f92090](https://linux-hardware.org/?probe=7fa2f92090) | Jan 05, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [661e288faf](https://linux-hardware.org/?probe=661e288faf) | Jan 05, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [c5fba295b9](https://linux-hardware.org/?probe=c5fba295b9) | Jan 05, 2021 |
| Intel         | NUC6CAYB J23203-404         | Mini pc     | [b4a706ae2b](https://linux-hardware.org/?probe=b4a706ae2b) | Jan 05, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [7933d453a8](https://linux-hardware.org/?probe=7933d453a8) | Jan 05, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1a2f4429b1](https://linux-hardware.org/?probe=1a2f4429b1) | Jan 05, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [8b9b10b481](https://linux-hardware.org/?probe=8b9b10b481) | Jan 04, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [800f790c23](https://linux-hardware.org/?probe=800f790c23) | Jan 04, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [fe678ae6f5](https://linux-hardware.org/?probe=fe678ae6f5) | Jan 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [e6886a3a33](https://linux-hardware.org/?probe=e6886a3a33) | Jan 04, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [1394b7fb3a](https://linux-hardware.org/?probe=1394b7fb3a) | Jan 04, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [64a44bf1e6](https://linux-hardware.org/?probe=64a44bf1e6) | Jan 04, 2021 |
| ASUSTek       | U56E                        | Notebook    | [eba46128ee](https://linux-hardware.org/?probe=eba46128ee) | Jan 04, 2021 |
| Alienware     | 0T76PD A01                  | Desktop     | [453a903a3b](https://linux-hardware.org/?probe=453a903a3b) | Jan 03, 2021 |
| Lenovo        | ThinkPad E480 20KN005CRT    | Notebook    | [7334ac7f2d](https://linux-hardware.org/?probe=7334ac7f2d) | Jan 03, 2021 |
| ASRock        | 775Dual-VSTA                | Desktop     | [e45a885545](https://linux-hardware.org/?probe=e45a885545) | Jan 03, 2021 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [ed3e0a5fd2](https://linux-hardware.org/?probe=ed3e0a5fd2) | Jan 03, 2021 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [d243e287ce](https://linux-hardware.org/?probe=d243e287ce) | Jan 03, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [aab465bdfd](https://linux-hardware.org/?probe=aab465bdfd) | Jan 03, 2021 |
| ASUSTek       | Z9PR-D12 Series             | Server      | [6acbf140d4](https://linux-hardware.org/?probe=6acbf140d4) | Jan 03, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [b4f32eead2](https://linux-hardware.org/?probe=b4f32eead2) | Jan 03, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [d4b2a29860](https://linux-hardware.org/?probe=d4b2a29860) | Jan 03, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [e50e81e73a](https://linux-hardware.org/?probe=e50e81e73a) | Jan 03, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [7b4723037b](https://linux-hardware.org/?probe=7b4723037b) | Jan 03, 2021 |
| Alienware     | M11x                        | Notebook    | [a71a5056f6](https://linux-hardware.org/?probe=a71a5056f6) | Jan 03, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [1d22a8d70a](https://linux-hardware.org/?probe=1d22a8d70a) | Jan 03, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [cf19e9b8ee](https://linux-hardware.org/?probe=cf19e9b8ee) | Jan 03, 2021 |
| HP            | Spectre XT Ultrabook PC     | Notebook    | [df1b5ae83a](https://linux-hardware.org/?probe=df1b5ae83a) | Jan 02, 2021 |
| PEAQ          | PMM C1010-I01NL MD99337     | Notebook    | [33f6e6e450](https://linux-hardware.org/?probe=33f6e6e450) | Jan 02, 2021 |
| MSI           | H310M PRO-M2                | Desktop     | [d3ae82193a](https://linux-hardware.org/?probe=d3ae82193a) | Jan 02, 2021 |
| ASUSTek       | X555QG                      | Notebook    | [801defb54c](https://linux-hardware.org/?probe=801defb54c) | Jan 02, 2021 |
| HUAWEI        | MRC-WX0                     | Notebook    | [f650998a3d](https://linux-hardware.org/?probe=f650998a3d) | Jan 02, 2021 |
| ASRock        | 775Dual-VSTA                | Desktop     | [6b49796eee](https://linux-hardware.org/?probe=6b49796eee) | Jan 02, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [630c70d8c6](https://linux-hardware.org/?probe=630c70d8c6) | Jan 01, 2021 |
| ZOTAC         | ZBOX-CI620/CI640/CI660      | Mini pc     | [e0c5fe36c4](https://linux-hardware.org/?probe=e0c5fe36c4) | Jan 01, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [bd23fb61ad](https://linux-hardware.org/?probe=bd23fb61ad) | Jan 01, 2021 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [3656c88417](https://linux-hardware.org/?probe=3656c88417) | Jan 01, 2021 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [b2b1e214c2](https://linux-hardware.org/?probe=b2b1e214c2) | Jan 01, 2021 |
| HP            | Notebook                    | Notebook    | [f35ecfc673](https://linux-hardware.org/?probe=f35ecfc673) | Dec 31, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [6fddc5c5e3](https://linux-hardware.org/?probe=6fddc5c5e3) | Dec 31, 2020 |
| Packard Be... | WMCP78M                     | Desktop     | [6a6c4577d4](https://linux-hardware.org/?probe=6a6c4577d4) | Dec 31, 2020 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [d31654b018](https://linux-hardware.org/?probe=d31654b018) | Dec 31, 2020 |
| ASUSTek       | Z8PE-D18                    | Desktop     | [d3f825998d](https://linux-hardware.org/?probe=d3f825998d) | Dec 31, 2020 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [2c0474607a](https://linux-hardware.org/?probe=2c0474607a) | Dec 30, 2020 |
| Biostar       | TA790GXB A2+                | Desktop     | [f308fe673b](https://linux-hardware.org/?probe=f308fe673b) | Dec 30, 2020 |
| Intel         | X58M                        | Desktop     | [e0308437db](https://linux-hardware.org/?probe=e0308437db) | Dec 30, 2020 |
| ASRock        | X300M-STX                   | Desktop     | [bb19b5f213](https://linux-hardware.org/?probe=bb19b5f213) | Dec 30, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [0a0be890cf](https://linux-hardware.org/?probe=0a0be890cf) | Dec 30, 2020 |
| Dell          | 0TWFTR A01                  | All in one  | [301b4de8ea](https://linux-hardware.org/?probe=301b4de8ea) | Dec 30, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ee31e00fab](https://linux-hardware.org/?probe=ee31e00fab) | Dec 30, 2020 |
| Packard Be... | WMCP78M                     | Desktop     | [4b3d23273f](https://linux-hardware.org/?probe=4b3d23273f) | Dec 30, 2020 |
| Packard Be... | WMCP78M                     | Desktop     | [713aa810ca](https://linux-hardware.org/?probe=713aa810ca) | Dec 30, 2020 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [189b60f797](https://linux-hardware.org/?probe=189b60f797) | Dec 30, 2020 |
| ASUSTek       | P7P55D-E                    | Desktop     | [2655172fc1](https://linux-hardware.org/?probe=2655172fc1) | Dec 29, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7443ed9c8e](https://linux-hardware.org/?probe=7443ed9c8e) | Dec 29, 2020 |
| Lenovo        | Yoga 720-12IKB 81B5         | Convertible | [f6f6ae0026](https://linux-hardware.org/?probe=f6f6ae0026) | Dec 29, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [b88f5bb549](https://linux-hardware.org/?probe=b88f5bb549) | Dec 29, 2020 |
| Gigabyte      | P61-S3                      | Desktop     | [cdc3efaa7d](https://linux-hardware.org/?probe=cdc3efaa7d) | Dec 29, 2020 |
| Intel         | H110                        | Desktop     | [61d0cc0b0d](https://linux-hardware.org/?probe=61d0cc0b0d) | Dec 29, 2020 |
| MSI           | H61M-P20                    | Desktop     | [f402863234](https://linux-hardware.org/?probe=f402863234) | Dec 29, 2020 |
| Dell          | Inspiron 1525               | Notebook    | [f479bc037f](https://linux-hardware.org/?probe=f479bc037f) | Dec 29, 2020 |
| Dell          | Latitude 5285               | Notebook    | [21853e6ddd](https://linux-hardware.org/?probe=21853e6ddd) | Dec 28, 2020 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [84c045204c](https://linux-hardware.org/?probe=84c045204c) | Dec 28, 2020 |
| Gigabyte      | F2A78M-D3H                  | Desktop     | [6fd8b79bab](https://linux-hardware.org/?probe=6fd8b79bab) | Dec 28, 2020 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [cb411462ef](https://linux-hardware.org/?probe=cb411462ef) | Dec 28, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cc4041e701](https://linux-hardware.org/?probe=cc4041e701) | Dec 28, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [095b9feabe](https://linux-hardware.org/?probe=095b9feabe) | Dec 28, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [7ccb916116](https://linux-hardware.org/?probe=7ccb916116) | Dec 28, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0130... | Notebook    | [1967b969bb](https://linux-hardware.org/?probe=1967b969bb) | Dec 28, 2020 |
| Gigabyte      | F2A78M-D3H                  | Desktop     | [2c09875054](https://linux-hardware.org/?probe=2c09875054) | Dec 28, 2020 |
| HP            | EliteBook x360 1030 G7 N... | Convertible | [b6102d6b20](https://linux-hardware.org/?probe=b6102d6b20) | Dec 27, 2020 |
| ASUSTek       | Q504UA                      | Notebook    | [149ef6f418](https://linux-hardware.org/?probe=149ef6f418) | Dec 27, 2020 |
| MSI           | Z77A-G41                    | Desktop     | [171be87aa0](https://linux-hardware.org/?probe=171be87aa0) | Dec 27, 2020 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [ba4eb365bc](https://linux-hardware.org/?probe=ba4eb365bc) | Dec 27, 2020 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [b6ffae8f7a](https://linux-hardware.org/?probe=b6ffae8f7a) | Dec 27, 2020 |
| Dell          | 088DT1 A01                  | Desktop     | [ca48c20657](https://linux-hardware.org/?probe=ca48c20657) | Dec 27, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [bbd47be3f2](https://linux-hardware.org/?probe=bbd47be3f2) | Dec 27, 2020 |
| ASRock        | P67 Extreme6                | Desktop     | [276b4b3251](https://linux-hardware.org/?probe=276b4b3251) | Dec 26, 2020 |
| ASRock        | P67 Extreme6                | Desktop     | [49ac9f184b](https://linux-hardware.org/?probe=49ac9f184b) | Dec 26, 2020 |
| Acer          | Swift SF315-41              | Notebook    | [3f21e7f5a0](https://linux-hardware.org/?probe=3f21e7f5a0) | Dec 26, 2020 |
| Acer          | Swift SF315-41              | Notebook    | [95a82f9f4b](https://linux-hardware.org/?probe=95a82f9f4b) | Dec 26, 2020 |
| Unknown       | Unknown                     | Notebook    | [62790cbdae](https://linux-hardware.org/?probe=62790cbdae) | Dec 26, 2020 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [e31df74cd8](https://linux-hardware.org/?probe=e31df74cd8) | Dec 26, 2020 |
| Unknown       | Unknown                     | Notebook    | [8454591bac](https://linux-hardware.org/?probe=8454591bac) | Dec 26, 2020 |
| ASUSTek       | K72Jr                       | Notebook    | [f04420d116](https://linux-hardware.org/?probe=f04420d116) | Dec 26, 2020 |
| Lenovo        | XiaoXin Air 12 80UN         | Notebook    | [7339b28f1b](https://linux-hardware.org/?probe=7339b28f1b) | Dec 26, 2020 |
| Lenovo        | XiaoXin Air 12 80UN         | Notebook    | [06c54d29ce](https://linux-hardware.org/?probe=06c54d29ce) | Dec 26, 2020 |
| HP            | 250 G3                      | Notebook    | [8b4416f1ed](https://linux-hardware.org/?probe=8b4416f1ed) | Dec 26, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ffeaeb9e4b](https://linux-hardware.org/?probe=ffeaeb9e4b) | Dec 26, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [dcef8dba06](https://linux-hardware.org/?probe=dcef8dba06) | Dec 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [c5acd280dc](https://linux-hardware.org/?probe=c5acd280dc) | Dec 25, 2020 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [ffc5a4faa0](https://linux-hardware.org/?probe=ffc5a4faa0) | Dec 25, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e0d1e76f11](https://linux-hardware.org/?probe=e0d1e76f11) | Dec 25, 2020 |
| Notebook      | NH50_70RH                   | Notebook    | [17b9e17199](https://linux-hardware.org/?probe=17b9e17199) | Dec 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [f85418ac43](https://linux-hardware.org/?probe=f85418ac43) | Dec 25, 2020 |
| ASUSTek       | P7P55D-E                    | Desktop     | [b762dffefb](https://linux-hardware.org/?probe=b762dffefb) | Dec 25, 2020 |
| Dell          | Inspiron 7391 2n1           | Convertible | [01da85c434](https://linux-hardware.org/?probe=01da85c434) | Dec 25, 2020 |
| Dell          | Inspiron 7391 2n1           | Convertible | [597b76daa1](https://linux-hardware.org/?probe=597b76daa1) | Dec 25, 2020 |
| Dell          | XPS 15 9500                 | Notebook    | [6b93ac772c](https://linux-hardware.org/?probe=6b93ac772c) | Dec 24, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [699368b0e6](https://linux-hardware.org/?probe=699368b0e6) | Dec 24, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [76064c0c88](https://linux-hardware.org/?probe=76064c0c88) | Dec 24, 2020 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [c2463308c5](https://linux-hardware.org/?probe=c2463308c5) | Dec 24, 2020 |
| Gigabyte      | P61-S3                      | Desktop     | [f6f7612ee2](https://linux-hardware.org/?probe=f6f7612ee2) | Dec 24, 2020 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [eb82a63318](https://linux-hardware.org/?probe=eb82a63318) | Dec 24, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [b3735eac0f](https://linux-hardware.org/?probe=b3735eac0f) | Dec 24, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [16fe529b66](https://linux-hardware.org/?probe=16fe529b66) | Dec 24, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [80a796809e](https://linux-hardware.org/?probe=80a796809e) | Dec 24, 2020 |
| Unknown       | Unknown                     | Desktop     | [c7f8e64bdf](https://linux-hardware.org/?probe=c7f8e64bdf) | Dec 24, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [1035c22955](https://linux-hardware.org/?probe=1035c22955) | Dec 23, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [1869efd485](https://linux-hardware.org/?probe=1869efd485) | Dec 23, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ba557d3a92](https://linux-hardware.org/?probe=ba557d3a92) | Dec 23, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f10fd9d89d](https://linux-hardware.org/?probe=f10fd9d89d) | Dec 23, 2020 |
| Dell          | G3 3590                     | Notebook    | [8e2ea96507](https://linux-hardware.org/?probe=8e2ea96507) | Dec 23, 2020 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [191e84568a](https://linux-hardware.org/?probe=191e84568a) | Dec 22, 2020 |
| MSI           | MS-7388                     | Desktop     | [2470f3c112](https://linux-hardware.org/?probe=2470f3c112) | Dec 22, 2020 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [a97071fcf0](https://linux-hardware.org/?probe=a97071fcf0) | Dec 22, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [87ecbeb3f9](https://linux-hardware.org/?probe=87ecbeb3f9) | Dec 22, 2020 |
| Lenovo        | ThinkPad E14 20RA004YUS     | Notebook    | [2f37bf84f5](https://linux-hardware.org/?probe=2f37bf84f5) | Dec 22, 2020 |
| Dell          | Latitude E6430              | Notebook    | [ff1b9b54b8](https://linux-hardware.org/?probe=ff1b9b54b8) | Dec 21, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [da7a49d389](https://linux-hardware.org/?probe=da7a49d389) | Dec 21, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [991d88e936](https://linux-hardware.org/?probe=991d88e936) | Dec 21, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [f5320272b1](https://linux-hardware.org/?probe=f5320272b1) | Dec 21, 2020 |
| Acer          | Aspire A515-44G             | Notebook    | [eb2ec87de1](https://linux-hardware.org/?probe=eb2ec87de1) | Dec 20, 2020 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [6af7f81ca3](https://linux-hardware.org/?probe=6af7f81ca3) | Dec 20, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [f5e5aaee76](https://linux-hardware.org/?probe=f5e5aaee76) | Dec 20, 2020 |
| Dell          | Latitude E4310              | Notebook    | [117c76c2f6](https://linux-hardware.org/?probe=117c76c2f6) | Dec 20, 2020 |
| HP            | 2000                        | Notebook    | [ee3b1aef4e](https://linux-hardware.org/?probe=ee3b1aef4e) | Dec 20, 2020 |
| Notebook      | W51XTU V1.0                 | Notebook    | [ea92a34511](https://linux-hardware.org/?probe=ea92a34511) | Dec 19, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [263df4fa91](https://linux-hardware.org/?probe=263df4fa91) | Dec 19, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [244e92ab75](https://linux-hardware.org/?probe=244e92ab75) | Dec 19, 2020 |
| Dell          | G3 3590                     | Notebook    | [28827b7522](https://linux-hardware.org/?probe=28827b7522) | Dec 19, 2020 |
| ASRock        | P55 Pro                     | Desktop     | [2c93457122](https://linux-hardware.org/?probe=2c93457122) | Dec 18, 2020 |
| Intel         | DG33FB AAD81072-303         | Desktop     | [fd86dcc178](https://linux-hardware.org/?probe=fd86dcc178) | Dec 18, 2020 |
| Dell          | G3 3590                     | Notebook    | [c61531cd2c](https://linux-hardware.org/?probe=c61531cd2c) | Dec 18, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [0f2eefc2e9](https://linux-hardware.org/?probe=0f2eefc2e9) | Dec 18, 2020 |
| Dell          | Latitude 3400               | Notebook    | [9e4d883b87](https://linux-hardware.org/?probe=9e4d883b87) | Dec 17, 2020 |
| Apple         | MacBookAir4,2               | Notebook    | [eca1e345b0](https://linux-hardware.org/?probe=eca1e345b0) | Dec 17, 2020 |
| Dell          | Latitude 7390               | Notebook    | [0d5f4826a2](https://linux-hardware.org/?probe=0d5f4826a2) | Dec 16, 2020 |
| HP            | ProBook 4540s               | Notebook    | [7f0de14d6d](https://linux-hardware.org/?probe=7f0de14d6d) | Dec 16, 2020 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [3b024af75b](https://linux-hardware.org/?probe=3b024af75b) | Dec 16, 2020 |
| Dell          | Latitude 7300               | Notebook    | [07ee4ec79c](https://linux-hardware.org/?probe=07ee4ec79c) | Dec 16, 2020 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e7d015bde4](https://linux-hardware.org/?probe=e7d015bde4) | Dec 16, 2020 |
| Dell          | Inspiron 5458               | Notebook    | [ba9b8c33be](https://linux-hardware.org/?probe=ba9b8c33be) | Dec 16, 2020 |
| Acer          | Gateway NE46Rs              | Notebook    | [b04f216a38](https://linux-hardware.org/?probe=b04f216a38) | Dec 15, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [0caaf0f2b5](https://linux-hardware.org/?probe=0caaf0f2b5) | Dec 15, 2020 |
| Lenovo        | ThinkPad T440s 20ARS1NS0... | Notebook    | [ad4a04d064](https://linux-hardware.org/?probe=ad4a04d064) | Dec 14, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [40db30ed00](https://linux-hardware.org/?probe=40db30ed00) | Dec 14, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [5a98d5a754](https://linux-hardware.org/?probe=5a98d5a754) | Dec 14, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [da5b8f33d0](https://linux-hardware.org/?probe=da5b8f33d0) | Dec 14, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2711b7a9b7](https://linux-hardware.org/?probe=2711b7a9b7) | Dec 13, 2020 |
| Dell          | 0478VN A00                  | Desktop     | [d8b7b22f85](https://linux-hardware.org/?probe=d8b7b22f85) | Dec 13, 2020 |
| BESSTAR Te... | AB1A                        | Mini pc     | [699b06c357](https://linux-hardware.org/?probe=699b06c357) | Dec 13, 2020 |
| Samsung       | R540/R580/R780/SA41/E452... | Notebook    | [3046fb7580](https://linux-hardware.org/?probe=3046fb7580) | Dec 13, 2020 |
| Gigabyte      | M68M-S2                     | Desktop     | [2aa18660c1](https://linux-hardware.org/?probe=2aa18660c1) | Dec 13, 2020 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [189ec9e1a2](https://linux-hardware.org/?probe=189ec9e1a2) | Dec 12, 2020 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [5885335d44](https://linux-hardware.org/?probe=5885335d44) | Dec 12, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [7aea4d859f](https://linux-hardware.org/?probe=7aea4d859f) | Dec 12, 2020 |
| Lenovo        | ThinkPad E480 20KNS0JU00    | Notebook    | [f3cb796c84](https://linux-hardware.org/?probe=f3cb796c84) | Dec 12, 2020 |
| ASUSTek       | ET2400A                     | Desktop     | [053ecece20](https://linux-hardware.org/?probe=053ecece20) | Dec 12, 2020 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [bab2a69242](https://linux-hardware.org/?probe=bab2a69242) | Dec 12, 2020 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [9f69acb29e](https://linux-hardware.org/?probe=9f69acb29e) | Dec 12, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [b8d0c8158d](https://linux-hardware.org/?probe=b8d0c8158d) | Dec 12, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [348e295ea8](https://linux-hardware.org/?probe=348e295ea8) | Dec 11, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [880408fa1c](https://linux-hardware.org/?probe=880408fa1c) | Dec 11, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [8eaef1ee87](https://linux-hardware.org/?probe=8eaef1ee87) | Dec 11, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [b035fc6450](https://linux-hardware.org/?probe=b035fc6450) | Dec 11, 2020 |
| MSI           | GV62 8RE                    | Notebook    | [0f99c76a1f](https://linux-hardware.org/?probe=0f99c76a1f) | Dec 11, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2f3e3d7641](https://linux-hardware.org/?probe=2f3e3d7641) | Dec 11, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a7dd5ba89e](https://linux-hardware.org/?probe=a7dd5ba89e) | Dec 10, 2020 |
| Lenovo        | ThinkPad T400 2768CJ6       | Notebook    | [1d878eeb02](https://linux-hardware.org/?probe=1d878eeb02) | Dec 10, 2020 |
| Dell          | Latitude E6530              | Notebook    | [edc4b418f1](https://linux-hardware.org/?probe=edc4b418f1) | Dec 09, 2020 |
| Avell High... | Avell A52 LIV               | Notebook    | [1da7f21a54](https://linux-hardware.org/?probe=1da7f21a54) | Dec 09, 2020 |
| HP            | 339A                        | Desktop     | [81a0e65daf](https://linux-hardware.org/?probe=81a0e65daf) | Dec 09, 2020 |
| Acer          | Aspire A515-44              | Notebook    | [5c5750eef2](https://linux-hardware.org/?probe=5c5750eef2) | Dec 09, 2020 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [27f9412b8a](https://linux-hardware.org/?probe=27f9412b8a) | Dec 08, 2020 |
| Dell          | Latitude 5401               | Notebook    | [2f4ca16020](https://linux-hardware.org/?probe=2f4ca16020) | Dec 08, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | Notebook    | [8a32a0ec2e](https://linux-hardware.org/?probe=8a32a0ec2e) | Dec 08, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | Notebook    | [318416a95a](https://linux-hardware.org/?probe=318416a95a) | Dec 08, 2020 |
| Razer         | Blade                       | Notebook    | [8bb9b715f6](https://linux-hardware.org/?probe=8bb9b715f6) | Dec 08, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [fd5f6edfb2](https://linux-hardware.org/?probe=fd5f6edfb2) | Dec 08, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [436c46dc4f](https://linux-hardware.org/?probe=436c46dc4f) | Dec 08, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [7aca37de47](https://linux-hardware.org/?probe=7aca37de47) | Dec 08, 2020 |
| Dell          | Latitude E6220              | Notebook    | [c3b3bae0fb](https://linux-hardware.org/?probe=c3b3bae0fb) | Dec 07, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [9e1974ae71](https://linux-hardware.org/?probe=9e1974ae71) | Dec 07, 2020 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [2e367ad7ca](https://linux-hardware.org/?probe=2e367ad7ca) | Dec 07, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [0db5b997da](https://linux-hardware.org/?probe=0db5b997da) | Dec 06, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [89fcced62a](https://linux-hardware.org/?probe=89fcced62a) | Dec 06, 2020 |
| Lenovo        | ThinkPad E14 20RAS0SE00     | Notebook    | [6f4a845bea](https://linux-hardware.org/?probe=6f4a845bea) | Dec 06, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [7858b282ff](https://linux-hardware.org/?probe=7858b282ff) | Dec 06, 2020 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [bfb2f3e541](https://linux-hardware.org/?probe=bfb2f3e541) | Dec 06, 2020 |
| PC Special... | GK5NR0O                     | Notebook    | [1dfbed1284](https://linux-hardware.org/?probe=1dfbed1284) | Dec 05, 2020 |
| Dell          | 09KPNV A01                  | Desktop     | [7615b677f1](https://linux-hardware.org/?probe=7615b677f1) | Dec 05, 2020 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [ab33f2f647](https://linux-hardware.org/?probe=ab33f2f647) | Dec 05, 2020 |
| MSI           | GF63 8RC                    | Notebook    | [807db9dea0](https://linux-hardware.org/?probe=807db9dea0) | Dec 05, 2020 |
| MSI           | GF63 8RC                    | Notebook    | [89656eef14](https://linux-hardware.org/?probe=89656eef14) | Dec 05, 2020 |
| Dell          | Latitude E6440              | Notebook    | [c5f71093b2](https://linux-hardware.org/?probe=c5f71093b2) | Dec 05, 2020 |
| Pegatron      | 2AB5                        | Desktop     | [070afe6a00](https://linux-hardware.org/?probe=070afe6a00) | Dec 04, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [e9fb942639](https://linux-hardware.org/?probe=e9fb942639) | Dec 04, 2020 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [a9d4fd08fb](https://linux-hardware.org/?probe=a9d4fd08fb) | Dec 04, 2020 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [1698815ca8](https://linux-hardware.org/?probe=1698815ca8) | Dec 04, 2020 |
| Dell          | 0VNP2H A02                  | Desktop     | [6e332680e5](https://linux-hardware.org/?probe=6e332680e5) | Dec 04, 2020 |
| Dell          | Inspiron 3437               | Notebook    | [a1663301b9](https://linux-hardware.org/?probe=a1663301b9) | Dec 04, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [baed8eba69](https://linux-hardware.org/?probe=baed8eba69) | Dec 04, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [3f2b0ae58b](https://linux-hardware.org/?probe=3f2b0ae58b) | Dec 04, 2020 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [57079efb76](https://linux-hardware.org/?probe=57079efb76) | Dec 04, 2020 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [0f481a1b93](https://linux-hardware.org/?probe=0f481a1b93) | Dec 04, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [38fa279b2b](https://linux-hardware.org/?probe=38fa279b2b) | Dec 04, 2020 |
| Dell          | 0CT103 A03                  | Desktop     | [8e89c2ac1c](https://linux-hardware.org/?probe=8e89c2ac1c) | Dec 04, 2020 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [14d57b951e](https://linux-hardware.org/?probe=14d57b951e) | Dec 04, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [12eca6d5e6](https://linux-hardware.org/?probe=12eca6d5e6) | Dec 03, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [3966da77f8](https://linux-hardware.org/?probe=3966da77f8) | Dec 03, 2020 |
| Lenovo        | ThinkPad W540 20BHS04K00    | Notebook    | [c429b95a44](https://linux-hardware.org/?probe=c429b95a44) | Dec 03, 2020 |
| BANGHO        | MOV                         | Notebook    | [237e3b0449](https://linux-hardware.org/?probe=237e3b0449) | Dec 03, 2020 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [17333fb7fd](https://linux-hardware.org/?probe=17333fb7fd) | Dec 03, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [841208193d](https://linux-hardware.org/?probe=841208193d) | Dec 03, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [3f285304e0](https://linux-hardware.org/?probe=3f285304e0) | Dec 03, 2020 |
| Dell          | Inspiron 3443               | Notebook    | [da0bddcec5](https://linux-hardware.org/?probe=da0bddcec5) | Dec 03, 2020 |
| Dell          | Inspiron 3443               | Notebook    | [2d72aed349](https://linux-hardware.org/?probe=2d72aed349) | Dec 03, 2020 |
| Acer          | Extensa 5620                | Notebook    | [f2087b24cf](https://linux-hardware.org/?probe=f2087b24cf) | Dec 02, 2020 |
| Dell          | Latitude 5591               | Notebook    | [43f7f0c137](https://linux-hardware.org/?probe=43f7f0c137) | Dec 02, 2020 |
| HP            | 2129                        | Desktop     | [2d6a252f42](https://linux-hardware.org/?probe=2d6a252f42) | Dec 02, 2020 |
| MSI           | NF980-G65                   | Desktop     | [905c03a3d4](https://linux-hardware.org/?probe=905c03a3d4) | Dec 02, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [62a9325cf5](https://linux-hardware.org/?probe=62a9325cf5) | Dec 02, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [ebdf15c19c](https://linux-hardware.org/?probe=ebdf15c19c) | Dec 01, 2020 |
| MSI           | B150M ECO                   | Desktop     | [e04d48b463](https://linux-hardware.org/?probe=e04d48b463) | Dec 01, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [ffd7043bc8](https://linux-hardware.org/?probe=ffd7043bc8) | Dec 01, 2020 |
| Dell          | 0R849J A01                  | Desktop     | [a9811d7fbd](https://linux-hardware.org/?probe=a9811d7fbd) | Dec 01, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [2c52f626c8](https://linux-hardware.org/?probe=2c52f626c8) | Dec 01, 2020 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [264c65947e](https://linux-hardware.org/?probe=264c65947e) | Dec 01, 2020 |
| MSI           | Z97 MPOWER                  | Desktop     | [be927dd59d](https://linux-hardware.org/?probe=be927dd59d) | Dec 01, 2020 |
| MSI           | Z97 MPOWER                  | Desktop     | [cfcbfb8f65](https://linux-hardware.org/?probe=cfcbfb8f65) | Nov 30, 2020 |
| Dell          | 0R849J A01                  | Desktop     | [024d1c547d](https://linux-hardware.org/?probe=024d1c547d) | Nov 30, 2020 |
| ZOTAC         | ZBOX-CI620/CI640/CI660      | Mini pc     | [3613c135f1](https://linux-hardware.org/?probe=3613c135f1) | Nov 30, 2020 |
| ZOTAC         | ZBOX-CI620/CI640/CI660      | Mini pc     | [39447c8f3d](https://linux-hardware.org/?probe=39447c8f3d) | Nov 30, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [533142a9d1](https://linux-hardware.org/?probe=533142a9d1) | Nov 30, 2020 |
| ASUSTek       | X555QG                      | Notebook    | [e90cdb39ef](https://linux-hardware.org/?probe=e90cdb39ef) | Nov 30, 2020 |
| Lenovo        | ThinkPad T440 20B7004KUS    | Notebook    | [1f8016d112](https://linux-hardware.org/?probe=1f8016d112) | Nov 30, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [78cf05bb96](https://linux-hardware.org/?probe=78cf05bb96) | Nov 29, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [cedd6ad29f](https://linux-hardware.org/?probe=cedd6ad29f) | Nov 29, 2020 |
| MSI           | MAG B550M MORTAR            | Desktop     | [37f28ef73f](https://linux-hardware.org/?probe=37f28ef73f) | Nov 29, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f4f3d941a0](https://linux-hardware.org/?probe=f4f3d941a0) | Nov 28, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [1b1044cc21](https://linux-hardware.org/?probe=1b1044cc21) | Nov 28, 2020 |
| MSI           | NF980-G65                   | Desktop     | [9e34262419](https://linux-hardware.org/?probe=9e34262419) | Nov 28, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [5858e130c3](https://linux-hardware.org/?probe=5858e130c3) | Nov 27, 2020 |
| MSI           | H61MA-E35                   | Desktop     | [6add96f4ac](https://linux-hardware.org/?probe=6add96f4ac) | Nov 27, 2020 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [873ae302a9](https://linux-hardware.org/?probe=873ae302a9) | Nov 27, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [8b31225bd7](https://linux-hardware.org/?probe=8b31225bd7) | Nov 27, 2020 |
| ASUSTek       | H87-PLUS                    | Desktop     | [563b11dfc7](https://linux-hardware.org/?probe=563b11dfc7) | Nov 27, 2020 |
| ASUSTek       | H87-PLUS                    | Desktop     | [7b22071212](https://linux-hardware.org/?probe=7b22071212) | Nov 27, 2020 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [d390d5e008](https://linux-hardware.org/?probe=d390d5e008) | Nov 26, 2020 |
| ASUSTek       | AM1I-A                      | Desktop     | [b3202de053](https://linux-hardware.org/?probe=b3202de053) | Nov 26, 2020 |
| Lenovo        | ThinkPad E15 20RD003JRT     | Notebook    | [698e9f1d85](https://linux-hardware.org/?probe=698e9f1d85) | Nov 25, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [e14774acd5](https://linux-hardware.org/?probe=e14774acd5) | Nov 25, 2020 |
| MSI           | MEG X570 UNIFY              | Desktop     | [a50e9bd7bb](https://linux-hardware.org/?probe=a50e9bd7bb) | Nov 25, 2020 |
| BESSTAR Te... | AB1A                        | Mini pc     | [9740b02be6](https://linux-hardware.org/?probe=9740b02be6) | Nov 25, 2020 |
| Lenovo        | ThinkPad E15 20RD003JRT     | Notebook    | [4a16873b8c](https://linux-hardware.org/?probe=4a16873b8c) | Nov 25, 2020 |
| ZOTAC         | ZBOX-MI525                  | Mini pc     | [e8be53afa7](https://linux-hardware.org/?probe=e8be53afa7) | Nov 25, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [bd5ed920b4](https://linux-hardware.org/?probe=bd5ed920b4) | Nov 24, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [5621028ebe](https://linux-hardware.org/?probe=5621028ebe) | Nov 24, 2020 |
| Acer          | Swift SF315-41              | Notebook    | [f5235ca11f](https://linux-hardware.org/?probe=f5235ca11f) | Nov 24, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [c433b6c798](https://linux-hardware.org/?probe=c433b6c798) | Nov 24, 2020 |
| Foxconn       | 945 7MD Series              | Desktop     | [65d7b7ad14](https://linux-hardware.org/?probe=65d7b7ad14) | Nov 23, 2020 |
| Fujitsu Si... | P5GD1-FM                    | Desktop     | [8473e30bdd](https://linux-hardware.org/?probe=8473e30bdd) | Nov 23, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4cb05b8053](https://linux-hardware.org/?probe=4cb05b8053) | Nov 23, 2020 |
| Dell          | Latitude E7270              | Notebook    | [bd99a0a889](https://linux-hardware.org/?probe=bd99a0a889) | Nov 23, 2020 |
| Dell          | Latitude E7270              | Notebook    | [8352753e5c](https://linux-hardware.org/?probe=8352753e5c) | Nov 23, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [44e261602f](https://linux-hardware.org/?probe=44e261602f) | Nov 22, 2020 |
| HP            | ProBook 470 G5              | Notebook    | [dbf4f96761](https://linux-hardware.org/?probe=dbf4f96761) | Nov 22, 2020 |
| ECS           | GeForce6100PM-M2            | Desktop     | [ff1cc0b0b7](https://linux-hardware.org/?probe=ff1cc0b0b7) | Nov 21, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [5b7b91dcd9](https://linux-hardware.org/?probe=5b7b91dcd9) | Nov 21, 2020 |
| ASUSTek       | X550LC                      | Notebook    | [e52b728376](https://linux-hardware.org/?probe=e52b728376) | Nov 21, 2020 |
| BANGHO        | MOV                         | Notebook    | [466365322d](https://linux-hardware.org/?probe=466365322d) | Nov 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [baae1bd1ef](https://linux-hardware.org/?probe=baae1bd1ef) | Nov 20, 2020 |
| MSI           | B360M Xtreme                | Desktop     | [68ebbb560b](https://linux-hardware.org/?probe=68ebbb560b) | Nov 20, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [b03cd88c60](https://linux-hardware.org/?probe=b03cd88c60) | Nov 20, 2020 |
| Acer          | NG-VX5-591G-52AT            | Notebook    | [304a828df3](https://linux-hardware.org/?probe=304a828df3) | Nov 20, 2020 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [7459ea254f](https://linux-hardware.org/?probe=7459ea254f) | Nov 20, 2020 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [ccd5e2e9b7](https://linux-hardware.org/?probe=ccd5e2e9b7) | Nov 20, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [f352d26452](https://linux-hardware.org/?probe=f352d26452) | Nov 20, 2020 |
| HP            | ProBook 455R G6             | Notebook    | [6768a1ee64](https://linux-hardware.org/?probe=6768a1ee64) | Nov 20, 2020 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [53383e710a](https://linux-hardware.org/?probe=53383e710a) | Nov 20, 2020 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [fd35bfd2d5](https://linux-hardware.org/?probe=fd35bfd2d5) | Nov 19, 2020 |
| Dell          | Inspiron 3443               | Notebook    | [d4740015ec](https://linux-hardware.org/?probe=d4740015ec) | Nov 19, 2020 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [6e86841e74](https://linux-hardware.org/?probe=6e86841e74) | Nov 19, 2020 |
| Dell          | 048DY8 A01                  | Desktop     | [206fc66c5c](https://linux-hardware.org/?probe=206fc66c5c) | Nov 19, 2020 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [54a29849d1](https://linux-hardware.org/?probe=54a29849d1) | Nov 19, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [490fa38293](https://linux-hardware.org/?probe=490fa38293) | Nov 19, 2020 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [fabdb78a80](https://linux-hardware.org/?probe=fabdb78a80) | Nov 19, 2020 |
| Lenovo        | B560 43308JG                | Notebook    | [a3bc47eb68](https://linux-hardware.org/?probe=a3bc47eb68) | Nov 18, 2020 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | Desktop     | [8b1f5d16fc](https://linux-hardware.org/?probe=8b1f5d16fc) | Nov 18, 2020 |
| Dell          | Inspiron 5577               | Notebook    | [efb6f602ba](https://linux-hardware.org/?probe=efb6f602ba) | Nov 18, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [c8af4ac482](https://linux-hardware.org/?probe=c8af4ac482) | Nov 18, 2020 |
| Dell          | Latitude E6530              | Notebook    | [efeaeed22a](https://linux-hardware.org/?probe=efeaeed22a) | Nov 18, 2020 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [feeec7a1c6](https://linux-hardware.org/?probe=feeec7a1c6) | Nov 18, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [2eca85f866](https://linux-hardware.org/?probe=2eca85f866) | Nov 18, 2020 |
| Lenovo        | ThinkPad E580 20KS001JPB    | Notebook    | [4eebd2d296](https://linux-hardware.org/?probe=4eebd2d296) | Nov 17, 2020 |
| Lenovo        | ThinkPad E580 20KS001JPB    | Notebook    | [081d245fc7](https://linux-hardware.org/?probe=081d245fc7) | Nov 17, 2020 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [7264b1c132](https://linux-hardware.org/?probe=7264b1c132) | Nov 17, 2020 |
| Biostar       | B350GT3                     | Desktop     | [35a9330750](https://linux-hardware.org/?probe=35a9330750) | Nov 17, 2020 |
| Biostar       | B350GT3                     | Desktop     | [2f41a7e32d](https://linux-hardware.org/?probe=2f41a7e32d) | Nov 17, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [2a743b7c68](https://linux-hardware.org/?probe=2a743b7c68) | Nov 17, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [907aebb56a](https://linux-hardware.org/?probe=907aebb56a) | Nov 16, 2020 |
| MSI           | MEG X570 ACE                | Desktop     | [df9073af0d](https://linux-hardware.org/?probe=df9073af0d) | Nov 16, 2020 |
| MSI           | B75A-G43                    | Desktop     | [3674b1e802](https://linux-hardware.org/?probe=3674b1e802) | Nov 16, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3d65def3ce](https://linux-hardware.org/?probe=3d65def3ce) | Nov 16, 2020 |
| Dell          | Latitude E6430              | Notebook    | [4cbfa4d98e](https://linux-hardware.org/?probe=4cbfa4d98e) | Nov 16, 2020 |
| MSI           | B75A-G43                    | Desktop     | [5f68cce112](https://linux-hardware.org/?probe=5f68cce112) | Nov 16, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a3c484b8ee](https://linux-hardware.org/?probe=a3c484b8ee) | Nov 16, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [2787eac1ff](https://linux-hardware.org/?probe=2787eac1ff) | Nov 15, 2020 |
| Fujitsu Si... | D2724-A1 S26361-D2724-A1    | Desktop     | [13e1369910](https://linux-hardware.org/?probe=13e1369910) | Nov 15, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [401a871151](https://linux-hardware.org/?probe=401a871151) | Nov 15, 2020 |
| Fujitsu Si... | D2724-A1 S26361-D2724-A1    | Desktop     | [b1f9452aba](https://linux-hardware.org/?probe=b1f9452aba) | Nov 15, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [bdb4536081](https://linux-hardware.org/?probe=bdb4536081) | Nov 15, 2020 |
| Dell          | 0478VN A00                  | Desktop     | [38009ac448](https://linux-hardware.org/?probe=38009ac448) | Nov 15, 2020 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [50cab28a32](https://linux-hardware.org/?probe=50cab28a32) | Nov 14, 2020 |
| Toshiba       | Satellite Pro L830          | Notebook    | [97a68dd7c5](https://linux-hardware.org/?probe=97a68dd7c5) | Nov 14, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ff4800db40](https://linux-hardware.org/?probe=ff4800db40) | Nov 12, 2020 |
| MSI           | B85-G41 PC Mate             | Desktop     | [37775c5053](https://linux-hardware.org/?probe=37775c5053) | Nov 12, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [95552a49fe](https://linux-hardware.org/?probe=95552a49fe) | Nov 12, 2020 |
| ASRock        | P55 Pro/USB3                | Desktop     | [c6d943db90](https://linux-hardware.org/?probe=c6d943db90) | Nov 12, 2020 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [310425e23b](https://linux-hardware.org/?probe=310425e23b) | Nov 12, 2020 |
| Lenovo        | ThinkPad E590 20NCS02G00    | Notebook    | [75eb8d58f3](https://linux-hardware.org/?probe=75eb8d58f3) | Nov 12, 2020 |
| ASUSTek       | A88XM-E                     | Desktop     | [52b7c8a912](https://linux-hardware.org/?probe=52b7c8a912) | Nov 12, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [08124a672d](https://linux-hardware.org/?probe=08124a672d) | Nov 12, 2020 |
| Acer          | Swift SF315-41              | Notebook    | [43d05784be](https://linux-hardware.org/?probe=43d05784be) | Nov 12, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [72e0270e6d](https://linux-hardware.org/?probe=72e0270e6d) | Nov 11, 2020 |
| Lenovo        | ThinkPad E590 20NCS02G00    | Notebook    | [11b7c15e41](https://linux-hardware.org/?probe=11b7c15e41) | Nov 11, 2020 |
| ASUSTek       | PN62                        | Mini pc     | [945c5cadf4](https://linux-hardware.org/?probe=945c5cadf4) | Nov 11, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [415a886136](https://linux-hardware.org/?probe=415a886136) | Nov 10, 2020 |
| ASUSTek       | N752VX                      | Notebook    | [0f1745c7fe](https://linux-hardware.org/?probe=0f1745c7fe) | Nov 10, 2020 |
| Acer          | Swift SF314-56              | Notebook    | [0a2c9a74a4](https://linux-hardware.org/?probe=0a2c9a74a4) | Nov 10, 2020 |
| Dell          | 0M3918                      | Desktop     | [1ae4feee32](https://linux-hardware.org/?probe=1ae4feee32) | Nov 10, 2020 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [ddc4a811c7](https://linux-hardware.org/?probe=ddc4a811c7) | Nov 10, 2020 |
| ASUSTek       | PN62                        | Mini pc     | [82ddcf65c3](https://linux-hardware.org/?probe=82ddcf65c3) | Nov 09, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [2430581ede](https://linux-hardware.org/?probe=2430581ede) | Nov 09, 2020 |
| ASUSTek       | P9X79 LE                    | Desktop     | [535bb960c8](https://linux-hardware.org/?probe=535bb960c8) | Nov 09, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [981f77fdb0](https://linux-hardware.org/?probe=981f77fdb0) | Nov 09, 2020 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [579f942204](https://linux-hardware.org/?probe=579f942204) | Nov 09, 2020 |
| HP            | Falco                       | Notebook    | [8a99b7cddd](https://linux-hardware.org/?probe=8a99b7cddd) | Nov 09, 2020 |
| ASUSTek       | A55BM-K                     | Desktop     | [bff939ac49](https://linux-hardware.org/?probe=bff939ac49) | Nov 09, 2020 |
| Dell          | Inspiron 5423               | Notebook    | [b3d994d481](https://linux-hardware.org/?probe=b3d994d481) | Nov 08, 2020 |
| ASRock        | N68-S3 FX                   | Desktop     | [3d560dcd13](https://linux-hardware.org/?probe=3d560dcd13) | Nov 08, 2020 |
| Dell          | Latitude 3150               | Notebook    | [8b0a72e6c2](https://linux-hardware.org/?probe=8b0a72e6c2) | Nov 08, 2020 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [aa86c8b102](https://linux-hardware.org/?probe=aa86c8b102) | Nov 08, 2020 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [2846226b13](https://linux-hardware.org/?probe=2846226b13) | Nov 08, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a1f9dad859](https://linux-hardware.org/?probe=a1f9dad859) | Nov 07, 2020 |
| ASUSTek       | TP300LA                     | Notebook    | [e111d34571](https://linux-hardware.org/?probe=e111d34571) | Nov 07, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [543559dfac](https://linux-hardware.org/?probe=543559dfac) | Nov 07, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [c7b7b29a68](https://linux-hardware.org/?probe=c7b7b29a68) | Nov 07, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f78c0034e0](https://linux-hardware.org/?probe=f78c0034e0) | Nov 07, 2020 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [2e6d4602ae](https://linux-hardware.org/?probe=2e6d4602ae) | Nov 07, 2020 |
| Dell          | Latitude 3150               | Notebook    | [6b70080d16](https://linux-hardware.org/?probe=6b70080d16) | Nov 06, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [ee5fa15c46](https://linux-hardware.org/?probe=ee5fa15c46) | Nov 06, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [5e61107d5a](https://linux-hardware.org/?probe=5e61107d5a) | Nov 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [883e1baba6](https://linux-hardware.org/?probe=883e1baba6) | Nov 06, 2020 |
| ASUSTek       | M4A78T-E                    | Desktop     | [9a0e560e5b](https://linux-hardware.org/?probe=9a0e560e5b) | Nov 05, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [517f296618](https://linux-hardware.org/?probe=517f296618) | Nov 05, 2020 |
| Acer          | Swift SF514-54T             | Notebook    | [55729d8e4c](https://linux-hardware.org/?probe=55729d8e4c) | Nov 05, 2020 |
| Dell          | Latitude E6540              | Notebook    | [90caadb7ca](https://linux-hardware.org/?probe=90caadb7ca) | Nov 05, 2020 |
| Acer          | Aspire E1-731               | Notebook    | [b01d6005b4](https://linux-hardware.org/?probe=b01d6005b4) | Nov 05, 2020 |
| Dell          | 054KM3 A00                  | Desktop     | [e24f78dcc5](https://linux-hardware.org/?probe=e24f78dcc5) | Nov 05, 2020 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [2d2aeee1c2](https://linux-hardware.org/?probe=2d2aeee1c2) | Nov 05, 2020 |
| Dell          | Precision 7740              | Notebook    | [887976cf88](https://linux-hardware.org/?probe=887976cf88) | Nov 05, 2020 |
| ASUSTek       | P5QL-E                      | Desktop     | [8eae2937da](https://linux-hardware.org/?probe=8eae2937da) | Nov 05, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [ea1071debc](https://linux-hardware.org/?probe=ea1071debc) | Nov 05, 2020 |
| HP            | ProBook 6560b               | Notebook    | [1e12011c45](https://linux-hardware.org/?probe=1e12011c45) | Nov 05, 2020 |
| ASUSTek       | P8P67-M PRO                 | Desktop     | [45a8acd5b2](https://linux-hardware.org/?probe=45a8acd5b2) | Nov 05, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [e26ce61aa3](https://linux-hardware.org/?probe=e26ce61aa3) | Nov 04, 2020 |
| ASUSTek       | AM1I-A                      | Desktop     | [e524e6ba83](https://linux-hardware.org/?probe=e524e6ba83) | Nov 04, 2020 |
| Fujitsu Si... | P5GD1-FM                    | Desktop     | [71495035b8](https://linux-hardware.org/?probe=71495035b8) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [aa9c0e0e54](https://linux-hardware.org/?probe=aa9c0e0e54) | Nov 04, 2020 |
| MSI           | NF980-G65                   | Desktop     | [91f0882001](https://linux-hardware.org/?probe=91f0882001) | Nov 04, 2020 |
| HP            | Laptop 15-rb0xx             | Notebook    | [24a0812127](https://linux-hardware.org/?probe=24a0812127) | Nov 04, 2020 |
| System76      | Galago Pro                  | Notebook    | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [fa42a090b5](https://linux-hardware.org/?probe=fa42a090b5) | Nov 03, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [d65f8070e0](https://linux-hardware.org/?probe=d65f8070e0) | Nov 03, 2020 |
| Dell          | 0KWVT8 A02                  | Desktop     | [2403e6e21e](https://linux-hardware.org/?probe=2403e6e21e) | Nov 03, 2020 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [ade4a70e45](https://linux-hardware.org/?probe=ade4a70e45) | Nov 03, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [6879002942](https://linux-hardware.org/?probe=6879002942) | Nov 03, 2020 |
| Acer          | Aspire E1-522               | Notebook    | [105d49fff8](https://linux-hardware.org/?probe=105d49fff8) | Nov 03, 2020 |
| Acer          | Aspire E1-522               | Notebook    | [565e92bb38](https://linux-hardware.org/?probe=565e92bb38) | Nov 03, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [6edccaf622](https://linux-hardware.org/?probe=6edccaf622) | Nov 03, 2020 |
| Dell          | Latitude E6520              | Notebook    | [7585dcdbb1](https://linux-hardware.org/?probe=7585dcdbb1) | Nov 03, 2020 |
| HP            | 250 G3                      | Notebook    | [8f9843ca68](https://linux-hardware.org/?probe=8f9843ca68) | Nov 02, 2020 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [c0b2f5236d](https://linux-hardware.org/?probe=c0b2f5236d) | Nov 02, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [a1fd3a40e7](https://linux-hardware.org/?probe=a1fd3a40e7) | Nov 01, 2020 |
| Lenovo        | G40-30 80FY                 | Notebook    | [7bc709a3cd](https://linux-hardware.org/?probe=7bc709a3cd) | Nov 01, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [3375f7b42a](https://linux-hardware.org/?probe=3375f7b42a) | Nov 01, 2020 |
| Schenker      | SCHENKER SLIM15 SSL15L19    | Notebook    | [fa9a4ec7af](https://linux-hardware.org/?probe=fa9a4ec7af) | Oct 31, 2020 |
| Notebook      | Titanium B155 MAX           | Notebook    | [9e5524a702](https://linux-hardware.org/?probe=9e5524a702) | Oct 31, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [58312aac21](https://linux-hardware.org/?probe=58312aac21) | Oct 31, 2020 |
| HUAWEI        | MRC-WX0                     | Notebook    | [57608acdc4](https://linux-hardware.org/?probe=57608acdc4) | Oct 31, 2020 |
| MSI           | X370 GAMING PLUS            | Desktop     | [bc7b255540](https://linux-hardware.org/?probe=bc7b255540) | Oct 31, 2020 |
| HP            | 1497                        | Desktop     | [522b4035a5](https://linux-hardware.org/?probe=522b4035a5) | Oct 31, 2020 |
| ASRock        | Z170 OC Formula             | Desktop     | [067d0719a1](https://linux-hardware.org/?probe=067d0719a1) | Oct 30, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [81d71d0c66](https://linux-hardware.org/?probe=81d71d0c66) | Oct 30, 2020 |
| Packard Be... | Veriton M275                | Desktop     | [0d3ab22c33](https://linux-hardware.org/?probe=0d3ab22c33) | Oct 30, 2020 |
| ASUSTek       | N551JM                      | Notebook    | [272cf23c9b](https://linux-hardware.org/?probe=272cf23c9b) | Oct 30, 2020 |
| ASUSTek       | N551JM                      | Notebook    | [f6c7f8b1e2](https://linux-hardware.org/?probe=f6c7f8b1e2) | Oct 30, 2020 |
| Dell          | Precision 5540              | Notebook    | [5b3140e7e8](https://linux-hardware.org/?probe=5b3140e7e8) | Oct 29, 2020 |
| Lenovo        | ThinkPad X240 20AMS1D10C    | Notebook    | [ca9137f2cc](https://linux-hardware.org/?probe=ca9137f2cc) | Oct 29, 2020 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [08b544552e](https://linux-hardware.org/?probe=08b544552e) | Oct 29, 2020 |
| Samsung       | 940Z5L                      | Notebook    | [6f6b5fc7b0](https://linux-hardware.org/?probe=6f6b5fc7b0) | Oct 29, 2020 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [5d99acdf08](https://linux-hardware.org/?probe=5d99acdf08) | Oct 29, 2020 |
| Packard Be... | EasyNote ML65               | Notebook    | [7817bf7259](https://linux-hardware.org/?probe=7817bf7259) | Oct 29, 2020 |
| MSI           | Z270 SLI                    | Desktop     | [f8adb0fcd7](https://linux-hardware.org/?probe=f8adb0fcd7) | Oct 29, 2020 |
| Avell High... | 1513                        | Notebook    | [e096bbb333](https://linux-hardware.org/?probe=e096bbb333) | Oct 29, 2020 |
| Acer          | Extensa 5620                | Notebook    | [e7fab7440e](https://linux-hardware.org/?probe=e7fab7440e) | Oct 29, 2020 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [fb8d81c3d7](https://linux-hardware.org/?probe=fb8d81c3d7) | Oct 29, 2020 |
| Dell          | 0X75JG A00                  | Desktop     | [b984a93bcc](https://linux-hardware.org/?probe=b984a93bcc) | Oct 29, 2020 |
| MSI           | X370 GAMING PLUS            | Desktop     | [f69288c298](https://linux-hardware.org/?probe=f69288c298) | Oct 28, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [3f18f3f21e](https://linux-hardware.org/?probe=3f18f3f21e) | Oct 28, 2020 |
| Teclast       | F6 Pro                      | Notebook    | [968c4a4b44](https://linux-hardware.org/?probe=968c4a4b44) | Oct 28, 2020 |
| Unknown       | Unknown                     | Notebook    | [bc4aa886d3](https://linux-hardware.org/?probe=bc4aa886d3) | Oct 28, 2020 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [2c380693bb](https://linux-hardware.org/?probe=2c380693bb) | Oct 28, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [68232dd449](https://linux-hardware.org/?probe=68232dd449) | Oct 28, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [1b94400f00](https://linux-hardware.org/?probe=1b94400f00) | Oct 28, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [e318eef11b](https://linux-hardware.org/?probe=e318eef11b) | Oct 28, 2020 |
| Fujitsu Si... | P5GD1-FM                    | Desktop     | [bae48146c3](https://linux-hardware.org/?probe=bae48146c3) | Oct 28, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [eda9a94c60](https://linux-hardware.org/?probe=eda9a94c60) | Oct 28, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [fa214e5217](https://linux-hardware.org/?probe=fa214e5217) | Oct 28, 2020 |
| ASRock        | Z87E-ITX                    | Desktop     | [dbb5f050b6](https://linux-hardware.org/?probe=dbb5f050b6) | Oct 28, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [580695e51d](https://linux-hardware.org/?probe=580695e51d) | Oct 27, 2020 |
| Foxconn       | 2AB1                        | Desktop     | [abc0471a17](https://linux-hardware.org/?probe=abc0471a17) | Oct 27, 2020 |
| HP            | 3047h                       | Desktop     | [a23efe0e20](https://linux-hardware.org/?probe=a23efe0e20) | Oct 26, 2020 |
| Dell          | 0KWVT8 A02                  | Desktop     | [6067b5fdca](https://linux-hardware.org/?probe=6067b5fdca) | Oct 26, 2020 |
| MSI           | H97 PC Mate                 | Desktop     | [7d2833c2f9](https://linux-hardware.org/?probe=7d2833c2f9) | Oct 25, 2020 |
| Dell          | Latitude E6430              | Notebook    | [fa72b037f5](https://linux-hardware.org/?probe=fa72b037f5) | Oct 25, 2020 |
| ASUSTek       | K53SJ                       | Notebook    | [9b2c191205](https://linux-hardware.org/?probe=9b2c191205) | Oct 25, 2020 |
| Acer          | Aspire E5-553G              | Notebook    | [57853d6509](https://linux-hardware.org/?probe=57853d6509) | Oct 25, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [f484441baf](https://linux-hardware.org/?probe=f484441baf) | Oct 25, 2020 |
| Lenovo        | G780 20138                  | Notebook    | [5dd91534ec](https://linux-hardware.org/?probe=5dd91534ec) | Oct 25, 2020 |
| Dell          | 03NVJ6 A01                  | Desktop     | [10f9e6c3d8](https://linux-hardware.org/?probe=10f9e6c3d8) | Oct 25, 2020 |
| Dell          | Latitude E6400              | Notebook    | [7716757d6d](https://linux-hardware.org/?probe=7716757d6d) | Oct 24, 2020 |
| Lenovo        | 3706 SDK0J40700 WIN 3258... | Desktop     | [d19a6fb1ad](https://linux-hardware.org/?probe=d19a6fb1ad) | Oct 24, 2020 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [7e20defaed](https://linux-hardware.org/?probe=7e20defaed) | Oct 24, 2020 |
| Complet       | MY8307                      | Tablet      | [cdc4024687](https://linux-hardware.org/?probe=cdc4024687) | Oct 24, 2020 |
| MSI           | NF980-G65                   | Desktop     | [b37787e43b](https://linux-hardware.org/?probe=b37787e43b) | Oct 24, 2020 |
| Acer          | Aspire F5-771G              | Notebook    | [13fb7214a9](https://linux-hardware.org/?probe=13fb7214a9) | Oct 23, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [b6190da277](https://linux-hardware.org/?probe=b6190da277) | Oct 23, 2020 |
| Packard Be... | M2N-NM                      | Desktop     | [52db91efa6](https://linux-hardware.org/?probe=52db91efa6) | Oct 23, 2020 |
| Dell          | 0TWFTR A01                  | All in one  | [027019184d](https://linux-hardware.org/?probe=027019184d) | Oct 23, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [e22529c904](https://linux-hardware.org/?probe=e22529c904) | Oct 23, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [47cb21f832](https://linux-hardware.org/?probe=47cb21f832) | Oct 23, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [892b8db889](https://linux-hardware.org/?probe=892b8db889) | Oct 23, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [3dc126996a](https://linux-hardware.org/?probe=3dc126996a) | Oct 23, 2020 |
| ASUSTek       | M4A785-M                    | Desktop     | [f5739b282a](https://linux-hardware.org/?probe=f5739b282a) | Oct 23, 2020 |
| Dell          | 0XPDFK A01                  | Desktop     | [0224c9fc78](https://linux-hardware.org/?probe=0224c9fc78) | Oct 22, 2020 |
| HP            | 630                         | Notebook    | [f5e6e95546](https://linux-hardware.org/?probe=f5e6e95546) | Oct 22, 2020 |
| HP            | ZHAN 66 Pro 15 G2           | Notebook    | [adb6a00cd2](https://linux-hardware.org/?probe=adb6a00cd2) | Oct 22, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [4c38164a20](https://linux-hardware.org/?probe=4c38164a20) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [9baf706433](https://linux-hardware.org/?probe=9baf706433) | Oct 21, 2020 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [c48530abc5](https://linux-hardware.org/?probe=c48530abc5) | Oct 21, 2020 |
| Dell          | Inspiron 5521               | Notebook    | [4379ee4d7a](https://linux-hardware.org/?probe=4379ee4d7a) | Oct 21, 2020 |
| Acer          | Spin SP113-31               | Convertible | [c55fc9990d](https://linux-hardware.org/?probe=c55fc9990d) | Oct 21, 2020 |
| Dell          | 088DT1 A01                  | Desktop     | [41919737ef](https://linux-hardware.org/?probe=41919737ef) | Oct 20, 2020 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [98ab87075c](https://linux-hardware.org/?probe=98ab87075c) | Oct 18, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [2defe4758c](https://linux-hardware.org/?probe=2defe4758c) | Oct 18, 2020 |
| MSI           | Z370M MORTAR                | Desktop     | [0a86954ea1](https://linux-hardware.org/?probe=0a86954ea1) | Oct 18, 2020 |
| Acer          | Aspire F5-771G              | Notebook    | [2078fc1092](https://linux-hardware.org/?probe=2078fc1092) | Oct 18, 2020 |
| Acer          | Aspire TC-105               | Desktop     | [954d6d151c](https://linux-hardware.org/?probe=954d6d151c) | Oct 17, 2020 |
| Acer          | Aspire TC-105               | Desktop     | [4897bba76b](https://linux-hardware.org/?probe=4897bba76b) | Oct 17, 2020 |
| Acer          | Aspire XC-605               | Desktop     | [77bfaa4cf4](https://linux-hardware.org/?probe=77bfaa4cf4) | Oct 17, 2020 |
| HP            | Laptop 15-rb0xx             | Notebook    | [78b81d2179](https://linux-hardware.org/?probe=78b81d2179) | Oct 16, 2020 |
| Sony          | SVF15318SNB                 | Notebook    | [600b06bc21](https://linux-hardware.org/?probe=600b06bc21) | Oct 15, 2020 |
| Sony          | SVF15318SNB                 | Notebook    | [cd7bfa655a](https://linux-hardware.org/?probe=cd7bfa655a) | Oct 15, 2020 |
| Lenovo        | ThinkPad T440s 20ARS1NS0... | Notebook    | [7480d0534c](https://linux-hardware.org/?probe=7480d0534c) | Oct 15, 2020 |
| Pegatron      | M2N-VM1394                  | Desktop     | [1fe28c5fbb](https://linux-hardware.org/?probe=1fe28c5fbb) | Oct 15, 2020 |
| ASUSTek       | B85-PLUS                    | Desktop     | [129ccdd03b](https://linux-hardware.org/?probe=129ccdd03b) | Oct 15, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b252bc95af](https://linux-hardware.org/?probe=b252bc95af) | Oct 15, 2020 |
| ASUSTek       | U50A                        | Notebook    | [1910c8ff4a](https://linux-hardware.org/?probe=1910c8ff4a) | Oct 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c51e5d8d0c](https://linux-hardware.org/?probe=c51e5d8d0c) | Oct 14, 2020 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [248f174931](https://linux-hardware.org/?probe=248f174931) | Oct 14, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [e0f9f6a923](https://linux-hardware.org/?probe=e0f9f6a923) | Oct 14, 2020 |
| ZOTAC         | ZBOX-CI620/CI640/CI660      | Mini pc     | [c6155e13c4](https://linux-hardware.org/?probe=c6155e13c4) | Oct 14, 2020 |
| ZOTAC         | MEK Mini                    | Desktop     | [9e475e6609](https://linux-hardware.org/?probe=9e475e6609) | Oct 14, 2020 |
| Pegatron      | IPM31G                      | Desktop     | [e42252fd1c](https://linux-hardware.org/?probe=e42252fd1c) | Oct 14, 2020 |
| ASUSTek       | P5Q3                        | Desktop     | [9d6e8131e9](https://linux-hardware.org/?probe=9d6e8131e9) | Oct 14, 2020 |
| ASUSTek       | P5Q3                        | Desktop     | [35e64cec70](https://linux-hardware.org/?probe=35e64cec70) | Oct 14, 2020 |
| Pegatron      | IPM31G                      | Desktop     | [5026b30c12](https://linux-hardware.org/?probe=5026b30c12) | Oct 13, 2020 |
| Intel         | H55                         | Desktop     | [9b6779ffba](https://linux-hardware.org/?probe=9b6779ffba) | Oct 13, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c87b57ee51](https://linux-hardware.org/?probe=c87b57ee51) | Oct 13, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f788b311f5](https://linux-hardware.org/?probe=f788b311f5) | Oct 12, 2020 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [ee0649427b](https://linux-hardware.org/?probe=ee0649427b) | Oct 12, 2020 |
| Lenovo        | ThinkPad T400 7417CTO       | Notebook    | [41f5d8bbb1](https://linux-hardware.org/?probe=41f5d8bbb1) | Oct 12, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [ede21e126b](https://linux-hardware.org/?probe=ede21e126b) | Oct 12, 2020 |
| Google        | Samus                       | Notebook    | [003074f1f5](https://linux-hardware.org/?probe=003074f1f5) | Oct 12, 2020 |
| Dell          | Inspiron 5547               | Notebook    | [81ee9f01b2](https://linux-hardware.org/?probe=81ee9f01b2) | Oct 11, 2020 |
| ASRock        | AB350M-HDV R3.0             | Desktop     | [368bc3c902](https://linux-hardware.org/?probe=368bc3c902) | Oct 11, 2020 |
| HP            | Laptop 15-rb0xx             | Notebook    | [e503816bd1](https://linux-hardware.org/?probe=e503816bd1) | Oct 11, 2020 |
| Dell          | Latitude E6430              | Notebook    | [3f82283451](https://linux-hardware.org/?probe=3f82283451) | Oct 10, 2020 |
| Dell          | Precision M6600             | Notebook    | [5eab77ccc6](https://linux-hardware.org/?probe=5eab77ccc6) | Oct 10, 2020 |
| Dell          | Precision M6600             | Notebook    | [8d87679ebf](https://linux-hardware.org/?probe=8d87679ebf) | Oct 10, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [47dc69334e](https://linux-hardware.org/?probe=47dc69334e) | Oct 10, 2020 |
| Unknown       | Unknown                     | Notebook    | [787abc9835](https://linux-hardware.org/?probe=787abc9835) | Oct 10, 2020 |
| WeiBu         | WTGLKC1R120 SD-BS-CJ41G-... | Desktop     | [bf41c99f19](https://linux-hardware.org/?probe=bf41c99f19) | Oct 10, 2020 |
| Apple         | Mac-F2268CC8                | All in one  | [3d6de31d0c](https://linux-hardware.org/?probe=3d6de31d0c) | Oct 09, 2020 |
| ASUSTek       | P8Q77-M                     | Desktop     | [38d99fffea](https://linux-hardware.org/?probe=38d99fffea) | Oct 09, 2020 |
| ASUSTek       | P8Q77-M                     | Desktop     | [8e83d6783c](https://linux-hardware.org/?probe=8e83d6783c) | Oct 09, 2020 |
| Lenovo        | ThinkPad E15 20RD0011MC     | Notebook    | [726bdf3762](https://linux-hardware.org/?probe=726bdf3762) | Oct 08, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [83ae97a2cc](https://linux-hardware.org/?probe=83ae97a2cc) | Oct 08, 2020 |
| ASUSTek       | Z87-A                       | Desktop     | [7e99ba9f73](https://linux-hardware.org/?probe=7e99ba9f73) | Oct 08, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [fd6f0a34c8](https://linux-hardware.org/?probe=fd6f0a34c8) | Oct 08, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5d3f7000fa](https://linux-hardware.org/?probe=5d3f7000fa) | Oct 08, 2020 |
| Dell          | Latitude E7240              | Notebook    | [f0eed491f0](https://linux-hardware.org/?probe=f0eed491f0) | Oct 07, 2020 |
| Dell          | Inspiron 7460               | Notebook    | [8c83b04a18](https://linux-hardware.org/?probe=8c83b04a18) | Oct 07, 2020 |
| HP            | 1998                        | Desktop     | [36f71f3062](https://linux-hardware.org/?probe=36f71f3062) | Oct 07, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [8b24c24267](https://linux-hardware.org/?probe=8b24c24267) | Oct 07, 2020 |
| HP            | 15                          | Notebook    | [d9177855f2](https://linux-hardware.org/?probe=d9177855f2) | Oct 06, 2020 |
| MSI           | K9A2 Platinum               | Desktop     | [d0cdd4c83e](https://linux-hardware.org/?probe=d0cdd4c83e) | Oct 06, 2020 |
| MSI           | K9A2 Platinum               | Desktop     | [410dc6ff65](https://linux-hardware.org/?probe=410dc6ff65) | Oct 06, 2020 |
| HP            | ENVY m7 Notebook            | Notebook    | [2087443349](https://linux-hardware.org/?probe=2087443349) | Oct 06, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [39dbff3b4e](https://linux-hardware.org/?probe=39dbff3b4e) | Oct 06, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [911a69ad62](https://linux-hardware.org/?probe=911a69ad62) | Oct 06, 2020 |
| Lenovo        | IdeaPad Z460 0913           | Notebook    | [f31c3b6a1e](https://linux-hardware.org/?probe=f31c3b6a1e) | Oct 06, 2020 |
| Samsung       | N145P/N250P/N260P           | Notebook    | [167ad77b77](https://linux-hardware.org/?probe=167ad77b77) | Oct 05, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [4c45779def](https://linux-hardware.org/?probe=4c45779def) | Oct 05, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [1d28040300](https://linux-hardware.org/?probe=1d28040300) | Oct 05, 2020 |
| Lenovo        | ThinkPad L440 20ASS2JL00    | Notebook    | [f94c3aa8fd](https://linux-hardware.org/?probe=f94c3aa8fd) | Oct 05, 2020 |
| Pegatron      | 2AD5                        | Desktop     | [4d341edca9](https://linux-hardware.org/?probe=4d341edca9) | Oct 05, 2020 |
| LG Electro... | 17Z90N-V.AA85D              | Notebook    | [4cfc3f24ed](https://linux-hardware.org/?probe=4cfc3f24ed) | Oct 05, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [cf0e73081e](https://linux-hardware.org/?probe=cf0e73081e) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [fb75c1edd7](https://linux-hardware.org/?probe=fb75c1edd7) | Oct 05, 2020 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fd73b699f6](https://linux-hardware.org/?probe=fd73b699f6) | Oct 05, 2020 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [3b83599aee](https://linux-hardware.org/?probe=3b83599aee) | Oct 05, 2020 |
| HP            | Pavilion dv5                | Notebook    | [9bbeef69a8](https://linux-hardware.org/?probe=9bbeef69a8) | Oct 04, 2020 |
| Toshiba       | Satellite A200              | Notebook    | [d72bfa9a4e](https://linux-hardware.org/?probe=d72bfa9a4e) | Oct 04, 2020 |
| Apple         | MacBookPro5,1               | Notebook    | [6e37cbe673](https://linux-hardware.org/?probe=6e37cbe673) | Oct 04, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | Notebook    | [6ad4cf1872](https://linux-hardware.org/?probe=6ad4cf1872) | Oct 04, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [4544ce6b1d](https://linux-hardware.org/?probe=4544ce6b1d) | Oct 04, 2020 |
| Gigabyte      | B360M HD3                   | Desktop     | [e0aadcb07c](https://linux-hardware.org/?probe=e0aadcb07c) | Oct 04, 2020 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [02b8f545e7](https://linux-hardware.org/?probe=02b8f545e7) | Oct 03, 2020 |
| ASRock        | A300M-STX                   | Desktop     | [48d09a0a0f](https://linux-hardware.org/?probe=48d09a0a0f) | Oct 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f7cdc16947](https://linux-hardware.org/?probe=f7cdc16947) | Oct 03, 2020 |
| HP            | ProBook 650 G2              | Notebook    | [50d00d9ac8](https://linux-hardware.org/?probe=50d00d9ac8) | Oct 02, 2020 |
| ASRock        | B450 Pro4                   | Desktop     | [e7a5537652](https://linux-hardware.org/?probe=e7a5537652) | Oct 02, 2020 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [afa58777a9](https://linux-hardware.org/?probe=afa58777a9) | Oct 02, 2020 |
| Dell          | 0773VG A02                  | Desktop     | [872ea44bee](https://linux-hardware.org/?probe=872ea44bee) | Oct 02, 2020 |
| Biostar       | A320MH                      | Desktop     | [ee41403938](https://linux-hardware.org/?probe=ee41403938) | Oct 02, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fcd36c5060](https://linux-hardware.org/?probe=fcd36c5060) | Oct 02, 2020 |
| Multilaser    | PC150                       | Notebook    | [b67243c0e6](https://linux-hardware.org/?probe=b67243c0e6) | Oct 01, 2020 |
| Dell          | Latitude 5501               | Notebook    | [ef5248a72c](https://linux-hardware.org/?probe=ef5248a72c) | Oct 01, 2020 |
| Medion        | P861X                       | Notebook    | [b088ab1281](https://linux-hardware.org/?probe=b088ab1281) | Oct 01, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | Notebook    | [124d606ddd](https://linux-hardware.org/?probe=124d606ddd) | Sep 30, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [4d7b7108a7](https://linux-hardware.org/?probe=4d7b7108a7) | Sep 30, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [dc773c8027](https://linux-hardware.org/?probe=dc773c8027) | Sep 30, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [875ed73389](https://linux-hardware.org/?probe=875ed73389) | Sep 30, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [c32337249b](https://linux-hardware.org/?probe=c32337249b) | Sep 30, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [6f21834dc9](https://linux-hardware.org/?probe=6f21834dc9) | Sep 30, 2020 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [3bee2f38f1](https://linux-hardware.org/?probe=3bee2f38f1) | Sep 29, 2020 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [7478c9e282](https://linux-hardware.org/?probe=7478c9e282) | Sep 29, 2020 |
| Lenovo        | B560 43308JG                | Notebook    | [4b3226d9aa](https://linux-hardware.org/?probe=4b3226d9aa) | Sep 29, 2020 |
| WeiBu         | WTGLKC1R120 SD-BS-CJ41G-... | Desktop     | [ee0a5bb389](https://linux-hardware.org/?probe=ee0a5bb389) | Sep 29, 2020 |
| Apple         | MacBookPro14,1              | Notebook    | [b509e38dad](https://linux-hardware.org/?probe=b509e38dad) | Sep 29, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [aba0775a08](https://linux-hardware.org/?probe=aba0775a08) | Sep 29, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [47838e477e](https://linux-hardware.org/?probe=47838e477e) | Sep 29, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [44178be6cc](https://linux-hardware.org/?probe=44178be6cc) | Sep 29, 2020 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [e473000ada](https://linux-hardware.org/?probe=e473000ada) | Sep 28, 2020 |
| ASUSTek       | K75DE                       | Notebook    | [b4cb493794](https://linux-hardware.org/?probe=b4cb493794) | Sep 28, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a36b437918](https://linux-hardware.org/?probe=a36b437918) | Sep 28, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b49235a2e5](https://linux-hardware.org/?probe=b49235a2e5) | Sep 28, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [cf7fb176a2](https://linux-hardware.org/?probe=cf7fb176a2) | Sep 28, 2020 |
| MSI           | Z97A SLI Krait Edition      | Desktop     | [8204be4261](https://linux-hardware.org/?probe=8204be4261) | Sep 28, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [a0ef0c68c8](https://linux-hardware.org/?probe=a0ef0c68c8) | Sep 28, 2020 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [2000204f0c](https://linux-hardware.org/?probe=2000204f0c) | Sep 28, 2020 |
| Lenovo        | ThinkPad P53 20QN000DGE     | Notebook    | [3a0bc546cc](https://linux-hardware.org/?probe=3a0bc546cc) | Sep 28, 2020 |
| Dell          | Precision 3530              | Notebook    | [2e65c3e59b](https://linux-hardware.org/?probe=2e65c3e59b) | Sep 28, 2020 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [ea4ebc4c7c](https://linux-hardware.org/?probe=ea4ebc4c7c) | Sep 27, 2020 |
| Dell          | Latitude E6430              | Notebook    | [108cf1b876](https://linux-hardware.org/?probe=108cf1b876) | Sep 27, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9e81c4a654](https://linux-hardware.org/?probe=9e81c4a654) | Sep 27, 2020 |
| LG Electro... | 17Z90N-V.AA85D              | Notebook    | [cfa1561aff](https://linux-hardware.org/?probe=cfa1561aff) | Sep 27, 2020 |
| Unknown       | G41T-M7                     | Desktop     | [b0a1c999b5](https://linux-hardware.org/?probe=b0a1c999b5) | Sep 26, 2020 |
| ASUSTek       | K72Jr                       | Notebook    | [8acb8baa23](https://linux-hardware.org/?probe=8acb8baa23) | Sep 26, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [40ed4cc83b](https://linux-hardware.org/?probe=40ed4cc83b) | Sep 24, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8727650187](https://linux-hardware.org/?probe=8727650187) | Sep 24, 2020 |
| Dell          | 0TWFTR A01                  | All in one  | [c46c49722a](https://linux-hardware.org/?probe=c46c49722a) | Sep 24, 2020 |
| WeiBu         | WTGLKC1R120 SD-BS-CJ41G-... | Desktop     | [c42578d8e4](https://linux-hardware.org/?probe=c42578d8e4) | Sep 24, 2020 |
| Lenovo        | ThinkPad L380 20M6S24V00    | Notebook    | [5ed75210ae](https://linux-hardware.org/?probe=5ed75210ae) | Sep 24, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [9525add8b0](https://linux-hardware.org/?probe=9525add8b0) | Sep 24, 2020 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [b3089d3cb7](https://linux-hardware.org/?probe=b3089d3cb7) | Sep 24, 2020 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [d734e4f3a6](https://linux-hardware.org/?probe=d734e4f3a6) | Sep 24, 2020 |
| HP            | 1998                        | Desktop     | [4645eff9b8](https://linux-hardware.org/?probe=4645eff9b8) | Sep 23, 2020 |
| Dell          | Latitude 3450               | Notebook    | [72d34c3efc](https://linux-hardware.org/?probe=72d34c3efc) | Sep 23, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [7b7a357d96](https://linux-hardware.org/?probe=7b7a357d96) | Sep 23, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e1a432f778](https://linux-hardware.org/?probe=e1a432f778) | Sep 23, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4b03ee65ce](https://linux-hardware.org/?probe=4b03ee65ce) | Sep 23, 2020 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [4c5a166fa8](https://linux-hardware.org/?probe=4c5a166fa8) | Sep 23, 2020 |
| Foxconn       | 2AB1                        | Desktop     | [49ad44dfa5](https://linux-hardware.org/?probe=49ad44dfa5) | Sep 22, 2020 |
| ASRock        | H110M-HG4                   | Desktop     | [bf0521b64f](https://linux-hardware.org/?probe=bf0521b64f) | Sep 22, 2020 |
| Dell          | Latitude E7440              | Notebook    | [7e013a08e4](https://linux-hardware.org/?probe=7e013a08e4) | Sep 22, 2020 |
| Dell          | Latitude 3450               | Notebook    | [876bad7f61](https://linux-hardware.org/?probe=876bad7f61) | Sep 22, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [b5a412b4ae](https://linux-hardware.org/?probe=b5a412b4ae) | Sep 22, 2020 |
| Dell          | Latitude E6430              | Notebook    | [ea0ad060bb](https://linux-hardware.org/?probe=ea0ad060bb) | Sep 21, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [0c58f48e72](https://linux-hardware.org/?probe=0c58f48e72) | Sep 21, 2020 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [427512ad2d](https://linux-hardware.org/?probe=427512ad2d) | Sep 21, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [7a07706a75](https://linux-hardware.org/?probe=7a07706a75) | Sep 21, 2020 |
| Dell          | Latitude E7440              | Notebook    | [71d9192dff](https://linux-hardware.org/?probe=71d9192dff) | Sep 21, 2020 |
| Dell          | Latitude E7440              | Notebook    | [868beceb46](https://linux-hardware.org/?probe=868beceb46) | Sep 21, 2020 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [de8040f8f2](https://linux-hardware.org/?probe=de8040f8f2) | Sep 20, 2020 |
| HP            | Notebook                    | Notebook    | [07eb4784fa](https://linux-hardware.org/?probe=07eb4784fa) | Sep 20, 2020 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [69c7b645f0](https://linux-hardware.org/?probe=69c7b645f0) | Sep 20, 2020 |
| ASRock        | B450M-HDV                   | Desktop     | [18c72cc162](https://linux-hardware.org/?probe=18c72cc162) | Sep 20, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [0665343246](https://linux-hardware.org/?probe=0665343246) | Sep 20, 2020 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [da6e444e64](https://linux-hardware.org/?probe=da6e444e64) | Sep 20, 2020 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [c64e54f364](https://linux-hardware.org/?probe=c64e54f364) | Sep 20, 2020 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [df8fbe9e18](https://linux-hardware.org/?probe=df8fbe9e18) | Sep 20, 2020 |
| Koloe         | X58                         | Desktop     | [81d474ab62](https://linux-hardware.org/?probe=81d474ab62) | Sep 20, 2020 |
| Acer          | Predator G5910              | Desktop     | [7c7e146182](https://linux-hardware.org/?probe=7c7e146182) | Sep 19, 2020 |
| Pegatron      | 2AB5                        | Desktop     | [00d244942e](https://linux-hardware.org/?probe=00d244942e) | Sep 18, 2020 |
| ASUSTek       | AM1I-A                      | Desktop     | [267811706f](https://linux-hardware.org/?probe=267811706f) | Sep 18, 2020 |
| Acer          | Aspire C27-962              | All in one  | [679e8852df](https://linux-hardware.org/?probe=679e8852df) | Sep 18, 2020 |
| HP            | 1998                        | Desktop     | [4217b92c39](https://linux-hardware.org/?probe=4217b92c39) | Sep 18, 2020 |
| Apple         | Mac-F2218FA9                | All in one  | [20134e0251](https://linux-hardware.org/?probe=20134e0251) | Sep 17, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6ec343f930](https://linux-hardware.org/?probe=6ec343f930) | Sep 16, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [29e9c90535](https://linux-hardware.org/?probe=29e9c90535) | Sep 16, 2020 |
| Lenovo        | ThinkPad T490 20N2S13700    | Notebook    | [1818c8c46e](https://linux-hardware.org/?probe=1818c8c46e) | Sep 16, 2020 |
| HP            | 250 G4                      | Notebook    | [6518dd62f0](https://linux-hardware.org/?probe=6518dd62f0) | Sep 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [0cf8ee1ae8](https://linux-hardware.org/?probe=0cf8ee1ae8) | Sep 16, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [a309e5b32f](https://linux-hardware.org/?probe=a309e5b32f) | Sep 16, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [3b0cfbae5d](https://linux-hardware.org/?probe=3b0cfbae5d) | Sep 16, 2020 |
| Dell          | XPS M1530                   | Notebook    | [fee4b0a261](https://linux-hardware.org/?probe=fee4b0a261) | Sep 15, 2020 |
| Clevo         | M1110M                      | Notebook    | [c545781337](https://linux-hardware.org/?probe=c545781337) | Sep 15, 2020 |
| HP            | 245 G5 Notebook PC          | Notebook    | [d2e8cd8f97](https://linux-hardware.org/?probe=d2e8cd8f97) | Sep 15, 2020 |
| Lenovo        | U41-70                      | Notebook    | [fdb99e4db2](https://linux-hardware.org/?probe=fdb99e4db2) | Sep 15, 2020 |
| ASRock        | H110M-HG4                   | Desktop     | [354bc6411b](https://linux-hardware.org/?probe=354bc6411b) | Sep 14, 2020 |
| Gigabyte      | B550M DS3H                  | Desktop     | [b2f1c44a0a](https://linux-hardware.org/?probe=b2f1c44a0a) | Sep 14, 2020 |
| HP            | 245 G5 Notebook PC          | Notebook    | [da0f03edfc](https://linux-hardware.org/?probe=da0f03edfc) | Sep 14, 2020 |
| Toshiba       | Satellite C645              | Notebook    | [c20aac3a01](https://linux-hardware.org/?probe=c20aac3a01) | Sep 14, 2020 |
| ASRock        | H110M-HG4                   | Desktop     | [71e3809cfa](https://linux-hardware.org/?probe=71e3809cfa) | Sep 13, 2020 |
| ASRock        | H110M-HG4                   | Desktop     | [21fae97e39](https://linux-hardware.org/?probe=21fae97e39) | Sep 13, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [6c33f8ea14](https://linux-hardware.org/?probe=6c33f8ea14) | Sep 13, 2020 |
| ASUSTek       | G750JW                      | Notebook    | [7d9956c2b8](https://linux-hardware.org/?probe=7d9956c2b8) | Sep 13, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [cf7a5991ac](https://linux-hardware.org/?probe=cf7a5991ac) | Sep 13, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [3479e025dc](https://linux-hardware.org/?probe=3479e025dc) | Sep 13, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [898dca2493](https://linux-hardware.org/?probe=898dca2493) | Sep 12, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c7631d7914](https://linux-hardware.org/?probe=c7631d7914) | Sep 12, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [026067e41d](https://linux-hardware.org/?probe=026067e41d) | Sep 12, 2020 |
| TYAN Compu... | S4885 Thunder K8SQ S4885    | Server      | [64251b3f2a](https://linux-hardware.org/?probe=64251b3f2a) | Sep 12, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | Notebook    | [9149c8b59c](https://linux-hardware.org/?probe=9149c8b59c) | Sep 11, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | Notebook    | [d549f8665d](https://linux-hardware.org/?probe=d549f8665d) | Sep 11, 2020 |
| Acer          | Aspire A715-75G             | Notebook    | [5f5f26f02c](https://linux-hardware.org/?probe=5f5f26f02c) | Sep 11, 2020 |
| HP            | 245 G5 Notebook PC          | Notebook    | [2ef10aa9df](https://linux-hardware.org/?probe=2ef10aa9df) | Sep 10, 2020 |
| Acer          | Predator G5910              | Desktop     | [2d8d8807fc](https://linux-hardware.org/?probe=2d8d8807fc) | Sep 10, 2020 |
| Acer          | Predator G5910              | Desktop     | [bc07c92db3](https://linux-hardware.org/?probe=bc07c92db3) | Sep 10, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [b23396f446](https://linux-hardware.org/?probe=b23396f446) | Sep 10, 2020 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [044c2421f2](https://linux-hardware.org/?probe=044c2421f2) | Sep 10, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [3280a78a79](https://linux-hardware.org/?probe=3280a78a79) | Sep 09, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ed6724ef0b](https://linux-hardware.org/?probe=ed6724ef0b) | Sep 09, 2020 |
| Dell          | Precision 5510              | Notebook    | [f4f4ec51bf](https://linux-hardware.org/?probe=f4f4ec51bf) | Sep 09, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [47f8b2d362](https://linux-hardware.org/?probe=47f8b2d362) | Sep 09, 2020 |
| HP            | 3031h                       | Desktop     | [55e0edb811](https://linux-hardware.org/?probe=55e0edb811) | Sep 09, 2020 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [fe6668f9b4](https://linux-hardware.org/?probe=fe6668f9b4) | Sep 08, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [c45b64a8d0](https://linux-hardware.org/?probe=c45b64a8d0) | Sep 08, 2020 |
| Dell          | Latitude E6430s             | Notebook    | [bd8ab4dd1c](https://linux-hardware.org/?probe=bd8ab4dd1c) | Sep 08, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [50084e0fd3](https://linux-hardware.org/?probe=50084e0fd3) | Sep 08, 2020 |
| HP            | Notebook                    | Notebook    | [06a50afc04](https://linux-hardware.org/?probe=06a50afc04) | Sep 08, 2020 |
| LG Electro... | 14Z990-V.AR52A2             | Notebook    | [c2bd6779ff](https://linux-hardware.org/?probe=c2bd6779ff) | Sep 08, 2020 |
| Gigabyte      | B360M HD3                   | Desktop     | [7521b3b6e2](https://linux-hardware.org/?probe=7521b3b6e2) | Sep 07, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [7359e2dd84](https://linux-hardware.org/?probe=7359e2dd84) | Sep 07, 2020 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [1b230fa054](https://linux-hardware.org/?probe=1b230fa054) | Sep 07, 2020 |
| ASUSTek       | EB1501P                     | Desktop     | [6f97b62a32](https://linux-hardware.org/?probe=6f97b62a32) | Sep 07, 2020 |
| ASUSTek       | P5LD2EB2-DHS                | Desktop     | [3c62df51c9](https://linux-hardware.org/?probe=3c62df51c9) | Sep 07, 2020 |
| Toshiba       | Satellite C70D-B            | Notebook    | [8be17e95f8](https://linux-hardware.org/?probe=8be17e95f8) | Sep 07, 2020 |
| ASUSTek       | P6T                         | Desktop     | [5b4f0b4a9d](https://linux-hardware.org/?probe=5b4f0b4a9d) | Sep 06, 2020 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [9f5fedde56](https://linux-hardware.org/?probe=9f5fedde56) | Sep 06, 2020 |
| Dell          | Inspiron 13-7378            | Notebook    | [b5f30e080b](https://linux-hardware.org/?probe=b5f30e080b) | Sep 06, 2020 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [6435c0f263](https://linux-hardware.org/?probe=6435c0f263) | Sep 06, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [e27a9041fe](https://linux-hardware.org/?probe=e27a9041fe) | Sep 06, 2020 |
| MSI           | A320M GRENADE               | Desktop     | [d57136dab3](https://linux-hardware.org/?probe=d57136dab3) | Sep 05, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [606450d026](https://linux-hardware.org/?probe=606450d026) | Sep 05, 2020 |
| ASUSTek       | TUF Gaming FA706II_FA706... | Notebook    | [010c1cd9e2](https://linux-hardware.org/?probe=010c1cd9e2) | Sep 05, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [543b18512b](https://linux-hardware.org/?probe=543b18512b) | Sep 05, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [f93061fe2b](https://linux-hardware.org/?probe=f93061fe2b) | Sep 05, 2020 |
| Notebook      | NH50_70RA                   | Notebook    | [e196e35eef](https://linux-hardware.org/?probe=e196e35eef) | Sep 05, 2020 |
| Lenovo        | ThinkPad T430 2349S1P       | Notebook    | [fe7927ec17](https://linux-hardware.org/?probe=fe7927ec17) | Sep 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [d6346fbb4b](https://linux-hardware.org/?probe=d6346fbb4b) | Sep 05, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b1248e2b3b](https://linux-hardware.org/?probe=b1248e2b3b) | Sep 05, 2020 |
| ASUSTek       | TUF Gaming FA706II_FA706... | Notebook    | [37d0b9b508](https://linux-hardware.org/?probe=37d0b9b508) | Sep 05, 2020 |
| HP            | 843B                        | Desktop     | [9af121301d](https://linux-hardware.org/?probe=9af121301d) | Sep 05, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [c917a68a1f](https://linux-hardware.org/?probe=c917a68a1f) | Sep 05, 2020 |
| Lenovo        | ThinkPad L470 20J4000NIX    | Notebook    | [a9bf3bb043](https://linux-hardware.org/?probe=a9bf3bb043) | Sep 04, 2020 |
| ASUSTek       | E3 PRO GAMING V5            | Desktop     | [149e51be54](https://linux-hardware.org/?probe=149e51be54) | Sep 04, 2020 |
| ASUSTek       | E3 PRO GAMING V5            | Desktop     | [96dcfc5f7a](https://linux-hardware.org/?probe=96dcfc5f7a) | Sep 04, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [a6f77b3cc6](https://linux-hardware.org/?probe=a6f77b3cc6) | Sep 04, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [59601aa4e7](https://linux-hardware.org/?probe=59601aa4e7) | Sep 04, 2020 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [ffa4fe7acd](https://linux-hardware.org/?probe=ffa4fe7acd) | Sep 04, 2020 |
| Sony          | SVF14A15CBB                 | Notebook    | [ad06e8af25](https://linux-hardware.org/?probe=ad06e8af25) | Sep 04, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [2e8f4e982d](https://linux-hardware.org/?probe=2e8f4e982d) | Sep 04, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [b079daad2c](https://linux-hardware.org/?probe=b079daad2c) | Sep 04, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [242f9cb8c6](https://linux-hardware.org/?probe=242f9cb8c6) | Sep 03, 2020 |
| Standard      | Unknown                     | Notebook    | [2a141c33ce](https://linux-hardware.org/?probe=2a141c33ce) | Sep 03, 2020 |
| MSI           | GF63 Thin 8RCS              | Notebook    | [ec4eac1cb7](https://linux-hardware.org/?probe=ec4eac1cb7) | Sep 03, 2020 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [84ab08b92f](https://linux-hardware.org/?probe=84ab08b92f) | Sep 03, 2020 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [57787ad63d](https://linux-hardware.org/?probe=57787ad63d) | Sep 03, 2020 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [66f1d9fde1](https://linux-hardware.org/?probe=66f1d9fde1) | Sep 03, 2020 |
| HP            | OMEN by HP Laptop 15-ce0... | Notebook    | [8cd545336f](https://linux-hardware.org/?probe=8cd545336f) | Sep 03, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [7fe7f3fa13](https://linux-hardware.org/?probe=7fe7f3fa13) | Sep 03, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [6c84136b17](https://linux-hardware.org/?probe=6c84136b17) | Sep 03, 2020 |
| HP            | 255 G6 Notebook PC          | Notebook    | [1fbe32dcdc](https://linux-hardware.org/?probe=1fbe32dcdc) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [13e0a80ca9](https://linux-hardware.org/?probe=13e0a80ca9) | Sep 03, 2020 |
| ASRock        | X470 Master SLI             | Desktop     | [03bcf3b1fd](https://linux-hardware.org/?probe=03bcf3b1fd) | Sep 02, 2020 |
| MSI           | Z97-G45 GAMING              | Desktop     | [23d327ddd1](https://linux-hardware.org/?probe=23d327ddd1) | Sep 02, 2020 |
| Acer          | Aspire VN7-592G             | Notebook    | [2eeaf6bdda](https://linux-hardware.org/?probe=2eeaf6bdda) | Sep 02, 2020 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [efb03db319](https://linux-hardware.org/?probe=efb03db319) | Sep 02, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [8771bcd693](https://linux-hardware.org/?probe=8771bcd693) | Sep 02, 2020 |
| Acer          | Aspire A515-51              | Notebook    | [3f826318c0](https://linux-hardware.org/?probe=3f826318c0) | Sep 02, 2020 |
| HP            | 3031h                       | Desktop     | [07f0c3ce98](https://linux-hardware.org/?probe=07f0c3ce98) | Sep 01, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [1f74a97af3](https://linux-hardware.org/?probe=1f74a97af3) | Sep 01, 2020 |
| TUXEDO        | N650DU                      | Notebook    | [9ae3f57dbb](https://linux-hardware.org/?probe=9ae3f57dbb) | Sep 01, 2020 |
| ECS           | 945GCT-M3                   | Desktop     | [f9ba0e8e03](https://linux-hardware.org/?probe=f9ba0e8e03) | Sep 01, 2020 |
| BESSTAR Te... | AB1A                        | Mini pc     | [ae96b73126](https://linux-hardware.org/?probe=ae96b73126) | Aug 31, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [fd7fc1ce8d](https://linux-hardware.org/?probe=fd7fc1ce8d) | Aug 31, 2020 |
| MSI           | Boston                      | Desktop     | [90c8e43351](https://linux-hardware.org/?probe=90c8e43351) | Aug 31, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [78553c451b](https://linux-hardware.org/?probe=78553c451b) | Aug 31, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [43ab5a6f50](https://linux-hardware.org/?probe=43ab5a6f50) | Aug 31, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c3715c80a4](https://linux-hardware.org/?probe=c3715c80a4) | Aug 31, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [8e66b19fac](https://linux-hardware.org/?probe=8e66b19fac) | Aug 31, 2020 |
| Dell          | 048DY8 A01                  | Desktop     | [bc89fe6963](https://linux-hardware.org/?probe=bc89fe6963) | Aug 31, 2020 |
| ASUSTek       | P5Q SE                      | Desktop     | [37d2955943](https://linux-hardware.org/?probe=37d2955943) | Aug 30, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [74033ad383](https://linux-hardware.org/?probe=74033ad383) | Aug 30, 2020 |
| Acer          | Aspire C24-865              | All in one  | [68d89317dc](https://linux-hardware.org/?probe=68d89317dc) | Aug 30, 2020 |
| Acer          | Aspire C24-865              | All in one  | [b10a4e5810](https://linux-hardware.org/?probe=b10a4e5810) | Aug 30, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [83c8a33e5b](https://linux-hardware.org/?probe=83c8a33e5b) | Aug 29, 2020 |
| HP            | Laptop 15-rb0xx             | Notebook    | [46be2eb505](https://linux-hardware.org/?probe=46be2eb505) | Aug 29, 2020 |
| ASUSTek       | X202E                       | Notebook    | [31ae5ac511](https://linux-hardware.org/?probe=31ae5ac511) | Aug 29, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e4cd61504d](https://linux-hardware.org/?probe=e4cd61504d) | Aug 29, 2020 |
| ASUSTek       | X202E                       | Notebook    | [74ccf153c8](https://linux-hardware.org/?probe=74ccf153c8) | Aug 29, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [58c99091e7](https://linux-hardware.org/?probe=58c99091e7) | Aug 29, 2020 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [46e52c99b2](https://linux-hardware.org/?probe=46e52c99b2) | Aug 29, 2020 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [675c58e89c](https://linux-hardware.org/?probe=675c58e89c) | Aug 29, 2020 |
| MSI           | B550-A PRO                  | Desktop     | [8a0712da96](https://linux-hardware.org/?probe=8a0712da96) | Aug 28, 2020 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [8906eb8e2a](https://linux-hardware.org/?probe=8906eb8e2a) | Aug 28, 2020 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [c94109d2e0](https://linux-hardware.org/?probe=c94109d2e0) | Aug 28, 2020 |
| Positivo      | C14CR21                     | Notebook    | [3ae459b25d](https://linux-hardware.org/?probe=3ae459b25d) | Aug 28, 2020 |
| Toshiba       | Satellite T135D             | Notebook    | [e59691cfe7](https://linux-hardware.org/?probe=e59691cfe7) | Aug 28, 2020 |
| HP            | 0266                        | Desktop     | [b2d762f823](https://linux-hardware.org/?probe=b2d762f823) | Aug 27, 2020 |
| Dell          | Inspiron 5557               | Notebook    | [09095e1ecf](https://linux-hardware.org/?probe=09095e1ecf) | Aug 27, 2020 |
| Dell          | Precision 7540              | Notebook    | [8e97d27134](https://linux-hardware.org/?probe=8e97d27134) | Aug 27, 2020 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [e971c1ded7](https://linux-hardware.org/?probe=e971c1ded7) | Aug 27, 2020 |
| ASRock        | Z87E-ITX                    | Desktop     | [e286963b35](https://linux-hardware.org/?probe=e286963b35) | Aug 26, 2020 |
| Dell          | Inspiron 7460               | Notebook    | [ac517bf42a](https://linux-hardware.org/?probe=ac517bf42a) | Aug 26, 2020 |
| ASRock        | H410M-HVS                   | Desktop     | [6fb6841972](https://linux-hardware.org/?probe=6fb6841972) | Aug 26, 2020 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [e1f992e468](https://linux-hardware.org/?probe=e1f992e468) | Aug 26, 2020 |
| HP            | 339A                        | Desktop     | [6565380ec2](https://linux-hardware.org/?probe=6565380ec2) | Aug 26, 2020 |
| Lenovo        | ThinkPad S5 Yoga 15 20DQ... | Notebook    | [0ee88118f8](https://linux-hardware.org/?probe=0ee88118f8) | Aug 26, 2020 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [3f34506c1d](https://linux-hardware.org/?probe=3f34506c1d) | Aug 26, 2020 |
| Lenovo        | ThinkPad T490 20N3S02L00    | Notebook    | [9cb7bccca3](https://linux-hardware.org/?probe=9cb7bccca3) | Aug 25, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [019aa19877](https://linux-hardware.org/?probe=019aa19877) | Aug 25, 2020 |
| Lenovo        | V370 HuronRiver Platform    | Notebook    | [ef3597f6f2](https://linux-hardware.org/?probe=ef3597f6f2) | Aug 24, 2020 |
| Lenovo        | ThinkPad X200 7458M3U       | Notebook    | [676494e561](https://linux-hardware.org/?probe=676494e561) | Aug 24, 2020 |
| Lenovo        | U41-70                      | Notebook    | [d35278ec3d](https://linux-hardware.org/?probe=d35278ec3d) | Aug 24, 2020 |
| LG Electro... | 15Z990-V.AA78B              | Notebook    | [f99a7bd86f](https://linux-hardware.org/?probe=f99a7bd86f) | Aug 24, 2020 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [4889be0d7d](https://linux-hardware.org/?probe=4889be0d7d) | Aug 22, 2020 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [d958b35d39](https://linux-hardware.org/?probe=d958b35d39) | Aug 21, 2020 |
| TUXEDO        | N650DU                      | Notebook    | [74b4a706ca](https://linux-hardware.org/?probe=74b4a706ca) | Aug 21, 2020 |
| HP            | 212B                        | Desktop     | [2ec5e51a63](https://linux-hardware.org/?probe=2ec5e51a63) | Aug 21, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [a032eb097e](https://linux-hardware.org/?probe=a032eb097e) | Aug 21, 2020 |
| Pegatron      | 2AB5                        | Desktop     | [954d271b91](https://linux-hardware.org/?probe=954d271b91) | Aug 20, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [a8d3c14440](https://linux-hardware.org/?probe=a8d3c14440) | Aug 20, 2020 |
| ASRock        | B360M Performance           | Desktop     | [52345bce36](https://linux-hardware.org/?probe=52345bce36) | Aug 19, 2020 |
| Dell          | Precision M4800             | Notebook    | [4765bc9ec2](https://linux-hardware.org/?probe=4765bc9ec2) | Aug 19, 2020 |
| MSI           | B450-A PRO MAX              | Desktop     | [a8bb7acbbc](https://linux-hardware.org/?probe=a8bb7acbbc) | Aug 19, 2020 |
| Dell          | Precision M4800             | Notebook    | [eee5b97967](https://linux-hardware.org/?probe=eee5b97967) | Aug 19, 2020 |
| Samsung       | 800G5M/800G5W               | Notebook    | [0d6c9159da](https://linux-hardware.org/?probe=0d6c9159da) | Aug 19, 2020 |
| Google        | Cyan                        | Notebook    | [9cf6dad6b6](https://linux-hardware.org/?probe=9cf6dad6b6) | Aug 19, 2020 |
| Google        | Cyan                        | Notebook    | [93a0058cec](https://linux-hardware.org/?probe=93a0058cec) | Aug 19, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5c09a8571d](https://linux-hardware.org/?probe=5c09a8571d) | Aug 19, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [eb53034724](https://linux-hardware.org/?probe=eb53034724) | Aug 18, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [e340100f45](https://linux-hardware.org/?probe=e340100f45) | Aug 18, 2020 |
| Acer          | Aspire A515-44G             | Notebook    | [ad50c2f263](https://linux-hardware.org/?probe=ad50c2f263) | Aug 17, 2020 |
| Acer          | Aspire A515-44G             | Notebook    | [97a874306a](https://linux-hardware.org/?probe=97a874306a) | Aug 17, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [316ac04cd7](https://linux-hardware.org/?probe=316ac04cd7) | Aug 17, 2020 |
| HP            | 1998                        | Desktop     | [7aa4744924](https://linux-hardware.org/?probe=7aa4744924) | Aug 17, 2020 |
| Unknown       | KN12A                       | Notebook    | [56648f0d99](https://linux-hardware.org/?probe=56648f0d99) | Aug 16, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [d254d96179](https://linux-hardware.org/?probe=d254d96179) | Aug 16, 2020 |
| Sony          | VPCEH35FM                   | Notebook    | [f96be03ce2](https://linux-hardware.org/?probe=f96be03ce2) | Aug 16, 2020 |
| Sony          | VPCEH35FM                   | Notebook    | [7c93afc948](https://linux-hardware.org/?probe=7c93afc948) | Aug 16, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [65cf550e5a](https://linux-hardware.org/?probe=65cf550e5a) | Aug 16, 2020 |
| MSI           | Z370-A PRO                  | Desktop     | [e37fd4a94f](https://linux-hardware.org/?probe=e37fd4a94f) | Aug 14, 2020 |
| ASUSTek       | X541SA                      | Notebook    | [2d6beed0c6](https://linux-hardware.org/?probe=2d6beed0c6) | Aug 13, 2020 |
| Lenovo        | ThinkPad T520 42405GG       | Notebook    | [b56a1ac043](https://linux-hardware.org/?probe=b56a1ac043) | Aug 13, 2020 |
| Dell          | Latitude E6410              | Notebook    | [09350e680d](https://linux-hardware.org/?probe=09350e680d) | Aug 12, 2020 |
| Lenovo        | HURONRIVER                  | All in one  | [f2d65d0d1d](https://linux-hardware.org/?probe=f2d65d0d1d) | Aug 12, 2020 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [2f7b60e4cd](https://linux-hardware.org/?probe=2f7b60e4cd) | Aug 12, 2020 |
| MSI           | B350 PC MATE                | Desktop     | [0d1eb9465b](https://linux-hardware.org/?probe=0d1eb9465b) | Aug 12, 2020 |
| MSI           | B250M BAZOOKA               | Desktop     | [78bb05b2c6](https://linux-hardware.org/?probe=78bb05b2c6) | Aug 12, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [a00f58a226](https://linux-hardware.org/?probe=a00f58a226) | Aug 11, 2020 |
| Dell          | XPS L502X                   | Notebook    | [9621996153](https://linux-hardware.org/?probe=9621996153) | Aug 11, 2020 |
| Dell          | Latitude E6530              | Notebook    | [e257f7fabb](https://linux-hardware.org/?probe=e257f7fabb) | Aug 11, 2020 |
| HP            | Notebook                    | Notebook    | [1b80bb7f7e](https://linux-hardware.org/?probe=1b80bb7f7e) | Aug 11, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [6c6091dbad](https://linux-hardware.org/?probe=6c6091dbad) | Aug 10, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [943de78484](https://linux-hardware.org/?probe=943de78484) | Aug 10, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a22cc9f46c](https://linux-hardware.org/?probe=a22cc9f46c) | Aug 10, 2020 |
| Dell          | Inspiron 5759               | Notebook    | [6484055ab4](https://linux-hardware.org/?probe=6484055ab4) | Aug 10, 2020 |
| Dell          | Inspiron 3793               | Notebook    | [3db004f298](https://linux-hardware.org/?probe=3db004f298) | Aug 09, 2020 |
| Lenovo        | Yoga 720-12IKB 81B5         | Convertible | [61518f1e84](https://linux-hardware.org/?probe=61518f1e84) | Aug 09, 2020 |
| Lenovo        | Yoga 720-12IKB 81B5         | Convertible | [09e63aa959](https://linux-hardware.org/?probe=09e63aa959) | Aug 09, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [e4a1d6db53](https://linux-hardware.org/?probe=e4a1d6db53) | Aug 08, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [e7bbf8e988](https://linux-hardware.org/?probe=e7bbf8e988) | Aug 08, 2020 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e238793adb](https://linux-hardware.org/?probe=e238793adb) | Aug 08, 2020 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [69126c9388](https://linux-hardware.org/?probe=69126c9388) | Aug 08, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e3d0d53b20](https://linux-hardware.org/?probe=e3d0d53b20) | Aug 08, 2020 |
| ASRock        | Z87 Pro3                    | Desktop     | [9fc26dbca3](https://linux-hardware.org/?probe=9fc26dbca3) | Aug 07, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3e788a2bd9](https://linux-hardware.org/?probe=3e788a2bd9) | Aug 07, 2020 |
| BANGHO        | MAX G5                      | Notebook    | [f38efc30b3](https://linux-hardware.org/?probe=f38efc30b3) | Aug 07, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [08654c69dd](https://linux-hardware.org/?probe=08654c69dd) | Aug 07, 2020 |
| ASRock        | Z87 Pro3                    | Desktop     | [fda49e84b2](https://linux-hardware.org/?probe=fda49e84b2) | Aug 06, 2020 |
| ASUSTek       | K72Jr                       | Notebook    | [b34ac67f89](https://linux-hardware.org/?probe=b34ac67f89) | Aug 06, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [8f00b6e4d5](https://linux-hardware.org/?probe=8f00b6e4d5) | Aug 05, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [4d69d17277](https://linux-hardware.org/?probe=4d69d17277) | Aug 05, 2020 |
| Gigabyte      | H97M-D3H                    | Desktop     | [2cd61abaf3](https://linux-hardware.org/?probe=2cd61abaf3) | Aug 05, 2020 |
| Gigabyte      | H97M-D3H                    | Desktop     | [35d7a6081d](https://linux-hardware.org/?probe=35d7a6081d) | Aug 05, 2020 |
| Intel         | E5 (INTEL Xeon E5/Core i... | Desktop     | [3917eb1849](https://linux-hardware.org/?probe=3917eb1849) | Aug 05, 2020 |
| Apple         | Mac-F22C86C8                | Mini pc     | [6d92297671](https://linux-hardware.org/?probe=6d92297671) | Aug 05, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [801277e6be](https://linux-hardware.org/?probe=801277e6be) | Aug 05, 2020 |
| Chuwi         | Hi10 X                      | Tablet      | [fcd613858b](https://linux-hardware.org/?probe=fcd613858b) | Aug 05, 2020 |
| Gigabyte      | AERO 15-SA                  | Notebook    | [6f661c14fd](https://linux-hardware.org/?probe=6f661c14fd) | Aug 04, 2020 |
| Razer         | Blade                       | Notebook    | [d75a02f0df](https://linux-hardware.org/?probe=d75a02f0df) | Aug 04, 2020 |
| Gigabyte      | AERO 15-SA                  | Notebook    | [d73c101b9a](https://linux-hardware.org/?probe=d73c101b9a) | Aug 04, 2020 |
| Chuwi         | Hi10 X                      | Tablet      | [64481efe47](https://linux-hardware.org/?probe=64481efe47) | Aug 04, 2020 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [66421b347c](https://linux-hardware.org/?probe=66421b347c) | Aug 03, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [26ce95f067](https://linux-hardware.org/?probe=26ce95f067) | Aug 03, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [3e56d4fbe5](https://linux-hardware.org/?probe=3e56d4fbe5) | Aug 02, 2020 |
| Gigabyte      | P67X-UD3-B3                 | Desktop     | [2a8cccd919](https://linux-hardware.org/?probe=2a8cccd919) | Aug 02, 2020 |
| Dell          | Latitude E7450              | Notebook    | [5986404aa5](https://linux-hardware.org/?probe=5986404aa5) | Aug 02, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0ecb4938d1](https://linux-hardware.org/?probe=0ecb4938d1) | Aug 02, 2020 |
| Lenovo        | ThinkPad T450 20BUS09905    | Notebook    | [1b8b139eab](https://linux-hardware.org/?probe=1b8b139eab) | Aug 02, 2020 |
| ASRock        | 775Dual-VSTA                | Desktop     | [a2ad60fd2b](https://linux-hardware.org/?probe=a2ad60fd2b) | Aug 01, 2020 |
| Lenovo        | ThinkPad T450 20BUS09905    | Notebook    | [e183ee6daa](https://linux-hardware.org/?probe=e183ee6daa) | Aug 01, 2020 |
| Dell          | Latitude E7440              | Notebook    | [9f2adcf4cc](https://linux-hardware.org/?probe=9f2adcf4cc) | Jul 31, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [96ba8dc0e8](https://linux-hardware.org/?probe=96ba8dc0e8) | Jul 31, 2020 |
| Dell          | Latitude 5580               | Notebook    | [f2260d4787](https://linux-hardware.org/?probe=f2260d4787) | Jul 30, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [747e731b16](https://linux-hardware.org/?probe=747e731b16) | Jul 30, 2020 |
| Dell          | Latitude 5490               | Notebook    | [3e498b1c43](https://linux-hardware.org/?probe=3e498b1c43) | Jul 30, 2020 |
| Lenovo        | ThinkPad W550s 20E2000CM... | Notebook    | [fae2775795](https://linux-hardware.org/?probe=fae2775795) | Jul 30, 2020 |
| ASRock        | Z370 Gaming K6              | Desktop     | [d2b117ce8f](https://linux-hardware.org/?probe=d2b117ce8f) | Jul 29, 2020 |
| Dell          | Vostro 5590                 | Notebook    | [8232cfcfe5](https://linux-hardware.org/?probe=8232cfcfe5) | Jul 28, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [8326d433b9](https://linux-hardware.org/?probe=8326d433b9) | Jul 27, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [95b87e4baf](https://linux-hardware.org/?probe=95b87e4baf) | Jul 27, 2020 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [0f375027b9](https://linux-hardware.org/?probe=0f375027b9) | Jul 27, 2020 |
| Dell          | Vostro 5481                 | Notebook    | [e87aff2d7f](https://linux-hardware.org/?probe=e87aff2d7f) | Jul 27, 2020 |
| HP            | 1495                        | Desktop     | [8a51ce66a3](https://linux-hardware.org/?probe=8a51ce66a3) | Jul 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f5c932c351](https://linux-hardware.org/?probe=f5c932c351) | Jul 27, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [94b11d033b](https://linux-hardware.org/?probe=94b11d033b) | Jul 26, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [0aa3ff02cb](https://linux-hardware.org/?probe=0aa3ff02cb) | Jul 26, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [b49d7f155b](https://linux-hardware.org/?probe=b49d7f155b) | Jul 26, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [68ef74226e](https://linux-hardware.org/?probe=68ef74226e) | Jul 26, 2020 |
| Samsung       | 550XBE/350XBE               | Notebook    | [ad20c88ebd](https://linux-hardware.org/?probe=ad20c88ebd) | Jul 25, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [2c9f3809f5](https://linux-hardware.org/?probe=2c9f3809f5) | Jul 25, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [d5f013fb10](https://linux-hardware.org/?probe=d5f013fb10) | Jul 25, 2020 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [8fde64525d](https://linux-hardware.org/?probe=8fde64525d) | Jul 24, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f8f7d2d073](https://linux-hardware.org/?probe=f8f7d2d073) | Jul 24, 2020 |
| Acer          | Extensa 5620                | Notebook    | [9cd383a169](https://linux-hardware.org/?probe=9cd383a169) | Jul 24, 2020 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [8a9f7186fb](https://linux-hardware.org/?probe=8a9f7186fb) | Jul 24, 2020 |
| Lenovo        | B330-15IKBR 81M1            | Notebook    | [a31b1a2785](https://linux-hardware.org/?probe=a31b1a2785) | Jul 24, 2020 |
| Samsung       | 300E5M/300E5L               | Notebook    | [1342a6e4c6](https://linux-hardware.org/?probe=1342a6e4c6) | Jul 24, 2020 |
| Dell          | Latitude 5480               | Notebook    | [e9eebe91ff](https://linux-hardware.org/?probe=e9eebe91ff) | Jul 24, 2020 |
| Dell          | Latitude 5480               | Notebook    | [27e8086cb0](https://linux-hardware.org/?probe=27e8086cb0) | Jul 24, 2020 |
| Samsung       | 300E5M/300E5L               | Notebook    | [1f38eb4b9f](https://linux-hardware.org/?probe=1f38eb4b9f) | Jul 24, 2020 |
| Dell          | 0FKTT8 A02                  | Desktop     | [599497ea19](https://linux-hardware.org/?probe=599497ea19) | Jul 24, 2020 |
| ECS           | G31T-M7                     | Desktop     | [41d6caba99](https://linux-hardware.org/?probe=41d6caba99) | Jul 24, 2020 |
| Samsung       | 550XBE/350XBE               | Notebook    | [e6daff2785](https://linux-hardware.org/?probe=e6daff2785) | Jul 24, 2020 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [780c10c662](https://linux-hardware.org/?probe=780c10c662) | Jul 24, 2020 |
| Acer          | Predator PH315-52           | Notebook    | [27e53576c5](https://linux-hardware.org/?probe=27e53576c5) | Jul 24, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [e7b12d791d](https://linux-hardware.org/?probe=e7b12d791d) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [8d28e2ad83](https://linux-hardware.org/?probe=8d28e2ad83) | Jul 24, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [5dfcf0d477](https://linux-hardware.org/?probe=5dfcf0d477) | Jul 24, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [badc539e85](https://linux-hardware.org/?probe=badc539e85) | Jul 24, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [c88ef41ab5](https://linux-hardware.org/?probe=c88ef41ab5) | Jul 24, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [b0815fe9a9](https://linux-hardware.org/?probe=b0815fe9a9) | Jul 24, 2020 |
| Acer          | Aspire A515-51              | Notebook    | [b7bda74f72](https://linux-hardware.org/?probe=b7bda74f72) | Jul 24, 2020 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [0c4cd978f2](https://linux-hardware.org/?probe=0c4cd978f2) | Jul 24, 2020 |
| Gateway       | NV59                        | Notebook    | [072f41bee2](https://linux-hardware.org/?probe=072f41bee2) | Jul 23, 2020 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | Notebook    | [edf7f9bd8c](https://linux-hardware.org/?probe=edf7f9bd8c) | Jul 23, 2020 |
| PC Special... | UltraNoteIV 14              | Notebook    | [52e8c39bcd](https://linux-hardware.org/?probe=52e8c39bcd) | Jul 23, 2020 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [730d20b522](https://linux-hardware.org/?probe=730d20b522) | Jul 23, 2020 |
| PC Special... | UltraNoteIV 14              | Notebook    | [405d3a990b](https://linux-hardware.org/?probe=405d3a990b) | Jul 23, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [f6f1267e91](https://linux-hardware.org/?probe=f6f1267e91) | Jul 23, 2020 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [746d3cea84](https://linux-hardware.org/?probe=746d3cea84) | Jul 23, 2020 |
| MSI           | H97 GUARD-PRO               | Desktop     | [ca29557f55](https://linux-hardware.org/?probe=ca29557f55) | Jul 23, 2020 |
| Lenovo        | ThinkPad E470 20H20008BR    | Notebook    | [b4a20d1c82](https://linux-hardware.org/?probe=b4a20d1c82) | Jul 23, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [452ca6ffa5](https://linux-hardware.org/?probe=452ca6ffa5) | Jul 23, 2020 |
| Huanan        | X79-ZD3 INTEL (INTEL Xeo... | Desktop     | [f1727aeef0](https://linux-hardware.org/?probe=f1727aeef0) | Jul 22, 2020 |
| SIRAGON       | Series 5100/7100/9100       | Notebook    | [c24a54538a](https://linux-hardware.org/?probe=c24a54538a) | Jul 22, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [180d7fadbc](https://linux-hardware.org/?probe=180d7fadbc) | Jul 22, 2020 |
| ASUSTek       | M4N72-E                     | Desktop     | [d77d4e79eb](https://linux-hardware.org/?probe=d77d4e79eb) | Jul 22, 2020 |
| Dell          | Latitude 7480               | Notebook    | [7fa880215f](https://linux-hardware.org/?probe=7fa880215f) | Jul 21, 2020 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [f69af5d26f](https://linux-hardware.org/?probe=f69af5d26f) | Jul 21, 2020 |
| ASUSTek       | K72Jr                       | Notebook    | [34628b0cae](https://linux-hardware.org/?probe=34628b0cae) | Jul 21, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6284319c25](https://linux-hardware.org/?probe=6284319c25) | Jul 20, 2020 |
| Dell          | Vostro 3560                 | Notebook    | [349fafab4b](https://linux-hardware.org/?probe=349fafab4b) | Jul 20, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [b920c346ed](https://linux-hardware.org/?probe=b920c346ed) | Jul 19, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [0d034528d4](https://linux-hardware.org/?probe=0d034528d4) | Jul 19, 2020 |
| Lenovo        | ThinkPad W550s 20E2000CM... | Notebook    | [2db5fa6bb3](https://linux-hardware.org/?probe=2db5fa6bb3) | Jul 19, 2020 |
| HP            | EliteBook 850 G3            | Notebook    | [6bdfab8f44](https://linux-hardware.org/?probe=6bdfab8f44) | Jul 19, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3f740083f9](https://linux-hardware.org/?probe=3f740083f9) | Jul 19, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f1c586d370](https://linux-hardware.org/?probe=f1c586d370) | Jul 19, 2020 |
| HP            | G71                         | Notebook    | [f950e81d78](https://linux-hardware.org/?probe=f950e81d78) | Jul 19, 2020 |
| Dell          | Inspiron 7586               | Convertible | [8db78d8a92](https://linux-hardware.org/?probe=8db78d8a92) | Jul 18, 2020 |
| Dell          | 0JYH5J A00                  | All in one  | [4269e1e573](https://linux-hardware.org/?probe=4269e1e573) | Jul 18, 2020 |
| Dell          | Latitude 7480               | Notebook    | [4d9b292d01](https://linux-hardware.org/?probe=4d9b292d01) | Jul 18, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [987d62f6ed](https://linux-hardware.org/?probe=987d62f6ed) | Jul 17, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2298274454](https://linux-hardware.org/?probe=2298274454) | Jul 17, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2f5df8729a](https://linux-hardware.org/?probe=2f5df8729a) | Jul 17, 2020 |
| Dell          | 0XPDFK A01                  | Desktop     | [97e1cc5928](https://linux-hardware.org/?probe=97e1cc5928) | Jul 17, 2020 |
| Dell          | 00V62H A00                  | Desktop     | [34a7d1db11](https://linux-hardware.org/?probe=34a7d1db11) | Jul 17, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b3cf909105](https://linux-hardware.org/?probe=b3cf909105) | Jul 17, 2020 |
| ASUSTek       | H81-PLUS                    | Desktop     | [0e79ae7820](https://linux-hardware.org/?probe=0e79ae7820) | Jul 16, 2020 |
| ASUSTek       | H81-PLUS                    | Desktop     | [915f6d5a88](https://linux-hardware.org/?probe=915f6d5a88) | Jul 16, 2020 |
| Dell          | Inspiron 7791 2n1           | Convertible | [ee7d2822e1](https://linux-hardware.org/?probe=ee7d2822e1) | Jul 15, 2020 |
| MSI           | 870U-G55                    | Desktop     | [256a906a3a](https://linux-hardware.org/?probe=256a906a3a) | Jul 14, 2020 |
| ASUSTek       | AM1I-A                      | Desktop     | [9425979073](https://linux-hardware.org/?probe=9425979073) | Jul 14, 2020 |
| Dell          | Latitude 5401               | Notebook    | [d5cde026f3](https://linux-hardware.org/?probe=d5cde026f3) | Jul 14, 2020 |
| Dell          | G3 3590                     | Notebook    | [7af64cd3fa](https://linux-hardware.org/?probe=7af64cd3fa) | Jul 14, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [de4ad13bb4](https://linux-hardware.org/?probe=de4ad13bb4) | Jul 14, 2020 |
| Dell          | Latitude E7440              | Notebook    | [324ee4f4c5](https://linux-hardware.org/?probe=324ee4f4c5) | Jul 13, 2020 |
| Dell          | Latitude 5580               | Notebook    | [554f51cf25](https://linux-hardware.org/?probe=554f51cf25) | Jul 13, 2020 |
| Dell          | 0TWFTR A01                  | All in one  | [539ade784f](https://linux-hardware.org/?probe=539ade784f) | Jul 12, 2020 |
| ASRock        | H61M-VG4                    | Desktop     | [2f9520527b](https://linux-hardware.org/?probe=2f9520527b) | Jul 11, 2020 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [85669d7c08](https://linux-hardware.org/?probe=85669d7c08) | Jul 11, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [2bafa31949](https://linux-hardware.org/?probe=2bafa31949) | Jul 11, 2020 |
| ASRock        | H61M-VG4                    | Desktop     | [b36bc5f47e](https://linux-hardware.org/?probe=b36bc5f47e) | Jul 11, 2020 |
| Dell          | Latitude 7480               | Notebook    | [c265940ec9](https://linux-hardware.org/?probe=c265940ec9) | Jul 11, 2020 |
| Dell          | Latitude E5440              | Notebook    | [99905ddc2d](https://linux-hardware.org/?probe=99905ddc2d) | Jul 11, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [7982b39946](https://linux-hardware.org/?probe=7982b39946) | Jul 10, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [92fbcdfaca](https://linux-hardware.org/?probe=92fbcdfaca) | Jul 10, 2020 |
| ECS           | A790GXM-AD3                 | Desktop     | [dc63f56959](https://linux-hardware.org/?probe=dc63f56959) | Jul 10, 2020 |
| ECS           | A790GXM-AD3                 | Desktop     | [f692211349](https://linux-hardware.org/?probe=f692211349) | Jul 10, 2020 |
| Dell          | Latitude E4310              | Notebook    | [b1580e01cb](https://linux-hardware.org/?probe=b1580e01cb) | Jul 10, 2020 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [79aa82328a](https://linux-hardware.org/?probe=79aa82328a) | Jul 10, 2020 |
| HP            | 3646h                       | Desktop     | [717ed10c8e](https://linux-hardware.org/?probe=717ed10c8e) | Jul 09, 2020 |
| Positivo      | N1240                       | Notebook    | [f2e8c91060](https://linux-hardware.org/?probe=f2e8c91060) | Jul 09, 2020 |
| ASRock        | AM2NF3-VSTA                 | Desktop     | [3231309a17](https://linux-hardware.org/?probe=3231309a17) | Jul 09, 2020 |
| Dell          | 048DY8 A01                  | Desktop     | [fc9d7c9dbe](https://linux-hardware.org/?probe=fc9d7c9dbe) | Jul 09, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [c6c58a06a8](https://linux-hardware.org/?probe=c6c58a06a8) | Jul 09, 2020 |
| MSI           | G41M-P33 Combo              | Desktop     | [eb330d82bf](https://linux-hardware.org/?probe=eb330d82bf) | Jul 09, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [9465d6fd4e](https://linux-hardware.org/?probe=9465d6fd4e) | Jul 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [ebd7d22162](https://linux-hardware.org/?probe=ebd7d22162) | Jul 08, 2020 |
| ASRock        | AM2NF3-VSTA                 | Desktop     | [ee27e6e96c](https://linux-hardware.org/?probe=ee27e6e96c) | Jul 08, 2020 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [e70d8ca32d](https://linux-hardware.org/?probe=e70d8ca32d) | Jul 08, 2020 |
| Acer          | Nitro AN517-51              | Notebook    | [c796207530](https://linux-hardware.org/?probe=c796207530) | Jul 08, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [910a91e8d2](https://linux-hardware.org/?probe=910a91e8d2) | Jul 07, 2020 |
| Dell          | Latitude 5285               | Tablet      | [086ab97331](https://linux-hardware.org/?probe=086ab97331) | Jul 06, 2020 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [e7446f8931](https://linux-hardware.org/?probe=e7446f8931) | Jul 06, 2020 |
| Acer          | Aspire MC605 v1.0           | Desktop     | [1ddf75d3b7](https://linux-hardware.org/?probe=1ddf75d3b7) | Jul 06, 2020 |
| PC Special... | N150CU                      | Notebook    | [98055ea3a5](https://linux-hardware.org/?probe=98055ea3a5) | Jul 06, 2020 |
| Dell          | 0DK46J A00                  | All in one  | [bb462bf2f6](https://linux-hardware.org/?probe=bb462bf2f6) | Jul 04, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [da708c50fe](https://linux-hardware.org/?probe=da708c50fe) | Jul 04, 2020 |
| Lenovo        | ThinkPad T590 20N5S2BP00    | Notebook    | [16f6fb2756](https://linux-hardware.org/?probe=16f6fb2756) | Jul 02, 2020 |
| HP            | 3646h                       | Desktop     | [e30378adda](https://linux-hardware.org/?probe=e30378adda) | Jul 01, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 1308      | 51.7%   |
| Kubuntu 20.10   | 264       | 10.43%  |
| Kubuntu 21.10   | 223       | 8.81%   |
| Kubuntu 18.04   | 213       | 8.42%   |
| Kubuntu 21.04   | 212       | 8.38%   |
| Kubuntu 19.10   | 180       | 7.11%   |
| Kubuntu 11      | 36        | 1.42%   |
| Kubuntu 22.04   | 32        | 1.26%   |
| Kubuntu 19.04   | 22        | 0.87%   |
| Kubuntu 16.04   | 12        | 0.47%   |
| Kubuntu         | 8         | 0.32%   |
| Kubuntu 18.10   | 7         | 0.28%   |
| Kubuntu 2.0     | 4         | 0.16%   |
| Kubuntu 17.10   | 3         | 0.12%   |
| Kubuntu 17.04   | 2         | 0.08%   |
| Kubuntu 14.04   | 2         | 0.08%   |
| Kubuntu 20.08.3 | 1         | 0.04%   |
| Kubuntu 12.04   | 1         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Kubuntu | 2424      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 107       | 3.82%   |
| 5.4.0-52-generic  | 73        | 2.61%   |
| 5.4.0-48-generic  | 63        | 2.25%   |
| 5.4.0-58-generic  | 62        | 2.21%   |
| 5.13.0-39-generic | 51        | 1.82%   |
| 5.4.0-40-generic  | 47        | 1.68%   |
| 5.13.0-28-generic | 45        | 1.61%   |
| 5.11.0-37-generic | 44        | 1.57%   |
| 5.11.0-25-generic | 39        | 1.39%   |
| 5.4.0-47-generic  | 38        | 1.36%   |
| 5.13.0-30-generic | 38        | 1.36%   |
| 5.8.0-48-generic  | 37        | 1.32%   |
| 5.4.0-65-generic  | 36        | 1.28%   |
| 5.4.0-37-generic  | 34        | 1.21%   |
| 5.3.0-40-generic  | 34        | 1.21%   |
| 5.4.0-29-generic  | 33        | 1.18%   |
| 5.13.0-22-generic | 33        | 1.18%   |
| 5.8.0-50-generic  | 31        | 1.11%   |
| 5.4.0-45-generic  | 31        | 1.11%   |
| 5.4.0-54-generic  | 30        | 1.07%   |
| 5.13.0-35-generic | 29        | 1.03%   |
| 5.8.0-63-generic  | 28        | 1%      |
| 5.8.0-44-generic  | 27        | 0.96%   |
| 5.3.0-26-generic  | 27        | 0.96%   |
| 5.8.0-43-generic  | 26        | 0.93%   |
| 5.11.0-22-generic | 26        | 0.93%   |
| 5.4.0-26-generic  | 25        | 0.89%   |
| 5.4.0-33-generic  | 24        | 0.86%   |
| 5.3.0-42-generic  | 24        | 0.86%   |
| 5.13.0-27-generic | 24        | 0.86%   |
| 5.11.0-27-generic | 24        | 0.86%   |
| 5.8.0-45-generic  | 23        | 0.82%   |
| 5.4.0-56-generic  | 23        | 0.82%   |
| 5.3.0-51-generic  | 23        | 0.82%   |
| 5.3.0-46-generic  | 23        | 0.82%   |
| 5.13.0-19-generic | 23        | 0.82%   |
| 5.8.0-55-generic  | 22        | 0.79%   |
| 5.4.0-31-generic  | 22        | 0.79%   |
| 5.11.0-38-generic | 22        | 0.79%   |
| 5.8.0-33-generic  | 21        | 0.75%   |
| 5.8.0-53-generic  | 20        | 0.71%   |
| 5.8.0-29-generic  | 20        | 0.71%   |
| 5.4.0-73-generic  | 20        | 0.71%   |
| 5.3.0-24-generic  | 20        | 0.71%   |
| 5.8.0-41-generic  | 19        | 0.68%   |
| 5.4.0-72-generic  | 19        | 0.68%   |
| 5.11.0-16-generic | 19        | 0.68%   |
| 5.8.0-59-generic  | 18        | 0.64%   |
| 5.4.0-66-generic  | 18        | 0.64%   |
| 5.3.0-29-generic  | 18        | 0.64%   |
| 5.11.0-40-generic | 18        | 0.64%   |
| 5.8.0-25-generic  | 17        | 0.61%   |
| 5.11.0-34-generic | 17        | 0.61%   |
| 5.11.0-31-generic | 17        | 0.61%   |
| 5.8.0-26-generic  | 16        | 0.57%   |
| 5.13.0-40-generic | 16        | 0.57%   |
| 5.13.0-20-generic | 16        | 0.57%   |
| 5.4.0-74-generic  | 15        | 0.54%   |
| 5.3.0-23-generic  | 15        | 0.54%   |
| 5.13.0-21-generic | 15        | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 902       | 35%     |
| 5.8.0   | 428       | 16.61%  |
| 5.13.0  | 333       | 12.92%  |
| 5.11.0  | 330       | 12.81%  |
| 5.3.0   | 236       | 9.16%   |
| 4.15.0  | 65        | 2.52%   |
| 5.0.0   | 39        | 1.51%   |
| 5.15.0  | 28        | 1.09%   |
| 5.6.0   | 16        | 0.62%   |
| 5.10.0  | 16        | 0.62%   |
| 4.4.0   | 9         | 0.35%   |
| 4.18.0  | 8         | 0.31%   |
| 5.17.0  | 7         | 0.27%   |
| 5.9.0   | 5         | 0.19%   |
| 5.14.0  | 5         | 0.19%   |
| 5.7.0   | 4         | 0.16%   |
| 4.10.0  | 4         | 0.16%   |
| 5.8.18  | 3         | 0.12%   |
| 5.12.9  | 3         | 0.12%   |
| 5.12.8  | 3         | 0.12%   |
| 5.12.0  | 3         | 0.12%   |
| 4.13.0  | 3         | 0.12%   |
| 5.9.16  | 2         | 0.08%   |
| 5.9.10  | 2         | 0.08%   |
| 5.9.1   | 2         | 0.08%   |
| 5.8.5   | 2         | 0.08%   |
| 5.8.2   | 2         | 0.08%   |
| 5.8.12  | 2         | 0.08%   |
| 5.8.1   | 2         | 0.08%   |
| 5.7.10  | 2         | 0.08%   |
| 5.7.1   | 2         | 0.08%   |
| 5.5.13  | 2         | 0.08%   |
| 5.5.0   | 2         | 0.08%   |
| 5.16.10 | 2         | 0.08%   |
| 5.16.0  | 2         | 0.08%   |
| 5.15.6  | 2         | 0.08%   |
| 5.15.5  | 2         | 0.08%   |
| 5.15.34 | 2         | 0.08%   |
| 5.14.9  | 2         | 0.08%   |
| 5.13.6  | 2         | 0.08%   |
| 5.13.12 | 2         | 0.08%   |
| 5.13.1  | 2         | 0.08%   |
| 5.12.6  | 2         | 0.08%   |
| 5.11.15 | 2         | 0.08%   |
| 5.11.12 | 2         | 0.08%   |
| 5.10.17 | 2         | 0.08%   |
| 5.9.8   | 1         | 0.04%   |
| 5.9.6   | 1         | 0.04%   |
| 5.9.12  | 1         | 0.04%   |
| 5.8.16  | 1         | 0.04%   |
| 5.8.14  | 1         | 0.04%   |
| 5.8.13  | 1         | 0.04%   |
| 5.8.11  | 1         | 0.04%   |
| 5.8.10  | 1         | 0.04%   |
| 5.7.9   | 1         | 0.04%   |
| 5.7.6   | 1         | 0.04%   |
| 5.7.19  | 1         | 0.04%   |
| 5.7.15  | 1         | 0.04%   |
| 5.6.7   | 1         | 0.04%   |
| 5.6.17  | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 909       | 35.36%  |
| 5.8     | 444       | 17.27%  |
| 5.13    | 344       | 13.38%  |
| 5.11    | 336       | 13.07%  |
| 5.3     | 239       | 9.3%    |
| 4.15    | 66        | 2.57%   |
| 5.15    | 40        | 1.56%   |
| 5.0     | 40        | 1.56%   |
| 5.10    | 26        | 1.01%   |
| 5.6     | 20        | 0.78%   |
| 5.9     | 14        | 0.54%   |
| 5.14    | 14        | 0.54%   |
| 5.12    | 14        | 0.54%   |
| 5.7     | 12        | 0.47%   |
| 4.18    | 10        | 0.39%   |
| 5.17    | 9         | 0.35%   |
| 4.4     | 9         | 0.35%   |
| 5.16    | 7         | 0.27%   |
| 5.5     | 6         | 0.23%   |
| 4.10    | 4         | 0.16%   |
| 4.13    | 3         | 0.12%   |
| 5.1     | 2         | 0.08%   |
| 4.17    | 1         | 0.04%   |
| 4.12    | 1         | 0.04%   |
| 3.13    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2410      | 99.42%  |
| i686    | 12        | 0.5%    |
| aarch64 | 2         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 1499      | 60.69%  |
| KDE      | 935       | 37.85%  |
| GNOME    | 8         | 0.32%   |
| Cinnamon | 8         | 0.32%   |
| Budgie   | 7         | 0.28%   |
| MATE     | 4         | 0.16%   |
| KDE4     | 3         | 0.12%   |
| XFCE     | 2         | 0.08%   |
| LXQt     | 2         | 0.08%   |
| Unity    | 1         | 0.04%   |
| Unknown  | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2351      | 96.55%  |
| Wayland | 61        | 2.51%   |
| Tty     | 23        | 0.94%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1286      | 52.09%  |
| Unknown | 1005      | 40.7%   |
| GDM     | 104       | 4.21%   |
| LightDM | 33        | 1.34%   |
| TDM     | 25        | 1.01%   |
| GDM3    | 15        | 0.61%   |
| SLiM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 957       | 39%     |
| de_DE   | 197       | 8.03%   |
| ru_RU   | 141       | 5.75%   |
| en_GB   | 130       | 5.3%    |
| pt_BR   | 126       | 5.13%   |
| fr_FR   | 106       | 4.32%   |
| it_IT   | 84        | 3.42%   |
| Unknown | 78        | 3.18%   |
| en_CA   | 59        | 2.4%    |
| es_ES   | 48        | 1.96%   |
| en_AU   | 48        | 1.96%   |
| en_IN   | 45        | 1.83%   |
| pl_PL   | 44        | 1.79%   |
| C       | 28        | 1.14%   |
| ru_UA   | 22        | 0.9%    |
| hu_HU   | 20        | 0.81%   |
| es_MX   | 20        | 0.81%   |
| de_CH   | 17        | 0.69%   |
| en_ZA   | 15        | 0.61%   |
| cs_CZ   | 15        | 0.61%   |
| es_AR   | 14        | 0.57%   |
| de_AT   | 13        | 0.53%   |
| en_NZ   | 11        | 0.45%   |
| nl_NL   | 10        | 0.41%   |
| sv_SE   | 9         | 0.37%   |
| pt_PT   | 9         | 0.37%   |
| en_IE   | 9         | 0.37%   |
| uk_UA   | 7         | 0.29%   |
| tr_TR   | 7         | 0.29%   |
| sk_SK   | 7         | 0.29%   |
| fi_FI   | 7         | 0.29%   |
| es_VE   | 7         | 0.29%   |
| es_CO   | 7         | 0.29%   |
| es_CL   | 7         | 0.29%   |
| en_IL   | 7         | 0.29%   |
| el_GR   | 7         | 0.29%   |
| ca_ES   | 7         | 0.29%   |
| nl_BE   | 6         | 0.24%   |
| zh_CN   | 5         | 0.2%    |
| sl_SI   | 5         | 0.2%    |
| ro_RO   | 5         | 0.2%    |
| ja_JP   | 5         | 0.2%    |
| fr_CH   | 5         | 0.2%    |
| fr_BE   | 4         | 0.16%   |
| en_DK   | 4         | 0.16%   |
| en_DE   | 4         | 0.16%   |
| da_DK   | 4         | 0.16%   |
| zh_TW   | 3         | 0.12%   |
| fr_CA   | 3         | 0.12%   |
| es_UY   | 3         | 0.12%   |
| es_PE   | 3         | 0.12%   |
| en_NL   | 3         | 0.12%   |
| en_NG   | 3         | 0.12%   |
| bg_BG   | 3         | 0.12%   |
| be_BY   | 3         | 0.12%   |
| sr_RS   | 2         | 0.08%   |
| nb_NO   | 2         | 0.08%   |
| ko_KR   | 2         | 0.08%   |
| id_ID   | 2         | 0.08%   |
| hr_HR   | 2         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1414      | 57.34%  |
| BIOS | 1052      | 42.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2228      | 91.2%   |
| Btrfs    | 103       | 4.22%   |
| Overlay  | 50        | 2.05%   |
| Xfs      | 27        | 1.11%   |
| Zfs      | 15        | 0.61%   |
| Unknown  | 13        | 0.53%   |
| Ext2     | 2         | 0.08%   |
| XXXX     | 1         | 0.04%   |
| Reiserfs | 1         | 0.04%   |
| Jfs      | 1         | 0.04%   |
| ExX4     | 1         | 0.04%   |
| Ext3     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1166      | 47.51%  |
| GPT     | 1039      | 42.34%  |
| MBR     | 249       | 10.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2127      | 86.78%  |
| Yes       | 324       | 13.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1493      | 60.74%  |
| Yes       | 965       | 39.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 402       | 16.58%  |
| Lenovo                 | 361       | 14.89%  |
| Dell                   | 351       | 14.48%  |
| Hewlett-Packard        | 323       | 13.33%  |
| Gigabyte Technology    | 189       | 7.8%    |
| MSI                    | 169       | 6.97%   |
| Acer                   | 106       | 4.37%   |
| ASRock                 | 98        | 4.04%   |
| Samsung Electronics    | 32        | 1.32%   |
| Apple                  | 30        | 1.24%   |
| Intel                  | 27        | 1.11%   |
| Unknown                | 23        | 0.95%   |
| HUAWEI                 | 22        | 0.91%   |
| Sony                   | 16        | 0.66%   |
| TUXEDO                 | 15        | 0.62%   |
| Toshiba                | 15        | 0.62%   |
| Notebook               | 14        | 0.58%   |
| Fujitsu                | 14        | 0.58%   |
| Pegatron               | 12        | 0.5%    |
| Timi                   | 10        | 0.41%   |
| Google                 | 10        | 0.41%   |
| Positivo               | 9         | 0.37%   |
| ZOTAC                  | 8         | 0.33%   |
| Packard Bell           | 8         | 0.33%   |
| Foxconn                | 8         | 0.33%   |
| Biostar                | 8         | 0.33%   |
| Alienware              | 8         | 0.33%   |
| Medion                 | 7         | 0.29%   |
| ECS                    | 7         | 0.29%   |
| Microsoft              | 6         | 0.25%   |
| PC Specialist          | 5         | 0.21%   |
| LG Electronics         | 5         | 0.21%   |
| Huanan                 | 5         | 0.21%   |
| Fujitsu Siemens        | 5         | 0.21%   |
| Chuwi                  | 5         | 0.21%   |
| System76               | 4         | 0.17%   |
| Hampoo                 | 4         | 0.17%   |
| Gateway                | 4         | 0.17%   |
| Supermicro             | 3         | 0.12%   |
| Schenker               | 3         | 0.12%   |
| Razer                  | 3         | 0.12%   |
| Panasonic              | 3         | 0.12%   |
| Avell High Performance | 3         | 0.12%   |
| Wortmann AG            | 2         | 0.08%   |
| Shuttle                | 2         | 0.08%   |
| Purism                 | 2         | 0.08%   |
| GPU Company            | 2         | 0.08%   |
| Entroware              | 2         | 0.08%   |
| Digma                  | 2         | 0.08%   |
| Clevo                  | 2         | 0.08%   |
| BESSTAR Tech           | 2         | 0.08%   |
| BANGHO                 | 2         | 0.08%   |
| XFX                    | 1         | 0.04%   |
| Wistron                | 1         | 0.04%   |
| WeiBu                  | 1         | 0.04%   |
| VERO                   | 1         | 0.04%   |
| UNOWHY                 | 1         | 0.04%   |
| TYAN Computer          | 1         | 0.04%   |
| Thomson                | 1         | 0.04%   |
| Teclast                | 1         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| ASUS All Series                           | 31        | 1.28%   |
| Unknown                                   | 30        | 1.24%   |
| MSI MS-7C37                               | 8         | 0.33%   |
| ASUS ROG STRIX B550-F GAMING              | 8         | 0.33%   |
| ASUS PRIME B450M-A                        | 8         | 0.33%   |
| HUAWEI NBLK-WAX9X                         | 7         | 0.29%   |
| HP Pavilion dv6                           | 7         | 0.29%   |
| HP Notebook                               | 7         | 0.29%   |
| Dell OptiPlex 9020                        | 7         | 0.29%   |
| MSI MS-7817                               | 6         | 0.25%   |
| HP Pavilion g6                            | 6         | 0.25%   |
| Gigabyte B450M DS3H                       | 6         | 0.25%   |
| Gigabyte 970A-DS3P                        | 6         | 0.25%   |
| ASUS ROG STRIX X570-E GAMING              | 6         | 0.25%   |
| ASUS PRIME B350-PLUS                      | 6         | 0.25%   |
| MSI MS-7C02                               | 5         | 0.21%   |
| MSI MS-7B79                               | 5         | 0.21%   |
| MSI MS-7A34                               | 5         | 0.21%   |
| HP Pavilion 15                            | 5         | 0.21%   |
| HP EliteBook 840 G5                       | 5         | 0.21%   |
| HP EliteBook 840 G3                       | 5         | 0.21%   |
| Gigabyte X570 AORUS MASTER                | 5         | 0.21%   |
| Gigabyte A320M-S2H                        | 5         | 0.21%   |
| Dell XPS 15 9570                          | 5         | 0.21%   |
| Dell XPS 15 9560                          | 5         | 0.21%   |
| Dell XPS 15 7590                          | 5         | 0.21%   |
| Dell XPS 13 9310                          | 5         | 0.21%   |
| Dell Latitude 5480                        | 5         | 0.21%   |
| ASRock AB350 Pro4                         | 5         | 0.21%   |
| Lenovo Legion Y530-15ICH 81FV             | 4         | 0.17%   |
| Lenovo IdeaPad 330-15IKB 81DE             | 4         | 0.17%   |
| HP Pavilion dv7                           | 4         | 0.17%   |
| HP Laptop 15s-eq0xxx                      | 4         | 0.17%   |
| HP EliteBook 840 G6                       | 4         | 0.17%   |
| Gigabyte A320M-S2H V2                     | 4         | 0.17%   |
| Gigabyte A320M-H                          | 4         | 0.17%   |
| Dell XPS 15 9500                          | 4         | 0.17%   |
| Dell Latitude E6540                       | 4         | 0.17%   |
| Dell Latitude 7480                        | 4         | 0.17%   |
| Dell Latitude 5580                        | 4         | 0.17%   |
| Dell Inspiron 7559                        | 4         | 0.17%   |
| Dell Inspiron 3847                        | 4         | 0.17%   |
| Dell G3 3579                              | 4         | 0.17%   |
| ASUS TUF X470-PLUS GAMING                 | 4         | 0.17%   |
| ASUS TUF GAMING X570-PLUS                 | 4         | 0.17%   |
| ZOTAC ZBOX-CI620/CI640/CI660              | 3         | 0.12%   |
| TUXEDO Pulse 15 Gen1                      | 3         | 0.12%   |
| Samsung 300E4C/300E5C/300E7C              | 3         | 0.12%   |
| MSI MS-7C94                               | 3         | 0.12%   |
| MSI MS-7C91                               | 3         | 0.12%   |
| MSI MS-7C52                               | 3         | 0.12%   |
| MSI MS-7B93                               | 3         | 0.12%   |
| MSI MS-7B89                               | 3         | 0.12%   |
| MSI MS-7A33                               | 3         | 0.12%   |
| MSI MS-7996                               | 3         | 0.12%   |
| MSI MS-7758                               | 3         | 0.12%   |
| MSI MS-7693                               | 3         | 0.12%   |
| Microsoft Surface Pro 3                   | 3         | 0.12%   |
| Lenovo Z50-75 80EC                        | 3         | 0.12%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVS0FP00 | 3         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 178       | 7.34%   |
| Dell Latitude         | 97        | 4%      |
| Dell Inspiron         | 93        | 3.84%   |
| Acer Aspire           | 72        | 2.97%   |
| HP Pavilion           | 69        | 2.85%   |
| Lenovo IdeaPad        | 63        | 2.6%    |
| Dell XPS              | 54        | 2.23%   |
| ASUS PRIME            | 53        | 2.19%   |
| ASUS ROG              | 48        | 1.98%   |
| HP ProBook            | 39        | 1.61%   |
| HP EliteBook          | 39        | 1.61%   |
| HP Laptop             | 36        | 1.49%   |
| Dell OptiPlex         | 32        | 1.32%   |
| Dell Precision        | 31        | 1.28%   |
| ASUS All              | 31        | 1.28%   |
| ASUS VivoBook         | 30        | 1.24%   |
| Unknown               | 30        | 1.24%   |
| HP Compaq             | 25        | 1.03%   |
| ASUS TUF              | 25        | 1.03%   |
| HP ENVY               | 20        | 0.83%   |
| Dell Vostro           | 20        | 0.83%   |
| Lenovo Yoga           | 17        | 0.7%    |
| Lenovo ThinkCentre    | 17        | 0.7%    |
| Lenovo Legion         | 14        | 0.58%   |
| Toshiba Satellite     | 13        | 0.54%   |
| Gigabyte X570         | 12        | 0.5%    |
| Gigabyte B450M        | 12        | 0.5%    |
| ASUS ZenBook          | 12        | 0.5%    |
| Lenovo ThinkBook      | 11        | 0.45%   |
| ASUS ASUS             | 11        | 0.45%   |
| Acer Swift            | 10        | 0.41%   |
| Acer Nitro            | 10        | 0.41%   |
| Gigabyte A320M-S2H    | 9         | 0.37%   |
| MSI MS-7C37           | 8         | 0.33%   |
| Gigabyte B550         | 8         | 0.33%   |
| HUAWEI NBLK-WAX9X     | 7         | 0.29%   |
| HP ZBook              | 7         | 0.29%   |
| HP Notebook           | 7         | 0.29%   |
| Dell Studio           | 7         | 0.29%   |
| ASRock AB350          | 7         | 0.29%   |
| MSI MS-7817           | 6         | 0.25%   |
| Microsoft Surface     | 6         | 0.25%   |
| HP Spectre            | 6         | 0.25%   |
| HP EliteDesk          | 6         | 0.25%   |
| HP 250                | 6         | 0.25%   |
| Gigabyte 970A-DS3P    | 6         | 0.25%   |
| Fujitsu ESPRIMO       | 6         | 0.25%   |
| Dell G3               | 6         | 0.25%   |
| MSI Prestige          | 5         | 0.21%   |
| MSI MS-7C02           | 5         | 0.21%   |
| MSI MS-7B79           | 5         | 0.21%   |
| MSI MS-7A34           | 5         | 0.21%   |
| HP ProDesk            | 5         | 0.21%   |
| HP OMEN               | 5         | 0.21%   |
| HP 15                 | 5         | 0.21%   |
| ASUS STRIX            | 5         | 0.21%   |
| ASUS SABERTOOTH       | 5         | 0.21%   |
| ASUS M5A78L-M         | 5         | 0.21%   |
| Packard Bell EasyNote | 4         | 0.17%   |
| MSI Modern            | 4         | 0.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 340       | 14.03%  |
| 2018    | 293       | 12.09%  |
| 2020    | 285       | 11.76%  |
| 2017    | 212       | 8.75%   |
| 2012    | 175       | 7.22%   |
| 2013    | 174       | 7.18%   |
| 2011    | 169       | 6.97%   |
| 2014    | 156       | 6.44%   |
| 2016    | 120       | 4.95%   |
| 2021    | 117       | 4.83%   |
| 2015    | 116       | 4.79%   |
| 2010    | 88        | 3.63%   |
| 2009    | 69        | 2.85%   |
| 2008    | 68        | 2.81%   |
| 2007    | 26        | 1.07%   |
| 2006    | 10        | 0.41%   |
| Unknown | 3         | 0.12%   |
| 2005    | 2         | 0.08%   |
| 2022    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1337      | 55.16%  |
| Desktop        | 928       | 38.28%  |
| Convertible    | 71        | 2.93%   |
| Mini pc        | 31        | 1.28%   |
| All in one     | 29        | 1.2%    |
| Tablet         | 16        | 0.66%   |
| Server         | 10        | 0.41%   |
| System on chip | 2         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2239      | 91.84%  |
| Enabled  | 199       | 8.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2409      | 99.38%  |
| Yes  | 15        | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 627       | 25.65%  |
| 4.01-8.0    | 551       | 22.55%  |
| 8.01-16.0   | 462       | 18.9%   |
| 3.01-4.0    | 316       | 12.93%  |
| 32.01-64.0  | 303       | 12.4%   |
| 64.01-256.0 | 64        | 2.62%   |
| 24.01-32.0  | 61        | 2.5%    |
| 1.01-2.0    | 45        | 1.84%   |
| 2.01-3.0    | 15        | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 692       | 26.26%  |
| 1.01-2.0   | 644       | 24.44%  |
| 4.01-8.0   | 586       | 22.24%  |
| 3.01-4.0   | 390       | 14.8%   |
| 8.01-16.0  | 198       | 7.51%   |
| 0.51-1.0   | 77        | 2.92%   |
| 16.01-24.0 | 28        | 1.06%   |
| 24.01-32.0 | 10        | 0.38%   |
| 32.01-64.0 | 5         | 0.19%   |
| 0.01-0.5   | 4         | 0.15%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1326      | 53.27%  |
| 2      | 672       | 27%     |
| 3      | 229       | 9.2%    |
| 4      | 130       | 5.22%   |
| 5      | 62        | 2.49%   |
| 6      | 29        | 1.17%   |
| 7      | 15        | 0.6%    |
| 0      | 10        | 0.4%    |
| 8      | 5         | 0.2%    |
| 9      | 4         | 0.16%   |
| 10     | 3         | 0.12%   |
| 12     | 2         | 0.08%   |
| 13     | 1         | 0.04%   |
| 11     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1591      | 65.23%  |
| Yes       | 848       | 34.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2090      | 86.08%  |
| No        | 338       | 13.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1835      | 75.39%  |
| No        | 599       | 24.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1578      | 64.51%  |
| No        | 868       | 35.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 424       | 17.47%  |
| Germany      | 270       | 11.12%  |
| Russia       | 197       | 8.12%   |
| Brazil       | 166       | 6.84%   |
| France       | 133       | 5.48%   |
| UK           | 110       | 4.53%   |
| Italy        | 104       | 4.29%   |
| Spain        | 73        | 3.01%   |
| Canada       | 65        | 2.68%   |
| Ukraine      | 59        | 2.43%   |
| Poland       | 57        | 2.35%   |
| Netherlands  | 57        | 2.35%   |
| Australia    | 47        | 1.94%   |
| India        | 46        | 1.9%    |
| Switzerland  | 36        | 1.48%   |
| Mexico       | 34        | 1.4%    |
| Hungary      | 33        | 1.36%   |
| Czechia      | 28        | 1.15%   |
| Belgium      | 23        | 0.95%   |
| Argentina    | 22        | 0.91%   |
| Austria      | 21        | 0.87%   |
| Greece       | 20        | 0.82%   |
| Finland      | 18        | 0.74%   |
| Turkey       | 17        | 0.7%    |
| Sweden       | 17        | 0.7%    |
| South Africa | 17        | 0.7%    |
| Romania      | 15        | 0.62%   |
| Indonesia    | 15        | 0.62%   |
| Bulgaria     | 15        | 0.62%   |
| Colombia     | 12        | 0.49%   |
| Belarus      | 12        | 0.49%   |
| Slovenia     | 11        | 0.45%   |
| Serbia       | 11        | 0.45%   |
| Ireland      | 11        | 0.45%   |
| Denmark      | 11        | 0.45%   |
| China        | 11        | 0.45%   |
| Slovakia     | 10        | 0.41%   |
| Portugal     | 10        | 0.41%   |
| Norway       | 10        | 0.41%   |
| New Zealand  | 10        | 0.41%   |
| Iran         | 10        | 0.41%   |
| Israel       | 9         | 0.37%   |
| Chile        | 8         | 0.33%   |
| Venezuela    | 7         | 0.29%   |
| Japan        | 7         | 0.29%   |
| Croatia      | 7         | 0.29%   |
| Vietnam      | 6         | 0.25%   |
| Pakistan     | 6         | 0.25%   |
| Estonia      | 6         | 0.25%   |
| Bangladesh   | 6         | 0.25%   |
| Taiwan       | 5         | 0.21%   |
| Nigeria      | 5         | 0.21%   |
| Uruguay      | 4         | 0.16%   |
| Thailand     | 4         | 0.16%   |
| South Korea  | 4         | 0.16%   |
| Saudi Arabia | 4         | 0.16%   |
| Peru         | 4         | 0.16%   |
| Kazakhstan   | 4         | 0.16%   |
| Singapore    | 3         | 0.12%   |
| Hong Kong    | 3         | 0.12%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 55        | 2.16%   |
| Berlin            | 27        | 1.06%   |
| Paris             | 22        | 0.86%   |
| St Petersburg     | 21        | 0.82%   |
| Rome              | 21        | 0.82%   |
| Hamburg           | 20        | 0.79%   |
| Budapest          | 19        | 0.75%   |
| Sao Paulo         | 18        | 0.71%   |
| Kyiv              | 17        | 0.67%   |
| London            | 16        | 0.63%   |
| Warsaw            | 15        | 0.59%   |
| Sydney            | 12        | 0.47%   |
| Rio de Janeiro    | 12        | 0.47%   |
| Madrid            | 12        | 0.47%   |
| Zurich            | 11        | 0.43%   |
| Vienna            | 11        | 0.43%   |
| Frankfurt am Main | 11        | 0.43%   |
| Novosibirsk       | 10        | 0.39%   |
| Minsk             | 10        | 0.39%   |
| Milan             | 10        | 0.39%   |
| Cologne           | 10        | 0.39%   |
| Athens            | 10        | 0.39%   |
| Amsterdam         | 10        | 0.39%   |
| Sofia             | 9         | 0.35%   |
| Prague            | 9         | 0.35%   |
| Munich            | 9         | 0.35%   |
| Los Angeles       | 9         | 0.35%   |
| Belgrade          | 9         | 0.35%   |
| St. Gallen        | 8         | 0.31%   |
| Krakow            | 8         | 0.31%   |
| Helsinki          | 8         | 0.31%   |
| Toronto           | 7         | 0.27%   |
| Phoenix           | 7         | 0.27%   |
| Melbourne         | 7         | 0.27%   |
| Jakarta           | 7         | 0.27%   |
| Istanbul          | 7         | 0.27%   |
| Dublin            | 7         | 0.27%   |
| Curitiba          | 7         | 0.27%   |
| Buenos Aires      | 7         | 0.27%   |
| Valencia          | 6         | 0.24%   |
| Montreal          | 6         | 0.24%   |
| Manchester        | 6         | 0.24%   |
| Leipzig           | 6         | 0.24%   |
| Dallas            | 6         | 0.24%   |
| Cape Town         | 6         | 0.24%   |
| Bucharest         | 6         | 0.24%   |
| Zagreb            | 5         | 0.2%    |
| Yekaterinburg     | 5         | 0.2%    |
| Seattle           | 5         | 0.2%    |
| San Jose          | 5         | 0.2%    |
| San Francisco     | 5         | 0.2%    |
| Portland          | 5         | 0.2%    |
| Odessa            | 5         | 0.2%    |
| Mexico City       | 5         | 0.2%    |
| Lagos             | 5         | 0.2%    |
| Krasnodar         | 5         | 0.2%    |
| Guadalajara       | 5         | 0.2%    |
| Chicago           | 5         | 0.2%    |
| Chennai           | 5         | 0.2%    |
| Bonn              | 5         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 703       | 1078   | 18.39%  |
| WDC                            | 608       | 1007   | 15.91%  |
| Seagate                        | 541       | 781    | 14.15%  |
| Toshiba                        | 229       | 301    | 5.99%   |
| Kingston                       | 221       | 270    | 5.78%   |
| SanDisk                        | 183       | 218    | 4.79%   |
| Crucial                        | 150       | 186    | 3.92%   |
| Unknown                        | 131       | 164    | 3.43%   |
| Intel                          | 116       | 160    | 3.04%   |
| Hitachi                        | 105       | 133    | 2.75%   |
| SK Hynix                       | 92        | 108    | 2.41%   |
| HGST                           | 75        | 96     | 1.96%   |
| A-DATA Technology              | 58        | 63     | 1.52%   |
| Micron Technology              | 54        | 61     | 1.41%   |
| Phison                         | 32        | 45     | 0.84%   |
| KIOXIA                         | 26        | 29     | 0.68%   |
| Silicon Motion                 | 25        | 29     | 0.65%   |
| Transcend                      | 24        | 25     | 0.63%   |
| China                          | 23        | 32     | 0.6%    |
| OCZ                            | 21        | 27     | 0.55%   |
| SPCC                           | 20        | 24     | 0.52%   |
| LITEON                         | 19        | 21     | 0.5%    |
| Intenso                        | 19        | 22     | 0.5%    |
| PNY                            | 18        | 21     | 0.47%   |
| Apple                          | 18        | 20     | 0.47%   |
| Patriot                        | 17        | 22     | 0.44%   |
| MAXTOR                         | 14        | 15     | 0.37%   |
| Corsair                        | 14        | 17     | 0.37%   |
| GOODRAM                        | 13        | 30     | 0.34%   |
| XPG                            | 12        | 13     | 0.31%   |
| KingSpec                       | 12        | 14     | 0.31%   |
| Fujitsu                        | 12        | 16     | 0.31%   |
| JMicron                        | 11        | 13     | 0.29%   |
| LITEONIT                       | 10        | 12     | 0.26%   |
| Team                           | 9         | 10     | 0.24%   |
| SABRENT                        | 8         | 9      | 0.21%   |
| Mushkin                        | 8         | 8      | 0.21%   |
| Apacer                         | 8         | 15     | 0.21%   |
| Gigabyte Technology            | 7         | 8      | 0.18%   |
| ASMT                           | 7         | 8      | 0.18%   |
| Unknown                        | 7         | 7      | 0.18%   |
| Realtek Semiconductor          | 6         | 6      | 0.16%   |
| Hewlett-Packard                | 5         | 7      | 0.13%   |
| Verbatim                       | 4         | 4      | 0.1%    |
| Union Memory                   | 4         | 4      | 0.1%    |
| PLEXTOR                        | 4         | 5      | 0.1%    |
| Micron/Crucial Technology      | 4         | 5      | 0.1%    |
| Lenovo                         | 4         | 4      | 0.1%    |
| LDLC                           | 4         | 10     | 0.1%    |
| KingDian                       | 4         | 5      | 0.1%    |
| Zheino                         | 3         | 5      | 0.08%   |
| TO Exter                       | 3         | 3      | 0.08%   |
| SSSTC                          | 3         | 3      | 0.08%   |
| Solid State Storage Technology | 3         | 5      | 0.08%   |
| Lite-On                        | 3         | 3      | 0.08%   |
| Lexar                          | 3         | 3      | 0.08%   |
| EMTEC                          | 3         | 3      | 0.08%   |
| AMD                            | 3         | 3      | 0.08%   |
| VENO                           | 2         | 5      | 0.05%   |
| TCSUNBOW                       | 2         | 4      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 43        | 1%      |
| Samsung SSD 850 EVO 250GB          | 38        | 0.88%   |
| Samsung SSD 850 EVO 500GB          | 35        | 0.81%   |
| Kingston SA400S37240G 240GB SSD    | 32        | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 31        | 0.72%   |
| Samsung SSD 860 EVO 1TB            | 31        | 0.72%   |
| Samsung NVMe SSD Drive 500GB       | 29        | 0.67%   |
| Kingston SA400S37480G 480GB SSD    | 29        | 0.67%   |
| Samsung NVMe SSD Drive 1TB         | 28        | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB     | 26        | 0.6%    |
| Samsung NVMe SSD Drive 512GB       | 25        | 0.58%   |
| Unknown MMC Card  32GB             | 24        | 0.56%   |
| Toshiba MQ04ABF100 1TB             | 23        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB        | 22        | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB           | 21        | 0.49%   |
| Toshiba MQ01ABD100 1TB             | 21        | 0.49%   |
| Seagate ST1000DM010-2EP102 1TB     | 21        | 0.49%   |
| Samsung SSD 970 EVO Plus 500GB     | 20        | 0.46%   |
| HGST HTS721010A9E630 1TB           | 20        | 0.46%   |
| Samsung SSD 860 EVO 250GB          | 18        | 0.42%   |
| Unknown MMC Card  64GB             | 17        | 0.39%   |
| Seagate ST500DM002-1BD142 500GB    | 17        | 0.39%   |
| SanDisk SSD PLUS 240GB             | 17        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB       | 17        | 0.39%   |
| Unknown SD/MMC/MS PRO 16GB         | 16        | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB     | 16        | 0.37%   |
| Seagate Expansion+ 2TB             | 16        | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 15        | 0.35%   |
| Toshiba HDWD110 1TB                | 15        | 0.35%   |
| Seagate ST500LT012-1DG142 500GB    | 15        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB     | 15        | 0.35%   |
| Kingston SA400S37120G 120GB SSD    | 15        | 0.35%   |
| Seagate ST2000DM008-2FR102 2TB     | 14        | 0.32%   |
| Seagate ST2000DM001-1ER164 2TB     | 14        | 0.32%   |
| Sandisk NVMe SSD Drive 512GB       | 14        | 0.32%   |
| Toshiba MQ01ABF050 500GB           | 13        | 0.3%    |
| Seagate ST2000DM006-2DM164 2TB     | 13        | 0.3%    |
| Seagate ST1000LM048-2E7172 1TB     | 13        | 0.3%    |
| Sandisk NVMe SSD Drive 256GB       | 13        | 0.3%    |
| Samsung SSD 860 EVO M.2 500GB      | 13        | 0.3%    |
| Kingston SV300S37A120G 120GB SSD   | 13        | 0.3%    |
| Kingston SUV400S37240G 240GB SSD   | 13        | 0.3%    |
| Crucial CT500MX500SSD1 500GB       | 13        | 0.3%    |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 12        | 0.28%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 12        | 0.28%   |
| Seagate ST3500418AS 500GB          | 12        | 0.28%   |
| Seagate ST2000DM001-1CH164 2TB     | 12        | 0.28%   |
| Samsung SSD 860 QVO 1TB            | 12        | 0.28%   |
| Kingston SV300S37A240G 240GB SSD   | 12        | 0.28%   |
| HGST HTS541010A9E680 1TB           | 12        | 0.28%   |
| WDC WD20EARX-00PASB0 2TB           | 11        | 0.26%   |
| WDC WD10SPZX-21Z10T0 1TB           | 11        | 0.26%   |
| Unknown MMC Card  128GB            | 11        | 0.26%   |
| Toshiba DT01ACA100 1TB             | 11        | 0.26%   |
| Seagate ST4000DM004-2CV104 4TB     | 11        | 0.26%   |
| Seagate ST3500413AS 500GB          | 11        | 0.26%   |
| Seagate ST31000524AS 1TB           | 11        | 0.26%   |
| Seagate Expansion Desk 4TB         | 11        | 0.26%   |
| Samsung SSD 970 EVO 1TB            | 11        | 0.26%   |
| Intel SSDPEKNW512G8 512GB          | 11        | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 531       | 759    | 35.33%  |
| WDC                 | 473       | 814    | 31.47%  |
| Toshiba             | 164       | 216    | 10.91%  |
| Hitachi             | 105       | 133    | 6.99%   |
| Samsung Electronics | 80        | 128    | 5.32%   |
| HGST                | 74        | 95     | 4.92%   |
| Unknown             | 19        | 21     | 1.26%   |
| MAXTOR              | 14        | 15     | 0.93%   |
| Fujitsu             | 11        | 15     | 0.73%   |
| SABRENT             | 8         | 9      | 0.53%   |
| Apple               | 8         | 8      | 0.53%   |
| ASMT                | 5         | 6      | 0.33%   |
| Hewlett-Packard     | 3         | 6      | 0.2%    |
| WD MediaMax         | 1         | 1      | 0.07%   |
| USB                 | 1         | 1      | 0.07%   |
| sage                | 1         | 1      | 0.07%   |
| LIO-ORG             | 1         | 1      | 0.07%   |
| LaCie               | 1         | 1      | 0.07%   |
| JMicron             | 1         | 1      | 0.07%   |
| ipTIME              | 1         | 1      | 0.07%   |
| ASMedia             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 375       | 519    | 27.86%  |
| Kingston            | 175       | 217    | 13%     |
| SanDisk             | 132       | 155    | 9.81%   |
| Crucial             | 129       | 163    | 9.58%   |
| WDC                 | 72        | 91     | 5.35%   |
| Intel               | 40        | 50     | 2.97%   |
| A-DATA Technology   | 40        | 44     | 2.97%   |
| Micron Technology   | 27        | 30     | 2.01%   |
| Toshiba             | 23        | 34     | 1.71%   |
| China               | 23        | 32     | 1.71%   |
| SK Hynix            | 22        | 24     | 1.63%   |
| OCZ                 | 21        | 27     | 1.56%   |
| Transcend           | 20        | 20     | 1.49%   |
| SPCC                | 18        | 21     | 1.34%   |
| Intenso             | 18        | 20     | 1.34%   |
| Patriot             | 17        | 22     | 1.26%   |
| PNY                 | 16        | 19     | 1.19%   |
| LITEON              | 14        | 15     | 1.04%   |
| GOODRAM             | 13        | 30     | 0.97%   |
| KingSpec            | 12        | 14     | 0.89%   |
| LITEONIT            | 10        | 12     | 0.74%   |
| Team                | 8         | 8      | 0.59%   |
| CORSAIR             | 8         | 10     | 0.59%   |
| Apacer              | 8         | 15     | 0.59%   |
| Mushkin             | 7         | 7      | 0.52%   |
| Apple               | 6         | 6      | 0.45%   |
| JMicron             | 5         | 6      | 0.37%   |
| Verbatim            | 4         | 4      | 0.3%    |
| Seagate             | 4         | 9      | 0.3%    |
| KingDian            | 4         | 5      | 0.3%    |
| Zheino              | 3         | 5      | 0.22%   |
| Unknown             | 3         | 4      | 0.22%   |
| TO Exter            | 3         | 3      | 0.22%   |
| PLEXTOR             | 3         | 4      | 0.22%   |
| Lexar               | 3         | 3      | 0.22%   |
| Gigabyte Technology | 3         | 3      | 0.22%   |
| EMTEC               | 3         | 3      | 0.22%   |
| Unknown             | 3         | 3      | 0.22%   |
| VENO                | 2         | 5      | 0.15%   |
| TCSUNBOW            | 2         | 4      | 0.15%   |
| Super Talent        | 2         | 2      | 0.15%   |
| Smartbuy            | 2         | 3      | 0.15%   |
| Netac               | 2         | 2      | 0.15%   |
| Leven               | 2         | 3      | 0.15%   |
| LDLC                | 2         | 2      | 0.15%   |
| DREVO               | 2         | 2      | 0.15%   |
| BHT                 | 2         | 3      | 0.15%   |
| ASMT                | 2         | 2      | 0.15%   |
| AMD                 | 2         | 2      | 0.15%   |
| AEGO                | 2         | 3      | 0.15%   |
| WDC WDS4            | 1         | 1      | 0.07%   |
| Vaseky              | 1         | 1      | 0.07%   |
| Varro               | 1         | 1      | 0.07%   |
| TUSUNBOW            | 1         | 1      | 0.07%   |
| Teclast             | 1         | 1      | 0.07%   |
| StoreJet            | 1         | 1      | 0.07%   |
| SMI                 | 1         | 1      | 0.07%   |
| ShanDianZhe         | 1         | 2      | 0.07%   |
| S3                  | 1         | 1      | 0.07%   |
| RZX                 | 1         | 1      | 0.07%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1205      | 2233   | 35.63%  |
| SSD     | 1156      | 1721   | 34.18%  |
| NVMe    | 864       | 1156   | 25.55%  |
| MMC     | 108       | 137    | 3.19%   |
| Unknown | 49        | 68     | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1825      | 3818   | 62.01%  |
| NVMe | 864       | 1154   | 29.36%  |
| SAS  | 146       | 206    | 4.96%   |
| MMC  | 108       | 137    | 3.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1294      | 2027   | 50.8%   |
| 0.51-1.0   | 816       | 1242   | 32.04%  |
| 1.01-2.0   | 254       | 385    | 9.97%   |
| 3.01-4.0   | 84        | 152    | 3.3%    |
| 2.01-3.0   | 61        | 88     | 2.39%   |
| 4.01-10.0  | 34        | 52     | 1.33%   |
| 10.01-20.0 | 4         | 8      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 640       | 25.47%  |
| 251-500        | 618       | 24.59%  |
| 501-1000       | 456       | 18.15%  |
| 1001-2000      | 245       | 9.75%   |
| More than 3000 | 183       | 7.28%   |
| 51-100         | 130       | 5.17%   |
| 2001-3000      | 108       | 4.3%    |
| 21-50          | 65        | 2.59%   |
| 1-20           | 59        | 2.35%   |
| Unknown        | 9         | 0.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 613       | 23.65%  |
| 101-250        | 441       | 17.01%  |
| 21-50          | 395       | 15.24%  |
| 51-100         | 352       | 13.58%  |
| 251-500        | 303       | 11.69%  |
| 501-1000       | 224       | 8.64%   |
| 1001-2000      | 126       | 4.86%   |
| More than 3000 | 91        | 3.51%   |
| 2001-3000      | 38        | 1.47%   |
| Unknown        | 9         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB       | 4         | 4      | 1.37%   |
| Seagate ST31000524AS 1TB              | 4         | 5      | 1.37%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 4      | 1.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 10     | 1.37%   |
| Seagate ST1000DM003-1CH162 1TB        | 4         | 8      | 1.37%   |
| Toshiba MQ01ABD100 1TB                | 3         | 4      | 1.03%   |
| Seagate ST3500418AS 500GB             | 3         | 3      | 1.03%   |
| Seagate ST31000528AS 1TB              | 3         | 3      | 1.03%   |
| Seagate ST1000LM048-2E7172 1TB        | 3         | 3      | 1.03%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 3      | 1.03%   |
| Hitachi HTS547564A9E384 640GB         | 3         | 3      | 1.03%   |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 1.03%   |
| Crucial CT1050MX300SSD1 1TB           | 3         | 3      | 1.03%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 2         | 2      | 0.69%   |
| WDC WD5000AAKS-00V1A0 500GB           | 2         | 3      | 0.69%   |
| WDC WD5000AAKS-00A7B0 500GB           | 2         | 2      | 0.69%   |
| WDC WD3200JD-22KLB0 320GB             | 2         | 2      | 0.69%   |
| WDC WD20EFRX-68EUZN0 2TB              | 2         | 4      | 0.69%   |
| WDC WD15EARS-00Z5B1 1TB               | 2         | 2      | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB              | 2         | 2      | 0.69%   |
| WDC WD1001FALS-40U9B0 1TB             | 2         | 2      | 0.69%   |
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 0.69%   |
| Toshiba MK1652GSX 160GB               | 2         | 2      | 0.69%   |
| Toshiba HDWD110 1TB                   | 2         | 2      | 0.69%   |
| SK Hynix SC401 SATA 512GB SSD         | 2         | 2      | 0.69%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.69%   |
| Seagate ST9250315AS 250GB             | 2         | 3      | 0.69%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 0.69%   |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 0.69%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 0.69%   |
| Seagate ST32000542AS 2TB              | 2         | 2      | 0.69%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 2      | 0.69%   |
| SanDisk SSD PLUS 240 GB               | 2         | 2      | 0.69%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 2         | 2      | 0.69%   |
| Samsung Electronics SSD 960 PRO 512GB | 2         | 2      | 0.69%   |
| Samsung Electronics SSD 840 EVO 500GB | 2         | 3      | 0.69%   |
| Samsung Electronics HD502HJ 500GB     | 2         | 2      | 0.69%   |
| Intel SSDSA2M080G2GC 80GB             | 2         | 2      | 0.69%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.69%   |
| HGST HTS545050A7E680 500GB            | 2         | 2      | 0.69%   |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 0.69%   |
| Crucial CT525MX300SSD4 528GB          | 2         | 2      | 0.69%   |
| Crucial CT525MX300SSD1 528GB          | 2         | 2      | 0.69%   |
| Crucial CT500P1SSD8 500GB             | 2         | 2      | 0.69%   |
| Crucial CT275MX300SSD1 275GB          | 2         | 3      | 0.69%   |
| Zheino CHN mSATA02M 256 256GB SSD     | 1         | 2      | 0.34%   |
| XPG SPECTRIX S40G 4TB                 | 1         | 1      | 0.34%   |
| WDC WD6400BEVT-00A0RT0 640GB          | 1         | 1      | 0.34%   |
| WDC WD6400AADS-00M2B0 640GB           | 1         | 1      | 0.34%   |
| WDC WD5003ABYX-01WERA0 500GB          | 1         | 2      | 0.34%   |
| WDC WD5000LPVX-60V0TT0 500GB          | 1         | 1      | 0.34%   |
| WDC WD5000LPVX-55V0TT0 500GB          | 1         | 1      | 0.34%   |
| WDC WD5000LPVT-24G33T1 500GB          | 1         | 1      | 0.34%   |
| WDC WD5000LPVT-22G33T0 500GB          | 1         | 1      | 0.34%   |
| WDC WD5000LPLX-00ZNTT0 500GB          | 1         | 1      | 0.34%   |
| WDC WD5000AAVS-00G9B1 500GB           | 1         | 1      | 0.34%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 1      | 0.34%   |
| WDC WD5000AAKS-00UU3A0 500GB          | 1         | 2      | 0.34%   |
| WDC WD5000AADS-56S9B1 499GB           | 1         | 1      | 0.34%   |
| WDC WD40EZRZ-00GXCB0 4TB              | 1         | 1      | 0.34%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 67        | 82     | 23.84%  |
| Seagate             | 67        | 83     | 23.84%  |
| Samsung Electronics | 27        | 32     | 9.61%   |
| Toshiba             | 26        | 29     | 9.25%   |
| Hitachi             | 17        | 17     | 6.05%   |
| Crucial             | 12        | 14     | 4.27%   |
| SanDisk             | 10        | 10     | 3.56%   |
| Intel               | 9         | 9      | 3.2%    |
| HGST                | 9         | 10     | 3.2%    |
| SK Hynix            | 6         | 6      | 2.14%   |
| Kingston            | 6         | 6      | 2.14%   |
| OCZ                 | 3         | 3      | 1.07%   |
| Micron Technology   | 3         | 3      | 1.07%   |
| MAXTOR              | 3         | 4      | 1.07%   |
| Apple               | 3         | 3      | 1.07%   |
| Fujitsu             | 2         | 2      | 0.71%   |
| A-DATA Technology   | 2         | 2      | 0.71%   |
| Zheino              | 1         | 2      | 0.36%   |
| XPG                 | 1         | 1      | 0.36%   |
| VENO                | 1         | 1      | 0.36%   |
| SPCC                | 1         | 1      | 0.36%   |
| Mushkin             | 1         | 1      | 0.36%   |
| LITEONIT            | 1         | 1      | 0.36%   |
| Drevo               | 1         | 1      | 0.36%   |
| ASMT                | 1         | 1      | 0.36%   |
| ASENNO              | 1         | 1      | 0.36%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 67        | 83     | 32.68%  |
| WDC                 | 66        | 81     | 32.2%   |
| Toshiba             | 22        | 25     | 10.73%  |
| Hitachi             | 17        | 17     | 8.29%   |
| Samsung Electronics | 15        | 19     | 7.32%   |
| HGST                | 9         | 10     | 4.39%   |
| MAXTOR              | 3         | 4      | 1.46%   |
| Apple               | 3         | 3      | 1.46%   |
| Fujitsu             | 2         | 2      | 0.98%   |
| ASMT                | 1         | 1      | 0.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 185       | 245    | 71.15%  |
| SSD  | 62        | 67     | 23.85%  |
| NVMe | 13        | 13     | 5%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB       | 1         | 1      | 25%     |
| Seagate ST500DM002-1BD142 500GB | 1         | 1      | 25%     |
| OCZ VERTEX460A 480GB SSD        | 1         | 1      | 25%     |
| Intel SSDSC2KB960G8 960GB       | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| OCZ     | 1         | 1      | 25%     |
| Intel   | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1242      | 2858   | 45.56%  |
| Works    | 1225      | 2128   | 44.94%  |
| Malfunc  | 255       | 325    | 9.35%   |
| Failed   | 4         | 4      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1586      | 49.94%  |
| AMD                              | 554       | 17.44%  |
| Samsung Electronics              | 311       | 9.79%   |
| Sandisk                          | 138       | 4.35%   |
| SK Hynix                         | 69        | 2.17%   |
| ASMedia Technology               | 60        | 1.89%   |
| Toshiba America Info Systems     | 50        | 1.57%   |
| Kingston Technology Company      | 46        | 1.45%   |
| Phison Electronics               | 45        | 1.42%   |
| JMicron Technology               | 39        | 1.23%   |
| Silicon Motion                   | 35        | 1.1%    |
| Nvidia                           | 33        | 1.04%   |
| Marvell Technology Group         | 29        | 0.91%   |
| Micron Technology                | 27        | 0.85%   |
| ADATA Technology                 | 26        | 0.82%   |
| Micron/Crucial Technology        | 25        | 0.79%   |
| KIOXIA                           | 21        | 0.66%   |
| Realtek Semiconductor            | 15        | 0.47%   |
| Lite-On Technology               | 9         | 0.28%   |
| Broadcom / LSI                   | 8         | 0.25%   |
| Union Memory (Shenzhen)          | 7         | 0.22%   |
| Silicon Image                    | 7         | 0.22%   |
| VIA Technologies                 | 6         | 0.19%   |
| Solid State Storage Technology   | 6         | 0.19%   |
| LSI Logic / Symbios Logic        | 4         | 0.13%   |
| Lenovo                           | 4         | 0.13%   |
| Apple                            | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| Integrated Technology Express    | 2         | 0.06%   |
| Adaptec                          | 2         | 0.06%   |
| Zhaoxin                          | 1         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| Promise Technology               | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| 3ware                            | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 397       | 10.95%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 208       | 5.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 145       | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 127       | 3.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 116       | 3.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 95        | 2.62%   |
| AMD 400 Series Chipset SATA Controller                                                  | 81        | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 78        | 2.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 69        | 1.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 67        | 1.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 65        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 60        | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 55        | 1.52%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 54        | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 53        | 1.46%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 48        | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 45        | 1.24%   |
| AMD 500 Series Chipset SATA Controller                                                  | 44        | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 41        | 1.13%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 40        | 1.1%    |
| Intel SSD 660P Series                                                                   | 40        | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 40        | 1.1%    |
| Samsung NVMe SSD Controller 980                                                         | 38        | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 37        | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 37        | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 36        | 0.99%   |
| Intel SATA Controller [RAID mode]                                                       | 35        | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 35        | 0.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 34        | 0.94%   |
| AMD 300 Series Chipset SATA Controller                                                  | 33        | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 32        | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 32        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 31        | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 28        | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 28        | 0.77%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 27        | 0.74%   |
| Micron Non-Volatile memory controller                                                   | 27        | 0.74%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 25        | 0.69%   |
| AMD FCH SATA Controller D                                                               | 25        | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 24        | 0.66%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 24        | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 24        | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 24        | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 23        | 0.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 23        | 0.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 22        | 0.61%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 22        | 0.61%   |
| Phison E12 NVMe Controller                                                              | 22        | 0.61%   |
| KIOXIA Non-Volatile memory controller                                                   | 21        | 0.58%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 21        | 0.58%   |
| Kingston Company A2000 NVMe SSD                                                         | 18        | 0.5%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 18        | 0.5%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 17        | 0.47%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 16        | 0.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 16        | 0.44%   |
| SK Hynix Gold P31 SSD                                                                   | 15        | 0.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 15        | 0.41%   |
| Kingston Company Company Non-Volatile memory controller                                 | 15        | 0.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 15        | 0.41%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 14        | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1823      | 57.38%  |
| NVMe | 864       | 27.2%   |
| IDE  | 255       | 8.03%   |
| RAID | 222       | 6.99%   |
| SAS  | 8         | 0.25%   |
| SCSI | 5         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1762      | 72.69%  |
| AMD          | 659       | 27.19%  |
| QUALCOMM     | 1         | 0.04%   |
| CentaurHauls | 1         | 0.04%   |
| ARM          | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 36        | 1.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 33        | 1.36%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 33        | 1.36%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 33        | 1.36%   |
| AMD Ryzen 5 3600 6-Core Processor             | 32        | 1.32%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 31        | 1.28%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 29        | 1.19%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 29        | 1.19%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 28        | 1.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 27        | 1.11%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 27        | 1.11%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 1.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 23        | 0.95%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 23        | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 0.86%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.86%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 20        | 0.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 20        | 0.82%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 18        | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 0.7%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 17        | 0.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 0.66%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 15        | 0.62%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 14        | 0.58%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 14        | 0.58%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 14        | 0.58%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 14        | 0.58%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 14        | 0.58%   |
| AMD FX-8350 Eight-Core Processor              | 14        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.54%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 13        | 0.54%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.54%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 13        | 0.54%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 13        | 0.54%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 12        | 0.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 12        | 0.49%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 12        | 0.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 12        | 0.49%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 12        | 0.49%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 12        | 0.49%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 12        | 0.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 11        | 0.45%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 11        | 0.45%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 11        | 0.45%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 11        | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 10        | 0.41%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 10        | 0.41%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 10        | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 10        | 0.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 0.41%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 10        | 0.41%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 10        | 0.41%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 9         | 0.37%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.37%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 9         | 0.37%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 9         | 0.37%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 9         | 0.37%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 9         | 0.37%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 9         | 0.37%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 9         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 599       | 24.66%  |
| Intel Core i5           | 568       | 23.38%  |
| AMD Ryzen 5             | 186       | 7.66%   |
| Intel Core i3           | 134       | 5.52%   |
| AMD Ryzen 7             | 134       | 5.52%   |
| Other                   | 107       | 4.41%   |
| Intel Celeron           | 80        | 3.29%   |
| Intel Core 2 Duo        | 61        | 2.51%   |
| Intel Xeon              | 54        | 2.22%   |
| Intel Pentium           | 46        | 1.89%   |
| AMD FX                  | 46        | 1.89%   |
| AMD Ryzen 9             | 43        | 1.77%   |
| AMD Ryzen 3             | 29        | 1.19%   |
| AMD A10                 | 28        | 1.15%   |
| Intel Core i9           | 22        | 0.91%   |
| Intel Atom              | 22        | 0.91%   |
| AMD A6                  | 19        | 0.78%   |
| AMD Phenom II X4        | 18        | 0.74%   |
| Intel Pentium Dual-Core | 17        | 0.7%    |
| Intel Core 2 Quad       | 17        | 0.7%    |
| AMD Ryzen 7 PRO         | 17        | 0.7%    |
| AMD A8                  | 16        | 0.66%   |
| AMD Athlon II X4        | 13        | 0.54%   |
| AMD A4                  | 10        | 0.41%   |
| Intel Pentium Silver    | 9         | 0.37%   |
| AMD Athlon              | 9         | 0.37%   |
| Intel Genuine           | 8         | 0.33%   |
| AMD Ryzen 5 PRO         | 8         | 0.33%   |
| AMD Athlon II X2        | 7         | 0.29%   |
| Intel Pentium Dual      | 6         | 0.25%   |
| Intel Core m3           | 6         | 0.25%   |
| AMD E2                  | 6         | 0.25%   |
| AMD E1                  | 6         | 0.25%   |
| AMD Athlon 64 X2        | 6         | 0.25%   |
| Intel Celeron Dual-Core | 5         | 0.21%   |
| AMD Ryzen Threadripper  | 5         | 0.21%   |
| AMD E                   | 5         | 0.21%   |
| Intel Pentium D         | 4         | 0.16%   |
| Intel Core 2            | 4         | 0.16%   |
| AMD Phenom II X6        | 4         | 0.16%   |
| AMD Phenom II X2        | 4         | 0.16%   |
| AMD A12                 | 4         | 0.16%   |
| Intel Pentium 4         | 3         | 0.12%   |
| AMD Sempron             | 3         | 0.12%   |
| AMD Phenom              | 3         | 0.12%   |
| AMD Athlon II           | 3         | 0.12%   |
| AMD Athlon 64           | 3         | 0.12%   |
| AMD Opteron             | 2         | 0.08%   |
| AMD C-50                | 2         | 0.08%   |
| AMD Athlon X4           | 2         | 0.08%   |
| AMD Athlon X2           | 2         | 0.08%   |
| Intel Xeon Gold         | 1         | 0.04%   |
| Intel Xeon Bronze       | 1         | 0.04%   |
| Intel Pentium Gold      | 1         | 0.04%   |
| AMD Z                   | 1         | 0.04%   |
| AMD Turion Neo X2       | 1         | 0.04%   |
| AMD Turion II           | 1         | 0.04%   |
| AMD Ryzen Embedded      | 1         | 0.04%   |
| AMD QC                  | 1         | 0.04%   |
| AMD GX                  | 1         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 1013      | 41.72%  |
| 2      | 831       | 34.23%  |
| 6      | 287       | 11.82%  |
| 8      | 197       | 8.11%   |
| 12     | 40        | 1.65%   |
| 1      | 26        | 1.07%   |
| 16     | 17        | 0.7%    |
| 10     | 6         | 0.25%   |
| 3      | 5         | 0.21%   |
| 32     | 2         | 0.08%   |
| 24     | 2         | 0.08%   |
| 20     | 1         | 0.04%   |
| 18     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2407      | 99.3%   |
| 2      | 16        | 0.66%   |
| 4      | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1792      | 73.74%  |
| 1      | 638       | 26.26%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2421      | 99.88%  |
| 32-bit         | 2         | 0.08%   |
| Unknown        | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 455       | 18.21%  |
| 0x206a7    | 141       | 5.64%   |
| 0x306a9    | 137       | 5.48%   |
| 0x306c3    | 124       | 4.96%   |
| 0x906ea    | 95        | 3.8%    |
| 0x806ec    | 82        | 3.28%   |
| 0x806ea    | 70        | 2.8%    |
| 0x40651    | 69        | 2.76%   |
| 0x1067a    | 63        | 2.52%   |
| 0x08701021 | 62        | 2.48%   |
| 0x806e9    | 61        | 2.44%   |
| 0x906e9    | 58        | 2.32%   |
| 0x806c1    | 57        | 2.28%   |
| 0x506e3    | 52        | 2.08%   |
| 0x406e3    | 47        | 1.88%   |
| 0x08108109 | 41        | 1.64%   |
| 0x306d4    | 40        | 1.6%    |
| 0x0800820d | 39        | 1.56%   |
| 0x08701013 | 36        | 1.44%   |
| 0x08108102 | 33        | 1.32%   |
| 0x08600106 | 30        | 1.2%    |
| 0x06000852 | 30        | 1.2%    |
| 0xa0652    | 29        | 1.16%   |
| 0x806eb    | 28        | 1.12%   |
| 0x706e5    | 26        | 1.04%   |
| 0x906ed    | 23        | 0.92%   |
| 0x010000c8 | 23        | 0.92%   |
| 0x20655    | 21        | 0.84%   |
| 0x406c4    | 20        | 0.8%    |
| 0x706a1    | 19        | 0.76%   |
| 0x08600104 | 18        | 0.72%   |
| 0x06001119 | 17        | 0.68%   |
| 0x806d1    | 15        | 0.6%    |
| 0x6fb      | 15        | 0.6%    |
| 0x30678    | 15        | 0.6%    |
| 0x10676    | 14        | 0.56%   |
| 0x706a8    | 13        | 0.52%   |
| 0x506c9    | 13        | 0.52%   |
| 0x306f2    | 13        | 0.52%   |
| 0x106e5    | 13        | 0.52%   |
| 0x0a50000c | 13        | 0.52%   |
| 0x010000db | 12        | 0.48%   |
| 0x6fd      | 11        | 0.44%   |
| 0x20652    | 11        | 0.44%   |
| 0x106a5    | 11        | 0.44%   |
| 0x0810100b | 11        | 0.44%   |
| 0x08001138 | 11        | 0.44%   |
| 0x07030105 | 11        | 0.44%   |
| 0xa0653    | 10        | 0.4%    |
| 0x08600103 | 10        | 0.4%    |
| 0x08101016 | 10        | 0.4%    |
| 0x06003106 | 10        | 0.4%    |
| 0xa0655    | 9         | 0.36%   |
| 0x0a201016 | 9         | 0.36%   |
| 0x0a201009 | 9         | 0.36%   |
| 0x08001137 | 9         | 0.36%   |
| 0x0700010f | 9         | 0.36%   |
| 0x06006705 | 9         | 0.36%   |
| 0x0600611a | 9         | 0.36%   |
| 0x03000027 | 9         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 501       | 20.62%  |
| Haswell         | 250       | 10.29%  |
| Zen 2           | 187       | 7.7%    |
| SandyBridge     | 171       | 7.04%   |
| IvyBridge       | 165       | 6.79%   |
| Zen+            | 133       | 5.47%   |
| Skylake         | 128       | 5.27%   |
| Penryn          | 88        | 3.62%   |
| TigerLake       | 74        | 3.05%   |
| Zen             | 63        | 2.59%   |
| CometLake       | 59        | 2.43%   |
| Piledriver      | 57        | 2.35%   |
| K10             | 55        | 2.26%   |
| IceLake         | 50        | 2.06%   |
| Broadwell       | 48        | 1.98%   |
| Westmere        | 46        | 1.89%   |
| Silvermont      | 43        | 1.77%   |
| Zen 3           | 41        | 1.69%   |
| Goldmont plus   | 39        | 1.6%    |
| Core            | 39        | 1.6%    |
| Excavator       | 33        | 1.36%   |
| Nehalem         | 31        | 1.28%   |
| Unknown         | 17        | 0.7%    |
| Steamroller     | 15        | 0.62%   |
| Puma            | 14        | 0.58%   |
| Goldmont        | 14        | 0.58%   |
| K8 Hammer       | 13        | 0.53%   |
| K10 Llano       | 11        | 0.45%   |
| Jaguar          | 11        | 0.45%   |
| Bobcat          | 11        | 0.45%   |
| NetBurst        | 7         | 0.29%   |
| Bulldozer       | 7         | 0.29%   |
| Bonnell         | 5         | 0.21%   |
| K8 & K10 hybrid | 2         | 0.08%   |
| Tremont         | 1         | 0.04%   |
| K6              | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1357      | 46.54%  |
| Nvidia                           | 879       | 30.14%  |
| AMD                              | 670       | 22.98%  |
| ASPEED Technology                | 4         | 0.14%   |
| Matrox Electronics Systems       | 3         | 0.1%    |
| Zhaoxin                          | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 115       | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 92        | 3.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 91        | 3.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 84        | 2.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 77        | 2.58%   |
| Intel UHD Graphics 620                                                                   | 77        | 2.58%   |
| AMD Renoir                                                                               | 76        | 2.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 73        | 2.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 70        | 2.34%   |
| Intel HD Graphics 620                                                                    | 60        | 2.01%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 59        | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 55        | 1.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 52        | 1.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 51        | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 47        | 1.57%   |
| Intel HD Graphics 5500                                                                   | 43        | 1.44%   |
| Intel HD Graphics 630                                                                    | 42        | 1.41%   |
| Intel HD Graphics 530                                                                    | 35        | 1.17%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 32        | 1.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 32        | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 31        | 1.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 30        | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 30        | 1%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 27        | 0.9%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 27        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 0.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 23        | 0.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 23        | 0.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 23        | 0.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 20        | 0.67%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 17        | 0.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 17        | 0.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 17        | 0.57%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 17        | 0.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 17        | 0.57%   |
| AMD Cezanne                                                                              | 17        | 0.57%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 17        | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 16        | 0.54%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 0.54%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 16        | 0.54%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 15        | 0.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 15        | 0.5%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 15        | 0.5%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 15        | 0.5%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 15        | 0.5%    |
| Nvidia GP108M [GeForce MX150]                                                            | 14        | 0.47%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 14        | 0.47%   |
| Intel Iris Plus Graphics G7                                                              | 14        | 0.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 14        | 0.47%   |
| Nvidia GT218 [GeForce 210]                                                               | 13        | 0.44%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 13        | 0.44%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 13        | 0.44%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 13        | 0.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 12        | 0.4%    |
| Nvidia GP108M [GeForce MX250]                                                            | 12        | 0.4%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 12        | 0.4%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 12        | 0.4%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 12        | 0.4%    |
| Nvidia GM108M [GeForce 840M]                                                             | 11        | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 902       | 37.06%  |
| 1 x AMD         | 541       | 22.23%  |
| 1 x Nvidia      | 457       | 18.78%  |
| Intel + Nvidia  | 378       | 15.53%  |
| Intel + AMD     | 60        | 2.47%   |
| 2 x AMD         | 42        | 1.73%   |
| AMD + Nvidia    | 30        | 1.23%   |
| 2 x Nvidia      | 12        | 0.49%   |
| 1 x ASPEED      | 3         | 0.12%   |
| Other           | 2         | 0.08%   |
| 1 x Matrox      | 2         | 0.08%   |
| 3 x Nvidia      | 1         | 0.04%   |
| 1 x Zhaoxin     | 1         | 0.04%   |
| 1 x SiS         | 1         | 0.04%   |
| Nvidia + Matrox | 1         | 0.04%   |
| Nvidia + ASPEED | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1775      | 72.24%  |
| Proprietary | 633       | 25.76%  |
| Unknown     | 49        | 1.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1241      | 49.9%   |
| 1.01-2.0   | 340       | 13.67%  |
| 0.01-0.5   | 217       | 8.73%   |
| 3.01-4.0   | 215       | 8.64%   |
| 0.51-1.0   | 208       | 8.36%   |
| 7.01-8.0   | 136       | 5.47%   |
| 5.01-6.0   | 77        | 3.1%    |
| 2.01-3.0   | 26        | 1.05%   |
| 8.01-16.0  | 23        | 0.92%   |
| 4.01-5.0   | 2         | 0.08%   |
| 32.01-64.0 | 1         | 0.04%   |
| 16.01-24.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 355       | 12.41%  |
| AU Optronics            | 313       | 10.94%  |
| LG Display              | 255       | 8.92%   |
| BOE                     | 229       | 8.01%   |
| Chimei Innolux          | 220       | 7.69%   |
| Dell                    | 192       | 6.71%   |
| Goldstar                | 150       | 5.24%   |
| Acer                    | 118       | 4.13%   |
| Hewlett-Packard         | 89        | 3.11%   |
| AOC                     | 82        | 2.87%   |
| BenQ                    | 78        | 2.73%   |
| Ancor Communications    | 77        | 2.69%   |
| Sharp                   | 73        | 2.55%   |
| Philips                 | 67        | 2.34%   |
| ViewSonic               | 44        | 1.54%   |
| Lenovo                  | 42        | 1.47%   |
| PANDA                   | 36        | 1.26%   |
| Iiyama                  | 35        | 1.22%   |
| Chi Mei Optoelectronics | 32        | 1.12%   |
| LG Electronics          | 27        | 0.94%   |
| Apple                   | 26        | 0.91%   |
| ASUSTek Computer        | 23        | 0.8%    |
| Unknown                 | 21        | 0.73%   |
| InfoVision              | 19        | 0.66%   |
| Sony                    | 17        | 0.59%   |
| Panasonic               | 15        | 0.52%   |
| NEC Computers           | 15        | 0.52%   |
| HannStar                | 10        | 0.35%   |
| Medion                  | 8         | 0.28%   |
| Eizo                    | 8         | 0.28%   |
| Toshiba                 | 7         | 0.24%   |
| MSI                     | 7         | 0.24%   |
| Vestel Elektronik       | 6         | 0.21%   |
| Sceptre Tech            | 6         | 0.21%   |
| Vizio                   | 4         | 0.14%   |
| Seiko/Epson             | 4         | 0.14%   |
| LG Philips              | 4         | 0.14%   |
| Idek Iiyama             | 4         | 0.14%   |
| Gateway                 | 4         | 0.14%   |
| DENON                   | 4         | 0.14%   |
| Viotek                  | 3         | 0.1%    |
| Sanyo                   | 3         | 0.1%    |
| SAC                     | 3         | 0.1%    |
| Packard Bell            | 3         | 0.1%    |
| Onkyo                   | 3         | 0.1%    |
| LGD                     | 3         | 0.1%    |
| HPN                     | 3         | 0.1%    |
| Envision                | 3         | 0.1%    |
| CSO                     | 3         | 0.1%    |
| CPT                     | 3         | 0.1%    |
| AUS                     | 3         | 0.1%    |
| Xiaomi                  | 2         | 0.07%   |
| Vestel                  | 2         | 0.07%   |
| Unknown (XXX)           | 2         | 0.07%   |
| Targa Visionary         | 2         | 0.07%   |
| SFX                     | 2         | 0.07%   |
| Sceptre                 | 2         | 0.07%   |
| ONN                     | 2         | 0.07%   |
| MiTAC                   | 2         | 0.07%   |
| Lenovo Group Limited    | 2         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 17        | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 14        | 0.47%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 13        | 0.43%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 13        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 13        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 12        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 11        | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 0.3%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 9         | 0.3%    |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 8         | 0.27%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 8         | 0.27%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 7         | 0.23%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 7         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 7         | 0.23%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 6         | 0.2%    |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 700x390mm 31.5-inch | 6         | 0.2%    |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 6         | 0.2%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 6         | 0.2%    |
| Goldstar Ultra HD GSM5B09 3780x2160 600x340mm 27.2-inch               | 6         | 0.2%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch      | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 6         | 0.2%    |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                 | 6         | 0.2%    |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 6         | 0.2%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 5         | 0.17%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 5         | 0.17%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 5         | 0.17%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 5         | 0.17%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 5         | 0.17%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 5         | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.17%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5         | 0.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 5         | 0.17%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 5         | 0.17%   |
| LG Display LCD Monitor LGD065A 1920x1080 340x190mm 15.3-inch          | 5         | 0.17%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch           | 5         | 0.17%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 5         | 0.17%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 5         | 0.17%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch          | 5         | 0.17%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 5         | 0.17%   |
| Dell U3415W DELA0A6 3440x1440 798x335mm 34.1-inch                     | 5         | 0.17%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 5         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 5         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 5         | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.17%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 5         | 0.17%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                 | 5         | 0.17%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 5         | 0.17%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 5         | 0.17%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                 | 5         | 0.17%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 5         | 0.17%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 5         | 0.17%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 5         | 0.17%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch         | 5         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1291      | 47.66%  |
| 1366x768 (WXGA)    | 421       | 15.54%  |
| 3840x2160 (4K)     | 184       | 6.79%   |
| 2560x1440 (QHD)    | 133       | 4.91%   |
| 1600x900 (HD+)     | 99        | 3.65%   |
| 1920x1200 (WUXGA)  | 81        | 2.99%   |
| 1680x1050 (WSXGA+) | 69        | 2.55%   |
| Unknown            | 64        | 2.36%   |
| 1280x1024 (SXGA)   | 63        | 2.33%   |
| 1440x900 (WXGA+)   | 35        | 1.29%   |
| 3440x1440          | 27        | 1%      |
| 1280x800 (WXGA)    | 27        | 1%      |
| 2560x1080          | 26        | 0.96%   |
| 3840x1080          | 24        | 0.89%   |
| 1360x768           | 21        | 0.78%   |
| 2160x1440          | 13        | 0.48%   |
| 3840x2400          | 12        | 0.44%   |
| 2560x1600          | 12        | 0.44%   |
| 1600x1200          | 10        | 0.37%   |
| 3840x1200          | 7         | 0.26%   |
| 3200x1800 (QHD+)   | 7         | 0.26%   |
| 2880x1800          | 7         | 0.26%   |
| 1024x768 (XGA)     | 7         | 0.26%   |
| 1920x540           | 6         | 0.22%   |
| 4480x1440          | 5         | 0.18%   |
| 1920x1280          | 4         | 0.15%   |
| 5760x1080          | 3         | 0.11%   |
| 3840x1600          | 3         | 0.11%   |
| 3600x1080          | 3         | 0.11%   |
| 3456x2160          | 3         | 0.11%   |
| 3200x1080          | 3         | 0.11%   |
| 7680x2160          | 2         | 0.07%   |
| 5760x2160          | 2         | 0.07%   |
| 4480x1080          | 2         | 0.07%   |
| 2736x1824          | 2         | 0.07%   |
| 2288x1287          | 2         | 0.07%   |
| 2240x1400          | 2         | 0.07%   |
| 1024x600           | 2         | 0.07%   |
| 6400x2160          | 1         | 0.04%   |
| 6400x1080          | 1         | 0.04%   |
| 5760x1200          | 1         | 0.04%   |
| 4480x1600          | 1         | 0.04%   |
| 3840x1920          | 1         | 0.04%   |
| 3840x1024          | 1         | 0.04%   |
| 3600x1200          | 1         | 0.04%   |
| 3360x1080          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 3040x900           | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 3000x1920          | 1         | 0.04%   |
| 2880x1440          | 1         | 0.04%   |
| 2880x1024          | 1         | 0.04%   |
| 2560x1700          | 1         | 0.04%   |
| 2400x1600          | 1         | 0.04%   |
| 2256x1504          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |
| 1921x1080          | 1         | 0.04%   |
| 1920x1440          | 1         | 0.04%   |
| 1680x945           | 1         | 0.04%   |
| 1400x1050          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 704       | 24.74%  |
| 13      | 245       | 8.61%   |
| 27      | 228       | 8.01%   |
| 24      | 226       | 7.94%   |
| 23      | 207       | 7.27%   |
| 14      | 204       | 7.17%   |
| Unknown | 194       | 6.82%   |
| 21      | 161       | 5.66%   |
| 17      | 159       | 5.59%   |
| 31      | 65        | 2.28%   |
| 19      | 57        | 2%      |
| 34      | 48        | 1.69%   |
| 22      | 47        | 1.65%   |
| 20      | 42        | 1.48%   |
| 12      | 36        | 1.26%   |
| 18      | 34        | 1.19%   |
| 11      | 29        | 1.02%   |
| 84      | 17        | 0.6%    |
| 25      | 17        | 0.6%    |
| 54      | 14        | 0.49%   |
| 32      | 13        | 0.46%   |
| 16      | 12        | 0.42%   |
| 72      | 10        | 0.35%   |
| 40      | 9         | 0.32%   |
| 26      | 7         | 0.25%   |
| 47      | 6         | 0.21%   |
| 52      | 4         | 0.14%   |
| 42      | 4         | 0.14%   |
| 37      | 4         | 0.14%   |
| 29      | 4         | 0.14%   |
| 28      | 4         | 0.14%   |
| 10      | 4         | 0.14%   |
| 48      | 3         | 0.11%   |
| 46      | 3         | 0.11%   |
| 43      | 3         | 0.11%   |
| 39      | 3         | 0.11%   |
| 65      | 2         | 0.07%   |
| 49      | 2         | 0.07%   |
| 36      | 2         | 0.07%   |
| 30      | 2         | 0.07%   |
| 142     | 1         | 0.04%   |
| 74      | 1         | 0.04%   |
| 61      | 1         | 0.04%   |
| 60      | 1         | 0.04%   |
| 55      | 1         | 0.04%   |
| 50      | 1         | 0.04%   |
| 35      | 1         | 0.04%   |
| 33      | 1         | 0.04%   |
| 8       | 1         | 0.04%   |
| 5       | 1         | 0.04%   |
| 3       | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1046      | 37.78%  |
| 501-600        | 605       | 21.85%  |
| 401-500        | 297       | 10.73%  |
| Unknown        | 194       | 7.01%   |
| 201-300        | 189       | 6.83%   |
| 351-400        | 184       | 6.64%   |
| 601-700        | 96        | 3.47%   |
| 701-800        | 64        | 2.31%   |
| 1001-1500      | 38        | 1.37%   |
| 1501-2000      | 28        | 1.01%   |
| 801-900        | 17        | 0.61%   |
| 901-1000       | 7         | 0.25%   |
| 1-100          | 2         | 0.07%   |
| More than 2000 | 1         | 0.04%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1903      | 76.06%  |
| 16/10   | 254       | 10.15%  |
| Unknown | 171       | 6.83%   |
| 5/4     | 63        | 2.52%   |
| 21/9    | 53        | 2.12%   |
| 3/2     | 24        | 0.96%   |
| 4/3     | 21        | 0.84%   |
| 32/9    | 8         | 0.32%   |
| 6/5     | 1         | 0.04%   |
| 1.96    | 1         | 0.04%   |
| 1.00    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 701       | 25.07%  |
| 201-250        | 484       | 17.31%  |
| 81-90          | 342       | 12.23%  |
| 301-350        | 234       | 8.37%   |
| Unknown        | 194       | 6.94%   |
| 151-200        | 141       | 5.04%   |
| 351-500        | 133       | 4.76%   |
| 71-80          | 114       | 4.08%   |
| 121-130        | 112       | 4.01%   |
| 251-300        | 95        | 3.4%    |
| 141-150        | 58        | 2.07%   |
| More than 1000 | 55        | 1.97%   |
| 501-1000       | 38        | 1.36%   |
| 61-70          | 29        | 1.04%   |
| 51-60          | 29        | 1.04%   |
| 131-140        | 15        | 0.54%   |
| 111-120        | 8         | 0.29%   |
| 91-100         | 7         | 0.25%   |
| 41-50          | 4         | 0.14%   |
| 1-40           | 3         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 856       | 31.42%  |
| 121-160       | 770       | 28.27%  |
| 101-120       | 619       | 22.72%  |
| Unknown       | 194       | 7.12%   |
| 161-240       | 143       | 5.25%   |
| More than 240 | 85        | 3.12%   |
| 1-50          | 57        | 2.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1836      | 74.18%  |
| 2     | 518       | 20.93%  |
| 3     | 64        | 2.59%   |
| 0     | 52        | 2.1%    |
| 4     | 5         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1402      | 38.62%  |
| Intel                                 | 1221      | 33.64%  |
| Qualcomm Atheros                      | 399       | 10.99%  |
| Broadcom                              | 154       | 4.24%   |
| Ralink Technology                     | 45        | 1.24%   |
| TP-Link                               | 42        | 1.16%   |
| Ralink                                | 38        | 1.05%   |
| Nvidia                                | 26        | 0.72%   |
| Broadcom Limited                      | 26        | 0.72%   |
| Marvell Technology Group              | 20        | 0.55%   |
| MEDIATEK                              | 19        | 0.52%   |
| Microsoft                             | 16        | 0.44%   |
| Qualcomm Atheros Communications       | 14        | 0.39%   |
| Qualcomm                              | 12        | 0.33%   |
| NetGear                               | 12        | 0.33%   |
| Aquantia                              | 12        | 0.33%   |
| Xiaomi                                | 11        | 0.3%    |
| Huawei Technologies                   | 10        | 0.28%   |
| DisplayLink                           | 10        | 0.28%   |
| Samsung Electronics                   | 9         | 0.25%   |
| D-Link                                | 9         | 0.25%   |
| Edimax Technology                     | 8         | 0.22%   |
| ASIX Electronics                      | 8         | 0.22%   |
| Sierra Wireless                       | 7         | 0.19%   |
| Lenovo                                | 7         | 0.19%   |
| Ericsson Business Mobile Networks     | 7         | 0.19%   |
| Dell                                  | 7         | 0.19%   |
| JMicron Technology                    | 6         | 0.17%   |
| Linksys                               | 5         | 0.14%   |
| ASUSTek Computer                      | 5         | 0.14%   |
| D-Link System                         | 4         | 0.11%   |
| Apple                                 | 4         | 0.11%   |
| T & A Mobile Phones                   | 3         | 0.08%   |
| Fibocom                               | 3         | 0.08%   |
| Belkin Components                     | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.06%   |
| VIA Technologies                      | 2         | 0.06%   |
| STMicroelectronics                    | 2         | 0.06%   |
| Silicon Integrated Systems [SiS]      | 2         | 0.06%   |
| Oculus VR                             | 2         | 0.06%   |
| Hewlett-Packard                       | 2         | 0.06%   |
| Google                                | 2         | 0.06%   |
| AVM                                   | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| 3Com                                  | 2         | 0.06%   |
| ZyDAS                                 | 1         | 0.03%   |
| Wilocity                              | 1         | 0.03%   |
| Wacom                                 | 1         | 0.03%   |
| U.S. Robotics                         | 1         | 0.03%   |
| Toshiba                               | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Sigma Designs                         | 1         | 0.03%   |
| SEGGER                                | 1         | 0.03%   |
| Seeed Technology                      | 1         | 0.03%   |
| QNAP System                           | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Motorola PCS                          | 1         | 0.03%   |
| Motorola BCS                          | 1         | 0.03%   |
| Motorola                              | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1014      | 23.84%  |
| Intel Wi-Fi 6 AX200                                               | 151       | 3.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 138       | 3.24%   |
| Intel Wireless 8265 / 8275                                        | 90        | 2.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 89        | 2.09%   |
| Intel I211 Gigabit Network Connection                             | 83        | 1.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 79        | 1.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 68        | 1.6%    |
| Intel Wireless 7260                                               | 64        | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 62        | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 60        | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 55        | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 54        | 1.27%   |
| Intel Wi-Fi 6 AX201                                               | 54        | 1.27%   |
| Intel Wireless 7265                                               | 53        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 51        | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 48        | 1.13%   |
| Intel Wireless 3165                                               | 43        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                              | 43        | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 43        | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 43        | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 38        | 0.89%   |
| Intel Wireless-AC 9260                                            | 36        | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 34        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 32        | 0.75%   |
| Intel Wireless 8260                                               | 31        | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 31        | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 30        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 29        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 26        | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                             | 25        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 24        | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 23        | 0.54%   |
| Ralink MT7601U Wireless Adapter                                   | 21        | 0.49%   |
| Intel Wireless 3160                                               | 21        | 0.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 21        | 0.49%   |
| Broadcom BCM43142 802.11b/g/n                                     | 20        | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.45%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 19        | 0.45%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 17        | 0.4%    |
| Intel Ethernet Connection (6) I219-V                              | 17        | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 16        | 0.38%   |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 15        | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 15        | 0.35%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.35%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.35%   |
| Intel 82579V Gigabit Network Connection                           | 15        | 0.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 13        | 0.31%   |
| Qualcomm Atheros AR9271 802.11n                                   | 13        | 0.31%   |
| Intel Ethernet Connection I217-V                                  | 13        | 0.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 12        | 0.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 12        | 0.28%   |
| Realtek 802.11ac NIC                                              | 12        | 0.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 12        | 0.28%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 951       | 49.15%  |
| Qualcomm Atheros                      | 315       | 16.28%  |
| Realtek Semiconductor                 | 301       | 15.56%  |
| Broadcom                              | 101       | 5.22%   |
| Ralink Technology                     | 45        | 2.33%   |
| TP-Link                               | 39        | 2.02%   |
| Ralink                                | 38        | 1.96%   |
| Broadcom Limited                      | 20        | 1.03%   |
| MEDIATEK                              | 15        | 0.78%   |
| Qualcomm Atheros Communications       | 14        | 0.72%   |
| Microsoft                             | 14        | 0.72%   |
| NetGear                               | 12        | 0.62%   |
| D-Link                                | 9         | 0.47%   |
| Edimax Technology                     | 8         | 0.41%   |
| Sierra Wireless                       | 7         | 0.36%   |
| Qualcomm                              | 6         | 0.31%   |
| Linksys                               | 5         | 0.26%   |
| ASUSTek Computer                      | 5         | 0.26%   |
| Marvell Technology Group              | 4         | 0.21%   |
| Dell                                  | 4         | 0.21%   |
| Belkin Components                     | 3         | 0.16%   |
| Fibocom                               | 2         | 0.1%    |
| D-Link System                         | 2         | 0.1%    |
| AVM                                   | 2         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.1%    |
| ZyDAS                                 | 1         | 0.05%   |
| Wilocity                              | 1         | 0.05%   |
| Wacom                                 | 1         | 0.05%   |
| Tenda                                 | 1         | 0.05%   |
| Philips (or NXP)                      | 1         | 0.05%   |
| Mercucys                              | 1         | 0.05%   |
| IMC Networks                          | 1         | 0.05%   |
| Guillemot                             | 1         | 0.05%   |
| Gemtek                                | 1         | 0.05%   |
| AirTies Wireless Networks             | 1         | 0.05%   |
| Accton Technology                     | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 151       | 7.75%   |
| Intel Wireless 8265 / 8275                                     | 90        | 4.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 68        | 3.49%   |
| Intel Wireless 7260                                            | 64        | 3.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 62        | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 60        | 3.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 55        | 2.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 54        | 2.77%   |
| Intel Wi-Fi 6 AX201                                            | 54        | 2.77%   |
| Intel Wireless 7265                                            | 53        | 2.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 48        | 2.46%   |
| Intel Wireless 3165                                            | 43        | 2.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 43        | 2.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 43        | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 39        | 2%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 38        | 1.95%   |
| Intel Wireless-AC 9260                                         | 36        | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 32        | 1.64%   |
| Intel Wireless 8260                                            | 31        | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 31        | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 30        | 1.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 29        | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 26        | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 23        | 1.18%   |
| Ralink MT7601U Wireless Adapter                                | 21        | 1.08%   |
| Intel Wireless 3160                                            | 21        | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 21        | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                  | 20        | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 19        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 17        | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 16        | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 15        | 0.77%   |
| Qualcomm Atheros AR9271 802.11n                                | 13        | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 12        | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 12        | 0.62%   |
| Realtek 802.11ac NIC                                           | 12        | 0.62%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 11        | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 0.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 11        | 0.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 11        | 0.56%   |
| Intel Centrino Advanced-N 6235                                 | 11        | 0.56%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 10        | 0.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 10        | 0.51%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 0.51%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 10        | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 9         | 0.46%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 9         | 0.46%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 9         | 0.46%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 9         | 0.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 8         | 0.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 8         | 0.41%   |
| Ralink RT5370 Wireless Adapter                                 | 7         | 0.36%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 7         | 0.36%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 7         | 0.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 7         | 0.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 7         | 0.36%   |
| Microsoft Xbox 360 Wireless Adapter                            | 7         | 0.36%   |
| Intel WiFi Link 5100                                           | 7         | 0.36%   |
| Intel Centrino Wireless-N 2230                                 | 7         | 0.36%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 7         | 0.36%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1285      | 57.88%  |
| Intel                            | 593       | 26.71%  |
| Qualcomm Atheros                 | 114       | 5.14%   |
| Broadcom                         | 66        | 2.97%   |
| Nvidia                           | 26        | 1.17%   |
| Marvell Technology Group         | 16        | 0.72%   |
| Aquantia                         | 12        | 0.54%   |
| Xiaomi                           | 11        | 0.5%    |
| DisplayLink                      | 10        | 0.45%   |
| Samsung Electronics              | 9         | 0.41%   |
| ASIX Electronics                 | 8         | 0.36%   |
| Lenovo                           | 7         | 0.32%   |
| Huawei Technologies              | 7         | 0.32%   |
| Broadcom Limited                 | 7         | 0.32%   |
| Qualcomm                         | 6         | 0.27%   |
| JMicron Technology               | 6         | 0.27%   |
| MediaTek                         | 4         | 0.18%   |
| Apple                            | 4         | 0.18%   |
| TP-Link                          | 3         | 0.14%   |
| T & A Mobile Phones              | 3         | 0.14%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.09%   |
| VIA Technologies                 | 2         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.09%   |
| Microsoft                        | 2         | 0.09%   |
| Google                           | 2         | 0.09%   |
| D-Link System                    | 2         | 0.09%   |
| 3Com                             | 2         | 0.09%   |
| QNAP System                      | 1         | 0.05%   |
| Motorola PCS                     | 1         | 0.05%   |
| Motorola BCS                     | 1         | 0.05%   |
| Mellanox Technologies            | 1         | 0.05%   |
| HMD Global                       | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| FIBOCOM                          | 1         | 0.05%   |
| Elecom                           | 1         | 0.05%   |
| Davicom Semiconductor            | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1014      | 44.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 138       | 6.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 89        | 3.91%   |
| Intel I211 Gigabit Network Connection                             | 83        | 3.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 79        | 3.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 51        | 2.24%   |
| Intel Ethernet Connection (2) I219-V                              | 43        | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 34        | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 26        | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                             | 25        | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 24        | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.83%   |
| Intel Ethernet Connection (6) I219-V                              | 17        | 0.75%   |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 15        | 0.66%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 15        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 13        | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 13        | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 12        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11        | 0.48%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 11        | 0.48%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 11        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.44%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 10        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9         | 0.39%   |
| Nvidia MCP61 Ethernet                                             | 9         | 0.39%   |
| Intel 82574L Gigabit Network Connection                           | 9         | 0.39%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 9         | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 0.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 0.35%   |
| Intel Ethernet Connection (10) I219-V                             | 8         | 0.35%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 0.35%   |
| Intel Ethernet Connection I219-V                                  | 7         | 0.31%   |
| Intel Ethernet Connection (5) I219-LM                             | 7         | 0.31%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.31%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.31%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 7         | 0.31%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.31%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 7         | 0.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.26%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 6         | 0.26%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.26%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.26%   |
| Intel 82578DM Gigabit Network Connection                          | 6         | 0.26%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.26%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 5         | 0.22%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.22%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 0.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.22%   |
| Nvidia MCP77 Ethernet                                             | 5         | 0.22%   |
| Huawei E353/E3131                                                 | 5         | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2086      | 52.84%  |
| WiFi     | 1836      | 46.5%   |
| Modem    | 26        | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1581      | 50.72%  |
| Ethernet | 1534      | 49.21%  |
| Modem    | 2         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1313      | 54.12%  |
| 1     | 1025      | 42.25%  |
| 3     | 48        | 1.98%   |
| 0     | 31        | 1.28%   |
| 4     | 6         | 0.25%   |
| 6     | 3         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 2135      | 87.04%  |
| Yes     | 317       | 12.92%  |
| Unknown | 1         | 0.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 808       | 50.44%  |
| Realtek Semiconductor           | 153       | 9.55%   |
| Qualcomm Atheros Communications | 141       | 8.8%    |
| Cambridge Silicon Radio         | 124       | 7.74%   |
| Broadcom                        | 88        | 5.49%   |
| IMC Networks                    | 54        | 3.37%   |
| Lite-On Technology              | 51        | 3.18%   |
| Foxconn / Hon Hai               | 30        | 1.87%   |
| Apple                           | 27        | 1.69%   |
| Dell                            | 25        | 1.56%   |
| ASUSTek Computer                | 23        | 1.44%   |
| Realtek                         | 18        | 1.12%   |
| Ralink                          | 10        | 0.62%   |
| Hewlett-Packard                 | 8         | 0.5%    |
| Foxconn International           | 6         | 0.37%   |
| Toshiba                         | 5         | 0.31%   |
| Marvell Semiconductor           | 5         | 0.31%   |
| Ralink Technology               | 4         | 0.25%   |
| Dynex                           | 4         | 0.25%   |
| Unknown                         | 2         | 0.12%   |
| TP-Link                         | 2         | 0.12%   |
| Taiyo Yuden                     | 2         | 0.12%   |
| Integrated System Solution      | 2         | 0.12%   |
| Belkin Components               | 2         | 0.12%   |
| Alps Electric                   | 2         | 0.12%   |
| Kensington                      | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |
| D-Link                          | 1         | 0.06%   |
| Creative Technology             | 1         | 0.06%   |
| Corsair                         | 1         | 0.06%   |
| AboCom Systems                  | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 296       | 18.44%  |
| Intel AX200 Bluetooth                                                               | 147       | 9.16%   |
| Intel Bluetooth Device                                                              | 136       | 8.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 124       | 7.73%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 124       | 7.73%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 75        | 4.67%   |
| Realtek Bluetooth Radio                                                             | 74        | 4.61%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 58        | 3.61%   |
| Lite-On Bluetooth Device                                                            | 35        | 2.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 33        | 2.06%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 29        | 1.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 24        | 1.5%    |
| IMC Networks Bluetooth Radio                                                        | 20        | 1.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 20        | 1.25%   |
| Realtek Bluetooth Radio                                                             | 18        | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 17        | 1.06%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 17        | 1.06%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 16        | 1%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 16        | 1%      |
| IMC Networks Bluetooth Device                                                       | 13        | 0.81%   |
| Apple Bluetooth USB Host Controller                                                 | 13        | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 12        | 0.75%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 12        | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 12        | 0.75%   |
| Intel AX210 Bluetooth                                                               | 11        | 0.69%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 11        | 0.69%   |
| Ralink RT3290 Bluetooth                                                             | 10        | 0.62%   |
| Realtek RTL8723B Bluetooth                                                          | 9         | 0.56%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 9         | 0.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 8         | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 8         | 0.5%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 7         | 0.44%   |
| IMC Networks Bluetooth USB Host Controller                                          | 7         | 0.44%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 7         | 0.44%   |
| IMC Networks Wireless_Device                                                        | 6         | 0.37%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 0.37%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 6         | 0.37%   |
| Dell DW375 Bluetooth Module                                                         | 6         | 0.37%   |
| Apple Bluetooth Host Controller                                                     | 6         | 0.37%   |
| Lite-On Bluetooth Radio                                                             | 5         | 0.31%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 4         | 0.25%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 4         | 0.25%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 0.25%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 4         | 0.25%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.25%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 4         | 0.25%   |
| Broadcom BCM92045B3 ROM                                                             | 4         | 0.25%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 4         | 0.25%   |
| Broadcom BCM2045 Bluetooth                                                          | 4         | 0.25%   |
| ASUS ASUS USB-BT500                                                                 | 4         | 0.25%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 0.19%   |
| IMC Networks BCM20702A0                                                             | 3         | 0.19%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 3         | 0.19%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 3         | 0.19%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 0.19%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 0.19%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 3         | 0.19%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 0.19%   |
| ASUS Bluetooth Radio                                                                | 3         | 0.19%   |
| Unknown Bluetooth Device                                                            | 2         | 0.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1712      | 48.5%   |
| AMD                                  | 770       | 21.81%  |
| Nvidia                               | 622       | 17.62%  |
| C-Media Electronics                  | 67        | 1.9%    |
| Logitech                             | 32        | 0.91%   |
| Creative Labs                        | 30        | 0.85%   |
| GN Netcom                            | 25        | 0.71%   |
| Realtek Semiconductor                | 21        | 0.59%   |
| Texas Instruments                    | 18        | 0.51%   |
| JMTek                                | 15        | 0.42%   |
| Plantronics                          | 13        | 0.37%   |
| Creative Technology                  | 13        | 0.37%   |
| Razer USA                            | 10        | 0.28%   |
| Generalplus Technology               | 10        | 0.28%   |
| Corsair                              | 10        | 0.28%   |
| ASUSTek Computer                     | 9         | 0.25%   |
| Focusrite-Novation                   | 7         | 0.2%    |
| Tenx Technology                      | 6         | 0.17%   |
| SteelSeries ApS                      | 6         | 0.17%   |
| Hewlett-Packard                      | 6         | 0.17%   |
| VIA Technologies                     | 5         | 0.14%   |
| Sennheiser Communications            | 5         | 0.14%   |
| Lenovo                               | 5         | 0.14%   |
| Kingston Technology                  | 5         | 0.14%   |
| Sony                                 | 4         | 0.11%   |
| SAVITECH                             | 4         | 0.11%   |
| Dell                                 | 4         | 0.11%   |
| Blue Microphones                     | 4         | 0.11%   |
| Yamaha                               | 3         | 0.08%   |
| RODE Microphones                     | 3         | 0.08%   |
| PreSonus Audio Electronics           | 3         | 0.08%   |
| ONN                                  | 3         | 0.08%   |
| Microsoft                            | 3         | 0.08%   |
| GYROCOM C&C                          | 3         | 0.08%   |
| CMX Systems                          | 3         | 0.08%   |
| XMOS                                 | 2         | 0.06%   |
| Trust                                | 2         | 0.06%   |
| TerraTec Electronic                  | 2         | 0.06%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.06%   |
| Roland                               | 2         | 0.06%   |
| QinHeng Electronics                  | 2         | 0.06%   |
| Native Instruments                   | 2         | 0.06%   |
| iConnectivity                        | 2         | 0.06%   |
| Google                               | 2         | 0.06%   |
| Fry's Electronics                    | 2         | 0.06%   |
| Conexant Systems                     | 2         | 0.06%   |
| BEHRINGER International              | 2         | 0.06%   |
| ZOOM                                 | 1         | 0.03%   |
| Zhaoxin                              | 1         | 0.03%   |
| www.hirestech.com 2010 REV 1.4       | 1         | 0.03%   |
| Winbond Electronics                  | 1         | 0.03%   |
| Valve Software                       | 1         | 0.03%   |
| USB MICROPHONE                       | 1         | 0.03%   |
| Unknown                              | 1         | 0.03%   |
| Turtle Beach                         | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.03%   |
| TEAC                                 | 1         | 0.03%   |
| Sunplus Innovation Technology        | 1         | 0.03%   |
| Schiit Audio                         | 1         | 0.03%   |
| Samsung Electronics                  | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 215       | 5.09%   |
| Intel Sunrise Point-LP HD Audio                                            | 204       | 4.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 157       | 3.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 155       | 3.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 136       | 3.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 131       | 3.1%    |
| AMD Starship/Matisse HD Audio Controller                                   | 128       | 3.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 107       | 2.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 105       | 2.49%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 91        | 2.15%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 88        | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 81        | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 79        | 1.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 78        | 1.85%   |
| AMD FCH Azalia Controller                                                  | 75        | 1.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 74        | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 74        | 1.75%   |
| Intel 8 Series HD Audio Controller                                         | 74        | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 72        | 1.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 60        | 1.42%   |
| Intel Comet Lake PCH-LP cAVS                                               | 57        | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 56        | 1.33%   |
| Intel Broadwell-U Audio Controller                                         | 46        | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 46        | 1.09%   |
| Nvidia TU116 High Definition Audio Controller                              | 45        | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 45        | 1.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 45        | 1.07%   |
| Nvidia GP106 High Definition Audio Controller                              | 43        | 1.02%   |
| Intel 200 Series PCH HD Audio                                              | 43        | 1.02%   |
| Intel Comet Lake PCH cAVS                                                  | 41        | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 40        | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 39        | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 39        | 0.92%   |
| AMD Kabini HDMI/DP Audio                                                   | 37        | 0.88%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 36        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 34        | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                              | 33        | 0.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 33        | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 32        | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 31        | 0.73%   |
| Intel CM238 HD Audio Controller                                            | 31        | 0.73%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 30        | 0.71%   |
| AMD Navi 10 HDMI Audio                                                     | 30        | 0.71%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 30        | 0.71%   |
| Nvidia High Definition Audio Controller                                    | 26        | 0.62%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 24        | 0.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 22        | 0.52%   |
| Nvidia GM204 High Definition Audio Controller                              | 21        | 0.5%    |
| Nvidia GM206 High Definition Audio Controller                              | 20        | 0.47%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 20        | 0.47%   |
| Realtek Semiconductor USB Audio                                            | 19        | 0.45%   |
| Nvidia GK107 HDMI Audio Controller                                         | 19        | 0.45%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 18        | 0.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 18        | 0.43%   |
| Nvidia GP108 High Definition Audio Controller                              | 17        | 0.4%    |
| Nvidia GF119 HDMI Audio Controller                                         | 17        | 0.4%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 17        | 0.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 16        | 0.38%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 16        | 0.38%   |
| Nvidia TU104 HD Audio Controller                                           | 15        | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 390       | 21.54%  |
| SK Hynix            | 284       | 15.68%  |
| Kingston            | 243       | 13.42%  |
| Micron Technology   | 177       | 9.77%   |
| Unknown             | 142       | 7.84%   |
| Crucial             | 127       | 7.01%   |
| Corsair             | 119       | 6.57%   |
| G.Skill             | 82        | 4.53%   |
| A-DATA Technology   | 34        | 1.88%   |
| Ramaxel Technology  | 29        | 1.6%    |
| Elpida              | 24        | 1.33%   |
| Nanya Technology    | 21        | 1.16%   |
| Unknown (ABCD)      | 17        | 0.94%   |
| Patriot             | 13        | 0.72%   |
| Team                | 12        | 0.66%   |
| Smart               | 12        | 0.66%   |
| Transcend           | 11        | 0.61%   |
| GOODRAM             | 7         | 0.39%   |
| SMART Brazil        | 5         | 0.28%   |
| Apacer              | 5         | 0.28%   |
| Silicon Power       | 4         | 0.22%   |
| AMD                 | 4         | 0.22%   |
| Teikon              | 3         | 0.17%   |
| ASint Technology    | 3         | 0.17%   |
| Unknown             | 3         | 0.17%   |
| Wilk                | 2         | 0.11%   |
| SHARETRONIC         | 2         | 0.11%   |
| Reboto              | 2         | 0.11%   |
| Kllisre             | 2         | 0.11%   |
| Kingmax             | 2         | 0.11%   |
| Hewlett-Packard     | 2         | 0.11%   |
| Gloway              | 2         | 0.11%   |
| GeIL                | 2         | 0.11%   |
| CSX                 | 2         | 0.11%   |
| Avant               | 2         | 0.11%   |
| V-GeN               | 1         | 0.06%   |
| V-Color             | 1         | 0.06%   |
| Unknown (0x29E)     | 1         | 0.06%   |
| Unknown (0x0C97)    | 1         | 0.06%   |
| Unknown (08AE)      | 1         | 0.06%   |
| Unifosa             | 1         | 0.06%   |
| Shenzhen WODPOSIT   | 1         | 0.06%   |
| PUSKILL             | 1         | 0.06%   |
| OCZ                 | 1         | 0.06%   |
| Mushkin             | 1         | 0.06%   |
| Magnum Tech         | 1         | 0.06%   |
| KingFast            | 1         | 0.06%   |
| imation             | 1         | 0.06%   |
| HBS                 | 1         | 0.06%   |
| Goldkey             | 1         | 0.06%   |
| Centon              | 1         | 0.06%   |
| Axiom               | 1         | 0.06%   |
| atermiter           | 1         | 0.06%   |
| ankowall            | 1         | 0.06%   |
| 48spaces            | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 21        | 1.07%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.97%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 16        | 0.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 16        | 0.82%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 15        | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 15        | 0.77%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.66%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 12        | 0.61%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 12        | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 12        | 0.61%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 12        | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 12        | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 12        | 0.61%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 12        | 0.61%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 11        | 0.56%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 11        | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 0.51%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 10        | 0.51%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 9         | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.46%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.41%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 8         | 0.41%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.41%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 8         | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 7         | 0.36%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.36%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.36%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 7         | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 6         | 0.31%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 6         | 0.31%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 6         | 0.31%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 6         | 0.31%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.31%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 6         | 0.31%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 6         | 0.31%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 6         | 0.31%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s          | 6         | 0.31%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.31%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 5         | 0.26%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 5         | 0.26%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.26%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.26%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.26%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.26%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 5         | 0.26%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 5         | 0.26%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s       | 5         | 0.26%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 5         | 0.26%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.26%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.26%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 5         | 0.26%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 5         | 0.26%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 5         | 0.26%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.26%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 5         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 875       | 56.2%   |
| DDR3    | 475       | 30.51%  |
| LPDDR4  | 54        | 3.47%   |
| Unknown | 44        | 2.83%   |
| LPDDR3  | 42        | 2.7%    |
| DDR2    | 37        | 2.38%   |
| SDRAM   | 23        | 1.48%   |
| DDR     | 6         | 0.39%   |
| DRAM    | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 896       | 57.66%  |
| DIMM         | 552       | 35.52%  |
| Row Of Chips | 91        | 5.86%   |
| Chip         | 9         | 0.58%   |
| Unknown      | 4         | 0.26%   |
| RIMM         | 1         | 0.06%   |
| FB-DIMM      | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 695       | 40.91%  |
| 4096  | 475       | 27.96%  |
| 16384 | 298       | 17.54%  |
| 2048  | 169       | 9.95%   |
| 32768 | 37        | 2.18%   |
| 1024  | 22        | 1.29%   |
| 512   | 1         | 0.06%   |
| 256   | 1         | 0.06%   |
| 128   | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 347       | 20.54%  |
| 1600    | 326       | 19.3%   |
| 3200    | 225       | 13.32%  |
| 2400    | 158       | 9.35%   |
| 1333    | 104       | 6.16%   |
| 2133    | 95        | 5.62%   |
| 3600    | 56        | 3.32%   |
| 1334    | 43        | 2.55%   |
| 800     | 28        | 1.66%   |
| 4267    | 24        | 1.42%   |
| 1867    | 23        | 1.36%   |
| 667     | 21        | 1.24%   |
| 2666    | 20        | 1.18%   |
| 3000    | 19        | 1.12%   |
| 3266    | 16        | 0.95%   |
| Unknown | 16        | 0.95%   |
| 3466    | 14        | 0.83%   |
| 2933    | 14        | 0.83%   |
| 3733    | 12        | 0.71%   |
| 1067    | 12        | 0.71%   |
| 1066    | 12        | 0.71%   |
| 3400    | 8         | 0.47%   |
| 4199    | 7         | 0.41%   |
| 3800    | 7         | 0.41%   |
| 1866    | 7         | 0.41%   |
| 2800    | 6         | 0.36%   |
| 400     | 6         | 0.36%   |
| 3533    | 5         | 0.3%    |
| 2000    | 5         | 0.3%    |
| 4266    | 4         | 0.24%   |
| 3866    | 4         | 0.24%   |
| 3333    | 4         | 0.24%   |
| 3151    | 4         | 0.24%   |
| 2048    | 4         | 0.24%   |
| 1800    | 4         | 0.24%   |
| 975     | 3         | 0.18%   |
| 533     | 3         | 0.18%   |
| 3334    | 2         | 0.12%   |
| 3066    | 2         | 0.12%   |
| 2132    | 2         | 0.12%   |
| 49926   | 1         | 0.06%   |
| 8400    | 1         | 0.06%   |
| 4400    | 1         | 0.06%   |
| 3467    | 1         | 0.06%   |
| 3100    | 1         | 0.06%   |
| 3067    | 1         | 0.06%   |
| 3007    | 1         | 0.06%   |
| 2473    | 1         | 0.06%   |
| 2200    | 1         | 0.06%   |
| 2134    | 1         | 0.06%   |
| 1904    | 1         | 0.06%   |
| 1776    | 1         | 0.06%   |
| 1648    | 1         | 0.06%   |
| 1200    | 1         | 0.06%   |
| 880     | 1         | 0.06%   |
| 666     | 1         | 0.06%   |
| 333     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 36        | 45.57%  |
| Brother Industries     | 17        | 21.52%  |
| Samsung Electronics    | 8         | 10.13%  |
| Canon                  | 8         | 10.13%  |
| Seiko Epson            | 4         | 5.06%   |
| Xerox                  | 1         | 1.27%   |
| Prolific Technology    | 1         | 1.27%   |
| Pantum                 | 1         | 1.27%   |
| Panasonic (Matsushita) | 1         | 1.27%   |
| ICS Advent             | 1         | 1.27%   |
| Apple                  | 1         | 1.27%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP OfficeJet Pro 8020 series                    | 3         | 3.7%    |
| HP OfficeJet Pro 7740 series                    | 2         | 2.47%   |
| HP LaserJet 1018                                | 2         | 2.47%   |
| HP ENVY 5000 series                             | 2         | 2.47%   |
| HP DeskJet 2620 All-in-One Printer              | 2         | 2.47%   |
| Xerox Phaser 6500DN                             | 1         | 1.23%   |
| Seiko Epson WF-2530 Series                      | 1         | 1.23%   |
| Seiko Epson Printer                             | 1         | 1.23%   |
| Seiko Epson L120 Series                         | 1         | 1.23%   |
| Seiko Epson ET-2710 Series                      | 1         | 1.23%   |
| Samsung Xerox Phaser 3117 Laser Printer         | 1         | 1.23%   |
| Samsung SCX-3200 Series                         | 1         | 1.23%   |
| Samsung ML-2250 Series                          | 1         | 1.23%   |
| Samsung ML-216x Series Laser Printer            | 1         | 1.23%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 1.23%   |
| Samsung CLX-3180 Series                         | 1         | 1.23%   |
| Samsung CLX-3170 Series                         | 1         | 1.23%   |
| Samsung CLP-360 Series                          | 1         | 1.23%   |
| Prolific PL2305 Parallel Port                   | 1         | 1.23%   |
| Pantum P2200 series                             | 1         | 1.23%   |
| Panasonic (Matsushita) KX-MB1500CX              | 1         | 1.23%   |
| ICS Advent Parallel Adapter                     | 1         | 1.23%   |
| HP OfficeJet Pro 9010 series                    | 1         | 1.23%   |
| HP OfficeJet 9010 series                        | 1         | 1.23%   |
| HP OfficeJet 4650 series                        | 1         | 1.23%   |
| HP Officejet 4630 series                        | 1         | 1.23%   |
| HP OfficeJet 3830 series                        | 1         | 1.23%   |
| HP LaserJet P2055 series                        | 1         | 1.23%   |
| HP LaserJet P2035                               | 1         | 1.23%   |
| HP LaserJet P2015 series                        | 1         | 1.23%   |
| HP LaserJet P1102                               | 1         | 1.23%   |
| HP LaserJet P1005                               | 1         | 1.23%   |
| HP LaserJet M402dn                              | 1         | 1.23%   |
| HP LaserJet M101-M106                           | 1         | 1.23%   |
| HP LaserJet CP1025nw                            | 1         | 1.23%   |
| HP LaserJet 200 color M251nw                    | 1         | 1.23%   |
| HP LaserJet 1300                                | 1         | 1.23%   |
| HP LaserJet 1020                                | 1         | 1.23%   |
| HP LaserJet 1010                                | 1         | 1.23%   |
| HP Laser 107a                                   | 1         | 1.23%   |
| HP ENVY Photo 7100 series                       | 1         | 1.23%   |
| HP ENVY 4500 series                             | 1         | 1.23%   |
| HP Deskjet F4500 series                         | 1         | 1.23%   |
| HP DeskJet F300 series                          | 1         | 1.23%   |
| HP DeskJet D1360                                | 1         | 1.23%   |
| HP DeskJet 930c                                 | 1         | 1.23%   |
| HP DeskJet 2700 series                          | 1         | 1.23%   |
| HP Deskjet 2540 series                          | 1         | 1.23%   |
| HP Deskjet 1050 J410                            | 1         | 1.23%   |
| Canon PIXMA MX920 Series                        | 1         | 1.23%   |
| Canon PIXMA MX490 Series                        | 1         | 1.23%   |
| Canon PIXMA MP495                               | 1         | 1.23%   |
| Canon PIXMA MP250                               | 1         | 1.23%   |
| Canon PIXMA MG2500 Series                       | 1         | 1.23%   |
| Canon MF4800 Series                             | 1         | 1.23%   |
| Canon LiDE 400                                  | 1         | 1.23%   |
| Canon G3000 series                              | 1         | 1.23%   |
| Brother MFC-L3770CDW                            | 1         | 1.23%   |
| Brother MFC-L2710DW series                      | 1         | 1.23%   |
| Brother MFC-J805DW                              | 1         | 1.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 8         | 47.06%  |
| Seiko Epson     | 4         | 23.53%  |
| Hewlett-Packard | 3         | 17.65%  |
| Mustek Systems  | 2         | 11.76%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 2         | 11.76%  |
| Canon CanoScan LIDE 25                                  | 2         | 11.76%  |
| Canon CanoScan LiDE 220                                 | 2         | 11.76%  |
| Canon CanoScan LiDE 110                                 | 2         | 11.76%  |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 5.88%   |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 5.88%   |
| Mustek Systems SNAPSCAN e22                             | 1         | 5.88%   |
| Mustek Systems BearPaw 1200 CU Plus                     | 1         | 5.88%   |
| HP ScanJet G4010                                        | 1         | 5.88%   |
| HP ScanJet 82x0C                                        | 1         | 5.88%   |
| HP ScanJet 3770                                         | 1         | 5.88%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5.88%   |
| Canon CanoScan LiDE 120                                 | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 310       | 19.12%  |
| IMC Networks                           | 165       | 10.18%  |
| Microdia                               | 144       | 8.88%   |
| Acer                                   | 136       | 8.39%   |
| Realtek Semiconductor                  | 133       | 8.2%    |
| Logitech                               | 128       | 7.9%    |
| Sunplus Innovation Technology          | 86        | 5.31%   |
| Quanta                                 | 66        | 4.07%   |
| Cheng Uei Precision Industry (Foxlink) | 66        | 4.07%   |
| Suyin                                  | 36        | 2.22%   |
| Silicon Motion                         | 34        | 2.1%    |
| Syntek                                 | 31        | 1.91%   |
| Apple                                  | 29        | 1.79%   |
| Lite-On Technology                     | 27        | 1.67%   |
| Microsoft                              | 24        | 1.48%   |
| Alcor Micro                            | 21        | 1.3%    |
| Luxvisions Innotech Limited            | 19        | 1.17%   |
| Samsung Electronics                    | 16        | 0.99%   |
| Ricoh                                  | 13        | 0.8%    |
| Z-Star Microelectronics                | 11        | 0.68%   |
| Generalplus Technology                 | 9         | 0.56%   |
| Genesys Logic                          | 8         | 0.49%   |
| Lenovo                                 | 7         | 0.43%   |
| Huawei Technologies                    | 6         | 0.37%   |
| ARC International                      | 6         | 0.37%   |
| KYE Systems (Mouse Systems)            | 5         | 0.31%   |
| Cubeternet                             | 5         | 0.31%   |
| Sunplus Technology                     | 4         | 0.25%   |
| Sonix Technology                       | 4         | 0.25%   |
| MacroSilicon                           | 4         | 0.25%   |
| Intel                                  | 4         | 0.25%   |
| Importek                               | 4         | 0.25%   |
| Razer USA                              | 3         | 0.19%   |
| Novatek Microelectronics               | 3         | 0.19%   |
| LG Electronics                         | 3         | 0.19%   |
| GEMBIRD                                | 3         | 0.19%   |
| Creative Technology                    | 3         | 0.19%   |
| Unknown                                | 2         | 0.12%   |
| Pixart Imaging                         | 2         | 0.12%   |
| Philips (or NXP)                       | 2         | 0.12%   |
| Google                                 | 2         | 0.12%   |
| DigiTech                               | 2         | 0.12%   |
| CQG-5693-201019                        | 2         | 0.12%   |
| Arkmicro Technologies                  | 2         | 0.12%   |
| ALi                                    | 2         | 0.12%   |
| A4Tech                                 | 2         | 0.12%   |
| Yealink Network Technology             | 1         | 0.06%   |
| Y Media                                | 1         | 0.06%   |
| Xiongmai                               | 1         | 0.06%   |
| webcam                                 | 1         | 0.06%   |
| WCM_USB                                | 1         | 0.06%   |
| Valve Software                         | 1         | 0.06%   |
| USB Camera CS                          | 1         | 0.06%   |
| USB Camera                             | 1         | 0.06%   |
| SunplusIT                              | 1         | 0.06%   |
| Sony                                   | 1         | 0.06%   |
| Primax Electronics                     | 1         | 0.06%   |
| OmniVision Technologies                | 1         | 0.06%   |
| Oculus VR                              | 1         | 0.06%   |
| Nokia Mobile Phones                    | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 67        | 4.08%   |
| Microdia Integrated_Webcam_HD                                   | 61        | 3.72%   |
| Realtek Integrated_Webcam_HD                                    | 60        | 3.66%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 51        | 3.11%   |
| IMC Networks Integrated Camera                                  | 45        | 2.74%   |
| Acer Integrated Camera                                          | 43        | 2.62%   |
| Sunplus Integrated_Webcam_HD                                    | 41        | 2.5%    |
| Chicony HD Webcam                                               | 33        | 2.01%   |
| Logitech Webcam C270                                            | 29        | 1.77%   |
| Logitech HD Pro Webcam C920                                     | 29        | 1.77%   |
| Chicony USB2.0 Camera                                           | 22        | 1.34%   |
| Chicony HP HD Camera                                            | 22        | 1.34%   |
| Syntek Integrated Camera                                        | 21        | 1.28%   |
| Acer Lenovo EasyCamera                                          | 21        | 1.28%   |
| Microdia Integrated Webcam                                      | 18        | 1.1%    |
| Acer HD Webcam                                                  | 16        | 0.98%   |
| Samsung Galaxy A5 (MTP)                                         | 15        | 0.91%   |
| Microdia Webcam Vitade AF                                       | 14        | 0.85%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 14        | 0.85%   |
| Lite-On Integrated Camera                                       | 13        | 0.79%   |
| Chicony HD User Facing                                          | 13        | 0.79%   |
| Quanta HP HD Camera                                             | 12        | 0.73%   |
| Chicony Integrated Camera (1280x720@30)                         | 12        | 0.73%   |
| Chicony HP Wide Vision HD Camera                                | 12        | 0.73%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 12        | 0.73%   |
| Acer BisonCam, NB Pro                                           | 12        | 0.73%   |
| Quanta HD User Facing                                           | 11        | 0.67%   |
| Chicony HP Truevision HD                                        | 11        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera             | 11        | 0.67%   |
| Realtek Integrated Webcam HD                                    | 10        | 0.61%   |
| Chicony USB 2.0 Camera                                          | 10        | 0.61%   |
| Quanta HD WebCam                                                | 9         | 0.55%   |
| Microsoft LifeCam HD-3000                                       | 9         | 0.55%   |
| Acer SunplusIT Integrated Camera                                | 9         | 0.55%   |
| Realtek USB Camera                                              | 8         | 0.49%   |
| Quanta HP Webcam                                                | 8         | 0.49%   |
| Quanta HP TrueVision HD Camera                                  | 8         | 0.49%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 8         | 0.49%   |
| Logitech HD Webcam C615                                         | 8         | 0.49%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 8         | 0.49%   |
| IMC Networks ov9734_azurewave_camera                            | 8         | 0.49%   |
| IMC Networks HD Camera                                          | 8         | 0.49%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 8         | 0.49%   |
| Alcor Micro USB 2.0 Web Camera                                  | 8         | 0.49%   |
| Sunplus HD WebCam                                               | 7         | 0.43%   |
| Realtek Integrated Webcam                                       | 7         | 0.43%   |
| Realtek HD WebCam                                               | 7         | 0.43%   |
| Luxvisions Innotech Limited HP HD Camera                        | 7         | 0.43%   |
| Logitech HD Webcam C525                                         | 7         | 0.43%   |
| IMC Networks USB2.0 HD IR UVC WebCam                            | 7         | 0.43%   |
| Chicony EasyCamera                                              | 7         | 0.43%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 7         | 0.43%   |
| Acer Lenovo Integrated Webcam                                   | 7         | 0.43%   |
| Acer BisonCam,NB Pro                                            | 7         | 0.43%   |
| Syntek EasyCamera                                               | 6         | 0.37%   |
| Suyin HP Truevision HD                                          | 6         | 0.37%   |
| Silicon Motion Web Camera                                       | 6         | 0.37%   |
| Ricoh USB2.0 Camera                                             | 6         | 0.37%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 6         | 0.37%   |
| IMC Networks UVC VGA Webcam                                     | 6         | 0.37%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 112       | 33.23%  |
| Validity Sensors           | 90        | 26.71%  |
| Shenzhen Goodix Technology | 62        | 18.4%   |
| Elan Microelectronics      | 24        | 7.12%   |
| Upek                       | 15        | 4.45%   |
| LighTuning Technology      | 14        | 4.15%   |
| AuthenTec                  | 13        | 3.86%   |
| STMicroelectronics         | 5         | 1.48%   |
| Focal-systems.Corp         | 1         | 0.3%    |
| DigitalPersona             | 1         | 0.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 42        | 12.46%  |
| Unknown                                                                    | 30        | 8.9%    |
| Shenzhen Goodix  FingerPrint Device                                        | 25        | 7.42%   |
| Shenzhen Goodix Fingerprint Reader                                         | 22        | 6.53%   |
| Elan ELAN:Fingerprint                                                      | 19        | 5.64%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 4.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 15        | 4.45%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 4.45%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 3.86%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 3.26%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.67%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 9         | 2.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.37%   |
| Synaptics  WBDI                                                            | 8         | 2.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 2.37%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.37%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 2.08%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.48%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.48%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.48%   |
| AuthenTec AES2810                                                          | 5         | 1.48%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.19%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.89%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.89%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 0.89%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.89%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.89%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 0.89%   |
| Validity Sensors VFS491                                                    | 2         | 0.59%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.59%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.59%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.3%    |
| Synaptics WBDI Device                                                      | 1         | 0.3%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.3%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.3%    |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.3%    |
| AuthenTec AES3500 TruePrint Sensor                                         | 1         | 0.3%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.3%    |
| AuthenTec AES1600                                                          | 1         | 0.3%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 61        | 39.1%   |
| Alcor Micro               | 43        | 27.56%  |
| Upek                      | 11        | 7.05%   |
| O2 Micro                  | 8         | 5.13%   |
| Lenovo                    | 5         | 3.21%   |
| Advanced Card Systems     | 4         | 2.56%   |
| OmniKey                   | 3         | 1.92%   |
| Gemalto (was Gemplus)     | 3         | 1.92%   |
| Yubico.com                | 2         | 1.28%   |
| SCM Microsystems          | 2         | 1.28%   |
| Realtek Semiconductor     | 2         | 1.28%   |
| Fujitsu Siemens Computers | 2         | 1.28%   |
| Watchdata                 | 1         | 0.64%   |
| Reiner SCT Kartensysteme  | 1         | 0.64%   |
| In Focus Systems          | 1         | 0.64%   |
| Giesecke & Devrient       | 1         | 0.64%   |
| Clay Logic                | 1         | 0.64%   |
| Chicony Electronics       | 1         | 0.64%   |
| BIT4ID                    | 1         | 0.64%   |
| ARDS                      | 1         | 0.64%   |
| Aladdin Knowledge Systems | 1         | 0.64%   |
| Aktiv                     | 1         | 0.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 41        | 26.28%  |
| Broadcom 5880                                                                | 18        | 11.54%  |
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 9.62%   |
| Broadcom 58200                                                               | 14        | 8.97%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 7.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 7.05%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 5.13%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.21%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 2.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.92%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.28%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.28%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.28%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.28%   |
| Watchdata USB Key                                                            | 1         | 0.64%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.64%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.64%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.64%   |
| OmniKey CardMan 4321                                                         | 1         | 0.64%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.64%   |
| OmniKey CardMan 1021                                                         | 1         | 0.64%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.64%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.64%   |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.64%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.64%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.64%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.64%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.64%   |
| ARDS JaCarta                                                                 | 1         | 0.64%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.64%   |
| Aktiv Rutoken lite                                                           | 1         | 0.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1689      | 68.44%  |
| 1     | 631       | 25.57%  |
| 2     | 118       | 4.78%   |
| 3     | 14        | 0.57%   |
| 4     | 7         | 0.28%   |
| 6     | 4         | 0.16%   |
| 7     | 3         | 0.12%   |
| 5     | 2         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 331       | 34.84%  |
| Graphics card            | 157       | 16.53%  |
| Chipcard                 | 135       | 14.21%  |
| Net/wireless             | 116       | 12.21%  |
| Sound                    | 32        | 3.37%   |
| Multimedia controller    | 32        | 3.37%   |
| Camera                   | 29        | 3.05%   |
| Bluetooth                | 28        | 2.95%   |
| Communication controller | 25        | 2.63%   |
| Unassigned class         | 20        | 2.11%   |
| Card reader              | 14        | 1.47%   |
| Storage                  | 9         | 0.95%   |
| Net/ethernet             | 6         | 0.63%   |
| Storage/ide              | 4         | 0.42%   |
| Network                  | 4         | 0.42%   |
| Modem                    | 3         | 0.32%   |
| Firewire controller      | 3         | 0.32%   |
| Dvb card                 | 2         | 0.21%   |
