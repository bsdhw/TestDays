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

Total: 29

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Google        | Kohaku                      | [94c3c0f6b7](https://bsd-hardware.info/?probe=94c3c0f6b7) | Nov 26, 2023 |
| Google        | Kohaku                      | [198b445c4e](https://bsd-hardware.info/?probe=198b445c4e) | Nov 26, 2023 |
| Dell          | Vostro 3500                 | [875b045b38](https://bsd-hardware.info/?probe=875b045b38) | Oct 29, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
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
| NetBSD 9.2        | 5         | 20.83%  |
| NetBSD 9.3        | 4         | 16.67%  |
| NetBSD 9.1        | 4         | 16.67%  |
| NetBSD 9.0        | 3         | 12.5%   |
| NetBSD 9.99.94    | 1         | 4.17%   |
| NetBSD 9.2_STABLE | 1         | 4.17%   |
| NetBSD 9.0_STABLE | 1         | 4.17%   |
| NetBSD 8.99.51    | 1         | 4.17%   |
| NetBSD 7.2        | 1         | 4.17%   |
| NetBSD 10.99.10   | 1         | 4.17%   |
| NetBSD 10.99.1    | 1         | 4.17%   |
| NetBSD 10.0_BETA  | 1         | 4.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| NetBSD | 23        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 18        | 78.26%  |
| i386  | 5         | 21.74%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 8         | 33.33%  |
| XFCE         | 4         | 16.67%  |
| ctwm         | 3         | 12.5%   |
| Fluxbox      | 2         | 8.33%   |
| DWM          | 2         | 8.33%   |
| sdorfehs     | 1         | 4.17%   |
| MATE         | 1         | 4.17%   |
| LXQt         | 1         | 4.17%   |
| helloDesktop | 1         | 4.17%   |
| Awesome      | 1         | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 20        | 86.96%  |
| Console | 3         | 13.04%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 20        | 86.96%  |
| XDM     | 1         | 4.35%   |
| SLiM    | 1         | 4.35%   |
| GDM     | 1         | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 16        | 69.57%  |
| en_US   | 6         | 26.09%  |
| ru_RU   | 1         | 4.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 23        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 23        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 12        | 52.17%  |
| Unknown | 11        | 47.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 8         | 34.78%  |
| Dell             | 2         | 8.7%    |
| ASUSTek Computer | 2         | 8.7%    |
| Acer             | 2         | 8.7%    |
| Toshiba          | 1         | 4.35%   |
| Sony             | 1         | 4.35%   |
| MiTAC            | 1         | 4.35%   |
| IBM              | 1         | 4.35%   |
| Hewlett-Packard  | 1         | 4.35%   |
| Google           | 1         | 4.35%   |
| Fujitsu Siemens  | 1         | 4.35%   |
| eMachines        | 1         | 4.35%   |
| Apple            | 1         | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Toshiba Satellite A100           | 1         | 4.35%   |
| Sony SVF1421DSGW                 | 1         | 4.35%   |
| MiTAC 5033                       | 1         | 4.35%   |
| Lenovo ThinkPad X240 20AMS0J01N  | 1         | 4.35%   |
| Lenovo ThinkPad T510 4313CTO     | 1         | 4.35%   |
| Lenovo ThinkPad T460s 20FAS3L002 | 1         | 4.35%   |
| Lenovo ThinkPad T430s 23564H3    | 1         | 4.35%   |
| Lenovo ThinkPad T430 2347A45     | 1         | 4.35%   |
| Lenovo ThinkPad T420 4236D26     | 1         | 4.35%   |
| Lenovo ThinkPad 13 20GJCTO1WW    | 1         | 4.35%   |
| Lenovo G500 20236                | 1         | 4.35%   |
| IBM ThinkPad R51 2887AVG         | 1         | 4.35%   |
| HP Pavilion 17                   | 1         | 4.35%   |
| Google Kohaku                    | 1         | 4.35%   |
| Fujitsu Siemens AMILO L7310      | 1         | 4.35%   |
| eMachines eME642G                | 1         | 4.35%   |
| Dell Vostro 3500                 | 1         | 4.35%   |
| Dell Precision M4500             | 1         | 4.35%   |
| ASUS X555LJ                      | 1         | 4.35%   |
| ASUS A3L                         | 1         | 4.35%   |
| Apple MacBook2,1                 | 1         | 4.35%   |
| Acer Aspire ES1-132              | 1         | 4.35%   |
| Acer Aspire A114-33              | 1         | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 7         | 30.43%  |
| Acer Aspire           | 2         | 8.7%    |
| Toshiba Satellite     | 1         | 4.35%   |
| Sony SVF1421DSGW      | 1         | 4.35%   |
| MiTAC 5033            | 1         | 4.35%   |
| Lenovo G500           | 1         | 4.35%   |
| IBM ThinkPad          | 1         | 4.35%   |
| HP Pavilion           | 1         | 4.35%   |
| Google Kohaku         | 1         | 4.35%   |
| Fujitsu Siemens AMILO | 1         | 4.35%   |
| eMachines eME642G     | 1         | 4.35%   |
| Dell Vostro           | 1         | 4.35%   |
| Dell Precision        | 1         | 4.35%   |
| ASUS X555LJ           | 1         | 4.35%   |
| ASUS A3L              | 1         | 4.35%   |
| Apple MacBook2        | 1         | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 5         | 21.74%  |
| 2005    | 3         | 13.04%  |
| 2021    | 2         | 8.7%    |
| 2016    | 2         | 8.7%    |
| 2011    | 2         | 8.7%    |
| 2010    | 2         | 8.7%    |
| 2007    | 2         | 8.7%    |
| 2022    | 1         | 4.35%   |
| 2019    | 1         | 4.35%   |
| 2017    | 1         | 4.35%   |
| 2014    | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 23        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 91.3%   |
| Yes  | 2         | 8.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 9         | 39.13%  |
| 3.01-4.0   | 5         | 21.74%  |
| 8.01-16.0  | 3         | 13.04%  |
| 0.51-1.0   | 2         | 8.7%    |
| 16.01-24.0 | 1         | 4.35%   |
| 1.01-2.0   | 1         | 4.35%   |
| 0.01-0.5   | 1         | 4.35%   |
| 0          | 1         | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 23        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 14        | 60.87%  |
| 0      | 9         | 39.13%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 86.96%  |
| Yes       | 3         | 13.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 86.96%  |
| No        | 3         | 13.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 95.65%  |
| No        | 1         | 4.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13        | 56.52%  |
| No        | 10        | 43.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Italy        | 4         | 17.39%  |
| USA          | 3         | 13.04%  |
| Russia       | 3         | 13.04%  |
| Vietnam      | 2         | 8.7%    |
| Saudi Arabia | 2         | 8.7%    |
| Hungary      | 2         | 8.7%    |
| Germany      | 2         | 8.7%    |
| India        | 1         | 4.35%   |
| France       | 1         | 4.35%   |
| Finland      | 1         | 4.35%   |
| China        | 1         | 4.35%   |
| Canada       | 1         | 4.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Rome             | 4         | 16.67%  |
| Riyadh           | 2         | 8.33%   |
| Moscow           | 2         | 8.33%   |
| Ho Chi Minh City | 2         | 8.33%   |
| Gardony          | 2         | 8.33%   |
| Washington       | 1         | 4.17%   |
| Turenki          | 1         | 4.17%   |
| Surrey           | 1         | 4.17%   |
| Sun Prairie      | 1         | 4.17%   |
| Ozersk           | 1         | 4.17%   |
| Ladbergen        | 1         | 4.17%   |
| Kalispell        | 1         | 4.17%   |
| Genzano di Roma  | 1         | 4.17%   |
| Chengdu          | 1         | 4.17%   |
| Carry-le-Rouet   | 1         | 4.17%   |
| Berlin           | 1         | 4.17%   |
| Ahmedabad        | 1         | 4.17%   |

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
| 101-250    | 8         | 34.78%  |
| 251-500    | 6         | 26.09%  |
| 501-1000   | 3         | 13.04%  |
| 51-100     | 3         | 13.04%  |
| 1-20       | 2         | 8.7%    |
| 21-50      | 1         | 4.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 17        | 70.83%  |
| 21-50   | 4         | 16.67%  |
| 51-100  | 2         | 8.33%   |
| 101-250 | 1         | 4.17%   |

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


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 20        | 80%     |
| AMD                            | 2         | 8%      |
| VIA Technologies               | 1         | 4%      |
| Solid State Storage Technology | 1         | 4%      |
| Kingston Technology Company    | 1         | 4%      |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 14.81%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 7.41%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                       | 2         | 7.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 7.41%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                  | 1         | 3.7%    |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 1         | 3.7%    |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 3.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 3.7%    |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 3.7%    |
| Intel Jasper Lake SATA AHCI Controller                                       | 1         | 3.7%    |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 3.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 3.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 1         | 3.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 1         | 3.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 1         | 3.7%    |
| Intel 82371AB/EB/MB PIIX4 IDE                                                | 1         | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                          | 1         | 3.7%    |
| AMD FCH IDE Controller                                                       | 1         | 3.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 18        | 66.67%  |
| IDE  | 7         | 25.93%  |
| NVMe | 2         | 7.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 19        | 82.61%  |
| AMD          | 3         | 13.04%  |
| 123456789ABC | 1         | 4.35%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel 686-class                           | 3         | 12.5%   |
| Intel Pentium M processor 1.60GHz         | 1         | 4.17%   |
| Intel Pentium M processor                 | 1         | 4.17%   |
| Intel Pentium CPU 2020M @ 2.40GHz         | 1         | 4.17%   |
| Intel Core i7-5500U CPU @ 2.40GHz         | 1         | 4.17%   |
| Intel Core i7-3520M CPU @ 2.90GHz         | 1         | 4.17%   |
| Intel Core i7-2640M CPU @ 2.80GHz         | 1         | 4.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz         | 1         | 4.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 1         | 4.17%   |
| Intel Core i5-4300U CPU @ 1.90GHz         | 1         | 4.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz         | 1         | 4.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz        | 1         | 4.17%   |
| Intel Core i5 CPU M 560 @ 2.67GH          | 1         | 4.17%   |
| Intel Core i5 CPU M 540 @ 2.53GHz         | 1         | 4.17%   |
| Intel Core i3-3217U CPU @ 1.80GHz         | 1         | 4.17%   |
| Intel Core 2 CPU T7200 @ 2.00GHz          | 1         | 4.17%   |
| Intel Core 2 CPU T7                       | 1         | 4.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz   | 1         | 4.17%   |
| AMD Tillamook                             | 1         | 4.17%   |
| AMD Athlon II P340 Dual-Core Processor    | 1         | 4.17%   |
| AMD A10-5745M APU with Radeon HD Graphics | 1         | 4.17%   |
| 123456789ABC Pentium 4                    | 1         | 4.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 7         | 29.17%  |
| Other           | 3         | 12.5%   |
| Intel Core i7   | 3         | 12.5%   |
| Intel 686-class | 3         | 12.5%   |
| Intel Pentium M | 2         | 8.33%   |
| Intel Core 2    | 2         | 8.33%   |
| Intel Pentium   | 1         | 4.17%   |
| Intel Core i3   | 1         | 4.17%   |
| AMD Athlon II   | 1         | 4.17%   |
| AMD A10         | 1         | 4.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 12        | 50%     |
| Unknown | 9         | 37.5%   |
| 4       | 3         | 12.5%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 21        | 87.5%   |
| Unknown | 3         | 12.5%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 11        | 45.83%  |
| Unknown | 9         | 37.5%   |
| 1       | 4         | 16.67%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 5         | 20.83%  |
| IvyBridge   | 4         | 16.67%  |
| Skylake     | 2         | 8.33%   |
| P6          | 2         | 8.33%   |
| Core        | 2         | 8.33%   |
| Westmere    | 1         | 4.17%   |
| TigerLake   | 1         | 4.17%   |
| SandyBridge | 1         | 4.17%   |
| Piledriver  | 1         | 4.17%   |
| KabyLake    | 1         | 4.17%   |
| K10         | 1         | 4.17%   |
| Haswell     | 1         | 4.17%   |
| Geode       | 1         | 4.17%   |
| Broadwell   | 1         | 4.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 17        | 70.83%  |
| Nvidia               | 3         | 12.5%   |
| AMD                  | 2         | 8.33%   |
| VIA Technologies     | 1         | 4.17%   |
| Trident Microsystems | 1         | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 15.38%  |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 7.69%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 7.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 7.69%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 7.69%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]             | 1         | 3.85%   |
| Trident Microsystems TGUI 9660/938x/968x                                      | 1         | 3.85%   |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 3.85%   |
| Nvidia GT216GLM [Quadro FX 880M]                                              | 1         | 3.85%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 3.85%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 3.85%   |
| Intel HD Graphics 5500                                                        | 1         | 3.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 3.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 3.85%   |
| Intel Apollo Lake [HD Graphics 505]                                           | 1         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 3.85%   |
| AMD Richland [Radeon HD 8610G]                                                | 1         | 3.85%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                  | 1         | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 14        | 60.87%  |
| 2 x Intel                | 2         | 8.7%    |
| 1 x Nvidia               | 2         | 8.7%    |
| 1 x AMD                  | 2         | 8.7%    |
| 1 x VIA                  | 1         | 4.35%   |
| 1 x Trident Microsystems | 1         | 4.35%   |
| Intel + Nvidia           | 1         | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 19        | 82.61%  |
| Unknown | 4         | 17.39%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 8         | 34.78%  |
| 1.01-2.0   | 6         | 26.09%  |
| 0.01-0.5   | 6         | 26.09%  |
| 0.51-1.0   | 2         | 8.7%    |
| 3.01-4.0   | 1         | 4.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 5         | 41.67%  |
| Samsung Electronics | 2         | 16.67%  |
| Chimei Innolux      | 2         | 16.67%  |
| LG Philips          | 1         | 8.33%   |
| Lenovo              | 1         | 8.33%   |
| Apple               | 1         | 8.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch | 1         | 8.33%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch | 1         | 8.33%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch          | 1         | 8.33%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch          | 1         | 8.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch         | 1         | 8.33%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch          | 1         | 8.33%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch          | 1         | 8.33%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch          | 1         | 8.33%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch              | 1         | 8.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch      | 1         | 8.33%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch      | 1         | 8.33%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch               | 1         | 8.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 6         | 50%     |
| 1600x900 (HD+)  | 3         | 25%     |
| 1280x800 (WXGA) | 2         | 16.67%  |
| 1920x1080 (FHD) | 1         | 8.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 6         | 50%     |
| 15     | 5         | 41.67%  |
| 12     | 1         | 8.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 10        | 83.33%  |
| 201-300     | 2         | 16.67%  |

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
| 81-90          | 6         | 50%     |
| 101-110        | 3         | 25%     |
| 91-100         | 2         | 16.67%  |
| 61-70          | 1         | 8.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 7         | 58.33%  |
| 121-160 | 3         | 25%     |
| 51-100  | 2         | 16.67%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 17        | 73.91%  |
| 0     | 6         | 26.09%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 15        | 39.47%  |
| Realtek Semiconductor             | 8         | 21.05%  |
| Qualcomm Atheros                  | 6         | 15.79%  |
| Broadcom                          | 2         | 5.26%   |
| VIA Technologies                  | 1         | 2.63%   |
| TP-Link                           | 1         | 2.63%   |
| Qualcomm Atheros Communications   | 1         | 2.63%   |
| Marvell Technology Group          | 1         | 2.63%   |
| Huawei Technologies               | 1         | 2.63%   |
| Ericsson Business Mobile Networks | 1         | 2.63%   |
| D-Link                            | 1         | 2.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 5         | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3         | 6%      |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 4%      |
| Intel Wireless 8260                                                                   | 2         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 4%      |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 2%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 2%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 2%      |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 2%      |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1         | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 2%      |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 2%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2%      |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2%      |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 2%      |
| Intel Wireless 7265                                                                   | 1         | 2%      |
| Intel Wireless 7260                                                                   | 1         | 2%      |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 2%      |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 2%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 2%      |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 2%      |
| Intel PRO/100 VE Network Connection                                                   | 1         | 2%      |
| Intel Ethernet Connection I219-V                                                      | 1         | 2%      |
| Intel Ethernet Connection I219-LM                                                     | 1         | 2%      |
| Intel Ethernet Connection I218-LM                                                     | 1         | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 2%      |
| Intel Centrino Wireless-N 135                                                         | 1         | 2%      |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 2%      |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 2%      |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller                     | 1         | 2%      |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                                    | 1         | 2%      |
| Intel 82577LM Gigabit Network Connection                                              | 1         | 2%      |
| Huawei USB Device                                                                     | 1         | 2%      |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module                    | 1         | 2%      |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 2%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                       | 1         | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 56%     |
| Qualcomm Atheros                | 5         | 20%     |
| Realtek Semiconductor           | 2         | 8%      |
| TP-Link                         | 1         | 4%      |
| Qualcomm Atheros Communications | 1         | 4%      |
| D-Link                          | 1         | 4%      |
| Broadcom                        | 1         | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 7.69%   |
| Intel Wireless 8260                                                                   | 2         | 7.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 7.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 3.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 3.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 3.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 3.85%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 3.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 3.85%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 3.85%   |
| Intel Wireless 7265                                                                   | 1         | 3.85%   |
| Intel Wireless 7260                                                                   | 1         | 3.85%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 3.85%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 3.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 3.85%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 3.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 3.85%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 3.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 3.85%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 3.85%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 9         | 42.86%  |
| Realtek Semiconductor    | 7         | 33.33%  |
| VIA Technologies         | 1         | 4.76%   |
| Qualcomm Atheros         | 1         | 4.76%   |
| Marvell Technology Group | 1         | 4.76%   |
| Huawei Technologies      | 1         | 4.76%   |
| Broadcom                 | 1         | 4.76%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5         | 23.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 14.29%  |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 4.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 4.76%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 4.76%   |
| Intel PRO/100 VE Network Connection                               | 1         | 4.76%   |
| Intel Ethernet Connection I219-V                                  | 1         | 4.76%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 4.76%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.76%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 4.76%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 4.76%   |
| Huawei USB Device                                                 | 1         | 4.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 47.73%  |
| Ethernet | 20        | 45.45%  |
| Modem    | 2         | 4.55%   |
| Unknown  | 1         | 2.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17        | 53.13%  |
| Ethernet | 14        | 43.75%  |
| Unknown  | 1         | 3.13%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 86.96%  |
| 0     | 2         | 8.7%    |
| 1     | 1         | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 18        | 78.26%  |
| Yes  | 5         | 21.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 9         | 64.29%  |
| Broadcom                | 2         | 14.29%  |
| IMC Networks            | 1         | 7.14%   |
| Cambridge Silicon Radio | 1         | 7.14%   |
| Apple                   | 1         | 7.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 28.57%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 14.29%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 14.29%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 7.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 7.14%   |
| Intel AX201 Bluetooth                               | 1         | 7.14%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 7.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 7.14%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 7.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 19        | 79.17%  |
| Nvidia           | 2         | 8.33%   |
| AMD              | 2         | 8.33%   |
| VIA Technologies | 1         | 4.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 14.29%  |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 7.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 7.14%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 7.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 7.14%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 3.57%   |
| Nvidia High Definition Audio Controller                                    | 1         | 3.57%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 3.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 3.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 3.57%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 3.57%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 3.57%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 3.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 3.57%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 3.57%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 3.57%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 3.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 3.57%   |
| AMD FCH Azalia Controller                                                  | 1         | 3.57%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 3.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 5         | 19.23%  |
| SK hynix            | 5         | 19.23%  |
| Samsung Electronics | 5         | 19.23%  |
| Ramaxel Technology  | 2         | 7.69%   |
| Micron Technology   | 2         | 7.69%   |
| Kingston            | 2         | 7.69%   |
| SHARETRONIC         | 1         | 3.85%   |
| Nanya Technology    | 1         | 3.85%   |
| G.Skill             | 1         | 3.85%   |
| A-DATA Technology   | 1         | 3.85%   |
| Unknown             | 1         | 3.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 2         | 7.69%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s               | 1         | 3.85%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 3.85%   |
| Unknown RAM Module 2GB SODIMM DDR3                         | 1         | 3.85%   |
| Unknown RAM Module 256MB SODIMM DDR                        | 1         | 3.85%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s             | 1         | 3.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 1         | 3.85%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 1         | 3.85%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 3.85%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1         | 3.85%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s        | 1         | 3.85%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s      | 1         | 3.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 3.85%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s   | 1         | 3.85%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 3.85%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s      | 1         | 3.85%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s     | 1         | 3.85%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| Kingston RAM 9905428-026.A02LF 2048MB SODIMM DDR3 1066MT/s | 1         | 3.85%   |
| G.Skill RAM F4-3200C22-8GRS 8GB SODIMM DDR4 3200MT/s       | 1         | 3.85%   |
| A-DATA RAM AM1L16BC4R1-B1PS 4GB SODIMM DDR3 1600MT/s       | 1         | 3.85%   |
| Unknown                                                    | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 11        | 57.89%  |
| DDR4   | 3         | 15.79%  |
| SDRAM  | 1         | 5.26%   |
| LPDDR3 | 1         | 5.26%   |
| DRAM   | 1         | 5.26%   |
| DDR2   | 1         | 5.26%   |
| DDR    | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 17        | 89.47%  |
| Row Of Chips | 1         | 5.26%   |
| Chip         | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 6         | 30%     |
| 8192 | 5         | 25%     |
| 2048 | 5         | 25%     |
| 512  | 2         | 10%     |
| 1024 | 1         | 5%      |
| 256  | 1         | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 5         | 22.73%  |
| 2133    | 3         | 13.64%  |
| 1867    | 2         | 9.09%   |
| 1334    | 2         | 9.09%   |
| 1067    | 2         | 9.09%   |
| Unknown | 2         | 9.09%   |
| 3200    | 1         | 4.55%   |
| 1333    | 1         | 4.55%   |
| 1066    | 1         | 4.55%   |
| 533     | 1         | 4.55%   |
| 266     | 1         | 4.55%   |
| 166     | 1         | 4.55%   |

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
| Chicony Electronics           | 6         | 40%     |
| Realtek Semiconductor         | 2         | 13.33%  |
| Syntek                        | 1         | 6.67%   |
| Sunplus Innovation Technology | 1         | 6.67%   |
| Quanta                        | 1         | 6.67%   |
| Microdia                      | 1         | 6.67%   |
| Lenovo                        | 1         | 6.67%   |
| Bison Electronics             | 1         | 6.67%   |
| ALi                           | 1         | 6.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 3         | 18.75%  |
| Syntek Lenovo EasyCamera             | 1         | 6.25%   |
| Sunplus Integrated Camera            | 1         | 6.25%   |
| Realtek USB Camera                   | 1         | 6.25%   |
| Realtek Acer 640 x 480 laptop camera | 1         | 6.25%   |
| Quanta VGA WebCam                    | 1         | 6.25%   |
| Microdia Integrated_Webcam_HD        | 1         | 6.25%   |
| Lenovo Integrated Webcam [R5U877]    | 1         | 6.25%   |
| Chicony Thinkpad T430 camera         | 1         | 6.25%   |
| Chicony Front Camera                 | 1         | 6.25%   |
| Chicony 8M Camera                    | 1         | 6.25%   |
| Chicony 720p HD Camera               | 1         | 6.25%   |
| Bison Integrated Camera              | 1         | 6.25%   |
| ALi Gateway Webcam                   | 1         | 6.25%   |

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
| 2     | 7         | 30.43%  |
| 1     | 7         | 30.43%  |
| 0     | 4         | 17.39%  |
| 4     | 2         | 8.7%    |
| 3     | 2         | 8.7%    |
| 5     | 1         | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 15        | 46.88%  |
| Net/wireless             | 6         | 18.75%  |
| Graphics card            | 4         | 12.5%   |
| Card reader              | 4         | 12.5%   |
| Storage                  | 1         | 3.13%   |
| Sound                    | 1         | 3.13%   |
| Modem                    | 1         | 3.13%   |

