MyBee - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for MyBee.

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

Total: 25

| Vendor        | Model                    | Probe                                                     | Date         |
|---------------|--------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | P6X58D PREMIUM           | [946e123320](https://bsd-hardware.info/?probe=946e123320) | Aug 13, 2023 |
| ASRockRack    | X570D4U-2L2T             | [4cada5d71b](https://bsd-hardware.info/?probe=4cada5d71b) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T              | [e782ceaea8](https://bsd-hardware.info/?probe=e782ceaea8) | May 19, 2023 |
| Gigabyte      | H77N-WIFI                | [cf2014c973](https://bsd-hardware.info/?probe=cf2014c973) | May 04, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF         | [882a817f46](https://bsd-hardware.info/?probe=882a817f46) | Apr 13, 2023 |
| MSI           | PRO H610M-B DDR4         | [ee01b690bc](https://bsd-hardware.info/?probe=ee01b690bc) | Mar 25, 2023 |
| MSI           | PRO H610M-B DDR4         | [b08fd92e36](https://bsd-hardware.info/?probe=b08fd92e36) | Mar 10, 2023 |
| ASUSTek       | P8Z77-V PREMIUM          | [a2873d7c87](https://bsd-hardware.info/?probe=a2873d7c87) | Mar 09, 2023 |
| Huanan        | X99-QD4 V1.0             | [8404060d9e](https://bsd-hardware.info/?probe=8404060d9e) | Mar 02, 2023 |
| Unknown       | Unknown                  | [95c62844de](https://bsd-hardware.info/?probe=95c62844de) | Feb 25, 2023 |
| MSI           | PRO H610M-B DDR4         | [1deece00b3](https://bsd-hardware.info/?probe=1deece00b3) | Jan 05, 2023 |
| ASUSTek       | PRIME B550-PLUS          | [4c3b92bb42](https://bsd-hardware.info/?probe=4c3b92bb42) | Dec 24, 2022 |
| ASUSTek       | PRIME B550-PLUS          | [3e5e7e3e61](https://bsd-hardware.info/?probe=3e5e7e3e61) | Dec 22, 2022 |
| Gigabyte      | A320M-H-CF               | [2549c7cadf](https://bsd-hardware.info/?probe=2549c7cadf) | Aug 27, 2022 |
| ASUSTek       | PRIME B550-PLUS          | [7d4eaaf087](https://bsd-hardware.info/?probe=7d4eaaf087) | Aug 22, 2022 |
| ASUSTek       | PRIME B550-PLUS          | [063addc66e](https://bsd-hardware.info/?probe=063addc66e) | Aug 22, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | [e3461d0ff8](https://bsd-hardware.info/?probe=e3461d0ff8) | Jul 17, 2022 |
| Acer          | RS880M05                 | [7bcc14ceba](https://bsd-hardware.info/?probe=7bcc14ceba) | Jul 16, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | [75132f9078](https://bsd-hardware.info/?probe=75132f9078) | Jul 13, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | [7cdaeb28fa](https://bsd-hardware.info/?probe=7cdaeb28fa) | Jun 16, 2022 |
| ASRock        | X570 Phantom Gaming 4    | [067dbf3357](https://bsd-hardware.info/?probe=067dbf3357) | Jun 15, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB        | [b98e41f6a4](https://bsd-hardware.info/?probe=b98e41f6a4) | Jun 05, 2022 |
| ASRockRack    | E3C242D4U2-2T            | [66f9070856](https://bsd-hardware.info/?probe=66f9070856) | May 23, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | [ea6146e013](https://bsd-hardware.info/?probe=ea6146e013) | May 19, 2022 |
| Fujitsu       | D3401-H2 S26361-D3401-H2 | [6974f0958e](https://bsd-hardware.info/?probe=6974f0958e) | May 15, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| MyBee 13.1         | 4        | 21.05%  |
| MyBee 13.2         | 3        | 15.79%  |
| MyBee 13.1-p7      | 3        | 15.79%  |
| MyBee 14.0-CURRENT | 2        | 10.53%  |
| MyBee 13.1-p1      | 2        | 10.53%  |
| MyBee 13.2-RC5     | 1        | 5.26%   |
| MyBee 13.2-RC4     | 1        | 5.26%   |
| MyBee 13.2-RC2     | 1        | 5.26%   |
| MyBee 13.1-p5      | 1        | 5.26%   |
| MyBee 13.1-p3      | 1        | 5.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| MyBee | 18       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 18       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 17       | 94.44%  |
| KDE5    | 1        | 5.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 17       | 94.44%  |
| X11     | 1        | 5.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 18       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 17       | 94.44%  |
| C     | 1        | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 18       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 18       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 18       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 4        | 22.22%  |
| Gigabyte Technology | 3        | 16.67%  |
| MSI                 | 2        | 11.11%  |
| Fujitsu             | 2        | 11.11%  |
| ASRockRack          | 2        | 11.11%  |
| IceWhale Technology | 1        | 5.56%   |
| Huanan              | 1        | 5.56%   |
| ASRock              | 1        | 5.56%   |
| Acer                | 1        | 5.56%   |
| Unknown             | 1        | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| MSI MS-7D46                      | 2        | 11.11%  |
| Fujitsu D3401-H2 S26361-D3401-H2 | 2        | 11.11%  |
| ASUS PRIME B550-PLUS             | 2        | 11.11%  |
| IceWhale ZimaBoard 832 ZMB       | 1        | 5.56%   |
| Huanan X99-QD4 V1.0              | 1        | 5.56%   |
| Gigabyte Z170-HD3 DDR3           | 1        | 5.56%   |
| Gigabyte H77N-WIFI               | 1        | 5.56%   |
| Gigabyte A320M-H                 | 1        | 5.56%   |
| ASUS P8Z77-V PREMIUM             | 1        | 5.56%   |
| ASUS P6X58D PREMIUM              | 1        | 5.56%   |
| ASRockRack X570D4U-2L2T          | 1        | 5.56%   |
| ASRockRack X470D4U2-2T           | 1        | 5.56%   |
| ASRock X570 Phantom Gaming 4     | 1        | 5.56%   |
| Acer Veriton M430                | 1        | 5.56%   |
| Unknown                          | 1        | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| MSI MS-7D46             | 2        | 11.11%  |
| Fujitsu D3401-H2        | 2        | 11.11%  |
| ASUS PRIME              | 2        | 11.11%  |
| IceWhale ZimaBoard      | 1        | 5.56%   |
| Huanan X99-QD4          | 1        | 5.56%   |
| Gigabyte Z170-HD3       | 1        | 5.56%   |
| Gigabyte H77N-WIFI      | 1        | 5.56%   |
| Gigabyte A320M-H        | 1        | 5.56%   |
| ASUS P8Z77-V            | 1        | 5.56%   |
| ASUS P6X58D             | 1        | 5.56%   |
| ASRockRack X570D4U-2L2T | 1        | 5.56%   |
| ASRockRack X470D4U2-2T  | 1        | 5.56%   |
| ASRock X570             | 1        | 5.56%   |
| Acer Veriton            | 1        | 5.56%   |
| Unknown                 | 1        | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2022 | 4        | 22.22%  |
| 2020 | 3        | 16.67%  |
| 2018 | 3        | 16.67%  |
| 2017 | 2        | 11.11%  |
| 2021 | 1        | 5.56%   |
| 2019 | 1        | 5.56%   |
| 2013 | 1        | 5.56%   |
| 2012 | 1        | 5.56%   |
| 2011 | 1        | 5.56%   |
| 2010 | 1        | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 18       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 18       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 64.01-256.0 | 7        | 38.89%  |
| 8.01-16.0   | 6        | 33.33%  |
| 32.01-64.0  | 2        | 11.11%  |
| 4.01-8.0    | 1        | 5.56%   |
| 24.01-32.0  | 1        | 5.56%   |
| 16.01-24.0  | 1        | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 8        | 44.44%  |
| 2.01-3.0   | 4        | 22.22%  |
| 1.01-2.0   | 3        | 16.67%  |
| 16.01-24.0 | 2        | 11.11%  |
| 4.01-8.0   | 1        | 5.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 8        | 44.44%  |
| 2      | 5        | 27.78%  |
| 5      | 2        | 11.11%  |
| 3      | 2        | 11.11%  |
| 6      | 1        | 5.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 88.89%  |
| Yes       | 2        | 11.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 18       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 16       | 88.89%  |
| Yes       | 2        | 11.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 94.44%  |
| Yes       | 1        | 5.56%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Russia  | 13       | 72.22%  |
| Germany | 2        | 11.11%  |
| USA     | 1        | 5.56%   |
| Finland | 1        | 5.56%   |
| Canada  | 1        | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| St Petersburg | 9        | 50%     |
| Moscow        | 2        | 11.11%  |
| Vladivostok   | 1        | 5.56%   |
| Remscheid     | 1        | 5.56%   |
| Montreal      | 1        | 5.56%   |
| Irkutsk       | 1        | 5.56%   |
| Helsinki      | 1        | 5.56%   |
| Falkenstein   | 1        | 5.56%   |
| Clearwater    | 1        | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Toshiba             | 5        | 17     | 21.74%  |
| Seagate             | 3        | 7      | 13.04%  |
| Samsung Electronics | 3        | 4      | 13.04%  |
| WDC                 | 2        | 2      | 8.7%    |
| Kingston            | 2        | 2      | 8.7%    |
| KingSpec            | 2        | 2      | 8.7%    |
| Silicon Motion      | 1        | 2      | 4.35%   |
| Phison              | 1        | 1      | 4.35%   |
| Micron Technology   | 1        | 2      | 4.35%   |
| Intel               | 1        | 1      | 4.35%   |
| GOODRAM             | 1        | 1      | 4.35%   |
| A-DATA Technology   | 1        | 2      | 4.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Toshiba MG07ACA12TE 12TB         | 2        | 8.7%    |
| Seagate ST1000DM010-2EP102 1TB   | 2        | 8.7%    |
| Samsung SSD 980 1TB              | 2        | 8.7%    |
| WDC WDS120G2G0A-00JH30 120GB     | 1        | 4.35%   |
| WDC WD30EJRX-89AKWY0 3TB         | 1        | 4.35%   |
| Toshiba MG06ACA800E 8TB          | 1        | 4.35%   |
| Toshiba KXG50ZNV512G 512GB       | 1        | 4.35%   |
| Toshiba DT01ACA100 1TB           | 1        | 4.35%   |
| Silicon Motion PCIe SSD 256GB    | 1        | 4.35%   |
| Seagate ST500DM002-1SB10A 500GB  | 1        | 4.35%   |
| Samsung SSD 870 EVO 1TB          | 1        | 4.35%   |
| Phison PCIe SSD 128GB            | 1        | 4.35%   |
| Micron 1100_MTFDDAK512TBN 512GB  | 1        | 4.35%   |
| Kingston SA400S37480G 480GB      | 1        | 4.35%   |
| Kingston SA400S37120G 120GB      | 1        | 4.35%   |
| KingSpec P3-256 256GB            | 1        | 4.35%   |
| KingSpec MT-1TB                  | 1        | 4.35%   |
| Intel SSDPEKNW010T8 1TB          | 1        | 4.35%   |
| GOODRAM SSDPR-PX500-256-80 256GB | 1        | 4.35%   |
| A-DATA SX8200PNP 1TB             | 1        | 4.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Toshiba | 4        | 15     | 50%     |
| Seagate | 3        | 7      | 37.5%   |
| WDC     | 1        | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 2        | 2      | 28.57%  |
| KingSpec            | 2        | 2      | 28.57%  |
| WDC                 | 1        | 1      | 14.29%  |
| Samsung Electronics | 1        | 2      | 14.29%  |
| Micron Technology   | 1        | 2      | 14.29%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 8        | 11     | 36.36%  |
| SSD  | 7        | 9      | 31.82%  |
| HDD  | 7        | 23     | 31.82%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 13       | 32     | 61.9%   |
| NVMe | 8        | 11     | 38.1%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.51-1.0   | 5        | 11     | 33.33%  |
| 0.01-0.5   | 5        | 5      | 33.33%  |
| 10.01-20.0 | 2        | 10     | 13.33%  |
| 2.01-3.0   | 1        | 1      | 6.67%   |
| 1.01-2.0   | 1        | 1      | 6.67%   |
| 4.01-10.0  | 1        | 4      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 6        | 31.58%  |
| More than 3000 | 4        | 21.05%  |
| 101-250        | 4        | 21.05%  |
| 251-500        | 3        | 15.79%  |
| 1001-2000      | 2        | 10.53%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 16       | 88.89%  |
| More than 3000 | 2        | 11.11%  |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 870 EVO 1TB        | 1        | 2      | 50%     |
| Micron Technology 1100_MTFDDAK512TBN 512GB | 1        | 2      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 2      | 50%     |
| Micron Technology   | 1        | 2      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 2        | 4      | 100%    |

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


| Status  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Works   | 17       | 39     | 89.47%  |
| Malfunc | 2        | 4      | 10.53%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 10       | 38.46%  |
| AMD                      | 7        | 26.92%  |
| Silicon Motion           | 2        | 7.69%   |
| Samsung Electronics      | 2        | 7.69%   |
| Toshiba                  | 1        | 3.85%   |
| Phison Electronics       | 1        | 3.85%   |
| Marvell Technology Group | 1        | 3.85%   |
| ASMedia Technology       | 1        | 3.85%   |
| ADATA Technology         | 1        | 3.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 3        | 10.34%  |
| AMD FCH SATA Controller [AHCI mode]                                           | 3        | 10.34%  |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers             | 2        | 6.9%    |
| Samsung NVMe SSD Controller 980                                               | 2        | 6.9%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                            | 2        | 6.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]  | 2        | 6.9%    |
| AMD 500 Series Chipset SATA Controller                                        | 2        | 6.9%    |
| Toshiba XG5 NVMe SSD Controller                                               | 1        | 3.45%   |
| Phison PS5013 E13 NVMe Controller                                             | 1        | 3.45%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller         | 1        | 3.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1        | 3.45%   |
| Intel SSD 660P Series                                                         | 1        | 3.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1        | 3.45%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                             | 1        | 3.45%   |
| ASMedia ASM1062 Serial ATA Controller                                         | 1        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                              | 1        | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                          | 1        | 3.45%   |
| AMD FCH SATA Controller D                                                     | 1        | 3.45%   |
| AMD 400 Series Chipset SATA Controller                                        | 1        | 3.45%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                   | 1        | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 16       | 64%     |
| NVMe | 8        | 32%     |
| IDE  | 1        | 4%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 11       | 61.11%  |
| AMD    | 7        | 38.89%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-7700 CPU @ 3.60GHz            | 2        | 11.11%  |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2        | 11.11%  |
| Intel 12th Gen Core i5-12400                | 2        | 11.11%  |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 2        | 11.11%  |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 11.11%  |
| Intel Xeon CPU E5-2686 v4 @ 2.30GHz         | 1        | 5.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1        | 5.56%   |
| Intel Core i7 CPU 960 @ 3.20GHz             | 1        | 5.56%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 5.56%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 1        | 5.56%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 5.56%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 1        | 5.56%   |
| AMD Phenom II X6 1045T Processor            | 1        | 5.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Core i7    | 6        | 33.33%  |
| AMD Ryzen 5      | 3        | 16.67%  |
| Other            | 2        | 11.11%  |
| AMD Ryzen 5 PRO  | 2        | 11.11%  |
| Intel Xeon       | 1        | 5.56%   |
| Intel Core i5    | 1        | 5.56%   |
| Intel Celeron    | 1        | 5.56%   |
| AMD Ryzen 9      | 1        | 5.56%   |
| AMD Phenom II X6 | 1        | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 8        | 44.44%  |
| 12     | 4        | 22.22%  |
| 6      | 3        | 16.67%  |
| 24     | 1        | 5.56%   |
| 18     | 1        | 5.56%   |
| 8      | 1        | 5.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 18       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 9        | 50%     |
| 1      | 9        | 50%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name      | Desktops | Percent |
|-----------|----------|---------|
| KabyLake  | 4        | 22.22%  |
| Zen 2     | 3        | 16.67%  |
| Zen 3     | 2        | 11.11%  |
| IvyBridge | 2        | 11.11%  |
| Unknown   | 2        | 11.11%  |
| Zen+      | 1        | 5.56%   |
| Nehalem   | 1        | 5.56%   |
| K10       | 1        | 5.56%   |
| Goldmont  | 1        | 5.56%   |
| Broadwell | 1        | 5.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 8        | 44.44%  |
| Nvidia            | 4        | 22.22%  |
| AMD               | 4        | 22.22%  |
| ASPEED Technology | 2        | 11.11%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 630                                                | 3        | 16.67%  |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                            | 2        | 11.11%  |
| ASPEED Technology ASPEED Graphics Family                             | 2        | 11.11%  |
| AMD Renoir                                                           | 2        | 11.11%  |
| Nvidia GP108 [GeForce GT 1030]                                       | 1        | 5.56%   |
| Nvidia GK107GL [Quadro K600]                                         | 1        | 5.56%   |
| Nvidia GF119 [GeForce GT 610]                                        | 1        | 5.56%   |
| Nvidia G96C [GeForce 9500 GT]                                        | 1        | 5.56%   |
| Intel UHD Graphics 620                                               | 1        | 5.56%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                               | 1        | 5.56%   |
| Intel HD Graphics 500                                                | 1        | 5.56%   |
| AMD RS880 [Radeon HD 4250]                                           | 1        | 5.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series] | 1        | 5.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 8        | 44.44%  |
| 1 x Nvidia | 4        | 22.22%  |
| 1 x AMD    | 4        | 22.22%  |
| 1 x ASPEED | 2        | 11.11%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver | Desktops | Percent |
|--------|----------|---------|
| Free   | 18       | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 17       | 94.44%  |
| 1.01-2.0   | 1        | 5.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Dell   | 1        | 100%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Dell LCD Monitor U2715H 2560x1440 | 1        | 100%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 2560x1440 (QHD) | 1        | 100%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1        | 100%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 1        | 100%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1        | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 1        | 100%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1        | 100%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 17       | 94.44%  |
| 1     | 1        | 5.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 11       | 47.83%  |
| Realtek Semiconductor    | 9        | 39.13%  |
| American Megatrends      | 2        | 8.7%    |
| Marvell Technology Group | 1        | 4.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 34.62%  |
| Intel Ethernet Controller X550                                    | 2        | 7.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 7.69%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 7.69%   |
| American Megatrends Virtual Ethernet                              | 2        | 7.69%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 3.85%   |
| Intel I350 Gigabit Network Connection                             | 1        | 3.85%   |
| Intel I211 Gigabit Network Connection                             | 1        | 3.85%   |
| Intel I210 Gigabit Network Connection                             | 1        | 3.85%   |
| Intel Centrino Wireless-N 2230                                    | 1        | 3.85%   |
| Intel Centrino Advanced-N 6200                                    | 1        | 3.85%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 3.85%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 3.85%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 3.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2        | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                          | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel Centrino Wireless-N 2230 | 1        | 50%     |
| Intel Centrino Advanced-N 6200 | 1        | 50%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 9        | 42.86%  |
| Intel                    | 9        | 42.86%  |
| American Megatrends      | 2        | 9.52%   |
| Marvell Technology Group | 1        | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9        | 37.5%   |
| Intel Ethernet Controller X550                                    | 2        | 8.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 8.33%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 8.33%   |
| American Megatrends Virtual Ethernet                              | 2        | 8.33%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 4.17%   |
| Intel I350 Gigabit Network Connection                             | 1        | 4.17%   |
| Intel I211 Gigabit Network Connection                             | 1        | 4.17%   |
| Intel I210 Gigabit Network Connection                             | 1        | 4.17%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 4.17%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 4.17%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 18       | 90%     |
| WiFi     | 2        | 10%     |

Used Controller
---------------

Currently used network controller

Zero info for selected period =(

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 18       | 100%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 83.33%  |
| Yes  | 3        | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Centrino Bluetooth Wireless Transceiver | 1        | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 8        | 44.44%  |
| AMD    | 7        | 38.89%  |
| Nvidia | 3        | 16.67%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                            | 3        | 13.64%  |
| AMD Family 17h/19h HD Audio Controller                              | 3        | 13.64%  |
| Intel Alder Lake-S HD Audio Controller                              | 2        | 9.09%   |
| AMD Renoir Radeon High Definition Audio Controller                  | 2        | 9.09%   |
| Nvidia GP108 High Definition Audio Controller                       | 1        | 4.55%   |
| Nvidia GK107 HDMI Audio Controller                                  | 1        | 4.55%   |
| Nvidia GF119 HDMI Audio Controller                                  | 1        | 4.55%   |
| Intel Sunrise Point-LP HD Audio                                     | 1        | 4.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster   | 1        | 4.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                    | 1        | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller | 1        | 4.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller | 1        | 4.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller     | 1        | 4.55%   |
| AMD SBx00 Azalia (Intel HDA)                                        | 1        | 4.55%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                        | 1        | 4.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                 | 1        | 4.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Kingston                                | 5        | 29.41%  |
| Crucial                                 | 4        | 23.53%  |
| Silicon Power Computer & Communications | 2        | 11.76%  |
| Samsung Electronics                     | 2        | 11.76%  |
| Unknown (ABCD)                          | 1        | 5.88%   |
| SK hynix                                | 1        | 5.88%   |
| Patriot                                 | 1        | 5.88%   |
| Unknown                                 | 1        | 5.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Silicon Power & RAM Module 8GB DIMM DDR4 3200MT/s              | 2        | 10.53%  |
| Kingston RAM 9965745-026.A00G 16GB DIMM DDR4 3200MT/s          | 2        | 10.53%  |
| Crucial RAM CT16G4DFD824A.C16FHD 16GB DIMM DDR4 2400MT/s       | 2        | 10.53%  |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1        | 5.26%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 2933MT/s           | 1        | 5.26%   |
| Samsung RAM Module 2GB DIMM DDR3 400MT/s                       | 1        | 5.26%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s           | 1        | 5.26%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s           | 1        | 5.26%   |
| Patriot RAM 1600 CL10 Series 8GB DIMM DDR3 1600MT/s            | 1        | 5.26%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s         | 1        | 5.26%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s        | 1        | 5.26%   |
| Kingston RAM 9905474-050.A00LF 4GB DIMM DDR3 1333MT/s          | 1        | 5.26%   |
| Crucial RAM CT32G4DFD832A.M16FF 32GB DIMM DDR4 3200MT/s        | 1        | 5.26%   |
| Crucial RAM CT32G4DFD832A.C16FF 32GB DIMM DDR4 3200MT/s        | 1        | 5.26%   |
| Crucial RAM CT32G4DFD8266.C16FB 32GB DIMM DDR4 2666MT/s        | 1        | 5.26%   |
| Unknown                                                        | 1        | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 12       | 70.59%  |
| DDR3    | 3        | 17.65%  |
| LPDDR4  | 1        | 5.88%   |
| Unknown | 1        | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 16       | 94.12%  |
| SODIMM | 1        | 5.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 6        | 35.29%  |
| 32768 | 4        | 23.53%  |
| 8192  | 4        | 23.53%  |
| 4096  | 2        | 11.76%  |
| 2048  | 1        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 6        | 35.29%  |
| 2400  | 5        | 29.41%  |
| 2933  | 1        | 5.88%   |
| 2666  | 1        | 5.88%   |
| 1600  | 1        | 5.88%   |
| 1333  | 1        | 5.88%   |
| 1066  | 1        | 5.88%   |
| 400   | 1        | 5.88%   |

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


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 10       | 55.56%  |
| 1     | 8        | 44.44%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 8        | 100%    |
