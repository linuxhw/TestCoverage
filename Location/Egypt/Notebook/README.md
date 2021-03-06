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

Total: 322

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion 15                 | [e35e3b2e52](https://linux-hardware.org/?probe=e35e3b2e52) | Jul 01, 2022 |
| HP            | Pavilion 15                 | [f76f8dff7a](https://linux-hardware.org/?probe=f76f8dff7a) | Jun 30, 2022 |
| HP            | ProBook 645 G1              | [1157ee7e3a](https://linux-hardware.org/?probe=1157ee7e3a) | Jun 21, 2022 |
| ASUSTek       | X555LJ                      | [ee2a9b3c87](https://linux-hardware.org/?probe=ee2a9b3c87) | Jun 20, 2022 |
| Dell          | G5 5587                     | [9f2ca6b48b](https://linux-hardware.org/?probe=9f2ca6b48b) | Jun 18, 2022 |
| Lenovo        | B40-80 80F6                 | [7449f0f8d2](https://linux-hardware.org/?probe=7449f0f8d2) | Jun 13, 2022 |
| HP            | ProBook 445 G7              | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| ASUSTek       | X553MA                      | [1794b92b61](https://linux-hardware.org/?probe=1794b92b61) | Jun 12, 2022 |
| Dell          | Latitude E6410              | [184348232a](https://linux-hardware.org/?probe=184348232a) | Jun 11, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [4058369652](https://linux-hardware.org/?probe=4058369652) | May 21, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [bd33528d52](https://linux-hardware.org/?probe=bd33528d52) | May 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| HP            | Pavilion 15                 | [a18593bb5b](https://linux-hardware.org/?probe=a18593bb5b) | May 07, 2022 |
| Dell          | Inspiron N4050              | [6d8f615203](https://linux-hardware.org/?probe=6d8f615203) | Apr 30, 2022 |
| Dell          | Inspiron N5110              | [fb1248d6be](https://linux-hardware.org/?probe=fb1248d6be) | Apr 29, 2022 |
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
| Dell          | Latitude 3410               | [d21a10beb4](https://linux-hardware.org/?probe=d21a10beb4) | Mar 10, 2022 |
| Acer          | Aspire ES1-331              | [cbba045d50](https://linux-hardware.org/?probe=cbba045d50) | Mar 05, 2022 |
| HP            | Pavilion Notebook           | [57bb50b654](https://linux-hardware.org/?probe=57bb50b654) | Feb 27, 2022 |
| Dell          | Venue 10 Pro 5056           | [faf162367f](https://linux-hardware.org/?probe=faf162367f) | Feb 25, 2022 |
| HP            | Laptop 15-db0xxx            | [732784f9ec](https://linux-hardware.org/?probe=732784f9ec) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | [2c3ac58820](https://linux-hardware.org/?probe=2c3ac58820) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | [eed2589bd2](https://linux-hardware.org/?probe=eed2589bd2) | Feb 25, 2022 |
| HP            | ENVY dv6                    | [6d07aead9f](https://linux-hardware.org/?probe=6d07aead9f) | Feb 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
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
| Dell          | Inspiron N5110              | [d08a0ed65d](https://linux-hardware.org/?probe=d08a0ed65d) | Jan 16, 2020 |
| Lenovo        | ThinkPad E590 20NB0002AD    | [0fc61e3795](https://linux-hardware.org/?probe=0fc61e3795) | Jan 13, 2020 |
| HP            | EliteBook 745 G4            | [99937a33e7](https://linux-hardware.org/?probe=99937a33e7) | Jan 05, 2020 |
| ASUSTek       | X540UA                      | [714b86d8a5](https://linux-hardware.org/?probe=714b86d8a5) | Dec 31, 2019 |
| Dell          | Inspiron 5570               | [92a06ce5da](https://linux-hardware.org/?probe=92a06ce5da) | Dec 31, 2019 |
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
| HP            | Pavilion dv7                | [6031485dd2](https://linux-hardware.org/?probe=6031485dd2) | Nov 08, 2019 |
| Lenovo        | ThinkPad T420 4178CXG       | [70105ff0ab](https://linux-hardware.org/?probe=70105ff0ab) | Nov 03, 2019 |
| Lenovo        | ThinkPad L460 20FVS0ER00    | [713a72e731](https://linux-hardware.org/?probe=713a72e731) | Oct 31, 2019 |
| HP            | ProBook 450 G4              | [e11bd3882e](https://linux-hardware.org/?probe=e11bd3882e) | Oct 22, 2019 |
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
| Ubuntu 20.04          | 54        | 23.48%  |
| Ubuntu 18.04          | 34        | 14.78%  |
| Ubuntu 19.10          | 9         | 3.91%   |
| Ubuntu 20.10          | 7         | 3.04%   |
| Zorin 15              | 6         | 2.61%   |
| Ubuntu 22.04          | 5         | 2.17%   |
| Pop!_OS 20.10         | 5         | 2.17%   |
| OpenMandriva 4.3      | 5         | 2.17%   |
| Ubuntu 21.10          | 4         | 1.74%   |
| Linux Mint 19.3       | 4         | 1.74%   |
| Fedora 34             | 4         | 1.74%   |
| ArcoLinux Rolling     | 4         | 1.74%   |
| Arch                  | 4         | 1.74%   |
| Ubuntu 21.04          | 3         | 1.3%    |
| Pop!_OS 20.04         | 3         | 1.3%    |
| Manjaro               | 3         | 1.3%    |
| Linux Mint 20.1       | 3         | 1.3%    |
| Kubuntu 20.04         | 3         | 1.3%    |
| KDE neon 20.04        | 3         | 1.3%    |
| Fedora 35             | 3         | 1.3%    |
| Fedora 33             | 3         | 1.3%    |
| Zorin 16              | 2         | 0.87%   |
| Ubuntu 19.04          | 2         | 0.87%   |
| Ubuntu 18.10          | 2         | 0.87%   |
| Ubuntu 16.04          | 2         | 0.87%   |
| Pop!_OS 22.04         | 2         | 0.87%   |
| Pop!_OS 21.04         | 2         | 0.87%   |
| OpenMandriva 4.2      | 2         | 0.87%   |
| Linux Mint 19         | 2         | 0.87%   |
| Kali 2022.1           | 2         | 0.87%   |
| Kali 2021.1           | 2         | 0.87%   |
| Fedora 32             | 2         | 0.87%   |
| Xubuntu 22.04         | 1         | 0.43%   |
| Ubuntu Budgie 19.10   | 1         | 0.43%   |
| ROSA R9               | 1         | 0.43%   |
| ROSA R11.1            | 1         | 0.43%   |
| ROSA 12.2             | 1         | 0.43%   |
| RHEL 8                | 1         | 0.43%   |
| Manjaro 21.2.6        | 1         | 0.43%   |
| Manjaro 21.2.5        | 1         | 0.43%   |
| Manjaro 21.2.1        | 1         | 0.43%   |
| Manjaro 21.2.0        | 1         | 0.43%   |
| Manjaro 20.2.1        | 1         | 0.43%   |
| Manjaro 20.1.1        | 1         | 0.43%   |
| Manjaro 18.1.5        | 1         | 0.43%   |
| Lubuntu 20.10         | 1         | 0.43%   |
| LMDE 4                | 1         | 0.43%   |
| Linux Mint 20.3       | 1         | 0.43%   |
| Linux Mint 20.2       | 1         | 0.43%   |
| Linux Mint 20         | 1         | 0.43%   |
| Kali 2021.3           | 1         | 0.43%   |
| Kali 2019.2           | 1         | 0.43%   |
| Fedora 31             | 1         | 0.43%   |
| Endless 4.0.3         | 1         | 0.43%   |
| Endless 4.0.0         | 1         | 0.43%   |
| Endless 3.8.7         | 1         | 0.43%   |
| Endless 3.7.5         | 1         | 0.43%   |
| Endless 3.6.0         | 1         | 0.43%   |
| Endless 3.5.8         | 1         | 0.43%   |
| Endless 3.4.2-nexthw1 | 1         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 119       | 53.36%  |
| Fedora        | 13        | 5.83%   |
| Linux Mint    | 12        | 5.38%   |
| Pop!_OS       | 11        | 4.93%   |
| Manjaro       | 9         | 4.04%   |
| Zorin         | 8         | 3.59%   |
| OpenMandriva  | 7         | 3.14%   |
| Endless       | 7         | 3.14%   |
| Kali          | 6         | 2.69%   |
| ArcoLinux     | 4         | 1.79%   |
| Arch          | 4         | 1.79%   |
| ROSA          | 3         | 1.35%   |
| Kubuntu       | 3         | 1.35%   |
| KDE neon      | 3         | 1.35%   |
| Clear Linux   | 2         | 0.9%    |
| Xubuntu       | 1         | 0.45%   |
| Ubuntu Budgie | 1         | 0.45%   |
| RHEL          | 1         | 0.45%   |
| Lubuntu       | 1         | 0.45%   |
| LMDE          | 1         | 0.45%   |
| EndeavourOS   | 1         | 0.45%   |
| Elementary    | 1         | 0.45%   |
| Debian        | 1         | 0.45%   |
| CentOS        | 1         | 0.45%   |
| BlackPanther  | 1         | 0.45%   |
| ALT Linux     | 1         | 0.45%   |
| Alpine        | 1         | 0.45%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.4.0-42-generic            | 13        | 5.28%   |
| 5.4.0-58-generic            | 6         | 2.44%   |
| 5.8.0-7630-generic          | 4         | 1.63%   |
| 5.8.0-48-generic            | 4         | 1.63%   |
| 5.4.0-48-generic            | 4         | 1.63%   |
| 5.4.0-29-generic            | 4         | 1.63%   |
| 5.16.7-desktop-1omv4003     | 4         | 1.63%   |
| 5.0.0-32-generic            | 4         | 1.63%   |
| 5.8.0-43-generic            | 3         | 1.22%   |
| 5.8.0-41-generic            | 3         | 1.22%   |
| 5.4.0-56-generic            | 3         | 1.22%   |
| 5.3.0-51-generic            | 3         | 1.22%   |
| 5.3.0-18-generic            | 3         | 1.22%   |
| 5.13.0-30-generic           | 3         | 1.22%   |
| 5.11.0-38-generic           | 3         | 1.22%   |
| 5.11.0-37-generic           | 3         | 1.22%   |
| 5.4.0-80-generic            | 2         | 0.81%   |
| 5.4.0-59-generic            | 2         | 0.81%   |
| 5.4.0-54-generic            | 2         | 0.81%   |
| 5.4.0-53-generic            | 2         | 0.81%   |
| 5.4.0-52-generic            | 2         | 0.81%   |
| 5.4.0-40-generic            | 2         | 0.81%   |
| 5.4.0-100-generic           | 2         | 0.81%   |
| 5.3.0-46-generic            | 2         | 0.81%   |
| 5.3.0-45-generic            | 2         | 0.81%   |
| 5.3.0-42-generic            | 2         | 0.81%   |
| 5.3.0-26-generic            | 2         | 0.81%   |
| 5.3.0-23-generic            | 2         | 0.81%   |
| 5.17.5-76051705-generic     | 2         | 0.81%   |
| 5.15.0-39-generic           | 2         | 0.81%   |
| 5.11.0-35-generic           | 2         | 0.81%   |
| 5.10.19-200.fc33.x86_64     | 2         | 0.81%   |
| 5.10.14-desktop-1omv4002    | 2         | 0.81%   |
| 5.0.0-37-generic            | 2         | 0.81%   |
| 5.0.0-25-generic            | 2         | 0.81%   |
| 4.18.0-15-generic           | 2         | 0.81%   |
| 4.15.0-54-generic           | 2         | 0.81%   |
| 4.15.0-20-generic           | 2         | 0.81%   |
| 5.9.1-arch1-1               | 1         | 0.41%   |
| 5.8.7-200.fc32.x86_64       | 1         | 0.41%   |
| 5.8.15-301.fc33.x86_64      | 1         | 0.41%   |
| 5.8.11-1-MANJARO            | 1         | 0.41%   |
| 5.8.10-arch1-1              | 1         | 0.41%   |
| 5.8.0-45-generic            | 1         | 0.41%   |
| 5.8.0-44-generic            | 1         | 0.41%   |
| 5.8.0-40-generic            | 1         | 0.41%   |
| 5.8.0-38-generic            | 1         | 0.41%   |
| 5.8.0-36-generic            | 1         | 0.41%   |
| 5.8.0-31-generic            | 1         | 0.41%   |
| 5.8.0-28-generic            | 1         | 0.41%   |
| 5.8.0-26-generic            | 1         | 0.41%   |
| 5.8.0-25-generic            | 1         | 0.41%   |
| 5.8.0-23-generic            | 1         | 0.41%   |
| 5.7.1-050701-generic        | 1         | 0.41%   |
| 5.6.8-1-MANJARO             | 1         | 0.41%   |
| 5.6.15-300.fc32.x86_64      | 1         | 0.41%   |
| 5.5.13-arch2-1              | 1         | 0.41%   |
| 5.4.83-generic-2rosa-x86_64 | 1         | 0.41%   |
| 5.4.70-1-lts                | 1         | 0.41%   |
| 5.4.67-1-MANJARO            | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 54        | 22.88%  |
| 5.3.0   | 24        | 10.17%  |
| 5.8.0   | 23        | 9.75%   |
| 4.15.0  | 16        | 6.78%   |
| 5.0.0   | 14        | 5.93%   |
| 5.11.0  | 12        | 5.08%   |
| 5.13.0  | 11        | 4.66%   |
| 4.18.0  | 8         | 3.39%   |
| 5.15.0  | 7         | 2.97%   |
| 5.16.7  | 4         | 1.69%   |
| 5.10.0  | 4         | 1.69%   |
| 5.17.5  | 2         | 0.85%   |
| 5.17.1  | 2         | 0.85%   |
| 5.10.19 | 2         | 0.85%   |
| 5.10.14 | 2         | 0.85%   |
| 4.19.0  | 2         | 0.85%   |
| 5.9.1   | 1         | 0.42%   |
| 5.8.7   | 1         | 0.42%   |
| 5.8.15  | 1         | 0.42%   |
| 5.8.11  | 1         | 0.42%   |
| 5.8.10  | 1         | 0.42%   |
| 5.7.1   | 1         | 0.42%   |
| 5.6.8   | 1         | 0.42%   |
| 5.6.15  | 1         | 0.42%   |
| 5.5.13  | 1         | 0.42%   |
| 5.4.83  | 1         | 0.42%   |
| 5.4.70  | 1         | 0.42%   |
| 5.4.67  | 1         | 0.42%   |
| 5.4.13  | 1         | 0.42%   |
| 5.4.101 | 1         | 0.42%   |
| 5.3.8   | 1         | 0.42%   |
| 5.3.7   | 1         | 0.42%   |
| 5.17.4  | 1         | 0.42%   |
| 5.17.15 | 1         | 0.42%   |
| 5.16.20 | 1         | 0.42%   |
| 5.16.19 | 1         | 0.42%   |
| 5.16.13 | 1         | 0.42%   |
| 5.16.11 | 1         | 0.42%   |
| 5.16.1  | 1         | 0.42%   |
| 5.16.0  | 1         | 0.42%   |
| 5.15.7  | 1         | 0.42%   |
| 5.15.5  | 1         | 0.42%   |
| 5.15.28 | 1         | 0.42%   |
| 5.15.12 | 1         | 0.42%   |
| 5.15.10 | 1         | 0.42%   |
| 5.14.9  | 1         | 0.42%   |
| 5.14.0  | 1         | 0.42%   |
| 5.13.19 | 1         | 0.42%   |
| 5.12.8  | 1         | 0.42%   |
| 5.12.13 | 1         | 0.42%   |
| 5.12.10 | 1         | 0.42%   |
| 5.11.12 | 1         | 0.42%   |
| 5.11.11 | 1         | 0.42%   |
| 5.10.93 | 1         | 0.42%   |
| 5.10.88 | 1         | 0.42%   |
| 5.10.74 | 1         | 0.42%   |
| 5.10.56 | 1         | 0.42%   |
| 5.10.36 | 1         | 0.42%   |
| 5.10.29 | 1         | 0.42%   |
| 5.10.16 | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 59        | 25.65%  |
| 5.8     | 26        | 11.3%   |
| 5.3     | 26        | 11.3%   |
| 4.15    | 16        | 6.96%   |
| 5.11    | 14        | 6.09%   |
| 5.10    | 14        | 6.09%   |
| 5.0     | 14        | 6.09%   |
| 5.13    | 12        | 5.22%   |
| 5.15    | 11        | 4.78%   |
| 5.16    | 10        | 4.35%   |
| 4.18    | 9         | 3.91%   |
| 5.17    | 5         | 2.17%   |
| 5.12    | 3         | 1.3%    |
| 5.6     | 2         | 0.87%   |
| 5.14    | 2         | 0.87%   |
| 4.19    | 2         | 0.87%   |
| 5.9     | 1         | 0.43%   |
| 5.7     | 1         | 0.43%   |
| 5.5     | 1         | 0.43%   |
| 4.9     | 1         | 0.43%   |
| 4.16    | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 215       | 99.08%  |
| i686   | 2         | 0.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 136       | 61.26%  |
| Unknown    | 34        | 15.32%  |
| KDE5       | 17        | 7.66%   |
| XFCE       | 16        | 7.21%   |
| X-Cinnamon | 8         | 3.6%    |
| MATE       | 2         | 0.9%    |
| KDE4       | 2         | 0.9%    |
| Unity      | 1         | 0.45%   |
| qtile      | 1         | 0.45%   |
| LXQt       | 1         | 0.45%   |
| KDE        | 1         | 0.45%   |
| i3         | 1         | 0.45%   |
| Cinnamon   | 1         | 0.45%   |
| Budgie     | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 177       | 79.02%  |
| Wayland | 22        | 9.82%   |
| Unknown | 22        | 9.82%   |
| Tty     | 3         | 1.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 146       | 66.67%  |
| GDM     | 30        | 13.7%   |
| SDDM    | 16        | 7.31%   |
| GDM3    | 10        | 4.57%   |
| LightDM | 8         | 3.65%   |
| TDM     | 7         | 3.2%    |
| KDM     | 2         | 0.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 175       | 79.19%  |
| Unknown | 31        | 14.03%  |
| en_GB   | 7         | 3.17%   |
| ar_EG   | 3         | 1.36%   |
| ru_RU   | 2         | 0.9%    |
| C       | 2         | 0.9%    |
| de_DE   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 123       | 56.16%  |
| EFI  | 96        | 43.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 187       | 85.39%  |
| Unknown | 11        | 5.02%   |
| Overlay | 8         | 3.65%   |
| Btrfs   | 8         | 3.65%   |
| Xfs     | 3         | 1.37%   |
| Ext3    | 2         | 0.91%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 152       | 70.05%  |
| GPT     | 47        | 21.66%  |
| MBR     | 18        | 8.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 193       | 87.33%  |
| Yes       | 28        | 12.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 119       | 53.85%  |
| Yes       | 102       | 46.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 66        | 30.41%  |
| Dell                        | 61        | 28.11%  |
| Lenovo                      | 50        | 23.04%  |
| ASUSTek Computer            | 13        | 5.99%   |
| Toshiba                     | 6         | 2.76%   |
| Acer                        | 5         | 2.3%    |
| Sony                        | 2         | 0.92%   |
| Packard Bell                | 2         | 0.92%   |
| MSI                         | 2         | 0.92%   |
| Hampoo                      | 2         | 0.92%   |
| Fujitsu                     | 2         | 0.92%   |
| TECNO                       | 1         | 0.46%   |
| Samsung Electronics         | 1         | 0.46%   |
| I-Life Digital Technologies | 1         | 0.46%   |
| Fujitsu Siemens             | 1         | 0.46%   |
| Apple                       | 1         | 0.46%   |
| Alienware                   | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo IdeaPad 520-15IKB 81BF           | 5         | 2.3%    |
| Dell Inspiron 5570                      | 5         | 2.3%    |
| HP ProBook 450 G7                       | 4         | 1.84%   |
| Dell Inspiron 7577                      | 4         | 1.84%   |
| Dell G5 5587                            | 4         | 1.84%   |
| Dell G3 3579                            | 4         | 1.84%   |
| HP ProBook 645 G1                       | 3         | 1.38%   |
| HP Pavilion dv6                         | 3         | 1.38%   |
| HP Laptop 15-da1xxx                     | 3         | 1.38%   |
| Lenovo Y50-70 20378                     | 2         | 0.92%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK   | 2         | 0.92%   |
| Lenovo IdeaPad 310-15IKB 80TV           | 2         | 0.92%   |
| Lenovo G555 0873                        | 2         | 0.92%   |
| HP ZBook 15 G2                          | 2         | 0.92%   |
| HP ProBook 450 G2                       | 2         | 0.92%   |
| HP Pavilion g6                          | 2         | 0.92%   |
| HP Pavilion g4                          | 2         | 0.92%   |
| HP Pavilion dv7                         | 2         | 0.92%   |
| HP Pavilion 15                          | 2         | 0.92%   |
| HP Notebook                             | 2         | 0.92%   |
| HP Laptop 15-bs0xx                      | 2         | 0.92%   |
| HP EliteBook 840 G1                     | 2         | 0.92%   |
| HP EliteBook 745 G3                     | 2         | 0.92%   |
| HP 15                                   | 2         | 0.92%   |
| Hampoo Cherry Trail CR                  | 2         | 0.92%   |
| Dell Latitude E5570                     | 2         | 0.92%   |
| Dell Inspiron N5110                     | 2         | 0.92%   |
| Dell Inspiron N5010                     | 2         | 0.92%   |
| Dell Inspiron N4050                     | 2         | 0.92%   |
| Dell Inspiron 5559                      | 2         | 0.92%   |
| Dell Inspiron 3593                      | 2         | 0.92%   |
| Dell Inspiron 3543                      | 2         | 0.92%   |
| Dell Inspiron 3521                      | 2         | 0.92%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR    | 2         | 0.92%   |
| Toshiba Satellite L850-A894             | 1         | 0.46%   |
| Toshiba Satellite L50-A661              | 1         | 0.46%   |
| Toshiba Satellite C850D-B810            | 1         | 0.46%   |
| Toshiba Satellite C850-B341             | 1         | 0.46%   |
| Toshiba Satellite C660                  | 1         | 0.46%   |
| Toshiba Satellite A300                  | 1         | 0.46%   |
| TECNO WinPad 10A                        | 1         | 0.46%   |
| Sony SVT1121B2EW                        | 1         | 0.46%   |
| Sony SVF15328CXB                        | 1         | 0.46%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV | 1         | 0.46%   |
| Packard Bell EasyNote TJ75              | 1         | 0.46%   |
| Packard Bell EasyNote LX                | 1         | 0.46%   |
| MSI GS65 Stealth Thin 8RE               | 1         | 0.46%   |
| MSI GL62 7QF                            | 1         | 0.46%   |
| Lenovo Z50-70 20354                     | 1         | 0.46%   |
| Lenovo Yoga 300-11IBY 80M0              | 1         | 0.46%   |
| Lenovo Yoga 3 Pro-1370 80HE             | 1         | 0.46%   |
| Lenovo ThinkPad X250 20CM003WMS         | 1         | 0.46%   |
| Lenovo ThinkPad T580 20LAS09100         | 1         | 0.46%   |
| Lenovo ThinkPad T420 4178CXG            | 1         | 0.46%   |
| Lenovo ThinkPad T410 2522N18            | 1         | 0.46%   |
| Lenovo ThinkPad SL410 0616A44           | 1         | 0.46%   |
| Lenovo ThinkPad S1 Yoga 12 20DK001YUK   | 1         | 0.46%   |
| Lenovo ThinkPad L460 20FVS0ER00         | 1         | 0.46%   |
| Lenovo ThinkPad E590 20NB0002AD         | 1         | 0.46%   |
| Lenovo ThinkPad E580 20KS0008AD         | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 35        | 16.13%  |
| Lenovo IdeaPad        | 19        | 8.76%   |
| HP ProBook            | 15        | 6.91%   |
| Lenovo ThinkPad       | 14        | 6.45%   |
| HP Pavilion           | 14        | 6.45%   |
| Dell Latitude         | 13        | 5.99%   |
| HP EliteBook          | 12        | 5.53%   |
| HP Laptop             | 7         | 3.23%   |
| Dell G3               | 7         | 3.23%   |
| Toshiba Satellite     | 6         | 2.76%   |
| Acer Aspire           | 5         | 2.3%    |
| Lenovo Legion         | 4         | 1.84%   |
| HP ZBook              | 4         | 1.84%   |
| Dell G5               | 4         | 1.84%   |
| ASUS VivoBook         | 4         | 1.84%   |
| Packard Bell EasyNote | 2         | 0.92%   |
| Lenovo Yoga           | 2         | 0.92%   |
| Lenovo Y50-70         | 2         | 0.92%   |
| Lenovo G555           | 2         | 0.92%   |
| HP Notebook           | 2         | 0.92%   |
| HP Compaq             | 2         | 0.92%   |
| HP 250                | 2         | 0.92%   |
| HP 15                 | 2         | 0.92%   |
| Hampoo Cherry         | 2         | 0.92%   |
| TECNO WinPad          | 1         | 0.46%   |
| Sony SVT1121B2EW      | 1         | 0.46%   |
| Sony SVF15328CXB      | 1         | 0.46%   |
| Samsung 300E5EV       | 1         | 0.46%   |
| MSI GS65              | 1         | 0.46%   |
| MSI GL62              | 1         | 0.46%   |
| Lenovo Z50-70         | 1         | 0.46%   |
| Lenovo G510           | 1         | 0.46%   |
| Lenovo G50-80         | 1         | 0.46%   |
| Lenovo G50-70         | 1         | 0.46%   |
| Lenovo Flex           | 1         | 0.46%   |
| Lenovo B40-80         | 1         | 0.46%   |
| Lenovo AILZx          | 1         | 0.46%   |
| I-Life Digital ZED    | 1         | 0.46%   |
| HP Pro                | 1         | 0.46%   |
| HP G62                | 1         | 0.46%   |
| HP G60                | 1         | 0.46%   |
| HP ENVY               | 1         | 0.46%   |
| HP 255                | 1         | 0.46%   |
| Fujitsu Siemens AMILO | 1         | 0.46%   |
| Fujitsu LIFEBOOK      | 1         | 0.46%   |
| Fujitsu FMVA06004     | 1         | 0.46%   |
| Dell Venue            | 1         | 0.46%   |
| Dell G15              | 1         | 0.46%   |
| ASUS X580VN           | 1         | 0.46%   |
| ASUS X555LJ           | 1         | 0.46%   |
| ASUS X553MA           | 1         | 0.46%   |
| ASUS X540UA           | 1         | 0.46%   |
| ASUS X455LD           | 1         | 0.46%   |
| ASUS X200MA           | 1         | 0.46%   |
| ASUS N501JW           | 1         | 0.46%   |
| ASUS G53SW            | 1         | 0.46%   |
| ASUS ASUS             | 1         | 0.46%   |
| Apple MacBookPro5     | 1         | 0.46%   |
| Alienware 17          | 1         | 0.46%   |
| Unknown               | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 32        | 14.75%  |
| 2017 | 26        | 11.98%  |
| 2014 | 23        | 10.6%   |
| 2013 | 21        | 9.68%   |
| 2019 | 20        | 9.22%   |
| 2016 | 19        | 8.76%   |
| 2011 | 15        | 6.91%   |
| 2015 | 14        | 6.45%   |
| 2010 | 11        | 5.07%   |
| 2012 | 10        | 4.61%   |
| 2008 | 10        | 4.61%   |
| 2020 | 8         | 3.69%   |
| 2009 | 4         | 1.84%   |
| 2021 | 2         | 0.92%   |
| 2007 | 2         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 217       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 206       | 94.93%  |
| Enabled  | 11        | 5.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 217       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 68        | 31.19%  |
| 16.01-24.0 | 57        | 26.15%  |
| 3.01-4.0   | 47        | 21.56%  |
| 8.01-16.0  | 28        | 12.84%  |
| 1.01-2.0   | 8         | 3.67%   |
| 2.01-3.0   | 7         | 3.21%   |
| 32.01-64.0 | 2         | 0.92%   |
| 24.01-32.0 | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 78        | 32.77%  |
| 1.01-2.0  | 77        | 32.35%  |
| 4.01-8.0  | 38        | 15.97%  |
| 3.01-4.0  | 37        | 15.55%  |
| 0.51-1.0  | 4         | 1.68%   |
| 8.01-16.0 | 3         | 1.26%   |
| 0.01-0.5  | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 127       | 56.7%   |
| 2      | 90        | 40.18%  |
| 3      | 7         | 3.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 119       | 54.59%  |
| Yes       | 99        | 45.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 199       | 91.71%  |
| No        | 18        | 8.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 98.16%  |
| No        | 4         | 1.84%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 177       | 80.45%  |
| No        | 43        | 19.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Egypt   | 217       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Cairo               | 130       | 55.56%  |
| Alexandria          | 25        | 10.68%  |
| Giza                | 17        | 7.26%   |
| Al Mansurah         | 8         | 3.42%   |
| Tanta               | 6         | 2.56%   |
| Awsim               | 4         | 1.71%   |
| Zagazig             | 3         | 1.28%   |
| Helwan              | 3         | 1.28%   |
| Assiut              | 3         | 1.28%   |
| Suez                | 2         | 0.85%   |
| New Cairo           | 2         | 0.85%   |
| Minya               | 2         | 0.85%   |
| Madinat as Sadat    | 2         | 0.85%   |
| Hurghada            | 2         | 0.85%   |
| Edfu                | 2         | 0.85%   |
| Damietta            | 2         | 0.85%   |
| Damanhur            | 2         | 0.85%   |
| Aswan               | 2         | 0.85%   |
| Zefta               | 1         | 0.43%   |
| Talkha              | 1         | 0.43%   |
| Port Said           | 1         | 0.43%   |
| Monufia             | 1         | 0.43%   |
| Mashtul as Suq      | 1         | 0.43%   |
| Luxor               | 1         | 0.43%   |
| Ismailia            | 1         | 0.43%   |
| Heliopolis          | 1         | 0.43%   |
| F??rask??r          | 1         | 0.43%   |
| Diyarb Najm         | 1         | 0.43%   |
| Bani Suwayf         | 1         | 0.43%   |
| Banha               | 1         | 0.43%   |
| Badr                | 1         | 0.43%   |
| Ashmun              | 1         | 0.43%   |
| Al Fayyum           | 1         | 0.43%   |
| Aga                 | 1         | 0.43%   |
| 6th of October City | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 68        | 75     | 22.59%  |
| WDC                       | 57        | 67     | 18.94%  |
| Toshiba                   | 47        | 61     | 15.61%  |
| Samsung Electronics       | 24        | 32     | 7.97%   |
| Kingston                  | 15        | 16     | 4.98%   |
| Unknown                   | 13        | 17     | 4.32%   |
| Crucial                   | 12        | 13     | 3.99%   |
| SK hynix                  | 10        | 10     | 3.32%   |
| Hitachi                   | 9         | 12     | 2.99%   |
| SanDisk                   | 7         | 8      | 2.33%   |
| Micron Technology         | 6         | 6      | 1.99%   |
| HS-SSD-C100               | 6         | 7      | 1.99%   |
| HGST                      | 4         | 4      | 1.33%   |
| LITEONIT                  | 3         | 4      | 1%      |
| LITEON                    | 3         | 5      | 1%      |
| Intel                     | 3         | 3      | 1%      |
| TwinMOS                   | 2         | 2      | 0.66%   |
| Transcend                 | 2         | 2      | 0.66%   |
| UMIS                      | 1         | 1      | 0.33%   |
| Team                      | 1         | 1      | 0.33%   |
| Silicon Motion            | 1         | 1      | 0.33%   |
| Micron/Crucial Technology | 1         | 1      | 0.33%   |
| Lexar                     | 1         | 1      | 0.33%   |
| KIOXIA                    | 1         | 1      | 0.33%   |
| KingSpec                  | 1         | 1      | 0.33%   |
| HUAWEI                    | 1         | 1      | 0.33%   |
| ADATA Technology          | 1         | 1      | 0.33%   |
| A-DATA Technology         | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 30        | 9.8%    |
| Toshiba MQ04ABF100 1TB                   | 11        | 3.59%   |
| Seagate ST2000LM007-1R8174 2TB           | 9         | 2.94%   |
| Toshiba MQ01ABD100 1TB                   | 8         | 2.61%   |
| Samsung NVMe SSD Drive 256GB             | 5         | 1.63%   |
| Kingston SA400S37480G 480GB SSD          | 5         | 1.63%   |
| Kingston SA400S37240G 240GB SSD          | 5         | 1.63%   |
| Crucial CT480BX500SSD1 480GB             | 5         | 1.63%   |
| WDC WD10SPZX-60Z10T0 1TB                 | 4         | 1.31%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 4         | 1.31%   |
| WDC WD10SPZX-24Z10 1TB                   | 3         | 0.98%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 3         | 0.98%   |
| Unknown SD/MMC/MS PRO 128GB              | 3         | 0.98%   |
| Toshiba MQ01ABF050 500GB                 | 3         | 0.98%   |
| Toshiba MK3276GSX 320GB                  | 3         | 0.98%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD      | 3         | 0.98%   |
| Seagate ST750LM022 HN-M750MBB 752GB      | 3         | 0.98%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 3         | 0.98%   |
| Kingston SA400S37120G 120GB SSD          | 3         | 0.98%   |
| Hitachi HTS547575A9E384 752GB            | 3         | 0.98%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 2         | 0.65%   |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 2         | 0.65%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 2         | 0.65%   |
| WDC WD5000LPCX-24C6HT0 500GB             | 2         | 0.65%   |
| WDC WD3200BPVT-75JJ5T0 320GB             | 2         | 0.65%   |
| WDC WD1600BEVT-24A23T0 160GB             | 2         | 0.65%   |
| WDC WD10SPZX-75Z10T3 1TB                 | 2         | 0.65%   |
| WDC WD10SPZX-75Z10T1 1TB                 | 2         | 0.65%   |
| WDC WD10SPZX-21Z10T0 1TB                 | 2         | 0.65%   |
| WDC WD10SPZX-00Z10T0 1TB                 | 2         | 0.65%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 2         | 0.65%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB     | 2         | 0.65%   |
| Unknown MMC Card  64GB                   | 2         | 0.65%   |
| Unknown MMC Card  32GB                   | 2         | 0.65%   |
| TwinMOS SSD 128GB                        | 2         | 0.65%   |
| Toshiba MQ01ACF032 320GB                 | 2         | 0.65%   |
| Toshiba MK3275GSX 320GB                  | 2         | 0.65%   |
| Toshiba MK3256GSY 320GB                  | 2         | 0.65%   |
| SK hynix BC501 NVMe 256GB                | 2         | 0.65%   |
| Seagate ST9500420AS 500GB                | 2         | 0.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 0.65%   |
| Seagate ST1000LX015-1U7172 1TB           | 2         | 0.65%   |
| Seagate ST1000LM014-SSHD-8GB             | 2         | 0.65%   |
| SanDisk X600 M.2 2280 SATA 128GB SSD     | 2         | 0.65%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD      | 2         | 0.65%   |
| Samsung SSD 860 EVO 500GB                | 2         | 0.65%   |
| Samsung NVMe SSD Drive 512GB             | 2         | 0.65%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB SSD | 2         | 0.65%   |
| Intel SSDSC2BF180A4H 180GB               | 2         | 0.65%   |
| HS-SSD-C100 SSD 240G                     | 2         | 0.65%   |
| HS-SSD-C100 240G                         | 2         | 0.65%   |
| Hitachi HTS545050B9SA02 500GB            | 2         | 0.65%   |
| Crucial CT500MX500SSD4 500GB             | 2         | 0.65%   |
| Crucial CT240BX500SSD1 240GB             | 2         | 0.65%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1         | 0.33%   |
| WDC WD800BEVS-07RST0 80GB                | 1         | 0.33%   |
| WDC WD5000LPVX-60V0TT0 500GB             | 1         | 0.33%   |
| WDC WD5000LPLX-08ZNTT0 500GB             | 1         | 0.33%   |
| WDC WD5000BUDT-63G8FY0 500GB             | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 68        | 75     | 38.42%  |
| WDC                 | 50        | 60     | 28.25%  |
| Toshiba             | 42        | 54     | 23.73%  |
| Hitachi             | 9         | 12     | 5.08%   |
| HGST                | 4         | 4      | 2.26%   |
| Unknown             | 3         | 3      | 1.69%   |
| Samsung Electronics | 1         | 2      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 15        | 16     | 19.23%  |
| Samsung Electronics | 12        | 13     | 15.38%  |
| Crucial             | 11        | 12     | 14.1%   |
| SanDisk             | 6         | 7      | 7.69%   |
| WDC                 | 5         | 5      | 6.41%   |
| Micron Technology   | 5         | 5      | 6.41%   |
| SK hynix            | 4         | 4      | 5.13%   |
| LITEONIT            | 3         | 4      | 3.85%   |
| LITEON              | 3         | 5      | 3.85%   |
| Intel               | 3         | 3      | 3.85%   |
| TwinMOS             | 2         | 2      | 2.56%   |
| Transcend           | 2         | 2      | 2.56%   |
| Toshiba             | 2         | 3      | 2.56%   |
| HS-SSD-C100         | 2         | 3      | 2.56%   |
| Team                | 1         | 1      | 1.28%   |
| Lexar               | 1         | 1      | 1.28%   |
| KingSpec            | 1         | 1      | 1.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 169       | 210    | 58.08%  |
| SSD     | 74        | 87     | 25.43%  |
| NVMe    | 34        | 40     | 11.68%  |
| MMC     | 9         | 12     | 3.09%   |
| Unknown | 5         | 5      | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 202       | 298    | 81.12%  |
| NVMe | 34        | 40     | 13.65%  |
| MMC  | 9         | 12     | 3.61%   |
| SAS  | 4         | 4      | 1.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 122       | 154    | 50.41%  |
| 0.51-1.0   | 107       | 130    | 44.21%  |
| 1.01-2.0   | 13        | 13     | 5.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 29.52%  |
| 251-500        | 47        | 20.7%   |
| 501-1000       | 33        | 14.54%  |
| 51-100         | 29        | 12.78%  |
| 1001-2000      | 19        | 8.37%   |
| 21-50          | 16        | 7.05%   |
| 1-20           | 11        | 4.85%   |
| Unknown        | 3         | 1.32%   |
| More than 3000 | 1         | 0.44%   |
| 2001-3000      | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 87        | 37.83%  |
| 21-50     | 47        | 20.43%  |
| 101-250   | 38        | 16.52%  |
| 51-100    | 27        | 11.74%  |
| 501-1000  | 13        | 5.65%   |
| 251-500   | 12        | 5.22%   |
| Unknown   | 3         | 1.3%    |
| 1001-2000 | 2         | 0.87%   |
| 2001-3000 | 1         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 2      | 13.33%  |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 6.67%   |
| WDC WD5000LPVX-60V0TT0 500GB                        | 1         | 1      | 6.67%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 6.67%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 6.67%   |
| Seagate ST95005620AS 500GB                          | 1         | 2      | 6.67%   |
| Seagate ST9320328CS 320GB                           | 1         | 2      | 6.67%   |
| Seagate ST2000LM015-2E81 2TB                        | 1         | 1      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 6.67%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 6.67%   |
| Hitachi HTS543225L9A300 250GB                       | 1         | 1      | 6.67%   |
| A-DATA Technology IM2P33F3 NVMe 256GB               | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 8      | 40%     |
| WDC               | 3         | 3      | 20%     |
| Micron Technology | 2         | 2      | 13.33%  |
| SK hynix          | 1         | 1      | 6.67%   |
| Intel             | 1         | 1      | 6.67%   |
| Hitachi           | 1         | 1      | 6.67%   |
| A-DATA Technology | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 8      | 60%     |
| WDC     | 3         | 3      | 30%     |
| Hitachi | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 12     | 66.67%  |
| SSD  | 4         | 4      | 26.67%  |
| NVMe | 1         | 1      | 6.67%   |

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
| Detected | 152       | 242    | 67.26%  |
| Works    | 59        | 95     | 26.11%  |
| Malfunc  | 15        | 17     | 6.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 183       | 75.62%  |
| AMD                          | 21        | 8.68%   |
| Samsung Electronics          | 13        | 5.37%   |
| SK hynix                     | 6         | 2.48%   |
| Toshiba America Info Systems | 5         | 2.07%   |
| SanDisk                      | 3         | 1.24%   |
| Micron/Crucial Technology    | 2         | 0.83%   |
| ADATA Technology             | 2         | 0.83%   |
| VIA Technologies             | 1         | 0.41%   |
| Union Memory (Shenzhen)      | 1         | 0.41%   |
| Silicon Motion               | 1         | 0.41%   |
| Shenzhen Longsys Electronics | 1         | 0.41%   |
| Nvidia                       | 1         | 0.41%   |
| Micron Technology            | 1         | 0.41%   |
| KIOXIA                       | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 36        | 14.52%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 18        | 7.26%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 17        | 6.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 15        | 6.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 14        | 5.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 14        | 5.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 11        | 4.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 11        | 4.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 9         | 3.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 9         | 3.63%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 8         | 3.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 6         | 2.42%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 2.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 2.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 2.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 5         | 2.02%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 4         | 1.61%   |
| Samsung NVMe SSD Controller 980                                                        | 4         | 1.61%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 3         | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 1.21%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 3         | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.21%   |
| SK hynix Gold P31 SSD                                                                  | 2         | 0.81%   |
| SanDisk PC SN520 NVMe SSD                                                              | 2         | 0.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.81%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 0.81%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 2         | 0.81%   |
| ADATA Non-Volatile memory controller                                                   | 2         | 0.81%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 1         | 0.4%    |
| VIA VT8237A SATA 2-Port Controller                                                     | 1         | 0.4%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.4%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.4%    |
| SK hynix BC511                                                                         | 1         | 0.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.4%    |
| Shenzhen Longsys Non-Volatile memory controller                                        | 1         | 0.4%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.4%    |
| Nvidia MCP79 SATA Controller                                                           | 1         | 0.4%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.4%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 0.4%    |
| Micron Non-Volatile memory controller                                                  | 1         | 0.4%    |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 0.4%    |
| Intel SATA Controller [RAID mode]                                                      | 1         | 0.4%    |
| Intel Mobile PM965/GM965 PT IDER Controller                                            | 1         | 0.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 1         | 0.4%    |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 0.4%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.4%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 0.4%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 0.4%    |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 186       | 76.23%  |
| NVMe | 36        | 14.75%  |
| RAID | 12        | 4.92%   |
| IDE  | 10        | 4.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 195       | 89.86%  |
| AMD    | 22        | 10.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz            | 13        | 5.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 11        | 5.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 7         | 3.23%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 7         | 3.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz           | 6         | 2.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 5         | 2.3%    |
| Intel Core i7-6500U CPU @ 2.50GHz            | 4         | 1.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 4         | 1.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 4         | 1.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 4         | 1.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 3         | 1.38%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 3         | 1.38%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz           | 3         | 1.38%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 3         | 1.38%   |
| Intel Core i7-2630QM CPU @ 2.00GHz           | 3         | 1.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 3         | 1.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 3         | 1.38%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 3         | 1.38%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 3         | 1.38%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 3         | 1.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 3         | 1.38%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 3         | 1.38%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 2         | 0.92%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz           | 2         | 0.92%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz           | 2         | 0.92%   |
| Intel Core i7-2670QM CPU @ 2.20GHz           | 2         | 0.92%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 2         | 0.92%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 2         | 0.92%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 2         | 0.92%   |
| Intel Core i5-4200M CPU @ 2.50GHz            | 2         | 0.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 2         | 0.92%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 2         | 0.92%   |
| Intel Core i5 CPU M 520 @ 2.40GHz            | 2         | 0.92%   |
| Intel Core i3-7020U CPU @ 2.30GHz            | 2         | 0.92%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 2         | 0.92%   |
| Intel Core i3-2330M CPU @ 2.20GHz            | 2         | 0.92%   |
| Intel Core i3 CPU M 350 @ 2.27GHz            | 2         | 0.92%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz         | 2         | 0.92%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz            | 2         | 0.92%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G | 2         | 0.92%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 0.92%   |
| Intel Processor 5Y70 CPU @ 1.10GHz           | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz  | 1         | 0.46%   |
| Intel Pentium CPU P6200 @ 2.13GHz            | 1         | 0.46%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.46%   |
| Intel Pentium CPU N3540 @ 2.16GHz            | 1         | 0.46%   |
| Intel Pentium 3560Y @ 1.20GHz                | 1         | 0.46%   |
| Intel Genuine CPU T2300 @ 1.66GHz            | 1         | 0.46%   |
| Intel Core i9-8950HK CPU @ 2.90GHz           | 1         | 0.46%   |
| Intel Core i7-8665U CPU @ 1.90GHz            | 1         | 0.46%   |
| Intel Core i7-5600U CPU @ 2.60GHz            | 1         | 0.46%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz           | 1         | 0.46%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz           | 1         | 0.46%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.46%   |
| Intel Core i7-4600M CPU @ 2.90GHz            | 1         | 0.46%   |
| Intel Core i7-4500U CPU @ 1.80GHz            | 1         | 0.46%   |
| Intel Core i7-3632QM CPU @ 2.20GHz           | 1         | 0.46%   |
| Intel Core i7-3612QM CPU @ 2.10GHz           | 1         | 0.46%   |
| Intel Core i7-3610QM CPU @ 2.30GHz           | 1         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 92        | 42.4%   |
| Intel Core i5           | 58        | 26.73%  |
| Intel Core i3           | 19        | 8.76%   |
| Intel Core 2 Duo        | 7         | 3.23%   |
| Intel Celeron           | 5         | 2.3%    |
| Intel Pentium           | 4         | 1.84%   |
| Intel Atom              | 4         | 1.84%   |
| Other                   | 3         | 1.38%   |
| AMD PRO A10             | 3         | 1.38%   |
| AMD A8                  | 3         | 1.38%   |
| Intel Pentium Dual-Core | 2         | 0.92%   |
| AMD Ryzen 7             | 2         | 0.92%   |
| AMD Ryzen 5             | 2         | 0.92%   |
| AMD E2                  | 2         | 0.92%   |
| AMD E1                  | 2         | 0.92%   |
| AMD Athlon II Dual-Core | 2         | 0.92%   |
| AMD A6                  | 2         | 0.92%   |
| AMD A4                  | 2         | 0.92%   |
| Intel Genuine           | 1         | 0.46%   |
| Intel Core i9           | 1         | 0.46%   |
| AMD E                   | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 119       | 54.84%  |
| 4      | 77        | 35.48%  |
| 6      | 17        | 7.83%   |
| 8      | 3         | 1.38%   |
| 1      | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 217       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 180       | 82.95%  |
| 1      | 37        | 17.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 210       | 96.33%  |
| Unknown        | 7         | 3.21%   |
| 32-bit         | 1         | 0.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 20.18%  |
| 0x206a7    | 17        | 7.62%   |
| 0x306c3    | 14        | 6.28%   |
| 0x806ea    | 13        | 5.83%   |
| 0x40651    | 13        | 5.83%   |
| 0x306a9    | 13        | 5.83%   |
| 0x906ea    | 12        | 5.38%   |
| 0x806e9    | 12        | 5.38%   |
| 0x806ec    | 10        | 4.48%   |
| 0x306d4    | 9         | 4.04%   |
| 0x406e3    | 7         | 3.14%   |
| 0x906e9    | 5         | 2.24%   |
| 0x1067a    | 5         | 2.24%   |
| 0x30678    | 4         | 1.79%   |
| 0x20655    | 4         | 1.79%   |
| 0xa0652    | 3         | 1.35%   |
| 0x706e5    | 3         | 1.35%   |
| 0x6fd      | 3         | 1.35%   |
| 0x406c3    | 3         | 1.35%   |
| 0x20652    | 3         | 1.35%   |
| 0x06006705 | 3         | 1.35%   |
| 0x806eb    | 2         | 0.9%    |
| 0x506e3    | 2         | 0.9%    |
| 0x06006704 | 2         | 0.9%    |
| 0x0600111f | 2         | 0.9%    |
| 0x806c1    | 1         | 0.45%   |
| 0x6e8      | 1         | 0.45%   |
| 0x506c9    | 1         | 0.45%   |
| 0x106e5    | 1         | 0.45%   |
| 0x10676    | 1         | 0.45%   |
| 0x0a50000c | 1         | 0.45%   |
| 0x08600106 | 1         | 0.45%   |
| 0x08108102 | 1         | 0.45%   |
| 0x07030106 | 1         | 0.45%   |
| 0x0600611a | 1         | 0.45%   |
| 0x06006110 | 1         | 0.45%   |
| 0x06003109 | 1         | 0.45%   |
| 0x05000119 | 1         | 0.45%   |
| 0x05000029 | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 70        | 32.26%  |
| Haswell     | 32        | 14.75%  |
| SandyBridge | 18        | 8.29%   |
| IvyBridge   | 14        | 6.45%   |
| Skylake     | 12        | 5.53%   |
| Broadwell   | 11        | 5.07%   |
| Westmere    | 10        | 4.61%   |
| Silvermont  | 8         | 3.69%   |
| Excavator   | 8         | 3.69%   |
| Penryn      | 6         | 2.76%   |
| CometLake   | 4         | 1.84%   |
| Piledriver  | 3         | 1.38%   |
| IceLake     | 3         | 1.38%   |
| Core        | 3         | 1.38%   |
| Zen 2       | 2         | 0.92%   |
| Puma        | 2         | 0.92%   |
| K10         | 2         | 0.92%   |
| Bobcat      | 2         | 0.92%   |
| Zen+        | 1         | 0.46%   |
| Zen 3       | 1         | 0.46%   |
| TigerLake   | 1         | 0.46%   |
| Steamroller | 1         | 0.46%   |
| P6          | 1         | 0.46%   |
| Nehalem     | 1         | 0.46%   |
| Goldmont    | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 179       | 53.75%  |
| Nvidia           | 80        | 24.02%  |
| AMD              | 73        | 21.92%  |
| VIA Technologies | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 19        | 5.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 5.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 4.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 4.46%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 13        | 3.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 3.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 3.57%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 12        | 3.57%   |
| Intel HD Graphics 620                                                                    | 10        | 2.98%   |
| Intel HD Graphics 5500                                                                   | 10        | 2.98%   |
| Nvidia GM108M [GeForce MX130]                                                            | 9         | 2.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 2.38%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 2.08%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 2.08%   |
| Intel HD Graphics 630                                                                    | 6         | 1.79%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 1.49%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.49%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.19%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 1.19%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.89%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.89%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.89%   |
| Intel HD Graphics 530                                                                    | 3         | 0.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.89%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 3         | 0.89%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.89%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 3         | 0.89%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 3         | 0.89%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.6%    |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.6%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.6%    |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 2         | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.6%    |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 2         | 0.6%    |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.6%    |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 2         | 0.6%    |
| AMD Topaz PRO [Radeon R5 M255]                                                           | 2         | 0.6%    |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 0.6%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.6%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.6%    |
| AMD Renoir                                                                               | 2         | 0.6%    |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 0.6%    |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 2         | 0.6%    |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 0.6%    |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 2         | 0.6%    |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.3%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.3%    |
| Nvidia TU117M                                                                            | 1         | 0.3%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.3%    |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.3%    |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.3%    |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 70        | 32.11%  |
| 1 x Intel      | 66        | 30.28%  |
| Intel + AMD    | 44        | 20.18%  |
| 1 x AMD        | 26        | 11.93%  |
| 1 x Nvidia     | 8         | 3.67%   |
| AMD + Nvidia   | 2         | 0.92%   |
| 2 x AMD        | 1         | 0.46%   |
| 1 x VIA        | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 181       | 81.9%   |
| Proprietary | 36        | 16.29%  |
| Unknown     | 4         | 1.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 50.9%   |
| 1.01-2.0   | 43        | 19.37%  |
| 3.01-4.0   | 34        | 15.32%  |
| 0.01-0.5   | 15        | 6.76%   |
| 0.51-1.0   | 14        | 6.31%   |
| 5.01-6.0   | 3         | 1.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 45        | 20.36%  |
| LG Display              | 44        | 19.91%  |
| Chimei Innolux          | 38        | 17.19%  |
| AU Optronics            | 36        | 16.29%  |
| Samsung Electronics     | 27        | 12.22%  |
| Chi Mei Optoelectronics | 11        | 4.98%   |
| Lenovo                  | 5         | 2.26%   |
| Dell                    | 4         | 1.81%   |
| InfoVision              | 3         | 1.36%   |
| Philips                 | 2         | 0.9%    |
| PANDA                   | 2         | 0.9%    |
| Panasonic               | 1         | 0.45%   |
| LG Philips              | 1         | 0.45%   |
| CPT                     | 1         | 0.45%   |
| Apple                   | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 8         | 3.62%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 6         | 2.71%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 5         | 2.26%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 4         | 1.81%   |
| BOE LCD Monitor BOE07B0 1920x1080 344x194mm 15.5-inch                    | 4         | 1.81%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 1.81%   |
| Samsung Electronics LCD Monitor SEC3151 1366x768 344x194mm 15.5-inch     | 3         | 1.36%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 1.36%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 1.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 1.36%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch          | 3         | 1.36%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 1.36%   |
| BOE LCD Monitor BOE06C6 1920x1080 344x194mm 15.5-inch                    | 3         | 1.36%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 3         | 1.36%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch     | 2         | 0.9%    |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch    | 2         | 0.9%    |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 2         | 0.9%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.9%    |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                  | 2         | 0.9%    |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15C2 1920x1080 344x194mm 15.5-inch         | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 0.9%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.9%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 2         | 0.9%    |
| BOE LCD Monitor BOE0826 1920x1080 344x193mm 15.5-inch                    | 2         | 0.9%    |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 2         | 0.9%    |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 2         | 0.9%    |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 2         | 0.9%    |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.9%    |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch      | 1         | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.45%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 1         | 0.45%   |
| Samsung Electronics S22B300 SAM08AB 1920x1080 477x268mm 21.5-inch        | 1         | 0.45%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch         | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 309x174mm 14.0-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC374E 1366x768 344x193mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4247 1366x768 344x194mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC3854 1920x1080 382x215mm 17.3-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC3147 1920x1080 276x155mm 12.5-inch    | 1         | 0.45%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch       | 1         | 0.45%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 0.45%   |
| Philips 225PL PHL088D 1680x1050 474x296mm 22.0-inch                      | 1         | 0.45%   |
| Philips 191EW PHLC02A 1366x768 413x234mm 18.7-inch                       | 1         | 0.45%   |
| PANDA LCD Monitor NCP0056 1920x1080 309x174mm 14.0-inch                  | 1         | 0.45%   |
| PANDA LCD Monitor NCP0054 1920x1080 344x194mm 15.5-inch                  | 1         | 0.45%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 1         | 0.45%   |
| LG Philips LCD Monitor LPL017D 1280x800 331x207mm 15.4-inch              | 1         | 0.45%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch            | 1         | 0.45%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch              | 1         | 0.45%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 110       | 50.46%  |
| 1920x1080 (FHD)    | 84        | 38.53%  |
| 1600x900 (HD+)     | 7         | 3.21%   |
| 1280x800 (WXGA)    | 6         | 2.75%   |
| 3840x2160 (4K)     | 4         | 1.83%   |
| 1440x900 (WXGA+)   | 4         | 1.83%   |
| 1680x1050 (WSXGA+) | 2         | 0.92%   |
| 3200x1800 (QHD+)   | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 148       | 66.97%  |
| 14      | 30        | 13.57%  |
| 13      | 14        | 6.33%   |
| 17      | 7         | 3.17%   |
| 12      | 6         | 2.71%   |
| 18      | 3         | 1.36%   |
| 27      | 2         | 0.9%    |
| 22      | 2         | 0.9%    |
| 21      | 2         | 0.9%    |
| 19      | 2         | 0.9%    |
| 11      | 2         | 0.9%    |
| 24      | 1         | 0.45%   |
| 23      | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 188       | 85.84%  |
| 201-300     | 11        | 5.02%   |
| 401-500     | 8         | 3.65%   |
| 351-400     | 7         | 3.2%    |
| 501-600     | 4         | 1.83%   |
| Unknown     | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 200       | 94.79%  |
| 16/10   | 10        | 4.74%   |
| Unknown | 1         | 0.47%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 145       | 65.91%  |
| 81-90          | 40        | 18.18%  |
| 61-70          | 6         | 2.73%   |
| 121-130        | 6         | 2.73%   |
| 201-250        | 5         | 2.27%   |
| 71-80          | 3         | 1.36%   |
| 151-200        | 3         | 1.36%   |
| 91-100         | 3         | 1.36%   |
| 51-60          | 2         | 0.91%   |
| 301-350        | 2         | 0.91%   |
| 141-150        | 2         | 0.91%   |
| 251-300        | 1         | 0.45%   |
| 131-140        | 1         | 0.45%   |
| Unknown        | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 100       | 46.08%  |
| 121-160       | 89        | 41.01%  |
| 51-100        | 24        | 11.06%  |
| More than 240 | 2         | 0.92%   |
| 161-240       | 1         | 0.46%   |
| Unknown       | 1         | 0.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 204       | 92.73%  |
| 2     | 12        | 5.45%   |
| 0     | 3         | 1.36%   |
| 3     | 1         | 0.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 155       | 41.67%  |
| Intel                             | 100       | 26.88%  |
| Qualcomm Atheros                  | 59        | 15.86%  |
| Broadcom                          | 27        | 7.26%   |
| Broadcom Limited                  | 7         | 1.88%   |
| Ralink                            | 6         | 1.61%   |
| Huawei Technologies               | 4         | 1.08%   |
| Samsung Electronics               | 2         | 0.54%   |
| Ralink Technology                 | 2         | 0.54%   |
| MediaTek                          | 2         | 0.54%   |
| Marvell Technology Group          | 2         | 0.54%   |
| VIA Technologies                  | 1         | 0.27%   |
| TP-Link                           | 1         | 0.27%   |
| Nvidia                            | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| Dell                              | 1         | 0.27%   |
| ASIX Electronics                  | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93        | 21.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 56        | 13.08%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 24        | 5.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 12        | 2.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 2.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 2.1%    |
| Intel Wireless 8265 / 8275                                        | 9         | 2.1%    |
| Intel Wireless 7260                                               | 9         | 2.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 1.87%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 1.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.64%   |
| Intel Wireless 8260                                               | 7         | 1.64%   |
| Intel Wireless 7265                                               | 7         | 1.64%   |
| Intel Wireless 3160                                               | 6         | 1.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 1.17%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 1.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.93%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 0.93%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.7%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 3         | 0.7%    |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.7%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 3         | 0.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 3         | 0.7%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.47%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.47%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.47%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.47%   |
| Intel PRODUCT_MODEM                                               | 2         | 0.47%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.47%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.47%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.47%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.47%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2         | 0.47%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 2         | 0.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.23%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.23%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.23%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.23%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 95        | 43.38%  |
| Qualcomm Atheros      | 51        | 23.29%  |
| Realtek Semiconductor | 32        | 14.61%  |
| Broadcom              | 24        | 10.96%  |
| Ralink                | 6         | 2.74%   |
| Broadcom Limited      | 6         | 2.74%   |
| Ralink Technology     | 2         | 0.91%   |
| TP-Link               | 1         | 0.46%   |
| MediaTek              | 1         | 0.46%   |
| Dell                  | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 24        | 10.91%  |
| Intel Cannon Lake PCH CNVi WiFi                                               | 12        | 5.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 10        | 4.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 9         | 4.09%   |
| Intel Wireless 8265 / 8275                                                    | 9         | 4.09%   |
| Intel Wireless 7260                                                           | 9         | 4.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 8         | 3.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 8         | 3.64%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 8         | 3.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 8         | 3.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 7         | 3.18%   |
| Intel Wireless 8260                                                           | 7         | 3.18%   |
| Intel Wireless 7265                                                           | 7         | 3.18%   |
| Intel Wireless 3160                                                           | 6         | 2.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 5         | 2.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 5         | 2.27%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 4         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 4         | 1.82%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 4         | 1.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 3         | 1.36%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 3         | 1.36%   |
| Intel Centrino Advanced-N 6235                                                | 3         | 1.36%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 3         | 1.36%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 3         | 1.36%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 2         | 0.91%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 2         | 0.91%   |
| Ralink RT5370 Wireless Adapter                                                | 2         | 0.91%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 2         | 0.91%   |
| Intel PRODUCT_MODEM                                                           | 2         | 0.91%   |
| Intel Centrino Wireless-N 2230                                                | 2         | 0.91%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 2         | 0.91%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 0.91%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                    | 2         | 0.91%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                        | 1         | 0.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 1         | 0.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.45%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 1         | 0.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 0.45%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 1         | 0.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 0.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 0.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 0.45%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.45%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                           | 1         | 0.45%   |
| Intel Wireless-AC 9260                                                        | 1         | 0.45%   |
| Intel Wireless 3165                                                           | 1         | 0.45%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 0.45%   |
| Intel Wi-Fi 6 AX200                                                           | 1         | 0.45%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 1         | 0.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 0.45%   |
| Intel Centrino Wireless-N 2200                                                | 1         | 0.45%   |
| Dell Wireless 5808e Gobi?????? 4G LTE Mobile Broadband Card                   | 1         | 0.45%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                   | 1         | 0.45%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1         | 0.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 149       | 72.68%  |
| Intel                    | 30        | 14.63%  |
| Qualcomm Atheros         | 12        | 5.85%   |
| Broadcom                 | 3         | 1.46%   |
| Samsung Electronics      | 2         | 0.98%   |
| Marvell Technology Group | 2         | 0.98%   |
| Huawei Technologies      | 2         | 0.98%   |
| VIA Technologies         | 1         | 0.49%   |
| Nvidia                   | 1         | 0.49%   |
| MediaTek                 | 1         | 0.49%   |
| Broadcom Limited         | 1         | 0.49%   |
| ASIX Electronics         | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93        | 45.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 56        | 27.32%  |
| Intel Ethernet Connection I217-LM                                 | 5         | 2.44%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.95%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.46%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.98%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.98%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.98%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.98%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.98%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 2         | 0.98%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.49%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.49%   |
| MediaTek TECNO SPARK 3                                            | 1         | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.49%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.49%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.49%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.49%   |
| Huawei E353/E3131                                                 | 1         | 0.49%   |
| Huawei COL-L29                                                    | 1         | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.49%   |
| Broadcom Limited NetXtreme BCM5762 Gigabit Ethernet PCIe          | 1         | 0.49%   |
| ASIX AX88772B                                                     | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 213       | 51.33%  |
| Ethernet | 199       | 47.95%  |
| Modem    | 3         | 0.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 182       | 82.73%  |
| Ethernet | 38        | 17.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 194       | 89.4%   |
| 1     | 17        | 7.83%   |
| 0     | 4         | 1.84%   |
| 3     | 2         | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 217       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 43.82%  |
| Qualcomm Atheros Communications | 31        | 17.42%  |
| Realtek Semiconductor           | 21        | 11.8%   |
| Broadcom                        | 16        | 8.99%   |
| Foxconn / Hon Hai               | 6         | 3.37%   |
| Toshiba                         | 5         | 2.81%   |
| Lite-On Technology              | 5         | 2.81%   |
| Ralink                          | 4         | 2.25%   |
| IMC Networks                    | 4         | 2.25%   |
| Dell                            | 3         | 1.69%   |
| Cambridge Silicon Radio         | 2         | 1.12%   |
| MediaTek                        | 1         | 0.56%   |
| Hewlett-Packard                 | 1         | 0.56%   |
| Apple                           | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 41        | 23.03%  |
| Qualcomm Atheros  Bluetooth Device                     | 22        | 12.36%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 15        | 8.43%   |
| Realtek Bluetooth Radio                                | 11        | 6.18%   |
| Intel Bluetooth Device                                 | 11        | 6.18%   |
| Realtek  Bluetooth 4.2 Adapter                         | 5         | 2.81%   |
| Ralink RT3290 Bluetooth                                | 4         | 2.25%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 4         | 2.25%   |
| Broadcom BCM43142 Bluetooth 4.0                        | 4         | 2.25%   |
| Realtek RTL8723B Bluetooth                             | 3         | 1.69%   |
| Qualcomm Atheros AR9462 Bluetooth                      | 3         | 1.69%   |
| Qualcomm Atheros AR3011 Bluetooth                      | 3         | 1.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth             | 3         | 1.69%   |
| Intel Wireless-AC 3168 Bluetooth                       | 3         | 1.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter       | 3         | 1.69%   |
| Dell Wireless 365 Bluetooth                            | 3         | 1.69%   |
| Broadcom HP Portable Bumble Bee                        | 3         | 1.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                  | 2         | 1.12%   |
| Lite-On Bluetooth Device                               | 2         | 1.12%   |
| IMC Networks Bluetooth Radio                           | 2         | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                     | 2         | 1.12%   |
| Foxconn / Hon Hai BCM20702A0                           | 2         | 1.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)    | 2         | 1.12%   |
| Broadcom HP Portable SoftSailing                       | 2         | 1.12%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                   | 2         | 1.12%   |
| Broadcom BCM2045B (BDC-2.1)                            | 2         | 1.12%   |
| Toshiba RT Bluetooth Radio                             | 1         | 0.56%   |
| Toshiba Integrated Bluetooth HCI                       | 1         | 0.56%   |
| Toshiba Bluetooth USB Host Controller                  | 1         | 0.56%   |
| Toshiba Bluetooth Device                               | 1         | 0.56%   |
| Toshiba Askey Bluetooth Module                         | 1         | 0.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                | 1         | 0.56%   |
| Realtek RTL8821A Bluetooth                             | 1         | 0.56%   |
| Qualcomm Atheros Bluetooth USB Host Controller         | 1         | 0.56%   |
| MediaTek MT7630e Bluetooth Adapter                     | 1         | 0.56%   |
| Intel AX200 Bluetooth                                  | 1         | 0.56%   |
| IMC Networks Bluetooth Device                          | 1         | 0.56%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                       | 1         | 0.56%   |
| Foxconn / Hon Hai BCM43142A0                           | 1         | 0.56%   |
| Foxconn / Hon Hai Acer Bluetooth module                | 1         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth Device                   | 1         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                      | 1         | 0.56%   |
| Broadcom BCM20702A0                                    | 1         | 0.56%   |
| Apple Bluetooth Host Controller                        | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 188       | 74.6%   |
| Nvidia           | 33        | 13.1%   |
| AMD              | 29        | 11.51%  |
| VIA Technologies | 1         | 0.4%    |
| Logitech         | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 40        | 12.9%   |
| Intel 8 Series HD Audio Controller                                                                | 18        | 5.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 17        | 5.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 16        | 5.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 5.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 5.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 4.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 3.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 3.55%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 3.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 3.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 2.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 2.58%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 2.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 2.58%   |
| AMD FCH Azalia Controller                                                                         | 7         | 2.26%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.94%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.61%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.29%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 1.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.97%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.97%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.65%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.65%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.65%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.32%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.32%   |
| Nvidia stereo controller                                                                          | 1         | 0.32%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.32%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.32%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.32%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.32%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.32%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.32%   |
| Nvidia Audio device                                                                               | 1         | 0.32%   |
| Logitech USB Headset                                                                              | 1         | 0.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.32%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.32%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.32%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.32%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 1         | 0.32%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 0.32%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 43        | 35.54%  |
| Samsung Electronics | 35        | 28.93%  |
| Micron Technology   | 12        | 9.92%   |
| Ramaxel Technology  | 9         | 7.44%   |
| Kingston            | 6         | 4.96%   |
| Crucial             | 5         | 4.13%   |
| Unknown             | 4         | 3.31%   |
| Nanya Technology    | 3         | 2.48%   |
| Unknown (ABCD)      | 1         | 0.83%   |
| G.Skill             | 1         | 0.83%   |
| Elpida              | 1         | 0.83%   |
| Axiom               | 1         | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 7         | 5.65%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 5         | 4.03%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 2.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 2.42%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 3         | 2.42%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 1.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.61%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 2         | 1.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 1.61%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 2         | 1.61%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 1.61%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.61%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 1.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.61%   |
| Ramaxel RAM RMSA3260NA78HAF-2400 8GB SODIMM DDR4 2400MT/s           | 2         | 1.61%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 2         | 1.61%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 2         | 1.61%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.81%   |
| Unknown RAM Module 8GB SODIMM DDR3                                  | 1         | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 0.81%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.81%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 1         | 0.81%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.81%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 3200MT/s                     | 1         | 0.81%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                     | 1         | 0.81%   |
| SK hynix RAM Module 4GB DIMM DDR3 1600MT/s                          | 1         | 0.81%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                     | 1         | 0.81%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2133MT/s                    | 1         | 0.81%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.81%   |
| SK hynix RAM HMT425S2AFR6R-PB 2GB SODIMM DDR3 1333MT/s              | 1         | 0.81%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.81%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s              | 1         | 0.81%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 1         | 0.81%   |
| SK hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 1334MT/s           | 1         | 0.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 0.81%   |
| SK hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s           | 1         | 0.81%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.81%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.81%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 0.81%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.81%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2400MT/s                     | 1         | 0.81%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2133MT/s                     | 1         | 0.81%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 1         | 0.81%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 0.81%   |
| Samsung RAM M471B5273EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.81%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.81%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.81%   |
| Samsung RAM M471B5173BH0-CH9 4GB SODIMM DDR3 1334MT/s               | 1         | 0.81%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.81%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 0.81%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s               | 1         | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 54        | 55.67%  |
| DDR3   | 38        | 39.18%  |
| LPDDR4 | 2         | 2.06%   |
| SDRAM  | 1         | 1.03%   |
| DDR2   | 1         | 1.03%   |
| DDR    | 1         | 1.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 93        | 98.94%  |
| DIMM   | 1         | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 40        | 37.74%  |
| 4096  | 31        | 29.25%  |
| 16384 | 20        | 18.87%  |
| 2048  | 13        | 12.26%  |
| 1024  | 1         | 0.94%   |
| 512   | 1         | 0.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 40        | 38.1%   |
| 1600    | 29        | 27.62%  |
| 2400    | 9         | 8.57%   |
| 1334    | 8         | 7.62%   |
| 3200    | 7         | 6.67%   |
| 2133    | 5         | 4.76%   |
| 1333    | 3         | 2.86%   |
| 4199    | 1         | 0.95%   |
| 800     | 1         | 0.95%   |
| 667     | 1         | 0.95%   |
| Unknown | 1         | 0.95%   |

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
| Chicony Electronics                    | 48        | 24.37%  |
| Microdia                               | 26        | 13.2%   |
| Realtek Semiconductor                  | 24        | 12.18%  |
| Cheng Uei Precision Industry (Foxlink) | 23        | 11.68%  |
| Acer                                   | 16        | 8.12%   |
| Sunplus Innovation Technology          | 14        | 7.11%   |
| IMC Networks                           | 13        | 6.6%    |
| Lite-On Technology                     | 9         | 4.57%   |
| Suyin                                  | 6         | 3.05%   |
| Quanta                                 | 4         | 2.03%   |
| Silicon Motion                         | 3         | 1.52%   |
| Apple                                  | 3         | 1.52%   |
| Syntek                                 | 2         | 1.02%   |
| Sonix Technology                       | 1         | 0.51%   |
| OmniVision Technologies                | 1         | 0.51%   |
| MacroSilicon                           | 1         | 0.51%   |
| Lenovo                                 | 1         | 0.51%   |
| Intel                                  | 1         | 0.51%   |
| ALi                                    | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 14        | 7.07%   |
| Microdia Integrated_Webcam_HD                                              | 13        | 6.57%   |
| Chicony EasyCamera                                                         | 8         | 4.04%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 7         | 3.54%   |
| Chicony Integrated Camera                                                  | 6         | 3.03%   |
| Acer Lenovo EasyCamera                                                     | 6         | 3.03%   |
| Sunplus Integrated_Webcam_HD                                               | 5         | 2.53%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 5         | 2.53%   |
| IMC Networks Integrated Camera                                             | 5         | 2.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 2.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 4         | 2.02%   |
| Acer HP TrueVision HD Webcam                                               | 4         | 2.02%   |
| Realtek Integrated Webcam                                                  | 3         | 1.52%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 3         | 1.52%   |
| Lite-On HP HD Webcam                                                       | 3         | 1.52%   |
| Lite-On HP HD Camera                                                       | 3         | 1.52%   |
| Chicony HP Truevision HD camera                                            | 3         | 1.52%   |
| Chicony HP HD Webcam                                                       | 3         | 1.52%   |
| Chicony HP HD Camera                                                       | 3         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 3         | 1.52%   |
| Suyin HP Truevision HD                                                     | 2         | 1.01%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 1.01%   |
| Sunplus Dell HD Webcam                                                     | 2         | 1.01%   |
| Realtek Integrated Webcam HD                                               | 2         | 1.01%   |
| Quanta HP Webcam                                                           | 2         | 1.01%   |
| Microdia Laptop_Integrated_Webcam_1.3M                                     | 2         | 1.01%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 2         | 1.01%   |
| Microdia 1.3 MPixel Integrated Webcam                                      | 2         | 1.01%   |
| Lite-On Integrated Camera                                                  | 2         | 1.01%   |
| IMC Networks Lenovo EasyCamera                                             | 2         | 1.01%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 1.01%   |
| Chicony HP Integrated Webcam                                               | 2         | 1.01%   |
| Chicony HD WebCam                                                          | 2         | 1.01%   |
| Chicony Front Camera                                                       | 2         | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 2         | 1.01%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 2         | 1.01%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 1.01%   |
| Acer EasyCamera                                                            | 2         | 1.01%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.51%   |
| Syntek Integrated Camera                                                   | 1         | 0.51%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 1         | 0.51%   |
| Suyin HP Webcam-50                                                         | 1         | 0.51%   |
| Suyin HP Integrated Webcam                                                 | 1         | 0.51%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.51%   |
| Sunplus Lenovo EasyCamera                                                  | 1         | 0.51%   |
| Sunplus Laptop Integrated Webcam FHD                                       | 1         | 0.51%   |
| Sunplus HP Wide Vision HD                                                  | 1         | 0.51%   |
| Sunplus HP Universal Camera                                                | 1         | 0.51%   |
| Sunplus Dell E5570 integrated webcam                                       | 1         | 0.51%   |
| Sonix HP Webcam-101                                                        | 1         | 0.51%   |
| Silicon Motion WebCam SC-03M12736N                                         | 1         | 0.51%   |
| Silicon Motion Lenovo EasyCamera                                           | 1         | 0.51%   |
| Silicon Motion HP Webcam-101                                               | 1         | 0.51%   |
| Realtek USB Camera                                                         | 1         | 0.51%   |
| Realtek Rear Camera                                                        | 1         | 0.51%   |
| Realtek Lenovo easy camera                                                 | 1         | 0.51%   |
| Realtek HP "Truevision HD" laptop camera                                   | 1         | 0.51%   |
| Realtek Acer 640 x 480 laptop camera                                       | 1         | 0.51%   |
| Quanta VGA WebCam                                                          | 1         | 0.51%   |
| Quanta HP TrueVision HD Camera                                             | 1         | 0.51%   |

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
| Broadcom    | 7         | 58.33%  |
| Alcor Micro | 3         | 25%     |
| O2 Micro    | 1         | 8.33%   |
| Lenovo      | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 25%     |
| Broadcom 5880                                                                | 2         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 8.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Broadcom 58200                                                               | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 141       | 63.51%  |
| 1     | 66        | 29.73%  |
| 2     | 14        | 6.31%   |
| 4     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 38        | 41.3%   |
| Graphics card            | 21        | 22.83%  |
| Chipcard                 | 12        | 13.04%  |
| Net/wireless             | 10        | 10.87%  |
| Bluetooth                | 6         | 6.52%   |
| Multimedia controller    | 2         | 2.17%   |
| Net/ethernet             | 1         | 1.09%   |
| Communication controller | 1         | 1.09%   |
| Card reader              | 1         | 1.09%   |

