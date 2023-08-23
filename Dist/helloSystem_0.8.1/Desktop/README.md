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

Total: 177

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Intel         | JSL MRD                     | [ca7024f423](https://bsd-hardware.info/?probe=ca7024f423) | Aug 10, 2023 |
| Intel         | H81                         | [80f40918ce](https://bsd-hardware.info/?probe=80f40918ce) | Aug 07, 2023 |
| HP            | 0AACh                       | [5997b1de3e](https://bsd-hardware.info/?probe=5997b1de3e) | Aug 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| ASUSTek       | M4A88TD-M/USB3              | [ce95634a53](https://bsd-hardware.info/?probe=ce95634a53) | Aug 06, 2023 |
| ASUSTek       | P5QL PRO                    | [dccefef8eb](https://bsd-hardware.info/?probe=dccefef8eb) | Aug 04, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [f66f032ffe](https://bsd-hardware.info/?probe=f66f032ffe) | Aug 01, 2023 |
| HP            | 83E1                        | [b211795736](https://bsd-hardware.info/?probe=b211795736) | Jul 27, 2023 |
| HP            | 339A                        | [b770568bae](https://bsd-hardware.info/?probe=b770568bae) | Jul 25, 2023 |
| ASRock        | H61M-VG3                    | [5cebf2275e](https://bsd-hardware.info/?probe=5cebf2275e) | Jul 24, 2023 |
| ASUSTek       | P5QL PRO                    | [b51bcdf3a5](https://bsd-hardware.info/?probe=b51bcdf3a5) | Jul 20, 2023 |
| HP            | 81C5 MVB                    | [1a4fbc384d](https://bsd-hardware.info/?probe=1a4fbc384d) | Jul 19, 2023 |
| Apple         | Mac-F221BEC8                | [3a5b0b3193](https://bsd-hardware.info/?probe=3a5b0b3193) | Jul 17, 2023 |
| ECS           | H61H2-M17                   | [aa4679bee7](https://bsd-hardware.info/?probe=aa4679bee7) | Jul 14, 2023 |
| ASRock        | H61M-GS                     | [502952e73f](https://bsd-hardware.info/?probe=502952e73f) | Jul 11, 2023 |
| ASRock        | A300M-STX                   | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
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
| amd64 | 150      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 149      | 99.33%  |
| GNOME        | 1        | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 150      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 150      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 57       | 37.5%   |
| fr_FR   | 46       | 30.26%  |
| ru_RU   | 11       | 7.24%   |
| es_ES   | 10       | 6.58%   |
| de_DE   | 10       | 6.58%   |
| it_IT   | 5        | 3.29%   |
| Unknown | 4        | 2.63%   |
| pt_BR   | 3        | 1.97%   |
| pl_PL   | 2        | 1.32%   |
| jp_JP   | 2        | 1.32%   |
| fr      | 1        | 0.66%   |
| es      | 1        | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 147      | 98%     |
| BIOS | 3        | 2%      |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 90       | 58.44%  |
| Zfs    | 64       | 41.56%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 147      | 98%     |
| MBR  | 3        | 2%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 36       | 24%     |
| Gigabyte Technology | 23       | 15.33%  |
| Hewlett-Packard     | 17       | 11.33%  |
| Dell                | 14       | 9.33%   |
| MSI                 | 8        | 5.33%   |
| Lenovo              | 8        | 5.33%   |
| ASRock              | 8        | 5.33%   |
| Intel               | 7        | 4.67%   |
| Unknown             | 5        | 3.33%   |
| Acer                | 4        | 2.67%   |
| Fujitsu             | 3        | 2%      |
| T-bao               | 2        | 1.33%   |
| Fujitsu Siemens     | 2        | 1.33%   |
| Foxconn             | 2        | 1.33%   |
| AZW                 | 2        | 1.33%   |
| Pegatron            | 1        | 0.67%   |
| LG Electronics      | 1        | 0.67%   |
| Huanan              | 1        | 0.67%   |
| Google              | 1        | 0.67%   |
| ECS                 | 1        | 0.67%   |
| Biostar             | 1        | 0.67%   |
| BESSTAR Tech        | 1        | 0.67%   |
| Axiomtek            | 1        | 0.67%   |
| Apple               | 1        | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 5        | 3.33%   |
| T-bao MINI PC                       | 2        | 1.33%   |
| MSI MS-7788                         | 2        | 1.33%   |
| Intel H81                           | 2        | 1.33%   |
| HP EliteDesk 800 G2 DM 35W          | 2        | 1.33%   |
| HP Compaq Elite 8300 USDT           | 2        | 1.33%   |
| ASUS ROG STRIX B550-F GAMING        | 2        | 1.33%   |
| ASUS PRIME B250M-A                  | 2        | 1.33%   |
| ASUS All Series                     | 2        | 1.33%   |
| Pegatron Compaq dx2450 Microtower   | 1        | 0.67%   |
| MSI MS-7C95                         | 1        | 0.67%   |
| MSI MS-7C51                         | 1        | 0.67%   |
| MSI MS-7C09                         | 1        | 0.67%   |
| MSI MS-7B86                         | 1        | 0.67%   |
| MSI MS-7599                         | 1        | 0.67%   |
| MSI Compaq dx2200 MT                | 1        | 0.67%   |
| LG R590-K.AAA9BT                    | 1        | 0.67%   |
| Lenovo ThinkCentre M900 10FLS15P00  | 1        | 0.67%   |
| Lenovo ThinkCentre M900 10FGS05C08  | 1        | 0.67%   |
| Lenovo ThinkCentre M75e 5065A11     | 1        | 0.67%   |
| Lenovo ThinkCentre M73 10AYA06EIA   | 1        | 0.67%   |
| Lenovo ThinkCentre M73 10AXS34800   | 1        | 0.67%   |
| Lenovo ThinkCentre M710s 10M8S0FW00 | 1        | 0.67%   |
| Lenovo ThinkCentre M58p 6138DK1     | 1        | 0.67%   |
| Lenovo ThinkCentre Edge72 34971B1   | 1        | 0.67%   |
| Intel X99                           | 1        | 0.67%   |
| Intel Jasper Lake Client Platform   | 1        | 0.67%   |
| Intel DH87RL AAG74240-400           | 1        | 0.67%   |
| Intel DG41TY AAE47335-300           | 1        | 0.67%   |
| Intel DB85FL AAG89861-203           | 1        | 0.67%   |
| Huanan X99-TF GAMING V3.0           | 1        | 0.67%   |
| HP Z4 G4 Workstation                | 1        | 0.67%   |
| HP Slim Desktop S01-pF1xxx          | 1        | 0.67%   |
| HP rp5800                           | 1        | 0.67%   |
| HP ProDesk 600 G3 SFF               | 1        | 0.67%   |
| HP ProDesk 600 G1 DM                | 1        | 0.67%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 0.67%   |
| HP EliteDesk 800 G4 SFF             | 1        | 0.67%   |
| HP EliteDesk 800 G2 SFF             | 1        | 0.67%   |
| HP EliteDesk 800 G2 DM 65W          | 1        | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 12       | 8%      |
| Lenovo ThinkCentre      | 8        | 5.33%   |
| Dell OptiPlex           | 7        | 4.67%   |
| ASUS ROG                | 7        | 4.67%   |
| HP EliteDesk            | 5        | 3.33%   |
| HP Compaq               | 5        | 3.33%   |
| Unknown                 | 5        | 3.33%   |
| Dell Precision          | 3        | 2%      |
| T-bao MINI              | 2        | 1.33%   |
| MSI MS-7788             | 2        | 1.33%   |
| Intel H81               | 2        | 1.33%   |
| HP ProDesk              | 2        | 1.33%   |
| Gigabyte B450M          | 2        | 1.33%   |
| Fujitsu Siemens ESPRIMO | 2        | 1.33%   |
| Fujitsu ESPRIMO         | 2        | 1.33%   |
| Dell Vostro             | 2        | 1.33%   |
| Dell Inspiron           | 2        | 1.33%   |
| ASUS TUF                | 2        | 1.33%   |
| ASUS All                | 2        | 1.33%   |
| Acer Veriton            | 2        | 1.33%   |
| Pegatron Compaq         | 1        | 0.67%   |
| MSI MS-7C95             | 1        | 0.67%   |
| MSI MS-7C51             | 1        | 0.67%   |
| MSI MS-7C09             | 1        | 0.67%   |
| MSI MS-7B86             | 1        | 0.67%   |
| MSI MS-7599             | 1        | 0.67%   |
| MSI Compaq              | 1        | 0.67%   |
| LG R590-K.AAA9BT        | 1        | 0.67%   |
| Intel X99               | 1        | 0.67%   |
| Intel Jasper            | 1        | 0.67%   |
| Intel DH87RL            | 1        | 0.67%   |
| Intel DG41TY            | 1        | 0.67%   |
| Intel DB85FL            | 1        | 0.67%   |
| Huanan X99-TF           | 1        | 0.67%   |
| HP Z4                   | 1        | 0.67%   |
| HP Slim                 | 1        | 0.67%   |
| HP rp5800               | 1        | 0.67%   |
| HP Pavilion             | 1        | 0.67%   |
| HP 290                  | 1        | 0.67%   |
| Google Panther          | 1        | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 17       | 11.33%  |
| 2013    | 16       | 10.67%  |
| 2022    | 14       | 9.33%   |
| 2020    | 13       | 8.67%   |
| 2012    | 13       | 8.67%   |
| 2019    | 11       | 7.33%   |
| 2010    | 10       | 6.67%   |
| 2018    | 9        | 6%      |
| 2014    | 8        | 5.33%   |
| 2017    | 7        | 4.67%   |
| 2011    | 6        | 4%      |
| 2016    | 5        | 3.33%   |
| 2023    | 4        | 2.67%   |
| 2015    | 4        | 2.67%   |
| 2009    | 4        | 2.67%   |
| 2008    | 4        | 2.67%   |
| 2007    | 2        | 1.33%   |
| 2006    | 2        | 1.33%   |
| Unknown | 1        | 0.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 150      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 149      | 99.33%  |
| Yes  | 1        | 0.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 54       | 36%     |
| 16.01-24.0  | 43       | 28.67%  |
| 4.01-8.0    | 27       | 18%     |
| 32.01-64.0  | 14       | 9.33%   |
| 2.01-3.0    | 4        | 2.67%   |
| 24.01-32.0  | 3        | 2%      |
| 64.01-256.0 | 3        | 2%      |
| 3.01-4.0    | 1        | 0.67%   |
| 0.51-1.0    | 1        | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 69       | 45.39%  |
| 0.51-1.0 | 56       | 36.84%  |
| 1.01-2.0 | 18       | 11.84%  |
| 2.01-3.0 | 8        | 5.26%   |
| 3.01-4.0 | 1        | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 72       | 48%     |
| 2      | 34       | 22.67%  |
| 3      | 21       | 14%     |
| 0      | 9        | 6%      |
| 5      | 6        | 4%      |
| 4      | 4        | 2.67%   |
| 9      | 2        | 1.33%   |
| 7      | 1        | 0.67%   |
| 6      | 1        | 0.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 92       | 61.33%  |
| Yes       | 58       | 38.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 145      | 96.67%  |
| No        | 5        | 3.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 66.89%  |
| Yes       | 50       | 33.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 111      | 74%     |
| Yes       | 39       | 26%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| Russia             | 20       | 13.33%  |
| USA                | 17       | 11.33%  |
| Germany            | 11       | 7.33%   |
| Spain              | 10       | 6.67%   |
| Italy              | 7        | 4.67%   |
| Hungary            | 6        | 4%      |
| Canada             | 6        | 4%      |
| Brazil             | 6        | 4%      |
| Serbia             | 5        | 3.33%   |
| Romania            | 5        | 3.33%   |
| Poland             | 5        | 3.33%   |
| France             | 5        | 3.33%   |
| Australia          | 4        | 2.67%   |
| UK                 | 3        | 2%      |
| Turkey             | 3        | 2%      |
| Peru               | 3        | 2%      |
| Mexico             | 3        | 2%      |
| Belgium            | 3        | 2%      |
| Ukraine            | 2        | 1.33%   |
| Sweden             | 2        | 1.33%   |
| Japan              | 2        | 1.33%   |
| India              | 2        | 1.33%   |
| China              | 2        | 1.33%   |
| Bulgaria           | 2        | 1.33%   |
| Argentina          | 2        | 1.33%   |
| Switzerland        | 1        | 0.67%   |
| South Korea        | 1        | 0.67%   |
| Slovenia           | 1        | 0.67%   |
| San Marino         | 1        | 0.67%   |
| Netherlands        | 1        | 0.67%   |
| Kyrgyzstan         | 1        | 0.67%   |
| Kazakhstan         | 1        | 0.67%   |
| Indonesia          | 1        | 0.67%   |
| Dominican Republic | 1        | 0.67%   |
| Croatia            | 1        | 0.67%   |
| Chile              | 1        | 0.67%   |
| Belarus            | 1        | 0.67%   |
| Austria            | 1        | 0.67%   |
| Algeria            | 1        | 0.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| St. Jean Baptiste | 3        | 1.99%   |
| Moscow            | 3        | 1.99%   |
| Belgrade          | 3        | 1.99%   |
| Sydney            | 2        | 1.32%   |
| Penza             | 2        | 1.32%   |
| Paris             | 2        | 1.32%   |
| Melbourne         | 2        | 1.32%   |
| Madrid            | 2        | 1.32%   |
| Kirov             | 2        | 1.32%   |
| Brooklyn          | 2        | 1.32%   |
| Berlin            | 2        | 1.32%   |
| Zurich            | 1        | 0.66%   |
| Zhengzhou         | 1        | 0.66%   |
| Yokohama          | 1        | 0.66%   |
| Woodbridge        | 1        | 0.66%   |
| Winnipeg          | 1        | 0.66%   |
| Warsaw            | 1        | 0.66%   |
| Volgodonsk        | 1        | 0.66%   |
| Vogogna           | 1        | 0.66%   |
| Virovitica        | 1        | 0.66%   |
| Villena           | 1        | 0.66%   |
| Vienna            | 1        | 0.66%   |
| Venice            | 1        | 0.66%   |
| Vecses            | 1        | 0.66%   |
| Valderrobres      | 1        | 0.66%   |
| Ubstadt-Weiher    | 1        | 0.66%   |
| Tucson            | 1        | 0.66%   |
| Trumbull          | 1        | 0.66%   |
| Trekhgornyy       | 1        | 0.66%   |
| Topolovgrad       | 1        | 0.66%   |
| Tolmin            | 1        | 0.66%   |
| Tokmok            | 1        | 0.66%   |
| Timișoara        | 1        | 0.66%   |
| Temple            | 1        | 0.66%   |
| Stuttgart         | 1        | 0.66%   |
| Stevenage         | 1        | 0.66%   |
| St Petersburg     | 1        | 0.66%   |
| Springfield       | 1        | 0.66%   |
| Sopron            | 1        | 0.66%   |
| Sofia             | 1        | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 44       | 64     | 18.64%  |
| Samsung Electronics | 33       | 49     | 13.98%  |
| Seagate             | 32       | 39     | 13.56%  |
| Kingston            | 27       | 27     | 11.44%  |
| Toshiba             | 14       | 17     | 5.93%   |
| SanDisk             | 9        | 9      | 3.81%   |
| Crucial             | 8        | 10     | 3.39%   |
| A-DATA Technology   | 7        | 8      | 2.97%   |
| China               | 6        | 7      | 2.54%   |
| Hitachi             | 5        | 6      | 2.12%   |
| Transcend           | 4        | 4      | 1.69%   |
| Patriot             | 4        | 4      | 1.69%   |
| Micron Technology   | 4        | 5      | 1.69%   |
| Maxtor              | 4        | 4      | 1.69%   |
| KingSpec            | 3        | 3      | 1.27%   |
| Team                | 2        | 2      | 0.85%   |
| PNY                 | 2        | 2      | 0.85%   |
| WALRAM              | 1        | 1      | 0.42%   |
| Vaseky              | 1        | 1      | 0.42%   |
| TAMMUZ              | 1        | 1      | 0.42%   |
| SPCC                | 1        | 1      | 0.42%   |
| Silicon Motion      | 1        | 1      | 0.42%   |
| SETHRISE            | 1        | 1      | 0.42%   |
| QUANTUM             | 1        | 1      | 0.42%   |
| Pioneer             | 1        | 1      | 0.42%   |
| Philips             | 1        | 1      | 0.42%   |
| Palit               | 1        | 1      | 0.42%   |
| OCZ                 | 1        | 1      | 0.42%   |
| Netac               | 1        | 1      | 0.42%   |
| LITEONIT            | 1        | 1      | 0.42%   |
| Kston               | 1        | 1      | 0.42%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.42%   |
| KIOXIA              | 1        | 1      | 0.42%   |
| Intenso             | 1        | 1      | 0.42%   |
| Intel               | 1        | 1      | 0.42%   |
| HGST                | 1        | 1      | 0.42%   |
| GOODRAM             | 1        | 1      | 0.42%   |
| Gigabyte Technology | 1        | 2      | 0.42%   |
| EDGE                | 1        | 1      | 0.42%   |
| Corsair             | 1        | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 7        | 2.54%   |
| Seagate ST500DM002-1BD142 496GB | 5        | 1.81%   |
| Seagate ST3500418AS 500GB       | 4        | 1.45%   |
| Samsung SSD 850 EVO 250GB       | 4        | 1.45%   |
| WDC WD10EZEX-08WN4A0 1TB        | 3        | 1.09%   |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 1.09%   |
| Seagate ST1000DM010-2EP102 1TB  | 3        | 1.09%   |
| Samsung SSD 980 1TB             | 3        | 1.09%   |
| Samsung SSD 870 EVO 500GB       | 3        | 1.09%   |
| Samsung SSD 860 EVO 500GB       | 3        | 1.09%   |
| Kingston SA400S37120G 120GB     | 3        | 1.09%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 1.09%   |
| WDC WDS240G2G0A-00JH30 240GB    | 2        | 0.72%   |
| WDC WDS120G2G0A-00JH30 120GB    | 2        | 0.72%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 2        | 0.72%   |
| WDC WD10EZEX-60WN4A0 1TB        | 2        | 0.72%   |
| Toshiba HDWD110 1TB             | 2        | 0.72%   |
| Toshiba DT01ACA100 1TB          | 2        | 0.72%   |
| Toshiba DT01ACA050 500GB        | 2        | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 0.72%   |
| SanDisk pSSD 16GB               | 2        | 0.72%   |
| Samsung SSD 980 PRO 500GB       | 2        | 0.72%   |
| Samsung SSD 970 PRO 512GB       | 2        | 0.72%   |
| Samsung SSD 970 EVO Plus 500GB  | 2        | 0.72%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 0.72%   |
| Patriot Burst Elite 120GB       | 2        | 0.72%   |
| Kingston SHFS37A240G 240GB      | 2        | 0.72%   |
| Kingston SA400S37480G 480GB     | 2        | 0.72%   |
| WDC WDS500G2B0A-00SM50 500GB    | 1        | 0.36%   |
| WDC WDS500G1B0A-00H9H0 500GB    | 1        | 0.36%   |
| WDC WDS250G1B0A-00H9H0 250GB    | 1        | 0.36%   |
| WDC WD800JD-75MSA3 80GB         | 1        | 0.36%   |
| WDC WD800AAJS-00PSA0 80GB       | 1        | 0.36%   |
| WDC WD7501AALS-00J7B0 752GB     | 1        | 0.36%   |
| WDC WD6400BPVT-22HXZT3 640GB    | 1        | 0.36%   |
| WDC WD60EZRX-00MVLB1 6TB        | 1        | 0.36%   |
| WDC WD50NDZW-11A8JS1 5TB        | 1        | 0.36%   |
| WDC WD5003AZEX-00K1GA0 500GB    | 1        | 0.36%   |
| WDC WD5000LPCX-21VHAT0 500GB    | 1        | 0.36%   |
| WDC WD5000AZRX-00A8LB0 500GB    | 1        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 37       | 56     | 38.95%  |
| Seagate             | 32       | 39     | 33.68%  |
| Toshiba             | 11       | 14     | 11.58%  |
| Hitachi             | 5        | 6      | 5.26%   |
| Maxtor              | 4        | 4      | 4.21%   |
| Samsung Electronics | 3        | 4      | 3.16%   |
| QUANTUM             | 1        | 1      | 1.05%   |
| HGST                | 1        | 1      | 1.05%   |
| Apple               | 1        | 1      | 1.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 19       | 19     | 18.1%   |
| Samsung Electronics | 17       | 24     | 16.19%  |
| SanDisk             | 9        | 9      | 8.57%   |
| WDC                 | 7        | 7      | 6.67%   |
| Crucial             | 7        | 8      | 6.67%   |
| China               | 6        | 7      | 5.71%   |
| Patriot             | 4        | 4      | 3.81%   |
| A-DATA Technology   | 4        | 4      | 3.81%   |
| Transcend           | 3        | 3      | 2.86%   |
| Toshiba             | 3        | 3      | 2.86%   |
| KingSpec            | 3        | 3      | 2.86%   |
| PNY                 | 2        | 2      | 1.9%    |
| WALRAM              | 1        | 1      | 0.95%   |
| Vaseky              | 1        | 1      | 0.95%   |
| Team                | 1        | 1      | 0.95%   |
| TAMMUZ              | 1        | 1      | 0.95%   |
| SPCC                | 1        | 1      | 0.95%   |
| SETHRISE            | 1        | 1      | 0.95%   |
| Pioneer             | 1        | 1      | 0.95%   |
| Philips             | 1        | 1      | 0.95%   |
| Palit               | 1        | 1      | 0.95%   |
| OCZ                 | 1        | 1      | 0.95%   |
| Micron Technology   | 1        | 1      | 0.95%   |
| LITEONIT            | 1        | 1      | 0.95%   |
| Kston               | 1        | 1      | 0.95%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.95%   |
| Intenso             | 1        | 1      | 0.95%   |
| Intel               | 1        | 1      | 0.95%   |
| GOODRAM             | 1        | 1      | 0.95%   |
| Gigabyte Technology | 1        | 2      | 0.95%   |
| EDGE                | 1        | 1      | 0.95%   |
| Apacer              | 1        | 1      | 0.95%   |
| AMD                 | 1        | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 82       | 115    | 40.8%   |
| HDD  | 80       | 126    | 39.8%   |
| NVMe | 39       | 48     | 19.4%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 134      | 241    | 77.46%  |
| NVMe | 39       | 48     | 22.54%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 113      | 164    | 66.47%  |
| 0.51-1.0   | 33       | 40     | 19.41%  |
| 1.01-2.0   | 12       | 21     | 7.06%   |
| 3.01-4.0   | 7        | 8      | 4.12%   |
| 2.01-3.0   | 2        | 5      | 1.18%   |
| 4.01-10.0  | 2        | 2      | 1.18%   |
| 10.01-20.0 | 1        | 1      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 85       | 55.56%  |
| 101-250    | 21       | 13.73%  |
| 51-100     | 19       | 12.42%  |
| 251-500    | 17       | 11.11%  |
| 501-1000   | 8        | 5.23%   |
| 21-50      | 2        | 1.31%   |
| Unknown    | 1        | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 147      | 98%     |
| 251-500 | 1        | 0.67%   |
| 21-50   | 1        | 0.67%   |
| Unknown | 1        | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| WDC WD800JD-75MSA3 80GB                    | 1        | 1      | 2.86%   |
| WDC WD6400BPVT-22HXZT3 640GB               | 1        | 1      | 2.86%   |
| WDC WD5000AAKX-08U6AA0 500GB               | 1        | 1      | 2.86%   |
| WDC WD5000AAKX-00ERMA0 500GB               | 1        | 1      | 2.86%   |
| WDC WD30EFRX-68EUZN0 3TB                   | 1        | 1      | 2.86%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1        | 1      | 2.86%   |
| WDC WD1600YS-01SHB1 164GB                  | 1        | 1      | 2.86%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 1      | 2.86%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1        | 1      | 2.86%   |
| WDC WD10EZEX-60M2NA0 1TB                   | 1        | 1      | 2.86%   |
| WDC WD10EARS-003BB1 1TB                    | 1        | 1      | 2.86%   |
| Toshiba MK3259GSXP 320GB                   | 1        | 1      | 2.86%   |
| Toshiba DT01ACA100 1TB                     | 1        | 1      | 2.86%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB  | 1        | 1      | 2.86%   |
| Seagate ST500LM000-1EJ162 500GB            | 1        | 1      | 2.86%   |
| Seagate ST500DM002-1BD142 496GB            | 1        | 1      | 2.86%   |
| Seagate ST380215AS 80GB                    | 1        | 1      | 2.86%   |
| Seagate ST3750528AS 752GB                  | 1        | 1      | 2.86%   |
| Seagate ST3500418AS 500GB                  | 1        | 1      | 2.86%   |
| Seagate ST3500320AS 500GB                  | 1        | 1      | 2.86%   |
| Seagate ST3320620AS 320GB                  | 1        | 1      | 2.86%   |
| Seagate ST3250312AS 250GB                  | 1        | 2      | 2.86%   |
| Seagate ST2000DM008-2FR102 2TB             | 1        | 1      | 2.86%   |
| Seagate ST1000DM010-2EP102 1TB             | 1        | 1      | 2.86%   |
| Samsung Electronics MZVL22T0HBLB-00B00 2TB | 1        | 1      | 2.86%   |
| Samsung Electronics HD103SJ 1TB            | 1        | 1      | 2.86%   |
| Maxtor 6Y080M0 82GB                        | 1        | 1      | 2.86%   |
| Maxtor 6V080E0 80GB                        | 1        | 1      | 2.86%   |
| Maxtor 6L080P0 82GB                        | 1        | 1      | 2.86%   |
| Kingston SA400S37240G 240GB                | 1        | 1      | 2.86%   |
| Hitachi HTS725050A7E630 500GB              | 1        | 1      | 2.86%   |
| Hitachi HTS541680J9SA00 80GB               | 1        | 1      | 2.86%   |
| HGST HTS545050A7E680 500GB                 | 1        | 1      | 2.86%   |
| Crucial CT1050MX300SSD1 1TB                | 1        | 1      | 2.86%   |
| China SH00R120GB                           | 1        | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 11     | 33.33%  |
| Seagate             | 8        | 11     | 24.24%  |
| Maxtor              | 3        | 3      | 9.09%   |
| Toshiba             | 2        | 2      | 6.06%   |
| Samsung Electronics | 2        | 2      | 6.06%   |
| Hitachi             | 2        | 2      | 6.06%   |
| Silicon Motion      | 1        | 1      | 3.03%   |
| Kingston            | 1        | 1      | 3.03%   |
| HGST                | 1        | 1      | 3.03%   |
| Crucial             | 1        | 1      | 3.03%   |
| China               | 1        | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 11     | 39.29%  |
| Seagate             | 8        | 11     | 28.57%  |
| Maxtor              | 3        | 3      | 10.71%  |
| Toshiba             | 2        | 2      | 7.14%   |
| Hitachi             | 2        | 2      | 7.14%   |
| Samsung Electronics | 1        | 1      | 3.57%   |
| HGST                | 1        | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 31     | 84.85%  |
| SSD  | 3        | 3      | 9.09%   |
| NVMe | 2        | 2      | 6.06%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB | 1        | 1      | 33.33%  |
| WDC WD1600BEVT-22ZCT0 160GB | 1        | 1      | 33.33%  |
| SanDisk pSSD 16GB           | 1        | 1      | 33.33%  |

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
| Works    | 118      | 236    | 72.84%  |
| Malfunc  | 33       | 36     | 20.37%  |
| Detected | 8        | 14     | 4.94%   |
| Failed   | 3        | 3      | 1.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 109      | 53.43%  |
| AMD                         | 35       | 17.16%  |
| Samsung Electronics         | 17       | 8.33%   |
| Kingston Technology Company | 8        | 3.92%   |
| Silicon Motion              | 4        | 1.96%   |
| Nvidia                      | 4        | 1.96%   |
| Marvell Technology Group    | 4        | 1.96%   |
| ASMedia Technology          | 4        | 1.96%   |
| Micron Technology           | 3        | 1.47%   |
| VIA Technologies            | 2        | 0.98%   |
| Sandisk                     | 2        | 0.98%   |
| Realtek Semiconductor       | 2        | 0.98%   |
| Micron/Crucial Technology   | 2        | 0.98%   |
| JMicron Technology          | 2        | 0.98%   |
| ADATA Technology            | 2        | 0.98%   |
| Phison Electronics          | 1        | 0.49%   |
| OCZ Technology Group        | 1        | 0.49%   |
| KIOXIA                      | 1        | 0.49%   |
| Broadcom / LSI              | 1        | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 6.37%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 15       | 5.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12       | 4.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 4.38%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 4.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 3.59%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 3.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 2.79%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 2.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6        | 2.39%   |
| Samsung NVMe SSD Controller 980                                                         | 5        | 1.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 1.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 1.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.59%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.59%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.59%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 1.2%    |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.2%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.2%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 1.2%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 1.2%    |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3        | 1.2%    |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3        | 1.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.2%    |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.8%    |
| Nvidia MCP61 IDE                                                                        | 2        | 0.8%    |
| Micron 2200S NVMe SSD [Cassandra]                                                       | 2        | 0.8%    |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 2        | 0.8%    |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2        | 0.8%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.8%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.8%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 2        | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 116      | 59.18%  |
| NVMe | 38       | 19.39%  |
| IDE  | 32       | 16.33%  |
| RAID | 8        | 4.08%   |
| SAS  | 1        | 0.51%   |
| SCSI | 1        | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 111      | 74%     |
| AMD    | 39       | 26%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz              | 4        | 2.67%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3        | 2%      |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3        | 2%      |
| Intel Core i3-7100 CPU @ 3.90GHz              | 3        | 2%      |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 2%      |
| AMD Ryzen 5 5600X 6-Core Processor            | 3        | 2%      |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 3        | 2%      |
| AMD Ryzen 5 2600 Six-Core Processor           | 3        | 2%      |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2        | 1.33%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2        | 1.33%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2        | 1.33%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2        | 1.33%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2        | 1.33%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 2        | 1.33%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 2        | 1.33%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2        | 1.33%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2        | 1.33%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 2        | 1.33%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2        | 1.33%   |
| Intel Celeron N5105 @ 2.00GHz                 | 2        | 1.33%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2        | 1.33%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 2        | 1.33%   |
| Intel 12th Gen Core i5-12400                  | 2        | 1.33%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2        | 1.33%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2        | 1.33%   |
| Intel Xeon W-2125 CPU @ 4.00GHz               | 1        | 0.67%   |
| Intel Xeon CPU W3670 @ 3.20GHz                | 1        | 0.67%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1        | 0.67%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1        | 0.67%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1        | 0.67%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1        | 0.67%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz           | 1        | 0.67%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz           | 1        | 0.67%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz           | 1        | 0.67%   |
| Intel Xeon                                    | 1        | 0.67%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1        | 0.67%   |
| Intel Pentium Dual-Core CPU E5300             | 1        | 0.67%   |
| Intel Pentium CPU G850 @ 2.90GHz              | 1        | 0.67%   |
| Intel Pentium CPU G620 @ 2.60GHz              | 1        | 0.67%   |
| Intel Pentium CPU G3240T @ 2.70GHz            | 1        | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 31       | 20.67%  |
| Intel Core i3           | 22       | 14.67%  |
| Intel Core i7           | 16       | 10.67%  |
| Intel Celeron           | 12       | 8%      |
| AMD Ryzen 5             | 12       | 8%      |
| Intel Xeon              | 10       | 6.67%   |
| Intel Core 2 Duo        | 6        | 4%      |
| AMD Ryzen 3             | 6        | 4%      |
| AMD Ryzen 7             | 5        | 3.33%   |
| Other                   | 4        | 2.67%   |
| Intel Pentium           | 4        | 2.67%   |
| AMD Phenom II X4        | 3        | 2%      |
| AMD Athlon II X2        | 3        | 2%      |
| Intel Core 2 Quad       | 2        | 1.33%   |
| AMD A4                  | 2        | 1.33%   |
| Intel Pentium Gold      | 1        | 0.67%   |
| Intel Pentium Dual-Core | 1        | 0.67%   |
| Intel Pentium 4         | 1        | 0.67%   |
| Intel Core i9           | 1        | 0.67%   |
| AMD Ryzen 9             | 1        | 0.67%   |
| AMD Phenom II X2        | 1        | 0.67%   |
| AMD FX                  | 1        | 0.67%   |
| AMD E                   | 1        | 0.67%   |
| AMD Athlon X2           | 1        | 0.67%   |
| AMD Athlon II X4        | 1        | 0.67%   |
| AMD Athlon 64           | 1        | 0.67%   |
| AMD A10                 | 1        | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 67       | 44.67%  |
| 2       | 41       | 27.33%  |
| 6       | 14       | 9.33%   |
| 12      | 10       | 6.67%   |
| 8       | 6        | 4%      |
| 16      | 4        | 2.67%   |
| Unknown | 4        | 2.67%   |
| 1       | 2        | 1.33%   |
| 24      | 1        | 0.67%   |
| 10      | 1        | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 148      | 98.67%  |
| 2      | 2        | 1.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 94       | 62.67%  |
| 2       | 51       | 34%     |
| Unknown | 5        | 3.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 21       | 14%     |
| KabyLake      | 17       | 11.33%  |
| IvyBridge     | 16       | 10.67%  |
| Skylake       | 13       | 8.67%   |
| Zen+          | 11       | 7.33%   |
| SandyBridge   | 11       | 7.33%   |
| K10           | 9        | 6%      |
| Zen 3         | 8        | 5.33%   |
| Penryn        | 7        | 4.67%   |
| Unknown       | 6        | 4%      |
| CometLake     | 5        | 3.33%   |
| Zen           | 4        | 2.67%   |
| Core          | 4        | 2.67%   |
| Piledriver    | 3        | 2%      |
| Nehalem       | 3        | 2%      |
| Westmere      | 2        | 1.33%   |
| Silvermont    | 2        | 1.33%   |
| Goldmont plus | 2        | 1.33%   |
| Zen 2         | 1        | 0.67%   |
| NetBurst      | 1        | 0.67%   |
| K8 Hammer     | 1        | 0.67%   |
| Goldmont      | 1        | 0.67%   |
| Bulldozer     | 1        | 0.67%   |
| Bobcat        | 1        | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 70       | 43.48%  |
| Nvidia                     | 48       | 29.81%  |
| AMD                        | 42       | 26.09%  |
| Matrox Electronics Systems | 1        | 0.62%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                       | 9        | 5.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 4.27%   |
| Intel HD Graphics 630                                                       | 7        | 4.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 4.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 3.66%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 3.66%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 3.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 3.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 2.44%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 2.44%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 1.83%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.83%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.83%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.22%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.22%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.22%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.22%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 1.22%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 2        | 1.22%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.22%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.22%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 1.22%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.22%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.22%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 1.22%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 1.22%   |
| AMD RS880 [Radeon HD 4250]                                                  | 2        | 1.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2        | 1.22%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 1.22%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.22%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.22%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.61%   |
| Nvidia GT218M [GeForce 310M]                                                | 1        | 0.61%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.61%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.61%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 1        | 0.61%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 53       | 34.87%  |
| 1 x Nvidia     | 44       | 28.95%  |
| 1 x AMD        | 34       | 22.37%  |
| Intel + AMD    | 8        | 5.26%   |
| 2 x Intel      | 6        | 3.95%   |
| Intel + Nvidia | 4        | 2.63%   |
| Other          | 1        | 0.66%   |
| 2 x AMD        | 1        | 0.66%   |
| 1 x Matrox     | 1        | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 114      | 75.5%   |
| Proprietary | 34       | 22.52%  |
| Unknown     | 3        | 1.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 93       | 61.18%  |
| 3.01-4.0   | 16       | 10.53%  |
| 1.01-2.0   | 16       | 10.53%  |
| 0.51-1.0   | 9        | 5.92%   |
| 5.01-6.0   | 7        | 4.61%   |
| 0.01-0.5   | 6        | 3.95%   |
| 7.01-8.0   | 3        | 1.97%   |
| 2.01-3.0   | 1        | 0.66%   |
| 8.01-16.0  | 1        | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 7        | 12.96%  |
| Acer                 | 7        | 12.96%  |
| Hewlett-Packard      | 5        | 9.26%   |
| Dell                 | 5        | 9.26%   |
| BenQ                 | 5        | 9.26%   |
| Ancor Communications | 4        | 7.41%   |
| Philips              | 3        | 5.56%   |
| LG Electronics       | 2        | 3.7%    |
| Lenovo               | 2        | 3.7%    |
| Goldstar             | 2        | 3.7%    |
| Unknown              | 2        | 3.7%    |
| Semp Toshiba         | 1        | 1.85%   |
| PKB                  | 1        | 1.85%   |
| NEC Computers        | 1        | 1.85%   |
| Microstep            | 1        | 1.85%   |
| Idek Iiyama          | 1        | 1.85%   |
| Eizo                 | 1        | 1.85%   |
| AUS                  | 1        | 1.85%   |
| ASUSTek Computer     | 1        | 1.85%   |
| Apple                | 1        | 1.85%   |
| AOC                  | 1        | 1.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                      | 2        | 3.7%    |
| Unknown                                                                | 2        | 3.7%    |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch              | 1        | 1.85%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch   | 1        | 1.85%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1        | 1.85%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1        | 1.85%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch       | 1        | 1.85%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 1        | 1.85%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 600x340mm 27.2-inch | 1        | 1.85%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch   | 1        | 1.85%   |
| PKB LCD Monitor MAE200W 1680x1050                                      | 1        | 1.85%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch                | 1        | 1.85%   |
| Philips PHL 221S8L PHL091C 1920x1080 480x270mm 21.7-inch               | 1        | 1.85%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                      | 1        | 1.85%   |
| NEC Computers LCD Monitor 70GX2 1280x1024                              | 1        | 1.85%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                            | 1        | 1.85%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 1.85%   |
| LG Electronics LCD Monitor L1918S 1280x1024                            | 1        | 1.85%   |
| Lenovo L24e-30 LEN66BC 1920x1080 530x300mm 24.0-inch                   | 1        | 1.85%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                    | 1        | 1.85%   |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160                             | 1        | 1.85%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 600x340mm 27.2-inch          | 1        | 1.85%   |
| Hewlett-Packard Z24nq HWP3239 2560x1440 530x300mm 24.0-inch            | 1        | 1.85%   |
| Hewlett-Packard w2007 HWP26A6 1680x1050 430x270mm 20.0-inch            | 1        | 1.85%   |
| Hewlett-Packard L1955 HWP262C 1280x1024 380x300mm 19.1-inch            | 1        | 1.85%   |
| Hewlett-Packard 27o HPN342C 1920x1080 600x340mm 27.2-inch              | 1        | 1.85%   |
| Goldstar LG IPS QHD GSM5BC4 2560x1440 530x300mm 24.0-inch              | 1        | 1.85%   |
| Goldstar 22EA53 GSM59A6 1920x1080 480x270mm 21.7-inch                  | 1        | 1.85%   |
| Eizo FS2331 ENC2211 1920x1080 510x290mm 23.1-inch                      | 1        | 1.85%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                      | 1        | 1.85%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                      | 1        | 1.85%   |
| Dell LCD Monitor U2419HC 1920x1080                                     | 1        | 1.85%   |
| Dell LCD Monitor S2721D 2560x1440                                      | 1        | 1.85%   |
| Dell E2220H DELF119 1920x1080 480x270mm 21.7-inch                      | 1        | 1.85%   |
| BenQ LCD Monitor GW2780 1920x1080                                      | 1        | 1.85%   |
| BenQ LCD Monitor GW2260 1920x1080                                      | 1        | 1.85%   |
| BenQ GW2480 BNQ78E7 1920x1080 530x300mm 24.0-inch                      | 1        | 1.85%   |
| BenQ GW2250H BNQ78BD 1920x1080 480x270mm 21.7-inch                     | 1        | 1.85%   |
| BenQ G900W BNQ7805 1440x900 410x260mm 19.1-inch                        | 1        | 1.85%   |
| AUS LCD Monitor ASUS VG247Q1A 1920x1080                                | 1        | 1.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 28       | 51.85%  |
| 2560x1440 (QHD)    | 6        | 11.11%  |
| 1366x768 (WXGA)    | 5        | 9.26%   |
| 1280x1024 (SXGA)   | 3        | 5.56%   |
| 3840x2160 (4K)     | 2        | 3.7%    |
| 1680x1050 (WSXGA+) | 2        | 3.7%    |
| Unknown            | 2        | 3.7%    |
| 5760x2160          | 1        | 1.85%   |
| 3840x1080          | 1        | 1.85%   |
| 1920x1200 (WUXGA)  | 1        | 1.85%   |
| 1600x900 (HD+)     | 1        | 1.85%   |
| 1440x900 (WXGA+)   | 1        | 1.85%   |
| 1024x768 (XGA)     | 1        | 1.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 33.33%  |
| 24      | 8        | 15.69%  |
| 27      | 7        | 13.73%  |
| 21      | 7        | 13.73%  |
| 23      | 3        | 5.88%   |
| 19      | 3        | 5.88%   |
| 18      | 3        | 5.88%   |
| 22      | 1        | 1.96%   |
| 20      | 1        | 1.96%   |
| 14      | 1        | 1.96%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 18       | 35.29%  |
| Unknown     | 17       | 33.33%  |
| 401-500     | 14       | 27.45%  |
| 351-400     | 1        | 1.96%   |
| 201-300     | 1        | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 29       | 56.86%  |
| Unknown | 17       | 33.33%  |
| 16/10   | 3        | 5.88%   |
| 5/4     | 1        | 1.96%   |
| 4/3     | 1        | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 19       | 37.25%  |
| Unknown        | 17       | 33.33%  |
| 301-350        | 7        | 13.73%  |
| 151-200        | 4        | 7.84%   |
| 141-150        | 3        | 5.88%   |
| 101-110        | 1        | 1.96%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 23       | 45.1%   |
| Unknown | 17       | 33.33%  |
| 101-120 | 9        | 17.65%  |
| 121-160 | 2        | 3.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 121      | 80.13%  |
| 0     | 26       | 17.22%  |
| 2     | 4        | 2.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 88       | 46.07%  |
| Intel                    | 63       | 32.98%  |
| Qualcomm Atheros         | 13       | 6.81%   |
| Ralink Technology        | 4        | 2.09%   |
| Ralink                   | 4        | 2.09%   |
| Broadcom                 | 4        | 2.09%   |
| TP-Link                  | 3        | 1.57%   |
| Marvell Technology Group | 2        | 1.05%   |
| Huawei Technologies      | 2        | 1.05%   |
| D-Link                   | 2        | 1.05%   |
| Samsung Electronics      | 1        | 0.52%   |
| National Semiconductor   | 1        | 0.52%   |
| MediaTek                 | 1        | 0.52%   |
| Edimax Technology        | 1        | 0.52%   |
| Atheros                  | 1        | 0.52%   |
| Accton Technology        | 1        | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76       | 36.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 4.29%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 3.81%   |
| Intel Ethernet Controller I225-V                                  | 7        | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6        | 2.86%   |
| Intel Ethernet Connection I217-V                                  | 5        | 2.38%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.43%   |
| Intel Wireless 3165                                               | 3        | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.43%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.43%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.95%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.95%   |
| Ralink RT2500 Wireless 802.11bg                                   | 2        | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.95%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.95%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 0.95%   |
| Intel I211 Gigabit Network Connection                             | 2        | 0.95%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.95%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.95%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 0.95%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.95%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 2        | 0.95%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.95%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.48%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.48%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1        | 0.48%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1        | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.48%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                      | 1        | 0.48%   |
| Ralink RT3072 Wireless Adapter                                    | 1        | 0.48%   |
| Ralink MT7601U Wireless Adapter                                   | 1        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 14       | 25.45%  |
| Intel                 | 14       | 25.45%  |
| Qualcomm Atheros      | 6        | 10.91%  |
| Ralink Technology     | 4        | 7.27%   |
| Ralink                | 4        | 7.27%   |
| Broadcom              | 4        | 7.27%   |
| TP-Link               | 3        | 5.45%   |
| D-Link                | 2        | 3.64%   |
| MediaTek              | 1        | 1.82%   |
| Edimax Technology     | 1        | 1.82%   |
| Atheros               | 1        | 1.82%   |
| Accton Technology     | 1        | 1.82%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 6        | 10.71%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 5.36%   |
| Intel Wireless 3165                                                  | 3        | 5.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 3.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2        | 3.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2        | 3.57%   |
| Ralink RT2500 Wireless 802.11bg                                      | 2        | 3.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 3.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2        | 3.57%   |
| Intel Wi-Fi 6 AX200                                                  | 2        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2        | 3.57%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2        | 3.57%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 1.79%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 1.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1        | 1.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 1.79%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                         | 1        | 1.79%   |
| Ralink RT3072 Wireless Adapter                                       | 1        | 1.79%   |
| Ralink MT7601U Wireless Adapter                                      | 1        | 1.79%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1        | 1.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 1.79%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 1        | 1.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1        | 1.79%   |
| Intel Wireless 8265 / 8275                                           | 1        | 1.79%   |
| Intel Wireless 8260                                                  | 1        | 1.79%   |
| Intel Wireless 7265                                                  | 1        | 1.79%   |
| Intel Wireless 7260                                                  | 1        | 1.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 1.79%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]             | 1        | 1.79%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU] | 1        | 1.79%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.D1) [Realtek RTL8188ETV]   | 1        | 1.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 1.79%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1        | 1.79%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 1        | 1.79%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 1        | 1.79%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 1.79%   |
| Accton Arcadyan 802.11N Wireless Adapter                             | 1        | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 82       | 54.3%   |
| Intel                    | 55       | 36.42%  |
| Qualcomm Atheros         | 7        | 4.64%   |
| Marvell Technology Group | 2        | 1.32%   |
| Huawei Technologies      | 2        | 1.32%   |
| Samsung Electronics      | 1        | 0.66%   |
| National Semiconductor   | 1        | 0.66%   |
| Broadcom                 | 1        | 0.66%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76       | 49.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 5.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 5.19%   |
| Intel Ethernet Controller I225-V                                  | 7        | 4.55%   |
| Intel Ethernet Connection I217-V                                  | 5        | 3.25%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 2.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.95%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 1.3%    |
| Intel I211 Gigabit Network Connection                             | 2        | 1.3%    |
| Intel I210 Gigabit Network Connection                             | 2        | 1.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.3%    |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.3%    |
| Intel 82567LF-3 Gigabit Network Connection                        | 2        | 1.3%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 0.65%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.65%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1        | 0.65%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.65%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.65%   |
| Intel Ethernet Connection (5) I219-V                              | 1        | 0.65%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.65%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.65%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.65%   |
| Huawei USB Device                                                 | 1        | 0.65%   |
| Huawei Android ADB Interface                                      | 1        | 0.65%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1        | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 145      | 74.36%  |
| WiFi     | 50       | 25.64%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 130      | 94.89%  |
| WiFi     | 7        | 5.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 103      | 68.21%  |
| 2     | 40       | 26.49%  |
| 3     | 4        | 2.65%   |
| 0     | 4        | 2.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 143      | 93.46%  |
| Yes  | 10       | 6.54%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 30.23%  |
| Realtek Semiconductor           | 9        | 20.93%  |
| Cambridge Silicon Radio         | 8        | 18.6%   |
| TP-Link                         | 2        | 4.65%   |
| IMC Networks                    | 2        | 4.65%   |
| Broadcom                        | 2        | 4.65%   |
| ASUSTek Computer                | 2        | 4.65%   |
| Apple                           | 2        | 4.65%   |
| Qualcomm Atheros Communications | 1        | 2.33%   |
| Primax Electronics              | 1        | 2.33%   |
| Fujitsu                         | 1        | 2.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 8        | 18.6%   |
| Realtek Bluetooth Adapter                                   | 7        | 16.28%  |
| Intel Bluetooth wireless interface                          | 7        | 16.28%  |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2        | 4.65%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2        | 4.65%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2        | 4.65%   |
| Intel AX201 Bluetooth                                       | 2        | 4.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2        | 4.65%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 2.33%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1        | 2.33%   |
| Intel AX210 Bluetooth                                       | 1        | 2.33%   |
| Intel AX200 Bluetooth                                       | 1        | 2.33%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS     | 1        | 2.33%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1        | 2.33%   |
| Fujitsu Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter  | 1        | 2.33%   |
| ASUS USB-BT500                                              | 1        | 2.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 2.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 2.33%   |
| Apple Bluetooth Host Controller                             | 1        | 2.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 105      | 44.68%  |
| AMD                    | 54       | 22.98%  |
| Nvidia                 | 45       | 19.15%  |
| C-Media Electronics    | 13       | 5.53%   |
| Texas Instruments      | 4        | 1.7%    |
| Realtek Semiconductor  | 2        | 0.85%   |
| Creative Labs          | 2        | 0.85%   |
| Yamaha                 | 1        | 0.43%   |
| Razer USA              | 1        | 0.43%   |
| OPPO Electronics       | 1        | 0.43%   |
| KTMicro                | 1        | 0.43%   |
| Hewlett-Packard        | 1        | 0.43%   |
| Harman                 | 1        | 0.43%   |
| Generalplus Technology | 1        | 0.43%   |
| GEMBIRD                | 1        | 0.43%   |
| Edifier Technology     | 1        | 0.43%   |
| Unknown                | 1        | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18       | 6.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15       | 5.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13       | 4.74%   |
| Intel 200 Series PCH HD Audio                                              | 13       | 4.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12       | 4.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11       | 4.01%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 2.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 2.92%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 8        | 2.92%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 2.55%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 2.55%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 6        | 2.19%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 2.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 2.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 2.19%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 5        | 1.82%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.46%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 1.46%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 1.46%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.09%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.09%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 1.09%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.09%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 1.09%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.73%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.73%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 0.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 0.73%   |
| Intel Jasper Lake HD Audio                                                 | 2        | 0.73%   |
| Intel Comet Lake PCH-V cAVS                                                | 2        | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2        | 0.73%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 34       | 18.99%  |
| Samsung Electronics | 25       | 13.97%  |
| Unknown             | 19       | 10.61%  |
| Corsair             | 15       | 8.38%   |
| Crucial             | 14       | 7.82%   |
| SK hynix            | 12       | 6.7%    |
| Micron Technology   | 10       | 5.59%   |
| G.Skill             | 8        | 4.47%   |
| Unknown             | 7        | 3.91%   |
| Nanya Technology    | 4        | 2.23%   |
| Ramaxel Technology  | 3        | 1.68%   |
| Patriot             | 3        | 1.68%   |
| Apacer              | 3        | 1.68%   |
| A-DATA Technology   | 3        | 1.68%   |
| Unknown (ABCD)      | 2        | 1.12%   |
| Kingmax             | 2        | 1.12%   |
| GOODRAM             | 2        | 1.12%   |
| Atermiter           | 2        | 1.12%   |
| Transcend           | 1        | 0.56%   |
| Team                | 1        | 0.56%   |
| Smart               | 1        | 0.56%   |
| Qumo                | 1        | 0.56%   |
| MemoWise            | 1        | 0.56%   |
| Lexar               | 1        | 0.56%   |
| Juhor               | 1        | 0.56%   |
| Golden Empire       | 1        | 0.56%   |
| Elpida              | 1        | 0.56%   |
| Avant               | 1        | 0.56%   |
| AMD                 | 1        | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 7        | 3.63%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 2        | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                | 2        | 1.04%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                     | 2        | 1.04%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 2        | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s          | 2        | 1.04%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                             | 2        | 1.04%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                     | 2        | 1.04%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s                     | 2        | 1.04%   |
| Samsung RAM M3 78T2863DZS-CE6 1GB DIMM DDR2 667MT/s                     | 2        | 1.04%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                       | 2        | 1.04%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                     | 2        | 1.04%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                     | 2        | 1.04%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 2        | 1.04%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                   | 2        | 1.04%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 0.52%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                    | 1        | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1        | 0.52%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 1        | 0.52%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                    | 1        | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                               | 1        | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                               | 1        | 0.52%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                                 | 1        | 0.52%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                     | 1        | 0.52%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                                | 1        | 0.52%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                | 1        | 0.52%   |
| Unknown RAM Module 1GB DIMM DDR2                                        | 1        | 0.52%   |
| Unknown RAM Module 1GB DIMM DDR 667MT/s                                 | 1        | 0.52%   |
| Unknown RAM Module 1GB DIMM 400MT/s                                     | 1        | 0.52%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s                       | 1        | 0.52%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                              | 1        | 0.52%   |
| Smart RAM SH564128FH8N0QNSCG 4GB DIMM DDR3 1600MT/s                     | 1        | 0.52%   |
| SK hynix RAM Module 2GB DIMM DDR2 1639MT/s                              | 1        | 0.52%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                           | 1        | 0.52%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1333MT/s                    | 1        | 0.52%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB DIMM DDR3 1600MT/s                    | 1        | 0.52%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1067MT/s                    | 1        | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                  | 1        | 0.52%   |
| SK hynix RAM HMT125U6AFP8C-G7 2GB DIMM DDR3 1066MT/s                    | 1        | 0.52%   |
| SK hynix RAM HMT125S6AFP8C-G7 2GB SODIMM DDR3 1067MT/s                  | 1        | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 68       | 45.33%  |
| DDR3    | 54       | 36%     |
| DDR2    | 12       | 8%      |
| Unknown | 10       | 6.67%   |
| SDRAM   | 2        | 1.33%   |
| LPDDR4  | 2        | 1.33%   |
| DDR     | 2        | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 127      | 85.23%  |
| SODIMM | 22       | 14.77%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 67       | 39.64%  |
| 4096  | 44       | 26.04%  |
| 2048  | 30       | 17.75%  |
| 16384 | 18       | 10.65%  |
| 1024  | 10       | 5.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 30       | 18.75%  |
| 1333    | 28       | 17.5%   |
| 2400    | 16       | 10%     |
| 2133    | 16       | 10%     |
| 2667    | 15       | 9.38%   |
| 3200    | 13       | 8.13%   |
| 800     | 9        | 5.63%   |
| 3600    | 5        | 3.13%   |
| 1067    | 5        | 3.13%   |
| 667     | 5        | 3.13%   |
| 2666    | 3        | 1.88%   |
| 1066    | 3        | 1.88%   |
| 3000    | 2        | 1.25%   |
| 400     | 2        | 1.25%   |
| Unknown | 2        | 1.25%   |
| 4400    | 1        | 0.63%   |
| 3333    | 1        | 0.63%   |
| 1867    | 1        | 0.63%   |
| 1639    | 1        | 0.63%   |
| 1200    | 1        | 0.63%   |
| 533     | 1        | 0.63%   |

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
| 1     | 69       | 45.7%   |
| 0     | 50       | 33.11%  |
| 2     | 28       | 18.54%  |
| 3     | 3        | 1.99%   |
| 4     | 1        | 0.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 91       | 71.65%  |
| Net/wireless             | 17       | 13.39%  |
| Sound                    | 12       | 9.45%   |
| Bluetooth                | 4        | 3.15%   |
| Card reader              | 2        | 1.57%   |
| Dvb card                 | 1        | 0.79%   |

