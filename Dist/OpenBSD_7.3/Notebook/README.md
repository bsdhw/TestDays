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

Total: 33

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 23        | 79.31%  |
| i386  | 5         | 17.24%  |
| arm64 | 1         | 3.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 24        | 82.76%  |
| GNOME        | 4         | 13.79%  |
| MATE         | 1         | 3.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 26        | 89.66%  |
| Console | 3         | 10.34%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 29        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 25        | 86.21%  |
| en_US   | 2         | 6.9%    |
| es_ES   | 1         | 3.45%   |
| C       | 1         | 3.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 15        | 51.72%  |
| BIOS | 14        | 48.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ffs  | 29        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 15        | 51.72%  |
| MBR  | 14        | 48.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 19        | 65.52%  |
| Panasonic                      | 2         | 6.9%    |
| Matsushita Electric Industrial | 2         | 6.9%    |
| Toshiba                        | 1         | 3.45%   |
| Tactus                         | 1         | 3.45%   |
| Hewlett-Packard                | 1         | 3.45%   |
| Fujitsu                        | 1         | 3.45%   |
| ASUSTek Computer               | 1         | 3.45%   |
| Unknown                        | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba NB250                               | 1         | 3.45%   |
| Tactus GeoFlex 110                          | 1         | 3.45%   |
| Panasonic CF-53AAGHYDM                      | 1         | 3.45%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 3.45%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 3.45%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 3.45%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 3.45%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 3.45%   |
| Lenovo ThinkPad X230 2325T4T                | 1         | 3.45%   |
| Lenovo ThinkPad X230 23257EP                | 1         | 3.45%   |
| Lenovo ThinkPad X220 429043U                | 1         | 3.45%   |
| Lenovo ThinkPad X201 3323BBG                | 1         | 3.45%   |
| Lenovo ThinkPad X140e 20BMS03E00            | 1         | 3.45%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 3.45%   |
| Lenovo ThinkPad T61 7659AS5                 | 1         | 3.45%   |
| Lenovo ThinkPad T500 205663G                | 1         | 3.45%   |
| Lenovo ThinkPad T480s 20L8A00KCL            | 1         | 3.45%   |
| Lenovo ThinkPad T450s 20BW001KLM            | 1         | 3.45%   |
| Lenovo ThinkPad T440s 20ARA07PLM            | 1         | 3.45%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 3.45%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 3.45%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 3.45%   |
| Lenovo ThinkPad T14 Gen 1 20UES5NW00        | 1         | 3.45%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW        | 1         | 3.45%   |
| Lenovo G570 20079                           | 1         | 3.45%   |
| HP Pavilion Notebook                        | 1         | 3.45%   |
| Fujitsu LIFEBOOK E752                       | 1         | 3.45%   |
| ASUS 1000HE                                 | 1         | 3.45%   |
| Unknown                                     | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 18        | 62.07%  |
| Toshiba NB250                               | 1         | 3.45%   |
| Tactus GeoFlex                              | 1         | 3.45%   |
| Panasonic CF-53AAGHYDM                      | 1         | 3.45%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 3.45%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 3.45%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 3.45%   |
| Lenovo G570                                 | 1         | 3.45%   |
| HP Pavilion                                 | 1         | 3.45%   |
| Fujitsu LIFEBOOK                            | 1         | 3.45%   |
| ASUS 1000HE                                 | 1         | 3.45%   |
| Unknown                                     | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 5         | 17.24%  |
| 2010    | 4         | 13.79%  |
| 2015    | 3         | 10.34%  |
| 2012    | 3         | 10.34%  |
| 2018    | 2         | 6.9%    |
| 2022    | 1         | 3.45%   |
| 2021    | 1         | 3.45%   |
| 2020    | 1         | 3.45%   |
| 2019    | 1         | 3.45%   |
| 2017    | 1         | 3.45%   |
| 2016    | 1         | 3.45%   |
| 2013    | 1         | 3.45%   |
| 2009    | 1         | 3.45%   |
| 2007    | 1         | 3.45%   |
| 2006    | 1         | 3.45%   |
| 2002    | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 29        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 8         | 27.59%  |
| 4.01-8.0   | 7         | 24.14%  |
| 3.01-4.0   | 6         | 20.69%  |
| 2.01-3.0   | 2         | 6.9%    |
| 0.51-1.0   | 2         | 6.9%    |
| 32.01-64.0 | 1         | 3.45%   |
| 24.01-32.0 | 1         | 3.45%   |
| 16.01-24.0 | 1         | 3.45%   |
| 1.01-2.0   | 1         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 24        | 82.76%  |
| 0        | 3         | 10.34%  |
| 1.01-2.0 | 1         | 3.45%   |
| 0.51-1.0 | 1         | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 65.52%  |
| 2      | 5         | 17.24%  |
| 3      | 4         | 13.79%  |
| 0      | 1         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 29        | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 26        | 89.66%  |
| No        | 3         | 10.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 93.1%   |
| No        | 2         | 6.9%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 68.97%  |
| No        | 9         | 31.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Canada   | 14        | 48.28%  |
| Uruguay  | 3         | 10.34%  |
| Brazil   | 3         | 10.34%  |
| USA      | 1         | 3.45%   |
| Ukraine  | 1         | 3.45%   |
| Spain    | 1         | 3.45%   |
| Russia   | 1         | 3.45%   |
| Romania  | 1         | 3.45%   |
| Poland   | 1         | 3.45%   |
| Mexico   | 1         | 3.45%   |
| Germany  | 1         | 3.45%   |
| Colombia | 1         | 3.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Saint-Laurent | 14        | 48.28%  |
| Montevideo    | 3         | 10.34%  |
| Blumenau      | 3         | 10.34%  |
| Swilcza       | 1         | 3.45%   |
| Sun Prairie   | 1         | 3.45%   |
| St Petersburg | 1         | 3.45%   |
| Puebla City   | 1         | 3.45%   |
| Navalcarnero  | 1         | 3.45%   |
| Montería     | 1         | 3.45%   |
| Lübeck       | 1         | 3.45%   |
| Brovary       | 1         | 3.45%   |
| Brasov        | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 18.18%  |
| NVMe                | 5         | 6      | 15.15%  |
| Samsung Electronics | 4         | 4      | 12.12%  |
| SanDisk             | 3         | 3      | 9.09%   |
| Kingston            | 3         | 3      | 9.09%   |
| Hitachi             | 3         | 3      | 9.09%   |
| Seagate             | 2         | 2      | 6.06%   |
| Verbatim            | 1         | 1      | 3.03%   |
| Union Memory        | 1         | 1      | 3.03%   |
| SMI                 | 1         | 1      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| Crucial             | 1         | 1      | 3.03%   |
| Apacer              | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| SanDisk Extreme SSD 500GB           | 2         | 5.88%   |
| NVMe SAMSUNG MZVLW256 256GB         | 2         | 5.88%   |
| WDC WD7500BPKX-00HPJT0 752GB        | 1         | 2.94%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 1         | 2.94%   |
| WDC WD7500BPKT-00PK4T0 752GB        | 1         | 2.94%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 2.94%   |
| WDC WD3200BEVE-00A0HT0 320GB        | 1         | 2.94%   |
| WDC WD10JPLX-00MBPT0 1TB            | 1         | 2.94%   |
| Verbatim STORE N GO 64GB            | 1         | 2.94%   |
| Union Memory RTOTJ128VGD2EYX 128GB  | 1         | 2.94%   |
| SMI USB DISK 18302PB                | 1         | 2.94%   |
| Seagate ST9160821A 160GB            | 1         | 2.94%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 2.94%   |
| SanDisk SSD PLUS 120GB              | 1         | 2.94%   |
| Samsung SSD 860 EVO M.2 1TB         | 1         | 2.94%   |
| Samsung SSD 850 EVO 500GB           | 1         | 2.94%   |
| Samsung MZ7TD128HAFV-000L1 128GB    | 1         | 2.94%   |
| Samsung MZ7PC128HAFU-000L1 128GB    | 1         | 2.94%   |
| NVMe Sabrent SB-1342- 1TB           | 1         | 2.94%   |
| NVMe KINGSTON SNVS200 2TB           | 1         | 2.94%   |
| NVMe KINGSTON SNV2S20 2TB           | 1         | 2.94%   |
| NVMe APPLE SSD AP0512 500GB         | 1         | 2.94%   |
| Kingston SA400S37240G 240GB         | 1         | 2.94%   |
| Kingston SA400S37120G 120GB         | 1         | 2.94%   |
| Kingston SA400M8240G 240GB          | 1         | 2.94%   |
| Intenso SSD 256GB                   | 1         | 2.94%   |
| Hitachi HTS723232A7A364 320GB       | 1         | 2.94%   |
| Hitachi HTS723225A7A365 OPAL 250GB  | 1         | 2.94%   |
| Hitachi HTS545016B9A300 160GB       | 1         | 2.94%   |
| Crucial CT480BX500SSD1 480GB        | 1         | 2.94%   |
| Apacer AS340 120GB                  | 1         | 2.94%   |
| A-DATA SP550 480GB                  | 1         | 2.94%   |

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
| Samsung Electronics | 4         | 4      | 25%     |
| SanDisk             | 3         | 3      | 18.75%  |
| Kingston            | 3         | 3      | 18.75%  |
| Union Memory        | 1         | 1      | 6.25%   |
| NVMe                | 1         | 1      | 6.25%   |
| Intenso             | 1         | 1      | 6.25%   |
| Crucial             | 1         | 1      | 6.25%   |
| Apacer              | 1         | 1      | 6.25%   |
| A-DATA Technology   | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 18     | 51.61%  |
| SSD  | 15        | 16     | 48.39%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 28        | 34     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 22        | 25     | 73.33%  |
| 0.51-1.0        | 5         | 5      | 16.67%  |
| 1.01-2.0        | 2         | 3      | 6.67%   |
| More than 100.0 | 1         | 1      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 21-50      | 11        | 37.93%  |
| 101-250    | 10        | 34.48%  |
| 51-100     | 4         | 13.79%  |
| 251-500    | 2         | 6.9%    |
| 1001-2000  | 1         | 3.45%   |
| 1-20       | 1         | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 25        | 86.21%  |
| 21-50   | 3         | 10.34%  |
| 51-100  | 1         | 3.45%   |

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
| Works    | 22        | 24     | 75.86%  |
| Detected | 6         | 9      | 20.69%  |
| Malfunc  | 1         | 1      | 3.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 22        | 78.57%  |
| Samsung Electronics         | 2         | 7.14%   |
| Kingston Technology Company | 2         | 7.14%   |
| Phison Electronics          | 1         | 3.57%   |
| AMD                         | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 4         | 13.79%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 10.34%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 10.34%  |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 10.34%  |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 6.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 6.9%    |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 3.45%   |
| Kingston Company unknown                                                               | 1         | 3.45%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                     | 1         | 3.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 3.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 1         | 3.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 1         | 3.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 3.45%   |
| Intel 82801CAM IDE U100 Controller                                                     | 1         | 3.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 1         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 3.45%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 1         | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 19        | 70.37%  |
| NVMe | 4         | 14.81%  |
| IDE  | 4         | 14.81%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 25        | 86.21%  |
| AMD     | 3         | 10.34%  |
| Unknown | 1         | 3.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                               | 3         | 10.34%  |
| Intel Core i5-3320M CPU @ 2.60GHz                               | 3         | 10.34%  |
| Intel Core i5-2520M CPU @ 2.50GHz                               | 3         | 10.34%  |
| Intel Core i5 CPU M 520 @ 2.40GHz                               | 2         | 6.9%    |
| Intel Pentium 4 Mobile CPU 1.60GHz                              | 1         | 3.45%   |
| Intel Genuine CPU T2300 @ 1.66GHz                               | 1         | 3.45%   |
| Intel Core i7-8650U CPU @ 1.90GHz                               | 1         | 3.45%   |
| Intel Core i7-3520M CPU @ 2.90GHz                               | 1         | 3.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz                               | 1         | 3.45%   |
| Intel Core i5-5300U CPU @ 2.30GHz                               | 1         | 3.45%   |
| Intel Core i5-4300U CPU @ 1.90GHz                               | 1         | 3.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz                               | 1         | 3.45%   |
| Intel Core i3 CPU M 350 @ 2.27GHz                               | 1         | 3.45%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz                            | 1         | 3.45%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz ("GenuineIntel" 686-class) | 1         | 3.45%   |
| Intel Celeron N4020 CPU @ 1.10GHz                               | 1         | 3.45%   |
| Intel Atom CPU N455 @ 1.66GHz ("GenuineIntel" 686-class)        | 1         | 3.45%   |
| Intel Atom CPU N280 @ 1.66GHz                                   | 1         | 3.45%   |
| AMD Ryzen 7 5825U with Radeon Graphics                          | 1         | 3.45%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics                      | 1         | 3.45%   |
| AMD E1-2500 APU with Radeon HD Graphics                         | 1         | 3.45%   |
|                                                                 | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 15        | 51.72%  |
| Intel Core i7    | 2         | 6.9%    |
| Intel Core 2 Duo | 2         | 6.9%    |
| Intel Atom       | 2         | 6.9%    |
| Other            | 1         | 3.45%   |
| Intel Pentium 4  | 1         | 3.45%   |
| Intel Genuine    | 1         | 3.45%   |
| Intel Core i3    | 1         | 3.45%   |
| Intel Celeron    | 1         | 3.45%   |
| AMD Ryzen 7      | 1         | 3.45%   |
| AMD Ryzen 5 PRO  | 1         | 3.45%   |
| AMD E1           | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 19        | 65.52%  |
| Unknown | 7         | 24.14%  |
| 16      | 1         | 3.45%   |
| 12      | 1         | 3.45%   |
| 4       | 1         | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 25        | 86.21%  |
| Unknown | 4         | 13.79%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 18        | 62.07%  |
| Unknown | 7         | 24.14%  |
| 1       | 4         | 13.79%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Skylake       | 4         | 13.79%  |
| SandyBridge   | 4         | 13.79%  |
| IvyBridge     | 4         | 13.79%  |
| Westmere      | 3         | 10.34%  |
| Bonnell       | 2         | 6.9%    |
| Zen 3         | 1         | 3.45%   |
| Zen 2         | 1         | 3.45%   |
| Penryn        | 1         | 3.45%   |
| P6            | 1         | 3.45%   |
| NetBurst      | 1         | 3.45%   |
| KabyLake      | 1         | 3.45%   |
| Jaguar        | 1         | 3.45%   |
| Haswell       | 1         | 3.45%   |
| Goldmont plus | 1         | 3.45%   |
| Core          | 1         | 3.45%   |
| Broadwell     | 1         | 3.45%   |
| Unknown       | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 82.14%  |
| AMD    | 5         | 17.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 12.9%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 12.9%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 12.9%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 9.68%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 6.45%   |
| Intel UHD Graphics 620                                                        | 1         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 3.23%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 3.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1         | 3.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 3.23%   |
| Intel HD Graphics 5500                                                        | 1         | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 3.23%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 3.23%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                           | 1         | 3.23%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                         | 1         | 3.23%   |
| AMD Renoir                                                                    | 1         | 3.23%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                       | 1         | 3.23%   |
| AMD Barcelo                                                                   | 1         | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| 1 x Intel   | 18        | 62.07%  |
| 2 x Intel   | 4         | 13.79%  |
| 1 x AMD     | 4         | 13.79%  |
| Other       | 2         | 6.9%    |
| Intel + AMD | 1         | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 25        | 86.21%  |
| Unknown | 4         | 13.79%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 38.46%  |
| Samsung Electronics | 2         | 15.38%  |
| TRU                 | 1         | 7.69%   |
| LG Display          | 1         | 7.69%   |
| Lenovo              | 1         | 7.69%   |
| Chimei Innolux      | 1         | 7.69%   |
| BOE                 | 1         | 7.69%   |
| BenQ                | 1         | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| TRU LCD Monitor TRU235C 1366x768 260x140mm 11.6-inch                 | 1         | 7.69%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 7.69%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch | 1         | 7.69%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch          | 1         | 7.69%   |
| Lenovo LCD Monitor LEN4053 1680x1050 330x210mm 15.4-inch             | 1         | 7.69%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 1         | 7.69%   |
| BOE LCD Monitor BOE08E2 1920x1080 340x190mm 15.3-inch                | 1         | 7.69%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                   | 1         | 7.69%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch       | 1         | 7.69%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch        | 1         | 7.69%   |
| AU Optronics LCD Monitor AUO173D 1920x1080 310x170mm 13.9-inch       | 1         | 7.69%   |
| AU Optronics LCD Monitor AUO1147 1440x900 300x190mm 14.0-inch        | 1         | 7.69%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch        | 1         | 7.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 5         | 41.67%  |
| 1920x1080 (FHD)    | 4         | 33.33%  |
| 1680x1050 (WSXGA+) | 1         | 8.33%   |
| 1600x900 (HD+)     | 1         | 8.33%   |
| 1440x900 (WXGA+)   | 1         | 8.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 4         | 30.77%  |
| 15     | 3         | 23.08%  |
| 12     | 2         | 15.38%  |
| 11     | 2         | 15.38%  |
| 24     | 1         | 7.69%   |
| 14     | 1         | 7.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 7         | 53.85%  |
| 201-300     | 5         | 38.46%  |
| 501-600     | 1         | 7.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 10        | 83.33%  |
| 16/10 | 2         | 16.67%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 5         | 38.46%  |
| 61-70          | 2         | 15.38%  |
| 51-60          | 2         | 15.38%  |
| 101-110        | 2         | 15.38%  |
| 201-250        | 1         | 7.69%   |
| 91-100         | 1         | 7.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 11        | 84.62%  |
| 51-100  | 2         | 15.38%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 25        | 86.21%  |
| 0     | 3         | 10.34%  |
| 2     | 1         | 3.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 23        | 62.16%  |
| Realtek Semiconductor             | 6         | 16.22%  |
| Qualcomm Atheros                  | 2         | 5.41%   |
| Ericsson Business Mobile Networks | 2         | 5.41%   |
| Sierra Wireless                   | 1         | 2.7%    |
| Ralink Technology                 | 1         | 2.7%    |
| Marvell Technology Group          | 1         | 2.7%    |
| Broadcom                          | 1         | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 7         | 11.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 7         | 11.86%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 3         | 5.08%   |
| Intel Wireless 8260                                                         | 3         | 5.08%   |
| Intel Ethernet Connection I219-LM                                           | 3         | 5.08%   |
| Intel 82577LM Gigabit Network Connection                                    | 3         | 5.08%   |
| Intel Wireless 7265                                                         | 2         | 3.39%   |
| Intel Wireless 7260                                                         | 2         | 3.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 2         | 3.39%   |
| Intel Centrino Advanced-N 6200                                              | 2         | 3.39%   |
| Sierra Wireless EM7455                                                      | 1         | 1.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 1         | 1.69%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                  | 1         | 1.69%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                 | 1         | 1.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1         | 1.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                       | 1         | 1.69%   |
| Ralink RT2501/RT2573 Wireless Adapter                                       | 1         | 1.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 1.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1         | 1.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet              | 1         | 1.69%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                     | 1         | 1.69%   |
| Intel Wireless 8265 / 8275                                                  | 1         | 1.69%   |
| Intel Wireless 3160                                                         | 1         | 1.69%   |
| Intel Wi-Fi 6 AX200                                                         | 1         | 1.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1         | 1.69%   |
| Intel Ethernet Connection I218-LM                                           | 1         | 1.69%   |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 1.69%   |
| Intel Ethernet Connection (3) I218-LM                                       | 1         | 1.69%   |
| Intel 82567LM Gigabit Network Connection                                    | 1         | 1.69%   |
| Intel 82566MM Gigabit Network Connection                                    | 1         | 1.69%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module          | 1         | 1.69%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 1.69%   |
| Broadcom BRCM4378 Wireless Network Adapter                                  | 1         | 1.69%   |
| Broadcom BRCM4378 Bluetooth Controller                                      | 1         | 1.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 75.86%  |
| Realtek Semiconductor | 2         | 6.9%    |
| Qualcomm Atheros      | 2         | 6.9%    |
| Sierra Wireless       | 1         | 3.45%   |
| Ralink Technology     | 1         | 3.45%   |
| Broadcom              | 1         | 3.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 23.33%  |
| Intel Wireless 8260                                            | 3         | 10%     |
| Intel Wireless 7265                                            | 2         | 6.67%   |
| Intel Wireless 7260                                            | 2         | 6.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 6.67%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 6.67%   |
| Sierra Wireless EM7455                                         | 1         | 3.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 3.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 3.33%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 3.33%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 3.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 3.33%   |
| Intel Wireless 8265 / 8275                                     | 1         | 3.33%   |
| Intel Wireless 3160                                            | 1         | 3.33%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 3.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 3.33%   |
| Broadcom BRCM4378 Wireless Network Adapter                     | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 18        | 69.23%  |
| Realtek Semiconductor    | 5         | 19.23%  |
| Qualcomm Atheros         | 2         | 7.69%   |
| Marvell Technology Group | 1         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 26.92%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3         | 11.54%  |
| Intel Ethernet Connection I219-LM                                 | 3         | 11.54%  |
| Intel 82577LM Gigabit Network Connection                          | 3         | 11.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 3.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 3.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 3.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 3.85%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 3.85%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.85%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.85%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 3.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 48.21%  |
| Ethernet | 26        | 46.43%  |
| Unknown  | 2         | 3.57%   |
| Modem    | 1         | 1.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 75.86%  |
| Ethernet | 7         | 24.14%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 25        | 86.21%  |
| 1     | 2         | 6.9%    |
| 3     | 1         | 3.45%   |
| 0     | 1         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 50%     |
| Broadcom              | 4         | 20%     |
| Foxconn / Hon Hai     | 2         | 10%     |
| Alps Electric         | 2         | 10%     |
| Realtek Semiconductor | 1         | 5%      |
| ASUSTek Computer      | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 9         | 45%     |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 2         | 10%     |
| Broadcom BCM2045B (BDC-2.1)                              | 2         | 10%     |
| Alps Electric UGTZ4 Bluetooth                            | 2         | 10%     |
| Realtek Bluetooth Adapter                                | 1         | 5%      |
| Intel AX200 Bluetooth                                    | 1         | 5%      |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device          | 1         | 5%      |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 1         | 5%      |
| ASUS Broadcom Bluetooth 2.1                              | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 88.89%  |
| AMD    | 3         | 11.11%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 15.63%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 12.5%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 12.5%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 9.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 6.25%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 2         | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 6.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 3.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 3.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 3.13%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 3.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 3.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 3.13%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                   | 1         | 3.13%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 3.13%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 3.13%   |
| AMD FCH Azalia Controller                                                  | 1         | 3.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 42.11%  |
| Unknown             | 5         | 26.32%  |
| SK hynix            | 5         | 26.32%  |
| Unknown             | 1         | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s   | 2         | 9.52%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 2         | 9.52%   |
| Unknown RAM Module 512MB SODIMM SDRAM                   | 1         | 4.76%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1         | 4.76%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s             | 1         | 4.76%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 4.76%   |
| Unknown RAM Module 1GB SODIMM DDR2                      | 1         | 4.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 4.76%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 4.76%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 1         | 4.76%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s | 1         | 4.76%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB SODIMM LPDDR3 1867MT/s  | 1         | 4.76%   |
| SK hynix RAM H9CCNNNBJTMLAR 4GB Chip LPDDR3 1867MT/s    | 1         | 4.76%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s   | 1         | 4.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 4.76%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1         | 4.76%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s   | 1         | 4.76%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s   | 1         | 4.76%   |
| Unknown                                                 | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 10        | 55.56%  |
| DDR4   | 3         | 16.67%  |
| SDRAM  | 2         | 11.11%  |
| DDR2   | 2         | 11.11%  |
| LPDDR3 | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 18        | 94.74%  |
| Chip   | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 7         | 38.89%  |
| 2048  | 6         | 33.33%  |
| 8192  | 2         | 11.11%  |
| 16384 | 1         | 5.56%   |
| 1024  | 1         | 5.56%   |
| 512   | 1         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 3         | 16.67%  |
| 1067    | 3         | 16.67%  |
| Unknown | 3         | 16.67%  |
| 1334    | 2         | 11.11%  |
| 1333    | 2         | 11.11%  |
| 3200    | 1         | 5.56%   |
| 2400    | 1         | 5.56%   |
| 2133    | 1         | 5.56%   |
| 1867    | 1         | 5.56%   |
| 667     | 1         | 5.56%   |

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
| Chicony Electronics | 10        | 52.63%  |
| Lite-On Technology  | 3         | 15.79%  |
| Bison Electronics   | 3         | 15.79%  |
| Tripath Technology  | 1         | 5.26%   |
| Lenovo              | 1         | 5.26%   |
| IMC Networks        | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lite-On Integrated Camera                | 3         | 15.79%  |
| Bison Integrated Camera                  | 3         | 15.79%  |
| Chicony Integrated Camera [ThinkPad]     | 2         | 10.53%  |
| Chicony Integrated Camera                | 2         | 10.53%  |
| Tripath PC Camera                        | 1         | 5.26%   |
| Lenovo Integrated Webcam                 | 1         | 5.26%   |
| IMC Networks Integrated Camera           | 1         | 5.26%   |
| Chicony Sonix ST50220 USB Video Camera   | 1         | 5.26%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 5.26%   |
| Chicony Lenovo EasyCamera                | 1         | 5.26%   |
| Chicony Integrated Camera (1280x720@30)  | 1         | 5.26%   |
| Chicony FJ Camera                        | 1         | 5.26%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 1         | 5.26%   |

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
| 1     | 21        | 72.41%  |
| 0     | 3         | 10.34%  |
| 5     | 2         | 6.9%    |
| 3     | 2         | 6.9%    |
| 2     | 1         | 3.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 21        | 55.26%  |
| Graphics card            | 4         | 10.53%  |
| Firewire controller      | 4         | 10.53%  |
| Network                  | 3         | 7.89%   |
| Storage/ata              | 2         | 5.26%   |
| Sound                    | 2         | 5.26%   |
| Net/wireless             | 2         | 5.26%   |

