Linux in Saudi Arabia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Saudi Arabia.

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

Total: 182

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | B590 20206                  | [f9eddff413](https://linux-hardware.org/?probe=f9eddff413) | Jun 19, 2022 |
| MSI           | GF63 Thin 8RCS              | [8cd1ebfa12](https://linux-hardware.org/?probe=8cd1ebfa12) | May 22, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c34e9b0da7](https://linux-hardware.org/?probe=c34e9b0da7) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [b6dc8a3fc8](https://linux-hardware.org/?probe=b6dc8a3fc8) | May 05, 2022 |
| Dell          | Inspiron 3580               | [51d4e9a2e2](https://linux-hardware.org/?probe=51d4e9a2e2) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| Acer          | Aspire V3-571               | [9cab38ff4f](https://linux-hardware.org/?probe=9cab38ff4f) | May 01, 2022 |
| Dell          | Inspiron 3580               | [794ab7ba41](https://linux-hardware.org/?probe=794ab7ba41) | Apr 28, 2022 |
| Dell          | Inspiron 3542               | [196f849315](https://linux-hardware.org/?probe=196f849315) | Apr 18, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [1f799cdbef](https://linux-hardware.org/?probe=1f799cdbef) | Apr 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [45548a6fe5](https://linux-hardware.org/?probe=45548a6fe5) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [10c6384de8](https://linux-hardware.org/?probe=10c6384de8) | Mar 25, 2022 |
| Dell          | Inspiron 14-3467            | [50131c5da4](https://linux-hardware.org/?probe=50131c5da4) | Mar 21, 2022 |
| Acer          | AO751h                      | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| Acer          | AO751h                      | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| ASUSTek       | K53SC                       | [43b019326c](https://linux-hardware.org/?probe=43b019326c) | Feb 12, 2022 |
| ASUSTek       | K53SC                       | [70f23c3da0](https://linux-hardware.org/?probe=70f23c3da0) | Feb 12, 2022 |
| Dell          | XPS 13 9310                 | [40c74584ee](https://linux-hardware.org/?probe=40c74584ee) | Feb 03, 2022 |
| Acer          | Aspire V3-571               | [ed5c6cf88d](https://linux-hardware.org/?probe=ed5c6cf88d) | Jan 24, 2022 |
| HP            | 15                          | [4dde4c5c0e](https://linux-hardware.org/?probe=4dde4c5c0e) | Jan 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [261fe8bda7](https://linux-hardware.org/?probe=261fe8bda7) | Jan 07, 2022 |
| Sony          | VPCCA35FA                   | [85f4fcc0b6](https://linux-hardware.org/?probe=85f4fcc0b6) | Jan 03, 2022 |
| Sony          | VPCCA35FA                   | [f69299cbfb](https://linux-hardware.org/?probe=f69299cbfb) | Jan 03, 2022 |
| Dell          | Inspiron 3521               | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| Packard Be... | EasyNote TJ65               | [b98b9252fa](https://linux-hardware.org/?probe=b98b9252fa) | Dec 29, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [938d24e76e](https://linux-hardware.org/?probe=938d24e76e) | Dec 27, 2021 |
| HP            | EliteBook 8440p             | [0dc23e59a4](https://linux-hardware.org/?probe=0dc23e59a4) | Dec 19, 2021 |
| Acer          | Aspire V3-571               | [071a8f0709](https://linux-hardware.org/?probe=071a8f0709) | Dec 15, 2021 |
| Acer          | Aspire V3-571               | [54680bac44](https://linux-hardware.org/?probe=54680bac44) | Dec 12, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [bb9141f09c](https://linux-hardware.org/?probe=bb9141f09c) | Dec 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b3c42ca2c2](https://linux-hardware.org/?probe=b3c42ca2c2) | Dec 09, 2021 |
| Lenovo        | V15-IIL 82C5                | [2a151de62b](https://linux-hardware.org/?probe=2a151de62b) | Dec 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [830882c4e6](https://linux-hardware.org/?probe=830882c4e6) | Dec 07, 2021 |
| Toshiba       | Satellite L500              | [5cc2fbfef5](https://linux-hardware.org/?probe=5cc2fbfef5) | Dec 04, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [e3acd70236](https://linux-hardware.org/?probe=e3acd70236) | Dec 02, 2021 |
| Lenovo        | ThinkPad E14 20RA008CAD     | [35fab17b69](https://linux-hardware.org/?probe=35fab17b69) | Dec 01, 2021 |
| HP            | EliteBook 8440p             | [cecc697189](https://linux-hardware.org/?probe=cecc697189) | Nov 30, 2021 |
| Toshiba       | Satellite L500              | [46d5208475](https://linux-hardware.org/?probe=46d5208475) | Nov 28, 2021 |
| Lenovo        | V15-IIL 82C5                | [e37587fbac](https://linux-hardware.org/?probe=e37587fbac) | Nov 23, 2021 |
| Lenovo        | V15-IIL 82C5                | [b050debd0a](https://linux-hardware.org/?probe=b050debd0a) | Nov 22, 2021 |
| Dell          | G3 3590                     | [605f0870d0](https://linux-hardware.org/?probe=605f0870d0) | Nov 16, 2021 |
| Dell          | G3 3590                     | [5bfafc889c](https://linux-hardware.org/?probe=5bfafc889c) | Nov 16, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| Lenovo        | V570 1066AJU                | [ffb36aac10](https://linux-hardware.org/?probe=ffb36aac10) | Nov 05, 2021 |
| Dell          | Inspiron 3593               | [5233ea30c6](https://linux-hardware.org/?probe=5233ea30c6) | Oct 09, 2021 |
| Lenovo        | ThinkPad P52s 20LBS0JC00    | [4c8c63da2f](https://linux-hardware.org/?probe=4c8c63da2f) | Oct 05, 2021 |
| HP            | Laptop 15-da2xxx            | [2e99b047ff](https://linux-hardware.org/?probe=2e99b047ff) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [de6b4e47d4](https://linux-hardware.org/?probe=de6b4e47d4) | Oct 01, 2021 |
| HP            | Laptop 15-da2xxx            | [28332170d1](https://linux-hardware.org/?probe=28332170d1) | Sep 28, 2021 |
| Dell          | Inspiron N5110              | [8c04a9e8df](https://linux-hardware.org/?probe=8c04a9e8df) | Sep 22, 2021 |
| Acer          | Aspire E5-573G              | [19374f68da](https://linux-hardware.org/?probe=19374f68da) | Sep 21, 2021 |
| Acer          | Aspire V3-571               | [6998aee6d0](https://linux-hardware.org/?probe=6998aee6d0) | Sep 02, 2021 |
| Toshiba       | Satellite C55-B             | [e7a572f322](https://linux-hardware.org/?probe=e7a572f322) | Aug 29, 2021 |
| Toshiba       | Satellite C55-B             | [99dbadcdde](https://linux-hardware.org/?probe=99dbadcdde) | Aug 22, 2021 |
| Dell          | Latitude E7440              | [b87783b728](https://linux-hardware.org/?probe=b87783b728) | Aug 18, 2021 |
| Dell          | Latitude E5470              | [f91acefb07](https://linux-hardware.org/?probe=f91acefb07) | Aug 14, 2021 |
| Dell          | XPS 15 9560                 | [9bae1ef315](https://linux-hardware.org/?probe=9bae1ef315) | Jul 07, 2021 |
| ASUSTek       | K43SJ                       | [f4702e95b4](https://linux-hardware.org/?probe=f4702e95b4) | Jul 05, 2021 |
| Dell          | XPS 15 9560                 | [08fad9a114](https://linux-hardware.org/?probe=08fad9a114) | Jul 03, 2021 |
| Dell          | G3 3590                     | [06d10d0717](https://linux-hardware.org/?probe=06d10d0717) | Jun 26, 2021 |
| Dell          | Inspiron 5437               | [06f25de7e3](https://linux-hardware.org/?probe=06f25de7e3) | Jun 19, 2021 |
| Dell          | Inspiron 5437               | [3fcbd5cd4f](https://linux-hardware.org/?probe=3fcbd5cd4f) | Jun 18, 2021 |
| Dell          | G3 3590                     | [877018f0d3](https://linux-hardware.org/?probe=877018f0d3) | Jun 18, 2021 |
| Dell          | G3 3590                     | [adf875d64d](https://linux-hardware.org/?probe=adf875d64d) | Jun 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d3a001e377](https://linux-hardware.org/?probe=d3a001e377) | Jun 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [a4d00095a1](https://linux-hardware.org/?probe=a4d00095a1) | Jun 01, 2021 |
| HP            | ProBook 445 G7              | [88e51bfd39](https://linux-hardware.org/?probe=88e51bfd39) | May 23, 2021 |
| ASUSTek       | GL502VMK                    | [0d9f5609e7](https://linux-hardware.org/?probe=0d9f5609e7) | May 20, 2021 |
| HP            | ProBook 445 G7              | [ed8c410826](https://linux-hardware.org/?probe=ed8c410826) | May 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [1d4c05756f](https://linux-hardware.org/?probe=1d4c05756f) | May 01, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9b03874730](https://linux-hardware.org/?probe=9b03874730) | Apr 27, 2021 |
| Dell          | Latitude E7470              | [1058573f86](https://linux-hardware.org/?probe=1058573f86) | Apr 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [14fd40d980](https://linux-hardware.org/?probe=14fd40d980) | Apr 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b31da2d02](https://linux-hardware.org/?probe=0b31da2d02) | Apr 16, 2021 |
| HP            | Pavilion Laptop 15t-eg00... | [cd64675ac7](https://linux-hardware.org/?probe=cd64675ac7) | Mar 30, 2021 |
| Toshiba       | Satellite S55t-A            | [9ede240e19](https://linux-hardware.org/?probe=9ede240e19) | Mar 20, 2021 |
| Apple         | MacBookPro9,2               | [7d8acdd5b6](https://linux-hardware.org/?probe=7d8acdd5b6) | Mar 19, 2021 |
| Toshiba       | Satellite S55t-A            | [5aa53770bf](https://linux-hardware.org/?probe=5aa53770bf) | Mar 06, 2021 |
| Toshiba       | Satellite S55t-A            | [5ed863271a](https://linux-hardware.org/?probe=5ed863271a) | Mar 06, 2021 |
| Acer          | Nitro AN515-52              | [99ee0e5718](https://linux-hardware.org/?probe=99ee0e5718) | Feb 24, 2021 |
| Acer          | Nitro AN515-52              | [89497c0f27](https://linux-hardware.org/?probe=89497c0f27) | Feb 23, 2021 |
| ASUSTek       | X555UB                      | [260d78f7c8](https://linux-hardware.org/?probe=260d78f7c8) | Feb 20, 2021 |
| HP            | Pavilion g6                 | [30bcebb4be](https://linux-hardware.org/?probe=30bcebb4be) | Feb 16, 2021 |
| Lenovo        | ThinkPad E460 20ET000MAD    | [cd000b8e6b](https://linux-hardware.org/?probe=cd000b8e6b) | Feb 11, 2021 |
| Dell          | Inspiron 3593               | [5407a15ab7](https://linux-hardware.org/?probe=5407a15ab7) | Feb 09, 2021 |
| Dell          | Inspiron 3593               | [0802cedb25](https://linux-hardware.org/?probe=0802cedb25) | Feb 09, 2021 |
| Dell          | Latitude E4310              | [9c6781e592](https://linux-hardware.org/?probe=9c6781e592) | Feb 08, 2021 |
| ASUSTek       | ROG Strix G512LWS_G512LW... | [d4d3110510](https://linux-hardware.org/?probe=d4d3110510) | Jan 29, 2021 |
| Toshiba       | Satellite C855D             | [46d5bf62c7](https://linux-hardware.org/?probe=46d5bf62c7) | Jan 19, 2021 |
| Dell          | Inspiron 3576               | [99f1a1ac09](https://linux-hardware.org/?probe=99f1a1ac09) | Jan 16, 2021 |
| Sony          | VGN-FZ250E                  | [d0d77ffe81](https://linux-hardware.org/?probe=d0d77ffe81) | Jan 15, 2021 |
| HP            | Laptop 14-ck0xxx            | [92ea4004af](https://linux-hardware.org/?probe=92ea4004af) | Jan 15, 2021 |
| Sony          | VGN-FZ250E                  | [68ddc53941](https://linux-hardware.org/?probe=68ddc53941) | Jan 14, 2021 |
| Dell          | Inspiron 3576               | [b21e44d0c4](https://linux-hardware.org/?probe=b21e44d0c4) | Jan 11, 2021 |
| Dell          | Vostro 5470                 | [216df384d8](https://linux-hardware.org/?probe=216df384d8) | Dec 22, 2020 |
| Dell          | Vostro 5470                 | [bec1b16786](https://linux-hardware.org/?probe=bec1b16786) | Dec 22, 2020 |
| LG Electro... | R490-G.ARL5RE2              | [58f0c96534](https://linux-hardware.org/?probe=58f0c96534) | Dec 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [239675db8d](https://linux-hardware.org/?probe=239675db8d) | Nov 25, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [dfcc723611](https://linux-hardware.org/?probe=dfcc723611) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b164be6cfc](https://linux-hardware.org/?probe=b164be6cfc) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a3ffdab533](https://linux-hardware.org/?probe=a3ffdab533) | Nov 16, 2020 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | [cce5403051](https://linux-hardware.org/?probe=cce5403051) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| I-Life Dig... | ZED Air Plus                | [b1a43bf9f2](https://linux-hardware.org/?probe=b1a43bf9f2) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | [c0ad42acb0](https://linux-hardware.org/?probe=c0ad42acb0) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | [b5e6f52433](https://linux-hardware.org/?probe=b5e6f52433) | Nov 04, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e9ca4c8d42](https://linux-hardware.org/?probe=e9ca4c8d42) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Acer          | Aspire E1-532P              | [4a2a5fd18c](https://linux-hardware.org/?probe=4a2a5fd18c) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c45580b2f3](https://linux-hardware.org/?probe=c45580b2f3) | Oct 28, 2020 |
| MSI           | MS-1454                     | [0accbf6c77](https://linux-hardware.org/?probe=0accbf6c77) | Oct 14, 2020 |
| Acer          | Swift SF314-52              | [a1665a6de1](https://linux-hardware.org/?probe=a1665a6de1) | Sep 26, 2020 |
| Acer          | Aspire E5-571G              | [d52f9c5bc7](https://linux-hardware.org/?probe=d52f9c5bc7) | Sep 18, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [6963343ed4](https://linux-hardware.org/?probe=6963343ed4) | Sep 17, 2020 |
| Clevo         | P15xEMx                     | [83d0f6aae6](https://linux-hardware.org/?probe=83d0f6aae6) | Aug 28, 2020 |
| Lenovo        | ThinkPad Edge 0301FFG       | [60d3a68581](https://linux-hardware.org/?probe=60d3a68581) | Aug 10, 2020 |
| HP            | Pavilion g6                 | [98d75162cc](https://linux-hardware.org/?probe=98d75162cc) | Aug 06, 2020 |
| HUAWEI        | HN-WX9X                     | [41a4a29b16](https://linux-hardware.org/?probe=41a4a29b16) | Aug 02, 2020 |
| Dell          | Inspiron 3542               | [9138a15fe4](https://linux-hardware.org/?probe=9138a15fe4) | Aug 01, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fe429f7077](https://linux-hardware.org/?probe=fe429f7077) | Jul 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f9c494b96b](https://linux-hardware.org/?probe=f9c494b96b) | Jul 22, 2020 |
| ASUSTek       | T100TA                      | [f6884bd3db](https://linux-hardware.org/?probe=f6884bd3db) | Jun 26, 2020 |
| ASUSTek       | T100TA                      | [1a288de2c5](https://linux-hardware.org/?probe=1a288de2c5) | Jun 24, 2020 |
| ASUSTek       | T100TA                      | [aa1c1587d1](https://linux-hardware.org/?probe=aa1c1587d1) | Jun 23, 2020 |
| Acer          | Aspire ES1-572              | [a166c179ea](https://linux-hardware.org/?probe=a166c179ea) | Jun 22, 2020 |
| ASUSTek       | L4000H                      | [d385784b22](https://linux-hardware.org/?probe=d385784b22) | Jun 22, 2020 |
| Acer          | Swift SF314-52              | [c5f91bc1ff](https://linux-hardware.org/?probe=c5f91bc1ff) | Jun 16, 2020 |
| Dell          | Inspiron N5030              | [5641d9b86e](https://linux-hardware.org/?probe=5641d9b86e) | Jun 14, 2020 |
| ASUSTek       | UX390UAK                    | [0857b4df77](https://linux-hardware.org/?probe=0857b4df77) | May 27, 2020 |
| Sony          | SVF153290X                  | [e19f1c716f](https://linux-hardware.org/?probe=e19f1c716f) | May 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [117bc7af0e](https://linux-hardware.org/?probe=117bc7af0e) | May 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0444dd48d1](https://linux-hardware.org/?probe=0444dd48d1) | May 09, 2020 |
| Acer          | Aspire E1-532P              | [b401e8b701](https://linux-hardware.org/?probe=b401e8b701) | Apr 30, 2020 |
| HP            | Pavilion dv6                | [8ee1846a65](https://linux-hardware.org/?probe=8ee1846a65) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [bff527c13e](https://linux-hardware.org/?probe=bff527c13e) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [8b02fac19f](https://linux-hardware.org/?probe=8b02fac19f) | Apr 26, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [640431a321](https://linux-hardware.org/?probe=640431a321) | Apr 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [095b8a5cdc](https://linux-hardware.org/?probe=095b8a5cdc) | Apr 16, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [874b42a4b7](https://linux-hardware.org/?probe=874b42a4b7) | Apr 16, 2020 |
| HP            | 15                          | [68b0d776a9](https://linux-hardware.org/?probe=68b0d776a9) | Apr 08, 2020 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [784de80b54](https://linux-hardware.org/?probe=784de80b54) | Apr 08, 2020 |
| HP            | Notebook                    | [f22cd145c5](https://linux-hardware.org/?probe=f22cd145c5) | Apr 07, 2020 |
| HP            | 15                          | [27ef1499e3](https://linux-hardware.org/?probe=27ef1499e3) | Apr 06, 2020 |
| HP            | 15                          | [0c2b7adf55](https://linux-hardware.org/?probe=0c2b7adf55) | Apr 06, 2020 |
| HP            | 15                          | [ee5fd88936](https://linux-hardware.org/?probe=ee5fd88936) | Apr 03, 2020 |
| HP            | 15                          | [bfd4fe41b3](https://linux-hardware.org/?probe=bfd4fe41b3) | Apr 03, 2020 |
| HP            | Laptop 15-bs1xx             | [cdce411ba5](https://linux-hardware.org/?probe=cdce411ba5) | Mar 13, 2020 |
| HP            | Laptop 15-bs1xx             | [6e7a1c3bc6](https://linux-hardware.org/?probe=6e7a1c3bc6) | Mar 13, 2020 |
| HP            | Laptop 15-da0xxx            | [d3d2a3b89f](https://linux-hardware.org/?probe=d3d2a3b89f) | Mar 05, 2020 |
| ASUSTek       | X555QA                      | [2f0a038eaf](https://linux-hardware.org/?probe=2f0a038eaf) | Feb 11, 2020 |
| ASUSTek       | X555QA                      | [e8062aced5](https://linux-hardware.org/?probe=e8062aced5) | Feb 10, 2020 |
| Dell          | Vostro 1440                 | [203e61a7c9](https://linux-hardware.org/?probe=203e61a7c9) | Feb 01, 2020 |
| HP            | Notebook                    | [86dc2687ad](https://linux-hardware.org/?probe=86dc2687ad) | Jan 29, 2020 |
| HP            | Notebook                    | [d3e2e18fa2](https://linux-hardware.org/?probe=d3e2e18fa2) | Jan 29, 2020 |
| HP            | Laptop 15-db0xxx            | [9c01b939ce](https://linux-hardware.org/?probe=9c01b939ce) | Jan 27, 2020 |
| HP            | Laptop 15-db0xxx            | [916d1cb7c0](https://linux-hardware.org/?probe=916d1cb7c0) | Jan 27, 2020 |
| Toshiba       | QOSMIO X875                 | [a20b2a7dd7](https://linux-hardware.org/?probe=a20b2a7dd7) | Jan 02, 2020 |
| Toshiba       | QOSMIO X875                 | [953a43ae80](https://linux-hardware.org/?probe=953a43ae80) | Jan 02, 2020 |
| Lenovo        | ThinkPad X230 2325OA3       | [ad8913bb6b](https://linux-hardware.org/?probe=ad8913bb6b) | Dec 09, 2019 |
| GPD           | MicroPC                     | [37bfeee080](https://linux-hardware.org/?probe=37bfeee080) | Dec 09, 2019 |
| ASUSTek       | X555LDB                     | [fffe9c8500](https://linux-hardware.org/?probe=fffe9c8500) | Sep 04, 2019 |
| ASUSTek       | X555LDB                     | [60bc2f13a4](https://linux-hardware.org/?probe=60bc2f13a4) | Sep 04, 2019 |
| Acer          | Aspire 4752                 | [4b1cbc26db](https://linux-hardware.org/?probe=4b1cbc26db) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | [5670d72491](https://linux-hardware.org/?probe=5670d72491) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | [81bd1c9f07](https://linux-hardware.org/?probe=81bd1c9f07) | Aug 13, 2019 |
| Sony          | VPCEA36FA                   | [069db5e1d5](https://linux-hardware.org/?probe=069db5e1d5) | Jul 11, 2019 |
| HUAWEI        | MateBook D                  | [0c82ca3724](https://linux-hardware.org/?probe=0c82ca3724) | Jul 06, 2019 |
| ASUSTek       | X540UA                      | [b66944b7d8](https://linux-hardware.org/?probe=b66944b7d8) | Jun 14, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [630f59eb30](https://linux-hardware.org/?probe=630f59eb30) | Jun 12, 2019 |
| ASUSTek       | X540UA                      | [3d424bc8d3](https://linux-hardware.org/?probe=3d424bc8d3) | Jun 07, 2019 |
| ASUSTek       | X540UA                      | [8b98fb721c](https://linux-hardware.org/?probe=8b98fb721c) | Jun 07, 2019 |
| ASUSTek       | X540NA                      | [ced21dc1f3](https://linux-hardware.org/?probe=ced21dc1f3) | May 21, 2019 |
| Sony          | SVF14N13CXB                 | [37e231ce84](https://linux-hardware.org/?probe=37e231ce84) | Apr 07, 2019 |
| HP            | 15                          | [e900ad9cfc](https://linux-hardware.org/?probe=e900ad9cfc) | Mar 15, 2019 |
| Lenovo        | Flex 2-15 20405             | [d44c9b123d](https://linux-hardware.org/?probe=d44c9b123d) | Dec 19, 2018 |
| Lenovo        | Flex 2-15 20405             | [b0c7903cb1](https://linux-hardware.org/?probe=b0c7903cb1) | Dec 19, 2018 |
| Acer          | Aspire E1-532P              | [26e0937896](https://linux-hardware.org/?probe=26e0937896) | Nov 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Ubuntu 20.04           | 23        | 19.33%  |
| Ubuntu 18.04           | 10        | 8.4%    |
| OpenMandriva 4.2       | 6         | 5.04%   |
| Fedora 35              | 5         | 4.2%    |
| Ubuntu 20.10           | 4         | 3.36%   |
| Zorin 16               | 3         | 2.52%   |
| Ubuntu 21.04           | 3         | 2.52%   |
| Pop!_OS 20.04          | 3         | 2.52%   |
| Endless 3.3.20-nexthw1 | 3         | 2.52%   |
| Debian Testing         | 3         | 2.52%   |
| Ubuntu 19.04           | 2         | 1.68%   |
| Pop!_OS 20.10          | 2         | 1.68%   |
| Manjaro 20.0.3         | 2         | 1.68%   |
| Linux Mint 20.1        | 2         | 1.68%   |
| Linux Mint 20          | 2         | 1.68%   |
| Kubuntu 20.04          | 2         | 1.68%   |
| Kali 2021.2            | 2         | 1.68%   |
| Endless 3.7.8          | 2         | 1.68%   |
| Xubuntu 20.10          | 1         | 0.84%   |
| Xubuntu 20.04          | 1         | 0.84%   |
| Xubuntu 18.04          | 1         | 0.84%   |
| Ubuntu 19.10           | 1         | 0.84%   |
| Ubuntu 16.04           | 1         | 0.84%   |
| Solus 4.1              | 1         | 0.84%   |
| Solus 3.9999           | 1         | 0.84%   |
| ROSA R8.1              | 1         | 0.84%   |
| RHEL 8                 | 1         | 0.84%   |
| Q4OS 4                 | 1         | 0.84%   |
| Pop!_OS 22.04          | 1         | 0.84%   |
| Pop!_OS 21.10          | 1         | 0.84%   |
| Pop!_OS 21.04          | 1         | 0.84%   |
| OpenMandriva 4.3       | 1         | 0.84%   |
| Manjaro 21.2.6         | 1         | 0.84%   |
| Manjaro 21.2.5         | 1         | 0.84%   |
| Manjaro 21.2.0         | 1         | 0.84%   |
| Linux Mint 19.1        | 1         | 0.84%   |
| Liberty OS             | 1         | 0.84%   |
| KDE neon 18.04         | 1         | 0.84%   |
| Kali 2020.4            | 1         | 0.84%   |
| Gentoo 2.7             | 1         | 0.84%   |
| Fedora 36              | 1         | 0.84%   |
| Fedora 34              | 1         | 0.84%   |
| Fedora 31              | 1         | 0.84%   |
| Endless 3.9.1          | 1         | 0.84%   |
| Endless 3.8.7          | 1         | 0.84%   |
| Endless 3.8.4          | 1         | 0.84%   |
| Endless 3.8.3          | 1         | 0.84%   |
| Endless 3.8.0          | 1         | 0.84%   |
| Endless 3.7.6          | 1         | 0.84%   |
| Endless 3.5.8          | 1         | 0.84%   |
| Endless 3.3.19-nexthw1 | 1         | 0.84%   |
| Endless 3.3.19         | 1         | 0.84%   |
| Elementary 5.1.7       | 1         | 0.84%   |
| Debian 9               | 1         | 0.84%   |
| Clear Linux 34820      | 1         | 0.84%   |
| Clear Linux 33190      | 1         | 0.84%   |
| ArcoLinux Rolling      | 1         | 0.84%   |
| Arch                   | 1         | 0.84%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 44        | 39.29%  |
| Endless      | 13        | 11.61%  |
| OpenMandriva | 7         | 6.25%   |
| Fedora       | 7         | 6.25%   |
| Pop!_OS      | 5         | 4.46%   |
| Linux Mint   | 5         | 4.46%   |
| Manjaro      | 4         | 3.57%   |
| Debian       | 4         | 3.57%   |
| Zorin        | 3         | 2.68%   |
| Xubuntu      | 3         | 2.68%   |
| Kali         | 3         | 2.68%   |
| Kubuntu      | 2         | 1.79%   |
| Clear Linux  | 2         | 1.79%   |
| Solus        | 1         | 0.89%   |
| ROSA         | 1         | 0.89%   |
| RHEL         | 1         | 0.89%   |
| Q4OS         | 1         | 0.89%   |
| Liberty OS   | 1         | 0.89%   |
| KDE neon     | 1         | 0.89%   |
| Gentoo       | 1         | 0.89%   |
| Elementary   | 1         | 0.89%   |
| ArcoLinux    | 1         | 0.89%   |
| Arch         | 1         | 0.89%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002     | 5         | 4%      |
| 5.4.0-42-generic             | 4         | 3.2%    |
| 4.15.0-15-generic            | 4         | 3.2%    |
| 5.4.0-19-generic             | 3         | 2.4%    |
| 5.11.0-43-generic            | 3         | 2.4%    |
| 5.8.0-53-generic             | 2         | 1.6%    |
| 5.8.0-41-generic             | 2         | 1.6%    |
| 5.8.0-38-generic             | 2         | 1.6%    |
| 5.8.0-36-generic             | 2         | 1.6%    |
| 5.4.0-58-generic             | 2         | 1.6%    |
| 5.4.0-37-generic             | 2         | 1.6%    |
| 5.3.0-28-generic             | 2         | 1.6%    |
| 5.3.0-2-amd64                | 2         | 1.6%    |
| 5.11.0-41-generic            | 2         | 1.6%    |
| 5.11.0-40-generic            | 2         | 1.6%    |
| 5.11.0-37-generic            | 2         | 1.6%    |
| 5.11.0-31-generic            | 2         | 1.6%    |
| 5.0.0-20-generic             | 2         | 1.6%    |
| 4.15.0-29-generic            | 2         | 1.6%    |
| 5.9.0-kali1-amd64            | 1         | 0.8%    |
| 5.8.18-xanmod1               | 1         | 0.8%    |
| 5.8.0-7630-generic           | 1         | 0.8%    |
| 5.8.0-57-generic             | 1         | 0.8%    |
| 5.8.0-48-generic             | 1         | 0.8%    |
| 5.8.0-45-generic             | 1         | 0.8%    |
| 5.8.0-44-generic             | 1         | 0.8%    |
| 5.8.0-43-generic             | 1         | 0.8%    |
| 5.8.0-26-generic             | 1         | 0.8%    |
| 5.8.0-25-generic             | 1         | 0.8%    |
| 5.8.0-14-generic             | 1         | 0.8%    |
| 5.7.9-1-MANJARO              | 1         | 0.8%    |
| 5.7.0-3-MANJARO              | 1         | 0.8%    |
| 5.6.4-152.current            | 1         | 0.8%    |
| 5.6.15-arch1-1               | 1         | 0.8%    |
| 5.6.14-955.native            | 1         | 0.8%    |
| 5.5.7-arch1-1                | 1         | 0.8%    |
| 5.4.123-116.lts2019          | 1         | 0.8%    |
| 5.4.12-200.fc31.x86_64       | 1         | 0.8%    |
| 5.4.0-92-generic             | 1         | 0.8%    |
| 5.4.0-90-generic             | 1         | 0.8%    |
| 5.4.0-7642-generic           | 1         | 0.8%    |
| 5.4.0-72-generic             | 1         | 0.8%    |
| 5.4.0-52-generic             | 1         | 0.8%    |
| 5.4.0-51-generic             | 1         | 0.8%    |
| 5.4.0-48-generic             | 1         | 0.8%    |
| 5.4.0-47-generic             | 1         | 0.8%    |
| 5.4.0-31-generic             | 1         | 0.8%    |
| 5.4.0-105-generic            | 1         | 0.8%    |
| 5.3.0-51-generic             | 1         | 0.8%    |
| 5.3.0-46-generic             | 1         | 0.8%    |
| 5.3.0-45-generic             | 1         | 0.8%    |
| 5.3.0-40-generic             | 1         | 0.8%    |
| 5.3.0-24-generic             | 1         | 0.8%    |
| 5.3.0-23-generic             | 1         | 0.8%    |
| 5.17.0-0.rc7.116.fc36.x86_64 | 1         | 0.8%    |
| 5.16.7-desktop-1omv4003      | 1         | 0.8%    |
| 5.16.5-200.fc35.x86_64       | 1         | 0.8%    |
| 5.16.19-76051619-generic     | 1         | 0.8%    |
| 5.16.16-200.fc35.x86_64      | 1         | 0.8%    |
| 5.16.15-76051615-generic     | 1         | 0.8%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.4.0    | 19        | 15.97%  |
| 5.8.0    | 17        | 14.29%  |
| 5.11.0   | 15        | 12.61%  |
| 5.3.0    | 10        | 8.4%    |
| 4.15.0   | 9         | 7.56%   |
| 5.10.14  | 5         | 4.2%    |
| 5.0.0    | 4         | 3.36%   |
| 4.18.0   | 4         | 3.36%   |
| 5.10.0   | 3         | 2.52%   |
| 5.13.0   | 2         | 1.68%   |
| 5.9.0    | 1         | 0.84%   |
| 5.8.18   | 1         | 0.84%   |
| 5.7.9    | 1         | 0.84%   |
| 5.7.0    | 1         | 0.84%   |
| 5.6.4    | 1         | 0.84%   |
| 5.6.15   | 1         | 0.84%   |
| 5.6.14   | 1         | 0.84%   |
| 5.5.7    | 1         | 0.84%   |
| 5.4.123  | 1         | 0.84%   |
| 5.4.12   | 1         | 0.84%   |
| 5.17.0   | 1         | 0.84%   |
| 5.16.7   | 1         | 0.84%   |
| 5.16.5   | 1         | 0.84%   |
| 5.16.19  | 1         | 0.84%   |
| 5.16.16  | 1         | 0.84%   |
| 5.16.15  | 1         | 0.84%   |
| 5.15.6   | 1         | 0.84%   |
| 5.15.5   | 1         | 0.84%   |
| 5.15.48  | 1         | 0.84%   |
| 5.15.11  | 1         | 0.84%   |
| 5.15.0   | 1         | 0.84%   |
| 5.14.10  | 1         | 0.84%   |
| 5.13.19  | 1         | 0.84%   |
| 5.11.19  | 1         | 0.84%   |
| 5.11.12  | 1         | 0.84%   |
| 5.10.109 | 1         | 0.84%   |
| 5.10.105 | 1         | 0.84%   |
| 4.9.9    | 1         | 0.84%   |
| 4.9.0    | 1         | 0.84%   |
| 4.18.16  | 1         | 0.84%   |
| 4.13.0   | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 21        | 17.95%  |
| 5.8     | 18        | 15.38%  |
| 5.11    | 17        | 14.53%  |
| 5.3     | 10        | 8.55%   |
| 5.10    | 9         | 7.69%   |
| 4.15    | 9         | 7.69%   |
| 5.16    | 5         | 4.27%   |
| 4.18    | 5         | 4.27%   |
| 5.15    | 4         | 3.42%   |
| 5.0     | 4         | 3.42%   |
| 5.6     | 3         | 2.56%   |
| 5.13    | 3         | 2.56%   |
| 5.7     | 2         | 1.71%   |
| 4.9     | 2         | 1.71%   |
| 5.9     | 1         | 0.85%   |
| 5.5     | 1         | 0.85%   |
| 5.17    | 1         | 0.85%   |
| 5.14    | 1         | 0.85%   |
| 4.13    | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 103       | 96.26%  |
| i686   | 4         | 3.74%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 65        | 58.04%  |
| Unknown    | 14        | 12.5%   |
| KDE5       | 11        | 9.82%   |
| XFCE       | 6         | 5.36%   |
| X-Cinnamon | 4         | 3.57%   |
| Cinnamon   | 3         | 2.68%   |
| KDE        | 2         | 1.79%   |
| Unity      | 1         | 0.89%   |
| trinity    | 1         | 0.89%   |
| Pantheon   | 1         | 0.89%   |
| openbox    | 1         | 0.89%   |
| KDE4       | 1         | 0.89%   |
| i3         | 1         | 0.89%   |
| Budgie     | 1         | 0.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 85        | 78.7%   |
| Wayland | 11        | 10.19%  |
| Unknown | 10        | 9.26%   |
| Tty     | 2         | 1.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 66        | 60.55%  |
| GDM     | 16        | 14.68%  |
| SDDM    | 12        | 11.01%  |
| GDM3    | 7         | 6.42%   |
| TDM     | 4         | 3.67%   |
| LightDM | 3         | 2.75%   |
| KDM     | 1         | 0.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 79        | 72.48%  |
| Unknown | 13        | 11.93%  |
| ar_EG   | 7         | 6.42%   |
| ar_SA   | 4         | 3.67%   |
| en_GB   | 3         | 2.75%   |
| C       | 2         | 1.83%   |
| ar_AE   | 1         | 0.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 58        | 53.7%   |
| EFI  | 50        | 46.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 90        | 82.57%  |
| Unknown | 6         | 5.5%    |
| Overlay | 4         | 3.67%   |
| Btrfs   | 4         | 3.67%   |
| Xfs     | 2         | 1.83%   |
| Zfs     | 1         | 0.92%   |
| Tmpfs   | 1         | 0.92%   |
| Ext2    | 1         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 75        | 69.44%  |
| GPT     | 24        | 22.22%  |
| MBR     | 9         | 8.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 86.36%  |
| Yes       | 15        | 13.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 81        | 75%     |
| Yes       | 27        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 24        | 22.43%  |
| Dell                        | 21        | 19.63%  |
| Hewlett-Packard             | 17        | 15.89%  |
| Lenovo                      | 15        | 14.02%  |
| Acer                        | 9         | 8.41%   |
| Toshiba                     | 5         | 4.67%   |
| Sony                        | 5         | 4.67%   |
| MSI                         | 2         | 1.87%   |
| HUAWEI                      | 2         | 1.87%   |
| Samsung Electronics         | 1         | 0.93%   |
| Packard Bell                | 1         | 0.93%   |
| LG Electronics              | 1         | 0.93%   |
| I-Life Digital Technologies | 1         | 0.93%   |
| GPD                         | 1         | 0.93%   |
| Clevo                       | 1         | 0.93%   |
| Apple                       | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 4         | 3.74%   |
| HP 15                                      | 3         | 2.8%    |
| Dell G3 3590                               | 3         | 2.8%    |
| HP Pavilion g6                             | 2         | 1.87%   |
| HP Notebook                                | 2         | 1.87%   |
| Dell Inspiron 3542                         | 2         | 1.87%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 2         | 1.87%   |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 2         | 1.87%   |
| Toshiba Satellite S55t-A                   | 1         | 0.93%   |
| Toshiba Satellite L500                     | 1         | 0.93%   |
| Toshiba Satellite C855D                    | 1         | 0.93%   |
| Toshiba Satellite C55-B                    | 1         | 0.93%   |
| Toshiba QOSMIO X875                        | 1         | 0.93%   |
| Sony VPCEA36FA                             | 1         | 0.93%   |
| Sony VPCCA35FA                             | 1         | 0.93%   |
| Sony VGN-FZ250E                            | 1         | 0.93%   |
| Sony SVF153290X                            | 1         | 0.93%   |
| Sony SVF14N13CXB                           | 1         | 0.93%   |
| Samsung 870Z5E/880Z5E/680Z5E               | 1         | 0.93%   |
| Packard Bell EasyNote TJ65                 | 1         | 0.93%   |
| MSI MS-1454                                | 1         | 0.93%   |
| MSI GF63 Thin 8RCS                         | 1         | 0.93%   |
| LG R490-G.ARL5RE2                          | 1         | 0.93%   |
| Lenovo V570 1066AJU                        | 1         | 0.93%   |
| Lenovo V15-IIL 82C5                        | 1         | 0.93%   |
| Lenovo ThinkPad X230 2325OA3               | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD003LAD   | 1         | 0.93%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH002JUS   | 1         | 0.93%   |
| Lenovo ThinkPad P52s 20LBS0JC00            | 1         | 0.93%   |
| Lenovo ThinkPad L14 Gen 2 20X10044EQ       | 1         | 0.93%   |
| Lenovo ThinkPad Edge 0301FFG               | 1         | 0.93%   |
| Lenovo ThinkPad E490 20N8000JAD            | 1         | 0.93%   |
| Lenovo ThinkPad E460 20ET000MAD            | 1         | 0.93%   |
| Lenovo ThinkPad E14 20RA008CAD             | 1         | 0.93%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2        | 1         | 0.93%   |
| Lenovo IdeaPad 5 14IIL05 81YH              | 1         | 0.93%   |
| Lenovo Flex 2-15 20405                     | 1         | 0.93%   |
| Lenovo B590 20206                          | 1         | 0.93%   |
| I-Life Digital ZED Air Plus                | 1         | 0.93%   |
| HUAWEI MateBook D                          | 1         | 0.93%   |
| HUAWEI HN-WX9X                             | 1         | 0.93%   |
| HP ProBook 445 G7                          | 1         | 0.93%   |
| HP Pavilion Laptop 15t-eg000               | 1         | 0.93%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 1         | 0.93%   |
| HP Pavilion dv6                            | 1         | 0.93%   |
| HP Laptop 15-db0xxx                        | 1         | 0.93%   |
| HP Laptop 15-da2xxx                        | 1         | 0.93%   |
| HP Laptop 15-da0xxx                        | 1         | 0.93%   |
| HP Laptop 15-bs1xx                         | 1         | 0.93%   |
| HP Laptop 14-ck0xxx                        | 1         | 0.93%   |
| HP EliteBook 8440p                         | 1         | 0.93%   |
| GPD MicroPC                                | 1         | 0.93%   |
| Dell XPS 15 9560                           | 1         | 0.93%   |
| Dell XPS 13 9310                           | 1         | 0.93%   |
| Dell Vostro 5470                           | 1         | 0.93%   |
| Dell Vostro 1440                           | 1         | 0.93%   |
| Dell Latitude E7470                        | 1         | 0.93%   |
| Dell Latitude E7440                        | 1         | 0.93%   |
| Dell Latitude E5470                        | 1         | 0.93%   |
| Dell Latitude E4310                        | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 10        | 9.35%   |
| Lenovo ThinkPad       | 9         | 8.41%   |
| ASUS VivoBook         | 9         | 8.41%   |
| Acer Aspire           | 6         | 5.61%   |
| HP Pavilion           | 5         | 4.67%   |
| HP Laptop             | 5         | 4.67%   |
| Toshiba Satellite     | 4         | 3.74%   |
| Dell Latitude         | 4         | 3.74%   |
| HP 15                 | 3         | 2.8%    |
| Dell G3               | 3         | 2.8%    |
| Lenovo IdeaPad        | 2         | 1.87%   |
| HP Notebook           | 2         | 1.87%   |
| Dell XPS              | 2         | 1.87%   |
| Dell Vostro           | 2         | 1.87%   |
| ASUS ROG              | 2         | 1.87%   |
| Toshiba QOSMIO        | 1         | 0.93%   |
| Sony VPCEA36FA        | 1         | 0.93%   |
| Sony VPCCA35FA        | 1         | 0.93%   |
| Sony VGN-FZ250E       | 1         | 0.93%   |
| Sony SVF153290X       | 1         | 0.93%   |
| Sony SVF14N13CXB      | 1         | 0.93%   |
| Samsung 870Z5E        | 1         | 0.93%   |
| Packard Bell EasyNote | 1         | 0.93%   |
| MSI MS-1454           | 1         | 0.93%   |
| MSI GF63              | 1         | 0.93%   |
| LG R490-G.ARL5RE2     | 1         | 0.93%   |
| Lenovo V570           | 1         | 0.93%   |
| Lenovo V15-IIL        | 1         | 0.93%   |
| Lenovo Flex           | 1         | 0.93%   |
| Lenovo B590           | 1         | 0.93%   |
| I-Life Digital ZED    | 1         | 0.93%   |
| HUAWEI MateBook       | 1         | 0.93%   |
| HUAWEI HN-WX9X        | 1         | 0.93%   |
| HP ProBook            | 1         | 0.93%   |
| HP EliteBook          | 1         | 0.93%   |
| GPD MicroPC           | 1         | 0.93%   |
| Clevo P15xEMx         | 1         | 0.93%   |
| ASUS ZenBook          | 1         | 0.93%   |
| ASUS X555UB           | 1         | 0.93%   |
| ASUS X555QA           | 1         | 0.93%   |
| ASUS X555LDB          | 1         | 0.93%   |
| ASUS X540UA           | 1         | 0.93%   |
| ASUS X540NA           | 1         | 0.93%   |
| ASUS UX390UAK         | 1         | 0.93%   |
| ASUS TUF              | 1         | 0.93%   |
| ASUS T100TA           | 1         | 0.93%   |
| ASUS L4000H           | 1         | 0.93%   |
| ASUS K53SC            | 1         | 0.93%   |
| ASUS K43SJ            | 1         | 0.93%   |
| ASUS GL502VMK         | 1         | 0.93%   |
| Apple MacBookPro9     | 1         | 0.93%   |
| Acer Swift            | 1         | 0.93%   |
| Acer Nitro            | 1         | 0.93%   |
| Acer AO751h           | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 19        | 17.76%  |
| 2019 | 13        | 12.15%  |
| 2014 | 10        | 9.35%   |
| 2012 | 9         | 8.41%   |
| 2020 | 8         | 7.48%   |
| 2017 | 8         | 7.48%   |
| 2011 | 8         | 7.48%   |
| 2013 | 7         | 6.54%   |
| 2010 | 7         | 6.54%   |
| 2016 | 5         | 4.67%   |
| 2015 | 4         | 3.74%   |
| 2021 | 3         | 2.8%    |
| 2009 | 3         | 2.8%    |
| 2008 | 1         | 0.93%   |
| 2007 | 1         | 0.93%   |
| 2002 | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 107       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 98        | 90.74%  |
| Enabled  | 10        | 9.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 37        | 33.94%  |
| 4.01-8.0   | 24        | 22.02%  |
| 16.01-24.0 | 17        | 15.6%   |
| 8.01-16.0  | 16        | 14.68%  |
| 32.01-64.0 | 6         | 5.5%    |
| 1.01-2.0   | 6         | 5.5%    |
| 2.01-3.0   | 3         | 2.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 46        | 38.98%  |
| 2.01-3.0  | 33        | 27.97%  |
| 3.01-4.0  | 17        | 14.41%  |
| 4.01-8.0  | 13        | 11.02%  |
| 0.51-1.0  | 7         | 5.93%   |
| 8.01-16.0 | 2         | 1.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 84        | 77.06%  |
| 2      | 20        | 18.35%  |
| 3      | 4         | 3.67%   |
| 0      | 1         | 0.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 52.29%  |
| Yes       | 52        | 47.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 78.7%   |
| No        | 23        | 21.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 98.13%  |
| No        | 2         | 1.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 84.11%  |
| No        | 17        | 15.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Saudi Arabia | 107       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City     | Notebooks | Percent |
|----------|-----------|---------|
| Riyadh   | 44        | 39.64%  |
| Jeddah   | 26        | 23.42%  |
| Makkah   | 12        | 10.81%  |
| Medina   | 9         | 8.11%   |
| Dammam   | 5         | 4.5%    |
| Khobar   | 4         | 3.6%    |
| Thuwal   | 3         | 2.7%    |
| Al Qatif | 3         | 2.7%    |
| Dhahran  | 2         | 1.8%    |
| Ta'if    | 1         | 0.9%    |
| Al Hufuf | 1         | 0.9%    |
| Al Faruq | 1         | 0.9%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 29        | 36     | 22.48%  |
| WDC                       | 20        | 25     | 15.5%   |
| Toshiba                   | 20        | 26     | 15.5%   |
| Samsung Electronics       | 11        | 13     | 8.53%   |
| Kingston                  | 11        | 12     | 8.53%   |
| SanDisk                   | 8         | 8      | 6.2%    |
| Unknown                   | 4         | 5      | 3.1%    |
| SK hynix                  | 4         | 5      | 3.1%    |
| Intel                     | 4         | 9      | 3.1%    |
| Micron/Crucial Technology | 2         | 2      | 1.55%   |
| KingSpec                  | 2         | 2      | 1.55%   |
| Hitachi                   | 2         | 2      | 1.55%   |
| Fujitsu                   | 2         | 2      | 1.55%   |
| XrayDisk                  | 1         | 1      | 0.78%   |
| SPCC                      | 1         | 1      | 0.78%   |
| OYUNKEY                   | 1         | 1      | 0.78%   |
| Lexar                     | 1         | 1      | 0.78%   |
| KIOXIA                    | 1         | 1      | 0.78%   |
| JMicron Technology        | 1         | 1      | 0.78%   |
| Hewlett-Packard           | 1         | 1      | 0.78%   |
| Crucial                   | 1         | 1      | 0.78%   |
| China                     | 1         | 1      | 0.78%   |
| A-DATA Technology         | 1         | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 12        | 9.09%   |
| Toshiba MQ04ABF100 1TB                | 7         | 5.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 3.03%   |
| Kingston SA400S37480G 480GB SSD       | 4         | 3.03%   |
| SanDisk NVMe SSD Drive 128GB          | 3         | 2.27%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 2.27%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 1.52%   |
| Toshiba MQ01ABF050 500GB              | 2         | 1.52%   |
| Toshiba MQ01ABD100 1TB                | 2         | 1.52%   |
| Toshiba MQ01ABD075 752GB              | 2         | 1.52%   |
| SK hynix NVMe SSD Drive 1024GB        | 2         | 1.52%   |
| Seagate ST9500325AS 500GB             | 2         | 1.52%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 1.52%   |
| Samsung NVMe SSD Drive 1024GB         | 2         | 1.52%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 1.52%   |
| Intel SSDPEKNW512G8 512GB             | 2         | 1.52%   |
| Intel NVMe SSD Drive 1024GB           | 2         | 1.52%   |
| XrayDisk SSD 1TB                      | 1         | 0.76%   |
| WDC WDS500G2B0B-00YS70 500GB SSD      | 1         | 0.76%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 1         | 0.76%   |
| WDC WDS100T3X0C-00SJG0 1TB            | 1         | 0.76%   |
| WDC WD5000LPVX-08V0TT6 500GB          | 1         | 0.76%   |
| WDC WD5000LPCX-00VHAT0 500GB          | 1         | 0.76%   |
| WDC WD5000BEVT-08A0RT1 500GB          | 1         | 0.76%   |
| WDC WD3200BPVT-75ZEST0 320GB          | 1         | 0.76%   |
| WDC WD3200BEVT-00ZCT0 320GB           | 1         | 0.76%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 0.76%   |
| WDC WD10SPZX-75Z10T2 1TB              | 1         | 0.76%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.76%   |
| WDC WD10SPZX-22Z10T0 1TB              | 1         | 0.76%   |
| WDC WD10SPZX-08Z10 1TB                | 1         | 0.76%   |
| WDC WD10SPZX-00Z10T0 1TB              | 1         | 0.76%   |
| WDC WD10JPVX-55JC3T3 1TB              | 1         | 0.76%   |
| WDC WD10JPVX-00JC3T0 1TB              | 1         | 0.76%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 1         | 0.76%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB  | 1         | 0.76%   |
| Unknown SM32G  32GB                   | 1         | 0.76%   |
| Unknown SD64G  64GB                   | 1         | 0.76%   |
| Unknown MMC Card  64GB                | 1         | 0.76%   |
| Unknown MMC Card  16GB                | 1         | 0.76%   |
| Toshiba NVMe SSD Drive 512GB          | 1         | 0.76%   |
| Toshiba MQ01ABD050 500GB              | 1         | 0.76%   |
| Toshiba MK7559GSXF 752GB              | 1         | 0.76%   |
| Toshiba MK5075GSX 500GB               | 1         | 0.76%   |
| Toshiba MK5061GSYN 500GB              | 1         | 0.76%   |
| Toshiba MK3265GSX 320GB               | 1         | 0.76%   |
| Toshiba MK1234GAX 120GB               | 1         | 0.76%   |
| Toshiba KXG6AZNV512G 512GB            | 1         | 0.76%   |
| SPCC M.2 PCIe SSD 256GB               | 1         | 0.76%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 0.76%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 0.76%   |
| Seagate ST9320423AS 320GB             | 1         | 0.76%   |
| Seagate ST9160418ASG 160GB            | 1         | 0.76%   |
| Seagate ST500LM030-1RK17D 500GB       | 1         | 0.76%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 0.76%   |
| Seagate ST2000LX001-1RG174 2TB        | 1         | 0.76%   |
| Seagate ST2000LM015-2E8174 2TB        | 1         | 0.76%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 0.76%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 0.76%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 0.76%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 29        | 36     | 43.28%  |
| Toshiba | 19        | 21     | 28.36%  |
| WDC     | 15        | 19     | 22.39%  |
| Hitachi | 2         | 2      | 2.99%   |
| Fujitsu | 2         | 2      | 2.99%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 9         | 10     | 30%     |
| SanDisk             | 4         | 4      | 13.33%  |
| Samsung Electronics | 4         | 4      | 13.33%  |
| WDC                 | 2         | 2      | 6.67%   |
| SK hynix            | 2         | 3      | 6.67%   |
| KingSpec            | 2         | 2      | 6.67%   |
| XrayDisk            | 1         | 1      | 3.33%   |
| OYUNKEY             | 1         | 1      | 3.33%   |
| Lexar               | 1         | 1      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |
| China               | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 65        | 80     | 51.59%  |
| SSD     | 30        | 32     | 23.81%  |
| NVMe    | 26        | 39     | 20.63%  |
| MMC     | 4         | 5      | 3.17%   |
| Unknown | 1         | 1      | 0.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 86        | 112    | 73.5%   |
| NVMe | 26        | 39     | 22.22%  |
| MMC  | 4         | 5      | 3.42%   |
| SAS  | 1         | 1      | 0.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 54     | 48.91%  |
| 0.51-1.0   | 44        | 55     | 47.83%  |
| 1.01-2.0   | 3         | 3      | 3.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 31        | 27.68%  |
| 251-500        | 28        | 25%     |
| 101-250        | 24        | 21.43%  |
| 51-100         | 11        | 9.82%   |
| 1-20           | 6         | 5.36%   |
| 21-50          | 4         | 3.57%   |
| 1001-2000      | 4         | 3.57%   |
| Unknown        | 2         | 1.79%   |
| More than 3000 | 1         | 0.89%   |
| 2001-3000      | 1         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 46        | 39.32%  |
| 21-50    | 33        | 28.21%  |
| 51-100   | 15        | 12.82%  |
| 251-500  | 9         | 7.69%   |
| 101-250  | 9         | 7.69%   |
| 501-1000 | 3         | 2.56%   |
| Unknown  | 2         | 1.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 20%     |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 20%     |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 20%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 20%     |
| OYUNKEY SSD 120GB                  | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| OYUNKEY | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Toshiba | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 80%     |
| SSD  | 1         | 1      | 20%     |

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
| Detected | 76        | 105    | 67.26%  |
| Works    | 32        | 47     | 28.32%  |
| Malfunc  | 5         | 5      | 4.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 91        | 75.21%  |
| SanDisk                          | 7         | 5.79%   |
| Samsung Electronics              | 7         | 5.79%   |
| AMD                              | 6         | 4.96%   |
| Toshiba America Info Systems     | 2         | 1.65%   |
| SK hynix                         | 2         | 1.65%   |
| Micron/Crucial Technology        | 2         | 1.65%   |
| Kingston Technology Company      | 2         | 1.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.83%   |
| Realtek Semiconductor            | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 14        | 11.11%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 10        | 7.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 10        | 7.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 8         | 6.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 7         | 5.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 6         | 4.76%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 4         | 3.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 3.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 3.17%   |
| SanDisk PC SN520 NVMe SSD                                                              | 3         | 2.38%   |
| Intel SSD 660P Series                                                                  | 3         | 2.38%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 1.59%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 2         | 1.59%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.59%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 2         | 1.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 1.59%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.59%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.59%   |
| SK hynix PC300 NVMe Solid State Drive 1TB                                              | 1         | 0.79%   |
| SK hynix Gold P31 SSD                                                                  | 1         | 0.79%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 0.79%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.79%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 0.79%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 1         | 0.79%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.79%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 0.79%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 1         | 0.79%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.79%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 0.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 1         | 0.79%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.79%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.79%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 0.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 0.79%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 82        | 67.21%  |
| NVMe | 26        | 21.31%  |
| RAID | 8         | 6.56%   |
| IDE  | 6         | 4.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 98        | 91.59%  |
| AMD    | 9         | 8.41%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 6.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 3.74%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.8%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.8%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 2.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.8%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 2.8%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 2.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.87%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.87%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.87%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.87%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.87%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.87%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.87%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.87%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.87%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 2         | 1.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.87%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.87%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.93%   |
| Intel Pentium CPU N3510 @ 1.99GHz             | 1         | 0.93%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.93%   |
| Intel Mobile Pentium 4 - M CPU 2.20GHz        | 1         | 0.93%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.93%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.93%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.93%   |
| Intel Core i7-3635QM CPU @ 2.40GHz            | 1         | 0.93%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.93%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.93%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.93%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.93%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 0.93%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 0.93%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 0.93%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 0.93%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 0.93%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 0.93%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 0.93%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 0.93%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 0.93%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 0.93%   |
| Intel Celeron CPU 925 @ 2.30GHz               | 1         | 0.93%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 1         | 0.93%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 0.93%   |
| Intel Atom CPU Z3740 @ 1.33GHz                | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 33        | 30.84%  |
| Intel Core i5           | 33        | 30.84%  |
| Intel Celeron           | 11        | 10.28%  |
| Intel Core i3           | 9         | 8.41%   |
| AMD Ryzen 5             | 5         | 4.67%   |
| Other                   | 3         | 2.8%    |
| Intel Core 2 Duo        | 3         | 2.8%    |
| Intel Pentium           | 2         | 1.87%   |
| Intel Atom              | 2         | 1.87%   |
| AMD Ryzen 9             | 2         | 1.87%   |
| Intel Pentium Dual-Core | 1         | 0.93%   |
| Intel Mobile Pentium 4  | 1         | 0.93%   |
| AMD E2                  | 1         | 0.93%   |
| AMD A12                 | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 64        | 59.81%  |
| 4      | 29        | 27.1%   |
| 6      | 9         | 8.41%   |
| 1      | 3         | 2.8%    |
| 8      | 2         | 1.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 83        | 77.57%  |
| 1      | 24        | 22.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 102       | 94.44%  |
| Unknown        | 4         | 3.7%    |
| 32-bit         | 2         | 1.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 24.78%  |
| 0x40651    | 11        | 9.73%   |
| 0x306a9    | 10        | 8.85%   |
| 0x206a7    | 7         | 6.19%   |
| 0x806ea    | 5         | 4.42%   |
| 0x706a1    | 5         | 4.42%   |
| 0x406e3    | 5         | 4.42%   |
| 0x806ec    | 4         | 3.54%   |
| 0x806e9    | 4         | 3.54%   |
| 0x1067a    | 4         | 3.54%   |
| 0x906ea    | 3         | 2.65%   |
| 0x806c1    | 3         | 2.65%   |
| 0x706e5    | 3         | 2.65%   |
| 0x20655    | 3         | 2.65%   |
| 0x20652    | 3         | 2.65%   |
| 0x306d4    | 2         | 1.77%   |
| 0x30673    | 2         | 1.77%   |
| 0xf27      | 1         | 0.88%   |
| 0xa0652    | 1         | 0.88%   |
| 0x906e9    | 1         | 0.88%   |
| 0x806eb    | 1         | 0.88%   |
| 0x6fa      | 1         | 0.88%   |
| 0x306c3    | 1         | 0.88%   |
| 0x08600106 | 1         | 0.88%   |
| 0x08600104 | 1         | 0.88%   |
| 0x08108109 | 1         | 0.88%   |
| 0x0810100b | 1         | 0.88%   |
| 0x0600611a | 1         | 0.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 27        | 25.23%  |
| Haswell       | 12        | 11.21%  |
| IvyBridge     | 11        | 10.28%  |
| Goldmont plus | 8         | 7.48%   |
| Westmere      | 7         | 6.54%   |
| Skylake       | 7         | 6.54%   |
| SandyBridge   | 7         | 6.54%   |
| Penryn        | 4         | 3.74%   |
| TigerLake     | 3         | 2.8%    |
| IceLake       | 3         | 2.8%    |
| Zen+          | 2         | 1.87%   |
| Zen 3         | 2         | 1.87%   |
| Zen 2         | 2         | 1.87%   |
| Silvermont    | 2         | 1.87%   |
| Broadwell     | 2         | 1.87%   |
| Zen           | 1         | 0.93%   |
| NetBurst      | 1         | 0.93%   |
| Goldmont      | 1         | 0.93%   |
| Excavator     | 1         | 0.93%   |
| Core          | 1         | 0.93%   |
| CometLake     | 1         | 0.93%   |
| Bonnell       | 1         | 0.93%   |
| Bobcat        | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 93        | 64.14%  |
| Nvidia                           | 30        | 20.69%  |
| AMD                              | 21        | 14.48%  |
| Silicon Integrated Systems [SiS] | 1         | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 11        | 7.53%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 11        | 7.53%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 8         | 5.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 4.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 7         | 4.79%   |
| Intel UHD Graphics 620                                                        | 6         | 4.11%   |
| Intel HD Graphics 620                                                         | 6         | 4.11%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 4.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6         | 4.11%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 2.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 4         | 2.74%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                   | 3         | 2.05%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 2.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 2.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 2.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 2.05%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                  | 3         | 2.05%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 2         | 1.37%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.37%   |
| Intel HD Graphics 5500                                                        | 2         | 1.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.37%   |
| AMD Renoir                                                                    | 2         | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.37%   |
| AMD Cezanne                                                                   | 2         | 1.37%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter     | 1         | 0.68%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                        | 1         | 0.68%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                         | 1         | 0.68%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.68%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                          | 1         | 0.68%   |
| Nvidia GP107M [GeForce MX350]                                                 | 1         | 0.68%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.68%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                  | 1         | 0.68%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.68%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 0.68%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.68%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 0.68%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.68%   |
| Nvidia GK107M [GeForce GT 750M]                                               | 1         | 0.68%   |
| Nvidia GK104M [GeForce GTX 670MX]                                             | 1         | 0.68%   |
| Nvidia GF119M [GeForce GT 520M]                                               | 1         | 0.68%   |
| Nvidia GF119M [GeForce GT 520MX]                                              | 1         | 0.68%   |
| Nvidia GF114M [GeForce GTX 670M]                                              | 1         | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 0.68%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 1         | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 0.68%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                             | 1         | 0.68%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 0.68%   |
| Intel HD Graphics 630                                                         | 1         | 0.68%   |
| Intel HD Graphics 500                                                         | 1         | 0.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 0.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 0.68%   |
| AMD Wrestler [Radeon HD 7340]                                                 | 1         | 0.68%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 1         | 0.68%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 1         | 0.68%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 1         | 0.68%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                             | 1         | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 0.68%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                      | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 52.78%  |
| Intel + Nvidia | 26        | 24.07%  |
| Intel + AMD    | 10        | 9.26%   |
| 1 x AMD        | 10        | 9.26%   |
| 1 x Nvidia     | 2         | 1.85%   |
| AMD + Nvidia   | 2         | 1.85%   |
| 1 x SiS        | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 94        | 86.24%  |
| Proprietary | 14        | 12.84%  |
| Unknown     | 1         | 0.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 66.67%  |
| 1.01-2.0   | 16        | 14.81%  |
| 0.51-1.0   | 7         | 6.48%   |
| 3.01-4.0   | 6         | 5.56%   |
| 2.01-3.0   | 3         | 2.78%   |
| 0.01-0.5   | 3         | 2.78%   |
| 7.01-8.0   | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 32        | 27.83%  |
| LG Display           | 21        | 18.26%  |
| AU Optronics         | 18        | 15.65%  |
| Chimei Innolux       | 13        | 11.3%   |
| Samsung Electronics  | 6         | 5.22%   |
| Lenovo               | 4         | 3.48%   |
| Dell                 | 4         | 3.48%   |
| Sharp                | 3         | 2.61%   |
| Unknown              | 2         | 1.74%   |
| Sony                 | 2         | 1.74%   |
| PANDA                | 2         | 1.74%   |
| ___                  | 1         | 0.87%   |
| ViewSonic            | 1         | 0.87%   |
| SKY                  | 1         | 0.87%   |
| InnoLux Display      | 1         | 0.87%   |
| InfoVision           | 1         | 0.87%   |
| Goldstar             | 1         | 0.87%   |
| Apple                | 1         | 0.87%   |
| Ancor Communications | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 4         | 3.45%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                | 3         | 2.59%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 3         | 2.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 2.59%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 2         | 1.72%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch | 2         | 1.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 1.72%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch      | 2         | 1.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 1.72%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                | 2         | 1.72%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                | 2         | 1.72%   |
| ___ LCDTV16 ___9000 1360x768                                         | 1         | 0.86%   |
| ViewSonic VA712-2SERIES VSC941C 1280x1024 338x270mm 17.0-inch        | 1         | 0.86%   |
| Unknown SMART TV 6488 3840x2160 1209x680mm 54.6-inch                 | 1         | 0.86%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1         | 0.86%   |
| Sony TV SNYAC03 1360x768                                             | 1         | 0.86%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                | 1         | 0.86%   |
| SKY TV Monitor SKY0001 1920x1080 885x498mm 40.0-inch                 | 1         | 0.86%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch              | 1         | 0.86%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch              | 1         | 0.86%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch              | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch | 1         | 0.86%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch              | 1         | 0.86%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 0.86%   |
| LG Display LCD Monitor LGD05E8 1920x1080 344x194mm 15.5-inch         | 1         | 0.86%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch         | 1         | 0.86%   |
| LG Display LCD Monitor LGD04B6 1366x768 309x174mm 14.0-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch         | 1         | 0.86%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 1         | 0.86%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD03FF 1920x1080 309x175mm 14.0-inch         | 1         | 0.86%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD01E1 1366x768 310x174mm 14.0-inch          | 1         | 0.86%   |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch             | 1         | 0.86%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 1         | 0.86%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 1         | 0.86%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch              | 1         | 0.86%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch     | 1         | 0.86%   |
| InfoVision LCD Monitor IVO8C5F 1920x1080 309x174mm 14.0-inch         | 1         | 0.86%   |
| Goldstar 27GL850 GSM5B80 2560x1440 697x392mm 31.5-inch               | 1         | 0.86%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                    | 1         | 0.86%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                    | 1         | 0.86%   |
| Dell U2413 DELF047 1920x1200 520x320mm 24.0-inch                     | 1         | 0.86%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                   | 1         | 0.86%   |
| Dell P2314H DEL4098 1920x1080 510x290mm 23.1-inch                    | 1         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 1         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 344x194mm 15.5-inch     | 1         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch      | 1         | 0.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 58        | 51.79%  |
| 1920x1080 (FHD)   | 39        | 34.82%  |
| 3840x2160 (4K)    | 4         | 3.57%   |
| 2560x1440 (QHD)   | 2         | 1.79%   |
| 1360x768          | 2         | 1.79%   |
| 3840x2400         | 1         | 0.89%   |
| 2160x1440         | 1         | 0.89%   |
| 1920x1200 (WUXGA) | 1         | 0.89%   |
| 1600x900 (HD+)    | 1         | 0.89%   |
| 1440x900 (WXGA+)  | 1         | 0.89%   |
| 1280x800 (WXGA)   | 1         | 0.89%   |
| 1280x1024 (SXGA)  | 1         | 0.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 64        | 55.17%  |
| 13      | 19        | 16.38%  |
| 14      | 15        | 12.93%  |
| 24      | 4         | 3.45%   |
| 12      | 3         | 2.59%   |
| 72      | 2         | 1.72%   |
| 27      | 2         | 1.72%   |
| 17      | 2         | 1.72%   |
| 54      | 1         | 0.86%   |
| 40      | 1         | 0.86%   |
| 31      | 1         | 0.86%   |
| 23      | 1         | 0.86%   |
| Unknown | 1         | 0.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 93        | 82.3%   |
| 201-300     | 6         | 5.31%   |
| 501-600     | 5         | 4.42%   |
| 351-400     | 3         | 2.65%   |
| 1501-2000   | 2         | 1.77%   |
| 801-900     | 1         | 0.88%   |
| 601-700     | 1         | 0.88%   |
| 1001-1500   | 1         | 0.88%   |
| Unknown     | 1         | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 98        | 95.15%  |
| 16/10 | 3         | 2.91%   |
| 5/4   | 1         | 0.97%   |
| 3/2   | 1         | 0.97%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 63        | 54.31%  |
| 81-90          | 32        | 27.59%  |
| 201-250        | 4         | 3.45%   |
| More than 1000 | 3         | 2.59%   |
| 61-70          | 3         | 2.59%   |
| 71-80          | 2         | 1.72%   |
| 301-350        | 2         | 1.72%   |
| 351-500        | 1         | 0.86%   |
| 251-300        | 1         | 0.86%   |
| 141-150        | 1         | 0.86%   |
| 121-130        | 1         | 0.86%   |
| 501-1000       | 1         | 0.86%   |
| 91-100         | 1         | 0.86%   |
| Unknown        | 1         | 0.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 57        | 50.44%  |
| 121-160       | 37        | 32.74%  |
| 51-100        | 10        | 8.85%   |
| More than 240 | 3         | 2.65%   |
| 1-50          | 3         | 2.65%   |
| 161-240       | 2         | 1.77%   |
| Unknown       | 1         | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 95        | 87.16%  |
| 2     | 8         | 7.34%   |
| 0     | 3         | 2.75%   |
| 3     | 2         | 1.83%   |
| 4     | 1         | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 71        | 41.04%  |
| Intel                            | 37        | 21.39%  |
| Qualcomm Atheros                 | 35        | 20.23%  |
| Broadcom                         | 10        | 5.78%   |
| Ralink                           | 4         | 2.31%   |
| Samsung Electronics              | 2         | 1.16%   |
| Ralink Technology                | 2         | 1.16%   |
| MediaTek                         | 2         | 1.16%   |
| Marvell Technology Group         | 2         | 1.16%   |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |
| Qualcomm                         | 1         | 0.58%   |
| OPPO Electronics                 | 1         | 0.58%   |
| Microsoft                        | 1         | 0.58%   |
| ICS Advent                       | 1         | 0.58%   |
| Broadcom Limited                 | 1         | 0.58%   |
| ASIX Electronics                 | 1         | 0.58%   |
| Apple                            | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 37        | 18.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 23        | 11.39%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 13        | 6.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 9         | 4.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 7         | 3.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 5         | 2.48%   |
| Intel Wireless 8265 / 8275                                                     | 5         | 2.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 4         | 1.98%   |
| Intel Wireless 8260                                                            | 4         | 1.98%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 4         | 1.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 3         | 1.49%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 3         | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 3         | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                                     | 2         | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 0.99%   |
| Intel Wireless 7265                                                            | 2         | 0.99%   |
| Intel Wireless 7260                                                            | 2         | 0.99%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 0.99%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.99%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.99%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                        | 1         | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.5%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.5%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 1         | 0.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 1         | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 0.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 1         | 0.5%    |
| Realtek RTL8187B Wireless Adapter                                              | 1         | 0.5%    |
| Realtek RTL8187 Wireless Adapter                                               | 1         | 0.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1         | 0.5%    |
| Ralink RT2070 Wireless Adapter                                                 | 1         | 0.5%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.5%    |
| Qualcomm QCA6390 Wireless Network Adapter                                      | 1         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.5%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.5%    |
| OPPO Find X2 Lite                                                              | 1         | 0.5%    |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 0.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.5%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.5%    |
| Intel Wireless-AC 9260                                                         | 1         | 0.5%    |
| Intel Wireless 3165                                                            | 1         | 0.5%    |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.5%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.5%    |
| Intel Ethernet Connection I219-V                                               | 1         | 0.5%    |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 32.73%  |
| Qualcomm Atheros      | 31        | 28.18%  |
| Realtek Semiconductor | 26        | 23.64%  |
| Broadcom              | 7         | 6.36%   |
| Ralink                | 4         | 3.64%   |
| Ralink Technology     | 2         | 1.82%   |
| MediaTek              | 2         | 1.82%   |
| Qualcomm              | 1         | 0.91%   |
| Broadcom Limited      | 1         | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 11.82%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 8.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 6.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 4.55%   |
| Intel Wireless 8265 / 8275                                              | 5         | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.64%   |
| Intel Wireless 8260                                                     | 4         | 3.64%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 3.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 2.73%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 2.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.82%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.82%   |
| Intel Wireless 7265                                                     | 2         | 1.82%   |
| Intel Wireless 7260                                                     | 2         | 1.82%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.91%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.91%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.91%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.91%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.91%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.91%   |
| Realtek RTL8187 Wireless Adapter                                        | 1         | 0.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.91%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.91%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.91%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 1         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.91%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.91%   |
| Intel Wireless 3165                                                     | 1         | 0.91%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.91%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.91%   |
| Intel Centrino Wireless-N + WiMAX 6150                                  | 1         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.91%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.91%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 0.91%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 0.91%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 0.91%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 60        | 65.93%  |
| Intel                            | 11        | 12.09%  |
| Qualcomm Atheros                 | 5         | 5.49%   |
| Broadcom                         | 5         | 5.49%   |
| Samsung Electronics              | 2         | 2.2%    |
| Marvell Technology Group         | 2         | 2.2%    |
| Silicon Integrated Systems [SiS] | 1         | 1.1%    |
| OPPO Electronics                 | 1         | 1.1%    |
| Microsoft                        | 1         | 1.1%    |
| ICS Advent                       | 1         | 1.1%    |
| ASIX Electronics                 | 1         | 1.1%    |
| Apple                            | 1         | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 37        | 40.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 23        | 25.27%  |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 2.2%    |
| Intel Ethernet Connection I219-LM                                              | 2         | 2.2%    |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.2%    |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 1.1%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.1%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.1%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.1%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.1%    |
| OPPO Find X2 Lite                                                              | 1         | 1.1%    |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 1.1%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.1%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 1.1%    |
| Intel Ethernet Connection I219-V                                               | 1         | 1.1%    |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.1%    |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.1%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.1%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 1.1%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.1%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.1%    |
| Apple iPad 4/Mini1                                                             | 1         | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 54.97%  |
| Ethernet | 85        | 44.5%   |
| Modem    | 1         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 89        | 79.46%  |
| Ethernet | 23        | 20.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 80        | 74.77%  |
| 1     | 26        | 24.3%   |
| 0     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 92        | 85.19%  |
| Yes  | 16        | 14.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 29.67%  |
| Qualcomm Atheros Communications | 17        | 18.68%  |
| Realtek Semiconductor           | 12        | 13.19%  |
| IMC Networks                    | 8         | 8.79%   |
| Foxconn / Hon Hai               | 8         | 8.79%   |
| Lite-On Technology              | 5         | 5.49%   |
| Broadcom                        | 4         | 4.4%    |
| Ralink                          | 3         | 3.3%    |
| Toshiba                         | 2         | 2.2%    |
| Dell                            | 2         | 2.2%    |
| Realtek                         | 1         | 1.1%    |
| Qcom                            | 1         | 1.1%    |
| Apple                           | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 14        | 15.38%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 8.79%   |
| Realtek Bluetooth Radio                                                             | 6         | 6.59%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 5.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 5.49%   |
| IMC Networks Bluetooth Device                                                       | 5         | 5.49%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 3.3%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 3.3%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 3.3%    |
| IMC Networks Bluetooth Radio                                                        | 3         | 3.3%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 2.2%    |
| Intel Bluetooth Device                                                              | 2         | 2.2%    |
| Intel AX200 Bluetooth                                                               | 2         | 2.2%    |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 2.2%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 2.2%    |
| Foxconn / Hon Hai BCM43142A0                                                        | 2         | 2.2%    |
| Toshiba Bluetooth Device                                                            | 1         | 1.1%    |
| Toshiba Askey for                                                                   | 1         | 1.1%    |
| Realtek RTL8723A Bluetooth                                                          | 1         | 1.1%    |
| Realtek Bluetooth Radio                                                             | 1         | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.1%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.1%    |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 1.1%    |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 1.1%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 1.1%    |
| Lite-On Bluetooth Device                                                            | 1         | 1.1%    |
| Lite-On BCM43142A0                                                                  | 1         | 1.1%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.1%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.1%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.1%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.1%    |
| Dell Wireless 365 Bluetooth                                                         | 1         | 1.1%    |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.1%    |
| Broadcom HP Portable Valentine                                                      | 1         | 1.1%    |
| Broadcom Bluetooth                                                                  | 1         | 1.1%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.1%    |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 96        | 78.05%  |
| Nvidia                           | 14        | 11.38%  |
| AMD                              | 11        | 8.94%   |
| Silicon Integrated Systems [SiS] | 1         | 0.81%   |
| Samson Technologies              | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 20        | 13.7%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 7.53%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 7.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 7.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 5.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 4.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 4.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 4.79%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 4.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 3.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 2.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 2.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2.05%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.37%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.37%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1         | 0.68%   |
| Samson Technologies GoMic compact condenser mic                            | 1         | 0.68%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.68%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.68%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.68%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.68%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.68%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.68%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 0.68%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.68%   |
| AMD FCH Azalia Controller                                                  | 1         | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung Electronics                  | 14        | 25%     |
| SK hynix                             | 12        | 21.43%  |
| Micron Technology                    | 8         | 14.29%  |
| Crucial                              | 5         | 8.93%   |
| Unknown                              | 3         | 5.36%   |
| Kingston                             | 3         | 5.36%   |
| Elpida                               | 2         | 3.57%   |
| Unknown (ABCD)                       | 1         | 1.79%   |
| Toshiba                              | 1         | 1.79%   |
| Team                                 | 1         | 1.79%   |
| Silicon Power                        | 1         | 1.79%   |
| Ramaxel Technology                   | 1         | 1.79%   |
| Nanya Technology                     | 1         | 1.79%   |
| Hikvision                            | 1         | 1.79%   |
| Chun Well Technology Holding Limited | 1         | 1.79%   |
| ASint Technology                     | 1         | 1.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                         | 3         | 5.08%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s                        | 2         | 3.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                         | 2         | 3.39%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s                      | 2         | 3.39%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                                | 1         | 1.69%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                           | 1         | 1.69%   |
| Unknown RAM Module 2GB SODIMM DDR2                                            | 1         | 1.69%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                         | 1         | 1.69%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s           | 1         | 1.69%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 1066MT/s                         | 1         | 1.69%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s                          | 1         | 1.69%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                                  | 1         | 1.69%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s                      | 1         | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s                     | 1         | 1.69%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.69%   |
| SK hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s                      | 1         | 1.69%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 4GB SODIMM DDR4 3200MT/s                        | 1         | 1.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                        | 1         | 1.69%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s                        | 1         | 1.69%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s                       | 1         | 1.69%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                        | 1         | 1.69%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                        | 1         | 1.69%   |
| Silicon Power RAM DBST8GN128S 8GB SODIMM DDR3 1333MT/s                        | 1         | 1.69%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                         | 1         | 1.69%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                         | 1         | 1.69%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                         | 1         | 1.69%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                         | 1         | 1.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                         | 1         | 1.69%   |
| Samsung RAM M471B1G73CB0-CK0 8GB SODIMM DDR3 1600MT/s                         | 1         | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s                   | 1         | 1.69%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                         | 1         | 1.69%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                         | 1         | 1.69%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s                     | 1         | 1.69%   |
| Nanya RAM NT1GC64BH4B0PS-CG 1GB SODIMM DDR3 1333MT/s                          | 1         | 1.69%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s                 | 1         | 1.69%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s                      | 1         | 1.69%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.69%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s                         | 1         | 1.69%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                          | 1         | 1.69%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s                         | 1         | 1.69%   |
| Micron RAM 16KTF51264HZ-1G4M1 4096MB SODIMM DDR3 1333MT/s                     | 1         | 1.69%   |
| Micron RAM 16ATF1G64HZ-2G1A2 8GB SODIMM DDR4 2133MT/s                         | 1         | 1.69%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                              | 1         | 1.69%   |
| Kingston RAM ACR256X64D3S1333C9 2048MB SODIMM DDR3 1334MT/s                   | 1         | 1.69%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s                       | 1         | 1.69%   |
| Hikvision RAM HKED4162DAA1D0MA1 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.69%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s                        | 1         | 1.69%   |
| Crucial RAM CT8G4SFS824A.C8FJ 8GB SODIMM DDR4 2400MT/s                        | 1         | 1.69%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16384MB SODIMM DDR4 3200MT/s                   | 1         | 1.69%   |
| Crucial RAM CB8GS2400.C8JT 8GB SODIMM DDR4 2400MT/s                           | 1         | 1.69%   |
| Crucial RAM BL16G32C16S4B.M16FE1 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.69%   |
| Chun Well Holding Limited RAM CL19-19-19 D4-2666 16384MB SODIMM DDR4 2667MT/s | 1         | 1.69%   |
| ASint RAM SSA302G08-GDJEC 4096MB SODIMM DDR3 1334MT/s                         | 1         | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 19        | 43.18%  |
| DDR3   | 18        | 40.91%  |
| DDR2   | 3         | 6.82%   |
| LPDDR4 | 2         | 4.55%   |
| SDRAM  | 1         | 2.27%   |
| LPDDR3 | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 93.02%  |
| Row Of Chips | 3         | 6.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 18        | 37.5%   |
| 4096  | 17        | 35.42%  |
| 2048  | 7         | 14.58%  |
| 16384 | 5         | 10.42%  |
| 1024  | 1         | 2.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 12        | 23.08%  |
| 2667    | 10        | 19.23%  |
| 3200    | 6         | 11.54%  |
| 1334    | 5         | 9.62%   |
| 2400    | 4         | 7.69%   |
| 3266    | 3         | 5.77%   |
| 1333    | 3         | 5.77%   |
| 2133    | 2         | 3.85%   |
| 4267    | 1         | 1.92%   |
| 4199    | 1         | 1.92%   |
| 1067    | 1         | 1.92%   |
| 1066    | 1         | 1.92%   |
| 975     | 1         | 1.92%   |
| 800     | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

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
| Chicony Electronics                    | 19        | 20.43%  |
| IMC Networks                           | 18        | 19.35%  |
| Microdia                               | 10        | 10.75%  |
| Realtek Semiconductor                  | 9         | 9.68%   |
| Lite-On Technology                     | 6         | 6.45%   |
| Suyin                                  | 5         | 5.38%   |
| Sunplus Innovation Technology          | 5         | 5.38%   |
| Acer                                   | 5         | 5.38%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.23%   |
| Ricoh                                  | 2         | 2.15%   |
| Quanta                                 | 2         | 2.15%   |
| Importek                               | 2         | 2.15%   |
| Alcor Micro                            | 2         | 2.15%   |
| Silicon Motion                         | 1         | 1.08%   |
| Samsung Electronics                    | 1         | 1.08%   |
| Logitech                               | 1         | 1.08%   |
| Lenovo                                 | 1         | 1.08%   |
| Apple                                  | 1         | 1.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                      | 12        | 12.9%   |
| Chicony Integrated Camera                               | 7         | 7.53%   |
| Microdia Integrated_Webcam_HD                           | 5         | 5.38%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 4.3%    |
| Sunplus Integrated_Webcam_HD                            | 3         | 3.23%   |
| Lite-On HP TrueVision HD Camera                         | 3         | 3.23%   |
| Sunplus HD WebCam                                       | 2         | 2.15%   |
| Realtek Integrated Webcam HD                            | 2         | 2.15%   |
| Realtek Integrated Webcam                               | 2         | 2.15%   |
| Realtek HP Truevision HD integrated webcam              | 2         | 2.15%   |
| Microdia HP Webcam-101                                  | 2         | 2.15%   |
| Chicony HD WebCam                                       | 2         | 2.15%   |
| Alcor Micro Asus Integrated Webcam                      | 2         | 2.15%   |
| Suyin USB 2.0 Camera                                    | 1         | 1.08%   |
| Suyin Integrated_Webcam_HD                              | 1         | 1.08%   |
| Suyin HP TrueVision HD                                  | 1         | 1.08%   |
| Suyin HP Integrated Webcam                              | 1         | 1.08%   |
| Suyin 1.3M HD WebCam                                    | 1         | 1.08%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 1         | 1.08%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 1         | 1.08%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870]     | 1         | 1.08%   |
| Ricoh USB2.0 Camera                                     | 1         | 1.08%   |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 1.08%   |
| Realtek Integrated_Webcam_HD                            | 1         | 1.08%   |
| Realtek HP Truevision HD                                | 1         | 1.08%   |
| Quanta LG Webcam                                        | 1         | 1.08%   |
| Quanta HP Wide Vision HD Camera                         | 1         | 1.08%   |
| Microdia Sonix USB 2.0 Camera                           | 1         | 1.08%   |
| Microdia Lenovo EasyCamera                              | 1         | 1.08%   |
| Microdia Integrated Webcam                              | 1         | 1.08%   |
| Logitech C922 Pro Stream Webcam                         | 1         | 1.08%   |
| Lite-On TOSHIBA Web Camera - HD                         | 1         | 1.08%   |
| Lite-On HP Webcam                                       | 1         | 1.08%   |
| Lite-On HP HD Camera                                    | 1         | 1.08%   |
| Lenovo Integrated Webcam [R5U877]                       | 1         | 1.08%   |
| Importek TOSHIBA Web Camera - HD                        | 1         | 1.08%   |
| Importek TOSHIBA Web Camera - FHD                       | 1         | 1.08%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 1.08%   |
| IMC Networks imx188_azurewave(p)                        | 1         | 1.08%   |
| Chicony USB2.0 VGA UVC WebCam                           | 1         | 1.08%   |
| Chicony USB2.0 UVC WebCam                               | 1         | 1.08%   |
| Chicony Integrated Camera (1280x720@30)                 | 1         | 1.08%   |
| Chicony HP Wide Vision HD Camera                        | 1         | 1.08%   |
| Chicony HP Webcam [2 MP Macro]                          | 1         | 1.08%   |
| Chicony HP Truevision HD                                | 1         | 1.08%   |
| Chicony HD WebCam (Acer)                                | 1         | 1.08%   |
| Chicony HD User Facing                                  | 1         | 1.08%   |
| Chicony Front Camera                                    | 1         | 1.08%   |
| Chicony Acer CrystalEye Webcam                          | 1         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 1         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera        | 1         | 1.08%   |
| Apple FaceTime HD Camera                                | 1         | 1.08%   |
| Acer SunplusIT Integrated Camera                        | 1         | 1.08%   |
| Acer Lenovo EasyCamera                                  | 1         | 1.08%   |
| Acer Integrated Camera                                  | 1         | 1.08%   |
| Acer Front Camera                                       | 1         | 1.08%   |
| Acer BisonCam, NB Pro                                   | 1         | 1.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 35.71%  |
| Upek                       | 2         | 14.29%  |
| Shenzhen Goodix Technology | 2         | 14.29%  |
| LighTuning Technology      | 2         | 14.29%  |
| Elan Microelectronics      | 2         | 14.29%  |
| Validity Sensors           | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 14.29%  |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 7.14%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.14%   |
| Shenzhen Goodix FingerPrint                            | 1         | 7.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 7.14%   |
| Elan ELAN:Fingerprint                                  | 1         | 7.14%   |
| Elan ELAN:ARM-M4                                       | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 75%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 50%     |
| Broadcom 5880                                                                | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 74        | 67.89%  |
| 1     | 31        | 28.44%  |
| 2     | 2         | 1.83%   |
| 4     | 1         | 0.92%   |
| 3     | 1         | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 35.9%   |
| Graphics card            | 7         | 17.95%  |
| Net/wireless             | 6         | 15.38%  |
| Chipcard                 | 4         | 10.26%  |
| Bluetooth                | 3         | 7.69%   |
| Multimedia controller    | 2         | 5.13%   |
| Modem                    | 1         | 2.56%   |
| Communication controller | 1         | 2.56%   |
| Camera                   | 1         | 2.56%   |

