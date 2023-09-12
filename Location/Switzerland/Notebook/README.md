BSD in Switzerland - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for BSD in Switzerland.

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

Total: 63

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Deciso    | NetBoard-A20                | [e9e295eae3](https://bsd-hardware.info/?probe=e9e295eae3) | Aug 24, 2023 |
| Deciso    | NetBoard-A20                | [c38eb6b9bd](https://bsd-hardware.info/?probe=c38eb6b9bd) | Aug 19, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [020e17c2f8](https://bsd-hardware.info/?probe=020e17c2f8) | Jul 23, 2023 |
| Deciso    | Netboard A20                | [e82dfa5520](https://bsd-hardware.info/?probe=e82dfa5520) | Jul 14, 2023 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [dd937d0914](https://bsd-hardware.info/?probe=dd937d0914) | Jun 12, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [95695f78c5](https://bsd-hardware.info/?probe=95695f78c5) | May 08, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [692b42afcd](https://bsd-hardware.info/?probe=692b42afcd) | Apr 08, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [0af5cebe20](https://bsd-hardware.info/?probe=0af5cebe20) | Mar 29, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Apple     | MacBookPro5,1               | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| Deciso    | Netboard A20                | [7c91a0f01b](https://bsd-hardware.info/?probe=7c91a0f01b) | Feb 14, 2023 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [0c9cf4e002](https://bsd-hardware.info/?probe=0c9cf4e002) | Feb 09, 2023 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [ca1e51a042](https://bsd-hardware.info/?probe=ca1e51a042) | Feb 09, 2023 |
| Deciso    | NetBoard-A10                | [5b226a942e](https://bsd-hardware.info/?probe=5b226a942e) | Jan 27, 2023 |
| Unknown   | Unknown                     | [8511097117](https://bsd-hardware.info/?probe=8511097117) | Jan 22, 2023 |
| Unknown   | Unknown                     | [d5d2ce1b39](https://bsd-hardware.info/?probe=d5d2ce1b39) | Jan 22, 2023 |
| Lenovo    | ThinkPad T460p 20FW003PM... | [ac8e728222](https://bsd-hardware.info/?probe=ac8e728222) | Sep 24, 2022 |
| Unknown   | Unknown                     | [fbd1af0e98](https://bsd-hardware.info/?probe=fbd1af0e98) | Sep 21, 2022 |
| Acer      | Aspire E5-771               | [0a58077c49](https://bsd-hardware.info/?probe=0a58077c49) | Sep 20, 2022 |
| Apple     | MacBookPro5,1               | [f4d84edb3b](https://bsd-hardware.info/?probe=f4d84edb3b) | Sep 04, 2022 |
| Deciso    | Netboard A20                | [c70ba0979e](https://bsd-hardware.info/?probe=c70ba0979e) | Jul 07, 2022 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [1cc5f44e4a](https://bsd-hardware.info/?probe=1cc5f44e4a) | May 25, 2022 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [ddaca5356c](https://bsd-hardware.info/?probe=ddaca5356c) | May 21, 2022 |
| Deciso    | DEC2700 - OPNsense Appli... | [926afc7ac8](https://bsd-hardware.info/?probe=926afc7ac8) | Apr 07, 2022 |
| Deciso    | Netboard A20                | [835d6c060f](https://bsd-hardware.info/?probe=835d6c060f) | Mar 25, 2022 |
| Deciso    | Netboard A20                | [5a6b66aa01](https://bsd-hardware.info/?probe=5a6b66aa01) | Mar 24, 2022 |
| ASUSTek   | N50Vc                       | [883ded6cb1](https://bsd-hardware.info/?probe=883ded6cb1) | Mar 15, 2022 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [dd57366224](https://bsd-hardware.info/?probe=dd57366224) | Mar 15, 2022 |
| Shuttle   | DS77U                       | [1ca3d58dfc](https://bsd-hardware.info/?probe=1ca3d58dfc) | Feb 23, 2022 |
| Lenovo    | ThinkPad X250 20CMCTO1WW    | [4ba527dc9b](https://bsd-hardware.info/?probe=4ba527dc9b) | Feb 06, 2022 |
| ASUSTek   | N50Vc                       | [468a2d7ab8](https://bsd-hardware.info/?probe=468a2d7ab8) | Jan 17, 2022 |
| Lenovo    | ThinkPad T470s W10DG 20J... | [6c895cb96f](https://bsd-hardware.info/?probe=6c895cb96f) | Jan 10, 2022 |
| Casper    | EXCALIBUR G900              | [539cf08655](https://bsd-hardware.info/?probe=539cf08655) | Dec 24, 2021 |
| Lenovo    | ThinkPad X1 Carbon Gen 9... | [8f9e9ddde5](https://bsd-hardware.info/?probe=8f9e9ddde5) | Dec 02, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [0fa0f325e9](https://bsd-hardware.info/?probe=0fa0f325e9) | Oct 28, 2021 |
| Lenovo    | ThinkPad T490s 20NYS3TU0... | [d377309110](https://bsd-hardware.info/?probe=d377309110) | Oct 02, 2021 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [2a54a0c338](https://bsd-hardware.info/?probe=2a54a0c338) | Sep 14, 2021 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [7979c87340](https://bsd-hardware.info/?probe=7979c87340) | Sep 14, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [1498417edf](https://bsd-hardware.info/?probe=1498417edf) | Aug 15, 2021 |
| Lenovo    | ThinkPad X1 Carbon Gen 8... | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| Lenovo    | ThinkPad T420 4237A12       | [dc29d714d9](https://bsd-hardware.info/?probe=dc29d714d9) | Jun 02, 2021 |
| ASUSTek   | UX31A                       | [67a6df2b68](https://bsd-hardware.info/?probe=67a6df2b68) | May 30, 2021 |
| Dell      | Latitude E6430              | [8d24817728](https://bsd-hardware.info/?probe=8d24817728) | May 19, 2021 |
| HP        | EliteBook 840 G3            | [2b97986de1](https://bsd-hardware.info/?probe=2b97986de1) | Apr 21, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [beacf76b6a](https://bsd-hardware.info/?probe=beacf76b6a) | Mar 26, 2021 |
| HUAWEI    | MACH-WX9                    | [f7e09652d9](https://bsd-hardware.info/?probe=f7e09652d9) | Mar 25, 2021 |
| HUAWEI    | MACH-WX9                    | [f9fdc75b45](https://bsd-hardware.info/?probe=f9fdc75b45) | Mar 25, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [acbc65fd42](https://bsd-hardware.info/?probe=acbc65fd42) | Mar 10, 2021 |
| Apple     | MacBookPro9,2               | [a7d9aeda81](https://bsd-hardware.info/?probe=a7d9aeda81) | Feb 22, 2021 |
| Lenovo    | ThinkPad T430 2349H2G       | [229db16a93](https://bsd-hardware.info/?probe=229db16a93) | Feb 05, 2021 |
| Lenovo    | ThinkPad T490 20N2CTO1WW    | [9458fbeb87](https://bsd-hardware.info/?probe=9458fbeb87) | Jan 19, 2021 |
| Lenovo    | Yoga 720-13IKB 81C3         | [467a6fc001](https://bsd-hardware.info/?probe=467a6fc001) | Nov 26, 2020 |
| HP        | EliteBook 840 G3            | [e44b010bc9](https://bsd-hardware.info/?probe=e44b010bc9) | Nov 11, 2020 |
| HP        | EliteBook 840 G3            | [2fb1bc911f](https://bsd-hardware.info/?probe=2fb1bc911f) | Nov 11, 2020 |
| Lenovo    | Yoga 720-13IKB 81C3         | [bdc2de68ce](https://bsd-hardware.info/?probe=bdc2de68ce) | Nov 05, 2020 |
| Lenovo    | Yoga 720-13IKB 81C3         | [8cfb32120b](https://bsd-hardware.info/?probe=8cfb32120b) | Nov 05, 2020 |
| Acer      | Aspire E1-532               | [10bff44534](https://bsd-hardware.info/?probe=10bff44534) | Oct 07, 2020 |
| Lenovo    | ThinkPad X1 Carbon 3rd 2... | [2dd2bb5d60](https://bsd-hardware.info/?probe=2dd2bb5d60) | Aug 20, 2020 |
| Dell      | Precision M6600             | [b6c974b8bd](https://bsd-hardware.info/?probe=b6c974b8bd) | Aug 19, 2020 |
| Dell      | Precision M6600             | [da6f06315a](https://bsd-hardware.info/?probe=da6f06315a) | Aug 06, 2020 |
| HUAWEI    | MACH-WX9                    | [455ba9f0a8](https://bsd-hardware.info/?probe=455ba9f0a8) | Jul 20, 2020 |
| Panasonic | CF-19ADUAX1M                | [cefc742c62](https://bsd-hardware.info/?probe=cefc742c62) | May 29, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| helloSystem 0.5.0        | 3         | 6.12%   |
| FreeBSD 13.0             | 3         | 6.12%   |
| OPNsense 23.7.1          | 2         | 4.08%   |
| OPNsense 23.1            | 2         | 4.08%   |
| helloSystem 0.8.2        | 2         | 4.08%   |
| FreeBSD 13.0-STABLE      | 2         | 4.08%   |
| FreeBSD 13.0-p7          | 2         | 4.08%   |
| FreeBSD 12.1-p8          | 2         | 4.08%   |
| OPNsense 23.4.1          | 1         | 2.04%   |
| OPNsense 22.7.4          | 1         | 2.04%   |
| OPNsense 22.7.11         | 1         | 2.04%   |
| OPNsense 22.10           | 1         | 2.04%   |
| OPNsense 22.1.9          | 1         | 2.04%   |
| OPNsense 22.1.4          | 1         | 2.04%   |
| OPNsense 22.1.1          | 1         | 2.04%   |
| OPNsense 21.1.5          | 1         | 2.04%   |
| OpenBSD 7.0              | 1         | 2.04%   |
| OpenBSD 6.8              | 1         | 2.04%   |
| OpenBSD 6.7              | 1         | 2.04%   |
| helloSystem 0.8.1        | 1         | 2.04%   |
| helloSystem 0.7.0        | 1         | 2.04%   |
| GhostBSD 23.07.20        | 1         | 2.04%   |
| GhostBSD 23.04.23        | 1         | 2.04%   |
| GhostBSD 23.04.02        | 1         | 2.04%   |
| GhostBSD 21.08.27        | 1         | 2.04%   |
| GhostBSD 20.04.02        | 1         | 2.04%   |
| FreeBSD 14.0-CURRENT     | 1         | 2.04%   |
| FreeBSD 13.2-PRERELEASE  | 1         | 2.04%   |
| FreeBSD 13.1-STABLE-HBSD | 1         | 2.04%   |
| FreeBSD 13.1-STABLE      | 1         | 2.04%   |
| FreeBSD 13.1-PRERELEASE  | 1         | 2.04%   |
| FreeBSD 13.0-p6          | 1         | 2.04%   |
| FreeBSD 13.0-p5          | 1         | 2.04%   |
| FreeBSD 13.0-p1          | 1         | 2.04%   |
| FreeBSD 12.2-STABLE      | 1         | 2.04%   |
| FreeBSD 12.2-p4          | 1         | 2.04%   |
| FreeBSD 12.2             | 1         | 2.04%   |
| FreeBSD 12.1-p22-HBSD    | 1         | 2.04%   |
| FreeBSD 12.1             | 1         | 2.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 17        | 42.5%   |
| OPNsense    | 11        | 27.5%   |
| helloSystem | 6         | 15%     |
| OpenBSD     | 3         | 7.5%    |
| GhostBSD    | 3         | 7.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 38        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 15        | 37.5%   |
| helloDesktop | 6         | 15%     |
| KDE5         | 5         | 12.5%   |
| MATE         | 3         | 7.5%    |
| i3           | 3         | 7.5%    |
| XFCE         | 2         | 5%      |
| TWM          | 2         | 5%      |
| fvwm         | 2         | 5%      |
| LXDE         | 1         | 2.5%    |
| GNOME        | 1         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 23        | 58.97%  |
| Console | 15        | 38.46%  |
| Wayland | 1         | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 22        | 55%     |
| SLiM    | 12        | 30%     |
| LightDM | 4         | 10%     |
| SDDM    | 1         | 2.5%    |
| GDM     | 1         | 2.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 43.59%  |
| C       | 9         | 23.08%  |
| en_US   | 8         | 20.51%  |
| fr_FR   | 2         | 5.13%   |
| de_CH   | 2         | 5.13%   |
| de_DE   | 1         | 2.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 33        | 86.84%  |
| BIOS | 5         | 13.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 23        | 57.5%   |
| Ufs    | 11        | 27.5%   |
| Ffs    | 3         | 7.5%    |
| Cd9660 | 3         | 7.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 36        | 94.74%  |
| MBR  | 2         | 5.26%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 15        | 39.47%  |
| Deciso           | 6         | 15.79%  |
| ASUSTek Computer | 3         | 7.89%   |
| HUAWEI           | 2         | 5.26%   |
| Dell             | 2         | 5.26%   |
| Apple            | 2         | 5.26%   |
| Acer             | 2         | 5.26%   |
| Unknown          | 2         | 5.26%   |
| Shuttle          | 1         | 2.63%   |
| Panasonic        | 1         | 2.63%   |
| Hewlett-Packard  | 1         | 2.63%   |
| Casper           | 1         | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS         | 3         | 7.89%   |
| HUAWEI MACH-WX9                            | 2         | 5.26%   |
| Deciso NetBoard-A20                        | 2         | 5.26%   |
| Deciso Netboard A20                        | 2         | 5.26%   |
| Unknown                                    | 2         | 5.26%   |
| Shuttle DS77U                              | 1         | 2.63%   |
| Panasonic CF-19ADUAX1M                     | 1         | 2.63%   |
| Lenovo Yoga 720-13IKB 81C3                 | 1         | 2.63%   |
| Lenovo ThinkPad X250 20CMCTO1WW            | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS09900   | 1         | 2.63%   |
| Lenovo ThinkPad T490s 20NYS3TU00           | 1         | 2.63%   |
| Lenovo ThinkPad T490 20N2CTO1WW            | 1         | 2.63%   |
| Lenovo ThinkPad T470s W10DG 20JTS0A900     | 1         | 2.63%   |
| Lenovo ThinkPad T460p 20FW003PMZ           | 1         | 2.63%   |
| Lenovo ThinkPad T430 2349H2G               | 1         | 2.63%   |
| Lenovo ThinkPad T420 4237A12               | 1         | 2.63%   |
| Lenovo IdeaPad Y700-15ISK 80NV             | 1         | 2.63%   |
| HP EliteBook 840 G3                        | 1         | 2.63%   |
| Dell Precision M6600                       | 1         | 2.63%   |
| Dell Latitude E6430                        | 1         | 2.63%   |
| Deciso NetBoard-A10                        | 1         | 2.63%   |
| Deciso DEC2700 - OPNsense Appliance        | 1         | 2.63%   |
| Casper EXCALIBUR G900                      | 1         | 2.63%   |
| ASUS UX31A                                 | 1         | 2.63%   |
| ASUS N50Vc                                 | 1         | 2.63%   |
| ASUS ASUS TUF Gaming A17 FA707RC_FA707RC   | 1         | 2.63%   |
| Apple MacBookPro9,2                        | 1         | 2.63%   |
| Apple MacBookPro5,1                        | 1         | 2.63%   |
| Acer Aspire E5-771                         | 1         | 2.63%   |
| Acer Aspire E1-532                         | 1         | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 10        | 26.32%  |
| Lenovo Yoga            | 4         | 10.53%  |
| HUAWEI MACH-WX9        | 2         | 5.26%   |
| Deciso NetBoard-A20    | 2         | 5.26%   |
| Deciso Netboard        | 2         | 5.26%   |
| Acer Aspire            | 2         | 5.26%   |
| Unknown                | 2         | 5.26%   |
| Shuttle DS77U          | 1         | 2.63%   |
| Panasonic CF-19ADUAX1M | 1         | 2.63%   |
| Lenovo IdeaPad         | 1         | 2.63%   |
| HP EliteBook           | 1         | 2.63%   |
| Dell Precision         | 1         | 2.63%   |
| Dell Latitude          | 1         | 2.63%   |
| Deciso NetBoard-A10    | 1         | 2.63%   |
| Deciso DEC2700         | 1         | 2.63%   |
| Casper EXCALIBUR       | 1         | 2.63%   |
| ASUS UX31A             | 1         | 2.63%   |
| ASUS N50Vc             | 1         | 2.63%   |
| ASUS ASUS              | 1         | 2.63%   |
| Apple MacBookPro9      | 1         | 2.63%   |
| Apple MacBookPro5      | 1         | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 10        | 26.32%  |
| 2015 | 4         | 10.53%  |
| 2019 | 3         | 7.89%   |
| 2017 | 3         | 7.89%   |
| 2016 | 3         | 7.89%   |
| 2013 | 3         | 7.89%   |
| 2011 | 3         | 7.89%   |
| 2022 | 2         | 5.26%   |
| 2020 | 2         | 5.26%   |
| 2018 | 2         | 5.26%   |
| 2014 | 1         | 2.63%   |
| 2012 | 1         | 2.63%   |
| 2009 | 1         | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 38        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 17        | 44.74%  |
| 8.01-16.0  | 12        | 31.58%  |
| 4.01-8.0   | 6         | 15.79%  |
| 32.01-64.0 | 3         | 7.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 17        | 44.74%  |
| 0.51-1.0 | 13        | 34.21%  |
| 1.01-2.0 | 5         | 13.16%  |
| 2.01-3.0 | 3         | 7.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 33        | 84.62%  |
| 2      | 6         | 15.38%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 81.58%  |
| Yes       | 7         | 18.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 78.95%  |
| No        | 8         | 21.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 78.95%  |
| No        | 8         | 21.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 65.79%  |
| No        | 13        | 34.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Switzerland | 38        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Zurich                   | 17        | 37.78%  |
| Basel                    | 3         | 6.67%   |
| Therwil                  | 2         | 4.44%   |
| Munchenstein             | 2         | 4.44%   |
| Glattbrugg               | 2         | 4.44%   |
| Corcelles-pres-Payerne   | 2         | 4.44%   |
| St. Moritz               | 1         | 2.22%   |
| Seuzach Dorf             | 1         | 2.22%   |
| Onex                     | 1         | 2.22%   |
| Moosseedorf              | 1         | 2.22%   |
| Lutry                    | 1         | 2.22%   |
| Loehningen               | 1         | 2.22%   |
| Lenzburg                 | 1         | 2.22%   |
| Le Landeron              | 1         | 2.22%   |
| Langnau am Albis         | 1         | 2.22%   |
| Kiesen                   | 1         | 2.22%   |
| Huttwil                  | 1         | 2.22%   |
| Hittnau / Hittnau (Dorf) | 1         | 2.22%   |
| Hildisrieden             | 1         | 2.22%   |
| Dinhard                  | 1         | 2.22%   |
| Broc                     | 1         | 2.22%   |
| Bern                     | 1         | 2.22%   |
| Adliswil                 | 1         | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 15     | 29.55%  |
| Transcend           | 7         | 9      | 15.91%  |
| WDC                 | 4         | 4      | 9.09%   |
| Toshiba             | 3         | 3      | 6.82%   |
| Kingston            | 3         | 3      | 6.82%   |
| Intel               | 3         | 4      | 6.82%   |
| SK hynix            | 2         | 4      | 4.55%   |
| SanDisk             | 2         | 2      | 4.55%   |
| NVMe                | 2         | 2      | 4.55%   |
| Crucial             | 2         | 2      | 4.55%   |
| Seagate             | 1         | 1      | 2.27%   |
| OCZ                 | 1         | 1      | 2.27%   |
| LITEON              | 1         | 6      | 2.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Transcend TS256GMTS952T2 256GB         | 3         | 6.67%   |
| Transcend TS128GMTE110S 128GB          | 2         | 4.44%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 2         | 4.44%   |
| Samsung MZVLB512HAJQ-00000 512GB       | 2         | 4.44%   |
| WDC WDS240G2G0A-00JH30 240GB           | 1         | 2.22%   |
| WDC WD10SPZX-21Z10T0 1TB               | 1         | 2.22%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB     | 1         | 2.22%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB   | 1         | 2.22%   |
| Transcend TS256GMTE710T 256GB          | 1         | 2.22%   |
| Transcend TS256GMTE652T2 256GB         | 1         | 2.22%   |
| Toshiba TR200 240GB                    | 1         | 2.22%   |
| Toshiba THNSFJ256GCSU 256GB            | 1         | 2.22%   |
| Toshiba MK3263GSXN 320GB               | 1         | 2.22%   |
| Seagate ST2000LM007-1R8174 2TB         | 1         | 2.22%   |
| SanDisk SSD PLUS 1000GB                | 1         | 2.22%   |
| SanDisk SD5SE2256G1002E 256GB          | 1         | 2.22%   |
| Samsung SSD SM841 2.5-inch 7mm 128GB   | 1         | 2.22%   |
| Samsung SSD 860 EVO 250GB              | 1         | 2.22%   |
| Samsung SSD 860 EVO 1TB                | 1         | 2.22%   |
| Samsung SSD 850 EVO 500GB              | 1         | 2.22%   |
| Samsung SSD 850 EVO 250GB              | 1         | 2.22%   |
| Samsung SSD 850 EVO 1TB                | 1         | 2.22%   |
| Samsung SSD 840 PRO Series 256GB       | 1         | 2.22%   |
| Samsung MZVLW1T0HMLH-000L7 1TB         | 1         | 2.22%   |
| Samsung MZVLB1T0HBLR-000L7 1TB         | 1         | 2.22%   |
| Samsung MZVL21T0HCLR-00BL7 1TB         | 1         | 2.22%   |
| Samsung MZMTD128HAFV-000L1 128GB       | 1         | 2.22%   |
| Samsung MZHPV512HDGL-000L1 512GB       | 1         | 2.22%   |
| OCZ AGILITY3 240GB                     | 1         | 2.22%   |
| NVMe SanDisk A400 SD9 256GB            | 1         | 2.22%   |
| NVMe KIOXIA-EXCERIA S 500GB            | 1         | 2.22%   |
| LITEON CV1-8B512 512GB                 | 1         | 2.22%   |
| Kingston SV300S37A60G 64GB             | 1         | 2.22%   |
| Kingston SKC600MS512G 512GB            | 1         | 2.22%   |
| Kingston SA400S37120G 120GB            | 1         | 2.22%   |
| Intel SSDSCKKF256G8H 256GB             | 1         | 2.22%   |
| Intel SSDPEKNU512GZ 512GB              | 1         | 2.22%   |
| Intel SSDPEKKF512G8L 512GB             | 1         | 2.22%   |
| Crucial CT480BX300SSD1 480GB           | 1         | 2.22%   |
| Crucial CT1000P5SSD8 1TB               | 1         | 2.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 10     | 34.78%  |
| Transcend           | 3         | 5      | 13.04%  |
| Kingston            | 3         | 3      | 13.04%  |
| Toshiba             | 2         | 2      | 8.7%    |
| SanDisk             | 2         | 2      | 8.7%    |
| WDC                 | 1         | 1      | 4.35%   |
| OCZ                 | 1         | 1      | 4.35%   |
| LITEON              | 1         | 6      | 4.35%   |
| Intel               | 1         | 2      | 4.35%   |
| Crucial             | 1         | 1      | 4.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 21        | 33     | 51.22%  |
| NVMe | 15        | 18     | 36.59%  |
| HDD  | 5         | 5      | 12.2%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 24        | 38     | 61.54%  |
| NVMe | 15        | 18     | 38.46%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 17        | 25     | 68%     |
| 0.51-1.0   | 7         | 12     | 28%     |
| 1.01-2.0   | 1         | 1      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 17        | 42.5%   |
| 251-500    | 11        | 27.5%   |
| 501-1000   | 7         | 17.5%   |
| 1-20       | 5         | 12.5%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 34        | 85%     |
| 21-50   | 2         | 5%      |
| 101-250 | 2         | 5%      |
| 51-100  | 2         | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| OCZ AGILITY3 240GB         | 1         | 1      | 33.33%  |
| Kingston SV300S37A60G 64GB | 1         | 1      | 33.33%  |
| Intel SSDSCKKF256G8H 256GB | 1         | 2      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| OCZ      | 1         | 1      | 33.33%  |
| Kingston | 1         | 1      | 33.33%  |
| Intel    | 1         | 2      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 4      | 100%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 35        | 50     | 87.5%   |
| Malfunc  | 3         | 4      | 7.5%    |
| Detected | 2         | 2      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 20        | 48.78%  |
| Samsung Electronics       | 6         | 14.63%  |
| Transcend                 | 3         | 7.32%   |
| SanDisk                   | 3         | 7.32%   |
| AMD                       | 3         | 7.32%   |
| SK hynix                  | 2         | 4.88%   |
| Silicon Motion            | 1         | 2.44%   |
| Nvidia                    | 1         | 2.44%   |
| Micron/Crucial Technology | 1         | 2.44%   |
| KIOXIA                    | 1         | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 3         | 7.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 7.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 7.32%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 3         | 7.32%   |
| Transcend NVMe PCIe SSD 120S/112S (DRAM-less)                                | 2         | 4.88%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 2         | 4.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 4.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 4.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 4.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 4.88%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers            | 1         | 2.44%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 2.44%   |
| SanDisk WD Black NVMe SSD                                                    | 1         | 2.44%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                              | 1         | 2.44%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                   | 1         | 2.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 2.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 1         | 2.44%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 2.44%   |
| Micron/Crucial P5 NVMe PCIe SSD[SlashP5]                                     | 1         | 2.44%   |
| KIOXIA NVMe SSD                                                              | 1         | 2.44%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 1         | 2.44%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                             | 1         | 2.44%   |
| Intel SSD 670p Series [Keystone Harbor]                                      | 1         | 2.44%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 2.44%   |
| Unknown                                                                      | 1         | 2.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 52.5%   |
| NVMe | 17        | 42.5%   |
| RAID | 2         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 73.68%  |
| AMD    | 10        | 26.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 7.89%   |
| AMD EPYC 3101 4-Core Processor          | 3         | 7.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 5.26%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 5.26%   |
| AMD Ryzen Embedded V1500B               | 2         | 5.26%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 2.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 2.63%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 1         | 2.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 2.63%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 2.63%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 2.63%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 2.63%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 2.63%   |
| Intel Core i7-2720QM CPU @ 2.20GH       | 1         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 2.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 2.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 2.63%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 2.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 2.63%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 1         | 2.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 2.63%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 1         | 2.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 2.63%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 2.63%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz    | 1         | 2.63%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 2.63%   |
| Intel Celeron 2955U @ 1.40GHz           | 1         | 2.63%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 1         | 2.63%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 2.63%   |
| AMD Ryzen 7 6800H with Radeon Graphics  | 1         | 2.63%   |
| AMD EPYC 3201 8-Core Processor          | 1         | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 11        | 28.95%  |
| Intel Core i5      | 11        | 28.95%  |
| AMD Ryzen 7        | 4         | 10.53%  |
| AMD EPYC           | 4         | 10.53%  |
| Other              | 2         | 5.26%   |
| Intel Core 2 Duo   | 2         | 5.26%   |
| AMD Ryzen Embedded | 2         | 5.26%   |
| Intel Core i3      | 1         | 2.63%   |
| Intel Celeron      | 1         | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 15        | 39.47%  |
| 4       | 14        | 36.84%  |
| 16      | 4         | 10.53%  |
| 8       | 4         | 10.53%  |
| Unknown | 1         | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 97.37%  |
| 2      | 1         | 2.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 25        | 65.79%  |
| 1       | 12        | 31.58%  |
| Unknown | 1         | 2.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 8         | 21.05%  |
| Zen         | 6         | 15.79%  |
| IvyBridge   | 5         | 13.16%  |
| Skylake     | 4         | 10.53%  |
| Zen 3       | 3         | 7.89%   |
| SandyBridge | 3         | 7.89%   |
| Broadwell   | 3         | 7.89%   |
| Penryn      | 2         | 5.26%   |
| Unknown     | 2         | 5.26%   |
| TigerLake   | 1         | 2.63%   |
| Haswell     | 1         | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 67.57%  |
| Nvidia | 7         | 18.92%  |
| AMD    | 5         | 13.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 13.16%  |
| Intel UHD Graphics 620                                                    | 3         | 7.89%   |
| Intel HD Graphics 5500                                                    | 3         | 7.89%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 7.89%   |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 5.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 5.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 5.26%   |
| Intel HD Graphics 530                                                     | 2         | 5.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 5.26%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 2.63%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 2.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 2.63%   |
| Nvidia G98M [GeForce 9300M GS]                                            | 1         | 2.63%   |
| Nvidia G96CM [GeForce 9600M GT]                                           | 1         | 2.63%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 2.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 2.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 2.63%   |
| Intel HD Graphics 620                                                     | 1         | 2.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 2.63%   |
| AMD Rembrandt [Radeon 680M]                                               | 1         | 2.63%   |
| AMD Blackcomb [Radeon HD 6970M/6990M]                                     | 1         | 2.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 21        | 55.26%  |
| Other          | 6         | 15.79%  |
| Intel + Nvidia | 4         | 10.53%  |
| 1 x AMD        | 4         | 10.53%  |
| 2 x Nvidia     | 1         | 2.63%   |
| 1 x Nvidia     | 1         | 2.63%   |
| AMD + Nvidia   | 1         | 2.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 28        | 73.68%  |
| Unknown     | 8         | 21.05%  |
| Proprietary | 2         | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 87.5%   |
| 1.01-2.0   | 3         | 7.5%    |
| 0.01-0.5   | 2         | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 6         | 27.27%  |
| LG Display              | 3         | 13.64%  |
| Chimei Innolux          | 3         | 13.64%  |
| JDI                     | 2         | 9.09%   |
| CSO                     | 2         | 9.09%   |
| Sharp                   | 1         | 4.55%   |
| Samsung Electronics     | 1         | 4.55%   |
| Dell                    | 1         | 4.55%   |
| Chi Mei Optoelectronics | 1         | 4.55%   |
| BOE                     | 1         | 4.55%   |
| Apple                   | 1         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| JDI LCD Monitor JDI422A 3000x2000 290x200mm 13.9-inch                    | 2         | 9.09%   |
| CSO LCD Monitor CSO1402 2880x1800 300x190mm 14.0-inch                    | 2         | 9.09%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch         | 2         | 9.09%   |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch                  | 1         | 4.55%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 800x330mm 34.1-inch          | 1         | 4.55%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 4.55%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 4.55%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch             | 1         | 4.55%   |
| Dell P2715Q DEL40BD 3840x2160 600x340mm 27.2-inch                        | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN1348 1920x1080 280x160mm 12.7-inch         | 1         | 4.55%   |
| Chi Mei Optoelectronics LCD Monitor CMO1561 1280x800 330x210mm 15.4-inch | 1         | 4.55%   |
| BOE LCD Monitor BOE0910 1920x1080 340x190mm 15.3-inch                    | 1         | 4.55%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 300x190mm 14.0-inch           | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO159D 1920x1080 380x210mm 17.1-inch           | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 310x170mm 13.9-inch           | 1         | 4.55%   |
| Apple LCD Monitor APP9C84 1440x900 330x210mm 15.4-inch                   | 1         | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 8         | 36.36%  |
| 3840x2160 (4K)    | 2         | 9.09%   |
| 3000x2000         | 2         | 9.09%   |
| 2880x1800         | 2         | 9.09%   |
| 1366x768 (WXGA)   | 2         | 9.09%   |
| 3440x1440         | 1         | 4.55%   |
| 2560x1440 (QHD)   | 1         | 4.55%   |
| 1920x1200 (WUXGA) | 1         | 4.55%   |
| 1600x900 (HD+)    | 1         | 4.55%   |
| 1440x900 (WXGA+)  | 1         | 4.55%   |
| 1280x800 (WXGA)   | 1         | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 9         | 40.91%  |
| 15     | 5         | 22.73%  |
| 14     | 3         | 13.64%  |
| 12     | 2         | 9.09%   |
| 34     | 1         | 4.55%   |
| 27     | 1         | 4.55%   |
| 17     | 1         | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 54.55%  |
| 201-300     | 7         | 31.82%  |
| 701-800     | 1         | 4.55%   |
| 501-600     | 1         | 4.55%   |
| 351-400     | 1         | 4.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 14        | 63.64%  |
| 16/10 | 5         | 22.73%  |
| 4/3   | 2         | 9.09%   |
| 21/9  | 1         | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 12        | 54.55%  |
| 101-110        | 4         | 18.18%  |
| 61-70          | 2         | 9.09%   |
| 351-500        | 1         | 4.55%   |
| 301-350        | 1         | 4.55%   |
| 121-130        | 1         | 4.55%   |
| 91-100         | 1         | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 7         | 31.82%  |
| More than 240 | 5         | 22.73%  |
| 161-240       | 5         | 22.73%  |
| 101-120       | 3         | 13.64%  |
| 51-100        | 2         | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 20        | 48.78%  |
| 0     | 19        | 46.34%  |
| 2     | 2         | 4.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 50.85%  |
| Realtek Semiconductor | 9         | 15.25%  |
| AMD                   | 6         | 10.17%  |
| Broadcom              | 4         | 6.78%   |
| TP-Link               | 2         | 3.39%   |
| Qualcomm Atheros      | 2         | 3.39%   |
| MediaTek              | 2         | 3.39%   |
| Sierra Wireless       | 1         | 1.69%   |
| Samsung Electronics   | 1         | 1.69%   |
| Ralink Technology     | 1         | 1.69%   |
| Nvidia                | 1         | 1.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 6         | 8.22%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 6.85%   |
| Intel I210 Gigabit Network Connection                             | 5         | 6.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 6.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 4.11%   |
| Intel Wireless 8265 / 8275                                        | 3         | 4.11%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 4.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 4.11%   |
| Intel Wireless 8260                                               | 2         | 2.74%   |
| Intel Wireless 7265                                               | 2         | 2.74%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 1.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 1.37%   |
| Sierra Wireless EM7455                                            | 1         | 1.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.37%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1         | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.37%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.37%   |
| MediaTek 802.11 n WLAN                                            | 1         | 1.37%   |
| Intel WiFi Link 5100                                              | 1         | 1.37%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.37%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.37%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.37%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.37%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.37%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.37%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.37%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.37%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.37%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 1.37%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.37%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 55.56%  |
| Realtek Semiconductor | 5         | 13.89%  |
| Broadcom              | 3         | 8.33%   |
| TP-Link               | 2         | 5.56%   |
| Qualcomm Atheros      | 2         | 5.56%   |
| MediaTek              | 2         | 5.56%   |
| Sierra Wireless       | 1         | 2.78%   |
| Ralink Technology     | 1         | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 8.33%   |
| Intel Wireless 8265 / 8275                                     | 3         | 8.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 8.33%   |
| Intel Wireless 8260                                            | 2         | 5.56%   |
| Intel Wireless 7265                                            | 2         | 5.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 5.56%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 2.78%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 2.78%   |
| Sierra Wireless EM7455                                         | 1         | 2.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 2.78%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 2.78%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 2.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 2.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 2.78%   |
| MediaTek 802.11 n WLAN                                         | 1         | 2.78%   |
| Intel WiFi Link 5100                                           | 1         | 2.78%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 2.78%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 2.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 2.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.78%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 2.78%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 2.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 2.78%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1         | 2.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 58.33%  |
| AMD                   | 6         | 16.67%  |
| Realtek Semiconductor | 5         | 13.89%  |
| Broadcom              | 2         | 5.56%   |
| Samsung Electronics   | 1         | 2.78%   |
| Nvidia                | 1         | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 6         | 16.22%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 13.51%  |
| Intel I210 Gigabit Network Connection                             | 5         | 13.51%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 13.51%  |
| Intel Ethernet Connection I219-LM                                 | 3         | 8.11%   |
| Intel I211 Gigabit Network Connection                             | 2         | 5.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 2.7%    |
| Nvidia MCP79 Ethernet                                             | 1         | 2.7%    |
| Intel Ethernet Connection (6) I219-V                              | 1         | 2.7%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.7%    |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.7%    |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 2.7%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.7%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 2.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 50%     |
| Ethernet | 30        | 50%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 27        | 56.25%  |
| WiFi     | 21        | 43.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 50%     |
| 1     | 10        | 26.32%  |
| 6     | 5         | 13.16%  |
| 5     | 2         | 5.26%   |
| 3     | 2         | 5.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 32        | 82.05%  |
| Yes  | 7         | 17.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 12        | 48%     |
| Realtek Semiconductor   | 3         | 12%     |
| Apple                   | 2         | 8%      |
| Lite-On Technology      | 1         | 4%      |
| IMC Networks            | 1         | 4%      |
| Foxconn / Hon Hai       | 1         | 4%      |
| Dell                    | 1         | 4%      |
| Cambridge Silicon Radio | 1         | 4%      |
| Broadcom                | 1         | 4%      |
| ASUSTek Computer        | 1         | 4%      |
| Alps Electric           | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 6         | 24%     |
| Realtek Bluetooth Adapter                                   | 3         | 12%     |
| Intel AX201 Bluetooth                                       | 3         | 12%     |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1         | 4%      |
| Intel AX200 Bluetooth                                       | 1         | 4%      |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 4%      |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 4%      |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 4%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 4%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 4%      |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 4%      |
| Apple Broadcom Built-in Bluetooth                           | 1         | 4%      |
| Apple Bluetooth Host Controller                             | 1         | 4%      |
| Alps Electric UGTZ4 Bluetooth                               | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 27        | 61.36%  |
| AMD              | 10        | 22.73%  |
| Nvidia           | 3         | 6.82%   |
| Lenovo           | 2         | 4.55%   |
| GN Netcom        | 1         | 2.27%   |
| ASUSTek Computer | 1         | 2.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 11.76%  |
| AMD Family 17h/19h HD Audio Controller                                     | 5         | 9.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 7.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 7.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 7.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 5.88%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 5.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 5.88%   |
| Lenovo Lenovo USB-C Mini Dock                                              | 2         | 3.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 3.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 3.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 3.92%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.96%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 1.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.96%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 1.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 1.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 1.96%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 1.96%   |
| GN Netcom Jabra UC VOICE 550 MS mono USB                                   | 1         | 1.96%   |
| ASUSTek Computer C-Media CM6549 Extension                                  | 1         | 1.96%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 1         | 1.96%   |
| Unknown                                                                    | 1         | 1.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 26.32%  |
| Micron Technology   | 7         | 18.42%  |
| Transcend           | 6         | 15.79%  |
| SK hynix            | 6         | 15.79%  |
| Kingston            | 4         | 10.53%  |
| Unknown             | 1         | 2.63%   |
| Elpida              | 1         | 2.63%   |
| Crucial             | 1         | 2.63%   |
| Corsair             | 1         | 2.63%   |
| A-DATA Technology   | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 4         | 10%     |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 3         | 7.5%    |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s            | 2         | 5%      |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 5%      |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 1         | 2.5%    |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s          | 1         | 2.5%    |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s           | 1         | 2.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 2.5%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 1         | 2.5%    |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s        | 1         | 2.5%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s        | 1         | 2.5%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s         | 1         | 2.5%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 2.5%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 2.5%    |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                    | 1         | 2.5%    |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s            | 1         | 2.5%    |
| Samsung RAM M471B5273QH0-YKO 8GB SODIMM DDR3 1600MT/s          | 1         | 2.5%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 2.5%    |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 2.5%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s       | 1         | 2.5%    |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s          | 1         | 2.5%    |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s    | 1         | 2.5%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 2.5%    |
| Micron RAM 4ATF51264HZ-2G3B2 4GB SODIMM DDR4 2400MT/s          | 1         | 2.5%    |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s         | 1         | 2.5%    |
| Kingston RAM Module 8192MB SODIMM DDR3 1867MT/s                | 1         | 2.5%    |
| Kingston RAM 9905712-035.A00G 16GB SODIMM DDR4 2667MT/s        | 1         | 2.5%    |
| Kingston RAM 9905469-157.A01LF 4096MB SODIMM DDR3 1600MT/s     | 1         | 2.5%    |
| Kingston RAM 9905428-196.A00LF 8GB SODIMM DDR3 1333MT/s        | 1         | 2.5%    |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.5%    |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s        | 1         | 2.5%    |
| Corsair RAM CMSO32GX4M2A2133C15 16GB SODIMM DDR4 2133MT/s      | 1         | 2.5%    |
| A-DATA RAM MIF4D2C087KZ1 4GB SODIMM DDR3 1600MT/s              | 1         | 2.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 17        | 48.57%  |
| DDR3   | 12        | 34.29%  |
| LPDDR3 | 3         | 8.57%   |
| LPDDR4 | 1         | 2.86%   |
| DDR5   | 1         | 2.86%   |
| DDR2   | 1         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 27        | 77.14%  |
| Row Of Chips | 7         | 20%     |
| Chip         | 1         | 2.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 47.22%  |
| 4096  | 9         | 25%     |
| 16384 | 6         | 16.67%  |
| 2048  | 4         | 11.11%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 8         | 22.22%  |
| 2667  | 7         | 19.44%  |
| 2133  | 7         | 19.44%  |
| 3200  | 4         | 11.11%  |
| 1333  | 4         | 11.11%  |
| 4800  | 1         | 2.78%   |
| 4267  | 1         | 2.78%   |
| 2400  | 1         | 2.78%   |
| 1867  | 1         | 2.78%   |
| 1067  | 1         | 2.78%   |
| 800   | 1         | 2.78%   |

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

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 40.91%  |
| IMC Networks                           | 5         | 22.73%  |
| Sunplus Innovation Technology          | 2         | 9.09%   |
| Bison Electronics                      | 2         | 9.09%   |
| Suyin                                  | 1         | 4.55%   |
| Supreme Electronics                    | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 4.55%   |
| Apple                                  | 1         | 4.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                   | 4         | 18.18%  |
| Chicony Integrated Camera                        | 4         | 18.18%  |
| Bison Integrated Camera                          | 2         | 9.09%   |
| Suyin HD WebCam                                  | 1         | 4.55%   |
| Supreme Realtek PC Camera                        | 1         | 4.55%   |
| Sunplus Laptop Integrated WebCam HD              | 1         | 4.55%   |
| Sunplus Laptop Integrated Webcam FHD             | 1         | 4.55%   |
| IMC Networks EasyCamera                          | 1         | 4.55%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 4.55%   |
| Chicony USB 2.0 2.0M UVC WebCam                  | 1         | 4.55%   |
| Chicony ThinkPad T490 Webcam                     | 1         | 4.55%   |
| Chicony Lenovo EasyCamera                        | 1         | 4.55%   |
| Chicony HP Universal Camera                      | 1         | 4.55%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 1         | 4.55%   |
| Apple FaceTime HD Camera                         | 1         | 4.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 50%     |
| Synaptics        | 2         | 33.33%  |
| Upek             | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 16.67%  |
| Validity Sensors Synaptics WBDI                        | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |
| Synaptics WBDI                                         | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 16.67%  |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 12        | 30%     |
| 2     | 11        | 27.5%   |
| 0     | 7         | 17.5%   |
| 4     | 4         | 10%     |
| 3     | 4         | 10%     |
| 5     | 2         | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 26        | 41.27%  |
| Net/wireless             | 9         | 14.29%  |
| Bluetooth                | 9         | 14.29%  |
| Card reader              | 6         | 9.52%   |
| Fingerprint reader       | 5         | 7.94%   |
| Firewire controller      | 4         | 6.35%   |
| Storage                  | 1         | 1.59%   |
| Sound                    | 1         | 1.59%   |
| Network                  | 1         | 1.59%   |
| Graphics card            | 1         | 1.59%   |

