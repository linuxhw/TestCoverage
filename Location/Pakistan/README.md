Linux in Pakistan - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Pakistan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Pakistan/Desktop/README.md) and [notebooks](/Location/Pakistan/Notebook/README.md).

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

Total: 335

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Sony      | VPCEA26FG                   | Notebook    | [b72a4de42b](https://linux-hardware.org/?probe=b72a4de42b) | Jul 01, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TD0... | Notebook    | [18fbe5a2d0](https://linux-hardware.org/?probe=18fbe5a2d0) | Jun 28, 2022 |
| HP        | EliteBook 8470p             | Notebook    | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Gigabyte  | A520M S2H                   | Desktop     | [094c3f1e98](https://linux-hardware.org/?probe=094c3f1e98) | Jun 24, 2022 |
| HP        | 339A                        | Desktop     | [a20191b759](https://linux-hardware.org/?probe=a20191b759) | Jun 23, 2022 |
| HP        | EliteBook 8470p             | Notebook    | [f9895656b6](https://linux-hardware.org/?probe=f9895656b6) | Jun 23, 2022 |
| HP        | EliteBook 8470p             | Notebook    | [2e2bcb63d7](https://linux-hardware.org/?probe=2e2bcb63d7) | Jun 23, 2022 |
| HP        | 18E7                        | Desktop     | [f2d50ba3c2](https://linux-hardware.org/?probe=f2d50ba3c2) | Jun 13, 2022 |
| HP        | EliteBook 850 G5            | Notebook    | [085f5c458d](https://linux-hardware.org/?probe=085f5c458d) | Jun 10, 2022 |
| HP        | Laptop 15s-fq2xxx           | Notebook    | [5bcb742cbe](https://linux-hardware.org/?probe=5bcb742cbe) | Jun 04, 2022 |
| Lenovo    | ThinkPad T450 20BV0005US    | Notebook    | [a795ed872f](https://linux-hardware.org/?probe=a795ed872f) | Jun 03, 2022 |
| ASUSTek   | STRIX B250H GAMING          | Desktop     | [9f28088790](https://linux-hardware.org/?probe=9f28088790) | Jun 01, 2022 |
| HP        | EliteBook 8460p             | Notebook    | [a9cca9972f](https://linux-hardware.org/?probe=a9cca9972f) | May 31, 2022 |
| HP        | EliteBook 8460p             | Notebook    | [f05323c723](https://linux-hardware.org/?probe=f05323c723) | May 31, 2022 |
| Dell      | Inspiron 3543               | Notebook    | [c48c32ae19](https://linux-hardware.org/?probe=c48c32ae19) | May 25, 2022 |
| HP        | Notebook                    | Notebook    | [4508e41795](https://linux-hardware.org/?probe=4508e41795) | May 22, 2022 |
| HP        | Notebook                    | Notebook    | [dc587c572e](https://linux-hardware.org/?probe=dc587c572e) | May 22, 2022 |
| HP        | 1495                        | Desktop     | [9ec1730693](https://linux-hardware.org/?probe=9ec1730693) | May 11, 2022 |
| Lenovo    | SDK0E50510 WIN              | Desktop     | [07526b3b20](https://linux-hardware.org/?probe=07526b3b20) | May 10, 2022 |
| Dell      | Latitude 3330               | Notebook    | [4f05d8475c](https://linux-hardware.org/?probe=4f05d8475c) | May 08, 2022 |
| Dell      | Latitude E6420              | Notebook    | [8c12f58910](https://linux-hardware.org/?probe=8c12f58910) | May 01, 2022 |
| HP        | 3396                        | Desktop     | [bd2e5eb69c](https://linux-hardware.org/?probe=bd2e5eb69c) | Apr 29, 2022 |
| HP        | 3396                        | Desktop     | [705baf56a1](https://linux-hardware.org/?probe=705baf56a1) | Apr 29, 2022 |
| HP        | EliteBook 840 G1            | Notebook    | [411c79850c](https://linux-hardware.org/?probe=411c79850c) | Apr 29, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | Notebook    | [59a49b2d04](https://linux-hardware.org/?probe=59a49b2d04) | Apr 23, 2022 |
| HP        | EliteBook 840 G2            | Notebook    | [3e0d410668](https://linux-hardware.org/?probe=3e0d410668) | Apr 19, 2022 |
| HP        | 3396                        | Desktop     | [2c07ec89d4](https://linux-hardware.org/?probe=2c07ec89d4) | Apr 17, 2022 |
| HP        | ProBook 450 G8 Notebook ... | Notebook    | [1974bfe63a](https://linux-hardware.org/?probe=1974bfe63a) | Apr 15, 2022 |
| Dell      | Latitude 3520               | Notebook    | [ee204b07aa](https://linux-hardware.org/?probe=ee204b07aa) | Apr 11, 2022 |
| HP        | Pavilion TS 11              | Notebook    | [9a817f6695](https://linux-hardware.org/?probe=9a817f6695) | Apr 09, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | Notebook    | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| HP        | 87D6 SMVB                   | Desktop     | [57d44d9705](https://linux-hardware.org/?probe=57d44d9705) | Apr 03, 2022 |
| HP        | 87D6 SMVB                   | Desktop     | [e70c6e6d89](https://linux-hardware.org/?probe=e70c6e6d89) | Apr 03, 2022 |
| Dell      | Latitude 7480               | Notebook    | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TD0... | Notebook    | [1936ee53b3](https://linux-hardware.org/?probe=1936ee53b3) | Mar 22, 2022 |
| Dell      | Latitude 7480               | Notebook    | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Lenovo    | V110-15IKB 80TH             | Notebook    | [a3aeef468a](https://linux-hardware.org/?probe=a3aeef468a) | Mar 12, 2022 |
| Dell      | 0HR330                      | Desktop     | [9e351420b6](https://linux-hardware.org/?probe=9e351420b6) | Mar 04, 2022 |
| Gigabyte  | A520M S2H                   | Desktop     | [06db14c491](https://linux-hardware.org/?probe=06db14c491) | Mar 01, 2022 |
| Dell      | 0HR330                      | Desktop     | [7e4c13a9bd](https://linux-hardware.org/?probe=7e4c13a9bd) | Mar 01, 2022 |
| Dell      | 0HR330                      | Desktop     | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell      | 0HR330                      | Desktop     | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e0169c3e87](https://linux-hardware.org/?probe=e0169c3e87) | Feb 23, 2022 |
| HP        | EliteBook Folio 9470m       | Notebook    | [1aa838368f](https://linux-hardware.org/?probe=1aa838368f) | Feb 20, 2022 |
| HP        | EliteBook Folio 9470m       | Notebook    | [8f3df927df](https://linux-hardware.org/?probe=8f3df927df) | Feb 18, 2022 |
| HP        | 8717                        | Desktop     | [d5d2ee0ab5](https://linux-hardware.org/?probe=d5d2ee0ab5) | Feb 18, 2022 |
| Dell      | Inspiron 3501               | Notebook    | [7fdd5b66fc](https://linux-hardware.org/?probe=7fdd5b66fc) | Feb 14, 2022 |
| Lenovo    | IdeaPad 510-15ISK 80SR      | Notebook    | [a5407aa128](https://linux-hardware.org/?probe=a5407aa128) | Feb 13, 2022 |
| Dell      | Inspiron 5547               | Notebook    | [2d6ff07a82](https://linux-hardware.org/?probe=2d6ff07a82) | Feb 12, 2022 |
| Dell      | Inspiron 3501               | Notebook    | [0dd77f2f7a](https://linux-hardware.org/?probe=0dd77f2f7a) | Feb 12, 2022 |
| HP        | 8061                        | Desktop     | [f721051d60](https://linux-hardware.org/?probe=f721051d60) | Feb 11, 2022 |
| HP        | 8717                        | Desktop     | [97d99714a1](https://linux-hardware.org/?probe=97d99714a1) | Feb 10, 2022 |
| Lenovo    | ThinkPad E15 Gen 2 20TDS... | Notebook    | [5a9a256568](https://linux-hardware.org/?probe=5a9a256568) | Feb 01, 2022 |
| Dell      | Inspiron 3501               | Notebook    | [4a0c4a62b7](https://linux-hardware.org/?probe=4a0c4a62b7) | Feb 01, 2022 |
| Dell      | Inspiron 3501               | Notebook    | [c902cc42a6](https://linux-hardware.org/?probe=c902cc42a6) | Jan 18, 2022 |
| Dell      | 0DR845                      | Desktop     | [daa833f06d](https://linux-hardware.org/?probe=daa833f06d) | Jan 08, 2022 |
| Dell      | Inspiron 3501               | Notebook    | [ce839c3628](https://linux-hardware.org/?probe=ce839c3628) | Jan 08, 2022 |
| Lenovo    | ThinkPad T540p 20BFS5630... | Notebook    | [e1e090d622](https://linux-hardware.org/?probe=e1e090d622) | Jan 02, 2022 |
| HP        | Pavilion Laptop 15-cs0xx... | Notebook    | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| HP        | EliteBook Folio 9470m       | Notebook    | [90d57a20ee](https://linux-hardware.org/?probe=90d57a20ee) | Dec 31, 2021 |
| HP        | EliteBook Folio 9470m       | Notebook    | [4db624e8a0](https://linux-hardware.org/?probe=4db624e8a0) | Dec 31, 2021 |
| HP        | EliteBook Folio 9470m       | Notebook    | [b79e118712](https://linux-hardware.org/?probe=b79e118712) | Dec 31, 2021 |
| HP        | ProLiant DL360 G7           | Server      | [70e6bfadc4](https://linux-hardware.org/?probe=70e6bfadc4) | Dec 26, 2021 |
| Acer      | Aspire ES1-411              | Notebook    | [9a5ebb6379](https://linux-hardware.org/?probe=9a5ebb6379) | Dec 19, 2021 |
| HP        | EliteBook 8470p             | Notebook    | [0f7389c7d9](https://linux-hardware.org/?probe=0f7389c7d9) | Dec 14, 2021 |
| Dell      | Inspiron 5515               | Notebook    | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell      | Inspiron 5515               | Notebook    | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| HP        | 0B3Ch HP P/N                | Desktop     | [2805378159](https://linux-hardware.org/?probe=2805378159) | Dec 10, 2021 |
| HP        | ZBook 15 G3                 | Notebook    | [e662c8b956](https://linux-hardware.org/?probe=e662c8b956) | Dec 07, 2021 |
| Lenovo    | ThinkStation D30 4223CC9    | Desktop     | [0784c5596b](https://linux-hardware.org/?probe=0784c5596b) | Dec 04, 2021 |
| Dell      | 0VHRW1 A03                  | Desktop     | [ebfaaee6ef](https://linux-hardware.org/?probe=ebfaaee6ef) | Dec 04, 2021 |
| Lenovo    | ThinkStation D30 4223CC9    | Desktop     | [50a026d588](https://linux-hardware.org/?probe=50a026d588) | Dec 02, 2021 |
| Dell      | 0VHRW1 A03                  | Desktop     | [19fd4c2057](https://linux-hardware.org/?probe=19fd4c2057) | Nov 30, 2021 |
| Lenovo    | ThinkStation D30 4223CC9    | Desktop     | [7493408721](https://linux-hardware.org/?probe=7493408721) | Nov 29, 2021 |
| Dell      | 0VHRW1 A03                  | Desktop     | [637bba1c58](https://linux-hardware.org/?probe=637bba1c58) | Nov 29, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [555032936f](https://linux-hardware.org/?probe=555032936f) | Nov 28, 2021 |
| Dell      | Inspiron 15 7000 Gaming     | Notebook    | [538c96bb62](https://linux-hardware.org/?probe=538c96bb62) | Nov 26, 2021 |
| Dell      | Latitude E6440              | Notebook    | [e0e5edfc03](https://linux-hardware.org/?probe=e0e5edfc03) | Nov 24, 2021 |
| HP        | Unknown                     | Notebook    | [ef28d45f68](https://linux-hardware.org/?probe=ef28d45f68) | Nov 23, 2021 |
| Dell      | G3 3579                     | Notebook    | [38e9f54ba1](https://linux-hardware.org/?probe=38e9f54ba1) | Nov 23, 2021 |
| Dell      | Inspiron 5520               | Notebook    | [6c6e631ffc](https://linux-hardware.org/?probe=6c6e631ffc) | Nov 20, 2021 |
| HP        | Unknown                     | Notebook    | [23dc38032d](https://linux-hardware.org/?probe=23dc38032d) | Nov 20, 2021 |
| Shuttle   | FS81                        | Desktop     | [ac6138c9d7](https://linux-hardware.org/?probe=ac6138c9d7) | Nov 19, 2021 |
| Shuttle   | FS81                        | Desktop     | [d889090212](https://linux-hardware.org/?probe=d889090212) | Nov 18, 2021 |
| Dell      | Inspiron 15 7000 Gaming     | Notebook    | [cd386145b8](https://linux-hardware.org/?probe=cd386145b8) | Nov 18, 2021 |
| HP        | Pavilion Laptop 14-ce2xx... | Notebook    | [f9ebb771b0](https://linux-hardware.org/?probe=f9ebb771b0) | Nov 14, 2021 |
| HP        | ZBook 15 G3                 | Notebook    | [67e5184b17](https://linux-hardware.org/?probe=67e5184b17) | Nov 13, 2021 |
| Dell      | Vostro 1500                 | Notebook    | [23aeb68ca2](https://linux-hardware.org/?probe=23aeb68ca2) | Nov 11, 2021 |
| HP        | 0AECh D                     | Desktop     | [7d8a81315d](https://linux-hardware.org/?probe=7d8a81315d) | Nov 11, 2021 |
| HP        | ZBook 15 G3                 | Notebook    | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [72f1028535](https://linux-hardware.org/?probe=72f1028535) | Nov 09, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [e43d36b3cf](https://linux-hardware.org/?probe=e43d36b3cf) | Nov 09, 2021 |
| Dell      | Inspiron 3501               | Notebook    | [5d35bd9e4a](https://linux-hardware.org/?probe=5d35bd9e4a) | Nov 07, 2021 |
| Dell      | Inspiron 15-3567            | Notebook    | [630a9144f1](https://linux-hardware.org/?probe=630a9144f1) | Nov 06, 2021 |
| ASUSTek   | PRIME B550-PLUS             | Desktop     | [98ddca21d9](https://linux-hardware.org/?probe=98ddca21d9) | Nov 06, 2021 |
| HP        | 0AECh D                     | Desktop     | [cd2f6268cf](https://linux-hardware.org/?probe=cd2f6268cf) | Oct 28, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [2f188b606a](https://linux-hardware.org/?probe=2f188b606a) | Oct 25, 2021 |
| HP        | 650                         | Notebook    | [c32592cabb](https://linux-hardware.org/?probe=c32592cabb) | Oct 20, 2021 |
| Apple     | MacBookPro14,1              | Notebook    | [bb1aa448fd](https://linux-hardware.org/?probe=bb1aa448fd) | Oct 20, 2021 |
| HP        | ProBook 450 G7              | Notebook    | [a47cdaa2ba](https://linux-hardware.org/?probe=a47cdaa2ba) | Oct 20, 2021 |
| Dell      | 0XPDFK A01                  | Desktop     | [0e66d5fd62](https://linux-hardware.org/?probe=0e66d5fd62) | Oct 16, 2021 |
| Lenovo    | ThinkBook 15-IIL 20SM       | Notebook    | [c7fc550482](https://linux-hardware.org/?probe=c7fc550482) | Oct 16, 2021 |
| HP        | ProBook 450 G7              | Notebook    | [f2a84de135](https://linux-hardware.org/?probe=f2a84de135) | Oct 12, 2021 |
| Dell      | Latitude E5570              | Notebook    | [938d1a781d](https://linux-hardware.org/?probe=938d1a781d) | Oct 08, 2021 |
| Lenovo    | ThinkPad X220 Tablet 429... | Notebook    | [33137c7c23](https://linux-hardware.org/?probe=33137c7c23) | Oct 07, 2021 |
| HP        | 0AECh D                     | Desktop     | [415146d6ec](https://linux-hardware.org/?probe=415146d6ec) | Oct 07, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [06efedbf24](https://linux-hardware.org/?probe=06efedbf24) | Oct 07, 2021 |
| Lenovo    | ThinkBook 15 G2 ITL 20VE    | Notebook    | [196fa579f8](https://linux-hardware.org/?probe=196fa579f8) | Oct 04, 2021 |
| Haier     | Y11C                        | Notebook    | [74b9ee5509](https://linux-hardware.org/?probe=74b9ee5509) | Oct 03, 2021 |
| Dell      | Precision M6400             | Notebook    | [5f6ec9333e](https://linux-hardware.org/?probe=5f6ec9333e) | Oct 03, 2021 |
| Haier     | Y11C                        | Notebook    | [591740bf00](https://linux-hardware.org/?probe=591740bf00) | Sep 27, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [029b85826d](https://linux-hardware.org/?probe=029b85826d) | Sep 27, 2021 |
| Dell      | Inspiron 5515               | Notebook    | [64af4c4882](https://linux-hardware.org/?probe=64af4c4882) | Sep 24, 2021 |
| HP        | 0AECh D                     | Desktop     | [202ada3fc3](https://linux-hardware.org/?probe=202ada3fc3) | Sep 23, 2021 |
| HP        | 3047h                       | Desktop     | [356ad972a7](https://linux-hardware.org/?probe=356ad972a7) | Sep 22, 2021 |
| Lenovo    | ThinkPad X220 Tablet 429... | Notebook    | [d0e2e19e84](https://linux-hardware.org/?probe=d0e2e19e84) | Sep 12, 2021 |
| HP        | 1587h                       | Desktop     | [5447d2e6c3](https://linux-hardware.org/?probe=5447d2e6c3) | Sep 12, 2021 |
| Unknown   | Unknown                     | Desktop     | [321a93dff9](https://linux-hardware.org/?probe=321a93dff9) | Sep 07, 2021 |
| Shuttle   | FS81                        | Desktop     | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| HP        | ProLiant DL380p Gen8        | Server      | [c5c3b2d36c](https://linux-hardware.org/?probe=c5c3b2d36c) | Sep 02, 2021 |
| HP        | ProLiant DL380p Gen8        | Server      | [ece6c14756](https://linux-hardware.org/?probe=ece6c14756) | Sep 02, 2021 |
| HP        | ProLiant DL380p Gen8        | Server      | [262cc4f3e7](https://linux-hardware.org/?probe=262cc4f3e7) | Aug 29, 2021 |
| Dell      | 09KPNV A01                  | Desktop     | [7e939d9f5f](https://linux-hardware.org/?probe=7e939d9f5f) | Aug 20, 2021 |
| ASUSTek   | VivoBook_ASUSLaptop X571... | Notebook    | [966a09526a](https://linux-hardware.org/?probe=966a09526a) | Aug 14, 2021 |
| Dell      | Inspiron 3542               | Notebook    | [0909599e9c](https://linux-hardware.org/?probe=0909599e9c) | Aug 11, 2021 |
| Dell      | Inspiron 5570               | Notebook    | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| Dell      | Inspiron 5593               | Notebook    | [1f6017347e](https://linux-hardware.org/?probe=1f6017347e) | Aug 05, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [921bde522e](https://linux-hardware.org/?probe=921bde522e) | Jul 31, 2021 |
| Dell      | Latitude E5250              | Notebook    | [f50f84a6a3](https://linux-hardware.org/?probe=f50f84a6a3) | Jul 26, 2021 |
| Gigabyte  | Z590 UD AC                  | Desktop     | [7e8e35538a](https://linux-hardware.org/?probe=7e8e35538a) | Jul 26, 2021 |
| Dell      | Latitude E5250              | Notebook    | [9806ab15ab](https://linux-hardware.org/?probe=9806ab15ab) | Jul 25, 2021 |
| Dell      | Latitude E5250              | Notebook    | [9a475d76a4](https://linux-hardware.org/?probe=9a475d76a4) | Jul 25, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [00614fd705](https://linux-hardware.org/?probe=00614fd705) | Jul 23, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [37924533d9](https://linux-hardware.org/?probe=37924533d9) | Jul 23, 2021 |
| Gigabyte  | Z590 UD AC                  | Desktop     | [4fc5079d7e](https://linux-hardware.org/?probe=4fc5079d7e) | Jul 20, 2021 |
| Dell      | Latitude E5250              | Notebook    | [d65621a003](https://linux-hardware.org/?probe=d65621a003) | Jul 16, 2021 |
| HP        | EliteBook 8440p             | Notebook    | [d89b69a6a3](https://linux-hardware.org/?probe=d89b69a6a3) | Jul 16, 2021 |
| Lenovo    | ThinkCentre M70e 0830F2U    | Desktop     | [8dad962f2f](https://linux-hardware.org/?probe=8dad962f2f) | Jul 09, 2021 |
| Dell      | Inspiron 15 7000 Gaming     | Notebook    | [d320594f42](https://linux-hardware.org/?probe=d320594f42) | Jul 07, 2021 |
| Lenovo    | ThinkPad E14 20RA007SAD     | Notebook    | [eb51ce8f36](https://linux-hardware.org/?probe=eb51ce8f36) | Jul 07, 2021 |
| Dell      | Inspiron 7306 2n1           | Convertible | [f4d326f499](https://linux-hardware.org/?probe=f4d326f499) | Jul 05, 2021 |
| Dell      | Precision 5530              | Notebook    | [7d267375f2](https://linux-hardware.org/?probe=7d267375f2) | Jul 05, 2021 |
| Dell      | Inspiron 7306 2n1           | Convertible | [7236dc0c95](https://linux-hardware.org/?probe=7236dc0c95) | Jul 04, 2021 |
| Dell      | Inspiron 5593               | Notebook    | [926e72bc56](https://linux-hardware.org/?probe=926e72bc56) | Jul 03, 2021 |
| HP        | Pavilion Notebook           | Notebook    | [f5ac8e2aca](https://linux-hardware.org/?probe=f5ac8e2aca) | Jun 25, 2021 |
| HP        | Pavilion dv6                | Notebook    | [c3529dc2aa](https://linux-hardware.org/?probe=c3529dc2aa) | Jun 24, 2021 |
| Dell      | Precision M6400             | Notebook    | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| HP        | 158A                        | Desktop     | [1da50908cf](https://linux-hardware.org/?probe=1da50908cf) | Jun 10, 2021 |
| Dell      | Latitude 3510               | Notebook    | [79c73e5595](https://linux-hardware.org/?probe=79c73e5595) | Jun 09, 2021 |
| Toshiba   | Satellite L850              | Notebook    | [6beced18da](https://linux-hardware.org/?probe=6beced18da) | May 23, 2021 |
| Dell      | Vostro 14-3468              | Notebook    | [1742ee5823](https://linux-hardware.org/?probe=1742ee5823) | May 21, 2021 |
| Dell      | 042P49 A00                  | Desktop     | [2d9b300bd3](https://linux-hardware.org/?probe=2d9b300bd3) | May 13, 2021 |
| Dell      | Latitude E5250              | Notebook    | [8c3b8c27c8](https://linux-hardware.org/?probe=8c3b8c27c8) | May 10, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [5a9b9278df](https://linux-hardware.org/?probe=5a9b9278df) | Apr 26, 2021 |
| Dell      | 06FW8P A01                  | Desktop     | [08f4c825cc](https://linux-hardware.org/?probe=08f4c825cc) | Apr 25, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [3423651b5d](https://linux-hardware.org/?probe=3423651b5d) | Apr 23, 2021 |
| Dell      | 0VHRW1 A03                  | Desktop     | [bc7c3f8c4d](https://linux-hardware.org/?probe=bc7c3f8c4d) | Apr 23, 2021 |
| Lenovo    | ThinkStation D30 4223CC9    | Desktop     | [8d7a62ce1a](https://linux-hardware.org/?probe=8d7a62ce1a) | Apr 20, 2021 |
| Dell      | 06FW8P A02                  | Desktop     | [583acd1f2e](https://linux-hardware.org/?probe=583acd1f2e) | Apr 20, 2021 |
| Dell      | 06FW8P A01                  | Desktop     | [a0b4b692ff](https://linux-hardware.org/?probe=a0b4b692ff) | Apr 20, 2021 |
| Shuttle   | FS81                        | Desktop     | [14e78cfe43](https://linux-hardware.org/?probe=14e78cfe43) | Apr 20, 2021 |
| Dell      | Latitude E6420              | Notebook    | [6e3288ca3a](https://linux-hardware.org/?probe=6e3288ca3a) | Apr 11, 2021 |
| Dell      | Inspiron 17-7779            | Notebook    | [2cf1f86b67](https://linux-hardware.org/?probe=2cf1f86b67) | Apr 06, 2021 |
| Gigabyte  | AERO 15-SA                  | Notebook    | [b162082414](https://linux-hardware.org/?probe=b162082414) | Apr 03, 2021 |
| Gigabyte  | AERO 15-SA                  | Notebook    | [536dfb993f](https://linux-hardware.org/?probe=536dfb993f) | Mar 28, 2021 |
| Dell      | Latitude 3510               | Notebook    | [1ef27c1786](https://linux-hardware.org/?probe=1ef27c1786) | Mar 25, 2021 |
| ASUSTek   | PN61                        | Mini pc     | [45389ef622](https://linux-hardware.org/?probe=45389ef622) | Mar 24, 2021 |
| HP        | EliteBook 2170p             | Notebook    | [eba311c4d7](https://linux-hardware.org/?probe=eba311c4d7) | Mar 22, 2021 |
| HP        | EliteBook 2170p             | Notebook    | [e506fc315e](https://linux-hardware.org/?probe=e506fc315e) | Mar 21, 2021 |
| Dell      | 0GU083 A00                  | Desktop     | [03e87a4ada](https://linux-hardware.org/?probe=03e87a4ada) | Mar 20, 2021 |
| Lenovo    | IdeaPad L340-15IWL 81LG     | Notebook    | [eb713030d2](https://linux-hardware.org/?probe=eb713030d2) | Mar 18, 2021 |
| Dell      | Latitude E6420              | Notebook    | [a062baeb24](https://linux-hardware.org/?probe=a062baeb24) | Mar 12, 2021 |
| Dell      | 0C27VV A01                  | Desktop     | [2ab353f0c6](https://linux-hardware.org/?probe=2ab353f0c6) | Mar 06, 2021 |
| HP        | EliteBook 850 G7 Noteboo... | Notebook    | [6dbe550700](https://linux-hardware.org/?probe=6dbe550700) | Feb 28, 2021 |
| Lenovo    | MAHOBAY NOK                 | Desktop     | [67ea005277](https://linux-hardware.org/?probe=67ea005277) | Feb 24, 2021 |
| HP        | EliteBook 840 G3            | Notebook    | [b8a8ea9182](https://linux-hardware.org/?probe=b8a8ea9182) | Feb 24, 2021 |
| HP        | EliteBook 840 G3            | Notebook    | [ce415da689](https://linux-hardware.org/?probe=ce415da689) | Feb 23, 2021 |
| ASUSTek   | TUF Gaming FA706IU_FA706... | Notebook    | [64c73f58bb](https://linux-hardware.org/?probe=64c73f58bb) | Feb 22, 2021 |
| Lenovo    | ThinkBook 15-IIL 20SM       | Notebook    | [0426a1c07e](https://linux-hardware.org/?probe=0426a1c07e) | Feb 20, 2021 |
| Lenovo    | MAHOBAY 31900003 STD        | Desktop     | [845f5a30c2](https://linux-hardware.org/?probe=845f5a30c2) | Feb 13, 2021 |
| HP        | 14                          | Notebook    | [d5382b721f](https://linux-hardware.org/?probe=d5382b721f) | Feb 11, 2021 |
| Toshiba   | Satellite S50t-B            | Notebook    | [2fe86bc977](https://linux-hardware.org/?probe=2fe86bc977) | Feb 06, 2021 |
| Toshiba   | Satellite S50t-B            | Notebook    | [ec72426035](https://linux-hardware.org/?probe=ec72426035) | Feb 05, 2021 |
| Toshiba   | Satellite S50t-B            | Notebook    | [f7709c05cb](https://linux-hardware.org/?probe=f7709c05cb) | Feb 05, 2021 |
| HP        | 14                          | Notebook    | [f27a999e26](https://linux-hardware.org/?probe=f27a999e26) | Feb 03, 2021 |
| Sony      | SVE15126CXS                 | Notebook    | [8a27b129a3](https://linux-hardware.org/?probe=8a27b129a3) | Feb 02, 2021 |
| Apple     | MacBookPro16,2              | Notebook    | [e3790fd911](https://linux-hardware.org/?probe=e3790fd911) | Jan 31, 2021 |
| Apple     | MacBookPro16,2              | Notebook    | [0ee13de953](https://linux-hardware.org/?probe=0ee13de953) | Jan 31, 2021 |
| Lenovo    | ThinkPad E15 20RD0088UE     | Notebook    | [d2bfe04a2b](https://linux-hardware.org/?probe=d2bfe04a2b) | Jan 28, 2021 |
| Lenovo    | ThinkCentre M58 7373C51     | Desktop     | [3e79476403](https://linux-hardware.org/?probe=3e79476403) | Jan 27, 2021 |
| HP        | ProBook 450 G5              | Notebook    | [e4b829fff8](https://linux-hardware.org/?probe=e4b829fff8) | Jan 26, 2021 |
| HP        | ProBook 450 G2              | Notebook    | [7db1cae3c0](https://linux-hardware.org/?probe=7db1cae3c0) | Jan 25, 2021 |
| HP        | ProBook 450 G5              | Notebook    | [0421fbf0d1](https://linux-hardware.org/?probe=0421fbf0d1) | Jan 25, 2021 |
| Lenovo    | ThinkPad T460 20FMS39800    | Notebook    | [7b4f78f648](https://linux-hardware.org/?probe=7b4f78f648) | Jan 10, 2021 |
| HP        | 3047h                       | Desktop     | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| HP        | ENVY x360 m6 Convertible    | Convertible | [c3c2bbd2bc](https://linux-hardware.org/?probe=c3c2bbd2bc) | Jan 06, 2021 |
| Dell      | Inspiron 7391 2n1           | Convertible | [01da85c434](https://linux-hardware.org/?probe=01da85c434) | Dec 25, 2020 |
| Dell      | Inspiron 7391 2n1           | Convertible | [597b76daa1](https://linux-hardware.org/?probe=597b76daa1) | Dec 25, 2020 |
| Dell      | Latitude E6510              | Notebook    | [2557f813e4](https://linux-hardware.org/?probe=2557f813e4) | Dec 15, 2020 |
| Dell      | Inspiron 15 7000 Gaming     | Notebook    | [b04b3b207e](https://linux-hardware.org/?probe=b04b3b207e) | Dec 11, 2020 |
| Fujitsu   | LIFEBOOK E752               | Notebook    | [252afde67a](https://linux-hardware.org/?probe=252afde67a) | Dec 08, 2020 |
| Lenovo    | ThinkBook 15-IML 20RW       | Notebook    | [f84c7affac](https://linux-hardware.org/?probe=f84c7affac) | Dec 07, 2020 |
| Dell      | Latitude E7440              | Notebook    | [0d04075b3e](https://linux-hardware.org/?probe=0d04075b3e) | Dec 03, 2020 |
| Lenovo    | ThinkPad W500 40612HU       | Notebook    | [06465bf227](https://linux-hardware.org/?probe=06465bf227) | Dec 01, 2020 |
| Lenovo    | ThinkPad T60 1951WAT        | Notebook    | [4da418a597](https://linux-hardware.org/?probe=4da418a597) | Nov 28, 2020 |
| Dell      | Latitude E7450              | Notebook    | [20ee05f0fa](https://linux-hardware.org/?probe=20ee05f0fa) | Nov 27, 2020 |
| Dell      | Latitude E7440              | Notebook    | [9627b61c6f](https://linux-hardware.org/?probe=9627b61c6f) | Nov 25, 2020 |
| Dell      | Latitude E7450              | Notebook    | [e9a83f5dc5](https://linux-hardware.org/?probe=e9a83f5dc5) | Nov 24, 2020 |
| HP        | 3047h                       | Desktop     | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| HP        | EliteBook 2540p             | Notebook    | [00a011fa83](https://linux-hardware.org/?probe=00a011fa83) | Nov 22, 2020 |
| HP        | EliteBook 2540p             | Notebook    | [12f4630385](https://linux-hardware.org/?probe=12f4630385) | Nov 22, 2020 |
| Microsoft | Surface Pro 3               | Tablet      | [eb17673652](https://linux-hardware.org/?probe=eb17673652) | Nov 21, 2020 |
| Lenovo    | ThinkPad E560 20EV0010UK    | Notebook    | [a52f064714](https://linux-hardware.org/?probe=a52f064714) | Nov 19, 2020 |
| Dell      | Inspiron 5567               | Notebook    | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| HP        | 650                         | Notebook    | [67e06d1514](https://linux-hardware.org/?probe=67e06d1514) | Nov 09, 2020 |
| HP        | Pavilion g6                 | Notebook    | [98124ff6a4](https://linux-hardware.org/?probe=98124ff6a4) | Nov 08, 2020 |
| HP        | EliteBook 8470p             | Notebook    | [847807840d](https://linux-hardware.org/?probe=847807840d) | Nov 05, 2020 |
| HP        | ProBook 6560b               | Notebook    | [934ffc99e6](https://linux-hardware.org/?probe=934ffc99e6) | Oct 30, 2020 |
| Dell      | 07N90W A01                  | Desktop     | [127c1a4946](https://linux-hardware.org/?probe=127c1a4946) | Oct 29, 2020 |
| Dell      | Inspiron 15-3567            | Notebook    | [2b138e461a](https://linux-hardware.org/?probe=2b138e461a) | Oct 26, 2020 |
| Dell      | Inspiron 15-3567            | Notebook    | [4460c27fd7](https://linux-hardware.org/?probe=4460c27fd7) | Oct 26, 2020 |
| Dell      | Inspiron 15-3567            | Notebook    | [b647bae107](https://linux-hardware.org/?probe=b647bae107) | Oct 24, 2020 |
| Apple     | MacBookAir6,2               | Notebook    | [3509d2f6e3](https://linux-hardware.org/?probe=3509d2f6e3) | Oct 22, 2020 |
| Toshiba   | PORTEGE Z30-B               | Notebook    | [d7c9922a29](https://linux-hardware.org/?probe=d7c9922a29) | Oct 21, 2020 |
| HP        | ProBook 4340s               | Notebook    | [3db4ff09f4](https://linux-hardware.org/?probe=3db4ff09f4) | Oct 18, 2020 |
| Dell      | Latitude E6540              | Notebook    | [36688dde6e](https://linux-hardware.org/?probe=36688dde6e) | Oct 06, 2020 |
| HP        | 650                         | Notebook    | [1ea9bf783e](https://linux-hardware.org/?probe=1ea9bf783e) | Oct 03, 2020 |
| HP        | ProBook 450 G5              | Notebook    | [94eb24ff74](https://linux-hardware.org/?probe=94eb24ff74) | Oct 02, 2020 |
| Dell      | Latitude E4300              | Notebook    | [12b944fb30](https://linux-hardware.org/?probe=12b944fb30) | Oct 02, 2020 |
| HP        | ProBook 450 G5              | Notebook    | [cb2cef5fcf](https://linux-hardware.org/?probe=cb2cef5fcf) | Oct 01, 2020 |
| Lenovo    | ThinkPad T440p 20AWS0DU0... | Notebook    | [caf12cb57f](https://linux-hardware.org/?probe=caf12cb57f) | Sep 30, 2020 |
| Lenovo    | ThinkPad T440p 20AWS0DU0... | Notebook    | [d3cc62a7f5](https://linux-hardware.org/?probe=d3cc62a7f5) | Sep 30, 2020 |
| Dell      | Latitude E7450              | Notebook    | [7df34be11f](https://linux-hardware.org/?probe=7df34be11f) | Sep 29, 2020 |
| Dell      | Latitude E7450              | Notebook    | [8149a50311](https://linux-hardware.org/?probe=8149a50311) | Sep 29, 2020 |
| HP        | ENVY x360 m6 Convertible    | Convertible | [974d6d3289](https://linux-hardware.org/?probe=974d6d3289) | Sep 29, 2020 |
| Samsung   | QX311/QX411/QX412/QX511     | Notebook    | [b6f7494e44](https://linux-hardware.org/?probe=b6f7494e44) | Sep 21, 2020 |
| HP        | 650                         | Notebook    | [278a9afdeb](https://linux-hardware.org/?probe=278a9afdeb) | Sep 21, 2020 |
| Dell      | Vostro 14-3468              | Notebook    | [4ab76fd5c2](https://linux-hardware.org/?probe=4ab76fd5c2) | Sep 20, 2020 |
| HP        | 650                         | Notebook    | [8aaa8d7e4d](https://linux-hardware.org/?probe=8aaa8d7e4d) | Sep 19, 2020 |
| Samsung   | QX311/QX411/QX412/QX511     | Notebook    | [1ec83fe97e](https://linux-hardware.org/?probe=1ec83fe97e) | Sep 17, 2020 |
| HP        | EliteBook 840 G3            | Notebook    | [d6204bd9e2](https://linux-hardware.org/?probe=d6204bd9e2) | Sep 16, 2020 |
| HP        | ProBook 455 G7              | Notebook    | [d84e4c8838](https://linux-hardware.org/?probe=d84e4c8838) | Sep 13, 2020 |
| HP        | ENVY 17                     | Notebook    | [08285409ad](https://linux-hardware.org/?probe=08285409ad) | Sep 13, 2020 |
| HP        | ProBook 455 G7              | Notebook    | [290aad9d0d](https://linux-hardware.org/?probe=290aad9d0d) | Sep 12, 2020 |
| HP        | ENVY x360 m6 Convertible    | Convertible | [dd76cd9006](https://linux-hardware.org/?probe=dd76cd9006) | Sep 12, 2020 |
| HP        | ProBook 450 G7              | Notebook    | [85d0104e28](https://linux-hardware.org/?probe=85d0104e28) | Sep 10, 2020 |
| Dell      | Inspiron 15-3573            | Notebook    | [9be442a7dd](https://linux-hardware.org/?probe=9be442a7dd) | Sep 07, 2020 |
| HP        | 8433 11                     | Desktop     | [1d000792d8](https://linux-hardware.org/?probe=1d000792d8) | Sep 03, 2020 |
| HP        | ProBook 440 G7              | Notebook    | [1c4d1f875b](https://linux-hardware.org/?probe=1c4d1f875b) | Sep 01, 2020 |
| HP        | ProBook 4340s               | Notebook    | [f7580ed51b](https://linux-hardware.org/?probe=f7580ed51b) | Aug 31, 2020 |
| Dell      | 0D6H9T A01                  | Desktop     | [1f914ddd57](https://linux-hardware.org/?probe=1f914ddd57) | Aug 31, 2020 |
| Dell      | Latitude E7250              | Notebook    | [ff13c002c8](https://linux-hardware.org/?probe=ff13c002c8) | Aug 27, 2020 |
| HP        | EliteBook 820 G2            | Notebook    | [f35b20067d](https://linux-hardware.org/?probe=f35b20067d) | Aug 25, 2020 |
| Dell      | 0HY9JP A02                  | Desktop     | [19795140c8](https://linux-hardware.org/?probe=19795140c8) | Aug 22, 2020 |
| Dell      | 0HY9JP A02                  | Desktop     | [b739a3410a](https://linux-hardware.org/?probe=b739a3410a) | Aug 22, 2020 |
| HP        | Laptop 15-da2xxx            | Notebook    | [031606a1a9](https://linux-hardware.org/?probe=031606a1a9) | Aug 21, 2020 |
| Dell      | 0PP150 A00                  | Desktop     | [a990cf0ce7](https://linux-hardware.org/?probe=a990cf0ce7) | Aug 21, 2020 |
| Dell      | Latitude E7250              | Notebook    | [63024e0df6](https://linux-hardware.org/?probe=63024e0df6) | Aug 19, 2020 |
| HP        | ProBook 450 G7              | Notebook    | [8a5fc0bc23](https://linux-hardware.org/?probe=8a5fc0bc23) | Aug 13, 2020 |
| HP        | ProBook 440 G5              | Notebook    | [fa604583d6](https://linux-hardware.org/?probe=fa604583d6) | Aug 10, 2020 |
| HP        | ProBook 440 G5              | Notebook    | [255da50641](https://linux-hardware.org/?probe=255da50641) | Aug 10, 2020 |
| HP        | 0B4Ch D                     | Desktop     | [4053256264](https://linux-hardware.org/?probe=4053256264) | Aug 10, 2020 |
| Lenovo    | ThinkPad X201 3249CTO       | Notebook    | [930fbc43ed](https://linux-hardware.org/?probe=930fbc43ed) | Aug 09, 2020 |
| HP        | Pavilion Notebook           | Notebook    | [f62759a869](https://linux-hardware.org/?probe=f62759a869) | Aug 05, 2020 |
| Dell      | 0DR845                      | Desktop     | [e4ff6acb83](https://linux-hardware.org/?probe=e4ff6acb83) | Aug 01, 2020 |
| Dell      | 0DR845                      | Desktop     | [4b9fbd7a8f](https://linux-hardware.org/?probe=4b9fbd7a8f) | Aug 01, 2020 |
| Dell      | Inspiron 15-3567            | Notebook    | [4af4cdfef7](https://linux-hardware.org/?probe=4af4cdfef7) | Jul 30, 2020 |
| HP        | ProBook 440 G7              | Notebook    | [4b38ecdae9](https://linux-hardware.org/?probe=4b38ecdae9) | Jul 28, 2020 |
| HP        | EliteBook 840 G2            | Notebook    | [9dbea8590b](https://linux-hardware.org/?probe=9dbea8590b) | Jul 19, 2020 |
| HP        | ProBook 450 G7              | Notebook    | [45478d9106](https://linux-hardware.org/?probe=45478d9106) | Jul 18, 2020 |
| HP        | 1589                        | Desktop     | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| HP        | Pavilion x360 Convertibl... | Convertible | [8ce6e9cb36](https://linux-hardware.org/?probe=8ce6e9cb36) | Jul 10, 2020 |
| HP        | ProBook 470 G2              | Notebook    | [c42c686ae8](https://linux-hardware.org/?probe=c42c686ae8) | Jul 09, 2020 |
| MOTION    | NVX00                       | Notebook    | [fd07831802](https://linux-hardware.org/?probe=fd07831802) | Jul 04, 2020 |
| HP        | ProBook 450 G3              | Notebook    | [a12518d58c](https://linux-hardware.org/?probe=a12518d58c) | Jun 30, 2020 |
| Dell      | Latitude E6440              | Notebook    | [a7fe187945](https://linux-hardware.org/?probe=a7fe187945) | Jun 28, 2020 |
| Haier     | Y11C                        | Notebook    | [6b98c2c449](https://linux-hardware.org/?probe=6b98c2c449) | Jun 23, 2020 |
| Gigabyte  | B450M S2H                   | Desktop     | [4e6a9e5117](https://linux-hardware.org/?probe=4e6a9e5117) | Jun 12, 2020 |
| Lenovo    | ThinkPad X201 3249CTO       | Notebook    | [8c8ed3d489](https://linux-hardware.org/?probe=8c8ed3d489) | Jun 06, 2020 |
| Haier     | Y11C                        | Notebook    | [7f9f93809f](https://linux-hardware.org/?probe=7f9f93809f) | Jun 01, 2020 |
| Gigabyte  | B250M-D3H-CF                | Desktop     | [f74cf1545a](https://linux-hardware.org/?probe=f74cf1545a) | May 21, 2020 |
| Dell      | Latitude E6410              | Notebook    | [60757c8504](https://linux-hardware.org/?probe=60757c8504) | May 21, 2020 |
| Lenovo    | ThinkPad X201 3249CTO       | Notebook    | [86a1d31e5c](https://linux-hardware.org/?probe=86a1d31e5c) | May 21, 2020 |
| Dell      | Latitude E7450              | Notebook    | [1031b89b4b](https://linux-hardware.org/?probe=1031b89b4b) | May 12, 2020 |
| HP        | EliteBook Folio 1040 G1     | Notebook    | [34b0697bf6](https://linux-hardware.org/?probe=34b0697bf6) | May 10, 2020 |
| Dell      | Latitude E6320              | Notebook    | [cedc2c5001](https://linux-hardware.org/?probe=cedc2c5001) | May 10, 2020 |
| Dell      | 0GU083 A00                  | Desktop     | [a31c9c5f4f](https://linux-hardware.org/?probe=a31c9c5f4f) | May 05, 2020 |
| Gigabyte  | Z170X-Gaming 7              | Desktop     | [e3400fb2b7](https://linux-hardware.org/?probe=e3400fb2b7) | May 04, 2020 |
| Dell      | 0PP150 A00                  | Desktop     | [51f69f1430](https://linux-hardware.org/?probe=51f69f1430) | May 02, 2020 |
| Lenovo    | ThinkCentre M57 6072W2A     | Desktop     | [d42ad893b6](https://linux-hardware.org/?probe=d42ad893b6) | May 01, 2020 |
| Lenovo    | ThinkCentre M57 6072W2A     | Desktop     | [366d3d0483](https://linux-hardware.org/?probe=366d3d0483) | May 01, 2020 |
| Dell      | 0PP150 A00                  | Desktop     | [f224ee60e5](https://linux-hardware.org/?probe=f224ee60e5) | Apr 30, 2020 |
| Acer      | Aspire E5-576               | Notebook    | [581af37cda](https://linux-hardware.org/?probe=581af37cda) | Apr 19, 2020 |
| Dell      | Latitude E5420              | Notebook    | [6d2ddeb934](https://linux-hardware.org/?probe=6d2ddeb934) | Apr 18, 2020 |
| HP        | EliteBook 6930p             | Notebook    | [ea52c08646](https://linux-hardware.org/?probe=ea52c08646) | Apr 09, 2020 |
| Dell      | Latitude E4300              | Notebook    | [5e38d54ea2](https://linux-hardware.org/?probe=5e38d54ea2) | Mar 18, 2020 |
| Dell      | 0XPDFK A01                  | Desktop     | [9434f7214c](https://linux-hardware.org/?probe=9434f7214c) | Mar 16, 2020 |
| Dell      | 0XPDFK A01                  | Desktop     | [4a53b5e634](https://linux-hardware.org/?probe=4a53b5e634) | Mar 11, 2020 |
| HP        | EliteBook 8440p             | Notebook    | [cd13c97ddb](https://linux-hardware.org/?probe=cd13c97ddb) | Mar 11, 2020 |
| Lenovo    | ThinkBook 15-IML 20RW       | Notebook    | [3cd2a73254](https://linux-hardware.org/?probe=3cd2a73254) | Mar 09, 2020 |
| Dell      | 054KM3 A01                  | Desktop     | [857f976c7f](https://linux-hardware.org/?probe=857f976c7f) | Jan 29, 2020 |
| HP        | 1497                        | Desktop     | [fe24ec7591](https://linux-hardware.org/?probe=fe24ec7591) | Jan 28, 2020 |
| HP        | Pavilion dv7                | Notebook    | [c727a0fa74](https://linux-hardware.org/?probe=c727a0fa74) | Jan 27, 2020 |
| Dell      | 054KM3 A01                  | Desktop     | [f682ad8814](https://linux-hardware.org/?probe=f682ad8814) | Jan 21, 2020 |
| HP        | EliteBook 8470p             | Notebook    | [e257c71d0b](https://linux-hardware.org/?probe=e257c71d0b) | Jan 14, 2020 |
| HP        | ProBook 450 G3              | Notebook    | [f73167982a](https://linux-hardware.org/?probe=f73167982a) | Jan 01, 2020 |
| Acer      | Veriton X6620G v1.0         | Desktop     | [e921d3af77](https://linux-hardware.org/?probe=e921d3af77) | Dec 13, 2019 |
| Dell      | Inspiron 5567               | Notebook    | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| Dell      | Latitude XT3                | Notebook    | [4ccaa2e0e2](https://linux-hardware.org/?probe=4ccaa2e0e2) | Oct 29, 2019 |
| Lenovo    | ThinkPad T440 20B7S1NK05    | Notebook    | [310405c604](https://linux-hardware.org/?probe=310405c604) | Oct 29, 2019 |
| HP        | EliteBook 6930p             | Notebook    | [856fcded98](https://linux-hardware.org/?probe=856fcded98) | Oct 25, 2019 |
| HP        | Unknown                     | Notebook    | [25dd8af3ee](https://linux-hardware.org/?probe=25dd8af3ee) | Oct 22, 2019 |
| ASUSTek   | Q87M-E                      | Desktop     | [01f990ea56](https://linux-hardware.org/?probe=01f990ea56) | Oct 19, 2019 |
| Lenovo    | ThinkPad 10 20C3001QAU      | Tablet      | [b1cb7238da](https://linux-hardware.org/?probe=b1cb7238da) | Oct 04, 2019 |
| HP        | EliteBook 6930p             | Notebook    | [43c8f2b72c](https://linux-hardware.org/?probe=43c8f2b72c) | Sep 13, 2019 |
| HP        | EliteBook 6930p             | Notebook    | [964e933faf](https://linux-hardware.org/?probe=964e933faf) | Sep 13, 2019 |
| Samsung   | 940Z5L                      | Notebook    | [28c94787df](https://linux-hardware.org/?probe=28c94787df) | Sep 13, 2019 |
| AMI       | Unknown                     | Notebook    | [407590d103](https://linux-hardware.org/?probe=407590d103) | Sep 09, 2019 |
| HP        | ProBook 6470b               | Notebook    | [81e17acdb1](https://linux-hardware.org/?probe=81e17acdb1) | Aug 02, 2019 |
| HP        | EliteBook 840 G3            | Notebook    | [b419735d70](https://linux-hardware.org/?probe=b419735d70) | Jul 04, 2019 |
| Sony      | VPCCB490X                   | Notebook    | [ed39416136](https://linux-hardware.org/?probe=ed39416136) | Jun 22, 2019 |
| Haier     | Y11C                        | Notebook    | [ab6b2cf0e5](https://linux-hardware.org/?probe=ab6b2cf0e5) | Jun 20, 2019 |
| Haier     | Y11C                        | Notebook    | [74a3547ed6](https://linux-hardware.org/?probe=74a3547ed6) | Jun 20, 2019 |
| HP        | 304Ah                       | Desktop     | [4f72bfd1f5](https://linux-hardware.org/?probe=4f72bfd1f5) | May 13, 2019 |
| Dell      | Latitude E6420              | Notebook    | [c5063bb936](https://linux-hardware.org/?probe=c5063bb936) | May 12, 2019 |
| Dell      | Latitude E6420              | Notebook    | [9563d07d0a](https://linux-hardware.org/?probe=9563d07d0a) | May 12, 2019 |
| Haier     | Y11B                        | Notebook    | [d90f70d18f](https://linux-hardware.org/?probe=d90f70d18f) | May 11, 2019 |
| Dell      | 054KM3 A01                  | Desktop     | [144815a4e9](https://linux-hardware.org/?probe=144815a4e9) | Jan 15, 2019 |
| Dell      | 054KM3 A01                  | Desktop     | [f83bcddf2e](https://linux-hardware.org/?probe=f83bcddf2e) | Jan 08, 2019 |
| Dell      | 054KM3 A01                  | Desktop     | [404e699144](https://linux-hardware.org/?probe=404e699144) | Jan 08, 2019 |
| Haier     | Y11B                        | Notebook    | [e359a25a69](https://linux-hardware.org/?probe=e359a25a69) | Nov 18, 2018 |
| Haier     | Y11B                        | Notebook    | [13e5308d20](https://linux-hardware.org/?probe=13e5308d20) | Nov 18, 2018 |
| HP        | Pavilion Notebook           | Notebook    | [7e2949f7da](https://linux-hardware.org/?probe=7e2949f7da) | Nov 11, 2018 |
| Acer      | Aspire 5733                 | Notebook    | [970a40e3d0](https://linux-hardware.org/?probe=970a40e3d0) | Oct 23, 2018 |
| ASUSTek   | K53U                        | Notebook    | [f644624e98](https://linux-hardware.org/?probe=f644624e98) | Oct 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 79        | 31.85%  |
| Ubuntu 18.04        | 26        | 10.48%  |
| Debian 11           | 8         | 3.23%   |
| Arch                | 7         | 2.82%   |
| Ubuntu 22.04        | 6         | 2.42%   |
| Ubuntu 21.04        | 6         | 2.42%   |
| KDE neon 20.04      | 6         | 2.42%   |
| Debian 10           | 6         | 2.42%   |
| Zorin 15            | 5         | 2.02%   |
| Pop!_OS 20.04       | 5         | 2.02%   |
| OpenMandriva 4.3    | 5         | 2.02%   |
| Ubuntu 19.04        | 4         | 1.61%   |
| Pop!_OS 21.04       | 4         | 1.61%   |
| OpenMandriva 4.2    | 4         | 1.61%   |
| Linux Mint 20.2     | 4         | 1.61%   |
| Linux Mint 20       | 4         | 1.61%   |
| Ubuntu 21.10        | 3         | 1.21%   |
| Pop!_OS 20.10       | 3         | 1.21%   |
| Manjaro             | 3         | 1.21%   |
| Kubuntu 20.04       | 3         | 1.21%   |
| Fedora 34           | 3         | 1.21%   |
| Fedora 33           | 3         | 1.21%   |
| Zorin 16            | 2         | 0.81%   |
| Ubuntu 20.10        | 2         | 0.81%   |
| Ubuntu 16.04        | 2         | 0.81%   |
| Parrot 4.10         | 2         | 0.81%   |
| Linux Mint 20.3     | 2         | 0.81%   |
| Linux Mint 20.1     | 2         | 0.81%   |
| Linux Mint 19.3     | 2         | 0.81%   |
| Kali 2022.2         | 2         | 0.81%   |
| Elementary 6.1      | 2         | 0.81%   |
| CentOS 7            | 2         | 0.81%   |
| Zorin 12            | 1         | 0.4%    |
| Xero Rolling        | 1         | 0.4%    |
| Ubuntu MATE 18.04   | 1         | 0.4%    |
| Ubuntu 19.10        | 1         | 0.4%    |
| Ubuntu 18.10        | 1         | 0.4%    |
| ROSA R10            | 1         | 0.4%    |
| RHEL 8              | 1         | 0.4%    |
| Oracle Linux 8.4    | 1         | 0.4%    |
| Manjaro 21.2.6      | 1         | 0.4%    |
| Manjaro 21.1.2      | 1         | 0.4%    |
| LMDE 4              | 1         | 0.4%    |
| LinuxFX 11          | 1         | 0.4%    |
| Linux Mint 19.2     | 1         | 0.4%    |
| Kubuntu 21.10       | 1         | 0.4%    |
| Kubuntu 21.04       | 1         | 0.4%    |
| Kubuntu 20.10       | 1         | 0.4%    |
| Kali 2022.1         | 1         | 0.4%    |
| Kali 2020.3         | 1         | 0.4%    |
| Fedora 35           | 1         | 0.4%    |
| Fedora 32           | 1         | 0.4%    |
| Fedora 31           | 1         | 0.4%    |
| Fedora 30           | 1         | 0.4%    |
| Endless 3.8.0       | 1         | 0.4%    |
| Endless 3.7.8       | 1         | 0.4%    |
| EndeavourOS Rolling | 1         | 0.4%    |
| Deepin 15.10        | 1         | 0.4%    |
| Clear Linux 34640   | 1         | 0.4%    |
| BlackPanther 18.1   | 1         | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 129       | 53.53%  |
| Linux Mint   | 14        | 5.81%   |
| Pop!_OS      | 11        | 4.56%   |
| Debian       | 11        | 4.56%   |
| OpenMandriva | 9         | 3.73%   |
| Fedora       | 9         | 3.73%   |
| Zorin        | 8         | 3.32%   |
| Arch         | 7         | 2.9%    |
| Kubuntu      | 6         | 2.49%   |
| KDE neon     | 6         | 2.49%   |
| Manjaro      | 5         | 2.07%   |
| Kali         | 4         | 1.66%   |
| Parrot       | 2         | 0.83%   |
| Endless      | 2         | 0.83%   |
| Elementary   | 2         | 0.83%   |
| CentOS       | 2         | 0.83%   |
| Xero         | 1         | 0.41%   |
| Ubuntu MATE  | 1         | 0.41%   |
| ROSA         | 1         | 0.41%   |
| RHEL         | 1         | 0.41%   |
| Oracle Linux | 1         | 0.41%   |
| LMDE         | 1         | 0.41%   |
| LinuxFX      | 1         | 0.41%   |
| EndeavourOS  | 1         | 0.41%   |
| Deepin       | 1         | 0.41%   |
| Clear Linux  | 1         | 0.41%   |
| BlackPanther | 1         | 0.41%   |
| ArcoLinux    | 1         | 0.41%   |
| Alpine       | 1         | 0.41%   |
| AlmaLinux    | 1         | 0.41%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.4.0-42-generic            | 10        | 3.86%   |
| 5.11.0-37-generic           | 6         | 2.32%   |
| 5.4.106-1-pve               | 5         | 1.93%   |
| 5.16.7-desktop-1omv4003     | 5         | 1.93%   |
| 5.8.0-59-generic            | 4         | 1.54%   |
| 5.4.0-54-generic            | 4         | 1.54%   |
| 5.4.0-52-generic            | 4         | 1.54%   |
| 5.4.0-48-generic            | 4         | 1.54%   |
| 5.4.0-47-generic            | 4         | 1.54%   |
| 5.4.0-40-generic            | 4         | 1.54%   |
| 5.4.0-26-generic            | 4         | 1.54%   |
| 5.11.0-27-generic           | 4         | 1.54%   |
| 5.10.14-desktop-1omv4002    | 4         | 1.54%   |
| 5.8.0-7630-generic          | 3         | 1.16%   |
| 5.8.0-44-generic            | 3         | 1.16%   |
| 5.8.0-41-generic            | 3         | 1.16%   |
| 5.4.0-7642-generic          | 3         | 1.16%   |
| 5.4.0-58-generic            | 3         | 1.16%   |
| 5.3.0-28-generic            | 3         | 1.16%   |
| 5.13.0-39-generic           | 3         | 1.16%   |
| 5.13.0-30-generic           | 3         | 1.16%   |
| 5.11.0-7620-generic         | 3         | 1.16%   |
| 5.11.0-43-generic           | 3         | 1.16%   |
| 5.11.0-41-generic           | 3         | 1.16%   |
| 5.11.0-40-generic           | 3         | 1.16%   |
| 5.11.0-38-generic           | 3         | 1.16%   |
| 5.0.0-23-generic            | 3         | 1.16%   |
| 5.9.8-200.fc33.x86_64       | 2         | 0.77%   |
| 5.8.0-48-generic            | 2         | 0.77%   |
| 5.8.0-43-generic            | 2         | 0.77%   |
| 5.7.0-2parrot2-amd64        | 2         | 0.77%   |
| 5.4.0-91-generic            | 2         | 0.77%   |
| 5.4.0-67-generic            | 2         | 0.77%   |
| 5.4.0-59-generic            | 2         | 0.77%   |
| 5.4.0-45-generic            | 2         | 0.77%   |
| 5.4.0-39-generic            | 2         | 0.77%   |
| 5.4.0-33-generic            | 2         | 0.77%   |
| 5.4.0-29-generic            | 2         | 0.77%   |
| 5.4.0-28-generic            | 2         | 0.77%   |
| 5.16.15-arch1-1             | 2         | 0.77%   |
| 5.15.0-39-generic           | 2         | 0.77%   |
| 5.15.0-25-generic           | 2         | 0.77%   |
| 5.13.19-1-pve               | 2         | 0.77%   |
| 5.13.0-44-generic           | 2         | 0.77%   |
| 5.13.0-40-generic           | 2         | 0.77%   |
| 5.13.0-28-generic           | 2         | 0.77%   |
| 5.0.0-37-generic            | 2         | 0.77%   |
| 5.0.0-32-generic            | 2         | 0.77%   |
| 4.18.0-18-generic           | 2         | 0.77%   |
| 4.15.0-66-generic           | 2         | 0.77%   |
| 3.10.0-1127.13.1.el7.x86_64 | 2         | 0.77%   |
| 5.9.10-200.fc33.x86_64      | 1         | 0.39%   |
| 5.9.0-rc4+                  | 1         | 0.39%   |
| 5.8.3-2-MANJARO             | 1         | 0.39%   |
| 5.8.0-kali2-amd64           | 1         | 0.39%   |
| 5.8.0-7625-generic          | 1         | 0.39%   |
| 5.8.0-63-generic            | 1         | 0.39%   |
| 5.8.0-55-generic            | 1         | 0.39%   |
| 5.8.0-45-generic            | 1         | 0.39%   |
| 5.8.0-40-generic            | 1         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 63        | 25.51%  |
| 5.11.0   | 29        | 11.74%  |
| 5.8.0    | 23        | 9.31%   |
| 5.13.0   | 19        | 7.69%   |
| 4.15.0   | 16        | 6.48%   |
| 5.0.0    | 11        | 4.45%   |
| 5.3.0    | 7         | 2.83%   |
| 5.15.0   | 7         | 2.83%   |
| 5.4.106  | 5         | 2.02%   |
| 5.16.7   | 5         | 2.02%   |
| 4.18.0   | 5         | 2.02%   |
| 5.11.22  | 4         | 1.62%   |
| 5.10.14  | 4         | 1.62%   |
| 5.10.0   | 3         | 1.21%   |
| 5.9.8    | 2         | 0.81%   |
| 5.7.0    | 2         | 0.81%   |
| 5.16.15  | 2         | 0.81%   |
| 5.13.4   | 2         | 0.81%   |
| 5.13.19  | 2         | 0.81%   |
| 3.10.0   | 2         | 0.81%   |
| 5.9.10   | 1         | 0.4%    |
| 5.9.0    | 1         | 0.4%    |
| 5.8.3    | 1         | 0.4%    |
| 5.7.9    | 1         | 0.4%    |
| 5.7.19   | 1         | 0.4%    |
| 5.7.10   | 1         | 0.4%    |
| 5.6.0    | 1         | 0.4%    |
| 5.4.41   | 1         | 0.4%    |
| 5.4.36   | 1         | 0.4%    |
| 5.4.175  | 1         | 0.4%    |
| 5.4.17   | 1         | 0.4%    |
| 5.4.15   | 1         | 0.4%    |
| 5.3.7    | 1         | 0.4%    |
| 5.2.13   | 1         | 0.4%    |
| 5.18.0   | 1         | 0.4%    |
| 5.17.9   | 1         | 0.4%    |
| 5.17.5   | 1         | 0.4%    |
| 5.16.0   | 1         | 0.4%    |
| 5.15.41  | 1         | 0.4%    |
| 5.14.2   | 1         | 0.4%    |
| 5.14.18  | 1         | 0.4%    |
| 5.14.11  | 1         | 0.4%    |
| 5.13.9   | 1         | 0.4%    |
| 5.13.7   | 1         | 0.4%    |
| 5.13.14  | 1         | 0.4%    |
| 5.13.13  | 1         | 0.4%    |
| 5.12.5   | 1         | 0.4%    |
| 5.12.12  | 1         | 0.4%    |
| 5.10.61  | 1         | 0.4%    |
| 5.10.17  | 1         | 0.4%    |
| 4.9.124  | 1         | 0.4%    |
| 4.19.0   | 1         | 0.4%    |
| 4.18.16  | 1         | 0.4%    |
| 3.10.105 | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 73        | 29.67%  |
| 5.11    | 33        | 13.41%  |
| 5.13    | 27        | 10.98%  |
| 5.8     | 24        | 9.76%   |
| 4.15    | 16        | 6.5%    |
| 5.0     | 11        | 4.47%   |
| 5.10    | 9         | 3.66%   |
| 5.3     | 8         | 3.25%   |
| 5.16    | 8         | 3.25%   |
| 5.15    | 8         | 3.25%   |
| 4.18    | 6         | 2.44%   |
| 5.7     | 5         | 2.03%   |
| 5.9     | 3         | 1.22%   |
| 5.14    | 3         | 1.22%   |
| 3.10    | 3         | 1.22%   |
| 5.17    | 2         | 0.81%   |
| 5.12    | 2         | 0.81%   |
| 5.6     | 1         | 0.41%   |
| 5.2     | 1         | 0.41%   |
| 5.18    | 1         | 0.41%   |
| 4.9     | 1         | 0.41%   |
| 4.19    | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 229       | 98.28%  |
| i686   | 4         | 1.72%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 143       | 59.34%  |
| Unknown    | 36        | 14.94%  |
| KDE5       | 21        | 8.71%   |
| X-Cinnamon | 12        | 4.98%   |
| KDE        | 8         | 3.32%   |
| XFCE       | 5         | 2.07%   |
| MATE       | 5         | 2.07%   |
| Unity      | 3         | 1.24%   |
| KDE4       | 3         | 1.24%   |
| Pantheon   | 2         | 0.83%   |
| i3         | 2         | 0.83%   |
| Deepin     | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 185       | 77.41%  |
| Wayland | 23        | 9.62%   |
| Unknown | 23        | 9.62%   |
| Tty     | 8         | 3.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 146       | 61.86%  |
| GDM     | 40        | 16.95%  |
| GDM3    | 21        | 8.9%    |
| SDDM    | 17        | 7.2%    |
| LightDM | 6         | 2.54%   |
| TDM     | 5         | 2.12%   |
| KDM     | 1         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 198       | 83.9%   |
| Unknown | 23        | 9.75%   |
| en_GB   | 10        | 4.24%   |
| en_PK   | 3         | 1.27%   |
| ur_PK   | 1         | 0.42%   |
| C       | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 128       | 53.33%  |
| EFI  | 112       | 46.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 203       | 84.23%  |
| Overlay | 11        | 4.56%   |
| Btrfs   | 10        | 4.15%   |
| Zfs     | 7         | 2.9%    |
| Unknown | 6         | 2.49%   |
| Xfs     | 4         | 1.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 157       | 66.81%  |
| GPT     | 62        | 26.38%  |
| MBR     | 16        | 6.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 207       | 87.34%  |
| Yes       | 30        | 12.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 152       | 63.87%  |
| Yes       | 86        | 36.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 85        | 36.48%  |
| Dell                | 72        | 30.9%   |
| Lenovo              | 34        | 14.59%  |
| Gigabyte Technology | 8         | 3.43%   |
| ASUSTek Computer    | 7         | 3%      |
| Haier               | 5         | 2.15%   |
| Acer                | 4         | 1.72%   |
| Toshiba             | 3         | 1.29%   |
| Sony                | 3         | 1.29%   |
| Apple               | 3         | 1.29%   |
| Shuttle             | 2         | 0.86%   |
| Samsung Electronics | 2         | 0.86%   |
| MOTION              | 1         | 0.43%   |
| Microsoft           | 1         | 0.43%   |
| Fujitsu             | 1         | 0.43%   |
| AMI                 | 1         | 0.43%   |
| Unknown             | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| HP ProBook 450 G7                   | 5         | 2.15%   |
| HP EliteBook 8470p                  | 5         | 2.15%   |
| Dell Precision WorkStation T7500    | 4         | 1.72%   |
| HP EliteBook 840 G3                 | 3         | 1.29%   |
| Haier Y11C                          | 3         | 1.29%   |
| Dell Precision WorkStation T3500    | 3         | 1.29%   |
| Dell Latitude E7450                 | 3         | 1.29%   |
| Dell Latitude E6420                 | 3         | 1.29%   |
| Unknown                             | 3         | 1.29%   |
| Shuttle DS81D                       | 2         | 0.86%   |
| Lenovo ThinkBook 15-IML 20RW        | 2         | 0.86%   |
| Lenovo ThinkBook 15-IIL 20SM        | 2         | 0.86%   |
| Lenovo ThinkBook 15 G2 ITL 20VE     | 2         | 0.86%   |
| HP ZBook 15 G3                      | 2         | 0.86%   |
| HP ProLiant DL380p Gen8             | 2         | 0.86%   |
| HP ProDesk 400 G7 Microtower PC     | 2         | 0.86%   |
| HP ProBook 450 G5                   | 2         | 0.86%   |
| HP ProBook 450 G3                   | 2         | 0.86%   |
| HP ProBook 440 G7                   | 2         | 0.86%   |
| HP Pavilion Notebook                | 2         | 0.86%   |
| HP ENVY x360 m6 Convertible         | 2         | 0.86%   |
| HP EliteBook 8440p                  | 2         | 0.86%   |
| HP EliteBook 840 G2                 | 2         | 0.86%   |
| HP EliteBook 6930p                  | 2         | 0.86%   |
| HP 650                              | 2         | 0.86%   |
| Haier Y11B                          | 2         | 0.86%   |
| Gigabyte Z590 UD AC                 | 2         | 0.86%   |
| Gigabyte A520M S2H                  | 2         | 0.86%   |
| Dell XPS 630i                       | 2         | 0.86%   |
| Dell Vostro 430                     | 2         | 0.86%   |
| Dell Vostro 14-3468                 | 2         | 0.86%   |
| Dell Precision WorkStation 490      | 2         | 0.86%   |
| Dell OptiPlex 755                   | 2         | 0.86%   |
| Dell Latitude E6440                 | 2         | 0.86%   |
| Dell Latitude E5250                 | 2         | 0.86%   |
| Dell Latitude E4300                 | 2         | 0.86%   |
| Dell Latitude 3510                  | 2         | 0.86%   |
| Dell Inspiron 5593                  | 2         | 0.86%   |
| Dell Inspiron 3501                  | 2         | 0.86%   |
| Dell Inspiron 15-3567               | 2         | 0.86%   |
| Toshiba Satellite S50t-B            | 1         | 0.43%   |
| Toshiba Satellite L850              | 1         | 0.43%   |
| Toshiba PORTEGE Z30-B               | 1         | 0.43%   |
| Sony VPCEA26FG                      | 1         | 0.43%   |
| Sony VPCCB490X                      | 1         | 0.43%   |
| Sony SVE15126CXS                    | 1         | 0.43%   |
| Samsung QX311/QX411/QX412/QX511     | 1         | 0.43%   |
| Samsung 940Z5L                      | 1         | 0.43%   |
| MOTION J3500                        | 1         | 0.43%   |
| Microsoft Surface Pro 3             | 1         | 0.43%   |
| Lenovo V110-15IKB 80TH              | 1         | 0.43%   |
| Lenovo ThinkStation D30 4223CC9     | 1         | 0.43%   |
| Lenovo ThinkPad X220 Tablet 4298A11 | 1         | 0.43%   |
| Lenovo ThinkPad X201 3249CTO        | 1         | 0.43%   |
| Lenovo ThinkPad W500 40612HU        | 1         | 0.43%   |
| Lenovo ThinkPad T60 1951WAT         | 1         | 0.43%   |
| Lenovo ThinkPad T540p 20BFS56300    | 1         | 0.43%   |
| Lenovo ThinkPad T460 20FMS39800     | 1         | 0.43%   |
| Lenovo ThinkPad T450 20BV0005US     | 1         | 0.43%   |
| Lenovo ThinkPad T440p 20AWS0DU00    | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 26        | 11.16%  |
| HP EliteBook          | 23        | 9.87%   |
| HP ProBook            | 19        | 8.15%   |
| Lenovo ThinkPad       | 18        | 7.73%   |
| Dell Inspiron         | 18        | 7.73%   |
| Dell Precision        | 12        | 5.15%   |
| HP Pavilion           | 11        | 4.72%   |
| HP Compaq             | 8         | 3.43%   |
| Dell OptiPlex         | 7         | 3%      |
| Lenovo ThinkBook      | 6         | 2.58%   |
| Dell Vostro           | 6         | 2.58%   |
| Lenovo ThinkCentre    | 5         | 2.15%   |
| HP ProDesk            | 4         | 1.72%   |
| HP ProLiant           | 3         | 1.29%   |
| HP ENVY               | 3         | 1.29%   |
| Haier Y11C            | 3         | 1.29%   |
| Acer Aspire           | 3         | 1.29%   |
| Unknown               | 3         | 1.29%   |
| Toshiba Satellite     | 2         | 0.86%   |
| Shuttle DS81D         | 2         | 0.86%   |
| Lenovo IdeaPad        | 2         | 0.86%   |
| HP ZBook              | 2         | 0.86%   |
| HP Laptop             | 2         | 0.86%   |
| HP 650                | 2         | 0.86%   |
| Haier Y11B            | 2         | 0.86%   |
| Gigabyte Z590         | 2         | 0.86%   |
| Gigabyte A520M        | 2         | 0.86%   |
| Dell XPS              | 2         | 0.86%   |
| Toshiba PORTEGE       | 1         | 0.43%   |
| Sony VPCEA26FG        | 1         | 0.43%   |
| Sony VPCCB490X        | 1         | 0.43%   |
| Sony SVE15126CXS      | 1         | 0.43%   |
| Samsung QX311         | 1         | 0.43%   |
| Samsung 940Z5L        | 1         | 0.43%   |
| MOTION J3500          | 1         | 0.43%   |
| Microsoft Surface     | 1         | 0.43%   |
| Lenovo V110-15IKB     | 1         | 0.43%   |
| Lenovo ThinkStation   | 1         | 0.43%   |
| Lenovo H520           | 1         | 0.43%   |
| HP Z800               | 1         | 0.43%   |
| HP Z620               | 1         | 0.43%   |
| HP Z420               | 1         | 0.43%   |
| HP Z400               | 1         | 0.43%   |
| HP Z210               | 1         | 0.43%   |
| HP Notebook           | 1         | 0.43%   |
| HP 14                 | 1         | 0.43%   |
| Gigabyte Z170X-Gaming | 1         | 0.43%   |
| Gigabyte B450M        | 1         | 0.43%   |
| Gigabyte B250M-D3H    | 1         | 0.43%   |
| Gigabyte AERO         | 1         | 0.43%   |
| Fujitsu LIFEBOOK      | 1         | 0.43%   |
| Dell G3               | 1         | 0.43%   |
| ASUS VivoBook         | 1         | 0.43%   |
| ASUS TUF              | 1         | 0.43%   |
| ASUS STRIX            | 1         | 0.43%   |
| ASUS Q87M-XA          | 1         | 0.43%   |
| ASUS PRIME            | 1         | 0.43%   |
| ASUS MINIPC           | 1         | 0.43%   |
| ASUS K53U             | 1         | 0.43%   |
| Apple MacBookPro16    | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 32        | 13.73%  |
| 2020    | 23        | 9.87%   |
| 2019    | 21        | 9.01%   |
| 2016    | 19        | 8.15%   |
| 2012    | 18        | 7.73%   |
| 2014    | 17        | 7.3%    |
| 2018    | 15        | 6.44%   |
| 2010    | 15        | 6.44%   |
| 2017    | 14        | 6.01%   |
| 2013    | 14        | 6.01%   |
| 2015    | 12        | 5.15%   |
| 2008    | 9         | 3.86%   |
| 2009    | 8         | 3.43%   |
| 2021    | 7         | 3%      |
| 2007    | 5         | 2.15%   |
| 2006    | 3         | 1.29%   |
| Unknown | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 160       | 68.67%  |
| Desktop     | 62        | 26.61%  |
| Convertible | 5         | 2.15%   |
| Server      | 3         | 1.29%   |
| Tablet      | 2         | 0.86%   |
| Mini pc     | 1         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 222       | 94.87%  |
| Enabled  | 12        | 5.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 233       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 71        | 30.21%  |
| 3.01-4.0        | 51        | 21.7%   |
| 16.01-24.0      | 47        | 20%     |
| 8.01-16.0       | 38        | 16.17%  |
| 32.01-64.0      | 14        | 5.96%   |
| 64.01-256.0     | 7         | 2.98%   |
| 1.01-2.0        | 4         | 1.7%    |
| 24.01-32.0      | 2         | 0.85%   |
| More than 256.0 | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 85        | 33.73%  |
| 2.01-3.0    | 83        | 32.94%  |
| 4.01-8.0    | 30        | 11.9%   |
| 3.01-4.0    | 29        | 11.51%  |
| 8.01-16.0   | 14        | 5.56%   |
| 0.51-1.0    | 6         | 2.38%   |
| 16.01-24.0  | 2         | 0.79%   |
| 32.01-64.0  | 1         | 0.4%    |
| 64.01-256.0 | 1         | 0.4%    |
| Unknown     | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 149       | 61.83%  |
| 2      | 62        | 25.73%  |
| 3      | 13        | 5.39%   |
| 6      | 4         | 1.66%   |
| 4      | 4         | 1.66%   |
| 5      | 3         | 1.24%   |
| 13     | 1         | 0.41%   |
| 11     | 1         | 0.41%   |
| 10     | 1         | 0.41%   |
| 9      | 1         | 0.41%   |
| 8      | 1         | 0.41%   |
| 0      | 1         | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 156       | 66.67%  |
| Yes       | 78        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 215       | 92.27%  |
| No        | 18        | 7.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 84.26%  |
| No        | 37        | 15.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 59%     |
| No        | 98        | 41%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Pakistan | 233       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lahore                         | 87        | 36.4%   |
| Karachi                        | 53        | 22.18%  |
| Islamabad                      | 38        | 15.9%   |
| Rawalpindi                     | 13        | 5.44%   |
| Multan                         | 7         | 2.93%   |
| Faisalabad                     | 7         | 2.93%   |
| Peshawar                       | 4         | 1.67%   |
| Sialkot                        | 2         | 0.84%   |
| Sargodha                       | 2         | 0.84%   |
| Kamoke                         | 2         | 0.84%   |
| Jhelum                         | 2         | 0.84%   |
| Tando Allahyar                 | 1         | 0.42%   |
| Sheikhupura                    | 1         | 0.42%   |
| Sahiwal                        | 1         | 0.42%   |
| Rahim Yar Khan                 | 1         | 0.42%   |
| Pindi Gheb                     | 1         | 0.42%   |
| Mirpur                         | 1         | 0.42%   |
| Mardan                         | 1         | 0.42%   |
| Layari                         | 1         | 0.42%   |
| Larkana                        | 1         | 0.42%   |
| Khanewal                       | 1         | 0.42%   |
| Hyderabad                      | 1         | 0.42%   |
| Hazro City                     | 1         | 0.42%   |
| Hassan Abdal                   | 1         | 0.42%   |
| Gujranwala                     | 1         | 0.42%   |
| Ghotki                         | 1         | 0.42%   |
| Dina                           | 1         | 0.42%   |
| Daska Kalan                    | 1         | 0.42%   |
| Dadu                           | 1         | 0.42%   |
| Chak Five Hundred Seventy-five | 1         | 0.42%   |
| Burewala                       | 1         | 0.42%   |
| Bahawalpur                     | 1         | 0.42%   |
| Abbottabad                     | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 64        | 105    | 18.55%  |
| WDC                          | 52        | 69     | 15.07%  |
| Samsung Electronics          | 41        | 45     | 11.88%  |
| Toshiba                      | 25        | 26     | 7.25%   |
| Hitachi                      | 20        | 27     | 5.8%    |
| Intel                        | 12        | 16     | 3.48%   |
| Kingston                     | 11        | 12     | 3.19%   |
| HGST                         | 9         | 10     | 2.61%   |
| Unknown                      | 8         | 9      | 2.32%   |
| Transcend                    | 8         | 8      | 2.32%   |
| SK hynix                     | 7         | 9      | 2.03%   |
| SanDisk                      | 7         | 8      | 2.03%   |
| Hewlett-Packard              | 7         | 16     | 2.03%   |
| Micron Technology            | 6         | 6      | 1.74%   |
| LITEON                       | 6         | 7      | 1.74%   |
| HS-SSD-E100                  | 6         | 6      | 1.74%   |
| Hajaan                       | 6         | 8      | 1.74%   |
| Silicon Motion               | 5         | 5      | 1.45%   |
| LITEONIT                     | 5         | 7      | 1.45%   |
| Lexar                        | 4         | 6      | 1.16%   |
| LaCie                        | 3         | 3      | 0.87%   |
| KIOXIA                       | 3         | 3      | 0.87%   |
| Crucial                      | 3         | 3      | 0.87%   |
| Apple                        | 3         | 4      | 0.87%   |
| A-DATA Technology            | 3         | 3      | 0.87%   |
| Maxtor                       | 2         | 2      | 0.58%   |
| Fujitsu                      | 2         | 2      | 0.58%   |
| ZTE                          | 1         | 1      | 0.29%   |
| Toshiba America Info Systems | 1         | 1      | 0.29%   |
| Team                         | 1         | 1      | 0.29%   |
| PNY                          | 1         | 2      | 0.29%   |
| Phison                       | 1         | 2      | 0.29%   |
| PHD 3.0                      | 1         | 1      | 0.29%   |
| MARSHAL                      | 1         | 1      | 0.29%   |
| Kingsand                     | 1         | 1      | 0.29%   |
| KingFast                     | 1         | 2      | 0.29%   |
| KESU                         | 1         | 1      | 0.29%   |
| Integral                     | 1         | 2      | 0.29%   |
| IBM-ESXS                     | 1         | 3      | 0.29%   |
| HS-SSD-E100N                 | 1         | 1      | 0.29%   |
| Gigabyte Technology          | 1         | 1      | 0.29%   |
| CSD                          | 1         | 1      | 0.29%   |
| Biostar                      | 1         | 1      | 0.29%   |
| Apacer                       | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST3000NXCLAR3000 3TB           | 7         | 1.85%   |
| WDC WD10SPZX-60Z10T0 1TB               | 6         | 1.59%   |
| HP MB2000EBZQC 2TB                     | 6         | 1.59%   |
| Hajaan SSD 256G                        | 6         | 1.59%   |
| Samsung SSD PM830 2.5 7mm 256GB        | 5         | 1.32%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 1.06%   |
| Toshiba MQ01ABF050 500GB               | 4         | 1.06%   |
| Seagate ST500LT012-1DG142 500GB        | 4         | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB         | 4         | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 4         | 1.06%   |
| Samsung MZALQ512HALU-000L1 512GB       | 4         | 1.06%   |
| WDC WD10SPZX-75Z10T3 1TB               | 3         | 0.79%   |
| WDC PC SN530 NVMe 256GB                | 3         | 0.79%   |
| Silicon Motion NVMe SSD Drive 512GB    | 3         | 0.79%   |
| Seagate ST8000DM004-2CX188 8TB         | 3         | 0.79%   |
| Seagate ST6000NM0024 6TB               | 3         | 0.79%   |
| Samsung MZ7PD128HCFV-000H1 128GB SSD   | 3         | 0.79%   |
| LITEONIT LCS-128M6S 2.5 7mm 128GB SSD  | 3         | 0.79%   |
| LITEON CV1-CC128-11 2.5 7mm 128GB      | 3         | 0.79%   |
| Lexar 256GB SSD                        | 3         | 0.79%   |
| LaCie Rugged USB-C 4TB                 | 3         | 0.79%   |
| Intel SSDSA2M080G2GN 73GB              | 3         | 0.79%   |
| HS-SSD-E100 128G                       | 3         | 0.79%   |
| WDC WD5000LPVX-75V0TT0 500GB           | 2         | 0.53%   |
| WDC WD10SPZX-24Z10 1TB                 | 2         | 0.53%   |
| Transcend TS512GMTE110S 512GB          | 2         | 0.53%   |
| Transcend TS256GMTS830S 256GB SSD      | 2         | 0.53%   |
| Transcend TS120GSSD220S 120GB          | 2         | 0.53%   |
| Toshiba MQ01ACF050 500GB               | 2         | 0.53%   |
| SK hynix SC300 M.2 2280 256GB SSD      | 2         | 0.53%   |
| Seagate ST9320423AS 320GB              | 2         | 0.53%   |
| Seagate ST9250315AS 250GB              | 2         | 0.53%   |
| Seagate ST9250311CS 250GB              | 2         | 0.53%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 0.53%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 0.53%   |
| Seagate ST3500414CS 500GB              | 2         | 0.53%   |
| Seagate ST3250318AS 250GB              | 2         | 0.53%   |
| Seagate ST2000VM003-1ET164 2TB         | 2         | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB         | 2         | 0.53%   |
| Seagate ST2000DM008-2FR1               | 2         | 0.53%   |
| Seagate ST1000DM003-1SB102 1TB         | 2         | 0.53%   |
| SanDisk X110 MSATA 128GB SSD           | 2         | 0.53%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 2         | 0.53%   |
| Maxtor STM380215AS 80GB                | 2         | 0.53%   |
| KIOXIA NVMe SSD Drive 256GB            | 2         | 0.53%   |
| Kingston NVMe SSD Drive 250GB          | 2         | 0.53%   |
| Intel NVMe SSD Drive 512GB             | 2         | 0.53%   |
| Intel H10 HBRPEKNX0202AO NVMe 32GB     | 2         | 0.53%   |
| Intel H10 HBRPEKNX0202A NVMe 512GB     | 2         | 0.53%   |
| Hitachi HUA723020ALA640 2TB            | 2         | 0.53%   |
| Hitachi HTS545050A7E380 500GB          | 2         | 0.53%   |
| Hitachi HTS545032B9A300 320GB          | 2         | 0.53%   |
| Hitachi HTS543225A7A384 250GB          | 2         | 0.53%   |
| HGST HTS725032A7E630 320GB             | 2         | 0.53%   |
| HGST HTS721010A9E630 1TB               | 2         | 0.53%   |
| HGST HTS541010B7E610 1TB               | 2         | 0.53%   |
| HGST HTS541010A9E680 1TB               | 2         | 0.53%   |
| Crucial CT525MX300SSD1 528GB           | 2         | 0.53%   |
| ZTE MMC Storage 8GB                    | 1         | 0.26%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 64        | 105    | 36.16%  |
| WDC                 | 45        | 57     | 25.42%  |
| Toshiba             | 21        | 22     | 11.86%  |
| Hitachi             | 20        | 27     | 11.3%   |
| HGST                | 9         | 10     | 5.08%   |
| Hewlett-Packard     | 6         | 15     | 3.39%   |
| Samsung Electronics | 4         | 4      | 2.26%   |
| Maxtor              | 2         | 2      | 1.13%   |
| Fujitsu             | 2         | 2      | 1.13%   |
| Unknown             | 1         | 1      | 0.56%   |
| PHD 3.0             | 1         | 1      | 0.56%   |
| MARSHAL             | 1         | 1      | 0.56%   |
| KESU                | 1         | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 29     | 25%     |
| Kingston            | 9         | 10     | 8.65%   |
| SK hynix            | 7         | 9      | 6.73%   |
| SanDisk             | 6         | 6      | 5.77%   |
| LITEON              | 6         | 7      | 5.77%   |
| Intel               | 6         | 7      | 5.77%   |
| Hajaan              | 6         | 8      | 5.77%   |
| Transcend           | 5         | 5      | 4.81%   |
| Micron Technology   | 5         | 5      | 4.81%   |
| LITEONIT            | 5         | 7      | 4.81%   |
| WDC                 | 4         | 5      | 3.85%   |
| Lexar               | 4         | 6      | 3.85%   |
| Crucial             | 3         | 3      | 2.88%   |
| Toshiba             | 2         | 2      | 1.92%   |
| A-DATA Technology   | 2         | 2      | 1.92%   |
| Team                | 1         | 1      | 0.96%   |
| PNY                 | 1         | 2      | 0.96%   |
| HS-SSD-E100         | 1         | 1      | 0.96%   |
| Hewlett-Packard     | 1         | 1      | 0.96%   |
| Gigabyte Technology | 1         | 1      | 0.96%   |
| Biostar             | 1         | 1      | 0.96%   |
| Apple               | 1         | 1      | 0.96%   |
| Apacer              | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 145       | 248    | 49.66%  |
| SSD     | 84        | 120    | 28.77%  |
| NVMe    | 43        | 54     | 14.73%  |
| Unknown | 15        | 20     | 5.14%   |
| MMC     | 5         | 6      | 1.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 194       | 361    | 75.78%  |
| NVMe | 43        | 54     | 16.8%   |
| SAS  | 14        | 27     | 5.47%   |
| MMC  | 5         | 6      | 1.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 147       | 236    | 63.36%  |
| 0.51-1.0   | 64        | 71     | 27.59%  |
| 1.01-2.0   | 10        | 31     | 4.31%   |
| 2.01-3.0   | 7         | 14     | 3.02%   |
| 4.01-10.0  | 3         | 15     | 1.29%   |
| 3.01-4.0   | 1         | 1      | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 87        | 35.22%  |
| 251-500        | 53        | 21.46%  |
| 51-100         | 46        | 18.62%  |
| 501-1000       | 20        | 8.1%    |
| 1-20           | 12        | 4.86%   |
| 21-50          | 10        | 4.05%   |
| 1001-2000      | 9         | 3.64%   |
| Unknown        | 7         | 2.83%   |
| More than 3000 | 2         | 0.81%   |
| 2001-3000      | 1         | 0.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 104       | 41.43%  |
| 21-50     | 61        | 24.3%   |
| 101-250   | 29        | 11.55%  |
| 51-100    | 28        | 11.16%  |
| 251-500   | 12        | 4.78%   |
| 501-1000  | 9         | 3.59%   |
| Unknown   | 7         | 2.79%   |
| 1001-2000 | 1         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                  | 2         | 2      | 7.14%   |
| Seagate ST2000DM008-2FR1                      | 2         | 2      | 7.14%   |
| Crucial CT525MX300SSD1 528GB                  | 2         | 2      | 7.14%   |
| WDC WD5000AAKX-75U6AA0 500GB                  | 1         | 1      | 3.57%   |
| WDC WD2500HHTZ-04N21V0 250GB                  | 1         | 1      | 3.57%   |
| WDC WD2500AAKS-00F0A0 250GB                   | 1         | 1      | 3.57%   |
| WDC WD1600AAJS-22L7A0 160GB                   | 1         | 1      | 3.57%   |
| WDC WD10JPVT-75A1YT0 1TB                      | 1         | 1      | 3.57%   |
| SK hynix HFS128G39TND-N210A 128GB SSD         | 1         | 1      | 3.57%   |
| Seagate ST3500418AS 500GB                     | 1         | 1      | 3.57%   |
| Seagate ST3160215AS 160GB                     | 1         | 1      | 3.57%   |
| Seagate ST2000DM008-2FR102 2TB                | 1         | 2      | 3.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB            | 1         | 1      | 3.57%   |
| Seagate ST1000DM010-2EP102 1TB                | 1         | 1      | 3.57%   |
| Samsung Electronics SP2004C 200GB             | 1         | 1      | 3.57%   |
| Samsung Electronics HD080HJ/ 80GB             | 1         | 1      | 3.57%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 1      | 3.57%   |
| Intel SSDSCKKF256G8H 256GB                    | 1         | 1      | 3.57%   |
| Intel SSDSA2M080G2GN 73GB                     | 1         | 1      | 3.57%   |
| Hitachi HUA723020ALA640 2TB                   | 1         | 2      | 3.57%   |
| Hitachi HTS725032A9A364 320GB                 | 1         | 1      | 3.57%   |
| Hitachi HTS543232A7A384 320GB                 | 1         | 1      | 3.57%   |
| Hitachi HDS721680PLA380 80GB                  | 1         | 1      | 3.57%   |
| Hitachi HDS721050CLA660 500GB                 | 1         | 1      | 3.57%   |
| Hewlett-Packard MB2000EBZQC 2TB               | 1         | 2      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 25.93%  |
| Seagate             | 6         | 8      | 22.22%  |
| Hitachi             | 5         | 6      | 18.52%  |
| Samsung Electronics | 2         | 2      | 7.41%   |
| Intel               | 2         | 2      | 7.41%   |
| Crucial             | 2         | 2      | 7.41%   |
| SK hynix            | 1         | 1      | 3.7%    |
| Micron Technology   | 1         | 1      | 3.7%    |
| Hewlett-Packard     | 1         | 2      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 33.33%  |
| Seagate             | 6         | 8      | 28.57%  |
| Hitachi             | 5         | 6      | 23.81%  |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Hewlett-Packard     | 1         | 2      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 25     | 71.43%  |
| SSD  | 6         | 6      | 28.57%  |

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
| Detected | 161       | 268    | 64.4%   |
| Works    | 69        | 149    | 27.6%   |
| Malfunc  | 20        | 31     | 8%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 203       | 74.36%  |
| AMD                          | 14        | 5.13%   |
| Samsung Electronics          | 11        | 4.03%   |
| LSI Logic / Symbios Logic    | 8         | 2.93%   |
| Silicon Motion               | 6         | 2.2%    |
| SanDisk                      | 6         | 2.2%    |
| KIOXIA                       | 5         | 1.83%   |
| Hewlett-Packard              | 3         | 1.1%    |
| Unknown                      | 2         | 0.73%   |
| Toshiba America Info Systems | 2         | 0.73%   |
| Nvidia                       | 2         | 0.73%   |
| Kingston Technology Company  | 2         | 0.73%   |
| Apple                        | 2         | 0.73%   |
| Realtek Semiconductor        | 1         | 0.37%   |
| Phison Electronics           | 1         | 0.37%   |
| Micron Technology            | 1         | 0.37%   |
| Marvell Technology Group     | 1         | 0.37%   |
| Broadcom / LSI               | 1         | 0.37%   |
| ASMedia Technology           | 1         | 0.37%   |
| Adaptec                      | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 30        | 9.09%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 15        | 4.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 14        | 4.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 13        | 3.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 11        | 3.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 10        | 3.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 10        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 10        | 3.03%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 9         | 2.73%   |
| LSI Logic / Symbios Logic SAS1068E PCI-Express Fusion-MPT SAS                          | 8         | 2.42%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 8         | 2.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 6         | 1.82%   |
| Samsung NVMe SSD Controller 980                                                        | 6         | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 6         | 1.82%   |
| KIOXIA Non-Volatile memory controller                                                  | 5         | 1.52%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 5         | 1.52%   |
| Intel SATA Controller [RAID mode]                                                      | 5         | 1.52%   |
| Intel Non-Volatile memory controller                                                   | 5         | 1.52%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                      | 5         | 1.52%   |
| SanDisk Non-Volatile memory controller                                                 | 4         | 1.21%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                | 4         | 1.21%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 4         | 1.21%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 1.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 1.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 0.91%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 3         | 0.91%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                    | 3         | 0.91%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                              | 3         | 0.91%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                               | 3         | 0.91%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                             | 3         | 0.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 3         | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 0.91%   |
| AMD 500 Series Chipset SATA Controller                                                 | 3         | 0.91%   |
| Unknown Non-Volatile memory controller                                                 | 2         | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 0.61%   |
| Nvidia MCP51 Serial ATA Controller                                                     | 2         | 0.61%   |
| Nvidia MCP51 IDE                                                                       | 2         | 0.61%   |
| LSI Logic / Symbios Logic SAS1064ET PCI-Express Fusion-MPT SAS                         | 2         | 0.61%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2008 [Falcon]                                   | 2         | 0.61%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 0.61%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 0.61%   |
| Intel C600/X79 series chipset IDE-r Controller                                         | 2         | 0.61%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 0.61%   |
| Intel 82Q35 Express PT IDER Controller                                                 | 2         | 0.61%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                             | 2         | 0.61%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                   | 2         | 0.61%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                   | 2         | 0.61%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 0.61%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 0.61%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                                 | 2         | 0.61%   |
| Intel 631xESB/632xESB IDE Controller                                                   | 2         | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.61%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                             | 2         | 0.61%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 2         | 0.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 2         | 0.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 2         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 174       | 57.81%  |
| NVMe | 43        | 14.29%  |
| IDE  | 35        | 11.63%  |
| RAID | 34        | 11.3%   |
| SCSI | 9         | 2.99%   |
| SAS  | 6         | 1.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 219       | 93.99%  |
| AMD    | 14        | 6.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-10510U CPU @ 1.80GHz      | 9         | 3.86%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 3%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 3%      |
| Intel Core i7-7500U CPU @ 2.70GHz       | 6         | 2.58%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 2.58%   |
| Intel Xeon CPU X5650 @ 2.67GHz          | 5         | 2.15%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 5         | 2.15%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 2.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 4         | 1.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 1.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 4         | 1.72%   |
| Intel Xeon CPU E5-2609 0 @ 2.40GHz      | 3         | 1.29%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz        | 3         | 1.29%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 1.29%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 1.29%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 3         | 1.29%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.29%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 3         | 1.29%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 3         | 1.29%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 1.29%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 3         | 1.29%   |
| Intel Xeon CPU X5660 @ 2.80GHz          | 2         | 0.86%   |
| Intel Xeon CPU 5160 @ 3.00GHz           | 2         | 0.86%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 2         | 0.86%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.86%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 2         | 0.86%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 0.86%   |
| Intel Core i7-4600M CPU @ 2.90GHz       | 2         | 0.86%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 2         | 0.86%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.86%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 2         | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 0.86%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 0.86%   |
| Intel Core i5-3427U CPU @ 1.80GHz       | 2         | 0.86%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 2         | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.86%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 0.86%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 2         | 0.86%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 2         | 0.86%   |
| Intel Core i3-2328M CPU @ 2.20GHz       | 2         | 0.86%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 2         | 0.86%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz    | 2         | 0.86%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 0.86%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 2         | 0.86%   |
| Intel Celeron CPU G1850 @ 2.90GHz       | 2         | 0.86%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz | 2         | 0.86%   |
| Intel Xeon CPU X5560 @ 2.80GHz          | 1         | 0.43%   |
| Intel Xeon CPU W3680 @ 3.33GHz          | 1         | 0.43%   |
| Intel Xeon CPU W3565 @ 3.20GHz          | 1         | 0.43%   |
| Intel Xeon CPU W3520 @ 2.67GHz          | 1         | 0.43%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz      | 1         | 0.43%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GHz      | 1         | 0.43%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1         | 0.43%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz  | 1         | 0.43%   |
| Intel Pentium CPU G870 @ 3.10GHz        | 1         | 0.43%   |
| Intel Pentium CPU B940 @ 2.00GHz        | 1         | 0.43%   |
| Intel Pentium CPU 4415U @ 2.30GHz       | 1         | 0.43%   |
| Intel Genuine CPU T2400 @ 1.83GHz       | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 80        | 34.33%  |
| Intel Core i7        | 58        | 24.89%  |
| Intel Xeon           | 19        | 8.15%   |
| Other                | 15        | 6.44%   |
| Intel Core 2 Duo     | 14        | 6.01%   |
| Intel Core i3        | 12        | 5.15%   |
| Intel Celeron        | 5         | 2.15%   |
| AMD Ryzen 7          | 4         | 1.72%   |
| AMD Ryzen 5          | 4         | 1.72%   |
| Intel Pentium        | 3         | 1.29%   |
| Intel Core m3        | 3         | 1.29%   |
| Intel Core M         | 2         | 0.86%   |
| Intel Core 2 Quad    | 2         | 0.86%   |
| Intel Atom           | 2         | 0.86%   |
| AMD Athlon II X2     | 2         | 0.86%   |
| Intel Pentium Dual   | 1         | 0.43%   |
| Intel Genuine        | 1         | 0.43%   |
| Intel Core 2 Extreme | 1         | 0.43%   |
| Intel Core 2         | 1         | 0.43%   |
| AMD Ryzen 3          | 1         | 0.43%   |
| AMD E                | 1         | 0.43%   |
| AMD A6               | 1         | 0.43%   |
| AMD A12              | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 124       | 52.99%  |
| 4      | 78        | 33.33%  |
| 6      | 14        | 5.98%   |
| 8      | 12        | 5.13%   |
| 12     | 3         | 1.28%   |
| 16     | 2         | 0.85%   |
| 1      | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 224       | 95.73%  |
| 2      | 10        | 4.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 177       | 75.97%  |
| 1      | 56        | 24.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 230       | 98.29%  |
| Unknown        | 3         | 1.28%   |
| 32-bit         | 1         | 0.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 18.67%  |
| 0x206a7    | 20        | 8.3%    |
| 0x806ec    | 14        | 5.81%   |
| 0x806e9    | 14        | 5.81%   |
| 0x306a9    | 13        | 5.39%   |
| 0x806c1    | 12        | 4.98%   |
| 0x406e3    | 11        | 4.56%   |
| 0x306d4    | 11        | 4.56%   |
| 0x20655    | 10        | 4.15%   |
| 0x1067a    | 10        | 4.15%   |
| 0x40651    | 9         | 3.73%   |
| 0x306c3    | 9         | 3.73%   |
| 0x806ea    | 7         | 2.9%    |
| 0x206c2    | 6         | 2.49%   |
| 0x706e5    | 5         | 2.07%   |
| 0x206d7    | 5         | 2.07%   |
| 0x506e3    | 4         | 1.66%   |
| 0x906ea    | 3         | 1.24%   |
| 0x6f6      | 3         | 1.24%   |
| 0x30678    | 3         | 1.24%   |
| 0x10676    | 3         | 1.24%   |
| 0xa0655    | 2         | 0.83%   |
| 0x6fd      | 2         | 0.83%   |
| 0x106a5    | 2         | 0.83%   |
| 0xa0671    | 1         | 0.41%   |
| 0xa0660    | 1         | 0.41%   |
| 0xa0652    | 1         | 0.41%   |
| 0x906e9    | 1         | 0.41%   |
| 0x806eb    | 1         | 0.41%   |
| 0x706a1    | 1         | 0.41%   |
| 0x6fb      | 1         | 0.41%   |
| 0x406c4    | 1         | 0.41%   |
| 0x20652    | 1         | 0.41%   |
| 0x08701021 | 1         | 0.41%   |
| 0x08608103 | 1         | 0.41%   |
| 0x08600106 | 1         | 0.41%   |
| 0x08600104 | 1         | 0.41%   |
| 0x0800820d | 1         | 0.41%   |
| 0x0700010f | 1         | 0.41%   |
| 0x0600611a | 1         | 0.41%   |
| 0x05000119 | 1         | 0.41%   |
| 0x010000b6 | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 43        | 18.45%  |
| SandyBridge   | 28        | 12.02%  |
| Haswell       | 22        | 9.44%   |
| Westmere      | 21        | 9.01%   |
| Skylake       | 19        | 8.15%   |
| IvyBridge     | 18        | 7.73%   |
| Penryn        | 15        | 6.44%   |
| Broadwell     | 14        | 6.01%   |
| TigerLake     | 13        | 5.58%   |
| Core          | 6         | 2.58%   |
| Zen 2         | 5         | 2.15%   |
| IceLake       | 5         | 2.15%   |
| Silvermont    | 4         | 1.72%   |
| CometLake     | 4         | 1.72%   |
| Nehalem       | 3         | 1.29%   |
| Unknown       | 3         | 1.29%   |
| Zen+          | 2         | 0.86%   |
| K10           | 2         | 0.86%   |
| Zen           | 1         | 0.43%   |
| P6            | 1         | 0.43%   |
| Jaguar        | 1         | 0.43%   |
| Goldmont plus | 1         | 0.43%   |
| Excavator     | 1         | 0.43%   |
| Bobcat        | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 178       | 64.73%  |
| Nvidia                     | 51        | 18.55%  |
| AMD                        | 44        | 16%     |
| Matrox Electronics Systems | 2         | 0.73%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 18        | 6.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 15        | 5.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 13        | 4.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 12        | 4.24%   |
| Intel HD Graphics 5500                                                                | 12        | 4.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 11        | 3.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 11        | 3.89%   |
| Intel HD Graphics 620                                                                 | 9         | 3.18%   |
| Intel Core Processor Integrated Graphics Controller                                   | 9         | 3.18%   |
| Intel UHD Graphics 620                                                                | 7         | 2.47%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 7         | 2.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 6         | 2.12%   |
| Nvidia GT218 [GeForce 210]                                                            | 5         | 1.77%   |
| Intel HD Graphics 530                                                                 | 5         | 1.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 5         | 1.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 5         | 1.77%   |
| Nvidia GP108M [GeForce MX230]                                                         | 4         | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 1.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 4         | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 3         | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 3         | 1.06%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 3         | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 3         | 1.06%   |
| Intel HD Graphics 615                                                                 | 3         | 1.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 3         | 1.06%   |
| AMD Renoir                                                                            | 3         | 1.06%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 0.71%   |
| Nvidia GT218M [NVS 3100M]                                                             | 2         | 0.71%   |
| Nvidia GT218 [GeForce 310]                                                            | 2         | 0.71%   |
| Nvidia GM206 [GeForce GTX 960]                                                        | 2         | 0.71%   |
| Nvidia GF119 [GeForce GT 610]                                                         | 2         | 0.71%   |
| Nvidia GF108 [GeForce GT 730]                                                         | 2         | 0.71%   |
| Matrox Electronics Systems MGA G200EH                                                 | 2         | 0.71%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                             | 2         | 0.71%   |
| Intel HD Graphics 5300                                                                | 2         | 0.71%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 2         | 0.71%   |
| Intel 82Q35 Express Integrated Graphics Controller                                    | 2         | 0.71%   |
| AMD Topaz PRO [Radeon R5 M255]                                                        | 2         | 0.71%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                 | 2         | 0.71%   |
| Nvidia TU117M [GeForce MX450]                                                         | 1         | 0.35%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                    | 1         | 0.35%   |
| Nvidia GP108M [GeForce MX330]                                                         | 1         | 0.35%   |
| Nvidia GP108M [GeForce MX250]                                                         | 1         | 0.35%   |
| Nvidia GP108M [GeForce MX150]                                                         | 1         | 0.35%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 0.35%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                 | 1         | 0.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 1         | 0.35%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                   | 1         | 0.35%   |
| Nvidia GM108M [GeForce MX130]                                                         | 1         | 0.35%   |
| Nvidia GM108M [GeForce MX110]                                                         | 1         | 0.35%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 0.35%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 1         | 0.35%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 0.35%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 1         | 0.35%   |
| Nvidia GM107GLM [Quadro M2000M]                                                       | 1         | 0.35%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 1         | 0.35%   |
| Nvidia GM107GL [Quadro K620]                                                          | 1         | 0.35%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                     | 1         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 139       | 58.9%   |
| 1 x Nvidia     | 25        | 10.59%  |
| 1 x AMD        | 24        | 10.17%  |
| Intel + Nvidia | 23        | 9.75%   |
| Intel + AMD    | 16        | 6.78%   |
| Other          | 2         | 0.85%   |
| 2 x AMD        | 2         | 0.85%   |
| 1 x Matrox     | 2         | 0.85%   |
| AMD + Nvidia   | 2         | 0.85%   |
| 2 x Nvidia     | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 204       | 85.36%  |
| Proprietary | 24        | 10.04%  |
| Unknown     | 11        | 4.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 166       | 69.46%  |
| 1.01-2.0   | 33        | 13.81%  |
| 0.01-0.5   | 17        | 7.11%   |
| 3.01-4.0   | 10        | 4.18%   |
| 0.51-1.0   | 9         | 3.77%   |
| 5.01-6.0   | 2         | 0.84%   |
| 2.01-3.0   | 1         | 0.42%   |
| 8.01-16.0  | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 46        | 20.72%  |
| Chimei Innolux          | 33        | 14.86%  |
| AU Optronics            | 27        | 12.16%  |
| BOE                     | 22        | 9.91%   |
| Samsung Electronics     | 18        | 8.11%   |
| Hewlett-Packard         | 18        | 8.11%   |
| Dell                    | 17        | 7.66%   |
| Chi Mei Optoelectronics | 5         | 2.25%   |
| Unknown                 | 4         | 1.8%    |
| Lenovo                  | 4         | 1.8%    |
| Acer                    | 4         | 1.8%    |
| Goldstar                | 3         | 1.35%   |
| Apple                   | 3         | 1.35%   |
| Sony                    | 2         | 0.9%    |
| Sharp                   | 2         | 0.9%    |
| NEC Computers           | 2         | 0.9%    |
| LG Philips              | 2         | 0.9%    |
| KDC                     | 2         | 0.9%    |
| ViewSonic               | 1         | 0.45%   |
| Planar                  | 1         | 0.45%   |
| Philips                 | 1         | 0.45%   |
| PANDA                   | 1         | 0.45%   |
| LPL                     | 1         | 0.45%   |
| LGD                     | 1         | 0.45%   |
| Hitachi                 | 1         | 0.45%   |
| HannStar                | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 2.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 2.21%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch           | 4         | 1.77%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 3         | 1.33%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch            | 3         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.33%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 3         | 1.33%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 3         | 1.33%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2         | 0.88%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.88%   |
| Samsung Electronics LCD Monitor SDC544B 1600x900 309x174mm 14.0-inch  | 2         | 0.88%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 2         | 0.88%   |
| LG Display LCD Monitor LGD052F 1920x1080 344x194mm 15.5-inch          | 2         | 0.88%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 0.88%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch           | 2         | 0.88%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                  | 2         | 0.88%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 2         | 0.88%   |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                     | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch      | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1332 1366x768 293x165mm 13.2-inch       | 2         | 0.88%   |
| BOE LCD Monitor BOE08C6 1920x1080 344x194mm 15.5-inch                 | 2         | 0.88%   |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch                 | 2         | 0.88%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO5024 1280x800 286x178mm 13.3-inch         | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch         | 2         | 0.88%   |
| ViewSonic LCD Monitor VA2451 SERIES 1920x1080                         | 1         | 0.44%   |
| Unknown LCD Monitor ITE DP2VGA V221 1680x1050                         | 1         | 0.44%   |
| Unknown LCD Monitor DellSP2008WFP 1680x1050                           | 1         | 0.44%   |
| Sony TV SNYAC03 1360x768                                              | 1         | 0.44%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.44%   |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM0586 1920x1200 518x324mm 24.1-inch  | 1         | 0.44%   |
| Samsung Electronics SMBX2240 SAM0684 1920x1080 477x268mm 21.5-inch    | 1         | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.44%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 0.44%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC414A 1920x1080 294x165mm 13.3-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch  | 1         | 0.44%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 1         | 0.44%   |
| Planar PL1500 PLN1500 1024x768 300x230mm 14.9-inch                    | 1         | 0.44%   |
| Philips 150P PHL0814 1024x768 307x230mm 15.1-inch                     | 1         | 0.44%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 1         | 0.44%   |
| NEC Computers LCD1770NX NEC6665 1280x1024 338x270mm 17.0-inch         | 1         | 0.44%   |
| NEC Computers EA244WMi NEC68D6 1920x1200 519x324mm 24.1-inch          | 1         | 0.44%   |
| LPL LCD Monitor 1440x900                                              | 1         | 0.44%   |
| LGD LCD Monitor 1920x1080                                             | 1         | 0.44%   |
| LG Philips LCD Monitor LPL0201 1280x800 331x207mm 15.4-inch           | 1         | 0.44%   |
| LG Philips LCD Monitor LGP9C1C 1024x768 285x214mm 14.0-inch           | 1         | 0.44%   |
| LG Display LP156WH2-TLR2 LGD027D 1366x768 344x194mm 15.5-inch         | 1         | 0.44%   |
| LG Display LCD Monitor LGD0684 1920x1080 344x194mm 15.5-inch          | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 89        | 41.2%   |
| 1366x768 (WXGA)    | 67        | 31.02%  |
| 1600x900 (HD+)     | 8         | 3.7%    |
| 1280x1024 (SXGA)   | 8         | 3.7%    |
| 1680x1050 (WSXGA+) | 7         | 3.24%   |
| 1280x800 (WXGA)    | 6         | 2.78%   |
| 3840x2160 (4K)     | 5         | 2.31%   |
| 1920x1200 (WUXGA)  | 5         | 2.31%   |
| 1440x900 (WXGA+)   | 4         | 1.85%   |
| 1024x768 (XGA)     | 4         | 1.85%   |
| 3440x1440          | 3         | 1.39%   |
| 2288x1287          | 2         | 0.93%   |
| Unknown            | 2         | 0.93%   |
| 3640x1920          | 1         | 0.46%   |
| 3520x1080          | 1         | 0.46%   |
| 2880x1800          | 1         | 0.46%   |
| 2560x1600          | 1         | 0.46%   |
| 2160x1440          | 1         | 0.46%   |
| 1360x768           | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 84        | 38.18%  |
| 14      | 32        | 14.55%  |
| 13      | 25        | 11.36%  |
| 17      | 11        | 5%      |
| 24      | 10        | 4.55%   |
| 21      | 10        | 4.55%   |
| Unknown | 10        | 4.55%   |
| 23      | 6         | 2.73%   |
| 19      | 6         | 2.73%   |
| 12      | 6         | 2.73%   |
| 27      | 4         | 1.82%   |
| 22      | 4         | 1.82%   |
| 11      | 4         | 1.82%   |
| 142     | 2         | 0.91%   |
| 40      | 2         | 0.91%   |
| 72      | 1         | 0.45%   |
| 20      | 1         | 0.45%   |
| 18      | 1         | 0.45%   |
| 10      | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 128       | 58.72%  |
| 201-300        | 25        | 11.47%  |
| 501-600        | 19        | 8.72%   |
| 401-500        | 18        | 8.26%   |
| 351-400        | 13        | 5.96%   |
| Unknown        | 10        | 4.59%   |
| More than 2000 | 2         | 0.92%   |
| 801-900        | 2         | 0.92%   |
| 1501-2000      | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 163       | 78.37%  |
| 16/10   | 20        | 9.62%   |
| Unknown | 10        | 4.81%   |
| 5/4     | 8         | 3.85%   |
| 4/3     | 4         | 1.92%   |
| 1.00    | 2         | 0.96%   |
| 3/2     | 1         | 0.48%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch?? | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 83        | 37.9%   |
| 81-90          | 44        | 20.09%  |
| 201-250        | 23        | 10.5%   |
| 71-80          | 11        | 5.02%   |
| 151-200        | 10        | 4.57%   |
| Unknown        | 10        | 4.57%   |
| 61-70          | 6         | 2.74%   |
| 141-150        | 5         | 2.28%   |
| 121-130        | 5         | 2.28%   |
| 51-60          | 4         | 1.83%   |
| 301-350        | 4         | 1.83%   |
| More than 1000 | 3         | 1.37%   |
| 251-300        | 3         | 1.37%   |
| 91-100         | 3         | 1.37%   |
| 131-140        | 2         | 0.91%   |
| 501-1000       | 2         | 0.91%   |
| 41-50          | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 76        | 35.02%  |
| 101-120       | 71        | 32.72%  |
| 51-100        | 46        | 21.2%   |
| Unknown       | 10        | 4.61%   |
| More than 240 | 6         | 2.76%   |
| 161-240       | 5         | 2.3%    |
| 1-50          | 3         | 1.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 198       | 83.9%   |
| 2     | 20        | 8.47%   |
| 0     | 17        | 7.2%    |
| 3     | 1         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 155       | 41.44%  |
| Realtek Semiconductor           | 109       | 29.14%  |
| Broadcom                        | 36        | 9.63%   |
| Qualcomm Atheros                | 18        | 4.81%   |
| Ralink Technology               | 9         | 2.41%   |
| Broadcom Limited                | 6         | 1.6%    |
| MediaTek                        | 5         | 1.34%   |
| Marvell Technology Group        | 4         | 1.07%   |
| Hewlett-Packard                 | 4         | 1.07%   |
| D-Link                          | 4         | 1.07%   |
| Sierra Wireless                 | 3         | 0.8%    |
| Samsung Electronics             | 3         | 0.8%    |
| Ralink                          | 3         | 0.8%    |
| Huawei Technologies             | 3         | 0.8%    |
| Nvidia                          | 2         | 0.53%   |
| Dell                            | 2         | 0.53%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.27%   |
| VIA Technologies                | 1         | 0.27%   |
| Qualcomm Atheros Communications | 1         | 0.27%   |
| Qualcomm                        | 1         | 0.27%   |
| QLogic                          | 1         | 0.27%   |
| Emulex                          | 1         | 0.27%   |
| ASIX Electronics                | 1         | 0.27%   |
| 3Com                            | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 71        | 15.43%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 28        | 6.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 16        | 3.48%   |
| Intel Wireless 7265                                                  | 14        | 3.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 14        | 3.04%   |
| Intel Wi-Fi 6 AX201                                                  | 12        | 2.61%   |
| Intel Wireless 3165                                                  | 10        | 2.17%   |
| Intel Ethernet Connection (3) I218-LM                                | 10        | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 10        | 2.17%   |
| Ralink MT7601U Wireless Adapter                                      | 9         | 1.96%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                     | 9         | 1.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 8         | 1.74%   |
| Intel Ethernet Connection I217-LM                                    | 8         | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 7         | 1.52%   |
| Intel Wireless 8260                                                  | 7         | 1.52%   |
| Intel Wireless 7260                                                  | 7         | 1.52%   |
| Intel 82577LM Gigabit Network Connection                             | 7         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 6         | 1.3%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                 | 6         | 1.3%    |
| Intel Ultimate N WiFi Link 5300                                      | 5         | 1.09%   |
| Intel Centrino Advanced-N 6200                                       | 5         | 1.09%   |
| Intel 82567LM Gigabit Network Connection                             | 5         | 1.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 4         | 0.87%   |
| Intel Ethernet Connection I219-LM                                    | 4         | 0.87%   |
| Intel Ethernet Connection I218-LM                                    | 4         | 0.87%   |
| Intel Centrino Ultimate-N 6300                                       | 4         | 0.87%   |
| Intel Centrino Advanced-N 6235                                       | 4         | 0.87%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 4         | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 4         | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 3         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 0.65%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 3         | 0.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 0.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 0.65%   |
| MediaTek TECNO SPARK 3                                               | 3         | 0.65%   |
| Intel Ethernet Connection (2) I219-V                                 | 3         | 0.65%   |
| Intel 82579V Gigabit Network Connection                              | 3         | 0.65%   |
| Intel 82574L Gigabit Network Connection                              | 3         | 0.65%   |
| Intel 82566DM-2 Gigabit Network Connection                           | 3         | 0.65%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                    | 3         | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 3         | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                        | 3         | 0.65%   |
| Sierra Wireless EM7345 4G LTE                                        | 2         | 0.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2         | 0.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 0.43%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 2         | 0.43%   |
| Realtek RTL8125 2.5GbE Controller                                    | 2         | 0.43%   |
| Nvidia MCP51 Ethernet Controller                                     | 2         | 0.43%   |
| Intel Wireless-AC 9260                                               | 2         | 0.43%   |
| Intel Wireless 8265 / 8275                                           | 2         | 0.43%   |
| Intel Wireless 3160                                                  | 2         | 0.43%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 0.43%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 0.43%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 2         | 0.43%   |
| Intel Ethernet Connection I219-V                                     | 2         | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                                | 2         | 0.43%   |
| Intel Ethernet Connection (11) I219-LM                               | 2         | 0.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 0.43%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                 | 2         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 118       | 56.46%  |
| Realtek Semiconductor           | 31        | 14.83%  |
| Qualcomm Atheros                | 16        | 7.66%   |
| Broadcom                        | 15        | 7.18%   |
| Ralink Technology               | 9         | 4.31%   |
| D-Link                          | 4         | 1.91%   |
| Sierra Wireless                 | 3         | 1.44%   |
| Ralink                          | 3         | 1.44%   |
| Marvell Technology Group        | 2         | 0.96%   |
| Hewlett-Packard                 | 2         | 0.96%   |
| Dell                            | 2         | 0.96%   |
| Broadcom Limited                | 2         | 0.96%   |
| Qualcomm Atheros Communications | 1         | 0.48%   |
| MediaTek                        | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                  | 14        | 6.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 14        | 6.6%    |
| Intel Wi-Fi 6 AX201                                                  | 12        | 5.66%   |
| Intel Wireless 3165                                                  | 10        | 4.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 10        | 4.72%   |
| Ralink MT7601U Wireless Adapter                                      | 9         | 4.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 8         | 3.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 7         | 3.3%    |
| Intel Wireless 8260                                                  | 7         | 3.3%    |
| Intel Wireless 7260                                                  | 7         | 3.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 6         | 2.83%   |
| Intel Ultimate N WiFi Link 5300                                      | 5         | 2.36%   |
| Intel Centrino Advanced-N 6200                                       | 5         | 2.36%   |
| Intel Centrino Ultimate-N 6300                                       | 4         | 1.89%   |
| Intel Centrino Advanced-N 6235                                       | 4         | 1.89%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 4         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 4         | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 1.42%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3         | 1.42%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 3         | 1.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 3         | 1.42%   |
| Broadcom BCM43142 802.11b/g/n                                        | 3         | 1.42%   |
| Sierra Wireless EM7345 4G LTE                                        | 2         | 0.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2         | 0.94%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 2         | 0.94%   |
| Intel Wireless-AC 9260                                               | 2         | 0.94%   |
| Intel Wireless 8265 / 8275                                           | 2         | 0.94%   |
| Intel Wireless 3160                                                  | 2         | 0.94%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 0.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 0.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 2         | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 0.94%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                 | 2         | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 0.94%   |
| HP lt4112 Gobi 4G Module Network Device                              | 2         | 0.94%   |
| Dell Hub of E-Port Replicator                                        | 2         | 0.94%   |
| Sierra Wireless EM7305                                               | 1         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.47%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1         | 0.47%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                               | 1         | 0.47%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                 | 1         | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 0.47%   |
| Realtek 802.11ac NIC                                                 | 1         | 0.47%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 1         | 0.47%   |
| Qualcomm Atheros AR9271 802.11n                                      | 1         | 0.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 1         | 0.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1         | 0.47%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                    | 1         | 0.47%   |
| Marvell Group 88W8361 [TopDog] 802.11n Wireless                      | 1         | 0.47%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 1         | 0.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 0.47%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 0.47%   |
| Intel Centrino Wireless-N 6150                                       | 1         | 0.47%   |
| Intel Centrino Wireless-N 2230                                       | 1         | 0.47%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 1         | 0.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 1         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 96        | 40.17%  |
| Realtek Semiconductor      | 93        | 38.91%  |
| Broadcom                   | 22        | 9.21%   |
| MediaTek                   | 4         | 1.67%   |
| Broadcom Limited           | 4         | 1.67%   |
| Samsung Electronics        | 3         | 1.26%   |
| Huawei Technologies        | 3         | 1.26%   |
| Qualcomm Atheros           | 2         | 0.84%   |
| Nvidia                     | 2         | 0.84%   |
| Marvell Technology Group   | 2         | 0.84%   |
| ZTE WCDMA Technologies MSM | 1         | 0.42%   |
| VIA Technologies           | 1         | 0.42%   |
| Qualcomm                   | 1         | 0.42%   |
| QLogic                     | 1         | 0.42%   |
| Hewlett-Packard            | 1         | 0.42%   |
| Emulex                     | 1         | 0.42%   |
| ASIX Electronics           | 1         | 0.42%   |
| 3Com                       | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 71        | 28.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 28        | 11.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 16        | 6.48%   |
| Intel Ethernet Connection (3) I218-LM                                          | 10        | 4.05%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 9         | 3.64%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 3.24%   |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 2.83%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 6         | 2.43%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 1.62%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.62%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.62%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 1.21%   |
| MediaTek TECNO SPARK 3                                                         | 3         | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.21%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 1.21%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.21%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3         | 1.21%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.21%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.81%   |
| Nvidia MCP51 Ethernet Controller                                               | 2         | 0.81%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.81%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.81%   |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 2         | 0.81%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.81%   |
| Huawei E353/E3131                                                              | 2         | 0.81%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 2         | 0.81%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                                 | 1         | 0.4%    |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 1         | 0.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.4%    |
| Qualcomm Redmi 9T                                                              | 1         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.4%    |
| QLogic cLOM8214 1/10GbE Controller                                             | 1         | 0.4%    |
| MediaTek TECNO SPARK 6 Go                                                      | 1         | 0.4%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.4%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.4%    |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.4%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.4%    |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.4%    |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.4%    |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.4%    |
| Intel 82578DM Gigabit Network Connection                                       | 1         | 0.4%    |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.4%    |
| Intel 82575GB Gigabit Network Connection                                       | 1         | 0.4%    |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.4%    |
| Huawei Ideos (tethering mode)                                                  | 1         | 0.4%    |
| HP lt4211 Gobi 4G Module                                                       | 1         | 0.4%    |
| Emulex OneConnect 10Gb NIC (be3)                                               | 1         | 0.4%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 1         | 0.4%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 1         | 0.4%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 1         | 0.4%    |
| Broadcom NetXtreme BCM5715 Gigabit Ethernet                                    | 1         | 0.4%    |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                                | 1         | 0.4%    |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.4%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 0.4%    |
| Broadcom Limited NetXtreme BCM5722 Gigabit Ethernet PCI Express                | 1         | 0.4%    |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 215       | 51.93%  |
| WiFi     | 198       | 47.83%  |
| Modem    | 1         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 168       | 73.04%  |
| Ethernet | 62        | 26.96%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 162       | 69.23%  |
| 1     | 57        | 24.36%  |
| 3     | 6         | 2.56%   |
| 4     | 4         | 1.71%   |
| 0     | 4         | 1.71%   |
| 8     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 226       | 96.58%  |
| Yes  | 8         | 3.42%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 79        | 55.24%  |
| Realtek Semiconductor           | 14        | 9.79%   |
| Qualcomm Atheros Communications | 11        | 7.69%   |
| Broadcom                        | 11        | 7.69%   |
| Cambridge Silicon Radio         | 10        | 6.99%   |
| Dell                            | 4         | 2.8%    |
| Ralink                          | 3         | 2.1%    |
| Foxconn / Hon Hai               | 3         | 2.1%    |
| IMC Networks                    | 2         | 1.4%    |
| Hewlett-Packard                 | 2         | 1.4%    |
| Marvell Semiconductor           | 1         | 0.7%    |
| Lite-On Technology              | 1         | 0.7%    |
| Apple                           | 1         | 0.7%    |
| AboCom Systems                  | 1         | 0.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 40        | 27.97%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 12.59%  |
| Intel Bluetooth Device                                                              | 15        | 10.49%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 6.99%   |
| Realtek Bluetooth Radio                                                             | 8         | 5.59%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 4.9%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 3.5%    |
| Broadcom HP Portable SoftSailing                                                    | 4         | 2.8%    |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.1%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 2.1%    |
| Intel AX200 Bluetooth                                                               | 2         | 1.4%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.4%    |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.4%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.4%    |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.7%    |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.7%    |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.7%    |
| IMC Networks Wireless_Device                                                        | 1         | 0.7%    |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.7%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.7%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.7%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.7%    |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.7%    |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.7%    |
| Broadcom HP Portable Valentine                                                      | 1         | 0.7%    |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.7%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.7%    |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.7%    |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.7%    |
| AboCom Systems AboCom Bluetooth Device                                              | 1         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 212       | 74.91%  |
| Nvidia                 | 32        | 11.31%  |
| AMD                    | 25        | 8.83%   |
| Generalplus Technology | 5         | 1.77%   |
| Logitech               | 2         | 0.71%   |
| C-Media Electronics    | 2         | 0.71%   |
| Texas Instruments      | 1         | 0.35%   |
| Realtek Semiconductor  | 1         | 0.35%   |
| Creative Labs          | 1         | 0.35%   |
| Apple                  | 1         | 0.35%   |
| Unknown                | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 33        | 9.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 6.34%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 19        | 5.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 16        | 4.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 14        | 4.23%   |
| Intel Broadwell-U Audio Controller                                         | 14        | 4.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 13        | 3.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 3.93%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 3.32%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 3.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10        | 3.02%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10        | 3.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 3.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 3.02%   |
| Nvidia High Definition Audio Controller                                    | 9         | 2.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.51%   |
| Nvidia GF119 HDMI Audio Controller                                         | 5         | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.51%   |
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 1.51%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 1.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 1.21%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.21%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 1.21%   |
| Generalplus Technology IMYB 7.1 Channel                                    | 4         | 1.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 1.21%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 0.91%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 0.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 0.91%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3         | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.6%    |
| Nvidia MCP51 High Definition Audio                                         | 2         | 0.6%    |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.6%    |
| Logitech Headset H340                                                      | 2         | 0.6%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.6%    |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 2         | 0.6%    |
| Intel 200 Series PCH HD Audio                                              | 2         | 0.6%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.6%    |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 0.6%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 0.6%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 0.6%    |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 0.6%    |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.3%    |
| Realtek Semiconductor USB Audio                                            | 1         | 0.3%    |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 0.3%    |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.3%    |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.3%    |
| Intel CM238 HD Audio Controller                                            | 1         | 0.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.3%    |
| Intel Audio device                                                         | 1         | 0.3%    |
| Generalplus Technology USB Microphone                                      | 1         | 0.3%    |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1         | 0.3%    |
| C-Media Electronics USB Audio Device                                       | 1         | 0.3%    |
| C-Media Electronics CM108 Audio Controller                                 | 1         | 0.3%    |
| Apple Audio Device                                                         | 1         | 0.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 29.37%  |
| SK hynix            | 40        | 27.97%  |
| Micron Technology   | 15        | 10.49%  |
| A-DATA Technology   | 8         | 5.59%   |
| Transcend           | 6         | 4.2%    |
| Unknown             | 5         | 3.5%    |
| Kingston            | 5         | 3.5%    |
| Elpida              | 4         | 2.8%    |
| Team                | 3         | 2.1%    |
| Crucial             | 3         | 2.1%    |
| Unknown (2C0B)      | 2         | 1.4%    |
| Spectek             | 2         | 1.4%    |
| Lexar               | 2         | 1.4%    |
| Unknown (768A)      | 1         | 0.7%    |
| TwinMOS             | 1         | 0.7%    |
| Toshiba-0098        | 1         | 0.7%    |
| Ramaxel Technology  | 1         | 0.7%    |
| Hikvision           | 1         | 0.7%    |
| Axiom               | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| A-DATA RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 5         | 3.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 3         | 1.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 3         | 1.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 3         | 1.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 3         | 1.85%   |
| Samsung RAM M393B2G70BH0-YH9 16GB DIMM DDR3 1333MT/s            | 3         | 1.85%   |
| Samsung RAM M393B2G70BH0-CK0 16GB DIMM DDR3 1600MT/s            | 3         | 1.85%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s            | 3         | 1.85%   |
| Unknown (2C0B) RAM Module 16GB DIMM DDR4 2667MT/s               | 2         | 1.23%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s           | 2         | 1.23%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                 | 2         | 1.23%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 1.23%   |
| SK hynix RAM HMT42GR7AFR4A-PB 16GB DIMM DDR3 1600MT/s           | 2         | 1.23%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 2         | 1.23%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                  | 2         | 1.23%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 2         | 1.23%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s           | 2         | 1.23%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.23%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s           | 2         | 1.23%   |
| Lexar RAM LD4AS016G-H2666G 16384MB SODIMM DDR4 2667MT/s         | 2         | 1.23%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 0.62%   |
| Unknown RAM Module 4GB DIMM SDRAM 1066MT/s                      | 1         | 0.62%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.62%   |
| Unknown RAM Module 2GB DIMM SDRAM 1066MT/s                      | 1         | 0.62%   |
| Unknown RAM Module 2048MB DIMM DDR3 1067MT/s                    | 1         | 0.62%   |
| Unknown RAM DDR3 1600 8G 8GB SODIMM DDR3 1333MT/s               | 1         | 0.62%   |
| Unknown (768A) RAM Module 16384MB SODIMM DDR4 2667MT/s          | 1         | 0.62%   |
| TwinMOS RAM CT16G4SFS8266.C8FB 16GB SODIMM DDR4 3200MT/s        | 1         | 0.62%   |
| Transcend RAM Module 8GB SODIMM DDR4 3200MT/s                   | 1         | 0.62%   |
| Transcend RAM Module 8192MB SODIMM DDR4 3200MT/s                | 1         | 0.62%   |
| Transcend RAM Module 8192MB SODIMM DDR4 2400MT/s                | 1         | 0.62%   |
| Transcend RAM Module 16384MB SODIMM DDR4 2667MT/s               | 1         | 0.62%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s           | 1         | 0.62%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s             | 1         | 0.62%   |
| Toshiba-0098 RAM 9965516-069.A00LF 8192MB DIMM DDR3 1067MT/s    | 1         | 0.62%   |
| Toshiba-0098 RAM 9965516-057.A00LF 8192MB DIMM DDR3 1067MT/s    | 1         | 0.62%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s           | 1         | 0.62%   |
| Spectek RAM Module 8GB Row Of Chips LPDDR3 1600MT/s             | 1         | 0.62%   |
| Spectek RAM Module 8192MB Row Of Chips LPDDR3 1600MT/s          | 1         | 0.62%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                 | 1         | 0.62%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 0.62%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s                 | 1         | 0.62%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                   | 1         | 0.62%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                      | 1         | 0.62%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1333MT/s                   | 1         | 0.62%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s            | 1         | 0.62%   |
| SK hynix RAM HMT451B6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 1         | 0.62%   |
| SK hynix RAM HMT42GR7AFR4A-PB 16GB DIMM DDR3 1067MT/s           | 1         | 0.62%   |
| SK hynix RAM HMT42GR7AFR4A 16GB DIMM DDR3 1600MT/s              | 1         | 0.62%   |
| SK hynix RAM HMT41GU6AFR8A-PB 8192MB DIMM DDR3 1600MT/s         | 1         | 0.62%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s       | 1         | 0.62%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 1         | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1600MT/s          | 1         | 0.62%   |
| SK hynix RAM HMT325U7BFR8C-H9 2048MB DIMM DDR3 1333MT/s         | 1         | 0.62%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s          | 1         | 0.62%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s          | 1         | 0.62%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s            | 1         | 0.62%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s          | 1         | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s | 1         | 0.62%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 49        | 45.79%  |
| DDR3   | 46        | 42.99%  |
| LPDDR3 | 4         | 3.74%   |
| SDRAM  | 3         | 2.8%    |
| LPDDR4 | 3         | 2.8%    |
| DDR2   | 1         | 0.93%   |
| DDR    | 1         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 72        | 68.57%  |
| DIMM         | 26        | 24.76%  |
| Row Of Chips | 7         | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 40        | 34.19%  |
| 4096  | 31        | 26.5%   |
| 16384 | 28        | 23.93%  |
| 2048  | 15        | 12.82%  |
| 32768 | 3         | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 36        | 29.03%  |
| 2667  | 29        | 23.39%  |
| 3200  | 12        | 9.68%   |
| 1333  | 11        | 8.87%   |
| 2133  | 9         | 7.26%   |
| 2400  | 8         | 6.45%   |
| 1334  | 5         | 4.03%   |
| 1067  | 3         | 2.42%   |
| 4267  | 2         | 1.61%   |
| 1066  | 2         | 1.61%   |
| 4199  | 1         | 0.81%   |
| 2666  | 1         | 0.81%   |
| 2200  | 1         | 0.81%   |
| 2000  | 1         | 0.81%   |
| 1867  | 1         | 0.81%   |
| 1866  | 1         | 0.81%   |
| 800   | 1         | 0.81%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Plustek | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Plustek OpticSlim 1200 Scanner | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 40        | 25.48%  |
| Microdia                               | 20        | 12.74%  |
| Cheng Uei Precision Industry (Foxlink) | 15        | 9.55%   |
| Sunplus Innovation Technology          | 14        | 8.92%   |
| Realtek Semiconductor                  | 11        | 7.01%   |
| Lite-On Technology                     | 8         | 5.1%    |
| Acer                                   | 7         | 4.46%   |
| Suyin                                  | 5         | 3.18%   |
| Ricoh                                  | 5         | 3.18%   |
| Quanta                                 | 5         | 3.18%   |
| IMC Networks                           | 5         | 3.18%   |
| Syntek                                 | 3         | 1.91%   |
| Silicon Motion                         | 3         | 1.91%   |
| Apple                                  | 3         | 1.91%   |
| Z-Star Microelectronics                | 2         | 1.27%   |
| Samsung Electronics                    | 1         | 0.64%   |
| Primax Electronics                     | 1         | 0.64%   |
| Pixart Imaging                         | 1         | 0.64%   |
| OmniVision Technologies                | 1         | 0.64%   |
| Microsoft                              | 1         | 0.64%   |
| MacroSilicon                           | 1         | 0.64%   |
| Luxvisions Innotech Limited            | 1         | 0.64%   |
| Logitech                               | 1         | 0.64%   |
| Lenovo                                 | 1         | 0.64%   |
| DigiTech                               | 1         | 0.64%   |
| 8SSC20F27145V1SR1BX02P8                | 1         | 0.64%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 10        | 6.33%   |
| Chicony HP HD Camera                                                       | 9         | 5.7%    |
| Chicony Integrated Camera                                                  | 8         | 5.06%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 7         | 4.43%   |
| Sunplus Integrated_Webcam_HD                                               | 6         | 3.8%    |
| Realtek Integrated_Webcam_HD                                               | 4         | 2.53%   |
| Microdia Integrated Webcam                                                 | 4         | 2.53%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 4         | 2.53%   |
| Acer Integrated Camera                                                     | 4         | 2.53%   |
| Sunplus HP HD Webcam [Fixed]                                               | 3         | 1.9%    |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 1.9%    |
| Realtek Integrated Webcam                                                  | 3         | 1.9%    |
| Lite-On HP HD Webcam                                                       | 3         | 1.9%    |
| Lite-On HP HD Camera                                                       | 3         | 1.9%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 1.9%    |
| Chicony USB 2.0Camera                                                      | 3         | 1.9%    |
| Apple iPhone 5/5C/5S/6/SE                                                  | 3         | 1.9%    |
| Z-Star Venus USB2.0 Camera                                                 | 2         | 1.27%   |
| Syntek Integrated Camera                                                   | 2         | 1.27%   |
| Sunplus HP Universal Camera                                                | 2         | 1.27%   |
| Silicon Motion 300k Pixel Camera                                           | 2         | 1.27%   |
| Realtek USB2.0 camera                                                      | 2         | 1.27%   |
| Quanta HP HD Camera                                                        | 2         | 1.27%   |
| Microdia Integrated_Webcam_FHD                                             | 2         | 1.27%   |
| Lite-On Integrated Camera                                                  | 2         | 1.27%   |
| IMC Networks Integrated Camera                                             | 2         | 1.27%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.27%   |
| Chicony Integrated HP HD Webcam                                            | 2         | 1.27%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 1.27%   |
| Chicony HP Truevision HD                                                   | 2         | 1.27%   |
| Chicony EasyCamera                                                         | 2         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 2         | 1.27%   |
| Syntek USB 2.0 PC Cam                                                      | 1         | 0.63%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 1         | 0.63%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 0.63%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 0.63%   |
| Suyin HP TrueVision HD                                                     | 1         | 0.63%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.63%   |
| Sunplus Laptop Integrated Webcam HD                                        | 1         | 0.63%   |
| Sunplus Integrated Webcam                                                  | 1         | 0.63%   |
| Sunplus HP Wide Vision HD                                                  | 1         | 0.63%   |
| Silicon Motion ATIV Real HD Camera                                         | 1         | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 1         | 0.63%   |
| Ricoh Integrated Webcam                                                    | 1         | 0.63%   |
| Ricoh HD Webcam                                                            | 1         | 0.63%   |
| Realtek Integrated Webcam_HD                                               | 1         | 0.63%   |
| Realtek HP Truevision HD                                                   | 1         | 0.63%   |
| Quanta VGA WebCam                                                          | 1         | 0.63%   |
| Quanta HP Wide Vision HD Camera                                            | 1         | 0.63%   |
| Quanta HP TrueVision HD Camera                                             | 1         | 0.63%   |
| Primax HP HD Webcam [Fixed]                                                | 1         | 0.63%   |
| Pixart Imaging USB_2.0_Webcam                                              | 1         | 0.63%   |
| OmniVision Monitor Integrated Webcam                                       | 1         | 0.63%   |
| Microsoft LifeCam Rear                                                     | 1         | 0.63%   |
| Microsoft LifeCam Front                                                    | 1         | 0.63%   |
| Microdia Webcam                                                            | 1         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 1         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                     | 1         | 0.63%   |
| Microdia Laptop Integrated Webcam HD (Composite Device)                    | 1         | 0.63%   |
| MacroSilicon MiraBox Capture                                               | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 36        | 69.23%  |
| Synaptics                  | 7         | 13.46%  |
| AuthenTec                  | 4         | 7.69%   |
| Shenzhen Goodix Technology | 3         | 5.77%   |
| Upek                       | 2         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 28.85%  |
| Validity Sensors VFS491                                                    | 7         | 13.46%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 13.46%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.77%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 5.77%   |
| AuthenTec AES2810                                                          | 3         | 5.77%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.92%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.92%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.92%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.92%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.92%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.92%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 17        | 94.44%  |
| O2 Micro | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 38.89%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |
| Broadcom 5880                                                                | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 136       | 56.9%   |
| 1     | 85        | 35.56%  |
| 2     | 13        | 5.44%   |
| 4     | 2         | 0.84%   |
| 3     | 2         | 0.84%   |
| 5     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 41.46%  |
| Chipcard                 | 18        | 14.63%  |
| Graphics card            | 15        | 12.2%   |
| Net/wireless             | 13        | 10.57%  |
| Sound                    | 8         | 6.5%    |
| Storage                  | 4         | 3.25%   |
| Communication controller | 4         | 3.25%   |
| Bluetooth                | 4         | 3.25%   |
| Network                  | 2         | 1.63%   |
| Net/ethernet             | 2         | 1.63%   |
| Multimedia controller    | 1         | 0.81%   |
| Camera                   | 1         | 0.81%   |

