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

Total: 105

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 59       | 90.77%  |
| arm64 | 3        | 4.62%   |
| arm   | 2        | 3.08%   |
| i386  | 1        | 1.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Console  | 32       | 49.23%  |
| KDE5     | 10       | 15.38%  |
| XFCE     | 9        | 13.85%  |
| TWM      | 3        | 4.62%   |
| Openbox  | 2        | 3.08%   |
| MATE     | 2        | 3.08%   |
| GNOME    | 2        | 3.08%   |
| plasma   | 1        | 1.54%   |
| LXQt     | 1        | 1.54%   |
| LXDE     | 1        | 1.54%   |
| Compton  | 1        | 1.54%   |
| Cinnamon | 1        | 1.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 33       | 50.77%  |
| X11     | 32       | 49.23%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 44       | 67.69%  |
| SDDM    | 10       | 15.38%  |
| XDM     | 4        | 6.15%   |
| SLiM    | 4        | 6.15%   |
| LightDM | 3        | 4.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 40       | 61.54%  |
| en_US   | 8        | 12.31%  |
| ru_RU   | 7        | 10.77%  |
| Unknown | 4        | 6.15%   |
| fr_FR   | 3        | 4.62%   |
| ja_JP   | 1        | 1.54%   |
| en_GB   | 1        | 1.54%   |
| de_DE   | 1        | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 41       | 62.12%  |
| BIOS | 25       | 37.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 41       | 63.08%  |
| Ufs  | 24       | 36.92%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 59       | 90.77%  |
| MBR  | 6        | 9.23%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 16.92%  |
| Gigabyte Technology | 9        | 13.85%  |
| Dell                | 9        | 13.85%  |
| Hewlett-Packard     | 6        | 9.23%   |
| ASRock              | 6        | 9.23%   |
| Unknown             | 5        | 7.69%   |
| Intel               | 4        | 6.15%   |
| MSI                 | 3        | 4.62%   |
| Acer                | 3        | 4.62%   |
| Supermicro          | 1        | 1.54%   |
| PC Engines          | 1        | 1.54%   |
| NITRINOnet          | 1        | 1.54%   |
| NF-M2S              | 1        | 1.54%   |
| MouseComputer       | 1        | 1.54%   |
| GVC                 | 1        | 1.54%   |
| Fujitsu             | 1        | 1.54%   |
| ASRockRack          | 1        | 1.54%   |
| AMI                 | 1        | 1.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 5        | 7.69%   |
| ASUS All Series                    | 3        | 4.62%   |
| MSI MS-7817                        | 2        | 3.08%   |
| Supermicro Icebreaker 4824         | 1        | 1.54%   |
| PC Engines APU3                    | 1        | 1.54%   |
| NITRINOnet M360RUS56               | 1        | 1.54%   |
| NF-M2S ABIT                        | 1        | 1.54%   |
| MSI MS-7D09                        | 1        | 1.54%   |
| MouseComputer B360M                | 1        | 1.54%   |
| Intel X79 V2.72A                   | 1        | 1.54%   |
| Intel Q3XXG4-P V1.0                | 1        | 1.54%   |
| Intel DN2820FYK H24582-203         | 1        | 1.54%   |
| Intel D945GCLF2 AAE46416-104       | 1        | 1.54%   |
| HP Z620 Workstation                | 1        | 1.54%   |
| HP ProLiant ML310e Gen8 v2         | 1        | 1.54%   |
| HP ProDesk 600 G1 DM               | 1        | 1.54%   |
| HP EliteDesk 800 G1 DM             | 1        | 1.54%   |
| HP Desktop M01-F0xxx               | 1        | 1.54%   |
| HP Compaq dc7900 Small Form Factor | 1        | 1.54%   |
| GVC EQUIUM 3200M                   | 1        | 1.54%   |
| Gigabyte Z370M D3H                 | 1        | 1.54%   |
| Gigabyte X470 AORUS GAMING 7 WIFI  | 1        | 1.54%   |
| Gigabyte P85-D3                    | 1        | 1.54%   |
| Gigabyte H97M-HD3                  | 1        | 1.54%   |
| Gigabyte H61MA-D3V                 | 1        | 1.54%   |
| Gigabyte GB-BSi3-1115G4            | 1        | 1.54%   |
| Gigabyte F2A75M-D3H                | 1        | 1.54%   |
| Gigabyte B550M AORUS PRO-P         | 1        | 1.54%   |
| Gigabyte B450M DS3H                | 1        | 1.54%   |
| Fujitsu D3401-H2 S26361-D3401-H2   | 1        | 1.54%   |
| Dell Precision T3600               | 1        | 1.54%   |
| Dell OptiPlex 7050                 | 1        | 1.54%   |
| Dell OptiPlex 7010                 | 1        | 1.54%   |
| Dell OptiPlex 5040                 | 1        | 1.54%   |
| Dell OptiPlex 3080                 | 1        | 1.54%   |
| Dell OptiPlex 3020                 | 1        | 1.54%   |
| Dell OptiPlex 3010                 | 1        | 1.54%   |
| Dell Inspiron 3668                 | 1        | 1.54%   |
| Dell G5 5090                       | 1        | 1.54%   |
| ASUS ROG STRIX X570-F GAMING       | 1        | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Dell OptiPlex            | 6        | 9.23%   |
| Unknown                  | 5        | 7.69%   |
| ASUS ROG                 | 3        | 4.62%   |
| ASUS PRIME               | 3        | 4.62%   |
| ASUS All                 | 3        | 4.62%   |
| MSI MS-7817              | 2        | 3.08%   |
| Supermicro Icebreaker    | 1        | 1.54%   |
| PC Engines APU3          | 1        | 1.54%   |
| NITRINOnet M360RUS56     | 1        | 1.54%   |
| NF-M2S ABIT              | 1        | 1.54%   |
| MSI MS-7D09              | 1        | 1.54%   |
| MouseComputer B360M      | 1        | 1.54%   |
| Intel X79                | 1        | 1.54%   |
| Intel Q3XXG4-P           | 1        | 1.54%   |
| Intel DN2820FYK          | 1        | 1.54%   |
| Intel D945GCLF2          | 1        | 1.54%   |
| HP Z620                  | 1        | 1.54%   |
| HP ProLiant              | 1        | 1.54%   |
| HP ProDesk               | 1        | 1.54%   |
| HP EliteDesk             | 1        | 1.54%   |
| HP Desktop               | 1        | 1.54%   |
| HP Compaq                | 1        | 1.54%   |
| GVC EQUIUM               | 1        | 1.54%   |
| Gigabyte Z370M           | 1        | 1.54%   |
| Gigabyte X470            | 1        | 1.54%   |
| Gigabyte P85-D3          | 1        | 1.54%   |
| Gigabyte H97M-HD3        | 1        | 1.54%   |
| Gigabyte H61MA-D3V       | 1        | 1.54%   |
| Gigabyte GB-BSi3-1115G4  | 1        | 1.54%   |
| Gigabyte F2A75M-D3H      | 1        | 1.54%   |
| Gigabyte B550M           | 1        | 1.54%   |
| Gigabyte B450M           | 1        | 1.54%   |
| Fujitsu D3401-H2         | 1        | 1.54%   |
| Dell Precision           | 1        | 1.54%   |
| Dell Inspiron            | 1        | 1.54%   |
| Dell G5                  | 1        | 1.54%   |
| ASUS P5Q-E               | 1        | 1.54%   |
| ASUS Maximus             | 1        | 1.54%   |
| ASRockRack E3C242D4U2-2T | 1        | 1.54%   |
| ASRock Z490M             | 1        | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 9        | 13.85%  |
| 2014    | 8        | 12.31%  |
| 2019    | 7        | 10.77%  |
| 2021    | 6        | 9.23%   |
| Unknown | 6        | 9.23%   |
| 2022    | 5        | 7.69%   |
| 2018    | 5        | 7.69%   |
| 2013    | 4        | 6.15%   |
| 2017    | 3        | 4.62%   |
| 2016    | 3        | 4.62%   |
| 2008    | 3        | 4.62%   |
| 2012    | 2        | 3.08%   |
| 2015    | 1        | 1.54%   |
| 2011    | 1        | 1.54%   |
| 2010    | 1        | 1.54%   |
| 2009    | 1        | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 65       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 64       | 98.46%  |
| Yes  | 1        | 1.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 19       | 28.79%  |
| 16.01-24.0  | 17       | 25.76%  |
| 32.01-64.0  | 8        | 12.12%  |
| 64.01-256.0 | 7        | 10.61%  |
| 4.01-8.0    | 4        | 6.06%   |
| 2.01-3.0    | 3        | 4.55%   |
| 0.01-0.5    | 3        | 4.55%   |
| 3.01-4.0    | 2        | 3.03%   |
| 24.01-32.0  | 2        | 3.03%   |
| 0.51-1.0    | 1        | 1.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 24       | 36.36%  |
| 0.51-1.0 | 21       | 31.82%  |
| 1.01-2.0 | 11       | 16.67%  |
| 2.01-3.0 | 4        | 6.06%   |
| 0        | 4        | 6.06%   |
| 3.01-4.0 | 2        | 3.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 27.27%  |
| 2      | 15       | 22.73%  |
| 3      | 10       | 15.15%  |
| 4      | 8        | 12.12%  |
| 0      | 7        | 10.61%  |
| 8      | 2        | 3.03%   |
| 6      | 2        | 3.03%   |
| 18     | 1        | 1.52%   |
| 15     | 1        | 1.52%   |
| 10     | 1        | 1.52%   |
| 5      | 1        | 1.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 45       | 69.23%  |
| Yes       | 20       | 30.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 59       | 90.77%  |
| No        | 6        | 9.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 72.31%  |
| Yes       | 18       | 27.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 83.08%  |
| Yes       | 11       | 16.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 17       | 26.15%  |
| Germany     | 10       | 15.38%  |
| Russia      | 9        | 13.85%  |
| France      | 5        | 7.69%   |
| Spain       | 4        | 6.15%   |
| Canada      | 3        | 4.62%   |
| New Zealand | 2        | 3.08%   |
| Netherlands | 2        | 3.08%   |
| Czechia     | 2        | 3.08%   |
| Austria     | 2        | 3.08%   |
| Australia   | 2        | 3.08%   |
| Thailand    | 1        | 1.54%   |
| Taiwan      | 1        | 1.54%   |
| Japan       | 1        | 1.54%   |
| Ireland     | 1        | 1.54%   |
| Hungary     | 1        | 1.54%   |
| Croatia     | 1        | 1.54%   |
| Belgium     | 1        | 1.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Frisco                  | 4        | 6.06%   |
| Ozersk                  | 3        | 4.55%   |
| Moscow                  | 3        | 4.55%   |
| Wellington              | 2        | 3.03%   |
| Tamm                    | 2        | 3.03%   |
| Redmond                 | 2        | 3.03%   |
| Omaha                   | 2        | 3.03%   |
| Madrid                  | 2        | 3.03%   |
| Brno                    | 2        | 3.03%   |
| Zagreb                  | 1        | 1.52%   |
| Yashio                  | 1        | 1.52%   |
| Wenatchee               | 1        | 1.52%   |
| Waldbrunn               | 1        | 1.52%   |
| Vienna                  | 1        | 1.52%   |
| Vaulx-en-Velin          | 1        | 1.52%   |
| Valladolid              | 1        | 1.52%   |
| Toronto                 | 1        | 1.52%   |
| Tiel                    | 1        | 1.52%   |
| Taipei                  | 1        | 1.52%   |
| Sydney                  | 1        | 1.52%   |
| St. Albert              | 1        | 1.52%   |
| St Petersburg           | 1        | 1.52%   |
| Sarasota                | 1        | 1.52%   |
| Saarbrücken            | 1        | 1.52%   |
| Poperinge               | 1        | 1.52%   |
| Pluvigner               | 1        | 1.52%   |
| Paris                   | 1        | 1.52%   |
| Neustadt am Ruebenberge | 1        | 1.52%   |
| Nakhodka                | 1        | 1.52%   |
| Münster                | 1        | 1.52%   |
| Mossingen               | 1        | 1.52%   |
| Montreal                | 1        | 1.52%   |
| Methuen                 | 1        | 1.52%   |
| Medford                 | 1        | 1.52%   |
| Marseille               | 1        | 1.52%   |
| Ludwigsburg             | 1        | 1.52%   |
| Lower Hutt              | 1        | 1.52%   |
| Green Valley            | 1        | 1.52%   |
| Gmunden                 | 1        | 1.52%   |
| Falkenstein             | 1        | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 29       | 60     | 26.85%  |
| Samsung Electronics | 20       | 43     | 18.52%  |
| Seagate             | 18       | 51     | 16.67%  |
| Toshiba             | 7        | 14     | 6.48%   |
| Crucial             | 6        | 9      | 5.56%   |
| Kingston            | 5        | 5      | 4.63%   |
| Intel               | 5        | 7      | 4.63%   |
| Hewlett-Packard     | 2        | 2      | 1.85%   |
| A-DATA Technology   | 2        | 2      | 1.85%   |
| Verbatim            | 1        | 1      | 0.93%   |
| SPCC                | 1        | 1      | 0.93%   |
| SK hynix            | 1        | 1      | 0.93%   |
| SanDisk             | 1        | 1      | 0.93%   |
| PNY                 | 1        | 2      | 0.93%   |
| ORICO               | 1        | 1      | 0.93%   |
| OCZ                 | 1        | 1      | 0.93%   |
| Micron Technology   | 1        | 2      | 0.93%   |
| LITEONIT            | 1        | 1      | 0.93%   |
| Hitachi             | 1        | 1      | 0.93%   |
| Hikvision           | 1        | 1      | 0.93%   |
| HGST                | 1        | 1      | 0.93%   |
| Gigabyte Technology | 1        | 1      | 0.93%   |
| China               | 1        | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB       | 4        | 2.92%   |
| Seagate ST1000DM010-2EP102 1TB | 3        | 2.19%   |
| Samsung SSD 850 EVO 500GB      | 3        | 2.19%   |
| WDC WD5000LPLX-00ZNTT0 500GB   | 2        | 1.46%   |
| WDC WD30EFRX-68EUZN0 3TB       | 2        | 1.46%   |
| Seagate ST4000DM000-1F2168 4TB | 2        | 1.46%   |
| Samsung SSD 970 EVO 1TB        | 2        | 1.46%   |
| Samsung SSD 870 QVO 2TB        | 2        | 1.46%   |
| Samsung SSD 840 EVO 120GB      | 2        | 1.46%   |
| Kingston SA400S37120G 120GB    | 2        | 1.46%   |
| Intel SSDSC2CT060A3 64GB       | 2        | 1.46%   |
| Crucial CT240BX500SSD1 240GB   | 2        | 1.46%   |
| A-DATA SU650 240GB             | 2        | 1.46%   |
| WDC WDS500G1B0A-00H9H0 500GB   | 1        | 0.73%   |
| WDC WDS100T2B0A-00SM50 1TB     | 1        | 0.73%   |
| WDC WDBA3V5000ANC-WRSN 500GB   | 1        | 0.73%   |
| WDC WD80EZZX-11CSGA0 8TB       | 1        | 0.73%   |
| WDC WD80EZAZ-11TDBA0 8TB       | 1        | 0.73%   |
| WDC WD80EMZZ-00TBGA0 8TB       | 1        | 0.73%   |
| WDC WD80EFBX-68AZZN0 8TB       | 1        | 0.73%   |
| WDC WD8003FFBX-68B9AN0 8TB     | 1        | 0.73%   |
| WDC WD60EFRX-68L0BN1 6TB       | 1        | 0.73%   |
| WDC WD5000LUCT-63Y8HY0 500GB   | 1        | 0.73%   |
| WDC WD5000BEVT-22ZAT0 500GB    | 1        | 0.73%   |
| WDC WD40EZRZ-22GXCB0 4TB       | 1        | 0.73%   |
| WDC WD4003FRYZ-01F0DB0 4TB     | 1        | 0.73%   |
| WDC WD30EFRX-68N32N0 3TB       | 1        | 0.73%   |
| WDC WD30EFRX-68AX9N0 3TB       | 1        | 0.73%   |
| WDC WD20NMVW-11EDZS2 2TB       | 1        | 0.73%   |
| WDC WD20NMVW-11AV3S2 2TB       | 1        | 0.73%   |
| WDC WD20EARX-00PASB0 2TB       | 1        | 0.73%   |
| WDC WD2003FYYS-18W0B0 2TB      | 1        | 0.73%   |
| WDC WD1600AAJS-60M0A0 160GB    | 1        | 0.73%   |
| WDC WD15EADS-00P8B0 1.5TB      | 1        | 0.73%   |
| WDC WD140EFGX-68B0GN0 14TB     | 1        | 0.73%   |
| WDC WD10EZEX-60WN4A0 1TB       | 1        | 0.73%   |
| WDC WD10EZEX-60M2NA0 1TB       | 1        | 0.73%   |
| WDC WD10EZEX-00RKKA0 1TB       | 1        | 0.73%   |
| WDC WD10EZEX-00MFCA0 1TB       | 1        | 0.73%   |
| WDC WD10EAVS-00D7B1 1TB        | 1        | 0.73%   |

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
| Samsung Electronics | 14       | 31     | 33.33%  |
| Crucial             | 5        | 5      | 11.9%   |
| Intel               | 4        | 6      | 9.52%   |
| Kingston            | 3        | 3      | 7.14%   |
| WDC                 | 2        | 2      | 4.76%   |
| A-DATA Technology   | 2        | 2      | 4.76%   |
| Verbatim            | 1        | 1      | 2.38%   |
| Toshiba             | 1        | 1      | 2.38%   |
| SPCC                | 1        | 1      | 2.38%   |
| SK hynix            | 1        | 1      | 2.38%   |
| SanDisk             | 1        | 1      | 2.38%   |
| PNY                 | 1        | 2      | 2.38%   |
| ORICO               | 1        | 1      | 2.38%   |
| OCZ                 | 1        | 1      | 2.38%   |
| Micron Technology   | 1        | 2      | 2.38%   |
| LITEONIT            | 1        | 1      | 2.38%   |
| Hikvision           | 1        | 1      | 2.38%   |
| China               | 1        | 1      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 38       | 123    | 42.22%  |
| SSD  | 36       | 63     | 40%     |
| NVMe | 16       | 23     | 17.78%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 55       | 186    | 77.46%  |
| NVMe | 16       | 23     | 22.54%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 34       | 52     | 40.48%  |
| 0.51-1.0   | 26       | 39     | 30.95%  |
| 1.01-2.0   | 9        | 29     | 10.71%  |
| 3.01-4.0   | 6        | 16     | 7.14%   |
| 4.01-10.0  | 4        | 29     | 4.76%   |
| 2.01-3.0   | 3        | 16     | 3.57%   |
| 10.01-20.0 | 2        | 5      | 2.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 19       | 28.79%  |
| 501-1000       | 13       | 19.7%   |
| 251-500        | 10       | 15.15%  |
| 21-50          | 9        | 13.64%  |
| 51-100         | 5        | 7.58%   |
| 2001-3000      | 3        | 4.55%   |
| 1-20           | 3        | 4.55%   |
| 1001-2000      | 2        | 3.03%   |
| More than 3000 | 1        | 1.52%   |
| Unknown        | 1        | 1.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 54       | 83.08%  |
| 21-50          | 5        | 7.69%   |
| 51-100         | 2        | 3.08%   |
| More than 3000 | 1        | 1.54%   |
| 251-500        | 1        | 1.54%   |
| 501-1000       | 1        | 1.54%   |
| Unknown        | 1        | 1.54%   |

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
| Works    | 55       | 190    | 84.62%  |
| Malfunc  | 8        | 13     | 12.31%  |
| Detected | 2        | 6      | 3.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 47       | 54.02%  |
| AMD                         | 11       | 12.64%  |
| Samsung Electronics         | 7        | 8.05%   |
| SanDisk                     | 4        | 4.6%    |
| Marvell Technology Group    | 3        | 3.45%   |
| Broadcom / LSI              | 3        | 3.45%   |
| ASMedia Technology          | 3        | 3.45%   |
| Micron/Crucial Technology   | 2        | 2.3%    |
| Kingston Technology Company | 2        | 2.3%    |
| Silicon Motion              | 1        | 1.15%   |
| Silicon Image               | 1        | 1.15%   |
| Seagate Technology          | 1        | 1.15%   |
| Phison Electronics          | 1        | 1.15%   |
| Nvidia                      | 1        | 1.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9        | 9.09%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6        | 6.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 5.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5        | 5.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 4.04%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 4.04%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3        | 3.03%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 3        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 3.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 3.03%   |
| Broadcom / LSI SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]                   | 3        | 3.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 2.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 2.02%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2        | 2.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 2.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2        | 2.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2        | 2.02%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 2.02%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2        | 2.02%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 2.02%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 2.02%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 1.01%   |
| Silicon Image SiI 3124 PCI-X Serial ATA Controller                             | 1        | 1.01%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 1.01%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 1.01%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 1.01%   |
| Phison NVMe Storage Controller                                                 | 1        | 1.01%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.01%   |
| Nvidia MCP61 IDE                                                               | 1        | 1.01%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 1.01%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                   | 1        | 1.01%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 1.01%   |
| Kingston Company KC2000 NVMe SSD                                               | 1        | 1.01%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 1.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1        | 1.01%   |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 1.01%   |
| Intel SSD 660P Series                                                          | 1        | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 1.01%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 1.01%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 53       | 63.1%   |
| NVMe | 16       | 19.05%  |
| IDE  | 8        | 9.52%   |
| SAS  | 4        | 4.76%   |
| RAID | 3        | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 47       | 72.31%  |
| AMD    | 13       | 20%     |
| ARM    | 5        | 7.69%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| ARM Cortex-A53 r0p4                    | 3        | 4.55%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 3        | 4.55%   |
| Intel Core i7-7700 CPU @ 3.60GHz       | 2        | 3.03%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 2        | 3.03%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 2        | 3.03%   |
| ARM ARM1176 r0p7 (ECO: 0x00000000)     | 2        | 3.03%   |
| Intel Xeon E-2136 CPU @ 3.30GHz        | 1        | 1.52%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz       | 1        | 1.52%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz    | 1        | 1.52%   |
| Intel Xeon CPU E5-2650 0 @ 2.00GH      | 1        | 1.52%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz    | 1        | 1.52%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz    | 1        | 1.52%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz    | 1        | 1.52%   |
| Intel Pentium II                       | 1        | 1.52%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz | 1        | 1.52%   |
| Intel Pentium CPU G3240T @ 2.70GHz     | 1        | 1.52%   |
| Intel Pentium CPU G3220 @ 3.00GHz      | 1        | 1.52%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 1        | 1.52%   |
| Intel Core i7-6700K CPU @ 4.00GHz      | 1        | 1.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 1        | 1.52%   |
| Intel Core i7-4785T CPU @ 2.20GHz      | 1        | 1.52%   |
| Intel Core i7-2600K CPU @ 3.40GHz      | 1        | 1.52%   |
| Intel Core i7-10700K CPU @ 3.80GHz     | 1        | 1.52%   |
| Intel Core i5-9400T CPU @ 1.80GHz      | 1        | 1.52%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 1        | 1.52%   |
| Intel Core i5-7500 CPU @ 3.40GHz       | 1        | 1.52%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 1        | 1.52%   |
| Intel Core i5-5250U CPU @ 1.60GHz      | 1        | 1.52%   |
| Intel Core i5-4690 CPU @ 3.50GHz       | 1        | 1.52%   |
| Intel Core i5-4670K CPU @ 3.40GHz      | 1        | 1.52%   |
| Intel Core i5-4590T CPU @ 2.00GHz      | 1        | 1.52%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 1        | 1.52%   |
| Intel Core i5-4440 CPU @ 3.10GHz       | 1        | 1.52%   |
| Intel Core i5-3570 CPU @ 3.40GHz       | 1        | 1.52%   |
| Intel Core i5-2400 CPU                 | 1        | 1.52%   |
| Intel Core i5-10600K CPU @ 4.10GHz     | 1        | 1.52%   |
| Intel Core i5-10400 CPU @ 2.90GHz      | 1        | 1.52%   |
| Intel Core i3-7100 CPU @ 3.90GHz       | 1        | 1.52%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 1        | 1.52%   |
| Intel Core i3 CPU 540 @ 3.07GHz        | 1        | 1.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| Intel Core i5      | 17       | 26.15%  |
| Intel Core i7      | 8        | 12.31%  |
| Intel Xeon         | 7        | 10.77%  |
| Other              | 4        | 6.15%   |
| AMD Ryzen 5        | 4        | 6.15%   |
| Intel Pentium      | 3        | 4.62%   |
| Intel Core i3      | 3        | 4.62%   |
| Intel Atom         | 3        | 4.62%   |
| ARM Cortex         | 3        | 4.62%   |
| AMD Ryzen 9        | 2        | 3.08%   |
| AMD Ryzen 7        | 2        | 3.08%   |
| Intel Pentium Gold | 1        | 1.54%   |
| Intel Core 2 Quad  | 1        | 1.54%   |
| Intel Core 2 Duo   | 1        | 1.54%   |
| Intel Celeron      | 1        | 1.54%   |
| AMD Ryzen 7 PRO    | 1        | 1.54%   |
| AMD Ryzen 3        | 1        | 1.54%   |
| AMD GX             | 1        | 1.54%   |
| AMD Athlon 64 X2   | 1        | 1.54%   |
| AMD A10            | 1        | 1.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 23       | 35.38%  |
| 2       | 11       | 16.92%  |
| 6       | 8        | 12.31%  |
| 8       | 6        | 9.23%   |
| Unknown | 6        | 9.23%   |
| 16      | 4        | 6.15%   |
| 12      | 4        | 6.15%   |
| 24      | 2        | 3.08%   |
| 1       | 1        | 1.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 59       | 90.77%  |
| Unknown | 5        | 7.69%   |
| 2       | 1        | 1.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 36       | 55.38%  |
| 2       | 22       | 33.85%  |
| Unknown | 7        | 10.77%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 11       | 16.67%  |
| Haswell     | 11       | 16.67%  |
| Unknown     | 6        | 9.09%   |
| IvyBridge   | 5        | 7.58%   |
| Zen 3       | 4        | 6.06%   |
| SandyBridge | 4        | 6.06%   |
| CometLake   | 4        | 6.06%   |
| Zen 2       | 3        | 4.55%   |
| Zen+        | 2        | 3.03%   |
| Skylake     | 2        | 3.03%   |
| Silvermont  | 2        | 3.03%   |
| Bonnell     | 2        | 3.03%   |
| Zen         | 1        | 1.52%   |
| Westmere    | 1        | 1.52%   |
| TigerLake   | 1        | 1.52%   |
| Puma        | 1        | 1.52%   |
| Piledriver  | 1        | 1.52%   |
| Penryn      | 1        | 1.52%   |
| P6          | 1        | 1.52%   |
| K8 Hammer   | 1        | 1.52%   |
| Core        | 1        | 1.52%   |
| Broadwell   | 1        | 1.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 28       | 45.9%   |
| Nvidia                               | 18       | 29.51%  |
| AMD                                  | 11       | 18.03%  |
| Matrox Electronics Systems           | 2        | 3.28%   |
| NVidia / SGS Thomson (Joint Venture) | 1        | 1.64%   |
| ASPEED Technology                    | 1        | 1.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 12.7%   |
| Intel HD Graphics 630                                                       | 3        | 4.76%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3        | 4.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 4.76%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 3.17%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 3.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 3.17%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 3.17%   |
| AMD Cezanne                                                                 | 2        | 3.17%   |
| AMD Caicos XTX [Radeon HD 8490 / R5 235X OEM]                               | 2        | 3.17%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.59%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1        | 1.59%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 1.59%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.59%   |
| Nvidia GK208B [GeForce GT 730]                                              | 1        | 1.59%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.59%   |
| Nvidia GF108 [GeForce GT 430]                                               | 1        | 1.59%   |
| NVidia / SGS Thomson (Joint Venture) Riva128                                | 1        | 1.59%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 1        | 1.59%   |
| Matrox Electronics Systems MGA G200EH                                       | 1        | 1.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 1.59%   |
| Intel Tiger Lake UHD Graphics                                               | 1        | 1.59%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 1        | 1.59%   |
| Intel HD Graphics 6000                                                      | 1        | 1.59%   |
| Intel HD Graphics 530                                                       | 1        | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 1.59%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 1.59%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 1        | 1.59%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 1        | 1.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.59%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 1.59%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 1.59%   |
| AMD Turks PRO [Radeon HD 7570]                                              | 1        | 1.59%   |
| AMD RV370 [Radeon X300/X550/X1050 Series] (Secondary)                       | 1        | 1.59%   |
| AMD RV370 [Radeon X300/X550/X1050 Series]                                   | 1        | 1.59%   |
| AMD Renoir                                                                  | 1        | 1.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| 1 x Intel                                | 26       | 40%     |
| 1 x Nvidia                               | 16       | 24.62%  |
| 1 x AMD                                  | 10       | 15.38%  |
| Other                                    | 6        | 9.23%   |
| 1 x Matrox                               | 2        | 3.08%   |
| Intel + Nvidia                           | 2        | 3.08%   |
| 2 x AMD                                  | 1        | 1.54%   |
| 1 x NVidia / SGS Thomson (Joint Venture) | 1        | 1.54%   |
| 1 x ASPEED                               | 1        | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 43       | 66.15%  |
| Proprietary | 15       | 23.08%  |
| Unknown     | 7        | 10.77%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 45       | 69.23%  |
| 1.01-2.0   | 6        | 9.23%   |
| 0.51-1.0   | 6        | 9.23%   |
| 7.01-8.0   | 2        | 3.08%   |
| 5.01-6.0   | 2        | 3.08%   |
| 3.01-4.0   | 2        | 3.08%   |
| 2.01-3.0   | 1        | 1.54%   |
| 0.01-0.5   | 1        | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 9        | 24.32%  |
| Dell                | 4        | 10.81%  |
| Acer                | 4        | 10.81%  |
| Goldstar            | 3        | 8.11%   |
| Philips             | 2        | 5.41%   |
| Lenovo              | 2        | 5.41%   |
| AOC                 | 2        | 5.41%   |
| ViewSonic           | 1        | 2.7%    |
| Vestel Elektronik   | 1        | 2.7%    |
| Sceptre Tech        | 1        | 2.7%    |
| Panasonic           | 1        | 2.7%    |
| LG Electronics      | 1        | 2.7%    |
| IOD                 | 1        | 2.7%    |
| Iiyama              | 1        | 2.7%    |
| Idek Iiyama         | 1        | 2.7%    |
| Compal              | 1        | 2.7%    |
| BenQ                | 1        | 2.7%    |
| ASUSTek Computer    | 1        | 2.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch   | 2        | 5.26%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch            | 1        | 2.63%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1        | 2.63%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x290mm 29.5-inch         | 1        | 2.63%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 380x300mm 19.1-inch    | 1        | 2.63%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 480x270mm 21.7-inch      | 1        | 2.63%   |
| Samsung Electronics LCD Monitor T27C370 1920x1080                      | 1        | 2.63%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 1        | 2.63%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                   | 1        | 2.63%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 2.63%   |
| Samsung Electronics LCD Monitor S24R35x 1920x1080                      | 1        | 2.63%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 2.63%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 1        | 2.63%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                    | 1        | 2.63%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1        | 2.63%   |
| Lenovo LEN T24i-10 LEN61CE 1920x1080 530x300mm 24.0-inch               | 1        | 2.63%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1        | 2.63%   |
| IOD KH270V IOD1B3B 1920x1080 600x340mm 27.2-inch                       | 1        | 2.63%   |
| Iiyama PL2483H IVM6138 1920x1080 530x300mm 24.0-inch                   | 1        | 2.63%   |
| Idek Iiyama LCD Monitor PL2730Q 2560x1440                              | 1        | 2.63%   |
| Goldstar LG ULTRAGEAR GSM776E 2560x1440 700x390mm 31.5-inch            | 1        | 2.63%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1        | 2.63%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                  | 1        | 2.63%   |
| Dell UP2716D DEL40DD 2560x1440 600x340mm 27.2-inch                     | 1        | 2.63%   |
| Dell LCD Monitor SP2309W 2048x1152                                     | 1        | 2.63%   |
| Dell IN2020M DELF030 1600x900 440x250mm 19.9-inch                      | 1        | 2.63%   |
| Dell E151FPp DEL7006 1024x768 300x230mm 14.9-inch                      | 1        | 2.63%   |
| Compal LCD Monitor WOR2760 2560x1440 600x340mm 27.2-inch               | 1        | 2.63%   |
| BenQ LCD Monitor PD3200Q                                               | 1        | 2.63%   |
| BenQ LCD Monitor GW2765                                                | 1        | 2.63%   |
| ASUSTek Computer PA248QV AUS2487 1920x1200 520x320mm 24.0-inch         | 1        | 2.63%   |
| AOC U28P2G6B AOC2802 3840x2160 620x340mm 27.8-inch                     | 1        | 2.63%   |
| AOC 24P1X AOC2401 1920x1200 520x320mm 24.0-inch                        | 1        | 2.63%   |
| Acer VW237Q ACR06B9 1920x1200 490x300mm 22.6-inch                      | 1        | 2.63%   |
| Acer RG270 ACR061E 1920x1080 600x340mm 27.2-inch                       | 1        | 2.63%   |
| Acer H223HQ ACR0086 1920x1080 480x270mm 21.7-inch                      | 1        | 2.63%   |
| Acer AL1916 ACR077C 1280x1024 380x310mm 19.3-inch                      | 1        | 2.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 15       | 41.67%  |
| 2560x1440 (QHD)    | 5        | 13.89%  |
| 1920x1200 (WUXGA)  | 3        | 8.33%   |
| 1280x1024 (SXGA)   | 3        | 8.33%   |
| 3840x2160 (4K)     | 2        | 5.56%   |
| 1680x1050 (WSXGA+) | 2        | 5.56%   |
| 2560x1080          | 1        | 2.78%   |
| 2048x1152          | 1        | 2.78%   |
| 1920x540           | 1        | 2.78%   |
| 1600x900 (HD+)     | 1        | 2.78%   |
| 1024x768 (XGA)     | 1        | 2.78%   |
| Unknown            | 1        | 2.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 22.22%  |
| 24      | 6        | 16.67%  |
| 27      | 5        | 13.89%  |
| 21      | 5        | 13.89%  |
| 20      | 2        | 5.56%   |
| 19      | 2        | 5.56%   |
| 57      | 1        | 2.78%   |
| 54      | 1        | 2.78%   |
| 42      | 1        | 2.78%   |
| 31      | 1        | 2.78%   |
| 29      | 1        | 2.78%   |
| 23      | 1        | 2.78%   |
| 22      | 1        | 2.78%   |
| 14      | 1        | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 11       | 30.56%  |
| 401-500     | 8        | 22.22%  |
| Unknown     | 8        | 22.22%  |
| 601-700     | 3        | 8.33%   |
| 351-400     | 2        | 5.56%   |
| 1001-1500   | 2        | 5.56%   |
| 201-300     | 1        | 2.78%   |
| 901-1000    | 1        | 2.78%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 55.88%  |
| Unknown | 8        | 23.53%  |
| 16/10   | 3        | 8.82%   |
| 6/5     | 1        | 2.94%   |
| 5/4     | 1        | 2.94%   |
| 4/3     | 1        | 2.94%   |
| 21/9    | 1        | 2.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 12       | 33.33%  |
| Unknown        | 8        | 22.22%  |
| 301-350        | 6        | 16.67%  |
| 151-200        | 4        | 11.11%  |
| More than 1000 | 2        | 5.56%   |
| 351-500        | 1        | 2.78%   |
| 251-300        | 1        | 2.78%   |
| 101-110        | 1        | 2.78%   |
| 501-1000       | 1        | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 17       | 48.57%  |
| 101-120 | 8        | 22.86%  |
| Unknown | 8        | 22.86%  |
| 1-50    | 1        | 2.86%   |
| 121-160 | 1        | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 31       | 47.69%  |
| 1     | 30       | 46.15%  |
| 2     | 3        | 4.62%   |
| 3     | 1        | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 34       | 43.04%  |
| Intel                    | 33       | 41.77%  |
| Qualcomm Atheros         | 3        | 3.8%    |
| Broadcom                 | 3        | 3.8%    |
| Xiaomi                   | 1        | 1.27%   |
| Ralink Technology        | 1        | 1.27%   |
| Marvell Technology Group | 1        | 1.27%   |
| LG Electronics           | 1        | 1.27%   |
| IMC Networks             | 1        | 1.27%   |
| D-Link System            | 1        | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26       | 26.8%   |
| Intel I211 Gigabit Network Connection                             | 6        | 6.19%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 5.15%   |
| Intel Ethernet Controller I225-V                                  | 4        | 4.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 3.09%   |
| Intel Wi-Fi 6 AX200                                               | 3        | 3.09%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 3.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 3.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 2.06%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.03%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.03%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1        | 1.03%   |
| Realtek Realtek Bluetooth Adapter                                 | 1        | 1.03%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC              | 1        | 1.03%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 1.03%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1        | 1.03%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1        | 1.03%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1        | 1.03%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.03%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.03%   |
| LG Optimus Android Phone [USB tethering mode]                     | 1        | 1.03%   |
| Intel Wireless-AC 9260                                            | 1        | 1.03%   |
| Intel Wireless 7260                                               | 1        | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 1.03%   |
| Intel Wi-Fi 6 AX201                                               | 1        | 1.03%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.03%   |
| Intel Ethernet Controller X550                                    | 1        | 1.03%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.03%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.03%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.03%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.03%   |
| Intel Ethernet Connection (13) I219-V                             | 1        | 1.03%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1        | 1.03%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 1.03%   |
| Intel 82599 Ethernet Controller Virtual Function                  | 1        | 1.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 36.36%  |
| Realtek Semiconductor | 7        | 31.82%  |
| Qualcomm Atheros      | 3        | 13.64%  |
| Broadcom              | 2        | 9.09%   |
| Ralink Technology     | 1        | 4.55%   |
| IMC Networks          | 1        | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 3        | 13.64%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 2        | 9.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 1        | 4.55%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 1        | 4.55%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                     | 1        | 4.55%   |
| Realtek Realtek Bluetooth Adapter                          | 1        | 4.55%   |
| Realtek Realtek 8811CU Wireless LAN 802.11ac USB NIC       | 1        | 4.55%   |
| Ralink RT5572 Wireless Adapter                             | 1        | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1        | 4.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1        | 4.55%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter           | 1        | 4.55%   |
| Intel Wireless-AC 9260                                     | 1        | 4.55%   |
| Intel Wireless 7260                                        | 1        | 4.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1        | 4.55%   |
| Intel Wi-Fi 6 AX201                                        | 1        | 4.55%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 1        | 4.55%   |
| IMC Networks 802.11 n/g/b Wireless LAN USB Mini-Card       | 1        | 4.55%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 1        | 4.55%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter         | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 32       | 48.48%  |
| Realtek Semiconductor    | 30       | 45.45%  |
| Xiaomi                   | 1        | 1.52%   |
| Marvell Technology Group | 1        | 1.52%   |
| D-Link System            | 1        | 1.52%   |
| Broadcom                 | 1        | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 26       | 35.14%  |
| Intel I211 Gigabit Network Connection                             | 6        | 8.11%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 6.76%   |
| Intel Ethernet Controller I225-V                                  | 4        | 5.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 4.05%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 4.05%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 1.35%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 1.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 1.35%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 1.35%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.35%   |
| Intel Ethernet Controller X550                                    | 1        | 1.35%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.35%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.35%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 1.35%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.35%   |
| Intel Ethernet Connection (13) I219-V                             | 1        | 1.35%   |
| Intel Ethernet Connection (11) I219-V                             | 1        | 1.35%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 1.35%   |
| Intel 82599 Ethernet Controller Virtual Function                  | 1        | 1.35%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 1.35%   |
| Intel 82575GB Gigabit Network Connection                          | 1        | 1.35%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 1.35%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)        | 1        | 1.35%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 1.35%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 1.35%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1        | 1.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 75%     |
| WiFi     | 19       | 23.75%  |
| Modem    | 1        | 1.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 57       | 95%     |
| WiFi     | 3        | 5%      |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 49.23%  |
| 2     | 17       | 26.15%  |
| 3     | 6        | 9.23%   |
| 0     | 5        | 7.69%   |
| 5     | 2        | 3.08%   |
| 4     | 2        | 3.08%   |
| 7     | 1        | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 54       | 83.08%  |
| Yes  | 11       | 16.92%  |

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
| Intel                       | 37       | 47.44%  |
| Nvidia                      | 18       | 23.08%  |
| AMD                         | 16       | 20.51%  |
| XMOS                        | 1        | 1.28%   |
| Realtek Semiconductor       | 1        | 1.28%   |
| Razer USA                   | 1        | 1.28%   |
| Kingston Technology         | 1        | 1.28%   |
| FiiO Electronics Technology | 1        | 1.28%   |
| Ensoniq                     | 1        | 1.28%   |
| Cambridge Silicon Radio     | 1        | 1.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 7        | 7.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 7        | 7.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4        | 4.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4        | 4.35%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4        | 4.35%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 3.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 3.26%   |
| Intel Cannon Lake PCH cAVS                                                        | 3        | 3.26%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3        | 3.26%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3        | 3.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 3.26%   |
| Nvidia GP108 High Definition Audio Controller                                     | 2        | 2.17%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 2.17%   |
| Nvidia GP104 High Definition Audio Controller                                     | 2        | 2.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 2.17%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 2.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2        | 2.17%   |
| Intel Comet Lake PCH-V cAVS                                                       | 2        | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 2        | 2.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2        | 2.17%   |
| Intel 200 Series PCH HD Audio                                                     | 2        | 2.17%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 2        | 2.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 2.17%   |
| XMOS XMOS XS1-U8 MFA (ST)                                                         | 1        | 1.09%   |
| Realtek Semiconductor Realtek USB Audio                                           | 1        | 1.09%   |
| Razer USA Razer BlackShark V2 Pro Razer BlackShark V2 Pro                         | 1        | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 1.09%   |
| Nvidia MCP61 High Definition Audio                                                | 1        | 1.09%   |
| Nvidia High Definition Audio Controller                                           | 1        | 1.09%   |
| Kingston Technology HyperX 7.1 Audio                                              | 1        | 1.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 1.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1        | 1.09%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 1        | 1.09%   |
| Intel Comet Lake PCH cAVS                                                         | 1        | 1.09%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 1.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1        | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1        | 1.09%   |
| FiiO Electronics Technology FiiO USB DAC-E10                                      | 1        | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 10       | 15.38%  |
| Samsung Electronics          | 9        | 13.85%  |
| Crucial                      | 8        | 12.31%  |
| SK hynix                     | 7        | 10.77%  |
| Micron Technology            | 6        | 9.23%   |
| Kingston                     | 6        | 9.23%   |
| G.Skill                      | 6        | 9.23%   |
| Unknown                      | 3        | 4.62%   |
| A-DATA Technology            | 2        | 3.08%   |
| Transcend                    | 1        | 1.54%   |
| Qimonda                      | 1        | 1.54%   |
| Patriot Memory (PDP Systems) | 1        | 1.54%   |
| Patriot                      | 1        | 1.54%   |
| Kingmax                      | 1        | 1.54%   |
| Hewlett-Packard              | 1        | 1.54%   |
| AMD                          | 1        | 1.54%   |
| Unknown                      | 1        | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                                 | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 1        | 1.43%   |
| Unknown RAM Module 2GB DIMM                                             | 1        | 1.43%   |
| Transcend RAM JM1333KSN-2G 2GB SODIMM DDR3 1066MT/s                     | 1        | 1.43%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s                    | 1        | 1.43%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                    | 1        | 1.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                  | 1        | 1.43%   |
| SK hynix RAM HMT42GR7CMR4A-G7 16GB DIMM DDR3 1067MT/s                   | 1        | 1.43%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s                    | 1        | 1.43%   |
| SK hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s                    | 1        | 1.43%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s                    | 1        | 1.43%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                    | 1        | 1.43%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 1.43%   |
| Samsung RAM M393B5170GB0 4GB DIMM DDR3 1333MT/s                         | 1        | 1.43%   |
| Samsung RAM M393B2G70DB0 16GB DIMM DDR3 1333MT/s                        | 1        | 1.43%   |
| Samsung RAM M391B5273DH0-YH9 4GB DIMM DDR3 1333MT/s                     | 1        | 1.43%   |
| Samsung RAM M391A2K43BB1-CTD 16GB DIMM DDR4 3200MT/s                    | 1        | 1.43%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s                     | 1        | 1.43%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s                     | 1        | 1.43%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 2666MT/s                     | 1        | 1.43%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s                     | 1        | 1.43%   |
| Qimonda RAM 64T128000EU2.5C2 1GB DIMM DDR2 800MT/s                      | 1        | 1.43%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s                          | 1        | 1.43%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1333MT/s                         | 1        | 1.43%   |
| Patriot Memory (PDP Systems) RAM 3733 C17 Series 8GB DIMM DDR4 2133MT/s | 1        | 1.43%   |
| Micron RAM Module 8GB DIMM DDR4 3200MT/s                                | 1        | 1.43%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                     | 1        | 1.43%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s                    | 1        | 1.43%   |
| Micron RAM 4ATF51264AZ-2G3B1 4GB DIMM DDR4 2400MT/s                     | 1        | 1.43%   |
| Micron RAM 36KSF1G72PZ-1 8GB DIMM DDR3 1333MT/s                         | 1        | 1.43%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB DIMM DDR3 1600MT/s                     | 1        | 1.43%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s                     | 1        | 1.43%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s                  | 1        | 1.43%   |
| Kingston RAM KHX1866C10D3/ 8GB DIMM DDR3 933MT/s                        | 1        | 1.43%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                     | 1        | 1.43%   |
| Kingston RAM CBD24D4U7S1ME-4 4GB DIMM DDR4 2400MT/s                     | 1        | 1.43%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s                   | 1        | 1.43%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB DIMM DDR3 1600MT/s                    | 1        | 1.43%   |
| Kingmax RAM FLFF65F-C8KL9 4GB DIMM DDR3 1333MT/s                        | 1        | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 28       | 47.46%  |
| DDR3    | 26       | 44.07%  |
| DDR2    | 2        | 3.39%   |
| Unknown | 2        | 3.39%   |
| DDR     | 1        | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 50       | 86.21%  |
| SODIMM | 8        | 13.79%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 34       | 50.75%  |
| 4096  | 16       | 23.88%  |
| 16384 | 7        | 10.45%  |
| 2048  | 7        | 10.45%  |
| 32768 | 2        | 2.99%   |
| 1024  | 1        | 1.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 26.67%  |
| 3200    | 8        | 13.33%  |
| 1333    | 8        | 13.33%  |
| 2400    | 6        | 10%     |
| 2133    | 5        | 8.33%   |
| 2666    | 3        | 5%      |
| 3600    | 2        | 3.33%   |
| 2667    | 2        | 3.33%   |
| 800     | 2        | 3.33%   |
| 3400    | 1        | 1.67%   |
| 2933    | 1        | 1.67%   |
| 1334    | 1        | 1.67%   |
| 1067    | 1        | 1.67%   |
| 1066    | 1        | 1.67%   |
| 933     | 1        | 1.67%   |
| 533     | 1        | 1.67%   |
| Unknown | 1        | 1.67%   |

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
| 1     | 29       | 44.62%  |
| 0     | 22       | 33.85%  |
| 2     | 11       | 16.92%  |
| 3     | 3        | 4.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 39       | 70.91%  |
| Net/wireless             | 5        | 9.09%   |
| Bluetooth                | 5        | 9.09%   |
| Firewire controller      | 3        | 5.45%   |
| Net/ethernet             | 2        | 3.64%   |
| Card reader              | 1        | 1.82%   |

