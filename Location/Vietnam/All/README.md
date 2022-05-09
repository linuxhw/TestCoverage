Linux in Vietnam - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Vietnam.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Vietnam/Desktop/README.md) and [notebooks](/Location/Vietnam/Notebook/README.md).

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

Total: 449

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb2ffeb78a](https://linux-hardware.org/?probe=bb2ffeb78a) | May 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb73f6aa37](https://linux-hardware.org/?probe=bb73f6aa37) | May 04, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [51625474b7](https://linux-hardware.org/?probe=51625474b7) | Apr 30, 2022 |
| Foxconn       | H61MD/H61MD-V               | Desktop     | [25b52955ee](https://linux-hardware.org/?probe=25b52955ee) | Apr 29, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [4c5cbe705d](https://linux-hardware.org/?probe=4c5cbe705d) | Apr 27, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [2fcc2371d9](https://linux-hardware.org/?probe=2fcc2371d9) | Apr 25, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [287e344d0e](https://linux-hardware.org/?probe=287e344d0e) | Apr 16, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [7499dbd303](https://linux-hardware.org/?probe=7499dbd303) | Apr 15, 2022 |
| Foxconn       | H61MD/H61MD-V               | Desktop     | [7bb124e322](https://linux-hardware.org/?probe=7bb124e322) | Apr 06, 2022 |
| Dell          | System Vostro 3450          | Notebook    | [78750d86f5](https://linux-hardware.org/?probe=78750d86f5) | Mar 19, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [5dcc8e2cee](https://linux-hardware.org/?probe=5dcc8e2cee) | Mar 14, 2022 |
| ASUSTek       | ET2013I                     | All in one  | [b20d7593ce](https://linux-hardware.org/?probe=b20d7593ce) | Mar 09, 2022 |
| Dell          | Latitude E5540              | Notebook    | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [9cfd9c7142](https://linux-hardware.org/?probe=9cfd9c7142) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [a93699018b](https://linux-hardware.org/?probe=a93699018b) | Mar 02, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6b0f448d7b](https://linux-hardware.org/?probe=6b0f448d7b) | Feb 24, 2022 |
| Dell          | System XPS L702X            | Notebook    | [e1d4821ec2](https://linux-hardware.org/?probe=e1d4821ec2) | Feb 19, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [64f5921b5b](https://linux-hardware.org/?probe=64f5921b5b) | Feb 13, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [0619812e27](https://linux-hardware.org/?probe=0619812e27) | Feb 11, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [4834a3fe2e](https://linux-hardware.org/?probe=4834a3fe2e) | Feb 09, 2022 |
| Dell          | G3 3500                     | Notebook    | [9001ccacbc](https://linux-hardware.org/?probe=9001ccacbc) | Feb 09, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [2621c151ec](https://linux-hardware.org/?probe=2621c151ec) | Feb 01, 2022 |
| Dell          | Vostro 3578                 | Notebook    | [a95dfa8bc8](https://linux-hardware.org/?probe=a95dfa8bc8) | Jan 26, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | Notebook    | [872bc057f0](https://linux-hardware.org/?probe=872bc057f0) | Jan 10, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [5588a84fcf](https://linux-hardware.org/?probe=5588a84fcf) | Jan 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [d65648c445](https://linux-hardware.org/?probe=d65648c445) | Jan 09, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [3b97b65258](https://linux-hardware.org/?probe=3b97b65258) | Jan 08, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [be7876abf4](https://linux-hardware.org/?probe=be7876abf4) | Jan 05, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [65c9a87d51](https://linux-hardware.org/?probe=65c9a87d51) | Jan 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [48cfc7d185](https://linux-hardware.org/?probe=48cfc7d185) | Dec 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [b64750f465](https://linux-hardware.org/?probe=b64750f465) | Dec 26, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1524f751eb](https://linux-hardware.org/?probe=1524f751eb) | Dec 24, 2021 |
| ASUSTek       | P8H61-MX                    | Desktop     | [cee5f081e3](https://linux-hardware.org/?probe=cee5f081e3) | Dec 19, 2021 |
| ASUSTek       | P8H61-MX                    | Desktop     | [297d964b96](https://linux-hardware.org/?probe=297d964b96) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [717b9f1dd0](https://linux-hardware.org/?probe=717b9f1dd0) | Dec 16, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [bd72de2067](https://linux-hardware.org/?probe=bd72de2067) | Dec 12, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [412accf186](https://linux-hardware.org/?probe=412accf186) | Dec 09, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [21d85302a2](https://linux-hardware.org/?probe=21d85302a2) | Dec 05, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [70c63b2fb6](https://linux-hardware.org/?probe=70c63b2fb6) | Dec 02, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [c5d4bf5c62](https://linux-hardware.org/?probe=c5d4bf5c62) | Dec 02, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| Timi          | A35S                        | Notebook    | [dbb600147d](https://linux-hardware.org/?probe=dbb600147d) | Nov 30, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [fa62ac7a45](https://linux-hardware.org/?probe=fa62ac7a45) | Nov 23, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [10455f4980](https://linux-hardware.org/?probe=10455f4980) | Nov 23, 2021 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [17781cb457](https://linux-hardware.org/?probe=17781cb457) | Nov 20, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [f4a646d1f8](https://linux-hardware.org/?probe=f4a646d1f8) | Nov 18, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [5471ce2e2f](https://linux-hardware.org/?probe=5471ce2e2f) | Nov 16, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [96b971a0ed](https://linux-hardware.org/?probe=96b971a0ed) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a471ac5d59](https://linux-hardware.org/?probe=a471ac5d59) | Nov 07, 2021 |
| Dell          | Vostro 3478                 | Notebook    | [f88e5eec69](https://linux-hardware.org/?probe=f88e5eec69) | Nov 05, 2021 |
| Dell          | Vostro 3478                 | Notebook    | [8174188077](https://linux-hardware.org/?probe=8174188077) | Nov 05, 2021 |
| ASUSTek       | K45A                        | Notebook    | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | Notebook    | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Dell          | Precision 7510              | Notebook    | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [5158fb179d](https://linux-hardware.org/?probe=5158fb179d) | Nov 02, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [3296f4587d](https://linux-hardware.org/?probe=3296f4587d) | Nov 02, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [042607d7f1](https://linux-hardware.org/?probe=042607d7f1) | Oct 31, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [11527ae3f9](https://linux-hardware.org/?probe=11527ae3f9) | Oct 31, 2021 |
| Gigabyte      | G31MF-S2                    | Desktop     | [370ad865cf](https://linux-hardware.org/?probe=370ad865cf) | Oct 31, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [f316c0a82e](https://linux-hardware.org/?probe=f316c0a82e) | Oct 25, 2021 |
| Gigabyte      | G31MF-S2                    | Desktop     | [0758ac392b](https://linux-hardware.org/?probe=0758ac392b) | Oct 25, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| Gigabyte      | EP43T-S3L                   | Desktop     | [8a1adefcb3](https://linux-hardware.org/?probe=8a1adefcb3) | Oct 20, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [df8a870427](https://linux-hardware.org/?probe=df8a870427) | Oct 20, 2021 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [603ccdfb84](https://linux-hardware.org/?probe=603ccdfb84) | Oct 19, 2021 |
| Gigabyte      | G31MF-S2                    | Desktop     | [cd6c8d7087](https://linux-hardware.org/?probe=cd6c8d7087) | Oct 19, 2021 |
| Gigabyte      | G31MF-S2                    | Desktop     | [7459a9ed47](https://linux-hardware.org/?probe=7459a9ed47) | Oct 18, 2021 |
| Dell          | Precision 7510              | Notebook    | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| HP            | Notebook                    | Notebook    | [6ac2c09585](https://linux-hardware.org/?probe=6ac2c09585) | Oct 09, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [c9fd6887d4](https://linux-hardware.org/?probe=c9fd6887d4) | Oct 06, 2021 |
| Acer          | Predator PH315-51           | Notebook    | [fb9a605481](https://linux-hardware.org/?probe=fb9a605481) | Oct 05, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [b1fb3d4e88](https://linux-hardware.org/?probe=b1fb3d4e88) | Oct 04, 2021 |
| Dell          | Latitude E7440              | Notebook    | [fe4153e816](https://linux-hardware.org/?probe=fe4153e816) | Oct 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8b3b2655bb](https://linux-hardware.org/?probe=8b3b2655bb) | Oct 03, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [101371762b](https://linux-hardware.org/?probe=101371762b) | Oct 01, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [52fe5aa259](https://linux-hardware.org/?probe=52fe5aa259) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [d8cde7951e](https://linux-hardware.org/?probe=d8cde7951e) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [db7c214214](https://linux-hardware.org/?probe=db7c214214) | Sep 28, 2021 |
| Dell          | Latitude 3520               | Notebook    | [2fb41f5f08](https://linux-hardware.org/?probe=2fb41f5f08) | Sep 24, 2021 |
| HP            | 15                          | Notebook    | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Sony          | SVE14A15FGW                 | Notebook    | [f1049f7db1](https://linux-hardware.org/?probe=f1049f7db1) | Sep 21, 2021 |
| Panasonic     | CFSX4-1                     | Notebook    | [d474bc1b91](https://linux-hardware.org/?probe=d474bc1b91) | Sep 03, 2021 |
| Panasonic     | CFSX4-1                     | Notebook    | [bee71431a0](https://linux-hardware.org/?probe=bee71431a0) | Sep 03, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | Notebook    | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | GF62 7RD                    | Notebook    | [5a35b145a9](https://linux-hardware.org/?probe=5a35b145a9) | Aug 19, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [df3d4bfff1](https://linux-hardware.org/?probe=df3d4bfff1) | Aug 18, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [dde539e1b1](https://linux-hardware.org/?probe=dde539e1b1) | Aug 18, 2021 |
| HP            | ProBook 4430s               | Notebook    | [0235e3c344](https://linux-hardware.org/?probe=0235e3c344) | Aug 18, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [f77c5c4c48](https://linux-hardware.org/?probe=f77c5c4c48) | Aug 10, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [886b00678b](https://linux-hardware.org/?probe=886b00678b) | Aug 09, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [57bf64ac4b](https://linux-hardware.org/?probe=57bf64ac4b) | Aug 09, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [955889f7c8](https://linux-hardware.org/?probe=955889f7c8) | Aug 08, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [76e0c19c46](https://linux-hardware.org/?probe=76e0c19c46) | Aug 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ce35fd4a1a](https://linux-hardware.org/?probe=ce35fd4a1a) | Jul 23, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [94aa730eda](https://linux-hardware.org/?probe=94aa730eda) | Jul 23, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [10c0149671](https://linux-hardware.org/?probe=10c0149671) | Jul 17, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [aa5fadb321](https://linux-hardware.org/?probe=aa5fadb321) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [dcc22fa273](https://linux-hardware.org/?probe=dcc22fa273) | Jul 13, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | Notebook    | [e6cb486cfd](https://linux-hardware.org/?probe=e6cb486cfd) | Jul 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | Notebook    | [58ad5d25b9](https://linux-hardware.org/?probe=58ad5d25b9) | Jul 07, 2021 |
| Dell          | Latitude E6410              | Notebook    | [9a4002aa3d](https://linux-hardware.org/?probe=9a4002aa3d) | Jul 07, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [894db66628](https://linux-hardware.org/?probe=894db66628) | Jul 05, 2021 |
| HP            | Compaq 510                  | Notebook    | [cd27b78fea](https://linux-hardware.org/?probe=cd27b78fea) | Jul 04, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [bec8a61ff4](https://linux-hardware.org/?probe=bec8a61ff4) | Jul 03, 2021 |
| Gigabyte      | P110-D3-CF                  | Desktop     | [37aab1ae76](https://linux-hardware.org/?probe=37aab1ae76) | Jun 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [3fb422fa2e](https://linux-hardware.org/?probe=3fb422fa2e) | Jun 27, 2021 |
| Colorful T... | C.A68M-BTC YV14             | Desktop     | [9b6c7d9e82](https://linux-hardware.org/?probe=9b6c7d9e82) | Jun 23, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [85b912e99c](https://linux-hardware.org/?probe=85b912e99c) | Jun 22, 2021 |
| Huanan        | X79 249PC V2.1              | Desktop     | [b6fd95e48e](https://linux-hardware.org/?probe=b6fd95e48e) | Jun 15, 2021 |
| Acer          | Aspire 4315                 | Notebook    | [ac56c24f68](https://linux-hardware.org/?probe=ac56c24f68) | Jun 15, 2021 |
| Acer          | Aspire 4315                 | Notebook    | [4527ee70c7](https://linux-hardware.org/?probe=4527ee70c7) | Jun 13, 2021 |
| MSI           | B365M PRO-VH                | Desktop     | [ea30bb632e](https://linux-hardware.org/?probe=ea30bb632e) | Jun 10, 2021 |
| Lenovo        | ThinkPad L520 5015A76       | Notebook    | [84b62cbde9](https://linux-hardware.org/?probe=84b62cbde9) | Jun 10, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [851f20cb74](https://linux-hardware.org/?probe=851f20cb74) | Jun 09, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [428cb5bb99](https://linux-hardware.org/?probe=428cb5bb99) | Jun 05, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [de3596a9a3](https://linux-hardware.org/?probe=de3596a9a3) | Jun 05, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [38acf36fce](https://linux-hardware.org/?probe=38acf36fce) | Jun 05, 2021 |
| Dell          | Latitude 7420               | Notebook    | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [4401c591ee](https://linux-hardware.org/?probe=4401c591ee) | Jun 01, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [f1d33c68f6](https://linux-hardware.org/?probe=f1d33c68f6) | Jun 01, 2021 |
| Lenovo        | V130-14IKB 81HQ             | Notebook    | [8995f3c1ad](https://linux-hardware.org/?probe=8995f3c1ad) | Jun 01, 2021 |
| Lenovo        | Z40-70 20366                | Notebook    | [b1b8196f26](https://linux-hardware.org/?probe=b1b8196f26) | May 31, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [35c74e640b](https://linux-hardware.org/?probe=35c74e640b) | May 31, 2021 |
| Lenovo        | ThinkPad X250 20CLCTO1WW    | Notebook    | [a5d677976f](https://linux-hardware.org/?probe=a5d677976f) | May 29, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [b70a62225d](https://linux-hardware.org/?probe=b70a62225d) | May 22, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [ddfb904938](https://linux-hardware.org/?probe=ddfb904938) | May 19, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [35324d2388](https://linux-hardware.org/?probe=35324d2388) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1abefab68f](https://linux-hardware.org/?probe=1abefab68f) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c4ea8f1bab](https://linux-hardware.org/?probe=c4ea8f1bab) | May 19, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [2ce7106efb](https://linux-hardware.org/?probe=2ce7106efb) | May 15, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [b8108b310a](https://linux-hardware.org/?probe=b8108b310a) | May 13, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [c596247722](https://linux-hardware.org/?probe=c596247722) | May 13, 2021 |
| Dell          | Inspiron 3443               | Notebook    | [c84fc5c646](https://linux-hardware.org/?probe=c84fc5c646) | May 12, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [ef73590627](https://linux-hardware.org/?probe=ef73590627) | May 09, 2021 |
| ASUSTek       | PRIME H110M-P               | Desktop     | [63effde8c3](https://linux-hardware.org/?probe=63effde8c3) | May 08, 2021 |
| ASUSTek       | PRIME H110M-P               | Desktop     | [99ac06d5e2](https://linux-hardware.org/?probe=99ac06d5e2) | May 08, 2021 |
| Acer          | Predator G9-793             | Notebook    | [90b04b667a](https://linux-hardware.org/?probe=90b04b667a) | May 03, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [2fabbbebb9](https://linux-hardware.org/?probe=2fabbbebb9) | Apr 29, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [23cc5c25c3](https://linux-hardware.org/?probe=23cc5c25c3) | Apr 29, 2021 |
| HP            | Pavilion 15                 | Notebook    | [1ddb966308](https://linux-hardware.org/?probe=1ddb966308) | Apr 28, 2021 |
| Sony          | VPCCW13FX                   | Notebook    | [82e9a1f82a](https://linux-hardware.org/?probe=82e9a1f82a) | Apr 25, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [599315872a](https://linux-hardware.org/?probe=599315872a) | Apr 24, 2021 |
| Dell          | Precision 3520              | Notebook    | [fc2d295c0e](https://linux-hardware.org/?probe=fc2d295c0e) | Apr 24, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [76defcf2f7](https://linux-hardware.org/?probe=76defcf2f7) | Apr 22, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [c941a697c2](https://linux-hardware.org/?probe=c941a697c2) | Apr 22, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e55472cf5f](https://linux-hardware.org/?probe=e55472cf5f) | Apr 18, 2021 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [007ae7cca0](https://linux-hardware.org/?probe=007ae7cca0) | Apr 18, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [07736896f9](https://linux-hardware.org/?probe=07736896f9) | Apr 18, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [abf17f0c92](https://linux-hardware.org/?probe=abf17f0c92) | Apr 17, 2021 |
| HP            | Unknown                     | Notebook    | [2465109965](https://linux-hardware.org/?probe=2465109965) | Apr 13, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [698d0ca8cc](https://linux-hardware.org/?probe=698d0ca8cc) | Apr 08, 2021 |
| Dell          | G3 3579                     | Notebook    | [d5d191947e](https://linux-hardware.org/?probe=d5d191947e) | Apr 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [07fd740efe](https://linux-hardware.org/?probe=07fd740efe) | Apr 06, 2021 |
| Chuwi         | LapBook SE                  | Notebook    | [0e9a03cc48](https://linux-hardware.org/?probe=0e9a03cc48) | Apr 06, 2021 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [d20d2b755f](https://linux-hardware.org/?probe=d20d2b755f) | Apr 04, 2021 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [cdfb323202](https://linux-hardware.org/?probe=cdfb323202) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [e8c59a070a](https://linux-hardware.org/?probe=e8c59a070a) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [b9324b1b4d](https://linux-hardware.org/?probe=b9324b1b4d) | Apr 04, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [0984402bad](https://linux-hardware.org/?probe=0984402bad) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [eba80415c0](https://linux-hardware.org/?probe=eba80415c0) | Apr 03, 2021 |
| MSI           | GS40 6QE Phantom            | Notebook    | [adbf080ab7](https://linux-hardware.org/?probe=adbf080ab7) | Mar 27, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [12fd74ecdc](https://linux-hardware.org/?probe=12fd74ecdc) | Mar 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [43f33bc8e0](https://linux-hardware.org/?probe=43f33bc8e0) | Mar 21, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [c377f57ac8](https://linux-hardware.org/?probe=c377f57ac8) | Mar 21, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [cac842cdbb](https://linux-hardware.org/?probe=cac842cdbb) | Mar 20, 2021 |
| Dell          | 04Y8V0 A02                  | Desktop     | [241289046a](https://linux-hardware.org/?probe=241289046a) | Mar 16, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [66ce284547](https://linux-hardware.org/?probe=66ce284547) | Mar 14, 2021 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [5bada8b921](https://linux-hardware.org/?probe=5bada8b921) | Mar 13, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [a8e1128b26](https://linux-hardware.org/?probe=a8e1128b26) | Mar 13, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [d56654c11c](https://linux-hardware.org/?probe=d56654c11c) | Mar 12, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [d1bd158872](https://linux-hardware.org/?probe=d1bd158872) | Mar 10, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [2ed429a812](https://linux-hardware.org/?probe=2ed429a812) | Mar 09, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [f85fc12bff](https://linux-hardware.org/?probe=f85fc12bff) | Mar 09, 2021 |
| ASUSTek       | X202E                       | Notebook    | [cc089d4ddb](https://linux-hardware.org/?probe=cc089d4ddb) | Mar 08, 2021 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [3acc3e5a05](https://linux-hardware.org/?probe=3acc3e5a05) | Mar 06, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [647b5fbb43](https://linux-hardware.org/?probe=647b5fbb43) | Mar 06, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [9e8527b842](https://linux-hardware.org/?probe=9e8527b842) | Mar 05, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [96fd52e1f2](https://linux-hardware.org/?probe=96fd52e1f2) | Mar 02, 2021 |
| Acer          | Aspire A515-53              | Notebook    | [637c3ebf75](https://linux-hardware.org/?probe=637c3ebf75) | Feb 28, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [05ad71d3d8](https://linux-hardware.org/?probe=05ad71d3d8) | Feb 24, 2021 |
| Gateway       | LT40                        | Notebook    | [90ae93da93](https://linux-hardware.org/?probe=90ae93da93) | Feb 24, 2021 |
| Gateway       | LT40                        | Notebook    | [98f2ce8032](https://linux-hardware.org/?probe=98f2ce8032) | Feb 24, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [4a441fe0c9](https://linux-hardware.org/?probe=4a441fe0c9) | Feb 21, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [bfb791c2fb](https://linux-hardware.org/?probe=bfb791c2fb) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | Notebook    | [87b755412e](https://linux-hardware.org/?probe=87b755412e) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | Notebook    | [8d0bcb0740](https://linux-hardware.org/?probe=8d0bcb0740) | Feb 19, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [bb980a20ea](https://linux-hardware.org/?probe=bb980a20ea) | Feb 18, 2021 |
| ASUSTek       | EB1036                      | Desktop     | [d77c773bc7](https://linux-hardware.org/?probe=d77c773bc7) | Feb 17, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [a79c837a9b](https://linux-hardware.org/?probe=a79c837a9b) | Feb 16, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5cb0f77327](https://linux-hardware.org/?probe=5cb0f77327) | Feb 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [0c70deaac1](https://linux-hardware.org/?probe=0c70deaac1) | Feb 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [0441228ba8](https://linux-hardware.org/?probe=0441228ba8) | Feb 07, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [abd5fe70e2](https://linux-hardware.org/?probe=abd5fe70e2) | Feb 06, 2021 |
| Dell          | Latitude E7450              | Notebook    | [94b0fc1fc8](https://linux-hardware.org/?probe=94b0fc1fc8) | Feb 06, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [2a68435a2b](https://linux-hardware.org/?probe=2a68435a2b) | Feb 06, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [24d2567059](https://linux-hardware.org/?probe=24d2567059) | Feb 02, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [b2b00b4390](https://linux-hardware.org/?probe=b2b00b4390) | Jan 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [d7f2ee4a81](https://linux-hardware.org/?probe=d7f2ee4a81) | Jan 25, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [568c3e9797](https://linux-hardware.org/?probe=568c3e9797) | Jan 21, 2021 |
| Shenzhen A... | X96 Max                     | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| Toshiba       | Satellite L840              | Notebook    | [82f5ebd486](https://linux-hardware.org/?probe=82f5ebd486) | Jan 18, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [e9acf54209](https://linux-hardware.org/?probe=e9acf54209) | Jan 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [d462b4ca25](https://linux-hardware.org/?probe=d462b4ca25) | Jan 12, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [8ae2ef5b3b](https://linux-hardware.org/?probe=8ae2ef5b3b) | Jan 07, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [bfc25ae638](https://linux-hardware.org/?probe=bfc25ae638) | Jan 06, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [4a11009c6f](https://linux-hardware.org/?probe=4a11009c6f) | Jan 06, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [cf3d073aae](https://linux-hardware.org/?probe=cf3d073aae) | Jan 06, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [8b549321e4](https://linux-hardware.org/?probe=8b549321e4) | Dec 31, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [540115f336](https://linux-hardware.org/?probe=540115f336) | Dec 28, 2020 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [2e581b986a](https://linux-hardware.org/?probe=2e581b986a) | Dec 28, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [cd0b939f13](https://linux-hardware.org/?probe=cd0b939f13) | Dec 27, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [6eaddc8157](https://linux-hardware.org/?probe=6eaddc8157) | Dec 21, 2020 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [fb16534a29](https://linux-hardware.org/?probe=fb16534a29) | Dec 17, 2020 |
| Sony          | VGN-NW270F                  | Notebook    | [d8989e5c40](https://linux-hardware.org/?probe=d8989e5c40) | Dec 16, 2020 |
| Apple         | MacBookPro11,4              | Notebook    | [e880800d6f](https://linux-hardware.org/?probe=e880800d6f) | Dec 13, 2020 |
| Dell          | G3 3579                     | Notebook    | [99724b8bd6](https://linux-hardware.org/?probe=99724b8bd6) | Dec 12, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [fa10ea29e8](https://linux-hardware.org/?probe=fa10ea29e8) | Dec 11, 2020 |
| HP            | 158A                        | Desktop     | [9c309002d1](https://linux-hardware.org/?probe=9c309002d1) | Dec 10, 2020 |
| Acer          | Predator PH315-51           | Notebook    | [c9539f5932](https://linux-hardware.org/?probe=c9539f5932) | Dec 09, 2020 |
| HP            | 2B2C                        | Desktop     | [ffd83f6d60](https://linux-hardware.org/?probe=ffd83f6d60) | Dec 08, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [4838a6e14f](https://linux-hardware.org/?probe=4838a6e14f) | Dec 05, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [ea2bf23a76](https://linux-hardware.org/?probe=ea2bf23a76) | Dec 03, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [2a4ce919e5](https://linux-hardware.org/?probe=2a4ce919e5) | Dec 03, 2020 |
| Acer          | Aspire V5-431P              | Notebook    | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| HP            | 158A                        | Desktop     | [eaab601c40](https://linux-hardware.org/?probe=eaab601c40) | Dec 02, 2020 |
| HP            | 158A                        | Desktop     | [64320f7764](https://linux-hardware.org/?probe=64320f7764) | Dec 02, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [4e39668b71](https://linux-hardware.org/?probe=4e39668b71) | Dec 02, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [dbff453f7e](https://linux-hardware.org/?probe=dbff453f7e) | Dec 02, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [80ca88b62a](https://linux-hardware.org/?probe=80ca88b62a) | Nov 30, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [80f3a03fc2](https://linux-hardware.org/?probe=80f3a03fc2) | Nov 22, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [471b375bb8](https://linux-hardware.org/?probe=471b375bb8) | Nov 22, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [4019b6c1ff](https://linux-hardware.org/?probe=4019b6c1ff) | Nov 16, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [7fb140838e](https://linux-hardware.org/?probe=7fb140838e) | Nov 12, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [a85397c97e](https://linux-hardware.org/?probe=a85397c97e) | Nov 11, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [ac263c6ad6](https://linux-hardware.org/?probe=ac263c6ad6) | Nov 10, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [0fea3e1fc2](https://linux-hardware.org/?probe=0fea3e1fc2) | Nov 09, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [3b2d445938](https://linux-hardware.org/?probe=3b2d445938) | Nov 07, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [ee5a941e33](https://linux-hardware.org/?probe=ee5a941e33) | Nov 06, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [f2a745943a](https://linux-hardware.org/?probe=f2a745943a) | Nov 04, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [bfa10fd887](https://linux-hardware.org/?probe=bfa10fd887) | Nov 04, 2020 |
| Dell          | Latitude 7490               | Notebook    | [8f0ec25c05](https://linux-hardware.org/?probe=8f0ec25c05) | Oct 29, 2020 |
| Dell          | Latitude E6530              | Notebook    | [1a16aeb4dd](https://linux-hardware.org/?probe=1a16aeb4dd) | Oct 28, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [318f172f36](https://linux-hardware.org/?probe=318f172f36) | Oct 27, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [070dae158a](https://linux-hardware.org/?probe=070dae158a) | Oct 24, 2020 |
| Toshiba       | Satellite L840              | Notebook    | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | Notebook    | [fa061b6d7e](https://linux-hardware.org/?probe=fa061b6d7e) | Oct 13, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | Notebook    | [dc9b667685](https://linux-hardware.org/?probe=dc9b667685) | Oct 13, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [9bf6f0ba43](https://linux-hardware.org/?probe=9bf6f0ba43) | Oct 09, 2020 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [bcc1019568](https://linux-hardware.org/?probe=bcc1019568) | Oct 07, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [125dd87b84](https://linux-hardware.org/?probe=125dd87b84) | Oct 03, 2020 |
| Dell          | 0215PR A02                  | Desktop     | [a37475889b](https://linux-hardware.org/?probe=a37475889b) | Oct 03, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Lenovo        | ThinkPad T420 4236C95       | Notebook    | [8cf52f76c0](https://linux-hardware.org/?probe=8cf52f76c0) | Oct 02, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [6753d2054d](https://linux-hardware.org/?probe=6753d2054d) | Oct 01, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [6c568247ff](https://linux-hardware.org/?probe=6c568247ff) | Oct 01, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [15bcec7549](https://linux-hardware.org/?probe=15bcec7549) | Sep 28, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [5ff5b89d5e](https://linux-hardware.org/?probe=5ff5b89d5e) | Sep 22, 2020 |
| Koloe         | X58                         | Desktop     | [81d474ab62](https://linux-hardware.org/?probe=81d474ab62) | Sep 20, 2020 |
| ASUSTek       | Z10PE-D8 WS                 | Desktop     | [55e8990643](https://linux-hardware.org/?probe=55e8990643) | Sep 17, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [3a8b43fc2f](https://linux-hardware.org/?probe=3a8b43fc2f) | Sep 16, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [8adea7b2b3](https://linux-hardware.org/?probe=8adea7b2b3) | Sep 15, 2020 |
| Dell          | Vostro 1450                 | Notebook    | [444ddb1aa9](https://linux-hardware.org/?probe=444ddb1aa9) | Sep 15, 2020 |
| Dell          | Precision 3520              | Notebook    | [e8f520c4fa](https://linux-hardware.org/?probe=e8f520c4fa) | Sep 09, 2020 |
| MASSCOM VI... | L133                        | Notebook    | [b356f018b2](https://linux-hardware.org/?probe=b356f018b2) | Sep 09, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [11a8a7e166](https://linux-hardware.org/?probe=11a8a7e166) | Sep 07, 2020 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [42cdde5346](https://linux-hardware.org/?probe=42cdde5346) | Sep 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [6b4eeecb26](https://linux-hardware.org/?probe=6b4eeecb26) | Sep 04, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [190c1e6486](https://linux-hardware.org/?probe=190c1e6486) | Aug 31, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [a9ced30680](https://linux-hardware.org/?probe=a9ced30680) | Aug 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [17c4f51c75](https://linux-hardware.org/?probe=17c4f51c75) | Aug 29, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [08d8dc8d6e](https://linux-hardware.org/?probe=08d8dc8d6e) | Aug 28, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [889530c9b1](https://linux-hardware.org/?probe=889530c9b1) | Aug 28, 2020 |
| Lenovo        | ThinkPad L430 2465CTO       | Notebook    | [e5371d9b58](https://linux-hardware.org/?probe=e5371d9b58) | Aug 26, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [01f13cc1c7](https://linux-hardware.org/?probe=01f13cc1c7) | Aug 25, 2020 |
| Dell          | 0200DY A02                  | Desktop     | [dc862d439b](https://linux-hardware.org/?probe=dc862d439b) | Aug 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4ff005e6d9](https://linux-hardware.org/?probe=4ff005e6d9) | Aug 21, 2020 |
| Lenovo        | ThinkPad T580 20L9001MUS    | Notebook    | [92c940e8c2](https://linux-hardware.org/?probe=92c940e8c2) | Aug 21, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [e7702e2ce8](https://linux-hardware.org/?probe=e7702e2ce8) | Aug 20, 2020 |
| Dell          | G3 3579                     | Notebook    | [8e341b94ae](https://linux-hardware.org/?probe=8e341b94ae) | Aug 18, 2020 |
| Dell          | G3 3579                     | Notebook    | [9a1078144d](https://linux-hardware.org/?probe=9a1078144d) | Aug 18, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [d9fe6d88cd](https://linux-hardware.org/?probe=d9fe6d88cd) | Aug 14, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [52f08d8242](https://linux-hardware.org/?probe=52f08d8242) | Aug 12, 2020 |
| Lenovo        | ThinkPad E480 20KN005GVA    | Notebook    | [f77c6858ad](https://linux-hardware.org/?probe=f77c6858ad) | Jul 24, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [a58d188243](https://linux-hardware.org/?probe=a58d188243) | Jul 19, 2020 |
| HP            | 2B2C                        | Desktop     | [ed031034e8](https://linux-hardware.org/?probe=ed031034e8) | Jul 18, 2020 |
| HP            | 2B2C                        | Desktop     | [dd85e7a5e1](https://linux-hardware.org/?probe=dd85e7a5e1) | Jul 18, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [ab4eff4438](https://linux-hardware.org/?probe=ab4eff4438) | Jul 16, 2020 |
| Dell          | Latitude E5470              | Notebook    | [777b8955c3](https://linux-hardware.org/?probe=777b8955c3) | Jul 12, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [d0dff5e971](https://linux-hardware.org/?probe=d0dff5e971) | Jul 09, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [7300218f1f](https://linux-hardware.org/?probe=7300218f1f) | Jul 09, 2020 |
| Dell          | Vostro 3590                 | Notebook    | [4f8fb0d621](https://linux-hardware.org/?probe=4f8fb0d621) | Jul 09, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [dba2423eba](https://linux-hardware.org/?probe=dba2423eba) | Jul 08, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [601726ae15](https://linux-hardware.org/?probe=601726ae15) | Jul 01, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [4e1f771d23](https://linux-hardware.org/?probe=4e1f771d23) | Jun 29, 2020 |
| Dell          | Vostro 3460                 | Notebook    | [2338ae0fde](https://linux-hardware.org/?probe=2338ae0fde) | Jun 28, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [a3b890c7f1](https://linux-hardware.org/?probe=a3b890c7f1) | Jun 26, 2020 |
| ASUSTek       | A68HM-K                     | Desktop     | [7fc608d8c2](https://linux-hardware.org/?probe=7fc608d8c2) | Jun 21, 2020 |
| HP            | ZBook 17 G2                 | Notebook    | [467e55d0db](https://linux-hardware.org/?probe=467e55d0db) | Jun 20, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [f223bc5b5e](https://linux-hardware.org/?probe=f223bc5b5e) | Jun 19, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [27d008955f](https://linux-hardware.org/?probe=27d008955f) | Jun 19, 2020 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [ce4a203e0f](https://linux-hardware.org/?probe=ce4a203e0f) | Jun 19, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [652d0e5648](https://linux-hardware.org/?probe=652d0e5648) | Jun 18, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [3b5f86f3d4](https://linux-hardware.org/?probe=3b5f86f3d4) | Jun 18, 2020 |
| Dell          | Inspiron 5548               | Notebook    | [60a6140ac2](https://linux-hardware.org/?probe=60a6140ac2) | Jun 14, 2020 |
| Dell          | Inspiron 5548               | Notebook    | [ac70aa8a8d](https://linux-hardware.org/?probe=ac70aa8a8d) | Jun 14, 2020 |
| Dell          | Vostro 3590                 | Notebook    | [faca1b4063](https://linux-hardware.org/?probe=faca1b4063) | Jun 14, 2020 |
| HP            | ZBook Studio G3             | Notebook    | [91a0ff7707](https://linux-hardware.org/?probe=91a0ff7707) | Jun 10, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [7b0270fb87](https://linux-hardware.org/?probe=7b0270fb87) | Jun 04, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [4f742a1225](https://linux-hardware.org/?probe=4f742a1225) | Jun 02, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [9cda4be295](https://linux-hardware.org/?probe=9cda4be295) | Jun 02, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [a00a01fc8a](https://linux-hardware.org/?probe=a00a01fc8a) | Jun 01, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [d20fb28927](https://linux-hardware.org/?probe=d20fb28927) | May 30, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [d32590fed2](https://linux-hardware.org/?probe=d32590fed2) | May 30, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [be05348be2](https://linux-hardware.org/?probe=be05348be2) | May 29, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [945550a204](https://linux-hardware.org/?probe=945550a204) | May 29, 2020 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [b0f5fc9b10](https://linux-hardware.org/?probe=b0f5fc9b10) | May 26, 2020 |
| Dell          | Latitude E7440              | Notebook    | [26b5908778](https://linux-hardware.org/?probe=26b5908778) | May 20, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [849bf107d8](https://linux-hardware.org/?probe=849bf107d8) | May 18, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [5a938c4186](https://linux-hardware.org/?probe=5a938c4186) | May 17, 2020 |
| Dell          | Inspiron 7520               | Notebook    | [f400730782](https://linux-hardware.org/?probe=f400730782) | May 15, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [ffb18f222a](https://linux-hardware.org/?probe=ffb18f222a) | May 15, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [272430b55d](https://linux-hardware.org/?probe=272430b55d) | May 12, 2020 |
| Toshiba       | PORTEGE T110                | Notebook    | [8c8ec8db54](https://linux-hardware.org/?probe=8c8ec8db54) | May 10, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [7e7b980d96](https://linux-hardware.org/?probe=7e7b980d96) | May 09, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [a4ec49073e](https://linux-hardware.org/?probe=a4ec49073e) | May 02, 2020 |
| ASRock        | AOD790GX/128M               | Desktop     | [8ba6b55d11](https://linux-hardware.org/?probe=8ba6b55d11) | Apr 28, 2020 |
| Dell          | Vostro 14-5480              | Notebook    | [3edae78003](https://linux-hardware.org/?probe=3edae78003) | Apr 28, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [8e17ac8b14](https://linux-hardware.org/?probe=8e17ac8b14) | Apr 27, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1aa80c5f94](https://linux-hardware.org/?probe=1aa80c5f94) | Apr 26, 2020 |
| Acer          | Swift SF315-52              | Notebook    | [a41dc8c7b3](https://linux-hardware.org/?probe=a41dc8c7b3) | Apr 24, 2020 |
| Dell          | Vostro 3478                 | Notebook    | [65a16b0f00](https://linux-hardware.org/?probe=65a16b0f00) | Apr 22, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [985dd25740](https://linux-hardware.org/?probe=985dd25740) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [8b6c1d10a4](https://linux-hardware.org/?probe=8b6c1d10a4) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [8680dc53ed](https://linux-hardware.org/?probe=8680dc53ed) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [9cb006b675](https://linux-hardware.org/?probe=9cb006b675) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [e670bd004a](https://linux-hardware.org/?probe=e670bd004a) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [ed1d4fbd62](https://linux-hardware.org/?probe=ed1d4fbd62) | Apr 19, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [c51238bbe1](https://linux-hardware.org/?probe=c51238bbe1) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [e421f3a586](https://linux-hardware.org/?probe=e421f3a586) | Apr 10, 2020 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [45b9a81a90](https://linux-hardware.org/?probe=45b9a81a90) | Apr 08, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Dell          | Precision 5530              | Notebook    | [805db6810c](https://linux-hardware.org/?probe=805db6810c) | Mar 31, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [6093f50362](https://linux-hardware.org/?probe=6093f50362) | Mar 30, 2020 |
| Sony          | VPCEB42EG                   | Notebook    | [d2586cdd17](https://linux-hardware.org/?probe=d2586cdd17) | Mar 25, 2020 |
| Sony          | VPCEB42EG                   | Notebook    | [424402e2b1](https://linux-hardware.org/?probe=424402e2b1) | Mar 25, 2020 |
| ASUSTek       | GL553VE                     | Notebook    | [1238bea224](https://linux-hardware.org/?probe=1238bea224) | Mar 21, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [72a39494c1](https://linux-hardware.org/?probe=72a39494c1) | Mar 18, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [7dddec34d1](https://linux-hardware.org/?probe=7dddec34d1) | Mar 02, 2020 |
| Intel         | S5520HC E26045-457          | Server      | [49d0f0d68c](https://linux-hardware.org/?probe=49d0f0d68c) | Mar 01, 2020 |
| Intel         | S5520HC E26045-457          | Server      | [359532fc26](https://linux-hardware.org/?probe=359532fc26) | Mar 01, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [b87f570104](https://linux-hardware.org/?probe=b87f570104) | Feb 29, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [f1e468eec0](https://linux-hardware.org/?probe=f1e468eec0) | Feb 29, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [3740504388](https://linux-hardware.org/?probe=3740504388) | Feb 28, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [284484a6b6](https://linux-hardware.org/?probe=284484a6b6) | Feb 15, 2020 |
| Koompi        | Unknown                     | Notebook    | [46e5e1375d](https://linux-hardware.org/?probe=46e5e1375d) | Feb 12, 2020 |
| Shuttle       | FS81                        | Desktop     | [93c00d64e6](https://linux-hardware.org/?probe=93c00d64e6) | Feb 07, 2020 |
| MSI           | GF63 8RD                    | Notebook    | [6eae1d7ba9](https://linux-hardware.org/?probe=6eae1d7ba9) | Feb 01, 2020 |
| MSI           | GF63 8RD                    | Notebook    | [b7087b6ba5](https://linux-hardware.org/?probe=b7087b6ba5) | Jan 31, 2020 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [e3cbb2da5f](https://linux-hardware.org/?probe=e3cbb2da5f) | Jan 24, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [46c0e495c1](https://linux-hardware.org/?probe=46c0e495c1) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b2bc63b818](https://linux-hardware.org/?probe=b2bc63b818) | Jan 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4ea2e33944](https://linux-hardware.org/?probe=4ea2e33944) | Jan 07, 2020 |
| AMI           | Cherry Trail FFD            | Notebook    | [c62d47b2a1](https://linux-hardware.org/?probe=c62d47b2a1) | Dec 22, 2019 |
| ASUSTek       | P9X79 WS                    | Desktop     | [7a8ccfd558](https://linux-hardware.org/?probe=7a8ccfd558) | Nov 21, 2019 |
| Jumper        | EZpad                       | Notebook    | [6dfb4e2274](https://linux-hardware.org/?probe=6dfb4e2274) | Oct 31, 2019 |
| Dell          | Vostro 3450                 | Notebook    | [2017fd9a25](https://linux-hardware.org/?probe=2017fd9a25) | Oct 29, 2019 |
| Dell          | Vostro 3450                 | Notebook    | [d9565f1b97](https://linux-hardware.org/?probe=d9565f1b97) | Oct 18, 2019 |
| Dell          | Vostro 3450                 | Notebook    | [a49293e78b](https://linux-hardware.org/?probe=a49293e78b) | Oct 18, 2019 |
| Dell          | Vostro 3450                 | Notebook    | [82abb6f331](https://linux-hardware.org/?probe=82abb6f331) | Oct 18, 2019 |
| Dell          | Vostro 3450                 | Notebook    | [90391fe6fe](https://linux-hardware.org/?probe=90391fe6fe) | Sep 19, 2019 |
| Samsung       | NC208/NC108                 | Notebook    | [a99fe6de20](https://linux-hardware.org/?probe=a99fe6de20) | Sep 16, 2019 |
| Dell          | 0CU409                      | Desktop     | [a5aabfdba4](https://linux-hardware.org/?probe=a5aabfdba4) | Sep 09, 2019 |
| Dell          | 0CU409                      | Desktop     | [a23804877f](https://linux-hardware.org/?probe=a23804877f) | Sep 08, 2019 |
| Dell          | 0CU409                      | Desktop     | [8efe3a4b92](https://linux-hardware.org/?probe=8efe3a4b92) | Sep 08, 2019 |
| Dell          | Inspiron 3421               | Notebook    | [46a7955491](https://linux-hardware.org/?probe=46a7955491) | Sep 04, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | Notebook    | [35dfb93d51](https://linux-hardware.org/?probe=35dfb93d51) | Sep 02, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | Notebook    | [635d10113c](https://linux-hardware.org/?probe=635d10113c) | Sep 02, 2019 |
| Gigabyte      | B360 M AORUS PRO-CF         | Desktop     | [657b0b4115](https://linux-hardware.org/?probe=657b0b4115) | Aug 28, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [f9ed638fe3](https://linux-hardware.org/?probe=f9ed638fe3) | Aug 27, 2019 |
| Dell          | Inspiron N4110              | Notebook    | [1923c8603b](https://linux-hardware.org/?probe=1923c8603b) | Aug 13, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [6a22791c51](https://linux-hardware.org/?probe=6a22791c51) | Aug 02, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [544c83c508](https://linux-hardware.org/?probe=544c83c508) | Aug 01, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [9394c6057f](https://linux-hardware.org/?probe=9394c6057f) | Aug 01, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [6cf789df63](https://linux-hardware.org/?probe=6cf789df63) | Jul 26, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [a6040fd25f](https://linux-hardware.org/?probe=a6040fd25f) | Jul 21, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [6c7e86d4da](https://linux-hardware.org/?probe=6c7e86d4da) | Jul 19, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [357c0ed67a](https://linux-hardware.org/?probe=357c0ed67a) | Jul 19, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [e4ad262a5d](https://linux-hardware.org/?probe=e4ad262a5d) | Jul 18, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [c52b084692](https://linux-hardware.org/?probe=c52b084692) | Jul 08, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [06efccb71d](https://linux-hardware.org/?probe=06efccb71d) | Jul 07, 2019 |
| Wistron       | JIH55Y                      | Desktop     | [75d7b2909e](https://linux-hardware.org/?probe=75d7b2909e) | Jul 07, 2019 |
| MSI           | K9A2 Neo2                   | Desktop     | [ab1717a7d5](https://linux-hardware.org/?probe=ab1717a7d5) | Jul 05, 2019 |
| MSI           | K9A2 Neo2                   | Desktop     | [d71c202dcb](https://linux-hardware.org/?probe=d71c202dcb) | Jul 05, 2019 |
| MSI           | K9A2 Neo2                   | Desktop     | [32eed13a8c](https://linux-hardware.org/?probe=32eed13a8c) | Jul 05, 2019 |
| Dell          | Inspiron 3537               | Notebook    | [96b08c73b2](https://linux-hardware.org/?probe=96b08c73b2) | Jul 03, 2019 |
| Dell          | Inspiron 7559               | Notebook    | [9662a59bb6](https://linux-hardware.org/?probe=9662a59bb6) | Jun 19, 2019 |
| ASUSTek       | K46CM                       | Notebook    | [f695a76e03](https://linux-hardware.org/?probe=f695a76e03) | Jun 16, 2019 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [e3cbad71df](https://linux-hardware.org/?probe=e3cbad71df) | Jun 06, 2019 |
| Dell          | Precision M4800             | Notebook    | [87cd78dbb8](https://linux-hardware.org/?probe=87cd78dbb8) | Jun 06, 2019 |
| Dell          | Inspiron 7559               | Notebook    | [2b022f3e6e](https://linux-hardware.org/?probe=2b022f3e6e) | Jun 06, 2019 |
| HP            | Unknown                     | Notebook    | [5a84e64836](https://linux-hardware.org/?probe=5a84e64836) | Jun 05, 2019 |
| Lenovo        | Unknown                     | Notebook    | [bb521ffe81](https://linux-hardware.org/?probe=bb521ffe81) | May 29, 2019 |
| Lenovo        | Unknown                     | Notebook    | [ded7e33a30](https://linux-hardware.org/?probe=ded7e33a30) | May 29, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [0142c9d319](https://linux-hardware.org/?probe=0142c9d319) | May 08, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [eab65462c8](https://linux-hardware.org/?probe=eab65462c8) | May 08, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | Notebook    | [11b1a757e3](https://linux-hardware.org/?probe=11b1a757e3) | May 07, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | Notebook    | [48a1bab21b](https://linux-hardware.org/?probe=48a1bab21b) | May 06, 2019 |
| Dell          | Inspiron 3420               | Notebook    | [97669e6bac](https://linux-hardware.org/?probe=97669e6bac) | Apr 28, 2019 |
| Lenovo        | ThinkPad X240 20AMA01LVA    | Notebook    | [60e3dddb8e](https://linux-hardware.org/?probe=60e3dddb8e) | Apr 18, 2019 |
| Lenovo        | ThinkPad X230 2325VEN       | Notebook    | [7de9f34ff3](https://linux-hardware.org/?probe=7de9f34ff3) | Apr 08, 2019 |
| Koompi        | Unknown                     | Notebook    | [d6664b0d4f](https://linux-hardware.org/?probe=d6664b0d4f) | Mar 20, 2019 |
| Lenovo        | ThinkPad T61 7661C54        | Notebook    | [f98ce96fd7](https://linux-hardware.org/?probe=f98ce96fd7) | Dec 14, 2018 |
| Lenovo        | ThinkPad T61 7661C54        | Notebook    | [d50c37f573](https://linux-hardware.org/?probe=d50c37f573) | Dec 14, 2018 |
| Lenovo        | ThinkPad T61 7661C54        | Notebook    | [3b2f20eb21](https://linux-hardware.org/?probe=3b2f20eb21) | Dec 14, 2018 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [eb181d9db4](https://linux-hardware.org/?probe=eb181d9db4) | Nov 17, 2018 |
| Gigabyte      | H61M-DS2                    | Desktop     | [6c2f44420a](https://linux-hardware.org/?probe=6c2f44420a) | Nov 09, 2018 |
| Gigabyte      | H61M-DS2                    | Desktop     | [795142797e](https://linux-hardware.org/?probe=795142797e) | Nov 09, 2018 |
| MSI           | GP62 6QE                    | Notebook    | [0befde2891](https://linux-hardware.org/?probe=0befde2891) | Oct 29, 2018 |
| MSI           | GP62 6QE                    | Notebook    | [6d5cda0177](https://linux-hardware.org/?probe=6d5cda0177) | Oct 29, 2018 |
| ASUSTek       | FX503VM                     | Notebook    | [c3eafeed41](https://linux-hardware.org/?probe=c3eafeed41) | May 23, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [b73b24ff47](https://linux-hardware.org/?probe=b73b24ff47) | May 16, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [4ced3a8a3c](https://linux-hardware.org/?probe=4ced3a8a3c) | Feb 04, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [f286164c3f](https://linux-hardware.org/?probe=f286164c3f) | Feb 04, 2018 |
| HP            | Notebook                    | Notebook    | [8f94426008](https://linux-hardware.org/?probe=8f94426008) | Dec 21, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [96a6c5cbab](https://linux-hardware.org/?probe=96a6c5cbab) | Dec 17, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [f59b817feb](https://linux-hardware.org/?probe=f59b817feb) | Dec 12, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [06a39a2c60](https://linux-hardware.org/?probe=06a39a2c60) | Dec 12, 2017 |
| Lenovo        | Board                       | Desktop     | [850f4b963c](https://linux-hardware.org/?probe=850f4b963c) | Dec 08, 2017 |
| Lenovo        | Board                       | Desktop     | [d8a97c748e](https://linux-hardware.org/?probe=d8a97c748e) | Dec 08, 2017 |
| Lenovo        | Board                       | Desktop     | [b820c8babb](https://linux-hardware.org/?probe=b820c8babb) | Dec 07, 2017 |
| Dell          | Precision M4600             | Notebook    | [dbbeb2486e](https://linux-hardware.org/?probe=dbbeb2486e) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [7ee7ca743b](https://linux-hardware.org/?probe=7ee7ca743b) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [28ae3d12b8](https://linux-hardware.org/?probe=28ae3d12b8) | Dec 03, 2017 |
| Lenovo        | Board                       | Desktop     | [e764602f25](https://linux-hardware.org/?probe=e764602f25) | Dec 02, 2017 |
| ASUSTek       | GL552JX                     | Notebook    | [c3e4792075](https://linux-hardware.org/?probe=c3e4792075) | Dec 10, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 82        | 26.89%  |
| Ubuntu 18.04                 | 37        | 12.13%  |
| Arch                         | 12        | 3.93%   |
| Ubuntu 16.04                 | 9         | 2.95%   |
| Pop!_OS 20.04                | 7         | 2.3%    |
| Debian 10                    | 7         | 2.3%    |
| Ubuntu 21.04                 | 6         | 1.97%   |
| ArcoLinux Rolling            | 6         | 1.97%   |
| OpenMandriva 4.2             | 5         | 1.64%   |
| Manjaro 20.2                 | 5         | 1.64%   |
| KDE neon 20.04               | 5         | 1.64%   |
| Arch Rolling                 | 5         | 1.64%   |
| Zorin 16                     | 4         | 1.31%   |
| Ubuntu 21.10                 | 4         | 1.31%   |
| Ubuntu 19.10                 | 4         | 1.31%   |
| Ubuntu 19.04                 | 4         | 1.31%   |
| Pop!_OS 21.04                | 4         | 1.31%   |
| Pop!_OS 20.10                | 4         | 1.31%   |
| Fedora 34                    | 4         | 1.31%   |
| Fedora 33                    | 4         | 1.31%   |
| Zorin 15                     | 3         | 0.98%   |
| Ubuntu 20.10                 | 3         | 0.98%   |
| Kubuntu 20.04                | 3         | 0.98%   |
| EndeavourOS Rolling          | 3         | 0.98%   |
| Elementary 6                 | 3         | 0.98%   |
| Debian 11                    | 3         | 0.98%   |
| Ubuntu MATE 20.04            | 2         | 0.66%   |
| Ubuntu 22.04                 | 2         | 0.66%   |
| Pop!_OS 21.10                | 2         | 0.66%   |
| OpenMandriva 4.3             | 2         | 0.66%   |
| Manjaro 18.0.4               | 2         | 0.66%   |
| Manjaro                      | 2         | 0.66%   |
| Linux Mint 20.3              | 2         | 0.66%   |
| Linux Mint 20.1              | 2         | 0.66%   |
| Linux Mint 20                | 2         | 0.66%   |
| Linux Mint 18.3              | 2         | 0.66%   |
| Kubuntu 21.04                | 2         | 0.66%   |
| Endless 3.8.0                | 2         | 0.66%   |
| Xubuntu 21.04                | 1         | 0.33%   |
| Xubuntu 20.04                | 1         | 0.33%   |
| Void Linux Rolling           | 1         | 0.33%   |
| Ubuntu Core 16               | 1         | 0.33%   |
| Ubuntu 18.10                 | 1         | 0.33%   |
| Solus 4.3                    | 1         | 0.33%   |
| ROSA R8                      | 1         | 0.33%   |
| Parrot 4.11                  | 1         | 0.33%   |
| openSUSE Tumbleweed-20210427 | 1         | 0.33%   |
| openSUSE Leap-15.1           | 1         | 0.33%   |
| openSUSE 20210916            | 1         | 0.33%   |
| openSUSE 20200405            | 1         | 0.33%   |
| MX 20                        | 1         | 0.33%   |
| Manjaro 21.2.6               | 1         | 0.33%   |
| Manjaro 21.0.5               | 1         | 0.33%   |
| Manjaro 21.0.1               | 1         | 0.33%   |
| Manjaro 20.1.2               | 1         | 0.33%   |
| Manjaro 20.1                 | 1         | 0.33%   |
| Manjaro 20.0.3               | 1         | 0.33%   |
| Lubuntu 20.04                | 1         | 0.33%   |
| Linux Mint 20.2              | 1         | 0.33%   |
| Linux Mint 19.3              | 1         | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 149       | 49.83%  |
| Pop!_OS      | 17        | 5.69%   |
| Arch         | 17        | 5.69%   |
| Manjaro      | 15        | 5.02%   |
| Fedora       | 11        | 3.68%   |
| Linux Mint   | 10        | 3.34%   |
| Debian       | 10        | 3.34%   |
| Zorin        | 7         | 2.34%   |
| OpenMandriva | 7         | 2.34%   |
| Endless      | 7         | 2.34%   |
| Kubuntu      | 6         | 2.01%   |
| ArcoLinux    | 6         | 2.01%   |
| KDE neon     | 5         | 1.67%   |
| openSUSE     | 4         | 1.34%   |
| Elementary   | 4         | 1.34%   |
| Clear Linux  | 4         | 1.34%   |
| Kali         | 3         | 1%      |
| EndeavourOS  | 3         | 1%      |
| Xubuntu      | 2         | 0.67%   |
| Ubuntu MATE  | 2         | 0.67%   |
| Gentoo       | 2         | 0.67%   |
| Void Linux   | 1         | 0.33%   |
| Solus        | 1         | 0.33%   |
| ROSA         | 1         | 0.33%   |
| Parrot       | 1         | 0.33%   |
| MX           | 1         | 0.33%   |
| Lubuntu      | 1         | 0.33%   |
| Devuan       | 1         | 0.33%   |
| CentOS       | 1         | 0.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 9         | 2.73%   |
| 5.4.0-37-generic         | 8         | 2.42%   |
| 5.4.0-52-generic         | 7         | 2.12%   |
| 5.4.0-48-generic         | 7         | 2.12%   |
| 5.4.0-58-generic         | 6         | 1.82%   |
| 5.4.0-40-generic         | 6         | 1.82%   |
| 5.8.0-55-generic         | 5         | 1.52%   |
| 5.11.0-38-generic        | 5         | 1.52%   |
| 5.11.0-37-generic        | 5         | 1.52%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.52%   |
| 5.8.0-7642-generic       | 4         | 1.21%   |
| 5.8.0-53-generic         | 4         | 1.21%   |
| 5.8.0-50-generic         | 4         | 1.21%   |
| 5.4.0-47-generic         | 4         | 1.21%   |
| 5.4.0-26-generic         | 4         | 1.21%   |
| 5.11.0-41-generic        | 4         | 1.21%   |
| 5.0.0-23-generic         | 4         | 1.21%   |
| 5.8.0-48-generic         | 3         | 0.91%   |
| 5.8.0-44-generic         | 3         | 0.91%   |
| 5.4.0-72-generic         | 3         | 0.91%   |
| 5.4.0-39-generic         | 3         | 0.91%   |
| 4.18.0-25-generic        | 3         | 0.91%   |
| 4.10.0-28-generic        | 3         | 0.91%   |
| 5.9.14-200.fc33.x86_64   | 2         | 0.61%   |
| 5.9.11-3-MANJARO         | 2         | 0.61%   |
| 5.8.0-59-generic         | 2         | 0.61%   |
| 5.8.0-45-generic         | 2         | 0.61%   |
| 5.8.0-43-generic         | 2         | 0.61%   |
| 5.8.0-41-generic         | 2         | 0.61%   |
| 5.8.0-25-generic         | 2         | 0.61%   |
| 5.4.0-90-generic         | 2         | 0.61%   |
| 5.4.0-7642-generic       | 2         | 0.61%   |
| 5.4.0-74-generic         | 2         | 0.61%   |
| 5.4.0-70-generic         | 2         | 0.61%   |
| 5.4.0-54-generic         | 2         | 0.61%   |
| 5.4.0-45-generic         | 2         | 0.61%   |
| 5.4.0-29-generic         | 2         | 0.61%   |
| 5.4.0-19-generic         | 2         | 0.61%   |
| 5.3.0-46-generic         | 2         | 0.61%   |
| 5.3.0-28-generic         | 2         | 0.61%   |
| 5.3.0-18-generic         | 2         | 0.61%   |
| 5.13.16-200.fc34.x86_64  | 2         | 0.61%   |
| 5.13.0-7614-generic      | 2         | 0.61%   |
| 5.13.0-30-generic        | 2         | 0.61%   |
| 5.13.0-28-generic        | 2         | 0.61%   |
| 5.13.0-20-generic        | 2         | 0.61%   |
| 5.11.0-7620-generic      | 2         | 0.61%   |
| 5.11.0-40-generic        | 2         | 0.61%   |
| 5.11.0-27-generic        | 2         | 0.61%   |
| 5.11.0-17-generic        | 2         | 0.61%   |
| 5.0.0-37-generic         | 2         | 0.61%   |
| 5.0.0-13-generic         | 2         | 0.61%   |
| 4.19.0-8-amd64           | 2         | 0.61%   |
| 4.15.0-96-generic        | 2         | 0.61%   |
| 4.15.0-36-generic        | 2         | 0.61%   |
| 5.9.3-1-MANJARO          | 1         | 0.3%    |
| 5.9.13-1-MANJARO         | 1         | 0.3%    |
| 5.9.12-arch1-1           | 1         | 0.3%    |
| 5.9.11-arch2-1           | 1         | 0.3%    |
| 5.9.1-1-MANJARO          | 1         | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 75        | 24.35%  |
| 5.8.0   | 35        | 11.36%  |
| 5.11.0  | 30        | 9.74%   |
| 4.15.0  | 15        | 4.87%   |
| 5.0.0   | 13        | 4.22%   |
| 5.3.0   | 11        | 3.57%   |
| 5.13.0  | 10        | 3.25%   |
| 4.18.0  | 8         | 2.6%    |
| 5.10.0  | 7         | 2.27%   |
| 5.10.14 | 5         | 1.62%   |
| 4.19.0  | 5         | 1.62%   |
| 4.10.0  | 5         | 1.62%   |
| 5.9.11  | 3         | 0.97%   |
| 5.9.0   | 3         | 0.97%   |
| 5.15.0  | 3         | 0.97%   |
| 5.9.14  | 2         | 0.65%   |
| 5.16.7  | 2         | 0.65%   |
| 5.13.16 | 2         | 0.65%   |
| 5.12.8  | 2         | 0.65%   |
| 4.13.0  | 2         | 0.65%   |
| 5.9.3   | 1         | 0.32%   |
| 5.9.13  | 1         | 0.32%   |
| 5.9.12  | 1         | 0.32%   |
| 5.9.1   | 1         | 0.32%   |
| 5.8.16  | 1         | 0.32%   |
| 5.8.14  | 1         | 0.32%   |
| 5.8.12  | 1         | 0.32%   |
| 5.7.16  | 1         | 0.32%   |
| 5.7.13  | 1         | 0.32%   |
| 5.7.12  | 1         | 0.32%   |
| 5.6.15  | 1         | 0.32%   |
| 5.6.0   | 1         | 0.32%   |
| 5.5.2   | 1         | 0.32%   |
| 5.5.10  | 1         | 0.32%   |
| 5.4.98  | 1         | 0.32%   |
| 5.4.97  | 1         | 0.32%   |
| 5.4.80  | 1         | 0.32%   |
| 5.4.78  | 1         | 0.32%   |
| 5.4.60  | 1         | 0.32%   |
| 5.4.18  | 1         | 0.32%   |
| 5.4.17  | 1         | 0.32%   |
| 5.4.13  | 1         | 0.32%   |
| 5.4.118 | 1         | 0.32%   |
| 5.17.4  | 1         | 0.32%   |
| 5.17.1  | 1         | 0.32%   |
| 5.16.9  | 1         | 0.32%   |
| 5.16.8  | 1         | 0.32%   |
| 5.16.13 | 1         | 0.32%   |
| 5.16.0  | 1         | 0.32%   |
| 5.15.8  | 1         | 0.32%   |
| 5.15.5  | 1         | 0.32%   |
| 5.15.32 | 1         | 0.32%   |
| 5.15.11 | 1         | 0.32%   |
| 5.15.10 | 1         | 0.32%   |
| 5.14.8  | 1         | 0.32%   |
| 5.14.2  | 1         | 0.32%   |
| 5.14.15 | 1         | 0.32%   |
| 5.14.14 | 1         | 0.32%   |
| 5.14.11 | 1         | 0.32%   |
| 5.13.9  | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 84        | 27.45%  |
| 5.8     | 38        | 12.42%  |
| 5.11    | 32        | 10.46%  |
| 5.10    | 21        | 6.86%   |
| 5.13    | 16        | 5.23%   |
| 5.0     | 16        | 5.23%   |
| 4.15    | 16        | 5.23%   |
| 5.9     | 12        | 3.92%   |
| 5.3     | 11        | 3.59%   |
| 5.15    | 8         | 2.61%   |
| 5.12    | 8         | 2.61%   |
| 4.18    | 8         | 2.61%   |
| 4.19    | 7         | 2.29%   |
| 5.16    | 6         | 1.96%   |
| 4.10    | 5         | 1.63%   |
| 5.14    | 4         | 1.31%   |
| 5.7     | 3         | 0.98%   |
| 5.6     | 2         | 0.65%   |
| 5.5     | 2         | 0.65%   |
| 5.17    | 2         | 0.65%   |
| 4.13    | 2         | 0.65%   |
| 4.4     | 1         | 0.33%   |
| 4.12    | 1         | 0.33%   |
| 4.1     | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 293       | 98.99%  |
| i686    | 2         | 0.68%   |
| aarch64 | 1         | 0.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 161       | 53.31%  |
| Unknown    | 50        | 16.56%  |
| KDE5       | 28        | 9.27%   |
| XFCE       | 18        | 5.96%   |
| KDE        | 11        | 3.64%   |
| Unity      | 7         | 2.32%   |
| MATE       | 5         | 1.66%   |
| X-Cinnamon | 4         | 1.32%   |
| Pantheon   | 4         | 1.32%   |
| Cinnamon   | 4         | 1.32%   |
| bspwm      | 2         | 0.66%   |
| awesome    | 2         | 0.66%   |
| Openbox    | 1         | 0.33%   |
| LXQt       | 1         | 0.33%   |
| KDE4       | 1         | 0.33%   |
| i3         | 1         | 0.33%   |
| Deepin     | 1         | 0.33%   |
| Budgie     | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 242       | 80.4%   |
| Unknown | 28        | 9.3%    |
| Wayland | 26        | 8.64%   |
| Tty     | 5         | 1.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 164       | 54.49%  |
| GDM     | 56        | 18.6%   |
| SDDM    | 29        | 9.63%   |
| TDM     | 19        | 6.31%   |
| LightDM | 19        | 6.31%   |
| GDM3    | 11        | 3.65%   |
| XDM     | 1         | 0.33%   |
| SLiM    | 1         | 0.33%   |
| KDM     | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 221       | 74.41%  |
| Unknown | 43        | 14.48%  |
| vi_VN   | 19        | 6.4%    |
| C       | 5         | 1.68%   |
| en_AU   | 3         | 1.01%   |
| ru_RU   | 2         | 0.67%   |
| en_GB   | 2         | 0.67%   |
| fr_FR   | 1         | 0.34%   |
| de_DE   | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 186       | 61.59%  |
| BIOS | 116       | 38.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 248       | 83.22%  |
| Btrfs   | 16        | 5.37%   |
| Unknown | 14        | 4.7%    |
| Overlay | 12        | 4.03%   |
| Zfs     | 6         | 2.01%   |
| Xfs     | 1         | 0.34%   |
| Ext3    | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 162       | 54.55%  |
| GPT     | 109       | 36.7%   |
| MBR     | 26        | 8.75%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 267       | 89.3%   |
| Yes       | 32        | 10.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 167       | 55.67%  |
| Yes       | 133       | 44.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell                           | 67        | 22.64%  |
| ASUSTek Computer               | 49        | 16.55%  |
| Lenovo                         | 45        | 15.2%   |
| Hewlett-Packard                | 39        | 13.18%  |
| Gigabyte Technology            | 25        | 8.45%   |
| MSI                            | 16        | 5.41%   |
| Acer                           | 15        | 5.07%   |
| Toshiba                        | 4         | 1.35%   |
| Sony                           | 4         | 1.35%   |
| Apple                          | 4         | 1.35%   |
| Intel                          | 3         | 1.01%   |
| Wistron                        | 2         | 0.68%   |
| Samsung Electronics            | 2         | 0.68%   |
| Foxconn                        | 2         | 0.68%   |
| ASRock                         | 2         | 0.68%   |
| ZOTAC                          | 1         | 0.34%   |
| Timi                           | 1         | 0.34%   |
| Shuttle                        | 1         | 0.34%   |
| Shenzhen Amediatech Technology | 1         | 0.34%   |
| Panasonic                      | 1         | 0.34%   |
| Microsoft                      | 1         | 0.34%   |
| MASSCOM VIETNAM                | 1         | 0.34%   |
| LG Electronics                 | 1         | 0.34%   |
| Koompi                         | 1         | 0.34%   |
| Koloe                          | 1         | 0.34%   |
| Jumper                         | 1         | 0.34%   |
| Huanan                         | 1         | 0.34%   |
| Gateway                        | 1         | 0.34%   |
| Colorful Technology            | 1         | 0.34%   |
| Chuwi                          | 1         | 0.34%   |
| AMI                            | 1         | 0.34%   |
| Unknown                        | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 5         | 1.69%   |
| Gigabyte H61M-DS2            | 4         | 1.35%   |
| Dell Inspiron 3537           | 4         | 1.35%   |
| Lenovo Legion 5 15ARH05 82B5 | 3         | 1.01%   |
| ASUS X411UA                  | 3         | 1.01%   |
| ASUS All Series              | 3         | 1.01%   |
| Toshiba Satellite L840       | 2         | 0.68%   |
| MSI MS-7B89                  | 2         | 0.68%   |
| MSI MS-7823                  | 2         | 0.68%   |
| MSI GF63 8RD                 | 2         | 0.68%   |
| Lenovo ThinkPad W530 2447EJ9 | 2         | 0.68%   |
| HP Notebook                  | 2         | 0.68%   |
| HP Laptop 14-bs0xx           | 2         | 0.68%   |
| HP EliteBook 840 G2          | 2         | 0.68%   |
| Gigabyte G41M-ES2L           | 2         | 0.68%   |
| Dell XPS 15 9570             | 2         | 0.68%   |
| Dell Vostro 3590             | 2         | 0.68%   |
| Dell Vostro 3578             | 2         | 0.68%   |
| Dell Vostro 3478             | 2         | 0.68%   |
| Dell Vostro 3460             | 2         | 0.68%   |
| Dell Vostro 15-3568          | 2         | 0.68%   |
| Dell Latitude E7440          | 2         | 0.68%   |
| Dell Inspiron 5570           | 2         | 0.68%   |
| Dell G3 3579                 | 2         | 0.68%   |
| ASUS P8H61-MX R2.0           | 2         | 0.68%   |
| ASUS K501UX                  | 2         | 0.68%   |
| ASUS B75M-A                  | 2         | 0.68%   |
| Acer Swift SF315-52          | 2         | 0.68%   |
| Acer Predator PH315-51       | 2         | 0.68%   |
| Acer Aspire A315-42          | 2         | 0.68%   |
| ZOTAC ZBOX-AD04              | 1         | 0.34%   |
| Wistron FMVDD2A0H0           | 1         | 0.34%   |
| Wistron FMVCEG40Y            | 1         | 0.34%   |
| Toshiba Satellite E45-B      | 1         | 0.34%   |
| Toshiba PORTEGE T110         | 1         | 0.34%   |
| Timi A35S                    | 1         | 0.34%   |
| Sony VPCEB42EG               | 1         | 0.34%   |
| Sony VPCCW13FX               | 1         | 0.34%   |
| Sony VGN-NW270F              | 1         | 0.34%   |
| Sony SVE14A15FGW             | 1         | 0.34%   |
| Shuttle DS81D                | 1         | 0.34%   |
| Shenzhen Amediatech X96 Max  | 1         | 0.34%   |
| Samsung NC208/NC108          | 1         | 0.34%   |
| Samsung 300E4Z/300E5Z/300E7Z | 1         | 0.34%   |
| Panasonic CFSX4-1            | 1         | 0.34%   |
| MSI Prestige 15 A11SCX       | 1         | 0.34%   |
| MSI MS-7C67                  | 1         | 0.34%   |
| MSI MS-7C31                  | 1         | 0.34%   |
| MSI MS-7B98                  | 1         | 0.34%   |
| MSI MS-7A38                  | 1         | 0.34%   |
| MSI MS-7388                  | 1         | 0.34%   |
| MSI GS40 6QE Phantom         | 1         | 0.34%   |
| MSI GP62 6QE                 | 1         | 0.34%   |
| MSI GF62 7RD                 | 1         | 0.34%   |
| MSI GE66 Raider 11UH         | 1         | 0.34%   |
| Microsoft Surface Pro        | 1         | 0.34%   |
| MASSCOM VIETNAM L133         | 1         | 0.34%   |
| LG 17U70N-R.AAS7U1           | 1         | 0.34%   |
| Lenovo Z40-70 20366          | 1         | 0.34%   |
| Lenovo Y520-15IKBN 80WK      | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 23        | 7.77%   |
| Dell Inspiron           | 19        | 6.42%   |
| Dell Vostro             | 17        | 5.74%   |
| Dell Latitude           | 11        | 3.72%   |
| HP EliteBook            | 10        | 3.38%   |
| Acer Aspire             | 9         | 3.04%   |
| Lenovo IdeaPad          | 7         | 2.36%   |
| HP ProBook              | 7         | 2.36%   |
| Dell XPS                | 6         | 2.03%   |
| Dell Precision          | 6         | 2.03%   |
| ASUS VivoBook           | 6         | 2.03%   |
| HP Laptop               | 5         | 1.69%   |
| Unknown                 | 5         | 1.69%   |
| Lenovo Legion           | 4         | 1.35%   |
| Gigabyte H61M-DS2       | 4         | 1.35%   |
| ASUS ROG                | 4         | 1.35%   |
| ASUS PRIME              | 4         | 1.35%   |
| Toshiba Satellite       | 3         | 1.01%   |
| Lenovo ThinkBook        | 3         | 1.01%   |
| HP ZBook                | 3         | 1.01%   |
| HP Pavilion             | 3         | 1.01%   |
| Dell OptiPlex           | 3         | 1.01%   |
| Dell G3                 | 3         | 1.01%   |
| ASUS X411UA             | 3         | 1.01%   |
| ASUS P8H61-MX           | 3         | 1.01%   |
| ASUS ASUS               | 3         | 1.01%   |
| ASUS All                | 3         | 1.01%   |
| Acer Swift              | 3         | 1.01%   |
| Acer Predator           | 3         | 1.01%   |
| MSI MS-7B89             | 2         | 0.68%   |
| MSI MS-7823             | 2         | 0.68%   |
| MSI GF63                | 2         | 0.68%   |
| Lenovo ThinkCentre      | 2         | 0.68%   |
| HP Notebook             | 2         | 0.68%   |
| HP Compaq               | 2         | 0.68%   |
| Gigabyte G41M-ES2L      | 2         | 0.68%   |
| Dell System             | 2         | 0.68%   |
| ASUS K501UX             | 2         | 0.68%   |
| ASUS B75M-A             | 2         | 0.68%   |
| ZOTAC ZBOX-AD04         | 1         | 0.34%   |
| Wistron FMVDD2A0H0      | 1         | 0.34%   |
| Wistron FMVCEG40Y       | 1         | 0.34%   |
| Toshiba PORTEGE         | 1         | 0.34%   |
| Timi A35S               | 1         | 0.34%   |
| Sony VPCEB42EG          | 1         | 0.34%   |
| Sony VPCCW13FX          | 1         | 0.34%   |
| Sony VGN-NW270F         | 1         | 0.34%   |
| Sony SVE14A15FGW        | 1         | 0.34%   |
| Shuttle DS81D           | 1         | 0.34%   |
| Shenzhen Amediatech X96 | 1         | 0.34%   |
| Samsung NC208           | 1         | 0.34%   |
| Samsung 300E4Z          | 1         | 0.34%   |
| Panasonic CFSX4-1       | 1         | 0.34%   |
| MSI Prestige            | 1         | 0.34%   |
| MSI MS-7C67             | 1         | 0.34%   |
| MSI MS-7C31             | 1         | 0.34%   |
| MSI MS-7B98             | 1         | 0.34%   |
| MSI MS-7A38             | 1         | 0.34%   |
| MSI MS-7388             | 1         | 0.34%   |
| MSI GS40                | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 44        | 14.86%  |
| 2012    | 38        | 12.84%  |
| 2019    | 28        | 9.46%   |
| 2020    | 25        | 8.45%   |
| 2017    | 23        | 7.77%   |
| 2013    | 22        | 7.43%   |
| 2016    | 21        | 7.09%   |
| 2015    | 21        | 7.09%   |
| 2014    | 21        | 7.09%   |
| 2011    | 15        | 5.07%   |
| 2010    | 13        | 4.39%   |
| 2009    | 10        | 3.38%   |
| 2021    | 9         | 3.04%   |
| 2007    | 4         | 1.35%   |
| 2008    | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 210       | 70.95%  |
| Desktop        | 74        | 25%     |
| Tablet         | 5         | 1.69%   |
| Mini pc        | 2         | 0.68%   |
| All in one     | 2         | 0.68%   |
| System on chip | 1         | 0.34%   |
| Convertible    | 1         | 0.34%   |
| Server         | 1         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 273       | 91.3%   |
| Enabled  | 26        | 8.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 296       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 82        | 27.52%  |
| 16.01-24.0  | 61        | 20.47%  |
| 8.01-16.0   | 60        | 20.13%  |
| 3.01-4.0    | 58        | 19.46%  |
| 32.01-64.0  | 17        | 5.7%    |
| 1.01-2.0    | 13        | 4.36%   |
| 24.01-32.0  | 4         | 1.34%   |
| 2.01-3.0    | 1         | 0.34%   |
| 64.01-256.0 | 1         | 0.34%   |
| 0.51-1.0    | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 104       | 33.02%  |
| 1.01-2.0   | 96        | 30.48%  |
| 4.01-8.0   | 47        | 14.92%  |
| 3.01-4.0   | 46        | 14.6%   |
| 8.01-16.0  | 12        | 3.81%   |
| 0.51-1.0   | 7         | 2.22%   |
| 16.01-24.0 | 2         | 0.63%   |
| 0.01-0.5   | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 180       | 60.4%   |
| 2      | 92        | 30.87%  |
| 3      | 16        | 5.37%   |
| 4      | 6         | 2.01%   |
| 0      | 2         | 0.67%   |
| 9      | 1         | 0.34%   |
| 5      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 222       | 75%     |
| Yes       | 74        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 254       | 85.23%  |
| No        | 44        | 14.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 84.12%  |
| No        | 47        | 15.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 72.05%  |
| No        | 83        | 27.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Vietnam | 296       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Ho Chi Minh City   | 127       | 41.64%  |
| Hanoi              | 99        | 32.46%  |
| Da Nang            | 9         | 2.95%   |
| Nha Trang          | 4         | 1.31%   |
| Nam Дђб»‹nh  | 4         | 1.31%   |
| Can Tho            | 4         | 1.31%   |
| VЕ©ng TГ u     | 3         | 0.98%   |
| Thai Nguyen        | 3         | 0.98%   |
| Tay Ninh           | 3         | 0.98%   |
| Quan Chin          | 3         | 0.98%   |
| Vinh Phuc          | 2         | 0.66%   |
| Thuan An           | 2         | 0.66%   |
| Tan An             | 2         | 0.66%   |
| Hung Yen           | 2         | 0.66%   |
| Dien Ban           | 2         | 0.66%   |
| Da Lat             | 2         | 0.66%   |
| Cao Lanh           | 2         | 0.66%   |
| Bien Hoa           | 2         | 0.66%   |
| Bao Loc            | 2         | 0.66%   |
| Vũng Tàu         | 1         | 0.33%   |
| Vinh Yen           | 1         | 0.33%   |
| Vinh               | 1         | 0.33%   |
| Thu Dau Mot        | 1         | 0.33%   |
| Tam Diep           | 1         | 0.33%   |
| Rach Gia           | 1         | 0.33%   |
| Quáº£ng NgÃ£i | 1         | 0.33%   |
| Quang Trung        | 1         | 0.33%   |
| Quang Tri          | 1         | 0.33%   |
| Quan Sau           | 1         | 0.33%   |
| Pleiku             | 1         | 0.33%   |
| Phan Thiбєїt    | 1         | 0.33%   |
| Nam Định        | 1         | 0.33%   |
| Nam Äá»‹nh  | 1         | 0.33%   |
| Khu Pho Nam        | 1         | 0.33%   |
| Khu Pho Bay        | 1         | 0.33%   |
| Huбєї           | 1         | 0.33%   |
| Hoa Thanh          | 1         | 0.33%   |
| Hoa Binh           | 1         | 0.33%   |
| Haiphong           | 1         | 0.33%   |
| Hai Duong          | 1         | 0.33%   |
| Dong Anh           | 1         | 0.33%   |
| Do Son             | 1         | 0.33%   |
| Di Linh            | 1         | 0.33%   |
| Cam Ranh           | 1         | 0.33%   |
| Bong Son           | 1         | 0.33%   |
| Binh Tan           | 1         | 0.33%   |
| Ba Ria             | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 70        | 84     | 16.59%  |
| Samsung Electronics   | 51        | 63     | 12.09%  |
| Seagate               | 50        | 61     | 11.85%  |
| Toshiba               | 36        | 47     | 8.53%   |
| HGST                  | 23        | 23     | 5.45%   |
| Intel                 | 20        | 21     | 4.74%   |
| Unknown               | 18        | 19     | 4.27%   |
| SK Hynix              | 17        | 18     | 4.03%   |
| Kingston              | 15        | 17     | 3.55%   |
| Hitachi               | 12        | 16     | 2.84%   |
| Crucial               | 12        | 16     | 2.84%   |
| Micron Technology     | 9         | 11     | 2.13%   |
| SanDisk               | 8         | 9      | 1.9%    |
| PLEXTOR               | 7         | 7      | 1.66%   |
| TO Exter              | 6         | 8      | 1.42%   |
| Lexar                 | 6         | 6      | 1.42%   |
| Colorful              | 6         | 6      | 1.42%   |
| OSCOO                 | 5         | 6      | 1.18%   |
| OCZ                   | 3         | 3      | 0.71%   |
| Netac                 | 3         | 3      | 0.71%   |
| ZOTAC                 | 2         | 3      | 0.47%   |
| Transcend             | 2         | 2      | 0.47%   |
| Phison                | 2         | 3      | 0.47%   |
| MAXTOR                | 2         | 2      | 0.47%   |
| LITEON                | 2         | 2      | 0.47%   |
| Lite-On               | 2         | 4      | 0.47%   |
| KingSpec              | 2         | 2      | 0.47%   |
| KingDian              | 2         | 4      | 0.47%   |
| Fujitsu               | 2         | 2      | 0.47%   |
| FORESEE               | 2         | 2      | 0.47%   |
| Apple                 | 2         | 2      | 0.47%   |
| Vaseky                | 1         | 1      | 0.24%   |
| SPCC                  | 1         | 1      | 0.24%   |
| Realtek Semiconductor | 1         | 2      | 0.24%   |
| OSC                   | 1         | 1      | 0.24%   |
| LITEONIT              | 1         | 1      | 0.24%   |
| Lenovo                | 1         | 1      | 0.24%   |
| KLEVV                 | 1         | 1      | 0.24%   |
| KIOXIA-EXCERIA        | 1         | 2      | 0.24%   |
| KIOXIA                | 1         | 1      | 0.24%   |
| Kingmax               | 1         | 1      | 0.24%   |
| KingFast              | 1         | 1      | 0.24%   |
| KING                  | 1         | 1      | 0.24%   |
| Indilinx              | 1         | 1      | 0.24%   |
| HXY                   | 1         | 1      | 0.24%   |
| Hikvision             | 1         | 1      | 0.24%   |
| Hewlett-Packard       | 1         | 1      | 0.24%   |
| Gigabyte Technology   | 1         | 1      | 0.24%   |
| External              | 1         | 1      | 0.24%   |
| EK                    | 1         | 1      | 0.24%   |
| China                 | 1         | 1      | 0.24%   |
| BR                    | 1         | 1      | 0.24%   |
| Apacer                | 1         | 1      | 0.24%   |
| AGI                   | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD     | 7         | 1.6%    |
| Seagate ST1000LM035-1RK172 1TB       | 7         | 1.6%    |
| HGST HTS721010A9E630 1TB             | 7         | 1.6%    |
| TO Exter nal USB 3.0 128GB           | 6         | 1.37%   |
| Samsung NVMe SSD Drive 512GB         | 6         | 1.37%   |
| Toshiba MQ04ABF100 1TB               | 5         | 1.14%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.14%   |
| SK Hynix NVMe SSD Drive 256GB        | 4         | 0.92%   |
| Seagate ST1000LM049-2GH172 1TB       | 4         | 0.92%   |
| Samsung SSD 860 EVO 500GB            | 4         | 0.92%   |
| Samsung SSD 860 EVO 250GB            | 4         | 0.92%   |
| Lexar 128GB SSD                      | 4         | 0.92%   |
| HGST HTS545050A7E680 500GB           | 4         | 0.92%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 3         | 0.69%   |
| WDC WD2500AAKX-00ERMA0 250GB         | 3         | 0.69%   |
| Unknown MMC Card  32GB               | 3         | 0.69%   |
| Toshiba MQ01ABD100 1TB               | 3         | 0.69%   |
| SK Hynix NVMe SSD Drive 512GB        | 3         | 0.69%   |
| Seagate ST9500325AS 500GB            | 3         | 0.69%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 0.69%   |
| Samsung NVMe SSD Drive 256GB         | 3         | 0.69%   |
| Samsung MZALQ512HALU-000L2 512GB     | 3         | 0.69%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 0.69%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.69%   |
| Hitachi HTS545050A7E380 500GB        | 3         | 0.69%   |
| HGST HTS725050A7E630 500GB           | 3         | 0.69%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 0.69%   |
| ZOTAC SATA SSD 120GB                 | 2         | 0.46%   |
| WDC WDS250G2B0A-00SM50 250GB SSD     | 2         | 0.46%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.46%   |
| WDC WD5000LPCX-21VHAT0 500GB         | 2         | 0.46%   |
| WDC WD3200AAKX-001CA0 320GB          | 2         | 0.46%   |
| WDC WD3200AAJS-00L7A0 320GB          | 2         | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB             | 2         | 0.46%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 0.46%   |
| WDC PC SN720 SDAPNTW-256G-1006 256GB | 2         | 0.46%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB | 2         | 0.46%   |
| Unknown NVMe SSD Drive 256GB         | 2         | 0.46%   |
| Toshiba NVMe SSD Drive 512GB         | 2         | 0.46%   |
| Toshiba NVMe SSD Drive 256GB         | 2         | 0.46%   |
| Toshiba MK2035GSS 200GB              | 2         | 0.46%   |
| Toshiba DT01ABA100V 1TB              | 2         | 0.46%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.46%   |
| Seagate ST2000DM006-2DM164 2TB       | 2         | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.46%   |
| Sandisk NVMe SSD Drive 500GB         | 2         | 0.46%   |
| Samsung SSD 860 EVO 1TB              | 2         | 0.46%   |
| Samsung SSD 750 EVO 120GB            | 2         | 0.46%   |
| Samsung NVMe SSD Drive 250GB         | 2         | 0.46%   |
| Samsung MZVLQ512HBLU-00B00 512GB     | 2         | 0.46%   |
| PLEXTOR PX-256M8VC 256GB SSD         | 2         | 0.46%   |
| OSCOO OSC SSD 128GB                  | 2         | 0.46%   |
| Netac SSD 120GB                      | 2         | 0.46%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.46%   |
| MAXTOR Z1 SSD 240GB                  | 2         | 0.46%   |
| Lexar SSD 240GB                      | 2         | 0.46%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.46%   |
| Kingston NVMe SSD Drive 256GB        | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 50        | 61     | 30.67%  |
| WDC     | 49        | 61     | 30.06%  |
| Toshiba | 26        | 32     | 15.95%  |
| HGST    | 23        | 23     | 14.11%  |
| Hitachi | 12        | 16     | 7.36%   |
| Fujitsu | 2         | 2      | 1.23%   |
| Unknown | 1         | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 29     | 16.67%  |
| WDC                 | 14        | 14     | 8.97%   |
| Kingston            | 12        | 14     | 7.69%   |
| Intel               | 12        | 13     | 7.69%   |
| Crucial             | 11        | 13     | 7.05%   |
| PLEXTOR             | 7         | 7      | 4.49%   |
| TO Exter            | 6         | 8      | 3.85%   |
| Lexar               | 6         | 6      | 3.85%   |
| SanDisk             | 5         | 6      | 3.21%   |
| SK Hynix            | 4         | 4      | 2.56%   |
| Micron Technology   | 4         | 4      | 2.56%   |
| Colorful            | 4         | 4      | 2.56%   |
| Toshiba             | 3         | 4      | 1.92%   |
| OSCOO               | 3         | 3      | 1.92%   |
| Netac               | 3         | 3      | 1.92%   |
| ZOTAC               | 2         | 3      | 1.28%   |
| Transcend           | 2         | 2      | 1.28%   |
| OCZ                 | 2         | 2      | 1.28%   |
| MAXTOR              | 2         | 2      | 1.28%   |
| LITEON              | 2         | 2      | 1.28%   |
| KingSpec            | 2         | 2      | 1.28%   |
| KingDian            | 2         | 4      | 1.28%   |
| FORESEE             | 2         | 2      | 1.28%   |
| Apple               | 2         | 2      | 1.28%   |
| Vaseky              | 1         | 1      | 0.64%   |
| Unknown             | 1         | 1      | 0.64%   |
| SPCC                | 1         | 1      | 0.64%   |
| OSC                 | 1         | 1      | 0.64%   |
| LITEONIT            | 1         | 1      | 0.64%   |
| KLEVV               | 1         | 1      | 0.64%   |
| KIOXIA-EXCERIA      | 1         | 2      | 0.64%   |
| Kingmax             | 1         | 1      | 0.64%   |
| Indilinx            | 1         | 1      | 0.64%   |
| HXY                 | 1         | 1      | 0.64%   |
| Hikvision           | 1         | 1      | 0.64%   |
| Hewlett-Packard     | 1         | 1      | 0.64%   |
| Gigabyte Technology | 1         | 1      | 0.64%   |
| External            | 1         | 1      | 0.64%   |
| EK                  | 1         | 1      | 0.64%   |
| China               | 1         | 1      | 0.64%   |
| Apacer              | 1         | 1      | 0.64%   |
| AGI                 | 1         | 1      | 0.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 149       | 196    | 37.63%  |
| SSD     | 139       | 172    | 35.1%   |
| NVMe    | 88        | 108    | 22.22%  |
| MMC     | 12        | 13     | 3.03%   |
| Unknown | 8         | 8      | 2.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 227       | 361    | 67.16%  |
| NVMe | 88        | 108    | 26.04%  |
| MMC  | 12        | 13     | 3.55%   |
| SAS  | 11        | 15     | 3.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 192       | 264    | 71.11%  |
| 0.51-1.0   | 64        | 81     | 23.7%   |
| 1.01-2.0   | 7         | 9      | 2.59%   |
| 4.01-10.0  | 5         | 12     | 1.85%   |
| 3.01-4.0   | 1         | 1      | 0.37%   |
| 2.01-3.0   | 1         | 1      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 110       | 35.95%  |
| 251-500        | 58        | 18.95%  |
| 501-1000       | 32        | 10.46%  |
| 51-100         | 26        | 8.5%    |
| 1001-2000      | 20        | 6.54%   |
| 21-50          | 18        | 5.88%   |
| 1-20           | 17        | 5.56%   |
| Unknown        | 12        | 3.92%   |
| 2001-3000      | 7         | 2.29%   |
| More than 3000 | 6         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 138       | 44.66%  |
| 21-50          | 55        | 17.8%   |
| 51-100         | 39        | 12.62%  |
| 101-250        | 22        | 7.12%   |
| 251-500        | 19        | 6.15%   |
| 501-1000       | 14        | 4.53%   |
| Unknown        | 12        | 3.88%   |
| More than 3000 | 4         | 1.29%   |
| 1001-2000      | 4         | 1.29%   |
| 2001-3000      | 2         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200AAKX-001CA0 320GB                  | 2         | 2      | 6.06%   |
| Seagate ST1000LM035-1RK172 1TB               | 2         | 2      | 6.06%   |
| HGST HTS725050A7E630 500GB                   | 2         | 2      | 6.06%   |
| WDC WD5000LPLX-60ZNTT1 500GB                 | 1         | 1      | 3.03%   |
| WDC WD3200AAJS-00L7A0 320GB                  | 1         | 1      | 3.03%   |
| WDC WD32 00BEVT-24A23 320GB                  | 1         | 1      | 3.03%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 1         | 1      | 3.03%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 1         | 1      | 3.03%   |
| Unknown Bamba-240GB SSD                      | 1         | 1      | 3.03%   |
| Transcend TS256GSSD230S 256GB                | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 3.03%   |
| Toshiba MK8046GSX 80GB                       | 1         | 1      | 3.03%   |
| Toshiba MK3265GSXN 320GB                     | 1         | 1      | 3.03%   |
| Toshiba HDWK105 500GB                        | 1         | 1      | 3.03%   |
| SK Hynix HFS032G34MNC-2200A 32GB SSD         | 1         | 1      | 3.03%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 3.03%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 3.03%   |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 3.03%   |
| Samsung Electronics MZVPW128HEGM-00000 128GB | 1         | 1      | 3.03%   |
| Intel SSDSC2CW120A3 120GB                    | 1         | 1      | 3.03%   |
| Hitachi HUA722020ALA331 2TB                  | 1         | 1      | 3.03%   |
| Hitachi HTS725050A7E635 500GB                | 1         | 1      | 3.03%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 3.03%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 3.03%   |
| HGST HTS725032A7E630 320GB                   | 1         | 1      | 3.03%   |
| HGST HTS545050A7E680 500GB                   | 1         | 1      | 3.03%   |
| HGST HTS545050A7 500GB                       | 1         | 1      | 3.03%   |
| HGST HTS541010A7E630 1TB                     | 1         | 1      | 3.03%   |
| Fujitsu MHK2120AT 12GB                       | 1         | 1      | 3.03%   |
| Crucial CT525MX300SSD1 528GB                 | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 7      | 21.21%  |
| HGST                | 6         | 6      | 18.18%  |
| Seagate             | 5         | 5      | 15.15%  |
| Toshiba             | 4         | 4      | 12.12%  |
| Hitachi             | 4         | 4      | 12.12%  |
| Unknown             | 1         | 1      | 3.03%   |
| Transcend           | 1         | 1      | 3.03%   |
| SK Hynix            | 1         | 1      | 3.03%   |
| Samsung Electronics | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| Fujitsu             | 1         | 1      | 3.03%   |
| Crucial             | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 7      | 25.93%  |
| HGST    | 6         | 6      | 22.22%  |
| Seagate | 5         | 5      | 18.52%  |
| Toshiba | 4         | 4      | 14.81%  |
| Hitachi | 4         | 4      | 14.81%  |
| Fujitsu | 1         | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 27     | 84.38%  |
| SSD  | 4         | 5      | 12.5%   |
| NVMe | 1         | 1      | 3.13%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 172       | 277    | 52.92%  |
| Works    | 123       | 187    | 37.85%  |
| Malfunc  | 30        | 33     | 9.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 244       | 67.97%  |
| Samsung Electronics            | 31        | 8.64%   |
| AMD                            | 25        | 6.96%   |
| SK Hynix                       | 13        | 3.62%   |
| Sandisk                        | 11        | 3.06%   |
| Toshiba America Info Systems   | 7         | 1.95%   |
| Micron Technology              | 5         | 1.39%   |
| Kingston Technology Company    | 3         | 0.84%   |
| ASMedia Technology             | 3         | 0.84%   |
| Solid State Storage Technology | 2         | 0.56%   |
| Phison Electronics             | 2         | 0.56%   |
| Micron/Crucial Technology      | 2         | 0.56%   |
| Lite-On Technology             | 2         | 0.56%   |
| KIOXIA                         | 2         | 0.56%   |
| Silicon Motion                 | 1         | 0.28%   |
| Realtek Semiconductor          | 1         | 0.28%   |
| OCZ Technology Group           | 1         | 0.28%   |
| Marvell Technology Group       | 1         | 0.28%   |
| LSI Logic / Symbios Logic      | 1         | 0.28%   |
| Lenovo                         | 1         | 0.28%   |
| JMicron Technology             | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 30        | 7.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 27        | 6.94%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 21        | 5.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19        | 4.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13        | 3.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 3.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 3.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 11        | 2.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 11        | 2.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 2.57%   |
| Samsung NVMe SSD Controller 980                                                         | 8         | 2.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 1.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 1.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 1.8%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 7         | 1.8%    |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 6         | 1.54%   |
| Micron Non-Volatile memory controller                                                   | 5         | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5         | 1.29%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 1.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5         | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 1.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.29%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1.29%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 4         | 1.03%   |
| SK Hynix Gold P31 SSD                                                                   | 4         | 1.03%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4         | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.03%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 3         | 0.77%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 3         | 0.77%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 3         | 0.77%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 3         | 0.77%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.77%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3         | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.77%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 0.77%   |
| Solid State Storage Non-Volatile memory controller                                      | 2         | 0.51%   |
| SK Hynix Non-Volatile memory controller                                                 | 2         | 0.51%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 0.51%   |
| Samsung Electronics SATA controller                                                     | 2         | 0.51%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 2         | 0.51%   |
| Lite-On Non-Volatile memory controller                                                  | 2         | 0.51%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 0.51%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 2         | 0.51%   |
| Intel SSD 660P Series                                                                   | 2         | 0.51%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2         | 0.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.51%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.51%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 0.51%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 0.51%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2         | 0.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 0.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 231       | 63.46%  |
| NVMe | 89        | 24.45%  |
| IDE  | 24        | 6.59%   |
| RAID | 19        | 5.22%   |
| SAS  | 1         | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 265       | 89.53%  |
| AMD    | 30        | 10.14%  |
| ARM    | 1         | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 5.07%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 2.36%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 2.36%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 2.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.35%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 1.35%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.35%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4         | 1.35%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.35%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.01%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3         | 1.01%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 1.01%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.01%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.01%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3         | 1.01%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 1.01%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.01%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.01%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 1.01%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.68%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.68%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.68%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.68%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.68%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.68%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 0.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.68%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.68%   |
| Intel Core i5-2500 CPU @ 3.30GHz              | 2         | 0.68%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.68%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.68%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 2         | 0.68%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 2         | 0.68%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 2         | 0.68%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.68%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.68%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 0.68%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 0.68%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2         | 0.68%   |
| Intel Core i3 CPU 540 @ 3.07GHz               | 2         | 0.68%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 2         | 0.68%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 2         | 0.68%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 2         | 0.68%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.68%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 0.68%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.68%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 0.68%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 0.68%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.34%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 0.34%   |
| Intel Xeon CPU X5570 @ 2.93GHz                | 1         | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 109       | 36.82%  |
| Intel Core i7           | 60        | 20.27%  |
| Intel Core i3           | 35        | 11.82%  |
| Other                   | 14        | 4.73%   |
| Intel Core 2 Duo        | 13        | 4.39%   |
| AMD Ryzen 5             | 12        | 4.05%   |
| Intel Celeron           | 10        | 3.38%   |
| Intel Xeon              | 9         | 3.04%   |
| Intel Pentium           | 5         | 1.69%   |
| Intel Atom              | 5         | 1.69%   |
| AMD Ryzen 7             | 4         | 1.35%   |
| AMD Ryzen 3             | 3         | 1.01%   |
| Intel Genuine           | 2         | 0.68%   |
| AMD Ryzen 7 PRO         | 2         | 0.68%   |
| AMD A8                  | 2         | 0.68%   |
| AMD A10                 | 2         | 0.68%   |
| Intel Pentium Dual-Core | 1         | 0.34%   |
| Intel Pentium Dual      | 1         | 0.34%   |
| Intel Core M            | 1         | 0.34%   |
| Intel Core i9           | 1         | 0.34%   |
| AMD Ryzen 9             | 1         | 0.34%   |
| AMD Ryzen 5 PRO         | 1         | 0.34%   |
| AMD Phenom II X4        | 1         | 0.34%   |
| AMD E                   | 1         | 0.34%   |
| AMD Athlon II X2        | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 136       | 45.95%  |
| 4      | 113       | 38.18%  |
| 6      | 29        | 9.8%    |
| 8      | 12        | 4.05%   |
| 1      | 2         | 0.68%   |
| 28     | 1         | 0.34%   |
| 24     | 1         | 0.34%   |
| 16     | 1         | 0.34%   |
| 12     | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 292       | 98.65%  |
| 2      | 4         | 1.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 225       | 76.01%  |
| 1      | 71        | 23.99%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 291       | 97.98%  |
| Unknown        | 6         | 2.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 14.85%  |
| 0x306a9    | 32        | 10.56%  |
| 0x806ea    | 20        | 6.6%    |
| 0x206a7    | 19        | 6.27%   |
| 0x306c3    | 15        | 4.95%   |
| 0x906ea    | 13        | 4.29%   |
| 0x306d4    | 13        | 4.29%   |
| 0x806ec    | 12        | 3.96%   |
| 0x40651    | 12        | 3.96%   |
| 0x806e9    | 10        | 3.3%    |
| 0x806c1    | 10        | 3.3%    |
| 0x1067a    | 10        | 3.3%    |
| 0x906e9    | 9         | 2.97%   |
| 0x406e3    | 8         | 2.64%   |
| 0x506e3    | 7         | 2.31%   |
| 0x6fd      | 5         | 1.65%   |
| 0x20655    | 4         | 1.32%   |
| 0x08108102 | 4         | 1.32%   |
| 0xa0652    | 3         | 0.99%   |
| 0x906ed    | 3         | 0.99%   |
| 0x706e5    | 3         | 0.99%   |
| 0x706a1    | 3         | 0.99%   |
| 0x406c4    | 3         | 0.99%   |
| 0x206d7    | 3         | 0.99%   |
| 0x08600106 | 3         | 0.99%   |
| 0x806d1    | 2         | 0.66%   |
| 0x30678    | 2         | 0.66%   |
| 0x0a50000c | 2         | 0.66%   |
| 0x08108109 | 2         | 0.66%   |
| 0x06003106 | 2         | 0.66%   |
| 0x906eb    | 1         | 0.33%   |
| 0x806eb    | 1         | 0.33%   |
| 0x406f1    | 1         | 0.33%   |
| 0x406c3    | 1         | 0.33%   |
| 0x40661    | 1         | 0.33%   |
| 0x306f2    | 1         | 0.33%   |
| 0x30661    | 1         | 0.33%   |
| 0x206c2    | 1         | 0.33%   |
| 0x20652    | 1         | 0.33%   |
| 0x106e5    | 1         | 0.33%   |
| 0x106ca    | 1         | 0.33%   |
| 0x106a5    | 1         | 0.33%   |
| 0x10676    | 1         | 0.33%   |
| 0x0a50000b | 1         | 0.33%   |
| 0x08701021 | 1         | 0.33%   |
| 0x08701013 | 1         | 0.33%   |
| 0x08600104 | 1         | 0.33%   |
| 0x08600103 | 1         | 0.33%   |
| 0x0810100b | 1         | 0.33%   |
| 0x07030105 | 1         | 0.33%   |
| 0x06001119 | 1         | 0.33%   |
| 0x05000119 | 1         | 0.33%   |
| 0x010000db | 1         | 0.33%   |
| 0x010000c7 | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 79        | 26.69%  |
| Haswell       | 36        | 12.16%  |
| IvyBridge     | 34        | 11.49%  |
| SandyBridge   | 24        | 8.11%   |
| Skylake       | 18        | 6.08%   |
| Broadwell     | 14        | 4.73%   |
| Zen 2         | 11        | 3.72%   |
| TigerLake     | 11        | 3.72%   |
| Penryn        | 11        | 3.72%   |
| Zen+          | 8         | 2.7%    |
| Westmere      | 7         | 2.36%   |
| Silvermont    | 7         | 2.36%   |
| Core          | 6         | 2.03%   |
| IceLake       | 4         | 1.35%   |
| Goldmont plus | 4         | 1.35%   |
| CometLake     | 4         | 1.35%   |
| Zen 3         | 3         | 1.01%   |
| Steamroller   | 2         | 0.68%   |
| Nehalem       | 2         | 0.68%   |
| K10           | 2         | 0.68%   |
| Bonnell       | 2         | 0.68%   |
| Unknown       | 2         | 0.68%   |
| Zen           | 1         | 0.34%   |
| Puma          | 1         | 0.34%   |
| Piledriver    | 1         | 0.34%   |
| Goldmont      | 1         | 0.34%   |
| Bobcat        | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 220       | 56.99%  |
| Nvidia            | 108       | 27.98%  |
| AMD               | 57        | 14.77%  |
| ASPEED Technology | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 6.14%   |
| Intel UHD Graphics 620                                                                   | 22        | 5.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 4.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 3.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 3.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 2.81%   |
| Intel HD Graphics 5500                                                                   | 11        | 2.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.56%   |
| Intel HD Graphics 620                                                                    | 8         | 2.05%   |
| AMD Renoir                                                                               | 8         | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 1.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 1.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.53%   |
| Intel HD Graphics 630                                                                    | 6         | 1.53%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.53%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 5         | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.28%   |
| Intel HD Graphics 530                                                                    | 5         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.28%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 5         | 1.28%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.02%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.02%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.02%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.02%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.02%   |
| Nvidia TU117M                                                                            | 3         | 0.77%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.77%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.77%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.77%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.77%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.77%   |
| AMD Cezanne                                                                              | 3         | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.51%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 2         | 0.51%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Max-Q]                                                | 2         | 0.51%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 0.51%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.51%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 2         | 0.51%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.51%   |
| NVIDIA GK107GLM [Quadro K1000M]                                                          | 2         | 0.51%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.51%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.51%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.51%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                                | 2         | 0.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.51%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.51%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.51%   |
| Intel Iris Plus Graphics 640                                                             | 2         | 0.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.51%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 136       | 45.95%  |
| Intel + Nvidia  | 62        | 20.95%  |
| 1 x Nvidia      | 39        | 13.18%  |
| 1 x AMD         | 30        | 10.14%  |
| Intel + AMD     | 20        | 6.76%   |
| AMD + Nvidia    | 6         | 2.03%   |
| Other           | 1         | 0.34%   |
| 2 x AMD         | 1         | 0.34%   |
| Nvidia + ASPEED | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 223       | 74.58%  |
| Proprietary | 74        | 24.75%  |
| Unknown     | 2         | 0.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 169       | 56.33%  |
| 1.01-2.0   | 53        | 17.67%  |
| 3.01-4.0   | 29        | 9.67%   |
| 0.51-1.0   | 17        | 5.67%   |
| 0.01-0.5   | 15        | 5%      |
| 7.01-8.0   | 6         | 2%      |
| 5.01-6.0   | 5         | 1.67%   |
| 8.01-16.0  | 5         | 1.67%   |
| 2.01-3.0   | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 44        | 14.06%  |
| LG Display              | 38        | 12.14%  |
| Samsung Electronics     | 37        | 11.82%  |
| AU Optronics            | 36        | 11.5%   |
| Dell                    | 35        | 11.18%  |
| Chimei Innolux          | 35        | 11.18%  |
| Sharp                   | 10        | 3.19%   |
| PANDA                   | 9         | 2.88%   |
| Goldstar                | 9         | 2.88%   |
| Lenovo                  | 6         | 1.92%   |
| LGD                     | 4         | 1.28%   |
| InfoVision              | 4         | 1.28%   |
| Hewlett-Packard         | 4         | 1.28%   |
| Apple                   | 4         | 1.28%   |
| AOC                     | 4         | 1.28%   |
| Ancor Communications    | 4         | 1.28%   |
| ViewSonic               | 3         | 0.96%   |
| Panasonic               | 3         | 0.96%   |
| Chi Mei Optoelectronics | 3         | 0.96%   |
| Sony                    | 2         | 0.64%   |
| Philips                 | 2         | 0.64%   |
| MStar                   | 2         | 0.64%   |
| BenQ                    | 2         | 0.64%   |
| ASUSTek Computer        | 2         | 0.64%   |
| Unknown (ADA)           | 1         | 0.32%   |
| RTK                     | 1         | 0.32%   |
| NEC Computers           | 1         | 0.32%   |
| LG Philips              | 1         | 0.32%   |
| LG Electronics          | 1         | 0.32%   |
| Lenovo Group Limited    | 1         | 0.32%   |
| HOP                     | 1         | 0.32%   |
| CHR                     | 1         | 0.32%   |
| CGC                     | 1         | 0.32%   |
| AUS                     | 1         | 0.32%   |
| Acer                    | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LGD LCD Monitor 1920x1080                                             | 4         | 1.26%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 4         | 1.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.26%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.26%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 3         | 0.95%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 3         | 0.95%   |
| Panasonic TV MEIC33B 1366x768 521x293mm 23.5-inch                     | 3         | 0.95%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.95%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.63%   |
| Samsung Electronics SME1720NR SAM0696 1280x1024 338x270mm 17.0-inch   | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 0.63%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.63%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 2         | 0.63%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 2         | 0.63%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 2         | 0.63%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.63%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 2         | 0.63%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 0.63%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 2         | 0.63%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.63%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                     | 2         | 0.63%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 2         | 0.63%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch       | 2         | 0.63%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                 | 2         | 0.63%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 2         | 0.63%   |
| BOE LCD Monitor BOE070D 1366x768 309x173mm 13.9-inch                  | 2         | 0.63%   |
| BOE LCD Monitor BOE06F3 1920x1080 309x173mm 13.9-inch                 | 2         | 0.63%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 0.63%   |
| BOE LCD Monitor BOE05EA 1366x768 309x173mm 13.9-inch                  | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO71ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.63%   |
| ASUSTek Computer VP249 AUS24AA 1920x1080 527x296mm 23.8-inch          | 2         | 0.63%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 1         | 0.32%   |
| ViewSonic VA2223-FHD VSC9239 1920x1080 477x268mm 21.5-inch            | 1         | 0.32%   |
| ViewSonic VA2201-FHD VSC683B 1920x1080 480x260mm 21.5-inch            | 1         | 0.32%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1         | 0.32%   |
| Sony TV SNY8E03 1920x1080                                             | 1         | 0.32%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 0.32%   |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch               | 1         | 0.32%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch               | 1         | 0.32%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.32%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.32%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.32%   |
| Sharp LCD Monitor SHP146B 3200x1800 294x165mm 13.3-inch               | 1         | 0.32%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.32%   |
| Sharp LCD Monitor SHP1420 1920x1080 294x165mm 13.3-inch               | 1         | 0.32%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch  | 1         | 0.32%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch     | 1         | 0.32%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 1         | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 0.32%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 155       | 50.82%  |
| 1366x768 (WXGA)   | 79        | 25.9%   |
| 3840x2160 (4K)    | 14        | 4.59%   |
| 1600x900 (HD+)    | 10        | 3.28%   |
| 2560x1440 (QHD)   | 9         | 2.95%   |
| 1280x1024 (SXGA)  | 8         | 2.62%   |
| 1280x800 (WXGA)   | 7         | 2.3%    |
| 1440x900 (WXGA+)  | 4         | 1.31%   |
| 1920x1200 (WUXGA) | 3         | 0.98%   |
| Unknown           | 3         | 0.98%   |
| 3200x1800 (QHD+)  | 2         | 0.66%   |
| 2560x1600         | 2         | 0.66%   |
| 3840x1080         | 1         | 0.33%   |
| 3456x2160         | 1         | 0.33%   |
| 3440x1440         | 1         | 0.33%   |
| 3286x1080         | 1         | 0.33%   |
| 2880x1800         | 1         | 0.33%   |
| 2736x1824         | 1         | 0.33%   |
| 1920x1280         | 1         | 0.33%   |
| 1360x768          | 1         | 0.33%   |
| 1024x600          | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 96        | 30.87%  |
| 13      | 45        | 14.47%  |
| 14      | 41        | 13.18%  |
| 23      | 17        | 5.47%   |
| 21      | 17        | 5.47%   |
| Unknown | 16        | 5.14%   |
| 24      | 13        | 4.18%   |
| 27      | 11        | 3.54%   |
| 18      | 10        | 3.22%   |
| 17      | 10        | 3.22%   |
| 12      | 8         | 2.57%   |
| 20      | 5         | 1.61%   |
| 19      | 5         | 1.61%   |
| 84      | 3         | 0.96%   |
| 11      | 3         | 0.96%   |
| 10      | 3         | 0.96%   |
| 52      | 1         | 0.32%   |
| 46      | 1         | 0.32%   |
| 42      | 1         | 0.32%   |
| 40      | 1         | 0.32%   |
| 34      | 1         | 0.32%   |
| 31      | 1         | 0.32%   |
| 25      | 1         | 0.32%   |
| 7       | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 173       | 55.81%  |
| 501-600     | 39        | 12.58%  |
| 401-500     | 35        | 11.29%  |
| 201-300     | 25        | 8.06%   |
| Unknown     | 16        | 5.16%   |
| 351-400     | 10        | 3.23%   |
| 601-700     | 3         | 0.97%   |
| 1501-2000   | 3         | 0.97%   |
| 1001-1500   | 2         | 0.65%   |
| 801-900     | 1         | 0.32%   |
| 701-800     | 1         | 0.32%   |
| 101-200     | 1         | 0.32%   |
| 901-1000    | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 243       | 84.97%  |
| 16/10   | 18        | 6.29%   |
| Unknown | 15        | 5.24%   |
| 5/4     | 6         | 2.1%    |
| 3/2     | 3         | 1.05%   |
| 21/9    | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 95        | 30.45%  |
| 81-90          | 77        | 24.68%  |
| 201-250        | 41        | 13.14%  |
| Unknown        | 16        | 5.13%   |
| 151-200        | 15        | 4.81%   |
| 141-150        | 13        | 4.17%   |
| 301-350        | 11        | 3.53%   |
| 71-80          | 10        | 3.21%   |
| 61-70          | 7         | 2.24%   |
| 121-130        | 5         | 1.6%    |
| More than 1000 | 4         | 1.28%   |
| 251-300        | 4         | 1.28%   |
| 51-60          | 3         | 0.96%   |
| 41-50          | 3         | 0.96%   |
| 501-1000       | 3         | 0.96%   |
| 351-500        | 2         | 0.64%   |
| 1-40           | 1         | 0.32%   |
| 131-140        | 1         | 0.32%   |
| 91-100         | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 115       | 37.7%   |
| 101-120       | 84        | 27.54%  |
| 51-100        | 66        | 21.64%  |
| 161-240       | 17        | 5.57%   |
| Unknown       | 16        | 5.25%   |
| More than 240 | 5         | 1.64%   |
| 1-50          | 2         | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 257       | 85.67%  |
| 2     | 31        | 10.33%  |
| 0     | 9         | 3%      |
| 3     | 3         | 1%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 173       | 37.45%  |
| Intel                                  | 149       | 32.25%  |
| Qualcomm Atheros                       | 63        | 13.64%  |
| Broadcom                               | 26        | 5.63%   |
| Ralink Technology                      | 8         | 1.73%   |
| Marvell Technology Group               | 6         | 1.3%    |
| Broadcom Limited                       | 6         | 1.3%    |
| MediaTek                               | 5         | 1.08%   |
| ASIX Electronics                       | 4         | 0.87%   |
| TP-Link                                | 3         | 0.65%   |
| D-Link                                 | 3         | 0.65%   |
| Samsung Electronics                    | 2         | 0.43%   |
| Ralink                                 | 2         | 0.43%   |
| Hewlett-Packard                        | 2         | 0.43%   |
| Xiaomi                                 | 1         | 0.22%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.22%   |
| Qualcomm Atheros Communications        | 1         | 0.22%   |
| Qualcomm                               | 1         | 0.22%   |
| ICS Advent                             | 1         | 0.22%   |
| Huawei Technologies                    | 1         | 0.22%   |
| Foxconn / Hon Hai                      | 1         | 0.22%   |
| Ericsson Business Mobile Networks      | 1         | 0.22%   |
| Edimax Technology                      | 1         | 0.22%   |
| ASUSTek Computer                       | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 129       | 24.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 4.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 2.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12        | 2.26%   |
| Intel Wireless 7265                                               | 12        | 2.26%   |
| Intel Wireless 3165                                               | 12        | 2.26%   |
| Intel Wireless 8265 / 8275                                        | 11        | 2.07%   |
| Broadcom BCM43142 802.11b/g/n                                     | 11        | 2.07%   |
| Intel Wireless 7260                                               | 9         | 1.69%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8         | 1.5%    |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.5%    |
| Intel Centrino Ultimate-N 6300                                    | 6         | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 0.94%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.75%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.75%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.75%   |
| Intel Wireless 8260                                               | 4         | 0.75%   |
| Intel Wireless 3160                                               | 4         | 0.75%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.56%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.56%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 3         | 0.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.56%   |
| ASIX AX88772A Fast Ethernet                                       | 3         | 0.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.38%   |
| Realtek 802.11ac NIC                                              | 2         | 0.38%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.38%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.38%   |
| Intel Wireless-AC 9260                                            | 2         | 0.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.38%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.38%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 120       | 46.33%  |
| Qualcomm Atheros                | 51        | 19.69%  |
| Realtek Semiconductor           | 35        | 13.51%  |
| Broadcom                        | 22        | 8.49%   |
| Ralink Technology               | 8         | 3.09%   |
| Broadcom Limited                | 6         | 2.32%   |
| MEDIATEK                        | 4         | 1.54%   |
| TP-Link                         | 3         | 1.16%   |
| D-Link                          | 3         | 1.16%   |
| Ralink                          | 2         | 0.77%   |
| Xiaomi                          | 1         | 0.39%   |
| Qualcomm Atheros Communications | 1         | 0.39%   |
| Marvell Technology Group        | 1         | 0.39%   |
| Edimax Technology               | 1         | 0.39%   |
| ASUSTek Computer                | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 5.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 4.63%   |
| Intel Wireless 7265                                                     | 12        | 4.63%   |
| Intel Wireless 3165                                                     | 12        | 4.63%   |
| Intel Wireless 8265 / 8275                                              | 11        | 4.25%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 4.25%   |
| Intel Wireless 7260                                                     | 9         | 3.47%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 3.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 3.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 3.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 3.09%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 3.09%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 2.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.54%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.54%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.54%   |
| Intel Wireless 8260                                                     | 4         | 1.54%   |
| Intel Wireless 3160                                                     | 4         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.16%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 3         | 1.16%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.16%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.77%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.77%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.77%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.77%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.77%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.77%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.77%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                          | 2         | 0.77%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.77%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 0.77%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                       | 1         | 0.39%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 1         | 0.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.39%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.39%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.39%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.39%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.39%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.39%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.39%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.39%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 1         | 0.39%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.39%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 161       | 60.53%  |
| Intel                                  | 64        | 24.06%  |
| Qualcomm Atheros                       | 17        | 6.39%   |
| Broadcom                               | 6         | 2.26%   |
| Marvell Technology Group               | 5         | 1.88%   |
| ASIX Electronics                       | 4         | 1.5%    |
| Samsung Electronics                    | 2         | 0.75%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.38%   |
| Qualcomm                               | 1         | 0.38%   |
| MediaTek                               | 1         | 0.38%   |
| ICS Advent                             | 1         | 0.38%   |
| Huawei Technologies                    | 1         | 0.38%   |
| Hewlett-Packard                        | 1         | 0.38%   |
| Foxconn / Hon Hai                      | 1         | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 129       | 47.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 26        | 9.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 5.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 1.85%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.85%   |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 1.48%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 1.48%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 1.11%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.11%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.11%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.11%   |
| ASIX AX88772A Fast Ethernet                                                    | 3         | 1.11%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.74%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.74%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.74%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.74%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.74%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 0.74%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.74%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express                          | 2         | 0.74%   |
| Sony Ericsson Mobile AB D6503                                                  | 1         | 0.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.37%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.37%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.37%   |
| Qualcomm Redmi 9T                                                              | 1         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.37%   |
| MediaTek WP7                                                                   | 1         | 0.37%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.37%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 1         | 0.37%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.37%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 0.37%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.37%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.37%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.37%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.37%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.37%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.37%   |
| Intel 82575EB Gigabit Network Connection                                       | 1         | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.37%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.37%   |
| Intel 82562V-2 10/100 Network Connection                                       | 1         | 0.37%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.37%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.37%   |
| Huawei HUAWEI                                                                  | 1         | 0.37%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.37%   |
| Foxconn / Hon Hai Nokia 7.1                                                    | 1         | 0.37%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 1         | 0.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 253       | 50.2%   |
| WiFi     | 249       | 49.4%   |
| Modem    | 2         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 222       | 59.36%  |
| Ethernet | 151       | 40.37%  |
| Modem    | 1         | 0.27%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 190       | 64.19%  |
| 1     | 99        | 33.45%  |
| 3     | 4         | 1.35%   |
| 0     | 3         | 1.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 242       | 80.4%   |
| Yes  | 59        | 19.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 98        | 45.16%  |
| Qualcomm Atheros Communications | 29        | 13.36%  |
| Broadcom                        | 19        | 8.76%   |
| Realtek Semiconductor           | 18        | 8.29%   |
| Cambridge Silicon Radio         | 15        | 6.91%   |
| IMC Networks                    | 11        | 5.07%   |
| Lite-On Technology              | 9         | 4.15%   |
| Apple                           | 5         | 2.3%    |
| Hewlett-Packard                 | 4         | 1.84%   |
| Foxconn / Hon Hai               | 3         | 1.38%   |
| Dell                            | 2         | 0.92%   |
| Toshiba                         | 1         | 0.46%   |
| Marvell Semiconductor           | 1         | 0.46%   |
| Conwise Technology              | 1         | 0.46%   |
| Alps Electric                   | 1         | 0.46%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 48        | 22.12%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 8.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 16        | 7.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 6.91%   |
| Realtek Bluetooth Radio                             | 13        | 5.99%   |
| Intel AX201 Bluetooth                               | 13        | 5.99%   |
| Intel AX200 Bluetooth                               | 9         | 4.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 2.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 2.3%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 1.84%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 1.84%   |
| Apple Bluetooth Host Controller                     | 4         | 1.84%   |
| Realtek 802.11n WLAN Adapter                        | 3         | 1.38%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.38%   |
| IMC Networks Wireless_Device                        | 3         | 1.38%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.38%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 1.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.92%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.92%   |
| Intel Bluetooth Device                              | 2         | 0.92%   |
| Intel AX210 Bluetooth                               | 2         | 0.92%   |
| IMC Networks Bluetooth Device                       | 2         | 0.92%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.92%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.92%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.92%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.46%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.46%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.46%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.46%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.46%   |
| Lite-On Bluetooth Radio                             | 1         | 0.46%   |
| Lite-On BCM43142A0                                  | 1         | 0.46%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.46%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.46%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.46%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.46%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.46%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.46%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.46%   |
| Conwise CW6622                                      | 1         | 0.46%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 0.46%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.46%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.46%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.46%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.46%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 260       | 67.89%  |
| Nvidia                   | 67        | 17.49%  |
| AMD                      | 40        | 10.44%  |
| Creative Labs            | 3         | 0.78%   |
| C-Media Electronics      | 3         | 0.78%   |
| Generalplus Technology   | 2         | 0.52%   |
| Realtek Semiconductor    | 1         | 0.26%   |
| Plantronics              | 1         | 0.26%   |
| OPPO Electronics         | 1         | 0.26%   |
| Nordic Semiconductor ASA | 1         | 0.26%   |
| JMTek                    | 1         | 0.26%   |
| GYROCOM C&C              | 1         | 0.26%   |
| GN Netcom                | 1         | 0.26%   |
| Unknown                  | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 44        | 9.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 6.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 5.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 20        | 4.47%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 4.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 19        | 4.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 2.91%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 2.91%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 2.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 2.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 2.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 2.24%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 8         | 1.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 1.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.34%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.34%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.34%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.12%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.89%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.89%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.89%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.89%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.67%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.67%   |
| Nvidia Audio device                                                                               | 3         | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.67%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.67%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.67%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.45%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 0.45%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.45%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.45%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 2         | 0.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.45%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 0.45%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.45%   |
| Generalplus Technology Usb Audio Device                                                           | 2         | 0.45%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.45%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.45%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.22%   |
| Plantronics Blackwire 5220 Series                                                                 | 1         | 0.22%   |
| OPPO Electronics Electronics Multimedia audio controller                                          | 1         | 0.22%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 55        | 25.94%  |
| SK Hynix            | 41        | 19.34%  |
| Kingston            | 36        | 16.98%  |
| Micron Technology   | 23        | 10.85%  |
| Corsair             | 12        | 5.66%   |
| Unknown             | 10        | 4.72%   |
| Ramaxel Technology  | 7         | 3.3%    |
| G.Skill             | 7         | 3.3%    |
| Crucial             | 7         | 3.3%    |
| Kingmax             | 4         | 1.89%   |
| Elpida              | 3         | 1.42%   |
| A-DATA Technology   | 3         | 1.42%   |
| Team                | 2         | 0.94%   |
| Unknown (7FE0)      | 1         | 0.47%   |
| Apacer              | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 2.62%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 1.75%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s     | 4         | 1.75%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s     | 4         | 1.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 4         | 1.75%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s     | 4         | 1.75%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 1.31%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 3         | 1.31%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 3         | 1.31%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 2         | 0.87%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 2         | 0.87%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.87%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 0.87%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 2         | 0.87%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s   | 2         | 0.87%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 2         | 0.87%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s               | 2         | 0.87%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 2         | 0.87%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.87%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 0.87%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s       | 2         | 0.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.87%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 0.87%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 2         | 0.87%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 2         | 0.87%   |
| Kingston RAM 99U5428-040.A01LF 4096MB SODIMM DDR3 1334MT/s   | 2         | 0.87%   |
| G.Skill RAM F4-2666C19-8GRS 8GB SODIMM DDR4 2667MT/s         | 2         | 0.87%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s        | 2         | 0.87%   |
| Crucial RAM CT4G4SFS824A.C8FF 4GB SODIMM DDR4 2400MT/s       | 2         | 0.87%   |
| Corsair RAM CMK8GX4M1A2666C16 8192MB DIMM DDR4 3000MT/s      | 2         | 0.87%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s               | 1         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 0.44%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                 | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR3                        | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 200MT/s                  | 1         | 0.44%   |
| Unknown RAM Module 1024MB DIMM DDR 133MT/s                   | 1         | 0.44%   |
| Unknown RAM BAPC08G3000D4T8 8192MB DIMM DDR4 2133MT/s        | 1         | 0.44%   |
| Unknown (7FE0) RAM Module 8192MB SODIMM DDR4 2400MT/s        | 1         | 0.44%   |
| Team RAM TEAMGROUP-UD3-160 4096MB DIMM DDR3 1333MT/s         | 1         | 0.44%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 1         | 0.44%   |
| SK Hynix RAM SNOAMOO Ltd:016M00 4096MB DIMM DDR3 1600MT/s    | 1         | 0.44%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2667MT/s                 | 1         | 0.44%   |
| SK Hynix RAM Module 4GB SODIMM DDR4 2133MT/s                 | 1         | 0.44%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1867MT/s              | 1         | 0.44%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 0.44%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2400MT/s             | 1         | 0.44%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s          | 1         | 0.44%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1         | 0.44%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.44%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.44%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2048MB DIMM DDR3 1600MT/s      | 1         | 0.44%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1         | 0.44%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 1         | 0.44%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s    | 1         | 0.44%   |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s         | 1         | 0.44%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s   | 1         | 0.44%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 1         | 0.44%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 87        | 51.48%  |
| DDR3    | 66        | 39.05%  |
| LPDDR4  | 4         | 2.37%   |
| LPDDR3  | 4         | 2.37%   |
| DDR2    | 4         | 2.37%   |
| Unknown | 2         | 1.18%   |
| SDRAM   | 1         | 0.59%   |
| DDR     | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 119       | 70.41%  |
| DIMM         | 42        | 24.85%  |
| Row Of Chips | 8         | 4.73%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 74        | 40.44%  |
| 8192  | 71        | 38.8%   |
| 16384 | 18        | 9.84%   |
| 2048  | 13        | 7.1%    |
| 1024  | 6         | 3.28%   |
| 32768 | 1         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 49        | 25.93%  |
| 2667    | 41        | 21.69%  |
| 3200    | 25        | 13.23%  |
| 2400    | 19        | 10.05%  |
| 1333    | 13        | 6.88%   |
| 2133    | 8         | 4.23%   |
| 1867    | 6         | 3.17%   |
| 1334    | 6         | 3.17%   |
| 3000    | 3         | 1.59%   |
| 800     | 3         | 1.59%   |
| 2800    | 2         | 1.06%   |
| 667     | 2         | 1.06%   |
| 4267    | 1         | 0.53%   |
| 4199    | 1         | 0.53%   |
| 3466    | 1         | 0.53%   |
| 3334    | 1         | 0.53%   |
| 3266    | 1         | 0.53%   |
| 3007    | 1         | 0.53%   |
| 2666    | 1         | 0.53%   |
| 1866    | 1         | 0.53%   |
| 1067    | 1         | 0.53%   |
| 200     | 1         | 0.53%   |
| 133     | 1         | 0.53%   |
| Unknown | 1         | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Ricoh           | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Ricoh Printing Support   | 1         | 50%     |
| HP LaserJet P3010 Series | 1         | 50%     |

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
| Chicony Electronics                    | 44        | 22%     |
| Microdia                               | 27        | 13.5%   |
| IMC Networks                           | 24        | 12%     |
| Sunplus Innovation Technology          | 22        | 11%     |
| Realtek Semiconductor                  | 18        | 9%      |
| Acer                                   | 12        | 6%      |
| Quanta                                 | 8         | 4%      |
| Syntek                                 | 7         | 3.5%    |
| Logitech                               | 7         | 3.5%    |
| Lite-On Technology                     | 6         | 3%      |
| Suyin                                  | 5         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2%      |
| Apple                                  | 4         | 2%      |
| Silicon Motion                         | 2         | 1%      |
| Ricoh                                  | 2         | 1%      |
| Sonix Technology                       | 1         | 0.5%    |
| Luxvisions Innotech Limited            | 1         | 0.5%    |
| Lenovo                                 | 1         | 0.5%    |
| KYE Systems (Mouse Systems)            | 1         | 0.5%    |
| Intel                                  | 1         | 0.5%    |
| IDS Imaging Development Systems        | 1         | 0.5%    |
| Denron                                 | 1         | 0.5%    |
| Alcor Micro                            | 1         | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD        | 12        | 5.97%   |
| Sunplus Integrated_Webcam_HD         | 11        | 5.47%   |
| Chicony Integrated Camera            | 9         | 4.48%   |
| Realtek Integrated_Webcam_HD         | 7         | 3.48%   |
| Microdia Laptop_Integrated_Webcam_HD | 7         | 3.48%   |
| IMC Networks USB2.0 VGA UVC WebCam   | 6         | 2.99%   |
| IMC Networks Integrated Camera       | 6         | 2.99%   |
| Chicony HD WebCam                    | 6         | 2.99%   |
| Chicony HP HD Camera                 | 5         | 2.49%   |
| Syntek Integrated Camera             | 4         | 1.99%   |
| Realtek Integrated Webcam            | 4         | 1.99%   |
| Logitech Webcam C270                 | 4         | 1.99%   |
| IMC Networks USB2.0 HD UVC WebCam    | 4         | 1.99%   |
| Chicony HP TrueVision HD Camera      | 4         | 1.99%   |
| Acer ThinkPad Integrated Camera      | 4         | 1.99%   |
| Sunplus Laptop_Integrated_Webcam_FHD | 3         | 1.49%   |
| IMC Networks VGA UVC WebCam          | 3         | 1.49%   |
| Chicony HP HD Webcam                 | 3         | 1.49%   |
| Acer Integrated Camera               | 3         | 1.49%   |
| Syntek Lenovo EasyCamera             | 2         | 1%      |
| Suyin Laptop_Integrated_Webcam_HD    | 2         | 1%      |
| Realtek Integrated Webcam HD         | 2         | 1%      |
| Quanta VGA WebCam                    | 2         | 1%      |
| Quanta HP TrueVision HD Camera       | 2         | 1%      |
| Quanta HP HD Camera                  | 2         | 1%      |
| Microdia Integrated Webcam HD        | 2         | 1%      |
| Microdia Integrated Webcam           | 2         | 1%      |
| Lite-On Integrated Camera            | 2         | 1%      |
| Lite-On HP HD Camera                 | 2         | 1%      |
| IMC Networks USB2.0 UVC HD Webcam    | 2         | 1%      |
| IMC Networks USB Camera              | 2         | 1%      |
| Chicony USB2.0 VGA UVC WebCam        | 2         | 1%      |
| Chicony TOSHIBA Web Camera - HD      | 2         | 1%      |
| Chicony Integrated HP HD Webcam      | 2         | 1%      |
| Apple iPhone 5/5C/5S/6/SE            | 2         | 1%      |
| Apple FaceTime HD Camera             | 2         | 1%      |
| Acer SunplusIT Integrated Camera     | 2         | 1%      |
| Syntek USB Video Device              | 1         | 0.5%    |
| Suyin HP webcam [dv6-1190en]         | 1         | 0.5%    |
| Suyin Acer/Lenovo Webcam [CN0316]    | 1         | 0.5%    |
| Suyin Acer CrystalEye Webcam         | 1         | 0.5%    |
| Sunplus Laptop_Integrated_Webcam_HD  | 1         | 0.5%    |
| Sunplus Laptop Integrated WebCam HD  | 1         | 0.5%    |
| Sunplus Integrated_Webcam_FHD        | 1         | 0.5%    |
| Sunplus HP TrueVision HD Camera      | 1         | 0.5%    |
| Sunplus HD WebCam                    | 1         | 0.5%    |
| Sunplus HD User Facing               | 1         | 0.5%    |
| Sunplus Dell Integrated Webcam       | 1         | 0.5%    |
| Sunplus ASUS USB2.0 Webcam           | 1         | 0.5%    |
| Sonix USB2.0 HD UVC WebCam           | 1         | 0.5%    |
| Silicon Motion WebCam SCB-0385N      | 1         | 0.5%    |
| Silicon Motion WebCam SC-03FFL11939N | 1         | 0.5%    |
| Ricoh Sony Vaio Integrated Webcam    | 1         | 0.5%    |
| Ricoh HD Webcam                      | 1         | 0.5%    |
| Realtek USB2.0 VGA UVC WebCam        | 1         | 0.5%    |
| Realtek USB2.0 HD UVC WebCam         | 1         | 0.5%    |
| Realtek USB2.0 camera                | 1         | 0.5%    |
| Realtek USB Camera                   | 1         | 0.5%    |
| Realtek HD WebCam                    | 1         | 0.5%    |
| Quanta HD Webcam                     | 1         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 30        | 58.82%  |
| Synaptics                  | 9         | 17.65%  |
| Shenzhen Goodix Technology | 6         | 11.76%  |
| LighTuning Technology      | 2         | 3.92%   |
| Elan Microelectronics      | 2         | 3.92%   |
| Upek                       | 1         | 1.96%   |
| STMicroelectronics         | 1         | 1.96%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 13.73%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 9.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 7.84%   |
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 7.84%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 5.88%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.88%   |
| Unknown                                                                    | 3         | 5.88%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.92%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.92%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.92%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.92%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 3.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.92%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.92%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.96%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.96%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.96%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.96%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.96%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.96%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.96%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 75%     |
| Upek        | 1         | 12.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 3         | 37.5%   |
| Broadcom 5880                                              | 2         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 12.5%   |
| Broadcom 58200                                             | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 206       | 68.67%  |
| 1     | 80        | 26.67%  |
| 2     | 10        | 3.33%   |
| 3     | 3         | 1%      |
| 5     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 46.36%  |
| Graphics card            | 15        | 13.64%  |
| Net/wireless             | 12        | 10.91%  |
| Chipcard                 | 8         | 7.27%   |
| Communication controller | 5         | 4.55%   |
| Net/ethernet             | 4         | 3.64%   |
| Multimedia controller    | 3         | 2.73%   |
| Camera                   | 3         | 2.73%   |
| Bluetooth                | 3         | 2.73%   |
| Unassigned class         | 2         | 1.82%   |
| Card reader              | 2         | 1.82%   |
| Storage                  | 1         | 0.91%   |
| Sound                    | 1         | 0.91%   |
