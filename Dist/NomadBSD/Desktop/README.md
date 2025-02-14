NomadBSD - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for NomadBSD.

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

Total: 79

| Vendor     | Model                       | Probe                                                     | Date         |
|------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASRock     | B550 Taichi                 | [524c9eda2c](https://bsd-hardware.info/?probe=524c9eda2c) | May 23, 2024 |
| ASRock     | B550 Taichi                 | [bf60c50ac6](https://bsd-hardware.info/?probe=bf60c50ac6) | May 23, 2024 |
| Gateway    | SX2185                      | [45623a4e3a](https://bsd-hardware.info/?probe=45623a4e3a) | Mar 24, 2024 |
| Gateway    | SX2185                      | [8d7eccbfda](https://bsd-hardware.info/?probe=8d7eccbfda) | Mar 24, 2024 |
| Lenovo     | SKYBAY SDK0J40700 WIN 32... | [dced74ec00](https://bsd-hardware.info/?probe=dced74ec00) | Jan 22, 2024 |
| Lenovo     | SHARKBAY SDK0E50510 PRO     | [8ff2212812](https://bsd-hardware.info/?probe=8ff2212812) | Jan 04, 2024 |
| Intel      | H61M-DS2                    | [bd541b60c8](https://bsd-hardware.info/?probe=bd541b60c8) | Dec 30, 2023 |
| MSI        | B450M PRO-VDH PLUS          | [742764e130](https://bsd-hardware.info/?probe=742764e130) | Dec 25, 2023 |
| MSI        | B450 TOMAHAWK MAX II        | [d9d33d12d7](https://bsd-hardware.info/?probe=d9d33d12d7) | Dec 14, 2023 |
| MSI        | B450 TOMAHAWK MAX II        | [9654df78b8](https://bsd-hardware.info/?probe=9654df78b8) | Dec 14, 2023 |
| ASRock     | H310M-HDV/M.2               | [56ef117b12](https://bsd-hardware.info/?probe=56ef117b12) | Dec 03, 2023 |
| Gigabyte   | J3455N-D3H                  | [6448ed1b12](https://bsd-hardware.info/?probe=6448ed1b12) | Oct 28, 2023 |
| Fujitsu    | D3314-E1 S26361-D3314-E1    | [2cde7906c1](https://bsd-hardware.info/?probe=2cde7906c1) | Oct 27, 2023 |
| Fujitsu    | D3314-A1 S26361-D3314-A1    | [d005339b5f](https://bsd-hardware.info/?probe=d005339b5f) | Oct 27, 2023 |
| Gigabyte   | H61M-S1                     | [723569d88a](https://bsd-hardware.info/?probe=723569d88a) | Oct 01, 2023 |
| Gigabyte   | H61M-S1                     | [8816b1ac4a](https://bsd-hardware.info/?probe=8816b1ac4a) | Sep 29, 2023 |
| Lenovo     | SHARKBAY SDK0E50510 WIN     | [66f982c40b](https://bsd-hardware.info/?probe=66f982c40b) | Aug 23, 2023 |
| ASRockRack | C226M WS                    | [06a8ca514a](https://bsd-hardware.info/?probe=06a8ca514a) | Apr 14, 2023 |
| ECS        | Z77H2-AX                    | [32a290eb5f](https://bsd-hardware.info/?probe=32a290eb5f) | Apr 13, 2023 |
| ASRock     | N68-S UCC                   | [04f43c3d70](https://bsd-hardware.info/?probe=04f43c3d70) | Feb 23, 2023 |
| HP         | 1589                        | [8a927b43cb](https://bsd-hardware.info/?probe=8a927b43cb) | Jan 26, 2023 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [335c3c990a](https://bsd-hardware.info/?probe=335c3c990a) | Jan 08, 2023 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [d893e02d90](https://bsd-hardware.info/?probe=d893e02d90) | Nov 21, 2022 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [7518e4f06a](https://bsd-hardware.info/?probe=7518e4f06a) | Nov 21, 2022 |
| ASRock     | B550 Steel Legend           | [4e6381e037](https://bsd-hardware.info/?probe=4e6381e037) | Jun 22, 2022 |
| HP         | 2B29                        | [e8c355314e](https://bsd-hardware.info/?probe=e8c355314e) | Jun 17, 2022 |
| HP         | 1589                        | [3765f1cb09](https://bsd-hardware.info/?probe=3765f1cb09) | Jun 17, 2022 |
| ASUSTek    | Maximus VIII HERO           | [c776760a11](https://bsd-hardware.info/?probe=c776760a11) | Apr 13, 2022 |
| MSI        | U-100 Ver.001               | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| Gigabyte   | X570S GAMING X              | [ff39ace6ec](https://bsd-hardware.info/?probe=ff39ace6ec) | Feb 16, 2022 |
| Intel      | DCP847SKE                   | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
| Dell       | 0M9KCM A01                  | [4db0a0ea05](https://bsd-hardware.info/?probe=4db0a0ea05) | Dec 06, 2021 |
| Gigabyte   | MZGLKBP-00                  | [e713e3adee](https://bsd-hardware.info/?probe=e713e3adee) | Dec 05, 2021 |
| ASUSTek    | PRIME Z390-P                | [1bd9270845](https://bsd-hardware.info/?probe=1bd9270845) | Nov 15, 2021 |
| Dell       | 0T10XW A01                  | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| Unknown    | X79                         | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| HP         | 87D6 SMVB                   | [f601f00e7c](https://bsd-hardware.info/?probe=f601f00e7c) | Oct 07, 2021 |
| Dell       | OptiPlex 3020               | [c391177240](https://bsd-hardware.info/?probe=c391177240) | Oct 05, 2021 |
| Dell       | OptiPlex 3020               | [070a0c6d62](https://bsd-hardware.info/?probe=070a0c6d62) | Sep 19, 2021 |
| Gigabyte   | Z370 AORUS ULTRAGAMING W... | [13371b2ab8](https://bsd-hardware.info/?probe=13371b2ab8) | Jun 27, 2021 |
| ASUSTek    | ROG STRIX X299-E GAMING     | [e91dc55970](https://bsd-hardware.info/?probe=e91dc55970) | Jun 22, 2021 |
| ASRock     | N68C-GS4 FX                 | [5abce24217](https://bsd-hardware.info/?probe=5abce24217) | Jun 06, 2021 |
| ASUSTek    | TUF GAMING B550M-PLUS       | [c6a1c1fa15](https://bsd-hardware.info/?probe=c6a1c1fa15) | May 25, 2021 |
| ASUSTek    | V-P7H55E                    | [8cf113ac55](https://bsd-hardware.info/?probe=8cf113ac55) | May 22, 2021 |
| Toshiba    | STI 005492G                 | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |
| ECT        | One Computer AMD A10-785... | [41a2a2e434](https://bsd-hardware.info/?probe=41a2a2e434) | Apr 07, 2021 |
| Acer       | EG43M                       | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| Dell       | 0NW6H5 A00                  | [650cd9b653](https://bsd-hardware.info/?probe=650cd9b653) | Mar 24, 2021 |
| Acer       | EG31M R01-C3                | [1186d46ac9](https://bsd-hardware.info/?probe=1186d46ac9) | Mar 08, 2021 |
| HP         | 158A                        | [da9d6bf86f](https://bsd-hardware.info/?probe=da9d6bf86f) | Mar 07, 2021 |
| Dell       | 0R849J A00                  | [1bd1dc24c9](https://bsd-hardware.info/?probe=1bd1dc24c9) | Mar 06, 2021 |
| ASRock     | Z490M Pro4                  | [348d592fab](https://bsd-hardware.info/?probe=348d592fab) | Mar 05, 2021 |
| VeryPC     | S400                        | [edcea11cb7](https://bsd-hardware.info/?probe=edcea11cb7) | Mar 04, 2021 |
| Acer       | EG31M R01-C3                | [046404e65c](https://bsd-hardware.info/?probe=046404e65c) | Mar 01, 2021 |
| Dell       | 0T568R A00                  | [cd086a9092](https://bsd-hardware.info/?probe=cd086a9092) | Feb 12, 2021 |
| ASRock     | B550 Phantom Gaming 4       | [2d0beb2534](https://bsd-hardware.info/?probe=2d0beb2534) | Feb 08, 2021 |
| Lenovo     | SHARKBAY 0B98401 WIN        | [2917a6fbe1](https://bsd-hardware.info/?probe=2917a6fbe1) | Jan 31, 2021 |
| HP         | 0AACh                       | [b7cac343f6](https://bsd-hardware.info/?probe=b7cac343f6) | Jan 29, 2021 |
| HP         | 3399                        | [b11946a41a](https://bsd-hardware.info/?probe=b11946a41a) | Jan 13, 2021 |
| Pegatron   | 2AB5                        | [8093f75ea2](https://bsd-hardware.info/?probe=8093f75ea2) | Jan 13, 2021 |
| Dell       | 0NW6H5 A00                  | [d54f451ea5](https://bsd-hardware.info/?probe=d54f451ea5) | Jan 07, 2021 |
| HP         | 3032h                       | [13648fd22d](https://bsd-hardware.info/?probe=13648fd22d) | Jan 07, 2021 |
| Dell       | 0KC9NP A01                  | [ee2d5f3289](https://bsd-hardware.info/?probe=ee2d5f3289) | Jan 07, 2021 |
| Dell       | 030VXY A01                  | [c117ffdc98](https://bsd-hardware.info/?probe=c117ffdc98) | Jan 07, 2021 |
| Gigabyte   | X570 AORUS MASTER           | [cfc292e9e8](https://bsd-hardware.info/?probe=cfc292e9e8) | Jan 07, 2021 |
| Dell       | 0C27VV A02                  | [cfd6a0ab4b](https://bsd-hardware.info/?probe=cfd6a0ab4b) | Jan 04, 2021 |
| Dell       | 0C27VV A02                  | [876f5d7b92](https://bsd-hardware.info/?probe=876f5d7b92) | Jan 02, 2021 |
| Dell       | 0C27VV A02                  | [889bba9dbc](https://bsd-hardware.info/?probe=889bba9dbc) | Dec 30, 2020 |
| Gigabyte   | X570 AORUS PRO              | [a3e2c4eda1](https://bsd-hardware.info/?probe=a3e2c4eda1) | Dec 30, 2020 |
| ASUSTek    | Z170-A                      | [a1c6966373](https://bsd-hardware.info/?probe=a1c6966373) | Oct 21, 2020 |
| ASRock     | AB350 Pro4                  | [407652fc8d](https://bsd-hardware.info/?probe=407652fc8d) | Oct 05, 2020 |
| Foxconn    | Napa HP P/N                 | [2a7cb7b214](https://bsd-hardware.info/?probe=2a7cb7b214) | Sep 03, 2020 |
| ASUSTek    | EMERY                       | [c93b86b3ba](https://bsd-hardware.info/?probe=c93b86b3ba) | Aug 27, 2020 |
| HP         | 0A64h                       | [10c48336b0](https://bsd-hardware.info/?probe=10c48336b0) | Aug 20, 2020 |
| ASUSTek    | M5A97 R2.0                  | [78d714a1a3](https://bsd-hardware.info/?probe=78d714a1a3) | Aug 19, 2020 |
| ASUSTek    | PRIME A320M-K               | [8a3cb911c3](https://bsd-hardware.info/?probe=8a3cb911c3) | Jul 18, 2020 |
| Gigabyte   | Z370 AORUS Ultra Gaming-... | [a03e1c19c1](https://bsd-hardware.info/?probe=a03e1c19c1) | Jul 04, 2020 |
| ASRock     | Z97 Extreme6/ac             | [9c2d19d0c3](https://bsd-hardware.info/?probe=9c2d19d0c3) | Jul 03, 2020 |
| ASRock     | B450M Pro4                  | [aa58b291b3](https://bsd-hardware.info/?probe=aa58b291b3) | May 24, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| NomadBSD 5806f915 | 18       | 29.03%  |
| NomadBSD 1.3.2    | 14       | 22.58%  |
| NomadBSD 20221130 | 7        | 11.29%  |
| NomadBSD 20231121 | 5        | 8.06%   |
| NomadBSD 20231013 | 4        | 6.45%   |
| NomadBSD 1.4-RC1  | 4        | 6.45%   |
| NomadBSD 1.4      | 3        | 4.84%   |
| NomadBSD 20240126 | 2        | 3.23%   |
| NomadBSD 1.3.1    | 2        | 3.23%   |
| NomadBSD 80dec9b9 | 1        | 1.61%   |
| NomadBSD 1.3      | 1        | 1.61%   |
| NomadBSD 1.0      | 1        | 1.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| NomadBSD | 62       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 60       | 96.77%  |
| i386  | 2        | 3.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Openbox       | 47       | 74.6%   |
| KDE5          | 5        | 7.94%   |
| xinitrc       | 4        | 6.35%   |
| XFCE          | 2        | 3.17%   |
| Enlightenment | 2        | 3.17%   |
| GNUstep       | 1        | 1.59%   |
| GNOME         | 1        | 1.59%   |
| filer         | 1        | 1.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 62       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 41       | 66.13%  |
| SDDM    | 19       | 30.65%  |
| LightDM | 2        | 3.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 22       | 35.48%  |
| Unknown | 16       | 25.81%  |
| de_DE   | 4        | 6.45%   |
| tr_TR   | 2        | 3.23%   |
| ru_RU   | 2        | 3.23%   |
| pt_BR   | 2        | 3.23%   |
| it_IT   | 2        | 3.23%   |
| hu_HU   | 2        | 3.23%   |
| fi_FI   | 2        | 3.23%   |
| zh_TW   | 1        | 1.61%   |
| pl_PL   | 1        | 1.61%   |
| nl_NL   | 1        | 1.61%   |
| es_ES   | 1        | 1.61%   |
| en_AU   | 1        | 1.61%   |
| cs_CZ   | 1        | 1.61%   |
| C       | 1        | 1.61%   |
| bg_BG   | 1        | 1.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 60       | 96.77%  |
| BIOS | 2        | 3.23%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ufs  | 46       | 74.19%  |
| Zfs  | 16       | 25.81%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 44       | 70.97%  |
| MBR  | 18       | 29.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 17.74%  |
| Hewlett-Packard     | 9        | 14.52%  |
| Gigabyte Technology | 8        | 12.9%   |
| ASRock              | 8        | 12.9%   |
| Dell                | 6        | 9.68%   |
| Lenovo              | 4        | 6.45%   |
| Acer                | 3        | 4.84%   |
| MSI                 | 2        | 3.23%   |
| Intel               | 2        | 3.23%   |
| Fujitsu             | 2        | 3.23%   |
| Semp Toshiba        | 1        | 1.61%   |
| Pegatron            | 1        | 1.61%   |
| Gateway             | 1        | 1.61%   |
| Foxconn             | 1        | 1.61%   |
| ECS                 | 1        | 1.61%   |
| ASRockRack          | 1        | 1.61%   |
| Unknown             | 1        | 1.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| HP Z420 Workstation                      | 2        | 3.23%   |
| Fujitsu FUTRO S520                       | 2        | 3.23%   |
| ASUS ROG STRIX B550-F GAMING             | 2        | 3.23%   |
| Acer Veriton M460                        | 2        | 3.23%   |
| Semp Toshiba STI                         | 1        | 1.61%   |
| Pegatron Elite 7300 Series MT            | 1        | 1.61%   |
| MSI MS-7C02                              | 1        | 1.61%   |
| MSI MS-7A38                              | 1        | 1.61%   |
| Lenovo ThinkStation P300 30AH000SUS      | 1        | 1.61%   |
| Lenovo ThinkCentre M93p 10AAS4EN00       | 1        | 1.61%   |
| Lenovo ThinkCentre M93p 10A8001HUS       | 1        | 1.61%   |
| Lenovo IdeaCentre 510S-08ISH 90FN008FNY  | 1        | 1.61%   |
| Intel H61M-DS2                           | 1        | 1.61%   |
| Intel DCP847SKE                          | 1        | 1.61%   |
| HP Z620 Workstation                      | 1        | 1.61%   |
| HP Desktop M01-F1xxx                     | 1        | 1.61%   |
| HP Compaq Elite 8300 Touch All-in-One PC | 1        | 1.61%   |
| HP Compaq dc7900 Convertible Minitower   | 1        | 1.61%   |
| HP Compaq dc7800p Convertible Minitower  | 1        | 1.61%   |
| HP Compaq dc5750 Microtower              | 1        | 1.61%   |
| HP 550-a114                              | 1        | 1.61%   |
| Gigabyte Z370 AORUS ULTRAGAMING WIFI-OP  | 1        | 1.61%   |
| Gigabyte Z370 AORUS Ultra Gaming         | 1        | 1.61%   |
| Gigabyte X570S GAMING X                  | 1        | 1.61%   |
| Gigabyte X570 AORUS PRO                  | 1        | 1.61%   |
| Gigabyte X570 AORUS MASTER               | 1        | 1.61%   |
| Gigabyte MZGLKBP-00                      | 1        | 1.61%   |
| Gigabyte J3455N-D3H                      | 1        | 1.61%   |
| Gigabyte H61M-S1                         | 1        | 1.61%   |
| Gateway SX2185                           | 1        | 1.61%   |
| Foxconn Napa                             | 1        | 1.61%   |
| ECS Z77H2-AX                             | 1        | 1.61%   |
| Dell Studio XPS 8100                     | 1        | 1.61%   |
| Dell Studio XPS 435MT                    | 1        | 1.61%   |
| Dell OptiPlex 9010                       | 1        | 1.61%   |
| Dell OptiPlex 780                        | 1        | 1.61%   |
| Dell OptiPlex 3020                       | 1        | 1.61%   |
| Dell OptiPlex 3010                       | 1        | 1.61%   |
| ASUS Z170-A                              | 1        | 1.61%   |
| ASUS V-P7H55E                            | 1        | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP Compaq           | 4        | 6.45%   |
| Dell OptiPlex       | 4        | 6.45%   |
| ASUS ROG            | 3        | 4.84%   |
| Lenovo ThinkCentre  | 2        | 3.23%   |
| HP Z420             | 2        | 3.23%   |
| Gigabyte Z370       | 2        | 3.23%   |
| Gigabyte X570       | 2        | 3.23%   |
| Fujitsu FUTRO       | 2        | 3.23%   |
| Dell Studio         | 2        | 3.23%   |
| ASUS PRIME          | 2        | 3.23%   |
| ASRock B550         | 2        | 3.23%   |
| Acer Veriton        | 2        | 3.23%   |
| Semp Toshiba STI    | 1        | 1.61%   |
| Pegatron Elite      | 1        | 1.61%   |
| MSI MS-7C02         | 1        | 1.61%   |
| MSI MS-7A38         | 1        | 1.61%   |
| Lenovo ThinkStation | 1        | 1.61%   |
| Lenovo IdeaCentre   | 1        | 1.61%   |
| Intel H61M-DS2      | 1        | 1.61%   |
| Intel DCP847SKE     | 1        | 1.61%   |
| HP Z620             | 1        | 1.61%   |
| HP Desktop          | 1        | 1.61%   |
| HP 550-a114         | 1        | 1.61%   |
| Gigabyte X570S      | 1        | 1.61%   |
| Gigabyte MZGLKBP-00 | 1        | 1.61%   |
| Gigabyte J3455N-D3H | 1        | 1.61%   |
| Gigabyte H61M-S1    | 1        | 1.61%   |
| Gateway SX2185      | 1        | 1.61%   |
| Foxconn Napa        | 1        | 1.61%   |
| ECS Z77H2-AX        | 1        | 1.61%   |
| ASUS Z170-A         | 1        | 1.61%   |
| ASUS V-P7H55E       | 1        | 1.61%   |
| ASUS TUF            | 1        | 1.61%   |
| ASUS Maximus        | 1        | 1.61%   |
| ASUS M5A97          | 1        | 1.61%   |
| ASUS ER904AA-ABA    | 1        | 1.61%   |
| ASRockRack C226M    | 1        | 1.61%   |
| ASRock Z97          | 1        | 1.61%   |
| ASRock N68C-GS4     | 1        | 1.61%   |
| ASRock N68-S        | 1        | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2020 | 6        | 9.68%   |
| 2013 | 6        | 9.68%   |
| 2009 | 6        | 9.68%   |
| 2019 | 5        | 8.06%   |
| 2018 | 5        | 8.06%   |
| 2016 | 5        | 8.06%   |
| 2017 | 4        | 6.45%   |
| 2015 | 4        | 6.45%   |
| 2010 | 4        | 6.45%   |
| 2022 | 3        | 4.84%   |
| 2021 | 3        | 4.84%   |
| 2012 | 3        | 4.84%   |
| 2011 | 3        | 4.84%   |
| 2014 | 2        | 3.23%   |
| 2008 | 1        | 1.61%   |
| 2007 | 1        | 1.61%   |
| 2006 | 1        | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 62       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 62       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 16       | 25.81%  |
| 8.01-16.0   | 16       | 25.81%  |
| 4.01-8.0    | 10       | 16.13%  |
| 32.01-64.0  | 10       | 16.13%  |
| 64.01-256.0 | 5        | 8.06%   |
| 2.01-3.0    | 4        | 6.45%   |
| 3.01-4.0    | 1        | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 28       | 45.16%  |
| 0.51-1.0 | 17       | 27.42%  |
| 1.01-2.0 | 13       | 20.97%  |
| 2.01-3.0 | 3        | 4.84%   |
| 3.01-4.0 | 1        | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 26       | 41.94%  |
| 2      | 14       | 22.58%  |
| 3      | 12       | 19.35%  |
| 0      | 5        | 8.06%   |
| 4      | 4        | 6.45%   |
| 7      | 1        | 1.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 31       | 50%     |
| No        | 31       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 60       | 96.77%  |
| No        | 2        | 3.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 54.84%  |
| Yes       | 28       | 45.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 47       | 74.6%   |
| Yes       | 16       | 25.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 18       | 29.03%  |
| Germany      | 8        | 12.9%   |
| Russia       | 4        | 6.45%   |
| France       | 4        | 6.45%   |
| Turkey       | 3        | 4.84%   |
| Thailand     | 2        | 3.23%   |
| Netherlands  | 2        | 3.23%   |
| Italy        | 2        | 3.23%   |
| Hungary      | 2        | 3.23%   |
| Finland      | 2        | 3.23%   |
| Brazil       | 2        | 3.23%   |
| Argentina    | 2        | 3.23%   |
| UK           | 1        | 1.61%   |
| Taiwan       | 1        | 1.61%   |
| Slovakia     | 1        | 1.61%   |
| Serbia       | 1        | 1.61%   |
| Saudi Arabia | 1        | 1.61%   |
| Poland       | 1        | 1.61%   |
| Indonesia    | 1        | 1.61%   |
| Czechia      | 1        | 1.61%   |
| Colombia     | 1        | 1.61%   |
| Bulgaria     | 1        | 1.61%   |
| Australia    | 1        | 1.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Wuppertal            | 3        | 4.84%   |
| Paris                | 3        | 4.84%   |
| Duncan               | 3        | 4.84%   |
| Woodland             | 2        | 3.23%   |
| Volzhskiy            | 2        | 3.23%   |
| Rio de Janeiro       | 2        | 3.23%   |
| Moscow               | 2        | 3.23%   |
| Milan                | 2        | 3.23%   |
| Lutherville-Timonium | 2        | 3.23%   |
| Istanbul             | 2        | 3.23%   |
| Hodmezovasarhely     | 2        | 3.23%   |
| Bangkok              | 2        | 3.23%   |
| Westervoort          | 1        | 1.61%   |
| Warsaw               | 1        | 1.61%   |
| Urcuit               | 1        | 1.61%   |
| Tucson               | 1        | 1.61%   |
| Taipei               | 1        | 1.61%   |
| South Tangerang      | 1        | 1.61%   |
| Sofia                | 1        | 1.61%   |
| Scottsdale           | 1        | 1.61%   |
| San Francisco        | 1        | 1.61%   |
| Peoria               | 1        | 1.61%   |
| Palm Bay             | 1        | 1.61%   |
| North Highlands      | 1        | 1.61%   |
| Melcice              | 1        | 1.61%   |
| McDonough            | 1        | 1.61%   |
| Marburg              | 1        | 1.61%   |
| Ludwigsburg          | 1        | 1.61%   |
| London               | 1        | 1.61%   |
| Langen               | 1        | 1.61%   |
| Joensuu              | 1        | 1.61%   |
| Helsinki             | 1        | 1.61%   |
| Frisco               | 1        | 1.61%   |
| Eindhoven            | 1        | 1.61%   |
| Dortmund             | 1        | 1.61%   |
| Denver               | 1        | 1.61%   |
| CГіrdoba           | 1        | 1.61%   |
| Córdoba             | 1        | 1.61%   |
| Conway               | 1        | 1.61%   |
| Cologne              | 1        | 1.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 24     | 18.56%  |
| Seagate             | 18       | 19     | 18.56%  |
| Samsung Electronics | 18       | 23     | 18.56%  |
| Toshiba             | 7        | 9      | 7.22%   |
| Crucial             | 6        | 6      | 6.19%   |
| Kingston            | 5        | 6      | 5.15%   |
| A-DATA Technology   | 5        | 5      | 5.15%   |
| Intel               | 3        | 4      | 3.09%   |
| Hewlett-Packard     | 3        | 3      | 3.09%   |
| SK hynix            | 2        | 2      | 2.06%   |
| SanDisk             | 2        | 3      | 2.06%   |
| Hitachi             | 2        | 2      | 2.06%   |
| Transcend           | 1        | 1      | 1.03%   |
| Team                | 1        | 1      | 1.03%   |
| Patriot             | 1        | 1      | 1.03%   |
| ORICO               | 1        | 1      | 1.03%   |
| Maxtor              | 1        | 1      | 1.03%   |
| HGST                | 1        | 1      | 1.03%   |
| GAMER               | 1        | 1      | 1.03%   |
| Corsair             | 1        | 1      | 1.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| WDC WDS100T1X0E-00AFY0 1TB                | 2        | 1.82%   |
| WDC WD40PURX-64GVNY0 4TB                  | 2        | 1.82%   |
| WDC WD1600AAJS-22L7A0 160GB               | 2        | 1.82%   |
| Toshiba HDWD120 2TB                       | 2        | 1.82%   |
| Seagate ST500DM002-1BD142 500GB           | 2        | 1.82%   |
| Samsung SSD 970 EVO Plus 1TB              | 2        | 1.82%   |
| Samsung SSD 970 EVO 500GB                 | 2        | 1.82%   |
| Samsung SSD 870 QVO 2TB                   | 2        | 1.82%   |
| Samsung SP2504C 250GB                     | 2        | 1.82%   |
| Kingston SA400S37480G 480GB               | 2        | 1.82%   |
| Kingston SA400S37240G 240GB               | 2        | 1.82%   |
| HP SSD EX950 2TB                          | 2        | 1.82%   |
| A-DATA SU630 240GB                        | 2        | 1.82%   |
| WDC WDS240G2G0B-00EPW0 240GB              | 1        | 0.91%   |
| WDC WDS120G2G0A-00JH30 120GB              | 1        | 0.91%   |
| WDC WD6400AAKS-22A7B2 640GB               | 1        | 0.91%   |
| WDC WD60EZRZ-00GZ5B1 6TB                  | 1        | 0.91%   |
| WDC WD40NMZW-11GX6S1 4TB                  | 1        | 0.91%   |
| WDC WD40EFAX-68JH4N0 4TB                  | 1        | 0.91%   |
| WDC WD30EZRZ-00GXCB0 3TB                  | 1        | 0.91%   |
| WDC WD2500BEKT-00PVMT0 250GB              | 1        | 0.91%   |
| WDC WD2004FBYZ-01YCBB1 2TB                | 1        | 0.91%   |
| WDC WD1200BEVE-00UYT0 120GB               | 1        | 0.91%   |
| WDC WD10JPLX-00MBPT0 1TB                  | 1        | 0.91%   |
| WDC WD10EZRZ-00HTKB0 1TB                  | 1        | 0.91%   |
| WDC WD10EZRX-00L4HB0 1TB                  | 1        | 0.91%   |
| WDC WD10EZEX-22MFCA0 1TB                  | 1        | 0.91%   |
| WDC WD10EFRX-68PJCN0 1TB                  | 1        | 0.91%   |
| WDC WD10EADS-00P8B0 1TB                   | 1        | 0.91%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1        | 0.91%   |
| Transcend TS32GCF800 32GB                 | 1        | 0.91%   |
| Toshiba MK1032GAX 100GB                   | 1        | 0.91%   |
| Toshiba MG06ACA800E 8TB                   | 1        | 0.91%   |
| Toshiba HDWD130 3TB                       | 1        | 0.91%   |
| Toshiba HDWD110 1TB                       | 1        | 0.91%   |
| Toshiba DT01ACA100 1TB                    | 1        | 0.91%   |
| Toshiba DT01ABA300 3TB                    | 1        | 0.91%   |
| Team TEAML5Lite3D1T 1TB                   | 1        | 0.91%   |
| SK hynix SKHynix_HFS256GD9TNI-L2B0B 256GB | 1        | 0.91%   |
| SK hynix SHGS31-500GS-2 500GB             | 1        | 0.91%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 18       | 19     | 35.29%  |
| WDC                 | 16       | 19     | 31.37%  |
| Toshiba             | 7        | 9      | 13.73%  |
| Samsung Electronics | 5        | 5      | 9.8%    |
| Hitachi             | 2        | 2      | 3.92%   |
| Maxtor              | 1        | 1      | 1.96%   |
| HGST                | 1        | 1      | 1.96%   |
| Hewlett-Packard     | 1        | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 10     | 26.67%  |
| A-DATA Technology   | 5        | 5      | 16.67%  |
| Kingston            | 4        | 5      | 13.33%  |
| Crucial             | 3        | 3      | 10%     |
| WDC                 | 2        | 2      | 6.67%   |
| SanDisk             | 2        | 3      | 6.67%   |
| Transcend           | 1        | 1      | 3.33%   |
| Team                | 1        | 1      | 3.33%   |
| SK hynix            | 1        | 1      | 3.33%   |
| Patriot             | 1        | 1      | 3.33%   |
| Intel               | 1        | 2      | 3.33%   |
| GAMER               | 1        | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 38       | 57     | 49.35%  |
| SSD  | 24       | 35     | 31.17%  |
| NVMe | 15       | 22     | 19.48%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 52       | 92     | 77.61%  |
| NVMe | 15       | 22     | 22.39%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 35       | 48     | 47.95%  |
| 0.51-1.0   | 21       | 24     | 28.77%  |
| 3.01-4.0   | 7        | 8      | 9.59%   |
| 1.01-2.0   | 5        | 5      | 6.85%   |
| 2.01-3.0   | 4        | 4      | 5.48%   |
| 4.01-10.0  | 1        | 3      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 48       | 77.42%  |
| 101-250    | 7        | 11.29%  |
| 21-50      | 3        | 4.84%   |
| 51-100     | 3        | 4.84%   |
| 501-1000   | 1        | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 60       | 96.77%  |
| 21-50   | 1        | 1.61%   |
| 51-100  | 1        | 1.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD40PURX-64GVNY0 4TB          | 1        | 1      | 7.69%   |
| WDC WD10EFRX-68PJCN0 1TB          | 1        | 2      | 7.69%   |
| Toshiba HDWD120 2TB               | 1        | 1      | 7.69%   |
| Toshiba DT01ABA300 3TB            | 1        | 1      | 7.69%   |
| Seagate ST9250315AS 250GB         | 1        | 1      | 7.69%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 7.69%   |
| Seagate ST3250823AS 250GB         | 1        | 1      | 7.69%   |
| Seagate ST310212A 10GB            | 1        | 1      | 7.69%   |
| Samsung Electronics SP2504C 250GB | 1        | 1      | 7.69%   |
| Samsung Electronics HM160HI 160GB | 1        | 1      | 7.69%   |
| Hewlett-Packard MB1000GCWCV 1TB   | 1        | 1      | 7.69%   |
| Crucial CT120M500SSD1 120GB       | 1        | 1      | 7.69%   |
| A-DATA Technology XM13 32GB       | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 30.77%  |
| WDC                 | 2        | 3      | 15.38%  |
| Toshiba             | 2        | 2      | 15.38%  |
| Samsung Electronics | 2        | 2      | 15.38%  |
| Hewlett-Packard     | 1        | 1      | 7.69%   |
| Crucial             | 1        | 1      | 7.69%   |
| A-DATA Technology   | 1        | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 36.36%  |
| WDC                 | 2        | 3      | 18.18%  |
| Toshiba             | 2        | 2      | 18.18%  |
| Samsung Electronics | 2        | 2      | 18.18%  |
| Hewlett-Packard     | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 12     | 83.33%  |
| SSD  | 2        | 2      | 16.67%  |

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
| Works    | 50       | 94     | 79.37%  |
| Malfunc  | 12       | 14     | 19.05%  |
| Detected | 1        | 6      | 1.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 40       | 43.96%  |
| AMD                         | 20       | 21.98%  |
| Samsung Electronics         | 8        | 8.79%   |
| ASMedia Technology          | 8        | 8.79%   |
| SanDisk                     | 3        | 3.3%    |
| Nvidia                      | 3        | 3.3%    |
| Micron/Crucial Technology   | 3        | 3.3%    |
| Biwin Storage Technology    | 2        | 2.2%    |
| VIA Technologies            | 1        | 1.1%    |
| Silicon Motion              | 1        | 1.1%    |
| Phison Electronics          | 1        | 1.1%    |
| Kingston Technology Company | 1        | 1.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 11       | 9.32%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 8        | 6.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6        | 5.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5        | 4.24%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 4.24%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4        | 3.39%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 2.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3        | 2.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 2.54%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 3        | 2.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 2.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3        | 2.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3        | 2.54%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2        | 1.69%   |
| Nvidia MCP61 SATA Controller                                                            | 2        | 1.69%   |
| Nvidia MCP61 IDE                                                                        | 2        | 1.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2        | 1.69%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2        | 1.69%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                                | 2        | 1.69%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                                | 2        | 1.69%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 1.69%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 2        | 1.69%   |
| Biwin Storage EX950 NVMe SSD                                                            | 2        | 1.69%   |
| VIA VT6421 IDE/SATA Controller                                                          | 1        | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 1        | 0.85%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                                   | 1        | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1        | 0.85%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                                     | 1        | 0.85%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                                 | 1        | 0.85%   |
| Nvidia MCP73 IDE Controller                                                             | 1        | 0.85%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                                | 1        | 0.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 1        | 0.85%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                               | 1        | 0.85%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 1        | 0.85%   |
| Intel SSD 660P Series                                                                   | 1        | 0.85%   |
| Intel NVMe Optane Memory Series                                                         | 1        | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 46       | 52.27%  |
| IDE  | 18       | 20.45%  |
| NVMe | 16       | 18.18%  |
| RAID | 5        | 5.68%   |
| SAS  | 3        | 3.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 40       | 64.52%  |
| AMD    | 22       | 35.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 4.84%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 3.23%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 3.23%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 3.23%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 1.61%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz            | 1        | 1.61%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 1.61%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1        | 1.61%   |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz         | 1        | 1.61%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 1.61%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 1.61%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.61%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 1.61%   |
| Intel Core i9-7960X CPU @ 2.80GHz           | 1        | 1.61%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.61%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.61%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.61%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.61%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.61%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1        | 1.61%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.61%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 1.61%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.61%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1        | 1.61%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 1.61%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 1.61%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.61%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.61%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.61%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.61%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.61%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 1.61%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 1.61%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz        | 1        | 1.61%   |
| Intel Core 2 Duo                            | 1        | 1.61%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 1        | 1.61%   |
| Intel Celeron CPU G530 @ 2.40GHz            | 1        | 1.61%   |
| Intel Celeron CPU 847E @ 1.10GHz            | 1        | 1.61%   |
| AMD Ryzen 7 PRO 5750G with Radeon Graphics  | 1        | 1.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 11       | 17.74%  |
| Intel Core i7           | 9        | 14.52%  |
| AMD Ryzen 5             | 8        | 12.9%   |
| Intel Core 2 Duo        | 6        | 9.68%   |
| Intel Xeon              | 5        | 8.06%   |
| Intel Celeron           | 3        | 4.84%   |
| AMD Ryzen 7             | 3        | 4.84%   |
| Intel Pentium Dual-Core | 2        | 3.23%   |
| AMD Ryzen 9             | 2        | 3.23%   |
| AMD GX                  | 2        | 3.23%   |
| AMD Athlon 64 X2        | 2        | 3.23%   |
| Intel Pentium Silver    | 1        | 1.61%   |
| Intel Pentium D         | 1        | 1.61%   |
| Intel Core i9           | 1        | 1.61%   |
| Intel Core i3           | 1        | 1.61%   |
| AMD Ryzen 7 PRO         | 1        | 1.61%   |
| AMD Phenom II X4        | 1        | 1.61%   |
| AMD FX                  | 1        | 1.61%   |
| AMD A8                  | 1        | 1.61%   |
| AMD A6                  | 1        | 1.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 23       | 37.1%   |
| 2       | 15       | 24.19%  |
| 8       | 7        | 11.29%  |
| 16      | 5        | 8.06%   |
| 6       | 5        | 8.06%   |
| 12      | 4        | 6.45%   |
| 24      | 2        | 3.23%   |
| Unknown | 1        | 1.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 61       | 98.39%  |
| 2      | 1        | 1.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 46       | 74.19%  |
| 2       | 15       | 24.19%  |
| Unknown | 1        | 1.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 8        | 12.9%   |
| IvyBridge     | 7        | 11.29%  |
| Haswell       | 6        | 9.68%   |
| SandyBridge   | 5        | 8.06%   |
| KabyLake      | 5        | 8.06%   |
| Zen 3         | 4        | 6.45%   |
| Zen 2         | 4        | 6.45%   |
| Zen+          | 3        | 4.84%   |
| Zen           | 3        | 4.84%   |
| Skylake       | 3        | 4.84%   |
| Nehalem       | 3        | 4.84%   |
| Puma          | 2        | 3.23%   |
| K8 Hammer     | 2        | 3.23%   |
| Jaguar        | 2        | 3.23%   |
| Piledriver    | 1        | 1.61%   |
| NetBurst      | 1        | 1.61%   |
| K10           | 1        | 1.61%   |
| Goldmont plus | 1        | 1.61%   |
| Goldmont      | 1        | 1.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 25       | 39.68%  |
| Nvidia | 19       | 30.16%  |
| Intel  | 19       | 30.16%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 6.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4        | 6.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 4.69%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.13%   |
| Intel HD Graphics 530                                                       | 2        | 3.13%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.13%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 3.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 3.13%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 3.13%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.56%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 1.56%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.56%   |
| Nvidia GP102 [TITAN X]                                                      | 1        | 1.56%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 1.56%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 1.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.56%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.56%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.56%   |
| Nvidia G92 [GeForce GTS 250]                                                | 1        | 1.56%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 1.56%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.56%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 1.56%   |
| Intel HD Graphics 630                                                       | 1        | 1.56%   |
| Intel HD Graphics 500                                                       | 1        | 1.56%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 1.56%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.56%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.56%   |
| AMD RV620 PRO [Radeon HD 3470]                                              | 1        | 1.56%   |
| AMD RS482/RS485 [Radeon Xpress 1100/1150]                                   | 1        | 1.56%   |
| AMD RS480 [Radeon Xpress 1150] (Secondary)                                  | 1        | 1.56%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 1        | 1.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.56%   |
| AMD Pitcairn XT GL [FirePro W7000]                                          | 1        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 1.56%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 1        | 1.56%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 1.56%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 24       | 38.71%  |
| 1 x Nvidia     | 18       | 29.03%  |
| 1 x Intel      | 18       | 29.03%  |
| 2 x AMD        | 1        | 1.61%   |
| Intel + Nvidia | 1        | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 46       | 74.19%  |
| Proprietary | 15       | 24.19%  |
| Unknown     | 1        | 1.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 39       | 62.9%   |
| 3.01-4.0   | 5        | 8.06%   |
| 1.01-2.0   | 5        | 8.06%   |
| 0.01-0.5   | 5        | 8.06%   |
| 5.01-6.0   | 4        | 6.45%   |
| 7.01-8.0   | 3        | 4.84%   |
| 0.51-1.0   | 1        | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 9        | 16.98%  |
| Samsung Electronics  | 7        | 13.21%  |
| Dell                 | 7        | 13.21%  |
| Hewlett-Packard      | 5        | 9.43%   |
| ViewSonic            | 4        | 7.55%   |
| Acer                 | 4        | 7.55%   |
| Fujitsu Siemens      | 3        | 5.66%   |
| ASUSTek Computer     | 2        | 3.77%   |
| Ancor Communications | 2        | 3.77%   |
| ___                  | 1        | 1.89%   |
| Westinghouse         | 1        | 1.89%   |
| Vizio                | 1        | 1.89%   |
| Toshiba              | 1        | 1.89%   |
| Sony                 | 1        | 1.89%   |
| Philips              | 1        | 1.89%   |
| NEC Computers        | 1        | 1.89%   |
| LG Electronics       | 1        | 1.89%   |
| HannStar             | 1        | 1.89%   |
| BenQ                 | 1        | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Fujitsu Siemens B24-9 WE FUS08C3 1920x1200 520x320mm 24.0-inch          | 3        | 5.45%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch            | 2        | 3.64%   |
| ___ MY TV LED TV ___0101 1920x1080                                      | 1        | 1.82%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch            | 1        | 1.82%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                    | 1        | 1.82%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                   | 1        | 1.82%   |
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch              | 1        | 1.82%   |
| ViewSonic VA2212 Series VSCBD2B 1920x1080 480x270mm 21.7-inch           | 1        | 1.82%   |
| ViewSonic TD2420 SERIES VSC452D 1920x1080 520x290mm 23.4-inch           | 1        | 1.82%   |
| Toshiba LCD-MONITOR LCDC980 1280x1024 380x300mm 19.1-inch               | 1        | 1.82%   |
| Sony TV SNY5D01 1360x768                                                | 1        | 1.82%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch       | 1        | 1.82%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch     | 1        | 1.82%   |
| Samsung Electronics SA300/350/360 SAM07D5 1920x1080 530x300mm 24.0-inch | 1        | 1.82%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch       | 1        | 1.82%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                       | 1        | 1.82%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch       | 1        | 1.82%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 1        | 1.82%   |
| Philips 170S PHL0856 1280x1024 340x270mm 17.1-inch                      | 1        | 1.82%   |
| NEC Computers EA275WMi NEC2BA7 2560x1440 600x340mm 27.2-inch            | 1        | 1.82%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                         | 1        | 1.82%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch             | 1        | 1.82%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch              | 1        | 1.82%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch             | 1        | 1.82%   |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch      | 1        | 1.82%   |
| Hewlett-Packard 27f 4k HPN3639 3840x2160 600x340mm 27.2-inch            | 1        | 1.82%   |
| HannStar LCD Monitor HSD0013 1280x1024 380x300mm 19.1-inch              | 1        | 1.82%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                     | 1        | 1.82%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                     | 1        | 1.82%   |
| Goldstar LG ULTRAWIDE GSM5AFB 2560x1080 800x340mm 34.2-inch             | 1        | 1.82%   |
| Goldstar LG UltraFine GSM5B10 3840x2160 480x270mm 21.7-inch             | 1        | 1.82%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 1        | 1.82%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch              | 1        | 1.82%   |
| Goldstar E2742 GSM58C9 1920x1080 600x340mm 27.2-inch                    | 1        | 1.82%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                    | 1        | 1.82%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                   | 1        | 1.82%   |
| Dell U2722D DEL422F 2560x1440 600x340mm 27.2-inch                       | 1        | 1.82%   |
| Dell U2722D DEL422D 2560x1440 600x340mm 27.2-inch                       | 1        | 1.82%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                       | 1        | 1.82%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                       | 1        | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 21       | 40.38%  |
| 1280x1024 (SXGA)   | 9        | 17.31%  |
| 1920x1200 (WUXGA)  | 5        | 9.62%   |
| 3840x2160 (4K)     | 4        | 7.69%   |
| 2560x1440 (QHD)    | 3        | 5.77%   |
| 1600x900 (HD+)     | 2        | 3.85%   |
| 1440x900 (WXGA+)   | 2        | 3.85%   |
| 1360x768           | 2        | 3.85%   |
| 2560x1080          | 1        | 1.92%   |
| 1680x1050 (WSXGA+) | 1        | 1.92%   |
| 1600x1200          | 1        | 1.92%   |
| 1366x768 (WXGA)    | 1        | 1.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 10       | 18.87%  |
| 19      | 9        | 16.98%  |
| 27      | 7        | 13.21%  |
| 21      | 7        | 13.21%  |
| 17      | 5        | 9.43%   |
| 23      | 4        | 7.55%   |
| Unknown | 4        | 7.55%   |
| 18      | 2        | 3.77%   |
| 39      | 1        | 1.89%   |
| 37      | 1        | 1.89%   |
| 34      | 1        | 1.89%   |
| 25      | 1        | 1.89%   |
| 22      | 1        | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 20       | 39.22%  |
| 401-500     | 14       | 27.45%  |
| 301-350     | 5        | 9.8%    |
| 351-400     | 4        | 7.84%   |
| Unknown     | 4        | 7.84%   |
| 801-900     | 2        | 3.92%   |
| 701-800     | 1        | 1.96%   |
| 601-700     | 1        | 1.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 30       | 58.82%  |
| 5/4     | 9        | 17.65%  |
| 16/10   | 9        | 17.65%  |
| Unknown | 2        | 3.92%   |
| 21/9    | 1        | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 18       | 33.96%  |
| 151-200        | 9        | 16.98%  |
| 301-350        | 7        | 13.21%  |
| 141-150        | 7        | 13.21%  |
| 251-300        | 5        | 9.43%   |
| Unknown        | 4        | 7.55%   |
| 501-1000       | 2        | 3.77%   |
| 351-500        | 1        | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 33       | 67.35%  |
| 101-120 | 9        | 18.37%  |
| Unknown | 4        | 8.16%   |
| 161-240 | 2        | 4.08%   |
| 121-160 | 1        | 2.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 44       | 70.97%  |
| 0     | 12       | 19.35%  |
| 2     | 5        | 8.06%   |
| 3     | 1        | 1.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 33       | 37.5%   |
| Intel                 | 30       | 34.09%  |
| Qualcomm Atheros      | 5        | 5.68%   |
| Broadcom              | 5        | 5.68%   |
| Ralink Technology     | 3        | 3.41%   |
| Mellanox Technologies | 2        | 2.27%   |
| TP-Link               | 1        | 1.14%   |
| Samsung Electronics   | 1        | 1.14%   |
| Ralink                | 1        | 1.14%   |
| Qualcomm              | 1        | 1.14%   |
| Nvidia                | 1        | 1.14%   |
| Microchip Technology  | 1        | 1.14%   |
| Huawei Technologies   | 1        | 1.14%   |
| Edimax Technology     | 1        | 1.14%   |
| D-Link System         | 1        | 1.14%   |
| Brooktrout Technology | 1        | 1.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 24       | 24.24%  |
| Intel Ethernet Connection (2) I219-V                                                  | 5        | 5.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 5        | 5.05%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 4        | 4.04%   |
| Intel Ethernet Connection I217-LM                                                     | 4        | 4.04%   |
| Intel Ethernet Controller I225-V                                                      | 3        | 3.03%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2        | 2.02%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                 | 2        | 2.02%   |
| Mellanox MT27500 Family [ConnectX-3]                                                  | 2        | 2.02%   |
| Intel I211 Gigabit Network Connection                                                 | 2        | 2.02%   |
| Intel 82567LM-3 Gigabit Network Connection                                            | 2        | 2.02%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                | 1        | 1.01%   |
| Samsung Galaxy series, misc. (tethering mode)                                         | 1        | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1        | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 1.01%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1        | 1.01%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 1.01%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 1.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1        | 1.01%   |
| Ralink RT5372 Wireless Adapter                                                        | 1        | 1.01%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                           | 1        | 1.01%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1        | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1        | 1.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 1.01%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 1.01%   |
| Qualcomm ALCATEL RNDIS Interface                                                      | 1        | 1.01%   |
| Nvidia MCP73 Ethernet                                                                 | 1        | 1.01%   |
| Microchip MCP2200 USB-to-Serial Port                                                  | 1        | 1.01%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 1.01%   |
| Intel Wireless 7260                                                                   | 1        | 1.01%   |
| Intel Wireless 3165                                                                   | 1        | 1.01%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 1.01%   |
| Intel NM10/ICH7 Family LAN Controller                                                 | 1        | 1.01%   |
| Intel I210 Gigabit Network Connection                                                 | 1        | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                                  | 1        | 1.01%   |
| Intel Ethernet Connection (2) I218-V                                                  | 1        | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1        | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 8        | 27.59%  |
| Intel                 | 7        | 24.14%  |
| Qualcomm Atheros      | 4        | 13.79%  |
| Ralink Technology     | 3        | 10.34%  |
| Broadcom              | 3        | 10.34%  |
| TP-Link               | 1        | 3.45%   |
| Ralink                | 1        | 3.45%   |
| Edimax Technology     | 1        | 3.45%   |
| D-Link System         | 1        | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2        | 6.9%    |
| Ralink RT2501/RT2573 Wireless Adapter                                                 | 2        | 6.9%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                                | 1        | 3.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1        | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 3.45%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1        | 3.45%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 3.45%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1        | 3.45%   |
| Ralink RT5372 Wireless Adapter                                                        | 1        | 3.45%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                           | 1        | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 3.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1        | 3.45%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 3.45%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 3.45%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 3.45%   |
| Intel Wireless 7260                                                                   | 1        | 3.45%   |
| Intel Wireless 3165                                                                   | 1        | 3.45%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 3.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 3.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 1        | 3.45%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 3.45%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                        | 1        | 3.45%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]                  | 1        | 3.45%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 1        | 3.45%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                          | 1        | 3.45%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1        | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 29       | 46.03%  |
| Intel                 | 28       | 44.44%  |
| Broadcom              | 2        | 3.17%   |
| Samsung Electronics   | 1        | 1.59%   |
| Qualcomm Atheros      | 1        | 1.59%   |
| Qualcomm              | 1        | 1.59%   |
| Nvidia                | 1        | 1.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 24       | 36.92%  |
| Intel Ethernet Connection (2) I219-V                                   | 5        | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5        | 7.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 6.15%   |
| Intel Ethernet Connection I217-LM                                      | 4        | 6.15%   |
| Intel Ethernet Controller I225-V                                       | 3        | 4.62%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 3.08%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 3.08%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1        | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 1.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1        | 1.54%   |
| Qualcomm ALCATEL RNDIS Interface                                       | 1        | 1.54%   |
| Nvidia MCP73 Ethernet                                                  | 1        | 1.54%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1        | 1.54%   |
| Intel I210 Gigabit Network Connection                                  | 1        | 1.54%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.54%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 1.54%   |
| Intel 82579V Gigabit Network Connection                                | 1        | 1.54%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 1.54%   |
| Intel 82567V-2 Gigabit Network Connection                              | 1        | 1.54%   |
| Intel 82567LF-2 Gigabit Network Connection                             | 1        | 1.54%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1        | 1.54%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 1        | 1.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1        | 1.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 60       | 64.52%  |
| WiFi     | 28       | 30.11%  |
| Unknown  | 4        | 4.3%    |
| Modem    | 1        | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 52       | 76.47%  |
| WiFi     | 14       | 20.59%  |
| Unknown  | 2        | 2.94%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 39       | 62.9%   |
| 2     | 19       | 30.65%  |
| 3     | 2        | 3.23%   |
| 4     | 1        | 1.61%   |
| 0     | 1        | 1.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 55       | 88.71%  |
| Yes  | 7        | 11.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 6        | 37.5%   |
| Qualcomm Atheros Communications | 2        | 12.5%   |
| Cambridge Silicon Radio         | 2        | 12.5%   |
| Broadcom                        | 2        | 12.5%   |
| TP-Link                         | 1        | 6.25%   |
| Realtek Semiconductor           | 1        | 6.25%   |
| ASUSTek Computer                | 1        | 6.25%   |
| Apple                           | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 4        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 12.5%   |
| TP-Link Bluetooth 5.0 USB Adapter                   | 1        | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 6.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 6.25%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)     | 1        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 6.25%   |
| Intel AX200 Bluetooth                               | 1        | 6.25%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1        | 6.25%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 6.25%   |
| ASUS Bluetooth Controller                           | 1        | 6.25%   |
| Apple Bluetooth Host Controller                     | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 38       | 37.62%  |
| AMD                     | 28       | 27.72%  |
| Nvidia                  | 18       | 17.82%  |
| XMOS                    | 2        | 1.98%   |
| Sony                    | 2        | 1.98%   |
| C-Media Electronics     | 2        | 1.98%   |
| BEHRINGER International | 2        | 1.98%   |
| Tenx Technology         | 1        | 0.99%   |
| RME                     | 1        | 0.99%   |
| Realtek Semiconductor   | 1        | 0.99%   |
| Quanta                  | 1        | 0.99%   |
| LG Electronics          | 1        | 0.99%   |
| Creative Technology     | 1        | 0.99%   |
| Creative Labs           | 1        | 0.99%   |
| Corsair                 | 1        | 0.99%   |
| Audio-Technica          | 1        | 0.99%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6        | 4.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5        | 4.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 4.03%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5        | 4.03%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 5        | 4.03%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4        | 3.23%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4        | 3.23%   |
| AMD Kabini HDMI/DP Audio                                                   | 4        | 3.23%   |
| AMD FCH Azalia Controller                                                  | 4        | 3.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 2.42%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 2.42%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 2.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 2.42%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 1.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.61%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 1.61%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2        | 1.61%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.61%   |
| XMOS XS1-U8 MFA (ST)                                                       | 1        | 0.81%   |
| XMOS Shanling UA2                                                          | 1        | 0.81%   |
| Tenx Technology USB  AUDIO                                                 | 1        | 0.81%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.81%   |
| Sony Audio                                                                 | 1        | 0.81%   |
| RME ADI-2 DAC (57750520)                                                   | 1        | 0.81%   |
| Realtek Semiconductor UACDemoV1.0 HoverCam Solo Spark Audio                | 1        | 0.81%   |
| Quanta USB Audio Realtek USB2.0 Audio Microphone                           | 1        | 0.81%   |
| Nvidia MCP73 High Definition Audio                                         | 1        | 0.81%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.81%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 0.81%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 12       | 17.65%  |
| Samsung Electronics | 10       | 14.71%  |
| Unknown             | 8        | 11.76%  |
| Corsair             | 8        | 11.76%  |
| SK hynix            | 7        | 10.29%  |
| Micron Technology   | 6        | 8.82%   |
| G.Skill             | 6        | 8.82%   |
| Elpida              | 3        | 4.41%   |
| Crucial             | 3        | 4.41%   |
| Nanya Technology    | 2        | 2.94%   |
| Transcend           | 1        | 1.47%   |
| EVGA                | 1        | 1.47%   |
| Unknown             | 1        | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 2        | 2.74%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 2        | 2.74%   |
| Micron RAM ITC 4GB DIMM DDR3 1066MT/s                  | 2        | 2.74%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2933MT/s      | 2        | 2.74%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 2.74%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s    | 2        | 2.74%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1        | 1.37%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 1.37%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s            | 1        | 1.37%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s            | 1        | 1.37%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s      | 1        | 1.37%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s      | 1        | 1.37%   |
| SK hynix RAM Zhidian4GDDR800000 4GB DIMM DDR2 800MT/s  | 1        | 1.37%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.37%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.37%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.37%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s   | 1        | 1.37%   |
| SK hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s   | 1        | 1.37%   |
| SK hynix RAM HMT125U6AFP8C-G7 2GB DIMM DDR3 1066MT/s   | 1        | 1.37%   |
| SK hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s        | 1        | 1.37%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2133MT/s   | 1        | 1.37%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s  | 1        | 1.37%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s  | 1        | 1.37%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s  | 1        | 1.37%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1        | 1.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s  | 1        | 1.37%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s    | 1        | 1.37%   |
| Samsung RAM M378B5673DZ1-CF8 2GB DIMM DDR3 1067MT/s    | 1        | 1.37%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 1.37%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s    | 1        | 1.37%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s    | 1        | 1.37%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s     | 1        | 1.37%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 800MT/s   | 1        | 1.37%   |
| Micron RAM 8HTF12864AZ-800H1 1GB DIMM DDR2 800MT/s     | 1        | 1.37%   |
| Micron RAM 36JSZF1G72PZ-1G4D 8GB DIMM DDR3 1333MT/s    | 1        | 1.37%   |
| Micron RAM 36JSF1G72PZ-1 8GB DIMM DDR3 1600MT/s        | 1        | 1.37%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s   | 1        | 1.37%   |
| Kingston RAM KY996D-ELD 2GB DIMM DDR3 1066MT/s         | 1        | 1.37%   |
| Kingston RAM KHX2400C15D4/8G 8192MB DIMM DDR4 2400MT/s | 1        | 1.37%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s    | 1        | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 29       | 44.62%  |
| DDR4    | 24       | 36.92%  |
| DDR2    | 9        | 13.85%  |
| SDRAM   | 1        | 1.54%   |
| DDR     | 1        | 1.54%   |
| Unknown | 1        | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 56       | 88.89%  |
| SODIMM | 7        | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 30       | 44.12%  |
| 4096  | 14       | 20.59%  |
| 2048  | 13       | 19.12%  |
| 16384 | 5        | 7.35%   |
| 1024  | 5        | 7.35%   |
| 32768 | 1        | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 16       | 24.24%  |
| 3200    | 9        | 13.64%  |
| 1333    | 8        | 12.12%  |
| 2400    | 6        | 9.09%   |
| 800     | 6        | 9.09%   |
| 1066    | 4        | 6.06%   |
| 3600    | 3        | 4.55%   |
| 3000    | 3        | 4.55%   |
| 2933    | 3        | 4.55%   |
| 533     | 2        | 3.03%   |
| 2667    | 1        | 1.52%   |
| 2133    | 1        | 1.52%   |
| 1866    | 1        | 1.52%   |
| 1067    | 1        | 1.52%   |
| 667     | 1        | 1.52%   |
| Unknown | 1        | 1.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 50%     |
| Apple           | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| HP PNP Fax Null                                                          | 1        | 33.33%  |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1        | 33.33%  |
| Apple Gamesir-G3s 2.10                                                   | 1        | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Seiko Epson ES-H7200 [GT-20000] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 3        | 42.86%  |
| Quanta                   | 1        | 14.29%  |
| Novatek Microelectronics | 1        | 14.29%  |
| Microdia                 | 1        | 14.29%  |
| Cubeternet               | 1        | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Quanta Realtek DMFT RGB                                             | 1        | 14.29%  |
| Novatek HP High Definition 2MP Webcam                               | 1        | 14.29%  |
| Microdia USB 2.0 Camera                                             | 1        | 14.29%  |
| Logitech Webcam C310                                                | 1        | 14.29%  |
| Logitech Webcam C270                                                | 1        | 14.29%  |
| Logitech C505 HD Webcam                                             | 1        | 14.29%  |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 14.29%  |

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
| 1     | 27       | 43.55%  |
| 0     | 17       | 27.42%  |
| 2     | 15       | 24.19%  |
| 3     | 2        | 3.23%   |
| 7     | 1        | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 32       | 48.48%  |
| Firewire controller      | 14       | 21.21%  |
| Net/wireless             | 9        | 13.64%  |
| Network                  | 4        | 6.06%   |
| Sound                    | 3        | 4.55%   |
| Bluetooth                | 3        | 4.55%   |
| Card reader              | 1        | 1.52%   |

