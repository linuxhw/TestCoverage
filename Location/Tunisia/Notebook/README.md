Linux in Tunisia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Tunisia.

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

Total: 153

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | Latitude 3540               | [a97573f3cf](https://linux-hardware.org/?probe=a97573f3cf) | Apr 29, 2022 |
| Dell      | Latitude 3540               | [a6b8509194](https://linux-hardware.org/?probe=a6b8509194) | Apr 29, 2022 |
| Toshiba   | Satellite Pro L850-B339     | [d884eeae8f](https://linux-hardware.org/?probe=d884eeae8f) | Apr 20, 2022 |
| Lenovo    | IdeaPad L3 15IML05 81Y3     | [03b34db583](https://linux-hardware.org/?probe=03b34db583) | Apr 05, 2022 |
| Lenovo    | IdeaPad L3 15IML05 81Y3     | [53a2862e30](https://linux-hardware.org/?probe=53a2862e30) | Apr 04, 2022 |
| Lenovo    | IdeaPad L3 15IML05 81Y3     | [e7a152d30a](https://linux-hardware.org/?probe=e7a152d30a) | Apr 04, 2022 |
| ASUSTek   | X550LC                      | [30ed5cb046](https://linux-hardware.org/?probe=30ed5cb046) | Apr 03, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [7c0d1ce382](https://linux-hardware.org/?probe=7c0d1ce382) | Mar 29, 2022 |
| MSI       | Katana GF66 12UC            | [bc07a3de3d](https://linux-hardware.org/?probe=bc07a3de3d) | Mar 15, 2022 |
| MSI       | Katana GF66 12UC            | [ddbc85ab3a](https://linux-hardware.org/?probe=ddbc85ab3a) | Mar 15, 2022 |
| ASUSTek   | ROG Strix G713QE_G713QE     | [4b2b4e7f5a](https://linux-hardware.org/?probe=4b2b4e7f5a) | Mar 10, 2022 |
| ASUSTek   | X550LC                      | [267fa2ca76](https://linux-hardware.org/?probe=267fa2ca76) | Mar 06, 2022 |
| Lenovo    | IdeaPad Gaming 3 15IMH05... | [7803f9b898](https://linux-hardware.org/?probe=7803f9b898) | Feb 24, 2022 |
| ASUSTek   | X553MA                      | [020df21e37](https://linux-hardware.org/?probe=020df21e37) | Feb 23, 2022 |
| Lenovo    | IdeaPad 100-15IBD 80QQ      | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Lenovo    | IdeaPad 120S-11IAP 81A4     | [49a3015875](https://linux-hardware.org/?probe=49a3015875) | Feb 10, 2022 |
| HP        | Pavilion dv7                | [3bd981aa35](https://linux-hardware.org/?probe=3bd981aa35) | Feb 09, 2022 |
| ASUSTek   | ASUS EXPERTBOOK B1500CEP... | [f814537586](https://linux-hardware.org/?probe=f814537586) | Feb 08, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [09caab8240](https://linux-hardware.org/?probe=09caab8240) | Feb 07, 2022 |
| Lenovo    | ThinkPad X1 Carbon 5th 2... | [75acdd40a6](https://linux-hardware.org/?probe=75acdd40a6) | Feb 07, 2022 |
| ASUSTek   | X553MA                      | [06f3844911](https://linux-hardware.org/?probe=06f3844911) | Jan 30, 2022 |
| ASUSTek   | X555LD                      | [0665a1599c](https://linux-hardware.org/?probe=0665a1599c) | Jan 26, 2022 |
| ASUSTek   | TUF Gaming FX705DD_TUF70... | [22dd608151](https://linux-hardware.org/?probe=22dd608151) | Jan 07, 2022 |
| ASUSTek   | TUF Gaming FX705DD_TUF70... | [391458138f](https://linux-hardware.org/?probe=391458138f) | Jan 07, 2022 |
| HP        | EliteBook 8740w             | [6f583dfeaf](https://linux-hardware.org/?probe=6f583dfeaf) | Dec 27, 2021 |
| Acer      | Aspire 5742                 | [45a5de08c7](https://linux-hardware.org/?probe=45a5de08c7) | Dec 25, 2021 |
| HP        | Notebook                    | [032be84586](https://linux-hardware.org/?probe=032be84586) | Dec 09, 2021 |
| Toshiba   | Satellite C50-A489          | [4d29ea3b9c](https://linux-hardware.org/?probe=4d29ea3b9c) | Dec 04, 2021 |
| Lenovo    | ThinkPad X240 20AMA0WRFR    | [13fe3346fd](https://linux-hardware.org/?probe=13fe3346fd) | Dec 02, 2021 |
| Samsung   | 530U3BI/530U4BI/530U4BH     | [d0a08a7a23](https://linux-hardware.org/?probe=d0a08a7a23) | Nov 22, 2021 |
| Samsung   | 530U3BI/530U4BI/530U4BH     | [507c380abb](https://linux-hardware.org/?probe=507c380abb) | Nov 22, 2021 |
| Acer      | Aspire A315-51              | [d49eff3d64](https://linux-hardware.org/?probe=d49eff3d64) | Nov 21, 2021 |
| Lenovo    | ThinkPad E15 20RD001SFE     | [358e3547b9](https://linux-hardware.org/?probe=358e3547b9) | Nov 17, 2021 |
| Lenovo    | ThinkPad E15 20RD001SFE     | [694f05492e](https://linux-hardware.org/?probe=694f05492e) | Nov 17, 2021 |
| HP        | Compaq 6735s                | [6571a6fe6d](https://linux-hardware.org/?probe=6571a6fe6d) | Nov 15, 2021 |
| HP        | ProBook 440 G7              | [35b6f85a28](https://linux-hardware.org/?probe=35b6f85a28) | Nov 10, 2021 |
| ASUSTek   | ASUS EXPERTBOOK B1400CEP... | [4bc0687791](https://linux-hardware.org/?probe=4bc0687791) | Nov 08, 2021 |
| HP        | Pavilion dv6                | [dcd2956978](https://linux-hardware.org/?probe=dcd2956978) | Nov 05, 2021 |
| HP        | Pavilion dv6                | [a509e62c95](https://linux-hardware.org/?probe=a509e62c95) | Nov 05, 2021 |
| Lenovo    | G50-70 20351                | [60e3fe1197](https://linux-hardware.org/?probe=60e3fe1197) | Oct 26, 2021 |
| ASUSTek   | TUF Gaming FX506LU_FX506... | [8f6efb8dbe](https://linux-hardware.org/?probe=8f6efb8dbe) | Oct 24, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [9b0872b3d4](https://linux-hardware.org/?probe=9b0872b3d4) | Oct 22, 2021 |
| Lenovo    | IdeaPad Gaming 3 15ARH05... | [9b74440deb](https://linux-hardware.org/?probe=9b74440deb) | Oct 07, 2021 |
| Acer      | Swift SF514-53T             | [e97a52d3d9](https://linux-hardware.org/?probe=e97a52d3d9) | Sep 28, 2021 |
| HP        | 250 G4                      | [b5177b1c13](https://linux-hardware.org/?probe=b5177b1c13) | Sep 08, 2021 |
| HP        | 250 G4                      | [32899cab30](https://linux-hardware.org/?probe=32899cab30) | Sep 08, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [d4cdb976c2](https://linux-hardware.org/?probe=d4cdb976c2) | Aug 20, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [633e5a9649](https://linux-hardware.org/?probe=633e5a9649) | Aug 20, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [6339cd2e5b](https://linux-hardware.org/?probe=6339cd2e5b) | Aug 17, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [58fb87de66](https://linux-hardware.org/?probe=58fb87de66) | Aug 02, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [8d891b7431](https://linux-hardware.org/?probe=8d891b7431) | Aug 02, 2021 |
| HP        | 250 G7 Notebook PC          | [726ed18d47](https://linux-hardware.org/?probe=726ed18d47) | Jul 25, 2021 |
| ASUSTek   | TUF Gaming FX506LU_FX506... | [a347415235](https://linux-hardware.org/?probe=a347415235) | Jul 19, 2021 |
| Lenovo    | IdeaPad 100-15IBD 80QQ      | [236639a923](https://linux-hardware.org/?probe=236639a923) | Jul 16, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [98862925dc](https://linux-hardware.org/?probe=98862925dc) | Jul 06, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [b6ce3d213a](https://linux-hardware.org/?probe=b6ce3d213a) | Jul 06, 2021 |
| MSI       | GF65 Thin 10UE              | [af8d7a6b6f](https://linux-hardware.org/?probe=af8d7a6b6f) | Jun 22, 2021 |
| Lenovo    | IdeaPad 100-15IBD 80QQ      | [9a767f85c2](https://linux-hardware.org/?probe=9a767f85c2) | May 17, 2021 |
| Dell      | Inspiron 5570               | [fe125a0b5f](https://linux-hardware.org/?probe=fe125a0b5f) | May 10, 2021 |
| Lenovo    | IdeaPad 130-15IKB 81H7      | [89cfbb6a0e](https://linux-hardware.org/?probe=89cfbb6a0e) | May 01, 2021 |
| Lenovo    | IdeaPad L340-15IRH Gamin... | [884b3d6f69](https://linux-hardware.org/?probe=884b3d6f69) | Apr 21, 2021 |
| Lenovo    | V15-IIL 82C5                | [50e1fa29fb](https://linux-hardware.org/?probe=50e1fa29fb) | Apr 16, 2021 |
| ASUSTek   | TUF Gaming FX505DY_TUF50... | [be7a218721](https://linux-hardware.org/?probe=be7a218721) | Apr 12, 2021 |
| Dell      | Latitude E6420              | [901b94b26d](https://linux-hardware.org/?probe=901b94b26d) | Mar 10, 2021 |
| Dell      | Latitude E6420              | [c0d9f82152](https://linux-hardware.org/?probe=c0d9f82152) | Mar 10, 2021 |
| Dell      | Latitude E5440              | [89089cf0ad](https://linux-hardware.org/?probe=89089cf0ad) | Mar 05, 2021 |
| Lenovo    | IdeaPad 330S-14AST 81F8     | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Lenovo    | IdeaPad L340-15IRH Gamin... | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| ASUSTek   | VivoBook_ASUSLaptop X509... | [347d45179a](https://linux-hardware.org/?probe=347d45179a) | Jan 30, 2021 |
| Acer      | Aspire V5-561G              | [4829da6130](https://linux-hardware.org/?probe=4829da6130) | Jan 30, 2021 |
| Dell      | Latitude 7410               | [19e75431d4](https://linux-hardware.org/?probe=19e75431d4) | Jan 30, 2021 |
| Samsung   | 300E5EV/300E4EV/270E5EV/... | [07f0354547](https://linux-hardware.org/?probe=07f0354547) | Jan 29, 2021 |
| Dell      | Inspiron N5110              | [5b18be0dd0](https://linux-hardware.org/?probe=5b18be0dd0) | Jan 28, 2021 |
| Lenovo    | IdeaPad L340-15IRH Gamin... | [304fa83224](https://linux-hardware.org/?probe=304fa83224) | Jan 21, 2021 |
| Lenovo    | IdeaPad L340-15IRH Gamin... | [09c2da07b2](https://linux-hardware.org/?probe=09c2da07b2) | Jan 21, 2021 |
| Lenovo    | IdeaPad 320-15IKB 81BT      | [cb1f74adbd](https://linux-hardware.org/?probe=cb1f74adbd) | Jan 17, 2021 |
| Lenovo    | IdeaPad 320-15IKB 81BT      | [f4c57eb290](https://linux-hardware.org/?probe=f4c57eb290) | Jan 17, 2021 |
| HP        | Laptop 15-bs0xx             | [95610ff17c](https://linux-hardware.org/?probe=95610ff17c) | Jan 14, 2021 |
| Dell      | Inspiron 3520               | [c1e7a232e0](https://linux-hardware.org/?probe=c1e7a232e0) | Dec 29, 2020 |
| eMachines | E725                        | [aa660241b3](https://linux-hardware.org/?probe=aa660241b3) | Dec 22, 2020 |
| Dell      | Latitude 7490               | [d42995d26a](https://linux-hardware.org/?probe=d42995d26a) | Dec 21, 2020 |
| MSI       | GF63 Thin 10SCXR            | [f52e267cc9](https://linux-hardware.org/?probe=f52e267cc9) | Dec 19, 2020 |
| Lenovo    | IdeaPad 330-15AST 81D6      | [e4ab77e8b0](https://linux-hardware.org/?probe=e4ab77e8b0) | Dec 11, 2020 |
| Lenovo    | ThinkPad E15 20RD001QFE     | [d02175d76c](https://linux-hardware.org/?probe=d02175d76c) | Dec 10, 2020 |
| ASUSTek   | UX310UQK                    | [bb566782bc](https://linux-hardware.org/?probe=bb566782bc) | Dec 04, 2020 |
| Toshiba   | Satellite A300              | [963065205e](https://linux-hardware.org/?probe=963065205e) | Nov 26, 2020 |
| Toshiba   | Satellite A300              | [c1aeee5a95](https://linux-hardware.org/?probe=c1aeee5a95) | Nov 26, 2020 |
| ASUSTek   | X550VX                      | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo    | ThinkPad X1 Extreme 20MF... | [563be9ddd8](https://linux-hardware.org/?probe=563be9ddd8) | Nov 21, 2020 |
| Lenovo    | IdeaPad S145-15AST 81N3     | [59de1f8260](https://linux-hardware.org/?probe=59de1f8260) | Nov 20, 2020 |
| Dell      | Inspiron N5110              | [64cce3acaa](https://linux-hardware.org/?probe=64cce3acaa) | Nov 04, 2020 |
| Lenovo    | IdeaPad 130-15IKB 81H7      | [97dee881c4](https://linux-hardware.org/?probe=97dee881c4) | Nov 01, 2020 |
| Dell      | Inspiron 3593               | [a236e15c5d](https://linux-hardware.org/?probe=a236e15c5d) | Oct 25, 2020 |
| Acer      | Swift SF314-52              | [f81c8f31d1](https://linux-hardware.org/?probe=f81c8f31d1) | Oct 10, 2020 |
| Acer      | Swift SF314-52              | [bb4464e5f1](https://linux-hardware.org/?probe=bb4464e5f1) | Oct 10, 2020 |
| Dell      | Latitude 7480               | [7bf6a7c3a4](https://linux-hardware.org/?probe=7bf6a7c3a4) | Sep 16, 2020 |
| ASUSTek   | UX360CA                     | [9d6a79d7ac](https://linux-hardware.org/?probe=9d6a79d7ac) | Jun 11, 2020 |
| ASUSTek   | UX360CA                     | [24742e9ec9](https://linux-hardware.org/?probe=24742e9ec9) | Jun 11, 2020 |
| Toshiba   | Satellite L500              | [1cb682ea0f](https://linux-hardware.org/?probe=1cb682ea0f) | Jun 06, 2020 |
| Toshiba   | Satellite L550              | [31501ab61b](https://linux-hardware.org/?probe=31501ab61b) | May 11, 2020 |
| Toshiba   | Satellite L550              | [b8e2396d82](https://linux-hardware.org/?probe=b8e2396d82) | May 11, 2020 |
| Lenovo    | IdeaPad L340-15IRH Gamin... | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Lenovo    | IdeaPad L340-15IRH Gamin... | [4ff939d0e2](https://linux-hardware.org/?probe=4ff939d0e2) | Apr 28, 2020 |
| Lenovo    | IdeaPad L340-15IRH Gamin... | [31b3c13f93](https://linux-hardware.org/?probe=31b3c13f93) | Apr 28, 2020 |
| Toshiba   | Satellite L550              | [73f10216d6](https://linux-hardware.org/?probe=73f10216d6) | Apr 25, 2020 |
| Dell      | Inspiron 15-3552            | [b5721fa9d5](https://linux-hardware.org/?probe=b5721fa9d5) | Apr 22, 2020 |
| Lenovo    | IdeaPad 130-15IKB 81H7      | [b391bbea48](https://linux-hardware.org/?probe=b391bbea48) | Apr 12, 2020 |
| Lenovo    | G580 20157                  | [30a8d59bdc](https://linux-hardware.org/?probe=30a8d59bdc) | Apr 09, 2020 |
| Lenovo    | G580 20157                  | [fc6eaad779](https://linux-hardware.org/?probe=fc6eaad779) | Apr 09, 2020 |
| ASUSTek   | X556UV                      | [cb5da8627a](https://linux-hardware.org/?probe=cb5da8627a) | Apr 07, 2020 |
| ASUSTek   | X550JX                      | [71dbec47eb](https://linux-hardware.org/?probe=71dbec47eb) | Mar 27, 2020 |
| ASUSTek   | X550JX                      | [cc439d9e0f](https://linux-hardware.org/?probe=cc439d9e0f) | Mar 27, 2020 |
| Dell      | Inspiron 3521               | [cb7137a57a](https://linux-hardware.org/?probe=cb7137a57a) | Mar 16, 2020 |
| ASUSTek   | TUF GAMING FX504GD_FX80G... | [64628c8c11](https://linux-hardware.org/?probe=64628c8c11) | Mar 12, 2020 |
| ASUSTek   | X550JX                      | [a1fa3183ed](https://linux-hardware.org/?probe=a1fa3183ed) | Feb 15, 2020 |
| Lenovo    | IdeaPad 700-15ISK 80RU      | [97b5418b6d](https://linux-hardware.org/?probe=97b5418b6d) | Feb 03, 2020 |
| Lenovo    | ThinkPad T440s 20AQ005NU... | [55d9286a1b](https://linux-hardware.org/?probe=55d9286a1b) | Jan 27, 2020 |
| Acer      | Aspire E1-570               | [9d92944e6c](https://linux-hardware.org/?probe=9d92944e6c) | Dec 21, 2019 |
| Acer      | Aspire E1-570               | [64702aadcd](https://linux-hardware.org/?probe=64702aadcd) | Dec 21, 2019 |
| Lenovo    | Unknown                     | [10ab399874](https://linux-hardware.org/?probe=10ab399874) | Dec 14, 2019 |
| Sony      | VPCEH36EF                   | [5b1adbe8f0](https://linux-hardware.org/?probe=5b1adbe8f0) | Dec 10, 2019 |
| Sony      | VPCEH36EF                   | [6518790628](https://linux-hardware.org/?probe=6518790628) | Nov 27, 2019 |
| Dell      | Latitude E6420              | [3f252a50fb](https://linux-hardware.org/?probe=3f252a50fb) | Nov 12, 2019 |
| ASUSTek   | TUF Gaming FX705DD_TUF70... | [1b5ae66e6f](https://linux-hardware.org/?probe=1b5ae66e6f) | Nov 10, 2019 |
| ASUSTek   | TUF Gaming FX705DD_TUF70... | [34d1b1bbb8](https://linux-hardware.org/?probe=34d1b1bbb8) | Nov 03, 2019 |
| ASUSTek   | TUF Gaming FX705DD_TUF70... | [5e467ffabe](https://linux-hardware.org/?probe=5e467ffabe) | Nov 02, 2019 |
| ASUSTek   | TUF Gaming FX705DD_TUF70... | [f39e5e0553](https://linux-hardware.org/?probe=f39e5e0553) | Nov 02, 2019 |
| ASUSTek   | TUF Gaming FX705DD_TUF70... | [d3a4d0e499](https://linux-hardware.org/?probe=d3a4d0e499) | Nov 02, 2019 |
| ASUSTek   | TUF Gaming FX705DD_TUF70... | [a9cc2a8ea0](https://linux-hardware.org/?probe=a9cc2a8ea0) | Nov 01, 2019 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [b57e5735a5](https://linux-hardware.org/?probe=b57e5735a5) | Sep 13, 2019 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [708bc2c339](https://linux-hardware.org/?probe=708bc2c339) | Sep 13, 2019 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [32431b14c6](https://linux-hardware.org/?probe=32431b14c6) | Sep 12, 2019 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [bd3f45d532](https://linux-hardware.org/?probe=bd3f45d532) | Sep 12, 2019 |
| HP        | 630                         | [8cb4c328bb](https://linux-hardware.org/?probe=8cb4c328bb) | Sep 10, 2019 |
| Acer      | Aspire V5-572G              | [7d046c01d0](https://linux-hardware.org/?probe=7d046c01d0) | Sep 07, 2019 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [8273112474](https://linux-hardware.org/?probe=8273112474) | Sep 04, 2019 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [247696e7ef](https://linux-hardware.org/?probe=247696e7ef) | Sep 04, 2019 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [ed2e1bf218](https://linux-hardware.org/?probe=ed2e1bf218) | Sep 04, 2019 |
| HP        | Pavilion g6                 | [6eebb27f65](https://linux-hardware.org/?probe=6eebb27f65) | Aug 28, 2019 |
| HP        | Laptop                      | [de71114421](https://linux-hardware.org/?probe=de71114421) | Aug 21, 2019 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [60c722f7f6](https://linux-hardware.org/?probe=60c722f7f6) | Aug 20, 2019 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [a360d16ee3](https://linux-hardware.org/?probe=a360d16ee3) | Aug 18, 2019 |
| Acer      | Aspire V5-572G              | [90d2c432d6](https://linux-hardware.org/?probe=90d2c432d6) | Aug 17, 2019 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [26b5185afb](https://linux-hardware.org/?probe=26b5185afb) | Aug 14, 2019 |
| Acer      | TravelMate P259-M           | [3693d52bff](https://linux-hardware.org/?probe=3693d52bff) | Nov 09, 2018 |
| Acer      | TravelMate P259-M           | [a951fd5ef9](https://linux-hardware.org/?probe=a951fd5ef9) | Nov 09, 2018 |
| HP        | Laptop 17-ak0xx             | [83d0682234](https://linux-hardware.org/?probe=83d0682234) | Sep 20, 2018 |
| HP        | Laptop 17-ak0xx             | [e2076e8303](https://linux-hardware.org/?probe=e2076e8303) | Sep 19, 2018 |
| HP        | Laptop 17-ak0xx             | [24599e9990](https://linux-hardware.org/?probe=24599e9990) | Sep 19, 2018 |
| HP        | Pavilion g6                 | [c93294c4ab](https://linux-hardware.org/?probe=c93294c4ab) | Sep 18, 2018 |
| HP        | Pavilion g6                 | [f12dea2a72](https://linux-hardware.org/?probe=f12dea2a72) | Sep 18, 2018 |
| HP        | Pavilion g6                 | [efc4afba58](https://linux-hardware.org/?probe=efc4afba58) | Aug 10, 2018 |
| HP        | Pavilion g6                 | [494e0c0416](https://linux-hardware.org/?probe=494e0c0416) | Aug 10, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 27        | 27.55%  |
| Ubuntu 18.04      | 13        | 13.27%  |
| Ubuntu 21.10      | 4         | 4.08%   |
| Zorin 15          | 3         | 3.06%   |
| Ubuntu 16.04      | 3         | 3.06%   |
| Debian 10         | 3         | 3.06%   |
| Ubuntu 21.04      | 2         | 2.04%   |
| Ubuntu 20.10      | 2         | 2.04%   |
| Pop!_OS 21.04     | 2         | 2.04%   |
| OpenMandriva 4.2  | 2         | 2.04%   |
| Manjaro 21.1.0    | 2         | 2.04%   |
| LMDE 4            | 2         | 2.04%   |
| Linux Mint 20.3   | 2         | 2.04%   |
| Linux Mint 20.2   | 2         | 2.04%   |
| Fedora 35         | 2         | 2.04%   |
| Fedora 33         | 2         | 2.04%   |
| Xubuntu 18.04     | 1         | 1.02%   |
| Ubuntu 19.10      | 1         | 1.02%   |
| Sodalite 35       | 1         | 1.02%   |
| ROSA R8.1         | 1         | 1.02%   |
| ROSA R11          | 1         | 1.02%   |
| ROSA R10          | 1         | 1.02%   |
| Pop!_OS 20.10     | 1         | 1.02%   |
| OpenMandriva 4.3  | 1         | 1.02%   |
| Manjaro 20.2      | 1         | 1.02%   |
| Lubuntu 20.04     | 1         | 1.02%   |
| Lubuntu 18.04     | 1         | 1.02%   |
| Linux Mint 20.1   | 1         | 1.02%   |
| Linux Mint 20     | 1         | 1.02%   |
| Kubuntu 20.04     | 1         | 1.02%   |
| Gentoo 2.7        | 1         | 1.02%   |
| Fedora 31         | 1         | 1.02%   |
| Endless 3.9.5     | 1         | 1.02%   |
| Endless 3.7.8     | 1         | 1.02%   |
| Endless 3.5.0     | 1         | 1.02%   |
| Elementary 5.1.5  | 1         | 1.02%   |
| Deepin            | 1         | 1.02%   |
| Debian 11         | 1         | 1.02%   |
| ArcoLinux Rolling | 1         | 1.02%   |
| Arch Rolling      | 1         | 1.02%   |
| Arch              | 1         | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 51        | 53.13%  |
| Linux Mint   | 6         | 6.25%   |
| Fedora       | 4         | 4.17%   |
| Debian       | 4         | 4.17%   |
| Zorin        | 3         | 3.13%   |
| ROSA         | 3         | 3.13%   |
| Pop!_OS      | 3         | 3.13%   |
| OpenMandriva | 3         | 3.13%   |
| Manjaro      | 3         | 3.13%   |
| Endless      | 3         | 3.13%   |
| Lubuntu      | 2         | 2.08%   |
| LMDE         | 2         | 2.08%   |
| Arch         | 2         | 2.08%   |
| Xubuntu      | 1         | 1.04%   |
| Sodalite     | 1         | 1.04%   |
| Kubuntu      | 1         | 1.04%   |
| Gentoo       | 1         | 1.04%   |
| Elementary   | 1         | 1.04%   |
| Deepin       | 1         | 1.04%   |
| ArcoLinux    | 1         | 1.04%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.13.0-28-generic        | 4         | 3.74%   |
| 5.3.0-46-generic         | 3         | 2.8%    |
| 5.11.0-38-generic        | 3         | 2.8%    |
| 5.0.0-25-generic         | 3         | 2.8%    |
| 5.8.0-38-generic         | 2         | 1.87%   |
| 5.4.0-72-generic         | 2         | 1.87%   |
| 5.4.0-58-generic         | 2         | 1.87%   |
| 5.4.0-52-generic         | 2         | 1.87%   |
| 5.4.0-42-generic         | 2         | 1.87%   |
| 5.3.0-40-generic         | 2         | 1.87%   |
| 5.3.0-28-generic         | 2         | 1.87%   |
| 5.11.0-7620-generic      | 2         | 1.87%   |
| 5.11.0-40-generic        | 2         | 1.87%   |
| 5.10.14-desktop-1omv4002 | 2         | 1.87%   |
| 4.19.0-6-amd64           | 2         | 1.87%   |
| 5.9.9-arch1-1            | 1         | 0.93%   |
| 5.8.15-301.fc33.x86_64   | 1         | 0.93%   |
| 5.8.0-50-generic         | 1         | 0.93%   |
| 5.8.0-44-generic         | 1         | 0.93%   |
| 5.8.0-40-generic         | 1         | 0.93%   |
| 5.8.0-33-generic         | 1         | 0.93%   |
| 5.8.0-32-generic         | 1         | 0.93%   |
| 5.8.0-28-generic         | 1         | 0.93%   |
| 5.8.0-14-generic         | 1         | 0.93%   |
| 5.4.80-2-MANJARO         | 1         | 0.93%   |
| 5.4.143-1-pve            | 1         | 0.93%   |
| 5.4.119-1-pve            | 1         | 0.93%   |
| 5.4.0-91-generic         | 1         | 0.93%   |
| 5.4.0-90-generic         | 1         | 0.93%   |
| 5.4.0-84-generic         | 1         | 0.93%   |
| 5.4.0-65-lowlatency      | 1         | 0.93%   |
| 5.4.0-65-generic         | 1         | 0.93%   |
| 5.4.0-64-lowlatency      | 1         | 0.93%   |
| 5.4.0-56-generic         | 1         | 0.93%   |
| 5.4.0-48-generic         | 1         | 0.93%   |
| 5.4.0-47-generic         | 1         | 0.93%   |
| 5.4.0-45-generic         | 1         | 0.93%   |
| 5.4.0-33-generic         | 1         | 0.93%   |
| 5.4.0-29-generic         | 1         | 0.93%   |
| 5.4.0-28-lowlatency      | 1         | 0.93%   |
| 5.4.0-26-generic         | 1         | 0.93%   |
| 5.4.0-107-generic        | 1         | 0.93%   |
| 5.3.8-300.fc31.x86_64    | 1         | 0.93%   |
| 5.3.0-59-generic         | 1         | 0.93%   |
| 5.16.9-200.fc35.x86_64   | 1         | 0.93%   |
| 5.16.7-desktop-1omv4003  | 1         | 0.93%   |
| 5.16.18-200.fc35.x86_64  | 1         | 0.93%   |
| 5.16.11-200.fc35.x86_64  | 1         | 0.93%   |
| 5.15.16-200.fc35.x86_64  | 1         | 0.93%   |
| 5.13.11-1-MANJARO        | 1         | 0.93%   |
| 5.13.0-40-generic        | 1         | 0.93%   |
| 5.13.0-30-generic        | 1         | 0.93%   |
| 5.13.0-27-generic        | 1         | 0.93%   |
| 5.13.0-22-generic        | 1         | 0.93%   |
| 5.13.0-21-generic        | 1         | 0.93%   |
| 5.12.12-arch1-1          | 1         | 0.93%   |
| 5.11.17-xanmod1          | 1         | 0.93%   |
| 5.11.13-arch1-1          | 1         | 0.93%   |
| 5.11.0-49-generic        | 1         | 0.93%   |
| 5.11.0-44-generic        | 1         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 21        | 20.39%  |
| 5.11.0  | 11        | 10.68%  |
| 5.8.0   | 9         | 8.74%   |
| 5.13.0  | 9         | 8.74%   |
| 5.3.0   | 8         | 7.77%   |
| 4.15.0  | 8         | 7.77%   |
| 5.0.0   | 6         | 5.83%   |
| 4.19.0  | 4         | 3.88%   |
| 5.10.14 | 2         | 1.94%   |
| 4.18.0  | 2         | 1.94%   |
| 5.9.9   | 1         | 0.97%   |
| 5.8.15  | 1         | 0.97%   |
| 5.4.80  | 1         | 0.97%   |
| 5.4.143 | 1         | 0.97%   |
| 5.4.119 | 1         | 0.97%   |
| 5.3.8   | 1         | 0.97%   |
| 5.16.9  | 1         | 0.97%   |
| 5.16.7  | 1         | 0.97%   |
| 5.16.18 | 1         | 0.97%   |
| 5.16.11 | 1         | 0.97%   |
| 5.15.16 | 1         | 0.97%   |
| 5.13.11 | 1         | 0.97%   |
| 5.12.12 | 1         | 0.97%   |
| 5.11.17 | 1         | 0.97%   |
| 5.11.13 | 1         | 0.97%   |
| 5.10.53 | 1         | 0.97%   |
| 5.10.27 | 1         | 0.97%   |
| 5.10.19 | 1         | 0.97%   |
| 5.10.0  | 1         | 0.97%   |
| 4.9.9   | 1         | 0.97%   |
| 4.9.60  | 1         | 0.97%   |
| 4.9.124 | 1         | 0.97%   |
| 3.13.0  | 1         | 0.97%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 23        | 23%     |
| 5.11    | 13        | 13%     |
| 5.8     | 10        | 10%     |
| 5.13    | 10        | 10%     |
| 5.3     | 9         | 9%      |
| 4.15    | 8         | 8%      |
| 5.10    | 6         | 6%      |
| 5.0     | 6         | 6%      |
| 4.19    | 4         | 4%      |
| 5.16    | 3         | 3%      |
| 4.9     | 2         | 2%      |
| 4.18    | 2         | 2%      |
| 5.9     | 1         | 1%      |
| 5.15    | 1         | 1%      |
| 5.12    | 1         | 1%      |
| 3.13    | 1         | 1%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 92        | 97.87%  |
| i686   | 2         | 2.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 56        | 57.14%  |
| Unknown         | 11        | 11.22%  |
| X-Cinnamon      | 7         | 7.14%   |
| KDE5            | 7         | 7.14%   |
| XFCE            | 4         | 4.08%   |
| KDE4            | 3         | 3.06%   |
| Pantheon        | 2         | 2.04%   |
| Unity           | 1         | 1.02%   |
| MATE            | 1         | 1.02%   |
| LXQt            | 1         | 1.02%   |
| LXDE            | 1         | 1.02%   |
| GNOME Flashback | 1         | 1.02%   |
| GNOME Classic   | 1         | 1.02%   |
| dwm             | 1         | 1.02%   |
| Deepin          | 1         | 1.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 76        | 79.17%  |
| Wayland | 13        | 13.54%  |
| Unknown | 5         | 5.21%   |
| Tty     | 2         | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 42        | 44.21%  |
| GDM     | 33        | 34.74%  |
| SDDM    | 7         | 7.37%   |
| LightDM | 7         | 7.37%   |
| KDM     | 3         | 3.16%   |
| GDM3    | 3         | 3.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 46        | 47.92%  |
| fr_FR   | 27        | 28.13%  |
| Unknown | 14        | 14.58%  |
| en_GB   | 4         | 4.17%   |
| C       | 2         | 2.08%   |
| pt_BR   | 1         | 1.04%   |
| en_CA   | 1         | 1.04%   |
| ar_TN   | 1         | 1.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 53        | 55.79%  |
| BIOS | 42        | 44.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 84        | 88.42%  |
| Unknown | 5         | 5.26%   |
| Overlay | 3         | 3.16%   |
| Btrfs   | 2         | 2.11%   |
| Xfs     | 1         | 1.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 48        | 50.53%  |
| GPT     | 31        | 32.63%  |
| MBR     | 16        | 16.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 86        | 90.53%  |
| Yes       | 9         | 9.47%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 67.74%  |
| Yes       | 30        | 32.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 26        | 27.96%  |
| Hewlett-Packard     | 18        | 19.35%  |
| ASUSTek Computer    | 17        | 18.28%  |
| Dell                | 12        | 12.9%   |
| Acer                | 8         | 8.6%    |
| Toshiba             | 5         | 5.38%   |
| MSI                 | 3         | 3.23%   |
| Samsung Electronics | 2         | 2.15%   |
| Sony                | 1         | 1.08%   |
| eMachines           | 1         | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 3         | 3.23%   |
| Lenovo IdeaPad 130-15IKB 81H7            | 2         | 2.15%   |
| HP Pavilion Gaming Laptop 15-ec1xxx      | 2         | 2.15%   |
| HP Pavilion g6                           | 2         | 2.15%   |
| ASUS X550JX                              | 2         | 2.15%   |
| Toshiba Satellite Pro L850-B339          | 1         | 1.08%   |
| Toshiba Satellite L550                   | 1         | 1.08%   |
| Toshiba Satellite L500                   | 1         | 1.08%   |
| Toshiba Satellite C50-A489               | 1         | 1.08%   |
| Toshiba Satellite A300                   | 1         | 1.08%   |
| Sony VPCEH36EF                           | 1         | 1.08%   |
| Samsung 530U3BI/530U4BI/530U4BH          | 1         | 1.08%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 1.08%   |
| MSI Katana GF66 12UC                     | 1         | 1.08%   |
| MSI GF65 Thin 10UE                       | 1         | 1.08%   |
| MSI GF63 Thin 10SCXR                     | 1         | 1.08%   |
| Lenovo V15-IIL 82C5                      | 1         | 1.08%   |
| Lenovo ThinkPad X240 20AMA0WRFR          | 1         | 1.08%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW    | 1         | 1.08%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100 | 1         | 1.08%   |
| Lenovo ThinkPad T440s 20AQ005NUS         | 1         | 1.08%   |
| Lenovo ThinkPad E15 20RD001SFE           | 1         | 1.08%   |
| Lenovo ThinkPad E15 20RD001QFE           | 1         | 1.08%   |
| Lenovo IdeaPad Y700-15ISK 80NV           | 1         | 1.08%   |
| Lenovo IdeaPad S145-15AST 81N3           | 1         | 1.08%   |
| Lenovo IdeaPad L3 15IML05 81Y3           | 1         | 1.08%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 1         | 1.08%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY     | 1         | 1.08%   |
| Lenovo IdeaPad 700-15ISK 80RU            | 1         | 1.08%   |
| Lenovo IdeaPad 330S-14AST 81F8           | 1         | 1.08%   |
| Lenovo IdeaPad 330-15AST 81D6            | 1         | 1.08%   |
| Lenovo IdeaPad 320-15IKB 81BT            | 1         | 1.08%   |
| Lenovo IdeaPad 120S-11IAP 81A4           | 1         | 1.08%   |
| Lenovo IdeaPad 100-15IBD 80QQ            | 1         | 1.08%   |
| Lenovo G580 20157                        | 1         | 1.08%   |
| Lenovo G50-70 20351                      | 1         | 1.08%   |
| HP ProBook 440 G7                        | 1         | 1.08%   |
| HP Pavilion Gaming Laptop 15-ec0xxx      | 1         | 1.08%   |
| HP Pavilion Gaming Laptop 15-dk0xxx      | 1         | 1.08%   |
| HP Pavilion dv7                          | 1         | 1.08%   |
| HP Pavilion dv6                          | 1         | 1.08%   |
| HP Notebook                              | 1         | 1.08%   |
| HP Laptop 17-ak0xx                       | 1         | 1.08%   |
| HP Laptop 15-bs0xx                       | 1         | 1.08%   |
| HP Laptop                                | 1         | 1.08%   |
| HP EliteBook 8740w                       | 1         | 1.08%   |
| HP Compaq 6735s                          | 1         | 1.08%   |
| HP 630                                   | 1         | 1.08%   |
| HP 250 G7 Notebook PC                    | 1         | 1.08%   |
| HP 250 G4                                | 1         | 1.08%   |
| eMachines E725                           | 1         | 1.08%   |
| Dell Latitude E6420                      | 1         | 1.08%   |
| Dell Latitude E5440                      | 1         | 1.08%   |
| Dell Latitude 7490                       | 1         | 1.08%   |
| Dell Latitude 7480                       | 1         | 1.08%   |
| Dell Latitude 7410                       | 1         | 1.08%   |
| Dell Latitude 3540                       | 1         | 1.08%   |
| Dell Inspiron N5110                      | 1         | 1.08%   |
| Dell Inspiron 5570                       | 1         | 1.08%   |
| Dell Inspiron 3593                       | 1         | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 16        | 17.2%   |
| HP Pavilion       | 8         | 8.6%    |
| Lenovo ThinkPad   | 6         | 6.45%   |
| Dell Latitude     | 6         | 6.45%   |
| Dell Inspiron     | 6         | 6.45%   |
| Toshiba Satellite | 5         | 5.38%   |
| Acer Aspire       | 5         | 5.38%   |
| ASUS TUF          | 4         | 4.3%    |
| HP Laptop         | 3         | 3.23%   |
| HP 250            | 2         | 2.15%   |
| ASUS X550JX       | 2         | 2.15%   |
| ASUS ASUS         | 2         | 2.15%   |
| Acer Swift        | 2         | 2.15%   |
| Sony VPCEH36EF    | 1         | 1.08%   |
| Samsung 530U3BI   | 1         | 1.08%   |
| Samsung 300E5EV   | 1         | 1.08%   |
| MSI Katana        | 1         | 1.08%   |
| MSI GF65          | 1         | 1.08%   |
| MSI GF63          | 1         | 1.08%   |
| Lenovo V15-IIL    | 1         | 1.08%   |
| Lenovo G580       | 1         | 1.08%   |
| Lenovo G50-70     | 1         | 1.08%   |
| HP ProBook        | 1         | 1.08%   |
| HP Notebook       | 1         | 1.08%   |
| HP EliteBook      | 1         | 1.08%   |
| HP Compaq         | 1         | 1.08%   |
| HP 630            | 1         | 1.08%   |
| eMachines E725    | 1         | 1.08%   |
| ASUS X556UV       | 1         | 1.08%   |
| ASUS X555LD       | 1         | 1.08%   |
| ASUS X553MA       | 1         | 1.08%   |
| ASUS X550VX       | 1         | 1.08%   |
| ASUS X550LC       | 1         | 1.08%   |
| ASUS VivoBook     | 1         | 1.08%   |
| ASUS UX360CA      | 1         | 1.08%   |
| ASUS UX310UQK     | 1         | 1.08%   |
| ASUS ROG          | 1         | 1.08%   |
| Acer TravelMate   | 1         | 1.08%   |
| Unknown           | 1         | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 13        | 13.98%  |
| 2020 | 11        | 11.83%  |
| 2018 | 11        | 11.83%  |
| 2017 | 9         | 9.68%   |
| 2013 | 9         | 9.68%   |
| 2015 | 8         | 8.6%    |
| 2011 | 6         | 6.45%   |
| 2012 | 5         | 5.38%   |
| 2021 | 4         | 4.3%    |
| 2016 | 4         | 4.3%    |
| 2014 | 4         | 4.3%    |
| 2008 | 4         | 4.3%    |
| 2009 | 3         | 3.23%   |
| 2010 | 2         | 2.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 93        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 86        | 92.47%  |
| Enabled  | 7         | 7.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 93        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 35        | 37.23%  |
| 3.01-4.0   | 19        | 20.21%  |
| 16.01-24.0 | 18        | 19.15%  |
| 8.01-16.0  | 16        | 17.02%  |
| 32.01-64.0 | 4         | 4.26%   |
| 2.01-3.0   | 1         | 1.06%   |
| 1.01-2.0   | 1         | 1.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 32        | 31.37%  |
| 1.01-2.0  | 30        | 29.41%  |
| 3.01-4.0  | 17        | 16.67%  |
| 4.01-8.0  | 16        | 15.69%  |
| 8.01-16.0 | 3         | 2.94%   |
| 0.51-1.0  | 3         | 2.94%   |
| Unknown   | 1         | 0.98%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 71        | 74.74%  |
| 2      | 24        | 25.26%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 50%     |
| No        | 47        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 88.17%  |
| No        | 11        | 11.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 86.46%  |
| No        | 13        | 13.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Tunisia | 93        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Tunis              | 46        | 43.81%  |
| Aryanah            | 7         | 6.67%   |
| Bizerte            | 6         | 5.71%   |
| Monastir           | 5         | 4.76%   |
| Nabeul             | 3         | 2.86%   |
| Centre Urbain Nord | 3         | 2.86%   |
| Sousse             | 2         | 1.9%    |
| Sfax               | 2         | 1.9%    |
| Rades              | 2         | 1.9%    |
| Medjez el Bab      | 2         | 1.9%    |
| Masakin            | 2         | 1.9%    |
| Kelibia            | 2         | 1.9%    |
| Zaouiat Djedidi    | 1         | 0.95%   |
| Wadi Maliz         | 1         | 0.95%   |
| Tataouine          | 1         | 0.95%   |
| Rafraf             | 1         | 0.95%   |
| Megrine            | 1         | 0.95%   |
| Mateur             | 1         | 0.95%   |
| La Marsa           | 1         | 0.95%   |
| La Goulette        | 1         | 0.95%   |
| Korba              | 1         | 0.95%   |
| Kairouan           | 1         | 0.95%   |
| Jedeida            | 1         | 0.95%   |
| Hergla             | 1         | 0.95%   |
| Hammam Sousse      | 1         | 0.95%   |
| Gafsa              | 1         | 0.95%   |
| GabГЁs           | 1         | 0.95%   |
| El Fahs            | 1         | 0.95%   |
| Douz               | 1         | 0.95%   |
| Cite Bouzaiene     | 1         | 0.95%   |
| Cite Ben Kilani    | 1         | 0.95%   |
| Cite 18 Janvier    | 1         | 0.95%   |
| Beni Khiar         | 1         | 0.95%   |
| Ben Arous          | 1         | 0.95%   |
| Belvedere          | 1         | 0.95%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 24        | 27     | 21.05%  |
| WDC                   | 20        | 28     | 17.54%  |
| Toshiba               | 12        | 14     | 10.53%  |
| Team                  | 8         | 10     | 7.02%   |
| SK Hynix              | 8         | 9      | 7.02%   |
| Samsung Electronics   | 8         | 9      | 7.02%   |
| Sandisk               | 5         | 5      | 4.39%   |
| HGST                  | 5         | 6      | 4.39%   |
| Hitachi               | 4         | 4      | 3.51%   |
| Unknown               | 3         | 3      | 2.63%   |
| Kingston              | 3         | 4      | 2.63%   |
| Fujitsu               | 3         | 3      | 2.63%   |
| Micron Technology     | 2         | 2      | 1.75%   |
| Intel                 | 2         | 2      | 1.75%   |
| UMIS                  | 1         | 1      | 0.88%   |
| Realtek Semiconductor | 1         | 1      | 0.88%   |
| PNY                   | 1         | 1      | 0.88%   |
| Phison                | 1         | 1      | 0.88%   |
| Patriot               | 1         | 1      | 0.88%   |
| OCZ                   | 1         | 1      | 0.88%   |
| A-DATA Technology     | 1         | 1      | 0.88%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 7         | 6.03%   |
| Seagate ST500LT012-1DG142 500GB         | 6         | 5.17%   |
| Seagate ST2000LM007-1R8174 2TB          | 3         | 2.59%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 2         | 1.72%   |
| WDC WD20SPZX-08UA7 2TB                  | 2         | 1.72%   |
| WDC WD10SPZX-08Z10 1TB                  | 2         | 1.72%   |
| WDC WD10SPCX-24HWST1 1TB                | 2         | 1.72%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 1.72%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 1.72%   |
| Toshiba MK5076GSX 500GB                 | 2         | 1.72%   |
| Team T253X2512G 512GB SSD               | 2         | 1.72%   |
| SK Hynix SC311 SATA 256GB SSD           | 2         | 1.72%   |
| Seagate ST1000LX015-1U7172 1TB          | 2         | 1.72%   |
| Kingston NVMe SSD Drive 512GB           | 2         | 1.72%   |
| Hitachi HTS545050A7E380 500GB           | 2         | 1.72%   |
| HGST HTS545050A7E380 500GB              | 2         | 1.72%   |
| Fujitsu MHV2100BH PL 100GB              | 2         | 1.72%   |
| WDC WD5000LPZX-60Z10T0 500GB            | 1         | 0.86%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 1         | 0.86%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 0.86%   |
| WDC WD5000LPLX-60ZNTT2 500GB            | 1         | 0.86%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.86%   |
| WDC WD5000BPVT-55HXZT3 500GB            | 1         | 0.86%   |
| WDC WD3200BEKT-60KA9T0 320GB            | 1         | 0.86%   |
| WDC WD2500BPVT-75JJ5T0 250GB            | 1         | 0.86%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.86%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB    | 1         | 0.86%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB    | 1         | 0.86%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB    | 1         | 0.86%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB    | 1         | 0.86%   |
| Unknown xD/SD/M.S.                      | 1         | 0.86%   |
| Unknown SS16G  16GB                     | 1         | 0.86%   |
| Unknown 00000  64GB                     | 1         | 0.86%   |
| UMIS RPJTJ512MEE1OWX 512GB              | 1         | 0.86%   |
| Toshiba MQ01ACF050 500GB                | 1         | 0.86%   |
| Toshiba MQ01ABD050 500GB                | 1         | 0.86%   |
| Toshiba MQ01ABD032 320GB                | 1         | 0.86%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.86%   |
| Toshiba MK4055GSX 400GB                 | 1         | 0.86%   |
| Toshiba MK3275GSX 320GB                 | 1         | 0.86%   |
| Team TM8FP6256G 256GB                   | 1         | 0.86%   |
| Team TM8FP6128G 128GB                   | 1         | 0.86%   |
| Team TM8FP4256G 256GB                   | 1         | 0.86%   |
| Team T253LE240G 240GB SSD               | 1         | 0.86%   |
| Team T253E2512G 512GB SSD               | 1         | 0.86%   |
| Team T2535T240G 240GB SSD               | 1         | 0.86%   |
| SK Hynix NVMe SSD Drive 512GB           | 1         | 0.86%   |
| SK Hynix HFS512G39MND-3510A 512GB SSD   | 1         | 0.86%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD   | 1         | 0.86%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD   | 1         | 0.86%   |
| SK Hynix HFM256GDJTNG-8310A 256GB       | 1         | 0.86%   |
| SK Hynix BC511 NVMe 256GB               | 1         | 0.86%   |
| SK Hynix BC511 HFM512GDJTNI-82A0A 512GB | 1         | 0.86%   |
| Seagate ST9320320AS 320GB               | 1         | 0.86%   |
| Seagate ST9120823ASG 120GB              | 1         | 0.86%   |
| Seagate ST500LM030-2E717D 500GB         | 1         | 0.86%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 1         | 0.86%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 0.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 1         | 0.86%   |
| SanDisk SSD U110 16GB                   | 1         | 0.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 24        | 27     | 36.92%  |
| WDC     | 17        | 24     | 26.15%  |
| Toshiba | 12        | 14     | 18.46%  |
| HGST    | 5         | 6      | 7.69%   |
| Hitachi | 4         | 4      | 6.15%   |
| Fujitsu | 3         | 3      | 4.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Team                | 5         | 7      | 23.81%  |
| SK Hynix            | 5         | 5      | 23.81%  |
| Samsung Electronics | 4         | 5      | 19.05%  |
| SanDisk             | 3         | 3      | 14.29%  |
| PNY                 | 1         | 1      | 4.76%   |
| Patriot             | 1         | 1      | 4.76%   |
| OCZ                 | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 64        | 78     | 57.66%  |
| NVMe    | 23        | 28     | 20.72%  |
| SSD     | 21        | 24     | 18.92%  |
| MMC     | 2         | 2      | 1.8%    |
| Unknown | 1         | 1      | 0.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 77        | 102    | 74.76%  |
| NVMe | 23        | 28     | 22.33%  |
| MMC  | 2         | 2      | 1.94%   |
| SAS  | 1         | 1      | 0.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 51        | 61     | 61.45%  |
| 0.51-1.0   | 27        | 34     | 32.53%  |
| 1.01-2.0   | 5         | 7      | 6.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 31        | 31.63%  |
| 101-250    | 30        | 30.61%  |
| 501-1000   | 15        | 15.31%  |
| 1001-2000  | 9         | 9.18%   |
| 1-20       | 6         | 6.12%   |
| 51-100     | 5         | 5.1%    |
| 21-50      | 2         | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 40        | 39.6%   |
| 101-250   | 20        | 19.8%   |
| 21-50     | 17        | 16.83%  |
| 51-100    | 13        | 12.87%  |
| 251-500   | 5         | 4.95%   |
| 501-1000  | 4         | 3.96%   |
| 1001-2000 | 2         | 1.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-55HXZT3 500GB                        | 1         | 2      | 10%     |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 10%     |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 10%     |
| Toshiba MK5076GSX 500GB                             | 1         | 2      | 10%     |
| Toshiba MK4055GSX 400GB                             | 1         | 1      | 10%     |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 10%     |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 10%     |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 10%     |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 10%     |
| HGST HTS545050A7E380 500GB                          | 1         | 2      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 4         | 5      | 40%     |
| Hitachi           | 2         | 2      | 20%     |
| WDC               | 1         | 2      | 10%     |
| Seagate           | 1         | 1      | 10%     |
| Micron Technology | 1         | 1      | 10%     |
| HGST              | 1         | 2      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 5      | 44.44%  |
| Hitachi | 2         | 2      | 22.22%  |
| WDC     | 1         | 2      | 11.11%  |
| Seagate | 1         | 1      | 11.11%  |
| HGST    | 1         | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 12     | 90%     |
| SSD  | 1         | 1      | 10%     |

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
| Detected | 48        | 67     | 49.48%  |
| Works    | 39        | 53     | 40.21%  |
| Malfunc  | 10        | 13     | 10.31%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 79        | 70.54%  |
| AMD                          | 10        | 8.93%   |
| Sandisk                      | 5         | 4.46%   |
| Samsung Electronics          | 4         | 3.57%   |
| SK Hynix                     | 3         | 2.68%   |
| Kingston Technology Company  | 3         | 2.68%   |
| Realtek Semiconductor        | 2         | 1.79%   |
| Phison Electronics           | 2         | 1.79%   |
| Union Memory (Shenzhen)      | 1         | 0.89%   |
| Silicon Motion               | 1         | 0.89%   |
| Shenzhen Longsys Electronics | 1         | 0.89%   |
| Micron Technology            | 1         | 0.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 9.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 7.83%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 7.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 6.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 6.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 4.35%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 3.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 3.48%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 2.61%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 2.61%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 2.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 2.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 2.61%   |
| SK Hynix BC511                                                                   | 2         | 1.74%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 2         | 1.74%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.74%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.74%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.74%   |
| Intel SSD 660P Series                                                            | 2         | 1.74%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.74%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.87%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.87%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.87%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                 | 1         | 0.87%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.87%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.87%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.87%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 1         | 0.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.87%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.87%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 76        | 67.86%  |
| NVMe | 23        | 20.54%  |
| RAID | 11        | 9.82%   |
| IDE  | 2         | 1.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 81        | 87.1%   |
| AMD    | 12        | 12.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 4.3%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 3.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 3.23%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 3.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 3.23%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 3.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 2.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.15%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 2.15%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 2.15%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 2.15%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 2.15%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 2.15%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 2.15%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 2.15%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 2.15%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 2         | 2.15%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 2.15%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 1.08%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 1.08%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 1.08%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 1.08%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 1.08%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.08%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz            | 1         | 1.08%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 1.08%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 1.08%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 1.08%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 1.08%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.08%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 1.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.08%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.08%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.08%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.08%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 1.08%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 1.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.08%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.08%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 1         | 1.08%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.08%   |
| Intel Core i5-10310U CPU @ 1.70GHz            | 1         | 1.08%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 1         | 1.08%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.08%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 1         | 1.08%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 1         | 1.08%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.08%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.08%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 1.08%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.08%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 1.08%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 1.08%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 1         | 1.08%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.08%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.08%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 32        | 34.41%  |
| Intel Core i7           | 21        | 22.58%  |
| Intel Core i3           | 15        | 16.13%  |
| AMD Ryzen 5             | 6         | 6.45%   |
| Other                   | 4         | 4.3%    |
| Intel Pentium           | 3         | 3.23%   |
| Intel Core 2 Duo        | 3         | 3.23%   |
| Intel Celeron           | 2         | 2.15%   |
| Intel Pentium Dual-Core | 1         | 1.08%   |
| Intel Core m3           | 1         | 1.08%   |
| AMD Sempron             | 1         | 1.08%   |
| AMD Ryzen 7             | 1         | 1.08%   |
| AMD E2                  | 1         | 1.08%   |
| AMD A6                  | 1         | 1.08%   |
| AMD A4                  | 1         | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 50        | 53.76%  |
| 4      | 32        | 34.41%  |
| 6      | 7         | 7.53%   |
| 8      | 2         | 2.15%   |
| 14     | 1         | 1.08%   |
| 1      | 1         | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 93        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 78        | 83.87%  |
| 1      | 15        | 16.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 92        | 98.92%  |
| Unknown        | 1         | 1.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 18.09%  |
| 0x40651    | 7         | 7.45%   |
| 0x806ea    | 6         | 6.38%   |
| 0x306a9    | 6         | 6.38%   |
| 0x206a7    | 6         | 6.38%   |
| 0x806ec    | 5         | 5.32%   |
| 0x906ea    | 4         | 4.26%   |
| 0xa0652    | 3         | 3.19%   |
| 0x706e5    | 3         | 3.19%   |
| 0x506e3    | 3         | 3.19%   |
| 0x406e3    | 3         | 3.19%   |
| 0x20655    | 3         | 3.19%   |
| 0x806e9    | 2         | 2.13%   |
| 0x806c1    | 2         | 2.13%   |
| 0x306d4    | 2         | 2.13%   |
| 0x306c3    | 2         | 2.13%   |
| 0x1067a    | 2         | 2.13%   |
| 0x08108102 | 2         | 2.13%   |
| 0x06006705 | 2         | 2.13%   |
| 0x06006704 | 2         | 2.13%   |
| 0x906a3    | 1         | 1.06%   |
| 0x6fd      | 1         | 1.06%   |
| 0x506c9    | 1         | 1.06%   |
| 0x406c4    | 1         | 1.06%   |
| 0x40661    | 1         | 1.06%   |
| 0x30678    | 1         | 1.06%   |
| 0x20652    | 1         | 1.06%   |
| 0x0a50000c | 1         | 1.06%   |
| 0x08600106 | 1         | 1.06%   |
| 0x08600104 | 1         | 1.06%   |
| 0x08108109 | 1         | 1.06%   |
| 0x02000032 | 1         | 1.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 23        | 24.73%  |
| Haswell         | 11        | 11.83%  |
| SandyBridge     | 8         | 8.6%    |
| Skylake         | 7         | 7.53%   |
| IvyBridge       | 6         | 6.45%   |
| Westmere        | 4         | 4.3%    |
| IceLake         | 4         | 4.3%    |
| Excavator       | 4         | 4.3%    |
| CometLake       | 4         | 4.3%    |
| Zen+            | 3         | 3.23%   |
| Zen 2           | 3         | 3.23%   |
| Silvermont      | 3         | 3.23%   |
| Penryn          | 3         | 3.23%   |
| Broadwell       | 3         | 3.23%   |
| TigerLake       | 2         | 2.15%   |
| Zen 3           | 1         | 1.08%   |
| K8 & K10 hybrid | 1         | 1.08%   |
| Goldmont        | 1         | 1.08%   |
| Core            | 1         | 1.08%   |
| Unknown         | 1         | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 76        | 53.9%   |
| Nvidia | 38        | 26.95%  |
| AMD    | 27        | 19.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 5.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4.93%   |
| Intel UHD Graphics 620                                                                   | 6         | 4.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 4.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 4.23%   |
| Intel HD Graphics 620                                                                    | 5         | 3.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 3.52%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 2.82%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 2.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 2.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 2.11%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 2.11%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 2.11%   |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 2.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.11%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 2.11%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.11%   |
| Intel HD Graphics 530                                                                    | 3         | 2.11%   |
| AMD Renoir                                                                               | 3         | 2.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.11%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.41%   |
| Nvidia TU117M                                                                            | 2         | 1.41%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.41%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.41%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.41%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 2         | 1.41%   |
| Nvidia GT218M [GeForce G 105M]                                                           | 1         | 0.7%    |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.7%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.7%    |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.7%    |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 0.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.7%    |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.7%    |
| Intel HD Graphics 515                                                                    | 1         | 0.7%    |
| Intel HD Graphics 500                                                                    | 1         | 0.7%    |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.7%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 1         | 0.7%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 1         | 0.7%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.7%    |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.7%    |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 1         | 0.7%    |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 1         | 0.7%    |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 1         | 0.7%    |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 1         | 0.7%    |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 34        | 36.56%  |
| Intel + Nvidia | 30        | 32.26%  |
| Intel + AMD    | 12        | 12.9%   |
| 1 x AMD        | 8         | 8.6%    |
| AMD + Nvidia   | 6         | 6.45%   |
| 1 x Nvidia     | 2         | 2.15%   |
| 2 x AMD        | 1         | 1.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 70        | 72.16%  |
| Proprietary | 23        | 23.71%  |
| Unknown     | 4         | 4.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 55.32%  |
| 1.01-2.0   | 12        | 12.77%  |
| 3.01-4.0   | 11        | 11.7%   |
| 0.01-0.5   | 10        | 10.64%  |
| 0.51-1.0   | 7         | 7.45%   |
| 2.01-3.0   | 2         | 2.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 24        | 23.76%  |
| BOE                     | 19        | 18.81%  |
| Chimei Innolux          | 18        | 17.82%  |
| Samsung Electronics     | 15        | 14.85%  |
| LG Display              | 12        | 11.88%  |
| Chi Mei Optoelectronics | 3         | 2.97%   |
| PANDA                   | 2         | 1.98%   |
| Hewlett-Packard         | 2         | 1.98%   |
| Lenovo                  | 1         | 0.99%   |
| ITE                     | 1         | 0.99%   |
| Goldstar                | 1         | 0.99%   |
| Dell                    | 1         | 0.99%   |
| BenQ                    | 1         | 0.99%   |
| Acer                    | 1         | 0.99%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 3.92%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 3         | 2.94%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 2.94%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 3         | 2.94%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch     | 2         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 1.96%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 1.96%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.96%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC354B 1440x900 367x230mm 17.1-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch     | 1         | 0.98%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 1         | 0.98%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 0.98%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                  | 1         | 0.98%   |
| LG Display LP156WH2-TLR1 LGD0221 1366x768 344x194mm 15.5-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch              | 1         | 0.98%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 1         | 0.98%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch              | 1         | 0.98%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch              | 1         | 0.98%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 1         | 0.98%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 1         | 0.98%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 1         | 0.98%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 1         | 0.98%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1         | 0.98%   |
| Lenovo LEN G27c-10 LEN66A3 1920x1080 597x336mm 27.0-inch                 | 1         | 0.98%   |
| ITE DP2VGA V158 ITE6512 1680x1050 600x340mm 27.2-inch                    | 1         | 0.98%   |
| Hewlett-Packard 24o HPN337C 1920x1080 531x299mm 24.0-inch                | 1         | 0.98%   |
| Hewlett-Packard 24es HWP3320 1920x1080 527x296mm 23.8-inch               | 1         | 0.98%   |
| Goldstar IPS226 GSM5807 1920x1080 477x268mm 21.5-inch                    | 1         | 0.98%   |
| Dell E2418HN DELA105 1920x1080 527x296mm 23.8-inch                       | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1733 1600x900 382x215mm 17.3-inch          | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch         | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 1         | 0.98%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 1         | 0.98%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 1         | 0.98%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 1         | 0.98%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 1         | 0.98%   |
| BOE LCD Monitor BOE0995 1920x1080 382x215mm 17.3-inch                    | 1         | 0.98%   |
| BOE LCD Monitor BOE095E 1366x768 344x194mm 15.5-inch                     | 1         | 0.98%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 1         | 0.98%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                    | 1         | 0.98%   |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch                    | 1         | 0.98%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                    | 1         | 0.98%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                    | 1         | 0.98%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 44        | 46.32%  |
| 1366x768 (WXGA)  | 41        | 43.16%  |
| 1600x900 (HD+)   | 5         | 5.26%   |
| 3840x2160 (4K)   | 2         | 2.11%   |
| 1440x900 (WXGA+) | 1         | 1.05%   |
| 1280x800 (WXGA)  | 1         | 1.05%   |
| 1280x1024 (SXGA) | 1         | 1.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 67        | 66.34%  |
| 17     | 8         | 7.92%   |
| 14     | 6         | 5.94%   |
| 13     | 6         | 5.94%   |
| 24     | 4         | 3.96%   |
| 21     | 4         | 3.96%   |
| 27     | 2         | 1.98%   |
| 31     | 1         | 0.99%   |
| 23     | 1         | 0.99%   |
| 12     | 1         | 0.99%   |
| 11     | 1         | 0.99%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 76        | 76%     |
| 351-400     | 8         | 8%      |
| 501-600     | 7         | 7%      |
| 401-500     | 4         | 4%      |
| 201-300     | 4         | 4%      |
| 601-700     | 1         | 1%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 85        | 95.51%  |
| 16/10 | 3         | 3.37%   |
| 5/4   | 1         | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 66.34%  |
| 81-90          | 10        | 9.9%    |
| 201-250        | 9         | 8.91%   |
| 121-130        | 5         | 4.95%   |
| 71-80          | 2         | 1.98%   |
| 301-350        | 2         | 1.98%   |
| 131-140        | 2         | 1.98%   |
| 61-70          | 1         | 0.99%   |
| 51-60          | 1         | 0.99%   |
| 351-500        | 1         | 0.99%   |
| 141-150        | 1         | 0.99%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 41        | 41.41%  |
| 121-160       | 38        | 38.38%  |
| 51-100        | 16        | 16.16%  |
| 161-240       | 2         | 2.02%   |
| More than 240 | 1         | 1.01%   |
| 1-50          | 1         | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 76        | 80%     |
| 2     | 14        | 14.74%  |
| 0     | 5         | 5.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 67        | 42.95%  |
| Intel                             | 36        | 23.08%  |
| Qualcomm Atheros                  | 26        | 16.67%  |
| Broadcom                          | 10        | 6.41%   |
| Broadcom Limited                  | 4         | 2.56%   |
| Ralink                            | 3         | 1.92%   |
| Ralink Technology                 | 2         | 1.28%   |
| D-Link                            | 2         | 1.28%   |
| Sierra Wireless                   | 1         | 0.64%   |
| OPPO Electronics                  | 1         | 0.64%   |
| MEDIATEK                          | 1         | 0.64%   |
| Marvell Technology Group          | 1         | 0.64%   |
| Huawei Technologies               | 1         | 0.64%   |
| Ericsson Business Mobile Networks | 1         | 0.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 24.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 9.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 4.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 4.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 3.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 3.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 2.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 2.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 2.14%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 2.14%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 2.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.6%    |
| Intel Wireless 8265 / 8275                                        | 3         | 1.6%    |
| Intel WiFi Link 5100                                              | 3         | 1.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.07%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 1.07%   |
| Intel Wireless 8260                                               | 2         | 1.07%   |
| Intel Wireless 7265                                               | 2         | 1.07%   |
| Intel Wireless 7260                                               | 2         | 1.07%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.07%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.07%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.07%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 2         | 1.07%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.07%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 2         | 1.07%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 1.07%   |
| Sierra Wireless EM7455                                            | 1         | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.53%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.53%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.53%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.53%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.53%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.53%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.53%   |
| OPPO SDM665-IDP _SN:18689828                                      | 1         | 0.53%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.53%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 0.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 0.53%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.53%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.53%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 1         | 0.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 1         | 0.53%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 0.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.53%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 0.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.53%   |
| Huawei HUAWEI                                                     | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 34.65%  |
| Qualcomm Atheros      | 24        | 23.76%  |
| Realtek Semiconductor | 22        | 21.78%  |
| Broadcom              | 7         | 6.93%   |
| Broadcom Limited      | 4         | 3.96%   |
| Ralink                | 3         | 2.97%   |
| Ralink Technology     | 2         | 1.98%   |
| D-Link                | 2         | 1.98%   |
| Sierra Wireless       | 1         | 0.99%   |
| MEDIATEK              | 1         | 0.99%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 7.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 7.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 5.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 5.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 3.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 3.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 3.92%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 3.92%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 3.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.94%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.94%   |
| Intel WiFi Link 5100                                           | 3         | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.96%   |
| Intel Wireless 8260                                            | 2         | 1.96%   |
| Intel Wireless 7265                                            | 2         | 1.96%   |
| Intel Wireless 7260                                            | 2         | 1.96%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.96%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 2         | 1.96%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 1.96%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.96%   |
| Sierra Wireless EM7455                                         | 1         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.98%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.98%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.98%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.98%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.98%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.98%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.98%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.98%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 0.98%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 0.98%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 0.98%   |
| Broadcom Limited BCM43142 802.11b/g/n                          | 1         | 0.98%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 1         | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 64        | 76.19%  |
| Intel                    | 11        | 13.1%   |
| Qualcomm Atheros         | 3         | 3.57%   |
| Broadcom                 | 3         | 3.57%   |
| OPPO Electronics         | 1         | 1.19%   |
| Marvell Technology Group | 1         | 1.19%   |
| Huawei Technologies      | 1         | 1.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 54.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 21.43%  |
| Intel Ethernet Connection I218-LM                                 | 2         | 2.38%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.38%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 2.38%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 2.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.19%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.19%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.19%   |
| OPPO SDM665-IDP _SN:18689828                                      | 1         | 1.19%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 1.19%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.19%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.19%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.19%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.19%   |
| Huawei HUAWEI                                                     | 1         | 1.19%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 93        | 52.84%  |
| Ethernet | 82        | 46.59%  |
| Modem    | 1         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 81        | 68.07%  |
| Ethernet | 38        | 31.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 82        | 87.23%  |
| 1     | 12        | 12.77%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 93        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 34.94%  |
| Realtek Semiconductor           | 17        | 20.48%  |
| Qualcomm Atheros Communications | 15        | 18.07%  |
| Lite-On Technology              | 7         | 8.43%   |
| IMC Networks                    | 3         | 3.61%   |
| Foxconn / Hon Hai               | 3         | 3.61%   |
| Broadcom                        | 3         | 3.61%   |
| Ralink                          | 2         | 2.41%   |
| Toshiba                         | 1         | 1.2%    |
| Realtek                         | 1         | 1.2%    |
| Hewlett-Packard                 | 1         | 1.2%    |
| Dell                            | 1         | 1.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 12        | 14.46%  |
| Realtek Bluetooth Radio                        | 11        | 13.25%  |
| Intel AX201 Bluetooth                          | 10        | 12.05%  |
| Qualcomm Atheros  Bluetooth Device             | 8         | 9.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 5         | 6.02%   |
| Qualcomm Atheros AR3011 Bluetooth              | 4         | 4.82%   |
| Realtek  Bluetooth 4.2 Adapter                 | 3         | 3.61%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device   | 3         | 3.61%   |
| Realtek RTL8723B Bluetooth                     | 2         | 2.41%   |
| Ralink RT3290 Bluetooth                        | 2         | 2.41%   |
| Lite-On Bluetooth Device                       | 2         | 2.41%   |
| IMC Networks Bluetooth Radio                   | 2         | 2.41%   |
| Foxconn / Hon Hai Bluetooth Device             | 2         | 2.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 2         | 2.41%   |
| Toshiba Bluetooth USB Host Controller          | 1         | 1.2%    |
| Realtek 802.11n WLAN Adapter                   | 1         | 1.2%    |
| Realtek Bluetooth Radio                        | 1         | 1.2%    |
| Qualcomm Atheros Bluetooth USB Host Controller | 1         | 1.2%    |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 1         | 1.2%    |
| Lite-On Atheros AR3012 Bluetooth               | 1         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth               | 1         | 1.2%    |
| Intel Bluetooth Device                         | 1         | 1.2%    |
| IMC Networks Wireless_Device                   | 1         | 1.2%    |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 1.2%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth  | 1         | 1.2%    |
| Dell DW375 Bluetooth Module                    | 1         | 1.2%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 1         | 1.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 81        | 69.23%  |
| Nvidia                    | 18        | 15.38%  |
| AMD                       | 15        | 12.82%  |
| Sennheiser Communications | 1         | 0.85%   |
| JMTek                     | 1         | 0.85%   |
| C-Media Electronics       | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 11.03%  |
| Intel 8 Series HD Audio Controller                                                                | 8         | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 5.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 5.15%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 5.15%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 4.41%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 4.41%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 3.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 2.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 2.94%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 2.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 2.94%   |
| AMD High Definition Audio Controller                                                              | 4         | 2.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.21%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.21%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.47%   |
| Nvidia Audio device                                                                               | 2         | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.47%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.47%   |
| Sennheiser Communications Headset [PC 8]                                                          | 1         | 0.74%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.74%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.74%   |
| JMTek USB PnP Audio Device(EEPROM)                                                                | 1         | 0.74%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.74%   |
| C-Media Electronics Redragon Gaming Headset                                                       | 1         | 0.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.74%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.74%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23        | 31.51%  |
| SK Hynix            | 12        | 16.44%  |
| Micron Technology   | 9         | 12.33%  |
| Team                | 6         | 8.22%   |
| A-DATA Technology   | 6         | 8.22%   |
| Crucial             | 4         | 5.48%   |
| Unknown             | 2         | 2.74%   |
| Toshiba             | 2         | 2.74%   |
| Nanya Technology    | 2         | 2.74%   |
| Kingston            | 2         | 2.74%   |
| Elpida              | 2         | 2.74%   |
| Ramaxel Technology  | 1         | 1.37%   |
| Hikvision           | 1         | 1.37%   |
| ASint Technology    | 1         | 1.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                     | 3         | 3.75%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s              | 2         | 2.5%    |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s               | 2         | 2.5%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s           | 2         | 2.5%    |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s           | 2         | 2.5%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 2         | 2.5%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 2         | 2.5%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s           | 2         | 2.5%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s           | 2         | 2.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 2.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 2.5%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 2.5%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s            | 2         | 2.5%    |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                  | 1         | 1.25%   |
| Unknown RAM Module 4096MB SODIMM DDR3                           | 1         | 1.25%   |
| Team RAM TEAMGROUP-SD4-2400 8192MB SODIMM DDR4 8400MT/s         | 1         | 1.25%   |
| Team RAM Module 8192MB SODIMM DDR4 2667MT/s                     | 1         | 1.25%   |
| SK Hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR 975MT/s            | 1         | 1.25%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.25%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.25%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.25%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s          | 1         | 1.25%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 1.25%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.25%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 1         | 1.25%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s          | 1         | 1.25%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s        | 1         | 1.25%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s        | 1         | 1.25%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s           | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s           | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.25%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.25%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s           | 1         | 1.25%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 1         | 1.25%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s           | 1         | 1.25%   |
| Samsung RAM K4F8E304HB-MGCJ 1024MB SODIMM LPDDR4 2400MT/s       | 1         | 1.25%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s         | 1         | 1.25%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.25%   |
| Micron RAM Module 4096MB SODIMM DDR4 3200MT/s                   | 1         | 1.25%   |
| Micron RAM L1G32D4PG107WT:B 8192MB Row Of Chips LPDDR3 1867MT/s | 1         | 1.25%   |
| Micron RAM 8KTF51264HZ-1G9N1 4096MB SODIMM DDR3 1867MT/s        | 1         | 1.25%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s        | 1         | 1.25%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16384MB SODIMM DDR4 3200MT/s        | 1         | 1.25%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s            | 1         | 1.25%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s           | 1         | 1.25%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.25%   |
| Kingston RAM HP24D4S7S8MB-4 4GB SODIMM DDR4 2400MT/s            | 1         | 1.25%   |
| Kingston RAM 99U5295-011.A00LF 2048MB SODIMM DDR2 667MT/s       | 1         | 1.25%   |
| Hikvision RAM HKED4162DAB1D0ZA1 16384MB SODIMM DDR4 2667MT/s    | 1         | 1.25%   |
| Elpida RAM EDJ8416E6MB-GN-F 4GB Chip DDR3 1600MT/s              | 1         | 1.25%   |
| Elpida RAM EBJ81UG8EFU5-GNL-F 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| Crucial RAM CT8G4SFRA266.C8FE 8GB SODIMM DDR4 2667MT/s          | 1         | 1.25%   |
| Crucial RAM CT51264BF1339.C16F 4096MB SODIMM DDR3 1334MT/s      | 1         | 1.25%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s        | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 56.9%   |
| DDR3   | 17        | 29.31%  |
| DDR2   | 3         | 5.17%   |
| SDRAM  | 2         | 3.45%   |
| LPDDR4 | 2         | 3.45%   |
| LPDDR3 | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 54        | 93.1%   |
| Row Of Chips | 3         | 5.17%   |
| Chip         | 1         | 1.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 28        | 40%     |
| 8192  | 21        | 30%     |
| 16384 | 8         | 11.43%  |
| 2048  | 8         | 11.43%  |
| 32768 | 4         | 5.71%   |
| 1024  | 1         | 1.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 20        | 29.85%  |
| 3200    | 11        | 16.42%  |
| 1600    | 11        | 16.42%  |
| 1334    | 7         | 10.45%  |
| 2400    | 5         | 7.46%   |
| 4199    | 2         | 2.99%   |
| 2133    | 2         | 2.99%   |
| 1867    | 2         | 2.99%   |
| 1066    | 2         | 2.99%   |
| 8400    | 1         | 1.49%   |
| 3266    | 1         | 1.49%   |
| 975     | 1         | 1.49%   |
| 667     | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

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
| Chicony Electronics                    | 18        | 21.18%  |
| Realtek Semiconductor                  | 13        | 15.29%  |
| IMC Networks                           | 11        | 12.94%  |
| Microdia                               | 7         | 8.24%   |
| Suyin                                  | 6         | 7.06%   |
| Acer                                   | 6         | 7.06%   |
| Lite-On Technology                     | 5         | 5.88%   |
| Sunplus Innovation Technology          | 4         | 4.71%   |
| Syntek                                 | 3         | 3.53%   |
| Quanta                                 | 3         | 3.53%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.53%   |
| Luxvisions Innotech Limited            | 2         | 2.35%   |
| Silicon Motion                         | 1         | 1.18%   |
| Ricoh                                  | 1         | 1.18%   |
| Apple                                  | 1         | 1.18%   |
| Alcor Micro                            | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 5.81%   |
| Chicony Integrated Camera                                                  | 4         | 4.65%   |
| Realtek USB Camera                                                         | 3         | 3.49%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 3.49%   |
| Lite-On Integrated Camera                                                  | 3         | 3.49%   |
| IMC Networks Integrated Camera                                             | 3         | 3.49%   |
| Acer Integrated Camera                                                     | 3         | 3.49%   |
| Syntek EasyCamera                                                          | 2         | 2.33%   |
| Suyin HP TrueVision HD                                                     | 2         | 2.33%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 2.33%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 2.33%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 2.33%   |
| Quanta HD WebCam                                                           | 2         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 2.33%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 2         | 2.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 2.33%   |
| Chicony Lenovo EasyCamera                                                  | 2         | 2.33%   |
| Chicony HD WebCam                                                          | 2         | 2.33%   |
| Chicony EasyCamera                                                         | 2         | 2.33%   |
| Syntek Integrated Camera                                                   | 1         | 1.16%   |
| Suyin USB 2.0 Camera                                                       | 1         | 1.16%   |
| Suyin HP Integrated Webcam                                                 | 1         | 1.16%   |
| Suyin HD WebCam                                                            | 1         | 1.16%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 1         | 1.16%   |
| Sunplus HD User Facing                                                     | 1         | 1.16%   |
| Sunplus Dell HD Webcam                                                     | 1         | 1.16%   |
| Silicon Motion WebCam SC-13HDL11431N                                       | 1         | 1.16%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 1         | 1.16%   |
| Realtek Integrated Webcam_HD                                               | 1         | 1.16%   |
| Realtek HP Webcam                                                          | 1         | 1.16%   |
| Realtek EasyCamera                                                         | 1         | 1.16%   |
| Quanta HP Webcam                                                           | 1         | 1.16%   |
| Microdia Webcam SC-10HDD12636P                                             | 1         | 1.16%   |
| Microdia HP Webcam                                                         | 1         | 1.16%   |
| Microdia HP Integrated Webcam                                              | 1         | 1.16%   |
| Lite-On TOSHIBA Web Camera - HD                                            | 1         | 1.16%   |
| Lite-On HP HD Camera                                                       | 1         | 1.16%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.16%   |
| IMC Networks Lenovo EasyCamera                                             | 1         | 1.16%   |
| IMC Networks HP TrueVision HD Camera                                       | 1         | 1.16%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 1.16%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 1.16%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 1.16%   |
| Chicony TOSHIBA Web Camera                                                 | 1         | 1.16%   |
| Chicony Sony Visual Communication Camera                                   | 1         | 1.16%   |
| Chicony HP Webcam [2 MP Macro]                                             | 1         | 1.16%   |
| Chicony HP Webcam                                                          | 1         | 1.16%   |
| Chicony HD WebCam (Acer)                                                   | 1         | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 1         | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 1         | 1.16%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 1.16%   |
| Alcor Micro HP Webcam-101                                                  | 1         | 1.16%   |
| Acer Lenovo EasyCamera                                                     | 1         | 1.16%   |
| Acer Integrated IR Camera                                                  | 1         | 1.16%   |
| Acer HD Webcam                                                             | 1         | 1.16%   |
| Acer EasyCamera                                                            | 1         | 1.16%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 50%     |
| LighTuning Technology      | 2         | 25%     |
| Synaptics                  | 1         | 12.5%   |
| Shenzhen Goodix Technology | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| LighTuning EgisTec Touch Fingerprint Sensor      | 2         | 25%     |
| Validity Sensors VFS495 Fingerprint Reader       | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor     | 1         | 12.5%   |
| Validity Sensors Synaptics WBDI                  | 1         | 12.5%   |
| Validity Sensors Fingerprint scanner             | 1         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device              | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom 5880                                                                | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 65        | 64.36%  |
| 1     | 29        | 28.71%  |
| 3     | 4         | 3.96%   |
| 2     | 2         | 1.98%   |
| 4     | 1         | 0.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 12        | 26.67%  |
| Net/wireless             | 10        | 22.22%  |
| Fingerprint reader       | 8         | 17.78%  |
| Bluetooth                | 4         | 8.89%   |
| Communication controller | 3         | 6.67%   |
| Chipcard                 | 3         | 6.67%   |
| Storage                  | 1         | 2.22%   |
| Sound                    | 1         | 2.22%   |
| Network                  | 1         | 2.22%   |
| Card reader              | 1         | 2.22%   |
| Camera                   | 1         | 2.22%   |
