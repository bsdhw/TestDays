FreeBSD 14.1 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for FreeBSD 14.1.

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

Total: 61

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Biostar       | H610MHP                     | [2858dee74a](https://bsd-hardware.info/?probe=2858dee74a) | Feb 10, 2025 |
| HP            | 1998                        | [11fe9b837d](https://bsd-hardware.info/?probe=11fe9b837d) | Feb 07, 2025 |
| Dell          | 0JJ7YG A00                  | [60a9be6897](https://bsd-hardware.info/?probe=60a9be6897) | Jan 02, 2025 |
| Dell          | 01D4TT A00                  | [447a0925d1](https://bsd-hardware.info/?probe=447a0925d1) | Jan 02, 2025 |
| Dell          | 0JJ7YG A00                  | [f586af63cf](https://bsd-hardware.info/?probe=f586af63cf) | Jan 02, 2025 |
| ASRockRack    | EPYC3101D4I-2T              | [be896d46e1](https://bsd-hardware.info/?probe=be896d46e1) | Dec 31, 2024 |
| Gigabyte      | M68MT-S2                    | [0ac816abb8](https://bsd-hardware.info/?probe=0ac816abb8) | Dec 22, 2024 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [57a5cf527b](https://bsd-hardware.info/?probe=57a5cf527b) | Dec 08, 2024 |
| MSI           | B550M PRO-VDH               | [2bd3d72cbb](https://bsd-hardware.info/?probe=2bd3d72cbb) | Dec 06, 2024 |
| HP            | 1998                        | [6233446d5e](https://bsd-hardware.info/?probe=6233446d5e) | Dec 04, 2024 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [8fbade62a5](https://bsd-hardware.info/?probe=8fbade62a5) | Dec 04, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [a070b11044](https://bsd-hardware.info/?probe=a070b11044) | Nov 30, 2024 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [8282b592ac](https://bsd-hardware.info/?probe=8282b592ac) | Nov 27, 2024 |
| MSI           | H310M PRO-M2 PLUS           | [db040ae85a](https://bsd-hardware.info/?probe=db040ae85a) | Nov 26, 2024 |
| Gigabyte      | Z490 AORUS MASTER           | [acfb1a77bf](https://bsd-hardware.info/?probe=acfb1a77bf) | Nov 24, 2024 |
| Gigabyte      | B650M D3HP                  | [adf503f345](https://bsd-hardware.info/?probe=adf503f345) | Nov 06, 2024 |
| Gigabyte      | B650M D3HP                  | [fe8076ef02](https://bsd-hardware.info/?probe=fe8076ef02) | Nov 06, 2024 |
| Unknown       | Unknown                     | [85bc2300d4](https://bsd-hardware.info/?probe=85bc2300d4) | Nov 04, 2024 |
| MSI           | H310M PRO-M2 PLUS           | [8c3d77a23b](https://bsd-hardware.info/?probe=8c3d77a23b) | Oct 31, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [1c6bd76968](https://bsd-hardware.info/?probe=1c6bd76968) | Oct 31, 2024 |
| MSI           | H310M PRO-M2 PLUS           | [8ad31a1bad](https://bsd-hardware.info/?probe=8ad31a1bad) | Oct 30, 2024 |
| Dell          | 053CWD A00                  | [1a6b365ab4](https://bsd-hardware.info/?probe=1a6b365ab4) | Oct 30, 2024 |
| Gigabyte      | B450M S2H V2                | [1dd8ec6cbc](https://bsd-hardware.info/?probe=1dd8ec6cbc) | Oct 27, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | [2c4cb4fd49](https://bsd-hardware.info/?probe=2c4cb4fd49) | Oct 20, 2024 |
| Shenzhen M... | AHBNB OEM                   | [cb7d2d44d9](https://bsd-hardware.info/?probe=cb7d2d44d9) | Oct 14, 2024 |
| Gigabyte      | X99-UD4P-CF                 | [a7f00617a4](https://bsd-hardware.info/?probe=a7f00617a4) | Oct 12, 2024 |
| MSI           | PRO B550M-VC WIFI           | [566f6b1b2f](https://bsd-hardware.info/?probe=566f6b1b2f) | Oct 09, 2024 |
| MSI           | PRO B550M-VC WIFI           | [8ad5f1d680](https://bsd-hardware.info/?probe=8ad5f1d680) | Oct 09, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | [97e0c04743](https://bsd-hardware.info/?probe=97e0c04743) | Oct 07, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | [e4e1bf6fa2](https://bsd-hardware.info/?probe=e4e1bf6fa2) | Oct 05, 2024 |
| ASUSTek       | P7H55-M LX                  | [74ed82c97a](https://bsd-hardware.info/?probe=74ed82c97a) | Sep 30, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [eb2586d6b5](https://bsd-hardware.info/?probe=eb2586d6b5) | Sep 30, 2024 |
| Gigabyte      | X670E AORUS XTREME          | [3a93bb7f24](https://bsd-hardware.info/?probe=3a93bb7f24) | Sep 26, 2024 |
| Unknown       | Unknown                     | [170341d296](https://bsd-hardware.info/?probe=170341d296) | Sep 19, 2024 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [25bed13946](https://bsd-hardware.info/?probe=25bed13946) | Sep 15, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [a740cbb4da](https://bsd-hardware.info/?probe=a740cbb4da) | Aug 31, 2024 |
| Dell          | 06X1TJ A01                  | [a3a44c5d03](https://bsd-hardware.info/?probe=a3a44c5d03) | Aug 26, 2024 |
| MSI           | B550 GAMING GEN3            | [09c4b51ebb](https://bsd-hardware.info/?probe=09c4b51ebb) | Aug 12, 2024 |
| ASUSTek       | P5Q-E                       | [eb7aecd79c](https://bsd-hardware.info/?probe=eb7aecd79c) | Aug 11, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [3a97ebc128](https://bsd-hardware.info/?probe=3a97ebc128) | Aug 05, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d5924117c3](https://bsd-hardware.info/?probe=d5924117c3) | Aug 04, 2024 |
| Unknown       | DH61BR G32662-203           | [596a891e0a](https://bsd-hardware.info/?probe=596a891e0a) | Aug 04, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [f7134ef010](https://bsd-hardware.info/?probe=f7134ef010) | Jul 31, 2024 |
| ASUSTek       | STRIX B250G GAMING          | [f18c3a7168](https://bsd-hardware.info/?probe=f18c3a7168) | Jul 27, 2024 |
| Unknown       | DH61BR G32662-203           | [6e073b5233](https://bsd-hardware.info/?probe=6e073b5233) | Jul 26, 2024 |
| ASUSTek       | P5Q-E                       | [a93627695c](https://bsd-hardware.info/?probe=a93627695c) | Jul 14, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [444d8544de](https://bsd-hardware.info/?probe=444d8544de) | Jul 14, 2024 |
| iKOOLCORE ... | R2                          | [457c9ab408](https://bsd-hardware.info/?probe=457c9ab408) | Jul 14, 2024 |
| HP            | 83E8                        | [06b44184a4](https://bsd-hardware.info/?probe=06b44184a4) | Jul 09, 2024 |
| ASUSTek       | P5Q-E                       | [a33387b7a5](https://bsd-hardware.info/?probe=a33387b7a5) | Jul 07, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [e923df9fa3](https://bsd-hardware.info/?probe=e923df9fa3) | Jul 07, 2024 |
| MSI           | B450M-A PRO MAX             | [da4d14dbcb](https://bsd-hardware.info/?probe=da4d14dbcb) | Jul 03, 2024 |
| ASRockRack    | EPYC3101D4I-2T              | [38cebb1de0](https://bsd-hardware.info/?probe=38cebb1de0) | Jun 30, 2024 |
| Dell          | 0KC9NP A01                  | [bb7ac1fa79](https://bsd-hardware.info/?probe=bb7ac1fa79) | Jun 19, 2024 |
| ASUSTek       | Z10PA-U8 Series             | [ed87446558](https://bsd-hardware.info/?probe=ed87446558) | Jun 15, 2024 |
| ASUSTek       | Z10PA-U8 Series             | [386e93d33b](https://bsd-hardware.info/?probe=386e93d33b) | Jun 15, 2024 |
| MSI           | B450I GAMING PLUS MAX WI... | [8a90f18f6a](https://bsd-hardware.info/?probe=8a90f18f6a) | Jun 11, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [0b068fd252](https://bsd-hardware.info/?probe=0b068fd252) | Jun 07, 2024 |
| Dell          | 0Y2V0C A03                  | [efc4ae0ffc](https://bsd-hardware.info/?probe=efc4ae0ffc) | Jun 04, 2024 |
| ASRock        | X99 Extreme4                | [af182c3b9b](https://bsd-hardware.info/?probe=af182c3b9b) | Jun 04, 2024 |
| Dell          | 0Y2V0C A03                  | [515e7801ba](https://bsd-hardware.info/?probe=515e7801ba) | Jun 04, 2024 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 40       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Console     | 11       | 26.83%  |
| XFCE        | 8        | 19.51%  |
| KDE5        | 6        | 14.63%  |
| GNOME       | 6        | 14.63%  |
| TWM         | 5        | 12.2%   |
| WindowMaker | 1        | 2.44%   |
| Openbox     | 1        | 2.44%   |
| LXQt        | 1        | 2.44%   |
| i3          | 1        | 2.44%   |
| Hyprland    | 1        | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 27       | 67.5%   |
| Console | 11       | 27.5%   |
| Wayland | 2        | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 25       | 60.98%  |
| SDDM    | 7        | 17.07%  |
| LightDM | 5        | 12.2%   |
| GDM     | 3        | 7.32%   |
| Ly      | 1        | 2.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| C       | 31       | 75.61%  |
| Unknown | 5        | 12.2%   |
| en_US   | 2        | 4.88%   |
| pt_BR   | 1        | 2.44%   |
| fr_FR   | 1        | 2.44%   |
| es_ES   | 1        | 2.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 34       | 82.93%  |
| BIOS | 7        | 17.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Zfs    | 31       | 77.5%   |
| Ufs    | 8        | 20%     |
| Nullfs | 1        | 2.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 38       | 95%     |
| MBR     | 1        | 2.5%    |
| Unknown | 1        | 2.5%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| MSI                                  | 8        | 20%     |
| ASUSTek Computer                     | 8        | 20%     |
| Gigabyte Technology                  | 7        | 17.5%   |
| Dell                                 | 6        | 15%     |
| Hewlett-Packard                      | 3        | 7.5%    |
| Unknown                              | 3        | 7.5%    |
| Shenzhen Meigao Electronic Equipment | 1        | 2.5%    |
| iKOOLCORE TECHNOLOGY                 | 1        | 2.5%    |
| Biostar                              | 1        | 2.5%    |
| ASRockRack                           | 1        | 2.5%    |
| ASRock                               | 1        | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Unknown                                           | 3        | 7.5%    |
| MSI MS-7C95                                       | 2        | 5%      |
| HP EliteDesk 800 G1 SFF                           | 2        | 5%      |
| Dell OptiPlex 9020                                | 2        | 5%      |
| Shenzhen Meigao Electronic Equipment Venus series | 1        | 2.5%    |
| MSI MS-7D75                                       | 1        | 2.5%    |
| MSI MS-7C94                                       | 1        | 2.5%    |
| MSI MS-7C52                                       | 1        | 2.5%    |
| MSI MS-7C08                                       | 1        | 2.5%    |
| MSI MS-7B86                                       | 1        | 2.5%    |
| MSI MS-7A40                                       | 1        | 2.5%    |
| iKOOLCORE TECHNOLOGY R2                           | 1        | 2.5%    |
| HP EliteDesk 705 G4 SFF                           | 1        | 2.5%    |
| Gigabyte X99-UD4P-CF                              | 1        | 2.5%    |
| Gigabyte X670E AORUS XTREME                       | 1        | 2.5%    |
| Gigabyte M68MT-S2                                 | 1        | 2.5%    |
| Gigabyte B650M D3HP                               | 1        | 2.5%    |
| Gigabyte B450M S2H V2                             | 1        | 2.5%    |
| Gigabyte B450M DS3H WIFI                          | 1        | 2.5%    |
| Gigabyte B450 I AORUS PRO WIFI                    | 1        | 2.5%    |
| Dell Vostro 3681                                  | 1        | 2.5%    |
| Dell OptiPlex XE2                                 | 1        | 2.5%    |
| Dell OptiPlex XE                                  | 1        | 2.5%    |
| Dell OptiPlex 3000                                | 1        | 2.5%    |
| Biostar H610MHP 2.0                               | 1        | 2.5%    |
| ASUS Z10PA-U8 Series                              | 1        | 2.5%    |
| ASUS TUF Gaming B550-PLUS                         | 1        | 2.5%    |
| ASUS TUF Gaming B450M-PRO S                       | 1        | 2.5%    |
| ASUS STRIX B250G GAMING                           | 1        | 2.5%    |
| ASUS ROG CROSSHAIR VIII HERO                      | 1        | 2.5%    |
| ASUS P7H55-M LX                                   | 1        | 2.5%    |
| ASUS P5Q-E                                        | 1        | 2.5%    |
| ASUS CROSSHAIR V FORMULA-Z                        | 1        | 2.5%    |
| ASRockRack EPYC3101D4I-2T                         | 1        | 2.5%    |
| ASRock X99 Extreme4                               | 1        | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Dell OptiPlex                              | 5        | 12.5%   |
| HP EliteDesk                               | 3        | 7.5%    |
| Unknown                                    | 3        | 7.5%    |
| MSI MS-7C95                                | 2        | 5%      |
| Gigabyte B450M                             | 2        | 5%      |
| ASUS TUF                                   | 2        | 5%      |
| Shenzhen Meigao Electronic Equipment Venus | 1        | 2.5%    |
| MSI MS-7D75                                | 1        | 2.5%    |
| MSI MS-7C94                                | 1        | 2.5%    |
| MSI MS-7C52                                | 1        | 2.5%    |
| MSI MS-7C08                                | 1        | 2.5%    |
| MSI MS-7B86                                | 1        | 2.5%    |
| MSI MS-7A40                                | 1        | 2.5%    |
| iKOOLCORE TECHNOLOGY R2                    | 1        | 2.5%    |
| Gigabyte X99-UD4P-CF                       | 1        | 2.5%    |
| Gigabyte X670E                             | 1        | 2.5%    |
| Gigabyte M68MT-S2                          | 1        | 2.5%    |
| Gigabyte B650M                             | 1        | 2.5%    |
| Gigabyte B450                              | 1        | 2.5%    |
| Dell Vostro                                | 1        | 2.5%    |
| Biostar H610MHP                            | 1        | 2.5%    |
| ASUS Z10PA-U8                              | 1        | 2.5%    |
| ASUS STRIX                                 | 1        | 2.5%    |
| ASUS ROG                                   | 1        | 2.5%    |
| ASUS P7H55-M                               | 1        | 2.5%    |
| ASUS P5Q-E                                 | 1        | 2.5%    |
| ASUS CROSSHAIR                             | 1        | 2.5%    |
| ASRockRack EPYC3101D4I-2T                  | 1        | 2.5%    |
| ASRock X99                                 | 1        | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2024 | 6        | 15%     |
| 2023 | 6        | 15%     |
| 2022 | 5        | 12.5%   |
| 2020 | 4        | 10%     |
| 2021 | 3        | 7.5%    |
| 2019 | 3        | 7.5%    |
| 2014 | 3        | 7.5%    |
| 2018 | 2        | 5%      |
| 2015 | 2        | 5%      |
| 2017 | 1        | 2.5%    |
| 2013 | 1        | 2.5%    |
| 2012 | 1        | 2.5%    |
| 2010 | 1        | 2.5%    |
| 2008 | 1        | 2.5%    |
| 2006 | 1        | 2.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 40       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 40       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 32.01-64.0      | 13       | 31.71%  |
| 16.01-24.0      | 13       | 31.71%  |
| 64.01-256.0     | 6        | 14.63%  |
| 8.01-16.0       | 5        | 12.2%   |
| 4.01-8.0        | 3        | 7.32%   |
| More than 256.0 | 1        | 2.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 13       | 31.71%  |
| 0.51-1.0   | 13       | 31.71%  |
| 0.01-0.5   | 6        | 14.63%  |
| 4.01-8.0   | 5        | 12.2%   |
| 2.01-3.0   | 2        | 4.88%   |
| 3.01-4.0   | 1        | 2.44%   |
| 16.01-24.0 | 1        | 2.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 14       | 34.15%  |
| 2      | 9        | 21.95%  |
| 0      | 8        | 19.51%  |
| 5      | 3        | 7.32%   |
| 4      | 3        | 7.32%   |
| 3      | 2        | 4.88%   |
| 10     | 1        | 2.44%   |
| 9      | 1        | 2.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 65%     |
| Yes       | 14       | 35%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 39       | 97.5%   |
| No        | 1        | 2.5%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 52.5%   |
| Yes       | 19       | 47.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 65%     |
| Yes       | 14       | 35%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| USA                | 16       | 40%     |
| Russia             | 4        | 10%     |
| Germany            | 4        | 10%     |
| UK                 | 2        | 5%      |
| Poland             | 2        | 5%      |
| France             | 2        | 5%      |
| Brazil             | 2        | 5%      |
| Venezuela          | 1        | 2.5%    |
| Ukraine            | 1        | 2.5%    |
| Thailand           | 1        | 2.5%    |
| Romania            | 1        | 2.5%    |
| Malaysia           | 1        | 2.5%    |
| Dominican Republic | 1        | 2.5%    |
| Colombia           | 1        | 2.5%    |
| Canada             | 1        | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Wroclaw               | 2        | 5%      |
| Taylor                | 2        | 5%      |
| Redmond               | 2        | 5%      |
| New York              | 2        | 5%      |
| Wellingborough        | 1        | 2.5%    |
| Vladivostok           | 1        | 2.5%    |
| Valencia              | 1        | 2.5%    |
| Ulm                   | 1        | 2.5%    |
| Ternopil              | 1        | 2.5%    |
| St Petersburg         | 1        | 2.5%    |
| Somerset              | 1        | 2.5%    |
| Santa Barbara d'Oeste | 1        | 2.5%    |
| San Angelo            | 1        | 2.5%    |
| Revel                 | 1        | 2.5%    |
| Puerto Plata          | 1        | 2.5%    |
| Paris                 | 1        | 2.5%    |
| Newcastle             | 1        | 2.5%    |
| Moscow                | 1        | 2.5%    |
| Medellín             | 1        | 2.5%    |
| Mankato               | 1        | 2.5%    |
| Macaiba               | 1        | 2.5%    |
| Lisle                 | 1        | 2.5%    |
| Lincolnton            | 1        | 2.5%    |
| Kuala Lumpur          | 1        | 2.5%    |
| Istra                 | 1        | 2.5%    |
| Iasi                  | 1        | 2.5%    |
| Harrow                | 1        | 2.5%    |
| Grand Rapids          | 1        | 2.5%    |
| Gilbert               | 1        | 2.5%    |
| Everett               | 1        | 2.5%    |
| Dornum                | 1        | 2.5%    |
| Carlsbad              | 1        | 2.5%    |
| Berlin                | 1        | 2.5%    |
| Bangkok               | 1        | 2.5%    |
| Bad Aibling           | 1        | 2.5%    |
| Arlington             | 1        | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 12       | 26     | 25%     |
| Seagate             | 9        | 17     | 18.75%  |
| Samsung Electronics | 8        | 18     | 16.67%  |
| Kingston            | 4        | 7      | 8.33%   |
| Hitachi             | 3        | 4      | 6.25%   |
| SPCC                | 2        | 6      | 4.17%   |
| SanDisk             | 2        | 2      | 4.17%   |
| Crucial             | 2        | 2      | 4.17%   |
| Toshiba             | 1        | 1      | 2.08%   |
| TEXTORM             | 1        | 1      | 2.08%   |
| T-FORCE             | 1        | 1      | 2.08%   |
| PNY                 | 1        | 2      | 2.08%   |
| China               | 1        | 1      | 2.08%   |
| Apacer              | 1        | 1      | 2.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB  | 2        | 3.7%    |
| Samsung SSD 870 EVO 500GB       | 2        | 3.7%    |
| Samsung SSD 860 EVO 1TB         | 2        | 3.7%    |
| Kingston SA400S37120G 120GB     | 2        | 3.7%    |
| WDC WDS250G2B0A 250GB           | 1        | 1.85%   |
| WDC WD5000AAKX-60U6AA0 500GB    | 1        | 1.85%   |
| WDC WD40EZRZ-22GXCB0 4TB        | 1        | 1.85%   |
| WDC WD40EZAZ-00SF3B0 4TB        | 1        | 1.85%   |
| WDC WD40EFRX-68N32N0 4TB        | 1        | 1.85%   |
| WDC WD3200BEKX-00B7WT0 320GB    | 1        | 1.85%   |
| WDC WD2500AAKX-75U6AA0 250GB    | 1        | 1.85%   |
| WDC WD2500AAJS-07B4A0 250GB     | 1        | 1.85%   |
| WDC WD20EZRZ-00Z5HB0 2TB        | 1        | 1.85%   |
| WDC WD20EZAZ-00GGJB0 2TB        | 1        | 1.85%   |
| WDC WD1600AAJS-00YZCA0 160GB    | 1        | 1.85%   |
| WDC WD10EZEX-22MFCA0 1TB        | 1        | 1.85%   |
| WDC WD1003FBYX-01Y7B1 1TB       | 1        | 1.85%   |
| Toshiba MQ01ABF050 500GB        | 1        | 1.85%   |
| TEXTORM BM5 480GB               | 1        | 1.85%   |
| T-FORCE SSD 256GB               | 1        | 1.85%   |
| SPCC Solid State Disk 1TB       | 1        | 1.85%   |
| SPCC Solid State Disk 128GB     | 1        | 1.85%   |
| SPCC M.2 PCIe SSD 1TB           | 1        | 1.85%   |
| Seagate ST8000DM004-2U9188 8TB  | 1        | 1.85%   |
| Seagate ST8000DM004-2CX188 8TB  | 1        | 1.85%   |
| Seagate ST500LT012-9WS142 500GB | 1        | 1.85%   |
| Seagate ST4000DM004-2CV104 4TB  | 1        | 1.85%   |
| Seagate ST4000DM000-1F2168 4TB  | 1        | 1.85%   |
| Seagate ST2000DM008-2UB102 2TB  | 1        | 1.85%   |
| Seagate ST1000DM010-2EP102 1TB  | 1        | 1.85%   |
| Seagate ST10000NM0046 10TB      | 1        | 1.85%   |
| SanDisk SSD U110 64GB           | 1        | 1.85%   |
| SanDisk SD8SN8U-128G-1006 128GB | 1        | 1.85%   |
| Samsung SSD 870 QVO 2TB         | 1        | 1.85%   |
| Samsung SSD 870 EVO 1TB         | 1        | 1.85%   |
| Samsung SSD 860 QVO 1TB         | 1        | 1.85%   |
| Samsung SSD 860 EVO 500GB       | 1        | 1.85%   |
| Samsung SSD 850 EVO 1TB         | 1        | 1.85%   |
| Samsung HD103SI 1TB             | 1        | 1.85%   |
| PNY 250GB SATA SSD              | 1        | 1.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 24     | 44%     |
| Seagate             | 9        | 17     | 36%     |
| Hitachi             | 3        | 4      | 12%     |
| Toshiba             | 1        | 1      | 4%      |
| Samsung Electronics | 1        | 2      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 16     | 33.33%  |
| Kingston            | 4        | 7      | 16.67%  |
| SPCC                | 2        | 5      | 8.33%   |
| SanDisk             | 2        | 2      | 8.33%   |
| Crucial             | 2        | 2      | 8.33%   |
| WDC                 | 1        | 2      | 4.17%   |
| TEXTORM             | 1        | 1      | 4.17%   |
| T-FORCE             | 1        | 1      | 4.17%   |
| PNY                 | 1        | 2      | 4.17%   |
| China               | 1        | 1      | 4.17%   |
| Apacer              | 1        | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 23       | 40     | 51.11%  |
| HDD  | 21       | 48     | 46.67%  |
| NVMe | 1        | 1      | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 32       | 88     | 96.97%  |
| NVMe | 1        | 1      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 22       | 35     | 50%     |
| 0.51-1.0   | 8        | 15     | 18.18%  |
| 1.01-2.0   | 7        | 26     | 15.91%  |
| 3.01-4.0   | 4        | 8      | 9.09%   |
| 4.01-10.0  | 3        | 4      | 6.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 12       | 29.27%  |
| 501-1000       | 12       | 29.27%  |
| 251-500        | 10       | 24.39%  |
| More than 3000 | 2        | 4.88%   |
| 1001-2000      | 2        | 4.88%   |
| 2001-3000      | 1        | 2.44%   |
| 1-20           | 1        | 2.44%   |
| Unknown        | 1        | 2.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 35       | 85.37%  |
| More than 3000 | 1        | 2.44%   |
| 251-500        | 1        | 2.44%   |
| 21-50          | 1        | 2.44%   |
| 101-250        | 1        | 2.44%   |
| 51-100         | 1        | 2.44%   |
| Unknown        | 1        | 2.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD2500AAJS-07B4A0 250GB     | 1        | 1      | 12.5%   |
| TEXTORM BM5 480GB               | 1        | 1      | 12.5%   |
| Seagate ST500LT012-9WS142 500GB | 1        | 1      | 12.5%   |
| Samsung Electronics HD103SI 1TB | 1        | 2      | 12.5%   |
| Kingston SA400S37480G 480GB     | 1        | 1      | 12.5%   |
| Hitachi HTS545016B9A300 160GB   | 1        | 1      | 12.5%   |
| Hitachi HTS542512K9SA00 120GB   | 1        | 1      | 12.5%   |
| Crucial FCCT256M550SSD1 256GB   | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 14.29%  |
| TEXTORM             | 1        | 1      | 14.29%  |
| Seagate             | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 2      | 14.29%  |
| Kingston            | 1        | 1      | 14.29%  |
| Hitachi             | 1        | 2      | 14.29%  |
| Crucial             | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 25%     |
| Seagate             | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 2      | 25%     |
| Hitachi             | 1        | 2      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 6      | 57.14%  |
| SSD  | 3        | 3      | 42.86%  |

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


| Status  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Works   | 30       | 80     | 81.08%  |
| Malfunc | 7        | 9      | 18.92%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 21       | 33.87%  |
| AMD                         | 17       | 27.42%  |
| SanDisk                     | 4        | 6.45%   |
| Samsung Electronics         | 4        | 6.45%   |
| Micron/Crucial Technology   | 3        | 4.84%   |
| ASMedia Technology          | 3        | 4.84%   |
| SK hynix                    | 2        | 3.23%   |
| Phison Electronics          | 2        | 3.23%   |
| Marvell Technology Group    | 2        | 3.23%   |
| Realtek Semiconductor       | 1        | 1.61%   |
| Nvidia                      | 1        | 1.61%   |
| Lite-On Technology          | 1        | 1.61%   |
| Kingston Technology Company | 1        | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11       | 14.29%  |
| AMD 400 Series Chipset SATA Controller                                         | 6        | 7.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 5.19%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 5.19%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3        | 3.9%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3        | 3.9%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3        | 3.9%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3        | 3.9%    |
| AMD 600 Series Chipset SATA Controller                                         | 3        | 3.9%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2        | 2.6%    |
| Intel SATA Controller [RAID mode]                                              | 2        | 2.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 2.6%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 2        | 2.6%    |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 1        | 1.3%    |
| SK hynix BC511 NVMe SSD                                                        | 1        | 1.3%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 1.3%    |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 1        | 1.3%    |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 1        | 1.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 1.3%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 1        | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 1.3%    |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 1        | 1.3%    |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 1        | 1.3%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 1.3%    |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.3%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 1.3%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 1.3%    |
| Lite-On CX2-8B256, CX2-8B512 NVMe SSD                                          | 1        | 1.3%    |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 1        | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 1        | 1.3%    |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 1.3%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 1        | 1.3%    |
| Intel Alder Lake-N SATA AHCI Controller                                        | 1        | 1.3%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 1.3%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1        | 1.3%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 1.3%    |
| ASMedia ASM1064 Serial ATA Controller                                          | 1        | 1.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 35       | 61.4%   |
| NVMe | 17       | 29.82%  |
| RAID | 3        | 5.26%   |
| IDE  | 2        | 3.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 21       | 52.5%   |
| AMD    | 19       | 47.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i5-4690 CPU @ 3.50GHz                | 2        | 5%      |
| Intel Xeon CPU E5-2695 v4 @ 2.10GHz             | 1        | 2.5%    |
| Intel Xeon CPU E5-2683 v3 @ 2.00GHz             | 1        | 2.5%    |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz             | 1        | 2.5%    |
| Intel Pentium CPU G860 @ 3.00GHz                | 1        | 2.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 2.5%    |
| Intel Core i7-4770S CPU @ 3.10GHz               | 1        | 2.5%    |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1        | 2.5%    |
| Intel Core i5-10400 CPU @ 2.90GHz               | 1        | 2.5%    |
| Intel Core i3-N300                              | 1        | 2.5%    |
| Intel Core i3-9100F CPU @ 3.60GHz               | 1        | 2.5%    |
| Intel Core i3-4160 CPU @ 3.60GHz                | 1        | 2.5%    |
| Intel Core i3 CPU 530 @ 2.93GHz                 | 1        | 2.5%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 2.5%    |
| Intel Core 2 Duo                                | 1        | 2.5%    |
| Intel Celeron N5105 @ 2.00GHz                   | 1        | 2.5%    |
| Intel 12th Gen Core i5-12600H                   | 1        | 2.5%    |
| Intel 12th Gen Core i5-12500                    | 1        | 2.5%    |
| Intel 12th Gen Core i5-12400                    | 1        | 2.5%    |
| Intel 12th Gen Core i3-12100F                   | 1        | 2.5%    |
| AMD Ryzen 9 9900X 12-Core Processor             | 1        | 2.5%    |
| AMD Ryzen 9 7900 12-Core Processor              | 1        | 2.5%    |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 2.5%    |
| AMD Ryzen 7 7700X 8-Core Processor              | 1        | 2.5%    |
| AMD Ryzen 7 5700X 8-Core Processor              | 1        | 2.5%    |
| AMD Ryzen 7 5700G with Radeon Graphics          | 1        | 2.5%    |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 2.5%    |
| AMD Ryzen 7 1800X Eight-Core Processor          | 1        | 2.5%    |
| AMD Ryzen 5 PRO 2400G with Radeon Vega Graphics | 1        | 2.5%    |
| AMD Ryzen 5 5600X 6-Core Processor              | 1        | 2.5%    |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 2.5%    |
| AMD Ryzen 5 5600 6-Core Processor               | 1        | 2.5%    |
| AMD Ryzen 5 5500                                | 1        | 2.5%    |
| AMD Ryzen 5 3500 6-Core Processor               | 1        | 2.5%    |
| AMD Ryzen 5 2600X Six-Core Processor            | 1        | 2.5%    |
| AMD Ryzen 5 1600 Six-Core Processor             | 1        | 2.5%    |
| AMD FX-8150 Eight-Core Processor                | 1        | 2.5%    |
| AMD FX-4100 Quad-Core Processor                 | 1        | 2.5%    |
| AMD EPYC 3101 4-Core Processor                  | 1        | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| AMD Ryzen 5       | 7        | 17.5%   |
| AMD Ryzen 7       | 5        | 12.5%   |
| Other             | 4        | 10%     |
| Intel Core i5     | 4        | 10%     |
| Intel Core i3     | 4        | 10%     |
| Intel Xeon        | 3        | 7.5%    |
| AMD Ryzen 9       | 3        | 7.5%    |
| Intel Core i7     | 2        | 5%      |
| AMD FX            | 2        | 5%      |
| Intel Pentium     | 1        | 2.5%    |
| Intel Core 2 Quad | 1        | 2.5%    |
| Intel Core 2 Duo  | 1        | 2.5%    |
| Intel Celeron     | 1        | 2.5%    |
| AMD Ryzen 5 PRO   | 1        | 2.5%    |
| AMD EPYC          | 1        | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 10       | 25%     |
| 12     | 6        | 15%     |
| 6      | 6        | 15%     |
| 8      | 5        | 12.5%   |
| 2      | 5        | 12.5%   |
| 16     | 4        | 10%     |
| 14     | 2        | 5%      |
| 24     | 1        | 2.5%    |
| 18     | 1        | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 40       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 23       | 57.5%   |
| 2      | 17       | 42.5%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 9        | 22.5%   |
| Zen 3       | 6        | 15%     |
| Haswell     | 6        | 15%     |
| Zen 2       | 3        | 7.5%    |
| Zen         | 3        | 7.5%    |
| Zen+        | 2        | 5%      |
| KabyLake    | 2        | 5%      |
| Bulldozer   | 2        | 5%      |
| Broadwell   | 2        | 5%      |
| Westmere    | 1        | 2.5%    |
| SandyBridge | 1        | 2.5%    |
| Penryn      | 1        | 2.5%    |
| Core        | 1        | 2.5%    |
| CometLake   | 1        | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| AMD               | 18       | 39.13%  |
| Intel             | 14       | 30.43%  |
| Nvidia            | 12       | 26.09%  |
| ASPEED Technology | 2        | 4.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 6.25%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 6.25%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 4.17%   |
| ASPEED Technology ASPEED Graphics Family                                    | 2        | 4.17%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 2        | 4.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 4.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 4.17%   |
| Nvidia TU117GL [T400 4GB / T400E]                                           | 1        | 2.08%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 2.08%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 2.08%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 2.08%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.08%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.08%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 2.08%   |
| Nvidia GF108 [GeForce GT 730]                                               | 1        | 2.08%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 1        | 2.08%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 1        | 2.08%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 1        | 2.08%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 2.08%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.08%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 1        | 2.08%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 1        | 2.08%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 1        | 2.08%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 1        | 2.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 2.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.08%   |
| AMD Raphael                                                                 | 1        | 2.08%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 1        | 2.08%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 1        | 2.08%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1        | 2.08%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 2.08%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 2.08%   |
| AMD Granite Ridge [Radeon Graphics]                                         | 1        | 2.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 2.08%   |
| AMD Cedar GL [FirePro 2270]                                                 | 1        | 2.08%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x AMD         | 14       | 33.33%  |
| 1 x Intel       | 11       | 26.19%  |
| 1 x Nvidia      | 9        | 21.43%  |
| 2 x AMD         | 2        | 4.76%   |
| 2 x Intel       | 1        | 2.38%   |
| Nvidia + ASPEED | 1        | 2.38%   |
| Intel + Nvidia  | 1        | 2.38%   |
| Intel + AMD     | 1        | 2.38%   |
| 1 x ASPEED      | 1        | 2.38%   |
| AMD + Nvidia    | 1        | 2.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 34       | 82.93%  |
| Proprietary | 6        | 14.63%  |
| Unknown     | 1        | 2.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 58.54%  |
| 3.01-4.0   | 6        | 14.63%  |
| 7.01-8.0   | 5        | 12.2%   |
| 8.01-16.0  | 2        | 4.88%   |
| 5.01-6.0   | 1        | 2.44%   |
| 16.01-24.0 | 1        | 2.44%   |
| 0.51-1.0   | 1        | 2.44%   |
| 0.01-0.5   | 1        | 2.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 14.29%  |
| ViewSonic           | 3        | 10.71%  |
| Samsung Electronics | 3        | 10.71%  |
| Philips             | 2        | 7.14%   |
| Goldstar            | 2        | 7.14%   |
| Dell                | 2        | 7.14%   |
| VKK                 | 1        | 3.57%   |
| Vita                | 1        | 3.57%   |
| Toshiba             | 1        | 3.57%   |
| Sceptre Tech        | 1        | 3.57%   |
| RGT                 | 1        | 3.57%   |
| MSI                 | 1        | 3.57%   |
| Lenovo              | 1        | 3.57%   |
| Iiyama              | 1        | 3.57%   |
| HKC                 | 1        | 3.57%   |
| Gigabyte Technology | 1        | 3.57%   |
| BenQ                | 1        | 3.57%   |
| Acer                | 1        | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| VKK VK1160C VKK1160 1920x1080 260x150mm 11.8-inch                      | 1        | 3.23%   |
| Vita V195EW-W VIT1950 1600x900 430x240mm 19.4-inch                     | 1        | 3.23%   |
| ViewSonic VA2342 SERIES VSCFA2B 1920x1080 510x290mm 23.1-inch          | 1        | 3.23%   |
| ViewSonic VA1916w-6 VSCF91F 1440x900 410x260mm 19.1-inch               | 1        | 3.23%   |
| ViewSonic LCD Monitor VA2246 SERIES 1920x1080                          | 1        | 3.23%   |
| Toshiba TV TSB010B 1920x1080 420x240mm 19.0-inch                       | 1        | 3.23%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 530x290mm 23.8-inch         | 1        | 3.23%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 1        | 3.23%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1110x620mm 50.1-inch | 1        | 3.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 1        | 3.23%   |
| RGT LCD Monitor RGT1252 1920x1080 1020x570mm 46.0-inch                 | 1        | 3.23%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 530x300mm 24.0-inch                | 1        | 3.23%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch                | 1        | 3.23%   |
| MSI G2422C MSI4BB3 1920x1080 520x300mm 23.6-inch                       | 1        | 3.23%   |
| Lenovo M14 LEN61DD 1920x1080 310x180mm 14.1-inch                       | 1        | 3.23%   |
| Iiyama PL2740HS IVM6663 1920x1080 600x340mm 27.2-inch                  | 1        | 3.23%   |
| HKC 24N1A HKC2421 1920x1080 530x290mm 23.8-inch                        | 1        | 3.23%   |
| Hewlett-Packard ZR22w HWP2868 1920x1080 480x270mm 21.7-inch            | 1        | 3.23%   |
| Hewlett-Packard Z23n HWP3283 1920x1080 510x290mm 23.1-inch             | 1        | 3.23%   |
| Hewlett-Packard Z23i HWP308F 1920x1080 510x290mm 23.1-inch             | 1        | 3.23%   |
| Hewlett-Packard VH240a HPN349A 1920x1080 530x300mm 24.0-inch           | 1        | 3.23%   |
| Hewlett-Packard VH240a HPN3499 1920x1080 530x300mm 24.0-inch           | 1        | 3.23%   |
| Hewlett-Packard E272q HWP326A 2560x1440 600x340mm 27.2-inch            | 1        | 3.23%   |
| Goldstar LG ULTRAFINE GSM5BC1 3840x2160 700x400mm 31.7-inch            | 1        | 3.23%   |
| Goldstar 24MB35 GSM5A4A 1920x1080 600x340mm 27.2-inch                  | 1        | 3.23%   |
| Gigabyte Technology M32UC GBT3209 3840x2160 700x390mm 31.5-inch        | 1        | 3.23%   |
| Dell LCD Monitor E2222H 3840x1080                                      | 1        | 3.23%   |
| Dell LCD Monitor E2222H                                                | 1        | 3.23%   |
| Dell 1707FP DEL4012 1280x1024 340x270mm 17.1-inch                      | 1        | 3.23%   |
| BenQ LCD BNQ8024 2560x1440 600x340mm 27.2-inch                         | 1        | 3.23%   |
| Acer EK221Q H ACR0B5D 1920x1080 480x260mm 21.5-inch                    | 1        | 3.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 15       | 60%     |
| 3840x2160 (4K)   | 3        | 12%     |
| 2560x1440 (QHD)  | 2        | 8%      |
| 3840x1080        | 1        | 4%      |
| 1600x900 (HD+)   | 1        | 4%      |
| 1440x900 (WXGA+) | 1        | 4%      |
| 1280x1024 (SXGA) | 1        | 4%      |
| Unknown          | 1        | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 5        | 17.86%  |
| 23      | 5        | 17.86%  |
| 24      | 3        | 10.71%  |
| 19      | 3        | 10.71%  |
| Unknown | 3        | 10.71%  |
| 31      | 2        | 7.14%   |
| 21      | 2        | 7.14%   |
| 50      | 1        | 3.57%   |
| 46      | 1        | 3.57%   |
| 17      | 1        | 3.57%   |
| 14      | 1        | 3.57%   |
| 11      | 1        | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 12       | 44.44%  |
| 401-500     | 5        | 18.52%  |
| Unknown     | 3        | 11.11%  |
| 601-700     | 2        | 7.41%   |
| 301-350     | 2        | 7.41%   |
| 1001-1500   | 2        | 7.41%   |
| 201-300     | 1        | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 20       | 83.33%  |
| Unknown | 2        | 8.33%   |
| 5/4     | 1        | 4.17%   |
| 16/10   | 1        | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 29.63%  |
| 301-350        | 5        | 18.52%  |
| 151-200        | 4        | 14.81%  |
| Unknown        | 3        | 11.11%  |
| 351-500        | 2        | 7.41%   |
| More than 1000 | 1        | 3.7%    |
| 81-90          | 1        | 3.7%    |
| 51-60          | 1        | 3.7%    |
| 141-150        | 1        | 3.7%    |
| 501-1000       | 1        | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 51.85%  |
| 101-120 | 5        | 18.52%  |
| 121-160 | 3        | 11.11%  |
| Unknown | 3        | 11.11%  |
| 1-50    | 1        | 3.7%    |
| 161-240 | 1        | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 48.78%  |
| 0     | 16       | 39.02%  |
| 2     | 3        | 7.32%   |
| 3     | 2        | 4.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 26       | 44.07%  |
| Realtek Semiconductor    | 23       | 38.98%  |
| MediaTek                 | 3        | 5.08%   |
| Samsung Electronics      | 1        | 1.69%   |
| Micro Star International | 1        | 1.69%   |
| Marvell Technology Group | 1        | 1.69%   |
| Emulex                   | 1        | 1.69%   |
| Broadcom                 | 1        | 1.69%   |
| Aquantia                 | 1        | 1.69%   |
| American Megatrends      | 1        | 1.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 13       | 18.31%  |
| Realtek RTL8125 2.5GbE Controller                                                             | 6        | 8.45%   |
| Intel Ethernet Connection I217-LM                                                             | 5        | 7.04%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 3        | 4.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 2        | 2.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 2        | 2.82%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 2        | 2.82%   |
| Intel I211 Gigabit Network Connection                                                         | 2        | 2.82%   |
| Intel Ethernet Controller I226-V                                                              | 2        | 2.82%   |
| Intel Ethernet Connection (2) I219-V                                                          | 2        | 2.82%   |
| Intel Ethernet Connection (2) I218-V                                                          | 2        | 2.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 2.82%   |
| Intel 82580 Gigabit Network Connection                                                        | 2        | 2.82%   |
| Intel 82574L Gigabit Network Connection                                                       | 2        | 2.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                                   | 1        | 1.41%   |
| Realtek USB 2.5GbE Controller                                                                 | 1        | 1.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.41%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 1.41%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                                       | 1        | 1.41%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 1.41%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]                    | 1        | 1.41%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 1.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                                       | 1        | 1.41%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                             | 1        | 1.41%   |
| Intel Wireless 8265 / 8275                                                                    | 1        | 1.41%   |
| Intel Wireless 8260                                                                           | 1        | 1.41%   |
| Intel I350 Gigabit Network Connection                                                         | 1        | 1.41%   |
| Intel I210 Gigabit Network Connection                                                         | 1        | 1.41%   |
| Intel Ethernet Controller X550                                                                | 1        | 1.41%   |
| Intel Ethernet Connection (17) I219-V                                                         | 1        | 1.41%   |
| Intel 82583V Gigabit Network Connection                                                       | 1        | 1.41%   |
| Intel 82579V Gigabit Network Connection                                                       | 1        | 1.41%   |
| Emulex OneConnect 10Gb NIC (be3)                                                              | 1        | 1.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                              | 1        | 1.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                               | 1        | 1.41%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig]             | 1        | 1.41%   |
| American Megatrends Virtual Ethernet                                                          | 1        | 1.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 9        | 47.37%  |
| Realtek Semiconductor    | 6        | 31.58%  |
| MediaTek                 | 3        | 15.79%  |
| Micro Star International | 1        | 5.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                     | 3        | 15%     |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 2        | 10%     |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                 | 2        | 10%     |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 2        | 10%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2        | 10%     |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 1        | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 5%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 1        | 5%      |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                                       | 1        | 5%      |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1        | 5%      |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070]                    | 1        | 5%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 1        | 5%      |
| Intel Wireless 8265 / 8275                                                                    | 1        | 5%      |
| Intel Wireless 8260                                                                           | 1        | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 20       | 44.44%  |
| Intel                    | 19       | 42.22%  |
| Samsung Electronics      | 1        | 2.22%   |
| Marvell Technology Group | 1        | 2.22%   |
| Emulex                   | 1        | 2.22%   |
| Broadcom                 | 1        | 2.22%   |
| Aquantia                 | 1        | 2.22%   |
| American Megatrends      | 1        | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller            | 13       | 25.49%  |
| Realtek RTL8125 2.5GbE Controller                                                 | 6        | 11.76%  |
| Intel Ethernet Connection I217-LM                                                 | 5        | 9.8%    |
| Intel I211 Gigabit Network Connection                                             | 2        | 3.92%   |
| Intel Ethernet Controller I226-V                                                  | 2        | 3.92%   |
| Intel Ethernet Connection (2) I219-V                                              | 2        | 3.92%   |
| Intel Ethernet Connection (2) I218-V                                              | 2        | 3.92%   |
| Intel 82580 Gigabit Network Connection                                            | 2        | 3.92%   |
| Intel 82574L Gigabit Network Connection                                           | 2        | 3.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                       | 1        | 1.96%   |
| Realtek USB 2.5GbE Controller                                                     | 1        | 1.96%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                           | 1        | 1.96%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                                 | 1        | 1.96%   |
| Intel I350 Gigabit Network Connection                                             | 1        | 1.96%   |
| Intel I210 Gigabit Network Connection                                             | 1        | 1.96%   |
| Intel Ethernet Controller X550                                                    | 1        | 1.96%   |
| Intel Ethernet Connection (17) I219-V                                             | 1        | 1.96%   |
| Intel 82583V Gigabit Network Connection                                           | 1        | 1.96%   |
| Intel 82579V Gigabit Network Connection                                           | 1        | 1.96%   |
| Emulex OneConnect 10Gb NIC (be3)                                                  | 1        | 1.96%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                  | 1        | 1.96%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                   | 1        | 1.96%   |
| Aquantia AQC113C NBase-T/IEEE 802.3an Ethernet Controller [Marvell Scalable mGig] | 1        | 1.96%   |
| American Megatrends Virtual Ethernet                                              | 1        | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 39       | 67.24%  |
| WiFi     | 19       | 32.76%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 32       | 91.43%  |
| WiFi     | 3        | 8.57%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 18       | 45%     |
| 1     | 15       | 37.5%   |
| 3     | 4        | 10%     |
| 6     | 1        | 2.5%    |
| 5     | 1        | 2.5%    |
| 4     | 1        | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 78.05%  |
| Yes  | 9        | 21.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 7        | 50%     |
| Realtek Semiconductor    | 3        | 21.43%  |
| MediaTek                 | 3        | 21.43%  |
| Micro Star International | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Realtek Bluetooth Adapter                             | 3        | 21.43%  |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 2        | 14.29%  |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 14.29%  |
| Intel AX210 Bluetooth                                 | 2        | 14.29%  |
| Micro Star International Bluetooth 2.1+EDR USB Device | 1        | 7.14%   |
| MediaTek Wireless_Device                              | 1        | 7.14%   |
| MediaTek RZ616 Bluetooth Adapter                      | 1        | 7.14%   |
| MediaTek RZ608 Bluetooth Adapter                      | 1        | 7.14%   |
| Intel Bluetooth wireless interface                    | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| AMD                         | 22       | 35.48%  |
| Intel                       | 19       | 30.65%  |
| Nvidia                      | 12       | 19.35%  |
| JMTek                       | 2        | 3.23%   |
| Realtek Semiconductor       | 1        | 1.61%   |
| Razer USA                   | 1        | 1.61%   |
| Micro Star International    | 1        | 1.61%   |
| Harman Kardon               | 1        | 1.61%   |
| FiiO Electronics Technology | 1        | 1.61%   |
| C-Media Electronics         | 1        | 1.61%   |
| Blue Microphones            | 1        | 1.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Ryzen HD Audio Controller                                              | 7        | 8.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6        | 7.32%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6        | 7.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 6.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4        | 4.88%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3        | 3.66%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 3        | 3.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.66%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 2.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.44%   |
| JMTek USB PnP Audio Device                                                 | 2        | 2.44%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 2.44%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2        | 2.44%   |
| AMD Radeon High Definition Audio Controller                                | 2        | 2.44%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.44%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.44%   |
| Realtek Semiconductor Maono AU-PM401 Maono AU-PM401 Microphone Headphone   | 1        | 1.22%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1        | 1.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1        | 1.22%   |
| Nvidia TU106 High Definition Audio Controller                              | 1        | 1.22%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.22%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.22%   |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 1.22%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 1.22%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.22%   |
| Nvidia AD102 High Definition Audio Controller                              | 1        | 1.22%   |
| Micro Star International Realtek Device                                    | 1        | 1.22%   |
| Intel Jasper Lake HD Audio                                                 | 1        | 1.22%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 1.22%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 1.22%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 1        | 1.22%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1        | 1.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 1.22%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1        | 1.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.22%   |
| Harman Kardon AKG Ara USB Microphone                                       | 1        | 1.22%   |
| FiiO Electronics Technology USB DAC                                        | 1        | 1.22%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 1.22%   |
| C-Media Electronics CM106 Like Sound Device                                | 1        | 1.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 13.33%  |
| Kingston            | 6        | 13.33%  |
| Corsair             | 6        | 13.33%  |
| SK hynix            | 5        | 11.11%  |
| G.Skill             | 5        | 11.11%  |
| Unknown             | 4        | 8.89%   |
| Patriot             | 3        | 6.67%   |
| Micron Technology   | 3        | 6.67%   |
| Crucial             | 3        | 6.67%   |
| Team                | 2        | 4.44%   |
| Unknown (0x0B45)    | 1        | 2.22%   |
| Unknown             | 1        | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2Z3200C16 8GB DIMM DDR4 3200MT/s            | 2        | 4%      |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1        | 2%      |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1        | 2%      |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1        | 2%      |
| Unknown RAM Module 2GB DIMM DDR 800MT/s                          | 1        | 2%      |
| Unknown (0x0B45) RAM WPBH32D416SWA-16G 16GB SODIMM DDR4 3200MT/s | 1        | 2%      |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s               | 1        | 2%      |
| Team RAM Module 8GB DIMM DDR4 2400MT/s                           | 1        | 2%      |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1        | 2%      |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1        | 2%      |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1        | 2%      |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1        | 2%      |
| SK hynix RAM HMAA2GU6CJR8N-XN 16GB DIMM DDR4 3200MT/s            | 1        | 2%      |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                        | 1        | 2%      |
| Samsung RAM Module 4GB Row Of Chips LPDDR5 6400MT/s              | 1        | 2%      |
| Samsung RAM M393A4K40BB1-CRC 32GB RIMM DDR4 2400MT/s             | 1        | 2%      |
| Samsung RAM M393A1G43DB0-CPB 8GB DIMM DDR4 2133MT/s              | 1        | 2%      |
| Samsung RAM M393A1G40DB0-CPB 8GB DIMM DDR4 2133MT/s              | 1        | 2%      |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s              | 1        | 2%      |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s              | 1        | 2%      |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s              | 1        | 2%      |
| Patriot RAM PSD416G320081 16GB DIMM DDR4 2400MT/s                | 1        | 2%      |
| Patriot RAM 7200 C34 Series 16GB DIMM DDR5 7200MT/s              | 1        | 2%      |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s               | 1        | 2%      |
| Patriot RAM 2400 C15 Series 8GB DIMM DDR4 2400MT/s               | 1        | 2%      |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 1        | 2%      |
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s             | 1        | 2%      |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s             | 1        | 2%      |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 2400MT/s              | 1        | 2%      |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 1        | 2%      |
| Kingston RAM KF3000C16D4/32GX 32GB DIMM DDR4 2400MT/s            | 1        | 2%      |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s            | 1        | 2%      |
| Kingston RAM 9965745-002.A00G 16GB DIMM DDR4 3000MT/s            | 1        | 2%      |
| Kingston RAM 9905713-042.A00G 8GB DIMM DDR4 3200MT/s             | 1        | 2%      |
| G.Skill RAM F4-3600C18-32GTZR 32GB DIMM DDR4 3600MT/s            | 1        | 2%      |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s               | 1        | 2%      |
| G.Skill RAM F4-3200C16-32GVK 32GB DIMM DDR4 3200MT/s             | 1        | 2%      |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s             | 1        | 2%      |
| G.Skill RAM F3-12800CL10-8GBXL 8GB DIMM DDR3 1600MT/s            | 1        | 2%      |
| G.Skill RAM F3-10666CL9-8GBXL 8GB DIMM DDR3 1333MT/s             | 1        | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 23       | 58.97%  |
| DDR3    | 8        | 20.51%  |
| DDR5    | 3        | 7.69%   |
| DDR     | 2        | 5.13%   |
| LPDDR5  | 1        | 2.56%   |
| DRAM    | 1        | 2.56%   |
| Unknown | 1        | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 35       | 89.74%  |
| SODIMM       | 2        | 5.13%   |
| Row Of Chips | 1        | 2.56%   |
| RIMM         | 1        | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 14       | 33.33%  |
| 16384 | 10       | 23.81%  |
| 32768 | 8        | 19.05%  |
| 4096  | 7        | 16.67%  |
| 2048  | 2        | 4.76%   |
| 49152 | 1        | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 14       | 33.33%  |
| 1600  | 8        | 19.05%  |
| 2400  | 7        | 16.67%  |
| 1333  | 4        | 9.52%   |
| 2133  | 2        | 4.76%   |
| 7200  | 1        | 2.38%   |
| 6400  | 1        | 2.38%   |
| 5600  | 1        | 2.38%   |
| 4800  | 1        | 2.38%   |
| 3600  | 1        | 2.38%   |
| 3000  | 1        | 2.38%   |
| 800   | 1        | 2.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Model                | Desktops | Percent |
|----------------------|----------|---------|
| Canon CanoScan 9000F | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 3        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Logitech Webcam C310        | 1        | 33.33%  |
| Logitech Webcam C270        | 1        | 33.33%  |
| Logitech HD Pro Webcam C920 | 1        | 33.33%  |

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
| 1     | 23       | 57.5%   |
| 0     | 9        | 22.5%   |
| 2     | 7        | 17.5%   |
| 5     | 1        | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 19       | 54.29%  |
| Net/wireless             | 7        | 20%     |
| Bluetooth                | 4        | 11.43%  |
| Net/ethernet             | 3        | 8.57%   |
| Sound                    | 1        | 2.86%   |
| Firewire controller      | 1        | 2.86%   |

