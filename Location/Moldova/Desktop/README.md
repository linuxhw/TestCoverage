Linux in Moldova - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Moldova.

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

Total: 84

| Vendor   | Model               | Probe                                                      | Date         |
|----------|---------------------|------------------------------------------------------------|--------------|
| Gigabyte | B450M S2H V2        | [e0e21604de](https://linux-hardware.org/?probe=e0e21604de) | Jun 24, 2022 |
| ASUSTek  | PRIME A520M-K       | [72dd09a86a](https://linux-hardware.org/?probe=72dd09a86a) | Jun 05, 2022 |
| ASUSTek  | M4A785-M            | [25526ee77d](https://linux-hardware.org/?probe=25526ee77d) | Apr 17, 2022 |
| ASUSTek  | PRIME B550-PLUS     | [8c88f1c50a](https://linux-hardware.org/?probe=8c88f1c50a) | Apr 12, 2022 |
| Gigabyte | Z690 UD DDR4        | [6c4ff21b02](https://linux-hardware.org/?probe=6c4ff21b02) | Feb 21, 2022 |
| HP       | 21F5                | [ce8e06508d](https://linux-hardware.org/?probe=ce8e06508d) | Jan 16, 2022 |
| Biostar  | N68S3+              | [8812de783f](https://linux-hardware.org/?probe=8812de783f) | Dec 16, 2021 |
| ASUSTek  | A_F_K20CE           | [926db6c655](https://linux-hardware.org/?probe=926db6c655) | Dec 15, 2021 |
| ASUSTek  | Z97I-PLUS           | [a379cfa431](https://linux-hardware.org/?probe=a379cfa431) | Dec 12, 2021 |
| Gigabyte | H61M-S2-B3          | [960d7d5035](https://linux-hardware.org/?probe=960d7d5035) | Dec 05, 2021 |
| ASRock   | M3A770DE            | [b6ee8bc974](https://linux-hardware.org/?probe=b6ee8bc974) | Dec 01, 2021 |
| Gigabyte | H81M-HD3            | [953c3f9284](https://linux-hardware.org/?probe=953c3f9284) | Nov 13, 2021 |
| MSI      | MS-7309             | [0a4d7fb95d](https://linux-hardware.org/?probe=0a4d7fb95d) | Oct 30, 2021 |
| MSI      | A75A-G35            | [7223bfa184](https://linux-hardware.org/?probe=7223bfa184) | Oct 22, 2021 |
| Biostar  | N68S3+              | [1eae78eec0](https://linux-hardware.org/?probe=1eae78eec0) | Aug 04, 2021 |
| Gigabyte | B460M DS3H V2       | [6177f24834](https://linux-hardware.org/?probe=6177f24834) | Aug 02, 2021 |
| Gigabyte | B460M DS3H V2       | [7fa66f2f95](https://linux-hardware.org/?probe=7fa66f2f95) | Aug 02, 2021 |
| Gigabyte | EP43-UD3L           | [3b6839e225](https://linux-hardware.org/?probe=3b6839e225) | Jul 01, 2021 |
| ASUSTek  | F1A75-M LE          | [b453e98364](https://linux-hardware.org/?probe=b453e98364) | May 21, 2021 |
| Biostar  | A58MD               | [3effc9a4ed](https://linux-hardware.org/?probe=3effc9a4ed) | Apr 18, 2021 |
| Biostar  | H110MHC             | [acc13c8156](https://linux-hardware.org/?probe=acc13c8156) | Mar 24, 2021 |
| ASUSTek  | P8Z77-V PRO         | [a3d54dee1b](https://linux-hardware.org/?probe=a3d54dee1b) | Feb 22, 2021 |
| ASUSTek  | P8Z77-V PRO         | [7f75cd3e14](https://linux-hardware.org/?probe=7f75cd3e14) | Feb 22, 2021 |
| ASUSTek  | PRIME B350-PLUS     | [23ddb098d4](https://linux-hardware.org/?probe=23ddb098d4) | Feb 18, 2021 |
| ASRock   | Z87 Extreme4        | [2fc1d961c0](https://linux-hardware.org/?probe=2fc1d961c0) | Feb 14, 2021 |
| ASUSTek  | B85M-E              | [024b12b22d](https://linux-hardware.org/?probe=024b12b22d) | Jan 17, 2021 |
| Gigabyte | GA-970A-DS3         | [f333aed432](https://linux-hardware.org/?probe=f333aed432) | Dec 04, 2020 |
| Gigabyte | X570 AORUS ULTRA    | [bdc9ccf5d5](https://linux-hardware.org/?probe=bdc9ccf5d5) | Nov 23, 2020 |
| Biostar  | A960D+V3            | [86864a3f9a](https://linux-hardware.org/?probe=86864a3f9a) | Oct 01, 2020 |
| Biostar  | A960D+V3            | [781ac4ebab](https://linux-hardware.org/?probe=781ac4ebab) | Sep 30, 2020 |
| Gigabyte | P41-ES3G            | [30feb0323e](https://linux-hardware.org/?probe=30feb0323e) | Sep 29, 2020 |
| Gigabyte | P41-ES3G            | [395e492e72](https://linux-hardware.org/?probe=395e492e72) | Sep 29, 2020 |
| ASUSTek  | P8H61-MX            | [46cff277d4](https://linux-hardware.org/?probe=46cff277d4) | Aug 16, 2020 |
| ASUSTek  | M2N-SLI DELUXE      | [02ab999339](https://linux-hardware.org/?probe=02ab999339) | Aug 04, 2020 |
| ASRock   | A320M-HDV R4.0      | [0320a45205](https://linux-hardware.org/?probe=0320a45205) | Jul 25, 2020 |
| ASUSTek  | M4A785TD-V EVO      | [734d413d2f](https://linux-hardware.org/?probe=734d413d2f) | May 25, 2020 |
| ASUSTek  | M4A785TD-V EVO      | [a5f24237a6](https://linux-hardware.org/?probe=a5f24237a6) | May 22, 2020 |
| ASUSTek  | P8B75-M LE          | [3051982d33](https://linux-hardware.org/?probe=3051982d33) | Apr 28, 2020 |
| ASUSTek  | P8B75-M LE          | [6e3a1017c8](https://linux-hardware.org/?probe=6e3a1017c8) | Apr 28, 2020 |
| ASUSTek  | H110M-K             | [d65e7d1bb6](https://linux-hardware.org/?probe=d65e7d1bb6) | Mar 28, 2020 |
| ASUSTek  | F1A75-M LE          | [3cee091303](https://linux-hardware.org/?probe=3cee091303) | Mar 25, 2020 |
| ASUSTek  | H110M-K             | [c0aa963f37](https://linux-hardware.org/?probe=c0aa963f37) | Mar 21, 2020 |
| MSI      | 2A9C                | [cb1789ae00](https://linux-hardware.org/?probe=cb1789ae00) | Mar 18, 2020 |
| ASUSTek  | M5A78L-M LX         | [90f55c011b](https://linux-hardware.org/?probe=90f55c011b) | Dec 04, 2019 |
| ASUSTek  | P5QL/EPU            | [8f31c009af](https://linux-hardware.org/?probe=8f31c009af) | Oct 20, 2019 |
| ASUSTek  | F1A75-M LE          | [bdb727808f](https://linux-hardware.org/?probe=bdb727808f) | Jul 26, 2019 |
| ASUSTek  | F1A75-M LE          | [961de73328](https://linux-hardware.org/?probe=961de73328) | Jul 26, 2019 |
| Biostar  | GF8100 M2+ SE       | [52b394c153](https://linux-hardware.org/?probe=52b394c153) | May 05, 2019 |
| ASUSTek  | P5P43TD             | [bbfc5c83ed](https://linux-hardware.org/?probe=bbfc5c83ed) | Apr 23, 2019 |
| ASUSTek  | P5P43TD             | [a1df618ae9](https://linux-hardware.org/?probe=a1df618ae9) | Apr 18, 2019 |
| Gigabyte | G41M-ES2L           | [62f911ea35](https://linux-hardware.org/?probe=62f911ea35) | Apr 09, 2019 |
| HP       | 82A1                | [f04f3b1720](https://linux-hardware.org/?probe=f04f3b1720) | Mar 18, 2019 |
| ASRock   | B250M Pro4          | [05dfa7d080](https://linux-hardware.org/?probe=05dfa7d080) | Jan 07, 2019 |
| ASRock   | B250M Pro4          | [4ca432ffe1](https://linux-hardware.org/?probe=4ca432ffe1) | Jan 03, 2019 |
| Biostar  | NF61D-A2            | [8920fb5da2](https://linux-hardware.org/?probe=8920fb5da2) | Nov 24, 2018 |
| Gigabyte | H61M-S1             | [f035a927b4](https://linux-hardware.org/?probe=f035a927b4) | Oct 16, 2018 |
| Gigabyte | H61M-S1             | [0cb176039a](https://linux-hardware.org/?probe=0cb176039a) | Oct 16, 2018 |
| ASUSTek  | H110M-R             | [e8cf4914df](https://linux-hardware.org/?probe=e8cf4914df) | Oct 11, 2018 |
| ASUSTek  | TUF X299 MARK 1     | [4ff6f8b306](https://linux-hardware.org/?probe=4ff6f8b306) | Aug 28, 2018 |
| ASUSTek  | H110M-R             | [856815508e](https://linux-hardware.org/?probe=856815508e) | Jul 20, 2018 |
| ASUSTek  | H110M-R             | [2c6e982e0a](https://linux-hardware.org/?probe=2c6e982e0a) | Jul 20, 2018 |
| ASRock   | H110M-DGS           | [2bf308c36a](https://linux-hardware.org/?probe=2bf308c36a) | Apr 22, 2018 |
| Gigabyte | H81M-S2PV           | [d73e7cdaf7](https://linux-hardware.org/?probe=d73e7cdaf7) | Apr 10, 2018 |
| ASUSTek  | M5A78L LE           | [324ea287af](https://linux-hardware.org/?probe=324ea287af) | Mar 25, 2018 |
| ASUSTek  | M5A78L LE           | [c4796ca0ba](https://linux-hardware.org/?probe=c4796ca0ba) | Mar 25, 2018 |
| MSI      | G31M3-L V2          | [a010b34c1d](https://linux-hardware.org/?probe=a010b34c1d) | Mar 14, 2018 |
| Gigabyte | GA-880GM-USB3       | [488c7af7b3](https://linux-hardware.org/?probe=488c7af7b3) | Feb 13, 2018 |
| Biostar  | H61MGV3             | [601f3981af](https://linux-hardware.org/?probe=601f3981af) | Jan 25, 2018 |
| MSI      | G31M3-L V2          | [cb825d670e](https://linux-hardware.org/?probe=cb825d670e) | Jan 23, 2018 |
| Biostar  | A960G+              | [1ed969e51e](https://linux-hardware.org/?probe=1ed969e51e) | Jan 02, 2018 |
| Gigabyte | H81M-S2PV           | [b4b5168bf0](https://linux-hardware.org/?probe=b4b5168bf0) | Oct 22, 2017 |
| Biostar  | TA790GX 128M        | [13dafc619e](https://linux-hardware.org/?probe=13dafc619e) | Sep 07, 2017 |
| ASUSTek  | P7P55D-E            | [7ead295d4f](https://linux-hardware.org/?probe=7ead295d4f) | May 04, 2017 |
| ASUSTek  | P5GPL               | [dc412a96d7](https://linux-hardware.org/?probe=dc412a96d7) | Mar 11, 2017 |
| ASUSTek  | P5GPL               | [704d76d7f0](https://linux-hardware.org/?probe=704d76d7f0) | Mar 11, 2017 |
| ECS      | GeForce7050M-M      | [dffec0e1ef](https://linux-hardware.org/?probe=dffec0e1ef) | Jan 26, 2017 |
| MSI      | G41M-P26            | [3a93859874](https://linux-hardware.org/?probe=3a93859874) | Jan 21, 2017 |
| Dell     | 0HJ054              | [3a64a2e7cc](https://linux-hardware.org/?probe=3a64a2e7cc) | Jan 14, 2017 |
| ASUSTek  | M5A78L-M LX3        | [de5986b48c](https://linux-hardware.org/?probe=de5986b48c) | Dec 27, 2016 |
| ASUSTek  | P8H61-M LX3         | [51108b9a7b](https://linux-hardware.org/?probe=51108b9a7b) | Nov 26, 2016 |
| ASUSTek  | A88X-PLUS           | [e5165dfe31](https://linux-hardware.org/?probe=e5165dfe31) | Nov 25, 2016 |
| ASUSTek  | A88X-PLUS           | [53f70342b5](https://linux-hardware.org/?probe=53f70342b5) | Nov 23, 2016 |
| ASUSTek  | P5KPL-AM IN/ROEM/SI | [c140d93dd9](https://linux-hardware.org/?probe=c140d93dd9) | Nov 08, 2016 |
| ECS      | GeForce7050M-M      | [3f276c748c](https://linux-hardware.org/?probe=3f276c748c) | Nov 04, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| ROSA R10         | 12       | 18.46%  |
| ROSA R11         | 8        | 12.31%  |
| ROSA R8          | 7        | 10.77%  |
| ROSA R8.1        | 6        | 9.23%   |
| OpenMandriva 4.2 | 6        | 9.23%   |
| ROSA R11.1       | 5        | 7.69%   |
| Ubuntu 18.04     | 2        | 3.08%   |
| Manjaro          | 2        | 3.08%   |
| Arch Rolling     | 2        | 3.08%   |
| Ubuntu 21.10     | 1        | 1.54%   |
| Ubuntu 20.04     | 1        | 1.54%   |
| Ubuntu 16.04     | 1        | 1.54%   |
| ROSA R9          | 1        | 1.54%   |
| ROSA 12.2        | 1        | 1.54%   |
| Pop!_OS 21.10    | 1        | 1.54%   |
| Pop!_OS 20.10    | 1        | 1.54%   |
| Pop!_OS 20.04    | 1        | 1.54%   |
| Manjaro 21.3.0   | 1        | 1.54%   |
| Linux Mint 20    | 1        | 1.54%   |
| Linux Mint 19.3  | 1        | 1.54%   |
| KDE neon 20.04   | 1        | 1.54%   |
| Kali 2019.3      | 1        | 1.54%   |
| Fedora 35        | 1        | 1.54%   |
| Ctlos 1.4.0      | 1        | 1.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| ROSA         | 38       | 60.32%  |
| OpenMandriva | 6        | 9.52%   |
| Ubuntu       | 5        | 7.94%   |
| Pop!_OS      | 3        | 4.76%   |
| Manjaro      | 3        | 4.76%   |
| Linux Mint   | 2        | 3.17%   |
| Arch         | 2        | 3.17%   |
| KDE neon     | 1        | 1.59%   |
| Kali         | 1        | 1.59%   |
| Fedora       | 1        | 1.59%   |
| Ctlos        | 1        | 1.59%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002            | 6        | 9.09%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 6        | 9.09%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 4        | 6.06%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 4        | 6.06%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 2        | 3.03%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 2        | 3.03%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 2        | 3.03%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 2        | 3.03%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 2        | 3.03%   |
| 5.9.3-050903-generic                | 1        | 1.52%   |
| 5.8.0-7642-generic                  | 1        | 1.52%   |
| 5.8.0-38-generic                    | 1        | 1.52%   |
| 5.5.9-zen1-2-zen                    | 1        | 1.52%   |
| 5.4.83-generic-2rosa-x86_64         | 1        | 1.52%   |
| 5.4.32-generic-2rosa-x86_64         | 1        | 1.52%   |
| 5.4.0-90-generic                    | 1        | 1.52%   |
| 5.4.0-7634-generic                  | 1        | 1.52%   |
| 5.4.0-56-generic                    | 1        | 1.52%   |
| 5.4.0-48-generic                    | 1        | 1.52%   |
| 5.2.0-kali2-amd64                   | 1        | 1.52%   |
| 5.17.9-arch1-1                      | 1        | 1.52%   |
| 5.16.9-200.fc35.x86_64              | 1        | 1.52%   |
| 5.15.48-1-MANJARO                   | 1        | 1.52%   |
| 5.15.11-76051511-generic            | 1        | 1.52%   |
| 5.14.14-arch1-1                     | 1        | 1.52%   |
| 5.13.0-39-generic                   | 1        | 1.52%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 1        | 1.52%   |
| 5.10.53-1-MANJARO                   | 1        | 1.52%   |
| 5.10.26-1-MANJARO                   | 1        | 1.52%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 1        | 1.52%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 1        | 1.52%   |
| 4.9.87-nrj-desktop-2rosa-x86_64     | 1        | 1.52%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 1        | 1.52%   |
| 4.9.76-nrj-desktop-1rosa-i586       | 1        | 1.52%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 1        | 1.52%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 1        | 1.52%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 1        | 1.52%   |
| 4.18.0-17-generic                   | 1        | 1.52%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 1        | 1.52%   |
| 4.15.0-desktop-54.1rosa-x86_64      | 1        | 1.52%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 1        | 1.52%   |
| 4.10.0-041000-generic               | 1        | 1.52%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 1        | 1.52%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 1        | 1.52%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 1        | 1.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.15.0  | 10       | 15.38%  |
| 4.9.60  | 7        | 10.77%  |
| 5.10.14 | 6        | 9.23%   |
| 4.1.34  | 6        | 9.23%   |
| 5.4.0   | 4        | 6.15%   |
| 5.8.0   | 2        | 3.08%   |
| 4.9.9   | 2        | 3.08%   |
| 4.9.76  | 2        | 3.08%   |
| 4.9.20  | 2        | 3.08%   |
| 4.9.155 | 2        | 3.08%   |
| 4.9.124 | 2        | 3.08%   |
| 4.1.38  | 2        | 3.08%   |
| 5.9.3   | 1        | 1.54%   |
| 5.5.9   | 1        | 1.54%   |
| 5.4.83  | 1        | 1.54%   |
| 5.4.32  | 1        | 1.54%   |
| 5.2.0   | 1        | 1.54%   |
| 5.17.9  | 1        | 1.54%   |
| 5.16.9  | 1        | 1.54%   |
| 5.15.48 | 1        | 1.54%   |
| 5.15.11 | 1        | 1.54%   |
| 5.14.14 | 1        | 1.54%   |
| 5.13.0  | 1        | 1.54%   |
| 5.10.74 | 1        | 1.54%   |
| 5.10.53 | 1        | 1.54%   |
| 5.10.26 | 1        | 1.54%   |
| 4.9.87  | 1        | 1.54%   |
| 4.18.0  | 1        | 1.54%   |
| 4.10.0  | 1        | 1.54%   |
| 4.1.25  | 1        | 1.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 17       | 26.56%  |
| 4.15    | 10       | 15.63%  |
| 5.10    | 9        | 14.06%  |
| 4.1     | 9        | 14.06%  |
| 5.4     | 6        | 9.38%   |
| 5.8     | 2        | 3.13%   |
| 5.15    | 2        | 3.13%   |
| 5.9     | 1        | 1.56%   |
| 5.5     | 1        | 1.56%   |
| 5.2     | 1        | 1.56%   |
| 5.17    | 1        | 1.56%   |
| 5.16    | 1        | 1.56%   |
| 5.14    | 1        | 1.56%   |
| 5.13    | 1        | 1.56%   |
| 4.18    | 1        | 1.56%   |
| 4.10    | 1        | 1.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 54       | 85.71%  |
| i686   | 9        | 14.29%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE4            | 26       | 40.63%  |
| KDE5            | 16       | 25%     |
| GNOME           | 8        | 12.5%   |
| XFCE            | 3        | 4.69%   |
| X-Cinnamon      | 2        | 3.13%   |
| LXQt            | 2        | 3.13%   |
| KDE             | 2        | 3.13%   |
| xinitrc         | 1        | 1.56%   |
| sway            | 1        | 1.56%   |
| MATE            | 1        | 1.56%   |
| GNOME Flashback | 1        | 1.56%   |
| Unknown         | 1        | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 59       | 93.65%  |
| Wayland | 3        | 4.76%   |
| Unknown | 1        | 1.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDM     | 26       | 40.63%  |
| SDDM    | 20       | 31.25%  |
| Unknown | 12       | 18.75%  |
| TDM     | 2        | 3.13%   |
| GDM     | 2        | 3.13%   |
| LightDM | 1        | 1.56%   |
| GDM3    | 1        | 1.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 34       | 52.31%  |
| ru_RU   | 17       | 26.15%  |
| en_US   | 10       | 15.38%  |
| ro_RO   | 2        | 3.08%   |
| ru_UA   | 1        | 1.54%   |
| en_GB   | 1        | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 53       | 82.81%  |
| EFI  | 11       | 17.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 35       | 55.56%  |
| Unknown | 21       | 33.33%  |
| Overlay | 5        | 7.94%   |
| Btrfs   | 2        | 3.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 37       | 56.92%  |
| Unknown | 18       | 27.69%  |
| GPT     | 10       | 15.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 53       | 84.13%  |
| Yes       | 10       | 15.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 43       | 67.19%  |
| Yes       | 21       | 32.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 27       | 42.86%  |
| Gigabyte Technology | 13       | 20.63%  |
| Biostar             | 9        | 14.29%  |
| MSI                 | 5        | 7.94%   |
| ASRock              | 5        | 7.94%   |
| Hewlett-Packard     | 2        | 3.17%   |
| ECS                 | 1        | 1.59%   |
| Dell                | 1        | 1.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS H110M-R               | 2        | 3.17%   |
| ASUS All Series            | 2        | 3.17%   |
| MSI Pro 3130 Microtower PC | 1        | 1.59%   |
| MSI MS-7695                | 1        | 1.59%   |
| MSI MS-7592                | 1        | 1.59%   |
| MSI MS-7529                | 1        | 1.59%   |
| MSI MS-7309                | 1        | 1.59%   |
| HP ProDesk 490 G2 MT       | 1        | 1.59%   |
| HP ProDesk 400 G4 MT       | 1        | 1.59%   |
| Gigabyte Z690 UD DDR4      | 1        | 1.59%   |
| Gigabyte X570 AORUS ULTRA  | 1        | 1.59%   |
| Gigabyte P41-ES3G          | 1        | 1.59%   |
| Gigabyte H81M-S2PV         | 1        | 1.59%   |
| Gigabyte H81M-HD3          | 1        | 1.59%   |
| Gigabyte H61M-S2-B3        | 1        | 1.59%   |
| Gigabyte H61M-S1           | 1        | 1.59%   |
| Gigabyte GA-970A-DS3       | 1        | 1.59%   |
| Gigabyte GA-880GM-USB3     | 1        | 1.59%   |
| Gigabyte G41M-ES2L         | 1        | 1.59%   |
| Gigabyte EP43-UD3L         | 1        | 1.59%   |
| Gigabyte B460MDS3HV2       | 1        | 1.59%   |
| Gigabyte B450M S2H V2      | 1        | 1.59%   |
| ECS GeForce7050M-M         | 1        | 1.59%   |
| Dell DM051                 | 1        | 1.59%   |
| Biostar TA790GX 128M       | 1        | 1.59%   |
| Biostar NF61D-A2           | 1        | 1.59%   |
| Biostar N68S3+             | 1        | 1.59%   |
| Biostar H61MGV3            | 1        | 1.59%   |
| Biostar H110MHC            | 1        | 1.59%   |
| Biostar GF8100 M2+ SE      | 1        | 1.59%   |
| Biostar A960G+             | 1        | 1.59%   |
| Biostar A960D+V3           | 1        | 1.59%   |
| Biostar A58MD              | 1        | 1.59%   |
| ASUS TUF X299 MARK 1       | 1        | 1.59%   |
| ASUS PRIME B550-PLUS       | 1        | 1.59%   |
| ASUS PRIME B350-PLUS       | 1        | 1.59%   |
| ASUS PRIME A520M-K         | 1        | 1.59%   |
| ASUS P8Z77-V PRO           | 1        | 1.59%   |
| ASUS P8H61-MX              | 1        | 1.59%   |
| ASUS P8H61-M LX3           | 1        | 1.59%   |
| ASUS P8B75-M LE            | 1        | 1.59%   |
| ASUS P7P55D-E              | 1        | 1.59%   |
| ASUS P5QL/EPU              | 1        | 1.59%   |
| ASUS P5P43TD               | 1        | 1.59%   |
| ASUS P5KPL-AM IN/ROEM/SI   | 1        | 1.59%   |
| ASUS P5GPL                 | 1        | 1.59%   |
| ASUS M5A78L-M LX3          | 1        | 1.59%   |
| ASUS M5A78L-M LX           | 1        | 1.59%   |
| ASUS M5A78L LE             | 1        | 1.59%   |
| ASUS M4A785TD-V EVO        | 1        | 1.59%   |
| ASUS M4A785-M              | 1        | 1.59%   |
| ASUS M2N-SLI DELUXE        | 1        | 1.59%   |
| ASUS H110M-K               | 1        | 1.59%   |
| ASUS F1A75-M LE            | 1        | 1.59%   |
| ASUS A_F_K20CE             | 1        | 1.59%   |
| ASUS A88X-PLUS             | 1        | 1.59%   |
| ASRock Z87 Extreme4        | 1        | 1.59%   |
| ASRock M3A770DE            | 1        | 1.59%   |
| ASRock H110M-DGS           | 1        | 1.59%   |
| ASRock B250M Pro4          | 1        | 1.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 3        | 4.76%   |
| HP ProDesk             | 2        | 3.17%   |
| ASUS M5A78L-M          | 2        | 3.17%   |
| ASUS H110M-R           | 2        | 3.17%   |
| ASUS All               | 2        | 3.17%   |
| MSI Pro                | 1        | 1.59%   |
| MSI MS-7695            | 1        | 1.59%   |
| MSI MS-7592            | 1        | 1.59%   |
| MSI MS-7529            | 1        | 1.59%   |
| MSI MS-7309            | 1        | 1.59%   |
| Gigabyte Z690          | 1        | 1.59%   |
| Gigabyte X570          | 1        | 1.59%   |
| Gigabyte P41-ES3G      | 1        | 1.59%   |
| Gigabyte H81M-S2PV     | 1        | 1.59%   |
| Gigabyte H81M-HD3      | 1        | 1.59%   |
| Gigabyte H61M-S2-B3    | 1        | 1.59%   |
| Gigabyte H61M-S1       | 1        | 1.59%   |
| Gigabyte GA-970A-DS3   | 1        | 1.59%   |
| Gigabyte GA-880GM-USB3 | 1        | 1.59%   |
| Gigabyte G41M-ES2L     | 1        | 1.59%   |
| Gigabyte EP43-UD3L     | 1        | 1.59%   |
| Gigabyte B460MDS3HV2   | 1        | 1.59%   |
| Gigabyte B450M         | 1        | 1.59%   |
| ECS GeForce7050M-M     | 1        | 1.59%   |
| Dell DM051             | 1        | 1.59%   |
| Biostar TA790GX        | 1        | 1.59%   |
| Biostar NF61D-A2       | 1        | 1.59%   |
| Biostar N68S3+         | 1        | 1.59%   |
| Biostar H61MGV3        | 1        | 1.59%   |
| Biostar H110MHC        | 1        | 1.59%   |
| Biostar GF8100         | 1        | 1.59%   |
| Biostar A960G+         | 1        | 1.59%   |
| Biostar A960D+V3       | 1        | 1.59%   |
| Biostar A58MD          | 1        | 1.59%   |
| ASUS TUF               | 1        | 1.59%   |
| ASUS P8Z77-V           | 1        | 1.59%   |
| ASUS P8H61-MX          | 1        | 1.59%   |
| ASUS P8H61-M           | 1        | 1.59%   |
| ASUS P8B75-M           | 1        | 1.59%   |
| ASUS P7P55D-E          | 1        | 1.59%   |
| ASUS P5QL              | 1        | 1.59%   |
| ASUS P5P43TD           | 1        | 1.59%   |
| ASUS P5KPL-AM          | 1        | 1.59%   |
| ASUS P5GPL             | 1        | 1.59%   |
| ASUS M5A78L            | 1        | 1.59%   |
| ASUS M4A785TD-V        | 1        | 1.59%   |
| ASUS M4A785-M          | 1        | 1.59%   |
| ASUS M2N-SLI           | 1        | 1.59%   |
| ASUS H110M-K           | 1        | 1.59%   |
| ASUS F1A75-M           | 1        | 1.59%   |
| ASUS A88X-PLUS         | 1        | 1.59%   |
| ASUS A                 | 1        | 1.59%   |
| ASRock Z87             | 1        | 1.59%   |
| ASRock M3A770DE        | 1        | 1.59%   |
| ASRock H110M-DGS       | 1        | 1.59%   |
| ASRock B250M           | 1        | 1.59%   |
| ASRock A320M-HDV       | 1        | 1.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 10       | 15.87%  |
| 2012 | 8        | 12.7%   |
| 2013 | 6        | 9.52%   |
| 2011 | 6        | 9.52%   |
| 2010 | 6        | 9.52%   |
| 2016 | 5        | 7.94%   |
| 2020 | 4        | 6.35%   |
| 2017 | 4        | 6.35%   |
| 2018 | 3        | 4.76%   |
| 2007 | 3        | 4.76%   |
| 2015 | 2        | 3.17%   |
| 2006 | 2        | 3.17%   |
| 2021 | 1        | 1.59%   |
| 2019 | 1        | 1.59%   |
| 2014 | 1        | 1.59%   |
| 2005 | 1        | 1.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 63       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 62       | 98.41%  |
| Enabled  | 1        | 1.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 63       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 3.01-4.0   | 24       | 37.5%   |
| 8.01-16.0  | 14       | 21.88%  |
| 4.01-8.0   | 7        | 10.94%  |
| 16.01-24.0 | 7        | 10.94%  |
| 2.01-3.0   | 4        | 6.25%   |
| 1.01-2.0   | 4        | 6.25%   |
| 32.01-64.0 | 3        | 4.69%   |
| 0.51-1.0   | 1        | 1.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1.01-2.0 | 26       | 37.68%  |
| 0.51-1.0 | 22       | 31.88%  |
| 2.01-3.0 | 8        | 11.59%  |
| 4.01-8.0 | 6        | 8.7%    |
| 3.01-4.0 | 4        | 5.8%    |
| 0.01-0.5 | 3        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 32       | 50%     |
| 2      | 19       | 29.69%  |
| 3      | 9        | 14.06%  |
| 4      | 3        | 4.69%   |
| 0      | 1        | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 50.79%  |
| Yes       | 31       | 49.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 63       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 79.37%  |
| Yes       | 13       | 20.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 56       | 88.89%  |
| Yes       | 7        | 11.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Moldova | 63       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City      | Desktops | Percent |
|-----------|----------|---------|
| Chisinau  | 26       | 41.27%  |
| Tiraspol  | 21       | 33.33%  |
| Tighina   | 2        | 3.17%   |
| Straseni  | 2        | 3.17%   |
| Tintareni | 1        | 1.59%   |
| Singera   | 1        | 1.59%   |
| R??bni??a | 1        | 1.59%   |
| Rezina    | 1        | 1.59%   |
| Lapusna   | 1        | 1.59%   |
| Ialoveni  | 1        | 1.59%   |
| Hincesti  | 1        | 1.59%   |
| Edine??   | 1        | 1.59%   |
| Drochia   | 1        | 1.59%   |
| Cazanesti | 1        | 1.59%   |
| C??u??eni | 1        | 1.59%   |
| B??l??i   | 1        | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 27     | 22.12%  |
| Seagate             | 20       | 22     | 19.23%  |
| WDC                 | 16       | 17     | 15.38%  |
| Toshiba             | 9        | 10     | 8.65%   |
| SPCC                | 5        | 6      | 4.81%   |
| Hitachi             | 5        | 6      | 4.81%   |
| Transcend           | 4        | 4      | 3.85%   |
| Kingston            | 4        | 4      | 3.85%   |
| Maxtor              | 3        | 4      | 2.88%   |
| Apacer              | 3        | 3      | 2.88%   |
| XPG                 | 1        | 1      | 0.96%   |
| Team                | 1        | 1      | 0.96%   |
| SK hynix            | 1        | 1      | 0.96%   |
| SanDisk             | 1        | 1      | 0.96%   |
| Phison              | 1        | 1      | 0.96%   |
| Patriot             | 1        | 1      | 0.96%   |
| Leven               | 1        | 1      | 0.96%   |
| Intel               | 1        | 1      | 0.96%   |
| HGST                | 1        | 1      | 0.96%   |
| Goodram             | 1        | 1      | 0.96%   |
| Goldkey             | 1        | 1      | 0.96%   |
| CHN25SATAS1         | 1        | 1      | 0.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Toshiba DT01ACA050 500GB               | 4        | 3.67%   |
| Toshiba DT01ACA100 1TB                 | 3        | 2.75%   |
| Samsung HD502HJ 500GB                  | 3        | 2.75%   |
| Kingston SHFS37A120G 120GB SSD         | 3        | 2.75%   |
| WDC WD5000AZRX-00A8LB0 500GB           | 2        | 1.83%   |
| Transcend TS64GSSD370S 64GB            | 2        | 1.83%   |
| Toshiba HDWD110 1TB                    | 2        | 1.83%   |
| SPCC Solid State Disk 128GB            | 2        | 1.83%   |
| Seagate ST500DM002-1BD142 500GB        | 2        | 1.83%   |
| Seagate ST4000VM000-2AF166 4TB         | 2        | 1.83%   |
| Seagate ST2000DM008-2FR102 2TB         | 2        | 1.83%   |
| Seagate ST1000DL002-9TT153 1TB         | 2        | 1.83%   |
| Samsung HD251HJ 250GB                  | 2        | 1.83%   |
| Samsung HD082GJ 80GB                   | 2        | 1.83%   |
| XPG NVMe SSD Drive 512GB               | 1        | 0.92%   |
| WDC WD62PURZ-85B3AY0 6TB               | 1        | 0.92%   |
| WDC WD5000AZRZ-00HTKB0 500GB           | 1        | 0.92%   |
| WDC WD5000AUDX-63WNHY0 500GB           | 1        | 0.92%   |
| WDC WD5000AAKX-08ERMA0 500GB           | 1        | 0.92%   |
| WDC WD5000AAKS-75V0A0 500GB            | 1        | 0.92%   |
| WDC WD5000AAKS-00WWPA0 500GB           | 1        | 0.92%   |
| WDC WD5000AAJS-00A8B0 500GB            | 1        | 0.92%   |
| WDC WD5000AADS-56S9B1 499GB            | 1        | 0.92%   |
| WDC WD3200BPVT-24ZEST0 320GB           | 1        | 0.92%   |
| WDC WD3200AVJS-63B6A0 320GB            | 1        | 0.92%   |
| WDC WD2500AAKX-00U6AA0 250GB           | 1        | 0.92%   |
| WDC WD20EZAZ-00GGJB0 2TB               | 1        | 0.92%   |
| WDC WD200EB-00CPF0 20GB                | 1        | 0.92%   |
| WDC WD10EZEX-00WN4A0 1TB               | 1        | 0.92%   |
| WDC WD1001FALS-00J7B0 1TB              | 1        | 0.92%   |
| Transcend TS256GSSD370S 256GB          | 1        | 0.92%   |
| Transcend TS128GSSD230S 128GB          | 1        | 0.92%   |
| Team L5 LITE SSD 240GB                 | 1        | 0.92%   |
| SPCC SSD162 56GB                       | 1        | 0.92%   |
| SPCC SSD162 120GB                      | 1        | 0.92%   |
| SPCC Solid State Disk 56GB             | 1        | 0.92%   |
| SK hynix NVMe SSD Drive 512GB          | 1        | 0.92%   |
| Seagate ST500LT012-9WS142 500GB        | 1        | 0.92%   |
| Seagate ST500LT012-1DG142 500GB        | 1        | 0.92%   |
| Seagate ST4000DM004-2CV104 4TB         | 1        | 0.92%   |
| Seagate ST3500418AS 500GB              | 1        | 0.92%   |
| Seagate ST3320613AS 320GB              | 1        | 0.92%   |
| Seagate ST320LM010-1KJ15C 320GB        | 1        | 0.92%   |
| Seagate ST320DM001 HD322GJ 320GB       | 1        | 0.92%   |
| Seagate ST3160023A 160GB               | 1        | 0.92%   |
| Seagate ST31000340NS 1TB               | 1        | 0.92%   |
| Seagate ST2000LM015-2E8174 2TB         | 1        | 0.92%   |
| Seagate ST2000DM001-1CH164 2TB         | 1        | 0.92%   |
| Seagate ST2000DL003-9VT166 2TB         | 1        | 0.92%   |
| Seagate ST1000VX005-2EZ102 1TB         | 1        | 0.92%   |
| Seagate ST1000NC001-1DY162 1TB         | 1        | 0.92%   |
| SanDisk SD7UB3Q256G1001 256GB SSD      | 1        | 0.92%   |
| Samsung SSD 970 EVO Plus 500GB         | 1        | 0.92%   |
| Samsung SSD 970 EVO 500GB              | 1        | 0.92%   |
| Samsung SSD 860 EVO 500GB              | 1        | 0.92%   |
| Samsung SSD 840 EVO 120GB              | 1        | 0.92%   |
| Samsung SP1614N 160GB                  | 1        | 0.92%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 1        | 0.92%   |
| Samsung SM963 2.5" NVMe PCIe SSD 128GB | 1        | 0.92%   |
| Samsung HM321HI 320GB                  | 1        | 0.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 22     | 28.17%  |
| Samsung Electronics | 17       | 20     | 23.94%  |
| WDC                 | 16       | 17     | 22.54%  |
| Toshiba             | 9        | 10     | 12.68%  |
| Hitachi             | 5        | 6      | 7.04%   |
| Maxtor              | 3        | 4      | 4.23%   |
| HGST                | 1        | 1      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SPCC                | 5        | 6      | 20%     |
| Transcend           | 4        | 4      | 16%     |
| Kingston            | 4        | 4      | 16%     |
| Apacer              | 3        | 3      | 12%     |
| Samsung Electronics | 2        | 2      | 8%      |
| Team                | 1        | 1      | 4%      |
| SanDisk             | 1        | 1      | 4%      |
| Patriot             | 1        | 1      | 4%      |
| Leven               | 1        | 1      | 4%      |
| Goodram             | 1        | 1      | 4%      |
| Goldkey             | 1        | 1      | 4%      |
| CHN25SATAS1         | 1        | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 53       | 80     | 64.63%  |
| SSD  | 23       | 26     | 28.05%  |
| NVMe | 6        | 9      | 7.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 59       | 106    | 90.77%  |
| NVMe | 6        | 9      | 9.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 52       | 82     | 71.23%  |
| 0.51-1.0   | 11       | 14     | 15.07%  |
| 1.01-2.0   | 6        | 6      | 8.22%   |
| 3.01-4.0   | 3        | 3      | 4.11%   |
| 4.01-10.0  | 1        | 1      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 13       | 20%     |
| 251-500        | 12       | 18.46%  |
| 51-100         | 12       | 18.46%  |
| 1-20           | 10       | 15.38%  |
| 501-1000       | 6        | 9.23%   |
| 21-50          | 5        | 7.69%   |
| More than 3000 | 2        | 3.08%   |
| 2001-3000      | 2        | 3.08%   |
| 1001-2000      | 2        | 3.08%   |
| Unknown        | 1        | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 34       | 52.31%  |
| 21-50          | 10       | 15.38%  |
| 51-100         | 8        | 12.31%  |
| 251-500        | 3        | 4.62%   |
| 101-250        | 3        | 4.62%   |
| 501-1000       | 3        | 4.62%   |
| 1001-2000      | 2        | 3.08%   |
| More than 3000 | 1        | 1.54%   |
| Unknown        | 1        | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD082GJ 80GB  | 2        | 2      | 7.69%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1        | 1      | 3.85%   |
| WDC WD5000AAKS-75V0A0 500GB       | 1        | 1      | 3.85%   |
| WDC WD5000AAKS-00WWPA0 500GB      | 1        | 1      | 3.85%   |
| WDC WD5000AADS-56S9B1 499GB       | 1        | 1      | 3.85%   |
| WDC WD2500AAKX-00U6AA0 250GB      | 1        | 1      | 3.85%   |
| Toshiba DT01ACA050 500GB          | 1        | 1      | 3.85%   |
| Team L5 LITE SSD 240GB            | 1        | 1      | 3.85%   |
| SPCC SSD162 120GB                 | 1        | 1      | 3.85%   |
| SPCC Solid State Disk 56GB        | 1        | 2      | 3.85%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 3.85%   |
| Seagate ST320DM001 HD322GJ 320GB  | 1        | 1      | 3.85%   |
| Seagate ST3160023A 160GB          | 1        | 1      | 3.85%   |
| Seagate ST31000340NS 1TB          | 1        | 1      | 3.85%   |
| Seagate ST1000DL002-9TT153 1TB    | 1        | 1      | 3.85%   |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 3.85%   |
| Samsung Electronics HD080HJ/ 80GB | 1        | 1      | 3.85%   |
| Maxtor STM380215AS 80GB           | 1        | 1      | 3.85%   |
| Maxtor STM3160811AS 160GB         | 1        | 1      | 3.85%   |
| Maxtor STM3160211AS 160GB         | 1        | 1      | 3.85%   |
| Maxtor 4R120L0 128GB              | 1        | 1      | 3.85%   |
| Kingston SHFS37A120G 120GB SSD    | 1        | 1      | 3.85%   |
| Hitachi HTS545025B9A300 250GB     | 1        | 1      | 3.85%   |
| Hitachi HDP725050GLA360 500GB     | 1        | 1      | 3.85%   |
| Hitachi HDP725025GLA380 250GB     | 1        | 2      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 20%     |
| Seagate             | 5        | 5      | 20%     |
| Samsung Electronics | 4        | 4      | 16%     |
| Maxtor              | 3        | 4      | 12%     |
| Hitachi             | 3        | 4      | 12%     |
| SPCC                | 2        | 3      | 8%      |
| Toshiba             | 1        | 1      | 4%      |
| Team                | 1        | 1      | 4%      |
| Kingston            | 1        | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 23.81%  |
| Seagate             | 5        | 5      | 23.81%  |
| Samsung Electronics | 4        | 4      | 19.05%  |
| Maxtor              | 3        | 4      | 14.29%  |
| Hitachi             | 3        | 4      | 14.29%  |
| Toshiba             | 1        | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 23     | 82.61%  |
| SSD  | 4        | 5      | 17.39%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD3200BPVT-24ZEST0 320GB      | 1        | 1      | 33.33%  |
| Samsung Electronics HD502HJ 500GB | 1        | 1      | 33.33%  |
| Samsung Electronics HD322GJ 320GB | 1        | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 3      | 66.67%  |
| WDC                 | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 35       | 54     | 46.05%  |
| Malfunc  | 23       | 28     | 30.26%  |
| Detected | 15       | 29     | 19.74%  |
| Failed   | 3        | 4      | 3.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 36       | 46.15%  |
| AMD                      | 21       | 26.92%  |
| Nvidia                   | 6        | 7.69%   |
| JMicron Technology       | 5        | 6.41%   |
| Samsung Electronics      | 4        | 5.13%   |
| ASMedia Technology       | 2        | 2.56%   |
| SK hynix                 | 1        | 1.28%   |
| Phison Electronics       | 1        | 1.28%   |
| Marvell Technology Group | 1        | 1.28%   |
| ADATA Technology         | 1        | 1.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 11       | 9.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10       | 8.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 4.31%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 4.31%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 5        | 4.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 3.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 3.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 2.59%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 2.59%   |
| Nvidia MCP61 IDE                                                                        | 3        | 2.59%   |
| JMicron JMB368 IDE controller                                                           | 3        | 2.59%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 2.59%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 1.72%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.72%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2        | 1.72%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2        | 1.72%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2        | 1.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 1.72%   |
| AMD FCH IDE Controller                                                                  | 2        | 1.72%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 1.72%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1        | 0.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.86%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.86%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 1        | 0.86%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 1        | 0.86%   |
| Nvidia MCP67 IDE Controller                                                             | 1        | 0.86%   |
| Nvidia MCP67 AHCI Controller                                                            | 1        | 0.86%   |
| Nvidia MCP55 SATA Controller                                                            | 1        | 0.86%   |
| Nvidia MCP55 IDE                                                                        | 1        | 0.86%   |
| Marvell Group 88SE914D SATA-600 Controller                                              | 1        | 0.86%   |
| Intel SSD 600P Series                                                                   | 1        | 0.86%   |
| Intel SATA Controller [RAID mode]                                                       | 1        | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 1        | 0.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.86%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1        | 0.86%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                            | 1        | 0.86%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                           | 1        | 0.86%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 1        | 0.86%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 1        | 0.86%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]           | 1        | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 0.86%   |
| AMD FCH SATA Controller D                                                               | 1        | 0.86%   |
| AMD 400 Series Chipset SATA Controller                                                  | 1        | 0.86%   |
| AMD 300 Series Chipset SATA Controller                                                  | 1        | 0.86%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 1        | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 41       | 48.24%  |
| IDE  | 36       | 42.35%  |
| NVMe | 6        | 7.06%   |
| RAID | 2        | 2.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 57.14%  |
| AMD    | 27       | 42.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Pentium CPU G4400 @ 3.30GHz               | 2        | 3.17%   |
| Intel Core i5-4670K CPU @ 3.40GHz               | 2        | 3.17%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 2        | 3.17%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 2        | 3.17%   |
| AMD Phenom II X6 1055T Processor                | 2        | 3.17%   |
| AMD Athlon II X2 280 Processor                  | 2        | 3.17%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1        | 1.59%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz          | 1        | 1.59%   |
| Intel Pentium D CPU 2.80GHz                     | 1        | 1.59%   |
| Intel Pentium D CPU 2.66GHz                     | 1        | 1.59%   |
| Intel Pentium CPU N3700 @ 1.60GHz               | 1        | 1.59%   |
| Intel Pentium CPU G640 @ 2.80GHz                | 1        | 1.59%   |
| Intel Pentium CPU G4620 @ 3.70GHz               | 1        | 1.59%   |
| Intel Pentium CPU G4560 @ 3.50GHz               | 1        | 1.59%   |
| Intel Pentium CPU G3240 @ 3.10GHz               | 1        | 1.59%   |
| Intel Pentium 4 CPU 2.66GHz                     | 1        | 1.59%   |
| Intel Core i7-7820X CPU @ 3.60GHz               | 1        | 1.59%   |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1        | 1.59%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 1        | 1.59%   |
| Intel Core i5-4690 CPU @ 3.50GHz                | 1        | 1.59%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 1        | 1.59%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 1        | 1.59%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 1.59%   |
| Intel Core i5-10600K CPU @ 4.10GHz              | 1        | 1.59%   |
| Intel Core i5 CPU 750 @ 2.67GHz                 | 1        | 1.59%   |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 1        | 1.59%   |
| Intel Core i3-7100 CPU @ 3.90GHz                | 1        | 1.59%   |
| Intel Core i3-6100 CPU @ 3.70GHz                | 1        | 1.59%   |
| Intel Core i3-3240 CPU @ 3.40GHz                | 1        | 1.59%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 1        | 1.59%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 1        | 1.59%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz           | 1        | 1.59%   |
| Intel Celeron CPU G1630 @ 2.80GHz               | 1        | 1.59%   |
| Intel Celeron CPU E1200 @ 1.60GHz               | 1        | 1.59%   |
| Intel Celeron CPU 2.53GHz                       | 1        | 1.59%   |
| Intel 12th Gen Core i5-12600K                   | 1        | 1.59%   |
| AMD Ryzen 5 1600 Six-Core Processor             | 1        | 1.59%   |
| AMD Ryzen 3 4300G with Radeon Graphics          | 1        | 1.59%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1        | 1.59%   |
| AMD Phenom II X4 945 Processor                  | 1        | 1.59%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 1.59%   |
| AMD FX-8120 Eight-Core Processor                | 1        | 1.59%   |
| AMD Athlon II X4 645 Processor                  | 1        | 1.59%   |
| AMD Athlon II X4 635 Processor                  | 1        | 1.59%   |
| AMD Athlon II X2 250 Processor                  | 1        | 1.59%   |
| AMD Athlon II X2 245 Processor                  | 1        | 1.59%   |
| AMD Athlon II X2 240 Processor                  | 1        | 1.59%   |
| AMD Athlon II X2 220 Processor                  | 1        | 1.59%   |
| AMD Athlon 64 X2 Dual Core Processor 5600+      | 1        | 1.59%   |
| AMD Athlon 64 X2 Dual Core Processor 4800+      | 1        | 1.59%   |
| AMD Athlon 64 X2 Dual Core Processor 4400+      | 1        | 1.59%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+      | 1        | 1.59%   |
| AMD Athlon 200GE with Radeon Vega Graphics      | 1        | 1.59%   |
| AMD A8-3870 APU with Radeon HD Graphics         | 1        | 1.59%   |
| AMD A4-4020 APU with Radeon HD Graphics         | 1        | 1.59%   |
| AMD A4-3400 APU with Radeon HD Graphics         | 1        | 1.59%   |
| AMD A10-7870K Radeon R7, 12 Compute Cores 4C+8G | 1        | 1.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 10       | 15.87%  |
| Intel Pentium           | 7        | 11.11%  |
| AMD Athlon II X2        | 6        | 9.52%   |
| Intel Core i3           | 5        | 7.94%   |
| AMD Athlon 64 X2        | 4        | 6.35%   |
| Intel Celeron           | 3        | 4.76%   |
| Intel Pentium D         | 2        | 3.17%   |
| Intel Core i7           | 2        | 3.17%   |
| Intel Core 2 Duo        | 2        | 3.17%   |
| AMD Ryzen 7             | 2        | 3.17%   |
| AMD Ryzen 3             | 2        | 3.17%   |
| AMD Phenom II X6        | 2        | 3.17%   |
| AMD FX                  | 2        | 3.17%   |
| AMD Athlon II X4        | 2        | 3.17%   |
| AMD A4                  | 2        | 3.17%   |
| Other                   | 1        | 1.59%   |
| Intel Pentium Dual-Core | 1        | 1.59%   |
| Intel Pentium Dual      | 1        | 1.59%   |
| Intel Pentium 4         | 1        | 1.59%   |
| Intel Core 2 Quad       | 1        | 1.59%   |
| AMD Ryzen 5             | 1        | 1.59%   |
| AMD Phenom II X4        | 1        | 1.59%   |
| AMD Athlon              | 1        | 1.59%   |
| AMD A8                  | 1        | 1.59%   |
| AMD A10                 | 1        | 1.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 32       | 50%     |
| 4       | 19       | 29.69%  |
| 8       | 3        | 4.69%   |
| 6       | 3        | 4.69%   |
| 1       | 3        | 4.69%   |
| Unknown | 3        | 4.69%   |
| 10      | 1        | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 63       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 41       | 64.06%  |
| 2       | 20       | 31.25%  |
| Unknown | 3        | 4.69%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 63       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 9        | 14.29%  |
| 0x010000c8 | 6        | 9.52%   |
| 0x906e9    | 4        | 6.35%   |
| 0x306c3    | 4        | 6.35%   |
| 0x306a9    | 4        | 6.35%   |
| 0x506e3    | 3        | 4.76%   |
| 0x206a7    | 3        | 4.76%   |
| 0x1067a    | 3        | 4.76%   |
| 0xf47      | 2        | 3.17%   |
| 0x6fd      | 2        | 3.17%   |
| 0x010000dc | 2        | 3.17%   |
| 0xf49      | 1        | 1.59%   |
| 0xf41      | 1        | 1.59%   |
| 0xa0655    | 1        | 1.59%   |
| 0x90672    | 1        | 1.59%   |
| 0x50654    | 1        | 1.59%   |
| 0x406c3    | 1        | 1.59%   |
| 0x20655    | 1        | 1.59%   |
| 0x106e5    | 1        | 1.59%   |
| 0x10676    | 1        | 1.59%   |
| 0x08701021 | 1        | 1.59%   |
| 0x08600106 | 1        | 1.59%   |
| 0x08108109 | 1        | 1.59%   |
| 0x08101102 | 1        | 1.59%   |
| 0x08001138 | 1        | 1.59%   |
| 0x06003106 | 1        | 1.59%   |
| 0x06000852 | 1        | 1.59%   |
| 0x0600063e | 1        | 1.59%   |
| 0x03000027 | 1        | 1.59%   |
| 0x03000025 | 1        | 1.59%   |
| 0x010000db | 1        | 1.59%   |
| 0x010000b6 | 1        | 1.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| K10              | 11       | 17.46%  |
| Haswell          | 6        | 9.52%   |
| Skylake          | 4        | 6.35%   |
| Penryn           | 4        | 6.35%   |
| NetBurst         | 4        | 6.35%   |
| KabyLake         | 4        | 6.35%   |
| K8 Hammer        | 4        | 6.35%   |
| IvyBridge        | 4        | 6.35%   |
| Zen 2            | 3        | 4.76%   |
| SandyBridge      | 3        | 4.76%   |
| Zen              | 2        | 3.17%   |
| Piledriver       | 2        | 3.17%   |
| K10 Llano        | 2        | 3.17%   |
| Core             | 2        | 3.17%   |
| Zen+             | 1        | 1.59%   |
| Westmere         | 1        | 1.59%   |
| Steamroller      | 1        | 1.59%   |
| Silvermont       | 1        | 1.59%   |
| Nehalem          | 1        | 1.59%   |
| CometLake        | 1        | 1.59%   |
| Bulldozer        | 1        | 1.59%   |
| Alderlake Hybrid | 1        | 1.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 27       | 41.54%  |
| AMD    | 22       | 33.85%  |
| Intel  | 16       | 24.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GF108 [GeForce GT 630]                                                            | 3        | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 4.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 2.9%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2        | 2.9%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 2.9%    |
| Nvidia GF108 [GeForce GT 440]                                                            | 2        | 2.9%    |
| Intel HD Graphics 630                                                                    | 2        | 2.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2        | 2.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2        | 2.9%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2        | 2.9%    |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 1.45%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1        | 1.45%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 1.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 1.45%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1        | 1.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1        | 1.45%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1        | 1.45%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 1.45%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1        | 1.45%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1        | 1.45%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 1        | 1.45%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1        | 1.45%   |
| Nvidia G73 [GeForce 7600 GS]                                                             | 1        | 1.45%   |
| Nvidia C77 [GeForce 8100 / nForce 720a]                                                  | 1        | 1.45%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1        | 1.45%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 1        | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 1        | 1.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 1.45%   |
| Intel HD Graphics 530                                                                    | 1        | 1.45%   |
| Intel HD Graphics 510                                                                    | 1        | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1        | 1.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1        | 1.45%   |
| Intel AlderLake-S GT1                                                                    | 1        | 1.45%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 1        | 1.45%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 1        | 1.45%   |
| AMD Trinity 2 [Radeon HD 7480D]                                                          | 1        | 1.45%   |
| AMD RV730 PRO [Radeon HD 4650]                                                           | 1        | 1.45%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 1        | 1.45%   |
| AMD RV635 [Radeon HD 3650/3750/4570/4580]                                                | 1        | 1.45%   |
| AMD RV570 [Radeon X1950 PRO] (Secondary)                                                 | 1        | 1.45%   |
| AMD RV570 [Radeon X1950 PRO]                                                             | 1        | 1.45%   |
| AMD RV380 [Radeon X550/X600] (Secondary)                                                 | 1        | 1.45%   |
| AMD RV380 [Radeon X550/X600]                                                             | 1        | 1.45%   |
| AMD RV370 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 1        | 1.45%   |
| AMD RV370 [Radeon X300/X550/X1050 Series]                                                | 1        | 1.45%   |
| AMD RS780L [Radeon 3000]                                                                 | 1        | 1.45%   |
| AMD RS780D [Radeon HD 3300]                                                              | 1        | 1.45%   |
| AMD Renoir                                                                               | 1        | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1        | 1.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1        | 1.45%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 1        | 1.45%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 1        | 1.45%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1        | 1.45%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 1        | 1.45%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 1.45%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1        | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Nvidia | 27       | 41.54%  |
| 1 x AMD    | 18       | 27.69%  |
| 1 x Intel  | 16       | 24.62%  |
| 2 x AMD    | 4        | 6.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 48       | 71.64%  |
| Proprietary | 12       | 17.91%  |
| Unknown     | 7        | 10.45%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 29.41%  |
| 1.01-2.0   | 14       | 20.59%  |
| 0.01-0.5   | 14       | 20.59%  |
| 0.51-1.0   | 10       | 14.71%  |
| 3.01-4.0   | 7        | 10.29%  |
| 5.01-6.0   | 2        | 2.94%   |
| 2.01-3.0   | 1        | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 18       | 29.51%  |
| Goldstar             | 13       | 21.31%  |
| Philips              | 8        | 13.11%  |
| Acer                 | 6        | 9.84%   |
| Dell                 | 4        | 6.56%   |
| Hewlett-Packard      | 3        | 4.92%   |
| AOC                  | 3        | 4.92%   |
| ViewSonic            | 1        | 1.64%   |
| Plain Tree Systems   | 1        | 1.64%   |
| Medion               | 1        | 1.64%   |
| HannStar             | 1        | 1.64%   |
| BenQ                 | 1        | 1.64%   |
| Ancor Communications | 1        | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM0108 1280x1024 312x234mm 15.4-inch   | 2        | 3.23%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 2        | 3.23%   |
| ViewSonic VA521-1 VSCF318 1024x768 304x228mm 15.0-inch                 | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM03D1 1680x1050 433x271mm 20.1-inch   | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch   | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch    | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch    | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch   | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM0213 1680x1050 408x306mm 20.1-inch   | 1        | 1.61%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch    | 1        | 1.61%   |
| Samsung Electronics SMB2440 SAM06AF 1920x1080 531x299mm 24.0-inch      | 1        | 1.61%   |
| Samsung Electronics SMB2030 SAM063D 1600x900 443x249mm 20.0-inch       | 1        | 1.61%   |
| Samsung Electronics S27F358 SAM0D73 1920x1080 598x336mm 27.0-inch      | 1        | 1.61%   |
| Samsung Electronics S22E391 SAM0C0D 1920x1080 477x268mm 21.5-inch      | 1        | 1.61%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1        | 1.61%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1        | 1.61%   |
| Samsung Electronics S/T 77E/76E STN0005 1280x1024 312x234mm 15.4-inch  | 1        | 1.61%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1        | 1.61%   |
| Plain Tree Systems XAP-192i PTS03D5 1280x1024 376x301mm 19.0-inch      | 1        | 1.61%   |
| Philips PHL 275E2F PHLC23A 2560x1440 597x336mm 27.0-inch               | 1        | 1.61%   |
| Philips PHL 246E7 PHLC107 1920x1080 521x293mm 23.5-inch                | 1        | 1.61%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 1.61%   |
| Philips PHL 240V5A PHLC10C 1920x1080 527x296mm 23.8-inch               | 1        | 1.61%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch                | 1        | 1.61%   |
| Philips PHL 234E5 PHLC0C7 1920x1080 510x290mm 23.1-inch                | 1        | 1.61%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1        | 1.61%   |
| Philips 201E PHLC033 1600x900 443x249mm 20.0-inch                      | 1        | 1.61%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                     | 1        | 1.61%   |
| Medion MD32119PR MED89C1 1280x1024 376x301mm 19.0-inch                 | 1        | 1.61%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch           | 1        | 1.61%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch             | 1        | 1.61%   |
| Hewlett-Packard 24x HPN3635 1920x1080 527x297mm 23.8-inch              | 1        | 1.61%   |
| HannStar HW223 HSD5B10 1680x1050 433x271mm 20.1-inch                   | 1        | 1.61%   |
| Goldstar W2343 GSM5700 1920x1080 474x296mm 22.0-inch                   | 1        | 1.61%   |
| Goldstar W2043 GSM4E9D 1600x900 450x250mm 20.3-inch                    | 1        | 1.61%   |
| Goldstar W2042 GSM4E7E 1680x1050 434x270mm 20.1-inch                   | 1        | 1.61%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch               | 1        | 1.61%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1        | 1.61%   |
| Goldstar M237WDP GSM5779 1920x1080 510x290mm 23.1-inch                 | 1        | 1.61%   |
| Goldstar L1953TR GSM4B44 1280x1024 340x270mm 17.1-inch                 | 1        | 1.61%   |
| Goldstar L1750U GSM440C 1280x1024 338x270mm 17.0-inch                  | 1        | 1.61%   |
| Goldstar L1750SQ GSM43E8 1280x1024 340x270mm 17.1-inch                 | 1        | 1.61%   |
| Goldstar L1717S GSM43FF 1280x1024 338x270mm 17.0-inch                  | 1        | 1.61%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                    | 1        | 1.61%   |
| Dell S2721DS DELA19D 2560x1440 597x336mm 27.0-inch                     | 1        | 1.61%   |
| Dell P2416D DELA0C4 2560x1440 527x296mm 23.8-inch                      | 1        | 1.61%   |
| Dell P2314H DEL4099 1920x1080 510x290mm 23.1-inch                      | 1        | 1.61%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                      | 1        | 1.61%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 1        | 1.61%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 1        | 1.61%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 1        | 1.61%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                         | 1        | 1.61%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch   | 1        | 1.61%   |
| Acer X203H ACR0075 1600x900 443x249mm 20.0-inch                        | 1        | 1.61%   |
| Acer X193HQ ACR0064 1366x768 344x194mm 15.5-inch                       | 1        | 1.61%   |
| Acer V206HQL ACR0334 1600x900 432x240mm 19.5-inch                      | 1        | 1.61%   |
| Acer V193W ACR001A 1440x900 410x256mm 19.0-inch                        | 1        | 1.61%   |
| Acer P226HQL ACR0198 1920x1080 480x270mm 21.7-inch                     | 1        | 1.61%   |
| Acer A221HQL ACR01B3 1920x1080 477x268mm 21.5-inch                     | 1        | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 34.43%  |
| 1280x1024 (SXGA)   | 11       | 18.03%  |
| 1600x900 (HD+)     | 5        | 8.2%    |
| 1440x900 (WXGA+)   | 5        | 8.2%    |
| 1366x768 (WXGA)    | 5        | 8.2%    |
| 1680x1050 (WSXGA+) | 4        | 6.56%   |
| 2560x1440 (QHD)    | 3        | 4.92%   |
| 2560x1080          | 2        | 3.28%   |
| 1600x1200          | 2        | 3.28%   |
| 1024x768 (XGA)     | 2        | 3.28%   |
| 1360x768           | 1        | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 19     | 10       | 16.13%  |
| 23     | 8        | 12.9%   |
| 20     | 8        | 12.9%   |
| 24     | 6        | 9.68%   |
| 21     | 6        | 9.68%   |
| 18     | 6        | 9.68%   |
| 15     | 6        | 9.68%   |
| 27     | 5        | 8.06%   |
| 17     | 5        | 8.06%   |
| 34     | 2        | 3.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 25       | 40.98%  |
| 501-600     | 18       | 29.51%  |
| 301-350     | 11       | 18.03%  |
| 351-400     | 5        | 8.2%    |
| 701-800     | 2        | 3.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 34       | 56.67%  |
| 5/4   | 9        | 15%     |
| 4/3   | 7        | 11.67%  |
| 16/10 | 7        | 11.67%  |
| 21/9  | 2        | 3.33%   |
| 3/2   | 1        | 1.67%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 20       | 32.26%  |
| 201-250        | 19       | 30.65%  |
| 141-150        | 10       | 16.13%  |
| 301-350        | 5        | 8.06%   |
| 111-120        | 4        | 6.45%   |
| 351-500        | 2        | 3.23%   |
| 101-110        | 2        | 3.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 47       | 77.05%  |
| 101-120 | 13       | 21.31%  |
| 121-160 | 1        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 60       | 95.24%  |
| 2     | 2        | 3.17%   |
| 0     | 1        | 1.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 44       | 57.89%  |
| Intel                    | 9        | 11.84%  |
| Qualcomm Atheros         | 7        | 9.21%   |
| Nvidia                   | 6        | 7.89%   |
| Xiaomi                   | 1        | 1.32%   |
| TP-Link                  | 1        | 1.32%   |
| Realtek                  | 1        | 1.32%   |
| Ralink                   | 1        | 1.32%   |
| MediaTek                 | 1        | 1.32%   |
| Marvell Technology Group | 1        | 1.32%   |
| D-Link System            | 1        | 1.32%   |
| D-Link                   | 1        | 1.32%   |
| Broadcom                 | 1        | 1.32%   |
| ASIX Electronics         | 1        | 1.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 40       | 50%     |
| Nvidia MCP61 Ethernet                                                  | 3        | 3.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 2.5%    |
| Intel Wi-Fi 6 AX200                                                    | 2        | 2.5%    |
| Intel I211 Gigabit Network Connection                                  | 2        | 2.5%    |
| Intel Ethernet Connection (2) I219-V                                   | 2        | 2.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1        | 1.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 1.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1        | 1.25%   |
| Realtek 802.11n NIC                                                    | 1        | 1.25%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                   | 1        | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.25%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 1.25%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1        | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.25%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1        | 1.25%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 1.25%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 1.25%   |
| Nvidia MCP77 Ethernet                                                  | 1        | 1.25%   |
| Nvidia MCP67 Ethernet                                                  | 1        | 1.25%   |
| Nvidia MCP55 Ethernet                                                  | 1        | 1.25%   |
| MediaTek TECNO SPARK 3                                                 | 1        | 1.25%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1        | 1.25%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 1.25%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.25%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 1.25%   |
| Intel Ethernet Connection (11) I219-V                                  | 1        | 1.25%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 1.25%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]   | 1        | 1.25%   |
| D-Link 802.11 n WLAN                                                   | 1        | 1.25%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                     | 1        | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1        | 1.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Qualcomm Atheros      | 3        | 23.08%  |
| Realtek Semiconductor | 2        | 15.38%  |
| Intel                 | 2        | 15.38%  |
| TP-Link               | 1        | 7.69%   |
| Realtek               | 1        | 7.69%   |
| Ralink                | 1        | 7.69%   |
| D-Link System         | 1        | 7.69%   |
| D-Link                | 1        | 7.69%   |
| Broadcom              | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 2        | 15.38%  |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 1        | 7.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 7.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 7.69%   |
| Realtek 802.11n NIC                                                    | 1        | 7.69%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                   | 1        | 7.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 7.69%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 1        | 7.69%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn] | 1        | 7.69%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]   | 1        | 7.69%   |
| D-Link 802.11 n WLAN                                                   | 1        | 7.69%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                     | 1        | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 44       | 66.67%  |
| Intel                    | 8        | 12.12%  |
| Nvidia                   | 6        | 9.09%   |
| Qualcomm Atheros         | 4        | 6.06%   |
| Xiaomi                   | 1        | 1.52%   |
| MediaTek                 | 1        | 1.52%   |
| Marvell Technology Group | 1        | 1.52%   |
| ASIX Electronics         | 1        | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40       | 59.7%   |
| Nvidia MCP61 Ethernet                                             | 3        | 4.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 2.99%   |
| Intel I211 Gigabit Network Connection                             | 2        | 2.99%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 2.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 1.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 1.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 1.49%   |
| Nvidia MCP77 Ethernet                                             | 1        | 1.49%   |
| Nvidia MCP67 Ethernet                                             | 1        | 1.49%   |
| Nvidia MCP55 Ethernet                                             | 1        | 1.49%   |
| MediaTek TECNO SPARK 3                                            | 1        | 1.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 1.49%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.49%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.49%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.49%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.49%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.49%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 63       | 82.89%  |
| WiFi     | 13       | 17.11%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 56       | 91.8%   |
| WiFi     | 5        | 8.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 53       | 84.13%  |
| 2     | 10       | 15.87%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 98.41%  |
| Yes  | 1        | 1.59%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 2        | 28.57%  |
| Integrated System Solution | 1        | 14.29%  |
| IMC Networks               | 1        | 14.29%  |
| Cambridge Silicon Radio    | 1        | 14.29%  |
| Broadcom                   | 1        | 14.29%  |
| ASUSTek Computer           | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                               | 2        | 28.57%  |
| Integrated System Solution Bluetooth Device         | 1        | 14.29%  |
| IMC Networks Bluetooth Radio                        | 1        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 14.29%  |
| Broadcom BCM92045B3 ROM                             | 1        | 14.29%  |
| ASUS BCM20702A0                                     | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 36       | 37.11%  |
| AMD                       | 28       | 28.87%  |
| Nvidia                    | 26       | 26.8%   |
| Texas Instruments         | 1        | 1.03%   |
| Shenzhen Rapoo Technology | 1        | 1.03%   |
| Plantronics               | 1        | 1.03%   |
| Kingston Technology       | 1        | 1.03%   |
| GN Netcom                 | 1        | 1.03%   |
| Creative Labs             | 1        | 1.03%   |
| C-Media Electronics       | 1        | 1.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11       | 9.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8        | 7.21%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6        | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 5        | 4.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5        | 4.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4        | 3.6%    |
| AMD FCH Azalia Controller                                                                         | 4        | 3.6%    |
| Nvidia MCP61 High Definition Audio                                                                | 3        | 2.7%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 3        | 2.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3        | 2.7%    |
| Intel 200 Series PCH HD Audio                                                                     | 3        | 2.7%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 3        | 2.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2        | 1.8%    |
| Nvidia GM204 High Definition Audio Controller                                                     | 2        | 1.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2        | 1.8%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2        | 1.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2        | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2        | 1.8%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 2        | 1.8%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2        | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2        | 1.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2        | 1.8%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2        | 1.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2        | 1.8%    |
| Texas Instruments PCM2902 Audio Codec                                                             | 1        | 0.9%    |
| Shenzhen Rapoo Technology Wireless Audio                                                          | 1        | 0.9%    |
| Plantronics Audio 628 USB                                                                         | 1        | 0.9%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1        | 0.9%    |
| Nvidia MCP67 High Definition Audio                                                                | 1        | 0.9%    |
| Nvidia MCP55 High Definition Audio                                                                | 1        | 0.9%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1        | 0.9%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 1        | 0.9%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 0.9%    |
| Kingston Technology HyperX 7.1 Audio                                                              | 1        | 0.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1        | 0.9%    |
| Intel Comet Lake PCH cAVS                                                                         | 1        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 0.9%    |
| Intel Alder Lake-S HD Audio Controller                                                            | 1        | 0.9%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1        | 0.9%    |
| GN Netcom enc060:Buttons Volume up/down/mute + phone [Jabra]                                      | 1        | 0.9%    |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]                         | 1        | 0.9%    |
| C-Media Electronics USB Audio Device                                                              | 1        | 0.9%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1        | 0.9%    |
| AMD Trinity HDMI Audio Controller                                                                 | 1        | 0.9%    |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1        | 0.9%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 1        | 0.9%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1        | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1        | 0.9%    |
| AMD Navi 10 HDMI Audio                                                                            | 1        | 0.9%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1        | 0.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 0.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 27       | 46.55%  |
| Kingston            | 10       | 17.24%  |
| SK hynix            | 2        | 3.45%   |
| Samsung Electronics | 2        | 3.45%   |
| Micron Technology   | 2        | 3.45%   |
| G.Skill             | 2        | 3.45%   |
| Transcend           | 1        | 1.72%   |
| Team                | 1        | 1.72%   |
| Silicon Power       | 1        | 1.72%   |
| Nanya Technology    | 1        | 1.72%   |
| Hexon               | 1        | 1.72%   |
| Goodram             | 1        | 1.72%   |
| Goldkey             | 1        | 1.72%   |
| Elpida              | 1        | 1.72%   |
| Crucial             | 1        | 1.72%   |
| AVEXIR              | 1        | 1.72%   |
| Apacer              | 1        | 1.72%   |
| A-DATA Technology   | 1        | 1.72%   |
| Unknown             | 1        | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                | 3        | 4.35%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 3        | 4.35%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                    | 2        | 2.9%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 2        | 2.9%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s               | 2        | 2.9%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 2        | 2.9%    |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                | 2        | 2.9%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s        | 2        | 2.9%    |
| Unknown RAM Module 8192MB DIMM 1333MT/s                    | 1        | 1.45%   |
| Unknown RAM Module 512MB DIMM SDRAM                        | 1        | 1.45%   |
| Unknown RAM Module 4GB DIMM 667MT/s                        | 1        | 1.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 1        | 1.45%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s               | 1        | 1.45%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                   | 1        | 1.45%   |
| Unknown RAM Module 2GB DIMM 667MT/s                        | 1        | 1.45%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s               | 1        | 1.45%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 1        | 1.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1        | 1.45%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                 | 1        | 1.45%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                | 1        | 1.45%   |
| Unknown RAM Module 2048MB DIMM                             | 1        | 1.45%   |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 1        | 1.45%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                | 1        | 1.45%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s                 | 1        | 1.45%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s  | 1        | 1.45%   |
| Unknown RAM ..E-D3U1600M/4G 4096MB DIMM DDR3 800MT/s       | 1        | 1.45%   |
| Transcend RAM JM1333KLH-4G 4GB DIMM DDR3 1333MT/s          | 1        | 1.45%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                 | 1        | 1.45%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 400MT/s        | 1        | 1.45%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s        | 1        | 1.45%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 400MT/s        | 1        | 1.45%   |
| Silicon Power RAM DCLT2GN568S 2048MB DIMM DDR3 1600MT/s    | 1        | 1.45%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s        | 1        | 1.45%   |
| Samsung RAM M3 78T6553CZ3-CD5 512MB DIMM DDR 533MT/s       | 1        | 1.45%   |
| Nanya RAM M2F2G64CB88B7N-CG 2048MB DIMM DDR3 1333MT/s      | 1        | 1.45%   |
| Micron RAM Module 4GB DIMM DDR3 1600MT/s                   | 1        | 1.45%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s        | 1        | 1.45%   |
| Micron RAM 16JTF25664AZ-1G4G1 2048MB DIMM DDR3 1400MT/s    | 1        | 1.45%   |
| Kingston RAM KHX3600C17D4/8GX 8GB DIMM DDR4 3600MT/s       | 1        | 1.45%   |
| Kingston RAM KF3000C15D4/8GX 8GB DIMM DDR4 3000MT/s        | 1        | 1.45%   |
| Kingston RAM CL16-16-16 D4-2400 4GB DIMM DDR4 2134MT/s     | 1        | 1.45%   |
| Kingston RAM 99U5474-015.A00LF 2048MB DIMM 1600MT/s        | 1        | 1.45%   |
| Kingston RAM 99U5402-048.A00LF 2048MB DIMM DDR3 1333MT/s   | 1        | 1.45%   |
| Kingston RAM 9905678-043.A00G 8192MB DIMM DDR4 2133MT/s    | 1        | 1.45%   |
| Kingston RAM 9905622-057.A00G 4GB DIMM DDR4 2133MT/s       | 1        | 1.45%   |
| Kingston RAM 9905595-005.A00LF 2GB DIMM DDR3 1600MT/s      | 1        | 1.45%   |
| Kingston RAM 9905584-015.A00LF 4096MB DIMM DDR3 1600MT/s   | 1        | 1.45%   |
| Hexon RAM Module 1024MB DIMM DDR 533MT/s                   | 1        | 1.45%   |
| Goodram RAM IR2400D464L17/16G 16384MB DIMM DDR4 2933MT/s   | 1        | 1.45%   |
| Goldkey RAM GKE400UD51208-2133AH 4096MB DIMM DDR4 2133MT/s | 1        | 1.45%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s        | 1        | 1.45%   |
| G.Skill RAM F3-17000CL11-4GBSR 4096MB DIMM DDR3 1600MT/s   | 1        | 1.45%   |
| Elpida RAM EBJ21UE8BDF0-DJ-F 2048MB DIMM DDR3 1333MT/s     | 1        | 1.45%   |
| Crucial RAM CT4G4DFS8213.C8FBD1 4GB DIMM DDR4 2667MT/s     | 1        | 1.45%   |
| Crucial RAM CT4G4DFS8213.C8FADP 4GB DIMM DDR4 2133MT/s     | 1        | 1.45%   |
| AVEXIR RAM M 4096MB DIMM DDR4 2133MT/s                     | 1        | 1.45%   |
| Apacer RAM D12.2356WS.001 8GB DIMM DDR4 2667MT/s           | 1        | 1.45%   |
| A-DATA RAM DDR4 3000 2OZ 4GB DIMM DDR4 3000MT/s            | 1        | 1.45%   |
| Unknown                                                    | 1        | 1.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 14       | 25.45%  |
| DDR3    | 14       | 25.45%  |
| Unknown | 11       | 20%     |
| DDR2    | 8        | 14.55%  |
| SDRAM   | 5        | 9.09%   |
| DDR     | 3        | 5.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 53       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 23       | 35.94%  |
| 4096  | 19       | 29.69%  |
| 8192  | 9        | 14.06%  |
| 1024  | 7        | 10.94%  |
| 16384 | 4        | 6.25%   |
| 512   | 2        | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 12       | 20.69%  |
| 1600    | 10       | 17.24%  |
| 800     | 7        | 12.07%  |
| 2133    | 6        | 10.34%  |
| 667     | 3        | 5.17%   |
| 333     | 3        | 5.17%   |
| Unknown | 3        | 5.17%   |
| 3000    | 2        | 3.45%   |
| 2667    | 2        | 3.45%   |
| 3600    | 1        | 1.72%   |
| 3500    | 1        | 1.72%   |
| 3200    | 1        | 1.72%   |
| 2933    | 1        | 1.72%   |
| 2800    | 1        | 1.72%   |
| 2666    | 1        | 1.72%   |
| 2400    | 1        | 1.72%   |
| 1400    | 1        | 1.72%   |
| 533     | 1        | 1.72%   |
| 400     | 1        | 1.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 2        | 50%     |
| Seiko Epson     | 1        | 25%     |
| Canon           | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed) | 1        | 25%     |
| HP LaserJet M14-M17                   | 1        | 25%     |
| HP LaserJet 1020                      | 1        | 25%     |
| Canon LaserShot LBP-1120 Printer      | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Canon CanoScan LiDE 700F | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech                    | 4        | 22.22%  |
| Microdia                    | 3        | 16.67%  |
| Z-Star Microelectronics     | 2        | 11.11%  |
| KYE Systems (Mouse Systems) | 2        | 11.11%  |
| Trust                       | 1        | 5.56%   |
| Samsung Electronics         | 1        | 5.56%   |
| Pixart Imaging              | 1        | 5.56%   |
| Microsoft                   | 1        | 5.56%   |
| Genesys Logic               | 1        | 5.56%   |
| Cubeternet                  | 1        | 5.56%   |
| Aveo Technology             | 1        | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Microdia Camera                           | 3        | 16.67%  |
| Z-Star Venus USB2.0 Camera                | 2        | 11.11%  |
| Logitech Webcam C270                      | 2        | 11.11%  |
| Trust Full HD Webcam                      | 1        | 5.56%   |
| Samsung Galaxy (PTP mode)                 | 1        | 5.56%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro      | 1        | 5.56%   |
| Microsoft LifeCam VX-700                  | 1        | 5.56%   |
| Logitech Webcam C170                      | 1        | 5.56%   |
| Logitech Webcam C110                      | 1        | 5.56%   |
| KYE Systems (Mouse Systems) FaceCam 1000X | 1        | 5.56%   |
| KYE Systems (Mouse Systems) eFace 2025    | 1        | 5.56%   |
| Genesys Logic U2 EE Cam                   | 1        | 5.56%   |
| Cubeternet USB2.0 Camera                  | 1        | 5.56%   |
| Aveo Camera                               | 1        | 5.56%   |

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
| 0     | 56       | 86.15%  |
| 1     | 9        | 13.85%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Graphics card | 8        | 88.89%  |
| Camera        | 1        | 11.11%  |

