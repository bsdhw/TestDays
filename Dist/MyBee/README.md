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

Total: 28

| Vendor        | Model                    | Form-Factor | Probe                                                     | Date         |
|---------------|--------------------------|-------------|-----------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| MyBee 13.1         | 7         | 31.82%  |
| MyBee 13.2         | 3         | 13.64%  |
| MyBee 13.1-p7      | 3         | 13.64%  |
| MyBee 14.0-CURRENT | 2         | 9.09%   |
| MyBee 13.1-p1      | 2         | 9.09%   |
| MyBee 13.2-RC5     | 1         | 4.55%   |
| MyBee 13.2-RC4     | 1         | 4.55%   |
| MyBee 13.2-RC2     | 1         | 4.55%   |
| MyBee 13.1-p5      | 1         | 4.55%   |
| MyBee 13.1-p3      | 1         | 4.55%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| MyBee | 21        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 21        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 20        | 95.24%  |
| KDE5    | 1         | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 20        | 95.24%  |
| X11     | 1         | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 21        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 19        | 90.48%  |
| C     | 2         | 9.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 21        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 21        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 21        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Gigabyte Technology | 3         | 14.29%  |
| ASUSTek Computer    | 3         | 14.29%  |
| Supermicro          | 2         | 9.52%   |
| MSI                 | 2         | 9.52%   |
| Fujitsu             | 2         | 9.52%   |
| ASRockRack          | 2         | 9.52%   |
| Insyde              | 1         | 4.76%   |
| IceWhale Technology | 1         | 4.76%   |
| Huanan              | 1         | 4.76%   |
| Hewlett-Packard     | 1         | 4.76%   |
| ASRock              | 1         | 4.76%   |
| Acer                | 1         | 4.76%   |
| Unknown             | 1         | 4.76%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| MSI MS-7D46                      | 2         | 9.52%   |
| Fujitsu D3401-H2 S26361-D3401-H2 | 2         | 9.52%   |
| ASUS PRIME B550-PLUS             | 2         | 9.52%   |
| Supermicro Super Server          | 1         | 4.76%   |
| Supermicro H8DGU                 | 1         | 4.76%   |
| Insyde Purley                    | 1         | 4.76%   |
| IceWhale ZimaBoard 832 ZMB       | 1         | 4.76%   |
| Huanan X99-QD4 V1.0              | 1         | 4.76%   |
| HP EliteBook 8540w               | 1         | 4.76%   |
| Gigabyte Z170-HD3 DDR3           | 1         | 4.76%   |
| Gigabyte H77N-WIFI               | 1         | 4.76%   |
| Gigabyte A320M-H                 | 1         | 4.76%   |
| ASUS P8Z77-V PREMIUM             | 1         | 4.76%   |
| ASRockRack X570D4U-2L2T          | 1         | 4.76%   |
| ASRockRack X470D4U2-2T           | 1         | 4.76%   |
| ASRock X570 Phantom Gaming 4     | 1         | 4.76%   |
| Acer Veriton M430                | 1         | 4.76%   |
| Unknown                          | 1         | 4.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| MSI MS-7D46             | 2         | 9.52%   |
| Fujitsu D3401-H2        | 2         | 9.52%   |
| ASUS PRIME              | 2         | 9.52%   |
| Supermicro Super        | 1         | 4.76%   |
| Supermicro H8DGU        | 1         | 4.76%   |
| Insyde Purley           | 1         | 4.76%   |
| IceWhale ZimaBoard      | 1         | 4.76%   |
| Huanan X99-QD4          | 1         | 4.76%   |
| HP EliteBook            | 1         | 4.76%   |
| Gigabyte Z170-HD3       | 1         | 4.76%   |
| Gigabyte H77N-WIFI      | 1         | 4.76%   |
| Gigabyte A320M-H        | 1         | 4.76%   |
| ASUS P8Z77-V            | 1         | 4.76%   |
| ASRockRack X570D4U-2L2T | 1         | 4.76%   |
| ASRockRack X470D4U2-2T  | 1         | 4.76%   |
| ASRock X570             | 1         | 4.76%   |
| Acer Veriton            | 1         | 4.76%   |
| Unknown                 | 1         | 4.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 4         | 19.05%  |
| 2020 | 4         | 19.05%  |
| 2018 | 3         | 14.29%  |
| 2017 | 3         | 14.29%  |
| 2013 | 2         | 9.52%   |
| 2021 | 1         | 4.76%   |
| 2019 | 1         | 4.76%   |
| 2012 | 1         | 4.76%   |
| 2011 | 1         | 4.76%   |
| 2010 | 1         | 4.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 17        | 80.95%  |
| Server   | 3         | 14.29%  |
| Notebook | 1         | 4.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 21        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 64.01-256.0     | 8         | 38.1%   |
| 8.01-16.0       | 7         | 33.33%  |
| 32.01-64.0      | 3         | 14.29%  |
| More than 256.0 | 1         | 4.76%   |
| 4.01-8.0        | 1         | 4.76%   |
| 16.01-24.0      | 1         | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 9         | 42.86%  |
| 2.01-3.0   | 4         | 19.05%  |
| 16.01-24.0 | 3         | 14.29%  |
| 1.01-2.0   | 3         | 14.29%  |
| 4.01-8.0   | 1         | 4.76%   |
| 8.01-16.0  | 1         | 4.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 8         | 38.1%   |
| 2      | 6         | 28.57%  |
| 3      | 3         | 14.29%  |
| 5      | 2         | 9.52%   |
| 6      | 1         | 4.76%   |
| 4      | 1         | 4.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 19        | 90.48%  |
| Yes       | 2         | 9.52%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 18        | 85.71%  |
| Yes       | 3         | 14.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 19        | 90.48%  |
| Yes       | 2         | 9.52%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 14        | 66.67%  |
| Germany | 3         | 14.29%  |
| USA     | 1         | 4.76%   |
| Iceland | 1         | 4.76%   |
| Finland | 1         | 4.76%   |
| Canada  | 1         | 4.76%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| St Petersburg       | 8         | 38.1%   |
| Moscow              | 3         | 14.29%  |
| Vladivostok         | 1         | 4.76%   |
| Rostov-on-Don       | 1         | 4.76%   |
| Reykjavik           | 1         | 4.76%   |
| Remscheid           | 1         | 4.76%   |
| Montreal            | 1         | 4.76%   |
| Limburg an der Lahn | 1         | 4.76%   |
| Irkutsk             | 1         | 4.76%   |
| Helsinki            | 1         | 4.76%   |
| Falkenstein         | 1         | 4.76%   |
| Clearwater          | 1         | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 16     | 15.38%  |
| Seagate             | 4         | 9      | 15.38%  |
| Kingston            | 4         | 7      | 15.38%  |
| Samsung Electronics | 3         | 4      | 11.54%  |
| KingSpec            | 2         | 2      | 7.69%   |
| Intel               | 2         | 3      | 7.69%   |
| WDC                 | 1         | 1      | 3.85%   |
| Silicon Motion      | 1         | 2      | 3.85%   |
| Phison              | 1         | 1      | 3.85%   |
| Micron Technology   | 1         | 2      | 3.85%   |
| HGST                | 1         | 2      | 3.85%   |
| GOODRAM             | 1         | 1      | 3.85%   |
| A-DATA Technology   | 1         | 2      | 3.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Toshiba MG07ACA12TE 12TB         | 2         | 7.69%   |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 7.69%   |
| Samsung SSD 980 1TB              | 2         | 7.69%   |
| WDC WDS120G2G0A-00JH30 120GB     | 1         | 3.85%   |
| Toshiba MG06ACA800E 8TB          | 1         | 3.85%   |
| Toshiba KXG50ZNV512G 512GB       | 1         | 3.85%   |
| Silicon Motion PCIe SSD 256GB    | 1         | 3.85%   |
| Seagate ST500DM002-1SB10A 500GB  | 1         | 3.85%   |
| Seagate ST1000LM048-2E7172 1TB   | 1         | 3.85%   |
| Samsung SSD 870 EVO 1TB          | 1         | 3.85%   |
| Phison PCIe SSD 128GB            | 1         | 3.85%   |
| Micron 1100_MTFDDAK512TBN 512GB  | 1         | 3.85%   |
| Kingston SNV425S2128GB           | 1         | 3.85%   |
| Kingston SA400S37480G 480GB      | 1         | 3.85%   |
| Kingston SA400S37240G 240GB      | 1         | 3.85%   |
| Kingston SA400S37120G 120GB      | 1         | 3.85%   |
| KingSpec P3-256 256GB            | 1         | 3.85%   |
| KingSpec MT-1TB                  | 1         | 3.85%   |
| Intel SSDPEKNW010T8 1TB          | 1         | 3.85%   |
| Intel SSDPE2MX450G7 450GB        | 1         | 3.85%   |
| HGST HUS726T4TALA6L1 4TB         | 1         | 3.85%   |
| GOODRAM SSDPR-PX500-256-80 256GB | 1         | 3.85%   |
| A-DATA SX8200PNP 1TB             | 1         | 3.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 9      | 50%     |
| Toshiba | 3         | 14     | 37.5%   |
| HGST    | 1         | 2      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


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

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 9         | 13     | 34.62%  |
| SSD  | 9         | 14     | 34.62%  |
| HDD  | 8         | 25     | 30.77%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16        | 39     | 64%     |
| NVMe | 9         | 13     | 36%     |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7         | 10     | 41.18%  |
| 0.51-1.0   | 5         | 12     | 29.41%  |
| 10.01-20.0 | 2         | 10     | 11.76%  |
| 3.01-4.0   | 1         | 2      | 5.88%   |
| 1.01-2.0   | 1         | 1      | 5.88%   |
| 4.01-10.0  | 1         | 4      | 5.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 7         | 31.82%  |
| 101-250        | 5         | 22.73%  |
| 251-500        | 4         | 18.18%  |
| More than 3000 | 3         | 13.64%  |
| 1001-2000      | 2         | 9.09%   |
| 21-50          | 1         | 4.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 19        | 90.48%  |
| More than 3000 | 2         | 9.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB        | 1         | 2      | 50%     |
| Micron Technology 1100_MTFDDAK512TBN 512GB | 1         | 2      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


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

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 20        | 48     | 90.91%  |
| Malfunc | 2         | 4      | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 12        | 40%     |
| AMD                      | 8         | 26.67%  |
| Silicon Motion           | 2         | 6.67%   |
| Samsung Electronics      | 2         | 6.67%   |
| Toshiba                  | 1         | 3.33%   |
| Phison Electronics       | 1         | 3.33%   |
| Marvell Technology Group | 1         | 3.33%   |
| Broadcom / LSI           | 1         | 3.33%   |
| ASMedia Technology       | 1         | 3.33%   |
| ADATA Technology         | 1         | 3.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 8.57%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 3         | 8.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                               | 2         | 5.71%   |
| Samsung NVMe SSD Controller 980                                               | 2         | 5.71%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                            | 2         | 5.71%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 2         | 5.71%   |
| AMD 500 Series Chipset SATA Controller                                        | 2         | 5.71%   |
| Toshiba XG5 NVMe SSD Controller                                               | 1         | 2.86%   |
| Phison PS5013 E13 NVMe Controller                                             | 1         | 2.86%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller         | 1         | 2.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 2.86%   |
| Intel SSD 660P Series                                                         | 1         | 2.86%   |
| Intel PCIe Data Center SSD                                                    | 1         | 2.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 2.86%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                  | 1         | 2.86%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 1         | 2.86%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 1         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 2.86%   |
| Broadcom / LSI MegaRAID 12GSAS/PCIe Secure SAS39xx                            | 1         | 2.86%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1         | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 1         | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1         | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 1         | 2.86%   |
| AMD FCH SATA Controller D                                                     | 1         | 2.86%   |
| AMD 400 Series Chipset SATA Controller                                        | 1         | 2.86%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1         | 2.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 19        | 63.33%  |
| NVMe | 9         | 30%     |
| RAID | 1         | 3.33%   |
| IDE  | 1         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 13        | 61.9%   |
| AMD    | 8         | 38.1%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 9.52%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 9.52%   |
| Intel 12th Gen Core i5-12400                | 2         | 9.52%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 2         | 9.52%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2         | 9.52%   |
| Intel Xeon Gold 6226R CPU @ 2.90GHz         | 1         | 4.76%   |
| Intel Xeon CPU E5-2686 v4 @ 2.30GHz         | 1         | 4.76%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1         | 4.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 4.76%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 4.76%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 4.76%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 4.76%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 4.76%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1         | 4.76%   |
| AMD Phenom II X6 1045T Processor            | 1         | 4.76%   |
| AMD Opteron Processor 6176                  | 1         | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 6         | 28.57%  |
| AMD Ryzen 5      | 3         | 14.29%  |
| Other            | 2         | 9.52%   |
| Intel Xeon       | 2         | 9.52%   |
| AMD Ryzen 5 PRO  | 2         | 9.52%   |
| Intel Xeon Gold  | 1         | 4.76%   |
| Intel Core i5    | 1         | 4.76%   |
| Intel Celeron    | 1         | 4.76%   |
| AMD Ryzen 9      | 1         | 4.76%   |
| AMD Phenom II X6 | 1         | 4.76%   |
| AMD Opteron      | 1         | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 7         | 33.33%  |
| 12     | 4         | 19.05%  |
| 6      | 4         | 19.05%  |
| 24     | 2         | 9.52%   |
| 32     | 1         | 4.76%   |
| 18     | 1         | 4.76%   |
| 8      | 1         | 4.76%   |
| 2      | 1         | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 19        | 90.48%  |
| 2      | 2         | 9.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 11        | 52.38%  |
| 1      | 10        | 47.62%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| KabyLake  | 4         | 19.05%  |
| Zen 2     | 3         | 14.29%  |
| Zen 3     | 2         | 9.52%   |
| K10       | 2         | 9.52%   |
| IvyBridge | 2         | 9.52%   |
| Broadwell | 2         | 9.52%   |
| Unknown   | 2         | 9.52%   |
| Zen+      | 1         | 4.76%   |
| Westmere  | 1         | 4.76%   |
| Skylake   | 1         | 4.76%   |
| Goldmont  | 1         | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 8         | 38.1%   |
| AMD                        | 5         | 23.81%  |
| ASPEED Technology          | 4         | 19.05%  |
| Nvidia                     | 3         | 14.29%  |
| Matrox Electronics Systems | 1         | 4.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                             | 4         | 19.05%  |
| Intel HD Graphics 630                                                | 3         | 14.29%  |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                            | 2         | 9.52%   |
| AMD Renoir                                                           | 2         | 9.52%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 1         | 4.76%   |
| Nvidia GF119 [GeForce GT 610]                                        | 1         | 4.76%   |
| Nvidia G96C [GeForce 9500 GT]                                        | 1         | 4.76%   |
| Matrox Electronics Systems MGA G200eW WPCM450                        | 1         | 4.76%   |
| Intel UHD Graphics 620                                               | 1         | 4.76%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                               | 1         | 4.76%   |
| Intel HD Graphics 500                                                | 1         | 4.76%   |
| AMD RS880 [Radeon HD 4250]                                           | 1         | 4.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 4.76%   |
| AMD Madison [Mobility Radeon HD 5730 / 6570M]                        | 1         | 4.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x Intel  | 8         | 38.1%   |
| 1 x AMD    | 5         | 23.81%  |
| 1 x ASPEED | 4         | 19.05%  |
| 1 x Nvidia | 3         | 14.29%  |
| 1 x Matrox | 1         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 21        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 95.24%  |
| 1.01-2.0   | 1         | 4.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Dell   | 1         | 100%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Dell LCD Monitor U2715H 2560x1440 | 1         | 100%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 2560x1440 (QHD) | 1         | 100%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 1         | 100%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1         | 100%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1         | 100%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 20        | 95.24%  |
| 1     | 1         | 4.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 55.56%  |
| Realtek Semiconductor | 9         | 33.33%  |
| American Megatrends   | 2         | 7.41%   |
| Broadcom              | 1         | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 29.03%  |
| Intel I350 Gigabit Network Connection                             | 2         | 6.45%   |
| Intel I211 Gigabit Network Connection                             | 2         | 6.45%   |
| Intel Ethernet Controller X550                                    | 2         | 6.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 6.45%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 6.45%   |
| American Megatrends Virtual Ethernet                              | 2         | 6.45%   |
| Intel I210 Gigabit Network Connection                             | 1         | 3.23%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 3.23%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 3.23%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 3.23%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 3.23%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.23%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.23%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 3.23%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 3.23%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 3.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 2         | 66.67%  |
| Broadcom | 1         | 33.33%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel Centrino Wireless-N 2230  | 1         | 33.33%  |
| Intel Centrino Advanced-N 6200  | 1         | 33.33%  |
| Broadcom BCM43224 802.11a/b/g/n | 1         | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 54.17%  |
| Realtek Semiconductor | 9         | 37.5%   |
| American Megatrends   | 2         | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 32.14%  |
| Intel I350 Gigabit Network Connection                             | 2         | 7.14%   |
| Intel I211 Gigabit Network Connection                             | 2         | 7.14%   |
| Intel Ethernet Controller X550                                    | 2         | 7.14%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 7.14%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 7.14%   |
| American Megatrends Virtual Ethernet                              | 2         | 7.14%   |
| Intel I210 Gigabit Network Connection                             | 1         | 3.57%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 3.57%   |
| Intel 82583V Gigabit Network Connection                           | 1         | 3.57%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 3.57%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 3.57%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 3.57%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 21        | 87.5%   |
| WiFi     | 3         | 12.5%   |

Used Controller
---------------

Currently used network controller

Zero info for selected period =(

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 21        | 100%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 19        | 90.48%  |
| Yes  | 2         | 9.52%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Intel           | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Centrino Bluetooth Wireless Transceiver | 1         | 50%     |
| HP Broadcom 2070 Bluetooth Combo              | 1         | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 8         | 47.06%  |
| Intel  | 7         | 41.18%  |
| Nvidia | 2         | 11.76%  |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 3         | 14.29%  |
| AMD Family 17h/19h HD Audio Controller                              | 3         | 14.29%  |
| Intel Alder Lake-S HD Audio Controller                              | 2         | 9.52%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 2         | 9.52%   |
| Nvidia GP108 High Definition Audio Controller                       | 1         | 4.76%   |
| Nvidia GF119 HDMI Audio Controller                                  | 1         | 4.76%   |
| Intel Sunrise Point-LP HD Audio                                     | 1         | 4.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 4.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1         | 4.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 4.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1         | 4.76%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 4.76%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                        | 1         | 4.76%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                      | 1         | 4.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 4.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston                                | 5         | 25%     |
| Samsung Electronics                     | 4         | 20%     |
| Crucial                                 | 4         | 20%     |
| SK hynix                                | 2         | 10%     |
| Silicon Power Computer & Communications | 2         | 10%     |
| Unknown (ABCD)                          | 1         | 5%      |
| Patriot                                 | 1         | 5%      |
| Micron Technology                       | 1         | 5%      |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Silicon Power & RAM Module 8GB DIMM DDR4 3200MT/s            | 2         | 9.09%   |
| Kingston RAM 9965745-026.A00G 16GB DIMM DDR4 3200MT/s        | 2         | 9.09%   |
| Crucial RAM CT16G4DFD824A.C16FHD 16GB DIMM DDR4 2400MT/s     | 2         | 9.09%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1         | 4.55%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 4.55%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 2933MT/s         | 1         | 4.55%   |
| Samsung RAM Module 32GB DIMM DDR4 2133MT/s                   | 1         | 4.55%   |
| Samsung RAM Module 2GB DIMM DDR3 400MT/s                     | 1         | 4.55%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s         | 1         | 4.55%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s         | 1         | 4.55%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s         | 1         | 4.55%   |
| Patriot RAM 1600 CL10 Series 8GB DIMM DDR3 1600MT/s          | 1         | 4.55%   |
| Micron RAM 36KDYS1G72PZ-1G4M1 8GB DIMM DDR3 1333MT/s         | 1         | 4.55%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 1         | 4.55%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s      | 1         | 4.55%   |
| Kingston RAM 9905474-050.A00LF 4GB DIMM DDR3 1333MT/s        | 1         | 4.55%   |
| Crucial RAM CT32G4DFD832A.M16FF 32GB DIMM DDR4 3200MT/s      | 1         | 4.55%   |
| Crucial RAM CT32G4DFD832A.C16FF 32GB DIMM DDR4 3200MT/s      | 1         | 4.55%   |
| Crucial RAM CT32G4DFD8266.C16FB 32GB DIMM DDR4 2666MT/s      | 1         | 4.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 70%     |
| DDR3   | 5         | 25%     |
| LPDDR4 | 1         | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 18        | 90%     |
| SODIMM | 2         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 7         | 35%     |
| 32768 | 5         | 25%     |
| 8192  | 5         | 25%     |
| 4096  | 2         | 10%     |
| 2048  | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 6         | 30%     |
| 2400  | 5         | 25%     |
| 1333  | 3         | 15%     |
| 2933  | 1         | 5%      |
| 2667  | 1         | 5%      |
| 2666  | 1         | 5%      |
| 2133  | 1         | 5%      |
| 1600  | 1         | 5%      |
| 400   | 1         | 5%      |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 10        | 47.62%  |
| 1     | 8         | 38.1%   |
| 2     | 3         | 14.29%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 11        | 91.67%  |
| Firewire controller      | 1         | 8.33%   |

