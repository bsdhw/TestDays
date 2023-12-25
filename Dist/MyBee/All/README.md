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

Total: 38

| Vendor        | Model                    | Form-Factor | Probe                                                     | Date         |
|---------------|--------------------------|-------------|-----------------------------------------------------------|--------------|
| MSI           | PRO H610M-B DDR4         | Desktop     | [c6ff092502](https://bsd-hardware.info/?probe=c6ff092502) | Nov 26, 2023 |
| Intel         | S5520UR E22554-752       | Server      | [8e20922890](https://bsd-hardware.info/?probe=8e20922890) | Oct 20, 2023 |
| ASRockRack    | X470D4U2-2T              | Desktop     | [c07dd3b911](https://bsd-hardware.info/?probe=c07dd3b911) | Oct 09, 2023 |
| Intel         | S5520UR E22554-752       | Server      | [ab0b5c4d36](https://bsd-hardware.info/?probe=ab0b5c4d36) | Sep 27, 2023 |
| Intel         | S5520UR E22554-753       | Server      | [4094543b6f](https://bsd-hardware.info/?probe=4094543b6f) | Sep 25, 2023 |
| ASUSTek       | P9D-MV Series            | Server      | [bccf02e740](https://bsd-hardware.info/?probe=bccf02e740) | Sep 25, 2023 |
| ASRock        | Z690 Phantom Gaming 4/D5 | Desktop     | [6eab8daef7](https://bsd-hardware.info/?probe=6eab8daef7) | Sep 21, 2023 |
| ASRockRack    | X470D4U2-2T              | Desktop     | [5a0b8eb786](https://bsd-hardware.info/?probe=5a0b8eb786) | Sep 21, 2023 |
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
| MyBee 13.1         | 7         | 22.58%  |
| MyBee 13.2         | 6         | 19.35%  |
| MyBee 14.0-BETA2   | 3         | 9.68%   |
| MyBee 13.1-p7      | 3         | 9.68%   |
| MyBee 14.0-CURRENT | 2         | 6.45%   |
| MyBee 13.1-p1      | 2         | 6.45%   |
| MyBee 14.0-BETA5   | 1         | 3.23%   |
| MyBee 14.0-BETA3   | 1         | 3.23%   |
| MyBee 14.0         | 1         | 3.23%   |
| MyBee 13.2-RC5     | 1         | 3.23%   |
| MyBee 13.2-RC4     | 1         | 3.23%   |
| MyBee 13.2-RC2     | 1         | 3.23%   |
| MyBee 13.1-p5      | 1         | 3.23%   |
| MyBee 13.1-p3      | 1         | 3.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| MyBee | 27        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 27        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 26        | 96.3%   |
| KDE5    | 1         | 3.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 26        | 96.3%   |
| X11     | 1         | 3.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 27        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 25        | 92.59%  |
| C     | 2         | 7.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 27        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 27        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 27        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 4         | 14.81%  |
| ASUSTek Computer    | 4         | 14.81%  |
| Gigabyte Technology | 3         | 11.11%  |
| Supermicro          | 2         | 7.41%   |
| MSI                 | 2         | 7.41%   |
| Fujitsu             | 2         | 7.41%   |
| ASRockRack          | 2         | 7.41%   |
| ASRock              | 2         | 7.41%   |
| Insyde              | 1         | 3.7%    |
| IceWhale Technology | 1         | 3.7%    |
| Huanan              | 1         | 3.7%    |
| Hewlett-Packard     | 1         | 3.7%    |
| Acer                | 1         | 3.7%    |
| Unknown             | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel S5520UR                    | 3         | 11.11%  |
| MSI MS-7D46                      | 2         | 7.41%   |
| Fujitsu D3401-H2 S26361-D3401-H2 | 2         | 7.41%   |
| ASUS PRIME B550-PLUS             | 2         | 7.41%   |
| Supermicro Super Server          | 1         | 3.7%    |
| Supermicro H8DGU                 | 1         | 3.7%    |
| Intel S3210SH                    | 1         | 3.7%    |
| Insyde Purley                    | 1         | 3.7%    |
| IceWhale ZimaBoard 832 ZMB       | 1         | 3.7%    |
| Huanan X99-QD4 V1.0              | 1         | 3.7%    |
| HP EliteBook 8540w               | 1         | 3.7%    |
| Gigabyte Z170-HD3 DDR3           | 1         | 3.7%    |
| Gigabyte H77N-WIFI               | 1         | 3.7%    |
| Gigabyte A320M-H                 | 1         | 3.7%    |
| ASUS P8Z77-V PREMIUM             | 1         | 3.7%    |
| ASUS P6X58D PREMIUM              | 1         | 3.7%    |
| ASRockRack X570D4U-2L2T          | 1         | 3.7%    |
| ASRockRack X470D4U2-2T           | 1         | 3.7%    |
| ASRock Z690 Phantom Gaming 4/D5  | 1         | 3.7%    |
| ASRock X570 Phantom Gaming 4     | 1         | 3.7%    |
| Acer Veriton M430                | 1         | 3.7%    |
| Unknown                          | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Intel S5520UR           | 3         | 11.11%  |
| MSI MS-7D46             | 2         | 7.41%   |
| Fujitsu D3401-H2        | 2         | 7.41%   |
| ASUS PRIME              | 2         | 7.41%   |
| Supermicro Super        | 1         | 3.7%    |
| Supermicro H8DGU        | 1         | 3.7%    |
| Intel S3210SH           | 1         | 3.7%    |
| Insyde Purley           | 1         | 3.7%    |
| IceWhale ZimaBoard      | 1         | 3.7%    |
| Huanan X99-QD4          | 1         | 3.7%    |
| HP EliteBook            | 1         | 3.7%    |
| Gigabyte Z170-HD3       | 1         | 3.7%    |
| Gigabyte H77N-WIFI      | 1         | 3.7%    |
| Gigabyte A320M-H        | 1         | 3.7%    |
| ASUS P8Z77-V            | 1         | 3.7%    |
| ASUS P6X58D             | 1         | 3.7%    |
| ASRockRack X570D4U-2L2T | 1         | 3.7%    |
| ASRockRack X470D4U2-2T  | 1         | 3.7%    |
| ASRock Z690             | 1         | 3.7%    |
| ASRock X570             | 1         | 3.7%    |
| Acer Veriton            | 1         | 3.7%    |
| Unknown                 | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 5         | 18.52%  |
| 2020 | 4         | 14.81%  |
| 2018 | 3         | 11.11%  |
| 2017 | 3         | 11.11%  |
| 2014 | 2         | 7.41%   |
| 2013 | 2         | 7.41%   |
| 2012 | 2         | 7.41%   |
| 2010 | 2         | 7.41%   |
| 2021 | 1         | 3.7%    |
| 2019 | 1         | 3.7%    |
| 2011 | 1         | 3.7%    |
| 2009 | 1         | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 19        | 70.37%  |
| Server   | 7         | 25.93%  |
| Notebook | 1         | 3.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 27        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 64.01-256.0     | 12        | 44.44%  |
| 8.01-16.0       | 8         | 29.63%  |
| 32.01-64.0      | 3         | 11.11%  |
| More than 256.0 | 1         | 3.7%    |
| 4.01-8.0        | 1         | 3.7%    |
| 24.01-32.0      | 1         | 3.7%    |
| 16.01-24.0      | 1         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 10        | 37.04%  |
| 4.01-8.0   | 5         | 18.52%  |
| 2.01-3.0   | 4         | 14.81%  |
| 1.01-2.0   | 4         | 14.81%  |
| 16.01-24.0 | 3         | 11.11%  |
| 8.01-16.0  | 1         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 9         | 31.03%  |
| 1      | 8         | 27.59%  |
| 0      | 4         | 13.79%  |
| 3      | 3         | 10.34%  |
| 5      | 2         | 6.9%    |
| 4      | 2         | 6.9%    |
| 6      | 1         | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 88.89%  |
| Yes       | 3         | 11.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 24        | 88.89%  |
| Yes       | 3         | 11.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 25        | 92.59%  |
| Yes       | 2         | 7.41%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 20        | 74.07%  |
| Germany | 3         | 11.11%  |
| USA     | 1         | 3.7%    |
| Iceland | 1         | 3.7%    |
| Finland | 1         | 3.7%    |
| Canada  | 1         | 3.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| St Petersburg       | 10        | 37.04%  |
| Moscow              | 6         | 22.22%  |
| Vladivostok         | 1         | 3.7%    |
| Rostov-on-Don       | 1         | 3.7%    |
| Reykjavik           | 1         | 3.7%    |
| Remscheid           | 1         | 3.7%    |
| Naberezhnyye Chelny | 1         | 3.7%    |
| Montreal            | 1         | 3.7%    |
| Limburg an der Lahn | 1         | 3.7%    |
| Irkutsk             | 1         | 3.7%    |
| Helsinki            | 1         | 3.7%    |
| Falkenstein         | 1         | 3.7%    |
| Clearwater          | 1         | 3.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 15     | 19.35%  |
| Toshiba             | 5         | 17     | 16.13%  |
| Samsung Electronics | 4         | 6      | 12.9%   |
| Kingston            | 4         | 7      | 12.9%   |
| WDC                 | 2         | 2      | 6.45%   |
| KingSpec            | 2         | 2      | 6.45%   |
| Intel               | 2         | 3      | 6.45%   |
| Silicon Motion      | 1         | 2      | 3.23%   |
| Phison              | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 2      | 3.23%   |
| HGST                | 1         | 2      | 3.23%   |
| GOODRAM             | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 2      | 3.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Toshiba MG07ACA12TE 12TB         | 2         | 6.45%   |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 6.45%   |
| Samsung SSD 980 1TB              | 2         | 6.45%   |
| WDC WDS120G2G0A-00JH30 120GB     | 1         | 3.23%   |
| WDC WD30EJRX-89AKWY0 3TB         | 1         | 3.23%   |
| Toshiba MG06ACA800E 8TB          | 1         | 3.23%   |
| Toshiba KXG50ZNV512G 512GB       | 1         | 3.23%   |
| Toshiba DT01ACA100 1TB           | 1         | 3.23%   |
| Silicon Motion PCIe SSD 256GB    | 1         | 3.23%   |
| Seagate ST500DM002-1SB10A 500GB  | 1         | 3.23%   |
| Seagate ST2000DM008-2UB102 2TB   | 1         | 3.23%   |
| Seagate ST1000NM0033-9ZM173 1TB  | 1         | 3.23%   |
| Seagate ST1000LM048-2E7172 1TB   | 1         | 3.23%   |
| Samsung SSD 970 EVO Plus 1TB     | 1         | 3.23%   |
| Samsung SSD 870 EVO 1TB          | 1         | 3.23%   |
| Phison PCIe SSD 512GB            | 1         | 3.23%   |
| Micron 1100_MTFDDAK512TBN 512GB  | 1         | 3.23%   |
| Kingston SNV425S2128GB           | 1         | 3.23%   |
| Kingston SA400S37480G 480GB      | 1         | 3.23%   |
| Kingston SA400S37240G 240GB      | 1         | 3.23%   |
| Kingston SA400S37120G 120GB      | 1         | 3.23%   |
| KingSpec P3-256 256GB            | 1         | 3.23%   |
| KingSpec MT-1TB                  | 1         | 3.23%   |
| Intel SSDPEKNW010T8 1TB          | 1         | 3.23%   |
| Intel SSDPE2MX450G7 450GB        | 1         | 3.23%   |
| HGST HUS726T4TALA6L1 4TB         | 1         | 3.23%   |
| GOODRAM SSDPR-PX500-256-80 256GB | 1         | 3.23%   |
| A-DATA SX8200PNP 1TB             | 1         | 3.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 15     | 50%     |
| Toshiba | 4         | 15     | 33.33%  |
| WDC     | 1         | 1      | 8.33%   |
| HGST    | 1         | 2      | 8.33%   |

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
| HDD  | 11        | 33     | 36.67%  |
| NVMe | 10        | 15     | 33.33%  |
| SSD  | 9         | 14     | 30%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 19        | 47     | 65.52%  |
| NVMe | 10        | 15     | 34.48%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 7         | 17     | 33.33%  |
| 0.01-0.5   | 7         | 10     | 33.33%  |
| 10.01-20.0 | 2         | 10     | 9.52%   |
| 1.01-2.0   | 2         | 3      | 9.52%   |
| 3.01-4.0   | 1         | 2      | 4.76%   |
| 2.01-3.0   | 1         | 1      | 4.76%   |
| 4.01-10.0  | 1         | 4      | 4.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 9         | 32.14%  |
| More than 3000 | 6         | 21.43%  |
| 101-250        | 5         | 17.86%  |
| 251-500        | 4         | 14.29%  |
| 1001-2000      | 2         | 7.14%   |
| 21-50          | 1         | 3.57%   |
| 2001-3000      | 1         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 92.59%  |
| More than 3000 | 2         | 7.41%   |

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
| Works   | 23        | 58     | 92%     |
| Malfunc | 2         | 4      | 8%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 18        | 45%     |
| AMD                      | 8         | 20%     |
| Broadcom / LSI           | 4         | 10%     |
| Samsung Electronics      | 3         | 7.5%    |
| Silicon Motion           | 2         | 5%      |
| Toshiba                  | 1         | 2.5%    |
| Phison Electronics       | 1         | 2.5%    |
| Marvell Technology Group | 1         | 2.5%    |
| ASMedia Technology       | 1         | 2.5%    |
| ADATA Technology         | 1         | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3         | 6.52%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                            | 3         | 6.52%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                             | 3         | 6.52%   |
| Broadcom / LSI MegaRAID SAS 2108 [Liberator]                                  | 3         | 6.52%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 3         | 6.52%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 2         | 4.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                   | 2         | 4.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 2         | 4.35%   |
| AMD 500 Series Chipset SATA Controller                                        | 2         | 4.35%   |
| Toshiba XG5 NVMe SSD Controller                                               | 1         | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 1         | 2.17%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                           | 1         | 2.17%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller         | 1         | 2.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 2.17%   |
| Intel SSD 660P Series                                                         | 1         | 2.17%   |
| Intel PCIe Data Center SSD                                                    | 1         | 2.17%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 2.17%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                  | 1         | 2.17%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                    | 1         | 2.17%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]              | 1         | 2.17%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                    | 1         | 2.17%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                    | 1         | 2.17%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]          | 1         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 1         | 2.17%   |
| Broadcom / LSI MegaRAID 12GSAS/PCIe Secure SAS39xx                            | 1         | 2.17%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1         | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 1         | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1         | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 1         | 2.17%   |
| AMD FCH SATA Controller D                                                     | 1         | 2.17%   |
| AMD 400 Series Chipset SATA Controller                                        | 1         | 2.17%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1         | 2.17%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 24        | 60%     |
| NVMe | 10        | 25%     |
| RAID | 4         | 10%     |
| IDE  | 2         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 19        | 70.37%  |
| AMD    | 8         | 29.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Xeon CPU E5645 @ 2.40GHz              | 3         | 11.11%  |
| Intel Core i7-7700 CPU @ 3.60GHz            | 2         | 7.41%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 7.41%   |
| Intel 12th Gen Core i5-12400                | 2         | 7.41%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 2         | 7.41%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2         | 7.41%   |
| Intel Xeon Gold 6226R CPU @ 2.90GHz         | 1         | 3.7%    |
| Intel Xeon CPU E5-2686 v4 @ 2.30GHz         | 1         | 3.7%    |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz         | 1         | 3.7%    |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 3.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 3.7%    |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 3.7%    |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1         | 3.7%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 3.7%    |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1         | 3.7%    |
| Intel 12th Gen Core i9-12900K               | 1         | 3.7%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 3.7%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1         | 3.7%    |
| AMD Phenom II X6 1045T Processor            | 1         | 3.7%    |
| AMD Opteron Processor 6176                  | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 7         | 25.93%  |
| Intel Xeon              | 5         | 18.52%  |
| Other                   | 3         | 11.11%  |
| AMD Ryzen 5             | 3         | 11.11%  |
| AMD Ryzen 5 PRO         | 2         | 7.41%   |
| Intel Xeon Gold         | 1         | 3.7%    |
| Intel Pentium Dual-Core | 1         | 3.7%    |
| Intel Core i5           | 1         | 3.7%    |
| Intel Celeron           | 1         | 3.7%    |
| AMD Ryzen 9             | 1         | 3.7%    |
| AMD Phenom II X6        | 1         | 3.7%    |
| AMD Opteron             | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 12     | 8         | 29.63%  |
| 4      | 8         | 29.63%  |
| 6      | 4         | 14.81%  |
| 24     | 2         | 7.41%   |
| 2      | 2         | 7.41%   |
| 32     | 1         | 3.7%    |
| 18     | 1         | 3.7%    |
| 8      | 1         | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 22        | 81.48%  |
| 2      | 5         | 18.52%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 16        | 59.26%  |
| 1      | 11        | 40.74%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Westmere  | 4         | 14.81%  |
| KabyLake  | 4         | 14.81%  |
| Zen 2     | 3         | 11.11%  |
| Unknown   | 3         | 11.11%  |
| Zen 3     | 2         | 7.41%   |
| K10       | 2         | 7.41%   |
| IvyBridge | 2         | 7.41%   |
| Broadwell | 2         | 7.41%   |
| Zen+      | 1         | 3.7%    |
| Skylake   | 1         | 3.7%    |
| Penryn    | 1         | 3.7%    |
| Nehalem   | 1         | 3.7%    |
| Goldmont  | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 9         | 33.33%  |
| Matrox Electronics Systems | 5         | 18.52%  |
| AMD                        | 5         | 18.52%  |
| Nvidia                     | 4         | 14.81%  |
| ASPEED Technology          | 4         | 14.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)    | 4         | 14.81%  |
| ASPEED Technology ASPEED Graphics Family                             | 4         | 14.81%  |
| Intel HD Graphics 630                                                | 3         | 11.11%  |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                            | 2         | 7.41%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]        | 2         | 7.41%   |
| Nvidia GP108 [GeForce GT 1030]                                       | 1         | 3.7%    |
| Nvidia GK107GL [Quadro K600]                                         | 1         | 3.7%    |
| Nvidia GF119 [GeForce GT 610]                                        | 1         | 3.7%    |
| Nvidia G96C [GeForce 9500 GT]                                        | 1         | 3.7%    |
| Matrox Electronics Systems MGA G200eW WPCM450                        | 1         | 3.7%    |
| Intel UHD Graphics 620                                               | 1         | 3.7%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                               | 1         | 3.7%    |
| Intel HD Graphics 500                                                | 1         | 3.7%    |
| Intel AlderLake-S GT1                                                | 1         | 3.7%    |
| AMD RS880 [Radeon HD 4250]                                           | 1         | 3.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 3.7%    |
| AMD Madison [Mobility Radeon HD 5730 / 6570M]                        | 1         | 3.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| 1 x Intel  | 9         | 33.33%  |
| 1 x Matrox | 5         | 18.52%  |
| 1 x AMD    | 5         | 18.52%  |
| 1 x Nvidia | 4         | 14.81%  |
| 1 x ASPEED | 4         | 14.81%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver | Computers | Percent |
|--------|-----------|---------|
| Free   | 27        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 26        | 96.3%   |
| 1.01-2.0   | 1         | 3.7%    |

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
| 0     | 26        | 96.3%   |
| 1     | 1         | 3.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 20        | 58.82%  |
| Realtek Semiconductor    | 10        | 29.41%  |
| American Megatrends      | 2         | 5.88%   |
| Marvell Technology Group | 1         | 2.94%   |
| Broadcom                 | 1         | 2.94%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 22.5%   |
| Intel Ethernet Connection (17) I219-V                             | 3         | 7.5%    |
| Intel 82575EB Gigabit Network Connection                          | 3         | 7.5%    |
| Intel I350 Gigabit Network Connection                             | 2         | 5%      |
| Intel I211 Gigabit Network Connection                             | 2         | 5%      |
| Intel Ethernet Controller X550                                    | 2         | 5%      |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 5%      |
| American Megatrends Virtual Ethernet                              | 2         | 5%      |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 2.5%    |
| Intel I210 Gigabit Network Connection                             | 1         | 2.5%    |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 2.5%    |
| Intel Centrino Wireless-N 2230                                    | 1         | 2.5%    |
| Intel Centrino Advanced-N 6200                                    | 1         | 2.5%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 2.5%    |
| Intel 82583V Gigabit Network Connection                           | 1         | 2.5%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.5%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.5%    |
| Intel 82576 Gigabit Network Connection                            | 1         | 2.5%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.5%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 2.5%    |
| Intel 82541GI Gigabit Ethernet Controller                         | 1         | 2.5%    |
| Broadcom BCM43224 802.11a/b/g/n                                   | 1         | 2.5%    |

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
| Intel                    | 18        | 58.06%  |
| Realtek Semiconductor    | 10        | 32.26%  |
| American Megatrends      | 2         | 6.45%   |
| Marvell Technology Group | 1         | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 24.32%  |
| Intel Ethernet Connection (17) I219-V                             | 3         | 8.11%   |
| Intel 82575EB Gigabit Network Connection                          | 3         | 8.11%   |
| Intel I350 Gigabit Network Connection                             | 2         | 5.41%   |
| Intel I211 Gigabit Network Connection                             | 2         | 5.41%   |
| Intel Ethernet Controller X550                                    | 2         | 5.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 5.41%   |
| American Megatrends Virtual Ethernet                              | 2         | 5.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 2.7%    |
| Intel I210 Gigabit Network Connection                             | 1         | 2.7%    |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 2.7%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1         | 2.7%    |
| Intel 82583V Gigabit Network Connection                           | 1         | 2.7%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 2.7%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.7%    |
| Intel 82576 Gigabit Network Connection                            | 1         | 2.7%    |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.7%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 2.7%    |
| Intel 82541GI Gigabit Ethernet Controller                         | 1         | 2.7%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 27        | 90%     |
| WiFi     | 3         | 10%     |

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
| 0     | 27        | 100%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 24        | 85.71%  |
| Yes  | 4         | 14.29%  |

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
| Intel  | 9         | 45%     |
| AMD    | 8         | 40%     |
| Nvidia | 3         | 15%     |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-S HD Audio Controller                              | 3         | 12.5%   |
| AMD Starship/Matisse HD Audio Controller                            | 3         | 12.5%   |
| AMD Family 17h/19h HD Audio Controller                              | 3         | 12.5%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 2         | 8.33%   |
| Nvidia GP108 High Definition Audio Controller                       | 1         | 4.17%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1         | 4.17%   |
| Nvidia GF119 HDMI Audio Controller                                  | 1         | 4.17%   |
| Intel Sunrise Point-LP HD Audio                                     | 1         | 4.17%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1         | 4.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1         | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1         | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1         | 4.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1         | 4.17%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1         | 4.17%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                        | 1         | 4.17%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                      | 1         | 4.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1         | 4.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston                                | 7         | 26.92%  |
| Samsung Electronics                     | 6         | 23.08%  |
| Crucial                                 | 4         | 15.38%  |
| SK hynix                                | 2         | 7.69%   |
| Silicon Power Computer & Communications | 2         | 7.69%   |
| Micron Technology                       | 2         | 7.69%   |
| Unknown (ABCD)                          | 1         | 3.85%   |
| Patriot                                 | 1         | 3.85%   |
| Unknown                                 | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Silicon Power & RAM Module 8GB DIMM DDR4 3200MT/s              | 2         | 5.88%   |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM 1866MT/s                | 2         | 5.88%   |
| Samsung RAM M393B2G70DB0-CMA 16GB DIMM 1866MT/s                | 2         | 5.88%   |
| Samsung RAM M393B2G70BH0-YK0 16GB DIMM 1600MT/s                | 2         | 5.88%   |
| Kingston RAM 9965745-026.A00G 16GB DIMM DDR4 3200MT/s          | 2         | 5.88%   |
| Crucial RAM CT16G4DFD824A.C16FHD 16GB DIMM DDR4 2400MT/s       | 2         | 5.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 2.94%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 2.94%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 2933MT/s           | 1         | 2.94%   |
| Samsung RAM Module 32GB DIMM DDR4 2133MT/s                     | 1         | 2.94%   |
| Samsung RAM Module 2GB DIMM DDR3 400MT/s                       | 1         | 2.94%   |
| Samsung RAM M393B2G70DB0-YK0 16GB DIMM DDR3 1600MT/s           | 1         | 2.94%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s           | 1         | 2.94%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s           | 1         | 2.94%   |
| Samsung RAM M393A2K40BB2-CTD 16GB DIMM DDR4 2667MT/s           | 1         | 2.94%   |
| Patriot RAM 1600 CL10 Series 8GB DIMM DDR3 1600MT/s            | 1         | 2.94%   |
| Micron RAM 36KSF2G72PZ-1G6N1 16GB DIMM 1600MT/s                | 1         | 2.94%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM 1600MT/s                | 1         | 2.94%   |
| Micron RAM 36KDYS1G72PZ-1G4M1 8GB DIMM DDR3 1333MT/s           | 1         | 2.94%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                      | 1         | 2.94%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 1         | 2.94%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s        | 1         | 2.94%   |
| Kingston RAM 9905782-018.A00G 32GB DIMM DDR5 4800MT/s          | 1         | 2.94%   |
| Kingston RAM 9905474-050.A00LF 4GB DIMM DDR3 1333MT/s          | 1         | 2.94%   |
| Crucial RAM CT32G4DFD832A.M16FF 32GB DIMM DDR4 3200MT/s        | 1         | 2.94%   |
| Crucial RAM CT32G4DFD832A.C16FF 32GB DIMM DDR4 3200MT/s        | 1         | 2.94%   |
| Crucial RAM CT32G4DFD8266.C16FB 32GB DIMM DDR4 2666MT/s        | 1         | 2.94%   |
| Unknown                                                        | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 14        | 53.85%  |
| DDR3    | 8         | 30.77%  |
| LPDDR4  | 1         | 3.85%   |
| DDR5    | 1         | 3.85%   |
| DDR2    | 1         | 3.85%   |
| Unknown | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 24        | 92.31%  |
| SODIMM | 2         | 7.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 10        | 38.46%  |
| 32768 | 6         | 23.08%  |
| 8192  | 5         | 19.23%  |
| 4096  | 3         | 11.54%  |
| 2048  | 2         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 6         | 21.43%  |
| 2400  | 5         | 17.86%  |
| 1600  | 4         | 14.29%  |
| 1333  | 3         | 10.71%  |
| 1866  | 2         | 7.14%   |
| 4800  | 1         | 3.57%   |
| 2933  | 1         | 3.57%   |
| 2667  | 1         | 3.57%   |
| 2666  | 1         | 3.57%   |
| 2133  | 1         | 3.57%   |
| 1066  | 1         | 3.57%   |
| 800   | 1         | 3.57%   |
| 400   | 1         | 3.57%   |

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
| 0     | 15        | 55.56%  |
| 1     | 8         | 29.63%  |
| 2     | 4         | 14.81%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 12        | 85.71%  |
| Net/ethernet             | 1         | 7.14%   |
| Firewire controller      | 1         | 7.14%   |

