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

Total: 31

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T470 20HES0EV0A    | [05ecc99fe8](https://bsd-hardware.info/?probe=05ecc99fe8) | Feb 13, 2024 |
| Samsung       | N150/N210/N220              | [92c052e0d7](https://bsd-hardware.info/?probe=92c052e0d7) | Jan 14, 2024 |
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
| NetBSD 9.2        | 5         | 19.23%  |
| NetBSD 9.3        | 4         | 15.38%  |
| NetBSD 9.1        | 4         | 15.38%  |
| NetBSD 9.0        | 3         | 11.54%  |
| NetBSD 9.99.94    | 1         | 3.85%   |
| NetBSD 9.2_STABLE | 1         | 3.85%   |
| NetBSD 9.0_STABLE | 1         | 3.85%   |
| NetBSD 8.99.51    | 1         | 3.85%   |
| NetBSD 7.2        | 1         | 3.85%   |
| NetBSD 10.99.10   | 1         | 3.85%   |
| NetBSD 10.99.1    | 1         | 3.85%   |
| NetBSD 10.0_RC3   | 1         | 3.85%   |
| NetBSD 10.0_RC2   | 1         | 3.85%   |
| NetBSD 10.0_BETA  | 1         | 3.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| NetBSD | 25        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 19        | 76%     |
| i386  | 6         | 24%     |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 8         | 30.77%  |
| XFCE         | 6         | 23.08%  |
| ctwm         | 3         | 11.54%  |
| Fluxbox      | 2         | 7.69%   |
| DWM          | 2         | 7.69%   |
| sdorfehs     | 1         | 3.85%   |
| MATE         | 1         | 3.85%   |
| LXQt         | 1         | 3.85%   |
| helloDesktop | 1         | 3.85%   |
| Awesome      | 1         | 3.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 22        | 88%     |
| Console | 3         | 12%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 20        | 80%     |
| SLiM    | 3         | 12%     |
| XDM     | 1         | 4%      |
| GDM     | 1         | 4%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 17        | 68%     |
| en_US   | 6         | 24%     |
| ru_RU   | 1         | 4%      |
| fr_FR   | 1         | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 25        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 25        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 13        | 52%     |
| Unknown | 12        | 48%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 9         | 36%     |
| Dell                | 2         | 8%      |
| ASUSTek Computer    | 2         | 8%      |
| Acer                | 2         | 8%      |
| Toshiba             | 1         | 4%      |
| Sony                | 1         | 4%      |
| Samsung Electronics | 1         | 4%      |
| MiTAC               | 1         | 4%      |
| IBM                 | 1         | 4%      |
| Hewlett-Packard     | 1         | 4%      |
| Google              | 1         | 4%      |
| Fujitsu Siemens     | 1         | 4%      |
| eMachines           | 1         | 4%      |
| Apple               | 1         | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Toshiba Satellite A100           | 1         | 4%      |
| Sony SVF1421DSGW                 | 1         | 4%      |
| Samsung N150/N210/N220           | 1         | 4%      |
| MiTAC 5033                       | 1         | 4%      |
| Lenovo ThinkPad X240 20AMS0J01N  | 1         | 4%      |
| Lenovo ThinkPad T510 4313CTO     | 1         | 4%      |
| Lenovo ThinkPad T470 20HES0EV0A  | 1         | 4%      |
| Lenovo ThinkPad T460s 20FAS3L002 | 1         | 4%      |
| Lenovo ThinkPad T430s 23564H3    | 1         | 4%      |
| Lenovo ThinkPad T430 2347A45     | 1         | 4%      |
| Lenovo ThinkPad T420 4236D26     | 1         | 4%      |
| Lenovo ThinkPad 13 20GJCTO1WW    | 1         | 4%      |
| Lenovo G500 20236                | 1         | 4%      |
| IBM ThinkPad R51 2887AVG         | 1         | 4%      |
| HP Pavilion 17                   | 1         | 4%      |
| Google Kohaku                    | 1         | 4%      |
| Fujitsu Siemens AMILO L7310      | 1         | 4%      |
| eMachines eME642G                | 1         | 4%      |
| Dell Vostro 3500                 | 1         | 4%      |
| Dell Precision M4500             | 1         | 4%      |
| ASUS X555LJ                      | 1         | 4%      |
| ASUS A3L                         | 1         | 4%      |
| Apple MacBook2,1                 | 1         | 4%      |
| Acer Aspire ES1-132              | 1         | 4%      |
| Acer Aspire A114-33              | 1         | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 8         | 32%     |
| Acer Aspire           | 2         | 8%      |
| Toshiba Satellite     | 1         | 4%      |
| Sony SVF1421DSGW      | 1         | 4%      |
| Samsung N150          | 1         | 4%      |
| MiTAC 5033            | 1         | 4%      |
| Lenovo G500           | 1         | 4%      |
| IBM ThinkPad          | 1         | 4%      |
| HP Pavilion           | 1         | 4%      |
| Google Kohaku         | 1         | 4%      |
| Fujitsu Siemens AMILO | 1         | 4%      |
| eMachines eME642G     | 1         | 4%      |
| Dell Vostro           | 1         | 4%      |
| Dell Precision        | 1         | 4%      |
| ASUS X555LJ           | 1         | 4%      |
| ASUS A3L              | 1         | 4%      |
| Apple MacBook2        | 1         | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 5         | 20%     |
| 2010    | 3         | 12%     |
| 2005    | 3         | 12%     |
| 2021    | 2         | 8%      |
| 2016    | 2         | 8%      |
| 2011    | 2         | 8%      |
| 2007    | 2         | 8%      |
| 2022    | 1         | 4%      |
| 2019    | 1         | 4%      |
| 2018    | 1         | 4%      |
| 2017    | 1         | 4%      |
| 2014    | 1         | 4%      |
| Unknown | 1         | 4%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 25        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 92%     |
| Yes  | 2         | 8%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 9         | 36%     |
| 3.01-4.0   | 5         | 20%     |
| 8.01-16.0  | 3         | 12%     |
| 0.51-1.0   | 3         | 12%     |
| 16.01-24.0 | 2         | 8%      |
| 1.01-2.0   | 1         | 4%      |
| 0.01-0.5   | 1         | 4%      |
| 0          | 1         | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 25        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 15        | 60%     |
| 0      | 10        | 40%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 22        | 88%     |
| Yes       | 3         | 12%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 88%     |
| No        | 3         | 12%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 96%     |
| No        | 1         | 4%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 14        | 56%     |
| No        | 11        | 44%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Italy        | 4         | 16%     |
| USA          | 3         | 12%     |
| Russia       | 3         | 12%     |
| France       | 3         | 12%     |
| Vietnam      | 2         | 8%      |
| Saudi Arabia | 2         | 8%      |
| Hungary      | 2         | 8%      |
| Germany      | 2         | 8%      |
| India        | 1         | 4%      |
| Finland      | 1         | 4%      |
| China        | 1         | 4%      |
| Canada       | 1         | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Rome             | 4         | 15.38%  |
| Riyadh           | 2         | 7.69%   |
| Moscow           | 2         | 7.69%   |
| Ho Chi Minh City | 2         | 7.69%   |
| Gardony          | 2         | 7.69%   |
| Washington       | 1         | 3.85%   |
| Turenki          | 1         | 3.85%   |
| Surrey           | 1         | 3.85%   |
| Sun Prairie      | 1         | 3.85%   |
| Ozersk           | 1         | 3.85%   |
| Noyon            | 1         | 3.85%   |
| Ladbergen        | 1         | 3.85%   |
| Kalispell        | 1         | 3.85%   |
| Genzano di Roma  | 1         | 3.85%   |
| Chengdu          | 1         | 3.85%   |
| Carry-le-Rouet   | 1         | 3.85%   |
| Berlin           | 1         | 3.85%   |
| Amiens           | 1         | 3.85%   |
| Ahmedabad        | 1         | 3.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 21.43%  |
| Intel               | 3         | 3      | 21.43%  |
| Hitachi             | 3         | 4      | 21.43%  |
| Kingston            | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD1600BEVT-00A23T0 160GB        | 1         | 7.14%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 7.14%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 7.14%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 7.14%   |
| Samsung HM080HC 80GB                | 1         | 7.14%   |
| Kingston SA400S37240G 240GB         | 1         | 7.14%   |
| Kingston SA400S37120G 120GB         | 1         | 7.14%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 7.14%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 7.14%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 7.14%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 7.14%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 7.14%   |
| Hitachi HTS545025B9A300 250GB       | 1         | 7.14%   |
| HGST HTS545050A7E680 500GB          | 1         | 7.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 33.33%  |
| Hitachi             | 3         | 4      | 33.33%  |
| WDC                 | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| HGST                | 1         | 1      | 11.11%  |

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
| HDD  | 9         | 10     | 64.29%  |
| SSD  | 5         | 5      | 35.71%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 14        | 15     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 13        | 14     | 92.86%  |
| 0.51-1.0   | 1         | 1      | 7.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 10        | 40%     |
| 251-500    | 6         | 24%     |
| 501-1000   | 3         | 12%     |
| 51-100     | 3         | 12%     |
| 1-20       | 2         | 8%      |
| 21-50      | 1         | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 18        | 69.23%  |
| 21-50   | 5         | 19.23%  |
| 51-100  | 2         | 7.69%   |
| 101-250 | 1         | 3.85%   |

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
| Malfunc  | 8         | 9      | 57.14%  |
| Works    | 5         | 5      | 35.71%  |
| Detected | 1         | 1      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 22        | 81.48%  |
| AMD                            | 2         | 7.41%   |
| VIA Technologies               | 1         | 3.7%    |
| Solid State Storage Technology | 1         | 3.7%    |
| Kingston Technology Company    | 1         | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 4         | 13.79%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 10.34%  |
| Intel 82801DBM (ICH4-M) IDE Controller                                       | 2         | 6.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 6.9%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                  | 1         | 3.45%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 1         | 3.45%   |
| Kingston Company OM3PDP3 NVMe SSD                                            | 1         | 3.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 3.45%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 3.45%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 3.45%   |
| Intel Jasper Lake SATA AHCI Controller                                       | 1         | 3.45%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 3.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 3.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 1         | 3.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 1         | 3.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 1         | 3.45%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                | 1         | 3.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 1         | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 1         | 3.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 1         | 3.45%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 1         | 3.45%   |
| AMD FCH IDE Controller                                                       | 1         | 3.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 20        | 68.97%  |
| IDE  | 7         | 24.14%  |
| NVMe | 2         | 6.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 21        | 84%     |
| AMD          | 3         | 12%     |
| 123456789ABC | 1         | 4%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel 686-class                           | 3         | 11.54%  |
| Intel Pentium M processor 1.60GHz         | 1         | 3.85%   |
| Intel Pentium M processor                 | 1         | 3.85%   |
| Intel Pentium CPU 2020M @ 2.40GHz         | 1         | 3.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz         | 1         | 3.85%   |
| Intel Core i7-3520M CPU @ 2.90GHz         | 1         | 3.85%   |
| Intel Core i7-2640M CPU @ 2.80GHz         | 1         | 3.85%   |
| Intel Core i5-7300U CPU @ 2.60GHz         | 1         | 3.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz         | 1         | 3.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 1         | 3.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz         | 1         | 3.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz         | 1         | 3.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz        | 1         | 3.85%   |
| Intel Core i5 CPU M 560 @ 2.67GH          | 1         | 3.85%   |
| Intel Core i5 CPU M 540 @ 2.53GHz         | 1         | 3.85%   |
| Intel Core i3-3217U CPU @ 1.80GHz         | 1         | 3.85%   |
| Intel Core 2 CPU T7200 @ 2.00GHz          | 1         | 3.85%   |
| Intel Core 2 CPU T7                       | 1         | 3.85%   |
| Intel Atom CPU N450 @ 1.66GHz             | 1         | 3.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz   | 1         | 3.85%   |
| AMD Tillamook                             | 1         | 3.85%   |
| AMD Athlon II P340 Dual-Core Processor    | 1         | 3.85%   |
| AMD A10-5745M APU with Radeon HD Graphics | 1         | 3.85%   |
| 123456789ABC Pentium 4                    | 1         | 3.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 8         | 30.77%  |
| Other           | 3         | 11.54%  |
| Intel Core i7   | 3         | 11.54%  |
| Intel 686-class | 3         | 11.54%  |
| Intel Pentium M | 2         | 7.69%   |
| Intel Core 2    | 2         | 7.69%   |
| Intel Pentium   | 1         | 3.85%   |
| Intel Core i3   | 1         | 3.85%   |
| Intel Atom      | 1         | 3.85%   |
| AMD Athlon II   | 1         | 3.85%   |
| AMD A10         | 1         | 3.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 13        | 50%     |
| Unknown | 10        | 38.46%  |
| 4       | 3         | 11.54%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 22        | 84.62%  |
| Unknown | 4         | 15.38%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 12        | 46.15%  |
| Unknown | 10        | 38.46%  |
| 1       | 4         | 15.38%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 6         | 23.08%  |
| IvyBridge   | 4         | 15.38%  |
| Skylake     | 2         | 7.69%   |
| P6          | 2         | 7.69%   |
| KabyLake    | 2         | 7.69%   |
| Core        | 2         | 7.69%   |
| Westmere    | 1         | 3.85%   |
| TigerLake   | 1         | 3.85%   |
| SandyBridge | 1         | 3.85%   |
| Piledriver  | 1         | 3.85%   |
| K10         | 1         | 3.85%   |
| Haswell     | 1         | 3.85%   |
| Geode       | 1         | 3.85%   |
| Broadwell   | 1         | 3.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 19        | 73.08%  |
| Nvidia               | 3         | 11.54%  |
| AMD                  | 2         | 7.69%   |
| VIA Technologies     | 1         | 3.85%   |
| Trident Microsystems | 1         | 3.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 14.29%  |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 7.14%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 7.14%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 7.14%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 7.14%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]             | 1         | 3.57%   |
| Trident Microsystems TGUI 9660/938x/968x                                      | 1         | 3.57%   |
| Nvidia GT218M [NVS 3100M]                                                     | 1         | 3.57%   |
| Nvidia GT216GLM [Quadro FX 880M]                                              | 1         | 3.57%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 3.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 3.57%   |
| Intel JasperLake [UHD Graphics]                                               | 1         | 3.57%   |
| Intel HD Graphics 620                                                         | 1         | 3.57%   |
| Intel HD Graphics 5500                                                        | 1         | 3.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 3.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 3.57%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 3.57%   |
| Intel Apollo Lake [HD Graphics 505]                                           | 1         | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 1         | 3.57%   |
| AMD Richland [Radeon HD 8610G]                                                | 1         | 3.57%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                  | 1         | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 15        | 60%     |
| 2 x Intel                | 3         | 12%     |
| 1 x Nvidia               | 2         | 8%      |
| 1 x AMD                  | 2         | 8%      |
| 1 x VIA                  | 1         | 4%      |
| 1 x Trident Microsystems | 1         | 4%      |
| Intel + Nvidia           | 1         | 4%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 21        | 84%     |
| Unknown | 4         | 16%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 40%     |
| 1.01-2.0   | 6         | 24%     |
| 0.01-0.5   | 6         | 24%     |
| 0.51-1.0   | 2         | 8%      |
| 3.01-4.0   | 1         | 4%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 5         | 35.71%  |
| Samsung Electronics     | 2         | 14.29%  |
| Chimei Innolux          | 2         | 14.29%  |
| LG Philips              | 1         | 7.14%   |
| Lenovo                  | 1         | 7.14%   |
| Chi Mei Optoelectronics | 1         | 7.14%   |
| BOE                     | 1         | 7.14%   |
| Apple                   | 1         | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch    | 1         | 7.14%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch    | 1         | 7.14%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch             | 1         | 7.14%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch             | 1         | 7.14%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch            | 1         | 7.14%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch             | 1         | 7.14%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch             | 1         | 7.14%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch             | 1         | 7.14%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                 | 1         | 7.14%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch         | 1         | 7.14%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch         | 1         | 7.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 220x120mm 9.9-inch | 1         | 7.14%   |
| BOE LCD Monitor BOE0827 1366x768 310x170mm 13.9-inch                    | 1         | 7.14%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                  | 1         | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 7         | 50%     |
| 1600x900 (HD+)  | 3         | 21.43%  |
| 1280x800 (WXGA) | 2         | 14.29%  |
| 1920x1080 (FHD) | 1         | 7.14%   |
| 1024x600        | 1         | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 7         | 50%     |
| 15     | 5         | 35.71%  |
| 12     | 1         | 7.14%   |
| 9      | 1         | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 78.57%  |
| 201-300     | 3         | 21.43%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 12        | 85.71%  |
| 16/10 | 2         | 14.29%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 7         | 50%     |
| 101-110        | 3         | 21.43%  |
| 91-100         | 2         | 14.29%  |
| 61-70          | 1         | 7.14%   |
| 41-50          | 1         | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 8         | 57.14%  |
| 121-160 | 4         | 28.57%  |
| 51-100  | 2         | 14.29%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 19        | 76%     |
| 0     | 6         | 24%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 16        | 39.02%  |
| Realtek Semiconductor             | 8         | 19.51%  |
| Qualcomm Atheros                  | 7         | 17.07%  |
| Marvell Technology Group          | 2         | 4.88%   |
| Broadcom                          | 2         | 4.88%   |
| VIA Technologies                  | 1         | 2.44%   |
| TP-Link                           | 1         | 2.44%   |
| Qualcomm Atheros Communications   | 1         | 2.44%   |
| Huawei Technologies               | 1         | 2.44%   |
| Ericsson Business Mobile Networks | 1         | 2.44%   |
| D-Link                            | 1         | 2.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 5         | 9.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3         | 5.56%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 3.7%    |
| Intel Wireless 8260                                                                   | 2         | 3.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 3.7%    |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 1.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 1.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 1.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1         | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 1.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 1.85%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 1.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.85%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.85%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 1.85%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                  | 1         | 1.85%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 1.85%   |
| Intel Wireless 7265                                                                   | 1         | 1.85%   |
| Intel Wireless 7260                                                                   | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.85%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.85%   |
| Intel PRO/100 VE Network Connection                                                   | 1         | 1.85%   |
| Intel Ethernet Connection I219-V                                                      | 1         | 1.85%   |
| Intel Ethernet Connection I219-LM                                                     | 1         | 1.85%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 1         | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 1.85%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 1.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 1.85%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 1.85%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller                     | 1         | 1.85%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                                    | 1         | 1.85%   |
| Intel 82577LM Gigabit Network Connection                                              | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 55.56%  |
| Qualcomm Atheros                | 6         | 22.22%  |
| Realtek Semiconductor           | 2         | 7.41%   |
| TP-Link                         | 1         | 3.7%    |
| Qualcomm Atheros Communications | 1         | 3.7%    |
| D-Link                          | 1         | 3.7%    |
| Broadcom                        | 1         | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 7.14%   |
| Intel Wireless 8260                                                                   | 2         | 7.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 7.14%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 3.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 3.57%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 3.57%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 3.57%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 3.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 3.57%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 3.57%   |
| Intel Wireless 8265 / 8275                                                            | 1         | 3.57%   |
| Intel Wireless 7265                                                                   | 1         | 3.57%   |
| Intel Wireless 7260                                                                   | 1         | 3.57%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 3.57%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 3.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 3.57%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 3.57%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 3.57%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 3.57%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 3.57%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 10        | 43.48%  |
| Realtek Semiconductor    | 7         | 30.43%  |
| Marvell Technology Group | 2         | 8.7%    |
| VIA Technologies         | 1         | 4.35%   |
| Qualcomm Atheros         | 1         | 4.35%   |
| Huawei Technologies      | 1         | 4.35%   |
| Broadcom                 | 1         | 4.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 5         | 21.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 13.04%  |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 4.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 4.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 4.35%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 4.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 4.35%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 4.35%   |
| Intel Ethernet Connection I219-V                                       | 1         | 4.35%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 4.35%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 4.35%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 4.35%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                     | 1         | 4.35%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 4.35%   |
| Huawei USB Device                                                      | 1         | 4.35%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 4.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 23        | 47.92%  |
| Ethernet | 22        | 45.83%  |
| Modem    | 2         | 4.17%   |
| Unknown  | 1         | 2.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 18        | 52.94%  |
| Ethernet | 15        | 44.12%  |
| Unknown  | 1         | 2.94%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 22        | 88%     |
| 0     | 2         | 8%      |
| 1     | 1         | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 19        | 76%     |
| Yes  | 6         | 24%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 10        | 66.67%  |
| Broadcom                | 2         | 13.33%  |
| IMC Networks            | 1         | 6.67%   |
| Cambridge Silicon Radio | 1         | 6.67%   |
| Apple                   | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 33.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 13.33%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 13.33%  |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 6.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 6.67%   |
| Intel AX201 Bluetooth                               | 1         | 6.67%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.67%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 21        | 80.77%  |
| Nvidia           | 2         | 7.69%   |
| AMD              | 2         | 7.69%   |
| VIA Technologies | 1         | 3.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 13.33%  |
| Intel Sunrise Point-LP HD Audio                                            | 3         | 10%     |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 10%     |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 6.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 6.67%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 3.33%   |
| Nvidia High Definition Audio Controller                                    | 1         | 3.33%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 3.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 3.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 3.33%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 3.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 3.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 3.33%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 3.33%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 3.33%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 3.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 3.33%   |
| AMD FCH Azalia Controller                                                  | 1         | 3.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 21.43%  |
| Unknown             | 5         | 17.86%  |
| Samsung Electronics | 5         | 17.86%  |
| Ramaxel Technology  | 2         | 7.14%   |
| Micron Technology   | 2         | 7.14%   |
| Kingston            | 2         | 7.14%   |
| SHARETRONIC         | 1         | 3.57%   |
| Nanya Technology    | 1         | 3.57%   |
| G.Skill             | 1         | 3.57%   |
| A-DATA Technology   | 1         | 3.57%   |
| 48spaces            | 1         | 3.57%   |
| Unknown             | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 7.14%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s                              | 1         | 3.57%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                              | 1         | 3.57%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 3.57%   |
| Unknown RAM Module 256MB SODIMM DDR                                       | 1         | 3.57%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s                            | 1         | 3.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 3.57%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                    | 1         | 3.57%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 3.57%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 3.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 3.57%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 3.57%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s                        | 1         | 3.57%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 3.57%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                     | 1         | 3.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.57%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 3.57%   |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s                  | 1         | 3.57%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                      | 1         | 3.57%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s                     | 1         | 3.57%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s                    | 1         | 3.57%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s                   | 1         | 3.57%   |
| Kingston RAM 9905428-026.A02LF 2048MB SODIMM DDR3 1066MT/s                | 1         | 3.57%   |
| G.Skill RAM F4-3200C22-8GRS 8GB SODIMM DDR4 3200MT/s                      | 1         | 3.57%   |
| A-DATA RAM AM1L16BC4R1-B1PS 4GB SODIMM DDR3 1600MT/s                      | 1         | 3.57%   |
| 48spaces RAM 012345678901234567890123456789012345 1GB SODIMM DDR2 800MT/s | 1         | 3.57%   |
| Unknown                                                                   | 1         | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 11        | 52.38%  |
| DDR4   | 4         | 19.05%  |
| DDR2   | 2         | 9.52%   |
| SDRAM  | 1         | 4.76%   |
| LPDDR3 | 1         | 4.76%   |
| DRAM   | 1         | 4.76%   |
| DDR    | 1         | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 19        | 90.48%  |
| Row Of Chips | 1         | 4.76%   |
| Chip         | 1         | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 8192 | 6         | 27.27%  |
| 4096 | 6         | 27.27%  |
| 2048 | 6         | 27.27%  |
| 512  | 2         | 9.09%   |
| 1024 | 1         | 4.55%   |
| 256  | 1         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 5         | 20.83%  |
| 2133    | 3         | 12.5%   |
| 1867    | 2         | 8.33%   |
| 1334    | 2         | 8.33%   |
| 1067    | 2         | 8.33%   |
| Unknown | 2         | 8.33%   |
| 3200    | 1         | 4.17%   |
| 2667    | 1         | 4.17%   |
| 1333    | 1         | 4.17%   |
| 1066    | 1         | 4.17%   |
| 800     | 1         | 4.17%   |
| 533     | 1         | 4.17%   |
| 266     | 1         | 4.17%   |
| 166     | 1         | 4.17%   |

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
| Chicony Electronics           | 7         | 41.18%  |
| Realtek Semiconductor         | 2         | 11.76%  |
| Z-Star Microelectronics       | 1         | 5.88%   |
| Syntek                        | 1         | 5.88%   |
| Sunplus Innovation Technology | 1         | 5.88%   |
| Quanta                        | 1         | 5.88%   |
| Microdia                      | 1         | 5.88%   |
| Lenovo                        | 1         | 5.88%   |
| Bison Electronics             | 1         | 5.88%   |
| ALi                           | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 4         | 22.22%  |
| Z-Star Webcam                        | 1         | 5.56%   |
| Syntek Lenovo EasyCamera             | 1         | 5.56%   |
| Sunplus Integrated Camera            | 1         | 5.56%   |
| Realtek USB Camera                   | 1         | 5.56%   |
| Realtek Acer 640 x 480 laptop camera | 1         | 5.56%   |
| Quanta VGA WebCam                    | 1         | 5.56%   |
| Microdia Integrated_Webcam_HD        | 1         | 5.56%   |
| Lenovo Integrated Webcam [R5U877]    | 1         | 5.56%   |
| Chicony Thinkpad T430 camera         | 1         | 5.56%   |
| Chicony Front Camera                 | 1         | 5.56%   |
| Chicony 8M Camera                    | 1         | 5.56%   |
| Chicony 720p HD Camera               | 1         | 5.56%   |
| Bison Integrated Camera              | 1         | 5.56%   |
| ALi Gateway Webcam                   | 1         | 5.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 1         | 50%     |
| Upek             | 1         | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                        | 1         | 50%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 50%     |

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
| 1     | 9         | 36%     |
| 2     | 7         | 28%     |
| 0     | 4         | 16%     |
| 4     | 2         | 8%      |
| 3     | 2         | 8%      |
| 5     | 1         | 4%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 16        | 47.06%  |
| Net/wireless             | 6         | 17.65%  |
| Graphics card            | 5         | 14.71%  |
| Card reader              | 4         | 11.76%  |
| Storage                  | 1         | 2.94%   |
| Sound                    | 1         | 2.94%   |
| Modem                    | 1         | 2.94%   |

