OpenBSD 7.1 - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenBSD_7.1/Desktop/README.md) and [notebooks](/Dist/OpenBSD_7.1/Notebook/README.md).

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

Total: 51

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| MSI           | MS-6788                     | Desktop     | [f750cb83e3](https://bsd-hardware.info/?probe=f750cb83e3) | May 31, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [3b03bdf595](https://bsd-hardware.info/?probe=3b03bdf595) | May 29, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown       | Raspberry Pi 3 Model B P... | Desktop     | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [5c7af4b143](https://bsd-hardware.info/?probe=5c7af4b143) | May 21, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| MSI           | MS-7C82                     | Desktop     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [0419c52079](https://bsd-hardware.info/?probe=0419c52079) | May 11, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9f6b4f114d](https://bsd-hardware.info/?probe=9f6b4f114d) | May 11, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [64600e1c24](https://bsd-hardware.info/?probe=64600e1c24) | May 11, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [49d1cd3009](https://bsd-hardware.info/?probe=49d1cd3009) | May 10, 2022 |
| Unknown       | Raspberry Pi 4 Model B R... | Desktop     | [154799d7fa](https://bsd-hardware.info/?probe=154799d7fa) | May 08, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| Matsushita... | CF-48V4KNDQM                | Notebook    | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | Notebook    | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | Notebook    | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | Notebook    | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Intel         | Q3XXG4-P                    | Desktop     | [ed04988a23](https://bsd-hardware.info/?probe=ed04988a23) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | Notebook    | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | Notebook    | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | Notebook    | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | Notebook    | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| MSI           | MS-7C37                     | Desktop     | [aaab7cf22a](https://bsd-hardware.info/?probe=aaab7cf22a) | Apr 28, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [9a61443be9](https://bsd-hardware.info/?probe=9a61443be9) | Apr 25, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| PC Engines    | APU2                        | Desktop     | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Intel         | DH67BL                      | Desktop     | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA     | SH series                   | Desktop     | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | Desktop     | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| DEXP          | NAVIS P100                  | Notebook    | [a9c8814bf8](https://bsd-hardware.info/?probe=a9c8814bf8) | Apr 22, 2022 |
| Sony          | VPCL22Z1R                   | Desktop     | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| Lenovo        | ThinkPad X121e 3053A52      | Notebook    | [68d0bf2a99](https://bsd-hardware.info/?probe=68d0bf2a99) | Apr 22, 2022 |
| Samsung       | DP700A3D-X01RU SEC_SW_RE... | All in one  | [22febd212f](https://bsd-hardware.info/?probe=22febd212f) | Apr 22, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek       | P10S-I Series               | Desktop     | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b4a6761ab3](https://bsd-hardware.info/?probe=b4a6761ab3) | Apr 21, 2022 |
| Dell          | G5 5090                     | Desktop     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [086a58a68f](https://bsd-hardware.info/?probe=086a58a68f) | Mar 24, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | Desktop     | [32d27b9404](https://bsd-hardware.info/?probe=32d27b9404) | Mar 19, 2022 |
| Lenovo        | ThinkCentre M93p 10AAS25... | Desktop     | [7361628ed9](https://bsd-hardware.info/?probe=7361628ed9) | Mar 19, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [e973d1e806](https://bsd-hardware.info/?probe=e973d1e806) | Mar 18, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [ed0add65a3](https://bsd-hardware.info/?probe=ed0add65a3) | Mar 14, 2022 |
| Lenovo        | Yoga 330-11IGM 81A6         | Notebook    | [621ae0501b](https://bsd-hardware.info/?probe=621ae0501b) | Mar 10, 2022 |
| Unknown       | LeMaker Banana Pi           | Desktop     | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [4bc5573cf5](https://bsd-hardware.info/?probe=4bc5573cf5) | Mar 02, 2022 |
| Lenovo        | ThinkPad X200 745969G       | Notebook    | [a4341268d0](https://bsd-hardware.info/?probe=a4341268d0) | Feb 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [62f4e0a060](https://bsd-hardware.info/?probe=62f4e0a060) | Feb 21, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 39        | 78%     |
| i386  | 5         | 10%     |
| arm64 | 5         | 10%     |
| armv7 | 1         | 2%      |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 39        | 78%     |
| fvwm         | 5         | 10%     |
| XFCE         | 4         | 8%      |
| MATE         | 1         | 2%      |
| Console      | 1         | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 36        | 72%     |
| Console | 14        | 28%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 50        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 41        | 82%     |
| ru_RU   | 8         | 16%     |
| en_GB   | 1         | 2%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 26        | 52%     |
| EFI  | 24        | 48%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ffs  | 50        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| MBR  | 32        | 64%     |
| GPT  | 18        | 36%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 13        | 26%     |
| Unknown                        | 7         | 14%     |
| ASUSTek Computer               | 6         | 12%     |
| MSI                            | 4         | 8%      |
| TUXEDO                         | 2         | 4%      |
| Panasonic                      | 2         | 4%      |
| Matsushita Electric Industrial | 2         | 4%      |
| Intel                          | 2         | 4%      |
| Dell                           | 2         | 4%      |
| Sony                           | 1         | 2%      |
| Samsung Electronics            | 1         | 2%      |
| PC Engines                     | 1         | 2%      |
| KOHJINSHA                      | 1         | 2%      |
| Hewlett-Packard                | 1         | 2%      |
| Gigabyte Technology            | 1         | 2%      |
| Fujitsu                        | 1         | 2%      |
| DEXP                           | 1         | 2%      |
| Biostar                        | 1         | 2%      |
| Apple                          | 1         | 2%      |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 7         | 14%     |
| Lenovo ThinkPad X200 745969G                | 3         | 6%      |
| TUXEDO Pulse 15 Gen1                        | 1         | 2%      |
| TUXEDO Aura 15 Gen1                         | 1         | 2%      |
| Sony VPCL22Z1R                              | 1         | 2%      |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 2%      |
| PC Engines APU2                             | 1         | 2%      |
| Panasonic CF-53AAGHYDM                      | 1         | 2%      |
| Panasonic CF-52PFPBSFQ                      | 1         | 2%      |
| MSI MS-7C82                                 | 1         | 2%      |
| MSI MS-7C37                                 | 1         | 2%      |
| MSI MS-6788                                 | 1         | 2%      |
| MSI Modern 14 B11MOL                        | 1         | 2%      |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2%      |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2%      |
| Lenovo Yoga 330-11IGM 81A6                  | 1         | 2%      |
| Lenovo ThinkPad X250 20CLS4WV08             | 1         | 2%      |
| Lenovo ThinkPad X240 20ALA0AHRT             | 1         | 2%      |
| Lenovo ThinkPad X220 429043U                | 1         | 2%      |
| Lenovo ThinkPad X121e 3053A52               | 1         | 2%      |
| Lenovo ThinkPad T430 2347GZU                | 1         | 2%      |
| Lenovo ThinkPad T420s 41742BU               | 1         | 2%      |
| Lenovo ThinkPad T410 2537N24                | 1         | 2%      |
| Lenovo ThinkPad E14 Gen 2 20T6003BRT        | 1         | 2%      |
| Lenovo ThinkCentre M93p 10AAS25M00          | 1         | 2%      |
| KOHJINSHA SH series                         | 1         | 2%      |
| Intel Q3XXG4-P                              | 1         | 2%      |
| Intel DH67BL                                | 1         | 2%      |
| HP Pavilion Laptop 15-cs0xxx                | 1         | 2%      |
| Gigabyte H81M-S2PV                          | 1         | 2%      |
| Fujitsu LIFEBOOK E752                       | 1         | 2%      |
| DEXP NAVIS P100                             | 1         | 2%      |
| Dell Vostro 3550                            | 1         | 2%      |
| Dell G5 5090                                | 1         | 2%      |
| Biostar G31-M7 TE                           | 1         | 2%      |
| ASUS Z170-K                                 | 1         | 2%      |
| ASUS PRIME X470-PRO                         | 1         | 2%      |
| ASUS PRIME B550M-K                          | 1         | 2%      |
| ASUS P10S-I Series                          | 1         | 2%      |
| ASUS M4A88TD-V EVO/USB3                     | 1         | 2%      |
| ASUS 1000HE                                 | 1         | 2%      |
| Apple MacBookPro5,3                         | 1         | 2%      |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 11        | 22%     |
| Unknown                                     | 7         | 14%     |
| ASUS PRIME                                  | 2         | 4%      |
| TUXEDO Pulse                                | 1         | 2%      |
| TUXEDO Aura                                 | 1         | 2%      |
| Sony VPCL22Z1R                              | 1         | 2%      |
| Samsung DP700A3D                            | 1         | 2%      |
| PC Engines APU2                             | 1         | 2%      |
| Panasonic CF-53AAGHYDM                      | 1         | 2%      |
| Panasonic CF-52PFPBSFQ                      | 1         | 2%      |
| MSI MS-7C82                                 | 1         | 2%      |
| MSI MS-7C37                                 | 1         | 2%      |
| MSI MS-6788                                 | 1         | 2%      |
| MSI Modern                                  | 1         | 2%      |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 2%      |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 2%      |
| Lenovo Yoga                                 | 1         | 2%      |
| Lenovo ThinkCentre                          | 1         | 2%      |
| KOHJINSHA SH                                | 1         | 2%      |
| Intel Q3XXG4-P                              | 1         | 2%      |
| Intel DH67BL                                | 1         | 2%      |
| HP Pavilion                                 | 1         | 2%      |
| Gigabyte H81M-S2PV                          | 1         | 2%      |
| Fujitsu LIFEBOOK                            | 1         | 2%      |
| DEXP NAVIS                                  | 1         | 2%      |
| Dell Vostro                                 | 1         | 2%      |
| Dell G5                                     | 1         | 2%      |
| Biostar G31-M7                              | 1         | 2%      |
| ASUS Z170-K                                 | 1         | 2%      |
| ASUS P10S-I                                 | 1         | 2%      |
| ASUS M4A88TD-V                              | 1         | 2%      |
| ASUS 1000HE                                 | 1         | 2%      |
| Apple MacBookPro5                           | 1         | 2%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7         | 14%     |
| 2018    | 6         | 12%     |
| 2020    | 5         | 10%     |
| 2011    | 5         | 10%     |
| 2009    | 5         | 10%     |
| 2021    | 4         | 8%      |
| 2010    | 4         | 8%      |
| 2016    | 2         | 4%      |
| 2015    | 2         | 4%      |
| 2014    | 2         | 4%      |
| 2013    | 2         | 4%      |
| 2022    | 1         | 2%      |
| 2019    | 1         | 2%      |
| 2012    | 1         | 2%      |
| 2007    | 1         | 2%      |
| 2006    | 1         | 2%      |
| 2002    | 1         | 2%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 25        | 50%     |
| Notebook   | 24        | 48%     |
| All in one | 1         | 2%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 49        | 98%     |
| Yes  | 1         | 2%      |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 14        | 28%     |
| 4.01-8.0   | 12        | 24%     |
| 16.01-24.0 | 7         | 14%     |
| 3.01-4.0   | 6         | 12%     |
| 2.01-3.0   | 5         | 10%     |
| 0.51-1.0   | 3         | 6%      |
| 1.01-2.0   | 2         | 4%      |
| 32.01-64.0 | 1         | 2%      |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 45        | 90%     |
| 0        | 4         | 8%      |
| 0.51-1.0 | 1         | 2%      |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 31        | 62%     |
| 2      | 10        | 20%     |
| 3      | 5         | 10%     |
| 4      | 3         | 6%      |
| 6      | 1         | 2%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 82%     |
| No        | 9         | 18%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 31        | 62%     |
| No        | 19        | 38%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 26        | 52%     |
| Yes       | 24        | 48%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 13        | 26%     |
| Canada      | 11        | 22%     |
| USA         | 4         | 8%      |
| Poland      | 4         | 8%      |
| Netherlands | 4         | 8%      |
| UK          | 3         | 6%      |
| Italy       | 2         | 4%      |
| Spain       | 1         | 2%      |
| Norway      | 1         | 2%      |
| India       | 1         | 2%      |
| Germany     | 1         | 2%      |
| France      | 1         | 2%      |
| Czechia     | 1         | 2%      |
| Chile       | 1         | 2%      |
| Austria     | 1         | 2%      |
| Argentina   | 1         | 2%      |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Montreal            | 10        | 20%     |
| Vladivostok         | 6         | 12%     |
| Poortugaal          | 4         | 8%      |
| Gdansk              | 3         | 6%      |
| Milan               | 2         | 4%      |
| West Valley City    | 1         | 2%      |
| Vienna              | 1         | 2%      |
| Valdivia            | 1         | 2%      |
| Tambov              | 1         | 2%      |
| Sutton              | 1         | 2%      |
| Starogard Gdański  | 1         | 2%      |
| St. Albert          | 1         | 2%      |
| St Petersburg       | 1         | 2%      |
| Springboro          | 1         | 2%      |
| Reutov              | 1         | 2%      |
| Ozersk              | 1         | 2%      |
| Oslo                | 1         | 2%      |
| Orenburg            | 1         | 2%      |
| Oakland             | 1         | 2%      |
| Newcastle upon Tyne | 1         | 2%      |
| Moscow              | 1         | 2%      |
| Memmingen           | 1         | 2%      |
| Kolomna             | 1         | 2%      |
| Edinburgh           | 1         | 2%      |
| Delhi               | 1         | 2%      |
| Columbus            | 1         | 2%      |
| Český Těšín    | 1         | 2%      |
| Buenos Aires        | 1         | 2%      |
| Biot                | 1         | 2%      |
| Alcorisa            | 1         | 2%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 13     | 18.75%  |
| NVMe                | 9         | 11     | 14.06%  |
| Seagate             | 8         | 10     | 12.5%   |
| Samsung Electronics | 7         | 7      | 10.94%  |
| SanDisk             | 3         | 3      | 4.69%   |
| Innostor            | 3         | 3      | 4.69%   |
| Hitachi             | 3         | 3      | 4.69%   |
| OPENBSD             | 2         | 2      | 3.13%   |
| Kingston            | 2         | 2      | 3.13%   |
| HGST                | 2         | 2      | 3.13%   |
| XPG                 | 1         | 1      | 1.56%   |
| USB                 | 1         | 1      | 1.56%   |
| Toshiba             | 1         | 1      | 1.56%   |
| StoreJet            | 1         | 1      | 1.56%   |
| OWC                 | 1         | 1      | 1.56%   |
| OCZ                 | 1         | 1      | 1.56%   |
| LDLC F6+            | 1         | 1      | 1.56%   |
| KingSpec            | 1         | 1      | 1.56%   |
| Intel               | 1         | 1      | 1.56%   |
| Hoodisk             | 1         | 1      | 1.56%   |
| Crucial             | 1         | 1      | 1.56%   |
| CORSAIR             | 1         | 1      | 1.56%   |
| A-DATA Technology   | 1         | 1      | 1.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung HM321HI 320GB              | 3         | 4.55%   |
| NVMe Samsung SSD 980 1TB           | 3         | 4.55%   |
| Innostor SSD 15GB                  | 3         | 4.55%   |
| OPENBSD SR RAID 1 752GB            | 2         | 3.03%   |
| XPG SX950U 240GB                   | 1         | 1.52%   |
| WDC WD800JD-60LSA5 80GB            | 1         | 1.52%   |
| WDC WD7500BPKX-00HPJT0 752GB       | 1         | 1.52%   |
| WDC WD7500BPKT-75PK4T0 752GB       | 1         | 1.52%   |
| WDC WD7500BPKT-00PK4T0 752GB       | 1         | 1.52%   |
| WDC WD6400AARS-00Y5B1 640GB        | 1         | 1.52%   |
| WDC WD5003AZEX-00K1GA0 500GB       | 1         | 1.52%   |
| WDC WD5000LPLX-00ZNTT0 500GB       | 1         | 1.52%   |
| WDC WD40EFZX-68AWUN0 4TB           | 1         | 1.52%   |
| WDC WD3200BEVE-00A0HT0 320GB       | 1         | 1.52%   |
| WDC WD20PURX-64P6ZY0 2TB           | 1         | 1.52%   |
| WDC WD10JPLX-00MBPT0 1TB           | 1         | 1.52%   |
| WDC WD10EZEX-00MFCA0 1TB           | 1         | 1.52%   |
| USB SanDisk 3.2Gen1 64GB           | 1         | 1.52%   |
| Toshiba DT01ACA050 500GB           | 1         | 1.52%   |
| StoreJet Transcend 120GB           | 1         | 1.52%   |
| Seagate ST9500420AS 500GB          | 1         | 1.52%   |
| Seagate ST9160821A 160GB           | 1         | 1.52%   |
| Seagate ST3750640NS 752GB          | 1         | 1.52%   |
| Seagate ST3250318AS 250GB          | 1         | 1.52%   |
| Seagate ST250DM000-1BD141 250GB    | 1         | 1.52%   |
| Seagate ST2000DM006-2DM164 2TB     | 1         | 1.52%   |
| Seagate ST1000VX000-1CU162 1TB     | 1         | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1.52%   |
| Seagate ST1000DM010-2EP102 1TB     | 1         | 1.52%   |
| SanDisk SD7UB3Q256G1001 256GB      | 1         | 1.52%   |
| SanDisk Extreme Pro 128GB          | 1         | 1.52%   |
| SanDisk Extreme 55AE 500GB         | 1         | 1.52%   |
| Samsung SSD 860 EVO 250GB          | 1         | 1.52%   |
| Samsung Portable SSD T3 250GB      | 1         | 1.52%   |
| Samsung MZ7PC128HAFU-000L1 128GB   | 1         | 1.52%   |
| Samsung Flash Drive FIT 32GB       | 1         | 1.52%   |
| OWC Mercury Electra 6G SSD         | 1         | 1.52%   |
| OCZ VERTEX3 120GB                  | 1         | 1.52%   |
| NVMe WDS100T3X0C-00SJ 1TB          | 1         | 1.52%   |
| NVMe WDC WDS500G2B0C- 500GB        | 1         | 1.52%   |
| NVMe WDC PC SN530 SDB 256GB        | 1         | 1.52%   |
| NVMe TOSHIBA-RC100 240GB           | 1         | 1.52%   |
| NVMe Samsung SSD 970 250GB         | 1         | 1.52%   |
| NVMe PC SN520 WD 256GB             | 1         | 1.52%   |
| NVMe KINGSTON OM8PDP3 256GB        | 1         | 1.52%   |
| LDLC F6+ M.2 120 120GB             | 1         | 1.52%   |
| Kingston SV300S37A120G 120GB       | 1         | 1.52%   |
| Kingston SMS200S330G 32GB          | 1         | 1.52%   |
| KingSpec NT-512 512GB              | 1         | 1.52%   |
| Intel SSDSC2BF180A4L 180GB         | 1         | 1.52%   |
| Hoodisk SSD 32GB                   | 1         | 1.52%   |
| Hitachi HUA723020ALA640 2TB        | 1         | 1.52%   |
| Hitachi HTS723232A7A364 320GB      | 1         | 1.52%   |
| Hitachi HTS541612J9AT00 120GB      | 1         | 1.52%   |
| HGST HUS724020ALA640 2TB           | 1         | 1.52%   |
| HGST HTS541010B7E610 1TB           | 1         | 1.52%   |
| Crucial CT2000MX500SSD1 2TB        | 1         | 1.52%   |
| CORSAIR FORCE LX SSD 256GB         | 1         | 1.52%   |
| A-DATA SP550 480GB                 | 1         | 1.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 13     | 30.77%  |
| Seagate             | 8         | 10     | 20.51%  |
| Samsung Electronics | 4         | 4      | 10.26%  |
| NVMe                | 4         | 5      | 10.26%  |
| Hitachi             | 3         | 3      | 7.69%   |
| OPENBSD             | 2         | 2      | 5.13%   |
| HGST                | 2         | 2      | 5.13%   |
| USB                 | 1         | 1      | 2.56%   |
| Toshiba             | 1         | 1      | 2.56%   |
| StoreJet            | 1         | 1      | 2.56%   |
| LDLC F6+            | 1         | 1      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| NVMe                | 4         | 5      | 16.67%  |
| SanDisk             | 3         | 3      | 12.5%   |
| Samsung Electronics | 3         | 3      | 12.5%   |
| Innostor            | 3         | 3      | 12.5%   |
| Kingston            | 2         | 2      | 8.33%   |
| XPG                 | 1         | 1      | 4.17%   |
| OWC                 | 1         | 1      | 4.17%   |
| OCZ                 | 1         | 1      | 4.17%   |
| KingSpec            | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Hoodisk             | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |
| CORSAIR             | 1         | 1      | 4.17%   |
| A-DATA Technology   | 1         | 1      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 43     | 56%     |
| SSD  | 21        | 25     | 42%     |
| NVMe | 1         | 1      | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 45        | 68     | 97.83%  |
| NVMe | 1         | 1      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 42     | 60.38%  |
| 0.51-1.0   | 17        | 19     | 32.08%  |
| 1.01-2.0   | 3         | 5      | 5.66%   |
| 3.01-4.0   | 1         | 2      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 13        | 26%     |
| 251-500        | 12        | 24%     |
| 101-250        | 11        | 22%     |
| 51-100         | 7         | 14%     |
| 1-20           | 6         | 12%     |
| More than 3000 | 1         | 2%      |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 46        | 92%     |
| 101-250   | 2         | 4%      |
| 21-50     | 1         | 2%      |
| 2001-3000 | 1         | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| XPG SX950U 240GB                | 1         | 1      | 12.5%   |
| Seagate ST9500420AS 500GB       | 1         | 1      | 12.5%   |
| Seagate ST3750640NS 752GB       | 1         | 2      | 12.5%   |
| Seagate ST250DM000-1BD141 250GB | 1         | 1      | 12.5%   |
| Seagate ST2000DM006-2DM164 2TB  | 1         | 1      | 12.5%   |
| SanDisk SD7UB3Q256G1001 256GB   | 1         | 1      | 12.5%   |
| OCZ VERTEX3 120GB               | 1         | 1      | 12.5%   |
| A-DATA Technology SP550 480GB   | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 4         | 5      | 50%     |
| XPG               | 1         | 1      | 12.5%   |
| SanDisk           | 1         | 1      | 12.5%   |
| OCZ               | 1         | 1      | 12.5%   |
| A-DATA Technology | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 5      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 4         | 4      | 50%     |
| HDD  | 4         | 5      | 50%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 36        | 44     | 65.45%  |
| Detected | 11        | 15     | 20%     |
| Malfunc  | 7         | 9      | 12.73%  |
| Failed   | 1         | 1      | 1.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 33        | 62.26%  |
| AMD                         | 7         | 13.21%  |
| Samsung Electronics         | 4         | 7.55%   |
| Sandisk                     | 3         | 5.66%   |
| VIA Technologies            | 1         | 1.89%   |
| Toshiba                     | 1         | 1.89%   |
| Nvidia                      | 1         | 1.89%   |
| Marvell Technology Group    | 1         | 1.89%   |
| Kingston Technology Company | 1         | 1.89%   |
| ASMedia Technology          | 1         | 1.89%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 7.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 5.26%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 5.26%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 3         | 5.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 3.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 3.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 3.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 3.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 3.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 2         | 3.51%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 3.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 3.51%   |
| VIA VT6415 PATA IDE Host Controller                                                    | 1         | 1.75%   |
| Toshiba BG3 NVMe SSD Controller                                                        | 1         | 1.75%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 1.75%   |
| Sandisk unknown                                                                        | 1         | 1.75%   |
| Sandisk PC SN530                                                                       | 1         | 1.75%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 1.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 1.75%   |
| Samsung NVMe SSD Controller 980                                                        | 1         | 1.75%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.75%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                       | 1         | 1.75%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 1.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 1         | 1.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 1         | 1.75%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 1         | 1.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 1.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 1.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 1         | 1.75%   |
| Intel 82801EB (ICH5) SATA Controller                                                   | 1         | 1.75%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 1.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 1         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 1         | 1.75%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 1         | 1.75%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 1         | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                                 | 1         | 1.75%   |
| AMD 400 Series Chipset SATA Controller                                                 | 1         | 1.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 34        | 66.67%  |
| NVMe | 9         | 17.65%  |
| IDE  | 8         | 15.69%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 34        | 68%     |
| AMD    | 9         | 18%     |
| ARM    | 6         | 12%     |
| 11th   | 1         | 2%      |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz                         | 4         | 8%      |
| ARM Cortex-A72 r0p3                                       | 4         | 8%      |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz                      | 3         | 6%      |
| Intel Core i5 CPU M 520 @ 2.40GHz                         | 2         | 4%      |
| AMD Ryzen 7 4700U with Radeon Graphics                    | 2         | 4%      |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                       | 1         | 2%      |
| Intel Pentium Silver N6000 @ 1.10GHz                      | 1         | 2%      |
| Intel Pentium Silver N5000 CPU @ 1.10GHz                  | 1         | 2%      |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz               | 1         | 2%      |
| Intel Pentium 4 Mobile CPU 1.60GHz                        | 1         | 2%      |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class)    | 1         | 2%      |
| Intel Genuine processor 600MHz ("GenuineIntel" 686-class) | 1         | 2%      |
| Intel Genuine CPU T2300 @ 1.66GHz                         | 1         | 2%      |
| Intel Core i7-9700K CPU @ 3.60GHz                         | 1         | 2%      |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 1         | 2%      |
| Intel Core i7-3520M CPU @ 2.90GHz                         | 1         | 2%      |
| Intel Core i7-2670QM CPU @ 2.20GHz                        | 1         | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz                         | 1         | 2%      |
| Intel Core i5-5300U CPU @ 2.30GHz                         | 1         | 2%      |
| Intel Core i5-4570T CPU @ 2.90GHz                         | 1         | 2%      |
| Intel Core i5-3470T CPU @ 2.90GHz                         | 1         | 2%      |
| Intel Core i5-3320M CPU @ 2.60GHz                         | 1         | 2%      |
| Intel Core i5-10400F CPU @ 2.90GHz                        | 1         | 2%      |
| Intel Core i3-5010U CPU @ 2.10GHz                         | 1         | 2%      |
| Intel Core i3-4010U CPU @ 1.70GHz                         | 1         | 2%      |
| Intel Core i3-3225 CPU @ 3.30GHz                          | 1         | 2%      |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz                      | 1         | 2%      |
| Intel Celeron CPU N3350 @ 1.10GHz                         | 1         | 2%      |
| Intel Celeron CPU G1820 @ 2.70GHz                         | 1         | 2%      |
| Intel Atom CPU N280 @ 1.66GHz                             | 1         | 2%      |
| ARM Cortex-A7 r0p4                                        | 1         | 2%      |
| ARM Cortex-A53 r0p4                                       | 1         | 2%      |
| AMD Ryzen 7 5800X 8-Core Processor                        | 1         | 2%      |
| AMD Ryzen 7 4800H with Radeon Graphics                    | 1         | 2%      |
| AMD Ryzen 5 5600X 6-Core Processor                        | 1         | 2%      |
| AMD Ryzen 3 2200G with Radeon Vega Graphics               | 1         | 2%      |
| AMD GX-412TC SOC                                          | 1         | 2%      |
| AMD E-300 APU with Radeon HD Graphics                     | 1         | 2%      |
| AMD Athlon II X4 640 Processor                            | 1         | 2%      |
| 11th Gen Intel Core i5-1135G7 @ 2.40GHz                   | 1         | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 12        | 24%     |
| ARM Cortex              | 6         | 12%     |
| Intel Core i7           | 4         | 8%      |
| Intel Core 2 Duo        | 4         | 8%      |
| AMD Ryzen 7             | 4         | 8%      |
| Intel Core i3           | 3         | 6%      |
| Intel Pentium Silver    | 2         | 4%      |
| Intel Pentium 4         | 2         | 4%      |
| Intel Genuine           | 2         | 4%      |
| Intel Celeron           | 2         | 4%      |
| Other                   | 1         | 2%      |
| Intel Xeon              | 1         | 2%      |
| Intel Pentium Dual-Core | 1         | 2%      |
| Intel Atom              | 1         | 2%      |
| AMD Ryzen 5             | 1         | 2%      |
| AMD Ryzen 3             | 1         | 2%      |
| AMD GX                  | 1         | 2%      |
| AMD E                   | 1         | 2%      |
| AMD Athlon II X4        | 1         | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 17        | 34%     |
| Unknown | 16        | 32%     |
| 4       | 9         | 18%     |
| 8       | 3         | 6%      |
| 1       | 3         | 6%      |
| 16      | 1         | 2%      |
| 12      | 1         | 2%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 34        | 68%     |
| Unknown | 16        | 32%     |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 19        | 38%     |
| 2       | 17        | 34%     |
| 1       | 14        | 28%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 10        | 20%     |
| SandyBridge   | 5         | 10%     |
| Penryn        | 5         | 10%     |
| IvyBridge     | 4         | 8%      |
| Zen 2         | 3         | 6%      |
| Haswell       | 3         | 6%      |
| Westmere      | 2         | 4%      |
| Skylake       | 2         | 4%      |
| P6            | 2         | 4%      |
| NetBurst      | 2         | 4%      |
| KabyLake      | 2         | 4%      |
| Broadwell     | 2         | 4%      |
| Zen 3         | 1         | 2%      |
| Zen           | 1         | 2%      |
| Puma          | 1         | 2%      |
| K10           | 1         | 2%      |
| Goldmont plus | 1         | 2%      |
| Goldmont      | 1         | 2%      |
| Bonnell       | 1         | 2%      |
| Bobcat        | 1         | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 26        | 57.78%  |
| AMD               | 15        | 33.33%  |
| Nvidia            | 3         | 6.67%   |
| ASPEED Technology | 1         | 2.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 8.16%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 3         | 6.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 6.12%   |
| AMD Renoir                                                                    | 3         | 6.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 2         | 4.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 4.08%   |
| Intel HD Graphics 5500                                                        | 2         | 4.08%   |
| Intel Core Processor Integrated Graphics Controller                           | 2         | 4.08%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 2         | 4.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2         | 4.08%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                         | 1         | 2.04%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 2.04%   |
| Nvidia G96CM [GeForce 9600M GT]                                               | 1         | 2.04%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 2.04%   |
| Intel UHD Graphics 620                                                        | 1         | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 2.04%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 2.04%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 2.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 1         | 2.04%   |
| Intel HD Graphics 530                                                         | 1         | 2.04%   |
| Intel HD Graphics 500                                                         | 1         | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 2.04%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 2.04%   |
| ASPEED Technology ASPEED Graphics Family                                      | 1         | 2.04%   |
| AMD Wrestler [Radeon HD 6310]                                                 | 1         | 2.04%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 1         | 2.04%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 1         | 2.04%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                  | 1         | 2.04%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 2.04%   |
| AMD RS880 [Radeon HD 4250]                                                    | 1         | 2.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 2.04%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 1         | 2.04%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 1         | 2.04%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                            | 1         | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| 1 x Intel   | 18        | 36%     |
| 1 x AMD     | 13        | 26%     |
| Other       | 7         | 14%     |
| 2 x Intel   | 6         | 12%     |
| 1 x Nvidia  | 2         | 4%      |
| Intel + AMD | 2         | 4%      |
| 2 x Nvidia  | 1         | 2%      |
| 1 x ASPEED  | 1         | 2%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 40        | 80%     |
| Unknown | 10        | 20%     |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 4         | 14.29%  |
| Lenovo                  | 4         | 14.29%  |
| BOE                     | 4         | 14.29%  |
| LG Display              | 3         | 10.71%  |
| Philips                 | 2         | 7.14%   |
| Dell                    | 2         | 7.14%   |
| AU Optronics            | 2         | 7.14%   |
| ViewSonic               | 1         | 3.57%   |
| PANDA                   | 1         | 3.57%   |
| InfoVision              | 1         | 3.57%   |
| Chimei Innolux          | 1         | 3.57%   |
| Chi Mei Optoelectronics | 1         | 3.57%   |
| Ancor Communications    | 1         | 3.57%   |
| Acer                    | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 3         | 10.71%  |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                    | 2         | 7.14%   |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch              | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch     | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch   | 1         | 3.57%   |
| Samsung Electronics DM700A-D SEM0324 1920x1080 520x290mm 23.4-inch       | 1         | 3.57%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                  | 1         | 3.57%   |
| LG Display LCD Monitor LGD05FA 1920x1080 310x170mm 13.9-inch             | 1         | 3.57%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch              | 1         | 3.57%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch             | 1         | 3.57%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch                 | 1         | 3.57%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 3.57%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 1         | 3.57%   |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                        | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch         | 1         | 3.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 3.57%   |
| BOE LCD Monitor BOE0900 1920x1080 340x190mm 15.3-inch                    | 1         | 3.57%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                    | 1         | 3.57%   |
| BOE LCD Monitor BOE07A5 1366x768 340x190mm 15.3-inch                     | 1         | 3.57%   |
| BOE LCD Monitor BOE075A 1366x768 310x170mm 13.9-inch                     | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 3.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 3.57%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch     | 1         | 3.57%   |
| Acer XZ342CK ACR078B 3440x1440 800x330mm 34.1-inch                       | 1         | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 11        | 39.29%  |
| 1366x768 (WXGA)  | 9         | 32.14%  |
| 1280x800 (WXGA)  | 3         | 10.71%  |
| 3840x2160 (4K)   | 1         | 3.57%   |
| 3440x1440        | 1         | 3.57%   |
| 1600x900 (HD+)   | 1         | 3.57%   |
| 1600x1200        | 1         | 3.57%   |
| 1440x900 (WXGA+) | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 6         | 21.43%  |
| 12     | 6         | 21.43%  |
| 13     | 5         | 17.86%  |
| 21     | 3         | 10.71%  |
| 54     | 1         | 3.57%   |
| 34     | 1         | 3.57%   |
| 24     | 1         | 3.57%   |
| 23     | 1         | 3.57%   |
| 20     | 1         | 3.57%   |
| 19     | 1         | 3.57%   |
| 18     | 1         | 3.57%   |
| 11     | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 10        | 35.71%  |
| 201-300     | 8         | 28.57%  |
| 401-500     | 6         | 21.43%  |
| 501-600     | 2         | 7.14%   |
| 701-800     | 1         | 3.57%   |
| 1001-1500   | 1         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 22        | 78.57%  |
| 16/10 | 4         | 14.29%  |
| 4/3   | 1         | 3.57%   |
| 21/9  | 1         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 61-70          | 6         | 21.43%  |
| 201-250        | 5         | 17.86%  |
| 81-90          | 4         | 14.29%  |
| 101-110        | 3         | 10.71%  |
| 91-100         | 3         | 10.71%  |
| 151-200        | 2         | 7.14%   |
| More than 1000 | 1         | 3.57%   |
| 71-80          | 1         | 3.57%   |
| 51-60          | 1         | 3.57%   |
| 351-500        | 1         | 3.57%   |
| 141-150        | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 13        | 46.43%  |
| 51-100  | 8         | 28.57%  |
| 101-120 | 6         | 21.43%  |
| 161-240 | 1         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 34        | 68%     |
| 0     | 16        | 32%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 30        | 46.88%  |
| Realtek Semiconductor             | 20        | 31.25%  |
| Qualcomm Atheros                  | 4         | 6.25%   |
| Qualcomm Atheros Communications   | 2         | 3.13%   |
| Ericsson Business Mobile Networks | 2         | 3.13%   |
| Qcom                              | 1         | 1.56%   |
| Nvidia                            | 1         | 1.56%   |
| Marvell Technology Group          | 1         | 1.56%   |
| Dell                              | 1         | 1.56%   |
| Broadcom                          | 1         | 1.56%   |
| AVM                               | 1         | 1.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 13        | 16.05%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 6.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5         | 6.17%   |
| Intel Wi-Fi 6 AX200                                                           | 4         | 4.94%   |
| Intel Ultimate N WiFi Link 5300                                               | 3         | 3.7%    |
| Intel 82567LM Gigabit Network Connection                                      | 3         | 3.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2         | 2.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 2.47%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 2.47%   |
| Intel I211 Gigabit Network Connection                                         | 2         | 2.47%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 2.47%   |
| Intel Centrino Advanced-N 6200                                                | 2         | 2.47%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 2.47%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 2.47%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III   | 2         | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 1         | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 1.23%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 1         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 1.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 1.23%   |
| Qcom RT73 USB Wireless LAN Card                                               | 1         | 1.23%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 1.23%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 1.23%   |
| Intel Wireless 7265                                                           | 1         | 1.23%   |
| Intel Wireless 7260                                                           | 1         | 1.23%   |
| Intel Wireless 3165                                                           | 1         | 1.23%   |
| Intel Wi-Fi 6 AX201 160MHz                                                    | 1         | 1.23%   |
| Intel Wi-Fi 6 AX201                                                           | 1         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 1         | 1.23%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 1.23%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 1.23%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 1.23%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 1.23%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 1.23%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 1.23%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                       | 1         | 1.23%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1         | 1.23%   |
| AVM A1 ISDN [Fritz]                                                           | 1         | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 69.7%   |
| Qualcomm Atheros                | 3         | 9.09%   |
| Realtek Semiconductor           | 2         | 6.06%   |
| Qualcomm Atheros Communications | 2         | 6.06%   |
| Qcom                            | 1         | 3.03%   |
| Dell                            | 1         | 3.03%   |
| Broadcom                        | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 15.15%  |
| Intel Wi-Fi 6 AX200                                            | 4         | 12.12%  |
| Intel Ultimate N WiFi Link 5300                                | 3         | 9.09%   |
| Qualcomm Atheros AR9271 802.11n                                | 2         | 6.06%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 3.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 3.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.03%   |
| Qcom RT73 USB Wireless LAN Card                                | 1         | 3.03%   |
| Intel Wireless 7265                                            | 1         | 3.03%   |
| Intel Wireless 7260                                            | 1         | 3.03%   |
| Intel Wireless 3165                                            | 1         | 3.03%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 3.03%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 3.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 3.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 3.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 3.03%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 3.03%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter        | 1         | 3.03%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 3.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 20        | 46.51%  |
| Realtek Semiconductor    | 19        | 44.19%  |
| Qualcomm Atheros         | 2         | 4.65%   |
| Nvidia                   | 1         | 2.33%   |
| Marvell Technology Group | 1         | 2.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 13        | 29.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 5         | 11.36%  |
| Intel 82567LM Gigabit Network Connection                                      | 3         | 6.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2         | 4.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 2         | 4.55%   |
| Intel I211 Gigabit Network Connection                                         | 2         | 4.55%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 4.55%   |
| Intel 82577LM Gigabit Network Connection                                      | 2         | 4.55%   |
| Intel 82574L Gigabit Network Connection                                       | 2         | 4.55%   |
| Realtek RTL8125 2.5GbE Controller                                             | 1         | 2.27%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1         | 2.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1         | 2.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 2.27%   |
| Nvidia MCP79 Ethernet                                                         | 1         | 2.27%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 1         | 2.27%   |
| Intel Ethernet Connection I218-LM                                             | 1         | 2.27%   |
| Intel Ethernet Connection I217-LM                                             | 1         | 2.27%   |
| Intel Ethernet Connection (3) I218-LM                                         | 1         | 2.27%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 2.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 41        | 53.95%  |
| WiFi     | 31        | 40.79%  |
| Unknown  | 4         | 5.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 56.82%  |
| Ethernet | 19        | 43.18%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 29        | 58%     |
| 1     | 11        | 22%     |
| 0     | 6         | 12%     |
| 3     | 3         | 6%      |
| 4     | 1         | 2%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 50        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 11        | 45.83%  |
| Broadcom                        | 5         | 20.83%  |
| Foxconn / Hon Hai               | 2         | 8.33%   |
| Alps Electric                   | 2         | 8.33%   |
| Realtek Semiconductor           | 1         | 4.17%   |
| Qualcomm Atheros Communications | 1         | 4.17%   |
| ASUSTek Computer                | 1         | 4.17%   |
| Apple                           | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 3         | 12.5%   |
| Intel AX200 Bluetooth                                       | 3         | 12.5%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 3         | 12.5%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 8.33%   |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 4.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 4.17%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 4.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 4.17%   |
| Intel AX201 Bluetooth                                       | 1         | 4.17%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 4.17%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 4.17%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 4.17%   |
| Apple Bluetooth Host Controller                             | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 31        | 64.58%  |
| AMD                 | 13        | 27.08%  |
| Nvidia              | 2         | 4.17%   |
| Creative Labs       | 1         | 2.08%   |
| C-Media Electronics | 1         | 2.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 6         | 9.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4         | 6.56%   |
| AMD Family 17h/19h HD Audio Controller                                            | 4         | 6.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 3         | 4.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 3         | 4.92%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 4.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 2         | 3.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 2         | 3.28%   |
| Intel Broadwell-U Audio Controller                                                | 2         | 3.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2         | 3.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 3.28%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 3.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 3.28%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2         | 3.28%   |
| Nvidia MCP79 High Definition Audio                                                | 1         | 1.64%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 1.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 1         | 1.64%   |
| Intel Sunrise Point-LP HD Audio                                                   | 1         | 1.64%   |
| Intel Jasper Lake HD Audio                                                        | 1         | 1.64%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1         | 1.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1         | 1.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 1         | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                        | 1         | 1.64%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                          | 1         | 1.64%   |
| Intel 8 Series HD Audio Controller                                                | 1         | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1         | 1.64%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 1         | 1.64%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 1         | 1.64%   |
| AMD Wrestler HDMI Audio                                                           | 1         | 1.64%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 1         | 1.64%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 1         | 1.64%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1         | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 1.64%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 1         | 1.64%   |
| AMD Navi 10 HDMI Audio                                                            | 1         | 1.64%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 4         | 28.57%  |
| Samsung Electronics | 4         | 28.57%  |
| SK Hynix            | 3         | 21.43%  |
| Kingston            | 1         | 7.14%   |
| A-DATA Technology   | 1         | 7.14%   |
| Unknown             | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 13.33%  |
| Unknown RAM Module 512MB SODIMM SDRAM                  | 1         | 6.67%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1         | 6.67%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 6.67%   |
| Unknown RAM Module 1GB SODIMM DDR2                     | 1         | 6.67%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 6.67%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s | 1         | 6.67%   |
| SK Hynix RAM 484D543332355336 2GB SODIMM DDR3 1333MT/s | 1         | 6.67%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 6.67%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s  | 1         | 6.67%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s  | 1         | 6.67%   |
| Kingston RAM 4143523531325836 4GB SODIMM DDR3 1333MT/s | 1         | 6.67%   |
| A-DATA RAM AM1U16BC4P2-B19C 4GB SODIMM DDR3 1600MT/s   | 1         | 6.67%   |
| Unknown                                                | 1         | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR3  | 9         | 75%     |
| SDRAM | 2         | 16.67%  |
| DDR2  | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 12        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 4096 | 6         | 46.15%  |
| 2048 | 5         | 38.46%  |
| 1024 | 1         | 7.69%   |
| 512  | 1         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1333    | 3         | 25%     |
| Unknown | 3         | 25%     |
| 1600    | 2         | 16.67%  |
| 1334    | 2         | 16.67%  |
| 1067    | 2         | 16.67%  |

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
| Chicony Electronics                    | 7         | 43.75%  |
| Acer                                   | 3         | 18.75%  |
| Ricoh                                  | 2         | 12.5%   |
| Silicon Motion                         | 1         | 6.25%   |
| Quanta                                 | 1         | 6.25%   |
| Denron                                 | 1         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Silicon Motion WebCam SC-10IRQ12340N                                       | 1         | 6.25%   |
| Ricoh USB2.0 Camera                                                        | 1         | 6.25%   |
| Ricoh Integrated Webcam                                                    | 1         | 6.25%   |
| Quanta VGA WebCam                                                          | 1         | 6.25%   |
| Denron Corp., 2M Front Camera                                              | 1         | 6.25%   |
| Chicony Ltd., Integrated Camera                                            | 1         | 6.25%   |
| Chicony Lenovo Integrated Camera UVC                                       | 1         | 6.25%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 6.25%   |
| Chicony integrated camera                                                  | 1         | 6.25%   |
| Chicony HD Webcam                                                          | 1         | 6.25%   |
| Chicony FJ Camera                                                          | 1         | 6.25%   |
| Chicony 2.0M UVC Webcam / CNF7129                                          | 1         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 6.25%   |
| Acer Integrated Camera                                                     | 1         | 6.25%   |
| Acer HD Webcam                                                             | 1         | 6.25%   |
| Acer EasyCamera                                                            | 1         | 6.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 50%     |
| Upek             | 1         | 25%     |
| AuthenTec        | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 25%     |
| AuthenTec AuthenTec Inc. AES2660                       | 1         | 25%     |

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
| 1     | 23        | 46%     |
| 0     | 15        | 30%     |
| 2     | 9         | 18%     |
| 5     | 1         | 2%      |
| 4     | 1         | 2%      |
| 3     | 1         | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 27        | 52.94%  |
| Graphics card            | 8         | 15.69%  |
| Firewire controller      | 6         | 11.76%  |
| Net/wireless             | 4         | 7.84%   |
| Sound                    | 2         | 3.92%   |
| Network                  | 2         | 3.92%   |
| Storage/ata              | 1         | 1.96%   |
| Storage                  | 1         | 1.96%   |

