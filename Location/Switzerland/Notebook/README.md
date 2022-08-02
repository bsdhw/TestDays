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

Total: 49

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [7f77c09ea1](https://bsd-hardware.info/?probe=7f77c09ea1) | Oct 28, 2021 |
| Lenovo    | ThinkPad T490s 20NYS3TU0... | [d377309110](https://bsd-hardware.info/?probe=d377309110) | Oct 02, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [cec09523c6](https://bsd-hardware.info/?probe=cec09523c6) | Sep 29, 2021 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [2a54a0c338](https://bsd-hardware.info/?probe=2a54a0c338) | Sep 14, 2021 |
| Lenovo    | Yoga Slim 7 Pro 14ACH5 8... | [7979c87340](https://bsd-hardware.info/?probe=7979c87340) | Sep 14, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [1498417edf](https://bsd-hardware.info/?probe=1498417edf) | Aug 15, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [c40cb92b67](https://bsd-hardware.info/?probe=c40cb92b67) | Aug 15, 2021 |
| Lenovo    | ThinkPad X1 Carbon Gen 8... | [85e94a1288](https://bsd-hardware.info/?probe=85e94a1288) | Jul 13, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [ae63f87748](https://bsd-hardware.info/?probe=ae63f87748) | Jun 22, 2021 |
| Lenovo    | ThinkPad T420 4237A12       | [dc29d714d9](https://bsd-hardware.info/?probe=dc29d714d9) | Jun 02, 2021 |
| ASUSTek   | UX31A                       | [67a6df2b68](https://bsd-hardware.info/?probe=67a6df2b68) | May 30, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [1cdbad9dfe](https://bsd-hardware.info/?probe=1cdbad9dfe) | May 27, 2021 |
| Dell      | Latitude E6430              | [8d24817728](https://bsd-hardware.info/?probe=8d24817728) | May 19, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [5020fdee8a](https://bsd-hardware.info/?probe=5020fdee8a) | May 01, 2021 |
| HP        | EliteBook 840 G3            | [2b97986de1](https://bsd-hardware.info/?probe=2b97986de1) | Apr 21, 2021 |
| Lenovo    | IdeaPad Y700-15ISK 80NV     | [6f935f23d5](https://bsd-hardware.info/?probe=6f935f23d5) | Apr 11, 2021 |
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


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| helloSystem 0.5.0       | 3         | 9.38%   |
| FreeBSD 13.0            | 3         | 9.38%   |
| FreeBSD 13.0-STABLE     | 2         | 6.25%   |
| FreeBSD 13.0-p7         | 2         | 6.25%   |
| FreeBSD 12.1-p8         | 2         | 6.25%   |
| OPNsense 22.1.9         | 1         | 3.13%   |
| OPNsense 22.1.4         | 1         | 3.13%   |
| OPNsense 22.1.1         | 1         | 3.13%   |
| OPNsense 21.1.5         | 1         | 3.13%   |
| OpenBSD 7.0             | 1         | 3.13%   |
| OpenBSD 6.8             | 1         | 3.13%   |
| OpenBSD 6.7             | 1         | 3.13%   |
| GhostBSD 21.08.27       | 1         | 3.13%   |
| GhostBSD 20.04.02       | 1         | 3.13%   |
| FreeBSD 14.0-CURRENT    | 1         | 3.13%   |
| FreeBSD 13.1-STABLE     | 1         | 3.13%   |
| FreeBSD 13.1-PRERELEASE | 1         | 3.13%   |
| FreeBSD 13.0-p6         | 1         | 3.13%   |
| FreeBSD 13.0-p5         | 1         | 3.13%   |
| FreeBSD 13.0-p1         | 1         | 3.13%   |
| FreeBSD 12.2-STABLE     | 1         | 3.13%   |
| FreeBSD 12.2-p4         | 1         | 3.13%   |
| FreeBSD 12.2            | 1         | 3.13%   |
| FreeBSD 12.1-p22-HBSD   | 1         | 3.13%   |
| FreeBSD 12.1            | 1         | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 16        | 57.14%  |
| OPNsense    | 4         | 14.29%  |
| OpenBSD     | 3         | 10.71%  |
| helloSystem | 3         | 10.71%  |
| GhostBSD    | 2         | 7.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 27        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 7         | 25%     |
| KDE5         | 5         | 17.86%  |
| i3           | 3         | 10.71%  |
| helloDesktop | 3         | 10.71%  |
| XFCE         | 2         | 7.14%   |
| TWM          | 2         | 7.14%   |
| MATE         | 2         | 7.14%   |
| fvwm         | 2         | 7.14%   |
| LXDE         | 1         | 3.57%   |
| GNOME        | 1         | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 20        | 71.43%  |
| Console | 8         | 28.57%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 14        | 50%     |
| SLiM    | 9         | 32.14%  |
| LightDM | 3         | 10.71%  |
| SDDM    | 1         | 3.57%   |
| GDM     | 1         | 3.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 10        | 37.04%  |
| en_US   | 7         | 25.93%  |
| C       | 7         | 25.93%  |
| de_CH   | 2         | 7.41%   |
| de_DE   | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 23        | 85.19%  |
| BIOS | 4         | 14.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 18        | 64.29%  |
| Ufs  | 7         | 25%     |
| Ffs  | 3         | 10.71%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 25        | 92.59%  |
| MBR  | 2         | 7.41%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 13        | 48.15%  |
| HUAWEI           | 2         | 7.41%   |
| Dell             | 2         | 7.41%   |
| Deciso           | 2         | 7.41%   |
| ASUSTek Computer | 2         | 7.41%   |
| Shuttle          | 1         | 3.7%    |
| Panasonic        | 1         | 3.7%    |
| Hewlett-Packard  | 1         | 3.7%    |
| Casper           | 1         | 3.7%    |
| Apple            | 1         | 3.7%    |
| Acer             | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS         | 2         | 7.41%   |
| HUAWEI MACH-WX9                            | 2         | 7.41%   |
| Shuttle DS77U                              | 1         | 3.7%    |
| Panasonic CF-19ADUAX1M                     | 1         | 3.7%    |
| Lenovo Yoga 720-13IKB 81C3                 | 1         | 3.7%    |
| Lenovo ThinkPad X250 20CMCTO1WW            | 1         | 3.7%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 3.7%    |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 1         | 3.7%    |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS09900   | 1         | 3.7%    |
| Lenovo ThinkPad T490s 20NYS3TU00           | 1         | 3.7%    |
| Lenovo ThinkPad T490 20N2CTO1WW            | 1         | 3.7%    |
| Lenovo ThinkPad T470s W10DG 20JTS0A900     | 1         | 3.7%    |
| Lenovo ThinkPad T430 2349H2G               | 1         | 3.7%    |
| Lenovo ThinkPad T420 4237A12               | 1         | 3.7%    |
| Lenovo IdeaPad Y700-15ISK 80NV             | 1         | 3.7%    |
| HP EliteBook 840 G3                        | 1         | 3.7%    |
| Dell Precision M6600                       | 1         | 3.7%    |
| Dell Latitude E6430                        | 1         | 3.7%    |
| Deciso Netboard A20                        | 1         | 3.7%    |
| Deciso DEC2700 - OPNsense Appliance        | 1         | 3.7%    |
| Casper EXCALIBUR G900                      | 1         | 3.7%    |
| ASUS UX31A                                 | 1         | 3.7%    |
| ASUS N50Vc                                 | 1         | 3.7%    |
| Apple MacBookPro9,2                        | 1         | 3.7%    |
| Acer Aspire E1-532                         | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 9         | 33.33%  |
| Lenovo Yoga            | 3         | 11.11%  |
| HUAWEI MACH-WX9        | 2         | 7.41%   |
| Shuttle DS77U          | 1         | 3.7%    |
| Panasonic CF-19ADUAX1M | 1         | 3.7%    |
| Lenovo IdeaPad         | 1         | 3.7%    |
| HP EliteBook           | 1         | 3.7%    |
| Dell Precision         | 1         | 3.7%    |
| Dell Latitude          | 1         | 3.7%    |
| Deciso Netboard        | 1         | 3.7%    |
| Deciso DEC2700         | 1         | 3.7%    |
| Casper EXCALIBUR       | 1         | 3.7%    |
| ASUS UX31A             | 1         | 3.7%    |
| ASUS N50Vc             | 1         | 3.7%    |
| Apple MacBookPro9      | 1         | 3.7%    |
| Acer Aspire            | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 6         | 22.22%  |
| 2017 | 3         | 11.11%  |
| 2015 | 3         | 11.11%  |
| 2013 | 3         | 11.11%  |
| 2011 | 3         | 11.11%  |
| 2019 | 2         | 7.41%   |
| 2018 | 2         | 7.41%   |
| 2016 | 2         | 7.41%   |
| 2020 | 1         | 3.7%    |
| 2014 | 1         | 3.7%    |
| 2009 | 1         | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 27        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 16.01-24.0 | 12        | 44.44%  |
| 8.01-16.0  | 9         | 33.33%  |
| 4.01-8.0   | 3         | 11.11%  |
| 32.01-64.0 | 3         | 11.11%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 11        | 40.74%  |
| 0.51-1.0 | 10        | 37.04%  |
| 1.01-2.0 | 4         | 14.81%  |
| 2.01-3.0 | 2         | 7.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 81.48%  |
| 2      | 5         | 18.52%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 77.78%  |
| Yes       | 6         | 22.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 74.07%  |
| No        | 7         | 25.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 92.59%  |
| No        | 2         | 7.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 74.07%  |
| No        | 7         | 25.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Switzerland | 27        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Zurich                 | 14        | 45.16%  |
| Therwil                | 2         | 6.45%   |
| Munchenstein           | 2         | 6.45%   |
| Glattbrugg             | 2         | 6.45%   |
| Corcelles-pres-Payerne | 2         | 6.45%   |
| St. Moritz             | 1         | 3.23%   |
| Onex                   | 1         | 3.23%   |
| Lenzburg               | 1         | 3.23%   |
| Langnau am Albis       | 1         | 3.23%   |
| Dinhard                | 1         | 3.23%   |
| Broc                   | 1         | 3.23%   |
| Bern                   | 1         | 3.23%   |
| Basel                  | 1         | 3.23%   |
| Adliswil               | 1         | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 13     | 36.67%  |
| WDC                 | 4         | 4      | 13.33%  |
| Transcend           | 2         | 3      | 6.67%   |
| Toshiba             | 2         | 2      | 6.67%   |
| SanDisk             | 2         | 2      | 6.67%   |
| NVMe                | 2         | 2      | 6.67%   |
| Intel               | 2         | 3      | 6.67%   |
| Crucial             | 2         | 2      | 6.67%   |
| Seagate             | 1         | 1      | 3.33%   |
| LITEON              | 1         | 9      | 3.33%   |
| Kingston            | 1         | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung MZVLB512HAJQ-00000 512GB     | 2         | 6.45%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 3.23%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 3.23%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB   | 1         | 3.23%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 3.23%   |
| Transcend TS256GMTS952T2 256GB       | 1         | 3.23%   |
| Transcend TS256GMTE652T2 256GB       | 1         | 3.23%   |
| Toshiba TR200 240GB                  | 1         | 3.23%   |
| Toshiba THNSFJ256GCSU 256GB          | 1         | 3.23%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 3.23%   |
| SanDisk SSD PLUS 1000GB              | 1         | 3.23%   |
| SanDisk SD5SE2256G1002E 256GB        | 1         | 3.23%   |
| Samsung SSD SM841 2.5-inch 7mm 128GB | 1         | 3.23%   |
| Samsung SSD 860 EVO 250GB            | 1         | 3.23%   |
| Samsung SSD 860 EVO 1TB              | 1         | 3.23%   |
| Samsung SSD 850 EVO 500GB            | 1         | 3.23%   |
| Samsung SSD 850 EVO 250GB            | 1         | 3.23%   |
| Samsung MZVLW1T0HMLH-000L7 1TB       | 1         | 3.23%   |
| Samsung MZVLB1T0HBLR-000L7 1TB       | 1         | 3.23%   |
| Samsung MZVL21T0HCLR-00BL7 1TB       | 1         | 3.23%   |
| Samsung MZMTD128HAFV-000L1 128GB     | 1         | 3.23%   |
| Samsung MZHPV512HDGL-000L1 512GB     | 1         | 3.23%   |
| NVMe SanDisk A400 SD9 256GB          | 1         | 3.23%   |
| NVMe KIOXIA-EXCERIA S 500GB          | 1         | 3.23%   |
| LITEON CV1-8B512 512GB               | 1         | 3.23%   |
| Kingston SA400S37120G 120GB          | 1         | 3.23%   |
| Intel SSDSCKKF256G8H 256GB           | 1         | 3.23%   |
| Intel SSDPEKKF512G8L 512GB           | 1         | 3.23%   |
| Crucial CT480BX300SSD1 480GB         | 1         | 3.23%   |
| Crucial CT1000P5SSD8 1TB             | 1         | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 37.5%   |
| Toshiba             | 2         | 2      | 12.5%   |
| SanDisk             | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| Transcend           | 1         | 2      | 6.25%   |
| LITEON              | 1         | 9      | 6.25%   |
| Kingston            | 1         | 1      | 6.25%   |
| Intel               | 1         | 2      | 6.25%   |
| Crucial             | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 15        | 28     | 51.72%  |
| NVMe | 10        | 10     | 34.48%  |
| HDD  | 4         | 4      | 13.79%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 18        | 32     | 64.29%  |
| NVMe | 10        | 10     | 35.71%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 13        | 18     | 68.42%  |
| 0.51-1.0   | 5         | 13     | 26.32%  |
| 1.01-2.0   | 1         | 1      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 40.74%  |
| 251-500    | 8         | 29.63%  |
| 501-1000   | 6         | 22.22%  |
| 1-20       | 2         | 7.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 23        | 82.14%  |
| 21-50   | 2         | 7.14%   |
| 51-100  | 2         | 7.14%   |
| 101-250 | 1         | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Intel SSDSCKKF256G8H 256GB | 1         | 2      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 2      | 100%    |

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
| SSD  | 1         | 2      | 100%    |

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
| Works    | 25        | 38     | 89.29%  |
| Detected | 2         | 2      | 7.14%   |
| Malfunc  | 1         | 2      | 3.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 15        | 53.57%  |
| Samsung Electronics       | 6         | 21.43%  |
| SanDisk                   | 3         | 10.71%  |
| Micron/Crucial Technology | 1         | 3.57%   |
| KIOXIA                    | 1         | 3.57%   |
| AMD                       | 1         | 3.57%   |
| Unknown                   | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 3         | 10.71%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 10.71%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 7.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 7.14%   |
| Unknown                                                                      | 2         | 7.14%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 3.57%   |
| SanDisk WD Black NVMe SSD                                                    | 1         | 3.57%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                              | 1         | 3.57%   |
| Samsung SM951 AHCI                                                           | 1         | 3.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 3.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 1         | 3.57%   |
| KIOXIA NVMe SSD                                                              | 1         | 3.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 3.57%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 1         | 3.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 3.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 1         | 3.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 3.57%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                         | 1         | 3.57%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 1         | 3.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 14        | 50%     |
| NVMe | 12        | 42.86%  |
| RAID | 2         | 7.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 85.19%  |
| AMD    | 4         | 14.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 7.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 7.41%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 2         | 7.41%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 3.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 3.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 1         | 3.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 1         | 3.7%    |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 3.7%    |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 3.7%    |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 3.7%    |
| Intel Core i7-2720QM CPU @ 2.20GH       | 1         | 3.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 1         | 3.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 3.7%    |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 3.7%    |
| Intel Core i5-3317U CPU @ 1.70GHz       | 1         | 3.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 3.7%    |
| Intel Core i5-10310U CPU @ 1.70GHz      | 1         | 3.7%    |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 3.7%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 1         | 3.7%    |
| Intel Celeron 2955U @ 1.40GHz           | 1         | 3.7%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 1         | 3.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 1         | 3.7%    |
| AMD Ryzen Embedded V1500B               | 1         | 3.7%    |
| AMD EPYC 3101 4-Core Processor          | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 10        | 37.04%  |
| Intel Core i5      | 8         | 29.63%  |
| Other              | 2         | 7.41%   |
| AMD Ryzen 7        | 2         | 7.41%   |
| Intel Core i3      | 1         | 3.7%    |
| Intel Core 2 Duo   | 1         | 3.7%    |
| Intel Celeron      | 1         | 3.7%    |
| AMD Ryzen Embedded | 1         | 3.7%    |
| AMD EPYC           | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13        | 48.15%  |
| 4      | 10        | 37.04%  |
| 16     | 2         | 7.41%   |
| 8      | 2         | 7.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 27        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 21        | 77.78%  |
| 1      | 6         | 22.22%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 7         | 25.93%  |
| IvyBridge   | 4         | 14.81%  |
| Skylake     | 3         | 11.11%  |
| SandyBridge | 3         | 11.11%  |
| Zen 3       | 2         | 7.41%   |
| Zen         | 2         | 7.41%   |
| Broadwell   | 2         | 7.41%   |
| TigerLake   | 1         | 3.7%    |
| Penryn      | 1         | 3.7%    |
| Haswell     | 1         | 3.7%    |
| Unknown     | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 75%     |
| Nvidia | 4         | 14.29%  |
| AMD    | 3         | 10.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 14.29%  |
| Intel UHD Graphics 620                                                    | 3         | 10.71%  |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 7.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 7.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 7.14%   |
| Intel HD Graphics 5500                                                    | 2         | 7.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 7.14%   |
| AMD Cezanne                                                               | 2         | 7.14%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 3.57%   |
| Nvidia G98M [GeForce 9300M GS]                                            | 1         | 3.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 3.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 3.57%   |
| Intel HD Graphics 620                                                     | 1         | 3.57%   |
| Intel HD Graphics 530                                                     | 1         | 3.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1         | 3.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 3.57%   |
| AMD Blackcomb [Radeon HD 6970M/6990M]                                     | 1         | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 18        | 66.67%  |
| Intel + Nvidia | 3         | 11.11%  |
| 1 x AMD        | 3         | 11.11%  |
| Other          | 2         | 7.41%   |
| 1 x Nvidia     | 1         | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 22        | 81.48%  |
| Unknown     | 4         | 14.81%  |
| Proprietary | 1         | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 92.59%  |
| 1.01-2.0   | 1         | 3.7%    |
| 0.01-0.5   | 1         | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 6         | 31.58%  |
| LG Display              | 3         | 15.79%  |
| Chimei Innolux          | 3         | 15.79%  |
| JDI                     | 2         | 10.53%  |
| Sharp                   | 1         | 5.26%   |
| Samsung Electronics     | 1         | 5.26%   |
| Dell                    | 1         | 5.26%   |
| Chi Mei Optoelectronics | 1         | 5.26%   |
| BOE                     | 1         | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| JDI LCD Monitor JDI422A 3000x2000 290x200mm 13.9-inch                    | 2         | 10.53%  |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 310x170mm 13.9-inch         | 2         | 10.53%  |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch                  | 1         | 5.26%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 800x330mm 34.1-inch          | 1         | 5.26%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 5.26%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch              | 1         | 5.26%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch             | 1         | 5.26%   |
| Dell P2715Q DEL40BD 3840x2160 600x340mm 27.2-inch                        | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN1348 1920x1080 280x160mm 12.7-inch         | 1         | 5.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1561 1280x800 330x210mm 15.4-inch | 1         | 5.26%   |
| BOE LCD Monitor BOE0910 1920x1080 340x190mm 15.3-inch                    | 1         | 5.26%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 300x190mm 14.0-inch           | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 310x170mm 13.9-inch           | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch            | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO159D 1920x1080 380x210mm 17.1-inch           | 1         | 5.26%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 310x170mm 13.9-inch           | 1         | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 8         | 42.11%  |
| 3840x2160 (4K)    | 2         | 10.53%  |
| 3000x2000         | 2         | 10.53%  |
| 1366x768 (WXGA)   | 2         | 10.53%  |
| 3440x1440         | 1         | 5.26%   |
| 2560x1440 (QHD)   | 1         | 5.26%   |
| 1920x1200 (WUXGA) | 1         | 5.26%   |
| 1600x900 (HD+)    | 1         | 5.26%   |
| 1280x800 (WXGA)   | 1         | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 9         | 47.37%  |
| 15     | 4         | 21.05%  |
| 12     | 2         | 10.53%  |
| 34     | 1         | 5.26%   |
| 27     | 1         | 5.26%   |
| 17     | 1         | 5.26%   |
| 14     | 1         | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 57.89%  |
| 201-300     | 5         | 26.32%  |
| 701-800     | 1         | 5.26%   |
| 501-600     | 1         | 5.26%   |
| 351-400     | 1         | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 14        | 73.68%  |
| 4/3   | 2         | 10.53%  |
| 16/10 | 2         | 10.53%  |
| 21/9  | 1         | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 52.63%  |
| 101-110        | 3         | 15.79%  |
| 61-70          | 2         | 10.53%  |
| 351-500        | 1         | 5.26%   |
| 301-350        | 1         | 5.26%   |
| 121-130        | 1         | 5.26%   |
| 91-100         | 1         | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 7         | 36.84%  |
| 161-240       | 5         | 26.32%  |
| More than 240 | 3         | 15.79%  |
| 101-120       | 2         | 10.53%  |
| 51-100        | 2         | 10.53%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 17        | 60.71%  |
| 0     | 9         | 32.14%  |
| 2     | 2         | 7.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 57.5%   |
| Realtek Semiconductor | 5         | 12.5%   |
| Broadcom              | 3         | 7.5%    |
| TP-Link               | 2         | 5%      |
| AMD                   | 2         | 5%      |
| Sierra Wireless       | 1         | 2.5%    |
| Samsung Electronics   | 1         | 2.5%    |
| Ralink Technology     | 1         | 2.5%    |
| Qualcomm Atheros      | 1         | 2.5%    |
| MediaTek              | 1         | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 9.26%   |
| Intel Wireless 8265 / 8275                                        | 3         | 5.56%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 5.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 5.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 3.7%    |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2         | 3.7%    |
| Intel Wireless 8260                                               | 2         | 3.7%    |
| Intel Wireless 7265                                               | 2         | 3.7%    |
| Intel I210 Gigabit Network Connection                             | 2         | 3.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 3.7%    |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 2         | 3.7%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 1.85%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 1.85%   |
| Sierra Wireless EM7455                                            | 1         | 1.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.85%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 1.85%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 1         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 1.85%   |
| MediaTek 802.11 n WLAN                                            | 1         | 1.85%   |
| Intel WiFi Link 5100                                              | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 1.85%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.85%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.85%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 1         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 1.85%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 1.85%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1         | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 19        | 61.29%  |
| Realtek Semiconductor | 4         | 12.9%   |
| TP-Link               | 2         | 6.45%   |
| Broadcom              | 2         | 6.45%   |
| Sierra Wireless       | 1         | 3.23%   |
| Ralink Technology     | 1         | 3.23%   |
| Qualcomm Atheros      | 1         | 3.23%   |
| MediaTek              | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                 | 3         | 9.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 3         | 9.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 2         | 6.45%   |
| Intel Wireless 8260                                        | 2         | 6.45%   |
| Intel Wireless 7265                                        | 2         | 6.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 2         | 6.45%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1         | 3.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1         | 3.23%   |
| Sierra Wireless EM7455                                     | 1         | 3.23%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 3.23%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 1         | 3.23%   |
| Ralink RT2501/RT2573 Wireless Adapter                      | 1         | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 1         | 3.23%   |
| MediaTek 802.11 n WLAN                                     | 1         | 3.23%   |
| Intel WiFi Link 5100                                       | 1         | 3.23%   |
| Intel Wi-Fi 6 AX201                                        | 1         | 3.23%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 1         | 3.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 1         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 1         | 3.23%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 3.23%   |
| Intel Centrino Advanced-N 6235                             | 1         | 3.23%   |
| Broadcom BCM4331 802.11a/b/g/n                             | 1         | 3.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 3.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 68.18%  |
| Realtek Semiconductor | 2         | 9.09%   |
| Broadcom              | 2         | 9.09%   |
| AMD                   | 2         | 9.09%   |
| Samsung Electronics   | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 21.74%  |
| Intel Ethernet Connection I219-LM                                 | 3         | 13.04%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2         | 8.7%    |
| Intel I210 Gigabit Network Connection                             | 2         | 8.7%    |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 2         | 8.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 4.35%   |
| Intel I211 Gigabit Network Connection                             | 1         | 4.35%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 4.35%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 4.35%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 4.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 4.35%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 4.35%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 4.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 55.56%  |
| Ethernet | 20        | 44.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 52.63%  |
| Ethernet | 18        | 47.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 16        | 59.26%  |
| 1     | 8         | 29.63%  |
| 6     | 1         | 3.7%    |
| 5     | 1         | 3.7%    |
| 3     | 1         | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 85.19%  |
| Yes  | 4         | 14.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 11        | 55%     |
| Realtek Semiconductor   | 2         | 10%     |
| Lite-On Technology      | 1         | 5%      |
| Dell                    | 1         | 5%      |
| Cambridge Silicon Radio | 1         | 5%      |
| Broadcom                | 1         | 5%      |
| ASUSTek Computer        | 1         | 5%      |
| Apple                   | 1         | 5%      |
| Alps Electric           | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 6         | 30%     |
| Intel AX201 Bluetooth                               | 3         | 15%     |
| Realtek Bluetooth Radio                             | 2         | 10%     |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 5%      |
| Dell Dell Wireless 380 Bluetooth 4.0 Module         | 1         | 5%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 5%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 5%      |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 5%      |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 5%      |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 23        | 76.67%  |
| AMD       | 5         | 16.67%  |
| Nvidia    | 1         | 3.33%   |
| GN Netcom | 1         | 3.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 17.14%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 11.43%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 8.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 8.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 5.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 5.71%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 5.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 5.71%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.86%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 2.86%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.86%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.86%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 2.86%   |
| GN Netcom Jabra UC VOICE 550 MS mono USB                                   | 1         | 2.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 2.86%   |
| AMD Barts HDMI Audio [Radeon HD 6790/6850/6870 / 7720 OEM]                 | 1         | 2.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Micron Technology   | 7         | 25.93%  |
| Samsung Electronics | 6         | 22.22%  |
| SK hynix            | 4         | 14.81%  |
| Kingston            | 4         | 14.81%  |
| Transcend           | 2         | 7.41%   |
| Unknown             | 1         | 3.7%    |
| Elpida              | 1         | 3.7%    |
| Corsair             | 1         | 3.7%    |
| A-DATA Technology   | 1         | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 2         | 7.14%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 7.14%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                     | 1         | 3.57%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 1         | 3.57%   |
| Transcend RAM TS1GLH64V6B3 8GB SODIMM DDR4 1333MT/s            | 1         | 3.57%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s           | 1         | 3.57%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 1         | 3.57%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s        | 1         | 3.57%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s         | 1         | 3.57%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 3.57%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 3.57%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s            | 1         | 3.57%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 3.57%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 3.57%   |
| Micron RAM 8KTF25664HZ-1G6M1 2GB SODIMM DDR3 1600MT/s          | 1         | 3.57%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s    | 1         | 3.57%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 3.57%   |
| Micron RAM 4ATF51264HZ-2G3B2 4GB SODIMM DDR4 2400MT/s          | 1         | 3.57%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s         | 1         | 3.57%   |
| Kingston RAM Module 8192MB SODIMM DDR3 1867MT/s                | 1         | 3.57%   |
| Kingston RAM 9905712-035.A00G 16GB SODIMM DDR4 2667MT/s        | 1         | 3.57%   |
| Kingston RAM 9905469-157.A01LF 4096MB SODIMM DDR3 1600MT/s     | 1         | 3.57%   |
| Kingston RAM 9905428-196.A00LF 8GB SODIMM DDR3 1333MT/s        | 1         | 3.57%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.57%   |
| Corsair RAM CMSO32GX4M2A2133C15 16GB SODIMM DDR4 2133MT/s      | 1         | 3.57%   |
| A-DATA RAM MIF4D2C087KZ1 4096MB SODIMM DDR3 1600MT/s           | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 10        | 41.67%  |
| DDR3   | 9         | 37.5%   |
| LPDDR3 | 3         | 12.5%   |
| LPDDR4 | 1         | 4.17%   |
| DDR2   | 1         | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 17        | 70.83%  |
| Row Of Chips | 6         | 25%     |
| Chip         | 1         | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 10        | 40%     |
| 4096  | 8         | 32%     |
| 16384 | 4         | 16%     |
| 2048  | 3         | 12%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2133  | 6         | 25%     |
| 1600  | 6         | 25%     |
| 2667  | 3         | 12.5%   |
| 1333  | 3         | 12.5%   |
| 3200  | 2         | 8.33%   |
| 4267  | 1         | 4.17%   |
| 2400  | 1         | 4.17%   |
| 1867  | 1         | 4.17%   |
| 800   | 1         | 4.17%   |

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
| Chicony Electronics                    | 9         | 47.37%  |
| IMC Networks                           | 4         | 21.05%  |
| Acer                                   | 2         | 10.53%  |
| Suyin                                  | 1         | 5.26%   |
| Sunplus Innovation Technology          | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.26%   |
| Apple                                  | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 4         | 21.05%  |
| IMC Networks Integrated Camera                   | 3         | 15.79%  |
| Acer Integrated Camera                           | 2         | 10.53%  |
| Suyin HD WebCam                                  | 1         | 5.26%   |
| Sunplus Laptop Integrated Webcam FHD             | 1         | 5.26%   |
| IMC Networks EasyCamera                          | 1         | 5.26%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 5.26%   |
| Chicony USB 2.0 2.0M UVC WebCam                  | 1         | 5.26%   |
| Chicony ThinkPad T490 Webcam                     | 1         | 5.26%   |
| Chicony Lenovo EasyCamera                        | 1         | 5.26%   |
| Chicony HP Universal Camera                      | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 1         | 5.26%   |
| Apple FaceTime HD Camera                         | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 40%     |
| Synaptics        | 2         | 40%     |
| Upek             | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 20%     |
| Validity Sensors Synaptics WBDI                        | 1         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 20%     |
| Synaptics  WBDI                                        | 1         | 20%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 20%     |

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
| 2     | 10        | 34.48%  |
| 1     | 9         | 31.03%  |
| 4     | 4         | 13.79%  |
| 3     | 3         | 10.34%  |
| 0     | 2         | 6.9%    |
| 5     | 1         | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 22        | 41.51%  |
| Bluetooth                | 8         | 15.09%  |
| Net/wireless             | 7         | 13.21%  |
| Firewire controller      | 4         | 7.55%   |
| Fingerprint reader       | 4         | 7.55%   |
| Card reader              | 4         | 7.55%   |
| Storage                  | 1         | 1.89%   |
| Sound                    | 1         | 1.89%   |
| Network                  | 1         | 1.89%   |
| Graphics card            | 1         | 1.89%   |

