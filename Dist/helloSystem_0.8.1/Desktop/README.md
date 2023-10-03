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

Total: 201

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkCentre M81 5049D7G     | [60de9490a9](https://bsd-hardware.info/?probe=60de9490a9) | Sep 29, 2023 |
| ASUSTek       | Z170-A                      | [3802fe676c](https://bsd-hardware.info/?probe=3802fe676c) | Sep 23, 2023 |
| HP            | 18E8                        | [7a96c7f43a](https://bsd-hardware.info/?probe=7a96c7f43a) | Sep 21, 2023 |
| HP            | 83F3                        | [4d1df66f57](https://bsd-hardware.info/?probe=4d1df66f57) | Sep 20, 2023 |
| Dell          | 0VRWRC A01                  | [6c85a42e64](https://bsd-hardware.info/?probe=6c85a42e64) | Sep 19, 2023 |
| ASRock        | B450 Pro4                   | [211b0f3e9c](https://bsd-hardware.info/?probe=211b0f3e9c) | Sep 19, 2023 |
| AZW           | U59                         | [ae0d8568d1](https://bsd-hardware.info/?probe=ae0d8568d1) | Sep 15, 2023 |
| AZW           | U59                         | [7e094459f9](https://bsd-hardware.info/?probe=7e094459f9) | Sep 14, 2023 |
| Dell          | 04YP6J A02                  | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| Lenovo        | 3140 NOK                    | [945ad170d7](https://bsd-hardware.info/?probe=945ad170d7) | Sep 10, 2023 |
| Lenovo        | 3140 NOK                    | [3f9dcefb8e](https://bsd-hardware.info/?probe=3f9dcefb8e) | Sep 10, 2023 |
| MSI           | X570-A PRO                  | [e3d8f34f08](https://bsd-hardware.info/?probe=e3d8f34f08) | Sep 08, 2023 |
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
| amd64 | 169      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 168      | 99.41%  |
| GNOME        | 1        | 0.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 169      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 169      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 66       | 38.6%   |
| fr_FR   | 49       | 28.65%  |
| ru_RU   | 14       | 8.19%   |
| es_ES   | 10       | 5.85%   |
| de_DE   | 10       | 5.85%   |
| pt_BR   | 6        | 3.51%   |
| it_IT   | 5        | 2.92%   |
| Unknown | 5        | 2.92%   |
| pl_PL   | 2        | 1.17%   |
| jp_JP   | 2        | 1.17%   |
| fr      | 1        | 0.58%   |
| es      | 1        | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 166      | 98.22%  |
| BIOS | 3        | 1.78%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 98       | 56.32%  |
| Zfs    | 76       | 43.68%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 166      | 98.22%  |
| MBR  | 3        | 1.78%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 39       | 23.08%  |
| Gigabyte Technology | 25       | 14.79%  |
| Hewlett-Packard     | 19       | 11.24%  |
| Dell                | 17       | 10.06%  |
| MSI                 | 13       | 7.69%   |
| Lenovo              | 10       | 5.92%   |
| ASRock              | 9        | 5.33%   |
| Intel               | 7        | 4.14%   |
| Unknown             | 5        | 2.96%   |
| Acer                | 4        | 2.37%   |
| Fujitsu             | 3        | 1.78%   |
| T-bao               | 2        | 1.18%   |
| Fujitsu Siemens     | 2        | 1.18%   |
| Foxconn             | 2        | 1.18%   |
| AZW                 | 2        | 1.18%   |
| Pegatron            | 1        | 0.59%   |
| LG Electronics      | 1        | 0.59%   |
| Huanan              | 1        | 0.59%   |
| Google              | 1        | 0.59%   |
| ECS                 | 1        | 0.59%   |
| Daten Tecnologia    | 1        | 0.59%   |
| Biostar             | 1        | 0.59%   |
| BESSTAR Tech        | 1        | 0.59%   |
| Axiomtek            | 1        | 0.59%   |
| Apple               | 1        | 0.59%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 5        | 2.96%   |
| T-bao MINI PC                          | 2        | 1.18%   |
| MSI MS-7788                            | 2        | 1.18%   |
| Intel H81                              | 2        | 1.18%   |
| HP EliteDesk 800 G2 DM 35W             | 2        | 1.18%   |
| HP Compaq Elite 8300 USDT              | 2        | 1.18%   |
| Dell OptiPlex 7010                     | 2        | 1.18%   |
| Dell OptiPlex 3020                     | 2        | 1.18%   |
| ASUS ROG STRIX B550-F GAMING           | 2        | 1.18%   |
| ASUS PRIME B250M-A                     | 2        | 1.18%   |
| ASUS All Series                        | 2        | 1.18%   |
| Pegatron Compaq dx2450 Microtower      | 1        | 0.59%   |
| MSI MS-7C95                            | 1        | 0.59%   |
| MSI MS-7C83                            | 1        | 0.59%   |
| MSI MS-7C51                            | 1        | 0.59%   |
| MSI MS-7C37                            | 1        | 0.59%   |
| MSI MS-7C09                            | 1        | 0.59%   |
| MSI MS-7B98                            | 1        | 0.59%   |
| MSI MS-7B86                            | 1        | 0.59%   |
| MSI MS-7B17                            | 1        | 0.59%   |
| MSI MS-7996                            | 1        | 0.59%   |
| MSI MS-7599                            | 1        | 0.59%   |
| MSI Compaq dx2200 MT                   | 1        | 0.59%   |
| LG R590-K.AAA9BT                       | 1        | 0.59%   |
| Lenovo ThinkCentre M900 10FLS15P00     | 1        | 0.59%   |
| Lenovo ThinkCentre M900 10FGS05C08     | 1        | 0.59%   |
| Lenovo ThinkCentre M81 5049D7G         | 1        | 0.59%   |
| Lenovo ThinkCentre M75e 5065A11        | 1        | 0.59%   |
| Lenovo ThinkCentre M73 10AYA06EIA      | 1        | 0.59%   |
| Lenovo ThinkCentre M73 10AXS34800      | 1        | 0.59%   |
| Lenovo ThinkCentre M710s 10M8S0FW00    | 1        | 0.59%   |
| Lenovo ThinkCentre M58p 6138DK1        | 1        | 0.59%   |
| Lenovo ThinkCentre Edge72 34971B1      | 1        | 0.59%   |
| Lenovo IdeaCentre 510S-07ICB Type 90K8 | 1        | 0.59%   |
| Intel X99                              | 1        | 0.59%   |
| Intel Jasper Lake Client Platform      | 1        | 0.59%   |
| Intel DH87RL AAG74240-400              | 1        | 0.59%   |
| Intel DG41TY AAE47335-300              | 1        | 0.59%   |
| Intel DB85FL AAG89861-203              | 1        | 0.59%   |
| Huanan X99-TF GAMING V3.0              | 1        | 0.59%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 12       | 7.1%    |
| Dell OptiPlex           | 10       | 5.92%   |
| Lenovo ThinkCentre      | 9        | 5.33%   |
| ASUS ROG                | 8        | 4.73%   |
| HP EliteDesk            | 5        | 2.96%   |
| HP Compaq               | 5        | 2.96%   |
| Unknown                 | 5        | 2.96%   |
| HP ProDesk              | 3        | 1.78%   |
| Dell Precision          | 3        | 1.78%   |
| T-bao MINI              | 2        | 1.18%   |
| MSI MS-7788             | 2        | 1.18%   |
| Intel H81               | 2        | 1.18%   |
| Gigabyte B450M          | 2        | 1.18%   |
| Fujitsu Siemens ESPRIMO | 2        | 1.18%   |
| Fujitsu ESPRIMO         | 2        | 1.18%   |
| Dell Vostro             | 2        | 1.18%   |
| Dell Inspiron           | 2        | 1.18%   |
| ASUS TUF                | 2        | 1.18%   |
| ASUS All                | 2        | 1.18%   |
| Acer Veriton            | 2        | 1.18%   |
| Pegatron Compaq         | 1        | 0.59%   |
| MSI MS-7C95             | 1        | 0.59%   |
| MSI MS-7C83             | 1        | 0.59%   |
| MSI MS-7C51             | 1        | 0.59%   |
| MSI MS-7C37             | 1        | 0.59%   |
| MSI MS-7C09             | 1        | 0.59%   |
| MSI MS-7B98             | 1        | 0.59%   |
| MSI MS-7B86             | 1        | 0.59%   |
| MSI MS-7B17             | 1        | 0.59%   |
| MSI MS-7996             | 1        | 0.59%   |
| MSI MS-7599             | 1        | 0.59%   |
| MSI Compaq              | 1        | 0.59%   |
| LG R590-K.AAA9BT        | 1        | 0.59%   |
| Lenovo IdeaCentre       | 1        | 0.59%   |
| Intel X99               | 1        | 0.59%   |
| Intel Jasper            | 1        | 0.59%   |
| Intel DH87RL            | 1        | 0.59%   |
| Intel DG41TY            | 1        | 0.59%   |
| Intel DB85FL            | 1        | 0.59%   |
| Huanan X99-TF           | 1        | 0.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 18       | 10.65%  |
| 2022    | 17       | 10.06%  |
| 2020    | 17       | 10.06%  |
| 2013    | 15       | 8.88%   |
| 2019    | 14       | 8.28%   |
| 2012    | 14       | 8.28%   |
| 2010    | 11       | 6.51%   |
| 2018    | 9        | 5.33%   |
| 2016    | 9        | 5.33%   |
| 2014    | 9        | 5.33%   |
| 2011    | 8        | 4.73%   |
| 2017    | 7        | 4.14%   |
| 2023    | 4        | 2.37%   |
| 2015    | 4        | 2.37%   |
| 2009    | 4        | 2.37%   |
| 2008    | 4        | 2.37%   |
| 2007    | 2        | 1.18%   |
| 2006    | 2        | 1.18%   |
| Unknown | 1        | 0.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 169      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 168      | 99.41%  |
| Yes  | 1        | 0.59%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 60       | 35.5%   |
| 16.01-24.0  | 49       | 28.99%  |
| 4.01-8.0    | 29       | 17.16%  |
| 32.01-64.0  | 18       | 10.65%  |
| 2.01-3.0    | 4        | 2.37%   |
| 64.01-256.0 | 4        | 2.37%   |
| 24.01-32.0  | 3        | 1.78%   |
| 3.01-4.0    | 1        | 0.59%   |
| 0.51-1.0    | 1        | 0.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 76       | 44.44%  |
| 0.51-1.0 | 63       | 36.84%  |
| 1.01-2.0 | 21       | 12.28%  |
| 2.01-3.0 | 9        | 5.26%   |
| 3.01-4.0 | 2        | 1.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 79       | 46.75%  |
| 2      | 38       | 22.49%  |
| 3      | 23       | 13.61%  |
| 0      | 11       | 6.51%   |
| 5      | 8        | 4.73%   |
| 4      | 4        | 2.37%   |
| 9      | 2        | 1.18%   |
| 6      | 2        | 1.18%   |
| 13     | 1        | 0.59%   |
| 7      | 1        | 0.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 106      | 62.72%  |
| Yes       | 63       | 37.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 164      | 97.04%  |
| No        | 5        | 2.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 113      | 66.47%  |
| Yes       | 57       | 33.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 124      | 73.37%  |
| Yes       | 45       | 26.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| Russia             | 24       | 14.2%   |
| USA                | 22       | 13.02%  |
| Germany            | 11       | 6.51%   |
| Spain              | 10       | 5.92%   |
| Brazil             | 9        | 5.33%   |
| Italy              | 7        | 4.14%   |
| Canada             | 7        | 4.14%   |
| Serbia             | 6        | 3.55%   |
| Hungary            | 6        | 3.55%   |
| Romania            | 5        | 2.96%   |
| Poland             | 5        | 2.96%   |
| France             | 5        | 2.96%   |
| Australia          | 5        | 2.96%   |
| Belgium            | 4        | 2.37%   |
| UK                 | 3        | 1.78%   |
| Turkey             | 3        | 1.78%   |
| Peru               | 3        | 1.78%   |
| Mexico             | 3        | 1.78%   |
| Japan              | 3        | 1.78%   |
| Ukraine            | 2        | 1.18%   |
| Sweden             | 2        | 1.18%   |
| Indonesia          | 2        | 1.18%   |
| India              | 2        | 1.18%   |
| China              | 2        | 1.18%   |
| Bulgaria           | 2        | 1.18%   |
| Argentina          | 2        | 1.18%   |
| Switzerland        | 1        | 0.59%   |
| South Korea        | 1        | 0.59%   |
| Slovenia           | 1        | 0.59%   |
| San Marino         | 1        | 0.59%   |
| Netherlands        | 1        | 0.59%   |
| Kyrgyzstan         | 1        | 0.59%   |
| Kazakhstan         | 1        | 0.59%   |
| Israel             | 1        | 0.59%   |
| Dominican Republic | 1        | 0.59%   |
| Croatia            | 1        | 0.59%   |
| Chile              | 1        | 0.59%   |
| Belarus            | 1        | 0.59%   |
| Austria            | 1        | 0.59%   |
| Algeria            | 1        | 0.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| St. Jean Baptiste | 3        | 1.74%   |
| Moscow            | 3        | 1.74%   |
| Belgrade          | 3        | 1.74%   |
| Sydney            | 2        | 1.16%   |
| St Petersburg     | 2        | 1.16%   |
| Penza             | 2        | 1.16%   |
| Paris             | 2        | 1.16%   |
| New York          | 2        | 1.16%   |
| Melbourne         | 2        | 1.16%   |
| Madrid            | 2        | 1.16%   |
| Kirov             | 2        | 1.16%   |
| Curitiba          | 2        | 1.16%   |
| Brooklyn          | 2        | 1.16%   |
| Berlin            | 2        | 1.16%   |
| Bandung           | 2        | 1.16%   |
| Zurich            | 1        | 0.58%   |
| Zhengzhou         | 1        | 0.58%   |
| Yokohama          | 1        | 0.58%   |
| Woodbridge        | 1        | 0.58%   |
| Winnipeg          | 1        | 0.58%   |
| Warsaw            | 1        | 0.58%   |
| Volgodonsk        | 1        | 0.58%   |
| Vogogna           | 1        | 0.58%   |
| Vladimir          | 1        | 0.58%   |
| Virovitica        | 1        | 0.58%   |
| Villena           | 1        | 0.58%   |
| Vienna            | 1        | 0.58%   |
| Venice            | 1        | 0.58%   |
| Vecses            | 1        | 0.58%   |
| Valderrobres      | 1        | 0.58%   |
| Ubstadt-Weiher    | 1        | 0.58%   |
| Tucson            | 1        | 0.58%   |
| Trumbull          | 1        | 0.58%   |
| Trieste           | 1        | 0.58%   |
| Trekhgornyy       | 1        | 0.58%   |
| Topolovgrad       | 1        | 0.58%   |
| Tolmin            | 1        | 0.58%   |
| Tokmok            | 1        | 0.58%   |
| Timișoara        | 1        | 0.58%   |
| Temple            | 1        | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 48       | 80     | 17.78%  |
| Seagate             | 38       | 61     | 14.07%  |
| Samsung Electronics | 37       | 54     | 13.7%   |
| Kingston            | 29       | 29     | 10.74%  |
| Toshiba             | 15       | 20     | 5.56%   |
| SanDisk             | 10       | 10     | 3.7%    |
| Crucial             | 10       | 12     | 3.7%    |
| China               | 7        | 8      | 2.59%   |
| A-DATA Technology   | 7        | 8      | 2.59%   |
| Hitachi             | 6        | 7      | 2.22%   |
| Transcend           | 4        | 4      | 1.48%   |
| Patriot             | 4        | 4      | 1.48%   |
| Micron Technology   | 4        | 5      | 1.48%   |
| Maxtor              | 4        | 4      | 1.48%   |
| KingSpec            | 4        | 4      | 1.48%   |
| SPCC                | 3        | 3      | 1.11%   |
| Intel               | 3        | 3      | 1.11%   |
| Team                | 2        | 2      | 0.74%   |
| PNY                 | 2        | 2      | 0.74%   |
| Gigabyte Technology | 2        | 3      | 0.74%   |
| Apacer              | 2        | 2      | 0.74%   |
| WALRAM              | 1        | 1      | 0.37%   |
| Vaseky              | 1        | 1      | 0.37%   |
| TAMMUZ              | 1        | 1      | 0.37%   |
| SUNEAST             | 1        | 1      | 0.37%   |
| SK hynix            | 1        | 1      | 0.37%   |
| Silicon Motion      | 1        | 1      | 0.37%   |
| SETHRISE            | 1        | 1      | 0.37%   |
| RX7                 | 1        | 1      | 0.37%   |
| QUANTUM             | 1        | 1      | 0.37%   |
| Pioneer             | 1        | 1      | 0.37%   |
| Philips             | 1        | 1      | 0.37%   |
| Palit               | 1        | 1      | 0.37%   |
| OCZ                 | 1        | 1      | 0.37%   |
| Netac               | 1        | 1      | 0.37%   |
| LITEONIT            | 1        | 1      | 0.37%   |
| Kston               | 1        | 1      | 0.37%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.37%   |
| KIOXIA              | 1        | 1      | 0.37%   |
| Intenso             | 1        | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 7        | 2.18%   |
| Seagate ST500DM002-1BD142 500GB | 6        | 1.87%   |
| Seagate ST3500418AS 500GB       | 4        | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB  | 4        | 1.25%   |
| Samsung SSD 870 EVO 500GB       | 4        | 1.25%   |
| Samsung SSD 860 EVO 500GB       | 4        | 1.25%   |
| Samsung SSD 850 EVO 250GB       | 4        | 1.25%   |
| WDC WD20EFRX-68EUZN0 2TB        | 3        | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB        | 3        | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 0.93%   |
| Samsung SSD 980 1TB             | 3        | 0.93%   |
| Samsung SSD 970 EVO Plus 500GB  | 3        | 0.93%   |
| Kingston SA400S37120G 120GB     | 3        | 0.93%   |
| Crucial CT500MX500SSD1 500GB    | 3        | 0.93%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 0.93%   |
| WDC WDS240G2G0A-00JH30 240GB    | 2        | 0.62%   |
| WDC WDS120G2G0A-00JH30 120GB    | 2        | 0.62%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 2        | 0.62%   |
| WDC WD20EZRX-00D8PB0 2TB        | 2        | 0.62%   |
| WDC WD10EZEX-60WN4A1 1TB        | 2        | 0.62%   |
| WDC WD10EZEX-60WN4A0 1TB        | 2        | 0.62%   |
| Toshiba HDWD110 1TB             | 2        | 0.62%   |
| Toshiba DT01ACA100 1TB          | 2        | 0.62%   |
| Toshiba DT01ACA050 500GB        | 2        | 0.62%   |
| SPCC Solid State Disk 128GB     | 2        | 0.62%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 0.62%   |
| SanDisk pSSD 256GB              | 2        | 0.62%   |
| Samsung SSD 980 PRO 500GB       | 2        | 0.62%   |
| Samsung SSD 970 PRO 512GB       | 2        | 0.62%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 0.62%   |
| Patriot Burst Elite 120GB       | 2        | 0.62%   |
| Kingston SHFS37A240G 240GB      | 2        | 0.62%   |
| Kingston SA400S37480G 480GB     | 2        | 0.62%   |
| WDC WDS500G2B0A-00SM50 500GB    | 1        | 0.31%   |
| WDC WDS500G1B0A-00H9H0 500GB    | 1        | 0.31%   |
| WDC WDS250G1B0A-00H9H0 250GB    | 1        | 0.31%   |
| WDC WD800JD-75MSA3 80GB         | 1        | 0.31%   |
| WDC WD800AAJS-00PSA0 80GB       | 1        | 0.31%   |
| WDC WD7501AALS-00J7B0 752GB     | 1        | 0.31%   |
| WDC WD6400BPVT-22HXZT3 640GB    | 1        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 41       | 70     | 38.32%  |
| Seagate             | 38       | 61     | 35.51%  |
| Toshiba             | 12       | 15     | 11.21%  |
| Hitachi             | 6        | 7      | 5.61%   |
| Maxtor              | 4        | 4      | 3.74%   |
| Samsung Electronics | 3        | 4      | 2.8%    |
| QUANTUM             | 1        | 1      | 0.93%   |
| HGST                | 1        | 1      | 0.93%   |
| Apple               | 1        | 1      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 20       | 27     | 16.67%  |
| Kingston            | 20       | 20     | 16.67%  |
| SanDisk             | 10       | 10     | 8.33%   |
| Crucial             | 9        | 10     | 7.5%    |
| WDC                 | 7        | 7      | 5.83%   |
| China               | 7        | 8      | 5.83%   |
| Patriot             | 4        | 4      | 3.33%   |
| KingSpec            | 4        | 4      | 3.33%   |
| A-DATA Technology   | 4        | 4      | 3.33%   |
| Transcend           | 3        | 3      | 2.5%    |
| Toshiba             | 3        | 5      | 2.5%    |
| SPCC                | 2        | 2      | 1.67%   |
| PNY                 | 2        | 2      | 1.67%   |
| Apacer              | 2        | 2      | 1.67%   |
| WALRAM              | 1        | 1      | 0.83%   |
| Vaseky              | 1        | 1      | 0.83%   |
| Team                | 1        | 1      | 0.83%   |
| TAMMUZ              | 1        | 1      | 0.83%   |
| SUNEAST             | 1        | 1      | 0.83%   |
| SETHRISE            | 1        | 1      | 0.83%   |
| RX7                 | 1        | 1      | 0.83%   |
| Pioneer             | 1        | 1      | 0.83%   |
| Philips             | 1        | 1      | 0.83%   |
| Palit               | 1        | 1      | 0.83%   |
| OCZ                 | 1        | 1      | 0.83%   |
| Micron Technology   | 1        | 1      | 0.83%   |
| LITEONIT            | 1        | 1      | 0.83%   |
| Kston               | 1        | 1      | 0.83%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.83%   |
| Intenso             | 1        | 1      | 0.83%   |
| Intel               | 1        | 1      | 0.83%   |
| HEORIADY            | 1        | 1      | 0.83%   |
| GOODRAM             | 1        | 1      | 0.83%   |
| Gigabyte Technology | 1        | 2      | 0.83%   |
| EDGE                | 1        | 1      | 0.83%   |
| Azerty              | 1        | 1      | 0.83%   |
| AMD                 | 1        | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 93       | 132    | 40.26%  |
| HDD  | 90       | 164    | 38.96%  |
| NVMe | 48       | 58     | 20.78%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 149      | 296    | 75.63%  |
| NVMe | 48       | 58     | 24.37%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 125      | 183    | 64.43%  |
| 0.51-1.0   | 39       | 48     | 20.1%   |
| 1.01-2.0   | 16       | 35     | 8.25%   |
| 3.01-4.0   | 8        | 12     | 4.12%   |
| 4.01-10.0  | 3        | 12     | 1.55%   |
| 2.01-3.0   | 2        | 5      | 1.03%   |
| 10.01-20.0 | 1        | 1      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 93       | 53.76%  |
| 101-250    | 24       | 13.87%  |
| 251-500    | 22       | 12.72%  |
| 51-100     | 21       | 12.14%  |
| 501-1000   | 9        | 5.2%    |
| 21-50      | 2        | 1.16%   |
| 1001-2000  | 1        | 0.58%   |
| Unknown    | 1        | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 166      | 98.22%  |
| 251-500 | 1        | 0.59%   |
| 21-50   | 1        | 0.59%   |
| Unknown | 1        | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| WDC WD800JD-75MSA3 80GB                    | 1        | 1      | 2.56%   |
| WDC WD6400BPVT-22HXZT3 640GB               | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-08U6AA0 500GB               | 1        | 1      | 2.56%   |
| WDC WD5000AAKX-00ERMA0 500GB               | 1        | 1      | 2.56%   |
| WDC WD30EFRX-68EUZN0 3TB                   | 1        | 1      | 2.56%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1        | 1      | 2.56%   |
| WDC WD20EARS-00MVWB0 2TB                   | 1        | 1      | 2.56%   |
| WDC WD1600YS-01SHB1 164GB                  | 1        | 1      | 2.56%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 1      | 2.56%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1        | 1      | 2.56%   |
| WDC WD10EZEX-60M2NA0 1TB                   | 1        | 1      | 2.56%   |
| WDC WD10EARS-003BB1 1TB                    | 1        | 1      | 2.56%   |
| WDC WD10EADS-11M2B2 1TB                    | 1        | 1      | 2.56%   |
| Toshiba MK8052GSX 80GB                     | 1        | 1      | 2.56%   |
| Toshiba MK3259GSXP 320GB                   | 1        | 1      | 2.56%   |
| Toshiba DT01ACA100 1TB                     | 1        | 1      | 2.56%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB  | 1        | 1      | 2.56%   |
| Seagate ST500LM000-1EJ162 500GB            | 1        | 1      | 2.56%   |
| Seagate ST500DM002-1BD142 500GB            | 1        | 1      | 2.56%   |
| Seagate ST380215AS 80GB                    | 1        | 1      | 2.56%   |
| Seagate ST3750528AS 752GB                  | 1        | 1      | 2.56%   |
| Seagate ST3500418AS 500GB                  | 1        | 1      | 2.56%   |
| Seagate ST3500320AS 500GB                  | 1        | 1      | 2.56%   |
| Seagate ST3320620AS 320GB                  | 1        | 1      | 2.56%   |
| Seagate ST3250312AS 250GB                  | 1        | 2      | 2.56%   |
| Seagate ST2000DM008-2FR102 2TB             | 1        | 1      | 2.56%   |
| Seagate ST1000DM010-2EP102 1TB             | 1        | 1      | 2.56%   |
| Samsung Electronics SSD 860 EVO 500GB      | 1        | 1      | 2.56%   |
| Samsung Electronics MZVL22T0HBLB-00B00 2TB | 1        | 1      | 2.56%   |
| Samsung Electronics HD103SJ 1TB            | 1        | 1      | 2.56%   |
| Maxtor 6Y080M0 82GB                        | 1        | 1      | 2.56%   |
| Maxtor 6V080E0 80GB                        | 1        | 1      | 2.56%   |
| Maxtor 6L080P0 82GB                        | 1        | 1      | 2.56%   |
| Kingston SA400S37240G 240GB                | 1        | 1      | 2.56%   |
| Hitachi HTS725050A7E630 500GB              | 1        | 1      | 2.56%   |
| Hitachi HTS541680J9SA00 80GB               | 1        | 1      | 2.56%   |
| HGST HTS545050A7E680 500GB                 | 1        | 1      | 2.56%   |
| Crucial CT1050MX300SSD1 1TB                | 1        | 1      | 2.56%   |
| China SH00R120GB                           | 1        | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 13     | 33.33%  |
| Seagate             | 8        | 11     | 22.22%  |
| Toshiba             | 3        | 3      | 8.33%   |
| Samsung Electronics | 3        | 3      | 8.33%   |
| Maxtor              | 3        | 3      | 8.33%   |
| Hitachi             | 2        | 2      | 5.56%   |
| Silicon Motion      | 1        | 1      | 2.78%   |
| Kingston            | 1        | 1      | 2.78%   |
| HGST                | 1        | 1      | 2.78%   |
| Crucial             | 1        | 1      | 2.78%   |
| China               | 1        | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 13     | 40%     |
| Seagate             | 8        | 11     | 26.67%  |
| Toshiba             | 3        | 3      | 10%     |
| Maxtor              | 3        | 3      | 10%     |
| Hitachi             | 2        | 2      | 6.67%   |
| Samsung Electronics | 1        | 1      | 3.33%   |
| HGST                | 1        | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 30       | 34     | 83.33%  |
| SSD  | 4        | 4      | 11.11%  |
| NVMe | 2        | 2      | 5.56%   |

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
| Works    | 133      | 296    | 73.48%  |
| Malfunc  | 36       | 40     | 19.89%  |
| Detected | 9        | 15     | 4.97%   |
| Failed   | 3        | 3      | 1.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 123      | 52.56%  |
| AMD                         | 40       | 17.09%  |
| Samsung Electronics         | 19       | 8.12%   |
| Kingston Technology Company | 9        | 3.85%   |
| ASMedia Technology          | 6        | 2.56%   |
| Silicon Motion              | 5        | 2.14%   |
| Marvell Technology Group    | 5        | 2.14%   |
| Nvidia                      | 4        | 1.71%   |
| SanDisk                     | 3        | 1.28%   |
| Micron Technology           | 3        | 1.28%   |
| JMicron Technology          | 3        | 1.28%   |
| VIA Technologies            | 2        | 0.85%   |
| Realtek Semiconductor       | 2        | 0.85%   |
| Phison Electronics          | 2        | 0.85%   |
| Micron/Crucial Technology   | 2        | 0.85%   |
| ADATA Technology            | 2        | 0.85%   |
| SK hynix                    | 1        | 0.43%   |
| OCZ Technology Group        | 1        | 0.43%   |
| KIOXIA                      | 1        | 0.43%   |
| Broadcom / LSI              | 1        | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19       | 6.62%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 17       | 5.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 15       | 5.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 4.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 3.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 3.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 3.14%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 3.14%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 3.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.09%   |
| Samsung NVMe SSD Controller 980                                                         | 5        | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 1.74%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 4        | 1.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.39%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.39%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4        | 1.39%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4        | 1.39%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 1.05%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.05%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.05%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 1.05%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 1.05%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3        | 1.05%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3        | 1.05%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 1.05%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.7%    |
| Nvidia MCP61 IDE                                                                        | 2        | 0.7%    |
| Micron 2200S NVMe SSD [Cassandra]                                                       | 2        | 0.7%    |
| Kingston Company unknown                                                                | 2        | 0.7%    |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 2        | 0.7%    |
| Kingston Company A2000 NVMe SSD                                                         | 2        | 0.7%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.7%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2        | 0.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 133      | 58.85%  |
| NVMe | 47       | 20.8%   |
| IDE  | 36       | 15.93%  |
| RAID | 8        | 3.54%   |
| SAS  | 1        | 0.44%   |
| SCSI | 1        | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 125      | 73.96%  |
| AMD    | 44       | 26.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz              | 6        | 3.55%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4        | 2.37%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4        | 2.37%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3        | 1.78%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3        | 1.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3        | 1.78%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 3        | 1.78%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 3        | 1.78%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 1.78%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3        | 1.78%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 1.18%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2        | 1.18%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2        | 1.18%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2        | 1.18%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2        | 1.18%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 2        | 1.18%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 2        | 1.18%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2        | 1.18%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2        | 1.18%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2        | 1.18%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 2        | 1.18%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2        | 1.18%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2        | 1.18%   |
| Intel Celeron N5105 @ 2.00GHz                 | 2        | 1.18%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2        | 1.18%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 2        | 1.18%   |
| Intel 12th Gen Core i5-12400                  | 2        | 1.18%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2        | 1.18%   |
| AMD Ryzen 5 5600 6-Core Processor             | 2        | 1.18%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2        | 1.18%   |
| Intel Xeon W-2125 CPU @ 4.00GHz               | 1        | 0.59%   |
| Intel Xeon CPU W3670 @ 3.20GHz                | 1        | 0.59%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1        | 0.59%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1        | 0.59%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1        | 0.59%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1        | 0.59%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz           | 1        | 0.59%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz           | 1        | 0.59%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz           | 1        | 0.59%   |
| Intel Xeon                                    | 1        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 37       | 21.89%  |
| Intel Core i3           | 25       | 14.79%  |
| Intel Core i7           | 19       | 11.24%  |
| AMD Ryzen 5             | 16       | 9.47%   |
| Intel Celeron           | 12       | 7.1%    |
| Intel Xeon              | 10       | 5.92%   |
| Intel Core 2 Duo        | 7        | 4.14%   |
| AMD Ryzen 3             | 6        | 3.55%   |
| AMD Ryzen 7             | 5        | 2.96%   |
| Other                   | 4        | 2.37%   |
| Intel Pentium           | 4        | 2.37%   |
| AMD Phenom II X4        | 3        | 1.78%   |
| AMD Athlon II X2        | 3        | 1.78%   |
| Intel Core i9           | 2        | 1.18%   |
| Intel Core 2 Quad       | 2        | 1.18%   |
| AMD A4                  | 2        | 1.18%   |
| Intel Pentium Gold      | 1        | 0.59%   |
| Intel Pentium Dual-Core | 1        | 0.59%   |
| Intel Pentium 4         | 1        | 0.59%   |
| AMD Ryzen 9             | 1        | 0.59%   |
| AMD Phenom II X6        | 1        | 0.59%   |
| AMD Phenom II X2        | 1        | 0.59%   |
| AMD FX                  | 1        | 0.59%   |
| AMD E                   | 1        | 0.59%   |
| AMD Athlon X2           | 1        | 0.59%   |
| AMD Athlon II X4        | 1        | 0.59%   |
| AMD Athlon 64           | 1        | 0.59%   |
| AMD A10                 | 1        | 0.59%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 74       | 43.79%  |
| 2       | 44       | 26.04%  |
| 6       | 18       | 10.65%  |
| 12      | 12       | 7.1%    |
| 8       | 9        | 5.33%   |
| 16      | 4        | 2.37%   |
| Unknown | 4        | 2.37%   |
| 1       | 2        | 1.18%   |
| 24      | 1        | 0.59%   |
| 10      | 1        | 0.59%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 167      | 98.82%  |
| 2      | 2        | 1.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 106      | 62.72%  |
| 2       | 58       | 34.32%  |
| Unknown | 5        | 2.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 24       | 14.2%   |
| KabyLake      | 21       | 12.43%  |
| IvyBridge     | 17       | 10.06%  |
| Skylake       | 16       | 9.47%   |
| Zen+          | 12       | 7.1%    |
| SandyBridge   | 12       | 7.1%    |
| Zen 3         | 10       | 5.92%   |
| K10           | 10       | 5.92%   |
| Penryn        | 8        | 4.73%   |
| CometLake     | 6        | 3.55%   |
| Unknown       | 6        | 3.55%   |
| Zen           | 5        | 2.96%   |
| Core          | 4        | 2.37%   |
| Piledriver    | 3        | 1.78%   |
| Nehalem       | 3        | 1.78%   |
| Westmere      | 2        | 1.18%   |
| Silvermont    | 2        | 1.18%   |
| Goldmont plus | 2        | 1.18%   |
| Zen 2         | 1        | 0.59%   |
| NetBurst      | 1        | 0.59%   |
| K8 Hammer     | 1        | 0.59%   |
| Goldmont      | 1        | 0.59%   |
| Bulldozer     | 1        | 0.59%   |
| Bobcat        | 1        | 0.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 80       | 43.96%  |
| Nvidia                     | 51       | 28.02%  |
| AMD                        | 50       | 27.47%  |
| Matrox Electronics Systems | 1        | 0.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                       | 12       | 6.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 5.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8        | 4.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 3.78%   |
| Intel HD Graphics 630                                                       | 7        | 3.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7        | 3.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 3.24%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 3.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 3.24%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 5        | 2.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 2.16%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 1.62%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.62%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.62%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.62%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.62%   |
| AMD RS880 [Radeon HD 4250]                                                  | 3        | 1.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.62%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.08%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.08%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.08%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 1.08%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 2        | 1.08%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 1.08%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 1.08%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.08%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 1.08%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 1.08%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 1.08%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 1.08%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 1.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.08%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.54%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.54%   |
| Nvidia GT218M [GeForce 310M]                                                | 1        | 0.54%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.54%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.54%   |
| Nvidia GP106 [P106-100]                                                     | 1        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 62       | 36.26%  |
| 1 x Nvidia     | 46       | 26.9%   |
| 1 x AMD        | 40       | 23.39%  |
| Intel + AMD    | 9        | 5.26%   |
| 2 x Intel      | 6        | 3.51%   |
| Intel + Nvidia | 4        | 2.34%   |
| Other          | 1        | 0.58%   |
| 2 x AMD        | 1        | 0.58%   |
| 1 x Matrox     | 1        | 0.58%   |
| AMD + Nvidia   | 1        | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 131      | 77.06%  |
| Proprietary | 36       | 21.18%  |
| Unknown     | 3        | 1.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 107      | 62.57%  |
| 1.01-2.0   | 17       | 9.94%   |
| 3.01-4.0   | 16       | 9.36%   |
| 0.51-1.0   | 10       | 5.85%   |
| 5.01-6.0   | 8        | 4.68%   |
| 0.01-0.5   | 6        | 3.51%   |
| 7.01-8.0   | 4        | 2.34%   |
| 8.01-16.0  | 2        | 1.17%   |
| 2.01-3.0   | 1        | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 8        | 10.96%  |
| Hewlett-Packard      | 7        | 9.59%   |
| Dell                 | 7        | 9.59%   |
| BenQ                 | 7        | 9.59%   |
| Acer                 | 7        | 9.59%   |
| Goldstar             | 6        | 8.22%   |
| AOC                  | 4        | 5.48%   |
| Ancor Communications | 4        | 5.48%   |
| Philips              | 3        | 4.11%   |
| LG Electronics       | 2        | 2.74%   |
| Lenovo               | 2        | 2.74%   |
| ASUSTek Computer     | 2        | 2.74%   |
| Unknown              | 2        | 2.74%   |
| Vizio                | 1        | 1.37%   |
| Semp Toshiba         | 1        | 1.37%   |
| PKB                  | 1        | 1.37%   |
| NEC Computers        | 1        | 1.37%   |
| MStar                | 1        | 1.37%   |
| MSI                  | 1        | 1.37%   |
| Microstep            | 1        | 1.37%   |
| ITE                  | 1        | 1.37%   |
| Idek Iiyama          | 1        | 1.37%   |
| Eizo                 | 1        | 1.37%   |
| AUS                  | 1        | 1.37%   |
| Apple                | 1        | 1.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                      | 2        | 2.74%   |
| Unknown                                                                | 2        | 2.74%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                      | 1        | 1.37%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch              | 1        | 1.37%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch   | 1        | 1.37%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1        | 1.37%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1        | 1.37%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 480x270mm 21.7-inch      | 1        | 1.37%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch       | 1        | 1.37%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 1        | 1.37%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 600x340mm 27.2-inch | 1        | 1.37%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch   | 1        | 1.37%   |
| PKB LCD Monitor MAE200W 1680x1050                                      | 1        | 1.37%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch                | 1        | 1.37%   |
| Philips PHL 221S8L PHL091C 1920x1080 480x270mm 21.7-inch               | 1        | 1.37%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                      | 1        | 1.37%   |
| NEC Computers LCD Monitor 70GX2 1280x1024                              | 1        | 1.37%   |
| MStar TSB LEDTV MST0030 1920x1080 1150x650mm 52.0-inch                 | 1        | 1.37%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                        | 1        | 1.37%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                            | 1        | 1.37%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 1.37%   |
| LG Electronics LCD Monitor L1918S 1280x1024                            | 1        | 1.37%   |
| Lenovo L24e-30 LEN66BC 1920x1080 530x300mm 24.0-inch                   | 1        | 1.37%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                    | 1        | 1.37%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                  | 1        | 1.37%   |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160                             | 1        | 1.37%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 600x340mm 27.2-inch          | 1        | 1.37%   |
| Hewlett-Packard Z24nq HWP3239 2560x1440 530x300mm 24.0-inch            | 1        | 1.37%   |
| Hewlett-Packard w2007 HWP26A6 1680x1050 430x270mm 20.0-inch            | 1        | 1.37%   |
| Hewlett-Packard L1955 HWP262C 1280x1024 380x300mm 19.1-inch            | 1        | 1.37%   |
| Hewlett-Packard HPQ 600 AIO HWP108B 1920x1080 480x270mm 21.7-inch      | 1        | 1.37%   |
| Hewlett-Packard 32 Display HPN351A 1920x1080 700x390mm 31.5-inch       | 1        | 1.37%   |
| Hewlett-Packard 27o HPN342C 1920x1080 600x340mm 27.2-inch              | 1        | 1.37%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 1        | 1.37%   |
| Goldstar LG IPS QHD GSM5BC4 2560x1440 530x300mm 24.0-inch              | 1        | 1.37%   |
| Goldstar LG IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch           | 1        | 1.37%   |
| Goldstar E2242 GSM58BE 1920x1080 480x270mm 21.7-inch                   | 1        | 1.37%   |
| Goldstar 22EA53 GSM59A6 1920x1080 480x270mm 21.7-inch                  | 1        | 1.37%   |
| Goldstar 20EN43 GSM4EE3 1600x900 450x250mm 20.3-inch                   | 1        | 1.37%   |
| Eizo FS2331 ENC2211 1920x1080 510x290mm 23.1-inch                      | 1        | 1.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 39       | 53.42%  |
| 1366x768 (WXGA)    | 8        | 10.96%  |
| 2560x1440 (QHD)    | 6        | 8.22%   |
| 3840x2160 (4K)     | 3        | 4.11%   |
| 1680x1050 (WSXGA+) | 3        | 4.11%   |
| 1280x1024 (SXGA)   | 3        | 4.11%   |
| 1920x1200 (WUXGA)  | 2        | 2.74%   |
| 1600x900 (HD+)     | 2        | 2.74%   |
| 1440x900 (WXGA+)   | 2        | 2.74%   |
| Unknown            | 2        | 2.74%   |
| 5760x2160          | 1        | 1.37%   |
| 3840x1080          | 1        | 1.37%   |
| 1024x768 (XGA)     | 1        | 1.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 24.29%  |
| 21      | 13       | 18.57%  |
| 24      | 10       | 14.29%  |
| 27      | 8        | 11.43%  |
| 18      | 5        | 7.14%   |
| 23      | 4        | 5.71%   |
| 19      | 4        | 5.71%   |
| 31      | 3        | 4.29%   |
| 20      | 3        | 4.29%   |
| 52      | 1        | 1.43%   |
| 22      | 1        | 1.43%   |
| 14      | 1        | 1.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 25       | 35.71%  |
| 501-600     | 22       | 31.43%  |
| Unknown     | 17       | 24.29%  |
| 601-700     | 3        | 4.29%   |
| 351-400     | 1        | 1.43%   |
| 201-300     | 1        | 1.43%   |
| 1001-1500   | 1        | 1.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 44       | 63.77%  |
| Unknown | 17       | 24.64%  |
| 16/10   | 6        | 8.7%    |
| 5/4     | 1        | 1.45%   |
| 4/3     | 1        | 1.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 27       | 38.57%  |
| Unknown        | 17       | 24.29%  |
| 301-350        | 8        | 11.43%  |
| 151-200        | 7        | 10%     |
| 141-150        | 5        | 7.14%   |
| 351-500        | 3        | 4.29%   |
| More than 1000 | 1        | 1.43%   |
| 251-300        | 1        | 1.43%   |
| 101-110        | 1        | 1.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 32       | 46.38%  |
| Unknown | 17       | 24.64%  |
| 101-120 | 15       | 21.74%  |
| 121-160 | 3        | 4.35%   |
| 1-50    | 2        | 2.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 137      | 80.59%  |
| 0     | 28       | 16.47%  |
| 2     | 5        | 2.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 101      | 46.76%  |
| Intel                    | 70       | 32.41%  |
| Qualcomm Atheros         | 15       | 6.94%   |
| Ralink Technology        | 4        | 1.85%   |
| Ralink                   | 4        | 1.85%   |
| Broadcom                 | 4        | 1.85%   |
| TP-Link                  | 3        | 1.39%   |
| Samsung Electronics      | 3        | 1.39%   |
| Marvell Technology Group | 2        | 0.93%   |
| Huawei Technologies      | 2        | 0.93%   |
| D-Link                   | 2        | 0.93%   |
| National Semiconductor   | 1        | 0.46%   |
| MediaTek                 | 1        | 0.46%   |
| Edimax Technology        | 1        | 0.46%   |
| D-Link System            | 1        | 0.46%   |
| Atheros                  | 1        | 0.46%   |
| Accton Technology        | 1        | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 87       | 36.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 4.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 3.36%   |
| Intel Ethernet Controller I225-V                                  | 7        | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6        | 2.52%   |
| Intel Ethernet Connection I217-V                                  | 5        | 2.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 1.68%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 1.68%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.26%   |
| Intel Wireless 3165                                               | 3        | 1.26%   |
| Intel I211 Gigabit Network Connection                             | 3        | 1.26%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.26%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.84%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2        | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 0.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 2        | 0.84%   |
| Ralink RT2500 Wireless 802.11bg                                   | 2        | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2        | 0.84%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2        | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.84%   |
| Intel Wi-Fi 6 AX200                                               | 2        | 0.84%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.84%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 0.84%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 0.84%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.84%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 2        | 0.84%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.84%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1        | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 16       | 25.81%  |
| Intel                 | 16       | 25.81%  |
| Qualcomm Atheros      | 8        | 12.9%   |
| Ralink Technology     | 4        | 6.45%   |
| Ralink                | 4        | 6.45%   |
| Broadcom              | 4        | 6.45%   |
| TP-Link               | 3        | 4.84%   |
| D-Link                | 2        | 3.23%   |
| MediaTek              | 1        | 1.61%   |
| Edimax Technology     | 1        | 1.61%   |
| D-Link System         | 1        | 1.61%   |
| Atheros               | 1        | 1.61%   |
| Accton Technology     | 1        | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 6        | 9.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 4        | 6.35%   |
| Intel Wireless 3165                                                        | 3        | 4.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 2        | 3.17%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 2        | 3.17%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 2        | 3.17%   |
| Ralink RT2500 Wireless 802.11bg                                            | 2        | 3.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 2        | 3.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 2        | 3.17%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 2        | 3.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 2        | 3.17%   |
| Intel Wi-Fi 6 AX200                                                        | 2        | 3.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 3.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2        | 3.17%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 2        | 3.17%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 1        | 1.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1        | 1.59%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 1.59%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1        | 1.59%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 1.59%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                               | 1        | 1.59%   |
| Ralink RT3072 Wireless Adapter                                             | 1        | 1.59%   |
| Ralink MT7601U Wireless Adapter                                            | 1        | 1.59%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                  | 1        | 1.59%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 1        | 1.59%   |
| Intel Wireless 8265 / 8275                                                 | 1        | 1.59%   |
| Intel Wireless 8260                                                        | 1        | 1.59%   |
| Intel Wireless 7265                                                        | 1        | 1.59%   |
| Intel Wireless 7260                                                        | 1        | 1.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 1        | 1.59%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                   | 1        | 1.59%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 1.59%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1        | 1.59%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.D1) [Realtek RTL8188ETV]         | 1        | 1.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1        | 1.59%   |
| Broadcom BCM43224 802.11a/b/g/n                                            | 1        | 1.59%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                     | 1        | 1.59%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                          | 1        | 1.59%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]       | 1        | 1.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 94       | 54.65%  |
| Intel                    | 62       | 36.05%  |
| Qualcomm Atheros         | 7        | 4.07%   |
| Samsung Electronics      | 3        | 1.74%   |
| Marvell Technology Group | 2        | 1.16%   |
| Huawei Technologies      | 2        | 1.16%   |
| National Semiconductor   | 1        | 0.58%   |
| Broadcom                 | 1        | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 87       | 49.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 6.29%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 4.57%   |
| Intel Ethernet Controller I225-V                                  | 7        | 4%      |
| Intel Ethernet Connection I217-V                                  | 5        | 2.86%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 2.29%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 2.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3        | 1.71%   |
| Intel I211 Gigabit Network Connection                             | 3        | 1.71%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.71%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.71%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 1.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 1.14%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 1.14%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.14%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 1.14%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 1.14%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.14%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 2        | 1.14%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 1.14%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.57%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.57%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1        | 0.57%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.57%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.57%   |
| Intel Ethernet Connection (5) I219-V                              | 1        | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.57%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.57%   |
| Huawei USB Device                                                 | 1        | 0.57%   |
| Huawei Android ADB Interface                                      | 1        | 0.57%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1        | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 164      | 74.21%  |
| WiFi     | 57       | 25.79%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 146      | 95.42%  |
| WiFi     | 7        | 4.58%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 117      | 68.82%  |
| 2     | 45       | 26.47%  |
| 3     | 4        | 2.35%   |
| 0     | 4        | 2.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 162      | 94.19%  |
| Yes  | 10       | 5.81%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 15       | 30.61%  |
| Realtek Semiconductor           | 10       | 20.41%  |
| Cambridge Silicon Radio         | 9        | 18.37%  |
| ASUSTek Computer                | 3        | 6.12%   |
| TP-Link                         | 2        | 4.08%   |
| IMC Networks                    | 2        | 4.08%   |
| Broadcom                        | 2        | 4.08%   |
| Apple                           | 2        | 4.08%   |
| Qualcomm Atheros Communications | 1        | 2.04%   |
| Primax Electronics              | 1        | 2.04%   |
| Lite-On Technology              | 1        | 2.04%   |
| Fujitsu                         | 1        | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 9        | 18.37%  |
| Realtek Bluetooth Adapter                                   | 7        | 14.29%  |
| Intel Bluetooth wireless interface                          | 7        | 14.29%  |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2        | 4.08%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2        | 4.08%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2        | 4.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2        | 4.08%   |
| Intel AX201 Bluetooth                                       | 2        | 4.08%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2        | 4.08%   |
| Realtek Bluetooth 5.1 Adapter                               | 1        | 2.04%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 2.04%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1        | 2.04%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1        | 2.04%   |
| Intel AX210 Bluetooth                                       | 1        | 2.04%   |
| Intel AX200 Bluetooth                                       | 1        | 2.04%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS     | 1        | 2.04%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1        | 2.04%   |
| Fujitsu Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter  | 1        | 2.04%   |
| ASUS USB-BT500                                              | 1        | 2.04%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 2.04%   |
| ASUS Bluetooth Controller                                   | 1        | 2.04%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 2.04%   |
| Apple Bluetooth Host Controller                             | 1        | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 118      | 44.87%  |
| AMD                      | 62       | 23.57%  |
| Nvidia                   | 47       | 17.87%  |
| C-Media Electronics      | 15       | 5.7%    |
| Texas Instruments        | 4        | 1.52%   |
| Realtek Semiconductor    | 2        | 0.76%   |
| Creative Labs            | 2        | 0.76%   |
| Unknown                  | 2        | 0.76%   |
| Yamaha                   | 1        | 0.38%   |
| Razer USA                | 1        | 0.38%   |
| OPPO Electronics         | 1        | 0.38%   |
| KTMicro                  | 1        | 0.38%   |
| JMTek                    | 1        | 0.38%   |
| Hewlett-Packard          | 1        | 0.38%   |
| HECATE G2 GAMING HEADSET | 1        | 0.38%   |
| Harman                   | 1        | 0.38%   |
| Generalplus Technology   | 1        | 0.38%   |
| GEMBIRD                  | 1        | 0.38%   |
| Edifier Technology       | 1        | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20       | 6.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16       | 5.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16       | 5.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15       | 4.85%   |
| Intel 200 Series PCH HD Audio                                              | 13       | 4.21%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 4.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10       | 3.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 2.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 2.59%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 2.59%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8        | 2.59%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 8        | 2.59%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 7        | 2.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 2.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7        | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6        | 1.94%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.62%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.62%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.29%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 1.29%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 1.29%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 3        | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.97%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3        | 0.97%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.97%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 0.97%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 3        | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 0.97%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 0.97%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 3        | 0.97%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 0.97%   |
| AMD FCH Azalia Controller                                                  | 3        | 0.97%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.65%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 0.65%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 2        | 0.65%   |
| Intel Jasper Lake HD Audio                                                 | 2        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 38       | 18.63%  |
| Samsung Electronics | 25       | 12.25%  |
| Unknown             | 20       | 9.8%    |
| Corsair             | 19       | 9.31%   |
| Micron Technology   | 14       | 6.86%   |
| Crucial             | 14       | 6.86%   |
| SK hynix            | 13       | 6.37%   |
| Unknown             | 10       | 4.9%    |
| G.Skill             | 9        | 4.41%   |
| Patriot             | 5        | 2.45%   |
| Nanya Technology    | 5        | 2.45%   |
| Ramaxel Technology  | 4        | 1.96%   |
| A-DATA Technology   | 4        | 1.96%   |
| Apacer              | 3        | 1.47%   |
| Unknown (ABCD)      | 2        | 0.98%   |
| Kingmax             | 2        | 0.98%   |
| GOODRAM             | 2        | 0.98%   |
| Atermiter           | 2        | 0.98%   |
| Unknown (8A02)      | 1        | 0.49%   |
| Transcend           | 1        | 0.49%   |
| Teikon              | 1        | 0.49%   |
| Team                | 1        | 0.49%   |
| Smart               | 1        | 0.49%   |
| Qumo                | 1        | 0.49%   |
| MemoWise            | 1        | 0.49%   |
| Lexar               | 1        | 0.49%   |
| Juhor               | 1        | 0.49%   |
| Golden Empire       | 1        | 0.49%   |
| Elpida              | 1        | 0.49%   |
| Avant               | 1        | 0.49%   |
| AMD                 | 1        | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 10       | 4.57%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                   | 3        | 1.37%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 2        | 0.91%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                | 2        | 0.91%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                     | 2        | 0.91%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 2        | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s            | 2        | 0.91%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                             | 2        | 0.91%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                     | 2        | 0.91%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s                     | 2        | 0.91%   |
| Samsung RAM M3 78T2863DZS-CE6 1GB DIMM DDR2 667MT/s                     | 2        | 0.91%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                     | 2        | 0.91%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                       | 2        | 0.91%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                     | 2        | 0.91%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                     | 2        | 0.91%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                     | 2        | 0.91%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 2        | 0.91%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s                    | 2        | 0.91%   |
| Corsair RAM CMK32GX4M2A2400C16 16GB DIMM DDR4 2400MT/s                  | 2        | 0.91%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 0.46%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                    | 1        | 0.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1        | 0.46%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 1        | 0.46%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                    | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                               | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                               | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                                 | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                     | 1        | 0.46%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                                    | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                                | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2                                        | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR 667MT/s                                 | 1        | 0.46%   |
| Unknown RAM Module 1GB DIMM 400MT/s                                     | 1        | 0.46%   |
| Unknown (8A02) RAM Module 8GB DIMM DDR3 1600MT/s                        | 1        | 0.46%   |
| Transcend RAM JM1333KLN-2G 2GB DIMM DDR3 1333MT/s                       | 1        | 0.46%   |
| Teikon RAM TMT41GS6BFR8A-PBHC 8GB SODIMM DDR3 1600MT/s                  | 1        | 0.46%   |
| Team RAM Elite-1600 8GB DIMM DDR3 1600MT/s                              | 1        | 0.46%   |
| Smart RAM SH564128FH8N0QNSCG 4GB DIMM DDR3 1600MT/s                     | 1        | 0.46%   |
| SK hynix RAM Module 2GB DIMM DDR2 1639MT/s                              | 1        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 79       | 46.75%  |
| DDR3    | 60       | 35.5%   |
| DDR2    | 12       | 7.1%    |
| Unknown | 12       | 7.1%    |
| SDRAM   | 2        | 1.18%   |
| LPDDR4  | 2        | 1.18%   |
| DDR     | 2        | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 143      | 85.12%  |
| SODIMM | 25       | 14.88%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 78       | 40.84%  |
| 4096  | 48       | 25.13%  |
| 2048  | 32       | 16.75%  |
| 16384 | 21       | 10.99%  |
| 1024  | 11       | 5.76%   |
| 32768 | 1        | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 34       | 18.89%  |
| 1333    | 31       | 17.22%  |
| 2133    | 19       | 10.56%  |
| 3200    | 17       | 9.44%   |
| 2667    | 17       | 9.44%   |
| 2400    | 17       | 9.44%   |
| 800     | 9        | 5%      |
| 3600    | 6        | 3.33%   |
| 1067    | 5        | 2.78%   |
| 667     | 5        | 2.78%   |
| 1066    | 4        | 2.22%   |
| 2666    | 3        | 1.67%   |
| Unknown | 3        | 1.67%   |
| 3000    | 2        | 1.11%   |
| 400     | 2        | 1.11%   |
| 4400    | 1        | 0.56%   |
| 3333    | 1        | 0.56%   |
| 1867    | 1        | 0.56%   |
| 1639    | 1        | 0.56%   |
| 1200    | 1        | 0.56%   |
| 533     | 1        | 0.56%   |

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
| Microdia                      | 3        | 21.43%  |
| Logitech                      | 3        | 21.43%  |
| Trust                         | 1        | 7.14%   |
| Sunplus Innovation Technology | 1        | 7.14%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 7.14%   |
| Importek                      | 1        | 7.14%   |
| IMC Networks                  | 1        | 7.14%   |
| Genesys Logic                 | 1        | 7.14%   |
| GEMBIRD                       | 1        | 7.14%   |
| Chicony Electronics           | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Microdia USB 2.0 Camera                           | 2        | 14.29%  |
| Logitech Webcam C270                              | 2        | 14.29%  |
| Trust Trust Full HD Webcam                        | 1        | 7.14%   |
| Sunplus SPCA2650 AV Camera                        | 1        | 7.14%   |
| SHENZHEN AONI ELECTRONIC NexiGo N990 4K Camera    | 1        | 7.14%   |
| Microdia Webcam Vitade AF                         | 1        | 7.14%   |
| Logitech HD Pro Webcam C920                       | 1        | 7.14%   |
| Importek FJ Camera                                | 1        | 7.14%   |
| IMC Networks XHC Camera                           | 1        | 7.14%   |
| Genesys Logic Digital Microscope                  | 1        | 7.14%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 7.14%   |
| Chicony HP 2.0MP High Definition Webcam           | 1        | 7.14%   |

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
| 1     | 82       | 48.24%  |
| 0     | 54       | 31.76%  |
| 2     | 30       | 17.65%  |
| 3     | 3        | 1.76%   |
| 4     | 1        | 0.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 104      | 73.24%  |
| Net/wireless             | 18       | 12.68%  |
| Sound                    | 12       | 8.45%   |
| Bluetooth                | 4        | 2.82%   |
| Card reader              | 2        | 1.41%   |
| Network                  | 1        | 0.7%    |
| Dvb card                 | 1        | 0.7%    |

