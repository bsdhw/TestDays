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

Total: 111

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 83       | 92.22%  |
| arm64 | 3        | 3.33%   |
| arm   | 3        | 3.33%   |
| i386  | 1        | 1.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Console   | 39       | 43.33%  |
| XFCE      | 15       | 16.67%  |
| KDE5      | 13       | 14.44%  |
| TWM       | 5        | 5.56%   |
| MATE      | 4        | 4.44%   |
| Openbox   | 3        | 3.33%   |
| i3        | 2        | 2.22%   |
| GNOME     | 2        | 2.22%   |
| plasma    | 1        | 1.11%   |
| LXQt      | 1        | 1.11%   |
| LXDE      | 1        | 1.11%   |
| Compton   | 1        | 1.11%   |
| Cinnamon  | 1        | 1.11%   |
| bspwm     | 1        | 1.11%   |
| AwesomeWM | 1        | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 48       | 53.33%  |
| Console | 41       | 45.56%  |
| Tty     | 1        | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 56       | 62.22%  |
| SDDM    | 13       | 14.44%  |
| LightDM | 7        | 7.78%   |
| SLiM    | 6        | 6.67%   |
| XDM     | 5        | 5.56%   |
| Ly      | 2        | 2.22%   |
| GDM     | 1        | 1.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 61       | 67.78%  |
| en_US   | 10       | 11.11%  |
| ru_RU   | 7        | 7.78%   |
| Unknown | 6        | 6.67%   |
| fr_FR   | 3        | 3.33%   |
| ja_JP   | 1        | 1.11%   |
| en_GB   | 1        | 1.11%   |
| de_DE   | 1        | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 60       | 65.93%  |
| BIOS | 31       | 34.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 59       | 65.56%  |
| Ufs  | 31       | 34.44%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 83       | 92.22%  |
| MBR  | 7        | 7.78%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 18       | 20%     |
| Gigabyte Technology | 11       | 12.22%  |
| Dell                | 10       | 11.11%  |
| Hewlett-Packard     | 8        | 8.89%   |
| ASRock              | 8        | 8.89%   |
| MSI                 | 6        | 6.67%   |
| Unknown             | 6        | 6.67%   |
| Intel               | 4        | 4.44%   |
| Acer                | 4        | 4.44%   |
| Fujitsu             | 2        | 2.22%   |
| Supermicro          | 1        | 1.11%   |
| Seeed Studio        | 1        | 1.11%   |
| PC Engines          | 1        | 1.11%   |
| NITRINOnet          | 1        | 1.11%   |
| NF-M2S              | 1        | 1.11%   |
| MouseComputer       | 1        | 1.11%   |
| Lenovo              | 1        | 1.11%   |
| Huanan              | 1        | 1.11%   |
| GVC                 | 1        | 1.11%   |
| Google              | 1        | 1.11%   |
| Foxconn             | 1        | 1.11%   |
| ASRockRack          | 1        | 1.11%   |
| AMI                 | 1        | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 6        | 6.67%   |
| ASUS All Series                    | 4        | 4.44%   |
| MSI MS-7817                        | 2        | 2.22%   |
| Dell Precision T3600               | 2        | 2.22%   |
| Supermicro Icebreaker 4824         | 1        | 1.11%   |
| Seeed Studio ODYSSEY-X86J4105      | 1        | 1.11%   |
| PC Engines APU3                    | 1        | 1.11%   |
| NITRINOnet M360RUS56               | 1        | 1.11%   |
| NF-M2S ABIT                        | 1        | 1.11%   |
| MSI MS-7D09                        | 1        | 1.11%   |
| MSI MS-7D08                        | 1        | 1.11%   |
| MSI MS-7C91                        | 1        | 1.11%   |
| MSI MS-7B86                        | 1        | 1.11%   |
| MouseComputer B360M                | 1        | 1.11%   |
| Lenovo H515 10125                  | 1        | 1.11%   |
| Intel X79 V2.72A                   | 1        | 1.11%   |
| Intel Q3XXG4-P V1.0                | 1        | 1.11%   |
| Intel DN2820FYK H24582-203         | 1        | 1.11%   |
| Intel D945GCLF2 AAE46416-104       | 1        | 1.11%   |
| Huanan X99-F8D V2.4                | 1        | 1.11%   |
| HP Z620 Workstation                | 1        | 1.11%   |
| HP ProLiant ML310e Gen8 v2         | 1        | 1.11%   |
| HP ProDesk 600 G1 DM               | 1        | 1.11%   |
| HP EliteDesk 800 G1 TWR            | 1        | 1.11%   |
| HP EliteDesk 800 G1 DM             | 1        | 1.11%   |
| HP Desktop M01-F0xxx               | 1        | 1.11%   |
| HP Compaq Pro 6300 MT              | 1        | 1.11%   |
| HP Compaq dc7900 Small Form Factor | 1        | 1.11%   |
| GVC EQUIUM 3200M                   | 1        | 1.11%   |
| Google Zako                        | 1        | 1.11%   |
| Gigabyte Z370M D3H                 | 1        | 1.11%   |
| Gigabyte X470 AORUS GAMING 7 WIFI  | 1        | 1.11%   |
| Gigabyte P85-D3                    | 1        | 1.11%   |
| Gigabyte H97M-HD3                  | 1        | 1.11%   |
| Gigabyte H61MA-D3V                 | 1        | 1.11%   |
| Gigabyte H61M-S2V-B3               | 1        | 1.11%   |
| Gigabyte GB-BSi3-1115G4            | 1        | 1.11%   |
| Gigabyte F2A75M-D3H                | 1        | 1.11%   |
| Gigabyte B550M AORUS PRO-P         | 1        | 1.11%   |
| Gigabyte B450M DS3H                | 1        | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Dell OptiPlex                 | 6        | 6.67%   |
| Unknown                       | 6        | 6.67%   |
| ASUS All                      | 4        | 4.44%   |
| ASUS ROG                      | 3        | 3.33%   |
| ASUS PRIME                    | 3        | 3.33%   |
| MSI MS-7817                   | 2        | 2.22%   |
| HP EliteDesk                  | 2        | 2.22%   |
| HP Compaq                     | 2        | 2.22%   |
| Dell Precision                | 2        | 2.22%   |
| Acer Veriton                  | 2        | 2.22%   |
| Supermicro Icebreaker         | 1        | 1.11%   |
| Seeed Studio ODYSSEY-X86J4105 | 1        | 1.11%   |
| PC Engines APU3               | 1        | 1.11%   |
| NITRINOnet M360RUS56          | 1        | 1.11%   |
| NF-M2S ABIT                   | 1        | 1.11%   |
| MSI MS-7D09                   | 1        | 1.11%   |
| MSI MS-7D08                   | 1        | 1.11%   |
| MSI MS-7C91                   | 1        | 1.11%   |
| MSI MS-7B86                   | 1        | 1.11%   |
| MouseComputer B360M           | 1        | 1.11%   |
| Lenovo H515                   | 1        | 1.11%   |
| Intel X79                     | 1        | 1.11%   |
| Intel Q3XXG4-P                | 1        | 1.11%   |
| Intel DN2820FYK               | 1        | 1.11%   |
| Intel D945GCLF2               | 1        | 1.11%   |
| Huanan X99-F8D                | 1        | 1.11%   |
| HP Z620                       | 1        | 1.11%   |
| HP ProLiant                   | 1        | 1.11%   |
| HP ProDesk                    | 1        | 1.11%   |
| HP Desktop                    | 1        | 1.11%   |
| GVC EQUIUM                    | 1        | 1.11%   |
| Google Zako                   | 1        | 1.11%   |
| Gigabyte Z370M                | 1        | 1.11%   |
| Gigabyte X470                 | 1        | 1.11%   |
| Gigabyte P85-D3               | 1        | 1.11%   |
| Gigabyte H97M-HD3             | 1        | 1.11%   |
| Gigabyte H61MA-D3V            | 1        | 1.11%   |
| Gigabyte H61M-S2V-B3          | 1        | 1.11%   |
| Gigabyte GB-BSi3-1115G4       | 1        | 1.11%   |
| Gigabyte F2A75M-D3H           | 1        | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 13       | 14.44%  |
| 2021    | 10       | 11.11%  |
| 2014    | 9        | 10%     |
| 2018    | 8        | 8.89%   |
| 2019    | 7        | 7.78%   |
| 2013    | 7        | 7.78%   |
| Unknown | 7        | 7.78%   |
| 2022    | 6        | 6.67%   |
| 2016    | 5        | 5.56%   |
| 2012    | 5        | 5.56%   |
| 2008    | 4        | 4.44%   |
| 2017    | 3        | 3.33%   |
| 2011    | 3        | 3.33%   |
| 2010    | 2        | 2.22%   |
| 2015    | 1        | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 90       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 88       | 97.78%  |
| Yes  | 2        | 2.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 24       | 26.37%  |
| 8.01-16.0   | 24       | 26.37%  |
| 64.01-256.0 | 12       | 13.19%  |
| 32.01-64.0  | 10       | 10.99%  |
| 4.01-8.0    | 9        | 9.89%   |
| 2.01-3.0    | 4        | 4.4%    |
| 0.01-0.5    | 3        | 3.3%    |
| 3.01-4.0    | 2        | 2.2%    |
| 24.01-32.0  | 2        | 2.2%    |
| 0.51-1.0    | 1        | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 35       | 38.46%  |
| 0.51-1.0 | 28       | 30.77%  |
| 1.01-2.0 | 14       | 15.38%  |
| 3.01-4.0 | 5        | 5.49%   |
| 2.01-3.0 | 5        | 5.49%   |
| 0        | 4        | 4.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 27       | 29.67%  |
| 2      | 21       | 23.08%  |
| 3      | 13       | 14.29%  |
| 4      | 12       | 13.19%  |
| 0      | 8        | 8.79%   |
| 8      | 2        | 2.2%    |
| 6      | 2        | 2.2%    |
| 18     | 1        | 1.1%    |
| 15     | 1        | 1.1%    |
| 10     | 1        | 1.1%    |
| 9      | 1        | 1.1%    |
| 7      | 1        | 1.1%    |
| 5      | 1        | 1.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 64       | 71.11%  |
| Yes       | 26       | 28.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 83       | 92.22%  |
| No        | 7        | 7.78%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 60       | 66.67%  |
| Yes       | 30       | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 69       | 76.67%  |
| Yes       | 21       | 23.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 24       | 26.67%  |
| Russia      | 15       | 16.67%  |
| Germany     | 11       | 12.22%  |
| Spain       | 5        | 5.56%   |
| France      | 5        | 5.56%   |
| Canada      | 5        | 5.56%   |
| New Zealand | 2        | 2.22%   |
| Netherlands | 2        | 2.22%   |
| Czechia     | 2        | 2.22%   |
| Belgium     | 2        | 2.22%   |
| Austria     | 2        | 2.22%   |
| Australia   | 2        | 2.22%   |
| Venezuela   | 1        | 1.11%   |
| Thailand    | 1        | 1.11%   |
| Taiwan      | 1        | 1.11%   |
| Sri Lanka   | 1        | 1.11%   |
| Serbia      | 1        | 1.11%   |
| Romania     | 1        | 1.11%   |
| Mexico      | 1        | 1.11%   |
| Japan       | 1        | 1.11%   |
| Italy       | 1        | 1.11%   |
| Ireland     | 1        | 1.11%   |
| India       | 1        | 1.11%   |
| Hungary     | 1        | 1.11%   |
| Croatia     | 1        | 1.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Moscow                  | 6        | 6.59%   |
| Frisco                  | 4        | 4.4%    |
| Ozersk                  | 3        | 3.3%    |
| Wellington              | 2        | 2.2%    |
| Tamm                    | 2        | 2.2%    |
| Redmond                 | 2        | 2.2%    |
| Omaha                   | 2        | 2.2%    |
| Madrid                  | 2        | 2.2%    |
| Brno                    | 2        | 2.2%    |
| Zagreb                  | 1        | 1.1%    |
| Yashio                  | 1        | 1.1%    |
| Wenatchee               | 1        | 1.1%    |
| Waldbrunn               | 1        | 1.1%    |
| Vienna                  | 1        | 1.1%    |
| Vaulx-en-Velin          | 1        | 1.1%    |
| Vancouver               | 1        | 1.1%    |
| Valladolid              | 1        | 1.1%    |
| Tucson                  | 1        | 1.1%    |
| Toronto                 | 1        | 1.1%    |
| Tiel                    | 1        | 1.1%    |
| Taipei                  | 1        | 1.1%    |
| Sydney                  | 1        | 1.1%    |
| St. Albert              | 1        | 1.1%    |
| St Petersburg           | 1        | 1.1%    |
| Springfield             | 1        | 1.1%    |
| Sherbrooke              | 1        | 1.1%    |
| Saratov                 | 1        | 1.1%    |
| Sarasota                | 1        | 1.1%    |
| Sant Cugat del Vallès  | 1        | 1.1%    |
| San Vincenzo La Costa   | 1        | 1.1%    |
| Saarbrücken            | 1        | 1.1%    |
| Rostov-on-Don           | 1        | 1.1%    |
| Poperinge               | 1        | 1.1%    |
| Pluvigner               | 1        | 1.1%    |
| Paris                   | 1        | 1.1%    |
| Palo Alto               | 1        | 1.1%    |
| Newport                 | 1        | 1.1%    |
| Neustadt am Ruebenberge | 1        | 1.1%    |
| Navi Mumbai             | 1        | 1.1%    |
| Nakhodka                | 1        | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 38       | 69     | 26.03%  |
| Seagate             | 26       | 67     | 17.81%  |
| Samsung Electronics | 22       | 37     | 15.07%  |
| Crucial             | 9        | 15     | 6.16%   |
| Kingston            | 8        | 8      | 5.48%   |
| Toshiba             | 7        | 14     | 4.79%   |
| Intel               | 5        | 7      | 3.42%   |
| SanDisk             | 2        | 2      | 1.37%   |
| PNY                 | 2        | 3      | 1.37%   |
| Hitachi             | 2        | 2      | 1.37%   |
| Hewlett-Packard     | 2        | 2      | 1.37%   |
| A-DATA Technology   | 2        | 2      | 1.37%   |
| Verbatim            | 1        | 1      | 0.68%   |
| Transcend           | 1        | 1      | 0.68%   |
| Team                | 1        | 1      | 0.68%   |
| T-FORCE             | 1        | 1      | 0.68%   |
| SPCC                | 1        | 1      | 0.68%   |
| SK hynix            | 1        | 1      | 0.68%   |
| Patriot             | 1        | 1      | 0.68%   |
| ORICO               | 1        | 1      | 0.68%   |
| OCZ                 | 1        | 1      | 0.68%   |
| Netac               | 1        | 1      | 0.68%   |
| MSI                 | 1        | 1      | 0.68%   |
| Micron Technology   | 1        | 2      | 0.68%   |
| LITEONIT            | 1        | 1      | 0.68%   |
| LITEON              | 1        | 1      | 0.68%   |
| HPT                 | 1        | 8      | 0.68%   |
| Hikvision           | 1        | 1      | 0.68%   |
| HGST                | 1        | 1      | 0.68%   |
| Gigabyte Technology | 1        | 1      | 0.68%   |
| FORESEE             | 1        | 1      | 0.68%   |
| Corsair             | 1        | 1      | 0.68%   |
| China               | 1        | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB        | 4        | 2.13%   |
| WDC WD30EFRX-68EUZN0 3TB        | 3        | 1.6%    |
| WDC WD30EFRX-68AX9N0 3TB        | 3        | 1.6%    |
| Seagate ST1000DM010-2EP102 1TB  | 3        | 1.6%    |
| Samsung SSD 850 EVO 500GB       | 3        | 1.6%    |
| WDC WD5000LPLX-00ZNTT0 500GB    | 2        | 1.06%   |
| Seagate ST4000NM0035-1V4107 4TB | 2        | 1.06%   |
| Seagate ST4000DM000-1F2168 4TB  | 2        | 1.06%   |
| Seagate ST2000DM008-2FR102 2TB  | 2        | 1.06%   |
| Samsung SSD 970 EVO 1TB         | 2        | 1.06%   |
| Samsung SSD 870 QVO 2TB         | 2        | 1.06%   |
| Samsung SSD 850 EVO 250GB       | 2        | 1.06%   |
| Samsung SSD 840 EVO 120GB       | 2        | 1.06%   |
| Kingston SA400S37960G 960GB     | 2        | 1.06%   |
| Kingston SA400S37120G 120GB     | 2        | 1.06%   |
| Intel SSDSC2CT060A3 64GB        | 2        | 1.06%   |
| Crucial CT240BX500SSD1 240GB    | 2        | 1.06%   |
| A-DATA SU650 240GB              | 2        | 1.06%   |
| WDC WDS500G1B0A-00H9H0 500GB    | 1        | 0.53%   |
| WDC WDS100T2B0A-00SM50 1TB      | 1        | 0.53%   |
| WDC WDBA3V5000ANC-WRSN 500GB    | 1        | 0.53%   |
| WDC WD80EZZX-11CSGA0 8TB        | 1        | 0.53%   |
| WDC WD80EZAZ-11TDBA0 8TB        | 1        | 0.53%   |
| WDC WD80EMZZ-00TBGA0 8TB        | 1        | 0.53%   |
| WDC WD80EFBX-68AZZN0 8TB        | 1        | 0.53%   |
| WDC WD800AAJS-00PSA0 80GB       | 1        | 0.53%   |
| WDC WD8003FFBX-68B9AN0 8TB      | 1        | 0.53%   |
| WDC WD6400AAKS-22A7B2 640GB     | 1        | 0.53%   |
| WDC WD60EFRX-68L0BN1 6TB        | 1        | 0.53%   |
| WDC WD5000LUCT-63Y8HY0 500GB    | 1        | 0.53%   |
| WDC WD5000BEVT-22ZAT0 500GB     | 1        | 0.53%   |
| WDC WD40EZRZ-22GXCB0 4TB        | 1        | 0.53%   |
| WDC WD40EZRZ-00GXCB0 4TB        | 1        | 0.53%   |
| WDC WD4003FRYZ-01F0DB0 4TB      | 1        | 0.53%   |
| WDC WD30EFRX-68N32N0 3TB        | 1        | 0.53%   |
| WDC WD20NMVW-11EDZS2 2TB        | 1        | 0.53%   |
| WDC WD20NMVW-11AV3S2 2TB        | 1        | 0.53%   |
| WDC WD20EARX-00PASB0 2TB        | 1        | 0.53%   |
| WDC WD20EARS-00MVWB1 2TB        | 1        | 0.53%   |
| WDC WD2003FYYS-18W0B0 2TB       | 1        | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 32       | 62     | 46.38%  |
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
| Samsung Electronics | 16       | 24     | 28.07%  |
| Crucial             | 8        | 11     | 14.04%  |
| Kingston            | 5        | 5      | 8.77%   |
| Intel               | 4        | 6      | 7.02%   |
| WDC                 | 2        | 2      | 3.51%   |
| SanDisk             | 2        | 2      | 3.51%   |
| PNY                 | 2        | 3      | 3.51%   |
| A-DATA Technology   | 2        | 2      | 3.51%   |
| Verbatim            | 1        | 1      | 1.75%   |
| Transcend           | 1        | 1      | 1.75%   |
| Toshiba             | 1        | 1      | 1.75%   |
| Team                | 1        | 1      | 1.75%   |
| SPCC                | 1        | 1      | 1.75%   |
| SK hynix            | 1        | 1      | 1.75%   |
| Patriot             | 1        | 1      | 1.75%   |
| ORICO               | 1        | 1      | 1.75%   |
| OCZ                 | 1        | 1      | 1.75%   |
| MSI                 | 1        | 1      | 1.75%   |
| Micron Technology   | 1        | 2      | 1.75%   |
| LITEONIT            | 1        | 1      | 1.75%   |
| LITEON              | 1        | 1      | 1.75%   |
| Hikvision           | 1        | 1      | 1.75%   |
| FORESEE             | 1        | 1      | 1.75%   |
| China               | 1        | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 54       | 157    | 43.2%   |
| SSD  | 50       | 72     | 40%     |
| NVMe | 21       | 28     | 16.8%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 77       | 229    | 78.57%  |
| NVMe | 21       | 28     | 21.43%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 47       | 69     | 39.83%  |
| 0.51-1.0   | 38       | 55     | 32.2%   |
| 1.01-2.0   | 13       | 32     | 11.02%  |
| 3.01-4.0   | 8        | 13     | 6.78%   |
| 2.01-3.0   | 5        | 20     | 4.24%   |
| 4.01-10.0  | 4        | 29     | 3.39%   |
| 10.01-20.0 | 3        | 11     | 2.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 25       | 27.47%  |
| 251-500        | 17       | 18.68%  |
| 501-1000       | 17       | 18.68%  |
| 21-50          | 10       | 10.99%  |
| 51-100         | 8        | 8.79%   |
| 1001-2000      | 4        | 4.4%    |
| 1-20           | 4        | 4.4%    |
| 2001-3000      | 3        | 3.3%    |
| More than 3000 | 2        | 2.2%    |
| Unknown        | 1        | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 74       | 82.22%  |
| 21-50          | 7        | 7.78%   |
| 51-100         | 3        | 3.33%   |
| More than 3000 | 2        | 2.22%   |
| 251-500        | 2        | 2.22%   |
| 501-1000       | 1        | 1.11%   |
| Unknown        | 1        | 1.11%   |

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
| WDC WD10EZRZ-00HTKB0 1TB                   | 1        | 1      | 5.88%   |
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
| WDC               | 5        | 7      | 29.41%  |
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
| WDC             | 5        | 7      | 41.67%  |
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
| HDD  | 12       | 14     | 70.59%  |
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
| Works    | 77       | 222    | 80.21%  |
| Malfunc  | 15       | 20     | 15.63%  |
| Detected | 4        | 15     | 4.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 64       | 52.89%  |
| AMD                         | 17       | 14.05%  |
| Samsung Electronics         | 8        | 6.61%   |
| SanDisk                     | 6        | 4.96%   |
| Marvell Technology Group    | 4        | 3.31%   |
| ASMedia Technology          | 4        | 3.31%   |
| Phison Electronics          | 3        | 2.48%   |
| Kingston Technology Company | 3        | 2.48%   |
| Broadcom / LSI              | 3        | 2.48%   |
| Silicon Motion              | 2        | 1.65%   |
| Micron/Crucial Technology   | 2        | 1.65%   |
| Silicon Image               | 1        | 0.83%   |
| Seagate Technology          | 1        | 0.83%   |
| Nvidia                      | 1        | 0.83%   |
| JMicron Technology          | 1        | 0.83%   |
| HighPoint Technologies      | 1        | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10       | 7.35%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 8        | 5.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 5.15%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6        | 4.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5        | 3.68%   |
| AMD 500 Series Chipset SATA Controller                                         | 5        | 3.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 2.94%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 4        | 2.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4        | 2.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 2.21%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3        | 2.21%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3        | 2.21%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 3        | 2.21%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3        | 2.21%   |
| AMD 400 Series Chipset SATA Controller                                         | 3        | 2.21%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2        | 1.47%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 1.47%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2        | 1.47%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 1.47%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2        | 1.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 1.47%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 1.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 1.47%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                          | 2        | 1.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2        | 1.47%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2        | 1.47%   |
| Unknown                                                                        | 2        | 1.47%   |
| Silicon Image SiI 3124 PCI-X Serial ATA Controller                             | 1        | 0.74%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 1        | 0.74%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 0.74%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1        | 0.74%   |
| Sandisk NVMe Controller                                                        | 1        | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.74%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 0.74%   |
| Phison NVMe Storage Controller                                                 | 1        | 0.74%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 0.74%   |
| Phison E12 NVMe Controller                                                     | 1        | 0.74%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.74%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.74%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 75       | 63.56%  |
| NVMe | 23       | 19.49%  |
| IDE  | 12       | 10.17%  |
| RAID | 4        | 3.39%   |
| SAS  | 4        | 3.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 64       | 71.11%  |
| AMD    | 20       | 22.22%  |
| ARM    | 6        | 6.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz       | 3        | 3.3%    |
| ARM Cortex-A53 r0p4                    | 3        | 3.3%    |
| AMD Ryzen 5 5600G with Radeon Graphics | 3        | 3.3%    |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2        | 2.2%    |
| Intel Core i7-6700K CPU @ 4.00GHz      | 2        | 2.2%    |
| Intel Core i5-8400 CPU @ 2.80GHz       | 2        | 2.2%    |
| Intel Core i5-6500 CPU @ 3.20GHz       | 2        | 2.2%    |
| ARM ARM1176 r0p7 (ECO: 0x00000000)     | 2        | 2.2%    |
| AMD Ryzen 9 5950X 16-Core Processor    | 2        | 2.2%    |
| Intel Xeon E-2136 CPU @ 3.30GHz        | 1        | 1.1%    |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz    | 1        | 1.1%    |
| Intel Xeon CPU E5-2670 @ 2.60GHz       | 1        | 1.1%    |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz    | 1        | 1.1%    |
| Intel Xeon CPU E5-2650 0 @ 2.00GH      | 1        | 1.1%    |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz    | 1        | 1.1%    |
| Intel Xeon CPU E5-1620 0 @ 3.60GH      | 1        | 1.1%    |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz    | 1        | 1.1%    |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz    | 1        | 1.1%    |
| Intel Xeon CPU                         | 1        | 1.1%    |
| Intel Pentium II                       | 1        | 1.1%    |
| Intel Pentium Gold G5400 CPU @ 3.70GHz | 1        | 1.1%    |
| Intel Pentium CPU G3240T @ 2.70GHz     | 1        | 1.1%    |
| Intel Pentium CPU G3220 @ 3.00GHz      | 1        | 1.1%    |
| Intel Core i7-9700K CPU @ 3.60GHz      | 1        | 1.1%    |
| Intel Core i7-6900K CPU @ 3.20GHz      | 1        | 1.1%    |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 1.1%    |
| Intel Core i7-4785T CPU @ 2.20GHz      | 1        | 1.1%    |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 1.1%    |
| Intel Core i7-10700K CPU @ 3.80GHz     | 1        | 1.1%    |
| Intel Core i5-9400T CPU @ 1.80GHz      | 1        | 1.1%    |
| Intel Core i5-9400F CPU @ 2.90GHz      | 1        | 1.1%    |
| Intel Core i5-9400 CPU @ 2.90GHz       | 1        | 1.1%    |
| Intel Core i5-7500 CPU @ 3.40GHz       | 1        | 1.1%    |
| Intel Core i5-6500T CPU @ 2.50GHz      | 1        | 1.1%    |
| Intel Core i5-5250U CPU @ 1.60GHz      | 1        | 1.1%    |
| Intel Core i5-4690 CPU @ 3.50GHz       | 1        | 1.1%    |
| Intel Core i5-4670K CPU @ 3.40GHz      | 1        | 1.1%    |
| Intel Core i5-4670 CPU @ 3.40GHz       | 1        | 1.1%    |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 1.1%    |
| Intel Core i5-4570 CPU @ 3.20GHz       | 1        | 1.1%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i5          | 24       | 26.67%  |
| Intel Xeon             | 10       | 11.11%  |
| Intel Core i7          | 10       | 11.11%  |
| Other                  | 6        | 6.67%   |
| AMD Ryzen 5            | 5        | 5.56%   |
| Intel Core i3          | 4        | 4.44%   |
| ARM Cortex             | 4        | 4.44%   |
| AMD Ryzen 9            | 4        | 4.44%   |
| Intel Pentium          | 3        | 3.33%   |
| Intel Celeron          | 3        | 3.33%   |
| Intel Atom             | 3        | 3.33%   |
| AMD Ryzen 7            | 2        | 2.22%   |
| Intel Pentium Gold     | 1        | 1.11%   |
| Intel Core 2 Quad      | 1        | 1.11%   |
| Intel Core 2 Duo       | 1        | 1.11%   |
| AMD Ryzen Threadripper | 1        | 1.11%   |
| AMD Ryzen 7 PRO        | 1        | 1.11%   |
| AMD Ryzen 3            | 1        | 1.11%   |
| AMD Phenom II X2       | 1        | 1.11%   |
| AMD GX                 | 1        | 1.11%   |
| AMD FX                 | 1        | 1.11%   |
| AMD E2                 | 1        | 1.11%   |
| AMD Athlon 64 X2       | 1        | 1.11%   |
| AMD A10                | 1        | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 34       | 37.78%  |
| 2       | 15       | 16.67%  |
| 6       | 11       | 12.22%  |
| 8       | 7        | 7.78%   |
| Unknown | 7        | 7.78%   |
| 12      | 5        | 5.56%   |
| 16      | 4        | 4.44%   |
| 32      | 2        | 2.22%   |
| 24      | 2        | 2.22%   |
| 64      | 1        | 1.11%   |
| 28      | 1        | 1.11%   |
| 1       | 1        | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 82       | 91.11%  |
| Unknown | 6        | 6.67%   |
| 2       | 2        | 2.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 52       | 57.78%  |
| 2       | 30       | 33.33%  |
| Unknown | 8        | 8.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 13       | 14.29%  |
| KabyLake      | 12       | 13.19%  |
| Unknown       | 10       | 10.99%  |
| SandyBridge   | 7        | 7.69%   |
| IvyBridge     | 7        | 7.69%   |
| Zen 3         | 6        | 6.59%   |
| Skylake       | 5        | 5.49%   |
| Zen 2         | 4        | 4.4%    |
| CometLake     | 4        | 4.4%    |
| Broadwell     | 3        | 3.3%    |
| Zen+          | 2        | 2.2%    |
| Westmere      | 2        | 2.2%    |
| Silvermont    | 2        | 2.2%    |
| Piledriver    | 2        | 2.2%    |
| Bonnell       | 2        | 2.2%    |
| Zen           | 1        | 1.1%    |
| TigerLake     | 1        | 1.1%    |
| Puma          | 1        | 1.1%    |
| Penryn        | 1        | 1.1%    |
| P6            | 1        | 1.1%    |
| K8 Hammer     | 1        | 1.1%    |
| K10           | 1        | 1.1%    |
| Jaguar        | 1        | 1.1%    |
| Goldmont plus | 1        | 1.1%    |
| Core          | 1        | 1.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 39       | 44.83%  |
| Nvidia                               | 25       | 28.74%  |
| AMD                                  | 19       | 21.84%  |
| Matrox Electronics Systems           | 2        | 2.3%    |
| NVidia / SGS Thomson (Joint Venture) | 1        | 1.15%   |
| ASPEED Technology                    | 1        | 1.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 10%     |
| Intel HD Graphics 530                                                       | 4        | 4.44%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 3.33%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 3.33%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 3.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 3.33%   |
| Intel HD Graphics 630                                                       | 3        | 3.33%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 3.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 3.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 2.22%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.22%   |
| Nvidia GF108 [GeForce GT 430]                                               | 2        | 2.22%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 2        | 2.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 2.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 2.22%   |
| AMD Turks [Radeon HD 7600 Series]                                           | 2        | 2.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 2.22%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                               | 2        | 2.22%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.11%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.11%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.11%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.11%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 1.11%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.11%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.11%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 1.11%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.11%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1        | 1.11%   |
| NVidia / SGS Thomson (Joint Venture) Riva128                                | 1        | 1.11%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 1        | 1.11%   |
| Matrox Electronics Systems MGA G200EH                                       | 1        | 1.11%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 1        | 1.11%   |
| Intel HD Graphics 6000                                                      | 1        | 1.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 1.11%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 1.11%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.11%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.11%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 1        | 1.11%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 1.11%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Intel                                | 35       | 38.89%  |
| 1 x Nvidia                               | 20       | 22.22%  |
| 1 x AMD                                  | 18       | 20%     |
| Other                                    | 8        | 8.89%   |
| Intel + Nvidia                           | 4        | 4.44%   |
| 1 x Matrox                               | 2        | 2.22%   |
| 2 x AMD                                  | 1        | 1.11%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 1.11%   |
| 1 x ASPEED                               | 1        | 1.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 62       | 68.13%  |
| Proprietary | 20       | 21.98%  |
| Unknown     | 9        | 9.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 62       | 68.89%  |
| 1.01-2.0   | 9        | 10%     |
| 0.51-1.0   | 7        | 7.78%   |
| 3.01-4.0   | 5        | 5.56%   |
| 7.01-8.0   | 3        | 3.33%   |
| 5.01-6.0   | 2        | 2.22%   |
| 2.01-3.0   | 1        | 1.11%   |
| 0.01-0.5   | 1        | 1.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 9        | 18.75%  |
| Dell                 | 6        | 12.5%   |
| Acer                 | 5        | 10.42%  |
| Goldstar             | 4        | 8.33%   |
| Philips              | 2        | 4.17%   |
| LG Electronics       | 2        | 4.17%   |
| Lenovo               | 2        | 4.17%   |
| BenQ                 | 2        | 4.17%   |
| AOC                  | 2        | 4.17%   |
| Ancor Communications | 2        | 4.17%   |
| ViewSonic            | 1        | 2.08%   |
| Vestel Elektronik    | 1        | 2.08%   |
| Toshiba              | 1        | 2.08%   |
| Sceptre Tech         | 1        | 2.08%   |
| Panasonic            | 1        | 2.08%   |
| Mi                   | 1        | 2.08%   |
| IOD                  | 1        | 2.08%   |
| Iiyama               | 1        | 2.08%   |
| Idek Iiyama          | 1        | 2.08%   |
| Compal               | 1        | 2.08%   |
| Chimei Innolux       | 1        | 2.08%   |
| ASUSTek Computer     | 1        | 2.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 2        | 4%      |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1        | 2%      |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1        | 2%      |
| Toshiba TV TSB0200 1920x1080 530x300mm 24.0-inch                       | 1        | 2%      |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1        | 2%      |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 1        | 2%      |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1        | 2%      |
| Samsung Electronics LCD Monitor T27C370 1920x1080                      | 1        | 2%      |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1        | 2%      |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 2%      |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 2%      |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1        | 2%      |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 2%      |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 2%      |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 1        | 2%      |
| Mi 27 NFGL XMIB004 1920x1080 600x330mm 27.0-inch                       | 1        | 2%      |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1        | 2%      |
| LG Electronics LCD Monitor 23MP55 1920x1080                            | 1        | 2%      |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch               | 1        | 2%      |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1        | 2%      |
| IOD KH270V IOD1B3B 1920x1080 600x340mm 27.2-inch                       | 1        | 2%      |
| Iiyama PL2483H IVM6138 1920x1080 530x300mm 24.0-inch                   | 1        | 2%      |
| Idek Iiyama LCD Monitor PL2730Q 2560x1440                              | 1        | 2%      |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                   | 1        | 2%      |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 1        | 2%      |
| Goldstar LG ULTRAGEAR GSM776E 2560x1440 700x390mm 31.5-inch            | 1        | 2%      |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1        | 2%      |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                  | 1        | 2%      |
| Dell UP2716D DEL40DD 2560x1440 600x340mm 27.2-inch                     | 1        | 2%      |
| Dell U3417W DELA0E0 3440x1440 800x330mm 34.1-inch                      | 1        | 2%      |
| Dell LCD Monitor SP2309W 2048x1152                                     | 1        | 2%      |
| Dell LCD Monitor P2217H 1920x1080                                      | 1        | 2%      |
| Dell IN2020M DELF030 1600x900 440x250mm 19.9-inch                      | 1        | 2%      |
| Dell E151FPp DEL7006 1024x768 300x230mm 14.9-inch                      | 1        | 2%      |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch               | 1        | 2%      |
| Chimei Innolux LCD Monitor CMN14A8 1920x1080 310x170mm 13.9-inch       | 1        | 2%      |
| BenQ LCD Monitor PD3200Q                                               | 1        | 2%      |
| BenQ LCD Monitor GW2765                                                | 1        | 2%      |
| BenQ G900HD BNQ7816 1366x768 410x230mm 18.5-inch                       | 1        | 2%      |
| ASUSTek Computer PA248QV AUS2487 1920x1200 520x320mm 24.0-inch         | 1        | 2%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 23       | 48.94%  |
| 2560x1440 (QHD)    | 5        | 10.64%  |
| 1920x1200 (WUXGA)  | 4        | 8.51%   |
| 1280x1024 (SXGA)   | 3        | 6.38%   |
| 3840x2160 (4K)     | 2        | 4.26%   |
| 1680x1050 (WSXGA+) | 2        | 4.26%   |
| 3440x1440          | 1        | 2.13%   |
| 2560x1080          | 1        | 2.13%   |
| 2048x1152          | 1        | 2.13%   |
| 1920x540           | 1        | 2.13%   |
| 1600x900 (HD+)     | 1        | 2.13%   |
| 1366x768 (WXGA)    | 1        | 2.13%   |
| 1024x768 (XGA)     | 1        | 2.13%   |
| Unknown            | 1        | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 12       | 25%     |
| 27      | 8        | 16.67%  |
| 24      | 7        | 14.58%  |
| 21      | 6        | 12.5%   |
| 20      | 2        | 4.17%   |
| 19      | 2        | 4.17%   |
| 57      | 1        | 2.08%   |
| 54      | 1        | 2.08%   |
| 42      | 1        | 2.08%   |
| 34      | 1        | 2.08%   |
| 31      | 1        | 2.08%   |
| 29      | 1        | 2.08%   |
| 23      | 1        | 2.08%   |
| 22      | 1        | 2.08%   |
| 18      | 1        | 2.08%   |
| 14      | 1        | 2.08%   |
| 13      | 1        | 2.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 15       | 31.25%  |
| Unknown     | 12       | 25%     |
| 401-500     | 10       | 20.83%  |
| 601-700     | 3        | 6.25%   |
| 351-400     | 2        | 4.17%   |
| 1001-1500   | 2        | 4.17%   |
| 701-800     | 1        | 2.08%   |
| 301-350     | 1        | 2.08%   |
| 201-300     | 1        | 2.08%   |
| 901-1000    | 1        | 2.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 25       | 55.56%  |
| Unknown | 12       | 26.67%  |
| 16/10   | 3        | 6.67%   |
| 21/9    | 2        | 4.44%   |
| 6/5     | 1        | 2.22%   |
| 5/4     | 1        | 2.22%   |
| 4/3     | 1        | 2.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 14       | 29.17%  |
| Unknown        | 12       | 25%     |
| 301-350        | 9        | 18.75%  |
| 151-200        | 4        | 8.33%   |
| More than 1000 | 2        | 4.17%   |
| 351-500        | 2        | 4.17%   |
| 81-90          | 1        | 2.08%   |
| 251-300        | 1        | 2.08%   |
| 141-150        | 1        | 2.08%   |
| 101-110        | 1        | 2.08%   |
| 501-1000       | 1        | 2.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 22       | 46.81%  |
| Unknown | 12       | 25.53%  |
| 101-120 | 10       | 21.28%  |
| 121-160 | 2        | 4.26%   |
| 1-50    | 1        | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 47.78%  |
| 0     | 42       | 46.67%  |
| 2     | 4        | 4.44%   |
| 3     | 1        | 1.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 48       | 41.74%  |
| Realtek Semiconductor           | 47       | 40.87%  |
| Qualcomm Atheros                | 6        | 5.22%   |
| Broadcom                        | 4        | 3.48%   |
| TP-Link                         | 2        | 1.74%   |
| Xiaomi                          | 1        | 0.87%   |
| Ralink Technology               | 1        | 0.87%   |
| Qualcomm Atheros Communications | 1        | 0.87%   |
| Mellanox Technologies           | 1        | 0.87%   |
| Marvell Technology Group        | 1        | 0.87%   |
| LG Electronics                  | 1        | 0.87%   |
| IMC Networks                    | 1        | 0.87%   |
| D-Link System                   | 1        | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 36       | 25.35%  |
| Intel I211 Gigabit Network Connection                                         | 9        | 6.34%   |
| Intel 82574L Gigabit Network Connection                                       | 6        | 4.23%   |
| Intel Wi-Fi 6 AX200                                                           | 5        | 3.52%   |
| Intel Ethernet Controller I225-V                                              | 5        | 3.52%   |
| Intel Ethernet Connection (2) I219-V                                          | 5        | 3.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5        | 3.52%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4        | 2.82%   |
| Intel Ethernet Connection I217-LM                                             | 3        | 2.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 1.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 1.41%   |
| Intel Ethernet Controller X550                                                | 2        | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                                         | 2        | 1.41%   |
| Intel Ethernet Connection (2) I218-V                                          | 2        | 1.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 2        | 1.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 1        | 0.7%    |
| TP-Link Wireless MU-MIMO USB Adapter                                          | 1        | 0.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 0.7%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 0.7%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 0.7%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 0.7%    |
| Realtek Bluetooth Adapter                                                     | 1        | 0.7%    |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                  | 1        | 0.7%    |
| Ralink RT5572 Wireless Adapter                                                | 1        | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 0.7%    |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 0.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 0.7%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 0.7%    |
| Mellanox MT27500 Family [ConnectX-3]                                          | 1        | 0.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 1        | 0.7%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 1        | 0.7%    |
| LG Optimus Android Phone [USB tethering mode]                                 | 1        | 0.7%    |
| Intel Wireless-AC 9260                                                        | 1        | 0.7%    |
| Intel Wireless 7260                                                           | 1        | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 38.24%  |
| Realtek Semiconductor           | 7        | 20.59%  |
| Qualcomm Atheros                | 6        | 17.65%  |
| Broadcom                        | 3        | 8.82%   |
| TP-Link                         | 2        | 5.88%   |
| Ralink Technology               | 1        | 2.94%   |
| Qualcomm Atheros Communications | 1        | 2.94%   |
| IMC Networks                    | 1        | 2.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 5        | 14.71%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2        | 5.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 2        | 5.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                            | 2        | 5.88%   |
| TP-Link Wireless MU-MIMO USB Adapter                                          | 1        | 2.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1        | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.94%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.94%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                        | 1        | 2.94%   |
| Realtek Bluetooth Adapter                                                     | 1        | 2.94%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                  | 1        | 2.94%   |
| Ralink RT5572 Wireless Adapter                                                | 1        | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 2.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1        | 2.94%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1        | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 2.94%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1        | 2.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1        | 2.94%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 1        | 2.94%   |
| Intel Wireless-AC 9260                                                        | 1        | 2.94%   |
| Intel Wireless 7260                                                           | 1        | 2.94%   |
| Intel Wi-Fi 6 AX201                                                           | 1        | 2.94%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1        | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 1        | 2.94%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1        | 2.94%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card                          | 1        | 2.94%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                            | 1        | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 47       | 50%     |
| Realtek Semiconductor    | 43       | 45.74%  |
| Xiaomi                   | 1        | 1.06%   |
| Marvell Technology Group | 1        | 1.06%   |
| D-Link System            | 1        | 1.06%   |
| Broadcom                 | 1        | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36       | 34.29%  |
| Intel I211 Gigabit Network Connection                             | 9        | 8.57%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 5.71%   |
| Intel Ethernet Controller I225-V                                  | 5        | 4.76%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 4.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.86%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.9%    |
| Intel Ethernet Controller X550                                    | 2        | 1.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.9%    |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.95%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.95%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.95%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.95%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.95%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.95%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.95%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.95%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.95%   |
| Intel Ethernet Connection (17) I219-V                             | 1        | 0.95%   |
| Intel Ethernet Connection (13) I219-V                             | 1        | 0.95%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.95%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.95%   |
| Intel 82599 Ethernet Controller Virtual Function                  | 1        | 0.95%   |
| Intel 82599 10 Gigabit Network Connection                         | 1        | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.95%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.95%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.95%   |
| Intel 82575GB Gigabit Network Connection                          | 1        | 0.95%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 0.95%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 0.95%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.95%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.95%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 84       | 71.19%  |
| WiFi     | 31       | 26.27%  |
| Unknown  | 2        | 1.69%   |
| Modem    | 1        | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 80       | 95.24%  |
| WiFi     | 4        | 4.76%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 42       | 46.67%  |
| 2     | 25       | 27.78%  |
| 3     | 11       | 12.22%  |
| 0     | 6        | 6.67%   |
| 5     | 3        | 3.33%   |
| 4     | 2        | 2.22%   |
| 7     | 1        | 1.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 72       | 80%     |
| Yes  | 18       | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 11       | 52.38%  |
| Qualcomm Atheros Communications | 3        | 14.29%  |
| ASUSTek Computer                | 3        | 14.29%  |
| Realtek Semiconductor           | 2        | 9.52%   |
| Cambridge Silicon Radio         | 2        | 9.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 4        | 19.05%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3        | 14.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2        | 9.52%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 4.76%   |
| Realtek Bluetooth Adapter                                   | 1        | 4.76%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 4.76%   |
| Qualcomm Atheros AR9462 Bluetooth 3.0 + HS Adapter          | 1        | 4.76%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1        | 4.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1        | 4.76%   |
| Intel Bluetooth wireless interface                          | 1        | 4.76%   |
| Intel AX210 Bluetooth                                       | 1        | 4.76%   |
| Intel AX201 Bluetooth                                       | 1        | 4.76%   |
| ASUS Qualcomm Bluetooth 4.1                                 | 1        | 4.76%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE       | 1        | 4.76%   |
| ASUS Bluetooth USB module                                   | 1        | 4.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 52       | 45.61%  |
| AMD                         | 26       | 22.81%  |
| Nvidia                      | 25       | 21.93%  |
| XMOS                        | 1        | 0.88%   |
| Realtek Semiconductor       | 1        | 0.88%   |
| Razer USA                   | 1        | 0.88%   |
| Micro Star International    | 1        | 0.88%   |
| Kingston Technology         | 1        | 0.88%   |
| Focusrite-Novation          | 1        | 0.88%   |
| FiiO Electronics Technology | 1        | 0.88%   |
| Ensoniq                     | 1        | 0.88%   |
| Creative Labs               | 1        | 0.88%   |
| Cambridge Silicon Radio     | 1        | 0.88%   |
| ASUSTek Computer            | 1        | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 8        | 5.88%   |
| AMD Starship/Matisse HD Audio Controller                                          | 7        | 5.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6        | 4.41%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 2.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 4        | 2.94%   |
| Intel Cannon Lake PCH cAVS                                                        | 4        | 2.94%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4        | 2.94%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 4        | 2.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 2.94%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 2.94%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 2.21%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 2.21%   |
| Nvidia GF108 High Definition Audio Controller                                     | 3        | 2.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3        | 2.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3        | 2.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 2.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 2        | 1.47%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 1.47%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 1.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 1.47%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 1.47%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 2        | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 1.47%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 1.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 1.47%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2        | 1.47%   |
| AMD FCH Azalia Controller                                                         | 2        | 1.47%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 1.47%   |
| XMOS XS1-U8 MFA (ST)                                                              | 1        | 0.74%   |
| Realtek Semiconductor USB Audio                                                   | 1        | 0.74%   |
| Razer USA BlackShark V2 Pro                                                       | 1        | 0.74%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 0.74%   |
| Nvidia High Definition Audio Controller                                           | 1        | 0.74%   |
| Nvidia GK106 HDMI Audio Controller                                                | 1        | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                                     | 1        | 0.74%   |
| Micro Star International Realtek USB Audio                                        | 1        | 0.74%   |
| Kingston Technology HyperX 7.1 Audio                                              | 1        | 0.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Samsung Electronics          | 13       | 14.29%  |
| Corsair                      | 13       | 14.29%  |
| Crucial                      | 10       | 10.99%  |
| SK hynix                     | 8        | 8.79%   |
| Kingston                     | 8        | 8.79%   |
| G.Skill                      | 8        | 8.79%   |
| Micron Technology            | 7        | 7.69%   |
| Unknown                      | 6        | 6.59%   |
| Patriot                      | 2        | 2.2%    |
| GOODRAM                      | 2        | 2.2%    |
| A-DATA Technology            | 2        | 2.2%    |
| Unknown (ABCD)               | 1        | 1.1%    |
| Unknown (8A5D)               | 1        | 1.1%    |
| Transcend                    | 1        | 1.1%    |
| Team                         | 1        | 1.1%    |
| Ramaxel Technology           | 1        | 1.1%    |
| Qimonda                      | 1        | 1.1%    |
| Patriot Memory (PDP Systems) | 1        | 1.1%    |
| Nanya Technology             | 1        | 1.1%    |
| Kingmax                      | 1        | 1.1%    |
| Hewlett-Packard              | 1        | 1.1%    |
| AMD                          | 1        | 1.1%    |
| Unknown                      | 1        | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 2        | 2.08%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                   | 2        | 2.08%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1        | 1.04%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                    | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                                 | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 1        | 1.04%   |
| Unknown RAM Module 2GB DIMM                                             | 1        | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s          | 1        | 1.04%   |
| Unknown (8A5D) RAM SKIHOTAR-8GB-2666 8GB SODIMM DDR4 2133MT/s           | 1        | 1.04%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1066MT/s                     | 1        | 1.04%   |
| Team RAM TEAMGROUP-UD4-3600 32GB DIMM DDR4 3600MT/s                     | 1        | 1.04%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s                    | 1        | 1.04%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                    | 1        | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                  | 1        | 1.04%   |
| SK hynix RAM HMT42GR7CMR4A-G7 16GB DIMM DDR3 1067MT/s                   | 1        | 1.04%   |
| SK hynix RAM HMT425U6AFR6A-PB 2GB DIMM DDR3 1600MT/s                    | 1        | 1.04%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s                    | 1        | 1.04%   |
| SK hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s                    | 1        | 1.04%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s                    | 1        | 1.04%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                    | 1        | 1.04%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 1.04%   |
| Samsung RAM Module 2GB DIMM DDR3 1334MT/s                               | 1        | 1.04%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s                   | 1        | 1.04%   |
| Samsung RAM M393B5273DH0-CK0 4GB DIMM DDR3 1600MT/s                     | 1        | 1.04%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1333MT/s                         | 1        | 1.04%   |
| Samsung RAM M393B2G70DB0 16GB DIMM DDR3 1333MT/s                        | 1        | 1.04%   |
| Samsung RAM M393A2G40EB1-CPB 16GB DIMM DDR4 2133MT/s                    | 1        | 1.04%   |
| Samsung RAM M391B5273DH0-YH9 4GB DIMM DDR3 1333MT/s                     | 1        | 1.04%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s                    | 1        | 1.04%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s                     | 1        | 1.04%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s                     | 1        | 1.04%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 2667MT/s                     | 1        | 1.04%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s                     | 1        | 1.04%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s                   | 1        | 1.04%   |
| Qimonda RAM 64T128000EU2.5C2 1GB DIMM DDR2 800MT/s                      | 1        | 1.04%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                          | 1        | 1.04%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1333MT/s                         | 1        | 1.04%   |
| Patriot RAM 1866 CL9 Series 4GB DIMM DDR3 1600MT/s                      | 1        | 1.04%   |
| Patriot Memory (PDP Systems) RAM 3733 C17 Series 8GB DIMM DDR4 2133MT/s | 1        | 1.04%   |
| Nanya RAM Module 2GB DIMM DDR3 1334MT/s                                 | 1        | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 40       | 48.19%  |
| DDR3    | 35       | 42.17%  |
| Unknown | 4        | 4.82%   |
| DDR2    | 2        | 2.41%   |
| LPDDR4  | 1        | 1.2%    |
| DDR     | 1        | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 72       | 87.8%   |
| SODIMM | 10       | 12.2%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 40       | 43.48%  |
| 4096  | 25       | 27.17%  |
| 16384 | 13       | 14.13%  |
| 2048  | 9        | 9.78%   |
| 32768 | 4        | 4.35%   |
| 1024  | 1        | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 23       | 27.06%  |
| 3200    | 11       | 12.94%  |
| 1333    | 11       | 12.94%  |
| 2400    | 10       | 11.76%  |
| 2133    | 9        | 10.59%  |
| 3600    | 4        | 4.71%   |
| 2667    | 4        | 4.71%   |
| 3000    | 2        | 2.35%   |
| 1334    | 2        | 2.35%   |
| 800     | 2        | 2.35%   |
| 3400    | 1        | 1.18%   |
| 2666    | 1        | 1.18%   |
| 1067    | 1        | 1.18%   |
| 1066    | 1        | 1.18%   |
| 933     | 1        | 1.18%   |
| 533     | 1        | 1.18%   |
| Unknown | 1        | 1.18%   |

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
| SHENZHEN EMEET TECHNOLOGY | 1        | 25%     |
| OmniVision Technologies   | 1        | 25%     |
| Microdia                  | 1        | 25%     |
| Logitech                  | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1        | 25%     |
| OmniVision Monitor Webcam                      | 1        | 25%     |
| Microdia JOYACCESS JA-Webcam                   | 1        | 25%     |
| Logitech Webcam C270                           | 1        | 25%     |

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
| 1     | 40       | 44.44%  |
| 0     | 28       | 31.11%  |
| 2     | 16       | 17.78%  |
| 3     | 5        | 5.56%   |
| 6     | 1        | 1.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 55       | 63.95%  |
| Bluetooth                | 12       | 13.95%  |
| Net/wireless             | 9        | 10.47%  |
| Firewire controller      | 4        | 4.65%   |
| Net/ethernet             | 2        | 2.33%   |
| Card reader              | 2        | 2.33%   |
| Network                  | 1        | 1.16%   |
| Fingerprint reader       | 1        | 1.16%   |

