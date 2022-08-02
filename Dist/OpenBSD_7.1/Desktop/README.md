OpenBSD 7.1 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.1.

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

Total: 38

| Vendor     | Model                       | Probe                                                     | Date         |
|------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASRock     | A320M-DVS R4.0              | [77f61a8711](https://bsd-hardware.info/?probe=77f61a8711) | Aug 01, 2022 |
| Gigabyte   | H87-HD3                     | [e6a9b0dd8b](https://bsd-hardware.info/?probe=e6a9b0dd8b) | Jul 25, 2022 |
| ASUSTek    | M4A785TD-M EVO              | [def87ec245](https://bsd-hardware.info/?probe=def87ec245) | Jul 18, 2022 |
| ASUSTek    | PRIME H410M-A               | [7b6faf5301](https://bsd-hardware.info/?probe=7b6faf5301) | Jul 14, 2022 |
| ASUSTek    | PRIME H410M-A               | [ba243fa7c4](https://bsd-hardware.info/?probe=ba243fa7c4) | Jul 09, 2022 |
| Dell       | OptiPlex 580                | [620888d077](https://bsd-hardware.info/?probe=620888d077) | Jul 02, 2022 |
| ASUSTek    | TUF Gaming B550-PLUS        | [77acc9f5cf](https://bsd-hardware.info/?probe=77acc9f5cf) | Jul 01, 2022 |
| ASUSTek    | TUF Gaming B550-PLUS        | [ffa0086c70](https://bsd-hardware.info/?probe=ffa0086c70) | Jul 01, 2022 |
| Gigabyte   | G41MT-S2                    | [0563158740](https://bsd-hardware.info/?probe=0563158740) | Jun 28, 2022 |
| MSI        | MS-7C02                     | [65265eea62](https://bsd-hardware.info/?probe=65265eea62) | Jun 20, 2022 |
| Lenovo     | ThinkPad T530 24292VG       | [6f744019ce](https://bsd-hardware.info/?probe=6f744019ce) | Jun 19, 2022 |
| Apple      | MacPro4,1                   | [65380f3847](https://bsd-hardware.info/?probe=65380f3847) | Jun 06, 2022 |
| ASUSTek    | PRIME H410M-E               | [8099e7abaf](https://bsd-hardware.info/?probe=8099e7abaf) | Jun 03, 2022 |
| MSI        | MS-6788                     | [f750cb83e3](https://bsd-hardware.info/?probe=f750cb83e3) | May 31, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [ade09344b8](https://bsd-hardware.info/?probe=ade09344b8) | May 26, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [cc37ea1b7d](https://bsd-hardware.info/?probe=cc37ea1b7d) | May 26, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [abacee12a9](https://bsd-hardware.info/?probe=abacee12a9) | May 26, 2022 |
| Unknown    | Raspberry Pi 3 Model B P... | [21fa41e4c1](https://bsd-hardware.info/?probe=21fa41e4c1) | May 26, 2022 |
| Gigabyte   | H81M-S2PV                   | [1937e77b97](https://bsd-hardware.info/?probe=1937e77b97) | May 22, 2022 |
| Biostar    | G31-M7 TE                   | [5c7af4b143](https://bsd-hardware.info/?probe=5c7af4b143) | May 21, 2022 |
| ASUSTek    | PRIME B550M-K               | [ce5ddde5ad](https://bsd-hardware.info/?probe=ce5ddde5ad) | May 18, 2022 |
| MSI        | MS-7C82                     | [2ad883afec](https://bsd-hardware.info/?probe=2ad883afec) | May 15, 2022 |
| ASUSTek    | PRIME X470-PRO              | [9f6b4f114d](https://bsd-hardware.info/?probe=9f6b4f114d) | May 11, 2022 |
| Unknown    | Raspberry Pi 4 Model B R... | [154799d7fa](https://bsd-hardware.info/?probe=154799d7fa) | May 08, 2022 |
| Intel      | Q3XXG4-P                    | [ed04988a23](https://bsd-hardware.info/?probe=ed04988a23) | May 03, 2022 |
| MSI        | MS-7C37                     | [aaab7cf22a](https://bsd-hardware.info/?probe=aaab7cf22a) | Apr 28, 2022 |
| ASUSTek    | M4A88TD-V EVO/USB3          | [12cc40cc60](https://bsd-hardware.info/?probe=12cc40cc60) | Apr 23, 2022 |
| PC Engines | APU2                        | [04a6549c99](https://bsd-hardware.info/?probe=04a6549c99) | Apr 23, 2022 |
| Intel      | DH67BL                      | [3c3c9e12da](https://bsd-hardware.info/?probe=3c3c9e12da) | Apr 22, 2022 |
| KOHJINSHA  | SH series                   | [3136a0ca03](https://bsd-hardware.info/?probe=3136a0ca03) | Apr 22, 2022 |
| Lenovo     | ThinkPad X240 20ALA0AHRT    | [062a08c811](https://bsd-hardware.info/?probe=062a08c811) | Apr 22, 2022 |
| Sony       | VPCL22Z1R                   | [f199d57905](https://bsd-hardware.info/?probe=f199d57905) | Apr 22, 2022 |
| ASUSTek    | Z170-K                      | [b16705bbbd](https://bsd-hardware.info/?probe=b16705bbbd) | Apr 22, 2022 |
| ASUSTek    | P10S-I Series               | [aca13dba36](https://bsd-hardware.info/?probe=aca13dba36) | Apr 22, 2022 |
| Dell       | G5 5090                     | [8b24170852](https://bsd-hardware.info/?probe=8b24170852) | Apr 17, 2022 |
| Lenovo     | ThinkCentre M93p 10AAS25... | [32d27b9404](https://bsd-hardware.info/?probe=32d27b9404) | Mar 19, 2022 |
| Lenovo     | ThinkCentre M93p 10AAS25... | [7361628ed9](https://bsd-hardware.info/?probe=7361628ed9) | Mar 19, 2022 |
| Unknown    | LeMaker Banana Pi           | [37e7d1912b](https://bsd-hardware.info/?probe=37e7d1912b) | Mar 05, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 28       | 77.78%  |
| arm64 | 5        | 13.89%  |
| i386  | 2        | 5.56%   |
| armv7 | 1        | 2.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 30       | 83.33%  |
| XFCE         | 4        | 11.11%  |
| GNOME        | 1        | 2.78%   |
| Console      | 1        | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 23       | 63.89%  |
| Console | 13       | 36.11%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 36       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 83.33%  |
| ru_RU   | 4        | 11.11%  |
| en_US   | 1        | 2.78%   |
| C       | 1        | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 20       | 55.56%  |
| EFI  | 16       | 44.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 36       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| MBR  | 24       | 66.67%  |
| GPT  | 12       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 10       | 27.78%  |
| Unknown             | 6        | 16.67%  |
| MSI                 | 4        | 11.11%  |
| Lenovo              | 3        | 8.33%   |
| Gigabyte Technology | 3        | 8.33%   |
| Intel               | 2        | 5.56%   |
| Dell                | 2        | 5.56%   |
| Sony                | 1        | 2.78%   |
| PC Engines          | 1        | 2.78%   |
| KOHJINSHA           | 1        | 2.78%   |
| Biostar             | 1        | 2.78%   |
| ASRock              | 1        | 2.78%   |
| Apple               | 1        | 2.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Unknown                            | 6        | 16.67%  |
| ASUS PRIME H410M-A                 | 2        | 5.56%   |
| Sony VPCL22Z1R                     | 1        | 2.78%   |
| PC Engines APU2                    | 1        | 2.78%   |
| MSI MS-7C82                        | 1        | 2.78%   |
| MSI MS-7C37                        | 1        | 2.78%   |
| MSI MS-7C02                        | 1        | 2.78%   |
| MSI MS-6788                        | 1        | 2.78%   |
| Lenovo ThinkPad X240 20ALA0AHRT    | 1        | 2.78%   |
| Lenovo ThinkPad T530 24292VG       | 1        | 2.78%   |
| Lenovo ThinkCentre M93p 10AAS25M00 | 1        | 2.78%   |
| KOHJINSHA SH series                | 1        | 2.78%   |
| Intel Q3XXG4-P                     | 1        | 2.78%   |
| Intel DH67BL                       | 1        | 2.78%   |
| Gigabyte H87-HD3                   | 1        | 2.78%   |
| Gigabyte H81M-S2PV                 | 1        | 2.78%   |
| Gigabyte G41MT-S2                  | 1        | 2.78%   |
| Dell OptiPlex 580                  | 1        | 2.78%   |
| Dell G5 5090                       | 1        | 2.78%   |
| Biostar G31-M7 TE                  | 1        | 2.78%   |
| ASUS Z170-K                        | 1        | 2.78%   |
| ASUS TUF Gaming B550-PLUS          | 1        | 2.78%   |
| ASUS PRIME X470-PRO                | 1        | 2.78%   |
| ASUS PRIME H410M-E                 | 1        | 2.78%   |
| ASUS PRIME B550M-K                 | 1        | 2.78%   |
| ASUS P10S-I Series                 | 1        | 2.78%   |
| ASUS M4A88TD-V EVO/USB3            | 1        | 2.78%   |
| ASUS M4A785TD-M EVO                | 1        | 2.78%   |
| ASRock A320M-DVS R4.0              | 1        | 2.78%   |
| Apple MacPro4,1                    | 1        | 2.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Unknown            | 6        | 16.67%  |
| ASUS PRIME         | 5        | 13.89%  |
| Lenovo ThinkPad    | 2        | 5.56%   |
| Sony VPCL22Z1R     | 1        | 2.78%   |
| PC Engines APU2    | 1        | 2.78%   |
| MSI MS-7C82        | 1        | 2.78%   |
| MSI MS-7C37        | 1        | 2.78%   |
| MSI MS-7C02        | 1        | 2.78%   |
| MSI MS-6788        | 1        | 2.78%   |
| Lenovo ThinkCentre | 1        | 2.78%   |
| KOHJINSHA SH       | 1        | 2.78%   |
| Intel Q3XXG4-P     | 1        | 2.78%   |
| Intel DH67BL       | 1        | 2.78%   |
| Gigabyte H87-HD3   | 1        | 2.78%   |
| Gigabyte H81M-S2PV | 1        | 2.78%   |
| Gigabyte G41MT-S2  | 1        | 2.78%   |
| Dell OptiPlex      | 1        | 2.78%   |
| Dell G5            | 1        | 2.78%   |
| Biostar G31-M7     | 1        | 2.78%   |
| ASUS Z170-K        | 1        | 2.78%   |
| ASUS TUF           | 1        | 2.78%   |
| ASUS P10S-I        | 1        | 2.78%   |
| ASUS M4A88TD-V     | 1        | 2.78%   |
| ASUS M4A785TD-M    | 1        | 2.78%   |
| ASRock A320M-DVS   | 1        | 2.78%   |
| Apple MacPro4      | 1        | 2.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 7        | 19.44%  |
| 2021    | 4        | 11.11%  |
| 2020    | 4        | 11.11%  |
| 2010    | 4        | 11.11%  |
| 2019    | 3        | 8.33%   |
| 2018    | 3        | 8.33%   |
| 2022    | 2        | 5.56%   |
| 2016    | 2        | 5.56%   |
| 2015    | 2        | 5.56%   |
| 2014    | 1        | 2.78%   |
| 2012    | 1        | 2.78%   |
| 2011    | 1        | 2.78%   |
| 2009    | 1        | 2.78%   |
| 2007    | 1        | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 36       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 35       | 97.22%  |
| Yes  | 1        | 2.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 10       | 27.78%  |
| 4.01-8.0    | 8        | 22.22%  |
| 16.01-24.0  | 8        | 22.22%  |
| 3.01-4.0    | 2        | 5.56%   |
| 2.01-3.0    | 2        | 5.56%   |
| 1.01-2.0    | 2        | 5.56%   |
| 0.51-1.0    | 2        | 5.56%   |
| 24.01-32.0  | 1        | 2.78%   |
| 64.01-256.0 | 1        | 2.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 32       | 88.89%  |
| 0        | 2        | 5.56%   |
| 4.01-8.0 | 1        | 2.78%   |
| 0.51-1.0 | 1        | 2.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 19       | 52.78%  |
| 4      | 7        | 19.44%  |
| 2      | 4        | 11.11%  |
| 3      | 3        | 8.33%   |
| 8      | 1        | 2.78%   |
| 6      | 1        | 2.78%   |
| 5      | 1        | 2.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 36       | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 29       | 80.56%  |
| No        | 7        | 19.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 72.22%  |
| Yes       | 10       | 27.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 83.33%  |
| Yes       | 6        | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 10       | 27.78%  |
| Italy       | 6        | 16.67%  |
| Netherlands | 4        | 11.11%  |
| USA         | 3        | 8.33%   |
| Germany     | 2        | 5.56%   |
| Austria     | 2        | 5.56%   |
| UK          | 1        | 2.78%   |
| Poland      | 1        | 2.78%   |
| Norway      | 1        | 2.78%   |
| Lithuania   | 1        | 2.78%   |
| India       | 1        | 2.78%   |
| Egypt       | 1        | 2.78%   |
| Czechia     | 1        | 2.78%   |
| Canada      | 1        | 2.78%   |
| Argentina   | 1        | 2.78%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Desktops | Percent |
|--------------------|----------|---------|
| Poortugaal         | 4        | 11.11%  |
| Milan              | 4        | 11.11%  |
| Vladivostok        | 3        | 8.33%   |
| Vienna             | 2        | 5.56%   |
| Wolverhampton      | 1        | 2.78%   |
| Tambov             | 1        | 2.78%   |
| St. Albert         | 1        | 2.78%   |
| Reutov             | 1        | 2.78%   |
| Pozzuolo Martesana | 1        | 2.78%   |
| Oslo               | 1        | 2.78%   |
| Orenburg           | 1        | 2.78%   |
| Oakland            | 1        | 2.78%   |
| Nuremberg          | 1        | 2.78%   |
| Moscow             | 1        | 2.78%   |
| Memmingen          | 1        | 2.78%   |
| Krasnodar          | 1        | 2.78%   |
| Kolomna            | 1        | 2.78%   |
| Gianico            | 1        | 2.78%   |
| Gdansk             | 1        | 2.78%   |
| Delhi              | 1        | 2.78%   |
| Columbus           | 1        | 2.78%   |
| Cherepovets        | 1        | 2.78%   |
| Český Těšín   | 1        | 2.78%   |
| Cairo              | 1        | 2.78%   |
| Buenos Aires       | 1        | 2.78%   |
| Brooklyn           | 1        | 2.78%   |
| Alytus             | 1        | 2.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 11     | 16.67%  |
| Seagate             | 8        | 12     | 13.33%  |
| NVMe                | 8        | 10     | 13.33%  |
| Samsung Electronics | 7        | 12     | 11.67%  |
| Toshiba             | 4        | 8      | 6.67%   |
| Hitachi             | 3        | 4      | 5%      |
| Crucial             | 3        | 3      | 5%      |
| OPENBSD             | 2        | 2      | 3.33%   |
| Kingston            | 2        | 2      | 3.33%   |
| Corsair             | 2        | 2      | 3.33%   |
| XPG                 | 1        | 1      | 1.67%   |
| StoreJet            | 1        | 1      | 1.67%   |
| SanDisk             | 1        | 1      | 1.67%   |
| PNY                 | 1        | 1      | 1.67%   |
| OCZ                 | 1        | 1      | 1.67%   |
| KingSpec            | 1        | 1      | 1.67%   |
| Intel               | 1        | 1      | 1.67%   |
| Hoodisk             | 1        | 1      | 1.67%   |
| HGST                | 1        | 1      | 1.67%   |
| Generic             | 1        | 1      | 1.67%   |
| AMD                 | 1        | 1      | 1.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Toshiba HDWG440 4TB             | 2        | 3.13%   |
| Seagate ST1000DM010-2EP102 1TB  | 2        | 3.13%   |
| OPENBSD SR RAID 1 752GB         | 2        | 3.13%   |
| NVMe Samsung SSD 980 1TB        | 2        | 3.13%   |
| XPG SX950U 240GB                | 1        | 1.56%   |
| WDC WD800JD-60LSA5 80GB         | 1        | 1.56%   |
| WDC WD6400AARS-00Y5B1 640GB     | 1        | 1.56%   |
| WDC WD5003AZEX-00K1GA0 500GB    | 1        | 1.56%   |
| WDC WD5003ABYX-01WERA2 500GB    | 1        | 1.56%   |
| WDC WD5000AZLX-00K2TA0 500GB    | 1        | 1.56%   |
| WDC WD5000AAKX-60U6AA0 500GB    | 1        | 1.56%   |
| WDC WD40EFZX-68AWUN0 4TB        | 1        | 1.56%   |
| WDC WD20PURX-64P6ZY0 2TB        | 1        | 1.56%   |
| WDC WD10JPVT-75A1YT0 1TB        | 1        | 1.56%   |
| WDC WD10EZEX-00MFCA0 1TB        | 1        | 1.56%   |
| Toshiba MG06ACA800E 8TB         | 1        | 1.56%   |
| Toshiba DT01ACA050 500GB        | 1        | 1.56%   |
| StoreJet Transcend 120GB        | 1        | 1.56%   |
| Seagate ST380815AS 80GB         | 1        | 1.56%   |
| Seagate ST3750640NS 752GB       | 1        | 1.56%   |
| Seagate ST3250318AS 250GB       | 1        | 1.56%   |
| Seagate ST3250310AS 250GB       | 1        | 1.56%   |
| Seagate ST3160212SCE 160GB      | 1        | 1.56%   |
| Seagate ST250DM000-1BD141 250GB | 1        | 1.56%   |
| Seagate ST2000DM006-2DM164 2TB  | 1        | 1.56%   |
| Seagate ST1000VX000-1CU162 1TB  | 1        | 1.56%   |
| Seagate Expansion 320GB         | 1        | 1.56%   |
| SanDisk Extreme Pro 128GB       | 1        | 1.56%   |
| Samsung SSD 870 QVO 2TB         | 1        | 1.56%   |
| Samsung SSD 860 EVO 500GB       | 1        | 1.56%   |
| Samsung SSD 860 EVO 250GB       | 1        | 1.56%   |
| Samsung Portable SSD T3 250GB   | 1        | 1.56%   |
| Samsung HD753LJ 752GB           | 1        | 1.56%   |
| Samsung HD161HJ 160GB           | 1        | 1.56%   |
| Samsung Flash Drive FIT 32GB    | 1        | 1.56%   |
| PNY CS900 120GB SSD             | 1        | 1.56%   |
| OCZ VERTEX3 120GB               | 1        | 1.56%   |
| NVMe WDS100T3X0C-00SJ 1TB       | 1        | 1.56%   |
| NVMe WDC WDS500G2B0C- 500GB     | 1        | 1.56%   |
| NVMe TOSHIBA-RC100 240GB        | 1        | 1.56%   |
| NVMe Samsung SSD 970 250GB      | 1        | 1.56%   |
| NVMe PC SN520 WD 256GB          | 1        | 1.56%   |
| NVMe KIOXIA-EXCERIA S 500GB     | 1        | 1.56%   |
| NVMe ADATA SX8200PNP 512GB      | 1        | 1.56%   |
| Kingston SMS200S330G 32GB       | 1        | 1.56%   |
| Kingston SEDC500M480G 480GB     | 1        | 1.56%   |
| KingSpec NT-512 512GB           | 1        | 1.56%   |
| Intel SSDSC2BF180A4L 180GB      | 1        | 1.56%   |
| Hoodisk SSD 32GB                | 1        | 1.56%   |
| Hitachi HUA723020ALA640 2TB     | 1        | 1.56%   |
| Hitachi HTS541612J9AT00 120GB   | 1        | 1.56%   |
| Hitachi HDE721064SLA360 640GB   | 1        | 1.56%   |
| HGST HUS724020ALA640 2TB        | 1        | 1.56%   |
| Generic Flash Disk 2GB          | 1        | 1.56%   |
| Crucial M4-CT128M4SSD2 128GB    | 1        | 1.56%   |
| Crucial CT2000MX500SSD1 2TB     | 1        | 1.56%   |
| Crucial CT1000MX500SSD1 1TB     | 1        | 1.56%   |
| Corsair Voyager SliderX1 32GB   | 1        | 1.56%   |
| Corsair FORCE LX SSD 256GB      | 1        | 1.56%   |
| AMD R5SL120G 120GB              | 1        | 1.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 10       | 11     | 27.03%  |
| Seagate             | 8        | 12     | 21.62%  |
| Toshiba             | 4        | 8      | 10.81%  |
| NVMe                | 4        | 5      | 10.81%  |
| Samsung Electronics | 3        | 3      | 8.11%   |
| Hitachi             | 3        | 4      | 8.11%   |
| OPENBSD             | 2        | 2      | 5.41%   |
| StoreJet            | 1        | 1      | 2.7%    |
| HGST                | 1        | 1      | 2.7%    |
| Generic             | 1        | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 4        | 9      | 18.18%  |
| NVMe                | 3        | 4      | 13.64%  |
| Crucial             | 3        | 3      | 13.64%  |
| Kingston            | 2        | 2      | 9.09%   |
| Corsair             | 2        | 2      | 9.09%   |
| XPG                 | 1        | 1      | 4.55%   |
| SanDisk             | 1        | 1      | 4.55%   |
| PNY                 | 1        | 1      | 4.55%   |
| OCZ                 | 1        | 1      | 4.55%   |
| KingSpec            | 1        | 1      | 4.55%   |
| Intel               | 1        | 1      | 4.55%   |
| Hoodisk             | 1        | 1      | 4.55%   |
| AMD                 | 1        | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 48     | 53.85%  |
| SSD  | 17       | 28     | 43.59%  |
| NVMe | 1        | 1      | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 33       | 76     | 97.06%  |
| NVMe | 1        | 1      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 26       | 37     | 54.17%  |
| 0.51-1.0   | 14       | 19     | 29.17%  |
| 1.01-2.0   | 4        | 11     | 8.33%   |
| 3.01-4.0   | 3        | 6      | 6.25%   |
| 4.01-10.0  | 1        | 3      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 10       | 27.78%  |
| 251-500        | 9        | 25%     |
| 21-50          | 6        | 16.67%  |
| 51-100         | 4        | 11.11%  |
| 1-20           | 3        | 8.33%   |
| More than 3000 | 2        | 5.56%   |
| 501-1000       | 2        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 32       | 88.89%  |
| 51-100    | 2        | 5.56%   |
| 21-50     | 1        | 2.78%   |
| 2001-3000 | 1        | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| XPG SX950U 240GB                  | 1        | 1      | 10%     |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 1      | 10%     |
| Seagate ST380815AS 80GB           | 1        | 1      | 10%     |
| Seagate ST3750640NS 752GB         | 1        | 2      | 10%     |
| Seagate ST3160212SCE 160GB        | 1        | 1      | 10%     |
| Seagate ST250DM000-1BD141 250GB   | 1        | 1      | 10%     |
| Seagate ST2000DM006-2DM164 2TB    | 1        | 1      | 10%     |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 10%     |
| Samsung Electronics HD161HJ 160GB | 1        | 1      | 10%     |
| OCZ VERTEX3 120GB                 | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 6      | 44.44%  |
| Samsung Electronics | 2        | 2      | 22.22%  |
| XPG                 | 1        | 1      | 11.11%  |
| WDC                 | 1        | 1      | 11.11%  |
| OCZ                 | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 6      | 57.14%  |
| Samsung Electronics | 2        | 2      | 28.57%  |
| WDC                 | 1        | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 9      | 77.78%  |
| SSD  | 2        | 2      | 22.22%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                       | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC WD6400AARS-00Y5B1 640GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| WDC    | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 26       | 52     | 57.78%  |
| Detected | 10       | 13     | 22.22%  |
| Malfunc  | 8        | 11     | 17.78%  |
| Failed   | 1        | 1      | 2.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 20       | 48.78%  |
| AMD                      | 10       | 24.39%  |
| Samsung Electronics      | 3        | 7.32%   |
| SanDisk                  | 2        | 4.88%   |
| VIA Technologies         | 1        | 2.44%   |
| Toshiba                  | 1        | 2.44%   |
| Marvell Technology Group | 1        | 2.44%   |
| KIOXIA                   | 1        | 2.44%   |
| ASMedia Technology       | 1        | 2.44%   |
| ADATA Technology         | 1        | 2.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4        | 8.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 6.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 6.38%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 3        | 6.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2        | 4.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 4.26%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 4.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2        | 4.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 4.26%   |
| AMD 500 Series Chipset SATA Controller                                         | 2        | 4.26%   |
| AMD 400 Series Chipset SATA Controller                                         | 2        | 4.26%   |
| VIA VT6415 PATA IDE Host Controller                                            | 1        | 2.13%   |
| Toshiba BG3 NVMe SSD Controller                                                | 1        | 2.13%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1        | 2.13%   |
| SanDisk unknown                                                                | 1        | 2.13%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1        | 2.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 2.13%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 1        | 2.13%   |
| KIOXIA NVMe SSD                                                                | 1        | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1        | 2.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 2.13%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 2.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 1        | 2.13%   |
| Intel 82801EB (ICH5) SATA Controller                                           | 1        | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 2.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1        | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 1        | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 2.13%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1        | 2.13%   |
| AMD FCH SATA Controller D                                                      | 1        | 2.13%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 2.13%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 26       | 63.41%  |
| NVMe | 8        | 19.51%  |
| IDE  | 7        | 17.07%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 20       | 55.56%  |
| AMD    | 10       | 27.78%  |
| ARM    | 6        | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| ARM Cortex-A72 r0p3                                       | 4        | 11.11%  |
| Intel Core i3-10100F CPU @ 3.60GHz                        | 2        | 5.56%   |
| Intel Xeon CPU E5520 @ 2.27GHz                            | 1        | 2.78%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz                       | 1        | 2.78%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz               | 1        | 2.78%   |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class)    | 1        | 2.78%   |
| Intel Genuine processor 600MHz ("GenuineIntel" 686-class) | 1        | 2.78%   |
| Intel Core i7-9700K CPU @ 3.60GHz                         | 1        | 2.78%   |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 1        | 2.78%   |
| Intel Core i7-4790 CPU @ 3.60GHz                          | 1        | 2.78%   |
| Intel Core i7-3610QM CPU @ 2.30GHz                        | 1        | 2.78%   |
| Intel Core i7-2670QM CPU @ 2.20GHz                        | 1        | 2.78%   |
| Intel Core i5-4570T CPU @ 2.90GHz                         | 1        | 2.78%   |
| Intel Core i5-10400F CPU @ 2.90GHz                        | 1        | 2.78%   |
| Intel Core i3-5010U CPU @ 2.10GHz                         | 1        | 2.78%   |
| Intel Core i3-4010U CPU @ 1.70GHz                         | 1        | 2.78%   |
| Intel Core i3-3225 CPU @ 3.30GHz                          | 1        | 2.78%   |
| Intel Core i3-10100 CPU @ 3.60GHz                         | 1        | 2.78%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz                     | 1        | 2.78%   |
| Intel Celeron CPU G1820 @ 2.70GHz                         | 1        | 2.78%   |
| ARM Cortex-A7 r0p4                                        | 1        | 2.78%   |
| ARM Cortex-A53 r0p4                                       | 1        | 2.78%   |
| AMD Ryzen 9 5950X 16-Core Processor                       | 1        | 2.78%   |
| AMD Ryzen 7 5800X 8-Core Processor                        | 1        | 2.78%   |
| AMD Ryzen 5 5600X 6-Core Processor                        | 1        | 2.78%   |
| AMD Ryzen 5 3600 6-Core Processor                         | 1        | 2.78%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics               | 1        | 2.78%   |
| AMD Phenom II X4 965 Processor                            | 1        | 2.78%   |
| AMD GX-412TC SOC                                          | 1        | 2.78%   |
| AMD Athlon II X4 640 Processor                            | 1        | 2.78%   |
| AMD Athlon II X2 B26 Processor                            | 1        | 2.78%   |
| AMD Athlon 3000G with Radeon Vega Graphics                | 1        | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i3           | 6        | 16.67%  |
| ARM Cortex              | 6        | 16.67%  |
| Intel Core i7           | 5        | 13.89%  |
| Intel Xeon              | 2        | 5.56%   |
| Intel Core i5           | 2        | 5.56%   |
| AMD Ryzen 5             | 2        | 5.56%   |
| Intel Pentium Dual-Core | 1        | 2.78%   |
| Intel Pentium 4         | 1        | 2.78%   |
| Intel Genuine           | 1        | 2.78%   |
| Intel Core 2 Quad       | 1        | 2.78%   |
| Intel Celeron           | 1        | 2.78%   |
| AMD Ryzen 9             | 1        | 2.78%   |
| AMD Ryzen 7             | 1        | 2.78%   |
| AMD Ryzen 3             | 1        | 2.78%   |
| AMD Phenom II X4        | 1        | 2.78%   |
| AMD GX                  | 1        | 2.78%   |
| AMD Athlon II X4        | 1        | 2.78%   |
| AMD Athlon II X2        | 1        | 2.78%   |
| AMD Athlon              | 1        | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 13       | 36.11%  |
| Unknown | 10       | 27.78%  |
| 2       | 6        | 16.67%  |
| 1       | 3        | 8.33%   |
| 8       | 2        | 5.56%   |
| 32      | 1        | 2.78%   |
| 12      | 1        | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 22       | 61.11%  |
| Unknown | 13       | 36.11%  |
| 2       | 1        | 2.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 13       | 36.11%  |
| 2       | 12       | 33.33%  |
| 1       | 11       | 30.56%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 8        | 22.22%  |
| Haswell     | 4        | 11.11%  |
| K10         | 3        | 8.33%   |
| CometLake   | 3        | 8.33%   |
| Zen 3       | 2        | 5.56%   |
| Skylake     | 2        | 5.56%   |
| Penryn      | 2        | 5.56%   |
| IvyBridge   | 2        | 5.56%   |
| Zen+        | 1        | 2.78%   |
| Zen 2       | 1        | 2.78%   |
| Zen         | 1        | 2.78%   |
| SandyBridge | 1        | 2.78%   |
| Puma        | 1        | 2.78%   |
| P6          | 1        | 2.78%   |
| NetBurst    | 1        | 2.78%   |
| Nehalem     | 1        | 2.78%   |
| KabyLake    | 1        | 2.78%   |
| Broadwell   | 1        | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| AMD               | 15       | 50%     |
| Intel             | 9        | 30%     |
| Nvidia            | 5        | 16.67%  |
| ASPEED Technology | 1        | 3.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 3        | 9.68%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                            | 3        | 9.68%   |
| AMD RS880 [Radeon HD 4200]                                                    | 2        | 6.45%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                       | 2        | 6.45%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                              | 2        | 6.45%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                         | 1        | 3.23%   |
| Nvidia GK208B [GeForce GT 710]                                                | 1        | 3.23%   |
| Nvidia GF108M [NVS 5400M]                                                     | 1        | 3.23%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1        | 3.23%   |
| Nvidia G96C [GeForce 9500 GT]                                                 | 1        | 3.23%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1        | 3.23%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 1        | 3.23%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 1        | 3.23%   |
| Intel HD Graphics 5500                                                        | 1        | 3.23%   |
| Intel HD Graphics 530                                                         | 1        | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 1        | 3.23%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                      | 1        | 3.23%   |
| ASPEED Technology ASPEED Graphics Family                                      | 1        | 3.23%   |
| AMD RV770 [Radeon HD 4850]                                                    | 1        | 3.23%   |
| AMD RV710/M92 [Mobility Radeon HD 4350/4550]                                  | 1        | 3.23%   |
| AMD RS880 [Radeon HD 4250]                                                    | 1        | 3.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1        | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1        | 3.23%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                | 1        | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x AMD     | 14       | 38.89%  |
| Other       | 7        | 19.44%  |
| 1 x Intel   | 7        | 19.44%  |
| 1 x Nvidia  | 5        | 13.89%  |
| 2 x Intel   | 1        | 2.78%   |
| Intel + AMD | 1        | 2.78%   |
| 1 x ASPEED  | 1        | 2.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 25       | 69.44%  |
| Unknown | 11       | 30.56%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Philips              | 6        | 35.29%  |
| Samsung Electronics  | 2        | 11.76%  |
| Dell                 | 2        | 11.76%  |
| ViewSonic            | 1        | 5.88%   |
| MSI                  | 1        | 5.88%   |
| Lenovo               | 1        | 5.88%   |
| InfoVision           | 1        | 5.88%   |
| Goldstar             | 1        | 5.88%   |
| Ancor Communications | 1        | 5.88%   |
| Acer                 | 1        | 5.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                  | 6        | 35.29%  |
| ViewSonic LCD Monitor VSCC42B 1920x1080 480x270mm 21.7-inch            | 1        | 5.88%   |
| Samsung Electronics SyncMaster SAM03CF 1280x1024 340x270mm 17.1-inch   | 1        | 5.88%   |
| Samsung Electronics LCD Monitor SAM7004 3840x2160 1210x680mm 54.6-inch | 1        | 5.88%   |
| MSI MAG241C MSI3EA2 1920x1080 520x290mm 23.4-inch                      | 1        | 5.88%   |
| Lenovo LEN S24e-10 LEN61CA 1920x1080 530x300mm 24.0-inch               | 1        | 5.88%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch            | 1        | 5.88%   |
| Goldstar L1752T GSM4434 1280x1024 340x270mm 17.1-inch                  | 1        | 5.88%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                       | 1        | 5.88%   |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                      | 1        | 5.88%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch   | 1        | 5.88%   |
| Acer XZ342CK ACR078B 3440x1440 800x330mm 34.1-inch                     | 1        | 5.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 9        | 52.94%  |
| 1366x768 (WXGA)  | 2        | 11.76%  |
| 1280x1024 (SXGA) | 2        | 11.76%  |
| 3840x2160 (4K)   | 1        | 5.88%   |
| 3440x1440        | 1        | 5.88%   |
| 1600x1200        | 1        | 5.88%   |
| 1440x900 (WXGA+) | 1        | 5.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 21     | 7        | 41.18%  |
| 17     | 2        | 11.76%  |
| 54     | 1        | 5.88%   |
| 34     | 1        | 5.88%   |
| 24     | 1        | 5.88%   |
| 23     | 1        | 5.88%   |
| 20     | 1        | 5.88%   |
| 19     | 1        | 5.88%   |
| 18     | 1        | 5.88%   |
| 12     | 1        | 5.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 10       | 58.82%  |
| 501-600     | 2        | 11.76%  |
| 301-350     | 2        | 11.76%  |
| 701-800     | 1        | 5.88%   |
| 201-300     | 1        | 5.88%   |
| 1001-1500   | 1        | 5.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 12       | 70.59%  |
| 5/4   | 2        | 11.76%  |
| 4/3   | 1        | 5.88%   |
| 21/9  | 1        | 5.88%   |
| 16/10 | 1        | 5.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 9        | 52.94%  |
| 141-150        | 3        | 17.65%  |
| 151-200        | 2        | 11.76%  |
| More than 1000 | 1        | 5.88%   |
| 61-70          | 1        | 5.88%   |
| 351-500        | 1        | 5.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 101-120 | 8        | 50%     |
| 51-100  | 7        | 43.75%  |
| 121-160 | 1        | 6.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 19       | 52.78%  |
| 0     | 16       | 44.44%  |
| 2     | 1        | 2.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 19       | 48.72%  |
| Intel                             | 12       | 30.77%  |
| Qualcomm Atheros Communications   | 2        | 5.13%   |
| Qualcomm Atheros                  | 2        | 5.13%   |
| Qcom                              | 1        | 2.56%   |
| Ericsson Business Mobile Networks | 1        | 2.56%   |
| Broadcom                          | 1        | 2.56%   |
| AVM                               | 1        | 2.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 13       | 28.89%  |
| Intel 82574L Gigabit Network Connection                                       | 3        | 6.67%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 4.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 4.44%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2        | 4.44%   |
| Intel I211 Gigabit Network Connection                                         | 2        | 4.44%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 4.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 1        | 2.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 2.22%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1        | 2.22%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 2.22%   |
| Qcom RT73 USB Wireless LAN Card                                               | 1        | 2.22%   |
| Intel Wireless 7260                                                           | 1        | 2.22%   |
| Intel Wi-Fi 6 AX200                                                           | 1        | 2.22%   |
| Intel Ethernet Connection I218-LM                                             | 1        | 2.22%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1        | 2.22%   |
| Intel Centrino Advanced-N 6235                                                | 1        | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 1        | 2.22%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 2.22%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 2.22%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module            | 1        | 2.22%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1        | 2.22%   |
| AVM A1 ISDN [Fritz]                                                           | 1        | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 4        | 40%     |
| Qualcomm Atheros Communications | 2        | 20%     |
| Realtek Semiconductor           | 1        | 10%     |
| Qualcomm Atheros                | 1        | 10%     |
| Qcom                            | 1        | 10%     |
| Broadcom                        | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Qualcomm Atheros AR9271 802.11n                                | 2        | 20%     |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 10%     |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 10%     |
| Qcom RT73 USB Wireless LAN Card                                | 1        | 10%     |
| Intel Wireless 7260                                            | 1        | 10%     |
| Intel Wi-Fi 6 AX200                                            | 1        | 10%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 10%     |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1        | 10%     |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 61.29%  |
| Intel                 | 11       | 35.48%  |
| Qualcomm Atheros      | 1        | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 13       | 40.63%  |
| Intel 82574L Gigabit Network Connection                                       | 3        | 9.38%   |
| Realtek RTL8125 2.5GbE Controller                                             | 2        | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 6.25%   |
| Intel I211 Gigabit Network Connection                                         | 2        | 6.25%   |
| Intel I210 Gigabit Network Connection                                         | 2        | 6.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 3.13%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                              | 1        | 3.13%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                 | 1        | 3.13%   |
| Intel Ethernet Connection I218-LM                                             | 1        | 3.13%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 3.13%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 3.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 1        | 3.13%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 3.13%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 29       | 69.05%  |
| WiFi     | 10       | 23.81%  |
| Unknown  | 2        | 4.76%   |
| Modem    | 1        | 2.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 22       | 78.57%  |
| WiFi     | 6        | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 15       | 41.67%  |
| 2     | 9        | 25%     |
| 0     | 7        | 19.44%  |
| 3     | 4        | 11.11%  |
| 4     | 1        | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 36       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 4        | 66.67%  |
| Foxconn / Hon Hai | 1        | 16.67%  |
| Apple             | 1        | 16.67%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                            | 1        | 16.67%  |
| Intel Centrino Bluetooth Wireless Transceiver               | 1        | 16.67%  |
| Intel Bluetooth wireless interface                          | 1        | 16.67%  |
| Intel AX200 Bluetooth                                       | 1        | 16.67%  |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1        | 16.67%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 16.67%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 17       | 44.74%  |
| AMD                 | 16       | 42.11%  |
| Nvidia              | 3        | 7.89%   |
| Creative Labs       | 1        | 2.63%   |
| C-Media Electronics | 1        | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 4        | 8%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3        | 6%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 6%      |
| Intel Comet Lake PCH-V cAVS                                                       | 3        | 6%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 6%      |
| AMD SBx00 Azalia (Intel HDA)                                                      | 3        | 6%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 6%      |
| Nvidia GF108 High Definition Audio Controller                                     | 2        | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 4%      |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 2        | 4%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 4%      |
| AMD Navi 10 HDMI Audio                                                            | 2        | 4%      |
| AMD Family 17h/19h HD Audio Controller                                            | 2        | 4%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 4%      |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 1        | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 2%      |
| Intel Haswell-ULT HD Audio Controller                                             | 1        | 2%      |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 2%      |
| Intel Broadwell-U Audio Controller                                                | 1        | 2%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 2%      |
| Intel 8 Series HD Audio Controller                                                | 1        | 2%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 1        | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 1        | 2%      |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                | 1        | 2%      |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 1        | 2%      |
| AMD RV770 HDMI Audio [Radeon HD 4850/4870]                                        | 1        | 2%      |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 1        | 2%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 1        | 2%      |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Kingston | 1        | 50%     |
| Corsair  | 1        | 50%     |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 2400MT/s | 1        | 50%     |
| Corsair RAM CML16GX3M2A1600C9 8GB DIMM DDR3 1600MT/s  | 1        | 50%     |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 1        | 50%     |
| DDR3 | 1        | 50%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 2        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 32768 | 1        | 50%     |
| 8192  | 1        | 50%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 2400  | 1        | 50%     |
| 1600  | 1        | 50%     |

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


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Ricoh               | 1        | 50%     |
| Chicony Electronics | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Ricoh USB2.0 Camera                  | 1        | 50%     |
| Chicony Integrated Camera [ThinkPad] | 1        | 50%     |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 100%    |

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
| 0     | 15       | 41.67%  |
| 1     | 14       | 38.89%  |
| 2     | 5        | 13.89%  |
| 3     | 2        | 5.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 15       | 50%     |
| Graphics card            | 5        | 16.67%  |
| Firewire controller      | 5        | 16.67%  |
| Net/wireless             | 2        | 6.67%   |
| Storage                  | 1        | 3.33%   |
| Sound                    | 1        | 3.33%   |
| Network                  | 1        | 3.33%   |

