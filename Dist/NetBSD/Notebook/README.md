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

Total: 21

| Vendor        | Model                    | Probe                                                     | Date         |
|---------------|--------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | X555LJ                   | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| Acer          | Aspire A114-33           | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| MiTAC         | 5033                     | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| Lenovo        | ThinkPad T420 4236D26    | [5c64875424](https://bsd-hardware.info/?probe=5c64875424) | Oct 12, 2021 |
| ASUSTek       | X555LJ                   | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| Toshiba       | Satellite A100           | [9ccf97d62c](https://bsd-hardware.info/?probe=9ccf97d62c) | Sep 05, 2021 |
| Sony          | SVF1421DSGW              | [abadb65058](https://bsd-hardware.info/?probe=abadb65058) | Jun 01, 2021 |
| Apple         | MacBook2,1               | [360f29bf3b](https://bsd-hardware.info/?probe=360f29bf3b) | Mar 05, 2021 |
| Apple         | MacBook2,1               | [f6e7638f87](https://bsd-hardware.info/?probe=f6e7638f87) | Mar 05, 2021 |
| IBM           | ThinkPad R51 2887AVG     | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG     | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Lenovo        | ThinkPad T430s 23564H3   | [eda02dc46b](https://bsd-hardware.info/?probe=eda02dc46b) | Dec 25, 2020 |
| Fujitsu Si... | AMILO L7310              | [0603b64315](https://bsd-hardware.info/?probe=0603b64315) | Dec 25, 2020 |
| Acer          | Aspire ES1-132           | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| Lenovo        | ThinkPad T510 4313CTO    | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| eMachines     | eME642G                  | [42027dfbb9](https://bsd-hardware.info/?probe=42027dfbb9) | Jul 25, 2020 |
| Lenovo        | G500 20236               | [99cf14c489](https://bsd-hardware.info/?probe=99cf14c489) | Jun 03, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |
| Lenovo        | G570 20079               | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| ASUSTek       | A3L                      | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| Lenovo        | G570 20079               | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| NetBSD 9.2        | 5         | 29.41%  |
| NetBSD 9.1        | 4         | 23.53%  |
| NetBSD 9.0        | 3         | 17.65%  |
| NetBSD 9.99.94    | 1         | 5.88%   |
| NetBSD 9.2_STABLE | 1         | 5.88%   |
| NetBSD 9.0_STABLE | 1         | 5.88%   |
| NetBSD 8.99.51    | 1         | 5.88%   |
| NetBSD 7.2        | 1         | 5.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| NetBSD | 16        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 11        | 68.75%  |
| i386  | 5         | 31.25%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 5         | 29.41%  |
| XFCE         | 4         | 23.53%  |
| Fluxbox      | 2         | 11.76%  |
| ctwm         | 2         | 11.76%  |
| MATE         | 1         | 5.88%   |
| helloDesktop | 1         | 5.88%   |
| DWM          | 1         | 5.88%   |
| Awesome      | 1         | 5.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 13        | 81.25%  |
| Console | 3         | 18.75%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 14        | 87.5%   |
| XDM     | 1         | 6.25%   |
| GDM     | 1         | 6.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 11        | 68.75%  |
| en_US   | 4         | 25%     |
| ru_RU   | 1         | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 16        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 16        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 10        | 62.5%   |
| GPT     | 6         | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 5         | 31.25%  |
| ASUSTek Computer | 2         | 12.5%   |
| Acer             | 2         | 12.5%   |
| Toshiba          | 1         | 6.25%   |
| Sony             | 1         | 6.25%   |
| MiTAC            | 1         | 6.25%   |
| IBM              | 1         | 6.25%   |
| Fujitsu Siemens  | 1         | 6.25%   |
| eMachines        | 1         | 6.25%   |
| Apple            | 1         | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Toshiba Satellite A100          | 1         | 6.25%   |
| Sony SVF1421DSGW                | 1         | 6.25%   |
| MiTAC 5033                      | 1         | 6.25%   |
| Lenovo ThinkPad X240 20AMS0J01N | 1         | 6.25%   |
| Lenovo ThinkPad T510 4313CTO    | 1         | 6.25%   |
| Lenovo ThinkPad T430s 23564H3   | 1         | 6.25%   |
| Lenovo ThinkPad T420 4236D26    | 1         | 6.25%   |
| Lenovo G500 20236               | 1         | 6.25%   |
| IBM ThinkPad R51 2887AVG        | 1         | 6.25%   |
| Fujitsu Siemens AMILO L7310     | 1         | 6.25%   |
| eMachines eME642G               | 1         | 6.25%   |
| ASUS X555LJ                     | 1         | 6.25%   |
| ASUS A3L                        | 1         | 6.25%   |
| Apple MacBook2,1                | 1         | 6.25%   |
| Acer Aspire ES1-132             | 1         | 6.25%   |
| Acer Aspire A114-33             | 1         | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 4         | 25%     |
| Acer Aspire           | 2         | 12.5%   |
| Toshiba Satellite     | 1         | 6.25%   |
| Sony SVF1421DSGW      | 1         | 6.25%   |
| MiTAC 5033            | 1         | 6.25%   |
| Lenovo G500           | 1         | 6.25%   |
| IBM ThinkPad          | 1         | 6.25%   |
| Fujitsu Siemens AMILO | 1         | 6.25%   |
| eMachines eME642G     | 1         | 6.25%   |
| ASUS X555LJ           | 1         | 6.25%   |
| ASUS A3L              | 1         | 6.25%   |
| Apple MacBook2        | 1         | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 4         | 25%     |
| 2011    | 2         | 12.5%   |
| 2005    | 2         | 12.5%   |
| 2021    | 1         | 6.25%   |
| 2019    | 1         | 6.25%   |
| 2017    | 1         | 6.25%   |
| 2016    | 1         | 6.25%   |
| 2010    | 1         | 6.25%   |
| 2007    | 1         | 6.25%   |
| 2006    | 1         | 6.25%   |
| Unknown | 1         | 6.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 16        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 15        | 93.75%  |
| Yes  | 1         | 6.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 6         | 37.5%   |
| 3.01-4.0   | 5         | 31.25%  |
| 0.51-1.0   | 2         | 12.5%   |
| 1.01-2.0   | 1         | 6.25%   |
| 0.01-0.5   | 1         | 6.25%   |
| 0          | 1         | 6.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 12        | 75%     |
| 0      | 4         | 25%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 14        | 87.5%   |
| Yes       | 2         | 12.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 93.75%  |
| No        | 1         | 6.25%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 93.75%  |
| No        | 1         | 6.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 8         | 50%     |
| No        | 8         | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Russia       | 3         | 18.75%  |
| Italy        | 3         | 18.75%  |
| Saudi Arabia | 2         | 12.5%   |
| Hungary      | 2         | 12.5%   |
| Vietnam      | 1         | 6.25%   |
| USA          | 1         | 6.25%   |
| India        | 1         | 6.25%   |
| Germany      | 1         | 6.25%   |
| Finland      | 1         | 6.25%   |
| Canada       | 1         | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Rome             | 3         | 17.65%  |
| Riyadh           | 2         | 11.76%  |
| Moscow           | 2         | 11.76%  |
| Gardony          | 2         | 11.76%  |
| Washington       | 1         | 5.88%   |
| Turenki          | 1         | 5.88%   |
| Surrey           | 1         | 5.88%   |
| Ozersk           | 1         | 5.88%   |
| Ladbergen        | 1         | 5.88%   |
| Ho Chi Minh City | 1         | 5.88%   |
| Genzano di Roma  | 1         | 5.88%   |
| Ahmedabad        | 1         | 5.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Intel               | 3         | 3      | 25%     |
| Seagate             | 2         | 2      | 16.67%  |
| Kingston            | 2         | 2      | 16.67%  |
| Hitachi             | 2         | 3      | 16.67%  |
| WDC                 | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| WDC WD1600BEVT-00A23T0 160GB    | 1         | 8.33%   |
| Seagate ST500VT000-1DK142 500GB | 1         | 8.33%   |
| Seagate ST500LT012-9WS142 500GB | 1         | 8.33%   |
| Samsung HM080HC 80GB            | 1         | 8.33%   |
| Kingston SA400S37240G 240GB     | 1         | 8.33%   |
| Kingston SA400S37120G 120GB     | 1         | 8.33%   |
| Intel SSDSC2KW120H6 120GB       | 1         | 8.33%   |
| Intel SSDSC2CW120A3 120GB       | 1         | 8.33%   |
| Intel SSDSC2BF180A4L 180GB      | 1         | 8.33%   |
| Hitachi HTS721060G9AT00 64GB    | 1         | 8.33%   |
| Hitachi HTS548040M9AT00 37GB    | 1         | 8.33%   |
| HGST HTS545050A7E680 500GB      | 1         | 8.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 28.57%  |
| Hitachi             | 2         | 3      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

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
| HDD  | 7         | 8      | 58.33%  |
| SSD  | 5         | 5      | 41.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 12        | 13     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 13     | 100%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 5         | 31.25%  |
| 251-500    | 3         | 18.75%  |
| 51-100     | 3         | 18.75%  |
| 1-20       | 2         | 12.5%   |
| 501-1000   | 2         | 12.5%   |
| 21-50      | 1         | 6.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 11        | 64.71%  |
| 21-50   | 3         | 17.65%  |
| 51-100  | 2         | 11.76%  |
| 101-250 | 1         | 5.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500VT000-1DK142 500GB | 1         | 1      | 14.29%  |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 14.29%  |
| Intel SSDSC2KW120H6 120GB       | 1         | 1      | 14.29%  |
| Intel SSDSC2CW120A3 120GB       | 1         | 1      | 14.29%  |
| Intel SSDSC2BF180A4L 180GB      | 1         | 1      | 14.29%  |
| Hitachi HTS721060G9AT00 64GB    | 1         | 1      | 14.29%  |
| Hitachi HTS548040M9AT00 37GB    | 1         | 2      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Intel   | 3         | 3      | 42.86%  |
| Seagate | 2         | 2      | 28.57%  |
| Hitachi | 2         | 3      | 28.57%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| Hitachi | 2         | 3      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 5      | 57.14%  |
| SSD  | 3         | 3      | 42.86%  |

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
| Malfunc  | 7         | 8      | 58.33%  |
| Works    | 4         | 4      | 33.33%  |
| Detected | 1         | 1      | 8.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 14        | 87.5%   |
| VIA Technologies | 1         | 6.25%   |
| AMD              | 1         | 6.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 17.65%  |
| Intel 82801DBM (ICH4-M) IDE Controller                                       | 2         | 11.76%  |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                  | 1         | 5.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 5.88%   |
| Intel Jasper Lake SATA AHCI Controller                                       | 1         | 5.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 5.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 1         | 5.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 1         | 5.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 1         | 5.88%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                | 1         | 5.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 5.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 5.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 5.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 11        | 64.71%  |
| IDE  | 6         | 35.29%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 13        | 81.25%  |
| AMD          | 2         | 12.5%   |
| 123456789ABC | 1         | 6.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel 686-class                        | 3         | 17.65%  |
| Intel Pentium M processor 1.60GHz      | 1         | 5.88%   |
| Intel Pentium M processor              | 1         | 5.88%   |
| Intel Pentium CPU 2020M @ 2.40GHz      | 1         | 5.88%   |
| Intel Core i7-5500U CPU @ 2.40GHz      | 1         | 5.88%   |
| Intel Core i7-2640M CPU @ 2.80GHz      | 1         | 5.88%   |
| Intel Core i5-4300U CPU @ 1.90GHz      | 1         | 5.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 1         | 5.88%   |
| Intel Core i5 CPU M 540 @ 2.53GHz      | 1         | 5.88%   |
| Intel Core i3-3217U CPU @ 1.80GHz      | 1         | 5.88%   |
| Intel Core 2 CPU T7200 @ 2.00GHz       | 1         | 5.88%   |
| Intel Core 2 CPU T7                    | 1         | 5.88%   |
| AMD Tillamook                          | 1         | 5.88%   |
| AMD Athlon II P340 Dual-Core Processor | 1         | 5.88%   |
| 123456789ABC Pentium 4                 | 1         | 5.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 3         | 17.65%  |
| Intel 686-class | 3         | 17.65%  |
| Other           | 2         | 11.76%  |
| Intel Pentium M | 2         | 11.76%  |
| Intel Core i7   | 2         | 11.76%  |
| Intel Core 2    | 2         | 11.76%  |
| Intel Pentium   | 1         | 5.88%   |
| Intel Core i3   | 1         | 5.88%   |
| AMD Athlon II   | 1         | 5.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 9         | 52.94%  |
| 2       | 8         | 47.06%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 14        | 82.35%  |
| Unknown | 3         | 17.65%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 9         | 52.94%  |
| 2       | 6         | 35.29%  |
| 1       | 2         | 11.76%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 5         | 29.41%  |
| IvyBridge   | 3         | 17.65%  |
| P6          | 2         | 11.76%  |
| Core        | 2         | 11.76%  |
| SandyBridge | 1         | 5.88%   |
| K10         | 1         | 5.88%   |
| Haswell     | 1         | 5.88%   |
| Geode       | 1         | 5.88%   |
| Broadwell   | 1         | 5.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 12        | 70.59%  |
| Nvidia               | 2         | 11.76%  |
| VIA Technologies     | 1         | 5.88%   |
| Trident Microsystems | 1         | 5.88%   |
| AMD                  | 1         | 5.88%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                              | Notebooks | Percent |
|------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                   | 3         | 15.79%  |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller      | 2         | 10.53%  |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller          | 2         | 10.53%  |
| Intel 82852/855GM Integrated Graphics Device                                       | 2         | 10.53%  |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]                  | 1         | 5.26%   |
| Trident Microsystems TGUI 9660/938x/968x                                           | 1         | 5.26%   |
| Nvidia GT218M [NVS 3100M]                                                          | 1         | 5.26%   |
| Nvidia GK208BM [GeForce 920M]                                                      | 1         | 5.26%   |
| Intel JasperLake [UHD Graphics]                                                    | 1         | 5.26%   |
| Intel HD Graphics 5500                                                             | 1         | 5.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                   | 1         | 5.26%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller | 1         | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller          | 1         | 5.26%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                       | 1         | 5.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 9         | 56.25%  |
| 2 x Intel                | 2         | 12.5%   |
| 1 x VIA                  | 1         | 6.25%   |
| 1 x Trident Microsystems | 1         | 6.25%   |
| 1 x Nvidia               | 1         | 6.25%   |
| Intel + Nvidia           | 1         | 6.25%   |
| 1 x AMD                  | 1         | 6.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 14        | 87.5%   |
| Unknown | 2         | 12.5%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 6         | 37.5%   |
| 1.01-2.0   | 5         | 31.25%  |
| Unknown    | 4         | 25%     |
| 3.01-4.0   | 1         | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 3         | 33.33%  |
| Chimei Innolux      | 2         | 22.22%  |
| Samsung Electronics | 1         | 11.11%  |
| LG Philips          | 1         | 11.11%  |
| Lenovo              | 1         | 11.11%  |
| Apple               | 1         | 11.11%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch | 1         | 11.11%  |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch          | 1         | 11.11%  |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch          | 1         | 11.11%  |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 11.11%  |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch          | 1         | 11.11%  |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 1         | 11.11%  |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 11.11%  |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch      | 1         | 11.11%  |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch               | 1         | 11.11%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 6         | 66.67%  |
| 1280x800 (WXGA) | 2         | 22.22%  |
| 1600x900 (HD+)  | 1         | 11.11%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 4         | 44.44%  |
| 13     | 4         | 44.44%  |
| 12     | 1         | 11.11%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 7         | 77.78%  |
| 201-300     | 2         | 22.22%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 7         | 77.78%  |
| 16/10 | 2         | 22.22%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 4         | 44.44%  |
| 101-110        | 3         | 33.33%  |
| 61-70          | 1         | 11.11%  |
| 91-100         | 1         | 11.11%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 6         | 66.67%  |
| 51-100  | 2         | 22.22%  |
| 121-160 | 1         | 11.11%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 12        | 75%     |
| 0     | 4         | 25%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 10        | 37.04%  |
| Qualcomm Atheros         | 6         | 22.22%  |
| Realtek Semiconductor    | 5         | 18.52%  |
| Broadcom                 | 2         | 7.41%   |
| VIA Technologies         | 1         | 3.7%    |
| Marvell Technology Group | 1         | 3.7%    |
| Huawei Technologies      | 1         | 3.7%    |
| D-Link                   | 1         | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 4         | 11.76%  |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 5.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 2         | 5.88%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 2.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 2.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2.94%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 2.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2.94%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.94%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 2.94%   |
| Intel Wireless 7265                                                                   | 1         | 2.94%   |
| Intel Wireless 7260                                                                   | 1         | 2.94%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 2.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 2.94%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 2.94%   |
| Intel PRO/100 VE Network Connection                                                   | 1         | 2.94%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.94%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 2.94%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller                     | 1         | 2.94%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                                    | 1         | 2.94%   |
| Intel 82577LM Gigabit Network Connection                                              | 1         | 2.94%   |
| Huawei USB Composite Device                                                           | 1         | 2.94%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 2.94%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                       | 1         | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 2.94%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 10        | 58.82%  |
| Qualcomm Atheros | 5         | 29.41%  |
| D-Link           | 1         | 5.88%   |
| Broadcom         | 1         | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 11.76%  |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 11.76%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 5.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 5.88%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 5.88%   |
| Intel Wireless 7265                                                                   | 1         | 5.88%   |
| Intel Wireless 7260                                                                   | 1         | 5.88%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 5.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 5.88%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 5.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 5.88%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 5.88%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 5.88%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 5.88%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 6         | 37.5%   |
| Realtek Semiconductor    | 5         | 31.25%  |
| VIA Technologies         | 1         | 6.25%   |
| Qualcomm Atheros         | 1         | 6.25%   |
| Marvell Technology Group | 1         | 6.25%   |
| Huawei Technologies      | 1         | 6.25%   |
| Broadcom                 | 1         | 6.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 25%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 12.5%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 6.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 6.25%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 6.25%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 6.25%   |
| Intel PRO/100 VE Network Connection                               | 1         | 6.25%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 6.25%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 6.25%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 6.25%   |
| Huawei USB Composite Device                                       | 1         | 6.25%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 6.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 15        | 48.39%  |
| Ethernet | 15        | 48.39%  |
| Modem    | 1         | 3.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 14        | 53.85%  |
| WiFi     | 12        | 46.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 15        | 93.75%  |
| 0     | 1         | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 13        | 81.25%  |
| Yes  | 3         | 18.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 5         | 55.56%  |
| IMC Networks            | 1         | 11.11%  |
| Cambridge Silicon Radio | 1         | 11.11%  |
| Broadcom                | 1         | 11.11%  |
| Apple                   | 1         | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 2         | 22.22%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 11.11%  |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 11.11%  |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 11.11%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 11.11%  |
| Apple Built-in iSight (no firmware loaded)          | 1         | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 13        | 81.25%  |
| VIA Technologies | 1         | 6.25%   |
| Nvidia           | 1         | 6.25%   |
| AMD              | 1         | 6.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 15.79%  |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 10.53%  |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 10.53%  |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 5.26%   |
| Nvidia High Definition Audio Controller                                    | 1         | 5.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 5.26%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 5.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 5.26%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 5.26%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 5.26%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 5.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 5.26%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 5.26%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 5.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 5         | 31.25%  |
| Samsung Electronics | 3         | 18.75%  |
| Micron Technology   | 2         | 12.5%   |
| Kingston            | 2         | 12.5%   |
| SK hynix            | 1         | 6.25%   |
| SHARETRONIC         | 1         | 6.25%   |
| Ramaxel Technology  | 1         | 6.25%   |
| Nanya Technology    | 1         | 6.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s               | 1         | 6.25%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 6.25%   |
| Unknown RAM Module 2GB SODIMM DDR3                         | 1         | 6.25%   |
| Unknown RAM Module 256MB SODIMM DDR                        | 1         | 6.25%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s             | 1         | 6.25%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 1         | 6.25%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1         | 6.25%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s      | 1         | 6.25%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 6.25%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 1         | 6.25%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 1         | 6.25%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 6.25%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s      | 1         | 6.25%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s     | 1         | 6.25%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2048MB SODIMM DDR3 1600MT/s | 1         | 6.25%   |
| Kingston RAM 9905428-026.A02LF 2048MB SODIMM DDR3 1066MT/s | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 8         | 66.67%  |
| SDRAM | 1         | 8.33%   |
| DRAM  | 1         | 8.33%   |
| DDR2  | 1         | 8.33%   |
| DDR   | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 12        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 2048 | 4         | 33.33%  |
| 4096 | 3         | 25%     |
| 512  | 2         | 16.67%  |
| 8192 | 1         | 8.33%   |
| 1024 | 1         | 8.33%   |
| 256  | 1         | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 3         | 21.43%  |
| 1067    | 2         | 14.29%  |
| Unknown | 2         | 14.29%  |
| 1867    | 1         | 7.14%   |
| 1334    | 1         | 7.14%   |
| 1333    | 1         | 7.14%   |
| 1066    | 1         | 7.14%   |
| 533     | 1         | 7.14%   |
| 266     | 1         | 7.14%   |
| 166     | 1         | 7.14%   |

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


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 3         | 30%     |
| Realtek Semiconductor | 2         | 20%     |
| Syntek                | 1         | 10%     |
| Quanta                | 1         | 10%     |
| Lenovo                | 1         | 10%     |
| ALi                   | 1         | 10%     |
| Acer                  | 1         | 10%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Chicony integrated camera            | 2         | 20%     |
| Syntek Lenovo EasyCamera             | 1         | 10%     |
| Realtek USB Camera                   | 1         | 10%     |
| Realtek Acer 640 x 480 laptop camera | 1         | 10%     |
| Quanta VGA WebCam                    | 1         | 10%     |
| Lenovo Integrated Webcam [R5U877]    | 1         | 10%     |
| Chicony Front Camera                 | 1         | 10%     |
| ALi Gateway Webcam                   | 1         | 10%     |
| Acer Integrated Camera               | 1         | 10%     |

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
| 1     | 6         | 37.5%   |
| 2     | 4         | 25%     |
| 0     | 3         | 18.75%  |
| 4     | 2         | 12.5%   |
| 5     | 1         | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 10        | 47.62%  |
| Graphics card            | 4         | 19.05%  |
| Net/wireless             | 3         | 14.29%  |
| Card reader              | 2         | 9.52%   |
| Storage                  | 1         | 4.76%   |
| Modem                    | 1         | 4.76%   |

