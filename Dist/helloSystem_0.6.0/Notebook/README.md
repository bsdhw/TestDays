helloSystem 0.6.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.6.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends&rel=hellosystem-0.6.0

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

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Apple     | MacBookAir5,1               | [b354b2bd4e](https://bsd-hardware.info/?probe=b354b2bd4e) | Oct 31, 2021 |
| HP        | Presario CQ43               | [b97d9ff563](https://bsd-hardware.info/?probe=b97d9ff563) | Oct 30, 2021 |
| Chuwi     | MiniBook                    | [4ce05f93a8](https://bsd-hardware.info/?probe=4ce05f93a8) | Oct 28, 2021 |
| Dell      | Precision M4600             | [2f848fd2c0](https://bsd-hardware.info/?probe=2f848fd2c0) | Oct 27, 2021 |
| Sony      | SVS1511AJB                  | [a366b5fab3](https://bsd-hardware.info/?probe=a366b5fab3) | Oct 24, 2021 |
| Sony      | SVS1511AJB                  | [2333f62192](https://bsd-hardware.info/?probe=2333f62192) | Oct 24, 2021 |
| Lenovo    | ThinkPad X1 Carbon 2nd 2... | [9996e06a3d](https://bsd-hardware.info/?probe=9996e06a3d) | Oct 22, 2021 |
| Dell      | Studio 1747                 | [ed704cde92](https://bsd-hardware.info/?probe=ed704cde92) | Oct 20, 2021 |
| Apple     | MacBookPro4,1               | [10861818b2](https://bsd-hardware.info/?probe=10861818b2) | Oct 20, 2021 |
| HP        | Unknown                     | [ad95186d17](https://bsd-hardware.info/?probe=ad95186d17) | Oct 19, 2021 |
| Dell      | Studio 1747                 | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| HP        | 15                          | [e3f26d7245](https://bsd-hardware.info/?probe=e3f26d7245) | Oct 18, 2021 |
| Lenovo    | Yoga 3 Pro-1370 80HE        | [48169f1d3c](https://bsd-hardware.info/?probe=48169f1d3c) | Oct 16, 2021 |
| Lenovo    | ThinkPad L440 20ASS0FP00    | [d92e6e3c21](https://bsd-hardware.info/?probe=d92e6e3c21) | Oct 11, 2021 |
| Lenovo    | ThinkPad X1 Carbon Gen 9... | [abf8bb08a6](https://bsd-hardware.info/?probe=abf8bb08a6) | Oct 11, 2021 |
| ASUSTek   | U33Jc                       | [07f11b6604](https://bsd-hardware.info/?probe=07f11b6604) | Oct 10, 2021 |
| MSI       | MS-16F1                     | [72b9db306a](https://bsd-hardware.info/?probe=72b9db306a) | Oct 09, 2021 |
| Lenovo    | S20-30 Touch 20434          | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| Lenovo    | ThinkPad X250 20CLS2A11K    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| Acer      | Aspire 5741                 | [fd4e40a8d9](https://bsd-hardware.info/?probe=fd4e40a8d9) | Oct 07, 2021 |
| Lenovo    | ThinkPad R500 2718W92       | [384f10861a](https://bsd-hardware.info/?probe=384f10861a) | Oct 05, 2021 |
| ASUSTek   | UX21A                       | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| Itautec   | Infoway w7530               | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [f02ef8c047](https://bsd-hardware.info/?probe=f02ef8c047) | Oct 04, 2021 |
| Dell      | Latitude E4300              | [fdb3de3036](https://bsd-hardware.info/?probe=fdb3de3036) | Oct 03, 2021 |
| Dell      | Inspiron 3521               | [748b6d14f4](https://bsd-hardware.info/?probe=748b6d14f4) | Oct 02, 2021 |
| Toshiba   | dynabook RX3 SM240E/3HD     | [2fe863dff4](https://bsd-hardware.info/?probe=2fe863dff4) | Oct 01, 2021 |
| Toshiba   | Satellite S55t-B            | [445fe665b8](https://bsd-hardware.info/?probe=445fe665b8) | Oct 01, 2021 |
| HP        | Pavilion dm4                | [bb5a564a50](https://bsd-hardware.info/?probe=bb5a564a50) | Sep 30, 2021 |
| Lenovo    | G500s 20245                 | [88cd1ca7bd](https://bsd-hardware.info/?probe=88cd1ca7bd) | Sep 18, 2021 |
| Kraftway  | KW10T                       | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Dell      | Latitude 3540               | [2583b22e8d](https://bsd-hardware.info/?probe=2583b22e8d) | Aug 29, 2021 |
| Dell      | Latitude 3540               | [de97e0b2fc](https://bsd-hardware.info/?probe=de97e0b2fc) | Aug 29, 2021 |
| Itautec   | Infoway w7530               | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| Toshiba   | Satellite S55t-B            | [5aaacec4ad](https://bsd-hardware.info/?probe=5aaacec4ad) | Aug 23, 2021 |
| Toshiba   | Satellite S55t-B            | [d74035a8e7](https://bsd-hardware.info/?probe=d74035a8e7) | Aug 23, 2021 |
| Lenovo    | ThinkPad X230 23062S2       | [bceadf5c66](https://bsd-hardware.info/?probe=bceadf5c66) | Aug 05, 2021 |
| Lenovo    | ThinkPad SL 2746M3C         | [aa10433581](https://bsd-hardware.info/?probe=aa10433581) | Jul 28, 2021 |
| Lenovo    | ThinkPad X230 2325IG2       | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| eMachines | eM350                       | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| eMachines | eM350                       | [c268dd82de](https://bsd-hardware.info/?probe=c268dd82de) | Jul 04, 2021 |
| Lenovo    | B590 62743PG                | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| Lenovo    | IdeaPad S145-15IWL 81MV     | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| eMachines | eM350                       | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines | eM350                       | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Dell      | Inspiron 3542               | [bb13e61de1](https://bsd-hardware.info/?probe=bb13e61de1) | Jun 21, 2021 |
| Lenovo    | ThinkPad Yoga 11e 20DAS0... | [0e448af5f5](https://bsd-hardware.info/?probe=0e448af5f5) | Jun 18, 2021 |
| Dell      | Latitude 7280               | [8fd335f46f](https://bsd-hardware.info/?probe=8fd335f46f) | Jun 18, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 38        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 37        | 97.37%  |
| XFCE         | 1         | 2.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 38        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 38        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 36        | 94.74%  |
| ru_RU   | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 27        | 71.05%  |
| BIOS | 11        | 28.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 38        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 38        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 14        | 36.84%  |
| Dell             | 7         | 18.42%  |
| Hewlett-Packard  | 4         | 10.53%  |
| Toshiba          | 2         | 5.26%   |
| ASUSTek Computer | 2         | 5.26%   |
| Apple            | 2         | 5.26%   |
| Sony             | 1         | 2.63%   |
| MSI              | 1         | 2.63%   |
| Kraftway         | 1         | 2.63%   |
| Itautec          | 1         | 2.63%   |
| eMachines        | 1         | 2.63%   |
| Chuwi            | 1         | 2.63%   |
| Acer             | 1         | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite S55t-B                   | 1         | 2.63%   |
| Toshiba dynabook RX3 SM240E/3HD            | 1         | 2.63%   |
| Sony SVS1511AJB                            | 1         | 2.63%   |
| MSI MS-16F1                                | 1         | 2.63%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 2.63%   |
| Lenovo ThinkPad Yoga 11e 20DAS0AE00        | 1         | 2.63%   |
| Lenovo ThinkPad X250 20CLS2A11K            | 1         | 2.63%   |
| Lenovo ThinkPad X230 2325IG2               | 1         | 2.63%   |
| Lenovo ThinkPad X230 23062S2               | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD | 1         | 2.63%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A70066UK   | 1         | 2.63%   |
| Lenovo ThinkPad SL 2746M3C                 | 1         | 2.63%   |
| Lenovo ThinkPad R500 2718W92               | 1         | 2.63%   |
| Lenovo ThinkPad L440 20ASS0FP00            | 1         | 2.63%   |
| Lenovo S20-30 Touch 20434                  | 1         | 2.63%   |
| Lenovo IdeaPad S145-15IWL 81MV             | 1         | 2.63%   |
| Lenovo G500s 20245                         | 1         | 2.63%   |
| Lenovo B590 62743PG                        | 1         | 2.63%   |
| Kraftway KW10T                             | 1         | 2.63%   |
| Itautec Infoway w7530                      | 1         | 2.63%   |
| HP Presario CQ43                           | 1         | 2.63%   |
| HP Pavilion dm4                            | 1         | 2.63%   |
| HP 15                                      | 1         | 2.63%   |
| eMachines eM350                            | 1         | 2.63%   |
| Dell Studio 1747                           | 1         | 2.63%   |
| Dell Precision M4600                       | 1         | 2.63%   |
| Dell Latitude E4300                        | 1         | 2.63%   |
| Dell Latitude 7280                         | 1         | 2.63%   |
| Dell Latitude 3540                         | 1         | 2.63%   |
| Dell Inspiron 3542                         | 1         | 2.63%   |
| Dell Inspiron 3521                         | 1         | 2.63%   |
| Chuwi MiniBook                             | 1         | 2.63%   |
| ASUS UX21A                                 | 1         | 2.63%   |
| ASUS U33Jc                                 | 1         | 2.63%   |
| Apple MacBookPro4,1                        | 1         | 2.63%   |
| Apple MacBookAir5,1                        | 1         | 2.63%   |
| Acer Aspire 5741                           | 1         | 2.63%   |
| Unknown                                    | 1         | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 9         | 23.68%  |
| Dell Latitude     | 3         | 7.89%   |
| Dell Inspiron     | 2         | 5.26%   |
| Toshiba Satellite | 1         | 2.63%   |
| Toshiba dynabook  | 1         | 2.63%   |
| Sony SVS1511AJB   | 1         | 2.63%   |
| MSI MS-16F1       | 1         | 2.63%   |
| Lenovo Yoga       | 1         | 2.63%   |
| Lenovo S20-30     | 1         | 2.63%   |
| Lenovo IdeaPad    | 1         | 2.63%   |
| Lenovo G500s      | 1         | 2.63%   |
| Lenovo B590       | 1         | 2.63%   |
| Kraftway KW10T    | 1         | 2.63%   |
| Itautec Infoway   | 1         | 2.63%   |
| HP Presario       | 1         | 2.63%   |
| HP Pavilion       | 1         | 2.63%   |
| HP 15             | 1         | 2.63%   |
| eMachines eM350   | 1         | 2.63%   |
| Dell Studio       | 1         | 2.63%   |
| Dell Precision    | 1         | 2.63%   |
| Chuwi MiniBook    | 1         | 2.63%   |
| ASUS UX21A        | 1         | 2.63%   |
| ASUS U33Jc        | 1         | 2.63%   |
| Apple MacBookPro4 | 1         | 2.63%   |
| Apple MacBookAir5 | 1         | 2.63%   |
| Acer Aspire       | 1         | 2.63%   |
| Unknown           | 1         | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 6         | 15.79%  |
| 2014 | 5         | 13.16%  |
| 2019 | 4         | 10.53%  |
| 2012 | 4         | 10.53%  |
| 2021 | 3         | 7.89%   |
| 2020 | 3         | 7.89%   |
| 2018 | 3         | 7.89%   |
| 2013 | 3         | 7.89%   |
| 2010 | 3         | 7.89%   |
| 2016 | 1         | 2.63%   |
| 2015 | 1         | 2.63%   |
| 2009 | 1         | 2.63%   |
| 2008 | 1         | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 38        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 18        | 47.37%  |
| 8.01-16.0  | 15        | 39.47%  |
| 16.01-24.0 | 4         | 10.53%  |
| 2.01-3.0   | 1         | 2.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 28        | 73.68%  |
| 0.51-1.0 | 10        | 26.32%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 34        | 89.47%  |
| 0      | 2         | 5.26%   |
| 3      | 1         | 2.63%   |
| 2      | 1         | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 20        | 52.63%  |
| Yes       | 18        | 47.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 84.21%  |
| No        | 6         | 15.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 97.37%  |
| No        | 1         | 2.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 21        | 55.26%  |
| No        | 17        | 44.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Russia      | 4         | 10.53%  |
| USA         | 3         | 7.89%   |
| China       | 3         | 7.89%   |
| Brazil      | 3         | 7.89%   |
| Ukraine     | 2         | 5.26%   |
| UK          | 2         | 5.26%   |
| Spain       | 2         | 5.26%   |
| South Korea | 2         | 5.26%   |
| New Zealand | 2         | 5.26%   |
| Mexico      | 2         | 5.26%   |
| Germany     | 2         | 5.26%   |
| Syria       | 1         | 2.63%   |
| Peru        | 1         | 2.63%   |
| Netherlands | 1         | 2.63%   |
| Lithuania   | 1         | 2.63%   |
| Libya       | 1         | 2.63%   |
| Japan       | 1         | 2.63%   |
| Italy       | 1         | 2.63%   |
| Greece      | 1         | 2.63%   |
| Czechia     | 1         | 2.63%   |
| Chile       | 1         | 2.63%   |
| Canada      | 1         | 2.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Guangzhou               | 2         | 5.13%   |
| Barcelona               | 2         | 5.13%   |
| Yeongdong-gun           | 1         | 2.56%   |
| Wellington              | 1         | 2.56%   |
| Ufa                     | 1         | 2.56%   |
| Tyumen                  | 1         | 2.56%   |
| Tripoli                 | 1         | 2.56%   |
| The Hague               | 1         | 2.56%   |
| Taito                   | 1         | 2.56%   |
| St Petersburg           | 1         | 2.56%   |
| Seoul                   | 1         | 2.56%   |
| Seattle                 | 1         | 2.56%   |
| Santiago                | 1         | 2.56%   |
| Rio de Janeiro          | 1         | 2.56%   |
| Redmond                 | 1         | 2.56%   |
| Pilsen                  | 1         | 2.56%   |
| Odessa                  | 1         | 2.56%   |
| Obninsk                 | 1         | 2.56%   |
| Nughedu San Nicolo      | 1         | 2.56%   |
| New Plymouth            | 1         | 2.56%   |
| Monterrey               | 1         | 2.56%   |
| Monte Belo              | 1         | 2.56%   |
| Mission                 | 1         | 2.56%   |
| Lima                    | 1         | 2.56%   |
| La Paz                  | 1         | 2.56%   |
| Kyiv                    | 1         | 2.56%   |
| Kaunas                  | 1         | 2.56%   |
| Ipojuca                 | 1         | 2.56%   |
| Finchley                | 1         | 2.56%   |
| Dulles                  | 1         | 2.56%   |
| Detmold                 | 1         | 2.56%   |
| Damascus                | 1         | 2.56%   |
| Chengdu                 | 1         | 2.56%   |
| Cabo de Santo Agostinho | 1         | 2.56%   |
| Bensheim                | 1         | 2.56%   |
| Athens                  | 1         | 2.56%   |
| Ashton-under-Lyne       | 1         | 2.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 9      | 20.51%  |
| Toshiba             | 4         | 5      | 10.26%  |
| Samsung Electronics | 4         | 4      | 10.26%  |
| WDC                 | 3         | 3      | 7.69%   |
| Kingston            | 2         | 3      | 5.13%   |
| Hitachi             | 2         | 2      | 5.13%   |
| SPCC                | 1         | 1      | 2.56%   |
| SanDisk             | 1         | 1      | 2.56%   |
| PLEXTOR             | 1         | 1      | 2.56%   |
| Patriot             | 1         | 1      | 2.56%   |
| LITEON              | 1         | 1      | 2.56%   |
| Lexar               | 1         | 1      | 2.56%   |
| Leven               | 1         | 1      | 2.56%   |
| Intel               | 1         | 1      | 2.56%   |
| HGST                | 1         | 1      | 2.56%   |
| FORESEE             | 1         | 1      | 2.56%   |
| Crucial             | 1         | 1      | 2.56%   |
| Corsair             | 1         | 1      | 2.56%   |
| Apple               | 1         | 1      | 2.56%   |
| Apacer              | 1         | 1      | 2.56%   |
| AMD                 | 1         | 1      | 2.56%   |
| A-DATA Technology   | 1         | 1      | 2.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB           | 3         | 7.5%    |
| Toshiba MQ01ABF050 500GB            | 2         | 5%      |
| WDC WD5000BEKT-60KA9T0 500GB        | 1         | 2.5%    |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 2.5%    |
| WDC WD2500BEVS-08VAT2 250GB         | 1         | 2.5%    |
| Toshiba MQ01ABD100 1TB              | 1         | 2.5%    |
| Toshiba MK5061GSYN 500GB            | 1         | 2.5%    |
| SPCC Solid State Disk 1TB           | 1         | 2.5%    |
| Seagate ST9160412ASG 160GB          | 1         | 2.5%    |
| Seagate ST500LT012-1DG142 500GB     | 1         | 2.5%    |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 2.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 2.5%    |
| SanDisk SD5SE2256G1002E 256GB       | 1         | 2.5%    |
| Samsung MZVL21T0HCLR-00BL7 1TB      | 1         | 2.5%    |
| Samsung MZNTE256HMHP-000L2 256GB    | 1         | 2.5%    |
| Samsung MZNLN512HMJP-000H1 512GB    | 1         | 2.5%    |
| Samsung MZ7TE128HMGR-000L1 128GB    | 1         | 2.5%    |
| PLEXTOR PX-128M5Pro 128GB           | 1         | 2.5%    |
| Patriot Burst 120GB                 | 1         | 2.5%    |
| LITEON IT LCS-128L9S-HP 128GB       | 1         | 2.5%    |
| Lexar 256GB SSD                     | 1         | 2.5%    |
| Leven JAJS300M480C 480GB            | 1         | 2.5%    |
| Kingston SVP200S37A60G 64GB         | 1         | 2.5%    |
| Kingston SMS200S360G 64GB           | 1         | 2.5%    |
| Kingston SKC300S37A240G 240GB       | 1         | 2.5%    |
| Intel SSDSCKGF180A4L 180GB          | 1         | 2.5%    |
| Hitachi HTS545025B9A300 250GB       | 1         | 2.5%    |
| Hitachi HTS541080G9SA00 80GB        | 1         | 2.5%    |
| HGST HTS541010A9E680 1TB            | 1         | 2.5%    |
| FORESEE 128GB SSD                   | 1         | 2.5%    |
| Crucial CT480BX200SSD1 480GB        | 1         | 2.5%    |
| Corsair Force 3 SSD 120GB           | 1         | 2.5%    |
| Apple SSD TS128E 121GB              | 1         | 2.5%    |
| Apacer AS681 240GB                  | 1         | 2.5%    |
| AMD R5SL120G 120GB                  | 1         | 2.5%    |
| A-DATA SX6000PNP 1TB                | 1         | 2.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 9      | 44.44%  |
| Toshiba | 4         | 5      | 22.22%  |
| WDC     | 3         | 3      | 16.67%  |
| Hitachi | 2         | 2      | 11.11%  |
| HGST    | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 15.79%  |
| Kingston            | 2         | 3      | 10.53%  |
| SPCC                | 1         | 1      | 5.26%   |
| SanDisk             | 1         | 1      | 5.26%   |
| PLEXTOR             | 1         | 1      | 5.26%   |
| Patriot             | 1         | 1      | 5.26%   |
| LITEON              | 1         | 1      | 5.26%   |
| Lexar               | 1         | 1      | 5.26%   |
| Leven               | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| FORESEE             | 1         | 1      | 5.26%   |
| Crucial             | 1         | 1      | 5.26%   |
| Corsair             | 1         | 1      | 5.26%   |
| Apple               | 1         | 1      | 5.26%   |
| Apacer              | 1         | 1      | 5.26%   |
| AMD                 | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 18        | 20     | 48.65%  |
| HDD  | 17        | 20     | 45.95%  |
| NVMe | 2         | 2      | 5.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 35        | 40     | 94.59%  |
| NVMe | 2         | 2      | 5.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 35     | 85.71%  |
| 0.51-1.0   | 4         | 4      | 11.43%  |
| 1.01-2.0   | 1         | 1      | 2.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 20        | 50%     |
| 101-250    | 9         | 22.5%   |
| 251-500    | 7         | 17.5%   |
| 501-1000   | 3         | 7.5%    |
| 51-100     | 1         | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 38        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-80A0RT0 320GB       | 1         | 1      | 12.5%   |
| Toshiba MQ01ABF050 500GB           | 1         | 2      | 12.5%   |
| Toshiba MK5061GSYN 500GB           | 1         | 1      | 12.5%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 12.5%   |
| Seagate ST500LM021-1KJ152 500GB    | 1         | 1      | 12.5%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 12.5%   |
| Hitachi HTS541080G9SA00 80GB       | 1         | 1      | 12.5%   |
| HGST HTS541010A9E680 1TB           | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 37.5%   |
| Toshiba | 2         | 3      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |
| HGST    | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 37.5%   |
| Toshiba | 2         | 3      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |
| HGST    | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 28        | 32     | 75.68%  |
| Malfunc | 8         | 9      | 21.62%  |
| Failed  | 1         | 1      | 2.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 94.87%  |
| Samsung Electronics   | 1         | 2.56%   |
| Realtek Semiconductor | 1         | 2.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 9         | 21.95%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 4         | 9.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                | 4         | 9.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 7.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 3         | 7.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 3         | 7.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 2         | 4.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]         | 2         | 4.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                | 2         | 4.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 1         | 2.44%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 2.44%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 1         | 2.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                 | 1         | 2.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                              | 1         | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode] | 1         | 2.44%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile    | 1         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 1         | 2.44%   |
| Unknown                                                                       | 1         | 2.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 33        | 82.5%   |
| RAID | 3         | 7.5%    |
| NVMe | 2         | 5%      |
| IDE  | 2         | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 100%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 5.26%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 2         | 5.26%   |
| Intel Processor 5Y70 CPU @ 1.10GHz      | 1         | 2.63%   |
| Intel Pentium CPU N3530 @ 2.16GHz       | 1         | 2.63%   |
| Intel Pentium CPU 5405U @ 2.30GHz       | 1         | 2.63%   |
| Intel CPU Version                       | 1         | 2.63%   |
| Intel Core m3-8100Y CPU @ 1.10GHz       | 1         | 2.63%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 2.63%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 1         | 2.63%   |
| Intel Core i7-3517U CPU @ 1.90GHz       | 1         | 2.63%   |
| Intel Core i7-2640M CPU @ 2.80GH        | 1         | 2.63%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 2.63%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 1         | 2.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 1         | 2.63%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 1         | 2.63%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 1         | 2.63%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 1         | 2.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 1         | 2.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 2.63%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 1         | 2.63%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 1         | 2.63%   |
| Intel Core i5 CPU M 450 @ 2.40GHz       | 1         | 2.63%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 1         | 2.63%   |
| Intel Core i3-3227U CPU @ 1.90GHz       | 1         | 2.63%   |
| Intel Core i3 CPU M 370 @ 2.40GH        | 1         | 2.63%   |
| Intel Core i3 CPU M 330 @ 2.13GHz       | 1         | 2.63%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz    | 1         | 2.63%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz    | 1         | 2.63%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 1         | 2.63%   |
| Intel Core 2 Duo                        | 1         | 2.63%   |
| Intel Celeron CPU N2930 @ 1.83GHz       | 1         | 2.63%   |
| Intel Celeron CPU B815 @ 1.60GHz        | 1         | 2.63%   |
| Intel Celeron CPU 847 @ 1.10GHz         | 1         | 2.63%   |
| Intel Atom CPU N450 @ 1.66GHz           | 1         | 2.63%   |
| Intel Atom CPU E3825 @ 1.33GHz          | 1         | 2.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 1         | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 13        | 34.21%  |
| Intel Core i3    | 6         | 15.79%  |
| Intel Core i7    | 4         | 10.53%  |
| Intel Core 2 Duo | 4         | 10.53%  |
| Other            | 3         | 7.89%   |
| Intel Celeron    | 3         | 7.89%   |
| Intel Pentium    | 2         | 5.26%   |
| Intel Atom       | 2         | 5.26%   |
| Intel Core m3    | 1         | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 29        | 76.32%  |
| 4       | 5         | 13.16%  |
| Unknown | 3         | 7.89%   |
| 1       | 1         | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 37        | 97.37%  |
| 2      | 1         | 2.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 29        | 76.32%  |
| 1       | 6         | 15.79%  |
| Unknown | 3         | 7.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 9         | 23.68%  |
| Westmere    | 5         | 13.16%  |
| Haswell     | 5         | 13.16%  |
| Silvermont  | 3         | 7.89%   |
| SandyBridge | 3         | 7.89%   |
| Penryn      | 3         | 7.89%   |
| KabyLake    | 3         | 7.89%   |
| Broadwell   | 3         | 7.89%   |
| TigerLake   | 1         | 2.63%   |
| Nehalem     | 1         | 2.63%   |
| Core        | 1         | 2.63%   |
| Bonnell     | 1         | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 32        | 76.19%  |
| Nvidia | 8         | 19.05%  |
| AMD    | 2         | 4.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 9         | 21.43%  |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 9.52%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 7.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 7.14%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 2         | 4.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 4.76%   |
| Intel HD Graphics 5500                                                    | 2         | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 4.76%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 2.38%   |
| Nvidia GK107M [GeForce GT 640M LE]                                        | 1         | 2.38%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 2.38%   |
| Nvidia GF106M [GeForce GTX 460M]                                          | 1         | 2.38%   |
| Nvidia G98M [GeForce G 105M]                                              | 1         | 2.38%   |
| Nvidia G84M [GeForce 8600M GT]                                            | 1         | 2.38%   |
| Intel UHD Graphics 615                                                    | 1         | 2.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 2.38%   |
| Intel HD Graphics 620                                                     | 1         | 2.38%   |
| Intel HD Graphics 5300                                                    | 1         | 2.38%   |
| Intel Coffee Lake UHD 610 Graphics Controller                             | 1         | 2.38%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 2.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 2.38%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                | 1         | 2.38%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                              | 1         | 2.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 25        | 65.79%  |
| 1 x Nvidia     | 5         | 13.16%  |
| 2 x Intel      | 3         | 7.89%   |
| Intel + Nvidia | 3         | 7.89%   |
| Intel + AMD    | 1         | 2.63%   |
| 1 x AMD        | 1         | 2.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 31        | 81.58%  |
| Unknown | 7         | 18.42%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 97.37%  |
| 0.51-1.0   | 1         | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 9         | 30%     |
| AU Optronics        | 6         | 20%     |
| BOE                 | 5         | 16.67%  |
| Samsung Electronics | 4         | 13.33%  |
| Chimei Innolux      | 3         | 10%     |
| Lenovo              | 1         | 3.33%   |
| InfoVision          | 1         | 3.33%   |
| Apple               | 1         | 3.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 6.67%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 310x170mm 13.9-inch  | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 310x170mm 13.9-inch  | 1         | 3.33%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 290x170mm 13.2-inch | 1         | 3.33%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch           | 1         | 3.33%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 3.33%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch           | 1         | 3.33%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch          | 1         | 3.33%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch           | 1         | 3.33%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 1         | 3.33%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch       | 1         | 3.33%   |
| Chimei Innolux LCD Monitor CMN1124 1920x1080 260x140mm 11.6-inch      | 1         | 3.33%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 1         | 3.33%   |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                  | 1         | 3.33%   |
| BOE LCD Monitor BOE06C8 1366x768 280x160mm 12.7-inch                  | 1         | 3.33%   |
| BOE LCD Monitor BOE0615 1366x768 340x190mm 15.3-inch                  | 1         | 3.33%   |
| BOE LCD Monitor BOE05E9 1366x768 250x140mm 11.3-inch                  | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 340x190mm 15.3-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO4100 1920x1200 220x140mm 10.3-inch        | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch         | 1         | 3.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 1         | 3.33%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 1         | 3.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 19        | 63.33%  |
| 1920x1080 (FHD)   | 4         | 13.33%  |
| 1280x800 (WXGA)   | 2         | 6.67%   |
| 3200x1800 (QHD+)  | 1         | 3.33%   |
| 2560x1440 (QHD)   | 1         | 3.33%   |
| 1920x1200 (WUXGA) | 1         | 3.33%   |
| 1600x900 (HD+)    | 1         | 3.33%   |
| 1024x600          | 1         | 3.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 12        | 40%     |
| 13     | 7         | 23.33%  |
| 12     | 4         | 13.33%  |
| 11     | 4         | 13.33%  |
| 10     | 2         | 6.67%   |
| 17     | 1         | 3.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 17        | 56.67%  |
| 201-300     | 12        | 40%     |
| 351-400     | 1         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 27        | 90%     |
| 16/10 | 3         | 10%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 8         | 26.67%  |
| 81-90          | 6         | 20%     |
| 61-70          | 4         | 13.33%  |
| 51-60          | 4         | 13.33%  |
| 101-110        | 4         | 13.33%  |
| 41-50          | 2         | 6.67%   |
| 71-80          | 1         | 3.33%   |
| 121-130        | 1         | 3.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 14        | 46.67%  |
| 121-160       | 10        | 33.33%  |
| 161-240       | 3         | 10%     |
| 51-100        | 2         | 6.67%   |
| More than 240 | 1         | 3.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 31        | 81.58%  |
| 0     | 7         | 18.42%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 21        | 34.43%  |
| Realtek Semiconductor             | 19        | 31.15%  |
| Qualcomm Atheros                  | 7         | 11.48%  |
| Broadcom                          | 7         | 11.48%  |
| Huawei Technologies               | 2         | 3.28%   |
| Sierra Wireless                   | 1         | 1.64%   |
| Ralink                            | 1         | 1.64%   |
| Marvell Technology Group          | 1         | 1.64%   |
| Google                            | 1         | 1.64%   |
| Ericsson Business Mobile Networks | 1         | 1.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 10        | 12.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 6         | 7.79%   |
| Intel Wireless 7265                                                         | 4         | 5.19%   |
| Intel Wireless 7260                                                         | 3         | 3.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 3         | 3.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2         | 2.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 2.6%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 2         | 2.6%    |
| Broadcom BCM43142 802.11b/g/n                                               | 2         | 2.6%    |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                               | 1         | 1.3%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 1         | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1         | 1.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 1         | 1.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                      | 1         | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1         | 1.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 1         | 1.3%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                       | 1         | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                    | 1         | 1.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 1.3%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                     | 1         | 1.3%    |
| Intel Wireless 8265 / 8275                                                  | 1         | 1.3%    |
| Intel Wireless 3160                                                         | 1         | 1.3%    |
| Intel WiFi Link 5100                                                        | 1         | 1.3%    |
| Intel Wi-Fi 6 AX201                                                         | 1         | 1.3%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1         | 1.3%    |
| Intel Ethernet Connection I218-LM                                           | 1         | 1.3%    |
| Intel Ethernet Connection I217-LM                                           | 1         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 1.3%    |
| Intel Ethernet Connection (3) I218-LM                                       | 1         | 1.3%    |
| Intel Centrino Wireless-N 6150                                              | 1         | 1.3%    |
| Intel Centrino Wireless-N 2200                                              | 1         | 1.3%    |
| Intel Centrino Wireless-N 135                                               | 1         | 1.3%    |
| Intel Centrino WiMAX 6150                                                   | 1         | 1.3%    |
| Intel Centrino Ultimate-N 6300                                              | 1         | 1.3%    |
| Intel Centrino Advanced-N 6235                                              | 1         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 1.3%    |
| Intel 82577LC Gigabit Network Connection                                    | 1         | 1.3%    |
| Intel 82567LM Gigabit Network Connection                                    | 1         | 1.3%    |
| Huawei USB Composite Device                                                 | 1         | 1.3%    |
| Huawei ME936 LTE/HSDPA+ 4G modem                                            | 1         | 1.3%    |
| Google Nexus/Pixel Device (tether)                                          | 1         | 1.3%    |
| Ericsson Business Mobile Networks N5321 gw Mobile Broadband Serial Port III | 1         | 1.3%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                      | 1         | 1.3%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                             | 1         | 1.3%    |
| Broadcom BCM43228 802.11a/b/g/n                                             | 1         | 1.3%    |
| Broadcom BCM43225 802.11b/g/n                                               | 1         | 1.3%    |
| Broadcom BCM43224 802.11a/b/g/n                                             | 1         | 1.3%    |
| Broadcom BCM4321 802.11a/b/g/n                                              | 1         | 1.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 50%     |
| Realtek Semiconductor | 7         | 17.5%   |
| Broadcom              | 6         | 15%     |
| Qualcomm Atheros      | 5         | 12.5%   |
| Sierra Wireless       | 1         | 2.5%    |
| Ralink                | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 4         | 9.52%   |
| Intel Wireless 7260                                                     | 3         | 7.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 4.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 4.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 4.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 4.76%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 2.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 2.38%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 2.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 2.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 2.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 2.38%   |
| Intel Wireless 8265 / 8275                                              | 1         | 2.38%   |
| Intel Wireless 3160                                                     | 1         | 2.38%   |
| Intel WiFi Link 5100                                                    | 1         | 2.38%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 2.38%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 2.38%   |
| Intel Centrino Wireless-N 6150                                          | 1         | 2.38%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 2.38%   |
| Intel Centrino Wireless-N 135                                           | 1         | 2.38%   |
| Intel Centrino WiMAX 6150                                               | 1         | 2.38%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 2.38%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 2.38%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 2.38%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 2.38%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 2.38%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 16        | 48.48%  |
| Intel                    | 9         | 27.27%  |
| Qualcomm Atheros         | 3         | 9.09%   |
| Broadcom                 | 2         | 6.06%   |
| Marvell Technology Group | 1         | 3.03%   |
| Huawei Technologies      | 1         | 3.03%   |
| Google                   | 1         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 30.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 18.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 9.09%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 3.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 3.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 3.03%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 3.03%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 3.03%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 3.03%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 3.03%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 3.03%   |
| Huawei USB Composite Device                                       | 1         | 3.03%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 3.03%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 3.03%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 3.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 38        | 52.78%  |
| Ethernet | 32        | 44.44%  |
| Modem    | 2         | 2.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 49.18%  |
| Ethernet | 30        | 49.18%  |
| Modem    | 1         | 1.64%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 30        | 78.95%  |
| 1     | 8         | 21.05%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 38        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 9         | 40.91%  |
| Broadcom                        | 4         | 18.18%  |
| Realtek Semiconductor           | 3         | 13.64%  |
| Apple                           | 2         | 9.09%   |
| Ralink                          | 1         | 4.55%   |
| Qualcomm Atheros Communications | 1         | 4.55%   |
| Foxconn / Hon Hai               | 1         | 4.55%   |
| Cambridge Silicon Radio         | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 31.82%  |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 9.09%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 9.09%   |
| Realtek RTL8723B Bluetooth                          | 1         | 4.55%   |
| Realtek  Bluetooth Adapter                          | 1         | 4.55%   |
| Realtek Bluetooth Radio                             | 1         | 4.55%   |
| Ralink RT3290 Bluetooth                             | 1         | 4.55%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.55%   |
| Intel AX201 Bluetooth                               | 1         | 4.55%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth          | 1         | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 4.55%   |
| Apple Bluetooth HCI                                 | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 38        | 88.37%  |
| Nvidia | 3         | 6.98%   |
| XMOS   | 1         | 2.33%   |
| AMD    | 1         | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 20%     |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 12%     |
| Intel 8 Series HD Audio Controller                                         | 4         | 8%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 6%      |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 6%      |
| Intel Broadwell-U Audio Controller                                         | 3         | 6%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 6%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 6%      |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 4%      |
| XMOS retrieving string failed                                              | 1         | 2%      |
| Nvidia High Definition Audio Controller                                    | 1         | 2%      |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 2%      |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 2%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 2%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 2%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 2%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 2%      |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 13        | 26.53%  |
| Micron Technology   | 7         | 14.29%  |
| Unknown             | 6         | 12.24%  |
| Samsung Electronics | 5         | 10.2%   |
| Kingston            | 4         | 8.16%   |
| Teikon              | 2         | 4.08%   |
| Team                | 2         | 4.08%   |
| Elpida              | 2         | 4.08%   |
| Unknown             | 2         | 4.08%   |
| Smart Brazil        | 1         | 2.04%   |
| Smart               | 1         | 2.04%   |
| PKI/Kingston        | 1         | 2.04%   |
| Nanya Technology    | 1         | 2.04%   |
| ASint Technology    | 1         | 2.04%   |
| A-DATA Technology   | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                              | 2         | 4%      |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                  | 2         | 4%      |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                  | 2         | 4%      |
| Unknown                                                                 | 2         | 4%      |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1         | 2%      |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                             | 1         | 2%      |
| Unknown RAM Module 4GB SODIMM DDR3                                      | 1         | 2%      |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                               | 1         | 2%      |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s                  | 1         | 2%      |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s                  | 1         | 2%      |
| Team RAM TEAMGROUP-SD3-1066 4GB SODIMM DDR3 1067MT/s                    | 1         | 2%      |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                            | 1         | 2%      |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                   | 1         | 2%      |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s            | 1         | 2%      |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 1600MT/s                    | 1         | 2%      |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                            | 1         | 2%      |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s                  | 1         | 2%      |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                  | 1         | 2%      |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                  | 1         | 2%      |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                  | 1         | 2%      |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                  | 1         | 2%      |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                  | 1         | 2%      |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s                  | 1         | 2%      |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s                  | 1         | 2%      |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s                   | 1         | 2%      |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s                  | 1         | 2%      |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1333MT/s                   | 1         | 2%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s                   | 1         | 2%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                   | 1         | 2%      |
| PKI/Kingston RAM 9905428-043.A00LF 4GB SODIMM DDR3 1067MT/s             | 1         | 2%      |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1066MT/s                    | 1         | 2%      |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                              | 1         | 2%      |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s                   | 1         | 2%      |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1333MT/s                   | 1         | 2%      |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s                    | 1         | 2%      |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s             | 1         | 2%      |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s                   | 1         | 2%      |
| Micron RAM 16JSF25664HY-1G1D1 2GB SODIMM DDR3 1066MT/s                  | 1         | 2%      |
| Kingston RAM TSB16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s                  | 1         | 2%      |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s                  | 1         | 2%      |
| Kingston RAM ACR16D3LS1KDG/2G 2GB SODIMM DDR3 1066MT/s                  | 1         | 2%      |
| Kingston RAM 9905428-012.A00LF 4GB SODIMM DDR3 1333MT/s                 | 1         | 2%      |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 2%      |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1333MT/s                   | 1         | 2%      |
| ASint RAM SSZ3128M8-EDJED 2GB SODIMM DDR3 1067MT/s                      | 1         | 2%      |
| A-DATA RAM 20444F564531423136334245202020202020 2GB SODIMM DDR2 667MT/s | 1         | 2%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 30        | 78.95%  |
| DDR2   | 3         | 7.89%   |
| LPDDR3 | 2         | 5.26%   |
| DDR4   | 2         | 5.26%   |
| LPDDR4 | 1         | 2.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 89.47%  |
| Row Of Chips | 2         | 5.26%   |
| DIMM         | 1         | 2.63%   |
| Chip         | 1         | 2.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 22        | 50%     |
| 2048 | 14        | 31.82%  |
| 8192 | 8         | 18.18%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 17        | 41.46%  |
| 1333    | 10        | 24.39%  |
| 1067    | 4         | 9.76%   |
| 667     | 3         | 7.32%   |
| 1066    | 2         | 4.88%   |
| 4267    | 1         | 2.44%   |
| 2400    | 1         | 2.44%   |
| 2133    | 1         | 2.44%   |
| 1334    | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 6         | 20.69%  |
| Sunplus Innovation Technology          | 3         | 10.34%  |
| Realtek Semiconductor                  | 3         | 10.34%  |
| Acer                                   | 3         | 10.34%  |
| Suyin                                  | 2         | 6.9%    |
| Microdia                               | 2         | 6.9%    |
| Tripath Technology                     | 1         | 3.45%   |
| Syntek                                 | 1         | 3.45%   |
| Lite-On Technology                     | 1         | 3.45%   |
| Lenovo                                 | 1         | 3.45%   |
| Importek                               | 1         | 3.45%   |
| IMC Networks                           | 1         | 3.45%   |
| Foxconn / Hon Hai                      | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.45%   |
| Apple                                  | 1         | 3.45%   |
| ALi                                    | 1         | 3.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 4         | 13.79%  |
| Realtek Realtek USB2.0 PC Camera                            | 2         | 6.9%    |
| Tripath 2M Front Camera                                     | 1         | 3.45%   |
| Syntek EasyCamera                                           | 1         | 3.45%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 3.45%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 3.45%   |
| Sunplus Lenovo EasyCamera                                   | 1         | 3.45%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 3.45%   |
| Sunplus Integrated Camera                                   | 1         | 3.45%   |
| Realtek Integrated_Webcam_HD                                | 1         | 3.45%   |
| Microdia Laptop_Integrated_Webcam_2M                        | 1         | 3.45%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 3.45%   |
| Lite-On Integrated Camera                                   | 1         | 3.45%   |
| Lenovo Integrated Webcam                                    | 1         | 3.45%   |
| Importek HP Webcam                                          | 1         | 3.45%   |
| IMC Networks 2M Integrated Webcam                           | 1         | 3.45%   |
| Foxconn / Hon Hai USB2.0 Camera                             | 1         | 3.45%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 3.45%   |
| Chicony Asus 720p CMOS webcam                               | 1         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101        | 1         | 3.45%   |
| Apple FaceTime HD Camera (Built-in)                         | 1         | 3.45%   |
| ALi WebCam                                                  | 1         | 3.45%   |
| Acer ThinkPad Integrated Camera                             | 1         | 3.45%   |
| Acer Lenovo EasyCamera                                      | 1         | 3.45%   |
| Acer Integrated Camera                                      | 1         | 3.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 60%     |
| AuthenTec        | 2         | 40%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 2         | 40%     |
| Validity Sensors VFS301 Fingerprint Reader   | 1         | 20%     |
| AuthenTec AuthenTec Inc. AES1660             | 1         | 20%     |
| AuthenTec AES2810                            | 1         | 20%     |

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
| 2     | 13        | 34.21%  |
| 1     | 12        | 31.58%  |
| 3     | 8         | 21.05%  |
| 0     | 4         | 10.53%  |
| 4     | 1         | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 29        | 45.31%  |
| Card reader              | 11        | 17.19%  |
| Net/wireless             | 9         | 14.06%  |
| Fingerprint reader       | 5         | 7.81%   |
| Firewire controller      | 4         | 6.25%   |
| Bluetooth                | 3         | 4.69%   |
| Storage                  | 2         | 3.13%   |
| Network                  | 1         | 1.56%   |

