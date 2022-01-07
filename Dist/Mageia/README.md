Mageia - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Mageia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Mageia/Desktop/README.md) and [notebooks](/Dist/Mageia/Notebook/README.md).

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

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [c44573411d](https://linux-hardware.org/?probe=c44573411d) | Dec 27, 2021 |
| MSI      | MPG X570 GAMING EDGE WIF... | Desktop     | [c1d67915d0](https://linux-hardware.org/?probe=c1d67915d0) | Dec 26, 2021 |
| ASUSTek  | ROG ZENITH EXTREME          | Desktop     | [e3d82aebbe](https://linux-hardware.org/?probe=e3d82aebbe) | Dec 20, 2021 |
| MSI      | MPG X570 GAMING EDGE WIF... | Desktop     | [fdc65fea9d](https://linux-hardware.org/?probe=fdc65fea9d) | Dec 08, 2021 |
| Gigabyte | H81M-S2H                    | Desktop     | [ceefdd4eac](https://linux-hardware.org/?probe=ceefdd4eac) | Dec 06, 2021 |
| Dell     | Latitude E5570              | Notebook    | [38032eae74](https://linux-hardware.org/?probe=38032eae74) | Dec 06, 2021 |
| Dell     | Latitude E5570              | Notebook    | [9314738bbb](https://linux-hardware.org/?probe=9314738bbb) | Dec 06, 2021 |
| Dell     | Precision 5530              | Notebook    | [f98313a80c](https://linux-hardware.org/?probe=f98313a80c) | Nov 29, 2021 |
| Dell     | 0TP412                      | Desktop     | [f759f2084b](https://linux-hardware.org/?probe=f759f2084b) | Nov 22, 2021 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [665331e075](https://linux-hardware.org/?probe=665331e075) | Nov 22, 2021 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | Desktop     | [3e92c96ac0](https://linux-hardware.org/?probe=3e92c96ac0) | Nov 17, 2021 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | Desktop     | [6e13fb31c9](https://linux-hardware.org/?probe=6e13fb31c9) | Oct 17, 2021 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | Desktop     | [45d12f532c](https://linux-hardware.org/?probe=45d12f532c) | Oct 01, 2021 |
| Lenovo   | IdeaPad 3 15ADA05 81W1      | Notebook    | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| Gigabyte | H170-D3H-CF                 | Desktop     | [e18761a6b2](https://linux-hardware.org/?probe=e18761a6b2) | Sep 28, 2021 |
| Gigabyte | H170-D3H-CF                 | Desktop     | [42784959b9](https://linux-hardware.org/?probe=42784959b9) | Sep 28, 2021 |
| Apple    | Mac-F42386C8 PVT            | All in one  | [3235b7d95a](https://linux-hardware.org/?probe=3235b7d95a) | Sep 24, 2021 |
| Dell     | 0TP412                      | Desktop     | [25b9af915a](https://linux-hardware.org/?probe=25b9af915a) | Sep 09, 2021 |
| MSI      | MAG B460M MORTAR            | Desktop     | [6fa1f56407](https://linux-hardware.org/?probe=6fa1f56407) | Aug 30, 2021 |
| Gigabyte | H81M-S2H                    | Desktop     | [46740d8f33](https://linux-hardware.org/?probe=46740d8f33) | Aug 22, 2021 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [31e9013879](https://linux-hardware.org/?probe=31e9013879) | Aug 18, 2021 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [809f094941](https://linux-hardware.org/?probe=809f094941) | Aug 17, 2021 |
| Gigabyte | H81M-S2H                    | Desktop     | [894c915ecc](https://linux-hardware.org/?probe=894c915ecc) | Aug 17, 2021 |
| Lenovo   | IdeaPad Slim 1-14AST-05 ... | Notebook    | [46250d420a](https://linux-hardware.org/?probe=46250d420a) | Aug 14, 2021 |
| Gigabyte | B450 AORUS PRO WIFI-CF      | Desktop     | [4c28c43c28](https://linux-hardware.org/?probe=4c28c43c28) | Aug 10, 2021 |
| Lenovo   | ThinkPad T61 6468AE2        | Notebook    | [216fbf401b](https://linux-hardware.org/?probe=216fbf401b) | Aug 05, 2021 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [88ddc09b9e](https://linux-hardware.org/?probe=88ddc09b9e) | Jul 28, 2021 |
| Gigabyte | H81M-S2H                    | Desktop     | [f52713e401](https://linux-hardware.org/?probe=f52713e401) | Jul 28, 2021 |
| Dell     | 0TP412                      | Desktop     | [8788d078a0](https://linux-hardware.org/?probe=8788d078a0) | Jul 19, 2021 |
| ASUSTek  | PRIME X399-A                | Desktop     | [a2b6af1a6a](https://linux-hardware.org/?probe=a2b6af1a6a) | Jul 14, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [8c0efa94e8](https://linux-hardware.org/?probe=8c0efa94e8) | Jul 08, 2021 |
| Gigabyte | Z68XP-UD3P                  | Desktop     | [259e2a4ac0](https://linux-hardware.org/?probe=259e2a4ac0) | Jun 24, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [7619cf7632](https://linux-hardware.org/?probe=7619cf7632) | May 31, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [70f882a983](https://linux-hardware.org/?probe=70f882a983) | May 31, 2021 |
| Notebook | NL40_50GU                   | Notebook    | [baa8447288](https://linux-hardware.org/?probe=baa8447288) | May 08, 2021 |
| Medion   | DEFENDER P10                | Notebook    | [cb752c0a4a](https://linux-hardware.org/?probe=cb752c0a4a) | May 01, 2021 |
| Medion   | DEFENDER P10                | Notebook    | [f42aa05a37](https://linux-hardware.org/?probe=f42aa05a37) | May 01, 2021 |
| Gigabyte | B450M DS3H-CF               | Desktop     | [1be802a26e](https://linux-hardware.org/?probe=1be802a26e) | Apr 18, 2021 |
| ECS      | IC780M-A2                   | Desktop     | [e3cbd0879b](https://linux-hardware.org/?probe=e3cbd0879b) | Apr 17, 2021 |
| ASUSTek  | Z170-P                      | Desktop     | [1ebcf0ea2c](https://linux-hardware.org/?probe=1ebcf0ea2c) | Apr 16, 2021 |
| ASUSTek  | Z170-P                      | Desktop     | [a95896e05e](https://linux-hardware.org/?probe=a95896e05e) | Apr 16, 2021 |
| Medion   | Z370H4-EM                   | Desktop     | [57435ad8fb](https://linux-hardware.org/?probe=57435ad8fb) | Apr 16, 2021 |
| ASUSTek  | SABERTOOTH P67              | Desktop     | [6d81c9d615](https://linux-hardware.org/?probe=6d81c9d615) | Apr 16, 2021 |
| Fujitsu  | LIFEBOOK E752               | Notebook    | [8ec052ba75](https://linux-hardware.org/?probe=8ec052ba75) | Apr 15, 2021 |
| Gigabyte | H61M-S2PV                   | Desktop     | [dce1091d81](https://linux-hardware.org/?probe=dce1091d81) | Apr 15, 2021 |
| Medion   | Z370H4-EM                   | Desktop     | [b88834e15d](https://linux-hardware.org/?probe=b88834e15d) | Apr 15, 2021 |
| Lenovo   | ThinkPad T430 2342A19       | Notebook    | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| HP       | 212B                        | Desktop     | [697e2f24f0](https://linux-hardware.org/?probe=697e2f24f0) | Apr 03, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [7da0db2567](https://linux-hardware.org/?probe=7da0db2567) | Apr 03, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [09afc59907](https://linux-hardware.org/?probe=09afc59907) | Apr 02, 2021 |
| Intel    | STL2-bd A28808-302          | Desktop     | [d6b5151873](https://linux-hardware.org/?probe=d6b5151873) | Apr 01, 2021 |
| Gigabyte | B450M DS3H-CF               | Desktop     | [dbb3c1865f](https://linux-hardware.org/?probe=dbb3c1865f) | Mar 29, 2021 |
| HP       | 212B                        | Desktop     | [69f528da9b](https://linux-hardware.org/?probe=69f528da9b) | Mar 28, 2021 |
| ASUSTek  | PRIME A320M-K               | Desktop     | [2b381b3421](https://linux-hardware.org/?probe=2b381b3421) | Mar 24, 2021 |
| ASUSTek  | X556URK                     | Notebook    | [4904d2c78e](https://linux-hardware.org/?probe=4904d2c78e) | Mar 18, 2021 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [d4570ea6b2](https://linux-hardware.org/?probe=d4570ea6b2) | Mar 12, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [0bb2c11bdc](https://linux-hardware.org/?probe=0bb2c11bdc) | Feb 24, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [a8e9bcdc07](https://linux-hardware.org/?probe=a8e9bcdc07) | Feb 23, 2021 |
| ASRock   | M3A UCC                     | Desktop     | [714da9501f](https://linux-hardware.org/?probe=714da9501f) | Feb 19, 2021 |
| HP       | 339A                        | Desktop     | [43e759b593](https://linux-hardware.org/?probe=43e759b593) | Feb 14, 2021 |
| HP       | 339A                        | Desktop     | [39d23c03ca](https://linux-hardware.org/?probe=39d23c03ca) | Feb 13, 2021 |
| Dell     | Latitude E6530              | Notebook    | [035378659f](https://linux-hardware.org/?probe=035378659f) | Feb 12, 2021 |
| Gigabyte | H81M-S2H                    | Desktop     | [f9e5b1d3c6](https://linux-hardware.org/?probe=f9e5b1d3c6) | Feb 08, 2021 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [aea262050c](https://linux-hardware.org/?probe=aea262050c) | Feb 04, 2021 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [adabf5b11e](https://linux-hardware.org/?probe=adabf5b11e) | Jan 31, 2021 |
| Dell     | Inspiron 5480               | Notebook    | [2ae12f394c](https://linux-hardware.org/?probe=2ae12f394c) | Jan 27, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [6e7c6b5d77](https://linux-hardware.org/?probe=6e7c6b5d77) | Jan 16, 2021 |
| Gigabyte | B450M DS3H-CF               | Desktop     | [a399a43535](https://linux-hardware.org/?probe=a399a43535) | Jan 16, 2021 |
| Gigabyte | H81M-S2H                    | Desktop     | [0b7e0d2152](https://linux-hardware.org/?probe=0b7e0d2152) | Jan 15, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [567ce23c0d](https://linux-hardware.org/?probe=567ce23c0d) | Jan 13, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [513ff22c6f](https://linux-hardware.org/?probe=513ff22c6f) | Jan 13, 2021 |
| Kiano    | SlimNote 15.6               | Notebook    | [55179f361c](https://linux-hardware.org/?probe=55179f361c) | Jan 08, 2021 |
| Kiano    | SlimNote 15.6               | Notebook    | [5379fd7478](https://linux-hardware.org/?probe=5379fd7478) | Jan 08, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [9136594961](https://linux-hardware.org/?probe=9136594961) | Jan 02, 2021 |
| ASUSTek  | X751LN                      | Notebook    | [ea55725f98](https://linux-hardware.org/?probe=ea55725f98) | Dec 30, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | Notebook    | [01aa1a7b95](https://linux-hardware.org/?probe=01aa1a7b95) | Dec 30, 2020 |
| ASUSTek  | Z87-DELUXE                  | Desktop     | [e160eea25a](https://linux-hardware.org/?probe=e160eea25a) | Dec 28, 2020 |
| ASUSTek  | X751LN                      | Notebook    | [8399780a87](https://linux-hardware.org/?probe=8399780a87) | Dec 27, 2020 |
| ASUSTek  | X751LN                      | Notebook    | [f7f3533d54](https://linux-hardware.org/?probe=f7f3533d54) | Dec 27, 2020 |
| HP       | 339A                        | Desktop     | [ea7792c224](https://linux-hardware.org/?probe=ea7792c224) | Dec 26, 2020 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [932603ce99](https://linux-hardware.org/?probe=932603ce99) | Dec 25, 2020 |
| ASUSTek  | ROG ZENITH EXTREME          | Desktop     | [5fd86e8c94](https://linux-hardware.org/?probe=5fd86e8c94) | Dec 22, 2020 |
| Dell     | Inspiron 5480               | Notebook    | [1261d0c9d3](https://linux-hardware.org/?probe=1261d0c9d3) | Dec 21, 2020 |
| Lenovo   | ThinkServer TS140           | Desktop     | [ec475a7f9a](https://linux-hardware.org/?probe=ec475a7f9a) | Dec 09, 2020 |
| ASRock   | H87M Pro4                   | Desktop     | [12185c0c75](https://linux-hardware.org/?probe=12185c0c75) | Dec 07, 2020 |
| ASRock   | H87M Pro4                   | Desktop     | [747bc56208](https://linux-hardware.org/?probe=747bc56208) | Dec 07, 2020 |
| Gigabyte | F2A88XM-DS2                 | Desktop     | [1b5123770e](https://linux-hardware.org/?probe=1b5123770e) | Dec 06, 2020 |
| Gigabyte | H81M-S2H                    | Desktop     | [3f948a0756](https://linux-hardware.org/?probe=3f948a0756) | Dec 03, 2020 |
| HP       | Spectre 13 Ultrabook        | Notebook    | [9b88fe4fa5](https://linux-hardware.org/?probe=9b88fe4fa5) | Nov 30, 2020 |
| Gigabyte | H81M-S2H                    | Desktop     | [009e2519cb](https://linux-hardware.org/?probe=009e2519cb) | Nov 22, 2020 |
| HP       | EliteBook 840 G3            | Notebook    | [4dd618cb59](https://linux-hardware.org/?probe=4dd618cb59) | Nov 21, 2020 |
| HP       | EliteBook 840 G3            | Notebook    | [2543664b54](https://linux-hardware.org/?probe=2543664b54) | Nov 21, 2020 |
| Gigabyte | GA-78LMT-USB3 R2            | Desktop     | [1aec57de3b](https://linux-hardware.org/?probe=1aec57de3b) | Nov 20, 2020 |
| Gigabyte | H81M-S2H                    | Desktop     | [8f031786c5](https://linux-hardware.org/?probe=8f031786c5) | Nov 16, 2020 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [1bdc158142](https://linux-hardware.org/?probe=1bdc158142) | Nov 16, 2020 |
| ASUSTek  | PRIME B360-PLUS             | Desktop     | [dadbc2f1d7](https://linux-hardware.org/?probe=dadbc2f1d7) | Nov 15, 2020 |
| Lenovo   | IdeaPad 3 15ADA05 81W1      | Notebook    | [889cb35866](https://linux-hardware.org/?probe=889cb35866) | Nov 13, 2020 |
| HP       | ProBook 445 G7              | Notebook    | [2e97281aa0](https://linux-hardware.org/?probe=2e97281aa0) | Nov 05, 2020 |
| MSI      | MPG X570 GAMING EDGE WIF... | Desktop     | [fb717dc126](https://linux-hardware.org/?probe=fb717dc126) | Nov 05, 2020 |
| Gigabyte | H170-D3H-CF                 | Desktop     | [8220a96972](https://linux-hardware.org/?probe=8220a96972) | Nov 02, 2020 |
| Acer     | Aspire V3-772               | Notebook    | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| Gigabyte | H81M-S2H                    | Desktop     | [a854973bf5](https://linux-hardware.org/?probe=a854973bf5) | Oct 25, 2020 |
| Dell     | Inspiron 5480               | Notebook    | [62bb8575f1](https://linux-hardware.org/?probe=62bb8575f1) | Oct 22, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | Desktop     | [e50d2bd553](https://linux-hardware.org/?probe=e50d2bd553) | Oct 18, 2020 |
| ZOTAC    | Unknown                     | Desktop     | [624888f3ab](https://linux-hardware.org/?probe=624888f3ab) | Oct 14, 2020 |
| Gigabyte | H170-D3H-CF                 | Desktop     | [c73f4878af](https://linux-hardware.org/?probe=c73f4878af) | Oct 04, 2020 |
| Gigabyte | H81M-S2H                    | Desktop     | [1a7d01552e](https://linux-hardware.org/?probe=1a7d01552e) | Oct 04, 2020 |
| Lenovo   | ThinkServer TS140           | Desktop     | [87f4eac666](https://linux-hardware.org/?probe=87f4eac666) | Sep 27, 2020 |
| Gigabyte | H81M-S2H                    | Desktop     | [8fa69c952c](https://linux-hardware.org/?probe=8fa69c952c) | Sep 15, 2020 |
| HP       | Unknown                     | Notebook    | [b12d1589a1](https://linux-hardware.org/?probe=b12d1589a1) | Sep 08, 2020 |
| Acer     | Aspire 7741                 | Notebook    | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| HP       | Pavilion dv6                | Notebook    | [021a94f63e](https://linux-hardware.org/?probe=021a94f63e) | Sep 03, 2020 |
| ASRock   | M3A UCC                     | Desktop     | [43182d8754](https://linux-hardware.org/?probe=43182d8754) | Sep 01, 2020 |
| ASRock   | M3A UCC                     | Desktop     | [50908c43f9](https://linux-hardware.org/?probe=50908c43f9) | Sep 01, 2020 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [cbab4d3ea3](https://linux-hardware.org/?probe=cbab4d3ea3) | Aug 31, 2020 |
| Gigabyte | H81M-S2H                    | Desktop     | [f6c7b24ad6](https://linux-hardware.org/?probe=f6c7b24ad6) | Aug 31, 2020 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [7fd8c75c95](https://linux-hardware.org/?probe=7fd8c75c95) | Aug 19, 2020 |
| Gigabyte | H81M-S2H                    | Desktop     | [14955a6413](https://linux-hardware.org/?probe=14955a6413) | Aug 19, 2020 |
| Lenovo   | G480 20149                  | Notebook    | [5598a535c7](https://linux-hardware.org/?probe=5598a535c7) | Jul 24, 2020 |
| ASUSTek  | P8H61-M LE                  | Desktop     | [2ca048a380](https://linux-hardware.org/?probe=2ca048a380) | Jun 29, 2020 |
| ASRock   | H81M-VG4 R2.0               | Desktop     | [ed7fe704dd](https://linux-hardware.org/?probe=ed7fe704dd) | May 25, 2020 |
| HP       | 339A                        | Desktop     | [bbd2341205](https://linux-hardware.org/?probe=bbd2341205) | May 09, 2020 |
| HP       | 339A                        | Desktop     | [1334fcea56](https://linux-hardware.org/?probe=1334fcea56) | May 09, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | Notebook    | [8e31f45bf5](https://linux-hardware.org/?probe=8e31f45bf5) | May 07, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | Notebook    | [db83d53491](https://linux-hardware.org/?probe=db83d53491) | May 07, 2020 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | Notebook    | [4b71b90312](https://linux-hardware.org/?probe=4b71b90312) | May 04, 2020 |
| MSI      | B360M MORTAR                | Desktop     | [d2215c28af](https://linux-hardware.org/?probe=d2215c28af) | Apr 26, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | Desktop     | [f6e5343aa5](https://linux-hardware.org/?probe=f6e5343aa5) | Mar 31, 2020 |
| ASUSTek  | H170M-PLUS                  | Desktop     | [6dd350fc4a](https://linux-hardware.org/?probe=6dd350fc4a) | Mar 31, 2020 |
| ASUSTek  | PRIME A320M-K               | Desktop     | [cabb3f4266](https://linux-hardware.org/?probe=cabb3f4266) | Mar 29, 2020 |
| Vorke    | V1 Plus                     | Desktop     | [c49c2bb635](https://linux-hardware.org/?probe=c49c2bb635) | Mar 29, 2020 |
| Gigabyte | H81M-S2H                    | Desktop     | [c61a5bbb12](https://linux-hardware.org/?probe=c61a5bbb12) | Mar 05, 2020 |
| ASRock   | X470 Taichi                 | Desktop     | [5125778e67](https://linux-hardware.org/?probe=5125778e67) | Mar 02, 2020 |
| Gigabyte | B85M-D3H                    | Desktop     | [00442cfd17](https://linux-hardware.org/?probe=00442cfd17) | Feb 25, 2020 |
| Gigabyte | Z87X-UD5H-CF                | Desktop     | [71a967abf8](https://linux-hardware.org/?probe=71a967abf8) | Feb 22, 2020 |
| Gigabyte | H81M-S2H                    | Desktop     | [52c3f45c8f](https://linux-hardware.org/?probe=52c3f45c8f) | Feb 22, 2020 |
| ASUSTek  | H170M-PLUS                  | Desktop     | [0ae790ac85](https://linux-hardware.org/?probe=0ae790ac85) | Feb 01, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | Desktop     | [506294e8e9](https://linux-hardware.org/?probe=506294e8e9) | Jan 13, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | Desktop     | [16e8d236b4](https://linux-hardware.org/?probe=16e8d236b4) | Jan 12, 2020 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | Desktop     | [7df7d9c296](https://linux-hardware.org/?probe=7df7d9c296) | Dec 20, 2019 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | Desktop     | [0c42dfc62c](https://linux-hardware.org/?probe=0c42dfc62c) | Dec 08, 2019 |
| ASUSTek  | SABERTOOTH 990FX R2.0       | Desktop     | [2ef79b672c](https://linux-hardware.org/?probe=2ef79b672c) | Nov 15, 2019 |
| ASUSTek  | A55BM-K                     | Desktop     | [d58dbcdd06](https://linux-hardware.org/?probe=d58dbcdd06) | Nov 08, 2019 |
| MSI      | Z97-G43                     | Desktop     | [87e4cd50ce](https://linux-hardware.org/?probe=87e4cd50ce) | Apr 26, 2019 |
| ASRock   | X470 Taichi                 | Desktop     | [14a8808d2b](https://linux-hardware.org/?probe=14a8808d2b) | Apr 26, 2019 |
| Gigabyte | Z68X-UD3H-B3                | Desktop     | [28ea4213cb](https://linux-hardware.org/?probe=28ea4213cb) | Feb 25, 2019 |
| Gigabyte | Z68X-UD3H-B3                | Desktop     | [b9c55f2790](https://linux-hardware.org/?probe=b9c55f2790) | Feb 25, 2019 |
| ASRock   | X470 Taichi                 | Desktop     | [7b6ec43d58](https://linux-hardware.org/?probe=7b6ec43d58) | Jan 08, 2019 |
| ASRock   | X470 Taichi                 | Desktop     | [117cb09799](https://linux-hardware.org/?probe=117cb09799) | Dec 31, 2018 |
| Gigabyte | Z68X-UD3H-B3                | Desktop     | [0a61436f40](https://linux-hardware.org/?probe=0a61436f40) | Feb 15, 2018 |
| ASUSTek  | M5A97 R2.0                  | Desktop     | [304aa59840](https://linux-hardware.org/?probe=304aa59840) | Dec 14, 2017 |
| ASUSTek  | M4A78 PLUS                  | Desktop     | [ed9d8a148d](https://linux-hardware.org/?probe=ed9d8a148d) | Mar 06, 2016 |
| Lenovo   | G570 20079                  | Notebook    | [fc57cb086b](https://linux-hardware.org/?probe=fc57cb086b) | Nov 26, 2015 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.7.19-desktop-3.mga7      | 14        | 12.61%  |
| 5.10.27-desktop-1.mga8     | 8         | 7.21%   |
| 5.7.19-desktop-1.mga7      | 7         | 6.31%   |
| 5.6.14-desktop-2.mga7      | 4         | 3.6%    |
| 5.5.4-desktop-1.mga7       | 4         | 3.6%    |
| 5.10.25-desktop-1.mga8     | 4         | 3.6%    |
| 5.5.9-desktop-1.mga7       | 3         | 2.7%    |
| 5.10.12-desktop-1.mga7     | 3         | 2.7%    |
| 5.7.14-desktop-1.mga7      | 2         | 1.8%    |
| 5.6.6-desktop-1.mga7       | 2         | 1.8%    |
| 5.3.7-desktop-4.mga7       | 2         | 1.8%    |
| 5.15.4-desktop-1.mga8      | 2         | 1.8%    |
| 5.10.60-desktop-2.mga8     | 2         | 1.8%    |
| 5.10.56-desktop-1.mga8     | 2         | 1.8%    |
| 5.10.52-desktop-1.mga8     | 2         | 1.8%    |
| 5.10.20-desktop-2.mga7     | 2         | 1.8%    |
| 5.10.14-desktop-1.mga7     | 2         | 1.8%    |
| 5.9.6-desktop-1.mga8       | 1         | 0.9%    |
| 5.9.3-desktop-1.mga8       | 1         | 0.9%    |
| 5.9.16-desktop-1.mga7      | 1         | 0.9%    |
| 5.9.11-desktop-3.mga8      | 1         | 0.9%    |
| 5.9.1-desktop-1.mga8       | 1         | 0.9%    |
| 5.8.5-desktop-2.mga8       | 1         | 0.9%    |
| 5.8.14-desktop-1.mga8      | 1         | 0.9%    |
| 5.7.8-desktop-1.mga8       | 1         | 0.9%    |
| 5.6.8-desktop-1.mga7       | 1         | 0.9%    |
| 5.5.6-desktop-2.mga7       | 1         | 0.9%    |
| 5.5.13-desktop-1.mga7      | 1         | 0.9%    |
| 5.4.8-desktop-1.mga7       | 1         | 0.9%    |
| 5.4.12-desktop-1.mga7      | 1         | 0.9%    |
| 5.3.13-desktop-2.mga7      | 1         | 0.9%    |
| 5.15.6-desktop-2.mga9      | 1         | 0.9%    |
| 5.15.6-desktop-2.mga8      | 1         | 0.9%    |
| 5.15.2-desktop-2.mga9      | 1         | 0.9%    |
| 5.15.10-desktop-1.mga9     | 1         | 0.9%    |
| 5.15.10-desktop-1.mga8     | 1         | 0.9%    |
| 5.14.9-desktop-1.mga9      | 1         | 0.9%    |
| 5.14.12-desktop-2.mga9     | 1         | 0.9%    |
| 5.14.10-desktop-1.mga8     | 1         | 0.9%    |
| 5.13.12-desktop-2.mga8     | 1         | 0.9%    |
| 5.12.15-desktop-1.mga8     | 1         | 0.9%    |
| 5.10.8-desktop-2.mga7      | 1         | 0.9%    |
| 5.10.78-desktop-1.mga8     | 1         | 0.9%    |
| 5.10.62-desktop-1.mga8     | 1         | 0.9%    |
| 5.10.6-desktop-1.mga7      | 1         | 0.9%    |
| 5.10.48-desktop-1.mga8     | 1         | 0.9%    |
| 5.10.46-desktop-1.mga8     | 1         | 0.9%    |
| 5.10.45-desktop-2.mga8     | 1         | 0.9%    |
| 5.10.37-desktop-2.mga8     | 1         | 0.9%    |
| 5.10.33-desktop-1.mga8     | 1         | 0.9%    |
| 5.10.30-desktop-1.mga8     | 1         | 0.9%    |
| 5.10.3-desktop-1.mga7      | 1         | 0.9%    |
| 5.10.2-desktop-1.mga8      | 1         | 0.9%    |
| 5.10.16-desktop-1.mga8     | 1         | 0.9%    |
| 5.10.16-desktop-1.mga7     | 1         | 0.9%    |
| 5.10.12-desktop-2.mga8     | 1         | 0.9%    |
| 5.1.0-desktop-0.rc6.1.mga7 | 1         | 0.9%    |
| 4.9.56-server-1.mga6       | 1         | 0.9%    |
| 4.19.13-desktop-1.mga7     | 1         | 0.9%    |
| 4.14.18-desktop-1.mga6     | 1         | 0.9%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.7.19   | 18        | 16.67%  |
| 5.10.27  | 8         | 7.41%   |
| 5.6.14   | 4         | 3.7%    |
| 5.5.4    | 4         | 3.7%    |
| 5.10.25  | 4         | 3.7%    |
| 5.10.12  | 4         | 3.7%    |
| 5.5.9    | 3         | 2.78%   |
| 5.7.14   | 2         | 1.85%   |
| 5.6.6    | 2         | 1.85%   |
| 5.3.7    | 2         | 1.85%   |
| 5.15.6   | 2         | 1.85%   |
| 5.15.4   | 2         | 1.85%   |
| 5.15.10  | 2         | 1.85%   |
| 5.10.60  | 2         | 1.85%   |
| 5.10.56  | 2         | 1.85%   |
| 5.10.52  | 2         | 1.85%   |
| 5.10.20  | 2         | 1.85%   |
| 5.10.16  | 2         | 1.85%   |
| 5.10.14  | 2         | 1.85%   |
| 5.9.6    | 1         | 0.93%   |
| 5.9.3    | 1         | 0.93%   |
| 5.9.16   | 1         | 0.93%   |
| 5.9.11   | 1         | 0.93%   |
| 5.9.1    | 1         | 0.93%   |
| 5.8.5    | 1         | 0.93%   |
| 5.8.14   | 1         | 0.93%   |
| 5.7.8    | 1         | 0.93%   |
| 5.6.8    | 1         | 0.93%   |
| 5.5.6    | 1         | 0.93%   |
| 5.5.13   | 1         | 0.93%   |
| 5.4.8    | 1         | 0.93%   |
| 5.4.12   | 1         | 0.93%   |
| 5.3.13   | 1         | 0.93%   |
| 5.15.2   | 1         | 0.93%   |
| 5.14.9   | 1         | 0.93%   |
| 5.14.12  | 1         | 0.93%   |
| 5.14.10  | 1         | 0.93%   |
| 5.13.12  | 1         | 0.93%   |
| 5.12.15  | 1         | 0.93%   |
| 5.10.8   | 1         | 0.93%   |
| 5.10.78  | 1         | 0.93%   |
| 5.10.62  | 1         | 0.93%   |
| 5.10.6   | 1         | 0.93%   |
| 5.10.48  | 1         | 0.93%   |
| 5.10.46  | 1         | 0.93%   |
| 5.10.45  | 1         | 0.93%   |
| 5.10.37  | 1         | 0.93%   |
| 5.10.33  | 1         | 0.93%   |
| 5.10.30  | 1         | 0.93%   |
| 5.10.3   | 1         | 0.93%   |
| 5.10.2   | 1         | 0.93%   |
| 5.1.0    | 1         | 0.93%   |
| 4.9.56   | 1         | 0.93%   |
| 4.19.13  | 1         | 0.93%   |
| 4.14.18  | 1         | 0.93%   |
| 4.14.106 | 1         | 0.93%   |
| 4.14.100 | 1         | 0.93%   |
| 4.1.15   | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 27        | 29.67%  |
| 5.7     | 19        | 20.88%  |
| 5.5     | 8         | 8.79%   |
| 5.6     | 7         | 7.69%   |
| 5.15    | 7         | 7.69%   |
| 5.9     | 5         | 5.49%   |
| 5.14    | 3         | 3.3%    |
| 4.14    | 3         | 3.3%    |
| 5.8     | 2         | 2.2%    |
| 5.4     | 2         | 2.2%    |
| 5.3     | 2         | 2.2%    |
| 5.13    | 1         | 1.1%    |
| 5.12    | 1         | 1.1%    |
| 5.1     | 1         | 1.1%    |
| 4.9     | 1         | 1.1%    |
| 4.19    | 1         | 1.1%    |
| 4.1     | 1         | 1.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 65        | 98.48%  |
| i686   | 1         | 1.52%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 27        | 36%     |
| KDE           | 23        | 30.67%  |
| Unknown       | 7         | 9.33%   |
| Cinnamon      | 5         | 6.67%   |
| GNOME         | 4         | 5.33%   |
| LXDE          | 3         | 4%      |
| XFCE          | 2         | 2.67%   |
| MATE          | 1         | 1.33%   |
| LXQt          | 1         | 1.33%   |
| KDE4          | 1         | 1.33%   |
| GNOME Classic | 1         | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 65        | 97.01%  |
| Wayland | 1         | 1.49%   |
| Tty     | 1         | 1.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 31        | 46.27%  |
| SDDM    | 29        | 43.28%  |
| TDM     | 3         | 4.48%   |
| LightDM | 2         | 2.99%   |
| XDM     | 1         | 1.49%   |
| GDM     | 1         | 1.49%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 14        | 20.59%  |
| fr_FR   | 11        | 16.18%  |
| de_DE   | 8         | 11.76%  |
| Unknown | 8         | 11.76%  |
| ru_RU   | 6         | 8.82%   |
| en_GB   | 4         | 5.88%   |
| it_IT   | 3         | 4.41%   |
| sv_SE   | 2         | 2.94%   |
| pt_BR   | 2         | 2.94%   |
| pl_PL   | 2         | 2.94%   |
| hu_HU   | 1         | 1.47%   |
| fr_BE   | 1         | 1.47%   |
| es_GT   | 1         | 1.47%   |
| es_ES   | 1         | 1.47%   |
| es_AR   | 1         | 1.47%   |
| en_CA   | 1         | 1.47%   |
| cs_CZ   | 1         | 1.47%   |
| bg_BG   | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 42        | 60%     |
| EFI  | 28        | 40%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 57        | 83.82%  |
| Unknown  | 6         | 8.82%   |
| Xfs      | 2         | 2.94%   |
| Btrfs    | 2         | 2.94%   |
| Reiserfs | 1         | 1.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 28        | 40.58%  |
| Unknown | 25        | 36.23%  |
| MBR     | 16        | 23.19%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 86.36%  |
| Yes       | 9         | 13.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 76.47%  |
| Yes       | 16        | 23.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 17        | 25.76%  |
| Gigabyte Technology | 12        | 18.18%  |
| Hewlett-Packard     | 7         | 10.61%  |
| Dell                | 6         | 9.09%   |
| MSI                 | 4         | 6.06%   |
| Lenovo              | 4         | 6.06%   |
| ASRock              | 4         | 6.06%   |
| Medion              | 2         | 3.03%   |
| Acer                | 2         | 3.03%   |
| ZOTAC               | 1         | 1.52%   |
| Vorke               | 1         | 1.52%   |
| Notebook            | 1         | 1.52%   |
| Kiano               | 1         | 1.52%   |
| Intel               | 1         | 1.52%   |
| Fujitsu             | 1         | 1.52%   |
| ECS                 | 1         | 1.52%   |
| Apple               | 1         | 1.52%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Gigabyte Z68X-UD3H-B3                | 2         | 3.03%   |
| Dell Precision WorkStation T3400     | 2         | 3.03%   |
| ASUS SABERTOOTH 990FX R2.0           | 2         | 3.03%   |
| Unknown                              | 2         | 3.03%   |
| Vorke V1 Plus                        | 1         | 1.52%   |
| Notebook NL40_50GU                   | 1         | 1.52%   |
| MSI MS-7C82                          | 1         | 1.52%   |
| MSI MS-7C37                          | 1         | 1.52%   |
| MSI MS-7B23                          | 1         | 1.52%   |
| MSI MS-7816                          | 1         | 1.52%   |
| Medion MD34161/C708                  | 1         | 1.52%   |
| Medion DEFENDER P10                  | 1         | 1.52%   |
| Lenovo ThinkPad T430 2342A19         | 1         | 1.52%   |
| Lenovo IdeaPad 3 15ADA05 81W1        | 1         | 1.52%   |
| Lenovo G480 20149                    | 1         | 1.52%   |
| Lenovo 70A4000HUX ThinkServer TS140  | 1         | 1.52%   |
| Kiano SlimNote 15.6                  | 1         | 1.52%   |
| Intel STL2                           | 1         | 1.52%   |
| HP Z440 Workstation                  | 1         | 1.52%   |
| HP Spectre 13 Ultrabook              | 1         | 1.52%   |
| HP ProBook 445 G7                    | 1         | 1.52%   |
| HP Pavilion dv6                      | 1         | 1.52%   |
| HP EliteBook 840 G3                  | 1         | 1.52%   |
| HP Compaq Pro 6300 SFF               | 1         | 1.52%   |
| Gigabyte Z87X-UD5H                   | 1         | 1.52%   |
| Gigabyte Z68XP-UD3P                  | 1         | 1.52%   |
| Gigabyte H81M-S2H                    | 1         | 1.52%   |
| Gigabyte H61M-S2PV                   | 1         | 1.52%   |
| Gigabyte H170-D3H                    | 1         | 1.52%   |
| Gigabyte GA-78LMT-USB3 R2            | 1         | 1.52%   |
| Gigabyte F2A88XM-DS2                 | 1         | 1.52%   |
| Gigabyte B85M-D3H                    | 1         | 1.52%   |
| Gigabyte B450M DS3H                  | 1         | 1.52%   |
| Gigabyte B450 AORUS PRO WIFI         | 1         | 1.52%   |
| Fujitsu LIFEBOOK E752                | 1         | 1.52%   |
| ECS IC780M-A2                        | 1         | 1.52%   |
| Dell Precision 5530                  | 1         | 1.52%   |
| Dell Latitude E6530                  | 1         | 1.52%   |
| Dell Latitude E5570                  | 1         | 1.52%   |
| Dell Inspiron 5480                   | 1         | 1.52%   |
| ASUS Z170-P                          | 1         | 1.52%   |
| ASUS X751LN                          | 1         | 1.52%   |
| ASUS X556URK                         | 1         | 1.52%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR | 1         | 1.52%   |
| ASUS SABERTOOTH P67                  | 1         | 1.52%   |
| ASUS ROG ZENITH EXTREME              | 1         | 1.52%   |
| ASUS PRIME X399-A                    | 1         | 1.52%   |
| ASUS PRIME B360-PLUS                 | 1         | 1.52%   |
| ASUS PRIME A320M-K                   | 1         | 1.52%   |
| ASUS P8H61-M LE                      | 1         | 1.52%   |
| ASUS M5A97 R2.0                      | 1         | 1.52%   |
| ASUS M4A78 PLUS                      | 1         | 1.52%   |
| ASUS H170M-PLUS                      | 1         | 1.52%   |
| ASUS All Series                      | 1         | 1.52%   |
| ASUS A55BM-K                         | 1         | 1.52%   |
| ASRock X470 Taichi                   | 1         | 1.52%   |
| ASRock M3A UCC                       | 1         | 1.52%   |
| ASRock H87M Pro4                     | 1         | 1.52%   |
| ASRock H81M-VG4 R2.0                 | 1         | 1.52%   |
| Apple iMac7,1                        | 1         | 1.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Precision         | 3         | 4.55%   |
| ASUS SABERTOOTH        | 3         | 4.55%   |
| ASUS PRIME             | 3         | 4.55%   |
| Gigabyte Z68X-UD3H-B3  | 2         | 3.03%   |
| Dell Latitude          | 2         | 3.03%   |
| Acer Aspire            | 2         | 3.03%   |
| Unknown                | 2         | 3.03%   |
| Vorke V1               | 1         | 1.52%   |
| Notebook NL40          | 1         | 1.52%   |
| MSI MS-7C82            | 1         | 1.52%   |
| MSI MS-7C37            | 1         | 1.52%   |
| MSI MS-7B23            | 1         | 1.52%   |
| MSI MS-7816            | 1         | 1.52%   |
| Medion MD34161         | 1         | 1.52%   |
| Medion DEFENDER        | 1         | 1.52%   |
| Lenovo ThinkPad        | 1         | 1.52%   |
| Lenovo IdeaPad         | 1         | 1.52%   |
| Lenovo G480            | 1         | 1.52%   |
| Lenovo 70A4000HUX      | 1         | 1.52%   |
| Kiano SlimNote         | 1         | 1.52%   |
| Intel STL2             | 1         | 1.52%   |
| HP Z440                | 1         | 1.52%   |
| HP Spectre             | 1         | 1.52%   |
| HP ProBook             | 1         | 1.52%   |
| HP Pavilion            | 1         | 1.52%   |
| HP EliteBook           | 1         | 1.52%   |
| HP Compaq              | 1         | 1.52%   |
| Gigabyte Z87X-UD5H     | 1         | 1.52%   |
| Gigabyte Z68XP-UD3P    | 1         | 1.52%   |
| Gigabyte H81M-S2H      | 1         | 1.52%   |
| Gigabyte H61M-S2PV     | 1         | 1.52%   |
| Gigabyte H170-D3H      | 1         | 1.52%   |
| Gigabyte GA-78LMT-USB3 | 1         | 1.52%   |
| Gigabyte F2A88XM-DS2   | 1         | 1.52%   |
| Gigabyte B85M-D3H      | 1         | 1.52%   |
| Gigabyte B450M         | 1         | 1.52%   |
| Gigabyte B450          | 1         | 1.52%   |
| Fujitsu LIFEBOOK       | 1         | 1.52%   |
| ECS IC780M-A2          | 1         | 1.52%   |
| Dell Inspiron          | 1         | 1.52%   |
| ASUS Z170-P            | 1         | 1.52%   |
| ASUS X751LN            | 1         | 1.52%   |
| ASUS X556URK           | 1         | 1.52%   |
| ASUS VivoBook          | 1         | 1.52%   |
| ASUS ROG               | 1         | 1.52%   |
| ASUS P8H61-M           | 1         | 1.52%   |
| ASUS M5A97             | 1         | 1.52%   |
| ASUS M4A78             | 1         | 1.52%   |
| ASUS H170M-PLUS        | 1         | 1.52%   |
| ASUS All               | 1         | 1.52%   |
| ASUS A55BM-K           | 1         | 1.52%   |
| ASRock X470            | 1         | 1.52%   |
| ASRock M3A             | 1         | 1.52%   |
| ASRock H87M            | 1         | 1.52%   |
| ASRock H81M-VG4        | 1         | 1.52%   |
| Apple iMac7            | 1         | 1.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 9         | 13.64%  |
| 2014 | 9         | 13.64%  |
| 2020 | 7         | 10.61%  |
| 2016 | 6         | 9.09%   |
| 2018 | 5         | 7.58%   |
| 2017 | 5         | 7.58%   |
| 2012 | 5         | 7.58%   |
| 2015 | 4         | 6.06%   |
| 2013 | 3         | 4.55%   |
| 2011 | 3         | 4.55%   |
| 2010 | 3         | 4.55%   |
| 2008 | 3         | 4.55%   |
| 2021 | 2         | 3.03%   |
| 2007 | 1         | 1.52%   |
| 2002 | 1         | 1.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 44        | 66.67%  |
| Notebook   | 21        | 31.82%  |
| All in one | 1         | 1.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 66        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 66        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 18        | 25.71%  |
| 4.01-8.0    | 15        | 21.43%  |
| 8.01-16.0   | 15        | 21.43%  |
| 32.01-64.0  | 9         | 12.86%  |
| 3.01-4.0    | 8         | 11.43%  |
| 64.01-256.0 | 3         | 4.29%   |
| 24.01-32.0  | 2         | 2.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 28        | 33.73%  |
| 1.01-2.0   | 21        | 25.3%   |
| 4.01-8.0   | 16        | 19.28%  |
| 3.01-4.0   | 10        | 12.05%  |
| 8.01-16.0  | 5         | 6.02%   |
| 0.51-1.0   | 2         | 2.41%   |
| 16.01-24.0 | 1         | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 38.57%  |
| 2      | 19        | 27.14%  |
| 3      | 13        | 18.57%  |
| 5      | 5         | 7.14%   |
| 4      | 3         | 4.29%   |
| 8      | 1         | 1.43%   |
| 7      | 1         | 1.43%   |
| 6      | 1         | 1.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 51.52%  |
| No        | 32        | 48.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 89.39%  |
| No        | 7         | 10.61%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 50.75%  |
| No        | 33        | 49.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 51.52%  |
| No        | 32        | 48.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| France     | 12        | 18.18%  |
| USA        | 11        | 16.67%  |
| Germany    | 8         | 12.12%  |
| UK         | 5         | 7.58%   |
| Ukraine    | 3         | 4.55%   |
| Russia     | 3         | 4.55%   |
| Italy      | 3         | 4.55%   |
| Sweden     | 2         | 3.03%   |
| Poland     | 2         | 3.03%   |
| Greece     | 2         | 3.03%   |
| Canada     | 2         | 3.03%   |
| Brazil     | 2         | 3.03%   |
| Romania    | 1         | 1.52%   |
| Luxembourg | 1         | 1.52%   |
| Kenya      | 1         | 1.52%   |
| Indonesia  | 1         | 1.52%   |
| Guatemala  | 1         | 1.52%   |
| Czechia    | 1         | 1.52%   |
| Colombia   | 1         | 1.52%   |
| Bulgaria   | 1         | 1.52%   |
| Belgium    | 1         | 1.52%   |
| Belarus    | 1         | 1.52%   |
| Argentina  | 1         | 1.52%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Waterloo                   | 3         | 3.49%   |
| Paris                      | 3         | 3.49%   |
| Mala Danylivka             | 3         | 3.49%   |
| Kharkiv                    | 3         | 3.49%   |
| Cologne                    | 3         | 3.49%   |
| Rome                       | 2         | 2.33%   |
| Oakland                    | 2         | 2.33%   |
| Kingston upon Thames       | 2         | 2.33%   |
| Grants Pass                | 2         | 2.33%   |
| Basingstoke                | 2         | 2.33%   |
| Yakutsk                    | 1         | 1.16%   |
| Werl                       | 1         | 1.16%   |
| Voronezh                   | 1         | 1.16%   |
| Volos                      | 1         | 1.16%   |
| Tver                       | 1         | 1.16%   |
| Tresserve                  | 1         | 1.16%   |
| Tours                      | 1         | 1.16%   |
| Thessaloniki               | 1         | 1.16%   |
| Teddington                 | 1         | 1.16%   |
| São Paulo                 | 1         | 1.16%   |
| Strasbourg                 | 1         | 1.16%   |
| Sternberk                  | 1         | 1.16%   |
| Sainte-Genevi??ve-des-Bois | 1         | 1.16%   |
| Saint-Dié                 | 1         | 1.16%   |
| Rio de Janeiro             | 1         | 1.16%   |
| Poznan                     | 1         | 1.16%   |
| Pisa                       | 1         | 1.16%   |
| Penmarch                   | 1         | 1.16%   |
| Palermo                    | 1         | 1.16%   |
| Oxford                     | 1         | 1.16%   |
| Odenville                  | 1         | 1.16%   |
| Obernai                    | 1         | 1.16%   |
| Nova Vodolaha              | 1         | 1.16%   |
| Nordenham                  | 1         | 1.16%   |
| Nairobi                    | 1         | 1.16%   |
| Munich                     | 1         | 1.16%   |
| Miercurea-Ciuc             | 1         | 1.16%   |
| Mannheim                   | 1         | 1.16%   |
| Luxembourg                 | 1         | 1.16%   |
| Lumajang                   | 1         | 1.16%   |
| Liège                     | 1         | 1.16%   |
| Lisieux                    | 1         | 1.16%   |
| Kehychivka                 | 1         | 1.16%   |
| Kalisz                     | 1         | 1.16%   |
| Jena                       | 1         | 1.16%   |
| Huty                       | 1         | 1.16%   |
| Helsingborg                | 1         | 1.16%   |
| Hammersmith                | 1         | 1.16%   |
| Guatemala City             | 1         | 1.16%   |
| Frankfurt am Main          | 1         | 1.16%   |
| Fountain Hill              | 1         | 1.16%   |
| Fort Bragg                 | 1         | 1.16%   |
| Farnborough                | 1         | 1.16%   |
| Erlangen                   | 1         | 1.16%   |
| Edinburgh                  | 1         | 1.16%   |
| Draveil                    | 1         | 1.16%   |
| Denver                     | 1         | 1.16%   |
| Delta                      | 1         | 1.16%   |
| Concarneau                 | 1         | 1.16%   |
| Colindale                  | 1         | 1.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 32        | 138    | 24.43%  |
| Seagate                 | 19        | 31     | 14.5%   |
| Samsung Electronics     | 15        | 18     | 11.45%  |
| Kingston                | 9         | 14     | 6.87%   |
| SanDisk                 | 8         | 14     | 6.11%   |
| Toshiba                 | 7         | 15     | 5.34%   |
| Hitachi                 | 6         | 6      | 4.58%   |
| Unknown                 | 4         | 4      | 3.05%   |
| HGST                    | 4         | 9      | 3.05%   |
| PNY                     | 3         | 4      | 2.29%   |
| Intel                   | 3         | 3      | 2.29%   |
| Crucial                 | 3         | 7      | 2.29%   |
| SK Hynix                | 2         | 3      | 1.53%   |
| OCZ-VERTEX              | 2         | 2      | 1.53%   |
| OCZ                     | 2         | 2      | 1.53%   |
| XPG                     | 1         | 4      | 0.76%   |
| Verbatim                | 1         | 1      | 0.76%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.76%   |
| Transcend               | 1         | 1      | 0.76%   |
| TO Exter                | 1         | 1      | 0.76%   |
| Team                    | 1         | 1      | 0.76%   |
| Phison                  | 1         | 1      | 0.76%   |
| LDLC                    | 1         | 1      | 0.76%   |
| HUAWEI                  | 1         | 1      | 0.76%   |
| FORESEE                 | 1         | 1      | 0.76%   |
| China                   | 1         | 1      | 0.76%   |
| Asmedia                 | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB                     | 3         | 2%      |
| Samsung SSD 860 EVO 250GB                    | 3         | 2%      |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 2         | 1.33%   |
| WDC WDS250G2B0A-00SM50 250GB SSD             | 2         | 1.33%   |
| WDC WD30EZRZ-00Z5HB0 3TB                     | 2         | 1.33%   |
| WDC WD2500BEVT-22ZCT0 250GB                  | 2         | 1.33%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 2         | 1.33%   |
| WDC WD10EZRZ-00HTKB0 1TB                     | 2         | 1.33%   |
| WDC WD10EFRX-68PJCN0 1TB                     | 2         | 1.33%   |
| Seagate ST3500418AS 500GB                    | 2         | 1.33%   |
| Seagate ST32000644NS 2TB                     | 2         | 1.33%   |
| SanDisk SDSSDA120G 120GB                     | 2         | 1.33%   |
| SanDisk Extreme SSD 500GB                    | 2         | 1.33%   |
| Samsung SSD 860 EVO 500GB                    | 2         | 1.33%   |
| Samsung SSD 850 EVO 500GB                    | 2         | 1.33%   |
| OCZ-VERTEX PLUS R2 64GB SSD                  | 2         | 1.33%   |
| Kingston SV300S37A240G 240GB SSD             | 2         | 1.33%   |
| Intel SSDSC2CW120A3 120GB                    | 2         | 1.33%   |
| Hitachi HDS722020ALA330 2TB                  | 2         | 1.33%   |
| HGST HUS726040ALE611 4TB                     | 2         | 1.33%   |
| XPG NVMe SSD Drive 2TB                       | 1         | 0.67%   |
| XPG NVMe SSD Drive 1024GB                    | 1         | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 0.67%   |
| WDC WDS100T2B0A 1TB SSD                      | 1         | 0.67%   |
| WDC WD800BB-00JHC0 80GB                      | 1         | 0.67%   |
| WDC WD5000AAKX-60U6AA0 500GB                 | 1         | 0.67%   |
| WDC WD5000AADS-00S9B0 500GB                  | 1         | 0.67%   |
| WDC WD40EFRX-68N32N0 4TB                     | 1         | 0.67%   |
| WDC WD4000FYYZ-01UL1B2 4TB                   | 1         | 0.67%   |
| WDC WD3200KS-00PFB0 320GB                    | 1         | 0.67%   |
| WDC WD3200AAJS-00B4A0 320GB                  | 1         | 0.67%   |
| WDC WD30PURX-64P6ZY0 3TB                     | 1         | 0.67%   |
| WDC WD30EZRX-00DC0B0 3TB                     | 1         | 0.67%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1         | 0.67%   |
| WDC WD3000GLFS-01F8U0 304GB                  | 1         | 0.67%   |
| WDC WD20EZRZ-00Z5HB0 2TB                     | 1         | 0.67%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 1         | 0.67%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 0.67%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1         | 0.67%   |
| WDC WD141KRYZ-01C66B0 14TB                   | 1         | 0.67%   |
| WDC WD10SPZX-75Z10T2 1TB                     | 1         | 0.67%   |
| WDC WD10SPZX-00Z10T0 1TB                     | 1         | 0.67%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 0.67%   |
| WDC WD10EZRX-00L4HB0 1TB                     | 1         | 0.67%   |
| WDC WD10EZRX-00A8LB0 1TB                     | 1         | 0.67%   |
| WDC WD10EZEX-22MFCA0 1TB                     | 1         | 0.67%   |
| WDC WD10EARS-00Y5B1 1TB                      | 1         | 0.67%   |
| WDC WD10EARS-00MVWB0 1TB                     | 1         | 0.67%   |
| WDC WD1002FAEX-00Z3A0 1TB                    | 1         | 0.67%   |
| Verbatim USB External SSD 256GB              | 1         | 0.67%   |
| Unknown SD/MMC/MS PRO 7GB                    | 1         | 0.67%   |
| Unknown MMC Card  32GB                       | 1         | 0.67%   |
| Unknown MMC Card  16GB                       | 1         | 0.67%   |
| Unknown L200 Hard drive 2TB                  | 1         | 0.67%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.67%   |
| Transcend TS512GSSD370 512GB                 | 1         | 0.67%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 0.67%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 0.67%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 0.67%   |
| Toshiba HDWD110 1TB                          | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 122    | 39.13%  |
| Seagate             | 19        | 31     | 27.54%  |
| Toshiba             | 7         | 15     | 10.14%  |
| Hitachi             | 6         | 6      | 8.7%    |
| HGST                | 4         | 9      | 5.8%    |
| Unknown             | 2         | 2      | 2.9%    |
| Samsung Electronics | 2         | 3      | 2.9%    |
| TO Exter            | 1         | 1      | 1.45%   |
| Asmedia             | 1         | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 22.45%  |
| WDC                 | 6         | 16     | 12.24%  |
| SanDisk             | 6         | 8      | 12.24%  |
| Kingston            | 6         | 9      | 12.24%  |
| PNY                 | 3         | 4      | 6.12%   |
| Intel               | 3         | 3      | 6.12%   |
| Crucial             | 3         | 7      | 6.12%   |
| OCZ-VERTEX          | 2         | 2      | 4.08%   |
| OCZ                 | 2         | 2      | 4.08%   |
| Verbatim            | 1         | 1      | 2.04%   |
| Transcend           | 1         | 1      | 2.04%   |
| Team                | 1         | 1      | 2.04%   |
| SK Hynix            | 1         | 1      | 2.04%   |
| LDLC                | 1         | 1      | 2.04%   |
| FORESEE             | 1         | 1      | 2.04%   |
| China               | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 51        | 190    | 50.5%   |
| SSD     | 36        | 70     | 35.64%  |
| NVMe    | 11        | 22     | 10.89%  |
| MMC     | 2         | 2      | 1.98%   |
| Unknown | 1         | 1      | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 60        | 245    | 74.07%  |
| NVMe | 11        | 22     | 13.58%  |
| SAS  | 8         | 16     | 9.88%   |
| MMC  | 2         | 2      | 2.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 98     | 50.51%  |
| 0.51-1.0   | 27        | 95     | 27.27%  |
| 1.01-2.0   | 10        | 17     | 10.1%   |
| 2.01-3.0   | 6         | 42     | 6.06%   |
| 3.01-4.0   | 5         | 7      | 5.05%   |
| 10.01-20.0 | 1         | 1      | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 19        | 27.14%  |
| More than 3000 | 13        | 18.57%  |
| 251-500        | 11        | 15.71%  |
| 101-250        | 9         | 12.86%  |
| 2001-3000      | 7         | 10%     |
| 1001-2000      | 7         | 10%     |
| 51-100         | 3         | 4.29%   |
| Unknown        | 1         | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 22.08%  |
| 1001-2000      | 11        | 14.29%  |
| 1-20           | 10        | 12.99%  |
| 251-500        | 9         | 11.69%  |
| 51-100         | 9         | 11.69%  |
| 501-1000       | 8         | 10.39%  |
| More than 3000 | 6         | 7.79%   |
| 21-50          | 5         | 6.49%   |
| 2001-3000      | 1         | 1.3%    |
| Unknown        | 1         | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 16.67%  |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 8.33%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 1         | 1      | 8.33%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 8.33%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 8.33%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 8.33%   |
| Seagate ST3250410AS 250GB             | 1         | 1      | 8.33%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 8.33%   |
| OCZ VERTEX3 120GB SSD                 | 1         | 1      | 8.33%   |
| Hitachi HTS725050A9A364 500GB         | 1         | 1      | 8.33%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 3      | 27.27%  |
| Intel    | 2         | 2      | 18.18%  |
| WDC      | 1         | 2      | 9.09%   |
| Toshiba  | 1         | 1      | 9.09%   |
| SK Hynix | 1         | 1      | 9.09%   |
| OCZ      | 1         | 1      | 9.09%   |
| Hitachi  | 1         | 1      | 9.09%   |
| HGST     | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 42.86%  |
| WDC     | 1         | 2      | 14.29%  |
| Toshiba | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |
| HGST    | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 8      | 63.64%  |
| SSD  | 4         | 4      | 36.36%  |

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
| Works    | 38        | 160    | 47.5%   |
| Detected | 31        | 113    | 38.75%  |
| Malfunc  | 11        | 12     | 13.75%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 45        | 51.14%  |
| AMD                         | 18        | 20.45%  |
| Marvell Technology Group    | 7         | 7.95%   |
| ASMedia Technology          | 5         | 5.68%   |
| Kingston Technology Company | 3         | 3.41%   |
| Sandisk                     | 2         | 2.27%   |
| Samsung Electronics         | 2         | 2.27%   |
| Phison Electronics          | 2         | 2.27%   |
| SK Hynix                    | 1         | 1.14%   |
| JMicron Technology          | 1         | 1.14%   |
| Broadcom                    | 1         | 1.14%   |
| ADATA Technology            | 1         | 1.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 8         | 7.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 6.54%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 4.67%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 4         | 3.74%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 4         | 3.74%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 3.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 3.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 3.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 3.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 3.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 2.8%    |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 2.8%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 1.87%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 1.87%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 1.87%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2         | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.87%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2         | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.87%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 2         | 1.87%   |
| AMD SB600 IDE                                                                           | 2         | 1.87%   |
| SK Hynix BC511                                                                          | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.93%   |
| Phison E7 NVMe Controller                                                               | 1         | 0.93%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.93%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1         | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 0.93%   |
| JMicron JMB362 SATA Controller                                                          | 1         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 1         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1         | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 1         | 0.93%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1         | 0.93%   |
| Intel C610/X99 series chipset 4-port SATA Controller [IDE mode]                         | 1         | 0.93%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 1         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 1         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 1         | 0.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 1         | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 0.93%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 1         | 0.93%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 0.93%   |
| Broadcom OSB4 IDE Controller                                                            | 1         | 0.93%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 0.93%   |
| AMD FCH SATA Controller D                                                               | 1         | 0.93%   |
| AMD FCH IDE Controller                                                                  | 1         | 0.93%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 56        | 67.47%  |
| IDE  | 13        | 15.66%  |
| NVMe | 10        | 12.05%  |
| RAID | 4         | 4.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 47        | 71.21%  |
| AMD    | 19        | 28.79%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz                | 2         | 2.99%   |
| Intel Core i7-2600K CPU @ 3.40GHz               | 2         | 2.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 2.99%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2         | 2.99%   |
| AMD FX-8350 Eight-Core Processor                | 2         | 2.99%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz             | 1         | 1.49%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz        | 1         | 1.49%   |
| Intel Pentium III (Coppermine)                  | 1         | 1.49%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz          | 1         | 1.49%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 1.49%   |
| Intel Pentium CPU G3450 @ 3.40GHz               | 1         | 1.49%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 1.49%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 1         | 1.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 1.49%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 1.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 1.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1         | 1.49%   |
| Intel Core i7-4770K CPU @ 3.50GHz               | 1         | 1.49%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 1         | 1.49%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 1.49%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 1.49%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 1.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 1.49%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 1         | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 1.49%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 1         | 1.49%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1         | 1.49%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz              | 1         | 1.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 1.49%   |
| Intel Core i5-4440 CPU @ 3.10GHz                | 1         | 1.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 1.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.49%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1         | 1.49%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 1.49%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1         | 1.49%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1         | 1.49%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 1.49%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1         | 1.49%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 1         | 1.49%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1         | 1.49%   |
| Intel Core 2 Duo CPU T7700 @ 2.40GHz            | 1         | 1.49%   |
| Intel Celeron CPU J3455 @ 1.50GHz               | 1         | 1.49%   |
| Intel Celeron CPU G1830 @ 2.80GHz               | 1         | 1.49%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 1         | 1.49%   |
| AMD Turion 64 X2 Mobile Technology TL-60        | 1         | 1.49%   |
| AMD Ryzen Threadripper 2990WX 32-Core Processor | 1         | 1.49%   |
| AMD Ryzen Threadripper 1950X 16-Core Processor  | 1         | 1.49%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1         | 1.49%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 1         | 1.49%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 1         | 1.49%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 1.49%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1         | 1.49%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics     | 1         | 1.49%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 1         | 1.49%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1         | 1.49%   |
| AMD Phenom II X6 1100T Processor                | 1         | 1.49%   |
| AMD Phenom II X4 955 Processor                  | 1         | 1.49%   |
| AMD FX-8120 Eight-Core Processor                | 1         | 1.49%   |
| AMD FX-6300 Six-Core Processor                  | 1         | 1.49%   |
| AMD Athlon II X3 455 Processor                  | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 16        | 24.24%  |
| Intel Core i5           | 14        | 21.21%  |
| Intel Core i3           | 5         | 7.58%   |
| AMD FX                  | 4         | 6.06%   |
| Intel Core 2 Duo        | 3         | 4.55%   |
| AMD Ryzen 7             | 3         | 4.55%   |
| Intel Pentium           | 2         | 3.03%   |
| Intel Celeron           | 2         | 3.03%   |
| AMD Ryzen Threadripper  | 2         | 3.03%   |
| AMD Ryzen 5             | 2         | 3.03%   |
| Intel Xeon              | 1         | 1.52%   |
| Intel Pentium Silver    | 1         | 1.52%   |
| Intel Pentium III       | 1         | 1.52%   |
| Intel Pentium Gold      | 1         | 1.52%   |
| Intel Atom              | 1         | 1.52%   |
| AMD Turion 64 X2 Mobile | 1         | 1.52%   |
| AMD Ryzen 9             | 1         | 1.52%   |
| AMD Ryzen 3             | 1         | 1.52%   |
| AMD Phenom II X6        | 1         | 1.52%   |
| AMD Phenom II X4        | 1         | 1.52%   |
| AMD Athlon II X3        | 1         | 1.52%   |
| AMD A8                  | 1         | 1.52%   |
| AMD A10                 | 1         | 1.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 30        | 44.78%  |
| 2      | 24        | 35.82%  |
| 6      | 6         | 8.96%   |
| 8      | 2         | 2.99%   |
| 3      | 2         | 2.99%   |
| 32     | 1         | 1.49%   |
| 16     | 1         | 1.49%   |
| 12     | 1         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 65        | 98.48%  |
| 2      | 1         | 1.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 42        | 63.64%  |
| 1      | 24        | 36.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 64        | 94.12%  |
| Unknown        | 3         | 4.41%   |
| 32-bit         | 1         | 1.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 21.62%  |
| 0x306c3    | 7         | 9.46%   |
| 0x206a7    | 6         | 8.11%   |
| 0x306a9    | 5         | 6.76%   |
| 0x906ea    | 2         | 2.7%    |
| 0x806e9    | 2         | 2.7%    |
| 0x40651    | 2         | 2.7%    |
| 0x1067a    | 2         | 2.7%    |
| 0x08108109 | 2         | 2.7%    |
| 0x0800820d | 2         | 2.7%    |
| 0x06000852 | 2         | 2.7%    |
| 0x010000c8 | 2         | 2.7%    |
| 0xa0653    | 1         | 1.35%   |
| 0xa0652    | 1         | 1.35%   |
| 0x906eb    | 1         | 1.35%   |
| 0x906e9    | 1         | 1.35%   |
| 0x806eb    | 1         | 1.35%   |
| 0x706a1    | 1         | 1.35%   |
| 0x686      | 1         | 1.35%   |
| 0x506e3    | 1         | 1.35%   |
| 0x506c9    | 1         | 1.35%   |
| 0x406e3    | 1         | 1.35%   |
| 0x406c4    | 1         | 1.35%   |
| 0x306f2    | 1         | 1.35%   |
| 0x20655    | 1         | 1.35%   |
| 0x08701021 | 1         | 1.35%   |
| 0x08701013 | 1         | 1.35%   |
| 0x08600106 | 1         | 1.35%   |
| 0x08108102 | 1         | 1.35%   |
| 0x08101016 | 1         | 1.35%   |
| 0x0800820b | 1         | 1.35%   |
| 0x08001137 | 1         | 1.35%   |
| 0x06003104 | 1         | 1.35%   |
| 0x06001119 | 1         | 1.35%   |
| 0x0600084f | 1         | 1.35%   |
| 0x010000bf | 1         | 1.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 12        | 17.91%  |
| KabyLake      | 9         | 13.43%  |
| SandyBridge   | 6         | 8.96%   |
| IvyBridge     | 6         | 8.96%   |
| Zen+          | 5         | 7.46%   |
| Skylake       | 4         | 5.97%   |
| Piledriver    | 4         | 5.97%   |
| Zen 2         | 3         | 4.48%   |
| K10           | 3         | 4.48%   |
| Zen           | 2         | 2.99%   |
| Penryn        | 2         | 2.99%   |
| CometLake     | 2         | 2.99%   |
| Westmere      | 1         | 1.49%   |
| Steamroller   | 1         | 1.49%   |
| Silvermont    | 1         | 1.49%   |
| P6            | 1         | 1.49%   |
| K8 Hammer     | 1         | 1.49%   |
| Goldmont plus | 1         | 1.49%   |
| Goldmont      | 1         | 1.49%   |
| Core          | 1         | 1.49%   |
| Bulldozer     | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 32        | 41.03%  |
| Intel  | 31        | 39.74%  |
| AMD    | 15        | 19.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 5.13%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 4         | 5.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 5.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 5.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 3.85%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 2.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 2         | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 2.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.56%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                                        | 2         | 2.56%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 2         | 2.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 1.28%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 1.28%   |
| Nvidia NV11 [GeForce2 MX/MX 400]                                                         | 1         | 1.28%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.28%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 1.28%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.28%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 1.28%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.28%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.28%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.28%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 1.28%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 1         | 1.28%   |
| Nvidia GK106M [GeForce GTX 760M]                                                         | 1         | 1.28%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                                        | 1         | 1.28%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 1         | 1.28%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 1         | 1.28%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.28%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.28%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 1         | 1.28%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.28%   |
| Intel HD Graphics 630                                                                    | 1         | 1.28%   |
| Intel HD Graphics 620                                                                    | 1         | 1.28%   |
| Intel HD Graphics 530                                                                    | 1         | 1.28%   |
| Intel HD Graphics 500                                                                    | 1         | 1.28%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.28%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.28%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 1.28%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 1         | 1.28%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1         | 1.28%   |
| AMD Richland [Radeon HD 8570D]                                                           | 1         | 1.28%   |
| AMD Renoir                                                                               | 1         | 1.28%   |
| AMD Redwood PRO [Radeon HD 5550/5570/5630/6510/6610/7570]                                | 1         | 1.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.28%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                               | 1         | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.28%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Nvidia     | 23        | 34.33%  |
| 1 x Intel      | 20        | 29.85%  |
| 1 x AMD        | 14        | 20.9%   |
| Intel + Nvidia | 9         | 13.43%  |
| Intel + AMD    | 1         | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 47        | 68.12%  |
| Unknown     | 12        | 17.39%  |
| Proprietary | 10        | 14.49%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 35.71%  |
| 1.01-2.0   | 16        | 22.86%  |
| 0.51-1.0   | 11        | 15.71%  |
| 0.01-0.5   | 5         | 7.14%   |
| 5.01-6.0   | 4         | 5.71%   |
| 3.01-4.0   | 4         | 5.71%   |
| 7.01-8.0   | 2         | 2.86%   |
| 2.01-3.0   | 2         | 2.86%   |
| 8.01-16.0  | 1         | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Ancor Communications    | 7         | 8.97%   |
| Samsung Electronics     | 6         | 7.69%   |
| BOE                     | 5         | 6.41%   |
| Acer                    | 5         | 6.41%   |
| LG Display              | 4         | 5.13%   |
| Goldstar                | 4         | 5.13%   |
| Dell                    | 4         | 5.13%   |
| Chimei Innolux          | 4         | 5.13%   |
| BenQ                    | 4         | 5.13%   |
| ViewSonic               | 3         | 3.85%   |
| Sony                    | 3         | 3.85%   |
| Philips                 | 3         | 3.85%   |
| LG Electronics          | 3         | 3.85%   |
| AU Optronics            | 3         | 3.85%   |
| AOC                     | 3         | 3.85%   |
| SNC                     | 2         | 2.56%   |
| Hewlett-Packard         | 2         | 2.56%   |
| Chi Mei Optoelectronics | 2         | 2.56%   |
| Sharp                   | 1         | 1.28%   |
| RTK                     | 1         | 1.28%   |
| QBell                   | 1         | 1.28%   |
| ONKYO                   | 1         | 1.28%   |
| Medion                  | 1         | 1.28%   |
| Lenovo                  | 1         | 1.28%   |
| HannStar                | 1         | 1.28%   |
| Eizo                    | 1         | 1.28%   |
| Compal                  | 1         | 1.28%   |
| ASUSTek Computer        | 1         | 1.28%   |
| Apple                   | 1         | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                       | 2         | 2.33%   |
| Goldstar 27EA33 GSM59BC 1920x1080 598x337mm 27.0-inch                     | 2         | 2.33%   |
| Ancor Communications PA248 ACI24B1 1920x1080 550x350mm 25.7-inch          | 2         | 2.33%   |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch     | 2         | 2.33%   |
| ViewSonic VX2409 SERIES VSC6C2E 1920x1080 521x293mm 23.5-inch             | 1         | 1.16%   |
| ViewSonic VA903-3Series VSC701E 1280x1024 376x301mm 19.0-inch             | 1         | 1.16%   |
| ViewSonic LCD Monitor VP2468 Series 3520x1080                             | 1         | 1.16%   |
| Sony TV SNYF301 1920x1080 1600x900mm 72.3-inch                            | 1         | 1.16%   |
| Sony TV SNYDC02 1920x1080 930x520mm 41.9-inch                             | 1         | 1.16%   |
| Sony SDM-X72 SNY1E70 1280x1024 338x270mm 17.0-inch                        | 1         | 1.16%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 1.16%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch      | 1         | 1.16%   |
| Samsung Electronics SMB2240W SAM0698 1680x1050 474x296mm 22.0-inch        | 1         | 1.16%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch         | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 1         | 1.16%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch    | 1         | 1.16%   |
| Samsung Electronics LCD Monitor S24D330 3840x1080                         | 1         | 1.16%   |
| Samsung Electronics LCD Monitor S24D330                                   | 1         | 1.16%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch         | 1         | 1.16%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                    | 1         | 1.16%   |
| QBell QB.19F-4WLHGB QBL3EC6 1440x900 410x257mm 19.1-inch                  | 1         | 1.16%   |
| Philips PHL 436M6VBP PHLC179 3840x2160 941x529mm 42.5-inch                | 1         | 1.16%   |
| Philips LCD Monitor FTV                                                   | 1         | 1.16%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                        | 1         | 1.16%   |
| ONKYO LCD Monitor TX-SR608 5760x2160                                      | 1         | 1.16%   |
| ONKYO LCD Monitor TX-SR608                                                | 1         | 1.16%   |
| ONKYO LCD Monitor AV Receiver 5760x2160                                   | 1         | 1.16%   |
| Medion MD 20122 MED3601 1680x1050 474x296mm 22.0-inch                     | 1         | 1.16%   |
| LG Electronics LCD Monitor LG HDR 4K 5760x2160                            | 1         | 1.16%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                           | 1         | 1.16%   |
| LG Electronics LCD Monitor 23MB35 1920x1080                               | 1         | 1.16%   |
| LG Display LCD Monitor LGD049B 1920x1080 340x190mm 15.3-inch              | 1         | 1.16%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch               | 1         | 1.16%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 1         | 1.16%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                   | 1         | 1.16%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch             | 1         | 1.16%   |
| Hewlett-Packard w22 HWP26AE 1680x1050 473x296mm 22.0-inch                 | 1         | 1.16%   |
| Hewlett-Packard LP1965 HWP2693 1280x1024 380x300mm 19.1-inch              | 1         | 1.16%   |
| HannStar HF225 HSP18BB 1920x1080 477x268mm 21.5-inch                      | 1         | 1.16%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 1         | 1.16%   |
| Goldstar 22BK55 GSM5A30 1680x1050 480x300mm 22.3-inch                     | 1         | 1.16%   |
| Eizo EV2436W ENC2384 1920x1200 519x324mm 24.1-inch                        | 1         | 1.16%   |
| Dell P2719H DEL4185 1920x1080 598x336mm 27.0-inch                         | 1         | 1.16%   |
| Dell P2715Q DEL40BF 3840x2160 597x336mm 27.0-inch                         | 1         | 1.16%   |
| Dell P2214H DELA097 1920x1080 480x270mm 21.7-inch                         | 1         | 1.16%   |
| Dell LCD Monitor ST2420L                                                  | 1         | 1.16%   |
| Compal TERRA 2450W WOR2450 1920x1080 341x256mm 16.8-inch                  | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 1         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1357 1920x1080 293x165mm 13.2-inch          | 1         | 1.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 1         | 1.16%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                     | 1         | 1.16%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 1         | 1.16%   |
| BOE LCD Monitor BOE0806 1920x1080 309x173mm 13.9-inch                     | 1         | 1.16%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 1         | 1.16%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 1         | 1.16%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                        | 1         | 1.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 35        | 45.45%  |
| 1366x768 (WXGA)    | 7         | 9.09%   |
| Unknown            | 6         | 7.79%   |
| 3840x2160 (4K)     | 5         | 6.49%   |
| 1600x900 (HD+)     | 5         | 6.49%   |
| 1920x1200 (WUXGA)  | 4         | 5.19%   |
| 1280x1024 (SXGA)   | 4         | 5.19%   |
| 1680x1050 (WSXGA+) | 3         | 3.9%    |
| 3840x1080          | 2         | 2.6%    |
| 5760x2160          | 1         | 1.3%    |
| 4480x1440          | 1         | 1.3%    |
| 3520x1080          | 1         | 1.3%    |
| 3200x900           | 1         | 1.3%    |
| 1440x900 (WXGA+)   | 1         | 1.3%    |
| 1280x800 (WXGA)    | 1         | 1.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 10        | 13.33%  |
| 27      | 9         | 12%     |
| 24      | 8         | 10.67%  |
| Unknown | 8         | 10.67%  |
| 21      | 7         | 9.33%   |
| 17      | 6         | 8%      |
| 19      | 5         | 6.67%   |
| 22      | 3         | 4%      |
| 14      | 3         | 4%      |
| 13      | 3         | 4%      |
| 46      | 2         | 2.67%   |
| 25      | 2         | 2.67%   |
| 23      | 2         | 2.67%   |
| 18      | 2         | 2.67%   |
| 72      | 1         | 1.33%   |
| 54      | 1         | 1.33%   |
| 42      | 1         | 1.33%   |
| 32      | 1         | 1.33%   |
| 20      | 1         | 1.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 20        | 27.03%  |
| 301-350     | 16        | 21.62%  |
| 401-500     | 14        | 18.92%  |
| 351-400     | 8         | 10.81%  |
| Unknown     | 8         | 10.81%  |
| 1001-1500   | 3         | 4.05%   |
| 701-800     | 1         | 1.35%   |
| 601-700     | 1         | 1.35%   |
| 201-300     | 1         | 1.35%   |
| 1501-2000   | 1         | 1.35%   |
| 901-1000    | 1         | 1.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 47        | 68.12%  |
| 16/10   | 10        | 14.49%  |
| Unknown | 8         | 11.59%  |
| 5/4     | 4         | 5.8%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 13        | 17.81%  |
| 101-110        | 10        | 13.7%   |
| 301-350        | 9         | 12.33%  |
| 151-200        | 8         | 10.96%  |
| Unknown        | 8         | 10.96%  |
| 81-90          | 5         | 6.85%   |
| 251-300        | 5         | 6.85%   |
| 121-130        | 5         | 6.85%   |
| 141-150        | 3         | 4.11%   |
| 501-1000       | 3         | 4.11%   |
| More than 1000 | 2         | 2.74%   |
| 71-80          | 1         | 1.37%   |
| 351-500        | 1         | 1.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 30        | 42.25%  |
| 101-120 | 14        | 19.72%  |
| 121-160 | 12        | 16.9%   |
| Unknown | 8         | 11.27%  |
| 1-50    | 4         | 5.63%   |
| 161-240 | 3         | 4.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 49        | 73.13%  |
| 2     | 18        | 26.87%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 35        | 36.46%  |
| Realtek Semiconductor    | 34        | 35.42%  |
| Qualcomm Atheros         | 8         | 8.33%   |
| Broadcom                 | 8         | 8.33%   |
| Wilocity                 | 1         | 1.04%   |
| Ultimarc                 | 1         | 1.04%   |
| Sierra Wireless          | 1         | 1.04%   |
| MediaTek                 | 1         | 1.04%   |
| Marvell Technology Group | 1         | 1.04%   |
| Huawei Technologies      | 1         | 1.04%   |
| Dell                     | 1         | 1.04%   |
| D-Link System            | 1         | 1.04%   |
| Broadcom Limited         | 1         | 1.04%   |
| ASIX Electronics         | 1         | 1.04%   |
| Aquantia                 | 1         | 1.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 25%     |
| Intel I211 Gigabit Network Connection                             | 4         | 3.57%   |
| Intel Wireless 3165                                               | 3         | 2.68%   |
| Intel Ethernet Connection I217-V                                  | 3         | 2.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 2.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.68%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 2         | 1.79%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2         | 1.79%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.79%   |
| Intel Wireless 8260                                               | 2         | 1.79%   |
| Intel Wireless 7265                                               | 2         | 1.79%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.79%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1.79%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.79%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 1.79%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.79%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1         | 0.89%   |
| Ultimarc A-PAC Arcade Control Interface                           | 1         | 0.89%   |
| Sierra Wireless MC8305 Modem                                      | 1         | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.89%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.89%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.89%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.89%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.89%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.89%   |
| MediaTek WiFi                                                     | 1         | 0.89%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.89%   |
| Intel Wireless-AC 9260                                            | 1         | 0.89%   |
| Intel Wireless 7260                                               | 1         | 0.89%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1         | 0.89%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.89%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1         | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.89%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.89%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1         | 0.89%   |
| Huawei Mass Storage                                               | 1         | 0.89%   |
| Dell DW5811e Snapdragon???�?? X7 LTE                              | 1         | 0.89%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 0.89%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.89%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.89%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1         | 0.89%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 1         | 0.89%   |
| Broadcom BCM4311 802.11a/b/g                                      | 1         | 0.89%   |
| ASIX AX88772B                                                     | 1         | 0.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 47.5%   |
| Qualcomm Atheros      | 7         | 17.5%   |
| Realtek Semiconductor | 5         | 12.5%   |
| Broadcom              | 5         | 12.5%   |
| Wilocity              | 1         | 2.5%    |
| Sierra Wireless       | 1         | 2.5%    |
| MediaTek              | 1         | 2.5%    |
| Dell                  | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 3165                                            | 3         | 6.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 6.82%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2         | 4.55%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 4.55%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 4.55%   |
| Intel Wireless 8260                                            | 2         | 4.55%   |
| Intel Wireless 7265                                            | 2         | 4.55%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 4.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 4.55%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1         | 2.27%   |
| Sierra Wireless MC8305 Modem                                   | 1         | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 2.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.27%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 2.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 2.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.27%   |
| MediaTek WiFi                                                  | 1         | 2.27%   |
| Intel Wireless-AC 9260                                         | 1         | 2.27%   |
| Intel Wireless 7260                                            | 1         | 2.27%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.27%   |
| Dell DW5811e Snapdragon???�?? X7 LTE                           | 1         | 2.27%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 1         | 2.27%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 2.27%   |
| Broadcom BCM4311 802.11a/b/g                                   | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 32        | 50%     |
| Intel                    | 22        | 34.38%  |
| Broadcom                 | 3         | 4.69%   |
| Qualcomm Atheros         | 2         | 3.13%   |
| Marvell Technology Group | 1         | 1.56%   |
| D-Link System            | 1         | 1.56%   |
| Broadcom Limited         | 1         | 1.56%   |
| ASIX Electronics         | 1         | 1.56%   |
| Aquantia                 | 1         | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 42.42%  |
| Intel I211 Gigabit Network Connection                             | 4         | 6.06%   |
| Intel Ethernet Connection I217-V                                  | 3         | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.55%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 3.03%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 3.03%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2         | 3.03%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 3.03%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 1.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.52%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.52%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.52%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.52%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.52%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.52%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.52%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.52%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1         | 1.52%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 1.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.52%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 1.52%   |
| ASIX AX88772B                                                     | 1         | 1.52%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 59        | 62.11%  |
| WiFi     | 34        | 35.79%  |
| Modem    | 1         | 1.05%   |
| Unknown  | 1         | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 60.53%  |
| WiFi     | 29        | 38.16%  |
| Unknown  | 1         | 1.32%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 52.86%  |
| 2     | 26        | 37.14%  |
| 3     | 4         | 5.71%   |
| 0     | 2         | 2.86%   |
| 4     | 1         | 1.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 63        | 92.65%  |
| Yes  | 5         | 7.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 16        | 43.24%  |
| Cambridge Silicon Radio | 7         | 18.92%  |
| Broadcom                | 3         | 8.11%   |
| ASUSTek Computer        | 3         | 8.11%   |
| IMC Networks            | 2         | 5.41%   |
| Realtek Semiconductor   | 1         | 2.7%    |
| Lite-On Technology      | 1         | 2.7%    |
| Hewlett-Packard         | 1         | 2.7%    |
| Foxconn / Hon Hai       | 1         | 2.7%    |
| Dell                    | 1         | 2.7%    |
| Apple                   | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 18.92%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 18.92%  |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 8.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.41%   |
| Intel AX200 Bluetooth                               | 2         | 5.41%   |
| IMC Networks Bluetooth Device                       | 2         | 5.41%   |
| Realtek Bluetooth Radio                             | 1         | 2.7%    |
| Lite-On Bluetooth Device                            | 1         | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.7%    |
| Intel AX201 Bluetooth                               | 1         | 2.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 2.7%    |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 2.7%    |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 2.7%    |
| Broadcom Bluetooth dongle                           | 1         | 2.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 2.7%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.7%    |
| ASUS Bluetooth Device                               | 1         | 2.7%    |
| ASUS BCM20702A0                                     | 1         | 2.7%    |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 45        | 44.12%  |
| Nvidia                     | 26        | 25.49%  |
| AMD                        | 20        | 19.61%  |
| C-Media Electronics        | 6         | 5.88%   |
| Mackie Designs             | 1         | 0.98%   |
| Logitech                   | 1         | 0.98%   |
| Corsair                    | 1         | 0.98%   |
| BEHRINGER International    | 1         | 0.98%   |
| Altec Lansing Technologies | 1         | 0.98%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 6.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 6.09%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 4.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 4.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 3.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 3.48%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 3.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 3.48%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 4         | 3.48%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 3.48%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 4         | 3.48%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 2.61%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 1.74%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.74%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.74%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.74%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 2         | 1.74%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.74%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                       | 2         | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.74%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.87%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.87%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.87%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.87%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.87%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.87%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 0.87%   |
| Mackie Designs ProFX                                                       | 1         | 0.87%   |
| Logitech Headset H340                                                      | 1         | 0.87%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.87%   |
| Intel Comet Lake PCH-V cAVS                                                | 1         | 0.87%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.87%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1         | 0.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1         | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 0.87%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 0.87%   |
| Corsair Corsair ST100 Headset Output                                      | 1         | 0.87%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1         | 0.87%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 0.87%   |
| BEHRINGER International UMC404HD 192k                                      | 1         | 0.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 0.87%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.87%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 0.87%   |
| Altec Lansing Technologies ADA-305 Speakers                                | 1         | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 12        | 25%     |
| Samsung Electronics | 7         | 14.58%  |
| Unknown             | 6         | 12.5%   |
| G.Skill             | 5         | 10.42%  |
| SK Hynix            | 4         | 8.33%   |
| Micron Technology   | 3         | 6.25%   |
| Corsair             | 3         | 6.25%   |
| Team                | 2         | 4.17%   |
| Crucial             | 2         | 4.17%   |
| Unknown (ABCD)      | 1         | 2.08%   |
| Smart               | 1         | 2.08%   |
| Nanya Technology    | 1         | 2.08%   |
| GOODRAM             | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s          | 2         | 3.92%   |
| G.Skill RAM F3-12800CL9-4GBXM 4096MB DIMM DDR3 1600MT/s      | 2         | 3.92%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                  | 1         | 1.96%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                       | 1         | 1.96%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 1         | 1.96%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                | 1         | 1.96%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                 | 1         | 1.96%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1         | 1.96%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                       | 1         | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1         | 1.96%   |
| Team RAM Elite-16 8GB DIMM DDR3 1600MT/s                     | 1         | 1.96%   |
| Team RAM Elite-1333 2GB DIMM DDR3 1333MT/s                   | 1         | 1.96%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s        | 1         | 1.96%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s                 | 1         | 1.96%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s    | 1         | 1.96%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 1         | 1.96%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 1         | 1.96%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 1.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.96%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.96%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s     | 1         | 1.96%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s        | 1         | 1.96%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 2667MT/s         | 1         | 1.96%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s          | 1         | 1.96%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4096MB DIMM DDR3 1600MT/s        | 1         | 1.96%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 1         | 1.96%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s     | 1         | 1.96%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s        | 1         | 1.96%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM 1334MT/s         | 1         | 1.96%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s            | 1         | 1.96%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s            | 1         | 1.96%   |
| Kingston RAM KHX2133C11D3/8GX 8192MB DIMM DDR3 2133MT/s      | 1         | 1.96%   |
| Kingston RAM KHX1600C9D3/8G 8192MB DIMM DDR3 1600MT/s        | 1         | 1.96%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1867MT/s       | 1         | 1.96%   |
| Kingston RAM KFYHV1-HYC 4GB SODIMM DDR3 1600MT/s             | 1         | 1.96%   |
| Kingston RAM KCRXJ6-MIE 16384MB SODIMM DDR4 2667MT/s         | 1         | 1.96%   |
| Kingston RAM ACR16D3LS1KBG/8G 8GB SODIMM DDR3 1600MT/s       | 1         | 1.96%   |
| Kingston RAM 99U5584-009.A00LF 4GB DIMM 1600MT/s             | 1         | 1.96%   |
| Kingston RAM 9905624-054.A00G 8GB SODIMM DDR4 2400MT/s       | 1         | 1.96%   |
| Kingston RAM 9905428-102.A00G 4GB SODIMM DDR3 1600MT/s       | 1         | 1.96%   |
| GOODRAM RAM GY1600D364L10/8G 8192MB DIMM DDR3 1600MT/s       | 1         | 1.96%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s           | 1         | 1.96%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 1         | 1.96%   |
| G.Skill RAM F4-2133C15-8GNT 8GB DIMM DDR4 2133MT/s           | 1         | 1.96%   |
| Crucial RAM CT51264BA1339.D16F 4096MB DIMM DDR3 1333MT/s     | 1         | 1.96%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16GB SODIMM DDR4 2400MT/s   | 1         | 1.96%   |
| Corsair RAM CMZ32GX3M4A1600C9 8GB DIMM DDR3 1600MT/s         | 1         | 1.96%   |
| Corsair RAM CMSX16GX4M1A2666C18 16384MB SODIMM DDR4 2667MT/s | 1         | 1.96%   |
| Corsair RAM CMSO8GX4M1A2133C15 8GB SODIMM DDR4 2133MT/s      | 1         | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 20        | 47.62%  |
| DDR4    | 17        | 40.48%  |
| DDR2    | 2         | 4.76%   |
| Unknown | 2         | 4.76%   |
| LPDDR4  | 1         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 24        | 57.14%  |
| SODIMM | 18        | 42.86%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 18        | 40%     |
| 4096  | 16        | 35.56%  |
| 16384 | 6         | 13.33%  |
| 2048  | 5         | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 14        | 30.43%  |
| 2400  | 5         | 10.87%  |
| 2133  | 5         | 10.87%  |
| 3200  | 4         | 8.7%    |
| 2667  | 3         | 6.52%   |
| 1333  | 3         | 6.52%   |
| 3334  | 2         | 4.35%   |
| 667   | 2         | 4.35%   |
| 3733  | 1         | 2.17%   |
| 3500  | 1         | 2.17%   |
| 2933  | 1         | 2.17%   |
| 1867  | 1         | 2.17%   |
| 1334  | 1         | 2.17%   |
| 1066  | 1         | 2.17%   |
| 975   | 1         | 2.17%   |
| 800   | 1         | 2.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Canon               | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung CLP-300 Series       | 1         | 25%     |
| HP OfficeJet 6950            | 1         | 25%     |
| Canon PIXMA MG3600 Series    | 1         | 25%     |
| Brother QL-570 Label Printer | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson Scanner                   | 1         | 50%     |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 26.67%  |
| Microdia                               | 5         | 16.67%  |
| Realtek Semiconductor                  | 2         | 6.67%   |
| Microsoft                              | 2         | 6.67%   |
| Logitech                               | 2         | 6.67%   |
| IMC Networks                           | 2         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.67%   |
| Apple                                  | 2         | 6.67%   |
| Suyin                                  | 1         | 3.33%   |
| Sunplus Innovation Technology          | 1         | 3.33%   |
| Primax Electronics                     | 1         | 3.33%   |
| Leap Motion                            | 1         | 3.33%   |
| Alcor Micro                            | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Camera                                                            | 2         | 6.67%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 6.67%   |
| Chicony USB2.0 Camera                                                      | 2         | 6.67%   |
| Chicony Integrated Camera                                                  | 2         | 6.67%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 3.33%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 3.33%   |
| Realtek USB Camera                                                         | 1         | 3.33%   |
| Realtek Integrated_Webcam_HD                                               | 1         | 3.33%   |
| Primax HP Truevision FHD                                                   | 1         | 3.33%   |
| Microsoft LifeCam VX-800                                                   | 1         | 3.33%   |
| Microsoft LifeCam HD-3000                                                  | 1         | 3.33%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 3.33%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 3.33%   |
| Microdia Integrated Webcam                                                 | 1         | 3.33%   |
| Logitech Webcam C110                                                       | 1         | 3.33%   |
| Logitech QuickCam Pro 9000                                                 | 1         | 3.33%   |
| Leap Motion Controller                                                     | 1         | 3.33%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 3.33%   |
| Chicony HD WebCam                                                          | 1         | 3.33%   |
| Chicony FJ Camera                                                          | 1         | 3.33%   |
| Chicony 1.3M HD WebCam                                                     | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 1         | 3.33%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 3.33%   |
| Apple Built-in iSight                                                      | 1         | 3.33%   |
| Alcor Micro SHUNCCM2MP                                                     | 1         | 3.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 2         | 40%     |
| Shenzhen Goodix Technology | 2         | 40%     |
| AuthenTec                  | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 1         | 20%     |
| Validity Sensors Fingerprint scanner       | 1         | 20%     |
| Shenzhen Goodix  FingerPrint Device        | 1         | 20%     |
| Shenzhen Goodix Fingerprint Reader         | 1         | 20%     |
| AuthenTec AES2501 Fingerprint Sensor       | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 2         | 50%     |
| O2 Micro | 1         | 25%     |
| Avtor    | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom 5880                                                                | 1         | 25%     |
| Avtor SecureToken                                                            | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 49        | 70%     |
| 1     | 17        | 24.29%  |
| 2     | 3         | 4.29%   |
| 3     | 1         | 1.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 9         | 39.13%  |
| Fingerprint reader       | 5         | 21.74%  |
| Chipcard                 | 4         | 17.39%  |
| Unassigned class         | 1         | 4.35%   |
| Sound                    | 1         | 4.35%   |
| Multimedia controller    | 1         | 4.35%   |
| Communication controller | 1         | 4.35%   |
| Camera                   | 1         | 4.35%   |
