NomadBSD 20221130 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for NomadBSD 20221130.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 31

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek       | 1005PXD                     | [1b05e8cf1b](https://bsd-hardware.info/?probe=1b05e8cf1b) | Sep 29, 2023 |
| MSI           | CX62 6QD                    | [e732d89b06](https://bsd-hardware.info/?probe=e732d89b06) | Sep 29, 2023 |
| Apple         | MacBookPro7,1               | [714516a696](https://bsd-hardware.info/?probe=714516a696) | Sep 29, 2023 |
| Apple         | MacBookPro9,1               | [cac0950717](https://bsd-hardware.info/?probe=cac0950717) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | [3c69dd7003](https://bsd-hardware.info/?probe=3c69dd7003) | Sep 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HHC... | [74d0396f87](https://bsd-hardware.info/?probe=74d0396f87) | Sep 27, 2023 |
| Dell          | XPS 13 7390                 | [6bb6186f22](https://bsd-hardware.info/?probe=6bb6186f22) | Sep 19, 2023 |
| eMachines     | G640                        | [c05619033c](https://bsd-hardware.info/?probe=c05619033c) | Sep 14, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [68efc7ef8d](https://bsd-hardware.info/?probe=68efc7ef8d) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [f42dfa2992](https://bsd-hardware.info/?probe=f42dfa2992) | Sep 06, 2023 |
| Unknown       | Unknown                     | [084127fd8b](https://bsd-hardware.info/?probe=084127fd8b) | Sep 06, 2023 |
| Lenovo        | ThinkPad X230 2325IB1       | [41fbf7d1ca](https://bsd-hardware.info/?probe=41fbf7d1ca) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [2854f97c81](https://bsd-hardware.info/?probe=2854f97c81) | Aug 01, 2023 |
| Fujitsu Si... | AMILO Li3710                | [7a5d32eb7f](https://bsd-hardware.info/?probe=7a5d32eb7f) | Jul 29, 2023 |
| HP            | EliteBook 750 G1            | [e0af4797d4](https://bsd-hardware.info/?probe=e0af4797d4) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | [461a92a1a2](https://bsd-hardware.info/?probe=461a92a1a2) | Jun 20, 2023 |
| Lenovo        | ThinkPad E495 20NE000BSP    | [0e02b323ee](https://bsd-hardware.info/?probe=0e02b323ee) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | [f6e5189f54](https://bsd-hardware.info/?probe=f6e5189f54) | Apr 11, 2023 |
| Lenovo        | ThinkPad X280 20KESB4T00    | [fb6c7b3b09](https://bsd-hardware.info/?probe=fb6c7b3b09) | Apr 11, 2023 |
| Dell          | Latitude 7300               | [d036260cce](https://bsd-hardware.info/?probe=d036260cce) | Apr 08, 2023 |
| Lenovo        | ThinkPad X230 23255NG       | [2ef93a7621](https://bsd-hardware.info/?probe=2ef93a7621) | Mar 29, 2023 |
| Acer          | Swift SF314-56              | [94c7da1b3f](https://bsd-hardware.info/?probe=94c7da1b3f) | Mar 13, 2023 |
| Intel         | Jasper Lake Client Platf... | [de93a79b7d](https://bsd-hardware.info/?probe=de93a79b7d) | Mar 10, 2023 |
| Lenovo        | ThinkPad T470 20HES0EV0A    | [dd6c3fa0f7](https://bsd-hardware.info/?probe=dd6c3fa0f7) | Mar 10, 2023 |
| Fujitsu       | CELSIUS H730                | [d2292bbcda](https://bsd-hardware.info/?probe=d2292bbcda) | Mar 10, 2023 |
| Acer          | Aspire 7738                 | [e61cd20061](https://bsd-hardware.info/?probe=e61cd20061) | Feb 18, 2023 |
| Lenovo        | ThinkPad W520 42844DG       | [d341f3c6f6](https://bsd-hardware.info/?probe=d341f3c6f6) | Feb 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [941da31f26](https://bsd-hardware.info/?probe=941da31f26) | Feb 02, 2023 |
| Lenovo        | G50-70 20351                | [6a1ff80054](https://bsd-hardware.info/?probe=6a1ff80054) | Jan 04, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | [1d3ccd1fe6](https://bsd-hardware.info/?probe=1d3ccd1fe6) | Dec 22, 2022 |
| Apple         | MacBookPro14,1              | [5234a39100](https://bsd-hardware.info/?probe=5234a39100) | Dec 10, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 24        | 96%     |
| i386  | 1         | 4%      |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Openbox | 17        | 68%     |
| xinitrc | 6         | 24%     |
| KDE5    | 2         | 8%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 25        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 25        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 6         | 24%     |
| en_GB   | 5         | 20%     |
| fr_FR   | 4         | 16%     |
| zh_TW   | 3         | 12%     |
| fi_FI   | 3         | 12%     |
| sv_SE   | 1         | 4%      |
| ru_RU   | 1         | 4%      |
| lt_LT   | 1         | 4%      |
| Unknown | 1         | 4%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 25        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Ufs  | 15        | 60%     |
| Zfs  | 10        | 40%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 15        | 60%     |
| MBR  | 10        | 40%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 11        | 44%     |
| Dell                | 2         | 8%      |
| ASUSTek Computer    | 2         | 8%      |
| Apple               | 2         | 8%      |
| Acer                | 2         | 8%      |
| Samsung Electronics | 1         | 4%      |
| Hewlett-Packard     | 1         | 4%      |
| Fujitsu Siemens     | 1         | 4%      |
| Fujitsu             | 1         | 4%      |
| eMachines           | 1         | 4%      |
| Chuwi               | 1         | 4%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung N150/N210/N220                   | 1         | 4%      |
| Lenovo Yoga 710-11IKB 80V6               | 1         | 4%      |
| Lenovo ThinkPad X280 20KESB4T00          | 1         | 4%      |
| Lenovo ThinkPad X230 2325IB1             | 1         | 4%      |
| Lenovo ThinkPad X230 23255NG             | 1         | 4%      |
| Lenovo ThinkPad X1 Nano Gen 1 20UN005LRT | 1         | 4%      |
| Lenovo ThinkPad W520 42844DG             | 1         | 4%      |
| Lenovo ThinkPad T470 20HES0EV0A          | 1         | 4%      |
| Lenovo ThinkPad T16 Gen 2 21HHCTO1WW     | 1         | 4%      |
| Lenovo ThinkPad E495 20NE000BSP          | 1         | 4%      |
| Lenovo ThinkPad E14 20RA0036RT           | 1         | 4%      |
| Lenovo G50-70 20351                      | 1         | 4%      |
| HP EliteBook 750 G1                      | 1         | 4%      |
| Fujitsu Siemens AMILO Li3710             | 1         | 4%      |
| Fujitsu CELSIUS H730                     | 1         | 4%      |
| eMachines G640                           | 1         | 4%      |
| Dell XPS 13 7390                         | 1         | 4%      |
| Dell Latitude 7300                       | 1         | 4%      |
| Chuwi CoreBook X                         | 1         | 4%      |
| ASUS K40IN                               | 1         | 4%      |
| ASUS 1005PXD                             | 1         | 4%      |
| Apple MacBookPro7,1                      | 1         | 4%      |
| Apple MacBookPro14,1                     | 1         | 4%      |
| Acer Swift SF314-56                      | 1         | 4%      |
| Acer Aspire 7738                         | 1         | 4%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 9         | 36%     |
| Samsung N150          | 1         | 4%      |
| Lenovo Yoga           | 1         | 4%      |
| Lenovo G50-70         | 1         | 4%      |
| HP EliteBook          | 1         | 4%      |
| Fujitsu Siemens AMILO | 1         | 4%      |
| Fujitsu CELSIUS       | 1         | 4%      |
| eMachines G640        | 1         | 4%      |
| Dell XPS              | 1         | 4%      |
| Dell Latitude         | 1         | 4%      |
| Chuwi CoreBook        | 1         | 4%      |
| ASUS K40IN            | 1         | 4%      |
| ASUS 1005PXD          | 1         | 4%      |
| Apple MacBookPro7     | 1         | 4%      |
| Apple MacBookPro14    | 1         | 4%      |
| Acer Swift            | 1         | 4%      |
| Acer Aspire           | 1         | 4%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 4         | 16%     |
| 2022 | 3         | 12%     |
| 2012 | 3         | 12%     |
| 2023 | 2         | 8%      |
| 2020 | 2         | 8%      |
| 2011 | 2         | 8%      |
| 2010 | 2         | 8%      |
| 2009 | 2         | 8%      |
| 2021 | 1         | 4%      |
| 2018 | 1         | 4%      |
| 2016 | 1         | 4%      |
| 2015 | 1         | 4%      |
| 2014 | 1         | 4%      |

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
| No   | 24        | 96%     |
| Yes  | 1         | 4%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 10        | 40%     |
| 16.01-24.0 | 7         | 28%     |
| 4.01-8.0   | 3         | 12%     |
| 2.01-3.0   | 3         | 12%     |
| 32.01-64.0 | 1         | 4%      |
| 24.01-32.0 | 1         | 4%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 13        | 52%     |
| 0.51-1.0 | 9         | 36%     |
| 1.01-2.0 | 2         | 8%      |
| 2.01-3.0 | 1         | 4%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 18        | 72%     |
| 2      | 4         | 16%     |
| 0      | 3         | 12%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 18        | 72%     |
| Yes       | 7         | 28%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 76%     |
| No        | 6         | 24%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 64%     |
| No        | 9         | 36%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| UK         | 5         | 20%     |
| France     | 5         | 20%     |
| USA        | 3         | 12%     |
| Taiwan     | 3         | 12%     |
| Finland    | 3         | 12%     |
| Russia     | 2         | 8%      |
| Sweden     | 1         | 4%      |
| Spain      | 1         | 4%      |
| San Marino | 1         | 4%      |
| Lithuania  | 1         | 4%      |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Turku          | 2         | 8%      |
| Taipei         | 2         | 8%      |
| Moscow         | 2         | 8%      |
| Melun          | 2         | 8%      |
| West Bromwich  | 1         | 4%      |
| Wakefield      | 1         | 4%      |
| Vilnius        | 1         | 4%      |
| Vaasa          | 1         | 4%      |
| Urcuit         | 1         | 4%      |
| Taichung       | 1         | 4%      |
| Södertälje   | 1         | 4%      |
| Seattle        | 1         | 4%      |
| Sartrouville   | 1         | 4%      |
| San Marino     | 1         | 4%      |
| Saint-Raphaël | 1         | 4%      |
| Rubí          | 1         | 4%      |
| Portland       | 1         | 4%      |
| Lincoln        | 1         | 4%      |
| Leesburg       | 1         | 4%      |
| Belfast        | 1         | 4%      |
| Addlestone     | 1         | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 16%     |
| Transcend           | 3         | 3      | 12%     |
| SanDisk             | 3         | 3      | 12%     |
| Toshiba             | 2         | 2      | 8%      |
| Crucial             | 2         | 2      | 8%      |
| WDC                 | 1         | 1      | 4%      |
| UMIS                | 1         | 1      | 4%      |
| SPCC                | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| Seagate             | 1         | 1      | 4%      |
| Phison              | 1         | 1      | 4%      |
| Kingston            | 1         | 1      | 4%      |
| Intel               | 1         | 1      | 4%      |
| Hitachi             | 1         | 2      | 4%      |
| AirDisk             | 1         | 1      | 4%      |
| A-DATA Technology   | 1         | 1      | 4%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| WDC WD7500BPKX-00HPJT0 752GB      | 1         | 4%      |
| UMIS RPJTJ256MED1OWX 256GB        | 1         | 4%      |
| Transcend TS512GSSD230S 512GB     | 1         | 4%      |
| Transcend TS128GSSD340K 128GB     | 1         | 4%      |
| Transcend TS128GSSD340 128GB      | 1         | 4%      |
| Toshiba MK3265GSX 320GB           | 1         | 4%      |
| Toshiba KBG40ZNT512G MEMORY 512GB | 1         | 4%      |
| SPCC Solid State Disk 128GB       | 1         | 4%      |
| SK hynix HFM512GDHTNG-8710B 512GB | 1         | 4%      |
| Seagate ST9160314AS 160GB         | 1         | 4%      |
| SanDisk X400 M.2 2280 256GB       | 1         | 4%      |
| SanDisk SDSSDA240G 240GB          | 1         | 4%      |
| SanDisk pSSD 256GB                | 1         | 4%      |
| Samsung SSD PM851 2.5 7mm 256GB   | 1         | 4%      |
| Samsung SSD 860 EVO M.2 250GB     | 1         | 4%      |
| Samsung SSD 850 EVO 2TB           | 1         | 4%      |
| Samsung PM981a NVMe 512GB         | 1         | 4%      |
| Phison Sabrent Rocket nano 512GB  | 1         | 4%      |
| Kingston SA400S37240G 240GB       | 1         | 4%      |
| Intel SSDPEKKF256G8L 256GB        | 1         | 4%      |
| Hitachi HTS545050B9A300 500GB     | 1         | 4%      |
| Crucial CT256MX100SSD1 256GB      | 1         | 4%      |
| Crucial CT2000BX500SSD1 2TB       | 1         | 4%      |
| AirDisk 512GB SSD                 | 1         | 4%      |
| A-DATA SSD DP900 512GB-DL3        | 1         | 4%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |
| Hitachi | 1         | 2      | 25%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Transcend           | 3         | 3      | 21.43%  |
| SanDisk             | 3         | 3      | 21.43%  |
| Samsung Electronics | 3         | 3      | 21.43%  |
| Crucial             | 2         | 2      | 14.29%  |
| SPCC                | 1         | 1      | 7.14%   |
| Kingston            | 1         | 1      | 7.14%   |
| A-DATA Technology   | 1         | 1      | 7.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 14        | 14     | 56%     |
| NVMe | 7         | 7      | 28%     |
| HDD  | 4         | 5      | 16%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 17        | 19     | 70.83%  |
| NVMe | 7         | 7      | 29.17%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 13        | 14     | 72.22%  |
| 0.51-1.0   | 3         | 3      | 16.67%  |
| 1.01-2.0   | 2         | 2      | 11.11%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 17        | 68%     |
| 21-50      | 4         | 16%     |
| 101-250    | 2         | 8%      |
| 251-500    | 1         | 4%      |
| 501-1000   | 1         | 4%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 25        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Toshiba MK3265GSX 320GB       | 1         | 1      | 50%     |
| Hitachi HTS545050B9A300 500GB | 1         | 2      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Hitachi | 1         | 2      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Hitachi | 1         | 2      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 3      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model              | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| SanDisk pSSD 256GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 21        | 22     | 87.5%   |
| Malfunc | 2         | 3      | 8.33%   |
| Failed  | 1         | 1      | 4.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 17        | 62.96%  |
| Nvidia                                  | 2         | 7.41%   |
| SK hynix                                | 1         | 3.7%    |
| Shenzhen Unionmemory Information System | 1         | 3.7%    |
| Sandisk                                 | 1         | 3.7%    |
| Samsung Electronics                     | 1         | 3.7%    |
| Phison Electronics                      | 1         | 3.7%    |
| MAXIO Technology (Hangzhou)             | 1         | 3.7%    |
| KIOXIA                                  | 1         | 3.7%    |
| AMD                                     | 1         | 3.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 10.71%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 2         | 7.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 2         | 7.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 7.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 7.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 7.14%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 3.57%   |
| Shenzhen Unionmemory Information System AM611 PCIe 3.0 NVMe SSD 256GB          | 1         | 3.57%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 1         | 3.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 3.57%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 3.57%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 3.57%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 3.57%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 3.57%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1         | 3.57%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 1         | 3.57%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 3.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1         | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 1         | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1         | 3.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 17        | 60.71%  |
| NVMe | 8         | 28.57%  |
| RAID | 2         | 7.14%   |
| IDE  | 1         | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 92%     |
| AMD    | 2         | 8%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz   | 2         | 8%      |
| Intel CPU Version                             | 1         | 4%      |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 4%      |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 4%      |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 4%      |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 4%      |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 4%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 4%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 4%      |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 4%      |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 4%      |
| Intel Core i5-7300U CPU @ 2.60GHz             | 1         | 4%      |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 4%      |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 4%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 4%      |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 4%      |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 4%      |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 4%      |
| Intel Atom CPU N450 @ 1.66GHz                 | 1         | 4%      |
| Intel 13th Gen Core i7-1355U                  | 1         | 4%      |
| Intel 12th Gen Core i5-1235U                  | 1         | 4%      |
| Intel 11th Gen Core i5-1130G7 @ 1.10GHz       | 1         | 4%      |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 1         | 4%      |
| AMD New Processor Technology                  | 1         | 4%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 8         | 32%     |
| Other                   | 5         | 20%     |
| Intel Core i7           | 5         | 20%     |
| Intel Celeron Dual-Core | 2         | 8%      |
| Intel Atom              | 2         | 8%      |
| Intel Core i3           | 1         | 4%      |
| Intel Core 2 Duo        | 1         | 4%      |
| AMD Ryzen 7             | 1         | 4%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 11        | 44%     |
| 4       | 8         | 32%     |
| 12      | 2         | 8%      |
| Unknown | 2         | 8%      |
| 8       | 1         | 4%      |
| 1       | 1         | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 23        | 92%     |
| 2       | 1         | 4%      |
| Unknown | 1         | 4%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 16        | 64%     |
| 1       | 7         | 28%     |
| Unknown | 2         | 8%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 8         | 32%     |
| Penryn      | 4         | 16%     |
| Haswell     | 3         | 12%     |
| IvyBridge   | 2         | 8%      |
| Bonnell     | 2         | 8%      |
| Unknown     | 2         | 8%      |
| Zen+        | 1         | 4%      |
| TigerLake   | 1         | 4%      |
| SandyBridge | 1         | 4%      |
| K10         | 1         | 4%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 75%     |
| Nvidia | 5         | 17.86%  |
| AMD    | 2         | 7.14%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 10.71%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 7.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 7.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 7.14%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 2         | 7.14%   |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 3.57%   |
| Nvidia GT216M [GeForce GT 240M]                                           | 1         | 3.57%   |
| Nvidia GK106GLM [Quadro K2100M]                                           | 1         | 3.57%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 3.57%   |
| Nvidia C79 [GeForce G102M]                                                | 1         | 3.57%   |
| Intel UHD Graphics 620                                                    | 1         | 3.57%   |
| Intel Tiger Lake-UP4 GT2 [Iris Xe Graphics]                               | 1         | 3.57%   |
| Intel Raptor Lake-P [UHD Graphics]                                        | 1         | 3.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 1         | 3.57%   |
| Intel Iris Plus Graphics 640                                              | 1         | 3.57%   |
| Intel HD Graphics 620                                                     | 1         | 3.57%   |
| Intel HD Graphics 615                                                     | 1         | 3.57%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 1         | 3.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 3.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 3.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 3.57%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 1         | 3.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 60%     |
| 2 x Intel      | 3         | 12%     |
| 1 x Nvidia     | 3         | 12%     |
| Intel + Nvidia | 2         | 8%      |
| 1 x AMD        | 2         | 8%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 23        | 92%     |
| Proprietary | 1         | 4%      |
| Unknown     | 1         | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 18.18%  |
| HannStar            | 2         | 18.18%  |
| Chimei Innolux      | 2         | 18.18%  |
| AU Optronics        | 2         | 18.18%  |
| LG Display          | 1         | 9.09%   |
| BOE                 | 1         | 9.09%   |
| Apple               | 1         | 9.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch | 1         | 9.09%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch | 1         | 9.09%   |
| LG Display LCD Monitor LGD03A3 1366x768 280x160mm 12.7-inch          | 1         | 9.09%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch            | 1         | 9.09%   |
| HannStar HSD140PHW1 HSD0583 1366x768 310x170mm 13.9-inch             | 1         | 9.09%   |
| Chimei Innolux LCD Monitor CMN1301 2160x1350 280x170mm 12.9-inch     | 1         | 9.09%   |
| Chimei Innolux LCD Monitor CMN1137 1920x1080 260x140mm 11.6-inch     | 1         | 9.09%   |
| BOE LCD Monitor BOE0742 1920x1080 310x170mm 13.9-inch                | 1         | 9.09%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 340x190mm 15.3-inch       | 1         | 9.09%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 290x170mm 13.2-inch       | 1         | 9.09%   |
| Apple Color LCD APPA034 2880x1800 290x180mm 13.4-inch                | 1         | 9.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1920x1080 (FHD) | 4         | 36.36%  |
| 1366x768 (WXGA) | 3         | 27.27%  |
| 3840x2160 (4K)  | 1         | 9.09%   |
| 2880x1800       | 1         | 9.09%   |
| 2160x1350       | 1         | 9.09%   |
| 1024x600        | 1         | 9.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 4         | 36.36%  |
| 15     | 3         | 27.27%  |
| 12     | 2         | 18.18%  |
| 11     | 1         | 9.09%   |
| 10     | 1         | 9.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 201-300     | 6         | 54.55%  |
| 301-350     | 5         | 45.45%  |

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
| 81-90          | 3         | 27.27%  |
| 71-80          | 2         | 18.18%  |
| 91-100         | 2         | 18.18%  |
| 61-70          | 1         | 9.09%   |
| 51-60          | 1         | 9.09%   |
| 41-50          | 1         | 9.09%   |
| 101-110        | 1         | 9.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3         | 27.27%  |
| 101-120       | 3         | 27.27%  |
| More than 240 | 2         | 18.18%  |
| 161-240       | 2         | 18.18%  |
| 51-100        | 1         | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 21        | 84%     |
| 0     | 4         | 16%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 17        | 39.53%  |
| Realtek Semiconductor             | 7         | 16.28%  |
| Qualcomm Atheros                  | 5         | 11.63%  |
| Broadcom                          | 5         | 11.63%  |
| Samsung Electronics               | 2         | 4.65%   |
| TP-Link                           | 1         | 2.33%   |
| Sierra Wireless                   | 1         | 2.33%   |
| Ralink Technology                 | 1         | 2.33%   |
| Marvell Technology Group          | 1         | 2.33%   |
| Ericsson Business Mobile Networks | 1         | 2.33%   |
| D-Link                            | 1         | 2.33%   |
| Apple                             | 1         | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 4         | 7.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 4         | 7.41%   |
| Samsung Galaxy series, misc. (tethering mode)                               | 2         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 3.7%    |
| Intel Wireless 8265 / 8275                                                  | 2         | 3.7%    |
| Intel Centrino Ultimate-N 6300                                              | 2         | 3.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 3.7%    |
| TP-Link Wireless USB Adapter                                                | 1         | 1.85%   |
| Sierra Wireless EM7305 Modem                                                | 1         | 1.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 1         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 1.85%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                          | 1         | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 1         | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 1         | 1.85%   |
| Ralink RT5372 Wireless Adapter                                              | 1         | 1.85%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                            | 1         | 1.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1         | 1.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 1.85%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                        | 1         | 1.85%   |
| Intel Wireless 8260                                                         | 1         | 1.85%   |
| Intel Wireless 7260                                                         | 1         | 1.85%   |
| Intel WiFi Link 5100                                                        | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 1.85%   |
| Intel Wi-Fi 6 AX200                                                         | 1         | 1.85%   |
| Intel Raptor Lake PCH CNVi WiFi                                             | 1         | 1.85%   |
| Intel Ethernet Controller I219-V                                            | 1         | 1.85%   |
| Intel Ethernet Connection I218-LM                                           | 1         | 1.85%   |
| Intel Ethernet Connection I217-LM                                           | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-V                                        | 1         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                                       | 1         | 1.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 1         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 1.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                            | 1         | 1.85%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 1         | 1.85%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]        | 1         | 1.85%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                           | 1         | 1.85%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                             | 1         | 1.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                             | 1         | 1.85%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                          | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 50%     |
| Qualcomm Atheros      | 5         | 16.67%  |
| Realtek Semiconductor | 4         | 13.33%  |
| Broadcom              | 3         | 10%     |
| TP-Link               | 1         | 3.33%   |
| Ralink Technology     | 1         | 3.33%   |
| D-Link                | 1         | 3.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 6.67%   |
| Intel Wireless 8265 / 8275                                              | 2         | 6.67%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 6.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 6.67%   |
| TP-Link Wireless USB Adapter                                            | 1         | 3.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 3.33%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                      | 1         | 3.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 3.33%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 3.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 1         | 3.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 3.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 3.33%   |
| Intel Wireless 8260                                                     | 1         | 3.33%   |
| Intel Wireless 7260                                                     | 1         | 3.33%   |
| Intel WiFi Link 5100                                                    | 1         | 3.33%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 3.33%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 3.33%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 1         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 3.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 3.33%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]    | 1         | 3.33%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                      | 1         | 3.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 3.33%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 3.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 9         | 40.91%  |
| Realtek Semiconductor    | 5         | 22.73%  |
| Broadcom                 | 3         | 13.64%  |
| Samsung Electronics      | 2         | 9.09%   |
| Qualcomm Atheros         | 1         | 4.55%   |
| Marvell Technology Group | 1         | 4.55%   |
| Apple                    | 1         | 4.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 18.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 18.18%  |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 4.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 4.55%   |
| Intel Ethernet Controller I219-V                                  | 1         | 4.55%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.55%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 4.55%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 4.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 4.55%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 4.55%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 4.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 4.55%   |
| Apple Ethernet Adapter [A1277]                                    | 1         | 4.55%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 26        | 53.06%  |
| Ethernet | 21        | 42.86%  |
| Unknown  | 2         | 4.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 12        | 54.55%  |
| Ethernet | 10        | 45.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 18        | 72%     |
| 1     | 7         | 28%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 92%     |
| Yes  | 2         | 8%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 62.5%   |
| Broadcom              | 3         | 18.75%  |
| Realtek Semiconductor | 2         | 12.5%   |
| Apple                 | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 4         | 25%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2         | 12.5%   |
| Intel AX201 Bluetooth                          | 2         | 12.5%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter        | 1         | 6.25%   |
| Realtek RTL8723B Bluetooth                     | 1         | 6.25%   |
| Intel Wireless Bluetooth                       | 1         | 6.25%   |
| Intel AX200 Bluetooth                          | 1         | 6.25%   |
| Broadcom Bluetooth 2.1 Device                  | 1         | 6.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 6.25%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 6.25%   |
| Apple Bluetooth Host Controller                | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 22        | 81.48%  |
| Nvidia | 3         | 11.11%  |
| AMD    | 2         | 7.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 12.5%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 9.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 6.25%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 6.25%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 6.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 6.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 6.25%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 6.25%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 3.13%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 3.13%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 3.13%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 3.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1         | 3.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 3.13%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1         | 3.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 29.03%  |
| SK hynix            | 7         | 22.58%  |
| Micron Technology   | 4         | 12.9%   |
| Kingston            | 3         | 9.68%   |
| Unknown             | 3         | 9.68%   |
| Unknown             | 1         | 3.23%   |
| Ramaxel Technology  | 1         | 3.23%   |
| Nanya Technology    | 1         | 3.23%   |
| A-DATA Technology   | 1         | 3.23%   |
| 48spaces            | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                   | 3         | 8.82%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 5.88%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 1         | 2.94%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 1         | 2.94%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 2.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.94%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 1         | 2.94%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 2.94%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 2.94%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 2.94%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s                          | 1         | 2.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 2.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.94%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 1         | 2.94%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.94%   |
| Samsung RAM M425R1GB4DB0-CWMOL 16GB SODIMM DDR5 5600MT/s                  | 1         | 2.94%   |
| Samsung RAM M4 70T5663RZ3-CF7 2GB SODIMM SDRAM 1639MT/s                   | 1         | 2.94%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 2.94%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 2.94%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.94%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 667MT/s                       | 1         | 2.94%   |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                              | 1         | 2.94%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s                        | 1         | 2.94%   |
| Micron RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                        | 1         | 2.94%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 1         | 2.94%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 2400MT/s                   | 1         | 2.94%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s                   | 1         | 2.94%   |
| Kingston RAM 9905428-105.A00G 8GB SODIMM DDR3 1333MT/s                    | 1         | 2.94%   |
| A-DATA RAM MIOVE1B163BZ 2GB SODIMM SDRAM 1639MT/s                         | 1         | 2.94%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 9         | 34.62%  |
| DDR4   | 7         | 26.92%  |
| LPDDR3 | 3         | 11.54%  |
| DDR2   | 3         | 11.54%  |
| SDRAM  | 1         | 3.85%   |
| LPDDR5 | 1         | 3.85%   |
| LPDDR4 | 1         | 3.85%   |
| DDR5   | 1         | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 21        | 84%     |
| Row Of Chips | 4         | 16%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 9         | 30%     |
| 4096  | 9         | 30%     |
| 2048  | 9         | 30%     |
| 16384 | 3         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 5         | 18.52%  |
| 1600  | 5         | 18.52%  |
| 667   | 3         | 11.11%  |
| 2400  | 2         | 7.41%   |
| 2133  | 2         | 7.41%   |
| 1067  | 2         | 7.41%   |
| 6400  | 1         | 3.7%    |
| 5600  | 1         | 3.7%    |
| 4267  | 1         | 3.7%    |
| 1867  | 1         | 3.7%    |
| 1639  | 1         | 3.7%    |
| 1334  | 1         | 3.7%    |
| 1333  | 1         | 3.7%    |
| 400   | 1         | 3.7%    |

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
| Chicony Electronics           | 5         | 26.32%  |
| IMC Networks                  | 3         | 15.79%  |
| Bison Electronics             | 3         | 15.79%  |
| Suyin                         | 2         | 10.53%  |
| Realtek Semiconductor         | 2         | 10.53%  |
| Z-Star Microelectronics       | 1         | 5.26%   |
| Sunplus Innovation Technology | 1         | 5.26%   |
| Microdia                      | 1         | 5.26%   |
| Luxvisions Innotech Limited   | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Bison SunplusIT Integrated Camera                           | 2         | 10.53%  |
| Z-Star Webcam                                               | 1         | 5.26%   |
| Suyin HD Video WebCam                                       | 1         | 5.26%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 5.26%   |
| Sunplus Hy HD Camera                                        | 1         | 5.26%   |
| Realtek Lenovo EasyCamera                                   | 1         | 5.26%   |
| Realtek Integrated_Webcam_HD                                | 1         | 5.26%   |
| Microdia Integrated Webcam                                  | 1         | 5.26%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 5.26%   |
| IMC Networks UVC VGA Webcam                                 | 1         | 5.26%   |
| IMC Networks Integrated Camera                              | 1         | 5.26%   |
| IMC Networks EasyCamera                                     | 1         | 5.26%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 1         | 5.26%   |
| Chicony Integrated Camera                                   | 1         | 5.26%   |
| Chicony HD WebCam                                           | 1         | 5.26%   |
| Chicony FJ Camera                                           | 1         | 5.26%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 1         | 5.26%   |
| Bison ThinkPad Integrated Camera                            | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Upek                       | 2         | 28.57%  |
| LighTuning Technology      | 2         | 28.57%  |
| Validity Sensors           | 1         | 14.29%  |
| Synaptics                  | 1         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 28.57%  |
| Validity Sensors Synaptics WBDI                        | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 14.29%  |
| LighTuning Fingerprint Reader                          | 1         | 14.29%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 14.29%  |

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
| 2     | 8         | 32%     |
| 1     | 7         | 28%     |
| 0     | 4         | 16%     |
| 4     | 3         | 12%     |
| 3     | 3         | 12%     |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 18        | 40.91%  |
| Bluetooth                | 8         | 18.18%  |
| Net/wireless             | 7         | 15.91%  |
| Fingerprint reader       | 6         | 13.64%  |
| Firewire controller      | 2         | 4.55%   |
| Card reader              | 2         | 4.55%   |
| Net/ethernet             | 1         | 2.27%   |

