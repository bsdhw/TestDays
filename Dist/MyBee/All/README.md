MyBee - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MyBee.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MyBee/Desktop/README.md) and [notebooks](/Dist/MyBee/Notebook/README.md).

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

Total: 30

| Vendor        | Model                    | Form-Factor | Probe                                                     | Date         |
|---------------|--------------------------|-------------|-----------------------------------------------------------|--------------|
| ASUSTek       | P6X58D PREMIUM           | Desktop     | [946e123320](https://bsd-hardware.info/?probe=946e123320) | Aug 13, 2023 |
| Intel         | S3210SH FRU Ver          | Server      | [b4112bd797](https://bsd-hardware.info/?probe=b4112bd797) | Jul 24, 2023 |
| Insyde        | Purley                   | Server      | [c6ffd34b07](https://bsd-hardware.info/?probe=c6ffd34b07) | Jun 21, 2023 |
| ASRockRack    | X570D4U-2L2T             | Desktop     | [4cada5d71b](https://bsd-hardware.info/?probe=4cada5d71b) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T              | Desktop     | [e782ceaea8](https://bsd-hardware.info/?probe=e782ceaea8) | May 19, 2023 |
| Gigabyte      | H77N-WIFI                | Desktop     | [cf2014c973](https://bsd-hardware.info/?probe=cf2014c973) | May 04, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF         | Desktop     | [882a817f46](https://bsd-hardware.info/?probe=882a817f46) | Apr 13, 2023 |
| MSI           | PRO H610M-B DDR4         | Desktop     | [ee01b690bc](https://bsd-hardware.info/?probe=ee01b690bc) | Mar 25, 2023 |
| MSI           | PRO H610M-B DDR4         | Desktop     | [b08fd92e36](https://bsd-hardware.info/?probe=b08fd92e36) | Mar 10, 2023 |
| ASUSTek       | P8Z77-V PREMIUM          | Desktop     | [a2873d7c87](https://bsd-hardware.info/?probe=a2873d7c87) | Mar 09, 2023 |
| Huanan        | X99-QD4 V1.0             | Desktop     | [8404060d9e](https://bsd-hardware.info/?probe=8404060d9e) | Mar 02, 2023 |
| Unknown       | Unknown                  | Desktop     | [95c62844de](https://bsd-hardware.info/?probe=95c62844de) | Feb 25, 2023 |
| MSI           | PRO H610M-B DDR4         | Desktop     | [1deece00b3](https://bsd-hardware.info/?probe=1deece00b3) | Jan 05, 2023 |
| ASUSTek       | PRIME B550-PLUS          | Desktop     | [4c3b92bb42](https://bsd-hardware.info/?probe=4c3b92bb42) | Dec 24, 2022 |
| ASUSTek       | PRIME B550-PLUS          | Desktop     | [3e5e7e3e61](https://bsd-hardware.info/?probe=3e5e7e3e61) | Dec 22, 2022 |
| Gigabyte      | A320M-H-CF               | Desktop     | [2549c7cadf](https://bsd-hardware.info/?probe=2549c7cadf) | Aug 27, 2022 |
| ASUSTek       | PRIME B550-PLUS          | Desktop     | [7d4eaaf087](https://bsd-hardware.info/?probe=7d4eaaf087) | Aug 22, 2022 |
| ASUSTek       | PRIME B550-PLUS          | Desktop     | [063addc66e](https://bsd-hardware.info/?probe=063addc66e) | Aug 22, 2022 |
| HP            | EliteBook 8540w          | Notebook    | [0063369c40](https://bsd-hardware.info/?probe=0063369c40) | Jul 30, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | Desktop     | [e3461d0ff8](https://bsd-hardware.info/?probe=e3461d0ff8) | Jul 17, 2022 |
| Acer          | RS880M05                 | Desktop     | [7bcc14ceba](https://bsd-hardware.info/?probe=7bcc14ceba) | Jul 16, 2022 |
| Supermicro    | H8DGU                    | Server      | [172bfe70b5](https://bsd-hardware.info/?probe=172bfe70b5) | Jul 14, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | Desktop     | [75132f9078](https://bsd-hardware.info/?probe=75132f9078) | Jul 13, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | Desktop     | [7cdaeb28fa](https://bsd-hardware.info/?probe=7cdaeb28fa) | Jun 16, 2022 |
| ASRock        | X570 Phantom Gaming 4    | Desktop     | [067dbf3357](https://bsd-hardware.info/?probe=067dbf3357) | Jun 15, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB        | Desktop     | [b98e41f6a4](https://bsd-hardware.info/?probe=b98e41f6a4) | Jun 05, 2022 |
| Supermicro    | X10SRi-FB                | Server      | [0e21a1eeb0](https://bsd-hardware.info/?probe=0e21a1eeb0) | May 27, 2022 |
| ASRockRack    | E3C242D4U2-2T            | Desktop     | [66f9070856](https://bsd-hardware.info/?probe=66f9070856) | May 23, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | Desktop     | [ea6146e013](https://bsd-hardware.info/?probe=ea6146e013) | May 19, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | Desktop     | [6974f0958e](https://bsd-hardware.info/?probe=6974f0958e) | May 15, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| MyBee 13.1         | 7         | 29.17%  |
| MyBee 13.2         | 5         | 20.83%  |
| MyBee 13.1-p7      | 3         | 12.5%   |
| MyBee 14.0-CURRENT | 2         | 8.33%   |
| MyBee 13.1-p1      | 2         | 8.33%   |
| MyBee 13.2-RC5     | 1         | 4.17%   |
| MyBee 13.2-RC4     | 1         | 4.17%   |
| MyBee 13.2-RC2     | 1         | 4.17%   |
| MyBee 13.1-p5      | 1         | 4.17%   |
| MyBee 13.1-p3      | 1         | 4.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| MyBee | 23        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 23        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 22        | 95.65%  |
| KDE5    | 1         | 4.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 22        | 95.65%  |
| X11     | 1         | 4.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 23        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 21        | 91.3%   |
| C     | 2         | 8.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 23        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 23        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 23        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 4         | 17.39%  |
| Gigabyte Technology | 3         | 13.04%  |
| Supermicro          | 2         | 8.7%    |
| MSI                 | 2         | 8.7%    |
| Fujitsu             | 2         | 8.7%    |
| ASRockRack          | 2         | 8.7%    |
| Intel               | 1         | 4.35%   |
| Insyde              | 1         | 4.35%   |
| IceWhale Technology | 1         | 4.35%   |
| Huanan              | 1         | 4.35%   |
| Hewlett-Packard     | 1         | 4.35%   |
| ASRock              | 1         | 4.35%   |
| Acer                | 1         | 4.35%   |
| Unknown             | 1         | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| MSI MS-7D46                      | 2         | 8.7%    |
| Fujitsu D3401-H2 S26361-D3401-H2 | 2         | 8.7%    |
| ASUS PRIME B550-PLUS             | 2         | 8.7%    |
| Supermicro Super Server          | 1         | 4.35%   |
| Supermicro H8DGU                 | 1         | 4.35%   |
| Intel S3210SH                    | 1         | 4.35%   |
| Insyde Purley                    | 1         | 4.35%   |
| IceWhale ZimaBoard 832 ZMB       | 1         | 4.35%   |
| Huanan X99-QD4 V1.0              | 1         | 4.35%   |
| HP EliteBook 8540w               | 1         | 4.35%   |
| Gigabyte Z170-HD3 DDR3           | 1         | 4.35%   |
| Gigabyte H77N-WIFI               | 1         | 4.35%   |
| Gigabyte A320M-H                 | 1         | 4.35%   |
| ASUS P8Z77-V PREMIUM             | 1         | 4.35%   |
| ASUS P6X58D PREMIUM              | 1         | 4.35%   |
| ASRockRack X570D4U-2L2T          | 1         | 4.35%   |
| ASRockRack X470D4U2-2T           | 1         | 4.35%   |
| ASRock X570 Phantom Gaming 4     | 1         | 4.35%   |
| Acer Veriton M430                | 1         | 4.35%   |
| Unknown                          | 1         | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| MSI MS-7D46             | 2         | 8.7%    |
| Fujitsu D3401-H2        | 2         | 8.7%    |
| ASUS PRIME              | 2         | 8.7%    |
| Supermicro Super        | 1         | 4.35%   |
| Supermicro H8DGU        | 1         | 4.35%   |
| Intel S3210SH           | 1         | 4.35%   |
| Insyde Purley           | 1         | 4.35%   |
| IceWhale ZimaBoard      | 1         | 4.35%   |
| Huanan X99-QD4          | 1         | 4.35%   |
| HP EliteBook            | 1         | 4.35%   |
| Gigabyte Z170-HD3       | 1         | 4.35%   |
| Gigabyte H77N-WIFI      | 1         | 4.35%   |
| Gigabyte A320M-H        | 1         | 4.35%   |
| ASUS P8Z77-V            | 1         | 4.35%   |
| ASUS P6X58D             | 1         | 4.35%   |
| ASRockRack X570D4U-2L2T | 1         | 4.35%   |
| ASRockRack X470D4U2-2T  | 1         | 4.35%   |
| ASRock X570             | 1         | 4.35%   |
| Acer Veriton            | 1         | 4.35%   |
| Unknown                 | 1         | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 4         | 17.39%  |
| 2020 | 4         | 17.39%  |
| 2018 | 3         | 13.04%  |
| 2017 | 3         | 13.04%  |
| 2013 | 2         | 8.7%    |
| 2011 | 2         | 8.7%    |
| 2021 | 1         | 4.35%   |
| 2019 | 1         | 4.35%   |
| 2012 | 1         | 4.35%   |
| 2010 | 1         | 4.35%   |
| 2009 | 1         | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 18        | 78.26%  |
| Server   | 4         | 17.39%  |
| Notebook | 1         | 4.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 23        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 64.01-256.0     | 8         | 34.78%  |
| 8.01-16.0       | 8         | 34.78%  |
| 32.01-64.0      | 3         | 13.04%  |
| More than 256.0 | 1         | 4.35%   |
| 4.01-8.0        | 1         | 4.35%   |
| 24.01-32.0      | 1         | 4.35%   |
| 16.01-24.0      | 1         | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 10        | 43.48%  |
| 2.01-3.0   | 4         | 17.39%  |
| 1.01-2.0   | 4         | 17.39%  |
| 16.01-24.0 | 3         | 13.04%  |
| 4.01-8.0   | 1         | 4.35%   |
| 8.01-16.0  | 1         | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 8         | 34.78%  |
| 1      | 8         | 34.78%  |
| 3      | 3         | 13.04%  |
| 5      | 2         | 8.7%    |
| 6      | 1         | 4.35%   |
| 4      | 1         | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 86.96%  |
| Yes       | 3         | 13.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 20        | 86.96%  |
| Yes       | 3         | 13.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 21        | 91.3%   |
| Yes       | 2         | 8.7%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 16        | 69.57%  |
| Germany | 3         | 13.04%  |
| USA     | 1         | 4.35%   |
| Iceland | 1         | 4.35%   |
| Finland | 1         | 4.35%   |
| Canada  | 1         | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| St Petersburg       | 10        | 43.48%  |
| Moscow              | 3         | 13.04%  |
| Vladivostok         | 1         | 4.35%   |
| Rostov-on-Don       | 1         | 4.35%   |
| Reykjavik           | 1         | 4.35%   |
| Remscheid           | 1         | 4.35%   |
| Montreal            | 1         | 4.35%   |
| Limburg an der Lahn | 1         | 4.35%   |
| Irkutsk             | 1         | 4.35%   |
| Helsinki            | 1         | 4.35%   |
| Falkenstein         | 1         | 4.35%   |
| Clearwater          | 1         | 4.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 5         | 17     | 17.24%  |
| Seagate             | 5         | 11     | 17.24%  |
| Kingston            | 4         | 7      | 13.79%  |
| Samsung Electronics | 3         | 4      | 10.34%  |
| WDC                 | 2         | 2      | 6.9%    |
| KingSpec            | 2         | 2      | 6.9%    |
| Intel               | 2         | 3      | 6.9%    |
| Silicon Motion      | 1         | 2      | 3.45%   |
| Phison              | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 2      | 3.45%   |
| HGST                | 1         | 2      | 3.45%   |
| GOODRAM             | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 2      | 3.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Toshiba MG07ACA12TE 12TB         | 2         | 6.9%    |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 6.9%    |
| Samsung SSD 980 1TB              | 2         | 6.9%    |
| WDC WDS120G2G0A-00JH30 120GB     | 1         | 3.45%   |
| WDC WD30EJRX-89AKWY0 3TB         | 1         | 3.45%   |
| Toshiba MG06ACA800E 8TB          | 1         | 3.45%   |
| Toshiba KXG50ZNV512G 512GB       | 1         | 3.45%   |
| Toshiba DT01ACA100 1TB           | 1         | 3.45%   |
| Silicon Motion PCIe SSD 256GB    | 1         | 3.45%   |
| Seagate ST500DM002-1SB10A 500GB  | 1         | 3.45%   |
| Seagate ST1000NM0033-9ZM173 1TB  | 1         | 3.45%   |
| Seagate ST1000LM048-2E7172 1TB   | 1         | 3.45%   |
| Samsung SSD 870 EVO 1TB          | 1         | 3.45%   |
| Phison PCIe SSD 128GB            | 1         | 3.45%   |
| Micron 1100_MTFDDAK512TBN 512GB  | 1         | 3.45%   |
| Kingston SNV425S2128GB           | 1         | 3.45%   |
| Kingston SA400S37480G 480GB      | 1         | 3.45%   |
| Kingston SA400S37240G 240GB      | 1         | 3.45%   |
| Kingston SA400S37120G 120GB      | 1         | 3.45%   |
| KingSpec P3-256 256GB            | 1         | 3.45%   |
| KingSpec MT-1TB                  | 1         | 3.45%   |
| Intel SSDPEKNW010T8 1TB          | 1         | 3.45%   |
| Intel SSDPE2MX450G7 450GB        | 1         | 3.45%   |
| HGST HUS726T4TALA6L1 4TB         | 1         | 3.45%   |
| GOODRAM SSDPR-PX500-256-80 256GB | 1         | 3.45%   |
| A-DATA SX8200PNP 1TB             | 1         | 3.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 11     | 45.45%  |
| Toshiba | 4         | 15     | 36.36%  |
| WDC     | 1         | 1      | 9.09%   |
| HGST    | 1         | 2      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 7      | 44.44%  |
| KingSpec            | 2         | 2      | 22.22%  |
| WDC                 | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 2      | 11.11%  |
| Micron Technology   | 1         | 2      | 11.11%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 29     | 35.71%  |
| NVMe | 9         | 13     | 32.14%  |
| SSD  | 9         | 14     | 32.14%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 18        | 43     | 66.67%  |
| NVMe | 9         | 13     | 33.33%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 7         | 15     | 35%     |
| 0.01-0.5   | 7         | 10     | 35%     |
| 10.01-20.0 | 2         | 10     | 10%     |
| 3.01-4.0   | 1         | 2      | 5%      |
| 2.01-3.0   | 1         | 1      | 5%      |
| 1.01-2.0   | 1         | 1      | 5%      |
| 4.01-10.0  | 1         | 4      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 8         | 33.33%  |
| 101-250        | 5         | 20.83%  |
| More than 3000 | 4         | 16.67%  |
| 251-500        | 4         | 16.67%  |
| 1001-2000      | 2         | 8.33%   |
| 21-50          | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 21        | 91.3%   |
| More than 3000 | 2         | 8.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB        | 1         | 2      | 50%     |
| Micron Technology 1100_MTFDDAK512TBN 512GB | 1         | 2      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 50%     |
| Micron Technology   | 1         | 2      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 4      | 100%    |

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


| Status  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 22        | 52     | 91.67%  |
| Malfunc | 2         | 4      | 8.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 14        | 43.75%  |
| AMD                      | 8         | 25%     |
| Silicon Motion           | 2         | 6.25%   |
| Samsung Electronics      | 2         | 6.25%   |
| Toshiba                  | 1         | 3.13%   |
| Phison Electronics       | 1         | 3.13%   |
| Marvell Technology Group | 1         | 3.13%   |
| Broadcom / LSI           | 1         | 3.13%   |
| ASMedia Technology       | 1         | 3.13%   |
| ADATA Technology         | 1         | 3.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 8.11%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 3         | 8.11%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 2         | 5.41%   |
| Samsung NVMe SSD Controller 980                                               | 2         | 5.41%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                            | 2         | 5.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 2         | 5.41%   |
| AMD 500 Series Chipset SATA Controller                                        | 2         | 5.41%   |
| Toshiba XG5 NVMe SSD Controller                                               | 1         | 2.7%    |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 2.7%    |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller         | 1         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 2.7%    |
| Intel SSD 660P Series                                                         | 1         | 2.7%    |
| Intel PCIe Data Center SSD                                                    | 1         | 2.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 2.7%    |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                  | 1         | 2.7%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 1         | 2.7%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 1         | 2.7%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                             | 1         | 2.7%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]          | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 2.7%    |
| Broadcom / LSI MegaRAID 12GSAS/PCIe Secure SAS39xx                            | 1         | 2.7%    |
| ASMedia ASM1062 Serial ATA Controller                                         | 1         | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 1         | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1         | 2.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 1         | 2.7%    |
| AMD FCH SATA Controller D                                                     | 1         | 2.7%    |
| AMD 400 Series Chipset SATA Controller                                        | 1         | 2.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 21        | 65.63%  |
| NVMe | 9         | 28.13%  |
| RAID | 1         | 3.13%   |
| IDE  | 1         | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 15        | 65.22%  |
| AMD    | 8         | 34.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 8.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 8.7%    |
| Intel 12th Gen Core i5-12400                | 2         | 8.7%    |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 2         | 8.7%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 2         | 8.7%    |
| Intel Xeon Gold 6226R CPU @ 2.90GHz         | 1         | 4.35%   |
| Intel Xeon CPU E5-2686 v4 @ 2.30GHz         | 1         | 4.35%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1         | 4.35%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 4.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 4.35%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 4.35%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1         | 4.35%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 4.35%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 4.35%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 4.35%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1         | 4.35%   |
| AMD Phenom II X6 1045T Processor            | 1         | 4.35%   |
| AMD Opteron Processor 6176                  | 1         | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 7         | 30.43%  |
| AMD Ryzen 5             | 3         | 13.04%  |
| Other                   | 2         | 8.7%    |
| Intel Xeon              | 2         | 8.7%    |
| AMD Ryzen 5 PRO         | 2         | 8.7%    |
| Intel Xeon Gold         | 1         | 4.35%   |
| Intel Pentium Dual-Core | 1         | 4.35%   |
| Intel Core i5           | 1         | 4.35%   |
| Intel Celeron           | 1         | 4.35%   |
| AMD Ryzen 9             | 1         | 4.35%   |
| AMD Phenom II X6        | 1         | 4.35%   |
| AMD Opteron             | 1         | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 8         | 34.78%  |
| 12     | 4         | 17.39%  |
| 6      | 4         | 17.39%  |
| 24     | 2         | 8.7%    |
| 2      | 2         | 8.7%    |
| 32     | 1         | 4.35%   |
| 18     | 1         | 4.35%   |
| 8      | 1         | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 21        | 91.3%   |
| 2      | 2         | 8.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 12        | 52.17%  |
| 1      | 11        | 47.83%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| KabyLake  | 4         | 17.39%  |
| Zen 2     | 3         | 13.04%  |
| Zen 3     | 2         | 8.7%    |
| K10       | 2         | 8.7%    |
| IvyBridge | 2         | 8.7%    |
| Broadwell | 2         | 8.7%    |
| Unknown   | 2         | 8.7%    |
| Zen+      | 1         | 4.35%   |
| Westmere  | 1         | 4.35%   |
| Skylake   | 1         | 4.35%   |
| Penryn    | 1         | 4.35%   |
| Nehalem   | 1         | 4.35%   |
| Goldmont  | 1         | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 8         | 34.78%  |
| AMD                        | 5         | 21.74%  |
| Nvidia                     | 4         | 17.39%  |
| ASPEED Technology          | 4         | 17.39%  |
| Matrox Electronics Systems | 2         | 8.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                             | 4         | 17.39%  |
| Intel HD Graphics 630                                                | 3         | 13.04%  |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                            | 2         | 8.7%    |
| AMD Renoir                                                           | 2         | 8.7%    |
| Nvidia GP108 [GeForce GT 1030]                                       | 1         | 4.35%   |
| Nvidia GK107GL [Quadro K600]                                         | 1         | 4.35%   |
| Nvidia GF119 [GeForce GT 610]                                        | 1         | 4.35%   |
| Nvidia G96C [GeForce 9500 GT]                                        | 1         | 4.35%   |
| Matrox Electronics Systems MGA G200eW WPCM450                        | 1         | 4.35%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)    | 1         | 4.35%   |
| Intel UHD Graphics 620                                               | 1         | 4.35%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                               | 1         | 4.35%   |
| Intel HD Graphics 500                                                | 1         | 4.35%   |
| AMD RS880 [Radeon HD 4250]                                           | 1         | 4.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 4.35%   |
| AMD Madison [Mobility Radeon HD 5730 / 6570M]                        | 1         | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x Intel  | 8         | 34.78%  |
| 1 x AMD    | 5         | 21.74%  |
| 1 x Nvidia | 4         | 17.39%  |
| 1 x ASPEED | 4         | 17.39%  |
| 1 x Matrox | 2         | 8.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 23        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 95.65%  |
| 1.01-2.0   | 1         | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Dell   | 1         | 100%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Dell LCD Monitor U2715H 2560x1440 | 1         | 100%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 2560x1440 (QHD) | 1         | 100%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 1         | 100%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1         | 100%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 22        | 95.65%  |
| 1     | 1         | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 16        | 55.17%  |
| Realtek Semiconductor    | 9         | 31.03%  |
| American Megatrends      | 2         | 6.9%    |
| Marvell Technology Group | 1         | 3.45%   |
| Broadcom                 | 1         | 3.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 26.47%  |
| Intel I350 Gigabit Network Connection                             | 2         | 5.88%   |
| Intel I211 Gigabit Network Connection                             | 2         | 5.88%   |
| Intel Ethernet Controller X550                                    | 2         | 5.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 5.88%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 5.88%   |
| American Megatrends Virtual Ethernet                              | 2         | 5.88%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 2.94%   |
| Intel I210 Gigabit Network Connection                             | 1         | 2.94%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 2.94%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 2.94%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 2.94%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 2.94%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.94%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.94%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 2.94%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.94%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 2.94%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1         | 2.94%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 2.94%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 2         | 66.67%  |
| Broadcom | 1         | 33.33%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel Centrino Wireless-N 2230  | 1         | 33.33%  |
| Intel Centrino Advanced-N 6200  | 1         | 33.33%  |
| Broadcom BCM43224 802.11a/b/g/n | 1         | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 14        | 53.85%  |
| Realtek Semiconductor    | 9         | 34.62%  |
| American Megatrends      | 2         | 7.69%   |
| Marvell Technology Group | 1         | 3.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 29.03%  |
| Intel I350 Gigabit Network Connection                             | 2         | 6.45%   |
| Intel I211 Gigabit Network Connection                             | 2         | 6.45%   |
| Intel Ethernet Controller X550                                    | 2         | 6.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 6.45%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 6.45%   |
| American Megatrends Virtual Ethernet                              | 2         | 6.45%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 3.23%   |
| Intel I210 Gigabit Network Connection                             | 1         | 3.23%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 3.23%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 3.23%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.23%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.23%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 3.23%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 3.23%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 3.23%   |
| Intel 82541GI Gigabit Ethernet Controller                         | 1         | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 23        | 88.46%  |
| WiFi     | 3         | 11.54%  |

Used Controller
---------------

Currently used network controller

Zero info for selected period =(

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 23        | 100%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 20        | 86.96%  |
| Yes  | 3         | 13.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Intel           | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Centrino Bluetooth Wireless Transceiver | 1         | 50%     |
| HP Broadcom 2070 Bluetooth Combo              | 1         | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 8         | 42.11%  |
| AMD    | 8         | 42.11%  |
| Nvidia | 3         | 15.79%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 3         | 13.04%  |
| AMD Family 17h/19h HD Audio Controller                              | 3         | 13.04%  |
| Intel Alder Lake-S HD Audio Controller                              | 2         | 8.7%    |
| AMD Renoir Radeon High Definition Audio Controller                  | 2         | 8.7%    |
| Nvidia GP108 High Definition Audio Controller                       | 1         | 4.35%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 4.35%   |
| Nvidia GF119 HDMI Audio Controller                                  | 1         | 4.35%   |
| Intel Sunrise Point-LP HD Audio                                     | 1         | 4.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 4.35%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1         | 4.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1         | 4.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 4.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1         | 4.35%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 4.35%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                        | 1         | 4.35%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                      | 1         | 4.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 4.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston                                | 6         | 27.27%  |
| Samsung Electronics                     | 4         | 18.18%  |
| Crucial                                 | 4         | 18.18%  |
| SK hynix                                | 2         | 9.09%   |
| Silicon Power Computer & Communications | 2         | 9.09%   |
| Unknown (ABCD)                          | 1         | 4.55%   |
| Patriot                                 | 1         | 4.55%   |
| Micron Technology                       | 1         | 4.55%   |
| Unknown                                 | 1         | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Silicon Power & RAM Module 8GB DIMM DDR4 3200MT/s              | 2         | 8.33%   |
| Kingston RAM 9965745-026.A00G 16GB DIMM DDR4 3200MT/s          | 2         | 8.33%   |
| Crucial RAM CT16G4DFD824A.C16FHD 16GB DIMM DDR4 2400MT/s       | 2         | 8.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 4.17%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 4.17%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 2933MT/s           | 1         | 4.17%   |
| Samsung RAM Module 32GB DIMM DDR4 2133MT/s                     | 1         | 4.17%   |
| Samsung RAM Module 2GB DIMM DDR3 400MT/s                       | 1         | 4.17%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s           | 1         | 4.17%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s           | 1         | 4.17%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s           | 1         | 4.17%   |
| Patriot RAM 1600 CL10 Series 8GB DIMM DDR3 1600MT/s            | 1         | 4.17%   |
| Micron RAM 36KDYS1G72PZ-1G4M1 8GB DIMM DDR3 1333MT/s           | 1         | 4.17%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                      | 1         | 4.17%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 1         | 4.17%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s        | 1         | 4.17%   |
| Kingston RAM 9905474-050.A00LF 4GB DIMM DDR3 1333MT/s          | 1         | 4.17%   |
| Crucial RAM CT32G4DFD832A.M16FF 32GB DIMM DDR4 3200MT/s        | 1         | 4.17%   |
| Crucial RAM CT32G4DFD832A.C16FF 32GB DIMM DDR4 3200MT/s        | 1         | 4.17%   |
| Crucial RAM CT32G4DFD8266.C16FB 32GB DIMM DDR4 2666MT/s        | 1         | 4.17%   |
| Unknown                                                        | 1         | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 14        | 63.64%  |
| DDR3    | 5         | 22.73%  |
| LPDDR4  | 1         | 4.55%   |
| DDR2    | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 20        | 90.91%  |
| SODIMM | 2         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 7         | 31.82%  |
| 32768 | 5         | 22.73%  |
| 8192  | 5         | 22.73%  |
| 4096  | 3         | 13.64%  |
| 2048  | 2         | 9.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 6         | 27.27%  |
| 2400  | 5         | 22.73%  |
| 1333  | 3         | 13.64%  |
| 2933  | 1         | 4.55%   |
| 2667  | 1         | 4.55%   |
| 2666  | 1         | 4.55%   |
| 2133  | 1         | 4.55%   |
| 1600  | 1         | 4.55%   |
| 1066  | 1         | 4.55%   |
| 800   | 1         | 4.55%   |
| 400   | 1         | 4.55%   |

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

Zero info for selected period =(

Camera Model
------------

Camera device models

Zero info for selected period =(

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 12        | 52.17%  |
| 1     | 8         | 34.78%  |
| 2     | 3         | 13.04%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 11        | 91.67%  |
| Firewire controller      | 1         | 8.33%   |

