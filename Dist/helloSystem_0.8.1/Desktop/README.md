helloSystem 0.8.1 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
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

Total: 125

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | PRIME B250M-A               | [270284972d](https://bsd-hardware.info/?probe=270284972d) | Apr 29, 2023 |
| Dell          | 0252PH A04                  | [f497e66dec](https://bsd-hardware.info/?probe=f497e66dec) | Apr 27, 2023 |
| HP            | 8056                        | [44fb168511](https://bsd-hardware.info/?probe=44fb168511) | Apr 26, 2023 |
| Dell          | 0VTC0D A02                  | [a807892254](https://bsd-hardware.info/?probe=a807892254) | Apr 19, 2023 |
| Acer          | Acadia V1.44                | [97bda17afa](https://bsd-hardware.info/?probe=97bda17afa) | Apr 19, 2023 |
| Gigabyte      | H61M-S2PH                   | [024173445b](https://bsd-hardware.info/?probe=024173445b) | Apr 18, 2023 |
| Gigabyte      | A520M DS3H AC               | [16021ac5b5](https://bsd-hardware.info/?probe=16021ac5b5) | Apr 17, 2023 |
| Pegatron      | 2A72h                       | [142340aed4](https://bsd-hardware.info/?probe=142340aed4) | Apr 15, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [8e77aee0e0](https://bsd-hardware.info/?probe=8e77aee0e0) | Apr 14, 2023 |
| HP            | 3397                        | [cf2d152bee](https://bsd-hardware.info/?probe=cf2d152bee) | Apr 13, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [e6c9c37b02](https://bsd-hardware.info/?probe=e6c9c37b02) | Apr 13, 2023 |
| Gigabyte      | H81M-S2PH                   | [b7ec959c9f](https://bsd-hardware.info/?probe=b7ec959c9f) | Apr 13, 2023 |
| ASUSTek       | PRIME B250M-A               | [0747d0a699](https://bsd-hardware.info/?probe=0747d0a699) | Apr 11, 2023 |
| Gigabyte      | M52L-S3P                    | [3a6baf7f2d](https://bsd-hardware.info/?probe=3a6baf7f2d) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3              | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
| Acer          | Veriton M6620G              | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| Lenovo        | Tilapia CRB                 | [977f089665](https://bsd-hardware.info/?probe=977f089665) | Apr 05, 2023 |
| Gigabyte      | B360M D2V                   | [6429eebbaa](https://bsd-hardware.info/?probe=6429eebbaa) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [92d0571176](https://bsd-hardware.info/?probe=92d0571176) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [096620cfac](https://bsd-hardware.info/?probe=096620cfac) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [760a744b91](https://bsd-hardware.info/?probe=760a744b91) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bcaaed4d6d](https://bsd-hardware.info/?probe=bcaaed4d6d) | Mar 31, 2023 |
| Gigabyte      | GA-880GM-USB3               | [a9bc1579c1](https://bsd-hardware.info/?probe=a9bc1579c1) | Mar 31, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [ca6badc637](https://bsd-hardware.info/?probe=ca6badc637) | Mar 30, 2023 |
| Gigabyte      | H81M-DS2V                   | [a69c208286](https://bsd-hardware.info/?probe=a69c208286) | Mar 30, 2023 |
| Dell          | 0T1D10 A01                  | [2f5592023f](https://bsd-hardware.info/?probe=2f5592023f) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | [6316b108be](https://bsd-hardware.info/?probe=6316b108be) | Mar 29, 2023 |
| BESSTAR Te... | UM700                       | [78ee14c1a5](https://bsd-hardware.info/?probe=78ee14c1a5) | Mar 28, 2023 |
| ASRock        | H61M-HVS                    | [98777ba333](https://bsd-hardware.info/?probe=98777ba333) | Mar 27, 2023 |
| MSI           | 870-G45                     | [19cbb6e0f3](https://bsd-hardware.info/?probe=19cbb6e0f3) | Mar 26, 2023 |
| Gigabyte      | F2A85X-UP4                  | [97d37b6e2f](https://bsd-hardware.info/?probe=97d37b6e2f) | Mar 25, 2023 |
| MSI           | 870-G45                     | [14e990c885](https://bsd-hardware.info/?probe=14e990c885) | Mar 25, 2023 |
| Gigabyte      | F2A85X-UP4                  | [c0b8eb494e](https://bsd-hardware.info/?probe=c0b8eb494e) | Mar 25, 2023 |
| ASUSTek       | P5K SE                      | [646eff3292](https://bsd-hardware.info/?probe=646eff3292) | Mar 25, 2023 |
| HP            | 8055                        | [03930fa6c3](https://bsd-hardware.info/?probe=03930fa6c3) | Mar 24, 2023 |
| HP            | 8350                        | [46dedb22a0](https://bsd-hardware.info/?probe=46dedb22a0) | Mar 24, 2023 |
| Unknown       | Unknown                     | [a66dffcb5c](https://bsd-hardware.info/?probe=a66dffcb5c) | Mar 23, 2023 |
| Intel         | DB85FL AAG89861-203         | [ff97717798](https://bsd-hardware.info/?probe=ff97717798) | Mar 23, 2023 |
| Gigabyte      | H81M-H                      | [e7cadcdae1](https://bsd-hardware.info/?probe=e7cadcdae1) | Mar 23, 2023 |
| Acer          | Revo 70                     | [50d93bea69](https://bsd-hardware.info/?probe=50d93bea69) | Mar 23, 2023 |
| Unknown       | T360D11                     | [d4d69405c5](https://bsd-hardware.info/?probe=d4d69405c5) | Mar 23, 2023 |
| T-bao         | MINI PC V1.0                | [eb2bc1cd51](https://bsd-hardware.info/?probe=eb2bc1cd51) | Mar 23, 2023 |
| Dell          | 0WWJRX A00                  | [b016b1fb3c](https://bsd-hardware.info/?probe=b016b1fb3c) | Mar 22, 2023 |
| Gigabyte      | F2A55-DS3                   | [ce8775fbe5](https://bsd-hardware.info/?probe=ce8775fbe5) | Mar 22, 2023 |
| Biostar       | H61MGC                      | [94e565457c](https://bsd-hardware.info/?probe=94e565457c) | Mar 22, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [c486bbb209](https://bsd-hardware.info/?probe=c486bbb209) | Mar 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [840a902d2b](https://bsd-hardware.info/?probe=840a902d2b) | Mar 22, 2023 |
| Foxconn       | M61PMV FAB                  | [197d75cbaa](https://bsd-hardware.info/?probe=197d75cbaa) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Intel         | X99                         | [a74c2b96ff](https://bsd-hardware.info/?probe=a74c2b96ff) | Mar 21, 2023 |
| Dell          | 0GM819                      | [9d5996dd7a](https://bsd-hardware.info/?probe=9d5996dd7a) | Mar 21, 2023 |
| HP            | 8054                        | [6e5a18f346](https://bsd-hardware.info/?probe=6e5a18f346) | Mar 20, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [33b600b436](https://bsd-hardware.info/?probe=33b600b436) | Mar 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [8d0e6be5da](https://bsd-hardware.info/?probe=8d0e6be5da) | Mar 20, 2023 |
| Dell          | 0GM819                      | [da7c02c542](https://bsd-hardware.info/?probe=da7c02c542) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c07b0a75e5](https://bsd-hardware.info/?probe=c07b0a75e5) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [71d2b7317c](https://bsd-hardware.info/?probe=71d2b7317c) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [36348fa16f](https://bsd-hardware.info/?probe=36348fa16f) | Mar 19, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [acc1970543](https://bsd-hardware.info/?probe=acc1970543) | Mar 18, 2023 |
| ASUSTek       | P6X58D-E                    | [ec05209185](https://bsd-hardware.info/?probe=ec05209185) | Mar 18, 2023 |
| Gigabyte      | H110M-H-CF                  | [29b3a70374](https://bsd-hardware.info/?probe=29b3a70374) | Mar 18, 2023 |
| Unknown       | Unknown                     | [dd8a64237a](https://bsd-hardware.info/?probe=dd8a64237a) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [74cf75116d](https://bsd-hardware.info/?probe=74cf75116d) | Mar 17, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [ebbd75883c](https://bsd-hardware.info/?probe=ebbd75883c) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | [7399558d80](https://bsd-hardware.info/?probe=7399558d80) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | [3fb2d0d992](https://bsd-hardware.info/?probe=3fb2d0d992) | Mar 17, 2023 |
| HP            | 1632                        | [8f3bb99bb4](https://bsd-hardware.info/?probe=8f3bb99bb4) | Mar 17, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [da2b96de55](https://bsd-hardware.info/?probe=da2b96de55) | Mar 16, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [0bae1528b9](https://bsd-hardware.info/?probe=0bae1528b9) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [eb6b70b310](https://bsd-hardware.info/?probe=eb6b70b310) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [f14a448799](https://bsd-hardware.info/?probe=f14a448799) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [44c7f21a07](https://bsd-hardware.info/?probe=44c7f21a07) | Mar 16, 2023 |
| Gigabyte      | B450M S2H                   | [dfa4f43317](https://bsd-hardware.info/?probe=dfa4f43317) | Mar 15, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [864a4017cb](https://bsd-hardware.info/?probe=864a4017cb) | Mar 15, 2023 |
| HP            | 3398                        | [b14de43688](https://bsd-hardware.info/?probe=b14de43688) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [c4798050c6](https://bsd-hardware.info/?probe=c4798050c6) | Mar 15, 2023 |
| ASUSTek       | Pro B550M-C                 | [a0e38ad11b](https://bsd-hardware.info/?probe=a0e38ad11b) | Mar 14, 2023 |
| Dell          | 00V62H A00                  | [ecb9b5d004](https://bsd-hardware.info/?probe=ecb9b5d004) | Mar 14, 2023 |
| Foxconn       | H61M/H61M-S                 | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [34c4bab715](https://bsd-hardware.info/?probe=34c4bab715) | Mar 14, 2023 |
| MSI           | 0A48                        | [815f019a8c](https://bsd-hardware.info/?probe=815f019a8c) | Mar 14, 2023 |
| Lenovo        | NO DPK                      | [8a38ed8d33](https://bsd-hardware.info/?probe=8a38ed8d33) | Mar 14, 2023 |
| ASUSTek       | B85M-G                      | [6401dd52d2](https://bsd-hardware.info/?probe=6401dd52d2) | Mar 14, 2023 |
| AZW           | U59                         | [5a6ef3fb8d](https://bsd-hardware.info/?probe=5a6ef3fb8d) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58p 6138DK1    | [293de8b0fd](https://bsd-hardware.info/?probe=293de8b0fd) | Mar 14, 2023 |
| Google        | Panther                     | [3577da7e53](https://bsd-hardware.info/?probe=3577da7e53) | Mar 13, 2023 |
| Dell          | 01TN68 A02                  | [cb6c76df00](https://bsd-hardware.info/?probe=cb6c76df00) | Mar 13, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [b337baf50e](https://bsd-hardware.info/?probe=b337baf50e) | Mar 13, 2023 |
| Gigabyte      | B365M H                     | [7acb7cb65f](https://bsd-hardware.info/?probe=7acb7cb65f) | Mar 13, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [e96ecce822](https://bsd-hardware.info/?probe=e96ecce822) | Mar 13, 2023 |
| HP            | 8056                        | [164b3e5c3f](https://bsd-hardware.info/?probe=164b3e5c3f) | Mar 13, 2023 |
| T-bao         | MINI PC                     | [d4440566b0](https://bsd-hardware.info/?probe=d4440566b0) | Mar 13, 2023 |
| Gigabyte      | G31M-S2L                    | [d210b12607](https://bsd-hardware.info/?probe=d210b12607) | Mar 13, 2023 |
| Gigabyte      | H110M-S2-CF                 | [6afb777789](https://bsd-hardware.info/?probe=6afb777789) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [0eeb0661dd](https://bsd-hardware.info/?probe=0eeb0661dd) | Mar 12, 2023 |
| Dell          | 0WMJ54 A01                  | [7949f20162](https://bsd-hardware.info/?probe=7949f20162) | Mar 12, 2023 |
| MSI           | B450-A PRO                  | [b2d29a5bbc](https://bsd-hardware.info/?probe=b2d29a5bbc) | Mar 12, 2023 |
| Gigabyte      | H61M-DS2 x.x                | [a39b128f44](https://bsd-hardware.info/?probe=a39b128f44) | Mar 12, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [34afe9e044](https://bsd-hardware.info/?probe=34afe9e044) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | [aebf680e82](https://bsd-hardware.info/?probe=aebf680e82) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | [6c50fda85b](https://bsd-hardware.info/?probe=6c50fda85b) | Mar 12, 2023 |
| ASUSTek       | A8N-E                       | [5fc3d86bac](https://bsd-hardware.info/?probe=5fc3d86bac) | Mar 12, 2023 |
| MSI           | H61M-E22                    | [227c78f3c1](https://bsd-hardware.info/?probe=227c78f3c1) | Mar 12, 2023 |
| ASRock        | Q1900M                      | [5d0f6c2276](https://bsd-hardware.info/?probe=5d0f6c2276) | Mar 12, 2023 |
| HP            | 8768 A                      | [5ab1dadbab](https://bsd-hardware.info/?probe=5ab1dadbab) | Mar 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [ad604088a2](https://bsd-hardware.info/?probe=ad604088a2) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| MSI           | A320M-A PRO                 | [593f6ff02d](https://bsd-hardware.info/?probe=593f6ff02d) | Mar 12, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ededc04017](https://bsd-hardware.info/?probe=ededc04017) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [37ee7b4f47](https://bsd-hardware.info/?probe=37ee7b4f47) | Mar 12, 2023 |
| Fujitsu       | JIM86YD                     | [7a69b91093](https://bsd-hardware.info/?probe=7a69b91093) | Mar 12, 2023 |
| MSI           | H61M-P31/W8                 | [5ae8ebe3cd](https://bsd-hardware.info/?probe=5ae8ebe3cd) | Mar 11, 2023 |
| HP            | 843B                        | [c1886bcd29](https://bsd-hardware.info/?probe=c1886bcd29) | Mar 11, 2023 |
| HP            | 3398                        | [20bcb682d8](https://bsd-hardware.info/?probe=20bcb682d8) | Mar 11, 2023 |
| ASUSTek       | P8Z68-V                     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| Dell          | 0C27VV A02                  | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Intel         | DG41TY AAE47335-300         | [7c1727d55a](https://bsd-hardware.info/?probe=7c1727d55a) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Huanan        | X99-TF GAMING V3.0          | [59db63fd9d](https://bsd-hardware.info/?probe=59db63fd9d) | Feb 22, 2023 |
| Huanan        | X99-TF GAMING V3.0          | [50dce9bf96](https://bsd-hardware.info/?probe=50dce9bf96) | Feb 19, 2023 |
| Gigabyte      | H81M-H                      | [8820014583](https://bsd-hardware.info/?probe=8820014583) | Feb 15, 2023 |
| Gigabyte      | H81M-H                      | [592ca6bab5](https://bsd-hardware.info/?probe=592ca6bab5) | Feb 15, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 108      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 107      | 99.07%  |
| GNOME        | 1        | 0.93%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 108      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 108      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| fr_FR   | 40       | 36.7%   |
| en_US   | 36       | 33.03%  |
| es_ES   | 9        | 8.26%   |
| de_DE   | 6        | 5.5%    |
| ru_RU   | 5        | 4.59%   |
| it_IT   | 3        | 2.75%   |
| Unknown | 3        | 2.75%   |
| pl_PL   | 2        | 1.83%   |
| jp_JP   | 2        | 1.83%   |
| pt_BR   | 1        | 0.92%   |
| fr      | 1        | 0.92%   |
| es      | 1        | 0.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 106      | 98.15%  |
| BIOS | 2        | 1.85%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 67       | 60.91%  |
| Zfs    | 43       | 39.09%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 106      | 98.15%  |
| MBR  | 2        | 1.85%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 23       | 21.3%   |
| Gigabyte Technology | 20       | 18.52%  |
| Hewlett-Packard     | 10       | 9.26%   |
| Dell                | 10       | 9.26%   |
| MSI                 | 8        | 7.41%   |
| Lenovo              | 8        | 7.41%   |
| Acer                | 4        | 3.7%    |
| Unknown             | 4        | 3.7%    |
| Intel               | 3        | 2.78%   |
| ASRock              | 3        | 2.78%   |
| T-bao               | 2        | 1.85%   |
| Fujitsu Siemens     | 2        | 1.85%   |
| Fujitsu             | 2        | 1.85%   |
| Foxconn             | 2        | 1.85%   |
| Pegatron            | 1        | 0.93%   |
| Huanan              | 1        | 0.93%   |
| Google              | 1        | 0.93%   |
| Biostar             | 1        | 0.93%   |
| BESSTAR Tech        | 1        | 0.93%   |
| AZW                 | 1        | 0.93%   |
| Axiomtek            | 1        | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 4        | 3.7%    |
| T-bao MINI PC                       | 2        | 1.85%   |
| MSI MS-7788                         | 2        | 1.85%   |
| HP Compaq Elite 8300 USDT           | 2        | 1.85%   |
| ASUS PRIME B250M-A                  | 2        | 1.85%   |
| Pegatron Compaq dx2450 Microtower   | 1        | 0.93%   |
| MSI MS-7C95                         | 1        | 0.93%   |
| MSI MS-7C51                         | 1        | 0.93%   |
| MSI MS-7C09                         | 1        | 0.93%   |
| MSI MS-7B86                         | 1        | 0.93%   |
| MSI MS-7599                         | 1        | 0.93%   |
| MSI Compaq dx2200 MT                | 1        | 0.93%   |
| Lenovo ThinkCentre M900 10FLS15P00  | 1        | 0.93%   |
| Lenovo ThinkCentre M900 10FGS05C08  | 1        | 0.93%   |
| Lenovo ThinkCentre M75e 5065A11     | 1        | 0.93%   |
| Lenovo ThinkCentre M73 10AYA06EIA   | 1        | 0.93%   |
| Lenovo ThinkCentre M73 10AXS34800   | 1        | 0.93%   |
| Lenovo ThinkCentre M710s 10M8S0FW00 | 1        | 0.93%   |
| Lenovo ThinkCentre M58p 6138DK1     | 1        | 0.93%   |
| Lenovo ThinkCentre Edge72 34971B1   | 1        | 0.93%   |
| Intel X99                           | 1        | 0.93%   |
| Intel DG41TY AAE47335-300           | 1        | 0.93%   |
| Intel DB85FL AAG89861-203           | 1        | 0.93%   |
| Huanan X99-TF GAMING V3.0           | 1        | 0.93%   |
| HP Slim Desktop S01-pF1xxx          | 1        | 0.93%   |
| HP rp5800                           | 1        | 0.93%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 0.93%   |
| HP EliteDesk 800 G2 SFF             | 1        | 0.93%   |
| HP EliteDesk 800 G2 DM 65W          | 1        | 0.93%   |
| HP EliteDesk 800 G2 DM 35W          | 1        | 0.93%   |
| HP Compaq Elite 8300 SFF            | 1        | 0.93%   |
| HP 290 G1 MT                        | 1        | 0.93%   |
| Google Panther                      | 1        | 0.93%   |
| Gigabyte Z87X-UD4H                  | 1        | 0.93%   |
| Gigabyte M52L-S3P                   | 1        | 0.93%   |
| Gigabyte H81M-S2PH                  | 1        | 0.93%   |
| Gigabyte H81M-H                     | 1        | 0.93%   |
| Gigabyte H81M-DS2V                  | 1        | 0.93%   |
| Gigabyte H61M-S2PH                  | 1        | 0.93%   |
| Gigabyte H61M-S2P-B3                | 1        | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Lenovo ThinkCentre      | 8        | 7.41%   |
| ASUS PRIME              | 7        | 6.48%   |
| Dell OptiPlex           | 6        | 5.56%   |
| ASUS ROG                | 5        | 4.63%   |
| Unknown                 | 4        | 3.7%    |
| HP EliteDesk            | 3        | 2.78%   |
| HP Compaq               | 3        | 2.78%   |
| T-bao MINI              | 2        | 1.85%   |
| MSI MS-7788             | 2        | 1.85%   |
| Gigabyte B450M          | 2        | 1.85%   |
| Fujitsu Siemens ESPRIMO | 2        | 1.85%   |
| Dell Precision          | 2        | 1.85%   |
| ASUS TUF                | 2        | 1.85%   |
| Acer Veriton            | 2        | 1.85%   |
| Pegatron Compaq         | 1        | 0.93%   |
| MSI MS-7C95             | 1        | 0.93%   |
| MSI MS-7C51             | 1        | 0.93%   |
| MSI MS-7C09             | 1        | 0.93%   |
| MSI MS-7B86             | 1        | 0.93%   |
| MSI MS-7599             | 1        | 0.93%   |
| MSI Compaq              | 1        | 0.93%   |
| Intel X99               | 1        | 0.93%   |
| Intel DG41TY            | 1        | 0.93%   |
| Intel DB85FL            | 1        | 0.93%   |
| Huanan X99-TF           | 1        | 0.93%   |
| HP Slim                 | 1        | 0.93%   |
| HP rp5800               | 1        | 0.93%   |
| HP Pavilion             | 1        | 0.93%   |
| HP 290                  | 1        | 0.93%   |
| Google Panther          | 1        | 0.93%   |
| Gigabyte Z87X-UD4H      | 1        | 0.93%   |
| Gigabyte M52L-S3P       | 1        | 0.93%   |
| Gigabyte H81M-S2PH      | 1        | 0.93%   |
| Gigabyte H81M-H         | 1        | 0.93%   |
| Gigabyte H81M-DS2V      | 1        | 0.93%   |
| Gigabyte H61M-S2PH      | 1        | 0.93%   |
| Gigabyte H61M-S2P-B3    | 1        | 0.93%   |
| Gigabyte H61M-DS2       | 1        | 0.93%   |
| Gigabyte H110M-S2       | 1        | 0.93%   |
| Gigabyte H110M-H-CF     | 1        | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2022    | 13       | 12.04%  |
| 2013    | 12       | 11.11%  |
| 2021    | 10       | 9.26%   |
| 2012    | 9        | 8.33%   |
| 2020    | 7        | 6.48%   |
| 2019    | 7        | 6.48%   |
| 2018    | 7        | 6.48%   |
| 2014    | 7        | 6.48%   |
| 2010    | 6        | 5.56%   |
| 2017    | 5        | 4.63%   |
| 2016    | 4        | 3.7%    |
| 2015    | 4        | 3.7%    |
| 2011    | 4        | 3.7%    |
| 2009    | 4        | 3.7%    |
| 2008    | 3        | 2.78%   |
| 2023    | 2        | 1.85%   |
| 2006    | 2        | 1.85%   |
| 2007    | 1        | 0.93%   |
| Unknown | 1        | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 108      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 107      | 99.07%  |
| Yes  | 1        | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 39       | 36.11%  |
| 16.01-24.0  | 26       | 24.07%  |
| 4.01-8.0    | 20       | 18.52%  |
| 32.01-64.0  | 13       | 12.04%  |
| 2.01-3.0    | 4        | 3.7%    |
| 24.01-32.0  | 2        | 1.85%   |
| 64.01-256.0 | 2        | 1.85%   |
| 3.01-4.0    | 1        | 0.93%   |
| 0.51-1.0    | 1        | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 50       | 45.45%  |
| 0.51-1.0 | 39       | 35.45%  |
| 1.01-2.0 | 17       | 15.45%  |
| 2.01-3.0 | 4        | 3.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 49       | 45.37%  |
| 2      | 28       | 25.93%  |
| 3      | 13       | 12.04%  |
| 0      | 7        | 6.48%   |
| 5      | 5        | 4.63%   |
| 9      | 2        | 1.85%   |
| 4      | 2        | 1.85%   |
| 7      | 1        | 0.93%   |
| 6      | 1        | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 61.11%  |
| Yes       | 42       | 38.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 104      | 96.3%   |
| No        | 4        | 3.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 66.97%  |
| Yes       | 36       | 33.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 80       | 74.07%  |
| Yes       | 28       | 25.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| USA                | 12       | 11.11%  |
| Russia             | 12       | 11.11%  |
| Spain              | 10       | 9.26%   |
| Germany            | 8        | 7.41%   |
| Italy              | 5        | 4.63%   |
| Hungary            | 5        | 4.63%   |
| Canada             | 5        | 4.63%   |
| Serbia             | 4        | 3.7%    |
| Romania            | 4        | 3.7%    |
| Poland             | 4        | 3.7%    |
| France             | 4        | 3.7%    |
| Brazil             | 4        | 3.7%    |
| Peru               | 3        | 2.78%   |
| Japan              | 2        | 1.85%   |
| India              | 2        | 1.85%   |
| China              | 2        | 1.85%   |
| Bulgaria           | 2        | 1.85%   |
| Belgium            | 2        | 1.85%   |
| Australia          | 2        | 1.85%   |
| Argentina          | 2        | 1.85%   |
| Ukraine            | 1        | 0.93%   |
| UK                 | 1        | 0.93%   |
| Turkey             | 1        | 0.93%   |
| Sweden             | 1        | 0.93%   |
| San Marino         | 1        | 0.93%   |
| Netherlands        | 1        | 0.93%   |
| Mexico             | 1        | 0.93%   |
| Indonesia          | 1        | 0.93%   |
| Dominican Republic | 1        | 0.93%   |
| Croatia            | 1        | 0.93%   |
| Chile              | 1        | 0.93%   |
| Belarus            | 1        | 0.93%   |
| Austria            | 1        | 0.93%   |
| Algeria            | 1        | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| St. Jean Baptiste        | 3        | 2.78%   |
| Madrid                   | 2        | 1.85%   |
| Kirov                    | 2        | 1.85%   |
| Berlin                   | 2        | 1.85%   |
| Belgrade                 | 2        | 1.85%   |
| Zhengzhou                | 1        | 0.93%   |
| Yokohama                 | 1        | 0.93%   |
| Warsaw                   | 1        | 0.93%   |
| Volgodonsk               | 1        | 0.93%   |
| Vogogna                  | 1        | 0.93%   |
| Virovitica               | 1        | 0.93%   |
| Villena                  | 1        | 0.93%   |
| Vienna                   | 1        | 0.93%   |
| Venice                   | 1        | 0.93%   |
| Vecses                   | 1        | 0.93%   |
| Valderrobres             | 1        | 0.93%   |
| Ubstadt-Weiher           | 1        | 0.93%   |
| Tucson                   | 1        | 0.93%   |
| Trumbull                 | 1        | 0.93%   |
| Topolovgrad              | 1        | 0.93%   |
| Timișoara               | 1        | 0.93%   |
| Sydney                   | 1        | 0.93%   |
| St Petersburg            | 1        | 0.93%   |
| Sopron                   | 1        | 0.93%   |
| Sofia                    | 1        | 0.93%   |
| Semlin                   | 1        | 0.93%   |
| Schweinfurt              | 1        | 0.93%   |
| Saskatoon                | 1        | 0.93%   |
| Saransk                  | 1        | 0.93%   |
| Sao Paulo                | 1        | 0.93%   |
| Santo Domingo Este       | 1        | 0.93%   |
| Santiago                 | 1        | 0.93%   |
| San Jose de la Rinconada | 1        | 0.93%   |
| Rochemaure               | 1        | 0.93%   |
| Río Cuarto              | 1        | 0.93%   |
| Ribeirao Preto           | 1        | 0.93%   |
| Ramenskoye               | 1        | 0.93%   |
| Radwanice                | 1        | 0.93%   |
| Portage                  | 1        | 0.93%   |
| Piatra Neamţ            | 1        | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 35       | 55     | 20.59%  |
| Seagate             | 25       | 30     | 14.71%  |
| Samsung Electronics | 22       | 35     | 12.94%  |
| Kingston            | 21       | 21     | 12.35%  |
| Toshiba             | 9        | 9      | 5.29%   |
| SanDisk             | 7        | 7      | 4.12%   |
| A-DATA Technology   | 5        | 6      | 2.94%   |
| Micron Technology   | 4        | 4      | 2.35%   |
| Maxtor              | 4        | 4      | 2.35%   |
| Hitachi             | 4        | 4      | 2.35%   |
| Crucial             | 4        | 5      | 2.35%   |
| Transcend           | 3        | 3      | 1.76%   |
| KingSpec            | 3        | 3      | 1.76%   |
| PNY                 | 2        | 2      | 1.18%   |
| Patriot             | 2        | 2      | 1.18%   |
| China               | 2        | 3      | 1.18%   |
| SPCC                | 1        | 1      | 0.59%   |
| Silicon Motion      | 1        | 1      | 0.59%   |
| QUANTUM             | 1        | 1      | 0.59%   |
| Pioneer             | 1        | 1      | 0.59%   |
| Palit               | 1        | 1      | 0.59%   |
| OCZ                 | 1        | 1      | 0.59%   |
| Kston               | 1        | 1      | 0.59%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.59%   |
| Intenso             | 1        | 1      | 0.59%   |
| GOODRAM             | 1        | 1      | 0.59%   |
| Gigabyte Technology | 1        | 2      | 0.59%   |
| EDGE                | 1        | 1      | 0.59%   |
| Corsair             | 1        | 1      | 0.59%   |
| Colorful            | 1        | 1      | 0.59%   |
| ASint Technology    | 1        | 1      | 0.59%   |
| Apple               | 1        | 1      | 0.59%   |
| Apacer              | 1        | 1      | 0.59%   |
| AMD                 | 1        | 1      | 0.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB | 5        | 2.45%   |
| Kingston SA400S37240G 240GB     | 5        | 2.45%   |
| Seagate ST3500418AS 500GB       | 4        | 1.96%   |
| WDC WD10EZEX-08WN4A0 1TB        | 3        | 1.47%   |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB  | 3        | 1.47%   |
| Samsung SSD 980 1TB             | 3        | 1.47%   |
| Samsung SSD 850 EVO 250GB       | 3        | 1.47%   |
| WDC WDS240G2G0A-00JH30 240GB    | 2        | 0.98%   |
| WDC WDS120G2G0A-00JH30 120GB    | 2        | 0.98%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 2        | 0.98%   |
| WDC WD10EZEX-60WN4A0 1TB        | 2        | 0.98%   |
| Toshiba DT01ACA100 1TB          | 2        | 0.98%   |
| Toshiba DT01ACA050 500GB        | 2        | 0.98%   |
| Samsung SSD 980 PRO 500GB       | 2        | 0.98%   |
| Samsung SSD 970 PRO 512GB       | 2        | 0.98%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 0.98%   |
| Samsung SSD 860 EVO 500GB       | 2        | 0.98%   |
| Kingston SHFS37A240G 240GB      | 2        | 0.98%   |
| Kingston SA400S37480G 480GB     | 2        | 0.98%   |
| Kingston SA400S37120G 120GB     | 2        | 0.98%   |
| Crucial CT240BX500SSD1 240GB    | 2        | 0.98%   |
| WDC WDS500G1B0A-00H9H0 500GB    | 1        | 0.49%   |
| WDC WDS250G1B0A-00H9H0 250GB    | 1        | 0.49%   |
| WDC WD800JD-75MSA3 80GB         | 1        | 0.49%   |
| WDC WD7501AALS-00J7B0 752GB     | 1        | 0.49%   |
| WDC WD6400BPVT-22HXZT3 640GB    | 1        | 0.49%   |
| WDC WD60EZRX-00MVLB1 6TB        | 1        | 0.49%   |
| WDC WD50NDZW-11A8JS1 5TB        | 1        | 0.49%   |
| WDC WD5003AZEX-00K1GA0 500GB    | 1        | 0.49%   |
| WDC WD5000LPCX-21VHAT0 500GB    | 1        | 0.49%   |
| WDC WD5000AZRX-00A8LB0 500GB    | 1        | 0.49%   |
| WDC WD5000AVVS-00ZWB0 500GB     | 1        | 0.49%   |
| WDC WD5000AAKX-001CA0 500GB     | 1        | 0.49%   |
| WDC WD42PURZ-85B4YY0 4TB        | 1        | 0.49%   |
| WDC WD40EZAZ-00ZGHB0 4TB        | 1        | 0.49%   |
| WDC WD40EZAZ-00SF3B0 4TB        | 1        | 0.49%   |
| WDC WD40EFRX-68WT0N0 4TB        | 1        | 0.49%   |
| WDC WD4000FYYZ-01UL1B3 4TB      | 1        | 0.49%   |
| WDC WD4000FYYZ-01UL1B2 4TB      | 1        | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 30       | 49     | 41.1%   |
| Seagate             | 25       | 30     | 34.25%  |
| Toshiba             | 7        | 7      | 9.59%   |
| Maxtor              | 4        | 4      | 5.48%   |
| Hitachi             | 4        | 4      | 5.48%   |
| Samsung Electronics | 1        | 1      | 1.37%   |
| QUANTUM             | 1        | 1      | 1.37%   |
| Apple               | 1        | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 14       | 14     | 19.18%  |
| Samsung Electronics | 12       | 18     | 16.44%  |
| SanDisk             | 7        | 7      | 9.59%   |
| WDC                 | 6        | 6      | 8.22%   |
| Crucial             | 4        | 5      | 5.48%   |
| Transcend           | 3        | 3      | 4.11%   |
| KingSpec            | 3        | 3      | 4.11%   |
| A-DATA Technology   | 3        | 3      | 4.11%   |
| Toshiba             | 2        | 2      | 2.74%   |
| PNY                 | 2        | 2      | 2.74%   |
| Patriot             | 2        | 2      | 2.74%   |
| China               | 2        | 3      | 2.74%   |
| SPCC                | 1        | 1      | 1.37%   |
| Pioneer             | 1        | 1      | 1.37%   |
| Palit               | 1        | 1      | 1.37%   |
| OCZ                 | 1        | 1      | 1.37%   |
| Micron Technology   | 1        | 1      | 1.37%   |
| Kston               | 1        | 1      | 1.37%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.37%   |
| Intenso             | 1        | 1      | 1.37%   |
| GOODRAM             | 1        | 1      | 1.37%   |
| Gigabyte Technology | 1        | 2      | 1.37%   |
| EDGE                | 1        | 1      | 1.37%   |
| Apacer              | 1        | 1      | 1.37%   |
| AMD                 | 1        | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 62       | 97     | 42.47%  |
| SSD  | 57       | 82     | 39.04%  |
| NVMe | 27       | 33     | 18.49%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 96       | 179    | 78.05%  |
| NVMe | 27       | 33     | 21.95%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 78       | 116    | 61.9%   |
| 0.51-1.0   | 25       | 28     | 19.84%  |
| 1.01-2.0   | 11       | 19     | 8.73%   |
| 3.01-4.0   | 7        | 8      | 5.56%   |
| 2.01-3.0   | 2        | 5      | 1.59%   |
| 4.01-10.0  | 2        | 2      | 1.59%   |
| 10.01-20.0 | 1        | 1      | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 64       | 58.72%  |
| 51-100     | 14       | 12.84%  |
| 101-250    | 12       | 11.01%  |
| 251-500    | 11       | 10.09%  |
| 501-1000   | 7        | 6.42%   |
| Unknown    | 1        | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 106      | 98.15%  |
| 21-50   | 1        | 0.93%   |
| Unknown | 1        | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| WDC WD800JD-75MSA3 80GB                    | 1        | 1      | 3.57%   |
| WDC WD6400BPVT-22HXZT3 640GB               | 1        | 1      | 3.57%   |
| WDC WD5000AAKX-08U6AA0 500GB               | 1        | 1      | 3.57%   |
| WDC WD30EFRX-68EUZN0 3TB                   | 1        | 1      | 3.57%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1        | 1      | 3.57%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 1      | 3.57%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1        | 1      | 3.57%   |
| WDC WD10EARS-003BB1 1TB                    | 1        | 1      | 3.57%   |
| Toshiba MK3259GSXP 320GB                   | 1        | 1      | 3.57%   |
| Toshiba DT01ACA100 1TB                     | 1        | 1      | 3.57%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB  | 1        | 1      | 3.57%   |
| Seagate ST500LM000-1EJ162 500GB            | 1        | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB            | 1        | 1      | 3.57%   |
| Seagate ST380215AS 80GB                    | 1        | 1      | 3.57%   |
| Seagate ST3500418AS 500GB                  | 1        | 1      | 3.57%   |
| Seagate ST3500320AS 500GB                  | 1        | 1      | 3.57%   |
| Seagate ST3320620AS 320GB                  | 1        | 1      | 3.57%   |
| Seagate ST2000DM008-2FR102 2TB             | 1        | 1      | 3.57%   |
| Seagate ST1000DM010-2EP102 1TB             | 1        | 1      | 3.57%   |
| Samsung Electronics MZVL22T0HBLB-00B00 2TB | 1        | 1      | 3.57%   |
| Samsung Electronics HD103SJ 1TB            | 1        | 1      | 3.57%   |
| Maxtor 6Y080M0 82GB                        | 1        | 1      | 3.57%   |
| Maxtor 6V080E0 80GB                        | 1        | 1      | 3.57%   |
| Maxtor 6L080P0 82GB                        | 1        | 1      | 3.57%   |
| Kingston SA400S37240G 240GB                | 1        | 1      | 3.57%   |
| Hitachi HTS725050A7E630 500GB              | 1        | 1      | 3.57%   |
| Hitachi HTS541680J9SA00 80GB               | 1        | 1      | 3.57%   |
| Crucial CT1050MX300SSD1 1TB                | 1        | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 8      | 30.77%  |
| Seagate             | 6        | 8      | 23.08%  |
| Maxtor              | 3        | 3      | 11.54%  |
| Toshiba             | 2        | 2      | 7.69%   |
| Samsung Electronics | 2        | 2      | 7.69%   |
| Hitachi             | 2        | 2      | 7.69%   |
| Silicon Motion      | 1        | 1      | 3.85%   |
| Kingston            | 1        | 1      | 3.85%   |
| Crucial             | 1        | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 8      | 36.36%  |
| Seagate             | 6        | 8      | 27.27%  |
| Maxtor              | 3        | 3      | 13.64%  |
| Toshiba             | 2        | 2      | 9.09%   |
| Hitachi             | 2        | 2      | 9.09%   |
| Samsung Electronics | 1        | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 22       | 24     | 84.62%  |
| NVMe | 2        | 2      | 7.69%   |
| SSD  | 2        | 2      | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB | 1        | 1      | 33.33%  |
| WDC WD1600BEVT-22ZCT0 160GB | 1        | 1      | 33.33%  |
| SanDisk pSSD 128GB          | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 66.67%  |
| SanDisk | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 86       | 174    | 72.27%  |
| Malfunc  | 26       | 28     | 21.85%  |
| Detected | 4        | 7      | 3.36%   |
| Failed   | 3        | 3      | 2.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 76       | 52.78%  |
| AMD                         | 27       | 18.75%  |
| Samsung Electronics         | 12       | 8.33%   |
| Kingston Technology Company | 7        | 4.86%   |
| Nvidia                      | 4        | 2.78%   |
| Micron Technology           | 3        | 2.08%   |
| Marvell Technology Group    | 3        | 2.08%   |
| ASMedia Technology          | 3        | 2.08%   |
| Silicon Motion              | 2        | 1.39%   |
| Realtek Semiconductor       | 2        | 1.39%   |
| VIA Technologies            | 1        | 0.69%   |
| Sandisk                     | 1        | 0.69%   |
| Phison Electronics          | 1        | 0.69%   |
| Broadcom / LSI              | 1        | 0.69%   |
| ADATA Technology            | 1        | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 6.04%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 10       | 5.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 4.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 3.3%    |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 3.3%    |
| Samsung NVMe SSD Controller 980                                                         | 5        | 2.75%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 2.2%    |
| Intel SATA Controller [RAID mode]                                                       | 4        | 2.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 2.2%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 2.2%    |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.65%   |
| Micron NVMe Storage Controller                                                          | 3        | 1.65%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.65%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.65%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3        | 1.65%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3        | 1.65%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.65%   |
| Unknown                                                                                 | 3        | 1.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2        | 1.1%    |
| Realtek NVMe Controller                                                                 | 2        | 1.1%    |
| Nvidia MCP61 IDE                                                                        | 2        | 1.1%    |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 2        | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 1.1%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 1.1%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2        | 1.1%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.55%   |
| Sandisk WD Black SN770 NVMe SSD                                                         | 1        | 0.55%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1        | 0.55%   |
| Nvidia CK804 IDE                                                                        | 1        | 0.55%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.55%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 80       | 56.34%  |
| NVMe | 27       | 19.01%  |
| IDE  | 27       | 19.01%  |
| RAID | 7        | 4.93%   |
| SAS  | 1        | 0.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 78       | 72.22%  |
| AMD    | 30       | 27.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz              | 4        | 3.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3        | 2.78%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 3        | 2.78%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 2.78%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3        | 2.78%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2        | 1.85%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2        | 1.85%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2        | 1.85%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 2        | 1.85%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2        | 1.85%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2        | 1.85%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 2        | 1.85%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 2        | 1.85%   |
| Intel 12th Gen Core i5-12400                  | 2        | 1.85%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2        | 1.85%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2        | 1.85%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2        | 1.85%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1        | 0.93%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1        | 0.93%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz           | 1        | 0.93%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz           | 1        | 0.93%   |
| Intel Xeon                                    | 1        | 0.93%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1        | 0.93%   |
| Intel Pentium Dual-Core CPU E5300             | 1        | 0.93%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1        | 0.93%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 1        | 0.93%   |
| Intel Pentium 4 CPU                           | 1        | 0.93%   |
| Intel Core i9-10900 CPU @ 2.80GHz             | 1        | 0.93%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1        | 0.93%   |
| Intel Core i7-4771 CPU @ 3.50GHz              | 1        | 0.93%   |
| Intel Core i7-4770S CPU @ 3.10GHz             | 1        | 0.93%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1        | 0.93%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1        | 0.93%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1        | 0.93%   |
| Intel Core i7 CPU 950 @ 3.07GHz               | 1        | 0.93%   |
| Intel Core i5-9500 CPU @ 3.00GHz              | 1        | 0.93%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1        | 0.93%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1        | 0.93%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 1        | 0.93%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1        | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 22       | 20.37%  |
| Intel Core i3           | 19       | 17.59%  |
| Intel Core i7           | 9        | 8.33%   |
| AMD Ryzen 5             | 9        | 8.33%   |
| Intel Celeron           | 7        | 6.48%   |
| Intel Xeon              | 5        | 4.63%   |
| Other                   | 4        | 3.7%    |
| Intel Core 2 Duo        | 4        | 3.7%    |
| AMD Ryzen 7             | 4        | 3.7%    |
| AMD Ryzen 3             | 3        | 2.78%   |
| Intel Pentium           | 2        | 1.85%   |
| Intel Core 2 Quad       | 2        | 1.85%   |
| AMD Phenom II X4        | 2        | 1.85%   |
| AMD Athlon II X2        | 2        | 1.85%   |
| AMD A4                  | 2        | 1.85%   |
| Intel Pentium Gold      | 1        | 0.93%   |
| Intel Pentium Dual-Core | 1        | 0.93%   |
| Intel Pentium 4         | 1        | 0.93%   |
| Intel Core i9           | 1        | 0.93%   |
| AMD Ryzen 9             | 1        | 0.93%   |
| AMD Phenom II X2        | 1        | 0.93%   |
| AMD FX                  | 1        | 0.93%   |
| AMD E                   | 1        | 0.93%   |
| AMD Athlon X2           | 1        | 0.93%   |
| AMD Athlon II X4        | 1        | 0.93%   |
| AMD Athlon 64           | 1        | 0.93%   |
| AMD A10                 | 1        | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 44       | 40.74%  |
| 2       | 33       | 30.56%  |
| 6       | 9        | 8.33%   |
| 12      | 8        | 7.41%   |
| 8       | 4        | 3.7%    |
| Unknown | 4        | 3.7%    |
| 16      | 2        | 1.85%   |
| 1       | 2        | 1.85%   |
| 24      | 1        | 0.93%   |
| 10      | 1        | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 107      | 99.07%  |
| 2      | 1        | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 68       | 62.96%  |
| 2       | 35       | 32.41%  |
| Unknown | 5        | 4.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Haswell     | 16       | 14.81%  |
| KabyLake    | 13       | 12.04%  |
| IvyBridge   | 12       | 11.11%  |
| Skylake     | 10       | 9.26%   |
| Zen+        | 7        | 6.48%   |
| Zen 3       | 7        | 6.48%   |
| SandyBridge | 7        | 6.48%   |
| K10         | 7        | 6.48%   |
| Penryn      | 6        | 5.56%   |
| Unknown     | 5        | 4.63%   |
| Zen         | 3        | 2.78%   |
| Piledriver  | 3        | 2.78%   |
| Core        | 3        | 2.78%   |
| Silvermont  | 2        | 1.85%   |
| CometLake   | 2        | 1.85%   |
| NetBurst    | 1        | 0.93%   |
| Nehalem     | 1        | 0.93%   |
| K8 Hammer   | 1        | 0.93%   |
| Bulldozer   | 1        | 0.93%   |
| Bobcat      | 1        | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 54       | 46.96%  |
| Nvidia                     | 31       | 26.96%  |
| AMD                        | 29       | 25.22%  |
| Matrox Electronics Systems | 1        | 0.87%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                       | 8        | 6.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6        | 5.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 4.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5        | 4.31%   |
| Intel HD Graphics 630                                                       | 5        | 4.31%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 4.31%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 3.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 2.59%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 2.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 2.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.59%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 2.59%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 2.59%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.72%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.72%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.72%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 1.72%   |
| AMD RS880 [Radeon HD 4250]                                                  | 2        | 1.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.72%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.72%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.86%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.86%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.86%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.86%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.86%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.86%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1        | 0.86%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.86%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 0.86%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 0.86%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.86%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 1        | 0.86%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 0.86%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1        | 0.86%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 1        | 0.86%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 0.86%   |
| Nvidia G72 [GeForce 7300 GS]                                                | 1        | 0.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 42       | 38.53%  |
| 1 x Nvidia     | 29       | 26.61%  |
| 1 x AMD        | 25       | 22.94%  |
| 2 x Intel      | 5        | 4.59%   |
| Intel + AMD    | 5        | 4.59%   |
| Intel + Nvidia | 2        | 1.83%   |
| 1 x Matrox     | 1        | 0.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 83       | 76.85%  |
| Proprietary | 23       | 21.3%   |
| Unknown     | 2        | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 62.04%  |
| 3.01-4.0   | 12       | 11.11%  |
| 1.01-2.0   | 8        | 7.41%   |
| 0.51-1.0   | 7        | 6.48%   |
| 5.01-6.0   | 5        | 4.63%   |
| 0.01-0.5   | 5        | 4.63%   |
| 7.01-8.0   | 2        | 1.85%   |
| 2.01-3.0   | 1        | 0.93%   |
| 8.01-16.0  | 1        | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Acer                 | 4        | 21.05%  |
| LG Electronics       | 2        | 10.53%  |
| Dell                 | 2        | 10.53%  |
| BenQ                 | 2        | 10.53%  |
| Unknown              | 2        | 10.53%  |
| PKB                  | 1        | 5.26%   |
| NEC Computers        | 1        | 5.26%   |
| Microstep            | 1        | 5.26%   |
| Idek Iiyama          | 1        | 5.26%   |
| AUS                  | 1        | 5.26%   |
| AOC                  | 1        | 5.26%   |
| Ancor Communications | 1        | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Unknown                                         | 2        | 10.53%  |
| PKB LCD Monitor MAE200W 1680x1050               | 1        | 5.26%   |
| NEC Computers LCD Monitor 70GX2 1280x1024       | 1        | 5.26%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080     | 1        | 5.26%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080 | 1        | 5.26%   |
| LG Electronics LCD Monitor L1918S 1280x1024     | 1        | 5.26%   |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160      | 1        | 5.26%   |
| Dell LCD Monitor U2419HC 1920x1080              | 1        | 5.26%   |
| Dell LCD Monitor S2721D 2560x1440               | 1        | 5.26%   |
| BenQ LCD Monitor GW2780 1920x1080               | 1        | 5.26%   |
| BenQ LCD Monitor GW2260 1920x1080               | 1        | 5.26%   |
| AUS LCD Monitor ASUS VG247Q1A 1920x1080         | 1        | 5.26%   |
| AOC LCD Monitor 27B2 1920x1080                  | 1        | 5.26%   |
| Ancor Communications LCD Monitor VX238          | 1        | 5.26%   |
| Acer LCD Monitor XV280K 3840x2160               | 1        | 5.26%   |
| Acer LCD Monitor XB273K GP 3840x2160            | 1        | 5.26%   |
| Acer LCD Monitor VG270U 2560x1440               | 1        | 5.26%   |
| Acer LCD Monitor KG251Q 3840x1080               | 1        | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 7        | 36.84%  |
| 3840x2160 (4K)     | 2        | 10.53%  |
| 2560x1440 (QHD)    | 2        | 10.53%  |
| 1280x1024 (SXGA)   | 2        | 10.53%  |
| Unknown            | 2        | 10.53%  |
| 5760x2160          | 1        | 5.26%   |
| 3840x1080          | 1        | 5.26%   |
| 1680x1050 (WSXGA+) | 1        | 5.26%   |
| 1366x768 (WXGA)    | 1        | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 100%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 17       | 100%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 17       | 100%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 100%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 87       | 80.56%  |
| 0     | 18       | 16.67%  |
| 2     | 3        | 2.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 66       | 49.25%  |
| Intel                    | 44       | 32.84%  |
| Qualcomm Atheros         | 7        | 5.22%   |
| Ralink                   | 3        | 2.24%   |
| TP-Link                  | 2        | 1.49%   |
| Ralink Technology        | 2        | 1.49%   |
| Marvell Technology Group | 2        | 1.49%   |
| Broadcom                 | 2        | 1.49%   |
| Samsung Electronics      | 1        | 0.75%   |
| MediaTek                 | 1        | 0.75%   |
| Huawei Technologies      | 1        | 0.75%   |
| D-Link                   | 1        | 0.75%   |
| Atheros                  | 1        | 0.75%   |
| Accton Technology        | 1        | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57       | 38.51%  |
| Intel Ethernet Connection (2) I219-LM                             | 6        | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 4.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4        | 2.7%    |
| Intel Ethernet Controller I225-V                                  | 4        | 2.7%    |
| Intel Ethernet Connection I217-V                                  | 4        | 2.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 2.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 2.03%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 2.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 1.35%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 1.35%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.35%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.35%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.35%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 1.35%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.35%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.35%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 2        | 1.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.68%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1        | 0.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.68%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                      | 1        | 0.68%   |
| Ralink RT3072 Wireless Adapter                                    | 1        | 0.68%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1        | 0.68%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.68%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.68%   |
| Ralink RT2500 Wireless 802.11bg                                   | 1        | 0.68%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1        | 0.68%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.68%   |
| Intel Wireless 7265                                               | 1        | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 10       | 27.03%  |
| Intel                 | 10       | 27.03%  |
| Qualcomm Atheros      | 4        | 10.81%  |
| Ralink                | 3        | 8.11%   |
| TP-Link               | 2        | 5.41%   |
| Ralink Technology     | 2        | 5.41%   |
| Broadcom              | 2        | 5.41%   |
| MediaTek              | 1        | 2.7%    |
| D-Link                | 1        | 2.7%    |
| Atheros               | 1        | 2.7%    |
| Accton Technology     | 1        | 2.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4        | 10.53%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 7.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 5.26%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 5.26%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2        | 5.26%   |
| Intel Wi-Fi 6 AX200                                                  | 2        | 5.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2        | 5.26%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2        | 5.26%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 2.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1        | 2.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 2.63%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                         | 1        | 2.63%   |
| Ralink RT3072 Wireless Adapter                                       | 1        | 2.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 2.63%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1        | 2.63%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1        | 2.63%   |
| Ralink RT2500 Wireless 802.11bg                                      | 1        | 2.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1        | 2.63%   |
| Intel Wireless 7265                                                  | 1        | 2.63%   |
| Intel Wireless 7260                                                  | 1        | 2.63%   |
| Intel Wireless 3165                                                  | 1        | 2.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 2.63%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.D1) [Realtek RTL8188ETV]   | 1        | 2.63%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1        | 2.63%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 1        | 2.63%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 2.63%   |
| Accton Arcadyan 802.11N Wireless Adapter                             | 1        | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 62       | 57.41%  |
| Intel                    | 38       | 35.19%  |
| Qualcomm Atheros         | 3        | 2.78%   |
| Marvell Technology Group | 2        | 1.85%   |
| Samsung Electronics      | 1        | 0.93%   |
| Huawei Technologies      | 1        | 0.93%   |
| Broadcom                 | 1        | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57       | 51.82%  |
| Intel Ethernet Connection (2) I219-LM                             | 6        | 5.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6        | 5.45%   |
| Intel Ethernet Controller I225-V                                  | 4        | 3.64%   |
| Intel Ethernet Connection I217-V                                  | 4        | 3.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 2.73%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 2.73%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.82%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.82%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.82%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.82%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 2        | 1.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.91%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.91%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.91%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.91%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.91%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.91%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.91%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.91%   |
| Intel Ethernet Connection (5) I219-V                              | 1        | 0.91%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.91%   |
| Huawei Android ADB Interface                                      | 1        | 0.91%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1        | 0.91%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 104      | 74.29%  |
| WiFi     | 36       | 25.71%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 93       | 93.94%  |
| WiFi     | 6        | 6.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 76       | 69.72%  |
| 2     | 29       | 26.61%  |
| 0     | 3        | 2.75%   |
| 3     | 1        | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 102      | 93.58%  |
| Yes  | 7        | 6.42%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 9        | 31.03%  |
| Realtek Semiconductor   | 6        | 20.69%  |
| Cambridge Silicon Radio | 6        | 20.69%  |
| TP-Link                 | 2        | 6.9%    |
| IMC Networks            | 2        | 6.9%    |
| Primax Electronics      | 1        | 3.45%   |
| Fujitsu                 | 1        | 3.45%   |
| Broadcom                | 1        | 3.45%   |
| ASUSTek Computer        | 1        | 3.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)        | 6        | 20.69%  |
| Realtek Bluetooth Adapter                                  | 4        | 13.79%  |
| Intel Bluetooth wireless interface                         | 3        | 10.34%  |
| TP-Link Bluetooth 5.0 USB Adapter                          | 2        | 6.9%    |
| Realtek  Bluetooth 4.2 Adapter                             | 2        | 6.9%    |
| Intel Wireless-AC 3168 Bluetooth                           | 2        | 6.9%    |
| Intel AX201 Bluetooth                                      | 2        | 6.9%    |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter              | 1        | 3.45%   |
| Intel AX210 Bluetooth                                      | 1        | 3.45%   |
| Intel AX200 Bluetooth                                      | 1        | 3.45%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS    | 1        | 3.45%   |
| IMC Networks MediaTek Bluetooth Adapter                    | 1        | 3.45%   |
| Fujitsu Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter | 1        | 3.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                          | 1        | 3.45%   |
| ASUS USB-BT500                                             | 1        | 3.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 73       | 44.51%  |
| AMD                    | 40       | 24.39%  |
| Nvidia                 | 30       | 18.29%  |
| C-Media Electronics    | 7        | 4.27%   |
| Texas Instruments      | 3        | 1.83%   |
| Realtek Semiconductor  | 2        | 1.22%   |
| Creative Labs          | 2        | 1.22%   |
| Yamaha                 | 1        | 0.61%   |
| OPPO Electronics       | 1        | 0.61%   |
| KTMicro                | 1        | 0.61%   |
| Hewlett-Packard        | 1        | 0.61%   |
| Generalplus Technology | 1        | 0.61%   |
| GEMBIRD                | 1        | 0.61%   |
| Edifier Technology     | 1        | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13       | 6.77%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 5.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 5.21%   |
| Intel 200 Series PCH HD Audio                                              | 10       | 5.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 4.69%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 3.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 3.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 3.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 2.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5        | 2.6%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 2.6%    |
| Nvidia TU116 High Definition Audio Controller                              | 4        | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 2.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4        | 2.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 2.08%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 1.56%   |
| Nvidia High Definition Audio Controller                                    | 3        | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.56%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.56%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 1.56%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3        | 1.56%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.56%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.04%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2        | 1.04%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 1.04%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 1.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 1.04%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 2        | 1.04%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 1.04%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 2        | 1.04%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.04%   |
| Yamaha AG06/AG03                                                           | 1        | 0.52%   |
| Texas Instruments PCM2903C Audio CODEC                                     | 1        | 0.52%   |
| Texas Instruments PCM2901 Audio Codec                                      | 1        | 0.52%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 28       | 21.54%  |
| Samsung Electronics | 16       | 12.31%  |
| Unknown             | 15       | 11.54%  |
| Corsair             | 12       | 9.23%   |
| SK hynix            | 9        | 6.92%   |
| Crucial             | 9        | 6.92%   |
| Micron Technology   | 7        | 5.38%   |
| G.Skill             | 5        | 3.85%   |
| Unknown             | 5        | 3.85%   |
| Patriot             | 3        | 2.31%   |
| Ramaxel Technology  | 2        | 1.54%   |
| Nanya Technology    | 2        | 1.54%   |
| Apacer              | 2        | 1.54%   |
| A-DATA Technology   | 2        | 1.54%   |
| Transcend           | 1        | 0.77%   |
| Team                | 1        | 0.77%   |
| Smart               | 1        | 0.77%   |
| Qumo                | 1        | 0.77%   |
| MemoWise            | 1        | 0.77%   |
| Kingmax             | 1        | 0.77%   |
| Juhor               | 1        | 0.77%   |
| GOODRAM             | 1        | 0.77%   |
| Golden Empire       | 1        | 0.77%   |
| Elpida              | 1        | 0.77%   |
| Avant               | 1        | 0.77%   |
| Atermiter           | 1        | 0.77%   |
| AMD                 | 1        | 0.77%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 5        | 3.55%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 2        | 1.42%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                     | 2        | 1.42%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 2        | 1.42%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                       | 2        | 1.42%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 2        | 1.42%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                   | 2        | 1.42%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 0.71%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                    | 1        | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1        | 0.71%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                               | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                               | 1        | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                | 1        | 0.71%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                                | 1        | 0.71%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                | 1        | 0.71%   |
| Unknown RAM Module 1GB DIMM DDR2                                        | 1        | 0.71%   |
| Unknown RAM Module 1GB DIMM 400MT/s                                     | 1        | 0.71%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s                       | 1        | 0.71%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                              | 1        | 0.71%   |
| Smart RAM SH564128FH8N0QNSCG 4GB DIMM DDR3 1600MT/s                     | 1        | 0.71%   |
| SK hynix RAM Module 2GB DIMM DDR2 1639MT/s                              | 1        | 0.71%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                           | 1        | 0.71%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1333MT/s                    | 1        | 0.71%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB DIMM DDR3 1600MT/s                    | 1        | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                  | 1        | 0.71%   |
| SK hynix RAM HMT125U6AFP8C-G7 2GB DIMM DDR3 1066MT/s                    | 1        | 0.71%   |
| SK hynix RAM HMAA2GU6CJR8N-XN 16GB DIMM DDR4 2400MT/s                   | 1        | 0.71%   |
| SK hynix RAM HMA81GU6MFR8N-UH 8GB DIMM DDR4 2400MT/s                    | 1        | 0.71%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s                    | 1        | 0.71%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                             | 1        | 0.71%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 0.71%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                               | 1        | 0.71%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                               | 1        | 0.71%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                             | 1        | 0.71%   |
| Samsung RAM Module 1GB DIMM DDR2 533MT/s                                | 1        | 0.71%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                   | 1        | 0.71%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                   | 1        | 0.71%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                     | 1        | 0.71%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s                     | 1        | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 50       | 46.73%  |
| DDR3    | 38       | 35.51%  |
| DDR2    | 10       | 9.35%   |
| Unknown | 8        | 7.48%   |
| SDRAM   | 1        | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 91       | 85.05%  |
| SODIMM | 16       | 14.95%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 46       | 37.4%   |
| 4096  | 32       | 26.02%  |
| 2048  | 24       | 19.51%  |
| 16384 | 13       | 10.57%  |
| 1024  | 8        | 6.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 23       | 19.83%  |
| 1600    | 20       | 17.24%  |
| 2400    | 13       | 11.21%  |
| 2133    | 13       | 11.21%  |
| 3200    | 10       | 8.62%   |
| 2667    | 10       | 8.62%   |
| 800     | 7        | 6.03%   |
| 3600    | 3        | 2.59%   |
| 667     | 3        | 2.59%   |
| 3000    | 2        | 1.72%   |
| 1067    | 2        | 1.72%   |
| 1066    | 2        | 1.72%   |
| 3333    | 1        | 0.86%   |
| 2666    | 1        | 0.86%   |
| 1867    | 1        | 0.86%   |
| 1639    | 1        | 0.86%   |
| 1200    | 1        | 0.86%   |
| 533     | 1        | 0.86%   |
| 400     | 1        | 0.86%   |
| Unknown | 1        | 0.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 2        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Brother HL-L2300D series | 1        | 50%     |
| Brother DCP-J152W        | 1        | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 120 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Microdia                      | 2        | 20%     |
| Logitech                      | 2        | 20%     |
| Trust                         | 1        | 10%     |
| Sunplus Innovation Technology | 1        | 10%     |
| Importek                      | 1        | 10%     |
| IMC Networks                  | 1        | 10%     |
| Genesys Logic                 | 1        | 10%     |
| GEMBIRD                       | 1        | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Microdia REDRAGON Live Camera Audio               | 2        | 20%     |
| Trust Trust Full HD Webcam                        | 1        | 10%     |
| Sunplus SPCA2650 AV Camera                        | 1        | 10%     |
| Logitech Webcam C270                              | 1        | 10%     |
| Logitech HD Pro Webcam C920                       | 1        | 10%     |
| Importek FJ Camera                                | 1        | 10%     |
| IMC Networks XHC Camera                           | 1        | 10%     |
| Genesys Logic Digital Microscope                  | 1        | 10%     |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 10%     |

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

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 50       | 45.87%  |
| 0     | 37       | 33.94%  |
| 2     | 21       | 19.27%  |
| 3     | 1        | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 64       | 71.11%  |
| Net/wireless             | 11       | 12.22%  |
| Sound                    | 10       | 11.11%  |
| Bluetooth                | 4        | 4.44%   |
| Dvb card                 | 1        | 1.11%   |

