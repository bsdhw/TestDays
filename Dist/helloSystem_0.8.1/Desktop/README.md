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

Total: 160

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | 8055                        | [94df572de4](https://bsd-hardware.info/?probe=94df572de4) | Jun 29, 2023 |
| ASUSTek       | M2A-VM                      | [2d5a9bba42](https://bsd-hardware.info/?probe=2d5a9bba42) | Jun 28, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [2dfabb3a28](https://bsd-hardware.info/?probe=2dfabb3a28) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [b63efe1bc2](https://bsd-hardware.info/?probe=b63efe1bc2) | Jun 23, 2023 |
| LG Electro... | R590-K.AAA9BT               | [5c3ab65e8e](https://bsd-hardware.info/?probe=5c3ab65e8e) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [29545a1054](https://bsd-hardware.info/?probe=29545a1054) | Jun 21, 2023 |
| ASUSTek       | P7P55D LE                   | [ea97ade85d](https://bsd-hardware.info/?probe=ea97ade85d) | Jun 17, 2023 |
| Dell          | 0X9X1W A00                  | [64825f4f71](https://bsd-hardware.info/?probe=64825f4f71) | Jun 08, 2023 |
| Dell          | 0X9X1W A00                  | [c9d8d9a491](https://bsd-hardware.info/?probe=c9d8d9a491) | Jun 08, 2023 |
| Dell          | 0WR7PY A03                  | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| Intel         | H81                         | [e0e15704fc](https://bsd-hardware.info/?probe=e0e15704fc) | May 29, 2023 |
| HP            | 21D0                        | [4a10865d28](https://bsd-hardware.info/?probe=4a10865d28) | May 28, 2023 |
| HP            | 21D0                        | [e3d20826b3](https://bsd-hardware.info/?probe=e3d20826b3) | May 28, 2023 |
| Gigabyte      | X58A-UD3R                   | [1d43f61471](https://bsd-hardware.info/?probe=1d43f61471) | May 27, 2023 |
| Unknown       | 1.0                         | [12d6c7934e](https://bsd-hardware.info/?probe=12d6c7934e) | May 27, 2023 |
| ASUSTek       | PRIME H510M-K               | [53a2d5356d](https://bsd-hardware.info/?probe=53a2d5356d) | May 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a0bff43f5c](https://bsd-hardware.info/?probe=a0bff43f5c) | May 23, 2023 |
| AZW           | GK55                        | [ef90c15915](https://bsd-hardware.info/?probe=ef90c15915) | May 23, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [0a03cd86a0](https://bsd-hardware.info/?probe=0a03cd86a0) | May 21, 2023 |
| ASUSTek       | Z87M-PLUS                   | [58da7daed7](https://bsd-hardware.info/?probe=58da7daed7) | May 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| Gigabyte      | Z490 VISION G               | [976e31bfbc](https://bsd-hardware.info/?probe=976e31bfbc) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | [8eeec83a4e](https://bsd-hardware.info/?probe=8eeec83a4e) | May 16, 2023 |
| ASUSTek       | PRIME A520M-K               | [bda308bc8c](https://bsd-hardware.info/?probe=bda308bc8c) | May 14, 2023 |
| Dell          | 0WN7Y6 A01                  | [a232411c74](https://bsd-hardware.info/?probe=a232411c74) | May 12, 2023 |
| ASUSTek       | PRIME B450M-K II            | [fe053db6c7](https://bsd-hardware.info/?probe=fe053db6c7) | May 10, 2023 |
| ASUSTek       | PRIME B450M-K II            | [16ca4a2aa0](https://bsd-hardware.info/?probe=16ca4a2aa0) | May 10, 2023 |
| ASRock        | Q1900M                      | [c779034e79](https://bsd-hardware.info/?probe=c779034e79) | May 09, 2023 |
| Dell          | 07F37C A00                  | [a23a95f97a](https://bsd-hardware.info/?probe=a23a95f97a) | May 07, 2023 |
| ASRock        | J4125-ITX                   | [6e34c8b22a](https://bsd-hardware.info/?probe=6e34c8b22a) | May 05, 2023 |
| Intel         | DH87RL AAG74240-400         | [7833b60865](https://bsd-hardware.info/?probe=7833b60865) | May 05, 2023 |
| Dell          | 0252PH A04                  | [0cc9ef6521](https://bsd-hardware.info/?probe=0cc9ef6521) | May 03, 2023 |
| Dell          | 0252PH A04                  | [acaf59c3d5](https://bsd-hardware.info/?probe=acaf59c3d5) | May 03, 2023 |
| HP            | 82B4                        | [244817e203](https://bsd-hardware.info/?probe=244817e203) | May 02, 2023 |
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
| Gigabyte      | B250M-Gaming 3-CF           | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
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
| amd64 | 134      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 133      | 99.25%  |
| GNOME        | 1        | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 134      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 134      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 52       | 38.52%  |
| fr_FR   | 43       | 31.85%  |
| es_ES   | 9        | 6.67%   |
| ru_RU   | 8        | 5.93%   |
| de_DE   | 8        | 5.93%   |
| it_IT   | 4        | 2.96%   |
| Unknown | 3        | 2.22%   |
| pt_BR   | 2        | 1.48%   |
| pl_PL   | 2        | 1.48%   |
| jp_JP   | 2        | 1.48%   |
| fr      | 1        | 0.74%   |
| es      | 1        | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 131      | 97.76%  |
| BIOS | 3        | 2.24%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 78       | 56.93%  |
| Zfs    | 59       | 43.07%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 131      | 97.76%  |
| MBR  | 3        | 2.24%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 33       | 24.63%  |
| Gigabyte Technology | 22       | 16.42%  |
| Dell                | 14       | 10.45%  |
| Hewlett-Packard     | 13       | 9.7%    |
| MSI                 | 8        | 5.97%   |
| Lenovo              | 8        | 5.97%   |
| Intel               | 5        | 3.73%   |
| ASRock              | 5        | 3.73%   |
| Unknown             | 5        | 3.73%   |
| Acer                | 4        | 2.99%   |
| T-bao               | 2        | 1.49%   |
| Fujitsu Siemens     | 2        | 1.49%   |
| Fujitsu             | 2        | 1.49%   |
| Foxconn             | 2        | 1.49%   |
| AZW                 | 2        | 1.49%   |
| Pegatron            | 1        | 0.75%   |
| LG Electronics      | 1        | 0.75%   |
| Huanan              | 1        | 0.75%   |
| Google              | 1        | 0.75%   |
| Biostar             | 1        | 0.75%   |
| BESSTAR Tech        | 1        | 0.75%   |
| Axiomtek            | 1        | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 5        | 3.73%   |
| T-bao MINI PC                       | 2        | 1.49%   |
| MSI MS-7788                         | 2        | 1.49%   |
| HP EliteDesk 800 G2 DM 35W          | 2        | 1.49%   |
| HP Compaq Elite 8300 USDT           | 2        | 1.49%   |
| ASUS ROG STRIX B550-F GAMING        | 2        | 1.49%   |
| ASUS PRIME B250M-A                  | 2        | 1.49%   |
| ASUS All Series                     | 2        | 1.49%   |
| Pegatron Compaq dx2450 Microtower   | 1        | 0.75%   |
| MSI MS-7C95                         | 1        | 0.75%   |
| MSI MS-7C51                         | 1        | 0.75%   |
| MSI MS-7C09                         | 1        | 0.75%   |
| MSI MS-7B86                         | 1        | 0.75%   |
| MSI MS-7599                         | 1        | 0.75%   |
| MSI Compaq dx2200 MT                | 1        | 0.75%   |
| LG R590-K.AAA9BT                    | 1        | 0.75%   |
| Lenovo ThinkCentre M900 10FLS15P00  | 1        | 0.75%   |
| Lenovo ThinkCentre M900 10FGS05C08  | 1        | 0.75%   |
| Lenovo ThinkCentre M75e 5065A11     | 1        | 0.75%   |
| Lenovo ThinkCentre M73 10AYA06EIA   | 1        | 0.75%   |
| Lenovo ThinkCentre M73 10AXS34800   | 1        | 0.75%   |
| Lenovo ThinkCentre M710s 10M8S0FW00 | 1        | 0.75%   |
| Lenovo ThinkCentre M58p 6138DK1     | 1        | 0.75%   |
| Lenovo ThinkCentre Edge72 34971B1   | 1        | 0.75%   |
| Intel X99                           | 1        | 0.75%   |
| Intel H81                           | 1        | 0.75%   |
| Intel DH87RL AAG74240-400           | 1        | 0.75%   |
| Intel DG41TY AAE47335-300           | 1        | 0.75%   |
| Intel DB85FL AAG89861-203           | 1        | 0.75%   |
| Huanan X99-TF GAMING V3.0           | 1        | 0.75%   |
| HP Slim Desktop S01-pF1xxx          | 1        | 0.75%   |
| HP rp5800                           | 1        | 0.75%   |
| HP ProDesk 600 G3 SFF               | 1        | 0.75%   |
| HP ProDesk 600 G1 DM                | 1        | 0.75%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 0.75%   |
| HP EliteDesk 800 G2 SFF             | 1        | 0.75%   |
| HP EliteDesk 800 G2 DM 65W          | 1        | 0.75%   |
| HP Compaq Elite 8300 SFF            | 1        | 0.75%   |
| HP 290 G1 MT                        | 1        | 0.75%   |
| Google Panther                      | 1        | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 11       | 8.21%   |
| Lenovo ThinkCentre      | 8        | 5.97%   |
| Dell OptiPlex           | 7        | 5.22%   |
| ASUS ROG                | 7        | 5.22%   |
| Unknown                 | 5        | 3.73%   |
| HP EliteDesk            | 4        | 2.99%   |
| HP Compaq               | 3        | 2.24%   |
| Dell Precision          | 3        | 2.24%   |
| T-bao MINI              | 2        | 1.49%   |
| MSI MS-7788             | 2        | 1.49%   |
| HP ProDesk              | 2        | 1.49%   |
| Gigabyte B450M          | 2        | 1.49%   |
| Fujitsu Siemens ESPRIMO | 2        | 1.49%   |
| Dell Vostro             | 2        | 1.49%   |
| Dell Inspiron           | 2        | 1.49%   |
| ASUS TUF                | 2        | 1.49%   |
| ASUS All                | 2        | 1.49%   |
| Acer Veriton            | 2        | 1.49%   |
| Pegatron Compaq         | 1        | 0.75%   |
| MSI MS-7C95             | 1        | 0.75%   |
| MSI MS-7C51             | 1        | 0.75%   |
| MSI MS-7C09             | 1        | 0.75%   |
| MSI MS-7B86             | 1        | 0.75%   |
| MSI MS-7599             | 1        | 0.75%   |
| MSI Compaq              | 1        | 0.75%   |
| LG R590-K.AAA9BT        | 1        | 0.75%   |
| Intel X99               | 1        | 0.75%   |
| Intel H81               | 1        | 0.75%   |
| Intel DH87RL            | 1        | 0.75%   |
| Intel DG41TY            | 1        | 0.75%   |
| Intel DB85FL            | 1        | 0.75%   |
| Huanan X99-TF           | 1        | 0.75%   |
| HP Slim                 | 1        | 0.75%   |
| HP rp5800               | 1        | 0.75%   |
| HP Pavilion             | 1        | 0.75%   |
| HP 290                  | 1        | 0.75%   |
| Google Panther          | 1        | 0.75%   |
| Gigabyte Z87X-UD4H      | 1        | 0.75%   |
| Gigabyte Z490           | 1        | 0.75%   |
| Gigabyte X58A-UD3R      | 1        | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 16       | 11.94%  |
| 2013    | 14       | 10.45%  |
| 2022    | 13       | 9.7%    |
| 2020    | 13       | 9.7%    |
| 2012    | 11       | 8.21%   |
| 2019    | 8        | 5.97%   |
| 2018    | 8        | 5.97%   |
| 2014    | 8        | 5.97%   |
| 2010    | 8        | 5.97%   |
| 2017    | 7        | 5.22%   |
| 2016    | 5        | 3.73%   |
| 2011    | 5        | 3.73%   |
| 2015    | 4        | 2.99%   |
| 2009    | 4        | 2.99%   |
| 2023    | 3        | 2.24%   |
| 2008    | 3        | 2.24%   |
| 2006    | 2        | 1.49%   |
| 2007    | 1        | 0.75%   |
| Unknown | 1        | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 134      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 133      | 99.25%  |
| Yes  | 1        | 0.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 48       | 35.82%  |
| 16.01-24.0  | 38       | 28.36%  |
| 4.01-8.0    | 24       | 17.91%  |
| 32.01-64.0  | 13       | 9.7%    |
| 2.01-3.0    | 4        | 2.99%   |
| 64.01-256.0 | 3        | 2.24%   |
| 24.01-32.0  | 2        | 1.49%   |
| 3.01-4.0    | 1        | 0.75%   |
| 0.51-1.0    | 1        | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 61       | 44.85%  |
| 0.51-1.0 | 49       | 36.03%  |
| 1.01-2.0 | 18       | 13.24%  |
| 2.01-3.0 | 7        | 5.15%   |
| 3.01-4.0 | 1        | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 63       | 47.01%  |
| 2      | 33       | 24.63%  |
| 3      | 18       | 13.43%  |
| 0      | 8        | 5.97%   |
| 5      | 6        | 4.48%   |
| 9      | 2        | 1.49%   |
| 4      | 2        | 1.49%   |
| 7      | 1        | 0.75%   |
| 6      | 1        | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 61.94%  |
| Yes       | 51       | 38.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 129      | 96.27%  |
| No        | 5        | 3.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 89       | 65.93%  |
| Yes       | 46       | 34.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 98       | 73.13%  |
| Yes       | 36       | 26.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| Russia             | 18       | 13.43%  |
| USA                | 14       | 10.45%  |
| Spain              | 10       | 7.46%   |
| Germany            | 9        | 6.72%   |
| Italy              | 6        | 4.48%   |
| Romania            | 5        | 3.73%   |
| Poland             | 5        | 3.73%   |
| Hungary            | 5        | 3.73%   |
| Canada             | 5        | 3.73%   |
| Brazil             | 5        | 3.73%   |
| Serbia             | 4        | 2.99%   |
| France             | 4        | 2.99%   |
| UK                 | 3        | 2.24%   |
| Turkey             | 3        | 2.24%   |
| Peru               | 3        | 2.24%   |
| Belgium            | 3        | 2.24%   |
| Australia          | 3        | 2.24%   |
| Ukraine            | 2        | 1.49%   |
| Sweden             | 2        | 1.49%   |
| Mexico             | 2        | 1.49%   |
| Japan              | 2        | 1.49%   |
| India              | 2        | 1.49%   |
| China              | 2        | 1.49%   |
| Bulgaria           | 2        | 1.49%   |
| Argentina          | 2        | 1.49%   |
| Switzerland        | 1        | 0.75%   |
| South Korea        | 1        | 0.75%   |
| Slovenia           | 1        | 0.75%   |
| San Marino         | 1        | 0.75%   |
| Netherlands        | 1        | 0.75%   |
| Kazakhstan         | 1        | 0.75%   |
| Indonesia          | 1        | 0.75%   |
| Dominican Republic | 1        | 0.75%   |
| Croatia            | 1        | 0.75%   |
| Chile              | 1        | 0.75%   |
| Belarus            | 1        | 0.75%   |
| Austria            | 1        | 0.75%   |
| Algeria            | 1        | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| St. Jean Baptiste     | 3        | 2.22%   |
| Moscow                | 3        | 2.22%   |
| Sydney                | 2        | 1.48%   |
| Madrid                | 2        | 1.48%   |
| Kirov                 | 2        | 1.48%   |
| Brooklyn              | 2        | 1.48%   |
| Berlin                | 2        | 1.48%   |
| Belgrade              | 2        | 1.48%   |
| Zurich                | 1        | 0.74%   |
| Zhengzhou             | 1        | 0.74%   |
| Yokohama              | 1        | 0.74%   |
| Warsaw                | 1        | 0.74%   |
| Volgodonsk            | 1        | 0.74%   |
| Vogogna               | 1        | 0.74%   |
| Virovitica            | 1        | 0.74%   |
| Villena               | 1        | 0.74%   |
| Vienna                | 1        | 0.74%   |
| Venice                | 1        | 0.74%   |
| Vecses                | 1        | 0.74%   |
| Valderrobres          | 1        | 0.74%   |
| Ubstadt-Weiher        | 1        | 0.74%   |
| Tucson                | 1        | 0.74%   |
| Trumbull              | 1        | 0.74%   |
| Trekhgornyy           | 1        | 0.74%   |
| Topolovgrad           | 1        | 0.74%   |
| Tolmin                | 1        | 0.74%   |
| Timișoara            | 1        | 0.74%   |
| Stevenage             | 1        | 0.74%   |
| St Petersburg         | 1        | 0.74%   |
| Sopron                | 1        | 0.74%   |
| Sofia                 | 1        | 0.74%   |
| Siheung-si            | 1        | 0.74%   |
| Semlin                | 1        | 0.74%   |
| Schweinfurt           | 1        | 0.74%   |
| Saskatoon             | 1        | 0.74%   |
| Saransk               | 1        | 0.74%   |
| Sao Paulo             | 1        | 0.74%   |
| Sao Jose do Rio Preto | 1        | 0.74%   |
| Santo Domingo Este    | 1        | 0.74%   |
| Santiago              | 1        | 0.74%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 41       | 61     | 19.34%  |
| Samsung Electronics | 30       | 46     | 14.15%  |
| Seagate             | 28       | 33     | 13.21%  |
| Kingston            | 24       | 24     | 11.32%  |
| Toshiba             | 12       | 14     | 5.66%   |
| SanDisk             | 8        | 8      | 3.77%   |
| Crucial             | 6        | 7      | 2.83%   |
| A-DATA Technology   | 6        | 7      | 2.83%   |
| China               | 5        | 6      | 2.36%   |
| Patriot             | 4        | 4      | 1.89%   |
| Micron Technology   | 4        | 5      | 1.89%   |
| Maxtor              | 4        | 4      | 1.89%   |
| Hitachi             | 4        | 4      | 1.89%   |
| Transcend           | 3        | 3      | 1.42%   |
| KingSpec            | 3        | 3      | 1.42%   |
| Team                | 2        | 2      | 0.94%   |
| PNY                 | 2        | 2      | 0.94%   |
| Vaseky              | 1        | 1      | 0.47%   |
| SPCC                | 1        | 1      | 0.47%   |
| Silicon Motion      | 1        | 1      | 0.47%   |
| SETHRISE            | 1        | 1      | 0.47%   |
| QUANTUM             | 1        | 1      | 0.47%   |
| Pioneer             | 1        | 1      | 0.47%   |
| Philips             | 1        | 1      | 0.47%   |
| Palit               | 1        | 1      | 0.47%   |
| OCZ                 | 1        | 1      | 0.47%   |
| Netac               | 1        | 1      | 0.47%   |
| LITEONIT            | 1        | 1      | 0.47%   |
| Kston               | 1        | 1      | 0.47%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.47%   |
| KIOXIA              | 1        | 1      | 0.47%   |
| Intenso             | 1        | 1      | 0.47%   |
| Intel               | 1        | 1      | 0.47%   |
| HGST                | 1        | 1      | 0.47%   |
| GOODRAM             | 1        | 1      | 0.47%   |
| Gigabyte Technology | 1        | 2      | 0.47%   |
| EDGE                | 1        | 1      | 0.47%   |
| Corsair             | 1        | 1      | 0.47%   |
| Colorful            | 1        | 1      | 0.47%   |
| ASint Technology    | 1        | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 6        | 2.41%   |
| Seagate ST500DM002-1BD142 500GB | 5        | 2.01%   |
| Seagate ST3500418AS 500GB       | 4        | 1.61%   |
| Samsung SSD 850 EVO 250GB       | 4        | 1.61%   |
| WDC WD10EZEX-08WN4A0 1TB        | 3        | 1.2%    |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 1.2%    |
| Seagate ST1000DM010-2EP102 1TB  | 3        | 1.2%    |
| Samsung SSD 980 1TB             | 3        | 1.2%    |
| Samsung SSD 870 EVO 500GB       | 3        | 1.2%    |
| Samsung SSD 860 EVO 500GB       | 3        | 1.2%    |
| WDC WDS240G2G0A-00JH30 240GB    | 2        | 0.8%    |
| WDC WDS120G2G0A-00JH30 120GB    | 2        | 0.8%    |
| WDC WD5000AAKX-08U6AA0 500GB    | 2        | 0.8%    |
| WDC WD10EZEX-60WN4A0 1TB        | 2        | 0.8%    |
| Toshiba DT01ACA100 1TB          | 2        | 0.8%    |
| Toshiba DT01ACA050 500GB        | 2        | 0.8%    |
| Samsung SSD 980 PRO 500GB       | 2        | 0.8%    |
| Samsung SSD 970 PRO 512GB       | 2        | 0.8%    |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 0.8%    |
| Patriot Burst Elite 120GB       | 2        | 0.8%    |
| Kingston SHFS37A240G 240GB      | 2        | 0.8%    |
| Kingston SA400S37480G 480GB     | 2        | 0.8%    |
| Kingston SA400S37120G 120GB     | 2        | 0.8%    |
| Crucial CT240BX500SSD1 240GB    | 2        | 0.8%    |
| WDC WDS500G2B0A-00SM50 500GB    | 1        | 0.4%    |
| WDC WDS500G1B0A-00H9H0 500GB    | 1        | 0.4%    |
| WDC WDS250G1B0A-00H9H0 250GB    | 1        | 0.4%    |
| WDC WD800JD-75MSA3 80GB         | 1        | 0.4%    |
| WDC WD7501AALS-00J7B0 752GB     | 1        | 0.4%    |
| WDC WD6400BPVT-22HXZT3 640GB    | 1        | 0.4%    |
| WDC WD60EZRX-00MVLB1 6TB        | 1        | 0.4%    |
| WDC WD50NDZW-11A8JS1 5TB        | 1        | 0.4%    |
| WDC WD5003AZEX-00K1GA0 500GB    | 1        | 0.4%    |
| WDC WD5000LPCX-21VHAT0 500GB    | 1        | 0.4%    |
| WDC WD5000AZRX-00A8LB0 500GB    | 1        | 0.4%    |
| WDC WD5000AVVS-00ZWB0 500GB     | 1        | 0.4%    |
| WDC WD5000AAKX-00ERMA0 500GB    | 1        | 0.4%    |
| WDC WD5000AAKX-001CA0 500GB     | 1        | 0.4%    |
| WDC WD42PURZ-85B4YY0 4TB        | 1        | 0.4%    |
| WDC WD40EZAZ-00ZGHB0 4TB        | 1        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 35       | 54     | 41.18%  |
| Seagate             | 28       | 33     | 32.94%  |
| Toshiba             | 9        | 11     | 10.59%  |
| Maxtor              | 4        | 4      | 4.71%   |
| Hitachi             | 4        | 4      | 4.71%   |
| Samsung Electronics | 2        | 3      | 2.35%   |
| QUANTUM             | 1        | 1      | 1.18%   |
| HGST                | 1        | 1      | 1.18%   |
| Apple               | 1        | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 24     | 17.71%  |
| Kingston            | 17       | 17     | 17.71%  |
| SanDisk             | 8        | 8      | 8.33%   |
| WDC                 | 7        | 7      | 7.29%   |
| Crucial             | 5        | 6      | 5.21%   |
| China               | 5        | 6      | 5.21%   |
| Patriot             | 4        | 4      | 4.17%   |
| Transcend           | 3        | 3      | 3.13%   |
| Toshiba             | 3        | 3      | 3.13%   |
| KingSpec            | 3        | 3      | 3.13%   |
| A-DATA Technology   | 3        | 3      | 3.13%   |
| PNY                 | 2        | 2      | 2.08%   |
| Vaseky              | 1        | 1      | 1.04%   |
| Team                | 1        | 1      | 1.04%   |
| SPCC                | 1        | 1      | 1.04%   |
| SETHRISE            | 1        | 1      | 1.04%   |
| Pioneer             | 1        | 1      | 1.04%   |
| Philips             | 1        | 1      | 1.04%   |
| Palit               | 1        | 1      | 1.04%   |
| OCZ                 | 1        | 1      | 1.04%   |
| Micron Technology   | 1        | 1      | 1.04%   |
| LITEONIT            | 1        | 1      | 1.04%   |
| Kston               | 1        | 1      | 1.04%   |
| KIOXIA-EXCERIA      | 1        | 1      | 1.04%   |
| Intenso             | 1        | 1      | 1.04%   |
| Intel               | 1        | 1      | 1.04%   |
| GOODRAM             | 1        | 1      | 1.04%   |
| Gigabyte Technology | 1        | 2      | 1.04%   |
| EDGE                | 1        | 1      | 1.04%   |
| Apacer              | 1        | 1      | 1.04%   |
| AMD                 | 1        | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 74       | 106    | 40.88%  |
| HDD  | 72       | 112    | 39.78%  |
| NVMe | 35       | 42     | 19.34%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 120      | 218    | 77.42%  |
| NVMe | 35       | 42     | 22.58%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 100      | 150    | 65.79%  |
| 0.51-1.0   | 29       | 33     | 19.08%  |
| 1.01-2.0   | 11       | 19     | 7.24%   |
| 3.01-4.0   | 7        | 8      | 4.61%   |
| 2.01-3.0   | 2        | 5      | 1.32%   |
| 4.01-10.0  | 2        | 2      | 1.32%   |
| 10.01-20.0 | 1        | 1      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 75       | 55.15%  |
| 101-250    | 19       | 13.97%  |
| 51-100     | 17       | 12.5%   |
| 251-500    | 16       | 11.76%  |
| 501-1000   | 7        | 5.15%   |
| 21-50      | 1        | 0.74%   |
| Unknown    | 1        | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 132      | 98.51%  |
| 21-50   | 1        | 0.75%   |
| Unknown | 1        | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| WDC WD800JD-75MSA3 80GB                    | 1        | 1      | 3.03%   |
| WDC WD6400BPVT-22HXZT3 640GB               | 1        | 1      | 3.03%   |
| WDC WD5000AAKX-08U6AA0 500GB               | 1        | 1      | 3.03%   |
| WDC WD5000AAKX-00ERMA0 500GB               | 1        | 1      | 3.03%   |
| WDC WD30EFRX-68EUZN0 3TB                   | 1        | 1      | 3.03%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1        | 1      | 3.03%   |
| WDC WD1600YS-01SHB1 164GB                  | 1        | 1      | 3.03%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 1      | 3.03%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1        | 1      | 3.03%   |
| WDC WD10EARS-003BB1 1TB                    | 1        | 1      | 3.03%   |
| Toshiba MK3259GSXP 320GB                   | 1        | 1      | 3.03%   |
| Toshiba DT01ACA100 1TB                     | 1        | 1      | 3.03%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB  | 1        | 1      | 3.03%   |
| Seagate ST500LM000-1EJ162 500GB            | 1        | 1      | 3.03%   |
| Seagate ST500DM002-1BD142 500GB            | 1        | 1      | 3.03%   |
| Seagate ST380215AS 80GB                    | 1        | 1      | 3.03%   |
| Seagate ST3750528AS 752GB                  | 1        | 1      | 3.03%   |
| Seagate ST3500418AS 500GB                  | 1        | 1      | 3.03%   |
| Seagate ST3500320AS 500GB                  | 1        | 1      | 3.03%   |
| Seagate ST3320620AS 320GB                  | 1        | 1      | 3.03%   |
| Seagate ST2000DM008-2FR102 2TB             | 1        | 1      | 3.03%   |
| Seagate ST1000DM010-2EP102 1TB             | 1        | 1      | 3.03%   |
| Samsung Electronics MZVL22T0HBLB-00B00 2TB | 1        | 1      | 3.03%   |
| Samsung Electronics HD103SJ 1TB            | 1        | 1      | 3.03%   |
| Maxtor 6Y080M0 82GB                        | 1        | 1      | 3.03%   |
| Maxtor 6V080E0 80GB                        | 1        | 1      | 3.03%   |
| Maxtor 6L080P0 82GB                        | 1        | 1      | 3.03%   |
| Kingston SA400S37240G 240GB                | 1        | 1      | 3.03%   |
| Hitachi HTS725050A7E630 500GB              | 1        | 1      | 3.03%   |
| Hitachi HTS541680J9SA00 80GB               | 1        | 1      | 3.03%   |
| HGST HTS545050A7E680 500GB                 | 1        | 1      | 3.03%   |
| Crucial CT1050MX300SSD1 1TB                | 1        | 1      | 3.03%   |
| China SH00R120GB                           | 1        | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 10     | 32.26%  |
| Seagate             | 7        | 9      | 22.58%  |
| Maxtor              | 3        | 3      | 9.68%   |
| Toshiba             | 2        | 2      | 6.45%   |
| Samsung Electronics | 2        | 2      | 6.45%   |
| Hitachi             | 2        | 2      | 6.45%   |
| Silicon Motion      | 1        | 1      | 3.23%   |
| Kingston            | 1        | 1      | 3.23%   |
| HGST                | 1        | 1      | 3.23%   |
| Crucial             | 1        | 1      | 3.23%   |
| China               | 1        | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 10     | 38.46%  |
| Seagate             | 7        | 9      | 26.92%  |
| Maxtor              | 3        | 3      | 11.54%  |
| Toshiba             | 2        | 2      | 7.69%   |
| Hitachi             | 2        | 2      | 7.69%   |
| Samsung Electronics | 1        | 1      | 3.85%   |
| HGST                | 1        | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 28     | 83.87%  |
| SSD  | 3        | 3      | 9.68%   |
| NVMe | 2        | 2      | 6.45%   |

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
| Works    | 106      | 213    | 73.1%   |
| Malfunc  | 31       | 33     | 21.38%  |
| Detected | 5        | 11     | 3.45%   |
| Failed   | 3        | 3      | 2.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 96       | 53.04%  |
| AMD                         | 32       | 17.68%  |
| Samsung Electronics         | 15       | 8.29%   |
| Kingston Technology Company | 7        | 3.87%   |
| Nvidia                      | 4        | 2.21%   |
| Marvell Technology Group    | 4        | 2.21%   |
| ASMedia Technology          | 4        | 2.21%   |
| Silicon Motion              | 3        | 1.66%   |
| Micron Technology           | 3        | 1.66%   |
| Realtek Semiconductor       | 2        | 1.1%    |
| JMicron Technology          | 2        | 1.1%    |
| ADATA Technology            | 2        | 1.1%    |
| VIA Technologies            | 1        | 0.55%   |
| Sandisk                     | 1        | 0.55%   |
| Phison Electronics          | 1        | 0.55%   |
| OCZ Technology Group        | 1        | 0.55%   |
| Micron/Crucial Technology   | 1        | 0.55%   |
| KIOXIA                      | 1        | 0.55%   |
| Broadcom / LSI              | 1        | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 6.76%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 13       | 5.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11       | 4.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 4.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8        | 3.6%    |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 3.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 3.15%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 2.7%    |
| Samsung NVMe SSD Controller 980                                                         | 5        | 2.25%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.8%    |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4        | 1.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4        | 1.8%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4        | 1.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 1.35%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.35%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.35%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.35%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3        | 1.35%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3        | 1.35%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.35%   |
| Realtek NVMe Controller                                                                 | 2        | 0.9%    |
| Nvidia MCP61 IDE                                                                        | 2        | 0.9%    |
| Micron 2200S NVMe SSD                                                                   | 2        | 0.9%    |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 2        | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 0.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.9%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 0.9%    |
| AMD FCH SATA Controller D                                                               | 2        | 0.9%    |
| AMD 300 Series Chipset SATA Controller                                                  | 2        | 0.9%    |
| Unknown                                                                                 | 2        | 0.9%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 1        | 0.45%   |
| Sandisk WD Black SN770 NVMe SSD                                                         | 1        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 105      | 59.66%  |
| NVMe | 34       | 19.32%  |
| IDE  | 28       | 15.91%  |
| RAID | 7        | 3.98%   |
| SAS  | 1        | 0.57%   |
| SCSI | 1        | 0.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 98       | 73.13%  |
| AMD    | 36       | 26.87%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz              | 4        | 2.99%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3        | 2.24%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3        | 2.24%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 3        | 2.24%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 2.24%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3        | 2.24%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 3        | 2.24%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2        | 1.49%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2        | 1.49%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 2        | 1.49%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2        | 1.49%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2        | 1.49%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 2        | 1.49%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2        | 1.49%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2        | 1.49%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 2        | 1.49%   |
| Intel 12th Gen Core i5-12400                  | 2        | 1.49%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2        | 1.49%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2        | 1.49%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1        | 0.75%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1        | 0.75%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1        | 0.75%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz           | 1        | 0.75%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz           | 1        | 0.75%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz           | 1        | 0.75%   |
| Intel Xeon                                    | 1        | 0.75%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1        | 0.75%   |
| Intel Pentium Dual-Core CPU E5300             | 1        | 0.75%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1        | 0.75%   |
| Intel Pentium CPU G3240T @ 2.70GHz            | 1        | 0.75%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 1        | 0.75%   |
| Intel Pentium 4 CPU                           | 1        | 0.75%   |
| Intel Core i9-10900 CPU @ 2.80GHz             | 1        | 0.75%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1        | 0.75%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1        | 0.75%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1        | 0.75%   |
| Intel Core i7-4771 CPU @ 3.50GHz              | 1        | 0.75%   |
| Intel Core i7-4770S CPU @ 3.10GHz             | 1        | 0.75%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1        | 0.75%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1        | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 29       | 21.64%  |
| Intel Core i3           | 22       | 16.42%  |
| Intel Core i7           | 13       | 9.7%    |
| AMD Ryzen 5             | 11       | 8.21%   |
| Intel Celeron           | 10       | 7.46%   |
| Intel Xeon              | 7        | 5.22%   |
| AMD Ryzen 7             | 5        | 3.73%   |
| AMD Ryzen 3             | 5        | 3.73%   |
| Other                   | 4        | 2.99%   |
| Intel Core 2 Duo        | 4        | 2.99%   |
| Intel Pentium           | 3        | 2.24%   |
| AMD Phenom II X4        | 3        | 2.24%   |
| Intel Core 2 Quad       | 2        | 1.49%   |
| AMD Athlon II X2        | 2        | 1.49%   |
| AMD A4                  | 2        | 1.49%   |
| Intel Pentium Gold      | 1        | 0.75%   |
| Intel Pentium Dual-Core | 1        | 0.75%   |
| Intel Pentium 4         | 1        | 0.75%   |
| Intel Core i9           | 1        | 0.75%   |
| AMD Ryzen 9             | 1        | 0.75%   |
| AMD Phenom II X2        | 1        | 0.75%   |
| AMD FX                  | 1        | 0.75%   |
| AMD E                   | 1        | 0.75%   |
| AMD Athlon X2           | 1        | 0.75%   |
| AMD Athlon II X4        | 1        | 0.75%   |
| AMD Athlon 64           | 1        | 0.75%   |
| AMD A10                 | 1        | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 59       | 44.03%  |
| 2       | 36       | 26.87%  |
| 6       | 12       | 8.96%   |
| 12      | 9        | 6.72%   |
| 8       | 6        | 4.48%   |
| 16      | 4        | 2.99%   |
| Unknown | 4        | 2.99%   |
| 1       | 2        | 1.49%   |
| 24      | 1        | 0.75%   |
| 10      | 1        | 0.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 132      | 98.51%  |
| 2      | 2        | 1.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 83       | 61.94%  |
| 2       | 46       | 34.33%  |
| Unknown | 5        | 3.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 20       | 14.93%  |
| KabyLake      | 16       | 11.94%  |
| IvyBridge     | 14       | 10.45%  |
| Skylake       | 11       | 8.21%   |
| Zen+          | 9        | 6.72%   |
| Zen 3         | 8        | 5.97%   |
| SandyBridge   | 8        | 5.97%   |
| K10           | 8        | 5.97%   |
| Penryn        | 6        | 4.48%   |
| CometLake     | 5        | 3.73%   |
| Unknown       | 5        | 3.73%   |
| Zen           | 4        | 2.99%   |
| Piledriver    | 3        | 2.24%   |
| Nehalem       | 3        | 2.24%   |
| Core          | 3        | 2.24%   |
| Silvermont    | 2        | 1.49%   |
| Goldmont plus | 2        | 1.49%   |
| Zen 2         | 1        | 0.75%   |
| Westmere      | 1        | 0.75%   |
| NetBurst      | 1        | 0.75%   |
| K8 Hammer     | 1        | 0.75%   |
| Goldmont      | 1        | 0.75%   |
| Bulldozer     | 1        | 0.75%   |
| Bobcat        | 1        | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 65       | 45.14%  |
| Nvidia                     | 41       | 28.47%  |
| AMD                        | 37       | 25.69%  |
| Matrox Electronics Systems | 1        | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                       | 9        | 6.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 4.79%   |
| Intel HD Graphics 630                                                       | 7        | 4.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 4.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 4.11%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 4.11%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 3.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 3.42%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 2.74%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 2.05%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 2.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 2.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 2.05%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.37%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.37%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 1.37%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.37%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.37%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.37%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 1.37%   |
| AMD RS880 [Radeon HD 4250]                                                  | 2        | 1.37%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.37%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.37%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.37%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.68%   |
| Nvidia GT218M [GeForce 310M]                                                | 1        | 0.68%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.68%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.68%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.68%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 0.68%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 0.68%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 0.68%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 0.68%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 0.68%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 0.68%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 50       | 36.76%  |
| 1 x Nvidia     | 37       | 27.21%  |
| 1 x AMD        | 30       | 22.06%  |
| Intel + AMD    | 7        | 5.15%   |
| 2 x Intel      | 5        | 3.68%   |
| Intel + Nvidia | 4        | 2.94%   |
| Other          | 1        | 0.74%   |
| 2 x AMD        | 1        | 0.74%   |
| 1 x Matrox     | 1        | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 102      | 75.56%  |
| Proprietary | 30       | 22.22%  |
| Unknown     | 3        | 2.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 84       | 62.22%  |
| 3.01-4.0   | 15       | 11.11%  |
| 1.01-2.0   | 13       | 9.63%   |
| 0.51-1.0   | 7        | 5.19%   |
| 5.01-6.0   | 6        | 4.44%   |
| 0.01-0.5   | 6        | 4.44%   |
| 7.01-8.0   | 2        | 1.48%   |
| 2.01-3.0   | 1        | 0.74%   |
| 8.01-16.0  | 1        | 0.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Acer                 | 6        | 14.29%  |
| Samsung Electronics  | 4        | 9.52%   |
| Hewlett-Packard      | 4        | 9.52%   |
| Dell                 | 4        | 9.52%   |
| BenQ                 | 4        | 9.52%   |
| Philips              | 3        | 7.14%   |
| Ancor Communications | 3        | 7.14%   |
| LG Electronics       | 2        | 4.76%   |
| Unknown              | 2        | 4.76%   |
| Semp Toshiba         | 1        | 2.38%   |
| PKB                  | 1        | 2.38%   |
| NEC Computers        | 1        | 2.38%   |
| Microstep            | 1        | 2.38%   |
| Lenovo               | 1        | 2.38%   |
| Idek Iiyama          | 1        | 2.38%   |
| Goldstar             | 1        | 2.38%   |
| AUS                  | 1        | 2.38%   |
| ASUSTek Computer     | 1        | 2.38%   |
| AOC                  | 1        | 2.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                     | 2        | 4.76%   |
| Unknown                                                               | 2        | 4.76%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch             | 1        | 2.38%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch  | 1        | 2.38%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 1        | 2.38%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch     | 1        | 2.38%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch      | 1        | 2.38%   |
| PKB LCD Monitor MAE200W 1680x1050                                     | 1        | 2.38%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch               | 1        | 2.38%   |
| Philips PHL 221S8L PHL091C 1920x1080 480x270mm 21.7-inch              | 1        | 2.38%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                     | 1        | 2.38%   |
| NEC Computers LCD Monitor 70GX2 1280x1024                             | 1        | 2.38%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                           | 1        | 2.38%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 1        | 2.38%   |
| LG Electronics LCD Monitor L1918S 1280x1024                           | 1        | 2.38%   |
| Lenovo L24e-30 LEN66BC 1920x1080 530x300mm 24.0-inch                  | 1        | 2.38%   |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160                            | 1        | 2.38%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 600x340mm 27.2-inch         | 1        | 2.38%   |
| Hewlett-Packard Z24nq HWP3239 2560x1440 530x300mm 24.0-inch           | 1        | 2.38%   |
| Hewlett-Packard L1955 HWP262C 1280x1024 380x300mm 19.1-inch           | 1        | 2.38%   |
| Hewlett-Packard 27o HPN342C 1920x1080 600x340mm 27.2-inch             | 1        | 2.38%   |
| Goldstar LG IPS QHD GSM5BC4 2560x1440 530x300mm 24.0-inch             | 1        | 2.38%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                     | 1        | 2.38%   |
| Dell LCD Monitor U2419HC 1920x1080                                    | 1        | 2.38%   |
| Dell LCD Monitor S2721D 2560x1440                                     | 1        | 2.38%   |
| Dell E2220H DELF119 1920x1080 480x270mm 21.7-inch                     | 1        | 2.38%   |
| BenQ LCD Monitor GW2780 1920x1080                                     | 1        | 2.38%   |
| BenQ LCD Monitor GW2260 1920x1080                                     | 1        | 2.38%   |
| BenQ GW2250H BNQ78BD 1920x1080 480x270mm 21.7-inch                    | 1        | 2.38%   |
| BenQ G900W BNQ7805 1440x900 410x260mm 19.1-inch                       | 1        | 2.38%   |
| AUS LCD Monitor ASUS VG247Q1A 1920x1080                               | 1        | 2.38%   |
| ASUSTek Computer VP247 AUS24DA 1920x1080 520x290mm 23.4-inch          | 1        | 2.38%   |
| AOC LCD Monitor 27B2 1920x1080                                        | 1        | 2.38%   |
| Ancor Communications LCD Monitor VX238                                | 1        | 2.38%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch  | 1        | 2.38%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 510x290mm 23.1-inch | 1        | 2.38%   |
| Acer LCD Monitor XV280K 3840x2160                                     | 1        | 2.38%   |
| Acer LCD Monitor XB273K GP 3840x2160                                  | 1        | 2.38%   |
| Acer LCD Monitor VG270U 2560x1440                                     | 1        | 2.38%   |
| Acer LCD Monitor KG251Q 3840x1080                                     | 1        | 2.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 50%     |
| 2560x1440 (QHD)    | 5        | 11.9%   |
| 1366x768 (WXGA)    | 3        | 7.14%   |
| 1280x1024 (SXGA)   | 3        | 7.14%   |
| 3840x2160 (4K)     | 2        | 4.76%   |
| Unknown            | 2        | 4.76%   |
| 5760x2160          | 1        | 2.38%   |
| 3840x1080          | 1        | 2.38%   |
| 1680x1050 (WSXGA+) | 1        | 2.38%   |
| 1600x900 (HD+)     | 1        | 2.38%   |
| 1440x900 (WXGA+)   | 1        | 2.38%   |
| 1024x768 (XGA)     | 1        | 2.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 42.5%   |
| 27      | 5        | 12.5%   |
| 24      | 5        | 12.5%   |
| 21      | 5        | 12.5%   |
| 19      | 3        | 7.5%    |
| 23      | 2        | 5%      |
| 18      | 2        | 5%      |
| 14      | 1        | 2.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 17       | 42.5%   |
| 501-600     | 12       | 30%     |
| 401-500     | 9        | 22.5%   |
| 351-400     | 1        | 2.5%    |
| 201-300     | 1        | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 20       | 50%     |
| Unknown | 17       | 42.5%   |
| 5/4     | 1        | 2.5%    |
| 4/3     | 1        | 2.5%    |
| 16/10   | 1        | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 17       | 42.5%   |
| 201-250        | 12       | 30%     |
| 301-350        | 5        | 12.5%   |
| 151-200        | 3        | 7.5%    |
| 141-150        | 2        | 5%      |
| 101-110        | 1        | 2.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 42.5%   |
| 51-100  | 15       | 37.5%   |
| 101-120 | 6        | 15%     |
| 121-160 | 2        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 109      | 81.34%  |
| 0     | 22       | 16.42%  |
| 2     | 3        | 2.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 81       | 47.37%  |
| Intel                    | 57       | 33.33%  |
| Qualcomm Atheros         | 10       | 5.85%   |
| Ralink Technology        | 4        | 2.34%   |
| TP-Link                  | 3        | 1.75%   |
| Ralink                   | 3        | 1.75%   |
| Broadcom                 | 3        | 1.75%   |
| Marvell Technology Group | 2        | 1.17%   |
| Huawei Technologies      | 2        | 1.17%   |
| Samsung Electronics      | 1        | 0.58%   |
| MediaTek                 | 1        | 0.58%   |
| Edimax Technology        | 1        | 0.58%   |
| D-Link                   | 1        | 0.58%   |
| Atheros                  | 1        | 0.58%   |
| Accton Technology        | 1        | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69       | 36.7%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 4.26%   |
| Intel Ethernet Controller I225-V                                  | 7        | 3.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 7        | 3.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5        | 2.66%   |
| Intel Ethernet Connection I217-V                                  | 5        | 2.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.6%    |
| Intel Wireless 3165                                               | 3        | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.6%    |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 1.06%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 1.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.06%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 1.06%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 1.06%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 1.06%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 1.06%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.06%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.06%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 1.06%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.06%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.06%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 2        | 1.06%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.53%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.53%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1        | 0.53%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.53%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                      | 1        | 0.53%   |
| Ralink RT3072 Wireless Adapter                                    | 1        | 0.53%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.53%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.53%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.53%   |
| Ralink RT2500 Wireless 802.11bg                                   | 1        | 0.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 0.53%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 27.45%  |
| Realtek Semiconductor | 13       | 25.49%  |
| Qualcomm Atheros      | 6        | 11.76%  |
| Ralink Technology     | 4        | 7.84%   |
| TP-Link               | 3        | 5.88%   |
| Ralink                | 3        | 5.88%   |
| Broadcom              | 3        | 5.88%   |
| MediaTek              | 1        | 1.96%   |
| Edimax Technology     | 1        | 1.96%   |
| D-Link                | 1        | 1.96%   |
| Atheros               | 1        | 1.96%   |
| Accton Technology     | 1        | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 5        | 9.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 5.77%   |
| Intel Wireless 3165                                                  | 3        | 5.77%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 3.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2        | 3.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2        | 3.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 3.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2        | 3.85%   |
| Intel Wi-Fi 6 AX200                                                  | 2        | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2        | 3.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2        | 3.85%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 1.92%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 1.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1        | 1.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 1.92%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                         | 1        | 1.92%   |
| Ralink RT3072 Wireless Adapter                                       | 1        | 1.92%   |
| Ralink MT7601U Wireless Adapter                                      | 1        | 1.92%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1        | 1.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1        | 1.92%   |
| Ralink RT2500 Wireless 802.11bg                                      | 1        | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 1.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 1        | 1.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1        | 1.92%   |
| Intel Wireless 8265 / 8275                                           | 1        | 1.92%   |
| Intel Wireless 8260                                                  | 1        | 1.92%   |
| Intel Wireless 7265                                                  | 1        | 1.92%   |
| Intel Wireless 7260                                                  | 1        | 1.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 1.92%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]             | 1        | 1.92%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.D1) [Realtek RTL8188ETV]   | 1        | 1.92%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 1.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1        | 1.92%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 1        | 1.92%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 1.92%   |
| Accton Arcadyan 802.11N Wireless Adapter                             | 1        | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 75       | 55.97%  |
| Intel                    | 49       | 36.57%  |
| Qualcomm Atheros         | 4        | 2.99%   |
| Marvell Technology Group | 2        | 1.49%   |
| Huawei Technologies      | 2        | 1.49%   |
| Samsung Electronics      | 1        | 0.75%   |
| Broadcom                 | 1        | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69       | 50.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 5.88%   |
| Intel Ethernet Controller I225-V                                  | 7        | 5.15%   |
| Intel Ethernet Connection (2) I219-LM                             | 7        | 5.15%   |
| Intel Ethernet Connection I217-V                                  | 5        | 3.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 2.21%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.21%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 2.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 1.47%   |
| Intel I211 Gigabit Network Connection                             | 2        | 1.47%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.47%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.47%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.47%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 2        | 1.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.74%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.74%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.74%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.74%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.74%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.74%   |
| Intel Ethernet Connection (5) I219-V                              | 1        | 0.74%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.74%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.74%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.74%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.74%   |
| Huawei USB Device                                                 | 1        | 0.74%   |
| Huawei Android ADB Interface                                      | 1        | 0.74%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1        | 0.74%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 129      | 73.71%  |
| WiFi     | 46       | 26.29%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 114      | 94.21%  |
| WiFi     | 7        | 5.79%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 91       | 67.41%  |
| 2     | 38       | 28.15%  |
| 0     | 4        | 2.96%   |
| 3     | 2        | 1.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 127      | 92.7%   |
| Yes  | 10       | 7.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 32.5%   |
| Realtek Semiconductor           | 8        | 20%     |
| Cambridge Silicon Radio         | 8        | 20%     |
| TP-Link                         | 2        | 5%      |
| IMC Networks                    | 2        | 5%      |
| ASUSTek Computer                | 2        | 5%      |
| Qualcomm Atheros Communications | 1        | 2.5%    |
| Primax Electronics              | 1        | 2.5%    |
| Fujitsu                         | 1        | 2.5%    |
| Broadcom                        | 1        | 2.5%    |
| Apple                           | 1        | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 8        | 20%     |
| Intel Bluetooth wireless interface                          | 7        | 17.5%   |
| Realtek Bluetooth Adapter                                   | 6        | 15%     |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2        | 5%      |
| Realtek  Bluetooth 4.2 Adapter                              | 2        | 5%      |
| Intel Wireless-AC 3168 Bluetooth                            | 2        | 5%      |
| Intel AX201 Bluetooth                                       | 2        | 5%      |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 2.5%    |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1        | 2.5%    |
| Intel AX210 Bluetooth                                       | 1        | 2.5%    |
| Intel AX200 Bluetooth                                       | 1        | 2.5%    |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS     | 1        | 2.5%    |
| IMC Networks MediaTek Bluetooth Adapter                     | 1        | 2.5%    |
| Fujitsu Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter  | 1        | 2.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1        | 2.5%    |
| ASUS USB-BT500                                              | 1        | 2.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 2.5%    |
| Apple Bluetooth Host Controller                             | 1        | 2.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 92       | 44.23%  |
| AMD                    | 48       | 23.08%  |
| Nvidia                 | 39       | 18.75%  |
| C-Media Electronics    | 12       | 5.77%   |
| Texas Instruments      | 4        | 1.92%   |
| Realtek Semiconductor  | 2        | 0.96%   |
| Creative Labs          | 2        | 0.96%   |
| Yamaha                 | 1        | 0.48%   |
| Razer USA              | 1        | 0.48%   |
| OPPO Electronics       | 1        | 0.48%   |
| KTMicro                | 1        | 0.48%   |
| Hewlett-Packard        | 1        | 0.48%   |
| Generalplus Technology | 1        | 0.48%   |
| GEMBIRD                | 1        | 0.48%   |
| Edifier Technology     | 1        | 0.48%   |
| Unknown                | 1        | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17       | 6.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 4.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 4.92%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 4.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11       | 4.51%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10       | 4.1%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 8        | 3.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 2.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6        | 2.46%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 2.46%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 2.46%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 2.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 2.46%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 2.05%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5        | 2.05%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 2.05%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 4        | 1.64%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.23%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 1.23%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.23%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 1.23%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 1.23%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 2        | 0.82%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.82%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 0.82%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 0.82%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2        | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 0.82%   |
| AMD Trinity HDMI Audio Controller                                          | 2        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 32       | 20%     |
| Samsung Electronics | 21       | 13.13%  |
| Unknown             | 17       | 10.63%  |
| Corsair             | 14       | 8.75%   |
| Crucial             | 13       | 8.13%   |
| SK hynix            | 11       | 6.88%   |
| Micron Technology   | 8        | 5%      |
| G.Skill             | 8        | 5%      |
| Unknown             | 6        | 3.75%   |
| Ramaxel Technology  | 3        | 1.88%   |
| Patriot             | 3        | 1.88%   |
| Nanya Technology    | 3        | 1.88%   |
| A-DATA Technology   | 3        | 1.88%   |
| Unknown (ABCD)      | 2        | 1.25%   |
| Apacer              | 2        | 1.25%   |
| Transcend           | 1        | 0.63%   |
| Team                | 1        | 0.63%   |
| Smart               | 1        | 0.63%   |
| Qumo                | 1        | 0.63%   |
| MemoWise            | 1        | 0.63%   |
| Lexar               | 1        | 0.63%   |
| Kingmax             | 1        | 0.63%   |
| Juhor               | 1        | 0.63%   |
| GOODRAM             | 1        | 0.63%   |
| Golden Empire       | 1        | 0.63%   |
| Elpida              | 1        | 0.63%   |
| Avant               | 1        | 0.63%   |
| Atermiter           | 1        | 0.63%   |
| AMD                 | 1        | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 6        | 3.51%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 2        | 1.17%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                | 2        | 1.17%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                     | 2        | 1.17%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 2        | 1.17%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s            | 2        | 1.17%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                             | 2        | 1.17%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                       | 2        | 1.17%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                     | 2        | 1.17%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 2        | 1.17%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                   | 2        | 1.17%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 0.58%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                    | 1        | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1        | 0.58%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 1        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                               | 1        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                               | 1        | 0.58%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                     | 1        | 0.58%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                                | 1        | 0.58%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                | 1        | 0.58%   |
| Unknown RAM Module 1GB DIMM DDR2                                        | 1        | 0.58%   |
| Unknown RAM Module 1GB DIMM 400MT/s                                     | 1        | 0.58%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s                       | 1        | 0.58%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                              | 1        | 0.58%   |
| Smart RAM SH564128FH8N0QNSCG 4GB DIMM DDR3 1600MT/s                     | 1        | 0.58%   |
| SK hynix RAM Module 2GB DIMM DDR2 1639MT/s                              | 1        | 0.58%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                           | 1        | 0.58%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1333MT/s                    | 1        | 0.58%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB DIMM DDR3 1600MT/s                    | 1        | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                  | 1        | 0.58%   |
| SK hynix RAM HMT125U6AFP8C-G7 2GB DIMM DDR3 1066MT/s                    | 1        | 0.58%   |
| SK hynix RAM HMT125S6AFP8C-G7 2GB SODIMM DDR3 1067MT/s                  | 1        | 0.58%   |
| SK hynix RAM HMAA2GU6CJR8N-XN 16GB DIMM DDR4 2400MT/s                   | 1        | 0.58%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s                    | 1        | 0.58%   |
| SK hynix RAM HMA81GU6MFR8N-UH 8GB DIMM DDR4 2400MT/s                    | 1        | 0.58%   |
| SK hynix RAM HMA451U6AFR8N-TF 4GB DIMM DDR4 2133MT/s                    | 1        | 0.58%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 0.58%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                               | 1        | 0.58%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                               | 1        | 0.58%   |
| Samsung RAM Module 4GB DIMM DDR4 2400MT/s                               | 1        | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 63       | 47.37%  |
| DDR3    | 46       | 34.59%  |
| DDR2    | 11       | 8.27%   |
| Unknown | 9        | 6.77%   |
| LPDDR4  | 2        | 1.5%    |
| SDRAM   | 1        | 0.75%   |
| DDR     | 1        | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 113      | 84.96%  |
| SODIMM | 20       | 15.04%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 61       | 40.67%  |
| 4096  | 38       | 25.33%  |
| 2048  | 27       | 18%     |
| 16384 | 16       | 10.67%  |
| 1024  | 8        | 5.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 18.31%  |
| 1333    | 25       | 17.61%  |
| 2400    | 17       | 11.97%  |
| 2133    | 15       | 10.56%  |
| 3200    | 13       | 9.15%   |
| 2667    | 12       | 8.45%   |
| 800     | 8        | 5.63%   |
| 3600    | 4        | 2.82%   |
| 2666    | 3        | 2.11%   |
| 1067    | 3        | 2.11%   |
| 667     | 3        | 2.11%   |
| 3000    | 2        | 1.41%   |
| 1066    | 2        | 1.41%   |
| 400     | 2        | 1.41%   |
| 4400    | 1        | 0.7%    |
| 3333    | 1        | 0.7%    |
| 1867    | 1        | 0.7%    |
| 1639    | 1        | 0.7%    |
| 1200    | 1        | 0.7%    |
| 533     | 1        | 0.7%    |
| Unknown | 1        | 0.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 2        | 66.67%  |
| Hewlett-Packard    | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| HP LaserJet 3390         | 1        | 33.33%  |
| Brother HL-L2300D series | 1        | 33.33%  |
| Brother DCP-J152W        | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Canon CanoScan LiDE 700F | 1        | 50%     |
| Canon CanoScan LiDE 120  | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 3        | 25%     |
| Microdia                      | 2        | 16.67%  |
| Trust                         | 1        | 8.33%   |
| Sunplus Innovation Technology | 1        | 8.33%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 8.33%   |
| Importek                      | 1        | 8.33%   |
| IMC Networks                  | 1        | 8.33%   |
| Genesys Logic                 | 1        | 8.33%   |
| GEMBIRD                       | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Microdia REDRAGON Live Camera Audio               | 2        | 16.67%  |
| Logitech Webcam C270                              | 2        | 16.67%  |
| Trust Trust Full HD Webcam                        | 1        | 8.33%   |
| Sunplus SPCA2650 AV Camera                        | 1        | 8.33%   |
| SHENZHEN AONI ELECTRONIC NexiGo N990 4K Camera    | 1        | 8.33%   |
| Logitech HD Pro Webcam C920                       | 1        | 8.33%   |
| Importek FJ Camera                                | 1        | 8.33%   |
| IMC Networks XHC Camera                           | 1        | 8.33%   |
| Genesys Logic Digital Microscope                  | 1        | 8.33%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 8.33%   |

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
| 1     | 62       | 45.93%  |
| 0     | 44       | 32.59%  |
| 2     | 27       | 20%     |
| 4     | 1        | 0.74%   |
| 3     | 1        | 0.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 81       | 70.43%  |
| Net/wireless             | 16       | 13.91%  |
| Sound                    | 11       | 9.57%   |
| Bluetooth                | 4        | 3.48%   |
| Card reader              | 2        | 1.74%   |
| Dvb card                 | 1        | 0.87%   |

