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

Total: 45

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Apple         | MacBookPro8,1               | [23e113910f](https://bsd-hardware.info/?probe=23e113910f) | May 05, 2024 |
| Apple         | MacBookPro8,1               | [55560acf02](https://bsd-hardware.info/?probe=55560acf02) | May 05, 2024 |
| Timi          | TM1612                      | [c139dfdf05](https://bsd-hardware.info/?probe=c139dfdf05) | Apr 13, 2024 |
| Apple         | MacBookAir7,2               | [a818576415](https://bsd-hardware.info/?probe=a818576415) | Apr 13, 2024 |
| Apple         | MacBookAir7,2               | [d8288ba73a](https://bsd-hardware.info/?probe=d8288ba73a) | Apr 09, 2024 |
| Lenovo        | ThinkPad X260 20F60097US    | [5fa2016fc1](https://bsd-hardware.info/?probe=5fa2016fc1) | Mar 11, 2024 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | [0dc4820d7e](https://bsd-hardware.info/?probe=0dc4820d7e) | Mar 05, 2024 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | [c3f8fdaebb](https://bsd-hardware.info/?probe=c3f8fdaebb) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [6c6fcc3427](https://bsd-hardware.info/?probe=6c6fcc3427) | Mar 04, 2024 |
| Lenovo        | ThinkPad T480s 20L8S45W0... | [b35f962bce](https://bsd-hardware.info/?probe=b35f962bce) | Mar 01, 2024 |
| Dell          | Precision 7520              | [bd40dd5305](https://bsd-hardware.info/?probe=bd40dd5305) | Feb 19, 2024 |
| Intel         | Jasper Lake Client Platf... | [6a041adf7a](https://bsd-hardware.info/?probe=6a041adf7a) | Feb 19, 2024 |
| Lenovo        | ThinkPad T410 2518A37       | [b2515cf7fb](https://bsd-hardware.info/?probe=b2515cf7fb) | Feb 19, 2024 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [05ecc99fe8](https://bsd-hardware.info/?probe=05ecc99fe8) | Feb 13, 2024 |
| Samsung       | N150/N210/N220              | [92c052e0d7](https://bsd-hardware.info/?probe=92c052e0d7) | Jan 14, 2024 |
| Google        | Kohaku                      | [94c3c0f6b7](https://bsd-hardware.info/?probe=94c3c0f6b7) | Nov 26, 2023 |
| Google        | Kohaku                      | [198b445c4e](https://bsd-hardware.info/?probe=198b445c4e) | Nov 26, 2023 |
| Dell          | Vostro 3500                 | [875b045b38](https://bsd-hardware.info/?probe=875b045b38) | Oct 29, 2023 |
| Apple         | MacBookAir7,2               | [29fc7f6f45](https://bsd-hardware.info/?probe=29fc7f6f45) | Aug 19, 2023 |
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
| NetBSD 9.3        | 6         | 16.67%  |
| NetBSD 9.2        | 5         | 13.89%  |
| NetBSD 9.1        | 4         | 11.11%  |
| NetBSD 9.0        | 3         | 8.33%   |
| NetBSD 10.0       | 3         | 8.33%   |
| NetBSD 10.0_RC5   | 2         | 5.56%   |
| NetBSD 10.0_RC4   | 2         | 5.56%   |
| NetBSD 10.0_RC3   | 2         | 5.56%   |
| NetBSD 9.99.94    | 1         | 2.78%   |
| NetBSD 9.2_STABLE | 1         | 2.78%   |
| NetBSD 9.0_STABLE | 1         | 2.78%   |
| NetBSD 8.99.51    | 1         | 2.78%   |
| NetBSD 7.2        | 1         | 2.78%   |
| NetBSD 10.99.10   | 1         | 2.78%   |
| NetBSD 10.99.1    | 1         | 2.78%   |
| NetBSD 10.0_RC2   | 1         | 2.78%   |
| NetBSD 10.0_BETA  | 1         | 2.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| NetBSD | 35        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 29        | 82.86%  |
| i386  | 6         | 17.14%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| XFCE         | 10        | 27.78%  |
| Console      | 9         | 25%     |
| MATE         | 3         | 8.33%   |
| ctwm         | 3         | 8.33%   |
| LXQt         | 2         | 5.56%   |
| iwm          | 2         | 5.56%   |
| Fluxbox      | 2         | 5.56%   |
| DWM          | 2         | 5.56%   |
| sdorfehs     | 1         | 2.78%   |
| helloDesktop | 1         | 2.78%   |
| Awesome      | 1         | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 31        | 88.57%  |
| Console | 4         | 11.43%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 26        | 74.29%  |
| SLiM    | 6         | 17.14%  |
| XDM     | 2         | 5.71%   |
| GDM     | 1         | 2.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 25        | 71.43%  |
| en_US   | 7         | 20%     |
| ru_RU   | 1         | 2.86%   |
| fr_FR   | 1         | 2.86%   |
| es_MX   | 1         | 2.86%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 35        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Ufs    | 34        | 97.14%  |
| Cd9660 | 1         | 2.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 22        | 62.86%  |
| Unknown | 13        | 37.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 13        | 37.14%  |
| Apple               | 4         | 11.43%  |
| Dell                | 3         | 8.57%   |
| ASUSTek Computer    | 2         | 5.71%   |
| Acer                | 2         | 5.71%   |
| Toshiba             | 1         | 2.86%   |
| Timi                | 1         | 2.86%   |
| Sony                | 1         | 2.86%   |
| Samsung Electronics | 1         | 2.86%   |
| MiTAC               | 1         | 2.86%   |
| Intel               | 1         | 2.86%   |
| IBM                 | 1         | 2.86%   |
| Hewlett-Packard     | 1         | 2.86%   |
| Google              | 1         | 2.86%   |
| Fujitsu Siemens     | 1         | 2.86%   |
| eMachines           | 1         | 2.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Apple MacBookAir7,2               | 2         | 5.71%   |
| Toshiba Satellite A100            | 1         | 2.86%   |
| Timi TM1612                       | 1         | 2.86%   |
| Sony SVF1421DSGW                  | 1         | 2.86%   |
| Samsung N150/N210/N220            | 1         | 2.86%   |
| MiTAC 5033                        | 1         | 2.86%   |
| Lenovo ThinkPad X260 20F60097US   | 1         | 2.86%   |
| Lenovo ThinkPad X240 20AMS0J01N   | 1         | 2.86%   |
| Lenovo ThinkPad T510 4313CTO      | 1         | 2.86%   |
| Lenovo ThinkPad T490 20N3S4PX02   | 1         | 2.86%   |
| Lenovo ThinkPad T480s 20L8S45W00  | 1         | 2.86%   |
| Lenovo ThinkPad T470 20HES0EV0A   | 1         | 2.86%   |
| Lenovo ThinkPad T460s 20FAS3L002  | 1         | 2.86%   |
| Lenovo ThinkPad T430s 23564H3     | 1         | 2.86%   |
| Lenovo ThinkPad T430 2347A45      | 1         | 2.86%   |
| Lenovo ThinkPad T420 4236D26      | 1         | 2.86%   |
| Lenovo ThinkPad T410 2518A37      | 1         | 2.86%   |
| Lenovo ThinkPad 13 20GJCTO1WW     | 1         | 2.86%   |
| Lenovo G500 20236                 | 1         | 2.86%   |
| Intel Jasper Lake Client Platform | 1         | 2.86%   |
| IBM ThinkPad R51 2887AVG          | 1         | 2.86%   |
| HP Pavilion 17                    | 1         | 2.86%   |
| Google Kohaku                     | 1         | 2.86%   |
| Fujitsu Siemens AMILO L7310       | 1         | 2.86%   |
| eMachines eME642G                 | 1         | 2.86%   |
| Dell Vostro 3500                  | 1         | 2.86%   |
| Dell Precision M4500              | 1         | 2.86%   |
| Dell Precision 7520               | 1         | 2.86%   |
| ASUS X555LJ                       | 1         | 2.86%   |
| ASUS A3L                          | 1         | 2.86%   |
| Apple MacBookPro8,1               | 1         | 2.86%   |
| Apple MacBook2,1                  | 1         | 2.86%   |
| Acer Aspire ES1-132               | 1         | 2.86%   |
| Acer Aspire A114-33               | 1         | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 12        | 34.29%  |
| Dell Precision        | 2         | 5.71%   |
| Apple MacBookAir7     | 2         | 5.71%   |
| Acer Aspire           | 2         | 5.71%   |
| Toshiba Satellite     | 1         | 2.86%   |
| Timi TM1612           | 1         | 2.86%   |
| Sony SVF1421DSGW      | 1         | 2.86%   |
| Samsung N150          | 1         | 2.86%   |
| MiTAC 5033            | 1         | 2.86%   |
| Lenovo G500           | 1         | 2.86%   |
| Intel Jasper          | 1         | 2.86%   |
| IBM ThinkPad          | 1         | 2.86%   |
| HP Pavilion           | 1         | 2.86%   |
| Google Kohaku         | 1         | 2.86%   |
| Fujitsu Siemens AMILO | 1         | 2.86%   |
| eMachines eME642G     | 1         | 2.86%   |
| Dell Vostro           | 1         | 2.86%   |
| ASUS X555LJ           | 1         | 2.86%   |
| ASUS A3L              | 1         | 2.86%   |
| Apple MacBookPro8     | 1         | 2.86%   |
| Apple MacBook2        | 1         | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 5         | 14.29%  |
| 2016    | 4         | 11.43%  |
| 2010    | 4         | 11.43%  |
| 2022    | 3         | 8.57%   |
| 2018    | 3         | 8.57%   |
| 2005    | 3         | 8.57%   |
| 2021    | 2         | 5.71%   |
| 2019    | 2         | 5.71%   |
| 2011    | 2         | 5.71%   |
| 2007    | 2         | 5.71%   |
| 2023    | 1         | 2.86%   |
| 2020    | 1         | 2.86%   |
| 2017    | 1         | 2.86%   |
| 2014    | 1         | 2.86%   |
| Unknown | 1         | 2.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 35        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 94.29%  |
| Yes  | 2         | 5.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 12        | 34.29%  |
| 3.01-4.0    | 7         | 20%     |
| 8.01-16.0   | 5         | 14.29%  |
| 16.01-24.0  | 4         | 11.43%  |
| 0.51-1.0    | 3         | 8.57%   |
| 64.01-256.0 | 1         | 2.86%   |
| 1.01-2.0    | 1         | 2.86%   |
| 0.01-0.5    | 1         | 2.86%   |
| 0           | 1         | 2.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 35        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 0      | 18        | 51.43%  |
| 1      | 17        | 48.57%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 32        | 91.43%  |
| Yes       | 3         | 8.57%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 85.71%  |
| No        | 5         | 14.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 33        | 94.29%  |
| No        | 2         | 5.71%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 65.71%  |
| No        | 12        | 34.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 6         | 17.14%  |
| France       | 5         | 14.29%  |
| Italy        | 4         | 11.43%  |
| Russia       | 3         | 8.57%   |
| Vietnam      | 2         | 5.71%   |
| Saudi Arabia | 2         | 5.71%   |
| India        | 2         | 5.71%   |
| Hungary      | 2         | 5.71%   |
| Germany      | 2         | 5.71%   |
| Taiwan       | 1         | 2.86%   |
| Spain        | 1         | 2.86%   |
| Mexico       | 1         | 2.86%   |
| Finland      | 1         | 2.86%   |
| Denmark      | 1         | 2.86%   |
| China        | 1         | 2.86%   |
| Canada       | 1         | 2.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Rome             | 4         | 11.11%  |
| Noyon            | 3         | 8.33%   |
| Riyadh           | 2         | 5.56%   |
| Moscow           | 2         | 5.56%   |
| Ho Chi Minh City | 2         | 5.56%   |
| Gardony          | 2         | 5.56%   |
| Washington       | 1         | 2.78%   |
| Turenki          | 1         | 2.78%   |
| Taipei           | 1         | 2.78%   |
| Surrey           | 1         | 2.78%   |
| Sun Prairie      | 1         | 2.78%   |
| Ozersk           | 1         | 2.78%   |
| New York         | 1         | 2.78%   |
| Ladbergen        | 1         | 2.78%   |
| Kalispell        | 1         | 2.78%   |
| Genzano di Roma  | 1         | 2.78%   |
| Frederiksberg    | 1         | 2.78%   |
| Córdoba         | 1         | 2.78%   |
| Chennai          | 1         | 2.78%   |
| Chengdu          | 1         | 2.78%   |
| Chandler         | 1         | 2.78%   |
| Carry-le-Rouet   | 1         | 2.78%   |
| Bridgton         | 1         | 2.78%   |
| Berlin           | 1         | 2.78%   |
| Amiens           | 1         | 2.78%   |
| Ahmedabad        | 1         | 2.78%   |
| A Coruña        | 1         | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 20%     |
| Intel               | 3         | 3      | 20%     |
| Hitachi             | 3         | 4      | 20%     |
| Kingston            | 2         | 2      | 13.33%  |
| HGST                | 2         | 2      | 13.33%  |
| WDC                 | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD1600BEVT-00A23T0 160GB        | 1         | 6.67%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 6.67%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 6.67%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 6.67%   |
| Samsung HM080HC 80GB                | 1         | 6.67%   |
| Kingston SA400S37240G 240GB         | 1         | 6.67%   |
| Kingston SA400S37120G 120GB         | 1         | 6.67%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 6.67%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 6.67%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 6.67%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 6.67%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 6.67%   |
| Hitachi HTS545025B9A300 250GB       | 1         | 6.67%   |
| HGST HTS545050A7E680 500GB          | 1         | 6.67%   |
| HGST HTS541010A9E680 1TB            | 1         | 6.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 30%     |
| Hitachi             | 3         | 4      | 30%     |
| HGST                | 2         | 2      | 20%     |
| WDC                 | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |

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
| HDD  | 10        | 11     | 66.67%  |
| SSD  | 5         | 5      | 33.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 15        | 16     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 13        | 14     | 86.67%  |
| 0.51-1.0   | 2         | 2      | 13.33%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 16        | 45.71%  |
| 251-500    | 7         | 20%     |
| 501-1000   | 5         | 14.29%  |
| 51-100     | 3         | 8.57%   |
| 1-20       | 2         | 5.71%   |
| 21-50      | 1         | 2.86%   |
| 1001-2000  | 1         | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 25        | 69.44%  |
| 21-50    | 7         | 19.44%  |
| 51-100   | 2         | 5.56%   |
| 101-250  | 1         | 2.78%   |
| 501-1000 | 1         | 2.78%   |

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
| Malfunc  | 8         | 9      | 53.33%  |
| Works    | 6         | 6      | 40%     |
| Detected | 1         | 1      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 30        | 78.95%  |
| Samsung Electronics            | 2         | 5.26%   |
| AMD                            | 2         | 5.26%   |
| VIA Technologies               | 1         | 2.63%   |
| Solid State Storage Technology | 1         | 2.63%   |
| Micron/Crucial Technology      | 1         | 2.63%   |
| Kingston Technology Company    | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 6         | 14.63%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 4         | 9.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 3         | 7.32%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                    | 2         | 4.88%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                              | 2         | 4.88%   |
| Intel Jasper Lake SATA AHCI Controller                                        | 2         | 4.88%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                        | 2         | 4.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 2         | 4.88%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1         | 2.44%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                | 1         | 2.44%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 2.44%   |
| Kingston Company OM3PDP3 NVMe SSD                                             | 1         | 2.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 1         | 2.44%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 2.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 2.44%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 2.44%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 2.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 2.44%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                 | 1         | 2.44%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                | 1         | 2.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                     | 1         | 2.44%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                 | 1         | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 1         | 2.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                             | 1         | 2.44%   |
| AMD FCH SATA Controller [AHCI mode]                                           | 1         | 2.44%   |
| AMD FCH IDE Controller                                                        | 1         | 2.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 29        | 70.73%  |
| IDE  | 7         | 17.07%  |
| NVMe | 5         | 12.2%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 31        | 88.57%  |
| AMD          | 3         | 8.57%   |
| 123456789ABC | 1         | 2.86%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel 686-class                           | 4         | 11.11%  |
| Intel Pentium M processor 1.60GHz         | 1         | 2.78%   |
| Intel Pentium M processor                 | 1         | 2.78%   |
| Intel Pentium CPU 2020M @ 2.40GHz         | 1         | 2.78%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz          | 1         | 2.78%   |
| Intel Core i7-7920HQ CPU @ 3.10GHz        | 1         | 2.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz         | 1         | 2.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz         | 1         | 2.78%   |
| Intel Core i7-3520M CPU @ 2.90GHz         | 1         | 2.78%   |
| Intel Core i7-2640M CPU @ 2.80GHz         | 1         | 2.78%   |
| Intel Core i5-8365U CPU @ 1.60GHz         | 1         | 2.78%   |
| Intel Core i5-8350U CPU @ 1.70GHz         | 1         | 2.78%   |
| Intel Core i5-7300U CPU @ 2.60GHz         | 1         | 2.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz         | 1         | 2.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz         | 1         | 2.78%   |
| Intel Core i5-5350U CPU @ 1.80GHz         | 1         | 2.78%   |
| Intel Core i5-4300U CPU @ 1.90GHz         | 1         | 2.78%   |
| Intel Core i5-3320M CPU @ 2.60GHz         | 1         | 2.78%   |
| Intel Core i5-2435M CPU @ 2.40GHz         | 1         | 2.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz        | 1         | 2.78%   |
| Intel Core i5 CPU M 560 @ 2.67GH          | 1         | 2.78%   |
| Intel Core i5 CPU M 540 @ 2.53GHz         | 1         | 2.78%   |
| Intel Core i5 CPU M 520 @ 2.40GHz         | 1         | 2.78%   |
| Intel Core i3-3217U CPU @ 1.80GHz         | 1         | 2.78%   |
| Intel Core 2 CPU T7200 @ 2.00GHz          | 1         | 2.78%   |
| Intel Core 2 CPU T7                       | 1         | 2.78%   |
| Intel Celeron N5100 @ 1.10GHz             | 1         | 2.78%   |
| Intel Atom CPU N450 @ 1.66GHz             | 1         | 2.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz   | 1         | 2.78%   |
| AMD Tillamook                             | 1         | 2.78%   |
| AMD Athlon II P340 Dual-Core Processor    | 1         | 2.78%   |
| AMD A10-5745M APU with Radeon HD Graphics | 1         | 2.78%   |
| 123456789ABC Pentium 4                    | 1         | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Notebooks | Percent |
|-----------------|-----------|---------|
| Intel Core i5   | 13        | 36.11%  |
| Intel Core i7   | 5         | 13.89%  |
| Intel 686-class | 4         | 11.11%  |
| Other           | 3         | 8.33%   |
| Intel Pentium M | 2         | 5.56%   |
| Intel Core 2    | 2         | 5.56%   |
| Intel Pentium   | 1         | 2.78%   |
| Intel Core m3   | 1         | 2.78%   |
| Intel Core i3   | 1         | 2.78%   |
| Intel Celeron   | 1         | 2.78%   |
| Intel Atom      | 1         | 2.78%   |
| AMD Athlon II   | 1         | 2.78%   |
| AMD A10         | 1         | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 18        | 50%     |
| Unknown | 11        | 30.56%  |
| 4       | 7         | 19.44%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 31        | 86.11%  |
| Unknown | 5         | 13.89%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 20        | 55.56%  |
| Unknown | 11        | 30.56%  |
| 1       | 5         | 13.89%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 9         | 25%     |
| KabyLake    | 5         | 13.89%  |
| Skylake     | 4         | 11.11%  |
| IvyBridge   | 4         | 11.11%  |
| SandyBridge | 2         | 5.56%   |
| P6          | 2         | 5.56%   |
| Core        | 2         | 5.56%   |
| Broadwell   | 2         | 5.56%   |
| Westmere    | 1         | 2.78%   |
| TigerLake   | 1         | 2.78%   |
| Piledriver  | 1         | 2.78%   |
| K10         | 1         | 2.78%   |
| Haswell     | 1         | 2.78%   |
| Geode       | 1         | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 28        | 75.68%  |
| Nvidia               | 5         | 13.51%  |
| AMD                  | 2         | 5.41%   |
| VIA Technologies     | 1         | 2.7%    |
| Trident Microsystems | 1         | 2.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 4         | 10.26%  |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 7.69%   |
| Nvidia GT218M [NVS 3100M]                                                     | 2         | 5.13%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 5.13%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 2         | 5.13%   |
| Intel JasperLake [UHD Graphics]                                               | 2         | 5.13%   |
| Intel HD Graphics 6000                                                        | 2         | 5.13%   |
| Intel 82852/855GM Integrated Graphics Device                                  | 2         | 5.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 2         | 5.13%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]             | 1         | 2.56%   |
| Trident Microsystems TGUI 9660/938x/968x                                      | 1         | 2.56%   |
| Nvidia GT216GLM [Quadro FX 880M]                                              | 1         | 2.56%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                         | 1         | 2.56%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 2.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 1         | 2.56%   |
| Intel UHD Graphics 620                                                        | 1         | 2.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 2.56%   |
| Intel HD Graphics 630                                                         | 1         | 2.56%   |
| Intel HD Graphics 620                                                         | 1         | 2.56%   |
| Intel HD Graphics 5500                                                        | 1         | 2.56%   |
| Intel HD Graphics 515                                                         | 1         | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1         | 2.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 1         | 2.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 1         | 2.56%   |
| Intel Apollo Lake [HD Graphics 505]                                           | 1         | 2.56%   |
| AMD Richland [Radeon HD 8610G]                                                | 1         | 2.56%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                  | 1         | 2.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 23        | 65.71%  |
| 2 x Intel                | 3         | 8.57%   |
| 1 x Nvidia               | 3         | 8.57%   |
| Intel + Nvidia           | 2         | 5.71%   |
| 1 x AMD                  | 2         | 5.71%   |
| 1 x VIA                  | 1         | 2.86%   |
| 1 x Trident Microsystems | 1         | 2.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 30        | 85.71%  |
| Unknown | 5         | 14.29%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 45.71%  |
| 0.01-0.5   | 7         | 20%     |
| 1.01-2.0   | 6         | 17.14%  |
| 3.01-4.0   | 4         | 11.43%  |
| 0.51-1.0   | 2         | 5.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 5         | 26.32%  |
| Samsung Electronics     | 2         | 10.53%  |
| Lenovo                  | 2         | 10.53%  |
| Chimei Innolux          | 2         | 10.53%  |
| BOE                     | 2         | 10.53%  |
| Apple                   | 2         | 10.53%  |
| LG Philips              | 1         | 5.26%   |
| InfoVision              | 1         | 5.26%   |
| Dell                    | 1         | 5.26%   |
| Chi Mei Optoelectronics | 1         | 5.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch    | 1         | 5.26%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch    | 1         | 5.26%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch             | 1         | 5.26%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch             | 1         | 5.26%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch            | 1         | 5.26%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch             | 1         | 5.26%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch             | 1         | 5.26%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch             | 1         | 5.26%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                 | 1         | 5.26%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                 | 1         | 5.26%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch            | 1         | 5.26%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                       | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch         | 1         | 5.26%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch         | 1         | 5.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 220x120mm 9.9-inch | 1         | 5.26%   |
| BOE LCD Monitor BOE0827 1366x768 310x170mm 13.9-inch                    | 1         | 5.26%   |
| BOE LCD Monitor BOE074F 1920x1080 310x170mm 13.9-inch                   | 1         | 5.26%   |
| Apple LCD Monitor APP9CC5 1280x800 290x180mm 13.4-inch                  | 1         | 5.26%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                  | 1         | 5.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 7         | 36.84%  |
| 1920x1080 (FHD)  | 4         | 21.05%  |
| 1600x900 (HD+)   | 3         | 15.79%  |
| 1280x800 (WXGA)  | 3         | 15.79%  |
| 1440x900 (WXGA+) | 1         | 5.26%   |
| 1024x600         | 1         | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 10        | 52.63%  |
| 15     | 5         | 26.32%  |
| 24     | 1         | 5.26%   |
| 14     | 1         | 5.26%   |
| 12     | 1         | 5.26%   |
| 9      | 1         | 5.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 68.42%  |
| 201-300     | 5         | 26.32%  |
| 501-600     | 1         | 5.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 15        | 78.95%  |
| 16/10 | 4         | 21.05%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 57.89%  |
| 101-110        | 3         | 15.79%  |
| 91-100         | 2         | 10.53%  |
| 61-70          | 1         | 5.26%   |
| 41-50          | 1         | 5.26%   |
| 201-250        | 1         | 5.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 9         | 47.37%  |
| 121-160 | 7         | 36.84%  |
| 51-100  | 3         | 15.79%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 27        | 77.14%  |
| 0     | 8         | 22.86%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 22        | 40%     |
| Realtek Semiconductor             | 11        | 20%     |
| Qualcomm Atheros                  | 7         | 12.73%  |
| Broadcom                          | 5         | 9.09%   |
| Marvell Technology Group          | 2         | 3.64%   |
| VIA Technologies                  | 1         | 1.82%   |
| TP-Link                           | 1         | 1.82%   |
| Qualcomm Atheros Communications   | 1         | 1.82%   |
| Huawei Technologies               | 1         | 1.82%   |
| Ericsson Business Mobile Networks | 1         | 1.82%   |
| Dell                              | 1         | 1.82%   |
| D-Link                            | 1         | 1.82%   |
| Apple                             | 1         | 1.82%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                | 6         | 8.11%   |
| Intel Wireless 8260                                                                   | 4         | 5.41%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3         | 4.05%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 2.7%    |
| Intel Ethernet Connection I219-LM                                                     | 2         | 2.7%    |
| Intel Ethernet Connection (4) I219-LM                                                 | 2         | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 2.7%    |
| Intel 82577LM Gigabit Network Connection                                              | 2         | 2.7%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 2         | 2.7%    |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 1.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.35%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 1.35%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.35%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.35%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1         | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 1         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 1.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 1.35%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 1.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.35%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.35%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 1.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                  | 1         | 1.35%   |
| Intel Wireless 7265                                                                   | 1         | 1.35%   |
| Intel Wireless 7260                                                                   | 1         | 1.35%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 1.35%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.35%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.35%   |
| Intel PRO/100 VE Network Connection                                                   | 1         | 1.35%   |
| Intel Ethernet Connection I219-V                                                      | 1         | 1.35%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 1.35%   |
| Intel Ethernet Connection (6) I219-LM                                                 | 1         | 1.35%   |
| Intel Ethernet Connection (5) I219-LM                                                 | 1         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.35%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 52.63%  |
| Qualcomm Atheros                | 6         | 15.79%  |
| Realtek Semiconductor           | 5         | 13.16%  |
| Broadcom                        | 4         | 10.53%  |
| TP-Link                         | 1         | 2.63%   |
| Qualcomm Atheros Communications | 1         | 2.63%   |
| D-Link                          | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                                   | 4         | 10.26%  |
| Intel Wireless 8265 / 8275                                                            | 3         | 7.69%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 5.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 5.13%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 2         | 5.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 2.56%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                                       | 1         | 2.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 2.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.56%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 2.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 2.56%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 2.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 2.56%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.56%   |
| Intel Wireless 7265                                                                   | 1         | 2.56%   |
| Intel Wireless 7260                                                                   | 1         | 2.56%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 2.56%   |
| Intel Wi-Fi 6 AX201                                                                   | 1         | 2.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 2.56%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 2.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 1         | 2.56%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 2.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 1         | 2.56%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 2.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 2.56%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 2.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 15        | 48.39%  |
| Realtek Semiconductor    | 8         | 25.81%  |
| Marvell Technology Group | 2         | 6.45%   |
| Broadcom                 | 2         | 6.45%   |
| VIA Technologies         | 1         | 3.23%   |
| Qualcomm Atheros         | 1         | 3.23%   |
| Huawei Technologies      | 1         | 3.23%   |
| Apple                    | 1         | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 6         | 19.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 9.68%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 6.45%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 6.45%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 6.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 3.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 3.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 3.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 3.23%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 3.23%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 3.23%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 3.23%   |
| Intel Ethernet Connection I219-V                                       | 1         | 3.23%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 3.23%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 3.23%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 3.23%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                     | 1         | 3.23%   |
| Huawei USB Device                                                      | 1         | 3.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 3.23%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 3.23%   |
| Apple Ethernet Adapter [A1277]                                         | 1         | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 32        | 48.48%  |
| Ethernet | 30        | 45.45%  |
| Modem    | 2         | 3.03%   |
| Unknown  | 2         | 3.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 51.16%  |
| Ethernet | 20        | 46.51%  |
| Unknown  | 1         | 2.33%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 28        | 80%     |
| 1     | 5         | 14.29%  |
| 0     | 2         | 5.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 77.14%  |
| Yes  | 8         | 22.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 14        | 58.33%  |
| Apple                   | 4         | 16.67%  |
| Broadcom                | 3         | 12.5%   |
| Realtek Semiconductor   | 1         | 4.17%   |
| IMC Networks            | 1         | 4.17%   |
| Cambridge Silicon Radio | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 8         | 33.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 12.5%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 8.33%   |
| Apple Broadcom Built-in Bluetooth                   | 2         | 8.33%   |
| Realtek Bluetooth Adapter                           | 1         | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.17%   |
| Intel AX201 Bluetooth                               | 1         | 4.17%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 4.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.17%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 4.17%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 4.17%   |
| Apple Bluetooth Host Controller                     | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 31        | 83.78%  |
| Nvidia           | 3         | 8.11%   |
| AMD              | 2         | 5.41%   |
| VIA Technologies | 1         | 2.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 6         | 13.95%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 9.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 6.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 6.98%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 6.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 6.98%   |
| Nvidia High Definition Audio Controller                                    | 2         | 4.65%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 4.65%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 2         | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 4.65%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                  | 1         | 2.33%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 2.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.33%   |
| Intel CM238 HD Audio Controller                                            | 1         | 2.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2.33%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 2.33%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 2.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 2.33%   |
| AMD FCH Azalia Controller                                                  | 1         | 2.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 2.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 25%     |
| SK hynix            | 7         | 17.5%   |
| Unknown             | 5         | 12.5%   |
| Micron Technology   | 4         | 10%     |
| Ramaxel Technology  | 3         | 7.5%    |
| Kingston            | 2         | 5%      |
| Unknown             | 2         | 5%      |
| SHARETRONIC         | 1         | 2.5%    |
| Patriot             | 1         | 2.5%    |
| Nanya Technology    | 1         | 2.5%    |
| G.Skill             | 1         | 2.5%    |
| Crucial             | 1         | 2.5%    |
| A-DATA Technology   | 1         | 2.5%    |
| 48spaces            | 1         | 2.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 4.88%   |
| Unknown                                                                   | 2         | 4.88%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s                              | 1         | 2.44%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                              | 1         | 2.44%   |
| Unknown RAM Module 2GB SODIMM DDR3                                        | 1         | 2.44%   |
| Unknown RAM Module 256MB SODIMM DDR                                       | 1         | 2.44%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s                            | 1         | 2.44%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                             | 1         | 2.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 2.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s                    | 1         | 2.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 2.44%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 2.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 2.44%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 2.44%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s                        | 1         | 2.44%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 2.44%   |
| Samsung RAM Module 2GB SODIMM LPDDR3 1867MT/s                             | 1         | 2.44%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                               | 1         | 2.44%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                     | 1         | 2.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.44%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 1         | 2.44%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 1         | 2.44%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s                    | 1         | 2.44%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 1         | 2.44%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.44%   |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2400MT/s                  | 1         | 2.44%   |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s                  | 1         | 2.44%   |
| Patriot RAM PSD34G13332S 4GB SODIMM DDR3 1334MT/s                         | 1         | 2.44%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                      | 1         | 2.44%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                                | 1         | 2.44%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.44%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                      | 1         | 2.44%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s                    | 1         | 2.44%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s                   | 1         | 2.44%   |
| Kingston RAM 9905428-026.A02LF 2048MB SODIMM DDR3 1066MT/s                | 1         | 2.44%   |
| G.Skill RAM F4-3200C22-8GRS 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.44%   |
| Crucial RAM CT8G4SFS824A.M8FR 8GB SODIMM DDR4 2400MT/s                    | 1         | 2.44%   |
| A-DATA RAM AM1L16BC4R1-B1PS 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.44%   |
| 48spaces RAM 012345678901234567890123456789012345 1GB SODIMM DDR2 800MT/s | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 14        | 46.67%  |
| DDR4   | 9         | 30%     |
| LPDDR3 | 2         | 6.67%   |
| DDR2   | 2         | 6.67%   |
| SDRAM  | 1         | 3.33%   |
| DRAM   | 1         | 3.33%   |
| DDR    | 1         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 93.33%  |
| Row Of Chips | 1         | 3.33%   |
| Chip         | 1         | 3.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 8         | 25%     |
| 4096  | 8         | 25%     |
| 2048  | 8         | 25%     |
| 16384 | 4         | 12.5%   |
| 512   | 2         | 6.25%   |
| 1024  | 1         | 3.13%   |
| 256   | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 6         | 17.65%  |
| 2667    | 4         | 11.76%  |
| 2133    | 4         | 11.76%  |
| 1867    | 3         | 8.82%   |
| 1334    | 3         | 8.82%   |
| 2400    | 2         | 5.88%   |
| 1333    | 2         | 5.88%   |
| 1067    | 2         | 5.88%   |
| Unknown | 2         | 5.88%   |
| 3200    | 1         | 2.94%   |
| 1066    | 1         | 2.94%   |
| 800     | 1         | 2.94%   |
| 533     | 1         | 2.94%   |
| 266     | 1         | 2.94%   |
| 166     | 1         | 2.94%   |

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
| Chicony Electronics           | 9         | 37.5%   |
| Realtek Semiconductor         | 3         | 12.5%   |
| Lenovo                        | 2         | 8.33%   |
| Bison Electronics             | 2         | 8.33%   |
| Z-Star Microelectronics       | 1         | 4.17%   |
| Syntek                        | 1         | 4.17%   |
| Sunplus Innovation Technology | 1         | 4.17%   |
| Quanta                        | 1         | 4.17%   |
| Microdia                      | 1         | 4.17%   |
| Lite-On Technology            | 1         | 4.17%   |
| Apple                         | 1         | 4.17%   |
| ALi                           | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 4         | 16%     |
| Lenovo Integrated Webcam [R5U877]       | 2         | 8%      |
| Z-Star Webcam                           | 1         | 4%      |
| Syntek Lenovo EasyCamera                | 1         | 4%      |
| Sunplus Integrated Camera               | 1         | 4%      |
| Realtek USB Camera                      | 1         | 4%      |
| Realtek USB 2.0 PC Camera               | 1         | 4%      |
| Realtek Acer 640 x 480 laptop camera    | 1         | 4%      |
| Quanta VGA WebCam                       | 1         | 4%      |
| Microdia Integrated_Webcam_HD           | 1         | 4%      |
| Lite-On Integrated Camera               | 1         | 4%      |
| Chicony XiaoMi USB 2.0 Webcam           | 1         | 4%      |
| Chicony Thinkpad T430 camera            | 1         | 4%      |
| Chicony Integrated Camera (1280x720@30) | 1         | 4%      |
| Chicony Front Camera                    | 1         | 4%      |
| Chicony 8M Camera                       | 1         | 4%      |
| Chicony 720p HD Camera                  | 1         | 4%      |
| Bison ThinkPad P50 Integrated Camera    | 1         | 4%      |
| Bison Integrated Camera                 | 1         | 4%      |
| Apple FaceTime HD Camera                | 1         | 4%      |
| ALi Gateway Webcam                      | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 50%     |
| Upek             | 1         | 25%     |
| Synaptics        | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 25%     |
| Validity Sensors Synaptics WBDI                        | 1         | 25%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 25%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 25%     |

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
| 2     | 13        | 37.14%  |
| 1     | 11        | 31.43%  |
| 0     | 4         | 11.43%  |
| 3     | 3         | 8.57%   |
| 5     | 2         | 5.71%   |
| 4     | 2         | 5.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 26        | 50%     |
| Net/wireless             | 12        | 23.08%  |
| Card reader              | 6         | 11.54%  |
| Graphics card            | 5         | 9.62%   |
| Storage                  | 1         | 1.92%   |
| Sound                    | 1         | 1.92%   |
| Modem                    | 1         | 1.92%   |

