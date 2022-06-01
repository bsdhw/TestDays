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

Total: 29

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| OPNsense 21.7.7      | 2         | 8.7%    |
| FreeBSD 14.0-CURRENT | 2         | 8.7%    |
| FreeBSD 13.0-p4      | 2         | 8.7%    |
| FreeBSD 12.1-p8      | 2         | 8.7%    |
| FreeBSD 12.1-p5      | 2         | 8.7%    |
| OPNsense 22.1.6      | 1         | 4.35%   |
| OPNsense 22.1.2      | 1         | 4.35%   |
| OPNsense 21.7.6      | 1         | 4.35%   |
| OpenBSD 6.8          | 1         | 4.35%   |
| helloSystem 0.7.0    | 1         | 4.35%   |
| helloSystem 0.5.0    | 1         | 4.35%   |
| FreeBSD 13.0-CURRENT | 1         | 4.35%   |
| FreeBSD 13.0         | 1         | 4.35%   |
| FreeBSD 12.3         | 1         | 4.35%   |
| FreeBSD 12.2-p5      | 1         | 4.35%   |
| FreeBSD 12.2         | 1         | 4.35%   |
| FreeBSD 12.1-p4      | 1         | 4.35%   |
| FreeBSD 12.1-p10     | 1         | 4.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 13        | 65%     |
| OPNsense    | 4         | 20%     |
| helloSystem | 2         | 10%     |
| OpenBSD     | 1         | 5%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 20        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| KDE5         | 7         | 33.33%  |
| Console      | 4         | 19.05%  |
| XFCE         | 2         | 9.52%   |
| helloDesktop | 2         | 9.52%   |
| MATE         | 1         | 4.76%   |
| LXQt         | 1         | 4.76%   |
| i3           | 1         | 4.76%   |
| GNOME        | 1         | 4.76%   |
| fvwm         | 1         | 4.76%   |
| Cinnamon     | 1         | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 15        | 75%     |
| Console | 4         | 20%     |
| Wayland | 1         | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 8         | 40%     |
| SDDM    | 7         | 35%     |
| SLiM    | 2         | 10%     |
| XDM     | 1         | 5%      |
| LightDM | 1         | 5%      |
| GDM     | 1         | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 9         | 40.91%  |
| en_US   | 5         | 22.73%  |
| C       | 5         | 22.73%  |
| de_DE   | 1         | 4.55%   |
| de_AT   | 1         | 4.55%   |
| cs_CZ   | 1         | 4.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 16        | 80%     |
| BIOS | 4         | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 12        | 60%     |
| Ufs  | 7         | 35%     |
| Ffs  | 1         | 5%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 18        | 90%     |
| MBR  | 2         | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo          | 10        | 50%     |
| Dell            | 4         | 20%     |
| Hewlett-Packard | 3         | 15%     |
| Panasonic       | 1         | 5%      |
| BESSTAR Tech    | 1         | 5%      |
| Unknown         | 1         | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo ThinkPad T490 20N2CTO1WW      | 2         | 10%     |
| Panasonic CF-30KTP48NL               | 1         | 5%      |
| Lenovo Y50-70 20378                  | 1         | 5%      |
| Lenovo ThinkPad T60 2007J3G          | 1         | 5%      |
| Lenovo ThinkPad T510 4384AJ6         | 1         | 5%      |
| Lenovo ThinkPad T410 2537WEE         | 1         | 5%      |
| Lenovo ThinkPad T410 2537AT1         | 1         | 5%      |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE | 1         | 5%      |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE | 1         | 5%      |
| Lenovo IdeaPad 110S-11IBR 80WG       | 1         | 5%      |
| HP ZBook 17 G4                       | 1         | 5%      |
| HP EliteBook Folio 9470m             | 1         | 5%      |
| HP EliteBook 840 G3                  | 1         | 5%      |
| Dell XPS 13 9360                     | 1         | 5%      |
| Dell Vostro V131                     | 1         | 5%      |
| Dell Precision 7530                  | 1         | 5%      |
| Dell Latitude E7440                  | 1         | 5%      |
| BESSTAR Tech U820                    | 1         | 5%      |
| Unknown                              | 1         | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 8         | 40%     |
| HP EliteBook           | 2         | 10%     |
| Panasonic CF-30KTP48NL | 1         | 5%      |
| Lenovo Y50-70          | 1         | 5%      |
| Lenovo IdeaPad         | 1         | 5%      |
| HP ZBook               | 1         | 5%      |
| Dell XPS               | 1         | 5%      |
| Dell Vostro            | 1         | 5%      |
| Dell Precision         | 1         | 5%      |
| Dell Latitude          | 1         | 5%      |
| BESSTAR Tech U820      | 1         | 5%      |
| Unknown                | 1         | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 4         | 20%     |
| 2021 | 3         | 15%     |
| 2010 | 3         | 15%     |
| 2018 | 2         | 10%     |
| 2017 | 2         | 10%     |
| 2020 | 1         | 5%      |
| 2016 | 1         | 5%      |
| 2015 | 1         | 5%      |
| 2011 | 1         | 5%      |
| 2009 | 1         | 5%      |
| 2006 | 1         | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 20        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 20        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 6         | 30%     |
| 16.01-24.0  | 5         | 25%     |
| 32.01-64.0  | 3         | 15%     |
| 3.01-4.0    | 2         | 10%     |
| 2.01-3.0    | 2         | 10%     |
| 4.01-8.0    | 1         | 5%      |
| 64.01-256.0 | 1         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 8         | 40%     |
| 1.01-2.0 | 5         | 25%     |
| 0.51-1.0 | 5         | 25%     |
| 2.01-3.0 | 2         | 10%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 14        | 70%     |
| 3      | 2         | 10%     |
| 2      | 2         | 10%     |
| 0      | 2         | 10%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 19        | 95%     |
| Yes       | 1         | 5%      |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 85%     |
| No        | 3         | 15%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 95%     |
| No        | 1         | 5%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 76.19%  |
| No        | 5         | 23.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Austria | 20        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vienna           | 12        | 57.14%  |
| Graz             | 2         | 9.52%   |
| Wels             | 1         | 4.76%   |
| Weidlingbach     | 1         | 4.76%   |
| Parndorf         | 1         | 4.76%   |
| Maria Enzersdorf | 1         | 4.76%   |
| Linz             | 1         | 4.76%   |
| Innsbruck        | 1         | 4.76%   |
| Bruck an der Mur | 1         | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 8      | 33.33%  |
| Intel               | 4         | 5      | 16.67%  |
| WDC                 | 3         | 3      | 12.5%   |
| SanDisk             | 2         | 2      | 8.33%   |
| Transcend           | 1         | 2      | 4.17%   |
| Seagate             | 1         | 1      | 4.17%   |
| Kingston            | 1         | 4      | 4.17%   |
| Intenso             | 1         | 1      | 4.17%   |
| Hitachi             | 1         | 1      | 4.17%   |
| HGST                | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung MZALQ512HBLU-00BL1 512GB     | 2         | 8%      |
| Intel SSDPEKKF512G8L 512GB           | 2         | 8%      |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 4%      |
| WDC WD20SPZX-22CRAT0 2TB             | 1         | 4%      |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 4%      |
| Transcend TS2TMTE220S 2TB            | 1         | 4%      |
| Seagate ST1000LX015-1U7172 1TB       | 1         | 4%      |
| SanDisk SSD PLUS 240GB               | 1         | 4%      |
| SanDisk SD7TB3Q-128G-1006 128GB      | 1         | 4%      |
| Samsung SSD PM851 mSATA 256GB        | 1         | 4%      |
| Samsung SSD PM841 2.5-inch 7mm 256GB | 1         | 4%      |
| Samsung SSD 860 EVO 250GB            | 1         | 4%      |
| Samsung MZVKW512HMJP-000H1 512GB     | 1         | 4%      |
| Samsung MZ7TE512HMHP-000L2 512GB     | 1         | 4%      |
| Samsung HM320JI 320GB                | 1         | 4%      |
| Kingston SUV500MS480G 480GB          | 1         | 4%      |
| Kingston SUV500MS120G 120GB          | 1         | 4%      |
| Intenso JAJM600M256C 256GB           | 1         | 4%      |
| Intel SSDSCKKF256G8H 256GB           | 1         | 4%      |
| Intel SSDPEKNW020T8 2TB              | 1         | 4%      |
| Hitachi HTS541040G9SA00 40GB         | 1         | 4%      |
| HGST HTS545050A7E680 500GB           | 1         | 4%      |
| Crucial CT275MX300SSD4 275GB         | 1         | 4%      |

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
| Samsung Electronics | 4         | 4      | 40%     |
| SanDisk             | 2         | 2      | 20%     |
| Kingston            | 1         | 4      | 10%     |
| Intenso             | 1         | 1      | 10%     |
| Intel               | 1         | 2      | 10%     |
| Crucial             | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 9         | 14     | 42.86%  |
| NVMe | 6         | 8      | 28.57%  |
| HDD  | 6         | 7      | 28.57%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 12        | 21     | 66.67%  |
| NVMe | 6         | 8      | 33.33%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 10        | 17     | 71.43%  |
| 0.51-1.0   | 3         | 3      | 21.43%  |
| 1.01-2.0   | 1         | 1      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 8         | 40%     |
| 101-250    | 6         | 30%     |
| 21-50      | 2         | 10%     |
| 51-100     | 2         | 10%     |
| 1-20       | 1         | 5%      |
| 501-1000   | 1         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 15        | 71.43%  |
| 21-50   | 3         | 14.29%  |
| 251-500 | 1         | 4.76%   |
| 101-250 | 1         | 4.76%   |
| 51-100  | 1         | 4.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB  | 1         | 1      | 33.33%  |
| Intel SSDSCKKF256G8H 256GB   | 1         | 2      | 33.33%  |
| Hitachi HTS541040G9SA00 40GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Intel   | 1         | 2      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

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
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 2      | 33.33%  |

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
| Works   | 16        | 25     | 84.21%  |
| Malfunc | 3         | 4      | 15.79%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 17        | 77.27%  |
| Samsung Electronics | 3         | 13.64%  |
| Toshiba             | 1         | 4.55%   |
| Silicon Motion      | 1         | 4.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980                                                  | 2         | 7.69%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 7.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 7.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 7.69%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 3.85%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 3.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 3.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 3.85%   |
| Intel SSD 660P Series                                                            | 1         | 3.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 3.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 3.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 3.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 3.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 3.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 3.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 3.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 3.85%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 3.85%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 3.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 3.85%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 3.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 12        | 52.17%  |
| NVMe | 7         | 30.43%  |
| IDE  | 4         | 17.39%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 18        | 90%     |
| AMD    | 2         | 10%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i7-8665U CPU @ 1.90GHz      | 2         | 10%     |
| Intel Core i5 CPU M 520 @ 2.40GHz      | 2         | 10%     |
| AMD Ryzen 5 5500U with Radeon Graphics | 2         | 10%     |
| Intel Core i7-8850H CPU @ 2.60GHz      | 1         | 5%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 1         | 5%      |
| Intel Core i7-4710HQ CPU @ 2.50GHz     | 1         | 5%      |
| Intel Core i7-3687U CPU @ 2.10GHz      | 1         | 5%      |
| Intel Core i5-8279U CPU @ 2.40GHz      | 1         | 5%      |
| Intel Core i5-7200U CPU @ 2.50GHz      | 1         | 5%      |
| Intel Core i5-6200U CPU @ 2.30GHz      | 1         | 5%      |
| Intel Core i5-4310U CPU @ 2.00GHz      | 1         | 5%      |
| Intel Core i5 CPU M 560 @ 2.67GHz      | 1         | 5%      |
| Intel Core 2 Duo CPU L9300 @ 1.60GHz   | 1         | 5%      |
| Intel Core 2 CPU                       | 1         | 5%      |
| Intel Celeron CPU N3060 @ 1.60GHz      | 1         | 5%      |
| Intel Celeron CPU 867 @ 1.30GHz        | 1         | 5%      |
| Intel Celeron 2955U @ 1.40GHz          | 1         | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 7         | 35%     |
| Intel Core i7    | 6         | 30%     |
| Intel Celeron    | 3         | 15%     |
| AMD Ryzen 5      | 2         | 10%     |
| Intel Core 2 Duo | 1         | 5%      |
| Intel Core 2     | 1         | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 10        | 50%     |
| 4       | 5         | 25%     |
| 12      | 2         | 10%     |
| Unknown | 2         | 10%     |
| 6       | 1         | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 19        | 95%     |
| Unknown | 1         | 5%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 13        | 65%     |
| 1       | 5         | 25%     |
| Unknown | 2         | 10%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 6         | 30%     |
| Westmere    | 3         | 15%     |
| Haswell     | 3         | 15%     |
| Unknown     | 2         | 10%     |
| Skylake     | 1         | 5%      |
| Silvermont  | 1         | 5%      |
| SandyBridge | 1         | 5%      |
| Penryn      | 1         | 5%      |
| IvyBridge   | 1         | 5%      |
| Core        | 1         | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 15        | 71.43%  |
| Nvidia | 3         | 14.29%  |
| AMD    | 3         | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 14.29%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 9.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 9.52%   |
| AMD Lucienne                                                                             | 2         | 9.52%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 4.76%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 4.76%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 4.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 4.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 4.76%   |
| Intel HD Graphics 620                                                                    | 1         | 4.76%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 4.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 4.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 4.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 4.76%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 4.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 13        | 65%     |
| 1 x AMD        | 3         | 15%     |
| 1 x Nvidia     | 2         | 10%     |
| 2 x Intel      | 1         | 5%      |
| Intel + Nvidia | 1         | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 18        | 90%     |
| Proprietary | 2         | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 80.95%  |
| 7.01-8.0   | 1         | 4.76%   |
| 3.01-4.0   | 1         | 4.76%   |
| 1.01-2.0   | 1         | 4.76%   |
| 0.51-1.0   | 1         | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 4         | 26.67%  |
| Lenovo              | 3         | 20%     |
| Samsung Electronics | 2         | 13.33%  |
| Chimei Innolux      | 2         | 13.33%  |
| BOE                 | 2         | 13.33%  |
| Unknown             | 1         | 6.67%   |
| Dell                | 1         | 6.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C34J79x SAM0F1E 3440x1440 800x330mm 34.1-inch | 2         | 13.33%  |
| AU Optronics LCD Monitor AUO2036 2560x1440 310x170mm 13.9-inch    | 2         | 13.33%  |
| Unknown LCD Monitor Sharp 3840x2160                               | 1         | 6.67%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch           | 1         | 6.67%   |
| Lenovo LCD Monitor LEN4043 1400x1050 300x230mm 14.9-inch          | 1         | 6.67%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch           | 1         | 6.67%   |
| Dell P2719H DEL4185 1920x1080 600x340mm 27.2-inch                 | 1         | 6.67%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch   | 1         | 6.67%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch   | 1         | 6.67%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch             | 1         | 6.67%   |
| BOE LCD Monitor BOE0714 1920x1080 310x170mm 13.9-inch             | 1         | 6.67%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch    | 1         | 6.67%   |
| AU Optronics LCD Monitor 1920x1080                                | 1         | 6.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 4         | 28.57%  |
| 3440x1440        | 2         | 14.29%  |
| 2560x1440 (QHD)  | 2         | 14.29%  |
| 1366x768 (WXGA)  | 2         | 14.29%  |
| 3840x2160 (4K)   | 1         | 7.14%   |
| 1600x900 (HD+)   | 1         | 7.14%   |
| 1440x900 (WXGA+) | 1         | 7.14%   |
| 1400x1050        | 1         | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 6         | 40%     |
| 34      | 2         | 13.33%  |
| 14      | 2         | 13.33%  |
| Unknown | 2         | 13.33%  |
| 27      | 1         | 6.67%   |
| 15      | 1         | 6.67%   |
| 11      | 1         | 6.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 7         | 46.67%  |
| 201-300     | 3         | 20%     |
| 701-800     | 2         | 13.33%  |
| Unknown     | 2         | 13.33%  |
| 501-600     | 1         | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 8         | 57.14%  |
| 21/9    | 2         | 14.29%  |
| Unknown | 2         | 14.29%  |
| 4/3     | 1         | 7.14%   |
| 16/10   | 1         | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 7         | 46.67%  |
| 351-500        | 2         | 13.33%  |
| Unknown        | 2         | 13.33%  |
| 51-60          | 1         | 6.67%   |
| 301-350        | 1         | 6.67%   |
| 101-110        | 1         | 6.67%   |
| 91-100         | 1         | 6.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 6         | 40%     |
| 101-120 | 4         | 26.67%  |
| 161-240 | 2         | 13.33%  |
| Unknown | 2         | 13.33%  |
| 51-100  | 1         | 6.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 10        | 50%     |
| 0     | 7         | 35%     |
| 2     | 3         | 15%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 68%     |
| Realtek Semiconductor | 6         | 24%     |
| Hewlett-Packard       | 1         | 4%      |
| Dell                  | 1         | 4%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 12.5%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 7.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 5%      |
| Intel Wireless 8265 / 8275                                        | 2         | 5%      |
| Intel Wireless 7260                                               | 2         | 5%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 5%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.5%    |
| Intel Wireless-AC 9260                                            | 1         | 2.5%    |
| Intel Wireless 8260                                               | 1         | 2.5%    |
| Intel Wireless 7265                                               | 1         | 2.5%    |
| Intel WiFi Link 5100                                              | 1         | 2.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 2.5%    |
| Intel I211 Gigabit Network Connection                             | 1         | 2.5%    |
| Intel Ethernet Controller I225-V                                  | 1         | 2.5%    |
| Intel Ethernet Connection I219-V                                  | 1         | 2.5%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 2.5%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 2.5%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 1         | 2.5%    |
| Intel Centrino Ultimate-N 6300                                    | 1         | 2.5%    |
| Intel Centrino Advanced-N 6235                                    | 1         | 2.5%    |
| Intel Centrino Advanced-N 6200                                    | 1         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 2.5%    |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 2.5%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.5%    |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter           | 1         | 2.5%    |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter           | 1         | 2.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 80%     |
| Realtek Semiconductor | 3         | 15%     |
| Dell                  | 1         | 5%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter      | 2         | 9.52%   |
| Intel Wireless 8265 / 8275                               | 2         | 9.52%   |
| Intel Wireless 7260                                      | 2         | 9.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                 | 2         | 9.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter | 1         | 4.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter | 1         | 4.76%   |
| Intel Wireless-AC 9260                                   | 1         | 4.76%   |
| Intel Wireless 8260                                      | 1         | 4.76%   |
| Intel Wireless 7265                                      | 1         | 4.76%   |
| Intel WiFi Link 5100                                     | 1         | 4.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection    | 1         | 4.76%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]            | 1         | 4.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]             | 1         | 4.76%   |
| Intel Centrino Ultimate-N 6300                           | 1         | 4.76%   |
| Intel Centrino Advanced-N 6235                           | 1         | 4.76%   |
| Intel Centrino Advanced-N 6200                           | 1         | 4.76%   |
| Dell Dell Wireless 5550 HSPA+ Mini-Card Network Adapter  | 1         | 4.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 72.22%  |
| Realtek Semiconductor | 5         | 27.78%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 27.78%  |
| Intel 82577LM Gigabit Network Connection                          | 3         | 16.67%  |
| Intel I211 Gigabit Network Connection                             | 1         | 5.56%   |
| Intel Ethernet Controller I225-V                                  | 1         | 5.56%   |
| Intel Ethernet Connection I219-V                                  | 1         | 5.56%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 5.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 5.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 5.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 5.56%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 5.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 5.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 51.35%  |
| Ethernet | 17        | 45.95%  |
| Modem    | 1         | 2.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 15        | 53.57%  |
| WiFi     | 12        | 42.86%  |
| Modem    | 1         | 3.57%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 15        | 75%     |
| 1     | 2         | 10%     |
| 6     | 1         | 5%      |
| 3     | 1         | 5%      |
| 0     | 1         | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 95%     |
| Yes  | 1         | 5%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 68.75%  |
| Realtek Semiconductor | 2         | 12.5%   |
| Broadcom              | 2         | 12.5%   |
| Alps Electric         | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 6         | 37.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 2         | 12.5%   |
| Broadcom BCM2045B (BDC-2.1)                      | 2         | 12.5%   |
| Realtek  Bluetooth Adapter                       | 1         | 6.25%   |
| Realtek Bluetooth Radio                          | 1         | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 1         | 6.25%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 6.25%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 6.25%   |
| Alps Electric UGTZ4 Bluetooth                    | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 18        | 81.82%  |
| AMD         | 2         | 9.09%   |
| Plantronics | 1         | 4.55%   |
| Nvidia      | 1         | 4.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 11.11%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 11.11%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 7.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 7.41%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 7.41%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 7.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 7.41%   |
| Plantronics Plantronics Blackwire 315.1                                                           | 1         | 3.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 3.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 3.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 3.7%    |
| Intel CM238 HD Audio Controller                                                                   | 1         | 3.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 3.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 3.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 3.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 3.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 3.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 41.67%  |
| Micron Technology   | 5         | 20.83%  |
| Kingston            | 3         | 12.5%   |
| SK Hynix            | 2         | 8.33%   |
| Unknown             | 1         | 4.17%   |
| Nanya Technology    | 1         | 4.17%   |
| Elpida              | 1         | 4.17%   |
| Corsair             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 2         | 7.41%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 7.41%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 7.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 7.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 3.7%    |
| Unknown RAM Module 1024MB SODIMM DDR2                          | 1         | 3.7%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s              | 1         | 3.7%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 3.7%    |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                    | 1         | 3.7%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s          | 1         | 3.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 3.7%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 3.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 3.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 3.7%    |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM 1334MT/s                | 1         | 3.7%    |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 3.7%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 1         | 3.7%    |
| Micron RAM 16JTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s         | 1         | 3.7%    |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s          | 1         | 3.7%    |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s              | 1         | 3.7%    |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s         | 1         | 3.7%    |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1066MT/s          | 1         | 3.7%    |
| Corsair RAM CMSX64GX4M2A2666C18 32GB SODIMM DDR4 2667MT/s      | 1         | 3.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 9         | 47.37%  |
| DDR4   | 8         | 42.11%  |
| LPDDR3 | 1         | 5.26%   |
| DDR2   | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 18        | 94.74%  |
| Row Of Chips | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 7         | 33.33%  |
| 4096  | 5         | 23.81%  |
| 2048  | 4         | 19.05%  |
| 16384 | 3         | 14.29%  |
| 32768 | 1         | 4.76%   |
| 1024  | 1         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 5         | 26.32%  |
| 2667    | 4         | 21.05%  |
| 3200    | 2         | 10.53%  |
| 2133    | 2         | 10.53%  |
| 1334    | 2         | 10.53%  |
| 1867    | 1         | 5.26%   |
| 1333    | 1         | 5.26%   |
| 1066    | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

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
| Chicony Electronics                    | 4         | 28.57%  |
| Microdia                               | 3         | 21.43%  |
| Realtek Semiconductor                  | 2         | 14.29%  |
| Lite-On Technology                     | 1         | 7.14%   |
| Lenovo                                 | 1         | 7.14%   |
| IMC Networks                           | 1         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 7.14%   |
| Acer                                   | 1         | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Realtek Realtek USB2.0 PC Camera                            | 2         | 14.29%  |
| Chicony ThinkPad T490 Webcam                                | 2         | 14.29%  |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 7.14%   |
| Microdia Integrated Webcam HD                               | 1         | 7.14%   |
| Microdia Integrated Webcam                                  | 1         | 7.14%   |
| Lite-On HP HD Camera                                        | 1         | 7.14%   |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 7.14%   |
| IMC Networks Integrated Camera                              | 1         | 7.14%   |
| Chicony Ltd., Integrated Camera                             | 1         | 7.14%   |
| Chicony HP Universal Camera                                 | 1         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 7.14%   |
| Acer Lenovo EasyCamera                                      | 1         | 7.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 44.44%  |
| Upek                       | 2         | 22.22%  |
| Synaptics                  | 1         | 11.11%  |
| STMicroelectronics         | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 22.22%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 22.22%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 11.11%  |
| Validity Sensors VFS491                                | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 11.11%  |
| STMicroelectronics Fingerprint Reader                  | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 11.11%  |

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
| 2     | 9         | 42.86%  |
| 3     | 5         | 23.81%  |
| 1     | 5         | 23.81%  |
| 4     | 1         | 4.76%   |
| 0     | 1         | 4.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 14        | 35%     |
| Fingerprint reader       | 9         | 22.5%   |
| Card reader              | 6         | 15%     |
| Bluetooth                | 5         | 12.5%   |
| Firewire controller      | 3         | 7.5%    |
| Net/wireless             | 2         | 5%      |
| Graphics card            | 1         | 2.5%    |

