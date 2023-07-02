OpenBSD 7.3 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 23

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Sony          | VGC-RB41M                   | [95804a1f40](https://bsd-hardware.info/?probe=95804a1f40) | Jun 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [4d99bc4b63](https://bsd-hardware.info/?probe=4d99bc4b63) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [8866724f46](https://bsd-hardware.info/?probe=8866724f46) | Jun 27, 2023 |
| Gigabyte      | G41MT-S2                    | [355202536f](https://bsd-hardware.info/?probe=355202536f) | Jun 07, 2023 |
| ASUSTek       | PRIME B460M-A               | [4c8047dca3](https://bsd-hardware.info/?probe=4c8047dca3) | May 19, 2023 |
| VIA Techno... | VT82C597                    | [d73db58e48](https://bsd-hardware.info/?probe=d73db58e48) | May 19, 2023 |
| HP            | 0A60h                       | [98e9deff3d](https://bsd-hardware.info/?probe=98e9deff3d) | May 16, 2023 |
| PC Engines    | APU2                        | [62fef2616b](https://bsd-hardware.info/?probe=62fef2616b) | May 15, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [2ce057e389](https://bsd-hardware.info/?probe=2ce057e389) | May 14, 2023 |
| ASUSTek       | M3A78-EMH HDMI              | [b4bf04ac2f](https://bsd-hardware.info/?probe=b4bf04ac2f) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [fa87f4741a](https://bsd-hardware.info/?probe=fa87f4741a) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [bd81294acc](https://bsd-hardware.info/?probe=bd81294acc) | May 13, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [cace71018f](https://bsd-hardware.info/?probe=cace71018f) | May 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [4353bb0195](https://bsd-hardware.info/?probe=4353bb0195) | May 09, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [be83fbb0f2](https://bsd-hardware.info/?probe=be83fbb0f2) | May 09, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [827308827b](https://bsd-hardware.info/?probe=827308827b) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c26c1111c6](https://bsd-hardware.info/?probe=c26c1111c6) | Apr 21, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [a6141b809a](https://bsd-hardware.info/?probe=a6141b809a) | Apr 21, 2023 |
| ASUSTek       | P10S-I Series               | [5084c2b77f](https://bsd-hardware.info/?probe=5084c2b77f) | Apr 11, 2023 |
| Apple         | MacPro1,1                   | [6843822d8c](https://bsd-hardware.info/?probe=6843822d8c) | Apr 11, 2023 |
| PC Engines    | APU2                        | [cdcdfe6e0b](https://bsd-hardware.info/?probe=cdcdfe6e0b) | Apr 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [a149d0b4b5](https://bsd-hardware.info/?probe=a149d0b4b5) | Apr 10, 2023 |
| Elpitech      | ET101-A1                    | [0172697883](https://bsd-hardware.info/?probe=0172697883) | Mar 10, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 13       | 81.25%  |
| i386  | 2        | 12.5%   |
| arm64 | 1        | 6.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 14       | 87.5%   |
| XFCE         | 1        | 6.25%   |
| GNOME        | 1        | 6.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 10       | 62.5%   |
| Console | 6        | 37.5%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 16       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 87.5%   |
| ru_RU   | 1        | 6.25%   |
| en_US   | 1        | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 9        | 56.25%  |
| EFI  | 7        | 43.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 16       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 10       | 62.5%   |
| GPT  | 6        | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 6        | 37.5%   |
| PC Engines          | 2        | 12.5%   |
| Gigabyte Technology | 2        | 12.5%   |
| VIA Technologies    | 1        | 6.25%   |
| Sony                | 1        | 6.25%   |
| Lenovo              | 1        | 6.25%   |
| Hewlett-Packard     | 1        | 6.25%   |
| Elpitech            | 1        | 6.25%   |
| Apple               | 1        | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| PC Engines APU2                    | 2        | 12.5%   |
| VIA VT82C597                       | 1        | 6.25%   |
| Sony VGC-RB41M                     | 1        | 6.25%   |
| Lenovo V14 G2 ITL 82NM             | 1        | 6.25%   |
| HP Compaq dc5700 Microtower        | 1        | 6.25%   |
| Gigabyte G41MT-S2                  | 1        | 6.25%   |
| Gigabyte B250M-Gaming 3            | 1        | 6.25%   |
| Elpitech ET101-A1                  | 1        | 6.25%   |
| ASUS TUF Gaming B550M-PLUS (WI-FI) | 1        | 6.25%   |
| ASUS TUF Gaming B550-PLUS          | 1        | 6.25%   |
| ASUS PRIME B650-PLUS               | 1        | 6.25%   |
| ASUS PRIME B460M-A                 | 1        | 6.25%   |
| ASUS P10S-I Series                 | 1        | 6.25%   |
| ASUS M3A78-EMH HDMI                | 1        | 6.25%   |
| Apple MacPro1,1                    | 1        | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| PC Engines APU2       | 2        | 12.5%   |
| ASUS TUF              | 2        | 12.5%   |
| ASUS PRIME            | 2        | 12.5%   |
| VIA VT82C597          | 1        | 6.25%   |
| Sony VGC-RB41M        | 1        | 6.25%   |
| Lenovo V14            | 1        | 6.25%   |
| HP Compaq             | 1        | 6.25%   |
| Gigabyte G41MT-S2     | 1        | 6.25%   |
| Gigabyte B250M-Gaming | 1        | 6.25%   |
| Elpitech ET101-A1     | 1        | 6.25%   |
| ASUS P10S-I           | 1        | 6.25%   |
| ASUS M3A78-EMH        | 1        | 6.25%   |
| Apple MacPro1         | 1        | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2023    | 3        | 18.75%  |
| 2022    | 2        | 12.5%   |
| 2016    | 2        | 12.5%   |
| 2010    | 2        | 12.5%   |
| 2021    | 1        | 6.25%   |
| 2019    | 1        | 6.25%   |
| 2018    | 1        | 6.25%   |
| 2007    | 1        | 6.25%   |
| 2006    | 1        | 6.25%   |
| 2005    | 1        | 6.25%   |
| Unknown | 1        | 6.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 16       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 14       | 87.5%   |
| Yes  | 2        | 12.5%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 6        | 35.29%  |
| 4.01-8.0    | 4        | 23.53%  |
| 64.01-256.0 | 3        | 17.65%  |
| 0.01-0.5    | 2        | 11.76%  |
| 32.01-64.0  | 1        | 5.88%   |
| 16.01-24.0  | 1        | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 10       | 62.5%   |
| 1.01-2.0 | 2        | 12.5%   |
| 0        | 2        | 12.5%   |
| 4.01-8.0 | 1        | 6.25%   |
| 0.51-1.0 | 1        | 6.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 9        | 56.25%  |
| 2      | 3        | 18.75%  |
| 3      | 2        | 12.5%   |
| 8      | 1        | 6.25%   |
| 6      | 1        | 6.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 14       | 87.5%   |
| No        | 2        | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 81.25%  |
| Yes       | 3        | 18.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 13       | 81.25%  |
| Yes       | 3        | 18.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 5        | 31.25%  |
| Germany | 3        | 18.75%  |
| Mexico  | 2        | 12.5%   |
| Brazil  | 2        | 12.5%   |
| USA     | 1        | 6.25%   |
| Spain   | 1        | 6.25%   |
| Romania | 1        | 6.25%   |
| Italy   | 1        | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Puebla City      | 2        | 12.5%   |
| Nuremberg        | 2        | 12.5%   |
| Moscow           | 2        | 12.5%   |
| Blumenau         | 2        | 12.5%   |
| St Petersburg    | 1        | 6.25%   |
| Podolsk          | 1        | 6.25%   |
| Oltenita         | 1        | 6.25%   |
| Monheim am Rhein | 1        | 6.25%   |
| Milan            | 1        | 6.25%   |
| Krasnodar        | 1        | 6.25%   |
| Barcelona        | 1        | 6.25%   |
| Austin           | 1        | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| NVMe                | 6        | 9      | 23.08%  |
| Samsung Electronics | 5        | 10     | 19.23%  |
| Hitachi             | 3        | 3      | 11.54%  |
| Seagate             | 2        | 3      | 7.69%   |
| OPENBSD             | 2        | 2      | 7.69%   |
| Kingston            | 2        | 2      | 7.69%   |
| WDC                 | 1        | 1      | 3.85%   |
| SanDisk             | 1        | 3      | 3.85%   |
| HGST                | 1        | 1      | 3.85%   |
| Crucial             | 1        | 2      | 3.85%   |
| Apacer              | 1        | 1      | 3.85%   |
| A-DATA Technology   | 1        | 1      | 3.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| NVMe Samsung SSD 980 500GB    | 2        | 6.9%    |
| WDC WD20PURX-64P6ZY0 2TB      | 1        | 3.45%   |
| Seagate ST3500414CS 500GB     | 1        | 3.45%   |
| Seagate ST3250824AS P 250GB   | 1        | 3.45%   |
| Seagate ST3250318AS 250GB     | 1        | 3.45%   |
| SanDisk SSD PLUS 120GB        | 1        | 3.45%   |
| SanDisk Cruzer Blade 64GB     | 1        | 3.45%   |
| Samsung SSD 870 QVO 2TB       | 1        | 3.45%   |
| Samsung SSD 870 EVO 500GB     | 1        | 3.45%   |
| Samsung SSD 840 EVO 250GB     | 1        | 3.45%   |
| Samsung HD161HJ 160GB         | 1        | 3.45%   |
| Samsung Flash Drive FIT 32GB  | 1        | 3.45%   |
| OPENBSD SR RAID 5 9.9TB       | 1        | 3.45%   |
| OPENBSD SR RAID 1 2TB         | 1        | 3.45%   |
| NVMe WDBRPG5000ANC-WR 500GB   | 1        | 3.45%   |
| NVMe TOSHIBA-RC100 240GB      | 1        | 3.45%   |
| NVMe SSSTC CL1-4D256 256GB    | 1        | 3.45%   |
| NVMe Sabrent Rocket 4 500GB   | 1        | 3.45%   |
| NVMe Asgard AN1TNVMe- 1TB     | 1        | 3.45%   |
| Kingston SMS200S330G 32GB     | 1        | 3.45%   |
| Kingston SA400S37480G 480GB   | 1        | 3.45%   |
| Hitachi HUA723020ALA640 2TB   | 1        | 3.45%   |
| Hitachi HDS722516VLAT80 164GB | 1        | 3.45%   |
| Hitachi HCS5C1032CLA382 320GB | 1        | 3.45%   |
| HGST HUS724020ALA640 2TB      | 1        | 3.45%   |
| Crucial CT500BX500SSD1 500GB  | 1        | 3.45%   |
| Apacer AST280 120GB           | 1        | 3.45%   |
| A-DATA SP550 240GB            | 1        | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| NVMe                | 4        | 7      | 26.67%  |
| Hitachi             | 3        | 3      | 20%     |
| Seagate             | 2        | 3      | 13.33%  |
| Samsung Electronics | 2        | 2      | 13.33%  |
| OPENBSD             | 2        | 2      | 13.33%  |
| WDC                 | 1        | 1      | 6.67%   |
| HGST                | 1        | 1      | 6.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 8      | 27.27%  |
| NVMe                | 2        | 2      | 18.18%  |
| Kingston            | 2        | 2      | 18.18%  |
| SanDisk             | 1        | 3      | 9.09%   |
| Crucial             | 1        | 2      | 9.09%   |
| Apacer              | 1        | 1      | 9.09%   |
| A-DATA Technology   | 1        | 1      | 9.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 10       | 19     | 50%     |
| HDD  | 10       | 19     | 50%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 15       | 38     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 15       | 25     | 78.95%  |
| 1.01-2.0   | 3        | 12     | 15.79%  |
| 4.01-10.0  | 1        | 1      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 4        | 23.53%  |
| 101-250        | 4        | 23.53%  |
| 21-50          | 3        | 17.65%  |
| More than 3000 | 2        | 11.76%  |
| 51-100         | 2        | 11.76%  |
| 1-20           | 1        | 5.88%   |
| 501-1000       | 1        | 5.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 11       | 68.75%  |
| More than 3000 | 1        | 6.25%   |
| 251-500        | 1        | 6.25%   |
| 21-50          | 1        | 6.25%   |
| 2001-3000      | 1        | 6.25%   |
| 101-250        | 1        | 6.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 20%     |
| Samsung Electronics SSD 840 EVO 250GB | 1        | 1      | 20%     |
| Samsung Electronics HD161HJ 160GB     | 1        | 1      | 20%     |
| Hitachi HDS722516VLAT80 164GB         | 1        | 1      | 20%     |
| A-DATA Technology SP550 240GB         | 1        | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 60%     |
| Hitachi             | 1        | 1      | 20%     |
| A-DATA Technology   | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 50%     |
| Hitachi             | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 3        | 3      | 60%     |
| HDD  | 2        | 2      | 40%     |

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
| Works    | 10       | 22     | 47.62%  |
| Detected | 6        | 11     | 28.57%  |
| Malfunc  | 5        | 5      | 23.81%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 8        | 34.78%  |
| AMD                            | 6        | 26.09%  |
| Samsung Electronics            | 2        | 8.7%    |
| VIA Technologies               | 1        | 4.35%   |
| Toshiba                        | 1        | 4.35%   |
| Solid State Storage Technology | 1        | 4.35%   |
| Silicon Motion                 | 1        | 4.35%   |
| SanDisk                        | 1        | 4.35%   |
| Phison Electronics             | 1        | 4.35%   |
| Artop Electronic               | 1        | 4.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2        | 7.41%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 2        | 7.41%   |
| AMD 500 Series Chipset SATA Controller                                        | 2        | 7.41%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1        | 3.7%    |
| Toshiba BG3 NVMe SSD Controller                                               | 1        | 3.7%    |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                | 1        | 3.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 1        | 3.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1        | 3.7%    |
| Phison E16 PCIe4 NVMe Controller                                              | 1        | 3.7%    |
| Intel Tiger Lake-LP SATA Controller                                           | 1        | 3.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1        | 3.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 1        | 3.7%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]           | 1        | 3.7%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                  | 1        | 3.7%    |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                 | 1        | 3.7%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                      | 1        | 3.7%    |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                        | 1        | 3.7%    |
| Intel 631xESB/632xESB IDE Controller                                          | 1        | 3.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1        | 3.7%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1        | 3.7%    |
| Artop Electronic AEC6712U SCSI                                                | 1        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1        | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 1        | 3.7%    |
| AMD FCH SATA Controller [IDE mode]                                            | 1        | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 9        | 39.13%  |
| IDE  | 7        | 30.43%  |
| NVMe | 6        | 26.09%  |
| SCSI | 1        | 4.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 8        | 50%     |
| AMD    | 7        | 43.75%  |
| ARM    | 1        | 6.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                       | 2        | 12.5%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                    | 1        | 6.25%   |
| Intel Xeon CPU 5150 @ 2.66GHz                          | 1        | 6.25%   |
| Intel Pentium 4 CPU 3.00GHz ("GenuineIntel" 686-class) | 1        | 6.25%   |
| Intel Core i5-7400 CPU @ 3.00GHz                       | 1        | 6.25%   |
| Intel Core i3-10100 CPU @ 3.60GHz                      | 1        | 6.25%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz                  | 1        | 6.25%   |
| Intel Core 2 CPU 6420 @ 2.13GHz                        | 1        | 6.25%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                | 1        | 6.25%   |
| ARM Cortex-A57 r1p3                                    | 1        | 6.25%   |
| AMD Ryzen 9 5950X 16-Core Processor                    | 1        | 6.25%   |
| AMD Ryzen 7 7700X 8-Core Processor                     | 1        | 6.25%   |
| AMD Ryzen 7 3700X 8-Core Processor                     | 1        | 6.25%   |
| AMD Phenom 9550 Quad-Core Processor                    | 1        | 6.25%   |
| AMD K6                                                 | 1        | 6.25%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Other             | 2        | 12.5%   |
| Intel Xeon        | 2        | 12.5%   |
| AMD Ryzen 7       | 2        | 12.5%   |
| AMD GX            | 2        | 12.5%   |
| Intel Pentium 4   | 1        | 6.25%   |
| Intel Core i5     | 1        | 6.25%   |
| Intel Core i3     | 1        | 6.25%   |
| Intel Core 2 Quad | 1        | 6.25%   |
| Intel Core 2      | 1        | 6.25%   |
| ARM Cortex        | 1        | 6.25%   |
| AMD Ryzen 9       | 1        | 6.25%   |
| AMD Phenom        | 1        | 6.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 7        | 43.75%  |
| Unknown | 3        | 18.75%  |
| 16      | 2        | 12.5%   |
| 1       | 2        | 12.5%   |
| 32      | 1        | 6.25%   |
| 2       | 1        | 6.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 11       | 68.75%  |
| Unknown | 4        | 25%     |
| 2       | 1        | 6.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 10       | 62.5%   |
| Unknown | 4        | 25%     |
| 2       | 2        | 12.5%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| Puma      | 2        | 12.5%   |
| Core      | 2        | 12.5%   |
| Unknown   | 2        | 12.5%   |
| Zen 3     | 1        | 6.25%   |
| Zen 2     | 1        | 6.25%   |
| TigerLake | 1        | 6.25%   |
| Skylake   | 1        | 6.25%   |
| Penryn    | 1        | 6.25%   |
| NetBurst  | 1        | 6.25%   |
| KabyLake  | 1        | 6.25%   |
| K10       | 1        | 6.25%   |
| Geode     | 1        | 6.25%   |
| CometLake | 1        | 6.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 5        | 33.33%  |
| Intel             | 5        | 33.33%  |
| AMD               | 4        | 26.67%  |
| ASPEED Technology | 1        | 6.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                | 2        | 13.33%  |
| Nvidia GP106 [GeForce GTX 1060 6GB]                           | 1        | 6.67%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                | 1        | 6.67%   |
| Nvidia G73 [GeForce 7300 GT]                                  | 1        | 6.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                     | 1        | 6.67%   |
| Intel HD Graphics 630                                         | 1        | 6.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                      | 1        | 6.67%   |
| Intel 82Q963/Q965 Integrated Graphics Controller              | 1        | 6.67%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller          | 1        | 6.67%   |
| ASPEED Technology ASPEED Graphics Family                      | 1        | 6.67%   |
| AMD RV770 [Radeon HD 4850]                                    | 1        | 6.67%   |
| AMD RV200 [Radeon 7500/7500 LE]                               | 1        | 6.67%   |
| AMD Raphael                                                   | 1        | 6.67%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT] | 1        | 6.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 4        | 25%     |
| Other          | 3        | 18.75%  |
| 1 x Nvidia     | 3        | 18.75%  |
| 1 x AMD        | 3        | 18.75%  |
| Intel + Nvidia | 1        | 6.25%   |
| 1 x ASPEED     | 1        | 6.25%   |
| AMD + Nvidia   | 1        | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 11       | 68.75%  |
| Unknown | 5        | 31.25%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 16       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Philips             | 2        | 22.22%  |
| ViewSonic           | 1        | 11.11%  |
| Samsung Electronics | 1        | 11.11%  |
| MSI                 | 1        | 11.11%  |
| Iiyama              | 1        | 11.11%  |
| Goldstar            | 1        | 11.11%  |
| Chimei Innolux      | 1        | 11.11%  |
| ASUSTek Computer    | 1        | 11.11%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                            | Desktops | Percent |
|------------------------------------------------------------------|----------|---------|
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch    | 1        | 11.11%  |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                | 1        | 11.11%  |
| Philips PHL 247E6 PHLC0E7 1920x1080 520x290mm 23.4-inch          | 1        | 11.11%  |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch            | 1        | 11.11%  |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                  | 1        | 11.11%  |
| Iiyama PL2530H IVM6131 1920x1080 540x300mm 24.3-inch             | 1        | 11.11%  |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch      | 1        | 11.11%  |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 310x170mm 13.9-inch | 1        | 11.11%  |
| ASUSTek Computer PA279 AUS2768 3840x2160 600x340mm 27.2-inch     | 1        | 11.11%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 6        | 66.67%  |
| 3840x2160 (4K)   | 1        | 11.11%  |
| 2560x1080        | 1        | 11.11%  |
| 1280x1024 (SXGA) | 1        | 11.11%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 2        | 22.22%  |
| 34      | 1        | 11.11%  |
| 27      | 1        | 11.11%  |
| 23      | 1        | 11.11%  |
| 21      | 1        | 11.11%  |
| 17      | 1        | 11.11%  |
| 13      | 1        | 11.11%  |
| Unknown | 1        | 11.11%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 4        | 44.44%  |
| 301-350     | 2        | 22.22%  |
| 701-800     | 1        | 11.11%  |
| 401-500     | 1        | 11.11%  |
| Unknown     | 1        | 11.11%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 7        | 77.78%  |
| 5/4   | 1        | 11.11%  |
| 21/9  | 1        | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 3        | 33.33%  |
| 81-90          | 1        | 11.11%  |
| 351-500        | 1        | 11.11%  |
| 301-350        | 1        | 11.11%  |
| 251-300        | 1        | 11.11%  |
| 141-150        | 1        | 11.11%  |
| Unknown        | 1        | 11.11%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 5        | 55.56%  |
| 161-240 | 1        | 11.11%  |
| 121-160 | 1        | 11.11%  |
| 101-120 | 1        | 11.11%  |
| Unknown | 1        | 11.11%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 9        | 56.25%  |
| 0     | 7        | 43.75%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 44.44%  |
| Realtek Semiconductor | 6        | 33.33%  |
| Qualcomm Atheros      | 1        | 5.56%   |
| Huawei Technologies   | 1        | 5.56%   |
| Edimax Technology     | 1        | 5.56%   |
| Broadcom              | 1        | 5.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3        | 16.67%  |
| Intel I210 Gigabit Network Connection                             | 3        | 16.67%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 11.11%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 5.56%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 5.56%   |
| Intel Wi-Fi 6 AX201                                               | 1        | 5.56%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 5.56%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 5.56%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller     | 1        | 5.56%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 5.56%   |
| Huawei E3372 LTE/UMTS/GSM HiLink Modem/Networkcard                | 1        | 5.56%   |
| Edimax AC600 Wireless LAN USB Adapter                             | 1        | 5.56%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 5.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 2        | 66.67%  |
| Edimax Technology | 1        | 33.33%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX201                   | 1        | 33.33%  |
| Intel Wi-Fi 6 AX200                   | 1        | 33.33%  |
| Edimax AC600 Wireless LAN USB Adapter | 1        | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 6        | 42.86%  |
| Intel                 | 6        | 42.86%  |
| Qualcomm Atheros      | 1        | 7.14%   |
| Broadcom              | 1        | 7.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3        | 21.43%  |
| Intel I210 Gigabit Network Connection                             | 3        | 21.43%  |
| Realtek RTL8125 2.5GbE Controller                                 | 2        | 14.29%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 7.14%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 7.14%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 7.14%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller     | 1        | 7.14%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 7.14%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 7.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 14       | 77.78%  |
| WiFi     | 3        | 16.67%  |
| Unknown  | 1        | 5.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 11       | 84.62%  |
| WiFi     | 2        | 15.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10       | 62.5%   |
| 2     | 3        | 18.75%  |
| 3     | 2        | 12.5%   |
| 0     | 1        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 2        | 66.67%  |
| Cambridge Silicon Radio | 1        | 33.33%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 33.33%  |
| Intel AX200 Bluetooth                               | 1        | 33.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 33.33%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 7        | 38.89%  |
| AMD      | 5        | 27.78%  |
| Nvidia   | 4        | 22.22%  |
| Logitech | 1        | 5.56%   |
| JMTek    | 1        | 5.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 10%     |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 10%     |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 5%      |
| Nvidia GA104 High Definition Audio Controller                              | 1        | 5%      |
| Logitech [G533 Wireless Headset Dongle]                                    | 1        | 5%      |
| JMTek USB PnP Audio Device                                                 | 1        | 5%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1        | 5%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1        | 5%      |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 5%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 5%      |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1        | 5%      |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 1        | 5%      |
| Intel 200 Series PCH HD Audio                                              | 1        | 5%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 1        | 5%      |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1        | 5%      |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1        | 5%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 5%      |
| AMD Family 17h/19h HD Audio Controller                                     | 1        | 5%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Kingston | 3        | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s     | 1        | 33.33%  |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s | 1        | 33.33%  |
| Kingston RAM 9905316-005.A04LF 1GB DIMM DDR2 667MT/s  | 1        | 33.33%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 2        | 66.67%  |
| DDR2 | 1        | 33.33%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 3        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 32768 | 1        | 33.33%  |
| 8192  | 1        | 33.33%  |
| 1024  | 1        | 33.33%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 2        | 66.67%  |
| 667   | 1        | 33.33%  |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Chicony Electronics | 1        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Chicony Integrated Camera | 1        | 100%    |

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
| 0     | 8        | 50%     |
| 1     | 5        | 31.25%  |
| 2     | 3        | 18.75%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 4        | 40%     |
| Communication controller | 4        | 40%     |
| Firewire controller      | 2        | 20%     |

