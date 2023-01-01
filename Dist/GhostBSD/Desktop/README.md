GhostBSD - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for GhostBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
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

Total: 95

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| HP        | 18E7                        | [0b962b9400](https://bsd-hardware.info/?probe=0b962b9400) | Dec 20, 2022 |
| MSI       | X299 PRO                    | [beec8001a1](https://bsd-hardware.info/?probe=beec8001a1) | Dec 17, 2022 |
| MSI       | B450M MORTAR MAX            | [d8d6af9e56](https://bsd-hardware.info/?probe=d8d6af9e56) | Dec 10, 2022 |
| ASUSTek   | H97-PLUS                    | [39ece5deaf](https://bsd-hardware.info/?probe=39ece5deaf) | Nov 27, 2022 |
| MSI       | X299 PRO                    | [d615157be7](https://bsd-hardware.info/?probe=d615157be7) | Nov 16, 2022 |
| Gigabyte  | B450M DS3H-CF               | [51ec4ce710](https://bsd-hardware.info/?probe=51ec4ce710) | Oct 24, 2022 |
| ASUSTek   | P8Z68-V                     | [6674bbf7f3](https://bsd-hardware.info/?probe=6674bbf7f3) | Oct 11, 2022 |
| Gigabyte  | H510M H                     | [8ad31cc470](https://bsd-hardware.info/?probe=8ad31cc470) | Sep 29, 2022 |
| Gigabyte  | B365M DS3H                  | [0d7d7288c0](https://bsd-hardware.info/?probe=0d7d7288c0) | Aug 27, 2022 |
| Gigabyte  | B365M DS3H                  | [0a90c3c566](https://bsd-hardware.info/?probe=0a90c3c566) | Aug 27, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [52cc45aba9](https://bsd-hardware.info/?probe=52cc45aba9) | Jul 21, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [3182740b56](https://bsd-hardware.info/?probe=3182740b56) | Jul 21, 2022 |
| MSI       | B85M-E45                    | [80f2d74d1a](https://bsd-hardware.info/?probe=80f2d74d1a) | Jul 16, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [9771cb16c0](https://bsd-hardware.info/?probe=9771cb16c0) | Jul 15, 2022 |
| Gigabyte  | X570 AORUS MASTER           | [3ee4c986b4](https://bsd-hardware.info/?probe=3ee4c986b4) | Jul 15, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [1e8b0433e8](https://bsd-hardware.info/?probe=1e8b0433e8) | Jul 15, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [85a49cb7be](https://bsd-hardware.info/?probe=85a49cb7be) | Jul 14, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [4c74cdfb76](https://bsd-hardware.info/?probe=4c74cdfb76) | Jul 10, 2022 |
| ASUSTek   | ROG CROSSHAIR VIII HERO     | [6edc61f549](https://bsd-hardware.info/?probe=6edc61f549) | Jul 10, 2022 |
| Lenovo    | SHARKBAY SDK0E50510 WIN     | [5d668f86de](https://bsd-hardware.info/?probe=5d668f86de) | Jul 06, 2022 |
| ASRock    | B450 Gaming K4              | [a03ff6ad9e](https://bsd-hardware.info/?probe=a03ff6ad9e) | Jun 10, 2022 |
| Dell      | 0M3F6C A01                  | [21d45bc75d](https://bsd-hardware.info/?probe=21d45bc75d) | May 23, 2022 |
| ASUSTek   | PRIME B350-PLUS             | [e9524e612d](https://bsd-hardware.info/?probe=e9524e612d) | May 22, 2022 |
| Gigabyte  | AX370-Gaming 3-CF           | [62ab2bc823](https://bsd-hardware.info/?probe=62ab2bc823) | May 07, 2022 |
| HP        | 0B4Ch D                     | [3f170bdee6](https://bsd-hardware.info/?probe=3f170bdee6) | May 01, 2022 |
| Dell      | 0DXJD9 A01                  | [4023d86091](https://bsd-hardware.info/?probe=4023d86091) | Apr 15, 2022 |
| Dell      | 0Y56T3 A00                  | [d9d86d5bfd](https://bsd-hardware.info/?probe=d9d86d5bfd) | Apr 12, 2022 |
| MSI       | B250 PC MATE                | [612b0f0a34](https://bsd-hardware.info/?probe=612b0f0a34) | Mar 19, 2022 |
| ASUSTek   | TUF GAMING X570-PRO         | [8307275b2e](https://bsd-hardware.info/?probe=8307275b2e) | Mar 07, 2022 |
| ASUSTek   | Z97-A                       | [84d7fb3f1e](https://bsd-hardware.info/?probe=84d7fb3f1e) | Jan 30, 2022 |
| Dell      | 0NNNCT A01                  | [290f10c785](https://bsd-hardware.info/?probe=290f10c785) | Jan 21, 2022 |
| Alienware | 01NYPT A00                  | [75aa0c00fb](https://bsd-hardware.info/?probe=75aa0c00fb) | Dec 06, 2021 |
| ASUSTek   | PRIME Z270-K                | [a2270b6f09](https://bsd-hardware.info/?probe=a2270b6f09) | Dec 02, 2021 |
| Medion    | MS-7728                     | [5b5a847fdd](https://bsd-hardware.info/?probe=5b5a847fdd) | Nov 02, 2021 |
| Gigabyte  | H410M S2 V2                 | [9cf5948654](https://bsd-hardware.info/?probe=9cf5948654) | Oct 13, 2021 |
| ASUSTek   | SABERTOOTH X58              | [8f00f132de](https://bsd-hardware.info/?probe=8f00f132de) | Sep 23, 2021 |
| ASRock    | X570 Taichi                 | [9dc50c0bcb](https://bsd-hardware.info/?probe=9dc50c0bcb) | Sep 11, 2021 |
| ASUSTek   | PRIME B350-PLUS             | [0ee3fe080c](https://bsd-hardware.info/?probe=0ee3fe080c) | Aug 30, 2021 |
| Gigabyte  | Z77M-D3H                    | [d60f1bc575](https://bsd-hardware.info/?probe=d60f1bc575) | Aug 29, 2021 |
| MSI       | H81M-P33                    | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| ASRock    | X570 Pro4                   | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| ASRock    | Z77 Extreme6                | [2521c70747](https://bsd-hardware.info/?probe=2521c70747) | Aug 02, 2021 |
| ASUSTek   | PRIME B350M-E               | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| ASUSTek   | PRIME A320M-A               | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| Lenovo    | Board                       | [428f39cbff](https://bsd-hardware.info/?probe=428f39cbff) | May 21, 2021 |
| ASUSTek   | V-P7H55E                    | [7634d3b6ca](https://bsd-hardware.info/?probe=7634d3b6ca) | May 12, 2021 |
| ASUSTek   | V-P7H55E                    | [f2e42a5ca3](https://bsd-hardware.info/?probe=f2e42a5ca3) | May 10, 2021 |
| ASUSTek   | V-P7H55E                    | [0af6399c18](https://bsd-hardware.info/?probe=0af6399c18) | May 10, 2021 |
| Dell      | 0TP412                      | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Huanan    | X79 INTEL (INTEL Xeon E5... | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| HP        | 1850                        | [3055c06d45](https://bsd-hardware.info/?probe=3055c06d45) | Mar 22, 2021 |
| ASRock    | X570 Phantom Gaming 4       | [a64a4e0792](https://bsd-hardware.info/?probe=a64a4e0792) | Mar 19, 2021 |
| ASUSTek   | ROG STRIX B450-F GAMING     | [39a46ce44e](https://bsd-hardware.info/?probe=39a46ce44e) | Mar 06, 2021 |
| Gigabyte  | EG43M-S2H                   | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| Acer      | Aspire XC-115               | [95f63df64d](https://bsd-hardware.info/?probe=95f63df64d) | Feb 21, 2021 |
| Lenovo    | Kabini CRB 31900058 STD     | [c08ca084b0](https://bsd-hardware.info/?probe=c08ca084b0) | Feb 21, 2021 |
| ASRock    | AB350 Pro4                  | [3680c4cd75](https://bsd-hardware.info/?probe=3680c4cd75) | Feb 20, 2021 |
| ASUSTek   | PRIME B450-PLUS             | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| Acer      | WG43M                       | [28a6795710](https://bsd-hardware.info/?probe=28a6795710) | Feb 15, 2021 |
| MSI       | PRESTIGE X570 CREATION      | [e6fa5753b5](https://bsd-hardware.info/?probe=e6fa5753b5) | Feb 12, 2021 |
| MSI       | PRESTIGE X570 CREATION      | [fd798dae01](https://bsd-hardware.info/?probe=fd798dae01) | Feb 12, 2021 |
| Dell      | 030VXY A01                  | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| ASUSTek   | TUF GAMING X570-PLUS        | [cf41f72474](https://bsd-hardware.info/?probe=cf41f72474) | Jan 31, 2021 |
| Dell      | 0NW6H5 A00                  | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| MSI       | Z97 GAMING 5                | [9ef0da6093](https://bsd-hardware.info/?probe=9ef0da6093) | Jan 16, 2021 |
| Dell      | 0KC9NP A01                  | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell      | 030VXY A01                  | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| Dell      | 0HY9JP A02                  | [b4d2af272e](https://bsd-hardware.info/?probe=b4d2af272e) | Jan 05, 2021 |
| ASUSTek   | Z170I PRO GAMING            | [5124b24d30](https://bsd-hardware.info/?probe=5124b24d30) | Jan 04, 2021 |
| Fujitsu   | D3617-A1 S26361-D3617-A1    | [2a0187ef7a](https://bsd-hardware.info/?probe=2a0187ef7a) | Jan 02, 2021 |
| ASUSTek   | PRIME A320M-C R2.0          | [4c24fe6fc4](https://bsd-hardware.info/?probe=4c24fe6fc4) | Dec 24, 2020 |
| HP        | 0B4Ch D                     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| Gigabyte  | Z370 AORUS Ultra Gaming-... | [a3a96da3fb](https://bsd-hardware.info/?probe=a3a96da3fb) | Dec 19, 2020 |
| ASUSTek   | TUF GAMING B550M-PLUS       | [464223cefe](https://bsd-hardware.info/?probe=464223cefe) | Dec 07, 2020 |
| ASRock    | B450 Gaming-ITX/ac          | [53bf449015](https://bsd-hardware.info/?probe=53bf449015) | Dec 02, 2020 |
| Quanta    | 2AF5 011                    | [172f23efac](https://bsd-hardware.info/?probe=172f23efac) | Nov 29, 2020 |
| ASRock    | AB350 Gaming-ITX/ac         | [8afa16fc20](https://bsd-hardware.info/?probe=8afa16fc20) | Nov 29, 2020 |
| Gigabyte  | X470 AORUS ULTRA GAMING-... | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI       | B450 GAMING PLUS            | [4cf3dd682b](https://bsd-hardware.info/?probe=4cf3dd682b) | Nov 24, 2020 |
| MSI       | B450 GAMING PLUS            | [edee76372b](https://bsd-hardware.info/?probe=edee76372b) | Nov 21, 2020 |
| ASRock    | X570 Phantom Gaming 4       | [cc075b3932](https://bsd-hardware.info/?probe=cc075b3932) | Nov 15, 2020 |
| ASRock    | X570 Phantom Gaming 4       | [6a0c640524](https://bsd-hardware.info/?probe=6a0c640524) | Nov 12, 2020 |
| ASRock    | X570 Phantom Gaming 4       | [6060033216](https://bsd-hardware.info/?probe=6060033216) | Nov 12, 2020 |
| Gigabyte  | Z97-D3H-CF                  | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Fujitsu   | D2950-A1 S26361-D2950-A1    | [86e9866c03](https://bsd-hardware.info/?probe=86e9866c03) | Oct 02, 2020 |
| Fujitsu   | D2950-A1 S26361-D2950-A1    | [3b8f8a2033](https://bsd-hardware.info/?probe=3b8f8a2033) | Oct 02, 2020 |
| MSI       | H61M-P20                    | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| Gigabyte  | F2A68HM-DS2                 | [0073f8ff71](https://bsd-hardware.info/?probe=0073f8ff71) | Aug 02, 2020 |
| Gigabyte  | H67A-UD3H-B3                | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| Unknown   | SKYBAY                      | [34bb81770b](https://bsd-hardware.info/?probe=34bb81770b) | Jul 22, 2020 |
| ASRock    | X370 Gaming K4              | [4473708fd0](https://bsd-hardware.info/?probe=4473708fd0) | Jul 22, 2020 |
| ASRock    | X370 Gaming K4              | [174569bf55](https://bsd-hardware.info/?probe=174569bf55) | Jul 21, 2020 |
| ASRock    | A300M-STX                   | [f62a2ace5a](https://bsd-hardware.info/?probe=f62a2ace5a) | Jul 16, 2020 |
| Lenovo    | Win8 Pro DPK TPG            | [db7146b868](https://bsd-hardware.info/?probe=db7146b868) | Jul 14, 2020 |
| Gigabyte  | Z170X-UD5 TH-CF             | [2fc2952380](https://bsd-hardware.info/?probe=2fc2952380) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GhostBSD 20.04.02 | 45       | 60%     |
| GhostBSD 21.08.27 | 8        | 10.67%  |
| GhostBSD 22.01.12 | 4        | 5.33%   |
| GhostBSD 22.11.22 | 3        | 4%      |
| GhostBSD 22.09.16 | 2        | 2.67%   |
| GhostBSD 22.07.16 | 2        | 2.67%   |
| GhostBSD 22.04.06 | 2        | 2.67%   |
| GhostBSD 22.11.02 | 1        | 1.33%   |
| GhostBSD 22.10.12 | 1        | 1.33%   |
| GhostBSD 22.08.23 | 1        | 1.33%   |
| GhostBSD 22.07.13 | 1        | 1.33%   |
| GhostBSD 22.06.26 | 1        | 1.33%   |
| GhostBSD 22.05.14 | 1        | 1.33%   |
| GhostBSD 22.04.22 | 1        | 1.33%   |
| GhostBSD 22.01.28 | 1        | 1.33%   |
| GhostBSD 19.12    | 1        | 1.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GhostBSD | 73       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 73       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| MATE             | 55       | 73.33%  |
| XFCE             | 9        | 12%     |
| KDE5             | 5        | 6.67%   |
| openbox          | 1        | 1.33%   |
| Metacity (Marco) | 1        | 1.33%   |
| LXQt             | 1        | 1.33%   |
| i3               | 1        | 1.33%   |
| GNOME            | 1        | 1.33%   |
| Cinnamon         | 1        | 1.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 73       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 71       | 97.26%  |
| SDDM    | 2        | 2.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 33       | 44.59%  |
| C       | 11       | 14.86%  |
| Unknown | 11       | 14.86%  |
| de_DE   | 9        | 12.16%  |
| ru_RU   | 4        | 5.41%   |
| fr_FR   | 2        | 2.7%    |
| sk_SK   | 1        | 1.35%   |
| es_ES   | 1        | 1.35%   |
| en_GB   | 1        | 1.35%   |
| en_AU   | 1        | 1.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 56       | 76.71%  |
| BIOS | 17       | 23.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 68       | 93.15%  |
| Ufs  | 5        | 6.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 68       | 93.15%  |
| MBR  | 5        | 6.85%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 16       | 21.92%  |
| Gigabyte Technology | 13       | 17.81%  |
| MSI                 | 10       | 13.7%   |
| Dell                | 9        | 12.33%  |
| ASRock              | 9        | 12.33%  |
| Lenovo              | 4        | 5.48%   |
| Hewlett-Packard     | 3        | 4.11%   |
| Fujitsu             | 2        | 2.74%   |
| Acer                | 2        | 2.74%   |
| Quanta              | 1        | 1.37%   |
| Medion              | 1        | 1.37%   |
| Huanan              | 1        | 1.37%   |
| Alienware           | 1        | 1.37%   |
| Unknown             | 1        | 1.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| MSI MS-7B86                                                           | 2        | 2.74%   |
| MSI MS-7817                                                           | 2        | 2.74%   |
| ASUS All Series                                                       | 2        | 2.74%   |
| Quanta 120-1333w                                                      | 1        | 1.37%   |
| MSI MS-7C36                                                           | 1        | 1.37%   |
| MSI MS-7B94                                                           | 1        | 1.37%   |
| MSI MS-7B89                                                           | 1        | 1.37%   |
| MSI MS-7A72                                                           | 1        | 1.37%   |
| MSI MS-7917                                                           | 1        | 1.37%   |
| MSI MS-7788                                                           | 1        | 1.37%   |
| Medion MS-7728                                                        | 1        | 1.37%   |
| Lenovo ThinkStation S10 6483CTO                                       | 1        | 1.37%   |
| Lenovo ThinkCentre M93p 10AB004DUS                                    | 1        | 1.37%   |
| Lenovo ThinkCentre Edge72 3493DEG                                     | 1        | 1.37%   |
| Lenovo H515s 10126                                                    | 1        | 1.37%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1        | 1.37%   |
| HP Z400 Workstation                                                   | 1        | 1.37%   |
| HP ProDesk 600 G1 SFF                                                 | 1        | 1.37%   |
| HP Compaq Pro 6305 SFF                                                | 1        | 1.37%   |
| Gigabyte Z97-D3H                                                      | 1        | 1.37%   |
| Gigabyte Z77M-D3H                                                     | 1        | 1.37%   |
| Gigabyte Z370 AORUS Ultra Gaming                                      | 1        | 1.37%   |
| Gigabyte Z170X-UD5 TH                                                 | 1        | 1.37%   |
| Gigabyte X570 AORUS MASTER                                            | 1        | 1.37%   |
| Gigabyte X470 AORUS ULTRA GAMING                                      | 1        | 1.37%   |
| Gigabyte H67A-UD3H-B3                                                 | 1        | 1.37%   |
| Gigabyte H510M H                                                      | 1        | 1.37%   |
| Gigabyte F2A68HM-DS2                                                  | 1        | 1.37%   |
| Gigabyte EG43M-S2H                                                    | 1        | 1.37%   |
| Gigabyte B450M DS3H                                                   | 1        | 1.37%   |
| Gigabyte B365M DS3H                                                   | 1        | 1.37%   |
| Gigabyte AX370-Gaming 3                                               | 1        | 1.37%   |
| Fujitsu ESPRIMO P1500                                                 | 1        | 1.37%   |
| Fujitsu CELSIUS W580                                                  | 1        | 1.37%   |
| Dell Precision WorkStation T3400                                      | 1        | 1.37%   |
| Dell Precision T5600                                                  | 1        | 1.37%   |
| Dell Precision 3630 Tower                                             | 1        | 1.37%   |
| Dell OptiPlex 9020                                                    | 1        | 1.37%   |
| Dell OptiPlex 790                                                     | 1        | 1.37%   |
| Dell OptiPlex 7050                                                    | 1        | 1.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 6        | 8.22%   |
| Dell OptiPlex         | 5        | 6.85%   |
| Dell Precision        | 3        | 4.11%   |
| ASUS TUF              | 3        | 4.11%   |
| ASRock X570           | 3        | 4.11%   |
| MSI MS-7B86           | 2        | 2.74%   |
| MSI MS-7817           | 2        | 2.74%   |
| Lenovo ThinkCentre    | 2        | 2.74%   |
| ASUS ROG              | 2        | 2.74%   |
| ASUS All              | 2        | 2.74%   |
| ASRock B450           | 2        | 2.74%   |
| Acer Aspire           | 2        | 2.74%   |
| Quanta 120-1333w      | 1        | 1.37%   |
| MSI MS-7C36           | 1        | 1.37%   |
| MSI MS-7B94           | 1        | 1.37%   |
| MSI MS-7B89           | 1        | 1.37%   |
| MSI MS-7A72           | 1        | 1.37%   |
| MSI MS-7917           | 1        | 1.37%   |
| MSI MS-7788           | 1        | 1.37%   |
| Medion MS-7728        | 1        | 1.37%   |
| Lenovo ThinkStation   | 1        | 1.37%   |
| Lenovo H515s          | 1        | 1.37%   |
| Huanan X79            | 1        | 1.37%   |
| HP Z400               | 1        | 1.37%   |
| HP ProDesk            | 1        | 1.37%   |
| HP Compaq             | 1        | 1.37%   |
| Gigabyte Z97-D3H      | 1        | 1.37%   |
| Gigabyte Z77M-D3H     | 1        | 1.37%   |
| Gigabyte Z370         | 1        | 1.37%   |
| Gigabyte Z170X-UD5    | 1        | 1.37%   |
| Gigabyte X570         | 1        | 1.37%   |
| Gigabyte X470         | 1        | 1.37%   |
| Gigabyte H67A-UD3H-B3 | 1        | 1.37%   |
| Gigabyte H510M        | 1        | 1.37%   |
| Gigabyte F2A68HM-DS2  | 1        | 1.37%   |
| Gigabyte EG43M-S2H    | 1        | 1.37%   |
| Gigabyte B450M        | 1        | 1.37%   |
| Gigabyte B365M        | 1        | 1.37%   |
| Gigabyte AX370-Gaming | 1        | 1.37%   |
| Fujitsu ESPRIMO       | 1        | 1.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 13       | 17.81%  |
| 2019 | 12       | 16.44%  |
| 2020 | 8        | 10.96%  |
| 2012 | 8        | 10.96%  |
| 2014 | 5        | 6.85%   |
| 2016 | 4        | 5.48%   |
| 2013 | 4        | 5.48%   |
| 2008 | 4        | 5.48%   |
| 2022 | 3        | 4.11%   |
| 2015 | 3        | 4.11%   |
| 2011 | 3        | 4.11%   |
| 2021 | 2        | 2.74%   |
| 2017 | 2        | 2.74%   |
| 2010 | 1        | 1.37%   |
| 2009 | 1        | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 73       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 73       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 22       | 30.14%  |
| 32.01-64.0  | 18       | 24.66%  |
| 8.01-16.0   | 18       | 24.66%  |
| 4.01-8.0    | 10       | 13.7%   |
| 64.01-256.0 | 4        | 5.48%   |
| 24.01-32.0  | 1        | 1.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 31       | 42.47%  |
| 0.01-0.5 | 23       | 31.51%  |
| 1.01-2.0 | 15       | 20.55%  |
| 3.01-4.0 | 4        | 5.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 30       | 39.47%  |
| 1      | 22       | 28.95%  |
| 4      | 7        | 9.21%   |
| 5      | 6        | 7.89%   |
| 3      | 6        | 7.89%   |
| 6      | 2        | 2.63%   |
| 22     | 1        | 1.32%   |
| 7      | 1        | 1.32%   |
| 0      | 1        | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 57.53%  |
| Yes       | 31       | 42.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 73       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 64.38%  |
| Yes       | 26       | 35.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 54       | 73.97%  |
| Yes       | 19       | 26.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 19       | 26.03%  |
| Germany     | 14       | 19.18%  |
| Russia      | 5        | 6.85%   |
| France      | 5        | 6.85%   |
| UK          | 4        | 5.48%   |
| Canada      | 3        | 4.11%   |
| Norway      | 2        | 2.74%   |
| Netherlands | 2        | 2.74%   |
| Malaysia    | 2        | 2.74%   |
| Czechia     | 2        | 2.74%   |
| Australia   | 2        | 2.74%   |
| Argentina   | 2        | 2.74%   |
| Ukraine     | 1        | 1.37%   |
| Switzerland | 1        | 1.37%   |
| Sweden      | 1        | 1.37%   |
| Spain       | 1        | 1.37%   |
| Morocco     | 1        | 1.37%   |
| Mexico      | 1        | 1.37%   |
| Luxembourg  | 1        | 1.37%   |
| Japan       | 1        | 1.37%   |
| Hungary     | 1        | 1.37%   |
| Finland     | 1        | 1.37%   |
| China       | 1        | 1.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Paris                       | 3        | 4.11%   |
| Berlin                      | 3        | 4.11%   |
| Obninsk                     | 2        | 2.74%   |
| Denver                      | 2        | 2.74%   |
| ЕЊta-ku                   | 1        | 1.37%   |
| Zapopan                     | 1        | 1.37%   |
| Washington                  | 1        | 1.37%   |
| Vidnoye                     | 1        | 1.37%   |
| Veenendaal                  | 1        | 1.37%   |
| Truro                       | 1        | 1.37%   |
| Traunstein                  | 1        | 1.37%   |
| Sydney                      | 1        | 1.37%   |
| St. Albert                  | 1        | 1.37%   |
| St Petersburg               | 1        | 1.37%   |
| Springfield                 | 1        | 1.37%   |
| Southampton                 | 1        | 1.37%   |
| San Nicolás de los Arroyos | 1        | 1.37%   |
| San Jose                    | 1        | 1.37%   |
| Salem                       | 1        | 1.37%   |
| Robbins                     | 1        | 1.37%   |
| Riedstadt                   | 1        | 1.37%   |
| Richmond                    | 1        | 1.37%   |
| Remseck am Neckar           | 1        | 1.37%   |
| Prague                      | 1        | 1.37%   |
| Phoenix                     | 1        | 1.37%   |
| Palm Bay                    | 1        | 1.37%   |
| Oslo                        | 1        | 1.37%   |
| Omaha                       | 1        | 1.37%   |
| Neuenhaus                   | 1        | 1.37%   |
| Moncton                     | 1        | 1.37%   |
| Madrid                      | 1        | 1.37%   |
| Luxembourg                  | 1        | 1.37%   |
| Ludwigsburg                 | 1        | 1.37%   |
| Lorient                     | 1        | 1.37%   |
| London                      | 1        | 1.37%   |
| Lincoln                     | 1        | 1.37%   |
| Leipzig                     | 1        | 1.37%   |
| Larnod                      | 1        | 1.37%   |
| Kyiv                        | 1        | 1.37%   |
| Kuala Lumpur                | 1        | 1.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 34       | 52     | 22.97%  |
| Samsung Electronics | 29       | 39     | 19.59%  |
| Seagate             | 20       | 30     | 13.51%  |
| Crucial             | 15       | 18     | 10.14%  |
| Toshiba             | 7        | 8      | 4.73%   |
| Hitachi             | 6        | 6      | 4.05%   |
| SanDisk             | 5        | 7      | 3.38%   |
| Micron Technology   | 3        | 3      | 2.03%   |
| Kingston            | 3        | 3      | 2.03%   |
| HGST                | 3        | 3      | 2.03%   |
| A-DATA Technology   | 3        | 3      | 2.03%   |
| PNY                 | 2        | 4      | 1.35%   |
| OCZ                 | 2        | 2      | 1.35%   |
| Maxtor              | 2        | 2      | 1.35%   |
| Intel               | 2        | 2      | 1.35%   |
| XPG                 | 1        | 1      | 0.68%   |
| Transcend           | 1        | 1      | 0.68%   |
| SPCC                | 1        | 1      | 0.68%   |
| Plextor             | 1        | 1      | 0.68%   |
| Phison              | 1        | 2      | 0.68%   |
| Patriot             | 1        | 1      | 0.68%   |
| LDLC                | 1        | 1      | 0.68%   |
| HPT                 | 1        | 4      | 0.68%   |
| Gigabyte Technology | 1        | 1      | 0.68%   |
| Corsair             | 1        | 1      | 0.68%   |
| China               | 1        | 1      | 0.68%   |
| AMD                 | 1        | 1      | 0.68%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Samsung SSD 850 EVO 500GB       | 4        | 2.29%   |
| Samsung SSD 850 EVO 250GB       | 4        | 2.29%   |
| Crucial CT1000MX500SSD1 1TB     | 4        | 2.29%   |
| Seagate ST500DM002-1BD142 500GB | 3        | 1.71%   |
| WDC WDS100T3X0C-00SJG0 1TB      | 2        | 1.14%   |
| WDC WD40EFRX-68N32N0 4TB        | 2        | 1.14%   |
| WDC WD2000JS-55MHB0 192GB       | 2        | 1.14%   |
| WDC WD10EZEX-21M2NA0 1TB        | 2        | 1.14%   |
| Toshiba Q300 480GB              | 2        | 1.14%   |
| Toshiba HDWD120 2TB             | 2        | 1.14%   |
| Seagate ST4000DM004-2CV104 4TB  | 2        | 1.14%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 1.14%   |
| Samsung SSD 970 EVO 500GB       | 2        | 1.14%   |
| Samsung SSD 860 QVO 1TB         | 2        | 1.14%   |
| Samsung SSD 860 EVO 1TB         | 2        | 1.14%   |
| Maxtor STM3320613AS 320GB       | 2        | 1.14%   |
| Crucial CT250MX500SSD1 250GB    | 2        | 1.14%   |
| XPG GAMMIX S11 Pro 256GB        | 1        | 0.57%   |
| WDC WDS500G2B0A-00SM50 500GB    | 1        | 0.57%   |
| WDC WDS500G2B0A 500GB           | 1        | 0.57%   |
| WDC WDS480G2G0A-00JH30 480GB    | 1        | 0.57%   |
| WDC WDS240G2G0C-00AJM0 240GB    | 1        | 0.57%   |
| WDC WDS200T2B0B-00YS70 2TB      | 1        | 0.57%   |
| WDC WDS200T2B0A-00SM50 2TB      | 1        | 0.57%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1        | 0.57%   |
| WDC WDS100T1X0E-00AFY0 1TB      | 1        | 0.57%   |
| WDC WD800BEVT-75ZCT2 80GB       | 1        | 0.57%   |
| WDC WD7500LPCX-00KHST0 752GB    | 1        | 0.57%   |
| WDC WD60EZRZ-00GZ5B1 6TB        | 1        | 0.57%   |
| WDC WD6003FFBX-68MU3N0 6TB      | 1        | 0.57%   |
| WDC WD50NMZW-59A8NS1 5TB        | 1        | 0.57%   |
| WDC WD5000LPLX-75ZNTT0 500GB    | 1        | 0.57%   |
| WDC WD5000BEVT-24A0RT0 500GB    | 1        | 0.57%   |
| WDC WD5000AAVS-00ZTB0 500GB     | 1        | 0.57%   |
| WDC WD5000AAKX-60U6AA0 500GB    | 1        | 0.57%   |
| WDC WD5000AAKX-00ERMA0 500GB    | 1        | 0.57%   |
| WDC WD5000AAKS-60WWPA0 500GB    | 1        | 0.57%   |
| WDC WD5000AADS-00S9B0 500GB     | 1        | 0.57%   |
| WDC WD3200BEKT-75KA9T0 320GB    | 1        | 0.57%   |
| WDC WD2500AAJS-75M0A0 250GB     | 1        | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 39     | 40.3%   |
| Seagate             | 19       | 28     | 28.36%  |
| Hitachi             | 6        | 6      | 8.96%   |
| Toshiba             | 5        | 6      | 7.46%   |
| Samsung Electronics | 4        | 5      | 5.97%   |
| HGST                | 3        | 3      | 4.48%   |
| Maxtor              | 2        | 2      | 2.99%   |
| HPT                 | 1        | 4      | 1.49%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 21       | 25     | 33.33%  |
| Crucial             | 12       | 14     | 19.05%  |
| SanDisk             | 5        | 7      | 7.94%   |
| WDC                 | 4        | 6      | 6.35%   |
| A-DATA Technology   | 3        | 3      | 4.76%   |
| Toshiba             | 2        | 2      | 3.17%   |
| PNY                 | 2        | 4      | 3.17%   |
| OCZ                 | 2        | 2      | 3.17%   |
| Micron Technology   | 2        | 2      | 3.17%   |
| Kingston            | 2        | 2      | 3.17%   |
| Transcend           | 1        | 1      | 1.59%   |
| SPCC                | 1        | 1      | 1.59%   |
| Seagate             | 1        | 1      | 1.59%   |
| Plextor             | 1        | 1      | 1.59%   |
| Patriot             | 1        | 1      | 1.59%   |
| Intel               | 1        | 1      | 1.59%   |
| China               | 1        | 1      | 1.59%   |
| AMD                 | 1        | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 48       | 93     | 42.48%  |
| SSD  | 44       | 75     | 38.94%  |
| NVMe | 21       | 30     | 18.58%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 70       | 168    | 76.92%  |
| NVMe | 21       | 30     | 23.08%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 53       | 80     | 47.75%  |
| 0.51-1.0   | 28       | 43     | 25.23%  |
| 1.01-2.0   | 15       | 21     | 13.51%  |
| 3.01-4.0   | 8        | 10     | 7.21%   |
| 4.01-10.0  | 5        | 10     | 4.5%    |
| 2.01-3.0   | 1        | 2      | 0.9%    |
| 10.01-20.0 | 1        | 2      | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 18       | 24.32%  |
| 1-20       | 17       | 22.97%  |
| 251-500    | 16       | 21.62%  |
| 501-1000   | 8        | 10.81%  |
| 51-100     | 6        | 8.11%   |
| Unknown    | 5        | 6.76%   |
| 21-50      | 2        | 2.7%    |
| 1001-2000  | 2        | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 59       | 79.73%  |
| 21-50   | 8        | 10.81%  |
| Unknown | 5        | 6.76%   |
| 51-100  | 2        | 2.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 2        | 2      | 10.53%  |
| Maxtor STM3320613AS 320GB       | 2        | 2      | 10.53%  |
| WDC WDS480G2G0A-00JH30 480GB    | 1        | 2      | 5.26%   |
| WDC WD5000AAKS-60WWPA0 500GB    | 1        | 1      | 5.26%   |
| WDC WD10EZEX-21M2NA0 1TB        | 1        | 1      | 5.26%   |
| Seagate ST500DM002-1BC142 500GB | 1        | 1      | 5.26%   |
| Seagate ST4000DM004-2CV104 4TB  | 1        | 1      | 5.26%   |
| Seagate ST3250310AS 250GB       | 1        | 1      | 5.26%   |
| Seagate ST31500541AS 1.5TB      | 1        | 1      | 5.26%   |
| Samsung Electronics HD103SJ 1TB | 1        | 2      | 5.26%   |
| OCZ AGILITY3 240GB              | 1        | 1      | 5.26%   |
| Hitachi HTS725032A9A364 320GB   | 1        | 1      | 5.26%   |
| Hitachi HTS547575A9E384 752GB   | 1        | 1      | 5.26%   |
| Hitachi HTS541680J9SA00 80GB    | 1        | 1      | 5.26%   |
| Crucial CT480M500SSD1 480GB     | 1        | 1      | 5.26%   |
| Crucial CT1050MX300SSD1 1TB     | 1        | 1      | 5.26%   |
| Crucial CT1000MX500SSD1 1TB     | 1        | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 27.78%  |
| WDC                 | 3        | 4      | 16.67%  |
| Hitachi             | 3        | 3      | 16.67%  |
| Crucial             | 3        | 3      | 16.67%  |
| Maxtor              | 2        | 2      | 11.11%  |
| Samsung Electronics | 1        | 2      | 5.56%   |
| OCZ                 | 1        | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 38.46%  |
| Hitachi             | 3        | 3      | 23.08%  |
| WDC                 | 2        | 2      | 15.38%  |
| Maxtor              | 2        | 2      | 15.38%  |
| Samsung Electronics | 1        | 2      | 7.69%   |

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
| Works    | 70       | 173    | 79.55%  |
| Malfunc  | 17       | 21     | 19.32%  |
| Detected | 1        | 4      | 1.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 42       | 39.62%  |
| AMD                           | 31       | 29.25%  |
| Samsung Electronics           | 7        | 6.6%    |
| SanDisk                       | 5        | 4.72%   |
| Phison Electronics            | 3        | 2.83%   |
| Micron/Crucial Technology     | 3        | 2.83%   |
| ASMedia Technology            | 3        | 2.83%   |
| Marvell Technology Group      | 2        | 1.89%   |
| Silicon Motion                | 1        | 0.94%   |
| Seagate Technology            | 1        | 0.94%   |
| Nvidia                        | 1        | 0.94%   |
| Micron Technology             | 1        | 0.94%   |
| Kingston Technology Company   | 1        | 0.94%   |
| JMicron Technology            | 1        | 0.94%   |
| Integrated Technology Express | 1        | 0.94%   |
| HighPoint Technologies        | 1        | 0.94%   |
| ADATA Technology              | 1        | 0.94%   |
| Adaptec                       | 1        | 0.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26       | 20.47%  |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 7.09%   |
| Intel SATA Controller [RAID mode]                                                       | 7        | 5.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 3.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5        | 3.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4        | 3.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 2.36%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 2.36%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 2.36%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.36%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.36%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.57%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 1.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.57%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 1.57%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 1.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.57%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.57%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.57%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.79%   |
| Seagate FireCuda 520 SSD                                                                | 1        | 0.79%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1        | 0.79%   |
| SanDisk unknown                                                                         | 1        | 0.79%   |
| SanDisk PC SN520 NVMe SSD                                                               | 1        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.79%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.79%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.79%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 0.79%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.79%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.79%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.79%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 61       | 60.4%   |
| NVMe | 21       | 20.79%  |
| IDE  | 9        | 8.91%   |
| RAID | 7        | 6.93%   |
| SCSI | 2        | 1.98%   |
| SAS  | 1        | 0.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 42       | 57.53%  |
| AMD    | 31       | 42.47%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 4.11%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 4.11%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 4.11%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 2.74%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 2.74%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 2.74%   |
| Intel Xeon E-2236 CPU @ 3.40GHz             | 1        | 1.37%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 1.37%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 1.37%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GH           | 1        | 1.37%   |
| Intel Xeon                                  | 1        | 1.37%   |
| Intel Unknown                               | 1        | 1.37%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 1.37%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 1.37%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1        | 1.37%   |
| Intel Core i9-10900X CPU @ 3.70GHz          | 1        | 1.37%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.37%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 1.37%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.37%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.37%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1        | 1.37%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.37%   |
| Intel Core i7-2600K CPU                     | 1        | 1.37%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.37%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 1.37%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.37%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 1.37%   |
| Intel Core i5-8400T CPU @ 1.70GHz           | 1        | 1.37%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.37%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.37%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.37%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 1        | 1.37%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.37%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.37%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 1.37%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.37%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 1        | 1.37%   |
| Intel Core i5-2500 CPU @ 3.30GH             | 1        | 1.37%   |
| Intel Core i5-10500T CPU @ 2.30GHz          | 1        | 1.37%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1        | 1.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 16       | 21.92%  |
| Intel Core i7           | 11       | 15.07%  |
| AMD Ryzen 7             | 9        | 12.33%  |
| AMD Ryzen 5             | 9        | 12.33%  |
| Intel Xeon              | 5        | 6.85%   |
| Intel Core i3           | 3        | 4.11%   |
| AMD Ryzen 9             | 3        | 4.11%   |
| Intel Pentium           | 2        | 2.74%   |
| Intel Core 2 Quad       | 2        | 2.74%   |
| AMD Ryzen 3             | 2        | 2.74%   |
| AMD E1                  | 2        | 2.74%   |
| Other                   | 1        | 1.37%   |
| Intel Pentium Dual-Core | 1        | 1.37%   |
| Intel Core i9           | 1        | 1.37%   |
| AMD Ryzen 3 PRO         | 1        | 1.37%   |
| AMD E2                  | 1        | 1.37%   |
| AMD Athlon X4           | 1        | 1.37%   |
| AMD Athlon              | 1        | 1.37%   |
| AMD A6                  | 1        | 1.37%   |
| AMD A10                 | 1        | 1.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 28       | 38.36%  |
| 16      | 9        | 12.33%  |
| 12      | 9        | 12.33%  |
| 2       | 9        | 12.33%  |
| 6       | 8        | 10.96%  |
| 8       | 4        | 5.48%   |
| 32      | 2        | 2.74%   |
| Unknown | 2        | 2.74%   |
| 24      | 1        | 1.37%   |
| 10      | 1        | 1.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 72       | 98.63%  |
| 2      | 1        | 1.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 52       | 71.23%  |
| 2       | 19       | 26.03%  |
| Unknown | 2        | 2.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 10       | 13.7%   |
| Zen+        | 9        | 12.33%  |
| Zen 2       | 9        | 12.33%  |
| Haswell     | 9        | 12.33%  |
| SandyBridge | 7        | 9.59%   |
| Penryn      | 5        | 6.85%   |
| Zen 3       | 4        | 5.48%   |
| Skylake     | 4        | 5.48%   |
| Zen         | 3        | 4.11%   |
| IvyBridge   | 3        | 4.11%   |
| Piledriver  | 2        | 2.74%   |
| CometLake   | 2        | 2.74%   |
| Westmere    | 1        | 1.37%   |
| Puma        | 1        | 1.37%   |
| Nehalem     | 1        | 1.37%   |
| Jaguar      | 1        | 1.37%   |
| Excavator   | 1        | 1.37%   |
| Bobcat      | 1        | 1.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 40       | 51.95%  |
| AMD    | 19       | 24.68%  |
| Intel  | 18       | 23.38%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 5        | 6.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 6.41%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 5.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 5.13%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 3.85%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 3.85%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 3        | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 3.85%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 2.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.56%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 2.56%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 2.56%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.56%   |
| Intel HD Graphics 630                                                       | 2        | 2.56%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 2.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.28%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.28%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.28%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.28%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 1.28%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 1.28%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.28%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 1.28%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 1.28%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.28%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.28%   |
| Nvidia GF100GL [Quadro 4000]                                                | 1        | 1.28%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.28%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 1.28%   |
| Intel HD Graphics 620                                                       | 1        | 1.28%   |
| Intel HD Graphics 530                                                       | 1        | 1.28%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.28%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.28%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.28%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.28%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 1.28%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 35       | 47.95%  |
| 1 x AMD        | 18       | 24.66%  |
| 1 x Intel      | 14       | 19.18%  |
| Intel + Nvidia | 3        | 4.11%   |
| 2 x Nvidia     | 1        | 1.37%   |
| 2 x Intel      | 1        | 1.37%   |
| AMD + Nvidia   | 1        | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 37       | 50.68%  |
| Proprietary | 36       | 49.32%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 40.54%  |
| 7.01-8.0   | 10       | 13.51%  |
| 1.01-2.0   | 10       | 13.51%  |
| 3.01-4.0   | 9        | 12.16%  |
| 0.51-1.0   | 8        | 10.81%  |
| 0.01-0.5   | 4        | 5.41%   |
| 5.01-6.0   | 1        | 1.35%   |
| 2.01-3.0   | 1        | 1.35%   |
| 8.01-16.0  | 1        | 1.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 10       | 13.33%  |
| Samsung Electronics  | 8        | 10.67%  |
| Goldstar             | 8        | 10.67%  |
| BenQ                 | 7        | 9.33%   |
| Acer                 | 5        | 6.67%   |
| Philips              | 3        | 4%      |
| LG Electronics       | 3        | 4%      |
| Hewlett-Packard      | 3        | 4%      |
| AOC                  | 3        | 4%      |
| Ancor Communications | 3        | 4%      |
| Vizio                | 2        | 2.67%   |
| ViewSonic            | 2        | 2.67%   |
| Lenovo               | 2        | 2.67%   |
| Iiyama               | 2        | 2.67%   |
| Fujitsu Siemens      | 2        | 2.67%   |
| ASUSTek Computer     | 2        | 2.67%   |
| WYT                  | 1        | 1.33%   |
| Toshiba              | 1        | 1.33%   |
| SAC                  | 1        | 1.33%   |
| Pixio                | 1        | 1.33%   |
| OEM                  | 1        | 1.33%   |
| Mi                   | 1        | 1.33%   |
| Idek Iiyama          | 1        | 1.33%   |
| HannStar             | 1        | 1.33%   |
| CHD                  | 1        | 1.33%   |
| Belinea              | 1        | 1.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 2        | 2.53%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                   | 1        | 1.27%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                    | 1        | 1.27%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                    | 1        | 1.27%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch              | 1        | 1.27%   |
| ViewSonic LCD Monitor VA1938 Series                                    | 1        | 1.27%   |
| Toshiba TV TSB010F 1920x1080 890x500mm 40.2-inch                       | 1        | 1.27%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch      | 1        | 1.27%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 600x340mm 27.2-inch    | 1        | 1.27%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 480x270mm 21.7-inch     | 1        | 1.27%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch  | 1        | 1.27%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch      | 1        | 1.27%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 1.27%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1        | 1.27%   |
| Samsung Electronics LCD Monitor SAM02A4 1360x768                       | 1        | 1.27%   |
| SAC LED MONITOR SAC952D 1920x1080 470x280mm 21.5-inch                  | 1        | 1.27%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                      | 1        | 1.27%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 1.27%   |
| Philips LCD Monitor PHL 240V5 1920x1080                                | 1        | 1.27%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1        | 1.27%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                        | 1        | 1.27%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch                   | 1        | 1.27%   |
| LG Electronics LCD Monitor W1952 2806x900                              | 1        | 1.27%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 1        | 1.27%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 1.27%   |
| Lenovo V20-10 LEN65DC 1600x900 430x240mm 19.4-inch                     | 1        | 1.27%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch               | 1        | 1.27%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                   | 1        | 1.27%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                   | 1        | 1.27%   |
| Idek Iiyama LCD Monitor PL3270Q 5120x1440                              | 1        | 1.27%   |
| Idek Iiyama LCD Monitor PL3270Q                                        | 1        | 1.27%   |
| Hewlett-Packard w1907 HWP26A3 1440x900 410x260mm 19.1-inch             | 1        | 1.27%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 1.27%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch           | 1        | 1.27%   |
| HannStar LCD Monitor HSD2469 1680x1050 470x300mm 22.0-inch             | 1        | 1.27%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                   | 1        | 1.27%   |
| Goldstar W2242 GSM4B6F 1680x1050 490x320mm 23.0-inch                   | 1        | 1.27%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 1        | 1.27%   |
| Goldstar LG ULTRAWIDE GSM76FA 2560x1080 800x340mm 34.2-inch            | 1        | 1.27%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 1        | 1.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 34       | 43.59%  |
| 2560x1440 (QHD)    | 10       | 12.82%  |
| 3840x2160 (4K)     | 7        | 8.97%   |
| 1280x1024 (SXGA)   | 5        | 6.41%   |
| 2560x1080          | 3        | 3.85%   |
| 1680x1050 (WSXGA+) | 3        | 3.85%   |
| 1600x900 (HD+)     | 3        | 3.85%   |
| Unknown            | 3        | 3.85%   |
| 1440x900 (WXGA+)   | 2        | 2.56%   |
| 1360x768           | 2        | 2.56%   |
| 5120x1440          | 1        | 1.28%   |
| 3840x1600          | 1        | 1.28%   |
| 3200x1080          | 1        | 1.28%   |
| 2806x900           | 1        | 1.28%   |
| 1920x540           | 1        | 1.28%   |
| 1920x1200 (WUXGA)  | 1        | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 13       | 17.33%  |
| 21      | 12       | 16%     |
| 24      | 10       | 13.33%  |
| Unknown | 10       | 13.33%  |
| 19      | 8        | 10.67%  |
| 23      | 7        | 9.33%   |
| 31      | 4        | 5.33%   |
| 54      | 2        | 2.67%   |
| 34      | 2        | 2.67%   |
| 22      | 2        | 2.67%   |
| 65      | 1        | 1.33%   |
| 40      | 1        | 1.33%   |
| 32      | 1        | 1.33%   |
| 17      | 1        | 1.33%   |
| 16      | 1        | 1.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 25       | 34.25%  |
| 401-500     | 19       | 26.03%  |
| Unknown     | 10       | 13.7%   |
| 601-700     | 7        | 9.59%   |
| 701-800     | 3        | 4.11%   |
| 351-400     | 3        | 4.11%   |
| 1001-1500   | 3        | 4.11%   |
| 301-350     | 2        | 2.74%   |
| 801-900     | 1        | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 49       | 69.01%  |
| Unknown | 8        | 11.27%  |
| 16/10   | 5        | 7.04%   |
| 5/4     | 4        | 5.63%   |
| 21/9    | 2        | 2.82%   |
| 6/5     | 1        | 1.41%   |
| 32/9    | 1        | 1.41%   |
| 3/2     | 1        | 1.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 28       | 37.84%  |
| 301-350        | 13       | 17.57%  |
| Unknown        | 10       | 13.51%  |
| 151-200        | 8        | 10.81%  |
| 351-500        | 7        | 9.46%   |
| More than 1000 | 3        | 4.05%   |
| 251-300        | 2        | 2.7%    |
| 141-150        | 1        | 1.35%   |
| 131-140        | 1        | 1.35%   |
| 501-1000       | 1        | 1.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 40       | 52.63%  |
| 101-120 | 18       | 23.68%  |
| Unknown | 10       | 13.16%  |
| 121-160 | 4        | 5.26%   |
| 1-50    | 2        | 2.63%   |
| 161-240 | 2        | 2.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 54       | 72.97%  |
| 2     | 12       | 16.22%  |
| 0     | 8        | 10.81%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 38       | 38.38%  |
| Realtek Semiconductor                 | 37       | 37.37%  |
| Qualcomm Atheros                      | 7        | 7.07%   |
| Broadcom                              | 5        | 5.05%   |
| TP-Link                               | 3        | 3.03%   |
| Ralink Technology                     | 1        | 1.01%   |
| Ralink                                | 1        | 1.01%   |
| Qualcomm Atheros Communications       | 1        | 1.01%   |
| Qualcomm                              | 1        | 1.01%   |
| Nvidia                                | 1        | 1.01%   |
| Microchip Technology                  | 1        | 1.01%   |
| Generic                               | 1        | 1.01%   |
| Aquantia                              | 1        | 1.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 24.11%  |
| Intel I211 Gigabit Network Connection                             | 11       | 9.82%   |
| Intel Wi-Fi 6 AX200                                               | 6        | 5.36%   |
| Intel Ethernet Connection (2) I219-V                              | 6        | 5.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 3.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.68%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3        | 2.68%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 2.68%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2        | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.79%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 1.79%   |
| TP-Link TP-LINK Wireless USB Adapter                              | 1        | 0.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 0.89%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.89%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.89%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.89%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.89%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 0.89%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.89%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.89%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1        | 0.89%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.89%   |
| Microchip HTC Hub Controller                                      | 1        | 0.89%   |
| Intel Wireless-AC 9260                                            | 1        | 0.89%   |
| Intel Wireless 7265                                               | 1        | 0.89%   |
| Intel Wireless 7260                                               | 1        | 0.89%   |
| Intel Wireless 3165                                               | 1        | 0.89%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.89%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1        | 0.89%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.89%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.89%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 13       | 46.43%  |
| Realtek Semiconductor                 | 4        | 14.29%  |
| Qualcomm Atheros                      | 4        | 14.29%  |
| TP-Link                               | 3        | 10.71%  |
| Ralink Technology                     | 1        | 3.57%   |
| Ralink                                | 1        | 3.57%   |
| Qualcomm Atheros Communications       | 1        | 3.57%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                              | Desktops | Percent |
|------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                | 6        | 21.43%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                   | 3        | 10.71%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                   | 3        | 10.71%  |
| Realtek RTL8188EE Wireless Network Adapter                                         | 2        | 7.14%   |
| TP-Link TP-LINK Wireless USB Adapter                                               | 1        | 3.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                       | 1        | 3.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                         | 1        | 3.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                           | 1        | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                | 1        | 3.57%   |
| Ralink RT5370 Wireless Adapter                                                     | 1        | 3.57%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                             | 1        | 3.57%   |
| Qualcomm Atheros AR9271 802.11n                                                    | 1        | 3.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                     | 1        | 3.57%   |
| Intel Wireless-AC 9260                                                             | 1        | 3.57%   |
| Intel Wireless 7265                                                                | 1        | 3.57%   |
| Intel Wireless 7260                                                                | 1        | 3.57%   |
| Intel Wireless 3165                                                                | 1        | 3.57%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB54GC v3 802.11g Adapter [Ralink RT2070L] | 1        | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 34       | 43.04%  |
| Intel                 | 34       | 43.04%  |
| Broadcom              | 5        | 6.33%   |
| Qualcomm Atheros      | 3        | 3.8%    |
| Qualcomm              | 1        | 1.27%   |
| Nvidia                | 1        | 1.27%   |
| Aquantia              | 1        | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27       | 33.75%  |
| Intel I211 Gigabit Network Connection                             | 11       | 13.75%  |
| Intel Ethernet Connection (2) I219-V                              | 6        | 7.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 3.75%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 3.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.5%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 2.5%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.25%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 1.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.25%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.25%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1        | 1.25%   |
| Nvidia MCP73 Ethernet                                             | 1        | 1.25%   |
| Intel I350 Gigabit Network Connection                             | 1        | 1.25%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1        | 1.25%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.25%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.25%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.25%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.25%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.25%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.25%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.25%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.25%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.25%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 1.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.25%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.25%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 1.25%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 1.25%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 73       | 70.87%  |
| WiFi     | 26       | 25.24%  |
| Modem    | 2        | 1.94%   |
| Unknown  | 2        | 1.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 68       | 82.93%  |
| WiFi     | 14       | 17.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 47       | 64.38%  |
| 2     | 20       | 27.4%   |
| 3     | 5        | 6.85%   |
| 5     | 1        | 1.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 72       | 98.63%  |
| Yes  | 1        | 1.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 12       | 66.67%  |
| Cambridge Silicon Radio  | 2        | 11.11%  |
| Broadcom                 | 2        | 11.11%  |
| HTC (High Tech Computer) | 1        | 5.56%   |
| ASUSTek Computer         | 1        | 5.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 5        | 27.78%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 16.67%  |
| Intel Bluetooth wireless interface                                   | 3        | 16.67%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2        | 11.11%  |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 11.11%  |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 5.56%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 5.56%   |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 1        | 5.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Nvidia               | 40       | 30.3%   |
| Intel                | 38       | 28.79%  |
| AMD                  | 36       | 27.27%  |
| Logitech             | 3        | 2.27%   |
| C-Media Electronics  | 3        | 2.27%   |
| VIA Technologies     | 2        | 1.52%   |
| SteelSeries ApS      | 2        | 1.52%   |
| Creative Labs        | 2        | 1.52%   |
| RODE Microphones     | 1        | 0.76%   |
| Nam Tai E&E Products | 1        | 0.76%   |
| JMTek                | 1        | 0.76%   |
| Focusrite-Novation   | 1        | 0.76%   |
| Creative Technology  | 1        | 0.76%   |
| Corsair              | 1        | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                              | 11       | 7.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                   | 10       | 6.49%   |
| Nvidia GP107GL High Definition Audio Controller                                       | 6        | 3.9%    |
| Nvidia GP104 High Definition Audio Controller                                         | 6        | 3.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                      | 6        | 3.9%    |
| Nvidia GK107 HDMI Audio Controller                                                    | 5        | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                   | 5        | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller            | 5        | 3.25%   |
| Intel 200 Series PCH HD Audio                                                         | 5        | 3.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                            | 5        | 3.25%   |
| Nvidia GP108 High Definition Audio Controller                                         | 4        | 2.6%    |
| Intel Cannon Lake PCH cAVS                                                            | 4        | 2.6%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                      | 4        | 2.6%    |
| AMD FCH Azalia Controller                                                             | 4        | 2.6%    |
| AMD Family 17h/19h HD Audio Controller                                                | 4        | 2.6%    |
| Nvidia TU106 High Definition Audio Controller                                         | 3        | 1.95%   |
| Nvidia GM206 High Definition Audio Controller                                         | 3        | 1.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                         | 3        | 1.95%   |
| Intel 9 Series Chipset Family HD Audio Controller                                     | 3        | 1.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                   | 3        | 1.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                       | 3        | 1.95%   |
| AMD Kabini HDMI/DP Audio                                                              | 3        | 1.95%   |
| SteelSeries ApS SteelSeries Arctis 7 Arctis 7 Chat Arctis 7 Game SteelSeries Arctis 7 | 2        | 1.3%    |
| Nvidia GP106 High Definition Audio Controller                                         | 2        | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                        | 2        | 1.3%    |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                         | 2        | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                    | 2        | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                   | 2        | 1.3%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]               | 2        | 1.3%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                          | 2        | 1.3%    |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller           | 1        | 0.65%   |
| VIA Technologies USB Audio Device                                                     | 1        | 0.65%   |
| RODE Microphones RDE NT-USB Mini                                                      | 1        | 0.65%   |
| Nvidia TU116 High Definition Audio Controller                                         | 1        | 0.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                        | 1        | 0.65%   |
| Nvidia TU104 HD Audio Controller                                                      | 1        | 0.65%   |
| Nvidia MCP73 High Definition Audio                                                    | 1        | 0.65%   |
| Nvidia High Definition Audio Controller                                               | 1        | 0.65%   |
| Nvidia GF116 High Definition Audio Controller                                         | 1        | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                                         | 1        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 14       | 16.87%  |
| G.Skill             | 14       | 16.87%  |
| Corsair             | 12       | 14.46%  |
| SK hynix            | 8        | 9.64%   |
| Samsung Electronics | 8        | 9.64%   |
| Crucial             | 7        | 8.43%   |
| Unknown             | 6        | 7.23%   |
| Nanya Technology    | 2        | 2.41%   |
| A-DATA Technology   | 2        | 2.41%   |
| Unknown             | 2        | 2.41%   |
| Undefined-00BA      | 1        | 1.2%    |
| TIMETEC             | 1        | 1.2%    |
| S                   | 1        | 1.2%    |
| Ramaxel Technology  | 1        | 1.2%    |
| Micron Technology   | 1        | 1.2%    |
| Kingmax             | 1        | 1.2%    |
| Elpida              | 1        | 1.2%    |
| Avant               | 1        | 1.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 5        | 5.75%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s     | 3        | 3.45%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s     | 2        | 2.3%    |
| Unknown                                                 | 2        | 2.3%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 1.15%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 1        | 1.15%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1        | 1.15%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s               | 1        | 1.15%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1        | 1.15%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 1        | 1.15%   |
| Undefined-00BA RAM Module 4GB DIMM DDR3 1333MT/s        | 1        | 1.15%   |
| TIMETEC RAM SD4-2666 16GB SODIMM DDR4 2666MT/s          | 1        | 1.15%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.15%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s    | 1        | 1.15%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s    | 1        | 1.15%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 1.15%   |
| SK hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR3 1333MT/s    | 1        | 1.15%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s | 1        | 1.15%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2667MT/s    | 1        | 1.15%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 1.15%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 1        | 1.15%   |
| Samsung RAM M393B5170FH0 4GB DIMM DDR3 1600MT/s         | 1        | 1.15%   |
| Samsung RAM M391B5273DH0-YH9 4GB DIMM DDR3 1333MT/s     | 1        | 1.15%   |
| Samsung RAM M391B5273DH0-CH9 4GB DIMM DDR3 1333MT/s     | 1        | 1.15%   |
| Samsung RAM M391A4G43MB1-CTD 32GB DIMM DDR4 3200MT/s    | 1        | 1.15%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 1        | 1.15%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.15%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.15%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s    | 1        | 1.15%   |
| S RAM Module 4GB DIMM DDR3 1600MT/s                     | 1        | 1.15%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s | 1        | 1.15%   |
| Nanya RAM NT2GT72U8PD0BY-3C 2GB DIMM DDR2 667MT/s       | 1        | 1.15%   |
| Nanya RAM M2F4G64CB8HB5N-CG 4GB DIMM DDR3 1333MT/s      | 1        | 1.15%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s     | 1        | 1.15%   |
| Kingston RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 1.15%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 1.15%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s    | 1        | 1.15%   |
| Kingston RAM KHX3000C15/16GX 16GB DIMM DDR4 2400MT/s    | 1        | 1.15%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s       | 1        | 1.15%   |
| Kingston RAM KHX2666C13/8GX 8GB DIMM DDR4 2400MT/s      | 1        | 1.15%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 41       | 56.16%  |
| DDR3    | 27       | 36.99%  |
| Unknown | 3        | 4.11%   |
| DDR2    | 2        | 2.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 67       | 91.78%  |
| SODIMM | 6        | 8.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 36       | 48.65%  |
| 4096  | 18       | 24.32%  |
| 16384 | 10       | 13.51%  |
| 2048  | 7        | 9.46%   |
| 32768 | 3        | 4.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 17       | 21.52%  |
| 3200  | 15       | 18.99%  |
| 1333  | 11       | 13.92%  |
| 2400  | 10       | 12.66%  |
| 2667  | 5        | 6.33%   |
| 2133  | 5        | 6.33%   |
| 2666  | 4        | 5.06%   |
| 3600  | 2        | 2.53%   |
| 1867  | 2        | 2.53%   |
| 800   | 2        | 2.53%   |
| 3333  | 1        | 1.27%   |
| 3066  | 1        | 1.27%   |
| 3000  | 1        | 1.27%   |
| 1067  | 1        | 1.27%   |
| 1066  | 1        | 1.27%   |
| 667   | 1        | 1.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 1        | 50%     |
| Brother Industries | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model              | Desktops | Percent |
|--------------------|----------|---------|
| HP HP Laser 107w   | 1        | 50%     |
| Brother MFC-J485DW | 1        | 50%     |

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

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Logitech            | 5        | 62.5%   |
| Xiongmai            | 1        | 12.5%   |
| Trust               | 1        | 12.5%   |
| Chicony Electronics | 1        | 12.5%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920           | 2        | 25%     |
| Xiongmai web camera                   | 1        | 12.5%   |
| Trust Trust USB Camera                | 1        | 12.5%   |
| Logitech Webcam C310                  | 1        | 12.5%   |
| Logitech HD Webcam C525               | 1        | 12.5%   |
| Logitech C920 HD Pro Webcam           | 1        | 12.5%   |
| Chicony HP High Definition 1MP Webcam | 1        | 12.5%   |

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
| 1     | 37       | 50.68%  |
| 0     | 18       | 24.66%  |
| 2     | 15       | 20.55%  |
| 3     | 3        | 4.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 33       | 44.59%  |
| Bluetooth                | 13       | 17.57%  |
| Net/wireless             | 9        | 12.16%  |
| Firewire controller      | 7        | 9.46%   |
| Sound                    | 4        | 5.41%   |
| Network                  | 3        | 4.05%   |
| Card reader              | 3        | 4.05%   |
| Net/ethernet             | 1        | 1.35%   |
| Modem                    | 1        | 1.35%   |

