FreeBSD 13.1 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 13.1.

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

Total: 118

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | Pro WS X570-ACE             | [89f0463ec6](https://bsd-hardware.info/?probe=89f0463ec6) | Dec 10, 2023 |
| Unknown       | Unknown                     | [1ba135fef1](https://bsd-hardware.info/?probe=1ba135fef1) | Sep 24, 2023 |
| Unknown       | Unknown                     | [9c8516c8a8](https://bsd-hardware.info/?probe=9c8516c8a8) | Sep 24, 2023 |
| MSI           | H510I PRO WIFI              | [743d249ba5](https://bsd-hardware.info/?probe=743d249ba5) | Jul 07, 2023 |
| Gigabyte      | B360M D2V                   | [bf5f6fd6dd](https://bsd-hardware.info/?probe=bf5f6fd6dd) | Jun 30, 2023 |
| ASRockRack    | GENOAD8UD-2T/X550           | [c6b62c6b5b](https://bsd-hardware.info/?probe=c6b62c6b5b) | May 26, 2023 |
| Dell          | 0H634K A00                  | [5e783a1c2e](https://bsd-hardware.info/?probe=5e783a1c2e) | Apr 30, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c7944c3ce9](https://bsd-hardware.info/?probe=c7944c3ce9) | Mar 31, 2023 |
| HP            | 339A                        | [ad10416fe3](https://bsd-hardware.info/?probe=ad10416fe3) | Mar 31, 2023 |
| Gigabyte      | B360M D2V                   | [6ac60b8104](https://bsd-hardware.info/?probe=6ac60b8104) | Mar 10, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [735f2f3ece](https://bsd-hardware.info/?probe=735f2f3ece) | Feb 28, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [b0fcea0c90](https://bsd-hardware.info/?probe=b0fcea0c90) | Feb 27, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b2681fdfb4](https://bsd-hardware.info/?probe=b2681fdfb4) | Feb 23, 2023 |
| ASRock        | X570 Taichi                 | [8eb068a097](https://bsd-hardware.info/?probe=8eb068a097) | Feb 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [6f4b514959](https://bsd-hardware.info/?probe=6f4b514959) | Feb 14, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [d69aba5432](https://bsd-hardware.info/?probe=d69aba5432) | Feb 14, 2023 |
| ASUSTek       | P8Z68 DELUXE                | [f65675c771](https://bsd-hardware.info/?probe=f65675c771) | Feb 13, 2023 |
| ASUSTek       | H170I-PRO                   | [63000ada74](https://bsd-hardware.info/?probe=63000ada74) | Feb 12, 2023 |
| Gigabyte      | H61M-S2V-B3                 | [33af90dd93](https://bsd-hardware.info/?probe=33af90dd93) | Feb 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [82ab576c6c](https://bsd-hardware.info/?probe=82ab576c6c) | Jan 31, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [95ebd841b2](https://bsd-hardware.info/?probe=95ebd841b2) | Jan 12, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [8def3dc9b2](https://bsd-hardware.info/?probe=8def3dc9b2) | Jan 09, 2023 |
| Acer          | Veriton M680G               | [cb44a9e848](https://bsd-hardware.info/?probe=cb44a9e848) | Dec 19, 2022 |
| Acer          | Veriton M680G               | [f7184d9158](https://bsd-hardware.info/?probe=f7184d9158) | Dec 19, 2022 |
| ASRock        | B660M-ITX/ac                | [f6c8eb4e18](https://bsd-hardware.info/?probe=f6c8eb4e18) | Dec 18, 2022 |
| Huanan        | X99-F8D V2.4                | [3d06b605c5](https://bsd-hardware.info/?probe=3d06b605c5) | Dec 13, 2022 |
| Huanan        | X99-F8D V2.4                | [f6685811a3](https://bsd-hardware.info/?probe=f6685811a3) | Dec 05, 2022 |
| Dell          | 0PTTT9 A01                  | [74575d6dfe](https://bsd-hardware.info/?probe=74575d6dfe) | Nov 25, 2022 |
| Huanan        | X99-F8D V2.4                | [9faf79b3f3](https://bsd-hardware.info/?probe=9faf79b3f3) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | [f732942dd9](https://bsd-hardware.info/?probe=f732942dd9) | Nov 18, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [443891740b](https://bsd-hardware.info/?probe=443891740b) | Nov 13, 2022 |
| Huanan        | X99-F8D V2.4                | [22ec05d988](https://bsd-hardware.info/?probe=22ec05d988) | Nov 12, 2022 |
| Google        | Zako                        | [5d4b53e2d4](https://bsd-hardware.info/?probe=5d4b53e2d4) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d27fd3b1a7](https://bsd-hardware.info/?probe=d27fd3b1a7) | Nov 04, 2022 |
| Unknown       | Unknown                     | [58c2f4b4f7](https://bsd-hardware.info/?probe=58c2f4b4f7) | Nov 04, 2022 |
| HP            | 18E4                        | [d66ffbbf6d](https://bsd-hardware.info/?probe=d66ffbbf6d) | Oct 21, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [3e2f5956c1](https://bsd-hardware.info/?probe=3e2f5956c1) | Oct 19, 2022 |
| ASUSTek       | P8B75-M                     | [2620fd3511](https://bsd-hardware.info/?probe=2620fd3511) | Oct 04, 2022 |
| AMI           | MNHO-048                    | [2ec6e55a75](https://bsd-hardware.info/?probe=2ec6e55a75) | Sep 28, 2022 |
| NITRINOnet    | M360RUS56                   | [490b9593e0](https://bsd-hardware.info/?probe=490b9593e0) | Sep 23, 2022 |
| HP            | 21D0                        | [43fa46655e](https://bsd-hardware.info/?probe=43fa46655e) | Sep 21, 2022 |
| HP            | 21D0                        | [463e2563d7](https://bsd-hardware.info/?probe=463e2563d7) | Sep 19, 2022 |
| Unknown       | Unknown                     | [83e48aa232](https://bsd-hardware.info/?probe=83e48aa232) | Sep 16, 2022 |
| Intel         | X79 V2.72A                  | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| ASRock        | AD2550-ITX                  | [43d0101ac4](https://bsd-hardware.info/?probe=43d0101ac4) | Aug 24, 2022 |
| Dell          | 042P49 A00                  | [7130975fe3](https://bsd-hardware.info/?probe=7130975fe3) | Aug 17, 2022 |
| MSI           | H81M-P33                    | [3d0836d403](https://bsd-hardware.info/?probe=3d0836d403) | Aug 14, 2022 |
| ASUSTek       | P5Q-E                       | [c50be0ecae](https://bsd-hardware.info/?probe=c50be0ecae) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4b6ad32189](https://bsd-hardware.info/?probe=4b6ad32189) | Aug 14, 2022 |
| ASRock        | H110M-DGS R3.0              | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| Dell          | 042P49 A00                  | [a38375fa97](https://bsd-hardware.info/?probe=a38375fa97) | Aug 08, 2022 |
| Dell          | 042P49 A00                  | [81a5e313cd](https://bsd-hardware.info/?probe=81a5e313cd) | Aug 08, 2022 |
| GVC           | DR 738                      | [ea08102a81](https://bsd-hardware.info/?probe=ea08102a81) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| Gigabyte      | H81M-DS2                    | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Gigabyte      | P85-D3                      | [7f077abed9](https://bsd-hardware.info/?probe=7f077abed9) | Aug 02, 2022 |
| ASUSTek       | B85-PRO GAMER               | [b29e940a75](https://bsd-hardware.info/?probe=b29e940a75) | Aug 02, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| Dell          | 0T7D40 A01                  | [bd2f6f8596](https://bsd-hardware.info/?probe=bd2f6f8596) | Jul 29, 2022 |
| Dell          | 040DDP A01                  | [5d4d3d7553](https://bsd-hardware.info/?probe=5d4d3d7553) | Jul 29, 2022 |
| HP            | 1825                        | [8c96329681](https://bsd-hardware.info/?probe=8c96329681) | Jul 24, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | [6cdc79a36f](https://bsd-hardware.info/?probe=6cdc79a36f) | Jul 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | [051f604f9a](https://bsd-hardware.info/?probe=051f604f9a) | Jul 21, 2022 |
| Dell          | 0WR7PY A03                  | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Dell          | 08HPGT A02                  | [ae260e17eb](https://bsd-hardware.info/?probe=ae260e17eb) | Jul 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3bf44f4bb5](https://bsd-hardware.info/?probe=3bf44f4bb5) | Jul 17, 2022 |
| Acer          | Veriton X490G               | [2912c74632](https://bsd-hardware.info/?probe=2912c74632) | Jul 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| MouseCompu... | B360M                       | [3c22f3e91b](https://bsd-hardware.info/?probe=3c22f3e91b) | Jul 13, 2022 |
| Acer          | Veriton X490G               | [cbae2b155b](https://bsd-hardware.info/?probe=cbae2b155b) | Jul 11, 2022 |
| Acer          | Veriton X490G               | [3cd79878cd](https://bsd-hardware.info/?probe=3cd79878cd) | Jul 11, 2022 |
| Unknown       | Unknown                     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Intel         | DN2820FYK H24582-203        | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| ASUSTek       | PRIME A520M-A II            | [0819ecdcf9](https://bsd-hardware.info/?probe=0819ecdcf9) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | [d459d3431a](https://bsd-hardware.info/?probe=d459d3431a) | Jul 07, 2022 |
| Acer          | Aspire XC-895 V:1.0         | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| ASRock        | Z490M Pro4                  | [b57457834e](https://bsd-hardware.info/?probe=b57457834e) | Jul 04, 2022 |
| Gigabyte      | Z370M D3H-CF                | [1d3db5e35a](https://bsd-hardware.info/?probe=1d3db5e35a) | Jul 04, 2022 |
| ASRock        | X300M-STX                   | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| ASRock        | P67 Professional            | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Gigabyte      | H61MA-D3V                   | [898da0bcec](https://bsd-hardware.info/?probe=898da0bcec) | Jun 28, 2022 |
| ASUSTek       | PRIME Z590-P                | [70aea59a1b](https://bsd-hardware.info/?probe=70aea59a1b) | Jun 25, 2022 |
| ASUSTek       | PRIME Z590-P                | [c285cb7899](https://bsd-hardware.info/?probe=c285cb7899) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7d054ce34f](https://bsd-hardware.info/?probe=7d054ce34f) | Jun 23, 2022 |
| MSI           | B85M-E45                    | [d9cc6cee6b](https://bsd-hardware.info/?probe=d9cc6cee6b) | Jun 21, 2022 |
| Intel         | D945GCLF2 AAE46416-104      | [84f2afeff4](https://bsd-hardware.info/?probe=84f2afeff4) | Jun 21, 2022 |
| ASUSTek       | Z87M-PLUS                   | [5e51d228ec](https://bsd-hardware.info/?probe=5e51d228ec) | Jun 21, 2022 |
| HP            | 3031h                       | [96ecd77f94](https://bsd-hardware.info/?probe=96ecd77f94) | Jun 19, 2022 |
| HP            | 3031h                       | [4da4d936b8](https://bsd-hardware.info/?probe=4da4d936b8) | Jun 19, 2022 |
| HP            | 86E9 A                      | [1d1ac2dd90](https://bsd-hardware.info/?probe=1d1ac2dd90) | Jun 16, 2022 |
| Dell          | 07KY25 A00                  | [9981217b1b](https://bsd-hardware.info/?probe=9981217b1b) | Jun 16, 2022 |
| Dell          | 0HMF7C A01                  | [ad0f6d4b31](https://bsd-hardware.info/?probe=ad0f6d4b31) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1febab0774](https://bsd-hardware.info/?probe=1febab0774) | Jun 12, 2022 |
| Supermicro    | X9DR3-F                     | [d81151c0e8](https://bsd-hardware.info/?probe=d81151c0e8) | Jun 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [5215d1ebb8](https://bsd-hardware.info/?probe=5215d1ebb8) | Jun 12, 2022 |
| MSI           | Z590 PRO WIFI               | [29b410eeb6](https://bsd-hardware.info/?probe=29b410eeb6) | Jun 06, 2022 |
| Gigabyte      | F2A75M-D3H                  | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| NF-M2S        | ABIT                        | [bef9700756](https://bsd-hardware.info/?probe=bef9700756) | May 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [f39611345a](https://bsd-hardware.info/?probe=f39611345a) | May 30, 2022 |
| Unknown       | Unknown                     | [90b27f0ac1](https://bsd-hardware.info/?probe=90b27f0ac1) | May 29, 2022 |
| ASUSTek       | P5Q-E                       | [cf67e4079f](https://bsd-hardware.info/?probe=cf67e4079f) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [8ebd281f5f](https://bsd-hardware.info/?probe=8ebd281f5f) | May 29, 2022 |
| MSI           | H81M-P33                    | [ab2181e1b4](https://bsd-hardware.info/?probe=ab2181e1b4) | May 29, 2022 |
| PC Engines    | APU3                        | [fca5a642c2](https://bsd-hardware.info/?probe=fca5a642c2) | May 28, 2022 |
| Unknown       | Unknown                     | [4e15ce78c8](https://bsd-hardware.info/?probe=4e15ce78c8) | May 26, 2022 |
| HP            | 158A                        | [883958cd36](https://bsd-hardware.info/?probe=883958cd36) | May 25, 2022 |
| Unknown       | Unknown                     | [78d1ad4565](https://bsd-hardware.info/?probe=78d1ad4565) | May 25, 2022 |
| ASRockRack    | E3C242D4U2-2T               | [d35f1fb7e0](https://bsd-hardware.info/?probe=d35f1fb7e0) | May 25, 2022 |
| Dell          | 055H3G A01                  | [cc1c76afc0](https://bsd-hardware.info/?probe=cc1c76afc0) | May 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a74913bffa](https://bsd-hardware.info/?probe=a74913bffa) | May 23, 2022 |
| GVC           | DR 738                      | [938866fb80](https://bsd-hardware.info/?probe=938866fb80) | May 21, 2022 |
| Gigabyte      | H61MA-D3V                   | [f369e09063](https://bsd-hardware.info/?probe=f369e09063) | May 19, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [9c459aae41](https://bsd-hardware.info/?probe=9c459aae41) | May 19, 2022 |
| Dell          | 0DXJD9 A01                  | [be13c9069c](https://bsd-hardware.info/?probe=be13c9069c) | May 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [edcd612c83](https://bsd-hardware.info/?probe=edcd612c83) | May 18, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2    | [b87692aeb4](https://bsd-hardware.info/?probe=b87692aeb4) | May 15, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 87       | 90.63%  |
| arm   | 5        | 5.21%   |
| arm64 | 3        | 3.13%   |
| i386  | 1        | 1.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Console   | 41       | 42.27%  |
| XFCE      | 15       | 15.46%  |
| KDE5      | 14       | 14.43%  |
| TWM       | 5        | 5.15%   |
| MATE      | 5        | 5.15%   |
| Openbox   | 3        | 3.09%   |
| LXDE      | 2        | 2.06%   |
| i3        | 2        | 2.06%   |
| GNOME     | 2        | 2.06%   |
| plasma    | 1        | 1.03%   |
| LXQt      | 1        | 1.03%   |
| fvwm2     | 1        | 1.03%   |
| Compton   | 1        | 1.03%   |
| Cinnamon  | 1        | 1.03%   |
| Budgie    | 1        | 1.03%   |
| bspwm     | 1        | 1.03%   |
| AwesomeWM | 1        | 1.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 52       | 54.17%  |
| Console | 43       | 44.79%  |
| Tty     | 1        | 1.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 58       | 60.42%  |
| SDDM    | 14       | 14.58%  |
| LightDM | 8        | 8.33%   |
| XDM     | 6        | 6.25%   |
| SLiM    | 6        | 6.25%   |
| Ly      | 2        | 2.08%   |
| GDM     | 2        | 2.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 67       | 69.79%  |
| en_US   | 10       | 10.42%  |
| ru_RU   | 7        | 7.29%   |
| Unknown | 6        | 6.25%   |
| fr_FR   | 3        | 3.13%   |
| ja_JP   | 1        | 1.04%   |
| en_GB   | 1        | 1.04%   |
| de_DE   | 1        | 1.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 63       | 64.95%  |
| BIOS | 34       | 35.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 62       | 64.58%  |
| Ufs  | 34       | 35.42%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 87       | 90.63%  |
| MBR  | 9        | 9.38%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 19       | 19.79%  |
| Gigabyte Technology | 11       | 11.46%  |
| Dell                | 11       | 11.46%  |
| Hewlett-Packard     | 8        | 8.33%   |
| ASRock              | 8        | 8.33%   |
| Unknown             | 8        | 8.33%   |
| MSI                 | 7        | 7.29%   |
| Intel               | 4        | 4.17%   |
| Acer                | 4        | 4.17%   |
| Fujitsu             | 2        | 2.08%   |
| ASRockRack          | 2        | 2.08%   |
| Supermicro          | 1        | 1.04%   |
| Seeed Studio        | 1        | 1.04%   |
| PC Engines          | 1        | 1.04%   |
| NITRINOnet          | 1        | 1.04%   |
| NF-M2S              | 1        | 1.04%   |
| MouseComputer       | 1        | 1.04%   |
| Lenovo              | 1        | 1.04%   |
| Huanan              | 1        | 1.04%   |
| GVC                 | 1        | 1.04%   |
| Google              | 1        | 1.04%   |
| Foxconn             | 1        | 1.04%   |
| AMI                 | 1        | 1.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 8        | 8.33%   |
| ASUS All Series                    | 4        | 4.17%   |
| MSI MS-7817                        | 2        | 2.08%   |
| Dell Precision T3600               | 2        | 2.08%   |
| Supermicro Icebreaker 4824         | 1        | 1.04%   |
| Seeed Studio ODYSSEY-X86J4105      | 1        | 1.04%   |
| PC Engines APU3                    | 1        | 1.04%   |
| NITRINOnet M360RUS56               | 1        | 1.04%   |
| NF-M2S ABIT                        | 1        | 1.04%   |
| MSI MS-7D16                        | 1        | 1.04%   |
| MSI MS-7D09                        | 1        | 1.04%   |
| MSI MS-7D08                        | 1        | 1.04%   |
| MSI MS-7C91                        | 1        | 1.04%   |
| MSI MS-7B86                        | 1        | 1.04%   |
| MouseComputer B360M                | 1        | 1.04%   |
| Lenovo H515 10125                  | 1        | 1.04%   |
| Intel X79 V2.72A                   | 1        | 1.04%   |
| Intel Q3XXG4-P V1.0                | 1        | 1.04%   |
| Intel DN2820FYK H24582-203         | 1        | 1.04%   |
| Intel D945GCLF2 AAE46416-104       | 1        | 1.04%   |
| Huanan X99-F8D V2.4                | 1        | 1.04%   |
| HP Z620 Workstation                | 1        | 1.04%   |
| HP ProLiant ML310e Gen8 v2         | 1        | 1.04%   |
| HP ProDesk 600 G1 DM               | 1        | 1.04%   |
| HP EliteDesk 800 G1 TWR            | 1        | 1.04%   |
| HP EliteDesk 800 G1 DM             | 1        | 1.04%   |
| HP Desktop M01-F0xxx               | 1        | 1.04%   |
| HP Compaq Pro 6300 MT              | 1        | 1.04%   |
| HP Compaq dc7900 Small Form Factor | 1        | 1.04%   |
| GVC EQUIUM 3200M                   | 1        | 1.04%   |
| Google Zako                        | 1        | 1.04%   |
| Gigabyte Z370M D3H                 | 1        | 1.04%   |
| Gigabyte X470 AORUS GAMING 7 WIFI  | 1        | 1.04%   |
| Gigabyte P85-D3                    | 1        | 1.04%   |
| Gigabyte H97M-HD3                  | 1        | 1.04%   |
| Gigabyte H61MA-D3V                 | 1        | 1.04%   |
| Gigabyte H61M-S2V-B3               | 1        | 1.04%   |
| Gigabyte GB-BSi3-1115G4            | 1        | 1.04%   |
| Gigabyte F2A75M-D3H                | 1        | 1.04%   |
| Gigabyte B550M AORUS PRO-P         | 1        | 1.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 8        | 8.33%   |
| Dell OptiPlex                 | 7        | 7.29%   |
| ASUS All                      | 4        | 4.17%   |
| ASUS ROG                      | 3        | 3.13%   |
| ASUS PRIME                    | 3        | 3.13%   |
| MSI MS-7817                   | 2        | 2.08%   |
| HP EliteDesk                  | 2        | 2.08%   |
| HP Compaq                     | 2        | 2.08%   |
| Dell Precision                | 2        | 2.08%   |
| ASUS Pro                      | 2        | 2.08%   |
| Acer Veriton                  | 2        | 2.08%   |
| Supermicro Icebreaker         | 1        | 1.04%   |
| Seeed Studio ODYSSEY-X86J4105 | 1        | 1.04%   |
| PC Engines APU3               | 1        | 1.04%   |
| NITRINOnet M360RUS56          | 1        | 1.04%   |
| NF-M2S ABIT                   | 1        | 1.04%   |
| MSI MS-7D16                   | 1        | 1.04%   |
| MSI MS-7D09                   | 1        | 1.04%   |
| MSI MS-7D08                   | 1        | 1.04%   |
| MSI MS-7C91                   | 1        | 1.04%   |
| MSI MS-7B86                   | 1        | 1.04%   |
| MouseComputer B360M           | 1        | 1.04%   |
| Lenovo H515                   | 1        | 1.04%   |
| Intel X79                     | 1        | 1.04%   |
| Intel Q3XXG4-P                | 1        | 1.04%   |
| Intel DN2820FYK               | 1        | 1.04%   |
| Intel D945GCLF2               | 1        | 1.04%   |
| Huanan X99-F8D                | 1        | 1.04%   |
| HP Z620                       | 1        | 1.04%   |
| HP ProLiant                   | 1        | 1.04%   |
| HP ProDesk                    | 1        | 1.04%   |
| HP Desktop                    | 1        | 1.04%   |
| GVC EQUIUM                    | 1        | 1.04%   |
| Google Zako                   | 1        | 1.04%   |
| Gigabyte Z370M                | 1        | 1.04%   |
| Gigabyte X470                 | 1        | 1.04%   |
| Gigabyte P85-D3               | 1        | 1.04%   |
| Gigabyte H97M-HD3             | 1        | 1.04%   |
| Gigabyte H61MA-D3V            | 1        | 1.04%   |
| Gigabyte H61M-S2V-B3          | 1        | 1.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 13       | 13.54%  |
| 2021    | 12       | 12.5%   |
| 2014    | 9        | 9.38%   |
| Unknown | 9        | 9.38%   |
| 2018    | 8        | 8.33%   |
| 2019    | 7        | 7.29%   |
| 2013    | 7        | 7.29%   |
| 2022    | 6        | 6.25%   |
| 2016    | 5        | 5.21%   |
| 2012    | 5        | 5.21%   |
| 2011    | 4        | 4.17%   |
| 2008    | 4        | 4.17%   |
| 2017    | 3        | 3.13%   |
| 2010    | 2        | 2.08%   |
| 2023    | 1        | 1.04%   |
| 2015    | 1        | 1.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 96       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 94       | 97.92%  |
| Yes  | 2        | 2.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 26       | 26.8%   |
| 8.01-16.0   | 25       | 25.77%  |
| 64.01-256.0 | 13       | 13.4%   |
| 32.01-64.0  | 10       | 10.31%  |
| 4.01-8.0    | 9        | 9.28%   |
| 0.01-0.5    | 5        | 5.15%   |
| 2.01-3.0    | 4        | 4.12%   |
| 3.01-4.0    | 2        | 2.06%   |
| 24.01-32.0  | 2        | 2.06%   |
| 0.51-1.0    | 1        | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 36       | 37.11%  |
| 0.51-1.0 | 30       | 30.93%  |
| 1.01-2.0 | 15       | 15.46%  |
| 0        | 6        | 6.19%   |
| 3.01-4.0 | 5        | 5.15%   |
| 2.01-3.0 | 5        | 5.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 27.84%  |
| 2      | 22       | 22.68%  |
| 3      | 15       | 15.46%  |
| 4      | 13       | 13.4%   |
| 0      | 10       | 10.31%  |
| 8      | 2        | 2.06%   |
| 6      | 2        | 2.06%   |
| 18     | 1        | 1.03%   |
| 15     | 1        | 1.03%   |
| 10     | 1        | 1.03%   |
| 9      | 1        | 1.03%   |
| 7      | 1        | 1.03%   |
| 5      | 1        | 1.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 71.88%  |
| Yes       | 27       | 28.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 86       | 89.58%  |
| No        | 10       | 10.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 66       | 68.04%  |
| Yes       | 31       | 31.96%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 74       | 77.08%  |
| Yes       | 22       | 22.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 26       | 27.08%  |
| Russia      | 15       | 15.63%  |
| Germany     | 13       | 13.54%  |
| Spain       | 5        | 5.21%   |
| France      | 5        | 5.21%   |
| Canada      | 5        | 5.21%   |
| Taiwan      | 2        | 2.08%   |
| New Zealand | 2        | 2.08%   |
| Netherlands | 2        | 2.08%   |
| Italy       | 2        | 2.08%   |
| Czechia     | 2        | 2.08%   |
| Belgium     | 2        | 2.08%   |
| Austria     | 2        | 2.08%   |
| Australia   | 2        | 2.08%   |
| Venezuela   | 1        | 1.04%   |
| Thailand    | 1        | 1.04%   |
| Sri Lanka   | 1        | 1.04%   |
| Serbia      | 1        | 1.04%   |
| Romania     | 1        | 1.04%   |
| Mexico      | 1        | 1.04%   |
| Japan       | 1        | 1.04%   |
| Ireland     | 1        | 1.04%   |
| India       | 1        | 1.04%   |
| Hungary     | 1        | 1.04%   |
| Croatia     | 1        | 1.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Moscow                  | 6        | 6.19%   |
| Frisco                  | 4        | 4.12%   |
| Ozersk                  | 3        | 3.09%   |
| Wellington              | 2        | 2.06%   |
| Tamm                    | 2        | 2.06%   |
| Taipei                  | 2        | 2.06%   |
| Redmond                 | 2        | 2.06%   |
| Omaha                   | 2        | 2.06%   |
| Madrid                  | 2        | 2.06%   |
| Los Angeles             | 2        | 2.06%   |
| Brno                    | 2        | 2.06%   |
| Zagreb                  | 1        | 1.03%   |
| Yashio                  | 1        | 1.03%   |
| Wenatchee               | 1        | 1.03%   |
| Waldbrunn               | 1        | 1.03%   |
| Vienna                  | 1        | 1.03%   |
| Vaulx-en-Velin          | 1        | 1.03%   |
| Vancouver               | 1        | 1.03%   |
| Valladolid              | 1        | 1.03%   |
| Tucson                  | 1        | 1.03%   |
| Toronto                 | 1        | 1.03%   |
| Tiel                    | 1        | 1.03%   |
| Sydney                  | 1        | 1.03%   |
| St. Albert              | 1        | 1.03%   |
| St Petersburg           | 1        | 1.03%   |
| Springfield             | 1        | 1.03%   |
| Sherbrooke              | 1        | 1.03%   |
| Saratov                 | 1        | 1.03%   |
| Sarasota                | 1        | 1.03%   |
| Sant Cugat del Vallès  | 1        | 1.03%   |
| San Vincenzo La Costa   | 1        | 1.03%   |
| Saarbrücken            | 1        | 1.03%   |
| Rostov-on-Don           | 1        | 1.03%   |
| Remseck am Neckar       | 1        | 1.03%   |
| Poperinge               | 1        | 1.03%   |
| Pluvigner               | 1        | 1.03%   |
| Paris                   | 1        | 1.03%   |
| Palo Alto               | 1        | 1.03%   |
| Newport                 | 1        | 1.03%   |
| Neustadt am Ruebenberge | 1        | 1.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 39       | 71     | 25.32%  |
| Seagate             | 26       | 67     | 16.88%  |
| Samsung Electronics | 22       | 37     | 14.29%  |
| Kingston            | 10       | 10     | 6.49%   |
| Crucial             | 10       | 17     | 6.49%   |
| Toshiba             | 7        | 14     | 4.55%   |
| Intel               | 5        | 7      | 3.25%   |
| PNY                 | 3        | 4      | 1.95%   |
| Verbatim            | 2        | 2      | 1.3%    |
| SanDisk             | 2        | 2      | 1.3%    |
| Hitachi             | 2        | 2      | 1.3%    |
| Hewlett-Packard     | 2        | 2      | 1.3%    |
| A-DATA Technology   | 2        | 2      | 1.3%    |
| Transcend           | 1        | 1      | 0.65%   |
| Team                | 1        | 1      | 0.65%   |
| T-FORCE             | 1        | 1      | 0.65%   |
| SPCC                | 1        | 1      | 0.65%   |
| SK hynix            | 1        | 1      | 0.65%   |
| Phison              | 1        | 1      | 0.65%   |
| Patriot             | 1        | 1      | 0.65%   |
| OWC                 | 1        | 3      | 0.65%   |
| ORICO               | 1        | 1      | 0.65%   |
| OCZ                 | 1        | 1      | 0.65%   |
| Netac               | 1        | 1      | 0.65%   |
| MSI                 | 1        | 2      | 0.65%   |
| Micron Technology   | 1        | 2      | 0.65%   |
| LITEONIT            | 1        | 1      | 0.65%   |
| LITEON              | 1        | 1      | 0.65%   |
| HPT                 | 1        | 8      | 0.65%   |
| Hikvision           | 1        | 1      | 0.65%   |
| HGST                | 1        | 1      | 0.65%   |
| Gigabyte Technology | 1        | 1      | 0.65%   |
| FORESEE             | 1        | 1      | 0.65%   |
| Corsair             | 1        | 1      | 0.65%   |
| China               | 1        | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB        | 4        | 2.01%   |
| WDC WD30EFRX-68EUZN0 3TB        | 3        | 1.51%   |
| WDC WD30EFRX-68AX9N0 3TB        | 3        | 1.51%   |
| Seagate ST1000DM010-2EP102 1TB  | 3        | 1.51%   |
| Samsung SSD 850 EVO 500GB       | 3        | 1.51%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 1.51%   |
| WDC WD5000LPLX-00ZNTT0 500GB    | 2        | 1.01%   |
| Verbatim Vi550 S3 SSD 256GB     | 2        | 1.01%   |
| Seagate ST4000NM0035-1V4107 4TB | 2        | 1.01%   |
| Seagate ST4000DM000-1F2168 4TB  | 2        | 1.01%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 1.01%   |
| Samsung SSD 970 EVO 1TB         | 2        | 1.01%   |
| Samsung SSD 870 QVO 2TB         | 2        | 1.01%   |
| Samsung SSD 850 EVO 250GB       | 2        | 1.01%   |
| Samsung SSD 840 EVO 120GB       | 2        | 1.01%   |
| PNY 120GB SATA SSD              | 2        | 1.01%   |
| Kingston SA400S37960G 960GB     | 2        | 1.01%   |
| Kingston SA400S37120G 120GB     | 2        | 1.01%   |
| Intel SSDSC2CT060A3 64GB        | 2        | 1.01%   |
| Crucial CT500P2SSD8 500GB       | 2        | 1.01%   |
| A-DATA SU650 240GB              | 2        | 1.01%   |
| WDC WDS500G2B0A-00SM50 500GB    | 1        | 0.5%    |
| WDC WDS500G1B0A-00H9H0 500GB    | 1        | 0.5%    |
| WDC WDS100T2B0A-00SM50 1TB      | 1        | 0.5%    |
| WDC WDBA3V5000ANC-WRSN 500GB    | 1        | 0.5%    |
| WDC WD80EZZX-11CSGA0 8TB        | 1        | 0.5%    |
| WDC WD80EZAZ-11TDBA0 8TB        | 1        | 0.5%    |
| WDC WD80EMZZ-00TBGA0 8TB        | 1        | 0.5%    |
| WDC WD80EFBX-68AZZN0 8TB        | 1        | 0.5%    |
| WDC WD800AAJS-00PSA0 80GB       | 1        | 0.5%    |
| WDC WD8003FFBX-68B9AN0 8TB      | 1        | 0.5%    |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 0.5%    |
| WDC WD60EFRX-68L0BN1 6TB        | 1        | 0.5%    |
| WDC WD5000LUCT-63Y8HY0 500GB    | 1        | 0.5%    |
| WDC WD5000BEVT-22ZAT0 500GB     | 1        | 0.5%    |
| WDC WD40EZRZ-22GXCB0 4TB        | 1        | 0.5%    |
| WDC WD40EZRZ-00GXCB0 4TB        | 1        | 0.5%    |
| WDC WD4003FRYZ-01F0DB0 4TB      | 1        | 0.5%    |
| WDC WD30EFRX-68N32N0 3TB        | 1        | 0.5%    |
| WDC WD20NMVW-11EDZS2 2TB        | 1        | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 32       | 63     | 46.38%  |
| Seagate             | 25       | 66     | 36.23%  |
| Toshiba             | 6        | 13     | 8.7%    |
| Hitachi             | 2        | 2      | 2.9%    |
| Samsung Electronics | 1        | 4      | 1.45%   |
| HPT                 | 1        | 8      | 1.45%   |
| HGST                | 1        | 1      | 1.45%   |
| Hewlett-Packard     | 1        | 1      | 1.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 16       | 24     | 25.4%   |
| Crucial             | 9        | 12     | 14.29%  |
| Kingston            | 6        | 6      | 9.52%   |
| Intel               | 4        | 6      | 6.35%   |
| WDC                 | 3        | 3      | 4.76%   |
| PNY                 | 3        | 4      | 4.76%   |
| Verbatim            | 2        | 2      | 3.17%   |
| SanDisk             | 2        | 2      | 3.17%   |
| A-DATA Technology   | 2        | 2      | 3.17%   |
| Transcend           | 1        | 1      | 1.59%   |
| Toshiba             | 1        | 1      | 1.59%   |
| Team                | 1        | 1      | 1.59%   |
| SPCC                | 1        | 1      | 1.59%   |
| SK hynix            | 1        | 1      | 1.59%   |
| Patriot             | 1        | 1      | 1.59%   |
| OWC                 | 1        | 3      | 1.59%   |
| ORICO               | 1        | 1      | 1.59%   |
| OCZ                 | 1        | 1      | 1.59%   |
| MSI                 | 1        | 2      | 1.59%   |
| Micron Technology   | 1        | 2      | 1.59%   |
| LITEONIT            | 1        | 1      | 1.59%   |
| LITEON              | 1        | 1      | 1.59%   |
| Hikvision           | 1        | 1      | 1.59%   |
| FORESEE             | 1        | 1      | 1.59%   |
| China               | 1        | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 54       | 81     | 40.91%  |
| HDD  | 54       | 158    | 40.91%  |
| NVMe | 24       | 31     | 18.18%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 81       | 239    | 77.14%  |
| NVMe | 24       | 31     | 22.86%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 51       | 77     | 41.46%  |
| 0.51-1.0   | 38       | 56     | 30.89%  |
| 1.01-2.0   | 14       | 33     | 11.38%  |
| 3.01-4.0   | 8        | 13     | 6.5%    |
| 2.01-3.0   | 5        | 20     | 4.07%   |
| 4.01-10.0  | 4        | 29     | 3.25%   |
| 10.01-20.0 | 3        | 11     | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 25       | 25.51%  |
| 251-500        | 20       | 20.41%  |
| 501-1000       | 18       | 18.37%  |
| 21-50          | 12       | 12.24%  |
| 51-100         | 8        | 8.16%   |
| 1001-2000      | 4        | 4.08%   |
| 1-20           | 4        | 4.08%   |
| More than 3000 | 3        | 3.06%   |
| 2001-3000      | 3        | 3.06%   |
| Unknown        | 1        | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 80       | 83.33%  |
| 21-50          | 7        | 7.29%   |
| 51-100         | 3        | 3.13%   |
| More than 3000 | 2        | 2.08%   |
| 251-500        | 2        | 2.08%   |
| 501-1000       | 1        | 1.04%   |
| Unknown        | 1        | 1.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| WDC WD6400AAKS-22A7B2 640GB                | 1        | 1      | 5.88%   |
| WDC WD5000LPLX-00ZNTT0 500GB               | 1        | 1      | 5.88%   |
| WDC WD30EFRX-68EUZN0 3TB                   | 1        | 3      | 5.88%   |
| WDC WD1600AAJS-60M0A0 160GB                | 1        | 1      | 5.88%   |
| WDC WD10EZRZ-00HTKB0 1TB                   | 1        | 2      | 5.88%   |
| SPCC M.2 SSD 256GB                         | 1        | 1      | 5.88%   |
| SK hynix SC308 SATA 128GB                  | 1        | 1      | 5.88%   |
| Seagate ST9500325AS 500GB                  | 1        | 1      | 5.88%   |
| Seagate ST500DM002-1ER14C 500GB            | 1        | 1      | 5.88%   |
| Seagate ST1000DM003-1CH162 1TB             | 1        | 1      | 5.88%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB | 1        | 2      | 5.88%   |
| LITEON IT LST-16S9G-HP 16GB                | 1        | 1      | 5.88%   |
| Kingston SV300S37A120G 120GB               | 1        | 1      | 5.88%   |
| Hitachi HTS727575A9E364 752GB              | 1        | 1      | 5.88%   |
| Hitachi HDS721010CLA332 1TB                | 1        | 1      | 5.88%   |
| HGST HTS725050A7E630 500GB                 | 1        | 1      | 5.88%   |
| Hewlett-Packard MB1000GCWCV 1TB            | 1        | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 5        | 8      | 29.41%  |
| Seagate           | 3        | 3      | 17.65%  |
| Hitachi           | 2        | 2      | 11.76%  |
| SPCC              | 1        | 1      | 5.88%   |
| SK hynix          | 1        | 1      | 5.88%   |
| Micron Technology | 1        | 2      | 5.88%   |
| LITEON            | 1        | 1      | 5.88%   |
| Kingston          | 1        | 1      | 5.88%   |
| HGST              | 1        | 1      | 5.88%   |
| Hewlett-Packard   | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 5        | 8      | 41.67%  |
| Seagate         | 3        | 3      | 25%     |
| Hitachi         | 2        | 2      | 16.67%  |
| HGST            | 1        | 1      | 8.33%   |
| Hewlett-Packard | 1        | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 12       | 15     | 70.59%  |
| SSD  | 5        | 6      | 29.41%  |

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

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 81       | 234    | 81%     |
| Malfunc  | 15       | 21     | 15%     |
| Detected | 4        | 15     | 4%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 67       | 51.54%  |
| AMD                         | 19       | 14.62%  |
| Samsung Electronics         | 8        | 6.15%   |
| SanDisk                     | 6        | 4.62%   |
| ASMedia Technology          | 5        | 3.85%   |
| Phison Electronics          | 4        | 3.08%   |
| Marvell Technology Group    | 4        | 3.08%   |
| Kingston Technology Company | 4        | 3.08%   |
| Micron/Crucial Technology   | 3        | 2.31%   |
| Broadcom / LSI              | 3        | 2.31%   |
| Silicon Motion              | 2        | 1.54%   |
| Silicon Image               | 1        | 0.77%   |
| Seagate Technology          | 1        | 0.77%   |
| Nvidia                      | 1        | 0.77%   |
| JMicron Technology          | 1        | 0.77%   |
| HighPoint Technologies      | 1        | 0.77%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10       | 6.85%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 10       | 6.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 4.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6        | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 3.42%   |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 3.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 2.74%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 4        | 2.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4        | 2.74%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 2.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 2.05%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3        | 2.05%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3        | 2.05%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 3        | 2.05%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 2.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 2.05%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2        | 1.37%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2        | 1.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.37%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 1.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 1.37%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.37%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2        | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.37%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                          | 2        | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2        | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2        | 1.37%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 1.37%   |
| Silicon Image SiI 3124 PCI-X Serial ATA Controller                             | 1        | 0.68%   |
| Seagate BarraCuda Q5 NVMe SSD (DRAM-less)                                      | 1        | 0.68%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1        | 0.68%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 1        | 0.68%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                          | 1        | 0.68%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1        | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.68%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1        | 0.68%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 1        | 0.68%   |
| Phison E8 PCIe3 NVMe Controller                                                | 1        | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.68%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 79       | 62.7%   |
| NVMe | 26       | 20.63%  |
| IDE  | 13       | 10.32%  |
| RAID | 4        | 3.17%   |
| SAS  | 4        | 3.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 66       | 68.75%  |
| AMD    | 22       | 22.92%  |
| ARM    | 8        | 8.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| ARM ARM1176 r0p7 (ECO: 0x00000000)     | 4        | 4.12%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 3        | 3.09%   |
| ARM Cortex-A53 r0p4                    | 3        | 3.09%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 3        | 3.09%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2        | 2.06%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 2        | 2.06%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 2        | 2.06%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 2        | 2.06%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 2        | 2.06%   |
| Intel Xeon E-2136 CPU @ 3.30GHz        | 1        | 1.03%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz    | 1        | 1.03%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz       | 1        | 1.03%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz    | 1        | 1.03%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GH      | 1        | 1.03%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz    | 1        | 1.03%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GH      | 1        | 1.03%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz    | 1        | 1.03%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz    | 1        | 1.03%   |
| Intel Xeon CPU                         | 1        | 1.03%   |
| Intel Pentium II                       | 1        | 1.03%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz | 1        | 1.03%   |
| Intel Pentium CPU G3240T @ 2.70GHz     | 1        | 1.03%   |
| Intel Pentium CPU G3220 @ 3.00GHz      | 1        | 1.03%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 1        | 1.03%   |
| Intel Core i7-6900K CPU @ 3.20GHz      | 1        | 1.03%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 1.03%   |
| Intel Core i7-4785T CPU @ 2.20GHz      | 1        | 1.03%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 1.03%   |
| Intel Core i7-10700K CPU @ 3.80GHz     | 1        | 1.03%   |
| Intel Core i5-9400T CPU @ 1.80GHz      | 1        | 1.03%   |
| Intel Core i5-9400F CPU @ 2.90GHz      | 1        | 1.03%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 1        | 1.03%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 1        | 1.03%   |
| Intel Core i5-6500T CPU @ 2.50GHz      | 1        | 1.03%   |
| Intel Core i5-5250U CPU @ 1.60GHz      | 1        | 1.03%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 1        | 1.03%   |
| Intel Core i5-4670K CPU @ 3.40GHz      | 1        | 1.03%   |
| Intel Core i5-4670 CPU @ 3.40GHz       | 1        | 1.03%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 1.03%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 1        | 1.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 24       | 25%     |
| Intel Xeon             | 10       | 10.42%  |
| Intel Core i7          | 10       | 10.42%  |
| Other                  | 8        | 8.33%   |
| Intel Core i3          | 5        | 5.21%   |
| AMD Ryzen 5            | 5        | 5.21%   |
| ARM Cortex             | 4        | 4.17%   |
| AMD Ryzen 9            | 4        | 4.17%   |
| Intel Pentium          | 3        | 3.13%   |
| Intel Celeron          | 3        | 3.13%   |
| Intel Atom             | 3        | 3.13%   |
| AMD Ryzen 7            | 3        | 3.13%   |
| Intel Core 2 Duo       | 2        | 2.08%   |
| Intel Pentium Gold     | 1        | 1.04%   |
| Intel Core 2 Quad      | 1        | 1.04%   |
| AMD Ryzen Threadripper | 1        | 1.04%   |
| AMD Ryzen 7 PRO        | 1        | 1.04%   |
| AMD Ryzen 3            | 1        | 1.04%   |
| AMD Phenom II X2       | 1        | 1.04%   |
| AMD GX                 | 1        | 1.04%   |
| AMD FX                 | 1        | 1.04%   |
| AMD EPYC               | 1        | 1.04%   |
| AMD E2                 | 1        | 1.04%   |
| AMD Athlon 64 X2       | 1        | 1.04%   |
| AMD A10                | 1        | 1.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 35       | 36.46%  |
| 2       | 16       | 16.67%  |
| 6       | 11       | 11.46%  |
| Unknown | 9        | 9.38%   |
| 8       | 7        | 7.29%   |
| 16      | 5        | 5.21%   |
| 12      | 5        | 5.21%   |
| 64      | 2        | 2.08%   |
| 32      | 2        | 2.08%   |
| 24      | 2        | 2.08%   |
| 28      | 1        | 1.04%   |
| 1       | 1        | 1.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 86       | 89.58%  |
| Unknown | 8        | 8.33%   |
| 2       | 2        | 2.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 55       | 57.29%  |
| 2       | 31       | 32.29%  |
| Unknown | 10       | 10.42%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 13       | 13.4%   |
| Unknown       | 13       | 13.4%   |
| KabyLake      | 12       | 12.37%  |
| Zen 3         | 7        | 7.22%   |
| SandyBridge   | 7        | 7.22%   |
| IvyBridge     | 7        | 7.22%   |
| Skylake       | 5        | 5.15%   |
| CometLake     | 5        | 5.15%   |
| Zen 2         | 4        | 4.12%   |
| Broadwell     | 3        | 3.09%   |
| Zen+          | 2        | 2.06%   |
| Westmere      | 2        | 2.06%   |
| Silvermont    | 2        | 2.06%   |
| Piledriver    | 2        | 2.06%   |
| Penryn        | 2        | 2.06%   |
| Bonnell       | 2        | 2.06%   |
| Zen           | 1        | 1.03%   |
| TigerLake     | 1        | 1.03%   |
| Puma          | 1        | 1.03%   |
| P6            | 1        | 1.03%   |
| K8 Hammer     | 1        | 1.03%   |
| K10           | 1        | 1.03%   |
| Jaguar        | 1        | 1.03%   |
| Goldmont plus | 1        | 1.03%   |
| Core          | 1        | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 39       | 42.86%  |
| Nvidia                               | 26       | 28.57%  |
| AMD                                  | 21       | 23.08%  |
| Matrox Electronics Systems           | 2        | 2.2%    |
| ASPEED Technology                    | 2        | 2.2%    |
| NVidia / SGS Thomson (Joint Venture) | 1        | 1.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 9.57%   |
| Intel HD Graphics 530                                                       | 4        | 4.26%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 3.19%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 3.19%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 3.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.19%   |
| Intel HD Graphics 630                                                       | 3        | 3.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 3.19%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.19%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 2.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.13%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 2.13%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 2.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.13%   |
| ASPEED Technology ASPEED Graphics Family                                    | 2        | 2.13%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 2        | 2.13%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 2        | 2.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.13%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                               | 2        | 2.13%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.06%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.06%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.06%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.06%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.06%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 1.06%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.06%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.06%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.06%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 1.06%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.06%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.06%   |
| NVidia / SGS Thomson (Joint Venture) Riva128                                | 1        | 1.06%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 1        | 1.06%   |
| Matrox Electronics Systems MGA G200EH                                       | 1        | 1.06%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 1        | 1.06%   |
| Intel HD Graphics 6000                                                      | 1        | 1.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.06%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.06%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Intel                                | 35       | 36.46%  |
| 1 x Nvidia                               | 21       | 21.88%  |
| 1 x AMD                                  | 20       | 20.83%  |
| Other                                    | 10       | 10.42%  |
| Intel + Nvidia                           | 4        | 4.17%   |
| 1 x Matrox                               | 2        | 2.08%   |
| 1 x ASPEED                               | 2        | 2.08%   |
| 2 x AMD                                  | 1        | 1.04%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 1.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 65       | 67.01%  |
| Proprietary | 21       | 21.65%  |
| Unknown     | 11       | 11.34%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 69.79%  |
| 1.01-2.0   | 10       | 10.42%  |
| 0.51-1.0   | 7        | 7.29%   |
| 3.01-4.0   | 5        | 5.21%   |
| 7.01-8.0   | 3        | 3.13%   |
| 5.01-6.0   | 2        | 2.08%   |
| 2.01-3.0   | 1        | 1.04%   |
| 0.01-0.5   | 1        | 1.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 9        | 18.37%  |
| Dell                 | 6        | 12.24%  |
| Acer                 | 5        | 10.2%   |
| Goldstar             | 4        | 8.16%   |
| Philips              | 2        | 4.08%   |
| LG Electronics       | 2        | 4.08%   |
| Lenovo               | 2        | 4.08%   |
| BenQ                 | 2        | 4.08%   |
| AOC                  | 2        | 4.08%   |
| Ancor Communications | 2        | 4.08%   |
| ViewSonic            | 1        | 2.04%   |
| Vestel Elektronik    | 1        | 2.04%   |
| Toshiba              | 1        | 2.04%   |
| Sceptre Tech         | 1        | 2.04%   |
| Pioneer Electronic   | 1        | 2.04%   |
| Panasonic            | 1        | 2.04%   |
| Mi                   | 1        | 2.04%   |
| IOD                  | 1        | 2.04%   |
| Iiyama               | 1        | 2.04%   |
| Idek Iiyama          | 1        | 2.04%   |
| Compal               | 1        | 2.04%   |
| Chimei Innolux       | 1        | 2.04%   |
| ASUSTek Computer     | 1        | 2.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 2        | 3.85%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch          | 1        | 1.92%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1        | 1.92%   |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1        | 1.92%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1        | 1.92%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 1        | 1.92%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1        | 1.92%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                      | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 1.92%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 1.92%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1        | 1.92%   |
| Pioneer Electronic LCD Monitor SC-1223 1920x1080                       | 1        | 1.92%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 1.92%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 1.92%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 1        | 1.92%   |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                       | 1        | 1.92%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1        | 1.92%   |
| LG Electronics LCD Monitor 23MP55 1920x1080                            | 1        | 1.92%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch               | 1        | 1.92%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1        | 1.92%   |
| IOD KH270V IOD1B3B 1920x1080 600x340mm 27.2-inch                       | 1        | 1.92%   |
| Iiyama PL2483H IVM6138 1920x1080 530x300mm 24.0-inch                   | 1        | 1.92%   |
| Idek Iiyama LCD Monitor PL2730Q 2560x1440                              | 1        | 1.92%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                   | 1        | 1.92%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1        | 1.92%   |
| Goldstar LG ULTRAGEAR GSM776E 2560x1440 700x390mm 31.5-inch            | 1        | 1.92%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch           | 1        | 1.92%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                  | 1        | 1.92%   |
| Dell UP2716D DEL40DD 2560x1440 600x340mm 27.2-inch                     | 1        | 1.92%   |
| Dell U3417W DELA0E0 3440x1440 800x330mm 34.1-inch                      | 1        | 1.92%   |
| Dell LCD Monitor SP2309W 2048x1152                                     | 1        | 1.92%   |
| Dell LCD Monitor P2217H 1920x1080                                      | 1        | 1.92%   |
| Dell IN2020M DELF030 1600x900 440x250mm 19.9-inch                      | 1        | 1.92%   |
| Dell E151FPp DEL7006 1024x768 300x230mm 14.9-inch                      | 1        | 1.92%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch               | 1        | 1.92%   |
| Chimei Innolux LCD Monitor CMN14A8 1920x1080 310x170mm 13.9-inch       | 1        | 1.92%   |
| BenQ LCD Monitor PD3200Q                                               | 1        | 1.92%   |
| BenQ LCD Monitor GW2765                                                | 1        | 1.92%   |
| BenQ G900HD BNQ7816 1366x768 410x230mm 18.5-inch                       | 1        | 1.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 24       | 50%     |
| 2560x1440 (QHD)    | 5        | 10.42%  |
| 1920x1200 (WUXGA)  | 4        | 8.33%   |
| 1280x1024 (SXGA)   | 3        | 6.25%   |
| 3840x2160 (4K)     | 2        | 4.17%   |
| 1680x1050 (WSXGA+) | 2        | 4.17%   |
| 3440x1440          | 1        | 2.08%   |
| 2560x1080          | 1        | 2.08%   |
| 2048x1152          | 1        | 2.08%   |
| 1920x540           | 1        | 2.08%   |
| 1600x900 (HD+)     | 1        | 2.08%   |
| 1366x768 (WXGA)    | 1        | 2.08%   |
| 1024x768 (XGA)     | 1        | 2.08%   |
| Unknown            | 1        | 2.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 26%     |
| 27      | 8        | 16%     |
| 24      | 8        | 16%     |
| 21      | 6        | 12%     |
| 20      | 2        | 4%      |
| 19      | 2        | 4%      |
| 57      | 1        | 2%      |
| 54      | 1        | 2%      |
| 42      | 1        | 2%      |
| 34      | 1        | 2%      |
| 31      | 1        | 2%      |
| 29      | 1        | 2%      |
| 23      | 1        | 2%      |
| 22      | 1        | 2%      |
| 18      | 1        | 2%      |
| 14      | 1        | 2%      |
| 13      | 1        | 2%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 32%     |
| Unknown     | 13       | 26%     |
| 401-500     | 10       | 20%     |
| 601-700     | 3        | 6%      |
| 351-400     | 2        | 4%      |
| 1001-1500   | 2        | 4%      |
| 701-800     | 1        | 2%      |
| 301-350     | 1        | 2%      |
| 201-300     | 1        | 2%      |
| 901-1000    | 1        | 2%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 25       | 53.19%  |
| Unknown | 13       | 27.66%  |
| 16/10   | 4        | 8.51%   |
| 21/9    | 2        | 4.26%   |
| 6/5     | 1        | 2.13%   |
| 5/4     | 1        | 2.13%   |
| 4/3     | 1        | 2.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 28%     |
| Unknown        | 13       | 26%     |
| 301-350        | 9        | 18%     |
| 151-200        | 4        | 8%      |
| More than 1000 | 2        | 4%      |
| 351-500        | 2        | 4%      |
| 251-300        | 2        | 4%      |
| 81-90          | 1        | 2%      |
| 141-150        | 1        | 2%      |
| 101-110        | 1        | 2%      |
| 501-1000       | 1        | 2%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 23       | 46.94%  |
| Unknown | 13       | 26.53%  |
| 101-120 | 10       | 20.41%  |
| 121-160 | 2        | 4.08%   |
| 1-50    | 1        | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 47       | 48.96%  |
| 1     | 44       | 45.83%  |
| 2     | 4        | 4.17%   |
| 3     | 1        | 1.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 52       | 42.62%  |
| Realtek Semiconductor           | 49       | 40.16%  |
| Qualcomm Atheros                | 6        | 4.92%   |
| Broadcom                        | 4        | 3.28%   |
| TP-Link                         | 2        | 1.64%   |
| Xiaomi                          | 1        | 0.82%   |
| Ralink Technology               | 1        | 0.82%   |
| Qualcomm Atheros Communications | 1        | 0.82%   |
| Mellanox Technologies           | 1        | 0.82%   |
| Marvell Technology Group        | 1        | 0.82%   |
| LG Electronics                  | 1        | 0.82%   |
| IMC Networks                    | 1        | 0.82%   |
| D-Link System                   | 1        | 0.82%   |
| American Megatrends             | 1        | 0.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 37       | 24.67%  |
| Intel I211 Gigabit Network Connection                                         | 10       | 6.67%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 4%      |
| Realtek RTL8125 2.5GbE Controller                                             | 5        | 3.33%   |
| Intel Wi-Fi 6 AX200                                                           | 5        | 3.33%   |
| Intel Ethernet Controller I225-V                                              | 5        | 3.33%   |
| Intel Ethernet Connection (2) I219-V                                          | 5        | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 3.33%   |
| Intel Ethernet Controller X550                                                | 3        | 2%      |
| Intel Ethernet Connection I217-LM                                             | 3        | 2%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 1.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 1.33%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 1.33%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 2        | 1.33%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 2        | 1.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.67%   |
| TP-Link Wireless MU-MIMO USB Adapter                                          | 1        | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 0.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.67%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 0.67%   |
| Realtek Bluetooth Adapter                                                     | 1        | 0.67%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                  | 1        | 0.67%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 0.67%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.67%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.67%   |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.67%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 0.67%   |
| LG Optimus Android Phone [USB tethering mode]                                 | 1        | 0.67%   |
| Intel Wireless-AC 9260                                                        | 1        | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 14       | 40%     |
| Realtek Semiconductor           | 7        | 20%     |
| Qualcomm Atheros                | 6        | 17.14%  |
| Broadcom                        | 3        | 8.57%   |
| TP-Link                         | 2        | 5.71%   |
| Ralink Technology               | 1        | 2.86%   |
| Qualcomm Atheros Communications | 1        | 2.86%   |
| IMC Networks                    | 1        | 2.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 5        | 14.29%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 5.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 5.71%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                  | 2        | 5.71%   |
| TP-Link Wireless MU-MIMO USB Adapter                                          | 1        | 2.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.86%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.86%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 2.86%   |
| Realtek Bluetooth Adapter                                                     | 1        | 2.86%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                  | 1        | 2.86%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 2.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 2.86%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 2.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 2.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 2.86%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 2.86%   |
| Intel Wireless-AC 9260                                                        | 1        | 2.86%   |
| Intel Wireless 7260                                                           | 1        | 2.86%   |
| Intel Wi-Fi 6 AX201                                                           | 1        | 2.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 1        | 2.86%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1        | 2.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 2.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1        | 2.86%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 1        | 2.86%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                  | 1        | 2.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 50       | 50.51%  |
| Realtek Semiconductor    | 44       | 44.44%  |
| Xiaomi                   | 1        | 1.01%   |
| Marvell Technology Group | 1        | 1.01%   |
| D-Link System            | 1        | 1.01%   |
| Broadcom                 | 1        | 1.01%   |
| American Megatrends      | 1        | 1.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37       | 33.33%  |
| Intel I211 Gigabit Network Connection                             | 10       | 9.01%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 5.41%   |
| Intel Ethernet Controller I225-V                                  | 5        | 4.5%    |
| Intel Ethernet Connection (2) I219-V                              | 5        | 4.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 4.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.7%    |
| Intel Ethernet Controller X550                                    | 3        | 2.7%    |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.8%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.8%    |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.8%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 1.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.9%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.9%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.9%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.9%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.9%    |
| Intel I350 Gigabit Network Connection                             | 1        | 0.9%    |
| Intel I210 Gigabit Network Connection                             | 1        | 0.9%    |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.9%    |
| Intel Ethernet Connection I217-V                                  | 1        | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.9%    |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.9%    |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.9%    |
| Intel Ethernet Connection (13) I219-V                             | 1        | 0.9%    |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.9%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.9%    |
| Intel 82599 Ethernet Controller Virtual Function                  | 1        | 0.9%    |
| Intel 82599 10 Gigabit Network Connection                         | 1        | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.9%    |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.9%    |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.9%    |
| Intel 82575GB Gigabit Network Connection                          | 1        | 0.9%    |
| Intel 82575EB Gigabit Network Connection                          | 1        | 0.9%    |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 0.9%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.9%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 0.9%    |
| American Megatrends Virtual Ethernet                              | 1        | 0.9%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 87       | 70.73%  |
| WiFi     | 32       | 26.02%  |
| Unknown  | 3        | 2.44%   |
| Modem    | 1        | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 84       | 94.38%  |
| WiFi     | 5        | 5.62%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 44.79%  |
| 2     | 26       | 27.08%  |
| 3     | 13       | 13.54%  |
| 0     | 8        | 8.33%   |
| 5     | 3        | 3.13%   |
| 4     | 2        | 2.08%   |
| 7     | 1        | 1.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 77       | 80.21%  |
| Yes  | 19       | 19.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 12       | 54.55%  |
| Qualcomm Atheros Communications | 3        | 13.64%  |
| ASUSTek Computer                | 3        | 13.64%  |
| Realtek Semiconductor           | 2        | 9.09%   |
| Cambridge Silicon Radio         | 2        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 4        | 18.18%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3        | 13.64%  |
| Intel AX201 Bluetooth                                       | 2        | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2        | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 4.55%   |
| Realtek Bluetooth Adapter                                   | 1        | 4.55%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 4.55%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 4.55%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1        | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1        | 4.55%   |
| Intel Bluetooth wireless interface                          | 1        | 4.55%   |
| Intel AX210 Bluetooth                                       | 1        | 4.55%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 1        | 4.55%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 1        | 4.55%   |
| ASUS Bluetooth USB module                                   | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 54       | 45%     |
| AMD                         | 28       | 23.33%  |
| Nvidia                      | 26       | 21.67%  |
| XMOS                        | 1        | 0.83%   |
| Samson Technologies         | 1        | 0.83%   |
| Realtek Semiconductor       | 1        | 0.83%   |
| Razer USA                   | 1        | 0.83%   |
| Micro Star International    | 1        | 0.83%   |
| Kingston Technology         | 1        | 0.83%   |
| Focusrite-Novation          | 1        | 0.83%   |
| FiiO Electronics Technology | 1        | 0.83%   |
| Ensoniq                     | 1        | 0.83%   |
| Creative Labs               | 1        | 0.83%   |
| Cambridge Silicon Radio     | 1        | 0.83%   |
| ASUSTek Computer            | 1        | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 5.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 8        | 5.59%   |
| AMD Starship/Matisse HD Audio Controller                                          | 8        | 5.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6        | 4.2%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 2.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4        | 2.8%    |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 2.8%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4        | 2.8%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 4        | 2.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 2.8%    |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 2.8%    |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 2.1%    |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 2.1%    |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 2.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3        | 2.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 2.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 1.4%    |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 1.4%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 1.4%    |
| Intel Smart Sound Technology (SST) Audio Controller                               | 2        | 1.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 1.4%    |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 1.4%    |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 1.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 1.4%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 1.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 1.4%    |
| Intel 200 Series PCH HD Audio                                                     | 2        | 1.4%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2        | 1.4%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 2        | 1.4%    |
| AMD Navi 10 HDMI Audio                                                            | 2        | 1.4%    |
| AMD FCH Azalia Controller                                                         | 2        | 1.4%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.4%    |
| XMOS XS1-U8 MFA (ST)                                                              | 1        | 0.7%    |
| Samson Technologies GoMic compact condenser mic                                   | 1        | 0.7%    |
| Realtek Semiconductor USB Audio                                                   | 1        | 0.7%    |
| Razer USA BlackShark V2 Pro                                                       | 1        | 0.7%    |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.7%    |
| Nvidia High Definition Audio Controller                                           | 1        | 0.7%    |
| Nvidia GK106 HDMI Audio Controller                                                | 1        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Samsung Electronics          | 13       | 13.68%  |
| Corsair                      | 13       | 13.68%  |
| Crucial                      | 10       | 10.53%  |
| SK hynix                     | 9        | 9.47%   |
| Kingston                     | 9        | 9.47%   |
| Micron Technology            | 8        | 8.42%   |
| G.Skill                      | 8        | 8.42%   |
| Unknown                      | 6        | 6.32%   |
| Patriot Memory (PDP Systems) | 2        | 2.11%   |
| Patriot                      | 2        | 2.11%   |
| GOODRAM                      | 2        | 2.11%   |
| A-DATA Technology            | 2        | 2.11%   |
| Unknown (ABCD)               | 1        | 1.05%   |
| Unknown (8A5D)               | 1        | 1.05%   |
| Transcend                    | 1        | 1.05%   |
| Team                         | 1        | 1.05%   |
| Ramaxel Technology           | 1        | 1.05%   |
| Qimonda                      | 1        | 1.05%   |
| Nanya Technology             | 1        | 1.05%   |
| Kingmax                      | 1        | 1.05%   |
| Hewlett-Packard              | 1        | 1.05%   |
| AMD                          | 1        | 1.05%   |
| Unknown                      | 1        | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 2        | 2%      |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                   | 2        | 2%      |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1        | 1%      |
| Unknown RAM Module 4GB DIMM 1600MT/s                                    | 1        | 1%      |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                                 | 1        | 1%      |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 1        | 1%      |
| Unknown RAM Module 2GB DIMM                                             | 1        | 1%      |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s       | 1        | 1%      |
| Unknown (8A5D) RAM SKIHOTAR-8GB-2666 8GB SODIMM DDR4 2133MT/s           | 1        | 1%      |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1066MT/s                     | 1        | 1%      |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s                      | 1        | 1%      |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s                    | 1        | 1%      |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                    | 1        | 1%      |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                  | 1        | 1%      |
| SK hynix RAM HMT42GR7CMR4A-G7 16GB DIMM DDR3 1067MT/s                   | 1        | 1%      |
| SK hynix RAM HMT425U6AFR6A-PB 2GB DIMM DDR3 1600MT/s                    | 1        | 1%      |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s                    | 1        | 1%      |
| SK hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s                    | 1        | 1%      |
| SK hynix RAM HMA82GU7MFR8N-TF 16GB DIMM DDR4 2133MT/s                   | 1        | 1%      |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s                    | 1        | 1%      |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                    | 1        | 1%      |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 1%      |
| Samsung RAM Module 2GB DIMM DDR3 1334MT/s                               | 1        | 1%      |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s                   | 1        | 1%      |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s                     | 1        | 1%      |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1333MT/s                         | 1        | 1%      |
| Samsung RAM M393B2G70DB0 16GB DIMM DDR3 1333MT/s                        | 1        | 1%      |
| Samsung RAM M393A2G40EB1-CPB 16GB DIMM DDR4 2133MT/s                    | 1        | 1%      |
| Samsung RAM M391B5273DH0-YH9 4GB DIMM DDR3 1333MT/s                     | 1        | 1%      |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s                    | 1        | 1%      |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s                     | 1        | 1%      |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s                     | 1        | 1%      |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 2667MT/s                     | 1        | 1%      |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s                     | 1        | 1%      |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s                   | 1        | 1%      |
| Qimonda RAM 64T128000EU2.5C2 1GB DIMM DDR2 800MT/s                      | 1        | 1%      |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                          | 1        | 1%      |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1333MT/s                         | 1        | 1%      |
| Patriot RAM 1866 CL9 Series 4GB DIMM DDR3 1600MT/s                      | 1        | 1%      |
| Patriot Memory (PDP Systems) RAM 3733 C17 Series 8GB DIMM DDR4 2133MT/s | 1        | 1%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 42       | 48.28%  |
| DDR3    | 35       | 40.23%  |
| Unknown | 4        | 4.6%    |
| DDR2    | 3        | 3.45%   |
| LPDDR4  | 1        | 1.15%   |
| DDR5    | 1        | 1.15%   |
| DDR     | 1        | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 76       | 88.37%  |
| SODIMM | 10       | 11.63%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 41       | 42.71%  |
| 4096  | 25       | 26.04%  |
| 16384 | 15       | 15.63%  |
| 2048  | 10       | 10.42%  |
| 32768 | 4        | 4.17%   |
| 1024  | 1        | 1.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 24       | 26.97%  |
| 3200    | 12       | 13.48%  |
| 2133    | 11       | 12.36%  |
| 2400    | 10       | 11.24%  |
| 1333    | 10       | 11.24%  |
| 3600    | 4        | 4.49%   |
| 2667    | 4        | 4.49%   |
| 800     | 3        | 3.37%   |
| 3000    | 2        | 2.25%   |
| 1334    | 2        | 2.25%   |
| 4800    | 1        | 1.12%   |
| 3400    | 1        | 1.12%   |
| 1067    | 1        | 1.12%   |
| 1066    | 1        | 1.12%   |
| 933     | 1        | 1.12%   |
| 533     | 1        | 1.12%   |
| Unknown | 1        | 1.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| HP LaserJet 1012 | 1        | 100%    |

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
| Canon CanoScan LiDE 220 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Trust                     | 1        | 20%     |
| SHENZHEN EMEET TECHNOLOGY | 1        | 20%     |
| OmniVision Technologies   | 1        | 20%     |
| Microdia                  | 1        | 20%     |
| Logitech                  | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Trust Trust QHD Webcam                         | 1        | 20%     |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1        | 20%     |
| OmniVision Monitor Webcam                      | 1        | 20%     |
| Microdia JOYACCESS JA-Webcam                   | 1        | 20%     |
| Logitech Webcam C270                           | 1        | 20%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

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
| 1     | 40       | 41.67%  |
| 0     | 31       | 32.29%  |
| 2     | 18       | 18.75%  |
| 3     | 6        | 6.25%   |
| 6     | 1        | 1.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 58       | 62.37%  |
| Bluetooth                | 13       | 13.98%  |
| Net/wireless             | 9        | 9.68%   |
| Firewire controller      | 5        | 5.38%   |
| Net/ethernet             | 3        | 3.23%   |
| Network                  | 2        | 2.15%   |
| Card reader              | 2        | 2.15%   |
| Fingerprint reader       | 1        | 1.08%   |

