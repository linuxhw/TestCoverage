Linux in Hong Kong - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Hong Kong.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Hong_Kong/Desktop/README.md) and [notebooks](/Location/Hong_Kong/Notebook/README.md).

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

Total: 376

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Compaq        | Tablet PC TC1000            | Notebook    | [80324222a7](https://linux-hardware.org/?probe=80324222a7) | Jun 26, 2022 |
| KOHJINSHA     | SX series                   | Notebook    | [7333815afc](https://linux-hardware.org/?probe=7333815afc) | Jun 26, 2022 |
| Samsung       | SQ1S Revision MP            | Notebook    | [faeb18a49e](https://linux-hardware.org/?probe=faeb18a49e) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [044be44d33](https://linux-hardware.org/?probe=044be44d33) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [5bd3ad4d01](https://linux-hardware.org/?probe=5bd3ad4d01) | Jun 24, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Huanan        | X99-TF                      | Desktop     | [04dc5246af](https://linux-hardware.org/?probe=04dc5246af) | Jun 18, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | Desktop     | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [f4c7f13ff8](https://linux-hardware.org/?probe=f4c7f13ff8) | Jun 14, 2022 |
| Lenovo        | ThinkPad X250 20CLA1VECD    | Notebook    | [e3df184136](https://linux-hardware.org/?probe=e3df184136) | Jun 12, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e373d39f20](https://linux-hardware.org/?probe=e373d39f20) | Jun 09, 2022 |
| Huanan        | X99-TF                      | Desktop     | [4e5364e832](https://linux-hardware.org/?probe=4e5364e832) | Jun 08, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [27301ce2e8](https://linux-hardware.org/?probe=27301ce2e8) | Jun 03, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [2f8215fb0a](https://linux-hardware.org/?probe=2f8215fb0a) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [33de2bbd12](https://linux-hardware.org/?probe=33de2bbd12) | May 31, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [4d4c32223e](https://linux-hardware.org/?probe=4d4c32223e) | May 31, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [4eab57bebf](https://linux-hardware.org/?probe=4eab57bebf) | May 30, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [eee1a317b6](https://linux-hardware.org/?probe=eee1a317b6) | May 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [63fd75f1a8](https://linux-hardware.org/?probe=63fd75f1a8) | May 29, 2022 |
| Lenovo        | Legion Y7000P2020H 82AX     | Notebook    | [220325c031](https://linux-hardware.org/?probe=220325c031) | May 29, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [75d345243e](https://linux-hardware.org/?probe=75d345243e) | May 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7fa4ca7312](https://linux-hardware.org/?probe=7fa4ca7312) | May 23, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [1f67896c5c](https://linux-hardware.org/?probe=1f67896c5c) | May 22, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [a227af798c](https://linux-hardware.org/?probe=a227af798c) | May 20, 2022 |
| Gigabyte      | HA65M-UD3H-B3               | Desktop     | [d368918a0b](https://linux-hardware.org/?probe=d368918a0b) | May 13, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [f0b122c199](https://linux-hardware.org/?probe=f0b122c199) | May 09, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [99e0958898](https://linux-hardware.org/?probe=99e0958898) | May 01, 2022 |
| Dell          | Precision 7520              | Notebook    | [2dc98a1a8d](https://linux-hardware.org/?probe=2dc98a1a8d) | Apr 30, 2022 |
| MSI           | H87I                        | Desktop     | [af4a26a5ea](https://linux-hardware.org/?probe=af4a26a5ea) | Apr 30, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [0633ac7757](https://linux-hardware.org/?probe=0633ac7757) | Apr 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [9191742453](https://linux-hardware.org/?probe=9191742453) | Apr 26, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [56902c7998](https://linux-hardware.org/?probe=56902c7998) | Apr 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [a3aa6e30b9](https://linux-hardware.org/?probe=a3aa6e30b9) | Apr 21, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [3dd8282149](https://linux-hardware.org/?probe=3dd8282149) | Apr 20, 2022 |
| GPD           | P2 MAX                      | Notebook    | [ca842dc5fb](https://linux-hardware.org/?probe=ca842dc5fb) | Apr 19, 2022 |
| Intel         | NUC11PABi5 K90634-304       | Mini pc     | [d359794b2f](https://linux-hardware.org/?probe=d359794b2f) | Apr 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [7ea786c89b](https://linux-hardware.org/?probe=7ea786c89b) | Apr 18, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0ac1f4daf9](https://linux-hardware.org/?probe=0ac1f4daf9) | Apr 12, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [abed3ae34d](https://linux-hardware.org/?probe=abed3ae34d) | Apr 12, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| ASUSTek       | VM62                        | Desktop     | [ae684cdf71](https://linux-hardware.org/?probe=ae684cdf71) | Apr 05, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [bdca066ba3](https://linux-hardware.org/?probe=bdca066ba3) | Apr 05, 2022 |
| ASRock        | H410M-ITX/ac                | Desktop     | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [314bd42e78](https://linux-hardware.org/?probe=314bd42e78) | Mar 28, 2022 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [a881a875bd](https://linux-hardware.org/?probe=a881a875bd) | Mar 27, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [2d48cb4419](https://linux-hardware.org/?probe=2d48cb4419) | Mar 26, 2022 |
| Dell          | 0Y3R3K A03                  | Desktop     | [b772cf9d86](https://linux-hardware.org/?probe=b772cf9d86) | Mar 26, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [e7fb180535](https://linux-hardware.org/?probe=e7fb180535) | Mar 16, 2022 |
| Dell          | Latitude 7285               | Notebook    | [87e555f958](https://linux-hardware.org/?probe=87e555f958) | Mar 13, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [7320ed668a](https://linux-hardware.org/?probe=7320ed668a) | Mar 12, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [03b27c8ca4](https://linux-hardware.org/?probe=03b27c8ca4) | Mar 12, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [4998fff0f9](https://linux-hardware.org/?probe=4998fff0f9) | Mar 12, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [99d3e16ede](https://linux-hardware.org/?probe=99d3e16ede) | Mar 12, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [c68cec2207](https://linux-hardware.org/?probe=c68cec2207) | Mar 11, 2022 |
| Unknown       | Intel X79                   | Desktop     | [e947d6af7f](https://linux-hardware.org/?probe=e947d6af7f) | Mar 11, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [96b36779e0](https://linux-hardware.org/?probe=96b36779e0) | Mar 11, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| HP            | Notebook                    | Notebook    | [9c04c0776d](https://linux-hardware.org/?probe=9c04c0776d) | Mar 10, 2022 |
| HP            | Notebook                    | Notebook    | [c7d735dc99](https://linux-hardware.org/?probe=c7d735dc99) | Mar 10, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0b9a7acb84](https://linux-hardware.org/?probe=0b9a7acb84) | Feb 27, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [3c7daed552](https://linux-hardware.org/?probe=3c7daed552) | Feb 22, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [6c00869d7b](https://linux-hardware.org/?probe=6c00869d7b) | Feb 21, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [0f4fad19b2](https://linux-hardware.org/?probe=0f4fad19b2) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6e5689a733](https://linux-hardware.org/?probe=6e5689a733) | Jan 28, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 Rev ... | Soc         | [2a66f4b578](https://linux-hardware.org/?probe=2a66f4b578) | Jan 24, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [515465fd5a](https://linux-hardware.org/?probe=515465fd5a) | Jan 22, 2022 |
| ASRock        | Z270M-ITX/ac                | Desktop     | [4c32bf6d7b](https://linux-hardware.org/?probe=4c32bf6d7b) | Jan 18, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c5fa4a0cec](https://linux-hardware.org/?probe=c5fa4a0cec) | Dec 24, 2021 |
| ASRock        | H410M-ITX/ac                | Desktop     | [99c341562a](https://linux-hardware.org/?probe=99c341562a) | Dec 21, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| MSI           | 870-G45                     | Desktop     | [e6317a2b91](https://linux-hardware.org/?probe=e6317a2b91) | Dec 19, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| Fujitsu       | LIFEBOOK LH530              | Notebook    | [8db7409ab5](https://linux-hardware.org/?probe=8db7409ab5) | Dec 14, 2021 |
| Unknown       | Intel X79                   | Desktop     | [985655e4b3](https://linux-hardware.org/?probe=985655e4b3) | Dec 11, 2021 |
| Unknown       | Unknown                     | Notebook    | [739be994cb](https://linux-hardware.org/?probe=739be994cb) | Dec 09, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [024a42eb21](https://linux-hardware.org/?probe=024a42eb21) | Dec 08, 2021 |
| Unknown       | Intel X79                   | Desktop     | [6f32192557](https://linux-hardware.org/?probe=6f32192557) | Dec 08, 2021 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| MSI           | Boston                      | Desktop     | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| Supermicro    | C2SBC-Q                     | Desktop     | [1099e48366](https://linux-hardware.org/?probe=1099e48366) | Nov 28, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [58d43162d2](https://linux-hardware.org/?probe=58d43162d2) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ee13ae89af](https://linux-hardware.org/?probe=ee13ae89af) | Nov 26, 2021 |
| Apple         | MacBook10,1                 | Notebook    | [6cb99e6a5f](https://linux-hardware.org/?probe=6cb99e6a5f) | Nov 23, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [fc59694424](https://linux-hardware.org/?probe=fc59694424) | Nov 17, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [35b58ec233](https://linux-hardware.org/?probe=35b58ec233) | Nov 16, 2021 |
| Jumper        | EZbook                      | Notebook    | [5da2b95e2f](https://linux-hardware.org/?probe=5da2b95e2f) | Nov 12, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | Notebook    | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Seco          | C40 C                       | Desktop     | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [9bcd3d5479](https://linux-hardware.org/?probe=9bcd3d5479) | Oct 29, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [c7fc01bd49](https://linux-hardware.org/?probe=c7fc01bd49) | Oct 27, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [6f87ece998](https://linux-hardware.org/?probe=6f87ece998) | Oct 26, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [3d42bc888b](https://linux-hardware.org/?probe=3d42bc888b) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [54e54e71bd](https://linux-hardware.org/?probe=54e54e71bd) | Oct 24, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [aedfc53de6](https://linux-hardware.org/?probe=aedfc53de6) | Oct 20, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [20dc49f637](https://linux-hardware.org/?probe=20dc49f637) | Oct 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [aee062d6e5](https://linux-hardware.org/?probe=aee062d6e5) | Oct 04, 2021 |
| Lenovo        | Legion Y9000P2021H 82JD     | Notebook    | [4c3be0fe24](https://linux-hardware.org/?probe=4c3be0fe24) | Oct 02, 2021 |
| MSI           | H61M-P23                    | Desktop     | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| GPD           | G1618-03                    | Notebook    | [41916177c2](https://linux-hardware.org/?probe=41916177c2) | Sep 01, 2021 |
| GPD           | G1618-03                    | Notebook    | [c2abcaf10c](https://linux-hardware.org/?probe=c2abcaf10c) | Sep 01, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [1440e244f6](https://linux-hardware.org/?probe=1440e244f6) | Aug 26, 2021 |
| Dell          | Precision 7550              | Notebook    | [42721343a3](https://linux-hardware.org/?probe=42721343a3) | Aug 16, 2021 |
| Lenovo        | XiaoXin-14API QC 2019 81... | Notebook    | [814eb97442](https://linux-hardware.org/?probe=814eb97442) | Aug 14, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [d920558127](https://linux-hardware.org/?probe=d920558127) | Aug 14, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5cd377c0e0](https://linux-hardware.org/?probe=5cd377c0e0) | Aug 13, 2021 |
| Gigabyte      | B75M-D2P                    | Desktop     | [5e54c2a102](https://linux-hardware.org/?probe=5e54c2a102) | Aug 12, 2021 |
| Lenovo        | ThinkPad T61 6465CTO        | Notebook    | [d93258840e](https://linux-hardware.org/?probe=d93258840e) | Aug 04, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [eb060cd2c4](https://linux-hardware.org/?probe=eb060cd2c4) | Aug 04, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [828a52387f](https://linux-hardware.org/?probe=828a52387f) | Aug 02, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [12b2c3e130](https://linux-hardware.org/?probe=12b2c3e130) | Aug 01, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [3af43c8ebe](https://linux-hardware.org/?probe=3af43c8ebe) | Jul 29, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [fa0aa86cef](https://linux-hardware.org/?probe=fa0aa86cef) | Jul 28, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [8fc32673b3](https://linux-hardware.org/?probe=8fc32673b3) | Jul 25, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [58b70e282d](https://linux-hardware.org/?probe=58b70e282d) | Jul 14, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [66cf378cf1](https://linux-hardware.org/?probe=66cf378cf1) | Jul 10, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [71da4978c9](https://linux-hardware.org/?probe=71da4978c9) | Jun 29, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [ed911e7e8c](https://linux-hardware.org/?probe=ed911e7e8c) | Jun 26, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [8785d98b0b](https://linux-hardware.org/?probe=8785d98b0b) | Jun 19, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [54e520ac17](https://linux-hardware.org/?probe=54e520ac17) | Jun 17, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [c2bfccf320](https://linux-hardware.org/?probe=c2bfccf320) | Jun 16, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [d3f69874dd](https://linux-hardware.org/?probe=d3f69874dd) | Jun 16, 2021 |
| Lenovo        | IdeaCentre B305 10052       | All in one  | [8399296d51](https://linux-hardware.org/?probe=8399296d51) | Jun 13, 2021 |
| Dell          | Precision M4800             | Notebook    | [298694c222](https://linux-hardware.org/?probe=298694c222) | Jun 12, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [76219e9cca](https://linux-hardware.org/?probe=76219e9cca) | Jun 09, 2021 |
| Acer          | Aspire E5-573               | Notebook    | [4193a2da9d](https://linux-hardware.org/?probe=4193a2da9d) | Jun 08, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [bcb80080a5](https://linux-hardware.org/?probe=bcb80080a5) | Jun 06, 2021 |
| Dell          | Precision M4800             | Notebook    | [67fb08d285](https://linux-hardware.org/?probe=67fb08d285) | Jun 06, 2021 |
| Dell          | Precision M4800             | Notebook    | [c72664a2f4](https://linux-hardware.org/?probe=c72664a2f4) | Jun 06, 2021 |
| HP            | 18E7                        | Desktop     | [9844f6635c](https://linux-hardware.org/?probe=9844f6635c) | May 30, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [81ffc7ba9e](https://linux-hardware.org/?probe=81ffc7ba9e) | May 26, 2021 |
| ASUSTek       | VM62                        | Desktop     | [486aeb5b89](https://linux-hardware.org/?probe=486aeb5b89) | May 25, 2021 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [e19475cd4c](https://linux-hardware.org/?probe=e19475cd4c) | May 22, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [a201bdfc36](https://linux-hardware.org/?probe=a201bdfc36) | May 19, 2021 |
| Fujitsu       | UH-X                        | Notebook    | [be65091e59](https://linux-hardware.org/?probe=be65091e59) | May 19, 2021 |
| ASUSTek       | M4A78-VM                    | Desktop     | [3313d34c41](https://linux-hardware.org/?probe=3313d34c41) | May 15, 2021 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [1409e11b30](https://linux-hardware.org/?probe=1409e11b30) | May 12, 2021 |
| Nvidia        | Tegra                       | Soc         | [54592ec1a2](https://linux-hardware.org/?probe=54592ec1a2) | May 08, 2021 |
| Nvidia        | Tegra                       | Soc         | [ab1c7d5eab](https://linux-hardware.org/?probe=ab1c7d5eab) | May 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [8d372d62b7](https://linux-hardware.org/?probe=8d372d62b7) | May 07, 2021 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [1b777c6f08](https://linux-hardware.org/?probe=1b777c6f08) | May 02, 2021 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [4c7956a34c](https://linux-hardware.org/?probe=4c7956a34c) | May 02, 2021 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [f35a966b00](https://linux-hardware.org/?probe=f35a966b00) | Apr 14, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [a917367457](https://linux-hardware.org/?probe=a917367457) | Apr 09, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [f7937503ac](https://linux-hardware.org/?probe=f7937503ac) | Apr 08, 2021 |
| ASUSTek       | Zephyrus M GM501GM          | Notebook    | [99d71b6ea5](https://linux-hardware.org/?probe=99d71b6ea5) | Apr 06, 2021 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [8253b70553](https://linux-hardware.org/?probe=8253b70553) | Apr 06, 2021 |
| MSI           | Boston                      | Desktop     | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [60600f6f0c](https://linux-hardware.org/?probe=60600f6f0c) | Mar 26, 2021 |
| HP            | 1632                        | Desktop     | [adf9ebb679](https://linux-hardware.org/?probe=adf9ebb679) | Mar 25, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [6a4196e0aa](https://linux-hardware.org/?probe=6a4196e0aa) | Mar 23, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dc64c81c35](https://linux-hardware.org/?probe=dc64c81c35) | Mar 23, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [280785b873](https://linux-hardware.org/?probe=280785b873) | Mar 22, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [20d78f0b3a](https://linux-hardware.org/?probe=20d78f0b3a) | Mar 22, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [71ef988016](https://linux-hardware.org/?probe=71ef988016) | Mar 21, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [e44a5ce779](https://linux-hardware.org/?probe=e44a5ce779) | Mar 14, 2021 |
| ASUSTek       | UX302LA                     | Notebook    | [fe27a8e195](https://linux-hardware.org/?probe=fe27a8e195) | Mar 12, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [d23d84b5f6](https://linux-hardware.org/?probe=d23d84b5f6) | Mar 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [5051ba6156](https://linux-hardware.org/?probe=5051ba6156) | Mar 05, 2021 |
| MSI           | Boston                      | Desktop     | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [b94539c6dc](https://linux-hardware.org/?probe=b94539c6dc) | Mar 01, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [b2cb174b9a](https://linux-hardware.org/?probe=b2cb174b9a) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [2414020b54](https://linux-hardware.org/?probe=2414020b54) | Feb 26, 2021 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [ae61a5e1fa](https://linux-hardware.org/?probe=ae61a5e1fa) | Feb 26, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [87c36a9322](https://linux-hardware.org/?probe=87c36a9322) | Feb 23, 2021 |
| Lenovo        | ThinkPad E14 20RAA002CD     | Notebook    | [77ccb1ee60](https://linux-hardware.org/?probe=77ccb1ee60) | Feb 22, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [7d9f2bee38](https://linux-hardware.org/?probe=7d9f2bee38) | Feb 21, 2021 |
| ASUSTek       | VM45                        | Desktop     | [03eeb85521](https://linux-hardware.org/?probe=03eeb85521) | Feb 21, 2021 |
| ASUSTek       | VM65-K                      | Desktop     | [6b97cf71eb](https://linux-hardware.org/?probe=6b97cf71eb) | Feb 18, 2021 |
| ASUSTek       | VM65-K                      | Desktop     | [4f0bcd1276](https://linux-hardware.org/?probe=4f0bcd1276) | Feb 17, 2021 |
| ASUSTek       | VM40B                       | Desktop     | [6c0bf22f39](https://linux-hardware.org/?probe=6c0bf22f39) | Feb 17, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [d82924b12b](https://linux-hardware.org/?probe=d82924b12b) | Feb 16, 2021 |
| Dell          | 0D02VH A01                  | Desktop     | [ebc5645105](https://linux-hardware.org/?probe=ebc5645105) | Feb 11, 2021 |
| Lenovo        | IdeaCentre K330             | Desktop     | [78ce34058b](https://linux-hardware.org/?probe=78ce34058b) | Feb 11, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [f4c2a6bac8](https://linux-hardware.org/?probe=f4c2a6bac8) | Feb 07, 2021 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [d4f69c78fa](https://linux-hardware.org/?probe=d4f69c78fa) | Jan 31, 2021 |
| Fujitsu       | S6420                       | Notebook    | [b23c0f10e7](https://linux-hardware.org/?probe=b23c0f10e7) | Jan 28, 2021 |
| Fujitsu       | S6420                       | Notebook    | [0cf6376b40](https://linux-hardware.org/?probe=0cf6376b40) | Jan 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [1d0000672d](https://linux-hardware.org/?probe=1d0000672d) | Jan 23, 2021 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [3d7ce778c6](https://linux-hardware.org/?probe=3d7ce778c6) | Jan 20, 2021 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [fe7d03f093](https://linux-hardware.org/?probe=fe7d03f093) | Jan 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [b8f5d6f1e4](https://linux-hardware.org/?probe=b8f5d6f1e4) | Jan 16, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [39bc70ca5d](https://linux-hardware.org/?probe=39bc70ca5d) | Jan 13, 2021 |
| ASRock        | H410M-HDV                   | Desktop     | [d2420f233b](https://linux-hardware.org/?probe=d2420f233b) | Jan 10, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| Dell          | 0TP412                      | Desktop     | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| Intel         | NUC6CAYB J23203-406         | Mini pc     | [038dce10fa](https://linux-hardware.org/?probe=038dce10fa) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [a8ac85cb5a](https://linux-hardware.org/?probe=a8ac85cb5a) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [8c7ba97457](https://linux-hardware.org/?probe=8c7ba97457) | Dec 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [01333c5b9e](https://linux-hardware.org/?probe=01333c5b9e) | Dec 29, 2020 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [728d7e48d4](https://linux-hardware.org/?probe=728d7e48d4) | Dec 27, 2020 |
| Lenovo        | ThinkPad X270 20HNA00RAD    | Notebook    | [1d4b16bb0d](https://linux-hardware.org/?probe=1d4b16bb0d) | Dec 22, 2020 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [cf7386e848](https://linux-hardware.org/?probe=cf7386e848) | Dec 18, 2020 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [88a7edec45](https://linux-hardware.org/?probe=88a7edec45) | Dec 18, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [1d6b7df7b4](https://linux-hardware.org/?probe=1d6b7df7b4) | Dec 08, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [8309aa39cf](https://linux-hardware.org/?probe=8309aa39cf) | Nov 30, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [ede3032fed](https://linux-hardware.org/?probe=ede3032fed) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [f3012a2898](https://linux-hardware.org/?probe=f3012a2898) | Nov 29, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [37d5acae7d](https://linux-hardware.org/?probe=37d5acae7d) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [3c4ff5bb58](https://linux-hardware.org/?probe=3c4ff5bb58) | Nov 27, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [97c485886b](https://linux-hardware.org/?probe=97c485886b) | Nov 25, 2020 |
| Dell          | 0D02VH A01                  | Desktop     | [8f55b945a1](https://linux-hardware.org/?probe=8f55b945a1) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | Notebook    | [f55a6a6679](https://linux-hardware.org/?probe=f55a6a6679) | Nov 20, 2020 |
| Fujitsu       | UH-X                        | Notebook    | [7aea886f7a](https://linux-hardware.org/?probe=7aea886f7a) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [de597aa847](https://linux-hardware.org/?probe=de597aa847) | Nov 20, 2020 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f5aa8c9150](https://linux-hardware.org/?probe=f5aa8c9150) | Nov 20, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a3c484b8ee](https://linux-hardware.org/?probe=a3c484b8ee) | Nov 16, 2020 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [6254edfb10](https://linux-hardware.org/?probe=6254edfb10) | Nov 14, 2020 |
| Lenovo        | G770 20089                  | Notebook    | [6da9203114](https://linux-hardware.org/?probe=6da9203114) | Nov 13, 2020 |
| HP            | 2000                        | Notebook    | [f548e6d1cc](https://linux-hardware.org/?probe=f548e6d1cc) | Nov 11, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [e1700b887e](https://linux-hardware.org/?probe=e1700b887e) | Nov 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [69fb29494b](https://linux-hardware.org/?probe=69fb29494b) | Nov 07, 2020 |
| HP            | 2000                        | Notebook    | [df76d279ad](https://linux-hardware.org/?probe=df76d279ad) | Nov 05, 2020 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [f90977870e](https://linux-hardware.org/?probe=f90977870e) | Nov 04, 2020 |
| Timi          | TM1607                      | Notebook    | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| ZOTAC         | ZBOX-ID92/ZBOX-IQ01         | Mini pc     | [fbba9f6a3b](https://linux-hardware.org/?probe=fbba9f6a3b) | Nov 02, 2020 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [e970e25954](https://linux-hardware.org/?probe=e970e25954) | Nov 02, 2020 |
| Acer          | Swift SF314-57              | Notebook    | [8395e5a946](https://linux-hardware.org/?probe=8395e5a946) | Oct 30, 2020 |
| Acer          | Swift SF314-57              | Notebook    | [123f60c868](https://linux-hardware.org/?probe=123f60c868) | Oct 29, 2020 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | Notebook    | [f9d1166197](https://linux-hardware.org/?probe=f9d1166197) | Oct 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77849f8db0](https://linux-hardware.org/?probe=77849f8db0) | Oct 23, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [77d6dd66e2](https://linux-hardware.org/?probe=77d6dd66e2) | Oct 23, 2020 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [1af7b2b551](https://linux-hardware.org/?probe=1af7b2b551) | Oct 13, 2020 |
| HP            | 2140                        | Notebook    | [bde3dc449f](https://linux-hardware.org/?probe=bde3dc449f) | Oct 07, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [1fe32b8f6d](https://linux-hardware.org/?probe=1fe32b8f6d) | Oct 04, 2020 |
| HP            | 2000                        | Notebook    | [fbd8bf0e69](https://linux-hardware.org/?probe=fbd8bf0e69) | Oct 01, 2020 |
| Fujitsu       | LIFEBOOK S904               | Notebook    | [5035864c45](https://linux-hardware.org/?probe=5035864c45) | Sep 27, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [37e6b406f7](https://linux-hardware.org/?probe=37e6b406f7) | Sep 27, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [bd8f561b0b](https://linux-hardware.org/?probe=bd8f561b0b) | Sep 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e292456297](https://linux-hardware.org/?probe=e292456297) | Sep 17, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e7b41f62a4](https://linux-hardware.org/?probe=e7b41f62a4) | Sep 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [20bdbc68b7](https://linux-hardware.org/?probe=20bdbc68b7) | Sep 12, 2020 |
| ASUSTek       | H81M-E                      | Desktop     | [43b8c677bc](https://linux-hardware.org/?probe=43b8c677bc) | Sep 10, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [24cad8bed5](https://linux-hardware.org/?probe=24cad8bed5) | Aug 28, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [3d4c2a283d](https://linux-hardware.org/?probe=3d4c2a283d) | Aug 28, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [64a249acd1](https://linux-hardware.org/?probe=64a249acd1) | Aug 28, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [6a91a7b38c](https://linux-hardware.org/?probe=6a91a7b38c) | Aug 25, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [e27db6fb31](https://linux-hardware.org/?probe=e27db6fb31) | Aug 24, 2020 |
| Samsung       | 930XBE                      | Notebook    | [92925e0656](https://linux-hardware.org/?probe=92925e0656) | Aug 24, 2020 |
| HP            | 802E                        | Desktop     | [653b11eec3](https://linux-hardware.org/?probe=653b11eec3) | Aug 11, 2020 |
| HP            | 802E                        | Desktop     | [6f32afeb2b](https://linux-hardware.org/?probe=6f32afeb2b) | Aug 10, 2020 |
| HP            | 802E                        | Desktop     | [25d8ddc0bb](https://linux-hardware.org/?probe=25d8ddc0bb) | Aug 10, 2020 |
| Dell          | Inspiron 5580               | Notebook    | [fbaf2b8f7f](https://linux-hardware.org/?probe=fbaf2b8f7f) | Aug 05, 2020 |
| Panasonic     | CFSZ5-2L                    | Notebook    | [e7488a8b16](https://linux-hardware.org/?probe=e7488a8b16) | Aug 04, 2020 |
| Toshiba       | PORTEGE R830                | Notebook    | [fa44f09e6e](https://linux-hardware.org/?probe=fa44f09e6e) | Aug 03, 2020 |
| Dell          | G7 7588                     | Notebook    | [e85e2949de](https://linux-hardware.org/?probe=e85e2949de) | Aug 01, 2020 |
| Lenovo        | ZHAOYANG K47                | Notebook    | [fa5be40392](https://linux-hardware.org/?probe=fa5be40392) | Jul 24, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [50dc692a9e](https://linux-hardware.org/?probe=50dc692a9e) | Jul 23, 2020 |
| Lenovo        | ZHAOYANG K47                | Notebook    | [879b0d586f](https://linux-hardware.org/?probe=879b0d586f) | Jul 22, 2020 |
| Gigabyte      | Z170X-Gaming 5 Modified ... | Desktop     | [a62f520dc3](https://linux-hardware.org/?probe=a62f520dc3) | Jul 18, 2020 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [723898cdec](https://linux-hardware.org/?probe=723898cdec) | Jun 20, 2020 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [f897dd388f](https://linux-hardware.org/?probe=f897dd388f) | Jun 17, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [c90b1cb242](https://linux-hardware.org/?probe=c90b1cb242) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [74dadf599d](https://linux-hardware.org/?probe=74dadf599d) | Jun 14, 2020 |
| Lenovo        | E10-30 20424                | Notebook    | [db21903e1a](https://linux-hardware.org/?probe=db21903e1a) | Jun 14, 2020 |
| Lenovo        | ThinkPad T480s 20L7005FU... | Notebook    | [2bc99eeca5](https://linux-hardware.org/?probe=2bc99eeca5) | Jun 09, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| HP            | 1998                        | Desktop     | [255863fefb](https://linux-hardware.org/?probe=255863fefb) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | Desktop     | [b159b440f2](https://linux-hardware.org/?probe=b159b440f2) | Jun 01, 2020 |
| Lenovo        | ThinkCentre M90p 3269A12    | Desktop     | [4181637bf3](https://linux-hardware.org/?probe=4181637bf3) | Jun 01, 2020 |
| Fujitsu       | LIFEBOOK AH556              | Notebook    | [c16b3d9827](https://linux-hardware.org/?probe=c16b3d9827) | May 30, 2020 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [55680319a1](https://linux-hardware.org/?probe=55680319a1) | May 29, 2020 |
| Biostar       | H110MHC                     | Desktop     | [98d1029698](https://linux-hardware.org/?probe=98d1029698) | May 26, 2020 |
| ASUSTek       | B150M-C                     | Desktop     | [2229b866b3](https://linux-hardware.org/?probe=2229b866b3) | May 26, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Apple         | MacBookPro7,1               | Notebook    | [956da1ac80](https://linux-hardware.org/?probe=956da1ac80) | May 11, 2020 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| Toshiba       | PORTEGE R830                | Notebook    | [08f3e97afe](https://linux-hardware.org/?probe=08f3e97afe) | May 02, 2020 |
| Lenovo        | 3000 G410                   | Notebook    | [2a909aaad5](https://linux-hardware.org/?probe=2a909aaad5) | May 02, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [179a82277c](https://linux-hardware.org/?probe=179a82277c) | May 01, 2020 |
| MSI           | 2A9C                        | Desktop     | [23df26e5de](https://linux-hardware.org/?probe=23df26e5de) | Apr 25, 2020 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [664ac5b85b](https://linux-hardware.org/?probe=664ac5b85b) | Apr 24, 2020 |
| MSI           | Boston                      | Desktop     | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [f11d6eedc7](https://linux-hardware.org/?probe=f11d6eedc7) | Apr 14, 2020 |
| HP            | G72                         | Notebook    | [6272536a26](https://linux-hardware.org/?probe=6272536a26) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [f504649d96](https://linux-hardware.org/?probe=f504649d96) | Apr 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [3916938374](https://linux-hardware.org/?probe=3916938374) | Apr 11, 2020 |
| Gigabyte      | Z87-HD3                     | Desktop     | [52a7dab5ac](https://linux-hardware.org/?probe=52a7dab5ac) | Apr 09, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [9c72670aa1](https://linux-hardware.org/?probe=9c72670aa1) | Apr 05, 2020 |
| Google        | Eve                         | Notebook    | [17c248ca99](https://linux-hardware.org/?probe=17c248ca99) | Apr 04, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [37fb7cae94](https://linux-hardware.org/?probe=37fb7cae94) | Mar 30, 2020 |
| MSI           | B360M FIRE                  | Desktop     | [8bb021d2a6](https://linux-hardware.org/?probe=8bb021d2a6) | Mar 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [18b565a861](https://linux-hardware.org/?probe=18b565a861) | Mar 26, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [abce376627](https://linux-hardware.org/?probe=abce376627) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e6860a26ae](https://linux-hardware.org/?probe=e6860a26ae) | Mar 24, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [5f2e14b65b](https://linux-hardware.org/?probe=5f2e14b65b) | Mar 16, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [1bcf8a4701](https://linux-hardware.org/?probe=1bcf8a4701) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [bd55777a4f](https://linux-hardware.org/?probe=bd55777a4f) | Mar 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [137262daa3](https://linux-hardware.org/?probe=137262daa3) | Mar 05, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [597092ba51](https://linux-hardware.org/?probe=597092ba51) | Feb 28, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [71fc35ceea](https://linux-hardware.org/?probe=71fc35ceea) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [047acafb1a](https://linux-hardware.org/?probe=047acafb1a) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e8315b1469](https://linux-hardware.org/?probe=e8315b1469) | Feb 28, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [04e5b85d84](https://linux-hardware.org/?probe=04e5b85d84) | Feb 28, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [310ae04477](https://linux-hardware.org/?probe=310ae04477) | Feb 27, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [046814376c](https://linux-hardware.org/?probe=046814376c) | Feb 20, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [a417965167](https://linux-hardware.org/?probe=a417965167) | Feb 19, 2020 |
| Intel         | DH77DF AAG40293-301         | Desktop     | [ac00169b1c](https://linux-hardware.org/?probe=ac00169b1c) | Feb 14, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [cef9a00862](https://linux-hardware.org/?probe=cef9a00862) | Feb 12, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [dcc65f9ee3](https://linux-hardware.org/?probe=dcc65f9ee3) | Feb 11, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [900a11f8b3](https://linux-hardware.org/?probe=900a11f8b3) | Feb 10, 2020 |
| MSI           | GS73VR 7RG                  | Notebook    | [fbdf43d1d6](https://linux-hardware.org/?probe=fbdf43d1d6) | Feb 04, 2020 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [20d5a3bd6a](https://linux-hardware.org/?probe=20d5a3bd6a) | Feb 01, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cf4dbec684](https://linux-hardware.org/?probe=cf4dbec684) | Feb 01, 2020 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Gigabyte      | P55A-UD3                    | Desktop     | [7168fd0137](https://linux-hardware.org/?probe=7168fd0137) | Jan 11, 2020 |
| Unknown       | Unknown                     | Notebook    | [1007637420](https://linux-hardware.org/?probe=1007637420) | Dec 31, 2019 |
| Unknown       | Unknown                     | Notebook    | [bb58a92938](https://linux-hardware.org/?probe=bb58a92938) | Dec 31, 2019 |
| ASUSTek       | Z8NA-D6                     | Desktop     | [b2d6dabaa7](https://linux-hardware.org/?probe=b2d6dabaa7) | Dec 23, 2019 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [e3b6ce369a](https://linux-hardware.org/?probe=e3b6ce369a) | Dec 23, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [0f39165d62](https://linux-hardware.org/?probe=0f39165d62) | Dec 06, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [816ad4feea](https://linux-hardware.org/?probe=816ad4feea) | Dec 06, 2019 |
| ASUSTek       | X556URK                     | Notebook    | [78f15ad5f0](https://linux-hardware.org/?probe=78f15ad5f0) | Nov 30, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [49e2cab57b](https://linux-hardware.org/?probe=49e2cab57b) | Nov 28, 2019 |
| HUAWEI        | KPRC-WX0                    | Notebook    | [042c4b3c5a](https://linux-hardware.org/?probe=042c4b3c5a) | Nov 22, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [f63dcc4fc8](https://linux-hardware.org/?probe=f63dcc4fc8) | Nov 07, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [15f84fa3f2](https://linux-hardware.org/?probe=15f84fa3f2) | Oct 26, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3497939f58](https://linux-hardware.org/?probe=3497939f58) | Oct 18, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a04ed98be8](https://linux-hardware.org/?probe=a04ed98be8) | Oct 18, 2019 |
| CompuLab      | Airtop                      | Mini pc     | [ff3ce414e4](https://linux-hardware.org/?probe=ff3ce414e4) | Oct 16, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [b2ebcf2c70](https://linux-hardware.org/?probe=b2ebcf2c70) | Oct 10, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [43a5e168a1](https://linux-hardware.org/?probe=43a5e168a1) | Oct 10, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [3392a03f3c](https://linux-hardware.org/?probe=3392a03f3c) | Oct 03, 2019 |
| Unknown       | Unknown                     | Notebook    | [f8f1207d2d](https://linux-hardware.org/?probe=f8f1207d2d) | Sep 29, 2019 |
| Unknown       | Unknown                     | Notebook    | [d19b3f1330](https://linux-hardware.org/?probe=d19b3f1330) | Sep 28, 2019 |
| Unknown       | Unknown                     | Notebook    | [a6d4347345](https://linux-hardware.org/?probe=a6d4347345) | Sep 28, 2019 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [4302e84025](https://linux-hardware.org/?probe=4302e84025) | Sep 24, 2019 |
| Acer          | Aspire S3-371               | Notebook    | [5086f9ddaa](https://linux-hardware.org/?probe=5086f9ddaa) | Sep 07, 2019 |
| Acer          | Aspire S3-371               | Notebook    | [aa8140a178](https://linux-hardware.org/?probe=aa8140a178) | Sep 03, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [e8ccb234ed](https://linux-hardware.org/?probe=e8ccb234ed) | Aug 30, 2019 |
| ASRock        | B75M R2.0                   | Desktop     | [1479826c17](https://linux-hardware.org/?probe=1479826c17) | Aug 28, 2019 |
| Hardkernel    | ODROID-H2                   | Desktop     | [26d6c60ad5](https://linux-hardware.org/?probe=26d6c60ad5) | Jul 06, 2019 |
| Gigabyte      | GA-MA78GM-S2HP              | Desktop     | [ea2ad2bc4d](https://linux-hardware.org/?probe=ea2ad2bc4d) | Jun 05, 2019 |
| ASUSTek       | TUF GAMING FX504GM_FX80G... | Notebook    | [7e9553ea70](https://linux-hardware.org/?probe=7e9553ea70) | Jun 03, 2019 |
| Lenovo        | ThinkPad T430 2342AG4       | Notebook    | [cf7413e712](https://linux-hardware.org/?probe=cf7413e712) | May 31, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [e8a5c28644](https://linux-hardware.org/?probe=e8a5c28644) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [b67f52c0c2](https://linux-hardware.org/?probe=b67f52c0c2) | May 29, 2019 |
| Lenovo        | ThinkPad X220 4290NL5       | Notebook    | [c408ceb62e](https://linux-hardware.org/?probe=c408ceb62e) | May 29, 2019 |
| Dell          | Latitude E4310              | Notebook    | [134afc5b6b](https://linux-hardware.org/?probe=134afc5b6b) | May 08, 2019 |
| Lenovo        | ThinkPad T520 4242BC5       | Notebook    | [977c44b97a](https://linux-hardware.org/?probe=977c44b97a) | Apr 29, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | Notebook    | [5801835e32](https://linux-hardware.org/?probe=5801835e32) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 64751W1       | Notebook    | [0f4999f205](https://linux-hardware.org/?probe=0f4999f205) | Apr 27, 2019 |
| Dell          | 0CRH6C A01                  | Desktop     | [23dcf2aff6](https://linux-hardware.org/?probe=23dcf2aff6) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [61bb547684](https://linux-hardware.org/?probe=61bb547684) | Apr 08, 2019 |
| ASUSTek       | B150M-A                     | Desktop     | [8549b6dfd8](https://linux-hardware.org/?probe=8549b6dfd8) | Apr 08, 2019 |
| Unknown       | A11-COMPUTER                | Notebook    | [fae06bb10f](https://linux-hardware.org/?probe=fae06bb10f) | Mar 28, 2019 |
| Unknown       | A11-COMPUTER                | Notebook    | [427daf4d4e](https://linux-hardware.org/?probe=427daf4d4e) | Mar 28, 2019 |
| Lenovo        | ThinkPad W530 24384KU       | Notebook    | [2064d92892](https://linux-hardware.org/?probe=2064d92892) | Dec 12, 2018 |
| Dell          | XPS 13 9350                 | Notebook    | [6fb539c340](https://linux-hardware.org/?probe=6fb539c340) | Oct 29, 2018 |
| ASRock        | Z270 Killer SLI             | Desktop     | [a03ea38833](https://linux-hardware.org/?probe=a03ea38833) | Jul 06, 2018 |
| HP            | ProBook 4540s               | Notebook    | [ace9a95fb7](https://linux-hardware.org/?probe=ace9a95fb7) | May 09, 2018 |
| HP            | ProBook 4540s               | Notebook    | [8f50260d94](https://linux-hardware.org/?probe=8f50260d94) | May 09, 2018 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [17f0958960](https://linux-hardware.org/?probe=17f0958960) | Oct 06, 2017 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 44        | 17.05%  |
| Ubuntu 18.04                 | 23        | 8.91%   |
| OpenMandriva 4.2             | 12        | 4.65%   |
| Ubuntu 19.10                 | 8         | 3.1%    |
| Arch                         | 8         | 3.1%    |
| KDE neon 20.04               | 7         | 2.71%   |
| Ubuntu 20.10                 | 6         | 2.33%   |
| Gentoo 2.7                   | 6         | 2.33%   |
| Fedora 35                    | 6         | 2.33%   |
| Fedora 32                    | 6         | 2.33%   |
| ArcoLinux Rolling            | 5         | 1.94%   |
| Arch Rolling                 | 5         | 1.94%   |
| Ubuntu 22.04                 | 4         | 1.55%   |
| Ubuntu 21.04                 | 4         | 1.55%   |
| Ubuntu 19.04                 | 4         | 1.55%   |
| Pop!_OS 20.10                | 4         | 1.55%   |
| OpenMandriva 4.3             | 4         | 1.55%   |
| Linux Mint 20                | 4         | 1.55%   |
| Fedora 33                    | 4         | 1.55%   |
| Debian 11                    | 4         | 1.55%   |
| Ubuntu 21.10                 | 3         | 1.16%   |
| Ubuntu 16.04                 | 3         | 1.16%   |
| Pop!_OS 22.04                | 3         | 1.16%   |
| Linux Mint 20.3              | 3         | 1.16%   |
| EndeavourOS Rolling          | 3         | 1.16%   |
| Elementary 5.1.7             | 3         | 1.16%   |
| Chrome OS                    | 3         | 1.16%   |
| antiX 21                     | 3         | 1.16%   |
| Zorin 15                     | 2         | 0.78%   |
| Pop!_OS 21.04                | 2         | 0.78%   |
| Pop!_OS 20.04                | 2         | 0.78%   |
| Parrot 4.9                   | 2         | 0.78%   |
| OpenMandriva 4.50            | 2         | 0.78%   |
| Manjaro 21.1.0               | 2         | 0.78%   |
| Manjaro 20.1                 | 2         | 0.78%   |
| Kubuntu 21.10                | 2         | 0.78%   |
| Gentoo 2.8                   | 2         | 0.78%   |
| Fedora 36                    | 2         | 0.78%   |
| Fedora 34                    | 2         | 0.78%   |
| Fedora 31                    | 2         | 0.78%   |
| CentOS 8                     | 2         | 0.78%   |
| Zorin 16                     | 1         | 0.39%   |
| Xubuntu 18.04                | 1         | 0.39%   |
| UbuntuDDE 21.10              | 1         | 0.39%   |
| Ubuntu MATE 20.10            | 1         | 0.39%   |
| Ubuntu MATE 20.04            | 1         | 0.39%   |
| Ubuntu Budgie 20.04          | 1         | 0.39%   |
| Slackware 15.0               | 1         | 0.39%   |
| Slackware 14.2               | 1         | 0.39%   |
| ROSA R8.1                    | 1         | 0.39%   |
| ROSA R11                     | 1         | 0.39%   |
| ROSA R10                     | 1         | 0.39%   |
| Raspbian 11                  | 1         | 0.39%   |
| Pop!_OS 21.10                | 1         | 0.39%   |
| PCLinuxOS 2020               | 1         | 0.39%   |
| Oracle Linux 8.6             | 1         | 0.39%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.39%   |
| Manjaro 21.0.6               | 1         | 0.39%   |
| Manjaro 21.0                 | 1         | 0.39%   |
| Manjaro 20.2.1               | 1         | 0.39%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 93        | 37.35%  |
| Fedora        | 23        | 9.24%   |
| OpenMandriva  | 18        | 7.23%   |
| Arch          | 13        | 5.22%   |
| Pop!_OS       | 12        | 4.82%   |
| Manjaro       | 9         | 3.61%   |
| Linux Mint    | 9         | 3.61%   |
| KDE neon      | 7         | 2.81%   |
| Gentoo        | 7         | 2.81%   |
| Clear Linux   | 5         | 2.01%   |
| ArcoLinux     | 5         | 2.01%   |
| EndeavourOS   | 4         | 1.61%   |
| Elementary    | 4         | 1.61%   |
| Debian        | 4         | 1.61%   |
| Zorin         | 3         | 1.2%    |
| ROSA          | 3         | 1.2%    |
| Kubuntu       | 3         | 1.2%    |
| Chrome OS     | 3         | 1.2%    |
| CentOS        | 3         | 1.2%    |
| antiX         | 3         | 1.2%    |
| Ubuntu MATE   | 2         | 0.8%    |
| Slackware     | 2         | 0.8%    |
| Parrot        | 2         | 0.8%    |
| Kali          | 2         | 0.8%    |
| Xubuntu       | 1         | 0.4%    |
| UbuntuDDE     | 1         | 0.4%    |
| Ubuntu Budgie | 1         | 0.4%    |
| Raspbian      | 1         | 0.4%    |
| PCLinuxOS     | 1         | 0.4%    |
| Oracle Linux  | 1         | 0.4%    |
| openSUSE      | 1         | 0.4%    |
| Lubuntu       | 1         | 0.4%    |
| BlackPanther  | 1         | 0.4%    |
| Artix         | 1         | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002  | 12        | 4.2%    |
| 5.4.0-42-generic          | 9         | 3.15%   |
| 5.16.7-desktop-1omv4003   | 4         | 1.4%    |
| 5.13.0-39-generic         | 4         | 1.4%    |
| 5.13.0-35-generic         | 4         | 1.4%    |
| 5.8.0-7630-generic        | 3         | 1.05%   |
| 5.8.0-55-generic          | 3         | 1.05%   |
| 5.8.0-43-generic          | 3         | 1.05%   |
| 5.4.0-48-generic          | 3         | 1.05%   |
| 5.4.0-33-generic          | 3         | 1.05%   |
| 5.4.0-28-generic          | 3         | 1.05%   |
| 5.4.0-26-generic          | 3         | 1.05%   |
| 5.3.0-46-generic          | 3         | 1.05%   |
| 5.11.0-37-generic         | 3         | 1.05%   |
| 4.9.0-279-antix.1-486-smp | 3         | 1.05%   |
| 4.19.49+                  | 3         | 1.05%   |
| 5.9.2-arch1-1             | 2         | 0.7%    |
| 5.5.0-1parrot1-amd64      | 2         | 0.7%    |
| 5.4.0-58-generic          | 2         | 0.7%    |
| 5.4.0-56-generic          | 2         | 0.7%    |
| 5.4.0-52-generic          | 2         | 0.7%    |
| 5.4.0-47-generic          | 2         | 0.7%    |
| 5.4.0-109-generic         | 2         | 0.7%    |
| 5.3.0-24-generic          | 2         | 0.7%    |
| 5.3.0-18-generic          | 2         | 0.7%    |
| 5.17.5-76051705-generic   | 2         | 0.7%    |
| 5.17.11-300.fc36.x86_64   | 2         | 0.7%    |
| 5.16.12-200.fc35.x86_64   | 2         | 0.7%    |
| 5.13.0-7614-generic       | 2         | 0.7%    |
| 5.13.0-21-generic         | 2         | 0.7%    |
| 5.11.0-43-generic         | 2         | 0.7%    |
| 5.11.0-41-generic         | 2         | 0.7%    |
| 5.11.0-25-generic         | 2         | 0.7%    |
| 5.10.76-gentoo-r1-x86_64  | 2         | 0.7%    |
| 5.0.0-37-generic          | 2         | 0.7%    |
| 5.0.0-32-generic          | 2         | 0.7%    |
| 5.0.0-31-generic          | 2         | 0.7%    |
| 5.0.0-25-generic          | 2         | 0.7%    |
| 4.18.0-15-generic         | 2         | 0.7%    |
| 4.15.0-88-generic         | 2         | 0.7%    |
| 4.15.0-65-generic         | 2         | 0.7%    |
| 4.15.0-47-generic         | 2         | 0.7%    |
| 5.9.8-200.fc33.x86_64     | 1         | 0.35%   |
| 5.9.4-zen1-1-zen          | 1         | 0.35%   |
| 5.9.3-arch1-1             | 1         | 0.35%   |
| 5.9.16-050916-generic     | 1         | 0.35%   |
| 5.9.14-100.fc32.x86_64    | 1         | 0.35%   |
| 5.9.12-artix1-1           | 1         | 0.35%   |
| 5.9.10-artix1-1           | 1         | 0.35%   |
| 5.9.0-kali1-amd64         | 1         | 0.35%   |
| 5.8.7-arch1-1             | 1         | 0.35%   |
| 5.8.6-1-MANJARO           | 1         | 0.35%   |
| 5.8.3-2-MANJARO           | 1         | 0.35%   |
| 5.8.16-2-MANJARO          | 1         | 0.35%   |
| 5.8.15-gentoo             | 1         | 0.35%   |
| 5.8.13-100.fc31.x86_64    | 1         | 0.35%   |
| 5.8.0-7642-generic        | 1         | 0.35%   |
| 5.8.0-64-generic          | 1         | 0.35%   |
| 5.8.0-63-generic          | 1         | 0.35%   |
| 5.8.0-60-generic          | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 40        | 14.98%  |
| 5.8.0   | 22        | 8.24%   |
| 5.13.0  | 17        | 6.37%   |
| 5.11.0  | 15        | 5.62%   |
| 4.15.0  | 14        | 5.24%   |
| 5.3.0   | 12        | 4.49%   |
| 5.10.14 | 12        | 4.49%   |
| 5.0.0   | 10        | 3.75%   |
| 5.15.0  | 5         | 1.87%   |
| 4.18.0  | 5         | 1.87%   |
| 5.16.7  | 4         | 1.5%    |
| 5.10.0  | 4         | 1.5%    |
| 5.17.5  | 3         | 1.12%   |
| 4.9.0   | 3         | 1.12%   |
| 4.19.49 | 3         | 1.12%   |
| 5.9.2   | 2         | 0.75%   |
| 5.5.0   | 2         | 0.75%   |
| 5.17.4  | 2         | 0.75%   |
| 5.17.11 | 2         | 0.75%   |
| 5.16.12 | 2         | 0.75%   |
| 5.16.11 | 2         | 0.75%   |
| 5.14.14 | 2         | 0.75%   |
| 5.10.76 | 2         | 0.75%   |
| 5.9.8   | 1         | 0.37%   |
| 5.9.4   | 1         | 0.37%   |
| 5.9.3   | 1         | 0.37%   |
| 5.9.16  | 1         | 0.37%   |
| 5.9.14  | 1         | 0.37%   |
| 5.9.12  | 1         | 0.37%   |
| 5.9.10  | 1         | 0.37%   |
| 5.9.0   | 1         | 0.37%   |
| 5.8.7   | 1         | 0.37%   |
| 5.8.6   | 1         | 0.37%   |
| 5.8.3   | 1         | 0.37%   |
| 5.8.16  | 1         | 0.37%   |
| 5.8.15  | 1         | 0.37%   |
| 5.8.13  | 1         | 0.37%   |
| 5.7.9   | 1         | 0.37%   |
| 5.7.7   | 1         | 0.37%   |
| 5.7.4   | 1         | 0.37%   |
| 5.7.11  | 1         | 0.37%   |
| 5.7.10  | 1         | 0.37%   |
| 5.7.0   | 1         | 0.37%   |
| 5.6.3   | 1         | 0.37%   |
| 5.6.14  | 1         | 0.37%   |
| 5.6.0   | 1         | 0.37%   |
| 5.5.10  | 1         | 0.37%   |
| 5.4.17  | 1         | 0.37%   |
| 5.3.5   | 1         | 0.37%   |
| 5.3.14  | 1         | 0.37%   |
| 5.3.11  | 1         | 0.37%   |
| 5.18.5  | 1         | 0.37%   |
| 5.18.2  | 1         | 0.37%   |
| 5.17.9  | 1         | 0.37%   |
| 5.17.3  | 1         | 0.37%   |
| 5.17.1  | 1         | 0.37%   |
| 5.17.0  | 1         | 0.37%   |
| 5.16.20 | 1         | 0.37%   |
| 5.16.2  | 1         | 0.37%   |
| 5.16.19 | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 40        | 15.15%  |
| 5.8     | 28        | 10.61%  |
| 5.10    | 28        | 10.61%  |
| 5.13    | 21        | 7.95%   |
| 5.11    | 21        | 7.95%   |
| 5.3     | 15        | 5.68%   |
| 4.15    | 14        | 5.3%    |
| 5.15    | 12        | 4.55%   |
| 5.17    | 11        | 4.17%   |
| 5.16    | 11        | 4.17%   |
| 5.9     | 10        | 3.79%   |
| 5.0     | 10        | 3.79%   |
| 4.9     | 7         | 2.65%   |
| 5.7     | 6         | 2.27%   |
| 5.14    | 6         | 2.27%   |
| 4.18    | 6         | 2.27%   |
| 5.6     | 3         | 1.14%   |
| 5.5     | 3         | 1.14%   |
| 5.12    | 3         | 1.14%   |
| 4.19    | 3         | 1.14%   |
| 5.18    | 2         | 0.76%   |
| 4.4     | 2         | 0.76%   |
| 4.17    | 1         | 0.38%   |
| 3.10    | 1         | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 231       | 94.67%  |
| i686    | 7         | 2.87%   |
| aarch64 | 4         | 1.64%   |
| i586    | 1         | 0.41%   |
| armv7l  | 1         | 0.41%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 117       | 46.06%  |
| Unknown    | 44        | 17.32%  |
| KDE5       | 43        | 16.93%  |
| XFCE       | 10        | 3.94%   |
| KDE        | 8         | 3.15%   |
| X-Cinnamon | 6         | 2.36%   |
| MATE       | 4         | 1.57%   |
| i3         | 4         | 1.57%   |
| Unity      | 3         | 1.18%   |
| Pantheon   | 3         | 1.18%   |
| openbox    | 2         | 0.79%   |
| LXDE       | 2         | 0.79%   |
| Deepin     | 2         | 0.79%   |
| LXQt       | 1         | 0.39%   |
| KDE4       | 1         | 0.39%   |
| fvwm       | 1         | 0.39%   |
| Cinnamon   | 1         | 0.39%   |
| Budgie     | 1         | 0.39%   |
| awesome    | 1         | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 199       | 79.28%  |
| Wayland | 31        | 12.35%  |
| Unknown | 17        | 6.77%   |
| Tty     | 4         | 1.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 131       | 52.19%  |
| SDDM    | 47        | 18.73%  |
| GDM     | 37        | 14.74%  |
| GDM3    | 14        | 5.58%   |
| LightDM | 13        | 5.18%   |
| TDM     | 7         | 2.79%   |
| XDM     | 1         | 0.4%    |
| KDM     | 1         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 88        | 34.78%  |
| en_HK   | 69        | 27.27%  |
| Unknown | 32        | 12.65%  |
| zh_CN   | 23        | 9.09%   |
| zh_TW   | 13        | 5.14%   |
| zh_HK   | 11        | 4.35%   |
| en_GB   | 7         | 2.77%   |
| C       | 5         | 1.98%   |
| en_AU   | 3         | 1.19%   |
| it_IT   | 1         | 0.4%    |
| en_ZA   | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 148       | 59.68%  |
| BIOS | 100       | 40.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 185       | 74.3%   |
| Btrfs   | 25        | 10.04%  |
| Overlay | 14        | 5.62%   |
| Xfs     | 8         | 3.21%   |
| Unknown | 8         | 3.21%   |
| Zfs     | 5         | 2.01%   |
| Ext3    | 2         | 0.8%    |
| F2fs    | 1         | 0.4%    |
| Ext2    | 1         | 0.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 130       | 52.42%  |
| GPT     | 98        | 39.52%  |
| MBR     | 20        | 8.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 215       | 87.04%  |
| Yes       | 32        | 12.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 162       | 65.06%  |
| Yes       | 87        | 34.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 49        | 20.08%  |
| ASUSTek Computer        | 40        | 16.39%  |
| Dell                    | 23        | 9.43%   |
| Gigabyte Technology     | 21        | 8.61%   |
| MSI                     | 19        | 7.79%   |
| Hewlett-Packard         | 19        | 7.79%   |
| Fujitsu                 | 10        | 4.1%    |
| ASRock                  | 9         | 3.69%   |
| Unknown                 | 9         | 3.69%   |
| Acer                    | 5         | 2.05%   |
| Raspberry Pi Foundation | 4         | 1.64%   |
| Intel                   | 4         | 1.64%   |
| Apple                   | 4         | 1.64%   |
| HUAWEI                  | 3         | 1.23%   |
| Toshiba                 | 2         | 0.82%   |
| Supermicro              | 2         | 0.82%   |
| Samsung Electronics     | 2         | 0.82%   |
| GPD                     | 2         | 0.82%   |
| ZOTAC                   | 1         | 0.41%   |
| Timi                    | 1         | 0.41%   |
| Sony                    | 1         | 0.41%   |
| Seco                    | 1         | 0.41%   |
| Schenker                | 1         | 0.41%   |
| Panasonic               | 1         | 0.41%   |
| Nvidia                  | 1         | 0.41%   |
| KOHJINSHA               | 1         | 0.41%   |
| Jumper                  | 1         | 0.41%   |
| Intel Client Systems    | 1         | 0.41%   |
| Huanan                  | 1         | 0.41%   |
| Hardkernel              | 1         | 0.41%   |
| Google                  | 1         | 0.41%   |
| Foxconn                 | 1         | 0.41%   |
| CompuLab                | 1         | 0.41%   |
| Compaq                  | 1         | 0.41%   |
| Biostar                 | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 9         | 3.69%   |
| ASUS H110I-PLUS                              | 3         | 1.23%   |
| ASUS All Series                              | 3         | 1.23%   |
| RPi Raspberry Pi                             | 2         | 0.82%   |
| MSI MS-7C94                                  | 2         | 0.82%   |
| Lenovo Legion R7000 2020 82B6                | 2         | 0.82%   |
| HUAWEI KPRC-WX0                              | 2         | 0.82%   |
| HP ZHAN 66 Pro 14 G4 Notebook PC             | 2         | 0.82%   |
| HP EliteBook 2540p                           | 2         | 0.82%   |
| Gigabyte X570 AORUS ELITE                    | 2         | 0.82%   |
| Fujitsu UH-X                                 | 2         | 0.82%   |
| Fujitsu LIFEBOOK AH544                       | 2         | 0.82%   |
| Dell XPS 13 9310                             | 2         | 0.82%   |
| Dell Inspiron 5580                           | 2         | 0.82%   |
| ASUS Z8NA-D6                                 | 2         | 0.82%   |
| ASUS VM65                                    | 2         | 0.82%   |
| ASUS VM62                                    | 2         | 0.82%   |
| ASUS TUF Gaming FA506IU_FA506IU              | 2         | 0.82%   |
| ASRock H410M-ITX/ac                          | 2         | 0.82%   |
| ASRock H410M-HDV                             | 2         | 0.82%   |
| ZOTAC ZBOX-ID92/ZBOX-IQ01                    | 1         | 0.41%   |
| Toshiba PORTEGE R830                         | 1         | 0.41%   |
| Toshiba dynabook R731/E                      | 1         | 0.41%   |
| Timi TM1607                                  | 1         | 0.41%   |
| Supermicro PIO-617R-TLN4F+-ST031             | 1         | 0.41%   |
| Supermicro C2SBC-Q                           | 1         | 0.41%   |
| Sony VPCCB17FG                               | 1         | 0.41%   |
| Seco C40                                     | 1         | 0.41%   |
| Schenker XMG_APEX15_XAP15E20                 | 1         | 0.41%   |
| Samsung SQ1S                                 | 1         | 0.41%   |
| Samsung 930XBE                               | 1         | 0.41%   |
| RPi Raspberry Pi Zero 2 Rev 1.0              | 1         | 0.41%   |
| RPi Raspberry Pi 400 Rev 1.0                 | 1         | 0.41%   |
| Panasonic CFSZ5-2L                           | 1         | 0.41%   |
| Nvidia Tegra                                 | 1         | 0.41%   |
| MSI Pro 3130 Small Form Factor PC            | 1         | 0.41%   |
| MSI MS-7C52                                  | 1         | 0.41%   |
| MSI MS-7C34                                  | 1         | 0.41%   |
| MSI MS-7C02                                  | 1         | 0.41%   |
| MSI MS-7B93                                  | 1         | 0.41%   |
| MSI MS-7B89                                  | 1         | 0.41%   |
| MSI MS-7B78                                  | 1         | 0.41%   |
| MSI MS-7B53                                  | 1         | 0.41%   |
| MSI MS-7A40                                  | 1         | 0.41%   |
| MSI MS-7A38                                  | 1         | 0.41%   |
| MSI MS-7918                                  | 1         | 0.41%   |
| MSI MS-7851                                  | 1         | 0.41%   |
| MSI MS-7798                                  | 1         | 0.41%   |
| MSI MS-7680                                  | 1         | 0.41%   |
| MSI MS-7599                                  | 1         | 0.41%   |
| MSI KT541AA-UUB a6528hk                      | 1         | 0.41%   |
| MSI GS73VR 7RG                               | 1         | 0.41%   |
| Lenovo ZHENGJIUZHE REN9000K-34IMZ 90Q90022CP | 1         | 0.41%   |
| Lenovo ZHAOYANG K47                          | 1         | 0.41%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS           | 1         | 0.41%   |
| Lenovo Yoga DuetITL 2021 82MA                | 1         | 0.41%   |
| Lenovo Yoga 730-15IWL 81JS                   | 1         | 0.41%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN            | 1         | 0.41%   |
| Lenovo XiaoXin-14API QC 2019 81UW            | 1         | 0.41%   |
| Lenovo XiaoXin Chao7000-14IKBR 81GA          | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Lenovo ThinkPad                  | 19        | 7.79%   |
| Unknown                          | 9         | 3.69%   |
| Fujitsu LIFEBOOK                 | 7         | 2.87%   |
| Dell Inspiron                    | 7         | 2.87%   |
| Dell XPS                         | 6         | 2.46%   |
| Lenovo Legion                    | 5         | 2.05%   |
| Lenovo IdeaPad                   | 5         | 2.05%   |
| Dell Precision                   | 5         | 2.05%   |
| ASUS TUF                         | 5         | 2.05%   |
| RPi Raspberry                    | 4         | 1.64%   |
| Acer Aspire                      | 4         | 1.64%   |
| Lenovo Yoga                      | 3         | 1.23%   |
| Lenovo ThinkCentre               | 3         | 1.23%   |
| HP EliteBook                     | 3         | 1.23%   |
| Gigabyte X570                    | 3         | 1.23%   |
| ASUS ROG                         | 3         | 1.23%   |
| ASUS PRIME                       | 3         | 1.23%   |
| ASUS H110I-PLUS                  | 3         | 1.23%   |
| ASUS All                         | 3         | 1.23%   |
| MSI MS-7C94                      | 2         | 0.82%   |
| Lenovo IdeaPadFlex               | 2         | 0.82%   |
| Lenovo IdeaCentre                | 2         | 0.82%   |
| HUAWEI KPRC-WX0                  | 2         | 0.82%   |
| HP ZHAN                          | 2         | 0.82%   |
| HP ProDesk                       | 2         | 0.82%   |
| Fujitsu UH-X                     | 2         | 0.82%   |
| Dell OptiPlex                    | 2         | 0.82%   |
| Dell Latitude                    | 2         | 0.82%   |
| ASUS Z8NA-D6                     | 2         | 0.82%   |
| ASUS VM65                        | 2         | 0.82%   |
| ASUS VM62                        | 2         | 0.82%   |
| ASRock H410M-ITX                 | 2         | 0.82%   |
| ASRock H410M-HDV                 | 2         | 0.82%   |
| ZOTAC ZBOX-ID92                  | 1         | 0.41%   |
| Toshiba PORTEGE                  | 1         | 0.41%   |
| Toshiba dynabook                 | 1         | 0.41%   |
| Timi TM1607                      | 1         | 0.41%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1         | 0.41%   |
| Supermicro C2SBC-Q               | 1         | 0.41%   |
| Sony VPCCB17FG                   | 1         | 0.41%   |
| Seco C40                         | 1         | 0.41%   |
| Schenker XMG                     | 1         | 0.41%   |
| Samsung SQ1S                     | 1         | 0.41%   |
| Samsung 930XBE                   | 1         | 0.41%   |
| Panasonic CFSZ5-2L               | 1         | 0.41%   |
| Nvidia Tegra                     | 1         | 0.41%   |
| MSI Pro                          | 1         | 0.41%   |
| MSI MS-7C52                      | 1         | 0.41%   |
| MSI MS-7C34                      | 1         | 0.41%   |
| MSI MS-7C02                      | 1         | 0.41%   |
| MSI MS-7B93                      | 1         | 0.41%   |
| MSI MS-7B89                      | 1         | 0.41%   |
| MSI MS-7B78                      | 1         | 0.41%   |
| MSI MS-7B53                      | 1         | 0.41%   |
| MSI MS-7A40                      | 1         | 0.41%   |
| MSI MS-7A38                      | 1         | 0.41%   |
| MSI MS-7918                      | 1         | 0.41%   |
| MSI MS-7851                      | 1         | 0.41%   |
| MSI MS-7798                      | 1         | 0.41%   |
| MSI MS-7680                      | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 33        | 13.52%  |
| 2018    | 33        | 13.52%  |
| 2019    | 27        | 11.07%  |
| 2021    | 20        | 8.2%    |
| 2010    | 16        | 6.56%   |
| 2013    | 15        | 6.15%   |
| 2011    | 15        | 6.15%   |
| 2016    | 14        | 5.74%   |
| 2015    | 13        | 5.33%   |
| 2014    | 13        | 5.33%   |
| 2017    | 12        | 4.92%   |
| 2012    | 10        | 4.1%    |
| 2008    | 7         | 2.87%   |
| Unknown | 5         | 2.05%   |
| 2022    | 4         | 1.64%   |
| 2009    | 3         | 1.23%   |
| 2007    | 3         | 1.23%   |
| 2003    | 1         | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 124       | 50.82%  |
| Desktop        | 103       | 42.21%  |
| System on chip | 5         | 2.05%   |
| Mini pc        | 5         | 2.05%   |
| Convertible    | 4         | 1.64%   |
| All in one     | 2         | 0.82%   |
| Tablet         | 1         | 0.41%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 223       | 91.39%  |
| Enabled  | 21        | 8.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 243       | 99.59%  |
| Yes  | 1         | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 56        | 22.67%  |
| 8.01-16.0   | 55        | 22.27%  |
| 4.01-8.0    | 42        | 17%     |
| 32.01-64.0  | 32        | 12.96%  |
| 3.01-4.0    | 30        | 12.15%  |
| 64.01-256.0 | 16        | 6.48%   |
| 24.01-32.0  | 5         | 2.02%   |
| 2.01-3.0    | 5         | 2.02%   |
| 1.01-2.0    | 3         | 1.21%   |
| 0.51-1.0    | 2         | 0.81%   |
| 0.01-0.5    | 1         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 81        | 30.8%   |
| 2.01-3.0   | 64        | 24.33%  |
| 4.01-8.0   | 46        | 17.49%  |
| 3.01-4.0   | 35        | 13.31%  |
| 8.01-16.0  | 14        | 5.32%   |
| 0.51-1.0   | 9         | 3.42%   |
| 0.01-0.5   | 9         | 3.42%   |
| 16.01-24.0 | 5         | 1.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 53.75%  |
| 2      | 73        | 28.85%  |
| 3      | 25        | 9.88%   |
| 5      | 6         | 2.37%   |
| 4      | 6         | 2.37%   |
| 9      | 2         | 0.79%   |
| 6      | 2         | 0.79%   |
| 0      | 2         | 0.79%   |
| 7      | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 178       | 71.49%  |
| Yes       | 71        | 28.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 81.15%  |
| No        | 46        | 18.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 76.11%  |
| No        | 59        | 23.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 65.06%  |
| No        | 87        | 34.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Hong Kong | 244       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Central          | 135       | 52.53%  |
| Tuen Mun         | 11        | 4.28%   |
| Kowloon          | 11        | 4.28%   |
| Tseung Kwan O    | 8         | 3.11%   |
| Shatin           | 7         | 2.72%   |
| Wanchai          | 6         | 2.33%   |
| Tung Chung       | 6         | 2.33%   |
| Ngau Wu Tok      | 6         | 2.33%   |
| Hong Kong        | 6         | 2.33%   |
| Yuen Long        | 5         | 1.95%   |
| Hung Hom         | 5         | 1.95%   |
| To Kwa Wan       | 4         | 1.56%   |
| Tai Po           | 4         | 1.56%   |
| Sai Kung         | 3         | 1.17%   |
| Quarry Bay       | 3         | 1.17%   |
| Ma On Shan Tsuen | 3         | 1.17%   |
| Tai Wan To       | 2         | 0.78%   |
| Man Kok          | 2         | 0.78%   |
| Kwun Hang        | 2         | 0.78%   |
| Kwu Tung         | 2         | 0.78%   |
| Kowloon Bay      | 2         | 0.78%   |
| Fanling          | 2         | 0.78%   |
| Discovery Bay    | 2         | 0.78%   |
| Cheung Sha Lan   | 2         | 0.78%   |
| Yau Tsim Mong    | 1         | 0.39%   |
| Wong Tai Sin     | 1         | 0.39%   |
| Tsuen Wan        | 1         | 0.39%   |
| Tsimshatsui      | 1         | 0.39%   |
| Tin Shui Wai     | 1         | 0.39%   |
| Tai Wan          | 1         | 0.39%   |
| Tai Kok Tsui     | 1         | 0.39%   |
| Sheung Shui      | 1         | 0.39%   |
| Shau Kei Wan     | 1         | 0.39%   |
| Sham Shui Po     | 1         | 0.39%   |
| North Point      | 1         | 0.39%   |
| North            | 1         | 0.39%   |
| Mong Kok         | 1         | 0.39%   |
| Ma Wan           | 1         | 0.39%   |
| Lam Tin          | 1         | 0.39%   |
| Ho Man Tin       | 1         | 0.39%   |
| Fo Tan           | 1         | 0.39%   |
| Causeway Bay     | 1         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 57        | 76     | 14.84%  |
| Seagate                     | 46        | 65     | 11.98%  |
| WDC                         | 45        | 71     | 11.72%  |
| Toshiba                     | 21        | 28     | 5.47%   |
| SanDisk                     | 18        | 19     | 4.69%   |
| Unknown                     | 17        | 21     | 4.43%   |
| Kingston                    | 16        | 18     | 4.17%   |
| Intel                       | 14        | 20     | 3.65%   |
| Hitachi                     | 14        | 19     | 3.65%   |
| A-DATA Technology           | 13        | 19     | 3.39%   |
| SK hynix                    | 9         | 13     | 2.34%   |
| HGST                        | 9         | 10     | 2.34%   |
| Crucial                     | 9         | 12     | 2.34%   |
| Fujitsu                     | 7         | 13     | 1.82%   |
| Phison                      | 6         | 9      | 1.56%   |
| JMicron Technology          | 6         | 10     | 1.56%   |
| Silicon Motion              | 5         | 6      | 1.3%    |
| Micron Technology           | 5         | 6      | 1.3%    |
| LITEON                      | 4         | 4      | 1.04%   |
| Transcend                   | 3         | 3      | 0.78%   |
| Team                        | 3         | 3      | 0.78%   |
| KIOXIA                      | 3         | 3      | 0.78%   |
| Hikvision                   | 3         | 3      | 0.78%   |
| DOGGO                       | 3         | 3      | 0.78%   |
| China                       | 3         | 4      | 0.78%   |
| Apple                       | 3         | 4      | 0.78%   |
| Unknown                     | 3         | 3      | 0.78%   |
| ZHITAI                      | 2         | 3      | 0.52%   |
| Plextor                     | 2         | 2      | 0.52%   |
| Lite-On                     | 2         | 3      | 0.52%   |
| Lexar                       | 2         | 2      | 0.52%   |
| KingSpec                    | 2         | 3      | 0.52%   |
| HS-SSD-C100                 | 2         | 3      | 0.52%   |
| Gigabyte Technology         | 2         | 5      | 0.52%   |
| BIWIN                       | 2         | 2      | 0.52%   |
| Apacer                      | 2         | 5      | 0.52%   |
| Yangtze Memory Technologies | 1         | 1      | 0.26%   |
| XPG                         | 1         | 1      | 0.26%   |
| Verbatim                    | 1         | 2      | 0.26%   |
| TO Exter                    | 1         | 1      | 0.26%   |
| tigo                        | 1         | 1      | 0.26%   |
| SPCC                        | 1         | 1      | 0.26%   |
| ShineDisk                   | 1         | 1      | 0.26%   |
| RECADATA                    | 1         | 1      | 0.26%   |
| Ramsta                      | 1         | 1      | 0.26%   |
| PNY                         | 1         | 1      | 0.26%   |
| PH4-CE12                    | 1         | 1      | 0.26%   |
| OCZ                         | 1         | 1      | 0.26%   |
| Maxmemory                   | 1         | 2      | 0.26%   |
| KIOXIA-EXCERIA              | 1         | 2      | 0.26%   |
| HGST HTS                    | 1         | 1      | 0.26%   |
| Hewlett-Packard             | 1         | 1      | 0.26%   |
| GALAX TA                    | 1         | 1      | 0.26%   |
| Faspeed                     | 1         | 1      | 0.26%   |
| Dogfish                     | 1         | 1      | 0.26%   |
| Corsair                     | 1         | 1      | 0.26%   |
| Aoluska                     | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 1TB              | 6         | 1.44%   |
| Samsung NVMe SSD Drive 512GB         | 5         | 1.2%    |
| JMicron Generic 2TB                  | 5         | 1.2%    |
| Fujitsu F300 480GB                   | 5         | 1.2%    |
| Unknown MMC Card  32GB               | 4         | 0.96%   |
| Toshiba DT01ACA100 1TB               | 4         | 0.96%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.96%   |
| Crucial CT500MX500SSD1 500GB         | 4         | 0.96%   |
| A-DATA SP550 240GB SSD               | 4         | 0.96%   |
| WDC WD10EZEX-08WN4A0 1TB             | 3         | 0.72%   |
| Unknown MMC Card  64GB               | 3         | 0.72%   |
| Toshiba DT01ACA050 500GB             | 3         | 0.72%   |
| Seagate ST500DM002-1BD142 500GB      | 3         | 0.72%   |
| Seagate ST3500413AS 500GB            | 3         | 0.72%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 0.72%   |
| Samsung SSD 970 EVO Plus 2TB         | 3         | 0.72%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.72%   |
| Samsung NVMe SSD Drive 1TB           | 3         | 0.72%   |
| Samsung NVMe SSD Drive 1024GB        | 3         | 0.72%   |
| DOGGO DQ-60G SSD                     | 3         | 0.72%   |
| Unknown                              | 3         | 0.72%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.48%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 2         | 0.48%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 2         | 0.48%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 2         | 0.48%   |
| WDC WD30EZRX-00D8PB0 3TB             | 2         | 0.48%   |
| WDC WD10SPZX-22Z10T1 1TB             | 2         | 0.48%   |
| Unknown SD32G  32GB                  | 2         | 0.48%   |
| Unknown MMC Card  128GB              | 2         | 0.48%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.48%   |
| Toshiba DT01ACA300 3TB               | 2         | 0.48%   |
| SK hynix SC311 SATA 128GB SSD        | 2         | 0.48%   |
| SK hynix BC501 NVMe 128GB            | 2         | 0.48%   |
| Silicon Motion NVMe SSD Drive 512GB  | 2         | 0.48%   |
| Silicon Motion NVMe SSD Drive 1024GB | 2         | 0.48%   |
| Seagate ST4000DM004-2CV104 4TB       | 2         | 0.48%   |
| Seagate ST3250318AS 250GB            | 2         | 0.48%   |
| Seagate ST3250310AS 250GB            | 2         | 0.48%   |
| Seagate ST3160815AS 160GB            | 2         | 0.48%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.48%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 0.48%   |
| SanDisk NVMe SSD Drive 500GB         | 2         | 0.48%   |
| SanDisk NVMe SSD Drive 256GB         | 2         | 0.48%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.48%   |
| Samsung MZVLB512HBJQ-000L2 512GB     | 2         | 0.48%   |
| Samsung MZVL2512HCJQ-00BL2 512GB     | 2         | 0.48%   |
| Plextor PX-128M7VC 128GB SSD         | 2         | 0.48%   |
| LITEON CV6-CQ128 128GB SSD           | 2         | 0.48%   |
| Lite-On NVMe SSD Drive 512GB         | 2         | 0.48%   |
| Lexar 512GB SSD                      | 2         | 0.48%   |
| KIOXIA NVMe SSD Drive 512GB          | 2         | 0.48%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.48%   |
| Kingston SA2000M81000G 1TB           | 2         | 0.48%   |
| Intel SSDPEKNW020T8 2TB              | 2         | 0.48%   |
| Intel SSDPEKKW256G7 256GB            | 2         | 0.48%   |
| Intel NVMe SSD Drive 512GB           | 2         | 0.48%   |
| HS-SSD-C100 960G                     | 2         | 0.48%   |
| Hitachi HDT721010SLA360 1TB          | 2         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 46        | 65     | 36.51%  |
| WDC                | 28        | 49     | 22.22%  |
| Toshiba            | 19        | 26     | 15.08%  |
| Hitachi            | 14        | 19     | 11.11%  |
| HGST               | 9         | 10     | 7.14%   |
| JMicron Technology | 6         | 10     | 4.76%   |
| Unknown            | 1         | 1      | 0.79%   |
| HGST HTS           | 1         | 1      | 0.79%   |
| Fujitsu            | 1         | 1      | 0.79%   |
| Apple              | 1         | 1      | 0.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 35     | 20.66%  |
| A-DATA Technology   | 11        | 17     | 9.09%   |
| Kingston            | 10        | 11     | 8.26%   |
| Crucial             | 9         | 12     | 7.44%   |
| WDC                 | 8         | 8      | 6.61%   |
| SanDisk             | 6         | 6      | 4.96%   |
| Intel               | 5         | 9      | 4.13%   |
| Fujitsu             | 5         | 11     | 4.13%   |
| Transcend           | 3         | 3      | 2.48%   |
| Team                | 3         | 3      | 2.48%   |
| LITEON              | 3         | 3      | 2.48%   |
| DOGGO               | 3         | 3      | 2.48%   |
| China               | 3         | 4      | 2.48%   |
| ZHITAI              | 2         | 2      | 1.65%   |
| SK hynix            | 2         | 6      | 1.65%   |
| Plextor             | 2         | 2      | 1.65%   |
| Micron Technology   | 2         | 3      | 1.65%   |
| Lexar               | 2         | 2      | 1.65%   |
| Hikvision           | 2         | 2      | 1.65%   |
| Apacer              | 2         | 5      | 1.65%   |
| Verbatim            | 1         | 2      | 0.83%   |
| TO Exter            | 1         | 1      | 0.83%   |
| tigo                | 1         | 1      | 0.83%   |
| SPCC                | 1         | 1      | 0.83%   |
| RECADATA            | 1         | 1      | 0.83%   |
| Ramsta              | 1         | 1      | 0.83%   |
| PNY                 | 1         | 1      | 0.83%   |
| OCZ                 | 1         | 1      | 0.83%   |
| Dogfish             | 1         | 1      | 0.83%   |
| Corsair             | 1         | 1      | 0.83%   |
| BIWIN               | 1         | 1      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |
| Aoluska             | 1         | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 109       | 183    | 31.87%  |
| SSD     | 105       | 161    | 30.7%   |
| NVMe    | 99        | 137    | 28.95%  |
| MMC     | 18        | 22     | 5.26%   |
| Unknown | 11        | 14     | 3.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 168       | 326    | 54.55%  |
| NVMe | 99        | 137    | 32.14%  |
| SAS  | 23        | 32     | 7.47%   |
| MMC  | 18        | 22     | 5.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 122       | 190    | 54.95%  |
| 0.51-1.0   | 58        | 76     | 26.13%  |
| 1.01-2.0   | 24        | 32     | 10.81%  |
| 2.01-3.0   | 8         | 13     | 3.6%    |
| 3.01-4.0   | 6         | 27     | 2.7%    |
| 4.01-10.0  | 3         | 5      | 1.35%   |
| 10.01-20.0 | 1         | 1      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 26.07%  |
| 251-500        | 51        | 19.84%  |
| 501-1000       | 36        | 14.01%  |
| 1001-2000      | 27        | 10.51%  |
| 51-100         | 25        | 9.73%   |
| 1-20           | 14        | 5.45%   |
| More than 3000 | 11        | 4.28%   |
| 2001-3000      | 11        | 4.28%   |
| 21-50          | 8         | 3.11%   |
| Unknown        | 7         | 2.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 112       | 41.18%  |
| 21-50          | 34        | 12.5%   |
| 101-250        | 32        | 11.76%  |
| 251-500        | 29        | 10.66%  |
| 51-100         | 28        | 10.29%  |
| 501-1000       | 15        | 5.51%   |
| 1001-2000      | 10        | 3.68%   |
| Unknown        | 7         | 2.57%   |
| 2001-3000      | 4         | 1.47%   |
| More than 3000 | 1         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| WDC WD30EZRX-00D8PB0 3TB                  | 1         | 1      | 4.76%   |
| WDC WD10EZEX-60WN4A1 1TB                  | 1         | 1      | 4.76%   |
| WDC WD10EZEX-00RKKA0 1TB                  | 1         | 1      | 4.76%   |
| WDC WD10EALS-00Z8A0 1TB                   | 1         | 2      | 4.76%   |
| Toshiba MK1252GSX 120GB                   | 1         | 1      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 4.76%   |
| Seagate ST3250310AS 250GB                 | 1         | 1      | 4.76%   |
| Seagate ST3160815AS 160GB                 | 1         | 1      | 4.76%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB       | 1         | 1      | 4.76%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD       | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 860 EVO 1TB       | 1         | 1      | 4.76%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD | 1         | 1      | 4.76%   |
| Kingston SA400S37480G 480GB SSD           | 1         | 1      | 4.76%   |
| Intel SSDPEKKW128G7 128GB                 | 1         | 1      | 4.76%   |
| Hitachi HTS725050A7E630 500GB             | 1         | 1      | 4.76%   |
| Hitachi HTS723216L9A360 160GB             | 1         | 1      | 4.76%   |
| Hitachi HTS542512K9SA00 120GB             | 1         | 1      | 4.76%   |
| Hitachi HTC426040G8CE00 40GB              | 1         | 1      | 4.76%   |
| HGST TOURO Mobile 1TB                     | 1         | 1      | 4.76%   |
| HGST HTS 541010A9E680 1TB                 | 1         | 1      | 4.76%   |
| Crucial CT240M500SSD1 240GB               | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 20%     |
| Hitachi             | 4         | 4      | 20%     |
| WDC                 | 3         | 5      | 15%     |
| Toshiba             | 1         | 1      | 5%      |
| SanDisk             | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| LITEON              | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| HGST HTS            | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |
| Crucial             | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 4      | 28.57%  |
| Hitachi  | 4         | 4      | 28.57%  |
| WDC      | 3         | 5      | 21.43%  |
| Toshiba  | 1         | 1      | 7.14%   |
| HGST HTS | 1         | 1      | 7.14%   |
| HGST     | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 16     | 68.42%  |
| SSD  | 5         | 5      | 26.32%  |
| NVMe | 1         | 1      | 5.26%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 145       | 299    | 54.72%  |
| Works    | 101       | 196    | 38.11%  |
| Malfunc  | 19        | 22     | 7.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 172       | 52.44%  |
| Samsung Electronics           | 37        | 11.28%  |
| AMD                           | 34        | 10.37%  |
| SanDisk                       | 21        | 6.4%    |
| Silicon Motion                | 8         | 2.44%   |
| Phison Electronics            | 8         | 2.44%   |
| SK hynix                      | 7         | 2.13%   |
| Kingston Technology Company   | 6         | 1.83%   |
| ASMedia Technology            | 6         | 1.83%   |
| Toshiba America Info Systems  | 3         | 0.91%   |
| Micron Technology             | 3         | 0.91%   |
| Marvell Technology Group      | 3         | 0.91%   |
| KIOXIA                        | 3         | 0.91%   |
| ADATA Technology              | 3         | 0.91%   |
| Yangtze Memory Technologies   | 2         | 0.61%   |
| VIA Technologies              | 2         | 0.61%   |
| Nvidia                        | 2         | 0.61%   |
| Lite-On Technology            | 2         | 0.61%   |
| JMicron Technology            | 2         | 0.61%   |
| LSI Logic / Symbios Logic     | 1         | 0.3%    |
| Integrated Technology Express | 1         | 0.3%    |
| Biwin Storage Technology      | 1         | 0.3%    |
| Apple                         | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 22        | 6.13%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 21        | 5.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16        | 4.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 3.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11        | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 2.79%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10        | 2.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 9         | 2.51%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 2.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7         | 1.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7         | 1.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 1.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 1.95%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 6         | 1.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 1.67%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 6         | 1.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 6         | 1.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 1.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 1.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5         | 1.39%   |
| Intel SSD 660P Series                                                                   | 5         | 1.39%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5         | 1.39%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.39%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4         | 1.11%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.84%   |
| SanDisk Non-Volatile memory controller                                                  | 3         | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 0.84%   |
| Phison E12 NVMe Controller                                                              | 3         | 0.84%   |
| Micron Non-Volatile memory controller                                                   | 3         | 0.84%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 0.84%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 3         | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.84%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.84%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 0.84%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 0.84%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 0.84%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3         | 0.84%   |
| Yangtze Memory Non-Volatile memory controller                                           | 2         | 0.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.56%   |
| SK hynix Non-Volatile memory controller                                                 | 2         | 0.56%   |
| SK hynix Gold P31 SSD                                                                   | 2         | 0.56%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2         | 0.56%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 0.56%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 0.56%   |
| Lite-On Non-Volatile memory controller                                                  | 2         | 0.56%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 0.56%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.56%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 2         | 0.56%   |
| Intel SSD 600P Series                                                                   | 2         | 0.56%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 0.56%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 179       | 56.47%  |
| NVMe | 101       | 31.86%  |
| IDE  | 21        | 6.62%   |
| RAID | 15        | 4.73%   |
| SAS  | 1         | 0.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 194       | 79.51%  |
| AMD          | 44        | 18.03%  |
| ARM          | 5         | 2.05%   |
| GenuineTMx86 | 1         | 0.41%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 2.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.63%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 4         | 1.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.63%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 4         | 1.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.63%   |
| ARM Processor                                 | 4         | 1.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 1.63%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 3         | 1.22%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 3         | 1.22%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 3         | 1.22%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.22%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 3         | 1.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.22%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 1.22%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 3         | 1.22%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.22%   |
| Intel Xeon CPU X5675 @ 3.07GHz                | 2         | 0.82%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 0.82%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 2         | 0.82%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.82%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 0.82%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.82%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2         | 0.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.82%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.82%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.82%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 2         | 0.82%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.82%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 0.82%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 0.82%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.82%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 0.82%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 0.82%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2         | 0.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.82%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.41%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 0.41%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz           | 1         | 0.41%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz           | 1         | 0.41%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz           | 1         | 0.41%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.41%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz           | 1         | 0.41%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz           | 1         | 0.41%   |
| Intel Pentium Silver N6005 @ 2.00GHz          | 1         | 0.41%   |
| Intel Pentium M processor 1.00GHz             | 1         | 0.41%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1         | 0.41%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.41%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.41%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.41%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.41%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 53        | 21.63%  |
| Intel Core i5           | 53        | 21.63%  |
| Other                   | 23        | 9.39%   |
| Intel Core i3           | 19        | 7.76%   |
| Intel Celeron           | 16        | 6.53%   |
| AMD Ryzen 7             | 15        | 6.12%   |
| AMD Ryzen 5             | 13        | 5.31%   |
| Intel Xeon              | 10        | 4.08%   |
| AMD Ryzen 9             | 7         | 2.86%   |
| Intel Pentium           | 5         | 2.04%   |
| Intel Core m3           | 3         | 1.22%   |
| Intel Core 2 Duo        | 3         | 1.22%   |
| AMD Phenom II X4        | 3         | 1.22%   |
| Intel Pentium Gold      | 2         | 0.82%   |
| Intel Pentium Dual-Core | 2         | 0.82%   |
| Intel Pentium Dual      | 2         | 0.82%   |
| Intel Core i9           | 2         | 0.82%   |
| Intel Atom              | 2         | 0.82%   |
| Intel Pentium Silver    | 1         | 0.41%   |
| Intel Pentium M         | 1         | 0.41%   |
| Intel Core 2 Quad       | 1         | 0.41%   |
| Intel Core 2 Extreme    | 1         | 0.41%   |
| ARM BCM                 | 1         | 0.41%   |
| AMD Ryzen Threadripper  | 1         | 0.41%   |
| AMD Ryzen Embedded      | 1         | 0.41%   |
| AMD Phenom II X6        | 1         | 0.41%   |
| AMD FX                  | 1         | 0.41%   |
| AMD Athlon II X3        | 1         | 0.41%   |
| AMD Athlon 64 X2        | 1         | 0.41%   |
| AMD A10                 | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 95        | 38.78%  |
| 2      | 79        | 32.24%  |
| 8      | 27        | 11.02%  |
| 6      | 24        | 9.8%    |
| 12     | 7         | 2.86%   |
| 1      | 4         | 1.63%   |
| 14     | 3         | 1.22%   |
| 16     | 2         | 0.82%   |
| 3      | 2         | 0.82%   |
| 24     | 1         | 0.41%   |
| 10     | 1         | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 240       | 98.36%  |
| 2      | 4         | 1.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 172       | 70.2%   |
| 1      | 73        | 29.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 231       | 94.67%  |
| Unknown        | 9         | 3.69%   |
| 32-bit         | 4         | 1.64%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 20.8%   |
| 0x206a7    | 16        | 6.4%    |
| 0x306c3    | 14        | 5.6%    |
| 0x806e9    | 12        | 4.8%    |
| 0x906ea    | 9         | 3.6%    |
| 0x806c1    | 9         | 3.6%    |
| 0x306a9    | 9         | 3.6%    |
| 0x506e3    | 7         | 2.8%    |
| 0x40651    | 7         | 2.8%    |
| 0x806ea    | 6         | 2.4%    |
| 0x906ed    | 5         | 2%      |
| 0x906e9    | 5         | 2%      |
| 0x806eb    | 5         | 2%      |
| 0x506c9    | 5         | 2%      |
| 0x0a50000c | 5         | 2%      |
| 0x406e3    | 4         | 1.6%    |
| 0x20655    | 4         | 1.6%    |
| 0xa0653    | 3         | 1.2%    |
| 0xa0652    | 3         | 1.2%    |
| 0x806ec    | 3         | 1.2%    |
| 0x706e5    | 3         | 1.2%    |
| 0x20652    | 3         | 1.2%    |
| 0x1067a    | 3         | 1.2%    |
| 0x0a201009 | 3         | 1.2%    |
| 0x08701013 | 3         | 1.2%    |
| 0x08108102 | 3         | 1.2%    |
| 0x0800820d | 3         | 1.2%    |
| 0x906a3    | 2         | 0.8%    |
| 0x806d1    | 2         | 0.8%    |
| 0x706a1    | 2         | 0.8%    |
| 0x6fd      | 2         | 0.8%    |
| 0x306e4    | 2         | 0.8%    |
| 0x206c2    | 2         | 0.8%    |
| 0x106c2    | 2         | 0.8%    |
| 0x0a50000b | 2         | 0.8%    |
| 0x08701021 | 2         | 0.8%    |
| 0x08600104 | 2         | 0.8%    |
| 0x08600103 | 2         | 0.8%    |
| 0x010000db | 2         | 0.8%    |
| 0x010000c8 | 2         | 0.8%    |
| 0xa0671    | 1         | 0.4%    |
| 0xa0655    | 1         | 0.4%    |
| 0x906c0    | 1         | 0.4%    |
| 0x90672    | 1         | 0.4%    |
| 0x706a8    | 1         | 0.4%    |
| 0x6fb      | 1         | 0.4%    |
| 0x6d6      | 1         | 0.4%    |
| 0x40671    | 1         | 0.4%    |
| 0x306d4    | 1         | 0.4%    |
| 0x30678    | 1         | 0.4%    |
| 0x106e5    | 1         | 0.4%    |
| 0x10677    | 1         | 0.4%    |
| 0x0a201016 | 1         | 0.4%    |
| 0x08600106 | 1         | 0.4%    |
| 0x08108109 | 1         | 0.4%    |
| 0x0810100b | 1         | 0.4%    |
| 0x08001137 | 1         | 0.4%    |
| 0x06003106 | 1         | 0.4%    |
| 0x06000852 | 1         | 0.4%    |
| 0x010000dc | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 49        | 20%     |
| Haswell          | 25        | 10.2%   |
| SandyBridge      | 20        | 8.16%   |
| Zen 2            | 15        | 6.12%   |
| Skylake          | 15        | 6.12%   |
| IvyBridge        | 15        | 6.12%   |
| Zen 3            | 12        | 4.9%    |
| TigerLake        | 12        | 4.9%    |
| Westmere         | 10        | 4.08%   |
| CometLake        | 10        | 4.08%   |
| Unknown          | 10        | 4.08%   |
| Zen+             | 7         | 2.86%   |
| Icelake          | 7         | 2.86%   |
| Goldmont         | 6         | 2.45%   |
| Penryn           | 5         | 2.04%   |
| K10              | 5         | 2.04%   |
| Core             | 4         | 1.63%   |
| Goldmont plus    | 3         | 1.22%   |
| Broadwell        | 3         | 1.22%   |
| Zen              | 2         | 0.82%   |
| Bonnell          | 2         | 0.82%   |
| Tremont          | 1         | 0.41%   |
| Steamroller      | 1         | 0.41%   |
| Silvermont       | 1         | 0.41%   |
| Piledriver       | 1         | 0.41%   |
| P6               | 1         | 0.41%   |
| Nehalem          | 1         | 0.41%   |
| K8 Hammer        | 1         | 0.41%   |
| Alderlake Hybrid | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 150       | 51.9%   |
| Nvidia            | 91        | 31.49%  |
| AMD               | 46        | 15.92%  |
| S3 Graphics       | 1         | 0.35%   |
| ASPEED Technology | 1         | 0.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 15        | 5.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 10        | 3.41%   |
| AMD Cezanne                                                                 | 8         | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7         | 2.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 7         | 2.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 7         | 2.39%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 7         | 2.39%   |
| Intel UHD Graphics 620                                                      | 6         | 2.05%   |
| Intel HD Graphics 620                                                       | 6         | 2.05%   |
| Intel HD Graphics 500                                                       | 6         | 2.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6         | 2.05%   |
| AMD Renoir                                                                  | 6         | 2.05%   |
| Intel HD Graphics 530                                                       | 5         | 1.71%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 4         | 1.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 1.37%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 4         | 1.37%   |
| Intel HD Graphics 615                                                       | 4         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 1.37%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 1.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 1.37%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 3         | 1.02%   |
| Nvidia GP108M [GeForce MX150]                                               | 3         | 1.02%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.02%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.02%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 3         | 1.02%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3         | 1.02%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3         | 1.02%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 1.02%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 3         | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 1.02%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 3         | 1.02%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3         | 1.02%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2         | 0.68%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.68%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2         | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 2         | 0.68%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 2         | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 2         | 0.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 0.68%   |
| Intel HD Graphics 610                                                       | 2         | 0.68%   |
| Intel HD Graphics 5500                                                      | 2         | 0.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 0.68%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2         | 0.68%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                      | 2         | 0.68%   |
| AMD RS780 [Radeon HD 3200]                                                  | 2         | 0.68%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2         | 0.68%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2         | 0.68%   |
| S3 Graphics Chrome 430 ULP / 435 ULP / 440 GTX                              | 1         | 0.34%   |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 0.34%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.34%   |
| Nvidia TU117M                                                               | 1         | 0.34%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.34%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.34%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 112       | 45.71%  |
| 1 x Nvidia      | 52        | 21.22%  |
| 1 x AMD         | 31        | 12.65%  |
| Intel + Nvidia  | 29        | 11.84%  |
| AMD + Nvidia    | 9         | 3.67%   |
| Other           | 5         | 2.04%   |
| Intel + AMD     | 5         | 2.04%   |
| 1 x S3 Graphics | 1         | 0.41%   |
| 1 x ASPEED      | 1         | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 182       | 74.29%  |
| Proprietary | 48        | 19.59%  |
| Unknown     | 15        | 6.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 143       | 57.43%  |
| 1.01-2.0   | 26        | 10.44%  |
| 0.51-1.0   | 19        | 7.63%   |
| 7.01-8.0   | 16        | 6.43%   |
| 3.01-4.0   | 16        | 6.43%   |
| 0.01-0.5   | 16        | 6.43%   |
| 5.01-6.0   | 8         | 3.21%   |
| 2.01-3.0   | 2         | 0.8%    |
| 8.01-16.0  | 2         | 0.8%    |
| 16.01-24.0 | 1         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 25        | 9.69%   |
| Samsung Electronics     | 24        | 9.3%    |
| AU Optronics            | 22        | 8.53%   |
| LG Display              | 20        | 7.75%   |
| Chimei Innolux          | 17        | 6.59%   |
| Dell                    | 16        | 6.2%    |
| Goldstar                | 15        | 5.81%   |
| Philips                 | 12        | 4.65%   |
| AOC                     | 12        | 4.65%   |
| Sharp                   | 8         | 3.1%    |
| Unknown                 | 6         | 2.33%   |
| Lenovo                  | 6         | 2.33%   |
| Ancor Communications    | 6         | 2.33%   |
| AMO                     | 6         | 2.33%   |
| Acer                    | 6         | 2.33%   |
| BenQ                    | 4         | 1.55%   |
| Hewlett-Packard         | 3         | 1.16%   |
| Apple                   | 3         | 1.16%   |
| ViewSonic               | 2         | 0.78%   |
| RTK                     | 2         | 0.78%   |
| Mi                      | 2         | 0.78%   |
| LG Philips              | 2         | 0.78%   |
| CSO                     | 2         | 0.78%   |
| Chi Mei Optoelectronics | 2         | 0.78%   |
| AUS                     | 2         | 0.78%   |
| Xiaomi                  | 1         | 0.39%   |
| Xiangye                 | 1         | 0.39%   |
| Unknown (DAE)           | 1         | 0.39%   |
| Unknown (AAA)           | 1         | 0.39%   |
| Toshiba                 | 1         | 0.39%   |
| TMX                     | 1         | 0.39%   |
| TCT                     | 1         | 0.39%   |
| Sony                    | 1         | 0.39%   |
| SKY                     | 1         | 0.39%   |
| SAC                     | 1         | 0.39%   |
| PDA                     | 1         | 0.39%   |
| PANDA                   | 1         | 0.39%   |
| NOV                     | 1         | 0.39%   |
| MStar                   | 1         | 0.39%   |
| LYC                     | 1         | 0.39%   |
| LG Electronics          | 1         | 0.39%   |
| Lenovo Group Limited    | 1         | 0.39%   |
| LDR                     | 1         | 0.39%   |
| JXC                     | 1         | 0.39%   |
| ITE                     | 1         | 0.39%   |
| IPS                     | 1         | 0.39%   |
| Intehill                | 1         | 0.39%   |
| InnoLux Display         | 1         | 0.39%   |
| InfoVision              | 1         | 0.39%   |
| HPN                     | 1         | 0.39%   |
| Hitachi                 | 1         | 0.39%   |
| GET                     | 1         | 0.39%   |
| GEN                     | 1         | 0.39%   |
| FST                     | 1         | 0.39%   |
| Founder                 | 1         | 0.39%   |
| Eizo                    | 1         | 0.39%   |
| CPT                     | 1         | 0.39%   |
| ASUSTek Computer        | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AMO HS241P AMO2800 2560x1440 620x349mm 28.0-inch                      | 4         | 1.52%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 3         | 1.14%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 3         | 1.14%   |
| BOE LCD Monitor BOE06B4 1920x1080 344x194mm 15.5-inch                 | 3         | 1.14%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.14%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.76%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 2         | 0.76%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.76%   |
| LG Display LCD Monitor LGD05C4 1920x1080 344x194mm 15.5-inch          | 2         | 0.76%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch           | 2         | 0.76%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 2         | 0.76%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2         | 0.76%   |
| Dell LCD Monitor DELD08E 1920x1080 520x290mm 23.4-inch                | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 2         | 0.76%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO068B 1920x1080 309x174mm 14.0-inch        | 2         | 0.76%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 2         | 0.76%   |
| Xiaomi Mi TV XMD004A 1920x1080 1110x620mm 50.1-inch                   | 1         | 0.38%   |
| Xiangye XE2400 XYE2380 3840x2160 520x310mm 23.8-inch                  | 1         | 0.38%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch              | 1         | 0.38%   |
| ViewSonic VA1616wSERIES VSC0021 1366x768 348x197mm 15.7-inch          | 1         | 0.38%   |
| Unknown LCD Monitor ROW AAA                                           | 1         | 0.38%   |
| Unknown LCD Monitor hp f1523 1024x768                                 | 1         | 0.38%   |
| Unknown LCD Monitor FST V22T-1R LED 1920x1080                         | 1         | 0.38%   |
| Unknown (DAE) L32S6550BN DAE0010 1366x768 698x392mm 31.5-inch         | 1         | 0.38%   |
| Unknown (AAA) U270 AAA2700 3840x2160 596x335mm 26.9-inch              | 1         | 0.38%   |
| Toshiba TV TSB2634 1920x1080 697x392mm 31.5-inch                      | 1         | 0.38%   |
| TMX TL156MDMP01-1 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.38%   |
| TCT DP1080P60 TCT0270 2560x1600 520x290mm 23.4-inch                   | 1         | 0.38%   |
| Sony BW8 MS_9001 2560x1600                                            | 1         | 0.38%   |
| SKY M16U1 SKY0156 3840x2160 345x194mm 15.6-inch                       | 1         | 0.38%   |
| Sharp LQ133M1JW48 SHP14F5 1920x1080 294x165mm 13.3-inch               | 1         | 0.38%   |
| Sharp LQ133M1JW35 SHP14B0 1920x1080 294x165mm 13.3-inch               | 1         | 0.38%   |
| Sharp LQ123P1JX32 SHP148A 2400x1600 259x173mm 12.3-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP141B 1920x1080 294x165mm 13.3-inch               | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0613 1920x1080                      | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM05B0 1920x1080                      | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM01D4 1440x900 410x260mm 19.1-inch   | 1         | 0.38%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch     | 1         | 0.38%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 520x290mm 23.4-inch     | 1         | 0.38%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.38%   |
| Samsung Electronics S22C650 SAM09DB 1920x1080 477x268mm 21.5-inch     | 1         | 0.38%   |
| Samsung Electronics S22C300 SAM0A1F 1920x1080 477x268mm 21.5-inch     | 1         | 0.38%   |
| Samsung Electronics LS27R75 SAM0F98 2560x1440 598x336mm 27.0-inch     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 480x270mm 21.7-inch | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SAM03DD 1680x1050                     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor S27B550 1920x1080                     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor S24D300 3840x1080                     | 1         | 0.38%   |
| Samsung Electronics LCD Monitor S22F350 1920x1080                     | 1         | 0.38%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1         | 0.38%   |
| SAC HDMI SAC2400 2560x1440 527x296mm 23.8-inch                        | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 110       | 44.72%  |
| 1366x768 (WXGA)    | 25        | 10.16%  |
| 3840x2160 (4K)     | 24        | 9.76%   |
| 2560x1440 (QHD)    | 17        | 6.91%   |
| 1440x900 (WXGA+)   | 8         | 3.25%   |
| 1600x900 (HD+)     | 7         | 2.85%   |
| Unknown            | 6         | 2.44%   |
| 1280x800 (WXGA)    | 5         | 2.03%   |
| 3440x1440          | 4         | 1.63%   |
| 1680x1050 (WSXGA+) | 4         | 1.63%   |
| 3840x1080          | 3         | 1.22%   |
| 2880x1800          | 3         | 1.22%   |
| 2560x1600          | 3         | 1.22%   |
| 1360x768           | 3         | 1.22%   |
| 3840x2400          | 2         | 0.81%   |
| 2560x1080          | 2         | 0.81%   |
| 1920x1200 (WUXGA)  | 2         | 0.81%   |
| 1280x1024 (SXGA)   | 2         | 0.81%   |
| 1024x768 (XGA)     | 2         | 0.81%   |
| 5120x1440          | 1         | 0.41%   |
| 4480x1440          | 1         | 0.41%   |
| 3840x1600          | 1         | 0.41%   |
| 3520x1080          | 1         | 0.41%   |
| 3456x2160          | 1         | 0.41%   |
| 3200x2000          | 1         | 0.41%   |
| 3200x1800 (QHD+)   | 1         | 0.41%   |
| 2880x1920          | 1         | 0.41%   |
| 2400x1600          | 1         | 0.41%   |
| 2304x1440          | 1         | 0.41%   |
| 2256x1504          | 1         | 0.41%   |
| 2160x1440          | 1         | 0.41%   |
| 2160x1350          | 1         | 0.41%   |
| 1024x576           | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 51        | 20.08%  |
| 13      | 28        | 11.02%  |
| 14      | 20        | 7.87%   |
| Unknown | 20        | 7.87%   |
| 23      | 18        | 7.09%   |
| 21      | 18        | 7.09%   |
| 27      | 17        | 6.69%   |
| 24      | 14        | 5.51%   |
| 31      | 11        | 4.33%   |
| 12      | 9         | 3.54%   |
| 18      | 7         | 2.76%   |
| 34      | 5         | 1.97%   |
| 28      | 5         | 1.97%   |
| 19      | 5         | 1.97%   |
| 17      | 5         | 1.97%   |
| 22      | 3         | 1.18%   |
| 25      | 2         | 0.79%   |
| 16      | 2         | 0.79%   |
| 10      | 2         | 0.79%   |
| 84      | 1         | 0.39%   |
| 72      | 1         | 0.39%   |
| 65      | 1         | 0.39%   |
| 52      | 1         | 0.39%   |
| 48      | 1         | 0.39%   |
| 46      | 1         | 0.39%   |
| 40      | 1         | 0.39%   |
| 37      | 1         | 0.39%   |
| 26      | 1         | 0.39%   |
| 20      | 1         | 0.39%   |
| 11      | 1         | 0.39%   |
| 8       | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 33.6%   |
| 501-600     | 50        | 20%     |
| 401-500     | 32        | 12.8%   |
| 201-300     | 29        | 11.6%   |
| Unknown     | 20        | 8%      |
| 601-700     | 16        | 6.4%    |
| 701-800     | 5         | 2%      |
| 351-400     | 5         | 2%      |
| 1001-1500   | 4         | 1.6%    |
| 801-900     | 2         | 0.8%    |
| 1501-2000   | 2         | 0.8%    |
| 101-200     | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 171       | 72.77%  |
| 16/10   | 33        | 14.04%  |
| Unknown | 16        | 6.81%   |
| 21/9    | 6         | 2.55%   |
| 3/2     | 4         | 1.7%    |
| 6/5     | 2         | 0.85%   |
| 4/3     | 1         | 0.43%   |
| 32/9    | 1         | 0.43%   |
| 0.62    | 1         | 0.43%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 51        | 20.16%  |
| 201-250        | 45        | 17.79%  |
| 81-90          | 33        | 13.04%  |
| 301-350        | 23        | 9.09%   |
| Unknown        | 20        | 7.91%   |
| 351-500        | 17        | 6.72%   |
| 71-80          | 16        | 6.32%   |
| 151-200        | 12        | 4.74%   |
| 61-70          | 8         | 3.16%   |
| 251-300        | 5         | 1.98%   |
| 141-150        | 5         | 1.98%   |
| More than 1000 | 4         | 1.58%   |
| 121-130        | 4         | 1.58%   |
| 501-1000       | 3         | 1.19%   |
| 41-50          | 2         | 0.79%   |
| 51-60          | 1         | 0.4%    |
| 1-40           | 1         | 0.4%    |
| 131-140        | 1         | 0.4%    |
| 111-120        | 1         | 0.4%    |
| 91-100         | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 71        | 28.63%  |
| 121-160       | 61        | 24.6%   |
| 101-120       | 49        | 19.76%  |
| 161-240       | 25        | 10.08%  |
| Unknown       | 20        | 8.06%   |
| More than 240 | 16        | 6.45%   |
| 1-50          | 6         | 2.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 200       | 81.63%  |
| 2     | 33        | 13.47%  |
| 0     | 11        | 4.49%   |
| 3     | 1         | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 142       | 41.04%  |
| Realtek Semiconductor    | 119       | 34.39%  |
| Qualcomm Atheros         | 25        | 7.23%   |
| Broadcom                 | 16        | 4.62%   |
| TP-Link                  | 7         | 2.02%   |
| Ralink Technology        | 7         | 2.02%   |
| MediaTek                 | 7         | 2.02%   |
| SEGGER                   | 2         | 0.58%   |
| Qualcomm                 | 2         | 0.58%   |
| Marvell Technology Group | 2         | 0.58%   |
| Broadcom Limited         | 2         | 0.58%   |
| ASIX Electronics         | 2         | 0.58%   |
| Xiaomi                   | 1         | 0.29%   |
| Ralink                   | 1         | 0.29%   |
| PEAK-System Technik      | 1         | 0.29%   |
| OPPO Electronics         | 1         | 0.29%   |
| Nvidia                   | 1         | 0.29%   |
| National Semiconductor   | 1         | 0.29%   |
| Microsoft                | 1         | 0.29%   |
| Lenovo                   | 1         | 0.29%   |
| ICS Advent               | 1         | 0.29%   |
| Fitbit                   | 1         | 0.29%   |
| DisplayLink              | 1         | 0.29%   |
| D-Link                   | 1         | 0.29%   |
| Belkin Components        | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82        | 19.43%  |
| Intel Wi-Fi 6 AX200                                               | 21        | 4.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 2.37%   |
| Intel Wireless 8265 / 8275                                        | 10        | 2.37%   |
| Intel I211 Gigabit Network Connection                             | 10        | 2.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 2.13%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.9%    |
| Intel Wireless 7265                                               | 7         | 1.66%   |
| Intel Wireless 7260                                               | 7         | 1.66%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 1.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 1.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.42%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.42%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 1.42%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 5         | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.18%   |
| Ralink MT7601U Wireless Adapter                                   | 5         | 1.18%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.95%   |
| Intel Wireless 8260                                               | 4         | 0.95%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.71%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.71%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.71%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.71%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.47%   |
| SEGGER J-Link Pro OB                                              | 2         | 0.47%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2         | 0.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.47%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 2         | 0.47%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 2         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.47%   |
| Realtek 802.11ac NIC                                              | 2         | 0.47%   |
| Qualcomm QCA6390 Wireless Network Adapter                         | 2         | 0.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.47%   |
| Intel Wireless-AC 9260                                            | 2         | 0.47%   |
| Intel Wireless 3160                                               | 2         | 0.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.47%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.47%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.47%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 114       | 57.29%  |
| Realtek Semiconductor | 26        | 13.07%  |
| Qualcomm Atheros      | 20        | 10.05%  |
| Broadcom              | 12        | 6.03%   |
| TP-Link               | 7         | 3.52%   |
| Ralink Technology     | 7         | 3.52%   |
| MediaTek              | 7         | 3.52%   |
| Qualcomm              | 2         | 1.01%   |
| Ralink                | 1         | 0.5%    |
| Microsoft             | 1         | 0.5%    |
| Broadcom Limited      | 1         | 0.5%    |
| Belkin Components     | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 21        | 10.5%   |
| Intel Wireless 8265 / 8275                                                                    | 10        | 5%      |
| Intel Wi-Fi 6 AX201                                                                           | 8         | 4%      |
| Intel Wireless 7265                                                                           | 7         | 3.5%    |
| Intel Wireless 7260                                                                           | 7         | 3.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 7         | 3.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 6         | 3%      |
| Intel Comet Lake PCH CNVi WiFi                                                                | 6         | 3%      |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 6         | 3%      |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 5         | 2.5%    |
| Ralink MT7601U Wireless Adapter                                                               | 5         | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 5         | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 4         | 2%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 4         | 2%      |
| Intel Wireless 8260                                                                           | 4         | 2%      |
| Broadcom BCM43142 802.11b/g/n                                                                 | 4         | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 3         | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 1.5%    |
| Intel Centrino Advanced-N 6200                                                                | 3         | 1.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 2         | 1%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 2         | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1%      |
| Realtek RTL8191SEvA Wireless LAN Controller                                                   | 2         | 1%      |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)                                     | 2         | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 1%      |
| Realtek 802.11ac NIC                                                                          | 2         | 1%      |
| Qualcomm QCA6390 Wireless Network Adapter                                                     | 2         | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 2         | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 2         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 2         | 1%      |
| Intel Wireless-AC 9260                                                                        | 2         | 1%      |
| Intel Wireless 3160                                                                           | 2         | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 2         | 1%      |
| Intel Tiger Lake PCH CNVi WiFi                                                                | 2         | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 2         | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 1%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 2         | 1%      |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                                            | 2         | 1%      |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                        | 2         | 1%      |
| TP-Link RTL8812AU Archer T4U 802.11ac                                                         | 1         | 0.5%    |
| TP-Link Archer T4U ver.3                                                                      | 1         | 0.5%    |
| TP-Link 802.11n NIC                                                                           | 1         | 0.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.5%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.5%    |
| Realtek RTL8723AU 802.11n WLAN Adapter                                                        | 1         | 0.5%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 1         | 0.5%    |
| Realtek Realtek Network controller                                                            | 1         | 0.5%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.5%    |
| Ralink RT5370 Wireless Adapter                                                                | 1         | 0.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 1         | 0.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 1         | 0.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 1         | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 1         | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 1         | 0.5%    |
| Microsoft XBOX ACC                                                                            | 1         | 0.5%    |
| MediaTek WLAN controller                                                                      | 1         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 109       | 51.9%   |
| Intel                    | 75        | 35.71%  |
| Qualcomm Atheros         | 8         | 3.81%   |
| Broadcom                 | 5         | 2.38%   |
| Marvell Technology Group | 2         | 0.95%   |
| ASIX Electronics         | 2         | 0.95%   |
| Xiaomi                   | 1         | 0.48%   |
| OPPO Electronics         | 1         | 0.48%   |
| Nvidia                   | 1         | 0.48%   |
| National Semiconductor   | 1         | 0.48%   |
| Lenovo                   | 1         | 0.48%   |
| ICS Advent               | 1         | 0.48%   |
| DisplayLink              | 1         | 0.48%   |
| D-Link                   | 1         | 0.48%   |
| Broadcom Limited         | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82        | 37.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 4.59%   |
| Intel I211 Gigabit Network Connection                             | 10        | 4.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 4.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.67%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 3.21%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 2.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.29%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 2.29%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.83%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.38%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.38%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.38%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.38%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2         | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.92%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.92%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.92%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.92%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.46%   |
| Realtek USB 10/100 LAN                                            | 1         | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.46%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.46%   |
| OPPO Find X2 Lite                                                 | 1         | 0.46%   |
| Nvidia MCP65 Ethernet                                             | 1         | 0.46%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1         | 0.46%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.46%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.46%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.46%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.46%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.46%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.46%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.46%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.46%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.46%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.46%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 0.46%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 0.46%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.46%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 0.46%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.46%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.46%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.46%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.46%   |
| Intel 82551QM Ethernet Controller                                 | 1         | 0.46%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 0.46%   |
| DisplayLink USB3.0 Dual Video Dock                                | 1         | 0.46%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.B1) [ASIX AX88772]      | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 198       | 50.77%  |
| WiFi     | 188       | 48.21%  |
| Modem    | 3         | 0.77%   |
| Unknown  | 1         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 55.89%  |
| Ethernet | 116       | 44.11%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 125       | 50.61%  |
| 1     | 103       | 41.7%   |
| 0     | 12        | 4.86%   |
| 3     | 4         | 1.62%   |
| 8     | 1         | 0.4%    |
| 7     | 1         | 0.4%    |
| 4     | 1         | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 243       | 98.78%  |
| Yes  | 3         | 1.22%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 96        | 58.18%  |
| Cambridge Silicon Radio         | 15        | 9.09%   |
| Broadcom                        | 8         | 4.85%   |
| Realtek Semiconductor           | 7         | 4.24%   |
| Qualcomm Atheros Communications | 6         | 3.64%   |
| Foxconn / Hon Hai               | 6         | 3.64%   |
| Lite-On Technology              | 5         | 3.03%   |
| Apple                           | 4         | 2.42%   |
| IMC Networks                    | 3         | 1.82%   |
| Hewlett-Packard                 | 3         | 1.82%   |
| Realtek                         | 2         | 1.21%   |
| Foxconn International           | 2         | 1.21%   |
| Dell                            | 2         | 1.21%   |
| ASUSTek Computer                | 2         | 1.21%   |
| Taiyo Yuden                     | 1         | 0.61%   |
| SINO WEALTH                     | 1         | 0.61%   |
| Fujitsu                         | 1         | 0.61%   |
| Askey Computer                  | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 28        | 16.97%  |
| Intel Bluetooth Device                              | 22        | 13.33%  |
| Intel AX200 Bluetooth                               | 21        | 12.73%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 6.67%   |
| Realtek Bluetooth Radio                             | 7         | 4.24%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 4.24%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.82%   |
| IMC Networks Wireless_Device                        | 3         | 1.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.82%   |
| Realtek Bluetooth Radio                             | 2         | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.21%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 1.21%   |
| Intel AX210 Bluetooth                               | 2         | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.21%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 1.21%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.21%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.21%   |
| ASUS Bluetooth Radio                                | 2         | 1.21%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.21%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.61%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1         | 0.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.61%   |
| Lite-On Bluetooth Radio                             | 1         | 0.61%   |
| Lite-On Bluetooth Device                            | 1         | 0.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.61%   |
| Fujitsu Bluetooth Device                            | 1         | 0.61%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.61%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.61%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.61%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.61%   |
| Broadcom Bluetooth Controller                       | 1         | 0.61%   |
| Broadcom BCM2045A0                                  | 1         | 0.61%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.61%   |
| Askey Bluetooth Device                              | 1         | 0.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.61%   |
| Apple Bluetooth Host Controller                     | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 190       | 56.72%  |
| Nvidia                               | 67        | 20%     |
| AMD                                  | 51        | 15.22%  |
| C-Media Electronics                  | 8         | 2.39%   |
| Logitech                             | 3         | 0.9%    |
| Generalplus Technology               | 2         | 0.6%    |
| Focusrite-Novation                   | 2         | 0.6%    |
| Creative Labs                        | 2         | 0.6%    |
| XMOS                                 | 1         | 0.3%    |
| VIA Technologies                     | 1         | 0.3%    |
| Thesycon Systemsoftware & Consulting | 1         | 0.3%    |
| Sony                                 | 1         | 0.3%    |
| Lynx                                 | 1         | 0.3%    |
| iCreate Technologies                 | 1         | 0.3%    |
| HiFimeDIY Audio                      | 1         | 0.3%    |
| FiiO Electronics Technology          | 1         | 0.3%    |
| BY EDIFIER                           | 1         | 0.3%    |
| AudioQuest                           | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 23        | 5.93%   |
| AMD Family 17h/19h HD Audio Controller                                            | 20        | 5.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 18        | 4.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 16        | 4.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 15        | 3.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 13        | 3.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 12        | 3.09%   |
| AMD Starship/Matisse HD Audio Controller                                          | 12        | 3.09%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 12        | 3.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 11        | 2.84%   |
| Intel Cannon Lake PCH cAVS                                                        | 10        | 2.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 8         | 2.06%   |
| Intel Haswell-ULT HD Audio Controller                                             | 7         | 1.8%    |
| Intel 8 Series HD Audio Controller                                                | 7         | 1.8%    |
| Nvidia GP106 High Definition Audio Controller                                     | 6         | 1.55%   |
| Intel Comet Lake PCH cAVS                                                         | 6         | 1.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 6         | 1.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 6         | 1.55%   |
| Intel 200 Series PCH HD Audio                                                     | 6         | 1.55%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6         | 1.55%   |
| Nvidia TU106 High Definition Audio Controller                                     | 5         | 1.29%   |
| Nvidia GM206 High Definition Audio Controller                                     | 5         | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5         | 1.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5         | 1.29%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 5         | 1.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 5         | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 1.03%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4         | 1.03%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                     | 4         | 1.03%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4         | 1.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 4         | 1.03%   |
| Intel Comet Lake PCH-V cAVS                                                       | 4         | 1.03%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3         | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 0.77%   |
| Nvidia Audio device                                                               | 3         | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3         | 0.77%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 3         | 0.77%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3         | 0.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 3         | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3         | 0.77%   |
| AMD Navi 10 HDMI Audio                                                            | 3         | 0.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3         | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 0.52%   |
| Nvidia TU104 HD Audio Controller                                                  | 2         | 0.52%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.52%   |
| Nvidia GF106 High Definition Audio Controller                                     | 2         | 0.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 2         | 0.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2         | 0.52%   |
| Intel CM238 HD Audio Controller                                                   | 2         | 0.52%   |
| Intel Broadwell-U Audio Controller                                                | 2         | 0.52%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2         | 0.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 0.52%   |
| Generalplus Technology IMYB 7.1 Channel                                           | 2         | 0.52%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2         | 0.52%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 0.52%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2         | 0.52%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2         | 0.52%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.52%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 2         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 32        | 21.05%  |
| Samsung Electronics | 28        | 18.42%  |
| Kingston            | 26        | 17.11%  |
| Micron Technology   | 14        | 9.21%   |
| Unknown             | 11        | 7.24%   |
| Corsair             | 9         | 5.92%   |
| A-DATA Technology   | 8         | 5.26%   |
| Crucial             | 6         | 3.95%   |
| Unknown             | 3         | 1.97%   |
| Unknown (ABCD)      | 2         | 1.32%   |
| Team                | 2         | 1.32%   |
| Ramaxel Technology  | 2         | 1.32%   |
| Kingmax             | 2         | 1.32%   |
| Transcend           | 1         | 0.66%   |
| Lenovo              | 1         | 0.66%   |
| Juhor               | 1         | 0.66%   |
| GLOWAY              | 1         | 0.66%   |
| G.Skill             | 1         | 0.66%   |
| Elpida              | 1         | 0.66%   |
| Apacer              | 1         | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 2.47%   |
| Unknown                                                          | 3         | 1.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 1.23%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                     | 2         | 1.23%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.23%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.23%   |
| Samsung RAM M471B1G73BH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.23%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.23%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 1.23%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.23%   |
| Kingston RAM KY7N41-MIE 8192MB DIMM DDR4 2666MT/s                | 2         | 1.23%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 1.23%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 2         | 1.23%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s         | 2         | 1.23%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1         | 0.62%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.62%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.62%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.62%   |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s                      | 1         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 0.62%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.62%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.62%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.62%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 1         | 0.62%   |
| Transcend RAM TS256MLQ72V6U 2048MB DIMM DDR2 667MT/s             | 1         | 0.62%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s               | 1         | 0.62%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s            | 1         | 0.62%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.62%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                       | 1         | 0.62%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.62%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.62%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.62%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.62%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.62%   |
| SK hynix RAM HMAA4GS7AJR8N-WM 32GB SODIMM DDR4 2933MT/s          | 1         | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.62%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.62%   |
| SK hynix RAM HMA82GS7AFR8N-UH 16384MB SODIMM DDR4 2400MT/s       | 1         | 0.62%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.62%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.62%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.62%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.62%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.62%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 1         | 0.62%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.62%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.62%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.62%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.62%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4096MB 1867MT/s                  | 1         | 0.62%   |
| SK hynix RAM D471A1K43CB1-CTD 8GB SODIMM DDR4 2400MT/s           | 1         | 0.62%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR4 3733MT/s           | 1         | 0.62%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 1600MT/s           | 1         | 0.62%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.62%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR3 1867MT/s              | 1         | 0.62%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.62%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.62%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 0.62%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 71        | 54.2%   |
| DDR3    | 30        | 22.9%   |
| LPDDR3  | 8         | 6.11%   |
| LPDDR4  | 6         | 4.58%   |
| DDR2    | 5         | 3.82%   |
| Unknown | 5         | 3.82%   |
| SDRAM   | 4         | 3.05%   |
| DRAM    | 1         | 0.76%   |
| DDR     | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 61        | 46.92%  |
| DIMM         | 51        | 39.23%  |
| Row Of Chips | 17        | 13.08%  |
| Unknown      | 1         | 0.77%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 50        | 35.21%  |
| 4096  | 35        | 24.65%  |
| 16384 | 25        | 17.61%  |
| 2048  | 16        | 11.27%  |
| 32768 | 11        | 7.75%   |
| 1024  | 3         | 2.11%   |
| 512   | 1         | 0.7%    |
| 232   | 1         | 0.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 26        | 18.57%  |
| 1600    | 25        | 17.86%  |
| 3200    | 24        | 17.14%  |
| 2400    | 12        | 8.57%   |
| 2133    | 8         | 5.71%   |
| 1333    | 6         | 4.29%   |
| 1867    | 5         | 3.57%   |
| 4267    | 3         | 2.14%   |
| 3466    | 3         | 2.14%   |
| 2666    | 3         | 2.14%   |
| 667     | 3         | 2.14%   |
| Unknown | 3         | 2.14%   |
| 3600    | 2         | 1.43%   |
| 3000    | 2         | 1.43%   |
| 800     | 2         | 1.43%   |
| 6400    | 1         | 0.71%   |
| 4800    | 1         | 0.71%   |
| 4199    | 1         | 0.71%   |
| 3800    | 1         | 0.71%   |
| 3733    | 1         | 0.71%   |
| 3400    | 1         | 0.71%   |
| 3266    | 1         | 0.71%   |
| 3007    | 1         | 0.71%   |
| 2933    | 1         | 0.71%   |
| 1866    | 1         | 0.71%   |
| 1334    | 1         | 0.71%   |
| 975     | 1         | 0.71%   |
| 533     | 1         | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Xiaomi             | 1         | 20%     |
| Hewlett-Packard    | 1         | 20%     |
| Fuji Xerox         | 1         | 20%     |
| Canon              | 1         | 20%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| Xiaomi MiMouse 2            | 1         | 20%     |
| HP LaserJet P2035           | 1         | 20%     |
| Fuji Xerox DocuPrint P158 b | 1         | 20%     |
| Canon MP160                 | 1         | 20%     |
| Brother HL-L2320D series    | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 26        | 21.14%  |
| Microdia                               | 11        | 8.94%   |
| IMC Networks                           | 11        | 8.94%   |
| Acer                                   | 11        | 8.94%   |
| Logitech                               | 7         | 5.69%   |
| Realtek Semiconductor                  | 6         | 4.88%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.88%   |
| Luxvisions Innotech Limited            | 5         | 4.07%   |
| Syntek                                 | 4         | 3.25%   |
| Sunplus Innovation Technology          | 4         | 3.25%   |
| Apple                                  | 4         | 3.25%   |
| Alcor Micro                            | 3         | 2.44%   |
| Suyin                                  | 2         | 1.63%   |
| Silicon Motion                         | 2         | 1.63%   |
| Quanta                                 | 2         | 1.63%   |
| Lite-On Technology                     | 2         | 1.63%   |
| Importek                               | 2         | 1.63%   |
| Cubeternet                             | 2         | 1.63%   |
| WaveRider Communications               | 1         | 0.81%   |
| Sonix Technology                       | 1         | 0.81%   |
| SN0002                                 | 1         | 0.81%   |
| Ricoh                                  | 1         | 0.81%   |
| Primax Electronics                     | 1         | 0.81%   |
| Nokia Mobile Phones                    | 1         | 0.81%   |
| Nebraska Furniture Mart                | 1         | 0.81%   |
| Microsoft                              | 1         | 0.81%   |
| lihappe8                               | 1         | 0.81%   |
| Google                                 | 1         | 0.81%   |
| Genesys Logic                          | 1         | 0.81%   |
| Essential Products                     | 1         | 0.81%   |
| eMPIA Technology                       | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                       | 7         | 5.6%    |
| Chicony Integrated Camera                                           | 7         | 5.6%    |
| IMC Networks USB2.0 HD UVC WebCam                                   | 5         | 4%      |
| Chicony FJ Camera                                                   | 5         | 4%      |
| Syntek Integrated Camera                                            | 4         | 3.2%    |
| IMC Networks Integrated Camera                                      | 4         | 3.2%    |
| Chicony HD Webcam                                                   | 4         | 3.2%    |
| Alcor Micro USB 2.0 Camera                                          | 3         | 2.4%    |
| Acer Integrated Camera                                              | 3         | 2.4%    |
| Realtek Integrated_Webcam_HD                                        | 2         | 1.6%    |
| Luxvisions Innotech Limited HP HD Camera                            | 2         | 1.6%    |
| Logitech Webcam C270                                                | 2         | 1.6%    |
| Logitech B525 HD Webcam                                             | 2         | 1.6%    |
| Lite-On Integrated Camera                                           | 2         | 1.6%    |
| Importek FJ Camera                                                  | 2         | 1.6%    |
| Apple FaceTime HD Camera (Built-in)                                 | 2         | 1.6%    |
| Acer SunplusIT Integrated Camera                                    | 2         | 1.6%    |
| Acer Lenovo EasyCamera                                              | 2         | 1.6%    |
| WaveRider USB 2.0 Camera                                            | 1         | 0.8%    |
| Suyin HP TrueVision HD Integrated Webcam                            | 1         | 0.8%    |
| Suyin HP Truevision HD                                              | 1         | 0.8%    |
| Sunplus MTD Camera                                                  | 1         | 0.8%    |
| Sunplus Integrated_Webcam_HD                                        | 1         | 0.8%    |
| Sunplus HP Universal Camera                                         | 1         | 0.8%    |
| Sunplus HD WebCam                                                   | 1         | 0.8%    |
| Sonix USB2.0 HD UVC WebCam                                          | 1         | 0.8%    |
| SN0002 HIK 2K Camera                                                | 1         | 0.8%    |
| Silicon Motion 720p HD Camera                                       | 1         | 0.8%    |
| Silicon Motion 300k Pixel Camera                                    | 1         | 0.8%    |
| Ricoh USB2.0 Camera                                                 | 1         | 0.8%    |
| Realtek WebCamera                                                   | 1         | 0.8%    |
| Realtek USB2.0 HD UVC WebCam                                        | 1         | 0.8%    |
| Realtek Lenovo easy camera                                          | 1         | 0.8%    |
| Realtek Integrated Webcam_HD                                        | 1         | 0.8%    |
| Quanta USB Webcam                                                   | 1         | 0.8%    |
| Quanta hm1091_techfront                                             | 1         | 0.8%    |
| Primax Dell Laptop Integrated Webcam 2Mpix                          | 1         | 0.8%    |
| Nokia Mobile Phones Lumia 640 Phone                                 | 1         | 0.8%    |
| Nebraska Furniture Mart USB 2.0 PC cam                              | 1         | 0.8%    |
| Microsoft LifeCam Cinema                                            | 1         | 0.8%    |
| Microdia Rapoo camera                                               | 1         | 0.8%    |
| Microdia Laptop_Integrated_Webcam_0.3M                              | 1         | 0.8%    |
| Microdia HP Webcam-101                                              | 1         | 0.8%    |
| Microdia Dell Integrated HD Webcam                                  | 1         | 0.8%    |
| Luxvisions Innotech Limited Integrated RGB Camera                   | 1         | 0.8%    |
| Luxvisions Innotech Limited Integrated Camera                       | 1         | 0.8%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera                 | 1         | 0.8%    |
| Logitech HD Pro Webcam C920                                         | 1         | 0.8%    |
| Logitech Fujitsu Webcam                                             | 1         | 0.8%    |
| Logitech BRIO Ultra HD Webcam                                       | 1         | 0.8%    |
| lihappe8 USB 2.0 Camera                                             | 1         | 0.8%    |
| IMC Networks USB2.0 VGA UVC WebCam                                  | 1         | 0.8%    |
| IMC Networks Lenovo EasyCamera                                      | 1         | 0.8%    |
| Google Nexus/Pixel Device (MTP + debug)                             | 1         | 0.8%    |
| Google Nexus 4/5 (PTP + debug)                                      | 1         | 0.8%    |
| Genesys Logic Camera                                                | 1         | 0.8%    |
| Essential Products PH-1                                             | 1         | 0.8%    |
| eMPIA M035 Compact Web Cam                                          | 1         | 0.8%    |
| Cubeternet GL-UPC822 UVC WebCam                                     | 1         | 0.8%    |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 37.04%  |
| Validity Sensors           | 6         | 22.22%  |
| Shenzhen Goodix Technology | 5         | 18.52%  |
| Upek                       | 2         | 7.41%   |
| AuthenTec                  | 2         | 7.41%   |
| Samsung Electronics        | 1         | 3.7%    |
| LighTuning Technology      | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 3         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 3         | 11.11%  |
| Validity Sensors Synaptics WBDI                        | 2         | 7.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 7.41%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 7.41%   |
| Shenzhen Goodix FingerPrint                            | 2         | 7.41%   |
| AuthenTec Fingerprint Sensor                           | 2         | 7.41%   |
| Unknown                                                | 2         | 7.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 3.7%    |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 3.7%    |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.7%    |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 3.7%    |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1         | 3.7%    |
| Synaptics  WBDI                                        | 1         | 3.7%    |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 3.7%    |
| Samsung Fingerprint Device                             | 1         | 3.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 33.33%  |
| Upek                  | 2         | 16.67%  |
| Lenovo                | 2         | 16.67%  |
| Yubico.com            | 1         | 8.33%   |
| O2 Micro              | 1         | 8.33%   |
| Alcor Micro           | 1         | 8.33%   |
| Advanced Card Systems | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 16.67%  |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 8.33%   |
| Broadcom 5880                                                                | 1         | 8.33%   |
| Broadcom 58200                                                               | 1         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 8.33%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 167       | 66.53%  |
| 1     | 66        | 26.29%  |
| 2     | 12        | 4.78%   |
| 4     | 3         | 1.2%    |
| 3     | 2         | 0.8%    |
| 5     | 1         | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 26        | 23.42%  |
| Graphics card            | 25        | 22.52%  |
| Net/wireless             | 17        | 15.32%  |
| Chipcard                 | 11        | 9.91%   |
| Communication controller | 9         | 8.11%   |
| Multimedia controller    | 8         | 7.21%   |
| Bluetooth                | 3         | 2.7%    |
| Unassigned class         | 2         | 1.8%    |
| Storage                  | 2         | 1.8%    |
| Sound                    | 2         | 1.8%    |
| Net/ethernet             | 2         | 1.8%    |
| Camera                   | 2         | 1.8%    |
| Storage/ata              | 1         | 0.9%    |
| Card reader              | 1         | 0.9%    |

