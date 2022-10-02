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

Total: 88

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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
| GhostBSD 20.04.02 | 45       | 65.22%  |
| GhostBSD 21.08.27 | 8        | 11.59%  |
| GhostBSD 22.01.12 | 4        | 5.8%    |
| GhostBSD 22.07.16 | 2        | 2.9%    |
| GhostBSD 22.04.06 | 2        | 2.9%    |
| GhostBSD 22.09.16 | 1        | 1.45%   |
| GhostBSD 22.08.23 | 1        | 1.45%   |
| GhostBSD 22.07.13 | 1        | 1.45%   |
| GhostBSD 22.06.26 | 1        | 1.45%   |
| GhostBSD 22.05.14 | 1        | 1.45%   |
| GhostBSD 22.04.22 | 1        | 1.45%   |
| GhostBSD 22.01.28 | 1        | 1.45%   |
| GhostBSD 19.12    | 1        | 1.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GhostBSD | 67       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 67       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| MATE             | 50       | 72.46%  |
| XFCE             | 9        | 13.04%  |
| KDE5             | 4        | 5.8%    |
| openbox          | 1        | 1.45%   |
| Metacity (Marco) | 1        | 1.45%   |
| LXQt             | 1        | 1.45%   |
| i3               | 1        | 1.45%   |
| GNOME            | 1        | 1.45%   |
| Cinnamon         | 1        | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 67       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 65       | 97.01%  |
| SDDM    | 2        | 2.99%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 30       | 44.12%  |
| C       | 11       | 16.18%  |
| Unknown | 11       | 16.18%  |
| de_DE   | 6        | 8.82%   |
| ru_RU   | 4        | 5.88%   |
| fr_FR   | 2        | 2.94%   |
| sk_SK   | 1        | 1.47%   |
| es_ES   | 1        | 1.47%   |
| en_GB   | 1        | 1.47%   |
| en_AU   | 1        | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 53       | 79.1%   |
| BIOS | 14       | 20.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 64       | 95.52%  |
| Ufs  | 3        | 4.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 63       | 94.03%  |
| MBR  | 4        | 5.97%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 14       | 20.9%   |
| Gigabyte Technology | 12       | 17.91%  |
| Dell                | 9        | 13.43%  |
| ASRock              | 9        | 13.43%  |
| MSI                 | 8        | 11.94%  |
| Lenovo              | 4        | 5.97%   |
| Hewlett-Packard     | 2        | 2.99%   |
| Fujitsu             | 2        | 2.99%   |
| Acer                | 2        | 2.99%   |
| Quanta              | 1        | 1.49%   |
| Medion              | 1        | 1.49%   |
| Huanan              | 1        | 1.49%   |
| Alienware           | 1        | 1.49%   |
| Unknown             | 1        | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| MSI MS-7B86                                                           | 2        | 2.99%   |
| MSI MS-7817                                                           | 2        | 2.99%   |
| Quanta 120-1333w                                                      | 1        | 1.49%   |
| MSI MS-7C36                                                           | 1        | 1.49%   |
| MSI MS-7A72                                                           | 1        | 1.49%   |
| MSI MS-7917                                                           | 1        | 1.49%   |
| MSI MS-7788                                                           | 1        | 1.49%   |
| Medion MS-7728                                                        | 1        | 1.49%   |
| Lenovo ThinkStation S10 6483CTO                                       | 1        | 1.49%   |
| Lenovo ThinkCentre M93p 10AB004DUS                                    | 1        | 1.49%   |
| Lenovo ThinkCentre Edge72 3493DEG                                     | 1        | 1.49%   |
| Lenovo H515s 10126                                                    | 1        | 1.49%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1        | 1.49%   |
| HP Z400 Workstation                                                   | 1        | 1.49%   |
| HP Compaq Pro 6305 SFF                                                | 1        | 1.49%   |
| Gigabyte Z97-D3H                                                      | 1        | 1.49%   |
| Gigabyte Z77M-D3H                                                     | 1        | 1.49%   |
| Gigabyte Z370 AORUS Ultra Gaming                                      | 1        | 1.49%   |
| Gigabyte Z170X-UD5 TH                                                 | 1        | 1.49%   |
| Gigabyte X570 AORUS MASTER                                            | 1        | 1.49%   |
| Gigabyte X470 AORUS ULTRA GAMING                                      | 1        | 1.49%   |
| Gigabyte H67A-UD3H-B3                                                 | 1        | 1.49%   |
| Gigabyte H510M H                                                      | 1        | 1.49%   |
| Gigabyte F2A68HM-DS2                                                  | 1        | 1.49%   |
| Gigabyte EG43M-S2H                                                    | 1        | 1.49%   |
| Gigabyte B365M DS3H                                                   | 1        | 1.49%   |
| Gigabyte AX370-Gaming 3                                               | 1        | 1.49%   |
| Fujitsu ESPRIMO P1500                                                 | 1        | 1.49%   |
| Fujitsu CELSIUS W580                                                  | 1        | 1.49%   |
| Dell Precision WorkStation T3400                                      | 1        | 1.49%   |
| Dell Precision T5600                                                  | 1        | 1.49%   |
| Dell Precision 3630 Tower                                             | 1        | 1.49%   |
| Dell OptiPlex 9020                                                    | 1        | 1.49%   |
| Dell OptiPlex 790                                                     | 1        | 1.49%   |
| Dell OptiPlex 7050                                                    | 1        | 1.49%   |
| Dell OptiPlex 5060                                                    | 1        | 1.49%   |
| Dell OptiPlex 3080                                                    | 1        | 1.49%   |
| Dell G5 5090                                                          | 1        | 1.49%   |
| ASUS Z170I PRO GAMING                                                 | 1        | 1.49%   |
| ASUS TUF GAMING X570-PRO                                              | 1        | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 6        | 8.96%   |
| Dell OptiPlex         | 5        | 7.46%   |
| Dell Precision        | 3        | 4.48%   |
| ASUS TUF              | 3        | 4.48%   |
| ASRock X570           | 3        | 4.48%   |
| MSI MS-7B86           | 2        | 2.99%   |
| MSI MS-7817           | 2        | 2.99%   |
| Lenovo ThinkCentre    | 2        | 2.99%   |
| ASUS ROG              | 2        | 2.99%   |
| ASRock B450           | 2        | 2.99%   |
| Acer Aspire           | 2        | 2.99%   |
| Quanta 120-1333w      | 1        | 1.49%   |
| MSI MS-7C36           | 1        | 1.49%   |
| MSI MS-7A72           | 1        | 1.49%   |
| MSI MS-7917           | 1        | 1.49%   |
| MSI MS-7788           | 1        | 1.49%   |
| Medion MS-7728        | 1        | 1.49%   |
| Lenovo ThinkStation   | 1        | 1.49%   |
| Lenovo H515s          | 1        | 1.49%   |
| Huanan X79            | 1        | 1.49%   |
| HP Z400               | 1        | 1.49%   |
| HP Compaq             | 1        | 1.49%   |
| Gigabyte Z97-D3H      | 1        | 1.49%   |
| Gigabyte Z77M-D3H     | 1        | 1.49%   |
| Gigabyte Z370         | 1        | 1.49%   |
| Gigabyte Z170X-UD5    | 1        | 1.49%   |
| Gigabyte X570         | 1        | 1.49%   |
| Gigabyte X470         | 1        | 1.49%   |
| Gigabyte H67A-UD3H-B3 | 1        | 1.49%   |
| Gigabyte H510M        | 1        | 1.49%   |
| Gigabyte F2A68HM-DS2  | 1        | 1.49%   |
| Gigabyte EG43M-S2H    | 1        | 1.49%   |
| Gigabyte B365M        | 1        | 1.49%   |
| Gigabyte AX370-Gaming | 1        | 1.49%   |
| Fujitsu ESPRIMO       | 1        | 1.49%   |
| Fujitsu CELSIUS       | 1        | 1.49%   |
| Dell G5               | 1        | 1.49%   |
| ASUS Z170I            | 1        | 1.49%   |
| ASUS SABERTOOTH       | 1        | 1.49%   |
| ASUS All              | 1        | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 12       | 17.91%  |
| 2019 | 11       | 16.42%  |
| 2020 | 7        | 10.45%  |
| 2012 | 6        | 8.96%   |
| 2014 | 5        | 7.46%   |
| 2016 | 4        | 5.97%   |
| 2008 | 4        | 5.97%   |
| 2022 | 3        | 4.48%   |
| 2015 | 3        | 4.48%   |
| 2013 | 3        | 4.48%   |
| 2011 | 3        | 4.48%   |
| 2021 | 2        | 2.99%   |
| 2017 | 2        | 2.99%   |
| 2010 | 1        | 1.49%   |
| 2009 | 1        | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 67       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 67       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 19       | 28.36%  |
| 32.01-64.0  | 17       | 25.37%  |
| 8.01-16.0   | 17       | 25.37%  |
| 4.01-8.0    | 9        | 13.43%  |
| 64.01-256.0 | 4        | 5.97%   |
| 24.01-32.0  | 1        | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 26       | 38.81%  |
| 0.01-0.5 | 22       | 32.84%  |
| 1.01-2.0 | 15       | 22.39%  |
| 3.01-4.0 | 4        | 5.97%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 28       | 40%     |
| 1      | 21       | 30%     |
| 3      | 6        | 8.57%   |
| 5      | 5        | 7.14%   |
| 4      | 5        | 7.14%   |
| 6      | 2        | 2.86%   |
| 22     | 1        | 1.43%   |
| 7      | 1        | 1.43%   |
| 0      | 1        | 1.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 56.72%  |
| Yes       | 29       | 43.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 67       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 42       | 62.69%  |
| Yes       | 25       | 37.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 48       | 71.64%  |
| Yes       | 19       | 28.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 18       | 26.87%  |
| Germany     | 10       | 14.93%  |
| Russia      | 5        | 7.46%   |
| France      | 5        | 7.46%   |
| UK          | 4        | 5.97%   |
| Canada      | 3        | 4.48%   |
| Norway      | 2        | 2.99%   |
| Netherlands | 2        | 2.99%   |
| Malaysia    | 2        | 2.99%   |
| Czechia     | 2        | 2.99%   |
| Australia   | 2        | 2.99%   |
| Argentina   | 2        | 2.99%   |
| Ukraine     | 1        | 1.49%   |
| Switzerland | 1        | 1.49%   |
| Sweden      | 1        | 1.49%   |
| Spain       | 1        | 1.49%   |
| Mexico      | 1        | 1.49%   |
| Luxembourg  | 1        | 1.49%   |
| Japan       | 1        | 1.49%   |
| Hungary     | 1        | 1.49%   |
| Finland     | 1        | 1.49%   |
| China       | 1        | 1.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                        | Desktops | Percent |
|-----------------------------|----------|---------|
| Paris                       | 3        | 4.48%   |
| Berlin                      | 3        | 4.48%   |
| Obninsk                     | 2        | 2.99%   |
| Denver                      | 2        | 2.99%   |
| ЕЊta-ku                   | 1        | 1.49%   |
| Zapopan                     | 1        | 1.49%   |
| Washington                  | 1        | 1.49%   |
| Vidnoye                     | 1        | 1.49%   |
| Veenendaal                  | 1        | 1.49%   |
| Truro                       | 1        | 1.49%   |
| Traunstein                  | 1        | 1.49%   |
| Sydney                      | 1        | 1.49%   |
| St. Albert                  | 1        | 1.49%   |
| St Petersburg               | 1        | 1.49%   |
| Springfield                 | 1        | 1.49%   |
| Southampton                 | 1        | 1.49%   |
| San Nicolás de los Arroyos | 1        | 1.49%   |
| San Jose                    | 1        | 1.49%   |
| Salem                       | 1        | 1.49%   |
| Robbins                     | 1        | 1.49%   |
| Riedstadt                   | 1        | 1.49%   |
| Richmond                    | 1        | 1.49%   |
| Prague                      | 1        | 1.49%   |
| Phoenix                     | 1        | 1.49%   |
| Palm Bay                    | 1        | 1.49%   |
| Oslo                        | 1        | 1.49%   |
| Omaha                       | 1        | 1.49%   |
| Moncton                     | 1        | 1.49%   |
| Madrid                      | 1        | 1.49%   |
| Luxembourg                  | 1        | 1.49%   |
| Ludwigsburg                 | 1        | 1.49%   |
| Lorient                     | 1        | 1.49%   |
| London                      | 1        | 1.49%   |
| Larnod                      | 1        | 1.49%   |
| Kyiv                        | 1        | 1.49%   |
| Kuala Lumpur                | 1        | 1.49%   |
| Kaplice                     | 1        | 1.49%   |
| JГ¶nkГ¶ping             | 1        | 1.49%   |
| JyvГ¤skylГ¤             | 1        | 1.49%   |
| Huntingdon                  | 1        | 1.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 32       | 49     | 23.7%   |
| Samsung Electronics | 25       | 33     | 18.52%  |
| Seagate             | 18       | 27     | 13.33%  |
| Crucial             | 12       | 13     | 8.89%   |
| Toshiba             | 7        | 8      | 5.19%   |
| Hitachi             | 6        | 6      | 4.44%   |
| SanDisk             | 3        | 4      | 2.22%   |
| Micron Technology   | 3        | 3      | 2.22%   |
| Kingston            | 3        | 3      | 2.22%   |
| HGST                | 3        | 3      | 2.22%   |
| A-DATA Technology   | 3        | 3      | 2.22%   |
| PNY                 | 2        | 4      | 1.48%   |
| OCZ                 | 2        | 2      | 1.48%   |
| Maxtor              | 2        | 2      | 1.48%   |
| Intel               | 2        | 2      | 1.48%   |
| XPG                 | 1        | 1      | 0.74%   |
| Transcend           | 1        | 1      | 0.74%   |
| SPCC                | 1        | 1      | 0.74%   |
| Plextor             | 1        | 1      | 0.74%   |
| Phison              | 1        | 2      | 0.74%   |
| Patriot             | 1        | 1      | 0.74%   |
| LDLC                | 1        | 1      | 0.74%   |
| HPT                 | 1        | 4      | 0.74%   |
| Gigabyte Technology | 1        | 1      | 0.74%   |
| Corsair             | 1        | 1      | 0.74%   |
| China               | 1        | 1      | 0.74%   |
| AMD                 | 1        | 1      | 0.74%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Crucial CT1000MX500SSD1 1TB     | 4        | 2.53%   |
| Samsung SSD 850 EVO 500GB       | 3        | 1.9%    |
| Samsung SSD 850 EVO 250GB       | 3        | 1.9%    |
| WDC WD40EFRX-68N32N0 4TB        | 2        | 1.27%   |
| WDC WD2000JS-55MHB0 192GB       | 2        | 1.27%   |
| WDC WD10EZEX-21M2NA0 1TB        | 2        | 1.27%   |
| Toshiba Q300 480GB              | 2        | 1.27%   |
| Toshiba HDWD120 2TB             | 2        | 1.27%   |
| Seagate ST500DM002-1BD142 500GB | 2        | 1.27%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 1.27%   |
| Samsung SSD 970 EVO 500GB       | 2        | 1.27%   |
| Samsung SSD 860 QVO 1TB         | 2        | 1.27%   |
| Maxtor STM3320613AS 320GB       | 2        | 1.27%   |
| Crucial CT250MX500SSD1 250GB    | 2        | 1.27%   |
| XPG GAMMIX S11 Pro 256GB        | 1        | 0.63%   |
| WDC WDS500G2B0A-00SM50 500GB    | 1        | 0.63%   |
| WDC WDS500G2B0A 500GB           | 1        | 0.63%   |
| WDC WDS480G2G0A-00JH30 480GB    | 1        | 0.63%   |
| WDC WDS240G2G0C-00AJM0 240GB    | 1        | 0.63%   |
| WDC WDS200T2B0B-00YS70 2TB      | 1        | 0.63%   |
| WDC WDS200T2B0A-00SM50 2TB      | 1        | 0.63%   |
| WDC WDS100T3X0C-00SJG0 1TB      | 1        | 0.63%   |
| WDC WDS100T2B0C-00PXH0 1TB      | 1        | 0.63%   |
| WDC WDS100T1X0E-00AFY0 1TB      | 1        | 0.63%   |
| WDC WD800BEVT-75ZCT2 80GB       | 1        | 0.63%   |
| WDC WD7500LPCX-00KHST0 752GB    | 1        | 0.63%   |
| WDC WD60EZRZ-00GZ5B1 6TB        | 1        | 0.63%   |
| WDC WD6003FFBX-68MU3N0 6TB      | 1        | 0.63%   |
| WDC WD50NMZW-59A8NS1 5TB        | 1        | 0.63%   |
| WDC WD5000LPLX-75ZNTT0 500GB    | 1        | 0.63%   |
| WDC WD5000BEVT-24A0RT0 500GB    | 1        | 0.63%   |
| WDC WD5000AAVS-00ZTB0 500GB     | 1        | 0.63%   |
| WDC WD5000AAKX-60U6AA0 500GB    | 1        | 0.63%   |
| WDC WD5000AAKX-00ERMA0 500GB    | 1        | 0.63%   |
| WDC WD5000AAKS-60WWPA0 500GB    | 1        | 0.63%   |
| WDC WD3200BEKT-75KA9T0 320GB    | 1        | 0.63%   |
| WDC WD2500AAJS-75M0A0 250GB     | 1        | 0.63%   |
| WDC WD20SPZX-22UA7T0 2TB        | 1        | 0.63%   |
| WDC WD20EZRZ-00Z5HB0 2TB        | 1        | 0.63%   |
| WDC WD2002FAEX-007BA0 2TB       | 1        | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 26       | 37     | 40.63%  |
| Seagate             | 17       | 25     | 26.56%  |
| Hitachi             | 6        | 6      | 9.38%   |
| Toshiba             | 5        | 6      | 7.81%   |
| Samsung Electronics | 4        | 5      | 6.25%   |
| HGST                | 3        | 3      | 4.69%   |
| Maxtor              | 2        | 2      | 3.13%   |
| HPT                 | 1        | 4      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 17       | 19     | 30.91%  |
| Crucial             | 10       | 11     | 18.18%  |
| WDC                 | 4        | 6      | 7.27%   |
| SanDisk             | 3        | 4      | 5.45%   |
| A-DATA Technology   | 3        | 3      | 5.45%   |
| Toshiba             | 2        | 2      | 3.64%   |
| PNY                 | 2        | 4      | 3.64%   |
| OCZ                 | 2        | 2      | 3.64%   |
| Micron Technology   | 2        | 2      | 3.64%   |
| Kingston            | 2        | 2      | 3.64%   |
| Transcend           | 1        | 1      | 1.82%   |
| SPCC                | 1        | 1      | 1.82%   |
| Seagate             | 1        | 1      | 1.82%   |
| Plextor             | 1        | 1      | 1.82%   |
| Patriot             | 1        | 1      | 1.82%   |
| Intel               | 1        | 1      | 1.82%   |
| China               | 1        | 1      | 1.82%   |
| AMD                 | 1        | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 45       | 88     | 43.69%  |
| SSD  | 39       | 63     | 37.86%  |
| NVMe | 19       | 27     | 18.45%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 64       | 151    | 77.11%  |
| NVMe | 19       | 27     | 22.89%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 49       | 71     | 48.04%  |
| 0.51-1.0   | 26       | 39     | 25.49%  |
| 1.01-2.0   | 13       | 18     | 12.75%  |
| 3.01-4.0   | 7        | 9      | 6.86%   |
| 4.01-10.0  | 5        | 10     | 4.9%    |
| 2.01-3.0   | 1        | 2      | 0.98%   |
| 10.01-20.0 | 1        | 2      | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 17       | 25%     |
| 1-20       | 17       | 25%     |
| 251-500    | 15       | 22.06%  |
| 501-1000   | 6        | 8.82%   |
| 51-100     | 6        | 8.82%   |
| Unknown    | 3        | 4.41%   |
| 21-50      | 2        | 2.94%   |
| 1001-2000  | 2        | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 55       | 80.88%  |
| 21-50   | 8        | 11.76%  |
| Unknown | 3        | 4.41%   |
| 51-100  | 2        | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Maxtor STM3320613AS 320GB       | 2        | 2      | 14.29%  |
| WDC WDS480G2G0A-00JH30 480GB    | 1        | 2      | 7.14%   |
| WDC WD5000AAKS-60WWPA0 500GB    | 1        | 1      | 7.14%   |
| WDC WD10EZEX-21M2NA0 1TB        | 1        | 1      | 7.14%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 7.14%   |
| Seagate ST500DM002-1BC142 500GB | 1        | 1      | 7.14%   |
| Seagate ST31500541AS 1.5TB      | 1        | 1      | 7.14%   |
| Samsung Electronics HD103SJ 1TB | 1        | 2      | 7.14%   |
| OCZ AGILITY3 240GB              | 1        | 1      | 7.14%   |
| Hitachi HTS725032A9A364 320GB   | 1        | 1      | 7.14%   |
| Hitachi HTS547575A9E384 752GB   | 1        | 1      | 7.14%   |
| Hitachi HTS541680J9SA00 80GB    | 1        | 1      | 7.14%   |
| Crucial CT1000MX500SSD1 1TB     | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 4      | 21.43%  |
| Seagate             | 3        | 3      | 21.43%  |
| Hitachi             | 3        | 3      | 21.43%  |
| Maxtor              | 2        | 2      | 14.29%  |
| Samsung Electronics | 1        | 2      | 7.14%   |
| OCZ                 | 1        | 1      | 7.14%   |
| Crucial             | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 3      | 27.27%  |
| Hitachi             | 3        | 3      | 27.27%  |
| WDC                 | 2        | 2      | 18.18%  |
| Maxtor              | 2        | 2      | 18.18%  |
| Samsung Electronics | 1        | 2      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 12     | 76.92%  |
| SSD  | 3        | 4      | 23.08%  |

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
| Works    | 65       | 158    | 82.28%  |
| Malfunc  | 13       | 16     | 16.46%  |
| Detected | 1        | 4      | 1.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 38       | 38.78%  |
| AMD                           | 29       | 29.59%  |
| Samsung Electronics           | 7        | 7.14%   |
| SanDisk                       | 4        | 4.08%   |
| Phison Electronics            | 3        | 3.06%   |
| ASMedia Technology            | 3        | 3.06%   |
| Micron/Crucial Technology     | 2        | 2.04%   |
| Marvell Technology Group      | 2        | 2.04%   |
| Silicon Motion                | 1        | 1.02%   |
| Seagate Technology            | 1        | 1.02%   |
| Nvidia                        | 1        | 1.02%   |
| Micron Technology             | 1        | 1.02%   |
| Kingston Technology Company   | 1        | 1.02%   |
| JMicron Technology            | 1        | 1.02%   |
| Integrated Technology Express | 1        | 1.02%   |
| HighPoint Technologies        | 1        | 1.02%   |
| ADATA Technology              | 1        | 1.02%   |
| Adaptec                       | 1        | 1.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 25       | 21.19%  |
| Intel SATA Controller [RAID mode]                                                       | 7        | 5.93%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 5.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5        | 4.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4        | 3.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 2.54%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 2.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3        | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 2.54%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 2.54%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 2.54%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 1.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.69%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 1.69%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 1.69%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 1.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.69%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2        | 1.69%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 1.69%   |
| AMD FCH SATA Controller D                                                               | 2        | 1.69%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.85%   |
| Seagate FireCuda 520 SSD                                                                | 1        | 0.85%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.85%   |
| SanDisk unknown                                                                         | 1        | 0.85%   |
| SanDisk PC SN520 NVMe SSD                                                               | 1        | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.85%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.85%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 0.85%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.85%   |
| Micron/Crucial NVMe Controller                                                          | 1        | 0.85%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.85%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 1        | 0.85%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.85%   |
| JMicron JMB362 SATA Controller                                                          | 1        | 0.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 0.85%   |
| Intel SSD 660P Series                                                                   | 1        | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 55       | 59.14%  |
| NVMe | 19       | 20.43%  |
| IDE  | 9        | 9.68%   |
| RAID | 7        | 7.53%   |
| SCSI | 2        | 2.15%   |
| SAS  | 1        | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 38       | 56.72%  |
| AMD    | 29       | 43.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 3        | 4.48%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 4.48%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 4.48%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 2.99%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 2.99%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2        | 2.99%   |
| Intel Xeon E-2236 CPU @ 3.40GHz             | 1        | 1.49%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 1.49%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1        | 1.49%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GH           | 1        | 1.49%   |
| Intel Xeon                                  | 1        | 1.49%   |
| Intel Unknown                               | 1        | 1.49%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 1        | 1.49%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 1.49%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.49%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 1.49%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.49%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.49%   |
| Intel Core i7-3770S CPU @ 3.10GHz           | 1        | 1.49%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 1.49%   |
| Intel Core i7-2600K CPU                     | 1        | 1.49%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 1.49%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 1        | 1.49%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1        | 1.49%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 1.49%   |
| Intel Core i5-8400T CPU @ 1.70GHz           | 1        | 1.49%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 1.49%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 1.49%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 1.49%   |
| Intel Core i5-4690 CPU @ 3.50GHz            | 1        | 1.49%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.49%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 1.49%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.49%   |
| Intel Core i5-2500 CPU @ 3.30GH             | 1        | 1.49%   |
| Intel Core i5-10500T CPU @ 2.30GHz          | 1        | 1.49%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1        | 1.49%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 1.49%   |
| Intel Core i3-10105 CPU @ 3.70GHz           | 1        | 1.49%   |
| Intel Core 2 Quad CPU Q9400                 | 1        | 1.49%   |
| Intel Core 2 Quad CPU                       | 1        | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 14       | 20.9%   |
| Intel Core i7           | 11       | 16.42%  |
| AMD Ryzen 7             | 9        | 13.43%  |
| AMD Ryzen 5             | 8        | 11.94%  |
| Intel Xeon              | 5        | 7.46%   |
| Intel Core i3           | 3        | 4.48%   |
| AMD Ryzen 9             | 3        | 4.48%   |
| Intel Core 2 Quad       | 2        | 2.99%   |
| AMD Ryzen 3             | 2        | 2.99%   |
| AMD E1                  | 2        | 2.99%   |
| Other                   | 1        | 1.49%   |
| Intel Pentium Dual-Core | 1        | 1.49%   |
| Intel Pentium           | 1        | 1.49%   |
| AMD Ryzen 3 PRO         | 1        | 1.49%   |
| AMD E2                  | 1        | 1.49%   |
| AMD Athlon X4           | 1        | 1.49%   |
| AMD A6                  | 1        | 1.49%   |
| AMD A10                 | 1        | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 25       | 37.31%  |
| 16      | 9        | 13.43%  |
| 12      | 8        | 11.94%  |
| 6       | 8        | 11.94%  |
| 2       | 8        | 11.94%  |
| 8       | 4        | 5.97%   |
| 32      | 2        | 2.99%   |
| Unknown | 2        | 2.99%   |
| 24      | 1        | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 66       | 98.51%  |
| 2      | 1        | 1.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 47       | 70.15%  |
| 2       | 18       | 26.87%  |
| Unknown | 2        | 2.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 10       | 14.93%  |
| Zen 2       | 9        | 13.43%  |
| Zen+        | 7        | 10.45%  |
| Haswell     | 7        | 10.45%  |
| SandyBridge | 6        | 8.96%   |
| Penryn      | 5        | 7.46%   |
| Zen 3       | 4        | 5.97%   |
| Zen         | 3        | 4.48%   |
| Skylake     | 3        | 4.48%   |
| IvyBridge   | 3        | 4.48%   |
| Piledriver  | 2        | 2.99%   |
| CometLake   | 2        | 2.99%   |
| Westmere    | 1        | 1.49%   |
| Puma        | 1        | 1.49%   |
| Nehalem     | 1        | 1.49%   |
| Jaguar      | 1        | 1.49%   |
| Excavator   | 1        | 1.49%   |
| Bobcat      | 1        | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 38       | 53.52%  |
| AMD    | 17       | 23.94%  |
| Intel  | 16       | 22.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5        | 6.94%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4        | 5.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 4.17%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 4.17%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 4.17%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 3        | 4.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 4.17%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 2.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 2.78%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2        | 2.78%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 2.78%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 2.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2        | 2.78%   |
| Intel HD Graphics 630                                                       | 2        | 2.78%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 2.78%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 1.39%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 1.39%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 1.39%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 1.39%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 1.39%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.39%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 1.39%   |
| Nvidia GK107 [GeForce GT 740]                                               | 1        | 1.39%   |
| Nvidia GK107 [GeForce GT 640]                                               | 1        | 1.39%   |
| Nvidia GF108GL [Quadro 600]                                                 | 1        | 1.39%   |
| Nvidia GF100GL [Quadro 4000]                                                | 1        | 1.39%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.39%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 1.39%   |
| Intel HD Graphics 620                                                       | 1        | 1.39%   |
| Intel HD Graphics 530                                                       | 1        | 1.39%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 1.39%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 1.39%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.39%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 1.39%   |
| AMD Wrestler [Radeon HD 7310]                                               | 1        | 1.39%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 1        | 1.39%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.39%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.39%   |
| AMD Mullins [Radeon R2 Graphics]                                            | 1        | 1.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 33       | 49.25%  |
| 1 x AMD        | 16       | 23.88%  |
| 1 x Intel      | 12       | 17.91%  |
| Intel + Nvidia | 3        | 4.48%   |
| 2 x Nvidia     | 1        | 1.49%   |
| 2 x Intel      | 1        | 1.49%   |
| AMD + Nvidia   | 1        | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Proprietary | 34       | 50.75%  |
| Free        | 33       | 49.25%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 39.71%  |
| 7.01-8.0   | 10       | 14.71%  |
| 1.01-2.0   | 10       | 14.71%  |
| 3.01-4.0   | 8        | 11.76%  |
| 0.51-1.0   | 8        | 11.76%  |
| 0.01-0.5   | 3        | 4.41%   |
| 2.01-3.0   | 1        | 1.47%   |
| 8.01-16.0  | 1        | 1.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 10       | 14.71%  |
| Samsung Electronics  | 8        | 11.76%  |
| Goldstar             | 7        | 10.29%  |
| BenQ                 | 6        | 8.82%   |
| Acer                 | 4        | 5.88%   |
| Philips              | 3        | 4.41%   |
| Hewlett-Packard      | 3        | 4.41%   |
| AOC                  | 3        | 4.41%   |
| Vizio                | 2        | 2.94%   |
| ViewSonic            | 2        | 2.94%   |
| LG Electronics       | 2        | 2.94%   |
| Lenovo               | 2        | 2.94%   |
| Iiyama               | 2        | 2.94%   |
| Fujitsu Siemens      | 2        | 2.94%   |
| ASUSTek Computer     | 2        | 2.94%   |
| WYT                  | 1        | 1.47%   |
| Toshiba              | 1        | 1.47%   |
| SAC                  | 1        | 1.47%   |
| Pixio                | 1        | 1.47%   |
| OEM                  | 1        | 1.47%   |
| Mi                   | 1        | 1.47%   |
| Idek Iiyama          | 1        | 1.47%   |
| HannStar             | 1        | 1.47%   |
| CHD                  | 1        | 1.47%   |
| Ancor Communications | 1        | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 2        | 2.78%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                   | 1        | 1.39%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                    | 1        | 1.39%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                    | 1        | 1.39%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch              | 1        | 1.39%   |
| ViewSonic LCD Monitor VA1938 Series                                    | 1        | 1.39%   |
| Toshiba TV TSB010F 1920x1080 890x500mm 40.2-inch                       | 1        | 1.39%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch      | 1        | 1.39%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 600x340mm 27.2-inch    | 1        | 1.39%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 480x270mm 21.7-inch     | 1        | 1.39%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch  | 1        | 1.39%   |
| Samsung Electronics S24E650 SAM0CC1 1920x1200 520x320mm 24.0-inch      | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1        | 1.39%   |
| Samsung Electronics LCD Monitor SAM02A4 1360x768                       | 1        | 1.39%   |
| SAC LED MONITOR SAC952D 1920x1080 470x280mm 21.5-inch                  | 1        | 1.39%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                      | 1        | 1.39%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 1.39%   |
| Philips LCD Monitor PHL 240V5 1920x1080                                | 1        | 1.39%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1        | 1.39%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                        | 1        | 1.39%   |
| Mi Redmi 27 NQ XMIE001 2560x1440 600x330mm 27.0-inch                   | 1        | 1.39%   |
| LG Electronics LCD Monitor W1952 2806x900                              | 1        | 1.39%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 1        | 1.39%   |
| Lenovo V20-10 LEN65DC 1600x900 430x240mm 19.4-inch                     | 1        | 1.39%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch               | 1        | 1.39%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                   | 1        | 1.39%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                   | 1        | 1.39%   |
| Idek Iiyama LCD Monitor PL3270Q 5120x1440                              | 1        | 1.39%   |
| Idek Iiyama LCD Monitor PL3270Q                                        | 1        | 1.39%   |
| Hewlett-Packard w1907 HWP26A3 1440x900 410x260mm 19.1-inch             | 1        | 1.39%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 1.39%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch           | 1        | 1.39%   |
| HannStar LCD Monitor HSD2469 1680x1050 470x300mm 22.0-inch             | 1        | 1.39%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                   | 1        | 1.39%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 1        | 1.39%   |
| Goldstar LG ULTRAWIDE GSM76FA 2560x1080 800x340mm 34.2-inch            | 1        | 1.39%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 1        | 1.39%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1        | 1.39%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 32       | 45.07%  |
| 2560x1440 (QHD)    | 8        | 11.27%  |
| 3840x2160 (4K)     | 6        | 8.45%   |
| 1280x1024 (SXGA)   | 4        | 5.63%   |
| 2560x1080          | 3        | 4.23%   |
| 1600x900 (HD+)     | 3        | 4.23%   |
| Unknown            | 3        | 4.23%   |
| 1680x1050 (WSXGA+) | 2        | 2.82%   |
| 1440x900 (WXGA+)   | 2        | 2.82%   |
| 1360x768           | 2        | 2.82%   |
| 5120x1440          | 1        | 1.41%   |
| 3840x1600          | 1        | 1.41%   |
| 3200x1080          | 1        | 1.41%   |
| 2806x900           | 1        | 1.41%   |
| 1920x540           | 1        | 1.41%   |
| 1920x1200 (WUXGA)  | 1        | 1.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 12       | 17.65%  |
| 27      | 10       | 14.71%  |
| 24      | 9        | 13.24%  |
| Unknown | 9        | 13.24%  |
| 19      | 7        | 10.29%  |
| 23      | 6        | 8.82%   |
| 31      | 4        | 5.88%   |
| 54      | 2        | 2.94%   |
| 34      | 2        | 2.94%   |
| 22      | 2        | 2.94%   |
| 65      | 1        | 1.47%   |
| 40      | 1        | 1.47%   |
| 32      | 1        | 1.47%   |
| 17      | 1        | 1.47%   |
| 16      | 1        | 1.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 22       | 32.84%  |
| 401-500     | 18       | 26.87%  |
| Unknown     | 9        | 13.43%  |
| 601-700     | 7        | 10.45%  |
| 701-800     | 3        | 4.48%   |
| 1001-1500   | 3        | 4.48%   |
| 351-400     | 2        | 2.99%   |
| 301-350     | 2        | 2.99%   |
| 801-900     | 1        | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 46       | 70.77%  |
| Unknown | 7        | 10.77%  |
| 16/10   | 5        | 7.69%   |
| 5/4     | 3        | 4.62%   |
| 21/9    | 2        | 3.08%   |
| 6/5     | 1        | 1.54%   |
| 32/9    | 1        | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 26       | 38.81%  |
| 301-350        | 10       | 14.93%  |
| Unknown        | 9        | 13.43%  |
| 351-500        | 7        | 10.45%  |
| 151-200        | 7        | 10.45%  |
| More than 1000 | 3        | 4.48%   |
| 251-300        | 2        | 2.99%   |
| 141-150        | 1        | 1.49%   |
| 131-140        | 1        | 1.49%   |
| 501-1000       | 1        | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 37       | 53.62%  |
| 101-120 | 16       | 23.19%  |
| Unknown | 9        | 13.04%  |
| 121-160 | 4        | 5.8%    |
| 1-50    | 2        | 2.9%    |
| 161-240 | 1        | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 49       | 72.06%  |
| 2     | 11       | 16.18%  |
| 0     | 8        | 11.76%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 34       | 37.78%  |
| Realtek Semiconductor                 | 33       | 36.67%  |
| Qualcomm Atheros                      | 7        | 7.78%   |
| Broadcom                              | 5        | 5.56%   |
| TP-Link                               | 2        | 2.22%   |
| Ralink Technology                     | 1        | 1.11%   |
| Ralink                                | 1        | 1.11%   |
| Qualcomm Atheros Communications       | 1        | 1.11%   |
| Qualcomm                              | 1        | 1.11%   |
| Nvidia                                | 1        | 1.11%   |
| Microchip Technology                  | 1        | 1.11%   |
| Generic                               | 1        | 1.11%   |
| Aquantia                              | 1        | 1.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 1.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24       | 23.3%   |
| Intel I211 Gigabit Network Connection                             | 11       | 10.68%  |
| Intel Wi-Fi 6 AX200                                               | 6        | 5.83%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 4.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.91%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3        | 2.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 2.91%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2        | 1.94%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.94%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 1.94%   |
| TP-Link TP-LINK Wireless USB Adapter                              | 1        | 0.97%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.97%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.97%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.97%   |
| Ralink RT5370 Wireless Adapter                                    | 1        | 0.97%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 0.97%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.97%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1        | 0.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.97%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1        | 0.97%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.97%   |
| Microchip HTC Hub Controller                                      | 1        | 0.97%   |
| Intel Wireless-AC 9260                                            | 1        | 0.97%   |
| Intel Wireless 7265                                               | 1        | 0.97%   |
| Intel Wireless 7260                                               | 1        | 0.97%   |
| Intel Wireless 3165                                               | 1        | 0.97%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1        | 0.97%   |
| Intel Ethernet Controller I225-V                                  | 1        | 0.97%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.97%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.97%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.97%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.97%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.97%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 13       | 48.15%  |
| Realtek Semiconductor                 | 4        | 14.81%  |
| Qualcomm Atheros                      | 4        | 14.81%  |
| TP-Link                               | 2        | 7.41%   |
| Ralink Technology                     | 1        | 3.7%    |
| Ralink                                | 1        | 3.7%    |
| Qualcomm Atheros Communications       | 1        | 3.7%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                              | Desktops | Percent |
|------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                | 6        | 22.22%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                   | 3        | 11.11%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                   | 3        | 11.11%  |
| Realtek RTL8188EE Wireless Network Adapter                                         | 2        | 7.41%   |
| TP-Link TP-LINK Wireless USB Adapter                                               | 1        | 3.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                         | 1        | 3.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                           | 1        | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                | 1        | 3.7%    |
| Ralink RT5370 Wireless Adapter                                                     | 1        | 3.7%    |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                             | 1        | 3.7%    |
| Qualcomm Atheros AR9271 802.11n                                                    | 1        | 3.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                     | 1        | 3.7%    |
| Intel Wireless-AC 9260                                                             | 1        | 3.7%    |
| Intel Wireless 7265                                                                | 1        | 3.7%    |
| Intel Wireless 7260                                                                | 1        | 3.7%    |
| Intel Wireless 3165                                                                | 1        | 3.7%    |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB54GC v3 802.11g Adapter [Ralink RT2070L] | 1        | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 31       | 43.06%  |
| Intel                 | 30       | 41.67%  |
| Broadcom              | 5        | 6.94%   |
| Qualcomm Atheros      | 3        | 4.17%   |
| Qualcomm              | 1        | 1.39%   |
| Nvidia                | 1        | 1.39%   |
| Aquantia              | 1        | 1.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 24       | 32.88%  |
| Intel I211 Gigabit Network Connection                             | 11       | 15.07%  |
| Intel Ethernet Connection (2) I219-V                              | 5        | 6.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 4.11%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 2.74%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 2.74%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 2.74%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 1.37%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1        | 1.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 1.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 1.37%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1        | 1.37%   |
| Nvidia MCP73 Ethernet                                             | 1        | 1.37%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1        | 1.37%   |
| Intel Ethernet Controller I225-V                                  | 1        | 1.37%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.37%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.37%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.37%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.37%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.37%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.37%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.37%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 1.37%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.37%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 1.37%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 1.37%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 67       | 70.53%  |
| WiFi     | 25       | 26.32%  |
| Modem    | 2        | 2.11%   |
| Unknown  | 1        | 1.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 63       | 81.82%  |
| WiFi     | 14       | 18.18%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 43       | 64.18%  |
| 2     | 19       | 28.36%  |
| 3     | 5        | 7.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 66       | 98.51%  |
| Yes  | 1        | 1.49%   |

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
| Nvidia               | 38       | 30.89%  |
| Intel                | 35       | 28.46%  |
| AMD                  | 34       | 27.64%  |
| Logitech             | 3        | 2.44%   |
| VIA Technologies     | 2        | 1.63%   |
| SteelSeries ApS      | 2        | 1.63%   |
| Creative Labs        | 2        | 1.63%   |
| C-Media Electronics  | 2        | 1.63%   |
| RODE Microphones     | 1        | 0.81%   |
| Nam Tai E&E Products | 1        | 0.81%   |
| JMTek                | 1        | 0.81%   |
| Focusrite-Novation   | 1        | 0.81%   |
| Creative Technology  | 1        | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                              | 11       | 7.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                   | 9        | 6.38%   |
| Nvidia GP104 High Definition Audio Controller                                         | 6        | 4.26%   |
| Nvidia GP107GL High Definition Audio Controller                                       | 5        | 3.55%   |
| Nvidia GK107 HDMI Audio Controller                                                    | 5        | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller            | 5        | 3.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                            | 5        | 3.55%   |
| Nvidia GP108 High Definition Audio Controller                                         | 4        | 2.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                      | 4        | 2.84%   |
| Intel Cannon Lake PCH cAVS                                                            | 4        | 2.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                      | 4        | 2.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                   | 4        | 2.84%   |
| Intel 200 Series PCH HD Audio                                                         | 4        | 2.84%   |
| AMD FCH Azalia Controller                                                             | 4        | 2.84%   |
| Nvidia GM206 High Definition Audio Controller                                         | 3        | 2.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                         | 3        | 2.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                   | 3        | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                       | 3        | 2.13%   |
| AMD Kabini HDMI/DP Audio                                                              | 3        | 2.13%   |
| AMD Family 17h/19h HD Audio Controller                                                | 3        | 2.13%   |
| SteelSeries ApS SteelSeries Arctis 7 Arctis 7 Chat Arctis 7 Game SteelSeries Arctis 7 | 2        | 1.42%   |
| Nvidia TU106 High Definition Audio Controller                                         | 2        | 1.42%   |
| Nvidia GP106 High Definition Audio Controller                                         | 2        | 1.42%   |
| Intel 9 Series Chipset Family HD Audio Controller                                     | 2        | 1.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                        | 2        | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                    | 2        | 1.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]               | 2        | 1.42%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                          | 2        | 1.42%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller           | 1        | 0.71%   |
| VIA Technologies USB Audio Device                                                     | 1        | 0.71%   |
| RODE Microphones RDE NT-USB Mini                                                      | 1        | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                                         | 1        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                        | 1        | 0.71%   |
| Nvidia TU104 HD Audio Controller                                                      | 1        | 0.71%   |
| Nvidia MCP73 High Definition Audio                                                    | 1        | 0.71%   |
| Nvidia High Definition Audio Controller                                               | 1        | 0.71%   |
| Nvidia GF116 High Definition Audio Controller                                         | 1        | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                                         | 1        | 0.71%   |
| Nvidia GF100 High Definition Audio Controller                                         | 1        | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                                         | 1        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 13       | 16.88%  |
| G.Skill             | 13       | 16.88%  |
| Corsair             | 11       | 14.29%  |
| Samsung Electronics | 8        | 10.39%  |
| SK hynix            | 7        | 9.09%   |
| Unknown             | 6        | 7.79%   |
| Crucial             | 6        | 7.79%   |
| Nanya Technology    | 2        | 2.6%    |
| A-DATA Technology   | 2        | 2.6%    |
| Undefined-00BA      | 1        | 1.3%    |
| TIMETEC             | 1        | 1.3%    |
| S                   | 1        | 1.3%    |
| Ramaxel Technology  | 1        | 1.3%    |
| Micron Technology   | 1        | 1.3%    |
| Kingmax             | 1        | 1.3%    |
| Elpida              | 1        | 1.3%    |
| Avant               | 1        | 1.3%    |
| Unknown             | 1        | 1.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s   | 4        | 5.06%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s     | 3        | 3.8%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s               | 1        | 1.27%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 1        | 1.27%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 1        | 1.27%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s               | 1        | 1.27%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 1        | 1.27%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 1        | 1.27%   |
| Undefined-00BA RAM Module 4GB DIMM DDR3 1333MT/s        | 1        | 1.27%   |
| TIMETEC RAM SD4-2666 16GB SODIMM DDR4 2666MT/s          | 1        | 1.27%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.27%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s    | 1        | 1.27%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s    | 1        | 1.27%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s | 1        | 1.27%   |
| SK hynix RAM HMA81GU6JJR8N-VK 8GB DIMM DDR4 2666MT/s    | 1        | 1.27%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 1.27%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 1        | 1.27%   |
| Samsung RAM M393B5170FH0 4GB DIMM DDR3 1600MT/s         | 1        | 1.27%   |
| Samsung RAM M391B5273DH0-YH9 4GB DIMM DDR3 1333MT/s     | 1        | 1.27%   |
| Samsung RAM M391B5273DH0-CH9 4GB DIMM DDR3 1333MT/s     | 1        | 1.27%   |
| Samsung RAM M391A4G43MB1-CTD 32GB DIMM DDR4 3200MT/s    | 1        | 1.27%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 1        | 1.27%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.27%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.27%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s    | 1        | 1.27%   |
| S RAM Module 4GB DIMM DDR3 1600MT/s                     | 1        | 1.27%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s | 1        | 1.27%   |
| Nanya RAM NT2GT72U8PD0BY-3C 2GB DIMM DDR2 667MT/s       | 1        | 1.27%   |
| Nanya RAM M2F4G64CB8HB5N-CG 4GB DIMM DDR3 1333MT/s      | 1        | 1.27%   |
| Micron RAM 16ATF1G64AZ-2G1B1 8GB DIMM DDR4 2133MT/s     | 1        | 1.27%   |
| Kingston RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 1.27%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s              | 1        | 1.27%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s    | 1        | 1.27%   |
| Kingston RAM KHX3000C15/16GX 16GB DIMM DDR4 2400MT/s    | 1        | 1.27%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s       | 1        | 1.27%   |
| Kingston RAM KHX2666C13/8GX 8GB DIMM DDR4 2400MT/s      | 1        | 1.27%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 2400MT/s     | 1        | 1.27%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2133MT/s     | 1        | 1.27%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s     | 1        | 1.27%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 2400MT/s   | 1        | 1.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 38       | 56.72%  |
| DDR3    | 24       | 35.82%  |
| Unknown | 3        | 4.48%   |
| DDR2    | 2        | 2.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 61       | 91.04%  |
| SODIMM | 6        | 8.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 32       | 47.06%  |
| 4096  | 17       | 25%     |
| 16384 | 10       | 14.71%  |
| 2048  | 6        | 8.82%   |
| 32768 | 3        | 4.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 16       | 21.92%  |
| 3200  | 13       | 17.81%  |
| 1333  | 10       | 13.7%   |
| 2400  | 9        | 12.33%  |
| 2666  | 5        | 6.85%   |
| 2133  | 5        | 6.85%   |
| 2667  | 4        | 5.48%   |
| 3600  | 2        | 2.74%   |
| 800   | 2        | 2.74%   |
| 3333  | 1        | 1.37%   |
| 3066  | 1        | 1.37%   |
| 3000  | 1        | 1.37%   |
| 1867  | 1        | 1.37%   |
| 1067  | 1        | 1.37%   |
| 1066  | 1        | 1.37%   |
| 667   | 1        | 1.37%   |

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
| Logitech            | 4        | 57.14%  |
| Xiongmai            | 1        | 14.29%  |
| Trust               | 1        | 14.29%  |
| Chicony Electronics | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920           | 2        | 28.57%  |
| Xiongmai web camera                   | 1        | 14.29%  |
| Trust Trust USB Camera                | 1        | 14.29%  |
| Logitech Webcam C310                  | 1        | 14.29%  |
| Logitech C920 HD Pro Webcam           | 1        | 14.29%  |
| Chicony HP High Definition 1MP Webcam | 1        | 14.29%  |

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
| 1     | 35       | 52.24%  |
| 0     | 16       | 23.88%  |
| 2     | 13       | 19.4%   |
| 3     | 3        | 4.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 29       | 42.65%  |
| Bluetooth                | 13       | 19.12%  |
| Net/wireless             | 9        | 13.24%  |
| Firewire controller      | 7        | 10.29%  |
| Sound                    | 3        | 4.41%   |
| Card reader              | 3        | 4.41%   |
| Network                  | 2        | 2.94%   |
| Net/ethernet             | 1        | 1.47%   |
| Modem                    | 1        | 1.47%   |

