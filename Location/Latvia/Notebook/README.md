Linux in Latvia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Latvia.

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

Total: 256

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Dell          | Inspiron 3543               | [7fb19b7da4](https://linux-hardware.org/?probe=7fb19b7da4) | Apr 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [73de8fd9f4](https://linux-hardware.org/?probe=73de8fd9f4) | Apr 26, 2022 |
| Dell          | Latitude E7440              | [8609968661](https://linux-hardware.org/?probe=8609968661) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [75f2876f06](https://linux-hardware.org/?probe=75f2876f06) | Apr 12, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [c3ac98aa71](https://linux-hardware.org/?probe=c3ac98aa71) | Apr 11, 2022 |
| Dell          | Latitude 5590               | [6e22c70e48](https://linux-hardware.org/?probe=6e22c70e48) | Apr 05, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [086d7749d3](https://linux-hardware.org/?probe=086d7749d3) | Apr 03, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [1a8680a665](https://linux-hardware.org/?probe=1a8680a665) | Mar 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d63ab08c03](https://linux-hardware.org/?probe=d63ab08c03) | Mar 17, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [5af22f3639](https://linux-hardware.org/?probe=5af22f3639) | Mar 07, 2022 |
| HP            | EliteBook 8570w             | [a97a0ba0ee](https://linux-hardware.org/?probe=a97a0ba0ee) | Feb 27, 2022 |
| Dell          | Inspiron 3531               | [d2d231ddeb](https://linux-hardware.org/?probe=d2d231ddeb) | Feb 24, 2022 |
| Lenovo        | ThinkPad X220 4291Q50       | [600a3137e2](https://linux-hardware.org/?probe=600a3137e2) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ae4eca9e09](https://linux-hardware.org/?probe=ae4eca9e09) | Feb 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| Lenovo        | G70-80 80FF                 | [0771453742](https://linux-hardware.org/?probe=0771453742) | Jan 25, 2022 |
| Apple         | MacBookPro8,1               | [9b3d91c6df](https://linux-hardware.org/?probe=9b3d91c6df) | Jan 24, 2022 |
| HP            | 250 G6 Notebook PC          | [dae0e58890](https://linux-hardware.org/?probe=dae0e58890) | Jan 23, 2022 |
| Razer         | Blade 15 Advanced Model ... | [c07445f559](https://linux-hardware.org/?probe=c07445f559) | Jan 23, 2022 |
| Lenovo        | G70-80 80FF                 | [c69ec5ad5b](https://linux-hardware.org/?probe=c69ec5ad5b) | Jan 17, 2022 |
| Razer         | Blade 15 Advanced Model ... | [6f992c3b94](https://linux-hardware.org/?probe=6f992c3b94) | Jan 14, 2022 |
| Razer         | Blade 15 Advanced Model ... | [95724a0980](https://linux-hardware.org/?probe=95724a0980) | Jan 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d453a69dad](https://linux-hardware.org/?probe=d453a69dad) | Jan 06, 2022 |
| Lenovo        | G70-80 80FF                 | [b1279c6db3](https://linux-hardware.org/?probe=b1279c6db3) | Jan 02, 2022 |
| Lenovo        | G70-80 80FF                 | [14f3be9ec8](https://linux-hardware.org/?probe=14f3be9ec8) | Jan 01, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [0d09c12302](https://linux-hardware.org/?probe=0d09c12302) | Dec 28, 2021 |
| Lenovo        | G70-80 80FF                 | [4210ac05a8](https://linux-hardware.org/?probe=4210ac05a8) | Dec 26, 2021 |
| Dell          | Inspiron 3543               | [2b61a95031](https://linux-hardware.org/?probe=2b61a95031) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | [7d2faf3b37](https://linux-hardware.org/?probe=7d2faf3b37) | Dec 21, 2021 |
| Lenovo        | ThinkPad T60 8741W3M        | [6df4a50194](https://linux-hardware.org/?probe=6df4a50194) | Dec 21, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| ASUSTek       | E402SA                      | [2a140138d3](https://linux-hardware.org/?probe=2a140138d3) | Dec 12, 2021 |
| Lenovo        | G70-80 80FF                 | [7d694ce256](https://linux-hardware.org/?probe=7d694ce256) | Dec 09, 2021 |
| Dell          | Latitude 7420               | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | [c7726d6967](https://linux-hardware.org/?probe=c7726d6967) | Nov 23, 2021 |
| Acer          | NC-E5-572G-7222             | [1c2a0c3295](https://linux-hardware.org/?probe=1c2a0c3295) | Nov 19, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [0c603f1589](https://linux-hardware.org/?probe=0c603f1589) | Nov 16, 2021 |
| HUAWEI        | MACHD-WXX9                  | [364fb5b6b7](https://linux-hardware.org/?probe=364fb5b6b7) | Nov 06, 2021 |
| HP            | EliteBook 850 G4            | [e6643f7ed1](https://linux-hardware.org/?probe=e6643f7ed1) | Oct 28, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [f1449188a9](https://linux-hardware.org/?probe=f1449188a9) | Oct 20, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| HP            | G62                         | [7873481ecb](https://linux-hardware.org/?probe=7873481ecb) | Oct 12, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [96b4a3fe5a](https://linux-hardware.org/?probe=96b4a3fe5a) | Oct 04, 2021 |
| ASUSTek       | N550JV                      | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [f4a4e754c5](https://linux-hardware.org/?probe=f4a4e754c5) | Sep 22, 2021 |
| HP            | 250 G6 Notebook PC          | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [eb5215553d](https://linux-hardware.org/?probe=eb5215553d) | Sep 18, 2021 |
| HP            | EliteBook 840 G3            | [5ac93f6014](https://linux-hardware.org/?probe=5ac93f6014) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| HP            | Pavilion dv7                | [f58a2f5f40](https://linux-hardware.org/?probe=f58a2f5f40) | Sep 11, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [b4e19fb76a](https://linux-hardware.org/?probe=b4e19fb76a) | Aug 27, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [c5ebbbd9c2](https://linux-hardware.org/?probe=c5ebbbd9c2) | Aug 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [516c59e9bb](https://linux-hardware.org/?probe=516c59e9bb) | Aug 26, 2021 |
| Sony          | VPCCW2S8E                   | [a8c2dc6942](https://linux-hardware.org/?probe=a8c2dc6942) | Aug 26, 2021 |
| HP            | EliteBook 840 G1            | [82b2192d48](https://linux-hardware.org/?probe=82b2192d48) | Aug 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [d26b653261](https://linux-hardware.org/?probe=d26b653261) | Aug 23, 2021 |
| Dell          | G3 3579                     | [6042d3630a](https://linux-hardware.org/?probe=6042d3630a) | Aug 22, 2021 |
| Dell          | G3 3579                     | [902b56f744](https://linux-hardware.org/?probe=902b56f744) | Aug 22, 2021 |
| HP            | Pavilion dv7                | [7d6c08fc9e](https://linux-hardware.org/?probe=7d6c08fc9e) | Aug 17, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [eb1b7627ff](https://linux-hardware.org/?probe=eb1b7627ff) | Aug 10, 2021 |
| HP            | EliteBook 8470p             | [c718b061d2](https://linux-hardware.org/?probe=c718b061d2) | Aug 05, 2021 |
| HP            | HDX 16                      | [47273f74b5](https://linux-hardware.org/?probe=47273f74b5) | Aug 02, 2021 |
| HP            | HDX 16                      | [aa6b70deac](https://linux-hardware.org/?probe=aa6b70deac) | Aug 02, 2021 |
| Toshiba       | Satellite L850-1LK          | [8e8d84c8eb](https://linux-hardware.org/?probe=8e8d84c8eb) | Jul 30, 2021 |
| Dell          | Vostro 1015                 | [0e16f2bc9c](https://linux-hardware.org/?probe=0e16f2bc9c) | Jul 30, 2021 |
| Toshiba       | Satellite L850-1LK          | [b0b636bbee](https://linux-hardware.org/?probe=b0b636bbee) | Jul 30, 2021 |
| HP            | HDX 16                      | [2516a8dd6d](https://linux-hardware.org/?probe=2516a8dd6d) | Jul 25, 2021 |
| HP            | HDX 16                      | [627219df22](https://linux-hardware.org/?probe=627219df22) | Jul 25, 2021 |
| Timi          | A35S                        | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [55460937e0](https://linux-hardware.org/?probe=55460937e0) | Jul 14, 2021 |
| Lenovo        | ThinkPad P70 20ER0035MH     | [3b7269dbb9](https://linux-hardware.org/?probe=3b7269dbb9) | Jul 12, 2021 |
| Dell          | Latitude 7420               | [ebf2372c3b](https://linux-hardware.org/?probe=ebf2372c3b) | Jul 09, 2021 |
| HP            | HDX 16                      | [0982265d67](https://linux-hardware.org/?probe=0982265d67) | Jul 08, 2021 |
| HP            | HDX 16                      | [ba1ae87cbe](https://linux-hardware.org/?probe=ba1ae87cbe) | Jul 07, 2021 |
| Acer          | Predator PH317-53           | [1e5cb90c22](https://linux-hardware.org/?probe=1e5cb90c22) | Jul 06, 2021 |
| HP            | Pavilion dv6500             | [135215864a](https://linux-hardware.org/?probe=135215864a) | Jun 19, 2021 |
| Dell          | Latitude 5520               | [9929364f77](https://linux-hardware.org/?probe=9929364f77) | Jun 01, 2021 |
| Acer          | AO725                       | [1a095f9c0f](https://linux-hardware.org/?probe=1a095f9c0f) | May 17, 2021 |
| Lenovo        | Y50-70 20378                | [cc68265730](https://linux-hardware.org/?probe=cc68265730) | May 15, 2021 |
| Dell          | Inspiron 3583               | [7e3064fadf](https://linux-hardware.org/?probe=7e3064fadf) | May 10, 2021 |
| Dell          | Inspiron 3583               | [29e5e6b501](https://linux-hardware.org/?probe=29e5e6b501) | May 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [de14cb7c23](https://linux-hardware.org/?probe=de14cb7c23) | May 06, 2021 |
| Dell          | Inspiron 5720               | [28fc1b9fd7](https://linux-hardware.org/?probe=28fc1b9fd7) | Apr 20, 2021 |
| Acer          | Aspire E5-774G              | [17734000ae](https://linux-hardware.org/?probe=17734000ae) | Apr 14, 2021 |
| Lenovo        | G50-80 80E5                 | [d6b6146396](https://linux-hardware.org/?probe=d6b6146396) | Apr 14, 2021 |
| Dell          | Inspiron 5720               | [2bff145cfe](https://linux-hardware.org/?probe=2bff145cfe) | Apr 10, 2021 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [09ae9c9787](https://linux-hardware.org/?probe=09ae9c9787) | Mar 31, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [3c5c72b0fb](https://linux-hardware.org/?probe=3c5c72b0fb) | Mar 20, 2021 |
| Dell          | Latitude 5400               | [002c23ff4b](https://linux-hardware.org/?probe=002c23ff4b) | Mar 19, 2021 |
| Dell          | Latitude E5400              | [0b3108a091](https://linux-hardware.org/?probe=0b3108a091) | Mar 04, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [35b79852e1](https://linux-hardware.org/?probe=35b79852e1) | Feb 06, 2021 |
| ASUSTek       | F3Sg                        | [98e32533f7](https://linux-hardware.org/?probe=98e32533f7) | Feb 06, 2021 |
| Dell          | Inspiron 5720               | [548a61cbe6](https://linux-hardware.org/?probe=548a61cbe6) | Jan 24, 2021 |
| Dell          | Inspiron 5720               | [8e7fe7b05c](https://linux-hardware.org/?probe=8e7fe7b05c) | Jan 23, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [61f2500518](https://linux-hardware.org/?probe=61f2500518) | Jan 08, 2021 |
| Dell          | Latitude E6330              | [06a79c3a7f](https://linux-hardware.org/?probe=06a79c3a7f) | Jan 05, 2021 |
| ASUSTek       | N56VM                       | [795cfd3d9a](https://linux-hardware.org/?probe=795cfd3d9a) | Dec 30, 2020 |
| Acer          | Aspire E5-774G              | [4770a5cb75](https://linux-hardware.org/?probe=4770a5cb75) | Dec 30, 2020 |
| Lenovo        | G70-80 80FF                 | [069f4b154c](https://linux-hardware.org/?probe=069f4b154c) | Dec 27, 2020 |
| Lenovo        | V110-15IAP 80TG             | [5bb5bac2f1](https://linux-hardware.org/?probe=5bb5bac2f1) | Dec 26, 2020 |
| Quanta        | TW8/SW8/DW8                 | [705e766496](https://linux-hardware.org/?probe=705e766496) | Dec 18, 2020 |
| Quanta        | TW8/SW8/DW8                 | [5501a16739](https://linux-hardware.org/?probe=5501a16739) | Dec 18, 2020 |
| Fujitsu       | STYLISTIC Q704              | [ae32e0d51d](https://linux-hardware.org/?probe=ae32e0d51d) | Dec 14, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [46c6cef9b6](https://linux-hardware.org/?probe=46c6cef9b6) | Nov 27, 2020 |
| Lenovo        | G70-80 80FF                 | [7563d834dc](https://linux-hardware.org/?probe=7563d834dc) | Nov 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [177a2353e0](https://linux-hardware.org/?probe=177a2353e0) | Nov 26, 2020 |
| Lenovo        | G70-80 80FF                 | [814d9b3267](https://linux-hardware.org/?probe=814d9b3267) | Nov 26, 2020 |
| Acer          | Aspire E5-774G              | [792da7f209](https://linux-hardware.org/?probe=792da7f209) | Nov 21, 2020 |
| ASUSTek       | N56VZ                       | [fb3694b0fb](https://linux-hardware.org/?probe=fb3694b0fb) | Nov 21, 2020 |
| Fujitsu       | STYLISTIC Q704              | [a016928cb6](https://linux-hardware.org/?probe=a016928cb6) | Nov 20, 2020 |
| Fujitsu       | STYLISTIC Q704              | [6cee0ffad6](https://linux-hardware.org/?probe=6cee0ffad6) | Nov 20, 2020 |
| Acer          | Nitro AN515-54              | [6b6517fc84](https://linux-hardware.org/?probe=6b6517fc84) | Nov 17, 2020 |
| ASUSTek       | F9S                         | [dbadd20bba](https://linux-hardware.org/?probe=dbadd20bba) | Nov 15, 2020 |
| ASUSTek       | X751LD                      | [1ddab278fa](https://linux-hardware.org/?probe=1ddab278fa) | Nov 13, 2020 |
| ASUSTek       | X751LD                      | [518aedab56](https://linux-hardware.org/?probe=518aedab56) | Nov 13, 2020 |
| ASUSTek       | F9S                         | [17861d40da](https://linux-hardware.org/?probe=17861d40da) | Nov 09, 2020 |
| Acer          | Aspire E1-570               | [cfca189393](https://linux-hardware.org/?probe=cfca189393) | Oct 29, 2020 |
| Packard Be... | EasyNote LE69KB             | [c31d50e8e1](https://linux-hardware.org/?probe=c31d50e8e1) | Oct 24, 2020 |
| Packard Be... | EasyNote LE69KB             | [5d55b9b791](https://linux-hardware.org/?probe=5d55b9b791) | Oct 23, 2020 |
| Acer          | Nitro AN515-52              | [21ce46139c](https://linux-hardware.org/?probe=21ce46139c) | Oct 19, 2020 |
| Dell          | Inspiron 5720               | [56476b8a3b](https://linux-hardware.org/?probe=56476b8a3b) | Oct 16, 2020 |
| Acer          | Predator PH317-53           | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| HP            | Pavilion dv6700             | [e514981e11](https://linux-hardware.org/?probe=e514981e11) | Sep 19, 2020 |
| Toshiba       | Satellite L750              | [8a4c97a585](https://linux-hardware.org/?probe=8a4c97a585) | Sep 16, 2020 |
| HP            | Pavilion dv6700             | [d74f453116](https://linux-hardware.org/?probe=d74f453116) | Aug 16, 2020 |
| MSI           | GP75 Leopard 9SD            | [b8b363d7ff](https://linux-hardware.org/?probe=b8b363d7ff) | Aug 07, 2020 |
| Lenovo        | ThinkPad E580 20KS001RMH    | [872482ce6e](https://linux-hardware.org/?probe=872482ce6e) | Aug 07, 2020 |
| HP            | Pavilion dv6700             | [fbc9ab283a](https://linux-hardware.org/?probe=fbc9ab283a) | Aug 03, 2020 |
| HP            | Pavilion dv6700             | [b217a06354](https://linux-hardware.org/?probe=b217a06354) | Aug 02, 2020 |
| Acer          | TravelMate P215-51G         | [8916655d52](https://linux-hardware.org/?probe=8916655d52) | Jul 19, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2fdc7ceb31](https://linux-hardware.org/?probe=2fdc7ceb31) | Jul 03, 2020 |
| HP            | 240 G7 Notebook PC          | [e9c46bd761](https://linux-hardware.org/?probe=e9c46bd761) | Jun 28, 2020 |
| Acer          | Swift SF314-41              | [0255fcb566](https://linux-hardware.org/?probe=0255fcb566) | Jun 26, 2020 |
| HP            | Pavilion dv6000 (RP297UA... | [1bd24ff33d](https://linux-hardware.org/?probe=1bd24ff33d) | May 27, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [23bc453b75](https://linux-hardware.org/?probe=23bc453b75) | May 10, 2020 |
| HP            | ProBook 430 G6              | [b06dadce70](https://linux-hardware.org/?probe=b06dadce70) | May 08, 2020 |
| Acer          | Aspire ES1-512              | [79811a61ef](https://linux-hardware.org/?probe=79811a61ef) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | [ff056eb6ed](https://linux-hardware.org/?probe=ff056eb6ed) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | [b2b82bcafa](https://linux-hardware.org/?probe=b2b82bcafa) | Apr 25, 2020 |
| ASUSTek       | N56VZ                       | [c8abfa271f](https://linux-hardware.org/?probe=c8abfa271f) | Apr 20, 2020 |
| Dell          | Inspiron 5559               | [5d3e49216d](https://linux-hardware.org/?probe=5d3e49216d) | Apr 18, 2020 |
| Lenovo        | G550 20023                  | [2caebc20ee](https://linux-hardware.org/?probe=2caebc20ee) | Apr 18, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [2c05881776](https://linux-hardware.org/?probe=2c05881776) | Apr 15, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [5541279306](https://linux-hardware.org/?probe=5541279306) | Apr 14, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [9e32edc48a](https://linux-hardware.org/?probe=9e32edc48a) | Apr 14, 2020 |
| Toshiba       | Satellite C660              | [e0f010109e](https://linux-hardware.org/?probe=e0f010109e) | Apr 12, 2020 |
| Toshiba       | Satellite C660              | [4e2dc64716](https://linux-hardware.org/?probe=4e2dc64716) | Apr 02, 2020 |
| Dell          | Inspiron 5770               | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| Dell          | Latitude E6230              | [a285b7f196](https://linux-hardware.org/?probe=a285b7f196) | Mar 24, 2020 |
| Toshiba       | Satellite C50D-B            | [837144a177](https://linux-hardware.org/?probe=837144a177) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | [971d398f3d](https://linux-hardware.org/?probe=971d398f3d) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | [7d6b47f5a9](https://linux-hardware.org/?probe=7d6b47f5a9) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | [578ebcd092](https://linux-hardware.org/?probe=578ebcd092) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | [02b2574558](https://linux-hardware.org/?probe=02b2574558) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | [57cecbbbce](https://linux-hardware.org/?probe=57cecbbbce) | Mar 23, 2020 |
| Toshiba       | Satellite C50D-B            | [8633a66df2](https://linux-hardware.org/?probe=8633a66df2) | Mar 23, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [72d22ff1c1](https://linux-hardware.org/?probe=72d22ff1c1) | Mar 23, 2020 |
| Lenovo        | G50-70 20351                | [526787b49d](https://linux-hardware.org/?probe=526787b49d) | Mar 08, 2020 |
| ASUSTek       | F3Sg                        | [808275816b](https://linux-hardware.org/?probe=808275816b) | Mar 01, 2020 |
| Acer          | Aspire 5742G                | [9e4356444d](https://linux-hardware.org/?probe=9e4356444d) | Feb 28, 2020 |
| MSI           | GT62VR 6RE                  | [6bb81391a7](https://linux-hardware.org/?probe=6bb81391a7) | Feb 26, 2020 |
| Dell          | Inspiron 5720               | [83127ec84c](https://linux-hardware.org/?probe=83127ec84c) | Feb 22, 2020 |
| Dell          | Inspiron 5720               | [726965c63c](https://linux-hardware.org/?probe=726965c63c) | Feb 22, 2020 |
| Dell          | Inspiron 5720               | [de9c8254c6](https://linux-hardware.org/?probe=de9c8254c6) | Feb 22, 2020 |
| ASUSTek       | BU401LAV                    | [adba948317](https://linux-hardware.org/?probe=adba948317) | Feb 16, 2020 |
| Dell          | Inspiron 3584               | [12adda1f05](https://linux-hardware.org/?probe=12adda1f05) | Feb 09, 2020 |
| Dell          | Inspiron 3584               | [5dd6368254](https://linux-hardware.org/?probe=5dd6368254) | Feb 09, 2020 |
| Lenovo        | ThinkPad T430 2347HM4       | [126922ef61](https://linux-hardware.org/?probe=126922ef61) | Feb 02, 2020 |
| Dell          | Latitude E6230              | [809af46e15](https://linux-hardware.org/?probe=809af46e15) | Jan 26, 2020 |
| Dell          | Inspiron 1720               | [14c0a5f6f7](https://linux-hardware.org/?probe=14c0a5f6f7) | Jan 24, 2020 |
| Dell          | Inspiron 5720               | [e681ea16dc](https://linux-hardware.org/?probe=e681ea16dc) | Jan 08, 2020 |
| HP            | Laptop 15-db0xxx            | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Lenovo        | ThinkPad T400 6475GC8       | [8263c74190](https://linux-hardware.org/?probe=8263c74190) | Dec 15, 2019 |
| HP            | EliteBook 840 G3            | [90bee29cfb](https://linux-hardware.org/?probe=90bee29cfb) | Dec 08, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | [f7ce0a6b8b](https://linux-hardware.org/?probe=f7ce0a6b8b) | Dec 06, 2019 |
| Lenovo        | ThinkPad X201 Tablet 311... | [a67a12b126](https://linux-hardware.org/?probe=a67a12b126) | Dec 02, 2019 |
| Dell          | Latitude D630               | [64fec98df4](https://linux-hardware.org/?probe=64fec98df4) | Nov 28, 2019 |
| Acer          | Aspire A515-52G             | [0804d7107b](https://linux-hardware.org/?probe=0804d7107b) | Nov 24, 2019 |
| Acer          | Aspire 5739G                | [363190383f](https://linux-hardware.org/?probe=363190383f) | Nov 23, 2019 |
| Dell          | Latitude E5510              | [e9955b821e](https://linux-hardware.org/?probe=e9955b821e) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | [b777297060](https://linux-hardware.org/?probe=b777297060) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | [ba39e36ce1](https://linux-hardware.org/?probe=ba39e36ce1) | Nov 17, 2019 |
| Acer          | Aspire 5739G                | [a749310754](https://linux-hardware.org/?probe=a749310754) | Nov 17, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | [321694ee65](https://linux-hardware.org/?probe=321694ee65) | Nov 16, 2019 |
| HP            | 250 G3                      | [65119a8793](https://linux-hardware.org/?probe=65119a8793) | Oct 17, 2019 |
| ASUSTek       | T100TA                      | [3b8a5ea4c5](https://linux-hardware.org/?probe=3b8a5ea4c5) | Oct 14, 2019 |
| Lenovo        | G70-80 80FF                 | [7c2a22f9c0](https://linux-hardware.org/?probe=7c2a22f9c0) | Oct 06, 2019 |
| Lenovo        | ThinkPad T495 20NK000HMH    | [e97740f470](https://linux-hardware.org/?probe=e97740f470) | Oct 05, 2019 |
| Lenovo        | G70-80 80FF                 | [afc0726228](https://linux-hardware.org/?probe=afc0726228) | Sep 25, 2019 |
| Dell          | Latitude E5510              | [df0c96aafe](https://linux-hardware.org/?probe=df0c96aafe) | Sep 19, 2019 |
| Dell          | Latitude E6230              | [2a12cfbc23](https://linux-hardware.org/?probe=2a12cfbc23) | Sep 18, 2019 |
| Lenovo        | G70-80 80FF                 | [2d0c5961b4](https://linux-hardware.org/?probe=2d0c5961b4) | Sep 16, 2019 |
| Lenovo        | G70-80 80FF                 | [e1fbe35814](https://linux-hardware.org/?probe=e1fbe35814) | Sep 04, 2019 |
| HP            | EliteBook 8440p             | [a689023dbd](https://linux-hardware.org/?probe=a689023dbd) | Aug 16, 2019 |
| HP            | EliteBook 8440p             | [beb52301b4](https://linux-hardware.org/?probe=beb52301b4) | Aug 16, 2019 |
| HP            | Laptop 15-bw0xx             | [d02cb45d1e](https://linux-hardware.org/?probe=d02cb45d1e) | Jul 17, 2019 |
| Lenovo        | G70-80 80FF                 | [bc2409772a](https://linux-hardware.org/?probe=bc2409772a) | Jul 02, 2019 |
| Acer          | Extensa 5220                | [c8eddeab31](https://linux-hardware.org/?probe=c8eddeab31) | Jun 30, 2019 |
| Dell          | Inspiron N5010              | [efc321ccd7](https://linux-hardware.org/?probe=efc321ccd7) | May 30, 2019 |
| Dell          | Latitude E6230              | [963d3ebfe9](https://linux-hardware.org/?probe=963d3ebfe9) | May 22, 2019 |
| Toshiba       | Satellite C660              | [57bab28e56](https://linux-hardware.org/?probe=57bab28e56) | May 09, 2019 |
| ASUSTek       | X540SA                      | [a5d1a1f3db](https://linux-hardware.org/?probe=a5d1a1f3db) | Apr 28, 2019 |
| HP            | EliteBook 8560w             | [41b1ae7140](https://linux-hardware.org/?probe=41b1ae7140) | Apr 24, 2019 |
| HP            | ProBook 455 G3              | [f8936a4237](https://linux-hardware.org/?probe=f8936a4237) | Apr 07, 2019 |
| Dell          | Inspiron 5720               | [eda1ab7b13](https://linux-hardware.org/?probe=eda1ab7b13) | Mar 20, 2019 |
| HP            | ProBook 655 G1              | [b1f95b092a](https://linux-hardware.org/?probe=b1f95b092a) | Mar 20, 2019 |
| Dell          | Inspiron 5720               | [4f91b6cf7c](https://linux-hardware.org/?probe=4f91b6cf7c) | Mar 19, 2019 |
| HP            | EliteBook 840 G3            | [be32c043b0](https://linux-hardware.org/?probe=be32c043b0) | Mar 19, 2019 |
| Lenovo        | ThinkPad P71 20HK0005PB     | [c61dcde6cf](https://linux-hardware.org/?probe=c61dcde6cf) | Feb 26, 2019 |
| HP            | ProBook 655 G1              | [2ec1ca3497](https://linux-hardware.org/?probe=2ec1ca3497) | Feb 25, 2019 |
| Dell          | Inspiron 1720               | [0b9fd4ad58](https://linux-hardware.org/?probe=0b9fd4ad58) | Nov 25, 2018 |
| HP            | ProBook 655 G1              | [60b0fba200](https://linux-hardware.org/?probe=60b0fba200) | Nov 23, 2018 |
| HP            | ProBook 655 G1              | [bb508c6afa](https://linux-hardware.org/?probe=bb508c6afa) | Nov 23, 2018 |
| Advent        | Roma                        | [36d20501b0](https://linux-hardware.org/?probe=36d20501b0) | Nov 16, 2018 |
| Advent        | Roma                        | [d7e4c674fb](https://linux-hardware.org/?probe=d7e4c674fb) | Nov 13, 2018 |
| ASUSTek       | N53SM                       | [4d5ff2b12c](https://linux-hardware.org/?probe=4d5ff2b12c) | Nov 12, 2018 |
| Advent        | Roma                        | [7f39913676](https://linux-hardware.org/?probe=7f39913676) | Nov 12, 2018 |
| HP            | Laptop 15-bw0xx             | [dd3560057b](https://linux-hardware.org/?probe=dd3560057b) | Oct 18, 2018 |
| ASUSTek       | X551MA                      | [941fa4532f](https://linux-hardware.org/?probe=941fa4532f) | Sep 16, 2018 |
| ASUSTek       | X551MA                      | [41403ed51e](https://linux-hardware.org/?probe=41403ed51e) | Sep 16, 2018 |
| Lenovo        | G70-80 80FF                 | [b2df76fa94](https://linux-hardware.org/?probe=b2df76fa94) | Jul 10, 2018 |
| Lenovo        | G70-80 80FF                 | [10158213c2](https://linux-hardware.org/?probe=10158213c2) | Jul 10, 2018 |
| Lenovo        | G70-80 80FF                 | [2c5daea589](https://linux-hardware.org/?probe=2c5daea589) | Jul 04, 2018 |
| Lenovo        | G70-80 80FF                 | [a6f7825946](https://linux-hardware.org/?probe=a6f7825946) | Jul 02, 2018 |
| Lenovo        | G70-80 80FF                 | [f57d532308](https://linux-hardware.org/?probe=f57d532308) | Jul 02, 2018 |
| Lenovo        | G70-80 80FF                 | [e1833971bd](https://linux-hardware.org/?probe=e1833971bd) | Jun 30, 2018 |
| Lenovo        | G70-80 80FF                 | [81a1c4ab2a](https://linux-hardware.org/?probe=81a1c4ab2a) | Jun 29, 2018 |
| Acer          | Aspire V5-552G              | [06f831207c](https://linux-hardware.org/?probe=06f831207c) | May 12, 2018 |
| HP            | Laptop 15-bw0xx             | [962546fb29](https://linux-hardware.org/?probe=962546fb29) | Mar 17, 2018 |
| Dell          | XPS MXC062                  | [c4448e72da](https://linux-hardware.org/?probe=c4448e72da) | Mar 01, 2018 |
| Samsung       | R528/R728                   | [f4aac127be](https://linux-hardware.org/?probe=f4aac127be) | Feb 24, 2018 |
| ASUSTek       | K73BE                       | [a66962c2cb](https://linux-hardware.org/?probe=a66962c2cb) | Jan 22, 2018 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [736fd47a6c](https://linux-hardware.org/?probe=736fd47a6c) | Nov 09, 2017 |
| ASUSTek       | X553MA                      | [27e37bc3c6](https://linux-hardware.org/?probe=27e37bc3c6) | Nov 04, 2017 |
| ASUSTek       | X551MA                      | [b32fe81f6d](https://linux-hardware.org/?probe=b32fe81f6d) | Sep 21, 2017 |
| ASUSTek       | X553MA                      | [140ec82ebd](https://linux-hardware.org/?probe=140ec82ebd) | Sep 01, 2017 |
| Dell          | XPS L501X                   | [dad4007dd5](https://linux-hardware.org/?probe=dad4007dd5) | Jul 30, 2017 |
| Dell          | Inspiron 1720               | [c9ecc51acf](https://linux-hardware.org/?probe=c9ecc51acf) | Jul 14, 2017 |
| eMachines     | Unknown                     | [ed52c8a528](https://linux-hardware.org/?probe=ed52c8a528) | Apr 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [3e8f4ab377](https://linux-hardware.org/?probe=3e8f4ab377) | Mar 31, 2017 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [0d0109d420](https://linux-hardware.org/?probe=0d0109d420) | Mar 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [dff502b943](https://linux-hardware.org/?probe=dff502b943) | Mar 25, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [7be53aba27](https://linux-hardware.org/?probe=7be53aba27) | Mar 22, 2017 |
| ASUSTek       | K73BE                       | [6b5bb270b2](https://linux-hardware.org/?probe=6b5bb270b2) | Mar 19, 2017 |
| ASUSTek       | K73BE                       | [1d9f061e4c](https://linux-hardware.org/?probe=1d9f061e4c) | Mar 07, 2017 |
| ASUSTek       | K73BE                       | [6b509a3d0e](https://linux-hardware.org/?probe=6b509a3d0e) | Feb 24, 2017 |
| ASUSTek       | F9S                         | [932ca241f8](https://linux-hardware.org/?probe=932ca241f8) | Feb 19, 2017 |
| ASUSTek       | K73BE                       | [507f596da6](https://linux-hardware.org/?probe=507f596da6) | Jan 10, 2017 |
| ASUSTek       | K53SD                       | [7ccf014558](https://linux-hardware.org/?probe=7ccf014558) | Nov 06, 2016 |
| ASUSTek       | K73BE                       | [82bb80bbc4](https://linux-hardware.org/?probe=82bb80bbc4) | Nov 03, 2016 |
| ASUSTek       | K73BE                       | [a006bee75a](https://linux-hardware.org/?probe=a006bee75a) | Oct 30, 2016 |
| ASUSTek       | K73BE                       | [bf7bf43a14](https://linux-hardware.org/?probe=bf7bf43a14) | Oct 30, 2016 |
| Dell          | Inspiron 1720               | [94502c2b70](https://linux-hardware.org/?probe=94502c2b70) | Oct 26, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 21        | 12.5%   |
| ROSA R11            | 14        | 8.33%   |
| Ubuntu 18.04        | 9         | 5.36%   |
| ROSA R9             | 7         | 4.17%   |
| ROSA R10            | 6         | 3.57%   |
| ROSA R8.1           | 5         | 2.98%   |
| ROSA R11.1          | 5         | 2.98%   |
| Debian 11           | 5         | 2.98%   |
| Arch                | 5         | 2.98%   |
| ROSA R8             | 4         | 2.38%   |
| Pop!_OS 21.04       | 4         | 2.38%   |
| Pop!_OS 20.10       | 4         | 2.38%   |
| Ubuntu 21.04        | 3         | 1.79%   |
| Ubuntu 19.10        | 3         | 1.79%   |
| ROSA 12.1           | 3         | 1.79%   |
| KDE neon 20.04      | 3         | 1.79%   |
| Fedora 34           | 3         | 1.79%   |
| Ubuntu 21.10        | 2         | 1.19%   |
| Ubuntu 20.10        | 2         | 1.19%   |
| Ubuntu 16.04        | 2         | 1.19%   |
| Pop!_OS 21.10       | 2         | 1.19%   |
| Linux Mint 20.1     | 2         | 1.19%   |
| Linux Mint 20       | 2         | 1.19%   |
| Linux Mint 19       | 2         | 1.19%   |
| Linux Mint 18.3     | 2         | 1.19%   |
| Debian Testing      | 2         | 1.19%   |
| Debian 10           | 2         | 1.19%   |
| ArcoLinux Rolling   | 2         | 1.19%   |
| Arch Rolling        | 2         | 1.19%   |
| Xubuntu 21.04       | 1         | 0.6%    |
| Xubuntu 20.04       | 1         | 0.6%    |
| Ubuntu MATE 16.04   | 1         | 0.6%    |
| Ubuntu Budgie 16.04 | 1         | 0.6%    |
| Ubuntu 19.04        | 1         | 0.6%    |
| Ubuntu 18.10        | 1         | 0.6%    |
| Ubuntu              | 1         | 0.6%    |
| SteamOS 3.2         | 1         | 0.6%    |
| Solus 4.1           | 1         | 0.6%    |
| ROSA R12            | 1         | 0.6%    |
| ROSA 12.2           | 1         | 0.6%    |
| Pop!_OS 20.04       | 1         | 0.6%    |
| Peppermint 10       | 1         | 0.6%    |
| Parrot 4.10         | 1         | 0.6%    |
| OpenMandriva 4.50   | 1         | 0.6%    |
| OpenMandriva 4.3    | 1         | 0.6%    |
| OpenMandriva 4.2    | 1         | 0.6%    |
| MX 19               | 1         | 0.6%    |
| Manjaro 20.2.1      | 1         | 0.6%    |
| Manjaro 20.2        | 1         | 0.6%    |
| Manjaro 20.1.2      | 1         | 0.6%    |
| Manjaro 20.0        | 1         | 0.6%    |
| Manjaro 18.0.4      | 1         | 0.6%    |
| Manjaro             | 1         | 0.6%    |
| Linux Mint 20.3     | 1         | 0.6%    |
| Linux Mint 19.3     | 1         | 0.6%    |
| Linux Mint 19.2     | 1         | 0.6%    |
| Linux Mint 18       | 1         | 0.6%    |
| Kali 2020.1         | 1         | 0.6%    |
| Kali 2019.2         | 1         | 0.6%    |
| Fedora 36           | 1         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 45        | 30%     |
| ROSA          | 32        | 21.33%  |
| Linux Mint    | 11        | 7.33%   |
| Pop!_OS       | 10        | 6.67%   |
| Debian        | 9         | 6%      |
| Arch          | 7         | 4.67%   |
| Fedora        | 6         | 4%      |
| Manjaro       | 5         | 3.33%   |
| OpenMandriva  | 3         | 2%      |
| KDE neon      | 3         | 2%      |
| Elementary    | 3         | 2%      |
| ArcoLinux     | 3         | 2%      |
| Xubuntu       | 2         | 1.33%   |
| Kali          | 2         | 1.33%   |
| Endless       | 2         | 1.33%   |
| Ubuntu MATE   | 1         | 0.67%   |
| Ubuntu Budgie | 1         | 0.67%   |
| SteamOS       | 1         | 0.67%   |
| Solus         | 1         | 0.67%   |
| Peppermint    | 1         | 0.67%   |
| Parrot        | 1         | 0.67%   |
| MX            | 1         | 0.67%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 4.9.20-nrj-desktop-1rosa-x86_64    | 6         | 3.16%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 6         | 3.16%   |
| 5.4.0-42-generic                   | 4         | 2.11%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 2.11%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 4         | 2.11%   |
| 5.8.0-7630-generic                 | 3         | 1.58%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 3         | 1.58%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 3         | 1.58%   |
| 4.15.0-desktop-60.7rosa-x86_64     | 3         | 1.58%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 3         | 1.58%   |
| 5.8.0-48-generic                   | 2         | 1.05%   |
| 5.4.83-generic-2rosa-x86_64        | 2         | 1.05%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 1.05%   |
| 5.4.0-80-generic                   | 2         | 1.05%   |
| 5.4.0-54-generic                   | 2         | 1.05%   |
| 5.4.0-26-generic                   | 2         | 1.05%   |
| 5.13.6-arch1-1                     | 2         | 1.05%   |
| 5.13.0-25-generic                  | 2         | 1.05%   |
| 5.11.0-43-generic                  | 2         | 1.05%   |
| 5.10.0-8-amd64                     | 2         | 1.05%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 2         | 1.05%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 2         | 1.05%   |
| 4.18.0-18-generic                  | 2         | 1.05%   |
| 4.15.0-desktop-68.5rosa-x86_64     | 2         | 1.05%   |
| 4.15.0-54-generic                  | 2         | 1.05%   |
| 4.10.0-38-generic                  | 2         | 1.05%   |
| 4.1.38-nrj-desktop-1rosa-x86_64    | 2         | 1.05%   |
| 5.9.8-2-MANJARO                    | 1         | 0.53%   |
| 5.9.0-5-amd64                      | 1         | 0.53%   |
| 5.8.16-2-MANJARO                   | 1         | 0.53%   |
| 5.8.13-050813-generic              | 1         | 0.53%   |
| 5.8.0-53-generic                   | 1         | 0.53%   |
| 5.8.0-45-generic                   | 1         | 0.53%   |
| 5.8.0-33-generic                   | 1         | 0.53%   |
| 5.8.0-29-generic                   | 1         | 0.53%   |
| 5.8.0-25-generic                   | 1         | 0.53%   |
| 5.8.0-1parrot1-amd64               | 1         | 0.53%   |
| 5.7.5-arch1-1                      | 1         | 0.53%   |
| 5.6.18-156.current                 | 1         | 0.53%   |
| 5.5.5-arch1-1                      | 1         | 0.53%   |
| 5.5.16-200.fc31.x86_64             | 1         | 0.53%   |
| 5.5.13-zen2-1-zen                  | 1         | 0.53%   |
| 5.4.72-generic-1rosa-x86_64        | 1         | 0.53%   |
| 5.4.72-1-lts                       | 1         | 0.53%   |
| 5.4.33-3-MANJARO                   | 1         | 0.53%   |
| 5.4.0-kali3-amd64                  | 1         | 0.53%   |
| 5.4.0-desktop-14.1rosa-x86_64      | 1         | 0.53%   |
| 5.4.0-99-generic                   | 1         | 0.53%   |
| 5.4.0-89-generic                   | 1         | 0.53%   |
| 5.4.0-84-generic                   | 1         | 0.53%   |
| 5.4.0-77-generic                   | 1         | 0.53%   |
| 5.4.0-73-generic                   | 1         | 0.53%   |
| 5.4.0-67-generic                   | 1         | 0.53%   |
| 5.4.0-66-generic                   | 1         | 0.53%   |
| 5.4.0-65-generic                   | 1         | 0.53%   |
| 5.4.0-53-generic                   | 1         | 0.53%   |
| 5.4.0-52-generic                   | 1         | 0.53%   |
| 5.4.0-51-generic                   | 1         | 0.53%   |
| 5.4.0-47-generic                   | 1         | 0.53%   |
| 5.4.0-40-generic                   | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 26        | 14.53%  |
| 4.15.0  | 21        | 11.73%  |
| 5.11.0  | 11        | 6.15%   |
| 5.8.0   | 10        | 5.59%   |
| 5.13.0  | 9         | 5.03%   |
| 5.3.0   | 6         | 3.35%   |
| 5.10.0  | 6         | 3.35%   |
| 4.9.20  | 6         | 3.35%   |
| 5.10.74 | 4         | 2.23%   |
| 5.0.0   | 4         | 2.23%   |
| 4.9.60  | 4         | 2.23%   |
| 4.18.0  | 4         | 2.23%   |
| 4.9.41  | 3         | 1.68%   |
| 4.9.155 | 3         | 1.68%   |
| 4.1.34  | 3         | 1.68%   |
| 5.4.83  | 2         | 1.12%   |
| 5.4.72  | 2         | 1.12%   |
| 5.4.32  | 2         | 1.12%   |
| 5.17.1  | 2         | 1.12%   |
| 5.13.6  | 2         | 1.12%   |
| 5.13.12 | 2         | 1.12%   |
| 5.12.14 | 2         | 1.12%   |
| 4.9.9   | 2         | 1.12%   |
| 4.9.124 | 2         | 1.12%   |
| 4.4.0   | 2         | 1.12%   |
| 4.10.0  | 2         | 1.12%   |
| 4.1.38  | 2         | 1.12%   |
| 5.9.8   | 1         | 0.56%   |
| 5.9.0   | 1         | 0.56%   |
| 5.8.16  | 1         | 0.56%   |
| 5.8.13  | 1         | 0.56%   |
| 5.7.5   | 1         | 0.56%   |
| 5.6.18  | 1         | 0.56%   |
| 5.5.5   | 1         | 0.56%   |
| 5.5.16  | 1         | 0.56%   |
| 5.5.13  | 1         | 0.56%   |
| 5.4.33  | 1         | 0.56%   |
| 5.2.17  | 1         | 0.56%   |
| 5.16.7  | 1         | 0.56%   |
| 5.16.16 | 1         | 0.56%   |
| 5.16.15 | 1         | 0.56%   |
| 5.15.7  | 1         | 0.56%   |
| 5.15.4  | 1         | 0.56%   |
| 5.15.11 | 1         | 0.56%   |
| 5.14.9  | 1         | 0.56%   |
| 5.14.5  | 1         | 0.56%   |
| 5.14.18 | 1         | 0.56%   |
| 5.14.0  | 1         | 0.56%   |
| 5.13.14 | 1         | 0.56%   |
| 5.12.4  | 1         | 0.56%   |
| 5.12.19 | 1         | 0.56%   |
| 5.12.13 | 1         | 0.56%   |
| 5.12.1  | 1         | 0.56%   |
| 5.10.28 | 1         | 0.56%   |
| 5.10.2  | 1         | 0.56%   |
| 5.10.14 | 1         | 0.56%   |
| 4.9.95  | 1         | 0.56%   |
| 4.9.76  | 1         | 0.56%   |
| 4.20.12 | 1         | 0.56%   |
| 4.19.75 | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 31        | 18.45%  |
| 4.15    | 21        | 12.5%   |
| 4.9     | 16        | 9.52%   |
| 5.13    | 13        | 7.74%   |
| 5.10    | 13        | 7.74%   |
| 5.8     | 12        | 7.14%   |
| 5.11    | 11        | 6.55%   |
| 5.3     | 6         | 3.57%   |
| 5.12    | 6         | 3.57%   |
| 5.0     | 4         | 2.38%   |
| 4.18    | 4         | 2.38%   |
| 4.1     | 4         | 2.38%   |
| 5.5     | 3         | 1.79%   |
| 5.16    | 3         | 1.79%   |
| 5.15    | 3         | 1.79%   |
| 5.14    | 3         | 1.79%   |
| 5.9     | 2         | 1.19%   |
| 5.17    | 2         | 1.19%   |
| 4.4     | 2         | 1.19%   |
| 4.19    | 2         | 1.19%   |
| 4.10    | 2         | 1.19%   |
| 5.7     | 1         | 0.6%    |
| 5.6     | 1         | 0.6%    |
| 5.2     | 1         | 0.6%    |
| 4.20    | 1         | 0.6%    |
| 4.13    | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 138       | 94.52%  |
| i686   | 8         | 5.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 62        | 38.99%  |
| KDE4       | 24        | 15.09%  |
| KDE5       | 23        | 14.47%  |
| Unknown    | 15        | 9.43%   |
| XFCE       | 9         | 5.66%   |
| MATE       | 6         | 3.77%   |
| KDE        | 4         | 2.52%   |
| Budgie     | 4         | 2.52%   |
| X-Cinnamon | 3         | 1.89%   |
| Pantheon   | 3         | 1.89%   |
| Unity      | 2         | 1.26%   |
| Cinnamon   | 2         | 1.26%   |
| LXQt       | 1         | 0.63%   |
| LXDE       | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 122       | 81.33%  |
| Wayland | 17        | 11.33%  |
| Unknown | 8         | 5.33%   |
| Tty     | 3         | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 56        | 36.84%  |
| GDM     | 29        | 19.08%  |
| KDM     | 24        | 15.79%  |
| SDDM    | 20        | 13.16%  |
| TDM     | 11        | 7.24%   |
| LightDM | 8         | 5.26%   |
| GDM3    | 2         | 1.32%   |
| SLiM    | 1         | 0.66%   |
| MDM     | 1         | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 68        | 44.44%  |
| Unknown     | 42        | 27.45%  |
| ru_RU       | 16        | 10.46%  |
| lv_LV       | 16        | 10.46%  |
| en_GB       | 7         | 4.58%   |
| C           | 2         | 1.31%   |
| ru_RU.UTF_8 | 1         | 0.65%   |
| de_DE       | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 77        | 52.38%  |
| EFI  | 70        | 47.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 117       | 78%     |
| Unknown | 16        | 10.67%  |
| Btrfs   | 10        | 6.67%   |
| Overlay | 6         | 4%      |
| Zfs     | 1         | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 66        | 43.71%  |
| GPT     | 52        | 34.44%  |
| MBR     | 33        | 21.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 140       | 90.91%  |
| Yes       | 14        | 9.09%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 110       | 73.33%  |
| Yes       | 40        | 26.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 33        | 22.6%   |
| Hewlett-Packard     | 26        | 17.81%  |
| ASUSTek Computer    | 25        | 17.12%  |
| Dell                | 23        | 15.75%  |
| Acer                | 16        | 10.96%  |
| Toshiba             | 5         | 3.42%   |
| Samsung Electronics | 4         | 2.74%   |
| MSI                 | 2         | 1.37%   |
| Valve               | 1         | 0.68%   |
| Timi                | 1         | 0.68%   |
| Sony                | 1         | 0.68%   |
| Razer               | 1         | 0.68%   |
| Quanta              | 1         | 0.68%   |
| Packard Bell        | 1         | 0.68%   |
| HUAWEI              | 1         | 0.68%   |
| Fujitsu Siemens     | 1         | 0.68%   |
| Fujitsu             | 1         | 0.68%   |
| eMachines           | 1         | 0.68%   |
| Apple               | 1         | 0.68%   |
| Advent              | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP EliteBook 840 G3                                   | 3         | 2.05%   |
| Toshiba Satellite C660                                | 2         | 1.37%   |
| Lenovo IdeaPad 300-15ISK 80Q7                         | 2         | 1.37%   |
| Lenovo IdeaPad 100-15IBD 80QQ                         | 2         | 1.37%   |
| HP 250 G6 Notebook PC                                 | 2         | 1.37%   |
| ASUS ZenBook UX431DA_UM431DA                          | 2         | 1.37%   |
| ASUS X551MA                                           | 2         | 1.37%   |
| Valve Jupiter                                         | 1         | 0.68%   |
| Toshiba Satellite L850-1LK                            | 1         | 0.68%   |
| Toshiba Satellite L750                                | 1         | 0.68%   |
| Toshiba Satellite C50D-B                              | 1         | 0.68%   |
| Timi A35S                                             | 1         | 0.68%   |
| Sony VPCCW2S8E                                        | 1         | 0.68%   |
| Samsung R528/R728                                     | 1         | 0.68%   |
| Samsung 355V4C/356V4C/3445VC/3545VC                   | 1         | 0.68%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.68%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B            | 1         | 0.68%   |
| Razer Blade 15 Advanced Model (Early 2021) - RZ09-036 | 1         | 0.68%   |
| Quanta TW8/SW8/DW8                                    | 1         | 0.68%   |
| Packard Bell EasyNote LE69KB                          | 1         | 0.68%   |
| MSI GT62VR 6RE                                        | 1         | 0.68%   |
| MSI GP75 Leopard 9SD                                  | 1         | 0.68%   |
| Lenovo Y50-70 20378                                   | 1         | 0.68%   |
| Lenovo V110-15IAP 80TG                                | 1         | 0.68%   |
| Lenovo ThinkPad X260 20F5S0HK1J                       | 1         | 0.68%   |
| Lenovo ThinkPad X250 20CLS2XA00                       | 1         | 0.68%   |
| Lenovo ThinkPad X230 Tablet 34382BG                   | 1         | 0.68%   |
| Lenovo ThinkPad X220 4291Q50                          | 1         | 0.68%   |
| Lenovo ThinkPad X201 Tablet 311396U                   | 1         | 0.68%   |
| Lenovo ThinkPad T60 8741W3M                           | 1         | 0.68%   |
| Lenovo ThinkPad T495 20NK000HMH                       | 1         | 0.68%   |
| Lenovo ThinkPad T430 2347HM4                          | 1         | 0.68%   |
| Lenovo ThinkPad T420 4180ED3                          | 1         | 0.68%   |
| Lenovo ThinkPad T400 6475GC8                          | 1         | 0.68%   |
| Lenovo ThinkPad T15 Gen 1 20S6005JMH                  | 1         | 0.68%   |
| Lenovo ThinkPad P71 20HK0005PB                        | 1         | 0.68%   |
| Lenovo ThinkPad P70 20ER0035MH                        | 1         | 0.68%   |
| Lenovo ThinkPad P14s Gen 1 20Y1000HMH                 | 1         | 0.68%   |
| Lenovo ThinkPad L390 20NRCTO1WW                       | 1         | 0.68%   |
| Lenovo ThinkPad E580 20KS001RMH                       | 1         | 0.68%   |
| Lenovo ThinkPad E490 20N8005JMH                       | 1         | 0.68%   |
| Lenovo ThinkPad E15 Gen 2 20T80054MH                  | 1         | 0.68%   |
| Lenovo ThinkPad E14 Gen 2 20T60026MH                  | 1         | 0.68%   |
| Lenovo Legion Y530-15ICH 81FV                         | 1         | 0.68%   |
| Lenovo IdeaPad S340-15API 81NC                        | 1         | 0.68%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY                  | 1         | 0.68%   |
| Lenovo IdeaPad 320-15ISK 80XH                         | 1         | 0.68%   |
| Lenovo G70-80 80FF                                    | 1         | 0.68%   |
| Lenovo G550 20023                                     | 1         | 0.68%   |
| Lenovo G50-80 80E5                                    | 1         | 0.68%   |
| Lenovo G50-70 20351                                   | 1         | 0.68%   |
| HUAWEI MACHD-WXX9                                     | 1         | 0.68%   |
| HP ProBook 655 G1                                     | 1         | 0.68%   |
| HP ProBook 455 G3                                     | 1         | 0.68%   |
| HP ProBook 430 G6                                     | 1         | 0.68%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 1         | 0.68%   |
| HP Pavilion dv7                                       | 1         | 0.68%   |
| HP Pavilion dv6700                                    | 1         | 0.68%   |
| HP Pavilion dv6500                                    | 1         | 0.68%   |
| HP Pavilion dv6000 (RP297UA#ABA)                      | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 19        | 13.01%  |
| HP EliteBook          | 10        | 6.85%   |
| Dell Inspiron         | 10        | 6.85%   |
| Dell Latitude         | 9         | 6.16%   |
| Acer Aspire           | 8         | 5.48%   |
| Lenovo IdeaPad        | 7         | 4.79%   |
| Toshiba Satellite     | 5         | 3.42%   |
| HP Pavilion           | 5         | 3.42%   |
| ASUS VivoBook         | 4         | 2.74%   |
| HP ProBook            | 3         | 2.05%   |
| HP 250                | 3         | 2.05%   |
| HP Laptop             | 2         | 1.37%   |
| Dell XPS              | 2         | 1.37%   |
| ASUS ZenBook          | 2         | 1.37%   |
| ASUS X551MA           | 2         | 1.37%   |
| ASUS TUF              | 2         | 1.37%   |
| Acer Nitro            | 2         | 1.37%   |
| Valve Jupiter         | 1         | 0.68%   |
| Timi A35S             | 1         | 0.68%   |
| Sony VPCCW2S8E        | 1         | 0.68%   |
| Samsung R528          | 1         | 0.68%   |
| Samsung 355V4C        | 1         | 0.68%   |
| Samsung 350V5C        | 1         | 0.68%   |
| Samsung 300V3A        | 1         | 0.68%   |
| Razer Blade           | 1         | 0.68%   |
| Quanta TW8            | 1         | 0.68%   |
| Packard Bell EasyNote | 1         | 0.68%   |
| MSI GT62VR            | 1         | 0.68%   |
| MSI GP75              | 1         | 0.68%   |
| Lenovo Y50-70         | 1         | 0.68%   |
| Lenovo V110-15IAP     | 1         | 0.68%   |
| Lenovo Legion         | 1         | 0.68%   |
| Lenovo G70-80         | 1         | 0.68%   |
| Lenovo G550           | 1         | 0.68%   |
| Lenovo G50-80         | 1         | 0.68%   |
| Lenovo G50-70         | 1         | 0.68%   |
| HUAWEI MACHD-WXX9     | 1         | 0.68%   |
| HP HDX                | 1         | 0.68%   |
| HP G62                | 1         | 0.68%   |
| HP 240                | 1         | 0.68%   |
| Fujitsu STYLISTIC     | 1         | 0.68%   |
| Fujitsu Siemens AMILO | 1         | 0.68%   |
| Dell Vostro           | 1         | 0.68%   |
| Dell G3               | 1         | 0.68%   |
| ASUS X751LD           | 1         | 0.68%   |
| ASUS X553MA           | 1         | 0.68%   |
| ASUS X540SA           | 1         | 0.68%   |
| ASUS T100TA           | 1         | 0.68%   |
| ASUS N56VZ            | 1         | 0.68%   |
| ASUS N56VM            | 1         | 0.68%   |
| ASUS N550JV           | 1         | 0.68%   |
| ASUS N53SM            | 1         | 0.68%   |
| ASUS K73BE            | 1         | 0.68%   |
| ASUS K53SD            | 1         | 0.68%   |
| ASUS F9S              | 1         | 0.68%   |
| ASUS F3Sg             | 1         | 0.68%   |
| ASUS E402SA           | 1         | 0.68%   |
| ASUS BU401LAV         | 1         | 0.68%   |
| ASUS ASUS             | 1         | 0.68%   |
| Apple MacBookPro8     | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 15        | 10.27%  |
| 2013 | 14        | 9.59%   |
| 2018 | 12        | 8.22%   |
| 2014 | 12        | 8.22%   |
| 2020 | 11        | 7.53%   |
| 2015 | 11        | 7.53%   |
| 2011 | 10        | 6.85%   |
| 2010 | 10        | 6.85%   |
| 2017 | 8         | 5.48%   |
| 2012 | 8         | 5.48%   |
| 2008 | 8         | 5.48%   |
| 2016 | 7         | 4.79%   |
| 2007 | 7         | 4.79%   |
| 2021 | 5         | 3.42%   |
| 2009 | 5         | 3.42%   |
| 2006 | 2         | 1.37%   |
| 2022 | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 146       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 133       | 89.86%  |
| Enabled  | 15        | 10.14%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 145       | 99.32%  |
| Yes  | 1         | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 46        | 31.29%  |
| 4.01-8.0   | 40        | 27.21%  |
| 8.01-16.0  | 23        | 15.65%  |
| 16.01-24.0 | 20        | 13.61%  |
| 32.01-64.0 | 5         | 3.4%    |
| 1.01-2.0   | 5         | 3.4%    |
| 2.01-3.0   | 4         | 2.72%   |
| 24.01-32.0 | 2         | 1.36%   |
| 0.51-1.0   | 2         | 1.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 53        | 32.32%  |
| 2.01-3.0   | 42        | 25.61%  |
| 0.51-1.0   | 24        | 14.63%  |
| 4.01-8.0   | 21        | 12.8%   |
| 3.01-4.0   | 17        | 10.37%  |
| 8.01-16.0  | 4         | 2.44%   |
| 16.01-24.0 | 2         | 1.22%   |
| 0.01-0.5   | 1         | 0.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 108       | 72.97%  |
| 2      | 35        | 23.65%  |
| 3      | 4         | 2.7%    |
| 0      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 85        | 57.05%  |
| Yes       | 64        | 42.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 91.16%  |
| No        | 13        | 8.84%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 98.63%  |
| No        | 2         | 1.37%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 76.51%  |
| No        | 35        | 23.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Latvia  | 146       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Riga          | 114       | 75%     |
| Daugavpils    | 6         | 3.95%   |
| JЕ«rmala    | 3         | 1.97%   |
| Ogre          | 2         | 1.32%   |
| LiepДЃja    | 2         | 1.32%   |
| Jelgava       | 2         | 1.32%   |
| Jaunmarupe    | 2         | 1.32%   |
| Dobele        | 2         | 1.32%   |
| VecvДЃrkava | 1         | 0.66%   |
| Valmiera      | 1         | 0.66%   |
| Ungurpils     | 1         | 0.66%   |
| Tukums        | 1         | 0.66%   |
| Tiraine       | 1         | 0.66%   |
| Sigulda       | 1         | 0.66%   |
| Saldus        | 1         | 0.66%   |
| Salaspils     | 1         | 0.66%   |
| Ozolnieki     | 1         | 0.66%   |
| LiepÄja    | 1         | 0.66%   |
| KДЃrsava    | 1         | 0.66%   |
| Koknese       | 1         | 0.66%   |
| Gulbene       | 1         | 0.66%   |
| Eleja         | 1         | 0.66%   |
| Carnikava     | 1         | 0.66%   |
| Balvi         | 1         | 0.66%   |
| Auce          | 1         | 0.66%   |
| AlЕ«ksne    | 1         | 0.66%   |
| Adazi         | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 27        | 33     | 15%     |
| Seagate                 | 25        | 33     | 13.89%  |
| Kingston                | 22        | 25     | 12.22%  |
| Toshiba                 | 20        | 24     | 11.11%  |
| WDC                     | 18        | 28     | 10%     |
| Hitachi                 | 9         | 12     | 5%      |
| SK Hynix                | 7         | 7      | 3.89%   |
| Unknown                 | 6         | 7      | 3.33%   |
| HGST                    | 6         | 16     | 3.33%   |
| Sandisk                 | 5         | 10     | 2.78%   |
| Patriot                 | 4         | 7      | 2.22%   |
| Micron Technology       | 3         | 3      | 1.67%   |
| KIOXIA                  | 3         | 4      | 1.67%   |
| Intel                   | 3         | 5      | 1.67%   |
| Crucial                 | 3         | 3      | 1.67%   |
| A-DATA Technology       | 3         | 4      | 1.67%   |
| LITEON                  | 2         | 2      | 1.11%   |
| Verbatim                | 1         | 1      | 0.56%   |
| USB                     | 1         | 1      | 0.56%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.56%   |
| Union Memory            | 1         | 1      | 0.56%   |
| Realtek                 | 1         | 1      | 0.56%   |
| PNY                     | 1         | 1      | 0.56%   |
| PLEXTOR                 | 1         | 1      | 0.56%   |
| Phison                  | 1         | 1      | 0.56%   |
| OCZ                     | 1         | 1      | 0.56%   |
| LITEONIT                | 1         | 1      | 0.56%   |
| KingSpec                | 1         | 1      | 0.56%   |
| Intenso                 | 1         | 1      | 0.56%   |
| Integral                | 1         | 1      | 0.56%   |
| China                   | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB              | 5         | 2.7%    |
| Kingston SA400S37240G 240GB SSD              | 5         | 2.7%    |
| Samsung SSD 850 EVO 500GB                    | 4         | 2.16%   |
| Toshiba MQ04ABF100 1TB                       | 3         | 1.62%   |
| Toshiba MQ01ABF050 500GB                     | 3         | 1.62%   |
| Seagate ST1000LM048-2E7172 1TB               | 3         | 1.62%   |
| Seagate ST1000LM035-1RK172 1TB               | 3         | 1.62%   |
| Hitachi HTS547575A9E384 752GB                | 3         | 1.62%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 2         | 1.08%   |
| Toshiba MQ01ABD100 1TB                       | 2         | 1.08%   |
| SK Hynix HFM512GDJTNG-8310A 512GB            | 2         | 1.08%   |
| SK Hynix BC511 NVMe 256GB                    | 2         | 1.08%   |
| Seagate ST9160821AS 160GB                    | 2         | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 1.08%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD          | 2         | 1.08%   |
| Sandisk NVMe SSD Drive 256GB                 | 2         | 1.08%   |
| Samsung SSD 860 EVO 500GB                    | 2         | 1.08%   |
| Samsung NVMe SSD Drive 1TB                   | 2         | 1.08%   |
| Samsung HM321HI 320GB                        | 2         | 1.08%   |
| Patriot Burst 240GB SSD                      | 2         | 1.08%   |
| KIOXIA KBG40ZNS512G NVMe 512GB               | 2         | 1.08%   |
| Kingston SV300S37A60G 64GB SSD               | 2         | 1.08%   |
| Kingston SA400S37480G 480GB SSD              | 2         | 1.08%   |
| Kingston SA400S37120G 120GB SSD              | 2         | 1.08%   |
| Hitachi HTS545050B9A300 500GB                | 2         | 1.08%   |
| Hitachi HTS545050A7E380 500GB                | 2         | 1.08%   |
| HGST HTS725032A7E630 320GB                   | 2         | 1.08%   |
| HGST HTS545050A7E680 500GB                   | 2         | 1.08%   |
| WDC WD5000LPVT-75G33T0 500GB                 | 1         | 0.54%   |
| WDC WD5000LPCX-24C6HT0 500GB                 | 1         | 0.54%   |
| WDC WD5000BPKT-75PK4T0 500GB                 | 1         | 0.54%   |
| WDC WD3200BEVT-75ZCT0 320GB                  | 1         | 0.54%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 0.54%   |
| WDC WD3200BEVS-26VAT0 320GB                  | 1         | 0.54%   |
| WDC WD2500BEKT-60PVMT0 250GB                 | 1         | 0.54%   |
| WDC WD1600BEVS-60RST0 160GB                  | 1         | 0.54%   |
| WDC WD1200BEVS-22UST0 120GB                  | 1         | 0.54%   |
| WDC WD10SPZX-24Z10 1TB                       | 1         | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB                     | 1         | 0.54%   |
| WDC WD10JPVX-60JC3T1 1TB                     | 1         | 0.54%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 0.54%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB         | 1         | 0.54%   |
| WDC PC SN720 SDAPNTW-512G-1014 512GB         | 1         | 0.54%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB         | 1         | 0.54%   |
| Verbatim Vi550 S3 SSD 128GB                  | 1         | 0.54%   |
| USB 3.1 500GB                                | 1         | 0.54%   |
| Unknown SL64G  64GB                          | 1         | 0.54%   |
| Unknown SEM32G  32GB                         | 1         | 0.54%   |
| Unknown RHDM2FDKU3A1-N3A8 256GB              | 1         | 0.54%   |
| Unknown NVMe SSD Drive 512GB                 | 1         | 0.54%   |
| Unknown MMC Card  32GB                       | 1         | 0.54%   |
| Unknown DA4128  128GB                        | 1         | 0.54%   |
| Unknown DA4064  64GB                         | 1         | 0.54%   |
| Union Memory RPFTJ256PDD2MWX 256GB           | 1         | 0.54%   |
| Union Memory (Shenzhen) NVMe SSD Drive 256GB | 1         | 0.54%   |
| Toshiba NVMe SSD Drive 256GB                 | 1         | 0.54%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 0.54%   |
| Toshiba MK8034GSX 80GB                       | 1         | 0.54%   |
| Toshiba MK6475GSX 640GB                      | 1         | 0.54%   |
| Toshiba MK6465GSXN 640GB                     | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 33     | 32.89%  |
| Toshiba             | 16        | 20     | 21.05%  |
| WDC                 | 15        | 24     | 19.74%  |
| Hitachi             | 9         | 12     | 11.84%  |
| HGST                | 6         | 16     | 7.89%   |
| Samsung Electronics | 4         | 4      | 5.26%   |
| USB                 | 1         | 1      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 19        | 21     | 31.15%  |
| Samsung Electronics | 16        | 18     | 26.23%  |
| Patriot             | 4         | 7      | 6.56%   |
| SanDisk             | 3         | 4      | 4.92%   |
| Crucial             | 3         | 3      | 4.92%   |
| A-DATA Technology   | 3         | 4      | 4.92%   |
| Micron Technology   | 2         | 2      | 3.28%   |
| LITEON              | 2         | 2      | 3.28%   |
| Verbatim            | 1         | 1      | 1.64%   |
| PNY                 | 1         | 1      | 1.64%   |
| PLEXTOR             | 1         | 1      | 1.64%   |
| OCZ                 | 1         | 1      | 1.64%   |
| LITEONIT            | 1         | 1      | 1.64%   |
| KingSpec            | 1         | 1      | 1.64%   |
| Intenso             | 1         | 1      | 1.64%   |
| Integral            | 1         | 1      | 1.64%   |
| China               | 1         | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 74        | 110    | 43.27%  |
| SSD     | 56        | 70     | 32.75%  |
| NVMe    | 36        | 51     | 21.05%  |
| MMC     | 4         | 5      | 2.34%   |
| Unknown | 1         | 1      | 0.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 114       | 178    | 72.15%  |
| NVMe | 36        | 50     | 22.78%  |
| SAS  | 4         | 4      | 2.53%   |
| MMC  | 4         | 5      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 88        | 123    | 68.22%  |
| 0.51-1.0   | 39        | 55     | 30.23%  |
| 1.01-2.0   | 2         | 2      | 1.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 53        | 32.52%  |
| 251-500    | 43        | 26.38%  |
| 501-1000   | 24        | 14.72%  |
| 51-100     | 12        | 7.36%   |
| 1-20       | 11        | 6.75%   |
| 1001-2000  | 10        | 6.13%   |
| 21-50      | 5         | 3.07%   |
| 2001-3000  | 3         | 1.84%   |
| Unknown    | 2         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 72        | 43.9%   |
| 21-50     | 27        | 16.46%  |
| 51-100    | 20        | 12.2%   |
| 101-250   | 18        | 10.98%  |
| 251-500   | 13        | 7.93%   |
| 501-1000  | 8         | 4.88%   |
| 1001-2000 | 4         | 2.44%   |
| Unknown   | 2         | 1.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD5000BPKT-75PK4T0 500GB         | 1         | 1      | 5.56%   |
| WDC WD3200BEVT-75ZCT0 320GB          | 1         | 4      | 5.56%   |
| WDC WD1600BEVS-60RST0 160GB          | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 5.56%   |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 5.56%   |
| Seagate ST9500420AS 500GB            | 1         | 1      | 5.56%   |
| Seagate ST9500325AS 500GB            | 1         | 6      | 5.56%   |
| Seagate ST9250827AS 250GB            | 1         | 1      | 5.56%   |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1      | 5.56%   |
| Samsung Electronics HN-M750MBB 752GB | 1         | 1      | 5.56%   |
| Kingston SV300S37A60G 64GB SSD       | 1         | 1      | 5.56%   |
| Kingston SV300S37A120G 120GB SSD     | 1         | 1      | 5.56%   |
| Hitachi HTS545050A7E380 500GB        | 1         | 1      | 5.56%   |
| Hitachi HTS542516K9SA00 160GB        | 1         | 1      | 5.56%   |
| HGST HTS725032A7E630 320GB           | 1         | 2      | 5.56%   |
| HGST HTS721010A9E630 1TB             | 1         | 3      | 5.56%   |
| HGST HTS545050A7E680 500GB           | 1         | 1      | 5.56%   |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 9      | 22.22%  |
| HGST                | 4         | 7      | 22.22%  |
| WDC                 | 3         | 6      | 16.67%  |
| Toshiba             | 2         | 2      | 11.11%  |
| Kingston            | 2         | 2      | 11.11%  |
| Hitachi             | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 9      | 25%     |
| HGST                | 4         | 7      | 25%     |
| WDC                 | 3         | 6      | 18.75%  |
| Toshiba             | 2         | 2      | 12.5%   |
| Hitachi             | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 27     | 88.24%  |
| SSD  | 2         | 2      | 11.76%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB     | 1         | 1      | 50%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 76        | 119    | 48.72%  |
| Detected | 61        | 87     | 39.1%   |
| Malfunc  | 17        | 29     | 10.9%   |
| Failed   | 2         | 2      | 1.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 116       | 67.84%  |
| AMD                          | 17        | 9.94%   |
| Samsung Electronics          | 10        | 5.85%   |
| SK Hynix                     | 7         | 4.09%   |
| Sandisk                      | 5         | 2.92%   |
| KIOXIA                       | 4         | 2.34%   |
| Toshiba America Info Systems | 3         | 1.75%   |
| Kingston Technology Company  | 3         | 1.75%   |
| Union Memory (Shenzhen)      | 2         | 1.17%   |
| Phison Electronics           | 1         | 0.58%   |
| Nvidia                       | 1         | 0.58%   |
| Micron Technology            | 1         | 0.58%   |
| ADATA Technology             | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 17        | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 8.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 11        | 5.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 5.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 3.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 3.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 3.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 3.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 3.21%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 5         | 2.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 2.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 2.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 2.67%   |
| KIOXIA Non-Volatile memory controller                                            | 4         | 2.14%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 1.6%    |
| Intel SSD 660P Series                                                            | 3         | 1.6%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.6%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 1.07%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 2         | 1.07%   |
| SK Hynix BC511                                                                   | 2         | 1.07%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.07%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.07%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 1.07%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.07%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.07%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.07%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.07%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 0.53%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.53%   |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.53%   |
| Sandisk Non-Volatile memory controller                                           | 1         | 0.53%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.53%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.53%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.53%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.53%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.53%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.53%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.53%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.53%   |
| AMD FCH IDE Controller                                                           | 1         | 0.53%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 118       | 65.19%  |
| NVMe | 38        | 20.99%  |
| IDE  | 15        | 8.29%   |
| RAID | 10        | 5.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 121       | 82.88%  |
| AMD    | 25        | 17.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 3.42%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 2.74%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 2.74%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 2.74%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 2.05%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 2.05%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.37%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.37%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.37%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.37%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.37%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.37%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.37%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 1.37%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.37%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.37%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.37%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 1.37%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 1.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.37%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.37%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.37%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.37%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.68%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.68%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.68%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.68%   |
| Intel Pentium CPU 4417U @ 2.30GHz             | 1         | 0.68%   |
| Intel Pentium 3805U @ 1.90GHz                 | 1         | 0.68%   |
| Intel Genuine CPU T2060 @ 1.60GHz             | 1         | 0.68%   |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 0.68%   |
| Intel Genuine CPU 575 @ 2.00GHz               | 1         | 0.68%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.68%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.68%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.68%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz            | 1         | 0.68%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.68%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 0.68%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.68%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 0.68%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.68%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.68%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.68%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.68%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.68%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 0.68%   |
| Intel Core i7 CPU L 640 @ 2.13GHz             | 1         | 0.68%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.68%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.68%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.68%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 23.97%  |
| Intel Core i7           | 27        | 18.49%  |
| Intel Core i3           | 16        | 10.96%  |
| Intel Core 2 Duo        | 12        | 8.22%   |
| Intel Celeron           | 11        | 7.53%   |
| Other                   | 8         | 5.48%   |
| AMD Ryzen 5             | 5         | 3.42%   |
| Intel Pentium           | 4         | 2.74%   |
| AMD Ryzen 7             | 4         | 2.74%   |
| Intel Pentium Dual-Core | 3         | 2.05%   |
| Intel Genuine           | 3         | 2.05%   |
| Intel Core 2            | 2         | 1.37%   |
| AMD Ryzen 3             | 2         | 1.37%   |
| AMD E1                  | 2         | 1.37%   |
| AMD A8                  | 2         | 1.37%   |
| AMD A10                 | 2         | 1.37%   |
| Intel Xeon              | 1         | 0.68%   |
| Intel Pentium Dual      | 1         | 0.68%   |
| Intel Atom              | 1         | 0.68%   |
| AMD Turion 64 X2 Mobile | 1         | 0.68%   |
| AMD Ryzen 7 PRO         | 1         | 0.68%   |
| AMD Ryzen 5 PRO         | 1         | 0.68%   |
| AMD E2                  | 1         | 0.68%   |
| AMD C-70                | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 91        | 61.9%   |
| 4      | 44        | 29.93%  |
| 6      | 5         | 3.4%    |
| 8      | 4         | 2.72%   |
| 1      | 3         | 2.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 146       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 99        | 67.35%  |
| 1      | 48        | 32.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 144       | 98.63%  |
| 32-bit         | 1         | 0.68%   |
| Unknown        | 1         | 0.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 13.51%  |
| 0x206a7    | 10        | 6.76%   |
| 0x406e3    | 9         | 6.08%   |
| 0x306a9    | 9         | 6.08%   |
| 0x306d4    | 6         | 4.05%   |
| 0x30678    | 6         | 4.05%   |
| 0x1067a    | 6         | 4.05%   |
| 0x906ea    | 5         | 3.38%   |
| 0x806c1    | 5         | 3.38%   |
| 0x6fd      | 5         | 3.38%   |
| 0x20655    | 5         | 3.38%   |
| 0x806ec    | 4         | 2.7%    |
| 0x40651    | 4         | 2.7%    |
| 0x08108102 | 4         | 2.7%    |
| 0x806ea    | 3         | 2.03%   |
| 0x806e9    | 3         | 2.03%   |
| 0x10676    | 3         | 2.03%   |
| 0x06001119 | 3         | 2.03%   |
| 0xa0652    | 2         | 1.35%   |
| 0x906e9    | 2         | 1.35%   |
| 0x6f6      | 2         | 1.35%   |
| 0x506e3    | 2         | 1.35%   |
| 0x406c3    | 2         | 1.35%   |
| 0x306c3    | 2         | 1.35%   |
| 0x20652    | 2         | 1.35%   |
| 0x08600103 | 2         | 1.35%   |
| 0x08108109 | 2         | 1.35%   |
| 0x05000119 | 2         | 1.35%   |
| 0x906ed    | 1         | 0.68%   |
| 0x806eb    | 1         | 0.68%   |
| 0x706a8    | 1         | 0.68%   |
| 0x706a1    | 1         | 0.68%   |
| 0x6fb      | 1         | 0.68%   |
| 0x6fa      | 1         | 0.68%   |
| 0x6ec      | 1         | 0.68%   |
| 0x506c9    | 1         | 0.68%   |
| 0x30673    | 1         | 0.68%   |
| 0x106e5    | 1         | 0.68%   |
| 0x10661    | 1         | 0.68%   |
| 0x0a50000c | 1         | 0.68%   |
| 0x08600106 | 1         | 0.68%   |
| 0x07030106 | 1         | 0.68%   |
| 0x07030105 | 1         | 0.68%   |
| 0x0700010f | 1         | 0.68%   |
| 0x06006705 | 1         | 0.68%   |
| 0x06006704 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 23        | 15.75%  |
| Skylake       | 13        | 8.9%    |
| Core          | 12        | 8.22%   |
| SandyBridge   | 11        | 7.53%   |
| IvyBridge     | 11        | 7.53%   |
| Silvermont    | 9         | 6.16%   |
| Penryn        | 9         | 6.16%   |
| Haswell       | 8         | 5.48%   |
| Zen+          | 7         | 4.79%   |
| Westmere      | 7         | 4.79%   |
| Broadwell     | 6         | 4.11%   |
| Zen 2         | 5         | 3.42%   |
| TigerLake     | 5         | 3.42%   |
| Piledriver    | 3         | 2.05%   |
| Puma          | 2         | 1.37%   |
| Goldmont plus | 2         | 1.37%   |
| Excavator     | 2         | 1.37%   |
| CometLake     | 2         | 1.37%   |
| Bobcat        | 2         | 1.37%   |
| Zen 3         | 1         | 0.68%   |
| P6            | 1         | 0.68%   |
| Nehalem       | 1         | 0.68%   |
| K8 Hammer     | 1         | 0.68%   |
| Jaguar        | 1         | 0.68%   |
| Goldmont      | 1         | 0.68%   |
| Unknown       | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 102       | 56.35%  |
| Nvidia | 45        | 24.86%  |
| AMD    | 34        | 18.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 5.29%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 4.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 3.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 3.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.65%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.65%   |
| AMD Renoir                                                                               | 5         | 2.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 2.12%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.59%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.59%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.06%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 1.06%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 1.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.06%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.06%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.06%   |
| Intel HD Graphics 620                                                                    | 2         | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.06%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.06%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.06%   |
| AMD Richland [Radeon HD 8650G]                                                           | 2         | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.53%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.53%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 1         | 0.53%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.53%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.53%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.53%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.53%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.53%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 0.53%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.53%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.53%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.53%   |
| Nvidia GM107GLM [Quadro M600M]                                                           | 1         | 0.53%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.53%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.53%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.53%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 0.53%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.53%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.53%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.53%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.53%   |
| Nvidia GF108M [GeForce GT 435M]                                                          | 1         | 0.53%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.53%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.53%   |
| Nvidia G96CM [GeForce 9600M GS]                                                          | 1         | 0.53%   |
| Nvidia G86M [GeForce 9300M G]                                                            | 1         | 0.53%   |
| Nvidia G86M [GeForce 8400M G]                                                            | 1         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 69        | 47.26%  |
| Intel + Nvidia | 27        | 18.49%  |
| 1 x AMD        | 22        | 15.07%  |
| 1 x Nvidia     | 16        | 10.96%  |
| Intel + AMD    | 6         | 4.11%   |
| 2 x AMD        | 4         | 2.74%   |
| AMD + Nvidia   | 2         | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 123       | 80.39%  |
| Proprietary | 26        | 16.99%  |
| Unknown     | 4         | 2.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 46.75%  |
| 1.01-2.0   | 34        | 22.08%  |
| 0.01-0.5   | 23        | 14.94%  |
| 0.51-1.0   | 11        | 7.14%   |
| 3.01-4.0   | 9         | 5.84%   |
| 7.01-8.0   | 3         | 1.95%   |
| 5.01-6.0   | 2         | 1.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 40        | 24.1%   |
| LG Display              | 27        | 16.27%  |
| Samsung Electronics     | 26        | 15.66%  |
| BOE                     | 18        | 10.84%  |
| Chimei Innolux          | 14        | 8.43%   |
| Dell                    | 11        | 6.63%   |
| PANDA                   | 3         | 1.81%   |
| Lenovo                  | 3         | 1.81%   |
| BenQ                    | 3         | 1.81%   |
| Sony                    | 2         | 1.2%    |
| Seiko/Epson             | 2         | 1.2%    |
| Hitachi                 | 2         | 1.2%    |
| Goldstar                | 2         | 1.2%    |
| Chi Mei Optoelectronics | 2         | 1.2%    |
| TIANMA XM               | 1         | 0.6%    |
| Sharp                   | 1         | 0.6%    |
| Quanta Display          | 1         | 0.6%    |
| Philips                 | 1         | 0.6%    |
| Panasonic               | 1         | 0.6%    |
| LGD                     | 1         | 0.6%    |
| LG Philips              | 1         | 0.6%    |
| InfoVision              | 1         | 0.6%    |
| Apple                   | 1         | 0.6%    |
| ANX                     | 1         | 0.6%    |
| Acer                    | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 3         | 1.74%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 3         | 1.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.74%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 3         | 1.74%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 2         | 1.16%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 1.16%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 2         | 1.16%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 2         | 1.16%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 1.16%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                     | 2         | 1.16%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 2         | 1.16%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                  | 2         | 1.16%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch        | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.16%   |
| TIANMA XM LCD Monitor TLX1388 3000x2000 293x196mm 13.9-inch           | 1         | 0.58%   |
| Sony SDM-S75A/E SNY3400 1280x1024 338x270mm 17.0-inch                 | 1         | 0.58%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 0.58%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch               | 1         | 0.58%   |
| Seiko/Epson LCD Monitor 1366x768                                      | 1         | 0.58%   |
| Seiko/Epson LCD Monitor 1280x800                                      | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM0878 1920x1080 885x498mm 40.0-inch  | 1         | 0.58%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 600x340mm 27.2-inch     | 1         | 0.58%   |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch     | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC3256 1920x1080 382x215mm 17.3-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM07E8 1920x1080 950x540mm 43.0-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0200 1280x720                      | 1         | 0.58%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1         | 0.58%   |
| Quanta Display LCD Monitor QDS0027 1280x800 331x207mm 15.4-inch       | 1         | 0.58%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                  | 1         | 0.58%   |
| PANDA LCD Monitor NCP0057 1920x1080 344x194mm 15.5-inch               | 1         | 0.58%   |
| Panasonic LCD Monitor 7680x2160                                       | 1         | 0.58%   |
| LGD LCD Monitor 1920x1080                                             | 1         | 0.58%   |
| LG Philips LCD Monitor LPL00E0 1440x900 304x190mm 14.1-inch           | 1         | 0.58%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch         | 1         | 0.58%   |
| LG Display LCD Monitor LGDE400 1920x1200 367x230mm 17.1-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch           | 1         | 0.58%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch           | 1         | 0.58%   |
| LG Display LCD Monitor LGD06CA 1920x1080 309x174mm 14.0-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD05F6 1920x1080 309x174mm 14.0-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD053B 1920x1080 294x165mm 13.3-inch          | 1         | 0.58%   |
| LG Display LCD Monitor LGD04BD 1366x768 344x194mm 15.5-inch           | 1         | 0.58%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch           | 1         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 55        | 35.95%  |
| 1920x1080 (FHD)    | 53        | 34.64%  |
| 1600x900 (HD+)     | 12        | 7.84%   |
| 1280x800 (WXGA)    | 9         | 5.88%   |
| 3840x2160 (4K)     | 5         | 3.27%   |
| 2560x1440 (QHD)    | 4         | 2.61%   |
| 1440x900 (WXGA+)   | 3         | 1.96%   |
| 1920x1200 (WUXGA)  | 2         | 1.31%   |
| 1280x1024 (SXGA)   | 2         | 1.31%   |
| 800x1280           | 1         | 0.65%   |
| 7680x2160          | 1         | 0.65%   |
| 3456x2160          | 1         | 0.65%   |
| 3440x1440          | 1         | 0.65%   |
| 3000x2000          | 1         | 0.65%   |
| 1680x1050 (WSXGA+) | 1         | 0.65%   |
| 1280x720 (HD)      | 1         | 0.65%   |
| Unknown            | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 83        | 49.4%   |
| 17      | 14        | 8.33%   |
| 14      | 14        | 8.33%   |
| 13      | 14        | 8.33%   |
| 12      | 10        | 5.95%   |
| 24      | 9         | 5.36%   |
| 27      | 5         | 2.98%   |
| Unknown | 5         | 2.98%   |
| 11      | 3         | 1.79%   |
| 40      | 2         | 1.19%   |
| 84      | 1         | 0.6%    |
| 43      | 1         | 0.6%    |
| 35      | 1         | 0.6%    |
| 31      | 1         | 0.6%    |
| 26      | 1         | 0.6%    |
| 23      | 1         | 0.6%    |
| 21      | 1         | 0.6%    |
| 19      | 1         | 0.6%    |
| 18      | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 103       | 62.05%  |
| 351-400     | 18        | 10.84%  |
| 201-300     | 17        | 10.24%  |
| 501-600     | 15        | 9.04%   |
| Unknown     | 5         | 3.01%   |
| 801-900     | 3         | 1.81%   |
| 401-500     | 2         | 1.2%    |
| 601-700     | 1         | 0.6%    |
| 1501-2000   | 1         | 0.6%    |
| 901-1000    | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 123       | 83.11%  |
| 16/10   | 15        | 10.14%  |
| Unknown | 4         | 2.7%    |
| 5/4     | 2         | 1.35%   |
| 3/2     | 2         | 1.35%   |
| 21/9    | 1         | 0.68%   |
| 0.62    | 1         | 0.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 81        | 48.5%   |
| 81-90          | 26        | 15.57%  |
| 61-70          | 10        | 5.99%   |
| 201-250        | 10        | 5.99%   |
| 121-130        | 10        | 5.99%   |
| 301-350        | 5         | 2.99%   |
| Unknown        | 5         | 2.99%   |
| 51-60          | 3         | 1.8%    |
| 131-140        | 3         | 1.8%    |
| 501-1000       | 3         | 1.8%    |
| 71-80          | 2         | 1.2%    |
| 351-500        | 2         | 1.2%    |
| 151-200        | 2         | 1.2%    |
| 91-100         | 2         | 1.2%    |
| More than 1000 | 1         | 0.6%    |
| 251-300        | 1         | 0.6%    |
| 141-150        | 1         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 65        | 39.16%  |
| 101-120       | 60        | 36.14%  |
| 51-100        | 27        | 16.27%  |
| Unknown       | 5         | 3.01%   |
| 161-240       | 4         | 2.41%   |
| More than 240 | 3         | 1.81%   |
| 1-50          | 2         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 119       | 80.41%  |
| 2     | 23        | 15.54%  |
| 3     | 3         | 2.03%   |
| 0     | 3         | 2.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 81        | 34.62%  |
| Intel                    | 77        | 32.91%  |
| Qualcomm Atheros         | 34        | 14.53%  |
| Broadcom                 | 17        | 7.26%   |
| Broadcom Limited         | 7         | 2.99%   |
| Marvell Technology Group | 3         | 1.28%   |
| TP-Link                  | 2         | 0.85%   |
| Ralink                   | 2         | 0.85%   |
| MEDIATEK                 | 2         | 0.85%   |
| Hewlett-Packard          | 2         | 0.85%   |
| Xiaomi                   | 1         | 0.43%   |
| U-Blox                   | 1         | 0.43%   |
| Samsung Electronics      | 1         | 0.43%   |
| Ralink Technology        | 1         | 0.43%   |
| Nvidia                   | 1         | 0.43%   |
| Lenovo                   | 1         | 0.43%   |
| Huawei Technologies      | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 17.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 7.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 3.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 2.08%   |
| Intel Wireless 3160                                               | 6         | 2.08%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.73%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.73%   |
| Intel Wireless 8260                                               | 5         | 1.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 5         | 1.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.38%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.38%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 4         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.38%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.04%   |
| Intel Wireless 7260                                               | 3         | 1.04%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 1.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.69%   |
| Intel Wireless-AC 9260                                            | 2         | 0.69%   |
| Intel Wireless 7265                                               | 2         | 0.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 0.69%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.69%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.69%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.69%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.69%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.69%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 0.69%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.35%   |
| U-Blox [u-blox 7]                                                 | 1         | 0.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.35%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.35%   |
| Realtek RTL8187SE Wireless LAN Controller                         | 1         | 0.35%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 1         | 0.35%   |
| Ralink RT2070 Wireless Adapter                                    | 1         | 0.35%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.35%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 76        | 51.35%  |
| Qualcomm Atheros      | 29        | 19.59%  |
| Realtek Semiconductor | 20        | 13.51%  |
| Broadcom              | 14        | 9.46%   |
| Broadcom Limited      | 3         | 2.03%   |
| TP-Link               | 2         | 1.35%   |
| Ralink                | 2         | 1.35%   |
| Ralink Technology     | 1         | 0.68%   |
| MEDIATEK              | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 5.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 4.05%   |
| Intel Wireless 3160                                                     | 6         | 4.05%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 4.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 4.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 3.38%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.38%   |
| Intel Wireless 8260                                                     | 5         | 3.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 3.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.7%    |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 2.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 2.7%    |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.03%   |
| Intel Wireless 7260                                                     | 3         | 2.03%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.35%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.35%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.35%   |
| Intel Wireless 7265                                                     | 2         | 1.35%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.35%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.35%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.35%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 1.35%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.68%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.68%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.68%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.68%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.68%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.68%   |
| Intel WiFi Link 5100                                                    | 1         | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.68%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.68%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.68%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 0.68%   |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 1         | 0.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 0.68%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.68%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 0.68%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.68%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 77        | 55.4%   |
| Intel                    | 30        | 21.58%  |
| Qualcomm Atheros         | 11        | 7.91%   |
| Broadcom                 | 7         | 5.04%   |
| Broadcom Limited         | 4         | 2.88%   |
| Marvell Technology Group | 3         | 2.16%   |
| Xiaomi                   | 1         | 0.72%   |
| Samsung Electronics      | 1         | 0.72%   |
| Nvidia                   | 1         | 0.72%   |
| MediaTek                 | 1         | 0.72%   |
| Lenovo                   | 1         | 0.72%   |
| Huawei Technologies      | 1         | 0.72%   |
| Hewlett-Packard          | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 37.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 15.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 6.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.16%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.44%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.44%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.44%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.44%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.44%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.44%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 1.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.72%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.72%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.72%   |
| MediaTek WP7                                                      | 1         | 0.72%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.72%   |
| Lenovo Thinkpad USB LAN                                           | 1         | 0.72%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.72%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.72%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.72%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.72%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.72%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.72%   |
| Huawei JNY-LX1                                                    | 1         | 0.72%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.72%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.72%   |
| Broadcom NetXtreme BCM5756ME Gigabit Ethernet PCI Express         | 1         | 0.72%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.72%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.72%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.72%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 0.72%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 144       | 51.43%  |
| Ethernet | 134       | 47.86%  |
| Modem    | 2         | 0.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 127       | 67.55%  |
| Ethernet | 61        | 32.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 126       | 86.3%   |
| 1     | 17        | 11.64%  |
| 3     | 2         | 1.37%   |
| 0     | 1         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 141       | 96.58%  |
| Yes  | 5         | 3.42%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 40.35%  |
| Realtek Semiconductor           | 13        | 11.4%   |
| IMC Networks                    | 10        | 8.77%   |
| Broadcom                        | 10        | 8.77%   |
| Qualcomm Atheros Communications | 9         | 7.89%   |
| Lite-On Technology              | 8         | 7.02%   |
| Dell                            | 5         | 4.39%   |
| Toshiba                         | 3         | 2.63%   |
| Hewlett-Packard                 | 3         | 2.63%   |
| Cambridge Silicon Radio         | 2         | 1.75%   |
| Ralink                          | 1         | 0.88%   |
| Qcom                            | 1         | 0.88%   |
| Foxconn / Hon Hai               | 1         | 0.88%   |
| ASUSTek Computer                | 1         | 0.88%   |
| Apple                           | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 20        | 17.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 7.89%   |
| Realtek Bluetooth Radio                                                             | 6         | 5.26%   |
| Intel AX200 Bluetooth                                                               | 6         | 5.26%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 4.39%   |
| Intel AX201 Bluetooth                                                               | 5         | 4.39%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 3.51%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.75%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 1.75%   |
| Realtek 802.11n WLAN Adapter                                                        | 2         | 1.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.75%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 1.75%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.75%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.75%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.75%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 1.75%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.75%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 1.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.75%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.75%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 1.75%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.88%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.88%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.88%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.88%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.88%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.88%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.88%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.88%   |
| Intel Bluetooth Device                                                              | 1         | 0.88%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.88%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.88%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.88%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.88%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.88%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.88%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.88%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.88%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.88%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.88%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.88%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.88%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 120       | 66.67%  |
| AMD                   | 27        | 15%     |
| Nvidia                | 22        | 12.22%  |
| C-Media Electronics   | 3         | 1.67%   |
| Logitech              | 2         | 1.11%   |
| Realtek Semiconductor | 1         | 0.56%   |
| Microsoft             | 1         | 0.56%   |
| GYROCOM C&C           | 1         | 0.56%   |
| GN Netcom             | 1         | 0.56%   |
| Creative Technology   | 1         | 0.56%   |
| Apple                 | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 8.37%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 6.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 5.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 4.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 3.72%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.72%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 3.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 3.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.79%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.33%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.86%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.4%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.4%    |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.4%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.4%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.93%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.93%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.93%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.93%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.93%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.93%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1         | 0.47%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.47%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.47%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.47%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.47%   |
| Microsoft Azure Kinect Microphone Array                                                           | 1         | 0.47%   |
| Logitech QuickCam for DELL Notebooks                                                              | 1         | 0.47%   |
| Logitech G430 Surround Sound Gaming Headset                                                       | 1         | 0.47%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.47%   |
| GYROCOM C&C Fiio E10                                                                              | 1         | 0.47%   |
| GN Netcom Jabra Link 380                                                                          | 1         | 0.47%   |
| Creative Technology USB Speaker                                                                   | 1         | 0.47%   |
| C-Media Electronics Redragon Gaming Headset                                                       | 1         | 0.47%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.47%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.47%   |
| Apple USB-C to 3.5mm Headphone Jack Adapter                                                       | 1         | 0.47%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.47%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 0.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.47%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 27.35%  |
| SK Hynix            | 29        | 24.79%  |
| Kingston            | 18        | 15.38%  |
| Unknown             | 15        | 12.82%  |
| Micron Technology   | 11        | 9.4%    |
| Elpida              | 3         | 2.56%   |
| Ramaxel Technology  | 2         | 1.71%   |
| Crucial             | 2         | 1.71%   |
| Corsair             | 2         | 1.71%   |
| Toshiba             | 1         | 0.85%   |
| GOODRAM             | 1         | 0.85%   |
| G.Skill             | 1         | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 4         | 3.25%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 3         | 2.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 3         | 2.44%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s                     | 3         | 2.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 3         | 2.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                        | 3         | 2.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                               | 2         | 1.63%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                                | 2         | 1.63%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s                       | 2         | 1.63%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                       | 2         | 1.63%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s                     | 2         | 1.63%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s                     | 2         | 1.63%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s                     | 2         | 1.63%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s                        | 2         | 1.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                        | 2         | 1.63%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s                      | 2         | 1.63%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                                  | 1         | 0.81%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                                  | 1         | 0.81%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                                   | 1         | 0.81%   |
| Unknown RAM Module 4096MB SODIMM DDR2 800MT/s                                | 1         | 0.81%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                                | 1         | 0.81%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                                | 1         | 0.81%   |
| Unknown RAM Module 2GB SODIMM DRAM                                           | 1         | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR3                                           | 1         | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR2 200MT/s                                   | 1         | 0.81%   |
| Unknown RAM Module 2048MB SODIMM DDR                                         | 1         | 0.81%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                                     | 1         | 0.81%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s                               | 1         | 0.81%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s                           | 1         | 0.81%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s                            | 1         | 0.81%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                              | 1         | 0.81%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                              | 1         | 0.81%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                                | 1         | 0.81%   |
| SK Hynix RAM HYMP564S64CP6-Y5 512MB SODIMM DDR 667MT/s                       | 1         | 0.81%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                         | 1         | 0.81%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.81%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s                    | 1         | 0.81%   |
| SK Hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s                       | 1         | 0.81%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 1         | 0.81%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                       | 1         | 0.81%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s                       | 1         | 0.81%   |
| SK Hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s                       | 1         | 0.81%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s                       | 1         | 0.81%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s                       | 1         | 0.81%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.81%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                       | 1         | 0.81%   |
| SK Hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s               | 1         | 0.81%   |
| SK Hynix RAM 252525252525252525252525252525252525 2048MB SODIMM DDR2 667MT/s | 1         | 0.81%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                               | 1         | 0.81%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2133MT/s                              | 1         | 0.81%   |
| Samsung RAM M474A1G43EB1-CRC 8192MB SODIMM DDR4 2400MT/s                     | 1         | 0.81%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                        | 1         | 0.81%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                        | 1         | 0.81%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s                        | 1         | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                        | 1         | 0.81%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s                        | 1         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                        | 1         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s                  | 1         | 0.81%   |
| Samsung RAM M4 70T5663QZ3-CE6 2048MB SODIMM DDR2 667MT/s                     | 1         | 0.81%   |
| Samsung RAM DEDEDEDEDEDEDEDEDEDEDEDEDEDEDEDEDEDE 1024MB SODIMM DDR2 667MT/s  | 1         | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 41        | 43.16%  |
| DDR4    | 37        | 38.95%  |
| DDR2    | 10        | 10.53%  |
| LPDDR4  | 3         | 3.16%   |
| SDRAM   | 1         | 1.05%   |
| DRAM    | 1         | 1.05%   |
| DDR     | 1         | 1.05%   |
| Unknown | 1         | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 91        | 96.81%  |
| Row Of Chips | 3         | 3.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 41        | 39.42%  |
| 8192  | 33        | 31.73%  |
| 2048  | 19        | 18.27%  |
| 16384 | 7         | 6.73%   |
| 1024  | 2         | 1.92%   |
| 32768 | 1         | 0.96%   |
| 512   | 1         | 0.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 27        | 25.71%  |
| 2667    | 21        | 20%     |
| 1334    | 9         | 8.57%   |
| 3200    | 7         | 6.67%   |
| 1333    | 7         | 6.67%   |
| 2400    | 6         | 5.71%   |
| 2133    | 6         | 5.71%   |
| 667     | 6         | 5.71%   |
| Unknown | 3         | 2.86%   |
| 4267    | 2         | 1.9%    |
| 1067    | 2         | 1.9%    |
| 1066    | 2         | 1.9%    |
| 800     | 2         | 1.9%    |
| 4199    | 1         | 0.95%   |
| 3266    | 1         | 0.95%   |
| 1867    | 1         | 0.95%   |
| 975     | 1         | 0.95%   |
| 200     | 1         | 0.95%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Samsung SCX-4100 Scanner | 1         | 50%     |
| Samsung SCX-3200 Series  | 1         | 50%     |

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
| Chicony Electronics                    | 34        | 26.98%  |
| IMC Networks                           | 17        | 13.49%  |
| Realtek Semiconductor                  | 13        | 10.32%  |
| Microdia                               | 8         | 6.35%   |
| Sunplus Innovation Technology          | 7         | 5.56%   |
| Suyin                                  | 6         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.76%   |
| Acer                                   | 6         | 4.76%   |
| Syntek                                 | 5         | 3.97%   |
| Quanta                                 | 5         | 3.97%   |
| Lite-On Technology                     | 4         | 3.17%   |
| Silicon Motion                         | 3         | 2.38%   |
| Ricoh                                  | 2         | 1.59%   |
| Luxvisions Innotech Limited            | 2         | 1.59%   |
| Samsung Electronics                    | 1         | 0.79%   |
| Primax Electronics                     | 1         | 0.79%   |
| OmniVision Technologies                | 1         | 0.79%   |
| Microsoft                              | 1         | 0.79%   |
| Lenovo                                 | 1         | 0.79%   |
| Genesys Logic                          | 1         | 0.79%   |
| DigiTech                               | 1         | 0.79%   |
| 8SSC20F27114V1GZ07N14V2                | 1         | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 6         | 4.69%   |
| Realtek Integrated_Webcam_HD                        | 5         | 3.91%   |
| Chicony integrated camera                           | 4         | 3.13%   |
| Chicony HD WebCam                                   | 4         | 3.13%   |
| Lite-On Integrated Camera                           | 3         | 2.34%   |
| IMC Networks Integrated Camera                      | 3         | 2.34%   |
| Chicony HP HD Camera                                | 3         | 2.34%   |
| Chicony HD User Facing                              | 3         | 2.34%   |
| Acer Lenovo EasyCamera                              | 3         | 2.34%   |
| Suyin HD WebCam                                     | 2         | 1.56%   |
| Sunplus ASUS USB2.0 Webcam                          | 2         | 1.56%   |
| Realtek USB Camera                                  | 2         | 1.56%   |
| Realtek Integrated Webcam                           | 2         | 1.56%   |
| Realtek HP Webcam                                   | 2         | 1.56%   |
| Microdia Integrated Webcam                          | 2         | 1.56%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.56%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 2         | 1.56%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.56%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 1.56%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 1.56%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 1.56%   |
| Chicony CNF9055 Toshiba Webcam                      | 2         | 1.56%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.56%   |
| Acer Integrated Camera                              | 2         | 1.56%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                | 1         | 0.78%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera               | 1         | 0.78%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.78%   |
| Syntek Integrated Camera                            | 1         | 0.78%   |
| Syntek EasyCamera                                   | 1         | 0.78%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.78%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 0.78%   |
| Suyin Acer HD Crystal Eye webcam                    | 1         | 0.78%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.78%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.78%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 0.78%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.78%   |
| Sunplus HD WebCam                                   | 1         | 0.78%   |
| Sunplus ASUS Webcam                                 | 1         | 0.78%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.78%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.78%   |
| Silicon Motion HP Webcam-101                        | 1         | 0.78%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.78%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 0.78%   |
| Ricoh Integrated Webcam                             | 1         | 0.78%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 0.78%   |
| Realtek HD WebCam                                   | 1         | 0.78%   |
| Quanta USB Webcam                                   | 1         | 0.78%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 1         | 0.78%   |
| Quanta Integrated_Webcam_2M                         | 1         | 0.78%   |
| Quanta HP Webcam                                    | 1         | 0.78%   |
| Quanta HD Webcam                                    | 1         | 0.78%   |
| Primax HP HD Webcam [Fixed]                         | 1         | 0.78%   |
| OmniVision OV2640 Webcam                            | 1         | 0.78%   |
| Microsoft Azure Kinect Depth Camera                 | 1         | 0.78%   |
| Microsoft Azure Kinect 4K Camera                    | 1         | 0.78%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 0.78%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.78%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 1         | 0.78%   |
| Microdia Laptop_Integrated_Webcam_1.3M              | 1         | 0.78%   |
| Microdia Integrated_Webcam_HD                       | 1         | 0.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 46.88%  |
| Synaptics                  | 6         | 18.75%  |
| AuthenTec                  | 3         | 9.38%   |
| Upek                       | 2         | 6.25%   |
| STMicroelectronics         | 2         | 6.25%   |
| Elan Microelectronics      | 2         | 6.25%   |
| Shenzhen Goodix Technology | 1         | 3.13%   |
| LighTuning Technology      | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 9.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 9.38%   |
| Validity Sensors VFS491                                                    | 2         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 6.25%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.25%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 6.25%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 3.13%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.13%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.13%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 3.13%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 3.13%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 3.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.13%   |
| AuthenTec AES1600                                                          | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 9         | 52.94%  |
| Broadcom    | 4         | 23.53%  |
| Lenovo      | 2         | 11.76%  |
| Upek        | 1         | 5.88%   |
| O2 Micro    | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 9         | 52.94%  |
| Broadcom 58200                                             | 3         | 17.65%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 11.76%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 5.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 5.88%   |
| Broadcom 5880                                              | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 96        | 62.75%  |
| 1     | 39        | 25.49%  |
| 2     | 17        | 11.11%  |
| 3     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 32        | 45.07%  |
| Chipcard              | 14        | 19.72%  |
| Graphics card         | 13        | 18.31%  |
| Net/wireless          | 6         | 8.45%   |
| Multimedia controller | 2         | 2.82%   |
| Camera                | 2         | 2.82%   |
| Card reader           | 1         | 1.41%   |
| Bluetooth             | 1         | 1.41%   |
