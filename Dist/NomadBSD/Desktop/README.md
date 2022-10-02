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

Total: 60

| Vendor   | Model                       | Probe                                                     | Date         |
|----------|-----------------------------|-----------------------------------------------------------|--------------|
| ASRock   | B550 Steel Legend           | [4e6381e037](https://bsd-hardware.info/?probe=4e6381e037) | Jun 22, 2022 |
| HP       | 2B29                        | [e8c355314e](https://bsd-hardware.info/?probe=e8c355314e) | Jun 17, 2022 |
| HP       | 1589                        | [3765f1cb09](https://bsd-hardware.info/?probe=3765f1cb09) | Jun 17, 2022 |
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
| NomadBSD 5806f915 | 18       | 41.86%  |
| NomadBSD 1.3.2    | 14       | 32.56%  |
| NomadBSD 1.4-RC1  | 4        | 9.3%    |
| NomadBSD 1.4      | 3        | 6.98%   |
| NomadBSD 1.3.1    | 2        | 4.65%   |
| NomadBSD 1.3      | 1        | 2.33%   |
| NomadBSD 1.0      | 1        | 2.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| NomadBSD | 43       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 42       | 97.67%  |
| i386  | 1        | 2.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Openbox | 39       | 88.64%  |
| KDE5    | 2        | 4.55%   |
| GNUstep | 1        | 2.27%   |
| GNOME   | 1        | 2.27%   |
| filer   | 1        | 2.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 43       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 41       | 95.35%  |
| SDDM | 2        | 4.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 17       | 39.53%  |
| Unknown | 9        | 20.93%  |
| de_DE   | 3        | 6.98%   |
| tr_TR   | 2        | 4.65%   |
| ru_RU   | 2        | 4.65%   |
| pt_BR   | 2        | 4.65%   |
| it_IT   | 2        | 4.65%   |
| hu_HU   | 2        | 4.65%   |
| fi_FI   | 1        | 2.33%   |
| es_ES   | 1        | 2.33%   |
| en_AU   | 1        | 2.33%   |
| cs_CZ   | 1        | 2.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 42       | 97.67%  |
| BIOS | 1        | 2.33%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ufs  | 37       | 86.05%  |
| Zfs  | 6        | 13.95%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 33       | 76.74%  |
| MBR  | 10       | 23.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 20.93%  |
| Hewlett-Packard     | 8        | 18.6%   |
| Gigabyte Technology | 6        | 13.95%  |
| Dell                | 6        | 13.95%  |
| ASRock              | 5        | 11.63%  |
| Acer                | 3        | 6.98%   |
| Semp Toshiba        | 1        | 2.33%   |
| Pegatron            | 1        | 2.33%   |
| Lenovo              | 1        | 2.33%   |
| Intel               | 1        | 2.33%   |
| Foxconn             | 1        | 2.33%   |
| Unknown             | 1        | 2.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| Acer Veriton M460                        | 2        | 4.65%   |
| Semp Toshiba STI                         | 1        | 2.33%   |
| Pegatron Elite 7300 Series MT            | 1        | 2.33%   |
| Lenovo ThinkCentre M93p 10A8001HUS       | 1        | 2.33%   |
| Intel DCP847SKE                          | 1        | 2.33%   |
| HP Z620 Workstation                      | 1        | 2.33%   |
| HP Z420 Workstation                      | 1        | 2.33%   |
| HP Desktop M01-F1xxx                     | 1        | 2.33%   |
| HP Compaq Elite 8300 Touch All-in-One PC | 1        | 2.33%   |
| HP Compaq dc7900 Convertible Minitower   | 1        | 2.33%   |
| HP Compaq dc7800p Convertible Minitower  | 1        | 2.33%   |
| HP Compaq dc5750 Microtower              | 1        | 2.33%   |
| HP 550-a114                              | 1        | 2.33%   |
| Gigabyte Z370 AORUS ULTRAGAMING WIFI-OP  | 1        | 2.33%   |
| Gigabyte Z370 AORUS Ultra Gaming         | 1        | 2.33%   |
| Gigabyte X570S GAMING X                  | 1        | 2.33%   |
| Gigabyte X570 AORUS PRO                  | 1        | 2.33%   |
| Gigabyte X570 AORUS MASTER               | 1        | 2.33%   |
| Gigabyte MZGLKBP-00                      | 1        | 2.33%   |
| Foxconn Napa                             | 1        | 2.33%   |
| Dell Studio XPS 8100                     | 1        | 2.33%   |
| Dell Studio XPS 435MT                    | 1        | 2.33%   |
| Dell OptiPlex 9010                       | 1        | 2.33%   |
| Dell OptiPlex 780                        | 1        | 2.33%   |
| Dell OptiPlex 3020                       | 1        | 2.33%   |
| Dell OptiPlex 3010                       | 1        | 2.33%   |
| ASUS Z170-A                              | 1        | 2.33%   |
| ASUS V-P7H55E                            | 1        | 2.33%   |
| ASUS TUF GAMING B550M-PLUS               | 1        | 2.33%   |
| ASUS ROG STRIX X299-E GAMING             | 1        | 2.33%   |
| ASUS PRIME Z390-P                        | 1        | 2.33%   |
| ASUS PRIME A320M-K                       | 1        | 2.33%   |
| ASUS Maximus VIII HERO                   | 1        | 2.33%   |
| ASUS M5A97 R2.0                          | 1        | 2.33%   |
| ASUS ER904AA-ABA A1440N                  | 1        | 2.33%   |
| ASRock Z97 Extreme6/ac                   | 1        | 2.33%   |
| ASRock N68C-GS4 FX                       | 1        | 2.33%   |
| ASRock B550 Steel Legend                 | 1        | 2.33%   |
| ASRock B450M Pro4                        | 1        | 2.33%   |
| ASRock AB350 Pro4                        | 1        | 2.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| HP Compaq           | 4        | 9.3%    |
| Dell OptiPlex       | 4        | 9.3%    |
| Gigabyte Z370       | 2        | 4.65%   |
| Gigabyte X570       | 2        | 4.65%   |
| Dell Studio         | 2        | 4.65%   |
| ASUS PRIME          | 2        | 4.65%   |
| Acer Veriton        | 2        | 4.65%   |
| Semp Toshiba STI    | 1        | 2.33%   |
| Pegatron Elite      | 1        | 2.33%   |
| Lenovo ThinkCentre  | 1        | 2.33%   |
| Intel DCP847SKE     | 1        | 2.33%   |
| HP Z620             | 1        | 2.33%   |
| HP Z420             | 1        | 2.33%   |
| HP Desktop          | 1        | 2.33%   |
| HP 550-a114         | 1        | 2.33%   |
| Gigabyte X570S      | 1        | 2.33%   |
| Gigabyte MZGLKBP-00 | 1        | 2.33%   |
| Foxconn Napa        | 1        | 2.33%   |
| ASUS Z170-A         | 1        | 2.33%   |
| ASUS V-P7H55E       | 1        | 2.33%   |
| ASUS TUF            | 1        | 2.33%   |
| ASUS ROG            | 1        | 2.33%   |
| ASUS Maximus        | 1        | 2.33%   |
| ASUS M5A97          | 1        | 2.33%   |
| ASUS ER904AA-ABA    | 1        | 2.33%   |
| ASRock Z97          | 1        | 2.33%   |
| ASRock N68C-GS4     | 1        | 2.33%   |
| ASRock B550         | 1        | 2.33%   |
| ASRock B450M        | 1        | 2.33%   |
| ASRock AB350        | 1        | 2.33%   |
| Acer Aspire         | 1        | 2.33%   |
| Unknown             | 1        | 2.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2009 | 6        | 13.95%  |
| 2019 | 5        | 11.63%  |
| 2021 | 4        | 9.3%    |
| 2015 | 4        | 9.3%    |
| 2018 | 3        | 6.98%   |
| 2017 | 3        | 6.98%   |
| 2013 | 3        | 6.98%   |
| 2010 | 3        | 6.98%   |
| 2020 | 2        | 4.65%   |
| 2016 | 2        | 4.65%   |
| 2012 | 2        | 4.65%   |
| 2022 | 1        | 2.33%   |
| 2014 | 1        | 2.33%   |
| 2011 | 1        | 2.33%   |
| 2008 | 1        | 2.33%   |
| 2007 | 1        | 2.33%   |
| 2006 | 1        | 2.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 43       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 43       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 11       | 25.58%  |
| 4.01-8.0    | 10       | 23.26%  |
| 16.01-24.0  | 10       | 23.26%  |
| 32.01-64.0  | 6        | 13.95%  |
| 64.01-256.0 | 4        | 9.3%    |
| 3.01-4.0    | 1        | 2.33%   |
| 2.01-3.0    | 1        | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 21       | 48.84%  |
| 0.51-1.0 | 11       | 25.58%  |
| 1.01-2.0 | 9        | 20.93%  |
| 2.01-3.0 | 2        | 4.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 41.86%  |
| 2      | 11       | 25.58%  |
| 3      | 9        | 20.93%  |
| 4      | 3        | 6.98%   |
| 7      | 1        | 2.33%   |
| 0      | 1        | 2.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 24       | 55.81%  |
| No        | 19       | 44.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 42       | 97.67%  |
| No        | 1        | 2.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 22       | 51.16%  |
| Yes       | 21       | 48.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 72.73%  |
| Yes       | 12       | 27.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| USA       | 15       | 34.88%  |
| Germany   | 4        | 9.3%    |
| Turkey    | 3        | 6.98%   |
| Russia    | 3        | 6.98%   |
| France    | 3        | 6.98%   |
| Thailand  | 2        | 4.65%   |
| Italy     | 2        | 4.65%   |
| Hungary   | 2        | 4.65%   |
| Brazil    | 2        | 4.65%   |
| Slovakia  | 1        | 2.33%   |
| Serbia    | 1        | 2.33%   |
| Finland   | 1        | 2.33%   |
| Czechia   | 1        | 2.33%   |
| Colombia  | 1        | 2.33%   |
| Australia | 1        | 2.33%   |
| Argentina | 1        | 2.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Paris            | 3        | 6.98%   |
| Duncan           | 3        | 6.98%   |
| Woodland         | 2        | 4.65%   |
| Volzhskiy        | 2        | 4.65%   |
| Rio de Janeiro   | 2        | 4.65%   |
| Milan            | 2        | 4.65%   |
| Istanbul         | 2        | 4.65%   |
| Hodmezovasarhely | 2        | 4.65%   |
| Bangkok          | 2        | 4.65%   |
| Tucson           | 1        | 2.33%   |
| Scottsdale       | 1        | 2.33%   |
| San Francisco    | 1        | 2.33%   |
| Peoria           | 1        | 2.33%   |
| Palm Bay         | 1        | 2.33%   |
| Moscow           | 1        | 2.33%   |
| Melcice          | 1        | 2.33%   |
| McDonough        | 1        | 2.33%   |
| Marburg          | 1        | 2.33%   |
| Langen           | 1        | 2.33%   |
| Helsinki         | 1        | 2.33%   |
| Frisco           | 1        | 2.33%   |
| Dortmund         | 1        | 2.33%   |
| Denver           | 1        | 2.33%   |
| CГіrdoba       | 1        | 2.33%   |
| Conway           | 1        | 2.33%   |
| Cologne          | 1        | 2.33%   |
| Cleveland        | 1        | 2.33%   |
| Brisbane         | 1        | 2.33%   |
| BogotГЎ        | 1        | 2.33%   |
| Bilina           | 1        | 2.33%   |
| Belgrade         | 1        | 2.33%   |
| BalД±kesir     | 1        | 2.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 15       | 21     | 20%     |
| Samsung Electronics | 13       | 16     | 17.33%  |
| Seagate             | 12       | 13     | 16%     |
| Toshiba             | 7        | 9      | 9.33%   |
| A-DATA Technology   | 5        | 5      | 6.67%   |
| Kingston            | 4        | 4      | 5.33%   |
| Crucial             | 4        | 4      | 5.33%   |
| Hewlett-Packard     | 3        | 3      | 4%      |
| SK hynix            | 2        | 2      | 2.67%   |
| Intel               | 2        | 2      | 2.67%   |
| Hitachi             | 2        | 2      | 2.67%   |
| Transcend           | 1        | 1      | 1.33%   |
| Team                | 1        | 1      | 1.33%   |
| SanDisk             | 1        | 2      | 1.33%   |
| ORICO               | 1        | 1      | 1.33%   |
| Maxtor              | 1        | 1      | 1.33%   |
| HGST                | 1        | 1      | 1.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| WDC WDS100T1X0E-00AFY0 1TB                | 2        | 2.38%   |
| WDC WD40PURX-64GVNY0 4TB                  | 2        | 2.38%   |
| WDC WD1600AAJS-22L7A0 160GB               | 2        | 2.38%   |
| Toshiba HDWD120 2TB                       | 2        | 2.38%   |
| Seagate ST500DM002-1BD142 500GB           | 2        | 2.38%   |
| Samsung SSD 970 EVO 500GB                 | 2        | 2.38%   |
| Samsung SSD 870 QVO 2TB                   | 2        | 2.38%   |
| Kingston SA400S37480G 480GB               | 2        | 2.38%   |
| HP SSD EX950 2TB                          | 2        | 2.38%   |
| A-DATA SU630 240GB                        | 2        | 2.38%   |
| WDC WDS240G2G0B-00EPW0 240GB              | 1        | 1.19%   |
| WDC WDS120G2G0A-00JH30 120GB              | 1        | 1.19%   |
| WDC WD6400AAKS-22A7B2 640GB               | 1        | 1.19%   |
| WDC WD60EZRZ-00GZ5B1 6TB                  | 1        | 1.19%   |
| WDC WD40NMZW-11GX6S1 4TB                  | 1        | 1.19%   |
| WDC WD2500BEKT-00PVMT0 250GB              | 1        | 1.19%   |
| WDC WD2004FBYZ-01YCBB1 2TB                | 1        | 1.19%   |
| WDC WD1200BEVE-00UYT0 120GB               | 1        | 1.19%   |
| WDC WD10JPLX-00MBPT0 1TB                  | 1        | 1.19%   |
| WDC WD10EZRZ-00HTKB0 1TB                  | 1        | 1.19%   |
| WDC WD10EZRX-00L4HB0 1TB                  | 1        | 1.19%   |
| WDC WD10EFRX-68PJCN0 1TB                  | 1        | 1.19%   |
| WDC WD10EADS-00P8B0 1TB                   | 1        | 1.19%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1        | 1.19%   |
| Transcend TS32GCF800 32GB                 | 1        | 1.19%   |
| Toshiba MK1032GAX 100GB                   | 1        | 1.19%   |
| Toshiba MG06ACA800E 8TB                   | 1        | 1.19%   |
| Toshiba HDWD130 3TB                       | 1        | 1.19%   |
| Toshiba HDWD110 1TB                       | 1        | 1.19%   |
| Toshiba DT01ACA100 1TB                    | 1        | 1.19%   |
| Toshiba DT01ABA300 3TB                    | 1        | 1.19%   |
| Team TEAML5Lite3D1T 1TB                   | 1        | 1.19%   |
| SK hynix SKHynix_HFS256GD9TNI-L2B0B 256GB | 1        | 1.19%   |
| SK hynix SHGS31-500GS-2 500GB             | 1        | 1.19%   |
| Seagate ST9500325AS 500GB                 | 1        | 1.19%   |
| Seagate ST4000DM000-2AE166 4TB            | 1        | 1.19%   |
| Seagate ST3500418AS 500GB                 | 1        | 1.19%   |
| Seagate ST3250823AS 250GB                 | 1        | 1.19%   |
| Seagate ST3250310AS 250GB                 | 1        | 1.19%   |
| Seagate ST31000528AS 1TB                  | 1        | 1.19%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 13       | 16     | 31.71%  |
| Seagate             | 12       | 13     | 29.27%  |
| Toshiba             | 7        | 9      | 17.07%  |
| Samsung Electronics | 4        | 4      | 9.76%   |
| Hitachi             | 2        | 2      | 4.88%   |
| Maxtor              | 1        | 1      | 2.44%   |
| HGST                | 1        | 1      | 2.44%   |
| Hewlett-Packard     | 1        | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 5        | 7      | 23.81%  |
| A-DATA Technology   | 5        | 5      | 23.81%  |
| Kingston            | 3        | 3      | 14.29%  |
| WDC                 | 2        | 2      | 9.52%   |
| Crucial             | 2        | 2      | 9.52%   |
| Transcend           | 1        | 1      | 4.76%   |
| Team                | 1        | 1      | 4.76%   |
| SK hynix            | 1        | 1      | 4.76%   |
| SanDisk             | 1        | 2      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 30       | 47     | 50%     |
| SSD  | 17       | 24     | 28.33%  |
| NVMe | 13       | 17     | 21.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 39       | 71     | 75%     |
| NVMe | 13       | 17     | 25%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 27       | 37     | 48.21%  |
| 0.51-1.0   | 16       | 19     | 28.57%  |
| 1.01-2.0   | 5        | 5      | 8.93%   |
| 3.01-4.0   | 4        | 4      | 7.14%   |
| 2.01-3.0   | 3        | 3      | 5.36%   |
| 4.01-10.0  | 1        | 3      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 35       | 81.4%   |
| 101-250    | 5        | 11.63%  |
| 51-100     | 2        | 4.65%   |
| 501-1000   | 1        | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 41       | 95.35%  |
| 21-50   | 1        | 2.33%   |
| 51-100  | 1        | 2.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD40PURX-64GVNY0 4TB          | 1        | 1      | 11.11%  |
| WDC WD10EFRX-68PJCN0 1TB          | 1        | 2      | 11.11%  |
| Toshiba HDWD120 2TB               | 1        | 1      | 11.11%  |
| Toshiba DT01ABA300 3TB            | 1        | 1      | 11.11%  |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 11.11%  |
| Seagate ST3250823AS 250GB         | 1        | 1      | 11.11%  |
| Samsung Electronics HM160HI 160GB | 1        | 1      | 11.11%  |
| Hewlett-Packard MB1000GCWCV 1TB   | 1        | 1      | 11.11%  |
| A-DATA Technology XM13 32GB       | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 3      | 22.22%  |
| Toshiba             | 2        | 2      | 22.22%  |
| Seagate             | 2        | 2      | 22.22%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| Hewlett-Packard     | 1        | 1      | 11.11%  |
| A-DATA Technology   | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 3      | 25%     |
| Toshiba             | 2        | 2      | 25%     |
| Seagate             | 2        | 2      | 25%     |
| Samsung Electronics | 1        | 1      | 12.5%   |
| Hewlett-Packard     | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 9      | 87.5%   |
| SSD  | 1        | 1      | 12.5%   |

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
| Works    | 38       | 72     | 80.85%  |
| Malfunc  | 8        | 10     | 17.02%  |
| Detected | 1        | 6      | 2.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 30       | 46.88%  |
| AMD                         | 12       | 18.75%  |
| Samsung Electronics         | 5        | 7.81%   |
| ASMedia Technology          | 5        | 7.81%   |
| SanDisk                     | 3        | 4.69%   |
| Nvidia                      | 2        | 3.13%   |
| Micron/Crucial Technology   | 2        | 3.13%   |
| Biwin Storage Technology    | 2        | 3.13%   |
| VIA Technologies            | 1        | 1.56%   |
| Silicon Motion              | 1        | 1.56%   |
| Kingston Technology Company | 1        | 1.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8        | 9.41%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5        | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4        | 4.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 3.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 3.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 3.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3        | 3.53%   |
| Unknown                                                                        | 3        | 3.53%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2        | 2.35%   |
| Intel SATA Controller [RAID mode]                                              | 2        | 2.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 2.35%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 2        | 2.35%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 2        | 2.35%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                           | 2        | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 2.35%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 2        | 2.35%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 2.35%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 2.35%   |
| VIA VT6421 IDE/SATA Controller                                                 | 1        | 1.18%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 1.18%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1        | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1        | 1.18%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                        | 1        | 1.18%   |
| Nvidia MCP73 IDE Controller                                                    | 1        | 1.18%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.18%   |
| Nvidia MCP61 IDE                                                               | 1        | 1.18%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1        | 1.18%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 1.18%   |
| Intel SSD 660P Series                                                          | 1        | 1.18%   |
| Intel NVMe Optane Memory Series                                                | 1        | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 1.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 1.18%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1        | 1.18%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                       | 1        | 1.18%   |
| Intel C600/X79 series chipset 2-Port SATA IDE Controller                       | 1        | 1.18%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 1        | 1.18%   |
| Intel 82Q35 Express PT IDER Controller                                         | 1        | 1.18%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 1.18%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 31       | 48.44%  |
| NVMe | 13       | 20.31%  |
| IDE  | 13       | 20.31%  |
| RAID | 5        | 7.81%   |
| SAS  | 2        | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 30       | 69.77%  |
| AMD    | 13       | 30.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 2        | 4.65%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 2        | 4.65%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 4.65%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 4.65%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 2.33%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz            | 1        | 2.33%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1        | 2.33%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1        | 2.33%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 1        | 2.33%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1        | 2.33%   |
| Intel Pentium D CPU 2.80GHz                 | 1        | 2.33%   |
| Intel Core i9-7960X CPU @ 2.80GHz           | 1        | 2.33%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 2.33%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 2.33%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 2.33%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 2.33%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1        | 2.33%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1        | 2.33%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1        | 2.33%   |
| Intel Core i5-8600K CPU @ 3.60GHz           | 1        | 2.33%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1        | 2.33%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1        | 2.33%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 2.33%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 2.33%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 2.33%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz        | 1        | 2.33%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 2.33%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz        | 1        | 2.33%   |
| Intel Core 2 Duo                            | 1        | 2.33%   |
| Intel Celeron CPU 847E @ 1.10GHz            | 1        | 2.33%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 2.33%   |
| AMD Ryzen 5 4600G with Radeon Graphics      | 1        | 2.33%   |
| AMD Ryzen 5 3600XT 6-Core Processor         | 1        | 2.33%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1        | 2.33%   |
| AMD Ryzen 5 1500X Quad-Core Processor       | 1        | 2.33%   |
| AMD FX-6300 Six-Core Processor              | 1        | 2.33%   |
| AMD Athlon 64 X2 Dual Core Processor 5600+  | 1        | 2.33%   |
| AMD Athlon 64 X2 Dual Core Processor 4000+  | 1        | 2.33%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 1        | 2.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 7        | 16.28%  |
| Intel Core i5           | 7        | 16.28%  |
| Intel Core 2 Duo        | 6        | 13.95%  |
| AMD Ryzen 5             | 6        | 13.95%  |
| Intel Xeon              | 3        | 6.98%   |
| Intel Pentium Dual-Core | 2        | 4.65%   |
| AMD Ryzen 9             | 2        | 4.65%   |
| AMD Athlon 64 X2        | 2        | 4.65%   |
| Intel Pentium Silver    | 1        | 2.33%   |
| Intel Pentium D         | 1        | 2.33%   |
| Intel Core i9           | 1        | 2.33%   |
| Intel Core i3           | 1        | 2.33%   |
| Intel Celeron           | 1        | 2.33%   |
| AMD Ryzen 7             | 1        | 2.33%   |
| AMD FX                  | 1        | 2.33%   |
| AMD A8                  | 1        | 2.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 14       | 32.56%  |
| 2       | 12       | 27.91%  |
| 8       | 6        | 13.95%  |
| 12      | 3        | 6.98%   |
| 6       | 3        | 6.98%   |
| 24      | 2        | 4.65%   |
| 16      | 2        | 4.65%   |
| Unknown | 1        | 2.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 42       | 97.67%  |
| 2      | 1        | 2.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 31       | 72.09%  |
| 2       | 11       | 25.58%  |
| Unknown | 1        | 2.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 8        | 18.6%   |
| SandyBridge   | 4        | 9.3%    |
| KabyLake      | 4        | 9.3%    |
| IvyBridge     | 4        | 9.3%    |
| Zen           | 3        | 6.98%   |
| Nehalem       | 3        | 6.98%   |
| Haswell       | 3        | 6.98%   |
| Zen+          | 2        | 4.65%   |
| Zen 3         | 2        | 4.65%   |
| Zen 2         | 2        | 4.65%   |
| Skylake       | 2        | 4.65%   |
| K8 Hammer     | 2        | 4.65%   |
| Puma          | 1        | 2.33%   |
| Piledriver    | 1        | 2.33%   |
| NetBurst      | 1        | 2.33%   |
| Goldmont plus | 1        | 2.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 16       | 36.36%  |
| Nvidia | 14       | 31.82%  |
| Intel  | 14       | 31.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 8.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 6.67%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 4.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 4.44%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2        | 4.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 4.44%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2        | 4.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 4.44%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 4.44%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 2.22%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.22%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1        | 2.22%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1        | 2.22%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 1        | 2.22%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 2.22%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 2.22%   |
| Nvidia G72 [GeForce 7300 LE]                                                | 1        | 2.22%   |
| Intel HD Graphics 630                                                       | 1        | 2.22%   |
| Intel HD Graphics 530                                                       | 1        | 2.22%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 2.22%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 1        | 2.22%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.22%   |
| AMD Vega 20 [Radeon VII]                                                    | 1        | 2.22%   |
| AMD RV620 PRO [Radeon HD 3470]                                              | 1        | 2.22%   |
| AMD RS482/RS485 [Radeon Xpress 1100/1150]                                   | 1        | 2.22%   |
| AMD RS480 [Radeon Xpress 1150] (Secondary)                                  | 1        | 2.22%   |
| AMD Renoir                                                                  | 1        | 2.22%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 1        | 2.22%   |
| AMD Pitcairn XT GL [FirePro W7000]                                          | 1        | 2.22%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 1        | 2.22%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 1        | 2.22%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 1        | 2.22%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 2.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 15       | 34.88%  |
| 1 x Nvidia     | 13       | 30.23%  |
| 1 x Intel      | 13       | 30.23%  |
| 2 x AMD        | 1        | 2.33%   |
| Intel + Nvidia | 1        | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 30       | 69.77%  |
| Proprietary | 12       | 27.91%  |
| Unknown     | 1        | 2.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 24       | 55.81%  |
| 1.01-2.0   | 5        | 11.63%  |
| 5.01-6.0   | 4        | 9.3%    |
| 0.01-0.5   | 4        | 9.3%    |
| 3.01-4.0   | 3        | 6.98%   |
| 7.01-8.0   | 2        | 4.65%   |
| 0.51-1.0   | 1        | 2.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 7        | 17.95%  |
| Dell                 | 6        | 15.38%  |
| Samsung Electronics  | 4        | 10.26%  |
| Hewlett-Packard      | 4        | 10.26%  |
| Acer                 | 4        | 10.26%  |
| ASUSTek Computer     | 2        | 5.13%   |
| Ancor Communications | 2        | 5.13%   |
| ___                  | 1        | 2.56%   |
| Westinghouse         | 1        | 2.56%   |
| Vizio                | 1        | 2.56%   |
| ViewSonic            | 1        | 2.56%   |
| Toshiba              | 1        | 2.56%   |
| Sony                 | 1        | 2.56%   |
| Philips              | 1        | 2.56%   |
| LG Electronics       | 1        | 2.56%   |
| HannStar             | 1        | 2.56%   |
| BenQ                 | 1        | 2.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch         | 2        | 5%      |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1        | 2.5%    |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch         | 1        | 2.5%    |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                 | 1        | 2.5%    |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                | 1        | 2.5%    |
| Toshiba LCD-MONITOR LCDC980 1280x1024 380x300mm 19.1-inch            | 1        | 2.5%    |
| Sony TV SNY5D01 1360x768                                             | 1        | 2.5%    |
| Samsung Electronics U28E510 SAM0D68 3840x2160 610x350mm 27.7-inch    | 1        | 2.5%    |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch  | 1        | 2.5%    |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch    | 1        | 2.5%    |
| Samsung Electronics LCD Monitor U28E590 3840x2160                    | 1        | 2.5%    |
| Philips 170S PHL0856 1280x1024 340x270mm 17.1-inch                   | 1        | 2.5%    |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                      | 1        | 2.5%    |
| Hewlett-Packard W2072a HWP299F 1600x900 440x250mm 19.9-inch          | 1        | 2.5%    |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch           | 1        | 2.5%    |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch          | 1        | 2.5%    |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch   | 1        | 2.5%    |
| HannStar LCD Monitor HSD0013 1280x1024 380x300mm 19.1-inch           | 1        | 2.5%    |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                  | 1        | 2.5%    |
| Goldstar LG UltraFine GSM5B10 3840x2160 480x270mm 21.7-inch          | 1        | 2.5%    |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 1        | 2.5%    |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch           | 1        | 2.5%    |
| Goldstar E2742 GSM58C9 1920x1080 600x340mm 27.2-inch                 | 1        | 2.5%    |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                 | 1        | 2.5%    |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                | 1        | 2.5%    |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                    | 1        | 2.5%    |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                    | 1        | 2.5%    |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                    | 1        | 2.5%    |
| Dell S2309W DELA041 1920x1080 510x290mm 23.1-inch                    | 1        | 2.5%    |
| Dell P1917S DELD091 1280x1024 380x300mm 19.1-inch                    | 1        | 2.5%    |
| Dell E2014H DELD03B 1600x900 430x240mm 19.4-inch                     | 1        | 2.5%    |
| Dell E1715S DELD062 1280x1024 340x270mm 17.1-inch                    | 1        | 2.5%    |
| BenQ GW2260 BNQ78C4 1920x1080 480x270mm 21.7-inch                    | 1        | 2.5%    |
| Ancor Communications PA248 ACI24B1 1920x1200 550x350mm 25.7-inch     | 1        | 2.5%    |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch | 1        | 2.5%    |
| Acer V173 ACR0019 1280x1024 340x270mm 17.1-inch                      | 1        | 2.5%    |
| Acer P191W ACR0010 1600x1200 410x260mm 19.1-inch                     | 1        | 2.5%    |
| Acer KG241 ACR0699 1920x1080 530x300mm 24.0-inch                     | 1        | 2.5%    |
| Acer AL2223W ACRAD84 1680x1050 470x300mm 22.0-inch                   | 1        | 2.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 15       | 39.47%  |
| 1280x1024 (SXGA)   | 9        | 23.68%  |
| 3840x2160 (4K)     | 3        | 7.89%   |
| 1920x1200 (WUXGA)  | 2        | 5.26%   |
| 1600x900 (HD+)     | 2        | 5.26%   |
| 1360x768           | 2        | 5.26%   |
| 2560x1440 (QHD)    | 1        | 2.63%   |
| 1680x1050 (WSXGA+) | 1        | 2.63%   |
| 1600x1200          | 1        | 2.63%   |
| 1440x900 (WXGA+)   | 1        | 2.63%   |
| 1366x768 (WXGA)    | 1        | 2.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 8        | 20.51%  |
| 21      | 6        | 15.38%  |
| 24      | 5        | 12.82%  |
| 17      | 5        | 12.82%  |
| Unknown | 4        | 10.26%  |
| 27      | 3        | 7.69%   |
| 23      | 2        | 5.13%   |
| 18      | 2        | 5.13%   |
| 39      | 1        | 2.56%   |
| 37      | 1        | 2.56%   |
| 25      | 1        | 2.56%   |
| 22      | 1        | 2.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 12       | 32.43%  |
| 501-600     | 9        | 24.32%  |
| 301-350     | 5        | 13.51%  |
| 351-400     | 4        | 10.81%  |
| Unknown     | 4        | 10.81%  |
| 801-900     | 2        | 5.41%   |
| 601-700     | 1        | 2.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 21       | 56.76%  |
| 5/4     | 9        | 24.32%  |
| 16/10   | 5        | 13.51%  |
| Unknown | 2        | 5.41%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 33.33%  |
| 151-200        | 8        | 20.51%  |
| 141-150        | 7        | 17.95%  |
| Unknown        | 4        | 10.26%  |
| 301-350        | 3        | 7.69%   |
| 251-300        | 2        | 5.13%   |
| 501-1000       | 2        | 5.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 23       | 65.71%  |
| 101-120 | 6        | 17.14%  |
| Unknown | 4        | 11.43%  |
| 161-240 | 1        | 2.86%   |
| 121-160 | 1        | 2.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 69.77%  |
| 0     | 8        | 18.6%   |
| 2     | 4        | 9.3%    |
| 3     | 1        | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 36.07%  |
| Intel                 | 21       | 34.43%  |
| Broadcom              | 5        | 8.2%    |
| Qualcomm Atheros      | 4        | 6.56%   |
| Mellanox Technologies | 2        | 3.28%   |
| Ralink Technology     | 1        | 1.64%   |
| Qualcomm              | 1        | 1.64%   |
| Nvidia                | 1        | 1.64%   |
| Microchip Technology  | 1        | 1.64%   |
| Edimax Technology     | 1        | 1.64%   |
| D-Link System         | 1        | 1.64%   |
| Brooktrout Technology | 1        | 1.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 14       | 19.72%  |
| Intel Ethernet Connection (2) I219-V                                                  | 5        | 7.04%   |
| Realtek RTL8125 2.5GbE Controller                                                     | 4        | 5.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 4        | 5.63%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2        | 2.82%   |
| Mellanox MT27500 Family [ConnectX-3]                                                  | 2        | 2.82%   |
| Intel I211 Gigabit Network Connection                                                 | 2        | 2.82%   |
| Intel 82567LM-3 Gigabit Network Connection                                            | 2        | 2.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1        | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 1.41%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1        | 1.41%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 1.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1        | 1.41%   |
| Ralink RT5372 Wireless Adapter                                                        | 1        | 1.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                             | 1        | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 1.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 1.41%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 1.41%   |
| Qualcomm ALCATEL Composite RNDIS Interface                                            | 1        | 1.41%   |
| Nvidia MCP73 Ethernet                                                                 | 1        | 1.41%   |
| Microchip MCP2200 USB-to-Serial Port                                                  | 1        | 1.41%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 1.41%   |
| Intel Wireless 7260                                                                   | 1        | 1.41%   |
| Intel Wireless 3165                                                                   | 1        | 1.41%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 1.41%   |
| Intel NM10/ICH7 Family LAN Controller                                                 | 1        | 1.41%   |
| Intel Ethernet Connection I217-LM                                                     | 1        | 1.41%   |
| Intel Ethernet Connection (2) I218-V                                                  | 1        | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 1.41%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 1.41%   |
| Intel 82579V Gigabit Network Connection                                               | 1        | 1.41%   |
| Intel 82574L Gigabit Network Connection                                               | 1        | 1.41%   |
| Intel 82567V-2 Gigabit Network Connection                                             | 1        | 1.41%   |
| Intel 82567LF-2 Gigabit Network Connection                                            | 1        | 1.41%   |
| Intel 82566DM-2 Gigabit Network Connection                                            | 1        | 1.41%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                        | 1        | 1.41%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]                  | 1        | 1.41%   |
| Brooktrout TruFax Board                                                               | 1        | 1.41%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                               | 1        | 1.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 7        | 31.82%  |
| Intel                 | 6        | 27.27%  |
| Qualcomm Atheros      | 3        | 13.64%  |
| Broadcom              | 3        | 13.64%  |
| Ralink Technology     | 1        | 4.55%   |
| Edimax Technology     | 1        | 4.55%   |
| D-Link System         | 1        | 4.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 2        | 9.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1        | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 4.55%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1        | 4.55%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1        | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1        | 4.55%   |
| Ralink RT5372 Wireless Adapter                                                        | 1        | 4.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1        | 4.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1        | 4.55%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 4.55%   |
| Intel Wireless 8265 / 8275                                                            | 1        | 4.55%   |
| Intel Wireless 7260                                                                   | 1        | 4.55%   |
| Intel Wireless 3165                                                                   | 1        | 4.55%   |
| Intel Wi-Fi 6 AX200                                                                   | 1        | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1        | 4.55%   |
| Intel Centrino Wireless-N 105                                                         | 1        | 4.55%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                        | 1        | 4.55%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]                  | 1        | 4.55%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1        | 4.55%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                    | 1        | 4.55%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1        | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 20       | 45.45%  |
| Realtek Semiconductor | 19       | 43.18%  |
| Broadcom              | 2        | 4.55%   |
| Qualcomm Atheros      | 1        | 2.27%   |
| Qualcomm              | 1        | 2.27%   |
| Nvidia                | 1        | 2.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14       | 31.11%  |
| Intel Ethernet Connection (2) I219-V                              | 5        | 11.11%  |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 8.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4        | 8.89%   |
| Intel I211 Gigabit Network Connection                             | 2        | 4.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 4.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 2.22%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 2.22%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 1        | 2.22%   |
| Nvidia MCP73 Ethernet                                             | 1        | 2.22%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.22%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 2.22%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 2.22%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 2.22%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 2.22%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1        | 2.22%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 2.22%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 2.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 42       | 62.69%  |
| WiFi     | 21       | 31.34%  |
| Unknown  | 3        | 4.48%   |
| Modem    | 1        | 1.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 38       | 70.37%  |
| WiFi     | 14       | 25.93%  |
| Unknown  | 2        | 3.7%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 60.47%  |
| 2     | 15       | 34.88%  |
| 4     | 1        | 2.33%   |
| 3     | 1        | 2.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 40       | 93.02%  |
| Yes  | 3        | 6.98%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 5        | 41.67%  |
| Broadcom                        | 2        | 16.67%  |
| Realtek Semiconductor           | 1        | 8.33%   |
| Qualcomm Atheros Communications | 1        | 8.33%   |
| Cambridge Silicon Radio         | 1        | 8.33%   |
| ASUSTek Computer                | 1        | 8.33%   |
| Apple                           | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth wireless interface                  | 3        | 25%     |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 8.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 8.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 8.33%   |
| Intel AX200 Bluetooth                               | 1        | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 8.33%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1        | 8.33%   |
| Broadcom BCM2045 Bluetooth                          | 1        | 8.33%   |
| ASUS Bluetooth Controller                           | 1        | 8.33%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 28       | 38.89%  |
| AMD                 | 19       | 26.39%  |
| Nvidia              | 14       | 19.44%  |
| XMOS                | 2        | 2.78%   |
| Sony                | 2        | 2.78%   |
| C-Media Electronics | 2        | 2.78%   |
| Quanta              | 1        | 1.39%   |
| LG Electronics      | 1        | 1.39%   |
| Creative Technology | 1        | 1.39%   |
| Corsair             | 1        | 1.39%   |
| Audio-Technica      | 1        | 1.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GP106 High Definition Audio Controller                              | 4        | 4.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4        | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4        | 4.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 3.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3        | 3.57%   |
| Intel 200 Series PCH HD Audio                                              | 3        | 3.57%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3        | 3.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 3.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.38%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2        | 2.38%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 2.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2        | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2        | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 2.38%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2        | 2.38%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.38%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2        | 2.38%   |
| XMOS XMOS XS1-U8 MFA (ST)                                                  | 1        | 1.19%   |
| XMOS Shanling UA2                                                          | 1        | 1.19%   |
| Sony Sony Audio                                                            | 1        | 1.19%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1        | 1.19%   |
| Quanta USB Audio Realtek USB2.0 Audio Microphone                           | 1        | 1.19%   |
| Nvidia MCP73 High Definition Audio                                         | 1        | 1.19%   |
| Nvidia MCP61 High Definition Audio                                         | 1        | 1.19%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.19%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.19%   |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 1.19%   |
| LG Electronics USB Audio LG UltraFine Display Audio                        | 1        | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 1.19%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 1        | 1.19%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 1        | 1.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1        | 1.19%   |
| Creative Technology Sound Blaster Omni Surround 5.1                        | 1        | 1.19%   |
| Corsair Corsair VOID PRO Wireless Gaming Headset                           | 1        | 1.19%   |
| Corsair Corsair ST100 Headset Output                                       | 1        | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 8        | 16.33%  |
| Unknown             | 7        | 14.29%  |
| SK hynix            | 6        | 12.24%  |
| Micron Technology   | 6        | 12.24%  |
| G.Skill             | 5        | 10.2%   |
| Corsair             | 5        | 10.2%   |
| Samsung Electronics | 4        | 8.16%   |
| Crucial             | 3        | 6.12%   |
| Nanya Technology    | 2        | 4.08%   |
| Elpida              | 2        | 4.08%   |
| EVGA                | 1        | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 2        | 3.85%   |
| Micron RAM ITC 4096MB DIMM DDR3 1066MT/s                | 2        | 3.85%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 2933MT/s   | 2        | 3.85%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 1.92%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1        | 1.92%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                | 1        | 1.92%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s             | 1        | 1.92%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s             | 1        | 1.92%   |
| SK hynix RAM Zhidian4GDDR800000 4GB DIMM DDR2 800MT/s   | 1        | 1.92%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.92%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 1.92%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1067MT/s    | 1        | 1.92%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s    | 1        | 1.92%   |
| SK hynix RAM HMT31GR7AFR4C-H9 8GB DIMM DDR3 1333MT/s    | 1        | 1.92%   |
| SK hynix RAM HMT125U6AFP8C-G7 2048MB DIMM DDR3 1066MT/s | 1        | 1.92%   |
| SK hynix RAM HMT112U6AFP8C-G7 1GB DIMM 1066MT/s         | 1        | 1.92%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s   | 1        | 1.92%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1        | 1.92%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.92%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s     | 1        | 1.92%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s      | 1        | 1.92%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 800MT/s    | 1        | 1.92%   |
| Micron RAM 8HTF12864AZ-800H1 1GB DIMM DDR2 800MT/s      | 1        | 1.92%   |
| Micron RAM 36JSZF1G72PZ-1G4D 8GB DIMM DDR3 1333MT/s     | 1        | 1.92%   |
| Micron RAM 36JSF1G72PZ-1 8GB DIMM DDR3 1600MT/s         | 1        | 1.92%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s    | 1        | 1.92%   |
| Kingston RAM KY996D-ELD 2GB DIMM 1066MT/s               | 1        | 1.92%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s       | 1        | 1.92%   |
| Kingston RAM KHX2400C15D4/8G 8192MB DIMM DDR4 2400MT/s  | 1        | 1.92%   |
| Kingston RAM K531R8-ETB 4GB DIMM DDR3 1600MT/s          | 1        | 1.92%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1067MT/s  | 1        | 1.92%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s  | 1        | 1.92%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s  | 1        | 1.92%   |
| G.Skill RAM F4-3600C18-8GTZN 8192MB DIMM DDR4 3600MT/s  | 1        | 1.92%   |
| G.Skill RAM F4-3600C17-16GTZSW 16GB DIMM DDR4 3600MT/s  | 1        | 1.92%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s     | 1        | 1.92%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3000MT/s     | 1        | 1.92%   |
| G.Skill RAM F4-2400C17-8GVR 8192MB DIMM DDR4 2400MT/s   | 1        | 1.92%   |
| EVGA RAM 8GX-D4-3200-MR 8192MB DIMM DDR4 3200MT/s       | 1        | 1.92%   |
| Elpida RAM EBJ21UE8BAFA-AE-E 2GB DIMM 1066MT/s          | 1        | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 17       | 36.96%  |
| DDR3    | 17       | 36.96%  |
| DDR2    | 8        | 17.39%  |
| Unknown | 2        | 4.35%   |
| SDRAM   | 1        | 2.17%   |
| DDR     | 1        | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 41       | 93.18%  |
| SODIMM | 3        | 6.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 33.33%  |
| 4096  | 12       | 25%     |
| 2048  | 10       | 20.83%  |
| 16384 | 5        | 10.42%  |
| 1024  | 5        | 10.42%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 7        | 15.22%  |
| 2400    | 6        | 13.04%  |
| 1333    | 6        | 13.04%  |
| 800     | 6        | 13.04%  |
| 3200    | 4        | 8.7%    |
| 1066    | 4        | 8.7%    |
| 2933    | 3        | 6.52%   |
| 3600    | 2        | 4.35%   |
| 2667    | 2        | 4.35%   |
| 1067    | 2        | 4.35%   |
| 3000    | 1        | 2.17%   |
| 667     | 1        | 2.17%   |
| 533     | 1        | 2.17%   |
| Unknown | 1        | 2.17%   |

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
| 1     | 20       | 46.51%  |
| 2     | 12       | 27.91%  |
| 0     | 9        | 20.93%  |
| 3     | 2        | 4.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 23       | 46%     |
| Firewire controller      | 12       | 24%     |
| Net/wireless             | 7        | 14%     |
| Network                  | 4        | 8%      |
| Sound                    | 2        | 4%      |
| Bluetooth                | 2        | 4%      |

