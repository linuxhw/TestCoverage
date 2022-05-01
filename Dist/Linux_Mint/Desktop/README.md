Linux Mint - Tested Hardware & Statistics (Desktops)
----------------------------------------------------

A project to collect tested hardware configurations for Linux Mint.

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

Total: 7901

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Pegatron      | 2AB5                        | [534476ac99](https://linux-hardware.org/?probe=534476ac99) | Apr 30, 2022 |
| LattePanda    | Alpha                       | [4e0dc573e1](https://linux-hardware.org/?probe=4e0dc573e1) | Apr 30, 2022 |
| MSI           | PRO H610M-G DDR4            | [f7806fa6f0](https://linux-hardware.org/?probe=f7806fa6f0) | Apr 30, 2022 |
| HP            | 0AECh D                     | [89441b750f](https://linux-hardware.org/?probe=89441b750f) | Apr 30, 2022 |
| ASUSTek       | P8H61-M                     | [942f86f88a](https://linux-hardware.org/?probe=942f86f88a) | Apr 30, 2022 |
| ASUSTek       | Lancaster8                  | [912f9bb3f9](https://linux-hardware.org/?probe=912f9bb3f9) | Apr 30, 2022 |
| ASRock        | P67 Pro3                    | [8e26d23d06](https://linux-hardware.org/?probe=8e26d23d06) | Apr 30, 2022 |
| Medion        | Cattle24 1M                 | [920d1b35ab](https://linux-hardware.org/?probe=920d1b35ab) | Apr 30, 2022 |
| Gigabyte      | GA-970A-UD3                 | [0158bc69ec](https://linux-hardware.org/?probe=0158bc69ec) | Apr 30, 2022 |
| Gigabyte      | B560M DS3H V2               | [c2096251fc](https://linux-hardware.org/?probe=c2096251fc) | Apr 30, 2022 |
| Gigabyte      | GA-MA770-UD3                | [4924979f39](https://linux-hardware.org/?probe=4924979f39) | Apr 29, 2022 |
| Dell          | 0G261D A00                  | [860d883e5b](https://linux-hardware.org/?probe=860d883e5b) | Apr 29, 2022 |
| Dell          | 0GY6Y8 A03                  | [b4946e7399](https://linux-hardware.org/?probe=b4946e7399) | Apr 29, 2022 |
| MSI           | Z390-A PRO                  | [e2f7ad0f81](https://linux-hardware.org/?probe=e2f7ad0f81) | Apr 29, 2022 |
| Intel         | MAHOBAY                     | [ca65be05f0](https://linux-hardware.org/?probe=ca65be05f0) | Apr 28, 2022 |
| ASRock        | P67 Pro3                    | [95e665d1f5](https://linux-hardware.org/?probe=95e665d1f5) | Apr 28, 2022 |
| ASUSTek       | PRIME B450M-A II            | [21b89b5942](https://linux-hardware.org/?probe=21b89b5942) | Apr 28, 2022 |
| ASUSTek       | PRIME B450M-A II            | [cc6cd50096](https://linux-hardware.org/?probe=cc6cd50096) | Apr 28, 2022 |
| Gigabyte      | B450 AORUS M                | [13f68cfe10](https://linux-hardware.org/?probe=13f68cfe10) | Apr 28, 2022 |
| ASRock        | P67 Pro3                    | [27b6c6ce37](https://linux-hardware.org/?probe=27b6c6ce37) | Apr 28, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [8d8cef9b7d](https://linux-hardware.org/?probe=8d8cef9b7d) | Apr 28, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [6f320b7fcb](https://linux-hardware.org/?probe=6f320b7fcb) | Apr 28, 2022 |
| ASRock        | B550M Pro4                  | [99b46394bf](https://linux-hardware.org/?probe=99b46394bf) | Apr 27, 2022 |
| HP            | 8437                        | [c9444c57eb](https://linux-hardware.org/?probe=c9444c57eb) | Apr 27, 2022 |
| HP            | 8437                        | [cb1aa84569](https://linux-hardware.org/?probe=cb1aa84569) | Apr 27, 2022 |
| Pegatron      | 2A99                        | [92c0dec6fa](https://linux-hardware.org/?probe=92c0dec6fa) | Apr 27, 2022 |
| Medion        | B360H4-EM V1.0              | [9ed05797b0](https://linux-hardware.org/?probe=9ed05797b0) | Apr 27, 2022 |
| Medion        | B360H4-EM V1.0              | [7a35687e1d](https://linux-hardware.org/?probe=7a35687e1d) | Apr 27, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [77c2b99e9b](https://linux-hardware.org/?probe=77c2b99e9b) | Apr 27, 2022 |
| ASRock        | P67 Pro3                    | [fe31926e33](https://linux-hardware.org/?probe=fe31926e33) | Apr 27, 2022 |
| Biostar       | G41D3C                      | [a6db6a2cdf](https://linux-hardware.org/?probe=a6db6a2cdf) | Apr 27, 2022 |
| Biostar       | G41D3C                      | [0a4b95688a](https://linux-hardware.org/?probe=0a4b95688a) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [bd185a521b](https://linux-hardware.org/?probe=bd185a521b) | Apr 27, 2022 |
| MSI           | Z97-G45 GAMING              | [6660cb5133](https://linux-hardware.org/?probe=6660cb5133) | Apr 27, 2022 |
| ASUSTek       | Maximus II Formula          | [66a4342140](https://linux-hardware.org/?probe=66a4342140) | Apr 26, 2022 |
| ASRock        | X300M-STX                   | [35a063e4e9](https://linux-hardware.org/?probe=35a063e4e9) | Apr 26, 2022 |
| ASRock        | P67 Pro3                    | [2e36dc12d2](https://linux-hardware.org/?probe=2e36dc12d2) | Apr 26, 2022 |
| Itautec       | NT 2030                     | [ce556d6808](https://linux-hardware.org/?probe=ce556d6808) | Apr 26, 2022 |
| Biostar       | G41D3C                      | [a91924c1db](https://linux-hardware.org/?probe=a91924c1db) | Apr 26, 2022 |
| Biostar       | G41D3C                      | [cf7cab4e09](https://linux-hardware.org/?probe=cf7cab4e09) | Apr 26, 2022 |
| Dell          | 0WMJ54 A01                  | [ff9f82ef2d](https://linux-hardware.org/?probe=ff9f82ef2d) | Apr 26, 2022 |
| ASRock        | H61M-DGS                    | [c8019d43f7](https://linux-hardware.org/?probe=c8019d43f7) | Apr 25, 2022 |
| HP            | 82FE 11                     | [1b7d145108](https://linux-hardware.org/?probe=1b7d145108) | Apr 25, 2022 |
| ASUSTek       | P5G41T-M LX3                | [43adb86887](https://linux-hardware.org/?probe=43adb86887) | Apr 25, 2022 |
| ASUSTek       | P5G41T-M LX3                | [ba9b8d5ac1](https://linux-hardware.org/?probe=ba9b8d5ac1) | Apr 25, 2022 |
| MSI           | MEG X570 ACE                | [6807da5804](https://linux-hardware.org/?probe=6807da5804) | Apr 25, 2022 |
| MSI           | MEG X570 ACE                | [e558893ff0](https://linux-hardware.org/?probe=e558893ff0) | Apr 25, 2022 |
| HP            | 82FE 11                     | [895a0442d0](https://linux-hardware.org/?probe=895a0442d0) | Apr 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | [37314a1343](https://linux-hardware.org/?probe=37314a1343) | Apr 25, 2022 |
| Positivo      | POS-EIBTDB                  | [2b6822eb50](https://linux-hardware.org/?probe=2b6822eb50) | Apr 24, 2022 |
| ASRock        | P67 Pro3                    | [2aa7f09968](https://linux-hardware.org/?probe=2aa7f09968) | Apr 24, 2022 |
| ASRock        | X300M-STX                   | [096a0bc434](https://linux-hardware.org/?probe=096a0bc434) | Apr 24, 2022 |
| Biostar       | NM70I-1017U                 | [c27061c8f4](https://linux-hardware.org/?probe=c27061c8f4) | Apr 24, 2022 |
| ASRock        | X300M-STX                   | [3e5e1e7137](https://linux-hardware.org/?probe=3e5e1e7137) | Apr 24, 2022 |
| Dell          | 0GY6Y8 A03                  | [58065270dd](https://linux-hardware.org/?probe=58065270dd) | Apr 24, 2022 |
| ASRock        | B550M Pro4                  | [3d46ae9ba9](https://linux-hardware.org/?probe=3d46ae9ba9) | Apr 23, 2022 |
| ASRock        | P67 Pro3                    | [37473be9b0](https://linux-hardware.org/?probe=37473be9b0) | Apr 23, 2022 |
| Pegatron      | IPPPV-D3G                   | [2eea78768b](https://linux-hardware.org/?probe=2eea78768b) | Apr 23, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [475131a6f4](https://linux-hardware.org/?probe=475131a6f4) | Apr 23, 2022 |
| Biostar       | G41D3C                      | [ac5c2d8b54](https://linux-hardware.org/?probe=ac5c2d8b54) | Apr 23, 2022 |
| Biostar       | G41D3C                      | [6fdf919c55](https://linux-hardware.org/?probe=6fdf919c55) | Apr 23, 2022 |
| ASRock        | B85M Pro3                   | [551ea1b91f](https://linux-hardware.org/?probe=551ea1b91f) | Apr 23, 2022 |
| MSI           | H510M PRO                   | [62b9c33cba](https://linux-hardware.org/?probe=62b9c33cba) | Apr 23, 2022 |
| HP            | 0AECh D                     | [5fd33a9a4e](https://linux-hardware.org/?probe=5fd33a9a4e) | Apr 23, 2022 |
| Gigabyte      | B550M DS3H                  | [c668e0d48e](https://linux-hardware.org/?probe=c668e0d48e) | Apr 23, 2022 |
| ASUSTek       | PRIME Z590-A                | [7f7ea99704](https://linux-hardware.org/?probe=7f7ea99704) | Apr 23, 2022 |
| MSI           | 770-G45                     | [5c1bce29f2](https://linux-hardware.org/?probe=5c1bce29f2) | Apr 23, 2022 |
| Dell          | 0XR1GT A00                  | [fb3d31a363](https://linux-hardware.org/?probe=fb3d31a363) | Apr 23, 2022 |
| Dell          | 0XR1GT A00                  | [a0eb199a0c](https://linux-hardware.org/?probe=a0eb199a0c) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [7ad6e17281](https://linux-hardware.org/?probe=7ad6e17281) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [73c09c4d29](https://linux-hardware.org/?probe=73c09c4d29) | Apr 23, 2022 |
| Dell          | 0HY9JP A00                  | [9a884ccaa8](https://linux-hardware.org/?probe=9a884ccaa8) | Apr 23, 2022 |
| Lenovo        | NO DPK                      | [709f4d5f8c](https://linux-hardware.org/?probe=709f4d5f8c) | Apr 22, 2022 |
| ASUSTek       | PRIME X570-P                | [2c7cee55b7](https://linux-hardware.org/?probe=2c7cee55b7) | Apr 22, 2022 |
| ASUSTek       | PRIME X570-P                | [b8a5ec8483](https://linux-hardware.org/?probe=b8a5ec8483) | Apr 22, 2022 |
| Medion        | H110H4-EM                   | [bdbf84afd8](https://linux-hardware.org/?probe=bdbf84afd8) | Apr 22, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [8888cb88d3](https://linux-hardware.org/?probe=8888cb88d3) | Apr 22, 2022 |
| Intel         | X99                         | [f7410bb2fd](https://linux-hardware.org/?probe=f7410bb2fd) | Apr 21, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [9a6d4db5b7](https://linux-hardware.org/?probe=9a6d4db5b7) | Apr 21, 2022 |
| Dell          | 042P49 A02                  | [40c3ccc42c](https://linux-hardware.org/?probe=40c3ccc42c) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [ff5e15c4d9](https://linux-hardware.org/?probe=ff5e15c4d9) | Apr 21, 2022 |
| Gigabyte      | B85M-D3H                    | [3e69787ee4](https://linux-hardware.org/?probe=3e69787ee4) | Apr 21, 2022 |
| MSI           | X470 GAMING PLUS            | [54084b1049](https://linux-hardware.org/?probe=54084b1049) | Apr 20, 2022 |
| Dell          | 06D7TR A01                  | [fe1217f09c](https://linux-hardware.org/?probe=fe1217f09c) | Apr 20, 2022 |
| ASRock        | B450M Pro4-F                | [68d9ef89c7](https://linux-hardware.org/?probe=68d9ef89c7) | Apr 19, 2022 |
| Medion        | D3F3-EM2                    | [733df830d1](https://linux-hardware.org/?probe=733df830d1) | Apr 19, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | [0fd05faa69](https://linux-hardware.org/?probe=0fd05faa69) | Apr 19, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [5d0b8a14f2](https://linux-hardware.org/?probe=5d0b8a14f2) | Apr 18, 2022 |
| ASUSTek       | M4A87TD/USB3                | [bee196bace](https://linux-hardware.org/?probe=bee196bace) | Apr 18, 2022 |
| Dell          | 06D7TR A01                  | [36f481beb4](https://linux-hardware.org/?probe=36f481beb4) | Apr 18, 2022 |
| ASRock        | 970 Pro3 R2.0               | [fefd073d6d](https://linux-hardware.org/?probe=fefd073d6d) | Apr 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [179b76718e](https://linux-hardware.org/?probe=179b76718e) | Apr 18, 2022 |
| ASUSTek       | PRIME Z390-A                | [81d7ace164](https://linux-hardware.org/?probe=81d7ace164) | Apr 18, 2022 |
| Gigabyte      | X570 GAMING X               | [d0cd53048e](https://linux-hardware.org/?probe=d0cd53048e) | Apr 18, 2022 |
| Gigabyte      | X570 GAMING X               | [8436ff452b](https://linux-hardware.org/?probe=8436ff452b) | Apr 18, 2022 |
| MSI           | Z77A-GD65                   | [0350456f3b](https://linux-hardware.org/?probe=0350456f3b) | Apr 17, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [b35ed6654a](https://linux-hardware.org/?probe=b35ed6654a) | Apr 17, 2022 |
| ASRock        | P67 Pro3                    | [18865ac675](https://linux-hardware.org/?probe=18865ac675) | Apr 17, 2022 |
| HP            | 3396                        | [2c07ec89d4](https://linux-hardware.org/?probe=2c07ec89d4) | Apr 17, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [063cead5c3](https://linux-hardware.org/?probe=063cead5c3) | Apr 17, 2022 |
| ASUSTek       | P5GC-MX                     | [55cd1e5c8f](https://linux-hardware.org/?probe=55cd1e5c8f) | Apr 17, 2022 |
| MSI           | H510M PRO                   | [a9ce7c295a](https://linux-hardware.org/?probe=a9ce7c295a) | Apr 17, 2022 |
| AZW           | U59                         | [fc7e5f0c5c](https://linux-hardware.org/?probe=fc7e5f0c5c) | Apr 16, 2022 |
| AZW           | U59                         | [377d280037](https://linux-hardware.org/?probe=377d280037) | Apr 16, 2022 |
| ASUSTek       | P6T DELUXE                  | [1ceaddfc92](https://linux-hardware.org/?probe=1ceaddfc92) | Apr 16, 2022 |
| ASUSTek       | A68HM-PLUS                  | [0bfefd6499](https://linux-hardware.org/?probe=0bfefd6499) | Apr 16, 2022 |
| MSI           | B560M-A PRO                 | [c394557d17](https://linux-hardware.org/?probe=c394557d17) | Apr 16, 2022 |
| MSI           | H110M PRO-VD                | [2fc240d0aa](https://linux-hardware.org/?probe=2fc240d0aa) | Apr 16, 2022 |
| ASUSTek       | A88XM-A                     | [427335d90c](https://linux-hardware.org/?probe=427335d90c) | Apr 16, 2022 |
| Dell          | 06D7TR A01                  | [9a21a6c0f4](https://linux-hardware.org/?probe=9a21a6c0f4) | Apr 16, 2022 |
| ASUSTek       | P5VD2-MX                    | [57fec52891](https://linux-hardware.org/?probe=57fec52891) | Apr 16, 2022 |
| ASRock        | P67 Pro3                    | [2f98f9cdee](https://linux-hardware.org/?probe=2f98f9cdee) | Apr 16, 2022 |
| Supermicro    | H8QG6                       | [060f1e3d34](https://linux-hardware.org/?probe=060f1e3d34) | Apr 16, 2022 |
| Dell          | 0VYXHD A00                  | [4280de633d](https://linux-hardware.org/?probe=4280de633d) | Apr 16, 2022 |
| ASUSTek       | M5A97 R2.0                  | [6f358d55e7](https://linux-hardware.org/?probe=6f358d55e7) | Apr 16, 2022 |
| Fujitsu Si... | D2750-A2 S26361-D2750-A2    | [44b99daa8e](https://linux-hardware.org/?probe=44b99daa8e) | Apr 16, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [d7f72a830c](https://linux-hardware.org/?probe=d7f72a830c) | Apr 15, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [623024de22](https://linux-hardware.org/?probe=623024de22) | Apr 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [9d2aeecf05](https://linux-hardware.org/?probe=9d2aeecf05) | Apr 15, 2022 |
| Gigabyte      | H370M DS3H-CF               | [c3eadb27ad](https://linux-hardware.org/?probe=c3eadb27ad) | Apr 15, 2022 |
| BESSTAR Te... | TL50                        | [28dba12634](https://linux-hardware.org/?probe=28dba12634) | Apr 15, 2022 |
| ASUSTek       | P8Z77-V LX                  | [997b338c67](https://linux-hardware.org/?probe=997b338c67) | Apr 15, 2022 |
| Dell          | 0P01GV A03                  | [7d156875bb](https://linux-hardware.org/?probe=7d156875bb) | Apr 15, 2022 |
| Dell          | 06X1TJ A00                  | [d92d515d6b](https://linux-hardware.org/?probe=d92d515d6b) | Apr 15, 2022 |
| Dell          | 06X1TJ A00                  | [32b40d296d](https://linux-hardware.org/?probe=32b40d296d) | Apr 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [96faf32841](https://linux-hardware.org/?probe=96faf32841) | Apr 15, 2022 |
| Gigabyte      | B85-HD3                     | [89fb08092b](https://linux-hardware.org/?probe=89fb08092b) | Apr 15, 2022 |
| ASUSTek       | P7P55D LE                   | [381477f3e6](https://linux-hardware.org/?probe=381477f3e6) | Apr 15, 2022 |
| Dell          | 0200DY A00                  | [1b0ad4ce13](https://linux-hardware.org/?probe=1b0ad4ce13) | Apr 14, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [6bc3ced902](https://linux-hardware.org/?probe=6bc3ced902) | Apr 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [b30795783f](https://linux-hardware.org/?probe=b30795783f) | Apr 14, 2022 |
| HP            | 3048h                       | [2d19799047](https://linux-hardware.org/?probe=2d19799047) | Apr 14, 2022 |
| ASUSTek       | PRIME X570-P                | [57a3a5a999](https://linux-hardware.org/?probe=57a3a5a999) | Apr 14, 2022 |
| Biostar       | H61MHV2                     | [e05349d6a0](https://linux-hardware.org/?probe=e05349d6a0) | Apr 14, 2022 |
| ASUSTek       | PRIME X570-P                | [f9b71f206c](https://linux-hardware.org/?probe=f9b71f206c) | Apr 14, 2022 |
| Dell          | 0773VG A00                  | [3f0d544715](https://linux-hardware.org/?probe=3f0d544715) | Apr 14, 2022 |
| ASUSTek       | P8H67-M                     | [ca7dd7880b](https://linux-hardware.org/?probe=ca7dd7880b) | Apr 14, 2022 |
| Dell          | 0D28YY A02                  | [c1ff26008f](https://linux-hardware.org/?probe=c1ff26008f) | Apr 14, 2022 |
| HP            | 18E5                        | [3b4f9e8525](https://linux-hardware.org/?probe=3b4f9e8525) | Apr 13, 2022 |
| MSI           | H81M-E33                    | [460099f77f](https://linux-hardware.org/?probe=460099f77f) | Apr 13, 2022 |
| Dell          | 0773VG A00                  | [e0ebd58f3d](https://linux-hardware.org/?probe=e0ebd58f3d) | Apr 13, 2022 |
| ASUSTek       | X99-A                       | [2ac66bb174](https://linux-hardware.org/?probe=2ac66bb174) | Apr 13, 2022 |
| Dell          | 0GY6Y8 A02                  | [5f2f221d6c](https://linux-hardware.org/?probe=5f2f221d6c) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [13ad3d5cb4](https://linux-hardware.org/?probe=13ad3d5cb4) | Apr 13, 2022 |
| Dell          | 0XCR8D A00                  | [d0f55067b0](https://linux-hardware.org/?probe=d0f55067b0) | Apr 13, 2022 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [5f4fac95df](https://linux-hardware.org/?probe=5f4fac95df) | Apr 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [4a91953dcb](https://linux-hardware.org/?probe=4a91953dcb) | Apr 13, 2022 |
| Gigabyte      | H87M-D3H                    | [f638f9b557](https://linux-hardware.org/?probe=f638f9b557) | Apr 13, 2022 |
| Dell          | 0HY9JP A02                  | [ee1ec3e09d](https://linux-hardware.org/?probe=ee1ec3e09d) | Apr 13, 2022 |
| Dell          | 0YXT71 A01                  | [682a5bc6cc](https://linux-hardware.org/?probe=682a5bc6cc) | Apr 13, 2022 |
| ASUSTek       | PRIME A320M-K               | [7d0cde0bcd](https://linux-hardware.org/?probe=7d0cde0bcd) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [f75dc153d0](https://linux-hardware.org/?probe=f75dc153d0) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [438f675016](https://linux-hardware.org/?probe=438f675016) | Apr 13, 2022 |
| Gigabyte      | H61M-DS2                    | [af56c63db4](https://linux-hardware.org/?probe=af56c63db4) | Apr 12, 2022 |
| ASRock        | P67 Pro3                    | [a96f6cbac7](https://linux-hardware.org/?probe=a96f6cbac7) | Apr 12, 2022 |
| Lenovo        | MAHOBAY 31900005 STD        | [d82d73ba0a](https://linux-hardware.org/?probe=d82d73ba0a) | Apr 12, 2022 |
| ASUSTek       | H110M-R                     | [eaf3d1ac6f](https://linux-hardware.org/?probe=eaf3d1ac6f) | Apr 12, 2022 |
| MSI           | X570-A PRO                  | [5d33b64d12](https://linux-hardware.org/?probe=5d33b64d12) | Apr 12, 2022 |
| MSI           | H510M PRO                   | [19dffc4e17](https://linux-hardware.org/?probe=19dffc4e17) | Apr 12, 2022 |
| MSI           | H510M PRO                   | [c4cd29bb7f](https://linux-hardware.org/?probe=c4cd29bb7f) | Apr 12, 2022 |
| ASRock        | P67 Pro3                    | [633d0b6693](https://linux-hardware.org/?probe=633d0b6693) | Apr 12, 2022 |
| Toshiba       | STI 010433                  | [9eb114e523](https://linux-hardware.org/?probe=9eb114e523) | Apr 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [3930b32e77](https://linux-hardware.org/?probe=3930b32e77) | Apr 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [1e302e1cce](https://linux-hardware.org/?probe=1e302e1cce) | Apr 12, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [f4cb39e804](https://linux-hardware.org/?probe=f4cb39e804) | Apr 12, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [80c51dad27](https://linux-hardware.org/?probe=80c51dad27) | Apr 12, 2022 |
| Dell          | 0HD5W2 A00                  | [ee2c10f4b2](https://linux-hardware.org/?probe=ee2c10f4b2) | Apr 11, 2022 |
| ASUSTek       | P5B                         | [c8191103ef](https://linux-hardware.org/?probe=c8191103ef) | Apr 11, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | [201076a42a](https://linux-hardware.org/?probe=201076a42a) | Apr 11, 2022 |
| ASUSTek       | Z87-K                       | [c80f104836](https://linux-hardware.org/?probe=c80f104836) | Apr 11, 2022 |
| Gigabyte      | Z97-HD3                     | [0f28cbb37d](https://linux-hardware.org/?probe=0f28cbb37d) | Apr 11, 2022 |
| ASUSTek       | Amberine M                  | [e47a1f2886](https://linux-hardware.org/?probe=e47a1f2886) | Apr 11, 2022 |
| Intel         | DH67BL AAG10189-211         | [e664ba6c5a](https://linux-hardware.org/?probe=e664ba6c5a) | Apr 10, 2022 |
| Dell          | 08NPPY A00                  | [5c2b30a7e1](https://linux-hardware.org/?probe=5c2b30a7e1) | Apr 10, 2022 |
| MSI           | B350I PRO AC                | [8065d41c05](https://linux-hardware.org/?probe=8065d41c05) | Apr 10, 2022 |
| Dell          | 0200DY A00                  | [38488f5c3a](https://linux-hardware.org/?probe=38488f5c3a) | Apr 10, 2022 |
| HP            | 0A64h                       | [45c89ff83d](https://linux-hardware.org/?probe=45c89ff83d) | Apr 10, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [9971d706c5](https://linux-hardware.org/?probe=9971d706c5) | Apr 10, 2022 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [c344a9c7b9](https://linux-hardware.org/?probe=c344a9c7b9) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [0bac47f3e6](https://linux-hardware.org/?probe=0bac47f3e6) | Apr 09, 2022 |
| Acer          | Veriton M6660G V:1.0        | [a41ffdc22b](https://linux-hardware.org/?probe=a41ffdc22b) | Apr 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [59b9f6ab96](https://linux-hardware.org/?probe=59b9f6ab96) | Apr 09, 2022 |
| HP            | 81C9                        | [2eff1b8a02](https://linux-hardware.org/?probe=2eff1b8a02) | Apr 09, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [27e9b2e124](https://linux-hardware.org/?probe=27e9b2e124) | Apr 09, 2022 |
| ASUSTek       | PRIME B550M-K               | [acff685c08](https://linux-hardware.org/?probe=acff685c08) | Apr 09, 2022 |
| Foxconn       | A7DA 3 series               | [2fc0654e61](https://linux-hardware.org/?probe=2fc0654e61) | Apr 09, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [8d440b5da5](https://linux-hardware.org/?probe=8d440b5da5) | Apr 09, 2022 |
| ASRock        | X299 Gaming K6              | [86fc074c1f](https://linux-hardware.org/?probe=86fc074c1f) | Apr 09, 2022 |
| Dell          | 033FF6 A00                  | [5a96e1cad1](https://linux-hardware.org/?probe=5a96e1cad1) | Apr 09, 2022 |
| Gigabyte      | 970A-DS3P                   | [f45b500a83](https://linux-hardware.org/?probe=f45b500a83) | Apr 09, 2022 |
| HP            | 0A64h                       | [1dda6c8ea9](https://linux-hardware.org/?probe=1dda6c8ea9) | Apr 09, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [d973a4378b](https://linux-hardware.org/?probe=d973a4378b) | Apr 08, 2022 |
| ASRock        | B450 Pro4                   | [16ac7687a0](https://linux-hardware.org/?probe=16ac7687a0) | Apr 08, 2022 |
| AZW           | U59                         | [d84f7caf26](https://linux-hardware.org/?probe=d84f7caf26) | Apr 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [fc6b27af99](https://linux-hardware.org/?probe=fc6b27af99) | Apr 08, 2022 |
| MSI           | FM2-A75MA-E35               | [5d1a0661c9](https://linux-hardware.org/?probe=5d1a0661c9) | Apr 08, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [f0bec097a1](https://linux-hardware.org/?probe=f0bec097a1) | Apr 08, 2022 |
| HP            | 81C9                        | [80ec21f760](https://linux-hardware.org/?probe=80ec21f760) | Apr 07, 2022 |
| ASRock        | P67 Pro3                    | [c427c69a65](https://linux-hardware.org/?probe=c427c69a65) | Apr 07, 2022 |
| Dell          | 042P49 A02                  | [527c75b918](https://linux-hardware.org/?probe=527c75b918) | Apr 07, 2022 |
| ECS           | IC55H-A                     | [932ee208e2](https://linux-hardware.org/?probe=932ee208e2) | Apr 07, 2022 |
| MSI           | FM2-A75MA-E35               | [b691235c0f](https://linux-hardware.org/?probe=b691235c0f) | Apr 07, 2022 |
| ASUSTek       | B85M-G                      | [c58e24cff5](https://linux-hardware.org/?probe=c58e24cff5) | Apr 07, 2022 |
| Dell          | 0TP406                      | [13fa76c1c5](https://linux-hardware.org/?probe=13fa76c1c5) | Apr 07, 2022 |
| ASRock        | H310CM-ITX/ac               | [60948d1473](https://linux-hardware.org/?probe=60948d1473) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [b9eb04d2d8](https://linux-hardware.org/?probe=b9eb04d2d8) | Apr 07, 2022 |
| ASRock        | P67 Pro3                    | [74599c7684](https://linux-hardware.org/?probe=74599c7684) | Apr 07, 2022 |
| Unknown       | K8M800-8237                 | [791e4eeaae](https://linux-hardware.org/?probe=791e4eeaae) | Apr 07, 2022 |
| ASUSTek       | P5Q-E                       | [224591ad3c](https://linux-hardware.org/?probe=224591ad3c) | Apr 07, 2022 |
| ASUSTek       | P5Q-E                       | [93aa02920a](https://linux-hardware.org/?probe=93aa02920a) | Apr 07, 2022 |
| Biostar       | A55ML2                      | [11d2b22b90](https://linux-hardware.org/?probe=11d2b22b90) | Apr 06, 2022 |
| Dell          | 0VNP2H A01                  | [ce01d1704a](https://linux-hardware.org/?probe=ce01d1704a) | Apr 06, 2022 |
| Dell          | 0U880P A01                  | [584ec9a64f](https://linux-hardware.org/?probe=584ec9a64f) | Apr 06, 2022 |
| Dell          | 0U880P A01                  | [54c8306a14](https://linux-hardware.org/?probe=54c8306a14) | Apr 06, 2022 |
| Dell          | 0TP406                      | [28425b209c](https://linux-hardware.org/?probe=28425b209c) | Apr 06, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [802551fe50](https://linux-hardware.org/?probe=802551fe50) | Apr 06, 2022 |
| MSI           | FM2-A75MA-E35               | [231d07274a](https://linux-hardware.org/?probe=231d07274a) | Apr 06, 2022 |
| Intel         | DH55TC AAE70932-204         | [336fcaa613](https://linux-hardware.org/?probe=336fcaa613) | Apr 05, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [939722b6a7](https://linux-hardware.org/?probe=939722b6a7) | Apr 05, 2022 |
| ASRock        | P67 Pro3                    | [12aa7e9d62](https://linux-hardware.org/?probe=12aa7e9d62) | Apr 05, 2022 |
| Dell          | 0T656F A02                  | [260c2183c2](https://linux-hardware.org/?probe=260c2183c2) | Apr 04, 2022 |
| MSI           | H510M PRO                   | [0874882b3f](https://linux-hardware.org/?probe=0874882b3f) | Apr 04, 2022 |
| Dell          | 02YRK5 A03                  | [8f30fb0a3f](https://linux-hardware.org/?probe=8f30fb0a3f) | Apr 04, 2022 |
| Dell          | 02YRK5 A03                  | [4014bf184c](https://linux-hardware.org/?probe=4014bf184c) | Apr 04, 2022 |
| MSI           | H510M PRO                   | [ee05ef80b8](https://linux-hardware.org/?probe=ee05ef80b8) | Apr 04, 2022 |
| ASRock        | Z270 Killer SLI/ac          | [cd29715a0d](https://linux-hardware.org/?probe=cd29715a0d) | Apr 04, 2022 |
| ASRock        | P67 Pro3                    | [0b85e0a11b](https://linux-hardware.org/?probe=0b85e0a11b) | Apr 04, 2022 |
| ECS           | IC55H-A                     | [a0287a7cca](https://linux-hardware.org/?probe=a0287a7cca) | Apr 04, 2022 |
| MSI           | H510M PRO                   | [e11c2453c5](https://linux-hardware.org/?probe=e11c2453c5) | Apr 04, 2022 |
| HP            | 8643 SMVB                   | [f6e3225172](https://linux-hardware.org/?probe=f6e3225172) | Apr 04, 2022 |
| ASUSTek       | H81M-E                      | [2659a11330](https://linux-hardware.org/?probe=2659a11330) | Apr 04, 2022 |
| ASRock        | P67 Pro3                    | [65b4903fb8](https://linux-hardware.org/?probe=65b4903fb8) | Apr 04, 2022 |
| Gigabyte      | B75M-D3V                    | [16d1981053](https://linux-hardware.org/?probe=16d1981053) | Apr 04, 2022 |
| MSI           | B450 TOMAHAWK               | [4008f4f114](https://linux-hardware.org/?probe=4008f4f114) | Apr 04, 2022 |
| HP            | 1998                        | [d30791d695](https://linux-hardware.org/?probe=d30791d695) | Apr 04, 2022 |
| HP            | 1998                        | [74f1744dce](https://linux-hardware.org/?probe=74f1744dce) | Apr 04, 2022 |
| Gigabyte      | B450M S2H V2                | [f3fde51c72](https://linux-hardware.org/?probe=f3fde51c72) | Apr 03, 2022 |
| ASRock        | 970 Extreme4                | [cc65547e82](https://linux-hardware.org/?probe=cc65547e82) | Apr 03, 2022 |
| ASRock        | H670M-ITX/ax                | [d4dc39b64e](https://linux-hardware.org/?probe=d4dc39b64e) | Apr 03, 2022 |
| Acer          | Predator G3-605             | [7e8eef4976](https://linux-hardware.org/?probe=7e8eef4976) | Apr 03, 2022 |
| HP            | 1790                        | [9b8f0779ab](https://linux-hardware.org/?probe=9b8f0779ab) | Apr 03, 2022 |
| ASRock        | H670M-ITX/ax                | [d97f9a02fe](https://linux-hardware.org/?probe=d97f9a02fe) | Apr 03, 2022 |
| HP            | 1998                        | [4b6628b734](https://linux-hardware.org/?probe=4b6628b734) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0              | [73cf5373cf](https://linux-hardware.org/?probe=73cf5373cf) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0              | [f76380fdae](https://linux-hardware.org/?probe=f76380fdae) | Apr 03, 2022 |
| MSI           | H510M-A PRO                 | [b3dfc0ae31](https://linux-hardware.org/?probe=b3dfc0ae31) | Apr 02, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [dfcfb79dcb](https://linux-hardware.org/?probe=dfcfb79dcb) | Apr 02, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [78665d8f57](https://linux-hardware.org/?probe=78665d8f57) | Apr 02, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [77e2c60730](https://linux-hardware.org/?probe=77e2c60730) | Apr 02, 2022 |
| ASRock        | B85M Pro3                   | [8d14068c4b](https://linux-hardware.org/?probe=8d14068c4b) | Apr 02, 2022 |
| ASRock        | B85M-HDS R2.0               | [9a446ac5fd](https://linux-hardware.org/?probe=9a446ac5fd) | Apr 02, 2022 |
| ASUSTek       | P8H67-M LE                  | [01a521b3d1](https://linux-hardware.org/?probe=01a521b3d1) | Apr 02, 2022 |
| MSI           | Z77A-GD65                   | [d7e7b28b04](https://linux-hardware.org/?probe=d7e7b28b04) | Apr 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | [ba7b7abd34](https://linux-hardware.org/?probe=ba7b7abd34) | Apr 02, 2022 |
| ASRock        | P67 Pro3                    | [f8a2c24557](https://linux-hardware.org/?probe=f8a2c24557) | Apr 02, 2022 |
| Gigabyte      | H410M S2H V3                | [0c9c9dd7e9](https://linux-hardware.org/?probe=0c9c9dd7e9) | Apr 02, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [2d4957c88f](https://linux-hardware.org/?probe=2d4957c88f) | Apr 02, 2022 |
| Toshiba       | STI 010433                  | [daa5ae86bc](https://linux-hardware.org/?probe=daa5ae86bc) | Apr 01, 2022 |
| HP            | 3047h                       | [356fac6a3a](https://linux-hardware.org/?probe=356fac6a3a) | Apr 01, 2022 |
| HP            | 3047h                       | [d4c9852b3c](https://linux-hardware.org/?probe=d4c9852b3c) | Apr 01, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [07d499a6f9](https://linux-hardware.org/?probe=07d499a6f9) | Apr 01, 2022 |
| ASRock        | 775Dual-VSTA                | [f5aea8ce64](https://linux-hardware.org/?probe=f5aea8ce64) | Apr 01, 2022 |
| ASUSTek       | M3A78-EMH HDMI              | [4462ffed73](https://linux-hardware.org/?probe=4462ffed73) | Apr 01, 2022 |
| ASRock        | P67 Pro3                    | [ff19736e64](https://linux-hardware.org/?probe=ff19736e64) | Apr 01, 2022 |
| HP            | 1998                        | [23ca5d6703](https://linux-hardware.org/?probe=23ca5d6703) | Apr 01, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [7633664f7f](https://linux-hardware.org/?probe=7633664f7f) | Apr 01, 2022 |
| ASUSTek       | P5KPL/1600                  | [4da992cdb7](https://linux-hardware.org/?probe=4da992cdb7) | Apr 01, 2022 |
| HP            | 0A64h                       | [732f81838c](https://linux-hardware.org/?probe=732f81838c) | Mar 31, 2022 |
| Intel         | D33217GKE G76540-201        | [04874b84db](https://linux-hardware.org/?probe=04874b84db) | Mar 31, 2022 |
| HP            | 2AA6 PVT                    | [7fbf6dadb4](https://linux-hardware.org/?probe=7fbf6dadb4) | Mar 31, 2022 |
| ASRock        | 960GM-GS3 FX                | [2c9c93fcb5](https://linux-hardware.org/?probe=2c9c93fcb5) | Mar 31, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [a33c598546](https://linux-hardware.org/?probe=a33c598546) | Mar 31, 2022 |
| Gigabyte      | H61M-DS2V                   | [830357fbc8](https://linux-hardware.org/?probe=830357fbc8) | Mar 31, 2022 |
| ASRock        | P67 Pro3                    | [599a17bae2](https://linux-hardware.org/?probe=599a17bae2) | Mar 31, 2022 |
| Gigabyte      | AX370-Gaming K3             | [63f7d865d3](https://linux-hardware.org/?probe=63f7d865d3) | Mar 31, 2022 |
| ASRock        | B75M R2.0                   | [ee7a1d8721](https://linux-hardware.org/?probe=ee7a1d8721) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | [84625838c2](https://linux-hardware.org/?probe=84625838c2) | Mar 30, 2022 |
| ASRock        | P67 Pro3                    | [bacc30fa55](https://linux-hardware.org/?probe=bacc30fa55) | Mar 30, 2022 |
| ASUSTek       | Amberine M                  | [767946408c](https://linux-hardware.org/?probe=767946408c) | Mar 30, 2022 |
| Maita         | NUCCF01                     | [ef888d0be5](https://linux-hardware.org/?probe=ef888d0be5) | Mar 29, 2022 |
| Maita         | NUCCF01                     | [c3c283c0f6](https://linux-hardware.org/?probe=c3c283c0f6) | Mar 29, 2022 |
| ASRock        | P67 Pro3                    | [13e0979200](https://linux-hardware.org/?probe=13e0979200) | Mar 29, 2022 |
| ASUSTek       | P8H67-M LE                  | [3a33018680](https://linux-hardware.org/?probe=3a33018680) | Mar 29, 2022 |
| ASUSTek       | ET2700I                     | [8379cf3a4a](https://linux-hardware.org/?probe=8379cf3a4a) | Mar 29, 2022 |
| ASRock        | P67 Pro3                    | [4df5971e89](https://linux-hardware.org/?probe=4df5971e89) | Mar 29, 2022 |
| ASRock        | B550M Pro4                  | [6755915c96](https://linux-hardware.org/?probe=6755915c96) | Mar 29, 2022 |
| Dell          | 0K83V0 A00                  | [0428ae1966](https://linux-hardware.org/?probe=0428ae1966) | Mar 29, 2022 |
| Dell          | 0K83V0 A00                  | [ef509c5553](https://linux-hardware.org/?probe=ef509c5553) | Mar 29, 2022 |
| MSI           | Z270 PC MATE                | [8193ff7289](https://linux-hardware.org/?probe=8193ff7289) | Mar 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [de17fecb09](https://linux-hardware.org/?probe=de17fecb09) | Mar 28, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [9aa5a3401d](https://linux-hardware.org/?probe=9aa5a3401d) | Mar 28, 2022 |
| Dell          | 0C27VV A04                  | [168c917da8](https://linux-hardware.org/?probe=168c917da8) | Mar 28, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [9688bbdb3f](https://linux-hardware.org/?probe=9688bbdb3f) | Mar 28, 2022 |
| ASUSTek       | H110M-K                     | [4e238835bd](https://linux-hardware.org/?probe=4e238835bd) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX B350-I GAMING     | [36e8a83674](https://linux-hardware.org/?probe=36e8a83674) | Mar 27, 2022 |
| ASUSTek       | PRIME B250M-A               | [1260b540e7](https://linux-hardware.org/?probe=1260b540e7) | Mar 27, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [a96405351a](https://linux-hardware.org/?probe=a96405351a) | Mar 27, 2022 |
| ASUSTek       | Amberine M                  | [cf54d7e964](https://linux-hardware.org/?probe=cf54d7e964) | Mar 27, 2022 |
| ASUSTek       | P8Z77 WS                    | [069d2c186e](https://linux-hardware.org/?probe=069d2c186e) | Mar 27, 2022 |
| Gigabyte      | M61VME-S2                   | [4e68853105](https://linux-hardware.org/?probe=4e68853105) | Mar 27, 2022 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [5efb11c731](https://linux-hardware.org/?probe=5efb11c731) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | [9e095340f3](https://linux-hardware.org/?probe=9e095340f3) | Mar 27, 2022 |
| MSI           | PRO Z690-P DDR4             | [7aac216113](https://linux-hardware.org/?probe=7aac216113) | Mar 26, 2022 |
| Gigabyte      | Z270-Gaming K3              | [fb365f1b1e](https://linux-hardware.org/?probe=fb365f1b1e) | Mar 26, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [b31460778c](https://linux-hardware.org/?probe=b31460778c) | Mar 26, 2022 |
| ASUSTek       | H110M-K                     | [14f509aa32](https://linux-hardware.org/?probe=14f509aa32) | Mar 26, 2022 |
| ASUSTek       | H110M-K                     | [31098e4c80](https://linux-hardware.org/?probe=31098e4c80) | Mar 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [6ebd5ce185](https://linux-hardware.org/?probe=6ebd5ce185) | Mar 26, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [e4526228cd](https://linux-hardware.org/?probe=e4526228cd) | Mar 26, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [402c4d5758](https://linux-hardware.org/?probe=402c4d5758) | Mar 26, 2022 |
| ASRock        | P67 Pro3                    | [515f03c954](https://linux-hardware.org/?probe=515f03c954) | Mar 26, 2022 |
| MSI           | B350I PRO AC                | [9d5ead8832](https://linux-hardware.org/?probe=9d5ead8832) | Mar 26, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [02a3f1feaf](https://linux-hardware.org/?probe=02a3f1feaf) | Mar 26, 2022 |
| Gigabyte      | Z270-Gaming K3              | [d8b099aefa](https://linux-hardware.org/?probe=d8b099aefa) | Mar 26, 2022 |
| Dell          | 0TDG4V A01                  | [4df00a11b0](https://linux-hardware.org/?probe=4df00a11b0) | Mar 25, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [243d5352ef](https://linux-hardware.org/?probe=243d5352ef) | Mar 25, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [88c6d60a0b](https://linux-hardware.org/?probe=88c6d60a0b) | Mar 25, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [023e66a08d](https://linux-hardware.org/?probe=023e66a08d) | Mar 25, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [2a333a0767](https://linux-hardware.org/?probe=2a333a0767) | Mar 25, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [381e2b1130](https://linux-hardware.org/?probe=381e2b1130) | Mar 25, 2022 |
| Dell          | 0JP3NX A01                  | [60eeaf871f](https://linux-hardware.org/?probe=60eeaf871f) | Mar 25, 2022 |
| ASUSTek       | P9X79 PRO                   | [4f717acbaa](https://linux-hardware.org/?probe=4f717acbaa) | Mar 24, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [55171208ed](https://linux-hardware.org/?probe=55171208ed) | Mar 24, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [80fa34cf94](https://linux-hardware.org/?probe=80fa34cf94) | Mar 24, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [4ce05dd1e2](https://linux-hardware.org/?probe=4ce05dd1e2) | Mar 24, 2022 |
| ASRock        | N68C-S UCC                  | [da1fd40737](https://linux-hardware.org/?probe=da1fd40737) | Mar 24, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | [090041bea7](https://linux-hardware.org/?probe=090041bea7) | Mar 24, 2022 |
| Dell          | 0M863N A01                  | [c05eaeb499](https://linux-hardware.org/?probe=c05eaeb499) | Mar 24, 2022 |
| HP            | 1998                        | [ec47a4edb9](https://linux-hardware.org/?probe=ec47a4edb9) | Mar 24, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [7c4be75815](https://linux-hardware.org/?probe=7c4be75815) | Mar 23, 2022 |
| Shuttle       | FH61V                       | [9b18d7b2ed](https://linux-hardware.org/?probe=9b18d7b2ed) | Mar 23, 2022 |
| Gigabyte      | X99-Designare EX-CF         | [868791f75e](https://linux-hardware.org/?probe=868791f75e) | Mar 23, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [39b19d4ecf](https://linux-hardware.org/?probe=39b19d4ecf) | Mar 22, 2022 |
| HP            | 3397                        | [51dd330f09](https://linux-hardware.org/?probe=51dd330f09) | Mar 22, 2022 |
| Biostar       | H61MLV2                     | [1bce4dc771](https://linux-hardware.org/?probe=1bce4dc771) | Mar 22, 2022 |
| Biostar       | H61MLV2                     | [4d97559516](https://linux-hardware.org/?probe=4d97559516) | Mar 22, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [5298f9dcc9](https://linux-hardware.org/?probe=5298f9dcc9) | Mar 22, 2022 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [d1fd7ebdcc](https://linux-hardware.org/?probe=d1fd7ebdcc) | Mar 22, 2022 |
| ASUSTek       | X99-M WS                    | [5f29519a18](https://linux-hardware.org/?probe=5f29519a18) | Mar 22, 2022 |
| MSI           | 970 GAMING                  | [45c6461d6c](https://linux-hardware.org/?probe=45c6461d6c) | Mar 22, 2022 |
| ASRock        | Z370 Extreme4               | [f39b16204a](https://linux-hardware.org/?probe=f39b16204a) | Mar 22, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e3d131ff9a](https://linux-hardware.org/?probe=e3d131ff9a) | Mar 22, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [dec65a823a](https://linux-hardware.org/?probe=dec65a823a) | Mar 22, 2022 |
| Gigabyte      | 970A-DS3P                   | [012e192ece](https://linux-hardware.org/?probe=012e192ece) | Mar 22, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [4492e433cd](https://linux-hardware.org/?probe=4492e433cd) | Mar 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [366258c1f2](https://linux-hardware.org/?probe=366258c1f2) | Mar 21, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [dd7543bdb3](https://linux-hardware.org/?probe=dd7543bdb3) | Mar 21, 2022 |
| HP            | 3032h                       | [e57d52908c](https://linux-hardware.org/?probe=e57d52908c) | Mar 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f4552c4008](https://linux-hardware.org/?probe=f4552c4008) | Mar 21, 2022 |
| ASUSTek       | Crosshair IV Formula        | [b379b1157c](https://linux-hardware.org/?probe=b379b1157c) | Mar 21, 2022 |
| Gigabyte      | Z490 VISION D               | [da9773a25d](https://linux-hardware.org/?probe=da9773a25d) | Mar 21, 2022 |
| MSI           | Z87-G45 GAMING              | [a4d8d08ea6](https://linux-hardware.org/?probe=a4d8d08ea6) | Mar 21, 2022 |
| Intel         | DH55TC AAE70932-301         | [e0c4ac33b9](https://linux-hardware.org/?probe=e0c4ac33b9) | Mar 21, 2022 |
| MSI           | X570-A PRO                  | [622384c18e](https://linux-hardware.org/?probe=622384c18e) | Mar 20, 2022 |
| HP            | 3397                        | [60dc930e32](https://linux-hardware.org/?probe=60dc930e32) | Mar 20, 2022 |
| VIA Techno... | KM266-8235                  | [ad3f9e9e12](https://linux-hardware.org/?probe=ad3f9e9e12) | Mar 20, 2022 |
| Dell          | 042P49 A02                  | [1a94f7526c](https://linux-hardware.org/?probe=1a94f7526c) | Mar 20, 2022 |
| Gigabyte      | H510M H                     | [4e555a8efa](https://linux-hardware.org/?probe=4e555a8efa) | Mar 20, 2022 |
| Gigabyte      | G41MT-S2PT                  | [ddc4f4eb12](https://linux-hardware.org/?probe=ddc4f4eb12) | Mar 20, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [b4287e3cb1](https://linux-hardware.org/?probe=b4287e3cb1) | Mar 20, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [991793e09e](https://linux-hardware.org/?probe=991793e09e) | Mar 20, 2022 |
| ASRock        | H370M-HDV                   | [9945efc3fa](https://linux-hardware.org/?probe=9945efc3fa) | Mar 20, 2022 |
| Dell          | 0P01GV A03                  | [54c52f2837](https://linux-hardware.org/?probe=54c52f2837) | Mar 19, 2022 |
| ASRock        | A55M-HVS                    | [b10a9e37bb](https://linux-hardware.org/?probe=b10a9e37bb) | Mar 19, 2022 |
| Acer          | Aspire XC600 v1.0           | [4191a185d4](https://linux-hardware.org/?probe=4191a185d4) | Mar 19, 2022 |
| Dell          | 0R6PCT A01                  | [de08cb0741](https://linux-hardware.org/?probe=de08cb0741) | Mar 19, 2022 |
| ECS           | A990FXM-A                   | [32deb5b6a1](https://linux-hardware.org/?probe=32deb5b6a1) | Mar 19, 2022 |
| Unknown       | X79-P3                      | [df0d4ee1a9](https://linux-hardware.org/?probe=df0d4ee1a9) | Mar 19, 2022 |
| Unknown       | X79-P3                      | [ab104fe8c0](https://linux-hardware.org/?probe=ab104fe8c0) | Mar 19, 2022 |
| MSI           | X370 GAMING M7 ACK          | [336e7a8d1d](https://linux-hardware.org/?probe=336e7a8d1d) | Mar 19, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6dd4a41851](https://linux-hardware.org/?probe=6dd4a41851) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [a5d1f1ec32](https://linux-hardware.org/?probe=a5d1f1ec32) | Mar 18, 2022 |
| Dell          | 0M863N A01                  | [f23210fa33](https://linux-hardware.org/?probe=f23210fa33) | Mar 18, 2022 |
| ASUSTek       | H81M-K                      | [9055c398c9](https://linux-hardware.org/?probe=9055c398c9) | Mar 18, 2022 |
| Dell          | 08WKV3 A00                  | [147bdbc26d](https://linux-hardware.org/?probe=147bdbc26d) | Mar 18, 2022 |
| Gigabyte      | X48T-DQ6                    | [f63c898bc3](https://linux-hardware.org/?probe=f63c898bc3) | Mar 18, 2022 |
| ASUSTek       | M5A78L LE                   | [d50c3e8e85](https://linux-hardware.org/?probe=d50c3e8e85) | Mar 18, 2022 |
| ASRock        | H570M Pro4                  | [b04e0c4c1c](https://linux-hardware.org/?probe=b04e0c4c1c) | Mar 18, 2022 |
| ASRock        | B560M-ITX/ac                | [58d3e7c461](https://linux-hardware.org/?probe=58d3e7c461) | Mar 18, 2022 |
| Dell          | 0Y5DDC A00                  | [ddca79ef25](https://linux-hardware.org/?probe=ddca79ef25) | Mar 17, 2022 |
| Dell          | 0HD5W2 A00                  | [14d41935a3](https://linux-hardware.org/?probe=14d41935a3) | Mar 17, 2022 |
| Fujitsu Si... | D2750-A2 S26361-D2750-A2    | [0a880e2e5c](https://linux-hardware.org/?probe=0a880e2e5c) | Mar 17, 2022 |
| ASUSTek       | Rampage IV FORMULA          | [433ed3c3d7](https://linux-hardware.org/?probe=433ed3c3d7) | Mar 17, 2022 |
| HP            | 1408h                       | [d80307d774](https://linux-hardware.org/?probe=d80307d774) | Mar 17, 2022 |
| Alienware     | 0PGRP5 A02                  | [8a28919b48](https://linux-hardware.org/?probe=8a28919b48) | Mar 17, 2022 |
| Gigabyte      | EX58-UD5                    | [f445174807](https://linux-hardware.org/?probe=f445174807) | Mar 17, 2022 |
| ASUSTek       | PRIME A320M-K               | [cb5c244ae1](https://linux-hardware.org/?probe=cb5c244ae1) | Mar 17, 2022 |
| ASUSTek       | Z87-A                       | [b671affabe](https://linux-hardware.org/?probe=b671affabe) | Mar 16, 2022 |
| Dell          | 0D28YY A02                  | [a00f7419d4](https://linux-hardware.org/?probe=a00f7419d4) | Mar 16, 2022 |
| ASUSTek       | P8H77-M PRO                 | [f7ee97d348](https://linux-hardware.org/?probe=f7ee97d348) | Mar 16, 2022 |
| Intel         | X99 V1.0                    | [3e1b96fe9f](https://linux-hardware.org/?probe=3e1b96fe9f) | Mar 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2f4e37d664](https://linux-hardware.org/?probe=2f4e37d664) | Mar 16, 2022 |
| ASRock        | X470 Gaming K4              | [90eaa170d1](https://linux-hardware.org/?probe=90eaa170d1) | Mar 15, 2022 |
| Dell          | 0P01GV A03                  | [1272dc8512](https://linux-hardware.org/?probe=1272dc8512) | Mar 14, 2022 |
| Positivo      | POS-PIH77CM POSITIVO        | [8420ad7ef2](https://linux-hardware.org/?probe=8420ad7ef2) | Mar 14, 2022 |
| Dell          | 0HD5W2 A00                  | [7284aabd99](https://linux-hardware.org/?probe=7284aabd99) | Mar 14, 2022 |
| MSI           | X99A SLI PLUS               | [3e6960fead](https://linux-hardware.org/?probe=3e6960fead) | Mar 14, 2022 |
| Lenovo        | ThinkStation S20 4157E92    | [a94f68e4dd](https://linux-hardware.org/?probe=a94f68e4dd) | Mar 14, 2022 |
| ASUSTek       | H87-PLUS                    | [41d61ba64b](https://linux-hardware.org/?probe=41d61ba64b) | Mar 14, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [314443b85b](https://linux-hardware.org/?probe=314443b85b) | Mar 14, 2022 |
| HP            | 1589                        | [41622b6b2d](https://linux-hardware.org/?probe=41622b6b2d) | Mar 14, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [34c10545c2](https://linux-hardware.org/?probe=34c10545c2) | Mar 14, 2022 |
| Lenovo        | MAHOBAY NOK                 | [5c3993ef06](https://linux-hardware.org/?probe=5c3993ef06) | Mar 14, 2022 |
| Biostar       | Hi-Fi H61S3                 | [469edf935f](https://linux-hardware.org/?probe=469edf935f) | Mar 14, 2022 |
| MSI           | B450M BAZOOKA V2            | [3dcd349d64](https://linux-hardware.org/?probe=3dcd349d64) | Mar 14, 2022 |
| Purism        | Librem Mini v2              | [909124577c](https://linux-hardware.org/?probe=909124577c) | Mar 14, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [e062006ffe](https://linux-hardware.org/?probe=e062006ffe) | Mar 13, 2022 |
| Dell          | 0GM819                      | [bf94874639](https://linux-hardware.org/?probe=bf94874639) | Mar 13, 2022 |
| MSI           | B360M MORTAR                | [a00a055108](https://linux-hardware.org/?probe=a00a055108) | Mar 13, 2022 |
| HP            | 1589                        | [95af16db2e](https://linux-hardware.org/?probe=95af16db2e) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [561a945c5a](https://linux-hardware.org/?probe=561a945c5a) | Mar 13, 2022 |
| ASRock        | Q1900M                      | [44eb8c4b87](https://linux-hardware.org/?probe=44eb8c4b87) | Mar 13, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [ee1dd1170b](https://linux-hardware.org/?probe=ee1dd1170b) | Mar 13, 2022 |
| ASUSTek       | M4A87TD                     | [aded9135ae](https://linux-hardware.org/?probe=aded9135ae) | Mar 13, 2022 |
| ASRock        | A320M-HDV R4.0              | [84d1a5e923](https://linux-hardware.org/?probe=84d1a5e923) | Mar 13, 2022 |
| Dell          | 0GM819                      | [acc1399bb2](https://linux-hardware.org/?probe=acc1399bb2) | Mar 13, 2022 |
| Gigabyte      | GA-MA770-UD3                | [7092d99cc8](https://linux-hardware.org/?probe=7092d99cc8) | Mar 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [b46a2338a9](https://linux-hardware.org/?probe=b46a2338a9) | Mar 13, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [12b1601612](https://linux-hardware.org/?probe=12b1601612) | Mar 13, 2022 |
| Visum         | A6VMX 0A                    | [82a79d1b3c](https://linux-hardware.org/?probe=82a79d1b3c) | Mar 13, 2022 |
| ASRock        | B85M-ITX                    | [252e96684a](https://linux-hardware.org/?probe=252e96684a) | Mar 13, 2022 |
| Lenovo        | ThinkCentre M90p 5536K6M    | [353245bef3](https://linux-hardware.org/?probe=353245bef3) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f9345bd168](https://linux-hardware.org/?probe=f9345bd168) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [84e80f8c56](https://linux-hardware.org/?probe=84e80f8c56) | Mar 12, 2022 |
| Dell          | 0M863N A01                  | [b8bdf93d55](https://linux-hardware.org/?probe=b8bdf93d55) | Mar 12, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [446c4bf806](https://linux-hardware.org/?probe=446c4bf806) | Mar 12, 2022 |
| ASUSTek       | G11CD-K                     | [f3347643b0](https://linux-hardware.org/?probe=f3347643b0) | Mar 12, 2022 |
| MSI           | 970 GAMING                  | [72e05276c6](https://linux-hardware.org/?probe=72e05276c6) | Mar 12, 2022 |
| MSI           | 970 GAMING                  | [1d740c1027](https://linux-hardware.org/?probe=1d740c1027) | Mar 12, 2022 |
| HP            | 2AA6 PVT                    | [69664fa477](https://linux-hardware.org/?probe=69664fa477) | Mar 11, 2022 |
| HP            | 0AECh D                     | [2c677684a5](https://linux-hardware.org/?probe=2c677684a5) | Mar 11, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [67369297e2](https://linux-hardware.org/?probe=67369297e2) | Mar 11, 2022 |
| HP            | 1497                        | [3c01ac84d3](https://linux-hardware.org/?probe=3c01ac84d3) | Mar 11, 2022 |
| Dell          | 0F6X5P A00                  | [b58520e2a7](https://linux-hardware.org/?probe=b58520e2a7) | Mar 11, 2022 |
| ASUSTek       | P6T WS PRO                  | [4414e91602](https://linux-hardware.org/?probe=4414e91602) | Mar 11, 2022 |
| MSI           | MS-7091                     | [6ff1d651e4](https://linux-hardware.org/?probe=6ff1d651e4) | Mar 11, 2022 |
| MSI           | Z490-A PRO                  | [5e908476ac](https://linux-hardware.org/?probe=5e908476ac) | Mar 11, 2022 |
| Megaware      | MW-H61M-2H                  | [ceb5a251e7](https://linux-hardware.org/?probe=ceb5a251e7) | Mar 10, 2022 |
| ASUSTek       | PRIME Z370-P                | [7a11ca484c](https://linux-hardware.org/?probe=7a11ca484c) | Mar 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [7b7cf41624](https://linux-hardware.org/?probe=7b7cf41624) | Mar 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [418dc14fe7](https://linux-hardware.org/?probe=418dc14fe7) | Mar 10, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | [2a7edc452e](https://linux-hardware.org/?probe=2a7edc452e) | Mar 09, 2022 |
| ASRock        | N68C-S UCC                  | [28e6a0766d](https://linux-hardware.org/?probe=28e6a0766d) | Mar 09, 2022 |
| ASRock        | N68C-S UCC                  | [8e6ae6265b](https://linux-hardware.org/?probe=8e6ae6265b) | Mar 09, 2022 |
| ASUSTek       | P8B75-M LX                  | [d52d9feb9e](https://linux-hardware.org/?probe=d52d9feb9e) | Mar 09, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [4a89454909](https://linux-hardware.org/?probe=4a89454909) | Mar 09, 2022 |
| Unknown       | Unknown                     | [c9ba6eb4ae](https://linux-hardware.org/?probe=c9ba6eb4ae) | Mar 09, 2022 |
| Dell          | 0M5DCD A02                  | [01cae1bb94](https://linux-hardware.org/?probe=01cae1bb94) | Mar 09, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [5aa4d54781](https://linux-hardware.org/?probe=5aa4d54781) | Mar 09, 2022 |
| HP            | 83E9                        | [3c45f526d3](https://linux-hardware.org/?probe=3c45f526d3) | Mar 09, 2022 |
| Gigabyte      | B450 AORUS M                | [a5c7569f3c](https://linux-hardware.org/?probe=a5c7569f3c) | Mar 09, 2022 |
| MSI           | B450M GAMING PLUS           | [283c6ec3a9](https://linux-hardware.org/?probe=283c6ec3a9) | Mar 08, 2022 |
| Gigabyte      | GA-A75-UD4H                 | [7d31af4995](https://linux-hardware.org/?probe=7d31af4995) | Mar 08, 2022 |
| ASUSTek       | PRIME B360M-A               | [038e9b79ef](https://linux-hardware.org/?probe=038e9b79ef) | Mar 08, 2022 |
| MSI           | H510M-A PRO                 | [bbd0c9e387](https://linux-hardware.org/?probe=bbd0c9e387) | Mar 08, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [bd1f2169bf](https://linux-hardware.org/?probe=bd1f2169bf) | Mar 08, 2022 |
| ASUSTek       | PRIME A320M-K               | [9695618053](https://linux-hardware.org/?probe=9695618053) | Mar 08, 2022 |
| HP            | 1589                        | [eceb34c7fa](https://linux-hardware.org/?probe=eceb34c7fa) | Mar 08, 2022 |
| ASUSTek       | Z170-P                      | [fac84edcf2](https://linux-hardware.org/?probe=fac84edcf2) | Mar 08, 2022 |
| Pegatron      | NARRA5                      | [c2d96b88c5](https://linux-hardware.org/?probe=c2d96b88c5) | Mar 08, 2022 |
| Dell          | 0M5DCD A02                  | [9435c7f3b8](https://linux-hardware.org/?probe=9435c7f3b8) | Mar 08, 2022 |
| Gigabyte      | A520M DS3H                  | [1e28e34bca](https://linux-hardware.org/?probe=1e28e34bca) | Mar 08, 2022 |
| ASUSTek       | P5QPL-AM                    | [5c6c47dafa](https://linux-hardware.org/?probe=5c6c47dafa) | Mar 07, 2022 |
| Gigabyte      | Z97-HD3                     | [9bc2f4ce28](https://linux-hardware.org/?probe=9bc2f4ce28) | Mar 07, 2022 |
| HP            | 0A64h                       | [ce6a8f8d54](https://linux-hardware.org/?probe=ce6a8f8d54) | Mar 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b69a703ea3](https://linux-hardware.org/?probe=b69a703ea3) | Mar 07, 2022 |
| Intel         | DG41RQ AAE54511-205         | [36979f5dde](https://linux-hardware.org/?probe=36979f5dde) | Mar 07, 2022 |
| Gigabyte      | X48T-DQ6                    | [e669f0a460](https://linux-hardware.org/?probe=e669f0a460) | Mar 06, 2022 |
| Gigabyte      | X48T-DQ6                    | [593cb60512](https://linux-hardware.org/?probe=593cb60512) | Mar 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | [3a889dd69f](https://linux-hardware.org/?probe=3a889dd69f) | Mar 06, 2022 |
| MSI           | H61MA-E35                   | [f95f2cdf47](https://linux-hardware.org/?probe=f95f2cdf47) | Mar 06, 2022 |
| ASRock        | B550M Steel Legend          | [d20b4fcfa5](https://linux-hardware.org/?probe=d20b4fcfa5) | Mar 06, 2022 |
| ASRock        | B550M Steel Legend          | [fea067392c](https://linux-hardware.org/?probe=fea067392c) | Mar 06, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [dff6b97b90](https://linux-hardware.org/?probe=dff6b97b90) | Mar 05, 2022 |
| MSI           | P67A-GD65                   | [b79a915db5](https://linux-hardware.org/?probe=b79a915db5) | Mar 05, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [e1090a394c](https://linux-hardware.org/?probe=e1090a394c) | Mar 05, 2022 |
| Foxconn       | A74ML/A74ML-K 3.0 1.0       | [61c50ec77f](https://linux-hardware.org/?probe=61c50ec77f) | Mar 04, 2022 |
| MSI           | Z77A-GD65                   | [c25ffc39db](https://linux-hardware.org/?probe=c25ffc39db) | Mar 04, 2022 |
| MSI           | Z77A-GD65                   | [261fc7fc09](https://linux-hardware.org/?probe=261fc7fc09) | Mar 04, 2022 |
| ASUSTek       | M2N-CM DVI                  | [499346b7ab](https://linux-hardware.org/?probe=499346b7ab) | Mar 04, 2022 |
| Lenovo        | SHARKBAY NOK                | [55ba5029ac](https://linux-hardware.org/?probe=55ba5029ac) | Mar 04, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1a54683c7c](https://linux-hardware.org/?probe=1a54683c7c) | Mar 04, 2022 |
| Intel         | DH55TC AAE70932-301         | [2780250f97](https://linux-hardware.org/?probe=2780250f97) | Mar 04, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [1a5f917071](https://linux-hardware.org/?probe=1a5f917071) | Mar 04, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [61ae40f852](https://linux-hardware.org/?probe=61ae40f852) | Mar 04, 2022 |
| Dell          | 0HR330                      | [9e351420b6](https://linux-hardware.org/?probe=9e351420b6) | Mar 04, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [9ec2a1761b](https://linux-hardware.org/?probe=9ec2a1761b) | Mar 04, 2022 |
| HP            | 3031h                       | [52a519941d](https://linux-hardware.org/?probe=52a519941d) | Mar 03, 2022 |
| KLLISRE       | B75 V1.1                    | [f29cfed3d4](https://linux-hardware.org/?probe=f29cfed3d4) | Mar 03, 2022 |
| ASUSTek       | P8B75-M LX                  | [8d3f72c54f](https://linux-hardware.org/?probe=8d3f72c54f) | Mar 03, 2022 |
| Gigabyte      | G31M-S2L                    | [dd40993d97](https://linux-hardware.org/?probe=dd40993d97) | Mar 03, 2022 |
| ASRock        | N68C-GS FX                  | [bdba90c583](https://linux-hardware.org/?probe=bdba90c583) | Mar 03, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | [9e20fdfe99](https://linux-hardware.org/?probe=9e20fdfe99) | Mar 03, 2022 |
| MSI           | A68HM-E33 V2                | [0875be36f0](https://linux-hardware.org/?probe=0875be36f0) | Mar 03, 2022 |
| Dell          | 0XHGV1 A02                  | [768657efd5](https://linux-hardware.org/?probe=768657efd5) | Mar 03, 2022 |
| ASRock        | J5005-ITX                   | [39757e65f1](https://linux-hardware.org/?probe=39757e65f1) | Mar 02, 2022 |
| Biostar       | A75MG                       | [9199cd8e0f](https://linux-hardware.org/?probe=9199cd8e0f) | Mar 02, 2022 |
| ASUSTek       | P8P67 LE                    | [6cc4fbe484](https://linux-hardware.org/?probe=6cc4fbe484) | Mar 02, 2022 |
| Gigabyte      | Z77-DS3H                    | [9ab077cead](https://linux-hardware.org/?probe=9ab077cead) | Mar 02, 2022 |
| MSI           | B350 TOMAHAWK ARCTIC        | [933aecdfff](https://linux-hardware.org/?probe=933aecdfff) | Mar 02, 2022 |
| HP            | 8054                        | [272944ecda](https://linux-hardware.org/?probe=272944ecda) | Mar 02, 2022 |
| Dell          | 0HR330                      | [1585d9c792](https://linux-hardware.org/?probe=1585d9c792) | Mar 02, 2022 |
| ASUSTek       | H81M-K                      | [20d1ba1a89](https://linux-hardware.org/?probe=20d1ba1a89) | Mar 02, 2022 |
| ASUSTek       | H81M-K                      | [2789dc5384](https://linux-hardware.org/?probe=2789dc5384) | Mar 02, 2022 |
| Gigabyte      | Z590 UD AC                  | [5e75b405ea](https://linux-hardware.org/?probe=5e75b405ea) | Mar 02, 2022 |
| Gigabyte      | Z590 UD AC                  | [74601a3854](https://linux-hardware.org/?probe=74601a3854) | Mar 02, 2022 |
| Gigabyte      | 970A-DS3P                   | [b6502f1cf3](https://linux-hardware.org/?probe=b6502f1cf3) | Mar 02, 2022 |
| HP            | 2AFB                        | [d2ebb4b0b8](https://linux-hardware.org/?probe=d2ebb4b0b8) | Mar 02, 2022 |
| Gigabyte      | B460M DS3H V2               | [a6f3637be8](https://linux-hardware.org/?probe=a6f3637be8) | Mar 01, 2022 |
| Dell          | 0HR330                      | [7e4c13a9bd](https://linux-hardware.org/?probe=7e4c13a9bd) | Mar 01, 2022 |
| HP            | 0AA8h                       | [e6f96c5f67](https://linux-hardware.org/?probe=e6f96c5f67) | Feb 28, 2022 |
| ASUSTek       | P8Q67-M DO/TPM              | [ee784c0a7e](https://linux-hardware.org/?probe=ee784c0a7e) | Feb 28, 2022 |
| ASRock        | X370 Taichi                 | [9315349aa3](https://linux-hardware.org/?probe=9315349aa3) | Feb 28, 2022 |
| ASRock        | X370 Taichi                 | [4fe10bf579](https://linux-hardware.org/?probe=4fe10bf579) | Feb 28, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [8f5984b3b6](https://linux-hardware.org/?probe=8f5984b3b6) | Feb 28, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [be9f38ce55](https://linux-hardware.org/?probe=be9f38ce55) | Feb 27, 2022 |
| Dell          | 0HY9JP A02                  | [398b45ed60](https://linux-hardware.org/?probe=398b45ed60) | Feb 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [a688333ca8](https://linux-hardware.org/?probe=a688333ca8) | Feb 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [de3e77f3b2](https://linux-hardware.org/?probe=de3e77f3b2) | Feb 27, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [b1e2e1baa3](https://linux-hardware.org/?probe=b1e2e1baa3) | Feb 27, 2022 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | [82d65e49e3](https://linux-hardware.org/?probe=82d65e49e3) | Feb 27, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [e79a48e141](https://linux-hardware.org/?probe=e79a48e141) | Feb 27, 2022 |
| EVGA          | 132-CK-NF79 2               | [5fa52d2663](https://linux-hardware.org/?probe=5fa52d2663) | Feb 27, 2022 |
| Lenovo        | Bantry CRB 31900058 STD     | [74057c64c8](https://linux-hardware.org/?probe=74057c64c8) | Feb 27, 2022 |
| ASUSTek       | PRIME A320M-K               | [787d7a32b7](https://linux-hardware.org/?probe=787d7a32b7) | Feb 26, 2022 |
| ASRock        | H170M Pro4                  | [c86d644cbc](https://linux-hardware.org/?probe=c86d644cbc) | Feb 26, 2022 |
| Gigabyte      | H510M S2H                   | [1cddab051d](https://linux-hardware.org/?probe=1cddab051d) | Feb 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [72dc373199](https://linux-hardware.org/?probe=72dc373199) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [d61754bba9](https://linux-hardware.org/?probe=d61754bba9) | Feb 26, 2022 |
| Gigabyte      | H510M S2H                   | [9773c6c6bd](https://linux-hardware.org/?probe=9773c6c6bd) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX X299-XE GAMING    | [a441cb78ea](https://linux-hardware.org/?probe=a441cb78ea) | Feb 26, 2022 |
| Gateway       | FX6860                      | [ea79bb0df8](https://linux-hardware.org/?probe=ea79bb0df8) | Feb 26, 2022 |
| HP            | 3397                        | [96bb93ffa4](https://linux-hardware.org/?probe=96bb93ffa4) | Feb 25, 2022 |
| MSI           | H81M-E34                    | [af63be0001](https://linux-hardware.org/?probe=af63be0001) | Feb 25, 2022 |
| Dell          | 0FJ030                      | [7a5ba0085b](https://linux-hardware.org/?probe=7a5ba0085b) | Feb 25, 2022 |
| ASUSTek       | H81M-C/BR                   | [7e14c1aa3b](https://linux-hardware.org/?probe=7e14c1aa3b) | Feb 25, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | [866eeb024c](https://linux-hardware.org/?probe=866eeb024c) | Feb 24, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | [9e1c3db4b1](https://linux-hardware.org/?probe=9e1c3db4b1) | Feb 24, 2022 |
| Gigabyte      | B85M-HD3                    | [160a1d60b3](https://linux-hardware.org/?probe=160a1d60b3) | Feb 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5e9d5e778e](https://linux-hardware.org/?probe=5e9d5e778e) | Feb 24, 2022 |
| Dell          | 0GDG8Y A00                  | [2d0234e231](https://linux-hardware.org/?probe=2d0234e231) | Feb 24, 2022 |
| ASRock        | N68C-S UCC                  | [8bff68d779](https://linux-hardware.org/?probe=8bff68d779) | Feb 24, 2022 |
| MSI           | A320M GAMING PRO            | [9cc531a056](https://linux-hardware.org/?probe=9cc531a056) | Feb 24, 2022 |
| Lenovo        | 0B98401 PRO                 | [c332efa9f8](https://linux-hardware.org/?probe=c332efa9f8) | Feb 24, 2022 |
| Lenovo        | Bantry CRB 31900058 STD     | [73de78c7d0](https://linux-hardware.org/?probe=73de78c7d0) | Feb 24, 2022 |
| ASRock        | G31M-S                      | [1ecf0fe3af](https://linux-hardware.org/?probe=1ecf0fe3af) | Feb 24, 2022 |
| Biostar       | A75MG                       | [ec80c46070](https://linux-hardware.org/?probe=ec80c46070) | Feb 24, 2022 |
| Lenovo        | ThinkCentre M58 7637AC6     | [bb3efc6bb4](https://linux-hardware.org/?probe=bb3efc6bb4) | Feb 24, 2022 |
| ASRock        | A320M-DGS                   | [f01c5c6bb8](https://linux-hardware.org/?probe=f01c5c6bb8) | Feb 23, 2022 |
| Intel         | H55                         | [39bf688b34](https://linux-hardware.org/?probe=39bf688b34) | Feb 23, 2022 |
| ASUSTek       | M4N68T-M LE                 | [da3e382cd2](https://linux-hardware.org/?probe=da3e382cd2) | Feb 23, 2022 |
| TYAN Compu... | D1691 S26361-D1691          | [2e2ef200f8](https://linux-hardware.org/?probe=2e2ef200f8) | Feb 23, 2022 |
| TYAN Compu... | D1691 S26361-D1691          | [7d04325630](https://linux-hardware.org/?probe=7d04325630) | Feb 22, 2022 |
| MicroStar ... | MS-7248-030 A-13            | [7316e5c5cf](https://linux-hardware.org/?probe=7316e5c5cf) | Feb 22, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4a5f73ba98](https://linux-hardware.org/?probe=4a5f73ba98) | Feb 21, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [1c3e6a4af1](https://linux-hardware.org/?probe=1c3e6a4af1) | Feb 21, 2022 |
| ASUSTek       | F1A55-M LX                  | [c032200973](https://linux-hardware.org/?probe=c032200973) | Feb 21, 2022 |
| ASUSTek       | F1A55-M LX                  | [1980619c3c](https://linux-hardware.org/?probe=1980619c3c) | Feb 21, 2022 |
| MicroStar ... | MS-7248-030 A-13            | [912154e93f](https://linux-hardware.org/?probe=912154e93f) | Feb 21, 2022 |
| MicroStar ... | MS-7248-030 A-13            | [27ff75d34a](https://linux-hardware.org/?probe=27ff75d34a) | Feb 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [03aa2b6723](https://linux-hardware.org/?probe=03aa2b6723) | Feb 21, 2022 |
| Unknown       | PCWARE APMCP68              | [4a123c183a](https://linux-hardware.org/?probe=4a123c183a) | Feb 21, 2022 |
| Pegatron      | 2AB5                        | [2bb0bac8e9](https://linux-hardware.org/?probe=2bb0bac8e9) | Feb 21, 2022 |
| Gigabyte      | GA-990XA-UD3                | [d24cd3d1e1](https://linux-hardware.org/?probe=d24cd3d1e1) | Feb 21, 2022 |
| Gigabyte      | H370M DS3H-CF               | [c6baf7375d](https://linux-hardware.org/?probe=c6baf7375d) | Feb 21, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [c671dad477](https://linux-hardware.org/?probe=c671dad477) | Feb 21, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [6e37f69275](https://linux-hardware.org/?probe=6e37f69275) | Feb 21, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [5031241166](https://linux-hardware.org/?probe=5031241166) | Feb 21, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [d6b6cbe6c9](https://linux-hardware.org/?probe=d6b6cbe6c9) | Feb 21, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [5431dfb2ef](https://linux-hardware.org/?probe=5431dfb2ef) | Feb 21, 2022 |
| Gigabyte      | B360N WIFI-CF               | [6fd8316a53](https://linux-hardware.org/?probe=6fd8316a53) | Feb 20, 2022 |
| ASUSTek       | P6X58D-E                    | [c7a12417f1](https://linux-hardware.org/?probe=c7a12417f1) | Feb 20, 2022 |
| Gigabyte      | B460 HD3                    | [ceeb703cf4](https://linux-hardware.org/?probe=ceeb703cf4) | Feb 20, 2022 |
| Unknown       | Unknown                     | [de7189b0d4](https://linux-hardware.org/?probe=de7189b0d4) | Feb 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [83ea68c8d9](https://linux-hardware.org/?probe=83ea68c8d9) | Feb 20, 2022 |
| ASUSTek       | Maximus IV GENE-Z/GEN3      | [9244fdd04c](https://linux-hardware.org/?probe=9244fdd04c) | Feb 20, 2022 |
| Intel         | D2550MUD2 AAG73892-600      | [bcae2aafa6](https://linux-hardware.org/?probe=bcae2aafa6) | Feb 20, 2022 |
| ASRock        | H110M-HDV R3.0              | [6fd6345632](https://linux-hardware.org/?probe=6fd6345632) | Feb 20, 2022 |
| ASRock        | H110M-HDV R3.0              | [f9923aebcb](https://linux-hardware.org/?probe=f9923aebcb) | Feb 20, 2022 |
| Dell          | 07N90W A02                  | [caa8d90509](https://linux-hardware.org/?probe=caa8d90509) | Feb 20, 2022 |
| HP            | 2AFA                        | [afbac16eec](https://linux-hardware.org/?probe=afbac16eec) | Feb 20, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [ed1a78c5a6](https://linux-hardware.org/?probe=ed1a78c5a6) | Feb 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [803b4d504c](https://linux-hardware.org/?probe=803b4d504c) | Feb 19, 2022 |
| Dell          | 0KV3RP A00                  | [e22b54e00d](https://linux-hardware.org/?probe=e22b54e00d) | Feb 19, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [ce7bffffc0](https://linux-hardware.org/?probe=ce7bffffc0) | Feb 19, 2022 |
| MSI           | B350M MORTAR                | [c27ff0d580](https://linux-hardware.org/?probe=c27ff0d580) | Feb 19, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [e4f6077e95](https://linux-hardware.org/?probe=e4f6077e95) | Feb 19, 2022 |
| HP            | 3397                        | [05cb6a1cf3](https://linux-hardware.org/?probe=05cb6a1cf3) | Feb 19, 2022 |
| MSI           | Z77A-GD65                   | [13dcc6145e](https://linux-hardware.org/?probe=13dcc6145e) | Feb 19, 2022 |
| MSI           | 970A SLI Krait Edition      | [794369f273](https://linux-hardware.org/?probe=794369f273) | Feb 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [70de36a2bb](https://linux-hardware.org/?probe=70de36a2bb) | Feb 19, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [82da933c60](https://linux-hardware.org/?probe=82da933c60) | Feb 18, 2022 |
| Gigabyte      | H77-DS3H                    | [417a759484](https://linux-hardware.org/?probe=417a759484) | Feb 18, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | [91f7933c5b](https://linux-hardware.org/?probe=91f7933c5b) | Feb 18, 2022 |
| Biostar       | A75MG                       | [1e051ea4d2](https://linux-hardware.org/?probe=1e051ea4d2) | Feb 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [66024b31ba](https://linux-hardware.org/?probe=66024b31ba) | Feb 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e9ac28286b](https://linux-hardware.org/?probe=e9ac28286b) | Feb 18, 2022 |
| Gigabyte      | B360M H                     | [17959e46ab](https://linux-hardware.org/?probe=17959e46ab) | Feb 18, 2022 |
| ASUSTek       | H81M-E                      | [fd7702ea67](https://linux-hardware.org/?probe=fd7702ea67) | Feb 18, 2022 |
| ASUSTek       | GL10DH                      | [56e2fba743](https://linux-hardware.org/?probe=56e2fba743) | Feb 18, 2022 |
| Lenovo        | NOK                         | [3936474618](https://linux-hardware.org/?probe=3936474618) | Feb 18, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | [d2088e6244](https://linux-hardware.org/?probe=d2088e6244) | Feb 18, 2022 |
| Gigabyte      | H97M-D3H                    | [da5a6a7160](https://linux-hardware.org/?probe=da5a6a7160) | Feb 17, 2022 |
| Dell          | 0DR845                      | [1dd9b9acaa](https://linux-hardware.org/?probe=1dd9b9acaa) | Feb 17, 2022 |
| Gigabyte      | 970A-DS3P                   | [edbe3bb3bb](https://linux-hardware.org/?probe=edbe3bb3bb) | Feb 17, 2022 |
| MSI           | Z77A-GD65                   | [75bab544df](https://linux-hardware.org/?probe=75bab544df) | Feb 17, 2022 |
| Gigabyte      | H81M-HD3                    | [fe34b72551](https://linux-hardware.org/?probe=fe34b72551) | Feb 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fb47a70139](https://linux-hardware.org/?probe=fb47a70139) | Feb 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [56ca73dc6d](https://linux-hardware.org/?probe=56ca73dc6d) | Feb 17, 2022 |
| HP            | 8433 11                     | [879012c323](https://linux-hardware.org/?probe=879012c323) | Feb 17, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [3c099cd157](https://linux-hardware.org/?probe=3c099cd157) | Feb 17, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [9f7425aac2](https://linux-hardware.org/?probe=9f7425aac2) | Feb 17, 2022 |
| MSI           | Z77A-GD65                   | [b8f472be64](https://linux-hardware.org/?probe=b8f472be64) | Feb 17, 2022 |
| Lenovo        | NOK                         | [1236b9a36b](https://linux-hardware.org/?probe=1236b9a36b) | Feb 17, 2022 |
| HP            | 8876 11                     | [4d3b19e49f](https://linux-hardware.org/?probe=4d3b19e49f) | Feb 17, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5a378e922a](https://linux-hardware.org/?probe=5a378e922a) | Feb 16, 2022 |
| MSI           | H81M-E34                    | [d5d33c5ba1](https://linux-hardware.org/?probe=d5d33c5ba1) | Feb 16, 2022 |
| HP            | 1495                        | [a66b522cfb](https://linux-hardware.org/?probe=a66b522cfb) | Feb 16, 2022 |
| ASUSTek       | PRIME Z370-P II             | [2780adec26](https://linux-hardware.org/?probe=2780adec26) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3442d4ea25](https://linux-hardware.org/?probe=3442d4ea25) | Feb 15, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [3bfd2622ae](https://linux-hardware.org/?probe=3bfd2622ae) | Feb 15, 2022 |
| MSI           | 785GTM-E45                  | [b4e9b2e08e](https://linux-hardware.org/?probe=b4e9b2e08e) | Feb 15, 2022 |
| MSI           | MS-7204                     | [5f95f68df7](https://linux-hardware.org/?probe=5f95f68df7) | Feb 15, 2022 |
| MSI           | 970A-G43                    | [ee48ba78a8](https://linux-hardware.org/?probe=ee48ba78a8) | Feb 15, 2022 |
| Gigabyte      | H110M-M2-CF                 | [b36ee90ac0](https://linux-hardware.org/?probe=b36ee90ac0) | Feb 15, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [2504c5ff16](https://linux-hardware.org/?probe=2504c5ff16) | Feb 15, 2022 |
| MSI           | Z270-A PRO                  | [94fca31209](https://linux-hardware.org/?probe=94fca31209) | Feb 15, 2022 |
| MSI           | Z77A-GD65                   | [c26a245a90](https://linux-hardware.org/?probe=c26a245a90) | Feb 14, 2022 |
| ASRock        | B150M Pro4                  | [fc9675169c](https://linux-hardware.org/?probe=fc9675169c) | Feb 14, 2022 |
| MSI           | B450-A PRO MAX              | [142f983ed2](https://linux-hardware.org/?probe=142f983ed2) | Feb 14, 2022 |
| ASUSTek       | F2A55-M LK2                 | [55a7c8230f](https://linux-hardware.org/?probe=55a7c8230f) | Feb 14, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [efcb060233](https://linux-hardware.org/?probe=efcb060233) | Feb 14, 2022 |
| Gigabyte      | AB350M-D3V-CF               | [8d0cd32859](https://linux-hardware.org/?probe=8d0cd32859) | Feb 14, 2022 |
| Gigabyte      | X58A-UD7                    | [b34c0f52a5](https://linux-hardware.org/?probe=b34c0f52a5) | Feb 14, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | [ba5c642fd0](https://linux-hardware.org/?probe=ba5c642fd0) | Feb 14, 2022 |
| Gigabyte      | 970A-DS3P                   | [543b68fdad](https://linux-hardware.org/?probe=543b68fdad) | Feb 13, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [8bd0ac2f4d](https://linux-hardware.org/?probe=8bd0ac2f4d) | Feb 13, 2022 |
| HP            | 2AF7                        | [ff4f3214c5](https://linux-hardware.org/?probe=ff4f3214c5) | Feb 13, 2022 |
| MSI           | Z97 GAMING 5                | [fa15ba7f8a](https://linux-hardware.org/?probe=fa15ba7f8a) | Feb 13, 2022 |
| Gigabyte      | F2A78M-HD2                  | [e87aaff114](https://linux-hardware.org/?probe=e87aaff114) | Feb 13, 2022 |
| Gigabyte      | F2A78M-HD2                  | [990899de1e](https://linux-hardware.org/?probe=990899de1e) | Feb 13, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [a60918c82b](https://linux-hardware.org/?probe=a60918c82b) | Feb 13, 2022 |
| MSI           | B350 TOMAHAWK ARCTIC        | [b0829a9cb6](https://linux-hardware.org/?probe=b0829a9cb6) | Feb 13, 2022 |
| Foxconn       | 2ADA                        | [64f5921b5b](https://linux-hardware.org/?probe=64f5921b5b) | Feb 13, 2022 |
| Gigabyte      | X58A-UD7                    | [1e9983d9ed](https://linux-hardware.org/?probe=1e9983d9ed) | Feb 13, 2022 |
| Dell          | 0P301D A02                  | [d1d9e8d131](https://linux-hardware.org/?probe=d1d9e8d131) | Feb 13, 2022 |
| Gigabyte      | H81M-D2V                    | [1033adb0bf](https://linux-hardware.org/?probe=1033adb0bf) | Feb 12, 2022 |
| Lenovo        | ThinkCentre A58 7515M6G     | [7b86a1d792](https://linux-hardware.org/?probe=7b86a1d792) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [196bd41500](https://linux-hardware.org/?probe=196bd41500) | Feb 12, 2022 |
| Acer          | Aspire M3920                | [8f76b3f28c](https://linux-hardware.org/?probe=8f76b3f28c) | Feb 12, 2022 |
| Shuttle       | FB83V10                     | [f0037e9c4e](https://linux-hardware.org/?probe=f0037e9c4e) | Feb 12, 2022 |
| Acer          | Aspire M3920                | [9f171d548e](https://linux-hardware.org/?probe=9f171d548e) | Feb 12, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [62d94ae03d](https://linux-hardware.org/?probe=62d94ae03d) | Feb 11, 2022 |
| ASRock        | G31M-S                      | [0e52738a23](https://linux-hardware.org/?probe=0e52738a23) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [3f6c7b343f](https://linux-hardware.org/?probe=3f6c7b343f) | Feb 11, 2022 |
| Gigabyte      | H81M-D2V                    | [2146c426fa](https://linux-hardware.org/?probe=2146c426fa) | Feb 11, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [41452f28a6](https://linux-hardware.org/?probe=41452f28a6) | Feb 11, 2022 |
| ASUSTek       | PRO B460M-C                 | [40fe78bb3c](https://linux-hardware.org/?probe=40fe78bb3c) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [bee4fb458f](https://linux-hardware.org/?probe=bee4fb458f) | Feb 11, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [afc333ef80](https://linux-hardware.org/?probe=afc333ef80) | Feb 11, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [4f6d622499](https://linux-hardware.org/?probe=4f6d622499) | Feb 11, 2022 |
| Gigabyte      | 970A-DS3P                   | [60f9ecb597](https://linux-hardware.org/?probe=60f9ecb597) | Feb 11, 2022 |
| Dell          | 0XJ8C4 A00                  | [db8c939b5b](https://linux-hardware.org/?probe=db8c939b5b) | Feb 10, 2022 |
| Dell          | 0XJ8C4 A00                  | [f444c246a2](https://linux-hardware.org/?probe=f444c246a2) | Feb 10, 2022 |
| MSI           | 970 GAMING                  | [5cbfcf93fe](https://linux-hardware.org/?probe=5cbfcf93fe) | Feb 10, 2022 |
| Gigabyte      | B460M DS3H V2               | [abce368b65](https://linux-hardware.org/?probe=abce368b65) | Feb 10, 2022 |
| ASUSTek       | P5Q                         | [bc3f44c0b9](https://linux-hardware.org/?probe=bc3f44c0b9) | Feb 10, 2022 |
| Positivo      | POS-EIBTPDC                 | [5b9ae01006](https://linux-hardware.org/?probe=5b9ae01006) | Feb 10, 2022 |
| Gigabyte      | 965P-DS3                    | [1da45b4476](https://linux-hardware.org/?probe=1da45b4476) | Feb 10, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [5469af659b](https://linux-hardware.org/?probe=5469af659b) | Feb 09, 2022 |
| Fujitsu Si... | G31T-M2 V3.02               | [acfc17126b](https://linux-hardware.org/?probe=acfc17126b) | Feb 09, 2022 |
| Apple         | Mac-F221BEC8                | [9196bd025d](https://linux-hardware.org/?probe=9196bd025d) | Feb 09, 2022 |
| MSI           | B450-A PRO MAX              | [da25fcadb3](https://linux-hardware.org/?probe=da25fcadb3) | Feb 09, 2022 |
| Gigabyte      | Z68X-UD3-B3                 | [933f07a2d6](https://linux-hardware.org/?probe=933f07a2d6) | Feb 09, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [0c4ce33bab](https://linux-hardware.org/?probe=0c4ce33bab) | Feb 08, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [691b0d2c8a](https://linux-hardware.org/?probe=691b0d2c8a) | Feb 08, 2022 |
| Medion        | MS-7748                     | [51b6c04c53](https://linux-hardware.org/?probe=51b6c04c53) | Feb 08, 2022 |
| ASUSTek       | M5A97 R2.0                  | [bb826e0f4e](https://linux-hardware.org/?probe=bb826e0f4e) | Feb 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [dbfba11836](https://linux-hardware.org/?probe=dbfba11836) | Feb 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [b6df9d3243](https://linux-hardware.org/?probe=b6df9d3243) | Feb 08, 2022 |
| ASUSTek       | H110M-R                     | [4ba54a77df](https://linux-hardware.org/?probe=4ba54a77df) | Feb 07, 2022 |
| ASRock        | 980DE3/U3S3                 | [2ee314a231](https://linux-hardware.org/?probe=2ee314a231) | Feb 07, 2022 |
| Dell          | 0TP412                      | [82a52e4923](https://linux-hardware.org/?probe=82a52e4923) | Feb 07, 2022 |
| Intel         | D2550MUD2 AAG73892-600      | [487aa43e66](https://linux-hardware.org/?probe=487aa43e66) | Feb 07, 2022 |
| Intel         | D2550MUD2 AAG73892-600      | [a87409099b](https://linux-hardware.org/?probe=a87409099b) | Feb 07, 2022 |
| Dell          | 0T10XW A01                  | [fd304fc689](https://linux-hardware.org/?probe=fd304fc689) | Feb 07, 2022 |
| Acer          | Predator G3120              | [d002f5e1b6](https://linux-hardware.org/?probe=d002f5e1b6) | Feb 06, 2022 |
| ASRock        | Z77 Extreme4                | [95b7145bd2](https://linux-hardware.org/?probe=95b7145bd2) | Feb 06, 2022 |
| Lenovo        | ThinkCentre M91p 7052A9G    | [0375c86d72](https://linux-hardware.org/?probe=0375c86d72) | Feb 06, 2022 |
| Dell          | 0C2KJT A00                  | [3535228070](https://linux-hardware.org/?probe=3535228070) | Feb 06, 2022 |
| Dell          | 0C2KJT A00                  | [b5b0dbcfa9](https://linux-hardware.org/?probe=b5b0dbcfa9) | Feb 06, 2022 |
| Packard Be... | GA-T671MG                   | [6b8d22e40e](https://linux-hardware.org/?probe=6b8d22e40e) | Feb 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | [db7f189b71](https://linux-hardware.org/?probe=db7f189b71) | Feb 06, 2022 |
| MSI           | A320M-A PRO MAX             | [7a203bf128](https://linux-hardware.org/?probe=7a203bf128) | Feb 06, 2022 |
| MSI           | B450M GAMING PLUS           | [5bcf69d905](https://linux-hardware.org/?probe=5bcf69d905) | Feb 06, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [145ea1361d](https://linux-hardware.org/?probe=145ea1361d) | Feb 06, 2022 |
| Gigabyte      | P55-UD3R                    | [a3398260e2](https://linux-hardware.org/?probe=a3398260e2) | Feb 05, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | [23b715cc77](https://linux-hardware.org/?probe=23b715cc77) | Feb 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | [25d529f5d7](https://linux-hardware.org/?probe=25d529f5d7) | Feb 05, 2022 |
| ASUSTek       | P8Z68-V LX                  | [5f2710fb3a](https://linux-hardware.org/?probe=5f2710fb3a) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | [ae06eadc57](https://linux-hardware.org/?probe=ae06eadc57) | Feb 05, 2022 |
| MSI           | MS-7502 Fab D               | [c4bd8c53df](https://linux-hardware.org/?probe=c4bd8c53df) | Feb 05, 2022 |
| MSI           | MS-7502 Fab D               | [01ac407ee8](https://linux-hardware.org/?probe=01ac407ee8) | Feb 05, 2022 |
| Dell          | 0T568R A00                  | [78286bc201](https://linux-hardware.org/?probe=78286bc201) | Feb 05, 2022 |
| Lenovo        | ThinkStation S30 056834G    | [654f88d25b](https://linux-hardware.org/?probe=654f88d25b) | Feb 05, 2022 |
| ASRock        | J4105M                      | [2f9baf0de0](https://linux-hardware.org/?probe=2f9baf0de0) | Feb 05, 2022 |
| MSI           | Z97 GAMING 3                | [b4feb3ee6c](https://linux-hardware.org/?probe=b4feb3ee6c) | Feb 05, 2022 |
| Gateway       | DS71                        | [cefb514e23](https://linux-hardware.org/?probe=cefb514e23) | Feb 05, 2022 |
| HP            | 339A                        | [2a3e077d71](https://linux-hardware.org/?probe=2a3e077d71) | Feb 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [c3fe4e8a6e](https://linux-hardware.org/?probe=c3fe4e8a6e) | Feb 05, 2022 |
| Biostar       | A320MH                      | [e024e56329](https://linux-hardware.org/?probe=e024e56329) | Feb 05, 2022 |
| Biostar       | A320MH                      | [9bf3504bc1](https://linux-hardware.org/?probe=9bf3504bc1) | Feb 05, 2022 |
| Gigabyte      | X170-Extreme ECC            | [0ffb32b32d](https://linux-hardware.org/?probe=0ffb32b32d) | Feb 05, 2022 |
| Gigabyte      | B550M AORUS PRO             | [7daee98d24](https://linux-hardware.org/?probe=7daee98d24) | Feb 05, 2022 |
| ASUSTek       | PRIME A320M-K               | [802fcebea6](https://linux-hardware.org/?probe=802fcebea6) | Feb 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [d30cab784e](https://linux-hardware.org/?probe=d30cab784e) | Feb 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [7f87e3773a](https://linux-hardware.org/?probe=7f87e3773a) | Feb 04, 2022 |
| MSI           | B550-A PRO                  | [091a9c467d](https://linux-hardware.org/?probe=091a9c467d) | Feb 04, 2022 |
| Gigabyte      | H81M-S                      | [2f6399fd27](https://linux-hardware.org/?probe=2f6399fd27) | Feb 04, 2022 |
| MSI           | B550-A PRO                  | [7ff1fc83fc](https://linux-hardware.org/?probe=7ff1fc83fc) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [ed2a250420](https://linux-hardware.org/?probe=ed2a250420) | Feb 04, 2022 |
| Dell          | 0KV3RP A00                  | [79440b54e9](https://linux-hardware.org/?probe=79440b54e9) | Feb 04, 2022 |
| Gigabyte      | 970A-DS3P                   | [d598fc04e1](https://linux-hardware.org/?probe=d598fc04e1) | Feb 04, 2022 |
| MSI           | A320M-A PRO MAX             | [6f0d60dffa](https://linux-hardware.org/?probe=6f0d60dffa) | Feb 04, 2022 |
| ASUSTek       | P7P55D-E                    | [22f5b07ac0](https://linux-hardware.org/?probe=22f5b07ac0) | Feb 04, 2022 |
| MSI           | MAG B550M MORTAR            | [06714fad25](https://linux-hardware.org/?probe=06714fad25) | Feb 03, 2022 |
| MSI           | B450M GAMING PLUS           | [0012ac9a3d](https://linux-hardware.org/?probe=0012ac9a3d) | Feb 03, 2022 |
| HC            | HCAR357-MI V1.0             | [37a019edd2](https://linux-hardware.org/?probe=37a019edd2) | Feb 03, 2022 |
| ASRock        | 870 Extreme3                | [6bbf5f06c2](https://linux-hardware.org/?probe=6bbf5f06c2) | Feb 03, 2022 |
| Gigabyte      | B460M DS3H                  | [4524a07e84](https://linux-hardware.org/?probe=4524a07e84) | Feb 03, 2022 |
| MSI           | H81M-E34                    | [0c134a78ad](https://linux-hardware.org/?probe=0c134a78ad) | Feb 03, 2022 |
| ASUSTek       | H81M-PLUS                   | [dde47afaff](https://linux-hardware.org/?probe=dde47afaff) | Feb 03, 2022 |
| Biostar       | H510MH                      | [2058cb6d56](https://linux-hardware.org/?probe=2058cb6d56) | Feb 03, 2022 |
| Gigabyte      | H81M-S                      | [fcfbc53f05](https://linux-hardware.org/?probe=fcfbc53f05) | Feb 03, 2022 |
| HP            | 0AECh D                     | [0faad8b8f3](https://linux-hardware.org/?probe=0faad8b8f3) | Feb 03, 2022 |
| Gigabyte      | A520M S2H                   | [08ea66be77](https://linux-hardware.org/?probe=08ea66be77) | Feb 03, 2022 |
| MSI           | 970 GAMING                  | [afccfe35a3](https://linux-hardware.org/?probe=afccfe35a3) | Feb 03, 2022 |
| Gigabyte      | H81M-S2PV                   | [4aece000f1](https://linux-hardware.org/?probe=4aece000f1) | Feb 03, 2022 |
| ASUSTek       | Leonite2                    | [5e707ca97c](https://linux-hardware.org/?probe=5e707ca97c) | Feb 03, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | [4f8d28c7c8](https://linux-hardware.org/?probe=4f8d28c7c8) | Feb 02, 2022 |
| Gigabyte      | A520M S2H                   | [285fd7e214](https://linux-hardware.org/?probe=285fd7e214) | Feb 02, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [589137e95b](https://linux-hardware.org/?probe=589137e95b) | Feb 02, 2022 |
| ASUSTek       | P8P67                       | [91c6112da4](https://linux-hardware.org/?probe=91c6112da4) | Feb 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | [466673ab1c](https://linux-hardware.org/?probe=466673ab1c) | Feb 02, 2022 |
| Gigabyte      | B75M-D3V                    | [bf085b398d](https://linux-hardware.org/?probe=bf085b398d) | Feb 02, 2022 |
| Gigabyte      | B75M-D3V                    | [020982ee77](https://linux-hardware.org/?probe=020982ee77) | Feb 02, 2022 |
| ASRock        | A320M-HDV                   | [18c74a8966](https://linux-hardware.org/?probe=18c74a8966) | Feb 02, 2022 |
| ASRock        | Z97M Pro4                   | [a496090845](https://linux-hardware.org/?probe=a496090845) | Feb 01, 2022 |
| ASUSTek       | P5QL-CM                     | [dfcb53da8c](https://linux-hardware.org/?probe=dfcb53da8c) | Feb 01, 2022 |
| Lenovo        | NOK                         | [fbc8b16f78](https://linux-hardware.org/?probe=fbc8b16f78) | Feb 01, 2022 |
| Foxconn       | 2ABF                        | [a598d34d8b](https://linux-hardware.org/?probe=a598d34d8b) | Feb 01, 2022 |
| Dell          | 0WPMFG A00                  | [e6fb5684ba](https://linux-hardware.org/?probe=e6fb5684ba) | Feb 01, 2022 |
| MSI           | Z390-A PRO                  | [27f07635df](https://linux-hardware.org/?probe=27f07635df) | Jan 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [00314992e5](https://linux-hardware.org/?probe=00314992e5) | Jan 31, 2022 |
| ASUSTek       | P8Z77-M                     | [cb5f618a4b](https://linux-hardware.org/?probe=cb5f618a4b) | Jan 31, 2022 |
| ASUSTek       | P8Z77-M                     | [0c1b8480b6](https://linux-hardware.org/?probe=0c1b8480b6) | Jan 31, 2022 |
| Gigabyte      | H81M-D2V                    | [83d98b94dd](https://linux-hardware.org/?probe=83d98b94dd) | Jan 31, 2022 |
| ASUSTek       | Z87-A                       | [b48601a549](https://linux-hardware.org/?probe=b48601a549) | Jan 31, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [96e168beb8](https://linux-hardware.org/?probe=96e168beb8) | Jan 31, 2022 |
| ASUSTek       | Z97-A                       | [19d74bd6f0](https://linux-hardware.org/?probe=19d74bd6f0) | Jan 31, 2022 |
| ASRock        | H170M Pro4S                 | [efb4e3254e](https://linux-hardware.org/?probe=efb4e3254e) | Jan 31, 2022 |
| Dell          | 0NX183 A01                  | [54e546f9ae](https://linux-hardware.org/?probe=54e546f9ae) | Jan 31, 2022 |
| Intel         | DH61HO AAG62445-102         | [e0cbedce41](https://linux-hardware.org/?probe=e0cbedce41) | Jan 30, 2022 |
| MSI           | B450-A PRO MAX              | [08a04a280f](https://linux-hardware.org/?probe=08a04a280f) | Jan 30, 2022 |
| MSI           | Z77A-GD65                   | [582fc22a3b](https://linux-hardware.org/?probe=582fc22a3b) | Jan 30, 2022 |
| ASUSTek       | P6T WS PRO                  | [007b4193a0](https://linux-hardware.org/?probe=007b4193a0) | Jan 30, 2022 |
| Intel         | DG33SXG2 AAD94468-504       | [9bf45b492e](https://linux-hardware.org/?probe=9bf45b492e) | Jan 30, 2022 |
| ASRock        | H510M-HVS                   | [5873b06924](https://linux-hardware.org/?probe=5873b06924) | Jan 30, 2022 |
| ASUSTek       | Z87-A                       | [b62cc09b63](https://linux-hardware.org/?probe=b62cc09b63) | Jan 30, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [f54779e17e](https://linux-hardware.org/?probe=f54779e17e) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [b4e94f35cb](https://linux-hardware.org/?probe=b4e94f35cb) | Jan 30, 2022 |
| Gigabyte      | Z590 AORUS MASTER           | [b2a956b143](https://linux-hardware.org/?probe=b2a956b143) | Jan 30, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [ef6879fe39](https://linux-hardware.org/?probe=ef6879fe39) | Jan 30, 2022 |
| MSI           | B450-A PRO MAX              | [8ee3d68631](https://linux-hardware.org/?probe=8ee3d68631) | Jan 30, 2022 |
| Gigabyte      | B250M-D3H-CF                | [5b4a8e5bc4](https://linux-hardware.org/?probe=5b4a8e5bc4) | Jan 29, 2022 |
| MSI           | Z77A-GD65                   | [908fbe05d3](https://linux-hardware.org/?probe=908fbe05d3) | Jan 29, 2022 |
| Gigabyte      | F2A68HM-H                   | [b3b777135e](https://linux-hardware.org/?probe=b3b777135e) | Jan 29, 2022 |
| ASUSTek       | P8Z68-V PRO                 | [c8c3cf77c4](https://linux-hardware.org/?probe=c8c3cf77c4) | Jan 29, 2022 |
| Gigabyte      | H81M-D2V                    | [5dc80948c0](https://linux-hardware.org/?probe=5dc80948c0) | Jan 29, 2022 |
| HP            | 1494                        | [ffe42400ea](https://linux-hardware.org/?probe=ffe42400ea) | Jan 29, 2022 |
| Acer          | RS740DVF                    | [88322439c0](https://linux-hardware.org/?probe=88322439c0) | Jan 29, 2022 |
| ASUSTek       | P8H61-M LE R2.0             | [d4593f5f1c](https://linux-hardware.org/?probe=d4593f5f1c) | Jan 29, 2022 |
| MSI           | 970A SLI Krait Edition      | [73d451f169](https://linux-hardware.org/?probe=73d451f169) | Jan 29, 2022 |
| Pegatron      | 2ACB                        | [336b313aee](https://linux-hardware.org/?probe=336b313aee) | Jan 28, 2022 |
| Fujitsu Si... | G31T-M2 V3.02               | [1cff880d91](https://linux-hardware.org/?probe=1cff880d91) | Jan 28, 2022 |
| MSI           | A68HM GRENADE               | [ea2a58f958](https://linux-hardware.org/?probe=ea2a58f958) | Jan 28, 2022 |
| MSI           | H87M-E35                    | [0cfdd2b772](https://linux-hardware.org/?probe=0cfdd2b772) | Jan 28, 2022 |
| Dell          | 0HY9JP A02                  | [326c139382](https://linux-hardware.org/?probe=326c139382) | Jan 28, 2022 |
| Intel         | H61                         | [c2f4b3c4d8](https://linux-hardware.org/?probe=c2f4b3c4d8) | Jan 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | [49f803336e](https://linux-hardware.org/?probe=49f803336e) | Jan 27, 2022 |
| ASUSTek       | M2R-FVM                     | [17fd122470](https://linux-hardware.org/?probe=17fd122470) | Jan 27, 2022 |
| Acer          | Aspire X1800                | [913dd4dcac](https://linux-hardware.org/?probe=913dd4dcac) | Jan 27, 2022 |
| MSI           | H81M-E34                    | [fc61aaf589](https://linux-hardware.org/?probe=fc61aaf589) | Jan 27, 2022 |
| ASUSTek       | M2N68-AM Plus               | [6e695b85fb](https://linux-hardware.org/?probe=6e695b85fb) | Jan 27, 2022 |
| Supermicro    | X7DWE                       | [b533d23254](https://linux-hardware.org/?probe=b533d23254) | Jan 27, 2022 |
| Supermicro    | X7DWE                       | [d1d2387327](https://linux-hardware.org/?probe=d1d2387327) | Jan 27, 2022 |
| Dell          | 0NC2VH A01                  | [032133db0a](https://linux-hardware.org/?probe=032133db0a) | Jan 27, 2022 |
| Pegatron      | 2ACB                        | [379fe56c17](https://linux-hardware.org/?probe=379fe56c17) | Jan 27, 2022 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | [a0aecb00c0](https://linux-hardware.org/?probe=a0aecb00c0) | Jan 26, 2022 |
| Gigabyte      | M61VME-S2                   | [c91d9663e8](https://linux-hardware.org/?probe=c91d9663e8) | Jan 26, 2022 |
| ASUSTek       | A68HM-PLUS                  | [a8678e1dc3](https://linux-hardware.org/?probe=a8678e1dc3) | Jan 26, 2022 |
| Intel         | DG31PR AAD97573-306         | [8b3d53834f](https://linux-hardware.org/?probe=8b3d53834f) | Jan 26, 2022 |
| Intel         | DG31PR AAD97573-306         | [5e11b9b4e3](https://linux-hardware.org/?probe=5e11b9b4e3) | Jan 26, 2022 |
| Intel         | D54250WYK H13922-303        | [8b6b3d70bf](https://linux-hardware.org/?probe=8b6b3d70bf) | Jan 26, 2022 |
| ASUSTek       | M2N68-AM Plus               | [38afcc5ebd](https://linux-hardware.org/?probe=38afcc5ebd) | Jan 26, 2022 |
| Intel         | H81                         | [1f7ff2e980](https://linux-hardware.org/?probe=1f7ff2e980) | Jan 26, 2022 |
| ASRock        | H170M Pro4S                 | [0c900f67d0](https://linux-hardware.org/?probe=0c900f67d0) | Jan 26, 2022 |
| ASUSTek       | M2N68-AM Plus               | [e2a82eff7e](https://linux-hardware.org/?probe=e2a82eff7e) | Jan 26, 2022 |
| Foxconn       | 2A92                        | [affed2d377](https://linux-hardware.org/?probe=affed2d377) | Jan 26, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [03af126d6b](https://linux-hardware.org/?probe=03af126d6b) | Jan 26, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | [e897e9c2a3](https://linux-hardware.org/?probe=e897e9c2a3) | Jan 25, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [2aff79c6af](https://linux-hardware.org/?probe=2aff79c6af) | Jan 25, 2022 |
| Dell          | 07N90W A02                  | [e31441d515](https://linux-hardware.org/?probe=e31441d515) | Jan 25, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [0156a32982](https://linux-hardware.org/?probe=0156a32982) | Jan 25, 2022 |
| ASUSTek       | P7H55-USB3                  | [1f4b756d04](https://linux-hardware.org/?probe=1f4b756d04) | Jan 25, 2022 |
| Dell          | 051FJ8 A00                  | [4248fcfd47](https://linux-hardware.org/?probe=4248fcfd47) | Jan 24, 2022 |
| ASRock        | AB350M Pro4                 | [cae6b39683](https://linux-hardware.org/?probe=cae6b39683) | Jan 24, 2022 |
| ASRock        | AB350M Pro4                 | [75e0b58fa2](https://linux-hardware.org/?probe=75e0b58fa2) | Jan 24, 2022 |
| Dell          | 0WF810                      | [254dc6cb82](https://linux-hardware.org/?probe=254dc6cb82) | Jan 24, 2022 |
| Gigabyte      | B85-HD3                     | [148043b8a4](https://linux-hardware.org/?probe=148043b8a4) | Jan 23, 2022 |
| Intel         | H61                         | [a673457fc6](https://linux-hardware.org/?probe=a673457fc6) | Jan 23, 2022 |
| Intel         | H61                         | [aa29a62d0d](https://linux-hardware.org/?probe=aa29a62d0d) | Jan 23, 2022 |
| ASRock        | Z77 Extreme4                | [1d9246a4f9](https://linux-hardware.org/?probe=1d9246a4f9) | Jan 23, 2022 |
| Dell          | 0HY9JP A00                  | [57d9a51438](https://linux-hardware.org/?probe=57d9a51438) | Jan 23, 2022 |
| MSI           | Z170A GAMING M3             | [3913d07acf](https://linux-hardware.org/?probe=3913d07acf) | Jan 23, 2022 |
| ASUSTek       | PRIME Z590-A                | [4b69ead66e](https://linux-hardware.org/?probe=4b69ead66e) | Jan 23, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | [157ee8c8d9](https://linux-hardware.org/?probe=157ee8c8d9) | Jan 23, 2022 |
| ASUSTek       | A68HM-PLUS                  | [bd309bc0ae](https://linux-hardware.org/?probe=bd309bc0ae) | Jan 22, 2022 |
| ASUSTek       | A68HM-PLUS                  | [e477b84aa1](https://linux-hardware.org/?probe=e477b84aa1) | Jan 22, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [2aa2fc8ed9](https://linux-hardware.org/?probe=2aa2fc8ed9) | Jan 22, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | [fd86396422](https://linux-hardware.org/?probe=fd86396422) | Jan 22, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [9eaa5ec16f](https://linux-hardware.org/?probe=9eaa5ec16f) | Jan 22, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [dc2fed01f8](https://linux-hardware.org/?probe=dc2fed01f8) | Jan 22, 2022 |
| ASRock        | B450 Steel Legend           | [5858d7a395](https://linux-hardware.org/?probe=5858d7a395) | Jan 22, 2022 |
| ASRock        | B450 Steel Legend           | [2359e355dd](https://linux-hardware.org/?probe=2359e355dd) | Jan 22, 2022 |
| Gigabyte      | F2A68HM-H                   | [87f489f402](https://linux-hardware.org/?probe=87f489f402) | Jan 22, 2022 |
| ASRock        | H310CM-HDV                  | [39cfe3259d](https://linux-hardware.org/?probe=39cfe3259d) | Jan 22, 2022 |
| ASRock        | H310CM-HDV                  | [6f70fbb3ac](https://linux-hardware.org/?probe=6f70fbb3ac) | Jan 22, 2022 |
| ASRock        | H310CM-HDV                  | [88ec95f516](https://linux-hardware.org/?probe=88ec95f516) | Jan 22, 2022 |
| ASRock        | H310CM-HDV                  | [2bae4483c9](https://linux-hardware.org/?probe=2bae4483c9) | Jan 21, 2022 |
| MSI           | Z77A-GD65                   | [d4ebf1228f](https://linux-hardware.org/?probe=d4ebf1228f) | Jan 21, 2022 |
| Medion        | Cattle24 1M                 | [328e103a74](https://linux-hardware.org/?probe=328e103a74) | Jan 21, 2022 |
| ASRock        | Z170 Extreme4               | [1484d8fbb7](https://linux-hardware.org/?probe=1484d8fbb7) | Jan 21, 2022 |
| ASUSTek       | M2N68-AM Plus               | [42f09fd170](https://linux-hardware.org/?probe=42f09fd170) | Jan 21, 2022 |
| HP            | 2B34                        | [d9288a73fc](https://linux-hardware.org/?probe=d9288a73fc) | Jan 21, 2022 |
| Medion        | MS-7748                     | [4f7fd0ee2a](https://linux-hardware.org/?probe=4f7fd0ee2a) | Jan 21, 2022 |
| KLLISRE       | X79 V1.2                    | [84bd3ccecf](https://linux-hardware.org/?probe=84bd3ccecf) | Jan 21, 2022 |
| ECS           | H61H2-A                     | [90c26876b2](https://linux-hardware.org/?probe=90c26876b2) | Jan 21, 2022 |
| ASUSTek       | PRIME H310M-E/BR            | [56c6a8b68d](https://linux-hardware.org/?probe=56c6a8b68d) | Jan 21, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [684fb39914](https://linux-hardware.org/?probe=684fb39914) | Jan 21, 2022 |
| ASUSTek       | P8H67-M                     | [a69dd56657](https://linux-hardware.org/?probe=a69dd56657) | Jan 21, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [14d9303d1d](https://linux-hardware.org/?probe=14d9303d1d) | Jan 20, 2022 |
| Acer          | Veriton X2640G V:1.0        | [8e5707f020](https://linux-hardware.org/?probe=8e5707f020) | Jan 20, 2022 |
| MSI           | Z77A-GD65                   | [b7eb1484b1](https://linux-hardware.org/?probe=b7eb1484b1) | Jan 20, 2022 |
| MSI           | PRO Z690-A DDR4             | [b69ed1da65](https://linux-hardware.org/?probe=b69ed1da65) | Jan 20, 2022 |
| Dell          | 0D28YY A01                  | [f427224d76](https://linux-hardware.org/?probe=f427224d76) | Jan 20, 2022 |
| Gigabyte      | B460M D3H                   | [d64f06fd5a](https://linux-hardware.org/?probe=d64f06fd5a) | Jan 20, 2022 |
| Toshiba       | STI 014348                  | [91c7d3cbf1](https://linux-hardware.org/?probe=91c7d3cbf1) | Jan 20, 2022 |
| MSI           | FM2-A75MA-E35               | [309ca3f321](https://linux-hardware.org/?probe=309ca3f321) | Jan 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | [4eeedfe547](https://linux-hardware.org/?probe=4eeedfe547) | Jan 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | [838fd0c9cb](https://linux-hardware.org/?probe=838fd0c9cb) | Jan 19, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [9af982ddf0](https://linux-hardware.org/?probe=9af982ddf0) | Jan 19, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [cbc94c270d](https://linux-hardware.org/?probe=cbc94c270d) | Jan 19, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [630c1a087a](https://linux-hardware.org/?probe=630c1a087a) | Jan 19, 2022 |
| ASRock        | B85M-HDS                    | [08a10e8f68](https://linux-hardware.org/?probe=08a10e8f68) | Jan 19, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [e90aff774e](https://linux-hardware.org/?probe=e90aff774e) | Jan 19, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [62c465d499](https://linux-hardware.org/?probe=62c465d499) | Jan 19, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [bddb19b4e9](https://linux-hardware.org/?probe=bddb19b4e9) | Jan 19, 2022 |
| Dell          | 0D28YY A01                  | [42be1b5e41](https://linux-hardware.org/?probe=42be1b5e41) | Jan 19, 2022 |
| Gigabyte      | B560M H                     | [8d57aad6be](https://linux-hardware.org/?probe=8d57aad6be) | Jan 19, 2022 |
| ASUSTek       | Amberine M                  | [95ac0d05c4](https://linux-hardware.org/?probe=95ac0d05c4) | Jan 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [baa38b7dbe](https://linux-hardware.org/?probe=baa38b7dbe) | Jan 19, 2022 |
| ASRock        | B450M Steel Legend          | [11d9077e60](https://linux-hardware.org/?probe=11d9077e60) | Jan 19, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [48375f6e86](https://linux-hardware.org/?probe=48375f6e86) | Jan 19, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [bb3105de31](https://linux-hardware.org/?probe=bb3105de31) | Jan 18, 2022 |
| MSI           | FM2-A75MA-E35               | [6dc490c1c0](https://linux-hardware.org/?probe=6dc490c1c0) | Jan 18, 2022 |
| MSI           | FM2-A75MA-E35               | [0ef1094698](https://linux-hardware.org/?probe=0ef1094698) | Jan 18, 2022 |
| MSI           | H510M PRO                   | [80761af465](https://linux-hardware.org/?probe=80761af465) | Jan 18, 2022 |
| Shuttle       | FH61V                       | [6d6980d0bb](https://linux-hardware.org/?probe=6d6980d0bb) | Jan 18, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [ca37e4f3e0](https://linux-hardware.org/?probe=ca37e4f3e0) | Jan 18, 2022 |
| DFI           | LP 925X-T2                  | [7c615bd7de](https://linux-hardware.org/?probe=7c615bd7de) | Jan 18, 2022 |
| DFI           | LP 925X-T2                  | [cbc72841ed](https://linux-hardware.org/?probe=cbc72841ed) | Jan 18, 2022 |
| ASUSTek       | M5A97 PLUS                  | [7f28b8e845](https://linux-hardware.org/?probe=7f28b8e845) | Jan 18, 2022 |
| MSI           | Z77A-GD65                   | [705984b378](https://linux-hardware.org/?probe=705984b378) | Jan 17, 2022 |
| HP            | 1495                        | [f67a5913e3](https://linux-hardware.org/?probe=f67a5913e3) | Jan 17, 2022 |
| ASUSTek       | P8H67-M                     | [1568252a07](https://linux-hardware.org/?probe=1568252a07) | Jan 17, 2022 |
| ASUSTek       | B85M-G R2.0                 | [a6302c118b](https://linux-hardware.org/?probe=a6302c118b) | Jan 17, 2022 |
| ASUSTek       | B85M-G R2.0                 | [8a0c194baa](https://linux-hardware.org/?probe=8a0c194baa) | Jan 17, 2022 |
| Dell          | 0D28YY A01                  | [06df6383d3](https://linux-hardware.org/?probe=06df6383d3) | Jan 17, 2022 |
| Dell          | 0XR1GT A00                  | [1ef5ed62fe](https://linux-hardware.org/?probe=1ef5ed62fe) | Jan 17, 2022 |
| Gigabyte      | A320MA-M.2-CF               | [3dacdab227](https://linux-hardware.org/?probe=3dacdab227) | Jan 17, 2022 |
| ASUSTek       | Z87-A                       | [b6d5a58347](https://linux-hardware.org/?probe=b6d5a58347) | Jan 17, 2022 |
| ASRock        | 970 Pro3 R2.0               | [8442ae3661](https://linux-hardware.org/?probe=8442ae3661) | Jan 16, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [00dc05487b](https://linux-hardware.org/?probe=00dc05487b) | Jan 16, 2022 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [91d1d727ec](https://linux-hardware.org/?probe=91d1d727ec) | Jan 16, 2022 |
| MediaVue      | MV-890GX V1.2               | [201163da2f](https://linux-hardware.org/?probe=201163da2f) | Jan 16, 2022 |
| Dell          | 030VXY A02                  | [f733f4f3ef](https://linux-hardware.org/?probe=f733f4f3ef) | Jan 16, 2022 |
| HP            | 1497                        | [47f5df0da8](https://linux-hardware.org/?probe=47f5df0da8) | Jan 16, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [9a968f26c6](https://linux-hardware.org/?probe=9a968f26c6) | Jan 16, 2022 |
| Dell          | 0M5DCD A02                  | [46114605ad](https://linux-hardware.org/?probe=46114605ad) | Jan 16, 2022 |
| Gigabyte      | B550M DS3H                  | [446a16b532](https://linux-hardware.org/?probe=446a16b532) | Jan 15, 2022 |
| MSI           | Z77A-GD65                   | [d6c5cd3656](https://linux-hardware.org/?probe=d6c5cd3656) | Jan 15, 2022 |
| Dell          | 0D6H9T A00                  | [cd0c65171a](https://linux-hardware.org/?probe=cd0c65171a) | Jan 15, 2022 |
| Dell          | 0D6H9T A00                  | [77239f8808](https://linux-hardware.org/?probe=77239f8808) | Jan 15, 2022 |
| ASRock        | FM2A88X Pro3+               | [3b7ba9382f](https://linux-hardware.org/?probe=3b7ba9382f) | Jan 15, 2022 |
| Pegatron      | EVE                         | [d21708f0ed](https://linux-hardware.org/?probe=d21708f0ed) | Jan 14, 2022 |
| Intel         | DG45ID AAE46743-302         | [ab40e8dd7d](https://linux-hardware.org/?probe=ab40e8dd7d) | Jan 14, 2022 |
| ASUSTek       | NARRA3                      | [a220440e03](https://linux-hardware.org/?probe=a220440e03) | Jan 14, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [ae9f25c32f](https://linux-hardware.org/?probe=ae9f25c32f) | Jan 14, 2022 |
| HP            | 1998                        | [4095cee079](https://linux-hardware.org/?probe=4095cee079) | Jan 14, 2022 |
| MSI           | B450-A PRO MAX              | [8b83c9806c](https://linux-hardware.org/?probe=8b83c9806c) | Jan 13, 2022 |
| MSI           | Z77A-GD65                   | [6b97a34c09](https://linux-hardware.org/?probe=6b97a34c09) | Jan 13, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [92f528e80b](https://linux-hardware.org/?probe=92f528e80b) | Jan 13, 2022 |
| Gigabyte      | H55M-USB3                   | [88396d099b](https://linux-hardware.org/?probe=88396d099b) | Jan 13, 2022 |
| Apple         | Mac-F221BEC8                | [70fcd71bb8](https://linux-hardware.org/?probe=70fcd71bb8) | Jan 13, 2022 |
| MSI           | B550-A PRO                  | [f07e46deec](https://linux-hardware.org/?probe=f07e46deec) | Jan 13, 2022 |
| Packard Be... | IMEDIA S1360                | [93a8fdf43c](https://linux-hardware.org/?probe=93a8fdf43c) | Jan 13, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [766bd5092b](https://linux-hardware.org/?probe=766bd5092b) | Jan 13, 2022 |
| ECS           | H61H2-A                     | [518e31fcb0](https://linux-hardware.org/?probe=518e31fcb0) | Jan 13, 2022 |
| Gigabyte      | GA-970A-UD3                 | [bb65153cf2](https://linux-hardware.org/?probe=bb65153cf2) | Jan 12, 2022 |
| AURES         | W-TOUCH                     | [adc4279e12](https://linux-hardware.org/?probe=adc4279e12) | Jan 12, 2022 |
| HP            | 1998                        | [2ab7c2ca99](https://linux-hardware.org/?probe=2ab7c2ca99) | Jan 12, 2022 |
| MSI           | GF615M-P33                  | [b214018b58](https://linux-hardware.org/?probe=b214018b58) | Jan 12, 2022 |
| Positivo      | POS-MIG31AG                 | [bd893c6368](https://linux-hardware.org/?probe=bd893c6368) | Jan 12, 2022 |
| Dell          | 0D28YY A01                  | [7829cca434](https://linux-hardware.org/?probe=7829cca434) | Jan 12, 2022 |
| MSI           | A320M-A PRO MAX             | [8428db012e](https://linux-hardware.org/?probe=8428db012e) | Jan 12, 2022 |
| Dell          | 0D28YY A01                  | [34b3a0e6e7](https://linux-hardware.org/?probe=34b3a0e6e7) | Jan 12, 2022 |
| ASUSTek       | P8Z77-M                     | [3ab1711306](https://linux-hardware.org/?probe=3ab1711306) | Jan 12, 2022 |
| Pegatron      | Maureen                     | [14450aab2c](https://linux-hardware.org/?probe=14450aab2c) | Jan 12, 2022 |
| ASRock        | A320M-HDV R4.0              | [88ef58f2e7](https://linux-hardware.org/?probe=88ef58f2e7) | Jan 11, 2022 |
| Positivo      | POS-PIH81DI                 | [0bbfacaaea](https://linux-hardware.org/?probe=0bbfacaaea) | Jan 11, 2022 |
| HP            | 2B34                        | [30e5ae1791](https://linux-hardware.org/?probe=30e5ae1791) | Jan 11, 2022 |
| ASRock        | G41M-VS3                    | [8709398c0f](https://linux-hardware.org/?probe=8709398c0f) | Jan 11, 2022 |
| ASRock        | G41M-VS3                    | [9915e534b9](https://linux-hardware.org/?probe=9915e534b9) | Jan 11, 2022 |
| Gigabyte      | GA-880GM-D2H                | [140f1ced79](https://linux-hardware.org/?probe=140f1ced79) | Jan 11, 2022 |
| Gigabyte      | GA-880GM-D2H                | [f63fbfe3b2](https://linux-hardware.org/?probe=f63fbfe3b2) | Jan 11, 2022 |
| ASRock        | P67 Pro3                    | [12708e4124](https://linux-hardware.org/?probe=12708e4124) | Jan 11, 2022 |
| ECS           | H61H2-M2                    | [21704ab656](https://linux-hardware.org/?probe=21704ab656) | Jan 10, 2022 |
| MSI           | 2AE0                        | [ae5c421eef](https://linux-hardware.org/?probe=ae5c421eef) | Jan 10, 2022 |
| ASUSTek       | Z97-P                       | [9683b70727](https://linux-hardware.org/?probe=9683b70727) | Jan 10, 2022 |
| Dell          | 0XR1GT A00                  | [1c534662b8](https://linux-hardware.org/?probe=1c534662b8) | Jan 10, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | [1da9aea182](https://linux-hardware.org/?probe=1da9aea182) | Jan 10, 2022 |
| ASRock        | H81M-DG4                    | [8e9dcd2eae](https://linux-hardware.org/?probe=8e9dcd2eae) | Jan 10, 2022 |
| ASUSTek       | PRIME B450M-A II            | [6e76d9068e](https://linux-hardware.org/?probe=6e76d9068e) | Jan 10, 2022 |
| ASUSTek       | PRIME B450M-A II            | [9224684769](https://linux-hardware.org/?probe=9224684769) | Jan 10, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [70ba3d0f9d](https://linux-hardware.org/?probe=70ba3d0f9d) | Jan 10, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [e4b074e70c](https://linux-hardware.org/?probe=e4b074e70c) | Jan 10, 2022 |
| HP            | 18E7                        | [0a1687e6fa](https://linux-hardware.org/?probe=0a1687e6fa) | Jan 09, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [cba57c7cfe](https://linux-hardware.org/?probe=cba57c7cfe) | Jan 09, 2022 |
| HP            | 0B54h D                     | [ac4cda5f96](https://linux-hardware.org/?probe=ac4cda5f96) | Jan 09, 2022 |
| Dell          | 02YYK5 A00                  | [bda3d22eee](https://linux-hardware.org/?probe=bda3d22eee) | Jan 09, 2022 |
| Gigabyte      | H110M-D2P-WG-CF             | [74c908ffe6](https://linux-hardware.org/?probe=74c908ffe6) | Jan 09, 2022 |
| KLLISRE       | X79 V1.2                    | [239547a419](https://linux-hardware.org/?probe=239547a419) | Jan 09, 2022 |
| Dell          | 0D6H9T A01                  | [8bc2b6cc7c](https://linux-hardware.org/?probe=8bc2b6cc7c) | Jan 09, 2022 |
| HP            | 0B54h D                     | [753fc0ec27](https://linux-hardware.org/?probe=753fc0ec27) | Jan 09, 2022 |
| Dell          | 0WR7PY A03                  | [dc2e38d1ed](https://linux-hardware.org/?probe=dc2e38d1ed) | Jan 09, 2022 |
| Gigabyte      | B550M DS3H                  | [8e5e7a9260](https://linux-hardware.org/?probe=8e5e7a9260) | Jan 09, 2022 |
| ASRock        | AB350 Pro4                  | [881da9fb53](https://linux-hardware.org/?probe=881da9fb53) | Jan 09, 2022 |
| ASUSTek       | P5B-VM SE                   | [70d1a7ddc8](https://linux-hardware.org/?probe=70d1a7ddc8) | Jan 09, 2022 |
| Fujitsu Si... | D2156-A1 S26361-D2156-A1    | [dcc677848e](https://linux-hardware.org/?probe=dcc677848e) | Jan 09, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b4f5f6f8da](https://linux-hardware.org/?probe=b4f5f6f8da) | Jan 08, 2022 |
| ASUSTek       | M5A97 R2.0                  | [f48dc8b412](https://linux-hardware.org/?probe=f48dc8b412) | Jan 08, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [0f8c9310ee](https://linux-hardware.org/?probe=0f8c9310ee) | Jan 08, 2022 |
| ASUSTek       | P5B-VM SE                   | [6a043eb515](https://linux-hardware.org/?probe=6a043eb515) | Jan 08, 2022 |
| Acer          | F672CR R01-A4               | [a2fa0bacec](https://linux-hardware.org/?probe=a2fa0bacec) | Jan 08, 2022 |
| Acer          | F672CR R01-A4               | [6c449b4b3c](https://linux-hardware.org/?probe=6c449b4b3c) | Jan 08, 2022 |
| ASUSTek       | P5K Deluxe                  | [4d2a0c8d41](https://linux-hardware.org/?probe=4d2a0c8d41) | Jan 08, 2022 |
| Gigabyte      | H55M-USB3                   | [aad9837ee4](https://linux-hardware.org/?probe=aad9837ee4) | Jan 08, 2022 |
| HP            | 3398                        | [b36bba1dac](https://linux-hardware.org/?probe=b36bba1dac) | Jan 08, 2022 |
| HP            | 3646h                       | [85edd0c1bf](https://linux-hardware.org/?probe=85edd0c1bf) | Jan 08, 2022 |
| HP            | 3646h                       | [616a0acd31](https://linux-hardware.org/?probe=616a0acd31) | Jan 08, 2022 |
| Dell          | 0WR7PY A01                  | [31dca40457](https://linux-hardware.org/?probe=31dca40457) | Jan 08, 2022 |
| HP            | 3398                        | [9f6575f374](https://linux-hardware.org/?probe=9f6575f374) | Jan 08, 2022 |
| ASRock        | Z270 Professional Gaming... | [30fc217d75](https://linux-hardware.org/?probe=30fc217d75) | Jan 08, 2022 |
| Gigabyte      | Z68X-UD3-B3                 | [46932917d4](https://linux-hardware.org/?probe=46932917d4) | Jan 08, 2022 |
| HP            | 3048h                       | [8580cdd56f](https://linux-hardware.org/?probe=8580cdd56f) | Jan 08, 2022 |
| HP            | 8643 SMVB                   | [0ab2fce296](https://linux-hardware.org/?probe=0ab2fce296) | Jan 08, 2022 |
| Gigabyte      | 990FXA-UD3                  | [38fcad709c](https://linux-hardware.org/?probe=38fcad709c) | Jan 07, 2022 |
| Intel         | H61                         | [aceeadad0e](https://linux-hardware.org/?probe=aceeadad0e) | Jan 07, 2022 |
| MSI           | H110M ECO                   | [c056a2eafa](https://linux-hardware.org/?probe=c056a2eafa) | Jan 07, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | [6f8a6d74e4](https://linux-hardware.org/?probe=6f8a6d74e4) | Jan 07, 2022 |
| Gigabyte      | B460M DS3H V2               | [1667660cbf](https://linux-hardware.org/?probe=1667660cbf) | Jan 07, 2022 |
| ASRock        | H61iCafe                    | [a3b1d70f6a](https://linux-hardware.org/?probe=a3b1d70f6a) | Jan 07, 2022 |
| ASUSTek       | P5G41T-M LE                 | [711a037e72](https://linux-hardware.org/?probe=711a037e72) | Jan 07, 2022 |
| ASRock        | H61iCafe                    | [c13275f37b](https://linux-hardware.org/?probe=c13275f37b) | Jan 07, 2022 |
| HP            | 2AA6 PVT                    | [ebf581be9f](https://linux-hardware.org/?probe=ebf581be9f) | Jan 07, 2022 |
| HP            | 18E7                        | [b9844ec9ca](https://linux-hardware.org/?probe=b9844ec9ca) | Jan 06, 2022 |
| Unknown       | NF-MCP78                    | [b1cca5c515](https://linux-hardware.org/?probe=b1cca5c515) | Jan 06, 2022 |
| Biostar       | TB250-BTC+                  | [ef57a01461](https://linux-hardware.org/?probe=ef57a01461) | Jan 06, 2022 |
| BESSTAR Te... | HM50                        | [1ca6712001](https://linux-hardware.org/?probe=1ca6712001) | Jan 06, 2022 |
| Gigabyte      | H81M-S                      | [8d1726befc](https://linux-hardware.org/?probe=8d1726befc) | Jan 06, 2022 |
| Gigabyte      | H81M-S                      | [2b09721dea](https://linux-hardware.org/?probe=2b09721dea) | Jan 06, 2022 |
| Gigabyte      | Z390 GAMING SLI-CF          | [affb3b3f70](https://linux-hardware.org/?probe=affb3b3f70) | Jan 06, 2022 |
| ASRock        | P67 Pro3                    | [db27d8ec7a](https://linux-hardware.org/?probe=db27d8ec7a) | Jan 06, 2022 |
| ECS           | H61H2-A                     | [47fb5347c0](https://linux-hardware.org/?probe=47fb5347c0) | Jan 06, 2022 |
| ECS           | H61H2-A                     | [fa589d8ed4](https://linux-hardware.org/?probe=fa589d8ed4) | Jan 06, 2022 |
| ASRock        | A320M-HD                    | [610072e219](https://linux-hardware.org/?probe=610072e219) | Jan 06, 2022 |
| Positivo      | POS-PQ45AU                  | [9293dfdb4d](https://linux-hardware.org/?probe=9293dfdb4d) | Jan 06, 2022 |
| ASRock        | N68-S3 UCC                  | [13caf15327](https://linux-hardware.org/?probe=13caf15327) | Jan 05, 2022 |
| Acer          | Aspire TC-605               | [14c214290f](https://linux-hardware.org/?probe=14c214290f) | Jan 05, 2022 |
| Gigabyte      | H67MA-USB3-B3               | [aae3c5234f](https://linux-hardware.org/?probe=aae3c5234f) | Jan 05, 2022 |
| Gigabyte      | M57SLI-S4                   | [ec63d82626](https://linux-hardware.org/?probe=ec63d82626) | Jan 05, 2022 |
| AMD           | A88K                        | [9c664dd81f](https://linux-hardware.org/?probe=9c664dd81f) | Jan 05, 2022 |
| ASRock        | N68-S3 UCC                  | [7d66181ba1](https://linux-hardware.org/?probe=7d66181ba1) | Jan 05, 2022 |
| Medion        | MS-7728                     | [c450aeb1bf](https://linux-hardware.org/?probe=c450aeb1bf) | Jan 05, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | [09727504a3](https://linux-hardware.org/?probe=09727504a3) | Jan 05, 2022 |
| ASUSTek       | H110M-R                     | [8b6fab3f89](https://linux-hardware.org/?probe=8b6fab3f89) | Jan 05, 2022 |
| Medion        | Cattle24 1M                 | [9980b9fb17](https://linux-hardware.org/?probe=9980b9fb17) | Jan 04, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c778e8e570](https://linux-hardware.org/?probe=c778e8e570) | Jan 04, 2022 |
| ASUSTek       | PRIME Z370-A                | [9150e92f84](https://linux-hardware.org/?probe=9150e92f84) | Jan 04, 2022 |
| Dell          | 0HHV7N A00                  | [6f7dc1c21a](https://linux-hardware.org/?probe=6f7dc1c21a) | Jan 04, 2022 |
| Gigabyte      | H57M-USB3                   | [71d90e1797](https://linux-hardware.org/?probe=71d90e1797) | Jan 04, 2022 |
| ASRock        | B85 Pro4                    | [e568726216](https://linux-hardware.org/?probe=e568726216) | Jan 04, 2022 |
| Intel         | H55                         | [aa361d5399](https://linux-hardware.org/?probe=aa361d5399) | Jan 03, 2022 |
| Alienware     | 0C92D0 A00                  | [baa822af3d](https://linux-hardware.org/?probe=baa822af3d) | Jan 03, 2022 |
| Gateway       | FX6860                      | [5c580708d7](https://linux-hardware.org/?probe=5c580708d7) | Jan 03, 2022 |
| Gateway       | FX6860                      | [e121883b10](https://linux-hardware.org/?probe=e121883b10) | Jan 03, 2022 |
| Biostar       | H81MHV3                     | [897c4f4fa5](https://linux-hardware.org/?probe=897c4f4fa5) | Jan 03, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [df695a7747](https://linux-hardware.org/?probe=df695a7747) | Jan 03, 2022 |
| ASUSTek       | Z97-P                       | [f159c9804a](https://linux-hardware.org/?probe=f159c9804a) | Jan 03, 2022 |
| MSI           | H110M PRO-VH PLUS           | [35c962a07f](https://linux-hardware.org/?probe=35c962a07f) | Jan 02, 2022 |
| ASUSTek       | PRIME A320M-K               | [9d1d46c08a](https://linux-hardware.org/?probe=9d1d46c08a) | Jan 02, 2022 |
| MSI           | B450M-A PRO MAX             | [e6a4a21d5c](https://linux-hardware.org/?probe=e6a4a21d5c) | Jan 02, 2022 |
| Acer          | RS880M05                    | [6d398453c9](https://linux-hardware.org/?probe=6d398453c9) | Jan 02, 2022 |
| ECS           | H61H2-A                     | [ff162b6454](https://linux-hardware.org/?probe=ff162b6454) | Jan 02, 2022 |
| Intel         | DQ45CB AAE30148-207         | [2b3e1be22b](https://linux-hardware.org/?probe=2b3e1be22b) | Jan 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [afab84fd36](https://linux-hardware.org/?probe=afab84fd36) | Jan 02, 2022 |
| Acer          | FMCP7AM                     | [cd1463cb99](https://linux-hardware.org/?probe=cd1463cb99) | Jan 02, 2022 |
| Dell          | 0M863N A01                  | [0afe993c93](https://linux-hardware.org/?probe=0afe993c93) | Jan 02, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [190d8738ba](https://linux-hardware.org/?probe=190d8738ba) | Jan 02, 2022 |
| ASRock        | H61iCafe                    | [5b2ee0f6e0](https://linux-hardware.org/?probe=5b2ee0f6e0) | Jan 02, 2022 |
| Gigabyte      | H57M-USB3                   | [60b9497731](https://linux-hardware.org/?probe=60b9497731) | Jan 01, 2022 |
| Gigabyte      | F2A68HM-H                   | [31a612967f](https://linux-hardware.org/?probe=31a612967f) | Jan 01, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [ab62777cb6](https://linux-hardware.org/?probe=ab62777cb6) | Jan 01, 2022 |
| ASRock        | H61iCafe                    | [edd51e57c1](https://linux-hardware.org/?probe=edd51e57c1) | Jan 01, 2022 |
| MSI           | 760GM-P23                   | [96ce7a909b](https://linux-hardware.org/?probe=96ce7a909b) | Jan 01, 2022 |
| Gigabyte      | F2A68HM-H                   | [39aefeb6fc](https://linux-hardware.org/?probe=39aefeb6fc) | Dec 31, 2021 |
| Gigabyte      | F2A68HM-H                   | [2371b7d590](https://linux-hardware.org/?probe=2371b7d590) | Dec 31, 2021 |
| MSI           | MEG Z490 UNIFY              | [5a14bee075](https://linux-hardware.org/?probe=5a14bee075) | Dec 31, 2021 |
| Biostar       | Hi-Fi H61S3                 | [6d68cbf5a2](https://linux-hardware.org/?probe=6d68cbf5a2) | Dec 31, 2021 |
| Gigabyte      | H97N-WIFI                   | [3350bd017d](https://linux-hardware.org/?probe=3350bd017d) | Dec 31, 2021 |
| Intel         | H61                         | [9743103ac6](https://linux-hardware.org/?probe=9743103ac6) | Dec 31, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [d7b37cd814](https://linux-hardware.org/?probe=d7b37cd814) | Dec 31, 2021 |
| ASRock        | X570 Pro4                   | [0396ef9c72](https://linux-hardware.org/?probe=0396ef9c72) | Dec 30, 2021 |
| Dell          | 0CU409                      | [088b0eb64c](https://linux-hardware.org/?probe=088b0eb64c) | Dec 30, 2021 |
| Dell          | 0CU409                      | [1e98ede2a2](https://linux-hardware.org/?probe=1e98ede2a2) | Dec 30, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [4161b37157](https://linux-hardware.org/?probe=4161b37157) | Dec 30, 2021 |
| Dell          | 051FJ8 A02                  | [8cc53ce548](https://linux-hardware.org/?probe=8cc53ce548) | Dec 30, 2021 |
| Gigabyte      | Z690 UD AX DDR4             | [9158036ed3](https://linux-hardware.org/?probe=9158036ed3) | Dec 30, 2021 |
| Dell          | 0J3C2F A01                  | [9a738c2a3c](https://linux-hardware.org/?probe=9a738c2a3c) | Dec 30, 2021 |
| ASUSTek       | P7H55-USB3                  | [da1ccbe603](https://linux-hardware.org/?probe=da1ccbe603) | Dec 29, 2021 |
| Pegatron      | IPMIP-GS                    | [0fe3445de4](https://linux-hardware.org/?probe=0fe3445de4) | Dec 29, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [03802bfda7](https://linux-hardware.org/?probe=03802bfda7) | Dec 29, 2021 |
| ASRock        | H170M Pro4S                 | [a84965705f](https://linux-hardware.org/?probe=a84965705f) | Dec 29, 2021 |
| Dell          | 0G919G A00                  | [afdc58ebbb](https://linux-hardware.org/?probe=afdc58ebbb) | Dec 29, 2021 |
| ASRock        | H170M Pro4S                 | [aba35e9f28](https://linux-hardware.org/?probe=aba35e9f28) | Dec 29, 2021 |
| ASUSTek       | H170M-PLUS                  | [997c8caab6](https://linux-hardware.org/?probe=997c8caab6) | Dec 29, 2021 |
| HP            | 2AF7                        | [646ae9f001](https://linux-hardware.org/?probe=646ae9f001) | Dec 29, 2021 |
| ECS           | H61H2-M2                    | [6f3d8856df](https://linux-hardware.org/?probe=6f3d8856df) | Dec 29, 2021 |
| Gigabyte      | GA-880GMA-UD2H              | [ca7b20563b](https://linux-hardware.org/?probe=ca7b20563b) | Dec 28, 2021 |
| Gigabyte      | H55M-USB3                   | [6ae95f862e](https://linux-hardware.org/?probe=6ae95f862e) | Dec 28, 2021 |
| ASRock        | AB350M Pro4                 | [4b2031d0f5](https://linux-hardware.org/?probe=4b2031d0f5) | Dec 28, 2021 |
| Pegatron      | Benicia                     | [2edd5769d6](https://linux-hardware.org/?probe=2edd5769d6) | Dec 28, 2021 |
| Apple         | Mac-F221BEC8                | [4cce063737](https://linux-hardware.org/?probe=4cce063737) | Dec 28, 2021 |
| Gigabyte      | M61VME-S2                   | [c8f8be20da](https://linux-hardware.org/?probe=c8f8be20da) | Dec 28, 2021 |
| ASUSTek       | Z170-A                      | [41738d6e6a](https://linux-hardware.org/?probe=41738d6e6a) | Dec 28, 2021 |
| ASUSTek       | TUF GAMING B550M-E WIFI     | [40a793e129](https://linux-hardware.org/?probe=40a793e129) | Dec 27, 2021 |
| Gigabyte      | B460M DS3H V2               | [7b222b01c6](https://linux-hardware.org/?probe=7b222b01c6) | Dec 27, 2021 |
| HP            | 21EF                        | [952572f778](https://linux-hardware.org/?probe=952572f778) | Dec 27, 2021 |
| HP            | 21EF                        | [1dd061783f](https://linux-hardware.org/?probe=1dd061783f) | Dec 27, 2021 |
| MSI           | Z390-A PRO                  | [b8d518ea38](https://linux-hardware.org/?probe=b8d518ea38) | Dec 27, 2021 |
| ASRock        | M3A770DE                    | [92b50bf0b6](https://linux-hardware.org/?probe=92b50bf0b6) | Dec 27, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [32842c33b7](https://linux-hardware.org/?probe=32842c33b7) | Dec 27, 2021 |
| MSI           | MEG X570 ACE                | [a36352a738](https://linux-hardware.org/?probe=a36352a738) | Dec 27, 2021 |
| ASUSTek       | M3N78-EMH HDMI              | [9c23b50b11](https://linux-hardware.org/?probe=9c23b50b11) | Dec 26, 2021 |
| Dell          | 0XR1GT A00                  | [23524d928e](https://linux-hardware.org/?probe=23524d928e) | Dec 26, 2021 |
| HPE           | ProLiant ML30 Gen10         | [44203f3cd5](https://linux-hardware.org/?probe=44203f3cd5) | Dec 26, 2021 |
| ASUSTek       | PRIME Z270-A                | [9f25d765b2](https://linux-hardware.org/?probe=9f25d765b2) | Dec 26, 2021 |
| ASRock        | M3A770DE                    | [47fa1e385d](https://linux-hardware.org/?probe=47fa1e385d) | Dec 26, 2021 |
| ASRock        | B75M R2.0                   | [8e4a08a77a](https://linux-hardware.org/?probe=8e4a08a77a) | Dec 26, 2021 |
| Intel         | DG965WH AAD41692-304        | [e53228af1f](https://linux-hardware.org/?probe=e53228af1f) | Dec 25, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ea9ed3625a](https://linux-hardware.org/?probe=ea9ed3625a) | Dec 25, 2021 |
| Lenovo        | ThinkCentre M57e 9439WHV    | [a9b2163945](https://linux-hardware.org/?probe=a9b2163945) | Dec 25, 2021 |
| MSI           | H97M-G43                    | [9befbf0087](https://linux-hardware.org/?probe=9befbf0087) | Dec 25, 2021 |
| ASRock        | Z97 Pro4                    | [11450cbfa0](https://linux-hardware.org/?probe=11450cbfa0) | Dec 25, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [7adc0ed4ef](https://linux-hardware.org/?probe=7adc0ed4ef) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [ee1cb83947](https://linux-hardware.org/?probe=ee1cb83947) | Dec 24, 2021 |
| HP            | 198E                        | [5f951aac2a](https://linux-hardware.org/?probe=5f951aac2a) | Dec 24, 2021 |
| ECS           | H61H2-M6                    | [da70905a9d](https://linux-hardware.org/?probe=da70905a9d) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [5b9e6ac08e](https://linux-hardware.org/?probe=5b9e6ac08e) | Dec 24, 2021 |
| Dell          | 0WF810                      | [77db7ecb38](https://linux-hardware.org/?probe=77db7ecb38) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [180954acf2](https://linux-hardware.org/?probe=180954acf2) | Dec 23, 2021 |
| Gigabyte      | GA-870A-UD3                 | [0d9b8b9c3b](https://linux-hardware.org/?probe=0d9b8b9c3b) | Dec 23, 2021 |
| Huanan        | X79 249PC V2.2              | [2ed1172293](https://linux-hardware.org/?probe=2ed1172293) | Dec 23, 2021 |
| ASRock        | 870 Extreme3                | [d202f241ee](https://linux-hardware.org/?probe=d202f241ee) | Dec 23, 2021 |
| ASUSTek       | P8Z77-V LX                  | [7444ed296c](https://linux-hardware.org/?probe=7444ed296c) | Dec 23, 2021 |
| ASRock        | 970 Pro3 R2.0               | [4658d07ba2](https://linux-hardware.org/?probe=4658d07ba2) | Dec 23, 2021 |
| Apple         | Mac-F221BEC8                | [737ca0661c](https://linux-hardware.org/?probe=737ca0661c) | Dec 23, 2021 |
| Dell          | 0T10XW A01                  | [863fb7b65d](https://linux-hardware.org/?probe=863fb7b65d) | Dec 23, 2021 |
| ASUSTek       | Z170-K                      | [1535d91deb](https://linux-hardware.org/?probe=1535d91deb) | Dec 23, 2021 |
| Dell          | 0J3C2F A00                  | [17a48a66b9](https://linux-hardware.org/?probe=17a48a66b9) | Dec 22, 2021 |
| Gigabyte      | GA-870A-UD3                 | [cb63a0c016](https://linux-hardware.org/?probe=cb63a0c016) | Dec 22, 2021 |
| ASRock        | B450M Steel Legend          | [b8ff289917](https://linux-hardware.org/?probe=b8ff289917) | Dec 22, 2021 |
| ASRock        | 970A-G                      | [2fe7ad63d1](https://linux-hardware.org/?probe=2fe7ad63d1) | Dec 22, 2021 |
| ASUSTek       | H170M-PLUS                  | [ba76788a15](https://linux-hardware.org/?probe=ba76788a15) | Dec 22, 2021 |
| Acer          | Aspire TC-780               | [5dc2b71ca6](https://linux-hardware.org/?probe=5dc2b71ca6) | Dec 21, 2021 |
| Acer          | Aspire TC-780               | [9f8df596ea](https://linux-hardware.org/?probe=9f8df596ea) | Dec 21, 2021 |
| Unknown       | NF-MCP78                    | [9c5e9cb548](https://linux-hardware.org/?probe=9c5e9cb548) | Dec 21, 2021 |
| HP            | 2820h                       | [3e0046043f](https://linux-hardware.org/?probe=3e0046043f) | Dec 21, 2021 |
| Lenovo        | 31900058 STD                | [0d85603510](https://linux-hardware.org/?probe=0d85603510) | Dec 21, 2021 |
| ASRock        | APL-NUC/J3455               | [5b97bc8891](https://linux-hardware.org/?probe=5b97bc8891) | Dec 21, 2021 |
| HP            | 18E7                        | [7e72b63f96](https://linux-hardware.org/?probe=7e72b63f96) | Dec 21, 2021 |
| ASRock        | B365M Pro4                  | [96a31c2b3c](https://linux-hardware.org/?probe=96a31c2b3c) | Dec 21, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [9813973b1b](https://linux-hardware.org/?probe=9813973b1b) | Dec 20, 2021 |
| Gigabyte      | B450M DS3H-CF               | [296af779e4](https://linux-hardware.org/?probe=296af779e4) | Dec 20, 2021 |
| Lenovo        | ThinkCentre M58p 7479AA3    | [a9a33efb46](https://linux-hardware.org/?probe=a9a33efb46) | Dec 20, 2021 |
| MSI           | X470 GAMING PRO             | [21ba13efd9](https://linux-hardware.org/?probe=21ba13efd9) | Dec 20, 2021 |
| ASRock        | H170M Pro4S                 | [bcd4acf346](https://linux-hardware.org/?probe=bcd4acf346) | Dec 20, 2021 |
| Gigabyte      | 990FXA-UD3                  | [ae37650ddb](https://linux-hardware.org/?probe=ae37650ddb) | Dec 20, 2021 |
| MSI           | MEG Z390 GODLIKE            | [96ba2cef20](https://linux-hardware.org/?probe=96ba2cef20) | Dec 20, 2021 |
| Gigabyte      | H55M-S2HP                   | [24bb32f99c](https://linux-hardware.org/?probe=24bb32f99c) | Dec 20, 2021 |
| ASUSTek       | K30BF_M32BF                 | [cf315ce3d1](https://linux-hardware.org/?probe=cf315ce3d1) | Dec 20, 2021 |
| MSI           | H310M PRO-VD                | [8d882031dc](https://linux-hardware.org/?probe=8d882031dc) | Dec 20, 2021 |
| MSI           | H310M PRO-VD                | [b1e22517f3](https://linux-hardware.org/?probe=b1e22517f3) | Dec 19, 2021 |
| ASRock        | AM1B-ITX                    | [50d68d9e27](https://linux-hardware.org/?probe=50d68d9e27) | Dec 19, 2021 |
| MSI           | MEG B550 UNIFY-X            | [4371d24300](https://linux-hardware.org/?probe=4371d24300) | Dec 19, 2021 |
| ASUSTek       | Maximus VII HERO            | [d13d9d333c](https://linux-hardware.org/?probe=d13d9d333c) | Dec 19, 2021 |
| ASUSTek       | M51BC                       | [cc33b3c3de](https://linux-hardware.org/?probe=cc33b3c3de) | Dec 19, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [8e9f7296a1](https://linux-hardware.org/?probe=8e9f7296a1) | Dec 19, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [6732863f05](https://linux-hardware.org/?probe=6732863f05) | Dec 19, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [2a8ce98dc1](https://linux-hardware.org/?probe=2a8ce98dc1) | Dec 19, 2021 |
| Unknown       | Unknown                     | [66758e1d27](https://linux-hardware.org/?probe=66758e1d27) | Dec 18, 2021 |
| ASUSTek       | PRIME B450M-A               | [efd600293e](https://linux-hardware.org/?probe=efd600293e) | Dec 18, 2021 |
| Medion        | MS-7707                     | [7df27b874f](https://linux-hardware.org/?probe=7df27b874f) | Dec 18, 2021 |
| ASRock        | 775Dual-VSTA                | [ab1b144f72](https://linux-hardware.org/?probe=ab1b144f72) | Dec 18, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [1e14543dfd](https://linux-hardware.org/?probe=1e14543dfd) | Dec 18, 2021 |
| ASUSTek       | H170M-PLUS                  | [3e25d6dd20](https://linux-hardware.org/?probe=3e25d6dd20) | Dec 18, 2021 |
| Intel         | DH61CR AAG14064-204         | [13c79f41a6](https://linux-hardware.org/?probe=13c79f41a6) | Dec 18, 2021 |
| MSI           | Z170-A PRO                  | [71409aa774](https://linux-hardware.org/?probe=71409aa774) | Dec 18, 2021 |
| Gigabyte      | H61M-DS2 DVI                | [1252e4adb0](https://linux-hardware.org/?probe=1252e4adb0) | Dec 18, 2021 |
| Dell          | 0J3C2F A00                  | [6a5d19d886](https://linux-hardware.org/?probe=6a5d19d886) | Dec 18, 2021 |
| MSI           | B450M PRO-VDH MAX           | [3879747d77](https://linux-hardware.org/?probe=3879747d77) | Dec 18, 2021 |
| ASUSTek       | Leonite2                    | [6daf99569d](https://linux-hardware.org/?probe=6daf99569d) | Dec 17, 2021 |
| ASUSTek       | P8H61-M LE                  | [b8be0cdaef](https://linux-hardware.org/?probe=b8be0cdaef) | Dec 17, 2021 |
| ASUSTek       | PRIME Z590-P                | [653951ef3c](https://linux-hardware.org/?probe=653951ef3c) | Dec 17, 2021 |
| ASRock        | 970A-G                      | [3329908d4f](https://linux-hardware.org/?probe=3329908d4f) | Dec 17, 2021 |
| BESSTAR Te... | HM50                        | [f83d953bf8](https://linux-hardware.org/?probe=f83d953bf8) | Dec 17, 2021 |
| MSI           | Z390-A PRO                  | [c1a35b5a0c](https://linux-hardware.org/?probe=c1a35b5a0c) | Dec 17, 2021 |
| ASRock        | AB350M Pro4                 | [4738ccac47](https://linux-hardware.org/?probe=4738ccac47) | Dec 16, 2021 |
| ASRock        | AB350M Pro4                 | [5e55084c3e](https://linux-hardware.org/?probe=5e55084c3e) | Dec 16, 2021 |
| MSI           | H81M-P33                    | [cd3905cb0a](https://linux-hardware.org/?probe=cd3905cb0a) | Dec 16, 2021 |
| Intel         | DH61CR AAG14064-204         | [247642d30f](https://linux-hardware.org/?probe=247642d30f) | Dec 16, 2021 |
| ASUSTek       | M2N68-AM SE2                | [0b7832c8d4](https://linux-hardware.org/?probe=0b7832c8d4) | Dec 16, 2021 |
| Intel         | DH61CR AAG14064-204         | [dbc555c5ad](https://linux-hardware.org/?probe=dbc555c5ad) | Dec 16, 2021 |
| Dell          | 0Y2MRG A00                  | [dfb598a85c](https://linux-hardware.org/?probe=dfb598a85c) | Dec 16, 2021 |
| MSI           | B450M PRO-VDH MAX           | [4995f4578e](https://linux-hardware.org/?probe=4995f4578e) | Dec 16, 2021 |
| HP            | 3032h                       | [b835cd4718](https://linux-hardware.org/?probe=b835cd4718) | Dec 16, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | [100a29da37](https://linux-hardware.org/?probe=100a29da37) | Dec 16, 2021 |
| ASUSTek       | P5QD TURBO                  | [eab6a0aed6](https://linux-hardware.org/?probe=eab6a0aed6) | Dec 16, 2021 |
| Dell          | 0GM819                      | [809fc591dd](https://linux-hardware.org/?probe=809fc591dd) | Dec 16, 2021 |
| Lenovo        | MAHOBAY                     | [734f764d4b](https://linux-hardware.org/?probe=734f764d4b) | Dec 15, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [830b8475ac](https://linux-hardware.org/?probe=830b8475ac) | Dec 15, 2021 |
| ASUSTek       | SABERTOOTH P67              | [af2732b8a5](https://linux-hardware.org/?probe=af2732b8a5) | Dec 15, 2021 |
| HP            | 2AA6 PVT                    | [e2c989bfdb](https://linux-hardware.org/?probe=e2c989bfdb) | Dec 15, 2021 |
| BESSTAR Te... | HM50                        | [cb2d53c616](https://linux-hardware.org/?probe=cb2d53c616) | Dec 15, 2021 |
| ASUSTek       | Rampage Formula             | [1c224f9f9a](https://linux-hardware.org/?probe=1c224f9f9a) | Dec 15, 2021 |
| Dell          | 0PU052                      | [280cb1ef78](https://linux-hardware.org/?probe=280cb1ef78) | Dec 14, 2021 |
| Biostar       | Hi-Fi H61S3                 | [e1362b0ad2](https://linux-hardware.org/?probe=e1362b0ad2) | Dec 14, 2021 |
| MSI           | Z390-A PRO                  | [625e13ab90](https://linux-hardware.org/?probe=625e13ab90) | Dec 14, 2021 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [c38b4574db](https://linux-hardware.org/?probe=c38b4574db) | Dec 14, 2021 |
| Medion        | Cattle24 1M                 | [2d145ac87e](https://linux-hardware.org/?probe=2d145ac87e) | Dec 14, 2021 |
| ASRock        | M3A770DE                    | [15671c0dbe](https://linux-hardware.org/?probe=15671c0dbe) | Dec 14, 2021 |
| Apple         | Mac-F221BEC8                | [44378ec4a5](https://linux-hardware.org/?probe=44378ec4a5) | Dec 14, 2021 |
| Fujitsu Si... | D2724-A1 S26361-D2724-A1    | [3760c1b2c2](https://linux-hardware.org/?probe=3760c1b2c2) | Dec 14, 2021 |
| ASUSTek       | PRIME B450M-A               | [fff0d6956f](https://linux-hardware.org/?probe=fff0d6956f) | Dec 14, 2021 |
| Gigabyte      | G31M-ES2L                   | [f03b1893e9](https://linux-hardware.org/?probe=f03b1893e9) | Dec 14, 2021 |
| MSI           | B450M PRO-VDH MAX           | [99b31d7eec](https://linux-hardware.org/?probe=99b31d7eec) | Dec 14, 2021 |
| MSI           | Z97 GUARD-PRO               | [dcc4b73b5c](https://linux-hardware.org/?probe=dcc4b73b5c) | Dec 14, 2021 |
| HP            | 0A64h                       | [54455563ba](https://linux-hardware.org/?probe=54455563ba) | Dec 14, 2021 |
| Gigabyte      | H110M-H-CF                  | [bc401cc9a6](https://linux-hardware.org/?probe=bc401cc9a6) | Dec 14, 2021 |
| HP            | 2B01                        | [f4cb17bb56](https://linux-hardware.org/?probe=f4cb17bb56) | Dec 14, 2021 |
| ASUSTek       | Z87-K                       | [08b5848d9e](https://linux-hardware.org/?probe=08b5848d9e) | Dec 14, 2021 |
| ASUSTek       | K30BF_M32BF                 | [d4423ab3b1](https://linux-hardware.org/?probe=d4423ab3b1) | Dec 14, 2021 |
| Shuttle       | FH61V                       | [b4c8a91d0f](https://linux-hardware.org/?probe=b4c8a91d0f) | Dec 13, 2021 |
| HP            | 1495                        | [7566d35441](https://linux-hardware.org/?probe=7566d35441) | Dec 13, 2021 |
| Gigabyte      | B250M-D3H-CF                | [903dfc6f62](https://linux-hardware.org/?probe=903dfc6f62) | Dec 13, 2021 |
| Medion        | Cattle24 1M                 | [4fdfe223e0](https://linux-hardware.org/?probe=4fdfe223e0) | Dec 13, 2021 |
| MSI           | MS-B1831                    | [30448f7ed3](https://linux-hardware.org/?probe=30448f7ed3) | Dec 13, 2021 |
| ASRock        | Z87 Extreme6                | [38f238572c](https://linux-hardware.org/?probe=38f238572c) | Dec 13, 2021 |
| HP            | 2AA6 PVT                    | [427171911e](https://linux-hardware.org/?probe=427171911e) | Dec 13, 2021 |
| ASRock        | H81M-HDS                    | [010e56531a](https://linux-hardware.org/?probe=010e56531a) | Dec 13, 2021 |
| Lenovo        | 31900058 STD                | [460a4eb80d](https://linux-hardware.org/?probe=460a4eb80d) | Dec 12, 2021 |
| HP            | 339A                        | [14f4f8df69](https://linux-hardware.org/?probe=14f4f8df69) | Dec 12, 2021 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [d08ae710bd](https://linux-hardware.org/?probe=d08ae710bd) | Dec 12, 2021 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [304e2838c7](https://linux-hardware.org/?probe=304e2838c7) | Dec 12, 2021 |
| ASRock        | 970A-G                      | [b2a7c58757](https://linux-hardware.org/?probe=b2a7c58757) | Dec 12, 2021 |
| HP            | 2B01                        | [d08f58a515](https://linux-hardware.org/?probe=d08f58a515) | Dec 12, 2021 |
| Acer          | E415SM                      | [cf0a135e4f](https://linux-hardware.org/?probe=cf0a135e4f) | Dec 12, 2021 |
| ASRock        | A320M-HD                    | [411bdbd3ed](https://linux-hardware.org/?probe=411bdbd3ed) | Dec 12, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [dd2c5e5957](https://linux-hardware.org/?probe=dd2c5e5957) | Dec 12, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [4a558bf6f1](https://linux-hardware.org/?probe=4a558bf6f1) | Dec 11, 2021 |
| Positivo      | POS-MI945AA                 | [d41df45a2d](https://linux-hardware.org/?probe=d41df45a2d) | Dec 11, 2021 |
| ASUSTek       | Bantry CRB SDK0E50510 WI... | [5dfc7cb81a](https://linux-hardware.org/?probe=5dfc7cb81a) | Dec 11, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | [e1ad26f0df](https://linux-hardware.org/?probe=e1ad26f0df) | Dec 11, 2021 |
| ASUSTek       | PRIME B550M-A               | [be567b9516](https://linux-hardware.org/?probe=be567b9516) | Dec 11, 2021 |
| Dell          | 0HY9JP A02                  | [edd20bb393](https://linux-hardware.org/?probe=edd20bb393) | Dec 11, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [9c363da2d7](https://linux-hardware.org/?probe=9c363da2d7) | Dec 11, 2021 |
| ASUSTek       | M5A78L LE                   | [52573eec91](https://linux-hardware.org/?probe=52573eec91) | Dec 11, 2021 |
| Packard Be... | IMEDIA S3810                | [f8085b1034](https://linux-hardware.org/?probe=f8085b1034) | Dec 11, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [aeb068d87a](https://linux-hardware.org/?probe=aeb068d87a) | Dec 11, 2021 |
| ASRockRack    | C236 WS                     | [079f4a8017](https://linux-hardware.org/?probe=079f4a8017) | Dec 11, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [ee015a6612](https://linux-hardware.org/?probe=ee015a6612) | Dec 10, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [a17cc5dc62](https://linux-hardware.org/?probe=a17cc5dc62) | Dec 10, 2021 |
| Medion        | MS-7633                     | [de58cbbfe7](https://linux-hardware.org/?probe=de58cbbfe7) | Dec 10, 2021 |
| Intel         | DH67CL AAG10212-210         | [ce021bf4dc](https://linux-hardware.org/?probe=ce021bf4dc) | Dec 10, 2021 |
| ASUSTek       | EX-B150M-V3                 | [b999617124](https://linux-hardware.org/?probe=b999617124) | Dec 10, 2021 |
| ASRock        | B450M Steel Legend          | [a5c3366e73](https://linux-hardware.org/?probe=a5c3366e73) | Dec 10, 2021 |
| HP            | 2AE3                        | [097cb47ea8](https://linux-hardware.org/?probe=097cb47ea8) | Dec 10, 2021 |
| HP            | 2AE3                        | [751335e09a](https://linux-hardware.org/?probe=751335e09a) | Dec 10, 2021 |
| Pegatron      | Eureka3                     | [de5382fb1e](https://linux-hardware.org/?probe=de5382fb1e) | Dec 09, 2021 |
| ASUSTek       | M2N68-AM SE2                | [623b76cf55](https://linux-hardware.org/?probe=623b76cf55) | Dec 09, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [ac173fd5ba](https://linux-hardware.org/?probe=ac173fd5ba) | Dec 09, 2021 |
| ASRock        | P67 Pro3                    | [7d033ae039](https://linux-hardware.org/?probe=7d033ae039) | Dec 09, 2021 |
| ASUSTek       | P8Z77-V LX                  | [892d6ba035](https://linux-hardware.org/?probe=892d6ba035) | Dec 09, 2021 |
| Dell          | 06D7TR A00                  | [90f509fc24](https://linux-hardware.org/?probe=90f509fc24) | Dec 09, 2021 |
| MSI           | B350 TOMAHAWK               | [664eef2dcd](https://linux-hardware.org/?probe=664eef2dcd) | Dec 09, 2021 |
| Acer          | Veriton N4620G              | [5ae13b415d](https://linux-hardware.org/?probe=5ae13b415d) | Dec 08, 2021 |
| ASUSTek       | PRIME Z390-A                | [e884cd44db](https://linux-hardware.org/?probe=e884cd44db) | Dec 08, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [d16919abc9](https://linux-hardware.org/?probe=d16919abc9) | Dec 08, 2021 |
| MSI           | MAG B550M BAZOOKA           | [11f31cc288](https://linux-hardware.org/?probe=11f31cc288) | Dec 08, 2021 |
| ASRock        | H55DE3                      | [30f7ecb27c](https://linux-hardware.org/?probe=30f7ecb27c) | Dec 08, 2021 |
| ASRock        | B450M Pro4                  | [032805bb35](https://linux-hardware.org/?probe=032805bb35) | Dec 08, 2021 |
| HP            | 2AE3                        | [a1cc0f1566](https://linux-hardware.org/?probe=a1cc0f1566) | Dec 08, 2021 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [b1ff547978](https://linux-hardware.org/?probe=b1ff547978) | Dec 07, 2021 |
| Gigabyte      | GA-970A-UD3                 | [85ffe220e9](https://linux-hardware.org/?probe=85ffe220e9) | Dec 07, 2021 |
| Foxconn       | B75MX                       | [029ee6b952](https://linux-hardware.org/?probe=029ee6b952) | Dec 07, 2021 |
| ASRock        | M3A770DE                    | [f0f197bdf8](https://linux-hardware.org/?probe=f0f197bdf8) | Dec 07, 2021 |
| Dell          | 0D28YY A00                  | [4c043a698b](https://linux-hardware.org/?probe=4c043a698b) | Dec 07, 2021 |
| ASUSTek       | P8B75-M LE                  | [fba5b9a41b](https://linux-hardware.org/?probe=fba5b9a41b) | Dec 07, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [f10c0bd6ce](https://linux-hardware.org/?probe=f10c0bd6ce) | Dec 07, 2021 |
| MSI           | PRO Z690-A DDR4             | [86d4be8f0c](https://linux-hardware.org/?probe=86d4be8f0c) | Dec 06, 2021 |
| Foxconn       | B75MX                       | [4715fec55b](https://linux-hardware.org/?probe=4715fec55b) | Dec 06, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [3d7d697cd5](https://linux-hardware.org/?probe=3d7d697cd5) | Dec 06, 2021 |
| HP            | 2B01                        | [585b1485f9](https://linux-hardware.org/?probe=585b1485f9) | Dec 06, 2021 |
| HP            | 2B01                        | [7c9875bdcf](https://linux-hardware.org/?probe=7c9875bdcf) | Dec 06, 2021 |
| Gigabyte      | MZBSWAP-K4                  | [944d447a7c](https://linux-hardware.org/?probe=944d447a7c) | Dec 06, 2021 |
| Gigabyte      | MZBSWAP-K4                  | [571baeeaa8](https://linux-hardware.org/?probe=571baeeaa8) | Dec 06, 2021 |
| Lenovo        | ThinkCentre M81 5049W16     | [ca1fd18874](https://linux-hardware.org/?probe=ca1fd18874) | Dec 05, 2021 |
| Dell          | 0HY9JP A02                  | [6cd6e09d21](https://linux-hardware.org/?probe=6cd6e09d21) | Dec 05, 2021 |
| ASUSTek       | B150I PRO GAMING/AURA       | [12182b50f7](https://linux-hardware.org/?probe=12182b50f7) | Dec 05, 2021 |
| Dell          | 0XR1GT A00                  | [1c1487bb5e](https://linux-hardware.org/?probe=1c1487bb5e) | Dec 05, 2021 |
| ASUSTek       | SABERTOOTH Z170 S           | [172ac4b2c9](https://linux-hardware.org/?probe=172ac4b2c9) | Dec 04, 2021 |
| Dell          | 0M863N A01                  | [01a565720c](https://linux-hardware.org/?probe=01a565720c) | Dec 04, 2021 |
| ASUSTek       | PRIME Z270-P                | [dea0e367e1](https://linux-hardware.org/?probe=dea0e367e1) | Dec 04, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [589a80be53](https://linux-hardware.org/?probe=589a80be53) | Dec 04, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | [4c79974ae8](https://linux-hardware.org/?probe=4c79974ae8) | Dec 03, 2021 |
| Gigabyte      | 990FXA-UD3                  | [f211a992b1](https://linux-hardware.org/?probe=f211a992b1) | Dec 03, 2021 |
| HP            | 806A                        | [1cbc4216fb](https://linux-hardware.org/?probe=1cbc4216fb) | Dec 03, 2021 |
| Unknown       | G41                         | [3f29d6f6fe](https://linux-hardware.org/?probe=3f29d6f6fe) | Dec 03, 2021 |
| Acer          | F672CR R01-A4               | [ee1bc7199e](https://linux-hardware.org/?probe=ee1bc7199e) | Dec 03, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [28570df433](https://linux-hardware.org/?probe=28570df433) | Dec 03, 2021 |
| Unknown       | Unknown                     | [0b08c43da5](https://linux-hardware.org/?probe=0b08c43da5) | Dec 03, 2021 |
| Dell          | 0JP3NX A01                  | [b1a639beb6](https://linux-hardware.org/?probe=b1a639beb6) | Dec 02, 2021 |
| HP            | 2B34                        | [38071b922e](https://linux-hardware.org/?probe=38071b922e) | Dec 02, 2021 |
| Gigabyte      | B460M DS3H V2               | [a0a3f5e715](https://linux-hardware.org/?probe=a0a3f5e715) | Dec 02, 2021 |
| Unknown       | 1.0                         | [412614529f](https://linux-hardware.org/?probe=412614529f) | Dec 02, 2021 |
| Dell          | 0WF810                      | [d943ed3484](https://linux-hardware.org/?probe=d943ed3484) | Dec 02, 2021 |
| Dell          | 0TP412                      | [b4fffa7540](https://linux-hardware.org/?probe=b4fffa7540) | Dec 02, 2021 |
| MSI           | A320M-A PRO MAX             | [fe9d69185a](https://linux-hardware.org/?probe=fe9d69185a) | Dec 02, 2021 |
| Dell          | 0D8312 A00                  | [806ae8b9e6](https://linux-hardware.org/?probe=806ae8b9e6) | Dec 02, 2021 |
| Lenovo        | ThinkCentre A52 8381W7G     | [3439a0acde](https://linux-hardware.org/?probe=3439a0acde) | Dec 02, 2021 |
| Biostar       | NF61V-M2                    | [0d21d633c9](https://linux-hardware.org/?probe=0d21d633c9) | Dec 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [46024c473c](https://linux-hardware.org/?probe=46024c473c) | Dec 01, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [7221613dbc](https://linux-hardware.org/?probe=7221613dbc) | Dec 01, 2021 |
| ASUSTek       | PRIME B450M-A               | [b11c66e0d4](https://linux-hardware.org/?probe=b11c66e0d4) | Dec 01, 2021 |
| ASUSTek       | PRIME B550M-A               | [c0b2c3fff7](https://linux-hardware.org/?probe=c0b2c3fff7) | Dec 01, 2021 |
| HP            | 1998                        | [ffa6c0b239](https://linux-hardware.org/?probe=ffa6c0b239) | Dec 01, 2021 |
| ASUSTek       | P5Q3                        | [ec0154a347](https://linux-hardware.org/?probe=ec0154a347) | Dec 01, 2021 |
| Unknown       | G41                         | [90924fdb20](https://linux-hardware.org/?probe=90924fdb20) | Dec 01, 2021 |
| ASUSTek       | P5Q3                        | [95f0ad6552](https://linux-hardware.org/?probe=95f0ad6552) | Dec 01, 2021 |
| MSI           | Z170-A PRO                  | [c2f7b10891](https://linux-hardware.org/?probe=c2f7b10891) | Dec 01, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [1d6ece4240](https://linux-hardware.org/?probe=1d6ece4240) | Dec 01, 2021 |
| Acer          | Aspire X1420                | [ff2c8a9378](https://linux-hardware.org/?probe=ff2c8a9378) | Dec 01, 2021 |
| Gigabyte      | G31M-ES2L                   | [960a8d5f25](https://linux-hardware.org/?probe=960a8d5f25) | Dec 01, 2021 |
| Foxconn       | 2A8Ch                       | [1eff06a331](https://linux-hardware.org/?probe=1eff06a331) | Nov 30, 2021 |
| ASRock        | 970 Pro3 R2.0               | [20db47125e](https://linux-hardware.org/?probe=20db47125e) | Nov 30, 2021 |
| ASRock        | 970 Pro3 R2.0               | [3ccb9d6a82](https://linux-hardware.org/?probe=3ccb9d6a82) | Nov 30, 2021 |
| Dell          | 0WK833                      | [59fed7d754](https://linux-hardware.org/?probe=59fed7d754) | Nov 30, 2021 |
| Apple         | Mac-F221BEC8                | [b752e7c259](https://linux-hardware.org/?probe=b752e7c259) | Nov 30, 2021 |
| MSI           | IONA                        | [67baa8e7a8](https://linux-hardware.org/?probe=67baa8e7a8) | Nov 30, 2021 |
| ECS           | H61H2-M6                    | [e044b4f23e](https://linux-hardware.org/?probe=e044b4f23e) | Nov 30, 2021 |
| ASRock        | B365 Phantom Gaming 4       | [425797ccc6](https://linux-hardware.org/?probe=425797ccc6) | Nov 30, 2021 |
| ASRock        | B450 Steel Legend           | [c1991967bb](https://linux-hardware.org/?probe=c1991967bb) | Nov 30, 2021 |
| Medion        | H110H4-EM                   | [d5db91e351](https://linux-hardware.org/?probe=d5db91e351) | Nov 30, 2021 |
| Dell          | 0MN1TX A00                  | [2d19165008](https://linux-hardware.org/?probe=2d19165008) | Nov 29, 2021 |
| Huanan        | X99-F8 GAMING V2.0          | [12d13db993](https://linux-hardware.org/?probe=12d13db993) | Nov 29, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [b3f954f0ca](https://linux-hardware.org/?probe=b3f954f0ca) | Nov 29, 2021 |
| Dell          | 0MN1TX A00                  | [8418cce749](https://linux-hardware.org/?probe=8418cce749) | Nov 29, 2021 |
| ASUSTek       | F1A55-M LK R2.0             | [45faf5c05a](https://linux-hardware.org/?probe=45faf5c05a) | Nov 29, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [ce70e58cb7](https://linux-hardware.org/?probe=ce70e58cb7) | Nov 28, 2021 |
| Huanan        | X99-F8 GAMING V2.0          | [7e68f244db](https://linux-hardware.org/?probe=7e68f244db) | Nov 28, 2021 |
| Huanan        | X99-F8 GAMING V2.0          | [44a2f22839](https://linux-hardware.org/?probe=44a2f22839) | Nov 28, 2021 |
| ASUSTek       | H97M-E                      | [4a9ecb83f8](https://linux-hardware.org/?probe=4a9ecb83f8) | Nov 28, 2021 |
| Gigabyte      | EP45C-DS3R                  | [7229f8da38](https://linux-hardware.org/?probe=7229f8da38) | Nov 28, 2021 |
| Gigabyte      | EP45C-DS3R                  | [4d539399e2](https://linux-hardware.org/?probe=4d539399e2) | Nov 28, 2021 |
| Gigabyte      | M57SLI-S4                   | [a9e4e25600](https://linux-hardware.org/?probe=a9e4e25600) | Nov 28, 2021 |
| HP            | 18E7                        | [4e517ee57d](https://linux-hardware.org/?probe=4e517ee57d) | Nov 28, 2021 |
| ASUSTek       | P8Q77-M                     | [8750a82b89](https://linux-hardware.org/?probe=8750a82b89) | Nov 28, 2021 |
| ASUSTek       | PRIME B560M-A               | [e03e498453](https://linux-hardware.org/?probe=e03e498453) | Nov 28, 2021 |
| Gigabyte      | B550M S2H                   | [1b41504caf](https://linux-hardware.org/?probe=1b41504caf) | Nov 28, 2021 |
| Gigabyte      | GA-770T-USB3                | [3ec823c570](https://linux-hardware.org/?probe=3ec823c570) | Nov 28, 2021 |
| Lenovo        | 1730BF8                     | [0c2c4e548a](https://linux-hardware.org/?probe=0c2c4e548a) | Nov 28, 2021 |
| ASRock        | Z77 Extreme6                | [3823cd8f77](https://linux-hardware.org/?probe=3823cd8f77) | Nov 28, 2021 |
| MSI           | 970 GAMING                  | [2c7f8bf22f](https://linux-hardware.org/?probe=2c7f8bf22f) | Nov 28, 2021 |
| MSI           | 970 GAMING                  | [cc054ae3fa](https://linux-hardware.org/?probe=cc054ae3fa) | Nov 28, 2021 |
| Emaxx Tech... | EMX-A55GT-iCafe V1.0        | [d6d799c3d8](https://linux-hardware.org/?probe=d6d799c3d8) | Nov 28, 2021 |
| ASUSTek       | SABERTOOTH X58              | [5192024675](https://linux-hardware.org/?probe=5192024675) | Nov 28, 2021 |
| Gigabyte      | B560M AORUS ELITE           | [03fbeed10f](https://linux-hardware.org/?probe=03fbeed10f) | Nov 28, 2021 |
| HP            | 2AA6 PVT                    | [50eb4adc3b](https://linux-hardware.org/?probe=50eb4adc3b) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [9bbe9ad940](https://linux-hardware.org/?probe=9bbe9ad940) | Nov 27, 2021 |
| HP            | 83EE                        | [19b7dc07a6](https://linux-hardware.org/?probe=19b7dc07a6) | Nov 27, 2021 |
| HP            | 2B52                        | [8b8194b666](https://linux-hardware.org/?probe=8b8194b666) | Nov 27, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [8e8b1fa1d0](https://linux-hardware.org/?probe=8e8b1fa1d0) | Nov 27, 2021 |
| Dell          | 0KC9NP A01                  | [5a3c7dac55](https://linux-hardware.org/?probe=5a3c7dac55) | Nov 27, 2021 |
| HC            | HCAR357-MI V1.0             | [c095de3db5](https://linux-hardware.org/?probe=c095de3db5) | Nov 27, 2021 |
| Dell          | 0WR7PY A02                  | [2f54ed391e](https://linux-hardware.org/?probe=2f54ed391e) | Nov 27, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [feb01c3dfa](https://linux-hardware.org/?probe=feb01c3dfa) | Nov 27, 2021 |
| Gigabyte      | H77M-D3H                    | [8b2be4927b](https://linux-hardware.org/?probe=8b2be4927b) | Nov 27, 2021 |
| Gigabyte      | EP45-DS3                    | [b7cb8d0193](https://linux-hardware.org/?probe=b7cb8d0193) | Nov 27, 2021 |
| ASUSTek       | Z87-K                       | [623d4f0e7d](https://linux-hardware.org/?probe=623d4f0e7d) | Nov 27, 2021 |
| ASUSTek       | SABERTOOTH X58              | [5615c3d1e5](https://linux-hardware.org/?probe=5615c3d1e5) | Nov 27, 2021 |
| Dell          | 0W5363                      | [60dbdd680a](https://linux-hardware.org/?probe=60dbdd680a) | Nov 26, 2021 |
| MSI           | B450M-A PRO MAX             | [602d5d0655](https://linux-hardware.org/?probe=602d5d0655) | Nov 26, 2021 |
| ASUSTek       | Leonite2                    | [cb3be45b72](https://linux-hardware.org/?probe=cb3be45b72) | Nov 26, 2021 |
| HP            | 8266                        | [ffadccf874](https://linux-hardware.org/?probe=ffadccf874) | Nov 26, 2021 |
| ASRock        | APL-NUC/J3455               | [75a1e66d2a](https://linux-hardware.org/?probe=75a1e66d2a) | Nov 26, 2021 |
| Dell          | 0D28YY A00                  | [2bc32a3aff](https://linux-hardware.org/?probe=2bc32a3aff) | Nov 26, 2021 |
| MSI           | B450M MORTAR MAX            | [cbf00405ff](https://linux-hardware.org/?probe=cbf00405ff) | Nov 26, 2021 |
| Dell          | 0F8101                      | [23d78dfe12](https://linux-hardware.org/?probe=23d78dfe12) | Nov 26, 2021 |
| ASUSTek       | P8Z68-V PRO                 | [72ecba39fa](https://linux-hardware.org/?probe=72ecba39fa) | Nov 26, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [deed540bd4](https://linux-hardware.org/?probe=deed540bd4) | Nov 26, 2021 |
| ASUSTek       | P5QL-VM EPU                 | [1331462ff8](https://linux-hardware.org/?probe=1331462ff8) | Nov 25, 2021 |
| MSI           | Z87-G45 GAMING              | [7c047cfb26](https://linux-hardware.org/?probe=7c047cfb26) | Nov 25, 2021 |
| Unknown       | Unknown                     | [9048aa2348](https://linux-hardware.org/?probe=9048aa2348) | Nov 25, 2021 |
| Dell          | 0HY9JP A02                  | [4b65b967b3](https://linux-hardware.org/?probe=4b65b967b3) | Nov 25, 2021 |
| ASRock        | B450M Pro4-F R2.0           | [34f8237b63](https://linux-hardware.org/?probe=34f8237b63) | Nov 25, 2021 |
| ASRock        | B450 Steel Legend           | [1e7f899e34](https://linux-hardware.org/?probe=1e7f899e34) | Nov 25, 2021 |
| HP            | 3646h                       | [096733a0fa](https://linux-hardware.org/?probe=096733a0fa) | Nov 25, 2021 |
| HP            | 3646h                       | [36b1e0c879](https://linux-hardware.org/?probe=36b1e0c879) | Nov 25, 2021 |
| ASUSTek       | PRIME B360-PLUS             | [515b608f63](https://linux-hardware.org/?probe=515b608f63) | Nov 25, 2021 |
| ASRock        | APL-NUC/J3455               | [3857c5d565](https://linux-hardware.org/?probe=3857c5d565) | Nov 25, 2021 |
| Gateway       | DX4840                      | [c62f7de8fb](https://linux-hardware.org/?probe=c62f7de8fb) | Nov 25, 2021 |
| HP            | 1998                        | [96a848eddc](https://linux-hardware.org/?probe=96a848eddc) | Nov 24, 2021 |
| Acer          | Revo 70                     | [f5cdb95334](https://linux-hardware.org/?probe=f5cdb95334) | Nov 24, 2021 |
| Acer          | Revo 70                     | [4c99b6ac71](https://linux-hardware.org/?probe=4c99b6ac71) | Nov 24, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [11ec96a447](https://linux-hardware.org/?probe=11ec96a447) | Nov 24, 2021 |
| Gigabyte      | B460M DS3H V2               | [2b9c97a79a](https://linux-hardware.org/?probe=2b9c97a79a) | Nov 24, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [fa956800a1](https://linux-hardware.org/?probe=fa956800a1) | Nov 24, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [3d27077285](https://linux-hardware.org/?probe=3d27077285) | Nov 24, 2021 |
| Gigabyte      | 970A-DS3P                   | [b718c829fa](https://linux-hardware.org/?probe=b718c829fa) | Nov 24, 2021 |
| Lenovo        | ThinkCentre A52 8381W7G     | [6a0e22157b](https://linux-hardware.org/?probe=6a0e22157b) | Nov 24, 2021 |
| ECS           | H81H3-WM                    | [3d0098dbe6](https://linux-hardware.org/?probe=3d0098dbe6) | Nov 24, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [6534df978c](https://linux-hardware.org/?probe=6534df978c) | Nov 24, 2021 |
| HP            | 2B52                        | [6c454a9414](https://linux-hardware.org/?probe=6c454a9414) | Nov 23, 2021 |
| ASUSTek       | AM1M-A                      | [5114945f73](https://linux-hardware.org/?probe=5114945f73) | Nov 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [93a3a6475c](https://linux-hardware.org/?probe=93a3a6475c) | Nov 23, 2021 |
| ASRock        | J3455-ITX                   | [790f5ef7cf](https://linux-hardware.org/?probe=790f5ef7cf) | Nov 23, 2021 |
| Gigabyte      | H61M-S2PV                   | [09b0e5058d](https://linux-hardware.org/?probe=09b0e5058d) | Nov 23, 2021 |
| ASUSTek       | Maximus IX HERO             | [5ac31a5e1f](https://linux-hardware.org/?probe=5ac31a5e1f) | Nov 23, 2021 |
| HP            | 8433 11                     | [e88c3d4a94](https://linux-hardware.org/?probe=e88c3d4a94) | Nov 22, 2021 |
| MSI           | H97M-G43                    | [72386930d0](https://linux-hardware.org/?probe=72386930d0) | Nov 22, 2021 |
| ASRock        | B550 Phantom Gaming 4       | [c158203eef](https://linux-hardware.org/?probe=c158203eef) | Nov 22, 2021 |
| Dell          | 0C522T A03                  | [9d6247f04c](https://linux-hardware.org/?probe=9d6247f04c) | Nov 22, 2021 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [7aa1a970ed](https://linux-hardware.org/?probe=7aa1a970ed) | Nov 22, 2021 |
| Acer          | Aspire X3995                | [cde003006d](https://linux-hardware.org/?probe=cde003006d) | Nov 22, 2021 |
| Acer          | Aspire X3995                | [2e97d6ef1c](https://linux-hardware.org/?probe=2e97d6ef1c) | Nov 22, 2021 |
| Dell          | 03NVJ6 A02                  | [8996f56926](https://linux-hardware.org/?probe=8996f56926) | Nov 21, 2021 |
| ASUSTek       | NARRA2                      | [65204d2390](https://linux-hardware.org/?probe=65204d2390) | Nov 21, 2021 |
| HP            | 1998                        | [7bc6ddebf4](https://linux-hardware.org/?probe=7bc6ddebf4) | Nov 21, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [d1d161f6ad](https://linux-hardware.org/?probe=d1d161f6ad) | Nov 21, 2021 |
| Unknown       | Intel X79                   | [b272698078](https://linux-hardware.org/?probe=b272698078) | Nov 21, 2021 |
| Gigabyte      | Z97-HD3                     | [352e08654b](https://linux-hardware.org/?probe=352e08654b) | Nov 21, 2021 |
| Dell          | 0PC5F7 A00                  | [d44907c1b9](https://linux-hardware.org/?probe=d44907c1b9) | Nov 21, 2021 |
| HP            | 1497                        | [2fb6eaa182](https://linux-hardware.org/?probe=2fb6eaa182) | Nov 21, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [e2bb3dc142](https://linux-hardware.org/?probe=e2bb3dc142) | Nov 21, 2021 |
| Gigabyte      | B560M AORUS ELITE           | [cf11451864](https://linux-hardware.org/?probe=cf11451864) | Nov 20, 2021 |
| ASUSTek       | H87M-E                      | [d69611bb86](https://linux-hardware.org/?probe=d69611bb86) | Nov 20, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [ea4842466c](https://linux-hardware.org/?probe=ea4842466c) | Nov 20, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [faf9e68f7a](https://linux-hardware.org/?probe=faf9e68f7a) | Nov 20, 2021 |
| Positivo      | POS-EINM70CS POSITIVO       | [54ef64d5fd](https://linux-hardware.org/?probe=54ef64d5fd) | Nov 20, 2021 |
| ASRock        | B75M R2.0                   | [000f6b6f44](https://linux-hardware.org/?probe=000f6b6f44) | Nov 20, 2021 |
| ASUSTek       | Z87-K                       | [53c5559e94](https://linux-hardware.org/?probe=53c5559e94) | Nov 20, 2021 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [4ca055247e](https://linux-hardware.org/?probe=4ca055247e) | Nov 20, 2021 |
| ASUSTek       | PRIME Z390-A                | [2b2ea53377](https://linux-hardware.org/?probe=2b2ea53377) | Nov 20, 2021 |
| ASUSTek       | P8P67 PRO                   | [e797ef583f](https://linux-hardware.org/?probe=e797ef583f) | Nov 19, 2021 |
| ASUSTek       | P5QL-VM EPU                 | [cd70e0831d](https://linux-hardware.org/?probe=cd70e0831d) | Nov 19, 2021 |
| MSI           | B350 PC MATE                | [01874c1e2b](https://linux-hardware.org/?probe=01874c1e2b) | Nov 19, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [03e757d062](https://linux-hardware.org/?probe=03e757d062) | Nov 19, 2021 |
| Unknown       | NF-MCP78                    | [5475574f89](https://linux-hardware.org/?probe=5475574f89) | Nov 19, 2021 |
| MSI           | 760GM-P21                   | [60c42a39dc](https://linux-hardware.org/?probe=60c42a39dc) | Nov 19, 2021 |
| OEM           | Unknown                     | [fe641f4c72](https://linux-hardware.org/?probe=fe641f4c72) | Nov 19, 2021 |
| Unknown       | Unknown                     | [c33849e45a](https://linux-hardware.org/?probe=c33849e45a) | Nov 19, 2021 |
| OEM           | Unknown                     | [793c116a8d](https://linux-hardware.org/?probe=793c116a8d) | Nov 19, 2021 |
| ASUSTek       | PRIME Z390-A                | [b4512f4b54](https://linux-hardware.org/?probe=b4512f4b54) | Nov 18, 2021 |
| Dell          | 0C27VV A01                  | [4383599975](https://linux-hardware.org/?probe=4383599975) | Nov 18, 2021 |
| HP            | 18E4                        | [bc3a8efa45](https://linux-hardware.org/?probe=bc3a8efa45) | Nov 18, 2021 |
| HP            | 18E4                        | [cd195fcbd7](https://linux-hardware.org/?probe=cd195fcbd7) | Nov 18, 2021 |
| Gigabyte      | G31M-ES2L                   | [e8a4c6e52b](https://linux-hardware.org/?probe=e8a4c6e52b) | Nov 18, 2021 |
| ASUSTek       | H81M-E                      | [b36ffa7c50](https://linux-hardware.org/?probe=b36ffa7c50) | Nov 17, 2021 |
| Gigabyte      | B550M S2H                   | [a5a05ae5c5](https://linux-hardware.org/?probe=a5a05ae5c5) | Nov 17, 2021 |
| Lenovo        | 0B98401 PRO                 | [1a33c95d3b](https://linux-hardware.org/?probe=1a33c95d3b) | Nov 17, 2021 |
| Gigabyte      | B560M DS3H                  | [5622f1a3b7](https://linux-hardware.org/?probe=5622f1a3b7) | Nov 17, 2021 |
| SZMZ          | X99M-G2                     | [14cf409f74](https://linux-hardware.org/?probe=14cf409f74) | Nov 17, 2021 |
| ASUSTek       | A68HM-PLUS                  | [818e4c91d6](https://linux-hardware.org/?probe=818e4c91d6) | Nov 17, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [cacc4df831](https://linux-hardware.org/?probe=cacc4df831) | Nov 16, 2021 |
| ASRock        | Z77 Extreme6                | [a07794cd1b](https://linux-hardware.org/?probe=a07794cd1b) | Nov 16, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [8a16729060](https://linux-hardware.org/?probe=8a16729060) | Nov 16, 2021 |
| ASUSTek       | P8H61-MX R2.0               | [75e04ad411](https://linux-hardware.org/?probe=75e04ad411) | Nov 16, 2021 |
| ECS           | H81H3-WM                    | [7c07ea0038](https://linux-hardware.org/?probe=7c07ea0038) | Nov 16, 2021 |
| ASUSTek       | P5Q                         | [f544ee5b12](https://linux-hardware.org/?probe=f544ee5b12) | Nov 16, 2021 |
| Dell          | 0D28YY A00                  | [5565624f6f](https://linux-hardware.org/?probe=5565624f6f) | Nov 15, 2021 |
| Dell          | 0D28YY A00                  | [f7f26d66a5](https://linux-hardware.org/?probe=f7f26d66a5) | Nov 15, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [6246272890](https://linux-hardware.org/?probe=6246272890) | Nov 15, 2021 |
| Gigabyte      | B460M DS3H V2               | [37e19c1421](https://linux-hardware.org/?probe=37e19c1421) | Nov 15, 2021 |
| MSI           | 970 GAMING                  | [1515779722](https://linux-hardware.org/?probe=1515779722) | Nov 15, 2021 |
| MSI           | 970 GAMING                  | [b74fb29b9b](https://linux-hardware.org/?probe=b74fb29b9b) | Nov 15, 2021 |
| MSI           | H81M-P32L                   | [85e36b9cfc](https://linux-hardware.org/?probe=85e36b9cfc) | Nov 15, 2021 |
| HP            | 2AF7                        | [7002772c56](https://linux-hardware.org/?probe=7002772c56) | Nov 15, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [4859ecd16b](https://linux-hardware.org/?probe=4859ecd16b) | Nov 15, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [bef1d97b7a](https://linux-hardware.org/?probe=bef1d97b7a) | Nov 14, 2021 |
| Gigabyte      | H87M-D3H                    | [2d14af5192](https://linux-hardware.org/?probe=2d14af5192) | Nov 14, 2021 |
| ASRock        | Z590M Phantom Gaming 4      | [f5df2fd431](https://linux-hardware.org/?probe=f5df2fd431) | Nov 14, 2021 |
| MSI           | B75MA-E31                   | [0b8f6946ab](https://linux-hardware.org/?probe=0b8f6946ab) | Nov 14, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [d44f4389ff](https://linux-hardware.org/?probe=d44f4389ff) | Nov 14, 2021 |
| ASUSTek       | P8H61                       | [dac2d8a7ac](https://linux-hardware.org/?probe=dac2d8a7ac) | Nov 14, 2021 |
| ASUSTek       | P8H61                       | [26718af2a1](https://linux-hardware.org/?probe=26718af2a1) | Nov 14, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [71342b9603](https://linux-hardware.org/?probe=71342b9603) | Nov 14, 2021 |
| ASRock        | AM1B-ITX                    | [ad3a01adeb](https://linux-hardware.org/?probe=ad3a01adeb) | Nov 14, 2021 |
| Gigabyte      | Z97-HD3                     | [95b39df23a](https://linux-hardware.org/?probe=95b39df23a) | Nov 14, 2021 |
| Gigabyte      | G41MT-S2PT                  | [3e5ea61173](https://linux-hardware.org/?probe=3e5ea61173) | Nov 14, 2021 |
| MSI           | H55M-E33                    | [f0786be9c3](https://linux-hardware.org/?probe=f0786be9c3) | Nov 14, 2021 |
| MSI           | MS-6579                     | [7f38d38147](https://linux-hardware.org/?probe=7f38d38147) | Nov 14, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [eb3074bfdc](https://linux-hardware.org/?probe=eb3074bfdc) | Nov 14, 2021 |
| MSI           | D2415 S26361-D2415-A10      | [ca4ad59f24](https://linux-hardware.org/?probe=ca4ad59f24) | Nov 14, 2021 |
| ASUSTek       | Z97-P                       | [5a55005b33](https://linux-hardware.org/?probe=5a55005b33) | Nov 13, 2021 |
| Gigabyte      | Z590 GAMING X               | [fa641b1a7e](https://linux-hardware.org/?probe=fa641b1a7e) | Nov 13, 2021 |
| Acer          | EM61SM/EM61PM               | [6a42469739](https://linux-hardware.org/?probe=6a42469739) | Nov 13, 2021 |
| MSI           | Z87-GD65 GAMING             | [0b7991e172](https://linux-hardware.org/?probe=0b7991e172) | Nov 13, 2021 |
| MSI           | Z87-GD65 GAMING             | [dc1ad476f1](https://linux-hardware.org/?probe=dc1ad476f1) | Nov 13, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [698e22c7f3](https://linux-hardware.org/?probe=698e22c7f3) | Nov 13, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [7ac3e325dd](https://linux-hardware.org/?probe=7ac3e325dd) | Nov 13, 2021 |
| MSI           | MS-7255                     | [063f5be918](https://linux-hardware.org/?probe=063f5be918) | Nov 13, 2021 |
| Foxconn       | NETBOX nT-435/535 Ver       | [d895c9e2c9](https://linux-hardware.org/?probe=d895c9e2c9) | Nov 13, 2021 |
| Biostar       | A320MH                      | [13ada6f4f0](https://linux-hardware.org/?probe=13ada6f4f0) | Nov 13, 2021 |
| SIMPC         | MS-7621                     | [3f67bd227e](https://linux-hardware.org/?probe=3f67bd227e) | Nov 13, 2021 |
| ASRock        | M3A770DE                    | [be4e2df627](https://linux-hardware.org/?probe=be4e2df627) | Nov 12, 2021 |
| Dell          | 0MN1TX A00                  | [c780a7f8cb](https://linux-hardware.org/?probe=c780a7f8cb) | Nov 12, 2021 |
| Gigabyte      | B560M AORUS ELITE           | [3f3b79ddbd](https://linux-hardware.org/?probe=3f3b79ddbd) | Nov 12, 2021 |
| Gigabyte      | MJPLNAB-00                  | [4a56fc976e](https://linux-hardware.org/?probe=4a56fc976e) | Nov 12, 2021 |
| ASRock        | X570 Pro4                   | [36ea469d12](https://linux-hardware.org/?probe=36ea469d12) | Nov 12, 2021 |
| Positivo      | POS-PIH81DI                 | [4280461eea](https://linux-hardware.org/?probe=4280461eea) | Nov 12, 2021 |
| Positivo      | POS-PIH81DI                 | [0844d91e6b](https://linux-hardware.org/?probe=0844d91e6b) | Nov 12, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [dde2f42474](https://linux-hardware.org/?probe=dde2f42474) | Nov 12, 2021 |
| ASRock        | B450M Pro4-F                | [83ad065463](https://linux-hardware.org/?probe=83ad065463) | Nov 12, 2021 |
| ASRock        | 970M Pro3                   | [5a73f1875a](https://linux-hardware.org/?probe=5a73f1875a) | Nov 12, 2021 |
| Foxconn       | 2AB1                        | [d21a50bb5d](https://linux-hardware.org/?probe=d21a50bb5d) | Nov 11, 2021 |
| Intel         | DH61BF AAG81311-101         | [42b9be4071](https://linux-hardware.org/?probe=42b9be4071) | Nov 11, 2021 |
| Gigabyte      | 8I915ME                     | [51fcf421f8](https://linux-hardware.org/?probe=51fcf421f8) | Nov 11, 2021 |
| MSI           | MS-7276                     | [c3450557eb](https://linux-hardware.org/?probe=c3450557eb) | Nov 11, 2021 |
| MSI           | B75MA-E33                   | [f1c4e10520](https://linux-hardware.org/?probe=f1c4e10520) | Nov 11, 2021 |
| Medion        | MS-7633                     | [3c937fd332](https://linux-hardware.org/?probe=3c937fd332) | Nov 11, 2021 |
| HP            | 83E9                        | [8f07311f26](https://linux-hardware.org/?probe=8f07311f26) | Nov 11, 2021 |
| MSI           | B450M PRO-VDH MAX           | [426b3eb01d](https://linux-hardware.org/?probe=426b3eb01d) | Nov 11, 2021 |
| ASUSTek       | P5QL-VM EPU                 | [91ee92932b](https://linux-hardware.org/?probe=91ee92932b) | Nov 10, 2021 |
| ASUSTek       | H110I-PLUS                  | [9e4827c307](https://linux-hardware.org/?probe=9e4827c307) | Nov 10, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [09b9df2ead](https://linux-hardware.org/?probe=09b9df2ead) | Nov 10, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [544e219f00](https://linux-hardware.org/?probe=544e219f00) | Nov 10, 2021 |
| Gigabyte      | H110M-M2-CF                 | [83ce5b471d](https://linux-hardware.org/?probe=83ce5b471d) | Nov 10, 2021 |
| Biostar       | G41D3C                      | [dca74215d7](https://linux-hardware.org/?probe=dca74215d7) | Nov 10, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [98e7d0e41c](https://linux-hardware.org/?probe=98e7d0e41c) | Nov 09, 2021 |
| HP            | 1850                        | [be26330bbe](https://linux-hardware.org/?probe=be26330bbe) | Nov 09, 2021 |
| ASUSTek       | P5Q-PRO                     | [2f4f76e796](https://linux-hardware.org/?probe=2f4f76e796) | Nov 09, 2021 |
| MSI           | MAG B365M MORTAR            | [5e5fefb1b6](https://linux-hardware.org/?probe=5e5fefb1b6) | Nov 09, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [c75ffcf988](https://linux-hardware.org/?probe=c75ffcf988) | Nov 09, 2021 |
| ASUSTek       | Maximus V EXTREME           | [c0aa47a4a3](https://linux-hardware.org/?probe=c0aa47a4a3) | Nov 09, 2021 |
| HP            | 339A                        | [702ccff1e4](https://linux-hardware.org/?probe=702ccff1e4) | Nov 09, 2021 |
| Dell          | 0HY9JP A02                  | [d3e0c93641](https://linux-hardware.org/?probe=d3e0c93641) | Nov 08, 2021 |
| ASUSTek       | PRIME B550M-K               | [de9d0e2b40](https://linux-hardware.org/?probe=de9d0e2b40) | Nov 08, 2021 |
| ASRock        | B365M Pro4                  | [ed60292a3d](https://linux-hardware.org/?probe=ed60292a3d) | Nov 08, 2021 |
| ASRock        | 970M Pro3                   | [01629df193](https://linux-hardware.org/?probe=01629df193) | Nov 08, 2021 |
| ASRock        | P67 Pro3                    | [093415210f](https://linux-hardware.org/?probe=093415210f) | Nov 07, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [46a1751e4c](https://linux-hardware.org/?probe=46a1751e4c) | Nov 07, 2021 |
| Biostar       | A10N-8800E                  | [6d26dd46b7](https://linux-hardware.org/?probe=6d26dd46b7) | Nov 07, 2021 |
| ASUSTek       | P6T DELUXE                  | [e0d50907c2](https://linux-hardware.org/?probe=e0d50907c2) | Nov 07, 2021 |
| ASRock        | H81M-HDS R2.0               | [1f2905ba63](https://linux-hardware.org/?probe=1f2905ba63) | Nov 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [74d845aae1](https://linux-hardware.org/?probe=74d845aae1) | Nov 07, 2021 |
| Gigabyte      | B550 AORUS ELITE            | [ad95df4422](https://linux-hardware.org/?probe=ad95df4422) | Nov 07, 2021 |
| Lenovo        | 3138 NO DPK                 | [83dcb96c95](https://linux-hardware.org/?probe=83dcb96c95) | Nov 07, 2021 |
| ASUSTek       | PRIME A320M-K               | [68d7274a99](https://linux-hardware.org/?probe=68d7274a99) | Nov 07, 2021 |
| ASUSTek       | P6T DELUXE                  | [e4a203dda2](https://linux-hardware.org/?probe=e4a203dda2) | Nov 07, 2021 |
| ASUSTek       | H81M-C                      | [09306240c7](https://linux-hardware.org/?probe=09306240c7) | Nov 07, 2021 |
| ASUSTek       | H81M-C                      | [707a5aa817](https://linux-hardware.org/?probe=707a5aa817) | Nov 07, 2021 |
| MSI           | Z370-A PRO                  | [5b4e37e135](https://linux-hardware.org/?probe=5b4e37e135) | Nov 06, 2021 |
| Gigabyte      | H410M S2H V3                | [48ffd402a1](https://linux-hardware.org/?probe=48ffd402a1) | Nov 06, 2021 |
| Lenovo        | ThinkCentre M81 5049W16     | [d1a6793e47](https://linux-hardware.org/?probe=d1a6793e47) | Nov 06, 2021 |
| ASRock        | B560M-HDV                   | [0246e9b73a](https://linux-hardware.org/?probe=0246e9b73a) | Nov 06, 2021 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [0e2e55a9ee](https://linux-hardware.org/?probe=0e2e55a9ee) | Nov 06, 2021 |
| ASUSTek       | P5LD2                       | [7fd427c196](https://linux-hardware.org/?probe=7fd427c196) | Nov 06, 2021 |
| MSI           | H55M-E33                    | [3d8c474259](https://linux-hardware.org/?probe=3d8c474259) | Nov 06, 2021 |
| Gigabyte      | H110M-A-CF                  | [0b0629f3b3](https://linux-hardware.org/?probe=0b0629f3b3) | Nov 06, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [cab956de97](https://linux-hardware.org/?probe=cab956de97) | Nov 06, 2021 |
| ASUSTek       | P8Z77-V                     | [7b16da5c58](https://linux-hardware.org/?probe=7b16da5c58) | Nov 06, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [c1b8176c1c](https://linux-hardware.org/?probe=c1b8176c1c) | Nov 06, 2021 |
| Dell          | 0YF8P5 A00                  | [788f56c983](https://linux-hardware.org/?probe=788f56c983) | Nov 05, 2021 |
| Dell          | 0GY6Y8 A03                  | [e77b328e1e](https://linux-hardware.org/?probe=e77b328e1e) | Nov 05, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [61cdc704e8](https://linux-hardware.org/?probe=61cdc704e8) | Nov 05, 2021 |
| MSI           | B450M GAMING PLUS           | [af595bb903](https://linux-hardware.org/?probe=af595bb903) | Nov 05, 2021 |
| MSI           | B450M GAMING PLUS           | [0a03433be5](https://linux-hardware.org/?probe=0a03433be5) | Nov 05, 2021 |
| Dell          | 09KPNV A00                  | [2ccec65f9c](https://linux-hardware.org/?probe=2ccec65f9c) | Nov 05, 2021 |
| ASUSTek       | Leonite2                    | [ba705b3f5a](https://linux-hardware.org/?probe=ba705b3f5a) | Nov 05, 2021 |
| MSI           | E350DM-E33                  | [d44e9f05c0](https://linux-hardware.org/?probe=d44e9f05c0) | Nov 04, 2021 |
| HP            | 2AA6 PVT                    | [8882e85aae](https://linux-hardware.org/?probe=8882e85aae) | Nov 04, 2021 |
| ASRock        | H310CM-HG4                  | [89e6c09611](https://linux-hardware.org/?probe=89e6c09611) | Nov 04, 2021 |
| ASRock        | H310CM-HG4                  | [a66f4a5024](https://linux-hardware.org/?probe=a66f4a5024) | Nov 04, 2021 |
| MSI           | B450M MORTAR MAX            | [80cef40751](https://linux-hardware.org/?probe=80cef40751) | Nov 04, 2021 |
| MSI           | B75MA-E33                   | [02be6a0c2c](https://linux-hardware.org/?probe=02be6a0c2c) | Nov 04, 2021 |
| Intel         | H61                         | [062b4c247d](https://linux-hardware.org/?probe=062b4c247d) | Nov 04, 2021 |
| Gigabyte      | Z270X-Gaming K5             | [443126a197](https://linux-hardware.org/?probe=443126a197) | Nov 04, 2021 |
| Gigabyte      | Z270X-Gaming K5             | [5ac710a245](https://linux-hardware.org/?probe=5ac710a245) | Nov 04, 2021 |
| ASUSTek       | P5QL-VM EPU                 | [dff36c2e91](https://linux-hardware.org/?probe=dff36c2e91) | Nov 03, 2021 |
| Dell          | 0Y2MRG A00                  | [80cfec46fc](https://linux-hardware.org/?probe=80cfec46fc) | Nov 03, 2021 |
| HP            | 1494                        | [ef0237e3cf](https://linux-hardware.org/?probe=ef0237e3cf) | Nov 03, 2021 |
| HP            | 18E4                        | [1c3ea795a0](https://linux-hardware.org/?probe=1c3ea795a0) | Nov 03, 2021 |
| HP            | 18E4                        | [4994f5c700](https://linux-hardware.org/?probe=4994f5c700) | Nov 03, 2021 |
| ASRock        | AD2700-ITX                  | [0617894ec9](https://linux-hardware.org/?probe=0617894ec9) | Nov 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [b89c97fac7](https://linux-hardware.org/?probe=b89c97fac7) | Nov 03, 2021 |
| Lenovo        | ThinkCentre M81 5049W16     | [1deda52bc2](https://linux-hardware.org/?probe=1deda52bc2) | Nov 03, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [fab384dadb](https://linux-hardware.org/?probe=fab384dadb) | Nov 03, 2021 |
| Dell          | 09KPNV A00                  | [36cb1f25d5](https://linux-hardware.org/?probe=36cb1f25d5) | Nov 03, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [8003a5853a](https://linux-hardware.org/?probe=8003a5853a) | Nov 03, 2021 |
| ASUSTek       | Z87-A                       | [d7cfe9c421](https://linux-hardware.org/?probe=d7cfe9c421) | Nov 03, 2021 |
| HP            | 1998                        | [5f464b262a](https://linux-hardware.org/?probe=5f464b262a) | Nov 02, 2021 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [3215c2037d](https://linux-hardware.org/?probe=3215c2037d) | Nov 02, 2021 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [e58e6144bf](https://linux-hardware.org/?probe=e58e6144bf) | Nov 02, 2021 |
| Acer          | Revo RN86                   | [ea82197a5a](https://linux-hardware.org/?probe=ea82197a5a) | Nov 02, 2021 |
| Acer          | Revo RN86                   | [99474dda25](https://linux-hardware.org/?probe=99474dda25) | Nov 02, 2021 |
| HP            | 2AA6 PVT                    | [6e3e85588f](https://linux-hardware.org/?probe=6e3e85588f) | Nov 02, 2021 |
| ASRock        | Z87M Extreme4               | [bf72ad4c7b](https://linux-hardware.org/?probe=bf72ad4c7b) | Nov 02, 2021 |
| ASUSTek       | PRO A320M-R WI-FI           | [a84ed9f4fc](https://linux-hardware.org/?probe=a84ed9f4fc) | Nov 02, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [e96cd29d28](https://linux-hardware.org/?probe=e96cd29d28) | Nov 02, 2021 |
| ASUSTek       | PRIME H310M-K               | [a6cafee332](https://linux-hardware.org/?probe=a6cafee332) | Nov 02, 2021 |
| ASUSTek       | A68HM-PLUS                  | [7c916be07e](https://linux-hardware.org/?probe=7c916be07e) | Nov 02, 2021 |
| ECS           | H61H2-M6                    | [703edac8b2](https://linux-hardware.org/?probe=703edac8b2) | Nov 02, 2021 |
| Gigabyte      | GA-78LMT-S2P                | [209a1faa74](https://linux-hardware.org/?probe=209a1faa74) | Nov 02, 2021 |
| MSI           | B250 GAMING M3              | [0d30aebcbf](https://linux-hardware.org/?probe=0d30aebcbf) | Nov 01, 2021 |
| ASUSTek       | PRIME B550M-A               | [68e47ae715](https://linux-hardware.org/?probe=68e47ae715) | Nov 01, 2021 |
| ASUSTek       | M5A97 R2.0                  | [f6efac325c](https://linux-hardware.org/?probe=f6efac325c) | Nov 01, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [c9e815f4f5](https://linux-hardware.org/?probe=c9e815f4f5) | Nov 01, 2021 |
| Shuttle       | XH410G                      | [5c0347ade8](https://linux-hardware.org/?probe=5c0347ade8) | Nov 01, 2021 |
| Foxconn       | H61MXV/H67MXV               | [01a3346d88](https://linux-hardware.org/?probe=01a3346d88) | Nov 01, 2021 |
| HP            | 1497                        | [c0fb875ca5](https://linux-hardware.org/?probe=c0fb875ca5) | Oct 31, 2021 |
| ASUSTek       | M2N68-AM SE2                | [324f6e5fad](https://linux-hardware.org/?probe=324f6e5fad) | Oct 31, 2021 |
| ASUSTek       | M2N68-AM SE2                | [a6574237d6](https://linux-hardware.org/?probe=a6574237d6) | Oct 31, 2021 |
| MSI           | 970 GAMING                  | [dec7ac6a34](https://linux-hardware.org/?probe=dec7ac6a34) | Oct 31, 2021 |
| HP            | 3031h                       | [d05cca1a32](https://linux-hardware.org/?probe=d05cca1a32) | Oct 31, 2021 |
| ASRock        | B450 Steel Legend           | [93825976f1](https://linux-hardware.org/?probe=93825976f1) | Oct 31, 2021 |
| HP            | 3031h                       | [e163c2a2d3](https://linux-hardware.org/?probe=e163c2a2d3) | Oct 31, 2021 |
| ASUSTek       | P6T DELUXE                  | [6c7ecc284b](https://linux-hardware.org/?probe=6c7ecc284b) | Oct 31, 2021 |
| HP            | 3031h                       | [513927ecf6](https://linux-hardware.org/?probe=513927ecf6) | Oct 31, 2021 |
| ASUSTek       | P6T DELUXE                  | [f35cfefa93](https://linux-hardware.org/?probe=f35cfefa93) | Oct 31, 2021 |
| Gigabyte      | H97M-D3H                    | [5ead0ca3ad](https://linux-hardware.org/?probe=5ead0ca3ad) | Oct 31, 2021 |
| Gigabyte      | H97M-D3H                    | [ef99fc6a0f](https://linux-hardware.org/?probe=ef99fc6a0f) | Oct 31, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a525c8911b](https://linux-hardware.org/?probe=a525c8911b) | Oct 31, 2021 |
| Gigabyte      | H97-D3H-CF                  | [ce787d81ef](https://linux-hardware.org/?probe=ce787d81ef) | Oct 31, 2021 |
| ASRock        | Z77 Extreme6                | [c5e2e9e4a4](https://linux-hardware.org/?probe=c5e2e9e4a4) | Oct 31, 2021 |
| LattePanda    | Alpha                       | [b5bd43e606](https://linux-hardware.org/?probe=b5bd43e606) | Oct 31, 2021 |
| Intel         | DH77EB AAG39073-304         | [34353c5c01](https://linux-hardware.org/?probe=34353c5c01) | Oct 30, 2021 |
| Dell          | 0HY9JP A02                  | [c5719c54c2](https://linux-hardware.org/?probe=c5719c54c2) | Oct 30, 2021 |
| Intel         | DH77EB AAG39073-304         | [68530fd616](https://linux-hardware.org/?probe=68530fd616) | Oct 30, 2021 |
| MSI           | Z170-A PRO                  | [ecaaa3b66a](https://linux-hardware.org/?probe=ecaaa3b66a) | Oct 30, 2021 |
| Dell          | 08WKV3 A00                  | [827cb9a77a](https://linux-hardware.org/?probe=827cb9a77a) | Oct 30, 2021 |
| Dell          | 07T4MC A06                  | [29f013d2e2](https://linux-hardware.org/?probe=29f013d2e2) | Oct 30, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [d397a37935](https://linux-hardware.org/?probe=d397a37935) | Oct 30, 2021 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [9bd1a96f2e](https://linux-hardware.org/?probe=9bd1a96f2e) | Oct 30, 2021 |
| Unknown       | Unknown                     | [eecc1408e7](https://linux-hardware.org/?probe=eecc1408e7) | Oct 29, 2021 |
| Gigabyte      | GA-78LMT-S2                 | [9cf8898973](https://linux-hardware.org/?probe=9cf8898973) | Oct 29, 2021 |
| ASUSTek       | H110M-R                     | [07067fe66c](https://linux-hardware.org/?probe=07067fe66c) | Oct 29, 2021 |
| ASUSTek       | H61M-K                      | [f31e6e3dd0](https://linux-hardware.org/?probe=f31e6e3dd0) | Oct 29, 2021 |
| Lenovo        | ThinkCentre M81 5049W16     | [3e625a72d2](https://linux-hardware.org/?probe=3e625a72d2) | Oct 29, 2021 |
| HP            | 1998                        | [f943d839a8](https://linux-hardware.org/?probe=f943d839a8) | Oct 29, 2021 |
| ASUSTek       | B150M-ET M2 SERIES          | [eb594b6eb5](https://linux-hardware.org/?probe=eb594b6eb5) | Oct 29, 2021 |
| ASUSTek       | M2N-SLI                     | [c31d447213](https://linux-hardware.org/?probe=c31d447213) | Oct 29, 2021 |
| Intel         | H61                         | [89c4e2a423](https://linux-hardware.org/?probe=89c4e2a423) | Oct 29, 2021 |
| HP            | 843C                        | [7546295df0](https://linux-hardware.org/?probe=7546295df0) | Oct 29, 2021 |
| Digitron      | G31T-M7                     | [8e02bb30bc](https://linux-hardware.org/?probe=8e02bb30bc) | Oct 29, 2021 |
| ASUSTek       | TUF Z270 MARK 1             | [f60a34fe5c](https://linux-hardware.org/?probe=f60a34fe5c) | Oct 28, 2021 |
| Gigabyte      | G41M-Combo                  | [a9908463d8](https://linux-hardware.org/?probe=a9908463d8) | Oct 28, 2021 |
| ASUSTek       | M11BB                       | [c049f2b753](https://linux-hardware.org/?probe=c049f2b753) | Oct 28, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [3f12d034e3](https://linux-hardware.org/?probe=3f12d034e3) | Oct 28, 2021 |
| HP            | 3647h                       | [2db1dbef9f](https://linux-hardware.org/?probe=2db1dbef9f) | Oct 28, 2021 |
| T-bao         | MINI PC V1.0                | [72ce248d0c](https://linux-hardware.org/?probe=72ce248d0c) | Oct 28, 2021 |
| HP            | 8643 SMVB                   | [ad0e1a0525](https://linux-hardware.org/?probe=ad0e1a0525) | Oct 28, 2021 |
| ASRock        | G31M-GS                     | [17892fbf03](https://linux-hardware.org/?probe=17892fbf03) | Oct 27, 2021 |
| ASRock        | G31M-GS                     | [25e9cd546b](https://linux-hardware.org/?probe=25e9cd546b) | Oct 27, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [e22ee33fef](https://linux-hardware.org/?probe=e22ee33fef) | Oct 27, 2021 |
| Dell          | 06X1TJ A00                  | [511c376041](https://linux-hardware.org/?probe=511c376041) | Oct 27, 2021 |
| Dell          | 07T4MC A11                  | [219a3a234f](https://linux-hardware.org/?probe=219a3a234f) | Oct 27, 2021 |
| Dell          | 07T4MC A11                  | [870145802c](https://linux-hardware.org/?probe=870145802c) | Oct 27, 2021 |
| HP            | 0AA8h                       | [a7dab352d6](https://linux-hardware.org/?probe=a7dab352d6) | Oct 27, 2021 |
| Gigabyte      | G41M-ES2L                   | [24d7bb4df6](https://linux-hardware.org/?probe=24d7bb4df6) | Oct 27, 2021 |
| ASRock        | P67 Pro3                    | [8753243650](https://linux-hardware.org/?probe=8753243650) | Oct 27, 2021 |
| Chuwi         | LarkBox                     | [d2611bc564](https://linux-hardware.org/?probe=d2611bc564) | Oct 27, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [6b0a992d9f](https://linux-hardware.org/?probe=6b0a992d9f) | Oct 26, 2021 |
| MSI           | 970 GAMING                  | [83563b491a](https://linux-hardware.org/?probe=83563b491a) | Oct 26, 2021 |
| Gigabyte      | 970A-DS3P                   | [c62f9b7a28](https://linux-hardware.org/?probe=c62f9b7a28) | Oct 26, 2021 |
| Lenovo        | ThinkCentre M81 5049W16     | [038ebc8704](https://linux-hardware.org/?probe=038ebc8704) | Oct 26, 2021 |
| Gigabyte      | F2A68HM-H                   | [2aed57accc](https://linux-hardware.org/?probe=2aed57accc) | Oct 26, 2021 |
| ASRock        | A320M-ITX                   | [44d0559b06](https://linux-hardware.org/?probe=44d0559b06) | Oct 26, 2021 |
| ASRock        | B450 Steel Legend           | [ea4655d2bb](https://linux-hardware.org/?probe=ea4655d2bb) | Oct 26, 2021 |
| Intel         | H55                         | [1b80ff1b5a](https://linux-hardware.org/?probe=1b80ff1b5a) | Oct 26, 2021 |
| Dell          | 0D441T A01                  | [51d64c0798](https://linux-hardware.org/?probe=51d64c0798) | Oct 26, 2021 |
| Dell          | 06X1TJ A00                  | [c0591f85ca](https://linux-hardware.org/?probe=c0591f85ca) | Oct 26, 2021 |
| Gigabyte      | 945GZM-S2                   | [f00a0a0903](https://linux-hardware.org/?probe=f00a0a0903) | Oct 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | [3c2298ba3b](https://linux-hardware.org/?probe=3c2298ba3b) | Oct 26, 2021 |
| MSI           | Z370M MORTAR                | [0e04954917](https://linux-hardware.org/?probe=0e04954917) | Oct 26, 2021 |
| MSI           | Z68A-GD55                   | [e83f9dcbbc](https://linux-hardware.org/?probe=e83f9dcbbc) | Oct 25, 2021 |
| ASRock        | P67 Pro3                    | [547cf0429d](https://linux-hardware.org/?probe=547cf0429d) | Oct 25, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [1229314f25](https://linux-hardware.org/?probe=1229314f25) | Oct 25, 2021 |
| ASRock        | 960GM-GS3 FX                | [5ac667365b](https://linux-hardware.org/?probe=5ac667365b) | Oct 25, 2021 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [47565a4690](https://linux-hardware.org/?probe=47565a4690) | Oct 25, 2021 |
| ASRock        | 960GM-GS3 FX                | [846f30af88](https://linux-hardware.org/?probe=846f30af88) | Oct 25, 2021 |
| Unknown       | K8M800-8237                 | [91468b399e](https://linux-hardware.org/?probe=91468b399e) | Oct 25, 2021 |
| Alienware     | 0VDT73 A00                  | [9cce6740be](https://linux-hardware.org/?probe=9cce6740be) | Oct 25, 2021 |
| ASRock        | 970M Pro3                   | [b6aaef26c3](https://linux-hardware.org/?probe=b6aaef26c3) | Oct 25, 2021 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [b72010e565](https://linux-hardware.org/?probe=b72010e565) | Oct 25, 2021 |
| HP            | 1850                        | [b155e888a5](https://linux-hardware.org/?probe=b155e888a5) | Oct 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [cee7d17aff](https://linux-hardware.org/?probe=cee7d17aff) | Oct 24, 2021 |
| Gigabyte      | GA-870A-UD3                 | [b2cbbc04b8](https://linux-hardware.org/?probe=b2cbbc04b8) | Oct 24, 2021 |
| Pegatron      | 2AB5                        | [d19235c3d0](https://linux-hardware.org/?probe=d19235c3d0) | Oct 24, 2021 |
| Dell          | 0T10XW A01                  | [47f345e24c](https://linux-hardware.org/?probe=47f345e24c) | Oct 24, 2021 |
| ASUSTek       | PRIME X570-P                | [f66b710a8a](https://linux-hardware.org/?probe=f66b710a8a) | Oct 24, 2021 |
| ASUSTek       | PRIME A520M-K               | [90283063c6](https://linux-hardware.org/?probe=90283063c6) | Oct 23, 2021 |
| ASUSTek       | A78M-A                      | [33d5096a54](https://linux-hardware.org/?probe=33d5096a54) | Oct 23, 2021 |
| ASUSTek       | PRIME B550M-K               | [d9c192ea8c](https://linux-hardware.org/?probe=d9c192ea8c) | Oct 23, 2021 |
| Dell          | 0H0P0M A00                  | [6f2f7d7453](https://linux-hardware.org/?probe=6f2f7d7453) | Oct 23, 2021 |
| ASRock        | 960GM-GS3 FX                | [195f1a80ee](https://linux-hardware.org/?probe=195f1a80ee) | Oct 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [b8967bd2fd](https://linux-hardware.org/?probe=b8967bd2fd) | Oct 23, 2021 |
| MSI           | 970 GAMING                  | [40e6e0ad76](https://linux-hardware.org/?probe=40e6e0ad76) | Oct 23, 2021 |
| MSI           | 970 GAMING                  | [741eb299dd](https://linux-hardware.org/?probe=741eb299dd) | Oct 23, 2021 |
| MSI           | Z370M MORTAR                | [17fc87f74a](https://linux-hardware.org/?probe=17fc87f74a) | Oct 23, 2021 |
| ASUSTek       | B85M-E                      | [7a6479dc2d](https://linux-hardware.org/?probe=7a6479dc2d) | Oct 23, 2021 |
| Dell          | 0K240Y A01                  | [cc3925f2e7](https://linux-hardware.org/?probe=cc3925f2e7) | Oct 22, 2021 |
| MSI           | B450M PRO-M2 MAX            | [61823fb44e](https://linux-hardware.org/?probe=61823fb44e) | Oct 22, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [545dc9a3e0](https://linux-hardware.org/?probe=545dc9a3e0) | Oct 22, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [6616fe6bb8](https://linux-hardware.org/?probe=6616fe6bb8) | Oct 22, 2021 |
| ASRock        | B450 Steel Legend           | [97cc5e8b11](https://linux-hardware.org/?probe=97cc5e8b11) | Oct 22, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [3f67c7622c](https://linux-hardware.org/?probe=3f67c7622c) | Oct 22, 2021 |
| ASUSTek       | P8Z77-M                     | [5e8e54739e](https://linux-hardware.org/?probe=5e8e54739e) | Oct 22, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [a5026c4013](https://linux-hardware.org/?probe=a5026c4013) | Oct 21, 2021 |
| Intel         | H61                         | [2e8854724e](https://linux-hardware.org/?probe=2e8854724e) | Oct 21, 2021 |
| Dell          | 0NC2VH A01                  | [6ced4f2897](https://linux-hardware.org/?probe=6ced4f2897) | Oct 21, 2021 |
| Lenovo        | ThinkCentre M81 5049W16     | [3ebbe97800](https://linux-hardware.org/?probe=3ebbe97800) | Oct 21, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [2edb67185b](https://linux-hardware.org/?probe=2edb67185b) | Oct 21, 2021 |
| ASRock        | 960GM-GS3 FX                | [9859c22ab8](https://linux-hardware.org/?probe=9859c22ab8) | Oct 21, 2021 |
| Pegatron      | 2AC3                        | [ae8b02d9cb](https://linux-hardware.org/?probe=ae8b02d9cb) | Oct 21, 2021 |
| ASUSTek       | P8Z77-M                     | [407fede3b4](https://linux-hardware.org/?probe=407fede3b4) | Oct 21, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | [e1ddc26c5e](https://linux-hardware.org/?probe=e1ddc26c5e) | Oct 20, 2021 |
| ASUSTek       | PRIME Z270-A                | [a11d4b7c50](https://linux-hardware.org/?probe=a11d4b7c50) | Oct 20, 2021 |
| ASUSTek       | M4N68T-M LE                 | [632f3122a2](https://linux-hardware.org/?probe=632f3122a2) | Oct 20, 2021 |
| Medion        | MS-7728                     | [d730ac701f](https://linux-hardware.org/?probe=d730ac701f) | Oct 19, 2021 |
| ASUSTek       | P8Z77-V                     | [e59d042da2](https://linux-hardware.org/?probe=e59d042da2) | Oct 19, 2021 |
| ASUSTek       | PRIME B550M-A               | [2e377185b9](https://linux-hardware.org/?probe=2e377185b9) | Oct 19, 2021 |
| ASUSTek       | ET2700I                     | [8dfd1c0952](https://linux-hardware.org/?probe=8dfd1c0952) | Oct 19, 2021 |
| ASRock        | B450M Pro4                  | [89569de968](https://linux-hardware.org/?probe=89569de968) | Oct 19, 2021 |
| MSI           | Z370M MORTAR                | [6c4dcb717b](https://linux-hardware.org/?probe=6c4dcb717b) | Oct 19, 2021 |
| HP            | 8643 SMVB                   | [ebe220fdf9](https://linux-hardware.org/?probe=ebe220fdf9) | Oct 19, 2021 |
| Pegatron      | 2A94h                       | [ebd6264587](https://linux-hardware.org/?probe=ebd6264587) | Oct 19, 2021 |
| MSI           | H97M-G43                    | [035fce3bfc](https://linux-hardware.org/?probe=035fce3bfc) | Oct 19, 2021 |
| Dell          | 0T10XW A01                  | [ee63195587](https://linux-hardware.org/?probe=ee63195587) | Oct 18, 2021 |
| ASUSTek       | ET2700I                     | [ca5500d384](https://linux-hardware.org/?probe=ca5500d384) | Oct 18, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [a2d8cc587d](https://linux-hardware.org/?probe=a2d8cc587d) | Oct 18, 2021 |
| Gigabyte      | GA-7VT600                   | [ca657531e4](https://linux-hardware.org/?probe=ca657531e4) | Oct 18, 2021 |
| MSI           | Z590-A PRO                  | [d8a7a695ae](https://linux-hardware.org/?probe=d8a7a695ae) | Oct 18, 2021 |
| ASUSTek       | A88XM-E                     | [82894be7a8](https://linux-hardware.org/?probe=82894be7a8) | Oct 18, 2021 |
| MSI           | MS-7255 V2.0                | [c61d7b8758](https://linux-hardware.org/?probe=c61d7b8758) | Oct 17, 2021 |
| ASRock        | B450M Pro4                  | [20c432ef7d](https://linux-hardware.org/?probe=20c432ef7d) | Oct 17, 2021 |
| Gigabyte      | B450M DS3H-CF               | [a33e68304f](https://linux-hardware.org/?probe=a33e68304f) | Oct 17, 2021 |
| Intel         | DG33BU AAD90159-403         | [a5121e1871](https://linux-hardware.org/?probe=a5121e1871) | Oct 17, 2021 |
| Gigabyte      | H55M-USB3                   | [4f5274c16a](https://linux-hardware.org/?probe=4f5274c16a) | Oct 17, 2021 |
| ASRock        | X399 Taichi Threadripper... | [8ef7556453](https://linux-hardware.org/?probe=8ef7556453) | Oct 17, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [14acfd829d](https://linux-hardware.org/?probe=14acfd829d) | Oct 17, 2021 |
| ASUSTek       | PRIME Z390-A                | [c0c2de7d52](https://linux-hardware.org/?probe=c0c2de7d52) | Oct 17, 2021 |
| Dell          | 0WMJ54 A01                  | [088da5f604](https://linux-hardware.org/?probe=088da5f604) | Oct 17, 2021 |
| Unknown       | Unknown                     | [7a2742f439](https://linux-hardware.org/?probe=7a2742f439) | Oct 17, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [3539f57219](https://linux-hardware.org/?probe=3539f57219) | Oct 17, 2021 |
| MSI           | B85M GAMING                 | [55468e657e](https://linux-hardware.org/?probe=55468e657e) | Oct 16, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [3d33db8116](https://linux-hardware.org/?probe=3d33db8116) | Oct 16, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [45d9e322ba](https://linux-hardware.org/?probe=45d9e322ba) | Oct 16, 2021 |
| Gateway       | H57M01                      | [fda18dabd0](https://linux-hardware.org/?probe=fda18dabd0) | Oct 16, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [d56594096c](https://linux-hardware.org/?probe=d56594096c) | Oct 16, 2021 |
| Dell          | 0XPDFK A01                  | [0e66d5fd62](https://linux-hardware.org/?probe=0e66d5fd62) | Oct 16, 2021 |
| Biostar       | P4M90-M7A Ver:1.0           | [d8875918ac](https://linux-hardware.org/?probe=d8875918ac) | Oct 16, 2021 |
| Medion        | MS-7707                     | [26b6148847](https://linux-hardware.org/?probe=26b6148847) | Oct 16, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [29575a20e2](https://linux-hardware.org/?probe=29575a20e2) | Oct 16, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [56f27fef6e](https://linux-hardware.org/?probe=56f27fef6e) | Oct 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [d890edb314](https://linux-hardware.org/?probe=d890edb314) | Oct 16, 2021 |
| HP            | 3397                        | [bf9875c5ac](https://linux-hardware.org/?probe=bf9875c5ac) | Oct 16, 2021 |
| HP            | 2AF7                        | [866165c6b2](https://linux-hardware.org/?probe=866165c6b2) | Oct 16, 2021 |
| Dell          | 0YXG0N A00                  | [26f4f12047](https://linux-hardware.org/?probe=26f4f12047) | Oct 16, 2021 |
| Foxconn       | TPS01                       | [a967246bfb](https://linux-hardware.org/?probe=a967246bfb) | Oct 16, 2021 |
| BESSTAR Te... | HM80                        | [49e132f4e1](https://linux-hardware.org/?probe=49e132f4e1) | Oct 16, 2021 |
| Gigabyte      | H61M-USB3V                  | [37a0658b60](https://linux-hardware.org/?probe=37a0658b60) | Oct 15, 2021 |
| Fujitsu Si... | G31T-M2 V3.02               | [dbe58885fe](https://linux-hardware.org/?probe=dbe58885fe) | Oct 15, 2021 |
| Fujitsu Si... | G31T-M2 V3.02               | [9c93f71903](https://linux-hardware.org/?probe=9c93f71903) | Oct 15, 2021 |
| Gigabyte      | G31M-ES2L                   | [9d1380f4a8](https://linux-hardware.org/?probe=9d1380f4a8) | Oct 15, 2021 |
| ASUSTek       | P5B-Deluxe                  | [a402bb261d](https://linux-hardware.org/?probe=a402bb261d) | Oct 15, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [4e0a74e0b9](https://linux-hardware.org/?probe=4e0a74e0b9) | Oct 15, 2021 |
| ASRock        | B450 Steel Legend           | [a293f4afb7](https://linux-hardware.org/?probe=a293f4afb7) | Oct 15, 2021 |
| HP            | 8643 SMVB                   | [a2b6b46a74](https://linux-hardware.org/?probe=a2b6b46a74) | Oct 15, 2021 |
| ASUSTek       | P8H61-M LE/CSM              | [4f5c2e2452](https://linux-hardware.org/?probe=4f5c2e2452) | Oct 15, 2021 |
| Unknown       | X79-P3                      | [a6e06b8cba](https://linux-hardware.org/?probe=a6e06b8cba) | Oct 15, 2021 |
| HP            | 3047h                       | [f66ec61e22](https://linux-hardware.org/?probe=f66ec61e22) | Oct 14, 2021 |
| Supermicro    | X7SPA-HF                    | [c7c31f9bcf](https://linux-hardware.org/?probe=c7c31f9bcf) | Oct 14, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [8e58600b6e](https://linux-hardware.org/?probe=8e58600b6e) | Oct 14, 2021 |
| Intel         | H61                         | [3f8d650142](https://linux-hardware.org/?probe=3f8d650142) | Oct 14, 2021 |
| Foxconn       | Napa HP P/N                 | [bdafb97364](https://linux-hardware.org/?probe=bdafb97364) | Oct 13, 2021 |
| ASUSTek       | Z97-P                       | [9343a7aac0](https://linux-hardware.org/?probe=9343a7aac0) | Oct 13, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [c12b538080](https://linux-hardware.org/?probe=c12b538080) | Oct 13, 2021 |
| Dell          | 0GY6Y8 A03                  | [2d3f5cc3d7](https://linux-hardware.org/?probe=2d3f5cc3d7) | Oct 13, 2021 |
| ASUSTek       | M2N-E                       | [7fd3ba10d1](https://linux-hardware.org/?probe=7fd3ba10d1) | Oct 12, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [d04ee85760](https://linux-hardware.org/?probe=d04ee85760) | Oct 12, 2021 |
| MSI           | 2AE0                        | [eb0924e07d](https://linux-hardware.org/?probe=eb0924e07d) | Oct 12, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [5964c48c2c](https://linux-hardware.org/?probe=5964c48c2c) | Oct 12, 2021 |
| MSI           | 2AE0                        | [e39aeb8c18](https://linux-hardware.org/?probe=e39aeb8c18) | Oct 12, 2021 |
| Medion        | MS-7633                     | [cb93382ea0](https://linux-hardware.org/?probe=cb93382ea0) | Oct 12, 2021 |
| MSI           | H97M-G43                    | [1bff3500a0](https://linux-hardware.org/?probe=1bff3500a0) | Oct 12, 2021 |
| ASRock        | 970 Extreme4                | [bfb643459a](https://linux-hardware.org/?probe=bfb643459a) | Oct 12, 2021 |
| MSI           | H97M-G43                    | [ccfb78add4](https://linux-hardware.org/?probe=ccfb78add4) | Oct 12, 2021 |
| Dell          | 0WR7PY A02                  | [8e43745e55](https://linux-hardware.org/?probe=8e43745e55) | Oct 12, 2021 |
| Dell          | 0WR7PY A02                  | [f0f228eff1](https://linux-hardware.org/?probe=f0f228eff1) | Oct 12, 2021 |
| HP            | 0B4Ch D                     | [d0b6443f5b](https://linux-hardware.org/?probe=d0b6443f5b) | Oct 12, 2021 |
| ASRock        | Z370 Gaming K6              | [3f995fd287](https://linux-hardware.org/?probe=3f995fd287) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [694de952d2](https://linux-hardware.org/?probe=694de952d2) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [91ba591940](https://linux-hardware.org/?probe=91ba591940) | Oct 12, 2021 |
| MSI           | Z68A-GD55                   | [5b86b40d43](https://linux-hardware.org/?probe=5b86b40d43) | Oct 11, 2021 |
| ASRock        | B450 Steel Legend           | [8957fd618b](https://linux-hardware.org/?probe=8957fd618b) | Oct 11, 2021 |
| HP            | 18E5                        | [6859bb4250](https://linux-hardware.org/?probe=6859bb4250) | Oct 11, 2021 |
| MSI           | 970 GAMING                  | [ab5ccb23b0](https://linux-hardware.org/?probe=ab5ccb23b0) | Oct 11, 2021 |
| ASRock        | 960GC-GS FX                 | [437c7ad805](https://linux-hardware.org/?probe=437c7ad805) | Oct 11, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [38c3e21767](https://linux-hardware.org/?probe=38c3e21767) | Oct 11, 2021 |
| ASUSTek       | M4A87TD EVO                 | [b2aa6b2d66](https://linux-hardware.org/?probe=b2aa6b2d66) | Oct 11, 2021 |
| Gigabyte      | GA-870A-UD3                 | [f781849677](https://linux-hardware.org/?probe=f781849677) | Oct 11, 2021 |
| MSI           | B75MA-P45                   | [a6aa274e8b](https://linux-hardware.org/?probe=a6aa274e8b) | Oct 10, 2021 |
| MSI           | B75MA-P45                   | [eb810bdb07](https://linux-hardware.org/?probe=eb810bdb07) | Oct 10, 2021 |
| ASUSTek       | AM1I-A                      | [b624e54271](https://linux-hardware.org/?probe=b624e54271) | Oct 10, 2021 |
| Dell          | 0PU052                      | [42be865dc0](https://linux-hardware.org/?probe=42be865dc0) | Oct 10, 2021 |
| Dell          | 0PU052                      | [ec8f46ab8b](https://linux-hardware.org/?probe=ec8f46ab8b) | Oct 10, 2021 |
| Biostar       | X470NH                      | [c42f6e5103](https://linux-hardware.org/?probe=c42f6e5103) | Oct 10, 2021 |
| Pegatron      | 2AB5                        | [db6e8fe547](https://linux-hardware.org/?probe=db6e8fe547) | Oct 10, 2021 |
| ASRock        | X300M-STX                   | [6ec6ce5c81](https://linux-hardware.org/?probe=6ec6ce5c81) | Oct 10, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [c9ef1c033f](https://linux-hardware.org/?probe=c9ef1c033f) | Oct 09, 2021 |
| ASRock        | J3455B-ITX                  | [9fd17a6579](https://linux-hardware.org/?probe=9fd17a6579) | Oct 09, 2021 |
| ASRock        | J3455B-ITX                  | [9b4b3c9f77](https://linux-hardware.org/?probe=9b4b3c9f77) | Oct 09, 2021 |
| Intel         | DQ77KB AAG81483-500         | [e686032cff](https://linux-hardware.org/?probe=e686032cff) | Oct 09, 2021 |
| Intel         | DQ77KB AAG81483-500         | [0705a7ff76](https://linux-hardware.org/?probe=0705a7ff76) | Oct 09, 2021 |
| MSI           | 760GM-P23                   | [fba59c709d](https://linux-hardware.org/?probe=fba59c709d) | Oct 09, 2021 |
| HP            | 18E7                        | [9ee94408e4](https://linux-hardware.org/?probe=9ee94408e4) | Oct 09, 2021 |
| ASUSTek       | PRIME H410M-K               | [67ba4012a3](https://linux-hardware.org/?probe=67ba4012a3) | Oct 09, 2021 |
| MSI           | B150M PRO-VDH               | [da329b10c9](https://linux-hardware.org/?probe=da329b10c9) | Oct 08, 2021 |
| MSI           | B150M PRO-VDH               | [13f8e82e6a](https://linux-hardware.org/?probe=13f8e82e6a) | Oct 08, 2021 |
| Dell          | 03NVJ6 A03                  | [a85d258107](https://linux-hardware.org/?probe=a85d258107) | Oct 08, 2021 |
| ASUSTek       | P8P67                       | [271ce3048a](https://linux-hardware.org/?probe=271ce3048a) | Oct 08, 2021 |
| ASRock        | 970 Pro3 R2.0               | [4d11543637](https://linux-hardware.org/?probe=4d11543637) | Oct 08, 2021 |
| Gigabyte      | X170-Extreme ECC            | [c67b0490d7](https://linux-hardware.org/?probe=c67b0490d7) | Oct 08, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [d91c23c12c](https://linux-hardware.org/?probe=d91c23c12c) | Oct 08, 2021 |
| ASRock        | FM2A55M-HD+ R2.0            | [2bc0b62213](https://linux-hardware.org/?probe=2bc0b62213) | Oct 08, 2021 |
| ASRock        | 970 Extreme4                | [bcd6396d8e](https://linux-hardware.org/?probe=bcd6396d8e) | Oct 08, 2021 |
| Shuttle       | SX50 V10                    | [8547733d58](https://linux-hardware.org/?probe=8547733d58) | Oct 08, 2021 |
| ASUSTek       | M4N78-AM                    | [9005621271](https://linux-hardware.org/?probe=9005621271) | Oct 08, 2021 |
| HP            | 83E9                        | [7964501ca5](https://linux-hardware.org/?probe=7964501ca5) | Oct 08, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [665206cf21](https://linux-hardware.org/?probe=665206cf21) | Oct 08, 2021 |
| Dell          | 096JG8 A01                  | [92f15aeb4d](https://linux-hardware.org/?probe=92f15aeb4d) | Oct 08, 2021 |
| Dell          | 0J3C2F A00                  | [5792e30787](https://linux-hardware.org/?probe=5792e30787) | Oct 07, 2021 |
| ASUSTek       | PRIME B550M-A               | [c84e12c553](https://linux-hardware.org/?probe=c84e12c553) | Oct 07, 2021 |
| MSI           | H81M-E34                    | [701aaa6b36](https://linux-hardware.org/?probe=701aaa6b36) | Oct 07, 2021 |
| MSI           | 970 GAMING                  | [82eb1c0341](https://linux-hardware.org/?probe=82eb1c0341) | Oct 07, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [0a88ff958d](https://linux-hardware.org/?probe=0a88ff958d) | Oct 07, 2021 |
| ASUSTek       | H81M-A                      | [b73e4dc969](https://linux-hardware.org/?probe=b73e4dc969) | Oct 07, 2021 |
| Intel         | DG31PR AAE58249-301         | [231505c0b0](https://linux-hardware.org/?probe=231505c0b0) | Oct 07, 2021 |
| ASUSTek       | PRIME B550M-K               | [d034cd0b4a](https://linux-hardware.org/?probe=d034cd0b4a) | Oct 07, 2021 |
| ASRock        | M3A790GXH/128M              | [98e0f3b4f7](https://linux-hardware.org/?probe=98e0f3b4f7) | Oct 06, 2021 |
| Unknown       | NF-MCP78                    | [89eef3c1a9](https://linux-hardware.org/?probe=89eef3c1a9) | Oct 06, 2021 |
| Huanan        | X79 249PC V2.2              | [06fc34a2df](https://linux-hardware.org/?probe=06fc34a2df) | Oct 06, 2021 |
| TPV-INVENT... | 2AF2 A01                    | [23e967d7f5](https://linux-hardware.org/?probe=23e967d7f5) | Oct 06, 2021 |
| ASRock        | 880GXH/USB3                 | [14d61b5241](https://linux-hardware.org/?probe=14d61b5241) | Oct 06, 2021 |
| ASUSTek       | H110M-D                     | [bdeb7627e2](https://linux-hardware.org/?probe=bdeb7627e2) | Oct 06, 2021 |
| ASRock        | 970M Pro3                   | [8e17c65da0](https://linux-hardware.org/?probe=8e17c65da0) | Oct 05, 2021 |
| HP            | 18E5                        | [60c4e27dcd](https://linux-hardware.org/?probe=60c4e27dcd) | Oct 05, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [2aa911eee8](https://linux-hardware.org/?probe=2aa911eee8) | Oct 05, 2021 |
| Huanan        | X79 249PC V2.2              | [bf8ddbe5b9](https://linux-hardware.org/?probe=bf8ddbe5b9) | Oct 05, 2021 |
| Dell          | 0GY6Y8 A03                  | [0e40ae6fde](https://linux-hardware.org/?probe=0e40ae6fde) | Oct 05, 2021 |
| MSI           | MS-7270                     | [4281e009bb](https://linux-hardware.org/?probe=4281e009bb) | Oct 05, 2021 |
| Gigabyte      | B450M DS3H-CF               | [04123e977f](https://linux-hardware.org/?probe=04123e977f) | Oct 05, 2021 |
| R-StyleCom... | MS-7395                     | [b26ee5a888](https://linux-hardware.org/?probe=b26ee5a888) | Oct 05, 2021 |
| Gigabyte      | H81M-S                      | [c5c52cc683](https://linux-hardware.org/?probe=c5c52cc683) | Oct 05, 2021 |
| HP            | 1589                        | [02326f7ee6](https://linux-hardware.org/?probe=02326f7ee6) | Oct 05, 2021 |
| Gigabyte      | P35-DS3R                    | [26844da013](https://linux-hardware.org/?probe=26844da013) | Oct 05, 2021 |
| ASUSTek       | M3N78                       | [07e2a98918](https://linux-hardware.org/?probe=07e2a98918) | Oct 05, 2021 |
| ASUSTek       | M3N78                       | [654de8bd26](https://linux-hardware.org/?probe=654de8bd26) | Oct 04, 2021 |
| HP            | 1589                        | [e2834d6df0](https://linux-hardware.org/?probe=e2834d6df0) | Oct 04, 2021 |
| MSI           | B150M PRO-VDH               | [b895ca1b63](https://linux-hardware.org/?probe=b895ca1b63) | Oct 04, 2021 |
| ASUSTek       | B85M-G                      | [3cd657a4b4](https://linux-hardware.org/?probe=3cd657a4b4) | Oct 04, 2021 |
| Lenovo        | ThinkCentre M58p 6234A1G    | [f6518ea548](https://linux-hardware.org/?probe=f6518ea548) | Oct 04, 2021 |
| Unknown       | Unknown                     | [be6cf2d704](https://linux-hardware.org/?probe=be6cf2d704) | Oct 04, 2021 |
| ASRock        | H370M-ITX/ac                | [84ef17b3a6](https://linux-hardware.org/?probe=84ef17b3a6) | Oct 04, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [f89ce83c89](https://linux-hardware.org/?probe=f89ce83c89) | Oct 04, 2021 |
| ASUSTek       | A55BM-E                     | [970153a68c](https://linux-hardware.org/?probe=970153a68c) | Oct 03, 2021 |
| Dell          | 0NGC9J A00                  | [99e8813af4](https://linux-hardware.org/?probe=99e8813af4) | Oct 03, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [cc0e35f480](https://linux-hardware.org/?probe=cc0e35f480) | Oct 03, 2021 |
| Biostar       | A68MHE                      | [672dad98b1](https://linux-hardware.org/?probe=672dad98b1) | Oct 03, 2021 |
| ASUSTek       | A88XM-PLUS                  | [9ced5db194](https://linux-hardware.org/?probe=9ced5db194) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0dbbd996c3](https://linux-hardware.org/?probe=0dbbd996c3) | Oct 03, 2021 |
| Unknown       | NF-MCP78                    | [acd7f5af32](https://linux-hardware.org/?probe=acd7f5af32) | Oct 03, 2021 |
| Biostar       | A68MHE                      | [545c387e6a](https://linux-hardware.org/?probe=545c387e6a) | Oct 03, 2021 |
| ASUSTek       | PRIME X570-P                | [5d22536356](https://linux-hardware.org/?probe=5d22536356) | Oct 03, 2021 |
| Gigabyte      | H81M-S2V                    | [ef8dfe0673](https://linux-hardware.org/?probe=ef8dfe0673) | Oct 02, 2021 |
| Lenovo        | 31900058 STD                | [5b14d08827](https://linux-hardware.org/?probe=5b14d08827) | Oct 02, 2021 |
| Acer          | Aspire TC-605               | [4aa46e7581](https://linux-hardware.org/?probe=4aa46e7581) | Oct 02, 2021 |
| Pegatron      | 2AE2                        | [0309cddc66](https://linux-hardware.org/?probe=0309cddc66) | Oct 02, 2021 |
| Gigabyte      | H310M S2H x.x               | [4f0c804d51](https://linux-hardware.org/?probe=4f0c804d51) | Oct 02, 2021 |
| ASUSTek       | P5K-VM                      | [04c2c920fe](https://linux-hardware.org/?probe=04c2c920fe) | Oct 02, 2021 |
| Gigabyte      | Z97N-WIFI                   | [1ec421714e](https://linux-hardware.org/?probe=1ec421714e) | Oct 02, 2021 |
| ASRock        | B450 Steel Legend           | [de746e220f](https://linux-hardware.org/?probe=de746e220f) | Oct 02, 2021 |
| Gigabyte      | GA-870A-UD3                 | [b469e85985](https://linux-hardware.org/?probe=b469e85985) | Oct 01, 2021 |
| ASUSTek       | PRIME A320M-K               | [14323f4223](https://linux-hardware.org/?probe=14323f4223) | Oct 01, 2021 |
| Gigabyte      | M61VME-S2                   | [51f657f344](https://linux-hardware.org/?probe=51f657f344) | Oct 01, 2021 |
| Gigabyte      | M61VME-S2                   | [a9ce018e0a](https://linux-hardware.org/?probe=a9ce018e0a) | Oct 01, 2021 |
| Acer          | RS780DV                     | [5b85dd12e6](https://linux-hardware.org/?probe=5b85dd12e6) | Oct 01, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [6caa62f0ea](https://linux-hardware.org/?probe=6caa62f0ea) | Sep 30, 2021 |
| Unknown       | Unknown                     | [7b53076230](https://linux-hardware.org/?probe=7b53076230) | Sep 30, 2021 |
| ASRock        | 970 Pro3 R2.0               | [b8751ff1d3](https://linux-hardware.org/?probe=b8751ff1d3) | Sep 30, 2021 |
| MSI           | MAG B460 TORPEDO            | [705e7c6317](https://linux-hardware.org/?probe=705e7c6317) | Sep 30, 2021 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [31837dab4e](https://linux-hardware.org/?probe=31837dab4e) | Sep 30, 2021 |
| ASUSTek       | M4N68T-M LE                 | [1abb7a2b2a](https://linux-hardware.org/?probe=1abb7a2b2a) | Sep 30, 2021 |
| Gigabyte      | GA-M56S-S3                  | [4502947e1a](https://linux-hardware.org/?probe=4502947e1a) | Sep 30, 2021 |
| HP            | 2AF7                        | [0d621f8e9a](https://linux-hardware.org/?probe=0d621f8e9a) | Sep 30, 2021 |
| HP            | 1589                        | [3aa8308f22](https://linux-hardware.org/?probe=3aa8308f22) | Sep 30, 2021 |
| HP            | 1589                        | [bb74383cbf](https://linux-hardware.org/?probe=bb74383cbf) | Sep 30, 2021 |
| Gigabyte      | M68SM-S2L                   | [9bea72de00](https://linux-hardware.org/?probe=9bea72de00) | Sep 30, 2021 |
| Gigabyte      | M68SM-S2L                   | [66d1af2e80](https://linux-hardware.org/?probe=66d1af2e80) | Sep 30, 2021 |
| HP            | 2AF7                        | [7ee724766a](https://linux-hardware.org/?probe=7ee724766a) | Sep 30, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [8aff06cd5c](https://linux-hardware.org/?probe=8aff06cd5c) | Sep 29, 2021 |
| MSI           | H61M-S20                    | [9669908158](https://linux-hardware.org/?probe=9669908158) | Sep 29, 2021 |
| ASUSTek       | P5KC                        | [c6c9f72f10](https://linux-hardware.org/?probe=c6c9f72f10) | Sep 29, 2021 |
| ASUSTek       | P5Q-PRO                     | [6e7d6bc0e7](https://linux-hardware.org/?probe=6e7d6bc0e7) | Sep 29, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [9b7ef00b29](https://linux-hardware.org/?probe=9b7ef00b29) | Sep 29, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [e48cd88acc](https://linux-hardware.org/?probe=e48cd88acc) | Sep 29, 2021 |
| Gigabyte      | P35-DS3R                    | [b5c8ba7874](https://linux-hardware.org/?probe=b5c8ba7874) | Sep 29, 2021 |
| HARDKERNEL    | ODROID-H2                   | [77e5d91462](https://linux-hardware.org/?probe=77e5d91462) | Sep 29, 2021 |
| Lenovo        | Bantry CRB 31900058 STD     | [b2e67684b4](https://linux-hardware.org/?probe=b2e67684b4) | Sep 29, 2021 |
| Pegatron      | NARRA5                      | [929e48a398](https://linux-hardware.org/?probe=929e48a398) | Sep 28, 2021 |
| Gigabyte      | A520M DS3H                  | [228b36fb26](https://linux-hardware.org/?probe=228b36fb26) | Sep 28, 2021 |
| ASUSTek       | M4N68T-M                    | [adaee7ea4e](https://linux-hardware.org/?probe=adaee7ea4e) | Sep 28, 2021 |
| MSI           | H61M-S20                    | [481ecaa854](https://linux-hardware.org/?probe=481ecaa854) | Sep 28, 2021 |
| Medion        | MS-7633                     | [ae51c1eef0](https://linux-hardware.org/?probe=ae51c1eef0) | Sep 28, 2021 |
| ASRock        | B85M-HDS                    | [e40d43f794](https://linux-hardware.org/?probe=e40d43f794) | Sep 28, 2021 |
| ASUSTek       | Maximus V FORMULA           | [59c26cd33a](https://linux-hardware.org/?probe=59c26cd33a) | Sep 28, 2021 |
| Lenovo        | Bantry CRB 31900058 STD     | [fe2e26adc3](https://linux-hardware.org/?probe=fe2e26adc3) | Sep 28, 2021 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [22853c3318](https://linux-hardware.org/?probe=22853c3318) | Sep 27, 2021 |
| HP            | 1497                        | [1d45c925f0](https://linux-hardware.org/?probe=1d45c925f0) | Sep 27, 2021 |
| HP            | 1497                        | [fcfd0c8e49](https://linux-hardware.org/?probe=fcfd0c8e49) | Sep 27, 2021 |
| Dell          | 0C2KJT A00                  | [23b6a793b8](https://linux-hardware.org/?probe=23b6a793b8) | Sep 27, 2021 |
| ASRock        | H61M-HVS                    | [66a2255f4a](https://linux-hardware.org/?probe=66a2255f4a) | Sep 27, 2021 |
| MSI           | 970 GAMING                  | [e37786e505](https://linux-hardware.org/?probe=e37786e505) | Sep 27, 2021 |
| Unknown       | Unknown                     | [e604f9120c](https://linux-hardware.org/?probe=e604f9120c) | Sep 27, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [fcb09a46a1](https://linux-hardware.org/?probe=fcb09a46a1) | Sep 27, 2021 |
| Unknown       | Unknown                     | [faf2457b94](https://linux-hardware.org/?probe=faf2457b94) | Sep 26, 2021 |
| MSI           | 970 GAMING                  | [d5cea69bf2](https://linux-hardware.org/?probe=d5cea69bf2) | Sep 26, 2021 |
| ASUSTek       | P5Q-E                       | [39df7a70f9](https://linux-hardware.org/?probe=39df7a70f9) | Sep 26, 2021 |
| ASRock        | N68C-GS FX                  | [bea6762fb6](https://linux-hardware.org/?probe=bea6762fb6) | Sep 26, 2021 |
| MSI           | Z97-G45 GAMING              | [aea6092159](https://linux-hardware.org/?probe=aea6092159) | Sep 26, 2021 |
| Lenovo        | Bantry CRB 31900058 STD     | [65e8b79de2](https://linux-hardware.org/?probe=65e8b79de2) | Sep 26, 2021 |
| Gigabyte      | F2A75M-HD2                  | [e8eb018ec4](https://linux-hardware.org/?probe=e8eb018ec4) | Sep 26, 2021 |
| Dell          | 08NPPY A00                  | [530c4bb80d](https://linux-hardware.org/?probe=530c4bb80d) | Sep 25, 2021 |
| Medion        | MS-7633                     | [a2b3bf9569](https://linux-hardware.org/?probe=a2b3bf9569) | Sep 25, 2021 |
| Biostar       | A320MH                      | [85950c5033](https://linux-hardware.org/?probe=85950c5033) | Sep 25, 2021 |
| ASUSTek       | P7P55D LE                   | [45b6a5f65a](https://linux-hardware.org/?probe=45b6a5f65a) | Sep 25, 2021 |
| Biostar       | GF8200C M2+                 | [be977291b5](https://linux-hardware.org/?probe=be977291b5) | Sep 24, 2021 |
| Gigabyte      | EX58-UD5                    | [505c585a78](https://linux-hardware.org/?probe=505c585a78) | Sep 24, 2021 |
| Lenovo        | ThinkCentre M58p 3285W2N    | [d9fae0041a](https://linux-hardware.org/?probe=d9fae0041a) | Sep 24, 2021 |
| MSI           | E350DM-E33                  | [725bc6ab87](https://linux-hardware.org/?probe=725bc6ab87) | Sep 24, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | [a9a92c303c](https://linux-hardware.org/?probe=a9a92c303c) | Sep 24, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [94b85ee028](https://linux-hardware.org/?probe=94b85ee028) | Sep 24, 2021 |
| ASRock        | X370 Gaming X               | [dc795d4f04](https://linux-hardware.org/?probe=dc795d4f04) | Sep 24, 2021 |
| ASUSTek       | PRIME B550M-K               | [b30800b2f9](https://linux-hardware.org/?probe=b30800b2f9) | Sep 24, 2021 |
| Lenovo        | Bantry CRB 31900058 STD     | [c6b6503f6e](https://linux-hardware.org/?probe=c6b6503f6e) | Sep 24, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [9e6acff67b](https://linux-hardware.org/?probe=9e6acff67b) | Sep 24, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [b7498ef12c](https://linux-hardware.org/?probe=b7498ef12c) | Sep 24, 2021 |
| ASUSTek       | PRIME B360M-A               | [b0e29d55a7](https://linux-hardware.org/?probe=b0e29d55a7) | Sep 23, 2021 |
| Gigabyte      | GA-MA770-UD3                | [1db3640529](https://linux-hardware.org/?probe=1db3640529) | Sep 23, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [03b0290469](https://linux-hardware.org/?probe=03b0290469) | Sep 23, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [b4cf3f9692](https://linux-hardware.org/?probe=b4cf3f9692) | Sep 23, 2021 |
| HP            | 3397                        | [a5cffbed73](https://linux-hardware.org/?probe=a5cffbed73) | Sep 23, 2021 |
| ASUSTek       | P8H67-V                     | [ddb22c91d8](https://linux-hardware.org/?probe=ddb22c91d8) | Sep 23, 2021 |
| Pegatron      | Benicia                     | [79f76a3ae8](https://linux-hardware.org/?probe=79f76a3ae8) | Sep 23, 2021 |
| Dell          | 0GXM1W A01                  | [59f9ea6e64](https://linux-hardware.org/?probe=59f9ea6e64) | Sep 23, 2021 |
| ASUSTek       | PRIME B360M-A               | [b39008d274](https://linux-hardware.org/?probe=b39008d274) | Sep 22, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [d76a8245a5](https://linux-hardware.org/?probe=d76a8245a5) | Sep 22, 2021 |
| Dell          | 0GM819                      | [708ca8f58a](https://linux-hardware.org/?probe=708ca8f58a) | Sep 22, 2021 |
| HP            | 3047h                       | [356ad972a7](https://linux-hardware.org/?probe=356ad972a7) | Sep 22, 2021 |
| Lenovo        | 31900058 STD                | [e24cae5c2f](https://linux-hardware.org/?probe=e24cae5c2f) | Sep 22, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [72bba35083](https://linux-hardware.org/?probe=72bba35083) | Sep 22, 2021 |
| ASUSTek       | Z87-C                       | [2ca018510e](https://linux-hardware.org/?probe=2ca018510e) | Sep 22, 2021 |
| Pegatron      | NARRA5                      | [3e823572de](https://linux-hardware.org/?probe=3e823572de) | Sep 22, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [5172a1a665](https://linux-hardware.org/?probe=5172a1a665) | Sep 22, 2021 |
| ASUSTek       | H87-PRO                     | [a3c7c985ff](https://linux-hardware.org/?probe=a3c7c985ff) | Sep 22, 2021 |
| HC            | HCAR357-MI V1.0             | [d4c7126b92](https://linux-hardware.org/?probe=d4c7126b92) | Sep 22, 2021 |
| Gigabyte      | H110M-S2H-CF                | [05eab7ef4b](https://linux-hardware.org/?probe=05eab7ef4b) | Sep 21, 2021 |
| Acer          | Aspire XC-830               | [74bc82899e](https://linux-hardware.org/?probe=74bc82899e) | Sep 21, 2021 |
| MSI           | H270 GAMING M3              | [3cd206163b](https://linux-hardware.org/?probe=3cd206163b) | Sep 21, 2021 |
| Biostar       | AM1ML                       | [dd9c920c24](https://linux-hardware.org/?probe=dd9c920c24) | Sep 21, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [5422161d82](https://linux-hardware.org/?probe=5422161d82) | Sep 21, 2021 |
| HP            | 18E7                        | [3dfecccb48](https://linux-hardware.org/?probe=3dfecccb48) | Sep 21, 2021 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [3d75b079f5](https://linux-hardware.org/?probe=3d75b079f5) | Sep 20, 2021 |
| Acer          | Aspire XC-830               | [70c023294e](https://linux-hardware.org/?probe=70c023294e) | Sep 20, 2021 |
| ASRock        | N68C-GS FX                  | [8da57ac550](https://linux-hardware.org/?probe=8da57ac550) | Sep 20, 2021 |
| Intel         | DP55WB AAE64798-204         | [d4b171dc3d](https://linux-hardware.org/?probe=d4b171dc3d) | Sep 19, 2021 |
| MSI           | MS-7253                     | [4be11be3f6](https://linux-hardware.org/?probe=4be11be3f6) | Sep 19, 2021 |
| ASUSTek       | A68HM-PLUS                  | [390e0faabf](https://linux-hardware.org/?probe=390e0faabf) | Sep 19, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [5b1bf150bb](https://linux-hardware.org/?probe=5b1bf150bb) | Sep 19, 2021 |
| Intel         | DG41WV AAE90316-102         | [c6bfde4b60](https://linux-hardware.org/?probe=c6bfde4b60) | Sep 19, 2021 |
| ASUSTek       | PRIME B450M-A               | [a8d544a8cc](https://linux-hardware.org/?probe=a8d544a8cc) | Sep 19, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [99773cf00e](https://linux-hardware.org/?probe=99773cf00e) | Sep 19, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [980a095c0f](https://linux-hardware.org/?probe=980a095c0f) | Sep 19, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [9fb09f15eb](https://linux-hardware.org/?probe=9fb09f15eb) | Sep 19, 2021 |
| Dell          | 0M5DCD A00                  | [1686fecc7f](https://linux-hardware.org/?probe=1686fecc7f) | Sep 18, 2021 |
| ASUSTek       | PRIME B550M-A               | [b5a5e09ef0](https://linux-hardware.org/?probe=b5a5e09ef0) | Sep 18, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | [879eb33660](https://linux-hardware.org/?probe=879eb33660) | Sep 18, 2021 |
| HP            | 304Ah                       | [ea9dbc3295](https://linux-hardware.org/?probe=ea9dbc3295) | Sep 18, 2021 |
| Gigabyte      | AX370-Gaming 5              | [5608b1aae3](https://linux-hardware.org/?probe=5608b1aae3) | Sep 18, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | [71d8abb637](https://linux-hardware.org/?probe=71d8abb637) | Sep 18, 2021 |
| Gigabyte      | Z170M-D3H-CF                | [726aef28e3](https://linux-hardware.org/?probe=726aef28e3) | Sep 18, 2021 |
| Gigabyte      | 970A-UD3                    | [30775b0fa5](https://linux-hardware.org/?probe=30775b0fa5) | Sep 18, 2021 |
| Gigabyte      | 970A-UD3                    | [0a0586d3e6](https://linux-hardware.org/?probe=0a0586d3e6) | Sep 18, 2021 |
| Dell          | 0PU052                      | [a4220ae695](https://linux-hardware.org/?probe=a4220ae695) | Sep 18, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [1e34f92251](https://linux-hardware.org/?probe=1e34f92251) | Sep 17, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [c334d92f91](https://linux-hardware.org/?probe=c334d92f91) | Sep 17, 2021 |
| Foxconn       | 2ADA                        | [f362f192fb](https://linux-hardware.org/?probe=f362f192fb) | Sep 17, 2021 |
| MSI           | 970A-G46                    | [973abacc5d](https://linux-hardware.org/?probe=973abacc5d) | Sep 16, 2021 |
| ASRock        | B365M Pro4                  | [220ff38d46](https://linux-hardware.org/?probe=220ff38d46) | Sep 16, 2021 |
| Acer          | FRS690L                     | [7086f5fe7c](https://linux-hardware.org/?probe=7086f5fe7c) | Sep 16, 2021 |
| Gigabyte      | EP43-DS3                    | [d538e97513](https://linux-hardware.org/?probe=d538e97513) | Sep 16, 2021 |
| HP            | 8703                        | [9d6a019031](https://linux-hardware.org/?probe=9d6a019031) | Sep 16, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [809abb28c7](https://linux-hardware.org/?probe=809abb28c7) | Sep 16, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [33e36b0623](https://linux-hardware.org/?probe=33e36b0623) | Sep 15, 2021 |
| HP            | 339A                        | [159f7347c2](https://linux-hardware.org/?probe=159f7347c2) | Sep 15, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [97f690a511](https://linux-hardware.org/?probe=97f690a511) | Sep 15, 2021 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [e880de0931](https://linux-hardware.org/?probe=e880de0931) | Sep 15, 2021 |
| HP            | 8056                        | [ddbc83496c](https://linux-hardware.org/?probe=ddbc83496c) | Sep 15, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [1cfd95b66e](https://linux-hardware.org/?probe=1cfd95b66e) | Sep 15, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | [423826edd0](https://linux-hardware.org/?probe=423826edd0) | Sep 14, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [337a81b054](https://linux-hardware.org/?probe=337a81b054) | Sep 14, 2021 |
| Pegatron      | Benicia                     | [d6cab650c7](https://linux-hardware.org/?probe=d6cab650c7) | Sep 14, 2021 |
| Gigabyte      | X99-Gaming 5                | [b057a2965d](https://linux-hardware.org/?probe=b057a2965d) | Sep 14, 2021 |
| ASRock        | B450M Steel Legend          | [cc958e62b8](https://linux-hardware.org/?probe=cc958e62b8) | Sep 14, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [2d457f6ad5](https://linux-hardware.org/?probe=2d457f6ad5) | Sep 14, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [a20a63cb23](https://linux-hardware.org/?probe=a20a63cb23) | Sep 14, 2021 |
| HP            | 8768 A                      | [5888a9be12](https://linux-hardware.org/?probe=5888a9be12) | Sep 14, 2021 |
| MSI           | H61M-P20                    | [5c930b615e](https://linux-hardware.org/?probe=5c930b615e) | Sep 14, 2021 |
| ASUSTek       | M5A78L-M LX3                | [af6ae24a4e](https://linux-hardware.org/?probe=af6ae24a4e) | Sep 14, 2021 |
| ASUSTek       | M5A78L-M LX3                | [e26c0c5591](https://linux-hardware.org/?probe=e26c0c5591) | Sep 14, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | [c5801cfce8](https://linux-hardware.org/?probe=c5801cfce8) | Sep 14, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [2e4712c237](https://linux-hardware.org/?probe=2e4712c237) | Sep 14, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [df088a601d](https://linux-hardware.org/?probe=df088a601d) | Sep 13, 2021 |
| Gigabyte      | H61M-S1                     | [3009341c2a](https://linux-hardware.org/?probe=3009341c2a) | Sep 13, 2021 |
| ASRock        | Q77M vPro                   | [4ee80780df](https://linux-hardware.org/?probe=4ee80780df) | Sep 13, 2021 |
| ASRock        | Q77M vPro                   | [11278bcc7d](https://linux-hardware.org/?probe=11278bcc7d) | Sep 13, 2021 |
| ASRock        | APL-NUC/J3455               | [f07dea6e74](https://linux-hardware.org/?probe=f07dea6e74) | Sep 13, 2021 |
| HP            | 87D6 SMVB                   | [0cf3d11620](https://linux-hardware.org/?probe=0cf3d11620) | Sep 13, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [93b467da17](https://linux-hardware.org/?probe=93b467da17) | Sep 13, 2021 |
| ASRock        | N68C-S UCC                  | [a44caf0bdc](https://linux-hardware.org/?probe=a44caf0bdc) | Sep 13, 2021 |
| HP            | 87D6 SMVB                   | [f493ff1ea6](https://linux-hardware.org/?probe=f493ff1ea6) | Sep 13, 2021 |
| HP            | 872B                        | [1ad7d53f97](https://linux-hardware.org/?probe=1ad7d53f97) | Sep 13, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [49b0cdfdc4](https://linux-hardware.org/?probe=49b0cdfdc4) | Sep 13, 2021 |
| MSI           | Z68A-GD55                   | [aae29d0847](https://linux-hardware.org/?probe=aae29d0847) | Sep 13, 2021 |
| MSI           | Z97 GAMING 5                | [9055e63e19](https://linux-hardware.org/?probe=9055e63e19) | Sep 12, 2021 |
| HP            | 82FE 11                     | [65852b4eb5](https://linux-hardware.org/?probe=65852b4eb5) | Sep 12, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [10cc07f1c3](https://linux-hardware.org/?probe=10cc07f1c3) | Sep 12, 2021 |
| ASUSTek       | PRIME A520M-K               | [1a4b83e8cc](https://linux-hardware.org/?probe=1a4b83e8cc) | Sep 12, 2021 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [1b82d2d167](https://linux-hardware.org/?probe=1b82d2d167) | Sep 12, 2021 |
| HP            | 339A                        | [d26f3dc453](https://linux-hardware.org/?probe=d26f3dc453) | Sep 11, 2021 |
| HC            | HCAR357-MI V1.0             | [e77876bf8c](https://linux-hardware.org/?probe=e77876bf8c) | Sep 11, 2021 |
| ASUSTek       | PRIME A520M-K               | [5c407737c5](https://linux-hardware.org/?probe=5c407737c5) | Sep 11, 2021 |
| MSI           | 970 GAMING                  | [a383aea0a0](https://linux-hardware.org/?probe=a383aea0a0) | Sep 11, 2021 |
| MSI           | 970 GAMING                  | [0dd4ba39fb](https://linux-hardware.org/?probe=0dd4ba39fb) | Sep 11, 2021 |
| Gigabyte      | P35-DS4                     | [ff9057981b](https://linux-hardware.org/?probe=ff9057981b) | Sep 11, 2021 |
| Gigabyte      | P35-DS4                     | [d5cbc70a78](https://linux-hardware.org/?probe=d5cbc70a78) | Sep 11, 2021 |
| HP            | 83EE                        | [2a014fbea5](https://linux-hardware.org/?probe=2a014fbea5) | Sep 11, 2021 |
| Gigabyte      | H61MA-D2V                   | [df2e5620c6](https://linux-hardware.org/?probe=df2e5620c6) | Sep 11, 2021 |
| Dell          | 0X231R A00                  | [83294c0249](https://linux-hardware.org/?probe=83294c0249) | Sep 11, 2021 |
| ASUSTek       | Crosshair V Formula         | [ce9374d120](https://linux-hardware.org/?probe=ce9374d120) | Sep 11, 2021 |
| ASRock        | 990FX Killer                | [f2c21698ce](https://linux-hardware.org/?probe=f2c21698ce) | Sep 11, 2021 |
| Gigabyte      | GA-MA785GM-US2H             | [4036778458](https://linux-hardware.org/?probe=4036778458) | Sep 11, 2021 |
| ASRock        | A320M-HD                    | [9d79dbb85f](https://linux-hardware.org/?probe=9d79dbb85f) | Sep 11, 2021 |
| ASRock        | A320M-HD                    | [72680b877a](https://linux-hardware.org/?probe=72680b877a) | Sep 11, 2021 |
| MSI           | CSM-B85M-E45                | [2d9685c474](https://linux-hardware.org/?probe=2d9685c474) | Sep 11, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [41894dc479](https://linux-hardware.org/?probe=41894dc479) | Sep 10, 2021 |
| HP            | 0A98h                       | [986db869b7](https://linux-hardware.org/?probe=986db869b7) | Sep 10, 2021 |
| ASUSTek       | M5A78L LE                   | [dc65befff1](https://linux-hardware.org/?probe=dc65befff1) | Sep 10, 2021 |
| ASUSTek       | M5A78L LE                   | [46dcdb6184](https://linux-hardware.org/?probe=46dcdb6184) | Sep 10, 2021 |
| ECS           | H61H2-M6                    | [b4a203ac5e](https://linux-hardware.org/?probe=b4a203ac5e) | Sep 10, 2021 |
| MSI           | B350M GAMING PRO            | [052bfbd512](https://linux-hardware.org/?probe=052bfbd512) | Sep 09, 2021 |
| MSI           | B350M GAMING PRO            | [a3b7774236](https://linux-hardware.org/?probe=a3b7774236) | Sep 09, 2021 |
| Gigabyte      | MZBSWAP-K4                  | [8b88d7ab23](https://linux-hardware.org/?probe=8b88d7ab23) | Sep 08, 2021 |
| Gigabyte      | MZBSWAP-K4                  | [ae4295e17e](https://linux-hardware.org/?probe=ae4295e17e) | Sep 08, 2021 |
| ASUSTek       | A88XM-E/USB                 | [9a2d988aba](https://linux-hardware.org/?probe=9a2d988aba) | Sep 08, 2021 |
| ASUSTek       | A88XM-E/USB                 | [ce9a48f4f4](https://linux-hardware.org/?probe=ce9a48f4f4) | Sep 08, 2021 |
| Gigabyte      | X99-UD4-CF                  | [4bb4ecadde](https://linux-hardware.org/?probe=4bb4ecadde) | Sep 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3e4596b968](https://linux-hardware.org/?probe=3e4596b968) | Sep 08, 2021 |
| ASRock        | 970 Extreme4                | [729d567161](https://linux-hardware.org/?probe=729d567161) | Sep 08, 2021 |
| ASRock        | N68-S3 FX                   | [6cd6e2e46b](https://linux-hardware.org/?probe=6cd6e2e46b) | Sep 08, 2021 |
| Dell          | 0X231R A00                  | [52b9aaf36d](https://linux-hardware.org/?probe=52b9aaf36d) | Sep 07, 2021 |
| Intel         | D945GCLF2D AAE59323-101     | [d6808fecbf](https://linux-hardware.org/?probe=d6808fecbf) | Sep 07, 2021 |
| HP            | 82F1                        | [d7aab7611a](https://linux-hardware.org/?probe=d7aab7611a) | Sep 07, 2021 |
| HP            | 82F1                        | [5f01149ce6](https://linux-hardware.org/?probe=5f01149ce6) | Sep 07, 2021 |
| ASUSTek       | P5E                         | [f2536ac0ff](https://linux-hardware.org/?probe=f2536ac0ff) | Sep 07, 2021 |
| Dell          | 0M5DCD A00                  | [89f806e02f](https://linux-hardware.org/?probe=89f806e02f) | Sep 07, 2021 |
| Dell          | 0D28YY A02                  | [dd3fbea0a7](https://linux-hardware.org/?probe=dd3fbea0a7) | Sep 07, 2021 |
| ASUSTek       | P7P55-M                     | [5c6513527b](https://linux-hardware.org/?probe=5c6513527b) | Sep 07, 2021 |
| Fujitsu Si... | D2451-A2 S26361-D2451-A2    | [7106ac4458](https://linux-hardware.org/?probe=7106ac4458) | Sep 07, 2021 |
| Positivo      | POS-EINM70CS POSITIVO       | [e9b6332a1f](https://linux-hardware.org/?probe=e9b6332a1f) | Sep 07, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [3d33efbcb3](https://linux-hardware.org/?probe=3d33efbcb3) | Sep 07, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [e0fba8ec14](https://linux-hardware.org/?probe=e0fba8ec14) | Sep 07, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [ad994fdd18](https://linux-hardware.org/?probe=ad994fdd18) | Sep 07, 2021 |
| ASRock        | G41M-VS                     | [4895fb4c21](https://linux-hardware.org/?probe=4895fb4c21) | Sep 07, 2021 |
| ASUSTek       | V-P8H67E                    | [a5eb4302d5](https://linux-hardware.org/?probe=a5eb4302d5) | Sep 06, 2021 |
| Dell          | 0C7195                      | [5e8cb420ea](https://linux-hardware.org/?probe=5e8cb420ea) | Sep 06, 2021 |
| DFI           | LP 925X-T2                  | [6f87ed4c41](https://linux-hardware.org/?probe=6f87ed4c41) | Sep 06, 2021 |
| Dell          | 0C7195                      | [c738d5b852](https://linux-hardware.org/?probe=c738d5b852) | Sep 06, 2021 |
| ASUSTek       | P8H67-M PRO                 | [fdb16528ab](https://linux-hardware.org/?probe=fdb16528ab) | Sep 06, 2021 |
| MSI           | X570-A PRO                  | [6d486e0e31](https://linux-hardware.org/?probe=6d486e0e31) | Sep 06, 2021 |
| ASUSTek       | Z87-C                       | [d12600995f](https://linux-hardware.org/?probe=d12600995f) | Sep 06, 2021 |
| Dell          | 0J3C2F A02                  | [f4dd0954c8](https://linux-hardware.org/?probe=f4dd0954c8) | Sep 06, 2021 |
| ASUSTek       | Commando                    | [1d1e5c6d7c](https://linux-hardware.org/?probe=1d1e5c6d7c) | Sep 05, 2021 |
| ASUSTek       | PRIME H370-PLUS             | [752964e357](https://linux-hardware.org/?probe=752964e357) | Sep 05, 2021 |
| ASRock        | N68-GS4 FX                  | [b1147fa740](https://linux-hardware.org/?probe=b1147fa740) | Sep 05, 2021 |
| ASRock        | N68-GS4 FX                  | [e33cd98e47](https://linux-hardware.org/?probe=e33cd98e47) | Sep 05, 2021 |
| Dell          | 0YXT71 A03                  | [bb0ef0735f](https://linux-hardware.org/?probe=bb0ef0735f) | Sep 05, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [43ee4267c3](https://linux-hardware.org/?probe=43ee4267c3) | Sep 05, 2021 |
| Dell          | 0J3C2F A02                  | [d6e4dc66a6](https://linux-hardware.org/?probe=d6e4dc66a6) | Sep 04, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [db5cf19c4f](https://linux-hardware.org/?probe=db5cf19c4f) | Sep 04, 2021 |
| HP            | 339A                        | [2c96fd74fb](https://linux-hardware.org/?probe=2c96fd74fb) | Sep 04, 2021 |
| Intel         | DP55WB AAE64798-204         | [abc17b67fe](https://linux-hardware.org/?probe=abc17b67fe) | Sep 03, 2021 |
| Gigabyte      | B460M DS3H V2               | [95b2a792dc](https://linux-hardware.org/?probe=95b2a792dc) | Sep 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [eb63e95eda](https://linux-hardware.org/?probe=eb63e95eda) | Sep 03, 2021 |
| ASRock        | B365M Pro4                  | [dae996e0cd](https://linux-hardware.org/?probe=dae996e0cd) | Sep 03, 2021 |
| MSI           | H61M-P20                    | [f389b9a3ca](https://linux-hardware.org/?probe=f389b9a3ca) | Sep 02, 2021 |
| MSI           | 970 GAMING                  | [be96e376bd](https://linux-hardware.org/?probe=be96e376bd) | Sep 02, 2021 |
| Pegatron      | 2AEE                        | [b24886cd7f](https://linux-hardware.org/?probe=b24886cd7f) | Sep 02, 2021 |
| Gigabyte      | B460M DS3H V2               | [f0f618d5a4](https://linux-hardware.org/?probe=f0f618d5a4) | Sep 02, 2021 |
| Foxconn       | M61PMV FAB                  | [9a3fc925aa](https://linux-hardware.org/?probe=9a3fc925aa) | Sep 02, 2021 |
| Foxconn       | M61PMV FAB                  | [880a64fe95](https://linux-hardware.org/?probe=880a64fe95) | Sep 02, 2021 |
| Dell          | 0J3C2F A01                  | [57e7819c28](https://linux-hardware.org/?probe=57e7819c28) | Sep 02, 2021 |
| DFI           | LP 925X-T2                  | [b86e87aff9](https://linux-hardware.org/?probe=b86e87aff9) | Sep 01, 2021 |
| DFI           | LP 925X-T2                  | [cf040efdc2](https://linux-hardware.org/?probe=cf040efdc2) | Sep 01, 2021 |
| Medion        | MS-7633                     | [decad06e89](https://linux-hardware.org/?probe=decad06e89) | Sep 01, 2021 |
| Biostar       | NM70I-847                   | [f2c9d990c4](https://linux-hardware.org/?probe=f2c9d990c4) | Sep 01, 2021 |
| Dell          | 0T10XW A01                  | [6f7bfa7d4d](https://linux-hardware.org/?probe=6f7bfa7d4d) | Sep 01, 2021 |
| Dell          | 0T10XW A01                  | [359c0c9382](https://linux-hardware.org/?probe=359c0c9382) | Sep 01, 2021 |
| DFI           | LP 925X-T2                  | [e2a758a937](https://linux-hardware.org/?probe=e2a758a937) | Aug 31, 2021 |
| PCWare        | IPMH61R1                    | [2479b1480b](https://linux-hardware.org/?probe=2479b1480b) | Aug 31, 2021 |
| MSI           | E350DM-E33                  | [d1bc30b527](https://linux-hardware.org/?probe=d1bc30b527) | Aug 31, 2021 |
| Dell          | 0N4YC8 A00                  | [7e7b3b3b91](https://linux-hardware.org/?probe=7e7b3b3b91) | Aug 31, 2021 |
| ASRock        | ALiveNF6G-VSTA              | [a78f46a907](https://linux-hardware.org/?probe=a78f46a907) | Aug 31, 2021 |
| ASUSTek       | PRIME B450M-A II            | [4dc49cd752](https://linux-hardware.org/?probe=4dc49cd752) | Aug 31, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [248d9c8b52](https://linux-hardware.org/?probe=248d9c8b52) | Aug 31, 2021 |
| ASRock        | AB350M Pro4                 | [24de612862](https://linux-hardware.org/?probe=24de612862) | Aug 31, 2021 |
| Medion        | MS-7633                     | [d477f1ff35](https://linux-hardware.org/?probe=d477f1ff35) | Aug 31, 2021 |
| HP            | 1497                        | [78103e94cd](https://linux-hardware.org/?probe=78103e94cd) | Aug 31, 2021 |
| Gigabyte      | GA-78LMT-S2                 | [0aa9eacb6a](https://linux-hardware.org/?probe=0aa9eacb6a) | Aug 31, 2021 |
| Biostar       | NM70I-847                   | [b8abb12f26](https://linux-hardware.org/?probe=b8abb12f26) | Aug 31, 2021 |
| HP            | 1850                        | [3bab0322ec](https://linux-hardware.org/?probe=3bab0322ec) | Aug 30, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [0d80b8eec9](https://linux-hardware.org/?probe=0d80b8eec9) | Aug 30, 2021 |
| Dell          | 0R849J A00                  | [0f128f25a7](https://linux-hardware.org/?probe=0f128f25a7) | Aug 30, 2021 |
| DFI           | LP 925X-T2                  | [7835627b56](https://linux-hardware.org/?probe=7835627b56) | Aug 30, 2021 |
| Unknown       | Unknown                     | [6cd64890d8](https://linux-hardware.org/?probe=6cd64890d8) | Aug 30, 2021 |
| ASUSTek       | P8H67-V                     | [954e4881c6](https://linux-hardware.org/?probe=954e4881c6) | Aug 30, 2021 |
| ASUSTek       | PRIME X570-P                | [f185dd7230](https://linux-hardware.org/?probe=f185dd7230) | Aug 30, 2021 |
| ASUSTek       | TUF GAMING B460M-PLUS       | [190ef257e8](https://linux-hardware.org/?probe=190ef257e8) | Aug 30, 2021 |
| MSI           | MS-7360                     | [7b04316091](https://linux-hardware.org/?probe=7b04316091) | Aug 30, 2021 |
| ECS           | G43T-AM                     | [9f51ae221b](https://linux-hardware.org/?probe=9f51ae221b) | Aug 30, 2021 |
| ASRock        | Z270 Killer SLI/ac          | [90d1808d1f](https://linux-hardware.org/?probe=90d1808d1f) | Aug 29, 2021 |
| Acer          | Elena                       | [b215ba0db1](https://linux-hardware.org/?probe=b215ba0db1) | Aug 29, 2021 |
| HP            | 1494                        | [2ead4a4e91](https://linux-hardware.org/?probe=2ead4a4e91) | Aug 29, 2021 |
| Acer          | E946GZ                      | [fd1d491c48](https://linux-hardware.org/?probe=fd1d491c48) | Aug 29, 2021 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [e7de7df1c7](https://linux-hardware.org/?probe=e7de7df1c7) | Aug 28, 2021 |
| DFI           | LP 925X-T2                  | [a0a96d01d3](https://linux-hardware.org/?probe=a0a96d01d3) | Aug 28, 2021 |
| MSI           | 760GM-E51                   | [d196442e59](https://linux-hardware.org/?probe=d196442e59) | Aug 28, 2021 |
| DFI           | LP 925X-T2                  | [7a45811341](https://linux-hardware.org/?probe=7a45811341) | Aug 28, 2021 |
| ASUSTek       | PRIME X570-P                | [90bb3d1b01](https://linux-hardware.org/?probe=90bb3d1b01) | Aug 28, 2021 |
| ASUSTek       | PRIME X570-P                | [7061106d50](https://linux-hardware.org/?probe=7061106d50) | Aug 28, 2021 |
| ASUSTek       | Q87M-E                      | [588e2a68e5](https://linux-hardware.org/?probe=588e2a68e5) | Aug 28, 2021 |
| ASUSTek       | P6X58D-E                    | [cf4c0a5a4d](https://linux-hardware.org/?probe=cf4c0a5a4d) | Aug 28, 2021 |
| ASUSTek       | Maximus IV Extreme          | [28427b19d7](https://linux-hardware.org/?probe=28427b19d7) | Aug 28, 2021 |
| ASRock        | B450M Steel Legend          | [9b335e87fe](https://linux-hardware.org/?probe=9b335e87fe) | Aug 28, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [2c3f484fc0](https://linux-hardware.org/?probe=2c3f484fc0) | Aug 28, 2021 |
| Dell          | 0C522T A00                  | [61a97623e0](https://linux-hardware.org/?probe=61a97623e0) | Aug 28, 2021 |
| Gigabyte      | B550M AORUS PRO             | [cd8fb61a12](https://linux-hardware.org/?probe=cd8fb61a12) | Aug 27, 2021 |
| HP            | 1497                        | [172fbe6a53](https://linux-hardware.org/?probe=172fbe6a53) | Aug 27, 2021 |
| ASRock        | X570M Pro4                  | [63aa83fa72](https://linux-hardware.org/?probe=63aa83fa72) | Aug 27, 2021 |
| MSI           | B450-A PRO MAX              | [b0f3ea8e48](https://linux-hardware.org/?probe=b0f3ea8e48) | Aug 27, 2021 |
| ASUSTek       | P8B75-M LX                  | [c75a0c0b0d](https://linux-hardware.org/?probe=c75a0c0b0d) | Aug 27, 2021 |
| Packard Be... | WMCP78M                     | [6017a97f3e](https://linux-hardware.org/?probe=6017a97f3e) | Aug 27, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [68da5f41b2](https://linux-hardware.org/?probe=68da5f41b2) | Aug 27, 2021 |
| Packard Be... | WMCP78M                     | [159b009d61](https://linux-hardware.org/?probe=159b009d61) | Aug 27, 2021 |
| Packard Be... | WMCP78M                     | [325fbc663c](https://linux-hardware.org/?probe=325fbc663c) | Aug 27, 2021 |
| MSI           | H61M-P20                    | [a4322b4668](https://linux-hardware.org/?probe=a4322b4668) | Aug 27, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [f76e6521ae](https://linux-hardware.org/?probe=f76e6521ae) | Aug 27, 2021 |
| HP            | 8056                        | [8eb9cf3f7a](https://linux-hardware.org/?probe=8eb9cf3f7a) | Aug 27, 2021 |
| ASUSTek       | P8B75-M LX                  | [ecf2d90f81](https://linux-hardware.org/?probe=ecf2d90f81) | Aug 26, 2021 |
| ASRock        | Q1900B-ITX                  | [6c231ade42](https://linux-hardware.org/?probe=6c231ade42) | Aug 26, 2021 |
| Gigabyte      | GB-BRR7H-4800               | [d87877599e](https://linux-hardware.org/?probe=d87877599e) | Aug 26, 2021 |
| Intel         | DP55WB AAE64798-204         | [2584a3d10e](https://linux-hardware.org/?probe=2584a3d10e) | Aug 26, 2021 |
| ASUSTek       | H81M-C                      | [83393788bf](https://linux-hardware.org/?probe=83393788bf) | Aug 26, 2021 |
| ASRock        | H410M-ITX/ac                | [36d19d4783](https://linux-hardware.org/?probe=36d19d4783) | Aug 26, 2021 |
| ASRock        | G41M-VS                     | [6d2338d42c](https://linux-hardware.org/?probe=6d2338d42c) | Aug 26, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [0d404bc317](https://linux-hardware.org/?probe=0d404bc317) | Aug 25, 2021 |
| Dell          | 06X1TJ A00                  | [f2e7416585](https://linux-hardware.org/?probe=f2e7416585) | Aug 25, 2021 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | [524d286fc6](https://linux-hardware.org/?probe=524d286fc6) | Aug 25, 2021 |
| ASUSTek       | PRIME Z390-A                | [f179b89779](https://linux-hardware.org/?probe=f179b89779) | Aug 25, 2021 |
| ASRock        | B550M Pro4                  | [2135d34339](https://linux-hardware.org/?probe=2135d34339) | Aug 25, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [0de7aa005a](https://linux-hardware.org/?probe=0de7aa005a) | Aug 25, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [b2d0f83e64](https://linux-hardware.org/?probe=b2d0f83e64) | Aug 25, 2021 |
| Gigabyte      | H81M-D2V                    | [2d9e510ffb](https://linux-hardware.org/?probe=2d9e510ffb) | Aug 24, 2021 |
| HC            | HCAR357-MI V1.0             | [bd1ce2340a](https://linux-hardware.org/?probe=bd1ce2340a) | Aug 24, 2021 |
| ASUSTek       | F1A75-V PRO                 | [52bfc025ea](https://linux-hardware.org/?probe=52bfc025ea) | Aug 24, 2021 |
| ASUSTek       | F1A75-V PRO                 | [2e19d48879](https://linux-hardware.org/?probe=2e19d48879) | Aug 24, 2021 |
| Gigabyte      | G31M-S2C                    | [15d48710db](https://linux-hardware.org/?probe=15d48710db) | Aug 24, 2021 |
| HP            | 1495                        | [efd819b050](https://linux-hardware.org/?probe=efd819b050) | Aug 24, 2021 |
| Dell          | 0PU052                      | [639d8ed1b3](https://linux-hardware.org/?probe=639d8ed1b3) | Aug 23, 2021 |
| Gigabyte      | Z77X-D3H                    | [a48e5130e8](https://linux-hardware.org/?probe=a48e5130e8) | Aug 23, 2021 |
| HP            | 1589                        | [4d308c9d28](https://linux-hardware.org/?probe=4d308c9d28) | Aug 23, 2021 |
| Dell          | 0VHWTR A01                  | [44a0ff75c4](https://linux-hardware.org/?probe=44a0ff75c4) | Aug 23, 2021 |
| Dell          | 0PU052                      | [7d02b28426](https://linux-hardware.org/?probe=7d02b28426) | Aug 23, 2021 |
| Lenovo        | 31900058 STD                | [fc54dc715f](https://linux-hardware.org/?probe=fc54dc715f) | Aug 23, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [75b8e49a80](https://linux-hardware.org/?probe=75b8e49a80) | Aug 23, 2021 |
| Acer          | RS780DV                     | [57b9f12c78](https://linux-hardware.org/?probe=57b9f12c78) | Aug 23, 2021 |
| ASUSTek       | PRIME Z390-A                | [983a472563](https://linux-hardware.org/?probe=983a472563) | Aug 22, 2021 |
| MSI           | E350DM-E33                  | [c1f85a0dd1](https://linux-hardware.org/?probe=c1f85a0dd1) | Aug 22, 2021 |
| Dell          | 0T656F A02                  | [7115ffee65](https://linux-hardware.org/?probe=7115ffee65) | Aug 22, 2021 |
| Alienware     | 07W25T A00                  | [9de02c2502](https://linux-hardware.org/?probe=9de02c2502) | Aug 22, 2021 |
| Alienware     | 07W25T A00                  | [592ec5b28e](https://linux-hardware.org/?probe=592ec5b28e) | Aug 22, 2021 |
| HP            | 08B8h                       | [91726cd422](https://linux-hardware.org/?probe=91726cd422) | Aug 22, 2021 |
| MSI           | Z170-A PRO                  | [6713ee6c8f](https://linux-hardware.org/?probe=6713ee6c8f) | Aug 22, 2021 |
| AMI           | Cherry Trail CR             | [c62a7ba17c](https://linux-hardware.org/?probe=c62a7ba17c) | Aug 22, 2021 |
| AMI           | Cherry Trail CR             | [f6d19ff1d9](https://linux-hardware.org/?probe=f6d19ff1d9) | Aug 22, 2021 |
| ASUSTek       | PRIME Z370-A                | [a6f2aa42c9](https://linux-hardware.org/?probe=a6f2aa42c9) | Aug 22, 2021 |
| ASUSTek       | PRIME Z370-A                | [03826ea2dc](https://linux-hardware.org/?probe=03826ea2dc) | Aug 22, 2021 |
| ASUSTek       | Z170-A                      | [3abd60af90](https://linux-hardware.org/?probe=3abd60af90) | Aug 22, 2021 |
| Gigabyte      | G31M-S2C                    | [a8d5b4ff89](https://linux-hardware.org/?probe=a8d5b4ff89) | Aug 22, 2021 |
| HP            | 3047h                       | [83bcb476ff](https://linux-hardware.org/?probe=83bcb476ff) | Aug 21, 2021 |
| Dell          | 0J37VM A01                  | [d35c6ea078](https://linux-hardware.org/?probe=d35c6ea078) | Aug 21, 2021 |
| ASUSTek       | PRIME B550M-A               | [a7243cb687](https://linux-hardware.org/?probe=a7243cb687) | Aug 21, 2021 |
| Acer          | Aspire X3990                | [e6f9ebd85c](https://linux-hardware.org/?probe=e6f9ebd85c) | Aug 21, 2021 |
| Gigabyte      | MFLP5IP-00                  | [5e56a713fd](https://linux-hardware.org/?probe=5e56a713fd) | Aug 21, 2021 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [0e048f070c](https://linux-hardware.org/?probe=0e048f070c) | Aug 21, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [37b0da887b](https://linux-hardware.org/?probe=37b0da887b) | Aug 21, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [126b405189](https://linux-hardware.org/?probe=126b405189) | Aug 21, 2021 |
| HP            | 08B8h                       | [85e5a57bef](https://linux-hardware.org/?probe=85e5a57bef) | Aug 21, 2021 |
| ASUSTek       | H110M-E/M.2                 | [3e2b5a80bd](https://linux-hardware.org/?probe=3e2b5a80bd) | Aug 21, 2021 |
| ASUSTek       | H110M-E/M.2                 | [13c3078b8d](https://linux-hardware.org/?probe=13c3078b8d) | Aug 20, 2021 |
| ASUSTek       | Maximus VII HERO            | [1a32dcae22](https://linux-hardware.org/?probe=1a32dcae22) | Aug 20, 2021 |
| Gateway       | FX6860                      | [403139feb5](https://linux-hardware.org/?probe=403139feb5) | Aug 20, 2021 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [afa56ccf22](https://linux-hardware.org/?probe=afa56ccf22) | Aug 20, 2021 |
| ASUSTek       | M4N68T-M LE                 | [483cf44fcf](https://linux-hardware.org/?probe=483cf44fcf) | Aug 20, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [a12e493c37](https://linux-hardware.org/?probe=a12e493c37) | Aug 20, 2021 |
| ASRock        | P67 Pro3                    | [9d78fc5336](https://linux-hardware.org/?probe=9d78fc5336) | Aug 20, 2021 |
| HP            | 304Ah                       | [8a2d5eb337](https://linux-hardware.org/?probe=8a2d5eb337) | Aug 20, 2021 |
| HP            | 08B8h                       | [57f6552e40](https://linux-hardware.org/?probe=57f6552e40) | Aug 20, 2021 |
| Pegatron      | 2A94                        | [89f32c6f1d](https://linux-hardware.org/?probe=89f32c6f1d) | Aug 19, 2021 |
| ASRock        | H310CM-ITX/ac               | [894b4aa792](https://linux-hardware.org/?probe=894b4aa792) | Aug 19, 2021 |
| ASUSTek       | D520MT_D520SF_D320MT        | [5fb844180b](https://linux-hardware.org/?probe=5fb844180b) | Aug 19, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [4fd0c6f1dc](https://linux-hardware.org/?probe=4fd0c6f1dc) | Aug 19, 2021 |
| ASRock        | X399 Professional Gaming    | [30e51ec830](https://linux-hardware.org/?probe=30e51ec830) | Aug 19, 2021 |
| ECS           | H61H2-M6                    | [89267dacbf](https://linux-hardware.org/?probe=89267dacbf) | Aug 19, 2021 |
| HC            | HCAR357-MI V1.0             | [bbe9348477](https://linux-hardware.org/?probe=bbe9348477) | Aug 19, 2021 |
| Dell          | 0HN7XN A01                  | [b81e6fce87](https://linux-hardware.org/?probe=b81e6fce87) | Aug 18, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [20cbedbe02](https://linux-hardware.org/?probe=20cbedbe02) | Aug 18, 2021 |
| HP            | 304Ah                       | [d4463b1cdb](https://linux-hardware.org/?probe=d4463b1cdb) | Aug 18, 2021 |
| Dell          | 0XC7MM A01                  | [1d0b62c228](https://linux-hardware.org/?probe=1d0b62c228) | Aug 18, 2021 |
| Gigabyte      | 2AC8                        | [76b1688580](https://linux-hardware.org/?probe=76b1688580) | Aug 18, 2021 |
| Gigabyte      | H77N-WIFI                   | [7aed6565ee](https://linux-hardware.org/?probe=7aed6565ee) | Aug 17, 2021 |
| ASRock        | Z270 Killer SLI/ac          | [027b87fe35](https://linux-hardware.org/?probe=027b87fe35) | Aug 17, 2021 |
| HP            | 0A64h                       | [4eb285306c](https://linux-hardware.org/?probe=4eb285306c) | Aug 17, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [535deb980c](https://linux-hardware.org/?probe=535deb980c) | Aug 17, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [04d9b1d5ac](https://linux-hardware.org/?probe=04d9b1d5ac) | Aug 17, 2021 |
| Dell          | 0X9680                      | [0753ad51f6](https://linux-hardware.org/?probe=0753ad51f6) | Aug 16, 2021 |
| ASUSTek       | Maximus VII HERO            | [01da0ddee2](https://linux-hardware.org/?probe=01da0ddee2) | Aug 16, 2021 |
| Intel         | DG33BU AAD79951-413         | [9824fedcc4](https://linux-hardware.org/?probe=9824fedcc4) | Aug 16, 2021 |
| Dell          | 0XC7MM A01                  | [64c3170dc8](https://linux-hardware.org/?probe=64c3170dc8) | Aug 16, 2021 |
| Zillion       | Unknown                     | [eca4874a91](https://linux-hardware.org/?probe=eca4874a91) | Aug 16, 2021 |
| ASUSTek       | F1A55-M LK R2.0             | [584c8073a4](https://linux-hardware.org/?probe=584c8073a4) | Aug 16, 2021 |
| Gigabyte      | H81M-S2PH                   | [527a7b3d30](https://linux-hardware.org/?probe=527a7b3d30) | Aug 16, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS_BR     | [fc6cc9b254](https://linux-hardware.org/?probe=fc6cc9b254) | Aug 15, 2021 |
| Gigabyte      | H81M-D2V                    | [21b913316b](https://linux-hardware.org/?probe=21b913316b) | Aug 15, 2021 |
| Acer          | RS780DV                     | [994fc23020](https://linux-hardware.org/?probe=994fc23020) | Aug 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | [16dc0450e2](https://linux-hardware.org/?probe=16dc0450e2) | Aug 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | [48c2b7a173](https://linux-hardware.org/?probe=48c2b7a173) | Aug 15, 2021 |
| ASUSTek       | PRIME X570-P                | [a86f566c6c](https://linux-hardware.org/?probe=a86f566c6c) | Aug 15, 2021 |
| MSI           | B450-A PRO MAX              | [2300e053ca](https://linux-hardware.org/?probe=2300e053ca) | Aug 15, 2021 |
| MSI           | B450-A PRO MAX              | [52778d6325](https://linux-hardware.org/?probe=52778d6325) | Aug 15, 2021 |
| ASUSTek       | PRIME X570-P                | [be9bb3d6af](https://linux-hardware.org/?probe=be9bb3d6af) | Aug 15, 2021 |
| Medion        | MS-7713                     | [c46b6b5b42](https://linux-hardware.org/?probe=c46b6b5b42) | Aug 15, 2021 |
| Medion        | MS-7713                     | [bc082003f5](https://linux-hardware.org/?probe=bc082003f5) | Aug 15, 2021 |
| Acer          | Aspire E500                 | [90210dde7b](https://linux-hardware.org/?probe=90210dde7b) | Aug 15, 2021 |
| Acer          | Aspire E500                 | [b6d4223ae5](https://linux-hardware.org/?probe=b6d4223ae5) | Aug 15, 2021 |
| HP            | 83E9                        | [325763d5e0](https://linux-hardware.org/?probe=325763d5e0) | Aug 15, 2021 |
| HP            | 83E9                        | [374e9260c0](https://linux-hardware.org/?probe=374e9260c0) | Aug 15, 2021 |
| ASRock        | H370 Performance            | [6f327655e8](https://linux-hardware.org/?probe=6f327655e8) | Aug 15, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [9ab4399f8c](https://linux-hardware.org/?probe=9ab4399f8c) | Aug 15, 2021 |
| HP            | 304Ah                       | [b5a5924aad](https://linux-hardware.org/?probe=b5a5924aad) | Aug 15, 2021 |
| HP            | 304Ah                       | [3cdb5a799c](https://linux-hardware.org/?probe=3cdb5a799c) | Aug 15, 2021 |
| ASRock        | G31M-S                      | [bb468923e2](https://linux-hardware.org/?probe=bb468923e2) | Aug 15, 2021 |
| ASRock        | X570 Pro4                   | [3f122964da](https://linux-hardware.org/?probe=3f122964da) | Aug 14, 2021 |
| ASUSTek       | Maximus VII GENE            | [400f842023](https://linux-hardware.org/?probe=400f842023) | Aug 14, 2021 |
| MSI           | B450-A PRO MAX              | [a5d64983dc](https://linux-hardware.org/?probe=a5d64983dc) | Aug 14, 2021 |
| ASRock        | X300TM-ITX                  | [7a67243762](https://linux-hardware.org/?probe=7a67243762) | Aug 14, 2021 |
| Gigabyte      | 970A-DS3P                   | [39d403837b](https://linux-hardware.org/?probe=39d403837b) | Aug 14, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [02b246850f](https://linux-hardware.org/?probe=02b246850f) | Aug 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [47857ab024](https://linux-hardware.org/?probe=47857ab024) | Aug 14, 2021 |
| PCWare        | IPX1800E2                   | [bf9caf2034](https://linux-hardware.org/?probe=bf9caf2034) | Aug 14, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a19e04efad](https://linux-hardware.org/?probe=a19e04efad) | Aug 13, 2021 |
| Acer          | RS780DV                     | [465919d85b](https://linux-hardware.org/?probe=465919d85b) | Aug 13, 2021 |
| Gigabyte      | 970A-UD3P                   | [1993cb18b6](https://linux-hardware.org/?probe=1993cb18b6) | Aug 13, 2021 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [008db1b6aa](https://linux-hardware.org/?probe=008db1b6aa) | Aug 13, 2021 |
| ASUSTek       | P8H61-MX USB3               | [bfa0d51edf](https://linux-hardware.org/?probe=bfa0d51edf) | Aug 13, 2021 |
| Gigabyte      | H81M-D2V                    | [3f6cd51532](https://linux-hardware.org/?probe=3f6cd51532) | Aug 13, 2021 |
| ASUSTek       | M5A97                       | [886707949b](https://linux-hardware.org/?probe=886707949b) | Aug 13, 2021 |
| Seco          | C40 C                       | [da14eea52c](https://linux-hardware.org/?probe=da14eea52c) | Aug 13, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | [c2c86f701d](https://linux-hardware.org/?probe=c2c86f701d) | Aug 13, 2021 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [02cfb8f16e](https://linux-hardware.org/?probe=02cfb8f16e) | Aug 12, 2021 |
| HP            | 3048h                       | [28cbe7812e](https://linux-hardware.org/?probe=28cbe7812e) | Aug 12, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [704537df18](https://linux-hardware.org/?probe=704537df18) | Aug 12, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [470372db2c](https://linux-hardware.org/?probe=470372db2c) | Aug 12, 2021 |
| HP            | 3397                        | [1f5c35a59f](https://linux-hardware.org/?probe=1f5c35a59f) | Aug 12, 2021 |
| ECS           | H81H3-WM                    | [4b6040d70e](https://linux-hardware.org/?probe=4b6040d70e) | Aug 12, 2021 |
| Intel         | DX38BT AAD85848-503         | [d9ea2aa414](https://linux-hardware.org/?probe=d9ea2aa414) | Aug 12, 2021 |
| ECS           | H81H3-WM                    | [8a83164118](https://linux-hardware.org/?probe=8a83164118) | Aug 12, 2021 |
| ASRock        | B450 Steel Legend           | [277bb0afb5](https://linux-hardware.org/?probe=277bb0afb5) | Aug 11, 2021 |
| Dell          | 0YJPT1 A00                  | [df38ee9c55](https://linux-hardware.org/?probe=df38ee9c55) | Aug 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [bc618727f4](https://linux-hardware.org/?probe=bc618727f4) | Aug 10, 2021 |
| Seco          | C40 C                       | [4bc1710a2d](https://linux-hardware.org/?probe=4bc1710a2d) | Aug 10, 2021 |
| Gigabyte      | M57SLI-S4                   | [dc6d81f2c5](https://linux-hardware.org/?probe=dc6d81f2c5) | Aug 10, 2021 |
| MSI           | H55M-E33                    | [2c2dda3bfb](https://linux-hardware.org/?probe=2c2dda3bfb) | Aug 10, 2021 |
| Seco          | C40 C                       | [60b5f94ee7](https://linux-hardware.org/?probe=60b5f94ee7) | Aug 10, 2021 |
| MSI           | 970A-G43                    | [6ca4c3466a](https://linux-hardware.org/?probe=6ca4c3466a) | Aug 10, 2021 |
| ASRock        | B550M Pro4                  | [9092457b4b](https://linux-hardware.org/?probe=9092457b4b) | Aug 10, 2021 |
| MSI           | FM2-A55M-P33                | [22ffcc8c10](https://linux-hardware.org/?probe=22ffcc8c10) | Aug 10, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [bf03ae775b](https://linux-hardware.org/?probe=bf03ae775b) | Aug 10, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [9308986f32](https://linux-hardware.org/?probe=9308986f32) | Aug 09, 2021 |
| MSI           | X99A RAIDER                 | [33539a9790](https://linux-hardware.org/?probe=33539a9790) | Aug 09, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [86b3d3acc3](https://linux-hardware.org/?probe=86b3d3acc3) | Aug 09, 2021 |
| Lenovo        | ThinkCentre M58 9728A5G     | [2d1e0a6a1b](https://linux-hardware.org/?probe=2d1e0a6a1b) | Aug 09, 2021 |
| Gigabyte      | B450M DS3H-CF               | [99763e52f1](https://linux-hardware.org/?probe=99763e52f1) | Aug 09, 2021 |
| Intel         | DX38BT AAD85848-503         | [9495ca3432](https://linux-hardware.org/?probe=9495ca3432) | Aug 09, 2021 |
| Positivo      | POS-PIG41BO                 | [58c9411a30](https://linux-hardware.org/?probe=58c9411a30) | Aug 09, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [c7ea2e5f09](https://linux-hardware.org/?probe=c7ea2e5f09) | Aug 09, 2021 |
| ASRock        | B550M Pro4                  | [f883001d8b](https://linux-hardware.org/?probe=f883001d8b) | Aug 09, 2021 |
| ASUSTek       | PRIME Z370-A                | [48f2b29fbb](https://linux-hardware.org/?probe=48f2b29fbb) | Aug 08, 2021 |
| PCChips       | P53G                        | [d5066d6f5b](https://linux-hardware.org/?probe=d5066d6f5b) | Aug 08, 2021 |
| ASUSTek       | P5P43TD PRO                 | [0576757382](https://linux-hardware.org/?probe=0576757382) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [44b36ed25b](https://linux-hardware.org/?probe=44b36ed25b) | Aug 08, 2021 |
| Seco          | C40 C                       | [3b2590348c](https://linux-hardware.org/?probe=3b2590348c) | Aug 08, 2021 |
| MSI           | FM2-A55M-P33                | [7bb16b9a62](https://linux-hardware.org/?probe=7bb16b9a62) | Aug 08, 2021 |
| MSI           | FM2-A55M-P33                | [5b435fd416](https://linux-hardware.org/?probe=5b435fd416) | Aug 08, 2021 |
| ASRock        | P67 Pro3                    | [3eca7094db](https://linux-hardware.org/?probe=3eca7094db) | Aug 08, 2021 |
| ASRock        | B550M Pro4                  | [7d11767c07](https://linux-hardware.org/?probe=7d11767c07) | Aug 07, 2021 |
| Gigabyte      | H81M-D2V                    | [3ead6919db](https://linux-hardware.org/?probe=3ead6919db) | Aug 07, 2021 |
| ASUSTek       | B85M-G                      | [46cf7b3378](https://linux-hardware.org/?probe=46cf7b3378) | Aug 07, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [a7b9f2665c](https://linux-hardware.org/?probe=a7b9f2665c) | Aug 07, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [51947c0182](https://linux-hardware.org/?probe=51947c0182) | Aug 07, 2021 |
| ASUSTek       | B85M-G                      | [30bbb6c5fe](https://linux-hardware.org/?probe=30bbb6c5fe) | Aug 06, 2021 |
| ASRock        | A785GM-LE                   | [d24d10a97d](https://linux-hardware.org/?probe=d24d10a97d) | Aug 06, 2021 |
| Gigabyte      | Z97P-D3                     | [ae008004cb](https://linux-hardware.org/?probe=ae008004cb) | Aug 06, 2021 |
| Gigabyte      | Z97P-D3                     | [cdc364bde9](https://linux-hardware.org/?probe=cdc364bde9) | Aug 06, 2021 |
| Lenovo        | Board                       | [df033c67a8](https://linux-hardware.org/?probe=df033c67a8) | Aug 06, 2021 |
| ASRock        | X399 Taichi Threadripper... | [25184d24f9](https://linux-hardware.org/?probe=25184d24f9) | Aug 06, 2021 |
| Gigabyte      | GA-78LMT-S2                 | [c9ad48feba](https://linux-hardware.org/?probe=c9ad48feba) | Aug 06, 2021 |
| Gigabyte      | GA-78LMT-S2                 | [2c0d3a0206](https://linux-hardware.org/?probe=2c0d3a0206) | Aug 06, 2021 |
| HP            | 3048h                       | [118dd943bb](https://linux-hardware.org/?probe=118dd943bb) | Aug 06, 2021 |
| ASUSTek       | TUF GAMING H570-PRO         | [990a72e285](https://linux-hardware.org/?probe=990a72e285) | Aug 06, 2021 |
| Lenovo        | 364A SDK0J40709 WIN 3259... | [8a83c9161e](https://linux-hardware.org/?probe=8a83c9161e) | Aug 06, 2021 |
| ASUSTek       | P5N-E SLI                   | [ab314d65be](https://linux-hardware.org/?probe=ab314d65be) | Aug 05, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | [4e0080256a](https://linux-hardware.org/?probe=4e0080256a) | Aug 05, 2021 |
| Gigabyte      | A520 AORUS ELITE            | [1d3167cdf0](https://linux-hardware.org/?probe=1d3167cdf0) | Aug 05, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [90e7e1e008](https://linux-hardware.org/?probe=90e7e1e008) | Aug 05, 2021 |
| HP            | 0B4Ch D                     | [41314c12cb](https://linux-hardware.org/?probe=41314c12cb) | Aug 05, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [789dbf910e](https://linux-hardware.org/?probe=789dbf910e) | Aug 04, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [8ac108e44f](https://linux-hardware.org/?probe=8ac108e44f) | Aug 04, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [9968f2a2cc](https://linux-hardware.org/?probe=9968f2a2cc) | Aug 04, 2021 |
| Pegatron      | 2A94                        | [02959528ba](https://linux-hardware.org/?probe=02959528ba) | Aug 04, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [663d6ee6d1](https://linux-hardware.org/?probe=663d6ee6d1) | Aug 04, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [899877b2fc](https://linux-hardware.org/?probe=899877b2fc) | Aug 03, 2021 |
| Dell          | 0J3C2F A00                  | [f557538404](https://linux-hardware.org/?probe=f557538404) | Aug 03, 2021 |
| Dell          | 0J3C2F A00                  | [54a72c496f](https://linux-hardware.org/?probe=54a72c496f) | Aug 03, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [729ae360b5](https://linux-hardware.org/?probe=729ae360b5) | Aug 03, 2021 |
| HP            | 1495                        | [48e893c344](https://linux-hardware.org/?probe=48e893c344) | Aug 03, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [f19b657d96](https://linux-hardware.org/?probe=f19b657d96) | Aug 03, 2021 |
| Positivo      | POS-EAA75DEA                | [df6385e8c2](https://linux-hardware.org/?probe=df6385e8c2) | Aug 03, 2021 |
| Pegatron      | 2A94                        | [f8aa38fd3c](https://linux-hardware.org/?probe=f8aa38fd3c) | Aug 03, 2021 |
| Dell          | 0KRC95 A00                  | [f8c48b22e6](https://linux-hardware.org/?probe=f8c48b22e6) | Aug 02, 2021 |
| Pegatron      | 2A99                        | [0b2a250ef5](https://linux-hardware.org/?probe=0b2a250ef5) | Aug 02, 2021 |
| Dell          | 0TY565                      | [e2b168eb4f](https://linux-hardware.org/?probe=e2b168eb4f) | Aug 02, 2021 |
| Dell          | 0CRH6C A02                  | [22b20f112a](https://linux-hardware.org/?probe=22b20f112a) | Aug 02, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [dfaac9ebd2](https://linux-hardware.org/?probe=dfaac9ebd2) | Aug 02, 2021 |
| ASUSTek       | PRIME B450M-A               | [dc8f396ad8](https://linux-hardware.org/?probe=dc8f396ad8) | Aug 02, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [50136afddd](https://linux-hardware.org/?probe=50136afddd) | Aug 02, 2021 |
| ASRock        | Z370/OEM                    | [c90b04c55f](https://linux-hardware.org/?probe=c90b04c55f) | Aug 02, 2021 |
| MSI           | H81M-P33                    | [f0164ad102](https://linux-hardware.org/?probe=f0164ad102) | Aug 02, 2021 |
| ASRock        | Z370/OEM                    | [2309a1a720](https://linux-hardware.org/?probe=2309a1a720) | Aug 02, 2021 |
| HP            | 81BB                        | [8de0bb36f6](https://linux-hardware.org/?probe=8de0bb36f6) | Aug 02, 2021 |
| ASUSTek       | Z170-A                      | [e523ad86d2](https://linux-hardware.org/?probe=e523ad86d2) | Aug 02, 2021 |
| HP            | 8860 A                      | [dc4ab2b326](https://linux-hardware.org/?probe=dc4ab2b326) | Aug 02, 2021 |
| ASUSTek       | F2A55-M LK2                 | [b9112336fa](https://linux-hardware.org/?probe=b9112336fa) | Aug 02, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [d7d3f2e504](https://linux-hardware.org/?probe=d7d3f2e504) | Aug 02, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [27e7a22365](https://linux-hardware.org/?probe=27e7a22365) | Aug 02, 2021 |
| Acer          | FQ965M                      | [3b458ed3ee](https://linux-hardware.org/?probe=3b458ed3ee) | Aug 01, 2021 |
| MSI           | Z370M MORTAR                | [503e728a35](https://linux-hardware.org/?probe=503e728a35) | Aug 01, 2021 |
| ASRock        | AM1B-ITX                    | [ef56975d6a](https://linux-hardware.org/?probe=ef56975d6a) | Aug 01, 2021 |
| Gigabyte      | H270-HD3-CF                 | [6e07f08893](https://linux-hardware.org/?probe=6e07f08893) | Jul 31, 2021 |
| HP            | 3648h                       | [b6fa1195a8](https://linux-hardware.org/?probe=b6fa1195a8) | Jul 31, 2021 |
| Gigabyte      | Z170X-UD3-CF                | [43a6598dac](https://linux-hardware.org/?probe=43a6598dac) | Jul 31, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [f832a4e2bd](https://linux-hardware.org/?probe=f832a4e2bd) | Jul 31, 2021 |
| ASUSTek       | PRIME A320M-K               | [2739cf0097](https://linux-hardware.org/?probe=2739cf0097) | Jul 31, 2021 |
| MSI           | Z170I GAMING PRO AC         | [394526363d](https://linux-hardware.org/?probe=394526363d) | Jul 31, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [c0cf2c3569](https://linux-hardware.org/?probe=c0cf2c3569) | Jul 31, 2021 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [5c5afc31a8](https://linux-hardware.org/?probe=5c5afc31a8) | Jul 31, 2021 |
| Lenovo        | Board                       | [c5b678d432](https://linux-hardware.org/?probe=c5b678d432) | Jul 31, 2021 |
| HP            | 3397                        | [2e950b5890](https://linux-hardware.org/?probe=2e950b5890) | Jul 31, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | [d1b088f1ea](https://linux-hardware.org/?probe=d1b088f1ea) | Jul 30, 2021 |
| Dell          | 0CU409                      | [764eeeca37](https://linux-hardware.org/?probe=764eeeca37) | Jul 30, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [a6df82ec75](https://linux-hardware.org/?probe=a6df82ec75) | Jul 30, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | [b33ddef912](https://linux-hardware.org/?probe=b33ddef912) | Jul 30, 2021 |
| Gigabyte      | MZGLKCP-00                  | [4d9f134679](https://linux-hardware.org/?probe=4d9f134679) | Jul 30, 2021 |
| ASUSTek       | M5A97 R2.0                  | [f9fb928d3e](https://linux-hardware.org/?probe=f9fb928d3e) | Jul 30, 2021 |
| ASUSTek       | M5A97 R2.0                  | [31dec7a129](https://linux-hardware.org/?probe=31dec7a129) | Jul 30, 2021 |
| Pegatron      | NARRA5                      | [3cd4dd3cfb](https://linux-hardware.org/?probe=3cd4dd3cfb) | Jul 30, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [2e4ee891ef](https://linux-hardware.org/?probe=2e4ee891ef) | Jul 30, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [1668dbb683](https://linux-hardware.org/?probe=1668dbb683) | Jul 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | [b2baf5a1da](https://linux-hardware.org/?probe=b2baf5a1da) | Jul 30, 2021 |
| Gigabyte      | M720-US3                    | [869cada120](https://linux-hardware.org/?probe=869cada120) | Jul 30, 2021 |
| Pegatron      | 2A99                        | [e295022426](https://linux-hardware.org/?probe=e295022426) | Jul 29, 2021 |
| Pegatron      | 2A99                        | [7fd0d73ccb](https://linux-hardware.org/?probe=7fd0d73ccb) | Jul 29, 2021 |
| Lenovo        | Board                       | [cf7f13e31c](https://linux-hardware.org/?probe=cf7f13e31c) | Jul 29, 2021 |
| Wibtek        | TH61G-S                     | [346ae2c85d](https://linux-hardware.org/?probe=346ae2c85d) | Jul 29, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [30deafe351](https://linux-hardware.org/?probe=30deafe351) | Jul 29, 2021 |
| ASRock        | FM2A58M-VG3+ R2.0           | [eaf0b17f45](https://linux-hardware.org/?probe=eaf0b17f45) | Jul 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [60b58b4557](https://linux-hardware.org/?probe=60b58b4557) | Jul 28, 2021 |
| ASUSTek       | P6X58D-E                    | [bd3b6b4f35](https://linux-hardware.org/?probe=bd3b6b4f35) | Jul 28, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [bc9a454567](https://linux-hardware.org/?probe=bc9a454567) | Jul 28, 2021 |
| ASRock        | P67 Pro3                    | [75da5ecc21](https://linux-hardware.org/?probe=75da5ecc21) | Jul 28, 2021 |
| Gigabyte      | B75M-D3V                    | [22361fb7c3](https://linux-hardware.org/?probe=22361fb7c3) | Jul 28, 2021 |
| MSI           | A320M-A PRO MAX             | [4772eaea38](https://linux-hardware.org/?probe=4772eaea38) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | [7fa4a7bf63](https://linux-hardware.org/?probe=7fa4a7bf63) | Jul 28, 2021 |
| Dell          | 0PU052                      | [32e63791d3](https://linux-hardware.org/?probe=32e63791d3) | Jul 27, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [ec43c09d85](https://linux-hardware.org/?probe=ec43c09d85) | Jul 27, 2021 |
| Dell          | 0PU052                      | [dcd01a391b](https://linux-hardware.org/?probe=dcd01a391b) | Jul 27, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [7264a53eae](https://linux-hardware.org/?probe=7264a53eae) | Jul 27, 2021 |
| Medion        | MS-7616                     | [699c5f366b](https://linux-hardware.org/?probe=699c5f366b) | Jul 27, 2021 |
| ASUSTek       | M4A88T-V EVO/USB3           | [30b94a4a43](https://linux-hardware.org/?probe=30b94a4a43) | Jul 27, 2021 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [981d5abb8a](https://linux-hardware.org/?probe=981d5abb8a) | Jul 27, 2021 |
| Gigabyte      | GA-78LMT-S2                 | [779731fc55](https://linux-hardware.org/?probe=779731fc55) | Jul 27, 2021 |
| Foxconn       | 2A8C                        | [c545107086](https://linux-hardware.org/?probe=c545107086) | Jul 27, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | [b1bfe26b42](https://linux-hardware.org/?probe=b1bfe26b42) | Jul 27, 2021 |
| Gigabyte      | A320M-S2H-CF                | [a3a628077f](https://linux-hardware.org/?probe=a3a628077f) | Jul 27, 2021 |
| Gigabyte      | H97M-DS3P                   | [5729ed1586](https://linux-hardware.org/?probe=5729ed1586) | Jul 26, 2021 |
| MSI           | Z97 GAMING 3                | [a5cc51aec1](https://linux-hardware.org/?probe=a5cc51aec1) | Jul 26, 2021 |
| HP            | 2B34                        | [ff2d39838e](https://linux-hardware.org/?probe=ff2d39838e) | Jul 26, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [cd88f96d38](https://linux-hardware.org/?probe=cd88f96d38) | Jul 26, 2021 |
| ASRock        | G41M-VS                     | [fbdfda41ad](https://linux-hardware.org/?probe=fbdfda41ad) | Jul 26, 2021 |
| ASRock        | G41M-VS                     | [e128037a00](https://linux-hardware.org/?probe=e128037a00) | Jul 26, 2021 |
| ASUSTek       | PRIME X570-P                | [edc90bacea](https://linux-hardware.org/?probe=edc90bacea) | Jul 25, 2021 |
| ASRock        | A785GM-LE                   | [ae9761461e](https://linux-hardware.org/?probe=ae9761461e) | Jul 25, 2021 |
| Megaware      | MW-G31T-M7                  | [ec17ba1097](https://linux-hardware.org/?probe=ec17ba1097) | Jul 25, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [8f6e1f1929](https://linux-hardware.org/?probe=8f6e1f1929) | Jul 25, 2021 |
| ASUSTek       | Z87-C                       | [02864b35ef](https://linux-hardware.org/?probe=02864b35ef) | Jul 25, 2021 |
| Megaware      | MW-G31T-M7                  | [26b3423579](https://linux-hardware.org/?probe=26b3423579) | Jul 25, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [d8bbd9a390](https://linux-hardware.org/?probe=d8bbd9a390) | Jul 25, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [fcc85782f6](https://linux-hardware.org/?probe=fcc85782f6) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [637cd40ba1](https://linux-hardware.org/?probe=637cd40ba1) | Jul 25, 2021 |
| ASRock        | B450M-HDV R4.0              | [0c95ca38e6](https://linux-hardware.org/?probe=0c95ca38e6) | Jul 25, 2021 |
| Megaware      | MW-G31T-M7                  | [5560d1c8a7](https://linux-hardware.org/?probe=5560d1c8a7) | Jul 24, 2021 |
| Megaware      | MW-G31T-M7                  | [eb823ab488](https://linux-hardware.org/?probe=eb823ab488) | Jul 24, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [c992c52bbe](https://linux-hardware.org/?probe=c992c52bbe) | Jul 24, 2021 |
| MSI           | B550-A PRO                  | [5abb0ed3c3](https://linux-hardware.org/?probe=5abb0ed3c3) | Jul 24, 2021 |
| ASRock        | X299 Taichi CLX             | [6a7082a749](https://linux-hardware.org/?probe=6a7082a749) | Jul 24, 2021 |
| Gigabyte      | 970A-DS3P                   | [bf73ea51b4](https://linux-hardware.org/?probe=bf73ea51b4) | Jul 24, 2021 |
| MSI           | B360-A PRO                  | [91540c6fa9](https://linux-hardware.org/?probe=91540c6fa9) | Jul 24, 2021 |
| Gigabyte      | H81M-D2V                    | [7fad6271d8](https://linux-hardware.org/?probe=7fad6271d8) | Jul 24, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [a2263d14f1](https://linux-hardware.org/?probe=a2263d14f1) | Jul 24, 2021 |
| ASUSTek       | P7H55                       | [44103309b6](https://linux-hardware.org/?probe=44103309b6) | Jul 24, 2021 |
| Gigabyte      | A320M-S2H-CF                | [98064b8e44](https://linux-hardware.org/?probe=98064b8e44) | Jul 24, 2021 |
| ASUSTek       | VC68V                       | [b6beb475b5](https://linux-hardware.org/?probe=b6beb475b5) | Jul 23, 2021 |
| ASUSTek       | P8B75-M LE                  | [e71a7fc65b](https://linux-hardware.org/?probe=e71a7fc65b) | Jul 23, 2021 |
| HP            | ProLiant ML350 G5           | [189789f8d5](https://linux-hardware.org/?probe=189789f8d5) | Jul 23, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | [e2953ddd9b](https://linux-hardware.org/?probe=e2953ddd9b) | Jul 23, 2021 |
| ECS           | G41T-M12                    | [bc6dbc46b6](https://linux-hardware.org/?probe=bc6dbc46b6) | Jul 23, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [85e81471c1](https://linux-hardware.org/?probe=85e81471c1) | Jul 22, 2021 |
| Gigabyte      | Z270X-Gaming K5             | [384c090a20](https://linux-hardware.org/?probe=384c090a20) | Jul 22, 2021 |
| Dell          | 0U880P A00                  | [2b44408767](https://linux-hardware.org/?probe=2b44408767) | Jul 22, 2021 |
| ASUSTek       | PRIME B350M-A               | [ae20cffdb3](https://linux-hardware.org/?probe=ae20cffdb3) | Jul 22, 2021 |
| Gigabyte      | H87M-D3H                    | [176a2484a2](https://linux-hardware.org/?probe=176a2484a2) | Jul 22, 2021 |
| Dell          | 0U880P A00                  | [caa82e88eb](https://linux-hardware.org/?probe=caa82e88eb) | Jul 22, 2021 |
| Gigabyte      | C1037UN-EU                  | [7dd534813a](https://linux-hardware.org/?probe=7dd534813a) | Jul 22, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [788a72e391](https://linux-hardware.org/?probe=788a72e391) | Jul 22, 2021 |
| ASUSTek       | P7F-X Series                | [1c7f2450cf](https://linux-hardware.org/?probe=1c7f2450cf) | Jul 22, 2021 |
| Gigabyte      | M4HM87P-00                  | [391325a409](https://linux-hardware.org/?probe=391325a409) | Jul 21, 2021 |
| ASUSTek       | CG1330                      | [2b6f11985e](https://linux-hardware.org/?probe=2b6f11985e) | Jul 21, 2021 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [954356dcd4](https://linux-hardware.org/?probe=954356dcd4) | Jul 21, 2021 |
| Intel         | DH61WW AAG23116-206         | [bdd8ae093d](https://linux-hardware.org/?probe=bdd8ae093d) | Jul 21, 2021 |
| ASUSTek       | PRIME X570-P                | [8556b83d79](https://linux-hardware.org/?probe=8556b83d79) | Jul 21, 2021 |
| HP            | 304Ah                       | [5642b38035](https://linux-hardware.org/?probe=5642b38035) | Jul 21, 2021 |
| Gigabyte      | M4HM87P-00                  | [344ceb47d4](https://linux-hardware.org/?probe=344ceb47d4) | Jul 20, 2021 |
| Foxconn       | H61MXT1/F2/-S/-V            | [cf7ebc455f](https://linux-hardware.org/?probe=cf7ebc455f) | Jul 20, 2021 |
| HP            | 876C SMVB                   | [a6957d7b79](https://linux-hardware.org/?probe=a6957d7b79) | Jul 20, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | [07374c75c8](https://linux-hardware.org/?probe=07374c75c8) | Jul 20, 2021 |
| AMI           | Cherry Trail CR             | [a27b2da2b9](https://linux-hardware.org/?probe=a27b2da2b9) | Jul 20, 2021 |
| ASRock        | B560M-ITX/ac                | [9305966b39](https://linux-hardware.org/?probe=9305966b39) | Jul 20, 2021 |
| HP            | 3048h                       | [3cf7fd4875](https://linux-hardware.org/?probe=3cf7fd4875) | Jul 20, 2021 |
| ASUSTek       | B85-PLUS                    | [a417ccc064](https://linux-hardware.org/?probe=a417ccc064) | Jul 20, 2021 |
| ASRock        | H110M-ITX                   | [7572a3a8a8](https://linux-hardware.org/?probe=7572a3a8a8) | Jul 20, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | [ca12d4a766](https://linux-hardware.org/?probe=ca12d4a766) | Jul 19, 2021 |
| MSI           | G41M-P23                    | [8d936f75c2](https://linux-hardware.org/?probe=8d936f75c2) | Jul 19, 2021 |
| Dell          | 0GM819                      | [4702931d5a](https://linux-hardware.org/?probe=4702931d5a) | Jul 19, 2021 |
| Unknown       | Phitronics H55-M            | [e112ab1467](https://linux-hardware.org/?probe=e112ab1467) | Jul 19, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [c74efec985](https://linux-hardware.org/?probe=c74efec985) | Jul 19, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [f410d6449b](https://linux-hardware.org/?probe=f410d6449b) | Jul 19, 2021 |
| MSI           | H81M-P33                    | [8db8179a0e](https://linux-hardware.org/?probe=8db8179a0e) | Jul 19, 2021 |
| Dell          | 00V62H A00                  | [59e8d7d296](https://linux-hardware.org/?probe=59e8d7d296) | Jul 19, 2021 |
| HP            | 3048h                       | [84d3c8325c](https://linux-hardware.org/?probe=84d3c8325c) | Jul 19, 2021 |
| Dell          | 0KWVT8 A02                  | [fc921e0ff7](https://linux-hardware.org/?probe=fc921e0ff7) | Jul 19, 2021 |
| Gigabyte      | H81M-S2H                    | [b16f7a7008](https://linux-hardware.org/?probe=b16f7a7008) | Jul 18, 2021 |
| HP            | 1495                        | [f2affe9c46](https://linux-hardware.org/?probe=f2affe9c46) | Jul 18, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [55114a067a](https://linux-hardware.org/?probe=55114a067a) | Jul 18, 2021 |
| ASUSTek       | M5A78L-M LX                 | [bf2209afbd](https://linux-hardware.org/?probe=bf2209afbd) | Jul 18, 2021 |
| Gigabyte      | A55M-DS2                    | [6144ed6dc1](https://linux-hardware.org/?probe=6144ed6dc1) | Jul 18, 2021 |
| HP            | 3047h                       | [58b480757e](https://linux-hardware.org/?probe=58b480757e) | Jul 18, 2021 |
| HP            | 3047h                       | [40a25f223c](https://linux-hardware.org/?probe=40a25f223c) | Jul 18, 2021 |
| ASRock        | B550M Pro4                  | [dc9d069225](https://linux-hardware.org/?probe=dc9d069225) | Jul 17, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [c332ee495e](https://linux-hardware.org/?probe=c332ee495e) | Jul 17, 2021 |
| Gigabyte      | Z77X-UD5H                   | [950221d4df](https://linux-hardware.org/?probe=950221d4df) | Jul 17, 2021 |
| Dell          | 04MFRM A02                  | [9d92f05e1c](https://linux-hardware.org/?probe=9d92f05e1c) | Jul 17, 2021 |
| HP            | 0A64h                       | [d4ac71b4a9](https://linux-hardware.org/?probe=d4ac71b4a9) | Jul 17, 2021 |
| Dell          | 04MFRM A02                  | [2b2a31a2f9](https://linux-hardware.org/?probe=2b2a31a2f9) | Jul 17, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [96c690a9aa](https://linux-hardware.org/?probe=96c690a9aa) | Jul 17, 2021 |
| eMachines     | EL1352                      | [83c494c15a](https://linux-hardware.org/?probe=83c494c15a) | Jul 17, 2021 |
| eMachines     | EL1360G                     | [fbc45e7ee4](https://linux-hardware.org/?probe=fbc45e7ee4) | Jul 16, 2021 |
| Dell          | 0XFWHV A01                  | [eaca4fc677](https://linux-hardware.org/?probe=eaca4fc677) | Jul 16, 2021 |
| Dell          | 0XFWHV A01                  | [ab423517d2](https://linux-hardware.org/?probe=ab423517d2) | Jul 16, 2021 |
| ASRock        | Z170 Gaming K4              | [7cbfec1381](https://linux-hardware.org/?probe=7cbfec1381) | Jul 16, 2021 |
| Gigabyte      | H510M H                     | [70f8b94923](https://linux-hardware.org/?probe=70f8b94923) | Jul 16, 2021 |
| eMachines     | WMCP61M                     | [93d91a0c0f](https://linux-hardware.org/?probe=93d91a0c0f) | Jul 16, 2021 |
| Gigabyte      | Z68X-UD3-B3                 | [0c0d9cc784](https://linux-hardware.org/?probe=0c0d9cc784) | Jul 15, 2021 |
| HP            | 3047h                       | [9e162f2640](https://linux-hardware.org/?probe=9e162f2640) | Jul 15, 2021 |
| Gigabyte      | Z390 M-CF                   | [25bb94e5f8](https://linux-hardware.org/?probe=25bb94e5f8) | Jul 15, 2021 |
| ASRock        | AM1B-ITX                    | [e8ace7a485](https://linux-hardware.org/?probe=e8ace7a485) | Jul 15, 2021 |
| Fujitsu Si... | MS-7504VP-PV                | [08f61af652](https://linux-hardware.org/?probe=08f61af652) | Jul 15, 2021 |
| Fujitsu Si... | MS-7504VP-PV                | [7b4081a5e1](https://linux-hardware.org/?probe=7b4081a5e1) | Jul 15, 2021 |
| ASUSTek       | PRIME B550M-A               | [4ec6b2f316](https://linux-hardware.org/?probe=4ec6b2f316) | Jul 14, 2021 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [78c6172b28](https://linux-hardware.org/?probe=78c6172b28) | Jul 14, 2021 |
| ASRock        | A785GM-LE                   | [109e164e89](https://linux-hardware.org/?probe=109e164e89) | Jul 14, 2021 |
| ASRock        | A785GM-LE                   | [b4c578b25e](https://linux-hardware.org/?probe=b4c578b25e) | Jul 14, 2021 |
| ASRock        | A785GM-LE                   | [0b105670a6](https://linux-hardware.org/?probe=0b105670a6) | Jul 14, 2021 |
| Gigabyte      | G31M-ES2L                   | [e7f4574c32](https://linux-hardware.org/?probe=e7f4574c32) | Jul 14, 2021 |
| Dell          | 0PC5F7 A02                  | [22292958a8](https://linux-hardware.org/?probe=22292958a8) | Jul 13, 2021 |
| Intel         | DG31PR AAD97573-306         | [ee8e9f3477](https://linux-hardware.org/?probe=ee8e9f3477) | Jul 13, 2021 |
| Intel         | DG41RQ AAE54511-203         | [eb654e1891](https://linux-hardware.org/?probe=eb654e1891) | Jul 13, 2021 |
| Gigabyte      | Z390 M-CF                   | [43d62b80af](https://linux-hardware.org/?probe=43d62b80af) | Jul 13, 2021 |
| Gigabyte      | B450M S2H                   | [643e83a867](https://linux-hardware.org/?probe=643e83a867) | Jul 13, 2021 |
| Biostar       | GF8200C M2+                 | [a7dfa10668](https://linux-hardware.org/?probe=a7dfa10668) | Jul 13, 2021 |
| ASUSTek       | TUF X299 MARK 2             | [d3f2c6d8d8](https://linux-hardware.org/?probe=d3f2c6d8d8) | Jul 13, 2021 |
| AWOW          | AK41                        | [9957ef3d80](https://linux-hardware.org/?probe=9957ef3d80) | Jul 13, 2021 |
| Intel         | MAHOBAY                     | [26404de5f4](https://linux-hardware.org/?probe=26404de5f4) | Jul 13, 2021 |
| HP            | 8054                        | [0263cc00da](https://linux-hardware.org/?probe=0263cc00da) | Jul 13, 2021 |
| Gigabyte      | M57SLI-S4                   | [456981cfae](https://linux-hardware.org/?probe=456981cfae) | Jul 12, 2021 |
| MSI           | H510M PRO                   | [b7df6ff27a](https://linux-hardware.org/?probe=b7df6ff27a) | Jul 12, 2021 |
| ASUSTek       | PRIME Z490-A                | [6beb6389bd](https://linux-hardware.org/?probe=6beb6389bd) | Jul 12, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [ed898ef0c6](https://linux-hardware.org/?probe=ed898ef0c6) | Jul 12, 2021 |
| ASRock        | B450M Pro4-F                | [b8a9b28642](https://linux-hardware.org/?probe=b8a9b28642) | Jul 11, 2021 |
| Intel         | B75                         | [d1b42d8c46](https://linux-hardware.org/?probe=d1b42d8c46) | Jul 11, 2021 |
| Dell          | 0J3C2F A00                  | [0f3e3f5e8e](https://linux-hardware.org/?probe=0f3e3f5e8e) | Jul 11, 2021 |
| ASRock        | P67 Pro3                    | [f2c66dab20](https://linux-hardware.org/?probe=f2c66dab20) | Jul 11, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5320824c78](https://linux-hardware.org/?probe=5320824c78) | Jul 11, 2021 |
| Dell          | 0RY007                      | [c49f9f065b](https://linux-hardware.org/?probe=c49f9f065b) | Jul 11, 2021 |
| Acer          | WMCP78M                     | [3c4134e3b4](https://linux-hardware.org/?probe=3c4134e3b4) | Jul 11, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [e2b0276cb9](https://linux-hardware.org/?probe=e2b0276cb9) | Jul 11, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [4b9b3916a7](https://linux-hardware.org/?probe=4b9b3916a7) | Jul 11, 2021 |
| Dell          | 06X1TJ A00                  | [942e69cf0e](https://linux-hardware.org/?probe=942e69cf0e) | Jul 11, 2021 |
| Dell          | 0RY007                      | [e075d2058a](https://linux-hardware.org/?probe=e075d2058a) | Jul 11, 2021 |
| ASUSTek       | PRIME B450M-K II            | [ac44464839](https://linux-hardware.org/?probe=ac44464839) | Jul 10, 2021 |
| ABIT          | AB9/AB9RPO                  | [5a0105e477](https://linux-hardware.org/?probe=5a0105e477) | Jul 10, 2021 |
| ASRock        | FP6D4-P1                    | [39f04ec538](https://linux-hardware.org/?probe=39f04ec538) | Jul 10, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [aabd4b96a3](https://linux-hardware.org/?probe=aabd4b96a3) | Jul 10, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [1517e70f66](https://linux-hardware.org/?probe=1517e70f66) | Jul 09, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [9b058a0abc](https://linux-hardware.org/?probe=9b058a0abc) | Jul 09, 2021 |
| ABIT          | AB9/AB9RPO                  | [10757e3d6f](https://linux-hardware.org/?probe=10757e3d6f) | Jul 09, 2021 |
| Seco          | C40 C                       | [ee840f7fd7](https://linux-hardware.org/?probe=ee840f7fd7) | Jul 09, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [36ef771a7b](https://linux-hardware.org/?probe=36ef771a7b) | Jul 09, 2021 |
| Seco          | C40 C                       | [222cca6c0b](https://linux-hardware.org/?probe=222cca6c0b) | Jul 09, 2021 |
| Huanan        | X79 249PC V2.2              | [82d15f27b4](https://linux-hardware.org/?probe=82d15f27b4) | Jul 09, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1837a96347](https://linux-hardware.org/?probe=1837a96347) | Jul 09, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [08882d835c](https://linux-hardware.org/?probe=08882d835c) | Jul 09, 2021 |
| Gigabyte      | B75M-D3V                    | [b77857df6b](https://linux-hardware.org/?probe=b77857df6b) | Jul 09, 2021 |
| HP            | 158A                        | [e201a5d028](https://linux-hardware.org/?probe=e201a5d028) | Jul 09, 2021 |
| MSI           | A55M-P33                    | [14d441e76a](https://linux-hardware.org/?probe=14d441e76a) | Jul 09, 2021 |
| ASRock        | B450M-HDV                   | [a642e5421d](https://linux-hardware.org/?probe=a642e5421d) | Jul 08, 2021 |
| Intel         | X79 V2.72B                  | [76de006d28](https://linux-hardware.org/?probe=76de006d28) | Jul 08, 2021 |
| ASRock        | B450M-HDV                   | [5b75337fc1](https://linux-hardware.org/?probe=5b75337fc1) | Jul 08, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.309     | [2f851e91cc](https://linux-hardware.org/?probe=2f851e91cc) | Jul 08, 2021 |
| HP            | 3047h                       | [e78150909f](https://linux-hardware.org/?probe=e78150909f) | Jul 08, 2021 |
| HP            | 212B                        | [150ca5d868](https://linux-hardware.org/?probe=150ca5d868) | Jul 08, 2021 |
| HP            | 2820h                       | [d67ecf5ce3](https://linux-hardware.org/?probe=d67ecf5ce3) | Jul 08, 2021 |
| HP            | 3397                        | [f1a6d10d78](https://linux-hardware.org/?probe=f1a6d10d78) | Jul 08, 2021 |
| HP            | 3397                        | [e087e03e0b](https://linux-hardware.org/?probe=e087e03e0b) | Jul 08, 2021 |
| ASUSTek       | PRIME Z370-P                | [7d52893b40](https://linux-hardware.org/?probe=7d52893b40) | Jul 08, 2021 |
| ASRock        | Z170 Pro4/D3                | [073c40fe0a](https://linux-hardware.org/?probe=073c40fe0a) | Jul 07, 2021 |
| Gigabyte      | 945GCM-S2L                  | [2c711e3bf8](https://linux-hardware.org/?probe=2c711e3bf8) | Jul 07, 2021 |
| Gigabyte      | 945GCM-S2L                  | [1fab2ca125](https://linux-hardware.org/?probe=1fab2ca125) | Jul 07, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [8c62fbb1d6](https://linux-hardware.org/?probe=8c62fbb1d6) | Jul 07, 2021 |
| ASUSTek       | PRIME X370-PRO              | [8c319e19f9](https://linux-hardware.org/?probe=8c319e19f9) | Jul 07, 2021 |
| MSI           | H170 GAMING M3              | [664dcbec03](https://linux-hardware.org/?probe=664dcbec03) | Jul 07, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [e3ee4893c9](https://linux-hardware.org/?probe=e3ee4893c9) | Jul 07, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [5ecd5863a5](https://linux-hardware.org/?probe=5ecd5863a5) | Jul 07, 2021 |
| ASUSTek       | H81M-K                      | [899763af49](https://linux-hardware.org/?probe=899763af49) | Jul 07, 2021 |
| Intel         | H61                         | [fae896fa93](https://linux-hardware.org/?probe=fae896fa93) | Jul 07, 2021 |
| ASRock        | P67 Pro3                    | [0a78c8bdc4](https://linux-hardware.org/?probe=0a78c8bdc4) | Jul 06, 2021 |
| ASRock        | 970M Pro3                   | [ef6d729144](https://linux-hardware.org/?probe=ef6d729144) | Jul 06, 2021 |
| Dell          | 0PC5F7 A02                  | [69010b3987](https://linux-hardware.org/?probe=69010b3987) | Jul 06, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a8c5113f4c](https://linux-hardware.org/?probe=a8c5113f4c) | Jul 06, 2021 |
| ASUSTek       | M5A78L-M LX3                | [8ee329f5cf](https://linux-hardware.org/?probe=8ee329f5cf) | Jul 05, 2021 |
| Dell          | 0TP406                      | [23a9dae189](https://linux-hardware.org/?probe=23a9dae189) | Jul 05, 2021 |
| ASRock        | 970M Pro3                   | [01db849422](https://linux-hardware.org/?probe=01db849422) | Jul 05, 2021 |
| ASRock        | FM2A55M-DGS                 | [fdc648f3e4](https://linux-hardware.org/?probe=fdc648f3e4) | Jul 05, 2021 |
| ASUSTek       | H81M-K                      | [9d12a5bba7](https://linux-hardware.org/?probe=9d12a5bba7) | Jul 05, 2021 |
| Acer          | Aspire TC-710 V:1.1         | [5813b68553](https://linux-hardware.org/?probe=5813b68553) | Jul 05, 2021 |
| Biostar       | A960D+                      | [ffb05113af](https://linux-hardware.org/?probe=ffb05113af) | Jul 04, 2021 |
| Gigabyte      | P35-DS3                     | [1756b98ff7](https://linux-hardware.org/?probe=1756b98ff7) | Jul 04, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [40e854d2c2](https://linux-hardware.org/?probe=40e854d2c2) | Jul 04, 2021 |
| Dell          | 0VD5HY A07                  | [398ee87d95](https://linux-hardware.org/?probe=398ee87d95) | Jul 04, 2021 |
| Dell          | 0VD5HY A07                  | [0fa3ef38f2](https://linux-hardware.org/?probe=0fa3ef38f2) | Jul 04, 2021 |
| ASRock        | H110M-DGS                   | [1439cc6a27](https://linux-hardware.org/?probe=1439cc6a27) | Jul 04, 2021 |
| Dell          | 06X1TJ A00                  | [bdd432febf](https://linux-hardware.org/?probe=bdd432febf) | Jul 04, 2021 |
| ASUSTek       | PRIME B450M-A II            | [6bb44a16ec](https://linux-hardware.org/?probe=6bb44a16ec) | Jul 04, 2021 |
| HP            | 805B                        | [5d5a6504aa](https://linux-hardware.org/?probe=5d5a6504aa) | Jul 03, 2021 |
| HP            | 805B                        | [83f501a4c5](https://linux-hardware.org/?probe=83f501a4c5) | Jul 03, 2021 |
| Dell          | 06X1TJ A00                  | [49b9a37043](https://linux-hardware.org/?probe=49b9a37043) | Jul 03, 2021 |
| Dell          | 0T0MHW A03                  | [93513b1c6b](https://linux-hardware.org/?probe=93513b1c6b) | Jul 03, 2021 |
| Gigabyte      | H57M-USB3                   | [56faab06ce](https://linux-hardware.org/?probe=56faab06ce) | Jul 03, 2021 |
| ASUSTek       | P8Z77-M                     | [77f78fba9c](https://linux-hardware.org/?probe=77f78fba9c) | Jul 03, 2021 |
| Dell          | 0GM819                      | [03375c12d1](https://linux-hardware.org/?probe=03375c12d1) | Jul 03, 2021 |
| AWOW          | AK41                        | [6d00f44a82](https://linux-hardware.org/?probe=6d00f44a82) | Jul 03, 2021 |
| ASUSTek       | P8Z68-V GEN3                | [ca23fa50aa](https://linux-hardware.org/?probe=ca23fa50aa) | Jul 02, 2021 |
| ASUSTek       | P8Z68-V GEN3                | [b89322de2e](https://linux-hardware.org/?probe=b89322de2e) | Jul 02, 2021 |
| ASUSTek       | M4N78-AM V2                 | [b756564b9b](https://linux-hardware.org/?probe=b756564b9b) | Jul 02, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [647b8b3725](https://linux-hardware.org/?probe=647b8b3725) | Jul 02, 2021 |
| Foxconn       | 2ABF                        | [b54459c5ca](https://linux-hardware.org/?probe=b54459c5ca) | Jul 01, 2021 |
| Lenovo        | 102F SDK0Q40112 WIN 3305... | [ee44b0781f](https://linux-hardware.org/?probe=ee44b0781f) | Jul 01, 2021 |
| ASUSTek       | PRIME B460M-A               | [2690174808](https://linux-hardware.org/?probe=2690174808) | Jul 01, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [a87404851f](https://linux-hardware.org/?probe=a87404851f) | Jul 01, 2021 |
| Dell          | 0GM819                      | [b7dd22633c](https://linux-hardware.org/?probe=b7dd22633c) | Jul 01, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [05a19759e5](https://linux-hardware.org/?probe=05a19759e5) | Jul 01, 2021 |
| Dell          | 0K068D A00                  | [63a723c1c1](https://linux-hardware.org/?probe=63a723c1c1) | Jul 01, 2021 |
| MSI           | X470 GAMING PLUS            | [20a5479774](https://linux-hardware.org/?probe=20a5479774) | Jul 01, 2021 |
| ECS           | Livermore                   | [b471a4666c](https://linux-hardware.org/?probe=b471a4666c) | Jun 30, 2021 |
| HP            | ProLiant ML350 G5           | [bc362bd630](https://linux-hardware.org/?probe=bc362bd630) | Jun 30, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [fe1e020c07](https://linux-hardware.org/?probe=fe1e020c07) | Jun 30, 2021 |
| ASUSTek       | PRIME X570-P                | [3038908567](https://linux-hardware.org/?probe=3038908567) | Jun 30, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | [d56325b68b](https://linux-hardware.org/?probe=d56325b68b) | Jun 30, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | [01a3fb2374](https://linux-hardware.org/?probe=01a3fb2374) | Jun 30, 2021 |
| Gigabyte      | B550M AORUS PRO             | [48ba8ef510](https://linux-hardware.org/?probe=48ba8ef510) | Jun 30, 2021 |
| Dell          | 0GX297                      | [f4debf994a](https://linux-hardware.org/?probe=f4debf994a) | Jun 30, 2021 |
| ASUSTek       | P5G41T-M                    | [8553d8a919](https://linux-hardware.org/?probe=8553d8a919) | Jun 30, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [1032d8b0ff](https://linux-hardware.org/?probe=1032d8b0ff) | Jun 29, 2021 |
| Foxconn       | 2ADA                        | [8d69e315a0](https://linux-hardware.org/?probe=8d69e315a0) | Jun 29, 2021 |
| Gigabyte      | B550M AORUS PRO             | [d4abd4fd4b](https://linux-hardware.org/?probe=d4abd4fd4b) | Jun 29, 2021 |
| ASUSTek       | PRIME Z490-A                | [1c6a743206](https://linux-hardware.org/?probe=1c6a743206) | Jun 29, 2021 |
| ASUSTek       | PRIME Z490-A                | [4d72cf33ac](https://linux-hardware.org/?probe=4d72cf33ac) | Jun 29, 2021 |
| Positivo      | POS-MIG31AG                 | [da99cedbef](https://linux-hardware.org/?probe=da99cedbef) | Jun 29, 2021 |
| Gigabyte      | P41-ES3G                    | [653a634621](https://linux-hardware.org/?probe=653a634621) | Jun 29, 2021 |
| ECS           | G31T-M9                     | [e1952ea77b](https://linux-hardware.org/?probe=e1952ea77b) | Jun 28, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [7a01d3d232](https://linux-hardware.org/?probe=7a01d3d232) | Jun 28, 2021 |
| Gigabyte      | GA-MA770-UD3                | [34d2885e24](https://linux-hardware.org/?probe=34d2885e24) | Jun 28, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7926c787f0](https://linux-hardware.org/?probe=7926c787f0) | Jun 28, 2021 |
| ECS           | G31T-M9                     | [acb1983b65](https://linux-hardware.org/?probe=acb1983b65) | Jun 27, 2021 |
| Dell          | 0XCR8D A03                  | [477c292f7f](https://linux-hardware.org/?probe=477c292f7f) | Jun 27, 2021 |
| Dell          | 0XCR8D A03                  | [0005b71b18](https://linux-hardware.org/?probe=0005b71b18) | Jun 27, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [c527888e95](https://linux-hardware.org/?probe=c527888e95) | Jun 27, 2021 |
| Lenovo        | 31900058 STD                | [50c94838b6](https://linux-hardware.org/?probe=50c94838b6) | Jun 27, 2021 |
| Gigabyte      | F2A88XM-DS2                 | [88f3b44a11](https://linux-hardware.org/?probe=88f3b44a11) | Jun 27, 2021 |
| Gigabyte      | H310M S2 x.x                | [dcb24fa810](https://linux-hardware.org/?probe=dcb24fa810) | Jun 27, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [f8d0d022fc](https://linux-hardware.org/?probe=f8d0d022fc) | Jun 27, 2021 |
| HP            | 8265                        | [a4104f0cbc](https://linux-hardware.org/?probe=a4104f0cbc) | Jun 26, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [409a0b5ee7](https://linux-hardware.org/?probe=409a0b5ee7) | Jun 26, 2021 |
| Gigabyte      | Z490 UD                     | [f564cbb6e0](https://linux-hardware.org/?probe=f564cbb6e0) | Jun 26, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | [d83849dff9](https://linux-hardware.org/?probe=d83849dff9) | Jun 26, 2021 |
| Lenovo        | 31900058 STD                | [338127e8ca](https://linux-hardware.org/?probe=338127e8ca) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [783cc8aa8e](https://linux-hardware.org/?probe=783cc8aa8e) | Jun 26, 2021 |
| MSI           | B75A-G43                    | [b251de3cbc](https://linux-hardware.org/?probe=b251de3cbc) | Jun 26, 2021 |
| MSI           | MS-7276                     | [b83bec578b](https://linux-hardware.org/?probe=b83bec578b) | Jun 26, 2021 |
| Acer          | Veriton M275                | [78aa035121](https://linux-hardware.org/?probe=78aa035121) | Jun 26, 2021 |
| Acer          | Veriton M275                | [e201ab6c1f](https://linux-hardware.org/?probe=e201ab6c1f) | Jun 26, 2021 |
| ASUSTek       | Z97-P                       | [95fcf3868f](https://linux-hardware.org/?probe=95fcf3868f) | Jun 26, 2021 |
| MSI           | B75A-G43                    | [db8082eb27](https://linux-hardware.org/?probe=db8082eb27) | Jun 26, 2021 |
| Gigabyte      | GA-970A-UD3                 | [134c59d2f0](https://linux-hardware.org/?probe=134c59d2f0) | Jun 25, 2021 |
| Gigabyte      | A320M-S2H-CF                | [55add6730f](https://linux-hardware.org/?probe=55add6730f) | Jun 25, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c7684068c8](https://linux-hardware.org/?probe=c7684068c8) | Jun 25, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [ea812bcd70](https://linux-hardware.org/?probe=ea812bcd70) | Jun 25, 2021 |
| Pegatron      | 2A94                        | [670987b884](https://linux-hardware.org/?probe=670987b884) | Jun 24, 2021 |
| Dell          | 04GJJT A00                  | [9c3ea60a02](https://linux-hardware.org/?probe=9c3ea60a02) | Jun 24, 2021 |
| ASRock        | B365M Pro4                  | [11a1841863](https://linux-hardware.org/?probe=11a1841863) | Jun 24, 2021 |
| Dell          | 04GJJT A00                  | [71193d62e3](https://linux-hardware.org/?probe=71193d62e3) | Jun 24, 2021 |
| Dell          | 0F6X5P A00                  | [a08f695bff](https://linux-hardware.org/?probe=a08f695bff) | Jun 23, 2021 |
| ASUSTek       | M2N-MX                      | [b5def43240](https://linux-hardware.org/?probe=b5def43240) | Jun 23, 2021 |
| Gigabyte      | 970A-D3P                    | [5481a23d37](https://linux-hardware.org/?probe=5481a23d37) | Jun 23, 2021 |
| ASUSTek       | M3N78                       | [563d3fb5e6](https://linux-hardware.org/?probe=563d3fb5e6) | Jun 22, 2021 |
| ASUSTek       | P5G41T-M LX2/GB             | [d444752046](https://linux-hardware.org/?probe=d444752046) | Jun 22, 2021 |
| Medion        | MS-7800                     | [90db582ae3](https://linux-hardware.org/?probe=90db582ae3) | Jun 22, 2021 |
| Intel         | B75                         | [421f0ac5c5](https://linux-hardware.org/?probe=421f0ac5c5) | Jun 22, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f7a5e326f3](https://linux-hardware.org/?probe=f7a5e326f3) | Jun 22, 2021 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [7fdab2823e](https://linux-hardware.org/?probe=7fdab2823e) | Jun 22, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3bb1691603](https://linux-hardware.org/?probe=3bb1691603) | Jun 21, 2021 |
| Pegatron      | 2ACB                        | [482b0fab72](https://linux-hardware.org/?probe=482b0fab72) | Jun 21, 2021 |
| HP            | 0A64h                       | [38876167c7](https://linux-hardware.org/?probe=38876167c7) | Jun 21, 2021 |
| HP            | 0A64h                       | [d3e791b0e1](https://linux-hardware.org/?probe=d3e791b0e1) | Jun 21, 2021 |
| Gigabyte      | Z87X-UD4H-CF                | [1a23213aab](https://linux-hardware.org/?probe=1a23213aab) | Jun 21, 2021 |
| Gigabyte      | GA-MA770-DS3                | [484afd8389](https://linux-hardware.org/?probe=484afd8389) | Jun 21, 2021 |
| Pegatron      | 2AD3                        | [0b6660d5b7](https://linux-hardware.org/?probe=0b6660d5b7) | Jun 21, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [a7bf20a30a](https://linux-hardware.org/?probe=a7bf20a30a) | Jun 21, 2021 |
| Gigabyte      | F2A88XM-DS2                 | [cea4d18a80](https://linux-hardware.org/?probe=cea4d18a80) | Jun 20, 2021 |
| Gigabyte      | GA-M56S-S3                  | [e7e3e4138d](https://linux-hardware.org/?probe=e7e3e4138d) | Jun 20, 2021 |
| Gigabyte      | GA-M56S-S3                  | [c4f55611e4](https://linux-hardware.org/?probe=c4f55611e4) | Jun 20, 2021 |
| Gigabyte      | A320M-H-CF                  | [626be63b85](https://linux-hardware.org/?probe=626be63b85) | Jun 20, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [c0ecdee03e](https://linux-hardware.org/?probe=c0ecdee03e) | Jun 20, 2021 |
| Gigabyte      | A520M H                     | [29c80abe49](https://linux-hardware.org/?probe=29c80abe49) | Jun 20, 2021 |
| PCWare        | IPMH61G1                    | [5bcc1419d8](https://linux-hardware.org/?probe=5bcc1419d8) | Jun 19, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [31458f96c8](https://linux-hardware.org/?probe=31458f96c8) | Jun 19, 2021 |
| HP            | 3048h                       | [9d66f53103](https://linux-hardware.org/?probe=9d66f53103) | Jun 19, 2021 |
| Pegatron      | 2A99                        | [d4e6e4c5db](https://linux-hardware.org/?probe=d4e6e4c5db) | Jun 19, 2021 |
| ASRock        | B365M Pro4                  | [f1bccbede1](https://linux-hardware.org/?probe=f1bccbede1) | Jun 19, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [69bc27e4e5](https://linux-hardware.org/?probe=69bc27e4e5) | Jun 19, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [06d9c6260f](https://linux-hardware.org/?probe=06d9c6260f) | Jun 19, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [aa0efa1872](https://linux-hardware.org/?probe=aa0efa1872) | Jun 19, 2021 |
| Dell          | 0J3C2F A00                  | [121b268e78](https://linux-hardware.org/?probe=121b268e78) | Jun 19, 2021 |
| Pegatron      | Benicia                     | [83a136db95](https://linux-hardware.org/?probe=83a136db95) | Jun 19, 2021 |
| ASUSTek       | H170-PRO                    | [27b4b0831d](https://linux-hardware.org/?probe=27b4b0831d) | Jun 18, 2021 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | [ca43a33e1d](https://linux-hardware.org/?probe=ca43a33e1d) | Jun 18, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [e9e1a01e53](https://linux-hardware.org/?probe=e9e1a01e53) | Jun 18, 2021 |
| ASUSTek       | PRIME B560-PLUS             | [ba370ceb36](https://linux-hardware.org/?probe=ba370ceb36) | Jun 18, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [5963dd2256](https://linux-hardware.org/?probe=5963dd2256) | Jun 18, 2021 |
| ASUSTek       | PRIME B560-PLUS             | [9379620c8f](https://linux-hardware.org/?probe=9379620c8f) | Jun 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [474af324cd](https://linux-hardware.org/?probe=474af324cd) | Jun 18, 2021 |
| Gigabyte      | B560M DS3H                  | [a9673cbf80](https://linux-hardware.org/?probe=a9673cbf80) | Jun 18, 2021 |
| ASRock        | NUC-8265U                   | [8a9bc571da](https://linux-hardware.org/?probe=8a9bc571da) | Jun 18, 2021 |
| MSI           | 2A9C                        | [db003454e7](https://linux-hardware.org/?probe=db003454e7) | Jun 18, 2021 |
| Dell          | 0F428D A00                  | [ca7bea0582](https://linux-hardware.org/?probe=ca7bea0582) | Jun 18, 2021 |
| Unknown       | Intel X79                   | [5be1e4c74c](https://linux-hardware.org/?probe=5be1e4c74c) | Jun 18, 2021 |
| eMachines     | ET1331                      | [6d8fbe65fd](https://linux-hardware.org/?probe=6d8fbe65fd) | Jun 17, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [033cd8c9eb](https://linux-hardware.org/?probe=033cd8c9eb) | Jun 17, 2021 |
| ASUSTek       | PRIME B350M-A               | [070ceed526](https://linux-hardware.org/?probe=070ceed526) | Jun 17, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | [0cfd20f720](https://linux-hardware.org/?probe=0cfd20f720) | Jun 16, 2021 |
| Gigabyte      | GA-K8NF-9-RH                | [e33a8c0c69](https://linux-hardware.org/?probe=e33a8c0c69) | Jun 16, 2021 |
| HP            | 339A                        | [88af8ec05f](https://linux-hardware.org/?probe=88af8ec05f) | Jun 16, 2021 |
| MSI           | Z170A GAMING M5             | [0ef1e89213](https://linux-hardware.org/?probe=0ef1e89213) | Jun 16, 2021 |
| MSI           | Z170A GAMING M5             | [f93e026525](https://linux-hardware.org/?probe=f93e026525) | Jun 16, 2021 |
| HP            | 3396                        | [9ab143ae50](https://linux-hardware.org/?probe=9ab143ae50) | Jun 16, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [becb0bd4e6](https://linux-hardware.org/?probe=becb0bd4e6) | Jun 16, 2021 |
| Intel         | SHARKBAY                    | [f6436bedb8](https://linux-hardware.org/?probe=f6436bedb8) | Jun 16, 2021 |
| Dell          | 0D28YY A00                  | [d9cac45ec3](https://linux-hardware.org/?probe=d9cac45ec3) | Jun 16, 2021 |
| ASUSTek       | P5GC-MX/1333                | [c7b83ec204](https://linux-hardware.org/?probe=c7b83ec204) | Jun 16, 2021 |
| ASUSTek       | P5GC-MX/1333                | [c299d91435](https://linux-hardware.org/?probe=c299d91435) | Jun 16, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [815b6ba33d](https://linux-hardware.org/?probe=815b6ba33d) | Jun 16, 2021 |
| MSI           | Z370-A PRO                  | [c24e05c90c](https://linux-hardware.org/?probe=c24e05c90c) | Jun 16, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [b13c355a3c](https://linux-hardware.org/?probe=b13c355a3c) | Jun 16, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [d9eb5348a1](https://linux-hardware.org/?probe=d9eb5348a1) | Jun 16, 2021 |
| Acer          | Aspire XC-603               | [b8e13ff999](https://linux-hardware.org/?probe=b8e13ff999) | Jun 15, 2021 |
| Lenovo        | ThinkCentre M58p 6137FN2    | [29ff95522b](https://linux-hardware.org/?probe=29ff95522b) | Jun 15, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [8d95bf6b27](https://linux-hardware.org/?probe=8d95bf6b27) | Jun 15, 2021 |
| ASUSTek       | H110M-R                     | [00bac228a5](https://linux-hardware.org/?probe=00bac228a5) | Jun 15, 2021 |
| Gigabyte      | Z77M-D3H                    | [fc3ab06806](https://linux-hardware.org/?probe=fc3ab06806) | Jun 15, 2021 |
| Dell          | 0J3C2F A00                  | [d52602be8a](https://linux-hardware.org/?probe=d52602be8a) | Jun 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [93c6859b5c](https://linux-hardware.org/?probe=93c6859b5c) | Jun 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [6347852742](https://linux-hardware.org/?probe=6347852742) | Jun 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [988cd2f5ee](https://linux-hardware.org/?probe=988cd2f5ee) | Jun 15, 2021 |
| ASUSTek       | PRIME A320M-K               | [96353190ff](https://linux-hardware.org/?probe=96353190ff) | Jun 15, 2021 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [0f213a70a3](https://linux-hardware.org/?probe=0f213a70a3) | Jun 15, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [232ecea688](https://linux-hardware.org/?probe=232ecea688) | Jun 15, 2021 |
| ASRock        | P55M Pro                    | [cac3198045](https://linux-hardware.org/?probe=cac3198045) | Jun 14, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e3fd02182e](https://linux-hardware.org/?probe=e3fd02182e) | Jun 14, 2021 |
| Gigabyte      | Z170M-D3H-CF                | [afd44ff35a](https://linux-hardware.org/?probe=afd44ff35a) | Jun 14, 2021 |
| Gigabyte      | GA-MA770-UD3                | [6fa1ce0161](https://linux-hardware.org/?probe=6fa1ce0161) | Jun 14, 2021 |
| Gigabyte      | G31M-ES2L                   | [0c5e09b00c](https://linux-hardware.org/?probe=0c5e09b00c) | Jun 14, 2021 |
| AMD           | A88                         | [6410a91c55](https://linux-hardware.org/?probe=6410a91c55) | Jun 13, 2021 |
| ASUSTek       | B85M-G                      | [a390d934b1](https://linux-hardware.org/?probe=a390d934b1) | Jun 13, 2021 |
| ASUSTek       | F1A55-M LK R2.0             | [60f39937e4](https://linux-hardware.org/?probe=60f39937e4) | Jun 13, 2021 |
| ECS           | MCP61PM-GM                  | [bc4b2b938f](https://linux-hardware.org/?probe=bc4b2b938f) | Jun 13, 2021 |
| ECS           | MCP61PM-GM                  | [dfda4f4f55](https://linux-hardware.org/?probe=dfda4f4f55) | Jun 13, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | [e49acd5f55](https://linux-hardware.org/?probe=e49acd5f55) | Jun 12, 2021 |
| ASUSTek       | P5SD2-VM                    | [af97a04e71](https://linux-hardware.org/?probe=af97a04e71) | Jun 12, 2021 |
| Unknown       | X79-P3                      | [8c01718379](https://linux-hardware.org/?probe=8c01718379) | Jun 12, 2021 |
| MSI           | B350 GAMING PLUS            | [0ce81f40cc](https://linux-hardware.org/?probe=0ce81f40cc) | Jun 12, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [b8540739ff](https://linux-hardware.org/?probe=b8540739ff) | Jun 12, 2021 |
| Gigabyte      | GA-970A-UD3                 | [9790504450](https://linux-hardware.org/?probe=9790504450) | Jun 12, 2021 |
| Intel         | DH55PJ AAE93812-302         | [00d6079e31](https://linux-hardware.org/?probe=00d6079e31) | Jun 12, 2021 |
| Intel         | DH55PJ AAE93812-302         | [945cb0164b](https://linux-hardware.org/?probe=945cb0164b) | Jun 12, 2021 |
| Biostar       | B450GT3                     | [edf58235ce](https://linux-hardware.org/?probe=edf58235ce) | Jun 12, 2021 |
| Dell          | 0F5C5X A00                  | [c4f0c146f6](https://linux-hardware.org/?probe=c4f0c146f6) | Jun 12, 2021 |
| Dell          | 0J3C2F A00                  | [85fdf2d852](https://linux-hardware.org/?probe=85fdf2d852) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [d19e5c9398](https://linux-hardware.org/?probe=d19e5c9398) | Jun 11, 2021 |
| Unknown       | Unknown                     | [e373b5b1c7](https://linux-hardware.org/?probe=e373b5b1c7) | Jun 11, 2021 |
| Unknown       | Unknown                     | [1b15747580](https://linux-hardware.org/?probe=1b15747580) | Jun 11, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [96032a59c8](https://linux-hardware.org/?probe=96032a59c8) | Jun 11, 2021 |
| OEM           | Unknown                     | [da66367cb9](https://linux-hardware.org/?probe=da66367cb9) | Jun 11, 2021 |
| OEM           | Unknown                     | [a17459fe7c](https://linux-hardware.org/?probe=a17459fe7c) | Jun 11, 2021 |
| Intel         | H61                         | [707b0d49de](https://linux-hardware.org/?probe=707b0d49de) | Jun 10, 2021 |
| MSI           | 970 GAMING                  | [cc0d8a379b](https://linux-hardware.org/?probe=cc0d8a379b) | Jun 10, 2021 |
| ASRock        | X470 Master SLI/ac          | [fa2f22306b](https://linux-hardware.org/?probe=fa2f22306b) | Jun 10, 2021 |
| Dell          | 0M5DCD A00                  | [86f3879b88](https://linux-hardware.org/?probe=86f3879b88) | Jun 09, 2021 |
| Dell          | 0M5DCD A00                  | [d3c31a6840](https://linux-hardware.org/?probe=d3c31a6840) | Jun 09, 2021 |
| Gigabyte      | H97M-DS3P                   | [7936a4e3cd](https://linux-hardware.org/?probe=7936a4e3cd) | Jun 09, 2021 |
| Dell          | 0J3C2F A00                  | [7e309360cd](https://linux-hardware.org/?probe=7e309360cd) | Jun 09, 2021 |
| Acer          | Aspire XC600 v1.0           | [5ab9e6db96](https://linux-hardware.org/?probe=5ab9e6db96) | Jun 09, 2021 |
| ASUSTek       | P5B-Deluxe                  | [1454659388](https://linux-hardware.org/?probe=1454659388) | Jun 09, 2021 |
| ASRock        | N68-S UCC                   | [155ac9e15e](https://linux-hardware.org/?probe=155ac9e15e) | Jun 09, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [c7ef032a3f](https://linux-hardware.org/?probe=c7ef032a3f) | Jun 08, 2021 |
| Dell          | 0PTTT9 A01                  | [1dfe7bd3cb](https://linux-hardware.org/?probe=1dfe7bd3cb) | Jun 08, 2021 |
| Acer          | Aspire XC-230               | [20257e1d41](https://linux-hardware.org/?probe=20257e1d41) | Jun 08, 2021 |
| ASRock        | B460 Phantom Gaming 4       | [fd0617ab84](https://linux-hardware.org/?probe=fd0617ab84) | Jun 08, 2021 |
| Gigabyte      | H61M-DS2                    | [b527e6a2a9](https://linux-hardware.org/?probe=b527e6a2a9) | Jun 08, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [9fbeee319a](https://linux-hardware.org/?probe=9fbeee319a) | Jun 08, 2021 |
| Fujitsu Si... | D1567 S26361-D1567          | [b26937abc3](https://linux-hardware.org/?probe=b26937abc3) | Jun 07, 2021 |
| Fujitsu Si... | D1567 S26361-D1567          | [ebb04fb6c9](https://linux-hardware.org/?probe=ebb04fb6c9) | Jun 07, 2021 |
| Biostar       | G41D3C                      | [263491c02a](https://linux-hardware.org/?probe=263491c02a) | Jun 07, 2021 |
| ASUSTek       | PRIME B250-PRO              | [9a8c7f02d7](https://linux-hardware.org/?probe=9a8c7f02d7) | Jun 07, 2021 |
| Gigabyte      | B365M DS3H                  | [64a3b14495](https://linux-hardware.org/?probe=64a3b14495) | Jun 07, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [7b820949e3](https://linux-hardware.org/?probe=7b820949e3) | Jun 07, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [f6a6e44eb7](https://linux-hardware.org/?probe=f6a6e44eb7) | Jun 06, 2021 |
| ECS           | P4M900T-M2                  | [1627d493ea](https://linux-hardware.org/?probe=1627d493ea) | Jun 06, 2021 |
| ASRock        | Z390 Phantom Gaming 4-CB    | [aeae38d50f](https://linux-hardware.org/?probe=aeae38d50f) | Jun 06, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [37be0c0682](https://linux-hardware.org/?probe=37be0c0682) | Jun 05, 2021 |
| Gigabyte      | Z270-Gaming 3               | [8dce933429](https://linux-hardware.org/?probe=8dce933429) | Jun 05, 2021 |
| Gigabyte      | Z270-Gaming 3               | [127d1eec46](https://linux-hardware.org/?probe=127d1eec46) | Jun 05, 2021 |
| ASUSTek       | P5SD2-VM                    | [8dbeec994e](https://linux-hardware.org/?probe=8dbeec994e) | Jun 05, 2021 |
| Dell          | 0XFWHV A00                  | [b72695b34f](https://linux-hardware.org/?probe=b72695b34f) | Jun 05, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [8004d950b6](https://linux-hardware.org/?probe=8004d950b6) | Jun 05, 2021 |
| eMachines     | EL1352                      | [c543977660](https://linux-hardware.org/?probe=c543977660) | Jun 05, 2021 |
| Gigabyte      | Z87-HD3                     | [8ca2af34b9](https://linux-hardware.org/?probe=8ca2af34b9) | Jun 05, 2021 |
| Dell          | 0CRH6C A02                  | [1d91fd9112](https://linux-hardware.org/?probe=1d91fd9112) | Jun 05, 2021 |
| ASRock        | 970 Extreme4                | [6bb04a23b1](https://linux-hardware.org/?probe=6bb04a23b1) | Jun 05, 2021 |
| ASUSTek       | P5SD2-VM                    | [d5c203111b](https://linux-hardware.org/?probe=d5c203111b) | Jun 05, 2021 |
| ASRock        | FM2A68M-DG3+                | [81fee2b563](https://linux-hardware.org/?probe=81fee2b563) | Jun 04, 2021 |
| ASUSTek       | P7P55D LE                   | [5e58b5909b](https://linux-hardware.org/?probe=5e58b5909b) | Jun 04, 2021 |
| ASUSTek       | P7H55-M LX                  | [a80a7c748b](https://linux-hardware.org/?probe=a80a7c748b) | Jun 04, 2021 |
| Acer          | FMCP7AM                     | [c9f48c1d32](https://linux-hardware.org/?probe=c9f48c1d32) | Jun 04, 2021 |
| ASUSTek       | 2A73h                       | [22c772be67](https://linux-hardware.org/?probe=22c772be67) | Jun 04, 2021 |
| ASUSTek       | P7H55-M LX                  | [65cc99b31c](https://linux-hardware.org/?probe=65cc99b31c) | Jun 04, 2021 |
| Lenovo        | ThinkCentre M57e 6176A13    | [168eb58716](https://linux-hardware.org/?probe=168eb58716) | Jun 04, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [d68abf1123](https://linux-hardware.org/?probe=d68abf1123) | Jun 04, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [44a240b27d](https://linux-hardware.org/?probe=44a240b27d) | Jun 04, 2021 |
| ASUSTek       | X99-DELUXE II               | [5dab87d558](https://linux-hardware.org/?probe=5dab87d558) | Jun 03, 2021 |
| ASRock        | P55M Pro                    | [b994c1917a](https://linux-hardware.org/?probe=b994c1917a) | Jun 03, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [93fae5187a](https://linux-hardware.org/?probe=93fae5187a) | Jun 03, 2021 |
| MSI           | H81M-P33                    | [40cf3439db](https://linux-hardware.org/?probe=40cf3439db) | Jun 02, 2021 |
| HP            | 1495                        | [6bcbd544ee](https://linux-hardware.org/?probe=6bcbd544ee) | Jun 02, 2021 |
| ASUSTek       | PRIME B550M-A               | [7fb5f68146](https://linux-hardware.org/?probe=7fb5f68146) | Jun 02, 2021 |
| HP            | 18E7                        | [ac4f9cd1e4](https://linux-hardware.org/?probe=ac4f9cd1e4) | Jun 02, 2021 |
| MSI           | 970 GAMING                  | [65e62cfb15](https://linux-hardware.org/?probe=65e62cfb15) | Jun 02, 2021 |
| Acer          | Aspire XC-230               | [0298fa0732](https://linux-hardware.org/?probe=0298fa0732) | Jun 02, 2021 |
| ASUSTek       | PRO B460M-C                 | [6d999709ad](https://linux-hardware.org/?probe=6d999709ad) | Jun 02, 2021 |
| MSI           | B450M GAMING PLUS           | [cdbf3bb107](https://linux-hardware.org/?probe=cdbf3bb107) | Jun 02, 2021 |
| Chuwi         | LarkBox                     | [0cb7a779d7](https://linux-hardware.org/?probe=0cb7a779d7) | Jun 01, 2021 |
| ASUSTek       | M2N-MX SE Plus              | [5e7b422316](https://linux-hardware.org/?probe=5e7b422316) | Jun 01, 2021 |
| Unknown       | Intel X79                   | [6853a4cb43](https://linux-hardware.org/?probe=6853a4cb43) | Jun 01, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [97c17f738a](https://linux-hardware.org/?probe=97c17f738a) | Jun 01, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [d88d9db618](https://linux-hardware.org/?probe=d88d9db618) | May 31, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [ee70388997](https://linux-hardware.org/?probe=ee70388997) | May 31, 2021 |
| ASUSTek       | H97M-E                      | [0d40daa834](https://linux-hardware.org/?probe=0d40daa834) | May 31, 2021 |
| Gigabyte      | A55M-DS2                    | [0e94f2ad8f](https://linux-hardware.org/?probe=0e94f2ad8f) | May 31, 2021 |
| ASUSTek       | PRIME B450M-A               | [115ec5eca4](https://linux-hardware.org/?probe=115ec5eca4) | May 31, 2021 |
| ASUSTek       | PRIME B450M-A               | [7740f5a978](https://linux-hardware.org/?probe=7740f5a978) | May 31, 2021 |
| Dell          | 096JG8 A01                  | [8989df3c9d](https://linux-hardware.org/?probe=8989df3c9d) | May 31, 2021 |
| ASUSTek       | Z97-A-USB31                 | [8f3ca163e7](https://linux-hardware.org/?probe=8f3ca163e7) | May 31, 2021 |
| MSI           | A320M GRENADE               | [d2fa60e459](https://linux-hardware.org/?probe=d2fa60e459) | May 30, 2021 |
| ASRock        | H110M-DGS                   | [3a2a9bd626](https://linux-hardware.org/?probe=3a2a9bd626) | May 30, 2021 |
| ASRock        | B150M Pro4                  | [2be44df65d](https://linux-hardware.org/?probe=2be44df65d) | May 30, 2021 |
| Gigabyte      | 990FXA-UD3                  | [1770bbe4e2](https://linux-hardware.org/?probe=1770bbe4e2) | May 30, 2021 |
| Gigabyte      | B75M-D3H                    | [f55f5434e6](https://linux-hardware.org/?probe=f55f5434e6) | May 29, 2021 |
| Gigabyte      | B75M-D3H                    | [3f196ad923](https://linux-hardware.org/?probe=3f196ad923) | May 29, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [0ff290ef92](https://linux-hardware.org/?probe=0ff290ef92) | May 29, 2021 |
| Foxconn       | 45GM/45CM/45CM-S            | [d502ee8537](https://linux-hardware.org/?probe=d502ee8537) | May 29, 2021 |
| Foxconn       | 45GM/45CM/45CM-S            | [3ded9ff276](https://linux-hardware.org/?probe=3ded9ff276) | May 29, 2021 |
| ECS           | G41T-M12                    | [086ce490f7](https://linux-hardware.org/?probe=086ce490f7) | May 29, 2021 |
| MSI           | B365M PRO-VH                | [9a3529c8ae](https://linux-hardware.org/?probe=9a3529c8ae) | May 29, 2021 |
| Gigabyte      | GA-970A-D3                  | [74d6e4ffa4](https://linux-hardware.org/?probe=74d6e4ffa4) | May 29, 2021 |
| HP            | 8595                        | [fff752395f](https://linux-hardware.org/?probe=fff752395f) | May 28, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [86e186908f](https://linux-hardware.org/?probe=86e186908f) | May 28, 2021 |
| HP            | 3397                        | [9c1343dd9b](https://linux-hardware.org/?probe=9c1343dd9b) | May 28, 2021 |
| Toshiba       | STI 012943                  | [4b79994619](https://linux-hardware.org/?probe=4b79994619) | May 28, 2021 |
| HP            | 3397                        | [64181552c3](https://linux-hardware.org/?probe=64181552c3) | May 28, 2021 |
| Lenovo        | 0.1                         | [77d8358e26](https://linux-hardware.org/?probe=77d8358e26) | May 28, 2021 |
| Gigabyte      | H81M-S                      | [f5747f7378](https://linux-hardware.org/?probe=f5747f7378) | May 28, 2021 |
| Gigabyte      | H81M-S                      | [09333861d3](https://linux-hardware.org/?probe=09333861d3) | May 28, 2021 |
| ASUSTek       | P8Z68-V LX                  | [4837692ecc](https://linux-hardware.org/?probe=4837692ecc) | May 28, 2021 |
| Dell          | 0J3C2F A00                  | [16d3397eb8](https://linux-hardware.org/?probe=16d3397eb8) | May 28, 2021 |
| ASRock        | B450 Steel Legend           | [bfbfde5c37](https://linux-hardware.org/?probe=bfbfde5c37) | May 27, 2021 |
| ASUSTek       | Z170-A                      | [5a56ed934e](https://linux-hardware.org/?probe=5a56ed934e) | May 27, 2021 |
| Lenovo        | 0.1                         | [d0fbef90ca](https://linux-hardware.org/?probe=d0fbef90ca) | May 27, 2021 |
| ASUSTek       | PRIME A320M-K               | [1d529bd30e](https://linux-hardware.org/?probe=1d529bd30e) | May 27, 2021 |
| ASRock        | B450M Pro4                  | [bb18d1360e](https://linux-hardware.org/?probe=bb18d1360e) | May 27, 2021 |
| MSI           | X470 GAMING M7 AC           | [5913b80a19](https://linux-hardware.org/?probe=5913b80a19) | May 26, 2021 |
| MSI           | X470 GAMING M7 AC           | [fa6dd15d4f](https://linux-hardware.org/?probe=fa6dd15d4f) | May 26, 2021 |
| Dell          | 0CU409                      | [d6059634ea](https://linux-hardware.org/?probe=d6059634ea) | May 26, 2021 |
| HP            | 18E7                        | [e5e458a769](https://linux-hardware.org/?probe=e5e458a769) | May 26, 2021 |
| HP            | 18E7                        | [0eec8697a8](https://linux-hardware.org/?probe=0eec8697a8) | May 26, 2021 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | [67cb78d31c](https://linux-hardware.org/?probe=67cb78d31c) | May 26, 2021 |
| MSI           | B450M GAMING PLUS           | [9b8f51b1d4](https://linux-hardware.org/?probe=9b8f51b1d4) | May 26, 2021 |
| ASUSTek       | B85M-G                      | [92f19ca1e6](https://linux-hardware.org/?probe=92f19ca1e6) | May 25, 2021 |
| ASUSTek       | H81M-A/BR                   | [eba4d60b90](https://linux-hardware.org/?probe=eba4d60b90) | May 25, 2021 |
| ASUSTek       | P8Z77-V LX2                 | [58a5849cc5](https://linux-hardware.org/?probe=58a5849cc5) | May 25, 2021 |
| HP            | 1998                        | [4c3248677a](https://linux-hardware.org/?probe=4c3248677a) | May 25, 2021 |
| HP            | 1998                        | [9239b61815](https://linux-hardware.org/?probe=9239b61815) | May 25, 2021 |
| ASUSTek       | STRIX H270I GAMING          | [5989c34ed4](https://linux-hardware.org/?probe=5989c34ed4) | May 25, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [b0f626d0e4](https://linux-hardware.org/?probe=b0f626d0e4) | May 25, 2021 |
| ASRock        | B450M Pro4                  | [229b36f7f9](https://linux-hardware.org/?probe=229b36f7f9) | May 25, 2021 |
| Dell          | 0CU409                      | [b88323dceb](https://linux-hardware.org/?probe=b88323dceb) | May 25, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [66ee405576](https://linux-hardware.org/?probe=66ee405576) | May 25, 2021 |
| Gigabyte      | X570 GAMING X               | [0b0d9a9d91](https://linux-hardware.org/?probe=0b0d9a9d91) | May 24, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [123b35c040](https://linux-hardware.org/?probe=123b35c040) | May 24, 2021 |
| Gigabyte      | X570 GAMING X               | [d63276b8f6](https://linux-hardware.org/?probe=d63276b8f6) | May 24, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [6783333b0d](https://linux-hardware.org/?probe=6783333b0d) | May 24, 2021 |
| ASUSTek       | M5A78L-M LX3                | [3eed0a8556](https://linux-hardware.org/?probe=3eed0a8556) | May 23, 2021 |
| ASUSTek       | M5A78L-M LX3                | [10cd2166f2](https://linux-hardware.org/?probe=10cd2166f2) | May 23, 2021 |
| Gigabyte      | G41M-ES2L                   | [862a8136da](https://linux-hardware.org/?probe=862a8136da) | May 23, 2021 |
| MSI           | 760GM-P23                   | [92f2b7546b](https://linux-hardware.org/?probe=92f2b7546b) | May 23, 2021 |
| Packard Be... | IMEDIA S3810                | [0b338ecaf1](https://linux-hardware.org/?probe=0b338ecaf1) | May 23, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [f7051f2963](https://linux-hardware.org/?probe=f7051f2963) | May 23, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [8726c7f1dc](https://linux-hardware.org/?probe=8726c7f1dc) | May 23, 2021 |
| MSI           | 760GM-P23                   | [0a6b2666b3](https://linux-hardware.org/?probe=0a6b2666b3) | May 22, 2021 |
| HP            | 3047h                       | [4e44ec3823](https://linux-hardware.org/?probe=4e44ec3823) | May 22, 2021 |
| Intel         | H61 V124                    | [503bb6469f](https://linux-hardware.org/?probe=503bb6469f) | May 22, 2021 |
| ASUSTek       | PRIME B450M-A               | [7a2a0a49c8](https://linux-hardware.org/?probe=7a2a0a49c8) | May 22, 2021 |
| MSI           | B85M GAMING                 | [4d2529b647](https://linux-hardware.org/?probe=4d2529b647) | May 22, 2021 |
| Acer          | EG43LMK                     | [c6f4b7dc40](https://linux-hardware.org/?probe=c6f4b7dc40) | May 22, 2021 |
| eMachines     | EMCP73VT-PM                 | [54fca2179e](https://linux-hardware.org/?probe=54fca2179e) | May 22, 2021 |
| Dell          | 0C2XKD A01                  | [57c0159990](https://linux-hardware.org/?probe=57c0159990) | May 21, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [961e640bf5](https://linux-hardware.org/?probe=961e640bf5) | May 21, 2021 |
| MSI           | MAG B550M BAZOOKA           | [4a568f856e](https://linux-hardware.org/?probe=4a568f856e) | May 21, 2021 |
| MSI           | MAG B550M BAZOOKA           | [dbdcc61220](https://linux-hardware.org/?probe=dbdcc61220) | May 21, 2021 |
| Alienware     | 0PGRP5 A01                  | [54c021054a](https://linux-hardware.org/?probe=54c021054a) | May 21, 2021 |
| Gigabyte      | G31M-ES2C                   | [98e3f46335](https://linux-hardware.org/?probe=98e3f46335) | May 21, 2021 |
| HP            | 8433 11                     | [8670420e76](https://linux-hardware.org/?probe=8670420e76) | May 21, 2021 |
| Apple         | Mac-F221BEC8                | [b14bc57ea5](https://linux-hardware.org/?probe=b14bc57ea5) | May 21, 2021 |
| Apple         | Mac-F221BEC8                | [7866779ebe](https://linux-hardware.org/?probe=7866779ebe) | May 21, 2021 |
| ASRock        | B450M-HDV R4.0              | [e2588635b4](https://linux-hardware.org/?probe=e2588635b4) | May 20, 2021 |
| Gigabyte      | G31M-S2L                    | [b1208dac2c](https://linux-hardware.org/?probe=b1208dac2c) | May 20, 2021 |
| ASRock        | Z77 Extreme4                | [9bc3a8a33e](https://linux-hardware.org/?probe=9bc3a8a33e) | May 20, 2021 |
| MSI           | B550-A PRO                  | [3067a6e57b](https://linux-hardware.org/?probe=3067a6e57b) | May 20, 2021 |
| Gigabyte      | F2A88XM-DS2                 | [91962c3998](https://linux-hardware.org/?probe=91962c3998) | May 20, 2021 |
| Pegatron      | 2A99h                       | [008b548654](https://linux-hardware.org/?probe=008b548654) | May 20, 2021 |
| Dell          | 0WG864                      | [c58153803d](https://linux-hardware.org/?probe=c58153803d) | May 20, 2021 |
| ASUSTek       | PRIME Z270-A                | [8325209418](https://linux-hardware.org/?probe=8325209418) | May 20, 2021 |
| Pegatron      | 2AC2                        | [69b2dc2208](https://linux-hardware.org/?probe=69b2dc2208) | May 20, 2021 |
| ASUSTek       | PRIME B450M-A               | [c5b23dd7cc](https://linux-hardware.org/?probe=c5b23dd7cc) | May 20, 2021 |
| ASUSTek       | X99-PRO/USB                 | [e456864b06](https://linux-hardware.org/?probe=e456864b06) | May 19, 2021 |
| ASUSTek       | PRIME J4005I-C              | [d8be675a5d](https://linux-hardware.org/?probe=d8be675a5d) | May 19, 2021 |
| PCWare        | IPMH81G1                    | [02cfdda040](https://linux-hardware.org/?probe=02cfdda040) | May 19, 2021 |
| HP            | 8055                        | [d4e8b6181f](https://linux-hardware.org/?probe=d4e8b6181f) | May 19, 2021 |
| Gigabyte      | F2A88XM-DS2                 | [83945bef1b](https://linux-hardware.org/?probe=83945bef1b) | May 19, 2021 |
| Intel         | DQ45CB AAE30148-302         | [95642c55fc](https://linux-hardware.org/?probe=95642c55fc) | May 19, 2021 |
| Huanan        | X99 F8D V1.0                | [3a75b6cf54](https://linux-hardware.org/?probe=3a75b6cf54) | May 19, 2021 |
| Gigabyte      | Z87X-UD5H-CF                | [a2454fcd1f](https://linux-hardware.org/?probe=a2454fcd1f) | May 19, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [61a19f497d](https://linux-hardware.org/?probe=61a19f497d) | May 19, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [a976c2d8c8](https://linux-hardware.org/?probe=a976c2d8c8) | May 19, 2021 |
| Pegatron      | NARRA5                      | [b793645633](https://linux-hardware.org/?probe=b793645633) | May 19, 2021 |
| MSI           | MEG X299 CREATION           | [c9ec042c96](https://linux-hardware.org/?probe=c9ec042c96) | May 19, 2021 |
| HP            | 158B                        | [730c09f9e6](https://linux-hardware.org/?probe=730c09f9e6) | May 19, 2021 |
| Wistron       | ProLiant ML110 G6           | [53d1c16f77](https://linux-hardware.org/?probe=53d1c16f77) | May 18, 2021 |
| ASUSTek       | H61M-K                      | [b8f1483fb0](https://linux-hardware.org/?probe=b8f1483fb0) | May 18, 2021 |
| Lenovo        | ThinkCentre A58e 0841A2U    | [38961e8d39](https://linux-hardware.org/?probe=38961e8d39) | May 18, 2021 |
| Inventec      | Z CLASS A02                 | [9d595da4f0](https://linux-hardware.org/?probe=9d595da4f0) | May 18, 2021 |
| MSI           | A68HM-E33 V2                | [a14cf2a48e](https://linux-hardware.org/?probe=a14cf2a48e) | May 18, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [b07d6adc60](https://linux-hardware.org/?probe=b07d6adc60) | May 18, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [31a93c68cb](https://linux-hardware.org/?probe=31a93c68cb) | May 18, 2021 |
| Acer          | EG43LMK                     | [1aaa7ce005](https://linux-hardware.org/?probe=1aaa7ce005) | May 18, 2021 |
| MSI           | B450-A PRO MAX              | [e94076c272](https://linux-hardware.org/?probe=e94076c272) | May 18, 2021 |
| Pegatron      | Benicia                     | [e051360964](https://linux-hardware.org/?probe=e051360964) | May 17, 2021 |
| MSI           | B450-A PRO MAX              | [3ca22b69d1](https://linux-hardware.org/?probe=3ca22b69d1) | May 17, 2021 |
| ASRock        | Z270 Pro4                   | [04129b414e](https://linux-hardware.org/?probe=04129b414e) | May 17, 2021 |
| ASUSTek       | Maximus VIII HERO           | [200e848484](https://linux-hardware.org/?probe=200e848484) | May 17, 2021 |
| ASUSTek       | Q170S1                      | [45b8a57335](https://linux-hardware.org/?probe=45b8a57335) | May 17, 2021 |
| MSI           | 970 GAMING                  | [758f4e679f](https://linux-hardware.org/?probe=758f4e679f) | May 17, 2021 |
| ASRock        | H97 Performance             | [98bbc7ad66](https://linux-hardware.org/?probe=98bbc7ad66) | May 17, 2021 |
| ASUSTek       | P7P55D-E                    | [7b61a183a5](https://linux-hardware.org/?probe=7b61a183a5) | May 16, 2021 |
| Pegatron      | NARRA5                      | [32af52eccd](https://linux-hardware.org/?probe=32af52eccd) | May 16, 2021 |
| ASRock        | B365M Pro4                  | [6a239e3767](https://linux-hardware.org/?probe=6a239e3767) | May 16, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [0941c48646](https://linux-hardware.org/?probe=0941c48646) | May 16, 2021 |
| ASUSTek       | B85M-E                      | [4c98ef4248](https://linux-hardware.org/?probe=4c98ef4248) | May 16, 2021 |
| Pegatron      | 2A99                        | [fb464c433d](https://linux-hardware.org/?probe=fb464c433d) | May 16, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [0d20396b4b](https://linux-hardware.org/?probe=0d20396b4b) | May 16, 2021 |
| Gigabyte      | X570 GAMING X               | [ac0f996928](https://linux-hardware.org/?probe=ac0f996928) | May 16, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [2d48c94948](https://linux-hardware.org/?probe=2d48c94948) | May 16, 2021 |
| Seco          | C40 C                       | [3f202f2d16](https://linux-hardware.org/?probe=3f202f2d16) | May 16, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | [d139816804](https://linux-hardware.org/?probe=d139816804) | May 16, 2021 |
| PCWare        | IPMH61G1                    | [3955febf5f](https://linux-hardware.org/?probe=3955febf5f) | May 16, 2021 |
| Acer          | Aspire E500                 | [21833c414e](https://linux-hardware.org/?probe=21833c414e) | May 16, 2021 |
| ASUSTek       | B85M-E                      | [906f940241](https://linux-hardware.org/?probe=906f940241) | May 16, 2021 |
| ASUSTek       | PRIME X570-P                | [ab49980dfa](https://linux-hardware.org/?probe=ab49980dfa) | May 16, 2021 |
| Acer          | RS780DV                     | [891ec8399c](https://linux-hardware.org/?probe=891ec8399c) | May 15, 2021 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | [f4ef1b4b09](https://linux-hardware.org/?probe=f4ef1b4b09) | May 15, 2021 |
| Acer          | Aspire E500                 | [50a708e093](https://linux-hardware.org/?probe=50a708e093) | May 15, 2021 |
| Inventec      | Z CLASS A02                 | [47afb8ff72](https://linux-hardware.org/?probe=47afb8ff72) | May 15, 2021 |
| MSI           | A320M GRENADE               | [143436ebd4](https://linux-hardware.org/?probe=143436ebd4) | May 15, 2021 |
| MSI           | A320M GRENADE               | [7a36abeac4](https://linux-hardware.org/?probe=7a36abeac4) | May 15, 2021 |
| ASUSTek       | P5K SE/EPU                  | [50ae548f24](https://linux-hardware.org/?probe=50ae548f24) | May 15, 2021 |
| ASUSTek       | P5K SE/EPU                  | [91eba55435](https://linux-hardware.org/?probe=91eba55435) | May 15, 2021 |
| ASUSTek       | PRIME B250M-K               | [09b5a12bde](https://linux-hardware.org/?probe=09b5a12bde) | May 15, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [8176b777b9](https://linux-hardware.org/?probe=8176b777b9) | May 15, 2021 |
| ASUSTek       | H81M-A                      | [30aeb41807](https://linux-hardware.org/?probe=30aeb41807) | May 14, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [356a329ce3](https://linux-hardware.org/?probe=356a329ce3) | May 14, 2021 |
| Lenovo        | Board                       | [97391ddd40](https://linux-hardware.org/?probe=97391ddd40) | May 14, 2021 |
| HP            | 3397                        | [65c281aa27](https://linux-hardware.org/?probe=65c281aa27) | May 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [c75942cc3c](https://linux-hardware.org/?probe=c75942cc3c) | May 14, 2021 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [366c59d94a](https://linux-hardware.org/?probe=366c59d94a) | May 14, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [363912f531](https://linux-hardware.org/?probe=363912f531) | May 14, 2021 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [8a00a70c48](https://linux-hardware.org/?probe=8a00a70c48) | May 14, 2021 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [a81edc4b9a](https://linux-hardware.org/?probe=a81edc4b9a) | May 14, 2021 |
| ASUSTek       | P7P55D-E                    | [3952ef02b5](https://linux-hardware.org/?probe=3952ef02b5) | May 14, 2021 |
| ASUSTek       | K8N                         | [da5df35a21](https://linux-hardware.org/?probe=da5df35a21) | May 13, 2021 |
| ASUSTek       | H170 PRO GAMING             | [265d5c9943](https://linux-hardware.org/?probe=265d5c9943) | May 13, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [7b8c559de7](https://linux-hardware.org/?probe=7b8c559de7) | May 13, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [eeb54d01f8](https://linux-hardware.org/?probe=eeb54d01f8) | May 13, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0c77c08736](https://linux-hardware.org/?probe=0c77c08736) | May 13, 2021 |
| ECS           | K8M800-M2                   | [20ebde2857](https://linux-hardware.org/?probe=20ebde2857) | May 12, 2021 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [855e581619](https://linux-hardware.org/?probe=855e581619) | May 12, 2021 |
| ASRock        | Z77 Pro3                    | [a981f9a0c5](https://linux-hardware.org/?probe=a981f9a0c5) | May 12, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [b925797f6d](https://linux-hardware.org/?probe=b925797f6d) | May 12, 2021 |
| Gigabyte      | GA-990FXA-UD3               | [5301771cb8](https://linux-hardware.org/?probe=5301771cb8) | May 12, 2021 |
| MSI           | H310M PRO-VD                | [be3b72e745](https://linux-hardware.org/?probe=be3b72e745) | May 12, 2021 |
| Intel         | D975XBX2 AAD53347-404       | [82933cdf0e](https://linux-hardware.org/?probe=82933cdf0e) | May 12, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [0d964b5339](https://linux-hardware.org/?probe=0d964b5339) | May 12, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [383f9a1f6c](https://linux-hardware.org/?probe=383f9a1f6c) | May 12, 2021 |
| Toshiba       | STI 005492G                 | [5850550628](https://linux-hardware.org/?probe=5850550628) | May 12, 2021 |
| Gigabyte      | H170-D3H-CF                 | [085c6c289b](https://linux-hardware.org/?probe=085c6c289b) | May 12, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | [4e6373a5ce](https://linux-hardware.org/?probe=4e6373a5ce) | May 12, 2021 |
| HP            | 3397                        | [7dc9ed5dd6](https://linux-hardware.org/?probe=7dc9ed5dd6) | May 12, 2021 |
| ASUSTek       | PRIME X570-P                | [ebd6b0baa5](https://linux-hardware.org/?probe=ebd6b0baa5) | May 12, 2021 |
| Gigabyte      | GA-MA770-DS3                | [06fa187755](https://linux-hardware.org/?probe=06fa187755) | May 12, 2021 |
| ASRock        | N68C-S UCC                  | [3c0ef1dbe1](https://linux-hardware.org/?probe=3c0ef1dbe1) | May 11, 2021 |
| Lenovo        | Board                       | [d3fae8964b](https://linux-hardware.org/?probe=d3fae8964b) | May 11, 2021 |
| Lanix         | H55M-E33 LNXACT             | [4671af1d0c](https://linux-hardware.org/?probe=4671af1d0c) | May 11, 2021 |
| Lanix         | H55M-E33 LNXACT             | [04e6d2e131](https://linux-hardware.org/?probe=04e6d2e131) | May 11, 2021 |
| ASRock        | A320M-HDV                   | [f85fceb5f0](https://linux-hardware.org/?probe=f85fceb5f0) | May 11, 2021 |
| HP            | 0B4Ch D                     | [83c114d947](https://linux-hardware.org/?probe=83c114d947) | May 11, 2021 |
| Lenovo        | ThinkCentre M58p 6137FN2    | [2ebc1306c7](https://linux-hardware.org/?probe=2ebc1306c7) | May 10, 2021 |
| ASRock        | 970M Pro3                   | [8271176e88](https://linux-hardware.org/?probe=8271176e88) | May 10, 2021 |
| ASUSTek       | P5KPL-AM                    | [981dfc073b](https://linux-hardware.org/?probe=981dfc073b) | May 10, 2021 |
| Gigabyte      | H81M-DS2                    | [a7eee355c3](https://linux-hardware.org/?probe=a7eee355c3) | May 10, 2021 |
| MSI           | A320M GRENADE               | [3ed1977b7c](https://linux-hardware.org/?probe=3ed1977b7c) | May 10, 2021 |
| MSI           | A320M GRENADE               | [e153b8a580](https://linux-hardware.org/?probe=e153b8a580) | May 10, 2021 |
| Gigabyte      | H81M-DS2                    | [fe0d3c24c8](https://linux-hardware.org/?probe=fe0d3c24c8) | May 10, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [df8b93d84c](https://linux-hardware.org/?probe=df8b93d84c) | May 10, 2021 |
| Acer          | RS780DV                     | [ccaa0d800f](https://linux-hardware.org/?probe=ccaa0d800f) | May 10, 2021 |
| Pegatron      | E60                         | [0e1fa2c583](https://linux-hardware.org/?probe=0e1fa2c583) | May 10, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [e7262e0201](https://linux-hardware.org/?probe=e7262e0201) | May 09, 2021 |
| MSI           | X58 Pro-E                   | [93440db1b9](https://linux-hardware.org/?probe=93440db1b9) | May 09, 2021 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | [717ec23ce4](https://linux-hardware.org/?probe=717ec23ce4) | May 09, 2021 |
| HP            | 1495                        | [edcac20052](https://linux-hardware.org/?probe=edcac20052) | May 09, 2021 |
| Packard Be... | ONETWO L5861                | [1cbee8a7ef](https://linux-hardware.org/?probe=1cbee8a7ef) | May 09, 2021 |
| HP            | 2AF7                        | [c596261cd2](https://linux-hardware.org/?probe=c596261cd2) | May 09, 2021 |
| HP            | 2AF7                        | [a3ffba7056](https://linux-hardware.org/?probe=a3ffba7056) | May 09, 2021 |
| ASRock        | B365M Pro4                  | [ff508028c9](https://linux-hardware.org/?probe=ff508028c9) | May 09, 2021 |
| ASRock        | H81M-VG4 R2.0               | [80070c566e](https://linux-hardware.org/?probe=80070c566e) | May 09, 2021 |
| ASRock        | B365M Pro4                  | [24eb402858](https://linux-hardware.org/?probe=24eb402858) | May 09, 2021 |
| Digitron      | G31T-M7                     | [bf40420f1c](https://linux-hardware.org/?probe=bf40420f1c) | May 09, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [36435391d6](https://linux-hardware.org/?probe=36435391d6) | May 09, 2021 |
| ASRock        | Z97 Extreme4                | [d32ca82327](https://linux-hardware.org/?probe=d32ca82327) | May 09, 2021 |
| MSI           | H310M PRO-VD                | [3b0efc8897](https://linux-hardware.org/?probe=3b0efc8897) | May 09, 2021 |
| MSI           | H310M PRO-VD                | [a7348df350](https://linux-hardware.org/?probe=a7348df350) | May 09, 2021 |
| Unknown       | Unknown                     | [e877586cf8](https://linux-hardware.org/?probe=e877586cf8) | May 09, 2021 |
| Unknown       | Unknown                     | [2d5059f0af](https://linux-hardware.org/?probe=2d5059f0af) | May 09, 2021 |
| HP            | 1495                        | [511a9836f9](https://linux-hardware.org/?probe=511a9836f9) | May 09, 2021 |
| Gigabyte      | GA-970A-UD3                 | [e50a48233d](https://linux-hardware.org/?probe=e50a48233d) | May 08, 2021 |
| Gigabyte      | X99-UD7 WIFI-CF             | [87d92ce1b4](https://linux-hardware.org/?probe=87d92ce1b4) | May 08, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | [dcd72d6f14](https://linux-hardware.org/?probe=dcd72d6f14) | May 08, 2021 |
| Dell          | 02YYK5 A01                  | [c7504bbb0c](https://linux-hardware.org/?probe=c7504bbb0c) | May 07, 2021 |
| Dell          | 02YYK5 A01                  | [0933cf325e](https://linux-hardware.org/?probe=0933cf325e) | May 07, 2021 |
| HP            | 339A                        | [1cbf86d8ab](https://linux-hardware.org/?probe=1cbf86d8ab) | May 07, 2021 |
| HP            | 339A                        | [4bbbc757cd](https://linux-hardware.org/?probe=4bbbc757cd) | May 07, 2021 |
| ASRock        | QC5000-ITX/PH               | [67a1a9ec87](https://linux-hardware.org/?probe=67a1a9ec87) | May 07, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | [6fec645dd9](https://linux-hardware.org/?probe=6fec645dd9) | May 07, 2021 |
| ASRock        | QC5000-ITX/PH               | [4ce5ecbbc4](https://linux-hardware.org/?probe=4ce5ecbbc4) | May 07, 2021 |
| Gigabyte      | H170-D3HP-CF                | [b83431d16d](https://linux-hardware.org/?probe=b83431d16d) | May 07, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Linux_Mint/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| Linux Mint 20.1 | 876      | 18.08%  |
| Linux Mint 20.2 | 839      | 17.32%  |
| Linux Mint 19.3 | 825      | 17.03%  |
| Linux Mint 20   | 758      | 15.65%  |
| Linux Mint 20.3 | 498      | 10.28%  |
| Linux Mint 19.1 | 394      | 8.13%   |
| Linux Mint 19.2 | 317      | 6.54%   |
| Linux Mint 19   | 149      | 3.08%   |
| Linux Mint 18.3 | 129      | 2.66%   |
| Linux Mint 18.2 | 30       | 0.62%   |
| Linux Mint 18.1 | 12       | 0.25%   |
| Linux Mint 18   | 9        | 0.19%   |
| Linux Mint 17.3 | 5        | 0.1%    |
| Linux Mint 17.1 | 2        | 0.04%   |
| Linux Mint 13   | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| Linux Mint | 4498     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.0-58-generic  | 206      | 3.76%   |
| 5.4.0-91-generic  | 193      | 3.52%   |
| 5.4.0-42-generic  | 149      | 2.72%   |
| 5.4.0-65-generic  | 147      | 2.68%   |
| 5.4.0-74-generic  | 142      | 2.59%   |
| 5.4.0-77-generic  | 132      | 2.41%   |
| 5.4.0-72-generic  | 117      | 2.13%   |
| 5.4.0-81-generic  | 114      | 2.08%   |
| 5.4.0-66-generic  | 113      | 2.06%   |
| 5.4.0-88-generic  | 112      | 2.04%   |
| 5.0.0-32-generic  | 111      | 2.03%   |
| 5.4.0-90-generic  | 110      | 2.01%   |
| 5.4.0-70-generic  | 107      | 1.95%   |
| 4.15.0-54-generic | 106      | 1.93%   |
| 5.4.0-73-generic  | 103      | 1.88%   |
| 5.4.0-80-generic  | 100      | 1.82%   |
| 5.4.0-107-generic | 100      | 1.82%   |
| 4.15.0-20-generic | 100      | 1.82%   |
| 5.4.0-89-generic  | 88       | 1.61%   |
| 5.4.0-100-generic | 87       | 1.59%   |
| 5.4.0-26-generic  | 81       | 1.48%   |
| 5.4.0-48-generic  | 76       | 1.39%   |
| 4.15.0-46-generic | 70       | 1.28%   |
| 5.4.0-52-generic  | 64       | 1.17%   |
| 5.4.0-96-generic  | 62       | 1.13%   |
| 5.4.0-84-generic  | 60       | 1.09%   |
| 5.4.0-104-generic | 56       | 1.02%   |
| 5.3.0-46-generic  | 56       | 1.02%   |
| 5.4.0-67-generic  | 53       | 0.97%   |
| 5.3.0-40-generic  | 52       | 0.95%   |
| 5.4.0-99-generic  | 51       | 0.93%   |
| 5.4.0-92-generic  | 49       | 0.89%   |
| 5.4.0-97-generic  | 48       | 0.88%   |
| 5.4.0-40-generic  | 48       | 0.88%   |
| 5.3.0-51-generic  | 48       | 0.88%   |
| 5.4.0-47-generic  | 46       | 0.84%   |
| 5.3.0-53-generic  | 46       | 0.84%   |
| 5.0.0-37-generic  | 46       | 0.84%   |
| 4.15.0-72-generic | 46       | 0.84%   |
| 5.4.0-54-generic  | 45       | 0.82%   |
| 5.4.0-64-generic  | 44       | 0.8%    |
| 5.4.0-60-generic  | 44       | 0.8%    |
| 4.15.0-70-generic | 38       | 0.69%   |
| 5.4.0-56-generic  | 37       | 0.68%   |
| 4.15.0-65-generic | 37       | 0.68%   |
| 4.15.0-58-generic | 36       | 0.66%   |
| 5.3.0-28-generic  | 35       | 0.64%   |
| 5.4.0-62-generic  | 34       | 0.62%   |
| 4.15.0-55-generic | 34       | 0.62%   |
| 4.15.0-48-generic | 34       | 0.62%   |
| 5.4.0-109-generic | 33       | 0.6%    |
| 5.4.0-105-generic | 32       | 0.58%   |
| 4.15.0-66-generic | 32       | 0.58%   |
| 5.4.0-94-generic  | 31       | 0.57%   |
| 5.3.0-59-generic  | 29       | 0.53%   |
| 5.3.0-26-generic  | 29       | 0.53%   |
| 5.4.0-45-generic  | 28       | 0.51%   |
| 5.3.0-42-generic  | 28       | 0.51%   |
| 4.15.0-74-generic | 27       | 0.49%   |
| 4.10.0-38-generic | 27       | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 2816     | 59.18%  |
| 4.15.0  | 874      | 18.37%  |
| 5.3.0   | 354      | 7.44%   |
| 5.0.0   | 182      | 3.83%   |
| 5.8.0   | 99       | 2.08%   |
| 5.13.0  | 93       | 1.95%   |
| 5.11.0  | 68       | 1.43%   |
| 4.4.0   | 35       | 0.74%   |
| 4.10.0  | 33       | 0.69%   |
| 4.13.0  | 26       | 0.55%   |
| 4.18.0  | 22       | 0.46%   |
| 4.8.0   | 14       | 0.29%   |
| 5.14.0  | 6        | 0.13%   |
| 5.9.0   | 5        | 0.11%   |
| 5.10.0  | 5        | 0.11%   |
| 5.3.6   | 4        | 0.08%   |
| 5.7.0   | 3        | 0.06%   |
| 5.4.1   | 3        | 0.06%   |
| 5.12.0  | 3        | 0.06%   |
| 5.0.9   | 3        | 0.06%   |
| 4.20.17 | 3        | 0.06%   |
| 4.11.0  | 3        | 0.06%   |
| 5.8.18  | 2        | 0.04%   |
| 5.7.19  | 2        | 0.04%   |
| 5.16.0  | 2        | 0.04%   |
| 5.15.5  | 2        | 0.04%   |
| 5.15.10 | 2        | 0.04%   |
| 5.15.0  | 2        | 0.04%   |
| 5.13.4  | 2        | 0.04%   |
| 5.13.12 | 2        | 0.04%   |
| 5.12.9  | 2        | 0.04%   |
| 5.11.6  | 2        | 0.04%   |
| 5.10.1  | 2        | 0.04%   |
| 5.0.21  | 2        | 0.04%   |
| 4.20.6  | 2        | 0.04%   |
| 4.16.0  | 2        | 0.04%   |
| 3.19.0  | 2        | 0.04%   |
| 3.13.0  | 2        | 0.04%   |
| 5.9.2   | 1        | 0.02%   |
| 5.9.16  | 1        | 0.02%   |
| 5.9.1   | 1        | 0.02%   |
| 5.8.3   | 1        | 0.02%   |
| 5.8.12  | 1        | 0.02%   |
| 5.7.9   | 1        | 0.02%   |
| 5.7.8   | 1        | 0.02%   |
| 5.7.10  | 1        | 0.02%   |
| 5.6.17  | 1        | 0.02%   |
| 5.6.10  | 1        | 0.02%   |
| 5.6.0   | 1        | 0.02%   |
| 5.5.13  | 1        | 0.02%   |
| 5.5.1   | 1        | 0.02%   |
| 5.5.0   | 1        | 0.02%   |
| 5.4.177 | 1        | 0.02%   |
| 5.4.14  | 1        | 0.02%   |
| 5.3.7   | 1        | 0.02%   |
| 5.3.18  | 1        | 0.02%   |
| 5.2.13  | 1        | 0.02%   |
| 5.2.11  | 1        | 0.02%   |
| 5.2.0   | 1        | 0.02%   |
| 5.17.4  | 1        | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 2821     | 59.34%  |
| 4.15    | 875      | 18.41%  |
| 5.3     | 360      | 7.57%   |
| 5.0     | 193      | 4.06%   |
| 5.8     | 103      | 2.17%   |
| 5.13    | 97       | 2.04%   |
| 5.11    | 74       | 1.56%   |
| 4.4     | 35       | 0.74%   |
| 4.10    | 33       | 0.69%   |
| 4.13    | 27       | 0.57%   |
| 4.18    | 23       | 0.48%   |
| 5.10    | 14       | 0.29%   |
| 4.8     | 14       | 0.29%   |
| 5.15    | 11       | 0.23%   |
| 5.9     | 8        | 0.17%   |
| 5.7     | 8        | 0.17%   |
| 4.20    | 8        | 0.17%   |
| 5.14    | 7        | 0.15%   |
| 5.12    | 6        | 0.13%   |
| 5.16    | 5        | 0.11%   |
| 5.6     | 3        | 0.06%   |
| 5.5     | 3        | 0.06%   |
| 5.2     | 3        | 0.06%   |
| 5.17    | 3        | 0.06%   |
| 4.14    | 3        | 0.06%   |
| 4.12    | 3        | 0.06%   |
| 4.11    | 3        | 0.06%   |
| 4.19    | 2        | 0.04%   |
| 4.16    | 2        | 0.04%   |
| 3.19    | 2        | 0.04%   |
| 3.13    | 2        | 0.04%   |
| 4.17    | 1        | 0.02%   |
| 3.2     | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 4315     | 95.8%   |
| i686   | 189      | 4.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| X-Cinnamon      | 2570     | 55.28%  |
| MATE            | 565      | 12.15%  |
| Unknown         | 517      | 11.12%  |
| Cinnamon        | 482      | 10.37%  |
| XFCE            | 373      | 8.02%   |
| GNOME           | 87       | 1.87%   |
| KDE5            | 19       | 0.41%   |
| KDE             | 19       | 0.41%   |
| LXDE            | 6        | 0.13%   |
| KDE4            | 2        | 0.04%   |
| i3              | 2        | 0.04%   |
| Trinity         | 1        | 0.02%   |
| Pantheon        | 1        | 0.02%   |
| LXQt            | 1        | 0.02%   |
| GNOME Flashback | 1        | 0.02%   |
| GNOME Classic   | 1        | 0.02%   |
| enlightenment   | 1        | 0.02%   |
| Budgie          | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 4474     | 99.36%  |
| Tty     | 20       | 0.44%   |
| Wayland | 6        | 0.13%   |
| Unknown | 3        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3090     | 67.61%  |
| TDM     | 775      | 16.96%  |
| LightDM | 638      | 13.96%  |
| MDM     | 41       | 0.9%    |
| SDDM    | 16       | 0.35%   |
| GDM     | 10       | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1090     | 23.77%  |
| Unknown | 679      | 14.81%  |
| de_DE   | 625      | 13.63%  |
| pt_BR   | 382      | 8.33%   |
| en_GB   | 184      | 4.01%   |
| ru_RU   | 182      | 3.97%   |
| fr_FR   | 177      | 3.86%   |
| en_CA   | 119      | 2.6%    |
| es_ES   | 99       | 2.16%   |
| it_IT   | 95       | 2.07%   |
| C       | 93       | 2.03%   |
| pl_PL   | 86       | 1.88%   |
| en_AU   | 77       | 1.68%   |
| nl_NL   | 58       | 1.26%   |
| es_AR   | 50       | 1.09%   |
| ru_UA   | 36       | 0.79%   |
| pt_PT   | 36       | 0.79%   |
| cs_CZ   | 34       | 0.74%   |
| hu_HU   | 28       | 0.61%   |
| es_MX   | 25       | 0.55%   |
| en_ZA   | 24       | 0.52%   |
| en_IN   | 24       | 0.52%   |
| fi_FI   | 23       | 0.5%    |
| de_CH   | 23       | 0.5%    |
| de_AT   | 23       | 0.5%    |
| sv_SE   | 19       | 0.41%   |
| sk_SK   | 18       | 0.39%   |
| fr_CA   | 18       | 0.39%   |
| uk_UA   | 16       | 0.35%   |
| fr_BE   | 16       | 0.35%   |
| tr_TR   | 14       | 0.31%   |
| en_NZ   | 14       | 0.31%   |
| es_CL   | 13       | 0.28%   |
| es_CO   | 11       | 0.24%   |
| en_IE   | 11       | 0.24%   |
| el_GR   | 11       | 0.24%   |
| es_PE   | 10       | 0.22%   |
| zh_CN   | 9        | 0.2%    |
| nl_BE   | 9        | 0.2%    |
| da_DK   | 9        | 0.2%    |
| bg_BG   | 8        | 0.17%   |
| ro_RO   | 7        | 0.15%   |
| ja_JP   | 7        | 0.15%   |
| es_VE   | 7        | 0.15%   |
| es_UY   | 7        | 0.15%   |
| en_PH   | 7        | 0.15%   |
| hr_HR   | 6        | 0.13%   |
| fr_CH   | 6        | 0.13%   |
| nb_NO   | 5        | 0.11%   |
| en_IL   | 4        | 0.09%   |
| ca_ES   | 4        | 0.09%   |
| zh_TW   | 3        | 0.07%   |
| sr_RS   | 3        | 0.07%   |
| lv_LV   | 3        | 0.07%   |
| es_US   | 3        | 0.07%   |
| en_DK   | 3        | 0.07%   |
| sl_SI   | 2        | 0.04%   |
| ko_KR   | 2        | 0.04%   |
| he_IL   | 2        | 0.04%   |
| es_CU   | 2        | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2997     | 65.8%   |
| EFI  | 1558     | 34.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 3870     | 84.39%  |
| Unknown | 511      | 11.14%  |
| Btrfs   | 81       | 1.77%   |
| Overlay | 78       | 1.7%    |
| Xfs     | 17       | 0.37%   |
| Ext2    | 12       | 0.26%   |
| Ext3    | 10       | 0.22%   |
| Zfs     | 2        | 0.04%   |
| Jfs     | 2        | 0.04%   |
| Aufs    | 2        | 0.04%   |
| Tmpfs   | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3152     | 69.2%   |
| GPT     | 823      | 18.07%  |
| MBR     | 580      | 12.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4153     | 91.46%  |
| Yes       | 388      | 8.54%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3677     | 80.9%   |
| Yes       | 868      | 19.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1129     | 25.1%   |
| Gigabyte Technology | 753      | 16.74%  |
| MSI                 | 460      | 10.23%  |
| ASRock              | 447      | 9.94%   |
| Dell                | 370      | 8.23%   |
| Hewlett-Packard     | 314      | 6.98%   |
| Lenovo              | 143      | 3.18%   |
| Intel               | 128      | 2.85%   |
| Acer                | 84       | 1.87%   |
| Pegatron            | 77       | 1.71%   |
| Unknown             | 57       | 1.27%   |
| Foxconn             | 55       | 1.22%   |
| Biostar             | 55       | 1.22%   |
| ECS                 | 49       | 1.09%   |
| Fujitsu             | 40       | 0.89%   |
| Medion              | 35       | 0.78%   |
| Positivo            | 25       | 0.56%   |
| Fujitsu Siemens     | 25       | 0.56%   |
| PCWare              | 15       | 0.33%   |
| Gateway             | 13       | 0.29%   |
| Apple               | 13       | 0.29%   |
| Shuttle             | 12       | 0.27%   |
| eMachines           | 12       | 0.27%   |
| Semp Toshiba        | 11       | 0.24%   |
| Packard Bell        | 9        | 0.2%    |
| Itautec             | 8        | 0.18%   |
| Alienware           | 8        | 0.18%   |
| OEM                 | 7        | 0.16%   |
| Huanan              | 7        | 0.16%   |
| AMI                 | 7        | 0.16%   |
| Supermicro          | 6        | 0.13%   |
| BESSTAR Tech        | 5        | 0.11%   |
| AZW                 | 5        | 0.11%   |
| ABIT                | 5        | 0.11%   |
| TYAN Computer       | 4        | 0.09%   |
| PCChips             | 4        | 0.09%   |
| Megaware            | 4        | 0.09%   |
| AMD                 | 4        | 0.09%   |
| ZOTAC               | 3        | 0.07%   |
| Wistron             | 3        | 0.07%   |
| Quanta              | 3        | 0.07%   |
| Login Informatica   | 3        | 0.07%   |
| HARDKERNEL          | 3        | 0.07%   |
| EVGA                | 3        | 0.07%   |
| Digitron            | 3        | 0.07%   |
| WinFast             | 2        | 0.04%   |
| VS Company          | 2        | 0.04%   |
| TPV-INVENTA         | 2        | 0.04%   |
| SZMZ                | 2        | 0.04%   |
| Philco              | 2        | 0.04%   |
| NEC Computers       | 2        | 0.04%   |
| Minix               | 2        | 0.04%   |
| KLLISRE             | 2        | 0.04%   |
| Inventec            | 2        | 0.04%   |
| INTELBRAS           | 2        | 0.04%   |
| IBM                 | 2        | 0.04%   |
| ECS-USA             | 2        | 0.04%   |
| DFI                 | 2        | 0.04%   |
| AWOW                | 2        | 0.04%   |
| ASRockRack          | 2        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 105      | 2.33%   |
| Unknown                      | 65       | 1.45%   |
| Dell OptiPlex 790            | 25       | 0.56%   |
| MSI MS-7693                  | 23       | 0.51%   |
| ASUS M5A78L-M/USB3           | 23       | 0.51%   |
| Dell OptiPlex 7010           | 21       | 0.47%   |
| Dell OptiPlex 780            | 20       | 0.44%   |
| ASUS PRIME A320M-K           | 20       | 0.44%   |
| ASUS TUF GAMING X570-PLUS    | 19       | 0.42%   |
| Gigabyte B450M DS3H          | 17       | 0.38%   |
| MSI MS-7C02                  | 16       | 0.36%   |
| MSI MS-7817                  | 16       | 0.36%   |
| MSI MS-7721                  | 16       | 0.36%   |
| Dell OptiPlex 755            | 16       | 0.36%   |
| MSI MS-7C37                  | 15       | 0.33%   |
| Dell OptiPlex 9020           | 15       | 0.33%   |
| Dell OptiPlex 390            | 15       | 0.33%   |
| Dell OptiPlex 3020           | 15       | 0.33%   |
| MSI MS-7B79                  | 14       | 0.31%   |
| HP EliteDesk 800 G1 SFF      | 14       | 0.31%   |
| Gigabyte 970A-DS3P           | 14       | 0.31%   |
| ASUS M5A97 R2.0              | 14       | 0.31%   |
| ASUS M5A78L-M PLUS/USB3      | 14       | 0.31%   |
| HP Compaq Elite 8300 SFF     | 13       | 0.29%   |
| Gigabyte G31M-ES2L           | 13       | 0.29%   |
| Dell OptiPlex 745            | 13       | 0.29%   |
| ASUS ROG STRIX B450-F GAMING | 13       | 0.29%   |
| HP Compaq 8200 Elite SFF PC  | 12       | 0.27%   |
| ASUS PRIME B350-PLUS         | 12       | 0.27%   |
| ASRock N68C-S UCC            | 12       | 0.27%   |
| ASRock A320M-HD              | 12       | 0.27%   |
| MSI MS-7A34                  | 11       | 0.24%   |
| Intel H61                    | 11       | 0.24%   |
| Dell OptiPlex 990            | 11       | 0.24%   |
| ASUS SABERTOOTH 990FX R2.0   | 11       | 0.24%   |
| ASUS PRIME B450M-A           | 11       | 0.24%   |
| ASRock B450M Pro4            | 11       | 0.24%   |
| Semp Toshiba STI             | 10       | 0.22%   |
| MSI MS-7C56                  | 10       | 0.22%   |
| MSI MS-7B86                  | 10       | 0.22%   |
| MSI MS-7641                  | 10       | 0.22%   |
| Gigabyte GA-970A-UD3         | 10       | 0.22%   |
| Gigabyte GA-78LMT-USB3       | 10       | 0.22%   |
| Gigabyte A320M-S2H           | 10       | 0.22%   |
| Dell OptiPlex 3010           | 10       | 0.22%   |
| ASUS M5A97 LE R2.0           | 10       | 0.22%   |
| MSI MS-7788                  | 9        | 0.2%    |
| HP Z400 Workstation          | 9        | 0.2%    |
| Gigabyte GA-78LMT-USB3 6.0   | 9        | 0.2%    |
| Gigabyte B450 AORUS ELITE    | 9        | 0.2%    |
| Dell OptiPlex 760            | 9        | 0.2%    |
| ASUS P5Q                     | 9        | 0.2%    |
| ASUS M5A99X EVO R2.0         | 9        | 0.2%    |
| MSI MS-7C91                  | 8        | 0.18%   |
| MSI MS-7C52                  | 8        | 0.18%   |
| HP Compaq Pro 6300 SFF       | 8        | 0.18%   |
| HP Compaq 8200 Elite CMT PC  | 8        | 0.18%   |
| HP Compaq 6005 Pro SFF PC    | 8        | 0.18%   |
| Gigabyte GA-78LMT-S2P        | 8        | 0.18%   |
| Gigabyte GA-78LMT-S2         | 8        | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 231      | 5.14%   |
| ASUS PRIME              | 173      | 3.85%   |
| HP Compaq               | 154      | 3.42%   |
| ASUS All                | 105      | 2.33%   |
| Lenovo ThinkCentre      | 95       | 2.11%   |
| Unknown                 | 65       | 1.45%   |
| ASUS ROG                | 64       | 1.42%   |
| ASUS TUF                | 57       | 1.27%   |
| ASUS M5A78L-M           | 56       | 1.24%   |
| Acer Aspire             | 53       | 1.18%   |
| Dell Inspiron           | 51       | 1.13%   |
| HP EliteDesk            | 38       | 0.84%   |
| ASUS P8H61-M            | 35       | 0.78%   |
| ASUS M5A97              | 34       | 0.76%   |
| Dell Precision          | 30       | 0.67%   |
| Fujitsu ESPRIMO         | 27       | 0.6%    |
| Gigabyte GA-78LMT-USB3  | 25       | 0.56%   |
| Gigabyte B450           | 25       | 0.56%   |
| ASUS SABERTOOTH         | 24       | 0.53%   |
| MSI MS-7693             | 23       | 0.51%   |
| ASRock B450M            | 23       | 0.51%   |
| Gigabyte B450M          | 22       | 0.49%   |
| Acer Veriton            | 22       | 0.49%   |
| HP ProDesk              | 19       | 0.42%   |
| Dell Vostro             | 19       | 0.42%   |
| MSI MS-7C02             | 16       | 0.36%   |
| MSI MS-7817             | 16       | 0.36%   |
| MSI MS-7721             | 16       | 0.36%   |
| Gigabyte X570           | 16       | 0.36%   |
| Gigabyte A320M-S2H      | 16       | 0.36%   |
| ASUS P5KPL-AM           | 16       | 0.36%   |
| ASUS P5G41T-M           | 16       | 0.36%   |
| MSI MS-7C37             | 15       | 0.33%   |
| HP Pavilion             | 15       | 0.33%   |
| Gigabyte B550           | 15       | 0.33%   |
| Gigabyte 970A-DS3P      | 15       | 0.33%   |
| Fujitsu Siemens ESPRIMO | 15       | 0.33%   |
| Dell XPS                | 15       | 0.33%   |
| ASRock 970              | 15       | 0.33%   |
| MSI MS-7B79             | 14       | 0.31%   |
| Gigabyte Z390           | 14       | 0.31%   |
| ASUS P8Z77-V            | 14       | 0.31%   |
| Lenovo IdeaCentre       | 13       | 0.29%   |
| Gigabyte G31M-ES2L      | 13       | 0.29%   |
| ASUS P5Q                | 13       | 0.29%   |
| Intel H61               | 12       | 0.27%   |
| ASUS P8Z68-V            | 12       | 0.27%   |
| ASUS Maximus            | 12       | 0.27%   |
| ASRock N68C-S           | 12       | 0.27%   |
| ASRock A320M-HDV        | 12       | 0.27%   |
| ASRock A320M-HD         | 12       | 0.27%   |
| Semp Toshiba STI        | 11       | 0.24%   |
| MSI MS-7A34             | 11       | 0.24%   |
| ASUS P8H67-M            | 11       | 0.24%   |
| ASUS P8B75-M            | 11       | 0.24%   |
| ASUS M5A99X             | 11       | 0.24%   |
| MSI MS-7C56             | 10       | 0.22%   |
| MSI MS-7B86             | 10       | 0.22%   |
| MSI MS-7641             | 10       | 0.22%   |
| Lenovo ThinkStation     | 10       | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 503      | 11.18%  |
| 2011    | 440      | 9.78%   |
| 2013    | 394      | 8.76%   |
| 2018    | 370      | 8.23%   |
| 2009    | 322      | 7.16%   |
| 2010    | 320      | 7.11%   |
| 2014    | 303      | 6.74%   |
| 2017    | 260      | 5.78%   |
| 2019    | 257      | 5.71%   |
| 2020    | 239      | 5.31%   |
| 2008    | 239      | 5.31%   |
| 2007    | 221      | 4.91%   |
| 2015    | 204      | 4.54%   |
| 2016    | 181      | 4.02%   |
| 2006    | 91       | 2.02%   |
| 2021    | 88       | 1.96%   |
| 2005    | 31       | 0.69%   |
| 2004    | 13       | 0.29%   |
| 2003    | 11       | 0.24%   |
| 2022    | 6        | 0.13%   |
| 2002    | 3        | 0.07%   |
| Unknown | 2        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4498     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 4386     | 97.27%  |
| Enabled  | 123      | 2.73%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4496     | 99.96%  |
| Yes  | 2        | 0.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1024     | 22.31%  |
| 8.01-16.0       | 955      | 20.81%  |
| 3.01-4.0        | 920      | 20.05%  |
| 4.01-8.0        | 753      | 16.41%  |
| 32.01-64.0      | 455      | 9.92%   |
| 1.01-2.0        | 215      | 4.69%   |
| 64.01-256.0     | 90       | 1.96%   |
| 2.01-3.0        | 82       | 1.79%   |
| 24.01-32.0      | 63       | 1.37%   |
| 0.51-1.0        | 30       | 0.65%   |
| More than 256.0 | 1        | 0.02%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 1990     | 39.39%  |
| 2.01-3.0   | 1269     | 25.12%  |
| 4.01-8.0   | 577      | 11.42%  |
| 3.01-4.0   | 549      | 10.87%  |
| 0.51-1.0   | 473      | 9.36%   |
| 8.01-16.0  | 143      | 2.83%   |
| 0.01-0.5   | 21       | 0.42%   |
| 16.01-24.0 | 15       | 0.3%    |
| 24.01-32.0 | 10       | 0.2%    |
| Unknown    | 3        | 0.06%   |
| 32.01-64.0 | 2        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1916     | 41.02%  |
| 2       | 1384     | 29.63%  |
| 3       | 717      | 15.35%  |
| 4       | 356      | 7.62%   |
| 5       | 153      | 3.28%   |
| 6       | 59       | 1.26%   |
| 7       | 31       | 0.66%   |
| 0       | 28       | 0.6%    |
| 8       | 15       | 0.32%   |
| 9       | 6        | 0.13%   |
| 10      | 3        | 0.06%   |
| 22      | 1        | 0.02%   |
| 14      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2649     | 58.27%  |
| No        | 1897     | 41.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4440     | 98.67%  |
| No        | 60       | 1.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2705     | 59.29%  |
| Yes       | 1857     | 40.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3479     | 76.24%  |
| Yes       | 1084     | 23.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 775      | 17.13%  |
| Germany                | 715      | 15.8%   |
| Brazil                 | 561      | 12.4%   |
| Russia                 | 312      | 6.9%    |
| France                 | 195      | 4.31%   |
| UK                     | 190      | 4.2%    |
| Canada                 | 167      | 3.69%   |
| Spain                  | 122      | 2.7%    |
| Italy                  | 107      | 2.36%   |
| Ukraine                | 105      | 2.32%   |
| Netherlands            | 103      | 2.28%   |
| Poland                 | 102      | 2.25%   |
| Australia              | 91       | 2.01%   |
| Argentina              | 56       | 1.24%   |
| Switzerland            | 48       | 1.06%   |
| Austria                | 46       | 1.02%   |
| Belgium                | 44       | 0.97%   |
| Czechia                | 43       | 0.95%   |
| Hungary                | 41       | 0.91%   |
| Sweden                 | 39       | 0.86%   |
| Portugal               | 37       | 0.82%   |
| Mexico                 | 35       | 0.77%   |
| Finland                | 32       | 0.71%   |
| South Africa           | 31       | 0.69%   |
| India                  | 30       | 0.66%   |
| Romania                | 24       | 0.53%   |
| Denmark                | 22       | 0.49%   |
| Slovakia               | 21       | 0.46%   |
| Greece                 | 20       | 0.44%   |
| Turkey                 | 18       | 0.4%    |
| Serbia                 | 17       | 0.38%   |
| New Zealand            | 17       | 0.38%   |
| Chile                  | 17       | 0.38%   |
| Bulgaria               | 17       | 0.38%   |
| Belarus                | 17       | 0.38%   |
| Norway                 | 16       | 0.35%   |
| Japan                  | 16       | 0.35%   |
| Colombia               | 16       | 0.35%   |
| Ireland                | 15       | 0.33%   |
| Indonesia              | 15       | 0.33%   |
| Croatia                | 15       | 0.33%   |
| Taiwan                 | 10       | 0.22%   |
| Peru                   | 10       | 0.22%   |
| China                  | 10       | 0.22%   |
| Venezuela              | 9        | 0.2%    |
| Malaysia               | 9        | 0.2%    |
| Israel                 | 9        | 0.2%    |
| Philippines            | 8        | 0.18%   |
| Latvia                 | 8        | 0.18%   |
| Egypt                  | 8        | 0.18%   |
| Uruguay                | 7        | 0.15%   |
| South Korea            | 7        | 0.15%   |
| Slovenia               | 7        | 0.15%   |
| Thailand               | 6        | 0.13%   |
| Iran                   | 6        | 0.13%   |
| Costa Rica             | 6        | 0.13%   |
| Bosnia and Herzegovina | 6        | 0.13%   |
| Puerto Rico            | 5        | 0.11%   |
| Pakistan               | 5        | 0.11%   |
| Lithuania              | 5        | 0.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 56       | 1.17%   |
| Sao Paulo         | 55       | 1.15%   |
| Berlin            | 49       | 1.02%   |
| Rio de Janeiro    | 32       | 0.67%   |
| Paris             | 32       | 0.67%   |
| Vienna            | 30       | 0.63%   |
| Hamburg           | 30       | 0.63%   |
| London            | 26       | 0.54%   |
| Frankfurt am Main | 26       | 0.54%   |
| Kyiv              | 25       | 0.52%   |
| Munich            | 24       | 0.5%    |
| Sydney            | 22       | 0.46%   |
| St Petersburg     | 21       | 0.44%   |
| Warsaw            | 20       | 0.42%   |
| Montreal          | 18       | 0.38%   |
| Madrid            | 18       | 0.38%   |
| Amsterdam         | 18       | 0.38%   |
| Leipzig           | 16       | 0.33%   |
| Budapest          | 16       | 0.33%   |
| BrasГ­lia       | 15       | 0.31%   |
| Toronto           | 14       | 0.29%   |
| New York          | 14       | 0.29%   |
| Helsinki          | 14       | 0.29%   |
| Cologne           | 14       | 0.29%   |
| Chicago           | 14       | 0.29%   |
| Vancouver         | 13       | 0.27%   |
| Stuttgart         | 13       | 0.27%   |
| Belo Horizonte    | 13       | 0.27%   |
| Belgrade          | 13       | 0.27%   |
| Rome              | 12       | 0.25%   |
| Porto Alegre      | 12       | 0.25%   |
| Perth             | 12       | 0.25%   |
| Curitiba          | 12       | 0.25%   |
| Brisbane          | 12       | 0.25%   |
| Barcelona         | 12       | 0.25%   |
| Zurich            | 11       | 0.23%   |
| Mexico City       | 11       | 0.23%   |
| Essen             | 11       | 0.23%   |
| Dresden           | 11       | 0.23%   |
| Zagreb            | 10       | 0.21%   |
| Recife            | 10       | 0.21%   |
| Natal             | 10       | 0.21%   |
| Minsk             | 10       | 0.21%   |
| Miami             | 10       | 0.21%   |
| Melbourne         | 10       | 0.21%   |
| Edmonton          | 10       | 0.21%   |
| Phoenix           | 9        | 0.19%   |
| Milan             | 9        | 0.19%   |
| Lisbon            | 9        | 0.19%   |
| Las Vegas         | 9        | 0.19%   |
| Johannesburg      | 9        | 0.19%   |
| Guarulhos         | 9        | 0.19%   |
| Fortaleza         | 9        | 0.19%   |
| Dallas            | 9        | 0.19%   |
| Chelyabinsk       | 9        | 0.19%   |
| Campinas          | 9        | 0.19%   |
| Buenos Aires      | 9        | 0.19%   |
| Athens            | 9        | 0.19%   |
| Stockholm         | 8        | 0.17%   |
| Sofia             | 8        | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 1716     | 2913   | 21.72%  |
| Seagate                   | 1666     | 2699   | 21.09%  |
| Samsung Electronics       | 1137     | 1825   | 14.39%  |
| Kingston                  | 492      | 668    | 6.23%   |
| Toshiba                   | 373      | 477    | 4.72%   |
| Hitachi                   | 364      | 496    | 4.61%   |
| SanDisk                   | 313      | 440    | 3.96%   |
| Crucial                   | 292      | 417    | 3.7%    |
| A-DATA Technology         | 114      | 151    | 1.44%   |
| MAXTOR                    | 99       | 141    | 1.25%   |
| Intel                     | 92       | 128    | 1.16%   |
| HGST                      | 78       | 110    | 0.99%   |
| Unknown                   | 74       | 110    | 0.94%   |
| China                     | 72       | 88     | 0.91%   |
| Intenso                   | 63       | 87     | 0.8%    |
| Phison                    | 62       | 89     | 0.78%   |
| OCZ                       | 50       | 65     | 0.63%   |
| SPCC                      | 49       | 66     | 0.62%   |
| Patriot                   | 46       | 53     | 0.58%   |
| Corsair                   | 44       | 53     | 0.56%   |
| PNY                       | 38       | 50     | 0.48%   |
| Transcend                 | 36       | 57     | 0.46%   |
| GOODRAM                   | 28       | 34     | 0.35%   |
| Silicon Motion            | 27       | 51     | 0.34%   |
| Micron Technology         | 24       | 30     | 0.3%    |
| XPG                       | 23       | 33     | 0.29%   |
| SK Hynix                  | 22       | 34     | 0.28%   |
| PLEXTOR                   | 22       | 30     | 0.28%   |
| Apacer                    | 22       | 26     | 0.28%   |
| JMicron                   | 19       | 25     | 0.24%   |
| Fujitsu                   | 18       | 26     | 0.23%   |
| Team                      | 17       | 23     | 0.22%   |
| Micron/Crucial Technology | 16       | 22     | 0.2%    |
| ASMT                      | 16       | 25     | 0.2%    |
| Lexar                     | 15       | 16     | 0.19%   |
| KingSpec                  | 15       | 28     | 0.19%   |
| Hewlett-Packard           | 14       | 16     | 0.18%   |
| Unknown                   | 13       | 20     | 0.16%   |
| LITEON                    | 12       | 13     | 0.15%   |
| WD MediaMax               | 11       | 20     | 0.14%   |
| TO Exter                  | 11       | 13     | 0.14%   |
| Gigabyte Technology       | 11       | 25     | 0.14%   |
| Realtek Semiconductor     | 10       | 11     | 0.13%   |
| SABRENT                   | 8        | 9      | 0.1%    |
| LITEONIT                  | 8        | 8      | 0.1%    |
| ExcelStor                 | 8        | 10     | 0.1%    |
| asmedia                   | 8        | 10     | 0.1%    |
| Smartbuy                  | 7        | 11     | 0.09%   |
| Mushkin                   | 7        | 9      | 0.09%   |
| KingDian                  | 7        | 7      | 0.09%   |
| AMD                       | 7        | 7      | 0.09%   |
| Verbatim                  | 6        | 7      | 0.08%   |
| EMTEC                     | 6        | 8      | 0.08%   |
| Pioneer                   | 5        | 6      | 0.06%   |
| Netac                     | 5        | 6      | 0.06%   |
| Lite-On                   | 5        | 5      | 0.06%   |
| USB30                     | 4        | 4      | 0.05%   |
| TCSUNBOW                  | 4        | 5      | 0.05%   |
| Leven                     | 4        | 4      | 0.05%   |
| LDLC                      | 4        | 4      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 140      | 1.54%   |
| Kingston SA400S37240G 240GB SSD  | 123      | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB   | 103      | 1.13%   |
| Toshiba DT01ACA100 1TB           | 98       | 1.08%   |
| Samsung SSD 850 EVO 250GB        | 86       | 0.94%   |
| Samsung SSD 860 EVO 500GB        | 75       | 0.82%   |
| WDC WD10EZEX-08WN4A0 1TB         | 73       | 0.8%    |
| Kingston SA400S37120G 120GB SSD  | 73       | 0.8%    |
| Seagate ST1000DM003-1CH162 1TB   | 70       | 0.77%   |
| Kingston SV300S37A120G 120GB SSD | 69       | 0.76%   |
| Seagate ST3500418AS 500GB        | 66       | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB   | 60       | 0.66%   |
| Samsung SSD 860 EVO 1TB          | 56       | 0.62%   |
| Seagate ST2000DM006-2DM164 2TB   | 55       | 0.6%    |
| Seagate ST1000DM003-1ER162 1TB   | 55       | 0.6%    |
| Samsung SSD 850 EVO 500GB        | 53       | 0.58%   |
| Samsung SSD 860 EVO 250GB        | 51       | 0.56%   |
| Crucial CT240BX500SSD1 240GB     | 49       | 0.54%   |
| Seagate ST31000524AS 1TB         | 48       | 0.53%   |
| WDC WD10EZEX-00BN5A0 1TB         | 47       | 0.52%   |
| Samsung NVMe SSD Drive 500GB     | 47       | 0.52%   |
| Kingston SA400S37480G 480GB SSD  | 45       | 0.49%   |
| Toshiba HDWD110 1TB              | 44       | 0.48%   |
| Seagate ST31000528AS 1TB         | 44       | 0.48%   |
| Seagate Expansion+ 2TB           | 41       | 0.45%   |
| Crucial CT500MX500SSD1 500GB     | 39       | 0.43%   |
| SanDisk SSD PLUS 240GB           | 38       | 0.42%   |
| SanDisk SDSSDA240G 240GB         | 38       | 0.42%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 37       | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB   | 37       | 0.41%   |
| Seagate ST2000DM001-1CH164 2TB   | 37       | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 36       | 0.4%    |
| Seagate ST3500413AS 500GB        | 36       | 0.4%    |
| Seagate ST4000DM004-2CV104 4TB   | 34       | 0.37%   |
| Toshiba DT01ACA200 2TB           | 33       | 0.36%   |
| Crucial CT1000MX500SSD1 1TB      | 33       | 0.36%   |
| Toshiba DT01ACA050 500GB         | 32       | 0.35%   |
| Samsung HD322HJ 320GB            | 31       | 0.34%   |
| Hitachi HDS721010CLA332 1TB      | 31       | 0.34%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 30       | 0.33%   |
| WDC WD10EARS-00Y5B1 1TB          | 30       | 0.33%   |
| Samsung HD502HJ 500GB            | 30       | 0.33%   |
| Unknown SD/MMC/MS PRO 16GB       | 29       | 0.32%   |
| Seagate ST3500312CS 500GB        | 28       | 0.31%   |
| Seagate ST1000DM003-1SB102 1TB   | 28       | 0.31%   |
| Samsung HD103SJ 1TB              | 28       | 0.31%   |
| Samsung SSD 840 EVO 250GB        | 27       | 0.3%    |
| WDC WD20EARX-00PASB0 2TB         | 26       | 0.29%   |
| WDC WD10EZEX-00WN4A0 1TB         | 26       | 0.29%   |
| Samsung HD502HI 500GB            | 26       | 0.29%   |
| Samsung HD103UJ 1TB              | 26       | 0.29%   |
| Seagate Expansion Desk 4TB       | 25       | 0.27%   |
| Samsung NVMe SSD Drive 250GB     | 25       | 0.27%   |
| Samsung NVMe SSD Drive 1TB       | 25       | 0.27%   |
| Samsung HD161HJ 160GB            | 25       | 0.27%   |
| Kingston SV300S37A240G 240GB SSD | 25       | 0.27%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 24       | 0.26%   |
| WDC WD20EZRX-00D8PB0 2TB         | 23       | 0.25%   |
| Seagate ST3250318AS 250GB        | 23       | 0.25%   |
| Samsung SSD 860 QVO 1TB          | 23       | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1639     | 2626   | 35.47%  |
| WDC                 | 1560     | 2640   | 33.76%  |
| Samsung Electronics | 400      | 571    | 8.66%   |
| Hitachi             | 364      | 496    | 7.88%   |
| Toshiba             | 348      | 440    | 7.53%   |
| MAXTOR              | 97       | 139    | 2.1%    |
| HGST                | 78       | 110    | 1.69%   |
| Unknown             | 35       | 48     | 0.76%   |
| Fujitsu             | 18       | 26     | 0.39%   |
| ASMT                | 14       | 18     | 0.3%    |
| SABRENT             | 8        | 9      | 0.17%   |
| Intenso             | 8        | 9      | 0.17%   |
| ExcelStor           | 6        | 8      | 0.13%   |
| WD MediaMax         | 5        | 13     | 0.11%   |
| JMicron             | 4        | 6      | 0.09%   |
| ASMT109x            | 3        | 3      | 0.06%   |
| asmedia             | 3        | 3      | 0.06%   |
| Apple               | 3        | 3      | 0.06%   |
| Maxtor 6            | 2        | 3      | 0.04%   |
| HPE                 | 2        | 3      | 0.04%   |
| Hewlett-Packard     | 2        | 2      | 0.04%   |
| Unknown             | 2        | 4      | 0.04%   |
| USB3.0              | 1        | 1      | 0.02%   |
| USB 3.0             | 1        | 2      | 0.02%   |
| USB                 | 1        | 1      | 0.02%   |
| TrueNAS             | 1        | 3      | 0.02%   |
| SYNOLOGY            | 1        | 1      | 0.02%   |
| QUANTUM             | 1        | 1      | 0.02%   |
| PHD 3.0             | 1        | 2      | 0.02%   |
| Maxone              | 1        | 1      | 0.02%   |
| MaxDigital          | 1        | 1      | 0.02%   |
| MARVELL             | 1        | 1      | 0.02%   |
| Magnetic Data       | 1        | 1      | 0.02%   |
| LaCie               | 1        | 1      | 0.02%   |
| KESU                | 1        | 1      | 0.02%   |
| IB                  | 1        | 2      | 0.02%   |
| HGST HTS            | 1        | 1      | 0.02%   |
| FEASSO              | 1        | 2      | 0.02%   |
| Config              | 1        | 1      | 0.02%   |
| CLOVER              | 1        | 1      | 0.02%   |
| China               | 1        | 1      | 0.02%   |
| Apricorn            | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 577      | 903    | 21.88%  |
| Kingston            | 445      | 602    | 16.88%  |
| Crucial             | 274      | 394    | 10.39%  |
| SanDisk             | 264      | 369    | 10.01%  |
| WDC                 | 182      | 238    | 6.9%    |
| A-DATA Technology   | 90       | 121    | 3.41%   |
| China               | 70       | 86     | 2.65%   |
| Intel               | 60       | 78     | 2.28%   |
| OCZ                 | 49       | 63     | 1.86%   |
| SPCC                | 47       | 64     | 1.78%   |
| Intenso             | 45       | 62     | 1.71%   |
| Patriot             | 43       | 50     | 1.63%   |
| PNY                 | 35       | 46     | 1.33%   |
| Transcend           | 32       | 46     | 1.21%   |
| Corsair             | 32       | 37     | 1.21%   |
| Toshiba             | 28       | 33     | 1.06%   |
| GOODRAM             | 28       | 34     | 1.06%   |
| Micron Technology   | 20       | 26     | 0.76%   |
| Apacer              | 20       | 24     | 0.76%   |
| PLEXTOR             | 19       | 24     | 0.72%   |
| Team                | 16       | 22     | 0.61%   |
| KingSpec            | 15       | 28     | 0.57%   |
| Lexar               | 13       | 14     | 0.49%   |
| Seagate             | 12       | 18     | 0.46%   |
| LITEON              | 12       | 13     | 0.46%   |
| TO Exter            | 11       | 13     | 0.42%   |
| SK Hynix            | 9        | 13     | 0.34%   |
| Hewlett-Packard     | 9        | 11     | 0.34%   |
| LITEONIT            | 8        | 8      | 0.3%    |
| Unknown             | 7        | 7      | 0.27%   |
| KingDian            | 7        | 7      | 0.27%   |
| Unknown             | 7        | 11     | 0.27%   |
| Verbatim            | 6        | 7      | 0.23%   |
| Smartbuy            | 6        | 10     | 0.23%   |
| Mushkin             | 6        | 8      | 0.23%   |
| JMicron             | 6        | 8      | 0.23%   |
| Gigabyte Technology | 6        | 19     | 0.23%   |
| AMD                 | 6        | 6      | 0.23%   |
| Pioneer             | 5        | 6      | 0.19%   |
| USB30               | 4        | 4      | 0.15%   |
| Netac               | 4        | 5      | 0.15%   |
| Leven               | 4        | 4      | 0.15%   |
| LDLC                | 4        | 4      | 0.15%   |
| External            | 4        | 4      | 0.15%   |
| EMTEC               | 4        | 5      | 0.15%   |
| ASMedia             | 4        | 5      | 0.15%   |
| TCSUNBOW            | 3        | 4      | 0.11%   |
| KIOXIA-EXCERIA      | 3        | 3      | 0.11%   |
| Kingmax             | 3        | 3      | 0.11%   |
| INNOVATION IT       | 3        | 4      | 0.11%   |
| Vaseky              | 2        | 3      | 0.08%   |
| THU                 | 2        | 2      | 0.08%   |
| Super Talent        | 2        | 2      | 0.08%   |
| Pichau              | 2        | 2      | 0.08%   |
| NGFF                | 2        | 2      | 0.08%   |
| MAXTOR              | 2        | 2      | 0.08%   |
| Lenovo              | 2        | 4      | 0.08%   |
| DREVO               | 2        | 2      | 0.08%   |
| DOGFISH             | 2        | 2      | 0.08%   |
| BLUERAY             | 2        | 2      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 3498     | 7206   | 53.82%  |
| SSD     | 2230     | 3661   | 34.31%  |
| NVMe    | 637      | 960    | 9.8%    |
| Unknown | 119      | 176    | 1.83%   |
| MMC     | 16       | 23     | 0.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4289     | 10518  | 81.26%  |
| NVMe | 637      | 957    | 12.07%  |
| SAS  | 336      | 528    | 6.37%   |
| MMC  | 16       | 23     | 0.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 3326     | 6150   | 53.4%   |
| 0.51-1.0   | 1778     | 2812   | 28.55%  |
| 1.01-2.0   | 668      | 1133   | 10.73%  |
| 3.01-4.0   | 207      | 368    | 3.32%   |
| 2.01-3.0   | 166      | 265    | 2.67%   |
| 4.01-10.0  | 72       | 117    | 1.16%   |
| 10.01-20.0 | 9        | 20     | 0.14%   |
| 0          | 2        | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1214     | 25.45%  |
| 251-500        | 929      | 19.48%  |
| 501-1000       | 783      | 16.42%  |
| 1001-2000      | 590      | 12.37%  |
| More than 3000 | 437      | 9.16%   |
| 51-100         | 293      | 6.14%   |
| 2001-3000      | 288      | 6.04%   |
| 21-50          | 124      | 2.6%    |
| 1-20           | 82       | 1.72%   |
| Unknown        | 30       | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1103     | 22.19%  |
| 21-50          | 961      | 19.34%  |
| 101-250        | 742      | 14.93%  |
| 51-100         | 643      | 12.94%  |
| 251-500        | 451      | 9.07%   |
| 501-1000       | 441      | 8.87%   |
| 1001-2000      | 315      | 6.34%   |
| More than 3000 | 158      | 3.18%   |
| 2001-3000      | 126      | 2.54%   |
| Unknown        | 30       | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 22       | 22     | 4.25%   |
| Seagate ST3500418AS 500GB             | 14       | 16     | 2.7%    |
| Seagate ST1000DM003-9YN162 1TB        | 6        | 6      | 1.16%   |
| WDC WD10EZEX-00BN5A0 1TB              | 5        | 6      | 0.97%   |
| WDC WD10EARS-00Y5B1 1TB               | 5        | 5      | 0.97%   |
| Seagate ST3500320AS 500GB             | 5        | 7      | 0.97%   |
| Seagate ST31000524AS 1TB              | 5        | 6      | 0.97%   |
| Seagate ST1000DM003-1CH162 1TB        | 5        | 6      | 0.97%   |
| Samsung Electronics HD502HI 500GB     | 5        | 5      | 0.97%   |
| Crucial CT525MX300SSD1 528GB          | 5        | 5      | 0.97%   |
| WDC WD3200AAJS-00L7A0 320GB           | 4        | 4      | 0.77%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 4        | 4      | 0.77%   |
| Seagate ST31500341AS 1TB              | 4        | 5      | 0.77%   |
| Seagate ST31000528AS 1TB              | 4        | 4      | 0.77%   |
| Seagate ST2000DM001-9YN164 2TB        | 4        | 4      | 0.77%   |
| Samsung Electronics HD322HJ 320GB     | 4        | 4      | 0.77%   |
| Samsung Electronics HD161HJ 160GB     | 4        | 4      | 0.77%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 4      | 0.77%   |
| MAXTOR STM3250310AS 250GB             | 4        | 5      | 0.77%   |
| Hitachi HDS721010CLA332 1TB           | 4        | 4      | 0.77%   |
| WDC WD5000AAKX-003CA0 500GB           | 3        | 3      | 0.58%   |
| WDC WD5000AAKX-001CA0 500GB           | 3        | 3      | 0.58%   |
| WDC WD5000AAKS-00A7B0 500GB           | 3        | 3      | 0.58%   |
| WDC WD3200AAJS-56M0A0 320GB           | 3        | 3      | 0.58%   |
| WDC WD20EZRX-00DC0B0 2TB              | 3        | 7      | 0.58%   |
| Seagate ST9250315AS 250GB             | 3        | 3      | 0.58%   |
| Seagate ST3250820AS 250GB             | 3        | 3      | 0.58%   |
| Seagate ST3250318AS 250GB             | 3        | 4      | 0.58%   |
| Seagate ST320LT012-1DG14C 320GB       | 3        | 3      | 0.58%   |
| Seagate ST31000333AS 1TB              | 3        | 3      | 0.58%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.58%   |
| Seagate ST1500DL003-9VT16L 1TB        | 3        | 3      | 0.58%   |
| Samsung Electronics SSD 970 EVO 500GB | 3        | 4      | 0.58%   |
| Samsung Electronics SP2504C 250GB     | 3        | 3      | 0.58%   |
| Kingston SHFS37A120G 120GB SSD        | 3        | 3      | 0.58%   |
| Hitachi HDS728080PLA380 80GB          | 3        | 4      | 0.58%   |
| Hitachi HDS721050CLA362 500GB         | 3        | 3      | 0.58%   |
| Hitachi HDP725050GLA360 500GB         | 3        | 7      | 0.58%   |
| Corsair Force LS SSD 240GB            | 3        | 6      | 0.58%   |
| WDC WD6401AALS-00L3B2 640GB           | 2        | 3      | 0.39%   |
| WDC WD5002ABYS-01B1B0 500GB           | 2        | 12     | 0.39%   |
| WDC WD5000AVDS-63U7B1 500GB           | 2        | 2      | 0.39%   |
| WDC WD40EFRX-68WT0N0 4TB              | 2        | 2      | 0.39%   |
| WDC WD3200AAJS-60Z0A0 320GB           | 2        | 2      | 0.39%   |
| WDC WD20EFRX-68EUZN0 2TB              | 2        | 3      | 0.39%   |
| WDC WD20EARX-00PASB0 2TB              | 2        | 2      | 0.39%   |
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 0.39%   |
| WDC WD1600BEVT-22A23T0 160GB          | 2        | 2      | 0.39%   |
| WDC WD15EARS-00MVWB0 1TB              | 2        | 2      | 0.39%   |
| WDC WD10EARS-22Y5B1 1TB               | 2        | 2      | 0.39%   |
| WDC WD10EADS-00L5B1 1TB               | 2        | 2      | 0.39%   |
| WDC WD1003FZEX-00MK2A0 1TB            | 2        | 2      | 0.39%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 2      | 0.39%   |
| Toshiba DT01ACA300 3TB                | 2        | 2      | 0.39%   |
| Toshiba DT01ACA050 500GB              | 2        | 2      | 0.39%   |
| Seagate ST9320325AS 320GB             | 2        | 2      | 0.39%   |
| Seagate ST500NM0011 500GB             | 2        | 2      | 0.39%   |
| Seagate ST500LT012-1DG142 500GB       | 2        | 2      | 0.39%   |
| Seagate ST4000VN008-2DR166 4TB        | 2        | 2      | 0.39%   |
| Seagate ST380817AS 80GB               | 2        | 2      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 156      | 181    | 31.9%   |
| WDC                 | 133      | 166    | 27.2%   |
| Samsung Electronics | 59       | 69     | 12.07%  |
| Hitachi             | 39       | 47     | 7.98%   |
| MAXTOR              | 13       | 17     | 2.66%   |
| Crucial             | 13       | 14     | 2.66%   |
| Toshiba             | 12       | 12     | 2.45%   |
| Kingston            | 11       | 12     | 2.25%   |
| SanDisk             | 9        | 10     | 1.84%   |
| Corsair             | 6        | 9      | 1.23%   |
| Intel               | 5        | 5      | 1.02%   |
| OCZ                 | 3        | 3      | 0.61%   |
| A-DATA Technology   | 3        | 3      | 0.61%   |
| SPCC                | 2        | 2      | 0.41%   |
| PLEXTOR             | 2        | 2      | 0.41%   |
| LDLC                | 2        | 2      | 0.41%   |
| Kingmax             | 2        | 2      | 0.41%   |
| Intenso             | 2        | 2      | 0.41%   |
| HGST                | 2        | 2      | 0.41%   |
| China               | 2        | 3      | 0.41%   |
| Unknown             | 1        | 1      | 0.2%    |
| Transcend           | 1        | 1      | 0.2%    |
| SK Hynix            | 1        | 1      | 0.2%    |
| Mushkin             | 1        | 1      | 0.2%    |
| Micron Technology   | 1        | 2      | 0.2%    |
| LITEONIT            | 1        | 1      | 0.2%    |
| Leven               | 1        | 1      | 0.2%    |
| HS-SSD-E100         | 1        | 1      | 0.2%    |
| Fujitsu             | 1        | 2      | 0.2%    |
| FEASSO              | 1        | 2      | 0.2%    |
| ExcelStor           | 1        | 1      | 0.2%    |
| asmedia             | 1        | 1      | 0.2%    |
| Unknown             | 1        | 2      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 156      | 181    | 38.05%  |
| WDC                 | 132      | 165    | 32.2%   |
| Samsung Electronics | 50       | 58     | 12.2%   |
| Hitachi             | 39       | 47     | 9.51%   |
| MAXTOR              | 13       | 17     | 3.17%   |
| Toshiba             | 12       | 12     | 2.93%   |
| HGST                | 2        | 2      | 0.49%   |
| Unknown             | 1        | 1      | 0.24%   |
| Fujitsu             | 1        | 2      | 0.24%   |
| FEASSO              | 1        | 2      | 0.24%   |
| ExcelStor           | 1        | 1      | 0.24%   |
| asmedia             | 1        | 1      | 0.24%   |
| Unknown             | 1        | 2      | 0.24%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 369      | 491    | 82.55%  |
| SSD  | 70       | 79     | 15.66%  |
| NVMe | 8        | 10     | 1.79%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB            | 1        | 1      | 25%     |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 25%     |
| Samsung Electronics HD252HJ 250GB | 1        | 1      | 25%     |
| Hitachi HDS721050DLE630 500GB     | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 2        | 2      | 50%     |
| Toshiba             | 1        | 1      | 25%     |
| Hitachi             | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3182     | 8629   | 64.53%  |
| Works    | 1308     | 2813   | 26.53%  |
| Malfunc  | 437      | 580    | 8.86%   |
| Failed   | 4        | 4      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2865     | 49.53%  |
| AMD                              | 1354     | 23.41%  |
| Samsung Electronics              | 260      | 4.5%    |
| Nvidia                           | 231      | 3.99%   |
| ASMedia Technology               | 179      | 3.09%   |
| Marvell Technology Group         | 169      | 2.92%   |
| JMicron Technology               | 168      | 2.9%    |
| Phison Electronics               | 92       | 1.59%   |
| Sandisk                          | 86       | 1.49%   |
| VIA Technologies                 | 65       | 1.12%   |
| Kingston Technology Company      | 52       | 0.9%    |
| Silicon Motion                   | 45       | 0.78%   |
| ADATA Technology                 | 41       | 0.71%   |
| Micron/Crucial Technology        | 35       | 0.61%   |
| Silicon Image                    | 17       | 0.29%   |
| Realtek Semiconductor            | 17       | 0.29%   |
| SK Hynix                         | 13       | 0.22%   |
| LSI Logic / Symbios Logic        | 13       | 0.22%   |
| Adaptec                          | 11       | 0.19%   |
| Broadcom / LSI                   | 10       | 0.17%   |
| Silicon Integrated Systems [SiS] | 9        | 0.16%   |
| Lite-On Technology               | 8        | 0.14%   |
| Seagate Technology               | 6        | 0.1%    |
| Integrated Technology Express    | 6        | 0.1%    |
| Toshiba America Info Systems     | 5        | 0.09%   |
| Micron Technology                | 5        | 0.09%   |
| ULi Electronics                  | 3        | 0.05%   |
| KIOXIA                           | 3        | 0.05%   |
| HighPoint Technologies           | 3        | 0.05%   |
| Shenzhen Longsys Electronics     | 2        | 0.03%   |
| OCZ Technology Group             | 2        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 2        | 0.03%   |
| Unknown                          | 1        | 0.02%   |
| Union Memory (Shenzhen)          | 1        | 0.02%   |
| Solid State Storage Technology   | 1        | 0.02%   |
| Promise Technology               | 1        | 0.02%   |
| Hewlett-Packard                  | 1        | 0.02%   |
| Artop Electronic                 | 1        | 0.02%   |
| 3ware                            | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 657      | 8.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 326      | 4.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 320      | 4.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 298      | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 297      | 3.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 265      | 3.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 232      | 2.97%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 229      | 2.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 213      | 2.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 207      | 2.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 193      | 2.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 172      | 2.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 169      | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 167      | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 167      | 2.14%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 167      | 2.14%   |
| Intel SATA Controller [RAID mode]                                                       | 155      | 1.99%   |
| Nvidia MCP61 SATA Controller                                                            | 144      | 1.85%   |
| Nvidia MCP61 IDE                                                                        | 115      | 1.47%   |
| AMD 500 Series Chipset SATA Controller                                                  | 109      | 1.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 103      | 1.32%   |
| AMD FCH SATA Controller D                                                               | 86       | 1.1%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 82       | 1.05%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 79       | 1.01%   |
| AMD 300 Series Chipset SATA Controller                                                  | 76       | 0.97%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 74       | 0.95%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 70       | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 67       | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 63       | 0.81%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 61       | 0.78%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 60       | 0.77%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 55       | 0.71%   |
| JMicron JMB368 IDE controller                                                           | 54       | 0.69%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 54       | 0.69%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 51       | 0.65%   |
| AMD FCH IDE Controller                                                                  | 49       | 0.63%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 47       | 0.6%    |
| Phison E12 NVMe Controller                                                              | 45       | 0.58%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 45       | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 43       | 0.55%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 42       | 0.54%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 41       | 0.53%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 37       | 0.47%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 32       | 0.41%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 32       | 0.41%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 31       | 0.4%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 31       | 0.4%    |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 30       | 0.38%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 30       | 0.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 29       | 0.37%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 29       | 0.37%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 29       | 0.37%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 28       | 0.36%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 28       | 0.36%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 28       | 0.36%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 27       | 0.35%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 27       | 0.35%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 26       | 0.33%   |
| Kingston Company A2000 NVMe SSD                                                         | 26       | 0.33%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 26       | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3256     | 55.34%  |
| IDE  | 1688     | 28.69%  |
| NVMe | 647      | 11%     |
| RAID | 251      | 4.27%   |
| SCSI | 22       | 0.37%   |
| SAS  | 20       | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 2938     | 65.32%  |
| AMD          | 1559     | 34.66%  |
| CentaurHauls | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 68       | 1.51%   |
| AMD Ryzen 5 3600 6-Core Processor           | 66       | 1.46%   |
| AMD FX-8350 Eight-Core Processor            | 66       | 1.46%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 59       | 1.31%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 56       | 1.24%   |
| AMD FX-6300 Six-Core Processor              | 56       | 1.24%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 55       | 1.22%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 53       | 1.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 48       | 1.06%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 44       | 0.97%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 43       | 0.95%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 43       | 0.95%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 41       | 0.91%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 41       | 0.91%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 39       | 0.86%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 39       | 0.86%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 37       | 0.82%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 37       | 0.82%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 37       | 0.82%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 32       | 0.71%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 31       | 0.69%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 30       | 0.66%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 30       | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 28       | 0.62%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 28       | 0.62%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 26       | 0.58%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 26       | 0.58%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 25       | 0.55%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 25       | 0.55%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 25       | 0.55%   |
| AMD Athlon II X2 250 Processor              | 25       | 0.55%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 24       | 0.53%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 24       | 0.53%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 24       | 0.53%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 23       | 0.51%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 23       | 0.51%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 23       | 0.51%   |
| AMD FX-4300 Quad-Core Processor             | 23       | 0.51%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 22       | 0.49%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 22       | 0.49%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 22       | 0.49%   |
| AMD Phenom II X4 955 Processor              | 22       | 0.49%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 21       | 0.47%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 21       | 0.47%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 21       | 0.47%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 21       | 0.47%   |
| AMD Phenom II X4 965 Processor              | 21       | 0.47%   |
| AMD FX-8300 Eight-Core Processor            | 21       | 0.47%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 20       | 0.44%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 20       | 0.44%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 20       | 0.44%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 19       | 0.42%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 19       | 0.42%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 19       | 0.42%   |
| AMD FX-8320 Eight-Core Processor            | 19       | 0.42%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 18       | 0.4%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 18       | 0.4%    |
| Intel Core i5-3570K CPU @ 3.40GHz           | 18       | 0.4%    |
| Intel Core i5-3330 CPU @ 3.00GHz            | 18       | 0.4%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 18       | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 807      | 17.89%  |
| Intel Core i7           | 527      | 11.69%  |
| Intel Core i3           | 335      | 7.43%   |
| AMD Ryzen 5             | 280      | 6.21%   |
| AMD FX                  | 274      | 6.08%   |
| Intel Core 2 Duo        | 223      | 4.94%   |
| Intel Xeon              | 174      | 3.86%   |
| AMD Ryzen 7             | 168      | 3.73%   |
| Intel Pentium           | 152      | 3.37%   |
| Intel Core 2 Quad       | 147      | 3.26%   |
| Intel Celeron           | 135      | 2.99%   |
| Intel Pentium Dual-Core | 127      | 2.82%   |
| AMD Ryzen 3             | 81       | 1.8%    |
| AMD Phenom II X4        | 80       | 1.77%   |
| AMD Athlon II X2        | 75       | 1.66%   |
| AMD Athlon 64 X2        | 72       | 1.6%    |
| AMD A8                  | 58       | 1.29%   |
| Other                   | 53       | 1.18%   |
| Intel Pentium 4         | 50       | 1.11%   |
| Intel Core 2            | 48       | 1.06%   |
| AMD Ryzen 9             | 48       | 1.06%   |
| Intel Pentium Dual      | 47       | 1.04%   |
| AMD Athlon II X4        | 45       | 1%      |
| AMD A4                  | 42       | 0.93%   |
| AMD A10                 | 41       | 0.91%   |
| Intel Pentium D         | 34       | 0.75%   |
| Intel Atom              | 34       | 0.75%   |
| AMD Athlon              | 33       | 0.73%   |
| Intel Core i9           | 31       | 0.69%   |
| AMD A6                  | 29       | 0.64%   |
| AMD Phenom II X6        | 28       | 0.62%   |
| AMD Sempron             | 23       | 0.51%   |
| AMD Phenom              | 23       | 0.51%   |
| AMD Athlon II X3        | 18       | 0.4%    |
| AMD Athlon X4           | 16       | 0.35%   |
| Intel Pentium Gold      | 14       | 0.31%   |
| AMD Phenom II X2        | 14       | 0.31%   |
| AMD Ryzen 5 PRO         | 13       | 0.29%   |
| AMD Athlon 64           | 11       | 0.24%   |
| Intel Genuine           | 9        | 0.2%    |
| AMD Ryzen Threadripper  | 9        | 0.2%    |
| AMD Athlon Dual Core    | 9        | 0.2%    |
| AMD E1                  | 8        | 0.18%   |
| AMD E                   | 8        | 0.18%   |
| AMD Phenom II X3        | 7        | 0.16%   |
| Intel Pentium Silver    | 6        | 0.13%   |
| AMD Ryzen 3 PRO         | 5        | 0.11%   |
| AMD PRO A10             | 5        | 0.11%   |
| AMD E2                  | 5        | 0.11%   |
| AMD Athlon X2           | 4        | 0.09%   |
| AMD A12                 | 4        | 0.09%   |
| AMD Ryzen 7 PRO         | 3        | 0.07%   |
| AMD Athlon XP           | 3        | 0.07%   |
| AMD Opteron             | 2        | 0.04%   |
| AMD G                   | 2        | 0.04%   |
| AMD Athlon II           | 2        | 0.04%   |
| Intel Core m3           | 1        | 0.02%   |
| Intel Core M            | 1        | 0.02%   |
| Intel Core 2 Extreme    | 1        | 0.02%   |
| CentaurHauls VIA Eden   | 1        | 0.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1826     | 40.41%  |
| 2       | 1509     | 33.39%  |
| 6       | 500      | 11.06%  |
| 8       | 272      | 6.02%   |
| 1       | 182      | 4.03%   |
| 3       | 114      | 2.52%   |
| 12      | 59       | 1.31%   |
| 16      | 20       | 0.44%   |
| 10      | 19       | 0.42%   |
| Unknown | 9        | 0.2%    |
| 24      | 4        | 0.09%   |
| 32      | 1        | 0.02%   |
| 20      | 1        | 0.02%   |
| 18      | 1        | 0.02%   |
| 14      | 1        | 0.02%   |
| 5       | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 4460     | 99.16%  |
| 2      | 38       | 0.84%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2368     | 52.44%  |
| 2       | 2139     | 47.36%  |
| Unknown | 9        | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4119     | 90.33%  |
| Unknown        | 407      | 8.93%   |
| 32-bit         | 34       | 0.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 471      | 10.24%  |
| 0x306c3    | 408      | 8.87%   |
| 0x206a7    | 371      | 8.07%   |
| 0x1067a    | 322      | 7%      |
| 0x306a9    | 313      | 6.8%    |
| 0x06000852 | 193      | 4.2%    |
| 0x010000c8 | 149      | 3.24%   |
| 0x506e3    | 148      | 3.22%   |
| 0x906e9    | 129      | 2.8%    |
| 0x08701021 | 125      | 2.72%   |
| 0x906ea    | 116      | 2.52%   |
| 0x0800820d | 101      | 2.2%    |
| 0x6fb      | 79       | 1.72%   |
| 0x6fd      | 78       | 1.7%    |
| 0x06001119 | 76       | 1.65%   |
| 0x10676    | 58       | 1.26%   |
| 0x08701013 | 57       | 1.24%   |
| 0x106e5    | 56       | 1.22%   |
| 0x08108109 | 54       | 1.17%   |
| 0x010000db | 49       | 1.07%   |
| 0x20655    | 48       | 1.04%   |
| 0x0600063e | 47       | 1.02%   |
| 0xa0655    | 45       | 0.98%   |
| 0x08001138 | 39       | 0.85%   |
| 0x06003106 | 36       | 0.78%   |
| 0x20652    | 32       | 0.7%    |
| 0x206c2    | 30       | 0.65%   |
| 0x08001137 | 30       | 0.65%   |
| 0xa0671    | 29       | 0.63%   |
| 0x906ed    | 29       | 0.63%   |
| 0x306f2    | 29       | 0.63%   |
| 0x6f6      | 28       | 0.61%   |
| 0x0600611a | 28       | 0.61%   |
| 0xa0653    | 25       | 0.54%   |
| 0x0810100b | 24       | 0.52%   |
| 0x03000027 | 24       | 0.52%   |
| 0x010000dc | 24       | 0.52%   |
| 0x6f2      | 23       | 0.5%    |
| 0x106a5    | 23       | 0.5%    |
| 0x10677    | 22       | 0.48%   |
| 0x08101016 | 22       | 0.48%   |
| 0x010000c7 | 22       | 0.48%   |
| 0x206d7    | 21       | 0.46%   |
| 0x0a201009 | 21       | 0.46%   |
| 0x906eb    | 20       | 0.43%   |
| 0xf65      | 19       | 0.41%   |
| 0x906ec    | 19       | 0.41%   |
| 0x0a201016 | 18       | 0.39%   |
| 0x706a1    | 17       | 0.37%   |
| 0x0a50000c | 17       | 0.37%   |
| 0x306e4    | 16       | 0.35%   |
| 0x05000119 | 16       | 0.35%   |
| 0x01000083 | 16       | 0.35%   |
| 0xf41      | 14       | 0.3%    |
| 0xf29      | 14       | 0.3%    |
| 0x30678    | 14       | 0.3%    |
| 0x08600106 | 14       | 0.3%    |
| 0x0800820b | 14       | 0.3%    |
| 0x0700010f | 14       | 0.3%    |
| 0xf49      | 12       | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 474      | 10.53%  |
| Penryn           | 419      | 9.3%    |
| SandyBridge      | 416      | 9.24%   |
| IvyBridge        | 353      | 7.84%   |
| KabyLake         | 339      | 7.53%   |
| K10              | 318      | 7.06%   |
| Piledriver       | 305      | 6.77%   |
| Core             | 233      | 5.17%   |
| Zen 2            | 212      | 4.71%   |
| Zen+             | 187      | 4.15%   |
| Skylake          | 171      | 3.8%    |
| Zen              | 155      | 3.44%   |
| Westmere         | 116      | 2.58%   |
| K8 Hammer        | 107      | 2.38%   |
| NetBurst         | 99       | 2.2%    |
| Nehalem          | 90       | 2%      |
| CometLake        | 77       | 1.71%   |
| Zen 3            | 69       | 1.53%   |
| Bulldozer        | 55       | 1.22%   |
| Steamroller      | 48       | 1.07%   |
| Silvermont       | 38       | 0.84%   |
| Excavator        | 36       | 0.8%    |
| Unknown          | 34       | 0.76%   |
| K10 Llano        | 26       | 0.58%   |
| Bonnell          | 26       | 0.58%   |
| Goldmont plus    | 22       | 0.49%   |
| Bobcat           | 22       | 0.49%   |
| Jaguar           | 14       | 0.31%   |
| Goldmont         | 12       | 0.27%   |
| Broadwell        | 9        | 0.2%    |
| Alderlake Hybrid | 7        | 0.16%   |
| Puma             | 4        | 0.09%   |
| K6               | 4        | 0.09%   |
| Icelake          | 4        | 0.09%   |
| Tremont          | 1        | 0.02%   |
| TigerLake        | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1842     | 38.74%  |
| Intel                                        | 1468     | 30.87%  |
| AMD                                          | 1402     | 29.48%  |
| VIA Technologies                             | 14       | 0.29%   |
| Matrox Electronics Systems                   | 11       | 0.23%   |
| Silicon Integrated Systems [SiS]             | 7        | 0.15%   |
| ATI Technologies                             | 5        | 0.11%   |
| S3 Graphics                                  | 3        | 0.06%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.04%   |
| ASPEED Technology                            | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 222      | 4.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 222      | 4.54%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 173      | 3.54%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 145      | 2.97%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 128      | 2.62%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 122      | 2.49%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 109      | 2.23%   |
| Intel HD Graphics 530                                                                    | 87       | 1.78%   |
| Nvidia GT218 [GeForce 210]                                                               | 83       | 1.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 81       | 1.66%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 79       | 1.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 70       | 1.43%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 69       | 1.41%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 65       | 1.33%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 65       | 1.33%   |
| AMD RS780L [Radeon 3000]                                                                 | 55       | 1.12%   |
| Intel HD Graphics 630                                                                    | 53       | 1.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 52       | 1.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 49       | 1%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 48       | 0.98%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 47       | 0.96%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 44       | 0.9%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 43       | 0.88%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 41       | 0.84%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 38       | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 37       | 0.76%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 37       | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 36       | 0.74%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 36       | 0.74%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 35       | 0.72%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 35       | 0.72%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 33       | 0.67%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 33       | 0.67%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 32       | 0.65%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 32       | 0.65%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 30       | 0.61%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 29       | 0.59%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 29       | 0.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 28       | 0.57%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 28       | 0.57%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 28       | 0.57%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 26       | 0.53%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 25       | 0.51%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 25       | 0.51%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 25       | 0.51%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 24       | 0.49%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 24       | 0.49%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 24       | 0.49%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 23       | 0.47%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 23       | 0.47%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 21       | 0.43%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 21       | 0.43%   |
| AMD Renoir                                                                               | 20       | 0.41%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 19       | 0.39%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 19       | 0.39%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 19       | 0.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19       | 0.39%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 19       | 0.39%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 19       | 0.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18       | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| 1 x Nvidia          | 1746     | 38.41%  |
| 1 x AMD             | 1299     | 28.57%  |
| 1 x Intel           | 1296     | 28.51%  |
| 2 x AMD             | 54       | 1.19%   |
| Intel + Nvidia      | 44       | 0.97%   |
| Intel + AMD         | 24       | 0.53%   |
| AMD + Nvidia        | 23       | 0.51%   |
| 2 x Nvidia          | 19       | 0.42%   |
| 1 x VIA             | 14       | 0.31%   |
| 1 x Matrox          | 11       | 0.24%   |
| 1 x SiS             | 7        | 0.15%   |
| 3 x AMD             | 2        | 0.04%   |
| 1 x S3 Graphics     | 2        | 0.04%   |
| Nvidia + XGI        | 2        | 0.04%   |
| Nvidia + ASPEED     | 1        | 0.02%   |
| Intel + 2 x Nvidia  | 1        | 0.02%   |
| Intel + S3 Graphics | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3021     | 65.98%  |
| Proprietary | 1346     | 29.4%   |
| Unknown     | 212      | 4.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1390     | 29.98%  |
| 1.01-2.0   | 906      | 19.54%  |
| 0.51-1.0   | 701      | 15.12%  |
| 0.01-0.5   | 688      | 14.84%  |
| 3.01-4.0   | 408      | 8.8%    |
| 7.01-8.0   | 276      | 5.95%   |
| 5.01-6.0   | 164      | 3.54%   |
| 2.01-3.0   | 61       | 1.32%   |
| 8.01-16.0  | 37       | 0.8%    |
| 16.01-24.0 | 5        | 0.11%   |
| 4.01-5.0   | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 786      | 17.03%  |
| Goldstar             | 475      | 10.29%  |
| Dell                 | 416      | 9.01%   |
| Acer                 | 358      | 7.76%   |
| Hewlett-Packard      | 312      | 6.76%   |
| AOC                  | 249      | 5.4%    |
| Ancor Communications | 223      | 4.83%   |
| BenQ                 | 215      | 4.66%   |
| Philips              | 202      | 4.38%   |
| LG Electronics       | 144      | 3.12%   |
| Unknown              | 120      | 2.6%    |
| ViewSonic            | 89       | 1.93%   |
| Iiyama               | 78       | 1.69%   |
| Sony                 | 54       | 1.17%   |
| Eizo                 | 47       | 1.02%   |
| Fujitsu Siemens      | 44       | 0.95%   |
| ASUSTek Computer     | 43       | 0.93%   |
| NEC Computers        | 41       | 0.89%   |
| Lenovo               | 39       | 0.85%   |
| Vizio                | 31       | 0.67%   |
| Medion               | 30       | 0.65%   |
| HannStar             | 30       | 0.65%   |
| Panasonic            | 24       | 0.52%   |
| Sceptre Tech         | 21       | 0.46%   |
| Idek Iiyama          | 19       | 0.41%   |
| Toshiba              | 16       | 0.35%   |
| Sharp                | 15       | 0.33%   |
| Unknown              | 14       | 0.3%    |
| Hitachi              | 12       | 0.26%   |
| Gateway              | 12       | 0.26%   |
| FUS                  | 12       | 0.26%   |
| AUS                  | 12       | 0.26%   |
| VIZ                  | 11       | 0.24%   |
| Vestel Elektronik    | 11       | 0.24%   |
| Plain Tree Systems   | 11       | 0.24%   |
| Lenovo Group Limited | 11       | 0.24%   |
| Packard Bell         | 10       | 0.22%   |
| MSI                  | 10       | 0.22%   |
| MStar                | 9        | 0.2%    |
| Insignia             | 9        | 0.2%    |
| ___                  | 8        | 0.17%   |
| Vestel               | 8        | 0.17%   |
| Unknown (XXX)        | 8        | 0.17%   |
| Westinghouse         | 7        | 0.15%   |
| HannStar Display     | 7        | 0.15%   |
| DENON                | 7        | 0.15%   |
| OEM                  | 6        | 0.13%   |
| Microstep            | 6        | 0.13%   |
| KTC                  | 6        | 0.13%   |
| Hyundai ImageQuest   | 6        | 0.13%   |
| HPN                  | 6        | 0.13%   |
| Belinea              | 6        | 0.13%   |
| Tech Concepts        | 5        | 0.11%   |
| ONN                  | 5        | 0.11%   |
| Onkyo                | 5        | 0.11%   |
| NCS                  | 5        | 0.11%   |
| JRY                  | 5        | 0.11%   |
| Grundig              | 5        | 0.11%   |
| eMachines            | 5        | 0.11%   |
| Compaq Computer      | 5        | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 22       | 0.44%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 18       | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 15       | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 14       | 0.28%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 14       | 0.28%   |
| Unknown                                                               | 14       | 0.28%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 13       | 0.26%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                   | 12       | 0.24%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 11       | 0.22%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch            | 11       | 0.22%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch      | 11       | 0.22%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 11       | 0.22%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 10       | 0.2%    |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 10       | 0.2%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 9        | 0.18%   |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch   | 9        | 0.18%   |
| Philips LCD Monitor FTV 1920x1080                                     | 9        | 0.18%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 9        | 0.18%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 480x270mm 21.7-inch | 9        | 0.18%   |
| Unknown LCD Monitor SAMSUNG                                           | 8        | 0.16%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 8        | 0.16%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 344x194mm 15.5-inch   | 8        | 0.16%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 8        | 0.16%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 8        | 0.16%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                          | 8        | 0.16%   |
| AOC 1950w AOC1950 1366x768 410x230mm 18.5-inch                        | 8        | 0.16%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch   | 7        | 0.14%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 7        | 0.14%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 7        | 0.14%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                  | 7        | 0.14%   |
| Panasonic TV MEIA296 3840x2160 1280x720mm 57.8-inch                   | 7        | 0.14%   |
| LG Electronics LCD Monitor LG TV 1920x1080                            | 7        | 0.14%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch           | 7        | 0.14%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 7        | 0.14%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch     | 6        | 0.12%   |
| Samsung Electronics S22B300 SAM08AA 1920x1080 477x268mm 21.5-inch     | 6        | 0.12%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch      | 6        | 0.12%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                  | 6        | 0.12%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 6        | 0.12%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch  | 6        | 0.12%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 6        | 0.12%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 6        | 0.12%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 6        | 0.12%   |
| LG Electronics LCD Monitor LG IPS FULLHD 1920x1080                    | 6        | 0.12%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 6        | 0.12%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch          | 6        | 0.12%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                   | 6        | 0.12%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                  | 6        | 0.12%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 6        | 0.12%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 6        | 0.12%   |
| Dell 1907FP DEL4015 1280x1024 376x301mm 19.0-inch                     | 6        | 0.12%   |
| BenQ GW2280 BNQ78E8 1920x1080 476x268mm 21.5-inch                     | 6        | 0.12%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 6        | 0.12%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 6        | 0.12%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 6        | 0.12%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 6        | 0.12%   |
| Vizio M550NV VIZ0063 1920x1080 1210x680mm 54.6-inch                   | 5        | 0.1%    |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 5        | 0.1%    |
| Toshiba TV TSB0206 1920x1080 700x390mm 31.5-inch                      | 5        | 0.1%    |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch  | 5        | 0.1%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1925     | 41.97%  |
| 1280x1024 (SXGA)   | 428      | 9.33%   |
| 1680x1050 (WSXGA+) | 308      | 6.71%   |
| 3840x2160 (4K)     | 252      | 5.49%   |
| 1366x768 (WXGA)    | 244      | 5.32%   |
| 1440x900 (WXGA+)   | 211      | 4.6%    |
| Unknown            | 192      | 4.19%   |
| 2560x1440 (QHD)    | 182      | 3.97%   |
| 1600x900 (HD+)     | 160      | 3.49%   |
| 1920x1200 (WUXGA)  | 138      | 3.01%   |
| 1360x768           | 107      | 2.33%   |
| 3840x1080          | 59       | 1.29%   |
| 2560x1080          | 55       | 1.2%    |
| 1024x768 (XGA)     | 46       | 1%      |
| 3440x1440          | 29       | 0.63%   |
| 1600x1200          | 27       | 0.59%   |
| 1920x540           | 21       | 0.46%   |
| 1280x720 (HD)      | 16       | 0.35%   |
| 3200x1080          | 15       | 0.33%   |
| 3600x1080          | 14       | 0.31%   |
| 4480x1440          | 9        | 0.2%    |
| 1280x960           | 8        | 0.17%   |
| 5760x1080          | 7        | 0.15%   |
| 3840x1200          | 7        | 0.15%   |
| 2560x1600          | 7        | 0.15%   |
| 1152x864           | 7        | 0.15%   |
| 5120x1440          | 6        | 0.13%   |
| 3286x1080          | 6        | 0.13%   |
| 5120x1080          | 5        | 0.11%   |
| 3520x1080          | 5        | 0.11%   |
| 3360x1050          | 5        | 0.11%   |
| 3280x1080          | 4        | 0.09%   |
| 2960x1050          | 4        | 0.09%   |
| 2560x1024          | 4        | 0.09%   |
| 1280x768           | 4        | 0.09%   |
| 3840x1600          | 3        | 0.07%   |
| 2048x1152          | 3        | 0.07%   |
| 1280x800 (WXGA)    | 3        | 0.07%   |
| 8960x2160          | 2        | 0.04%   |
| 4000x1440          | 2        | 0.04%   |
| 3360x1080          | 2        | 0.04%   |
| 3280x1200          | 2        | 0.04%   |
| 3200x1200          | 2        | 0.04%   |
| 3120x1050          | 2        | 0.04%   |
| 2720x768           | 2        | 0.04%   |
| 2288x1287          | 2        | 0.04%   |
| 7680x1440          | 1        | 0.02%   |
| 7680x1080          | 1        | 0.02%   |
| 7280x1440          | 1        | 0.02%   |
| 640x480            | 1        | 0.02%   |
| 6400x1440          | 1        | 0.02%   |
| 5520x2160          | 1        | 0.02%   |
| 5520x1080          | 1        | 0.02%   |
| 5206x1080          | 1        | 0.02%   |
| 5200x1200          | 1        | 0.02%   |
| 5200x1080          | 1        | 0.02%   |
| 5120x1200          | 1        | 0.02%   |
| 4721x1050          | 1        | 0.02%   |
| 4480x1080          | 1        | 0.02%   |
| 4240x1440          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 888      | 19.53%  |
| 23      | 479      | 10.53%  |
| 24      | 477      | 10.49%  |
| 21      | 443      | 9.74%   |
| 27      | 399      | 8.77%   |
| 19      | 332      | 7.3%    |
| 18      | 246      | 5.41%   |
| 17      | 206      | 4.53%   |
| 22      | 200      | 4.4%    |
| 20      | 185      | 4.07%   |
| 31      | 128      | 2.81%   |
| 15      | 93       | 2.04%   |
| 34      | 66       | 1.45%   |
| 84      | 47       | 1.03%   |
| 32      | 38       | 0.84%   |
| 54      | 35       | 0.77%   |
| 72      | 33       | 0.73%   |
| 40      | 33       | 0.73%   |
| 25      | 28       | 0.62%   |
| 26      | 20       | 0.44%   |
| 16      | 18       | 0.4%    |
| 46      | 11       | 0.24%   |
| 33      | 10       | 0.22%   |
| 12      | 9        | 0.2%    |
| 52      | 8        | 0.18%   |
| 39      | 8        | 0.18%   |
| 37      | 8        | 0.18%   |
| 28      | 8        | 0.18%   |
| 13      | 8        | 0.18%   |
| 65      | 7        | 0.15%   |
| 49      | 7        | 0.15%   |
| 36      | 7        | 0.15%   |
| 55      | 6        | 0.13%   |
| 48      | 6        | 0.13%   |
| 29      | 6        | 0.13%   |
| 74      | 5        | 0.11%   |
| 60      | 5        | 0.11%   |
| 47      | 5        | 0.11%   |
| 44      | 4        | 0.09%   |
| 42      | 4        | 0.09%   |
| 30      | 4        | 0.09%   |
| 14      | 4        | 0.09%   |
| 57      | 2        | 0.04%   |
| 50      | 2        | 0.04%   |
| 43      | 2        | 0.04%   |
| 41      | 2        | 0.04%   |
| 38      | 2        | 0.04%   |
| 35      | 2        | 0.04%   |
| 80      | 1        | 0.02%   |
| 69      | 1        | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 1293     | 28.99%  |
| 401-500     | 1185     | 26.57%  |
| Unknown     | 888      | 19.91%  |
| 301-350     | 280      | 6.28%   |
| 351-400     | 234      | 5.25%   |
| 601-700     | 193      | 4.33%   |
| 701-800     | 121      | 2.71%   |
| 1001-1500   | 93       | 2.09%   |
| 1501-2000   | 87       | 1.95%   |
| 801-900     | 53       | 1.19%   |
| 201-300     | 21       | 0.47%   |
| 901-1000    | 12       | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2330     | 53.89%  |
| Unknown | 829      | 19.17%  |
| 16/10   | 578      | 13.37%  |
| 5/4     | 359      | 8.3%    |
| 4/3     | 105      | 2.43%   |
| 21/9    | 70       | 1.62%   |
| 3/2     | 23       | 0.53%   |
| 6/5     | 16       | 0.37%   |
| 32/9    | 8        | 0.19%   |
| 1.96    | 3        | 0.07%   |
| 11/10   | 2        | 0.05%   |
| 1.00    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1306     | 29.18%  |
| Unknown        | 888      | 19.84%  |
| 151-200        | 663      | 14.81%  |
| 301-350        | 409      | 9.14%   |
| 141-150        | 367      | 8.2%    |
| 351-500        | 256      | 5.72%   |
| 251-300        | 184      | 4.11%   |
| More than 1000 | 154      | 3.44%   |
| 501-1000       | 93       | 2.08%   |
| 101-110        | 78       | 1.74%   |
| 131-140        | 31       | 0.69%   |
| 111-120        | 21       | 0.47%   |
| 71-80          | 10       | 0.22%   |
| 121-130        | 6        | 0.13%   |
| 81-90          | 5        | 0.11%   |
| 91-100         | 5        | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2522     | 58.22%  |
| Unknown | 888      | 20.5%   |
| 101-120 | 604      | 13.94%  |
| 1-50    | 174      | 4.02%   |
| 121-160 | 96       | 2.22%   |
| 161-240 | 48       | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3706     | 81.22%  |
| 2     | 584      | 12.8%   |
| 0     | 212      | 4.65%   |
| 3     | 56       | 1.23%   |
| 4     | 5        | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2813     | 44.4%   |
| Intel                                  | 1446     | 22.83%  |
| Qualcomm Atheros                       | 461      | 7.28%   |
| Ralink Technology                      | 227      | 3.58%   |
| Broadcom                               | 194      | 3.06%   |
| Nvidia                                 | 190      | 3%      |
| Ralink                                 | 120      | 1.89%   |
| TP-Link                                | 115      | 1.82%   |
| Marvell Technology Group               | 64       | 1.01%   |
| Qualcomm Atheros Communications        | 63       | 0.99%   |
| Broadcom Limited                       | 55       | 0.87%   |
| NetGear                                | 43       | 0.68%   |
| D-Link                                 | 41       | 0.65%   |
| D-Link System                          | 39       | 0.62%   |
| VIA Technologies                       | 38       | 0.6%    |
| Samsung Electronics                    | 34       | 0.54%   |
| ASUSTek Computer                       | 27       | 0.43%   |
| MediaTek                               | 25       | 0.39%   |
| Xiaomi                                 | 21       | 0.33%   |
| Huawei Technologies                    | 21       | 0.33%   |
| Belkin Components                      | 21       | 0.33%   |
| Linksys                                | 20       | 0.32%   |
| IMC Networks                           | 18       | 0.28%   |
| Microsoft                              | 17       | 0.27%   |
| Edimax Technology                      | 15       | 0.24%   |
| ASIX Electronics                       | 15       | 0.24%   |
| Aquantia                               | 12       | 0.19%   |
| Motorola PCS                           | 10       | 0.16%   |
| Sitecom Europe                         | 9        | 0.14%   |
| AVM                                    | 9        | 0.14%   |
| Sundance Technology Inc / IC Plus      | 8        | 0.13%   |
| Silicon Integrated Systems [SiS]       | 5        | 0.08%   |
| Qualcomm                               | 5        | 0.08%   |
| Motorola                               | 5        | 0.08%   |
| Gemtek                                 | 5        | 0.08%   |
| ZyDAS                                  | 4        | 0.06%   |
| ZTE WCDMA Technologies MSM             | 4        | 0.06%   |
| Microchip Technology                   | 4        | 0.06%   |
| LG Electronics                         | 4        | 0.06%   |
| Holtek Semiconductor                   | 4        | 0.06%   |
| Google                                 | 4        | 0.06%   |
| DisplayLink                            | 4        | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 4        | 0.06%   |
| U-Blox                                 | 3        | 0.05%   |
| TRENDnet                               | 3        | 0.05%   |
| Texas Instruments                      | 3        | 0.05%   |
| STMicroelectronics                     | 3        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.05%   |
| Mellanox Technologies                  | 3        | 0.05%   |
| Arduino SA                             | 3        | 0.05%   |
| Apple                                  | 3        | 0.05%   |
| Accton Technology                      | 3        | 0.05%   |
| ZyXEL Communications                   | 2        | 0.03%   |
| Wacom                                  | 2        | 0.03%   |
| ULi Electronics                        | 2        | 0.03%   |
| Tenda                                  | 2        | 0.03%   |
| PCTel                                  | 2        | 0.03%   |
| OPPO Electronics                       | 2        | 0.03%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.03%   |
| Mercucys                               | 2        | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2249     | 32.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 206      | 2.96%   |
| Intel Ethernet Connection (2) I219-V                              | 155      | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 151      | 2.17%   |
| Intel I211 Gigabit Network Connection                             | 138      | 1.98%   |
| Nvidia MCP61 Ethernet                                             | 121      | 1.74%   |
| Intel Wi-Fi 6 AX200                                               | 121      | 1.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 98       | 1.41%   |
| Ralink MT7601U Wireless Adapter                                   | 98       | 1.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 86       | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 84       | 1.21%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 84       | 1.21%   |
| Intel 82579V Gigabit Network Connection                           | 72       | 1.03%   |
| Intel Ethernet Connection (7) I219-V                              | 68       | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 59       | 0.85%   |
| Intel Ethernet Connection I217-V                                  | 58       | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 57       | 0.82%   |
| Realtek 802.11ac NIC                                              | 53       | 0.76%   |
| Intel Ethernet Connection (2) I218-V                              | 52       | 0.75%   |
| Qualcomm Atheros AR9271 802.11n                                   | 51       | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 50       | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 45       | 0.65%   |
| Ralink RT5370 Wireless Adapter                                    | 42       | 0.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 40       | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39       | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 37       | 0.53%   |
| Intel Wireless-AC 9260                                            | 37       | 0.53%   |
| Intel Ethernet Controller I225-V                                  | 36       | 0.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 35       | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 33       | 0.47%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 32       | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 30       | 0.43%   |
| Intel 82578DM Gigabit Network Connection                          | 29       | 0.42%   |
| Intel 82574L Gigabit Network Connection                           | 29       | 0.42%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 29       | 0.42%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 28       | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 28       | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                             | 27       | 0.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 26       | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 26       | 0.37%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 26       | 0.37%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 26       | 0.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 25       | 0.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25       | 0.36%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 25       | 0.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 24       | 0.34%   |
| Intel Wireless 3165                                               | 24       | 0.34%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 22       | 0.32%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 22       | 0.32%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 22       | 0.32%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 21       | 0.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 21       | 0.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21       | 0.3%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 21       | 0.3%    |
| Intel Wireless 8260                                               | 20       | 0.29%   |
| Intel Wireless 7260                                               | 20       | 0.29%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 20       | 0.29%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 18       | 0.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18       | 0.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 18       | 0.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 492      | 24.43%  |
| Intel                                 | 400      | 19.86%  |
| Ralink Technology                     | 227      | 11.27%  |
| Qualcomm Atheros                      | 222      | 11.02%  |
| Ralink                                | 120      | 5.96%   |
| TP-Link                               | 115      | 5.71%   |
| Broadcom                              | 66       | 3.28%   |
| Qualcomm Atheros Communications       | 63       | 3.13%   |
| NetGear                               | 43       | 2.14%   |
| D-Link                                | 41       | 2.04%   |
| ASUSTek Computer                      | 27       | 1.34%   |
| D-Link System                         | 22       | 1.09%   |
| Linksys                               | 20       | 0.99%   |
| Belkin Components                     | 20       | 0.99%   |
| IMC Networks                          | 18       | 0.89%   |
| Microsoft                             | 17       | 0.84%   |
| Edimax Technology                     | 15       | 0.74%   |
| MediaTek                              | 12       | 0.6%    |
| Broadcom Limited                      | 12       | 0.6%    |
| Sitecom Europe                        | 9        | 0.45%   |
| AVM                                   | 9        | 0.45%   |
| Gemtek                                | 5        | 0.25%   |
| ZyDAS                                 | 4        | 0.2%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.2%    |
| TRENDnet                              | 3        | 0.15%   |
| Texas Instruments                     | 3        | 0.15%   |
| ZyXEL Communications                  | 2        | 0.1%    |
| Wacom                                 | 2        | 0.1%    |
| Tenda                                 | 2        | 0.1%    |
| Samsung Electronics                   | 2        | 0.1%    |
| Mercucys                              | 2        | 0.1%    |
| Accton Technology                     | 2        | 0.1%    |
| Xiaomi                                | 1        | 0.05%   |
| VIA Technologies                      | 1        | 0.05%   |
| Sagem                                 | 1        | 0.05%   |
| PLANEX                                | 1        | 0.05%   |
| Philips (or NXP)                      | 1        | 0.05%   |
| Netopia                               | 1        | 0.05%   |
| Marvell Technology Group              | 1        | 0.05%   |
| Guillemot                             | 1        | 0.05%   |
| Fujitsu Siemens Computers             | 1        | 0.05%   |
| BUFFALO                               | 1        | 0.05%   |
| Atmel                                 | 1        | 0.05%   |
| AirVast                               | 1        | 0.05%   |
| AboCom Systems                        | 1        | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                           | 121      | 5.92%   |
| Ralink MT7601U Wireless Adapter                                                               | 98       | 4.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 59       | 2.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 57       | 2.79%   |
| Realtek 802.11ac NIC                                                                          | 53       | 2.59%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 51       | 2.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 50       | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 45       | 2.2%    |
| Ralink RT5370 Wireless Adapter                                                                | 42       | 2.05%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 40       | 1.96%   |
| Intel Wireless-AC 9260                                                                        | 37       | 1.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 35       | 1.71%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 28       | 1.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 26       | 1.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                         | 26       | 1.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 26       | 1.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 25       | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 25       | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 24       | 1.17%   |
| Intel Wireless 3165                                                                           | 24       | 1.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                              | 22       | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 22       | 1.08%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 21       | 1.03%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 21       | 1.03%   |
| Intel Wireless 8260                                                                           | 20       | 0.98%   |
| Intel Wireless 7260                                                                           | 20       | 0.98%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                               | 18       | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 18       | 0.88%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 17       | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 16       | 0.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 16       | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 16       | 0.78%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 15       | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 15       | 0.73%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 15       | 0.73%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 15       | 0.73%   |
| Intel Wireless 7265                                                                           | 15       | 0.73%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 14       | 0.68%   |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                                          | 14       | 0.68%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 13       | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 13       | 0.64%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 13       | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 13       | 0.64%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 13       | 0.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 13       | 0.64%   |
| Intel Wireless 8265 / 8275                                                                    | 12       | 0.59%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                         | 11       | 0.54%   |
| TP-Link 802.11ac WLAN Adapter                                                                 | 11       | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 11       | 0.54%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 11       | 0.54%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                               | 11       | 0.54%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 11       | 0.54%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 11       | 0.54%   |
| Realtek RTL8187 Wireless Adapter                                                              | 10       | 0.49%   |
| Ralink RT5372 Wireless Adapter                                                                | 10       | 0.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 10       | 0.49%   |
| Intel Wireless 3160                                                                           | 10       | 0.49%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                            | 10       | 0.49%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 9        | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 9        | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2625     | 55.1%   |
| Intel                                  | 1224     | 25.69%  |
| Qualcomm Atheros                       | 254      | 5.33%   |
| Nvidia                                 | 190      | 3.99%   |
| Broadcom                               | 128      | 2.69%   |
| Marvell Technology Group               | 63       | 1.32%   |
| Broadcom Limited                       | 43       | 0.9%    |
| VIA Technologies                       | 36       | 0.76%   |
| Samsung Electronics                    | 32       | 0.67%   |
| Xiaomi                                 | 20       | 0.42%   |
| D-Link System                          | 17       | 0.36%   |
| ASIX Electronics                       | 15       | 0.31%   |
| MediaTek                               | 13       | 0.27%   |
| Huawei Technologies                    | 13       | 0.27%   |
| Aquantia                               | 12       | 0.25%   |
| Sundance Technology Inc / IC Plus      | 8        | 0.17%   |
| Motorola PCS                           | 7        | 0.15%   |
| Silicon Integrated Systems [SiS]       | 5        | 0.1%    |
| ZTE WCDMA Technologies MSM             | 4        | 0.08%   |
| Qualcomm                               | 4        | 0.08%   |
| LG Electronics                         | 4        | 0.08%   |
| Google                                 | 4        | 0.08%   |
| DisplayLink                            | 4        | 0.08%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.06%   |
| Apple                                  | 3        | 0.06%   |
| OPPO Electronics                       | 2        | 0.04%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.04%   |
| Microchip Technology                   | 2        | 0.04%   |
| Mellanox Technologies                  | 2        | 0.04%   |
| ICS Advent                             | 2        | 0.04%   |
| HTC (High Tech Computer)               | 2        | 0.04%   |
| ADMtek                                 | 2        | 0.04%   |
| 3Com                                   | 2        | 0.04%   |
| ULi Electronics                        | 1        | 0.02%   |
| Trendchip Technologies                 | 1        | 0.02%   |
| Tehuti Networks                        | 1        | 0.02%   |
| Spreadtrum Communications              | 1        | 0.02%   |
| Novatel Wireless                       | 1        | 0.02%   |
| NetXen Incorporated                    | 1        | 0.02%   |
| Netchip Technology                     | 1        | 0.02%   |
| National Semiconductor                 | 1        | 0.02%   |
| IBM                                    | 1        | 0.02%   |
| HMD Global                             | 1        | 0.02%   |
| Emulex                                 | 1        | 0.02%   |
| Digital Equipment                      | 1        | 0.02%   |
| Davicom Semiconductor                  | 1        | 0.02%   |
| Compal Electronics                     | 1        | 0.02%   |
| Belkin Components                      | 1        | 0.02%   |
| Accton Technology                      | 1        | 0.02%   |
| 3DSP                                   | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2249     | 46.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 206      | 4.24%   |
| Intel Ethernet Connection (2) I219-V                              | 155      | 3.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 151      | 3.11%   |
| Intel I211 Gigabit Network Connection                             | 138      | 2.84%   |
| Nvidia MCP61 Ethernet                                             | 121      | 2.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 98       | 2.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 86       | 1.77%   |
| Intel Ethernet Connection I217-LM                                 | 84       | 1.73%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 84       | 1.73%   |
| Intel 82579V Gigabit Network Connection                           | 72       | 1.48%   |
| Intel Ethernet Connection (7) I219-V                              | 68       | 1.4%    |
| Intel Ethernet Connection I217-V                                  | 58       | 1.19%   |
| Intel Ethernet Connection (2) I218-V                              | 52       | 1.07%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39       | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 37       | 0.76%   |
| Intel Ethernet Controller I225-V                                  | 36       | 0.74%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 33       | 0.68%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 32       | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 30       | 0.62%   |
| Intel 82578DM Gigabit Network Connection                          | 29       | 0.6%    |
| Intel 82574L Gigabit Network Connection                           | 29       | 0.6%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 29       | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 28       | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 27       | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 26       | 0.53%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 25       | 0.51%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 22       | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 21       | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 21       | 0.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 20       | 0.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18       | 0.37%   |
| Intel 82562V-2 10/100 Network Connection                          | 18       | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 17       | 0.35%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 17       | 0.35%   |
| Nvidia MCP77 Ethernet                                             | 16       | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15       | 0.31%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15       | 0.31%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 15       | 0.31%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 14       | 0.29%   |
| Nvidia MCP73 Ethernet                                             | 14       | 0.29%   |
| Intel 82578DC Gigabit Network Connection                          | 14       | 0.29%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 14       | 0.29%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 14       | 0.29%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 13       | 0.27%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 13       | 0.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12       | 0.25%   |
| Nvidia MCP55 Ethernet                                             | 12       | 0.25%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 12       | 0.25%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 11       | 0.23%   |
| MediaTek NOA N2                                                   | 11       | 0.23%   |
| Intel Ethernet Connection (14) I219-V                             | 10       | 0.21%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 10       | 0.21%   |
| Intel NM10/ICH7 Family LAN Controller                             | 9        | 0.19%   |
| Intel I210 Gigabit Network Connection                             | 9        | 0.19%   |
| Intel Ethernet Connection (7) I219-LM                             | 9        | 0.19%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 9        | 0.19%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 9        | 0.19%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 9        | 0.19%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 9        | 0.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4440     | 69.84%  |
| WiFi     | 1857     | 29.21%  |
| Modem    | 42       | 0.66%   |
| Unknown  | 18       | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4041     | 73.66%  |
| WiFi     | 1440     | 26.25%  |
| Unknown  | 5        | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3258     | 72.1%   |
| 2     | 1107     | 24.5%   |
| 3     | 95       | 2.1%    |
| 0     | 43       | 0.95%   |
| 4     | 10       | 0.22%   |
| 5     | 4        | 0.09%   |
| 7     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3850     | 84.43%  |
| Yes  | 710      | 15.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 385      | 34.75%  |
| Intel                           | 358      | 32.31%  |
| Broadcom                        | 84       | 7.58%   |
| ASUSTek Computer                | 72       | 6.5%    |
| Realtek Semiconductor           | 71       | 6.41%   |
| Qualcomm Atheros Communications | 39       | 3.52%   |
| IMC Networks                    | 18       | 1.62%   |
| Apple                           | 13       | 1.17%   |
| Integrated System Solution      | 12       | 1.08%   |
| Lite-On Technology              | 9        | 0.81%   |
| Belkin Components               | 6        | 0.54%   |
| Dell                            | 5        | 0.45%   |
| MediaTek                        | 4        | 0.36%   |
| Dynex                           | 4        | 0.36%   |
| Conwise Technology              | 4        | 0.36%   |
| Ralink                          | 3        | 0.27%   |
| Logitech                        | 3        | 0.27%   |
| Edimax Technology               | 3        | 0.27%   |
| TP-Link                         | 2        | 0.18%   |
| Micro Star International        | 2        | 0.18%   |
| Hewlett-Packard                 | 2        | 0.18%   |
| Roper                           | 1        | 0.09%   |
| Primax Electronics              | 1        | 0.09%   |
| Motorola PCS                    | 1        | 0.09%   |
| Microsoft                       | 1        | 0.09%   |
| Kensington                      | 1        | 0.09%   |
| HTC (High Tech Computer)        | 1        | 0.09%   |
| Fujitsu Siemens Computers       | 1        | 0.09%   |
| Foxconn / Hon Hai               | 1        | 0.09%   |
| D-Link                          | 1        | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 384      | 34.59%  |
| Intel AX200 Bluetooth                                    | 106      | 9.55%   |
| Intel Bluetooth wireless interface                       | 88       | 7.93%   |
| Intel Wireless-AC 3168 Bluetooth                         | 57       | 5.14%   |
| Realtek Bluetooth Radio                                  | 52       | 4.68%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 46       | 4.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 36       | 3.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 31       | 2.79%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 30       | 2.7%    |
| Intel Bluetooth Device                                   | 20       | 1.8%    |
| Realtek  Bluetooth 4.2 Adapter                           | 16       | 1.44%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 14       | 1.26%   |
| Intel AX210 Bluetooth                                    | 12       | 1.08%   |
| IMC Networks Bluetooth Radio                             | 11       | 0.99%   |
| ASUS BCM20702A0                                          | 11       | 0.99%   |
| Qualcomm Atheros  Bluetooth Device                       | 10       | 0.9%    |
| ASUS ASUS USB-BT500                                      | 10       | 0.9%    |
| Lite-On Bluetooth Device                                 | 9        | 0.81%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 8        | 0.72%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 8        | 0.72%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 7        | 0.63%   |
| ASUS Bluetooth Radio                                     | 7        | 0.63%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 6        | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 5        | 0.45%   |
| Broadcom BCM2045 Bluetooth                               | 5        | 0.45%   |
| ASUS Qualcomm Bluetooth 4.1                              | 5        | 0.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 5        | 0.45%   |
| MediaTek Wireless_Device                                 | 4        | 0.36%   |
| Integrated System Solution Bluetooth Device              | 4        | 0.36%   |
| IMC Networks Bluetooth Device                            | 4        | 0.36%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 4        | 0.36%   |
| Conwise CW6622                                           | 4        | 0.36%   |
| Broadcom HP Bluethunder                                  | 4        | 0.36%   |
| Broadcom Bluetooth 3.0 Dongle                            | 4        | 0.36%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 4        | 0.36%   |
| ASUS Bluetooth Adapter                                   | 4        | 0.36%   |
| Apple Bluetooth USB Host Controller                      | 4        | 0.36%   |
| Apple Bluetooth HCI                                      | 4        | 0.36%   |
| Realtek RTL8821A Bluetooth                               | 3        | 0.27%   |
| Ralink RT3290 Bluetooth                                  | 3        | 0.27%   |
| Logitech BT Mini-Receiver (HCI mode)                     | 3        | 0.27%   |
| Dell BT Mini-Receiver                                    | 3        | 0.27%   |
| Broadcom HP Bluetooth Module                             | 3        | 0.27%   |
| TP-Link UB500 Adapter                                    | 2        | 0.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 2        | 0.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 2        | 0.18%   |
| Edimax Bluetooth Adapter                                 | 2        | 0.18%   |
| Dell Broadcom BCM20702A0 Bluetooth                       | 2        | 0.18%   |
| Broadcom HP Portable Bumble Bee                          | 2        | 0.18%   |
| Broadcom Bluetooth Device                                | 2        | 0.18%   |
| Broadcom Bluetooth 2.0+eDR dongle                        | 2        | 0.18%   |
| Broadcom BCM2210 Bluetooth                               | 2        | 0.18%   |
| Broadcom BCM2035 Bluetooth dongle                        | 2        | 0.18%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 2        | 0.18%   |
| Belkin Components Bluetooth Mini Dongle                  | 2        | 0.18%   |
| ASUS Bluetooth Device                                    | 2        | 0.18%   |
| Roper Class 1 Bluetooth Dongle                           | 1        | 0.09%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter            | 1        | 0.09%   |
| Motorola PCS Bluetooth Device                            | 1        | 0.09%   |
| Microsoft Wireless Transceiver for Bluetooth 2.0         | 1        | 0.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 2771     | 38.52%  |
| AMD                                             | 1861     | 25.87%  |
| Nvidia                                          | 1678     | 23.33%  |
| C-Media Electronics                             | 188      | 2.61%   |
| Creative Labs                                   | 120      | 1.67%   |
| Logitech                                        | 71       | 0.99%   |
| VIA Technologies                                | 48       | 0.67%   |
| Texas Instruments                               | 36       | 0.5%    |
| Generalplus Technology                          | 32       | 0.44%   |
| JMTek                                           | 29       | 0.4%    |
| Kingston Technology                             | 24       | 0.33%   |
| Creative Technology                             | 24       | 0.33%   |
| Razer USA                                       | 17       | 0.24%   |
| GN Netcom                                       | 16       | 0.22%   |
| Corsair                                         | 13       | 0.18%   |
| Tenx Technology                                 | 12       | 0.17%   |
| Plantronics                                     | 11       | 0.15%   |
| Focusrite-Novation                              | 11       | 0.15%   |
| Silicon Integrated Systems [SiS]                | 9        | 0.13%   |
| M-Audio                                         | 9        | 0.13%   |
| ASUSTek Computer                                | 9        | 0.13%   |
| SteelSeries ApS                                 | 8        | 0.11%   |
| Sennheiser Communications                       | 8        | 0.11%   |
| Ensoniq                                         | 7        | 0.1%    |
| Dell                                            | 7        | 0.1%    |
| BEHRINGER International                         | 7        | 0.1%    |
| Yamaha                                          | 6        | 0.08%   |
| Samson Technologies                             | 6        | 0.08%   |
| Microsoft                                       | 6        | 0.08%   |
| XMOS                                            | 5        | 0.07%   |
| Realtek Semiconductor                           | 5        | 0.07%   |
| Licensed by Sony Computer Entertainment America | 5        | 0.07%   |
| ATI Technologies                                | 5        | 0.07%   |
| RODE Microphones                                | 4        | 0.06%   |
| Asahi Kasei Microsystems                        | 4        | 0.06%   |
| ULi Electronics                                 | 3        | 0.04%   |
| Turtle Beach                                    | 3        | 0.04%   |
| Sony                                            | 3        | 0.04%   |
| Medeli Electronics                              | 3        | 0.04%   |
| Elite Silicon                                   | 3        | 0.04%   |
| Blue Microphones                                | 3        | 0.04%   |
| AKAI Professional M.I.                          | 3        | 0.04%   |
| A4Tech                                          | 3        | 0.04%   |
| ZOOM                                            | 2        | 0.03%   |
| Trust                                           | 2        | 0.03%   |
| TOWA Electronics                                | 2        | 0.03%   |
| TerraTec Electronic                             | 2        | 0.03%   |
| Tdlasunnic                                      | 2        | 0.03%   |
| Syntek                                          | 2        | 0.03%   |
| SHARKOON Technologies                           | 2        | 0.03%   |
| SAVITECH                                        | 2        | 0.03%   |
| ONN                                             | 2        | 0.03%   |
| Nuforce                                         | 2        | 0.03%   |
| Nordic Semiconductor ASA                        | 2        | 0.03%   |
| Microchip Technology                            | 2        | 0.03%   |
| Micro Star International                        | 2        | 0.03%   |
| LG Electronics                                  | 2        | 0.03%   |
| Insignia (Best Buy)                             | 2        | 0.03%   |
| GYROCOM C&C                                     | 2        | 0.03%   |
| Fry's Electronics                               | 2        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 487      | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 475      | 5.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 351      | 4.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 299      | 3.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 245      | 2.96%   |
| AMD Starship/Matisse HD Audio Controller                                          | 234      | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 228      | 2.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 217      | 2.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 197      | 2.38%   |
| AMD FCH Azalia Controller                                                         | 187      | 2.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 184      | 2.22%   |
| Intel 200 Series PCH HD Audio                                                     | 178      | 2.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 173      | 2.09%   |
| AMD Family 17h/19h HD Audio Controller                                            | 162      | 1.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 159      | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 145      | 1.75%   |
| Nvidia MCP61 High Definition Audio                                                | 140      | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 138      | 1.67%   |
| Nvidia High Definition Audio Controller                                           | 122      | 1.47%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 121      | 1.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 118      | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                        | 111      | 1.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 100      | 1.21%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 95       | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                                     | 94       | 1.14%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 92       | 1.11%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 90       | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                                     | 85       | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                     | 83       | 1%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 81       | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 75       | 0.91%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 75       | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                                     | 74       | 0.89%   |
| Nvidia GP108 High Definition Audio Controller                                     | 65       | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                                | 63       | 0.76%   |
| Nvidia GF119 HDMI Audio Controller                                                | 58       | 0.7%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 55       | 0.66%   |
| Nvidia GM206 High Definition Audio Controller                                     | 47       | 0.57%   |
| Nvidia GK104 HDMI Audio Controller                                                | 47       | 0.57%   |
| Nvidia GM204 High Definition Audio Controller                                     | 46       | 0.56%   |
| Nvidia GK106 HDMI Audio Controller                                                | 46       | 0.56%   |
| Nvidia GF116 High Definition Audio Controller                                     | 46       | 0.56%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 45       | 0.54%   |
| Nvidia TU106 High Definition Audio Controller                                     | 44       | 0.53%   |
| AMD Trinity HDMI Audio Controller                                                 | 43       | 0.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 41       | 0.5%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 40       | 0.48%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 38       | 0.46%   |
| AMD Navi 10 HDMI Audio                                                            | 38       | 0.46%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 37       | 0.45%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 35       | 0.42%   |
| AMD Kabini HDMI/DP Audio                                                          | 34       | 0.41%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 33       | 0.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 32       | 0.39%   |
| Nvidia TU104 HD Audio Controller                                                  | 32       | 0.39%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 31       | 0.37%   |
| Generalplus Technology USB Audio Device                                           | 31       | 0.37%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 31       | 0.37%   |
| Intel Comet Lake PCH cAVS                                                         | 30       | 0.36%   |
| Intel Comet Lake PCH-V cAVS                                                       | 29       | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Kingston                             | 352      | 18.48%  |
| Unknown                              | 348      | 18.27%  |
| Corsair                              | 219      | 11.5%   |
| SK Hynix                             | 156      | 8.19%   |
| Crucial                              | 152      | 7.98%   |
| Samsung Electronics                  | 151      | 7.93%   |
| G.Skill                              | 150      | 7.87%   |
| Micron Technology                    | 70       | 3.67%   |
| A-DATA Technology                    | 36       | 1.89%   |
| Nanya Technology                     | 30       | 1.57%   |
| Patriot                              | 29       | 1.52%   |
| Team                                 | 26       | 1.36%   |
| Ramaxel Technology                   | 17       | 0.89%   |
| AMD                                  | 13       | 0.68%   |
| GOODRAM                              | 12       | 0.63%   |
| Elpida                               | 11       | 0.58%   |
| Transcend                            | 9        | 0.47%   |
| Unknown                              | 9        | 0.47%   |
| Kingmax                              | 8        | 0.42%   |
| Unifosa                              | 7        | 0.37%   |
| GEIL                                 | 7        | 0.37%   |
| Unknown (ABCD)                       | 5        | 0.26%   |
| Teikon                               | 5        | 0.26%   |
| Smart                                | 5        | 0.26%   |
| Silicon Power                        | 5        | 0.26%   |
| Apacer                               | 5        | 0.26%   |
| Wilk Elektronik                      | 4        | 0.21%   |
| Sesame                               | 4        | 0.21%   |
| Unknown (0x8551)                     | 3        | 0.16%   |
| Ramos Technology                     | 3        | 0.16%   |
| PNY                                  | 3        | 0.16%   |
| OCZ                                  | 3        | 0.16%   |
| Multilaser                           | 3        | 0.16%   |
| KETECH                               | 3        | 0.16%   |
| CSX                                  | 3        | 0.16%   |
| Avant                                | 3        | 0.16%   |
| Wilk                                 | 2        | 0.1%    |
| V-Color                              | 2        | 0.1%    |
| TakeMS                               | 2        | 0.1%    |
| Qumo                                 | 2        | 0.1%    |
| Qimonda                              | 2        | 0.1%    |
| Undefined-000B                       | 1        | 0.05%   |
| TwinMOS                              | 1        | 0.05%   |
| TIMETEC                              | 1        | 0.05%   |
| SemsoTai                             | 1        | 0.05%   |
| Qbex                                 | 1        | 0.05%   |
| PUSKILL                              | 1        | 0.05%   |
| Patriot Memory                       | 1        | 0.05%   |
| OLOY                                 | 1        | 0.05%   |
| Mushkin                              | 1        | 0.05%   |
| M                                    | 1        | 0.05%   |
| Kinlstuo                             | 1        | 0.05%   |
| Innodisk                             | 1        | 0.05%   |
| Hyundai Elect                        | 1        | 0.05%   |
| HPE                                  | 1        | 0.05%   |
| HMD                                  | 1        | 0.05%   |
| H                                    | 1        | 0.05%   |
| Goldkey                              | 1        | 0.05%   |
| Exceleram                            | 1        | 0.05%   |
| Chun Well Technology Holding Limited | 1        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 24       | 1.15%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 23       | 1.1%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                   | 22       | 1.05%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 20       | 0.96%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 17       | 0.81%   |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 15       | 0.72%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s           | 14       | 0.67%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 14       | 0.67%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 13       | 0.62%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 13       | 0.62%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                   | 12       | 0.57%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 12       | 0.57%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 12       | 0.57%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s            | 11       | 0.53%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s            | 11       | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                    | 10       | 0.48%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s        | 10       | 0.48%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 10       | 0.48%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                        | 9        | 0.43%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 9        | 0.43%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s             | 9        | 0.43%   |
| Kingston RAM KHX2133C14D4/4G 4096MB DIMM DDR4 2933MT/s         | 9        | 0.43%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s       | 9        | 0.43%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3200MT/s         | 9        | 0.43%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s         | 9        | 0.43%   |
| Unknown                                                        | 9        | 0.43%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 8        | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                    | 8        | 0.38%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                         | 8        | 0.38%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 8        | 0.38%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s            | 8        | 0.38%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s            | 8        | 0.38%   |
| Kingston RAM KHX1600C10D3/4G 4096MB DIMM DDR3 1866MT/s         | 8        | 0.38%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s       | 8        | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                     | 7        | 0.33%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                    | 7        | 0.33%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM SDRAM 1867MT/s           | 7        | 0.33%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s            | 7        | 0.33%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 7        | 0.33%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s            | 7        | 0.33%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s            | 7        | 0.33%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s              | 7        | 0.33%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s             | 7        | 0.33%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 7        | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR2                            | 6        | 0.29%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                         | 6        | 0.29%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s            | 6        | 0.29%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 6        | 0.29%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 6        | 0.29%   |
| Kingston RAM 99U5471-012.A00LF 4096MB DIMM DDR3 1600MT/s       | 6        | 0.29%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s          | 6        | 0.29%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                        | 5        | 0.24%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s                    | 5        | 0.24%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                   | 5        | 0.24%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                    | 5        | 0.24%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                     | 5        | 0.24%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR3 2400MT/s | 5        | 0.24%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s        | 5        | 0.24%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s           | 5        | 0.24%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM 1333MT/s                 | 5        | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR3         | 644      | 38.45%  |
| DDR4         | 641      | 38.27%  |
| Unknown      | 141      | 8.42%   |
| DDR2         | 124      | 7.4%    |
| SDRAM        | 84       | 5.01%   |
| DDR          | 30       | 1.79%   |
| LPDDR4       | 8        | 0.48%   |
| DRAM         | 2        | 0.12%   |
| DDR2 FB-DIMM | 1        | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1555     | 94.59%  |
| SODIMM       | 82       | 4.99%   |
| FB-DIMM      | 5        | 0.3%    |
| Row Of Chips | 1        | 0.06%   |
| RIMM         | 1        | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 623      | 34.31%  |
| 4096  | 502      | 27.64%  |
| 2048  | 348      | 19.16%  |
| 16384 | 190      | 10.46%  |
| 1024  | 88       | 4.85%   |
| 32768 | 42       | 2.31%   |
| 512   | 18       | 0.99%   |
| 1536  | 2        | 0.11%   |
| 256   | 2        | 0.11%   |
| 16    | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 363      | 19.87%  |
| 1333    | 299      | 16.37%  |
| 3200    | 144      | 7.88%   |
| 2400    | 111      | 6.08%   |
| 800     | 98       | 5.36%   |
| 3600    | 91       | 4.98%   |
| 2667    | 83       | 4.54%   |
| 2133    | 83       | 4.54%   |
| 667     | 69       | 3.78%   |
| Unknown | 53       | 2.9%    |
| 1867    | 38       | 2.08%   |
| 3000    | 37       | 2.03%   |
| 2933    | 33       | 1.81%   |
| 3466    | 32       | 1.75%   |
| 1866    | 32       | 1.75%   |
| 1066    | 23       | 1.26%   |
| 1800    | 19       | 1.04%   |
| 2666    | 18       | 0.99%   |
| 3533    | 14       | 0.77%   |
| 3733    | 12       | 0.66%   |
| 400     | 12       | 0.66%   |
| 2800    | 11       | 0.6%    |
| 1067    | 10       | 0.55%   |
| 3800    | 8        | 0.44%   |
| 3400    | 7        | 0.38%   |
| 3151    | 7        | 0.38%   |
| 333     | 7        | 0.38%   |
| 2733    | 6        | 0.33%   |
| 1400    | 6        | 0.33%   |
| 1334    | 6        | 0.33%   |
| 3866    | 5        | 0.27%   |
| 3007    | 5        | 0.27%   |
| 2048    | 5        | 0.27%   |
| 1639    | 5        | 0.27%   |
| 533     | 5        | 0.27%   |
| 3334    | 4        | 0.22%   |
| 3066    | 4        | 0.22%   |
| 2000    | 4        | 0.22%   |
| 49926   | 3        | 0.16%   |
| 3500    | 3        | 0.16%   |
| 3333    | 3        | 0.16%   |
| 3100    | 3        | 0.16%   |
| 2866    | 3        | 0.16%   |
| 2465    | 3        | 0.16%   |
| 2200    | 3        | 0.16%   |
| 2134    | 3        | 0.16%   |
| 2132    | 3        | 0.16%   |
| 4800    | 2        | 0.11%   |
| 4199    | 2        | 0.11%   |
| 4000    | 2        | 0.11%   |
| 3067    | 2        | 0.11%   |
| 266     | 2        | 0.11%   |
| 200     | 2        | 0.11%   |
| 52217   | 1        | 0.05%   |
| 8192    | 1        | 0.05%   |
| 4333    | 1        | 0.05%   |
| 4266    | 1        | 0.05%   |
| 4133    | 1        | 0.05%   |
| 3666    | 1        | 0.05%   |
| 3266    | 1        | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 128      | 38.1%   |
| Brother Industries       | 70       | 20.83%  |
| Canon                    | 53       | 15.77%  |
| Samsung Electronics      | 30       | 8.93%   |
| Seiko Epson              | 27       | 8.04%   |
| QinHeng Electronics      | 5        | 1.49%   |
| Prolific Technology      | 4        | 1.19%   |
| Seiko Instruments        | 2        | 0.6%    |
| Pantum                   | 2        | 0.6%    |
| Kyocera                  | 2        | 0.6%    |
| Dell                     | 2        | 0.6%    |
| Xerox                    | 1        | 0.3%    |
| Sato                     | 1        | 0.3%    |
| Ricoh                    | 1        | 0.3%    |
| Panasonic (Matsushita)   | 1        | 0.3%    |
| Oki Data                 | 1        | 0.3%    |
| NXP Semiconductors       | 1        | 0.3%    |
| Magic Control Technology | 1        | 0.3%    |
| Fuji Xerox               | 1        | 0.3%    |
| Dymo-CoStar              | 1        | 0.3%    |
| Agere Systems (Lucent)   | 1        | 0.3%    |
| Unknown                  | 1        | 0.3%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| HP LaserJet 1020                                      | 6        | 1.78%   |
| Samsung M2070 Series                                  | 5        | 1.48%   |
| Samsung M2020 Series                                  | 5        | 1.48%   |
| QinHeng CH340S                                        | 5        | 1.48%   |
| HP DeskJet 2620 All-in-One Printer                    | 5        | 1.48%   |
| Brother HL-L2360D series                              | 5        | 1.48%   |
| Samsung SCX-3400 Series                               | 4        | 1.19%   |
| Prolific PL2305 Parallel Port                         | 4        | 1.19%   |
| HP OfficeJet 5200 series                              | 4        | 1.19%   |
| HP Officejet 4500 G510n-z                             | 4        | 1.19%   |
| HP LaserJet P1005                                     | 4        | 1.19%   |
| HP LaserJet 1018                                      | 4        | 1.19%   |
| HP DeskJet F4200 series                               | 4        | 1.19%   |
| Brother Printer                                       | 4        | 1.19%   |
| Seiko Epson L210 Series                               | 3        | 0.89%   |
| HP OfficeJet Pro 69                                   | 3        | 0.89%   |
| HP LaserJet Professional P 1102w                      | 3        | 0.89%   |
| HP ENVY 5540 series                                   | 3        | 0.89%   |
| HP ENVY 4520 series                                   | 3        | 0.89%   |
| HP DeskJet 3630 series                                | 3        | 0.89%   |
| HP Deskjet 2540 series                                | 3        | 0.89%   |
| HP DeskJet 2130 series                                | 3        | 0.89%   |
| Canon LiDE 400                                        | 3        | 0.89%   |
| Brother MFC-J497DW                                    | 3        | 0.89%   |
| Brother HL-2270DW Laser Printer                       | 3        | 0.89%   |
| Brother HL-1110 series                                | 3        | 0.89%   |
| Brother DCP-7055 scanner/printer                      | 3        | 0.89%   |
| Seiko Epson Printer                                   | 2        | 0.59%   |
| Seiko Epson L365 Series                               | 2        | 0.59%   |
| Seiko Epson L222 Series                               | 2        | 0.59%   |
| Seiko Epson ET-2710 Series                            | 2        | 0.59%   |
| Samsung C48x Series Color Laser Multifunction Printer | 2        | 0.59%   |
| HP OfficeJet Pro 8020 series                          | 2        | 0.59%   |
| HP OfficeJet 6950                                     | 2        | 0.59%   |
| HP OfficeJet 4650 series                              | 2        | 0.59%   |
| HP OfficeJet 3830 series                              | 2        | 0.59%   |
| HP LaserJet Professional P1102w                       | 2        | 0.59%   |
| HP LaserJet P2014                                     | 2        | 0.59%   |
| HP LaserJet P1102                                     | 2        | 0.59%   |
| HP LaserJet 1010                                      | 2        | 0.59%   |
| HP ENVY 5000 series                                   | 2        | 0.59%   |
| HP Deskjet 4620 series                                | 2        | 0.59%   |
| HP DeskJet 3700 series                                | 2        | 0.59%   |
| HP Deskjet 3050 J610 series                           | 2        | 0.59%   |
| HP Deskjet 2050 J510                                  | 2        | 0.59%   |
| HP Deskjet 1050 J410                                  | 2        | 0.59%   |
| HP Deskjet 1000 J110 series                           | 2        | 0.59%   |
| Canon TR4500 series                                   | 2        | 0.59%   |
| Canon PIXMA MX490 Series                              | 2        | 0.59%   |
| Canon PIXMA MG3500 Series                             | 2        | 0.59%   |
| Canon PIXMA MG3000 series                             | 2        | 0.59%   |
| Canon MF4320-4350                                     | 2        | 0.59%   |
| Canon LBP2900                                         | 2        | 0.59%   |
| Canon iP4800 series                                   | 2        | 0.59%   |
| Canon I-SENSYS MF4550d                                | 2        | 0.59%   |
| Canon G3000 series                                    | 2        | 0.59%   |
| Brother MFC-L2710DW series                            | 2        | 0.59%   |
| Brother MFC-1810                                      | 2        | 0.59%   |
| Brother HL-3142CW series                              | 2        | 0.59%   |
| Brother HL-3140CW series                              | 2        | 0.59%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 56       | 58.95%  |
| Seiko Epson                 | 17       | 17.89%  |
| Hewlett-Packard             | 11       | 11.58%  |
| Mustek Systems              | 4        | 4.21%   |
| Ultima Electronics          | 2        | 2.11%   |
| Acer Peripherals (now BenQ) | 2        | 2.11%   |
| UMAX                        | 1        | 1.05%   |
| Microtek International      | 1        | 1.05%   |
| AGFA-Gevaert NV             | 1        | 1.05%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LIDE 25                                                                | 10       | 10.53%  |
| Canon CanoScan LiDE 110                                                               | 10       | 10.53%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 5        | 5.26%   |
| Canon CanoScan LiDE 120                                                               | 5        | 5.26%   |
| Canon CanoScan LiDE 700F                                                              | 4        | 4.21%   |
| Canon CanoScan LiDE 220                                                               | 4        | 4.21%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 3        | 3.16%   |
| Canon CanoScan LiDE 90                                                                | 3        | 3.16%   |
| Canon CanoScan LiDE 60                                                                | 3        | 3.16%   |
| Canon CanoScan LiDE 210                                                               | 3        | 3.16%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2        | 2.11%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 2        | 2.11%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 2        | 2.11%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2        | 2.11%   |
| Mustek Systems SNAPSCAN e22                                                           | 2        | 2.11%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 2        | 2.11%   |
| HP ScanJet 2400c                                                                      | 2        | 2.11%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 2.11%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 2        | 2.11%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                           | 2        | 2.11%   |
| UMAX Astra 4400/4450                                                                  | 1        | 1.05%   |
| Seiko Epson Stylus Photo RX500/510                                                    | 1        | 1.05%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1        | 1.05%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1        | 1.05%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1        | 1.05%   |
| Seiko Epson GT-F600 [Perfection 4180]                                                 | 1        | 1.05%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1        | 1.05%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1        | 1.05%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 1        | 1.05%   |
| Microtek International USB1200 Scanner                                                | 1        | 1.05%   |
| HP ScanJet G3010                                                                      | 1        | 1.05%   |
| HP ScanJet 5200c                                                                      | 1        | 1.05%   |
| HP ScanJet 4070 PhotoSmart                                                            | 1        | 1.05%   |
| HP ScanJet 3800c                                                                      | 1        | 1.05%   |
| HP ScanJet 3670                                                                       | 1        | 1.05%   |
| HP Scanjet 300                                                                        | 1        | 1.05%   |
| HP ScanJet 2200c                                                                      | 1        | 1.05%   |
| HP Scanjet 200                                                                        | 1        | 1.05%   |
| HP HP4470C                                                                            | 1        | 1.05%   |
| Canon CanoScan N650U/N656U                                                            | 1        | 1.05%   |
| Canon CanoScan LiDE 200                                                               | 1        | 1.05%   |
| Canon CanoScan 9000F Mark II                                                          | 1        | 1.05%   |
| Canon CanoScan 8000F                                                                  | 1        | 1.05%   |
| Canon CanoScan                                                                        | 1        | 1.05%   |
| AGFA-Gevaert NV SnapScan 1212U                                                        | 1        | 1.05%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 309      | 34.88%  |
| Microdia                               | 81       | 9.14%   |
| Microsoft                              | 61       | 6.88%   |
| Samsung Electronics                    | 48       | 5.42%   |
| Chicony Electronics                    | 31       | 3.5%    |
| Z-Star Microelectronics                | 28       | 3.16%   |
| Sunplus Innovation Technology          | 25       | 2.82%   |
| Generalplus Technology                 | 24       | 2.71%   |
| GEMBIRD                                | 21       | 2.37%   |
| Creative Technology                    | 18       | 2.03%   |
| Realtek Semiconductor                  | 17       | 1.92%   |
| Apple                                  | 17       | 1.92%   |
| KYE Systems (Mouse Systems)            | 16       | 1.81%   |
| Aveo Technology                        | 15       | 1.69%   |
| ARC International                      | 12       | 1.35%   |
| Arkmicro Technologies                  | 11       | 1.24%   |
| IMC Networks                           | 10       | 1.13%   |
| LG Electronics                         | 8        | 0.9%    |
| Cubeternet                             | 8        | 0.9%    |
| MacroSilicon                           | 7        | 0.79%   |
| Jieli Technology                       | 7        | 0.79%   |
| Genesys Logic                          | 7        | 0.79%   |
| Alcor Micro                            | 7        | 0.79%   |
| Pixart Imaging                         | 6        | 0.68%   |
| Novatek Microelectronics               | 6        | 0.68%   |
| Sonix Technology                       | 5        | 0.56%   |
| Philips (or NXP)                       | 5        | 0.56%   |
| Hewlett-Packard                        | 5        | 0.56%   |
| Silicon Motion                         | 4        | 0.45%   |
| Huawei Technologies                    | 4        | 0.45%   |
| AVerMedia Technologies                 | 4        | 0.45%   |
| Unknown                                | 3        | 0.34%   |
| Trust                                  | 3        | 0.34%   |
| Syntek                                 | 3        | 0.34%   |
| SJ-180517-N                            | 3        | 0.34%   |
| Cheng Uei Precision Industry (Foxlink) | 3        | 0.34%   |
| Asuscom Network                        | 3        | 0.34%   |
| YGTek                                  | 2        | 0.23%   |
| webcam                                 | 2        | 0.23%   |
| WaveRider Communications               | 2        | 0.23%   |
| OmniVision Technologies                | 2        | 0.23%   |
| MediaTek                               | 2        | 0.23%   |
| Lenovo                                 | 2        | 0.23%   |
| Guillemot                              | 2        | 0.23%   |
| Google                                 | 2        | 0.23%   |
| YSD-2053--200409                       | 1        | 0.11%   |
| YJX                                    | 1        | 0.11%   |
| Xiongmai                               | 1        | 0.11%   |
| Xiaomi                                 | 1        | 0.11%   |
| USB3.0 HD Audio Capture                | 1        | 0.11%   |
| TP                                     | 1        | 0.11%   |
| Teslong Camera                         | 1        | 0.11%   |
| T & A Mobile Phones                    | 1        | 0.11%   |
| Sunplus Technology                     | 1        | 0.11%   |
| Spreadtrum Communications              | 1        | 0.11%   |
| Sony                                   | 1        | 0.11%   |
| SHENZHEN EMEET TECHNOLOGY              | 1        | 0.11%   |
| Ruision                                | 1        | 0.11%   |
| Razer USA                              | 1        | 0.11%   |
| PrehKeyTec                             | 1        | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 80       | 9.01%   |
| Samsung Galaxy A5 (MTP)                               | 48       | 5.41%   |
| Logitech HD Pro Webcam C920                           | 38       | 4.28%   |
| Microsoft LifeCam HD-3000                             | 27       | 3.04%   |
| Microdia Webcam Vitade AF                             | 23       | 2.59%   |
| Logitech HD Webcam C525                               | 23       | 2.59%   |
| Logitech Webcam C170                                  | 21       | 2.36%   |
| Logitech Webcam C310                                  | 19       | 2.14%   |
| Microdia Camera                                       | 17       | 1.91%   |
| Apple iPhone 5/5C/5S/6/SE                             | 17       | 1.91%   |
| Microdia Sonix USB 2.0 Camera                         | 12       | 1.35%   |
| ARC International Camera                              | 12       | 1.35%   |
| Z-Star Venus USB2.0 Camera                            | 11       | 1.24%   |
| Generalplus GENERAL WEBCAM                            | 11       | 1.24%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 11       | 1.24%   |
| Sunplus Live Camera                                   | 10       | 1.13%   |
| Realtek FULL HD 1080P Webcam                          | 10       | 1.13%   |
| Logitech HD Webcam C615                               | 10       | 1.13%   |
| Logitech Webcam C210                                  | 9        | 1.01%   |
| Generalplus 808 Camera #9 (web-cam mode)              | 9        | 1.01%   |
| Chicony HP High Definition 1MP Webcam                 | 9        | 1.01%   |
| Microdia USB 2.0 Camera                               | 8        | 0.9%    |
| Microdia JP001                                        | 8        | 0.9%    |
| Logitech Webcam C200                                  | 8        | 0.9%    |
| GEMBIRD USB2.0 PC CAMERA                              | 8        | 0.9%    |
| Arkmicro USB2.0 PC CAMERA                             | 8        | 0.9%    |
| Logitech Webcam C925e                                 | 7        | 0.79%   |
| Logitech QuickCam Pro 9000                            | 7        | 0.79%   |
| Logitech HD Webcam C910                               | 7        | 0.79%   |
| Logitech C920 PRO HD Webcam                           | 7        | 0.79%   |
| Jieli USB PHY 2.0                                     | 7        | 0.79%   |
| Creative Live! Cam Chat HD [VF0700]                   | 7        | 0.79%   |
| Microsoft LifeCam HD-5000                             | 6        | 0.68%   |
| Microsoft LifeCam Cinema                              | 6        | 0.68%   |
| Logitech C922 Pro Stream Webcam                       | 6        | 0.68%   |
| IMC Networks XHC Camera                               | 6        | 0.68%   |
| Aveo UVC camera (Bresser microscope)                  | 6        | 0.68%   |
| Aveo USB2.0 Camera                                    | 6        | 0.68%   |
| Z-Star Vimicro USB Camera (Altair)                    | 5        | 0.56%   |
| Sunplus Integrated_Webcam_HD                          | 5        | 0.56%   |
| MacroSilicon USB Video                                | 5        | 0.56%   |
| Logitech QuickCam Pro 5000                            | 5        | 0.56%   |
| Logitech HD Webcam C510                               | 5        | 0.56%   |
| Alcor Micro USB 2.0 PC Camera                         | 5        | 0.56%   |
| Z-Star Integrated Camera                              | 4        | 0.45%   |
| Realtek HP 1.0MP High Definition Webcam               | 4        | 0.45%   |
| Pixart Imaging USB2.0_Camera                          | 4        | 0.45%   |
| Microsoft LifeCam Studio                              | 4        | 0.45%   |
| Microdia Laptop_Integrated_Webcam_FHD                 | 4        | 0.45%   |
| Logitech Webcam Pro 9000                              | 4        | 0.45%   |
| Logitech Webcam C600                                  | 4        | 0.45%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 4        | 0.45%   |
| Huawei UVC Camera                                     | 4        | 0.45%   |
| Generalplus USB WEBCAM                                | 4        | 0.45%   |
| Creative Live! Cam Sync HD [VF0770]                   | 4        | 0.45%   |
| Chicony CNF8050 Webcam                                | 4        | 0.45%   |
| Z-Star A4 TECH USB2.0 PC Camera J                     | 3        | 0.34%   |
| Sonix USB Camera                                      | 3        | 0.34%   |
| SJ-180517-N 1080P Webcam                              | 3        | 0.34%   |
| Philips (or NXP) Webcam SPC530NC                      | 3        | 0.34%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 3        | 42.86%  |
| Synaptics                  | 1        | 14.29%  |
| STMicroelectronics         | 1        | 14.29%  |
| Shenzhen Goodix Technology | 1        | 14.29%  |
| AuthenTec                  | 1        | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Elan ELAN:Fingerprint                        | 3        | 42.86%  |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 14.29%  |
| STMicroelectronics Fingerprint Reader        | 1        | 14.29%  |
| Shenzhen Goodix  Fingerprint Device          | 1        | 14.29%  |
| AuthenTec AES2550 Fingerprint Sensor         | 1        | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Alcor Micro                       | 7        | 25.93%  |
| SCM Microsystems                  | 3        | 11.11%  |
| OmniKey                           | 3        | 11.11%  |
| Realtek Semiconductor             | 2        | 7.41%   |
| Chicony Electronics               | 2        | 7.41%   |
| VASCO Data Security International | 1        | 3.7%    |
| Reiner SCT Kartensysteme          | 1        | 3.7%    |
| In Focus Systems                  | 1        | 3.7%    |
| Giesecke & Devrient               | 1        | 3.7%    |
| Gemalto (was Gemplus)             | 1        | 3.7%    |
| Fujitsu Siemens Computers         | 1        | 3.7%    |
| BIT4ID                            | 1        | 3.7%    |
| ARDS                              | 1        | 3.7%    |
| Aktiv                             | 1        | 3.7%    |
| Advanced Card Systems             | 1        | 3.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Alcor Micro Watchdata W 1981                                    | 4        | 14.81%  |
| OmniKey CardMan 3021 / 3121                                     | 3        | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                             | 3        | 11.11%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 2        | 7.41%   |
| Realtek Semiconductor Smart Card Reader Interface               | 2        | 7.41%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 2        | 7.41%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 3.7%    |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 3.7%    |
| Reiner SCT Kartensysteme tanJack USB                            | 1        | 3.7%    |
| In Focus Systems EMV Smartcard Reader                           | 1        | 3.7%    |
| Giesecke & Devrient StarSign CUT                                | 1        | 3.7%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 1        | 3.7%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                   | 1        | 3.7%    |
| BIT4ID miniLector-S                                             | 1        | 3.7%    |
| ARDS JaCarta                                                    | 1        | 3.7%    |
| Aktiv Rutoken lite                                              | 1        | 3.7%    |
| Advanced Card Systems ACR122U                                   | 1        | 3.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3806     | 82.88%  |
| 1     | 657      | 14.31%  |
| 2     | 100      | 2.18%   |
| 3     | 19       | 0.41%   |
| 4     | 6        | 0.13%   |
| 5     | 3        | 0.07%   |
| 6     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 295      | 32.74%  |
| Net/wireless             | 233      | 25.86%  |
| Communication controller | 105      | 11.65%  |
| Unassigned class         | 42       | 4.66%   |
| Multimedia controller    | 39       | 4.33%   |
| Sound                    | 34       | 3.77%   |
| Network                  | 23       | 2.55%   |
| Camera                   | 20       | 2.22%   |
| Bluetooth                | 18       | 2%      |
| Chipcard                 | 16       | 1.78%   |
| Net/ethernet             | 13       | 1.44%   |
| Modem                    | 12       | 1.33%   |
| Card reader              | 12       | 1.33%   |
| Storage/ide              | 10       | 1.11%   |
| Storage/raid             | 9        | 1%      |
| Dvb card                 | 7        | 0.78%   |
| Fingerprint reader       | 6        | 0.67%   |
| Tv card                  | 2        | 0.22%   |
| Firewire controller      | 2        | 0.22%   |
| Unclassified device      | 1        | 0.11%   |
| Storage/nvme             | 1        | 0.11%   |
| Storage/ata              | 1        | 0.11%   |
