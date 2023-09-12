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

Total: 189

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| MSI           | Z390-A PRO                  | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| Dell          | 0YXT71 A02                  | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [3dab6f4044](https://bsd-hardware.info/?probe=3dab6f4044) | Aug 28, 2023 |
| MSI           | H110M PRO-VD                | [dcbd4ebf8f](https://bsd-hardware.info/?probe=dcbd4ebf8f) | Aug 27, 2023 |
| AZW           | U59                         | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| MSI           | MAG B460M BAZOOKA           | [7cf9279c14](https://bsd-hardware.info/?probe=7cf9279c14) | Aug 22, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [35eb7df9a7](https://bsd-hardware.info/?probe=35eb7df9a7) | Aug 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [7e1d475356](https://bsd-hardware.info/?probe=7e1d475356) | Aug 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [df095be4ba](https://bsd-hardware.info/?probe=df095be4ba) | Aug 18, 2023 |
| Daten Tecn... | DH110MXV                    | [bdd9c72e7c](https://bsd-hardware.info/?probe=bdd9c72e7c) | Aug 18, 2023 |
| ASRock        | B450 Pro4                   | [c12a76c083](https://bsd-hardware.info/?probe=c12a76c083) | Aug 16, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [f25db83457](https://bsd-hardware.info/?probe=f25db83457) | Aug 15, 2023 |
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
| amd64 | 161      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 160      | 99.38%  |
| GNOME        | 1        | 0.62%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 161      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 161      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 63       | 38.65%  |
| fr_FR   | 48       | 29.45%  |
| ru_RU   | 12       | 7.36%   |
| es_ES   | 10       | 6.13%   |
| de_DE   | 10       | 6.13%   |
| pt_BR   | 5        | 3.07%   |
| it_IT   | 5        | 3.07%   |
| Unknown | 4        | 2.45%   |
| pl_PL   | 2        | 1.23%   |
| jp_JP   | 2        | 1.23%   |
| fr      | 1        | 0.61%   |
| es      | 1        | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 158      | 98.14%  |
| BIOS | 3        | 1.86%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 93       | 56.36%  |
| Zfs    | 72       | 43.64%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 158      | 98.14%  |
| MBR  | 3        | 1.86%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 38       | 23.6%   |
| Gigabyte Technology | 25       | 15.53%  |
| Hewlett-Packard     | 17       | 10.56%  |
| Dell                | 15       | 9.32%   |
| MSI                 | 12       | 7.45%   |
| ASRock              | 9        | 5.59%   |
| Lenovo              | 8        | 4.97%   |
| Intel               | 7        | 4.35%   |
| Unknown             | 5        | 3.11%   |
| Acer                | 4        | 2.48%   |
| Fujitsu             | 3        | 1.86%   |
| T-bao               | 2        | 1.24%   |
| Fujitsu Siemens     | 2        | 1.24%   |
| Foxconn             | 2        | 1.24%   |
| AZW                 | 2        | 1.24%   |
| Pegatron            | 1        | 0.62%   |
| LG Electronics      | 1        | 0.62%   |
| Huanan              | 1        | 0.62%   |
| Google              | 1        | 0.62%   |
| ECS                 | 1        | 0.62%   |
| Daten Tecnologia    | 1        | 0.62%   |
| Biostar             | 1        | 0.62%   |
| BESSTAR Tech        | 1        | 0.62%   |
| Axiomtek            | 1        | 0.62%   |
| Apple               | 1        | 0.62%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 5        | 3.11%   |
| T-bao MINI PC                       | 2        | 1.24%   |
| MSI MS-7788                         | 2        | 1.24%   |
| Intel H81                           | 2        | 1.24%   |
| HP EliteDesk 800 G2 DM 35W          | 2        | 1.24%   |
| HP Compaq Elite 8300 USDT           | 2        | 1.24%   |
| Dell OptiPlex 7010                  | 2        | 1.24%   |
| ASUS ROG STRIX B550-F GAMING        | 2        | 1.24%   |
| ASUS PRIME B250M-A                  | 2        | 1.24%   |
| ASUS All Series                     | 2        | 1.24%   |
| Pegatron Compaq dx2450 Microtower   | 1        | 0.62%   |
| MSI MS-7C95                         | 1        | 0.62%   |
| MSI MS-7C83                         | 1        | 0.62%   |
| MSI MS-7C51                         | 1        | 0.62%   |
| MSI MS-7C09                         | 1        | 0.62%   |
| MSI MS-7B98                         | 1        | 0.62%   |
| MSI MS-7B86                         | 1        | 0.62%   |
| MSI MS-7B17                         | 1        | 0.62%   |
| MSI MS-7996                         | 1        | 0.62%   |
| MSI MS-7599                         | 1        | 0.62%   |
| MSI Compaq dx2200 MT                | 1        | 0.62%   |
| LG R590-K.AAA9BT                    | 1        | 0.62%   |
| Lenovo ThinkCentre M900 10FLS15P00  | 1        | 0.62%   |
| Lenovo ThinkCentre M900 10FGS05C08  | 1        | 0.62%   |
| Lenovo ThinkCentre M75e 5065A11     | 1        | 0.62%   |
| Lenovo ThinkCentre M73 10AYA06EIA   | 1        | 0.62%   |
| Lenovo ThinkCentre M73 10AXS34800   | 1        | 0.62%   |
| Lenovo ThinkCentre M710s 10M8S0FW00 | 1        | 0.62%   |
| Lenovo ThinkCentre M58p 6138DK1     | 1        | 0.62%   |
| Lenovo ThinkCentre Edge72 34971B1   | 1        | 0.62%   |
| Intel X99                           | 1        | 0.62%   |
| Intel Jasper Lake Client Platform   | 1        | 0.62%   |
| Intel DH87RL AAG74240-400           | 1        | 0.62%   |
| Intel DG41TY AAE47335-300           | 1        | 0.62%   |
| Intel DB85FL AAG89861-203           | 1        | 0.62%   |
| Huanan X99-TF GAMING V3.0           | 1        | 0.62%   |
| HP Z4 G4 Workstation                | 1        | 0.62%   |
| HP Slim Desktop S01-pF1xxx          | 1        | 0.62%   |
| HP rp5800                           | 1        | 0.62%   |
| HP ProDesk 600 G3 SFF               | 1        | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 12       | 7.45%   |
| Lenovo ThinkCentre      | 8        | 4.97%   |
| Dell OptiPlex           | 8        | 4.97%   |
| ASUS ROG                | 8        | 4.97%   |
| HP EliteDesk            | 5        | 3.11%   |
| HP Compaq               | 5        | 3.11%   |
| Unknown                 | 5        | 3.11%   |
| Dell Precision          | 3        | 1.86%   |
| T-bao MINI              | 2        | 1.24%   |
| MSI MS-7788             | 2        | 1.24%   |
| Intel H81               | 2        | 1.24%   |
| HP ProDesk              | 2        | 1.24%   |
| Gigabyte B450M          | 2        | 1.24%   |
| Fujitsu Siemens ESPRIMO | 2        | 1.24%   |
| Fujitsu ESPRIMO         | 2        | 1.24%   |
| Dell Vostro             | 2        | 1.24%   |
| Dell Inspiron           | 2        | 1.24%   |
| ASUS TUF                | 2        | 1.24%   |
| ASUS All                | 2        | 1.24%   |
| Acer Veriton            | 2        | 1.24%   |
| Pegatron Compaq         | 1        | 0.62%   |
| MSI MS-7C95             | 1        | 0.62%   |
| MSI MS-7C83             | 1        | 0.62%   |
| MSI MS-7C51             | 1        | 0.62%   |
| MSI MS-7C09             | 1        | 0.62%   |
| MSI MS-7B98             | 1        | 0.62%   |
| MSI MS-7B86             | 1        | 0.62%   |
| MSI MS-7B17             | 1        | 0.62%   |
| MSI MS-7996             | 1        | 0.62%   |
| MSI MS-7599             | 1        | 0.62%   |
| MSI Compaq              | 1        | 0.62%   |
| LG R590-K.AAA9BT        | 1        | 0.62%   |
| Intel X99               | 1        | 0.62%   |
| Intel Jasper            | 1        | 0.62%   |
| Intel DH87RL            | 1        | 0.62%   |
| Intel DG41TY            | 1        | 0.62%   |
| Intel DB85FL            | 1        | 0.62%   |
| Huanan X99-TF           | 1        | 0.62%   |
| HP Z4                   | 1        | 0.62%   |
| HP Slim                 | 1        | 0.62%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2022    | 17       | 10.56%  |
| 2021    | 17       | 10.56%  |
| 2020    | 15       | 9.32%   |
| 2013    | 15       | 9.32%   |
| 2012    | 14       | 8.7%    |
| 2019    | 12       | 7.45%   |
| 2010    | 11       | 6.83%   |
| 2018    | 9        | 5.59%   |
| 2016    | 8        | 4.97%   |
| 2014    | 8        | 4.97%   |
| 2017    | 7        | 4.35%   |
| 2011    | 7        | 4.35%   |
| 2023    | 4        | 2.48%   |
| 2015    | 4        | 2.48%   |
| 2009    | 4        | 2.48%   |
| 2008    | 4        | 2.48%   |
| 2007    | 2        | 1.24%   |
| 2006    | 2        | 1.24%   |
| Unknown | 1        | 0.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 161      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 160      | 99.38%  |
| Yes  | 1        | 0.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 58       | 36.02%  |
| 16.01-24.0  | 45       | 27.95%  |
| 4.01-8.0    | 28       | 17.39%  |
| 32.01-64.0  | 17       | 10.56%  |
| 2.01-3.0    | 4        | 2.48%   |
| 64.01-256.0 | 4        | 2.48%   |
| 24.01-32.0  | 3        | 1.86%   |
| 3.01-4.0    | 1        | 0.62%   |
| 0.51-1.0    | 1        | 0.62%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 73       | 44.79%  |
| 0.51-1.0 | 58       | 35.58%  |
| 1.01-2.0 | 21       | 12.88%  |
| 2.01-3.0 | 9        | 5.52%   |
| 3.01-4.0 | 2        | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 74       | 45.96%  |
| 2      | 37       | 22.98%  |
| 3      | 22       | 13.66%  |
| 0      | 11       | 6.83%   |
| 5      | 7        | 4.35%   |
| 4      | 4        | 2.48%   |
| 9      | 2        | 1.24%   |
| 6      | 2        | 1.24%   |
| 13     | 1        | 0.62%   |
| 7      | 1        | 0.62%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 62.73%  |
| Yes       | 60       | 37.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 156      | 96.89%  |
| No        | 5        | 3.11%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 108      | 66.67%  |
| Yes       | 54       | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 118      | 73.29%  |
| Yes       | 43       | 26.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| Russia             | 23       | 14.29%  |
| USA                | 21       | 13.04%  |
| Germany            | 11       | 6.83%   |
| Spain              | 10       | 6.21%   |
| Brazil             | 8        | 4.97%   |
| Italy              | 7        | 4.35%   |
| Canada             | 7        | 4.35%   |
| Hungary            | 6        | 3.73%   |
| Serbia             | 5        | 3.11%   |
| Romania            | 5        | 3.11%   |
| Poland             | 5        | 3.11%   |
| France             | 5        | 3.11%   |
| Australia          | 5        | 3.11%   |
| UK                 | 3        | 1.86%   |
| Turkey             | 3        | 1.86%   |
| Peru               | 3        | 1.86%   |
| Mexico             | 3        | 1.86%   |
| Belgium            | 3        | 1.86%   |
| Ukraine            | 2        | 1.24%   |
| Sweden             | 2        | 1.24%   |
| Japan              | 2        | 1.24%   |
| India              | 2        | 1.24%   |
| China              | 2        | 1.24%   |
| Bulgaria           | 2        | 1.24%   |
| Argentina          | 2        | 1.24%   |
| Switzerland        | 1        | 0.62%   |
| South Korea        | 1        | 0.62%   |
| Slovenia           | 1        | 0.62%   |
| San Marino         | 1        | 0.62%   |
| Netherlands        | 1        | 0.62%   |
| Kyrgyzstan         | 1        | 0.62%   |
| Kazakhstan         | 1        | 0.62%   |
| Indonesia          | 1        | 0.62%   |
| Dominican Republic | 1        | 0.62%   |
| Croatia            | 1        | 0.62%   |
| Chile              | 1        | 0.62%   |
| Belarus            | 1        | 0.62%   |
| Austria            | 1        | 0.62%   |
| Algeria            | 1        | 0.62%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| St. Jean Baptiste | 3        | 1.84%   |
| Moscow            | 3        | 1.84%   |
| Belgrade          | 3        | 1.84%   |
| Sydney            | 2        | 1.23%   |
| St Petersburg     | 2        | 1.23%   |
| Penza             | 2        | 1.23%   |
| Paris             | 2        | 1.23%   |
| Melbourne         | 2        | 1.23%   |
| Madrid            | 2        | 1.23%   |
| Kirov             | 2        | 1.23%   |
| Curitiba          | 2        | 1.23%   |
| Brooklyn          | 2        | 1.23%   |
| Berlin            | 2        | 1.23%   |
| Zurich            | 1        | 0.61%   |
| Zhengzhou         | 1        | 0.61%   |
| Yokohama          | 1        | 0.61%   |
| Woodbridge        | 1        | 0.61%   |
| Winnipeg          | 1        | 0.61%   |
| Warsaw            | 1        | 0.61%   |
| Volgodonsk        | 1        | 0.61%   |
| Vogogna           | 1        | 0.61%   |
| Virovitica        | 1        | 0.61%   |
| Villena           | 1        | 0.61%   |
| Vienna            | 1        | 0.61%   |
| Venice            | 1        | 0.61%   |
| Vecses            | 1        | 0.61%   |
| Valderrobres      | 1        | 0.61%   |
| Ubstadt-Weiher    | 1        | 0.61%   |
| Tucson            | 1        | 0.61%   |
| Trumbull          | 1        | 0.61%   |
| Trieste           | 1        | 0.61%   |
| Trekhgornyy       | 1        | 0.61%   |
| Topolovgrad       | 1        | 0.61%   |
| Tolmin            | 1        | 0.61%   |
| Tokmok            | 1        | 0.61%   |
| Timișoara        | 1        | 0.61%   |
| Temple            | 1        | 0.61%   |
| Superior          | 1        | 0.61%   |
| Stuttgart         | 1        | 0.61%   |
| Stevenage         | 1        | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 47       | 73     | 18.29%  |
| Seagate             | 36       | 51     | 14.01%  |
| Samsung Electronics | 35       | 51     | 13.62%  |
| Kingston            | 28       | 28     | 10.89%  |
| Toshiba             | 14       | 18     | 5.45%   |
| Crucial             | 10       | 12     | 3.89%   |
| SanDisk             | 9        | 9      | 3.5%    |
| China               | 7        | 8      | 2.72%   |
| A-DATA Technology   | 7        | 8      | 2.72%   |
| Hitachi             | 5        | 6      | 1.95%   |
| Transcend           | 4        | 4      | 1.56%   |
| Patriot             | 4        | 4      | 1.56%   |
| Micron Technology   | 4        | 5      | 1.56%   |
| Maxtor              | 4        | 4      | 1.56%   |
| KingSpec            | 4        | 4      | 1.56%   |
| SPCC                | 3        | 3      | 1.17%   |
| Intel               | 3        | 3      | 1.17%   |
| Team                | 2        | 2      | 0.78%   |
| PNY                 | 2        | 2      | 0.78%   |
| Gigabyte Technology | 2        | 3      | 0.78%   |
| WALRAM              | 1        | 1      | 0.39%   |
| Vaseky              | 1        | 1      | 0.39%   |
| TAMMUZ              | 1        | 1      | 0.39%   |
| Silicon Motion      | 1        | 1      | 0.39%   |
| SETHRISE            | 1        | 1      | 0.39%   |
| QUANTUM             | 1        | 1      | 0.39%   |
| Pioneer             | 1        | 1      | 0.39%   |
| Philips             | 1        | 1      | 0.39%   |
| Palit               | 1        | 1      | 0.39%   |
| OCZ                 | 1        | 1      | 0.39%   |
| Netac               | 1        | 1      | 0.39%   |
| LITEONIT            | 1        | 1      | 0.39%   |
| Kston               | 1        | 1      | 0.39%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.39%   |
| KIOXIA              | 1        | 1      | 0.39%   |
| Intenso             | 1        | 1      | 0.39%   |
| HGST                | 1        | 1      | 0.39%   |
| HEORIADY            | 1        | 1      | 0.39%   |
| GOODRAM             | 1        | 1      | 0.39%   |
| EDGE                | 1        | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 7        | 2.29%   |
| Seagate ST500DM002-1BD142 500GB | 5        | 1.63%   |
| Seagate ST3500418AS 500GB       | 4        | 1.31%   |
| Seagate ST1000DM010-2EP102 1TB  | 4        | 1.31%   |
| Samsung SSD 860 EVO 500GB       | 4        | 1.31%   |
| Samsung SSD 850 EVO 250GB       | 4        | 1.31%   |
| WDC WD10EZEX-08WN4A0 1TB        | 3        | 0.98%   |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 0.98%   |
| Samsung SSD 980 1TB             | 3        | 0.98%   |
| Samsung SSD 870 EVO 500GB       | 3        | 0.98%   |
| Kingston SA400S37120G 120GB     | 3        | 0.98%   |
| Crucial CT500MX500SSD1 500GB    | 3        | 0.98%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 0.98%   |
| WDC WDS240G2G0A-00JH30 240GB    | 2        | 0.65%   |
| WDC WDS120G2G0A-00JH30 120GB    | 2        | 0.65%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 2        | 0.65%   |
| WDC WD20EZRX-00D8PB0 2TB        | 2        | 0.65%   |
| WDC WD20EFRX-68EUZN0 2TB        | 2        | 0.65%   |
| WDC WD10EZEX-60WN4A1 1TB        | 2        | 0.65%   |
| WDC WD10EZEX-60WN4A0 1TB        | 2        | 0.65%   |
| Toshiba HDWD110 1TB             | 2        | 0.65%   |
| Toshiba DT01ACA100 1TB          | 2        | 0.65%   |
| Toshiba DT01ACA050 500GB        | 2        | 0.65%   |
| SPCC Solid State Disk 128GB     | 2        | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 0.65%   |
| SanDisk pSSD 256GB              | 2        | 0.65%   |
| Samsung SSD 980 PRO 500GB       | 2        | 0.65%   |
| Samsung SSD 970 PRO 512GB       | 2        | 0.65%   |
| Samsung SSD 970 EVO Plus 500GB  | 2        | 0.65%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 0.65%   |
| Patriot Burst Elite 120GB       | 2        | 0.65%   |
| Kingston SHFS37A240G 240GB      | 2        | 0.65%   |
| Kingston SA400S37480G 480GB     | 2        | 0.65%   |
| WDC WDS500G2B0A-00SM50 500GB    | 1        | 0.33%   |
| WDC WDS500G1B0A-00H9H0 500GB    | 1        | 0.33%   |
| WDC WDS250G1B0A-00H9H0 250GB    | 1        | 0.33%   |
| WDC WD800JD-75MSA3 80GB         | 1        | 0.33%   |
| WDC WD800AAJS-00PSA0 80GB       | 1        | 0.33%   |
| WDC WD7501AALS-00J7B0 752GB     | 1        | 0.33%   |
| WDC WD6400BPVT-22HXZT3 640GB    | 1        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 40       | 64     | 39.22%  |
| Seagate             | 36       | 51     | 35.29%  |
| Toshiba             | 11       | 14     | 10.78%  |
| Hitachi             | 5        | 6      | 4.9%    |
| Maxtor              | 4        | 4      | 3.92%   |
| Samsung Electronics | 3        | 4      | 2.94%   |
| QUANTUM             | 1        | 1      | 0.98%   |
| HGST                | 1        | 1      | 0.98%   |
| Apple               | 1        | 1      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 19       | 26     | 16.67%  |
| Kingston            | 19       | 19     | 16.67%  |
| SanDisk             | 9        | 9      | 7.89%   |
| Crucial             | 9        | 10     | 7.89%   |
| WDC                 | 7        | 7      | 6.14%   |
| China               | 7        | 8      | 6.14%   |
| Patriot             | 4        | 4      | 3.51%   |
| KingSpec            | 4        | 4      | 3.51%   |
| A-DATA Technology   | 4        | 4      | 3.51%   |
| Transcend           | 3        | 3      | 2.63%   |
| Toshiba             | 3        | 4      | 2.63%   |
| SPCC                | 2        | 2      | 1.75%   |
| PNY                 | 2        | 2      | 1.75%   |
| WALRAM              | 1        | 1      | 0.88%   |
| Vaseky              | 1        | 1      | 0.88%   |
| Team                | 1        | 1      | 0.88%   |
| TAMMUZ              | 1        | 1      | 0.88%   |
| SETHRISE            | 1        | 1      | 0.88%   |
| Pioneer             | 1        | 1      | 0.88%   |
| Philips             | 1        | 1      | 0.88%   |
| Palit               | 1        | 1      | 0.88%   |
| OCZ                 | 1        | 1      | 0.88%   |
| Micron Technology   | 1        | 1      | 0.88%   |
| LITEONIT            | 1        | 1      | 0.88%   |
| Kston               | 1        | 1      | 0.88%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.88%   |
| Intenso             | 1        | 1      | 0.88%   |
| Intel               | 1        | 1      | 0.88%   |
| HEORIADY            | 1        | 1      | 0.88%   |
| GOODRAM             | 1        | 1      | 0.88%   |
| Gigabyte Technology | 1        | 2      | 0.88%   |
| EDGE                | 1        | 1      | 0.88%   |
| Azerty              | 1        | 1      | 0.88%   |
| Apacer              | 1        | 1      | 0.88%   |
| AMD                 | 1        | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 88       | 125    | 40.18%  |
| HDD  | 86       | 146    | 39.27%  |
| NVMe | 45       | 54     | 20.55%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 142      | 271    | 75.94%  |
| NVMe | 45       | 54     | 24.06%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 118      | 172    | 63.78%  |
| 0.51-1.0   | 38       | 47     | 20.54%  |
| 1.01-2.0   | 15       | 29     | 8.11%   |
| 3.01-4.0   | 8        | 10     | 4.32%   |
| 4.01-10.0  | 3        | 7      | 1.62%   |
| 2.01-3.0   | 2        | 5      | 1.08%   |
| 10.01-20.0 | 1        | 1      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 88       | 53.66%  |
| 101-250    | 23       | 14.02%  |
| 251-500    | 20       | 12.2%   |
| 51-100     | 20       | 12.2%   |
| 501-1000   | 9        | 5.49%   |
| 21-50      | 2        | 1.22%   |
| 1001-2000  | 1        | 0.61%   |
| Unknown    | 1        | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 158      | 98.14%  |
| 251-500 | 1        | 0.62%   |
| 21-50   | 1        | 0.62%   |
| Unknown | 1        | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| WDC WD800JD-75MSA3 80GB                    | 1        | 1      | 2.63%   |
| WDC WD6400BPVT-22HXZT3 640GB               | 1        | 1      | 2.63%   |
| WDC WD5000AAKX-08U6AA0 500GB               | 1        | 1      | 2.63%   |
| WDC WD5000AAKX-00ERMA0 500GB               | 1        | 1      | 2.63%   |
| WDC WD30EFRX-68EUZN0 3TB                   | 1        | 1      | 2.63%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1        | 1      | 2.63%   |
| WDC WD20EARS-00MVWB0 2TB                   | 1        | 1      | 2.63%   |
| WDC WD1600YS-01SHB1 164GB                  | 1        | 1      | 2.63%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 1      | 2.63%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1        | 1      | 2.63%   |
| WDC WD10EZEX-60M2NA0 1TB                   | 1        | 1      | 2.63%   |
| WDC WD10EARS-003BB1 1TB                    | 1        | 1      | 2.63%   |
| WDC WD10EADS-11M2B2 1TB                    | 1        | 1      | 2.63%   |
| Toshiba MK3259GSXP 320GB                   | 1        | 1      | 2.63%   |
| Toshiba DT01ACA100 1TB                     | 1        | 1      | 2.63%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB  | 1        | 1      | 2.63%   |
| Seagate ST500LM000-1EJ162 500GB            | 1        | 1      | 2.63%   |
| Seagate ST500DM002-1BD142 500GB            | 1        | 1      | 2.63%   |
| Seagate ST380215AS 80GB                    | 1        | 1      | 2.63%   |
| Seagate ST3750528AS 752GB                  | 1        | 1      | 2.63%   |
| Seagate ST3500418AS 500GB                  | 1        | 1      | 2.63%   |
| Seagate ST3500320AS 500GB                  | 1        | 1      | 2.63%   |
| Seagate ST3320620AS 320GB                  | 1        | 1      | 2.63%   |
| Seagate ST3250312AS 250GB                  | 1        | 2      | 2.63%   |
| Seagate ST2000DM008-2FR102 2TB             | 1        | 1      | 2.63%   |
| Seagate ST1000DM010-2EP102 1TB             | 1        | 1      | 2.63%   |
| Samsung Electronics SSD 860 EVO 500GB      | 1        | 1      | 2.63%   |
| Samsung Electronics MZVL22T0HBLB-00B00 2TB | 1        | 1      | 2.63%   |
| Samsung Electronics HD103SJ 1TB            | 1        | 1      | 2.63%   |
| Maxtor 6Y080M0 82GB                        | 1        | 1      | 2.63%   |
| Maxtor 6V080E0 80GB                        | 1        | 1      | 2.63%   |
| Maxtor 6L080P0 82GB                        | 1        | 1      | 2.63%   |
| Kingston SA400S37240G 240GB                | 1        | 1      | 2.63%   |
| Hitachi HTS725050A7E630 500GB              | 1        | 1      | 2.63%   |
| Hitachi HTS541680J9SA00 80GB               | 1        | 1      | 2.63%   |
| HGST HTS545050A7E680 500GB                 | 1        | 1      | 2.63%   |
| Crucial CT1050MX300SSD1 1TB                | 1        | 1      | 2.63%   |
| China SH00R120GB                           | 1        | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 13     | 34.29%  |
| Seagate             | 8        | 11     | 22.86%  |
| Samsung Electronics | 3        | 3      | 8.57%   |
| Maxtor              | 3        | 3      | 8.57%   |
| Toshiba             | 2        | 2      | 5.71%   |
| Hitachi             | 2        | 2      | 5.71%   |
| Silicon Motion      | 1        | 1      | 2.86%   |
| Kingston            | 1        | 1      | 2.86%   |
| HGST                | 1        | 1      | 2.86%   |
| Crucial             | 1        | 1      | 2.86%   |
| China               | 1        | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 13     | 41.38%  |
| Seagate             | 8        | 11     | 27.59%  |
| Maxtor              | 3        | 3      | 10.34%  |
| Toshiba             | 2        | 2      | 6.9%    |
| Hitachi             | 2        | 2      | 6.9%    |
| Samsung Electronics | 1        | 1      | 3.45%   |
| HGST                | 1        | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 29       | 33     | 82.86%  |
| SSD  | 4        | 4      | 11.43%  |
| NVMe | 2        | 2      | 5.71%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB | 1        | 1      | 33.33%  |
| WDC WD1600BEVT-22ZCT0 160GB | 1        | 1      | 33.33%  |
| SanDisk pSSD 256GB          | 1        | 1      | 33.33%  |

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
| Works    | 126      | 268    | 72.83%  |
| Malfunc  | 35       | 39     | 20.23%  |
| Detected | 9        | 15     | 5.2%    |
| Failed   | 3        | 3      | 1.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 116      | 52.25%  |
| AMD                         | 39       | 17.57%  |
| Samsung Electronics         | 17       | 7.66%   |
| Kingston Technology Company | 9        | 4.05%   |
| Silicon Motion              | 5        | 2.25%   |
| Marvell Technology Group    | 5        | 2.25%   |
| ASMedia Technology          | 5        | 2.25%   |
| Nvidia                      | 4        | 1.8%    |
| SanDisk                     | 3        | 1.35%   |
| Micron Technology           | 3        | 1.35%   |
| JMicron Technology          | 3        | 1.35%   |
| VIA Technologies            | 2        | 0.9%    |
| Realtek Semiconductor       | 2        | 0.9%    |
| Phison Electronics          | 2        | 0.9%    |
| Micron/Crucial Technology   | 2        | 0.9%    |
| ADATA Technology            | 2        | 0.9%    |
| OCZ Technology Group        | 1        | 0.45%   |
| KIOXIA                      | 1        | 0.45%   |
| Broadcom / LSI              | 1        | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 5.82%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 16       | 5.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 5.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 4%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 4%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 3.27%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 3.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 3.27%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 2.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 2.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.18%   |
| Samsung NVMe SSD Controller 980                                                         | 5        | 1.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 1.82%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4        | 1.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.45%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.45%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 1.45%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.09%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.09%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.09%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 1.09%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3        | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3        | 1.09%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.09%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.09%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.73%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.73%   |
| Micron 2200S NVMe SSD [Cassandra]                                                       | 2        | 0.73%   |
| Kingston Company unknown                                                                | 2        | 0.73%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 2        | 0.73%   |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.73%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 125      | 58.14%  |
| NVMe | 44       | 20.47%  |
| IDE  | 36       | 16.74%  |
| RAID | 8        | 3.72%   |
| SAS  | 1        | 0.47%   |
| SCSI | 1        | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 118      | 73.29%  |
| AMD    | 43       | 26.71%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz              | 5        | 3.11%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4        | 2.48%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4        | 2.48%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3        | 1.86%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3        | 1.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3        | 1.86%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 3        | 1.86%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 1.86%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3        | 1.86%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 1.24%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2        | 1.24%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2        | 1.24%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2        | 1.24%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2        | 1.24%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 2        | 1.24%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 2        | 1.24%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2        | 1.24%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2        | 1.24%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2        | 1.24%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 2        | 1.24%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2        | 1.24%   |
| Intel Celeron N5105 @ 2.00GHz                 | 2        | 1.24%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2        | 1.24%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 2        | 1.24%   |
| Intel 12th Gen Core i5-12400                  | 2        | 1.24%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2        | 1.24%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2        | 1.24%   |
| Intel Xeon W-2125 CPU @ 4.00GHz               | 1        | 0.62%   |
| Intel Xeon CPU W3670 @ 3.20GHz                | 1        | 0.62%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1        | 0.62%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1        | 0.62%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1        | 0.62%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1        | 0.62%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz           | 1        | 0.62%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz           | 1        | 0.62%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz           | 1        | 0.62%   |
| Intel Xeon                                    | 1        | 0.62%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1        | 0.62%   |
| Intel Pentium Dual-Core CPU E5300             | 1        | 0.62%   |
| Intel Pentium CPU G850 @ 2.90GHz              | 1        | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 33       | 20.5%   |
| Intel Core i3           | 23       | 14.29%  |
| Intel Core i7           | 18       | 11.18%  |
| AMD Ryzen 5             | 15       | 9.32%   |
| Intel Celeron           | 12       | 7.45%   |
| Intel Xeon              | 10       | 6.21%   |
| Intel Core 2 Duo        | 7        | 4.35%   |
| AMD Ryzen 3             | 6        | 3.73%   |
| AMD Ryzen 7             | 5        | 3.11%   |
| Other                   | 4        | 2.48%   |
| Intel Pentium           | 4        | 2.48%   |
| AMD Phenom II X4        | 3        | 1.86%   |
| AMD Athlon II X2        | 3        | 1.86%   |
| Intel Core i9           | 2        | 1.24%   |
| Intel Core 2 Quad       | 2        | 1.24%   |
| AMD A4                  | 2        | 1.24%   |
| Intel Pentium Gold      | 1        | 0.62%   |
| Intel Pentium Dual-Core | 1        | 0.62%   |
| Intel Pentium 4         | 1        | 0.62%   |
| AMD Ryzen 9             | 1        | 0.62%   |
| AMD Phenom II X6        | 1        | 0.62%   |
| AMD Phenom II X2        | 1        | 0.62%   |
| AMD FX                  | 1        | 0.62%   |
| AMD E                   | 1        | 0.62%   |
| AMD Athlon X2           | 1        | 0.62%   |
| AMD Athlon II X4        | 1        | 0.62%   |
| AMD Athlon 64           | 1        | 0.62%   |
| AMD A10                 | 1        | 0.62%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 69       | 42.86%  |
| 2       | 43       | 26.71%  |
| 6       | 17       | 10.56%  |
| 12      | 11       | 6.83%   |
| 8       | 9        | 5.59%   |
| 16      | 4        | 2.48%   |
| Unknown | 4        | 2.48%   |
| 1       | 2        | 1.24%   |
| 24      | 1        | 0.62%   |
| 10      | 1        | 0.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 159      | 98.76%  |
| 2      | 2        | 1.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 100      | 62.11%  |
| 2       | 56       | 34.78%  |
| Unknown | 5        | 3.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 21       | 13.04%  |
| KabyLake      | 19       | 11.8%   |
| IvyBridge     | 17       | 10.56%  |
| Skylake       | 15       | 9.32%   |
| Zen+          | 12       | 7.45%   |
| SandyBridge   | 11       | 6.83%   |
| K10           | 10       | 6.21%   |
| Zen 3         | 9        | 5.59%   |
| Penryn        | 8        | 4.97%   |
| CometLake     | 6        | 3.73%   |
| Unknown       | 6        | 3.73%   |
| Zen           | 5        | 3.11%   |
| Core          | 4        | 2.48%   |
| Piledriver    | 3        | 1.86%   |
| Nehalem       | 3        | 1.86%   |
| Westmere      | 2        | 1.24%   |
| Silvermont    | 2        | 1.24%   |
| Goldmont plus | 2        | 1.24%   |
| Zen 2         | 1        | 0.62%   |
| NetBurst      | 1        | 0.62%   |
| K8 Hammer     | 1        | 0.62%   |
| Goldmont      | 1        | 0.62%   |
| Bulldozer     | 1        | 0.62%   |
| Bobcat        | 1        | 0.62%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 73       | 42.44%  |
| Nvidia                     | 50       | 29.07%  |
| AMD                        | 48       | 27.91%  |
| Matrox Electronics Systems | 1        | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                       | 11       | 6.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 4.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 4%      |
| Intel HD Graphics 630                                                       | 7        | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 4%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7        | 4%      |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 3.43%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 2.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 2.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4        | 2.29%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 2.29%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 1.71%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.71%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.71%   |
| AMD RS880 [Radeon HD 4250]                                                  | 3        | 1.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.71%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.14%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.14%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.14%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.14%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 1.14%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 2        | 1.14%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.14%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.14%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.14%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 1.14%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 1.14%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 1.14%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.14%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.14%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.57%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.57%   |
| Nvidia GT218M [GeForce 310M]                                                | 1        | 0.57%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.57%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.57%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 0.57%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 56       | 34.36%  |
| 1 x Nvidia     | 46       | 28.22%  |
| 1 x AMD        | 40       | 24.54%  |
| Intel + AMD    | 8        | 4.91%   |
| 2 x Intel      | 6        | 3.68%   |
| Intel + Nvidia | 4        | 2.45%   |
| Other          | 1        | 0.61%   |
| 2 x AMD        | 1        | 0.61%   |
| 1 x Matrox     | 1        | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 123      | 75.93%  |
| Proprietary | 36       | 22.22%  |
| Unknown     | 3        | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 100      | 61.35%  |
| 1.01-2.0   | 17       | 10.43%  |
| 3.01-4.0   | 16       | 9.82%   |
| 0.51-1.0   | 10       | 6.13%   |
| 5.01-6.0   | 8        | 4.91%   |
| 0.01-0.5   | 6        | 3.68%   |
| 7.01-8.0   | 3        | 1.84%   |
| 8.01-16.0  | 2        | 1.23%   |
| 2.01-3.0   | 1        | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 7        | 10.94%  |
| Acer                 | 7        | 10.94%  |
| Hewlett-Packard      | 6        | 9.38%   |
| BenQ                 | 6        | 9.38%   |
| Dell                 | 5        | 7.81%   |
| Goldstar             | 4        | 6.25%   |
| AOC                  | 4        | 6.25%   |
| Ancor Communications | 4        | 6.25%   |
| Philips              | 3        | 4.69%   |
| LG Electronics       | 2        | 3.13%   |
| Lenovo               | 2        | 3.13%   |
| ASUSTek Computer     | 2        | 3.13%   |
| Unknown              | 2        | 3.13%   |
| Vizio                | 1        | 1.56%   |
| Semp Toshiba         | 1        | 1.56%   |
| PKB                  | 1        | 1.56%   |
| NEC Computers        | 1        | 1.56%   |
| Microstep            | 1        | 1.56%   |
| ITE                  | 1        | 1.56%   |
| Idek Iiyama          | 1        | 1.56%   |
| Eizo                 | 1        | 1.56%   |
| AUS                  | 1        | 1.56%   |
| Apple                | 1        | 1.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                      | 2        | 3.13%   |
| Unknown                                                                | 2        | 3.13%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                      | 1        | 1.56%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch              | 1        | 1.56%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch   | 1        | 1.56%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1        | 1.56%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1        | 1.56%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch       | 1        | 1.56%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 1        | 1.56%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 600x340mm 27.2-inch | 1        | 1.56%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch   | 1        | 1.56%   |
| PKB LCD Monitor MAE200W 1680x1050                                      | 1        | 1.56%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch                | 1        | 1.56%   |
| Philips PHL 221S8L PHL091C 1920x1080 480x270mm 21.7-inch               | 1        | 1.56%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                      | 1        | 1.56%   |
| NEC Computers LCD Monitor 70GX2 1280x1024                              | 1        | 1.56%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                            | 1        | 1.56%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 1.56%   |
| LG Electronics LCD Monitor L1918S 1280x1024                            | 1        | 1.56%   |
| Lenovo L24e-30 LEN66BC 1920x1080 530x300mm 24.0-inch                   | 1        | 1.56%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                    | 1        | 1.56%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                  | 1        | 1.56%   |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160                             | 1        | 1.56%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 600x340mm 27.2-inch          | 1        | 1.56%   |
| Hewlett-Packard Z24nq HWP3239 2560x1440 530x300mm 24.0-inch            | 1        | 1.56%   |
| Hewlett-Packard w2007 HWP26A6 1680x1050 430x270mm 20.0-inch            | 1        | 1.56%   |
| Hewlett-Packard L1955 HWP262C 1280x1024 380x300mm 19.1-inch            | 1        | 1.56%   |
| Hewlett-Packard 32 Display HPN351A 1920x1080 700x390mm 31.5-inch       | 1        | 1.56%   |
| Hewlett-Packard 27o HPN342C 1920x1080 600x340mm 27.2-inch              | 1        | 1.56%   |
| Goldstar LG IPS QHD GSM5BC4 2560x1440 530x300mm 24.0-inch              | 1        | 1.56%   |
| Goldstar E2242 GSM58BE 1920x1080 480x270mm 21.7-inch                   | 1        | 1.56%   |
| Goldstar 22EA53 GSM59A6 1920x1080 480x270mm 21.7-inch                  | 1        | 1.56%   |
| Goldstar 20EN43 GSM4EE3 1600x900 450x250mm 20.3-inch                   | 1        | 1.56%   |
| Eizo FS2331 ENC2211 1920x1080 510x290mm 23.1-inch                      | 1        | 1.56%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                      | 1        | 1.56%   |
| Dell P2414H DELA09B 1920x1080 530x300mm 24.0-inch                      | 1        | 1.56%   |
| Dell LCD Monitor U2419HC 1920x1080                                     | 1        | 1.56%   |
| Dell LCD Monitor S2721D 2560x1440                                      | 1        | 1.56%   |
| Dell E2220H DELF119 1920x1080 480x270mm 21.7-inch                      | 1        | 1.56%   |
| BenQ LCD Monitor GW2780 1920x1080                                      | 1        | 1.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 34       | 53.13%  |
| 1366x768 (WXGA)    | 7        | 10.94%  |
| 2560x1440 (QHD)    | 6        | 9.38%   |
| 3840x2160 (4K)     | 3        | 4.69%   |
| 1280x1024 (SXGA)   | 3        | 4.69%   |
| 1680x1050 (WSXGA+) | 2        | 3.13%   |
| 1600x900 (HD+)     | 2        | 3.13%   |
| Unknown            | 2        | 3.13%   |
| 5760x2160          | 1        | 1.56%   |
| 3840x1080          | 1        | 1.56%   |
| 1920x1200 (WUXGA)  | 1        | 1.56%   |
| 1440x900 (WXGA+)   | 1        | 1.56%   |
| 1024x768 (XGA)     | 1        | 1.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 27.87%  |
| 21      | 10       | 16.39%  |
| 27      | 8        | 13.11%  |
| 24      | 8        | 13.11%  |
| 23      | 4        | 6.56%   |
| 18      | 4        | 6.56%   |
| 31      | 3        | 4.92%   |
| 19      | 3        | 4.92%   |
| 20      | 2        | 3.28%   |
| 22      | 1        | 1.64%   |
| 14      | 1        | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 32.79%  |
| 401-500     | 19       | 31.15%  |
| Unknown     | 17       | 27.87%  |
| 601-700     | 3        | 4.92%   |
| 351-400     | 1        | 1.64%   |
| 201-300     | 1        | 1.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 39       | 63.93%  |
| Unknown | 17       | 27.87%  |
| 16/10   | 3        | 4.92%   |
| 5/4     | 1        | 1.64%   |
| 4/3     | 1        | 1.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 23       | 37.7%   |
| Unknown        | 17       | 27.87%  |
| 301-350        | 8        | 13.11%  |
| 151-200        | 5        | 8.2%    |
| 141-150        | 4        | 6.56%   |
| 351-500        | 3        | 4.92%   |
| 101-110        | 1        | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 28       | 45.9%   |
| Unknown | 17       | 27.87%  |
| 101-120 | 12       | 19.67%  |
| 121-160 | 3        | 4.92%   |
| 1-50    | 1        | 1.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 130      | 80.25%  |
| 0     | 28       | 17.28%  |
| 2     | 4        | 2.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 96       | 46.6%   |
| Intel                    | 67       | 32.52%  |
| Qualcomm Atheros         | 14       | 6.8%    |
| Ralink Technology        | 4        | 1.94%   |
| Ralink                   | 4        | 1.94%   |
| Broadcom                 | 4        | 1.94%   |
| TP-Link                  | 3        | 1.46%   |
| Samsung Electronics      | 3        | 1.46%   |
| Marvell Technology Group | 2        | 0.97%   |
| Huawei Technologies      | 2        | 0.97%   |
| D-Link                   | 2        | 0.97%   |
| National Semiconductor   | 1        | 0.49%   |
| MediaTek                 | 1        | 0.49%   |
| Edimax Technology        | 1        | 0.49%   |
| Atheros                  | 1        | 0.49%   |
| Accton Technology        | 1        | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82       | 36.12%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 4.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 3.52%   |
| Intel Ethernet Controller I225-V                                  | 7        | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6        | 2.64%   |
| Intel Ethernet Connection I217-V                                  | 5        | 2.2%    |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 1.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.32%   |
| Intel Wireless 3165                                               | 3        | 1.32%   |
| Intel I211 Gigabit Network Connection                             | 3        | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.32%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.32%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.32%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.88%   |
| Ralink RT2500 Wireless 802.11bg                                   | 2        | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.88%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 0.88%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.88%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 0.88%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.88%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 2        | 0.88%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.88%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 16       | 27.12%  |
| Realtek Semiconductor | 15       | 25.42%  |
| Qualcomm Atheros      | 7        | 11.86%  |
| Ralink Technology     | 4        | 6.78%   |
| Ralink                | 4        | 6.78%   |
| Broadcom              | 4        | 6.78%   |
| TP-Link               | 3        | 5.08%   |
| D-Link                | 2        | 3.39%   |
| MediaTek              | 1        | 1.69%   |
| Edimax Technology     | 1        | 1.69%   |
| Atheros               | 1        | 1.69%   |
| Accton Technology     | 1        | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 6        | 10%     |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3        | 5%      |
| Intel Wireless 3165                                                  | 3        | 5%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 3.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 2        | 3.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2        | 3.33%   |
| Ralink RT2500 Wireless 802.11bg                                      | 2        | 3.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 3.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 2        | 3.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2        | 3.33%   |
| Intel Wi-Fi 6 AX200                                                  | 2        | 3.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2        | 3.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2        | 3.33%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2        | 3.33%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                  | 1        | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1        | 1.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1        | 1.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1        | 1.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 1.67%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                         | 1        | 1.67%   |
| Ralink RT3072 Wireless Adapter                                       | 1        | 1.67%   |
| Ralink MT7601U Wireless Adapter                                      | 1        | 1.67%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1        | 1.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1        | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 1.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 1        | 1.67%   |
| Intel Wireless 8265 / 8275                                           | 1        | 1.67%   |
| Intel Wireless 8260                                                  | 1        | 1.67%   |
| Intel Wireless 7265                                                  | 1        | 1.67%   |
| Intel Wireless 7260                                                  | 1        | 1.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 1        | 1.67%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]             | 1        | 1.67%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU] | 1        | 1.67%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.D1) [Realtek RTL8188ETV]   | 1        | 1.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 1        | 1.67%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1        | 1.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 1        | 1.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 1        | 1.67%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1        | 1.67%   |
| Accton Arcadyan 802.11N Wireless Adapter                             | 1        | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 89       | 54.27%  |
| Intel                    | 59       | 35.98%  |
| Qualcomm Atheros         | 7        | 4.27%   |
| Samsung Electronics      | 3        | 1.83%   |
| Marvell Technology Group | 2        | 1.22%   |
| Huawei Technologies      | 2        | 1.22%   |
| National Semiconductor   | 1        | 0.61%   |
| Broadcom                 | 1        | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82       | 49.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 5.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 4.79%   |
| Intel Ethernet Controller I225-V                                  | 7        | 4.19%   |
| Intel Ethernet Connection I217-V                                  | 5        | 2.99%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 2.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.8%    |
| Intel I211 Gigabit Network Connection                             | 3        | 1.8%    |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.8%    |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.8%    |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.8%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 1.2%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 1.2%    |
| Intel I210 Gigabit Network Connection                             | 2        | 1.2%    |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.2%    |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.2%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.2%    |
| Intel 82567LF-3 Gigabit Network Connection                        | 2        | 1.2%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.2%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.6%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.6%    |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1        | 0.6%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.6%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.6%    |
| Intel Ethernet Connection (5) I219-V                              | 1        | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.6%    |
| Intel Ethernet Connection (2) I219-V                              | 1        | 0.6%    |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.6%    |
| Huawei USB Device                                                 | 1        | 0.6%    |
| Huawei Android ADB Interface                                      | 1        | 0.6%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1        | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 156      | 74.29%  |
| WiFi     | 54       | 25.71%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 139      | 95.21%  |
| WiFi     | 7        | 4.79%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 110      | 67.9%   |
| 2     | 44       | 27.16%  |
| 3     | 4        | 2.47%   |
| 0     | 4        | 2.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 154      | 93.9%   |
| Yes  | 10       | 6.1%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 31.91%  |
| Realtek Semiconductor           | 9        | 19.15%  |
| Cambridge Silicon Radio         | 9        | 19.15%  |
| ASUSTek Computer                | 3        | 6.38%   |
| TP-Link                         | 2        | 4.26%   |
| IMC Networks                    | 2        | 4.26%   |
| Broadcom                        | 2        | 4.26%   |
| Apple                           | 2        | 4.26%   |
| Qualcomm Atheros Communications | 1        | 2.13%   |
| Primax Electronics              | 1        | 2.13%   |
| Fujitsu                         | 1        | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 9        | 19.15%  |
| Realtek Bluetooth Adapter                                   | 7        | 14.89%  |
| Intel Bluetooth wireless interface                          | 7        | 14.89%  |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2        | 4.26%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2        | 4.26%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2        | 4.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2        | 4.26%   |
| Intel AX201 Bluetooth                                       | 2        | 4.26%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2        | 4.26%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 2.13%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1        | 2.13%   |
| Intel AX210 Bluetooth                                       | 1        | 2.13%   |
| Intel AX200 Bluetooth                                       | 1        | 2.13%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS     | 1        | 2.13%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1        | 2.13%   |
| Fujitsu Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter  | 1        | 2.13%   |
| ASUS USB-BT500                                              | 1        | 2.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 2.13%   |
| ASUS Bluetooth Controller                                   | 1        | 2.13%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 2.13%   |
| Apple Bluetooth Host Controller                             | 1        | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 111      | 43.87%  |
| AMD                      | 60       | 23.72%  |
| Nvidia                   | 47       | 18.58%  |
| C-Media Electronics      | 14       | 5.53%   |
| Texas Instruments        | 4        | 1.58%   |
| Realtek Semiconductor    | 2        | 0.79%   |
| Creative Labs            | 2        | 0.79%   |
| Unknown                  | 2        | 0.79%   |
| Yamaha                   | 1        | 0.4%    |
| Razer USA                | 1        | 0.4%    |
| OPPO Electronics         | 1        | 0.4%    |
| KTMicro                  | 1        | 0.4%    |
| JMTek                    | 1        | 0.4%    |
| Hewlett-Packard          | 1        | 0.4%    |
| HECATE G2 GAMING HEADSET | 1        | 0.4%    |
| Harman                   | 1        | 0.4%    |
| Generalplus Technology   | 1        | 0.4%    |
| GEMBIRD                  | 1        | 0.4%    |
| Edifier Technology       | 1        | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18       | 6.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15       | 5.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14       | 4.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13       | 4.39%   |
| Intel 200 Series PCH HD Audio                                              | 13       | 4.39%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 4.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10       | 3.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 3.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 2.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 8        | 2.7%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 7        | 2.36%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7        | 2.36%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 2.36%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 2.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 2.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6        | 2.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.69%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.35%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 1.35%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 1.35%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.01%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.01%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 1.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 1.01%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 1.01%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 1.01%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.01%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 1.01%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 3        | 1.01%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 1.01%   |
| AMD FCH Azalia Controller                                                  | 3        | 1.01%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.68%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 0.68%   |
| Intel Jasper Lake HD Audio                                                 | 2        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 35       | 17.95%  |
| Samsung Electronics | 25       | 12.82%  |
| Unknown             | 20       | 10.26%  |
| Corsair             | 19       | 9.74%   |
| Crucial             | 14       | 7.18%   |
| SK hynix            | 13       | 6.67%   |
| Micron Technology   | 12       | 6.15%   |
| G.Skill             | 9        | 4.62%   |
| Unknown             | 9        | 4.62%   |
| Nanya Technology    | 5        | 2.56%   |
| Patriot             | 4        | 2.05%   |
| A-DATA Technology   | 4        | 2.05%   |
| Ramaxel Technology  | 3        | 1.54%   |
| Apacer              | 3        | 1.54%   |
| Unknown (ABCD)      | 2        | 1.03%   |
| Kingmax             | 2        | 1.03%   |
| GOODRAM             | 2        | 1.03%   |
| Atermiter           | 2        | 1.03%   |
| Unknown (8A02)      | 1        | 0.51%   |
| Transcend           | 1        | 0.51%   |
| Team                | 1        | 0.51%   |
| Smart               | 1        | 0.51%   |
| Qumo                | 1        | 0.51%   |
| MemoWise            | 1        | 0.51%   |
| Lexar               | 1        | 0.51%   |
| Juhor               | 1        | 0.51%   |
| Golden Empire       | 1        | 0.51%   |
| Elpida              | 1        | 0.51%   |
| Avant               | 1        | 0.51%   |
| AMD                 | 1        | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 9        | 4.31%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                   | 3        | 1.44%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 2        | 0.96%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                | 2        | 0.96%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                     | 2        | 0.96%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 2        | 0.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s          | 2        | 0.96%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                             | 2        | 0.96%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                     | 2        | 0.96%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s                     | 2        | 0.96%   |
| Samsung RAM M3 78T2863DZS-CE6 1GB DIMM DDR2 667MT/s                     | 2        | 0.96%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                     | 2        | 0.96%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                       | 2        | 0.96%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                     | 2        | 0.96%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                     | 2        | 0.96%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                     | 2        | 0.96%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 2        | 0.96%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s                    | 2        | 0.96%   |
| Corsair RAM CMK32GX4M2A2400C16 16GB DIMM DDR4 2400MT/s                  | 2        | 0.96%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 0.48%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                    | 1        | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1        | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 1        | 0.48%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                    | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                               | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                               | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                                 | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                     | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                                    | 1        | 0.48%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                                | 1        | 0.48%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                | 1        | 0.48%   |
| Unknown RAM Module 1GB DIMM DDR2                                        | 1        | 0.48%   |
| Unknown RAM Module 1GB DIMM DDR 667MT/s                                 | 1        | 0.48%   |
| Unknown RAM Module 1GB DIMM 400MT/s                                     | 1        | 0.48%   |
| Unknown (8A02) RAM Module 8GB DIMM DDR3 1600MT/s                        | 1        | 0.48%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s                       | 1        | 0.48%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                              | 1        | 0.48%   |
| Smart RAM SH564128FH8N0QNSCG 4GB DIMM DDR3 1600MT/s                     | 1        | 0.48%   |
| SK hynix RAM Module 2GB DIMM DDR2 1639MT/s                              | 1        | 0.48%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                           | 1        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 75       | 46.58%  |
| DDR3    | 56       | 34.78%  |
| DDR2    | 12       | 7.45%   |
| Unknown | 12       | 7.45%   |
| SDRAM   | 2        | 1.24%   |
| LPDDR4  | 2        | 1.24%   |
| DDR     | 2        | 1.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 138      | 86.25%  |
| SODIMM | 22       | 13.75%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 73       | 39.89%  |
| 4096  | 47       | 25.68%  |
| 2048  | 31       | 16.94%  |
| 16384 | 20       | 10.93%  |
| 1024  | 11       | 6.01%   |
| 32768 | 1        | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 32       | 18.6%   |
| 1333    | 29       | 16.86%  |
| 2133    | 18       | 10.47%  |
| 3200    | 17       | 9.88%   |
| 2400    | 16       | 9.3%    |
| 2667    | 15       | 8.72%   |
| 800     | 9        | 5.23%   |
| 3600    | 6        | 3.49%   |
| 1067    | 5        | 2.91%   |
| 667     | 5        | 2.91%   |
| 1066    | 4        | 2.33%   |
| 2666    | 3        | 1.74%   |
| Unknown | 3        | 1.74%   |
| 3000    | 2        | 1.16%   |
| 400     | 2        | 1.16%   |
| 4400    | 1        | 0.58%   |
| 3333    | 1        | 0.58%   |
| 1867    | 1        | 0.58%   |
| 1639    | 1        | 0.58%   |
| 1200    | 1        | 0.58%   |
| 533     | 1        | 0.58%   |

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
| Microdia                      | 3        | 23.08%  |
| Logitech                      | 3        | 23.08%  |
| Trust                         | 1        | 7.69%   |
| Sunplus Innovation Technology | 1        | 7.69%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 7.69%   |
| Importek                      | 1        | 7.69%   |
| IMC Networks                  | 1        | 7.69%   |
| Genesys Logic                 | 1        | 7.69%   |
| GEMBIRD                       | 1        | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Microdia REDRAGON Live Camera Audio               | 2        | 15.38%  |
| Logitech Webcam C270                              | 2        | 15.38%  |
| Trust Trust Full HD Webcam                        | 1        | 7.69%   |
| Sunplus SPCA2650 AV Camera                        | 1        | 7.69%   |
| SHENZHEN AONI ELECTRONIC NexiGo N990 4K Camera    | 1        | 7.69%   |
| Microdia Webcam Vitade AF                         | 1        | 7.69%   |
| Logitech HD Pro Webcam C920                       | 1        | 7.69%   |
| Importek FJ Camera                                | 1        | 7.69%   |
| IMC Networks XHC Camera                           | 1        | 7.69%   |
| Genesys Logic Digital Microscope                  | 1        | 7.69%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 7.69%   |

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
| 1     | 76       | 46.91%  |
| 0     | 53       | 32.72%  |
| 2     | 29       | 17.9%   |
| 3     | 3        | 1.85%   |
| 4     | 1        | 0.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 97       | 71.85%  |
| Net/wireless             | 18       | 13.33%  |
| Sound                    | 12       | 8.89%   |
| Bluetooth                | 4        | 2.96%   |
| Card reader              | 2        | 1.48%   |
| Network                  | 1        | 0.74%   |
| Dvb card                 | 1        | 0.74%   |

