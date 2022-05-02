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

Total: 57

| Vendor   | Model                       | Probe                                                     | Date         |
|----------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek  | Maximus VIII HERO           | [c776760a11](https://bsd-hardware.info/?probe=c776760a11) | Apr 13, 2022 |
| MSI      | U-100 Ver.001               | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| Gigabyte | X570S GAMING X              | [ff39ace6ec](https://bsd-hardware.info/?probe=ff39ace6ec) | Feb 16, 2022 |
| Intel    | DCP847SKE                   | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
| Dell     | 0M9KCM A01                  | [4db0a0ea05](https://bsd-hardware.info/?probe=4db0a0ea05) | Dec 06, 2021 |
| Gigabyte | MZGLKBP-00                  | [e713e3adee](https://bsd-hardware.info/?probe=e713e3adee) | Dec 05, 2021 |
| ASUSTek  | PRIME Z390-P                | [1bd9270845](https://bsd-hardware.info/?probe=1bd9270845) | Nov 15, 2021 |
| Dell     | 0T10XW A01                  | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| Unknown  | X79                         | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| HP       | 87D6 SMVB                   | [f601f00e7c](https://bsd-hardware.info/?probe=f601f00e7c) | Oct 07, 2021 |
| Dell     | OptiPlex 3020               | [c391177240](https://bsd-hardware.info/?probe=c391177240) | Oct 05, 2021 |
| Dell     | OptiPlex 3020               | [070a0c6d62](https://bsd-hardware.info/?probe=070a0c6d62) | Sep 19, 2021 |
| Gigabyte | Z370 AORUS ULTRAGAMING W... | [13371b2ab8](https://bsd-hardware.info/?probe=13371b2ab8) | Jun 27, 2021 |
| ASUSTek  | ROG STRIX X299-E GAMING     | [e91dc55970](https://bsd-hardware.info/?probe=e91dc55970) | Jun 22, 2021 |
| ASRock   | N68C-GS4 FX                 | [5abce24217](https://bsd-hardware.info/?probe=5abce24217) | Jun 06, 2021 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [c6a1c1fa15](https://bsd-hardware.info/?probe=c6a1c1fa15) | May 25, 2021 |
| ASUSTek  | V-P7H55E                    | [8cf113ac55](https://bsd-hardware.info/?probe=8cf113ac55) | May 22, 2021 |
| Toshiba  | STI 005492G                 | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |
| ECT      | One Computer AMD A10-785... | [41a2a2e434](https://bsd-hardware.info/?probe=41a2a2e434) | Apr 07, 2021 |
| Acer     | EG43M                       | [0bc978756c](https://bsd-hardware.info/?probe=0bc978756c) | Mar 27, 2021 |
| Dell     | 0NW6H5 A00                  | [650cd9b653](https://bsd-hardware.info/?probe=650cd9b653) | Mar 24, 2021 |
| Acer     | EG31M R01-C3                | [1186d46ac9](https://bsd-hardware.info/?probe=1186d46ac9) | Mar 08, 2021 |
| HP       | 158A                        | [da9d6bf86f](https://bsd-hardware.info/?probe=da9d6bf86f) | Mar 07, 2021 |
| Dell     | 0R849J A00                  | [1bd1dc24c9](https://bsd-hardware.info/?probe=1bd1dc24c9) | Mar 06, 2021 |
| ASRock   | Z490M Pro4                  | [348d592fab](https://bsd-hardware.info/?probe=348d592fab) | Mar 05, 2021 |
| VeryPC   | S400                        | [edcea11cb7](https://bsd-hardware.info/?probe=edcea11cb7) | Mar 04, 2021 |
| Acer     | EG31M R01-C3                | [046404e65c](https://bsd-hardware.info/?probe=046404e65c) | Mar 01, 2021 |
| Dell     | 0T568R A00                  | [cd086a9092](https://bsd-hardware.info/?probe=cd086a9092) | Feb 12, 2021 |
| ASRock   | B550 Phantom Gaming 4       | [2d0beb2534](https://bsd-hardware.info/?probe=2d0beb2534) | Feb 08, 2021 |
| Lenovo   | SHARKBAY 0B98401 WIN        | [2917a6fbe1](https://bsd-hardware.info/?probe=2917a6fbe1) | Jan 31, 2021 |
| HP       | 0AACh                       | [b7cac343f6](https://bsd-hardware.info/?probe=b7cac343f6) | Jan 29, 2021 |
| HP       | 3399                        | [b11946a41a](https://bsd-hardware.info/?probe=b11946a41a) | Jan 13, 2021 |
| Pegatron | 2AB5                        | [8093f75ea2](https://bsd-hardware.info/?probe=8093f75ea2) | Jan 13, 2021 |
| Dell     | 0NW6H5 A00                  | [d54f451ea5](https://bsd-hardware.info/?probe=d54f451ea5) | Jan 07, 2021 |
| HP       | 3032h                       | [13648fd22d](https://bsd-hardware.info/?probe=13648fd22d) | Jan 07, 2021 |
| Dell     | 0KC9NP A01                  | [ee2d5f3289](https://bsd-hardware.info/?probe=ee2d5f3289) | Jan 07, 2021 |
| Dell     | 030VXY A01                  | [c117ffdc98](https://bsd-hardware.info/?probe=c117ffdc98) | Jan 07, 2021 |
| Gigabyte | X570 AORUS MASTER           | [cfc292e9e8](https://bsd-hardware.info/?probe=cfc292e9e8) | Jan 07, 2021 |
| Dell     | 0C27VV A02                  | [cfd6a0ab4b](https://bsd-hardware.info/?probe=cfd6a0ab4b) | Jan 04, 2021 |
| Dell     | 0C27VV A02                  | [c532e18070](https://bsd-hardware.info/?probe=c532e18070) | Jan 04, 2021 |
| Dell     | 0C27VV A02                  | [876f5d7b92](https://bsd-hardware.info/?probe=876f5d7b92) | Jan 02, 2021 |
| Dell     | 0C27VV A02                  | [0bf1fa2725](https://bsd-hardware.info/?probe=0bf1fa2725) | Jan 02, 2021 |
| Dell     | 0C27VV A02                  | [87e4734cb8](https://bsd-hardware.info/?probe=87e4734cb8) | Dec 30, 2020 |
| Dell     | 0C27VV A02                  | [d892bd7805](https://bsd-hardware.info/?probe=d892bd7805) | Dec 30, 2020 |
| Dell     | 0C27VV A02                  | [917e6fde25](https://bsd-hardware.info/?probe=917e6fde25) | Dec 30, 2020 |
| Dell     | 0C27VV A02                  | [889bba9dbc](https://bsd-hardware.info/?probe=889bba9dbc) | Dec 30, 2020 |
| Gigabyte | X570 AORUS PRO              | [a3e2c4eda1](https://bsd-hardware.info/?probe=a3e2c4eda1) | Dec 30, 2020 |
| ASUSTek  | Z170-A                      | [a1c6966373](https://bsd-hardware.info/?probe=a1c6966373) | Oct 21, 2020 |
| ASRock   | AB350 Pro4                  | [407652fc8d](https://bsd-hardware.info/?probe=407652fc8d) | Oct 05, 2020 |
| Foxconn  | Napa HP P/N                 | [2a7cb7b214](https://bsd-hardware.info/?probe=2a7cb7b214) | Sep 03, 2020 |
| ASUSTek  | EMERY                       | [c93b86b3ba](https://bsd-hardware.info/?probe=c93b86b3ba) | Aug 27, 2020 |
| HP       | 0A64h                       | [10c48336b0](https://bsd-hardware.info/?probe=10c48336b0) | Aug 20, 2020 |
| ASUSTek  | M5A97 R2.0                  | [78d714a1a3](https://bsd-hardware.info/?probe=78d714a1a3) | Aug 19, 2020 |
| ASUSTek  | PRIME A320M-K               | [8a3cb911c3](https://bsd-hardware.info/?probe=8a3cb911c3) | Jul 18, 2020 |
| Gigabyte | Z370 AORUS Ultra Gaming-... | [a03e1c19c1](https://bsd-hardware.info/?probe=a03e1c19c1) | Jul 04, 2020 |
| ASRock   | Z97 Extreme6/ac             | [9c2d19d0c3](https://bsd-hardware.info/?probe=9c2d19d0c3) | Jul 03, 2020 |
| ASRock   | B450M Pro4                  | [aa58b291b3](https://bsd-hardware.info/?probe=aa58b291b3) | May 24, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| NomadBSD 5806f915 | 15       | 37.5%   |
| NomadBSD 1.3.2    | 14       | 35%     |
| NomadBSD 1.4-RC1  | 4        | 10%     |
| NomadBSD 1.4      | 3        | 7.5%    |
| NomadBSD 1.3.1    | 2        | 5%      |
| NomadBSD 1.3      | 1        | 2.5%    |
| NomadBSD 1.0      | 1        | 2.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| NomadBSD | 40       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 39       | 97.5%   |
| i386  | 1        | 2.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Openbox | 36       | 87.8%   |
| KDE5    | 2        | 4.88%   |
| GNUstep | 1        | 2.44%   |
| GNOME   | 1        | 2.44%   |
| filer   | 1        | 2.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 40       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 38       | 95%     |
| SDDM | 2        | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 14       | 35%     |
| Unknown | 9        | 22.5%   |
| de_DE   | 3        | 7.5%    |
| tr_TR   | 2        | 5%      |
| ru_RU   | 2        | 5%      |
| pt_BR   | 2        | 5%      |
| it_IT   | 2        | 5%      |
| hu_HU   | 2        | 5%      |
| fi_FI   | 1        | 2.5%    |
| es_ES   | 1        | 2.5%    |
| en_AU   | 1        | 2.5%    |
| cs_CZ   | 1        | 2.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 39       | 97.5%   |
| BIOS | 1        | 2.5%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ufs  | 34       | 85%     |
| Zfs  | 6        | 15%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 30       | 75%     |
| MBR  | 10       | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 22.5%   |
| Hewlett-Packard     | 6        | 15%     |
| Gigabyte Technology | 6        | 15%     |
| Dell                | 6        | 15%     |
| ASRock              | 4        | 10%     |
| Acer                | 3        | 7.5%    |
| Semp Toshiba        | 1        | 2.5%    |
| Pegatron            | 1        | 2.5%    |
| Lenovo              | 1        | 2.5%    |
| Intel               | 1        | 2.5%    |
| Foxconn             | 1        | 2.5%    |
| Unknown             | 1        | 2.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Acer Veriton M460                        | 2        | 5%      |
| Semp Toshiba STI                         | 1        | 2.5%    |
| Pegatron Elite 7300 Series MT            | 1        | 2.5%    |
| Lenovo ThinkCentre M93p 10A8001HUS       | 1        | 2.5%    |
| Intel DCP847SKE                          | 1        | 2.5%    |
| HP Z620 Workstation                      | 1        | 2.5%    |
| HP Desktop M01-F1xxx                     | 1        | 2.5%    |
| HP Compaq Elite 8300 Touch All-in-One PC | 1        | 2.5%    |
| HP Compaq dc7900 Convertible Minitower   | 1        | 2.5%    |
| HP Compaq dc7800p Convertible Minitower  | 1        | 2.5%    |
| HP Compaq dc5750 Microtower              | 1        | 2.5%    |
| Gigabyte Z370 AORUS ULTRAGAMING WIFI-OP  | 1        | 2.5%    |
| Gigabyte Z370 AORUS Ultra Gaming         | 1        | 2.5%    |
| Gigabyte X570S GAMING X                  | 1        | 2.5%    |
| Gigabyte X570 AORUS PRO                  | 1        | 2.5%    |
| Gigabyte X570 AORUS MASTER               | 1        | 2.5%    |
| Gigabyte MZGLKBP-00                      | 1        | 2.5%    |
| Foxconn Napa                             | 1        | 2.5%    |
| Dell Studio XPS 8100                     | 1        | 2.5%    |
| Dell Studio XPS 435MT                    | 1        | 2.5%    |
| Dell OptiPlex 9010                       | 1        | 2.5%    |
| Dell OptiPlex 780                        | 1        | 2.5%    |
| Dell OptiPlex 3020                       | 1        | 2.5%    |
| Dell OptiPlex 3010                       | 1        | 2.5%    |
| ASUS Z170-A                              | 1        | 2.5%    |
| ASUS V-P7H55E                            | 1        | 2.5%    |
| ASUS TUF GAMING B550M-PLUS               | 1        | 2.5%    |
| ASUS ROG STRIX X299-E GAMING             | 1        | 2.5%    |
| ASUS PRIME Z390-P                        | 1        | 2.5%    |
| ASUS PRIME A320M-K                       | 1        | 2.5%    |
| ASUS Maximus VIII HERO                   | 1        | 2.5%    |
| ASUS M5A97 R2.0                          | 1        | 2.5%    |
| ASUS ER904AA-ABA A1440N                  | 1        | 2.5%    |
| ASRock Z97 Extreme6/ac                   | 1        | 2.5%    |
| ASRock N68C-GS4 FX                       | 1        | 2.5%    |
| ASRock B450M Pro4                        | 1        | 2.5%    |
| ASRock AB350 Pro4                        | 1        | 2.5%    |
| Acer Aspire M3900                        | 1        | 2.5%    |
| Unknown                                  | 1        | 2.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP Compaq           | 4        | 10%     |
| Dell OptiPlex       | 4        | 10%     |
| Gigabyte Z370       | 2        | 5%      |
| Gigabyte X570       | 2        | 5%      |
| Dell Studio         | 2        | 5%      |
| ASUS PRIME          | 2        | 5%      |
| Acer Veriton        | 2        | 5%      |
| Semp Toshiba STI    | 1        | 2.5%    |
| Pegatron Elite      | 1        | 2.5%    |
| Lenovo ThinkCentre  | 1        | 2.5%    |
| Intel DCP847SKE     | 1        | 2.5%    |
| HP Z620             | 1        | 2.5%    |
| HP Desktop          | 1        | 2.5%    |
| Gigabyte X570S      | 1        | 2.5%    |
| Gigabyte MZGLKBP-00 | 1        | 2.5%    |
| Foxconn Napa        | 1        | 2.5%    |
| ASUS Z170-A         | 1        | 2.5%    |
| ASUS V-P7H55E       | 1        | 2.5%    |
| ASUS TUF            | 1        | 2.5%    |
| ASUS ROG            | 1        | 2.5%    |
| ASUS Maximus        | 1        | 2.5%    |
| ASUS M5A97          | 1        | 2.5%    |
| ASUS ER904AA-ABA    | 1        | 2.5%    |
| ASRock Z97          | 1        | 2.5%    |
| ASRock N68C-GS4     | 1        | 2.5%    |
| ASRock B450M        | 1        | 2.5%    |
| ASRock AB350        | 1        | 2.5%    |
| Acer Aspire         | 1        | 2.5%    |
| Unknown             | 1        | 2.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 6        | 15%     |
| 2019 | 5        | 12.5%   |
| 2021 | 3        | 7.5%    |
| 2020 | 3        | 7.5%    |
| 2018 | 3        | 7.5%    |
| 2017 | 3        | 7.5%    |
| 2015 | 3        | 7.5%    |
| 2010 | 3        | 7.5%    |
| 2016 | 2        | 5%      |
| 2013 | 2        | 5%      |
| 2012 | 2        | 5%      |
| 2014 | 1        | 2.5%    |
| 2011 | 1        | 2.5%    |
| 2008 | 1        | 2.5%    |
| 2007 | 1        | 2.5%    |
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


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 11       | 27.5%   |
| 4.01-8.0    | 10       | 25%     |
| 16.01-24.0  | 9        | 22.5%   |
| 32.01-64.0  | 6        | 15%     |
| 64.01-256.0 | 2        | 5%      |
| 3.01-4.0    | 1        | 2.5%    |
| 2.01-3.0    | 1        | 2.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 21       | 52.5%   |
| 0.51-1.0 | 10       | 25%     |
| 1.01-2.0 | 7        | 17.5%   |
| 2.01-3.0 | 2        | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 42.5%   |
| 2      | 11       | 27.5%   |
| 3      | 8        | 20%     |
| 4      | 2        | 5%      |
| 7      | 1        | 2.5%    |
| 0      | 1        | 2.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 22       | 55%     |
| No        | 18       | 45%     |

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
| No        | 30       | 73.17%  |
| Yes       | 11       | 26.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 13       | 32.5%   |
| Germany   | 4        | 10%     |
| Turkey    | 3        | 7.5%    |
| Russia    | 3        | 7.5%    |
| France    | 3        | 7.5%    |
| Italy     | 2        | 5%      |
| Hungary   | 2        | 5%      |
| Brazil    | 2        | 5%      |
| Thailand  | 1        | 2.5%    |
| Slovakia  | 1        | 2.5%    |
| Serbia    | 1        | 2.5%    |
| Finland   | 1        | 2.5%    |
| Czechia   | 1        | 2.5%    |
| Colombia  | 1        | 2.5%    |
| Australia | 1        | 2.5%    |
| Argentina | 1        | 2.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Paris            | 3        | 7.5%    |
| Woodland         | 2        | 5%      |
| Volzhskiy        | 2        | 5%      |
| Rio de Janeiro   | 2        | 5%      |
| Milan            | 2        | 5%      |
| Istanbul         | 2        | 5%      |
| Hodmezovasarhely | 2        | 5%      |
| Tucson           | 1        | 2.5%    |
| Scottsdale       | 1        | 2.5%    |
| San Francisco    | 1        | 2.5%    |
| Peoria           | 1        | 2.5%    |
| Palm Bay         | 1        | 2.5%    |
| Moscow           | 1        | 2.5%    |
| Melcice          | 1        | 2.5%    |
| McDonough        | 1        | 2.5%    |
| Marburg          | 1        | 2.5%    |
| Langen           | 1        | 2.5%    |
| Helsinki         | 1        | 2.5%    |
| Frisco           | 1        | 2.5%    |
| Duncan           | 1        | 2.5%    |
| Dortmund         | 1        | 2.5%    |
| Denver           | 1        | 2.5%    |
| CГіrdoba       | 1        | 2.5%    |
| Conway           | 1        | 2.5%    |
| Cologne          | 1        | 2.5%    |
| Cleveland        | 1        | 2.5%    |
| Brisbane         | 1        | 2.5%    |
| BogotГЎ        | 1        | 2.5%    |
| Bilina           | 1        | 2.5%    |
| Belgrade         | 1        | 2.5%    |
| Bangkok          | 1        | 2.5%    |
| BalД±kesir     | 1        | 2.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 18     | 18.84%  |
| Samsung Electronics | 13       | 16     | 18.84%  |
| Seagate             | 12       | 13     | 17.39%  |
| Toshiba             | 6        | 7      | 8.7%    |
| A-DATA Technology   | 5        | 5      | 7.25%   |
| Kingston            | 4        | 4      | 5.8%    |
| Crucial             | 3        | 3      | 4.35%   |
| Intel               | 2        | 2      | 2.9%    |
| Hitachi             | 2        | 2      | 2.9%    |
| Hewlett-Packard     | 2        | 2      | 2.9%    |
| Transcend           | 1        | 1      | 1.45%   |
| Team                | 1        | 1      | 1.45%   |
| SK Hynix            | 1        | 1      | 1.45%   |
| SanDisk             | 1        | 2      | 1.45%   |
| ORICO               | 1        | 1      | 1.45%   |
| MAXTOR              | 1        | 1      | 1.45%   |
| HGST                | 1        | 1      | 1.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| WDC WD1600AAJS-22L7A0 160GB               | 2        | 2.6%    |
| Toshiba HDWD120 2TB                       | 2        | 2.6%    |
| Seagate ST500DM002-1BD142 500GB           | 2        | 2.6%    |
| Samsung SSD 970 EVO 500GB                 | 2        | 2.6%    |
| Samsung SSD 870 QVO 2TB                   | 2        | 2.6%    |
| Kingston SA400S37480G 480GB               | 2        | 2.6%    |
| A-DATA SU630 240GB                        | 2        | 2.6%    |
| WDC WDS240G2G0B-00EPW0 240GB              | 1        | 1.3%    |
| WDC WDS120G2G0A-00JH30 120GB              | 1        | 1.3%    |
| WDC WDS100T1X0E-00AFY0 1TB                | 1        | 1.3%    |
| WDC WD6400AAKS-22A7B2 640GB               | 1        | 1.3%    |
| WDC WD40PURX-64GVNY0 4TB                  | 1        | 1.3%    |
| WDC WD40NMZW-11GX6S1 4TB                  | 1        | 1.3%    |
| WDC WD2500BEKT-00PVMT0 250GB              | 1        | 1.3%    |
| WDC WD2004FBYZ-01YCBB1 2TB                | 1        | 1.3%    |
| WDC WD1200BEVE-00UYT0 120GB               | 1        | 1.3%    |
| WDC WD10JPLX-00MBPT0 1TB                  | 1        | 1.3%    |
| WDC WD10EZRZ-00HTKB0 1TB                  | 1        | 1.3%    |
| WDC WD10EZRX-00L4HB0 1TB                  | 1        | 1.3%    |
| WDC WD10EFRX-68PJCN0 1TB                  | 1        | 1.3%    |
| WDC WD10EADS-00P8B0 1TB                   | 1        | 1.3%    |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1        | 1.3%    |
| Transcend TS32GCF800 32GB                 | 1        | 1.3%    |
| Toshiba MK1032GAX 100GB                   | 1        | 1.3%    |
| Toshiba HDWD130 3TB                       | 1        | 1.3%    |
| Toshiba HDWD110 1TB                       | 1        | 1.3%    |
| Toshiba DT01ACA100 1TB                    | 1        | 1.3%    |
| Toshiba DT01ABA300 3TB                    | 1        | 1.3%    |
| Team TEAML5Lite3D1T 1TB                   | 1        | 1.3%    |
| SK Hynix SKHynix_HFS256GD9TNI-L2B0B 256GB | 1        | 1.3%    |
| Seagate ST9500325AS 500GB                 | 1        | 1.3%    |
| Seagate ST4000DM000-2AE166 4TB            | 1        | 1.3%    |
| Seagate ST3500418AS 500GB                 | 1        | 1.3%    |
| Seagate ST3250823AS 250GB                 | 1        | 1.3%    |
| Seagate ST3250310AS 250GB                 | 1        | 1.3%    |
| Seagate ST31000528AS 1TB                  | 1        | 1.3%    |
| Seagate ST3000DM008-2DM166 3TB            | 1        | 1.3%    |
| Seagate ST1000LX015-1U7172 1TB            | 1        | 1.3%    |
| Seagate ST1000LM049-2GH172 1TB            | 1        | 1.3%    |
| Seagate ST1000DM003-1CH162 1TB            | 1        | 1.3%    |
| SanDisk SSD PLUS 120GB                    | 1        | 1.3%    |
| Samsung SSD 970 EVO Plus 1TB              | 1        | 1.3%    |
| Samsung SSD 970 EVO 2TB                   | 1        | 1.3%    |
| Samsung SSD 960 EVO 1TB                   | 1        | 1.3%    |
| Samsung SSD 870 EVO 1TB                   | 1        | 1.3%    |
| Samsung SSD 860 EVO 1TB                   | 1        | 1.3%    |
| Samsung SSD 850 EVO M.2 500GB             | 1        | 1.3%    |
| Samsung SSD 850 EVO 500GB                 | 1        | 1.3%    |
| Samsung SSD 840 EVO 250GB                 | 1        | 1.3%    |
| Samsung SP2504C 250GB                     | 1        | 1.3%    |
| Samsung HM160HI 160GB                     | 1        | 1.3%    |
| Samsung HD161HJ 160GB                     | 1        | 1.3%    |
| Samsung HD161GJ 160GB                     | 1        | 1.3%    |
| ORICO V500 1TB                            | 1        | 1.3%    |
| MAXTOR STM3250310AS 250GB                 | 1        | 1.3%    |
| Kingston SA400S37240G 240GB               | 1        | 1.3%    |
| Kingston SA2000M8500G 500GB               | 1        | 1.3%    |
| Intel SSDPEKNW020T8 2TB                   | 1        | 1.3%    |
| Intel MEMPEK1W032GA 32GB                  | 1        | 1.3%    |
| Hitachi HDS721032CLA362 320GB             | 1        | 1.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 12       | 13     | 31.58%  |
| WDC                 | 11       | 14     | 28.95%  |
| Toshiba             | 6        | 7      | 15.79%  |
| Samsung Electronics | 4        | 4      | 10.53%  |
| Hitachi             | 2        | 2      | 5.26%   |
| MAXTOR              | 1        | 1      | 2.63%   |
| HGST                | 1        | 1      | 2.63%   |
| Hewlett-Packard     | 1        | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 7      | 26.32%  |
| A-DATA Technology   | 5        | 5      | 26.32%  |
| Kingston            | 3        | 3      | 15.79%  |
| WDC                 | 2        | 2      | 10.53%  |
| Transcend           | 1        | 1      | 5.26%   |
| Team                | 1        | 1      | 5.26%   |
| SanDisk             | 1        | 2      | 5.26%   |
| Crucial             | 1        | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 43     | 50.91%  |
| SSD  | 15       | 22     | 27.27%  |
| NVMe | 12       | 15     | 21.82%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 36       | 65     | 75%     |
| NVMe | 12       | 15     | 25%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 26       | 36     | 50%     |
| 0.51-1.0   | 15       | 18     | 28.85%  |
| 1.01-2.0   | 5        | 5      | 9.62%   |
| 3.01-4.0   | 3        | 3      | 5.77%   |
| 2.01-3.0   | 3        | 3      | 5.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 32       | 80%     |
| 101-250    | 5        | 12.5%   |
| 51-100     | 2        | 5%      |
| 501-1000   | 1        | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 38       | 95%     |
| 21-50   | 1        | 2.5%    |
| 51-100  | 1        | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD10EFRX-68PJCN0 1TB          | 1        | 2      | 12.5%   |
| Toshiba HDWD120 2TB               | 1        | 1      | 12.5%   |
| Toshiba DT01ABA300 3TB            | 1        | 1      | 12.5%   |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 12.5%   |
| Seagate ST3250823AS 250GB         | 1        | 1      | 12.5%   |
| Samsung Electronics HM160HI 160GB | 1        | 1      | 12.5%   |
| Hewlett-Packard MB1000GCWCV 1TB   | 1        | 1      | 12.5%   |
| A-DATA Technology XM13 32GB       | 1        | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 2        | 2      | 25%     |
| Seagate             | 2        | 2      | 25%     |
| WDC                 | 1        | 2      | 12.5%   |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Hewlett-Packard     | 1        | 1      | 12.5%   |
| A-DATA Technology   | 1        | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 2        | 2      | 28.57%  |
| Seagate             | 2        | 2      | 28.57%  |
| WDC                 | 1        | 2      | 14.29%  |
| Samsung Electronics | 1        | 1      | 14.29%  |
| Hewlett-Packard     | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 8      | 85.71%  |
| SSD  | 1        | 1      | 14.29%  |

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
| Works    | 35       | 65     | 81.4%   |
| Malfunc  | 7        | 9      | 16.28%  |
| Detected | 1        | 6      | 2.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 29       | 49.15%  |
| AMD                         | 10       | 16.95%  |
| Samsung Electronics         | 5        | 8.47%   |
| ASMedia Technology          | 5        | 8.47%   |
| Sandisk                     | 2        | 3.39%   |
| Nvidia                      | 2        | 3.39%   |
| Micron/Crucial Technology   | 2        | 3.39%   |
| VIA Technologies            | 1        | 1.69%   |
| Silicon Motion              | 1        | 1.69%   |
| Kingston Technology Company | 1        | 1.69%   |
| Biwin Storage Technology    | 1        | 1.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 8.97%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 6.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 5.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 3.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 3.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 3.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 3.85%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 2.56%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2        | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 2.56%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 2.56%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 2.56%   |
| Unknown                                                                        | 2        | 2.56%   |
| VIA VT6421 IDE/SATA Controller                                                 | 1        | 1.28%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 1.28%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 1.28%   |
| Sandisk PC SN520 NVMe SSD                                                      | 1        | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 1.28%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                        | 1        | 1.28%   |
| Nvidia MCP73 IDE Controller                                                    | 1        | 1.28%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.28%   |
| Nvidia MCP61 IDE                                                               | 1        | 1.28%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1        | 1.28%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 1.28%   |
| Intel SSD 660P Series                                                          | 1        | 1.28%   |
| Intel NVMe Optane Memory Series                                                | 1        | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.28%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1        | 1.28%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 1        | 1.28%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 1        | 1.28%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                       | 1        | 1.28%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 1.28%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 1.28%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 1.28%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 1.28%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 1        | 1.28%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 1        | 1.28%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                   | 1        | 1.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1        | 1.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1        | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1        | 1.28%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 1        | 1.28%   |
| AMD SB600 IDE                                                                  | 1        | 1.28%   |
| AMD FCH SATA Controller D                                                      | 1        | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 1.28%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 1.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 29       | 50%     |
| NVMe | 12       | 20.69%  |
| IDE  | 12       | 20.69%  |
| RAID | 4        | 6.9%    |
| SAS  | 1        | 1.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 29       | 72.5%   |
| AMD    | 11       | 27.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 5%      |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 5%      |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 5%      |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 2.5%    |
| Intel Xeon CPU E5-2670 @ 2.60GHz            | 1        | 2.5%    |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 2.5%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 2.5%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 2.5%    |
| Intel Pentium D CPU 2.80GHz                 | 1        | 2.5%    |
| Intel Core i9-7960X CPU @ 2.80GHz           | 1        | 2.5%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 2.5%    |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 2.5%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 2.5%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 2.5%    |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 2.5%    |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 2.5%    |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 2.5%    |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 2.5%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 2.5%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 2.5%    |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 2.5%    |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 2.5%    |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 2.5%    |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 2.5%    |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 2.5%    |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz        | 1        | 2.5%    |
| Intel Core 2 Duo                            | 1        | 2.5%    |
| Intel Celeron CPU 847E @ 1.10GHz            | 1        | 2.5%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 2.5%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 2.5%    |
| AMD Ryzen 5 4600G with Radeon Graphics      | 1        | 2.5%    |
| AMD Ryzen 5 3600XT 6-Core Processor         | 1        | 2.5%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 1        | 2.5%    |
| AMD Ryzen 5 1500X Quad-Core Processor       | 1        | 2.5%    |
| AMD FX-6300 Six-Core Processor              | 1        | 2.5%    |
| AMD Athlon 64 X2 Dual Core Processor 5600+  | 1        | 2.5%    |
| AMD Athlon 64 X2 Dual Core Processor 4000+  | 1        | 2.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 7        | 17.5%   |
| Intel Core i5           | 7        | 17.5%   |
| Intel Core 2 Duo        | 6        | 15%     |
| AMD Ryzen 5             | 6        | 15%     |
| Intel Xeon              | 2        | 5%      |
| Intel Pentium Dual-Core | 2        | 5%      |
| AMD Athlon 64 X2        | 2        | 5%      |
| Intel Pentium Silver    | 1        | 2.5%    |
| Intel Pentium D         | 1        | 2.5%    |
| Intel Core i9           | 1        | 2.5%    |
| Intel Core i3           | 1        | 2.5%    |
| Intel Celeron           | 1        | 2.5%    |
| AMD Ryzen 9             | 1        | 2.5%    |
| AMD Ryzen 7             | 1        | 2.5%    |
| AMD FX                  | 1        | 2.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 12       | 30%     |
| 2       | 12       | 30%     |
| 8       | 6        | 15%     |
| 12      | 3        | 7.5%    |
| 6       | 3        | 7.5%    |
| 16      | 2        | 5%      |
| 24      | 1        | 2.5%    |
| Unknown | 1        | 2.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 39       | 97.5%   |
| 2      | 1        | 2.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 29       | 72.5%   |
| 2       | 10       | 25%     |
| Unknown | 1        | 2.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 8        | 20%     |
| SandyBridge   | 4        | 10%     |
| KabyLake      | 4        | 10%     |
| Zen           | 3        | 7.5%    |
| Nehalem       | 3        | 7.5%    |
| IvyBridge     | 3        | 7.5%    |
| Haswell       | 3        | 7.5%    |
| Zen+          | 2        | 5%      |
| Zen 2         | 2        | 5%      |
| Skylake       | 2        | 5%      |
| K8 Hammer     | 2        | 5%      |
| Zen 3         | 1        | 2.5%    |
| Piledriver    | 1        | 2.5%    |
| NetBurst      | 1        | 2.5%    |
| Goldmont plus | 1        | 2.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 14       | 34.15%  |
| Intel  | 14       | 34.15%  |
| AMD    | 13       | 31.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 9.52%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 7.14%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 4.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 4.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 4.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 4.76%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 4.76%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.38%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.38%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 2.38%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 2.38%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 2.38%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 2.38%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 2.38%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 2.38%   |
| Intel HD Graphics 630                                                       | 1        | 2.38%   |
| Intel HD Graphics 530                                                       | 1        | 2.38%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 2.38%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 2.38%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.38%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 2.38%   |
| AMD RV620 PRO [Radeon HD 3470]                                              | 1        | 2.38%   |
| AMD RS482/RS485 [Radeon Xpress 1100/1150]                                   | 1        | 2.38%   |
| AMD RS480 [Radeon Xpress 1150] (Secondary)                                  | 1        | 2.38%   |
| AMD Renoir                                                                  | 1        | 2.38%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.38%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 2.38%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 1        | 2.38%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 2.38%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 13       | 32.5%   |
| 1 x Intel      | 13       | 32.5%   |
| 1 x AMD        | 12       | 30%     |
| 2 x AMD        | 1        | 2.5%    |
| Intel + Nvidia | 1        | 2.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 27       | 67.5%   |
| Proprietary | 12       | 30%     |
| Unknown     | 1        | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 57.5%   |
| 1.01-2.0   | 5        | 12.5%   |
| 5.01-6.0   | 4        | 10%     |
| 0.01-0.5   | 3        | 7.5%    |
| 7.01-8.0   | 2        | 5%      |
| 3.01-4.0   | 2        | 5%      |
| 0.51-1.0   | 1        | 2.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 7        | 19.44%  |
| Dell                 | 6        | 16.67%  |
| Samsung Electronics  | 4        | 11.11%  |
| Hewlett-Packard      | 4        | 11.11%  |
| Acer                 | 4        | 11.11%  |
| ___                  | 1        | 2.78%   |
| Westinghouse         | 1        | 2.78%   |
| Vizio                | 1        | 2.78%   |
| ViewSonic            | 1        | 2.78%   |
| Toshiba              | 1        | 2.78%   |
| Sony                 | 1        | 2.78%   |
| Philips              | 1        | 2.78%   |
| LG Electronics       | 1        | 2.78%   |
| HannStar             | 1        | 2.78%   |
| BenQ                 | 1        | 2.78%   |
| Ancor Communications | 1        | 2.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ___ MY TV LED TV ___0101 1920x1080                                   | 1        | 2.7%    |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch         | 1        | 2.7%    |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                 | 1        | 2.7%    |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                | 1        | 2.7%    |
| Toshiba LCD-MONITOR LCDC980 1280x1024 380x300mm 19.1-inch            | 1        | 2.7%    |
| Sony TV SNY5D01 1360x768                                             | 1        | 2.7%    |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch    | 1        | 2.7%    |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch  | 1        | 2.7%    |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch    | 1        | 2.7%    |
| Samsung Electronics LCD Monitor U28E590 3840x2160                    | 1        | 2.7%    |
| Philips 170S PHL0856 1280x1024 340x270mm 17.1-inch                   | 1        | 2.7%    |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                      | 1        | 2.7%    |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch          | 1        | 2.7%    |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch           | 1        | 2.7%    |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 1        | 2.7%    |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch   | 1        | 2.7%    |
| HannStar LCD Monitor HSD0013 1280x1024 380x300mm 19.1-inch           | 1        | 2.7%    |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                  | 1        | 2.7%    |
| Goldstar LG UltraFine GSM5B10 3840x2160 480x270mm 21.7-inch          | 1        | 2.7%    |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 1        | 2.7%    |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch           | 1        | 2.7%    |
| Goldstar E2742 GSM58C9 1920x1080 600x340mm 27.2-inch                 | 1        | 2.7%    |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                 | 1        | 2.7%    |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                | 1        | 2.7%    |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                    | 1        | 2.7%    |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 1        | 2.7%    |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 1        | 2.7%    |
| Dell S2309W DELA041 1920x1080 510x290mm 23.1-inch                    | 1        | 2.7%    |
| Dell P1917S DELD091 1280x1024 380x300mm 19.1-inch                    | 1        | 2.7%    |
| Dell E2014H DELD03B 1600x900 430x240mm 19.4-inch                     | 1        | 2.7%    |
| Dell E1715S DELD062 1280x1024 340x270mm 17.1-inch                    | 1        | 2.7%    |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                    | 1        | 2.7%    |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch | 1        | 2.7%    |
| Acer V173 ACR0019 1280x1024 340x270mm 17.1-inch                      | 1        | 2.7%    |
| Acer P191W ACR0010 1600x1200 410x260mm 19.1-inch                     | 1        | 2.7%    |
| Acer KG241 ACR0699 1920x1080 530x300mm 24.0-inch                     | 1        | 2.7%    |
| Acer AL2223W ACRAD84 1680x1050 470x300mm 22.0-inch                   | 1        | 2.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 13       | 37.14%  |
| 1280x1024 (SXGA)   | 9        | 25.71%  |
| 3840x2160 (4K)     | 3        | 8.57%   |
| 1600x900 (HD+)     | 2        | 5.71%   |
| 1360x768           | 2        | 5.71%   |
| 2560x1440 (QHD)    | 1        | 2.86%   |
| 1920x1200 (WUXGA)  | 1        | 2.86%   |
| 1680x1050 (WSXGA+) | 1        | 2.86%   |
| 1600x1200          | 1        | 2.86%   |
| 1440x900 (WXGA+)   | 1        | 2.86%   |
| 1366x768 (WXGA)    | 1        | 2.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 8        | 22.22%  |
| 21      | 6        | 16.67%  |
| 17      | 5        | 13.89%  |
| Unknown | 4        | 11.11%  |
| 27      | 3        | 8.33%   |
| 24      | 3        | 8.33%   |
| 23      | 2        | 5.56%   |
| 18      | 2        | 5.56%   |
| 39      | 1        | 2.78%   |
| 37      | 1        | 2.78%   |
| 22      | 1        | 2.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 12       | 34.29%  |
| 501-600     | 7        | 20%     |
| 301-350     | 5        | 14.29%  |
| 351-400     | 4        | 11.43%  |
| Unknown     | 4        | 11.43%  |
| 801-900     | 2        | 5.71%   |
| 601-700     | 1        | 2.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 19       | 55.88%  |
| 5/4     | 9        | 26.47%  |
| 16/10   | 4        | 11.76%  |
| Unknown | 2        | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 11       | 30.56%  |
| 151-200        | 8        | 22.22%  |
| 141-150        | 7        | 19.44%  |
| Unknown        | 4        | 11.11%  |
| 301-350        | 3        | 8.33%   |
| 501-1000       | 2        | 5.56%   |
| 251-300        | 1        | 2.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 21       | 63.64%  |
| 101-120 | 6        | 18.18%  |
| Unknown | 4        | 12.12%  |
| 161-240 | 1        | 3.03%   |
| 121-160 | 1        | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 29       | 72.5%   |
| 0     | 7        | 17.5%   |
| 2     | 3        | 7.5%    |
| 3     | 1        | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 35.71%  |
| Intel                 | 20       | 35.71%  |
| Qualcomm Atheros      | 4        | 7.14%   |
| Broadcom              | 4        | 7.14%   |
| Mellanox Technologies | 2        | 3.57%   |
| Ralink Technology     | 1        | 1.79%   |
| Qualcomm              | 1        | 1.79%   |
| Nvidia                | 1        | 1.79%   |
| Microchip Technology  | 1        | 1.79%   |
| D-Link System         | 1        | 1.79%   |
| Brooktrout Technology | 1        | 1.79%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 14       | 21.21%  |
| Intel Ethernet Connection (2) I219-V                                                  | 5        | 7.58%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 3        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3        | 4.55%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2        | 3.03%   |
| Mellanox MT27500 Family [ConnectX-3]                                                  | 2        | 3.03%   |
| Intel I211 Gigabit Network Connection                                                 | 2        | 3.03%   |
| Intel 82567LM-3 Gigabit Network Connection                                            | 2        | 3.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1        | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 1.52%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1        | 1.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 1.52%   |
| Ralink RT5372 Wireless Adapter                                                        | 1        | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 1.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 1.52%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 1.52%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                            | 1        | 1.52%   |
| Nvidia MCP73 Ethernet                                                                 | 1        | 1.52%   |
| Microchip MCP2200 USB-to-Serial Port                                                  | 1        | 1.52%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 1.52%   |
| Intel Wireless 7260                                                                   | 1        | 1.52%   |
| Intel Wireless 3165                                                                   | 1        | 1.52%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 1.52%   |
| Intel NM10/ICH7 Family LAN Controller                                                 | 1        | 1.52%   |
| Intel Ethernet Connection I217-LM                                                     | 1        | 1.52%   |
| Intel Ethernet Connection (2) I218-V                                                  | 1        | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 1.52%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 1.52%   |
| Intel 82579V Gigabit Network Connection                                               | 1        | 1.52%   |
| Intel 82574L Gigabit Network Connection                                               | 1        | 1.52%   |
| Intel 82567V-2 Gigabit Network Connection                                             | 1        | 1.52%   |
| Intel 82567LF-2 Gigabit Network Connection                                            | 1        | 1.52%   |
| Intel 82566DM-2 Gigabit Network Connection                                            | 1        | 1.52%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]                  | 1        | 1.52%   |
| Brooktrout TruFax Board                                                               | 1        | 1.52%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                               | 1        | 1.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                       | 1        | 1.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 1.52%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 1        | 1.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 35%     |
| Intel                 | 6        | 30%     |
| Qualcomm Atheros      | 3        | 15%     |
| Broadcom              | 2        | 10%     |
| Ralink Technology     | 1        | 5%      |
| D-Link System         | 1        | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2        | 10%     |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1        | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 5%      |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1        | 5%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 5%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 5%      |
| Ralink RT5372 Wireless Adapter                                                        | 1        | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 5%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 5%      |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 5%      |
| Intel Wireless 8265 / 8275                                                            | 1        | 5%      |
| Intel Wireless 7260                                                                   | 1        | 5%      |
| Intel Wireless 3165                                                                   | 1        | 5%      |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 5%      |
| Intel Centrino Wireless-N 105                                                         | 1        | 5%      |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]                  | 1        | 5%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 5%      |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 1        | 5%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 19       | 46.34%  |
| Realtek Semiconductor | 17       | 41.46%  |
| Broadcom              | 2        | 4.88%   |
| Qualcomm Atheros      | 1        | 2.44%   |
| Qualcomm              | 1        | 2.44%   |
| Nvidia                | 1        | 2.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14       | 33.33%  |
| Intel Ethernet Connection (2) I219-V                              | 5        | 11.9%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 7.14%   |
| Intel I211 Gigabit Network Connection                             | 2        | 4.76%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 4.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.38%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1        | 2.38%   |
| Nvidia MCP73 Ethernet                                             | 1        | 2.38%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.38%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.38%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 2.38%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 2.38%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 2.38%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 2.38%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.38%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 2.38%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 2.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 39       | 62.9%   |
| WiFi     | 19       | 30.65%  |
| Unknown  | 3        | 4.84%   |
| Modem    | 1        | 1.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 37       | 69.81%  |
| WiFi     | 14       | 26.42%  |
| Unknown  | 2        | 3.77%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 24       | 60%     |
| 2     | 14       | 35%     |
| 4     | 1        | 2.5%    |
| 3     | 1        | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 37       | 92.5%   |
| Yes  | 3        | 7.5%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 45.45%  |
| Realtek Semiconductor           | 1        | 9.09%   |
| Qualcomm Atheros Communications | 1        | 9.09%   |
| Cambridge Silicon Radio         | 1        | 9.09%   |
| Broadcom                        | 1        | 9.09%   |
| ASUSTek Computer                | 1        | 9.09%   |
| Apple                           | 1        | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 3        | 27.27%  |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 9.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 9.09%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 9.09%   |
| Intel AX200 Bluetooth                               | 1        | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 9.09%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 9.09%   |
| ASUS Bluetooth Controller                           | 1        | 9.09%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1        | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 27       | 40.3%   |
| AMD                 | 16       | 23.88%  |
| Nvidia              | 14       | 20.9%   |
| Sony                | 2        | 2.99%   |
| C-Media Electronics | 2        | 2.99%   |
| XMOS                | 1        | 1.49%   |
| Quanta              | 1        | 1.49%   |
| LG Electronics      | 1        | 1.49%   |
| Creative Technology | 1        | 1.49%   |
| Corsair             | 1        | 1.49%   |
| Audio-Technica      | 1        | 1.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 High Definition Audio Controller                                     | 4        | 5.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4        | 5.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 5.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 3.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 3.9%    |
| Intel 200 Series PCH HD Audio                                                     | 3        | 3.9%    |
| AMD Family 17h/19h HD Audio Controller                                            | 3        | 3.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3        | 3.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 2        | 2.6%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2        | 2.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2        | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 2.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 2.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 2.6%    |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2        | 2.6%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2        | 2.6%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 2.6%    |
| XMOS XMOS XS1-U8 MFA (ST)                                                         | 1        | 1.3%    |
| Sony Sony Audio                                                                   | 1        | 1.3%    |
| Sony DualShock 4 [CUH-ZCT2x]                                                      | 1        | 1.3%    |
| Quanta USB Audio Realtek USB2.0 Audio Microphone                                  | 1        | 1.3%    |
| Nvidia MCP73 High Definition Audio                                                | 1        | 1.3%    |
| Nvidia MCP61 High Definition Audio                                                | 1        | 1.3%    |
| Nvidia High Definition Audio Controller                                           | 1        | 1.3%    |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 1.3%    |
| Nvidia GP104 High Definition Audio Controller                                     | 1        | 1.3%    |
| Nvidia GA104 High Definition Audio Controller                                     | 1        | 1.3%    |
| LG Electronics USB Audio LG UltraFine Display Audio                               | 1        | 1.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 1.3%    |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 1.3%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 1        | 1.3%    |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 1        | 1.3%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1        | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 1        | 1.3%    |
| Creative Technology Sound Blaster Omni Surround 5.1                               | 1        | 1.3%    |
| Corsair Corsair VOID PRO Wireless Gaming Headset                                  | 1        | 1.3%    |
| Corsair Corsair ST100 Headset Output                                              | 1        | 1.3%    |
| C-Media Electronics Audio Device                                                  | 1        | 1.3%    |
| C-Media Electronics Audio Adapter                                                 | 1        | 1.3%    |
| Audio-Technica AT2020USB+                                                         | 1        | 1.3%    |
| AMD Vega 20 HDMI Audio [Radeon VII]                                               | 1        | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 1        | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 1.3%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 1        | 1.3%    |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 1        | 1.3%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1        | 1.3%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 1.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 7        | 15.56%  |
| Unknown             | 6        | 13.33%  |
| SK Hynix            | 6        | 13.33%  |
| Micron Technology   | 5        | 11.11%  |
| G.Skill             | 5        | 11.11%  |
| Corsair             | 5        | 11.11%  |
| Samsung Electronics | 3        | 6.67%   |
| Crucial             | 3        | 6.67%   |
| Nanya Technology    | 2        | 4.44%   |
| Elpida              | 2        | 4.44%   |
| EVGA                | 1        | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 2        | 4.17%   |
| Micron RAM ITC 4096MB DIMM DDR3 1066MT/s                  | 2        | 4.17%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1        | 2.08%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                  | 1        | 2.08%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s               | 1        | 2.08%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s               | 1        | 2.08%   |
| SK Hynix RAM Zhidian4GDDR800000 4GB DIMM DDR2 800MT/s     | 1        | 2.08%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 2.08%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1        | 2.08%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s      | 1        | 2.08%   |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s      | 1        | 2.08%   |
| SK Hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s      | 1        | 2.08%   |
| SK Hynix RAM HMT125U6AFP8C-G7 2048MB DIMM DDR3 1066MT/s   | 1        | 2.08%   |
| SK Hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s           | 1        | 2.08%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s     | 1        | 2.08%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s     | 1        | 2.08%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 2.08%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s        | 1        | 2.08%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 800MT/s      | 1        | 2.08%   |
| Micron RAM 8HTF12864AZ-800H1 1GB DIMM DDR2 800MT/s        | 1        | 2.08%   |
| Micron RAM 36JSF1G72PZ-1 8GB DIMM DDR3 1600MT/s           | 1        | 2.08%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s      | 1        | 2.08%   |
| Kingston RAM KY996D-ELD 2GB DIMM 1066MT/s                 | 1        | 2.08%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s         | 1        | 2.08%   |
| Kingston RAM KHX2400C15D4/8G 8192MB DIMM DDR4 2400MT/s    | 1        | 2.08%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 2400MT/s     | 1        | 2.08%   |
| Kingston RAM K531R8-ETB 4GB DIMM DDR3 1600MT/s            | 1        | 2.08%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1067MT/s    | 1        | 2.08%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s    | 1        | 2.08%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s    | 1        | 2.08%   |
| G.Skill RAM F4-3600C18-8GTZN 8192MB DIMM DDR4 3600MT/s    | 1        | 2.08%   |
| G.Skill RAM F4-3600C17-16GTZSW 16GB DIMM DDR4 3600MT/s    | 1        | 2.08%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s       | 1        | 2.08%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 2933MT/s       | 1        | 2.08%   |
| G.Skill RAM F4-2400C17-8GVR 8192MB DIMM DDR4 2400MT/s     | 1        | 2.08%   |
| EVGA RAM 8GX-D4-3200-MR 8192MB DIMM DDR4 3200MT/s         | 1        | 2.08%   |
| Elpida RAM EBJ21UE8BAFA-AE-E 2GB DIMM 1066MT/s            | 1        | 2.08%   |
| Elpida RAM EBE11UD8AJWA-6E-E 1024MB DIMM DDR2 667MT/s     | 1        | 2.08%   |
| Crucial RAM CT16G4DFD824A.M16FE 16GB DIMM DDR4 2400MT/s   | 1        | 2.08%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8192MB DIMM DDR4 2400MT/s | 1        | 2.08%   |
| Crucial RAM BLS8G4D240FSB.16FBD 8GB DIMM DDR4 2933MT/s    | 1        | 2.08%   |
| Corsair RAM Module 8GB DIMM DDR4 3200MT/s                 | 1        | 2.08%   |
| Corsair RAM CMZ4GX3M2A1600C9 2048MB DIMM DDR3 1333MT/s    | 1        | 2.08%   |
| Corsair RAM CMY16GX3M2A2400C11 8192MB DIMM DDR3 2400MT/s  | 1        | 2.08%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3200MT/s    | 1        | 2.08%   |
| Corsair RAM CM2X2048-6400C5 2048MB DIMM DDR2 800MT/s      | 1        | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 16       | 37.21%  |
| DDR3    | 15       | 34.88%  |
| DDR2    | 8        | 18.6%   |
| Unknown | 2        | 4.65%   |
| SDRAM   | 1        | 2.33%   |
| DDR     | 1        | 2.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 38       | 92.68%  |
| SODIMM | 3        | 7.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 14       | 31.11%  |
| 4096  | 12       | 26.67%  |
| 2048  | 10       | 22.22%  |
| 1024  | 5        | 11.11%  |
| 16384 | 4        | 8.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2400    | 7        | 16.28%  |
| 1600    | 6        | 13.95%  |
| 800     | 6        | 13.95%  |
| 1333    | 5        | 11.63%  |
| 3200    | 4        | 9.3%    |
| 1066    | 4        | 9.3%    |
| 3600    | 2        | 4.65%   |
| 2933    | 2        | 4.65%   |
| 2667    | 2        | 4.65%   |
| 1067    | 2        | 4.65%   |
| 667     | 1        | 2.33%   |
| 533     | 1        | 2.33%   |
| Unknown | 1        | 2.33%   |

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
| Quanta Realtek DMFT - RGB             | 1        | 20%     |
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
| 1     | 18       | 45%     |
| 2     | 12       | 30%     |
| 0     | 9        | 22.5%   |
| 3     | 1        | 2.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 22       | 48.89%  |
| Firewire controller      | 11       | 24.44%  |
| Net/wireless             | 6        | 13.33%  |
| Network                  | 3        | 6.67%   |
| Bluetooth                | 2        | 4.44%   |
| Sound                    | 1        | 2.22%   |

