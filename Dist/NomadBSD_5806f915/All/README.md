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

Total: 63

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [94f78425f1](https://bsd-hardware.info/?probe=94f78425f1) | Mar 25, 2022 |
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
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [2d874470d0](https://bsd-hardware.info/?probe=2d874470d0) | Jun 01, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [c6a1c1fa15](https://bsd-hardware.info/?probe=c6a1c1fa15) | May 25, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [96cc0c27b0](https://bsd-hardware.info/?probe=96cc0c27b0) | May 25, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [8cf113ac55](https://bsd-hardware.info/?probe=8cf113ac55) | May 22, 2021 |
| Toshiba       | STI 005492G                 | Desktop     | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 48        | 96%     |
| i386  | 2         | 4%      |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Openbox | 49        | 98%     |
| KDE5    | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 50        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 49        | 98%     |
| SDDM | 1         | 2%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 27        | 52.94%  |
| de_DE   | 5         | 9.8%    |
| Unknown | 4         | 7.84%   |
| ru_RU   | 3         | 5.88%   |
| en_GB   | 3         | 5.88%   |
| zh_CN   | 2         | 3.92%   |
| pt_BR   | 2         | 3.92%   |
| pl_PL   | 1         | 1.96%   |
| fr_FR   | 1         | 1.96%   |
| fi_FI   | 1         | 1.96%   |
| es_ES   | 1         | 1.96%   |
| en_AU   | 1         | 1.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 49        | 98%     |
| BIOS | 1         | 2%      |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 46        | 92%     |
| Zfs  | 4         | 8%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 41        | 82%     |
| MBR  | 9         | 18%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 13        | 26%     |
| ASUSTek Computer    | 10        | 20%     |
| Dell                | 8         | 16%     |
| Lenovo              | 6         | 12%     |
| Gigabyte Technology | 3         | 6%      |
| Intel               | 2         | 4%      |
| Sony                | 1         | 2%      |
| Semp Toshiba        | 1         | 2%      |
| Notebook            | 1         | 2%      |
| Fujitsu Siemens     | 1         | 2%      |
| ASRock              | 1         | 2%      |
| Apple               | 1         | 2%      |
| Acer                | 1         | 2%      |
| Unknown             | 1         | 2%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Sony VJS121C11N                         | 1         | 2%      |
| Semp Toshiba STI                        | 1         | 2%      |
| Notebook W650DC,DD                      | 1         | 2%      |
| Lenovo ThinkPad X380 Yoga 20LJ000WUK    | 1         | 2%      |
| Lenovo ThinkPad T490s 20NX000DRT        | 1         | 2%      |
| Lenovo ThinkPad T470s W10DG 20JS001FGE  | 1         | 2%      |
| Lenovo ThinkPad T440s 20AQ006HUS        | 1         | 2%      |
| Lenovo ThinkPad S1 Yoga 20C0S0M300      | 1         | 2%      |
| Lenovo Legion Y7000 2019 PG0 81T0       | 1         | 2%      |
| Intel NUC6i5SYB H81131-502              | 1         | 2%      |
| Intel DCP847SKE                         | 1         | 2%      |
| HP ZBook Studio G3                      | 1         | 2%      |
| HP Z420 Workstation                     | 1         | 2%      |
| HP ProBook x360 11 G6 EE                | 1         | 2%      |
| HP ProBook 450 G2                       | 1         | 2%      |
| HP Pavilion Notebook                    | 1         | 2%      |
| HP Pavilion g6                          | 1         | 2%      |
| HP OMEN by HP Laptop 17-cb1xxx          | 1         | 2%      |
| HP Notebook                             | 1         | 2%      |
| HP Laptop 15-db0xxx                     | 1         | 2%      |
| HP Desktop M01-F1xxx                    | 1         | 2%      |
| HP 550-a114                             | 1         | 2%      |
| HP 255 G8 Notebook PC                   | 1         | 2%      |
| HP 2000                                 | 1         | 2%      |
| Gigabyte Z370 AORUS ULTRAGAMING WIFI-OP | 1         | 2%      |
| Gigabyte X570S GAMING X                 | 1         | 2%      |
| Gigabyte MZGLKBP-00                     | 1         | 2%      |
| Fujitsu Siemens AMILO PRO V3515         | 1         | 2%      |
| Dell Studio 1555                        | 1         | 2%      |
| Dell PowerEdge T410                     | 1         | 2%      |
| Dell OptiPlex 9010                      | 1         | 2%      |
| Dell OptiPlex 3020                      | 1         | 2%      |
| Dell OptiPlex 3010                      | 1         | 2%      |
| Dell Latitude D630                      | 1         | 2%      |
| Dell Latitude 5290                      | 1         | 2%      |
| Dell Inspiron 15-5568                   | 1         | 2%      |
| ASUS X540YA                             | 1         | 2%      |
| ASUS X202E                              | 1         | 2%      |
| ASUS V-P7H55E                           | 1         | 2%      |
| ASUS TUF Gaming FX505DU_FX505DU         | 1         | 2%      |
| ASUS TUF GAMING B550M-PLUS              | 1         | 2%      |
| ASUS ROG STRIX X299-E GAMING            | 1         | 2%      |
| ASUS PRIME Z390-P                       | 1         | 2%      |
| ASUS Maximus VIII HERO                  | 1         | 2%      |
| ASUS M51Sr                              | 1         | 2%      |
| ASUS 1000                               | 1         | 2%      |
| ASRock B550 Steel Legend                | 1         | 2%      |
| Apple MacBookAir6,1                     | 1         | 2%      |
| Acer Aspire 3810T                       | 1         | 2%      |
| Unknown                                 | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 5         | 10%     |
| Dell OptiPlex         | 3         | 6%      |
| HP ProBook            | 2         | 4%      |
| HP Pavilion           | 2         | 4%      |
| Dell Latitude         | 2         | 4%      |
| ASUS TUF              | 2         | 4%      |
| Sony VJS121C11N       | 1         | 2%      |
| Semp Toshiba STI      | 1         | 2%      |
| Notebook W650DC       | 1         | 2%      |
| Lenovo Legion         | 1         | 2%      |
| Intel NUC6i5SYB       | 1         | 2%      |
| Intel DCP847SKE       | 1         | 2%      |
| HP ZBook              | 1         | 2%      |
| HP Z420               | 1         | 2%      |
| HP OMEN               | 1         | 2%      |
| HP Notebook           | 1         | 2%      |
| HP Laptop             | 1         | 2%      |
| HP Desktop            | 1         | 2%      |
| HP 550-a114           | 1         | 2%      |
| HP 255                | 1         | 2%      |
| HP 2000               | 1         | 2%      |
| Gigabyte Z370         | 1         | 2%      |
| Gigabyte X570S        | 1         | 2%      |
| Gigabyte MZGLKBP-00   | 1         | 2%      |
| Fujitsu Siemens AMILO | 1         | 2%      |
| Dell Studio           | 1         | 2%      |
| Dell PowerEdge        | 1         | 2%      |
| Dell Inspiron         | 1         | 2%      |
| ASUS X540YA           | 1         | 2%      |
| ASUS X202E            | 1         | 2%      |
| ASUS V-P7H55E         | 1         | 2%      |
| ASUS ROG              | 1         | 2%      |
| ASUS PRIME            | 1         | 2%      |
| ASUS Maximus          | 1         | 2%      |
| ASUS M51Sr            | 1         | 2%      |
| ASUS 1000             | 1         | 2%      |
| ASRock B550           | 1         | 2%      |
| Apple MacBookAir6     | 1         | 2%      |
| Acer Aspire           | 1         | 2%      |
| Unknown               | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 9         | 18%     |
| 2021 | 7         | 14%     |
| 2020 | 6         | 12%     |
| 2017 | 5         | 10%     |
| 2015 | 4         | 8%      |
| 2013 | 3         | 6%      |
| 2009 | 3         | 6%      |
| 2008 | 3         | 6%      |
| 2022 | 2         | 4%      |
| 2018 | 2         | 4%      |
| 2012 | 2         | 4%      |
| 2014 | 1         | 2%      |
| 2011 | 1         | 2%      |
| 2010 | 1         | 2%      |
| 2006 | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 28        | 56%     |
| Desktop     | 18        | 36%     |
| Convertible | 2         | 4%      |
| Mini pc     | 1         | 2%      |
| Server      | 1         | 2%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 50        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 19        | 38%     |
| 16.01-24.0  | 11        | 22%     |
| 4.01-8.0    | 8         | 16%     |
| 32.01-64.0  | 6         | 12%     |
| 64.01-256.0 | 3         | 6%      |
| 2.01-3.0    | 2         | 4%      |
| 24.01-32.0  | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 19        | 38%     |
| 0.51-1.0 | 16        | 32%     |
| 1.01-2.0 | 13        | 26%     |
| 4.01-8.0 | 1         | 2%      |
| 3.01-4.0 | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 60.78%  |
| 2      | 12        | 23.53%  |
| 3      | 6         | 11.76%  |
| 4      | 2         | 3.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 30        | 60%     |
| Yes       | 20        | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 94%     |
| No        | 3         | 6%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 84%     |
| No        | 8         | 16%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 54.9%   |
| No        | 23        | 45.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| USA       | 16        | 32%     |
| Germany   | 6         | 12%     |
| Russia    | 5         | 10%     |
| Mexico    | 3         | 6%      |
| Thailand  | 2         | 4%      |
| Romania   | 2         | 4%      |
| Japan     | 2         | 4%      |
| China     | 2         | 4%      |
| Brazil    | 2         | 4%      |
| Spain     | 1         | 2%      |
| Slovakia  | 1         | 2%      |
| Poland    | 1         | 2%      |
| Norway    | 1         | 2%      |
| Italy     | 1         | 2%      |
| France    | 1         | 2%      |
| Finland   | 1         | 2%      |
| Denmark   | 1         | 2%      |
| Belarus   | 1         | 2%      |
| Australia | 1         | 2%      |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Whittier              | 3         | 6%      |
| Tijuana               | 3         | 6%      |
| Duncan                | 3         | 6%      |
| Volzhskiy             | 2         | 4%      |
| Setagaya-ku           | 2         | 4%      |
| Rio de Janeiro        | 2         | 4%      |
| Moscow                | 2         | 4%      |
| Drobeta-Turnu Severin | 2         | 4%      |
| Cologne               | 2         | 4%      |
| Changzhou             | 2         | 4%      |
| Bangkok               | 2         | 4%      |
| Wloszczowa            | 1         | 2%      |
| Winter Haven          | 1         | 2%      |
| Vollen                | 1         | 2%      |
| Tucson                | 1         | 2%      |
| Trieste               | 1         | 2%      |
| Syracuse              | 1         | 2%      |
| Sedavi                | 1         | 2%      |
| Scottsdale            | 1         | 2%      |
| San Francisco         | 1         | 2%      |
| San Bernardino        | 1         | 2%      |
| Palmer                | 1         | 2%      |
| Palm Bay              | 1         | 2%      |
| Novosibirsk           | 1         | 2%      |
| Mogilev               | 1         | 2%      |
| Melcice               | 1         | 2%      |
| Marburg               | 1         | 2%      |
| Helsinki              | 1         | 2%      |
| Greifswald            | 1         | 2%      |
| Fontenay-sous-Bois    | 1         | 2%      |
| DÃ¼sseldorf         | 1         | 2%      |
| Cupertino             | 1         | 2%      |
| Copenhagen            | 1         | 2%      |
| Conway                | 1         | 2%      |
| Brisbane              | 1         | 2%      |
| Berlin                | 1         | 2%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 16     | 18.92%  |
| Samsung Electronics | 11        | 13     | 14.86%  |
| Seagate             | 9         | 10     | 12.16%  |
| Crucial             | 7         | 7      | 9.46%   |
| Toshiba             | 5         | 7      | 6.76%   |
| SK hynix            | 4         | 4      | 5.41%   |
| Kingston            | 3         | 3      | 4.05%   |
| Intel               | 3         | 3      | 4.05%   |
| A-DATA Technology   | 3         | 3      | 4.05%   |
| SanDisk             | 2         | 2      | 2.7%    |
| PNY                 | 2         | 2      | 2.7%    |
| Hewlett-Packard     | 2         | 2      | 2.7%    |
| Apple               | 2         | 2      | 2.7%    |
| Transcend           | 1         | 1      | 1.35%   |
| Team                | 1         | 1      | 1.35%   |
| SPCC                | 1         | 1      | 1.35%   |
| Micron Technology   | 1         | 1      | 1.35%   |
| HGST                | 1         | 1      | 1.35%   |
| Gigabyte Technology | 1         | 1      | 1.35%   |
| ASUSTek Computer    | 1         | 2      | 1.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| WDC WDS100T1X0E-00AFY0 1TB                | 2         | 2.56%   |
| WDC WD40PURX-64GVNY0 4TB                  | 2         | 2.56%   |
| Seagate ST9500325AS 500GB                 | 2         | 2.56%   |
| SanDisk SSD U100 24GB                     | 2         | 2.56%   |
| Kingston SA400S37480G 480GB               | 2         | 2.56%   |
| HP SSD EX950 2TB                          | 2         | 2.56%   |
| Crucial CT1000P1SSD8 1TB                  | 2         | 2.56%   |
| A-DATA SU630 240GB                        | 2         | 2.56%   |
| WDC WDS120G2G0A-00JH30 120GB              | 1         | 1.28%   |
| WDC WD60EZRZ-00GZ5B1 6TB                  | 1         | 1.28%   |
| WDC WD3200BEVT-75ZCT2 320GB               | 1         | 1.28%   |
| WDC WD2500BEKT-00PVMT0 250GB              | 1         | 1.28%   |
| WDC WD1200BEVS-07LAT0 120GB               | 1         | 1.28%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 1.28%   |
| WDC WD10SMRW-11Y43S0 1TB                  | 1         | 1.28%   |
| WDC WD10JPVX-60JC3T0 1TB                  | 1         | 1.28%   |
| WDC WD10EADS-00P8B0 1TB                   | 1         | 1.28%   |
| WDC PC SN720 SDAPNTW-1T00-1006 1TB        | 1         | 1.28%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB      | 1         | 1.28%   |
| WDC PC SN520 SDAPMUW-128G-1101 128GB      | 1         | 1.28%   |
| Transcend TS512GSSD370S 512GB             | 1         | 1.28%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.28%   |
| Toshiba MK1637GSX 160GB                   | 1         | 1.28%   |
| Toshiba MG06ACA800E 8TB                   | 1         | 1.28%   |
| Toshiba KXG5AZNV256G 256GB                | 1         | 1.28%   |
| Toshiba HDWD120 2TB                       | 1         | 1.28%   |
| Team TEAML5Lite3D1T 1TB                   | 1         | 1.28%   |
| SPCC Solid State Disk 240GB               | 1         | 1.28%   |
| SK hynix SKHynix_HFS512GD9TNG-L5B0B 512GB | 1         | 1.28%   |
| SK hynix SKHynix_HFS256GD9TNI-L2B0B 256GB | 1         | 1.28%   |
| SK hynix SHGS31-500GS-2 500GB             | 1         | 1.28%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB   | 1         | 1.28%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 1.28%   |
| Seagate ST500LM030-2E717D 500GB           | 1         | 1.28%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1.28%   |
| Seagate ST4000DM000-2AE166 4TB            | 1         | 1.28%   |
| Seagate ST3000DM008-2DM166 3TB            | 1         | 1.28%   |
| Seagate ST2000LM007-1R8174 2TB            | 1         | 1.28%   |
| Seagate ST2000DM001-1CH164 2TB            | 1         | 1.28%   |
| Samsung SSD 970 EVO 500GB                 | 1         | 1.28%   |
| Samsung SSD 970 EVO 2TB                   | 1         | 1.28%   |
| Samsung SSD 870 QVO 2TB                   | 1         | 1.28%   |
| Samsung SSD 870 EVO 1TB                   | 1         | 1.28%   |
| Samsung SSD 860 EVO 1TB                   | 1         | 1.28%   |
| Samsung SSD 840 EVO 250GB                 | 1         | 1.28%   |
| Samsung MZVLB256HBHQ-000L2 256GB          | 1         | 1.28%   |
| Samsung MZVLB256HAHQ-00000 256GB          | 1         | 1.28%   |
| Samsung MZVKW512HMJP-000H1 512GB          | 1         | 1.28%   |
| Samsung MZ7TD256HAFV-000L9 256GB          | 1         | 1.28%   |
| Samsung MZ7TD128HAFV-000L1 128GB          | 1         | 1.28%   |
| Samsung HM160HI 160GB                     | 1         | 1.28%   |
| Samsung HD161GJ 160GB                     | 1         | 1.28%   |
| PNY SSD2SC240G1CS1754D117-489 240GB       | 1         | 1.28%   |
| PNY CS1311 120GB SSD                      | 1         | 1.28%   |
| Micron MTFDHBA512QFD-1AX1AABHA 512GB      | 1         | 1.28%   |
| Kingston SA2000M8500G 500GB               | 1         | 1.28%   |
| Intel SSDSCKKW240H6 240GB                 | 1         | 1.28%   |
| Intel SSDPEKNW020T8 2TB                   | 1         | 1.28%   |
| Intel MEMPEK1W032GA 32GB                  | 1         | 1.28%   |
| HGST HTS725050A7E630 500GB                | 1         | 1.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 37.04%  |
| Seagate             | 9         | 10     | 33.33%  |
| Toshiba             | 4         | 5      | 14.81%  |
| Samsung Electronics | 2         | 2      | 7.41%   |
| HGST                | 1         | 1      | 3.7%    |
| Apple               | 1         | 1      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


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

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 29     | 36.92%  |
| SSD  | 22        | 29     | 33.85%  |
| NVMe | 19        | 24     | 29.23%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 58     | 68.33%  |
| NVMe | 19        | 24     | 31.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 37     | 59.57%  |
| 0.51-1.0   | 10        | 10     | 21.28%  |
| 1.01-2.0   | 4         | 4      | 8.51%   |
| 3.01-4.0   | 3         | 3      | 6.38%   |
| 2.01-3.0   | 1         | 1      | 2.13%   |
| 4.01-10.0  | 1         | 3      | 2.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 44        | 88%     |
| 101-250    | 4         | 8%      |
| 251-500    | 1         | 2%      |
| 51-100     | 1         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 49        | 98%     |
| 51-100  | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 44        | 72     | 84.62%  |
| Malfunc  | 7         | 8      | 13.46%  |
| Detected | 1         | 2      | 1.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 32        | 46.38%  |
| AMD                         | 12        | 17.39%  |
| Samsung Electronics         | 6         | 8.7%    |
| SanDisk                     | 5         | 7.25%   |
| Micron/Crucial Technology   | 3         | 4.35%   |
| SK hynix                    | 2         | 2.9%    |
| Biwin Storage Technology    | 2         | 2.9%    |
| ASMedia Technology          | 2         | 2.9%    |
| VIA Technologies            | 1         | 1.45%   |
| Toshiba                     | 1         | 1.45%   |
| Micron Technology           | 1         | 1.45%   |
| Kingston Technology Company | 1         | 1.45%   |
| JMicron Technology          | 1         | 1.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 11.69%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 5.19%   |
| Unknown                                                                        | 4         | 5.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 3.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 3.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 3.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 3.9%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 2.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 2.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 2.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 2.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 2.6%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 2.6%    |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 2.6%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1         | 1.3%    |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 1.3%    |
| Toshiba unknown                                                                | 1         | 1.3%    |
| SK hynix hynix unknown                                                         | 1         | 1.3%    |
| SK hynix BC511                                                                 | 1         | 1.3%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 1.3%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 1.3%    |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 1.3%    |
| Samsung Apple PCIe SSD                                                         | 1         | 1.3%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 1.3%    |
| Micron/Crucial NVMe Controller                                                 | 1         | 1.3%    |
| Kingston Company A2000 NVMe SSD                                                | 1         | 1.3%    |
| JMicron JMB360 AHCI Controller                                                 | 1         | 1.3%    |
| Intel SSD 660P Series                                                          | 1         | 1.3%    |
| Intel NVMe Optane Memory Series                                                | 1         | 1.3%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 1.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 1.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.3%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 1         | 1.3%    |
| Intel C600/X79 series chipset SATA RAID Controller                             | 1         | 1.3%    |
| Intel C600/X79 series chipset IDE-r Controller                                 | 1         | 1.3%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1         | 1.3%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1         | 1.3%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 1         | 1.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1         | 1.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 1         | 1.3%    |
| AMD FCH SATA Controller [IDE mode]                                             | 1         | 1.3%    |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.3%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 55.88%  |
| NVMe | 19        | 27.94%  |
| IDE  | 8         | 11.76%  |
| RAID | 2         | 2.94%   |
| SAS  | 1         | 1.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 38        | 76%     |
| AMD    | 12        | 24%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 9 5900X 12-Core Processor           | 2         | 4%      |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 4%      |
| Intel Xeon CPU E5640 @ 2.67GHz                | 1         | 2%      |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1         | 2%      |
| Intel Xeon CPU E5-1620 v2 @ 3.70GHz           | 1         | 2%      |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 2%      |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 2%      |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 2%      |
| Intel Genuine CPU U7300 @ 1.30GHz             | 1         | 2%      |
| Intel CPU Version                             | 1         | 2%      |
| Intel Core i9-7960X CPU @ 2.80GHz             | 1         | 2%      |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 2%      |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 2%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 2%      |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 2%      |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 2%      |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 2%      |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 2%      |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 1         | 2%      |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 2%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 2%      |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 2%      |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 2%      |
| Intel Core i5-6260U CPU @ 1.80GHz             | 1         | 2%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 2%      |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 2%      |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 2%      |
| Intel Core i5-3570 CPU @ 3.40GHz              | 1         | 2%      |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 2%      |
| Intel Core i5-10210Y CPU @ 1.00GHz            | 1         | 2%      |
| Intel Core i5 CPU 750 @ 2.67GHz               | 1         | 2%      |
| Intel Core i3-8130U CPU @ 2.20GHz             | 1         | 2%      |
| Intel Core i3-4150 CPU @ 3.50GHz              | 1         | 2%      |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 2%      |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 2%      |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 1         | 2%      |
| Intel Core 2 Duo                              | 1         | 2%      |
| Intel Celeron M CPU                           | 1         | 2%      |
| Intel Celeron CPU 847E @ 1.10GHz              | 1         | 2%      |
| Intel Atom CPU N270 @ 1.60GHz                 | 1         | 2%      |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 2%      |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1         | 2%      |
| AMD Ryzen 5 4600G with Radeon Graphics        | 1         | 2%      |
| AMD Ryzen 5 3600XT 6-Core Processor           | 1         | 2%      |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 1         | 2%      |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 1         | 2%      |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 1         | 2%      |
| AMD A6-3420M APU with Radeon HD Graphics      | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 13        | 26%     |
| Intel Core i7           | 7         | 14%     |
| Intel Xeon              | 4         | 8%      |
| Intel Core i3           | 4         | 8%      |
| AMD Ryzen 5             | 3         | 6%      |
| AMD A8                  | 3         | 6%      |
| Other                   | 2         | 4%      |
| Intel Core 2 Duo        | 2         | 4%      |
| AMD Ryzen 9             | 2         | 4%      |
| AMD A6                  | 2         | 4%      |
| Intel Pentium Silver    | 1         | 2%      |
| Intel Pentium Dual-Core | 1         | 2%      |
| Intel Genuine           | 1         | 2%      |
| Intel Core i9           | 1         | 2%      |
| Intel Celeron M         | 1         | 2%      |
| Intel Celeron           | 1         | 2%      |
| Intel Atom              | 1         | 2%      |
| AMD Ryzen 7             | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 19        | 38%     |
| 2       | 16        | 32%     |
| 12      | 3         | 6%      |
| 8       | 3         | 6%      |
| Unknown | 3         | 6%      |
| 24      | 2         | 4%      |
| 6       | 2         | 4%      |
| 16      | 1         | 2%      |
| 1       | 1         | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 24        | 48%     |
| 1       | 22        | 44%     |
| Unknown | 4         | 8%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 18%     |
| Skylake       | 6         | 12%     |
| IvyBridge     | 5         | 10%     |
| Haswell       | 5         | 10%     |
| Puma          | 4         | 8%      |
| Penryn        | 4         | 8%      |
| Zen 3         | 2         | 4%      |
| Zen 2         | 2         | 4%      |
| SandyBridge   | 2         | 4%      |
| Zen+          | 1         | 2%      |
| Westmere      | 1         | 2%      |
| P6            | 1         | 2%      |
| Nehalem       | 1         | 2%      |
| K10 Llano     | 1         | 2%      |
| Goldmont plus | 1         | 2%      |
| Excavator     | 1         | 2%      |
| Core          | 1         | 2%      |
| CometLake     | 1         | 2%      |
| Bonnell       | 1         | 2%      |
| Unknown       | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 25        | 45.45%  |
| AMD                        | 18        | 32.73%  |
| Nvidia                     | 10        | 18.18%  |
| VIA Technologies           | 1         | 1.82%   |
| Matrox Electronics Systems | 1         | 1.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 7.02%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                           | 4         | 7.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 2         | 3.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 3.51%   |
| Intel UHD Graphics 620                                                        | 2         | 3.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 3.51%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 3.51%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 2         | 3.51%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 1         | 1.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 1.75%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                        | 1         | 1.75%   |
| Nvidia GT218 [GeForce 210]                                                    | 1         | 1.75%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 1.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 1         | 1.75%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                            | 1         | 1.75%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 1         | 1.75%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1         | 1.75%   |
| Nvidia GA104 [GeForce RTX 3070]                                               | 1         | 1.75%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                 | 1         | 1.75%   |
| Intel UHD Graphics 615                                                        | 1         | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 1.75%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 1.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.75%   |
| Intel Iris Graphics 540                                                       | 1         | 1.75%   |
| Intel HD Graphics P530                                                        | 1         | 1.75%   |
| Intel HD Graphics 630                                                         | 1         | 1.75%   |
| Intel HD Graphics 530                                                         | 1         | 1.75%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 1.75%   |
| AMD Vega 20 [Radeon VII]                                                      | 1         | 1.75%   |
| AMD Topaz PRO [Radeon R5 M255]                                                | 1         | 1.75%   |
| AMD Sumo [Radeon HD 6520G]                                                    | 1         | 1.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                      | 1         | 1.75%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                             | 1         | 1.75%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                             | 1         | 1.75%   |
| AMD RV610/M72-S [Mobility Radeon HD 2400]                                     | 1         | 1.75%   |
| AMD Renoir                                                                    | 1         | 1.75%   |
| AMD Pitcairn XT GL [FirePro W7000]                                            | 1         | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.75%   |
| AMD Lucienne                                                                  | 1         | 1.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 1         | 1.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 38%     |
| 1 x AMD        | 16        | 32%     |
| 1 x Nvidia     | 7         | 14%     |
| 2 x Intel      | 2         | 4%      |
| Intel + Nvidia | 2         | 4%      |
| 1 x VIA        | 1         | 2%      |
| 1 x Matrox     | 1         | 2%      |
| Intel + AMD    | 1         | 2%      |
| AMD + Nvidia   | 1         | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 43        | 86%     |
| Proprietary | 4         | 8%      |
| Unknown     | 3         | 6%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 78%     |
| 0.01-0.5   | 6         | 12%     |
| 0.51-1.0   | 2         | 4%      |
| 7.01-8.0   | 1         | 2%      |
| 5.01-6.0   | 1         | 2%      |
| 3.01-4.0   | 1         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 7         | 16.28%  |
| LG Display           | 6         | 13.95%  |
| Goldstar             | 6         | 13.95%  |
| Samsung Electronics  | 5         | 11.63%  |
| BOE                  | 4         | 9.3%    |
| Chimei Innolux       | 2         | 4.65%   |
| ASUSTek Computer     | 2         | 4.65%   |
| Ancor Communications | 2         | 4.65%   |
| ___                  | 1         | 2.33%   |
| Westinghouse         | 1         | 2.33%   |
| Sharp                | 1         | 2.33%   |
| Hewlett-Packard      | 1         | 2.33%   |
| HannStar             | 1         | 2.33%   |
| Dell                 | 1         | 2.33%   |
| Apple                | 1         | 2.33%   |
| AOC                  | 1         | 2.33%   |
| Acer                 | 1         | 2.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch         | 2         | 4.65%   |
| ___ MY TV LED TV ___0101 1920x1080                                   | 1         | 2.33%   |
| Westinghouse DWM40F3G1 WET1ECC 1920x1080 880x480mm 39.5-inch         | 1         | 2.33%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch              | 1         | 2.33%   |
| Samsung Electronics S27E330 SAM0D91 1920x1080 600x340mm 27.2-inch    | 1         | 2.33%   |
| Samsung Electronics LF24T450F SAM7094 1920x1080 530x300mm 24.0-inch  | 1         | 2.33%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                    | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 300x190mm 14.0-inch | 1         | 2.33%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch | 1         | 2.33%   |
| LG Display LCD Monitor LGD7001 1366x768 340x190mm 15.3-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD05B3 1920x1080 290x170mm 13.2-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD040A 1920x1080 310x170mm 13.9-inch         | 1         | 2.33%   |
| LG Display LCD Monitor LGD034D 1366x768 340x190mm 15.3-inch          | 1         | 2.33%   |
| LG Display LCD Monitor LGD01F7 1366x768 290x160mm 13.0-inch          | 1         | 2.33%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 530x300mm 24.0-inch           | 1         | 2.33%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 1         | 2.33%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                 | 1         | 2.33%   |
| Goldstar W1943 GSM4BAD 1360x768 410x230mm 18.5-inch                  | 1         | 2.33%   |
| Goldstar LG UltraFine GSM5B10 3840x2160 480x270mm 21.7-inch          | 1         | 2.33%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 1         | 2.33%   |
| Goldstar LCD Monitor GSM5AB7 1920x1080 480x270mm 21.7-inch           | 1         | 2.33%   |
| Goldstar E2241 GSM581A 1920x1080 480x270mm 21.7-inch                 | 1         | 2.33%   |
| Dell E196FP DELA015 1280x1024 380x300mm 19.1-inch                    | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch      | 1         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch      | 1         | 2.33%   |
| BOE LCD Monitor BOE0715 1366x768 250x140mm 11.3-inch                 | 1         | 2.33%   |
| BOE LCD Monitor BOE069B 1600x900 380x210mm 17.1-inch                 | 1         | 2.33%   |
| BOE LCD Monitor BOE0691 1920x1080 280x160mm 12.7-inch                | 1         | 2.33%   |
| BOE LCD Monitor BOE062B 1920x1080 340x190mm 15.3-inch                | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO8174 1280x800 330x210mm 15.4-inch        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO305C 1366x768 260x140mm 11.6-inch        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 340x190mm 15.3-inch       | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 340x190mm 15.3-inch        | 1         | 2.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 2.33%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 1         | 2.33%   |
| AOC U2879G6 AOC2879 3840x2160 620x340mm 27.8-inch                    | 1         | 2.33%   |
| Ancor Communications PA248 ACI24B1 1920x1200 550x350mm 25.7-inch     | 1         | 2.33%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch | 1         | 2.33%   |
| Acer KW272U ACR099D 2560x1440 600x340mm 27.2-inch                    | 1         | 2.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 16        | 40%     |
| 1366x768 (WXGA)   | 13        | 32.5%   |
| 3840x2160 (4K)    | 3         | 7.5%    |
| 2560x1440 (QHD)   | 1         | 2.5%    |
| 1920x1200 (WUXGA) | 1         | 2.5%    |
| 1600x900 (HD+)    | 1         | 2.5%    |
| 1440x900 (WXGA+)  | 1         | 2.5%    |
| 1360x768          | 1         | 2.5%    |
| 1280x800 (WXGA)   | 1         | 2.5%    |
| 1280x1024 (SXGA)  | 1         | 2.5%    |
| 1024x600          | 1         | 2.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 11        | 25.58%  |
| 24      | 5         | 11.63%  |
| 21      | 4         | 9.3%    |
| 13      | 4         | 9.3%    |
| 27      | 3         | 6.98%   |
| 12      | 3         | 6.98%   |
| 11      | 3         | 6.98%   |
| 18      | 2         | 4.65%   |
| Unknown | 2         | 4.65%   |
| 39      | 1         | 2.33%   |
| 25      | 1         | 2.33%   |
| 19      | 1         | 2.33%   |
| 17      | 1         | 2.33%   |
| 14      | 1         | 2.33%   |
| 10      | 1         | 2.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 30.95%  |
| 201-300     | 10        | 23.81%  |
| 501-600     | 7         | 16.67%  |
| 401-500     | 6         | 14.29%  |
| 351-400     | 2         | 4.76%   |
| Unknown     | 2         | 4.76%   |
| 801-900     | 1         | 2.38%   |
| 601-700     | 1         | 2.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 33        | 86.84%  |
| 16/10   | 3         | 7.89%   |
| 5/4     | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 9         | 20.93%  |
| 91-100         | 9         | 20.93%  |
| 81-90          | 3         | 6.98%   |
| 61-70          | 3         | 6.98%   |
| 51-60          | 3         | 6.98%   |
| 301-350        | 3         | 6.98%   |
| 71-80          | 2         | 4.65%   |
| 141-150        | 2         | 4.65%   |
| 101-110        | 2         | 4.65%   |
| Unknown        | 2         | 4.65%   |
| 41-50          | 1         | 2.33%   |
| 251-300        | 1         | 2.33%   |
| 151-200        | 1         | 2.33%   |
| 121-130        | 1         | 2.33%   |
| 501-1000       | 1         | 2.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 13        | 31.71%  |
| 121-160       | 11        | 26.83%  |
| 51-100        | 10        | 24.39%  |
| 161-240       | 4         | 9.76%   |
| Unknown       | 2         | 4.88%   |
| More than 240 | 1         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 34        | 68%     |
| 0     | 11        | 22%     |
| 2     | 4         | 8%      |
| 3     | 1         | 2%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 27        | 34.18%  |
| Intel                 | 24        | 30.38%  |
| Qualcomm Atheros      | 8         | 10.13%  |
| Broadcom              | 8         | 10.13%  |
| Ralink                | 2         | 2.53%   |
| Fibocom               | 2         | 2.53%   |
| VIA Technologies      | 1         | 1.27%   |
| Sierra Wireless       | 1         | 1.27%   |
| Samsung Electronics   | 1         | 1.27%   |
| Ralink Technology     | 1         | 1.27%   |
| Microchip Technology  | 1         | 1.27%   |
| Edimax Technology     | 1         | 1.27%   |
| D-Link System         | 1         | 1.27%   |
| Atheros               | 1         | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 16        | 16.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 6         | 6.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3         | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                    | 3         | 3.03%   |
| Intel Ethernet Connection (2) I219-V                                 | 3         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2         | 2.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 2.02%   |
| Intel Wireless 8265 / 8275                                           | 2         | 2.02%   |
| Intel Wireless 8260                                                  | 2         | 2.02%   |
| Intel Wireless 7260                                                  | 2         | 2.02%   |
| Intel Wireless 3165                                                  | 2         | 2.02%   |
| Intel Ethernet Connection (4) I219-LM                                | 2         | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 2.02%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                    | 2         | 2.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 2         | 2.02%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 2.02%   |
| VIA VT6102/VT6103 [Rhine-II]                                         | 1         | 1.01%   |
| Sierra Wireless EM7455                                               | 1         | 1.01%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 1         | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 1.01%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1         | 1.01%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1         | 1.01%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                | 1         | 1.01%   |
| Ralink RT5372 Wireless Adapter                                       | 1         | 1.01%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter               | 1         | 1.01%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 1.01%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                        | 1         | 1.01%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                | 1         | 1.01%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                             | 1         | 1.01%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 1.01%   |
| Microchip MCP2200 USB-to-Serial Port                                 | 1         | 1.01%   |
| Intel Wireless-AC 9260                                               | 1         | 1.01%   |
| Intel WiMAX/WiFi Link 5150                                           | 1         | 1.01%   |
| Intel WiFi Link 5100                                                 | 1         | 1.01%   |
| Intel Wi-Fi 6 AX200                                                  | 1         | 1.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 1         | 1.01%   |
| Intel Ethernet Connection I219-V                                     | 1         | 1.01%   |
| Intel Ethernet Connection I219-LM                                    | 1         | 1.01%   |
| Intel Ethernet Connection I218-LM                                    | 1         | 1.01%   |
| Intel Ethernet Connection (6) I219-V                                 | 1         | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 1.01%   |
| Intel 82579V Gigabit Network Connection                              | 1         | 1.01%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 1         | 1.01%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1         | 1.01%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                       | 1         | 1.01%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                       | 1         | 1.01%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                    | 1         | 1.01%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express             | 1         | 1.01%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                      | 1         | 1.01%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                   | 1         | 1.01%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 1.01%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 36.96%  |
| Realtek Semiconductor | 12        | 26.09%  |
| Qualcomm Atheros      | 5         | 10.87%  |
| Broadcom              | 5         | 10.87%  |
| Ralink                | 2         | 4.35%   |
| Sierra Wireless       | 1         | 2.17%   |
| Ralink Technology     | 1         | 2.17%   |
| Edimax Technology     | 1         | 2.17%   |
| D-Link System         | 1         | 2.17%   |
| Atheros               | 1         | 2.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3         | 6.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 4.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2         | 4.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 4.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 4.26%   |
| Intel Wireless 8265 / 8275                                           | 2         | 4.26%   |
| Intel Wireless 8260                                                  | 2         | 4.26%   |
| Intel Wireless 7260                                                  | 2         | 4.26%   |
| Intel Wireless 3165                                                  | 2         | 4.26%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 2         | 4.26%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 4.26%   |
| Sierra Wireless EM7455                                               | 1         | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 2.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 2.13%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 1         | 2.13%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1         | 2.13%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1         | 2.13%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                | 1         | 2.13%   |
| Ralink RT5372 Wireless Adapter                                       | 1         | 2.13%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter               | 1         | 2.13%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1         | 2.13%   |
| Intel Wireless-AC 9260                                               | 1         | 2.13%   |
| Intel WiMAX/WiFi Link 5150                                           | 1         | 2.13%   |
| Intel WiFi Link 5100                                                 | 1         | 2.13%   |
| Intel Wi-Fi 6 AX200                                                  | 1         | 2.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 1         | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 1         | 2.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 1         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 1         | 2.13%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 1         | 2.13%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070] | 1         | 2.13%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                   | 1         | 2.13%   |
| Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 2.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 25        | 52.08%  |
| Intel                 | 13        | 27.08%  |
| Qualcomm Atheros      | 4         | 8.33%   |
| Broadcom              | 4         | 8.33%   |
| VIA Technologies      | 1         | 2.08%   |
| Samsung Electronics   | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 16        | 32.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 12.24%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 6.12%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 6.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.08%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 2.04%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 2.04%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 2.04%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 2.04%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 2.04%   |
| Intel Ethernet Connection I219-V                                  | 1         | 2.04%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2.04%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.04%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.04%   |
| Broadcom NetXtreme II BCM5716 Gigabit Ethernet                    | 1         | 2.04%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 2.04%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 2.04%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 2.04%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 47        | 51.09%  |
| WiFi     | 42        | 45.65%  |
| Unknown  | 2         | 2.17%   |
| Modem    | 1         | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 40        | 59.7%   |
| WiFi     | 26        | 38.81%  |
| Unknown  | 1         | 1.49%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 35        | 70%     |
| 1     | 14        | 28%     |
| 4     | 1         | 2%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 86%     |
| Yes  | 7         | 14%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 40%     |
| Realtek Semiconductor           | 4         | 13.33%  |
| Broadcom                        | 3         | 10%     |
| ASUSTek Computer                | 3         | 10%     |
| Qualcomm Atheros Communications | 2         | 6.67%   |
| Apple                           | 2         | 6.67%   |
| Lite-On Technology              | 1         | 3.33%   |
| IMC Networks                    | 1         | 3.33%   |
| Foxconn / Hon Hai               | 1         | 3.33%   |
| Cambridge Silicon Radio         | 1         | 3.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 20%     |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 6.67%   |
| Apple Apple Broadcom Built-in Bluetooth             | 2         | 6.67%   |
| Realtek  Bluetooth 4.0 Adapter                      | 1         | 3.33%   |
| Realtek  Bluetooth 4.0 + High Speed Chip            | 1         | 3.33%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE | 1         | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.33%   |
| Lite-On Atheros Bluetooth                           | 1         | 3.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 3.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 3.33%   |
| Intel AX201 Bluetooth                               | 1         | 3.33%   |
| Intel AX200 Bluetooth                               | 1         | 3.33%   |
| IMC Networks Realtek Bluetooth Adapter              | 1         | 3.33%   |
| Foxconn / Hon Hai Bluetooth USB Module              | 1         | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.33%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 3.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 3.33%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.33%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 3.33%   |
| ASUS Bluetooth Controller                           | 1         | 3.33%   |
| ASUS ASUS USB-BT500                                 | 1         | 3.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 36        | 49.32%  |
| AMD                 | 17        | 23.29%  |
| Nvidia              | 9         | 12.33%  |
| Sony                | 2         | 2.74%   |
| Corsair             | 2         | 2.74%   |
| XMOS                | 1         | 1.37%   |
| VIA Technologies    | 1         | 1.37%   |
| Quanta              | 1         | 1.37%   |
| LG Electronics      | 1         | 1.37%   |
| Creative Technology | 1         | 1.37%   |
| C-Media Electronics | 1         | 1.37%   |
| Audio-Technica      | 1         | 1.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 6.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 5.62%   |
| AMD FCH Azalia Controller                                                  | 5         | 5.62%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 4.49%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 4.49%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 4.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 3.37%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 3.37%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 3.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 2.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 2.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 2.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 2.25%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 2.25%   |
| Corsair Corsair VOID PRO Wireless Gaming Headset                           | 2         | 2.25%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 2.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 2.25%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 2.25%   |
| XMOS Shanling UA2                                                          | 1         | 1.12%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 1.12%   |
| Sony Sony Audio                                                            | 1         | 1.12%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 1.12%   |
| Quanta USB Audio Realtek USB2.0 Audio Microphone                           | 1         | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 1.12%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 1.12%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.12%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 1.12%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 1.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 1.12%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 1.12%   |
| LG Electronics USB Audio LG UltraFine Display Audio                        | 1         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.12%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 1.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 1.12%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 1.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 1.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 1.12%   |
| Creative Technology Sound Blaster Omni Surround 5.1                        | 1         | 1.12%   |
| Corsair Corsair ST100 Headset Output                                       | 1         | 1.12%   |
| C-Media Electronics Audio Device                                           | 1         | 1.12%   |
| Audio-Technica AT2020USB+                                                  | 1         | 1.12%   |
| AMD Vega 20 HDMI Audio [Radeon VII]                                        | 1         | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1         | 1.12%   |
| AMD High Definition Audio Controller                                       | 1         | 1.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 1.12%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 1.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 16        | 26.67%  |
| Samsung Electronics | 12        | 20%     |
| Unknown             | 8         | 13.33%  |
| Micron Technology   | 6         | 10%     |
| Kingston            | 4         | 6.67%   |
| G.Skill             | 4         | 6.67%   |
| Crucial             | 3         | 5%      |
| Transcend           | 2         | 3.33%   |
| Nanya Technology    | 2         | 3.33%   |
| Corsair             | 2         | 3.33%   |
| Elpida              | 1         | 1.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 8         | 12.7%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s    | 3         | 4.76%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 3.17%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 2400MT/s     | 2         | 3.17%   |
| Transcend RAM TS512MSK64V1N 4GB SODIMM 800MT/s            | 1         | 1.59%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR 667MT/s          | 1         | 1.59%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 1         | 1.59%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s      | 1         | 1.59%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s     | 1         | 1.59%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s      | 1         | 1.59%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s      | 1         | 1.59%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1         | 1.59%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 1.59%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1         | 1.59%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s    | 1         | 1.59%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s    | 1         | 1.59%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s   | 1         | 1.59%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 1.59%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s    | 1         | 1.59%   |
| Samsung RAM Module 16GB SODIMM DDR4 2133MT/s              | 1         | 1.59%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1333MT/s     | 1         | 1.59%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1         | 1.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 1         | 1.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s     | 1         | 1.59%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s     | 1         | 1.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s     | 1         | 1.59%   |
| Samsung RAM M393B5170FHD-CF8 4GB DIMM DDR3 1066MT/s       | 1         | 1.59%   |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s       | 1         | 1.59%   |
| Nanya RAM NT4GC64B88B1NF-DI 4GB DIMM DDR3 1600MT/s        | 1         | 1.59%   |
| Nanya RAM Module 4GB Row Of Chips LPDDR3 2133MT/s         | 1         | 1.59%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s      | 1         | 1.59%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s      | 1         | 1.59%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 1         | 1.59%   |
| Micron RAM 36JSZF51272PZ1G4G1 4GB DIMM DDR3 1333MT/s      | 1         | 1.59%   |
| Micron RAM 36JSZF1G72PZ-1G4D 8GB DIMM DDR3 1333MT/s       | 1         | 1.59%   |
| Micron RAM 36JSF1G72PZ-1 8GB DIMM DDR3 1600MT/s           | 1         | 1.59%   |
| Kingston RAM K531R8-ETB 4GB DIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s    | 1         | 1.59%   |
| Kingston RAM 9905711-015.A00G 4GB SODIMM DDR4 2400MT/s    | 1         | 1.59%   |
| G.Skill RAM F4-3600C17-16GTZSW 16GB DIMM DDR4 3600MT/s    | 1         | 1.59%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s       | 1         | 1.59%   |
| G.Skill RAM F4-2133C15-8GRS 8GB SODIMM DDR4 2133MT/s      | 1         | 1.59%   |
| G.Skill RAM F3-1600C9-4GRSL 4GB SODIMM DDR3 1600MT/s      | 1         | 1.59%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s     | 1         | 1.59%   |
| Crucial RAM CT16G4SFD8266.C16FN 16GB SODIMM DDR4 2133MT/s | 1         | 1.59%   |
| Crucial RAM BLS8G4D240FSB.16FBD 8GB DIMM DDR4 2933MT/s    | 1         | 1.59%   |
| Crucial RAM BLS16G4S26BFSD.16FD 16GB SODIMM DDR4 2400MT/s | 1         | 1.59%   |
| Corsair RAM Module 8GB DIMM DDR4 3200MT/s                 | 1         | 1.59%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3200MT/s    | 1         | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 22        | 43.14%  |
| DDR3    | 18        | 35.29%  |
| DDR2    | 3         | 5.88%   |
| SDRAM   | 2         | 3.92%   |
| LPDDR3  | 2         | 3.92%   |
| DDR     | 2         | 3.92%   |
| DRAM    | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 60.78%  |
| DIMM         | 17        | 33.33%  |
| Chip         | 2         | 3.92%   |
| Row Of Chips | 1         | 1.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 22        | 40%     |
| 8192  | 18        | 32.73%  |
| 16384 | 8         | 14.55%  |
| 2048  | 6         | 10.91%  |
| 1024  | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 23.64%  |
| 2400    | 9         | 16.36%  |
| 2133    | 7         | 12.73%  |
| 1333    | 6         | 10.91%  |
| 3200    | 5         | 9.09%   |
| 2667    | 4         | 7.27%   |
| 667     | 2         | 3.64%   |
| Unknown | 2         | 3.64%   |
| 3600    | 1         | 1.82%   |
| 2933    | 1         | 1.82%   |
| 1334    | 1         | 1.82%   |
| 1066    | 1         | 1.82%   |
| 975     | 1         | 1.82%   |
| 800     | 1         | 1.82%   |
| 533     | 1         | 1.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


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

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 4         | 16.67%  |
| Acer                                   | 4         | 16.67%  |
| Quanta                                 | 3         | 12.5%   |
| Microdia                               | 2         | 8.33%   |
| Lite-On Technology                     | 2         | 8.33%   |
| IMC Networks                           | 2         | 8.33%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 8.33%   |
| Suyin                                  | 1         | 4.17%   |
| Sunplus Innovation Technology          | 1         | 4.17%   |
| Realtek Semiconductor                  | 1         | 4.17%   |
| Intel                                  | 1         | 4.17%   |
| Alcor Micro                            | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Acer Integrated Camera                                         | 3         | 12.5%   |
| Quanta Realtek DMFT - RGB                                      | 2         | 8.33%   |
| Chicony Integrated Camera                                      | 2         | 8.33%   |
| Suyin USB 2.0 UVC 1.3M WebCam                                  | 1         | 4.17%   |
| Sunplus Integrated Webcam                                      | 1         | 4.17%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 1         | 4.17%   |
| Quanta Front camera                                            | 1         | 4.17%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 4.17%   |
| Microdia Integrated Webcam                                     | 1         | 4.17%   |
| Lite-On Realtek PC Camera                                      | 1         | 4.17%   |
| Lite-On HP Universal Camera                                    | 1         | 4.17%   |
| Intel WiMAX Connection 2400m                                   | 1         | 4.17%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 1         | 4.17%   |
| Chicony HP HD Webcam [Fixed]                                   | 1         | 4.17%   |
| Chicony Chicony USB2.0 Camera                                  | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 1         | 4.17%   |
| Alcor Micro HP WebCam-101                                      | 1         | 4.17%   |
| Acer Lenovo EasyCamera                                         | 1         | 4.17%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 4         | 66.67%  |
| Synaptics        | 1         | 16.67%  |
| AuthenTec        | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                   | 2         | 33.33%  |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 16.67%  |
| AuthenTec AES1600                                 | 1         | 16.67%  |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 20        | 40%     |
| 2     | 14        | 28%     |
| 0     | 9         | 18%     |
| 3     | 4         | 8%      |
| 4     | 3         | 6%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 29        | 42.03%  |
| Net/wireless             | 17        | 24.64%  |
| Fingerprint reader       | 6         | 8.7%    |
| Bluetooth                | 6         | 8.7%    |
| Firewire controller      | 5         | 7.25%   |
| Network                  | 3         | 4.35%   |
| Card reader              | 2         | 2.9%    |
| Sound                    | 1         | 1.45%   |

