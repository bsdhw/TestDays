OpenBSD 7.4 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for OpenBSD 7.4.

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

Total: 32

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | OptiPlex 9010               | [b80c6041c4](https://bsd-hardware.info/?probe=b80c6041c4) | Mar 15, 2025 |
| ASRock        | Z77 Pro4                    | [f4a2218557](https://bsd-hardware.info/?probe=f4a2218557) | Feb 08, 2025 |
| FUJI wortm... | D1547                       | [b0c75a2f48](https://bsd-hardware.info/?probe=b0c75a2f48) | Jul 01, 2024 |
| Dell          | Vostro 3268                 | [3492b3ebb5](https://bsd-hardware.info/?probe=3492b3ebb5) | Mar 31, 2024 |
| ASUSTek       | PRIME B550M-A (WI-FI)       | [feb3803dbc](https://bsd-hardware.info/?probe=feb3803dbc) | Mar 24, 2024 |
| Dell          | Inspiron 5521               | [15446ac441](https://bsd-hardware.info/?probe=15446ac441) | Mar 24, 2024 |
| Sun           | SUNW,Ultra-1                | [33ed69952b](https://bsd-hardware.info/?probe=33ed69952b) | Mar 17, 2024 |
| HP            | ProLiant ML370 G4           | [e3d8ea32d4](https://bsd-hardware.info/?probe=e3d8ea32d4) | Mar 13, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS (W... | [9015dcf1b5](https://bsd-hardware.info/?probe=9015dcf1b5) | Mar 12, 2024 |
| Lenovo        | ThinkCentre M75n 11BXS00... | [6ed6f9c86f](https://bsd-hardware.info/?probe=6ed6f9c86f) | Mar 09, 2024 |
| Biostar       | B450NH                      | [9f4dedfcd6](https://bsd-hardware.info/?probe=9f4dedfcd6) | Feb 17, 2024 |
| Lenovo        | ThinkCentre M91p 7052C1G    | [3aeb926332](https://bsd-hardware.info/?probe=3aeb926332) | Feb 08, 2024 |
| MSI           | MS-7D15                     | [a22ee27a4a](https://bsd-hardware.info/?probe=a22ee27a4a) | Feb 03, 2024 |
| MSI           | MS-7D15                     | [476be56dc7](https://bsd-hardware.info/?probe=476be56dc7) | Feb 03, 2024 |
| Gigabyte      | Z690 UD DDR4                | [f6f19ac329](https://bsd-hardware.info/?probe=f6f19ac329) | Feb 02, 2024 |
| AZW           | MINI S                      | [99c79c2cc8](https://bsd-hardware.info/?probe=99c79c2cc8) | Jan 30, 2024 |
| IBM           | 830381U                     | [e44647b8cd](https://bsd-hardware.info/?probe=e44647b8cd) | Jan 20, 2024 |
| Microsoft     | Windows Dev Kit 2023        | [2cd25bfacf](https://bsd-hardware.info/?probe=2cd25bfacf) | Jan 19, 2024 |
| HP            | s5-1210br                   | [9ce94bc2b7](https://bsd-hardware.info/?probe=9ce94bc2b7) | Jan 19, 2024 |
| Unknown       | Unknown                     | [2a34bc9613](https://bsd-hardware.info/?probe=2a34bc9613) | Nov 28, 2023 |
| AZW           | SER                         | [48a259ae28](https://bsd-hardware.info/?probe=48a259ae28) | Nov 28, 2023 |
| Lenovo        | ThinkCentre M90n-1 11AHS... | [eca5b59407](https://bsd-hardware.info/?probe=eca5b59407) | Nov 23, 2023 |
| Lenovo        | ThinkCentre M720s 10SUSB... | [a44a9f3526](https://bsd-hardware.info/?probe=a44a9f3526) | Nov 23, 2023 |
| HP            | Compaq CQ45                 | [4f3c176253](https://bsd-hardware.info/?probe=4f3c176253) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [700d52c2dd](https://bsd-hardware.info/?probe=700d52c2dd) | Nov 07, 2023 |
| Apple         | MacPro4,1                   | [5960492992](https://bsd-hardware.info/?probe=5960492992) | Nov 07, 2023 |
| Intel         | DCP847SKE                   | [3b5b83d95f](https://bsd-hardware.info/?probe=3b5b83d95f) | Oct 30, 2023 |
| ASUSTek       | MINIPC PN53-G               | [57d8823b4b](https://bsd-hardware.info/?probe=57d8823b4b) | Oct 28, 2023 |
| Dell          | PowerEdge T110 II           | [f93395bc11](https://bsd-hardware.info/?probe=f93395bc11) | Oct 28, 2023 |
| Sun           | SUNW,SPARC-Enterprise-T5... | [50457ff825](https://bsd-hardware.info/?probe=50457ff825) | Oct 27, 2023 |
| Gigabyte      | H81M-S2PV                   | [310fcb9763](https://bsd-hardware.info/?probe=310fcb9763) | Oct 26, 2023 |
| MECHREVO      | Unknown                     | [2dac22205c](https://bsd-hardware.info/?probe=2dac22205c) | Oct 23, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 25       | 83.33%  |
| sparc64 | 2        | 6.67%   |
| i386    | 2        | 6.67%   |
| arm64   | 1        | 3.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 25       | 83.33%  |
| XFCE         | 4        | 13.33%  |
| GNOME        | 1        | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 21       | 70%     |
| Console | 9        | 30%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 30       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 25       | 83.33%  |
| pl_PL   | 1        | 3.33%   |
| fr_FR   | 1        | 3.33%   |
| es_CO   | 1        | 3.33%   |
| en_US   | 1        | 3.33%   |
| en_GB   | 1        | 3.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 24       | 80%     |
| BIOS | 6        | 20%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Ffs  | 30       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 20       | 66.67%  |
| MBR  | 10       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Lenovo              | 4        | 13.33%  |
| Dell                | 4        | 13.33%  |
| ASUSTek Computer    | 4        | 13.33%  |
| Hewlett-Packard     | 3        | 10%     |
| Sun                 | 2        | 6.67%   |
| Gigabyte Technology | 2        | 6.67%   |
| AZW                 | 2        | 6.67%   |
| MSI                 | 1        | 3.33%   |
| Microsoft           | 1        | 3.33%   |
| MECHREVO            | 1        | 3.33%   |
| Intel               | 1        | 3.33%   |
| FUJI wortmann       | 1        | 3.33%   |
| Biostar             | 1        | 3.33%   |
| ASRock              | 1        | 3.33%   |
| Apple               | 1        | 3.33%   |
| Unknown             | 1        | 3.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Unknown                              | 2        | 6.67%   |
| Sun SUNW,Ultra-1                     | 1        | 3.33%   |
| Sun SUNW,SPARC-Enterprise-T5120      | 1        | 3.33%   |
| MSI MS-7D15                          | 1        | 3.33%   |
| Microsoft Windows Dev Kit 2023       | 1        | 3.33%   |
| Lenovo ThinkCentre M91p 7052C1G      | 1        | 3.33%   |
| Lenovo ThinkCentre M90n-1 11AHS0B200 | 1        | 3.33%   |
| Lenovo ThinkCentre M75n 11BXS00100   | 1        | 3.33%   |
| Lenovo ThinkCentre M720s 10SUSB7Y00  | 1        | 3.33%   |
| Intel DCP847SKE                      | 1        | 3.33%   |
| HP s5-1210br                         | 1        | 3.33%   |
| HP ProLiant ML370 G4                 | 1        | 3.33%   |
| HP Compaq CQ45                       | 1        | 3.33%   |
| Gigabyte Z690 UD DDR4                | 1        | 3.33%   |
| Gigabyte H81M-S2PV                   | 1        | 3.33%   |
| FUJI wortmann D1547                  | 1        | 3.33%   |
| Dell Vostro 3268                     | 1        | 3.33%   |
| Dell PowerEdge T110 II               | 1        | 3.33%   |
| Dell OptiPlex 9010                   | 1        | 3.33%   |
| Dell Inspiron 5521                   | 1        | 3.33%   |
| Biostar B450NH                       | 1        | 3.33%   |
| AZW SER                              | 1        | 3.33%   |
| AZW MINI S                           | 1        | 3.33%   |
| ASUS TUF Gaming B550M-PLUS (WI-FI)   | 1        | 3.33%   |
| ASUS TUF Gaming B550-PLUS            | 1        | 3.33%   |
| ASUS PRIME B550M-A (WI-FI)           | 1        | 3.33%   |
| ASUS MINIPC PN53-G                   | 1        | 3.33%   |
| ASRock Z77 Pro4                      | 1        | 3.33%   |
| Apple MacPro4,1                      | 1        | 3.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Lenovo ThinkCentre  | 4        | 13.33%  |
| Sun SUNW            | 2        | 6.67%   |
| ASUS TUF            | 2        | 6.67%   |
| Unknown             | 2        | 6.67%   |
| MSI MS-7D15         | 1        | 3.33%   |
| Microsoft Windows   | 1        | 3.33%   |
| Intel DCP847SKE     | 1        | 3.33%   |
| HP s5-1210br        | 1        | 3.33%   |
| HP ProLiant         | 1        | 3.33%   |
| HP Compaq           | 1        | 3.33%   |
| Gigabyte Z690       | 1        | 3.33%   |
| Gigabyte H81M-S2PV  | 1        | 3.33%   |
| FUJI wortmann D1547 | 1        | 3.33%   |
| Dell Vostro         | 1        | 3.33%   |
| Dell PowerEdge      | 1        | 3.33%   |
| Dell OptiPlex       | 1        | 3.33%   |
| Dell Inspiron       | 1        | 3.33%   |
| Biostar B450NH      | 1        | 3.33%   |
| AZW SER             | 1        | 3.33%   |
| AZW MINI            | 1        | 3.33%   |
| ASUS PRIME          | 1        | 3.33%   |
| ASUS MINIPC         | 1        | 3.33%   |
| ASRock Z77          | 1        | 3.33%   |
| Apple MacPro4       | 1        | 3.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2023    | 10       | 33.33%  |
| 2022    | 4        | 13.33%  |
| 2013    | 3        | 10%     |
| 2012    | 2        | 6.67%   |
| Unknown | 2        | 6.67%   |
| 2021    | 1        | 3.33%   |
| 2020    | 1        | 3.33%   |
| 2019    | 1        | 3.33%   |
| 2018    | 1        | 3.33%   |
| 2014    | 1        | 3.33%   |
| 2011    | 1        | 3.33%   |
| 2009    | 1        | 3.33%   |
| 2006    | 1        | 3.33%   |
| 2003    | 1        | 3.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 30       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 30       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 5        | 16.67%  |
| 16.01-24.0  | 5        | 16.67%  |
| 8.01-16.0   | 5        | 16.67%  |
| 32.01-64.0  | 4        | 13.33%  |
| 3.01-4.0    | 3        | 10%     |
| 64.01-256.0 | 3        | 10%     |
| 24.01-32.0  | 2        | 6.67%   |
| 2.01-3.0    | 2        | 6.67%   |
| 0.01-0.5    | 1        | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 20       | 66.67%  |
| 0.51-1.0 | 5        | 16.67%  |
| 1.01-2.0 | 3        | 10%     |
| 4.01-8.0 | 1        | 3.33%   |
| 0        | 1        | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 17       | 56.67%  |
| 2      | 7        | 23.33%  |
| 4      | 3        | 10%     |
| 8      | 1        | 3.33%   |
| 5      | 1        | 3.33%   |
| 0      | 1        | 3.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 30       | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 93.33%  |
| No        | 2        | 6.67%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 17       | 56.67%  |
| No        | 13       | 43.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 17       | 56.67%  |
| Yes       | 13       | 43.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country    | Desktops | Percent |
|------------|----------|---------|
| USA        | 3        | 10%     |
| Russia     | 3        | 10%     |
| Germany    | 3        | 10%     |
| Romania    | 2        | 6.67%   |
| Italy      | 2        | 6.67%   |
| Colombia   | 2        | 6.67%   |
| Australia  | 2        | 6.67%   |
| Ukraine    | 1        | 3.33%   |
| UK         | 1        | 3.33%   |
| Turkey     | 1        | 3.33%   |
| Spain      | 1        | 3.33%   |
| Poland     | 1        | 3.33%   |
| Norway     | 1        | 3.33%   |
| Montenegro | 1        | 3.33%   |
| Latvia     | 1        | 3.33%   |
| France     | 1        | 3.33%   |
| China      | 1        | 3.33%   |
| Canada     | 1        | 3.33%   |
| Brazil     | 1        | 3.33%   |
| Austria    | 1        | 3.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| New York      | 2        | 6.67%   |
| Milan         | 2        | 6.67%   |
| Canberra      | 2        | 6.67%   |
| Wolfsburg     | 1        | 3.33%   |
| Witow         | 1        | 3.33%   |
| Volgograd     | 1        | 3.33%   |
| Valmojado     | 1        | 3.33%   |
| Sydenham      | 1        | 3.33%   |
| Stade         | 1        | 3.33%   |
| St Petersburg | 1        | 3.33%   |
| Songjiang     | 1        | 3.33%   |
| Simferopol    | 1        | 3.33%   |
| Sao Paulo     | 1        | 3.33%   |
| Riga          | 1        | 3.33%   |
| Prudhoe       | 1        | 3.33%   |
| Podgorica     | 1        | 3.33%   |
| Ploieşti     | 1        | 3.33%   |
| Orenburg      | 1        | 3.33%   |
| Mersin        | 1        | 3.33%   |
| Medellín     | 1        | 3.33%   |
| Furth im Wald | 1        | 3.33%   |
| Floro         | 1        | 3.33%   |
| Cournanel     | 1        | 3.33%   |
| Calarasi      | 1        | 3.33%   |
| Bucaramanga   | 1        | 3.33%   |
| Axams         | 1        | 3.33%   |
| Austin        | 1        | 3.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| NVMe                | 12       | 14     | 27.91%  |
| Samsung Electronics | 7        | 15     | 16.28%  |
| Seagate             | 5        | 5      | 11.63%  |
| WDC                 | 3        | 3      | 6.98%   |
| Kingston            | 2        | 2      | 4.65%   |
| Hitachi             | 2        | 3      | 4.65%   |
| Toshiba             | 1        | 1      | 2.33%   |
| OPENBSD             | 1        | 1      | 2.33%   |
| Netac               | 1        | 1      | 2.33%   |
| LSILOGIC            | 1        | 1      | 2.33%   |
| KIOXIA-EXCERIA      | 1        | 1      | 2.33%   |
| Intenso             | 1        | 1      | 2.33%   |
| HGST                | 1        | 1      | 2.33%   |
| Hewlett-Packard     | 1        | 1      | 2.33%   |
| Generic             | 1        | 1      | 2.33%   |
| External            | 1        | 1      | 2.33%   |
| Crucial             | 1        | 1      | 2.33%   |
| China               | 1        | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 840 PRO Series 256GB | 2        | 4.17%   |
| NVMe Samsung SSD 980 1TB         | 2        | 4.17%   |
| NVMe SAMSUNG MZALQ128 128GB      | 2        | 4.17%   |
| Kingston SA400S37240G 240GB      | 2        | 4.17%   |
| WDC WD64 00AAKS-22A7B2 640GB     | 1        | 2.08%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1        | 2.08%   |
| WDC WD10JPVT-75A1YT0 1TB         | 1        | 2.08%   |
| Toshiba DT01ACA050 500GB         | 1        | 2.08%   |
| Seagate ST31000340AS 1TB         | 1        | 2.08%   |
| Seagate ST250DM000-1BD141 250GB  | 1        | 2.08%   |
| Seagate ST2000NT001-3M3101 2TB   | 1        | 2.08%   |
| Seagate ST2000LX001-1RG174 2TB   | 1        | 2.08%   |
| Seagate ST1000DM003-1CH162 1TB   | 1        | 2.08%   |
| Samsung SSD 870 QVO 2TB          | 1        | 2.08%   |
| Samsung SSD 860 EVO 250GB        | 1        | 2.08%   |
| Samsung SSD 840 EVO 500GB        | 1        | 2.08%   |
| Samsung SSD 840 EVO 250GB        | 1        | 2.08%   |
| Samsung PSSD T7 500GB            | 1        | 2.08%   |
| Samsung MZ7TE128HMGR-000L1 128GB | 1        | 2.08%   |
| Samsung MZ7LN512HCHP-000 512GB   | 1        | 2.08%   |
| Samsung Flash Drive 64GB         | 1        | 2.08%   |
| OPENBSD SR RAID 5 9.9TB          | 1        | 2.08%   |
| NVMe WDBRPG5000ANC-WR 500GB      | 1        | 2.08%   |
| NVMe Sabrent Rocket 4 500GB      | 1        | 2.08%   |
| NVMe Lexar SSD NM7A1 1TB         | 1        | 2.08%   |
| NVMe Lexar SSD NM620 1TB         | 1        | 2.08%   |
| NVMe Lexar SSD ARES 1 1TB        | 1        | 2.08%   |
| NVMe KIOXIA-EXCERIA S 500GB      | 1        | 2.08%   |
| NVMe KBG40ZNS512G BG4 512GB      | 1        | 2.08%   |
| NVMe HP SSD EX900 500 500GB      | 1        | 2.08%   |
| NVMe CT500P3PSSD8 500GB          | 1        | 2.08%   |
| NVMe aigo SSD P3 512GB           | 1        | 2.08%   |
| Netac NS512GSSD340 512GB         | 1        | 2.08%   |
| LSILOGIC Logical Volume 146GB    | 1        | 2.08%   |
| KIOXIA-EXCERIA SATA SSD 480GB    | 1        | 2.08%   |
| Intenso External USB 3.0 1TB     | 1        | 2.08%   |
| Hitachi HTS541010G9SA00 100GB    | 1        | 2.08%   |
| Hitachi HDE721064SLA360 640GB    | 1        | 2.08%   |
| HGST HTS545050A7E380 500GB       | 1        | 2.08%   |
| HP LOGICAL VOLUME 2TB            | 1        | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 21.74%  |
| NVMe                | 5        | 6      | 21.74%  |
| WDC                 | 3        | 3      | 13.04%  |
| Hitachi             | 2        | 3      | 8.7%    |
| Toshiba             | 1        | 1      | 4.35%   |
| Samsung Electronics | 1        | 1      | 4.35%   |
| OPENBSD             | 1        | 1      | 4.35%   |
| LSILOGIC            | 1        | 1      | 4.35%   |
| Intenso             | 1        | 1      | 4.35%   |
| HGST                | 1        | 1      | 4.35%   |
| Hewlett-Packard     | 1        | 1      | 4.35%   |
| Generic             | 1        | 1      | 4.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| NVMe                | 7        | 7      | 35%     |
| Samsung Electronics | 6        | 14     | 30%     |
| Kingston            | 2        | 2      | 10%     |
| Netac               | 1        | 1      | 5%      |
| KIOXIA-EXCERIA      | 1        | 1      | 5%      |
| External            | 1        | 1      | 5%      |
| Crucial             | 1        | 1      | 5%      |
| China               | 1        | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 25     | 50%     |
| SSD  | 18       | 28     | 47.37%  |
| NVMe | 1        | 1      | 2.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 53     | 96.67%  |
| NVMe | 1        | 1      | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 28     | 55.26%  |
| 0.51-1.0   | 9        | 12     | 23.68%  |
| 1.01-2.0   | 7        | 12     | 18.42%  |
| 4.01-10.0  | 1        | 1      | 2.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 14       | 46.67%  |
| 101-250        | 9        | 30%     |
| 1001-2000      | 2        | 6.67%   |
| 51-100         | 2        | 6.67%   |
| More than 3000 | 1        | 3.33%   |
| 21-50          | 1        | 3.33%   |
| 501-1000       | 1        | 3.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 22       | 73.33%  |
| 21-50    | 6        | 20%     |
| 501-1000 | 1        | 3.33%   |
| 51-100   | 1        | 3.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB          | 1        | 1      | 16.67%  |
| WDC WD10JPVT-75A1YT0 1TB              | 1        | 1      | 16.67%  |
| Seagate ST250DM000-1BD141 250GB       | 1        | 1      | 16.67%  |
| Samsung Electronics SSD 840 EVO 250GB | 1        | 1      | 16.67%  |
| Hitachi HTS541010G9SA00 100GB         | 1        | 1      | 16.67%  |
| HGST HTS545050A7E380 500GB            | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 33.33%  |
| Seagate             | 1        | 1      | 16.67%  |
| Samsung Electronics | 1        | 1      | 16.67%  |
| Hitachi             | 1        | 1      | 16.67%  |
| HGST                | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 2        | 2      | 40%     |
| Seagate | 1        | 1      | 20%     |
| Hitachi | 1        | 1      | 20%     |
| HGST    | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 5      | 83.33%  |
| SSD  | 1        | 1      | 16.67%  |

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
| Detected | 17       | 21     | 45.95%  |
| Works    | 14       | 27     | 37.84%  |
| Malfunc  | 6        | 6      | 16.22%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 17       | 42.5%   |
| Samsung Electronics          | 4        | 10%     |
| AMD                          | 4        | 10%     |
| Shenzhen Longsys Electronics | 2        | 5%      |
| KIOXIA                       | 2        | 5%      |
| Broadcom / LSI               | 2        | 5%      |
| ASMedia Technology           | 2        | 5%      |
| SanDisk                      | 1        | 2.5%    |
| Phison Electronics           | 1        | 2.5%    |
| Micron/Crucial Technology    | 1        | 2.5%    |
| MAXIO Technology (Hangzhou)  | 1        | 2.5%    |
| Compaq Computer              | 1        | 2.5%    |
| Biwin Storage Technology     | 1        | 2.5%    |
| Unknown                      | 1        | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3        | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3        | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3        | 7.14%   |
| AMD 500 Series Chipset SATA Controller                                         | 3        | 7.14%   |
| Shenzhen Longsys Lexar NM790 / Patriot Viper VP4300 Lite NVMe SSD (DRAM-less)  | 2        | 4.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2        | 4.76%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 2        | 4.76%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1        | 2.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1        | 2.38%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 2.38%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1        | 2.38%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 1        | 2.38%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 1        | 2.38%   |
| KIOXIA NVMe SSD                                                                | 1        | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1        | 2.38%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 2.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 2.38%   |
| Intel Alder Lake-N SATA AHCI Controller                                        | 1        | 2.38%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 2.38%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                   | 1        | 2.38%   |
| Intel 82801DB (ICH4) IDE Controller                                            | 1        | 2.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.38%   |
| Intel 7 Series/C210 Series Chipset Family IDE-r Controller                     | 1        | 2.38%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 1        | 2.38%   |
| Compaq Smart Array 64xx                                                        | 1        | 2.38%   |
| Broadcom / LSI SAS1068E PCI-Express Fusion-MPT SAS                             | 1        | 2.38%   |
| Broadcom / LSI 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI                     | 1        | 2.38%   |
| Biwin Storage EX900 NVMe SSD (DRAM-less)                                       | 1        | 2.38%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 1        | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 1        | 2.38%   |
| Unknown                                                                        | 1        | 2.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 20       | 52.63%  |
| NVMe | 12       | 31.58%  |
| IDE  | 3        | 7.89%   |
| SCSI | 2        | 5.26%   |
| RAID | 1        | 2.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 19       | 63.33%  |
| AMD     | 8        | 26.67%  |
| Unknown | 2        | 6.67%   |
| ARM     | 1        | 3.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
|                                                             | 2        | 6.67%   |
| Intel Xeon CPU E5520 @ 2.27GHz                              | 1        | 3.33%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz                         | 1        | 3.33%   |
| Intel Xeon CPU 3.40GHz                                      | 1        | 3.33%   |
| Intel Pentium CPU G620 @ 2.60GHz                            | 1        | 3.33%   |
| Intel Pentium 4 CPU 2.66GHz ("GenuineIntel" 686-class)      | 1        | 3.33%   |
| Intel N95                                                   | 1        | 3.33%   |
| Intel Core i7-3537U CPU @ 2.00GHz                           | 1        | 3.33%   |
| Intel Core i7-2600 CPU @ 3.40GHz                            | 1        | 3.33%   |
| Intel Core i5-7500 CPU @ 3.40GHz                            | 1        | 3.33%   |
| Intel Core i5-3570K CPU @ 3.40GHz                           | 1        | 3.33%   |
| Intel Core i5-3470 CPU @ 3.20GHz ("GenuineIntel" 686-class) | 1        | 3.33%   |
| Intel Core i5-10400F CPU @ 2.90GHz                          | 1        | 3.33%   |
| Intel Core i3-8145U CPU @ 2.10GHz                           | 1        | 3.33%   |
| Intel Core i3-8100 CPU @ 3.60GHz                            | 1        | 3.33%   |
| Intel Celeron N5095A @ 2.00GHz                              | 1        | 3.33%   |
| Intel Celeron CPU G1820 @ 2.70GHz                           | 1        | 3.33%   |
| Intel Celeron CPU B830 @ 1.80GHz                            | 1        | 3.33%   |
| Intel Celeron CPU 847E @ 1.10GHz                            | 1        | 3.33%   |
| Intel 13th Gen Core i7-13700K                               | 1        | 3.33%   |
| ARM Cortex-A78C r0p0                                        | 1        | 3.33%   |
| AMD Ryzen 9 6900HX with Radeon Graphics                     | 1        | 3.33%   |
| AMD Ryzen 9 5950X 16-Core Processor                         | 1        | 3.33%   |
| AMD Ryzen 7 7840H w/ Radeon 780M Graphics                   | 1        | 3.33%   |
| AMD Ryzen 7 3700X 8-Core Processor                          | 1        | 3.33%   |
| AMD Ryzen 5 5600GT with Radeon Graphics                     | 1        | 3.33%   |
| AMD Ryzen 5 5600G with Radeon Graphics                      | 1        | 3.33%   |
| AMD Ryzen 5 5560U with Radeon Graphics                      | 1        | 3.33%   |
| AMD Athlon Silver 3050e with Radeon Graphics                | 1        | 3.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Desktops | Percent |
|-----------------|----------|---------|
| Other           | 4        | 13.33%  |
| Intel Core i5   | 4        | 13.33%  |
| Intel Celeron   | 4        | 13.33%  |
| Intel Xeon      | 3        | 10%     |
| AMD Ryzen 5     | 3        | 10%     |
| Intel Core i7   | 2        | 6.67%   |
| Intel Core i3   | 2        | 6.67%   |
| AMD Ryzen 9     | 2        | 6.67%   |
| AMD Ryzen 7     | 2        | 6.67%   |
| Intel Pentium 4 | 1        | 3.33%   |
| Intel Pentium   | 1        | 3.33%   |
| ARM Cortex      | 1        | 3.33%   |
| AMD Athlon      | 1        | 3.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 9        | 30%     |
| 2       | 6        | 20%     |
| 12      | 4        | 13.33%  |
| Unknown | 4        | 13.33%  |
| 16      | 3        | 10%     |
| 1       | 2        | 6.67%   |
| 32      | 1        | 3.33%   |
| 8       | 1        | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 23       | 76.67%  |
| Unknown | 6        | 20%     |
| 2       | 1        | 3.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 19       | 63.33%  |
| Unknown | 6        | 20%     |
| 2       | 5        | 16.67%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 9        | 30%     |
| Zen 3       | 4        | 13.33%  |
| SandyBridge | 4        | 13.33%  |
| IvyBridge   | 4        | 13.33%  |
| KabyLake    | 3        | 10%     |
| NetBurst    | 2        | 6.67%   |
| Zen 2       | 1        | 3.33%   |
| Zen         | 1        | 3.33%   |
| Nehalem     | 1        | 3.33%   |
| Haswell     | 1        | 3.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| AMD                        | 13       | 44.83%  |
| Intel                      | 12       | 41.38%  |
| Nvidia                     | 3        | 10.34%  |
| Matrox Electronics Systems | 1        | 3.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 10%     |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3        | 10%     |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 6.67%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 3.33%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 1        | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 3.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 3.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1        | 3.33%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 1        | 3.33%   |
| Intel JasperLake [UHD Graphics]                                             | 1        | 3.33%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 3.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 3.33%   |
| Intel Alder Lake-N [UHD Graphics]                                           | 1        | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 1        | 3.33%   |
| AMD RV280 [Radeon 9200] (Secondary)                                         | 1        | 3.33%   |
| AMD RV280 [Radeon 9200]                                                     | 1        | 3.33%   |
| AMD Rembrandt [Radeon 680M]                                                 | 1        | 3.33%   |
| AMD Rage 3 [Rage XL PCI]                                                    | 1        | 3.33%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 1        | 3.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 1        | 3.33%   |
| AMD Phoenix1                                                                | 1        | 3.33%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                             | 1        | 3.33%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 1        | 3.33%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 1        | 3.33%   |
| AMD Mars [Radeon HD 8730M]                                                  | 1        | 3.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Intel   | 10       | 33.33%  |
| 1 x AMD     | 10       | 33.33%  |
| Other       | 3        | 10%     |
| 1 x Nvidia  | 3        | 10%     |
| Intel + AMD | 2        | 6.67%   |
| 2 x AMD     | 1        | 3.33%   |
| 1 x Matrox  | 1        | 3.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 24       | 80%     |
| Unknown | 6        | 20%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 3        | 16.67%  |
| ASUSTek Computer     | 3        | 16.67%  |
| Philips              | 2        | 11.11%  |
| Dell                 | 2        | 11.11%  |
| Ancor Communications | 2        | 11.11%  |
| NEC Computers        | 1        | 5.56%   |
| MSI                  | 1        | 5.56%   |
| LG Display           | 1        | 5.56%   |
| Goldstar             | 1        | 5.56%   |
| AU Optronics         | 1        | 5.56%   |
| AOC                  | 1        | 5.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM041E 2048x1152 510x290mm 23.1-inch  | 1        | 5.56%   |
| Samsung Electronics S24B350 SAM08DA 1920x1080 530x300mm 24.0-inch     | 1        | 5.56%   |
| Samsung Electronics C32JG5x SAM0F54 2560x1440 700x390mm 31.5-inch     | 1        | 5.56%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1        | 5.56%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 1        | 5.56%   |
| NEC Computers EX341R NEC2C7A 3440x1440 800x330mm 34.1-inch            | 1        | 5.56%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                       | 1        | 5.56%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 1        | 5.56%   |
| Goldstar LG IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch          | 1        | 5.56%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                     | 1        | 5.56%   |
| Dell P2210 DEL404E 1680x1050 470x300mm 22.0-inch                      | 1        | 5.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 1        | 5.56%   |
| ASUSTek Computer XG49WCR AUS4932 3840x1080 1190x340mm 48.7-inch       | 1        | 5.56%   |
| ASUSTek Computer XG49V AUS49A1 3840x1080 1200x340mm 49.1-inch         | 1        | 5.56%   |
| ASUSTek Computer PA279 AUS2768 3840x2160 600x340mm 27.2-inch          | 1        | 5.56%   |
| AOC Q27G2WG4 AOC2702 2560x1440 600x340mm 27.2-inch                    | 1        | 5.56%   |
| Ancor Communications ASUS VW199 ACI19ED 1440x900 410x260mm 19.1-inch  | 1        | 5.56%   |
| Ancor Communications ASUS VH228 ACI22FC 1920x1080 470x260mm 21.1-inch | 1        | 5.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 6        | 37.5%   |
| 3840x1080          | 2        | 12.5%   |
| 2560x1440 (QHD)    | 2        | 12.5%   |
| 3840x2160 (4K)     | 1        | 6.25%   |
| 3440x1440          | 1        | 6.25%   |
| 2048x1152          | 1        | 6.25%   |
| 1680x1050 (WSXGA+) | 1        | 6.25%   |
| 1440x900 (WXGA+)   | 1        | 6.25%   |
| 1366x768 (WXGA)    | 1        | 6.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 24     | 3        | 17.65%  |
| 21     | 3        | 17.65%  |
| 27     | 2        | 11.76%  |
| 49     | 1        | 5.88%   |
| 48     | 1        | 5.88%   |
| 34     | 1        | 5.88%   |
| 31     | 1        | 5.88%   |
| 23     | 1        | 5.88%   |
| 22     | 1        | 5.88%   |
| 19     | 1        | 5.88%   |
| 15     | 1        | 5.88%   |
| 13     | 1        | 5.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 35.29%  |
| 401-500     | 5        | 29.41%  |
| 301-350     | 2        | 11.76%  |
| 1001-1500   | 2        | 11.76%  |
| 701-800     | 1        | 5.88%   |
| 601-700     | 1        | 5.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 11       | 68.75%  |
| 32/9  | 2        | 12.5%   |
| 16/10 | 2        | 12.5%   |
| 21/9  | 1        | 6.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 8        | 44.44%  |
| 351-500        | 2        | 11.11%  |
| 301-350        | 2        | 11.11%  |
| 151-200        | 2        | 11.11%  |
| 501-1000       | 2        | 11.11%  |
| 81-90          | 1        | 5.56%   |
| 91-100         | 1        | 5.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 9        | 52.94%  |
| 101-120 | 6        | 35.29%  |
| 161-240 | 1        | 5.88%   |
| 121-160 | 1        | 5.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 14       | 46.67%  |
| 0     | 14       | 46.67%  |
| 2     | 2        | 6.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 43.48%  |
| Intel                 | 16       | 34.78%  |
| Broadcom              | 3        | 6.52%   |
| Qualcomm Atheros      | 2        | 4.35%   |
| ASUSTek Computer      | 2        | 4.35%   |
| Qualcomm Technologies | 1        | 2.17%   |
| Motorola PCS          | 1        | 2.17%   |
| MediaTek              | 1        | 2.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 11       | 22.92%  |
| Realtek RTL8125 2.5GbE Controller                                             | 6        | 12.5%   |
| Intel Wi-Fi 6 AX200                                                           | 3        | 6.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 4.17%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 4.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 1        | 2.08%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 1        | 2.08%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                    | 1        | 2.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 1        | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1        | 2.08%   |
| Motorola PCS USB RNDIS Device                                                 | 1        | 2.08%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 1        | 2.08%   |
| Intel Wireless 3165                                                           | 1        | 2.08%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 1        | 2.08%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 2.08%   |
| Intel Ethernet Connection (10) I219-V                                         | 1        | 2.08%   |
| Intel Centrino Wireless-N 2230                                                | 1        | 2.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 1        | 2.08%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                            | 1        | 2.08%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 2.08%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 2.08%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 2.08%   |
| Broadcom NetXtreme BCM5703 Gigabit Ethernet                                   | 1        | 2.08%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 1        | 2.08%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]            | 1        | 2.08%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                           | 1        | 2.08%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 7        | 41.18%  |
| Realtek Semiconductor | 3        | 17.65%  |
| Qualcomm Atheros      | 2        | 11.76%  |
| ASUSTek Computer      | 2        | 11.76%  |
| Qualcomm Technologies | 1        | 5.88%   |
| MediaTek              | 1        | 5.88%   |
| Broadcom              | 1        | 5.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                | 3        | 17.65%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 1        | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 1        | 5.88%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                         | 1        | 5.88%   |
| Qualcomm QCNFA765 Wireless Network Adapter                         | 1        | 5.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 1        | 5.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1        | 5.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter      | 1        | 5.88%   |
| Intel Wireless 3165                                                | 1        | 5.88%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]          | 1        | 5.88%   |
| Intel Centrino Wireless-N 2230                                     | 1        | 5.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 1        | 5.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller             | 1        | 5.88%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 1        | 5.88%   |
| ASUS Realtek 8188EUS [USB-N10 Nano]                                | 1        | 5.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 19       | 61.29%  |
| Intel                 | 9        | 29.03%  |
| Broadcom              | 2        | 6.45%   |
| Motorola PCS          | 1        | 3.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 11       | 35.48%  |
| Realtek RTL8125 2.5GbE Controller                                             | 6        | 19.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 2        | 6.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 2        | 6.45%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 2        | 6.45%   |
| Motorola PCS USB RNDIS Device                                                 | 1        | 3.23%   |
| Intel Ethernet Connection (7) I219-V                                          | 1        | 3.23%   |
| Intel Ethernet Connection (10) I219-V                                         | 1        | 3.23%   |
| Intel 82801DB PRO/100 VE (LOM) Ethernet Controller                            | 1        | 3.23%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 3.23%   |
| Intel 82574L Gigabit Network Connection                                       | 1        | 3.23%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                       | 1        | 3.23%   |
| Broadcom NetXtreme BCM5703 Gigabit Ethernet                                   | 1        | 3.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 28       | 62.22%  |
| WiFi     | 17       | 37.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 23       | 92%     |
| WiFi     | 2        | 8%      |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 12       | 40%     |
| 1     | 12       | 40%     |
| 3     | 4        | 13.33%  |
| 4     | 1        | 3.33%   |
| 0     | 1        | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 29       | 96.67%  |
| Yes  | 1        | 3.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 7        | 53.85%  |
| Realtek Semiconductor           | 2        | 15.38%  |
| Qualcomm Atheros Communications | 2        | 15.38%  |
| Foxconn / Hon Hai               | 1        | 7.69%   |
| Apple                           | 1        | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                       | 3        | 23.08%  |
| Realtek Bluetooth Adapter                                   | 2        | 15.38%  |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 7.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1        | 7.69%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1        | 7.69%   |
| Intel Bluetooth wireless interface                          | 1        | 7.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 1        | 7.69%   |
| Intel AX210 Bluetooth                                       | 1        | 7.69%   |
| Foxconn / Hon Hai RZ616 Bluetooth Adapter                   | 1        | 7.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 16       | 43.24%  |
| AMD                                          | 11       | 29.73%  |
| Nvidia                                       | 2        | 5.41%   |
| C-Media Electronics                          | 2        | 5.41%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 2.7%    |
| Texas Instruments                            | 1        | 2.7%    |
| Logitech                                     | 1        | 2.7%    |
| KTMicro                                      | 1        | 2.7%    |
| JMTek                                        | 1        | 2.7%    |
| Creative Labs                                | 1        | 2.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Ryzen HD Audio Controller                                              | 6        | 13.33%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5        | 11.11%  |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 3        | 6.67%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 6.67%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 4.44%   |
| C-Media Electronics USB Audio Class 1.0 and 2.0 Device                     | 2        | 4.44%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2        | 4.44%   |
| AMD Radeon High Definition Audio Controller                                | 2        | 4.44%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1        | 2.22%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 2.22%   |
| Logitech [G533 Wireless Headset Dongle]                                    | 1        | 2.22%   |
| KTMicro KT USB Audio                                                       | 1        | 2.22%   |
| JMTek USB PnP Audio Device                                                 | 1        | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1        | 2.22%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 1        | 2.22%   |
| Intel Jasper Lake HD Audio                                                 | 1        | 2.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1        | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 1        | 2.22%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 1        | 2.22%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1        | 2.22%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 1        | 2.22%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1        | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1        | 2.22%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1        | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1        | 2.22%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 1        | 2.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Kingston | 1        | 100%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 3600MT/s | 1        | 100%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 1        | 100%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 1        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 32768 | 1        | 100%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 1        | 100%    |

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


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 50%     |
| Logitech              | 1        | 50%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Realtek Integrated Webcam HD | 1        | 50%     |
| Logitech C920 PRO HD Webcam  | 1        | 50%     |

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
| 1     | 16       | 53.33%  |
| 0     | 9        | 30%     |
| 2     | 4        | 13.33%  |
| 3     | 1        | 3.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 15       | 57.69%  |
| Net/wireless             | 6        | 23.08%  |
| Graphics card            | 4        | 15.38%  |
| Firewire controller      | 1        | 3.85%   |

