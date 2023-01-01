BSD in Austria - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for BSD in Austria.

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

Total: 36

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad A485 20MVS0LG00    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| Intel         | H81U                        | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Intel         | H81U                        | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Deciso        | NetBoard-A10                | [aefb2f4660](https://bsd-hardware.info/?probe=aefb2f4660) | Aug 24, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Fujitsu       | LIFEBOOK A555               | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| BESSTAR Te... | U820                        | [6f2aa2d02a](https://bsd-hardware.info/?probe=6f2aa2d02a) | May 07, 2022 |
| Lenovo        | ThinkPad T410 2537WEE       | [973ade9e4a](https://bsd-hardware.info/?probe=973ade9e4a) | Mar 07, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| Lenovo        | Y50-70 20378                | [1feb455e8c](https://bsd-hardware.info/?probe=1feb455e8c) | Jan 25, 2022 |
| Dell          | Precision 7530              | [498bfe852c](https://bsd-hardware.info/?probe=498bfe852c) | Jan 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| Unknown       | Unknown                     | [db4d12babd](https://bsd-hardware.info/?probe=db4d12babd) | Dec 23, 2021 |
| HP            | EliteBook Folio 9470m       | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| Unknown       | Unknown                     | [eab0d6c6d3](https://bsd-hardware.info/?probe=eab0d6c6d3) | Dec 12, 2021 |
| Unknown       | Unknown                     | [6d1fb7b4bb](https://bsd-hardware.info/?probe=6d1fb7b4bb) | Nov 27, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [087d40ba7c](https://bsd-hardware.info/?probe=087d40ba7c) | Oct 19, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [bf9b083102](https://bsd-hardware.info/?probe=bf9b083102) | Sep 08, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [62f9376847](https://bsd-hardware.info/?probe=62f9376847) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| HP            | EliteBook Folio 9470m       | [e1837571df](https://bsd-hardware.info/?probe=e1837571df) | Apr 15, 2021 |
| HP            | EliteBook Folio 9470m       | [57de8a523c](https://bsd-hardware.info/?probe=57de8a523c) | Mar 29, 2021 |
| Panasonic     | CF-30KTP48NL                | [119b4875e9](https://bsd-hardware.info/?probe=119b4875e9) | Mar 12, 2021 |
| Dell          | Vostro V131                 | [897616d9c8](https://bsd-hardware.info/?probe=897616d9c8) | Jan 31, 2021 |
| Dell          | Vostro V131                 | [630822a6a1](https://bsd-hardware.info/?probe=630822a6a1) | Jan 25, 2021 |
| HP            | ZBook 17 G4                 | [40ad0612de](https://bsd-hardware.info/?probe=40ad0612de) | Jan 02, 2021 |
| Lenovo        | ThinkPad T410 2537AT1       | [4e693bfcb2](https://bsd-hardware.info/?probe=4e693bfcb2) | Oct 29, 2020 |
| Dell          | Latitude E7440              | [acd2735dc4](https://bsd-hardware.info/?probe=acd2735dc4) | Aug 07, 2020 |
| HP            | EliteBook 840 G3            | [71c35a9cc2](https://bsd-hardware.info/?probe=71c35a9cc2) | Aug 06, 2020 |
| HP            | EliteBook 840 G3            | [6c7374d0ab](https://bsd-hardware.info/?probe=6c7374d0ab) | May 29, 2020 |
| Lenovo        | ThinkPad T60 2007J3G        | [ee60eb3dc8](https://bsd-hardware.info/?probe=ee60eb3dc8) | May 25, 2020 |
| Dell          | XPS 13 9360                 | [152f5cda4c](https://bsd-hardware.info/?probe=152f5cda4c) | May 23, 2020 |
| Dell          | XPS 13 9360                 | [d350b44569](https://bsd-hardware.info/?probe=d350b44569) | May 23, 2020 |
| Dell          | XPS 13 9360                 | [4199e37b56](https://bsd-hardware.info/?probe=4199e37b56) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| FreeBSD 13.1         | 3         | 10.34%  |
| OPNsense 21.7.7      | 2         | 6.9%    |
| FreeBSD 14.0-CURRENT | 2         | 6.9%    |
| FreeBSD 13.0-p4      | 2         | 6.9%    |
| FreeBSD 12.1-p8      | 2         | 6.9%    |
| FreeBSD 12.1-p5      | 2         | 6.9%    |
| OPNsense 22.7.9      | 1         | 3.45%   |
| OPNsense 22.4.3      | 1         | 3.45%   |
| OPNsense 22.1.6      | 1         | 3.45%   |
| OPNsense 22.1.2      | 1         | 3.45%   |
| OPNsense 21.7.6      | 1         | 3.45%   |
| OpenBSD 6.8          | 1         | 3.45%   |
| helloSystem 0.7.0    | 1         | 3.45%   |
| helloSystem 0.5.0    | 1         | 3.45%   |
| FreeBSD 13.1-p5      | 1         | 3.45%   |
| FreeBSD 13.0-CURRENT | 1         | 3.45%   |
| FreeBSD 13.0         | 1         | 3.45%   |
| FreeBSD 12.3         | 1         | 3.45%   |
| FreeBSD 12.2-p5      | 1         | 3.45%   |
| FreeBSD 12.2         | 1         | 3.45%   |
| FreeBSD 12.1-p4      | 1         | 3.45%   |
| FreeBSD 12.1-p10     | 1         | 3.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 17        | 65.38%  |
| OPNsense    | 6         | 23.08%  |
| helloSystem | 2         | 7.69%   |
| OpenBSD     | 1         | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 26        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| KDE5         | 8         | 29.63%  |
| Console      | 6         | 22.22%  |
| Cinnamon     | 3         | 11.11%  |
| XFCE         | 2         | 7.41%   |
| i3           | 2         | 7.41%   |
| helloDesktop | 2         | 7.41%   |
| MATE         | 1         | 3.7%    |
| LXQt         | 1         | 3.7%    |
| GNOME        | 1         | 3.7%    |
| fvwm         | 1         | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 18        | 69.23%  |
| Console | 7         | 26.92%  |
| Wayland | 1         | 3.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 10        | 38.46%  |
| Console | 10        | 38.46%  |
| SLiM    | 3         | 11.54%  |
| XDM     | 1         | 3.85%   |
| LightDM | 1         | 3.85%   |
| GDM     | 1         | 3.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 11        | 39.29%  |
| C       | 9         | 32.14%  |
| en_US   | 5         | 17.86%  |
| de_DE   | 1         | 3.57%   |
| de_AT   | 1         | 3.57%   |
| cs_CZ   | 1         | 3.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 22        | 84.62%  |
| BIOS | 4         | 15.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 17        | 65.38%  |
| Ufs  | 8         | 30.77%  |
| Ffs  | 1         | 3.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 24        | 92.31%  |
| MBR  | 2         | 7.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo          | 11        | 42.31%  |
| Hewlett-Packard | 5         | 19.23%  |
| Dell            | 4         | 15.38%  |
| Panasonic       | 1         | 3.85%   |
| Intel           | 1         | 3.85%   |
| Fujitsu         | 1         | 3.85%   |
| Deciso          | 1         | 3.85%   |
| BESSTAR Tech    | 1         | 3.85%   |
| Unknown         | 1         | 3.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo ThinkPad T490 20N2CTO1WW      | 2         | 7.69%   |
| HP EliteBook 850 G7 Notebook PC      | 2         | 7.69%   |
| Panasonic CF-30KTP48NL               | 1         | 3.85%   |
| Lenovo Y50-70 20378                  | 1         | 3.85%   |
| Lenovo ThinkPad T60 2007J3G          | 1         | 3.85%   |
| Lenovo ThinkPad T510 4384AJ6         | 1         | 3.85%   |
| Lenovo ThinkPad T410 2537WEE         | 1         | 3.85%   |
| Lenovo ThinkPad T410 2537AT1         | 1         | 3.85%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE | 1         | 3.85%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE | 1         | 3.85%   |
| Lenovo ThinkPad A485 20MVS0LG00      | 1         | 3.85%   |
| Lenovo IdeaPad 110S-11IBR 80WG       | 1         | 3.85%   |
| Intel H81U                           | 1         | 3.85%   |
| HP ZBook 17 G4                       | 1         | 3.85%   |
| HP EliteBook Folio 9470m             | 1         | 3.85%   |
| HP EliteBook 840 G3                  | 1         | 3.85%   |
| Fujitsu LIFEBOOK A555                | 1         | 3.85%   |
| Dell XPS 13 9360                     | 1         | 3.85%   |
| Dell Vostro V131                     | 1         | 3.85%   |
| Dell Precision 7530                  | 1         | 3.85%   |
| Dell Latitude E7440                  | 1         | 3.85%   |
| Deciso NetBoard-A10                  | 1         | 3.85%   |
| BESSTAR Tech U820                    | 1         | 3.85%   |
| Unknown                              | 1         | 3.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 9         | 34.62%  |
| HP EliteBook           | 4         | 15.38%  |
| Panasonic CF-30KTP48NL | 1         | 3.85%   |
| Lenovo Y50-70          | 1         | 3.85%   |
| Lenovo IdeaPad         | 1         | 3.85%   |
| Intel H81U             | 1         | 3.85%   |
| HP ZBook               | 1         | 3.85%   |
| Fujitsu LIFEBOOK       | 1         | 3.85%   |
| Dell XPS               | 1         | 3.85%   |
| Dell Vostro            | 1         | 3.85%   |
| Dell Precision         | 1         | 3.85%   |
| Dell Latitude          | 1         | 3.85%   |
| Deciso NetBoard-A10    | 1         | 3.85%   |
| BESSTAR Tech U820      | 1         | 3.85%   |
| Unknown                | 1         | 3.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 6         | 23.08%  |
| 2022 | 3         | 11.54%  |
| 2021 | 3         | 11.54%  |
| 2018 | 3         | 11.54%  |
| 2010 | 3         | 11.54%  |
| 2017 | 2         | 7.69%   |
| 2020 | 1         | 3.85%   |
| 2016 | 1         | 3.85%   |
| 2015 | 1         | 3.85%   |
| 2011 | 1         | 3.85%   |
| 2009 | 1         | 3.85%   |
| 2006 | 1         | 3.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 26        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 26        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 10        | 38.46%  |
| 16.01-24.0  | 7         | 26.92%  |
| 32.01-64.0  | 3         | 11.54%  |
| 3.01-4.0    | 2         | 7.69%   |
| 2.01-3.0    | 2         | 7.69%   |
| 4.01-8.0    | 1         | 3.85%   |
| 64.01-256.0 | 1         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 11        | 42.31%  |
| 1.01-2.0 | 8         | 30.77%  |
| 0.51-1.0 | 5         | 19.23%  |
| 2.01-3.0 | 2         | 7.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 69.23%  |
| 2      | 3         | 11.54%  |
| 0      | 3         | 11.54%  |
| 3      | 2         | 7.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 25        | 96.15%  |
| Yes       | 1         | 3.85%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 80.77%  |
| No        | 5         | 19.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 92.31%  |
| No        | 2         | 7.69%   |

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


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Austria | 26        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vienna           | 16        | 59.26%  |
| Graz             | 2         | 7.41%   |
| Wels             | 1         | 3.7%    |
| Weidlingbach     | 1         | 3.7%    |
| Vorchdorf        | 1         | 3.7%    |
| Parndorf         | 1         | 3.7%    |
| Maria Enzersdorf | 1         | 3.7%    |
| Linz             | 1         | 3.7%    |
| Innsbruck        | 1         | 3.7%    |
| Grosspertholz    | 1         | 3.7%    |
| Bruck an der Mur | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 31.03%  |
| Intel               | 4         | 5      | 13.79%  |
| WDC                 | 3         | 3      | 10.34%  |
| Transcend           | 2         | 3      | 6.9%    |
| SK hynix            | 2         | 2      | 6.9%    |
| SanDisk             | 2         | 2      | 6.9%    |
| Seagate             | 1         | 1      | 3.45%   |
| Kingston            | 1         | 4      | 3.45%   |
| Intenso             | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 2      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 6.45%   |
| Samsung MZALQ512HBLU-00BL1 512GB        | 2         | 6.45%   |
| Intel SSDPEKKF512G8L 512GB              | 2         | 6.45%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 3.23%   |
| WDC WD20SPZX-22CRAT0 2TB                | 1         | 3.23%   |
| WDC WD10JPLX-00MBPT0 1TB                | 1         | 3.23%   |
| Transcend TS2TMTE220S 2TB               | 1         | 3.23%   |
| Transcend TS256GMTE652T2 256GB          | 1         | 3.23%   |
| Seagate ST1000LX015-1U7172 1TB          | 1         | 3.23%   |
| SanDisk SSD PLUS 240GB                  | 1         | 3.23%   |
| SanDisk SD7TB3Q-128G-1006 128GB         | 1         | 3.23%   |
| Samsung SSD PM851 mSATA 256GB           | 1         | 3.23%   |
| Samsung SSD PM841 2.5-inch 7mm 256GB    | 1         | 3.23%   |
| Samsung SSD 860 EVO 250GB               | 1         | 3.23%   |
| Samsung MZVLB256HAHQ-000L7 256GB        | 1         | 3.23%   |
| Samsung MZVKW512HMJP-000H1 512GB        | 1         | 3.23%   |
| Samsung MZ7TE512HMHP-000L2 512GB        | 1         | 3.23%   |
| Samsung HM320JI 320GB                   | 1         | 3.23%   |
| Kingston SUV500MS480G 480GB             | 1         | 3.23%   |
| Kingston SUV500MS120G 120GB             | 1         | 3.23%   |
| Intenso JAJM600M256C 256GB              | 1         | 3.23%   |
| Intel SSDSCKKF256G8H 256GB              | 1         | 3.23%   |
| Intel SSDPEKNW020T8 2TB                 | 1         | 3.23%   |
| Hitachi HTS541040G9SA00 40GB            | 1         | 3.23%   |
| HGST HTS545050A7E680 500GB              | 1         | 3.23%   |
| Crucial CT275MX300SSD4 275GB            | 1         | 3.23%   |
| A-DATA SU650 240GB                      | 1         | 3.23%   |
| A-DATA SU630 240GB                      | 1         | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 42.86%  |
| Seagate             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 36.36%  |
| SanDisk             | 2         | 2      | 18.18%  |
| Kingston            | 1         | 4      | 9.09%   |
| Intenso             | 1         | 1      | 9.09%   |
| Intel               | 1         | 2      | 9.09%   |
| Crucial             | 1         | 1      | 9.09%   |
| A-DATA Technology   | 1         | 2      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 10        | 12     | 38.46%  |
| SSD  | 10        | 16     | 38.46%  |
| HDD  | 6         | 7      | 23.08%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 13        | 23     | 56.52%  |
| NVMe | 10        | 12     | 43.48%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 11        | 19     | 73.33%  |
| 0.51-1.0   | 3         | 3      | 20%     |
| 1.01-2.0   | 1         | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 10        | 38.46%  |
| 101-250    | 10        | 38.46%  |
| 21-50      | 2         | 7.69%   |
| 51-100     | 2         | 7.69%   |
| 1-20       | 1         | 3.85%   |
| 501-1000   | 1         | 3.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 21        | 77.78%  |
| 21-50   | 3         | 11.11%  |
| 251-500 | 1         | 3.7%    |
| 101-250 | 1         | 3.7%    |
| 51-100  | 1         | 3.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB   | 1         | 1      | 25%     |
| Intel SSDSCKKF256G8H 256GB    | 1         | 2      | 25%     |
| Hitachi HTS541040G9SA00 40GB  | 1         | 1      | 25%     |
| A-DATA Technology SU630 240GB | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 1         | 1      | 25%     |
| Intel             | 1         | 2      | 25%     |
| Hitachi           | 1         | 1      | 25%     |
| A-DATA Technology | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 3      | 50%     |
| HDD  | 2         | 2      | 50%     |

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


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 21        | 30     | 84%     |
| Malfunc | 4         | 5      | 16%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 19        | 65.52%  |
| Samsung Electronics | 4         | 13.79%  |
| SK hynix            | 2         | 6.9%    |
| Transcend           | 1         | 3.45%   |
| Toshiba             | 1         | 3.45%   |
| Silicon Motion      | 1         | 3.45%   |
| AMD                 | 1         | 3.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 9.09%   |
| SK hynix BC511                                                                   | 2         | 6.06%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 6.06%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 6.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 6.06%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 3.03%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 3.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 3.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 3.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 3.03%   |
| Intel SSD 660P Series                                                            | 1         | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 3.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 3.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 3.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 3.03%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 3.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 3.03%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 3.03%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 3.03%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 1         | 3.03%   |
| Unknown                                                                          | 1         | 3.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 15        | 50%     |
| NVMe | 11        | 36.67%  |
| IDE  | 4         | 13.33%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 84.62%  |
| AMD    | 4         | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 7.69%   |
| Intel Core i5-10310U CPU @ 1.70GHz              | 2         | 7.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 2         | 7.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 2         | 7.69%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 3.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 3.85%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 3.85%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 3.85%   |
| Intel Core i5-8279U CPU @ 2.40GHz               | 1         | 3.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 3.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 3.85%   |
| Intel Core i5-4310U CPU @ 2.00GHz               | 1         | 3.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 3.85%   |
| Intel Core i5 CPU M 560 @ 2.67GHz               | 1         | 3.85%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 3.85%   |
| Intel Core 2 Duo CPU L9300 @ 1.60GHz            | 1         | 3.85%   |
| Intel Core 2 CPU                                | 1         | 3.85%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 3.85%   |
| Intel Celeron CPU 867 @ 1.30GHz                 | 1         | 3.85%   |
| Intel Celeron 2955U @ 1.40GHz                   | 1         | 3.85%   |
| AMD Ryzen Embedded V1500B                       | 1         | 3.85%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 10        | 38.46%  |
| Intel Core i7      | 6         | 23.08%  |
| Intel Celeron      | 3         | 11.54%  |
| AMD Ryzen 5        | 2         | 7.69%   |
| Intel Core i3      | 1         | 3.85%   |
| Intel Core 2 Duo   | 1         | 3.85%   |
| Intel Core 2       | 1         | 3.85%   |
| AMD Ryzen Embedded | 1         | 3.85%   |
| AMD Ryzen 5 PRO    | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 12        | 46.15%  |
| 4       | 7         | 26.92%  |
| 12      | 2         | 7.69%   |
| 8       | 2         | 7.69%   |
| Unknown | 2         | 7.69%   |
| 6       | 1         | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 25        | 96.15%  |
| Unknown | 1         | 3.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 17        | 65.38%  |
| 1       | 7         | 26.92%  |
| Unknown | 2         | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 8         | 30.77%  |
| Haswell     | 4         | 15.38%  |
| Westmere    | 3         | 11.54%  |
| Zen         | 2         | 7.69%   |
| Unknown     | 2         | 7.69%   |
| Skylake     | 1         | 3.85%   |
| Silvermont  | 1         | 3.85%   |
| SandyBridge | 1         | 3.85%   |
| Penryn      | 1         | 3.85%   |
| IvyBridge   | 1         | 3.85%   |
| Core        | 1         | 3.85%   |
| Broadwell   | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 19        | 73.08%  |
| AMD    | 4         | 15.38%  |
| Nvidia | 3         | 11.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 11.54%  |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 11.54%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 7.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 7.69%   |
| AMD Lucienne                                                                             | 2         | 7.69%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 3.85%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 3.85%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 3.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 3.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 3.85%   |
| Intel HD Graphics 620                                                                    | 1         | 3.85%   |
| Intel HD Graphics 5500                                                                   | 1         | 3.85%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 3.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 3.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 3.85%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 3.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 17        | 65.38%  |
| 1 x AMD        | 4         | 15.38%  |
| 1 x Nvidia     | 2         | 7.69%   |
| Other          | 1         | 3.85%   |
| 2 x Intel      | 1         | 3.85%   |
| Intel + Nvidia | 1         | 3.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 23        | 88.46%  |
| Proprietary | 2         | 7.69%   |
| Unknown     | 1         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 85.19%  |
| 7.01-8.0   | 1         | 3.7%    |
| 3.01-4.0   | 1         | 3.7%    |
| 1.01-2.0   | 1         | 3.7%    |
| 0.51-1.0   | 1         | 3.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 4         | 22.22%  |
| LG Display          | 3         | 16.67%  |
| Lenovo              | 3         | 16.67%  |
| Samsung Electronics | 2         | 11.11%  |
| Chimei Innolux      | 2         | 11.11%  |
| BOE                 | 2         | 11.11%  |
| Unknown             | 1         | 5.56%   |
| Dell                | 1         | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C34J79x SAM0F1E 3440x1440 800x330mm 34.1-inch | 2         | 11.11%  |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch      | 2         | 11.11%  |
| AU Optronics LCD Monitor AUO2036 2560x1440 310x170mm 13.9-inch    | 2         | 11.11%  |
| Unknown LCD Monitor Sharp 3840x2160                               | 1         | 5.56%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch       | 1         | 5.56%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch           | 1         | 5.56%   |
| Lenovo LCD Monitor LEN4043 1400x1050 300x230mm 14.9-inch          | 1         | 5.56%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch           | 1         | 5.56%   |
| Dell P2719H DEL4185 1920x1080 600x340mm 27.2-inch                 | 1         | 5.56%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch   | 1         | 5.56%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch   | 1         | 5.56%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch             | 1         | 5.56%   |
| BOE LCD Monitor BOE0714 1920x1080 310x170mm 13.9-inch             | 1         | 5.56%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch    | 1         | 5.56%   |
| AU Optronics LCD Monitor 1920x1080                                | 1         | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 6         | 35.29%  |
| 1366x768 (WXGA)  | 3         | 17.65%  |
| 3440x1440        | 2         | 11.76%  |
| 2560x1440 (QHD)  | 2         | 11.76%  |
| 3840x2160 (4K)   | 1         | 5.88%   |
| 1600x900 (HD+)   | 1         | 5.88%   |
| 1440x900 (WXGA+) | 1         | 5.88%   |
| 1400x1050        | 1         | 5.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 6         | 33.33%  |
| 15      | 4         | 22.22%  |
| 34      | 2         | 11.11%  |
| 14      | 2         | 11.11%  |
| Unknown | 2         | 11.11%  |
| 27      | 1         | 5.56%   |
| 11      | 1         | 5.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 10        | 55.56%  |
| 201-300     | 3         | 16.67%  |
| 701-800     | 2         | 11.11%  |
| Unknown     | 2         | 11.11%  |
| 501-600     | 1         | 5.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 11        | 64.71%  |
| 21/9    | 2         | 11.76%  |
| Unknown | 2         | 11.76%  |
| 4/3     | 1         | 5.88%   |
| 16/10   | 1         | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 7         | 38.89%  |
| 91-100         | 3         | 16.67%  |
| 351-500        | 2         | 11.11%  |
| 101-110        | 2         | 11.11%  |
| Unknown        | 2         | 11.11%  |
| 51-60          | 1         | 5.56%   |
| 301-350        | 1         | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 8         | 44.44%  |
| 101-120 | 4         | 22.22%  |
| 161-240 | 2         | 11.11%  |
| 51-100  | 2         | 11.11%  |
| Unknown | 2         | 11.11%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 13        | 50%     |
| 0     | 10        | 38.46%  |
| 2     | 3         | 11.54%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 67.65%  |
| Realtek Semiconductor | 8         | 23.53%  |
| Hewlett-Packard       | 1         | 2.94%   |
| Dell                  | 1         | 2.94%   |
| AMD                   | 1         | 2.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 14%     |
| Intel Wireless 7260                                               | 3         | 6%      |
| Intel I211 Gigabit Network Connection                             | 3         | 6%      |
| Intel 82577LM Gigabit Network Connection                          | 3         | 6%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 4%      |
| Intel Wireless-AC 9260                                            | 2         | 4%      |
| Intel Wireless 8265 / 8275                                        | 2         | 4%      |
| Intel Wireless 7265                                               | 2         | 4%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 4%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 4%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2%      |
| Intel Wireless 8260                                               | 1         | 2%      |
| Intel WiFi Link 5100                                              | 1         | 2%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 2%      |
| Intel Ethernet Controller I225-V                                  | 1         | 2%      |
| Intel Ethernet Connection I219-V                                  | 1         | 2%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 2%      |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2%      |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2%      |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2%      |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 2%      |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 1         | 2%      |
| Intel Centrino Ultimate-N 6300                                    | 1         | 2%      |
| Intel Centrino Advanced-N 6235                                    | 1         | 2%      |
| Intel Centrino Advanced-N 6200                                    | 1         | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2%      |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2%      |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter           | 1         | 2%      |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter           | 1         | 2%      |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 84%     |
| Realtek Semiconductor | 3         | 12%     |
| Dell                  | 1         | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                      | 3         | 11.54%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter      | 2         | 7.69%   |
| Intel Wireless-AC 9260                                   | 2         | 7.69%   |
| Intel Wireless 8265 / 8275                               | 2         | 7.69%   |
| Intel Wireless 7265                                      | 2         | 7.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                        | 2         | 7.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                 | 2         | 7.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter | 1         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter | 1         | 3.85%   |
| Intel Wireless 8260                                      | 1         | 3.85%   |
| Intel WiFi Link 5100                                     | 1         | 3.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection    | 1         | 3.85%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]            | 1         | 3.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]             | 1         | 3.85%   |
| Intel Centrino Ultimate-N 6300                           | 1         | 3.85%   |
| Intel Centrino Advanced-N 6235                           | 1         | 3.85%   |
| Intel Centrino Advanced-N 6200                           | 1         | 3.85%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter  | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 65.22%  |
| Realtek Semiconductor | 7         | 30.43%  |
| AMD                   | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 30.43%  |
| Intel I211 Gigabit Network Connection                             | 3         | 13.04%  |
| Intel 82577LM Gigabit Network Connection                          | 3         | 13.04%  |
| Intel Ethernet Controller I225-V                                  | 1         | 4.35%   |
| Intel Ethernet Connection I219-V                                  | 1         | 4.35%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.35%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 4.35%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 4.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 4.35%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 4.35%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 4.35%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 52.17%  |
| Ethernet | 21        | 45.65%  |
| Modem    | 1         | 2.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 18        | 52.94%  |
| WiFi     | 15        | 44.12%  |
| Modem    | 1         | 2.94%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 16        | 61.54%  |
| 1     | 4         | 15.38%  |
| 3     | 3         | 11.54%  |
| 6     | 1         | 3.85%   |
| 5     | 1         | 3.85%   |
| 0     | 1         | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 96.15%  |
| Yes  | 1         | 3.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 75%     |
| Realtek Semiconductor | 2         | 10%     |
| Broadcom              | 2         | 10%     |
| Alps Electric         | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 7         | 35%     |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 2         | 10%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 2         | 10%     |
| Intel AX201 Bluetooth                            | 2         | 10%     |
| Broadcom BCM2045B (BDC-2.1)                      | 2         | 10%     |
| Realtek  Bluetooth Adapter                       | 1         | 5%      |
| Realtek Bluetooth Radio                          | 1         | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 5%      |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 5%      |
| Alps Electric UGTZ4 Bluetooth                    | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 22        | 73.33%  |
| AMD         | 4         | 13.33%  |
| Plantronics | 3         | 10%     |
| Nvidia      | 1         | 3.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 10.53%  |
| Plantronics Plantronics Blackwire 315.1                                                           | 3         | 7.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 7.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 7.89%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 7.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 7.89%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 5.26%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 5.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 5.26%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 2.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.63%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.63%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 2.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 2.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 37.93%  |
| SK hynix            | 5         | 17.24%  |
| Micron Technology   | 5         | 17.24%  |
| Kingston            | 3         | 10.34%  |
| Unknown             | 1         | 3.45%   |
| Transcend           | 1         | 3.45%   |
| Nanya Technology    | 1         | 3.45%   |
| Elpida              | 1         | 3.45%   |
| Corsair             | 1         | 3.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                  | 2         | 6.25%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 2         | 6.25%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 6.25%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 6.25%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 6.25%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 3.13%   |
| Unknown RAM Module 1024MB SODIMM DDR2                          | 1         | 3.13%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 1         | 3.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 3.13%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s              | 1         | 3.13%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 3.13%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                    | 1         | 3.13%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s          | 1         | 3.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 3.13%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 3.13%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 3.13%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 3.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 3.13%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s           | 1         | 3.13%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 3.13%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 1         | 3.13%   |
| Micron RAM 16JTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s         | 1         | 3.13%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s          | 1         | 3.13%   |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s              | 1         | 3.13%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s         | 1         | 3.13%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s          | 1         | 3.13%   |
| Corsair RAM CMSX64GX4M2A2666C18 32GB SODIMM DDR4 2667MT/s      | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 12        | 50%     |
| DDR3   | 10        | 41.67%  |
| LPDDR3 | 1         | 4.17%   |
| DDR2   | 1         | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 23        | 95.83%  |
| Row Of Chips | 1         | 4.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 10        | 38.46%  |
| 16384 | 5         | 19.23%  |
| 4096  | 5         | 19.23%  |
| 2048  | 4         | 15.38%  |
| 32768 | 1         | 3.85%   |
| 1024  | 1         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 6         | 25%     |
| 1600    | 6         | 25%     |
| 3200    | 4         | 16.67%  |
| 2133    | 2         | 8.33%   |
| 1334    | 2         | 8.33%   |
| 1867    | 1         | 4.17%   |
| 1333    | 1         | 4.17%   |
| 1067    | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

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
| Chicony Electronics                    | 7         | 41.18%  |
| Microdia                               | 3         | 17.65%  |
| Realtek Semiconductor                  | 2         | 11.76%  |
| Lite-On Technology                     | 1         | 5.88%   |
| Lenovo                                 | 1         | 5.88%   |
| IMC Networks                           | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.88%   |
| Acer                                   | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Realtek Realtek USB2.0 PC Camera                            | 2         | 11.76%  |
| Chicony ThinkPad T490 Webcam                                | 2         | 11.76%  |
| Chicony HP HD Camera                                        | 2         | 11.76%  |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 5.88%   |
| Microdia Integrated Webcam HD                               | 1         | 5.88%   |
| Microdia Integrated Webcam                                  | 1         | 5.88%   |
| Lite-On HP HD Camera                                        | 1         | 5.88%   |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 5.88%   |
| IMC Networks Integrated Camera                              | 1         | 5.88%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 5.88%   |
| Chicony Integrated Camera                                   | 1         | 5.88%   |
| Chicony HP Universal Camera                                 | 1         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 5.88%   |
| Acer Lenovo EasyCamera                                      | 1         | 5.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 36.36%  |
| Synaptics                  | 3         | 27.27%  |
| Upek                       | 2         | 18.18%  |
| STMicroelectronics         | 1         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 18.18%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 18.18%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 18.18%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 9.09%   |
| Validity Sensors VFS491                                   | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 9.09%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 9.09%   |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 9.09%   |

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
| 2     | 10        | 37.04%  |
| 3     | 7         | 25.93%  |
| 1     | 6         | 22.22%  |
| 4     | 2         | 7.41%   |
| 0     | 2         | 7.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 19        | 38%     |
| Fingerprint reader       | 11        | 22%     |
| Card reader              | 7         | 14%     |
| Bluetooth                | 7         | 14%     |
| Firewire controller      | 3         | 6%      |
| Net/wireless             | 2         | 4%      |
| Graphics card            | 1         | 2%      |

