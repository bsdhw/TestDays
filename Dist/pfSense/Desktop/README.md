pfSense - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for pfSense.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

Total: 23

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| PC Engines    | APU2                        | [e56b256787](https://bsd-hardware.info/?probe=e56b256787) | Mar 15, 2022 |
| Intel         | Q3XXG4-P V1.0               | [8bbeb73a52](https://bsd-hardware.info/?probe=8bbeb73a52) | Jan 31, 2022 |
| Intel         | Q3XXG4-P V1.0               | [98ed242ae0](https://bsd-hardware.info/?probe=98ed242ae0) | Jan 01, 2022 |
| Dell          | 06D7TR A02                  | [201ba6cbba](https://bsd-hardware.info/?probe=201ba6cbba) | Nov 04, 2021 |
| Lenovo        | Win8 Pro DPK TPG            | [f57ea5540f](https://bsd-hardware.info/?probe=f57ea5540f) | Oct 13, 2021 |
| ASUSTek       | N3150M-E                    | [289423796b](https://bsd-hardware.info/?probe=289423796b) | Jul 17, 2021 |
| ASUSTek       | N3150M-E                    | [64d08bd493](https://bsd-hardware.info/?probe=64d08bd493) | Jul 17, 2021 |
| PC Engines    | APU                         | [60d7917c9d](https://bsd-hardware.info/?probe=60d7917c9d) | Mar 28, 2021 |
| Dell          | 02YYK5 A00                  | [d4708d5f62](https://bsd-hardware.info/?probe=d4708d5f62) | Mar 07, 2021 |
| Unknown       | YL-J3160L4                  | [47c08e3817](https://bsd-hardware.info/?probe=47c08e3817) | Feb 27, 2021 |
| Protectli     | FW4B Ver                    | [dadf566436](https://bsd-hardware.info/?probe=dadf566436) | Jan 06, 2021 |
| HP            | 18E7                        | [8c4d8cbfc9](https://bsd-hardware.info/?probe=8c4d8cbfc9) | Dec 22, 2020 |
| HP            | 213D A01                    | [623a12f06b](https://bsd-hardware.info/?probe=623a12f06b) | Dec 20, 2020 |
| Supermicro    | X7SPA-HF                    | [84225d9f44](https://bsd-hardware.info/?probe=84225d9f44) | Dec 16, 2020 |
| Netgate       | SG-5100 1                   | [8336fb3a61](https://bsd-hardware.info/?probe=8336fb3a61) | Dec 16, 2020 |
| Unknown       | Unknown                     | [237f10ea9c](https://bsd-hardware.info/?probe=237f10ea9c) | Dec 16, 2020 |
| Dell          | 02YYK5 A00                  | [3fc7c8bb8d](https://bsd-hardware.info/?probe=3fc7c8bb8d) | Nov 01, 2020 |
| TYAN Compu... | Unknown                     | [5ba6da7c5f](https://bsd-hardware.info/?probe=5ba6da7c5f) | Oct 29, 2020 |
| Protectli     | FW2B Ver                    | [4fcfd19048](https://bsd-hardware.info/?probe=4fcfd19048) | Sep 21, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [7e845aab76](https://bsd-hardware.info/?probe=7e845aab76) | Jul 26, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | [7febd3108d](https://bsd-hardware.info/?probe=7febd3108d) | Jul 26, 2020 |
| ADI Engine... | RCC-VE                      | [91f0c6425b](https://bsd-hardware.info/?probe=91f0c6425b) | Jun 03, 2020 |
| ASUSTek       | P5Q SE PLUS                 | [84e9e67aa2](https://bsd-hardware.info/?probe=84e9e67aa2) | May 25, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| pfSense 2.4.5       | 10       | 50%     |
| pfSense 2.5.0       | 4        | 20%     |
| pfSense 2.4.4       | 2        | 10%     |
| pfSense 12.2-STABLE | 2        | 10%     |
| pfSense 2.6.0       | 1        | 5%      |
| pfSense 12.3-STABLE | 1        | 5%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| pfSense | 20       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 19       | 95%     |
| arm   | 1        | 5%      |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 20       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 20       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 20       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 17       | 85%     |
| en_US   | 2        | 10%     |
| pt_BR   | 1        | 5%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 13       | 65%     |
| EFI  | 7        | 35%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ufs  | 12       | 60%     |
| Zfs  | 8        | 40%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 13       | 65%     |
| MBR  | 7        | 35%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Protectli        | 2        | 10%     |
| PC Engines       | 2        | 10%     |
| Intel            | 2        | 10%     |
| Hewlett-Packard  | 2        | 10%     |
| Dell             | 2        | 10%     |
| ASUSTek Computer | 2        | 10%     |
| Unknown          | 2        | 10%     |
| TYAN Computer    | 1        | 5%      |
| Supermicro       | 1        | 5%      |
| Netgate          | 1        | 5%      |
| Lenovo           | 1        | 5%      |
| Itautec          | 1        | 5%      |
| ADI Engineering  | 1        | 5%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 3        | 15%     |
| Intel Q3XXG4-P V1.0               | 2        | 10%     |
| Supermicro X7SPA-HF               | 1        | 5%      |
| Protectli FW4B                    | 1        | 5%      |
| Protectli FW2B                    | 1        | 5%      |
| PC Engines APU2                   | 1        | 5%      |
| PC Engines APU                    | 1        | 5%      |
| Netgate SG-5100                   | 1        | 5%      |
| Lenovo ThinkCentre Edge72 3493AZG | 1        | 5%      |
| Itautec Infoway                   | 1        | 5%      |
| HP t620 PLUS Quad Core TC         | 1        | 5%      |
| HP ProDesk 600 G1 SFF             | 1        | 5%      |
| Dell OptiPlex 990                 | 1        | 5%      |
| Dell OptiPlex 7020                | 1        | 5%      |
| ASUS P5Q SE PLUS                  | 1        | 5%      |
| ASUS All Series                   | 1        | 5%      |
| ADI Engineering RCC-VE            | 1        | 5%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 3        | 15%     |
| Intel Q3XXG4-P         | 2        | 10%     |
| Dell OptiPlex          | 2        | 10%     |
| Supermicro X7SPA-HF    | 1        | 5%      |
| Protectli FW4B         | 1        | 5%      |
| Protectli FW2B         | 1        | 5%      |
| PC Engines APU2        | 1        | 5%      |
| PC Engines APU         | 1        | 5%      |
| Netgate SG-5100        | 1        | 5%      |
| Lenovo ThinkCentre     | 1        | 5%      |
| Itautec Infoway        | 1        | 5%      |
| HP t620                | 1        | 5%      |
| HP ProDesk             | 1        | 5%      |
| ASUS P5Q               | 1        | 5%      |
| ASUS All               | 1        | 5%      |
| ADI Engineering RCC-VE | 1        | 5%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 4        | 20%     |
| 2016    | 3        | 15%     |
| 2014    | 3        | 15%     |
| 2017    | 2        | 10%     |
| 2009    | 2        | 10%     |
| 2019    | 1        | 5%      |
| 2015    | 1        | 5%      |
| 2012    | 1        | 5%      |
| 2010    | 1        | 5%      |
| 2006    | 1        | 5%      |
| Unknown | 1        | 5%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 20       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 85%     |
| Yes  | 3        | 15%     |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 8.01-16.0  | 9        | 45%     |
| 4.01-8.0   | 7        | 35%     |
| 2.01-3.0   | 2        | 10%     |
| 16.01-24.0 | 2        | 10%     |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 14       | 70%     |
| 0.51-1.0 | 4        | 20%     |
| 4.01-8.0 | 1        | 5%      |
| 2.01-3.0 | 1        | 5%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 15       | 75%     |
| 2      | 3        | 15%     |
| 0      | 2        | 10%     |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 18       | 90%     |
| Yes       | 2        | 10%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 19       | 95%     |
| No        | 1        | 5%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 85%     |
| Yes       | 3        | 15%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 20       | 100%    |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 12       | 60%     |
| UK          | 1        | 5%      |
| Taiwan      | 1        | 5%      |
| Sweden      | 1        | 5%      |
| Russia      | 1        | 5%      |
| Netherlands | 1        | 5%      |
| India       | 1        | 5%      |
| Greece      | 1        | 5%      |
| Brazil      | 1        | 5%      |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Salem             | 2        | 10%     |
| Yegor'yevsk       | 1        | 5%      |
| Silver Spring     | 1        | 5%      |
| Pasadena          | 1        | 5%      |
| Malmo             | 1        | 5%      |
| Longmont          | 1        | 5%      |
| Long Beach        | 1        | 5%      |
| London            | 1        | 5%      |
| Lawrenceville     | 1        | 5%      |
| JaraguГЎ do Sul | 1        | 5%      |
| Hoboken           | 1        | 5%      |
| Fletcher          | 1        | 5%      |
| Douliu            | 1        | 5%      |
| Centreville       | 1        | 5%      |
| Bengaluru         | 1        | 5%      |
| Atlanta           | 1        | 5%      |
| Athens            | 1        | 5%      |
| Ashburn           | 1        | 5%      |
| Amsterdam         | 1        | 5%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 5        | 5      | 25%     |
| Seagate             | 2        | 2      | 10%     |
| Samsung Electronics | 2        | 2      | 10%     |
| Phison              | 2        | 2      | 10%     |
| Intel               | 2        | 2      | 10%     |
| Apacer              | 2        | 2      | 10%     |
| WDC                 | 1        | 2      | 5%      |
| SPCC                | 1        | 1      | 5%      |
| Hoodisk             | 1        | 1      | 5%      |
| FORESEE             | 1        | 1      | 5%      |
| China               | 1        | 2      | 5%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SUV500MS120G 120GB     | 2        | 10%     |
| WDC WD10EFRX-68FYTN0 1TB        | 1        | 5%      |
| SPCC Solid State Disk 120GB     | 1        | 5%      |
| Seagate ST500DM002-1BD142 500GB | 1        | 5%      |
| Seagate ST3160023A 160GB        | 1        | 5%      |
| Samsung SSD RBX Series 64GB M   | 1        | 5%      |
| Samsung SSD 860 EVO 250GB       | 1        | 5%      |
| Phison SATA SSD 32GB            | 1        | 5%      |
| Phison SATA SSD 240GB           | 1        | 5%      |
| Kingston SUV500MS240G 240GB     | 1        | 5%      |
| Kingston SUV500M8120G 120GB     | 1        | 5%      |
| Kingston SNS4151S316G 16GB      | 1        | 5%      |
| Intel SSDSA2CW080G3 80GB        | 1        | 5%      |
| Intel SSDMCEAC030B3 32GB        | 1        | 5%      |
| Hoodisk SSD 32GB                | 1        | 5%      |
| FORESEE 64GB SSD                | 1        | 5%      |
| China SATA SSD 256GB            | 1        | 5%      |
| Apacer 64GB SATA Flash Drive    | 1        | 5%      |
| Apacer 32GB SATA Flash Drive    | 1        | 5%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 2      | 66.67%  |
| WDC     | 1        | 2      | 33.33%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 5        | 5      | 29.41%  |
| Samsung Electronics | 2        | 2      | 11.76%  |
| Phison              | 2        | 2      | 11.76%  |
| Intel               | 2        | 2      | 11.76%  |
| Apacer              | 2        | 2      | 11.76%  |
| SPCC                | 1        | 1      | 5.88%   |
| Hoodisk             | 1        | 1      | 5.88%   |
| FORESEE             | 1        | 1      | 5.88%   |
| China               | 1        | 2      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 15       | 18     | 83.33%  |
| HDD  | 3        | 4      | 16.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 18       | 22     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 17       | 20     | 94.44%  |
| 0.51-1.0   | 1        | 2      | 5.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 21-50      | 5        | 25%     |
| 101-250    | 5        | 25%     |
| 51-100     | 5        | 25%     |
| 1-20       | 3        | 15%     |
| 251-500    | 1        | 5%      |
| 501-1000   | 1        | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 19       | 95%     |
| 21-50   | 1        | 5%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| Kingston SNS4151S316G 16GB   | 1        | 1      | 50%     |
| Apacer 32GB SATA Flash Drive | 1        | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Kingston | 1        | 1      | 50%     |
| Apacer   | 1        | 1      | 50%     |

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
| SSD  | 2        | 2      | 100%    |

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
| Works   | 16       | 20     | 88.89%  |
| Malfunc | 2        | 2      | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Intel              | 15       | 71.43%  |
| AMD                | 4        | 19.05%  |
| Silicon Image      | 1        | 4.76%   |
| JMicron Technology | 1        | 4.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4        | 16%     |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2        | 8%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2        | 8%      |
| AMD FCH SATA Controller [AHCI mode]                                              | 2        | 8%      |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1        | 4%      |
| JMicron JMB368 IDE controller                                                    | 1        | 4%      |
| Intel SATA Controller [RAID mode]                                                | 1        | 4%      |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1        | 4%      |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1        | 4%      |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1        | 4%      |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 1        | 4%      |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 1        | 4%      |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 4%      |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 4%      |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 4%      |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 4%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1        | 4%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1        | 4%      |
| AMD AMD-8111 IDE                                                                 | 1        | 4%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 15       | 75%     |
| IDE  | 3        | 15%     |
| RAID | 2        | 10%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 15       | 75%     |
| AMD    | 4        | 20%     |
| ARM    | 1        | 5%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Core i7-5550U CPU @ 2.00GHz        | 2        | 10%     |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2        | 10%     |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1        | 5%      |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1        | 5%      |
| Intel Core i5-3470S CPU @ 2.90GHz        | 1        | 5%      |
| Intel Core i5-2400 CPU @ 3.10GH          | 1        | 5%      |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz     | 1        | 5%      |
| Intel Celeron CPU N3150 @ 1.60GHz        | 1        | 5%      |
| Intel Celeron CPU J3060 @ 1.60GHz        | 1        | 5%      |
| Intel Celeron CPU 450 @ 2.20GHz          | 1        | 5%      |
| Intel Atom CPU D525 @ 1.80GHz            | 1        | 5%      |
| Intel Atom CPU C3558 @ 2.20GHz           | 1        | 5%      |
| Intel Atom CPU C2758 @ 2.40GHz           | 1        | 5%      |
| ARM Cortex-A9 r4p1 (ECO: 0x00000000)     | 1        | 5%      |
| AMD Opteron Processor 252                | 1        | 5%      |
| AMD GX-420CA SOC with Radeon HD Graphics | 1        | 5%      |
| AMD GX-412TC SOC                         | 1        | 5%      |
| AMD G-T40E Processor                     | 1        | 5%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Desktops | Percent |
|------------------|----------|---------|
| Intel Celeron    | 5        | 25%     |
| Intel Core i5    | 4        | 20%     |
| Intel Atom       | 3        | 15%     |
| Intel Core i7    | 2        | 10%     |
| AMD GX           | 2        | 10%     |
| Intel Core 2 Duo | 1        | 5%      |
| ARM Cortex       | 1        | 5%      |
| AMD Opteron      | 1        | 5%      |
| AMD G            | 1        | 5%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 10       | 50%     |
| 2       | 6        | 30%     |
| Unknown | 3        | 15%     |
| 1       | 1        | 5%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 18       | 90%     |
| 2       | 1        | 5%      |
| Unknown | 1        | 5%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 14       | 70%     |
| 2       | 3        | 15%     |
| Unknown | 3        | 15%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Silvermont  | 5        | 25%     |
| Unknown     | 3        | 15%     |
| Haswell     | 2        | 10%     |
| Broadwell   | 2        | 10%     |
| SandyBridge | 1        | 5%      |
| Puma        | 1        | 5%      |
| Penryn      | 1        | 5%      |
| K8 Hammer   | 1        | 5%      |
| IvyBridge   | 1        | 5%      |
| Goldmont    | 1        | 5%      |
| Bonnell     | 1        | 5%      |
| Bobcat      | 1        | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 11       | 73.33%  |
| AMD                        | 3        | 20%     |
| Matrox Electronics Systems | 1        | 6.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 26.67%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2        | 13.33%  |
| Intel HD Graphics 6000                                                                   | 2        | 13.33%  |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 6.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1        | 6.67%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 6.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 6.67%   |
| AMD Rage 3 [Rage XL PCI]                                                                 | 1        | 6.67%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1        | 6.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 6.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 11       | 55%     |
| Other      | 5        | 25%     |
| 1 x AMD    | 3        | 15%     |
| 1 x Matrox | 1        | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 15       | 75%     |
| Unknown | 5        | 25%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

Zero info for selected period =(

Monitor Model
-------------

Monitor models

Zero info for selected period =(

Monitor Resolution
------------------

Monitor screen resolution

Zero info for selected period =(

Monitor Diagonal
----------------

Diagonal size in inches

Zero info for selected period =(

Monitor Width
-------------

Physical width

Zero info for selected period =(

Aspect Ratio
------------

Proportional relationship between the width and the height

Zero info for selected period =(

Monitor Area
------------

Area in inch²

Zero info for selected period =(

Pixel Density
-------------

Pixels per inch

Zero info for selected period =(

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 20       | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 53.85%  |
| Realtek Semiconductor | 5        | 19.23%  |
| Qualcomm Atheros      | 3        | 11.54%  |
| Broadcom              | 2        | 7.69%   |
| NetXen Incorporated   | 1        | 3.85%   |
| MediaTek              | 1        | 3.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5        | 15.15%  |
| Intel I211 Gigabit Network Connection                                         | 4        | 12.12%  |
| Intel I210 Gigabit Network Connection                                         | 4        | 12.12%  |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2        | 6.06%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 6.06%   |
| Intel 82580 Gigabit Network Connection                                        | 2        | 6.06%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 6.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 3.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1        | 3.03%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter          | 1        | 3.03%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 3.03%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 3.03%   |
| Intel Ethernet Connection I354                                                | 1        | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 3.03%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 3.03%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 3.03%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 3.03%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 3.03%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1        | 3.03%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Qualcomm Atheros | 3        | 100%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2        | 66.67%  |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 33.33%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 66.67%  |
| Realtek Semiconductor | 5        | 23.81%  |
| Broadcom              | 2        | 9.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 5        | 17.86%  |
| Intel I211 Gigabit Network Connection                                         | 4        | 14.29%  |
| Intel I210 Gigabit Network Connection                                         | 4        | 14.29%  |
| Intel Ethernet Connection I217-LM                                             | 2        | 7.14%   |
| Intel 82580 Gigabit Network Connection                                        | 2        | 7.14%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 7.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 3.57%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 3.57%   |
| Intel Ethernet Connection I354                                                | 1        | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 3.57%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 3.57%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 3.57%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 3.57%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 3.57%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1        | 3.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 79.17%  |
| WiFi     | 3        | 12.5%   |
| Modem    | 1        | 4.17%   |
| Unknown  | 1        | 4.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 19       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 5     | 5        | 25%     |
| 3     | 4        | 20%     |
| 2     | 4        | 20%     |
| 6     | 3        | 15%     |
| 4     | 2        | 10%     |
| 8     | 1        | 5%      |
| 0     | 1        | 5%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 17       | 85%     |
| Yes  | 3        | 15%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

Zero info for selected period =(

Bluetooth Model
---------------

Controller models

Zero info for selected period =(

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 9        | 81.82%  |
| AMD    | 2        | 18.18%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 18.75%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2        | 12.5%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 12.5%   |
| Intel Broadwell-U Audio Controller                                                                | 2        | 12.5%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2        | 12.5%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1        | 6.25%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 6.25%   |
| AMD FCH Azalia Controller                                                                         | 1        | 6.25%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 6.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 6        | 31.58%  |
| Samsung Electronics | 4        | 21.05%  |
| Crucial             | 4        | 21.05%  |
| Transcend           | 2        | 10.53%  |
| SK Hynix            | 1        | 5.26%   |
| Micron Technology   | 1        | 5.26%   |
| Kingston            | 1        | 5.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                     | 2        | 10.53%  |
| Crucial RAM CT204864BF160B.M16 16GB SODIMM DDR3 1600MT/s | 2        | 10.53%  |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s      | 1        | 5.26%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 1        | 5.26%   |
| Unknown RAM Module 4096MB SODIMM DDR3 800MT/s            | 1        | 5.26%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 5.26%   |
| Transcend RAM TS512MSH64V4H 4096MB DIMM DDR4 2400MT/s    | 1        | 5.26%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s        | 1        | 5.26%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 5.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 5.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 5.26%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 5.26%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 5.26%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 5.26%   |
| Kingston RAM 9905471-028.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 5.26%   |
| Crucial RAM CT25664BD160B.C8FP 2GB DIMM DDR3 1333MT/s    | 1        | 5.26%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s    | 1        | 5.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 13       | 76.47%  |
| SDRAM | 2        | 11.76%  |
| DDR4  | 1        | 5.88%   |
| DDR2  | 1        | 5.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 12       | 70.59%  |
| SODIMM | 5        | 29.41%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 10       | 58.82%  |
| 2048  | 4        | 23.53%  |
| 16384 | 2        | 11.76%  |
| 8192  | 1        | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 8        | 47.06%  |
| 1333    | 4        | 23.53%  |
| 800     | 2        | 11.76%  |
| Unknown | 2        | 11.76%  |
| 2400    | 1        | 5.88%   |

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
| 0     | 12       | 60%     |
| 1     | 7        | 35%     |
| 2     | 1        | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 7        | 87.5%   |
| Network                  | 1        | 12.5%   |
