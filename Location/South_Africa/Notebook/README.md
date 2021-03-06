Linux in South Africa - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------------

A project to collect tested hardware configurations for Linux in South Africa.

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

Total: 727

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6400              | [1c5025c952](https://linux-hardware.org/?probe=1c5025c952) | Jul 01, 2022 |
| Dell          | Latitude E6400              | [a47d49bfab](https://linux-hardware.org/?probe=a47d49bfab) | Jul 01, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [7d85e08611](https://linux-hardware.org/?probe=7d85e08611) | Jun 29, 2022 |
| Acer          | Aspire A515-51G             | [4178b8c79f](https://linux-hardware.org/?probe=4178b8c79f) | Jun 28, 2022 |
| Acer          | Aspire A515-51G             | [1571a4ab8e](https://linux-hardware.org/?probe=1571a4ab8e) | Jun 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [3e451a9d00](https://linux-hardware.org/?probe=3e451a9d00) | Jun 28, 2022 |
| HP            | Pavilion dv7                | [6338462156](https://linux-hardware.org/?probe=6338462156) | Jun 27, 2022 |
| Acer          | TMP453-MG                   | [e2790ebf7e](https://linux-hardware.org/?probe=e2790ebf7e) | Jun 23, 2022 |
| Acer          | TMP453-MG                   | [c99aceab3b](https://linux-hardware.org/?probe=c99aceab3b) | Jun 23, 2022 |
| Dell          | Latitude 5490               | [f0726860d4](https://linux-hardware.org/?probe=f0726860d4) | Jun 23, 2022 |
| Acer          | Swift SF314-54              | [3e80b4439f](https://linux-hardware.org/?probe=3e80b4439f) | Jun 22, 2022 |
| Toshiba       | Satellite L655              | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| Dell          | Latitude E6540              | [93f049609f](https://linux-hardware.org/?probe=93f049609f) | Jun 16, 2022 |
| Lenovo        | V15-IIL 82C5                | [bf09de57ad](https://linux-hardware.org/?probe=bf09de57ad) | Jun 14, 2022 |
| Intel         | (R) Education Tablet        | [a776aa706c](https://linux-hardware.org/?probe=a776aa706c) | Jun 13, 2022 |
| Intel         | (R) Education Tablet        | [8c47e36905](https://linux-hardware.org/?probe=8c47e36905) | Jun 13, 2022 |
| HP            | Laptop 15-bs0xx             | [a5474363da](https://linux-hardware.org/?probe=a5474363da) | Jun 12, 2022 |
| Lenovo        | E50-70 80JA                 | [2eb0d9bb23](https://linux-hardware.org/?probe=2eb0d9bb23) | Jun 11, 2022 |
| Lenovo        | E50-70 80JA                 | [1391106844](https://linux-hardware.org/?probe=1391106844) | Jun 10, 2022 |
| Dell          | Inspiron 3542               | [cf46fd5c4e](https://linux-hardware.org/?probe=cf46fd5c4e) | Jun 03, 2022 |
| Dell          | Inspiron 3542               | [94db4f10be](https://linux-hardware.org/?probe=94db4f10be) | Jun 03, 2022 |
| Dell          | G5 5590                     | [4e53892479](https://linux-hardware.org/?probe=4e53892479) | Jun 02, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [d0dbd3d75e](https://linux-hardware.org/?probe=d0dbd3d75e) | Jun 01, 2022 |
| Dell          | Latitude E6400              | [d70c53a9df](https://linux-hardware.org/?probe=d70c53a9df) | May 31, 2022 |
| Dell          | Vostro 5481                 | [5fd6fe3593](https://linux-hardware.org/?probe=5fd6fe3593) | May 31, 2022 |
| Dell          | Latitude 3410               | [b1115f6bbc](https://linux-hardware.org/?probe=b1115f6bbc) | May 28, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1eecb7a012](https://linux-hardware.org/?probe=1eecb7a012) | May 26, 2022 |
| HP            | 635                         | [79aa62cc98](https://linux-hardware.org/?probe=79aa62cc98) | May 25, 2022 |
| HP            | 635                         | [f97ec34a67](https://linux-hardware.org/?probe=f97ec34a67) | May 24, 2022 |
| LG Electro... | C500                        | [e59da09f71](https://linux-hardware.org/?probe=e59da09f71) | May 24, 2022 |
| Lenovo        | G505 20240                  | [6c4aff8f5f](https://linux-hardware.org/?probe=6c4aff8f5f) | May 18, 2022 |
| Dell          | Precision 3520              | [9e2b1878d1](https://linux-hardware.org/?probe=9e2b1878d1) | May 18, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8026841674](https://linux-hardware.org/?probe=8026841674) | May 15, 2022 |
| Dell          | Inspiron 3580               | [33dbac4352](https://linux-hardware.org/?probe=33dbac4352) | May 15, 2022 |
| HP            | OMEN by Laptop              | [f08cef4e3b](https://linux-hardware.org/?probe=f08cef4e3b) | May 13, 2022 |
| HP            | Pavilion dv7                | [709b7bc3e0](https://linux-hardware.org/?probe=709b7bc3e0) | May 09, 2022 |
| Standard      | Unknown                     | [74971ae227](https://linux-hardware.org/?probe=74971ae227) | May 04, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c628f1d84](https://linux-hardware.org/?probe=5c628f1d84) | May 01, 2022 |
| ASUSTek       | G75VX                       | [fb58cab830](https://linux-hardware.org/?probe=fb58cab830) | Apr 30, 2022 |
| Dell          | Latitude 5490               | [9445f416cb](https://linux-hardware.org/?probe=9445f416cb) | Apr 30, 2022 |
| Dell          | Latitude 5520               | [d35917a603](https://linux-hardware.org/?probe=d35917a603) | Apr 29, 2022 |
| Dell          | Latitude 5520               | [9851c7847d](https://linux-hardware.org/?probe=9851c7847d) | Apr 29, 2022 |
| HP            | Pavilion dv7                | [fd2d8cc4f6](https://linux-hardware.org/?probe=fd2d8cc4f6) | Apr 29, 2022 |
| HP            | ProBook 4310s               | [a37901ae30](https://linux-hardware.org/?probe=a37901ae30) | Apr 26, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [b586e45245](https://linux-hardware.org/?probe=b586e45245) | Apr 25, 2022 |
| Acer          | Aspire E1-571               | [009a9c8ce0](https://linux-hardware.org/?probe=009a9c8ce0) | Apr 25, 2022 |
| Acer          | Aspire E1-571               | [4a76d57188](https://linux-hardware.org/?probe=4a76d57188) | Apr 23, 2022 |
| Acer          | Aspire E1-571               | [ee546b53aa](https://linux-hardware.org/?probe=ee546b53aa) | Apr 23, 2022 |
| Proline       | V146A                       | [30cc5fb7c1](https://linux-hardware.org/?probe=30cc5fb7c1) | Apr 22, 2022 |
| Acer          | Swift SF314-42              | [b0dc5471af](https://linux-hardware.org/?probe=b0dc5471af) | Apr 22, 2022 |
| HP            | Laptop 15-bw0xx             | [b251d7f8e6](https://linux-hardware.org/?probe=b251d7f8e6) | Apr 20, 2022 |
| Acer          | Swift SF314-42              | [a8af23856d](https://linux-hardware.org/?probe=a8af23856d) | Apr 20, 2022 |
| Toshiba       | Satellite C850-F31Q         | [e7a2a2ff69](https://linux-hardware.org/?probe=e7a2a2ff69) | Apr 19, 2022 |
| MECER         | YA13Q20-DP_PRO              | [d4cf4e840f](https://linux-hardware.org/?probe=d4cf4e840f) | Apr 18, 2022 |
| Dell          | Inspiron 3521               | [00dc9c3cca](https://linux-hardware.org/?probe=00dc9c3cca) | Apr 18, 2022 |
| Dell          | Latitude 3550               | [03ed6ab7b4](https://linux-hardware.org/?probe=03ed6ab7b4) | Apr 16, 2022 |
| HP            | Presario CQ57               | [110b597e47](https://linux-hardware.org/?probe=110b597e47) | Apr 14, 2022 |
| Dell          | Latitude 3550               | [6947850074](https://linux-hardware.org/?probe=6947850074) | Apr 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [6565c955db](https://linux-hardware.org/?probe=6565c955db) | Apr 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f6c87488b0](https://linux-hardware.org/?probe=f6c87488b0) | Apr 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [48f70d4c5a](https://linux-hardware.org/?probe=48f70d4c5a) | Apr 05, 2022 |
| Dell          | XPS 13 9380                 | [1395229a99](https://linux-hardware.org/?probe=1395229a99) | Apr 04, 2022 |
| Dell          | Latitude 5500               | [798c0e5fa4](https://linux-hardware.org/?probe=798c0e5fa4) | Apr 02, 2022 |
| CONNEX        | L1470                       | [6c1aaac1ee](https://linux-hardware.org/?probe=6c1aaac1ee) | Apr 02, 2022 |
| Lenovo        | G500 20236                  | [9ebbf23e28](https://linux-hardware.org/?probe=9ebbf23e28) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | [95d2d82ede](https://linux-hardware.org/?probe=95d2d82ede) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 41786KG       | [00630dc1b2](https://linux-hardware.org/?probe=00630dc1b2) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 41786KG       | [373ac41605](https://linux-hardware.org/?probe=373ac41605) | Apr 01, 2022 |
| ASUSTek       | UL80VT                      | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| ASUSTek       | GL753VD                     | [af3543aaed](https://linux-hardware.org/?probe=af3543aaed) | Mar 31, 2022 |
| HUAWEI        | BOHB-WAX9                   | [cb353468c2](https://linux-hardware.org/?probe=cb353468c2) | Mar 28, 2022 |
| ASUSTek       | X555UB                      | [e0b9178226](https://linux-hardware.org/?probe=e0b9178226) | Mar 28, 2022 |
| HP            | Pavilion g6                 | [79ebe026b7](https://linux-hardware.org/?probe=79ebe026b7) | Mar 26, 2022 |
| Dell          | Inspiron M5040              | [74a1c6bd00](https://linux-hardware.org/?probe=74a1c6bd00) | Mar 26, 2022 |
| Dell          | Inspiron M5040              | [e352bc299f](https://linux-hardware.org/?probe=e352bc299f) | Mar 26, 2022 |
| Dell          | Latitude E5540              | [c743515039](https://linux-hardware.org/?probe=c743515039) | Mar 25, 2022 |
| Dell          | Latitude E5540              | [0059ee485d](https://linux-hardware.org/?probe=0059ee485d) | Mar 25, 2022 |
| Lenovo        | G500 20236                  | [da34cf7e5c](https://linux-hardware.org/?probe=da34cf7e5c) | Mar 24, 2022 |
| ASUSTek       | Strix GL704GV_GL704GV       | [87c17cc6e1](https://linux-hardware.org/?probe=87c17cc6e1) | Mar 22, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [26a88b6d1f](https://linux-hardware.org/?probe=26a88b6d1f) | Mar 21, 2022 |
| Dell          | Latitude 5420               | [b1a1e20ab3](https://linux-hardware.org/?probe=b1a1e20ab3) | Mar 21, 2022 |
| Lenovo        | ThinkPad 20LB000DZA         | [e4b122e82a](https://linux-hardware.org/?probe=e4b122e82a) | Mar 21, 2022 |
| Lenovo        | ThinkPad 20LB000DZA         | [879224cf79](https://linux-hardware.org/?probe=879224cf79) | Mar 20, 2022 |
| Lenovo        | ThinkPad T520 424067G       | [3e6c1f772d](https://linux-hardware.org/?probe=3e6c1f772d) | Mar 18, 2022 |
| ASUSTek       | K52Jr                       | [b05ec1dbda](https://linux-hardware.org/?probe=b05ec1dbda) | Mar 18, 2022 |
| ASUSTek       | K52Jr                       | [77c6485b0f](https://linux-hardware.org/?probe=77c6485b0f) | Mar 17, 2022 |
| Dell          | Latitude 3550               | [947e147577](https://linux-hardware.org/?probe=947e147577) | Mar 13, 2022 |
| Dell          | Latitude 3550               | [afffe18667](https://linux-hardware.org/?probe=afffe18667) | Mar 13, 2022 |
| Dell          | Inspiron 3543               | [e6d7592af0](https://linux-hardware.org/?probe=e6d7592af0) | Mar 10, 2022 |
| HP            | Laptop 15-dw3xxx            | [65026cfb9e](https://linux-hardware.org/?probe=65026cfb9e) | Mar 09, 2022 |
| HP            | Laptop 15-dw3xxx            | [7557102b76](https://linux-hardware.org/?probe=7557102b76) | Mar 08, 2022 |
| HP            | Laptop 14 14s-dq1008ni      | [8184627283](https://linux-hardware.org/?probe=8184627283) | Mar 07, 2022 |
| Acer          | TMP453-MG                   | [87bcae98bc](https://linux-hardware.org/?probe=87bcae98bc) | Mar 07, 2022 |
| Dell          | Latitude E6430              | [0e9a8aa6cc](https://linux-hardware.org/?probe=0e9a8aa6cc) | Mar 06, 2022 |
| ASUSTek       | X555LAB                     | [80be8910f4](https://linux-hardware.org/?probe=80be8910f4) | Mar 05, 2022 |
| Acer          | Aspire VN7-591G             | [57452c9459](https://linux-hardware.org/?probe=57452c9459) | Mar 03, 2022 |
| Dell          | Inspiron 3543               | [f10ea4bbca](https://linux-hardware.org/?probe=f10ea4bbca) | Mar 02, 2022 |
| Dell          | Precision 3520              | [4b9a52ac5c](https://linux-hardware.org/?probe=4b9a52ac5c) | Feb 24, 2022 |
| ASUSTek       | X555LAB                     | [9e1f07c164](https://linux-hardware.org/?probe=9e1f07c164) | Feb 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | [8e2cd5844e](https://linux-hardware.org/?probe=8e2cd5844e) | Feb 21, 2022 |
| Acer          | TMP453-MG                   | [4b25f5d025](https://linux-hardware.org/?probe=4b25f5d025) | Feb 19, 2022 |
| Dell          | Latitude D630               | [e427bda7a4](https://linux-hardware.org/?probe=e427bda7a4) | Feb 17, 2022 |
| Dell          | Latitude D630               | [bca39271ba](https://linux-hardware.org/?probe=bca39271ba) | Feb 17, 2022 |
| Fujitsu       | LIFEBOOK E751               | [5ca51d5bb5](https://linux-hardware.org/?probe=5ca51d5bb5) | Feb 17, 2022 |
| Dell          | Inspiron 5521               | [e0b1929884](https://linux-hardware.org/?probe=e0b1929884) | Feb 17, 2022 |
| Acer          | Predator G9-793             | [45ec93214f](https://linux-hardware.org/?probe=45ec93214f) | Feb 16, 2022 |
| Sony          | VPCEH38FG                   | [15472f67f5](https://linux-hardware.org/?probe=15472f67f5) | Feb 15, 2022 |
| Lenovo        | G560 20042                  | [5c4a8043b1](https://linux-hardware.org/?probe=5c4a8043b1) | Feb 15, 2022 |
| Dell          | Inspiron 5521               | [aee089a0aa](https://linux-hardware.org/?probe=aee089a0aa) | Feb 14, 2022 |
| ASUSTek       | X101CH                      | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [456d12240c](https://linux-hardware.org/?probe=456d12240c) | Feb 11, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [305921eee8](https://linux-hardware.org/?probe=305921eee8) | Feb 11, 2022 |
| System76      | Oryx Pro                    | [f8437eee6d](https://linux-hardware.org/?probe=f8437eee6d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | [80b214a273](https://linux-hardware.org/?probe=80b214a273) | Feb 10, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [b29422e3cd](https://linux-hardware.org/?probe=b29422e3cd) | Feb 10, 2022 |
| Acer          | TMP453-MG                   | [4e741a6acc](https://linux-hardware.org/?probe=4e741a6acc) | Feb 08, 2022 |
| HP            | EliteBook 2540p             | [006afe98fe](https://linux-hardware.org/?probe=006afe98fe) | Feb 07, 2022 |
| HP            | 635                         | [3f689c9c23](https://linux-hardware.org/?probe=3f689c9c23) | Feb 06, 2022 |
| Dell          | Inspiron 3537               | [66fb2bc907](https://linux-hardware.org/?probe=66fb2bc907) | Feb 06, 2022 |
| HP            | ENVY TS 15                  | [becd915336](https://linux-hardware.org/?probe=becd915336) | Feb 04, 2022 |
| Dell          | Inspiron 15-3567            | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [3df622872c](https://linux-hardware.org/?probe=3df622872c) | Feb 03, 2022 |
| HP            | ProBook 4530s               | [4a1bfbe60f](https://linux-hardware.org/?probe=4a1bfbe60f) | Feb 01, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [940c2e990d](https://linux-hardware.org/?probe=940c2e990d) | Jan 31, 2022 |
| Dell          | Latitude E6220              | [808db5a1c8](https://linux-hardware.org/?probe=808db5a1c8) | Jan 29, 2022 |
| Toshiba       | TECRA A10                   | [bdaff089b2](https://linux-hardware.org/?probe=bdaff089b2) | Jan 28, 2022 |
| Dell          | Latitude D630               | [8a0a5b89dd](https://linux-hardware.org/?probe=8a0a5b89dd) | Jan 27, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3b58afceea](https://linux-hardware.org/?probe=3b58afceea) | Jan 21, 2022 |
| WinSome       | A14C .B005                  | [d685b78944](https://linux-hardware.org/?probe=d685b78944) | Jan 19, 2022 |
| Dell          | Latitude D630               | [6327eec09e](https://linux-hardware.org/?probe=6327eec09e) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [c9dbc0c289](https://linux-hardware.org/?probe=c9dbc0c289) | Jan 14, 2022 |
| HP            | ZBook 15 G3                 | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Dell          | Inspiron 15-3567            | [e36e312cf4](https://linux-hardware.org/?probe=e36e312cf4) | Jan 09, 2022 |
| HP            | Laptop 15-bs1xx             | [d187087325](https://linux-hardware.org/?probe=d187087325) | Jan 09, 2022 |
| HP            | 2000                        | [3c3f60019b](https://linux-hardware.org/?probe=3c3f60019b) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 1294BL5         | [2cd6f5fbb0](https://linux-hardware.org/?probe=2cd6f5fbb0) | Jan 01, 2022 |
| Acer          | TravelMate P255             | [1efdd6ce09](https://linux-hardware.org/?probe=1efdd6ce09) | Dec 26, 2021 |
| Dell          | Latitude 3540               | [7e7f291d68](https://linux-hardware.org/?probe=7e7f291d68) | Dec 24, 2021 |
| Dell          | Latitude E6430              | [c5ac7574f0](https://linux-hardware.org/?probe=c5ac7574f0) | Dec 22, 2021 |
| HP            | ZBook 15u G3                | [6d1e6100ef](https://linux-hardware.org/?probe=6d1e6100ef) | Dec 21, 2021 |
| Acer          | Aspire VN7-572G             | [895dca26b0](https://linux-hardware.org/?probe=895dca26b0) | Dec 21, 2021 |
| Toshiba       | TECRA A10                   | [e5b76a4673](https://linux-hardware.org/?probe=e5b76a4673) | Dec 21, 2021 |
| Lenovo        | ThinkPad T410 25376B8       | [0b0d4dd23f](https://linux-hardware.org/?probe=0b0d4dd23f) | Dec 21, 2021 |
| Lenovo        | ThinkPad E580 20KS001QZA    | [202290bb62](https://linux-hardware.org/?probe=202290bb62) | Dec 20, 2021 |
| Lenovo        | ThinkPad E580 20KS001QZA    | [8a131f560b](https://linux-hardware.org/?probe=8a131f560b) | Dec 20, 2021 |
| HP            | EliteBook 2570p             | [15e7aaf611](https://linux-hardware.org/?probe=15e7aaf611) | Dec 17, 2021 |
| Acer          | TravelMate 6594             | [d706658ff8](https://linux-hardware.org/?probe=d706658ff8) | Dec 15, 2021 |
| Dell          | Inspiron 1525               | [b93d5f0c9c](https://linux-hardware.org/?probe=b93d5f0c9c) | Dec 14, 2021 |
| Dell          | Inspiron 3537               | [f1213e164f](https://linux-hardware.org/?probe=f1213e164f) | Dec 13, 2021 |
| Sony          | VPCP116KG                   | [237c9f66e1](https://linux-hardware.org/?probe=237c9f66e1) | Dec 13, 2021 |
| HP            | EliteBook 2570p             | [1e9841c0eb](https://linux-hardware.org/?probe=1e9841c0eb) | Dec 12, 2021 |
| TCL Commun... | 8085                        | [3d795ceee0](https://linux-hardware.org/?probe=3d795ceee0) | Dec 11, 2021 |
| Dell          | Precision M6800             | [da95c95a07](https://linux-hardware.org/?probe=da95c95a07) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d0e3422cba](https://linux-hardware.org/?probe=d0e3422cba) | Dec 08, 2021 |
| Dell          | Precision M6800             | [3a4d66818c](https://linux-hardware.org/?probe=3a4d66818c) | Dec 07, 2021 |
| HP            | Laptop 15-bs1xx             | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| Dell          | Precision M6800             | [3b4f2f0a57](https://linux-hardware.org/?probe=3b4f2f0a57) | Dec 06, 2021 |
| HP            | 255 G8 Notebook PC          | [a700683a6f](https://linux-hardware.org/?probe=a700683a6f) | Dec 05, 2021 |
| Dell          | Latitude 5590               | [5f9747af05](https://linux-hardware.org/?probe=5f9747af05) | Dec 04, 2021 |
| Acer          | Predator G9-793             | [b9dc27ddac](https://linux-hardware.org/?probe=b9dc27ddac) | Nov 29, 2021 |
| Lenovo        | ThinkPad T580 20L90024ZA    | [6b8493406e](https://linux-hardware.org/?probe=6b8493406e) | Nov 28, 2021 |
| Lenovo        | ThinkPad T580 20L90024ZA    | [4a398efa1b](https://linux-hardware.org/?probe=4a398efa1b) | Nov 28, 2021 |
| HP            | ProBook 4310s               | [9f467df8a8](https://linux-hardware.org/?probe=9f467df8a8) | Nov 27, 2021 |
| HP            | ProBook 4310s               | [6d339b7843](https://linux-hardware.org/?probe=6d339b7843) | Nov 27, 2021 |
| LattePanda    | Delta                       | [5950a5a8ac](https://linux-hardware.org/?probe=5950a5a8ac) | Nov 24, 2021 |
| Dell          | Inspiron N5110              | [ea27790fc4](https://linux-hardware.org/?probe=ea27790fc4) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | [d543e2cd80](https://linux-hardware.org/?probe=d543e2cd80) | Nov 19, 2021 |
| HP            | Notebook                    | [12d501a930](https://linux-hardware.org/?probe=12d501a930) | Nov 17, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [7114246672](https://linux-hardware.org/?probe=7114246672) | Nov 15, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [2cb8a3b9ff](https://linux-hardware.org/?probe=2cb8a3b9ff) | Nov 15, 2021 |
| HP            | Presario CQ56               | [a514e96472](https://linux-hardware.org/?probe=a514e96472) | Nov 15, 2021 |
| MSI           | CR72 7ML                    | [9fdd485636](https://linux-hardware.org/?probe=9fdd485636) | Nov 12, 2021 |
| MSI           | CR72 7ML                    | [1165c3e22f](https://linux-hardware.org/?probe=1165c3e22f) | Nov 12, 2021 |
| Acer          | Aspire V3-571               | [0c1d65f646](https://linux-hardware.org/?probe=0c1d65f646) | Nov 08, 2021 |
| Dell          | Inspiron 5721               | [d9146c3909](https://linux-hardware.org/?probe=d9146c3909) | Nov 07, 2021 |
| Dell          | Studio 1735                 | [6a444456ef](https://linux-hardware.org/?probe=6a444456ef) | Nov 06, 2021 |
| Gigabyte      | P17FV5                      | [379e023c65](https://linux-hardware.org/?probe=379e023c65) | Nov 04, 2021 |
| HP            | ProBook 4310s               | [bb95a3f04d](https://linux-hardware.org/?probe=bb95a3f04d) | Nov 03, 2021 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [293a751aaf](https://linux-hardware.org/?probe=293a751aaf) | Nov 02, 2021 |
| Gigabyte      | P17FV5                      | [7304aa43c3](https://linux-hardware.org/?probe=7304aa43c3) | Nov 02, 2021 |
| Apple         | MacBook4,1                  | [4a72082fdb](https://linux-hardware.org/?probe=4a72082fdb) | Nov 01, 2021 |
| Packard Be... | ENTE11HC                    | [e31fe4eef0](https://linux-hardware.org/?probe=e31fe4eef0) | Nov 01, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | [e18dd8b896](https://linux-hardware.org/?probe=e18dd8b896) | Nov 01, 2021 |
| HP            | ProBook 450 G3              | [1069b24865](https://linux-hardware.org/?probe=1069b24865) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | [9e32a01dc0](https://linux-hardware.org/?probe=9e32a01dc0) | Oct 31, 2021 |
| Dell          | Inspiron 3537               | [b0f6309320](https://linux-hardware.org/?probe=b0f6309320) | Oct 31, 2021 |
| MECER         | Z140C+Home                  | [2fbf6f153b](https://linux-hardware.org/?probe=2fbf6f153b) | Oct 30, 2021 |
| ASUSTek       | X58C                        | [fdd83a3517](https://linux-hardware.org/?probe=fdd83a3517) | Oct 28, 2021 |
| Dell          | Latitude E5570              | [e7a049a026](https://linux-hardware.org/?probe=e7a049a026) | Oct 27, 2021 |
| HP            | EliteBook 8440p             | [f527983cc9](https://linux-hardware.org/?probe=f527983cc9) | Oct 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d43c3cb973](https://linux-hardware.org/?probe=d43c3cb973) | Oct 27, 2021 |
| HP            | Presario CQ56               | [10acff551d](https://linux-hardware.org/?probe=10acff551d) | Oct 25, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [eaf7694813](https://linux-hardware.org/?probe=eaf7694813) | Oct 24, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [44b5186950](https://linux-hardware.org/?probe=44b5186950) | Oct 24, 2021 |
| Dell          | Vostro 15-3568              | [4a961ff6da](https://linux-hardware.org/?probe=4a961ff6da) | Oct 22, 2021 |
| HP            | Laptop 15-dw3xxx            | [9bde1214a9](https://linux-hardware.org/?probe=9bde1214a9) | Oct 22, 2021 |
| Dell          | Latitude E6430              | [b127732e59](https://linux-hardware.org/?probe=b127732e59) | Oct 19, 2021 |
| MSI           | GF65 Thin 10SDR             | [0a048a009d](https://linux-hardware.org/?probe=0a048a009d) | Oct 15, 2021 |
| Lenovo        | E50-80 80J2                 | [c3d31689ec](https://linux-hardware.org/?probe=c3d31689ec) | Oct 11, 2021 |
| Apple         | MacBookPro8,2               | [a3f3c59edc](https://linux-hardware.org/?probe=a3f3c59edc) | Oct 11, 2021 |
| Acer          | Aspire VN7-792G             | [4985d6b90c](https://linux-hardware.org/?probe=4985d6b90c) | Oct 10, 2021 |
| Apple         | MacBookPro9,2               | [d804de918d](https://linux-hardware.org/?probe=d804de918d) | Oct 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c62915e0](https://linux-hardware.org/?probe=26c62915e0) | Oct 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [080e5a9a9f](https://linux-hardware.org/?probe=080e5a9a9f) | Oct 06, 2021 |
| Lenovo        | G50-80 80E5                 | [d9b26b9fec](https://linux-hardware.org/?probe=d9b26b9fec) | Oct 06, 2021 |
| HP            | EliteBook 850 G3            | [cb307dd929](https://linux-hardware.org/?probe=cb307dd929) | Oct 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f85d75b229](https://linux-hardware.org/?probe=f85d75b229) | Oct 05, 2021 |
| HP            | 650                         | [bbe8e793b8](https://linux-hardware.org/?probe=bbe8e793b8) | Oct 05, 2021 |
| HP            | EliteBook 8440p             | [0890806446](https://linux-hardware.org/?probe=0890806446) | Oct 04, 2021 |
| Acer          | Aspire A315-31              | [65388cbcfc](https://linux-hardware.org/?probe=65388cbcfc) | Oct 03, 2021 |
| Acer          | Aspire A315-31              | [97dde270fa](https://linux-hardware.org/?probe=97dde270fa) | Oct 03, 2021 |
| MSI           | Modern 14 B11MO             | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| HP            | Laptop 15-bs0xx             | [e9dd5491e8](https://linux-hardware.org/?probe=e9dd5491e8) | Sep 28, 2021 |
| HP            | Laptop 15-bs0xx             | [44d29122aa](https://linux-hardware.org/?probe=44d29122aa) | Sep 28, 2021 |
| MSI           | Modern 14 B11MO             | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Acer          | Aspire A315-31              | [7af0b1b5dd](https://linux-hardware.org/?probe=7af0b1b5dd) | Sep 27, 2021 |
| Acer          | TravelMate P255             | [c6b7f1d5d9](https://linux-hardware.org/?probe=c6b7f1d5d9) | Sep 26, 2021 |
| Acer          | Aspire VN7-792G             | [b555c8cd95](https://linux-hardware.org/?probe=b555c8cd95) | Sep 25, 2021 |
| Dell          | Latitude E6220              | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | [9d9796386e](https://linux-hardware.org/?probe=9d9796386e) | Sep 21, 2021 |
| Acer          | Aspire V3-571G              | [33781ae35f](https://linux-hardware.org/?probe=33781ae35f) | Sep 21, 2021 |
| Acer          | Extensa 2511                | [b38f9bfa33](https://linux-hardware.org/?probe=b38f9bfa33) | Sep 16, 2021 |
| Dell          | Latitude E7440              | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| Dell          | Precision 7550              | [42890f7542](https://linux-hardware.org/?probe=42890f7542) | Sep 10, 2021 |
| Dell          | Precision 7550              | [a4a1a56132](https://linux-hardware.org/?probe=a4a1a56132) | Sep 09, 2021 |
| Apple         | MacBookPro8,1               | [03445cb511](https://linux-hardware.org/?probe=03445cb511) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [10052076e0](https://linux-hardware.org/?probe=10052076e0) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [8a0df29327](https://linux-hardware.org/?probe=8a0df29327) | Sep 09, 2021 |
| Dell          | XPS 13 9310                 | [1ee958abc3](https://linux-hardware.org/?probe=1ee958abc3) | Sep 08, 2021 |
| HP            | Presario CQ56               | [b5666dc71b](https://linux-hardware.org/?probe=b5666dc71b) | Sep 08, 2021 |
| Packard Be... | EasyNote TK85               | [3e9c16c5a0](https://linux-hardware.org/?probe=3e9c16c5a0) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Dell          | Latitude 7480               | [844ab8df38](https://linux-hardware.org/?probe=844ab8df38) | Sep 06, 2021 |
| HP            | ProBook 450 G5              | [beefff4447](https://linux-hardware.org/?probe=beefff4447) | Sep 06, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| ASUSTek       | G551JM                      | [4309f5e034](https://linux-hardware.org/?probe=4309f5e034) | Sep 04, 2021 |
| ASUSTek       | G551JM                      | [0dad1d056d](https://linux-hardware.org/?probe=0dad1d056d) | Sep 04, 2021 |
| Dell          | Latitude E6430              | [866d479f07](https://linux-hardware.org/?probe=866d479f07) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | Notebook                    | [552535c21e](https://linux-hardware.org/?probe=552535c21e) | Sep 02, 2021 |
| HP            | Notebook                    | [0405b5aa6c](https://linux-hardware.org/?probe=0405b5aa6c) | Sep 02, 2021 |
| HP            | ProBook 450 G5              | [1579919ebb](https://linux-hardware.org/?probe=1579919ebb) | Sep 01, 2021 |
| HP            | EliteBook 8730w             | [93ee7aecde](https://linux-hardware.org/?probe=93ee7aecde) | Aug 31, 2021 |
| HP            | EliteBook 8730w             | [c99d13438f](https://linux-hardware.org/?probe=c99d13438f) | Aug 30, 2021 |
| HP            | EliteBook 850 G6            | [87f2a544c5](https://linux-hardware.org/?probe=87f2a544c5) | Aug 30, 2021 |
| Mustek        | W35xSS_370SS                | [ee70b31c91](https://linux-hardware.org/?probe=ee70b31c91) | Aug 24, 2021 |
| Dell          | Inspiron 7577               | [82ff6985ce](https://linux-hardware.org/?probe=82ff6985ce) | Aug 18, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [d9923e15e0](https://linux-hardware.org/?probe=d9923e15e0) | Aug 18, 2021 |
| Packard Be... | EasyNote TK85               | [4faeb04124](https://linux-hardware.org/?probe=4faeb04124) | Aug 17, 2021 |
| Gigabyte      | Q2006                       | [16503fc58a](https://linux-hardware.org/?probe=16503fc58a) | Aug 16, 2021 |
| Dell          | Latitude E6430              | [31491d6a83](https://linux-hardware.org/?probe=31491d6a83) | Aug 15, 2021 |
| Dell          | Latitude 5580               | [1c57f7bb76](https://linux-hardware.org/?probe=1c57f7bb76) | Aug 15, 2021 |
| HP            | Pavilion dv4                | [bc1ab4b47e](https://linux-hardware.org/?probe=bc1ab4b47e) | Aug 12, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [1f6745d6bb](https://linux-hardware.org/?probe=1f6745d6bb) | Aug 11, 2021 |
| Notebook      | W54_55SU1,SUW               | [a771e9b877](https://linux-hardware.org/?probe=a771e9b877) | Aug 11, 2021 |
| Apple         | MacBookPro7,1               | [da4107ffc3](https://linux-hardware.org/?probe=da4107ffc3) | Aug 10, 2021 |
| HP            | Pavilion dv4                | [34b7ad0d24](https://linux-hardware.org/?probe=34b7ad0d24) | Aug 09, 2021 |
| HP            | ZBook 15u G3                | [e1a51f61f1](https://linux-hardware.org/?probe=e1a51f61f1) | Aug 08, 2021 |
| Lenovo        | ThinkPad T440p 2000CT0      | [574392d159](https://linux-hardware.org/?probe=574392d159) | Aug 07, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| HP            | Laptop 15-dw2xxx            | [80d1826ee1](https://linux-hardware.org/?probe=80d1826ee1) | Aug 02, 2021 |
| Acer          | Aspire ES1-512              | [ac364c0278](https://linux-hardware.org/?probe=ac364c0278) | Aug 01, 2021 |
| Acer          | Aspire ES1-512              | [161731059f](https://linux-hardware.org/?probe=161731059f) | Aug 01, 2021 |
| HP            | Presario CQ56               | [b2f6fbae75](https://linux-hardware.org/?probe=b2f6fbae75) | Jul 29, 2021 |
| Dell          | Inspiron M5040              | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Samsung       | N150P/N210P/N220P           | [f126b121e0](https://linux-hardware.org/?probe=f126b121e0) | Jul 23, 2021 |
| Dell          | XPS 13 9310                 | [bcb7059afa](https://linux-hardware.org/?probe=bcb7059afa) | Jul 19, 2021 |
| Samsung       | RC410/RC510/RC710           | [f9f770c055](https://linux-hardware.org/?probe=f9f770c055) | Jul 17, 2021 |
| Samsung       | RC410/RC510/RC710           | [f2f4a48775](https://linux-hardware.org/?probe=f2f4a48775) | Jul 17, 2021 |
| ASUSTek       | X550CL                      | [3a09584428](https://linux-hardware.org/?probe=3a09584428) | Jul 16, 2021 |
| Dell          | Latitude 5590               | [71d3a5a5d7](https://linux-hardware.org/?probe=71d3a5a5d7) | Jul 16, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [662ed28f07](https://linux-hardware.org/?probe=662ed28f07) | Jul 16, 2021 |
| HP            | 250 G7 Notebook PC          | [846febb191](https://linux-hardware.org/?probe=846febb191) | Jul 14, 2021 |
| Dell          | XPS 13 9310                 | [96ce85594c](https://linux-hardware.org/?probe=96ce85594c) | Jul 14, 2021 |
| Dell          | XPS 13 9310                 | [8e96e56dc3](https://linux-hardware.org/?probe=8e96e56dc3) | Jul 14, 2021 |
| Apple         | MacBookPro9,2               | [f1ca4c9fb2](https://linux-hardware.org/?probe=f1ca4c9fb2) | Jul 12, 2021 |
| Dell          | G7 7790                     | [9c6ab51434](https://linux-hardware.org/?probe=9c6ab51434) | Jul 11, 2021 |
| Acer          | Aspire 5715Z                | [8459bc8e66](https://linux-hardware.org/?probe=8459bc8e66) | Jul 11, 2021 |
| Acer          | Aspire 5715Z                | [77bd0c29ea](https://linux-hardware.org/?probe=77bd0c29ea) | Jul 10, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [94137d1697](https://linux-hardware.org/?probe=94137d1697) | Jul 08, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c27edc6b7e](https://linux-hardware.org/?probe=c27edc6b7e) | Jul 07, 2021 |
| Dell          | Latitude E7440              | [c7aa70ad78](https://linux-hardware.org/?probe=c7aa70ad78) | Jul 07, 2021 |
| HP            | Laptop 15-bs0xx             | [76b81b25d9](https://linux-hardware.org/?probe=76b81b25d9) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d23e2c3398](https://linux-hardware.org/?probe=d23e2c3398) | Jul 01, 2021 |
| Dell          | Inspiron 1564               | [37f6c092f2](https://linux-hardware.org/?probe=37f6c092f2) | Jun 30, 2021 |
| Lenovo        | ThinkPad Edge 057872G       | [8bc64e956d](https://linux-hardware.org/?probe=8bc64e956d) | Jun 25, 2021 |
| Dell          | Inspiron 15-3567            | [b18b2ef77a](https://linux-hardware.org/?probe=b18b2ef77a) | Jun 20, 2021 |
| Acer          | TravelMate 8571             | [5ebead6e64](https://linux-hardware.org/?probe=5ebead6e64) | Jun 20, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [d1c7b5962a](https://linux-hardware.org/?probe=d1c7b5962a) | Jun 19, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [592d026476](https://linux-hardware.org/?probe=592d026476) | Jun 19, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [4154f6bf31](https://linux-hardware.org/?probe=4154f6bf31) | Jun 14, 2021 |
| Dell          | XPS 13 9310                 | [278fd058ed](https://linux-hardware.org/?probe=278fd058ed) | Jun 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| Acer          | Aspire E1-571               | [c0ba4bd856](https://linux-hardware.org/?probe=c0ba4bd856) | Jun 10, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [54fa44f208](https://linux-hardware.org/?probe=54fa44f208) | Jun 09, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5d0ad3d400](https://linux-hardware.org/?probe=5d0ad3d400) | Jun 08, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [d13e2fdb32](https://linux-hardware.org/?probe=d13e2fdb32) | Jun 05, 2021 |
| HP            | ProBook 6560b               | [f9ee7c5367](https://linux-hardware.org/?probe=f9ee7c5367) | Jun 01, 2021 |
| HP            | ProBook 6560b               | [523614fee6](https://linux-hardware.org/?probe=523614fee6) | May 31, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [d507f88a47](https://linux-hardware.org/?probe=d507f88a47) | May 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [fbf4582983](https://linux-hardware.org/?probe=fbf4582983) | May 25, 2021 |
| Packard Be... | EasyNote TS44HR             | [85bcf858c5](https://linux-hardware.org/?probe=85bcf858c5) | May 25, 2021 |
| Apple         | MacBookPro16,1              | [2bddf8b98a](https://linux-hardware.org/?probe=2bddf8b98a) | May 23, 2021 |
| Acer          | TMP453-MG                   | [07291bacfe](https://linux-hardware.org/?probe=07291bacfe) | May 22, 2021 |
| Dell          | Latitude E7440              | [ef82f4635d](https://linux-hardware.org/?probe=ef82f4635d) | May 21, 2021 |
| Dell          | Latitude E7440              | [211f0afc76](https://linux-hardware.org/?probe=211f0afc76) | May 21, 2021 |
| HP            | Compaq Presario C700        | [78d8d0ea55](https://linux-hardware.org/?probe=78d8d0ea55) | May 21, 2021 |
| HP            | Compaq Presario C700        | [46f488f882](https://linux-hardware.org/?probe=46f488f882) | May 21, 2021 |
| HP            | Laptop 15-db0xxx            | [2947241fec](https://linux-hardware.org/?probe=2947241fec) | May 19, 2021 |
| ASUSTek       | X550VX                      | [6b634edf3a](https://linux-hardware.org/?probe=6b634edf3a) | May 19, 2021 |
| ASUSTek       | U80A                        | [1a763007d1](https://linux-hardware.org/?probe=1a763007d1) | May 18, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [c83a466f92](https://linux-hardware.org/?probe=c83a466f92) | May 17, 2021 |
| ASUSTek       | U80A                        | [b3134204a7](https://linux-hardware.org/?probe=b3134204a7) | May 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a035be3ea2](https://linux-hardware.org/?probe=a035be3ea2) | May 16, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [bc6920fa56](https://linux-hardware.org/?probe=bc6920fa56) | May 16, 2021 |
| HP            | ProBook 430 G3              | [08de893a8a](https://linux-hardware.org/?probe=08de893a8a) | May 16, 2021 |
| HP            | ProBook 430 G3              | [20657f6556](https://linux-hardware.org/?probe=20657f6556) | May 16, 2021 |
| Lenovo        | IdeaPad Y560                | [a51abd79ce](https://linux-hardware.org/?probe=a51abd79ce) | May 14, 2021 |
| Dell          | Inspiron 15-3567            | [d42792c1a7](https://linux-hardware.org/?probe=d42792c1a7) | May 14, 2021 |
| Google        | Treeya                      | [5dfc619144](https://linux-hardware.org/?probe=5dfc619144) | May 09, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF0L    | [dc9c7088dd](https://linux-hardware.org/?probe=dc9c7088dd) | May 08, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF0L    | [9cf4893825](https://linux-hardware.org/?probe=9cf4893825) | May 08, 2021 |
| Standard      | Unknown                     | [e9a891227f](https://linux-hardware.org/?probe=e9a891227f) | May 05, 2021 |
| Standard      | Unknown                     | [713ab93267](https://linux-hardware.org/?probe=713ab93267) | May 04, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [5fe6b07786](https://linux-hardware.org/?probe=5fe6b07786) | May 04, 2021 |
| Standard      | Unknown                     | [c3b8d0e386](https://linux-hardware.org/?probe=c3b8d0e386) | May 04, 2021 |
| Toshiba       | Satellite L300              | [2b7b781f75](https://linux-hardware.org/?probe=2b7b781f75) | May 02, 2021 |
| HP            | Compaq CQ58                 | [d1bde8c0f4](https://linux-hardware.org/?probe=d1bde8c0f4) | May 02, 2021 |
| HP            | Compaq CQ58                 | [e6efc8f997](https://linux-hardware.org/?probe=e6efc8f997) | May 02, 2021 |
| HP            | Pavilion dv7                | [98693d2a86](https://linux-hardware.org/?probe=98693d2a86) | May 01, 2021 |
| HP            | Pavilion dv7                | [bd65b55f0a](https://linux-hardware.org/?probe=bd65b55f0a) | May 01, 2021 |
| HP            | ProBook 430 G5              | [18081fbf4f](https://linux-hardware.org/?probe=18081fbf4f) | May 01, 2021 |
| Acer          | Aspire 4315                 | [159c0c0abe](https://linux-hardware.org/?probe=159c0c0abe) | Apr 30, 2021 |
| CONNEX        | L1420                       | [048b79fa6b](https://linux-hardware.org/?probe=048b79fa6b) | Apr 30, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [2a4fa34857](https://linux-hardware.org/?probe=2a4fa34857) | Apr 30, 2021 |
| Dell          | Latitude E6400              | [2ea2bb4954](https://linux-hardware.org/?probe=2ea2bb4954) | Apr 30, 2021 |
| Acer          | Aspire 4315                 | [b05c255870](https://linux-hardware.org/?probe=b05c255870) | Apr 30, 2021 |
| Sony          | VGN-CR343N_B                | [9ac5c739ff](https://linux-hardware.org/?probe=9ac5c739ff) | Apr 29, 2021 |
| HP            | EliteBook 850 G3            | [945ffd0849](https://linux-hardware.org/?probe=945ffd0849) | Apr 28, 2021 |
| Toshiba       | Satellite L300              | [c52eca34ae](https://linux-hardware.org/?probe=c52eca34ae) | Apr 28, 2021 |
| Acer          | Aspire E1-571               | [b9694847a3](https://linux-hardware.org/?probe=b9694847a3) | Apr 26, 2021 |
| PINNACLEMI... | P65_P67RGRERA               | [15933445a2](https://linux-hardware.org/?probe=15933445a2) | Apr 25, 2021 |
| PINNACLEMI... | P65_P67RGRERA               | [b0ccc7e7a7](https://linux-hardware.org/?probe=b0ccc7e7a7) | Apr 25, 2021 |
| HP            | ENVY TS 15                  | [7ee12f0f12](https://linux-hardware.org/?probe=7ee12f0f12) | Apr 24, 2021 |
| HP            | ENVY TS 15                  | [1e93ee4ada](https://linux-hardware.org/?probe=1e93ee4ada) | Apr 23, 2021 |
| HP            | 255 G7 Notebook PC          | [4f1fd4db18](https://linux-hardware.org/?probe=4f1fd4db18) | Apr 22, 2021 |
| CONNEX        | L1420                       | [eb5985fa85](https://linux-hardware.org/?probe=eb5985fa85) | Apr 21, 2021 |
| CONNEX        | L1420                       | [4abc009f2e](https://linux-hardware.org/?probe=4abc009f2e) | Apr 21, 2021 |
| HP            | Pavilion dv6500             | [cb77a79ee8](https://linux-hardware.org/?probe=cb77a79ee8) | Apr 18, 2021 |
| HP            | Laptop 15-bs0xx             | [50ce0817b2](https://linux-hardware.org/?probe=50ce0817b2) | Apr 14, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [2d9245f497](https://linux-hardware.org/?probe=2d9245f497) | Apr 14, 2021 |
| Apple         | MacBookPro16,1              | [3842dcb196](https://linux-hardware.org/?probe=3842dcb196) | Apr 06, 2021 |
| Apple         | MacBookPro16,1              | [8730828ebe](https://linux-hardware.org/?probe=8730828ebe) | Apr 06, 2021 |
| Apple         | MacBookPro9,2               | [6c925ae270](https://linux-hardware.org/?probe=6c925ae270) | Apr 05, 2021 |
| ASUSTek       | X101CH                      | [c1b96ff3fa](https://linux-hardware.org/?probe=c1b96ff3fa) | Apr 04, 2021 |
| HP            | 255 G2                      | [f8dcdf927f](https://linux-hardware.org/?probe=f8dcdf927f) | Apr 04, 2021 |
| Lenovo        | ThinkPad Edge E530 3259T... | [6faba40178](https://linux-hardware.org/?probe=6faba40178) | Mar 30, 2021 |
| Apple         | MacBookPro16,1              | [e5efa4cc6a](https://linux-hardware.org/?probe=e5efa4cc6a) | Mar 29, 2021 |
| HP            | 255 G7 Notebook PC          | [e5a505d84f](https://linux-hardware.org/?probe=e5a505d84f) | Mar 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [90f8531811](https://linux-hardware.org/?probe=90f8531811) | Mar 23, 2021 |
| HP            | ProBook 4520s               | [7577a208f6](https://linux-hardware.org/?probe=7577a208f6) | Mar 22, 2021 |
| HP            | ProBook 4520s               | [d94784890e](https://linux-hardware.org/?probe=d94784890e) | Mar 22, 2021 |
| Apple         | MacBookPro16,1              | [1e05fafe6d](https://linux-hardware.org/?probe=1e05fafe6d) | Mar 21, 2021 |
| HP            | Pavilion g7                 | [ccc49b1cd4](https://linux-hardware.org/?probe=ccc49b1cd4) | Mar 21, 2021 |
| Packard Be... | ENTE11HC                    | [7c208291a7](https://linux-hardware.org/?probe=7c208291a7) | Mar 19, 2021 |
| Apple         | MacBookPro16,1              | [471d1e9f3d](https://linux-hardware.org/?probe=471d1e9f3d) | Mar 18, 2021 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [01aac2b2b5](https://linux-hardware.org/?probe=01aac2b2b5) | Mar 17, 2021 |
| Lenovo        | ThinkPad T410 25374A5       | [ff1dee8695](https://linux-hardware.org/?probe=ff1dee8695) | Mar 15, 2021 |
| Apple         | MacBookPro9,2               | [e5b4868f6d](https://linux-hardware.org/?probe=e5b4868f6d) | Mar 15, 2021 |
| Lenovo        | ThinkPad T420 4236EJ8       | [15fd4b07d7](https://linux-hardware.org/?probe=15fd4b07d7) | Mar 14, 2021 |
| Dell          | Latitude E5420              | [89b141dfe7](https://linux-hardware.org/?probe=89b141dfe7) | Mar 11, 2021 |
| Dell          | Latitude E5420              | [1d9f651a21](https://linux-hardware.org/?probe=1d9f651a21) | Mar 11, 2021 |
| YiFang        | NXM1012BCP                  | [321104f919](https://linux-hardware.org/?probe=321104f919) | Mar 02, 2021 |
| YiFang        | NXM1012BCP                  | [689a0a7984](https://linux-hardware.org/?probe=689a0a7984) | Mar 02, 2021 |
| Packard Be... | ENTE11HC                    | [e96028c294](https://linux-hardware.org/?probe=e96028c294) | Mar 01, 2021 |
| HP            | Notebook                    | [aa01f63a6a](https://linux-hardware.org/?probe=aa01f63a6a) | Feb 28, 2021 |
| HP            | Notebook                    | [36d62b8339](https://linux-hardware.org/?probe=36d62b8339) | Feb 28, 2021 |
| Lenovo        | V510-14IKB 80WR             | [fc338623ab](https://linux-hardware.org/?probe=fc338623ab) | Feb 27, 2021 |
| MSI           | Bravo 15 A4DDR              | [9bec1814a1](https://linux-hardware.org/?probe=9bec1814a1) | Feb 24, 2021 |
| HP            | Pavilion dv7                | [8592f4c025](https://linux-hardware.org/?probe=8592f4c025) | Feb 23, 2021 |
| HP            | EliteBook 850 G3            | [0159818f3c](https://linux-hardware.org/?probe=0159818f3c) | Feb 22, 2021 |
| Acer          | TravelMate P643-M           | [096216b249](https://linux-hardware.org/?probe=096216b249) | Feb 22, 2021 |
| Lenovo        | ThinkPad T410 25376B8       | [de7bf8efee](https://linux-hardware.org/?probe=de7bf8efee) | Feb 20, 2021 |
| HP            | EliteBook 2740p             | [13520f47b2](https://linux-hardware.org/?probe=13520f47b2) | Feb 19, 2021 |
| Acer          | Aspire VN7-591G             | [bc2d4ed095](https://linux-hardware.org/?probe=bc2d4ed095) | Feb 18, 2021 |
| HP            | ProBook 650 G1              | [239d40566e](https://linux-hardware.org/?probe=239d40566e) | Feb 18, 2021 |
| HP            | 255 G2                      | [00f7f8adc6](https://linux-hardware.org/?probe=00f7f8adc6) | Feb 16, 2021 |
| HP            | 255 G2                      | [e7c30a1f46](https://linux-hardware.org/?probe=e7c30a1f46) | Feb 16, 2021 |
| Acer          | TravelMate 6594             | [8d386ea5a9](https://linux-hardware.org/?probe=8d386ea5a9) | Feb 15, 2021 |
| Purism        | Librem 13 v4                | [af4ad81769](https://linux-hardware.org/?probe=af4ad81769) | Feb 13, 2021 |
| HP            | 620                         | [101229cb11](https://linux-hardware.org/?probe=101229cb11) | Feb 09, 2021 |
| HP            | Laptop 15-da0xxx            | [b01bec9bdc](https://linux-hardware.org/?probe=b01bec9bdc) | Feb 09, 2021 |
| HP            | 530                         | [cd817322c7](https://linux-hardware.org/?probe=cd817322c7) | Feb 08, 2021 |
| HP            | ProBook 6460b               | [1591c890ac](https://linux-hardware.org/?probe=1591c890ac) | Feb 07, 2021 |
| Dell          | Latitude 5580               | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| Lenovo        | ThinkPad E580 20KS000EZA    | [086c30adbd](https://linux-hardware.org/?probe=086c30adbd) | Feb 03, 2021 |
| Dell          | Latitude 5590               | [196742e426](https://linux-hardware.org/?probe=196742e426) | Feb 02, 2021 |
| HP            | ProBook 430 G5              | [88a8fe1d45](https://linux-hardware.org/?probe=88a8fe1d45) | Feb 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [2d403e6b99](https://linux-hardware.org/?probe=2d403e6b99) | Jan 31, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [e3fd95697c](https://linux-hardware.org/?probe=e3fd95697c) | Jan 31, 2021 |
| HP            | EliteBook 850 G3            | [492e34ec5b](https://linux-hardware.org/?probe=492e34ec5b) | Jan 22, 2021 |
| HP            | Laptop 15-da0xxx            | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| Mustek        | W650SR                      | [093806c2aa](https://linux-hardware.org/?probe=093806c2aa) | Jan 20, 2021 |
| HP            | 530 Notebook PC(KD092AA#... | [f551313213](https://linux-hardware.org/?probe=f551313213) | Jan 20, 2021 |
| Lenovo        | ThinkPad T410 25374A5       | [5d131c8a55](https://linux-hardware.org/?probe=5d131c8a55) | Jan 19, 2021 |
| Mustek        | W650SR                      | [df9d2e0b6e](https://linux-hardware.org/?probe=df9d2e0b6e) | Jan 19, 2021 |
| ASUSTek       | K52F                        | [8852b30ffb](https://linux-hardware.org/?probe=8852b30ffb) | Jan 15, 2021 |
| ASUSTek       | K52F                        | [f939607deb](https://linux-hardware.org/?probe=f939607deb) | Jan 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5a3e5bd489](https://linux-hardware.org/?probe=5a3e5bd489) | Jan 12, 2021 |
| Mustek        | W650SR                      | [959dcafda5](https://linux-hardware.org/?probe=959dcafda5) | Jan 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b6b5391249](https://linux-hardware.org/?probe=b6b5391249) | Jan 12, 2021 |
| Dell          | Precision 7750              | [9cae2308d3](https://linux-hardware.org/?probe=9cae2308d3) | Jan 12, 2021 |
| Dell          | Precision 7750              | [4480bd05df](https://linux-hardware.org/?probe=4480bd05df) | Jan 12, 2021 |
| Lenovo        | ThinkPad W530 24472L5       | [3b79402144](https://linux-hardware.org/?probe=3b79402144) | Jan 12, 2021 |
| Acer          | TravelMate 6594             | [134cac6028](https://linux-hardware.org/?probe=134cac6028) | Jan 11, 2021 |
| Acer          | TravelMate 6594             | [d015dcdb11](https://linux-hardware.org/?probe=d015dcdb11) | Jan 11, 2021 |
| Dell          | Inspiron 3537               | [1912a7c4ea](https://linux-hardware.org/?probe=1912a7c4ea) | Jan 07, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [6a1e524903](https://linux-hardware.org/?probe=6a1e524903) | Jan 06, 2021 |
| Dell          | Inspiron 3537               | [02eda08f03](https://linux-hardware.org/?probe=02eda08f03) | Jan 06, 2021 |
| Dell          | Inspiron 3580               | [ecabe519f7](https://linux-hardware.org/?probe=ecabe519f7) | Jan 06, 2021 |
| HP            | 530 Notebook PC(KD092AA#... | [5c3ff90c04](https://linux-hardware.org/?probe=5c3ff90c04) | Jan 04, 2021 |
| Sony          | VPCCB17FG                   | [9e2a14cddd](https://linux-hardware.org/?probe=9e2a14cddd) | Jan 02, 2021 |
| Dell          | XPS 13 9300                 | [0d6592676a](https://linux-hardware.org/?probe=0d6592676a) | Jan 02, 2021 |
| Dell          | System XPS L502X            | [acfba5cf21](https://linux-hardware.org/?probe=acfba5cf21) | Jan 01, 2021 |
| Dell          | G3 3579                     | [3f9b834132](https://linux-hardware.org/?probe=3f9b834132) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [32c6bfaacf](https://linux-hardware.org/?probe=32c6bfaacf) | Dec 29, 2020 |
| Dell          | Inspiron 3580               | [1fb2f225a2](https://linux-hardware.org/?probe=1fb2f225a2) | Dec 26, 2020 |
| HP            | 15                          | [e9ea153217](https://linux-hardware.org/?probe=e9ea153217) | Dec 23, 2020 |
| HP            | 15                          | [df1bd71a5b](https://linux-hardware.org/?probe=df1bd71a5b) | Dec 23, 2020 |
| Dell          | Inspiron N5110              | [79dc0bb6e5](https://linux-hardware.org/?probe=79dc0bb6e5) | Dec 21, 2020 |
| HP            | 530 Notebook PC(KD092AA#... | [6b5a6b87d0](https://linux-hardware.org/?probe=6b5a6b87d0) | Dec 20, 2020 |
| Acer          | Aspire A315-54K             | [4a57537b9c](https://linux-hardware.org/?probe=4a57537b9c) | Dec 17, 2020 |
| Lenovo        | ThinkPad T560 20FJS3CR00    | [f027e7d759](https://linux-hardware.org/?probe=f027e7d759) | Dec 15, 2020 |
| HP            | ProBook 450 G2              | [f874634860](https://linux-hardware.org/?probe=f874634860) | Dec 15, 2020 |
| HP            | 250 G6 Notebook PC          | [724522a6d1](https://linux-hardware.org/?probe=724522a6d1) | Dec 14, 2020 |
| Apple         | MacBookPro7,1               | [fe895f311c](https://linux-hardware.org/?probe=fe895f311c) | Dec 13, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [4f4c7dcb90](https://linux-hardware.org/?probe=4f4c7dcb90) | Dec 12, 2020 |
| Unknown       | Unknown                     | [ef997b1269](https://linux-hardware.org/?probe=ef997b1269) | Dec 12, 2020 |
| Unknown       | Unknown                     | [a49b1a585c](https://linux-hardware.org/?probe=a49b1a585c) | Dec 12, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [c4d727c0fe](https://linux-hardware.org/?probe=c4d727c0fe) | Dec 12, 2020 |
| Lenovo        | ThinkPad T560 20FJS3CR00    | [a2a24647bc](https://linux-hardware.org/?probe=a2a24647bc) | Dec 10, 2020 |
| HP            | 530 Notebook PC(KD092AA#... | [795405460c](https://linux-hardware.org/?probe=795405460c) | Dec 10, 2020 |
| Acer          | TravelMate 6594             | [ae03da366b](https://linux-hardware.org/?probe=ae03da366b) | Dec 02, 2020 |
| Toshiba       | Satellite L655              | [084b1edabe](https://linux-hardware.org/?probe=084b1edabe) | Nov 28, 2020 |
| Razer         | Blade                       | [e18d620129](https://linux-hardware.org/?probe=e18d620129) | Nov 26, 2020 |
| MSI           | GF65 Thin 10SDR             | [d7689a3ea9](https://linux-hardware.org/?probe=d7689a3ea9) | Nov 26, 2020 |
| Lenovo        | ThinkPad W530 24475FG       | [1cb4ed8103](https://linux-hardware.org/?probe=1cb4ed8103) | Nov 26, 2020 |
| Lenovo        | ThinkPad W530 24475FG       | [4661924b42](https://linux-hardware.org/?probe=4661924b42) | Nov 25, 2020 |
| MSI           | GF65 Thin 10SDR             | [20666074cc](https://linux-hardware.org/?probe=20666074cc) | Nov 25, 2020 |
| MSI           | GF65 Thin 10SDR             | [aa40dc132e](https://linux-hardware.org/?probe=aa40dc132e) | Nov 24, 2020 |
| MSI           | GF65 Thin 10SDR             | [e330dc888c](https://linux-hardware.org/?probe=e330dc888c) | Nov 24, 2020 |
| Dell          | System XPS L502X            | [cb6a73b345](https://linux-hardware.org/?probe=cb6a73b345) | Nov 22, 2020 |
| Lenovo        | ThinkPad W530 24472L5       | [eb70db095c](https://linux-hardware.org/?probe=eb70db095c) | Nov 21, 2020 |
| Toshiba       | Satellite L300              | [14ba3c1b1e](https://linux-hardware.org/?probe=14ba3c1b1e) | Nov 21, 2020 |
| MSI           | GF65 Thin 10SDR             | [7459ea254f](https://linux-hardware.org/?probe=7459ea254f) | Nov 20, 2020 |
| MSI           | GF65 Thin 10SDR             | [ccd5e2e9b7](https://linux-hardware.org/?probe=ccd5e2e9b7) | Nov 20, 2020 |
| Acer          | TMP453-MG                   | [78f12b69b1](https://linux-hardware.org/?probe=78f12b69b1) | Nov 20, 2020 |
| Acer          | Aspire A515-51              | [9d17b487c9](https://linux-hardware.org/?probe=9d17b487c9) | Nov 19, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [8d5d3ceb39](https://linux-hardware.org/?probe=8d5d3ceb39) | Nov 19, 2020 |
| HP            | ProBook 4740s               | [52eecd895e](https://linux-hardware.org/?probe=52eecd895e) | Nov 19, 2020 |
| HP            | Laptop 15-db0xxx            | [2bc5d144a7](https://linux-hardware.org/?probe=2bc5d144a7) | Nov 15, 2020 |
| Lenovo        | ThinkPad T410 25374A5       | [5872fcfdcc](https://linux-hardware.org/?probe=5872fcfdcc) | Nov 10, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | [c8b05a074e](https://linux-hardware.org/?probe=c8b05a074e) | Nov 08, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | [2f2b8ffce4](https://linux-hardware.org/?probe=2f2b8ffce4) | Nov 07, 2020 |
| Acer          | TMP453-MG                   | [1d55620e4d](https://linux-hardware.org/?probe=1d55620e4d) | Nov 05, 2020 |
| HP            | ProBook 430 G5              | [47fa01cd3c](https://linux-hardware.org/?probe=47fa01cd3c) | Nov 05, 2020 |
| HP            | 530                         | [1b2646e26e](https://linux-hardware.org/?probe=1b2646e26e) | Nov 04, 2020 |
| Packard Be... | EasyNote ENTG81BA           | [554b898a54](https://linux-hardware.org/?probe=554b898a54) | Nov 04, 2020 |
| Dell          | Precision M2800             | [bffd355a04](https://linux-hardware.org/?probe=bffd355a04) | Nov 03, 2020 |
| Dell          | Precision 7740              | [77dfb73496](https://linux-hardware.org/?probe=77dfb73496) | Nov 02, 2020 |
| HP            | Notebook                    | [e7ef3fa0c5](https://linux-hardware.org/?probe=e7ef3fa0c5) | Oct 29, 2020 |
| Dell          | Inspiron 1564               | [181df38a9d](https://linux-hardware.org/?probe=181df38a9d) | Oct 28, 2020 |
| Dell          | G3 3590                     | [26424b5cc7](https://linux-hardware.org/?probe=26424b5cc7) | Oct 22, 2020 |
| HP            | Compaq nc6320 (RH367ET#A... | [558f06c315](https://linux-hardware.org/?probe=558f06c315) | Oct 22, 2020 |
| Dell          | Precision 7740              | [703a5701df](https://linux-hardware.org/?probe=703a5701df) | Oct 19, 2020 |
| Dell          | G3 3590                     | [4506998df7](https://linux-hardware.org/?probe=4506998df7) | Oct 19, 2020 |
| Dell          | G3 3590                     | [e373695d27](https://linux-hardware.org/?probe=e373695d27) | Oct 19, 2020 |
| HP            | Pavilion g7                 | [09258aec8a](https://linux-hardware.org/?probe=09258aec8a) | Oct 18, 2020 |
| HP            | Laptop 15-db0xxx            | [a4ff2b6824](https://linux-hardware.org/?probe=a4ff2b6824) | Oct 14, 2020 |
| HP            | Laptop 15-db0xxx            | [79804afa01](https://linux-hardware.org/?probe=79804afa01) | Oct 14, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | [365a05297a](https://linux-hardware.org/?probe=365a05297a) | Oct 10, 2020 |
| HP            | Pavilion g7                 | [1efaadf26c](https://linux-hardware.org/?probe=1efaadf26c) | Oct 10, 2020 |
| ASUSTek       | X540LA                      | [258c7e5c59](https://linux-hardware.org/?probe=258c7e5c59) | Oct 06, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c37e90e5ba](https://linux-hardware.org/?probe=c37e90e5ba) | Oct 02, 2020 |
| HP            | Pavilion g7                 | [9230541054](https://linux-hardware.org/?probe=9230541054) | Sep 27, 2020 |
| Dell          | XPS 15 9570                 | [356de884b8](https://linux-hardware.org/?probe=356de884b8) | Sep 26, 2020 |
| Dell          | XPS 15 9570                 | [4d17cc2498](https://linux-hardware.org/?probe=4d17cc2498) | Sep 26, 2020 |
| ASUSTek       | X541UAK                     | [3c6317b054](https://linux-hardware.org/?probe=3c6317b054) | Sep 25, 2020 |
| Lenovo        | ThinkPad E490 20N8000GZA    | [a2cab9674f](https://linux-hardware.org/?probe=a2cab9674f) | Sep 21, 2020 |
| Acer          | TravelMate 5730             | [263c747308](https://linux-hardware.org/?probe=263c747308) | Sep 20, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [158b2e89af](https://linux-hardware.org/?probe=158b2e89af) | Sep 20, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [38c0fd0b5e](https://linux-hardware.org/?probe=38c0fd0b5e) | Sep 20, 2020 |
| HP            | 650                         | [530347b45b](https://linux-hardware.org/?probe=530347b45b) | Sep 15, 2020 |
| HP            | 650                         | [fa6359ea31](https://linux-hardware.org/?probe=fa6359ea31) | Sep 15, 2020 |
| Packard Be... | DOA150                      | [e8e13f5c29](https://linux-hardware.org/?probe=e8e13f5c29) | Sep 15, 2020 |
| HP            | Laptop 15-bs1xx             | [54f64b9271](https://linux-hardware.org/?probe=54f64b9271) | Sep 14, 2020 |
| HP            | Laptop 15-bs1xx             | [a2c238595d](https://linux-hardware.org/?probe=a2c238595d) | Sep 14, 2020 |
| Lenovo        | ThinkPad T560 20FJS2QH00    | [b8a2c9ffb6](https://linux-hardware.org/?probe=b8a2c9ffb6) | Sep 12, 2020 |
| Acer          | Aspire A315-33              | [ba7f97b25f](https://linux-hardware.org/?probe=ba7f97b25f) | Sep 11, 2020 |
| Lenovo        | Z50-75 80EC                 | [4b6d8031d3](https://linux-hardware.org/?probe=4b6d8031d3) | Sep 09, 2020 |
| Dell          | Inspiron 3558               | [c532a136d9](https://linux-hardware.org/?probe=c532a136d9) | Sep 08, 2020 |
| Fujitsu       | LIFEBOOK AH532              | [813ee792ff](https://linux-hardware.org/?probe=813ee792ff) | Sep 07, 2020 |
| Dell          | G5 5587                     | [9e3a5fe32f](https://linux-hardware.org/?probe=9e3a5fe32f) | Sep 07, 2020 |
| Lenovo        | ThinkPad T560 20FJS2QH00    | [eb58725fb3](https://linux-hardware.org/?probe=eb58725fb3) | Sep 07, 2020 |
| HP            | Laptop 15-rb0xx             | [2ef696d3c4](https://linux-hardware.org/?probe=2ef696d3c4) | Sep 04, 2020 |
| Alienware     | 15 R3                       | [99d1babb0c](https://linux-hardware.org/?probe=99d1babb0c) | Sep 04, 2020 |
| Dell          | Inspiron 15-3567            | [d7fbcdbfbe](https://linux-hardware.org/?probe=d7fbcdbfbe) | Sep 03, 2020 |
| Lenovo        | ThinkPad E460 20ET000BZA    | [9594512da6](https://linux-hardware.org/?probe=9594512da6) | Aug 31, 2020 |
| HP            | ProBook 430 G5              | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Acer          | Aspire 7750G                | [91041cbcfb](https://linux-hardware.org/?probe=91041cbcfb) | Aug 28, 2020 |
| Acer          | Aspire 7750G                | [072119fece](https://linux-hardware.org/?probe=072119fece) | Aug 28, 2020 |
| Dell          | Latitude E5510              | [b5daf24624](https://linux-hardware.org/?probe=b5daf24624) | Aug 26, 2020 |
| Toshiba       | Satellite L300              | [d910a7c7f6](https://linux-hardware.org/?probe=d910a7c7f6) | Aug 25, 2020 |
| Gigabyte      | Q1532P                      | [7a2e9494a2](https://linux-hardware.org/?probe=7a2e9494a2) | Aug 24, 2020 |
| Dell          | XPS 15 7590                 | [1ecbfe31cc](https://linux-hardware.org/?probe=1ecbfe31cc) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [d475ab6b1f](https://linux-hardware.org/?probe=d475ab6b1f) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [25f98c006e](https://linux-hardware.org/?probe=25f98c006e) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [c2d9b7b8f9](https://linux-hardware.org/?probe=c2d9b7b8f9) | Aug 23, 2020 |
| Toshiba       | Satellite L300              | [5f5af9383f](https://linux-hardware.org/?probe=5f5af9383f) | Aug 18, 2020 |
| Dell          | Inspiron 15-3567            | [d074e75c19](https://linux-hardware.org/?probe=d074e75c19) | Aug 15, 2020 |
| Dell          | Latitude E5510              | [48dc8dde92](https://linux-hardware.org/?probe=48dc8dde92) | Aug 15, 2020 |
| Lenovo        | ThinkPad T520 42405GG       | [b56a1ac043](https://linux-hardware.org/?probe=b56a1ac043) | Aug 13, 2020 |
| Acer          | TravelMate 5730             | [348008255f](https://linux-hardware.org/?probe=348008255f) | Aug 12, 2020 |
| ASUSTek       | X540SA                      | [ae4f0e030f](https://linux-hardware.org/?probe=ae4f0e030f) | Aug 11, 2020 |
| Dell          | System XPS L502X            | [9621996153](https://linux-hardware.org/?probe=9621996153) | Aug 11, 2020 |
| Acer          | Aspire A315-33              | [2e6e1fee7d](https://linux-hardware.org/?probe=2e6e1fee7d) | Aug 11, 2020 |
| HP            | Laptop 15-rb0xx             | [c336e9c30d](https://linux-hardware.org/?probe=c336e9c30d) | Aug 10, 2020 |
| HP            | EliteBook 8530p             | [de121e336e](https://linux-hardware.org/?probe=de121e336e) | Aug 10, 2020 |
| HP            | EliteBook 8530p             | [87b8fdd5d0](https://linux-hardware.org/?probe=87b8fdd5d0) | Aug 10, 2020 |
| ASUSTek       | X541UAK                     | [81676db3c8](https://linux-hardware.org/?probe=81676db3c8) | Aug 10, 2020 |
| HP            | EliteBook 2560p             | [d3dfb613fb](https://linux-hardware.org/?probe=d3dfb613fb) | Aug 07, 2020 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [cc43288bbf](https://linux-hardware.org/?probe=cc43288bbf) | Aug 04, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2970... | [9fe0854fe1](https://linux-hardware.org/?probe=9fe0854fe1) | Jul 27, 2020 |
| HP            | Pavilion 15                 | [a0ce170236](https://linux-hardware.org/?probe=a0ce170236) | Jul 27, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7efc08bc3f](https://linux-hardware.org/?probe=7efc08bc3f) | Jul 27, 2020 |
| Mustek        | W150HNM/W170HN              | [cb2e9bf05e](https://linux-hardware.org/?probe=cb2e9bf05e) | Jul 26, 2020 |
| HP            | ENVY 17                     | [fe4340900e](https://linux-hardware.org/?probe=fe4340900e) | Jul 24, 2020 |
| Dell          | XPS 15 7590                 | [cf0e22a73b](https://linux-hardware.org/?probe=cf0e22a73b) | Jul 23, 2020 |
| HP            | Compaq 6730b (FU498ES#AC... | [eafb860249](https://linux-hardware.org/?probe=eafb860249) | Jul 18, 2020 |
| HP            | Compaq 6730b (FU498ES#AC... | [6589c077c1](https://linux-hardware.org/?probe=6589c077c1) | Jul 18, 2020 |
| Acer          | Aspire ES1-531              | [12daf0c779](https://linux-hardware.org/?probe=12daf0c779) | Jul 15, 2020 |
| Acer          | Aspire ES1-531              | [c715d782a7](https://linux-hardware.org/?probe=c715d782a7) | Jul 15, 2020 |
| Dell          | Inspiron 1564               | [6f2fd1c5f5](https://linux-hardware.org/?probe=6f2fd1c5f5) | Jul 13, 2020 |
| HP            | Laptop 15-da1xxx            | [2bafa31949](https://linux-hardware.org/?probe=2bafa31949) | Jul 11, 2020 |
| HP            | EliteBook 8460p             | [690be1abd1](https://linux-hardware.org/?probe=690be1abd1) | Jul 07, 2020 |
| HP            | EliteBook 8460p             | [0a23e6ddb9](https://linux-hardware.org/?probe=0a23e6ddb9) | Jul 07, 2020 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [9d9e59f8a7](https://linux-hardware.org/?probe=9d9e59f8a7) | Jul 06, 2020 |
| HP            | Laptop 15-rb0xx             | [5453a2ab1e](https://linux-hardware.org/?probe=5453a2ab1e) | Jul 06, 2020 |
| PINNACLEMI... | W54_55_94_95_97AU,AUQ       | [10e802c9d2](https://linux-hardware.org/?probe=10e802c9d2) | Jul 05, 2020 |
| PINNACLEMI... | W54_55_94_95_97AU,AUQ       | [d2a15517ae](https://linux-hardware.org/?probe=d2a15517ae) | Jul 05, 2020 |
| Acer          | Aspire ES1-531              | [fcfe22c7f7](https://linux-hardware.org/?probe=fcfe22c7f7) | Jul 04, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [811c58d180](https://linux-hardware.org/?probe=811c58d180) | Jul 03, 2020 |
| HP            | ProBook 450 G3              | [cf66568c1a](https://linux-hardware.org/?probe=cf66568c1a) | Jul 01, 2020 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [f86d13d08b](https://linux-hardware.org/?probe=f86d13d08b) | Jun 30, 2020 |
| ASUSTek       | GL552VW                     | [680865d570](https://linux-hardware.org/?probe=680865d570) | Jun 28, 2020 |
| ASUSTek       | GL552VW                     | [4bd631ea1e](https://linux-hardware.org/?probe=4bd631ea1e) | Jun 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2970... | [7998eb3c9d](https://linux-hardware.org/?probe=7998eb3c9d) | Jun 26, 2020 |
| Acer          | Aspire A315-33              | [6f89973e83](https://linux-hardware.org/?probe=6f89973e83) | Jun 26, 2020 |
| Acer          | Aspire E1-571               | [846c2cfcc2](https://linux-hardware.org/?probe=846c2cfcc2) | Jun 25, 2020 |
| Dell          | Inspiron 15-3567            | [ba23c3d53b](https://linux-hardware.org/?probe=ba23c3d53b) | Jun 21, 2020 |
| HP            | ProBook 4530s               | [9a3677462f](https://linux-hardware.org/?probe=9a3677462f) | Jun 15, 2020 |
| Dell          | Vostro 5581                 | [9cca353931](https://linux-hardware.org/?probe=9cca353931) | Jun 14, 2020 |
| HP            | ProBook 450 G3              | [7c8e952de0](https://linux-hardware.org/?probe=7c8e952de0) | Jun 12, 2020 |
| Dell          | Inspiron 15-3567            | [723f40770e](https://linux-hardware.org/?probe=723f40770e) | Jun 12, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [210e0bbd91](https://linux-hardware.org/?probe=210e0bbd91) | Jun 10, 2020 |
| Dell          | Latitude E5470              | [8e2c9531ee](https://linux-hardware.org/?probe=8e2c9531ee) | Jun 08, 2020 |
| HP            | Pavilion dv6                | [75bb7f58f7](https://linux-hardware.org/?probe=75bb7f58f7) | Jun 07, 2020 |
| Dell          | Inspiron 15-3567            | [042de23941](https://linux-hardware.org/?probe=042de23941) | Jun 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X532... | [e132acbd84](https://linux-hardware.org/?probe=e132acbd84) | Jun 05, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [231469ed54](https://linux-hardware.org/?probe=231469ed54) | Jun 04, 2020 |
| ASUSTek       | F3E                         | [017dbb9885](https://linux-hardware.org/?probe=017dbb9885) | Jun 02, 2020 |
| ASUSTek       | F3E                         | [94392b7fbe](https://linux-hardware.org/?probe=94392b7fbe) | Jun 02, 2020 |
| HP            | Unknown                     | [c9eaaa02f0](https://linux-hardware.org/?probe=c9eaaa02f0) | Jun 02, 2020 |
| Dell          | Inspiron 15-3567            | [8517d04de8](https://linux-hardware.org/?probe=8517d04de8) | Jun 02, 2020 |
| Dell          | Inspiron 15-3567            | [2542efac1a](https://linux-hardware.org/?probe=2542efac1a) | Jun 02, 2020 |
| Apple         | MacBookPro14,1              | [0ecb29970a](https://linux-hardware.org/?probe=0ecb29970a) | May 31, 2020 |
| Apple         | MacBookPro14,1              | [28fa9f025a](https://linux-hardware.org/?probe=28fa9f025a) | May 31, 2020 |
| HP            | 635                         | [4c1e9766eb](https://linux-hardware.org/?probe=4c1e9766eb) | May 30, 2020 |
| Acer          | Swift SF714-52T             | [225373558d](https://linux-hardware.org/?probe=225373558d) | May 28, 2020 |
| Acer          | Swift SF714-52T             | [45777f6233](https://linux-hardware.org/?probe=45777f6233) | May 28, 2020 |
| HP            | Compaq 615                  | [b5764f8ab1](https://linux-hardware.org/?probe=b5764f8ab1) | May 28, 2020 |
| Acer          | TravelMate 5730             | [cbd537f7c5](https://linux-hardware.org/?probe=cbd537f7c5) | May 26, 2020 |
| ASUSTek       | X541NA                      | [2b1ef7d7ca](https://linux-hardware.org/?probe=2b1ef7d7ca) | May 26, 2020 |
| MSI           | GE62 2QF                    | [321d1bd5a9](https://linux-hardware.org/?probe=321d1bd5a9) | May 24, 2020 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [d691e2d0c5](https://linux-hardware.org/?probe=d691e2d0c5) | May 24, 2020 |
| HP            | ProBook 4520s               | [a82abd4f97](https://linux-hardware.org/?probe=a82abd4f97) | May 24, 2020 |
| HP            | ProBook 4520s               | [ad874f6c98](https://linux-hardware.org/?probe=ad874f6c98) | May 24, 2020 |
| Dell          | G3 3579                     | [ec47395462](https://linux-hardware.org/?probe=ec47395462) | May 23, 2020 |
| Dell          | G3 3579                     | [c1b7c40099](https://linux-hardware.org/?probe=c1b7c40099) | May 23, 2020 |
| HP            | ProBook 430 G5              | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP            | ProBook 430 G5              | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| ASUSTek       | X541NA                      | [8664f78348](https://linux-hardware.org/?probe=8664f78348) | May 18, 2020 |
| Dell          | Inspiron 1564               | [f8beaacc00](https://linux-hardware.org/?probe=f8beaacc00) | May 18, 2020 |
| HP            | Pavilion dv6                | [6e5db16a3d](https://linux-hardware.org/?probe=6e5db16a3d) | May 17, 2020 |
| HP            | Laptop 15-da0xxx            | [f8d707f73e](https://linux-hardware.org/?probe=f8d707f73e) | May 16, 2020 |
| Dell          | Inspiron 1564               | [64684a4b90](https://linux-hardware.org/?probe=64684a4b90) | May 16, 2020 |
| Acer          | Aspire A315-54              | [64bc1caac9](https://linux-hardware.org/?probe=64bc1caac9) | May 14, 2020 |
| Acer          | Aspire A315-54              | [22538b9f97](https://linux-hardware.org/?probe=22538b9f97) | May 13, 2020 |
| HP            | 250 G4 Notebook PC          | [2406267563](https://linux-hardware.org/?probe=2406267563) | May 12, 2020 |
| HP            | 250 G4 Notebook PC          | [7e8fdf4b86](https://linux-hardware.org/?probe=7e8fdf4b86) | May 11, 2020 |
| ASUSTek       | X541NA                      | [0f64cb0bb2](https://linux-hardware.org/?probe=0f64cb0bb2) | May 11, 2020 |
| ASUSTek       | X541NA                      | [8f1e4e6ac0](https://linux-hardware.org/?probe=8f1e4e6ac0) | May 11, 2020 |
| ASUSTek       | Strix GL504GM_GL504GM       | [877b1afb6f](https://linux-hardware.org/?probe=877b1afb6f) | May 10, 2020 |
| Acer          | Aspire E1-571               | [81745dc737](https://linux-hardware.org/?probe=81745dc737) | May 07, 2020 |
| Dell          | Vostro 3550                 | [aeb508b54b](https://linux-hardware.org/?probe=aeb508b54b) | May 07, 2020 |
| Dell          | Inspiron 3521               | [621dd13569](https://linux-hardware.org/?probe=621dd13569) | May 07, 2020 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [927efeb75f](https://linux-hardware.org/?probe=927efeb75f) | May 06, 2020 |
| Dell          | G3 3779                     | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Acer          | Aspire A315-54K             | [45fad98669](https://linux-hardware.org/?probe=45fad98669) | May 04, 2020 |
| Gigabyte      | P65                         | [8fbc34fb32](https://linux-hardware.org/?probe=8fbc34fb32) | May 04, 2020 |
| Dell          | Inspiron 1545               | [ac74330be2](https://linux-hardware.org/?probe=ac74330be2) | May 03, 2020 |
| HP            | Unknown                     | [e161ed1b13](https://linux-hardware.org/?probe=e161ed1b13) | May 01, 2020 |
| Acer          | Aspire A315-54              | [9007ac437f](https://linux-hardware.org/?probe=9007ac437f) | Apr 30, 2020 |
| Acer          | Aspire A315-54              | [e56e6a57f6](https://linux-hardware.org/?probe=e56e6a57f6) | Apr 30, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | [29954f450a](https://linux-hardware.org/?probe=29954f450a) | Apr 28, 2020 |
| Dell          | Inspiron 1545               | [fed3b2695a](https://linux-hardware.org/?probe=fed3b2695a) | Apr 27, 2020 |
| Dell          | Inspiron N5010              | [a70e19ee19](https://linux-hardware.org/?probe=a70e19ee19) | Apr 27, 2020 |
| HP            | Laptop 15-da0xxx            | [7eee20d7e5](https://linux-hardware.org/?probe=7eee20d7e5) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | [a1b6c234ed](https://linux-hardware.org/?probe=a1b6c234ed) | Apr 25, 2020 |
| Dell          | Latitude E6510              | [f15cdfeb6c](https://linux-hardware.org/?probe=f15cdfeb6c) | Apr 15, 2020 |
| HP            | ProBook 430 G5              | [a1f59e373b](https://linux-hardware.org/?probe=a1f59e373b) | Apr 10, 2020 |
| Dell          | Vostro 5471                 | [031fe22aec](https://linux-hardware.org/?probe=031fe22aec) | Apr 08, 2020 |
| eMachines     | E725                        | [b4f225dd7c](https://linux-hardware.org/?probe=b4f225dd7c) | Apr 04, 2020 |
| HP            | Compaq nc6320 (EY396EA#A... | [737a6eaa7d](https://linux-hardware.org/?probe=737a6eaa7d) | Apr 02, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [65f353ed24](https://linux-hardware.org/?probe=65f353ed24) | Apr 01, 2020 |
| HP            | ProBook 4320s               | [b78e8287b3](https://linux-hardware.org/?probe=b78e8287b3) | Mar 27, 2020 |
| HP            | ProBook 450 G6              | [9e4d8ea0ce](https://linux-hardware.org/?probe=9e4d8ea0ce) | Mar 27, 2020 |
| Acer          | Aspire E1-571               | [628116088e](https://linux-hardware.org/?probe=628116088e) | Mar 26, 2020 |
| HP            | Laptop 15-bs1xx             | [b3f0c20207](https://linux-hardware.org/?probe=b3f0c20207) | Mar 23, 2020 |
| Dell          | Inspiron 3593               | [683e249eac](https://linux-hardware.org/?probe=683e249eac) | Mar 11, 2020 |
| Acer          | Aspire E1-571               | [2152fb6549](https://linux-hardware.org/?probe=2152fb6549) | Mar 10, 2020 |
| Acer          | TravelMate 5760             | [dca1c692d7](https://linux-hardware.org/?probe=dca1c692d7) | Mar 08, 2020 |
| Acer          | Aspire E5-773G              | [b51ba53e10](https://linux-hardware.org/?probe=b51ba53e10) | Mar 06, 2020 |
| Dell          | Latitude E4310              | [234ba00176](https://linux-hardware.org/?probe=234ba00176) | Feb 27, 2020 |
| Acer          | Aspire E5-773G              | [01210c0b0e](https://linux-hardware.org/?probe=01210c0b0e) | Feb 22, 2020 |
| Acer          | Aspire 5100                 | [1312407631](https://linux-hardware.org/?probe=1312407631) | Feb 17, 2020 |
| HP            | ProBook 4530s               | [639dbf3714](https://linux-hardware.org/?probe=639dbf3714) | Feb 16, 2020 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [0d6a51d929](https://linux-hardware.org/?probe=0d6a51d929) | Feb 16, 2020 |
| Dell          | Vostro 3550                 | [edfe8875af](https://linux-hardware.org/?probe=edfe8875af) | Feb 12, 2020 |
| Dell          | XPS 13 9360                 | [56f48226c5](https://linux-hardware.org/?probe=56f48226c5) | Feb 11, 2020 |
| Dell          | System XPS L702X            | [ea0d918dbc](https://linux-hardware.org/?probe=ea0d918dbc) | Feb 09, 2020 |
| HP            | Pavilion dv6                | [170bcb6796](https://linux-hardware.org/?probe=170bcb6796) | Feb 08, 2020 |
| Dell          | Latitude E6420              | [abf8099af0](https://linux-hardware.org/?probe=abf8099af0) | Feb 07, 2020 |
| Dell          | Inspiron 15-3567            | [451bf983c1](https://linux-hardware.org/?probe=451bf983c1) | Jan 29, 2020 |
| ADSC          | A21R                        | [e753f5a358](https://linux-hardware.org/?probe=e753f5a358) | Jan 25, 2020 |
| ADSC          | A21R                        | [80b05fc52a](https://linux-hardware.org/?probe=80b05fc52a) | Jan 25, 2020 |
| Lenovo        | ThinkPad X250 20CLS65E00    | [23d14de0c7](https://linux-hardware.org/?probe=23d14de0c7) | Jan 24, 2020 |
| Dell          | Vostro 3700                 | [a2fcc4ac0b](https://linux-hardware.org/?probe=a2fcc4ac0b) | Jan 15, 2020 |
| Toshiba       | Satellite Pro C850-F84U     | [43c5790730](https://linux-hardware.org/?probe=43c5790730) | Jan 15, 2020 |
| Toshiba       | Satellite Pro C850-F84U     | [19597039c1](https://linux-hardware.org/?probe=19597039c1) | Jan 14, 2020 |
| Apple         | MacBook2,1                  | [9f544e3b8a](https://linux-hardware.org/?probe=9f544e3b8a) | Jan 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [713c4952d3](https://linux-hardware.org/?probe=713c4952d3) | Jan 14, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [4bcdaf5509](https://linux-hardware.org/?probe=4bcdaf5509) | Jan 05, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [ae8aac83f4](https://linux-hardware.org/?probe=ae8aac83f4) | Jan 05, 2020 |
| Dell          | Inspiron 15-3567            | [41c1bfbdd4](https://linux-hardware.org/?probe=41c1bfbdd4) | Jan 03, 2020 |
| ASUSTek       | Strix GL704GV_GL704GV       | [772f70fa79](https://linux-hardware.org/?probe=772f70fa79) | Jan 01, 2020 |
| Acer          | TMP455-MG                   | [9f0083c2b2](https://linux-hardware.org/?probe=9f0083c2b2) | Dec 28, 2019 |
| ASUSTek       | Strix GL704GV_GL704GV       | [a47d005445](https://linux-hardware.org/?probe=a47d005445) | Dec 26, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [7605fc1d79](https://linux-hardware.org/?probe=7605fc1d79) | Dec 23, 2019 |
| Dell          | Inspiron 15-3567            | [86a1799786](https://linux-hardware.org/?probe=86a1799786) | Dec 22, 2019 |
| Acer          | TMP455-MG                   | [e7cf026b7b](https://linux-hardware.org/?probe=e7cf026b7b) | Dec 22, 2019 |
| Panasonic     | FZ55-1                      | [c6b0fb17ab](https://linux-hardware.org/?probe=c6b0fb17ab) | Dec 17, 2019 |
| Dell          | Inspiron 15-3573            | [4aa36c1dd5](https://linux-hardware.org/?probe=4aa36c1dd5) | Dec 10, 2019 |
| Dell          | G3 3779                     | [716cb93844](https://linux-hardware.org/?probe=716cb93844) | Dec 06, 2019 |
| HP            | ZBook 15 G6                 | [bdd15b19b1](https://linux-hardware.org/?probe=bdd15b19b1) | Dec 06, 2019 |
| HP            | Notebook                    | [832aafeb1a](https://linux-hardware.org/?probe=832aafeb1a) | Dec 06, 2019 |
| Acer          | TravelMate 6594             | [da5eb48dbb](https://linux-hardware.org/?probe=da5eb48dbb) | Nov 27, 2019 |
| Dell          | Inspiron N5050              | [f4cae8af59](https://linux-hardware.org/?probe=f4cae8af59) | Nov 19, 2019 |
| HP            | Notebook                    | [b9f3d1de04](https://linux-hardware.org/?probe=b9f3d1de04) | Nov 15, 2019 |
| HP            | Notebook                    | [ee3c3a87f9](https://linux-hardware.org/?probe=ee3c3a87f9) | Nov 15, 2019 |
| Lenovo        | V510-14IKB 80WR             | [649bc0e8ee](https://linux-hardware.org/?probe=649bc0e8ee) | Nov 13, 2019 |
| Lenovo        | V510-14IKB 80WR             | [a21f74c946](https://linux-hardware.org/?probe=a21f74c946) | Nov 13, 2019 |
| HP            | Notebook                    | [6b5304d567](https://linux-hardware.org/?probe=6b5304d567) | Nov 12, 2019 |
| HP            | Notebook                    | [5cc3eb5066](https://linux-hardware.org/?probe=5cc3eb5066) | Nov 11, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [689eb23f13](https://linux-hardware.org/?probe=689eb23f13) | Oct 29, 2019 |
| HP            | ProBook 6560b               | [791c17d2af](https://linux-hardware.org/?probe=791c17d2af) | Oct 26, 2019 |
| CONNEX        | L1470                       | [5e59b4f83c](https://linux-hardware.org/?probe=5e59b4f83c) | Oct 16, 2019 |
| Acer          | Aspire E1-571               | [5ae5b431d6](https://linux-hardware.org/?probe=5ae5b431d6) | Oct 14, 2019 |
| HP            | ProBook 6560b               | [113596c5ef](https://linux-hardware.org/?probe=113596c5ef) | Oct 12, 2019 |
| HP            | Notebook                    | [01242805f0](https://linux-hardware.org/?probe=01242805f0) | Oct 08, 2019 |
| HP            | ProBook 6550b               | [10745db434](https://linux-hardware.org/?probe=10745db434) | Sep 30, 2019 |
| Lenovo        | ThinkPad X201 3680L11       | [c448add7bc](https://linux-hardware.org/?probe=c448add7bc) | Sep 30, 2019 |
| HP            | ProBook 6560b               | [a94a53c453](https://linux-hardware.org/?probe=a94a53c453) | Sep 17, 2019 |
| HP            | ProBook 6560b               | [a95e0f0396](https://linux-hardware.org/?probe=a95e0f0396) | Sep 10, 2019 |
| HP            | ProBook 6560b               | [544a98fd56](https://linux-hardware.org/?probe=544a98fd56) | Sep 09, 2019 |
| Dell          | Inspiron 1525               | [ebb2371a06](https://linux-hardware.org/?probe=ebb2371a06) | Aug 28, 2019 |
| Dell          | Inspiron 1525               | [cdb9ea2eb6](https://linux-hardware.org/?probe=cdb9ea2eb6) | Aug 28, 2019 |
| HP            | ProBook 450 G0              | [4aea7a651a](https://linux-hardware.org/?probe=4aea7a651a) | Aug 27, 2019 |
| HP            | ProBook 450 G2              | [43a52eb758](https://linux-hardware.org/?probe=43a52eb758) | Aug 24, 2019 |
| ASUSTek       | GL553VE                     | [46d0739d29](https://linux-hardware.org/?probe=46d0739d29) | Aug 20, 2019 |
| Lenovo        | ThinkPad T440s 20AQ006LZ... | [4e682ac524](https://linux-hardware.org/?probe=4e682ac524) | Jul 24, 2019 |
| Dell          | Latitude E6410              | [d588cd38c2](https://linux-hardware.org/?probe=d588cd38c2) | Jul 20, 2019 |
| Dell          | Vostro 3350                 | [02a2ac15de](https://linux-hardware.org/?probe=02a2ac15de) | Jul 18, 2019 |
| Lenovo        | ThinkPad L520 5017BB3       | [916fa6f088](https://linux-hardware.org/?probe=916fa6f088) | Jul 14, 2019 |
| Samsung       | 300E4C/300E5C/300E7C        | [3a996cf854](https://linux-hardware.org/?probe=3a996cf854) | Jul 08, 2019 |
| Dell          | Vostro 3350                 | [3f908b8c67](https://linux-hardware.org/?probe=3f908b8c67) | Jul 02, 2019 |
| HP            | ProBook 4520s               | [bd68794cbe](https://linux-hardware.org/?probe=bd68794cbe) | Jun 19, 2019 |
| HP            | ProBook 4520s               | [bf38f0dbfe](https://linux-hardware.org/?probe=bf38f0dbfe) | Jun 18, 2019 |
| Toshiba       | Satellite L50-A0381         | [8618f4a1cf](https://linux-hardware.org/?probe=8618f4a1cf) | Jun 08, 2019 |
| HP            | EliteBook 8530w (FU462EA... | [e05fe6b4ab](https://linux-hardware.org/?probe=e05fe6b4ab) | May 18, 2019 |
| HP            | EliteBook 8530w (FU462EA... | [224acb078e](https://linux-hardware.org/?probe=224acb078e) | May 17, 2019 |
| HP            | 250 G6 Notebook PC          | [f6ca1a1782](https://linux-hardware.org/?probe=f6ca1a1782) | May 14, 2019 |
| Lenovo        | ThinkPad Edge E530c 3366... | [86e834e0d5](https://linux-hardware.org/?probe=86e834e0d5) | May 07, 2019 |
| Lenovo        | G500 20236                  | [2cc1e7b6e9](https://linux-hardware.org/?probe=2cc1e7b6e9) | May 07, 2019 |
| Apple         | MacBook2,1                  | [06a8da4be5](https://linux-hardware.org/?probe=06a8da4be5) | May 05, 2019 |
| Apple         | MacBook2,1                  | [c98f5d17c5](https://linux-hardware.org/?probe=c98f5d17c5) | May 05, 2019 |
| HP            | ProBook 4530s               | [93916c5a59](https://linux-hardware.org/?probe=93916c5a59) | Apr 12, 2019 |
| HP            | 635                         | [c98b3f711e](https://linux-hardware.org/?probe=c98b3f711e) | Apr 11, 2019 |
| ASUSTek       | Strix GL504GM_GL504GM       | [b1a967e21d](https://linux-hardware.org/?probe=b1a967e21d) | Apr 09, 2019 |
| HP            | 2000                        | [32c8e8239c](https://linux-hardware.org/?probe=32c8e8239c) | Feb 16, 2019 |
| Lenovo        | ThinkPad T410 2537BU0       | [1c48341762](https://linux-hardware.org/?probe=1c48341762) | Dec 18, 2018 |
| Lenovo        | ThinkPad T410 2537BU0       | [f9c9eb5f06](https://linux-hardware.org/?probe=f9c9eb5f06) | Dec 18, 2018 |
| Toshiba       | Satellite C850-F117         | [94f8199a4b](https://linux-hardware.org/?probe=94f8199a4b) | Dec 13, 2018 |
| Dell          | Latitude E6400              | [837615c7fb](https://linux-hardware.org/?probe=837615c7fb) | Nov 30, 2018 |
| Dell          | Latitude E6400              | [e92097f8a8](https://linux-hardware.org/?probe=e92097f8a8) | Nov 29, 2018 |
| Dell          | Latitude E6400              | [c6d1868c6a](https://linux-hardware.org/?probe=c6d1868c6a) | Nov 29, 2018 |
| HP            | Notebook                    | [176d8ea47b](https://linux-hardware.org/?probe=176d8ea47b) | Oct 19, 2018 |
| HP            | Notebook                    | [798c678ca4](https://linux-hardware.org/?probe=798c678ca4) | Oct 19, 2018 |
| Purism        | Librem 15 v3                | [02e23b6024](https://linux-hardware.org/?probe=02e23b6024) | May 21, 2018 |
| Lenovo        | ThinkPad W520 4284B82       | [ec9f5a20b2](https://linux-hardware.org/?probe=ec9f5a20b2) | Mar 05, 2018 |
| Samsung       | 300E4C/300E5C/300E7C        | [d126f4661a](https://linux-hardware.org/?probe=d126f4661a) | Jan 09, 2018 |
| Samsung       | 300E4C/300E5C/300E7C        | [87968fc7d7](https://linux-hardware.org/?probe=87968fc7d7) | Mar 13, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 101       | 20.57%  |
| Ubuntu 18.04        | 40        | 8.15%   |
| Zorin 16            | 18        | 3.67%   |
| KDE neon 20.04      | 18        | 3.67%   |
| Pop!_OS 21.04       | 14        | 2.85%   |
| Pop!_OS 20.04       | 13        | 2.65%   |
| Linux Mint 20.3     | 11        | 2.24%   |
| Linux Mint 20.2     | 11        | 2.24%   |
| Linux Mint 20.1     | 11        | 2.24%   |
| Zorin 15            | 10        | 2.04%   |
| Ubuntu 21.04        | 10        | 2.04%   |
| OpenMandriva 4.2    | 10        | 2.04%   |
| Manjaro             | 9         | 1.83%   |
| Linux Mint 19.3     | 9         | 1.83%   |
| Ubuntu 19.10        | 8         | 1.63%   |
| Ubuntu 19.04        | 8         | 1.63%   |
| Pop!_OS 20.10       | 8         | 1.63%   |
| Ubuntu 20.10        | 7         | 1.43%   |
| Linux Mint 20       | 7         | 1.43%   |
| Fedora 34           | 7         | 1.43%   |
| Kubuntu 20.04       | 6         | 1.22%   |
| Fedora 35           | 6         | 1.22%   |
| Linux Mint 19.1     | 5         | 1.02%   |
| Debian 11           | 5         | 1.02%   |
| Arch Rolling        | 5         | 1.02%   |
| Arch                | 5         | 1.02%   |
| Pop!_OS 21.10       | 4         | 0.81%   |
| Linux Mint 19       | 4         | 0.81%   |
| Fedora 32           | 4         | 0.81%   |
| Debian 10           | 4         | 0.81%   |
| ArcoLinux Rolling   | 4         | 0.81%   |
| Xubuntu 19.10       | 3         | 0.61%   |
| Ubuntu 22.04        | 3         | 0.61%   |
| Ubuntu 21.10        | 3         | 0.61%   |
| OpenMandriva 4.3    | 3         | 0.61%   |
| Kubuntu 21.10       | 3         | 0.61%   |
| Kali 2022.1         | 3         | 0.61%   |
| Gentoo 2.6          | 3         | 0.61%   |
| Endless 3.7.8       | 3         | 0.61%   |
| Xubuntu 20.04       | 2         | 0.41%   |
| Ubuntu Budgie 20.04 | 2         | 0.41%   |
| Ubuntu 16.04        | 2         | 0.41%   |
| Slackware 15.0      | 2         | 0.41%   |
| Rocky Linux 8.5     | 2         | 0.41%   |
| RHEL 8              | 2         | 0.41%   |
| Pop!_OS 22.04       | 2         | 0.41%   |
| Parrot 5.0          | 2         | 0.41%   |
| Lubuntu 20.04       | 2         | 0.41%   |
| LMDE 4              | 2         | 0.41%   |
| Linux Mint 19.2     | 2         | 0.41%   |
| Kubuntu 18.04       | 2         | 0.41%   |
| KDE neon 18.04      | 2         | 0.41%   |
| Kali 2021.3         | 2         | 0.41%   |
| Kali 2021.2         | 2         | 0.41%   |
| Fedora 33           | 2         | 0.41%   |
| Endless 3.9.1       | 2         | 0.41%   |
| Elementary 6.1      | 2         | 0.41%   |
| Elementary 5.1.7    | 2         | 0.41%   |
| Xubuntu 21.04       | 1         | 0.2%    |
| Xubuntu 18.04       | 1         | 0.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 173       | 36.89%  |
| Linux Mint    | 58        | 12.37%  |
| Pop!_OS       | 41        | 8.74%   |
| Zorin         | 28        | 5.97%   |
| KDE neon      | 20        | 4.26%   |
| Fedora        | 16        | 3.41%   |
| Kubuntu       | 14        | 2.99%   |
| OpenMandriva  | 13        | 2.77%   |
| Manjaro       | 13        | 2.77%   |
| Debian        | 10        | 2.13%   |
| Arch          | 10        | 2.13%   |
| Kali          | 9         | 1.92%   |
| Xubuntu       | 7         | 1.49%   |
| Endless       | 7         | 1.49%   |
| Clear Linux   | 6         | 1.28%   |
| Elementary    | 5         | 1.07%   |
| ArcoLinux     | 4         | 0.85%   |
| Ubuntu Budgie | 3         | 0.64%   |
| ROSA          | 3         | 0.64%   |
| Parrot        | 3         | 0.64%   |
| Gentoo        | 3         | 0.64%   |
| Slackware     | 2         | 0.43%   |
| Rocky Linux   | 2         | 0.43%   |
| RHEL          | 2         | 0.43%   |
| Lubuntu       | 2         | 0.43%   |
| LMDE          | 2         | 0.43%   |
| UbuntuDDE     | 1         | 0.21%   |
| PureOS        | 1         | 0.21%   |
| Peppermint    | 1         | 0.21%   |
| openSUSE      | 1         | 0.21%   |
| LinuxFX       | 1         | 0.21%   |
| KaOS          | 1         | 0.21%   |
| Garuda Linux  | 1         | 0.21%   |
| EndeavourOS   | 1         | 0.21%   |
| Deepin        | 1         | 0.21%   |
| CentOS        | 1         | 0.21%   |
| Archcraft     | 1         | 0.21%   |
| antergos      | 1         | 0.21%   |
| Alpine        | 1         | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 2.74%   |
| 5.10.14-desktop-1omv4002 | 10        | 1.83%   |
| 5.4.0-58-generic         | 9         | 1.65%   |
| 5.4.0-40-generic         | 8         | 1.46%   |
| 5.11.0-38-generic        | 8         | 1.46%   |
| 5.4.0-72-generic         | 7         | 1.28%   |
| 5.4.0-52-generic         | 7         | 1.28%   |
| 5.4.0-29-generic         | 7         | 1.28%   |
| 5.13.0-7614-generic      | 7         | 1.28%   |
| 5.13.0-39-generic        | 7         | 1.28%   |
| 5.11.0-27-generic        | 7         | 1.28%   |
| 5.8.0-43-generic         | 6         | 1.1%    |
| 5.4.0-33-generic         | 6         | 1.1%    |
| 5.4.0-26-generic         | 6         | 1.1%    |
| 5.3.0-28-generic         | 6         | 1.1%    |
| 5.13.0-28-generic        | 6         | 1.1%    |
| 5.0.0-37-generic         | 6         | 1.1%    |
| 5.8.0-7630-generic       | 5         | 0.91%   |
| 5.4.0-73-generic         | 5         | 0.91%   |
| 5.4.0-56-generic         | 5         | 0.91%   |
| 5.3.0-51-generic         | 5         | 0.91%   |
| 5.11.0-37-generic        | 5         | 0.91%   |
| 5.8.0-7642-generic       | 4         | 0.73%   |
| 5.8.0-63-generic         | 4         | 0.73%   |
| 5.4.0-77-generic         | 4         | 0.73%   |
| 5.4.0-7642-generic       | 4         | 0.73%   |
| 5.4.0-7634-generic       | 4         | 0.73%   |
| 5.4.0-31-generic         | 4         | 0.73%   |
| 5.13.0-40-generic        | 4         | 0.73%   |
| 5.13.0-30-generic        | 4         | 0.73%   |
| 5.11.0-43-generic        | 4         | 0.73%   |
| 5.11.0-41-generic        | 4         | 0.73%   |
| 5.11.0-40-generic        | 4         | 0.73%   |
| 5.11.0-34-generic        | 4         | 0.73%   |
| 5.8.0-53-generic         | 3         | 0.55%   |
| 5.8.0-50-generic         | 3         | 0.55%   |
| 5.8.0-44-generic         | 3         | 0.55%   |
| 5.8.0-41-generic         | 3         | 0.55%   |
| 5.4.0-91-generic         | 3         | 0.55%   |
| 5.4.0-80-generic         | 3         | 0.55%   |
| 5.4.0-74-generic         | 3         | 0.55%   |
| 5.4.0-65-generic         | 3         | 0.55%   |
| 5.4.0-60-generic         | 3         | 0.55%   |
| 5.4.0-47-generic         | 3         | 0.55%   |
| 5.4.0-45-generic         | 3         | 0.55%   |
| 5.3.0-42-generic         | 3         | 0.55%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.55%   |
| 5.15.15-76051515-generic | 3         | 0.55%   |
| 5.15.0-kali3-amd64       | 3         | 0.55%   |
| 5.11.0-25-generic        | 3         | 0.55%   |
| 5.11.0-22-generic        | 3         | 0.55%   |
| 4.18.0-15-generic        | 3         | 0.55%   |
| 4.15.0-29-generic        | 3         | 0.55%   |
| 5.8.0-59-generic         | 2         | 0.37%   |
| 5.8.0-36-generic         | 2         | 0.37%   |
| 5.8.0-14-generic         | 2         | 0.37%   |
| 5.4.0-92-generic         | 2         | 0.37%   |
| 5.4.0-89-generic         | 2         | 0.37%   |
| 5.4.0-84-generic         | 2         | 0.37%   |
| 5.4.0-71-generic         | 2         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 128       | 25.6%   |
| 5.11.0  | 53        | 10.6%   |
| 5.8.0   | 47        | 9.4%    |
| 5.13.0  | 45        | 9%      |
| 4.15.0  | 34        | 6.8%    |
| 5.3.0   | 31        | 6.2%    |
| 5.0.0   | 16        | 3.2%    |
| 5.10.0  | 12        | 2.4%    |
| 5.10.14 | 10        | 2%      |
| 4.18.0  | 9         | 1.8%    |
| 5.15.0  | 7         | 1.4%    |
| 5.17.5  | 5         | 1%      |
| 5.14.0  | 5         | 1%      |
| 5.16.7  | 4         | 0.8%    |
| 4.19.0  | 4         | 0.8%    |
| 5.16.18 | 3         | 0.6%    |
| 5.15.15 | 3         | 0.6%    |
| 5.14.9  | 3         | 0.6%    |
| 5.17.9  | 2         | 0.4%    |
| 5.16.11 | 2         | 0.4%    |
| 5.12.5  | 2         | 0.4%    |
| 5.9.16  | 1         | 0.2%    |
| 5.9.14  | 1         | 0.2%    |
| 5.9.11  | 1         | 0.2%    |
| 5.9.1   | 1         | 0.2%    |
| 5.9.0   | 1         | 0.2%    |
| 5.8.9   | 1         | 0.2%    |
| 5.8.3   | 1         | 0.2%    |
| 5.8.16  | 1         | 0.2%    |
| 5.8.10  | 1         | 0.2%    |
| 5.8.1   | 1         | 0.2%    |
| 5.7.9   | 1         | 0.2%    |
| 5.7.7   | 1         | 0.2%    |
| 5.7.2   | 1         | 0.2%    |
| 5.7.10  | 1         | 0.2%    |
| 5.7.1   | 1         | 0.2%    |
| 5.7.0   | 1         | 0.2%    |
| 5.6.7   | 1         | 0.2%    |
| 5.6.19  | 1         | 0.2%    |
| 5.6.16  | 1         | 0.2%    |
| 5.6.14  | 1         | 0.2%    |
| 5.6.11  | 1         | 0.2%    |
| 5.6.10  | 1         | 0.2%    |
| 5.6.0   | 1         | 0.2%    |
| 5.5.9   | 1         | 0.2%    |
| 5.5.8   | 1         | 0.2%    |
| 5.5.0   | 1         | 0.2%    |
| 5.4.60  | 1         | 0.2%    |
| 5.4.32  | 1         | 0.2%    |
| 5.3.12  | 1         | 0.2%    |
| 5.3.10  | 1         | 0.2%    |
| 5.2.9   | 1         | 0.2%    |
| 5.18.5  | 1         | 0.2%    |
| 5.17.7  | 1         | 0.2%    |
| 5.16.8  | 1         | 0.2%    |
| 5.16.16 | 1         | 0.2%    |
| 5.16.10 | 1         | 0.2%    |
| 5.16.0  | 1         | 0.2%    |
| 5.15.6  | 1         | 0.2%    |
| 5.15.5  | 1         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 130       | 26.32%  |
| 5.11    | 57        | 11.54%  |
| 5.8     | 52        | 10.53%  |
| 5.13    | 50        | 10.12%  |
| 4.15    | 34        | 6.88%   |
| 5.3     | 33        | 6.68%   |
| 5.10    | 29        | 5.87%   |
| 5.15    | 19        | 3.85%   |
| 5.0     | 16        | 3.24%   |
| 5.16    | 12        | 2.43%   |
| 5.14    | 10        | 2.02%   |
| 4.18    | 9         | 1.82%   |
| 5.17    | 8         | 1.62%   |
| 5.7     | 6         | 1.21%   |
| 5.6     | 6         | 1.21%   |
| 5.9     | 5         | 1.01%   |
| 4.19    | 5         | 1.01%   |
| 5.5     | 3         | 0.61%   |
| 5.12    | 3         | 0.61%   |
| 5.2     | 1         | 0.2%    |
| 5.18    | 1         | 0.2%    |
| 4.9     | 1         | 0.2%    |
| 4.16    | 1         | 0.2%    |
| 4.13    | 1         | 0.2%    |
| 4.12    | 1         | 0.2%    |
| 4.1     | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 443       | 97.15%  |
| i686   | 13        | 2.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 232       | 49.15%  |
| KDE5             | 57        | 12.08%  |
| Unknown          | 48        | 10.17%  |
| X-Cinnamon       | 41        | 8.69%   |
| XFCE             | 29        | 6.14%   |
| KDE              | 21        | 4.45%   |
| MATE             | 11        | 2.33%   |
| Unity            | 6         | 1.27%   |
| Pantheon         | 5         | 1.06%   |
| Cinnamon         | 4         | 0.85%   |
| Deepin           | 3         | 0.64%   |
| Budgie           | 3         | 0.64%   |
| LXDE             | 2         | 0.42%   |
| lightdm-xsession | 2         | 0.42%   |
| KDE4             | 2         | 0.42%   |
| LXQt             | 1         | 0.21%   |
| i3               | 1         | 0.21%   |
| GNOME Flashback  | 1         | 0.21%   |
| GNOME Classic    | 1         | 0.21%   |
| bspwm            | 1         | 0.21%   |
| Awesome          | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 399       | 84.18%  |
| Wayland | 46        | 9.7%    |
| Unknown | 20        | 4.22%   |
| Tty     | 9         | 1.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 311       | 65.75%  |
| SDDM    | 49        | 10.36%  |
| GDM     | 36        | 7.61%   |
| GDM3    | 35        | 7.4%    |
| LightDM | 28        | 5.92%   |
| TDM     | 12        | 2.54%   |
| KDM     | 2         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_ZA   | 307       | 65.46%  |
| en_US   | 81        | 17.27%  |
| Unknown | 39        | 8.32%   |
| en_GB   | 35        | 7.46%   |
| C       | 4         | 0.85%   |
| fr_FR   | 2         | 0.43%   |
| en_ZW   | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 250       | 53.53%  |
| EFI  | 217       | 46.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 394       | 85.28%  |
| Overlay | 21        | 4.55%   |
| Btrfs   | 20        | 4.33%   |
| Unknown | 12        | 2.6%    |
| Xfs     | 8         | 1.73%   |
| Zfs     | 4         | 0.87%   |
| Aufs    | 2         | 0.43%   |
| Tmpfs   | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 338       | 72.84%  |
| GPT     | 101       | 21.77%  |
| MBR     | 25        | 5.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 420       | 90.71%  |
| Yes       | 43        | 9.29%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 345       | 74.51%  |
| Yes       | 118       | 25.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 110       | 24.12%  |
| Dell                | 110       | 24.12%  |
| Lenovo              | 80        | 17.54%  |
| ASUSTek Computer    | 38        | 8.33%   |
| Acer                | 37        | 8.11%   |
| Apple               | 13        | 2.85%   |
| Toshiba             | 8         | 1.75%   |
| Samsung Electronics | 7         | 1.54%   |
| Packard Bell        | 5         | 1.1%    |
| MSI                 | 5         | 1.1%    |
| Sony                | 4         | 0.88%   |
| Gigabyte Technology | 4         | 0.88%   |
| Standard            | 3         | 0.66%   |
| Mustek              | 3         | 0.66%   |
| CONNEX              | 3         | 0.66%   |
| Purism              | 2         | 0.44%   |
| PINNACLEMICRO       | 2         | 0.44%   |
| MECER               | 2         | 0.44%   |
| HUAWEI              | 2         | 0.44%   |
| Fujitsu             | 2         | 0.44%   |
| YiFang              | 1         | 0.22%   |
| WinSome             | 1         | 0.22%   |
| TCL Communication   | 1         | 0.22%   |
| System76            | 1         | 0.22%   |
| Razer               | 1         | 0.22%   |
| Proline             | 1         | 0.22%   |
| Notebook            | 1         | 0.22%   |
| LG Electronics      | 1         | 0.22%   |
| LattePanda          | 1         | 0.22%   |
| Intel               | 1         | 0.22%   |
| Google              | 1         | 0.22%   |
| Fujitsu Siemens     | 1         | 0.22%   |
| eMachines           | 1         | 0.22%   |
| Alienware           | 1         | 0.22%   |
| ADSC                | 1         | 0.22%   |
| Unknown             | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Inspiron 15-3567                | 10        | 2.19%   |
| Unknown                              | 6         | 1.32%   |
| HP ProBook 4530s                     | 4         | 0.88%   |
| HP Pavilion dv7                      | 4         | 0.88%   |
| HP Notebook                          | 4         | 0.88%   |
| HP 635                               | 4         | 0.88%   |
| Dell XPS 13 9310                     | 4         | 0.88%   |
| Dell Latitude E6400                  | 4         | 0.88%   |
| Lenovo IdeaPad 110-15IBR 80T7        | 3         | 0.66%   |
| Lenovo G500 20236                    | 3         | 0.66%   |
| HP ProBook 4520s                     | 3         | 0.66%   |
| HP Laptop 15-da0xxx                  | 3         | 0.66%   |
| HP Laptop 15-bs1xx                   | 3         | 0.66%   |
| HP Laptop 15-bs0xx                   | 3         | 0.66%   |
| Dell Latitude E6430                  | 3         | 0.66%   |
| Dell Inspiron 3580                   | 3         | 0.66%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 3         | 0.66%   |
| Apple MacBookPro9,2                  | 3         | 0.66%   |
| Apple MacBookPro16,1                 | 3         | 0.66%   |
| Acer Aspire E1-571                   | 3         | 0.66%   |
| Toshiba Satellite L655               | 2         | 0.44%   |
| Samsung 300E4C/300E5C/300E7C         | 2         | 0.44%   |
| Lenovo V510-14IKB 80WR               | 2         | 0.44%   |
| Lenovo ThinkPad T410 25376B8         | 2         | 0.44%   |
| Lenovo ThinkPad Edge E540 20C600HHZA | 2         | 0.44%   |
| Lenovo IdeaPad 320-15IKB 80XL        | 2         | 0.44%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 2         | 0.44%   |
| HP ProBook 6560b                     | 2         | 0.44%   |
| HP ProBook 450 G3                    | 2         | 0.44%   |
| HP ProBook 450 G2                    | 2         | 0.44%   |
| HP Pavilion dv6                      | 2         | 0.44%   |
| HP Laptop 15-dw3xxx                  | 2         | 0.44%   |
| HP ENVY TS 15                        | 2         | 0.44%   |
| HP EliteBook 850 G3                  | 2         | 0.44%   |
| HP 650                               | 2         | 0.44%   |
| HP 530 Notebook PC(KD092AA#ACQ)      | 2         | 0.44%   |
| HP 255 G7 Notebook PC                | 2         | 0.44%   |
| HP 250 G6 Notebook PC                | 2         | 0.44%   |
| Dell XPS 15 7590                     | 2         | 0.44%   |
| Dell System XPS L502X                | 2         | 0.44%   |
| Dell Latitude E7440                  | 2         | 0.44%   |
| Dell Latitude D630                   | 2         | 0.44%   |
| Dell Latitude 5590                   | 2         | 0.44%   |
| Dell Latitude 5580                   | 2         | 0.44%   |
| Dell Latitude 5490                   | 2         | 0.44%   |
| Dell Latitude 3550                   | 2         | 0.44%   |
| Dell Inspiron N5110                  | 2         | 0.44%   |
| Dell Inspiron M5040                  | 2         | 0.44%   |
| Dell Inspiron 3537                   | 2         | 0.44%   |
| Dell Inspiron 3521                   | 2         | 0.44%   |
| Dell Inspiron 1545                   | 2         | 0.44%   |
| Dell Inspiron 1525                   | 2         | 0.44%   |
| Dell G3 3779                         | 2         | 0.44%   |
| Dell G3 3579                         | 2         | 0.44%   |
| CONNEX L1470                         | 2         | 0.44%   |
| ASUS X555LAB                         | 2         | 0.44%   |
| Apple MacBookPro7,1                  | 2         | 0.44%   |
| Acer TravelMate 5730                 | 2         | 0.44%   |
| Acer Aspire ES1-531                  | 2         | 0.44%   |
| Acer Aspire A315-54K                 | 2         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 40        | 8.77%   |
| Dell Inspiron          | 38        | 8.33%   |
| Dell Latitude          | 37        | 8.11%   |
| HP ProBook             | 25        | 5.48%   |
| Lenovo IdeaPad         | 24        | 5.26%   |
| Acer Aspire            | 23        | 5.04%   |
| HP Laptop              | 17        | 3.73%   |
| HP EliteBook           | 14        | 3.07%   |
| HP Pavilion            | 13        | 2.85%   |
| Dell XPS               | 10        | 2.19%   |
| ASUS VivoBook          | 10        | 2.19%   |
| Toshiba Satellite      | 7         | 1.54%   |
| Dell Vostro            | 7         | 1.54%   |
| Acer TravelMate        | 7         | 1.54%   |
| HP Compaq              | 6         | 1.32%   |
| Dell Precision         | 6         | 1.32%   |
| Unknown                | 6         | 1.32%   |
| Dell G3                | 5         | 1.1%    |
| HP Notebook            | 4         | 0.88%   |
| HP 635                 | 4         | 0.88%   |
| HP 255                 | 4         | 0.88%   |
| HP 250                 | 4         | 0.88%   |
| Packard Bell EasyNote  | 3         | 0.66%   |
| Lenovo G500            | 3         | 0.66%   |
| HP ZBook               | 3         | 0.66%   |
| HP ENVY                | 3         | 0.66%   |
| HP 530                 | 3         | 0.66%   |
| Dell System            | 3         | 0.66%   |
| Apple MacBookPro9      | 3         | 0.66%   |
| Apple MacBookPro16     | 3         | 0.66%   |
| Acer Swift             | 3         | 0.66%   |
| Samsung 300E4C         | 2         | 0.44%   |
| Purism Librem          | 2         | 0.44%   |
| Lenovo Yoga            | 2         | 0.44%   |
| Lenovo V510-14IKB      | 2         | 0.44%   |
| Lenovo Legion          | 2         | 0.44%   |
| HP Presario            | 2         | 0.44%   |
| HP 650                 | 2         | 0.44%   |
| Fujitsu LIFEBOOK       | 2         | 0.44%   |
| Dell G5                | 2         | 0.44%   |
| CONNEX L1470           | 2         | 0.44%   |
| ASUS X555LAB           | 2         | 0.44%   |
| ASUS TUF               | 2         | 0.44%   |
| ASUS Strix             | 2         | 0.44%   |
| Apple MacBookPro8      | 2         | 0.44%   |
| Apple MacBookPro7      | 2         | 0.44%   |
| YiFang NXM1012BCP      | 1         | 0.22%   |
| WinSome A14C           | 1         | 0.22%   |
| Toshiba TECRA          | 1         | 0.22%   |
| TCL Communication 8085 | 1         | 0.22%   |
| System76 Oryx          | 1         | 0.22%   |
| Sony VPCP116KG         | 1         | 0.22%   |
| Sony VPCEH38FG         | 1         | 0.22%   |
| Sony VPCCB17FG         | 1         | 0.22%   |
| Sony VGN-CR343N        | 1         | 0.22%   |
| Samsung RV411          | 1         | 0.22%   |
| Samsung RC410          | 1         | 0.22%   |
| Samsung N150P          | 1         | 0.22%   |
| Samsung 700Z3A         | 1         | 0.22%   |
| Samsung 350V5C         | 1         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 53        | 11.62%  |
| 2011 | 51        | 11.18%  |
| 2017 | 37        | 8.11%   |
| 2016 | 35        | 7.68%   |
| 2020 | 34        | 7.46%   |
| 2019 | 34        | 7.46%   |
| 2013 | 33        | 7.24%   |
| 2012 | 33        | 7.24%   |
| 2008 | 30        | 6.58%   |
| 2015 | 28        | 6.14%   |
| 2010 | 28        | 6.14%   |
| 2014 | 20        | 4.39%   |
| 2021 | 14        | 3.07%   |
| 2009 | 13        | 2.85%   |
| 2007 | 10        | 2.19%   |
| 2006 | 3         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 456       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 403       | 86.85%  |
| Enabled  | 61        | 13.15%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 452       | 99.12%  |
| Yes  | 4         | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 119       | 25.87%  |
| 4.01-8.0    | 117       | 25.43%  |
| 16.01-24.0  | 70        | 15.22%  |
| 8.01-16.0   | 70        | 15.22%  |
| 1.01-2.0    | 32        | 6.96%   |
| 32.01-64.0  | 25        | 5.43%   |
| 2.01-3.0    | 13        | 2.83%   |
| 24.01-32.0  | 6         | 1.3%    |
| 64.01-256.0 | 4         | 0.87%   |
| 0.51-1.0    | 4         | 0.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 194       | 37.67%  |
| 2.01-3.0   | 142       | 27.57%  |
| 4.01-8.0   | 61        | 11.84%  |
| 3.01-4.0   | 50        | 9.71%   |
| 0.51-1.0   | 36        | 6.99%   |
| 8.01-16.0  | 24        | 4.66%   |
| 16.01-24.0 | 4         | 0.78%   |
| 0.01-0.5   | 3         | 0.58%   |
| 24.01-32.0 | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 315       | 67.89%  |
| 2      | 125       | 26.94%  |
| 3      | 12        | 2.59%   |
| 0      | 9         | 1.94%   |
| 4      | 3         | 0.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 240       | 52.29%  |
| No        | 219       | 47.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 409       | 89.69%  |
| No        | 47        | 10.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 445       | 97.59%  |
| No        | 11        | 2.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 363       | 78.06%  |
| No        | 102       | 21.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| South Africa | 456       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Johannesburg     | 127       | 25.76%  |
| Cape Town        | 114       | 23.12%  |
| Pretoria         | 56        | 11.36%  |
| Durban           | 25        | 5.07%   |
| Port Elizabeth   | 13        | 2.64%   |
| Centurion        | 10        | 2.03%   |
| East London      | 9         | 1.83%   |
| Sandton          | 8         | 1.62%   |
| Pietermaritzburg | 7         | 1.42%   |
| Roodepoort       | 5         | 1.01%   |
| Bloemfontein     | 5         | 1.01%   |
| Thabazimbi       | 4         | 0.81%   |
| Randburg         | 4         | 0.81%   |
| Potchefstroom    | 4         | 0.81%   |
| Polokwane        | 4         | 0.81%   |
| Midrand          | 4         | 0.81%   |
| Boksburg         | 4         | 0.81%   |
| Bellville        | 4         | 0.81%   |
| Somerset West    | 3         | 0.61%   |
| Benoni           | 3         | 0.61%   |
| Alberton         | 3         | 0.61%   |
| Witbank          | 2         | 0.41%   |
| White River      | 2         | 0.41%   |
| Vanderbijlpark   | 2         | 0.41%   |
| Sabie            | 2         | 0.41%   |
| Port Alfred      | 2         | 0.41%   |
| Oudtshoorn       | 2         | 0.41%   |
| Mokopane         | 2         | 0.41%   |
| Middelburg       | 2         | 0.41%   |
| Louis Trichardt  | 2         | 0.41%   |
| Lichtenburg      | 2         | 0.41%   |
| Klerksdorp       | 2         | 0.41%   |
| Kempton Park     | 2         | 0.41%   |
| Hermanus         | 2         | 0.41%   |
| George           | 2         | 0.41%   |
| Edenvale         | 2         | 0.41%   |
| Zeerust          | 1         | 0.2%    |
| Worcester        | 1         | 0.2%    |
| Wellington       | 1         | 0.2%    |
| Welkom           | 1         | 0.2%    |
| Villiersdorp     | 1         | 0.2%    |
| Upington         | 1         | 0.2%    |
| Tzaneen          | 1         | 0.2%    |
| Tulbagh          | 1         | 0.2%    |
| Thohoyandou      | 1         | 0.2%    |
| Strand           | 1         | 0.2%    |
| Stellenbosch     | 1         | 0.2%    |
| Standerton       | 1         | 0.2%    |
| Springs          | 1         | 0.2%    |
| Springbok        | 1         | 0.2%    |
| Sandown          | 1         | 0.2%    |
| Richards Bay     | 1         | 0.2%    |
| Randfontein      | 1         | 0.2%    |
| Plettenberg Bay  | 1         | 0.2%    |
| Nelspruit        | 1         | 0.2%    |
| Mulbarton        | 1         | 0.2%    |
| Mossel Bay       | 1         | 0.2%    |
| Melkbosstrand    | 1         | 0.2%    |
| Lebowakgomo      | 1         | 0.2%    |
| Ladysmith        | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 104       | 147    | 18.18%  |
| WDC                 | 94        | 114    | 16.43%  |
| Toshiba             | 73        | 88     | 12.76%  |
| Samsung Electronics | 53        | 72     | 9.27%   |
| Unknown             | 31        | 38     | 5.42%   |
| Hitachi             | 23        | 33     | 4.02%   |
| HGST                | 23        | 28     | 4.02%   |
| SanDisk             | 17        | 23     | 2.97%   |
| Kingston            | 17        | 19     | 2.97%   |
| SK hynix            | 14        | 14     | 2.45%   |
| Transcend           | 11        | 14     | 1.92%   |
| Intel               | 11        | 14     | 1.92%   |
| A-DATA Technology   | 11        | 17     | 1.92%   |
| Silicon Motion      | 10        | 18     | 1.75%   |
| Crucial             | 9         | 9      | 1.57%   |
| TO Exter            | 6         | 6      | 1.05%   |
| Apple               | 6         | 7      | 1.05%   |
| Fujitsu             | 5         | 6      | 0.87%   |
| KIOXIA              | 4         | 4      | 0.7%    |
| Hikvision           | 4         | 4      | 0.7%    |
| Micron Technology   | 3         | 4      | 0.52%   |
| LITEONIT            | 3         | 4      | 0.52%   |
| LITEON              | 3         | 3      | 0.52%   |
| Phison              | 2         | 2      | 0.35%   |
| Netac               | 2         | 2      | 0.35%   |
| Mushkin             | 2         | 4      | 0.35%   |
| JMicron Technology  | 2         | 2      | 0.35%   |
| HGST HTS            | 2         | 2      | 0.35%   |
| Hewlett-Packard     | 2         | 3      | 0.35%   |
| Gigabyte Technology | 2         | 3      | 0.35%   |
| External            | 2         | 2      | 0.35%   |
| Apacer              | 2         | 2      | 0.35%   |
| Union Memory        | 1         | 1      | 0.17%   |
| UMIS                | 1         | 1      | 0.17%   |
| Radeon              | 1         | 1      | 0.17%   |
| Plextor             | 1         | 1      | 0.17%   |
| PHISON S            | 1         | 1      | 0.17%   |
| Netac SS            | 1         | 1      | 0.17%   |
| Neo Forza           | 1         | 1      | 0.17%   |
| MyDigitalSSD        | 1         | 1      | 0.17%   |
| Lite-On             | 1         | 1      | 0.17%   |
| Lexar               | 1         | 1      | 0.17%   |
| Lenovo              | 1         | 1      | 0.17%   |
| Kingmax             | 1         | 1      | 0.17%   |
| Hypertec            | 1         | 1      | 0.17%   |
| HUAWEI              | 1         | 1      | 0.17%   |
| HS-SSD-E100         | 1         | 2      | 0.17%   |
| HS-SSD-C100         | 1         | 2      | 0.17%   |
| Corsair             | 1         | 2      | 0.17%   |
| AFOX                | 1         | 1      | 0.17%   |
| Unknown             | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 25        | 4.24%   |
| Toshiba MQ01ABF050 500GB             | 13        | 2.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 11        | 1.86%   |
| Toshiba MQ04ABF100 1TB               | 10        | 1.69%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 9         | 1.53%   |
| HGST HTS721010A9E630 1TB             | 9         | 1.53%   |
| Unknown MMC Card  32GB               | 8         | 1.36%   |
| Toshiba MQ01ABD100 1TB               | 8         | 1.36%   |
| Samsung NVMe SSD Drive 256GB         | 7         | 1.19%   |
| Toshiba MQ01ACF050 500GB             | 6         | 1.02%   |
| TO Exter nal USB 3.0 256GB           | 6         | 1.02%   |
| Seagate ST500LT012-1DG142 500GB      | 6         | 1.02%   |
| Samsung NVMe SSD Drive 512GB         | 6         | 1.02%   |
| HGST HTS541010A9E680 1TB             | 6         | 1.02%   |
| Toshiba NVMe SSD Drive 512GB         | 5         | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 4         | 0.68%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 4         | 0.68%   |
| WDC WD10SPZX-60Z10T0 1TB             | 4         | 0.68%   |
| Intel NVMe SSD Drive 512GB           | 4         | 0.68%   |
| WDC WD10JPVX-75JC3T0 1TB             | 3         | 0.51%   |
| WDC WD10JPVX-60JC3T0 1TB             | 3         | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 0.51%   |
| WDC WD10JPCX-24UE4T0 1TB             | 3         | 0.51%   |
| Unknown SC16G  16GB                  | 3         | 0.51%   |
| Unknown MMC Card  16GB               | 3         | 0.51%   |
| Transcend TS256GSSD230S 256GB        | 3         | 0.51%   |
| SK hynix NVMe SSD Drive 512GB        | 3         | 0.51%   |
| SK hynix NVMe SSD Drive 256GB        | 3         | 0.51%   |
| Silicon Motion NVMe SSD Drive 1024GB | 3         | 0.51%   |
| Seagate ST9500423AS 500GB            | 3         | 0.51%   |
| Seagate ST9500325AS 500GB            | 3         | 0.51%   |
| Seagate ST9320423AS 320GB            | 3         | 0.51%   |
| Seagate ST9320325AS 320GB            | 3         | 0.51%   |
| Seagate ST9250315AS 250GB            | 3         | 0.51%   |
| Seagate ST500LM030-2E717D 500GB      | 3         | 0.51%   |
| Seagate ST1000LX015-1U7172 1TB       | 3         | 0.51%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 0.51%   |
| Seagate ST1000LM014-1EJ164 1TB       | 3         | 0.51%   |
| SanDisk SSD PLUS 240GB               | 3         | 0.51%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 0.51%   |
| Samsung NVMe SSD Drive 1024GB        | 3         | 0.51%   |
| Hitachi HTS543232A7A384 320GB        | 3         | 0.51%   |
| HGST HTS725050A7E630 500GB           | 3         | 0.51%   |
| Apple SSD AP1024N 1TB                | 3         | 0.51%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 2         | 0.34%   |
| WDC WD5000BUCT-63PUZY0 500GB         | 2         | 0.34%   |
| WDC WD3200BPVT-75ZEST0 320GB         | 2         | 0.34%   |
| WDC WD3200BPVT-22ZEST0 320GB         | 2         | 0.34%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 2         | 0.34%   |
| WDC WD3200BEKT-60V5T1 320GB          | 2         | 0.34%   |
| WDC WD1200BEVS-60UST0 120GB          | 2         | 0.34%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.34%   |
| Unknown SS16G  16GB                  | 2         | 0.34%   |
| Transcend TS120GSSD220S 120GB        | 2         | 0.34%   |
| Toshiba MK6461GSY 640GB              | 2         | 0.34%   |
| Toshiba MK5065GSXF 500GB             | 2         | 0.34%   |
| Toshiba MK3259GSXP 320GB             | 2         | 0.34%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 2         | 0.34%   |
| Silicon Motion NVMe SSD Drive 512GB  | 2         | 0.34%   |
| Silicon Motion NVMe SSD Drive 2TB    | 2         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 100       | 136    | 34.48%  |
| WDC                 | 73        | 88     | 25.17%  |
| Toshiba             | 57        | 69     | 19.66%  |
| Hitachi             | 23        | 33     | 7.93%   |
| HGST                | 23        | 28     | 7.93%   |
| Fujitsu             | 5         | 6      | 1.72%   |
| Samsung Electronics | 4         | 4      | 1.38%   |
| Apple               | 3         | 3      | 1.03%   |
| Unknown             | 1         | 1      | 0.34%   |
| HGST HTS            | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 36     | 17.93%  |
| WDC                 | 20        | 24     | 13.79%  |
| SanDisk             | 12        | 15     | 8.28%   |
| Kingston            | 12        | 14     | 8.28%   |
| Transcend           | 10        | 13     | 6.9%    |
| A-DATA Technology   | 9         | 15     | 6.21%   |
| Crucial             | 8         | 8      | 5.52%   |
| TO Exter            | 6         | 6      | 4.14%   |
| Toshiba             | 5         | 6      | 3.45%   |
| SK hynix            | 4         | 4      | 2.76%   |
| Seagate             | 4         | 8      | 2.76%   |
| Intel               | 4         | 5      | 2.76%   |
| Micron Technology   | 3         | 4      | 2.07%   |
| LITEONIT            | 3         | 4      | 2.07%   |
| Netac               | 2         | 2      | 1.38%   |
| LITEON              | 2         | 2      | 1.38%   |
| Gigabyte Technology | 2         | 3      | 1.38%   |
| Apacer              | 2         | 2      | 1.38%   |
| Radeon              | 1         | 1      | 0.69%   |
| Plextor             | 1         | 1      | 0.69%   |
| Neo Forza           | 1         | 1      | 0.69%   |
| MyDigitalSSD        | 1         | 1      | 0.69%   |
| Lexar               | 1         | 1      | 0.69%   |
| Kingmax             | 1         | 1      | 0.69%   |
| Hypertec            | 1         | 1      | 0.69%   |
| Hikvision           | 1         | 1      | 0.69%   |
| Hewlett-Packard     | 1         | 1      | 0.69%   |
| Corsair             | 1         | 2      | 0.69%   |
| AFOX                | 1         | 1      | 0.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 285       | 369    | 51.44%  |
| SSD     | 135       | 183    | 24.37%  |
| NVMe    | 91        | 124    | 16.43%  |
| MMC     | 30        | 38     | 5.42%   |
| Unknown | 13        | 16     | 2.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 378       | 537    | 71.73%  |
| NVMe | 91        | 124    | 17.27%  |
| MMC  | 30        | 38     | 5.69%   |
| SAS  | 28        | 31     | 5.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 262       | 357    | 62.68%  |
| 0.51-1.0   | 144       | 181    | 34.45%  |
| 1.01-2.0   | 8         | 8      | 1.91%   |
| 3.01-4.0   | 3         | 5      | 0.72%   |
| 4.01-10.0  | 1         | 1      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 143       | 29.67%  |
| 101-250        | 110       | 22.82%  |
| 501-1000       | 84        | 17.43%  |
| 1001-2000      | 45        | 9.34%   |
| 51-100         | 29        | 6.02%   |
| 1-20           | 26        | 5.39%   |
| 21-50          | 18        | 3.73%   |
| 2001-3000      | 10        | 2.07%   |
| Unknown        | 10        | 2.07%   |
| More than 3000 | 7         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 171       | 33.4%   |
| 21-50          | 102       | 19.92%  |
| 51-100         | 71        | 13.87%  |
| 101-250        | 61        | 11.91%  |
| 251-500        | 46        | 8.98%   |
| 501-1000       | 35        | 6.84%   |
| 1001-2000      | 11        | 2.15%   |
| Unknown        | 10        | 1.95%   |
| 2001-3000      | 4         | 0.78%   |
| More than 3000 | 1         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 14.29%  |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 14.29%  |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 4.76%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 4.76%   |
| Toshiba MK5065GSXF 500GB              | 1         | 1      | 4.76%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 4.76%   |
| Seagate ST9500423AS 500GB             | 1         | 1      | 4.76%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 4.76%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 4.76%   |
| Seagate ST1000LM014-SSHD-8GB          | 1         | 1      | 4.76%   |
| Micron Technology 1100 SATA 256GB SSD | 1         | 1      | 4.76%   |
| Intel SSDSCKKF240H6L 240GB            | 1         | 2      | 4.76%   |
| Intel SSDSC2BF240A4L 240GB            | 1         | 1      | 4.76%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 4.76%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 4.76%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 10        | 10     | 47.62%  |
| WDC               | 2         | 2      | 9.52%   |
| Toshiba           | 2         | 2      | 9.52%   |
| Intel             | 2         | 3      | 9.52%   |
| HGST              | 2         | 2      | 9.52%   |
| SK hynix          | 1         | 1      | 4.76%   |
| Micron Technology | 1         | 1      | 4.76%   |
| Hitachi           | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 10     | 58.82%  |
| WDC     | 2         | 2      | 11.76%  |
| Toshiba | 2         | 2      | 11.76%  |
| HGST    | 2         | 2      | 11.76%  |
| Hitachi | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 17     | 80.95%  |
| SSD  | 4         | 5      | 19.05%  |

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
| Detected | 345       | 550    | 72.33%  |
| Works    | 111       | 158    | 23.27%  |
| Malfunc  | 21        | 22     | 4.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 376       | 74.6%   |
| AMD                              | 32        | 6.35%   |
| Samsung Electronics              | 24        | 4.76%   |
| Toshiba America Info Systems     | 16        | 3.17%   |
| Silicon Motion                   | 11        | 2.18%   |
| SK hynix                         | 10        | 1.98%   |
| SanDisk                          | 6         | 1.19%   |
| KIOXIA                           | 5         | 0.99%   |
| Kingston Technology Company      | 5         | 0.99%   |
| Phison Electronics               | 3         | 0.6%    |
| Nvidia                           | 3         | 0.6%    |
| Apple                            | 3         | 0.6%    |
| MAXIO Technology (Hangzhou)      | 2         | 0.4%    |
| ADATA Technology                 | 2         | 0.4%    |
| Union Memory (Shenzhen)          | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Micron/Crucial Technology        | 1         | 0.2%    |
| Lite-On Technology               | 1         | 0.2%    |
| Lenovo                           | 1         | 0.2%    |
| Biwin Storage Technology         | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 56        | 10.24%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 46        | 8.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 38        | 6.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 34        | 6.22%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 21        | 3.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 18        | 3.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 18        | 3.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 17        | 3.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 17        | 3.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 15        | 2.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 15        | 2.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 13        | 2.38%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 12        | 2.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 12        | 2.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 11        | 2.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 11        | 2.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 10        | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 10        | 1.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 9         | 1.65%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                          | 8         | 1.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 8         | 1.46%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 7         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 6         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 6         | 1.1%    |
| Samsung NVMe SSD Controller 980                                                        | 5         | 0.91%   |
| KIOXIA Non-Volatile memory controller                                                  | 5         | 0.91%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 5         | 0.91%   |
| Intel SSD 660P Series                                                                  | 5         | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 0.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 4         | 0.73%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 4         | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 4         | 0.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 4         | 0.73%   |
| SK hynix BC511                                                                         | 3         | 0.55%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 3         | 0.55%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 3         | 0.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 0.55%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 3         | 0.55%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 3         | 0.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 3         | 0.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 0.55%   |
| Apple ANS2 NVMe Controller                                                             | 3         | 0.55%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 2         | 0.37%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 2         | 0.37%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                           | 2         | 0.37%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 2         | 0.37%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.37%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 2         | 0.37%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 0.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 2         | 0.37%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 0.37%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 0.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 2         | 0.37%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 2         | 0.37%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 2         | 0.37%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                 | 1         | 0.18%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                   | 1         | 0.18%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 1         | 0.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 343       | 64.96%  |
| NVMe | 95        | 17.99%  |
| RAID | 52        | 9.85%   |
| IDE  | 38        | 7.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 415       | 91.01%  |
| AMD    | 41        | 8.99%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz       | 11        | 2.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 10        | 2.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 9         | 1.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 9         | 1.97%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 9         | 1.97%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 9         | 1.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 8         | 1.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 8         | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 8         | 1.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 7         | 1.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 7         | 1.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 7         | 1.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 7         | 1.54%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 7         | 1.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 6         | 1.32%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 6         | 1.32%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 6         | 1.32%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 6         | 1.32%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 6         | 1.32%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 6         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 1.1%    |
| Intel Core i5-2450M CPU @ 2.50GHz       | 5         | 1.1%    |
| Intel Core i5-2410M CPU @ 2.30GHz       | 5         | 1.1%    |
| Intel Core i3-5005U CPU @ 2.00GHz       | 5         | 1.1%    |
| Intel Celeron CPU N3350 @ 1.10GHz       | 5         | 1.1%    |
| Intel Celeron CPU N3050 @ 1.60GHz       | 5         | 1.1%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 5         | 1.1%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 5         | 1.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 1.1%    |
| AMD E-450 APU with Radeon HD Graphics   | 5         | 1.1%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 4         | 0.88%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 4         | 0.88%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 4         | 0.88%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 4         | 0.88%   |
| Intel Core i9-9880H CPU @ 2.30GHz       | 3         | 0.66%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 3         | 0.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 3         | 0.66%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 0.66%   |
| Intel Core i5-4200M CPU @ 2.50GHz       | 3         | 0.66%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 3         | 0.66%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 3         | 0.66%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 3         | 0.66%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 3         | 0.66%   |
| Intel Core i3 CPU M 350 @ 2.27GHz       | 3         | 0.66%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz    | 3         | 0.66%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 3         | 0.66%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 0.66%   |
| Intel Genuine CPU U7300 @ 1.30GHz       | 2         | 0.44%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 2         | 0.44%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 2         | 0.44%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz      | 2         | 0.44%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz      | 2         | 0.44%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 2         | 0.44%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 2         | 0.44%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.44%   |
| Intel Core i7-3537U CPU @ 2.00GHz       | 2         | 0.44%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 2         | 0.44%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 2         | 0.44%   |
| Intel Core i7-10875H CPU @ 2.30GHz      | 2         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 136       | 29.82%  |
| Intel Core i5           | 124       | 27.19%  |
| Intel Core i3           | 46        | 10.09%  |
| Intel Celeron           | 38        | 8.33%   |
| Intel Core 2 Duo        | 25        | 5.48%   |
| Other                   | 14        | 3.07%   |
| Intel Atom              | 11        | 2.41%   |
| AMD Ryzen 7             | 10        | 2.19%   |
| AMD E                   | 7         | 1.54%   |
| Intel Pentium           | 5         | 1.1%    |
| Intel Core i9           | 4         | 0.88%   |
| AMD A4                  | 4         | 0.88%   |
| Intel Genuine           | 3         | 0.66%   |
| AMD Ryzen 5             | 3         | 0.66%   |
| Intel Pentium Dual-Core | 2         | 0.44%   |
| Intel Pentium Dual      | 2         | 0.44%   |
| Intel Core Duo          | 2         | 0.44%   |
| Intel Core 2            | 2         | 0.44%   |
| AMD E2                  | 2         | 0.44%   |
| AMD E1                  | 2         | 0.44%   |
| AMD A6                  | 2         | 0.44%   |
| Intel Celeron M         | 1         | 0.22%   |
| Intel Celeron Dual-Core | 1         | 0.22%   |
| AMD Turion II Dual-Core | 1         | 0.22%   |
| AMD Turion 64 Mobile    | 1         | 0.22%   |
| AMD Ryzen 9             | 1         | 0.22%   |
| AMD Ryzen 7 PRO         | 1         | 0.22%   |
| AMD Ryzen 3             | 1         | 0.22%   |
| AMD FX                  | 1         | 0.22%   |
| AMD Athlon X2           | 1         | 0.22%   |
| AMD Athlon II           | 1         | 0.22%   |
| AMD Athlon 64 X2        | 1         | 0.22%   |
| AMD A10                 | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 278       | 60.96%  |
| 4      | 129       | 28.29%  |
| 6      | 20        | 4.39%   |
| 8      | 17        | 3.73%   |
| 1      | 12        | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 456       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 340       | 74.56%  |
| 1      | 116       | 25.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 446       | 97.38%  |
| 32-bit         | 6         | 1.31%   |
| Unknown        | 6         | 1.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 114       | 23.9%   |
| 0x206a7    | 43        | 9.01%   |
| 0x406e3    | 26        | 5.45%   |
| 0x806e9    | 25        | 5.24%   |
| 0x306a9    | 24        | 5.03%   |
| 0x20655    | 20        | 4.19%   |
| 0x1067a    | 16        | 3.35%   |
| 0x806ea    | 15        | 3.14%   |
| 0x906ea    | 14        | 2.94%   |
| 0x806ec    | 14        | 2.94%   |
| 0x406c4    | 13        | 2.73%   |
| 0x306d4    | 13        | 2.73%   |
| 0x306c3    | 13        | 2.73%   |
| 0x40651    | 11        | 2.31%   |
| 0x906e9    | 10        | 2.1%    |
| 0x806c1    | 8         | 1.68%   |
| 0x506e3    | 7         | 1.47%   |
| 0x06006705 | 7         | 1.47%   |
| 0x6fd      | 6         | 1.26%   |
| 0x406c3    | 6         | 1.26%   |
| 0xa0652    | 5         | 1.05%   |
| 0x20652    | 5         | 1.05%   |
| 0x806eb    | 4         | 0.84%   |
| 0x706e5    | 4         | 0.84%   |
| 0x506c9    | 4         | 0.84%   |
| 0x10676    | 4         | 0.84%   |
| 0x10661    | 4         | 0.84%   |
| 0x906ed    | 3         | 0.63%   |
| 0x706a1    | 3         | 0.63%   |
| 0x05000119 | 3         | 0.63%   |
| 0x6f6      | 2         | 0.42%   |
| 0x6ec      | 2         | 0.42%   |
| 0x30678    | 2         | 0.42%   |
| 0x30661    | 2         | 0.42%   |
| 0x106e5    | 2         | 0.42%   |
| 0x106c2    | 2         | 0.42%   |
| 0x0a50000c | 2         | 0.42%   |
| 0x08600106 | 2         | 0.42%   |
| 0x08108109 | 2         | 0.42%   |
| 0x0700010f | 2         | 0.42%   |
| 0x806d1    | 1         | 0.21%   |
| 0x6e8      | 1         | 0.21%   |
| 0x106ca    | 1         | 0.21%   |
| 0x08608102 | 1         | 0.21%   |
| 0x08600102 | 1         | 0.21%   |
| 0x08108102 | 1         | 0.21%   |
| 0x08101007 | 1         | 0.21%   |
| 0x06006704 | 1         | 0.21%   |
| 0x0600611a | 1         | 0.21%   |
| 0x06003106 | 1         | 0.21%   |
| 0x05000029 | 1         | 0.21%   |
| 0x02000057 | 1         | 0.21%   |
| 0x010000c8 | 1         | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 104       | 22.81%  |
| SandyBridge     | 53        | 11.62%  |
| Skylake         | 36        | 7.89%   |
| Westmere        | 32        | 7.02%   |
| IvyBridge       | 32        | 7.02%   |
| Haswell         | 32        | 7.02%   |
| Penryn          | 26        | 5.7%    |
| Silvermont      | 23        | 5.04%   |
| Broadwell       | 17        | 3.73%   |
| Core            | 15        | 3.29%   |
| TigerLake       | 12        | 2.63%   |
| IceLake         | 9         | 1.97%   |
| Excavator       | 9         | 1.97%   |
| Bobcat          | 8         | 1.75%   |
| Zen 3           | 5         | 1.1%    |
| Zen 2           | 5         | 1.1%    |
| Goldmont        | 5         | 1.1%    |
| CometLake       | 5         | 1.1%    |
| Bonnell         | 5         | 1.1%    |
| Zen+            | 4         | 0.88%   |
| Goldmont plus   | 4         | 0.88%   |
| P6              | 3         | 0.66%   |
| Nehalem         | 2         | 0.44%   |
| K8 Hammer       | 2         | 0.44%   |
| K10             | 2         | 0.44%   |
| Jaguar          | 2         | 0.44%   |
| Zen             | 1         | 0.22%   |
| Steamroller     | 1         | 0.22%   |
| K8 & K10 hybrid | 1         | 0.22%   |
| Unknown         | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 383       | 66.96%  |
| Nvidia                           | 107       | 18.71%  |
| AMD                              | 81        | 14.16%  |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 48        | 8.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 30        | 5.07%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 4.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 26        | 4.39%   |
| Intel HD Graphics 620                                                                    | 25        | 4.22%   |
| Intel UHD Graphics 620                                                                   | 22        | 3.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 3.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 19        | 3.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 2.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 2.87%   |
| Intel HD Graphics 5500                                                                   | 17        | 2.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 2.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 2.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 2.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 1.69%   |
| Intel HD Graphics 630                                                                    | 10        | 1.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 1.18%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 1.18%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 1.01%   |
| Nvidia GM108M [GeForce MX130]                                                            | 6         | 1.01%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 1.01%   |
| Intel HD Graphics 530                                                                    | 6         | 1.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.84%   |
| Intel HD Graphics 500                                                                    | 5         | 0.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 0.84%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 5         | 0.84%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 0.84%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 0.84%   |
| AMD Renoir                                                                               | 5         | 0.84%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.68%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 0.68%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 4         | 0.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.68%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 4         | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.51%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.51%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.51%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.51%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 3         | 0.51%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.51%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 3         | 0.51%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 0.51%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.51%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 3         | 0.51%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 3         | 0.51%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 0.51%   |
| AMD Cezanne                                                                              | 3         | 0.51%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 0.34%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.34%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.34%   |
| Nvidia GT218M [NVS 3100M]                                                                | 2         | 0.34%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 2         | 0.34%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.34%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.34%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 270       | 59.08%  |
| Intel + Nvidia | 81        | 17.72%  |
| 1 x AMD        | 44        | 9.63%   |
| Intel + AMD    | 31        | 6.78%   |
| 1 x Nvidia     | 23        | 5.03%   |
| 2 x AMD        | 3         | 0.66%   |
| AMD + Nvidia   | 3         | 0.66%   |
| 2 x Intel      | 1         | 0.22%   |
| 1 x SiS        | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 391       | 84.82%  |
| Proprietary | 61        | 13.23%  |
| Unknown     | 9         | 1.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 322       | 67.93%  |
| 1.01-2.0   | 58        | 12.24%  |
| 0.01-0.5   | 36        | 7.59%   |
| 3.01-4.0   | 22        | 4.64%   |
| 0.51-1.0   | 18        | 3.8%    |
| 5.01-6.0   | 11        | 2.32%   |
| 2.01-3.0   | 4         | 0.84%   |
| 7.01-8.0   | 3         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 99        | 18.1%   |
| LG Display              | 83        | 15.17%  |
| BOE                     | 78        | 14.26%  |
| Chimei Innolux          | 64        | 11.7%   |
| Samsung Electronics     | 60        | 10.97%  |
| Dell                    | 41        | 7.5%    |
| Chi Mei Optoelectronics | 22        | 4.02%   |
| Goldstar                | 18        | 3.29%   |
| Apple                   | 13        | 2.38%   |
| Lenovo                  | 11        | 2.01%   |
| Sharp                   | 10        | 1.83%   |
| LG Philips              | 7         | 1.28%   |
| Philips                 | 4         | 0.73%   |
| Hewlett-Packard         | 4         | 0.73%   |
| Toshiba                 | 3         | 0.55%   |
| Fujitsu Siemens         | 3         | 0.55%   |
| AOC                     | 3         | 0.55%   |
| SKY                     | 2         | 0.37%   |
| Quanta Display          | 2         | 0.37%   |
| VST                     | 1         | 0.18%   |
| VIE                     | 1         | 0.18%   |
| Tatung                  | 1         | 0.18%   |
| Sony                    | 1         | 0.18%   |
| SLD                     | 1         | 0.18%   |
| SKK                     | 1         | 0.18%   |
| SEEYOO                  | 1         | 0.18%   |
| PANDA                   | 1         | 0.18%   |
| Panasonic               | 1         | 0.18%   |
| MStar                   | 1         | 0.18%   |
| Microsoft               | 1         | 0.18%   |
| LTM                     | 1         | 0.18%   |
| InnoLux Display         | 1         | 0.18%   |
| InfoVision              | 1         | 0.18%   |
| HKC                     | 1         | 0.18%   |
| HannStar                | 1         | 0.18%   |
| Eizo                    | 1         | 0.18%   |
| Daewoo                  | 1         | 0.18%   |
| CMN                     | 1         | 0.18%   |
| Acer                    | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 1.61%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 9         | 1.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 1.07%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 5         | 0.89%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 5         | 0.89%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 5         | 0.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.89%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 4         | 0.71%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 4         | 0.71%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.71%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 4         | 0.71%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                      | 4         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.54%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 3         | 0.54%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 3         | 0.54%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 3         | 0.54%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 3         | 0.54%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch              | 3         | 0.54%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 3         | 0.54%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                  | 3         | 0.54%   |
| Goldstar W2343 GSM5700 1920x1080 474x296mm 22.0-inch                     | 3         | 0.54%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 3         | 0.54%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                       | 3         | 0.54%   |
| Dell S3220DGF DELD0F2 2560x1440 697x392mm 31.5-inch                      | 3         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 3         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 3         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 3         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch          | 3         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 3         | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 3         | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 3         | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.54%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                     | 3         | 0.54%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 3         | 0.54%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 3         | 0.54%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.54%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.54%   |
| Apple Color LCD APPA044 3072x1920 345x215mm 16.0-inch                    | 3         | 0.54%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 3         | 0.54%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch        | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch     | 2         | 0.36%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.36%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.36%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 0.36%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.36%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 2         | 0.36%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch              | 2         | 0.36%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch              | 2         | 0.36%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 2         | 0.36%   |
| Dell SE2419H DELF109 1920x1080 527x296mm 23.8-inch                       | 2         | 0.36%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                       | 2         | 0.36%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                       | 2         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 213       | 41.52%  |
| 1920x1080 (FHD)    | 168       | 32.75%  |
| 1280x800 (WXGA)    | 31        | 6.04%   |
| 1600x900 (HD+)     | 28        | 5.46%   |
| 2560x1440 (QHD)    | 11        | 2.14%   |
| 1440x900 (WXGA+)   | 10        | 1.95%   |
| 1920x1200 (WUXGA)  | 9         | 1.75%   |
| 3840x2160 (4K)     | 8         | 1.56%   |
| 1680x1050 (WSXGA+) | 6         | 1.17%   |
| 1280x1024 (SXGA)   | 6         | 1.17%   |
| 3072x1920          | 3         | 0.58%   |
| 2560x1080          | 3         | 0.58%   |
| 1360x768           | 3         | 0.58%   |
| 1024x768 (XGA)     | 3         | 0.58%   |
| 1024x600           | 3         | 0.58%   |
| 3840x1080          | 1         | 0.19%   |
| 2880x1920          | 1         | 0.19%   |
| 2880x1800          | 1         | 0.19%   |
| 2288x1287          | 1         | 0.19%   |
| 1x1                | 1         | 0.19%   |
| 1920x540           | 1         | 0.19%   |
| 1680x945           | 1         | 0.19%   |
| 1600x1200          | 1         | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 291       | 52.53%  |
| 13      | 49        | 8.84%   |
| 14      | 40        | 7.22%   |
| 17      | 39        | 7.04%   |
| 23      | 23        | 4.15%   |
| 24      | 22        | 3.97%   |
| 27      | 11        | 1.99%   |
| 21      | 11        | 1.99%   |
| 31      | 8         | 1.44%   |
| 12      | 8         | 1.44%   |
| 20      | 6         | 1.08%   |
| 18      | 6         | 1.08%   |
| Unknown | 6         | 1.08%   |
| 22      | 5         | 0.9%    |
| 19      | 4         | 0.72%   |
| 40      | 3         | 0.54%   |
| 34      | 3         | 0.54%   |
| 16      | 3         | 0.54%   |
| 10      | 3         | 0.54%   |
| 72      | 2         | 0.36%   |
| 54      | 2         | 0.36%   |
| 26      | 2         | 0.36%   |
| 11      | 2         | 0.36%   |
| 52      | 1         | 0.18%   |
| 48      | 1         | 0.18%   |
| 39      | 1         | 0.18%   |
| 32      | 1         | 0.18%   |
| 8       | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 356       | 64.85%  |
| 501-600     | 52        | 9.47%   |
| 351-400     | 41        | 7.47%   |
| 201-300     | 37        | 6.74%   |
| 401-500     | 32        | 5.83%   |
| 601-700     | 9         | 1.64%   |
| Unknown     | 6         | 1.09%   |
| 801-900     | 4         | 0.73%   |
| 701-800     | 4         | 0.73%   |
| 1001-1500   | 4         | 0.73%   |
| 1501-2000   | 2         | 0.36%   |
| 101-200     | 1         | 0.18%   |
| 1-100       | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 392       | 83.76%  |
| 16/10   | 57        | 12.18%  |
| 4/3     | 6         | 1.28%   |
| 5/4     | 3         | 0.64%   |
| 3/2     | 3         | 0.64%   |
| 21/9    | 3         | 0.64%   |
| 32/9    | 2         | 0.43%   |
| 0.00    | 1         | 0.21%   |
| Unknown | 1         | 0.21%   |

Monitor Area
------------

Area in inch??

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch?? | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 290       | 52.63%  |
| 81-90          | 70        | 12.7%   |
| 201-250        | 53        | 9.62%   |
| 121-130        | 33        | 5.99%   |
| 71-80          | 19        | 3.45%   |
| 151-200        | 13        | 2.36%   |
| 351-500        | 12        | 2.18%   |
| 301-350        | 12        | 2.18%   |
| 141-150        | 9         | 1.63%   |
| 61-70          | 8         | 1.45%   |
| Unknown        | 7         | 1.27%   |
| More than 1000 | 5         | 0.91%   |
| 501-1000       | 5         | 0.91%   |
| 251-300        | 4         | 0.73%   |
| 111-120        | 3         | 0.54%   |
| 51-60          | 2         | 0.36%   |
| 41-50          | 2         | 0.36%   |
| 131-140        | 2         | 0.36%   |
| 1-40           | 1         | 0.18%   |
| 91-100         | 1         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 229       | 42.72%  |
| 121-160       | 153       | 28.54%  |
| 51-100        | 117       | 21.83%  |
| 161-240       | 17        | 3.17%   |
| 1-50          | 9         | 1.68%   |
| Unknown       | 6         | 1.12%   |
| More than 240 | 5         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 348       | 73.73%  |
| 2     | 106       | 22.46%  |
| 3     | 12        | 2.54%   |
| 0     | 6         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 259       | 33.12%  |
| Intel                             | 219       | 28.01%  |
| Qualcomm Atheros                  | 125       | 15.98%  |
| Broadcom                          | 55        | 7.03%   |
| Dell                              | 17        | 2.17%   |
| Ralink                            | 12        | 1.53%   |
| Huawei Technologies               | 12        | 1.53%   |
| Broadcom Limited                  | 12        | 1.53%   |
| Marvell Technology Group          | 11        | 1.41%   |
| Samsung Electronics               | 10        | 1.28%   |
| Ericsson Business Mobile Networks | 6         | 0.77%   |
| JMicron Technology                | 5         | 0.64%   |
| MediaTek                          | 4         | 0.51%   |
| TP-Link                           | 3         | 0.38%   |
| Sierra Wireless                   | 3         | 0.38%   |
| Hewlett-Packard                   | 3         | 0.38%   |
| ASIX Electronics                  | 3         | 0.38%   |
| Apple                             | 3         | 0.38%   |
| Spreadtrum Communications         | 2         | 0.26%   |
| Lenovo                            | 2         | 0.26%   |
| ZyXEL Communications              | 1         | 0.13%   |
| Xiaomi                            | 1         | 0.13%   |
| TRENDnet                          | 1         | 0.13%   |
| Toshiba                           | 1         | 0.13%   |
| Texas Instruments                 | 1         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.13%   |
| Ralink Technology                 | 1         | 0.13%   |
| Qualcomm Atheros Communications   | 1         | 0.13%   |
| Nvidia                            | 1         | 0.13%   |
| HMD Global                        | 1         | 0.13%   |
| Fibocom                           | 1         | 0.13%   |
| Exar                              | 1         | 0.13%   |
| DisplayLink                       | 1         | 0.13%   |
| Attansic Technology               | 1         | 0.13%   |
| ASUSTek Computer                  | 1         | 0.13%   |
| Arduino SA                        | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 155       | 16.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 70        | 7.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 25        | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 25        | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 23        | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 17        | 1.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 1.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 14        | 1.49%   |
| Intel Wireless 8265 / 8275                                              | 14        | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.39%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 1.28%   |
| Intel Centrino Advanced-N 6200                                          | 12        | 1.28%   |
| Intel 82577LM Gigabit Network Connection                                | 12        | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 1.17%   |
| Intel Wireless 8260                                                     | 11        | 1.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 1.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 1.07%   |
| Intel Wireless 3165                                                     | 10        | 1.07%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.07%   |
| Intel Wireless 3160                                                     | 9         | 0.96%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 9         | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 0.85%   |
| Intel Wireless 7265                                                     | 8         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 0.75%   |
| Intel WiFi Link 5100                                                    | 7         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.75%   |
| Intel Ethernet Connection I219-LM                                       | 7         | 0.75%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                                | 7         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 7         | 0.75%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 6         | 0.64%   |
| Intel Wireless 7260                                                     | 6         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                                   | 6         | 0.64%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.64%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.53%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 5         | 0.53%   |
| Intel Ultimate N WiFi Link 5300                                         | 5         | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 0.53%   |
| Dell DW5811e Snapdragon?????? X7 LTE                                    | 5         | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 5         | 0.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 4         | 0.43%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 4         | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 4         | 0.43%   |
| Intel Ethernet Connection I218-LM                                       | 4         | 0.43%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.43%   |
| Intel 82579V Gigabit Network Connection                                 | 4         | 0.43%   |
| Dell Hub of E-Port Replicator                                           | 4         | 0.43%   |
| Dell F3607gw v2 Mobile Broadband Module                                 | 4         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 211       | 44.99%  |
| Qualcomm Atheros                | 113       | 24.09%  |
| Realtek Semiconductor           | 61        | 13.01%  |
| Broadcom                        | 42        | 8.96%   |
| Ralink                          | 12        | 2.56%   |
| Dell                            | 9         | 1.92%   |
| Broadcom Limited                | 6         | 1.28%   |
| TP-Link                         | 3         | 0.64%   |
| Sierra Wireless                 | 3         | 0.64%   |
| MediaTek                        | 3         | 0.64%   |
| ZyXEL Communications            | 1         | 0.21%   |
| TRENDnet                        | 1         | 0.21%   |
| Ralink Technology               | 1         | 0.21%   |
| Qualcomm Atheros Communications | 1         | 0.21%   |
| Fibocom                         | 1         | 0.21%   |
| ASUSTek Computer                | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 25        | 5.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 25        | 5.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 23        | 4.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 4.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 3.39%   |
| Intel Wireless 8265 / 8275                                              | 14        | 2.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 2.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 2.75%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 2.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 2.54%   |
| Intel Centrino Advanced-N 6200                                          | 12        | 2.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 2.33%   |
| Intel Wireless 8260                                                     | 11        | 2.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 2.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 2.12%   |
| Intel Wireless 3165                                                     | 10        | 2.12%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 2.12%   |
| Intel Wireless 3160                                                     | 9         | 1.91%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 9         | 1.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 1.69%   |
| Intel Wireless 7265                                                     | 8         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.48%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 1.48%   |
| Intel WiFi Link 5100                                                    | 7         | 1.48%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 1.48%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.48%   |
| Intel Wireless 7260                                                     | 6         | 1.27%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 1.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.06%   |
| Intel Ultimate N WiFi Link 5300                                         | 5         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.06%   |
| Dell DW5811e Snapdragon?????? X7 LTE                                    | 5         | 1.06%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 1.06%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.85%   |
| Dell Hub of E-Port Replicator                                           | 4         | 0.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.85%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 0.85%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 3         | 0.64%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.64%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 0.64%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 3         | 0.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.64%   |
| Sierra Wireless EM7455                                                  | 2         | 0.42%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 2         | 0.42%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.42%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 2         | 0.42%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.42%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 2         | 0.42%   |
| ZyXEL NWD-270N Wireless N-lite USB Adapter                              | 1         | 0.21%   |
| TRENDnet 802.11n WLAN Adapter                                           | 1         | 0.21%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.21%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 244       | 55.96%  |
| Intel                            | 91        | 20.87%  |
| Broadcom                         | 24        | 5.5%    |
| Qualcomm Atheros                 | 22        | 5.05%   |
| Marvell Technology Group         | 11        | 2.52%   |
| Samsung Electronics              | 10        | 2.29%   |
| Broadcom Limited                 | 7         | 1.61%   |
| JMicron Technology               | 5         | 1.15%   |
| Huawei Technologies              | 5         | 1.15%   |
| ASIX Electronics                 | 3         | 0.69%   |
| Apple                            | 3         | 0.69%   |
| Spreadtrum Communications        | 2         | 0.46%   |
| Lenovo                           | 2         | 0.46%   |
| Xiaomi                           | 1         | 0.23%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| Nvidia                           | 1         | 0.23%   |
| MediaTek                         | 1         | 0.23%   |
| HMD Global                       | 1         | 0.23%   |
| DisplayLink                      | 1         | 0.23%   |
| Attansic Technology              | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 155       | 35.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 70        | 15.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 17        | 3.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 14        | 3.2%    |
| Intel 82577LM Gigabit Network Connection                                       | 12        | 2.74%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 1.6%    |
| Intel 82567LM Gigabit Network Connection                                       | 7         | 1.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 7         | 1.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 6         | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.14%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 5         | 1.14%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 1.14%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 0.91%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 0.91%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 4         | 0.91%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 0.91%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 0.91%   |
| Intel 82579V Gigabit Network Connection                                        | 4         | 0.91%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.68%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.68%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile           | 3         | 0.68%   |
| Huawei E353/E3131                                                              | 3         | 0.68%   |
| Apple iBridge                                                                  | 3         | 0.68%   |
| Spreadtrum Unisoc Phone                                                        | 2         | 0.46%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.46%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.46%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.46%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.46%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.46%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.46%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.46%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 2         | 0.46%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                            | 2         | 0.46%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.46%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.23%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.23%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.23%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.23%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.23%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.23%   |
| MediaTek TECNO SPARK 3                                                         | 1         | 0.23%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.23%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.23%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.23%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.23%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 1         | 0.23%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 445       | 50.51%  |
| Ethernet | 409       | 46.42%  |
| Modem    | 27        | 3.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 373       | 75.05%  |
| Ethernet | 123       | 24.75%  |
| Modem    | 1         | 0.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 388       | 85.09%  |
| 1     | 54        | 11.84%  |
| 0     | 12        | 2.63%   |
| 3     | 2         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 447       | 98.03%  |
| Yes  | 9         | 1.97%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 139       | 37.98%  |
| Qualcomm Atheros Communications | 51        | 13.93%  |
| Realtek Semiconductor           | 37        | 10.11%  |
| Broadcom                        | 22        | 6.01%   |
| Foxconn / Hon Hai               | 19        | 5.19%   |
| Lite-On Technology              | 18        | 4.92%   |
| Hewlett-Packard                 | 18        | 4.92%   |
| IMC Networks                    | 15        | 4.1%    |
| Dell                            | 13        | 3.55%   |
| Ralink                          | 10        | 2.73%   |
| Apple                           | 8         | 2.19%   |
| Toshiba                         | 7         | 1.91%   |
| Cambridge Silicon Radio         | 4         | 1.09%   |
| ASUSTek Computer                | 3         | 0.82%   |
| Realtek                         | 1         | 0.27%   |
| Foxconn International           | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 61        | 16.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 24        | 6.56%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 20        | 5.46%   |
| Realtek Bluetooth Radio                                                             | 19        | 5.19%   |
| Intel Bluetooth Device                                                              | 19        | 5.19%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 15        | 4.1%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 12        | 3.28%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 11        | 3.01%   |
| Intel AX200 Bluetooth                                                               | 11        | 3.01%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 11        | 3.01%   |
| Ralink RT3290 Bluetooth                                                             | 10        | 2.73%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 2.73%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 9         | 2.46%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 8         | 2.19%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 1.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 7         | 1.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 1.64%   |
| Lite-On Bluetooth Device                                                            | 6         | 1.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 6         | 1.64%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 1.37%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.37%   |
| IMC Networks Bluetooth Device                                                       | 5         | 1.37%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 4         | 1.09%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.09%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 4         | 1.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 1.09%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 1.09%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.82%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 3         | 0.82%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 3         | 0.82%   |
| Toshiba RT Bluetooth Radio                                                          | 2         | 0.55%   |
| Toshiba Askey Bluetooth Module                                                      | 2         | 0.55%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.55%   |
| IMC Networks Bluetooth USB Host Controller                                          | 2         | 0.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.55%   |
| Foxconn / Hon Hai BT                                                                | 2         | 0.55%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 2         | 0.55%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.55%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.55%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.55%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.55%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 2         | 0.55%   |
| Apple Bluetooth Host Controller                                                     | 2         | 0.55%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.55%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.27%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.27%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 1         | 0.27%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.27%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.27%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.27%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.27%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.27%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.27%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.27%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.27%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.27%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.27%   |
| Broadcom Bluetooth Device                                                           | 1         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 404       | 74.26%  |
| Nvidia                           | 53        | 9.74%   |
| AMD                              | 53        | 9.74%   |
| Logitech                         | 5         | 0.92%   |
| C-Media Electronics              | 4         | 0.74%   |
| Lenovo                           | 3         | 0.55%   |
| Apple                            | 3         | 0.55%   |
| Realtek Semiconductor            | 2         | 0.37%   |
| Xiaomi                           | 1         | 0.18%   |
| Tenx Technology                  | 1         | 0.18%   |
| Syntek                           | 1         | 0.18%   |
| Steinberg Soft-und Hardware      | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Schiit Audio                     | 1         | 0.18%   |
| Magic Control Technology         | 1         | 0.18%   |
| M-Audio                          | 1         | 0.18%   |
| JMTek                            | 1         | 0.18%   |
| Hewlett-Packard                  | 1         | 0.18%   |
| GN Netcom                        | 1         | 0.18%   |
| Focusrite-Novation               | 1         | 0.18%   |
| Creative Technology              | 1         | 0.18%   |
| Corsair                          | 1         | 0.18%   |
| Cooler Master                    | 1         | 0.18%   |
| Conexant Systems                 | 1         | 0.18%   |
| Afatech                          | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 76        | 12.1%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 44        | 7.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 41        | 6.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 34        | 5.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 23        | 3.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 20        | 3.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 2.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 2.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 17        | 2.71%   |
| Intel Broadwell-U Audio Controller                                                                | 17        | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 2.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 2.55%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 2.55%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 2.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 2.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 1.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 1.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 1.59%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.43%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 1.27%   |
| AMD High Definition Audio Controller                                                              | 8         | 1.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 1.27%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 1.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.8%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 0.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 0.8%    |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.8%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 0.64%   |
| AMD Navi 10 HDMI Audio                                                                            | 4         | 0.64%   |
| AMD FCH Azalia Controller                                                                         | 4         | 0.64%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.48%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.48%   |
| C-Media Electronics USB Audio Device                                                              | 3         | 0.48%   |
| Apple Audio Device                                                                                | 3         | 0.48%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.48%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.48%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.32%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.32%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.32%   |
| Nvidia stereo controller                                                                          | 2         | 0.32%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.32%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.32%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.32%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 2         | 0.32%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.32%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.32%   |
| Xiaomi Mi Dual Driver Earphones Type-C                                                            | 1         | 0.16%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.16%   |
| Syntek STK1160 Video Capture Device                                                               | 1         | 0.16%   |
| Steinberg Soft-und Hardware MI4                                                                   | 1         | 0.16%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 76        | 30.28%  |
| Samsung Electronics | 58        | 23.11%  |
| Micron Technology   | 23        | 9.16%   |
| Kingston            | 23        | 9.16%   |
| Crucial             | 12        | 4.78%   |
| Unknown             | 11        | 4.38%   |
| Transcend           | 7         | 2.79%   |
| Ramaxel Technology  | 7         | 2.79%   |
| Elpida              | 7         | 2.79%   |
| Nanya Technology    | 6         | 2.39%   |
| A-DATA Technology   | 6         | 2.39%   |
| Corsair             | 5         | 1.99%   |
| G.Skill             | 3         | 1.2%    |
| Patriot             | 2         | 0.8%    |
| Essencore Limited   | 2         | 0.8%    |
| Unknown (ABCD)      | 1         | 0.4%    |
| Neo Forza           | 1         | 0.4%    |
| KLEVV               | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 8         | 3.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 6         | 2.32%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 5         | 1.93%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 5         | 1.93%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 5         | 1.93%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 1.54%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 4         | 1.54%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 3         | 1.16%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 3         | 1.16%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 1.16%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 1.16%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.16%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 1.16%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.16%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 3         | 1.16%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 3         | 1.16%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s               | 2         | 0.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.77%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 2         | 0.77%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s           | 2         | 0.77%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.77%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s             | 2         | 0.77%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 0.77%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 0.77%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.77%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.77%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.77%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.77%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.77%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4096MB SODIMM DDR3 1334MT/s             | 2         | 0.77%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s            | 2         | 0.77%   |
| Kingston RAM 9905700-026.A00G 8192MB SODIMM DDR4 2667MT/s           | 2         | 0.77%   |
| Kingston RAM 9905663-030.A00G 16GB SODIMM DDR4 2667MT/s             | 2         | 0.77%   |
| Kingston RAM 9905663-021.A00G 16GB SODIMM DDR4 2400MT/s             | 2         | 0.77%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s            | 2         | 0.77%   |
| Corsair RAM CMSX16GX4M1A2666C18 16GB SODIMM DDR4 2667MT/s           | 2         | 0.77%   |
| Corsair RAM CMSO8GX4M1A2133C15 8192MB SODIMM DDR4 2133MT/s          | 2         | 0.77%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                        | 1         | 0.39%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                         | 1         | 0.39%   |
| Unknown RAM Module 1GB SODIMM DDR2                                  | 1         | 0.39%   |
| Unknown RAM Module 16384MB 2133MT/s                                 | 1         | 0.39%   |
| Unknown RAM DDR4 NB 8G 2133 8GB SODIMM DDR4 2133MT/s                | 1         | 0.39%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.39%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s                | 1         | 0.39%   |
| Transcend RAM TS1GSK64W6H 8192MB SODIMM DDR3 1600MT/s               | 1         | 0.39%   |
| Transcend RAM TS1GSH64V4B 8192MB SODIMM DDR4 2400MT/s               | 1         | 0.39%   |
| Transcend RAM JM2666HSH-4G 4096MB Row Of Chips DDR4 2667MT/s        | 1         | 0.39%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s              | 1         | 0.39%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 3200MT/s                     | 1         | 0.39%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                     | 1         | 0.39%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                     | 1         | 0.39%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 1         | 0.39%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                        | 1         | 0.39%   |
| SK hynix RAM Module 2GB SODIMM DDR2 533MT/s                         | 1         | 0.39%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                     | 1         | 0.39%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                       | 1         | 0.39%   |
| SK hynix RAM Module 1GB SODIMM DDR2 533MT/s                         | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 85        | 46.7%   |
| DDR3    | 79        | 43.41%  |
| LPDDR4  | 9         | 4.95%   |
| DDR2    | 6         | 3.3%    |
| LPDDR3  | 2         | 1.1%    |
| Unknown | 1         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 173       | 93.51%  |
| Row Of Chips | 8         | 4.32%   |
| Chip         | 2         | 1.08%   |
| DIMM         | 1         | 0.54%   |
| Unknown      | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 73        | 35.1%   |
| 8192  | 62        | 29.81%  |
| 2048  | 38        | 18.27%  |
| 16384 | 26        | 12.5%   |
| 1024  | 5         | 2.4%    |
| 32768 | 3         | 1.44%   |
| 512   | 1         | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 59        | 28.1%   |
| 1600    | 51        | 24.29%  |
| 2400    | 19        | 9.05%   |
| 2133    | 16        | 7.62%   |
| 1334    | 16        | 7.62%   |
| 3200    | 14        | 6.67%   |
| 1333    | 11        | 5.24%   |
| 3266    | 6         | 2.86%   |
| 4267    | 3         | 1.43%   |
| 975     | 3         | 1.43%   |
| 667     | 3         | 1.43%   |
| 1067    | 2         | 0.95%   |
| 2933    | 1         | 0.48%   |
| 1867    | 1         | 0.48%   |
| 1776    | 1         | 0.48%   |
| 1066    | 1         | 0.48%   |
| 800     | 1         | 0.48%   |
| 533     | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Canon                 | 3         | 60%     |
| Lexmark International | 1         | 20%     |
| Hewlett-Packard       | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lexmark International InkJet Color Printer | 1         | 20%     |
| HP LaserJet 1022                           | 1         | 20%     |
| Canon PIXMA MG2500 Series                  | 1         | 20%     |
| Canon MF210 Series                         | 1         | 20%     |
| Canon G4000 series                         | 1         | 20%     |

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


| Vendor                                            | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Electronics                               | 79        | 18.94%  |
| Microdia                                          | 48        | 11.51%  |
| Realtek Semiconductor                             | 46        | 11.03%  |
| Acer                                              | 35        | 8.39%   |
| Sunplus Innovation Technology                     | 31        | 7.43%   |
| IMC Networks                                      | 31        | 7.43%   |
| Quanta                                            | 20        | 4.8%    |
| Cheng Uei Precision Industry (Foxlink)            | 18        | 4.32%   |
| Apple                                             | 15        | 3.6%    |
| Suyin                                             | 14        | 3.36%   |
| Lite-On Technology                                | 12        | 2.88%   |
| Syntek                                            | 11        | 2.64%   |
| Samsung Electronics                               | 10        | 2.4%    |
| Silicon Motion                                    | 6         | 1.44%   |
| Alcor Micro                                       | 6         | 1.44%   |
| Ricoh                                             | 5         | 1.2%    |
| Microsoft                                         | 4         | 0.96%   |
| Luxvisions Innotech Limited                       | 4         | 0.96%   |
| Z-Star Microelectronics                           | 3         | 0.72%   |
| Primax Electronics                                | 3         | 0.72%   |
| Lenovo                                            | 3         | 0.72%   |
| LG Electronics                                    | 2         | 0.48%   |
| Importek                                          | 2         | 0.48%   |
| GEMBIRD                                           | 2         | 0.48%   |
| Sunplus Technology                                | 1         | 0.24%   |
| STMicroelectronics Imaging Division (VLSI Vision) | 1         | 0.24%   |
| Spreadtrum Communications                         | 1         | 0.24%   |
| Logitech                                          | 1         | 0.24%   |
| icSpring                                          | 1         | 0.24%   |
| DigiTech                                          | 1         | 0.24%   |
| 8SSC20F27145V1SR1BX02P8                           | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                               | 22        | 5.28%   |
| Realtek Integrated_Webcam_HD                                | 15        | 3.6%    |
| Sunplus Integrated_Webcam_HD                                | 12        | 2.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 11        | 2.64%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 10        | 2.4%    |
| Microdia Integrated Webcam                                  | 8         | 1.92%   |
| Chicony HD Webcam                                           | 8         | 1.92%   |
| Acer Integrated Camera                                      | 8         | 1.92%   |
| Realtek Integrated Webcam HD                                | 6         | 1.44%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 1.44%   |
| IMC Networks Integrated Camera                              | 6         | 1.44%   |
| Chicony integrated camera                                   | 6         | 1.44%   |
| Chicony EasyCamera                                          | 6         | 1.44%   |
| Quanta VGA WebCam                                           | 5         | 1.2%    |
| Apple iPhone 5/5C/5S/6/SE                                   | 5         | 1.2%    |
| Apple FaceTime HD Camera                                    | 5         | 1.2%    |
| Acer Lenovo EasyCamera                                      | 5         | 1.2%    |
| Syntek EasyCamera                                           | 4         | 0.96%   |
| Sunplus HD WebCam                                           | 4         | 0.96%   |
| Realtek Integrated Webcam                                   | 4         | 0.96%   |
| Realtek HP Truevision HD                                    | 4         | 0.96%   |
| Quanta HP Webcam                                            | 4         | 0.96%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 4         | 0.96%   |
| Lite-On HP HD Camera                                        | 4         | 0.96%   |
| Chicony USB2.0 VGA UVC WebCam                               | 4         | 0.96%   |
| Chicony HP Webcam                                           | 4         | 0.96%   |
| Chicony HP TrueVision HD Camera                             | 4         | 0.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 4         | 0.96%   |
| Acer SunplusIT Integrated Camera                            | 4         | 0.96%   |
| Acer EasyCamera                                             | 4         | 0.96%   |
| Syntek Lenovo EasyCamera                                    | 3         | 0.72%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 3         | 0.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 0.72%   |
| Realtek USB2.0 VGA UVC WebCam                               | 3         | 0.72%   |
| Realtek HD Webcam - Realtek                                 | 3         | 0.72%   |
| Quanta HP HD Camera                                         | 3         | 0.72%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 3         | 0.72%   |
| Lenovo Integrated Webcam [R5U877]                           | 3         | 0.72%   |
| Chicony USB 2.0 Camera                                      | 3         | 0.72%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 3         | 0.72%   |
| Chicony Integrated HP HD Webcam                             | 3         | 0.72%   |
| Chicony HP Laptop Integrated Webcam [2 MP Fixed]            | 3         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 3         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 3         | 0.72%   |
| Apple FaceTime HD Camera (Built-in)                         | 3         | 0.72%   |
| Alcor Micro USB 2.0 Camera                                  | 3         | 0.72%   |
| Acer BisonCam, NB Pro                                       | 3         | 0.72%   |
| Syntek Integrated Camera                                    | 2         | 0.48%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 0.48%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 2         | 0.48%   |
| Silicon Motion WebCam SC-13HDL11939N                        | 2         | 0.48%   |
| Realtek Integrated Camera                                   | 2         | 0.48%   |
| Realtek Acer 640 x 480 laptop camera                        | 2         | 0.48%   |
| Quanta Laptop_Integrated_Webcam_2HDM                        | 2         | 0.48%   |
| Quanta HP Wide Vision HD Camera                             | 2         | 0.48%   |
| Quanta HP TrueVision HD Camera                              | 2         | 0.48%   |
| Microsoft LifeCam HD-3000                                   | 2         | 0.48%   |
| Microdia Sonix USB 2.0 Camera                               | 2         | 0.48%   |
| Microdia Laptop_Integrated_Webcam_2M                        | 2         | 0.48%   |
| Microdia Dell Integrated HD Webcam                          | 2         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 48        | 50%     |
| Upek                       | 12        | 12.5%   |
| Synaptics                  | 12        | 12.5%   |
| Shenzhen Goodix Technology | 9         | 9.38%   |
| AuthenTec                  | 8         | 8.33%   |
| LighTuning Technology      | 5         | 5.21%   |
| STMicroelectronics         | 1         | 1.04%   |
| Focal-systems.Corp         | 1         | 1.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 12        | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 11        | 11.46%  |
| Validity Sensors VFS5011 Fingerprint Reader                | 6         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 6         | 6.25%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 5         | 5.21%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 5         | 5.21%   |
| Shenzhen Goodix Fingerprint Reader                         | 4         | 4.17%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 3         | 3.13%   |
| Validity Sensors Fingerprint scanner                       | 3         | 3.13%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 3         | 3.13%   |
| Shenzhen Goodix FingerPrint                                | 3         | 3.13%   |
| AuthenTec AES2810                                          | 3         | 3.13%   |
| Validity Sensors VFS491                                    | 2         | 2.08%   |
| Validity Sensors Synaptics WBDI                            | 2         | 2.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 2         | 2.08%   |
| Shenzhen Goodix  FingerPrint Device                        | 2         | 2.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 2.08%   |
| AuthenTec Fingerprint Sensor                               | 2         | 2.08%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 2.08%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 1         | 1.04%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 1.04%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.04%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.04%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 1.04%   |
| Synaptics  WBDI                                            | 1         | 1.04%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 1.04%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 1.04%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.04%   |
| LighTuning Fingerprint Sensor                              | 1         | 1.04%   |
| LighTuning Fingerprint Reader                              | 1         | 1.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 1.04%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.04%   |
| AuthenTec AES1600                                          | 1         | 1.04%   |
| Unknown                                                    | 1         | 1.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 30        | 68.18%  |
| Lenovo      | 5         | 11.36%  |
| O2 Micro    | 4         | 9.09%   |
| Alcor Micro | 3         | 6.82%   |
| Upek        | 2         | 4.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 20.45%  |
| Broadcom 5880                                                                | 8         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 15.91%  |
| Broadcom 58200                                                               | 6         | 13.64%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 11.36%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 6.82%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 284       | 61.08%  |
| 1     | 143       | 30.75%  |
| 2     | 34        | 7.31%   |
| 3     | 3         | 0.65%   |
| 9     | 1         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 96        | 43.05%  |
| Chipcard                 | 41        | 18.39%  |
| Net/wireless             | 22        | 9.87%   |
| Graphics card            | 20        | 8.97%   |
| Bluetooth                | 13        | 5.83%   |
| Multimedia controller    | 9         | 4.04%   |
| Storage                  | 5         | 2.24%   |
| Camera                   | 5         | 2.24%   |
| Modem                    | 3         | 1.35%   |
| Communication controller | 3         | 1.35%   |
| Sound                    | 2         | 0.9%    |
| Card reader              | 2         | 0.9%    |
| Network                  | 1         | 0.45%   |
| Flash memory             | 1         | 0.45%   |

