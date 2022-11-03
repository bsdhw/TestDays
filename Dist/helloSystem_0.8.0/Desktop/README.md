helloSystem 0.8.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.0.

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

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo    | 3106 SDK0J40705 WIN 3425... | [d20bfb6d64](https://bsd-hardware.info/?probe=d20bfb6d64) | Oct 30, 2022 |
| HP        | 843B                        | [d7d572f9ad](https://bsd-hardware.info/?probe=d7d572f9ad) | Oct 29, 2022 |
| HP        | 843B                        | [9ea2590610](https://bsd-hardware.info/?probe=9ea2590610) | Oct 23, 2022 |
| MSI       | B450M PRO-VDH PLUS          | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| HP        | 86FC MVB                    | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP        | 86FC MVB                    | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| Dell      | 0T10XW A01                  | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| ASRock    | ConRoeXFire-eSATA2          | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| ASUSTek   | ROG STRIX B550-I GAMING     | [079adb24f8](https://bsd-hardware.info/?probe=079adb24f8) | Aug 28, 2022 |
| ASUSTek   | P5QL-ASUS-SE                | [50a0d392e7](https://bsd-hardware.info/?probe=50a0d392e7) | Aug 06, 2022 |
| ASUSTek   | K30AM-J                     | [470ced8f30](https://bsd-hardware.info/?probe=470ced8f30) | Aug 05, 2022 |
| MSI       | MPG X570 GAMING PLUS        | [a80b1c4f3c](https://bsd-hardware.info/?probe=a80b1c4f3c) | Jul 17, 2022 |
| HP        | 1998                        | [e4fda48283](https://bsd-hardware.info/?probe=e4fda48283) | Jul 15, 2022 |
| Pegatron  | IPM41-D3                    | [8b2af1b843](https://bsd-hardware.info/?probe=8b2af1b843) | Jul 06, 2022 |
| Biostar   | G41D3C                      | [118bd083bf](https://bsd-hardware.info/?probe=118bd083bf) | Jul 01, 2022 |
| ASUSTek   | K30AM-J                     | [f4352f7897](https://bsd-hardware.info/?probe=f4352f7897) | May 16, 2022 |
| Lenovo    | 30D9 SDK0J40705 WIN 3425... | [964ceb3616](https://bsd-hardware.info/?probe=964ceb3616) | Apr 03, 2022 |
| MSI       | B350M BAZOOKA               | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| ASRock    | G41C-VS                     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel     | DN2800MT AAG23738-600       | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| ASUSTek   | TUF GAMING X570-PLUS        | [64999a24c1](https://bsd-hardware.info/?probe=64999a24c1) | Feb 16, 2022 |
| AMD       | X64                         | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| Lenovo    | SHARKBAY SDK0E50510 WIN     | [eddeb5c246](https://bsd-hardware.info/?probe=eddeb5c246) | Feb 13, 2022 |
| MACHINIST | X99-k9 V2.0                 | [0a36d71db1](https://bsd-hardware.info/?probe=0a36d71db1) | Feb 10, 2022 |
| Pegatron  | IPPPV-D3G                   | [d5e44ccf6b](https://bsd-hardware.info/?probe=d5e44ccf6b) | Jan 28, 2022 |
| Intel     | MAHOBAY                     | [2036093b68](https://bsd-hardware.info/?probe=2036093b68) | Jan 25, 2022 |
| HP        | 8648                        | [b0adf55067](https://bsd-hardware.info/?probe=b0adf55067) | Jan 23, 2022 |
| Dell      | 0593VH A00                  | [484d14dbef](https://bsd-hardware.info/?probe=484d14dbef) | Jan 22, 2022 |
| ASRock    | B365M Pro4                  | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| Dell      | 0YF8P5 A00                  | [913b2a7483](https://bsd-hardware.info/?probe=913b2a7483) | Jan 18, 2022 |
| Dell      | 0X4N41 A01                  | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 28       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 28       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 28       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 28       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 28       | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 27       | 96.43%  |
| BIOS | 1        | 3.57%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 17       | 58.62%  |
| Zfs    | 12       | 41.38%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 27       | 96.43%  |
| MBR  | 1        | 3.57%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Hewlett-Packard  | 4        | 14.29%  |
| Dell             | 4        | 14.29%  |
| ASUSTek Computer | 4        | 14.29%  |
| MSI              | 3        | 10.71%  |
| Lenovo           | 3        | 10.71%  |
| ASRock           | 3        | 10.71%  |
| Pegatron         | 2        | 7.14%   |
| Intel            | 2        | 7.14%   |
| MACHINIST        | 1        | 3.57%   |
| Biostar          | 1        | 3.57%   |
| AMD              | 1        | 3.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7A38                         | 2        | 7.14%   |
| Pegatron IPPPV-D3G                  | 1        | 3.57%   |
| Pegatron IPM41-D3                   | 1        | 3.57%   |
| MSI MS-7C37                         | 1        | 3.57%   |
| MACHINIST X99-k9 V2.0               | 1        | 3.57%   |
| Lenovo ThinkCentre M93p 10AAA0WGUK  | 1        | 3.57%   |
| Lenovo ThinkCentre M910s 10MK0039US | 1        | 3.57%   |
| Lenovo ThinkCentre M700 10GS        | 1        | 3.57%   |
| Intel MAHOBAY                       | 1        | 3.57%   |
| Intel DN2800MT AAG23738-600         | 1        | 3.57%   |
| HP Slim Desktop S01-aF1xxx          | 1        | 3.57%   |
| HP Pavilion Desktop 590-p0xxx       | 1        | 3.57%   |
| HP EliteDesk 800 G1 SFF             | 1        | 3.57%   |
| HP Desktop Pro A G3                 | 1        | 3.57%   |
| Dell Precision 3440                 | 1        | 3.57%   |
| Dell OptiPlex 3010                  | 1        | 3.57%   |
| Dell Inspiron 3891                  | 1        | 3.57%   |
| Dell Inspiron 3656                  | 1        | 3.57%   |
| Biostar G41D3C                      | 1        | 3.57%   |
| ASUS TUF GAMING X570-PLUS           | 1        | 3.57%   |
| ASUS ROG STRIX B550-I GAMING        | 1        | 3.57%   |
| ASUS P5QL-ASUS-SE                   | 1        | 3.57%   |
| ASUS K30AM-J                        | 1        | 3.57%   |
| ASRock G41C-VS                      | 1        | 3.57%   |
| ASRock ConRoeXFire-eSATA2           | 1        | 3.57%   |
| ASRock B365M Pro4                   | 1        | 3.57%   |
| AMD X64                             | 1        | 3.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| Lenovo ThinkCentre        | 3        | 10.71%  |
| MSI MS-7A38               | 2        | 7.14%   |
| Dell Inspiron             | 2        | 7.14%   |
| Pegatron IPPPV-D3G        | 1        | 3.57%   |
| Pegatron IPM41-D3         | 1        | 3.57%   |
| MSI MS-7C37               | 1        | 3.57%   |
| MACHINIST X99-k9          | 1        | 3.57%   |
| Intel MAHOBAY             | 1        | 3.57%   |
| Intel DN2800MT            | 1        | 3.57%   |
| HP Slim                   | 1        | 3.57%   |
| HP Pavilion               | 1        | 3.57%   |
| HP EliteDesk              | 1        | 3.57%   |
| HP Desktop                | 1        | 3.57%   |
| Dell Precision            | 1        | 3.57%   |
| Dell OptiPlex             | 1        | 3.57%   |
| Biostar G41D3C            | 1        | 3.57%   |
| ASUS TUF                  | 1        | 3.57%   |
| ASUS ROG                  | 1        | 3.57%   |
| ASUS P5QL-ASUS-SE         | 1        | 3.57%   |
| ASUS K30AM-J              | 1        | 3.57%   |
| ASRock G41C-VS            | 1        | 3.57%   |
| ASRock ConRoeXFire-eSATA2 | 1        | 3.57%   |
| ASRock B365M              | 1        | 3.57%   |
| AMD X64                   | 1        | 3.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 4        | 14.29%  |
| 2020 | 3        | 10.71%  |
| 2018 | 3        | 10.71%  |
| 2010 | 3        | 10.71%  |
| 2022 | 2        | 7.14%   |
| 2019 | 2        | 7.14%   |
| 2015 | 2        | 7.14%   |
| 2014 | 2        | 7.14%   |
| 2013 | 2        | 7.14%   |
| 2011 | 2        | 7.14%   |
| 2009 | 2        | 7.14%   |
| 2012 | 1        | 3.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 28       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 28       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 16.01-24.0 | 11       | 39.29%  |
| 4.01-8.0   | 7        | 25%     |
| 8.01-16.0  | 5        | 17.86%  |
| 2.01-3.0   | 3        | 10.71%  |
| 32.01-64.0 | 2        | 7.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 11       | 39.29%  |
| 0.01-0.5 | 9        | 32.14%  |
| 1.01-2.0 | 6        | 21.43%  |
| 4.01-8.0 | 1        | 3.57%   |
| 2.01-3.0 | 1        | 3.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 55.17%  |
| 2      | 8        | 27.59%  |
| 3      | 2        | 6.9%    |
| 6      | 1        | 3.45%   |
| 5      | 1        | 3.45%   |
| 4      | 1        | 3.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 21       | 75%     |
| Yes       | 7        | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 58.62%  |
| Yes       | 12       | 41.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 19       | 67.86%  |
| Yes       | 9        | 32.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 5        | 17.86%  |
| Russia       | 5        | 17.86%  |
| Brazil       | 3        | 10.71%  |
| Spain        | 2        | 7.14%   |
| Poland       | 2        | 7.14%   |
| France       | 2        | 7.14%   |
| UK           | 1        | 3.57%   |
| South Africa | 1        | 3.57%   |
| Serbia       | 1        | 3.57%   |
| Norway       | 1        | 3.57%   |
| Mexico       | 1        | 3.57%   |
| India        | 1        | 3.57%   |
| Germany      | 1        | 3.57%   |
| China        | 1        | 3.57%   |
| Canada       | 1        | 3.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Volgograd           | 2        | 6.9%    |
| Temple              | 2        | 6.9%    |
| Moscow              | 2        | 6.9%    |
| Zhengzhou           | 1        | 3.45%   |
| Voronezh            | 1        | 3.45%   |
| Surrey              | 1        | 3.45%   |
| Southminster        | 1        | 3.45%   |
| Salisbury           | 1        | 3.45%   |
| Reinsvoll           | 1        | 3.45%   |
| Munich              | 1        | 3.45%   |
| Monterrey           | 1        | 3.45%   |
| Medford             | 1        | 3.45%   |
| Londrina            | 1        | 3.45%   |
| LogroÃ±o          | 1        | 3.45%   |
| Katowice            | 1        | 3.45%   |
| Jedlicze            | 1        | 3.45%   |
| Guadalupe           | 1        | 3.45%   |
| Escondido           | 1        | 3.45%   |
| Curitiba            | 1        | 3.45%   |
| Cournon-d'Auvergne  | 1        | 3.45%   |
| Chennai             | 1        | 3.45%   |
| Chatou              | 1        | 3.45%   |
| Brasília           | 1        | 3.45%   |
| Bloemfontein        | 1        | 3.45%   |
| Belgrade            | 1        | 3.45%   |
| Alcalá de Guadaira | 1        | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 12     | 19.57%  |
| Samsung Electronics | 6        | 6      | 13.04%  |
| WDC                 | 5        | 7      | 10.87%  |
| Hitachi             | 5        | 5      | 10.87%  |
| Toshiba             | 4        | 4      | 8.7%    |
| Kingston            | 3        | 3      | 6.52%   |
| SPCC                | 2        | 2      | 4.35%   |
| SK hynix            | 1        | 1      | 2.17%   |
| SanDisk             | 1        | 2      | 2.17%   |
| PNY                 | 1        | 1      | 2.17%   |
| OCZ                 | 1        | 1      | 2.17%   |
| Lexar               | 1        | 2      | 2.17%   |
| LDLC                | 1        | 1      | 2.17%   |
| KingSpec            | 1        | 1      | 2.17%   |
| Intenso             | 1        | 1      | 2.17%   |
| Hewlett-Packard     | 1        | 1      | 2.17%   |
| Gigabyte Technology | 1        | 1      | 2.17%   |
| Crucial             | 1        | 1      | 2.17%   |
| Corsair             | 1        | 1      | 2.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Toshiba MQ01ABD050 500GB         | 2        | 3.85%   |
| WDC WDS500G2X0C-00L350 500GB     | 1        | 1.92%   |
| WDC WDS500G2B0A 500GB            | 1        | 1.92%   |
| WDC WDS500G1B0C-00S6U0 500GB     | 1        | 1.92%   |
| WDC WD5000AZLX-60K2TA1 500GB     | 1        | 1.92%   |
| WDC WD5000AVVS-63H0B1 500GB      | 1        | 1.92%   |
| WDC WD3003FZEX-00Z4SA0 3TB       | 1        | 1.92%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1        | 1.92%   |
| Toshiba TR200 480GB              | 1        | 1.92%   |
| Toshiba DT01ACA100 1TB           | 1        | 1.92%   |
| SPCC Solid State Disk 56GB       | 1        | 1.92%   |
| SPCC Solid State Disk 512GB      | 1        | 1.92%   |
| SK hynix BC711 NVMe 256GB        | 1        | 1.92%   |
| Seagate ST9120821AS 118GB        | 1        | 1.92%   |
| Seagate ST4000DM004-2CV104 4TB   | 1        | 1.92%   |
| Seagate ST3250310AS 250GB        | 1        | 1.92%   |
| Seagate ST3160811AS 160GB        | 1        | 1.92%   |
| Seagate ST3000DM001-1CH166 3TB   | 1        | 1.92%   |
| Seagate ST250LT003-9YG14C 250GB  | 1        | 1.92%   |
| Seagate ST2000DM008-2FR102 2TB   | 1        | 1.92%   |
| Seagate ST2000DL003-9VT166 2TB   | 1        | 1.92%   |
| Seagate ST1000VX001-1Z4102 1TB   | 1        | 1.92%   |
| Seagate ST1000LM035-1RK172 1TB   | 1        | 1.92%   |
| Seagate ST1000DM010-2EP102 1TB   | 1        | 1.92%   |
| Seagate ST1000DM003-1ER162 1TB   | 1        | 1.92%   |
| SanDisk SDSA5GK-016G-1006 16GB   | 1        | 1.92%   |
| Samsung SSD 860 PRO 512GB        | 1        | 1.92%   |
| Samsung SSD 860 EVO 250GB        | 1        | 1.92%   |
| Samsung SP0812C 80GB             | 1        | 1.92%   |
| Samsung MZVLQ512HALU-000H1 512GB | 1        | 1.92%   |
| Samsung MZNLN128HAHQ-000H1 128GB | 1        | 1.92%   |
| Samsung HD501LJ 500GB            | 1        | 1.92%   |
| PNY CS900 500GB SSD              | 1        | 1.92%   |
| OCZ VERTEX3 240GB                | 1        | 1.92%   |
| Lexar 256GB SSD                  | 1        | 1.92%   |
| Lexar 250GB SSD                  | 1        | 1.92%   |
| LDLC F8+M.2 240 240GB            | 1        | 1.92%   |
| Kingston SV300S37A120G 120GB     | 1        | 1.92%   |
| Kingston SA2000M8500G 500GB      | 1        | 1.92%   |
| Kingston OM8SBP3512K-AH 512GB    | 1        | 1.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 12     | 37.5%   |
| Hitachi             | 5        | 5      | 20.83%  |
| WDC                 | 4        | 4      | 16.67%  |
| Toshiba             | 3        | 3      | 12.5%   |
| Samsung Electronics | 2        | 2      | 8.33%   |
| Hewlett-Packard     | 1        | 1      | 4.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 20%     |
| SPCC                | 2        | 2      | 13.33%  |
| WDC                 | 1        | 1      | 6.67%   |
| Toshiba             | 1        | 1      | 6.67%   |
| SanDisk             | 1        | 2      | 6.67%   |
| PNY                 | 1        | 1      | 6.67%   |
| OCZ                 | 1        | 1      | 6.67%   |
| Lexar               | 1        | 1      | 6.67%   |
| Kingston            | 1        | 1      | 6.67%   |
| KingSpec            | 1        | 1      | 6.67%   |
| Intenso             | 1        | 1      | 6.67%   |
| Gigabyte Technology | 1        | 1      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 27     | 45.24%  |
| SSD  | 14       | 16     | 33.33%  |
| NVMe | 9        | 10     | 21.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 27       | 43     | 75%     |
| NVMe | 9        | 10     | 25%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 29     | 63.64%  |
| 0.51-1.0   | 7        | 8      | 21.21%  |
| 1.01-2.0   | 3        | 3      | 9.09%   |
| 3.01-4.0   | 1        | 1      | 3.03%   |
| 2.01-3.0   | 1        | 2      | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 15       | 53.57%  |
| 251-500    | 6        | 21.43%  |
| 101-250    | 4        | 14.29%  |
| 1001-2000  | 2        | 7.14%   |
| 51-100     | 1        | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 26       | 92.86%  |
| 101-250  | 1        | 3.57%   |
| 501-1000 | 1        | 3.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD5000AVVS-63H0B1 500GB       | 1        | 1      | 20%     |
| Samsung Electronics HD501LJ 500GB | 1        | 1      | 20%     |
| OCZ VERTEX3 240GB                 | 1        | 1      | 20%     |
| Hitachi HTS545050A7E380 500GB     | 1        | 1      | 20%     |
| Hitachi HTS541680J9SA00 80GB      | 1        | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Hitachi             | 2        | 2      | 40%     |
| WDC                 | 1        | 1      | 20%     |
| Samsung Electronics | 1        | 1      | 20%     |
| OCZ                 | 1        | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Hitachi             | 2        | 2      | 50%     |
| WDC                 | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 4      | 80%     |
| SSD  | 1        | 1      | 20%     |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 24       | 43     | 80%     |
| Malfunc  | 4        | 5      | 13.33%  |
| Detected | 2        | 5      | 6.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 20       | 47.62%  |
| AMD                          | 8        | 19.05%  |
| SanDisk                      | 2        | 4.76%   |
| Kingston Technology Company  | 2        | 4.76%   |
| JMicron Technology           | 2        | 4.76%   |
| SK hynix                     | 1        | 2.38%   |
| Silicon Motion               | 1        | 2.38%   |
| Shenzhen Longsys Electronics | 1        | 2.38%   |
| Samsung Electronics          | 1        | 2.38%   |
| Phison Electronics           | 1        | 2.38%   |
| Micron/Crucial Technology    | 1        | 2.38%   |
| Marvell Technology Group     | 1        | 2.38%   |
| ASMedia Technology           | 1        | 2.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 6        | 12.5%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 6.25%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3        | 6.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 4.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 4.17%   |
| SK hynix Gold P31 SSD                                                          | 1        | 2.08%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1        | 2.08%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                               | 1        | 2.08%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1        | 2.08%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 2.08%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 2.08%   |
| Phison E12 NVMe Controller                                                     | 1        | 2.08%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 2.08%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 1        | 2.08%   |
| Kingston Company A2000 NVMe SSD                                                | 1        | 2.08%   |
| JMicron JMB368 IDE controller                                                  | 1        | 2.08%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1        | 2.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.08%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 2.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 2.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 2.08%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1        | 2.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1        | 2.08%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 2.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.08%   |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]  | 1        | 2.08%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 2.08%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 2.08%   |
| AMD FCH SATA Controller [IDE mode]                                             | 1        | 2.08%   |
| AMD FCH IDE Controller                                                         | 1        | 2.08%   |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 2.08%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.08%   |
| AMD 300 Series Chipset SATA Controller                                         | 1        | 2.08%   |
| Unknown                                                                        | 1        | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 23       | 57.5%   |
| NVMe | 9        | 22.5%   |
| IDE  | 8        | 20%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 71.43%  |
| AMD    | 8        | 28.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Xeon CPU E5-2630L v4 @ 1.80GHz            | 1        | 3.57%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz        | 1        | 3.57%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz     | 1        | 3.57%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz     | 1        | 3.57%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz     | 1        | 3.57%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz     | 1        | 3.57%   |
| Intel Pentium CPU G4400 @ 3.30GHz               | 1        | 3.57%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1        | 3.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 1        | 3.57%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 1        | 3.57%   |
| Intel Core i5-4570T CPU @ 2.90GHz               | 1        | 3.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 1        | 3.57%   |
| Intel Core i3-8100 CPU @ 3.60GHz                | 1        | 3.57%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 1        | 3.57%   |
| Intel Core i3-10100 CPU @ 3.60GHz               | 1        | 3.57%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 1        | 3.57%   |
| Intel Celeron CPU J1800 @ 2.41GHz               | 1        | 3.57%   |
| Intel Atom CPU N2800 @ 1.86GHz                  | 1        | 3.57%   |
| Intel Atom CPU D425 @ 1.80GHz                   | 1        | 3.57%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz          | 1        | 3.57%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1        | 3.57%   |
| AMD Ryzen 5 PRO 3400G with Radeon Vega Graphics | 1        | 3.57%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 3.57%   |
| AMD Ryzen 5 3600X 6-Core Processor              | 1        | 3.57%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 3.57%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 1        | 3.57%   |
| AMD RX-8120 Processor                           | 1        | 3.57%   |
| AMD FX-8800P Radeon R7, 12 Compute Cores 4C+8G  | 1        | 3.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Pentium Dual-Core | 4        | 14.29%  |
| AMD Ryzen 5             | 4        | 14.29%  |
| Intel Core i5           | 3        | 10.71%  |
| Intel Core i3           | 3        | 10.71%  |
| Other                   | 2        | 7.14%   |
| Intel Core i7           | 2        | 7.14%   |
| Intel Atom              | 2        | 7.14%   |
| Intel Xeon              | 1        | 3.57%   |
| Intel Pentium Silver    | 1        | 3.57%   |
| Intel Pentium           | 1        | 3.57%   |
| Intel Core 2 Quad       | 1        | 3.57%   |
| Intel Celeron           | 1        | 3.57%   |
| AMD Ryzen 9             | 1        | 3.57%   |
| AMD Ryzen 5 PRO         | 1        | 3.57%   |
| AMD FX                  | 1        | 3.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 8        | 28.57%  |
| 2       | 8        | 28.57%  |
| 8       | 4        | 14.29%  |
| 12      | 3        | 10.71%  |
| 24      | 1        | 3.57%   |
| 10      | 1        | 3.57%   |
| 6       | 1        | 3.57%   |
| 1       | 1        | 3.57%   |
| Unknown | 1        | 3.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 28       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 20       | 71.43%  |
| 2       | 7        | 25%     |
| Unknown | 1        | 3.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 4        | 14.29%  |
| Zen+          | 2        | 7.14%   |
| Zen 2         | 2        | 7.14%   |
| Skylake       | 2        | 7.14%   |
| KabyLake      | 2        | 7.14%   |
| IvyBridge     | 2        | 7.14%   |
| Haswell       | 2        | 7.14%   |
| Bonnell       | 2        | 7.14%   |
| Unknown       | 2        | 7.14%   |
| Zen 3         | 1        | 3.57%   |
| Zen           | 1        | 3.57%   |
| Silvermont    | 1        | 3.57%   |
| Goldmont plus | 1        | 3.57%   |
| Excavator     | 1        | 3.57%   |
| Core          | 1        | 3.57%   |
| CometLake     | 1        | 3.57%   |
| Broadwell     | 1        | 3.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 13       | 44.83%  |
| Nvidia | 9        | 31.03%  |
| AMD    | 7        | 24.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 6.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2        | 6.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 6.9%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 3.45%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 3.45%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 3.45%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 3.45%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1        | 3.45%   |
| Nvidia G84 [GeForce 8600 GTS]                                               | 1        | 3.45%   |
| Nvidia G73 [GeForce 7600 GS]                                                | 1        | 3.45%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1        | 3.45%   |
| Intel HD Graphics 530                                                       | 1        | 3.45%   |
| Intel HD Graphics 510                                                       | 1        | 3.45%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1        | 3.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 3.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 3.45%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 1        | 3.45%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller             | 1        | 3.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 3.45%   |
| AMD Tobago PRO [Radeon R7 360 / R9 360 OEM]                                 | 1        | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 3.45%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 1        | 3.45%   |
| AMD Kryptos [Radeon RX 350]                                                 | 1        | 3.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 1        | 3.45%   |
| AMD Cezanne                                                                 | 1        | 3.45%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 1        | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 11       | 39.29%  |
| 1 x Nvidia  | 9        | 32.14%  |
| 1 x AMD     | 6        | 21.43%  |
| 2 x Intel   | 1        | 3.57%   |
| Intel + AMD | 1        | 3.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 17       | 60.71%  |
| Proprietary | 8        | 28.57%  |
| Unknown     | 3        | 10.71%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 15       | 53.57%  |
| 1.01-2.0   | 4        | 14.29%  |
| 5.01-6.0   | 3        | 10.71%  |
| 3.01-4.0   | 2        | 7.14%   |
| 0.51-1.0   | 2        | 7.14%   |
| 7.01-8.0   | 1        | 3.57%   |
| 0.01-0.5   | 1        | 3.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Goldstar            | 4        | 18.18%  |
| Dell                | 4        | 18.18%  |
| MSI                 | 3        | 13.64%  |
| Samsung Electronics | 2        | 9.09%   |
| AOC                 | 2        | 9.09%   |
| Vizio               | 1        | 4.55%   |
| Toshiba             | 1        | 4.55%   |
| Philips             | 1        | 4.55%   |
| Insignia            | 1        | 4.55%   |
| Iiyama              | 1        | 4.55%   |
| Hewlett-Packard     | 1        | 4.55%   |
| Acer                | 1        | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                      | 2        | 8.7%    |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                   | 1        | 4.35%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                    | 1        | 4.35%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                      | 1        | 4.35%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch  | 1        | 4.35%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch | 1        | 4.35%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch              | 1        | 4.35%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 790x330mm 33.7-inch                 | 1        | 4.35%   |
| Insignia 32DR310NA17 BBY3253 1680x1050 700x390mm 31.5-inch           | 1        | 4.35%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch              | 1        | 4.35%   |
| Hewlett-Packard 27xi HWP3038 1920x1080 600x340mm 27.2-inch           | 1        | 4.35%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch          | 1        | 4.35%   |
| Goldstar L1918S GSM4B31 1280x1024 380x300mm 19.1-inch                | 1        | 4.35%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch          | 1        | 4.35%   |
| Goldstar 22MP55 GSM5A24 1920x1080 480x270mm 21.7-inch                | 1        | 4.35%   |
| Dell S2316H DELD07E 1920x1080 510x290mm 23.1-inch                    | 1        | 4.35%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                   | 1        | 4.35%   |
| Dell E2216HV DELF06F 1920x1080 480x270mm 21.7-inch                   | 1        | 4.35%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                     | 1        | 4.35%   |
| AOC Q2577W AOC2577 2560x1440 550x310mm 24.9-inch                     | 1        | 4.35%   |
| AOC 2481W AOC2481 1920x1080 530x300mm 24.0-inch                      | 1        | 4.35%   |
| Acer GN246HL ACR02FA 1920x1080 530x300mm 24.0-inch                   | 1        | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 14       | 63.64%  |
| 3440x1440          | 2        | 9.09%   |
| 1680x1050 (WSXGA+) | 2        | 9.09%   |
| 2560x1440 (QHD)    | 1        | 4.55%   |
| 1600x900 (HD+)     | 1        | 4.55%   |
| 1366x768 (WXGA)    | 1        | 4.55%   |
| 1280x1024 (SXGA)   | 1        | 4.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 4        | 17.39%  |
| 31      | 3        | 13.04%  |
| 24      | 3        | 13.04%  |
| 21      | 3        | 13.04%  |
| 19      | 2        | 8.7%    |
| 50      | 1        | 4.35%   |
| 41      | 1        | 4.35%   |
| 34      | 1        | 4.35%   |
| 33      | 1        | 4.35%   |
| 27      | 1        | 4.35%   |
| 22      | 1        | 4.35%   |
| 18      | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 8        | 34.78%  |
| 401-500     | 6        | 26.09%  |
| 601-700     | 3        | 13.04%  |
| 701-800     | 2        | 8.7%    |
| 351-400     | 1        | 4.35%   |
| 1001-1500   | 1        | 4.35%   |
| 901-1000    | 1        | 4.35%   |
| Unknown     | 1        | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 18       | 81.82%  |
| 21/9  | 2        | 9.09%   |
| 5/4   | 1        | 4.55%   |
| 16/10 | 1        | 4.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 10       | 43.48%  |
| 351-500        | 5        | 21.74%  |
| 151-200        | 2        | 8.7%    |
| More than 1000 | 1        | 4.35%   |
| 301-350        | 1        | 4.35%   |
| 251-300        | 1        | 4.35%   |
| 141-150        | 1        | 4.35%   |
| 501-1000       | 1        | 4.35%   |
| Unknown        | 1        | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 15       | 65.22%  |
| 101-120 | 6        | 26.09%  |
| 1-50    | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 22       | 78.57%  |
| 0     | 5        | 17.86%  |
| 2     | 1        | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 18       | 51.43%  |
| Intel                 | 10       | 28.57%  |
| Qualcomm Atheros      | 2        | 5.71%   |
| Ralink Technology     | 1        | 2.86%   |
| IMC Networks          | 1        | 2.86%   |
| Edimax Technology     | 1        | 2.86%   |
| Broadcom              | 1        | 2.86%   |
| ASUSTek Computer      | 1        | 2.86%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 18       | 43.9%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 4.88%   |
| Intel Wi-Fi 6 AX200                                                         | 2        | 4.88%   |
| Intel Ethernet Connection I217-LM                                           | 2        | 4.88%   |
| Intel 82574L Gigabit Network Connection                                     | 2        | 4.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 2.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1        | 2.44%   |
| Ralink RT5370 Wireless Adapter                                              | 1        | 2.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                  | 1        | 2.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                       | 1        | 2.44%   |
| Intel Wireless 8265 / 8275                                                  | 1        | 2.44%   |
| Intel Ethernet Controller I225-V                                            | 1        | 2.44%   |
| Intel Ethernet Connection (2) I219-V                                        | 1        | 2.44%   |
| Intel Ethernet Connection (2) I219-LM                                       | 1        | 2.44%   |
| Intel Ethernet Connection (11) I219-LM                                      | 1        | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 1        | 2.44%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 2.44%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1        | 2.44%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1        | 2.44%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 2.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 4        | 33.33%  |
| Intel                 | 3        | 25%     |
| Ralink Technology     | 1        | 8.33%   |
| IMC Networks          | 1        | 8.33%   |
| Edimax Technology     | 1        | 8.33%   |
| Broadcom              | 1        | 8.33%   |
| ASUSTek Computer      | 1        | 8.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2        | 16.67%  |
| Intel Wi-Fi 6 AX200                                                         | 2        | 16.67%  |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 8.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 1        | 8.33%   |
| Ralink RT5370 Wireless Adapter                                              | 1        | 8.33%   |
| Intel Wireless 8265 / 8275                                                  | 1        | 8.33%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 8.33%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1        | 8.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1        | 8.33%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 8.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 18       | 64.29%  |
| Intel                 | 8        | 28.57%  |
| Qualcomm Atheros      | 2        | 7.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 18       | 62.07%  |
| Intel Ethernet Connection I217-LM                                 | 2        | 6.9%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 6.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 3.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1        | 3.45%   |
| Intel Ethernet Controller I225-V                                  | 1        | 3.45%   |
| Intel Ethernet Connection (2) I219-V                              | 1        | 3.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 3.45%   |
| Intel Ethernet Connection (11) I219-LM                            | 1        | 3.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 3.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 71.79%  |
| WiFi     | 11       | 28.21%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 26       | 92.86%  |
| WiFi     | 2        | 7.14%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 20       | 71.43%  |
| 2     | 8        | 28.57%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 96.43%  |
| Yes  | 1        | 3.57%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Realtek Semiconductor   | 3        | 33.33%  |
| Intel                   | 3        | 33.33%  |
| Cambridge Silicon Radio | 1        | 11.11%  |
| Bluetooth Device        | 1        | 11.11%  |
| Apple                   | 1        | 11.11%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Realtek  Bluetooth 4.2 Adapter                           | 2        | 22.22%  |
| Intel AX200 Bluetooth                                    | 2        | 22.22%  |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE              | 1        | 11.11%  |
| Intel Bluetooth wireless interface                       | 1        | 11.11%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 1        | 11.11%  |
| Bluetooth Device Silicon Wave Bluetooth Wireless Adapter | 1        | 11.11%  |
| Apple Apple Broadcom Built-in Bluetooth                  | 1        | 11.11%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 19       | 44.19%  |
| AMD                 | 10       | 23.26%  |
| Nvidia              | 7        | 16.28%  |
| C-Media Electronics | 3        | 6.98%   |
| Google              | 2        | 4.65%   |
| Yamaha              | 1        | 2.33%   |
| Creative Technology | 1        | 2.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6        | 12%     |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 6%      |
| AMD Family 17h/19h HD Audio Controller                                     | 3        | 6%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2        | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 4%      |
| Intel 200 Series PCH HD Audio                                              | 2        | 4%      |
| Google Pixel earbuds                                                       | 2        | 4%      |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 4%      |
| Yamaha Steinberg UR22mkII                                                  | 1        | 2%      |
| Nvidia High Definition Audio Controller                                    | 1        | 2%      |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 2%      |
| Nvidia GM206 High Definition Audio Controller                              | 1        | 2%      |
| Nvidia GK104 HDMI Audio Controller                                         | 1        | 2%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 1        | 2%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1        | 2%      |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2%      |
| Intel C610/X99 series chipset HD Audio Controller                          | 1        | 2%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1        | 2%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2%      |
| Creative Technology Sound BlasterX G1                                      | 1        | 2%      |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1        | 2%      |
| C-Media Electronics Cmedia Audio                                           | 1        | 2%      |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 2%      |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1        | 2%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 2%      |
| AMD Navi 10 HDMI Audio                                                     | 1        | 2%      |
| AMD FCH Azalia Controller                                                  | 1        | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1        | 2%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1        | 2%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1        | 2%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 1        | 2%      |
| Unknown                                                                    | 1        | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 7        | 18.42%  |
| SK hynix            | 6        | 15.79%  |
| Kingston            | 5        | 13.16%  |
| Samsung Electronics | 4        | 10.53%  |
| Micron Technology   | 4        | 10.53%  |
| Crucial             | 4        | 10.53%  |
| Unknown             | 2        | 5.26%   |
| Transcend           | 1        | 2.63%   |
| Ramaxel Technology  | 1        | 2.63%   |
| Patriot             | 1        | 2.63%   |
| GLOWAY              | 1        | 2.63%   |
| Corsair             | 1        | 2.63%   |
| A-DATA Technology   | 1        | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 1GB DIMM SDRAM                       | 2        | 4.88%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s    | 2        | 4.88%   |
| Unknown                                                 | 2        | 4.88%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s             | 1        | 2.44%   |
| Unknown RAM Module 4GB DIMM SDRAM                       | 1        | 2.44%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 1        | 2.44%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s               | 1        | 2.44%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 2.44%   |
| Unknown RAM Module 2GB DIMM DDR2                        | 1        | 2.44%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s    | 1        | 2.44%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 2.44%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s    | 1        | 2.44%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s    | 1        | 2.44%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 2.44%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s             | 1        | 2.44%   |
| Samsung RAM Module 4GB DIMM DDR4 2400MT/s               | 1        | 2.44%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 2.44%   |
| Samsung RAM M378A5143DB0-CPB 4GB DIMM DDR4 2133MT/s     | 1        | 2.44%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB DIMM DDR3 1600MT/s   | 1        | 2.44%   |
| Patriot RAM PSD48G240081 8GB DIMM DDR4 3200MT/s         | 1        | 2.44%   |
| Micron RAM Module 8GB DIMM DDR4 2400MT/s                | 1        | 2.44%   |
| Micron RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s  | 1        | 2.44%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 1        | 2.44%   |
| Micron RAM 4ATF51264AZ-3G2J1 4GB DIMM DDR4 3200MT/s     | 1        | 2.44%   |
| Kingston RAM KHX3200C18D4/16G 16GB DIMM DDR4 3200MT/s   | 1        | 2.44%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 2933MT/s    | 1        | 2.44%   |
| Kingston RAM KHX2666C13/16GX 16GB DIMM DDR4 2667MT/s    | 1        | 2.44%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s     | 1        | 2.44%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 2667MT/s    | 1        | 2.44%   |
| GLOWAY RAM TYA4U2666D19161C 16GB DIMM DDR4 2666MT/s     | 1        | 2.44%   |
| Crucial RAM CT8G4DFD8213.C16FAR1 8GB DIMM DDR4 2133MT/s | 1        | 2.44%   |
| Crucial RAM CT4G4DFS824A.C8FBD2 4GB DIMM DDR4 2133MT/s  | 1        | 2.44%   |
| Crucial RAM CT16G4DFRA266.C8FE 16GB DIMM DDR4 2667MT/s  | 1        | 2.44%   |
| Crucial RAM CB8GU2666.C8JT 8GB DIMM DDR4 2667MT/s       | 1        | 2.44%   |
| Crucial RAM BL8G32C16U4BL.M8FE 8GB DIMM DDR4 2667MT/s   | 1        | 2.44%   |
| Crucial RAM BL8G30C15U4B.M8FE 8GB DIMM DDR4 2666MT/s    | 1        | 2.44%   |
| Corsair RAM CMV4GX4M1A2133C15 4GB DIMM DDR4 2133MT/s    | 1        | 2.44%   |
| A-DATA RAM AM2P26KC4U1-BBOS 4GB DIMM DDR4 2666MT/s      | 1        | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR4  | 14       | 50%     |
| DDR3  | 9        | 32.14%  |
| SDRAM | 3        | 10.71%  |
| DDR2  | 2        | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 25       | 89.29%  |
| SODIMM | 3        | 10.71%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 14       | 35.9%   |
| 8192  | 13       | 33.33%  |
| 2048  | 6        | 15.38%  |
| 16384 | 4        | 10.26%  |
| 1024  | 2        | 5.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 6        | 19.35%  |
| 3200    | 4        | 12.9%   |
| 2667    | 4        | 12.9%   |
| Unknown | 4        | 12.9%   |
| 2400    | 3        | 9.68%   |
| 2133    | 3        | 9.68%   |
| 2666    | 2        | 6.45%   |
| 800     | 2        | 6.45%   |
| 2933    | 1        | 3.23%   |
| 1333    | 1        | 3.23%   |
| 1066    | 1        | 3.23%   |

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
| Z-Star Microelectronics | 1        | 25%     |
| Microdia                | 1        | 25%     |
| Logitech                | 1        | 25%     |
| Arkmicro Technologies   | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| Z-Star Venus USB2.0 Camera  | 1        | 25%     |
| Microdia Camera             | 1        | 25%     |
| Logitech HD Pro Webcam C920 | 1        | 25%     |
| Arkmicro Webcam Carrefour   | 1        | 25%     |

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
| 0     | 13       | 46.43%  |
| 1     | 11       | 39.29%  |
| 2     | 3        | 10.71%  |
| 3     | 1        | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 10       | 52.63%  |
| Net/wireless             | 6        | 31.58%  |
| Sound                    | 1        | 5.26%   |
| Card reader              | 1        | 5.26%   |
| Bluetooth                | 1        | 5.26%   |

