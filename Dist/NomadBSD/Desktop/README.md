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

Total: 68

| Vendor     | Model                       | Probe                                                     | Date         |
|------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| NomadBSD 5806f915 | 18       | 33.33%  |
| NomadBSD 1.3.2    | 14       | 25.93%  |
| NomadBSD 20221130 | 7        | 12.96%  |
| NomadBSD 1.4-RC1  | 4        | 7.41%   |
| NomadBSD 20231013 | 3        | 5.56%   |
| NomadBSD 1.4      | 3        | 5.56%   |
| NomadBSD 1.3.1    | 2        | 3.7%    |
| NomadBSD 80dec9b9 | 1        | 1.85%   |
| NomadBSD 1.3      | 1        | 1.85%   |
| NomadBSD 1.0      | 1        | 1.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| NomadBSD | 54       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 53       | 98.15%  |
| i386  | 1        | 1.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Openbox       | 45       | 81.82%  |
| KDE5          | 5        | 9.09%   |
| Enlightenment | 2        | 3.64%   |
| GNUstep       | 1        | 1.82%   |
| GNOME         | 1        | 1.82%   |
| filer         | 1        | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 54       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SLiM    | 41       | 75.93%  |
| SDDM    | 11       | 20.37%  |
| LightDM | 2        | 3.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 20       | 37.04%  |
| Unknown | 14       | 25.93%  |
| de_DE   | 4        | 7.41%   |
| tr_TR   | 2        | 3.7%    |
| ru_RU   | 2        | 3.7%    |
| pt_BR   | 2        | 3.7%    |
| it_IT   | 2        | 3.7%    |
| hu_HU   | 2        | 3.7%    |
| zh_TW   | 1        | 1.85%   |
| fi_FI   | 1        | 1.85%   |
| es_ES   | 1        | 1.85%   |
| en_AU   | 1        | 1.85%   |
| cs_CZ   | 1        | 1.85%   |
| bg_BG   | 1        | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 53       | 98.15%  |
| BIOS | 1        | 1.85%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ufs  | 40       | 74.07%  |
| Zfs  | 14       | 25.93%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 38       | 70.37%  |
| MBR  | 16       | 29.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 11       | 20.37%  |
| Hewlett-Packard     | 9        | 16.67%  |
| Gigabyte Technology | 8        | 14.81%  |
| Dell                | 6        | 11.11%  |
| ASRock              | 6        | 11.11%  |
| Acer                | 3        | 5.56%   |
| Lenovo              | 2        | 3.7%    |
| Fujitsu             | 2        | 3.7%    |
| Semp Toshiba        | 1        | 1.85%   |
| Pegatron            | 1        | 1.85%   |
| Intel               | 1        | 1.85%   |
| Foxconn             | 1        | 1.85%   |
| ECS                 | 1        | 1.85%   |
| ASRockRack          | 1        | 1.85%   |
| Unknown             | 1        | 1.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| HP Z420 Workstation                      | 2        | 3.7%    |
| Fujitsu FUTRO S520                       | 2        | 3.7%    |
| ASUS ROG STRIX B550-F GAMING             | 2        | 3.7%    |
| Acer Veriton M460                        | 2        | 3.7%    |
| Semp Toshiba STI                         | 1        | 1.85%   |
| Pegatron Elite 7300 Series MT            | 1        | 1.85%   |
| Lenovo ThinkCentre M93p 10AAS4EN00       | 1        | 1.85%   |
| Lenovo ThinkCentre M93p 10A8001HUS       | 1        | 1.85%   |
| Intel DCP847SKE                          | 1        | 1.85%   |
| HP Z620 Workstation                      | 1        | 1.85%   |
| HP Desktop M01-F1xxx                     | 1        | 1.85%   |
| HP Compaq Elite 8300 Touch All-in-One PC | 1        | 1.85%   |
| HP Compaq dc7900 Convertible Minitower   | 1        | 1.85%   |
| HP Compaq dc7800p Convertible Minitower  | 1        | 1.85%   |
| HP Compaq dc5750 Microtower              | 1        | 1.85%   |
| HP 550-a114                              | 1        | 1.85%   |
| Gigabyte Z370 AORUS ULTRAGAMING WIFI-OP  | 1        | 1.85%   |
| Gigabyte Z370 AORUS Ultra Gaming         | 1        | 1.85%   |
| Gigabyte X570S GAMING X                  | 1        | 1.85%   |
| Gigabyte X570 AORUS PRO                  | 1        | 1.85%   |
| Gigabyte X570 AORUS MASTER               | 1        | 1.85%   |
| Gigabyte MZGLKBP-00                      | 1        | 1.85%   |
| Gigabyte J3455N-D3H                      | 1        | 1.85%   |
| Gigabyte H61M-S1                         | 1        | 1.85%   |
| Foxconn Napa                             | 1        | 1.85%   |
| ECS Z77H2-AX                             | 1        | 1.85%   |
| Dell Studio XPS 8100                     | 1        | 1.85%   |
| Dell Studio XPS 435MT                    | 1        | 1.85%   |
| Dell OptiPlex 9010                       | 1        | 1.85%   |
| Dell OptiPlex 780                        | 1        | 1.85%   |
| Dell OptiPlex 3020                       | 1        | 1.85%   |
| Dell OptiPlex 3010                       | 1        | 1.85%   |
| ASUS Z170-A                              | 1        | 1.85%   |
| ASUS V-P7H55E                            | 1        | 1.85%   |
| ASUS TUF GAMING B550M-PLUS               | 1        | 1.85%   |
| ASUS ROG STRIX X299-E GAMING             | 1        | 1.85%   |
| ASUS PRIME Z390-P                        | 1        | 1.85%   |
| ASUS PRIME A320M-K                       | 1        | 1.85%   |
| ASUS Maximus VIII HERO                   | 1        | 1.85%   |
| ASUS M5A97 R2.0                          | 1        | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP Compaq           | 4        | 7.41%   |
| Dell OptiPlex       | 4        | 7.41%   |
| ASUS ROG            | 3        | 5.56%   |
| Lenovo ThinkCentre  | 2        | 3.7%    |
| HP Z420             | 2        | 3.7%    |
| Gigabyte Z370       | 2        | 3.7%    |
| Gigabyte X570       | 2        | 3.7%    |
| Fujitsu FUTRO       | 2        | 3.7%    |
| Dell Studio         | 2        | 3.7%    |
| ASUS PRIME          | 2        | 3.7%    |
| Acer Veriton        | 2        | 3.7%    |
| Semp Toshiba STI    | 1        | 1.85%   |
| Pegatron Elite      | 1        | 1.85%   |
| Intel DCP847SKE     | 1        | 1.85%   |
| HP Z620             | 1        | 1.85%   |
| HP Desktop          | 1        | 1.85%   |
| HP 550-a114         | 1        | 1.85%   |
| Gigabyte X570S      | 1        | 1.85%   |
| Gigabyte MZGLKBP-00 | 1        | 1.85%   |
| Gigabyte J3455N-D3H | 1        | 1.85%   |
| Gigabyte H61M-S1    | 1        | 1.85%   |
| Foxconn Napa        | 1        | 1.85%   |
| ECS Z77H2-AX        | 1        | 1.85%   |
| ASUS Z170-A         | 1        | 1.85%   |
| ASUS V-P7H55E       | 1        | 1.85%   |
| ASUS TUF            | 1        | 1.85%   |
| ASUS Maximus        | 1        | 1.85%   |
| ASUS M5A97          | 1        | 1.85%   |
| ASUS ER904AA-ABA    | 1        | 1.85%   |
| ASRockRack C226M    | 1        | 1.85%   |
| ASRock Z97          | 1        | 1.85%   |
| ASRock N68C-GS4     | 1        | 1.85%   |
| ASRock N68-S        | 1        | 1.85%   |
| ASRock B550         | 1        | 1.85%   |
| ASRock B450M        | 1        | 1.85%   |
| ASRock AB350        | 1        | 1.85%   |
| Acer Aspire         | 1        | 1.85%   |
| Unknown             | 1        | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2013 | 6        | 11.11%  |
| 2009 | 6        | 11.11%  |
| 2019 | 5        | 9.26%   |
| 2018 | 5        | 9.26%   |
| 2021 | 4        | 7.41%   |
| 2020 | 4        | 7.41%   |
| 2015 | 4        | 7.41%   |
| 2017 | 3        | 5.56%   |
| 2016 | 3        | 5.56%   |
| 2012 | 3        | 5.56%   |
| 2010 | 3        | 5.56%   |
| 2014 | 2        | 3.7%    |
| 2011 | 2        | 3.7%    |
| 2022 | 1        | 1.85%   |
| 2008 | 1        | 1.85%   |
| 2007 | 1        | 1.85%   |
| 2006 | 1        | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 54       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 54       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 14       | 25.93%  |
| 16.01-24.0  | 13       | 24.07%  |
| 4.01-8.0    | 10       | 18.52%  |
| 32.01-64.0  | 9        | 16.67%  |
| 64.01-256.0 | 4        | 7.41%   |
| 2.01-3.0    | 3        | 5.56%   |
| 3.01-4.0    | 1        | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 25       | 46.3%   |
| 0.51-1.0 | 15       | 27.78%  |
| 1.01-2.0 | 12       | 22.22%  |
| 2.01-3.0 | 2        | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 22       | 40.74%  |
| 2      | 12       | 22.22%  |
| 3      | 11       | 20.37%  |
| 4      | 4        | 7.41%   |
| 0      | 4        | 7.41%   |
| 7      | 1        | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 29       | 53.7%   |
| Yes       | 25       | 46.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 52       | 96.3%   |
| No        | 2        | 3.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 55.56%  |
| Yes       | 24       | 44.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 41       | 74.55%  |
| Yes       | 14       | 25.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 17       | 31.48%  |
| Germany     | 8        | 14.81%  |
| France      | 4        | 7.41%   |
| Turkey      | 3        | 5.56%   |
| Russia      | 3        | 5.56%   |
| Thailand    | 2        | 3.7%    |
| Italy       | 2        | 3.7%    |
| Hungary     | 2        | 3.7%    |
| Brazil      | 2        | 3.7%    |
| Argentina   | 2        | 3.7%    |
| Taiwan      | 1        | 1.85%   |
| Slovakia    | 1        | 1.85%   |
| Serbia      | 1        | 1.85%   |
| Netherlands | 1        | 1.85%   |
| Finland     | 1        | 1.85%   |
| Czechia     | 1        | 1.85%   |
| Colombia    | 1        | 1.85%   |
| Bulgaria    | 1        | 1.85%   |
| Australia   | 1        | 1.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Wuppertal            | 3        | 5.56%   |
| Paris                | 3        | 5.56%   |
| Duncan               | 3        | 5.56%   |
| Woodland             | 2        | 3.7%    |
| Volzhskiy            | 2        | 3.7%    |
| Rio de Janeiro       | 2        | 3.7%    |
| Milan                | 2        | 3.7%    |
| Lutherville-Timonium | 2        | 3.7%    |
| Istanbul             | 2        | 3.7%    |
| Hodmezovasarhely     | 2        | 3.7%    |
| Bangkok              | 2        | 3.7%    |
| Urcuit               | 1        | 1.85%   |
| Tucson               | 1        | 1.85%   |
| Taipei               | 1        | 1.85%   |
| Sofia                | 1        | 1.85%   |
| Scottsdale           | 1        | 1.85%   |
| San Francisco        | 1        | 1.85%   |
| Peoria               | 1        | 1.85%   |
| Palm Bay             | 1        | 1.85%   |
| Moscow               | 1        | 1.85%   |
| Melcice              | 1        | 1.85%   |
| McDonough            | 1        | 1.85%   |
| Marburg              | 1        | 1.85%   |
| Ludwigsburg          | 1        | 1.85%   |
| Langen               | 1        | 1.85%   |
| Helsinki             | 1        | 1.85%   |
| Frisco               | 1        | 1.85%   |
| Eindhoven            | 1        | 1.85%   |
| Dortmund             | 1        | 1.85%   |
| Denver               | 1        | 1.85%   |
| CГіrdoba           | 1        | 1.85%   |
| Córdoba             | 1        | 1.85%   |
| Conway               | 1        | 1.85%   |
| Cologne              | 1        | 1.85%   |
| Cleveland            | 1        | 1.85%   |
| Brisbane             | 1        | 1.85%   |
| BogotГЎ            | 1        | 1.85%   |
| Bilina               | 1        | 1.85%   |
| Belgrade             | 1        | 1.85%   |
| BalД±kesir         | 1        | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 17       | 23     | 19.54%  |
| Samsung Electronics | 17       | 22     | 19.54%  |
| Seagate             | 15       | 16     | 17.24%  |
| Toshiba             | 7        | 9      | 8.05%   |
| Kingston            | 5        | 6      | 5.75%   |
| Crucial             | 5        | 5      | 5.75%   |
| A-DATA Technology   | 5        | 5      | 5.75%   |
| Hewlett-Packard     | 3        | 3      | 3.45%   |
| SK hynix            | 2        | 2      | 2.3%    |
| Intel               | 2        | 2      | 2.3%    |
| Hitachi             | 2        | 2      | 2.3%    |
| Transcend           | 1        | 1      | 1.15%   |
| Team                | 1        | 1      | 1.15%   |
| SanDisk             | 1        | 2      | 1.15%   |
| ORICO               | 1        | 1      | 1.15%   |
| Maxtor              | 1        | 1      | 1.15%   |
| HGST                | 1        | 1      | 1.15%   |
| Corsair             | 1        | 1      | 1.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| WDC WDS100T1X0E-00AFY0 1TB                | 2        | 2.02%   |
| WDC WD40PURX-64GVNY0 4TB                  | 2        | 2.02%   |
| WDC WD1600AAJS-22L7A0 160GB               | 2        | 2.02%   |
| Toshiba HDWD120 2TB                       | 2        | 2.02%   |
| Seagate ST500DM002-1BD142 500GB           | 2        | 2.02%   |
| Samsung SSD 970 EVO Plus 1TB              | 2        | 2.02%   |
| Samsung SSD 970 EVO 500GB                 | 2        | 2.02%   |
| Samsung SSD 870 QVO 2TB                   | 2        | 2.02%   |
| Kingston SA400S37480G 480GB               | 2        | 2.02%   |
| Kingston SA400S37240G 240GB               | 2        | 2.02%   |
| HP SSD EX950 2TB                          | 2        | 2.02%   |
| A-DATA SU630 240GB                        | 2        | 2.02%   |
| WDC WDS240G2G0B-00EPW0 240GB              | 1        | 1.01%   |
| WDC WDS120G2G0A-00JH30 120GB              | 1        | 1.01%   |
| WDC WD6400AAKS-22A7B2 640GB               | 1        | 1.01%   |
| WDC WD60EZRZ-00GZ5B1 6TB                  | 1        | 1.01%   |
| WDC WD40NMZW-11GX6S1 4TB                  | 1        | 1.01%   |
| WDC WD40EFAX-68JH4N0 4TB                  | 1        | 1.01%   |
| WDC WD30EZRZ-00GXCB0 3TB                  | 1        | 1.01%   |
| WDC WD2500BEKT-00PVMT0 250GB              | 1        | 1.01%   |
| WDC WD2004FBYZ-01YCBB1 2TB                | 1        | 1.01%   |
| WDC WD1200BEVE-00UYT0 120GB               | 1        | 1.01%   |
| WDC WD10JPLX-00MBPT0 1TB                  | 1        | 1.01%   |
| WDC WD10EZRZ-00HTKB0 1TB                  | 1        | 1.01%   |
| WDC WD10EZRX-00L4HB0 1TB                  | 1        | 1.01%   |
| WDC WD10EFRX-68PJCN0 1TB                  | 1        | 1.01%   |
| WDC WD10EADS-00P8B0 1TB                   | 1        | 1.01%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1        | 1.01%   |
| Transcend TS32GCF800 32GB                 | 1        | 1.01%   |
| Toshiba MK1032GAX 100GB                   | 1        | 1.01%   |
| Toshiba MG06ACA800E 8TB                   | 1        | 1.01%   |
| Toshiba HDWD130 3TB                       | 1        | 1.01%   |
| Toshiba HDWD110 1TB                       | 1        | 1.01%   |
| Toshiba DT01ACA100 1TB                    | 1        | 1.01%   |
| Toshiba DT01ABA300 3TB                    | 1        | 1.01%   |
| Team TEAML5Lite3D1T 1TB                   | 1        | 1.01%   |
| SK hynix SKHynix_HFS256GD9TNI-L2B0B 256GB | 1        | 1.01%   |
| SK hynix SHGS31-500GS-2 500GB             | 1        | 1.01%   |
| Seagate ST9500325AS 500GB                 | 1        | 1.01%   |
| Seagate ST9250315AS 250GB                 | 1        | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 18     | 32.61%  |
| Seagate             | 15       | 16     | 32.61%  |
| Toshiba             | 7        | 9      | 15.22%  |
| Samsung Electronics | 4        | 4      | 8.7%    |
| Hitachi             | 2        | 2      | 4.35%   |
| Maxtor              | 1        | 1      | 2.17%   |
| HGST                | 1        | 1      | 2.17%   |
| Hewlett-Packard     | 1        | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 10     | 32%     |
| A-DATA Technology   | 5        | 5      | 20%     |
| Kingston            | 4        | 5      | 16%     |
| WDC                 | 2        | 2      | 8%      |
| Crucial             | 2        | 2      | 8%      |
| Transcend           | 1        | 1      | 4%      |
| Team                | 1        | 1      | 4%      |
| SK hynix            | 1        | 1      | 4%      |
| SanDisk             | 1        | 2      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 52     | 47.83%  |
| SSD  | 21       | 29     | 30.43%  |
| NVMe | 15       | 22     | 21.74%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 45       | 81     | 75%     |
| NVMe | 15       | 22     | 25%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 31       | 43     | 48.44%  |
| 0.51-1.0   | 18       | 21     | 28.13%  |
| 3.01-4.0   | 5        | 5      | 7.81%   |
| 1.01-2.0   | 5        | 5      | 7.81%   |
| 2.01-3.0   | 4        | 4      | 6.25%   |
| 4.01-10.0  | 1        | 3      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 40       | 74.07%  |
| 101-250    | 7        | 12.96%  |
| 21-50      | 3        | 5.56%   |
| 51-100     | 3        | 5.56%   |
| 501-1000   | 1        | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 52       | 96.3%   |
| 21-50   | 1        | 1.85%   |
| 51-100  | 1        | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD40PURX-64GVNY0 4TB          | 1        | 1      | 9.09%   |
| WDC WD10EFRX-68PJCN0 1TB          | 1        | 2      | 9.09%   |
| Toshiba HDWD120 2TB               | 1        | 1      | 9.09%   |
| Toshiba DT01ABA300 3TB            | 1        | 1      | 9.09%   |
| Seagate ST9250315AS 250GB         | 1        | 1      | 9.09%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 9.09%   |
| Seagate ST3250823AS 250GB         | 1        | 1      | 9.09%   |
| Seagate ST310212A 10GB            | 1        | 1      | 9.09%   |
| Samsung Electronics HM160HI 160GB | 1        | 1      | 9.09%   |
| Hewlett-Packard MB1000GCWCV 1TB   | 1        | 1      | 9.09%   |
| A-DATA Technology XM13 32GB       | 1        | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 36.36%  |
| WDC                 | 2        | 3      | 18.18%  |
| Toshiba             | 2        | 2      | 18.18%  |
| Samsung Electronics | 1        | 1      | 9.09%   |
| Hewlett-Packard     | 1        | 1      | 9.09%   |
| A-DATA Technology   | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 4      | 40%     |
| WDC                 | 2        | 3      | 20%     |
| Toshiba             | 2        | 2      | 20%     |
| Samsung Electronics | 1        | 1      | 10%     |
| Hewlett-Packard     | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 11     | 90%     |
| SSD  | 1        | 1      | 10%     |

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
| Works    | 44       | 85     | 80%     |
| Malfunc  | 10       | 12     | 18.18%  |
| Detected | 1        | 6      | 1.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 36       | 44.44%  |
| AMD                         | 16       | 19.75%  |
| Samsung Electronics         | 7        | 8.64%   |
| ASMedia Technology          | 7        | 8.64%   |
| SanDisk                     | 3        | 3.7%    |
| Nvidia                      | 3        | 3.7%    |
| Micron/Crucial Technology   | 3        | 3.7%    |
| Biwin Storage Technology    | 2        | 2.47%   |
| VIA Technologies            | 1        | 1.23%   |
| Silicon Motion              | 1        | 1.23%   |
| Phison Electronics          | 1        | 1.23%   |
| Kingston Technology Company | 1        | 1.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10       | 9.35%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 7        | 6.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5        | 4.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4        | 3.74%   |
| AMD 500 Series Chipset SATA Controller                                         | 4        | 3.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 2.8%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 3        | 2.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 2.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 2.8%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 2.8%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2        | 1.87%   |
| Nvidia MCP61 SATA Controller                                                   | 2        | 1.87%   |
| Nvidia MCP61 IDE                                                               | 2        | 1.87%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 1.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 1.87%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 2        | 1.87%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 2        | 1.87%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                       | 2        | 1.87%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2        | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 1.87%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 1.87%   |
| Biwin Storage EX950 NVMe SSD                                                   | 2        | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 1.87%   |
| VIA VT6421 IDE/SATA Controller                                                 | 1        | 0.93%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1        | 0.93%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 1        | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 0.93%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 1        | 0.93%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                        | 1        | 0.93%   |
| Nvidia MCP73 IDE Controller                                                    | 1        | 0.93%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                       | 1        | 0.93%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 0.93%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 1        | 0.93%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1        | 0.93%   |
| Intel SSD 660P Series                                                          | 1        | 0.93%   |
| Intel NVMe Optane Memory Series                                                | 1        | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1        | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 39       | 49.37%  |
| IDE  | 17       | 21.52%  |
| NVMe | 15       | 18.99%  |
| RAID | 5        | 6.33%   |
| SAS  | 3        | 3.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 36       | 66.67%  |
| AMD    | 18       | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 5.56%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 3.7%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 3.7%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 3.7%    |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 1.85%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz            | 1        | 1.85%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 1.85%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1        | 1.85%   |
| Intel Xeon CPU E3-1276 v3 @ 3.60GHz         | 1        | 1.85%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 1.85%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 1.85%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 1.85%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 1.85%   |
| Intel Core i9-7960X CPU @ 2.80GHz           | 1        | 1.85%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 1.85%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 1.85%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 1.85%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 1.85%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 1.85%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1        | 1.85%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 1.85%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 1.85%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 1.85%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 1        | 1.85%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 1.85%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 1.85%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 1.85%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 1.85%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 1.85%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 1.85%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 1.85%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz        | 1        | 1.85%   |
| Intel Core 2 Duo                            | 1        | 1.85%   |
| Intel Celeron CPU J3455 @ 1.50GHz           | 1        | 1.85%   |
| Intel Celeron CPU 847E @ 1.10GHz            | 1        | 1.85%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 1        | 1.85%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 1.85%   |
| AMD Ryzen 5 4600G with Radeon Graphics      | 1        | 1.85%   |
| AMD Ryzen 5 3600XT 6-Core Processor         | 1        | 1.85%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 9        | 16.67%  |
| Intel Core i7           | 8        | 14.81%  |
| AMD Ryzen 5             | 7        | 12.96%  |
| Intel Core 2 Duo        | 6        | 11.11%  |
| Intel Xeon              | 5        | 9.26%   |
| Intel Pentium Dual-Core | 2        | 3.7%    |
| Intel Celeron           | 2        | 3.7%    |
| AMD Ryzen 9             | 2        | 3.7%    |
| AMD Ryzen 7             | 2        | 3.7%    |
| AMD GX                  | 2        | 3.7%    |
| AMD Athlon 64 X2        | 2        | 3.7%    |
| Intel Pentium Silver    | 1        | 1.85%   |
| Intel Pentium D         | 1        | 1.85%   |
| Intel Core i9           | 1        | 1.85%   |
| Intel Core i3           | 1        | 1.85%   |
| AMD Phenom II X4        | 1        | 1.85%   |
| AMD FX                  | 1        | 1.85%   |
| AMD A8                  | 1        | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 20       | 37.04%  |
| 2       | 14       | 25.93%  |
| 8       | 6        | 11.11%  |
| 12      | 4        | 7.41%   |
| 6       | 4        | 7.41%   |
| 16      | 3        | 5.56%   |
| 24      | 2        | 3.7%    |
| Unknown | 1        | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 53       | 98.15%  |
| 2      | 1        | 1.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 39       | 72.22%  |
| 2       | 14       | 25.93%  |
| Unknown | 1        | 1.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 8        | 14.81%  |
| IvyBridge     | 7        | 12.96%  |
| Haswell       | 5        | 9.26%   |
| SandyBridge   | 4        | 7.41%   |
| KabyLake      | 4        | 7.41%   |
| Zen 3         | 3        | 5.56%   |
| Zen 2         | 3        | 5.56%   |
| Zen           | 3        | 5.56%   |
| Nehalem       | 3        | 5.56%   |
| Zen+          | 2        | 3.7%    |
| Skylake       | 2        | 3.7%    |
| Puma          | 2        | 3.7%    |
| K8 Hammer     | 2        | 3.7%    |
| Piledriver    | 1        | 1.85%   |
| NetBurst      | 1        | 1.85%   |
| K10           | 1        | 1.85%   |
| Jaguar        | 1        | 1.85%   |
| Goldmont plus | 1        | 1.85%   |
| Goldmont      | 1        | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 21       | 38.18%  |
| Nvidia | 17       | 30.91%  |
| Intel  | 17       | 30.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 7.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3        | 5.36%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 5.36%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 3.57%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 3.57%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 3.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 3.57%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 3.57%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 1.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 1.79%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 1.79%   |
| Nvidia GP102 [TITAN X]                                                      | 1        | 1.79%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 1.79%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 1.79%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 1.79%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 1.79%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 1.79%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 1.79%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 1.79%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller              | 1        | 1.79%   |
| Intel HD Graphics 630                                                       | 1        | 1.79%   |
| Intel HD Graphics 530                                                       | 1        | 1.79%   |
| Intel HD Graphics 500                                                       | 1        | 1.79%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 1.79%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 1.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 1.79%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 1.79%   |
| AMD RV620 PRO [Radeon HD 3470]                                              | 1        | 1.79%   |
| AMD RS482/RS485 [Radeon Xpress 1100/1150]                                   | 1        | 1.79%   |
| AMD RS480 [Radeon Xpress 1150] (Secondary)                                  | 1        | 1.79%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 1        | 1.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 1.79%   |
| AMD Pitcairn XT GL [FirePro W7000]                                          | 1        | 1.79%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 1        | 1.79%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 1.79%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 1        | 1.79%   |
| AMD Mullins [Radeon R2 Graphics]                                            | 1        | 1.79%   |
| AMD Kabini [Radeon HD 8310E]                                                | 1        | 1.79%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 1        | 1.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 20       | 37.04%  |
| 1 x Nvidia     | 16       | 29.63%  |
| 1 x Intel      | 16       | 29.63%  |
| 2 x AMD        | 1        | 1.85%   |
| Intel + Nvidia | 1        | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 39       | 72.22%  |
| Proprietary | 14       | 25.93%  |
| Unknown     | 1        | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 61.11%  |
| 1.01-2.0   | 5        | 9.26%   |
| 5.01-6.0   | 4        | 7.41%   |
| 3.01-4.0   | 4        | 7.41%   |
| 0.01-0.5   | 4        | 7.41%   |
| 7.01-8.0   | 3        | 5.56%   |
| 0.51-1.0   | 1        | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 7        | 15.22%  |
| Dell                 | 6        | 13.04%  |
| Samsung Electronics  | 5        | 10.87%  |
| Hewlett-Packard      | 4        | 8.7%    |
| Acer                 | 4        | 8.7%    |
| ViewSonic            | 3        | 6.52%   |
| Fujitsu Siemens      | 3        | 6.52%   |
| ASUSTek Computer     | 2        | 4.35%   |
| Ancor Communications | 2        | 4.35%   |
| ___                  | 1        | 2.17%   |
| Westinghouse         | 1        | 2.17%   |
| Vizio                | 1        | 2.17%   |
| Toshiba              | 1        | 2.17%   |
| Sony                 | 1        | 2.17%   |
| Philips              | 1        | 2.17%   |
| NEC Computers        | 1        | 2.17%   |
| LG Electronics       | 1        | 2.17%   |
| HannStar             | 1        | 2.17%   |
| BenQ                 | 1        | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Fujitsu Siemens B24-9 WE FUS08C3 1920x1200 520x320mm 24.0-inch       | 3        | 6.38%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch         | 2        | 4.26%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1        | 2.13%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch         | 1        | 2.13%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                 | 1        | 2.13%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                | 1        | 2.13%   |
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch           | 1        | 2.13%   |
| ViewSonic TD2420 SERIES VSC452D 1920x1080 520x290mm 23.4-inch        | 1        | 2.13%   |
| Toshiba LCD-MONITOR LCDC980 1280x1024 380x300mm 19.1-inch            | 1        | 2.13%   |
| Sony TV SNY5D01 1360x768                                             | 1        | 2.13%   |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch    | 1        | 2.13%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch  | 1        | 2.13%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch    | 1        | 2.13%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                    | 1        | 2.13%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 600x340mm 27.2-inch    | 1        | 2.13%   |
| Philips 170S PHL0856 1280x1024 340x270mm 17.1-inch                   | 1        | 2.13%   |
| NEC Computers EA275WMi NEC2BA7 2560x1440 600x340mm 27.2-inch         | 1        | 2.13%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                      | 1        | 2.13%   |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch          | 1        | 2.13%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch           | 1        | 2.13%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 1        | 2.13%   |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch   | 1        | 2.13%   |
| HannStar LCD Monitor HSD0013 1280x1024 380x300mm 19.1-inch           | 1        | 2.13%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                  | 1        | 2.13%   |
| Goldstar LG UltraFine GSM5B10 3840x2160 480x270mm 21.7-inch          | 1        | 2.13%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 1        | 2.13%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch           | 1        | 2.13%   |
| Goldstar E2742 GSM58C9 1920x1080 600x340mm 27.2-inch                 | 1        | 2.13%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                 | 1        | 2.13%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                | 1        | 2.13%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                    | 1        | 2.13%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 1        | 2.13%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 1        | 2.13%   |
| Dell S2309W DELA041 1920x1080 510x290mm 23.1-inch                    | 1        | 2.13%   |
| Dell P1917S DELD091 1280x1024 380x300mm 19.1-inch                    | 1        | 2.13%   |
| Dell E2014H DELD03B 1600x900 430x240mm 19.4-inch                     | 1        | 2.13%   |
| Dell E1715S DELD062 1280x1024 340x270mm 17.1-inch                    | 1        | 2.13%   |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                    | 1        | 2.13%   |
| Ancor Communications PA248 ACI24B1 1920x1200 550x350mm 25.7-inch     | 1        | 2.13%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch | 1        | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 18       | 40%     |
| 1280x1024 (SXGA)   | 9        | 20%     |
| 1920x1200 (WUXGA)  | 5        | 11.11%  |
| 3840x2160 (4K)     | 3        | 6.67%   |
| 2560x1440 (QHD)    | 2        | 4.44%   |
| 1600x900 (HD+)     | 2        | 4.44%   |
| 1360x768           | 2        | 4.44%   |
| 1680x1050 (WSXGA+) | 1        | 2.22%   |
| 1600x1200          | 1        | 2.22%   |
| 1440x900 (WXGA+)   | 1        | 2.22%   |
| 1366x768 (WXGA)    | 1        | 2.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 9        | 19.57%  |
| 19      | 8        | 17.39%  |
| 21      | 6        | 13.04%  |
| 27      | 5        | 10.87%  |
| 17      | 5        | 10.87%  |
| Unknown | 4        | 8.7%    |
| 23      | 3        | 6.52%   |
| 18      | 2        | 4.35%   |
| 39      | 1        | 2.17%   |
| 37      | 1        | 2.17%   |
| 25      | 1        | 2.17%   |
| 22      | 1        | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 16       | 36.36%  |
| 401-500     | 12       | 27.27%  |
| 301-350     | 5        | 11.36%  |
| 351-400     | 4        | 9.09%   |
| Unknown     | 4        | 9.09%   |
| 801-900     | 2        | 4.55%   |
| 601-700     | 1        | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 25       | 56.82%  |
| 5/4     | 9        | 20.45%  |
| 16/10   | 8        | 18.18%  |
| Unknown | 2        | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 32.61%  |
| 151-200        | 8        | 17.39%  |
| 141-150        | 7        | 15.22%  |
| 301-350        | 5        | 10.87%  |
| 251-300        | 5        | 10.87%  |
| Unknown        | 4        | 8.7%    |
| 501-1000       | 2        | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 29       | 69.05%  |
| 101-120 | 7        | 16.67%  |
| Unknown | 4        | 9.52%   |
| 161-240 | 1        | 2.38%   |
| 121-160 | 1        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 38       | 70.37%  |
| 0     | 11       | 20.37%  |
| 2     | 4        | 7.41%   |
| 3     | 1        | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 27       | 36%     |
| Intel                 | 26       | 34.67%  |
| Qualcomm Atheros      | 5        | 6.67%   |
| Broadcom              | 5        | 6.67%   |
| Ralink Technology     | 3        | 4%      |
| Mellanox Technologies | 2        | 2.67%   |
| Samsung Electronics   | 1        | 1.33%   |
| Qualcomm              | 1        | 1.33%   |
| Nvidia                | 1        | 1.33%   |
| Microchip Technology  | 1        | 1.33%   |
| Edimax Technology     | 1        | 1.33%   |
| D-Link System         | 1        | 1.33%   |
| Brooktrout Technology | 1        | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 19       | 22.09%  |
| Intel Ethernet Connection (2) I219-V                                                  | 5        | 5.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 5        | 5.81%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 4        | 4.65%   |
| Intel Ethernet Connection I217-LM                                                     | 3        | 3.49%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2        | 2.33%   |
| Ralink RT2501/RT2573 Wireless Adapter                                                 | 2        | 2.33%   |
| Mellanox MT27500 Family [ConnectX-3]                                                  | 2        | 2.33%   |
| Intel I211 Gigabit Network Connection                                                 | 2        | 2.33%   |
| Intel Ethernet Controller I225-V                                                      | 2        | 2.33%   |
| Intel 82567LM-3 Gigabit Network Connection                                            | 2        | 2.33%   |
| Samsung Galaxy series, misc. (tethering mode)                                         | 1        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1        | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 1.16%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1        | 1.16%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 1.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1        | 1.16%   |
| Ralink RT5372 Wireless Adapter                                                        | 1        | 1.16%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1        | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1        | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 1.16%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 1.16%   |
| Qualcomm ALCATEL RNDIS Interface                                                      | 1        | 1.16%   |
| Nvidia MCP73 Ethernet                                                                 | 1        | 1.16%   |
| Microchip MCP2200 USB-to-Serial Port                                                  | 1        | 1.16%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 1.16%   |
| Intel Wireless 7260                                                                   | 1        | 1.16%   |
| Intel Wireless 3165                                                                   | 1        | 1.16%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 1.16%   |
| Intel NM10/ICH7 Family LAN Controller                                                 | 1        | 1.16%   |
| Intel I210 Gigabit Network Connection                                                 | 1        | 1.16%   |
| Intel Ethernet Connection (2) I218-V                                                  | 1        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 1.16%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 1.16%   |
| Intel 82579V Gigabit Network Connection                                               | 1        | 1.16%   |
| Intel 82574L Gigabit Network Connection                                               | 1        | 1.16%   |
| Intel 82567V-2 Gigabit Network Connection                                             | 1        | 1.16%   |
| Intel 82567LF-2 Gigabit Network Connection                                            | 1        | 1.16%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 28%     |
| Intel                 | 6        | 24%     |
| Qualcomm Atheros      | 4        | 16%     |
| Ralink Technology     | 3        | 12%     |
| Broadcom              | 3        | 12%     |
| Edimax Technology     | 1        | 4%      |
| D-Link System         | 1        | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2        | 8%      |
| Ralink RT2501/RT2573 Wireless Adapter                                                 | 2        | 8%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1        | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 4%      |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1        | 4%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 4%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 4%      |
| Ralink RT5372 Wireless Adapter                                                        | 1        | 4%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 4%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1        | 4%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 4%      |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 4%      |
| Intel Wireless 8265 / 8275                                                            | 1        | 4%      |
| Intel Wireless 7260                                                                   | 1        | 4%      |
| Intel Wireless 3165                                                                   | 1        | 4%      |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 4%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 4%      |
| Intel Centrino Wireless-N 105                                                         | 1        | 4%      |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                        | 1        | 4%      |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]                  | 1        | 4%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 1        | 4%      |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                          | 1        | 4%      |
| Broadcom BCM43142 802.11b/g/n                                                         | 1        | 4%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 25       | 45.45%  |
| Realtek Semiconductor | 24       | 43.64%  |
| Broadcom              | 2        | 3.64%   |
| Samsung Electronics   | 1        | 1.82%   |
| Qualcomm Atheros      | 1        | 1.82%   |
| Qualcomm              | 1        | 1.82%   |
| Nvidia                | 1        | 1.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 33.33%  |
| Intel Ethernet Connection (2) I219-V                              | 5        | 8.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5        | 8.77%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 7.02%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 5.26%   |
| Intel I211 Gigabit Network Connection                             | 2        | 3.51%   |
| Intel Ethernet Controller I225-V                                  | 2        | 3.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 3.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 1.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 1.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 1.75%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1        | 1.75%   |
| Nvidia MCP73 Ethernet                                             | 1        | 1.75%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 1.75%   |
| Intel I210 Gigabit Network Connection                             | 1        | 1.75%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 1.75%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 1.75%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 1.75%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 1.75%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 1.75%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 1.75%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 1.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 52       | 65%     |
| WiFi     | 24       | 30%     |
| Unknown  | 3        | 3.75%   |
| Modem    | 1        | 1.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 47       | 74.6%   |
| WiFi     | 14       | 22.22%  |
| Unknown  | 2        | 3.17%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 34       | 62.96%  |
| 2     | 16       | 29.63%  |
| 3     | 2        | 3.7%    |
| 4     | 1        | 1.85%   |
| 0     | 1        | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 47       | 87.04%  |
| Yes  | 7        | 12.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 35.71%  |
| Qualcomm Atheros Communications | 2        | 14.29%  |
| Cambridge Silicon Radio         | 2        | 14.29%  |
| Broadcom                        | 2        | 14.29%  |
| Realtek Semiconductor           | 1        | 7.14%   |
| ASUSTek Computer                | 1        | 7.14%   |
| Apple                           | 1        | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 3        | 21.43%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2        | 14.29%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 7.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 7.14%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)     | 1        | 7.14%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 7.14%   |
| Intel AX200 Bluetooth                               | 1        | 7.14%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1        | 7.14%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 7.14%   |
| ASUS Bluetooth Controller                           | 1        | 7.14%   |
| Apple Bluetooth Host Controller                     | 1        | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 34       | 38.2%   |
| AMD                     | 24       | 26.97%  |
| Nvidia                  | 17       | 19.1%   |
| XMOS                    | 2        | 2.25%   |
| Sony                    | 2        | 2.25%   |
| C-Media Electronics     | 2        | 2.25%   |
| Tenx Technology         | 1        | 1.12%   |
| Quanta                  | 1        | 1.12%   |
| LG Electronics          | 1        | 1.12%   |
| Creative Technology     | 1        | 1.12%   |
| Creative Labs           | 1        | 1.12%   |
| Corsair                 | 1        | 1.12%   |
| BEHRINGER International | 1        | 1.12%   |
| Audio-Technica          | 1        | 1.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5        | 4.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 4.63%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 3.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 3.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 3.7%    |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 3.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 4        | 3.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 2.78%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3        | 2.78%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 2.78%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 2.78%   |
| AMD Kabini HDMI/DP Audio                                                   | 3        | 2.78%   |
| AMD FCH Azalia Controller                                                  | 3        | 2.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 2.78%   |
| Nvidia MCP61 High Definition Audio                                         | 2        | 1.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 1.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 1.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 1.85%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2        | 1.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2        | 1.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 1.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 1.85%   |
| XMOS XS1-U8 MFA (ST)                                                       | 1        | 0.93%   |
| XMOS Shanling UA2                                                          | 1        | 0.93%   |
| Tenx Technology USB  AUDIO                                                 | 1        | 0.93%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 0.93%   |
| Sony Audio                                                                 | 1        | 0.93%   |
| Quanta USB Audio Realtek USB2.0 Audio Microphone                           | 1        | 0.93%   |
| Nvidia MCP73 High Definition Audio                                         | 1        | 0.93%   |
| Nvidia High Definition Audio Controller                                    | 1        | 0.93%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 0.93%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 0.93%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 1        | 0.93%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 0.93%   |
| LG Electronics USB Audio LG UltraFine Display Audio                        | 1        | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 10       | 16.67%  |
| Samsung Electronics | 8        | 13.33%  |
| Unknown             | 7        | 11.67%  |
| SK hynix            | 6        | 10%     |
| Micron Technology   | 6        | 10%     |
| G.Skill             | 6        | 10%     |
| Corsair             | 6        | 10%     |
| Elpida              | 3        | 5%      |
| Crucial             | 3        | 5%      |
| Nanya Technology    | 2        | 3.33%   |
| Transcend           | 1        | 1.67%   |
| EVGA                | 1        | 1.67%   |
| Unknown             | 1        | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 2        | 3.13%   |
| Micron RAM ITC 4GB DIMM DDR3 1066MT/s                  | 2        | 3.13%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 3.13%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s    | 2        | 3.13%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 1.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1        | 1.56%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 1        | 1.56%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s            | 1        | 1.56%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s            | 1        | 1.56%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s      | 1        | 1.56%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s      | 1        | 1.56%   |
| SK hynix RAM Zhidian4GDDR800000 4GB DIMM DDR2 800MT/s  | 1        | 1.56%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.56%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.56%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM 1600MT/s        | 1        | 1.56%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s   | 1        | 1.56%   |
| SK hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s   | 1        | 1.56%   |
| SK hynix RAM HMT125U6AFP8C-G7 2GB DIMM DDR3 1066MT/s   | 1        | 1.56%   |
| SK hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s        | 1        | 1.56%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s  | 1        | 1.56%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s  | 1        | 1.56%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s  | 1        | 1.56%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1        | 1.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s  | 1        | 1.56%   |
| Samsung RAM M391B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s    | 1        | 1.56%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 1.56%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s    | 1        | 1.56%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s     | 1        | 1.56%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 800MT/s   | 1        | 1.56%   |
| Micron RAM 8HTF12864AZ-800H1 1GB DIMM DDR2 800MT/s     | 1        | 1.56%   |
| Micron RAM 36JSZF1G72PZ-1G4D 8GB DIMM DDR3 1333MT/s    | 1        | 1.56%   |
| Micron RAM 36JSF1G72PZ-1 8GB DIMM DDR3 1600MT/s        | 1        | 1.56%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s   | 1        | 1.56%   |
| Kingston RAM KY996D-ELD 2GB DIMM 1066MT/s              | 1        | 1.56%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s      | 1        | 1.56%   |
| Kingston RAM KHX2400C15D4/8G 8192MB DIMM DDR4 2400MT/s | 1        | 1.56%   |
| Kingston RAM KF3600C17D4/8GX 8GB DIMM DDR4 3600MT/s    | 1        | 1.56%   |
| Kingston RAM K531R8-ETB 4GB DIMM DDR3 1600MT/s         | 1        | 1.56%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s | 1        | 1.56%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s | 1        | 1.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 25       | 43.86%  |
| DDR4    | 19       | 33.33%  |
| DDR2    | 9        | 15.79%  |
| Unknown | 2        | 3.51%   |
| SDRAM   | 1        | 1.75%   |
| DDR     | 1        | 1.75%   |

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
| 8192  | 24       | 40%     |
| 4096  | 14       | 23.33%  |
| 2048  | 12       | 20%     |
| 16384 | 5        | 8.33%   |
| 1024  | 5        | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 14       | 24.56%  |
| 1333    | 8        | 14.04%  |
| 3200    | 7        | 12.28%  |
| 2400    | 6        | 10.53%  |
| 800     | 6        | 10.53%  |
| 1066    | 4        | 7.02%   |
| 3600    | 3        | 5.26%   |
| 2667    | 2        | 3.51%   |
| 533     | 2        | 3.51%   |
| 3000    | 1        | 1.75%   |
| 2933    | 1        | 1.75%   |
| 1866    | 1        | 1.75%   |
| 667     | 1        | 1.75%   |
| Unknown | 1        | 1.75%   |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 3        | 60%     |
| Quanta                   | 1        | 20%     |
| Novatek Microelectronics | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Quanta Realtek DMFT RGB               | 1        | 20%     |
| Novatek HP High Definition 2MP Webcam | 1        | 20%     |
| Logitech Webcam C310                  | 1        | 20%     |
| Logitech Webcam C270                  | 1        | 20%     |
| Logitech C505 HD Webcam               | 1        | 20%     |

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
| 1     | 25       | 46.3%   |
| 2     | 13       | 24.07%  |
| 0     | 13       | 24.07%  |
| 3     | 2        | 3.7%    |
| 7     | 1        | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 28       | 46.67%  |
| Firewire controller      | 14       | 23.33%  |
| Net/wireless             | 8        | 13.33%  |
| Network                  | 4        | 6.67%   |
| Sound                    | 3        | 5%      |
| Bluetooth                | 3        | 5%      |

