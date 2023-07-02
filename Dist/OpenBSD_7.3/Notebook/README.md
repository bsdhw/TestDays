OpenBSD 7.3 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

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

Total: 35

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Panasonic     | CFSX4-1                     | [ff83a965d2](https://bsd-hardware.info/?probe=ff83a965d2) | Jun 15, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [01df487b47](https://bsd-hardware.info/?probe=01df487b47) | Jun 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [9f18b1b304](https://bsd-hardware.info/?probe=9f18b1b304) | Jun 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [85c18dbbb5](https://bsd-hardware.info/?probe=85c18dbbb5) | Jun 06, 2023 |
| Toshiba       | NB250                       | [62c572e895](https://bsd-hardware.info/?probe=62c572e895) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | [df93ad7e83](https://bsd-hardware.info/?probe=df93ad7e83) | May 27, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [580c52399f](https://bsd-hardware.info/?probe=580c52399f) | May 25, 2023 |
| Lenovo        | ThinkPad X140e 20BMS03E0... | [84e3ac62d5](https://bsd-hardware.info/?probe=84e3ac62d5) | May 23, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| Lenovo        | ThinkPad X201 3323BBG       | [7b529b0888](https://bsd-hardware.info/?probe=7b529b0888) | May 17, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| ASUSTek       | 1000HE                      | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [d2bd7a8764](https://bsd-hardware.info/?probe=d2bd7a8764) | May 07, 2023 |
| Lenovo        | ThinkPad T500 205663G       | [d706da9400](https://bsd-hardware.info/?probe=d706da9400) | May 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8A00KC... | [44ddee0eec](https://bsd-hardware.info/?probe=44ddee0eec) | May 06, 2023 |
| Matsushita... | CF-51RCVDNLM                | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| Panasonic     | CF-53AAGHYDM                | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| HP            | Pavilion Notebook           | [247810c987](https://bsd-hardware.info/?probe=247810c987) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | [243a9c2f22](https://bsd-hardware.info/?probe=243a9c2f22) | Apr 22, 2023 |
| Lenovo        | G570 20079                  | [0ebba481d1](https://bsd-hardware.info/?probe=0ebba481d1) | Apr 14, 2023 |
| Lenovo        | ThinkPad T440s 20ARA07PL... | [04ddab3620](https://bsd-hardware.info/?probe=04ddab3620) | Apr 14, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| Lenovo        | ThinkPad T450s 20BW001KL... | [4f6a7e2739](https://bsd-hardware.info/?probe=4f6a7e2739) | Apr 02, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 25        | 80.65%  |
| i386  | 5         | 16.13%  |
| arm64 | 1         | 3.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 26        | 83.87%  |
| GNOME        | 4         | 12.9%   |
| MATE         | 1         | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 28        | 90.32%  |
| Console | 3         | 9.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 31        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 87.1%   |
| en_US   | 2         | 6.45%   |
| es_ES   | 1         | 3.23%   |
| C       | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 16        | 51.61%  |
| EFI  | 15        | 48.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ffs  | 31        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| MBR  | 16        | 51.61%  |
| GPT  | 15        | 48.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 20        | 64.52%  |
| Panasonic                      | 3         | 9.68%   |
| Matsushita Electric Industrial | 2         | 6.45%   |
| Toshiba                        | 1         | 3.23%   |
| Tactus                         | 1         | 3.23%   |
| Hewlett-Packard                | 1         | 3.23%   |
| Fujitsu                        | 1         | 3.23%   |
| ASUSTek Computer               | 1         | 3.23%   |
| Unknown                        | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba NB250                               | 1         | 3.23%   |
| Tactus GeoFlex 110                          | 1         | 3.23%   |
| Panasonic CFSX4-1                           | 1         | 3.23%   |
| Panasonic CF-53AAGHYDM                      | 1         | 3.23%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 3.23%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 3.23%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 3.23%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 3.23%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 3.23%   |
| Lenovo ThinkPad X230 2325T4T                | 1         | 3.23%   |
| Lenovo ThinkPad X230 23257EP                | 1         | 3.23%   |
| Lenovo ThinkPad X220 429043U                | 1         | 3.23%   |
| Lenovo ThinkPad X201 3323BBG                | 1         | 3.23%   |
| Lenovo ThinkPad X140e 20BMS03E00            | 1         | 3.23%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 3.23%   |
| Lenovo ThinkPad T61 7659AS5                 | 1         | 3.23%   |
| Lenovo ThinkPad T500 205663G                | 1         | 3.23%   |
| Lenovo ThinkPad T480s 20L8A00KCL            | 1         | 3.23%   |
| Lenovo ThinkPad T450s 20BW001KLM            | 1         | 3.23%   |
| Lenovo ThinkPad T440s 20ARA07PLM            | 1         | 3.23%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 3.23%   |
| Lenovo ThinkPad T430 2344BZU                | 1         | 3.23%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 3.23%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 3.23%   |
| Lenovo ThinkPad T14 Gen 1 20UES5NW00        | 1         | 3.23%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW        | 1         | 3.23%   |
| Lenovo G570 20079                           | 1         | 3.23%   |
| HP Pavilion Notebook                        | 1         | 3.23%   |
| Fujitsu LIFEBOOK E752                       | 1         | 3.23%   |
| ASUS 1000HE                                 | 1         | 3.23%   |
| Unknown                                     | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 19        | 61.29%  |
| Toshiba NB250                               | 1         | 3.23%   |
| Tactus GeoFlex                              | 1         | 3.23%   |
| Panasonic CFSX4-1                           | 1         | 3.23%   |
| Panasonic CF-53AAGHYDM                      | 1         | 3.23%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 3.23%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 3.23%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 3.23%   |
| Lenovo G570                                 | 1         | 3.23%   |
| HP Pavilion                                 | 1         | 3.23%   |
| Fujitsu LIFEBOOK                            | 1         | 3.23%   |
| ASUS 1000HE                                 | 1         | 3.23%   |
| Unknown                                     | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 5         | 16.13%  |
| 2010    | 4         | 12.9%   |
| 2015    | 3         | 9.68%   |
| 2012    | 3         | 9.68%   |
| 2019    | 2         | 6.45%   |
| 2018    | 2         | 6.45%   |
| 2013    | 2         | 6.45%   |
| 2022    | 1         | 3.23%   |
| 2021    | 1         | 3.23%   |
| 2020    | 1         | 3.23%   |
| 2017    | 1         | 3.23%   |
| 2016    | 1         | 3.23%   |
| 2009    | 1         | 3.23%   |
| 2007    | 1         | 3.23%   |
| 2006    | 1         | 3.23%   |
| 2002    | 1         | 3.23%   |
| Unknown | 1         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 31        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 30        | 96.77%  |
| Yes  | 1         | 3.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 8         | 25.81%  |
| 4.01-8.0   | 7         | 22.58%  |
| 3.01-4.0   | 6         | 19.35%  |
| 16.01-24.0 | 3         | 9.68%   |
| 2.01-3.0   | 2         | 6.45%   |
| 0.51-1.0   | 2         | 6.45%   |
| 32.01-64.0 | 1         | 3.23%   |
| 24.01-32.0 | 1         | 3.23%   |
| 1.01-2.0   | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 26        | 83.87%  |
| 0        | 3         | 9.68%   |
| 1.01-2.0 | 1         | 3.23%   |
| 0.51-1.0 | 1         | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 61.29%  |
| 2      | 6         | 19.35%  |
| 3      | 4         | 12.9%   |
| 0      | 2         | 6.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 31        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 28        | 90.32%  |
| No        | 3         | 9.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 93.55%  |
| No        | 2         | 6.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 70.97%  |
| No        | 9         | 29.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Canada   | 14        | 45.16%  |
| USA      | 3         | 9.68%   |
| Uruguay  | 3         | 9.68%   |
| Brazil   | 3         | 9.68%   |
| Ukraine  | 1         | 3.23%   |
| Spain    | 1         | 3.23%   |
| Russia   | 1         | 3.23%   |
| Romania  | 1         | 3.23%   |
| Poland   | 1         | 3.23%   |
| Mexico   | 1         | 3.23%   |
| Germany  | 1         | 3.23%   |
| Colombia | 1         | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Saint-Laurent | 14        | 45.16%  |
| Sun Prairie   | 3         | 9.68%   |
| Montevideo    | 3         | 9.68%   |
| Blumenau      | 3         | 9.68%   |
| Swilcza       | 1         | 3.23%   |
| St Petersburg | 1         | 3.23%   |
| Puebla City   | 1         | 3.23%   |
| Navalcarnero  | 1         | 3.23%   |
| Montería     | 1         | 3.23%   |
| Lübeck       | 1         | 3.23%   |
| Brovary       | 1         | 3.23%   |
| Brasov        | 1         | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 17.65%  |
| NVMe                | 5         | 6      | 14.71%  |
| Samsung Electronics | 4         | 4      | 11.76%  |
| SanDisk             | 3         | 3      | 8.82%   |
| Kingston            | 3         | 3      | 8.82%   |
| Hitachi             | 3         | 3      | 8.82%   |
| Seagate             | 2         | 2      | 5.88%   |
| Verbatim            | 1         | 1      | 2.94%   |
| Union Memory        | 1         | 1      | 2.94%   |
| SMI                 | 1         | 1      | 2.94%   |
| PNY                 | 1         | 2      | 2.94%   |
| Intenso             | 1         | 1      | 2.94%   |
| Crucial             | 1         | 1      | 2.94%   |
| Apacer              | 1         | 1      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| SanDisk Extreme SSD 500GB           | 2         | 5.71%   |
| NVMe SAMSUNG MZVLW256 256GB         | 2         | 5.71%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 2.86%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 2.86%   |
| WDC WD7500BPKT-00PK4T0 752GB        | 1         | 2.86%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 2.86%   |
| WDC WD3200BEVE-00A0HT0 320GB        | 1         | 2.86%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 2.86%   |
| Verbatim STORE N GO 64GB            | 1         | 2.86%   |
| Union Memory RTOTJ128VGD2EYX 128GB  | 1         | 2.86%   |
| SMI USB DISK 18302PB                | 1         | 2.86%   |
| Seagate ST9160821A 160GB            | 1         | 2.86%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 2.86%   |
| SanDisk SSD PLUS 120GB              | 1         | 2.86%   |
| Samsung SSD 860 EVO M.2 1TB         | 1         | 2.86%   |
| Samsung SSD 850 EVO 500GB           | 1         | 2.86%   |
| Samsung MZ7TD128HAFV-000L1 128GB    | 1         | 2.86%   |
| Samsung MZ7PC128HAFU-000L1 128GB    | 1         | 2.86%   |
| PNY CS900 1TB SSD                   | 1         | 2.86%   |
| NVMe Sabrent SB-1342- 1TB           | 1         | 2.86%   |
| NVMe KINGSTON SNVS200 2TB           | 1         | 2.86%   |
| NVMe KINGSTON SNV2S20 2TB           | 1         | 2.86%   |
| NVMe APPLE SSD AP0512 500GB         | 1         | 2.86%   |
| Kingston SA400S37240G 240GB         | 1         | 2.86%   |
| Kingston SA400S37120G 120GB         | 1         | 2.86%   |
| Kingston SA400M8240G 240GB          | 1         | 2.86%   |
| Intenso SSD 256GB                   | 1         | 2.86%   |
| Hitachi HTS723232A7A364 320GB       | 1         | 2.86%   |
| Hitachi HTS723225A7A365 OPAL 250GB  | 1         | 2.86%   |
| Hitachi HTS545016B9A300 160GB       | 1         | 2.86%   |
| Crucial CT480BX500SSD1 480GB        | 1         | 2.86%   |
| Apacer AS340 120GB                  | 1         | 2.86%   |
| A-DATA SP550 480GB                  | 1         | 2.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 6         | 6      | 35.29%  |
| NVMe     | 4         | 5      | 23.53%  |
| Hitachi  | 3         | 3      | 17.65%  |
| Seagate  | 2         | 2      | 11.76%  |
| Verbatim | 1         | 1      | 5.88%   |
| SMI      | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 23.53%  |
| SanDisk             | 3         | 3      | 17.65%  |
| Kingston            | 3         | 3      | 17.65%  |
| Union Memory        | 1         | 1      | 5.88%   |
| PNY                 | 1         | 2      | 5.88%   |
| NVMe                | 1         | 1      | 5.88%   |
| Intenso             | 1         | 1      | 5.88%   |
| Crucial             | 1         | 1      | 5.88%   |
| Apacer              | 1         | 1      | 5.88%   |
| A-DATA Technology   | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 16        | 18     | 50%     |
| HDD  | 16        | 18     | 50%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 29        | 36     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 22        | 25     | 70.97%  |
| 0.51-1.0        | 6         | 7      | 19.35%  |
| 1.01-2.0        | 2         | 3      | 6.45%   |
| More than 100.0 | 1         | 1      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 21-50      | 11        | 35.48%  |
| 101-250    | 11        | 35.48%  |
| 51-100     | 4         | 12.9%   |
| 251-500    | 2         | 6.45%   |
| 1001-2000  | 2         | 6.45%   |
| 1-20       | 1         | 3.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 26        | 83.87%  |
| 21-50   | 4         | 12.9%   |
| 51-100  | 1         | 3.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| A-DATA Technology SP550 480GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| A-DATA Technology | 1         | 1      | 100%    |

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
| SSD  | 1         | 1      | 100%    |

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
| Works    | 23        | 26     | 76.67%  |
| Detected | 6         | 9      | 20%     |
| Malfunc  | 1         | 1      | 3.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 24        | 80%     |
| Samsung Electronics         | 2         | 6.67%   |
| Kingston Technology Company | 2         | 6.67%   |
| Phison Electronics          | 1         | 3.33%   |
| AMD                         | 1         | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 5         | 16.13%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 9.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 9.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 9.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 6.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 6.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 6.45%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 3.23%   |
| Kingston Company unknown                                                               | 1         | 3.23%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                     | 1         | 3.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 3.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 3.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 3.23%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 3.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 3.23%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 3.23%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 72.41%  |
| NVMe | 4         | 13.79%  |
| IDE  | 4         | 13.79%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 27        | 87.1%   |
| AMD     | 3         | 9.68%   |
| Unknown | 1         | 3.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz                               | 4         | 12.9%   |
| Intel Core i5-6300U CPU @ 2.40GHz                               | 3         | 9.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz                               | 3         | 9.68%   |
| Intel Core i5-5300U CPU @ 2.30GHz                               | 2         | 6.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                               | 2         | 6.45%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                              | 1         | 3.23%   |
| Intel Genuine CPU T2300 @ 1.66GHz                               | 1         | 3.23%   |
| Intel Core i7-8650U CPU @ 1.90GHz                               | 1         | 3.23%   |
| Intel Core i7-3520M CPU @ 2.90GHz                               | 1         | 3.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz                               | 1         | 3.23%   |
| Intel Core i5-4300U CPU @ 1.90GHz                               | 1         | 3.23%   |
| Intel Core i5-2410M CPU @ 2.30GHz                               | 1         | 3.23%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                               | 1         | 3.23%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                            | 1         | 3.23%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz ("GenuineIntel" 686-class) | 1         | 3.23%   |
| Intel Celeron N4020 CPU @ 1.10GHz                               | 1         | 3.23%   |
| Intel Atom CPU N455 @ 1.66GHz ("GenuineIntel" 686-class)        | 1         | 3.23%   |
| Intel Atom CPU N280 @ 1.66GHz                                   | 1         | 3.23%   |
| AMD Ryzen 7 5825U with Radeon Graphics                          | 1         | 3.23%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics                      | 1         | 3.23%   |
| AMD E1-2500 APU with Radeon HD Graphics                         | 1         | 3.23%   |
|                                                                 | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 17        | 54.84%  |
| Intel Core i7    | 2         | 6.45%   |
| Intel Core 2 Duo | 2         | 6.45%   |
| Intel Atom       | 2         | 6.45%   |
| Other            | 1         | 3.23%   |
| Intel Pentium 4  | 1         | 3.23%   |
| Intel Genuine    | 1         | 3.23%   |
| Intel Core i3    | 1         | 3.23%   |
| Intel Celeron    | 1         | 3.23%   |
| AMD Ryzen 7      | 1         | 3.23%   |
| AMD Ryzen 5 PRO  | 1         | 3.23%   |
| AMD E1           | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 21        | 67.74%  |
| Unknown | 7         | 22.58%  |
| 16      | 1         | 3.23%   |
| 12      | 1         | 3.23%   |
| 4       | 1         | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 27        | 87.1%   |
| Unknown | 4         | 12.9%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 20        | 64.52%  |
| Unknown | 7         | 22.58%  |
| 1       | 4         | 12.9%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| IvyBridge     | 5         | 16.13%  |
| Skylake       | 4         | 12.9%   |
| SandyBridge   | 4         | 12.9%   |
| Westmere      | 3         | 9.68%   |
| Broadwell     | 2         | 6.45%   |
| Bonnell       | 2         | 6.45%   |
| Zen 3         | 1         | 3.23%   |
| Zen 2         | 1         | 3.23%   |
| Penryn        | 1         | 3.23%   |
| P6            | 1         | 3.23%   |
| NetBurst      | 1         | 3.23%   |
| KabyLake      | 1         | 3.23%   |
| Jaguar        | 1         | 3.23%   |
| Haswell       | 1         | 3.23%   |
| Goldmont plus | 1         | 3.23%   |
| Core          | 1         | 3.23%   |
| Unknown       | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 83.33%  |
| AMD    | 5         | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 15.15%  |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 12.12%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 12.12%  |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 9.09%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 6.06%   |
| Intel HD Graphics 5500                                                        | 2         | 6.06%   |
| Intel UHD Graphics 620                                                        | 1         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 3.03%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 3.03%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 3.03%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 3.03%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 3.03%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                         | 1         | 3.03%   |
| AMD Renoir                                                                    | 1         | 3.03%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 3.03%   |
| AMD Barcelo                                                                   | 1         | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| 1 x Intel   | 20        | 64.52%  |
| 2 x Intel   | 4         | 12.9%   |
| 1 x AMD     | 4         | 12.9%   |
| Other       | 2         | 6.45%   |
| Intel + AMD | 1         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 27        | 87.1%   |
| Unknown | 4         | 12.9%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 6         | 42.86%  |
| Samsung Electronics | 2         | 14.29%  |
| TRU                 | 1         | 7.14%   |
| LG Display          | 1         | 7.14%   |
| Lenovo              | 1         | 7.14%   |
| Chimei Innolux      | 1         | 7.14%   |
| BOE                 | 1         | 7.14%   |
| BenQ                | 1         | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                 | 1         | 7.14%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 7.14%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 7.14%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 1         | 7.14%   |
| Lenovo LCD Monitor LEN4053 1680x1050 330x210mm 15.4-inch             | 1         | 7.14%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 1         | 7.14%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                | 1         | 7.14%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                   | 1         | 7.14%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch       | 1         | 7.14%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 7.14%   |
| AU Optronics LCD Monitor AUO213E 1600x900 310x170mm 13.9-inch        | 1         | 7.14%   |
| AU Optronics LCD Monitor AUO173D 1920x1080 310x170mm 13.9-inch       | 1         | 7.14%   |
| AU Optronics LCD Monitor AUO1147 1440x900 300x190mm 14.0-inch        | 1         | 7.14%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 5         | 38.46%  |
| 1920x1080 (FHD)    | 4         | 30.77%  |
| 1600x900 (HD+)     | 2         | 15.38%  |
| 1680x1050 (WSXGA+) | 1         | 7.69%   |
| 1440x900 (WXGA+)   | 1         | 7.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 5         | 35.71%  |
| 15     | 3         | 21.43%  |
| 12     | 2         | 14.29%  |
| 11     | 2         | 14.29%  |
| 24     | 1         | 7.14%   |
| 14     | 1         | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 8         | 57.14%  |
| 201-300     | 5         | 35.71%  |
| 501-600     | 1         | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 11        | 84.62%  |
| 16/10 | 2         | 15.38%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 6         | 42.86%  |
| 61-70          | 2         | 14.29%  |
| 51-60          | 2         | 14.29%  |
| 101-110        | 2         | 14.29%  |
| 201-250        | 1         | 7.14%   |
| 91-100         | 1         | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 12        | 85.71%  |
| 51-100  | 2         | 14.29%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 27        | 87.1%   |
| 0     | 3         | 9.68%   |
| 2     | 1         | 3.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 25        | 64.1%   |
| Realtek Semiconductor             | 6         | 15.38%  |
| Qualcomm Atheros                  | 2         | 5.13%   |
| Ericsson Business Mobile Networks | 2         | 5.13%   |
| Sierra Wireless                   | 1         | 2.56%   |
| Ralink Technology                 | 1         | 2.56%   |
| Marvell Technology Group          | 1         | 2.56%   |
| Broadcom                          | 1         | 2.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 8         | 12.7%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 8         | 12.7%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 3         | 4.76%   |
| Intel Wireless 8260                                                         | 3         | 4.76%   |
| Intel Wireless 7265                                                         | 3         | 4.76%   |
| Intel Ethernet Connection I219-LM                                           | 3         | 4.76%   |
| Intel 82577LM Gigabit Network Connection                                    | 3         | 4.76%   |
| Intel Wireless 7260                                                         | 2         | 3.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 3.17%   |
| Intel Ethernet Connection (3) I218-LM                                       | 2         | 3.17%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 3.17%   |
| Sierra Wireless EM7455                                                      | 1         | 1.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 1         | 1.59%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                  | 1         | 1.59%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1         | 1.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 1.59%   |
| Ralink RT2501/RT2573 Wireless Adapter                                       | 1         | 1.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 1.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1         | 1.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 1.59%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 1.59%   |
| Intel Wireless 8265 / 8275                                                  | 1         | 1.59%   |
| Intel Wireless 3160                                                         | 1         | 1.59%   |
| Intel Wi-Fi 6 AX200                                                         | 1         | 1.59%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1         | 1.59%   |
| Intel Ethernet Connection I218-LM                                           | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 1.59%   |
| Intel 82567LM Gigabit Network Connection                                    | 1         | 1.59%   |
| Intel 82566MM Gigabit Network Connection                                    | 1         | 1.59%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module          | 1         | 1.59%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 1.59%   |
| Broadcom BRCM4378 Wireless Network Adapter                                  | 1         | 1.59%   |
| Broadcom BRCM4378 Bluetooth Controller                                      | 1         | 1.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 77.42%  |
| Realtek Semiconductor | 2         | 6.45%   |
| Qualcomm Atheros      | 2         | 6.45%   |
| Sierra Wireless       | 1         | 3.23%   |
| Ralink Technology     | 1         | 3.23%   |
| Broadcom              | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 25%     |
| Intel Wireless 8260                                            | 3         | 9.38%   |
| Intel Wireless 7265                                            | 3         | 9.38%   |
| Intel Wireless 7260                                            | 2         | 6.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 6.25%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 6.25%   |
| Sierra Wireless EM7455                                         | 1         | 3.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 3.13%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 3.13%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 3.13%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 3.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.13%   |
| Intel Wireless 8265 / 8275                                     | 1         | 3.13%   |
| Intel Wireless 3160                                            | 1         | 3.13%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 3.13%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 3.13%   |
| Broadcom BRCM4378 Wireless Network Adapter                     | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 20        | 71.43%  |
| Realtek Semiconductor    | 5         | 17.86%  |
| Qualcomm Atheros         | 2         | 7.14%   |
| Marvell Technology Group | 1         | 3.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 28.57%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 10.71%  |
| Intel Ethernet Connection I219-LM                                 | 3         | 10.71%  |
| Intel 82577LM Gigabit Network Connection                          | 3         | 10.71%  |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 7.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 3.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 3.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 3.57%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 3.57%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.57%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.57%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 48.33%  |
| Ethernet | 28        | 46.67%  |
| Unknown  | 2         | 3.33%   |
| Modem    | 1         | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 24        | 72.73%  |
| Ethernet | 9         | 27.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 27        | 87.1%   |
| 1     | 2         | 6.45%   |
| 3     | 1         | 3.23%   |
| 0     | 1         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 50%     |
| Broadcom              | 5         | 22.73%  |
| Foxconn / Hon Hai     | 2         | 9.09%   |
| Alps Electric         | 2         | 9.09%   |
| Realtek Semiconductor | 1         | 4.55%   |
| ASUSTek Computer      | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 10        | 45.45%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 3         | 13.64%  |
| Broadcom BCM2045B (BDC-2.1)                              | 2         | 9.09%   |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 9.09%   |
| Realtek Bluetooth Adapter                                | 1         | 4.55%   |
| Intel AX200 Bluetooth                                    | 1         | 4.55%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device          | 1         | 4.55%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 4.55%   |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 26        | 89.66%  |
| AMD    | 3         | 10.34%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 14.29%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 14.29%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 11.43%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 8.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 5.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 5.71%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 5.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 5.71%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 5.71%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 2.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.86%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 2.86%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.86%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 2.86%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 38.1%   |
| Unknown             | 5         | 23.81%  |
| SK hynix            | 5         | 23.81%  |
| Micron Technology   | 1         | 4.76%   |
| Crucial             | 1         | 4.76%   |
| Unknown             | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s   | 2         | 8.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 2         | 8.7%    |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 4.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1         | 4.35%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 4.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 4.35%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 4.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 4.35%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 4.35%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 1         | 4.35%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s | 1         | 4.35%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s  | 1         | 4.35%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s    | 1         | 4.35%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s   | 1         | 4.35%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 4.35%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 4.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s   | 1         | 4.35%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s   | 1         | 4.35%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s   | 1         | 4.35%   |
| Crucial RAM CT8G3S1339M 8GB SODIMM DDR3 800MT/s         | 1         | 4.35%   |
| Unknown                                                 | 1         | 4.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 12        | 60%     |
| DDR4   | 3         | 15%     |
| SDRAM  | 2         | 10%     |
| DDR2   | 2         | 10%     |
| LPDDR3 | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 20        | 95.24%  |
| Chip   | 1         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 7         | 35%     |
| 2048  | 6         | 30%     |
| 8192  | 4         | 20%     |
| 16384 | 1         | 5%      |
| 1024  | 1         | 5%      |
| 512   | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 4         | 20%     |
| 1067    | 3         | 15%     |
| Unknown | 3         | 15%     |
| 1334    | 2         | 10%     |
| 1333    | 2         | 10%     |
| 3200    | 1         | 5%      |
| 2667    | 1         | 5%      |
| 2133    | 1         | 5%      |
| 1867    | 1         | 5%      |
| 800     | 1         | 5%      |
| 667     | 1         | 5%      |

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


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chicony Electronics | 11        | 52.38%  |
| Bison Electronics   | 4         | 19.05%  |
| Lite-On Technology  | 3         | 14.29%  |
| Tripath Technology  | 1         | 4.76%   |
| Lenovo              | 1         | 4.76%   |
| IMC Networks        | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lite-On Integrated Camera                | 3         | 14.29%  |
| Bison Integrated Camera                  | 3         | 14.29%  |
| Chicony Integrated Camera [ThinkPad]     | 2         | 9.52%   |
| Chicony Integrated Camera                | 2         | 9.52%   |
| Tripath PC Camera                        | 1         | 4.76%   |
| Lenovo Integrated Webcam                 | 1         | 4.76%   |
| IMC Networks Integrated Camera           | 1         | 4.76%   |
| Chicony thinkpad t430s camera            | 1         | 4.76%   |
| Chicony Sonix ST50220 USB Video Camera   | 1         | 4.76%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 4.76%   |
| Chicony Lenovo EasyCamera                | 1         | 4.76%   |
| Chicony Integrated Camera (1280x720@30)  | 1         | 4.76%   |
| Chicony FJ Camera                        | 1         | 4.76%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 4.76%   |
| Bison USB HD Webcam                      | 1         | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 4         | 44.44%  |
| Synaptics        | 2         | 22.22%  |
| AuthenTec        | 2         | 22.22%  |
| Upek             | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 33.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 11.11%  |
| AuthenTec AES2810                                      | 1         | 11.11%  |
| AuthenTec AES2660                                      | 1         | 11.11%  |

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
| 1     | 22        | 70.97%  |
| 0     | 4         | 12.9%   |
| 5     | 2         | 6.45%   |
| 3     | 2         | 6.45%   |
| 2     | 1         | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 22        | 56.41%  |
| Graphics card            | 4         | 10.26%  |
| Firewire controller      | 4         | 10.26%  |
| Network                  | 3         | 7.69%   |
| Storage/ata              | 2         | 5.13%   |
| Sound                    | 2         | 5.13%   |
| Net/wireless             | 2         | 5.13%   |

