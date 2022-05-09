Linux in Egypt - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Egypt.

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

Total: 327

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion 15                 | [ef6a55e4fc](https://linux-hardware.org/?probe=ef6a55e4fc) | May 07, 2022 |
| Dell          | Inspiron N4050              | [6d8f615203](https://linux-hardware.org/?probe=6d8f615203) | Apr 30, 2022 |
| Dell          | Inspiron N5110              | [fb1248d6be](https://linux-hardware.org/?probe=fb1248d6be) | Apr 29, 2022 |
| HP            | Pavilion 15                 | [2484213956](https://linux-hardware.org/?probe=2484213956) | Apr 29, 2022 |
| HP            | Pavilion 15                 | [fee7e96d70](https://linux-hardware.org/?probe=fee7e96d70) | Apr 28, 2022 |
| Fujitsu       | FMVA06004                   | [4c63e1bcc2](https://linux-hardware.org/?probe=4c63e1bcc2) | Apr 25, 2022 |
| Dell          | Latitude 3440               | [a0c0358f78](https://linux-hardware.org/?probe=a0c0358f78) | Apr 24, 2022 |
| HP            | Laptop 15-bs0xx             | [a1636896d9](https://linux-hardware.org/?probe=a1636896d9) | Apr 22, 2022 |
| HP            | Laptop 15-bs0xx             | [03481a94b3](https://linux-hardware.org/?probe=03481a94b3) | Apr 22, 2022 |
| HP            | 15                          | [3253e0fc56](https://linux-hardware.org/?probe=3253e0fc56) | Apr 21, 2022 |
| Sony          | SVT1121B2EW                 | [dd43f45353](https://linux-hardware.org/?probe=dd43f45353) | Apr 21, 2022 |
| Dell          | Inspiron 7577               | [6843f2bcfe](https://linux-hardware.org/?probe=6843f2bcfe) | Apr 20, 2022 |
| Alienware     | 17                          | [b9b420077c](https://linux-hardware.org/?probe=b9b420077c) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [fecdd237a4](https://linux-hardware.org/?probe=fecdd237a4) | Apr 11, 2022 |
| Lenovo        | Flex 2-14 20404             | [4368114931](https://linux-hardware.org/?probe=4368114931) | Apr 04, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f93e8f46c2](https://linux-hardware.org/?probe=f93e8f46c2) | Apr 01, 2022 |
| HP            | Laptop 15-bs0xx             | [bd875807ce](https://linux-hardware.org/?probe=bd875807ce) | Mar 26, 2022 |
| HP            | Laptop 15-bs0xx             | [d6a6546ccd](https://linux-hardware.org/?probe=d6a6546ccd) | Mar 26, 2022 |
| HP            | Laptop 15-bs0xx             | [96f9ba743f](https://linux-hardware.org/?probe=96f9ba743f) | Mar 25, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [55a2911462](https://linux-hardware.org/?probe=55a2911462) | Mar 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Notebook                    | [4cc8a23994](https://linux-hardware.org/?probe=4cc8a23994) | Mar 22, 2022 |
| HP            | Notebook                    | [cb2c910f05](https://linux-hardware.org/?probe=cb2c910f05) | Mar 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [99dc5cde41](https://linux-hardware.org/?probe=99dc5cde41) | Mar 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d74cd69ff9](https://linux-hardware.org/?probe=d74cd69ff9) | Mar 20, 2022 |
| HP            | Pavilion 15                 | [0f3cb22c3d](https://linux-hardware.org/?probe=0f3cb22c3d) | Mar 20, 2022 |
| HP            | G62                         | [5a5a9ce935](https://linux-hardware.org/?probe=5a5a9ce935) | Mar 20, 2022 |
| HP            | ENVY dv6                    | [39ff0aa86d](https://linux-hardware.org/?probe=39ff0aa86d) | Mar 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [55533901d3](https://linux-hardware.org/?probe=55533901d3) | Mar 11, 2022 |
| Dell          | Latitude 3410               | [d21a10beb4](https://linux-hardware.org/?probe=d21a10beb4) | Mar 10, 2022 |
| Acer          | Aspire ES1-331              | [cbba045d50](https://linux-hardware.org/?probe=cbba045d50) | Mar 05, 2022 |
| HP            | Pavilion Notebook           | [57bb50b654](https://linux-hardware.org/?probe=57bb50b654) | Feb 27, 2022 |
| Dell          | Venue 10 Pro 5056           | [faf162367f](https://linux-hardware.org/?probe=faf162367f) | Feb 25, 2022 |
| HP            | Laptop 15-db0xxx            | [732784f9ec](https://linux-hardware.org/?probe=732784f9ec) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | [2c3ac58820](https://linux-hardware.org/?probe=2c3ac58820) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | [eed2589bd2](https://linux-hardware.org/?probe=eed2589bd2) | Feb 25, 2022 |
| HP            | ENVY dv6                    | [6d07aead9f](https://linux-hardware.org/?probe=6d07aead9f) | Feb 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f0c89a4e5b](https://linux-hardware.org/?probe=f0c89a4e5b) | Feb 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [cf41cc6ddb](https://linux-hardware.org/?probe=cf41cc6ddb) | Feb 15, 2022 |
| Dell          | G3 3500                     | [0010596573](https://linux-hardware.org/?probe=0010596573) | Feb 10, 2022 |
| Dell          | Latitude E6540              | [9129341c42](https://linux-hardware.org/?probe=9129341c42) | Jan 24, 2022 |
| HP            | ProBook 445 G7              | [bceca55120](https://linux-hardware.org/?probe=bceca55120) | Jan 23, 2022 |
| Sony          | SVF15328CXB                 | [d55d8f394d](https://linux-hardware.org/?probe=d55d8f394d) | Jan 21, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dfbb7c034f](https://linux-hardware.org/?probe=dfbb7c034f) | Jan 20, 2022 |
| HP            | 250 G7 Notebook PC          | [6da1d84e76](https://linux-hardware.org/?probe=6da1d84e76) | Jan 16, 2022 |
| Dell          | Inspiron N5010              | [4edc707b67](https://linux-hardware.org/?probe=4edc707b67) | Jan 14, 2022 |
| HP            | EliteBook 8440p             | [b70942532f](https://linux-hardware.org/?probe=b70942532f) | Jan 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| HP            | EliteBook 8440p             | [bda1b240c9](https://linux-hardware.org/?probe=bda1b240c9) | Dec 28, 2021 |
| Dell          | G15 5510                    | [1209f0844f](https://linux-hardware.org/?probe=1209f0844f) | Dec 20, 2021 |
| Dell          | G15 5510                    | [e5039b3b7d](https://linux-hardware.org/?probe=e5039b3b7d) | Dec 18, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [f8dc028352](https://linux-hardware.org/?probe=f8dc028352) | Dec 08, 2021 |
| HP            | Compaq CQ58                 | [dd578dae69](https://linux-hardware.org/?probe=dd578dae69) | Dec 05, 2021 |
| HP            | Compaq CQ58                 | [d15350584d](https://linux-hardware.org/?probe=d15350584d) | Dec 05, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [d6acd43784](https://linux-hardware.org/?probe=d6acd43784) | Nov 25, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [e820cb3456](https://linux-hardware.org/?probe=e820cb3456) | Nov 25, 2021 |
| HP            | ProBook 470 G3              | [49f973804a](https://linux-hardware.org/?probe=49f973804a) | Nov 13, 2021 |
| Dell          | Latitude 5420               | [973018da2b](https://linux-hardware.org/?probe=973018da2b) | Nov 08, 2021 |
| Dell          | Inspiron 3537               | [eacb69d71e](https://linux-hardware.org/?probe=eacb69d71e) | Nov 05, 2021 |
| Lenovo        | ThinkPad E14 20RAS0CM00     | [a35aaaeb6d](https://linux-hardware.org/?probe=a35aaaeb6d) | Oct 31, 2021 |
| HP            | 255 G7 Notebook PC          | [e8781db5ab](https://linux-hardware.org/?probe=e8781db5ab) | Oct 31, 2021 |
| HP            | 255 G7 Notebook PC          | [e1978d5164](https://linux-hardware.org/?probe=e1978d5164) | Oct 31, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [08d287d2e2](https://linux-hardware.org/?probe=08d287d2e2) | Oct 30, 2021 |
| HP            | ProBook 6460b               | [317c62df4b](https://linux-hardware.org/?probe=317c62df4b) | Oct 23, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | [2db5d6dc7c](https://linux-hardware.org/?probe=2db5d6dc7c) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | [1faf3f28e5](https://linux-hardware.org/?probe=1faf3f28e5) | Oct 20, 2021 |
| Dell          | Inspiron 3521               | [831fff897a](https://linux-hardware.org/?probe=831fff897a) | Oct 15, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d69772c626](https://linux-hardware.org/?probe=d69772c626) | Oct 14, 2021 |
| Lenovo        | ThinkPad E15 20RD0086ED     | [2db7f4be45](https://linux-hardware.org/?probe=2db7f4be45) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e8ae6d00a2](https://linux-hardware.org/?probe=e8ae6d00a2) | Oct 12, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d0fb953c7e](https://linux-hardware.org/?probe=d0fb953c7e) | Oct 11, 2021 |
| HP            | ProBook 645 G1              | [102902cf2b](https://linux-hardware.org/?probe=102902cf2b) | Oct 10, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [51d51a675d](https://linux-hardware.org/?probe=51d51a675d) | Oct 10, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [f8d957d29f](https://linux-hardware.org/?probe=f8d957d29f) | Oct 09, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [6c5495590b](https://linux-hardware.org/?probe=6c5495590b) | Oct 08, 2021 |
| Hampoo        | Cherry Trail CR             | [b95391e679](https://linux-hardware.org/?probe=b95391e679) | Oct 03, 2021 |
| Hampoo        | Cherry Trail CR             | [61c4dc2ac2](https://linux-hardware.org/?probe=61c4dc2ac2) | Oct 03, 2021 |
| ASUSTek       | N501JW                      | [0e37d3409d](https://linux-hardware.org/?probe=0e37d3409d) | Oct 01, 2021 |
| Dell          | Inspiron 5584               | [48b4af3338](https://linux-hardware.org/?probe=48b4af3338) | Sep 01, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [d2e64a8d57](https://linux-hardware.org/?probe=d2e64a8d57) | Aug 08, 2021 |
| HP            | Compaq 2510p                | [ea3c7d2fe2](https://linux-hardware.org/?probe=ea3c7d2fe2) | Aug 07, 2021 |
| HP            | Compaq 2510p                | [31449a4b42](https://linux-hardware.org/?probe=31449a4b42) | Aug 07, 2021 |
| Packard Be... | EasyNote LX                 | [125ad979fe](https://linux-hardware.org/?probe=125ad979fe) | Aug 06, 2021 |
| Dell          | G3 3579                     | [4f7539c771](https://linux-hardware.org/?probe=4f7539c771) | Jul 30, 2021 |
| Dell          | Inspiron 1564               | [08fc5f3b99](https://linux-hardware.org/?probe=08fc5f3b99) | Jul 27, 2021 |
| Dell          | Inspiron 5570               | [b07887acc1](https://linux-hardware.org/?probe=b07887acc1) | Jul 18, 2021 |
| Lenovo        | G510 20238                  | [428dcd6503](https://linux-hardware.org/?probe=428dcd6503) | Jul 07, 2021 |
| Dell          | G3 3579                     | [97c520db01](https://linux-hardware.org/?probe=97c520db01) | Jul 04, 2021 |
| ASUSTek       | X200MA                      | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| Dell          | Inspiron 1545               | [8c7ef2bc15](https://linux-hardware.org/?probe=8c7ef2bc15) | Jun 20, 2021 |
| Dell          | Inspiron 1545               | [4c397b8b70](https://linux-hardware.org/?probe=4c397b8b70) | Jun 20, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [05dbeca379](https://linux-hardware.org/?probe=05dbeca379) | Jun 17, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [f685842bb1](https://linux-hardware.org/?probe=f685842bb1) | Jun 16, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [696a1c9564](https://linux-hardware.org/?probe=696a1c9564) | Jun 13, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [e57c2fb16d](https://linux-hardware.org/?probe=e57c2fb16d) | May 30, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [976e39384a](https://linux-hardware.org/?probe=976e39384a) | May 30, 2021 |
| HP            | ProBook 645 G1              | [a92458c2db](https://linux-hardware.org/?probe=a92458c2db) | May 26, 2021 |
| Fujitsu       | LIFEBOOK S752               | [6ae217a5a8](https://linux-hardware.org/?probe=6ae217a5a8) | May 21, 2021 |
| Dell          | G5 5587                     | [fae808ae7d](https://linux-hardware.org/?probe=fae808ae7d) | May 02, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [cb93a75f6a](https://linux-hardware.org/?probe=cb93a75f6a) | Apr 28, 2021 |
| HP            | Notebook                    | [872a5f9112](https://linux-hardware.org/?probe=872a5f9112) | Apr 18, 2021 |
| Hampoo        | Cherry Trail CR             | [101c47c9a2](https://linux-hardware.org/?probe=101c47c9a2) | Apr 17, 2021 |
| Fujitsu Si... | AMILO Li1705                | [3200f41cf0](https://linux-hardware.org/?probe=3200f41cf0) | Apr 13, 2021 |
| HP            | 15                          | [27bcfc6f15](https://linux-hardware.org/?probe=27bcfc6f15) | Apr 10, 2021 |
| HP            | 15                          | [aebfb75282](https://linux-hardware.org/?probe=aebfb75282) | Apr 10, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [820db16b30](https://linux-hardware.org/?probe=820db16b30) | Apr 08, 2021 |
| Dell          | Inspiron 3580               | [fcb5ccbc6c](https://linux-hardware.org/?probe=fcb5ccbc6c) | Apr 08, 2021 |
| Dell          | Inspiron 7577               | [a3ecba2a79](https://linux-hardware.org/?probe=a3ecba2a79) | Apr 06, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [bb1ef328b0](https://linux-hardware.org/?probe=bb1ef328b0) | Mar 30, 2021 |
| HP            | Unknown                     | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| HP            | Pavilion dv6                | [ecb76b364b](https://linux-hardware.org/?probe=ecb76b364b) | Mar 20, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [9dbe8f6250](https://linux-hardware.org/?probe=9dbe8f6250) | Mar 12, 2021 |
| TECNO         | WinPad 10A                  | [e96bf0a4fa](https://linux-hardware.org/?probe=e96bf0a4fa) | Mar 08, 2021 |
| Lenovo        | AILZx                       | [b0c93e5b27](https://linux-hardware.org/?probe=b0c93e5b27) | Mar 07, 2021 |
| Lenovo        | AILZx                       | [d06410a1dd](https://linux-hardware.org/?probe=d06410a1dd) | Mar 04, 2021 |
| Lenovo        | AILZx                       | [cf1bc93ffd](https://linux-hardware.org/?probe=cf1bc93ffd) | Mar 04, 2021 |
| Lenovo        | G50-80 80E5                 | [5ba97fc0d2](https://linux-hardware.org/?probe=5ba97fc0d2) | Mar 03, 2021 |
| HP            | EliteBook 8470p             | [586d9baf41](https://linux-hardware.org/?probe=586d9baf41) | Feb 25, 2021 |
| HP            | EliteBook 8470p             | [f22c5da52d](https://linux-hardware.org/?probe=f22c5da52d) | Feb 25, 2021 |
| Dell          | Inspiron 5570               | [4fd5f831b6](https://linux-hardware.org/?probe=4fd5f831b6) | Feb 22, 2021 |
| Dell          | Latitude XT3                | [2335b761fb](https://linux-hardware.org/?probe=2335b761fb) | Feb 16, 2021 |
| HP            | 250 G3                      | [67cb272c8e](https://linux-hardware.org/?probe=67cb272c8e) | Feb 14, 2021 |
| Dell          | Latitude XT3                | [94f5a1f396](https://linux-hardware.org/?probe=94f5a1f396) | Feb 13, 2021 |
| Lenovo        | G50-80 80E5                 | [3624afadba](https://linux-hardware.org/?probe=3624afadba) | Feb 10, 2021 |
| HP            | Laptop 15-da1xxx            | [6472781079](https://linux-hardware.org/?probe=6472781079) | Feb 09, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [fdfa43b360](https://linux-hardware.org/?probe=fdfa43b360) | Feb 01, 2021 |
| HP            | ProBook 450 G7              | [7e3a962336](https://linux-hardware.org/?probe=7e3a962336) | Jan 31, 2021 |
| Lenovo        | G50-80 80E5                 | [9072c5e554](https://linux-hardware.org/?probe=9072c5e554) | Jan 29, 2021 |
| HP            | Pavilion dv6                | [55752483ef](https://linux-hardware.org/?probe=55752483ef) | Jan 25, 2021 |
| Lenovo        | ThinkPad T580 20LAS09100    | [92d071729f](https://linux-hardware.org/?probe=92d071729f) | Jan 22, 2021 |
| HP            | Laptop 15-da1xxx            | [e596928019](https://linux-hardware.org/?probe=e596928019) | Jan 22, 2021 |
| HP            | Laptop 15-da1xxx            | [8b2119a584](https://linux-hardware.org/?probe=8b2119a584) | Jan 22, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [bdfeee2839](https://linux-hardware.org/?probe=bdfeee2839) | Jan 21, 2021 |
| Dell          | G3 3590                     | [27fb9a0695](https://linux-hardware.org/?probe=27fb9a0695) | Jan 12, 2021 |
| HP            | Pavilion dv6                | [dbf279a62e](https://linux-hardware.org/?probe=dbf279a62e) | Jan 07, 2021 |
| HP            | Pavilion dv6                | [f14ce7c7c0](https://linux-hardware.org/?probe=f14ce7c7c0) | Jan 07, 2021 |
| Dell          | Inspiron 5520               | [a8f7f002a3](https://linux-hardware.org/?probe=a8f7f002a3) | Jan 06, 2021 |
| Dell          | Inspiron 7577               | [09ee69f73b](https://linux-hardware.org/?probe=09ee69f73b) | Jan 05, 2021 |
| HP            | ZBook 15 G2                 | [062d9c02f6](https://linux-hardware.org/?probe=062d9c02f6) | Jan 03, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [f13f9a9cdc](https://linux-hardware.org/?probe=f13f9a9cdc) | Dec 31, 2020 |
| HP            | Pavilion dv6                | [d18c93f636](https://linux-hardware.org/?probe=d18c93f636) | Dec 31, 2020 |
| HP            | Pavilion dv6                | [0a288440a6](https://linux-hardware.org/?probe=0a288440a6) | Dec 31, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [1262d56db8](https://linux-hardware.org/?probe=1262d56db8) | Dec 30, 2020 |
| Dell          | Latitude E6400              | [9f5ac2d658](https://linux-hardware.org/?probe=9f5ac2d658) | Dec 30, 2020 |
| Toshiba       | Satellite C660              | [054d224782](https://linux-hardware.org/?probe=054d224782) | Dec 25, 2020 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [7038da6d94](https://linux-hardware.org/?probe=7038da6d94) | Dec 25, 2020 |
| Apple         | MacBookPro5,3               | [29542ce3fc](https://linux-hardware.org/?probe=29542ce3fc) | Dec 23, 2020 |
| Lenovo        | ThinkPad E15 20RD001HAD     | [4f6e684aa1](https://linux-hardware.org/?probe=4f6e684aa1) | Dec 22, 2020 |
| HP            | Pavilion g6                 | [172d4abbd7](https://linux-hardware.org/?probe=172d4abbd7) | Dec 19, 2020 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [9d4e1e6361](https://linux-hardware.org/?probe=9d4e1e6361) | Dec 17, 2020 |
| HP            | ProBook 4540s               | [a35b479f53](https://linux-hardware.org/?probe=a35b479f53) | Dec 09, 2020 |
| HP            | ZBook 15                    | [f7f246578a](https://linux-hardware.org/?probe=f7f246578a) | Dec 07, 2020 |
| ASUSTek       | X455LD                      | [9e5d7995ce](https://linux-hardware.org/?probe=9e5d7995ce) | Dec 03, 2020 |
| Lenovo        | ThinkPad T580 20LAS09100    | [d5a8abcbc5](https://linux-hardware.org/?probe=d5a8abcbc5) | Dec 01, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c9204a3c7d](https://linux-hardware.org/?probe=c9204a3c7d) | Nov 22, 2020 |
| Fujitsu       | LIFEBOOK S752               | [db7eb29112](https://linux-hardware.org/?probe=db7eb29112) | Nov 22, 2020 |
| I-Life Dig... | ZED AIR 2                   | [74f5e7c221](https://linux-hardware.org/?probe=74f5e7c221) | Nov 20, 2020 |
| I-Life Dig... | ZED AIR 2                   | [04802ac1cb](https://linux-hardware.org/?probe=04802ac1cb) | Nov 20, 2020 |
| HP            | ZBook 15                    | [9adafc3a81](https://linux-hardware.org/?probe=9adafc3a81) | Nov 19, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [228404e1d2](https://linux-hardware.org/?probe=228404e1d2) | Nov 18, 2020 |
| Dell          | Inspiron 7577               | [c09f7df61e](https://linux-hardware.org/?probe=c09f7df61e) | Nov 18, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [630b92e4d0](https://linux-hardware.org/?probe=630b92e4d0) | Nov 18, 2020 |
| HP            | EliteBook 2570p             | [3d005c24b6](https://linux-hardware.org/?probe=3d005c24b6) | Nov 17, 2020 |
| HP            | ProBook 450 G7              | [907aebb56a](https://linux-hardware.org/?probe=907aebb56a) | Nov 16, 2020 |
| HP            | EliteBook 745 G3            | [ec87278338](https://linux-hardware.org/?probe=ec87278338) | Nov 14, 2020 |
| HP            | EliteBook 850 G1            | [0b7205d523](https://linux-hardware.org/?probe=0b7205d523) | Nov 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [cee12c5d76](https://linux-hardware.org/?probe=cee12c5d76) | Nov 09, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b5aff9926a](https://linux-hardware.org/?probe=b5aff9926a) | Nov 09, 2020 |
| HP            | Pavilion g6                 | [a1e12ac11a](https://linux-hardware.org/?probe=a1e12ac11a) | Nov 07, 2020 |
| HP            | Pavilion g6                 | [c9fef7b025](https://linux-hardware.org/?probe=c9fef7b025) | Nov 07, 2020 |
| Dell          | Latitude 3590               | [6a285d94b7](https://linux-hardware.org/?probe=6a285d94b7) | Nov 02, 2020 |
| Dell          | Latitude E5570              | [ba5361df9e](https://linux-hardware.org/?probe=ba5361df9e) | Oct 29, 2020 |
| Dell          | G5 5587                     | [14789ef506](https://linux-hardware.org/?probe=14789ef506) | Oct 27, 2020 |
| Dell          | G5 5587                     | [414f6ca570](https://linux-hardware.org/?probe=414f6ca570) | Oct 27, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [3810f22dfc](https://linux-hardware.org/?probe=3810f22dfc) | Oct 23, 2020 |
| Dell          | Inspiron 5570               | [b7c7ae8b8b](https://linux-hardware.org/?probe=b7c7ae8b8b) | Oct 17, 2020 |
| HP            | Laptop 15-da1xxx            | [8e58300f1c](https://linux-hardware.org/?probe=8e58300f1c) | Oct 17, 2020 |
| HP            | ProBook 450 G7              | [e6c4e6ff27](https://linux-hardware.org/?probe=e6c4e6ff27) | Oct 15, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [59bbdc5626](https://linux-hardware.org/?probe=59bbdc5626) | Oct 14, 2020 |
| HP            | ProBook 450 G7              | [1722d6f45f](https://linux-hardware.org/?probe=1722d6f45f) | Oct 13, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [9a361154cb](https://linux-hardware.org/?probe=9a361154cb) | Oct 11, 2020 |
| HP            | EliteBook 840 G1            | [8d775d0fba](https://linux-hardware.org/?probe=8d775d0fba) | Oct 07, 2020 |
| HP            | EliteBook 840 G1            | [0f22425e10](https://linux-hardware.org/?probe=0f22425e10) | Oct 07, 2020 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [68e8da08fa](https://linux-hardware.org/?probe=68e8da08fa) | Oct 06, 2020 |
| HP            | ProBook 645 G1              | [6a95a69346](https://linux-hardware.org/?probe=6a95a69346) | Oct 04, 2020 |
| HP            | ProBook 645 G1              | [fc81852ffb](https://linux-hardware.org/?probe=fc81852ffb) | Oct 04, 2020 |
| ASUSTek       | G53SW                       | [cb9eb22047](https://linux-hardware.org/?probe=cb9eb22047) | Oct 02, 2020 |
| HP            | Laptop 15-da1xxx            | [6e17f92f25](https://linux-hardware.org/?probe=6e17f92f25) | Sep 30, 2020 |
| HP            | Laptop 15-da1xxx            | [839f278908](https://linux-hardware.org/?probe=839f278908) | Sep 30, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [e22e757c8c](https://linux-hardware.org/?probe=e22e757c8c) | Sep 23, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [105d229822](https://linux-hardware.org/?probe=105d229822) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [4d46200fc3](https://linux-hardware.org/?probe=4d46200fc3) | Sep 17, 2020 |
| ASUSTek       | X580VN                      | [cdd3998e5d](https://linux-hardware.org/?probe=cdd3998e5d) | Sep 12, 2020 |
| ASUSTek       | X580VN                      | [02de9a38ac](https://linux-hardware.org/?probe=02de9a38ac) | Sep 12, 2020 |
| HP            | ProBook 645 G1              | [0a888dfc64](https://linux-hardware.org/?probe=0a888dfc64) | Sep 12, 2020 |
| HP            | ZBook 15 G2                 | [29083832b1](https://linux-hardware.org/?probe=29083832b1) | Aug 22, 2020 |
| HP            | EliteBook 725 G2            | [f9f5c68624](https://linux-hardware.org/?probe=f9f5c68624) | Aug 22, 2020 |
| Dell          | Inspiron 3543               | [82f88ee681](https://linux-hardware.org/?probe=82f88ee681) | Aug 09, 2020 |
| Dell          | G5 5587                     | [ff9bde0012](https://linux-hardware.org/?probe=ff9bde0012) | Aug 06, 2020 |
| Dell          | G5 5587                     | [0f1718b1a5](https://linux-hardware.org/?probe=0f1718b1a5) | Aug 03, 2020 |
| HP            | EliteBook 745 G3            | [0107343e87](https://linux-hardware.org/?probe=0107343e87) | Aug 02, 2020 |
| Dell          | Latitude 7400               | [bb45d9a55f](https://linux-hardware.org/?probe=bb45d9a55f) | Jul 31, 2020 |
| Dell          | Inspiron 7577               | [3ed23397a7](https://linux-hardware.org/?probe=3ed23397a7) | Jul 30, 2020 |
| HP            | ZBook 15 G3                 | [5bd1b54d12](https://linux-hardware.org/?probe=5bd1b54d12) | Jul 28, 2020 |
| Dell          | Inspiron 3593               | [51ed8b0103](https://linux-hardware.org/?probe=51ed8b0103) | Jul 28, 2020 |
| Lenovo        | ThinkPad E420 1141D7G       | [f599cd92cd](https://linux-hardware.org/?probe=f599cd92cd) | Jul 27, 2020 |
| HP            | ZBook 15 G3                 | [81dd1b462b](https://linux-hardware.org/?probe=81dd1b462b) | Jul 26, 2020 |
| Lenovo        | ThinkPad E580 20KS0008AD    | [5e0f6c1dce](https://linux-hardware.org/?probe=5e0f6c1dce) | Jul 26, 2020 |
| Lenovo        | ThinkPad E420 1141D7G       | [f24dee8f72](https://linux-hardware.org/?probe=f24dee8f72) | Jul 24, 2020 |
| HP            | EliteBook 850 G5            | [56cf19c251](https://linux-hardware.org/?probe=56cf19c251) | Jul 18, 2020 |
| Dell          | Inspiron 5570               | [3d66bcb580](https://linux-hardware.org/?probe=3d66bcb580) | Jul 15, 2020 |
| HP            | EliteBook 840 G2            | [a2a8e9d267](https://linux-hardware.org/?probe=a2a8e9d267) | Jul 13, 2020 |
| Dell          | Inspiron 1525               | [754b2de717](https://linux-hardware.org/?probe=754b2de717) | Jun 27, 2020 |
| Lenovo        | G555 0873                   | [6a79c9f57b](https://linux-hardware.org/?probe=6a79c9f57b) | Jun 26, 2020 |
| Dell          | Inspiron 5559               | [3b7aa38697](https://linux-hardware.org/?probe=3b7aa38697) | Jun 24, 2020 |
| Dell          | Inspiron 5559               | [bf6cda0ab3](https://linux-hardware.org/?probe=bf6cda0ab3) | Jun 24, 2020 |
| Lenovo        | Y50-70 20378                | [f9ef75ee84](https://linux-hardware.org/?probe=f9ef75ee84) | Jun 23, 2020 |
| Dell          | Inspiron 5559               | [bd3ec8d031](https://linux-hardware.org/?probe=bd3ec8d031) | Jun 23, 2020 |
| Dell          | Inspiron 5559               | [bb181efab0](https://linux-hardware.org/?probe=bb181efab0) | Jun 22, 2020 |
| Dell          | Inspiron 5559               | [5cad704188](https://linux-hardware.org/?probe=5cad704188) | Jun 22, 2020 |
| Lenovo        | ThinkPad E480 20KN0082AD    | [f8743f8e7c](https://linux-hardware.org/?probe=f8743f8e7c) | Jun 03, 2020 |
| Acer          | Aspire 5253                 | [7951613e3c](https://linux-hardware.org/?probe=7951613e3c) | Jun 02, 2020 |
| Lenovo        | Z50-70 20354                | [474b3dc645](https://linux-hardware.org/?probe=474b3dc645) | Jun 01, 2020 |
| HP            | G60                         | [36393e3df7](https://linux-hardware.org/?probe=36393e3df7) | May 30, 2020 |
| Dell          | Latitude E5570              | [52fe4fa81d](https://linux-hardware.org/?probe=52fe4fa81d) | May 27, 2020 |
| Packard Be... | EasyNote TJ75               | [3e4f50b818](https://linux-hardware.org/?probe=3e4f50b818) | May 18, 2020 |
| Lenovo        | G555 0873                   | [80cd03a651](https://linux-hardware.org/?probe=80cd03a651) | May 17, 2020 |
| Lenovo        | G555 0873                   | [0c8aa224f6](https://linux-hardware.org/?probe=0c8aa224f6) | May 17, 2020 |
| Lenovo        | G50-70 20351                | [49f0886269](https://linux-hardware.org/?probe=49f0886269) | May 15, 2020 |
| Lenovo        | G50-70 20351                | [261ecd7cd3](https://linux-hardware.org/?probe=261ecd7cd3) | May 15, 2020 |
| HP            | Pavilion g4                 | [d72a853f70](https://linux-hardware.org/?probe=d72a853f70) | May 15, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | [567c197788](https://linux-hardware.org/?probe=567c197788) | May 14, 2020 |
| HP            | ProBook 450 G1              | [d2f086da96](https://linux-hardware.org/?probe=d2f086da96) | May 13, 2020 |
| Dell          | G3 3579                     | [1391477c00](https://linux-hardware.org/?probe=1391477c00) | May 11, 2020 |
| Dell          | G3 3779                     | [8adf43a503](https://linux-hardware.org/?probe=8adf43a503) | May 05, 2020 |
| Dell          | Inspiron 3521               | [bdb886a73d](https://linux-hardware.org/?probe=bdb886a73d) | May 05, 2020 |
| HP            | Pavilion g4                 | [8dec145194](https://linux-hardware.org/?probe=8dec145194) | May 05, 2020 |
| Toshiba       | Satellite L850-A894         | [4cff22692a](https://linux-hardware.org/?probe=4cff22692a) | Apr 26, 2020 |
| Toshiba       | Satellite L850-A894         | [c6bd4ae874](https://linux-hardware.org/?probe=c6bd4ae874) | Apr 26, 2020 |
| Dell          | Inspiron 5583               | [73ad84a03c](https://linux-hardware.org/?probe=73ad84a03c) | Apr 22, 2020 |
| Dell          | G5 5587                     | [56485e9db4](https://linux-hardware.org/?probe=56485e9db4) | Apr 22, 2020 |
| Toshiba       | Satellite A300              | [cb33489db5](https://linux-hardware.org/?probe=cb33489db5) | Apr 18, 2020 |
| Toshiba       | Satellite A300              | [47732faaf2](https://linux-hardware.org/?probe=47732faaf2) | Apr 18, 2020 |
| Toshiba       | Satellite A300              | [e39b380b81](https://linux-hardware.org/?probe=e39b380b81) | Apr 18, 2020 |
| Dell          | Inspiron 3543               | [165bdbdf8b](https://linux-hardware.org/?probe=165bdbdf8b) | Apr 09, 2020 |
| Acer          | Aspire E5-475G              | [a8a037650e](https://linux-hardware.org/?probe=a8a037650e) | Apr 05, 2020 |
| Toshiba       | Satellite C850D-B810        | [bfa7a5b4b3](https://linux-hardware.org/?probe=bfa7a5b4b3) | Apr 04, 2020 |
| Toshiba       | Satellite C850D-B810        | [d911f2bb34](https://linux-hardware.org/?probe=d911f2bb34) | Apr 04, 2020 |
| HP            | Pavilion dv6                | [5a16417e7b](https://linux-hardware.org/?probe=5a16417e7b) | Apr 04, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c6657af4bd](https://linux-hardware.org/?probe=c6657af4bd) | Mar 29, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [2645325565](https://linux-hardware.org/?probe=2645325565) | Mar 29, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [b90d909930](https://linux-hardware.org/?probe=b90d909930) | Mar 28, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [3aa7a0e126](https://linux-hardware.org/?probe=3aa7a0e126) | Mar 27, 2020 |
| HP            | Pavilion dv7                | [6f801c5209](https://linux-hardware.org/?probe=6f801c5209) | Mar 20, 2020 |
| Dell          | Inspiron 3593               | [f7f247e8c5](https://linux-hardware.org/?probe=f7f247e8c5) | Mar 19, 2020 |
| Lenovo        | ThinkPad SL410 0616A44      | [2c3f83610d](https://linux-hardware.org/?probe=2c3f83610d) | Mar 04, 2020 |
| Lenovo        | Y50-70 20378                | [d4389ea7a1](https://linux-hardware.org/?probe=d4389ea7a1) | Feb 23, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| Dell          | Inspiron N4050              | [9808803a9a](https://linux-hardware.org/?probe=9808803a9a) | Feb 07, 2020 |
| Dell          | Inspiron N4050              | [bd16699d67](https://linux-hardware.org/?probe=bd16699d67) | Feb 07, 2020 |
| Dell          | Inspiron 5570               | [101d794bd2](https://linux-hardware.org/?probe=101d794bd2) | Jan 30, 2020 |
| Dell          | Inspiron N5110              | [975cffd2a7](https://linux-hardware.org/?probe=975cffd2a7) | Jan 17, 2020 |
| Dell          | Inspiron N5110              | [31d025a5aa](https://linux-hardware.org/?probe=31d025a5aa) | Jan 16, 2020 |
| Dell          | Inspiron N5110              | [d08a0ed65d](https://linux-hardware.org/?probe=d08a0ed65d) | Jan 16, 2020 |
| Lenovo        | ThinkPad E590 20NB0002AD    | [0fc61e3795](https://linux-hardware.org/?probe=0fc61e3795) | Jan 13, 2020 |
| HP            | EliteBook 745 G4            | [99937a33e7](https://linux-hardware.org/?probe=99937a33e7) | Jan 05, 2020 |
| ASUSTek       | X540UA                      | [714b86d8a5](https://linux-hardware.org/?probe=714b86d8a5) | Dec 31, 2019 |
| Dell          | Inspiron 5570               | [92a06ce5da](https://linux-hardware.org/?probe=92a06ce5da) | Dec 31, 2019 |
| HP            | Pavilion dv7                | [56ba5d2a72](https://linux-hardware.org/?probe=56ba5d2a72) | Dec 20, 2019 |
| HP            | Pavilion dv7                | [9091bfdcb2](https://linux-hardware.org/?probe=9091bfdcb2) | Dec 13, 2019 |
| Dell          | Inspiron 15-3567            | [ddc251a8e0](https://linux-hardware.org/?probe=ddc251a8e0) | Dec 07, 2019 |
| Dell          | Inspiron 3542               | [38da710325](https://linux-hardware.org/?probe=38da710325) | Dec 01, 2019 |
| Lenovo        | IdeaPad Z510 20287          | [19294a1943](https://linux-hardware.org/?probe=19294a1943) | Nov 29, 2019 |
| Dell          | Inspiron 15-3567            | [ba36a0ae04](https://linux-hardware.org/?probe=ba36a0ae04) | Nov 27, 2019 |
| Dell          | Inspiron 15-3567            | [a93aff23bf](https://linux-hardware.org/?probe=a93aff23bf) | Nov 24, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8f75febf6c](https://linux-hardware.org/?probe=8f75febf6c) | Nov 23, 2019 |
| HP            | Pavilion dv7                | [0261873b10](https://linux-hardware.org/?probe=0261873b10) | Nov 22, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [3054eabefb](https://linux-hardware.org/?probe=3054eabefb) | Nov 20, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [62081db5d0](https://linux-hardware.org/?probe=62081db5d0) | Nov 20, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [6ed324d188](https://linux-hardware.org/?probe=6ed324d188) | Nov 20, 2019 |
| HP            | Pavilion dv7                | [ab5fc8d0ac](https://linux-hardware.org/?probe=ab5fc8d0ac) | Nov 15, 2019 |
| Dell          | Inspiron 3543               | [5d228450e9](https://linux-hardware.org/?probe=5d228450e9) | Nov 11, 2019 |
| HP            | Pavilion dv7                | [41305d675a](https://linux-hardware.org/?probe=41305d675a) | Nov 09, 2019 |
| HP            | Pavilion dv7                | [02fb246519](https://linux-hardware.org/?probe=02fb246519) | Nov 08, 2019 |
| HP            | Pavilion dv7                | [37ccba5300](https://linux-hardware.org/?probe=37ccba5300) | Nov 08, 2019 |
| HP            | Pavilion dv7                | [a73d7baeb5](https://linux-hardware.org/?probe=a73d7baeb5) | Nov 08, 2019 |
| HP            | Pavilion dv7                | [118f3ee0a0](https://linux-hardware.org/?probe=118f3ee0a0) | Nov 08, 2019 |
| HP            | Pavilion dv7                | [86daa5b939](https://linux-hardware.org/?probe=86daa5b939) | Nov 08, 2019 |
| HP            | Pavilion dv7                | [adcc1828a6](https://linux-hardware.org/?probe=adcc1828a6) | Nov 08, 2019 |
| HP            | Pavilion dv7                | [6031485dd2](https://linux-hardware.org/?probe=6031485dd2) | Nov 08, 2019 |
| Lenovo        | ThinkPad T420 4178CXG       | [70105ff0ab](https://linux-hardware.org/?probe=70105ff0ab) | Nov 03, 2019 |
| Lenovo        | ThinkPad L460 20FVS0ER00    | [713a72e731](https://linux-hardware.org/?probe=713a72e731) | Oct 31, 2019 |
| HP            | ProBook 450 G4              | [e11bd3882e](https://linux-hardware.org/?probe=e11bd3882e) | Oct 22, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1bbc7dacba](https://linux-hardware.org/?probe=1bbc7dacba) | Oct 19, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [677874b570](https://linux-hardware.org/?probe=677874b570) | Oct 18, 2019 |
| HP            | ProBook 450 G2              | [d8532c559a](https://linux-hardware.org/?probe=d8532c559a) | Sep 18, 2019 |
| Dell          | Inspiron N5010              | [fb490db7bf](https://linux-hardware.org/?probe=fb490db7bf) | Sep 09, 2019 |
| Dell          | Inspiron N5010              | [993460ba08](https://linux-hardware.org/?probe=993460ba08) | Sep 09, 2019 |
| MSI           | GL62 7QF                    | [4d0dbc5874](https://linux-hardware.org/?probe=4d0dbc5874) | Aug 30, 2019 |
| MSI           | GL62 7QF                    | [e508053ff2](https://linux-hardware.org/?probe=e508053ff2) | Aug 29, 2019 |
| Dell          | G3 3579                     | [ddcae43a95](https://linux-hardware.org/?probe=ddcae43a95) | Aug 24, 2019 |
| Dell          | Latitude E6440              | [c9fc484b61](https://linux-hardware.org/?probe=c9fc484b61) | Aug 20, 2019 |
| Dell          | Latitude E6440              | [f153be7930](https://linux-hardware.org/?probe=f153be7930) | Aug 20, 2019 |
| HP            | Pavilion dv7                | [d2006e7a87](https://linux-hardware.org/?probe=d2006e7a87) | Jul 27, 2019 |
| Toshiba       | Satellite C850-B341         | [acd80fad4b](https://linux-hardware.org/?probe=acd80fad4b) | Jul 20, 2019 |
| Acer          | Aspire A315-21              | [ea1580c609](https://linux-hardware.org/?probe=ea1580c609) | Jul 01, 2019 |
| Dell          | Inspiron 5559               | [4cbf20a7cf](https://linux-hardware.org/?probe=4cbf20a7cf) | Jun 18, 2019 |
| Lenovo        | ThinkPad T410 2522N18       | [9ab11256e2](https://linux-hardware.org/?probe=9ab11256e2) | Jun 16, 2019 |
| Acer          | Aspire E5-576G              | [119e4e5705](https://linux-hardware.org/?probe=119e4e5705) | Jun 06, 2019 |
| Lenovo        | Yoga 300-11IBY 80M0         | [0d944086c2](https://linux-hardware.org/?probe=0d944086c2) | Jun 04, 2019 |
| HP            | Laptop 15-bs1xx             | [47b56cee05](https://linux-hardware.org/?probe=47b56cee05) | May 25, 2019 |
| HP            | EliteBook 840 G1            | [fb72c7a17e](https://linux-hardware.org/?probe=fb72c7a17e) | May 22, 2019 |
| HP            | EliteBook 840 G1            | [8cc7613eb4](https://linux-hardware.org/?probe=8cc7613eb4) | May 22, 2019 |
| Dell          | Inspiron 3576               | [e86a5c4340](https://linux-hardware.org/?probe=e86a5c4340) | Apr 12, 2019 |
| HP            | ProBook 450 G2              | [ed27c8b4b2](https://linux-hardware.org/?probe=ed27c8b4b2) | Feb 23, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d1e0440b23](https://linux-hardware.org/?probe=d1e0440b23) | Jan 30, 2019 |
| Dell          | Inspiron 7520               | [4362c41db3](https://linux-hardware.org/?probe=4362c41db3) | Nov 17, 2018 |
| Dell          | Inspiron 7520               | [461541bb3a](https://linux-hardware.org/?probe=461541bb3a) | Nov 17, 2018 |
| Dell          | Latitude E5470              | [f54e62ab63](https://linux-hardware.org/?probe=f54e62ab63) | Nov 11, 2018 |
| Dell          | Latitude E5470              | [915fd0001b](https://linux-hardware.org/?probe=915fd0001b) | Nov 11, 2018 |
| Dell          | Latitude E5470              | [496335b114](https://linux-hardware.org/?probe=496335b114) | Nov 10, 2018 |
| Dell          | Latitude E5470              | [3c869c46e5](https://linux-hardware.org/?probe=3c869c46e5) | Nov 08, 2018 |
| Toshiba       | Satellite L50-A661          | [fad34d33ee](https://linux-hardware.org/?probe=fad34d33ee) | Apr 22, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Ubuntu 20.04          | 54        | 24.55%  |
| Ubuntu 18.04          | 34        | 15.45%  |
| Ubuntu 19.10          | 9         | 4.09%   |
| Ubuntu 20.10          | 7         | 3.18%   |
| Zorin 15              | 6         | 2.73%   |
| Pop!_OS 20.10         | 5         | 2.27%   |
| Ubuntu 21.10          | 4         | 1.82%   |
| Linux Mint 19.3       | 4         | 1.82%   |
| Fedora 34             | 4         | 1.82%   |
| ArcoLinux Rolling     | 4         | 1.82%   |
| Arch                  | 4         | 1.82%   |
| Ubuntu 21.04          | 3         | 1.36%   |
| Pop!_OS 20.04         | 3         | 1.36%   |
| OpenMandriva 4.3      | 3         | 1.36%   |
| Manjaro               | 3         | 1.36%   |
| Linux Mint 20.1       | 3         | 1.36%   |
| Kubuntu 20.04         | 3         | 1.36%   |
| Fedora 35             | 3         | 1.36%   |
| Fedora 33             | 3         | 1.36%   |
| Zorin 16              | 2         | 0.91%   |
| Ubuntu 22.04          | 2         | 0.91%   |
| Ubuntu 19.04          | 2         | 0.91%   |
| Ubuntu 18.10          | 2         | 0.91%   |
| Ubuntu 16.04          | 2         | 0.91%   |
| Pop!_OS 21.04         | 2         | 0.91%   |
| OpenMandriva 4.2      | 2         | 0.91%   |
| Linux Mint 19         | 2         | 0.91%   |
| KDE neon 20.04        | 2         | 0.91%   |
| Kali 2022.1           | 2         | 0.91%   |
| Kali 2021.1           | 2         | 0.91%   |
| Fedora 32             | 2         | 0.91%   |
| Ubuntu Budgie 19.10   | 1         | 0.45%   |
| ROSA R9               | 1         | 0.45%   |
| ROSA R11.1            | 1         | 0.45%   |
| ROSA 12.2             | 1         | 0.45%   |
| Pop!_OS 22.04         | 1         | 0.45%   |
| Manjaro 21.2.6        | 1         | 0.45%   |
| Manjaro 21.2.5        | 1         | 0.45%   |
| Manjaro 21.2.1        | 1         | 0.45%   |
| Manjaro 21.2.0        | 1         | 0.45%   |
| Manjaro 20.2.1        | 1         | 0.45%   |
| Manjaro 20.1.1        | 1         | 0.45%   |
| Manjaro 18.1.5        | 1         | 0.45%   |
| Lubuntu 20.10         | 1         | 0.45%   |
| LMDE 4                | 1         | 0.45%   |
| Linux Mint 20.3       | 1         | 0.45%   |
| Linux Mint 20.2       | 1         | 0.45%   |
| Linux Mint 20         | 1         | 0.45%   |
| Kali 2021.3           | 1         | 0.45%   |
| Kali 2019.2           | 1         | 0.45%   |
| Fedora 31             | 1         | 0.45%   |
| Endless 4.0.3         | 1         | 0.45%   |
| Endless 4.0.0         | 1         | 0.45%   |
| Endless 3.8.7         | 1         | 0.45%   |
| Endless 3.7.5         | 1         | 0.45%   |
| Endless 3.6.0         | 1         | 0.45%   |
| Endless 3.5.8         | 1         | 0.45%   |
| Endless 3.4.2-nexthw1 | 1         | 0.45%   |
| EndeavourOS Rolling   | 1         | 0.45%   |
| Elementary 5.1.2      | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 116       | 54.21%  |
| Fedora        | 13        | 6.07%   |
| Linux Mint    | 12        | 5.61%   |
| Pop!_OS       | 10        | 4.67%   |
| Manjaro       | 9         | 4.21%   |
| Zorin         | 8         | 3.74%   |
| Endless       | 7         | 3.27%   |
| Kali          | 6         | 2.8%    |
| OpenMandriva  | 5         | 2.34%   |
| ArcoLinux     | 4         | 1.87%   |
| Arch          | 4         | 1.87%   |
| ROSA          | 3         | 1.4%    |
| Kubuntu       | 3         | 1.4%    |
| KDE neon      | 2         | 0.93%   |
| Clear Linux   | 2         | 0.93%   |
| Ubuntu Budgie | 1         | 0.47%   |
| Lubuntu       | 1         | 0.47%   |
| LMDE          | 1         | 0.47%   |
| EndeavourOS   | 1         | 0.47%   |
| Elementary    | 1         | 0.47%   |
| Debian        | 1         | 0.47%   |
| CentOS        | 1         | 0.47%   |
| BlackPanther  | 1         | 0.47%   |
| ALT Linux     | 1         | 0.47%   |
| Alpine        | 1         | 0.47%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.4.0-42-generic            | 13        | 5.51%   |
| 5.4.0-58-generic            | 6         | 2.54%   |
| 5.8.0-7630-generic          | 4         | 1.69%   |
| 5.8.0-48-generic            | 4         | 1.69%   |
| 5.4.0-48-generic            | 4         | 1.69%   |
| 5.4.0-29-generic            | 4         | 1.69%   |
| 5.0.0-32-generic            | 4         | 1.69%   |
| 5.8.0-43-generic            | 3         | 1.27%   |
| 5.8.0-41-generic            | 3         | 1.27%   |
| 5.4.0-56-generic            | 3         | 1.27%   |
| 5.3.0-51-generic            | 3         | 1.27%   |
| 5.3.0-18-generic            | 3         | 1.27%   |
| 5.13.0-30-generic           | 3         | 1.27%   |
| 5.11.0-38-generic           | 3         | 1.27%   |
| 5.11.0-37-generic           | 3         | 1.27%   |
| 5.4.0-80-generic            | 2         | 0.85%   |
| 5.4.0-59-generic            | 2         | 0.85%   |
| 5.4.0-54-generic            | 2         | 0.85%   |
| 5.4.0-53-generic            | 2         | 0.85%   |
| 5.4.0-52-generic            | 2         | 0.85%   |
| 5.4.0-40-generic            | 2         | 0.85%   |
| 5.4.0-100-generic           | 2         | 0.85%   |
| 5.3.0-46-generic            | 2         | 0.85%   |
| 5.3.0-45-generic            | 2         | 0.85%   |
| 5.3.0-42-generic            | 2         | 0.85%   |
| 5.3.0-26-generic            | 2         | 0.85%   |
| 5.3.0-23-generic            | 2         | 0.85%   |
| 5.16.7-desktop-1omv4003     | 2         | 0.85%   |
| 5.11.0-35-generic           | 2         | 0.85%   |
| 5.10.19-200.fc33.x86_64     | 2         | 0.85%   |
| 5.10.14-desktop-1omv4002    | 2         | 0.85%   |
| 5.0.0-37-generic            | 2         | 0.85%   |
| 5.0.0-25-generic            | 2         | 0.85%   |
| 4.18.0-15-generic           | 2         | 0.85%   |
| 4.15.0-54-generic           | 2         | 0.85%   |
| 4.15.0-20-generic           | 2         | 0.85%   |
| 5.9.1-arch1-1               | 1         | 0.42%   |
| 5.8.7-200.fc32.x86_64       | 1         | 0.42%   |
| 5.8.15-301.fc33.x86_64      | 1         | 0.42%   |
| 5.8.11-1-MANJARO            | 1         | 0.42%   |
| 5.8.10-arch1-1              | 1         | 0.42%   |
| 5.8.0-45-generic            | 1         | 0.42%   |
| 5.8.0-44-generic            | 1         | 0.42%   |
| 5.8.0-40-generic            | 1         | 0.42%   |
| 5.8.0-38-generic            | 1         | 0.42%   |
| 5.8.0-36-generic            | 1         | 0.42%   |
| 5.8.0-31-generic            | 1         | 0.42%   |
| 5.8.0-28-generic            | 1         | 0.42%   |
| 5.8.0-26-generic            | 1         | 0.42%   |
| 5.8.0-25-generic            | 1         | 0.42%   |
| 5.8.0-23-generic            | 1         | 0.42%   |
| 5.7.1-050701-generic        | 1         | 0.42%   |
| 5.6.8-1-MANJARO             | 1         | 0.42%   |
| 5.6.15-300.fc32.x86_64      | 1         | 0.42%   |
| 5.5.13-arch2-1              | 1         | 0.42%   |
| 5.4.83-generic-2rosa-x86_64 | 1         | 0.42%   |
| 5.4.70-1-lts                | 1         | 0.42%   |
| 5.4.67-1-MANJARO            | 1         | 0.42%   |
| 5.4.13-3-MANJARO            | 1         | 0.42%   |
| 5.4.101-1-MANJARO           | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 54        | 23.89%  |
| 5.3.0   | 24        | 10.62%  |
| 5.8.0   | 23        | 10.18%  |
| 4.15.0  | 16        | 7.08%   |
| 5.0.0   | 14        | 6.19%   |
| 5.11.0  | 12        | 5.31%   |
| 5.13.0  | 11        | 4.87%   |
| 4.18.0  | 7         | 3.1%    |
| 5.10.0  | 4         | 1.77%   |
| 5.15.0  | 3         | 1.33%   |
| 5.17.1  | 2         | 0.88%   |
| 5.16.7  | 2         | 0.88%   |
| 5.10.19 | 2         | 0.88%   |
| 5.10.14 | 2         | 0.88%   |
| 4.19.0  | 2         | 0.88%   |
| 5.9.1   | 1         | 0.44%   |
| 5.8.7   | 1         | 0.44%   |
| 5.8.15  | 1         | 0.44%   |
| 5.8.11  | 1         | 0.44%   |
| 5.8.10  | 1         | 0.44%   |
| 5.7.1   | 1         | 0.44%   |
| 5.6.8   | 1         | 0.44%   |
| 5.6.15  | 1         | 0.44%   |
| 5.5.13  | 1         | 0.44%   |
| 5.4.83  | 1         | 0.44%   |
| 5.4.70  | 1         | 0.44%   |
| 5.4.67  | 1         | 0.44%   |
| 5.4.13  | 1         | 0.44%   |
| 5.4.101 | 1         | 0.44%   |
| 5.3.8   | 1         | 0.44%   |
| 5.3.7   | 1         | 0.44%   |
| 5.17.5  | 1         | 0.44%   |
| 5.17.4  | 1         | 0.44%   |
| 5.16.20 | 1         | 0.44%   |
| 5.16.19 | 1         | 0.44%   |
| 5.16.13 | 1         | 0.44%   |
| 5.16.11 | 1         | 0.44%   |
| 5.16.1  | 1         | 0.44%   |
| 5.16.0  | 1         | 0.44%   |
| 5.15.7  | 1         | 0.44%   |
| 5.15.5  | 1         | 0.44%   |
| 5.15.28 | 1         | 0.44%   |
| 5.15.25 | 1         | 0.44%   |
| 5.15.12 | 1         | 0.44%   |
| 5.15.10 | 1         | 0.44%   |
| 5.14.9  | 1         | 0.44%   |
| 5.14.0  | 1         | 0.44%   |
| 5.13.19 | 1         | 0.44%   |
| 5.12.8  | 1         | 0.44%   |
| 5.12.13 | 1         | 0.44%   |
| 5.12.10 | 1         | 0.44%   |
| 5.11.12 | 1         | 0.44%   |
| 5.11.11 | 1         | 0.44%   |
| 5.10.93 | 1         | 0.44%   |
| 5.10.88 | 1         | 0.44%   |
| 5.10.74 | 1         | 0.44%   |
| 5.10.56 | 1         | 0.44%   |
| 5.10.36 | 1         | 0.44%   |
| 5.10.29 | 1         | 0.44%   |
| 5.10.16 | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 59        | 26.46%  |
| 5.8     | 26        | 11.66%  |
| 5.3     | 26        | 11.66%  |
| 4.15    | 16        | 7.17%   |
| 5.11    | 14        | 6.28%   |
| 5.10    | 14        | 6.28%   |
| 5.0     | 14        | 6.28%   |
| 5.13    | 12        | 5.38%   |
| 5.16    | 8         | 3.59%   |
| 5.15    | 8         | 3.59%   |
| 4.18    | 8         | 3.59%   |
| 5.17    | 4         | 1.79%   |
| 5.12    | 3         | 1.35%   |
| 5.6     | 2         | 0.9%    |
| 5.14    | 2         | 0.9%    |
| 4.19    | 2         | 0.9%    |
| 5.9     | 1         | 0.45%   |
| 5.7     | 1         | 0.45%   |
| 5.5     | 1         | 0.45%   |
| 4.9     | 1         | 0.45%   |
| 4.16    | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 207       | 99.04%  |
| i686   | 2         | 0.96%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 131       | 61.5%   |
| Unknown    | 34        | 15.96%  |
| XFCE       | 15        | 7.04%   |
| KDE5       | 14        | 6.57%   |
| X-Cinnamon | 8         | 3.76%   |
| MATE       | 2         | 0.94%   |
| KDE4       | 2         | 0.94%   |
| Unity      | 1         | 0.47%   |
| qtile      | 1         | 0.47%   |
| LXQt       | 1         | 0.47%   |
| KDE        | 1         | 0.47%   |
| i3         | 1         | 0.47%   |
| Cinnamon   | 1         | 0.47%   |
| Budgie     | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 171       | 79.17%  |
| Unknown | 22        | 10.19%  |
| Wayland | 20        | 9.26%   |
| Tty     | 3         | 1.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 145       | 68.72%  |
| GDM     | 29        | 13.74%  |
| SDDM    | 13        | 6.16%   |
| LightDM | 8         | 3.79%   |
| TDM     | 7         | 3.32%   |
| GDM3    | 7         | 3.32%   |
| KDM     | 2         | 0.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 167       | 78.4%   |
| Unknown | 31        | 14.55%  |
| en_GB   | 7         | 3.29%   |
| ar_EG   | 3         | 1.41%   |
| ru_RU   | 2         | 0.94%   |
| C       | 2         | 0.94%   |
| de_DE   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 120       | 56.6%   |
| EFI  | 92        | 43.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 181       | 85.78%  |
| Unknown | 11        | 5.21%   |
| Btrfs   | 8         | 3.79%   |
| Overlay | 7         | 3.32%   |
| Xfs     | 2         | 0.95%   |
| Ext3    | 2         | 0.95%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 150       | 71.77%  |
| GPT     | 43        | 20.57%  |
| MBR     | 16        | 7.66%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 188       | 88.26%  |
| Yes       | 25        | 11.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 114       | 53.52%  |
| Yes       | 99        | 46.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 65        | 31.1%   |
| Dell                        | 59        | 28.23%  |
| Lenovo                      | 47        | 22.49%  |
| ASUSTek Computer            | 11        | 5.26%   |
| Toshiba                     | 6         | 2.87%   |
| Acer                        | 5         | 2.39%   |
| Sony                        | 2         | 0.96%   |
| Packard Bell                | 2         | 0.96%   |
| MSI                         | 2         | 0.96%   |
| Hampoo                      | 2         | 0.96%   |
| Fujitsu                     | 2         | 0.96%   |
| TECNO                       | 1         | 0.48%   |
| Samsung Electronics         | 1         | 0.48%   |
| I-Life Digital Technologies | 1         | 0.48%   |
| Fujitsu Siemens             | 1         | 0.48%   |
| Apple                       | 1         | 0.48%   |
| Alienware                   | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Dell Inspiron 5570                      | 5         | 2.39%   |
| Lenovo IdeaPad 520-15IKB 81BF           | 4         | 1.91%   |
| HP ProBook 450 G7                       | 4         | 1.91%   |
| Dell Inspiron 7577                      | 4         | 1.91%   |
| Dell G3 3579                            | 4         | 1.91%   |
| HP Pavilion dv6                         | 3         | 1.44%   |
| HP Laptop 15-da1xxx                     | 3         | 1.44%   |
| Dell G5 5587                            | 3         | 1.44%   |
| Lenovo Y50-70 20378                     | 2         | 0.96%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK   | 2         | 0.96%   |
| Lenovo IdeaPad 310-15IKB 80TV           | 2         | 0.96%   |
| Lenovo G555 0873                        | 2         | 0.96%   |
| HP ZBook 15 G2                          | 2         | 0.96%   |
| HP ProBook 645 G1                       | 2         | 0.96%   |
| HP ProBook 450 G2                       | 2         | 0.96%   |
| HP Pavilion g6                          | 2         | 0.96%   |
| HP Pavilion g4                          | 2         | 0.96%   |
| HP Pavilion dv7                         | 2         | 0.96%   |
| HP Pavilion 15                          | 2         | 0.96%   |
| HP Notebook                             | 2         | 0.96%   |
| HP Laptop 15-bs0xx                      | 2         | 0.96%   |
| HP EliteBook 840 G1                     | 2         | 0.96%   |
| HP EliteBook 745 G3                     | 2         | 0.96%   |
| HP 15                                   | 2         | 0.96%   |
| Hampoo Cherry Trail CR                  | 2         | 0.96%   |
| Dell Latitude E5570                     | 2         | 0.96%   |
| Dell Inspiron N5110                     | 2         | 0.96%   |
| Dell Inspiron N5010                     | 2         | 0.96%   |
| Dell Inspiron N4050                     | 2         | 0.96%   |
| Dell Inspiron 5559                      | 2         | 0.96%   |
| Dell Inspiron 3593                      | 2         | 0.96%   |
| Dell Inspiron 3543                      | 2         | 0.96%   |
| Dell Inspiron 3521                      | 2         | 0.96%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR    | 2         | 0.96%   |
| Toshiba Satellite L850-A894             | 1         | 0.48%   |
| Toshiba Satellite L50-A661              | 1         | 0.48%   |
| Toshiba Satellite C850D-B810            | 1         | 0.48%   |
| Toshiba Satellite C850-B341             | 1         | 0.48%   |
| Toshiba Satellite C660                  | 1         | 0.48%   |
| Toshiba Satellite A300                  | 1         | 0.48%   |
| TECNO WinPad 10A                        | 1         | 0.48%   |
| Sony SVT1121B2EW                        | 1         | 0.48%   |
| Sony SVF15328CXB                        | 1         | 0.48%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.48%   |
| Packard Bell EasyNote TJ75              | 1         | 0.48%   |
| Packard Bell EasyNote LX                | 1         | 0.48%   |
| MSI GS65 Stealth Thin 8RE               | 1         | 0.48%   |
| MSI GL62 7QF                            | 1         | 0.48%   |
| Lenovo Z50-70 20354                     | 1         | 0.48%   |
| Lenovo Yoga 300-11IBY 80M0              | 1         | 0.48%   |
| Lenovo Yoga 3 Pro-1370 80HE             | 1         | 0.48%   |
| Lenovo ThinkPad X250 20CM003WMS         | 1         | 0.48%   |
| Lenovo ThinkPad T580 20LAS09100         | 1         | 0.48%   |
| Lenovo ThinkPad T420 4178CXG            | 1         | 0.48%   |
| Lenovo ThinkPad T410 2522N18            | 1         | 0.48%   |
| Lenovo ThinkPad SL410 0616A44           | 1         | 0.48%   |
| Lenovo ThinkPad S1 Yoga 12 20DK001YUK   | 1         | 0.48%   |
| Lenovo ThinkPad L460 20FVS0ER00         | 1         | 0.48%   |
| Lenovo ThinkPad E590 20NB0002AD         | 1         | 0.48%   |
| Lenovo ThinkPad E580 20KS0008AD         | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 35        | 16.75%  |
| Lenovo IdeaPad        | 18        | 8.61%   |
| Lenovo ThinkPad       | 14        | 6.7%    |
| HP ProBook            | 14        | 6.7%    |
| HP Pavilion           | 14        | 6.7%    |
| HP EliteBook          | 12        | 5.74%   |
| Dell Latitude         | 12        | 5.74%   |
| HP Laptop             | 7         | 3.35%   |
| Dell G3               | 7         | 3.35%   |
| Toshiba Satellite     | 6         | 2.87%   |
| Acer Aspire           | 5         | 2.39%   |
| HP ZBook              | 4         | 1.91%   |
| ASUS VivoBook         | 4         | 1.91%   |
| Lenovo Legion         | 3         | 1.44%   |
| Dell G5               | 3         | 1.44%   |
| Packard Bell EasyNote | 2         | 0.96%   |
| Lenovo Yoga           | 2         | 0.96%   |
| Lenovo Y50-70         | 2         | 0.96%   |
| Lenovo G555           | 2         | 0.96%   |
| HP Notebook           | 2         | 0.96%   |
| HP Compaq             | 2         | 0.96%   |
| HP 250                | 2         | 0.96%   |
| HP 15                 | 2         | 0.96%   |
| Hampoo Cherry         | 2         | 0.96%   |
| TECNO WinPad          | 1         | 0.48%   |
| Sony SVT1121B2EW      | 1         | 0.48%   |
| Sony SVF15328CXB      | 1         | 0.48%   |
| Samsung 300E5EV       | 1         | 0.48%   |
| MSI GS65              | 1         | 0.48%   |
| MSI GL62              | 1         | 0.48%   |
| Lenovo Z50-70         | 1         | 0.48%   |
| Lenovo G510           | 1         | 0.48%   |
| Lenovo G50-80         | 1         | 0.48%   |
| Lenovo G50-70         | 1         | 0.48%   |
| Lenovo Flex           | 1         | 0.48%   |
| Lenovo AILZx          | 1         | 0.48%   |
| I-Life Digital ZED    | 1         | 0.48%   |
| HP Pro                | 1         | 0.48%   |
| HP G62                | 1         | 0.48%   |
| HP G60                | 1         | 0.48%   |
| HP ENVY               | 1         | 0.48%   |
| HP 255                | 1         | 0.48%   |
| Fujitsu Siemens AMILO | 1         | 0.48%   |
| Fujitsu LIFEBOOK      | 1         | 0.48%   |
| Fujitsu FMVA06004     | 1         | 0.48%   |
| Dell Venue            | 1         | 0.48%   |
| Dell G15              | 1         | 0.48%   |
| ASUS X580VN           | 1         | 0.48%   |
| ASUS X540UA           | 1         | 0.48%   |
| ASUS X455LD           | 1         | 0.48%   |
| ASUS X200MA           | 1         | 0.48%   |
| ASUS N501JW           | 1         | 0.48%   |
| ASUS G53SW            | 1         | 0.48%   |
| ASUS ASUS             | 1         | 0.48%   |
| Apple MacBookPro5     | 1         | 0.48%   |
| Alienware 17          | 1         | 0.48%   |
| Unknown               | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 31        | 14.83%  |
| 2017 | 25        | 11.96%  |
| 2013 | 21        | 10.05%  |
| 2019 | 20        | 9.57%   |
| 2016 | 19        | 9.09%   |
| 2014 | 19        | 9.09%   |
| 2011 | 15        | 7.18%   |
| 2015 | 14        | 6.7%    |
| 2012 | 10        | 4.78%   |
| 2010 | 10        | 4.78%   |
| 2008 | 10        | 4.78%   |
| 2020 | 8         | 3.83%   |
| 2009 | 4         | 1.91%   |
| 2007 | 2         | 0.96%   |
| 2021 | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 209       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 200       | 95.69%  |
| Enabled  | 9         | 4.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 209       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 65        | 30.95%  |
| 16.01-24.0 | 56        | 26.67%  |
| 3.01-4.0   | 46        | 21.9%   |
| 8.01-16.0  | 26        | 12.38%  |
| 2.01-3.0   | 7         | 3.33%   |
| 1.01-2.0   | 7         | 3.33%   |
| 32.01-64.0 | 2         | 0.95%   |
| 24.01-32.0 | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 75        | 32.89%  |
| 1.01-2.0  | 75        | 32.89%  |
| 4.01-8.0  | 36        | 15.79%  |
| 3.01-4.0  | 33        | 14.47%  |
| 8.01-16.0 | 4         | 1.75%   |
| 0.51-1.0  | 4         | 1.75%   |
| 0.01-0.5  | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 123       | 56.94%  |
| 2      | 86        | 39.81%  |
| 3      | 7         | 3.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 113       | 53.81%  |
| Yes       | 97        | 46.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 91.87%  |
| No        | 17        | 8.13%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 98.56%  |
| No        | 3         | 1.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 170       | 80.19%  |
| No        | 42        | 19.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Egypt   | 209       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Cairo               | 125       | 55.8%   |
| Alexandria          | 24        | 10.71%  |
| Giza                | 15        | 6.7%    |
| Al Mansurah         | 10        | 4.46%   |
| Tanta               | 5         | 2.23%   |
| Suez                | 4         | 1.79%   |
| Assiut              | 4         | 1.79%   |
| Minya               | 3         | 1.34%   |
| Madinat an Nasr     | 3         | 1.34%   |
| Damanhur            | 3         | 1.34%   |
| Zagazig             | 2         | 0.89%   |
| Maadi Cornish       | 2         | 0.89%   |
| Hurghada            | 2         | 0.89%   |
| Awsim               | 2         | 0.89%   |
| Aswan               | 2         | 0.89%   |
| The Industrial Zone | 1         | 0.45%   |
| Rosetta             | 1         | 0.45%   |
| Port Said           | 1         | 0.45%   |
| New Cairo           | 1         | 0.45%   |
| Munuf               | 1         | 0.45%   |
| Monufia             | 1         | 0.45%   |
| Mashtul as Suq      | 1         | 0.45%   |
| Madinat as Sadat    | 1         | 0.45%   |
| El Shorouk          | 1         | 0.45%   |
| Edfu                | 1         | 0.45%   |
| Dokki               | 1         | 0.45%   |
| Diyarb Najm         | 1         | 0.45%   |
| Disuq               | 1         | 0.45%   |
| Damietta            | 1         | 0.45%   |
| Bulaq ad Dakrur     | 1         | 0.45%   |
| Banha               | 1         | 0.45%   |
| Badr                | 1         | 0.45%   |
| Al Matariyah        | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 65        | 73     | 22.49%  |
| WDC                       | 56        | 65     | 19.38%  |
| Toshiba                   | 45        | 57     | 15.57%  |
| Samsung Electronics       | 24        | 30     | 8.3%    |
| Kingston                  | 14        | 16     | 4.84%   |
| Unknown                   | 13        | 17     | 4.5%    |
| Crucial                   | 11        | 12     | 3.81%   |
| SK Hynix                  | 9         | 9      | 3.11%   |
| Hitachi                   | 8         | 11     | 2.77%   |
| SanDisk                   | 7         | 8      | 2.42%   |
| Micron Technology         | 5         | 5      | 1.73%   |
| HS-SSD-C100               | 5         | 6      | 1.73%   |
| HGST                      | 4         | 4      | 1.38%   |
| LITEONIT                  | 3         | 4      | 1.04%   |
| LITEON                    | 3         | 5      | 1.04%   |
| Intel                     | 3         | 3      | 1.04%   |
| TwinMOS                   | 2         | 2      | 0.69%   |
| Transcend                 | 2         | 2      | 0.69%   |
| UMIS                      | 1         | 1      | 0.35%   |
| Team                      | 1         | 1      | 0.35%   |
| Silicon Motion            | 1         | 1      | 0.35%   |
| Micron/Crucial Technology | 1         | 1      | 0.35%   |
| Lexar                     | 1         | 1      | 0.35%   |
| KIOXIA                    | 1         | 1      | 0.35%   |
| KingSpec                  | 1         | 1      | 0.35%   |
| HUAWEI                    | 1         | 1      | 0.35%   |
| ADATA Technology          | 1         | 1      | 0.35%   |
| A-DATA Technology         | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 28        | 9.52%   |
| Toshiba MQ04ABF100 1TB                   | 11        | 3.74%   |
| Seagate ST2000LM007-1R8174 2TB           | 9         | 3.06%   |
| Toshiba MQ01ABD100 1TB                   | 6         | 2.04%   |
| Samsung NVMe SSD Drive 256GB             | 5         | 1.7%    |
| Kingston SA400S37480G 480GB SSD          | 5         | 1.7%    |
| Kingston SA400S37240G 240GB SSD          | 5         | 1.7%    |
| WDC WD10SPZX-60Z10T0 1TB                 | 4         | 1.36%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 4         | 1.36%   |
| Crucial CT480BX500SSD1 480GB             | 4         | 1.36%   |
| WDC WD10SPZX-24Z10 1TB                   | 3         | 1.02%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 3         | 1.02%   |
| Unknown SD/MMC/MS PRO 128GB              | 3         | 1.02%   |
| Toshiba NVMe SSD Drive 256GB             | 3         | 1.02%   |
| Toshiba MQ01ABF050 500GB                 | 3         | 1.02%   |
| Toshiba MK3276GSX 320GB                  | 3         | 1.02%   |
| Seagate ST750LM022 HN-M750MBB 752GB      | 3         | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 3         | 1.02%   |
| Hitachi HTS547575A9E384 752GB            | 3         | 1.02%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 2         | 0.68%   |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 2         | 0.68%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 2         | 0.68%   |
| WDC WD5000LPCX-24C6HT0 500GB             | 2         | 0.68%   |
| WDC WD3200BPVT-75JJ5T0 320GB             | 2         | 0.68%   |
| WDC WD1600BEVT-24A23T0 160GB             | 2         | 0.68%   |
| WDC WD10SPZX-75Z10T1 1TB                 | 2         | 0.68%   |
| WDC WD10SPZX-21Z10T0 1TB                 | 2         | 0.68%   |
| WDC WD10SPZX-00Z10T0 1TB                 | 2         | 0.68%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 2         | 0.68%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB     | 2         | 0.68%   |
| Unknown MMC Card  64GB                   | 2         | 0.68%   |
| Unknown MMC Card  32GB                   | 2         | 0.68%   |
| TwinMOS SSD 128GB                        | 2         | 0.68%   |
| Toshiba MQ01ACF032 320GB                 | 2         | 0.68%   |
| Toshiba MK3275GSX 320GB                  | 2         | 0.68%   |
| Toshiba MK3256GSY 320GB                  | 2         | 0.68%   |
| SK Hynix BC501 NVMe 256GB                | 2         | 0.68%   |
| Seagate ST9500420AS 500GB                | 2         | 0.68%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 0.68%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 0.68%   |
| Seagate ST1000LX015-1U7172 1TB           | 2         | 0.68%   |
| Seagate ST1000LM014-SSHD-8GB             | 2         | 0.68%   |
| SanDisk X600 M.2 2280 SATA 128GB SSD     | 2         | 0.68%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD      | 2         | 0.68%   |
| Samsung SSD 860 EVO 500GB                | 2         | 0.68%   |
| Samsung NVMe SSD Drive 512GB             | 2         | 0.68%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB SSD | 2         | 0.68%   |
| Kingston SA400S37120G 120GB SSD          | 2         | 0.68%   |
| Intel SSDSC2BF180A4H 180GB               | 2         | 0.68%   |
| HS-SSD-C100 240G                         | 2         | 0.68%   |
| Hitachi HTS545050B9SA02 500GB            | 2         | 0.68%   |
| Crucial CT500MX500SSD4 500GB             | 2         | 0.68%   |
| Crucial CT240BX500SSD1 240GB             | 2         | 0.68%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1         | 0.34%   |
| WDC WD800BEVS-07RST0 80GB                | 1         | 0.34%   |
| WDC WD5000LPVX-60V0TT0 500GB             | 1         | 0.34%   |
| WDC WD5000LPLX-08ZNTT0 500GB             | 1         | 0.34%   |
| WDC WD5000BUDT-63G8FY0 500GB             | 1         | 0.34%   |
| WDC WD5000BPVT-22HXZT1 500GB             | 1         | 0.34%   |
| WDC WD5000BEVT-75A0RT0 500GB             | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 73     | 38.24%  |
| WDC                 | 49        | 58     | 28.82%  |
| Toshiba             | 40        | 50     | 23.53%  |
| Hitachi             | 8         | 11     | 4.71%   |
| HGST                | 4         | 4      | 2.35%   |
| Unknown             | 3         | 3      | 1.76%   |
| Samsung Electronics | 1         | 2      | 0.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 14        | 16     | 18.92%  |
| Samsung Electronics | 12        | 13     | 16.22%  |
| Crucial             | 10        | 11     | 13.51%  |
| SanDisk             | 6         | 7      | 8.11%   |
| WDC                 | 5         | 5      | 6.76%   |
| SK Hynix            | 4         | 4      | 5.41%   |
| Micron Technology   | 4         | 4      | 5.41%   |
| LITEONIT            | 3         | 4      | 4.05%   |
| LITEON              | 3         | 5      | 4.05%   |
| Intel               | 3         | 3      | 4.05%   |
| TwinMOS             | 2         | 2      | 2.7%    |
| Transcend           | 2         | 2      | 2.7%    |
| Toshiba             | 2         | 3      | 2.7%    |
| Team                | 1         | 1      | 1.35%   |
| Lexar               | 1         | 1      | 1.35%   |
| KingSpec            | 1         | 1      | 1.35%   |
| HS-SSD-C100         | 1         | 2      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 163       | 201    | 58.21%  |
| SSD     | 70        | 84     | 25%     |
| NVMe    | 33        | 37     | 11.79%  |
| MMC     | 9         | 12     | 3.21%   |
| Unknown | 5         | 5      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 195       | 286    | 80.91%  |
| NVMe | 33        | 37     | 13.69%  |
| MMC  | 9         | 12     | 3.73%   |
| SAS  | 4         | 4      | 1.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 117       | 147    | 50.43%  |
| 0.51-1.0   | 102       | 125    | 43.97%  |
| 1.01-2.0   | 13        | 13     | 5.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 65        | 29.68%  |
| 251-500        | 47        | 21.46%  |
| 501-1000       | 31        | 14.16%  |
| 51-100         | 27        | 12.33%  |
| 1001-2000      | 19        | 8.68%   |
| 21-50          | 15        | 6.85%   |
| 1-20           | 10        | 4.57%   |
| Unknown        | 3         | 1.37%   |
| More than 3000 | 1         | 0.46%   |
| 2001-3000      | 1         | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 83        | 37.39%  |
| 21-50     | 45        | 20.27%  |
| 101-250   | 37        | 16.67%  |
| 51-100    | 27        | 12.16%  |
| 501-1000  | 13        | 5.86%   |
| 251-500   | 11        | 4.95%   |
| Unknown   | 3         | 1.35%   |
| 1001-2000 | 2         | 0.9%    |
| 2001-3000 | 1         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 7.69%   |
| WDC WD5000LPVX-60V0TT0 500GB                        | 1         | 1      | 7.69%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 7.69%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 7.69%   |
| Seagate ST95005620AS 500GB                          | 1         | 2      | 7.69%   |
| Seagate ST9320328CS 320GB                           | 1         | 2      | 7.69%   |
| Seagate ST2000LM015-2E81 2TB                        | 1         | 1      | 7.69%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 7.69%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 7.69%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 7.69%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 7.69%   |
| A-DATA Technology IM2P33F3 NVMe 256GB               | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 5         | 7      | 38.46%  |
| WDC               | 3         | 3      | 23.08%  |
| Micron Technology | 2         | 2      | 15.38%  |
| SK Hynix          | 1         | 1      | 7.69%   |
| Intel             | 1         | 1      | 7.69%   |
| A-DATA Technology | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 7      | 62.5%   |
| WDC     | 3         | 3      | 37.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 10     | 61.54%  |
| SSD  | 4         | 4      | 30.77%  |
| NVMe | 1         | 1      | 7.69%   |

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
| Detected | 149       | 236    | 68.98%  |
| Works    | 54        | 88     | 25%     |
| Malfunc  | 13        | 15     | 6.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 177       | 75.97%  |
| AMD                          | 19        | 8.15%   |
| Samsung Electronics          | 13        | 5.58%   |
| Toshiba America Info Systems | 5         | 2.15%   |
| SK Hynix                     | 5         | 2.15%   |
| Sandisk                      | 3         | 1.29%   |
| Micron/Crucial Technology    | 2         | 0.86%   |
| ADATA Technology             | 2         | 0.86%   |
| VIA Technologies             | 1         | 0.43%   |
| Union Memory (Shenzhen)      | 1         | 0.43%   |
| Silicon Motion               | 1         | 0.43%   |
| Shenzhen Longsys Electronics | 1         | 0.43%   |
| Nvidia                       | 1         | 0.43%   |
| Micron Technology            | 1         | 0.43%   |
| KIOXIA                       | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 35        | 14.71%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 18        | 7.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 15        | 6.3%    |
| AMD FCH SATA Controller [AHCI mode]                                                    | 15        | 6.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 14        | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 14        | 5.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 4.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 9         | 3.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 3.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 9         | 3.78%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 8         | 3.36%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 6         | 2.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 2.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 2.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 2.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 5         | 2.1%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 4         | 1.68%   |
| Samsung NVMe SSD Controller 980                                                        | 4         | 1.68%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 3         | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 1.26%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 3         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.26%   |
| Sandisk PC SN520 NVMe SSD                                                              | 2         | 0.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.84%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 0.84%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 0.84%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 2         | 0.84%   |
| ADATA Non-Volatile memory controller                                                   | 2         | 0.84%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 1         | 0.42%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 1         | 0.42%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.42%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.42%   |
| SK Hynix Gold P31 SSD                                                                  | 1         | 0.42%   |
| SK Hynix BC511                                                                         | 1         | 0.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.42%   |
| Shenzhen Longsys Non-Volatile memory controller                                        | 1         | 0.42%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.42%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 0.42%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.42%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 0.42%   |
| Micron Non-Volatile memory controller                                                  | 1         | 0.42%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 0.42%   |
| Intel SATA Controller [RAID mode]                                                      | 1         | 0.42%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                            | 1         | 0.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 0.42%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 0.42%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.42%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.42%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 180       | 76.6%   |
| NVMe | 35        | 14.89%  |
| RAID | 11        | 4.68%   |
| IDE  | 9         | 3.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 189       | 90.43%  |
| AMD    | 20        | 9.57%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz            | 12        | 5.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 10        | 4.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 7         | 3.35%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 7         | 3.35%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz           | 6         | 2.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 5         | 2.39%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 4         | 1.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 4         | 1.91%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 4         | 1.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 3         | 1.44%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz           | 3         | 1.44%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 3         | 1.44%   |
| Intel Core i7-2630QM CPU @ 2.00GHz           | 3         | 1.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 3         | 1.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 3         | 1.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 3         | 1.44%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 3         | 1.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 3         | 1.44%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 3         | 1.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 3         | 1.44%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 3         | 1.44%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 2         | 0.96%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 2         | 0.96%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz           | 2         | 0.96%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz           | 2         | 0.96%   |
| Intel Core i7-2670QM CPU @ 2.20GHz           | 2         | 0.96%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 2         | 0.96%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 2         | 0.96%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 2         | 0.96%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 2         | 0.96%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 2         | 0.96%   |
| Intel Core i5 CPU M 520 @ 2.40GHz            | 2         | 0.96%   |
| Intel Core i3-7020U CPU @ 2.30GHz            | 2         | 0.96%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 2         | 0.96%   |
| Intel Core i3-2330M CPU @ 2.20GHz            | 2         | 0.96%   |
| Intel Core i3 CPU M 350 @ 2.27GHz            | 2         | 0.96%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz         | 2         | 0.96%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz            | 2         | 0.96%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G | 2         | 0.96%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 0.96%   |
| Intel Processor 5Y70 CPU @ 1.10GHz           | 1         | 0.48%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 1         | 0.48%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz  | 1         | 0.48%   |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.48%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.48%   |
| Intel Pentium CPU N3540 @ 2.16GHz            | 1         | 0.48%   |
| Intel Pentium 3560Y @ 1.20GHz                | 1         | 0.48%   |
| Intel Genuine CPU T2300 @ 1.66GHz            | 1         | 0.48%   |
| Intel Core i9-8950HK CPU @ 2.90GHz           | 1         | 0.48%   |
| Intel Core i7-8665U CPU @ 1.90GHz            | 1         | 0.48%   |
| Intel Core i7-5600U CPU @ 2.60GHz            | 1         | 0.48%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz           | 1         | 0.48%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz           | 1         | 0.48%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.48%   |
| Intel Core i7-4600M CPU @ 2.90GHz            | 1         | 0.48%   |
| Intel Core i7-4500U CPU @ 1.80GHz            | 1         | 0.48%   |
| Intel Core i7-3632QM CPU @ 2.20GHz           | 1         | 0.48%   |
| Intel Core i7-3612QM CPU @ 2.10GHz           | 1         | 0.48%   |
| Intel Core i7-3610QM CPU @ 2.30GHz           | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 88        | 42.11%  |
| Intel Core i5           | 57        | 27.27%  |
| Intel Core i3           | 19        | 9.09%   |
| Intel Core 2 Duo        | 7         | 3.35%   |
| Intel Pentium           | 4         | 1.91%   |
| Intel Celeron           | 4         | 1.91%   |
| Intel Atom              | 4         | 1.91%   |
| Other                   | 3         | 1.44%   |
| AMD PRO A10             | 3         | 1.44%   |
| Intel Pentium Dual-Core | 2         | 0.96%   |
| AMD Ryzen 5             | 2         | 0.96%   |
| AMD E2                  | 2         | 0.96%   |
| AMD E1                  | 2         | 0.96%   |
| AMD Athlon II Dual-Core | 2         | 0.96%   |
| AMD A8                  | 2         | 0.96%   |
| AMD A6                  | 2         | 0.96%   |
| AMD A4                  | 2         | 0.96%   |
| Intel Genuine           | 1         | 0.48%   |
| Intel Core i9           | 1         | 0.48%   |
| AMD Ryzen 7             | 1         | 0.48%   |
| AMD E                   | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 114       | 54.55%  |
| 4      | 76        | 36.36%  |
| 6      | 16        | 7.66%   |
| 8      | 2         | 0.96%   |
| 1      | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 209       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 173       | 82.78%  |
| 1      | 36        | 17.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 202       | 96.19%  |
| Unknown        | 7         | 3.33%   |
| 32-bit         | 1         | 0.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 20.37%  |
| 0x206a7    | 17        | 7.87%   |
| 0x306c3    | 14        | 6.48%   |
| 0x40651    | 13        | 6.02%   |
| 0x306a9    | 13        | 6.02%   |
| 0x906ea    | 12        | 5.56%   |
| 0x806ea    | 12        | 5.56%   |
| 0x806e9    | 12        | 5.56%   |
| 0x806ec    | 10        | 4.63%   |
| 0x306d4    | 8         | 3.7%    |
| 0x406e3    | 7         | 3.24%   |
| 0x906e9    | 5         | 2.31%   |
| 0x1067a    | 5         | 2.31%   |
| 0xa0652    | 3         | 1.39%   |
| 0x706e5    | 3         | 1.39%   |
| 0x6fd      | 3         | 1.39%   |
| 0x406c3    | 3         | 1.39%   |
| 0x30678    | 3         | 1.39%   |
| 0x20655    | 3         | 1.39%   |
| 0x20652    | 3         | 1.39%   |
| 0x06006705 | 3         | 1.39%   |
| 0x806eb    | 2         | 0.93%   |
| 0x506e3    | 2         | 0.93%   |
| 0x06006704 | 2         | 0.93%   |
| 0x806c1    | 1         | 0.46%   |
| 0x6e8      | 1         | 0.46%   |
| 0x506c9    | 1         | 0.46%   |
| 0x106e5    | 1         | 0.46%   |
| 0x10676    | 1         | 0.46%   |
| 0x08600106 | 1         | 0.46%   |
| 0x08108102 | 1         | 0.46%   |
| 0x07030106 | 1         | 0.46%   |
| 0x0600611a | 1         | 0.46%   |
| 0x06006110 | 1         | 0.46%   |
| 0x06003109 | 1         | 0.46%   |
| 0x0600111f | 1         | 0.46%   |
| 0x05000119 | 1         | 0.46%   |
| 0x05000029 | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 68        | 32.54%  |
| Haswell     | 32        | 15.31%  |
| SandyBridge | 18        | 8.61%   |
| IvyBridge   | 14        | 6.7%    |
| Skylake     | 12        | 5.74%   |
| Westmere    | 9         | 4.31%   |
| Broadwell   | 9         | 4.31%   |
| Excavator   | 8         | 3.83%   |
| Silvermont  | 7         | 3.35%   |
| Penryn      | 6         | 2.87%   |
| CometLake   | 4         | 1.91%   |
| IceLake     | 3         | 1.44%   |
| Core        | 3         | 1.44%   |
| Zen 2       | 2         | 0.96%   |
| Puma        | 2         | 0.96%   |
| Piledriver  | 2         | 0.96%   |
| K10         | 2         | 0.96%   |
| Bobcat      | 2         | 0.96%   |
| Zen+        | 1         | 0.48%   |
| TigerLake   | 1         | 0.48%   |
| Steamroller | 1         | 0.48%   |
| P6          | 1         | 0.48%   |
| Nehalem     | 1         | 0.48%   |
| Goldmont    | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 174       | 54.04%  |
| Nvidia           | 76        | 23.6%   |
| AMD              | 71        | 22.05%  |
| VIA Technologies | 1         | 0.31%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 18        | 5.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 5.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 4.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 14        | 4.31%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 4%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 3.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 3.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 12        | 3.69%   |
| Intel HD Graphics 620                                                                    | 10        | 3.08%   |
| Nvidia GM108M [GeForce MX130]                                                            | 9         | 2.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.77%   |
| Intel HD Graphics 5500                                                                   | 8         | 2.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 2.46%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 2.15%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 2.15%   |
| Intel HD Graphics 630                                                                    | 6         | 1.85%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 1.54%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.54%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.23%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 1.23%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.92%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.92%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.92%   |
| Intel HD Graphics 530                                                                    | 3         | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.92%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 3         | 0.92%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.92%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 0.92%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.92%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.62%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.62%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.62%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 2         | 0.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.62%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 2         | 0.62%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.62%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 2         | 0.62%   |
| AMD Topaz PRO [Radeon R5 M255]                                                           | 2         | 0.62%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 0.62%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.62%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.62%   |
| AMD Renoir                                                                               | 2         | 0.62%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 0.62%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 2         | 0.62%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 0.62%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 2         | 0.62%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.31%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.31%   |
| Nvidia TU117M                                                                            | 1         | 0.31%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.31%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.31%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.31%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 68        | 32.23%  |
| 1 x Intel      | 64        | 30.33%  |
| Intel + AMD    | 44        | 20.85%  |
| 1 x AMD        | 25        | 11.85%  |
| 1 x Nvidia     | 7         | 3.32%   |
| 2 x AMD        | 1         | 0.47%   |
| 1 x VIA        | 1         | 0.47%   |
| AMD + Nvidia   | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 175       | 82.16%  |
| Proprietary | 35        | 16.43%  |
| Unknown     | 3         | 1.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 50.23%  |
| 1.01-2.0   | 43        | 20%     |
| 3.01-4.0   | 34        | 15.81%  |
| 0.01-0.5   | 14        | 6.51%   |
| 0.51-1.0   | 13        | 6.05%   |
| 5.01-6.0   | 3         | 1.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 44        | 20.56%  |
| LG Display              | 43        | 20.09%  |
| Chimei Innolux          | 36        | 16.82%  |
| AU Optronics            | 34        | 15.89%  |
| Samsung Electronics     | 27        | 12.62%  |
| Chi Mei Optoelectronics | 10        | 4.67%   |
| Lenovo                  | 5         | 2.34%   |
| Dell                    | 4         | 1.87%   |
| InfoVision              | 3         | 1.4%    |
| Philips                 | 2         | 0.93%   |
| PANDA                   | 2         | 0.93%   |
| Panasonic               | 1         | 0.47%   |
| LG Philips              | 1         | 0.47%   |
| CPT                     | 1         | 0.47%   |
| Apple                   | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 8         | 3.74%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 6         | 2.8%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 4         | 1.87%   |
| BOE LCD Monitor BOE07B0 1920x1080 344x194mm 15.5-inch                    | 4         | 1.87%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 1.87%   |
| Samsung Electronics LCD Monitor SEC3151 1366x768 344x194mm 15.5-inch     | 3         | 1.4%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 1.4%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 3         | 1.4%    |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 3         | 1.4%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 2         | 0.93%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch    | 2         | 0.93%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 2         | 0.93%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.93%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                  | 2         | 0.93%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15C2 1920x1080 344x194mm 15.5-inch         | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 2         | 0.93%   |
| BOE LCD Monitor BOE0826 1920x1080 344x193mm 15.5-inch                    | 2         | 0.93%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 2         | 0.93%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 2         | 0.93%   |
| BOE LCD Monitor BOE06C6 1920x1080 344x194mm 15.5-inch                    | 2         | 0.93%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 2         | 0.93%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.93%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch      | 1         | 0.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 1         | 0.47%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 1         | 0.47%   |
| Samsung Electronics S22B300 SAM08AB 1920x1080 477x268mm 21.5-inch        | 1         | 0.47%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch         | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 309x174mm 14.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC374E 1366x768 344x193mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4247 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC3854 1920x1080 382x215mm 17.3-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC3147 1920x1080 276x155mm 12.5-inch    | 1         | 0.47%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch       | 1         | 0.47%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch        | 1         | 0.47%   |
| Philips 225PL PHL088D 1680x1050 474x296mm 22.0-inch                      | 1         | 0.47%   |
| Philips 191EW PHLC02A 1366x768 413x234mm 18.7-inch                       | 1         | 0.47%   |
| PANDA LCD Monitor NCP0056 1920x1080 309x174mm 14.0-inch                  | 1         | 0.47%   |
| PANDA LCD Monitor NCP0054 1920x1080 344x194mm 15.5-inch                  | 1         | 0.47%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch              | 1         | 0.47%   |
| LG Philips LCD Monitor LPL017D 1280x800 331x207mm 15.4-inch              | 1         | 0.47%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch            | 1         | 0.47%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch              | 1         | 0.47%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 0.47%   |
| LG Display LCD Monitor LGD05DA 1920x1080 309x174mm 14.0-inch             | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 106       | 50.24%  |
| 1920x1080 (FHD)    | 82        | 38.86%  |
| 1600x900 (HD+)     | 7         | 3.32%   |
| 1280x800 (WXGA)    | 6         | 2.84%   |
| 3840x2160 (4K)     | 4         | 1.9%    |
| 1440x900 (WXGA+)   | 3         | 1.42%   |
| 1680x1050 (WSXGA+) | 2         | 0.95%   |
| 3200x1800 (QHD+)   | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 144       | 67.29%  |
| 14      | 28        | 13.08%  |
| 13      | 13        | 6.07%   |
| 17      | 7         | 3.27%   |
| 12      | 6         | 2.8%    |
| 18      | 3         | 1.4%    |
| 27      | 2         | 0.93%   |
| 22      | 2         | 0.93%   |
| 21      | 2         | 0.93%   |
| 19      | 2         | 0.93%   |
| 11      | 2         | 0.93%   |
| 24      | 1         | 0.47%   |
| 23      | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 181       | 85.38%  |
| 201-300     | 11        | 5.19%   |
| 401-500     | 8         | 3.77%   |
| 351-400     | 7         | 3.3%    |
| 501-600     | 4         | 1.89%   |
| Unknown     | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 194       | 95.1%   |
| 16/10   | 9         | 4.41%   |
| Unknown | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 141       | 66.2%   |
| 81-90          | 37        | 17.37%  |
| 61-70          | 6         | 2.82%   |
| 121-130        | 6         | 2.82%   |
| 201-250        | 5         | 2.35%   |
| 71-80          | 3         | 1.41%   |
| 151-200        | 3         | 1.41%   |
| 91-100         | 3         | 1.41%   |
| 51-60          | 2         | 0.94%   |
| 301-350        | 2         | 0.94%   |
| 141-150        | 2         | 0.94%   |
| 251-300        | 1         | 0.47%   |
| 131-140        | 1         | 0.47%   |
| Unknown        | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 98        | 46.67%  |
| 121-160       | 86        | 40.95%  |
| 51-100        | 22        | 10.48%  |
| More than 240 | 2         | 0.95%   |
| 161-240       | 1         | 0.48%   |
| Unknown       | 1         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 197       | 92.92%  |
| 2     | 12        | 5.66%   |
| 0     | 2         | 0.94%   |
| 3     | 1         | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 149       | 41.39%  |
| Intel                             | 98        | 27.22%  |
| Qualcomm Atheros                  | 56        | 15.56%  |
| Broadcom                          | 26        | 7.22%   |
| Broadcom Limited                  | 7         | 1.94%   |
| Ralink                            | 6         | 1.67%   |
| Huawei Technologies               | 4         | 1.11%   |
| Samsung Electronics               | 2         | 0.56%   |
| Ralink Technology                 | 2         | 0.56%   |
| MEDIATEK                          | 2         | 0.56%   |
| Marvell Technology Group          | 2         | 0.56%   |
| VIA Technologies                  | 1         | 0.28%   |
| TP-Link                           | 1         | 0.28%   |
| Nvidia                            | 1         | 0.28%   |
| Ericsson Business Mobile Networks | 1         | 0.28%   |
| Dell                              | 1         | 0.28%   |
| ASIX Electronics                  | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 21.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 55        | 13.29%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 24        | 5.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 2.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 2.17%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.17%   |
| Intel Wireless 7260                                               | 9         | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 1.93%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 1.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 1.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.69%   |
| Intel Wireless 8260                                               | 7         | 1.69%   |
| Intel Wireless 7265                                               | 7         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.45%   |
| Intel Wireless 3160                                               | 6         | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 1.21%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.21%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 1.21%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.97%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 0.97%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.72%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 3         | 0.72%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.72%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 3         | 0.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.48%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.48%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.48%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.48%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.48%   |
| Intel PRODUCT_MODEM                                               | 2         | 0.48%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.48%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.48%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.48%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.48%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.48%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.48%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2         | 0.48%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 2         | 0.48%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.48%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.24%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.24%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.24%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.24%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.24%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.24%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.24%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 94        | 44.34%  |
| Qualcomm Atheros      | 48        | 22.64%  |
| Realtek Semiconductor | 30        | 14.15%  |
| Broadcom              | 23        | 10.85%  |
| Ralink                | 6         | 2.83%   |
| Broadcom Limited      | 6         | 2.83%   |
| Ralink Technology     | 2         | 0.94%   |
| TP-Link               | 1         | 0.47%   |
| MEDIATEK              | 1         | 0.47%   |
| Dell                  | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 24        | 11.27%  |
| Intel Cannon Lake PCH CNVi WiFi                                               | 11        | 5.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 9         | 4.23%   |
| Intel Wireless 8265 / 8275                                                    | 9         | 4.23%   |
| Intel Wireless 7260                                                           | 9         | 4.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 8         | 3.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 8         | 3.76%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 8         | 3.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 8         | 3.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 7         | 3.29%   |
| Intel Wireless 8260                                                           | 7         | 3.29%   |
| Intel Wireless 7265                                                           | 7         | 3.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 2.82%   |
| Intel Wireless 3160                                                           | 6         | 2.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 5         | 2.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 5         | 2.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 4         | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4         | 1.88%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 4         | 1.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3         | 1.41%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 3         | 1.41%   |
| Intel Centrino Advanced-N 6235                                                | 3         | 1.41%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 3         | 1.41%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 2         | 0.94%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 2         | 0.94%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 0.94%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 2         | 0.94%   |
| Intel PRODUCT_MODEM                                                           | 2         | 0.94%   |
| Intel Centrino Wireless-N 2230                                                | 2         | 0.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 0.94%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 0.94%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                    | 2         | 0.94%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 2         | 0.94%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.47%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 0.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 0.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 0.47%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.47%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter                           | 1         | 0.47%   |
| Intel Wireless-AC 9260                                                        | 1         | 0.47%   |
| Intel Wireless 3165                                                           | 1         | 0.47%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 0.47%   |
| Intel Wi-Fi 6 AX200                                                           | 1         | 0.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 1         | 0.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 0.47%   |
| Intel Centrino Wireless-N 2200                                                | 1         | 0.47%   |
| Dell Wireless 5808e Gobiâ¢ 4G LTE Mobile Broadband Card                   | 1         | 0.47%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                   | 1         | 0.47%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1         | 0.47%   |
| Broadcom BCM43225 802.11b/g/n                                                 | 1         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 143       | 72.22%  |
| Intel                    | 29        | 14.65%  |
| Qualcomm Atheros         | 12        | 6.06%   |
| Broadcom                 | 3         | 1.52%   |
| Samsung Electronics      | 2         | 1.01%   |
| Marvell Technology Group | 2         | 1.01%   |
| Huawei Technologies      | 2         | 1.01%   |
| VIA Technologies         | 1         | 0.51%   |
| Nvidia                   | 1         | 0.51%   |
| MediaTek                 | 1         | 0.51%   |
| Broadcom Limited         | 1         | 0.51%   |
| ASIX Electronics         | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 44.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 55        | 27.78%  |
| Intel Ethernet Connection I217-LM                                 | 5         | 2.53%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.02%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.01%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.01%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.01%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.01%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.01%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.01%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2         | 1.01%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.51%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.51%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.51%   |
| MediaTek NOA N2                                                   | 1         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.51%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.51%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.51%   |
| Huawei JNY-LX1                                                    | 1         | 0.51%   |
| Huawei E353/E3131                                                 | 1         | 0.51%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.51%   |
| Broadcom Limited NetXtreme BCM5762 Gigabit Ethernet PCIe          | 1         | 0.51%   |
| ASIX AX88772B                                                     | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 206       | 51.37%  |
| Ethernet | 192       | 47.88%  |
| Modem    | 3         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 182       | 69.73%  |
| Ethernet | 79        | 30.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 188       | 89.95%  |
| 1     | 15        | 7.18%   |
| 0     | 4         | 1.91%   |
| 3     | 2         | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 209       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 45.03%  |
| Qualcomm Atheros Communications | 30        | 17.54%  |
| Realtek Semiconductor           | 19        | 11.11%  |
| Broadcom                        | 15        | 8.77%   |
| Foxconn / Hon Hai               | 6         | 3.51%   |
| Toshiba                         | 5         | 2.92%   |
| Ralink                          | 4         | 2.34%   |
| Lite-On Technology              | 4         | 2.34%   |
| IMC Networks                    | 3         | 1.75%   |
| Dell                            | 3         | 1.75%   |
| Cambridge Silicon Radio         | 2         | 1.17%   |
| MediaTek                        | 1         | 0.58%   |
| Hewlett-Packard                 | 1         | 0.58%   |
| Apple                           | 1         | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 41        | 23.98%  |
| Qualcomm Atheros  Bluetooth Device                     | 22        | 12.87%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 14        | 8.19%   |
| Intel AX201 Bluetooth                                  | 11        | 6.43%   |
| Realtek Bluetooth Radio                                | 10        | 5.85%   |
| Ralink RT3290 Bluetooth                                | 4         | 2.34%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 4         | 2.34%   |
| Broadcom BCM43142 Bluetooth 4.0                        | 4         | 2.34%   |
| Realtek RTL8723B Bluetooth                             | 3         | 1.75%   |
| Realtek  Bluetooth 4.2 Adapter                         | 3         | 1.75%   |
| Qualcomm Atheros AR9462 Bluetooth                      | 3         | 1.75%   |
| Qualcomm Atheros AR3011 Bluetooth                      | 3         | 1.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth             | 3         | 1.75%   |
| Intel Wireless-AC 3168 Bluetooth                       | 3         | 1.75%   |
| Intel Bluetooth Device                                 | 3         | 1.75%   |
| Dell Wireless 365 Bluetooth                            | 3         | 1.75%   |
| Realtek 802.11n WLAN Adapter                           | 2         | 1.17%   |
| IMC Networks Bluetooth Radio                           | 2         | 1.17%   |
| Foxconn / Hon Hai Bluetooth Device                     | 2         | 1.17%   |
| Foxconn / Hon Hai BCM20702A0                           | 2         | 1.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 2         | 1.17%   |
| Broadcom HP Portable SoftSailing                       | 2         | 1.17%   |
| Broadcom HP Portable Bumble Bee                        | 2         | 1.17%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                   | 2         | 1.17%   |
| Broadcom BCM2045B (BDC-2.1)                            | 2         | 1.17%   |
| Toshiba RT Bluetooth Radio                             | 1         | 0.58%   |
| Toshiba Integrated Bluetooth HCI                       | 1         | 0.58%   |
| Toshiba Bluetooth USB Host Controller                  | 1         | 0.58%   |
| Toshiba Bluetooth Device                               | 1         | 0.58%   |
| Toshiba Askey Bluetooth Module                         | 1         | 0.58%   |
| Realtek RTL8821A Bluetooth                             | 1         | 0.58%   |
| Qualcomm Atheros Bluetooth USB Host Controller         | 1         | 0.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 1         | 0.58%   |
| MediaTek MT7630e Bluetooth Adapter                     | 1         | 0.58%   |
| Lite-On Bluetooth Device                               | 1         | 0.58%   |
| Intel AX200 Bluetooth                                  | 1         | 0.58%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                       | 1         | 0.58%   |
| Foxconn / Hon Hai BCM43142A0                           | 1         | 0.58%   |
| Foxconn / Hon Hai Acer Bluetooth module                | 1         | 0.58%   |
| Broadcom BCM43142A0 Bluetooth Device                   | 1         | 0.58%   |
| Broadcom BCM43142A0 Bluetooth 4.0                      | 1         | 0.58%   |
| Broadcom BCM20702A0                                    | 1         | 0.58%   |
| Apple Bluetooth Host Controller                        | 1         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 182       | 75.83%  |
| Nvidia           | 29        | 12.08%  |
| AMD              | 27        | 11.25%  |
| VIA Technologies | 1         | 0.42%   |
| Logitech         | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 39        | 13.22%  |
| Intel 8 Series HD Audio Controller                                                                | 18        | 6.1%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 17        | 5.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 5.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 5.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 5.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 4.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 3.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 3.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 3.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 3.05%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 2.71%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 2.71%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 2.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 2.03%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 2.03%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.69%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.36%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.02%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.68%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.68%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.68%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.34%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.34%   |
| Nvidia stereo controller                                                                          | 1         | 0.34%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.34%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.34%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.34%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.34%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.34%   |
| Logitech USB Headset                                                                              | 1         | 0.34%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.34%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.34%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.34%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.34%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.34%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.34%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 0.34%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 41        | 36.28%  |
| Samsung Electronics | 33        | 29.2%   |
| Micron Technology   | 10        | 8.85%   |
| Ramaxel Technology  | 9         | 7.96%   |
| Kingston            | 6         | 5.31%   |
| Crucial             | 5         | 4.42%   |
| Nanya Technology    | 3         | 2.65%   |
| Unknown             | 2         | 1.77%   |
| Unknown (ABCD)      | 1         | 0.88%   |
| G.Skill             | 1         | 0.88%   |
| ELPIDA              | 1         | 0.88%   |
| AXIOM               | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 7         | 6.09%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 4         | 3.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 2.61%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 3         | 2.61%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.74%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 1.74%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.74%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.74%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 1.74%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 2         | 1.74%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 1.74%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.74%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 1.74%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.74%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.74%   |
| Ramaxel RAM RMSA3260NA78HAF-2400 8GB SODIMM DDR4 2400MT/s           | 2         | 1.74%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 2         | 1.74%   |
| Unknown RAM Module 8GB SODIMM DDR3                                  | 1         | 0.87%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.87%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.87%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 1         | 0.87%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.87%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 3200MT/s                     | 1         | 0.87%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                     | 1         | 0.87%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1600MT/s                          | 1         | 0.87%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                     | 1         | 0.87%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2133MT/s                    | 1         | 0.87%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 1         | 0.87%   |
| SK Hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 1334MT/s           | 1         | 0.87%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s           | 1         | 0.87%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.87%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s          | 1         | 0.87%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.87%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 0.87%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.87%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2400MT/s                     | 1         | 0.87%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2133MT/s                     | 1         | 0.87%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 0.87%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s            | 1         | 0.87%   |
| Samsung RAM M471B5273EB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.87%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.87%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.87%   |
| Samsung RAM M471B5173BH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.87%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.87%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 0.87%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 0.87%   |
| Samsung RAM M471A1G43EB1-CPB 8192MB SODIMM DDR4 2133MT/s            | 1         | 0.87%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 0.87%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s             | 1         | 0.87%   |
| Ramaxel RAM RMSA3300MH78HBF-2666 16384MB SODIMM DDR4 2400MT/s       | 1         | 0.87%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 52        | 57.14%  |
| DDR3   | 34        | 37.36%  |
| LPDDR4 | 2         | 2.2%    |
| SDRAM  | 1         | 1.1%    |
| DDR2   | 1         | 1.1%    |
| DDR    | 1         | 1.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 87        | 98.86%  |
| DIMM   | 1         | 1.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 38        | 38.38%  |
| 4096  | 27        | 27.27%  |
| 16384 | 20        | 20.2%   |
| 2048  | 12        | 12.12%  |
| 1024  | 1         | 1.01%   |
| 512   | 1         | 1.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 39        | 39.8%   |
| 1600    | 27        | 27.55%  |
| 2400    | 8         | 8.16%   |
| 1334    | 7         | 7.14%   |
| 3200    | 6         | 6.12%   |
| 2133    | 5         | 5.1%    |
| 1333    | 2         | 2.04%   |
| 4199    | 1         | 1.02%   |
| 800     | 1         | 1.02%   |
| 667     | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1018 | 1         | 50%     |
| HP Deskjet 1510  | 1         | 50%     |

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
| Chicony Electronics                    | 46        | 24.08%  |
| Microdia                               | 25        | 13.09%  |
| Realtek Semiconductor                  | 23        | 12.04%  |
| Cheng Uei Precision Industry (Foxlink) | 23        | 12.04%  |
| Acer                                   | 16        | 8.38%   |
| Sunplus Innovation Technology          | 14        | 7.33%   |
| IMC Networks                           | 12        | 6.28%   |
| Lite-On Technology                     | 8         | 4.19%   |
| Suyin                                  | 6         | 3.14%   |
| Quanta                                 | 4         | 2.09%   |
| Silicon Motion                         | 3         | 1.57%   |
| Apple                                  | 3         | 1.57%   |
| Syntek                                 | 2         | 1.05%   |
| Sonix Technology                       | 1         | 0.52%   |
| OmniVision Technologies                | 1         | 0.52%   |
| MacroSilicon                           | 1         | 0.52%   |
| Lenovo                                 | 1         | 0.52%   |
| Intel                                  | 1         | 0.52%   |
| ALi                                    | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                   | 14        | 7.29%   |
| Microdia Integrated_Webcam_HD                                  | 12        | 6.25%   |
| Chicony EasyCamera                                             | 8         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam            | 7         | 3.65%   |
| Sunplus Integrated_Webcam_HD                                   | 6         | 3.13%   |
| Chicony Integrated Camera                                      | 6         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 6         | 3.13%   |
| Acer Lenovo EasyCamera                                         | 6         | 3.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 5         | 2.6%    |
| IMC Networks Integrated Camera                                 | 5         | 2.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 2.08%   |
| Acer HP TrueVision HD Webcam                                   | 4         | 2.08%   |
| Realtek Integrated Webcam                                      | 3         | 1.56%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 3         | 1.56%   |
| Lite-On HP HD Camera                                           | 3         | 1.56%   |
| Chicony HP Truevision HD camera                                | 3         | 1.56%   |
| Chicony HP HD Webcam                                           | 3         | 1.56%   |
| Chicony HP HD Camera                                           | 3         | 1.56%   |
| Suyin HP Truevision HD                                         | 2         | 1.04%   |
| Sunplus HP HD Webcam [Fixed]                                   | 2         | 1.04%   |
| Sunplus Dell HD Webcam                                         | 2         | 1.04%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.04%   |
| Quanta HP Webcam                                               | 2         | 1.04%   |
| Microdia Laptop_Integrated_Webcam_1.3M                         | 2         | 1.04%   |
| Microdia Dell Laptop Integrated Webcam HD                      | 2         | 1.04%   |
| Microdia 1.3 MPixel Integrated Webcam                          | 2         | 1.04%   |
| Lite-On Integrated Camera                                      | 2         | 1.04%   |
| Lite-On HP HD Webcam                                           | 2         | 1.04%   |
| Chicony HP Integrated Webcam                                   | 2         | 1.04%   |
| Chicony HD WebCam                                              | 2         | 1.04%   |
| Chicony Front Camera                                           | 2         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.04%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 2         | 1.04%   |
| Acer SunplusIT Integrated Camera                               | 2         | 1.04%   |
| Acer EasyCamera                                                | 2         | 1.04%   |
| Syntek Lenovo EasyCamera                                       | 1         | 0.52%   |
| Syntek Integrated Camera                                       | 1         | 0.52%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 1         | 0.52%   |
| Suyin HP Webcam-50                                             | 1         | 0.52%   |
| Suyin HP Integrated Webcam                                     | 1         | 0.52%   |
| Suyin 1.3M HD WebCam                                           | 1         | 0.52%   |
| Sunplus Lenovo EasyCamera                                      | 1         | 0.52%   |
| Sunplus Laptop Integrated Webcam FHD                           | 1         | 0.52%   |
| Sunplus HP Wide Vision HD                                      | 1         | 0.52%   |
| Sunplus HP Universal Camera                                    | 1         | 0.52%   |
| Sonix HP Webcam-101                                            | 1         | 0.52%   |
| Silicon Motion WebCam SC-03M12736N                             | 1         | 0.52%   |
| Silicon Motion Lenovo EasyCamera                               | 1         | 0.52%   |
| Silicon Motion HP Webcam-101                                   | 1         | 0.52%   |
| Realtek USB Camera                                             | 1         | 0.52%   |
| Realtek Rear Camera                                            | 1         | 0.52%   |
| Realtek HP "Truevision HD" laptop camera                       | 1         | 0.52%   |
| Realtek Acer 640 x 480 laptop camera                           | 1         | 0.52%   |
| Quanta VGA WebCam                                              | 1         | 0.52%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 0.52%   |
| OmniVision OV2640 Webcam                                       | 1         | 0.52%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam                 | 1         | 0.52%   |
| Microdia Integrated_Webcam_1.3M                                | 1         | 0.52%   |
| Microdia Integrated Webcam HD                                  | 1         | 0.52%   |
| Microdia Integrated Webcam                                     | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 51.28%  |
| Synaptics                  | 10        | 25.64%  |
| Shenzhen Goodix Technology | 5         | 12.82%  |
| Upek                       | 3         | 7.69%   |
| AuthenTec                  | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 10        | 25.64%  |
| Validity Sensors Fingerprint scanner                      | 5         | 12.82%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 4         | 10.26%  |
| Shenzhen Goodix Fingerprint Reader                        | 4         | 10.26%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 3         | 7.69%   |
| Synaptics  WBDI                                           | 3         | 7.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 3         | 7.69%   |
| Validity Sensors VFS491                                   | 2         | 5.13%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 2.56%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 2.56%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 2.56%   |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 2.56%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 54.55%  |
| Alcor Micro | 3         | 27.27%  |
| O2 Micro    | 1         | 9.09%   |
| Lenovo      | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 18.18%  |
| Broadcom 5880                                                                | 2         | 18.18%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Broadcom 58200                                                               | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 136       | 63.85%  |
| 1     | 65        | 30.52%  |
| 2     | 12        | 5.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 38        | 44.71%  |
| Graphics card         | 19        | 22.35%  |
| Chipcard              | 11        | 12.94%  |
| Net/wireless          | 9         | 10.59%  |
| Bluetooth             | 5         | 5.88%   |
| Net/ethernet          | 1         | 1.18%   |
| Multimedia controller | 1         | 1.18%   |
| Card reader           | 1         | 1.18%   |
