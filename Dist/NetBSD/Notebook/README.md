NetBSD - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for NetBSD.

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

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | Pavilion 17                 | [0f891b4377](https://bsd-hardware.info/?probe=0f891b4377) | Apr 21, 2023 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | [59713ca193](https://bsd-hardware.info/?probe=59713ca193) | Feb 15, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Dell          | Precision M4500             | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| ASUSTek       | X555LJ                      | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| Acer          | Aspire A114-33              | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| MiTAC         | 5033                        | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| Lenovo        | ThinkPad T420 4236D26       | [5c64875424](https://bsd-hardware.info/?probe=5c64875424) | Oct 12, 2021 |
| ASUSTek       | X555LJ                      | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| Toshiba       | Satellite A100              | [9ccf97d62c](https://bsd-hardware.info/?probe=9ccf97d62c) | Sep 05, 2021 |
| Sony          | SVF1421DSGW                 | [abadb65058](https://bsd-hardware.info/?probe=abadb65058) | Jun 01, 2021 |
| Apple         | MacBook2,1                  | [360f29bf3b](https://bsd-hardware.info/?probe=360f29bf3b) | Mar 05, 2021 |
| Apple         | MacBook2,1                  | [f6e7638f87](https://bsd-hardware.info/?probe=f6e7638f87) | Mar 05, 2021 |
| IBM           | ThinkPad R51 2887AVG        | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | [eda02dc46b](https://bsd-hardware.info/?probe=eda02dc46b) | Dec 25, 2020 |
| Fujitsu Si... | AMILO L7310                 | [0603b64315](https://bsd-hardware.info/?probe=0603b64315) | Dec 25, 2020 |
| Acer          | Aspire ES1-132              | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| eMachines     | eME642G                     | [42027dfbb9](https://bsd-hardware.info/?probe=42027dfbb9) | Jul 25, 2020 |
| Lenovo        | G500 20236                  | [99cf14c489](https://bsd-hardware.info/?probe=99cf14c489) | Jun 03, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |
| Lenovo        | G570 20079                  | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| ASUSTek       | A3L                         | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| Lenovo        | G570 20079                  | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| NetBSD 9.2        | 5         | 23.81%  |
| NetBSD 9.1        | 4         | 19.05%  |
| NetBSD 9.0        | 3         | 14.29%  |
| NetBSD 9.3        | 2         | 9.52%   |
| NetBSD 9.99.94    | 1         | 4.76%   |
| NetBSD 9.2_STABLE | 1         | 4.76%   |
| NetBSD 9.0_STABLE | 1         | 4.76%   |
| NetBSD 8.99.51    | 1         | 4.76%   |
| NetBSD 7.2        | 1         | 4.76%   |
| NetBSD 10.99.1    | 1         | 4.76%   |
| NetBSD 10.0_BETA  | 1         | 4.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| NetBSD | 20        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 15        | 75%     |
| i386  | 5         | 25%     |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 6         | 28.57%  |
| XFCE         | 4         | 19.05%  |
| ctwm         | 3         | 14.29%  |
| Fluxbox      | 2         | 9.52%   |
| sdorfehs     | 1         | 4.76%   |
| MATE         | 1         | 4.76%   |
| LXQt         | 1         | 4.76%   |
| helloDesktop | 1         | 4.76%   |
| DWM          | 1         | 4.76%   |
| Awesome      | 1         | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 17        | 85%     |
| Console | 3         | 15%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 17        | 85%     |
| XDM     | 1         | 5%      |
| SLiM    | 1         | 5%      |
| GDM     | 1         | 5%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 70%     |
| en_US   | 5         | 25%     |
| ru_RU   | 1         | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 20        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 20        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 11        | 55%     |
| GPT     | 9         | 45%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 7         | 35%     |
| ASUSTek Computer | 2         | 10%     |
| Acer             | 2         | 10%     |
| Toshiba          | 1         | 5%      |
| Sony             | 1         | 5%      |
| MiTAC            | 1         | 5%      |
| IBM              | 1         | 5%      |
| Hewlett-Packard  | 1         | 5%      |
| Fujitsu Siemens  | 1         | 5%      |
| eMachines        | 1         | 5%      |
| Dell             | 1         | 5%      |
| Apple            | 1         | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Toshiba Satellite A100           | 1         | 5%      |
| Sony SVF1421DSGW                 | 1         | 5%      |
| MiTAC 5033                       | 1         | 5%      |
| Lenovo ThinkPad X240 20AMS0J01N  | 1         | 5%      |
| Lenovo ThinkPad T510 4313CTO     | 1         | 5%      |
| Lenovo ThinkPad T460s 20FAS3L002 | 1         | 5%      |
| Lenovo ThinkPad T430s 23564H3    | 1         | 5%      |
| Lenovo ThinkPad T420 4236D26     | 1         | 5%      |
| Lenovo ThinkPad 13 20GJCTO1WW    | 1         | 5%      |
| Lenovo G500 20236                | 1         | 5%      |
| IBM ThinkPad R51 2887AVG         | 1         | 5%      |
| HP Pavilion 17                   | 1         | 5%      |
| Fujitsu Siemens AMILO L7310      | 1         | 5%      |
| eMachines eME642G                | 1         | 5%      |
| Dell Precision M4500             | 1         | 5%      |
| ASUS X555LJ                      | 1         | 5%      |
| ASUS A3L                         | 1         | 5%      |
| Apple MacBook2,1                 | 1         | 5%      |
| Acer Aspire ES1-132              | 1         | 5%      |
| Acer Aspire A114-33              | 1         | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 6         | 30%     |
| Acer Aspire           | 2         | 10%     |
| Toshiba Satellite     | 1         | 5%      |
| Sony SVF1421DSGW      | 1         | 5%      |
| MiTAC 5033            | 1         | 5%      |
| Lenovo G500           | 1         | 5%      |
| IBM ThinkPad          | 1         | 5%      |
| HP Pavilion           | 1         | 5%      |
| Fujitsu Siemens AMILO | 1         | 5%      |
| eMachines eME642G     | 1         | 5%      |
| Dell Precision        | 1         | 5%      |
| ASUS X555LJ           | 1         | 5%      |
| ASUS A3L              | 1         | 5%      |
| Apple MacBook2        | 1         | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 4         | 20%     |
| 2016    | 3         | 15%     |
| 2011    | 2         | 10%     |
| 2010    | 2         | 10%     |
| 2005    | 2         | 10%     |
| 2021    | 1         | 5%      |
| 2019    | 1         | 5%      |
| 2017    | 1         | 5%      |
| 2014    | 1         | 5%      |
| 2007    | 1         | 5%      |
| 2006    | 1         | 5%      |
| Unknown | 1         | 5%      |

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
| No   | 19        | 95%     |
| Yes  | 1         | 5%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 8         | 40%     |
| 3.01-4.0   | 5         | 25%     |
| 0.51-1.0   | 2         | 10%     |
| 16.01-24.0 | 1         | 5%      |
| 1.01-2.0   | 1         | 5%      |
| 8.01-16.0  | 1         | 5%      |
| 0.01-0.5   | 1         | 5%      |
| 0          | 1         | 5%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 20        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 13        | 65%     |
| 0      | 7         | 35%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 90%     |
| Yes       | 2         | 10%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 90%     |
| No        | 2         | 10%     |

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
| Yes       | 10        | 50%     |
| No        | 10        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Italy        | 4         | 20%     |
| USA          | 3         | 15%     |
| Russia       | 3         | 15%     |
| Saudi Arabia | 2         | 10%     |
| Hungary      | 2         | 10%     |
| Vietnam      | 1         | 5%      |
| India        | 1         | 5%      |
| Germany      | 1         | 5%      |
| France       | 1         | 5%      |
| Finland      | 1         | 5%      |
| Canada       | 1         | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Rome             | 4         | 19.05%  |
| Riyadh           | 2         | 9.52%   |
| Moscow           | 2         | 9.52%   |
| Gardony          | 2         | 9.52%   |
| Washington       | 1         | 4.76%   |
| Turenki          | 1         | 4.76%   |
| Surrey           | 1         | 4.76%   |
| Sun Prairie      | 1         | 4.76%   |
| Ozersk           | 1         | 4.76%   |
| Ladbergen        | 1         | 4.76%   |
| Kalispell        | 1         | 4.76%   |
| Ho Chi Minh City | 1         | 4.76%   |
| Genzano di Roma  | 1         | 4.76%   |
| Carry-le-Rouet   | 1         | 4.76%   |
| Ahmedabad        | 1         | 4.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 23.08%  |
| Intel               | 3         | 3      | 23.08%  |
| Kingston            | 2         | 2      | 15.38%  |
| Hitachi             | 2         | 3      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| Samsung Electronics | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD1600BEVT-00A23T0 160GB        | 1         | 7.69%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 7.69%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 7.69%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 7.69%   |
| Samsung HM080HC 80GB                | 1         | 7.69%   |
| Kingston SA400S37240G 240GB         | 1         | 7.69%   |
| Kingston SA400S37120G 120GB         | 1         | 7.69%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 7.69%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 7.69%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 7.69%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 7.69%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 7.69%   |
| HGST HTS545050A7E680 500GB          | 1         | 7.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 37.5%   |
| Hitachi             | 2         | 3      | 25%     |
| WDC                 | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| HGST                | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Intel    | 3         | 3      | 60%     |
| Kingston | 2         | 2      | 40%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 61.54%  |
| SSD  | 5         | 5      | 38.46%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 13        | 14     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 13     | 92.31%  |
| 0.51-1.0   | 1         | 1      | 7.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 7         | 35%     |
| 251-500    | 4         | 20%     |
| 501-1000   | 3         | 15%     |
| 51-100     | 3         | 15%     |
| 1-20       | 2         | 10%     |
| 21-50      | 1         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 14        | 66.67%  |
| 21-50   | 4         | 19.05%  |
| 51-100  | 2         | 9.52%   |
| 101-250 | 1         | 4.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 12.5%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1      | 12.5%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 12.5%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 12.5%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 1      | 12.5%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1      | 12.5%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 12.5%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 2      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 37.5%   |
| Intel   | 3         | 3      | 37.5%   |
| Hitachi | 2         | 3      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 60%     |
| Hitachi | 2         | 3      | 40%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 62.5%   |
| SSD  | 3         | 3      | 37.5%   |

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
| Malfunc  | 8         | 9      | 61.54%  |
| Works    | 4         | 4      | 30.77%  |
| Detected | 1         | 1      | 7.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 17        | 85%     |
| AMD              | 2         | 10%     |
| VIA Technologies | 1         | 5%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 13.64%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 9.09%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                       | 2         | 9.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 9.09%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                  | 1         | 4.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 4.55%   |
| Intel Jasper Lake SATA AHCI Controller                                       | 1         | 4.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 4.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 1         | 4.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 1         | 4.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 1         | 4.55%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                | 1         | 4.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 4.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 4.55%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 1         | 4.55%   |
| AMD FCH IDE Controller                                                       | 1         | 4.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 15        | 68.18%  |
| IDE  | 7         | 31.82%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 16        | 80%     |
| AMD          | 3         | 15%     |
| 123456789ABC | 1         | 5%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel 686-class                           | 3         | 14.29%  |
| Intel Pentium M processor 1.60GHz         | 1         | 4.76%   |
| Intel Pentium M processor                 | 1         | 4.76%   |
| Intel Pentium CPU 2020M @ 2.40GHz         | 1         | 4.76%   |
| Intel Core i7-5500U CPU @ 2.40GHz         | 1         | 4.76%   |
| Intel Core i7-2640M CPU @ 2.80GHz         | 1         | 4.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz         | 1         | 4.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 1         | 4.76%   |
| Intel Core i5-4300U CPU @ 1.90GHz         | 1         | 4.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz         | 1         | 4.76%   |
| Intel Core i5 CPU M 560 @ 2.67GH          | 1         | 4.76%   |
| Intel Core i5 CPU M 540 @ 2.53GHz         | 1         | 4.76%   |
| Intel Core i3-3217U CPU @ 1.80GHz         | 1         | 4.76%   |
| Intel Core 2 CPU T7200 @ 2.00GHz          | 1         | 4.76%   |
| Intel Core 2 CPU T7                       | 1         | 4.76%   |
| AMD Tillamook                             | 1         | 4.76%   |
| AMD Athlon II P340 Dual-Core Processor    | 1         | 4.76%   |
| AMD A10-5745M APU with Radeon HD Graphics | 1         | 4.76%   |
| 123456789ABC Pentium 4                    | 1         | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 6         | 28.57%  |
| Intel 686-class | 3         | 14.29%  |
| Other           | 2         | 9.52%   |
| Intel Pentium M | 2         | 9.52%   |
| Intel Core i7   | 2         | 9.52%   |
| Intel Core 2    | 2         | 9.52%   |
| Intel Pentium   | 1         | 4.76%   |
| Intel Core i3   | 1         | 4.76%   |
| AMD Athlon II   | 1         | 4.76%   |
| AMD A10         | 1         | 4.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 11        | 52.38%  |
| Unknown | 9         | 42.86%  |
| 4       | 1         | 4.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 18        | 85.71%  |
| Unknown | 3         | 14.29%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 9         | 42.86%  |
| 2       | 8         | 38.1%   |
| 1       | 4         | 19.05%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 5         | 23.81%  |
| IvyBridge   | 3         | 14.29%  |
| Skylake     | 2         | 9.52%   |
| P6          | 2         | 9.52%   |
| Core        | 2         | 9.52%   |
| Westmere    | 1         | 4.76%   |
| SandyBridge | 1         | 4.76%   |
| Piledriver  | 1         | 4.76%   |
| K10         | 1         | 4.76%   |
| Haswell     | 1         | 4.76%   |
| Geode       | 1         | 4.76%   |
| Broadwell   | 1         | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 14        | 66.67%  |
| Nvidia               | 3         | 14.29%  |
| AMD                  | 2         | 9.52%   |
| VIA Technologies     | 1         | 4.76%   |
| Trident Microsystems | 1         | 4.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 3         | 13.04%  |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 8.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 8.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 8.7%    |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 8.7%    |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]             | 1         | 4.35%   |
| Trident Microsystems TGUI 9660/938x/968x                                      | 1         | 4.35%   |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 4.35%   |
| Nvidia GT216GLM [Quadro FX 880M]                                              | 1         | 4.35%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 4.35%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 4.35%   |
| Intel HD Graphics 5500                                                        | 1         | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 4.35%   |
| Intel Apollo Lake [HD Graphics 505]                                           | 1         | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 4.35%   |
| AMD Richland [Radeon HD 8610G]                                                | 1         | 4.35%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                  | 1         | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 11        | 55%     |
| 2 x Intel                | 2         | 10%     |
| 1 x Nvidia               | 2         | 10%     |
| 1 x AMD                  | 2         | 10%     |
| 1 x VIA                  | 1         | 5%      |
| 1 x Trident Microsystems | 1         | 5%      |
| Intel + Nvidia           | 1         | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 18        | 90%     |
| Unknown | 2         | 10%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 6         | 30%     |
| Unknown    | 6         | 30%     |
| 1.01-2.0   | 5         | 25%     |
| 0.51-1.0   | 2         | 10%     |
| 3.01-4.0   | 1         | 5%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 5         | 45.45%  |
| Chimei Innolux      | 2         | 18.18%  |
| Samsung Electronics | 1         | 9.09%   |
| LG Philips          | 1         | 9.09%   |
| Lenovo              | 1         | 9.09%   |
| Apple               | 1         | 9.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch | 1         | 9.09%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch          | 1         | 9.09%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch          | 1         | 9.09%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 9.09%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 9.09%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch          | 1         | 9.09%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch          | 1         | 9.09%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 1         | 9.09%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 9.09%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch      | 1         | 9.09%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch               | 1         | 9.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 6         | 54.55%  |
| 1600x900 (HD+)  | 2         | 18.18%  |
| 1280x800 (WXGA) | 2         | 18.18%  |
| 1920x1080 (FHD) | 1         | 9.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 5         | 45.45%  |
| 13     | 5         | 45.45%  |
| 12     | 1         | 9.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 9         | 81.82%  |
| 201-300     | 2         | 18.18%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 9         | 81.82%  |
| 16/10 | 2         | 18.18%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 5         | 45.45%  |
| 101-110        | 3         | 27.27%  |
| 91-100         | 2         | 18.18%  |
| 61-70          | 1         | 9.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 7         | 63.64%  |
| 121-160 | 2         | 18.18%  |
| 51-100  | 2         | 18.18%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 16        | 80%     |
| 0     | 4         | 20%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 12        | 38.71%  |
| Realtek Semiconductor    | 6         | 19.35%  |
| Qualcomm Atheros         | 6         | 19.35%  |
| Broadcom                 | 2         | 6.45%   |
| VIA Technologies         | 1         | 3.23%   |
| TP-Link                  | 1         | 3.23%   |
| Marvell Technology Group | 1         | 3.23%   |
| Huawei Technologies      | 1         | 3.23%   |
| D-Link                   | 1         | 3.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 4         | 9.52%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 4.76%   |
| Intel Wireless 8260                                                                   | 2         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 4.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 2         | 4.76%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 2.38%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 2.38%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 2.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 2.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1         | 2.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 2.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2.38%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.38%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 2.38%   |
| Intel Wireless 7265                                                                   | 1         | 2.38%   |
| Intel Wireless 7260                                                                   | 1         | 2.38%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 2.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 2.38%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 2.38%   |
| Intel PRO/100 VE Network Connection                                                   | 1         | 2.38%   |
| Intel Ethernet Connection I219-V                                                      | 1         | 2.38%   |
| Intel Ethernet Connection I219-LM                                                     | 1         | 2.38%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.38%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.38%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 2.38%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller                     | 1         | 2.38%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                                    | 1         | 2.38%   |
| Intel 82577LM Gigabit Network Connection                                              | 1         | 2.38%   |
| Huawei USB Device                                                                     | 1         | 2.38%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 2.38%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                       | 1         | 2.38%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 2.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 12        | 57.14%  |
| Qualcomm Atheros      | 5         | 23.81%  |
| TP-Link               | 1         | 4.76%   |
| Realtek Semiconductor | 1         | 4.76%   |
| D-Link                | 1         | 4.76%   |
| Broadcom              | 1         | 4.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 9.09%   |
| Intel Wireless 8260                                                                   | 2         | 9.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 9.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 4.55%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 4.55%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 4.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 4.55%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 4.55%   |
| Intel Wireless 7265                                                                   | 1         | 4.55%   |
| Intel Wireless 7260                                                                   | 1         | 4.55%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 4.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 4.55%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 4.55%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 4.55%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 4.55%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 4.55%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 4.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 8         | 42.11%  |
| Realtek Semiconductor    | 6         | 31.58%  |
| VIA Technologies         | 1         | 5.26%   |
| Qualcomm Atheros         | 1         | 5.26%   |
| Marvell Technology Group | 1         | 5.26%   |
| Huawei Technologies      | 1         | 5.26%   |
| Broadcom                 | 1         | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 21.05%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 10.53%  |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 5.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 5.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 5.26%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 5.26%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 5.26%   |
| Intel PRO/100 VE Network Connection                               | 1         | 5.26%   |
| Intel Ethernet Connection I219-V                                  | 1         | 5.26%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 5.26%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 5.26%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 5.26%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 5.26%   |
| Huawei USB Device                                                 | 1         | 5.26%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 19        | 50%     |
| Ethernet | 18        | 47.37%  |
| Modem    | 1         | 2.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 16        | 53.33%  |
| Ethernet | 14        | 46.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 18        | 90%     |
| 0     | 2         | 10%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 16        | 80%     |
| Yes  | 4         | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 7         | 63.64%  |
| IMC Networks            | 1         | 9.09%   |
| Cambridge Silicon Radio | 1         | 9.09%   |
| Broadcom                | 1         | 9.09%   |
| Apple                   | 1         | 9.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 36.36%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 9.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 9.09%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 9.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 9.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 9.09%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 9.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 16        | 76.19%  |
| Nvidia           | 2         | 9.52%   |
| AMD              | 2         | 9.52%   |
| VIA Technologies | 1         | 4.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 12%     |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 8%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 8%      |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 8%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 8%      |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 4%      |
| Nvidia High Definition Audio Controller                                    | 1         | 4%      |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 4%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 4%      |
| Intel Jasper Lake HD Audio                                                 | 1         | 4%      |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 4%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 4%      |
| Intel Broadwell-U Audio Controller                                         | 1         | 4%      |
| Intel 8 Series HD Audio Controller                                         | 1         | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 4%      |
| AMD Trinity HDMI Audio Controller                                          | 1         | 4%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 4%      |
| AMD FCH Azalia Controller                                                  | 1         | 4%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 4%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 5         | 23.81%  |
| SK hynix            | 3         | 14.29%  |
| Samsung Electronics | 3         | 14.29%  |
| Ramaxel Technology  | 2         | 9.52%   |
| Micron Technology   | 2         | 9.52%   |
| Kingston            | 2         | 9.52%   |
| SHARETRONIC         | 1         | 4.76%   |
| Nanya Technology    | 1         | 4.76%   |
| A-DATA Technology   | 1         | 4.76%   |
| Unknown             | 1         | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s               | 1         | 4.76%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 4.76%   |
| Unknown RAM Module 2GB SODIMM DDR3                         | 1         | 4.76%   |
| Unknown RAM Module 256MB SODIMM DDR                        | 1         | 4.76%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s             | 1         | 4.76%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 1         | 4.76%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 1         | 4.76%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 4.76%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1         | 4.76%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s      | 1         | 4.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 4.76%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 1         | 4.76%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 1         | 4.76%   |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s   | 1         | 4.76%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 4.76%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s      | 1         | 4.76%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s     | 1         | 4.76%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s    | 1         | 4.76%   |
| Kingston RAM 9905428-026.A02LF 2048MB SODIMM DDR3 1066MT/s | 1         | 4.76%   |
| A-DATA RAM AM1L16BC4R1-B1PS 4GB SODIMM DDR3 1600MT/s       | 1         | 4.76%   |
| Unknown                                                    | 1         | 4.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 10        | 62.5%   |
| DDR4  | 2         | 12.5%   |
| SDRAM | 1         | 6.25%   |
| DRAM  | 1         | 6.25%   |
| DDR2  | 1         | 6.25%   |
| DDR   | 1         | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 15        | 93.75%  |
| Chip   | 1         | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 5         | 29.41%  |
| 2048 | 5         | 29.41%  |
| 8192 | 3         | 17.65%  |
| 512  | 2         | 11.76%  |
| 1024 | 1         | 5.88%   |
| 256  | 1         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 4         | 22.22%  |
| 2133    | 2         | 11.11%  |
| 1334    | 2         | 11.11%  |
| 1067    | 2         | 11.11%  |
| Unknown | 2         | 11.11%  |
| 1867    | 1         | 5.56%   |
| 1333    | 1         | 5.56%   |
| 1066    | 1         | 5.56%   |
| 533     | 1         | 5.56%   |
| 266     | 1         | 5.56%   |
| 166     | 1         | 5.56%   |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 4         | 33.33%  |
| Realtek Semiconductor         | 2         | 16.67%  |
| Syntek                        | 1         | 8.33%   |
| Sunplus Innovation Technology | 1         | 8.33%   |
| Quanta                        | 1         | 8.33%   |
| Lenovo                        | 1         | 8.33%   |
| Bison Electronics             | 1         | 8.33%   |
| ALi                           | 1         | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 3         | 25%     |
| Syntek Lenovo EasyCamera             | 1         | 8.33%   |
| Sunplus Integrated Camera            | 1         | 8.33%   |
| Realtek USB Camera                   | 1         | 8.33%   |
| Realtek Acer 640 x 480 laptop camera | 1         | 8.33%   |
| Quanta VGA WebCam                    | 1         | 8.33%   |
| Lenovo Integrated Webcam [R5U877]    | 1         | 8.33%   |
| Chicony Front Camera                 | 1         | 8.33%   |
| Bison Integrated Camera              | 1         | 8.33%   |
| ALi Gateway Webcam                   | 1         | 8.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 100%    |

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
| 1     | 7         | 35%     |
| 2     | 6         | 30%     |
| 0     | 4         | 20%     |
| 4     | 2         | 10%     |
| 5     | 1         | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 12        | 46.15%  |
| Net/wireless             | 4         | 15.38%  |
| Graphics card            | 4         | 15.38%  |
| Card reader              | 4         | 15.38%  |
| Storage                  | 1         | 3.85%   |
| Modem                    | 1         | 3.85%   |

