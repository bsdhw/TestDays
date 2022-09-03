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

Total: 100

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Intel         | X79 V2.72A                  | [435901d8c9](https://bsd-hardware.info/?probe=435901d8c9) | Aug 29, 2022 |
| ASRock        | AD2550-ITX                  | [43d0101ac4](https://bsd-hardware.info/?probe=43d0101ac4) | Aug 24, 2022 |
| Dell          | 042P49 A00                  | [7130975fe3](https://bsd-hardware.info/?probe=7130975fe3) | Aug 17, 2022 |
| MSI           | H81M-P33                    | [3d0836d403](https://bsd-hardware.info/?probe=3d0836d403) | Aug 14, 2022 |
| ASUSTek       | P5Q-E                       | [c50be0ecae](https://bsd-hardware.info/?probe=c50be0ecae) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4b6ad32189](https://bsd-hardware.info/?probe=4b6ad32189) | Aug 14, 2022 |
| ASRock        | H110M-DGS R3.0              | [0c654b6c34](https://bsd-hardware.info/?probe=0c654b6c34) | Aug 11, 2022 |
| Dell          | 042P49 A00                  | [a38375fa97](https://bsd-hardware.info/?probe=a38375fa97) | Aug 08, 2022 |
| Dell          | 042P49 A00                  | [81a5e313cd](https://bsd-hardware.info/?probe=81a5e313cd) | Aug 08, 2022 |
| MSI           | H81M-P33                    | [099e1c8b15](https://bsd-hardware.info/?probe=099e1c8b15) | Aug 07, 2022 |
| ASUSTek       | P5Q-E                       | [b96612a45b](https://bsd-hardware.info/?probe=b96612a45b) | Aug 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [29b392331d](https://bsd-hardware.info/?probe=29b392331d) | Aug 07, 2022 |
| GVC           | DR 738                      | [ea08102a81](https://bsd-hardware.info/?probe=ea08102a81) | Aug 06, 2022 |
| Gigabyte      | H97M-HD3                    | [4a7705414f](https://bsd-hardware.info/?probe=4a7705414f) | Aug 06, 2022 |
| Gigabyte      | H81M-DS2                    | [5b88dea745](https://bsd-hardware.info/?probe=5b88dea745) | Aug 06, 2022 |
| Gigabyte      | P85-D3                      | [7f077abed9](https://bsd-hardware.info/?probe=7f077abed9) | Aug 02, 2022 |
| ASUSTek       | B85-PRO GAMER               | [b29e940a75](https://bsd-hardware.info/?probe=b29e940a75) | Aug 02, 2022 |
| MSI           | H81M-P33                    | [10fc9a4368](https://bsd-hardware.info/?probe=10fc9a4368) | Jul 31, 2022 |
| ASUSTek       | P5Q-E                       | [10139014e1](https://bsd-hardware.info/?probe=10139014e1) | Jul 31, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1129960acb](https://bsd-hardware.info/?probe=1129960acb) | Jul 31, 2022 |
| Gigabyte      | GB-BSi3-1115G4              | [4cd0769d75](https://bsd-hardware.info/?probe=4cd0769d75) | Jul 30, 2022 |
| Dell          | 0T7D40 A01                  | [bd2f6f8596](https://bsd-hardware.info/?probe=bd2f6f8596) | Jul 29, 2022 |
| Dell          | 040DDP A01                  | [5d4d3d7553](https://bsd-hardware.info/?probe=5d4d3d7553) | Jul 29, 2022 |
| HP            | 1825                        | [8c96329681](https://bsd-hardware.info/?probe=8c96329681) | Jul 24, 2022 |
| MSI           | H81M-P33                    | [2f7e57d927](https://bsd-hardware.info/?probe=2f7e57d927) | Jul 24, 2022 |
| ASUSTek       | P5Q-E                       | [6fd0d31624](https://bsd-hardware.info/?probe=6fd0d31624) | Jul 24, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | [6cdc79a36f](https://bsd-hardware.info/?probe=6cdc79a36f) | Jul 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | [051f604f9a](https://bsd-hardware.info/?probe=051f604f9a) | Jul 21, 2022 |
| Dell          | 0WR7PY A03                  | [46a6f4e8f3](https://bsd-hardware.info/?probe=46a6f4e8f3) | Jul 19, 2022 |
| Dell          | 08HPGT A02                  | [ae260e17eb](https://bsd-hardware.info/?probe=ae260e17eb) | Jul 19, 2022 |
| MSI           | H81M-P33                    | [c9d1bc6685](https://bsd-hardware.info/?probe=c9d1bc6685) | Jul 17, 2022 |
| ASUSTek       | P5Q-E                       | [7c02a92f29](https://bsd-hardware.info/?probe=7c02a92f29) | Jul 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3bf44f4bb5](https://bsd-hardware.info/?probe=3bf44f4bb5) | Jul 17, 2022 |
| Acer          | Veriton X490G               | [2912c74632](https://bsd-hardware.info/?probe=2912c74632) | Jul 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [607a66e533](https://bsd-hardware.info/?probe=607a66e533) | Jul 14, 2022 |
| MouseCompu... | B360M                       | [3c22f3e91b](https://bsd-hardware.info/?probe=3c22f3e91b) | Jul 13, 2022 |
| Acer          | Veriton X490G               | [cbae2b155b](https://bsd-hardware.info/?probe=cbae2b155b) | Jul 11, 2022 |
| Acer          | Veriton X490G               | [3cd79878cd](https://bsd-hardware.info/?probe=3cd79878cd) | Jul 11, 2022 |
| MSI           | H81M-P33                    | [698249149d](https://bsd-hardware.info/?probe=698249149d) | Jul 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c2a2cdcbbb](https://bsd-hardware.info/?probe=c2a2cdcbbb) | Jul 10, 2022 |
| ASUSTek       | P5Q-E                       | [0c830d88dc](https://bsd-hardware.info/?probe=0c830d88dc) | Jul 10, 2022 |
| Unknown       | Unknown                     | [947d413e10](https://bsd-hardware.info/?probe=947d413e10) | Jul 09, 2022 |
| Intel         | DN2820FYK H24582-203        | [8a9a8cdbd0](https://bsd-hardware.info/?probe=8a9a8cdbd0) | Jul 08, 2022 |
| ASUSTek       | PRIME A520M-A II            | [0819ecdcf9](https://bsd-hardware.info/?probe=0819ecdcf9) | Jul 07, 2022 |
| ASUSTek       | PRIME A520M-A II            | [d459d3431a](https://bsd-hardware.info/?probe=d459d3431a) | Jul 07, 2022 |
| Acer          | Aspire XC-895 V:1.0         | [d67aa61a6b](https://bsd-hardware.info/?probe=d67aa61a6b) | Jul 05, 2022 |
| Acer          | Revo RN86                   | [2dc98202aa](https://bsd-hardware.info/?probe=2dc98202aa) | Jul 05, 2022 |
| ASRock        | Z490M Pro4                  | [b57457834e](https://bsd-hardware.info/?probe=b57457834e) | Jul 04, 2022 |
| Gigabyte      | Z370M D3H-CF                | [1d3db5e35a](https://bsd-hardware.info/?probe=1d3db5e35a) | Jul 04, 2022 |
| MSI           | H81M-P33                    | [e482fbe2d2](https://bsd-hardware.info/?probe=e482fbe2d2) | Jul 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d5dd169581](https://bsd-hardware.info/?probe=d5dd169581) | Jul 03, 2022 |
| ASUSTek       | P5Q-E                       | [7a998b2fa4](https://bsd-hardware.info/?probe=7a998b2fa4) | Jul 03, 2022 |
| ASRock        | X300M-STX                   | [a76b64487b](https://bsd-hardware.info/?probe=a76b64487b) | Jul 01, 2022 |
| ASRock        | P67 Professional            | [3372d35113](https://bsd-hardware.info/?probe=3372d35113) | Jun 28, 2022 |
| Gigabyte      | H61MA-D3V                   | [898da0bcec](https://bsd-hardware.info/?probe=898da0bcec) | Jun 28, 2022 |
| MSI           | H81M-P33                    | [079fcf320f](https://bsd-hardware.info/?probe=079fcf320f) | Jun 26, 2022 |
| ASUSTek       | P5Q-E                       | [bbc59d9815](https://bsd-hardware.info/?probe=bbc59d9815) | Jun 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6eb02df970](https://bsd-hardware.info/?probe=6eb02df970) | Jun 26, 2022 |
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
| MSI           | H81M-P33                    | [87a66430db](https://bsd-hardware.info/?probe=87a66430db) | Jun 12, 2022 |
| ASUSTek       | P5Q-E                       | [9b34d14850](https://bsd-hardware.info/?probe=9b34d14850) | Jun 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [c281c439e8](https://bsd-hardware.info/?probe=c281c439e8) | Jun 12, 2022 |
| Supermicro    | X9DR3-F                     | [d81151c0e8](https://bsd-hardware.info/?probe=d81151c0e8) | Jun 12, 2022 |
| ASUSTek       | Maximus VII FORMULA         | [5215d1ebb8](https://bsd-hardware.info/?probe=5215d1ebb8) | Jun 12, 2022 |
| MSI           | Z590 PRO WIFI               | [29b410eeb6](https://bsd-hardware.info/?probe=29b410eeb6) | Jun 06, 2022 |
| Gigabyte      | F2A75M-D3H                  | [ae3436167b](https://bsd-hardware.info/?probe=ae3436167b) | Jun 05, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [ff3865e01f](https://bsd-hardware.info/?probe=ff3865e01f) | Jun 05, 2022 |
| MSI           | H81M-P33                    | [49ab973713](https://bsd-hardware.info/?probe=49ab973713) | Jun 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7f11ab4091](https://bsd-hardware.info/?probe=7f11ab4091) | Jun 05, 2022 |
| ASUSTek       | P5Q-E                       | [10381fadd6](https://bsd-hardware.info/?probe=10381fadd6) | Jun 05, 2022 |
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
| amd64 | 56       | 91.8%   |
| arm64 | 3        | 4.92%   |
| i386  | 1        | 1.64%   |
| arm   | 1        | 1.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Console  | 30       | 49.18%  |
| KDE5     | 10       | 16.39%  |
| XFCE     | 9        | 14.75%  |
| TWM      | 3        | 4.92%   |
| Openbox  | 2        | 3.28%   |
| MATE     | 2        | 3.28%   |
| GNOME    | 2        | 3.28%   |
| LXQt     | 1        | 1.64%   |
| Compton  | 1        | 1.64%   |
| Cinnamon | 1        | 1.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 31       | 50.82%  |
| X11     | 30       | 49.18%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 42       | 68.85%  |
| SDDM    | 9        | 14.75%  |
| XDM     | 4        | 6.56%   |
| SLiM    | 4        | 6.56%   |
| LightDM | 2        | 3.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 38       | 62.3%   |
| en_US   | 8        | 13.11%  |
| ru_RU   | 6        | 9.84%   |
| fr_FR   | 3        | 4.92%   |
| Unknown | 3        | 4.92%   |
| ja_JP   | 1        | 1.64%   |
| en_GB   | 1        | 1.64%   |
| de_DE   | 1        | 1.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 39       | 62.9%   |
| BIOS | 23       | 37.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 40       | 65.57%  |
| Ufs  | 21       | 34.43%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 56       | 91.8%   |
| MBR  | 5        | 8.2%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 18.03%  |
| Gigabyte Technology | 9        | 14.75%  |
| Dell                | 9        | 14.75%  |
| ASRock              | 6        | 9.84%   |
| Hewlett-Packard     | 5        | 8.2%    |
| Intel               | 4        | 6.56%   |
| Unknown             | 4        | 6.56%   |
| MSI                 | 3        | 4.92%   |
| Acer                | 3        | 4.92%   |
| Supermicro          | 1        | 1.64%   |
| PC Engines          | 1        | 1.64%   |
| NF-M2S              | 1        | 1.64%   |
| MouseComputer       | 1        | 1.64%   |
| GVC                 | 1        | 1.64%   |
| Fujitsu             | 1        | 1.64%   |
| ASRockRack          | 1        | 1.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 4        | 6.56%   |
| ASUS All Series                    | 3        | 4.92%   |
| MSI MS-7817                        | 2        | 3.28%   |
| Supermicro Icebreaker 4824         | 1        | 1.64%   |
| PC Engines APU3                    | 1        | 1.64%   |
| NF-M2S ABIT                        | 1        | 1.64%   |
| MSI MS-7D09                        | 1        | 1.64%   |
| MouseComputer B360M                | 1        | 1.64%   |
| Intel X79 V2.72A                   | 1        | 1.64%   |
| Intel Q3XXG4-P V1.0                | 1        | 1.64%   |
| Intel DN2820FYK H24582-203         | 1        | 1.64%   |
| Intel D945GCLF2 AAE46416-104       | 1        | 1.64%   |
| HP Z620 Workstation                | 1        | 1.64%   |
| HP ProLiant ML310e Gen8 v2         | 1        | 1.64%   |
| HP EliteDesk 800 G1 DM             | 1        | 1.64%   |
| HP Desktop M01-F0xxx               | 1        | 1.64%   |
| HP Compaq dc7900 Small Form Factor | 1        | 1.64%   |
| GVC EQUIUM 3200M                   | 1        | 1.64%   |
| Gigabyte Z370M D3H                 | 1        | 1.64%   |
| Gigabyte X470 AORUS GAMING 7 WIFI  | 1        | 1.64%   |
| Gigabyte P85-D3                    | 1        | 1.64%   |
| Gigabyte H97M-HD3                  | 1        | 1.64%   |
| Gigabyte H61MA-D3V                 | 1        | 1.64%   |
| Gigabyte GB-BSi3-1115G4            | 1        | 1.64%   |
| Gigabyte F2A75M-D3H                | 1        | 1.64%   |
| Gigabyte B550M AORUS PRO-P         | 1        | 1.64%   |
| Gigabyte B450M DS3H                | 1        | 1.64%   |
| Fujitsu D3401-H2 S26361-D3401-H2   | 1        | 1.64%   |
| Dell Precision T3600               | 1        | 1.64%   |
| Dell OptiPlex 7050                 | 1        | 1.64%   |
| Dell OptiPlex 7010                 | 1        | 1.64%   |
| Dell OptiPlex 5040                 | 1        | 1.64%   |
| Dell OptiPlex 3080                 | 1        | 1.64%   |
| Dell OptiPlex 3020                 | 1        | 1.64%   |
| Dell OptiPlex 3010                 | 1        | 1.64%   |
| Dell Inspiron 3668                 | 1        | 1.64%   |
| Dell G5 5090                       | 1        | 1.64%   |
| ASUS ROG STRIX X570-F GAMING       | 1        | 1.64%   |
| ASUS ROG STRIX B550-F GAMING       | 1        | 1.64%   |
| ASUS ROG CROSSHAIR VIII HERO       | 1        | 1.64%   |
| ASUS PRIME Z590-P                  | 1        | 1.64%   |
| ASUS PRIME B350-PLUS               | 1        | 1.64%   |
| ASUS PRIME A520M-A II              | 1        | 1.64%   |
| ASUS P5Q-E                         | 1        | 1.64%   |
| ASUS Maximus VIII HERO             | 1        | 1.64%   |
| ASRockRack E3C242D4U2-2T           | 1        | 1.64%   |
| ASRock Z490M Pro4                  | 1        | 1.64%   |
| ASRock X300M-STX                   | 1        | 1.64%   |
| ASRock P67 Professional            | 1        | 1.64%   |
| ASRock H110M-DGS R3.0              | 1        | 1.64%   |
| ASRock B550 Phantom Gaming-ITX/ax  | 1        | 1.64%   |
| ASRock AD2550-ITX                  | 1        | 1.64%   |
| Acer Veriton X490G                 | 1        | 1.64%   |
| Acer Revo RN86                     | 1        | 1.64%   |
| Acer Aspire XC-895                 | 1        | 1.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Dell OptiPlex            | 6        | 9.84%   |
| Unknown                  | 4        | 6.56%   |
| ASUS ROG                 | 3        | 4.92%   |
| ASUS PRIME               | 3        | 4.92%   |
| ASUS All                 | 3        | 4.92%   |
| MSI MS-7817              | 2        | 3.28%   |
| Supermicro Icebreaker    | 1        | 1.64%   |
| PC Engines APU3          | 1        | 1.64%   |
| NF-M2S ABIT              | 1        | 1.64%   |
| MSI MS-7D09              | 1        | 1.64%   |
| MouseComputer B360M      | 1        | 1.64%   |
| Intel X79                | 1        | 1.64%   |
| Intel Q3XXG4-P           | 1        | 1.64%   |
| Intel DN2820FYK          | 1        | 1.64%   |
| Intel D945GCLF2          | 1        | 1.64%   |
| HP Z620                  | 1        | 1.64%   |
| HP ProLiant              | 1        | 1.64%   |
| HP EliteDesk             | 1        | 1.64%   |
| HP Desktop               | 1        | 1.64%   |
| HP Compaq                | 1        | 1.64%   |
| GVC EQUIUM               | 1        | 1.64%   |
| Gigabyte Z370M           | 1        | 1.64%   |
| Gigabyte X470            | 1        | 1.64%   |
| Gigabyte P85-D3          | 1        | 1.64%   |
| Gigabyte H97M-HD3        | 1        | 1.64%   |
| Gigabyte H61MA-D3V       | 1        | 1.64%   |
| Gigabyte GB-BSi3-1115G4  | 1        | 1.64%   |
| Gigabyte F2A75M-D3H      | 1        | 1.64%   |
| Gigabyte B550M           | 1        | 1.64%   |
| Gigabyte B450M           | 1        | 1.64%   |
| Fujitsu D3401-H2         | 1        | 1.64%   |
| Dell Precision           | 1        | 1.64%   |
| Dell Inspiron            | 1        | 1.64%   |
| Dell G5                  | 1        | 1.64%   |
| ASUS P5Q-E               | 1        | 1.64%   |
| ASUS Maximus             | 1        | 1.64%   |
| ASRockRack E3C242D4U2-2T | 1        | 1.64%   |
| ASRock Z490M             | 1        | 1.64%   |
| ASRock X300M-STX         | 1        | 1.64%   |
| ASRock P67               | 1        | 1.64%   |
| ASRock H110M-DGS         | 1        | 1.64%   |
| ASRock B550              | 1        | 1.64%   |
| ASRock AD2550-ITX        | 1        | 1.64%   |
| Acer Veriton             | 1        | 1.64%   |
| Acer Revo                | 1        | 1.64%   |
| Acer Aspire              | 1        | 1.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 9        | 14.75%  |
| 2019    | 7        | 11.48%  |
| 2014    | 7        | 11.48%  |
| 2022    | 5        | 8.2%    |
| 2021    | 5        | 8.2%    |
| 2018    | 5        | 8.2%    |
| Unknown | 5        | 8.2%    |
| 2013    | 4        | 6.56%   |
| 2016    | 3        | 4.92%   |
| 2008    | 3        | 4.92%   |
| 2017    | 2        | 3.28%   |
| 2012    | 2        | 3.28%   |
| 2015    | 1        | 1.64%   |
| 2011    | 1        | 1.64%   |
| 2010    | 1        | 1.64%   |
| 2009    | 1        | 1.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 61       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 60       | 98.36%  |
| Yes  | 1        | 1.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 17       | 27.42%  |
| 8.01-16.0   | 16       | 25.81%  |
| 32.01-64.0  | 8        | 12.9%   |
| 64.01-256.0 | 7        | 11.29%  |
| 4.01-8.0    | 4        | 6.45%   |
| 2.01-3.0    | 3        | 4.84%   |
| 3.01-4.0    | 2        | 3.23%   |
| 24.01-32.0  | 2        | 3.23%   |
| 0.01-0.5    | 2        | 3.23%   |
| 0.51-1.0    | 1        | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 22       | 35.48%  |
| 0.51-1.0 | 20       | 32.26%  |
| 1.01-2.0 | 11       | 17.74%  |
| 2.01-3.0 | 4        | 6.45%   |
| 0        | 3        | 4.84%   |
| 3.01-4.0 | 2        | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 25.81%  |
| 2      | 15       | 24.19%  |
| 3      | 10       | 16.13%  |
| 4      | 8        | 12.9%   |
| 0      | 5        | 8.06%   |
| 8      | 2        | 3.23%   |
| 6      | 2        | 3.23%   |
| 18     | 1        | 1.61%   |
| 15     | 1        | 1.61%   |
| 10     | 1        | 1.61%   |
| 5      | 1        | 1.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 67.21%  |
| Yes       | 20       | 32.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 56       | 91.8%   |
| No        | 5        | 8.2%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 44       | 72.13%  |
| Yes       | 17       | 27.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 50       | 81.97%  |
| Yes       | 11       | 18.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 17       | 27.87%  |
| Russia      | 8        | 13.11%  |
| Germany     | 8        | 13.11%  |
| Spain       | 4        | 6.56%   |
| France      | 4        | 6.56%   |
| Canada      | 3        | 4.92%   |
| New Zealand | 2        | 3.28%   |
| Netherlands | 2        | 3.28%   |
| Czechia     | 2        | 3.28%   |
| Austria     | 2        | 3.28%   |
| Australia   | 2        | 3.28%   |
| Thailand    | 1        | 1.64%   |
| Taiwan      | 1        | 1.64%   |
| Japan       | 1        | 1.64%   |
| Ireland     | 1        | 1.64%   |
| Hungary     | 1        | 1.64%   |
| Croatia     | 1        | 1.64%   |
| Belgium     | 1        | 1.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Frisco          | 4        | 6.45%   |
| Ozersk          | 3        | 4.84%   |
| Wellington      | 2        | 3.23%   |
| Tamm            | 2        | 3.23%   |
| Redmond         | 2        | 3.23%   |
| Omaha           | 2        | 3.23%   |
| Moscow          | 2        | 3.23%   |
| Madrid          | 2        | 3.23%   |
| Brno            | 2        | 3.23%   |
| Zagreb          | 1        | 1.61%   |
| Yashio          | 1        | 1.61%   |
| Wenatchee       | 1        | 1.61%   |
| Waldbrunn       | 1        | 1.61%   |
| Vienna          | 1        | 1.61%   |
| Vaulx-en-Velin  | 1        | 1.61%   |
| Valladolid      | 1        | 1.61%   |
| Toronto         | 1        | 1.61%   |
| Tiel            | 1        | 1.61%   |
| Taipei          | 1        | 1.61%   |
| Sydney          | 1        | 1.61%   |
| St. Albert      | 1        | 1.61%   |
| St Petersburg   | 1        | 1.61%   |
| Sarasota        | 1        | 1.61%   |
| Saarbrücken    | 1        | 1.61%   |
| Poperinge       | 1        | 1.61%   |
| Pluvigner       | 1        | 1.61%   |
| Paris           | 1        | 1.61%   |
| Nakhodka        | 1        | 1.61%   |
| Münster        | 1        | 1.61%   |
| Mossingen       | 1        | 1.61%   |
| Montreal        | 1        | 1.61%   |
| Methuen         | 1        | 1.61%   |
| Medford         | 1        | 1.61%   |
| Marseille       | 1        | 1.61%   |
| Lower Hutt      | 1        | 1.61%   |
| Green Valley    | 1        | 1.61%   |
| Gmunden         | 1        | 1.61%   |
| Falkenstein     | 1        | 1.61%   |
| Düsseldorf     | 1        | 1.61%   |
| Dublin          | 1        | 1.61%   |
| Denver          | 1        | 1.61%   |
| Chelyabinsk     | 1        | 1.61%   |
| Charlotte       | 1        | 1.61%   |
| Budapest        | 1        | 1.61%   |
| Brisbane        | 1        | 1.61%   |
| Borrego Springs | 1        | 1.61%   |
| Bangkok         | 1        | 1.61%   |
| Auburn          | 1        | 1.61%   |
| Asten           | 1        | 1.61%   |
| Altea           | 1        | 1.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 29       | 60     | 27.36%  |
| Samsung Electronics | 19       | 42     | 17.92%  |
| Seagate             | 18       | 51     | 16.98%  |
| Toshiba             | 7        | 14     | 6.6%    |
| Kingston            | 5        | 5      | 4.72%   |
| Intel               | 5        | 7      | 4.72%   |
| Crucial             | 5        | 8      | 4.72%   |
| Hewlett-Packard     | 2        | 2      | 1.89%   |
| A-DATA Technology   | 2        | 2      | 1.89%   |
| Verbatim            | 1        | 1      | 0.94%   |
| SPCC                | 1        | 1      | 0.94%   |
| SK hynix            | 1        | 1      | 0.94%   |
| SanDisk             | 1        | 1      | 0.94%   |
| PNY                 | 1        | 2      | 0.94%   |
| ORICO               | 1        | 1      | 0.94%   |
| OCZ                 | 1        | 1      | 0.94%   |
| Micron Technology   | 1        | 2      | 0.94%   |
| LITEONIT            | 1        | 1      | 0.94%   |
| Hitachi             | 1        | 1      | 0.94%   |
| Hikvision           | 1        | 1      | 0.94%   |
| HGST                | 1        | 1      | 0.94%   |
| Gigabyte Technology | 1        | 1      | 0.94%   |
| China               | 1        | 1      | 0.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB             | 4        | 2.96%   |
| Seagate ST1000DM010-2EP102 1TB       | 3        | 2.22%   |
| Samsung SSD 850 EVO 500GB            | 3        | 2.22%   |
| WDC WD5000LPLX-00ZNTT0 500GB         | 2        | 1.48%   |
| WDC WD30EFRX-68EUZN0 3TB             | 2        | 1.48%   |
| Seagate ST4000DM000-1F2168 4TB       | 2        | 1.48%   |
| Samsung SSD 970 EVO 1TB              | 2        | 1.48%   |
| Samsung SSD 870 QVO 2TB              | 2        | 1.48%   |
| Samsung SSD 840 EVO 120GB            | 2        | 1.48%   |
| Kingston SA400S37120G 120GB          | 2        | 1.48%   |
| Intel SSDSC2CT060A3 64GB             | 2        | 1.48%   |
| Crucial CT240BX500SSD1 240GB         | 2        | 1.48%   |
| A-DATA SU650 240GB                   | 2        | 1.48%   |
| WDC WDS500G1B0A-00H9H0 500GB         | 1        | 0.74%   |
| WDC WDS100T2B0A-00SM50 1TB           | 1        | 0.74%   |
| WDC WDBA3V5000ANC-WRSN 500GB         | 1        | 0.74%   |
| WDC WD80EZZX-11CSGA0 8TB             | 1        | 0.74%   |
| WDC WD80EZAZ-11TDBA0 8TB             | 1        | 0.74%   |
| WDC WD80EMZZ-00TBGA0 8TB             | 1        | 0.74%   |
| WDC WD80EFBX-68AZZN0 8TB             | 1        | 0.74%   |
| WDC WD8003FFBX-68B9AN0 8TB           | 1        | 0.74%   |
| WDC WD60EFRX-68L0BN1 6TB             | 1        | 0.74%   |
| WDC WD5000LUCT-63Y8HY0 500GB         | 1        | 0.74%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 1        | 0.74%   |
| WDC WD40EZRZ-22GXCB0 4TB             | 1        | 0.74%   |
| WDC WD4003FRYZ-01F0DB0 4TB           | 1        | 0.74%   |
| WDC WD30EFRX-68N32N0 3TB             | 1        | 0.74%   |
| WDC WD30EFRX-68AX9N0 3TB             | 1        | 0.74%   |
| WDC WD20NMVW-11EDZS2 2TB             | 1        | 0.74%   |
| WDC WD20NMVW-11AV3S2 2TB             | 1        | 0.74%   |
| WDC WD20EARX-00PASB0 2TB             | 1        | 0.74%   |
| WDC WD2003FYYS-18W0B0 2TB            | 1        | 0.74%   |
| WDC WD1600AAJS-60M0A0 160GB          | 1        | 0.74%   |
| WDC WD15EADS-00P8B0 1.5TB            | 1        | 0.74%   |
| WDC WD140EFGX-68B0GN0 14TB           | 1        | 0.74%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1        | 0.74%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1        | 0.74%   |
| WDC WD10EZEX-00RKKA0 1TB             | 1        | 0.74%   |
| WDC WD10EZEX-00MFCA0 1TB             | 1        | 0.74%   |
| WDC WD10EAVS-00D7B1 1TB              | 1        | 0.74%   |
| WDC WD100EMAZ-00WJTA0 10TB           | 1        | 0.74%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 1        | 0.74%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB | 1        | 0.74%   |
| WDC PC SN520 NVMe 256GB              | 1        | 0.74%   |
| WDC CL SN720 SDAQNTW-512G-2000 512GB | 1        | 0.74%   |
| Verbatim Vi550 S3 SSD 512GB          | 1        | 0.74%   |
| Toshiba TR200 240GB                  | 1        | 0.74%   |
| Toshiba HDWR180 8TB                  | 1        | 0.74%   |
| Toshiba HDWD120 2TB                  | 1        | 0.74%   |
| Toshiba HDWD110 1TB                  | 1        | 0.74%   |
| Toshiba HDWD105 500GB                | 1        | 0.74%   |
| Toshiba DT01ACA300 3TB               | 1        | 0.74%   |
| Toshiba DT01ACA100 1TB               | 1        | 0.74%   |
| Toshiba DT01ABA300 3TB               | 1        | 0.74%   |
| SPCC M.2 SSD 256GB                   | 1        | 0.74%   |
| SK hynix SC308 SATA 128GB            | 1        | 0.74%   |
| Seagate ST9500325AS 500GB            | 1        | 0.74%   |
| Seagate ST9320423AS 320GB            | 1        | 0.74%   |
| Seagate ST8000VN0022-2EL112 8TB      | 1        | 0.74%   |
| Seagate ST8000AS0002-1NA17Z 8TB      | 1        | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 53     | 46%     |
| Seagate             | 17       | 50     | 34%     |
| Toshiba             | 6        | 13     | 12%     |
| Samsung Electronics | 1        | 4      | 2%      |
| Hitachi             | 1        | 1      | 2%      |
| HGST                | 1        | 1      | 2%      |
| Hewlett-Packard     | 1        | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 30     | 32.5%   |
| Intel               | 4        | 6      | 10%     |
| Crucial             | 4        | 4      | 10%     |
| Kingston            | 3        | 3      | 7.5%    |
| WDC                 | 2        | 2      | 5%      |
| A-DATA Technology   | 2        | 2      | 5%      |
| Verbatim            | 1        | 1      | 2.5%    |
| Toshiba             | 1        | 1      | 2.5%    |
| SPCC                | 1        | 1      | 2.5%    |
| SK hynix            | 1        | 1      | 2.5%    |
| SanDisk             | 1        | 1      | 2.5%    |
| PNY                 | 1        | 2      | 2.5%    |
| ORICO               | 1        | 1      | 2.5%    |
| OCZ                 | 1        | 1      | 2.5%    |
| Micron Technology   | 1        | 2      | 2.5%    |
| LITEONIT            | 1        | 1      | 2.5%    |
| Hikvision           | 1        | 1      | 2.5%    |
| China               | 1        | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 38       | 123    | 43.18%  |
| SSD  | 34       | 61     | 38.64%  |
| NVMe | 16       | 23     | 18.18%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 53       | 184    | 76.81%  |
| NVMe | 16       | 23     | 23.19%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 32       | 50     | 39.02%  |
| 0.51-1.0   | 26       | 39     | 31.71%  |
| 1.01-2.0   | 9        | 29     | 10.98%  |
| 3.01-4.0   | 6        | 16     | 7.32%   |
| 4.01-10.0  | 4        | 29     | 4.88%   |
| 2.01-3.0   | 3        | 16     | 3.66%   |
| 10.01-20.0 | 2        | 5      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 16       | 25.81%  |
| 501-1000       | 13       | 20.97%  |
| 251-500        | 10       | 16.13%  |
| 21-50          | 8        | 12.9%   |
| 51-100         | 5        | 8.06%   |
| 2001-3000      | 3        | 4.84%   |
| 1-20           | 3        | 4.84%   |
| 1001-2000      | 2        | 3.23%   |
| More than 3000 | 1        | 1.61%   |
| Unknown        | 1        | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 50       | 81.97%  |
| 21-50          | 5        | 8.2%    |
| 51-100         | 2        | 3.28%   |
| More than 3000 | 1        | 1.64%   |
| 251-500        | 1        | 1.64%   |
| 501-1000       | 1        | 1.64%   |
| Unknown        | 1        | 1.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| WDC WD5000LPLX-00ZNTT0 500GB               | 1        | 1      | 10%     |
| WDC WD30EFRX-68EUZN0 3TB                   | 1        | 3      | 10%     |
| WDC WD1600AAJS-60M0A0 160GB                | 1        | 1      | 10%     |
| SPCC M.2 SSD 256GB                         | 1        | 1      | 10%     |
| SK hynix SC308 SATA 128GB                  | 1        | 1      | 10%     |
| Seagate ST9500325AS 500GB                  | 1        | 1      | 10%     |
| Micron Technology 1100_MTFDDAK512TBN 512GB | 1        | 2      | 10%     |
| Hitachi HTS727575A9E364 752GB              | 1        | 1      | 10%     |
| HGST HTS725050A7E630 500GB                 | 1        | 1      | 10%     |
| Hewlett-Packard MB1000GCWCV 1TB            | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| WDC               | 3        | 5      | 30%     |
| SPCC              | 1        | 1      | 10%     |
| SK hynix          | 1        | 1      | 10%     |
| Seagate           | 1        | 1      | 10%     |
| Micron Technology | 1        | 2      | 10%     |
| Hitachi           | 1        | 1      | 10%     |
| HGST              | 1        | 1      | 10%     |
| Hewlett-Packard   | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor          | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| WDC             | 3        | 5      | 42.86%  |
| Seagate         | 1        | 1      | 14.29%  |
| Hitachi         | 1        | 1      | 14.29%  |
| HGST            | 1        | 1      | 14.29%  |
| Hewlett-Packard | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 9      | 70%     |
| SSD  | 3        | 4      | 30%     |

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
| Works    | 53       | 188    | 84.13%  |
| Malfunc  | 8        | 13     | 12.7%   |
| Detected | 2        | 6      | 3.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 44       | 52.38%  |
| AMD                         | 11       | 13.1%   |
| Samsung Electronics         | 7        | 8.33%   |
| SanDisk                     | 4        | 4.76%   |
| Marvell Technology Group    | 3        | 3.57%   |
| Broadcom / LSI              | 3        | 3.57%   |
| ASMedia Technology          | 3        | 3.57%   |
| Micron/Crucial Technology   | 2        | 2.38%   |
| Kingston Technology Company | 2        | 2.38%   |
| Silicon Motion              | 1        | 1.19%   |
| Silicon Image               | 1        | 1.19%   |
| Seagate Technology          | 1        | 1.19%   |
| Phison Electronics          | 1        | 1.19%   |
| Nvidia                      | 1        | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8        | 8.33%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6        | 6.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 5.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 4.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 4.17%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 4.17%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3        | 3.13%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 3.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 3.13%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 3        | 3.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 2.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 2.08%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2        | 2.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 2.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 2.08%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 2.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2        | 2.08%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 2.08%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 2.08%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 1.04%   |
| Silicon Image SiI 3124 PCI-X Serial ATA Controller                             | 1        | 1.04%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 1.04%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1        | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 1.04%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.04%   |
| Phison NVMe Storage Controller                                                 | 1        | 1.04%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.04%   |
| Nvidia MCP61 IDE                                                               | 1        | 1.04%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.04%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                   | 1        | 1.04%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 1.04%   |
| Kingston Company KC2000 NVMe SSD                                               | 1        | 1.04%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 1.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1        | 1.04%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 1.04%   |
| Intel SSD 660P Series                                                          | 1        | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 1.04%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 1.04%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 1        | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1        | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.04%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 1        | 1.04%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 1        | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1        | 1.04%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                          | 1        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1        | 1.04%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 1        | 1.04%   |
| ASMedia ASM1166 Serial ATA Controller                                          | 1        | 1.04%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1        | 1.04%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 1.04%   |
| Unknown                                                                        | 1        | 1.04%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 50       | 61.73%  |
| NVMe | 16       | 19.75%  |
| IDE  | 8        | 9.88%   |
| SAS  | 4        | 4.94%   |
| RAID | 3        | 3.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 44       | 72.13%  |
| AMD    | 13       | 21.31%  |
| ARM    | 4        | 6.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ARM Cortex-A53 r0p4                        | 3        | 4.84%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 3        | 4.84%   |
| Intel Core i7-7700 CPU @ 3.60GHz           | 2        | 3.23%   |
| Intel Core i5-8400 CPU @ 2.80GHz           | 2        | 3.23%   |
| Intel Core i5-3470 CPU @ 3.20GHz           | 2        | 3.23%   |
| Intel Xeon E-2136 CPU @ 3.30GHz            | 1        | 1.61%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz           | 1        | 1.61%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz        | 1        | 1.61%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GH          | 1        | 1.61%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz        | 1        | 1.61%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz        | 1        | 1.61%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz        | 1        | 1.61%   |
| Intel Pentium II                           | 1        | 1.61%   |
| Intel Pentium CPU G3220 @ 3.00GHz          | 1        | 1.61%   |
| Intel Core i7-9700K CPU @ 3.60GHz          | 1        | 1.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 1        | 1.61%   |
| Intel Core i7-4790K CPU @ 4.00GHz          | 1        | 1.61%   |
| Intel Core i7-4785T CPU @ 2.20GHz          | 1        | 1.61%   |
| Intel Core i7-2600K CPU @ 3.40GHz          | 1        | 1.61%   |
| Intel Core i7-10700K CPU @ 3.80GHz         | 1        | 1.61%   |
| Intel Core i5-9400T CPU @ 1.80GHz          | 1        | 1.61%   |
| Intel Core i5-9400 CPU @ 2.90GHz           | 1        | 1.61%   |
| Intel Core i5-7500 CPU @ 3.40GHz           | 1        | 1.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz           | 1        | 1.61%   |
| Intel Core i5-5250U CPU @ 1.60GHz          | 1        | 1.61%   |
| Intel Core i5-4690 CPU @ 3.50GHz           | 1        | 1.61%   |
| Intel Core i5-4670K CPU @ 3.40GHz          | 1        | 1.61%   |
| Intel Core i5-4590T CPU @ 2.00GHz          | 1        | 1.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz           | 1        | 1.61%   |
| Intel Core i5-4440 CPU @ 3.10GHz           | 1        | 1.61%   |
| Intel Core i5-3570 CPU @ 3.40GHz           | 1        | 1.61%   |
| Intel Core i5-2400 CPU                     | 1        | 1.61%   |
| Intel Core i5-10600K CPU @ 4.10GHz         | 1        | 1.61%   |
| Intel Core i5-10400 CPU @ 2.90GHz          | 1        | 1.61%   |
| Intel Core i3-7100 CPU @ 3.90GHz           | 1        | 1.61%   |
| Intel Core i3-10100 CPU @ 3.60GHz          | 1        | 1.61%   |
| Intel Core i3 CPU 540 @ 3.07GHz            | 1        | 1.61%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz      | 1        | 1.61%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz       | 1        | 1.61%   |
| Intel Celeron CPU N2830 @ 2.16GHz          | 1        | 1.61%   |
| Intel Atom CPU D2550 @ 1.86GHz             | 1        | 1.61%   |
| Intel Atom CPU 330 @ 1.60GHz               | 1        | 1.61%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz     | 1        | 1.61%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz    | 1        | 1.61%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)         | 1        | 1.61%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 1        | 1.61%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 1        | 1.61%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics | 1        | 1.61%   |
| AMD Ryzen 7 2700X Eight-Core Processor     | 1        | 1.61%   |
| AMD Ryzen 7 1700 Eight-Core Processor      | 1        | 1.61%   |
| AMD Ryzen 5 2600 Six-Core Processor        | 1        | 1.61%   |
| AMD Ryzen 3 3300X 4-Core Processor         | 1        | 1.61%   |
| AMD GX-412TC SOC                           | 1        | 1.61%   |
| AMD Athlon 64 X2 Dual Core Processor 6000+ | 1        | 1.61%   |
| AMD A10-5800K APU with Radeon HD Graphics  | 1        | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i5     | 17       | 27.87%  |
| Intel Core i7     | 8        | 13.11%  |
| Intel Xeon        | 7        | 11.48%  |
| AMD Ryzen 5       | 4        | 6.56%   |
| Other             | 3        | 4.92%   |
| Intel Core i3     | 3        | 4.92%   |
| ARM Cortex        | 3        | 4.92%   |
| Intel Pentium     | 2        | 3.28%   |
| Intel Atom        | 2        | 3.28%   |
| AMD Ryzen 9       | 2        | 3.28%   |
| AMD Ryzen 7       | 2        | 3.28%   |
| Intel Core 2 Quad | 1        | 1.64%   |
| Intel Core 2 Duo  | 1        | 1.64%   |
| Intel Celeron     | 1        | 1.64%   |
| AMD Ryzen 7 PRO   | 1        | 1.64%   |
| AMD Ryzen 3       | 1        | 1.64%   |
| AMD GX            | 1        | 1.64%   |
| AMD Athlon 64 X2  | 1        | 1.64%   |
| AMD A10           | 1        | 1.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 22       | 36.07%  |
| 2       | 9        | 14.75%  |
| 6       | 8        | 13.11%  |
| 8       | 6        | 9.84%   |
| Unknown | 5        | 8.2%    |
| 16      | 4        | 6.56%   |
| 12      | 4        | 6.56%   |
| 24      | 2        | 3.28%   |
| 1       | 1        | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 56       | 91.8%   |
| Unknown | 4        | 6.56%   |
| 2       | 1        | 1.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 34       | 55.74%  |
| 2       | 21       | 34.43%  |
| Unknown | 6        | 9.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 10       | 16.13%  |
| Haswell     | 10       | 16.13%  |
| IvyBridge   | 5        | 8.06%   |
| Unknown     | 5        | 8.06%   |
| Zen 3       | 4        | 6.45%   |
| SandyBridge | 4        | 6.45%   |
| CometLake   | 4        | 6.45%   |
| Zen 2       | 3        | 4.84%   |
| Zen+        | 2        | 3.23%   |
| Skylake     | 2        | 3.23%   |
| Bonnell     | 2        | 3.23%   |
| Zen         | 1        | 1.61%   |
| Westmere    | 1        | 1.61%   |
| TigerLake   | 1        | 1.61%   |
| Silvermont  | 1        | 1.61%   |
| Puma        | 1        | 1.61%   |
| Piledriver  | 1        | 1.61%   |
| Penryn      | 1        | 1.61%   |
| P6          | 1        | 1.61%   |
| K8 Hammer   | 1        | 1.61%   |
| Core        | 1        | 1.61%   |
| Broadwell   | 1        | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 25       | 43.1%   |
| Nvidia                               | 18       | 31.03%  |
| AMD                                  | 11       | 18.97%  |
| Matrox Electronics Systems           | 2        | 3.45%   |
| NVidia / SGS Thomson (Joint Venture) | 1        | 1.72%   |
| ASPEED Technology                    | 1        | 1.72%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 7        | 11.67%  |
| Intel HD Graphics 630                                                       | 3        | 5%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 5%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 5%      |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 3.33%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 3.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.33%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.33%   |
| AMD Cezanne                                                                 | 2        | 3.33%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                               | 2        | 3.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.67%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.67%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 1.67%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.67%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.67%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.67%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.67%   |
| NVidia / SGS Thomson (Joint Venture) Riva128                                | 1        | 1.67%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 1        | 1.67%   |
| Matrox Electronics Systems MGA G200EH                                       | 1        | 1.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.67%   |
| Intel Tiger Lake UHD Graphics                                               | 1        | 1.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.67%   |
| Intel HD Graphics 6000                                                      | 1        | 1.67%   |
| Intel HD Graphics 530                                                       | 1        | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 1.67%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 1        | 1.67%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.67%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.67%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.67%   |
| AMD Turks PRO [Radeon HD 7570]                                              | 1        | 1.67%   |
| AMD RV370 [Radeon X300/X550/X1050 Series] (Secondary)                       | 1        | 1.67%   |
| AMD RV370 [Radeon X300/X550/X1050 Series]                                   | 1        | 1.67%   |
| AMD Renoir                                                                  | 1        | 1.67%   |
| AMD Redwood XT [Radeon HD 5670/5690/5730]                                   | 1        | 1.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 1.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Intel                                | 23       | 37.7%   |
| 1 x Nvidia                               | 16       | 26.23%  |
| 1 x AMD                                  | 10       | 16.39%  |
| Other                                    | 5        | 8.2%    |
| 1 x Matrox                               | 2        | 3.28%   |
| Intel + Nvidia                           | 2        | 3.28%   |
| 2 x AMD                                  | 1        | 1.64%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 1.64%   |
| 1 x ASPEED                               | 1        | 1.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 40       | 65.57%  |
| Proprietary | 15       | 24.59%  |
| Unknown     | 6        | 9.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 41       | 67.21%  |
| 1.01-2.0   | 6        | 9.84%   |
| 0.51-1.0   | 6        | 9.84%   |
| 7.01-8.0   | 2        | 3.28%   |
| 5.01-6.0   | 2        | 3.28%   |
| 3.01-4.0   | 2        | 3.28%   |
| 2.01-3.0   | 1        | 1.64%   |
| 0.01-0.5   | 1        | 1.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 8        | 22.86%  |
| Dell                | 4        | 11.43%  |
| Acer                | 4        | 11.43%  |
| Goldstar            | 3        | 8.57%   |
| Philips             | 2        | 5.71%   |
| Lenovo              | 2        | 5.71%   |
| ViewSonic           | 1        | 2.86%   |
| Vestel Elektronik   | 1        | 2.86%   |
| Sceptre Tech        | 1        | 2.86%   |
| Panasonic           | 1        | 2.86%   |
| LG Electronics      | 1        | 2.86%   |
| IOD                 | 1        | 2.86%   |
| Iiyama              | 1        | 2.86%   |
| Idek Iiyama         | 1        | 2.86%   |
| Compal              | 1        | 2.86%   |
| BenQ                | 1        | 2.86%   |
| ASUSTek Computer    | 1        | 2.86%   |
| AOC                 | 1        | 2.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 2        | 5.56%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1        | 2.78%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1        | 2.78%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1        | 2.78%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1        | 2.78%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                      | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 2.78%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 2.78%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1        | 2.78%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 2.78%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 2.78%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 1        | 2.78%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1        | 2.78%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch               | 1        | 2.78%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1        | 2.78%   |
| IOD KH270V IOD1B3B 1920x1080 600x340mm 27.2-inch                       | 1        | 2.78%   |
| Iiyama PL2483H IVM6138 1920x1080 530x300mm 24.0-inch                   | 1        | 2.78%   |
| Idek Iiyama LCD Monitor PL2730Q 2560x1440                              | 1        | 2.78%   |
| Goldstar LG ULTRAGEAR GSM776E 2560x1440 700x390mm 31.5-inch            | 1        | 2.78%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1        | 2.78%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                  | 1        | 2.78%   |
| Dell UP2716D DEL40DD 2560x1440 600x340mm 27.2-inch                     | 1        | 2.78%   |
| Dell LCD Monitor SP2309W 2048x1152                                     | 1        | 2.78%   |
| Dell IN2020M DELF030 1600x900 440x250mm 19.9-inch                      | 1        | 2.78%   |
| Dell E151FPp DEL7006 1024x768 300x230mm 14.9-inch                      | 1        | 2.78%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch               | 1        | 2.78%   |
| BenQ LCD Monitor PD3200Q                                               | 1        | 2.78%   |
| BenQ LCD Monitor GW2765                                                | 1        | 2.78%   |
| ASUSTek Computer PA248QV AUS2487 1920x1200 520x320mm 24.0-inch         | 1        | 2.78%   |
| AOC U28P2G6B AOC2802 3840x2160 620x340mm 27.8-inch                     | 1        | 2.78%   |
| Acer VW237Q ACR06B9 1920x1200 490x300mm 22.6-inch                      | 1        | 2.78%   |
| Acer RG270 ACR061E 1920x1080 600x340mm 27.2-inch                       | 1        | 2.78%   |
| Acer H223HQ ACR0086 1920x1080 480x270mm 21.7-inch                      | 1        | 2.78%   |
| Acer AL1916 ACR077C 1280x1024 380x310mm 19.3-inch                      | 1        | 2.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 41.18%  |
| 2560x1440 (QHD)    | 5        | 14.71%  |
| 1920x1200 (WUXGA)  | 3        | 8.82%   |
| 3840x2160 (4K)     | 2        | 5.88%   |
| 1680x1050 (WSXGA+) | 2        | 5.88%   |
| 1280x1024 (SXGA)   | 2        | 5.88%   |
| 2560x1080          | 1        | 2.94%   |
| 2048x1152          | 1        | 2.94%   |
| 1920x540           | 1        | 2.94%   |
| 1600x900 (HD+)     | 1        | 2.94%   |
| 1024x768 (XGA)     | 1        | 2.94%   |
| Unknown            | 1        | 2.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 23.53%  |
| 27      | 5        | 14.71%  |
| 24      | 5        | 14.71%  |
| 21      | 5        | 14.71%  |
| 20      | 2        | 5.88%   |
| 57      | 1        | 2.94%   |
| 54      | 1        | 2.94%   |
| 42      | 1        | 2.94%   |
| 31      | 1        | 2.94%   |
| 29      | 1        | 2.94%   |
| 23      | 1        | 2.94%   |
| 22      | 1        | 2.94%   |
| 19      | 1        | 2.94%   |
| 14      | 1        | 2.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 29.41%  |
| 401-500     | 8        | 23.53%  |
| Unknown     | 8        | 23.53%  |
| 601-700     | 3        | 8.82%   |
| 1001-1500   | 2        | 5.88%   |
| 351-400     | 1        | 2.94%   |
| 201-300     | 1        | 2.94%   |
| 901-1000    | 1        | 2.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 18       | 56.25%  |
| Unknown | 8        | 25%     |
| 16/10   | 3        | 9.38%   |
| 6/5     | 1        | 3.13%   |
| 4/3     | 1        | 3.13%   |
| 21/9    | 1        | 3.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 32.35%  |
| Unknown        | 8        | 23.53%  |
| 301-350        | 6        | 17.65%  |
| 151-200        | 3        | 8.82%   |
| More than 1000 | 2        | 5.88%   |
| 351-500        | 1        | 2.94%   |
| 251-300        | 1        | 2.94%   |
| 101-110        | 1        | 2.94%   |
| 501-1000       | 1        | 2.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 45.45%  |
| 101-120 | 8        | 24.24%  |
| Unknown | 8        | 24.24%  |
| 1-50    | 1        | 3.03%   |
| 121-160 | 1        | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 29       | 47.54%  |
| 1     | 28       | 45.9%   |
| 2     | 3        | 4.92%   |
| 3     | 1        | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 33       | 44%     |
| Intel                    | 31       | 41.33%  |
| Qualcomm Atheros         | 3        | 4%      |
| Broadcom                 | 3        | 4%      |
| Xiaomi                   | 1        | 1.33%   |
| Ralink Technology        | 1        | 1.33%   |
| Marvell Technology Group | 1        | 1.33%   |
| LG Electronics           | 1        | 1.33%   |
| D-Link System            | 1        | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 26.88%  |
| Intel I211 Gigabit Network Connection                             | 5        | 5.38%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 5.38%   |
| Intel Ethernet Controller I225-V                                  | 4        | 4.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 3.23%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 3.23%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 2.15%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.08%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.08%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 1.08%   |
| Realtek Realtek Bluetooth Adapter                                 | 1        | 1.08%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC              | 1        | 1.08%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 1.08%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 1.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 1.08%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 1.08%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.08%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.08%   |
| LG Optimus Android Phone [USB tethering mode]                     | 1        | 1.08%   |
| Intel Wireless-AC 9260                                            | 1        | 1.08%   |
| Intel Wireless 7260                                               | 1        | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 1.08%   |
| Intel Wi-Fi 6 AX201                                               | 1        | 1.08%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.08%   |
| Intel Ethernet Controller X550                                    | 1        | 1.08%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.08%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.08%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.08%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.08%   |
| Intel Ethernet Connection (13) I219-V                             | 1        | 1.08%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 1.08%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 1.08%   |
| Intel 82599 Ethernet Controller Virtual Function                  | 1        | 1.08%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.08%   |
| Intel 82575GB Gigabit Network Connection                          | 1        | 1.08%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 1.08%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.08%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.08%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 1.08%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 1        | 1.08%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 1        | 1.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 38.1%   |
| Realtek Semiconductor | 7        | 33.33%  |
| Qualcomm Atheros      | 3        | 14.29%  |
| Broadcom              | 2        | 9.52%   |
| Ralink Technology     | 1        | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 3        | 14.29%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 2        | 9.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 4.76%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 1        | 4.76%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                     | 1        | 4.76%   |
| Realtek Realtek Bluetooth Adapter                          | 1        | 4.76%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC       | 1        | 4.76%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 4.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1        | 4.76%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 4.76%   |
| Intel Wireless-AC 9260                                     | 1        | 4.76%   |
| Intel Wireless 7260                                        | 1        | 4.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1        | 4.76%   |
| Intel Wi-Fi 6 AX201                                        | 1        | 4.76%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1        | 4.76%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 4.76%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1        | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 30       | 47.62%  |
| Realtek Semiconductor    | 29       | 46.03%  |
| Xiaomi                   | 1        | 1.59%   |
| Marvell Technology Group | 1        | 1.59%   |
| D-Link System            | 1        | 1.59%   |
| Broadcom                 | 1        | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25       | 35.21%  |
| Intel I211 Gigabit Network Connection                             | 5        | 7.04%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 7.04%   |
| Intel Ethernet Controller I225-V                                  | 4        | 5.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 4.23%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 4.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.41%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 1.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.41%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.41%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.41%   |
| Intel Ethernet Controller X550                                    | 1        | 1.41%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.41%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.41%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.41%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.41%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.41%   |
| Intel Ethernet Connection (13) I219-V                             | 1        | 1.41%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.41%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 1.41%   |
| Intel 82599 Ethernet Controller Virtual Function                  | 1        | 1.41%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.41%   |
| Intel 82575GB Gigabit Network Connection                          | 1        | 1.41%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 1.41%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.41%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.41%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 57       | 75%     |
| WiFi     | 18       | 23.68%  |
| Modem    | 1        | 1.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 54       | 94.74%  |
| WiFi     | 3        | 5.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 49.18%  |
| 2     | 17       | 27.87%  |
| 3     | 6        | 9.84%   |
| 0     | 4        | 6.56%   |
| 5     | 2        | 3.28%   |
| 7     | 1        | 1.64%   |
| 4     | 1        | 1.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 51       | 83.61%  |
| Yes  | 10       | 16.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 54.55%  |
| Realtek Semiconductor           | 2        | 18.18%  |
| Qualcomm Atheros Communications | 1        | 9.09%   |
| Cambridge Silicon Radio         | 1        | 9.09%   |
| ASUSTek Computer                | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 2        | 18.18%  |
| Realtek  Bluetooth Adapter                                  | 1        | 9.09%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1        | 9.09%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1        | 9.09%   |
| Intel Bluetooth wireless interface                          | 1        | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1        | 9.09%   |
| Intel AX201 Bluetooth                                       | 1        | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1        | 9.09%   |
| ASUS Bluetooth USB module                                   | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 34       | 45.33%  |
| Nvidia                      | 18       | 24%     |
| AMD                         | 16       | 21.33%  |
| XMOS                        | 1        | 1.33%   |
| Realtek Semiconductor       | 1        | 1.33%   |
| Razer USA                   | 1        | 1.33%   |
| Kingston Technology         | 1        | 1.33%   |
| FiiO Electronics Technology | 1        | 1.33%   |
| Ensoniq                     | 1        | 1.33%   |
| Cambridge Silicon Radio     | 1        | 1.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6        | 6.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 6        | 6.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 4.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 4.55%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 4.55%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 3.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 3.41%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3        | 3.41%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 3.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 3.41%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 2.27%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 2.27%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 2.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 2.27%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 2.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 2.27%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 2.27%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 2.27%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 2.27%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 2.27%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 2.27%   |
| XMOS XMOS XS1-U8 MFA (ST)                                                         | 1        | 1.14%   |
| Realtek Semiconductor Realtek USB Audio                                           | 1        | 1.14%   |
| Razer USA Razer BlackShark V2 Pro Razer BlackShark V2 Pro                         | 1        | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 1.14%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 1.14%   |
| Nvidia High Definition Audio Controller                                           | 1        | 1.14%   |
| Kingston Technology HyperX 7.1 Audio                                              | 1        | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 1.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1        | 1.14%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1        | 1.14%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 1.14%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 1.14%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 1.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1        | 1.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1        | 1.14%   |
| FiiO Electronics Technology FiiO USB DAC-E10                                      | 1        | 1.14%   |
| Ensoniq 5880B / Creative Labs CT5880                                              | 1        | 1.14%   |
| Cambridge Silicon Radio B10                                                       | 1        | 1.14%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                    | 1        | 1.14%   |
| AMD Navi 10 HDMI Audio                                                            | 1        | 1.14%   |
| AMD FCH Azalia Controller                                                         | 1        | 1.14%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 1        | 1.14%   |
| Unknown                                                                           | 1        | 1.14%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 10       | 16.39%  |
| Samsung Electronics          | 9        | 14.75%  |
| Crucial                      | 8        | 13.11%  |
| SK hynix                     | 6        | 9.84%   |
| Kingston                     | 6        | 9.84%   |
| Micron Technology            | 5        | 8.2%    |
| G.Skill                      | 5        | 8.2%    |
| Unknown                      | 3        | 4.92%   |
| A-DATA Technology            | 2        | 3.28%   |
| Transcend                    | 1        | 1.64%   |
| Qimonda                      | 1        | 1.64%   |
| Patriot Memory (PDP Systems) | 1        | 1.64%   |
| Patriot                      | 1        | 1.64%   |
| Kingmax                      | 1        | 1.64%   |
| Hewlett-Packard              | 1        | 1.64%   |
| Unknown                      | 1        | 1.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 1        | 1.52%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                                 | 1        | 1.52%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 1        | 1.52%   |
| Unknown RAM Module 2GB DIMM                                             | 1        | 1.52%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1066MT/s                     | 1        | 1.52%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s                    | 1        | 1.52%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                    | 1        | 1.52%   |
| SK hynix RAM HMT42GR7CMR4A-G7 16GB DIMM DDR3 1067MT/s                   | 1        | 1.52%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s                    | 1        | 1.52%   |
| SK hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s                    | 1        | 1.52%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s                    | 1        | 1.52%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                    | 1        | 1.52%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 1.52%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1333MT/s                         | 1        | 1.52%   |
| Samsung RAM M393B2G70DB0 16GB DIMM DDR3 1333MT/s                        | 1        | 1.52%   |
| Samsung RAM M391B5273DH0-YH9 4GB DIMM DDR3 1333MT/s                     | 1        | 1.52%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 2667MT/s                    | 1        | 1.52%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s                     | 1        | 1.52%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s                     | 1        | 1.52%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 2666MT/s                     | 1        | 1.52%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s                     | 1        | 1.52%   |
| Qimonda RAM 64T128000EU2.5C2 1GB DIMM DDR2 800MT/s                      | 1        | 1.52%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                          | 1        | 1.52%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1333MT/s                         | 1        | 1.52%   |
| Patriot Memory (PDP Systems) RAM 3733 C17 Series 8GB DIMM DDR4 2133MT/s | 1        | 1.52%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                                | 1        | 1.52%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                     | 1        | 1.52%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s                    | 1        | 1.52%   |
| Micron RAM 4ATF51264AZ-2G3B1 4GB DIMM DDR4 2400MT/s                     | 1        | 1.52%   |
| Micron RAM 36KSF1G72PZ-1 8GB DIMM DDR3 1333MT/s                         | 1        | 1.52%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s                     | 1        | 1.52%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s                  | 1        | 1.52%   |
| Kingston RAM KHX1866C10D3/ 8GB DIMM DDR3 933MT/s                        | 1        | 1.52%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                     | 1        | 1.52%   |
| Kingston RAM CBD24D4U7S1ME-4 4GB DIMM DDR4 2400MT/s                     | 1        | 1.52%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s                   | 1        | 1.52%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB DIMM DDR3 1600MT/s                    | 1        | 1.52%   |
| Kingmax RAM FLFF65F-C8KL9 4GB DIMM DDR3 1333MT/s                        | 1        | 1.52%   |
| HP RAM 647658-081 8GB DIMM DDR3 1333MT/s                                | 1        | 1.52%   |
| G.Skill RAM F4-3600C18-8GTZR 8GB DIMM DDR4 3600MT/s                     | 1        | 1.52%   |
| G.Skill RAM F4-3600C16-8GVKC 8GB DIMM DDR4 2133MT/s                     | 1        | 1.52%   |
| G.Skill RAM F4-3200C16-32GVK 32GB DIMM DDR4 2666MT/s                    | 1        | 1.52%   |
| G.Skill RAM F4-2133C15-8GVR 8GB DIMM DDR4 2133MT/s                      | 1        | 1.52%   |
| G.Skill RAM F3-12800CL7-2GBRM 2GB DIMM DDR3 1600MT/s                    | 1        | 1.52%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s                 | 1        | 1.52%   |
| Crucial RAM CT16G4DFRA266.C16FP 16GB DIMM DDR4 2400MT/s                 | 1        | 1.52%   |
| Crucial RAM CT16G4DFRA266.C16FE 16GB DIMM DDR4 2400MT/s                 | 1        | 1.52%   |
| Crucial RAM CT16G4DFD8213.M16FA 16GB DIMM DDR4 2133MT/s                 | 1        | 1.52%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s                 | 1        | 1.52%   |
| Crucial RAM BLS8G4D240FSBK.8FBD 8GB DIMM DDR4 2400MT/s                  | 1        | 1.52%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s                   | 1        | 1.52%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s                   | 1        | 1.52%   |
| Crucial RAM BL8G32C16U4B.8FE 8GB DIMM DDR4 3200MT/s                     | 1        | 1.52%   |
| Corsair RAM Module 2GB DIMM DDR2 533MT/s                                | 1        | 1.52%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s                   | 1        | 1.52%   |
| Corsair RAM CMSX16GX4M2A3200C22 8GB SODIMM DDR4 3400MT/s                | 1        | 1.52%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s                     | 1        | 1.52%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s                  | 1        | 1.52%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s                  | 1        | 1.52%   |
| Corsair RAM CMK16GX4M2C3600C20 8GB DIMM DDR4 2133MT/s                   | 1        | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 27       | 48.21%  |
| DDR3    | 24       | 42.86%  |
| DDR2    | 2        | 3.57%   |
| Unknown | 2        | 3.57%   |
| DDR     | 1        | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 48       | 87.27%  |
| SODIMM | 7        | 12.73%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 31       | 49.21%  |
| 4096  | 15       | 23.81%  |
| 16384 | 7        | 11.11%  |
| 2048  | 7        | 11.11%  |
| 32768 | 2        | 3.17%   |
| 1024  | 1        | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 14       | 24.56%  |
| 1333    | 8        | 14.04%  |
| 3200    | 7        | 12.28%  |
| 2400    | 5        | 8.77%   |
| 2133    | 5        | 8.77%   |
| 2667    | 3        | 5.26%   |
| 2666    | 3        | 5.26%   |
| 3600    | 2        | 3.51%   |
| 800     | 2        | 3.51%   |
| 3400    | 1        | 1.75%   |
| 2933    | 1        | 1.75%   |
| 1334    | 1        | 1.75%   |
| 1067    | 1        | 1.75%   |
| 1066    | 1        | 1.75%   |
| 933     | 1        | 1.75%   |
| 533     | 1        | 1.75%   |
| Unknown | 1        | 1.75%   |

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
| 1     | 28       | 45.9%   |
| 0     | 20       | 32.79%  |
| 2     | 10       | 16.39%  |
| 3     | 3        | 4.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 37       | 69.81%  |
| Net/wireless             | 5        | 9.43%   |
| Bluetooth                | 5        | 9.43%   |
| Firewire controller      | 3        | 5.66%   |
| Net/ethernet             | 2        | 3.77%   |
| Card reader              | 1        | 1.89%   |

