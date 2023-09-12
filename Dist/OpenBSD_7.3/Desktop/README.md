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

Total: 30

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| VIA Techno... | VT8623-8235                 | [3274cd095e](https://bsd-hardware.info/?probe=3274cd095e) | Aug 31, 2023 |
| MSI           | MS-7125                     | [3dfb767d80](https://bsd-hardware.info/?probe=3dfb767d80) | Aug 30, 2023 |
| ASUSTek       | P5M2-R                      | [73135bf26d](https://bsd-hardware.info/?probe=73135bf26d) | Aug 25, 2023 |
| MSI           | MS-7721                     | [a577019634](https://bsd-hardware.info/?probe=a577019634) | Aug 18, 2023 |
| MSI           | MS-7623                     | [189fb4d7cc](https://bsd-hardware.info/?probe=189fb4d7cc) | Aug 08, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [e74d459c5a](https://bsd-hardware.info/?probe=e74d459c5a) | Jul 28, 2023 |
| MSI           | G41M-P33 Combo              | [d4a26f9214](https://bsd-hardware.info/?probe=d4a26f9214) | Jul 24, 2023 |
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
| amd64 | 19       | 82.61%  |
| i386  | 3        | 13.04%  |
| arm64 | 1        | 4.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 20       | 86.96%  |
| XFCE         | 2        | 8.7%    |
| GNOME        | 1        | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 17       | 73.91%  |
| Console | 6        | 26.09%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 23       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 20       | 86.96%  |
| en_US   | 2        | 8.7%    |
| ru_RU   | 1        | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 13       | 56.52%  |
| EFI  | 10       | 43.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 23       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 15       | 65.22%  |
| GPT  | 8        | 34.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 8        | 34.78%  |
| MSI                 | 4        | 17.39%  |
| VIA Technologies    | 2        | 8.7%    |
| PC Engines          | 2        | 8.7%    |
| Gigabyte Technology | 2        | 8.7%    |
| Sony                | 1        | 4.35%   |
| Lenovo              | 1        | 4.35%   |
| Hewlett-Packard     | 1        | 4.35%   |
| Elpitech            | 1        | 4.35%   |
| Apple               | 1        | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| PC Engines APU2                    | 2        | 8.7%    |
| ASUS PRIME B650-PLUS               | 2        | 8.7%    |
| VIA VT8623-8235                    | 1        | 4.35%   |
| VIA VT82C597                       | 1        | 4.35%   |
| Sony VGC-RB41M                     | 1        | 4.35%   |
| MSI MS-7721                        | 1        | 4.35%   |
| MSI MS-7623                        | 1        | 4.35%   |
| MSI MS-7592                        | 1        | 4.35%   |
| MSI MS-7125                        | 1        | 4.35%   |
| Lenovo V14 G2 ITL 82NM             | 1        | 4.35%   |
| HP Compaq dc5700 Microtower        | 1        | 4.35%   |
| Gigabyte G41MT-S2                  | 1        | 4.35%   |
| Gigabyte B250M-Gaming 3            | 1        | 4.35%   |
| Elpitech ET101-A1                  | 1        | 4.35%   |
| ASUS TUF Gaming B550M-PLUS (WI-FI) | 1        | 4.35%   |
| ASUS TUF Gaming B550-PLUS          | 1        | 4.35%   |
| ASUS RS120-E4/PA2                  | 1        | 4.35%   |
| ASUS PRIME B460M-A                 | 1        | 4.35%   |
| ASUS P10S-I Series                 | 1        | 4.35%   |
| ASUS M3A78-EMH HDMI                | 1        | 4.35%   |
| Apple MacPro1,1                    | 1        | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 3        | 13.04%  |
| PC Engines APU2       | 2        | 8.7%    |
| ASUS TUF              | 2        | 8.7%    |
| VIA VT8623-8235       | 1        | 4.35%   |
| VIA VT82C597          | 1        | 4.35%   |
| Sony VGC-RB41M        | 1        | 4.35%   |
| MSI MS-7721           | 1        | 4.35%   |
| MSI MS-7623           | 1        | 4.35%   |
| MSI MS-7592           | 1        | 4.35%   |
| MSI MS-7125           | 1        | 4.35%   |
| Lenovo V14            | 1        | 4.35%   |
| HP Compaq             | 1        | 4.35%   |
| Gigabyte G41MT-S2     | 1        | 4.35%   |
| Gigabyte B250M-Gaming | 1        | 4.35%   |
| Elpitech ET101-A1     | 1        | 4.35%   |
| ASUS RS120-E4         | 1        | 4.35%   |
| ASUS P10S-I           | 1        | 4.35%   |
| ASUS M3A78-EMH        | 1        | 4.35%   |
| Apple MacPro1         | 1        | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2023    | 4        | 17.39%  |
| 2016    | 3        | 13.04%  |
| 2010    | 3        | 13.04%  |
| 2022    | 2        | 8.7%    |
| 2007    | 2        | 8.7%    |
| 2006    | 2        | 8.7%    |
| 2021    | 1        | 4.35%   |
| 2019    | 1        | 4.35%   |
| 2018    | 1        | 4.35%   |
| 2013    | 1        | 4.35%   |
| 2005    | 1        | 4.35%   |
| 2004    | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 23       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 21       | 91.3%   |
| Yes  | 2        | 8.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 7        | 29.17%  |
| 8.01-16.0   | 7        | 29.17%  |
| 64.01-256.0 | 4        | 16.67%  |
| 0.01-0.5    | 3        | 12.5%   |
| 16.01-24.0  | 2        | 8.33%   |
| 32.01-64.0  | 1        | 4.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 15       | 65.22%  |
| 0        | 3        | 13.04%  |
| 4.01-8.0 | 2        | 8.7%    |
| 1.01-2.0 | 2        | 8.7%    |
| 0.51-1.0 | 1        | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 13       | 56.52%  |
| 2      | 5        | 21.74%  |
| 3      | 3        | 13.04%  |
| 8      | 1        | 4.35%   |
| 6      | 1        | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 21       | 91.3%   |
| No        | 2        | 8.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 86.96%  |
| Yes       | 3        | 13.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 86.96%  |
| Yes       | 3        | 13.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 10       | 43.48%  |
| Germany | 3        | 13.04%  |
| USA     | 2        | 8.7%    |
| Mexico  | 2        | 8.7%    |
| Italy   | 2        | 8.7%    |
| Brazil  | 2        | 8.7%    |
| Spain   | 1        | 4.35%   |
| Romania | 1        | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| St Petersburg    | 4        | 17.39%  |
| Puebla City      | 2        | 8.7%    |
| Nuremberg        | 2        | 8.7%    |
| Moscow           | 2        | 8.7%    |
| Milan            | 2        | 8.7%    |
| Cherepovets      | 2        | 8.7%    |
| Blumenau         | 2        | 8.7%    |
| San Francisco    | 1        | 4.35%   |
| Podolsk          | 1        | 4.35%   |
| Oltenita         | 1        | 4.35%   |
| Monheim am Rhein | 1        | 4.35%   |
| Krasnodar        | 1        | 4.35%   |
| Barcelona        | 1        | 4.35%   |
| Austin           | 1        | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| NVMe                | 7        | 10     | 18.92%  |
| Samsung Electronics | 5        | 10     | 13.51%  |
| WDC                 | 3        | 3      | 8.11%   |
| Seagate             | 3        | 4      | 8.11%   |
| Intel               | 3        | 3      | 8.11%   |
| Hitachi             | 3        | 3      | 8.11%   |
| SanDisk             | 2        | 4      | 5.41%   |
| OPENBSD             | 2        | 2      | 5.41%   |
| Kingston            | 2        | 2      | 5.41%   |
| Crucial             | 2        | 3      | 5.41%   |
| HGST                | 1        | 1      | 2.7%    |
| Fujitsu             | 1        | 1      | 2.7%    |
| Apacer              | 1        | 1      | 2.7%    |
| AMD                 | 1        | 1      | 2.7%    |
| A-DATA Technology   | 1        | 1      | 2.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel SSDSC2BW480H6 480GB     | 3        | 7.5%    |
| NVMe Samsung SSD 980 500GB    | 2        | 5%      |
| WDC WD5000AZLX-00K2TA0 500GB  | 1        | 2.5%    |
| WDC WD3201ABYS-01B9A0 320GB   | 1        | 2.5%    |
| WDC WD20PURX-64P6ZY0 2TB      | 1        | 2.5%    |
| Seagate ST3500414CS 500GB     | 1        | 2.5%    |
| Seagate ST3250824AS P 250GB   | 1        | 2.5%    |
| Seagate ST3250318AS 250GB     | 1        | 2.5%    |
| Seagate ST320011A 20GB        | 1        | 2.5%    |
| SanDisk SSD PLUS 240GB        | 1        | 2.5%    |
| SanDisk SSD PLUS 120GB        | 1        | 2.5%    |
| SanDisk Cruzer Blade 64GB     | 1        | 2.5%    |
| Samsung SSD 870 QVO 2TB       | 1        | 2.5%    |
| Samsung SSD 870 EVO 500GB     | 1        | 2.5%    |
| Samsung SSD 840 EVO 250GB     | 1        | 2.5%    |
| Samsung HD161HJ 160GB         | 1        | 2.5%    |
| Samsung Flash Drive FIT 32GB  | 1        | 2.5%    |
| OPENBSD SR RAID 5 9.9TB       | 1        | 2.5%    |
| OPENBSD SR RAID 1 2TB         | 1        | 2.5%    |
| NVMe WDBRPG5000ANC-WR 500GB   | 1        | 2.5%    |
| NVMe TOSHIBA-RC100 240GB      | 1        | 2.5%    |
| NVMe SSSTC CL1-4D256 256GB    | 1        | 2.5%    |
| NVMe Samsung SSD 990 2TB      | 1        | 2.5%    |
| NVMe Sabrent Rocket 4 500GB   | 1        | 2.5%    |
| NVMe Asgard AN1TNVMe- 1TB     | 1        | 2.5%    |
| Kingston SMS200S330G 32GB     | 1        | 2.5%    |
| Kingston SA400S37480G 480GB   | 1        | 2.5%    |
| Hitachi HUA723020ALA640 2TB   | 1        | 2.5%    |
| Hitachi HDS722516VLAT80 164GB | 1        | 2.5%    |
| Hitachi HCS5C1032CLA382 320GB | 1        | 2.5%    |
| HGST HUS724020ALA640 2TB      | 1        | 2.5%    |
| Fujitsu MHV2080BH 80GB        | 1        | 2.5%    |
| Crucial CT500MX500SSD1 500GB  | 1        | 2.5%    |
| Crucial CT500BX500SSD1 500GB  | 1        | 2.5%    |
| Apacer AST280 120GB           | 1        | 2.5%    |
| AMD R5SL120G 120GB            | 1        | 2.5%    |
| A-DATA SP550 240GB            | 1        | 2.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| NVMe                | 4        | 7      | 21.05%  |
| WDC                 | 3        | 3      | 15.79%  |
| Seagate             | 3        | 4      | 15.79%  |
| Hitachi             | 3        | 3      | 15.79%  |
| Samsung Electronics | 2        | 2      | 10.53%  |
| OPENBSD             | 2        | 2      | 10.53%  |
| HGST                | 1        | 1      | 5.26%   |
| Fujitsu             | 1        | 1      | 5.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 8      | 16.67%  |
| NVMe                | 3        | 3      | 16.67%  |
| Intel               | 3        | 3      | 16.67%  |
| SanDisk             | 2        | 4      | 11.11%  |
| Kingston            | 2        | 2      | 11.11%  |
| Crucial             | 2        | 3      | 11.11%  |
| Apacer              | 1        | 1      | 5.56%   |
| AMD                 | 1        | 1      | 5.56%   |
| A-DATA Technology   | 1        | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 16       | 26     | 55.17%  |
| HDD  | 13       | 23     | 44.83%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 22       | 49     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 35     | 80.77%  |
| 1.01-2.0   | 4        | 13     | 15.38%  |
| 4.01-10.0  | 1        | 1      | 3.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 7        | 29.17%  |
| 101-250        | 6        | 25%     |
| 21-50          | 3        | 12.5%   |
| More than 3000 | 2        | 8.33%   |
| 1-20           | 2        | 8.33%   |
| 501-1000       | 2        | 8.33%   |
| 51-100         | 2        | 8.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 16       | 69.57%  |
| 21-50          | 2        | 8.7%    |
| More than 3000 | 1        | 4.35%   |
| 251-500        | 1        | 4.35%   |
| 2001-3000      | 1        | 4.35%   |
| 101-250        | 1        | 4.35%   |
| 51-100         | 1        | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Intel SSDSC2BW480H6 480GB             | 3        | 3      | 33.33%  |
| SanDisk SSD PLUS 240GB                | 1        | 1      | 11.11%  |
| Samsung Electronics SSD 870 EVO 500GB | 1        | 1      | 11.11%  |
| Samsung Electronics SSD 840 EVO 250GB | 1        | 1      | 11.11%  |
| Samsung Electronics HD161HJ 160GB     | 1        | 1      | 11.11%  |
| Hitachi HDS722516VLAT80 164GB         | 1        | 1      | 11.11%  |
| A-DATA Technology SP550 240GB         | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 33.33%  |
| Intel               | 3        | 3      | 33.33%  |
| SanDisk             | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 1      | 11.11%  |
| A-DATA Technology   | 1        | 1      | 11.11%  |

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
| SSD  | 7        | 7      | 77.78%  |
| HDD  | 2        | 2      | 22.22%  |

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
| Works    | 14       | 28     | 46.67%  |
| Malfunc  | 9        | 9      | 30%     |
| Detected | 7        | 12     | 23.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 10       | 32.26%  |
| AMD                            | 9        | 29.03%  |
| Samsung Electronics            | 3        | 9.68%   |
| VIA Technologies               | 2        | 6.45%   |
| Toshiba                        | 1        | 3.23%   |
| Solid State Storage Technology | 1        | 3.23%   |
| Silicon Motion                 | 1        | 3.23%   |
| SanDisk                        | 1        | 3.23%   |
| Phison Electronics             | 1        | 3.23%   |
| Nvidia                         | 1        | 3.23%   |
| Artop Electronic               | 1        | 3.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 4        | 10.26%  |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 2        | 5.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2        | 5.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                             | 2        | 5.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 2        | 5.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 2        | 5.13%   |
| AMD 500 Series Chipset SATA Controller                                        | 2        | 5.13%   |
| Toshiba BG3 NVMe SSD Controller                                               | 1        | 2.56%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                | 1        | 2.56%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 1        | 2.56%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1        | 2.56%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                   | 1        | 2.56%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1        | 2.56%   |
| Nvidia CK804 Serial ATA Controller                                            | 1        | 2.56%   |
| Nvidia CK804 IDE                                                              | 1        | 2.56%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1        | 2.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1        | 2.56%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1        | 2.56%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]           | 1        | 2.56%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                  | 1        | 2.56%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                 | 1        | 2.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                      | 1        | 2.56%   |
| Intel 631xESB/632xESB/3100 Chipset SATA IDE Controller                        | 1        | 2.56%   |
| Intel 631xESB/632xESB IDE Controller                                          | 1        | 2.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 1        | 2.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                              | 1        | 2.56%   |
| Artop Electronic AEC6712U SCSI                                                | 1        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 1        | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1        | 2.56%   |
| AMD FCH SATA Controller [IDE mode]                                            | 1        | 2.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 13       | 39.39%  |
| IDE  | 12       | 36.36%  |
| NVMe | 7        | 21.21%  |
| SCSI | 1        | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 11       | 47.83%  |
| Intel  | 10       | 43.48%  |
| VIA    | 1        | 4.35%   |
| ARM    | 1        | 4.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz                  | 2        | 8.7%    |
| AMD GX-412TC SOC                                       | 2        | 8.7%    |
| VIA C3                                                 | 1        | 4.35%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                    | 1        | 4.35%   |
| Intel Xeon CPU 5150 @ 2.66GHz                          | 1        | 4.35%   |
| Intel Pentium 4 CPU 3.00GHz ("GenuineIntel" 686-class) | 1        | 4.35%   |
| Intel Core i5-7400 CPU @ 3.00GHz                       | 1        | 4.35%   |
| Intel Core i3-10100 CPU @ 3.60GHz                      | 1        | 4.35%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz                  | 1        | 4.35%   |
| Intel Core 2 CPU 6420 @ 2.13GHz                        | 1        | 4.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz                | 1        | 4.35%   |
| ARM Cortex-A57 r1p3                                    | 1        | 4.35%   |
| AMD Ryzen 9 7950X 16-Core Processor                    | 1        | 4.35%   |
| AMD Ryzen 9 5950X 16-Core Processor                    | 1        | 4.35%   |
| AMD Ryzen 7 7700X 8-Core Processor                     | 1        | 4.35%   |
| AMD Ryzen 7 3700X 8-Core Processor                     | 1        | 4.35%   |
| AMD Phenom 9550 Quad-Core Processor                    | 1        | 4.35%   |
| AMD K6                                                 | 1        | 4.35%   |
| AMD Athlon X4 870K Quad Core Processor                 | 1        | 4.35%   |
| AMD Athlon II X2 240 Processor                         | 1        | 4.35%   |
| AMD Athlon 64 Processor 3200+                          | 1        | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Other             | 3        | 13.04%  |
| Intel Core 2 Quad | 3        | 13.04%  |
| Intel Xeon        | 2        | 8.7%    |
| AMD Ryzen 9       | 2        | 8.7%    |
| AMD Ryzen 7       | 2        | 8.7%    |
| AMD GX            | 2        | 8.7%    |
| Intel Pentium 4   | 1        | 4.35%   |
| Intel Core i5     | 1        | 4.35%   |
| Intel Core i3     | 1        | 4.35%   |
| Intel Core 2      | 1        | 4.35%   |
| ARM Cortex        | 1        | 4.35%   |
| AMD Phenom        | 1        | 4.35%   |
| AMD Athlon X4     | 1        | 4.35%   |
| AMD Athlon II X2  | 1        | 4.35%   |
| AMD Athlon 64     | 1        | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 9        | 39.13%  |
| Unknown | 5        | 21.74%  |
| 1       | 3        | 13.04%  |
| 32      | 2        | 8.7%    |
| 16      | 2        | 8.7%    |
| 2       | 2        | 8.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 18       | 78.26%  |
| Unknown | 4        | 17.39%  |
| 2       | 1        | 4.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 14       | 60.87%  |
| Unknown | 7        | 30.43%  |
| 2       | 2        | 8.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Core        | 4        | 17.39%  |
| Unknown     | 4        | 17.39%  |
| Puma        | 2        | 8.7%    |
| K10         | 2        | 8.7%    |
| Zen 3       | 1        | 4.35%   |
| Zen 2       | 1        | 4.35%   |
| TigerLake   | 1        | 4.35%   |
| Steamroller | 1        | 4.35%   |
| Skylake     | 1        | 4.35%   |
| Penryn      | 1        | 4.35%   |
| NetBurst    | 1        | 4.35%   |
| KabyLake    | 1        | 4.35%   |
| K8 Hammer   | 1        | 4.35%   |
| Geode       | 1        | 4.35%   |
| CometLake   | 1        | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 8        | 34.78%  |
| AMD               | 7        | 30.43%  |
| Intel             | 6        | 26.09%  |
| VIA Technologies  | 1        | 4.35%   |
| ASPEED Technology | 1        | 4.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                                         | 2        | 8.7%    |
| AMD Raphael                                                            | 2        | 8.7%    |
| VIA Technologies VT8623 [Apollo CLE266] integrated CastleRock graphics | 1        | 4.35%   |
| Nvidia GT200 [GeForce GTX 260]                                         | 1        | 4.35%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                    | 1        | 4.35%   |
| Nvidia GA104GL [RTX A4000]                                             | 1        | 4.35%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                         | 1        | 4.35%   |
| Nvidia G73 [GeForce 7300 GT]                                           | 1        | 4.35%   |
| Nvidia G72 [GeForce 7300 LE]                                           | 1        | 4.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                              | 1        | 4.35%   |
| Intel HD Graphics 630                                                  | 1        | 4.35%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                               | 1        | 4.35%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                       | 1        | 4.35%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                   | 1        | 4.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                  | 1        | 4.35%   |
| ASPEED Technology ASPEED Graphics Family                               | 1        | 4.35%   |
| AMD RV770 [Radeon HD 4850]                                             | 1        | 4.35%   |
| AMD RV200 [Radeon 7500/7500 LE]                                        | 1        | 4.35%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]          | 1        | 4.35%   |
| AMD ES1000                                                             | 1        | 4.35%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                         | 1        | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 5        | 21.74%  |
| 1 x Intel      | 5        | 21.74%  |
| 1 x AMD        | 5        | 21.74%  |
| Other          | 3        | 13.04%  |
| AMD + Nvidia   | 2        | 8.7%    |
| 1 x VIA        | 1        | 4.35%   |
| Intel + Nvidia | 1        | 4.35%   |
| 1 x ASPEED     | 1        | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 18       | 78.26%  |
| Unknown | 5        | 21.74%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 23       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Philips             | 4        | 26.67%  |
| Samsung Electronics | 3        | 20%     |
| ViewSonic           | 2        | 13.33%  |
| MSI                 | 1        | 6.67%   |
| Iiyama              | 1        | 6.67%   |
| Goldstar            | 1        | 6.67%   |
| Chimei Innolux      | 1        | 6.67%   |
| ASUSTek Computer    | 1        | 6.67%   |
| AOC                 | 1        | 6.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch | 2        | 13.33%  |
| Philips 170S PHL0839 1280x1024 340x270mm 17.1-inch                   | 2        | 13.33%  |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch        | 1        | 6.67%   |
| ViewSonic VA2418-FHD VSCD739 1920x1080 530x300mm 24.0-inch           | 1        | 6.67%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                    | 1        | 6.67%   |
| Philips PHL 247E6 PHLC0E7 1920x1080 520x290mm 23.4-inch              | 1        | 6.67%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                | 1        | 6.67%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                      | 1        | 6.67%   |
| Iiyama PL2530H IVM6131 1920x1080 540x300mm 24.3-inch                 | 1        | 6.67%   |
| Goldstar LG ULTRAWIDE GSM76F9 2560x1080 800x340mm 34.2-inch          | 1        | 6.67%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 310x170mm 13.9-inch     | 1        | 6.67%   |
| ASUSTek Computer PA279 AUS2768 3840x2160 600x340mm 27.2-inch         | 1        | 6.67%   |
| AOC 27V2G5 AOC2702 1920x1080 600x340mm 27.2-inch                     | 1        | 6.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 8        | 53.33%  |
| 1280x1024 (SXGA) | 5        | 33.33%  |
| 3840x2160 (4K)   | 1        | 6.67%   |
| 2560x1080        | 1        | 6.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 17      | 5        | 33.33%  |
| 24      | 3        | 20%     |
| 27      | 2        | 13.33%  |
| 34      | 1        | 6.67%   |
| 23      | 1        | 6.67%   |
| 21      | 1        | 6.67%   |
| 13      | 1        | 6.67%   |
| Unknown | 1        | 6.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 40%     |
| 301-350     | 6        | 40%     |
| 701-800     | 1        | 6.67%   |
| 401-500     | 1        | 6.67%   |
| Unknown     | 1        | 6.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 9        | 60%     |
| 5/4   | 5        | 33.33%  |
| 21/9  | 1        | 6.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 5        | 33.33%  |
| 201-250        | 4        | 26.67%  |
| 301-350        | 2        | 13.33%  |
| 81-90          | 1        | 6.67%   |
| 351-500        | 1        | 6.67%   |
| 251-300        | 1        | 6.67%   |
| Unknown        | 1        | 6.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 11       | 73.33%  |
| 161-240 | 1        | 6.67%   |
| 121-160 | 1        | 6.67%   |
| 101-120 | 1        | 6.67%   |
| Unknown | 1        | 6.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 65.22%  |
| 0     | 8        | 34.78%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 9        | 36%     |
| Intel                 | 8        | 32%     |
| Qualcomm Atheros      | 2        | 8%      |
| Broadcom              | 2        | 8%      |
| VIA Technologies      | 1        | 4%      |
| Huawei Technologies   | 1        | 4%      |
| Edimax Technology     | 1        | 4%      |
| D-Link System         | 1        | 4%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 16%     |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 12%     |
| Intel I210 Gigabit Network Connection                             | 3        | 12%     |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 4%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 4%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4%      |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 4%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 4%      |
| Intel Wi-Fi 6 AX201                                               | 1        | 4%      |
| Intel Wi-Fi 6 AX200                                               | 1        | 4%      |
| Intel Ethernet Connection (2) I219-V                              | 1        | 4%      |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller     | 1        | 4%      |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 4%      |
| Huawei E3372 LTE/UMTS/GSM HiLink Modem/Networkcard                | 1        | 4%      |
| Edimax AC600 Wireless LAN USB Adapter                             | 1        | 4%      |
| D-Link System DGE-560T PCI Express Gigabit Ethernet Adapter       | 1        | 4%      |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 4%      |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 4%      |

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
| Realtek Semiconductor | 9        | 42.86%  |
| Intel                 | 6        | 28.57%  |
| Qualcomm Atheros      | 2        | 9.52%   |
| Broadcom              | 2        | 9.52%   |
| VIA Technologies      | 1        | 4.76%   |
| D-Link System         | 1        | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4        | 19.05%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 14.29%  |
| Intel I210 Gigabit Network Connection                             | 3        | 14.29%  |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1        | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 4.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 4.76%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 4.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 4.76%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 4.76%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller     | 1        | 4.76%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 4.76%   |
| D-Link System DGE-560T PCI Express Gigabit Ethernet Adapter       | 1        | 4.76%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 4.76%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 1        | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 21       | 84%     |
| WiFi     | 3        | 12%     |
| Unknown  | 1        | 4%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 17       | 89.47%  |
| WiFi     | 2        | 10.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 16       | 69.57%  |
| 2     | 4        | 17.39%  |
| 3     | 2        | 8.7%    |
| 0     | 1        | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 23       | 100%    |

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


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 8        | 32%     |
| AMD              | 8        | 32%     |
| Nvidia           | 6        | 24%     |
| VIA Technologies | 1        | 4%      |
| Logitech         | 1        | 4%      |
| JMTek            | 1        | 4%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 6.9%    |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 6.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 6.9%    |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 6.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 2        | 6.9%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2        | 6.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 2        | 6.9%    |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1        | 3.45%   |
| Nvidia GP106 High Definition Audio Controller                              | 1        | 3.45%   |
| Nvidia CK804 AC'97 Audio Controller                                        | 1        | 3.45%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1        | 3.45%   |
| JMTek USB PnP Audio Device                                                 | 1        | 3.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1        | 3.45%   |
| Intel Comet Lake PCH-V cAVS                                                | 1        | 3.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1        | 3.45%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 1        | 3.45%   |
| Intel 631xESB/632xESB High Definition Audio Controller                     | 1        | 3.45%   |
| Intel 200 Series PCH HD Audio                                              | 1        | 3.45%   |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                 | 1        | 3.45%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 1        | 3.45%   |
| AMD FCH Azalia Controller                                                  | 1        | 3.45%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 1        | 3.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Kingston | 3        | 42.86%  |
| Unknown  | 3        | 42.86%  |
| Unknown  | 1        | 14.29%  |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown                                               | 3        | 42.86%  |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s              | 1        | 14.29%  |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s     | 1        | 14.29%  |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s | 1        | 14.29%  |
| Kingston RAM 9905316-005.A04LF 1GB DIMM DDR2 667MT/s  | 1        | 14.29%  |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 2        | 28.57%  |
| DDR2    | 2        | 28.57%  |
| Unknown | 2        | 28.57%  |
| SDRAM   | 1        | 14.29%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 7        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 2        | 28.57%  |
| 1024  | 2        | 28.57%  |
| 32768 | 1        | 14.29%  |
| 8192  | 1        | 14.29%  |
| 512   | 1        | 14.29%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2400    | 2        | 28.57%  |
| 667     | 2        | 28.57%  |
| Unknown | 2        | 28.57%  |
| 800     | 1        | 14.29%  |

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


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Generalplus Technology | 1        | 50%     |
| Chicony Electronics    | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Generalplus HD Webcam     | 1        | 50%     |
| Chicony Integrated Camera | 1        | 50%     |

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
| 0     | 13       | 56.52%  |
| 1     | 7        | 30.43%  |
| 2     | 3        | 13.04%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 5        | 41.67%  |
| Communication controller | 4        | 33.33%  |
| Firewire controller      | 3        | 25%     |

