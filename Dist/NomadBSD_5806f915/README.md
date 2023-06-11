NomadBSD 5806f915 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for NomadBSD 5806f915.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NomadBSD_5806f915/Desktop/README.md) and [notebooks](/Dist/NomadBSD_5806f915/Notebook/README.md).

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

Total: 67

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [17d766d55a](https://bsd-hardware.info/?probe=17d766d55a) | Oct 08, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [91a1870b65](https://bsd-hardware.info/?probe=91a1870b65) | Sep 01, 2022 |
| Lenovo        | ThinkPad T480 20L50000GE    | Notebook    | [cd7d7d83ba](https://bsd-hardware.info/?probe=cd7d7d83ba) | Aug 20, 2022 |
| Lenovo        | ThinkPad T480 20L6SB2N00    | Notebook    | [995a8a5e6f](https://bsd-hardware.info/?probe=995a8a5e6f) | Jul 16, 2022 |
| Lenovo        | V580 20147                  | Notebook    | [0615e8260d](https://bsd-hardware.info/?probe=0615e8260d) | Jul 02, 2022 |
| Lenovo        | V580 20147                  | Notebook    | [6f1fd71366](https://bsd-hardware.info/?probe=6f1fd71366) | Jul 02, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [4e6381e037](https://bsd-hardware.info/?probe=4e6381e037) | Jun 22, 2022 |
| HP            | 2B29                        | Desktop     | [e8c355314e](https://bsd-hardware.info/?probe=e8c355314e) | Jun 17, 2022 |
| HP            | 1589                        | Desktop     | [3765f1cb09](https://bsd-hardware.info/?probe=3765f1cb09) | Jun 17, 2022 |
| Dell          | 0Y2G6P A03                  | Server      | [ecb370bba4](https://bsd-hardware.info/?probe=ecb370bba4) | Jun 17, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [004e039a23](https://bsd-hardware.info/?probe=004e039a23) | May 19, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [555a7733b7](https://bsd-hardware.info/?probe=555a7733b7) | May 19, 2022 |
| Dell          | Latitude 5290               | Notebook    | [11c3db8f1b](https://bsd-hardware.info/?probe=11c3db8f1b) | Apr 23, 2022 |
| Notebook      | W650DC,DD                   | Notebook    | [0f474b9ebb](https://bsd-hardware.info/?probe=0f474b9ebb) | Apr 23, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [c4f7b8a774](https://bsd-hardware.info/?probe=c4f7b8a774) | Apr 22, 2022 |
| Dell          | Studio 1555                 | Notebook    | [6da8f97bcd](https://bsd-hardware.info/?probe=6da8f97bcd) | Apr 22, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [c776760a11](https://bsd-hardware.info/?probe=c776760a11) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [c052d7cab0](https://bsd-hardware.info/?probe=c052d7cab0) | Apr 01, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [95646c7b48](https://bsd-hardware.info/?probe=95646c7b48) | Mar 25, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [09116f9139](https://bsd-hardware.info/?probe=09116f9139) | Mar 24, 2022 |
| ASUSTek       | M51Sr                       | Notebook    | [936a577d1a](https://bsd-hardware.info/?probe=936a577d1a) | Mar 10, 2022 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [2af47b6502](https://bsd-hardware.info/?probe=2af47b6502) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | Desktop     | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| Dell          | Latitude D630               | Notebook    | [ae56d2cedd](https://bsd-hardware.info/?probe=ae56d2cedd) | Feb 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e27a6f46fc](https://bsd-hardware.info/?probe=e27a6f46fc) | Feb 26, 2022 |
| Gigabyte      | X570S GAMING X              | Desktop     | [ff39ace6ec](https://bsd-hardware.info/?probe=ff39ace6ec) | Feb 16, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [766e62f699](https://bsd-hardware.info/?probe=766e62f699) | Feb 12, 2022 |
| HP            | Notebook                    | Notebook    | [1758596e26](https://bsd-hardware.info/?probe=1758596e26) | Feb 12, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24f3a7da57](https://bsd-hardware.info/?probe=24f3a7da57) | Feb 07, 2022 |
| Intel         | DCP847SKE                   | Desktop     | [2828ef2a6d](https://bsd-hardware.info/?probe=2828ef2a6d) | Jan 20, 2022 |
| ASUSTek       | 1000                        | Notebook    | [da8689c840](https://bsd-hardware.info/?probe=da8689c840) | Dec 08, 2021 |
| Dell          | 0M9KCM A01                  | Desktop     | [4db0a0ea05](https://bsd-hardware.info/?probe=4db0a0ea05) | Dec 06, 2021 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [e713e3adee](https://bsd-hardware.info/?probe=e713e3adee) | Dec 05, 2021 |
| HP            | ProBook x360 11 G6 EE       | Convertible | [7eaff44a64](https://bsd-hardware.info/?probe=7eaff44a64) | Nov 27, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1bd9270845](https://bsd-hardware.info/?probe=1bd9270845) | Nov 15, 2021 |
| Acer          | Aspire 3810T                | Notebook    | [86782a69be](https://bsd-hardware.info/?probe=86782a69be) | Nov 13, 2021 |
| Acer          | Aspire 3810T                | Notebook    | [608e43163d](https://bsd-hardware.info/?probe=608e43163d) | Nov 12, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [ae2203b146](https://bsd-hardware.info/?probe=ae2203b146) | Nov 12, 2021 |
| Unknown       | X79                         | Desktop     | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [1d261120d3](https://bsd-hardware.info/?probe=1d261120d3) | Nov 06, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [767b44a6ae](https://bsd-hardware.info/?probe=767b44a6ae) | Oct 30, 2021 |
| ASUSTek       | X202E                       | Notebook    | [54259ac9a1](https://bsd-hardware.info/?probe=54259ac9a1) | Oct 29, 2021 |
| Sony          | VJS121C11N                  | Notebook    | [d86c621ef0](https://bsd-hardware.info/?probe=d86c621ef0) | Oct 25, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [2d72b6939d](https://bsd-hardware.info/?probe=2d72b6939d) | Oct 24, 2021 |
| HP            | 87D6 SMVB                   | Desktop     | [f601f00e7c](https://bsd-hardware.info/?probe=f601f00e7c) | Oct 07, 2021 |
| Dell          | OptiPlex 3020               | Desktop     | [c391177240](https://bsd-hardware.info/?probe=c391177240) | Oct 05, 2021 |
| Dell          | OptiPlex 3020               | Desktop     | [070a0c6d62](https://bsd-hardware.info/?probe=070a0c6d62) | Sep 19, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [c5751c736c](https://bsd-hardware.info/?probe=c5751c736c) | Sep 19, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [d8f8901ae7](https://bsd-hardware.info/?probe=d8f8901ae7) | Sep 19, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | Notebook    | [b00c8e76e8](https://bsd-hardware.info/?probe=b00c8e76e8) | Aug 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [f1dc5150c2](https://bsd-hardware.info/?probe=f1dc5150c2) | Aug 13, 2021 |
| HP            | 2000                        | Notebook    | [d2240a960b](https://bsd-hardware.info/?probe=d2240a960b) | Aug 05, 2021 |
| HP            | 2000                        | Notebook    | [65d183fe41](https://bsd-hardware.info/?probe=65d183fe41) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | Notebook    | [39ef89f214](https://bsd-hardware.info/?probe=39ef89f214) | Aug 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0M... | Notebook    | [4e7ace8a39](https://bsd-hardware.info/?probe=4e7ace8a39) | Aug 04, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [3348992bef](https://bsd-hardware.info/?probe=3348992bef) | Jul 23, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [77676fbcfc](https://bsd-hardware.info/?probe=77676fbcfc) | Jul 18, 2021 |
| Dell          | Inspiron 15-5568            | Notebook    | [3ed52ae70d](https://bsd-hardware.info/?probe=3ed52ae70d) | Jul 01, 2021 |
| Gigabyte      | Z370 AORUS ULTRAGAMING W... | Desktop     | [13371b2ab8](https://bsd-hardware.info/?probe=13371b2ab8) | Jun 27, 2021 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [e91dc55970](https://bsd-hardware.info/?probe=e91dc55970) | Jun 22, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [46bf9edc63](https://bsd-hardware.info/?probe=46bf9edc63) | Jun 17, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [dbda48cff7](https://bsd-hardware.info/?probe=dbda48cff7) | Jun 17, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [dab0ca2417](https://bsd-hardware.info/?probe=dab0ca2417) | Jun 01, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [c6a1c1fa15](https://bsd-hardware.info/?probe=c6a1c1fa15) | May 25, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [96cc0c27b0](https://bsd-hardware.info/?probe=96cc0c27b0) | May 25, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [8cf113ac55](https://bsd-hardware.info/?probe=8cf113ac55) | May 22, 2021 |
| Toshiba       | STI 005492G                 | Desktop     | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 52        | 96.3%   |
| i386  | 2         | 3.7%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Openbox | 53        | 98.15%  |
| KDE5    | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 54        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 53        | 98.15%  |
| SDDM | 1         | 1.85%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 27        | 49.09%  |
| de_DE   | 6         | 10.91%  |
| Unknown | 5         | 9.09%   |
| ru_RU   | 4         | 7.27%   |
| en_GB   | 4         | 7.27%   |
| zh_CN   | 2         | 3.64%   |
| pt_BR   | 2         | 3.64%   |
| pl_PL   | 1         | 1.82%   |
| fr_FR   | 1         | 1.82%   |
| fi_FI   | 1         | 1.82%   |
| es_ES   | 1         | 1.82%   |
| en_AU   | 1         | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 53        | 98.15%  |
| BIOS | 1         | 1.85%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 50        | 92.59%  |
| Zfs  | 4         | 7.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 44        | 81.48%  |
| MBR  | 10        | 18.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 13        | 24.07%  |
| ASUSTek Computer    | 10        | 18.52%  |
| Lenovo              | 8         | 14.81%  |
| Dell                | 8         | 14.81%  |
| Gigabyte Technology | 3         | 5.56%   |
| TUXEDO              | 2         | 3.7%    |
| Intel               | 2         | 3.7%    |
| Sony                | 1         | 1.85%   |
| Semp Toshiba        | 1         | 1.85%   |
| Notebook            | 1         | 1.85%   |
| Fujitsu Siemens     | 1         | 1.85%   |
| ASRock              | 1         | 1.85%   |
| Apple               | 1         | 1.85%   |
| Acer                | 1         | 1.85%   |
| Unknown             | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| TUXEDO Pulse 15 Gen2                    | 1         | 1.85%   |
| TUXEDO InfinityBook S 15 Gen6           | 1         | 1.85%   |
| Sony VJS121C11N                         | 1         | 1.85%   |
| Semp Toshiba STI                        | 1         | 1.85%   |
| Notebook W650DC,DD                      | 1         | 1.85%   |
| Lenovo V580 20147                       | 1         | 1.85%   |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK    | 1         | 1.85%   |
| Lenovo ThinkPad T490s 20NX000DRT        | 1         | 1.85%   |
| Lenovo ThinkPad T480 20L50000GE         | 1         | 1.85%   |
| Lenovo ThinkPad T470s W10DG 20JS001FGE  | 1         | 1.85%   |
| Lenovo ThinkPad T440s 20AQ006HUS        | 1         | 1.85%   |
| Lenovo ThinkPad S1 Yoga 20C0S0M300      | 1         | 1.85%   |
| Lenovo Legion Y7000 2019 PG0 81T0       | 1         | 1.85%   |
| Intel NUC6i5SYB H81131-502              | 1         | 1.85%   |
| Intel DCP847SKE                         | 1         | 1.85%   |
| HP ZBook Studio G3                      | 1         | 1.85%   |
| HP Z420 Workstation                     | 1         | 1.85%   |
| HP ProBook x360 11 G6 EE                | 1         | 1.85%   |
| HP ProBook 450 G2                       | 1         | 1.85%   |
| HP Pavilion Notebook                    | 1         | 1.85%   |
| HP Pavilion g6                          | 1         | 1.85%   |
| HP OMEN by HP Laptop 17-cb1xxx          | 1         | 1.85%   |
| HP Notebook                             | 1         | 1.85%   |
| HP Laptop 15-db0xxx                     | 1         | 1.85%   |
| HP Desktop M01-F1xxx                    | 1         | 1.85%   |
| HP 550-a114                             | 1         | 1.85%   |
| HP 255 G8 Notebook PC                   | 1         | 1.85%   |
| HP 2000                                 | 1         | 1.85%   |
| Gigabyte Z370 AORUS ULTRAGAMING WIFI-OP | 1         | 1.85%   |
| Gigabyte X570S GAMING X                 | 1         | 1.85%   |
| Gigabyte MZGLKBP-00                     | 1         | 1.85%   |
| Fujitsu Siemens AMILO PRO V3515         | 1         | 1.85%   |
| Dell Studio 1555                        | 1         | 1.85%   |
| Dell PowerEdge T410                     | 1         | 1.85%   |
| Dell OptiPlex 9010                      | 1         | 1.85%   |
| Dell OptiPlex 3020                      | 1         | 1.85%   |
| Dell OptiPlex 3010                      | 1         | 1.85%   |
| Dell Latitude D630                      | 1         | 1.85%   |
| Dell Latitude 5290                      | 1         | 1.85%   |
| Dell Inspiron 15-5568                   | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 6         | 11.11%  |
| Dell OptiPlex         | 3         | 5.56%   |
| HP ProBook            | 2         | 3.7%    |
| HP Pavilion           | 2         | 3.7%    |
| Dell Latitude         | 2         | 3.7%    |
| ASUS TUF              | 2         | 3.7%    |
| TUXEDO Pulse          | 1         | 1.85%   |
| TUXEDO InfinityBook   | 1         | 1.85%   |
| Sony VJS121C11N       | 1         | 1.85%   |
| Semp Toshiba STI      | 1         | 1.85%   |
| Notebook W650DC       | 1         | 1.85%   |
| Lenovo V580           | 1         | 1.85%   |
| Lenovo Legion         | 1         | 1.85%   |
| Intel NUC6i5SYB       | 1         | 1.85%   |
| Intel DCP847SKE       | 1         | 1.85%   |
| HP ZBook              | 1         | 1.85%   |
| HP Z420               | 1         | 1.85%   |
| HP OMEN               | 1         | 1.85%   |
| HP Notebook           | 1         | 1.85%   |
| HP Laptop             | 1         | 1.85%   |
| HP Desktop            | 1         | 1.85%   |
| HP 550-a114           | 1         | 1.85%   |
| HP 255                | 1         | 1.85%   |
| HP 2000               | 1         | 1.85%   |
| Gigabyte Z370         | 1         | 1.85%   |
| Gigabyte X570S        | 1         | 1.85%   |
| Gigabyte MZGLKBP-00   | 1         | 1.85%   |
| Fujitsu Siemens AMILO | 1         | 1.85%   |
| Dell Studio           | 1         | 1.85%   |
| Dell PowerEdge        | 1         | 1.85%   |
| Dell Inspiron         | 1         | 1.85%   |
| ASUS X540YA           | 1         | 1.85%   |
| ASUS X202E            | 1         | 1.85%   |
| ASUS V-P7H55E         | 1         | 1.85%   |
| ASUS ROG              | 1         | 1.85%   |
| ASUS PRIME            | 1         | 1.85%   |
| ASUS Maximus          | 1         | 1.85%   |
| ASUS M51Sr            | 1         | 1.85%   |
| ASUS 1000             | 1         | 1.85%   |
| ASRock B550           | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 9         | 16.67%  |
| 2019 | 9         | 16.67%  |
| 2020 | 5         | 9.26%   |
| 2017 | 5         | 9.26%   |
| 2015 | 4         | 7.41%   |
| 2022 | 3         | 5.56%   |
| 2018 | 3         | 5.56%   |
| 2013 | 3         | 5.56%   |
| 2012 | 3         | 5.56%   |
| 2009 | 3         | 5.56%   |
| 2008 | 3         | 5.56%   |
| 2014 | 1         | 1.85%   |
| 2011 | 1         | 1.85%   |
| 2010 | 1         | 1.85%   |
| 2006 | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 32        | 59.26%  |
| Desktop     | 18        | 33.33%  |
| Convertible | 2         | 3.7%    |
| Mini pc     | 1         | 1.85%   |
| Server      | 1         | 1.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 20        | 37.04%  |
| 16.01-24.0  | 13        | 24.07%  |
| 4.01-8.0    | 8         | 14.81%  |
| 32.01-64.0  | 6         | 11.11%  |
| 64.01-256.0 | 4         | 7.41%   |
| 2.01-3.0    | 2         | 3.7%    |
| 24.01-32.0  | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 20        | 37.04%  |
| 0.51-1.0 | 18        | 33.33%  |
| 1.01-2.0 | 13        | 24.07%  |
| 4.01-8.0 | 1         | 1.85%   |
| 3.01-4.0 | 1         | 1.85%   |
| 2.01-3.0 | 1         | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 33        | 60%     |
| 2      | 14        | 25.45%  |
| 3      | 6         | 10.91%  |
| 4      | 2         | 3.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 61.11%  |
| Yes       | 21        | 38.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 94.44%  |
| No        | 3         | 5.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 85.19%  |
| No        | 8         | 14.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 58.18%  |
| No        | 23        | 41.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| USA       | 16        | 29.63%  |
| Germany   | 8         | 14.81%  |
| Russia    | 6         | 11.11%  |
| Mexico    | 3         | 5.56%   |
| Thailand  | 2         | 3.7%    |
| Romania   | 2         | 3.7%    |
| Norway    | 2         | 3.7%    |
| Japan     | 2         | 3.7%    |
| China     | 2         | 3.7%    |
| Brazil    | 2         | 3.7%    |
| Spain     | 1         | 1.85%   |
| Slovakia  | 1         | 1.85%   |
| Poland    | 1         | 1.85%   |
| Italy     | 1         | 1.85%   |
| France    | 1         | 1.85%   |
| Finland   | 1         | 1.85%   |
| Denmark   | 1         | 1.85%   |
| Belarus   | 1         | 1.85%   |
| Australia | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Whittier              | 3         | 5.56%   |
| Tijuana               | 3         | 5.56%   |
| Duncan                | 3         | 5.56%   |
| Volzhskiy             | 2         | 3.7%    |
| Vollen                | 2         | 3.7%    |
| Setagaya-ku           | 2         | 3.7%    |
| Rio de Janeiro        | 2         | 3.7%    |
| Moscow                | 2         | 3.7%    |
| Drobeta-Turnu Severin | 2         | 3.7%    |
| Cologne               | 2         | 3.7%    |
| Changzhou             | 2         | 3.7%    |
| Bangkok               | 2         | 3.7%    |
| Wloszczowa            | 1         | 1.85%   |
| Winter Haven          | 1         | 1.85%   |
| Ufa                   | 1         | 1.85%   |
| Tucson                | 1         | 1.85%   |
| Trieste               | 1         | 1.85%   |
| Syracuse              | 1         | 1.85%   |
| Sedavi                | 1         | 1.85%   |
| Scottsdale            | 1         | 1.85%   |
| San Francisco         | 1         | 1.85%   |
| San Bernardino        | 1         | 1.85%   |
| Palmer                | 1         | 1.85%   |
| Palm Bay              | 1         | 1.85%   |
| Novosibirsk           | 1         | 1.85%   |
| Münster              | 1         | 1.85%   |
| Mogilev               | 1         | 1.85%   |
| Melcice               | 1         | 1.85%   |
| Marburg               | 1         | 1.85%   |
| Helsinki              | 1         | 1.85%   |
| Hadenfeld             | 1         | 1.85%   |
| Greifswald            | 1         | 1.85%   |
| Fontenay-sous-Bois    | 1         | 1.85%   |
| DÃ¼sseldorf         | 1         | 1.85%   |
| Cupertino             | 1         | 1.85%   |
| Copenhagen            | 1         | 1.85%   |
| Conway                | 1         | 1.85%   |
| Brisbane              | 1         | 1.85%   |
| Berlin                | 1         | 1.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 17     | 19.23%  |
| Samsung Electronics | 14        | 18     | 17.95%  |
| Seagate             | 9         | 10     | 11.54%  |
| Crucial             | 7         | 7      | 8.97%   |
| Toshiba             | 5         | 7      | 6.41%   |
| SK hynix            | 4         | 4      | 5.13%   |
| Kingston            | 3         | 3      | 3.85%   |
| Intel               | 3         | 3      | 3.85%   |
| A-DATA Technology   | 3         | 3      | 3.85%   |
| SanDisk             | 2         | 2      | 2.56%   |
| PNY                 | 2         | 2      | 2.56%   |
| Hewlett-Packard     | 2         | 2      | 2.56%   |
| Apple               | 2         | 2      | 2.56%   |
| Transcend           | 1         | 1      | 1.28%   |
| Team                | 1         | 1      | 1.28%   |
| SPCC                | 1         | 1      | 1.28%   |
| Micron Technology   | 1         | 1      | 1.28%   |
| HGST                | 1         | 1      | 1.28%   |
| Gigabyte Technology | 1         | 1      | 1.28%   |
| ASUSTek Computer    | 1         | 2      | 1.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| WDC WDS100T1X0E-00AFY0 1TB                | 2         | 2.44%   |
| WDC WD40PURX-64GVNY0 4TB                  | 2         | 2.44%   |
| Seagate ST9500325AS 500GB                 | 2         | 2.44%   |
| SanDisk SSD U100 24GB                     | 2         | 2.44%   |
| Kingston SA400S37480G 480GB               | 2         | 2.44%   |
| HP SSD EX950 2TB                          | 2         | 2.44%   |
| Crucial CT1000P1SSD8 1TB                  | 2         | 2.44%   |
| A-DATA SU630 240GB                        | 2         | 2.44%   |
| WDC WDS120G2G0A-00JH30 120GB              | 1         | 1.22%   |
| WDC WD60EZRZ-00GZ5B1 6TB                  | 1         | 1.22%   |
| WDC WD3200BEVT-75ZCT2 320GB               | 1         | 1.22%   |
| WDC WD2500BEKT-00PVMT0 250GB              | 1         | 1.22%   |
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 1.22%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 1.22%   |
| WDC WD10SMRW-11Y43S0 1TB                  | 1         | 1.22%   |
| WDC WD10JPVX-60JC3T0 1TB                  | 1         | 1.22%   |
| WDC WD10JPVT-08A1YT2 1TB                  | 1         | 1.22%   |
| WDC WD10EADS-00P8B0 1TB                   | 1         | 1.22%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB        | 1         | 1.22%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB      | 1         | 1.22%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1         | 1.22%   |
| Transcend TS512GSSD370S 512GB             | 1         | 1.22%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.22%   |
| Toshiba MK1637GSX 160GB                   | 1         | 1.22%   |
| Toshiba MG06ACA800E 8TB                   | 1         | 1.22%   |
| Toshiba KXG5AZNV256G 256GB                | 1         | 1.22%   |
| Toshiba HDWD120 2TB                       | 1         | 1.22%   |
| Team TEAML5Lite3D1T 1TB                   | 1         | 1.22%   |
| SPCC Solid State Disk 240GB               | 1         | 1.22%   |
| SK hynix SKHynix_HFS512GD9TNG-L5B0B 512GB | 1         | 1.22%   |
| SK hynix SKHynix_HFS256GD9TNI-L2B0B 256GB | 1         | 1.22%   |
| SK hynix SHGS31-500GS-2 500GB             | 1         | 1.22%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB   | 1         | 1.22%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 1.22%   |
| Seagate ST500LM030-2E717D 500GB           | 1         | 1.22%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1.22%   |
| Seagate ST4000DM000-2AE166 4TB            | 1         | 1.22%   |
| Seagate ST3000DM008-2DM166 3TB            | 1         | 1.22%   |
| Seagate ST2000LM007-1R8174 2TB            | 1         | 1.22%   |
| Seagate ST2000DM001-1CH164 2TB            | 1         | 1.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 39.29%  |
| Seagate             | 9         | 10     | 32.14%  |
| Toshiba             | 4         | 5      | 14.29%  |
| Samsung Electronics | 2         | 2      | 7.14%   |
| HGST                | 1         | 1      | 3.57%   |
| Apple               | 1         | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 18.52%  |
| Crucial             | 4         | 4      | 14.81%  |
| A-DATA Technology   | 3         | 3      | 11.11%  |
| SanDisk             | 2         | 2      | 7.41%   |
| PNY                 | 2         | 2      | 7.41%   |
| Kingston            | 2         | 2      | 7.41%   |
| WDC                 | 1         | 1      | 3.7%    |
| Transcend           | 1         | 1      | 3.7%    |
| Team                | 1         | 1      | 3.7%    |
| SPCC                | 1         | 1      | 3.7%    |
| SK hynix            | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |
| Gigabyte Technology | 1         | 1      | 3.7%    |
| ASUSTek Computer    | 1         | 2      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 30     | 36.23%  |
| NVMe | 22        | 29     | 31.88%  |
| SSD  | 22        | 29     | 31.88%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 42        | 59     | 65.63%  |
| NVMe | 22        | 29     | 34.38%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 37     | 58.33%  |
| 0.51-1.0   | 11        | 11     | 22.92%  |
| 1.01-2.0   | 4         | 4      | 8.33%   |
| 3.01-4.0   | 3         | 3      | 6.25%   |
| 2.01-3.0   | 1         | 1      | 2.08%   |
| 4.01-10.0  | 1         | 3      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 48        | 88.89%  |
| 101-250    | 4         | 7.41%   |
| 251-500    | 1         | 1.85%   |
| 51-100     | 1         | 1.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 53        | 98.15%  |
| 51-100  | 1         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD40PURX-64GVNY0 4TB          | 1         | 1      | 12.5%   |
| WDC WD1200BEVS-07LAT0 120GB       | 1         | 1      | 12.5%   |
| WDC WD10JPVX-60JC3T0 1TB          | 1         | 1      | 12.5%   |
| Toshiba HDWD120 2TB               | 1         | 1      | 12.5%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 12.5%   |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 12.5%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 12.5%   |
| A-DATA Technology XM13 32GB       | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 37.5%   |
| Toshiba             | 1         | 1      | 12.5%   |
| Seagate             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| HGST                | 1         | 1      | 12.5%   |
| A-DATA Technology   | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 42.86%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 85.71%  |
| SSD  | 1         | 1      | 14.29%  |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 48        | 78     | 85.71%  |
| Malfunc  | 7         | 8      | 12.5%   |
| Detected | 1         | 2      | 1.79%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 33        | 45.21%  |
| AMD                         | 12        | 16.44%  |
| Samsung Electronics         | 9         | 12.33%  |
| SanDisk                     | 5         | 6.85%   |
| Micron/Crucial Technology   | 3         | 4.11%   |
| SK hynix                    | 2         | 2.74%   |
| Biwin Storage Technology    | 2         | 2.74%   |
| ASMedia Technology          | 2         | 2.74%   |
| VIA Technologies            | 1         | 1.37%   |
| Toshiba                     | 1         | 1.37%   |
| Micron Technology           | 1         | 1.37%   |
| Kingston Technology Company | 1         | 1.37%   |
| JMicron Technology          | 1         | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 9         | 11.11%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 5         | 6.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 4         | 4.94%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 3         | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 3         | 3.7%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                    | 2         | 2.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 2.47%   |
| Micron/Crucial NVMe Storage Controller                                        | 2         | 2.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 2         | 2.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 2         | 2.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 2         | 2.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 2         | 2.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 2         | 2.47%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 2         | 2.47%   |
| AMD 500 Series Chipset SATA Controller                                        | 2         | 2.47%   |
| Unknown                                                                       | 2         | 2.47%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1         | 1.23%   |
| VIA VT8237A SATA 2-Port Controller                                            | 1         | 1.23%   |
| Toshiba XG5 NVMe SSD Controller                                               | 1         | 1.23%   |
| SK hynix hynix unknown                                                        | 1         | 1.23%   |
| SK hynix BC511                                                                | 1         | 1.23%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                     | 1         | 1.23%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                               | 1         | 1.23%   |
| SanDisk PC SN520 NVMe SSD                                                     | 1         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 1         | 1.23%   |
| Samsung Apple PCIe SSD                                                        | 1         | 1.23%   |
| Micron/Crucial P1 NVMe PCIe SSD                                               | 1         | 1.23%   |
| Micron NVMe Storage Controller                                                | 1         | 1.23%   |
| Kingston Company A2000 NVMe SSD                                               | 1         | 1.23%   |
| JMicron JMB360 AHCI Controller                                                | 1         | 1.23%   |
| Intel SSD 660P Series                                                         | 1         | 1.23%   |
| Intel NVMe Optane Memory Series                                               | 1         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 1         | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                    | 1         | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.23%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 1         | 1.23%   |
| Intel C600/X79 series chipset SATA RAID Controller                            | 1         | 1.23%   |
| Intel C600/X79 series chipset IDE-r Controller                                | 1         | 1.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 39        | 54.17%  |
| NVMe | 22        | 30.56%  |
| IDE  | 8         | 11.11%  |
| RAID | 2         | 2.78%   |
| SAS  | 1         | 1.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 41        | 75.93%  |
| AMD    | 13        | 24.07%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor         | 2         | 3.7%    |
| AMD A8-7410 APU with AMD Radeon R5 Graphics | 2         | 3.7%    |
| Intel Xeon CPU E5640 @ 2.67GHz              | 1         | 1.85%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1         | 1.85%   |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz         | 1         | 1.85%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 1.85%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 1.85%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 1.85%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 1.85%   |
| Intel CPU Version                           | 1         | 1.85%   |
| Intel Core i9-7960X CPU @ 2.80GHz           | 1         | 1.85%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1         | 1.85%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 1.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.85%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 1.85%   |
| Intel Core i7-4650U CPU @ 1.70GHz           | 1         | 1.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.85%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.85%   |
| Intel Core i5-9300HF CPU @ 2.40GHz          | 1         | 1.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 1.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.85%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.85%   |
| Intel Core i5-6260U CPU @ 1.80GHz           | 1         | 1.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 1.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.85%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1         | 1.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.85%   |
| Intel Core i5-10210Y CPU @ 1.00GHz          | 1         | 1.85%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1         | 1.85%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 1         | 1.85%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1         | 1.85%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.85%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 1         | 1.85%   |
| Intel Core 2 Duo                            | 1         | 1.85%   |
| Intel Celeron M CPU                         | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 14        | 25.93%  |
| Intel Core i7           | 8         | 14.81%  |
| Intel Xeon              | 4         | 7.41%   |
| Intel Core i3           | 4         | 7.41%   |
| Other                   | 3         | 5.56%   |
| AMD Ryzen 5             | 3         | 5.56%   |
| AMD A8                  | 3         | 5.56%   |
| Intel Core 2 Duo        | 2         | 3.7%    |
| AMD Ryzen 9             | 2         | 3.7%    |
| AMD Ryzen 7             | 2         | 3.7%    |
| AMD A6                  | 2         | 3.7%    |
| Intel Pentium Silver    | 1         | 1.85%   |
| Intel Pentium Dual-Core | 1         | 1.85%   |
| Intel Genuine           | 1         | 1.85%   |
| Intel Core i9           | 1         | 1.85%   |
| Intel Celeron M         | 1         | 1.85%   |
| Intel Celeron           | 1         | 1.85%   |
| Intel Atom              | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 21        | 38.89%  |
| 2       | 17        | 31.48%  |
| 12      | 3         | 5.56%   |
| 8       | 3         | 5.56%   |
| Unknown | 3         | 5.56%   |
| 24      | 2         | 3.7%    |
| 16      | 2         | 3.7%    |
| 6       | 2         | 3.7%    |
| 1       | 1         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 27        | 50%     |
| 1       | 23        | 42.59%  |
| Unknown | 4         | 7.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 10        | 18.52%  |
| Skylake       | 6         | 11.11%  |
| IvyBridge     | 6         | 11.11%  |
| Haswell       | 5         | 9.26%   |
| Puma          | 4         | 7.41%   |
| Penryn        | 4         | 7.41%   |
| Zen 3         | 2         | 3.7%    |
| Zen 2         | 2         | 3.7%    |
| SandyBridge   | 2         | 3.7%    |
| Unknown       | 2         | 3.7%    |
| Zen+          | 1         | 1.85%   |
| Westmere      | 1         | 1.85%   |
| TigerLake     | 1         | 1.85%   |
| P6            | 1         | 1.85%   |
| Nehalem       | 1         | 1.85%   |
| K10 Llano     | 1         | 1.85%   |
| Goldmont plus | 1         | 1.85%   |
| Excavator     | 1         | 1.85%   |
| Core          | 1         | 1.85%   |
| CometLake     | 1         | 1.85%   |
| Bonnell       | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 28        | 46.67%  |
| AMD                        | 19        | 31.67%  |
| Nvidia                     | 11        | 18.33%  |
| VIA Technologies           | 1         | 1.67%   |
| Matrox Electronics Systems | 1         | 1.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 6.45%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                           | 4         | 6.45%   |
| Intel UHD Graphics 620                                                        | 3         | 4.84%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 3         | 4.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 2         | 3.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 3.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 3.23%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 2         | 3.23%   |
| AMD Lucienne                                                                  | 2         | 3.23%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 1         | 1.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.61%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 1.61%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                        | 1         | 1.61%   |
| Nvidia GT218 [GeForce 210]                                                    | 1         | 1.61%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1         | 1.61%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                            | 1         | 1.61%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 1         | 1.61%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1         | 1.61%   |
| Nvidia GK107M [GeForce GT 645M]                                               | 1         | 1.61%   |
| Nvidia GA104 [GeForce RTX 3070]                                               | 1         | 1.61%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                 | 1         | 1.61%   |
| Intel UHD Graphics 617                                                        | 1         | 1.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.61%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.61%   |
| Intel Iris Graphics 540                                                       | 1         | 1.61%   |
| Intel HD Graphics P530                                                        | 1         | 1.61%   |
| Intel HD Graphics 630                                                         | 1         | 1.61%   |
| Intel HD Graphics 530                                                         | 1         | 1.61%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.61%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.61%   |
| AMD Vega 20 [Radeon VII]                                                      | 1         | 1.61%   |
| AMD Topaz PRO [Radeon R5 M255]                                                | 1         | 1.61%   |
| AMD Sumo [Radeon HD 6520G]                                                    | 1         | 1.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 38.89%  |
| 1 x AMD        | 17        | 31.48%  |
| 1 x Nvidia     | 7         | 12.96%  |
| Intel + Nvidia | 3         | 5.56%   |
| 2 x Intel      | 2         | 3.7%    |
| 1 x VIA        | 1         | 1.85%   |
| 1 x Matrox     | 1         | 1.85%   |
| Intel + AMD    | 1         | 1.85%   |
| AMD + Nvidia   | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 46        | 85.19%  |
| Proprietary | 4         | 7.41%   |
| Unknown     | 4         | 7.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 79.63%  |
| 0.01-0.5   | 6         | 11.11%  |
| 0.51-1.0   | 2         | 3.7%    |
| 7.01-8.0   | 1         | 1.85%   |
| 5.01-6.0   | 1         | 1.85%   |
| 3.01-4.0   | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 8         | 17.39%  |
| LG Display              | 7         | 15.22%  |
| Goldstar                | 6         | 13.04%  |
| Samsung Electronics     | 5         | 10.87%  |
| BOE                     | 4         | 8.7%    |
| Chimei Innolux          | 2         | 4.35%   |
| ASUSTek Computer        | 2         | 4.35%   |
| Ancor Communications    | 2         | 4.35%   |
| ___                     | 1         | 2.17%   |
| Westinghouse            | 1         | 2.17%   |
| Sharp                   | 1         | 2.17%   |
| Hewlett-Packard         | 1         | 2.17%   |
| HannStar                | 1         | 2.17%   |
| Dell                    | 1         | 2.17%   |
| Chi Mei Optoelectronics | 1         | 2.17%   |
| Apple                   | 1         | 2.17%   |
| AOC                     | 1         | 2.17%   |
| Acer                    | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 2         | 4.35%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch             | 2         | 4.35%   |
| ___ MY TV LED TV ___0101 1920x1080                                       | 1         | 2.17%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch             | 1         | 2.17%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 2.17%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch        | 1         | 2.17%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch      | 1         | 2.17%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                        | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch     | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch     | 1         | 2.17%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD0612 1920x1080 340x190mm 15.3-inch             | 1         | 2.17%   |
| LG Display LCD Monitor LGD05B3 1920x1080 290x170mm 13.2-inch             | 1         | 2.17%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch             | 1         | 2.17%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch             | 1         | 2.17%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch              | 1         | 2.17%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch              | 1         | 2.17%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch               | 1         | 2.17%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 220x130mm 10.1-inch                 | 1         | 2.17%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                     | 1         | 2.17%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                      | 1         | 2.17%   |
| Goldstar LG UltraFine GSM5B10 3840x2160 480x270mm 21.7-inch              | 1         | 2.17%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 2.17%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch               | 1         | 2.17%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                     | 1         | 2.17%   |
| Dell E196FP DELA015 1280x1024 380x300mm 19.1-inch                        | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch          | 1         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch          | 1         | 2.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch | 1         | 2.17%   |
| BOE LCD Monitor BOE0715 1366x768 250x140mm 11.3-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE069B 1600x900 380x210mm 17.1-inch                     | 1         | 2.17%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                    | 1         | 2.17%   |
| BOE LCD Monitor BOE062B 1920x1080 340x190mm 15.3-inch                    | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO305C 1366x768 260x140mm 11.6-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 340x190mm 15.3-inch           | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 340x190mm 15.3-inch            | 1         | 2.17%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 2.17%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                     | 1         | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 18        | 41.86%  |
| 1366x768 (WXGA)   | 14        | 32.56%  |
| 3840x2160 (4K)    | 3         | 6.98%   |
| 2560x1440 (QHD)   | 1         | 2.33%   |
| 1920x1200 (WUXGA) | 1         | 2.33%   |
| 1600x900 (HD+)    | 1         | 2.33%   |
| 1440x900 (WXGA+)  | 1         | 2.33%   |
| 1360x768          | 1         | 2.33%   |
| 1280x800 (WXGA)   | 1         | 2.33%   |
| 1280x1024 (SXGA)  | 1         | 2.33%   |
| 1024x600          | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 13        | 28.26%  |
| 24      | 5         | 10.87%  |
| 13      | 5         | 10.87%  |
| 21      | 4         | 8.7%    |
| 27      | 3         | 6.52%   |
| 12      | 3         | 6.52%   |
| 11      | 3         | 6.52%   |
| 18      | 2         | 4.35%   |
| Unknown | 2         | 4.35%   |
| 39      | 1         | 2.17%   |
| 25      | 1         | 2.17%   |
| 19      | 1         | 2.17%   |
| 17      | 1         | 2.17%   |
| 14      | 1         | 2.17%   |
| 10      | 1         | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 16        | 35.56%  |
| 201-300     | 10        | 22.22%  |
| 501-600     | 7         | 15.56%  |
| 401-500     | 6         | 13.33%  |
| 351-400     | 2         | 4.44%   |
| Unknown     | 2         | 4.44%   |
| 801-900     | 1         | 2.22%   |
| 601-700     | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 36        | 87.8%   |
| 16/10   | 3         | 7.32%   |
| 5/4     | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 10        | 21.74%  |
| 201-250        | 9         | 19.57%  |
| 81-90          | 4         | 8.7%    |
| 61-70          | 3         | 6.52%   |
| 51-60          | 3         | 6.52%   |
| 301-350        | 3         | 6.52%   |
| 101-110        | 3         | 6.52%   |
| 71-80          | 2         | 4.35%   |
| 141-150        | 2         | 4.35%   |
| Unknown        | 2         | 4.35%   |
| 41-50          | 1         | 2.17%   |
| 251-300        | 1         | 2.17%   |
| 151-200        | 1         | 2.17%   |
| 121-130        | 1         | 2.17%   |
| 501-1000       | 1         | 2.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 13        | 29.55%  |
| 101-120       | 13        | 29.55%  |
| 51-100        | 11        | 25%     |
| 161-240       | 4         | 9.09%   |
| Unknown       | 2         | 4.55%   |
| More than 240 | 1         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 68.52%  |
| 0     | 12        | 22.22%  |
| 2     | 4         | 7.41%   |
| 3     | 1         | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 30        | 34.48%  |
| Intel                 | 27        | 31.03%  |
| Broadcom              | 9         | 10.34%  |
| Qualcomm Atheros      | 8         | 9.2%    |
| Ralink Technology     | 2         | 2.3%    |
| Ralink                | 2         | 2.3%    |
| Fibocom               | 2         | 2.3%    |
| VIA Technologies      | 1         | 1.15%   |
| Sierra Wireless       | 1         | 1.15%   |
| Samsung Electronics   | 1         | 1.15%   |
| Microchip Technology  | 1         | 1.15%   |
| Edimax Technology     | 1         | 1.15%   |
| D-Link System         | 1         | 1.15%   |
| Atheros               | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 17.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 5.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 2.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.78%   |
| Intel Wireless 8265 / 8275                                        | 3         | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.85%   |
| Intel Wireless 8260                                               | 2         | 1.85%   |
| Intel Wireless 7260                                               | 2         | 1.85%   |
| Intel Wireless 3165                                               | 2         | 1.85%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.85%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                 | 2         | 1.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.93%   |
| Sierra Wireless EM7455                                            | 1         | 0.93%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.93%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1         | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.93%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 1         | 0.93%   |
| Ralink RT5372 Wireless Adapter                                    | 1         | 0.93%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                 | 1         | 0.93%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.93%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.93%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.93%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.93%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.93%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.93%   |
| Microchip MCP2200 USB-to-Serial Port                              | 1         | 0.93%   |
| Intel Wireless-AC 9260                                            | 1         | 0.93%   |
| Intel WiMAX/WiFi Link 5150                                        | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 39.22%  |
| Realtek Semiconductor | 12        | 23.53%  |
| Broadcom              | 6         | 11.76%  |
| Qualcomm Atheros      | 5         | 9.8%    |
| Ralink Technology     | 2         | 3.92%   |
| Ralink                | 2         | 3.92%   |
| Sierra Wireless       | 1         | 1.96%   |
| Edimax Technology     | 1         | 1.96%   |
| D-Link System         | 1         | 1.96%   |
| Atheros               | 1         | 1.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3         | 5.77%   |
| Intel Wireless 8265 / 8275                                           | 3         | 5.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 3.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2         | 3.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 3.85%   |
| Intel Wireless 8260                                                  | 2         | 3.85%   |
| Intel Wireless 7260                                                  | 2         | 3.85%   |
| Intel Wireless 3165                                                  | 2         | 3.85%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 3.85%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 2         | 3.85%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 3.85%   |
| Sierra Wireless EM7455                                               | 1         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.92%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 1.92%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1         | 1.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1         | 1.92%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                | 1         | 1.92%   |
| Ralink RT5372 Wireless Adapter                                       | 1         | 1.92%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                    | 1         | 1.92%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter               | 1         | 1.92%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.92%   |
| Intel Wireless-AC 9260                                               | 1         | 1.92%   |
| Intel WiMAX/WiFi Link 5150                                           | 1         | 1.92%   |
| Intel WiFi Link 5100                                                 | 1         | 1.92%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 1.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 1         | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.92%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 1         | 1.92%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1         | 1.92%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                   | 1         | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 1         | 1.92%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 28        | 53.85%  |
| Intel                 | 14        | 26.92%  |
| Qualcomm Atheros      | 4         | 7.69%   |
| Broadcom              | 4         | 7.69%   |
| VIA Technologies      | 1         | 1.92%   |
| Samsung Electronics   | 1         | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19        | 35.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 11.32%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 5.66%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 5.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.77%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.89%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.89%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 1.89%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.89%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.89%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.89%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 1.89%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.89%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.89%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                    | 1         | 1.89%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1.89%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.89%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 1.89%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 51        | 51%     |
| WiFi     | 46        | 46%     |
| Unknown  | 2         | 2%      |
| Modem    | 1         | 1%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 60.56%  |
| WiFi     | 27        | 38.03%  |
| Unknown  | 1         | 1.41%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 39        | 72.22%  |
| 1     | 14        | 25.93%  |
| 4     | 1         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 85.19%  |
| Yes  | 8         | 14.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 44.12%  |
| Realtek Semiconductor           | 4         | 11.76%  |
| Broadcom                        | 4         | 11.76%  |
| ASUSTek Computer                | 3         | 8.82%   |
| Qualcomm Atheros Communications | 2         | 5.88%   |
| Apple                           | 2         | 5.88%   |
| Lite-On Technology              | 1         | 2.94%   |
| IMC Networks                    | 1         | 2.94%   |
| Foxconn / Hon Hai               | 1         | 2.94%   |
| Cambridge Silicon Radio         | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 20.59%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 5.88%   |
| Intel AX201 Bluetooth                               | 2         | 5.88%   |
| Intel AX200 Bluetooth                               | 2         | 5.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 2.94%   |
| Realtek Bluetooth 4.2 Adapter                       | 1         | 2.94%   |
| Realtek Bluetooth 4.0 Adapter                       | 1         | 2.94%   |
| Realtek Bluetooth 4.0 + High Speed Chip             | 1         | 2.94%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE | 1         | 2.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.94%   |
| Lite-On Atheros Bluetooth                           | 1         | 2.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 2.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 2.94%   |
| IMC Networks Realtek Bluetooth Adapter              | 1         | 2.94%   |
| Foxconn / Hon Hai Bluetooth USB Module              | 1         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.94%   |
| Broadcom Bluetooth 4.0                              | 1         | 2.94%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 2.94%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 2.94%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.94%   |
| ASUS USB-BT500                                      | 1         | 2.94%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 2.94%   |
| ASUS Bluetooth Controller                           | 1         | 2.94%   |
| Apple Broadcom Built-in Bluetooth                   | 1         | 2.94%   |
| Apple Bluetooth Host Controller                     | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 39        | 50.65%  |
| AMD                 | 18        | 23.38%  |
| Nvidia              | 9         | 11.69%  |
| Sony                | 2         | 2.6%    |
| Corsair             | 2         | 2.6%    |
| XMOS                | 1         | 1.3%    |
| VIA Technologies    | 1         | 1.3%    |
| Quanta              | 1         | 1.3%    |
| LG Electronics      | 1         | 1.3%    |
| Creative Technology | 1         | 1.3%    |
| C-Media Electronics | 1         | 1.3%    |
| Audio-Technica      | 1         | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                     | 7         | 7.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 6         | 6.38%   |
| AMD FCH Azalia Controller                                           | 5         | 5.32%   |
| Intel Haswell-ULT HD Audio Controller                               | 4         | 4.26%   |
| Intel 8 Series HD Audio Controller                                  | 4         | 4.26%   |
| AMD Kabini HDMI/DP Audio                                            | 4         | 4.26%   |
| AMD Family 17h/19h HD Audio Controller                              | 4         | 4.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 3         | 3.19%   |
| AMD Starship/Matisse HD Audio Controller                            | 3         | 3.19%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 3         | 3.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller             | 2         | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller              | 2         | 2.13%   |
| Intel Cannon Lake PCH cAVS                                          | 2         | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                      | 2         | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                      | 2         | 2.13%   |
| Intel 200 Series PCH HD Audio                                       | 2         | 2.13%   |
| Corsair VOID PRO Wireless Gaming Headset                            | 2         | 2.13%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                    | 2         | 2.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                             | 2         | 2.13%   |
| XMOS Shanling UA2                                                   | 1         | 1.06%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller      | 1         | 1.06%   |
| Sony DualShock 4 [CUH-ZCT2x]                                        | 1         | 1.06%   |
| Sony Audio                                                          | 1         | 1.06%   |
| Quanta USB Audio Realtek USB2.0 Audio Microphone                    | 1         | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                       | 1         | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller      | 1         | 1.06%   |
| Nvidia TU104 HD Audio Controller                                    | 1         | 1.06%   |
| Nvidia High Definition Audio Controller                             | 1         | 1.06%   |
| Nvidia GP108 High Definition Audio Controller                       | 1         | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                       | 1         | 1.06%   |
| Nvidia GP104 High Definition Audio Controller                       | 1         | 1.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                               | 1         | 1.06%   |
| Nvidia GA104 High Definition Audio Controller                       | 1         | 1.06%   |
| LG Electronics USB Audio LG UltraFine Display Audio                 | 1         | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller    | 1         | 1.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller         | 1         | 1.06%   |
| Intel Comet Lake PCH cAVS                                           | 1         | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio        | 1         | 1.06%   |
| Intel C600/X79 series chipset High Definition Audio Controller      | 1         | 1.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 17        | 26.15%  |
| Samsung Electronics | 15        | 23.08%  |
| Unknown             | 6         | 9.23%   |
| Micron Technology   | 6         | 9.23%   |
| Kingston            | 4         | 6.15%   |
| G.Skill             | 4         | 6.15%   |
| Crucial             | 3         | 4.62%   |
| Transcend           | 2         | 3.08%   |
| Nanya Technology    | 2         | 3.08%   |
| Corsair             | 2         | 3.08%   |
| Unknown             | 2         | 3.08%   |
| Ramaxel Technology  | 1         | 1.54%   |
| Elpida              | 1         | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s  | 3         | 4.41%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 2         | 2.94%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 2         | 2.94%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s   | 2         | 2.94%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2         | 2.94%   |
| Unknown                                                 | 2         | 2.94%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 1.47%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1         | 1.47%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                | 1         | 1.47%   |
| Unknown RAM Module 1GB SODIMM DRAM 533MT/s              | 1         | 1.47%   |
| Unknown RAM 7TE39AA# 8GB DIMM DDR4 2667MT/s             | 1         | 1.47%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s          | 1         | 1.47%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s        | 1         | 1.47%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s            | 1         | 1.47%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s    | 1         | 1.47%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s   | 1         | 1.47%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s    | 1         | 1.47%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s    | 1         | 1.47%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1         | 1.47%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 1.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 1.47%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1         | 1.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s  | 1         | 1.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s  | 1         | 1.47%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s | 1         | 1.47%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s  | 1         | 1.47%   |
| Samsung RAM Module 16GB SODIMM DDR4 2133MT/s            | 1         | 1.47%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s   | 1         | 1.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 1         | 1.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 1.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 1.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s   | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s   | 1         | 1.47%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s  | 1         | 1.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s   | 1         | 1.47%   |
| Samsung RAM M393B5170FHD-CF8 4GB DIMM DDR3 1066MT/s     | 1         | 1.47%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s     | 1         | 1.47%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 25        | 45.45%  |
| DDR3    | 19        | 34.55%  |
| DDR2    | 3         | 5.45%   |
| SDRAM   | 2         | 3.64%   |
| LPDDR3  | 2         | 3.64%   |
| DDR     | 2         | 3.64%   |
| DRAM    | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 63.64%  |
| DIMM         | 17        | 30.91%  |
| Chip         | 2         | 3.64%   |
| Row Of Chips | 1         | 1.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 23        | 38.98%  |
| 8192  | 20        | 33.9%   |
| 16384 | 8         | 13.56%  |
| 2048  | 6         | 10.17%  |
| 32768 | 1         | 1.69%   |
| 1024  | 1         | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 14        | 23.33%  |
| 3200    | 9         | 15%     |
| 2400    | 8         | 13.33%  |
| 2133    | 7         | 11.67%  |
| 2667    | 5         | 8.33%   |
| 1333    | 5         | 8.33%   |
| 1334    | 2         | 3.33%   |
| 667     | 2         | 3.33%   |
| Unknown | 2         | 3.33%   |
| 3600    | 1         | 1.67%   |
| 2933    | 1         | 1.67%   |
| 1066    | 1         | 1.67%   |
| 975     | 1         | 1.67%   |
| 800     | 1         | 1.67%   |
| 533     | 1         | 1.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HP PNP Fax Null                                                          | 1         | 50%     |
| HP HP LaserJet M101-M106 Printer HP LEDM HP LEDM IPP Printer IPP Printer | 1         | 50%     |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 7         | 25%     |
| Bison Electronics                      | 4         | 14.29%  |
| Quanta                                 | 3         | 10.71%  |
| IMC Networks                           | 3         | 10.71%  |
| Microdia                               | 2         | 7.14%   |
| Lite-On Technology                     | 2         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 7.14%   |
| Suyin                                  | 1         | 3.57%   |
| Sunplus Innovation Technology          | 1         | 3.57%   |
| Realtek Semiconductor                  | 1         | 3.57%   |
| Intel                                  | 1         | 3.57%   |
| Alcor Micro                            | 1         | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 3         | 10.71%  |
| Bison Integrated Camera                                        | 3         | 10.71%  |
| Quanta Realtek DMFT RGB                                        | 2         | 7.14%   |
| Suyin USB 2.0 UVC 1.3M WebCam                                  | 1         | 3.57%   |
| Sunplus Integrated Webcam                                      | 1         | 3.57%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 1         | 3.57%   |
| Quanta Front camera                                            | 1         | 3.57%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 3.57%   |
| Microdia Integrated Webcam                                     | 1         | 3.57%   |
| Lite-On Realtek PC Camera                                      | 1         | 3.57%   |
| Lite-On HP Universal Camera                                    | 1         | 3.57%   |
| Intel WiMAX Connection 2400m                                   | 1         | 3.57%   |
| IMC Networks USB 2.0 UVC HD Webcam                             | 1         | 3.57%   |
| IMC Networks Realtek PC Camera                                 | 1         | 3.57%   |
| IMC Networks EasyCamera                                        | 1         | 3.57%   |
| Chicony Realtek DMFT RGB                                       | 1         | 3.57%   |
| Chicony Integrated IR Camera                                   | 1         | 3.57%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 3.57%   |
| Chicony Chicony USB2.0 Camera                                  | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 3.57%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 1         | 3.57%   |
| Bison Lenovo EasyCamera                                        | 1         | 3.57%   |
| Alcor Micro HP WebCam-101                                      | 1         | 3.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 4         | 40%     |
| Synaptics             | 3         | 30%     |
| Upek                  | 1         | 10%     |
| Elan Microelectronics | 1         | 10%     |
| AuthenTec             | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 2         | 20%     |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 10%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 10%     |
| Elan Fingerprint Sensor                                | 1         | 10%     |
| AuthenTec AES1600                                      | 1         | 10%     |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 20        | 37.04%  |
| 2     | 15        | 27.78%  |
| 0     | 9         | 16.67%  |
| 4     | 5         | 9.26%   |
| 3     | 5         | 9.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 31        | 37.8%   |
| Net/wireless             | 20        | 24.39%  |
| Fingerprint reader       | 10        | 12.2%   |
| Bluetooth                | 9         | 10.98%  |
| Firewire controller      | 5         | 6.1%    |
| Network                  | 3         | 3.66%   |
| Card reader              | 3         | 3.66%   |
| Sound                    | 1         | 1.22%   |

