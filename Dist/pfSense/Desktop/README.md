pfSense - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for pfSense.

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

Total: 41

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| SJRC          | ADLN-6L                     | [a600ba22b2](https://bsd-hardware.info/?probe=a600ba22b2) | Dec 09, 2024 |
| PC Engines    | APU2                        | [66d6af8951](https://bsd-hardware.info/?probe=66d6af8951) | Feb 20, 2024 |
| Dell          | 0NC2VH A01                  | [83673368b9](https://bsd-hardware.info/?probe=83673368b9) | Nov 17, 2023 |
| Dell          | 0NC2VH A01                  | [0d6203b7c9](https://bsd-hardware.info/?probe=0d6203b7c9) | Nov 07, 2023 |
| Dell          | 0NC2VH A01                  | [e69fadd7a8](https://bsd-hardware.info/?probe=e69fadd7a8) | Oct 29, 2023 |
| Techvision    | TVI7309X B0                 | [b6e5a7e7bc](https://bsd-hardware.info/?probe=b6e5a7e7bc) | Jun 18, 2023 |
| Techvision    | TVI7309X B0                 | [2d50927445](https://bsd-hardware.info/?probe=2d50927445) | Jun 18, 2023 |
| HP            | 0AA0h                       | [bed2f4cfd7](https://bsd-hardware.info/?probe=bed2f4cfd7) | May 16, 2023 |
| Advantech     | UNO-2271G_V2                | [23e4b8d9b1](https://bsd-hardware.info/?probe=23e4b8d9b1) | Apr 12, 2023 |
| HP            | 805D                        | [4912ca5cd6](https://bsd-hardware.info/?probe=4912ca5cd6) | Jan 11, 2023 |
| HP            | 805D                        | [3da9c57f1f](https://bsd-hardware.info/?probe=3da9c57f1f) | Jan 11, 2023 |
| Unknown       | Unknown                     | [fdffbdb940](https://bsd-hardware.info/?probe=fdffbdb940) | Nov 22, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [0d37f1878b](https://bsd-hardware.info/?probe=0d37f1878b) | Nov 17, 2022 |
| ASUSTek       | A88XM-E                     | [fde1fa45b8](https://bsd-hardware.info/?probe=fde1fa45b8) | Nov 07, 2022 |
| Techvision    | TVI7309X B0                 | [384de92279](https://bsd-hardware.info/?probe=384de92279) | Oct 07, 2022 |
| Intel         | Q3XXG4-P V1.0               | [5b73e61a78](https://bsd-hardware.info/?probe=5b73e61a78) | Jul 31, 2022 |
| Intel         | Q3XXG4-P V1.0               | [699fea1ac9](https://bsd-hardware.info/?probe=699fea1ac9) | Jul 02, 2022 |
| Gigabyte      | B85M-D3H                    | [92f62da399](https://bsd-hardware.info/?probe=92f62da399) | Jun 22, 2022 |
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
| pfSense 2.4.5       | 10       | 31.25%  |
| pfSense 2.6.0       | 7        | 21.88%  |
| pfSense 2.5.0       | 4        | 12.5%   |
| pfSense 12.3-STABLE | 4        | 12.5%   |
| pfSense 2.7.2       | 2        | 6.25%   |
| pfSense 2.4.4       | 2        | 6.25%   |
| pfSense 12.2-STABLE | 2        | 6.25%   |
| pfSense 2.7.0       | 1        | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| pfSense | 31       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 30       | 96.77%  |
| arm   | 1        | 3.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 31       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 31       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 31       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 80.65%  |
| C       | 3        | 9.68%   |
| en_US   | 2        | 6.45%   |
| pt_BR   | 1        | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 17       | 54.84%  |
| EFI  | 14       | 45.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 17       | 54.84%  |
| Ufs  | 14       | 45.16%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 24       | 77.42%  |
| MBR  | 7        | 22.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 12.9%   |
| PC Engines          | 3        | 9.68%   |
| ASUSTek Computer    | 3        | 9.68%   |
| Unknown             | 3        | 9.68%   |
| Techvision          | 2        | 6.45%   |
| Protectli           | 2        | 6.45%   |
| Lenovo              | 2        | 6.45%   |
| Intel               | 2        | 6.45%   |
| Dell                | 2        | 6.45%   |
| TYAN Computer       | 1        | 3.23%   |
| Supermicro          | 1        | 3.23%   |
| SJRC                | 1        | 3.23%   |
| Netgate             | 1        | 3.23%   |
| Itautec             | 1        | 3.23%   |
| Gigabyte Technology | 1        | 3.23%   |
| Advantech           | 1        | 3.23%   |
| ADI Engineering     | 1        | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Unknown                           | 4        | 12.9%   |
| Techvision TVI7309X               | 2        | 6.45%   |
| PC Engines APU2                   | 2        | 6.45%   |
| Intel Q3XXG4-P V1.0               | 2        | 6.45%   |
| Supermicro X7SPA-HF               | 1        | 3.23%   |
| SJRC ADLN-6L                      | 1        | 3.23%   |
| Protectli FW4B                    | 1        | 3.23%   |
| Protectli FW2B                    | 1        | 3.23%   |
| PC Engines APU                    | 1        | 3.23%   |
| Netgate SG-5100                   | 1        | 3.23%   |
| Lenovo ThinkCentre M92p 3209D9U   | 1        | 3.23%   |
| Lenovo ThinkCentre Edge72 3493AZG | 1        | 3.23%   |
| Itautec Infoway                   | 1        | 3.23%   |
| HP xw4600 Workstation             | 1        | 3.23%   |
| HP t620 PLUS Quad Core TC         | 1        | 3.23%   |
| HP ProDesk 600 G2 SFF             | 1        | 3.23%   |
| HP ProDesk 600 G1 SFF             | 1        | 3.23%   |
| Gigabyte B85M-D3H                 | 1        | 3.23%   |
| Dell OptiPlex 990                 | 1        | 3.23%   |
| Dell OptiPlex 7020                | 1        | 3.23%   |
| ASUS P5Q SE PLUS                  | 1        | 3.23%   |
| ASUS All Series                   | 1        | 3.23%   |
| ASUS A88XM-E                      | 1        | 3.23%   |
| Advantech UNO-2271G_V2            | 1        | 3.23%   |
| ADI Engineering RCC-VE            | 1        | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Unknown                | 4        | 12.9%   |
| Techvision TVI7309X    | 2        | 6.45%   |
| PC Engines APU2        | 2        | 6.45%   |
| Lenovo ThinkCentre     | 2        | 6.45%   |
| Intel Q3XXG4-P         | 2        | 6.45%   |
| HP ProDesk             | 2        | 6.45%   |
| Dell OptiPlex          | 2        | 6.45%   |
| Supermicro X7SPA-HF    | 1        | 3.23%   |
| SJRC ADLN-6L           | 1        | 3.23%   |
| Protectli FW4B         | 1        | 3.23%   |
| Protectli FW2B         | 1        | 3.23%   |
| PC Engines APU         | 1        | 3.23%   |
| Netgate SG-5100        | 1        | 3.23%   |
| Itautec Infoway        | 1        | 3.23%   |
| HP xw4600              | 1        | 3.23%   |
| HP t620                | 1        | 3.23%   |
| Gigabyte B85M-D3H      | 1        | 3.23%   |
| ASUS P5Q               | 1        | 3.23%   |
| ASUS All               | 1        | 3.23%   |
| ASUS A88XM-E           | 1        | 3.23%   |
| Advantech UNO-2271G    | 1        | 3.23%   |
| ADI Engineering RCC-VE | 1        | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 5        | 16.13%  |
| 2016    | 4        | 12.9%   |
| 2022    | 3        | 9.68%   |
| 2015    | 3        | 9.68%   |
| 2017    | 2        | 6.45%   |
| 2014    | 2        | 6.45%   |
| 2013    | 2        | 6.45%   |
| 2012    | 2        | 6.45%   |
| 2009    | 2        | 6.45%   |
| 2024    | 1        | 3.23%   |
| 2021    | 1        | 3.23%   |
| 2019    | 1        | 3.23%   |
| 2010    | 1        | 3.23%   |
| 2006    | 1        | 3.23%   |
| Unknown | 1        | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 31       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 87.1%   |
| Yes  | 4        | 12.9%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 11       | 35.48%  |
| 8.01-16.0   | 11       | 35.48%  |
| 16.01-24.0  | 5        | 16.13%  |
| 2.01-3.0    | 2        | 6.45%   |
| 32.01-64.0  | 1        | 3.23%   |
| 64.01-256.0 | 1        | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 18       | 58.06%  |
| 0.51-1.0 | 8        | 25.81%  |
| 4.01-8.0 | 2        | 6.45%   |
| 2.01-3.0 | 2        | 6.45%   |
| 1.01-2.0 | 1        | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 25       | 78.13%  |
| 0      | 4        | 12.5%   |
| 2      | 3        | 9.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 83.87%  |
| Yes       | 5        | 16.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 30       | 96.77%  |
| No        | 1        | 3.23%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 80.65%  |
| Yes       | 6        | 19.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 96.77%  |
| Yes       | 1        | 3.23%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 15       | 48.39%  |
| Germany     | 3        | 9.68%   |
| Russia      | 2        | 6.45%   |
| Brazil      | 2        | 6.45%   |
| UK          | 1        | 3.23%   |
| Taiwan      | 1        | 3.23%   |
| Sweden      | 1        | 3.23%   |
| New Zealand | 1        | 3.23%   |
| Netherlands | 1        | 3.23%   |
| India       | 1        | 3.23%   |
| Greece      | 1        | 3.23%   |
| Canada      | 1        | 3.23%   |
| Cameroon    | 1        | 3.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Salem             | 2        | 6.45%   |
| Yegor'yevsk       | 1        | 3.23%   |
| Wellington        | 1        | 3.23%   |
| Waconia           | 1        | 3.23%   |
| Uxbridge          | 1        | 3.23%   |
| Stuttgart         | 1        | 3.23%   |
| Silver Spring     | 1        | 3.23%   |
| Renton            | 1        | 3.23%   |
| Pasadena          | 1        | 3.23%   |
| Moscow            | 1        | 3.23%   |
| Meine             | 1        | 3.23%   |
| Malmo             | 1        | 3.23%   |
| Longmont          | 1        | 3.23%   |
| Long Beach        | 1        | 3.23%   |
| London            | 1        | 3.23%   |
| Lawrenceville     | 1        | 3.23%   |
| Kottenheim        | 1        | 3.23%   |
| JaraguГЎ do Sul | 1        | 3.23%   |
| Jaraguá do Sul   | 1        | 3.23%   |
| Hoboken           | 1        | 3.23%   |
| Fletcher          | 1        | 3.23%   |
| Douliu            | 1        | 3.23%   |
| Douala            | 1        | 3.23%   |
| Daly City         | 1        | 3.23%   |
| Centreville       | 1        | 3.23%   |
| Bengaluru         | 1        | 3.23%   |
| Atlanta           | 1        | 3.23%   |
| Athens            | 1        | 3.23%   |
| Ashburn           | 1        | 3.23%   |
| Amsterdam         | 1        | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 6        | 6      | 20%     |
| Seagate             | 4        | 4      | 13.33%  |
| Samsung Electronics | 4        | 4      | 13.33%  |
| WDC                 | 2        | 3      | 6.67%   |
| Phison              | 2        | 2      | 6.67%   |
| Intel               | 2        | 2      | 6.67%   |
| Apacer              | 2        | 2      | 6.67%   |
| SPCC                | 1        | 1      | 3.33%   |
| Silicon Motion      | 1        | 1      | 3.33%   |
| SanDisk             | 1        | 1      | 3.33%   |
| Netac               | 1        | 1      | 3.33%   |
| Hoodisk             | 1        | 1      | 3.33%   |
| FORESEE             | 1        | 1      | 3.33%   |
| Crucial             | 1        | 1      | 3.33%   |
| China               | 1        | 2      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SUV500MS120G 120GB     | 2        | 6.67%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 1        | 3.33%   |
| WDC WD10EFRX-68FYTN0 1TB        | 1        | 3.33%   |
| SPCC Solid State Disk 120GB     | 1        | 3.33%   |
| Silicon Motion NVME SSD 128GB   | 1        | 3.33%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 3.33%   |
| Seagate ST380815AS 80GB         | 1        | 3.33%   |
| Seagate ST3160023A 160GB        | 1        | 3.33%   |
| Seagate ST240HM000-1G5152 240GB | 1        | 3.33%   |
| SanDisk SDSSDP064G 64GB         | 1        | 3.33%   |
| Samsung SSD RBX Series 64GB M   | 1        | 3.33%   |
| Samsung SSD 860 EVO 250GB       | 1        | 3.33%   |
| Samsung SSD 850 EVO mSATA 250GB | 1        | 3.33%   |
| Samsung SSD 850 EVO 120GB       | 1        | 3.33%   |
| Phison SATA SSD 32GB            | 1        | 3.33%   |
| Phison SATA SSD 240GB           | 1        | 3.33%   |
| Netac SSD 256GB                 | 1        | 3.33%   |
| Kingston SUV500MS240G 240GB     | 1        | 3.33%   |
| Kingston SUV500M8120G 120GB     | 1        | 3.33%   |
| Kingston SNVS1000G 1TB          | 1        | 3.33%   |
| Kingston SNS4151S316G 16GB      | 1        | 3.33%   |
| Intel SSDSA2CW080G3 80GB        | 1        | 3.33%   |
| Intel SSDMCEAC030B3 32GB        | 1        | 3.33%   |
| Hoodisk SSD 32GB                | 1        | 3.33%   |
| FORESEE 64GB SSD                | 1        | 3.33%   |
| Crucial CT500P2SSD8 500GB       | 1        | 3.33%   |
| China SATA SSD 256GB            | 1        | 3.33%   |
| Apacer 64GB SATA Flash Drive    | 1        | 3.33%   |
| Apacer 32GB SATA Flash Drive    | 1        | 3.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 3        | 3      | 60%     |
| WDC     | 2        | 3      | 40%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 5        | 5      | 22.73%  |
| Samsung Electronics | 4        | 4      | 18.18%  |
| Phison              | 2        | 2      | 9.09%   |
| Intel               | 2        | 2      | 9.09%   |
| Apacer              | 2        | 2      | 9.09%   |
| SPCC                | 1        | 1      | 4.55%   |
| Seagate             | 1        | 1      | 4.55%   |
| SanDisk             | 1        | 1      | 4.55%   |
| Netac               | 1        | 1      | 4.55%   |
| Hoodisk             | 1        | 1      | 4.55%   |
| FORESEE             | 1        | 1      | 4.55%   |
| China               | 1        | 2      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 19       | 23     | 70.37%  |
| HDD  | 5        | 6      | 18.52%  |
| NVMe | 3        | 3      | 11.11%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 24       | 29     | 88.89%  |
| NVMe | 3        | 3      | 11.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 23       | 27     | 95.83%  |
| 0.51-1.0   | 1        | 2      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 9        | 29.03%  |
| 51-100     | 8        | 25.81%  |
| 21-50      | 6        | 19.35%  |
| 251-500    | 3        | 9.68%   |
| 1-20       | 3        | 9.68%   |
| 501-1000   | 2        | 6.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 30       | 96.77%  |
| 21-50   | 1        | 3.23%   |

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
| Works   | 25       | 30     | 92.59%  |
| Malfunc | 2        | 2      | 7.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 22       | 64.71%  |
| AMD                         | 6        | 17.65%  |
| Silicon Motion              | 2        | 5.88%   |
| Silicon Image               | 1        | 2.94%   |
| Micron/Crucial Technology   | 1        | 2.94%   |
| Kingston Technology Company | 1        | 2.94%   |
| JMicron Technology          | 1        | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4        | 10.53%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3        | 7.89%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 3        | 7.89%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 2        | 5.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2        | 5.26%   |
| Intel SATA Controller [RAID mode]                                                | 2        | 5.26%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                 | 1        | 2.63%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1        | 2.63%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                             | 1        | 2.63%   |
| JMicron JMB368 IDE controller                                                    | 1        | 2.63%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1        | 2.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1        | 2.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1        | 2.63%   |
| Intel Elkhart Lake SATA AHCI                                                     | 1        | 2.63%   |
| Intel Atom Processor C3000 Series SATA Controller 1                              | 1        | 2.63%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 1        | 2.63%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 1        | 2.63%   |
| Intel Atom processor C2000 AHCI SATA2 Controller                                 | 1        | 2.63%   |
| Intel Alder Lake-N SATA AHCI Controller                                          | 1        | 2.63%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 1        | 2.63%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                       | 1        | 2.63%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]             | 1        | 2.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1        | 2.63%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1        | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1        | 2.63%   |
| AMD FCH SATA Controller [IDE mode]                                               | 1        | 2.63%   |
| AMD AMD-8111 IDE                                                                 | 1        | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 22       | 66.67%  |
| NVMe | 4        | 12.12%  |
| IDE  | 4        | 12.12%  |
| RAID | 3        | 9.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 24       | 77.42%  |
| AMD    | 6        | 19.35%  |
| ARM    | 1        | 3.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Core i7-5550U CPU @ 2.00GHz        | 2        | 6.45%   |
| Intel Celeron N5105 @ 2.00GHz            | 2        | 6.45%   |
| Intel Celeron CPU J3160 @ 1.60GHz        | 2        | 6.45%   |
| AMD GX-412TC SOC                         | 2        | 6.45%   |
| Intel N100                               | 1        | 3.23%   |
| Intel Core i5-6500 CPU @ 3.20GHz         | 1        | 3.23%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1        | 3.23%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 1        | 3.23%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 1        | 3.23%   |
| Intel Core i5-3570 CPU @ 3.40GHz         | 1        | 3.23%   |
| Intel Core i5-3470S CPU @ 2.90GHz        | 1        | 3.23%   |
| Intel Core i5-2400 CPU @ 3.10GH          | 1        | 3.23%   |
| Intel Core 2 Quad CPU Q9450 @ 2.66GHz    | 1        | 3.23%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz     | 1        | 3.23%   |
| Intel Celeron N6210 @ 1.20GHz            | 1        | 3.23%   |
| Intel Celeron CPU N3150 @ 1.60GHz        | 1        | 3.23%   |
| Intel Celeron CPU J3060 @ 1.60GHz        | 1        | 3.23%   |
| Intel Celeron CPU 450 @ 2.20GHz          | 1        | 3.23%   |
| Intel Atom CPU D525 @ 1.80GHz            | 1        | 3.23%   |
| Intel Atom CPU C3558 @ 2.20GHz           | 1        | 3.23%   |
| Intel Atom CPU C2758 @ 2.40GHz           | 1        | 3.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 1        | 3.23%   |
| ARM Cortex-A9 r4p1 (ECO: 0x00000000)     | 1        | 3.23%   |
| AMD Opteron Processor 252                | 1        | 3.23%   |
| AMD GX-420CA SOC with Radeon HD Graphics | 1        | 3.23%   |
| AMD G-T40E Processor                     | 1        | 3.23%   |
| AMD Athlon X4 860K Quad Core Processor   | 1        | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Celeron     | 8        | 25.81%  |
| Intel Core i5     | 7        | 22.58%  |
| Intel Atom        | 3        | 9.68%   |
| AMD GX            | 3        | 9.68%   |
| Other             | 2        | 6.45%   |
| Intel Core i7     | 2        | 6.45%   |
| Intel Core 2 Quad | 1        | 3.23%   |
| Intel Core 2 Duo  | 1        | 3.23%   |
| ARM Cortex        | 1        | 3.23%   |
| AMD Opteron       | 1        | 3.23%   |
| AMD G             | 1        | 3.23%   |
| AMD Athlon X4     | 1        | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 20       | 64.52%  |
| 2       | 7        | 22.58%  |
| Unknown | 3        | 9.68%   |
| 1       | 1        | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 29       | 93.55%  |
| 2       | 1        | 3.23%   |
| Unknown | 1        | 3.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 24       | 77.42%  |
| 2       | 4        | 12.9%   |
| Unknown | 3        | 9.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 7        | 22.58%  |
| Silvermont  | 5        | 16.13%  |
| Haswell     | 3        | 9.68%   |
| Puma        | 2        | 6.45%   |
| Penryn      | 2        | 6.45%   |
| IvyBridge   | 2        | 6.45%   |
| Broadwell   | 2        | 6.45%   |
| TigerLake   | 1        | 3.23%   |
| Steamroller | 1        | 3.23%   |
| Skylake     | 1        | 3.23%   |
| SandyBridge | 1        | 3.23%   |
| K8 Hammer   | 1        | 3.23%   |
| Goldmont    | 1        | 3.23%   |
| Bonnell     | 1        | 3.23%   |
| Bobcat      | 1        | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 19       | 79.17%  |
| AMD                        | 4        | 16.67%  |
| Matrox Electronics Systems | 1        | 4.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 16.67%  |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3        | 12.5%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 8.33%   |
| Intel JasperLake [UHD Graphics]                                                          | 2        | 8.33%   |
| Intel HD Graphics 6000                                                                   | 2        | 8.33%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1        | 4.17%   |
| Intel HD Graphics 530                                                                    | 1        | 4.17%   |
| Intel Elkhart Lake [UHD Graphics Gen11 16EU]                                             | 1        | 4.17%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 1        | 4.17%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 1        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1        | 4.17%   |
| AMD RV710 [Radeon HD 4550]                                                               | 1        | 4.17%   |
| AMD Rage 3 [Rage XL PCI]                                                                 | 1        | 4.17%   |
| AMD Kabini [Radeon HD 8400E]                                                             | 1        | 4.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1        | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 19       | 61.29%  |
| Other      | 7        | 22.58%  |
| 1 x AMD    | 4        | 12.9%   |
| 1 x Matrox | 1        | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 24       | 77.42%  |
| Unknown | 7        | 22.58%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 31       | 100%    |

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
| 0     | 31       | 100%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 23       | 57.5%   |
| Realtek Semiconductor     | 8        | 20%     |
| Qualcomm Atheros          | 3        | 7.5%    |
| Broadcom                  | 3        | 7.5%    |
| Solarflare Communications | 1        | 2.5%    |
| NetXen Incorporated       | 1        | 2.5%    |
| MediaTek                  | 1        | 2.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 7        | 13.73%  |
| Intel I211 Gigabit Network Connection                                         | 5        | 9.8%    |
| Intel I210 Gigabit Network Connection                                         | 5        | 9.8%    |
| Intel 82580 Gigabit Network Connection                                        | 3        | 5.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2        | 3.92%   |
| Intel Ethernet Controller I226-V                                              | 2        | 3.92%   |
| Intel Ethernet Controller I225-V                                              | 2        | 3.92%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 3.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 3.92%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 3.92%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 1.96%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1        | 1.96%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 1.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 1.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1        | 1.96%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter          | 1        | 1.96%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 1.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1        | 1.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 1        | 1.96%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 1.96%   |
| Intel Ethernet Connection I354                                                | 1        | 1.96%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 1.96%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 1.96%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 1.96%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 1.96%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 1.96%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 1.96%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 1.96%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1        | 1.96%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Qualcomm Atheros      | 3        | 50%     |
| Intel                 | 2        | 33.33%  |
| Realtek Semiconductor | 1        | 16.67%  |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2        | 33.33%  |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1        | 16.67%  |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1        | 16.67%  |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1        | 16.67%  |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 1        | 16.67%  |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 23       | 63.89%  |
| Realtek Semiconductor     | 8        | 22.22%  |
| Broadcom                  | 3        | 8.33%   |
| Solarflare Communications | 1        | 2.78%   |
| MediaTek                  | 1        | 2.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 7        | 15.91%  |
| Intel I211 Gigabit Network Connection                                         | 5        | 11.36%  |
| Intel I210 Gigabit Network Connection                                         | 5        | 11.36%  |
| Intel 82580 Gigabit Network Connection                                        | 3        | 6.82%   |
| Intel Ethernet Controller I226-V                                              | 2        | 4.55%   |
| Intel Ethernet Controller I225-V                                              | 2        | 4.55%   |
| Intel Ethernet Connection I217-LM                                             | 2        | 4.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 4.55%   |
| Intel 82574L Gigabit Network Connection                                       | 2        | 4.55%   |
| Solarflare SFC9120 10G Ethernet Controller                                    | 1        | 2.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1        | 2.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 2.27%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1        | 2.27%   |
| Intel Ethernet Connection X553 1GbE                                           | 1        | 2.27%   |
| Intel Ethernet Connection I354                                                | 1        | 2.27%   |
| Intel Ethernet Connection (2) I219-LM                                         | 1        | 2.27%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 1        | 2.27%   |
| Intel 82576 Gigabit Network Connection                                        | 1        | 2.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.27%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller (Copper)                    | 1        | 2.27%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 1        | 2.27%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express                       | 1        | 2.27%   |
| Broadcom NetXtreme BCM5704 Gigabit Ethernet                                   | 1        | 2.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 81.08%  |
| WiFi     | 6        | 16.22%  |
| Unknown  | 1        | 2.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 100%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 3     | 8        | 25.81%  |
| 5     | 7        | 22.58%  |
| 2     | 5        | 16.13%  |
| 6     | 4        | 12.9%   |
| 4     | 4        | 12.9%   |
| 8     | 1        | 3.23%   |
| 7     | 1        | 3.23%   |
| 0     | 1        | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 26       | 83.87%  |
| Yes  | 5        | 16.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1        | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Intel Wireless-AC 9260 Bluetooth Adapter | 1        | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 18       | 85.71%  |
| AMD    | 3        | 14.29%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3        | 11.54%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 11.54%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 7.69%   |
| Intel Jasper Lake HD Audio                                                                        | 2        | 7.69%   |
| Intel Broadwell-U Audio Controller                                                                | 2        | 7.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2        | 7.69%   |
| AMD FCH Azalia Controller                                                                         | 2        | 7.69%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1        | 3.85%   |
| Intel Elkhart Lake High Density Audio bus interface                                               | 1        | 3.85%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 1        | 3.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 3.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 3.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1        | 3.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1        | 3.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1        | 3.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1        | 3.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 7        | 23.33%  |
| Samsung Electronics | 6        | 20%     |
| Crucial             | 5        | 16.67%  |
| Transcend           | 2        | 6.67%   |
| SK hynix            | 2        | 6.67%   |
| Micron Technology   | 2        | 6.67%   |
| V-Color             | 1        | 3.33%   |
| Unknown (0x1636)    | 1        | 3.33%   |
| Ramaxel Technology  | 1        | 3.33%   |
| Nanya Technology    | 1        | 3.33%   |
| Kingston            | 1        | 3.33%   |
| Corsair             | 1        | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                     | 2        | 6.67%   |
| Crucial RAM CT204864BF160B.M16 16GB SODIMM DDR3 1600MT/s | 2        | 6.67%   |
| V-Color RAM TN432G32D822 32GB SODIMM DDR4 3200MT/s       | 1        | 3.33%   |
| Unknown RAM WPBS16D308SWD-4G 4GB DIMM DDR3 1600MT/s      | 1        | 3.33%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s              | 1        | 3.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 1        | 3.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3 800MT/s            | 1        | 3.33%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 3.33%   |
| Unknown (0x1636) RAM 5.6.5 4GB SODIMM DDR4 2667MT/s      | 1        | 3.33%   |
| Transcend RAM TS512MSH64V4H 4096MB DIMM DDR4 2400MT/s    | 1        | 3.33%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s        | 1        | 3.33%   |
| SK hynix RAM Module 4GB DIMM DDR4 2133MT/s               | 1        | 3.33%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 1        | 3.33%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 3.33%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s      | 1        | 3.33%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s  | 1        | 3.33%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s      | 1        | 3.33%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 1        | 3.33%   |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s      | 1        | 3.33%   |
| Ramaxel RAM RML1320KE48D8F-800 2GB DIMM DDR2 800MT/s     | 1        | 3.33%   |
| Nanya RAM NT4GC64B8HG0NF-DI 4GB DIMM DDR3 1600MT/s       | 1        | 3.33%   |
| Micron RAM MTA8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s  | 1        | 3.33%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 1        | 3.33%   |
| Kingston RAM 9905471-028.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 3.33%   |
| Crucial RAM CT8G4SFRA32A.C8FP 8GB SODIMM DDR4 3200MT/s   | 1        | 3.33%   |
| Crucial RAM CT25664BD160B.C8FP 2GB DIMM DDR3 1333MT/s    | 1        | 3.33%   |
| Crucial RAM CT102464BF160B.M16 8GB DIMM DDR3 1600MT/s    | 1        | 3.33%   |
| Corsair RAM CM2X1024-6400 1GB DIMM DDR2 800MT/s          | 1        | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Desktops | Percent |
|-------|----------|---------|
| DDR3  | 15       | 55.56%  |
| DDR4  | 6        | 22.22%  |
| SDRAM | 3        | 11.11%  |
| DDR2  | 2        | 7.41%   |
| DDR5  | 1        | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 16       | 61.54%  |
| SODIMM | 10       | 38.46%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 4096  | 14       | 51.85%  |
| 2048  | 5        | 18.52%  |
| 8192  | 4        | 14.81%  |
| 16384 | 2        | 7.41%   |
| 32768 | 1        | 3.7%    |
| 1024  | 1        | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 10       | 38.46%  |
| 1333    | 4        | 15.38%  |
| 3200    | 3        | 11.54%  |
| 800     | 3        | 11.54%  |
| Unknown | 2        | 7.69%   |
| 4800    | 1        | 3.85%   |
| 2667    | 1        | 3.85%   |
| 2400    | 1        | 3.85%   |
| 2133    | 1        | 3.85%   |

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
| 1     | 14       | 45.16%  |
| 0     | 14       | 45.16%  |
| 2     | 2        | 6.45%   |
| 3     | 1        | 3.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 16       | 76.19%  |
| Net/wireless             | 3        | 14.29%  |
| Network                  | 1        | 4.76%   |
| Bluetooth                | 1        | 4.76%   |

