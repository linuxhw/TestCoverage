Linux in Hong Kong - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hong Kong.

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

Total: 166

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte   | X570 AORUS PRO WIFI         | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| Huanan     | X99-TF                      | [04dc5246af](https://linux-hardware.org/?probe=04dc5246af) | Jun 18, 2022 |
| Lenovo     | 3715 SDK0L77769 WIN 3423... | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Huanan     | X99-TF                      | [4e5364e832](https://linux-hardware.org/?probe=4e5364e832) | Jun 08, 2022 |
| Gigabyte   | HA65M-UD3H-B3               | [d368918a0b](https://linux-hardware.org/?probe=d368918a0b) | May 13, 2022 |
| Gigabyte   | X570 AORUS PRO WIFI         | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| Gigabyte   | GA-880GMA-UD2H              | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| MSI        | H87I                        | [af4a26a5ea](https://linux-hardware.org/?probe=af4a26a5ea) | Apr 30, 2022 |
| Gigabyte   | B660M DS3H AX DDR4          | [0633ac7757](https://linux-hardware.org/?probe=0633ac7757) | Apr 26, 2022 |
| Gigabyte   | B660M DS3H AX DDR4          | [56902c7998](https://linux-hardware.org/?probe=56902c7998) | Apr 26, 2022 |
| Gigabyte   | B660M DS3H AX DDR4          | [abed3ae34d](https://linux-hardware.org/?probe=abed3ae34d) | Apr 12, 2022 |
| ASUSTek    | VM62                        | [ae684cdf71](https://linux-hardware.org/?probe=ae684cdf71) | Apr 05, 2022 |
| ASRock     | H410M-ITX/ac                | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| MSI        | MAG B550M MORTAR            | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Dell       | 0Y3R3K A03                  | [b772cf9d86](https://linux-hardware.org/?probe=b772cf9d86) | Mar 26, 2022 |
| ASUSTek    | PRIME Z590-A                | [7320ed668a](https://linux-hardware.org/?probe=7320ed668a) | Mar 12, 2022 |
| Gigabyte   | X570 AORUS ELITE            | [99d3e16ede](https://linux-hardware.org/?probe=99d3e16ede) | Mar 12, 2022 |
| Unknown    | Intel X79                   | [e947d6af7f](https://linux-hardware.org/?probe=e947d6af7f) | Mar 11, 2022 |
| MSI        | MPG X570 GAMING PRO CARB... | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| MSI        | B450M PRO-VDH PLUS          | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte   | X570 AORUS ELITE            | [0b9a7acb84](https://linux-hardware.org/?probe=0b9a7acb84) | Feb 27, 2022 |
| MSI        | B75MA-P45                   | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell       | 0Y5DDC A00                  | [3c7daed552](https://linux-hardware.org/?probe=3c7daed552) | Feb 22, 2022 |
| ASUSTek    | TUF Gaming B550M-PLUS       | [6e5689a733](https://linux-hardware.org/?probe=6e5689a733) | Jan 28, 2022 |
| ASRock     | Z270M-ITX/ac                | [4c32bf6d7b](https://linux-hardware.org/?probe=4c32bf6d7b) | Jan 18, 2022 |
| HP         | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte   | B450 AORUS PRO WIFI-CF      | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| ASUSTek    | Z170 PRO GAMING             | [c5fa4a0cec](https://linux-hardware.org/?probe=c5fa4a0cec) | Dec 24, 2021 |
| ASRock     | H410M-ITX/ac                | [99c341562a](https://linux-hardware.org/?probe=99c341562a) | Dec 21, 2021 |
| Gigabyte   | B450 AORUS PRO WIFI-CF      | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| MSI        | 870-G45                     | [e6317a2b91](https://linux-hardware.org/?probe=e6317a2b91) | Dec 19, 2021 |
| Unknown    | Intel X79                   | [985655e4b3](https://linux-hardware.org/?probe=985655e4b3) | Dec 11, 2021 |
| Unknown    | Intel X79                   | [6f32192557](https://linux-hardware.org/?probe=6f32192557) | Dec 08, 2021 |
| Supermicro | X9DRi-LN4+/X9DR3-LN4+       | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| MSI        | Boston                      | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| Supermicro | C2SBC-Q                     | [1099e48366](https://linux-hardware.org/?probe=1099e48366) | Nov 28, 2021 |
| MSI        | MAG B550M MORTAR WIFI       | [58d43162d2](https://linux-hardware.org/?probe=58d43162d2) | Nov 28, 2021 |
| Gigabyte   | H310M S2H x.x               | [fc59694424](https://linux-hardware.org/?probe=fc59694424) | Nov 17, 2021 |
| MSI        | B450 TOMAHAWK MAX II        | [35b58ec233](https://linux-hardware.org/?probe=35b58ec233) | Nov 16, 2021 |
| Seco       | C40 C                       | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| MSI        | B450 TOMAHAWK MAX II        | [9bcd3d5479](https://linux-hardware.org/?probe=9bcd3d5479) | Oct 29, 2021 |
| Gigabyte   | X570 AORUS PRO WIFI         | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| MSI        | B450 TOMAHAWK MAX II        | [aedfc53de6](https://linux-hardware.org/?probe=aedfc53de6) | Oct 20, 2021 |
| MSI        | H61M-P23                    | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| MSI        | MEG X570 GODLIKE            | [1440e244f6](https://linux-hardware.org/?probe=1440e244f6) | Aug 26, 2021 |
| Gigabyte   | B365M GAMING HD             | [d920558127](https://linux-hardware.org/?probe=d920558127) | Aug 14, 2021 |
| Gigabyte   | X570 AORUS ELITE            | [5cd377c0e0](https://linux-hardware.org/?probe=5cd377c0e0) | Aug 13, 2021 |
| Gigabyte   | B75M-D2P                    | [5e54c2a102](https://linux-hardware.org/?probe=5e54c2a102) | Aug 12, 2021 |
| HP         | 2B38                        | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP         | 2B38                        | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock     | H410M-HDV                   | [58b70e282d](https://linux-hardware.org/?probe=58b70e282d) | Jul 14, 2021 |
| Gigabyte   | B365M GAMING HD             | [66cf378cf1](https://linux-hardware.org/?probe=66cf378cf1) | Jul 10, 2021 |
| Gigabyte   | B85M-DS3H-A                 | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Gigabyte   | B85M-DS3H-A                 | [71da4978c9](https://linux-hardware.org/?probe=71da4978c9) | Jun 29, 2021 |
| Gigabyte   | B365M GAMING HD             | [ed911e7e8c](https://linux-hardware.org/?probe=ed911e7e8c) | Jun 26, 2021 |
| Gigabyte   | B365M GAMING HD             | [8785d98b0b](https://linux-hardware.org/?probe=8785d98b0b) | Jun 19, 2021 |
| ASUSTek    | PRIME Z390-P                | [54e520ac17](https://linux-hardware.org/?probe=54e520ac17) | Jun 17, 2021 |
| ASUSTek    | TUF Gaming Z490-PLUS        | [76219e9cca](https://linux-hardware.org/?probe=76219e9cca) | Jun 09, 2021 |
| ASRock     | H410M-HDV                   | [bcb80080a5](https://linux-hardware.org/?probe=bcb80080a5) | Jun 06, 2021 |
| HP         | 18E7                        | [9844f6635c](https://linux-hardware.org/?probe=9844f6635c) | May 30, 2021 |
| ASUSTek    | VM62                        | [486aeb5b89](https://linux-hardware.org/?probe=486aeb5b89) | May 25, 2021 |
| Gigabyte   | F2A88XN-WIFI                | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| Dell       | 0D02VH A01                  | [e19475cd4c](https://linux-hardware.org/?probe=e19475cd4c) | May 22, 2021 |
| ASUSTek    | PRIME X399-A                | [a201bdfc36](https://linux-hardware.org/?probe=a201bdfc36) | May 19, 2021 |
| ASUSTek    | M4A78-VM                    | [3313d34c41](https://linux-hardware.org/?probe=3313d34c41) | May 15, 2021 |
| ASUSTek    | Z8NA-D6                     | [1b777c6f08](https://linux-hardware.org/?probe=1b777c6f08) | May 02, 2021 |
| ASUSTek    | Z8NA-D6                     | [4c7956a34c](https://linux-hardware.org/?probe=4c7956a34c) | May 02, 2021 |
| MSI        | Boston                      | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| HP         | 1632                        | [adf9ebb679](https://linux-hardware.org/?probe=adf9ebb679) | Mar 25, 2021 |
| MSI        | B450I GAMING PLUS AC        | [6a4196e0aa](https://linux-hardware.org/?probe=6a4196e0aa) | Mar 23, 2021 |
| MSI        | B450M-A PRO MAX             | [dc64c81c35](https://linux-hardware.org/?probe=dc64c81c35) | Mar 23, 2021 |
| ASUSTek    | B85M-G R2.0                 | [71ef988016](https://linux-hardware.org/?probe=71ef988016) | Mar 21, 2021 |
| ASRock     | H410M-HDV                   | [e44a5ce779](https://linux-hardware.org/?probe=e44a5ce779) | Mar 14, 2021 |
| MSI        | Boston                      | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| ASUSTek    | P8H61-M LX PLUS             | [b94539c6dc](https://linux-hardware.org/?probe=b94539c6dc) | Mar 01, 2021 |
| ASUSTek    | B85M-G R2.0                 | [b2cb174b9a](https://linux-hardware.org/?probe=b2cb174b9a) | Mar 01, 2021 |
| Lenovo     | MAHOBAY NOK                 | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| Dell       | 0D02VH A01                  | [87c36a9322](https://linux-hardware.org/?probe=87c36a9322) | Feb 23, 2021 |
| ASUSTek    | VM45                        | [03eeb85521](https://linux-hardware.org/?probe=03eeb85521) | Feb 21, 2021 |
| ASUSTek    | VM65-K                      | [6b97cf71eb](https://linux-hardware.org/?probe=6b97cf71eb) | Feb 18, 2021 |
| ASUSTek    | VM65-K                      | [4f0bcd1276](https://linux-hardware.org/?probe=4f0bcd1276) | Feb 17, 2021 |
| ASUSTek    | VM40B                       | [6c0bf22f39](https://linux-hardware.org/?probe=6c0bf22f39) | Feb 17, 2021 |
| Dell       | 0D02VH A01                  | [ebc5645105](https://linux-hardware.org/?probe=ebc5645105) | Feb 11, 2021 |
| Lenovo     | IdeaCentre K330             | [78ce34058b](https://linux-hardware.org/?probe=78ce34058b) | Feb 11, 2021 |
| ASUSTek    | ROG STRIX B450-I GAMING     | [39bc70ca5d](https://linux-hardware.org/?probe=39bc70ca5d) | Jan 13, 2021 |
| ASRock     | H410M-HDV                   | [d2420f233b](https://linux-hardware.org/?probe=d2420f233b) | Jan 10, 2021 |
| MSI        | H97 GAMING 3                | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| Dell       | 0TP412                      | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| ASRock     | Z390 Phantom Gaming-ITX/... | [cf7386e848](https://linux-hardware.org/?probe=cf7386e848) | Dec 18, 2020 |
| ASUSTek    | H97M-PLUS                   | [1d6b7df7b4](https://linux-hardware.org/?probe=1d6b7df7b4) | Dec 08, 2020 |
| Gigabyte   | X570 AORUS ELITE            | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| Dell       | 0D02VH A01                  | [8309aa39cf](https://linux-hardware.org/?probe=8309aa39cf) | Nov 30, 2020 |
| Gigabyte   | B450M DS3H-CF               | [37d5acae7d](https://linux-hardware.org/?probe=37d5acae7d) | Nov 27, 2020 |
| ASUSTek    | 970 PRO GAMING/AURA         | [97c485886b](https://linux-hardware.org/?probe=97c485886b) | Nov 25, 2020 |
| Dell       | 0D02VH A01                  | [8f55b945a1](https://linux-hardware.org/?probe=8f55b945a1) | Nov 20, 2020 |
| ASUSTek    | 970 PRO GAMING/AURA         | [de597aa847](https://linux-hardware.org/?probe=de597aa847) | Nov 20, 2020 |
| ASUSTek    | 970 PRO GAMING/AURA         | [f5aa8c9150](https://linux-hardware.org/?probe=f5aa8c9150) | Nov 20, 2020 |
| ASUSTek    | H110I-PLUS                  | [a3c484b8ee](https://linux-hardware.org/?probe=a3c484b8ee) | Nov 16, 2020 |
| ASUSTek    | H97M-PLUS                   | [f90977870e](https://linux-hardware.org/?probe=f90977870e) | Nov 04, 2020 |
| Gigabyte   | Z370 HD3P-CF                | [1af7b2b551](https://linux-hardware.org/?probe=1af7b2b551) | Oct 13, 2020 |
| ASUSTek    | H110I-PLUS                  | [e292456297](https://linux-hardware.org/?probe=e292456297) | Sep 17, 2020 |
| Lenovo     | SHARKBAY SDK0E50510 WIN     | [e7b41f62a4](https://linux-hardware.org/?probe=e7b41f62a4) | Sep 14, 2020 |
| ASUSTek    | H110I-PLUS                  | [20bdbc68b7](https://linux-hardware.org/?probe=20bdbc68b7) | Sep 12, 2020 |
| ASUSTek    | H81M-E                      | [43b8c677bc](https://linux-hardware.org/?probe=43b8c677bc) | Sep 10, 2020 |
| Lenovo     | MAHOBAY NOK                 | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| Foxconn    | 2ADA                        | [24cad8bed5](https://linux-hardware.org/?probe=24cad8bed5) | Aug 28, 2020 |
| Foxconn    | 2ADA                        | [3d4c2a283d](https://linux-hardware.org/?probe=3d4c2a283d) | Aug 28, 2020 |
| ASRock     | B450 Gaming-ITX/ac          | [e27db6fb31](https://linux-hardware.org/?probe=e27db6fb31) | Aug 24, 2020 |
| HP         | 802E                        | [653b11eec3](https://linux-hardware.org/?probe=653b11eec3) | Aug 11, 2020 |
| HP         | 802E                        | [6f32afeb2b](https://linux-hardware.org/?probe=6f32afeb2b) | Aug 10, 2020 |
| HP         | 802E                        | [25d8ddc0bb](https://linux-hardware.org/?probe=25d8ddc0bb) | Aug 10, 2020 |
| Gigabyte   | B150M-D3H-CF                | [50dc692a9e](https://linux-hardware.org/?probe=50dc692a9e) | Jul 23, 2020 |
| Gigabyte   | Z170X-Gaming 5 Modified ... | [a62f520dc3](https://linux-hardware.org/?probe=a62f520dc3) | Jul 18, 2020 |
| MSI        | B450M MORTAR MAX            | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| HP         | 1998                        | [255863fefb](https://linux-hardware.org/?probe=255863fefb) | Jun 01, 2020 |
| Lenovo     | ThinkCentre M90p 3269A12    | [b159b440f2](https://linux-hardware.org/?probe=b159b440f2) | Jun 01, 2020 |
| Lenovo     | ThinkCentre M90p 3269A12    | [4181637bf3](https://linux-hardware.org/?probe=4181637bf3) | Jun 01, 2020 |
| Biostar    | H110MHC                     | [98d1029698](https://linux-hardware.org/?probe=98d1029698) | May 26, 2020 |
| ASUSTek    | B150M-C                     | [2229b866b3](https://linux-hardware.org/?probe=2229b866b3) | May 26, 2020 |
| ASUSTek    | H110I-PLUS                  | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| ASUSTek    | H110I-PLUS                  | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| ASUSTek    | STRIX H270F GAMING          | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| Dell       | 0C2KJT A00                  | [179a82277c](https://linux-hardware.org/?probe=179a82277c) | May 01, 2020 |
| MSI        | 2A9C                        | [23df26e5de](https://linux-hardware.org/?probe=23df26e5de) | Apr 25, 2020 |
| Acer       | Aspire XC-710 V:1.1         | [664ac5b85b](https://linux-hardware.org/?probe=664ac5b85b) | Apr 24, 2020 |
| MSI        | Boston                      | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| ASUSTek    | H110I-PLUS                  | [f504649d96](https://linux-hardware.org/?probe=f504649d96) | Apr 11, 2020 |
| ASUSTek    | H110I-PLUS                  | [3916938374](https://linux-hardware.org/?probe=3916938374) | Apr 11, 2020 |
| Gigabyte   | Z87-HD3                     | [52a7dab5ac](https://linux-hardware.org/?probe=52a7dab5ac) | Apr 09, 2020 |
| ASUSTek    | H110I-PLUS                  | [9c72670aa1](https://linux-hardware.org/?probe=9c72670aa1) | Apr 05, 2020 |
| ASUSTek    | H110I-PLUS                  | [37fb7cae94](https://linux-hardware.org/?probe=37fb7cae94) | Mar 30, 2020 |
| MSI        | B360M FIRE                  | [8bb021d2a6](https://linux-hardware.org/?probe=8bb021d2a6) | Mar 27, 2020 |
| ASUSTek    | H110I-PLUS                  | [18b565a861](https://linux-hardware.org/?probe=18b565a861) | Mar 26, 2020 |
| ASUSTek    | H110I-PLUS                  | [abce376627](https://linux-hardware.org/?probe=abce376627) | Mar 24, 2020 |
| ASUSTek    | H110I-PLUS                  | [e6860a26ae](https://linux-hardware.org/?probe=e6860a26ae) | Mar 24, 2020 |
| ASUSTek    | H110I-PLUS                  | [5f2e14b65b](https://linux-hardware.org/?probe=5f2e14b65b) | Mar 16, 2020 |
| ASUSTek    | H110I-PLUS                  | [1bcf8a4701](https://linux-hardware.org/?probe=1bcf8a4701) | Mar 14, 2020 |
| ASUSTek    | H110I-PLUS                  | [bd55777a4f](https://linux-hardware.org/?probe=bd55777a4f) | Mar 14, 2020 |
| ASUSTek    | H110I-PLUS                  | [137262daa3](https://linux-hardware.org/?probe=137262daa3) | Mar 05, 2020 |
| ASUSTek    | H110I-PLUS                  | [047acafb1a](https://linux-hardware.org/?probe=047acafb1a) | Feb 28, 2020 |
| ASUSTek    | H110I-PLUS                  | [e8315b1469](https://linux-hardware.org/?probe=e8315b1469) | Feb 28, 2020 |
| ASUSTek    | H110I-PLUS                  | [04e5b85d84](https://linux-hardware.org/?probe=04e5b85d84) | Feb 28, 2020 |
| Gigabyte   | Z390 GAMING X-CF            | [310ae04477](https://linux-hardware.org/?probe=310ae04477) | Feb 27, 2020 |
| ASUSTek    | H110I-PLUS                  | [046814376c](https://linux-hardware.org/?probe=046814376c) | Feb 20, 2020 |
| ASUSTek    | H110I-PLUS                  | [a417965167](https://linux-hardware.org/?probe=a417965167) | Feb 19, 2020 |
| Intel      | DH77DF AAG40293-301         | [ac00169b1c](https://linux-hardware.org/?probe=ac00169b1c) | Feb 14, 2020 |
| ASUSTek    | H110I-PLUS                  | [cef9a00862](https://linux-hardware.org/?probe=cef9a00862) | Feb 12, 2020 |
| ASUSTek    | H110I-PLUS                  | [dcc65f9ee3](https://linux-hardware.org/?probe=dcc65f9ee3) | Feb 11, 2020 |
| ASUSTek    | H110I-PLUS                  | [900a11f8b3](https://linux-hardware.org/?probe=900a11f8b3) | Feb 10, 2020 |
| Gigabyte   | GA-MA78GM-S2HP              | [20d5a3bd6a](https://linux-hardware.org/?probe=20d5a3bd6a) | Feb 01, 2020 |
| Gigabyte   | Z77N-WIFI                   | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Gigabyte   | P55A-UD3                    | [7168fd0137](https://linux-hardware.org/?probe=7168fd0137) | Jan 11, 2020 |
| ASUSTek    | Z8NA-D6                     | [b2d6dabaa7](https://linux-hardware.org/?probe=b2d6dabaa7) | Dec 23, 2019 |
| MSI        | X470 GAMING PRO CARBON      | [e3b6ce369a](https://linux-hardware.org/?probe=e3b6ce369a) | Dec 23, 2019 |
| Intel      | DZ68DB AAG27985-101         | [15f84fa3f2](https://linux-hardware.org/?probe=15f84fa3f2) | Oct 26, 2019 |
| Gigabyte   | GA-MA78GM-S2HP              | [3392a03f3c](https://linux-hardware.org/?probe=3392a03f3c) | Oct 03, 2019 |
| Gigabyte   | B150M-D3H-CF                | [4302e84025](https://linux-hardware.org/?probe=4302e84025) | Sep 24, 2019 |
| ASUSTek    | B150M-A                     | [e8ccb234ed](https://linux-hardware.org/?probe=e8ccb234ed) | Aug 30, 2019 |
| ASRock     | B75M R2.0                   | [1479826c17](https://linux-hardware.org/?probe=1479826c17) | Aug 28, 2019 |
| Hardkernel | ODROID-H2                   | [26d6c60ad5](https://linux-hardware.org/?probe=26d6c60ad5) | Jul 06, 2019 |
| Gigabyte   | GA-MA78GM-S2HP              | [ea2ad2bc4d](https://linux-hardware.org/?probe=ea2ad2bc4d) | Jun 05, 2019 |
| Dell       | 0CRH6C A01                  | [23dcf2aff6](https://linux-hardware.org/?probe=23dcf2aff6) | Apr 08, 2019 |
| ASUSTek    | B150M-A                     | [61bb547684](https://linux-hardware.org/?probe=61bb547684) | Apr 08, 2019 |
| ASUSTek    | B150M-A                     | [8549b6dfd8](https://linux-hardware.org/?probe=8549b6dfd8) | Apr 08, 2019 |
| ASRock     | Z270 Killer SLI             | [a03ea38833](https://linux-hardware.org/?probe=a03ea38833) | Jul 06, 2018 |
| Gigabyte   | GA-M56S-S3                  | [17f0958960](https://linux-hardware.org/?probe=17f0958960) | Oct 06, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 16       | 14.55%  |
| Ubuntu 18.04        | 13       | 11.82%  |
| OpenMandriva 4.2    | 9        | 8.18%   |
| KDE neon 20.04      | 5        | 4.55%   |
| Ubuntu 19.10        | 4        | 3.64%   |
| Fedora 35           | 4        | 3.64%   |
| Ubuntu 20.10        | 3        | 2.73%   |
| OpenMandriva 4.3    | 3        | 2.73%   |
| ArcoLinux Rolling   | 3        | 2.73%   |
| Ubuntu 21.10        | 2        | 1.82%   |
| Ubuntu 19.04        | 2        | 1.82%   |
| Pop!_OS 20.10       | 2        | 1.82%   |
| Parrot 4.9          | 2        | 1.82%   |
| Gentoo 2.7          | 2        | 1.82%   |
| Fedora 31           | 2        | 1.82%   |
| Elementary 5.1.7    | 2        | 1.82%   |
| Debian 11           | 2        | 1.82%   |
| CentOS 8            | 2        | 1.82%   |
| Arch Rolling        | 2        | 1.82%   |
| Zorin 15            | 1        | 0.91%   |
| Xubuntu 18.04       | 1        | 0.91%   |
| Ubuntu MATE 20.04   | 1        | 0.91%   |
| Ubuntu 21.04        | 1        | 0.91%   |
| Slackware 15.0      | 1        | 0.91%   |
| Slackware 14.2      | 1        | 0.91%   |
| ROSA R8.1           | 1        | 0.91%   |
| Pop!_OS 22.04       | 1        | 0.91%   |
| Pop!_OS 21.04       | 1        | 0.91%   |
| OpenMandriva 4.50   | 1        | 0.91%   |
| Manjaro 21.1.0      | 1        | 0.91%   |
| Manjaro 21.0.6      | 1        | 0.91%   |
| Manjaro 20.0.3      | 1        | 0.91%   |
| Lubuntu 18.04       | 1        | 0.91%   |
| Linux Mint 20.3     | 1        | 0.91%   |
| Linux Mint 20       | 1        | 0.91%   |
| Kubuntu 21.10       | 1        | 0.91%   |
| Kubuntu 20.10       | 1        | 0.91%   |
| Kali 2021.2         | 1        | 0.91%   |
| Gentoo 2.8          | 1        | 0.91%   |
| Fedora 33           | 1        | 0.91%   |
| Fedora 32           | 1        | 0.91%   |
| EndeavourOS Rolling | 1        | 0.91%   |
| EndeavourOS         | 1        | 0.91%   |
| Elementary 6.1      | 1        | 0.91%   |
| Clear Linux 36510   | 1        | 0.91%   |
| Clear Linux 33460   | 1        | 0.91%   |
| CentOS 7            | 1        | 0.91%   |
| Artix               | 1        | 0.91%   |
| Arch                | 1        | 0.91%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 37       | 34.91%  |
| OpenMandriva | 13       | 12.26%  |
| Fedora       | 8        | 7.55%   |
| KDE neon     | 5        | 4.72%   |
| Pop!_OS      | 4        | 3.77%   |
| Manjaro      | 3        | 2.83%   |
| Gentoo       | 3        | 2.83%   |
| Elementary   | 3        | 2.83%   |
| CentOS       | 3        | 2.83%   |
| ArcoLinux    | 3        | 2.83%   |
| Arch         | 3        | 2.83%   |
| Slackware    | 2        | 1.89%   |
| Parrot       | 2        | 1.89%   |
| Linux Mint   | 2        | 1.89%   |
| Kubuntu      | 2        | 1.89%   |
| EndeavourOS  | 2        | 1.89%   |
| Debian       | 2        | 1.89%   |
| Clear Linux  | 2        | 1.89%   |
| Zorin        | 1        | 0.94%   |
| Xubuntu      | 1        | 0.94%   |
| Ubuntu MATE  | 1        | 0.94%   |
| ROSA         | 1        | 0.94%   |
| Lubuntu      | 1        | 0.94%   |
| Kali         | 1        | 0.94%   |
| Artix        | 1        | 0.94%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 9        | 7.03%   |
| 5.4.0-42-generic         | 3        | 2.34%   |
| 5.16.7-desktop-1omv4003  | 3        | 2.34%   |
| 5.5.0-1parrot1-amd64     | 2        | 1.56%   |
| 5.4.0-56-generic         | 2        | 1.56%   |
| 5.4.0-47-generic         | 2        | 1.56%   |
| 5.4.0-33-generic         | 2        | 1.56%   |
| 5.4.0-109-generic        | 2        | 1.56%   |
| 5.3.0-46-generic         | 2        | 1.56%   |
| 5.13.0-35-generic        | 2        | 1.56%   |
| 5.11.0-43-generic        | 2        | 1.56%   |
| 5.0.0-25-generic         | 2        | 1.56%   |
| 4.15.0-88-generic        | 2        | 1.56%   |
| 5.9.16-050916-generic    | 1        | 0.78%   |
| 5.9.12-artix1-1          | 1        | 0.78%   |
| 5.9.0-kali1-amd64        | 1        | 0.78%   |
| 5.8.7-arch1-1            | 1        | 0.78%   |
| 5.8.13-100.fc31.x86_64   | 1        | 0.78%   |
| 5.8.0-7642-generic       | 1        | 0.78%   |
| 5.8.0-7630-generic       | 1        | 0.78%   |
| 5.8.0-60-generic         | 1        | 0.78%   |
| 5.8.0-59-generic         | 1        | 0.78%   |
| 5.8.0-55-generic         | 1        | 0.78%   |
| 5.8.0-50-generic         | 1        | 0.78%   |
| 5.8.0-44-generic         | 1        | 0.78%   |
| 5.8.0-38-generic         | 1        | 0.78%   |
| 5.8.0-36-generic         | 1        | 0.78%   |
| 5.8.0-29-generic         | 1        | 0.78%   |
| 5.8.0-28-lowlatency      | 1        | 0.78%   |
| 5.7.7-967.native         | 1        | 0.78%   |
| 5.7.0-3-MANJARO          | 1        | 0.78%   |
| 5.6.14-300.fc32.x86_64   | 1        | 0.78%   |
| 5.6.0-pf6                | 1        | 0.78%   |
| 5.5.10-200.fc31.x86_64   | 1        | 0.78%   |
| 5.4.0-91-generic         | 1        | 0.78%   |
| 5.4.0-90-generic         | 1        | 0.78%   |
| 5.4.0-74-generic         | 1        | 0.78%   |
| 5.4.0-73-generic         | 1        | 0.78%   |
| 5.4.0-66-generic         | 1        | 0.78%   |
| 5.4.0-54-generic         | 1        | 0.78%   |
| 5.4.0-52-generic         | 1        | 0.78%   |
| 5.4.0-31-generic         | 1        | 0.78%   |
| 5.4.0-28-generic         | 1        | 0.78%   |
| 5.4.0-26-generic         | 1        | 0.78%   |
| 5.4.0-21-generic         | 1        | 0.78%   |
| 5.4.0-110-generic        | 1        | 0.78%   |
| 5.3.0-45-generic         | 1        | 0.78%   |
| 5.3.0-29-generic         | 1        | 0.78%   |
| 5.3.0-28-generic         | 1        | 0.78%   |
| 5.3.0-24-generic         | 1        | 0.78%   |
| 5.3.0-23-generic         | 1        | 0.78%   |
| 5.18.5-zen1-1-zen        | 1        | 0.78%   |
| 5.18.2-1157.native       | 1        | 0.78%   |
| 5.17.5-zen1-1-zen        | 1        | 0.78%   |
| 5.17.5-76051705-generic  | 1        | 0.78%   |
| 5.17.0-gentoo            | 1        | 0.78%   |
| 5.16.2-arch1-1           | 1        | 0.78%   |
| 5.16.12-200.fc35.x86_64  | 1        | 0.78%   |
| 5.16.11-arch1-2          | 1        | 0.78%   |
| 5.15.8-arch1-1           | 1        | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 20       | 17.09%  |
| 5.8.0   | 9        | 7.69%   |
| 5.10.14 | 9        | 7.69%   |
| 5.3.0   | 7        | 5.98%   |
| 5.11.0  | 7        | 5.98%   |
| 5.13.0  | 6        | 5.13%   |
| 4.15.0  | 6        | 5.13%   |
| 5.0.0   | 5        | 4.27%   |
| 5.16.7  | 3        | 2.56%   |
| 5.10.0  | 3        | 2.56%   |
| 4.18.0  | 3        | 2.56%   |
| 5.5.0   | 2        | 1.71%   |
| 5.17.5  | 2        | 1.71%   |
| 5.14.14 | 2        | 1.71%   |
| 5.9.16  | 1        | 0.85%   |
| 5.9.12  | 1        | 0.85%   |
| 5.9.0   | 1        | 0.85%   |
| 5.8.7   | 1        | 0.85%   |
| 5.8.13  | 1        | 0.85%   |
| 5.7.7   | 1        | 0.85%   |
| 5.7.0   | 1        | 0.85%   |
| 5.6.14  | 1        | 0.85%   |
| 5.6.0   | 1        | 0.85%   |
| 5.5.10  | 1        | 0.85%   |
| 5.18.5  | 1        | 0.85%   |
| 5.18.2  | 1        | 0.85%   |
| 5.17.0  | 1        | 0.85%   |
| 5.16.2  | 1        | 0.85%   |
| 5.16.12 | 1        | 0.85%   |
| 5.16.11 | 1        | 0.85%   |
| 5.15.8  | 1        | 0.85%   |
| 5.15.6  | 1        | 0.85%   |
| 5.15.30 | 1        | 0.85%   |
| 5.15.0  | 1        | 0.85%   |
| 5.13.11 | 1        | 0.85%   |
| 5.13.10 | 1        | 0.85%   |
| 5.12.4  | 1        | 0.85%   |
| 5.12.15 | 1        | 0.85%   |
| 5.10.76 | 1        | 0.85%   |
| 5.10.44 | 1        | 0.85%   |
| 5.10.41 | 1        | 0.85%   |
| 5.10.37 | 1        | 0.85%   |
| 5.10.15 | 1        | 0.85%   |
| 4.9.9   | 1        | 0.85%   |
| 4.4.240 | 1        | 0.85%   |
| 4.17.3  | 1        | 0.85%   |
| 3.10.0  | 1        | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 20       | 17.24%  |
| 5.10    | 16       | 13.79%  |
| 5.8     | 11       | 9.48%   |
| 5.13    | 8        | 6.9%    |
| 5.3     | 7        | 6.03%   |
| 5.11    | 7        | 6.03%   |
| 5.16    | 6        | 5.17%   |
| 4.15    | 6        | 5.17%   |
| 5.0     | 5        | 4.31%   |
| 5.15    | 4        | 3.45%   |
| 5.9     | 3        | 2.59%   |
| 5.5     | 3        | 2.59%   |
| 5.17    | 3        | 2.59%   |
| 4.18    | 3        | 2.59%   |
| 5.7     | 2        | 1.72%   |
| 5.6     | 2        | 1.72%   |
| 5.18    | 2        | 1.72%   |
| 5.14    | 2        | 1.72%   |
| 5.12    | 2        | 1.72%   |
| 4.9     | 1        | 0.86%   |
| 4.4     | 1        | 0.86%   |
| 4.17    | 1        | 0.86%   |
| 3.10    | 1        | 0.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 102      | 99.03%  |
| i686   | 1        | 0.97%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 43       | 39.09%  |
| KDE5       | 23       | 20.91%  |
| Unknown    | 19       | 17.27%  |
| XFCE       | 6        | 5.45%   |
| KDE        | 4        | 3.64%   |
| Pantheon   | 3        | 2.73%   |
| MATE       | 3        | 2.73%   |
| X-Cinnamon | 2        | 1.82%   |
| Unity      | 1        | 0.91%   |
| openbox    | 1        | 0.91%   |
| LXDE       | 1        | 0.91%   |
| KDE4       | 1        | 0.91%   |
| i3         | 1        | 0.91%   |
| Deepin     | 1        | 0.91%   |
| awesome    | 1        | 0.91%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 84       | 77.78%  |
| Wayland | 13       | 12.04%  |
| Unknown | 9        | 8.33%   |
| Tty     | 2        | 1.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 60       | 56.07%  |
| SDDM    | 26       | 24.3%   |
| GDM     | 9        | 8.41%   |
| GDM3    | 5        | 4.67%   |
| LightDM | 3        | 2.8%    |
| TDM     | 2        | 1.87%   |
| XDM     | 1        | 0.93%   |
| KDM     | 1        | 0.93%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_HK   | 38       | 35.51%  |
| en_US   | 33       | 30.84%  |
| Unknown | 12       | 11.21%  |
| zh_TW   | 8        | 7.48%   |
| zh_CN   | 7        | 6.54%   |
| zh_HK   | 3        | 2.8%    |
| en_GB   | 3        | 2.8%    |
| en_AU   | 2        | 1.87%   |
| C       | 1        | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 53       | 50%     |
| EFI  | 53       | 50%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 78       | 73.58%  |
| Btrfs   | 10       | 9.43%   |
| Overlay | 7        | 6.6%    |
| Xfs     | 5        | 4.72%   |
| Zfs     | 3        | 2.83%   |
| F2fs    | 1        | 0.94%   |
| Ext3    | 1        | 0.94%   |
| Unknown | 1        | 0.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 58       | 55.77%  |
| GPT     | 37       | 35.58%  |
| MBR     | 9        | 8.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 85       | 80.95%  |
| Yes       | 20       | 19.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 75       | 70.09%  |
| Yes       | 32       | 29.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 27       | 26.21%  |
| Gigabyte Technology | 21       | 20.39%  |
| MSI                 | 18       | 17.48%  |
| ASRock              | 9        | 8.74%   |
| Hewlett-Packard     | 6        | 5.83%   |
| Dell                | 6        | 5.83%   |
| Lenovo              | 5        | 4.85%   |
| Supermicro          | 2        | 1.94%   |
| Intel               | 2        | 1.94%   |
| Seco                | 1        | 0.97%   |
| Huanan              | 1        | 0.97%   |
| Hardkernel          | 1        | 0.97%   |
| Foxconn             | 1        | 0.97%   |
| Biostar             | 1        | 0.97%   |
| Acer                | 1        | 0.97%   |
| Unknown             | 1        | 0.97%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| ASUS H110I-PLUS                              | 3        | 2.91%   |
| ASUS All Series                              | 3        | 2.91%   |
| MSI MS-7C94                                  | 2        | 1.94%   |
| Gigabyte X570 AORUS ELITE                    | 2        | 1.94%   |
| ASUS Z8NA-D6                                 | 2        | 1.94%   |
| ASUS VM65                                    | 2        | 1.94%   |
| ASUS VM62                                    | 2        | 1.94%   |
| ASRock H410M-ITX/ac                          | 2        | 1.94%   |
| ASRock H410M-HDV                             | 2        | 1.94%   |
| Supermicro PIO-617R-TLN4F+-ST031             | 1        | 0.97%   |
| Supermicro C2SBC-Q                           | 1        | 0.97%   |
| Seco C40                                     | 1        | 0.97%   |
| MSI Pro 3130 Small Form Factor PC            | 1        | 0.97%   |
| MSI MS-7C52                                  | 1        | 0.97%   |
| MSI MS-7C34                                  | 1        | 0.97%   |
| MSI MS-7C02                                  | 1        | 0.97%   |
| MSI MS-7B93                                  | 1        | 0.97%   |
| MSI MS-7B89                                  | 1        | 0.97%   |
| MSI MS-7B78                                  | 1        | 0.97%   |
| MSI MS-7B53                                  | 1        | 0.97%   |
| MSI MS-7A40                                  | 1        | 0.97%   |
| MSI MS-7A38                                  | 1        | 0.97%   |
| MSI MS-7918                                  | 1        | 0.97%   |
| MSI MS-7851                                  | 1        | 0.97%   |
| MSI MS-7798                                  | 1        | 0.97%   |
| MSI MS-7680                                  | 1        | 0.97%   |
| MSI MS-7599                                  | 1        | 0.97%   |
| MSI KT541AA-UUB a6528hk                      | 1        | 0.97%   |
| Lenovo ZHENGJIUZHE REN9000K-34IMZ 90Q90022CP | 1        | 0.97%   |
| Lenovo ThinkCentre M92p 3227D13              | 1        | 0.97%   |
| Lenovo ThinkCentre M90p 3269A12              | 1        | 0.97%   |
| Lenovo ThinkCentre M73 10AYCTO1WW            | 1        | 0.97%   |
| Lenovo IdeaCentre K330                       | 1        | 0.97%   |
| Intel DZ68DB AAG27985-101                    | 1        | 0.97%   |
| Intel DH77DF AAG40293-301                    | 1        | 0.97%   |
| Huanan X99-TF                                | 1        | 0.97%   |
| HP Z240 SFF Workstation                      | 1        | 0.97%   |
| HP rp5800                                    | 1        | 0.97%   |
| HP ProDesk 600 G5 SFF                        | 1        | 0.97%   |
| HP ProDesk 600 G1 SFF                        | 1        | 0.97%   |
| HP EliteDesk 800 G1 SFF                      | 1        | 0.97%   |
| HP 200-010hk                                 | 1        | 0.97%   |
| Hardkernel ODROID-H2                         | 1        | 0.97%   |
| Gigabyte Z87-HD3                             | 1        | 0.97%   |
| Gigabyte Z77N-WIFI                           | 1        | 0.97%   |
| Gigabyte Z390 GAMING X                       | 1        | 0.97%   |
| Gigabyte Z370 HD3P                           | 1        | 0.97%   |
| Gigabyte Z170X-Gaming 5                      | 1        | 0.97%   |
| Gigabyte X570 AORUS PRO WIFI                 | 1        | 0.97%   |
| Gigabyte P55A-UD3                            | 1        | 0.97%   |
| Gigabyte M56S-S3                             | 1        | 0.97%   |
| Gigabyte HA65M-UD3H-B3                       | 1        | 0.97%   |
| Gigabyte H310M S2H 2.0                       | 1        | 0.97%   |
| Gigabyte GA-MA78GM-S2HP                      | 1        | 0.97%   |
| Gigabyte GA-880GMA-UD2H                      | 1        | 0.97%   |
| Gigabyte F2A88XN-WIFI                        | 1        | 0.97%   |
| Gigabyte B85M-DS3H-A                         | 1        | 0.97%   |
| Gigabyte B75M-D2P                            | 1        | 0.97%   |
| Gigabyte B660M DS3H AX DDR4                  | 1        | 0.97%   |
| Gigabyte B450 AORUS PRO WIFI                 | 1        | 0.97%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Lenovo ThinkCentre               | 3        | 2.91%   |
| Gigabyte X570                    | 3        | 2.91%   |
| ASUS PRIME                       | 3        | 2.91%   |
| ASUS H110I-PLUS                  | 3        | 2.91%   |
| ASUS All                         | 3        | 2.91%   |
| MSI MS-7C94                      | 2        | 1.94%   |
| HP ProDesk                       | 2        | 1.94%   |
| Dell Precision                   | 2        | 1.94%   |
| Dell OptiPlex                    | 2        | 1.94%   |
| Dell Inspiron                    | 2        | 1.94%   |
| ASUS Z8NA-D6                     | 2        | 1.94%   |
| ASUS VM65                        | 2        | 1.94%   |
| ASUS VM62                        | 2        | 1.94%   |
| ASUS TUF                         | 2        | 1.94%   |
| ASRock H410M-ITX                 | 2        | 1.94%   |
| ASRock H410M-HDV                 | 2        | 1.94%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1        | 0.97%   |
| Supermicro C2SBC-Q               | 1        | 0.97%   |
| Seco C40                         | 1        | 0.97%   |
| MSI Pro                          | 1        | 0.97%   |
| MSI MS-7C52                      | 1        | 0.97%   |
| MSI MS-7C34                      | 1        | 0.97%   |
| MSI MS-7C02                      | 1        | 0.97%   |
| MSI MS-7B93                      | 1        | 0.97%   |
| MSI MS-7B89                      | 1        | 0.97%   |
| MSI MS-7B78                      | 1        | 0.97%   |
| MSI MS-7B53                      | 1        | 0.97%   |
| MSI MS-7A40                      | 1        | 0.97%   |
| MSI MS-7A38                      | 1        | 0.97%   |
| MSI MS-7918                      | 1        | 0.97%   |
| MSI MS-7851                      | 1        | 0.97%   |
| MSI MS-7798                      | 1        | 0.97%   |
| MSI MS-7680                      | 1        | 0.97%   |
| MSI MS-7599                      | 1        | 0.97%   |
| MSI KT541AA-UUB                  | 1        | 0.97%   |
| Lenovo ZHENGJIUZHE               | 1        | 0.97%   |
| Lenovo IdeaCentre                | 1        | 0.97%   |
| Intel DZ68DB                     | 1        | 0.97%   |
| Intel DH77DF                     | 1        | 0.97%   |
| Huanan X99-TF                    | 1        | 0.97%   |
| HP Z240                          | 1        | 0.97%   |
| HP rp5800                        | 1        | 0.97%   |
| HP EliteDesk                     | 1        | 0.97%   |
| HP 200-010hk                     | 1        | 0.97%   |
| Hardkernel ODROID-H2             | 1        | 0.97%   |
| Gigabyte Z87-HD3                 | 1        | 0.97%   |
| Gigabyte Z77N-WIFI               | 1        | 0.97%   |
| Gigabyte Z390                    | 1        | 0.97%   |
| Gigabyte Z370                    | 1        | 0.97%   |
| Gigabyte Z170X-Gaming            | 1        | 0.97%   |
| Gigabyte P55A-UD3                | 1        | 0.97%   |
| Gigabyte M56S-S3                 | 1        | 0.97%   |
| Gigabyte HA65M-UD3H-B3           | 1        | 0.97%   |
| Gigabyte H310M                   | 1        | 0.97%   |
| Gigabyte GA-MA78GM-S2HP          | 1        | 0.97%   |
| Gigabyte GA-880GMA-UD2H          | 1        | 0.97%   |
| Gigabyte F2A88XN-WIFI            | 1        | 0.97%   |
| Gigabyte B85M-DS3H-A             | 1        | 0.97%   |
| Gigabyte B75M-D2P                | 1        | 0.97%   |
| Gigabyte B660M                   | 1        | 0.97%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 14       | 13.59%  |
| 2018 | 12       | 11.65%  |
| 2020 | 11       | 10.68%  |
| 2013 | 11       | 10.68%  |
| 2016 | 10       | 9.71%   |
| 2010 | 9        | 8.74%   |
| 2015 | 7        | 6.8%    |
| 2014 | 7        | 6.8%    |
| 2011 | 6        | 5.83%   |
| 2017 | 4        | 3.88%   |
| 2012 | 3        | 2.91%   |
| 2008 | 3        | 2.91%   |
| 2021 | 2        | 1.94%   |
| 2009 | 2        | 1.94%   |
| 2022 | 1        | 0.97%   |
| 2007 | 1        | 0.97%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 103      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 100      | 97.09%  |
| Enabled  | 3        | 2.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 103      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 27       | 25.47%  |
| 8.01-16.0   | 24       | 22.64%  |
| 32.01-64.0  | 17       | 16.04%  |
| 64.01-256.0 | 12       | 11.32%  |
| 4.01-8.0    | 11       | 10.38%  |
| 3.01-4.0    | 11       | 10.38%  |
| 24.01-32.0  | 3        | 2.83%   |
| 2.01-3.0    | 1        | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 36       | 31.03%  |
| 2.01-3.0   | 32       | 27.59%  |
| 4.01-8.0   | 20       | 17.24%  |
| 3.01-4.0   | 13       | 11.21%  |
| 8.01-16.0  | 6        | 5.17%   |
| 0.51-1.0   | 6        | 5.17%   |
| 16.01-24.0 | 2        | 1.72%   |
| 0.01-0.5   | 1        | 0.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 46       | 42.99%  |
| 2      | 26       | 24.3%   |
| 3      | 19       | 17.76%  |
| 4      | 6        | 5.61%   |
| 5      | 5        | 4.67%   |
| 9      | 2        | 1.87%   |
| 6      | 2        | 1.87%   |
| 7      | 1        | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 62.86%  |
| Yes       | 39       | 37.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 101      | 98.06%  |
| No        | 2        | 1.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 54       | 50.94%  |
| No        | 52       | 49.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 50.47%  |
| Yes       | 53       | 49.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Hong Kong | 103      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Central          | 55       | 50.46%  |
| Tuen Mun         | 9        | 8.26%   |
| Kowloon          | 6        | 5.5%    |
| Ngau Wu Tok      | 4        | 3.67%   |
| Tseung Kwan O    | 3        | 2.75%   |
| To Kwa Wan       | 3        | 2.75%   |
| Ma On Shan Tsuen | 3        | 2.75%   |
| Yuen Long        | 2        | 1.83%   |
| Wanchai          | 2        | 1.83%   |
| Quarry Bay       | 2        | 1.83%   |
| Kwu Tung         | 2        | 1.83%   |
| Hong Kong        | 2        | 1.83%   |
| Cheung Sha Lan   | 2        | 1.83%   |
| Tung Chung       | 1        | 0.92%   |
| Tsimshatsui      | 1        | 0.92%   |
| Tai Wan To       | 1        | 0.92%   |
| Tai Po           | 1        | 0.92%   |
| Tai Kok Tsui     | 1        | 0.92%   |
| Sheung Shui      | 1        | 0.92%   |
| Shatin           | 1        | 0.92%   |
| Sham Shui Po     | 1        | 0.92%   |
| Sai Kung         | 1        | 0.92%   |
| Ma Wan           | 1        | 0.92%   |
| Kwun Hang        | 1        | 0.92%   |
| Hung Hom         | 1        | 0.92%   |
| Ho Man Tin       | 1        | 0.92%   |
| Fo Tan           | 1        | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 36       | 54     | 18.75%  |
| WDC                         | 22       | 47     | 11.46%  |
| Toshiba                     | 17       | 24     | 8.85%   |
| Samsung Electronics         | 17       | 29     | 8.85%   |
| A-DATA Technology           | 12       | 18     | 6.25%   |
| Kingston                    | 8        | 9      | 4.17%   |
| SanDisk                     | 7        | 7      | 3.65%   |
| Hitachi                     | 7        | 12     | 3.65%   |
| Silicon Motion              | 5        | 6      | 2.6%    |
| Crucial                     | 5        | 5      | 2.6%    |
| LITEON                      | 4        | 4      | 2.08%   |
| Intel                       | 4        | 8      | 2.08%   |
| Fujitsu                     | 4        | 9      | 2.08%   |
| Transcend                   | 3        | 3      | 1.56%   |
| Phison                      | 3        | 6      | 1.56%   |
| JMicron Technology          | 3        | 6      | 1.56%   |
| HGST                        | 3        | 3      | 1.56%   |
| DOGGO                       | 3        | 3      | 1.56%   |
| Unknown                     | 2        | 2      | 1.04%   |
| Team                        | 2        | 2      | 1.04%   |
| SK hynix                    | 2        | 6      | 1.04%   |
| Lite-On                     | 2        | 3      | 1.04%   |
| Hikvision                   | 2        | 2      | 1.04%   |
| Gigabyte Technology         | 2        | 5      | 1.04%   |
| ZHITAI                      | 1        | 2      | 0.52%   |
| Yangtze Memory Technologies | 1        | 1      | 0.52%   |
| XPG                         | 1        | 1      | 0.52%   |
| tigo                        | 1        | 1      | 0.52%   |
| SPCC                        | 1        | 1      | 0.52%   |
| PNY                         | 1        | 1      | 0.52%   |
| OCZ                         | 1        | 1      | 0.52%   |
| Micron Technology           | 1        | 1      | 0.52%   |
| Maxmemory                   | 1        | 2      | 0.52%   |
| Lexar                       | 1        | 1      | 0.52%   |
| KIOXIA-EXCERIA              | 1        | 2      | 0.52%   |
| HS-SSD-C100                 | 1        | 1      | 0.52%   |
| HGST HTS                    | 1        | 1      | 0.52%   |
| Dogfish                     | 1        | 1      | 0.52%   |
| Corsair                     | 1        | 1      | 0.52%   |
| Apacer                      | 1        | 1      | 0.52%   |
| Aoluska                     | 1        | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB              | 5        | 2.3%    |
| Toshiba DT01ACA100 1TB               | 4        | 1.84%   |
| A-DATA SP550 240GB SSD               | 4        | 1.84%   |
| WDC WD10EZEX-08WN4A0 1TB             | 3        | 1.38%   |
| Toshiba DT01ACA050 500GB             | 3        | 1.38%   |
| Seagate ST500DM002-1BD142 500GB      | 3        | 1.38%   |
| Seagate ST3500413AS 500GB            | 3        | 1.38%   |
| Kingston SA400S37480G 480GB SSD      | 3        | 1.38%   |
| JMicron Generic 2TB                  | 3        | 1.38%   |
| Fujitsu F300 480GB                   | 3        | 1.38%   |
| DOGGO DQ-60G SSD                     | 3        | 1.38%   |
| WDC WD30EZRX-00D8PB0 3TB             | 2        | 0.92%   |
| Toshiba DT01ACA300 3TB               | 2        | 0.92%   |
| SK hynix SC311 SATA 128GB SSD        | 2        | 0.92%   |
| Silicon Motion NVMe SSD Drive 512GB  | 2        | 0.92%   |
| Silicon Motion NVMe SSD Drive 1024GB | 2        | 0.92%   |
| Seagate ST4000DM004-2CV104 4TB       | 2        | 0.92%   |
| Seagate ST3250318AS 250GB            | 2        | 0.92%   |
| Seagate ST3250310AS 250GB            | 2        | 0.92%   |
| Seagate ST3160815AS 160GB            | 2        | 0.92%   |
| Seagate ST2000DM008-2FR102 2TB       | 2        | 0.92%   |
| Seagate ST1000DM010-2EP102 1TB       | 2        | 0.92%   |
| Samsung SSD 970 EVO Plus 1TB         | 2        | 0.92%   |
| Samsung NVMe SSD Drive 512GB         | 2        | 0.92%   |
| LITEON CV6-CQ128 128GB SSD           | 2        | 0.92%   |
| Lite-On NVMe SSD Drive 512GB         | 2        | 0.92%   |
| Intel SSDPEKNW020T8 2TB              | 2        | 0.92%   |
| Hitachi HDT721010SLA360 1TB          | 2        | 0.92%   |
| Crucial CT500MX500SSD1 500GB         | 2        | 0.92%   |
| A-DATA HC660 1TB SSD                 | 2        | 0.92%   |
| ZHITAI SC001 Active 1TB SSD          | 1        | 0.46%   |
| ZHITAI PC005 Active 512GB            | 1        | 0.46%   |
| Yangtze Memory NVMe SSD Drive 1024GB | 1        | 0.46%   |
| XPG NVMe SSD Drive 1TB               | 1        | 0.46%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1        | 0.46%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1        | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1        | 0.46%   |
| WDC WDS500G1X0E-00AFY0 500GB         | 1        | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1        | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1        | 0.46%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1        | 0.46%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1        | 0.46%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1        | 0.46%   |
| WDC WD5002ABYS-02B1B0 500GB          | 1        | 0.46%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1        | 0.46%   |
| WDC WD5000AAKX-001CA0 500GB          | 1        | 0.46%   |
| WDC WD5000AAKS-40YGA1 500GB          | 1        | 0.46%   |
| WDC WD5000AAKS-22V1A0 500GB          | 1        | 0.46%   |
| WDC WD50 00LPLX-75ZNTT0 500GB        | 1        | 0.46%   |
| WDC WD40EZRZ-75GXCB0 4TB             | 1        | 0.46%   |
| WDC WD40EZRZ-00GXCB0 4TB             | 1        | 0.46%   |
| WDC WD40EZAZ-00SF3B0 4TB             | 1        | 0.46%   |
| WDC WD40EJRX-89T1XY0 4TB             | 1        | 0.46%   |
| WDC WD4003FZEX-00Z4SA0 4TB           | 1        | 0.46%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1        | 0.46%   |
| WDC WD20EARX-00PASB0 2TB             | 1        | 0.46%   |
| WDC WD10EZEX-60WN4A1 1TB             | 1        | 0.46%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1        | 0.46%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1        | 0.46%   |
| WDC WD10EARS-00Y5B1 1TB              | 1        | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| Seagate            | 36       | 54     | 42.86%  |
| Toshiba            | 17       | 24     | 20.24%  |
| WDC                | 15       | 36     | 17.86%  |
| Hitachi            | 7        | 12     | 8.33%   |
| JMicron Technology | 3        | 6      | 3.57%   |
| HGST               | 3        | 3      | 3.57%   |
| Unknown            | 1        | 1      | 1.19%   |
| HGST HTS           | 1        | 1      | 1.19%   |
| Fujitsu            | 1        | 1      | 1.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 17     | 14.49%  |
| A-DATA Technology   | 10       | 16     | 14.49%  |
| Kingston            | 6        | 7      | 8.7%    |
| SanDisk             | 5        | 5      | 7.25%   |
| Crucial             | 5        | 5      | 7.25%   |
| WDC                 | 4        | 4      | 5.8%    |
| Transcend           | 3        | 3      | 4.35%   |
| LITEON              | 3        | 3      | 4.35%   |
| Fujitsu             | 3        | 8      | 4.35%   |
| DOGGO               | 3        | 3      | 4.35%   |
| Team                | 2        | 2      | 2.9%    |
| SK hynix            | 2        | 6      | 2.9%    |
| ZHITAI              | 1        | 1      | 1.45%   |
| tigo                | 1        | 1      | 1.45%   |
| SPCC                | 1        | 1      | 1.45%   |
| PNY                 | 1        | 1      | 1.45%   |
| OCZ                 | 1        | 1      | 1.45%   |
| Micron Technology   | 1        | 1      | 1.45%   |
| Lexar               | 1        | 1      | 1.45%   |
| Intel               | 1        | 3      | 1.45%   |
| Hikvision           | 1        | 1      | 1.45%   |
| Dogfish             | 1        | 1      | 1.45%   |
| Corsair             | 1        | 1      | 1.45%   |
| Apacer              | 1        | 1      | 1.45%   |
| Aoluska             | 1        | 1      | 1.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 68       | 138    | 41.98%  |
| SSD     | 58       | 94     | 35.8%   |
| NVMe    | 33       | 57     | 20.37%  |
| Unknown | 2        | 3      | 1.23%   |
| MMC     | 1        | 1      | 0.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 92       | 217    | 67.15%  |
| NVMe | 33       | 57     | 24.09%  |
| SAS  | 11       | 18     | 8.03%   |
| MMC  | 1        | 1      | 0.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 68       | 112    | 50.37%  |
| 0.51-1.0   | 36       | 54     | 26.67%  |
| 1.01-2.0   | 14       | 21     | 10.37%  |
| 2.01-3.0   | 8        | 13     | 5.93%   |
| 3.01-4.0   | 6        | 27     | 4.44%   |
| 4.01-10.0  | 3        | 5      | 2.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 26       | 23.64%  |
| 251-500        | 19       | 17.27%  |
| 501-1000       | 16       | 14.55%  |
| 51-100         | 13       | 11.82%  |
| 1001-2000      | 11       | 10%     |
| More than 3000 | 9        | 8.18%   |
| 2001-3000      | 7        | 6.36%   |
| Unknown        | 6        | 5.45%   |
| 1-20           | 3        | 2.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 43       | 35.83%  |
| 101-250        | 20       | 16.67%  |
| 251-500        | 13       | 10.83%  |
| 21-50          | 12       | 10%     |
| 501-1000       | 8        | 6.67%   |
| 51-100         | 8        | 6.67%   |
| Unknown        | 6        | 5%      |
| 1001-2000      | 5        | 4.17%   |
| 2001-3000      | 4        | 3.33%   |
| More than 3000 | 1        | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| WDC WD30EZRX-00D8PB0 3TB                  | 1        | 1      | 7.14%   |
| WDC WD10EZEX-60WN4A1 1TB                  | 1        | 1      | 7.14%   |
| WDC WD10EZEX-00RKKA0 1TB                  | 1        | 1      | 7.14%   |
| WDC WD10EALS-00Z8A0 1TB                   | 1        | 2      | 7.14%   |
| Toshiba MK1252GSX 120GB                   | 1        | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB           | 1        | 1      | 7.14%   |
| Seagate ST3250310AS 250GB                 | 1        | 1      | 7.14%   |
| Seagate ST3160815AS 160GB                 | 1        | 1      | 7.14%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB       | 1        | 1      | 7.14%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD | 1        | 1      | 7.14%   |
| Kingston SA400S37480G 480GB SSD           | 1        | 1      | 7.14%   |
| Intel SSDPEKKW128G7 128GB                 | 1        | 1      | 7.14%   |
| Hitachi HTS542512K9SA00 120GB             | 1        | 1      | 7.14%   |
| HGST HTS 541010A9E680 1TB                 | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 4        | 4      | 30.77%  |
| WDC      | 3        | 5      | 23.08%  |
| Toshiba  | 1        | 1      | 7.69%   |
| LITEON   | 1        | 1      | 7.69%   |
| Kingston | 1        | 1      | 7.69%   |
| Intel    | 1        | 1      | 7.69%   |
| Hitachi  | 1        | 1      | 7.69%   |
| HGST HTS | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 4        | 4      | 40%     |
| WDC      | 3        | 5      | 30%     |
| Toshiba  | 1        | 1      | 10%     |
| Hitachi  | 1        | 1      | 10%     |
| HGST HTS | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 12     | 75%     |
| SSD  | 2        | 2      | 16.67%  |
| NVMe | 1        | 1      | 8.33%   |

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
| Detected | 61       | 168    | 53.04%  |
| Works    | 42       | 110    | 36.52%  |
| Malfunc  | 12       | 15     | 10.43%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 77       | 50.66%  |
| AMD                           | 25       | 16.45%  |
| Samsung Electronics           | 9        | 5.92%   |
| Silicon Motion                | 6        | 3.95%   |
| ASMedia Technology            | 6        | 3.95%   |
| SanDisk                       | 5        | 3.29%   |
| Phison Electronics            | 5        | 3.29%   |
| Marvell Technology Group      | 3        | 1.97%   |
| ADATA Technology              | 3        | 1.97%   |
| Yangtze Memory Technologies   | 2        | 1.32%   |
| Lite-On Technology            | 2        | 1.32%   |
| Kingston Technology Company   | 2        | 1.32%   |
| JMicron Technology            | 2        | 1.32%   |
| VIA Technologies              | 1        | 0.66%   |
| Nvidia                        | 1        | 0.66%   |
| LSI Logic / Symbios Logic     | 1        | 0.66%   |
| KIOXIA                        | 1        | 0.66%   |
| Integrated Technology Express | 1        | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 7.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 5.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9        | 5.17%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 5.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 4.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 4.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 3.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 3.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 2.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.87%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 2.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 2.3%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 2.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 1.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.72%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.72%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 1.72%   |
| Yangtze Memory Non-Volatile memory controller                                           | 2        | 1.15%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 1.15%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2        | 1.15%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 1.15%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.15%   |
| Phison E12 NVMe Controller                                                              | 2        | 1.15%   |
| Lite-On Non-Volatile memory controller                                                  | 2        | 1.15%   |
| Intel SSD 660P Series                                                                   | 2        | 1.15%   |
| Intel SSD 600P Series                                                                   | 2        | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 1.15%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 1.15%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 1.15%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 0.57%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.57%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1        | 0.57%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.57%   |
| Nvidia MCP65 SATA Controller                                                            | 1        | 0.57%   |
| Nvidia MCP65 IDE                                                                        | 1        | 0.57%   |
| Marvell Group MV64460/64461/64462 System Controller, Revision B                         | 1        | 0.57%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                                   | 1        | 0.57%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1        | 0.57%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1        | 0.57%   |
| KIOXIA NVMe SSD                                                                         | 1        | 0.57%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1        | 0.57%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.57%   |
| JMicron JMB58x AHCI SATA controller                                                     | 1        | 0.57%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.57%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1        | 0.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.57%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 1        | 0.57%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 1        | 0.57%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 1        | 0.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1        | 0.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 96       | 66.21%  |
| NVMe | 33       | 22.76%  |
| IDE  | 11       | 7.59%   |
| RAID | 4        | 2.76%   |
| SAS  | 1        | 0.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 77       | 74.76%  |
| AMD    | 26       | 25.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Core i7-6700 CPU @ 3.40GHz         | 4        | 3.85%   |
| Intel Core i7-7700K CPU @ 4.20GHz        | 3        | 2.88%   |
| Intel Core i5-6400 CPU @ 2.70GHz         | 3        | 2.88%   |
| Intel Core i3-10100 CPU @ 3.60GHz        | 3        | 2.88%   |
| AMD Ryzen 7 5700G with Radeon Graphics   | 3        | 2.88%   |
| AMD Ryzen 5 3600 6-Core Processor        | 3        | 2.88%   |
| Intel Xeon CPU X5675 @ 3.07GHz           | 2        | 1.92%   |
| Intel Core i7-9700K CPU @ 3.60GHz        | 2        | 1.92%   |
| Intel Core i7-9700 CPU @ 3.00GHz         | 2        | 1.92%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 2        | 1.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz         | 2        | 1.92%   |
| Intel Core i7-2600 CPU @ 3.40GHz         | 2        | 1.92%   |
| Intel Core i5-8400 CPU @ 2.80GHz         | 2        | 1.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 2        | 1.92%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 2        | 1.92%   |
| AMD Ryzen 9 5900X 12-Core Processor      | 2        | 1.92%   |
| AMD Ryzen 7 3700X 8-Core Processor       | 2        | 1.92%   |
| AMD Ryzen 5 5600X 6-Core Processor       | 2        | 1.92%   |
| Intel Xeon CPU X5650 @ 2.67GHz           | 1        | 0.96%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz      | 1        | 0.96%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz      | 1        | 0.96%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz      | 1        | 0.96%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz      | 1        | 0.96%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz      | 1        | 0.96%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz   | 1        | 0.96%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz   | 1        | 0.96%   |
| Intel Pentium CPU G640 @ 2.80GHz         | 1        | 0.96%   |
| Intel Pentium CPU G620T @ 2.20GHz        | 1        | 0.96%   |
| Intel Pentium CPU G4560 @ 3.50GHz        | 1        | 0.96%   |
| Intel Pentium CPU G4400 @ 3.30GHz        | 1        | 0.96%   |
| Intel Pentium CPU G3250T @ 2.80GHz       | 1        | 0.96%   |
| Intel Core i9-9900 CPU @ 3.10GHz         | 1        | 0.96%   |
| Intel Core i9-10900K CPU @ 3.70GHz       | 1        | 0.96%   |
| Intel Core i7-6700K CPU @ 4.00GHz        | 1        | 0.96%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 1        | 0.96%   |
| Intel Core i7-10700K CPU @ 3.80GHz       | 1        | 0.96%   |
| Intel Core i7 CPU 860 @ 2.80GHz          | 1        | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1        | 0.96%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1        | 0.96%   |
| Intel Core i5-4570 CPU @ 3.20GHz         | 1        | 0.96%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 1        | 0.96%   |
| Intel Core i5-4440 CPU @ 3.10GHz         | 1        | 0.96%   |
| Intel Core i5-4430 CPU @ 3.00GHz         | 1        | 0.96%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 1        | 0.96%   |
| Intel Core i5-2500 CPU @ 3.30GHz         | 1        | 0.96%   |
| Intel Core i5 CPU 650 @ 3.20GHz          | 1        | 0.96%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 1        | 0.96%   |
| Intel Core i3-4160T CPU @ 3.10GHz        | 1        | 0.96%   |
| Intel Core i3-4130 CPU @ 3.40GHz         | 1        | 0.96%   |
| Intel Core i3-4030U CPU @ 1.90GHz        | 1        | 0.96%   |
| Intel Core i3-3225 CPU @ 3.30GHz         | 1        | 0.96%   |
| Intel Core i3-2120 CPU @ 3.30GHz         | 1        | 0.96%   |
| Intel Core i3-10105 CPU @ 3.70GHz        | 1        | 0.96%   |
| Intel Core i3 CPU 550 @ 3.20GHz          | 1        | 0.96%   |
| Intel Core i3 CPU 540 @ 3.07GHz          | 1        | 0.96%   |
| Intel Core 2 Quad CPU Q6700 @ 2.66GHz    | 1        | 0.96%   |
| Intel Core 2 Extreme CPU X9650 @ 3.00GHz | 1        | 0.96%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 1        | 0.96%   |
| Intel Celeron CPU G3930 @ 2.90GHz        | 1        | 0.96%   |
| Intel Celeron CPU 3865U @ 1.80GHz        | 1        | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 21       | 20.19%  |
| Intel Core i5          | 18       | 17.31%  |
| Intel Core i3          | 12       | 11.54%  |
| Intel Xeon             | 8        | 7.69%   |
| AMD Ryzen 5            | 8        | 7.69%   |
| AMD Ryzen 7            | 7        | 6.73%   |
| Intel Pentium          | 5        | 4.81%   |
| Intel Celeron          | 5        | 4.81%   |
| AMD Ryzen 9            | 3        | 2.88%   |
| AMD Phenom II X4       | 3        | 2.88%   |
| Other                  | 2        | 1.92%   |
| Intel Core i9          | 2        | 1.92%   |
| Intel Pentium Gold     | 1        | 0.96%   |
| Intel Pentium Dual     | 1        | 0.96%   |
| Intel Core 2 Quad      | 1        | 0.96%   |
| Intel Core 2 Extreme   | 1        | 0.96%   |
| AMD Ryzen Threadripper | 1        | 0.96%   |
| AMD Ryzen Embedded     | 1        | 0.96%   |
| AMD Phenom II X6       | 1        | 0.96%   |
| AMD FX                 | 1        | 0.96%   |
| AMD Athlon 64 X2       | 1        | 0.96%   |
| AMD A10                | 1        | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 41       | 39.42%  |
| 2      | 24       | 23.08%  |
| 8      | 14       | 13.46%  |
| 6      | 14       | 13.46%  |
| 12     | 6        | 5.77%   |
| 16     | 2        | 1.92%   |
| 24     | 1        | 0.96%   |
| 10     | 1        | 0.96%   |
| 3      | 1        | 0.96%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 99       | 96.12%  |
| 2      | 4        | 3.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 63       | 61.17%  |
| 1      | 40       | 38.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 103      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 18.69%  |
| 0x306c3    | 10       | 9.35%   |
| 0x206a7    | 7        | 6.54%   |
| 0x506e3    | 6        | 5.61%   |
| 0x906ed    | 5        | 4.67%   |
| 0x906ea    | 5        | 4.67%   |
| 0x306a9    | 5        | 4.67%   |
| 0xa0653    | 3        | 2.8%    |
| 0x906e9    | 3        | 2.8%    |
| 0x806e9    | 3        | 2.8%    |
| 0x40651    | 3        | 2.8%    |
| 0x0a50000c | 3        | 2.8%    |
| 0x0a201009 | 3        | 2.8%    |
| 0x0800820d | 3        | 2.8%    |
| 0x306e4    | 2        | 1.87%   |
| 0x206c2    | 2        | 1.87%   |
| 0x20652    | 2        | 1.87%   |
| 0x08701021 | 2        | 1.87%   |
| 0x08701013 | 2        | 1.87%   |
| 0x010000c8 | 2        | 1.87%   |
| 0xa0671    | 1        | 0.93%   |
| 0xa0655    | 1        | 0.93%   |
| 0x90672    | 1        | 0.93%   |
| 0x706a1    | 1        | 0.93%   |
| 0x6fd      | 1        | 0.93%   |
| 0x20655    | 1        | 0.93%   |
| 0x106e5    | 1        | 0.93%   |
| 0x10677    | 1        | 0.93%   |
| 0x0a201016 | 1        | 0.93%   |
| 0x08108109 | 1        | 0.93%   |
| 0x0810100b | 1        | 0.93%   |
| 0x08001137 | 1        | 0.93%   |
| 0x06003106 | 1        | 0.93%   |
| 0x06000852 | 1        | 0.93%   |
| 0x010000dc | 1        | 0.93%   |
| 0x010000db | 1        | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 18       | 17.31%  |
| Haswell       | 15       | 14.42%  |
| Skylake       | 9        | 8.65%   |
| SandyBridge   | 8        | 7.69%   |
| IvyBridge     | 8        | 7.69%   |
| Zen 3         | 7        | 6.73%   |
| Zen 2         | 7        | 6.73%   |
| Westmere      | 6        | 5.77%   |
| CometLake     | 6        | 5.77%   |
| Zen+          | 4        | 3.85%   |
| K10           | 4        | 3.85%   |
| Zen           | 2        | 1.92%   |
| Core          | 2        | 1.92%   |
| Steamroller   | 1        | 0.96%   |
| Piledriver    | 1        | 0.96%   |
| Penryn        | 1        | 0.96%   |
| Nehalem       | 1        | 0.96%   |
| K8 Hammer     | 1        | 0.96%   |
| Icelake       | 1        | 0.96%   |
| Goldmont plus | 1        | 0.96%   |
| Unknown       | 1        | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 47       | 41.59%  |
| Intel             | 41       | 36.28%  |
| AMD               | 24       | 21.24%  |
| ASPEED Technology | 1        | 0.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 5.26%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 5.26%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 4        | 3.51%   |
| Intel HD Graphics 530                                                       | 4        | 3.51%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 3.51%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 3        | 2.63%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 2.63%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 2.63%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 2.63%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 2.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.63%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3        | 2.63%   |
| AMD Cezanne                                                                 | 3        | 2.63%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.75%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.75%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.75%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.75%   |
| Intel HD Graphics 620                                                       | 2        | 1.75%   |
| Intel HD Graphics 610                                                       | 2        | 1.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.75%   |
| AMD RS780 [Radeon HD 3200]                                                  | 2        | 1.75%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.75%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.75%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.88%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.88%   |
| Nvidia GT200GL [Quadro FX 5800]                                             | 1        | 0.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.88%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.88%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.88%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.88%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.88%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 0.88%   |
| Nvidia GF108 [GeForce GT 620]                                               | 1        | 0.88%   |
| Nvidia GF108 [GeForce GT 520]                                               | 1        | 0.88%   |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 0.88%   |
| Nvidia GF106 [GeForce GT 440]                                               | 1        | 0.88%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 0.88%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.88%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 1        | 0.88%   |
| Nvidia G80GL [Quadro FX 4600]                                               | 1        | 0.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 0.88%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                        | 1        | 0.88%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 0.88%   |
| Intel HD Graphics 510                                                       | 1        | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 0.88%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 0.88%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 0.88%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 0.88%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 0.88%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 0.88%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 1        | 0.88%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 1        | 0.88%   |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 0.88%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 0.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 0.88%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 0.88%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 43       | 41.35%  |
| 1 x Intel      | 35       | 33.65%  |
| 1 x AMD        | 21       | 20.19%  |
| Intel + Nvidia | 2        | 1.92%   |
| AMD + Nvidia   | 2        | 1.92%   |
| 1 x ASPEED     | 1        | 0.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 73       | 70.19%  |
| Proprietary | 25       | 24.04%  |
| Unknown     | 6        | 5.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 48       | 44.86%  |
| 0.51-1.0   | 14       | 13.08%  |
| 7.01-8.0   | 12       | 11.21%  |
| 1.01-2.0   | 11       | 10.28%  |
| 3.01-4.0   | 8        | 7.48%   |
| 0.01-0.5   | 6        | 5.61%   |
| 5.01-6.0   | 3        | 2.8%    |
| 2.01-3.0   | 2        | 1.87%   |
| 8.01-16.0  | 2        | 1.87%   |
| 16.01-24.0 | 1        | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 12.04%  |
| Goldstar             | 13       | 12.04%  |
| Philips              | 10       | 9.26%   |
| AOC                  | 9        | 8.33%   |
| Dell                 | 8        | 7.41%   |
| AMO                  | 6        | 5.56%   |
| Unknown              | 5        | 4.63%   |
| Ancor Communications | 5        | 4.63%   |
| Acer                 | 5        | 4.63%   |
| BenQ                 | 4        | 3.7%    |
| Lenovo               | 3        | 2.78%   |
| ViewSonic            | 2        | 1.85%   |
| RTK                  | 2        | 1.85%   |
| Hewlett-Packard      | 2        | 1.85%   |
| AUS                  | 2        | 1.85%   |
| Xiaomi               | 1        | 0.93%   |
| Xiangye              | 1        | 0.93%   |
| Unknown (AAA)        | 1        | 0.93%   |
| Toshiba              | 1        | 0.93%   |
| TCT                  | 1        | 0.93%   |
| SKY                  | 1        | 0.93%   |
| SAC                  | 1        | 0.93%   |
| PDA                  | 1        | 0.93%   |
| Mi                   | 1        | 0.93%   |
| LYC                  | 1        | 0.93%   |
| LG Electronics       | 1        | 0.93%   |
| HPN                  | 1        | 0.93%   |
| Hitachi              | 1        | 0.93%   |
| GET                  | 1        | 0.93%   |
| GEN                  | 1        | 0.93%   |
| FST                  | 1        | 0.93%   |
| Founder              | 1        | 0.93%   |
| Eizo                 | 1        | 0.93%   |
| ASUSTek Computer     | 1        | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| AMO HS241P AMO2800 2560x1440 620x349mm 28.0-inch                      | 4        | 3.57%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 3        | 2.68%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch               | 2        | 1.79%   |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch              | 2        | 1.79%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 2        | 1.79%   |
| Xiaomi Mi TV XMD004A 1920x1080 1110x620mm 50.1-inch                   | 1        | 0.89%   |
| Xiangye XE2400 XYE2380 3840x2160 520x310mm 23.8-inch                  | 1        | 0.89%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch              | 1        | 0.89%   |
| ViewSonic VA1616wSERIES VSC0021 1366x768 348x197mm 15.7-inch          | 1        | 0.89%   |
| Unknown LCD Monitor hp f1523 1024x768                                 | 1        | 0.89%   |
| Unknown LCD Monitor FST V22T-1R LED 1920x1080                         | 1        | 0.89%   |
| Unknown (AAA) U270 AAA2700 3840x2160 596x335mm 26.9-inch              | 1        | 0.89%   |
| Toshiba TV TSB2634 1920x1080 697x392mm 31.5-inch                      | 1        | 0.89%   |
| TCT DP1080P60 TCT0270 2560x1600 520x290mm 23.4-inch                   | 1        | 0.89%   |
| SKY M16U1 SKY0156 3840x2160 345x194mm 15.6-inch                       | 1        | 0.89%   |
| Samsung Electronics SyncMaster SAM01D4 1440x900 410x260mm 19.1-inch   | 1        | 0.89%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch     | 1        | 0.89%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 520x290mm 23.4-inch     | 1        | 0.89%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1        | 0.89%   |
| Samsung Electronics S22C650 SAM09DB 1920x1080 477x268mm 21.5-inch     | 1        | 0.89%   |
| Samsung Electronics S22C300 SAM0A1F 1920x1080 477x268mm 21.5-inch     | 1        | 0.89%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1        | 0.89%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 480x270mm 21.7-inch | 1        | 0.89%   |
| Samsung Electronics LCD Monitor SAM03DD 1680x1050                     | 1        | 0.89%   |
| Samsung Electronics LCD Monitor S27B550 1920x1080                     | 1        | 0.89%   |
| Samsung Electronics LCD Monitor S24D300 3840x1080                     | 1        | 0.89%   |
| Samsung Electronics LCD Monitor S22F350 1920x1080                     | 1        | 0.89%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch    | 1        | 0.89%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1        | 0.89%   |
| SAC HDMI SAC2400 2560x1440 527x296mm 23.8-inch                        | 1        | 0.89%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                     | 1        | 0.89%   |
| RTK C-FORCE RTK2A3B 1920x1080 531x299mm 24.0-inch                     | 1        | 0.89%   |
| Philips PHL 345E2 PHLC237 3440x1440 800x335mm 34.1-inch               | 1        | 0.89%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch               | 1        | 0.89%   |
| Philips PHL 234E5 PHLC0C7 1920x1080 510x290mm 23.1-inch               | 1        | 0.89%   |
| Philips PHL 224E5 PHLC0C6 1920x1080 476x268mm 21.5-inch               | 1        | 0.89%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch               | 1        | 0.89%   |
| Philips LCD Monitor PHL0850 1680x1050 470x300mm 22.0-inch             | 1        | 0.89%   |
| Philips 190V4 PHLC0B0 1440x900 408x255mm 18.9-inch                    | 1        | 0.89%   |
| Philips 190E PHLC031 1440x900 408x255mm 18.9-inch                     | 1        | 0.89%   |
| PDA P24FA2 PDA2380 1920x1080 409x230mm 18.5-inch                      | 1        | 0.89%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 1        | 0.89%   |
| LYC L2106 LYC0001 1920x1080 476x268mm 21.5-inch                       | 1        | 0.89%   |
| LG Electronics LCD Monitor LG HDR WFHD 2560x1080                      | 1        | 0.89%   |
| Lenovo LEN L27i-28 LEN65E0 1920x1080 598x336mm 27.0-inch              | 1        | 0.89%   |
| HPN LCD Monitor HP 24o                                                | 1        | 0.89%   |
| Hitachi HDMI HEC0030 1920x1080 580x330mm 26.3-inch                    | 1        | 0.89%   |
| Hewlett-Packard 32 Display HPN351A 1920x1080 698x393mm 31.5-inch      | 1        | 0.89%   |
| Hewlett-Packard 24o HPN337C 1920x1080 531x299mm 24.0-inch             | 1        | 0.89%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 1        | 0.89%   |
| Goldstar QHD GSM772A 2560x1440 697x392mm 31.5-inch                    | 1        | 0.89%   |
| Goldstar M198WA GSM4B35 1440x900 408x255mm 18.9-inch                  | 1        | 0.89%   |
| Goldstar L196WTQ GSM4B50 1440x900 408x255mm 18.9-inch                 | 1        | 0.89%   |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch               | 1        | 0.89%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 1        | 0.89%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1        | 0.89%   |
| Goldstar E2350 GSM5791 1920x1080 510x290mm 23.1-inch                  | 1        | 0.89%   |
| Goldstar D2743 GSM58EE 1920x1080 597x336mm 27.0-inch                  | 1        | 0.89%   |
| Goldstar C222W GSM5705 1680x1050 474x296mm 22.0-inch                  | 1        | 0.89%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 1        | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 43       | 41.75%  |
| 3840x2160 (4K)     | 14       | 13.59%  |
| 2560x1440 (QHD)    | 11       | 10.68%  |
| 1440x900 (WXGA+)   | 6        | 5.83%   |
| 1366x768 (WXGA)    | 5        | 4.85%   |
| 1680x1050 (WSXGA+) | 4        | 3.88%   |
| 3840x1080          | 3        | 2.91%   |
| 1360x768           | 3        | 2.91%   |
| Unknown            | 3        | 2.91%   |
| 3440x1440          | 2        | 1.94%   |
| 2560x1080          | 2        | 1.94%   |
| 1280x1024 (SXGA)   | 2        | 1.94%   |
| 1024x768 (XGA)     | 2        | 1.94%   |
| 5120x1440          | 1        | 0.97%   |
| 2560x1600          | 1        | 0.97%   |
| 1920x1200 (WUXGA)  | 1        | 0.97%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 14       | 13.33%  |
| 23      | 14       | 13.33%  |
| Unknown | 14       | 13.33%  |
| 21      | 12       | 11.43%  |
| 24      | 10       | 9.52%   |
| 31      | 8        | 7.62%   |
| 18      | 7        | 6.67%   |
| 28      | 5        | 4.76%   |
| 34      | 3        | 2.86%   |
| 22      | 3        | 2.86%   |
| 19      | 3        | 2.86%   |
| 15      | 3        | 2.86%   |
| 84      | 1        | 0.95%   |
| 65      | 1        | 0.95%   |
| 48      | 1        | 0.95%   |
| 46      | 1        | 0.95%   |
| 40      | 1        | 0.95%   |
| 26      | 1        | 0.95%   |
| 25      | 1        | 0.95%   |
| 17      | 1        | 0.95%   |
| 16      | 1        | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 38       | 37.25%  |
| 401-500     | 24       | 23.53%  |
| Unknown     | 14       | 13.73%  |
| 601-700     | 13       | 12.75%  |
| 301-350     | 5        | 4.9%    |
| 701-800     | 3        | 2.94%   |
| 1001-1500   | 3        | 2.94%   |
| 801-900     | 1        | 0.98%   |
| 1501-2000   | 1        | 0.98%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 65       | 65.66%  |
| 16/10   | 14       | 14.14%  |
| Unknown | 13       | 13.13%  |
| 21/9    | 3        | 3.03%   |
| 6/5     | 2        | 2.02%   |
| 4/3     | 1        | 1.01%   |
| 32/9    | 1        | 1.01%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 32       | 31.07%  |
| 301-350        | 20       | 19.42%  |
| Unknown        | 14       | 13.59%  |
| 351-500        | 11       | 10.68%  |
| 151-200        | 9        | 8.74%   |
| 141-150        | 5        | 4.85%   |
| 251-300        | 3        | 2.91%   |
| 101-110        | 3        | 2.91%   |
| 501-1000       | 3        | 2.91%   |
| More than 1000 | 2        | 1.94%   |
| 131-140        | 1        | 0.97%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 55       | 54.46%  |
| 101-120       | 21       | 20.79%  |
| Unknown       | 14       | 13.86%  |
| 161-240       | 5        | 4.95%   |
| 1-50          | 3        | 2.97%   |
| 121-160       | 2        | 1.98%   |
| More than 240 | 1        | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 84       | 81.55%  |
| 2     | 13       | 12.62%  |
| 0     | 6        | 5.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Realtek Semiconductor  | 58       | 40%     |
| Intel                  | 57       | 39.31%  |
| TP-Link                | 7        | 4.83%   |
| Broadcom               | 6        | 4.14%   |
| Qualcomm Atheros       | 5        | 3.45%   |
| Ralink Technology      | 3        | 2.07%   |
| MediaTek               | 2        | 1.38%   |
| SEGGER                 | 1        | 0.69%   |
| PEAK-System Technik    | 1        | 0.69%   |
| Nvidia                 | 1        | 0.69%   |
| National Semiconductor | 1        | 0.69%   |
| Microsoft              | 1        | 0.69%   |
| D-Link                 | 1        | 0.69%   |
| Belkin Components      | 1        | 0.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49       | 28%     |
| Intel Wi-Fi 6 AX200                                               | 10       | 5.71%   |
| Intel I211 Gigabit Network Connection                             | 9        | 5.14%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6        | 3.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 2.29%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.71%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.71%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.14%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 1.14%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2        | 1.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.14%   |
| Realtek 802.11ac NIC                                              | 2        | 1.14%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.14%   |
| Intel Wireless 8265 / 8275                                        | 2        | 1.14%   |
| Intel Wireless 7265                                               | 2        | 1.14%   |
| Intel Wireless 7260                                               | 2        | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 1.14%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.14%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2        | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.14%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                             | 1        | 0.57%   |
| TP-Link Archer T4U ver.3                                          | 1        | 0.57%   |
| TP-Link 802.11n NIC                                               | 1        | 0.57%   |
| SEGGER J-Link Pro OB                                              | 1        | 0.57%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.57%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 1        | 0.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.57%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.57%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 0.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.57%   |
| PEAK-System Technik Network controller                            | 1        | 0.57%   |
| Nvidia MCP65 Ethernet                                             | 1        | 0.57%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1        | 0.57%   |
| Microsoft XBOX ACC                                                | 1        | 0.57%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                | 1        | 0.57%   |
| MediaTek 802.11 n WLAN                                            | 1        | 0.57%   |
| Intel Wireless-AC 9260                                            | 1        | 0.57%   |
| Intel Wireless 3160                                               | 1        | 0.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1        | 0.57%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.57%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.57%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.57%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.57%   |
| Intel Centrino Wireless-N 2230                                    | 1        | 0.57%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1        | 0.57%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 1        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 34       | 56.67%  |
| TP-Link               | 7        | 11.67%  |
| Realtek Semiconductor | 7        | 11.67%  |
| Ralink Technology     | 3        | 5%      |
| Broadcom              | 3        | 5%      |
| Qualcomm Atheros      | 2        | 3.33%   |
| MediaTek              | 2        | 3.33%   |
| Microsoft             | 1        | 1.67%   |
| Belkin Components     | 1        | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 10       | 16.67%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 6        | 10%     |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 3.33%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2        | 3.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2        | 3.33%   |
| Realtek 802.11ac NIC                                                   | 2        | 3.33%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 3.33%   |
| Intel Wireless 8265 / 8275                                             | 2        | 3.33%   |
| Intel Wireless 7265                                                    | 2        | 3.33%   |
| Intel Wireless 7260                                                    | 2        | 3.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 2        | 3.33%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2        | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 3.33%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                  | 1        | 1.67%   |
| TP-Link Archer T4U ver.3                                               | 1        | 1.67%   |
| TP-Link 802.11n NIC                                                    | 1        | 1.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.67%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)              | 1        | 1.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 1.67%   |
| Ralink RT5370 Wireless Adapter                                         | 1        | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1        | 1.67%   |
| Microsoft XBOX ACC                                                     | 1        | 1.67%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                     | 1        | 1.67%   |
| MediaTek 802.11 n WLAN                                                 | 1        | 1.67%   |
| Intel Wireless-AC 9260                                                 | 1        | 1.67%   |
| Intel Wireless 3160                                                    | 1        | 1.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 1        | 1.67%   |
| Intel Centrino Wireless-N 2230                                         | 1        | 1.67%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 1        | 1.67%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 1        | 1.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 1        | 1.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 1        | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                          | 1        | 1.67%   |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870] | 1        | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Realtek Semiconductor  | 58       | 54.21%  |
| Intel                  | 40       | 37.38%  |
| Qualcomm Atheros       | 3        | 2.8%    |
| Broadcom               | 3        | 2.8%    |
| Nvidia                 | 1        | 0.93%   |
| National Semiconductor | 1        | 0.93%   |
| D-Link                 | 1        | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49       | 43.36%  |
| Intel I211 Gigabit Network Connection                             | 9        | 7.96%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 6.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 3.54%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.65%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 2.65%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 2.65%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2        | 1.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.77%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.77%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.77%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.77%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.88%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.88%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.88%   |
| Nvidia MCP65 Ethernet                                             | 1        | 0.88%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1        | 0.88%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.88%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.88%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.88%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.88%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.88%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.88%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.88%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.88%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1        | 0.88%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.88%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.B1) [ASIX AX88772]      | 1        | 0.88%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.88%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1        | 0.88%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 101      | 64.33%  |
| WiFi     | 54       | 34.39%  |
| Modem    | 1        | 0.64%   |
| Unknown  | 1        | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 86       | 74.78%  |
| WiFi     | 29       | 25.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 55       | 51.89%  |
| 2     | 44       | 41.51%  |
| 3     | 2        | 1.89%   |
| 0     | 2        | 1.89%   |
| 8     | 1        | 0.94%   |
| 7     | 1        | 0.94%   |
| 4     | 1        | 0.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 102      | 98.08%  |
| Yes  | 2        | 1.92%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 32       | 57.14%  |
| Cambridge Silicon Radio         | 14       | 25%     |
| Realtek Semiconductor           | 2        | 3.57%   |
| Broadcom                        | 2        | 3.57%   |
| ASUSTek Computer                | 2        | 3.57%   |
| SINO WEALTH                     | 1        | 1.79%   |
| Qualcomm Atheros Communications | 1        | 1.79%   |
| Lite-On Technology              | 1        | 1.79%   |
| Apple                           | 1        | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14       | 25%     |
| Intel AX200 Bluetooth                               | 10       | 17.86%  |
| Intel Bluetooth wireless interface                  | 7        | 12.5%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6        | 10.71%  |
| Intel Bluetooth Device                              | 3        | 5.36%   |
| Realtek Bluetooth Radio                             | 2        | 3.57%   |
| Intel AX210 Bluetooth                               | 2        | 3.57%   |
| ASUS Bluetooth Radio                                | 2        | 3.57%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1        | 1.79%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 1.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 1.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1        | 1.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.79%   |
| Broadcom Bluetooth Controller                       | 1        | 1.79%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.79%   |
| Apple Bluetooth USB Host Controller                 | 1        | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 75       | 43.86%  |
| Nvidia                               | 45       | 26.32%  |
| AMD                                  | 32       | 18.71%  |
| C-Media Electronics                  | 8        | 4.68%   |
| Focusrite-Novation                   | 2        | 1.17%   |
| Creative Labs                        | 2        | 1.17%   |
| XMOS                                 | 1        | 0.58%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.58%   |
| Sony                                 | 1        | 0.58%   |
| Lynx                                 | 1        | 0.58%   |
| Logitech                             | 1        | 0.58%   |
| HiFimeDIY Audio                      | 1        | 0.58%   |
| AudioQuest                           | 1        | 0.58%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 11       | 5.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10       | 5%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 9        | 4.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7        | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 7        | 3.5%    |
| Intel Cannon Lake PCH cAVS                                                        | 6        | 3%      |
| Intel 200 Series PCH HD Audio                                                     | 6        | 3%      |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5        | 2.5%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 5        | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 2.5%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 4        | 2%      |
| Nvidia GF108 High Definition Audio Controller                                     | 4        | 2%      |
| Intel Comet Lake PCH-V cAVS                                                       | 4        | 2%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4        | 2%      |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 2%      |
| Nvidia TU106 High Definition Audio Controller                                     | 3        | 1.5%    |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 1.5%    |
| Nvidia GP104 High Definition Audio Controller                                     | 3        | 1.5%    |
| Nvidia GM206 High Definition Audio Controller                                     | 3        | 1.5%    |
| Intel Sunrise Point-LP HD Audio                                                   | 3        | 1.5%    |
| Intel Haswell-ULT HD Audio Controller                                             | 3        | 1.5%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 1.5%    |
| Intel 8 Series HD Audio Controller                                                | 3        | 1.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 3        | 1.5%    |
| AMD Navi 10 HDMI Audio                                                            | 3        | 1.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 1.5%    |
| Nvidia TU104 HD Audio Controller                                                  | 2        | 1%      |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 1%      |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 1%      |
| Nvidia GF106 High Definition Audio Controller                                     | 2        | 1%      |
| Intel Comet Lake PCH cAVS                                                         | 2        | 1%      |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 2        | 1%      |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 2        | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 1%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 1%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 1%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1%      |
| XMOS X1S USB DAC                                                                  | 1        | 0.5%    |
| Thesycon Systemsoftware & Consulting SMSL USB AUDIO                               | 1        | 0.5%    |
| Sony Wireless Controller                                                          | 1        | 0.5%    |
| Nvidia MCP65 High Definition Audio                                                | 1        | 0.5%    |
| Nvidia GP102 HDMI Audio Controller                                                | 1        | 0.5%    |
| Nvidia GK106 HDMI Audio Controller                                                | 1        | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 0.5%    |
| Nvidia GF116 High Definition Audio Controller                                     | 1        | 0.5%    |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 0.5%    |
| Nvidia GA102 High Definition Audio Controller                                     | 1        | 0.5%    |
| Lynx Hilo                                                                         | 1        | 0.5%    |
| Logitech Headset H340                                                             | 1        | 0.5%    |
| Intel USB PnP Sound Device                                                        | 1        | 0.5%    |
| Intel UNA USB audio                                                               | 1        | 0.5%    |
| Intel Tiger Lake-H HD Audio Controller                                            | 1        | 0.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1        | 0.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 0.5%    |
| Intel C610/X99 series chipset HD Audio Controller                                 | 1        | 0.5%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 18       | 30%     |
| Corsair             | 8        | 13.33%  |
| A-DATA Technology   | 7        | 11.67%  |
| Samsung Electronics | 6        | 10%     |
| Unknown             | 4        | 6.67%   |
| SK hynix            | 3        | 5%      |
| Crucial             | 3        | 5%      |
| Ramaxel Technology  | 2        | 3.33%   |
| Transcend           | 1        | 1.67%   |
| Team                | 1        | 1.67%   |
| Micron Technology   | 1        | 1.67%   |
| Kingmax             | 1        | 1.67%   |
| Juhor               | 1        | 1.67%   |
| GLOWAY              | 1        | 1.67%   |
| G.Skill             | 1        | 1.67%   |
| Apacer              | 1        | 1.67%   |
| Unknown             | 1        | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KY7N41-MIE 8192MB DIMM DDR4 2666MT/s        | 2        | 3.03%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s      | 2        | 3.03%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s | 2        | 3.03%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 1.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 1.52%   |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s              | 1        | 1.52%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                   | 1        | 1.52%   |
| Transcend RAM TS256MLQ72V6U 2048MB DIMM DDR2 667MT/s     | 1        | 1.52%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s       | 1        | 1.52%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s               | 1        | 1.52%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s               | 1        | 1.52%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s     | 1        | 1.52%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s   | 1        | 1.52%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s    | 1        | 1.52%   |
| Samsung RAM M471B1G73DH0-YK0 8GB SODIMM DDR3 1600MT/s    | 1        | 1.52%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s    | 1        | 1.52%   |
| Samsung RAM M471A1G43EB1-CPB 8192MB SODIMM DDR4 2133MT/s | 1        | 1.52%   |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 1.52%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s      | 1        | 1.52%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1866MT/s   | 1        | 1.52%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 1.52%   |
| Ramaxel RAM RMR5040MM58F9F1600 4096MB DIMM DDR3 1600MT/s | 1        | 1.52%   |
| Ramaxel RAM RMR1870ED48E8F1333 2048MB DIMM DDR3 1333MT/s | 1        | 1.52%   |
| Micron RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s    | 1        | 1.52%   |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s           | 1        | 1.52%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 1        | 1.52%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s      | 1        | 1.52%   |
| Kingston RAM HX426C16FB/8 8GB DIMM DDR4 2667MT/s         | 1        | 1.52%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s  | 1        | 1.52%   |
| Kingston RAM 99U5469-041.A00LF 4GB SODIMM DDR3 1600MT/s  | 1        | 1.52%   |
| Kingston RAM 99P5471-017.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.52%   |
| Kingston RAM 9905744-011.A00G 32GB SODIMM DDR4 2667MT/s  | 1        | 1.52%   |
| Kingston RAM 9905702-136.A00G 8GB DIMM DDR4 2667MT/s     | 1        | 1.52%   |
| Kingston RAM 9905702-120.A00G 8GB DIMM DDR4 2667MT/s     | 1        | 1.52%   |
| Kingston RAM 9905701-143.A00G 16384MB DIMM DDR4 2666MT/s | 1        | 1.52%   |
| Kingston RAM 9905701-132.A00G 16384MB DIMM DDR4 2667MT/s | 1        | 1.52%   |
| Kingston RAM 9905678-026.A00G 8192MB DIMM DDR4 2400MT/s  | 1        | 1.52%   |
| Kingston RAM 9905625-066.A00G 16GB DIMM DDR4 2667MT/s    | 1        | 1.52%   |
| Kingston RAM 9905471-006.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 1.52%   |
| Kingston RAM 9905403-02X.B00LF 4GB DIMM DDR3 1600MT/s    | 1        | 1.52%   |
| Kingmax RAM GLLG42F-DA--------- 8GB DIMM DDR4 2400MT/s   | 1        | 1.52%   |
| Juhor RAM JHD2666U1916JG 16384MB DIMM DDR4 2667MT/s      | 1        | 1.52%   |
| GLOWAY RAM TYA4U2666D19161C 16GB DIMM DDR4 2667MT/s      | 1        | 1.52%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 1        | 1.52%   |
| Crucial RAM CT8G4DFS832A.M8FJ 8GB DIMM DDR4 3200MT/s     | 1        | 1.52%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 3000MT/s     | 1        | 1.52%   |
| Crucial RAM CT8G4DFS824A.C8FBD1 8GB DIMM DDR4 3000MT/s   | 1        | 1.52%   |
| Crucial RAM BL16G32C16U4BL.M16FE 16GB DIMM DDR4 3200MT/s | 1        | 1.52%   |
| Corsair RAM CMZ16GX3M2A1600C9 8192MB DIMM DDR3 1600MT/s  | 1        | 1.52%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s   | 1        | 1.52%   |
| Corsair RAM CMK64GX4M2D3000C16 32GB DIMM DDR4 3000MT/s   | 1        | 1.52%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s    | 1        | 1.52%   |
| Corsair RAM CM4X8GE2400C16K4 8192MB DIMM DDR4 2400MT/s   | 1        | 1.52%   |
| Corsair RAM CM4X16GC3200C16K2E 16GB DIMM DDR4 3200MT/s   | 1        | 1.52%   |
| Apacer RAM 78.B2GCN.9K00C 4GB SODIMM DDR3 1600MT/s       | 1        | 1.52%   |
| A-DATA RAM Module 8192MB DIMM DDR4 2667MT/s              | 1        | 1.52%   |
| A-DATA RAM Module 4GB DIMM DDR4 2400MT/s                 | 1        | 1.52%   |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 1.52%   |
| A-DATA RAM Module 16384MB DIMM DDR4 2667MT/s             | 1        | 1.52%   |
| A-DATA RAM DDR4 3600 16GB DIMM DDR4 3800MT/s             | 1        | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 35       | 64.81%  |
| DDR3    | 14       | 25.93%  |
| SDRAM   | 2        | 3.7%    |
| DDR2    | 2        | 3.7%    |
| Unknown | 1        | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 46       | 85.19%  |
| SODIMM | 8        | 14.81%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 18       | 31.58%  |
| 16384 | 15       | 26.32%  |
| 4096  | 13       | 22.81%  |
| 2048  | 6        | 10.53%  |
| 32768 | 4        | 7.02%   |
| 1024  | 1        | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2667  | 10       | 17.24%  |
| 1600  | 9        | 15.52%  |
| 3200  | 8        | 13.79%  |
| 2400  | 5        | 8.62%   |
| 1333  | 5        | 8.62%   |
| 3466  | 3        | 5.17%   |
| 2666  | 3        | 5.17%   |
| 2133  | 3        | 5.17%   |
| 3600  | 2        | 3.45%   |
| 3000  | 2        | 3.45%   |
| 800   | 2        | 3.45%   |
| 4199  | 1        | 1.72%   |
| 3800  | 1        | 1.72%   |
| 3400  | 1        | 1.72%   |
| 3007  | 1        | 1.72%   |
| 1866  | 1        | 1.72%   |
| 667   | 1        | 1.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 1        | 25%     |
| Fuji Xerox         | 1        | 25%     |
| Canon              | 1        | 25%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP LaserJet P2035           | 1        | 25%     |
| Fuji Xerox DocuPrint P158 b | 1        | 25%     |
| Canon MP160                 | 1        | 25%     |
| Brother HL-L2320D series    | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Mustek Systems | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 5        | 38.46%  |
| Microdia            | 2        | 15.38%  |
| SN0002              | 1        | 7.69%   |
| Nokia Mobile Phones | 1        | 7.69%   |
| Google              | 1        | 7.69%   |
| Essential Products  | 1        | 7.69%   |
| eMPIA Technology    | 1        | 7.69%   |
| Cubeternet          | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 2        | 14.29%  |
| Logitech B525 HD Webcam                 | 2        | 14.29%  |
| SN0002 HIK 2K Camera                    | 1        | 7.14%   |
| Nokia Mobile Phones Lumia 640 Phone     | 1        | 7.14%   |
| Microdia Rapoo camera                   | 1        | 7.14%   |
| Microdia HP Webcam-101                  | 1        | 7.14%   |
| Logitech BRIO Ultra HD Webcam           | 1        | 7.14%   |
| Google Nexus/Pixel Device (MTP + debug) | 1        | 7.14%   |
| Google Nexus 4/5 (PTP + debug)          | 1        | 7.14%   |
| Essential Products PH-1                 | 1        | 7.14%   |
| eMPIA M035 Compact Web Cam              | 1        | 7.14%   |
| Cubeternet GL-UPC822 UVC WebCam         | 1        | 7.14%   |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Yubico.com            | 1        | 50%     |
| Advanced Card Systems | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Yubico.com Yubikey 4/5 U2F+CCID              | 1        | 50%     |
| Advanced Card Systems ACR1281 1S Dual Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 83       | 77.57%  |
| 1     | 20       | 18.69%  |
| 4     | 2        | 1.87%   |
| 2     | 2        | 1.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 10       | 31.25%  |
| Graphics card            | 8        | 25%     |
| Communication controller | 6        | 18.75%  |
| Unassigned class         | 2        | 6.25%   |
| Storage/ata              | 1        | 3.13%   |
| Sound                    | 1        | 3.13%   |
| Net/ethernet             | 1        | 3.13%   |
| Chipcard                 | 1        | 3.13%   |
| Camera                   | 1        | 3.13%   |
| Bluetooth                | 1        | 3.13%   |

