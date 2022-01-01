OpenBSD 7.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | TI AM335x BeagleBone Bla... | [14d6cfb7a4](https://bsd-hardware.info/?probe=14d6cfb7a4) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [ce75fa56bd](https://bsd-hardware.info/?probe=ce75fa56bd) | Dec 27, 2021 |
| Unknown       | TI AM335x BeagleBone Bla... | [612825abe3](https://bsd-hardware.info/?probe=612825abe3) | Dec 27, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING     | [2ee4c7fefe](https://bsd-hardware.info/?probe=2ee4c7fefe) | Dec 27, 2021 |
| PC Engines    | APU2                        | [d271c4a29f](https://bsd-hardware.info/?probe=d271c4a29f) | Dec 15, 2021 |
| Gigabyte      | H81M-S2PV                   | [0d4c532744](https://bsd-hardware.info/?probe=0d4c532744) | Nov 29, 2021 |
| MSI           | MS-7C56                     | [d4e3f14ad4](https://bsd-hardware.info/?probe=d4e3f14ad4) | Nov 23, 2021 |
| PC Engines    | APU2                        | [15a26da041](https://bsd-hardware.info/?probe=15a26da041) | Nov 14, 2021 |
| Unknown       | Hardkernel ODROID-N2        | [42f6e357c9](https://bsd-hardware.info/?probe=42f6e357c9) | Nov 05, 2021 |
| Yanling       | YL-KBR6L                    | [35f1c905eb](https://bsd-hardware.info/?probe=35f1c905eb) | Nov 04, 2021 |
| HP            | 0A60h                       | [5c227c5b61](https://bsd-hardware.info/?probe=5c227c5b61) | Oct 27, 2021 |
| Lenovo        | SHARKBAY No DPK             | [e762f9146e](https://bsd-hardware.info/?probe=e762f9146e) | Oct 16, 2021 |
| ASUSTek       | P10S-I Series               | [d086bf947a](https://bsd-hardware.info/?probe=d086bf947a) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H                  | [445b53ddba](https://bsd-hardware.info/?probe=445b53ddba) | Oct 15, 2021 |
| Protectli     | FW6                         | [de39c4e316](https://bsd-hardware.info/?probe=de39c4e316) | Oct 15, 2021 |
| MSI           | MS-7D54                     | [ac1f6ee8a6](https://bsd-hardware.info/?probe=ac1f6ee8a6) | Oct 13, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | [49173900e7](https://bsd-hardware.info/?probe=49173900e7) | Oct 04, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B      | [d05a877535](https://bsd-hardware.info/?probe=d05a877535) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [46672cf89f](https://bsd-hardware.info/?probe=46672cf89f) | Oct 01, 2021 |
| Gigabyte      | BRi3(H)-10110               | [9aa3540749](https://bsd-hardware.info/?probe=9aa3540749) | Sep 09, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 11       | 73.33%  |
| arm64 | 2        | 13.33%  |
| i386  | 1        | 6.67%   |
| armv7 | 1        | 6.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| fvwm    | 9        | 60%     |
| Console | 5        | 33.33%  |
| XFCE    | 1        | 6.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 8        | 53.33%  |
| Console | 7        | 46.67%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 14       | 93.33%  |
| SLiM    | 1        | 6.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 86.67%  |
| ru_RU   | 1        | 6.67%   |
| de_DE   | 1        | 6.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 8        | 53.33%  |
| BIOS | 7        | 46.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 15       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 9        | 60%     |
| GPT  | 6        | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Gigabyte Technology     | 4        | 26.67%  |
| MSI                     | 2        | 13.33%  |
| Unknown                 | 2        | 13.33%  |
| Yanling                 | 1        | 6.67%   |
| Raspberry Pi Foundation | 1        | 6.67%   |
| Protectli               | 1        | 6.67%   |
| PC Engines              | 1        | 6.67%   |
| Lenovo                  | 1        | 6.67%   |
| Hewlett-Packard         | 1        | 6.67%   |
| ASUSTek Computer        | 1        | 6.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 2        | 13.33%  |
| Yanling YL-KBR6L                   | 1        | 6.67%   |
| RPi Raspberry Pi 4 Model B         | 1        | 6.67%   |
| Protectli FW6                      | 1        | 6.67%   |
| PC Engines APU2                    | 1        | 6.67%   |
| MSI MS-7D54                        | 1        | 6.67%   |
| MSI MS-7C56                        | 1        | 6.67%   |
| Lenovo ThinkCentre M73z 10BB001DRU | 1        | 6.67%   |
| HP Compaq dc5700 Microtower        | 1        | 6.67%   |
| Gigabyte X470 AORUS ULTRA GAMING   | 1        | 6.67%   |
| Gigabyte H81M-S2PV                 | 1        | 6.67%   |
| Gigabyte BRi3(H)-10110             | 1        | 6.67%   |
| Gigabyte B450M DS3H                | 1        | 6.67%   |
| ASUS P10S-I Series                 | 1        | 6.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 2        | 13.33%  |
| Yanling YL-KBR6L       | 1        | 6.67%   |
| RPi Raspberry          | 1        | 6.67%   |
| Protectli FW6          | 1        | 6.67%   |
| PC Engines APU2        | 1        | 6.67%   |
| MSI MS-7D54            | 1        | 6.67%   |
| MSI MS-7C56            | 1        | 6.67%   |
| Lenovo ThinkCentre     | 1        | 6.67%   |
| HP Compaq              | 1        | 6.67%   |
| Gigabyte X470          | 1        | 6.67%   |
| Gigabyte H81M-S2PV     | 1        | 6.67%   |
| Gigabyte BRi3(H)-10110 | 1        | 6.67%   |
| Gigabyte B450M         | 1        | 6.67%   |
| ASUS P10S-I            | 1        | 6.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2019    | 5        | 33.33%  |
| 2020    | 4        | 26.67%  |
| 2021    | 2        | 13.33%  |
| Unknown | 2        | 13.33%  |
| 2015    | 1        | 6.67%   |
| 2006    | 1        | 6.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 15       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 13       | 86.67%  |
| Yes  | 2        | 13.33%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 5        | 33.33%  |
| 3.01-4.0   | 3        | 20%     |
| 8.01-16.0  | 3        | 20%     |
| 4.01-8.0   | 2        | 13.33%  |
| 32.01-64.0 | 1        | 6.67%   |
| 0.01-0.5   | 1        | 6.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 13       | 86.67%  |
| 0.51-1.0 | 1        | 6.67%   |
| 0        | 1        | 6.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 7        | 46.67%  |
| 2      | 4        | 26.67%  |
| 4      | 2        | 13.33%  |
| 6      | 1        | 6.67%   |
| 3      | 1        | 6.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 93.33%  |
| Yes       | 1        | 6.67%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12       | 80%     |
| No        | 3        | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 73.33%  |
| Yes       | 4        | 26.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11       | 73.33%  |
| Yes       | 4        | 26.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 5        | 33.33%  |
| USA         | 3        | 20%     |
| Poland      | 2        | 13.33%  |
| Ukraine     | 1        | 6.67%   |
| UK          | 1        | 6.67%   |
| Switzerland | 1        | 6.67%   |
| Sweden      | 1        | 6.67%   |
| Germany     | 1        | 6.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Moscow          | 2        | 13.33%  |
| Miedziana Gora  | 2        | 13.33%  |
| Zhukovskiy      | 1        | 6.67%   |
| Voskresensk     | 1        | 6.67%   |
| Syeverodonets'k | 1        | 6.67%   |
| St Petersburg   | 1        | 6.67%   |
| Poplar          | 1        | 6.67%   |
| Oensingen       | 1        | 6.67%   |
| Kingman         | 1        | 6.67%   |
| Irvine          | 1        | 6.67%   |
| Erlangen        | 1        | 6.67%   |
| Ames            | 1        | 6.67%   |
| Akarp           | 1        | 6.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 4        | 4      | 14.29%  |
| Kingston                           | 4        | 5      | 14.29%  |
| Seagate                            | 3        | 3      | 10.71%  |
| Samsung Electronics                | 3        | 3      | 10.71%  |
| NVMe                               | 3        | 3      | 10.71%  |
| Toshiba                            | 2        | 2      | 7.14%   |
| SanDisk                            | 1        | 1      | 3.57%   |
| Product:              USB DISK 3.0 | 1        | 1      | 3.57%   |
| OPENBSD                            | 1        | 1      | 3.57%   |
| Intel                              | 1        | 1      | 3.57%   |
| HPE                                | 1        | 2      | 3.57%   |
| Hitachi                            | 1        | 1      | 3.57%   |
| HGST                               | 1        | 1      | 3.57%   |
| Crucial                            | 1        | 1      | 3.57%   |
| ASMT                               | 1        | 1      | 3.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| WDC WDS240G2G0B-00EPW0 240GB                         | 1        | 3.57%   |
| WDC WD6400AARS-00Y5B1 640GB                          | 1        | 3.57%   |
| WDC WD20PURX-64P6ZY0 2TB                             | 1        | 3.57%   |
| WDC WD10EADS-00M2B0 1TB                              | 1        | 3.57%   |
| Toshiba MQ04ABF100 1TB                               | 1        | 3.57%   |
| Toshiba DT01ACA050 500GB                             | 1        | 3.57%   |
| Seagate ST3250318AS 250GB                            | 1        | 3.57%   |
| Seagate ST250DM000-1BD141 250GB                      | 1        | 3.57%   |
| Seagate ST1000LM035-1RK172 1TB                       | 1        | 3.57%   |
| SanDisk Ultra 32GB                                   | 1        | 3.57%   |
| Samsung SSD 860 EVO 250GB                            | 1        | 3.57%   |
| Samsung HD501LJ 500GB                                | 1        | 3.57%   |
| Samsung Flash Drive FIT 32GB                         | 1        | 3.57%   |
| Product:              USB DISK 3.0 USB DISK 3.0 64GB | 1        | 3.57%   |
| OPENBSD SR RAID 1 1TB                                | 1        | 3.57%   |
| NVMe TOSHIBA-RC100 240GB                             | 1        | 3.57%   |
| NVMe Samsung SSD 970 250GB                           | 1        | 3.57%   |
| NVMe PCIe SSD 512GB                                  | 1        | 3.57%   |
| Kingston SV300S37A240G 240GB                         | 1        | 3.57%   |
| Kingston SUV500MS480G 480GB                          | 1        | 3.57%   |
| Kingston SUV500MS240G 240GB                          | 1        | 3.57%   |
| Kingston SMS200S330G 32GB                            | 1        | 3.57%   |
| Intel SSDSC2BW240A4 240GB                            | 1        | 3.57%   |
| HPE MK000480GWXFF 480GB                              | 1        | 3.57%   |
| Hitachi HUA723020ALA640 2TB                          | 1        | 3.57%   |
| HGST HUS724020ALA640 2TB                             | 1        | 3.57%   |
| Crucial M4-CT128M4SSD2 128GB                         | 1        | 3.57%   |
| ASMT 2115 500GB                                      | 1        | 3.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC                                | 3        | 3      | 18.75%  |
| Seagate                            | 3        | 3      | 18.75%  |
| Toshiba                            | 2        | 2      | 12.5%   |
| Samsung Electronics                | 2        | 2      | 12.5%   |
| Product:              USB DISK 3.0 | 1        | 1      | 6.25%   |
| OPENBSD                            | 1        | 1      | 6.25%   |
| NVMe                               | 1        | 1      | 6.25%   |
| Hitachi                            | 1        | 1      | 6.25%   |
| HGST                               | 1        | 1      | 6.25%   |
| ASMT                               | 1        | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 4        | 5      | 33.33%  |
| NVMe                | 2        | 2      | 16.67%  |
| WDC                 | 1        | 1      | 8.33%   |
| SanDisk             | 1        | 1      | 8.33%   |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Intel               | 1        | 1      | 8.33%   |
| HPE                 | 1        | 2      | 8.33%   |
| Crucial             | 1        | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 11       | 14     | 61.11%  |
| HDD  | 7        | 16     | 38.89%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 15       | 30     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 15       | 21     | 75%     |
| 0.51-1.0   | 4        | 6      | 20%     |
| 1.01-2.0   | 1        | 3      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 6        | 40%     |
| 251-500        | 4        | 26.67%  |
| 21-50          | 3        | 20%     |
| More than 3000 | 1        | 6.67%   |
| 501-1000       | 1        | 6.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 9        | 60%     |
| 21-50     | 3        | 20%     |
| 2001-3000 | 1        | 6.67%   |
| 101-250   | 1        | 6.67%   |
| 51-100    | 1        | 6.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD10EADS-00M2B0 1TB         | 1        | 1      | 25%     |
| Toshiba MQ04ABF100 1TB          | 1        | 1      | 25%     |
| Seagate ST250DM000-1BD141 250GB | 1        | 1      | 25%     |
| Kingston SMS200S330G 32GB       | 1        | 2      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 1        | 1      | 25%     |
| Toshiba  | 1        | 1      | 25%     |
| Seagate  | 1        | 1      | 25%     |
| Kingston | 1        | 2      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Toshiba | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 3        | 3      | 75%     |
| SSD  | 1        | 2      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 12       | 18     | 57.14%  |
| Detected | 4        | 6      | 19.05%  |
| Malfunc  | 4        | 5      | 19.05%  |
| Failed   | 1        | 1      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Intel                  | 7        | 46.67%  |
| AMD                    | 5        | 33.33%  |
| Toshiba                | 1        | 6.67%   |
| Phison Electronics     | 1        | 6.67%   |
| HighPoint Technologies | 1        | 6.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 4        | 22.22%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2        | 11.11%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 11.11%  |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 11.11%  |
| Toshiba BG3 NVMe SSD Controller                                                | 1        | 5.56%   |
| Phison E12 NVMe Controller                                                     | 1        | 5.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 5.56%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 5.56%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]            | 1        | 5.56%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 1        | 5.56%   |
| HighPoint unknown                                                              | 1        | 5.56%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 1        | 5.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 11       | 73.33%  |
| NVMe | 2        | 13.33%  |
| RAID | 1        | 6.67%   |
| IDE  | 1        | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 7        | 46.67%  |
| AMD    | 5        | 33.33%  |
| ARM    | 3        | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| AMD Ryzen 7 5800X 8-Core Processor    | 2        | 13.33%  |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz   | 1        | 6.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz     | 1        | 6.67%   |
| Intel Core i5-4570S CPU @ 2.90GHz     | 1        | 6.67%   |
| Intel Core i3-10110U CPU @ 2.10GHz    | 1        | 6.67%   |
| Intel Core 2 CPU 6400 @ 2.13GHz       | 1        | 6.67%   |
| Intel Celeron CPU G1820 @ 2.70GHz     | 1        | 6.67%   |
| Intel Celeron CPU 3865U @ 1.80GHz     | 1        | 6.67%   |
| ARM Cortex-A8 r3p2                    | 1        | 6.67%   |
| ARM Cortex-A72 r0p3                   | 1        | 6.67%   |
| ARM Cortex-A53 r0p4                   | 1        | 6.67%   |
| AMD Ryzen 7 2700 Eight-Core Processor | 1        | 6.67%   |
| AMD Ryzen 3 3100 4-Core Processor     | 1        | 6.67%   |
| AMD GX-412TC SOC                      | 1        | 6.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| ARM Cortex    | 3        | 20%     |
| AMD Ryzen 7   | 3        | 20%     |
| Intel Celeron | 2        | 13.33%  |
| Intel Xeon    | 1        | 6.67%   |
| Intel Core i7 | 1        | 6.67%   |
| Intel Core i5 | 1        | 6.67%   |
| Intel Core i3 | 1        | 6.67%   |
| Intel Core 2  | 1        | 6.67%   |
| AMD Ryzen 3   | 1        | 6.67%   |
| AMD GX        | 1        | 6.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 4        | 26.67%  |
| 2       | 4        | 26.67%  |
| Unknown | 4        | 26.67%  |
| 16      | 1        | 6.67%   |
| 8       | 1        | 6.67%   |
| 1       | 1        | 6.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 9        | 60%     |
| Unknown | 5        | 33.33%  |
| 2       | 1        | 6.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 8        | 53.33%  |
| Unknown | 5        | 33.33%  |
| 2       | 2        | 13.33%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Unknown  | 5        | 33.33%  |
| KabyLake | 3        | 20%     |
| Haswell  | 2        | 13.33%  |
| Zen+     | 1        | 6.67%   |
| Zen 2    | 1        | 6.67%   |
| Skylake  | 1        | 6.67%   |
| Puma     | 1        | 6.67%   |
| Core     | 1        | 6.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 6        | 54.55%  |
| AMD               | 4        | 36.36%  |
| ASPEED Technology | 1        | 9.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 18.18%  |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                                | 2        | 18.18%  |
| Intel UHD Graphics 620                                                      | 1        | 9.09%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                        | 1        | 9.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1        | 9.09%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 1        | 9.09%   |
| ASPEED Technology ASPEED Graphics Family                                    | 1        | 9.09%   |
| AMD Oland PRO [Radeon R7 240/340]                                           | 1        | 9.09%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 9.09%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 6        | 40%     |
| Other      | 4        | 26.67%  |
| 1 x AMD    | 4        | 26.67%  |
| 1 x ASPEED | 1        | 6.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 8        | 53.33%  |
| Unknown | 7        | 46.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Iiyama               | 1        | 33.33%  |
| Ancor Communications | 1        | 33.33%  |
| Acer                 | 1        | 33.33%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Iiyama PL3288UH IVM7610 3840x2160 700x390mm 31.5-inch                | 1        | 33.33%  |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch | 1        | 33.33%  |
| Acer VG220Q ACR06D8 1920x1080 480x270mm 21.7-inch                    | 1        | 33.33%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 3840x2160 (4K)   | 1        | 33.33%  |
| 1920x1080 (FHD)  | 1        | 33.33%  |
| 1440x900 (WXGA+) | 1        | 33.33%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 31     | 1        | 33.33%  |
| 21     | 1        | 33.33%  |
| 19     | 1        | 33.33%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 2        | 66.67%  |
| 601-700     | 1        | 33.33%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 2        | 66.67%  |
| 16/10 | 1        | 33.33%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 351-500        | 1        | 33.33%  |
| 201-250        | 1        | 33.33%  |
| 151-200        | 1        | 33.33%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 121-160 | 1        | 33.33%  |
| 101-120 | 1        | 33.33%  |
| 51-100  | 1        | 33.33%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 8        | 53.33%  |
| 1     | 7        | 46.67%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 8        | 57.14%  |
| Realtek Semiconductor | 4        | 28.57%  |
| TP-Link               | 1        | 7.14%   |
| Broadcom              | 1        | 7.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3        | 18.75%  |
| Intel I211 Gigabit Network Connection                             | 2        | 12.5%   |
| Intel I210 Gigabit Network Connection                             | 2        | 12.5%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1        | 6.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 6.25%   |
| Intel Wireless 7260                                               | 1        | 6.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 6.25%   |
| Intel Ethernet Connection I217-V                                  | 1        | 6.25%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 6.25%   |
| Intel Centrino Wireless-N 2230                                    | 1        | 6.25%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 6.25%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 6.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 3        | 75%     |
| TP-Link | 1        | 25%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS] | 1        | 25%     |
| Intel Wireless 7260                          | 1        | 25%     |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz       | 1        | 25%     |
| Intel Centrino Wireless-N 2230               | 1        | 25%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 58.33%  |
| Realtek Semiconductor | 4        | 33.33%  |
| Broadcom              | 1        | 8.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3        | 25%     |
| Intel I211 Gigabit Network Connection                             | 2        | 16.67%  |
| Intel I210 Gigabit Network Connection                             | 2        | 16.67%  |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 8.33%   |
| Intel Ethernet Connection I217-V                                  | 1        | 8.33%   |
| Intel Ethernet Connection (6) I219-V                              | 1        | 8.33%   |
| Intel 82583V Gigabit Network Connection                           | 1        | 8.33%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 8.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12       | 75%     |
| WiFi     | 4        | 25%     |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 8        | 80%     |
| WiFi     | 2        | 20%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 6        | 40%     |
| 2     | 3        | 20%     |
| 0     | 3        | 20%     |
| 7     | 1        | 6.67%   |
| 6     | 1        | 6.67%   |
| 3     | 1        | 6.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 3        | 75%     |
| Cambridge Silicon Radio | 1        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 25%     |
| Intel Bluetooth wireless interface                  | 1        | 25%     |
| Intel AX210 Bluetooth                               | 1        | 25%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 25%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 5        | 45.45%  |
| AMD                 | 4        | 36.36%  |
| C-Media Electronics | 1        | 9.09%   |
| Blue Microphones    | 1        | 9.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                | 3        | 18.75%  |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 2        | 12.5%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]               | 2        | 12.5%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 1        | 6.25%   |
| Intel Sunrise Point-LP HD Audio                                         | 1        | 6.25%   |
| Intel Comet Lake PCH-LP cAVS                                            | 1        | 6.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                          | 1        | 6.25%   |
| C-Media Electronics Digital Hifi Audio Digital Hifi Audio SPDIFs        | 1        | 6.25%   |
| Blue Microphones Yeti Stereo Microphone                                 | 1        | 6.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 1        | 6.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 1        | 6.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 1        | 6.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 50%     |
| Transcend           | 1        | 25%     |
| SK Hynix            | 1        | 25%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Transcend RAM TS128MLQ64V6J 1GB DIMM DDR2 667MT/s     | 1        | 20%     |
| SK Hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 667MT/s   | 1        | 20%     |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s | 1        | 20%     |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s | 1        | 20%     |
| Samsung RAM M3 78T2953CZ3-CE6 1GB DIMM DDR2 667MT/s   | 1        | 20%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR3 | 1        | 50%     |
| DDR2 | 1        | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| SODIMM | 1        | 50%     |
| DIMM   | 1        | 50%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Desktops | Percent |
|------|----------|---------|
| 4096 | 1        | 50%     |
| 1024 | 1        | 50%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 1        | 50%     |
| 667   | 1        | 50%     |

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


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Z-Star Microelectronics | 1        | 50%     |
| Microdia                | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Z-Star Integrated Camera        | 1        | 50%     |
| Microdia Ltd., USB  Live camera | 1        | 50%     |

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
| 1     | 6        | 40%     |
| 0     | 6        | 40%     |
| 2     | 3        | 20%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 6        | 54.55%  |
| Graphics card            | 3        | 27.27%  |
| Storage/raid             | 1        | 9.09%   |
| Net/wireless             | 1        | 9.09%   |

