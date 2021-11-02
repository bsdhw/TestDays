helloSystem 0.6.0 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

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
| ASRock    | X300M-STX                   | [e25f042400](https://bsd-hardware.info/?probe=e25f042400) | Oct 30, 2021 |
| Unknown   | Intel X79                   | [044908e7c3](https://bsd-hardware.info/?probe=044908e7c3) | Oct 30, 2021 |
| ASUSTek   | TUF GAMING X570-PLUS        | [9f8010bdbe](https://bsd-hardware.info/?probe=9f8010bdbe) | Oct 25, 2021 |
| ASUSTek   | TUF B450M-PRO GAMING        | [9959c0900a](https://bsd-hardware.info/?probe=9959c0900a) | Oct 23, 2021 |
| Gigabyte  | H410M S2 V2                 | [b106820e47](https://bsd-hardware.info/?probe=b106820e47) | Oct 21, 2021 |
| Acer      | RS880M05                    | [4718f0cb0c](https://bsd-hardware.info/?probe=4718f0cb0c) | Oct 21, 2021 |
| Apple     | Mac-F221BEC8                | [cb2cc35e6c](https://bsd-hardware.info/?probe=cb2cc35e6c) | Oct 19, 2021 |
| Gigabyte  | 990FXA-UD3                  | [3cf20ca77c](https://bsd-hardware.info/?probe=3cf20ca77c) | Oct 19, 2021 |
| Dell      | 0VRWRC A00                  | [9b4defb194](https://bsd-hardware.info/?probe=9b4defb194) | Oct 19, 2021 |
| HP        | 3398                        | [892f19c9bd](https://bsd-hardware.info/?probe=892f19c9bd) | Oct 18, 2021 |
| ASUSTek   | CROSSHAIR V FORMULA-Z       | [0cdd3497f6](https://bsd-hardware.info/?probe=0cdd3497f6) | Oct 18, 2021 |
| Gigabyte  | G41MT-S2                    | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| ASUSTek   | P5P43TD PRO                 | [2870e26de1](https://bsd-hardware.info/?probe=2870e26de1) | Oct 17, 2021 |
| Lenovo    | SHARKBAY No DPK             | [14dcd924b5](https://bsd-hardware.info/?probe=14dcd924b5) | Oct 13, 2021 |
| Medion    | H61H2-LM3                   | [67ed0f639c](https://bsd-hardware.info/?probe=67ed0f639c) | Oct 10, 2021 |
| ASUSTek   | H81M-K                      | [e24f67a603](https://bsd-hardware.info/?probe=e24f67a603) | Oct 08, 2021 |
| MSI       | G41M-P25                    | [21eec496b4](https://bsd-hardware.info/?probe=21eec496b4) | Oct 08, 2021 |
| ASRock    | A320M-DGS                   | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| Gigabyte  | B450 AORUS M                | [d09f63f257](https://bsd-hardware.info/?probe=d09f63f257) | Oct 07, 2021 |
| Intel     | H61                         | [6ce71c1b9e](https://bsd-hardware.info/?probe=6ce71c1b9e) | Oct 06, 2021 |
| HP        | 3397                        | [4c71aae5bf](https://bsd-hardware.info/?probe=4c71aae5bf) | Oct 05, 2021 |
| ASRock    | B365M-ITX/ac                | [1c8820a6d0](https://bsd-hardware.info/?probe=1c8820a6d0) | Oct 04, 2021 |
| MSI       | B450I GAMING PLUS AC        | [43388a27a4](https://bsd-hardware.info/?probe=43388a27a4) | Oct 04, 2021 |
| MSI       | MPG X570 GAMING PRO CARB... | [bd312d1c88](https://bsd-hardware.info/?probe=bd312d1c88) | Oct 03, 2021 |
| HP        | ProLiant ML350 G5           | [4d525cba3e](https://bsd-hardware.info/?probe=4d525cba3e) | Oct 03, 2021 |
| ASRock    | X570 Phantom Gaming 4       | [9b14548c15](https://bsd-hardware.info/?probe=9b14548c15) | Sep 21, 2021 |
| Sapphire  | EDGE-FT1M1 E450 1AOVU044    | [ea8fefdf4e](https://bsd-hardware.info/?probe=ea8fefdf4e) | Sep 20, 2021 |
| Dell      | 0MGK50 A02                  | [9d2959b4f1](https://bsd-hardware.info/?probe=9d2959b4f1) | Sep 20, 2021 |
| HP        | 81B4 01                     | [179504116d](https://bsd-hardware.info/?probe=179504116d) | Sep 20, 2021 |
| ASRock    | B450 Gaming-ITX/ac          | [790d020ebe](https://bsd-hardware.info/?probe=790d020ebe) | Sep 19, 2021 |
| Gigabyte  | H270M-DS3H-CF               | [9b046b157e](https://bsd-hardware.info/?probe=9b046b157e) | Sep 17, 2021 |
| ASUSTek   | PRIME B360M-C               | [0f6e7e26fc](https://bsd-hardware.info/?probe=0f6e7e26fc) | Sep 11, 2021 |
| HP        | 3397                        | [5d95b75768](https://bsd-hardware.info/?probe=5d95b75768) | Sep 06, 2021 |
| Medion    | H61H2-LM3                   | [eb81abe401](https://bsd-hardware.info/?probe=eb81abe401) | Sep 02, 2021 |
| ASRock    | Z390 Pro4                   | [ecbf097bc5](https://bsd-hardware.info/?probe=ecbf097bc5) | Sep 02, 2021 |
| ASUSTek   | TUF B360M-PLUS GAMING S     | [33ba0b7c38](https://bsd-hardware.info/?probe=33ba0b7c38) | Aug 29, 2021 |
| ASUSTek   | P7H55-M LX                  | [5fe1a9e521](https://bsd-hardware.info/?probe=5fe1a9e521) | Aug 16, 2021 |
| PCPartner | MILANO-P Rev.00             | [ef8217ac30](https://bsd-hardware.info/?probe=ef8217ac30) | Aug 01, 2021 |
| ASUSTek   | H110M-PLUS                  | [d0f2da9c41](https://bsd-hardware.info/?probe=d0f2da9c41) | Jul 21, 2021 |
| Gigabyte  | H110-D3A-CF                 | [2c390b4301](https://bsd-hardware.info/?probe=2c390b4301) | Jul 09, 2021 |
| Gigabyte  | H110-D3A-CF                 | [aea3a11daf](https://bsd-hardware.info/?probe=aea3a11daf) | Jul 08, 2021 |
| Lenovo    | SHARKBAY SDK0E50510 WIN     | [6cf3337855](https://bsd-hardware.info/?probe=6cf3337855) | Jul 01, 2021 |
| ASUSTek   | M5A97 R2.0                  | [e7a0dfcecf](https://bsd-hardware.info/?probe=e7a0dfcecf) | Jun 28, 2021 |
| ASUSTek   | H81M-K                      | [1a35d2f6ab](https://bsd-hardware.info/?probe=1a35d2f6ab) | Jun 26, 2021 |
| ASUSTek   | H110M-E/M.2                 | [b0b67667d3](https://bsd-hardware.info/?probe=b0b67667d3) | Jun 16, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 38       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 38       | 97.44%  |
| GNOME        | 1        | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 38       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 38       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 38       | 100%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 35       | 92.11%  |
| BIOS | 3        | 7.89%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 38       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 38       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 10       | 26.32%  |
| ASRock              | 6        | 15.79%  |
| Gigabyte Technology | 5        | 13.16%  |
| Hewlett-Packard     | 4        | 10.53%  |
| MSI                 | 3        | 7.89%   |
| Dell                | 2        | 5.26%   |
| Sapphire            | 1        | 2.63%   |
| PCPartner           | 1        | 2.63%   |
| Medion              | 1        | 2.63%   |
| Lenovo              | 1        | 2.63%   |
| Intel               | 1        | 2.63%   |
| Apple               | 1        | 2.63%   |
| Acer                | 1        | 2.63%   |
| Unknown             | 1        | 2.63%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| Sapphire EDGE-FT1M1 E450 1AOVU044 | 1        | 2.63%   |
| PCPartner DREAMSYS                | 1        | 2.63%   |
| MSI MS-7B93                       | 1        | 2.63%   |
| MSI MS-7A40                       | 1        | 2.63%   |
| MSI MS-7592                       | 1        | 2.63%   |
| Medion H61H2-LM3                  | 1        | 2.63%   |
| Lenovo ThinkCentre M83 10AHS35Q00 | 1        | 2.63%   |
| Intel H61                         | 1        | 2.63%   |
| HP ProLiant ML350 G5              | 1        | 2.63%   |
| HP Compaq Elite 8300 USDT         | 1        | 2.63%   |
| HP Compaq Elite 8300 SFF          | 1        | 2.63%   |
| HP 260-p026                       | 1        | 2.63%   |
| Gigabyte H410M S2 V2              | 1        | 2.63%   |
| Gigabyte H270M-DS3H               | 1        | 2.63%   |
| Gigabyte G41MT-S2                 | 1        | 2.63%   |
| Gigabyte B450 AORUS M             | 1        | 2.63%   |
| Gigabyte 990FXA-UD3               | 1        | 2.63%   |
| Dell OptiPlex 3040                | 1        | 2.63%   |
| Dell OptiPlex 3020M               | 1        | 2.63%   |
| ASUS TUF GAMING X570-PLUS         | 1        | 2.63%   |
| ASUS TUF B450M-PRO GAMING         | 1        | 2.63%   |
| ASUS TUF B360M-PLUS GAMING S      | 1        | 2.63%   |
| ASUS P7H55-M LX                   | 1        | 2.63%   |
| ASUS P5P43TD PRO                  | 1        | 2.63%   |
| ASUS M5A97 R2.0                   | 1        | 2.63%   |
| ASUS H110M-PLUS                   | 1        | 2.63%   |
| ASUS exone Business 1203          | 1        | 2.63%   |
| ASUS CROSSHAIR V FORMULA-Z        | 1        | 2.63%   |
| ASUS All Series                   | 1        | 2.63%   |
| ASRock Z390 Pro4                  | 1        | 2.63%   |
| ASRock X570 Phantom Gaming 4      | 1        | 2.63%   |
| ASRock X300M-STX                  | 1        | 2.63%   |
| ASRock B450 Gaming-ITX/ac         | 1        | 2.63%   |
| ASRock B365M-ITX/ac               | 1        | 2.63%   |
| ASRock A320M-DGS                  | 1        | 2.63%   |
| Apple MacPro5,1                   | 1        | 2.63%   |
| Acer Veriton M430                 | 1        | 2.63%   |
| Unknown                           | 1        | 2.63%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS TUF            | 3        | 7.89%   |
| HP Compaq           | 2        | 5.26%   |
| Dell OptiPlex       | 2        | 5.26%   |
| Sapphire EDGE-FT1M1 | 1        | 2.63%   |
| PCPartner DREAMSYS  | 1        | 2.63%   |
| MSI MS-7B93         | 1        | 2.63%   |
| MSI MS-7A40         | 1        | 2.63%   |
| MSI MS-7592         | 1        | 2.63%   |
| Medion H61H2-LM3    | 1        | 2.63%   |
| Lenovo ThinkCentre  | 1        | 2.63%   |
| Intel H61           | 1        | 2.63%   |
| HP ProLiant         | 1        | 2.63%   |
| HP 260-p026         | 1        | 2.63%   |
| Gigabyte H410M      | 1        | 2.63%   |
| Gigabyte H270M-DS3H | 1        | 2.63%   |
| Gigabyte G41MT-S2   | 1        | 2.63%   |
| Gigabyte B450       | 1        | 2.63%   |
| Gigabyte 990FXA-UD3 | 1        | 2.63%   |
| ASUS P7H55-M        | 1        | 2.63%   |
| ASUS P5P43TD        | 1        | 2.63%   |
| ASUS M5A97          | 1        | 2.63%   |
| ASUS H110M-PLUS     | 1        | 2.63%   |
| ASUS exone          | 1        | 2.63%   |
| ASUS CROSSHAIR      | 1        | 2.63%   |
| ASUS All            | 1        | 2.63%   |
| ASRock Z390         | 1        | 2.63%   |
| ASRock X570         | 1        | 2.63%   |
| ASRock X300M-STX    | 1        | 2.63%   |
| ASRock B450         | 1        | 2.63%   |
| ASRock B365M-ITX    | 1        | 2.63%   |
| ASRock A320M-DGS    | 1        | 2.63%   |
| Apple MacPro5       | 1        | 2.63%   |
| Acer Veriton        | 1        | 2.63%   |
| Unknown             | 1        | 2.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 7        | 18.42%  |
| 2020 | 6        | 15.79%  |
| 2019 | 6        | 15.79%  |
| 2015 | 4        | 10.53%  |
| 2010 | 3        | 7.89%   |
| 2018 | 2        | 5.26%   |
| 2017 | 2        | 5.26%   |
| 2016 | 2        | 5.26%   |
| 2012 | 2        | 5.26%   |
| 2011 | 2        | 5.26%   |
| 2013 | 1        | 2.63%   |
| 2009 | 1        | 2.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 38       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 13       | 34.21%  |
| 8.01-16.0   | 10       | 26.32%  |
| 4.01-8.0    | 6        | 15.79%  |
| 32.01-64.0  | 6        | 15.79%  |
| 64.01-256.0 | 3        | 7.89%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 17       | 44.74%  |
| 0.01-0.5 | 14       | 36.84%  |
| 1.01-2.0 | 6        | 15.79%  |
| 3.01-4.0 | 1        | 2.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 15       | 38.46%  |
| 2      | 11       | 28.21%  |
| 3      | 7        | 17.95%  |
| 4      | 5        | 12.82%  |
| 5      | 1        | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 63.16%  |
| Yes       | 14       | 36.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 38       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 24       | 63.16%  |
| Yes       | 14       | 36.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 26       | 68.42%  |
| Yes       | 12       | 31.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 6        | 15.79%  |
| USA         | 4        | 10.53%  |
| Germany     | 3        | 7.89%   |
| Spain       | 2        | 5.26%   |
| Italy       | 2        | 5.26%   |
| China       | 2        | 5.26%   |
| Brazil      | 2        | 5.26%   |
| Ukraine     | 1        | 2.63%   |
| UK          | 1        | 2.63%   |
| Turkey      | 1        | 2.63%   |
| Thailand    | 1        | 2.63%   |
| Switzerland | 1        | 2.63%   |
| South Korea | 1        | 2.63%   |
| Poland      | 1        | 2.63%   |
| Netherlands | 1        | 2.63%   |
| Mexico      | 1        | 2.63%   |
| India       | 1        | 2.63%   |
| Hungary     | 1        | 2.63%   |
| Hong Kong   | 1        | 2.63%   |
| Guatemala   | 1        | 2.63%   |
| Denmark     | 1        | 2.63%   |
| Chile       | 1        | 2.63%   |
| Canada      | 1        | 2.63%   |
| Australia   | 1        | 2.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Marlborough       | 2        | 5.26%   |
| Yekaterinburg     | 1        | 2.63%   |
| Xiamen            | 1        | 2.63%   |
| Voronezh          | 1        | 2.63%   |
| Tula de Allende   | 1        | 2.63%   |
| Torre del Mar     | 1        | 2.63%   |
| Tampa             | 1        | 2.63%   |
| Stuttgart         | 1        | 2.63%   |
| Shepetivka        | 1        | 2.63%   |
| Santiago          | 1        | 2.63%   |
| Rostov-on-Don     | 1        | 2.63%   |
| Riehen            | 1        | 2.63%   |
| Richmond          | 1        | 2.63%   |
| Reriutaba         | 1        | 2.63%   |
| Qingdao           | 1        | 2.63%   |
| Pistoia           | 1        | 2.63%   |
| Nieuwegein        | 1        | 2.63%   |
| Newtownabbey      | 1        | 2.63%   |
| Moscow            | 1        | 2.63%   |
| Kosekoy           | 1        | 2.63%   |
| Katowice          | 1        | 2.63%   |
| Irkutsk           | 1        | 2.63%   |
| Inhapim           | 1        | 2.63%   |
| Hong Kong         | 1        | 2.63%   |
| Hicksville        | 1        | 2.63%   |
| Heidelberg        | 1        | 2.63%   |
| Gy?�r             | 1        | 2.63%   |
| Gwangyang         | 1        | 2.63%   |
| Guatemala City    | 1        | 2.63%   |
| Grottazzolina     | 1        | 2.63%   |
| Fuente Carreteros | 1        | 2.63%   |
| Frederiksberg     | 1        | 2.63%   |
| Filderstadt       | 1        | 2.63%   |
| Ernakulam         | 1        | 2.63%   |
| Chelyabinsk       | 1        | 2.63%   |
| Brisbane          | 1        | 2.63%   |
| Bangkok           | 1        | 2.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 16       | 20     | 24.24%  |
| Seagate             | 13       | 17     | 19.7%   |
| Samsung Electronics | 8        | 10     | 12.12%  |
| Toshiba             | 3        | 5      | 4.55%   |
| SanDisk             | 3        | 3      | 4.55%   |
| Hitachi             | 3        | 4      | 4.55%   |
| Crucial             | 3        | 5      | 4.55%   |
| Smartbuy            | 2        | 2      | 3.03%   |
| Kingston            | 2        | 4      | 3.03%   |
| China               | 2        | 2      | 3.03%   |
| A-DATA Technology   | 2        | 4      | 3.03%   |
| Verbatim            | 1        | 1      | 1.52%   |
| SPCC                | 1        | 1      | 1.52%   |
| PLEXTOR             | 1        | 1      | 1.52%   |
| LITEONIT            | 1        | 1      | 1.52%   |
| Intel               | 1        | 1      | 1.52%   |
| Hewlett-Packard     | 1        | 1      | 1.52%   |
| Gigabyte Technology | 1        | 1      | 1.52%   |
| Corsair             | 1        | 1      | 1.52%   |
| Apacer              | 1        | 1      | 1.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| WDC WDS100T2B0C-00PXH0 1TB          | 2        | 2.5%    |
| WDC WD3200BPVT-22JJ5T0 320GB        | 2        | 2.5%    |
| Toshiba DT01ACA100 1TB              | 2        | 2.5%    |
| SanDisk SDSSDA240G 240GB            | 2        | 2.5%    |
| Samsung SSD 860 EVO 500GB           | 2        | 2.5%    |
| Samsung SSD 850 EVO 250GB           | 2        | 2.5%    |
| Samsung HD322HJ 320GB               | 2        | 2.5%    |
| China SATA SSD 120GB                | 2        | 2.5%    |
| WDC WDS250G2X0C-00L350 250GB        | 1        | 1.25%   |
| WDC WD5000LPCX-00VHAT0 500GB        | 1        | 1.25%   |
| WDC WD5000AAVS-00ZTB0 500GB         | 1        | 1.25%   |
| WDC WD5000AAKS-00V1A0 500GB         | 1        | 1.25%   |
| WDC WD40EZRZ-22GXCB0 4TB            | 1        | 1.25%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1        | 1.25%   |
| WDC WD30EZRZ-00WN9B0 3TB            | 1        | 1.25%   |
| WDC WD3003FZEX-00Z4SA0 3TB          | 1        | 1.25%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1        | 1.25%   |
| WDC WD1600AAJS-00WAA0 160GB         | 1        | 1.25%   |
| WDC WD1600AAJS-00V4A0 160GB         | 1        | 1.25%   |
| WDC WD10SPZX-22Z10T0 1TB            | 1        | 1.25%   |
| WDC WD10JMVW-11AJGS0 1TB            | 1        | 1.25%   |
| WDC WD10EZRX-00A8LB0 1TB            | 1        | 1.25%   |
| WDC WD10EZEX-75WN4A1 1TB            | 1        | 1.25%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1        | 1.25%   |
| Verbatim Vi550 S3 SSD 256GB         | 1        | 1.25%   |
| Toshiba MQ01UBD100 1TB              | 1        | 1.25%   |
| Toshiba DT01ACA050 500GB            | 1        | 1.25%   |
| SPCC M.2 PCIe SSD 256GB             | 1        | 1.25%   |
| Smartbuy SSD 240GB                  | 1        | 1.25%   |
| Smartbuy SSD 120GB                  | 1        | 1.25%   |
| Seagate ST9320325AS 320GB           | 1        | 1.25%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1        | 1.25%   |
| Seagate ST500LM000-1EJ162 500GB     | 1        | 1.25%   |
| Seagate ST500DM002-1SB10A 500GB     | 1        | 1.25%   |
| Seagate ST4000DM004-2CV104 4TB      | 1        | 1.25%   |
| Seagate ST3500413AS 500GB           | 1        | 1.25%   |
| Seagate ST3500312CS 500GB           | 1        | 1.25%   |
| Seagate ST3250318AS 250GB           | 1        | 1.25%   |
| Seagate ST3160813AS 160GB           | 1        | 1.25%   |
| Seagate ST31000524AS 1TB            | 1        | 1.25%   |
| Seagate ST3000DM001-1CH166 3TB      | 1        | 1.25%   |
| Seagate ST2000DX001-1CM164 2TB      | 1        | 1.25%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 1.25%   |
| Seagate ST1000LM035-1RK172 1TB      | 1        | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1        | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB      | 1        | 1.25%   |
| SanDisk SDSSDA120G 120GB            | 1        | 1.25%   |
| Samsung SSD 970 EVO 500GB           | 1        | 1.25%   |
| Samsung SSD 860 EVO 250GB           | 1        | 1.25%   |
| Samsung SSD 860 EVO 1TB             | 1        | 1.25%   |
| Samsung HD161HJ 160GB               | 1        | 1.25%   |
| PLEXTOR PX-AG256M6e 256GB           | 1        | 1.25%   |
| LITEONIT LMT-32L3M 32GB             | 1        | 1.25%   |
| Kingston SUV400S37240G 240GB        | 1        | 1.25%   |
| Kingston SS200S330G 32GB            | 1        | 1.25%   |
| Kingston SA400S37240G 240GB         | 1        | 1.25%   |
| Intel SSDSA2BW160G3H 160GB          | 1        | 1.25%   |
| Hitachi HUS724030ALE641 3TB         | 1        | 1.25%   |
| Hitachi HTS547550A9E384 500GB       | 1        | 1.25%   |
| Hitachi HDS721050CLA360 500GB       | 1        | 1.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 17     | 38.89%  |
| Seagate             | 13       | 17     | 36.11%  |
| Toshiba             | 3        | 5      | 8.33%   |
| Hitachi             | 3        | 4      | 8.33%   |
| Samsung Electronics | 2        | 3      | 5.56%   |
| Hewlett-Packard     | 1        | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 6        | 6      | 25%     |
| SanDisk             | 3        | 3      | 12.5%   |
| Crucial             | 3        | 5      | 12.5%   |
| Smartbuy            | 2        | 2      | 8.33%   |
| Kingston            | 2        | 4      | 8.33%   |
| China               | 2        | 2      | 8.33%   |
| Verbatim            | 1        | 1      | 4.17%   |
| PLEXTOR             | 1        | 1      | 4.17%   |
| LITEONIT            | 1        | 1      | 4.17%   |
| Intel               | 1        | 1      | 4.17%   |
| Apacer              | 1        | 1      | 4.17%   |
| A-DATA Technology   | 1        | 2      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 47     | 47.17%  |
| SSD  | 20       | 29     | 37.74%  |
| NVMe | 8        | 9      | 15.09%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 35       | 76     | 81.4%   |
| NVMe | 8        | 9      | 18.6%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 34       | 48     | 58.62%  |
| 0.51-1.0   | 15       | 17     | 25.86%  |
| 1.01-2.0   | 4        | 4      | 6.9%    |
| 2.01-3.0   | 3        | 5      | 5.17%   |
| 3.01-4.0   | 2        | 2      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 25       | 65.79%  |
| 101-250    | 9        | 23.68%  |
| 251-500    | 3        | 7.89%   |
| 21-50      | 1        | 2.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 38       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Samsung Electronics HD322HJ 320GB   | 2        | 2      | 15.38%  |
| WDC WD5000AAKS-00V1A0 500GB         | 1        | 1      | 7.69%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 1        | 1      | 7.69%   |
| WDC WD3200AAKS-00UU3A0 320GB        | 1        | 1      | 7.69%   |
| WDC WD10JMVW-11AJGS0 1TB            | 1        | 1      | 7.69%   |
| Toshiba MQ01UBD100 1TB              | 1        | 1      | 7.69%   |
| Toshiba DT01ACA100 1TB              | 1        | 2      | 7.69%   |
| Seagate ST9320325AS 320GB           | 1        | 1      | 7.69%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1        | 1      | 7.69%   |
| Seagate ST3500413AS 500GB           | 1        | 1      | 7.69%   |
| SanDisk SDSSDA240G 240GB            | 1        | 1      | 7.69%   |
| Samsung Electronics HD161HJ 160GB   | 1        | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 33.33%  |
| Seagate             | 3        | 3      | 25%     |
| Toshiba             | 2        | 3      | 16.67%  |
| Samsung Electronics | 2        | 3      | 16.67%  |
| SanDisk             | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 4        | 4      | 36.36%  |
| Seagate             | 3        | 3      | 27.27%  |
| Toshiba             | 2        | 3      | 18.18%  |
| Samsung Electronics | 2        | 3      | 18.18%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 10       | 13     | 90.91%  |
| SSD  | 1        | 1      | 9.09%   |

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
| Works    | 36       | 70     | 75%     |
| Malfunc  | 11       | 14     | 22.92%  |
| Detected | 1        | 1      | 2.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 23       | 46.94%  |
| AMD                        | 13       | 26.53%  |
| Sandisk                    | 3        | 6.12%   |
| Phison Electronics         | 3        | 6.12%   |
| ASMedia Technology         | 2        | 4.08%   |
| Samsung Electronics        | 1        | 2.04%   |
| Lite-On IT Corp. / Plextor | 1        | 2.04%   |
| JMicron Technology         | 1        | 2.04%   |
| Hewlett-Packard            | 1        | 2.04%   |
| ADATA Technology           | 1        | 2.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 12.07%  |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 6.9%    |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 6.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 5.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 5.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3        | 5.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 5.17%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 2        | 3.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 3.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2        | 3.45%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2        | 3.45%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1        | 1.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 1.72%   |
| Phison PS5013 E13 NVMe Controller                                              | 1        | 1.72%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 1.72%   |
| Phison E12 NVMe Controller                                                     | 1        | 1.72%   |
| Lite-On IT Corp. / Plextor M6e PCI Express SSD [Marvell 88SS9183]              | 1        | 1.72%   |
| JMicron JMB361 AHCI/IDE                                                        | 1        | 1.72%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 1.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1        | 1.72%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 1        | 1.72%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 1        | 1.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 1        | 1.72%   |
| Intel 631xESB/632xESB IDE Controller                                           | 1        | 1.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 1        | 1.72%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 1        | 1.72%   |
| HP Smart Array E200i (SAS Controller)                                          | 1        | 1.72%   |
| HP Smart Array Controller                                                      | 1        | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 1        | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 1        | 1.72%   |
| AMD FCH SATA Controller D                                                      | 1        | 1.72%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 1        | 1.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 30       | 66.67%  |
| NVMe | 8        | 17.78%  |
| IDE  | 6        | 13.33%  |
| RAID | 1        | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 24       | 63.16%  |
| AMD    | 14       | 36.84%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-6100T CPU @ 3.20GHz           | 2        | 5.26%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 5.26%   |
| Intel Xeon CPU W3680 @ 3.33GHz              | 1        | 2.63%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 2.63%   |
| Intel Xeon                                  | 1        | 2.63%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 1        | 2.63%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1        | 2.63%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1        | 2.63%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1        | 2.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 2.63%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 1        | 2.63%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1        | 2.63%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1        | 2.63%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 2.63%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 2.63%   |
| Intel Core i5 CPU 661 @ 3.33GHz             | 1        | 2.63%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1        | 2.63%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 2.63%   |
| Intel Core i3-4150T CPU @ 3.00GHz           | 1        | 2.63%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 1        | 2.63%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 1        | 2.63%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 1        | 2.63%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 1        | 2.63%   |
| Intel Core 2 Duo CPU                        | 1        | 2.63%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 1        | 2.63%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 1        | 2.63%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 1        | 2.63%   |
| AMD Ryzen 5 PRO 4650G with Radeon Graphics  | 1        | 2.63%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1        | 2.63%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 1        | 2.63%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 2.63%   |
| AMD Phenom II X6 1045T Processor            | 1        | 2.63%   |
| AMD FX-8350 Eight-Core Processor            | 1        | 2.63%   |
| AMD FX-6300 Six-Core Processor              | 1        | 2.63%   |
| AMD FX-6100 Six-Core Processor              | 1        | 2.63%   |
| AMD E-450 APU with Radeon HD Graphics       | 1        | 2.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel Core i3     | 7        | 18.42%  |
| Intel Core i7     | 5        | 13.16%  |
| Intel Core i5     | 5        | 13.16%  |
| Intel Xeon        | 3        | 7.89%   |
| AMD Ryzen 9       | 3        | 7.89%   |
| AMD FX            | 3        | 7.89%   |
| Intel Core 2 Duo  | 2        | 5.26%   |
| AMD Ryzen 7       | 2        | 5.26%   |
| AMD Ryzen 5       | 2        | 5.26%   |
| Intel Pentium     | 1        | 2.63%   |
| Intel Core 2 Quad | 1        | 2.63%   |
| AMD Ryzen 5 PRO   | 1        | 2.63%   |
| AMD Ryzen 3       | 1        | 2.63%   |
| AMD Phenom II X6  | 1        | 2.63%   |
| AMD E             | 1        | 2.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 10       | 26.32%  |
| 4       | 9        | 23.68%  |
| 6       | 6        | 15.79%  |
| 8       | 4        | 10.53%  |
| 24      | 3        | 7.89%   |
| 12      | 3        | 7.89%   |
| 16      | 2        | 5.26%   |
| Unknown | 1        | 2.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 37       | 97.37%  |
| 2      | 1        | 2.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 24       | 63.16%  |
| 2       | 13       | 34.21%  |
| Unknown | 1        | 2.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| KabyLake    | 6        | 15.79%  |
| Zen 2       | 4        | 10.53%  |
| Penryn      | 4        | 10.53%  |
| Haswell     | 4        | 10.53%  |
| Zen+        | 3        | 7.89%   |
| SandyBridge | 3        | 7.89%   |
| Westmere    | 2        | 5.26%   |
| Skylake     | 2        | 5.26%   |
| Piledriver  | 2        | 5.26%   |
| IvyBridge   | 2        | 5.26%   |
| Zen 3       | 1        | 2.63%   |
| Zen         | 1        | 2.63%   |
| K10         | 1        | 2.63%   |
| CometLake   | 1        | 2.63%   |
| Bulldozer   | 1        | 2.63%   |
| Bobcat      | 1        | 2.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 18       | 45%     |
| AMD    | 13       | 32.5%   |
| Intel  | 9        | 22.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 5%      |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 5%      |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 5%      |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 5%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 5%      |
| AMD Oland PRO [Radeon R7 240/340]                                           | 2        | 5%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2        | 5%      |
| Nvidia GT215 [GeForce GT 220]                                               | 1        | 2.5%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 2.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1        | 2.5%    |
| Nvidia GP104 [GeForce GTX 1060 3GB]                                         | 1        | 2.5%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 2.5%    |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 2.5%    |
| Nvidia GK104 [GeForce GTX 680]                                              | 1        | 2.5%    |
| Nvidia GF108 [GeForce GT 530]                                               | 1        | 2.5%    |
| Nvidia GF108 [GeForce GT 440]                                               | 1        | 2.5%    |
| Nvidia G96C [GeForce 9500 GT]                                               | 1        | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1        | 2.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 2.5%    |
| Intel HD Graphics 630                                                       | 1        | 2.5%    |
| Intel HD Graphics 530                                                       | 1        | 2.5%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 2.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1        | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 1        | 2.5%    |
| AMD Wrestler [Radeon HD 6320]                                               | 1        | 2.5%    |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 2.5%    |
| AMD RS880 [Radeon HD 4250]                                                  | 1        | 2.5%    |
| AMD Renoir                                                                  | 1        | 2.5%    |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 1        | 2.5%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 1        | 2.5%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 1        | 2.5%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 1        | 2.5%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 1        | 2.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 17       | 44.74%  |
| 1 x AMD        | 12       | 31.58%  |
| 1 x Intel      | 7        | 18.42%  |
| Intel + Nvidia | 1        | 2.63%   |
| Intel + AMD    | 1        | 2.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 28       | 73.68%  |
| Proprietary | 9        | 23.68%  |
| Unknown     | 1        | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 21       | 55.26%  |
| 1.01-2.0   | 6        | 15.79%  |
| 3.01-4.0   | 3        | 7.89%   |
| 0.01-0.5   | 3        | 7.89%   |
| 7.01-8.0   | 2        | 5.26%   |
| 5.01-6.0   | 2        | 5.26%   |
| 0.51-1.0   | 1        | 2.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 4        | 16.67%  |
| Iiyama               | 3        | 12.5%   |
| Hewlett-Packard      | 2        | 8.33%   |
| Acer                 | 2        | 8.33%   |
| Vizio                | 1        | 4.17%   |
| ViewSonic            | 1        | 4.17%   |
| Philips              | 1        | 4.17%   |
| Medion               | 1        | 4.17%   |
| Lenovo               | 1        | 4.17%   |
| Haier                | 1        | 4.17%   |
| Goldstar             | 1        | 4.17%   |
| Eizo                 | 1        | 4.17%   |
| Dell                 | 1        | 4.17%   |
| BenQ                 | 1        | 4.17%   |
| AOC                  | 1        | 4.17%   |
| Ancor Communications | 1        | 4.17%   |
| ALP                  | 1        | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch              | 2        | 8.33%   |
| Vizio LCD Monitor VIZ0022 1920x540 480x270mm 21.7-inch               | 1        | 4.17%   |
| ViewSonic VX2458-mhd VSC0437 1920x1080 520x290mm 23.4-inch           | 1        | 4.17%   |
| Samsung Electronics T22D390 SAM0B69 1920x1080 480x270mm 21.7-inch    | 1        | 4.17%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                     | 1        | 4.17%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                     | 1        | 4.17%   |
| Samsung Electronics LCD Monitor SAM4A75 1024x768 300x230mm 14.9-inch | 1        | 4.17%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch               | 1        | 4.17%   |
| Medion MD21281 MED3947 1366x768 410x230mm 18.5-inch                  | 1        | 4.17%   |
| Lenovo LEN-M73Z-D LEN00A0 1600x900 440x240mm 19.7-inch               | 1        | 4.17%   |
| Iiyama PL2409HD IVM560C 1920x1080 520x290mm 23.4-inch                | 1        | 4.17%   |
| Hewlett-Packard E243m HPN3465 1920x1080 530x300mm 24.0-inch          | 1        | 4.17%   |
| Hewlett-Packard 2310 HWP288F 1920x1080 510x290mm 23.1-inch           | 1        | 4.17%   |
| Haier HT-20216B(C) HAI2031 1920x1080 480x270mm 21.7-inch             | 1        | 4.17%   |
| Goldstar L1553S GSM3BB0 1024x768 300x230mm 14.9-inch                 | 1        | 4.17%   |
| Eizo EV2316W ENC2394 1920x1080 510x290mm 23.1-inch                   | 1        | 4.17%   |
| Dell 1708FP DEL4024 1280x1024 340x270mm 17.1-inch                    | 1        | 4.17%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 1        | 4.17%   |
| AOC LE19W037 AOC1907 1360x768 410x230mm 18.5-inch                    | 1        | 4.17%   |
| Ancor Communications MW221 ACI22B1 1680x1050 470x300mm 22.0-inch     | 1        | 4.17%   |
| ALP 2476 IPS ALP2476 1920x1080 530x300mm 24.0-inch                   | 1        | 4.17%   |
| Acer ET430K ACR0558 3840x2160 940x530mm 42.5-inch                    | 1        | 4.17%   |
| Acer B223W ACR0018 1680x1050 470x300mm 22.0-inch                     | 1        | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 12       | 50%     |
| 1680x1050 (WSXGA+) | 2        | 8.33%   |
| 1366x768 (WXGA)    | 2        | 8.33%   |
| 1024x768 (XGA)     | 2        | 8.33%   |
| 3840x2160 (4K)     | 1        | 4.17%   |
| 2560x1440 (QHD)    | 1        | 4.17%   |
| 1920x540           | 1        | 4.17%   |
| 1600x900 (HD+)     | 1        | 4.17%   |
| 1360x768           | 1        | 4.17%   |
| 1280x1024 (SXGA)   | 1        | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 6        | 25%     |
| 21      | 3        | 12.5%   |
| 18      | 3        | 12.5%   |
| 24      | 2        | 8.33%   |
| 22      | 2        | 8.33%   |
| 14      | 2        | 8.33%   |
| Unknown | 2        | 8.33%   |
| 42      | 1        | 4.17%   |
| 27      | 1        | 4.17%   |
| 19      | 1        | 4.17%   |
| 17      | 1        | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 9        | 37.5%   |
| 401-500     | 9        | 37.5%   |
| 201-300     | 2        | 8.33%   |
| Unknown     | 2        | 8.33%   |
| 301-350     | 1        | 4.17%   |
| 901-1000    | 1        | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 19       | 79.17%  |
| 4/3   | 2        | 8.33%   |
| 16/10 | 2        | 8.33%   |
| 5/4   | 1        | 4.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 13       | 54.17%  |
| 141-150        | 4        | 16.67%  |
| 101-110        | 2        | 8.33%   |
| Unknown        | 2        | 8.33%   |
| 301-350        | 1        | 4.17%   |
| 151-200        | 1        | 4.17%   |
| 501-1000       | 1        | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 18       | 75%     |
| 101-120 | 4        | 16.67%  |
| Unknown | 2        | 8.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 55.26%  |
| 0     | 16       | 42.11%  |
| 2     | 1        | 2.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 21       | 41.18%  |
| Intel                    | 14       | 27.45%  |
| Broadcom                 | 6        | 11.76%  |
| Qualcomm Atheros         | 3        | 5.88%   |
| Ralink Technology        | 2        | 3.92%   |
| Ralink                   | 1        | 1.96%   |
| Marvell Technology Group | 1        | 1.96%   |
| IMC Networks             | 1        | 1.96%   |
| ASUSTek Computer         | 1        | 1.96%   |
| Aquantia                 | 1        | 1.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 19       | 35.19%  |
| Intel I211 Gigabit Network Connection                                          | 3        | 5.56%   |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 5.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2        | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2        | 3.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 2        | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1        | 1.85%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1        | 1.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 1.85%   |
| Ralink RT3072 Wireless Adapter                                                 | 1        | 1.85%   |
| Ralink MT7601U Wireless Adapter                                                | 1        | 1.85%   |
| Ralink RT2561/RT61 rev B 802.11g                                               | 1        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1        | 1.85%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1        | 1.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 1.85%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 1.85%   |
| Intel Wireless 7265                                                            | 1        | 1.85%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 1.85%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 1.85%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 1.85%   |
| Intel 82583V Gigabit Network Connection                                        | 1        | 1.85%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 1.85%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter    | 1        | 1.85%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1        | 1.85%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                  | 1        | 1.85%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                             | 1        | 1.85%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 1        | 1.85%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                      | 1        | 1.85%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1        | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Broadcom              | 4        | 26.67%  |
| Intel                 | 3        | 20%     |
| Realtek Semiconductor | 2        | 13.33%  |
| Ralink Technology     | 2        | 13.33%  |
| Ralink                | 1        | 6.67%   |
| Qualcomm Atheros      | 1        | 6.67%   |
| IMC Networks          | 1        | 6.67%   |
| ASUSTek Computer      | 1        | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2        | 13.33%  |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 2        | 13.33%  |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1        | 6.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                       | 1        | 6.67%   |
| Ralink RT3072 Wireless Adapter                                              | 1        | 6.67%   |
| Ralink MT7601U Wireless Adapter                                             | 1        | 6.67%   |
| Ralink RT2561/RT61 rev B 802.11g                                            | 1        | 6.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 1        | 6.67%   |
| Intel Wireless 7265                                                         | 1        | 6.67%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1        | 6.67%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                          | 1        | 6.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 1        | 6.67%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1        | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 20       | 51.28%  |
| Intel                    | 13       | 33.33%  |
| Qualcomm Atheros         | 2        | 5.13%   |
| Broadcom                 | 2        | 5.13%   |
| Marvell Technology Group | 1        | 2.56%   |
| Aquantia                 | 1        | 2.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 19       | 48.72%  |
| Intel I211 Gigabit Network Connection                                          | 3        | 7.69%   |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2        | 5.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1        | 2.56%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1        | 2.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 2.56%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1        | 2.56%   |
| Intel Ethernet Connection I217-LM                                              | 1        | 2.56%   |
| Intel Ethernet Connection (2) I219-V                                           | 1        | 2.56%   |
| Intel Ethernet Connection (11) I219-V                                          | 1        | 2.56%   |
| Intel 82583V Gigabit Network Connection                                        | 1        | 2.56%   |
| Intel 82574L Gigabit Network Connection                                        | 1        | 2.56%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                 | 1        | 2.56%   |
| Broadcom NetXtreme BCM5705_2 Gigabit Ethernet                                  | 1        | 2.56%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 1        | 2.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 38       | 73.08%  |
| WiFi     | 14       | 26.92%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 38       | 82.61%  |
| WiFi     | 8        | 17.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 26       | 68.42%  |
| 2     | 11       | 28.95%  |
| 3     | 1        | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 38       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 4        | 33.33%  |
| Apple                   | 3        | 25%     |
| Realtek Semiconductor   | 1        | 8.33%   |
| Foxconn / Hon Hai       | 1        | 8.33%   |
| Cambridge Silicon Radio | 1        | 8.33%   |
| Broadcom                | 1        | 8.33%   |
| ASUSTek Computer        | 1        | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 16.67%  |
| Apple Apple Broadcom Built-in Bluetooth             | 2        | 16.67%  |
| Realtek  Bluetooth 4.0 Adapter                      | 1        | 8.33%   |
| Intel Bluetooth wireless interface                  | 1        | 8.33%   |
| Intel AX200 Bluetooth                               | 1        | 8.33%   |
| Foxconn / Hon Hai Broadcom Bluetooth 4.0 USB        | 1        | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 8.33%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 8.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 8.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 22       | 32.35%  |
| AMD                     | 18       | 26.47%  |
| Nvidia                  | 17       | 25%     |
| C-Media Electronics     | 4        | 5.88%   |
| Logitech                | 2        | 2.94%   |
| Texas Instruments       | 1        | 1.47%   |
| Plantronics             | 1        | 1.47%   |
| Hewlett-Packard         | 1        | 1.47%   |
| Creative Labs           | 1        | 1.47%   |
| BEHRINGER International | 1        | 1.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 6.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4        | 5.06%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4        | 5.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3        | 3.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3        | 3.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3        | 3.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3        | 3.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3        | 3.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 2.53%   |
| Nvidia GM206 High Definition Audio Controller                              | 2        | 2.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2        | 2.53%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2        | 2.53%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2        | 2.53%   |
| Nvidia GF108 High Definition Audio Controller                              | 2        | 2.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2        | 2.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2        | 2.53%   |
| Intel Cannon Lake PCH cAVS                                                 | 2        | 2.53%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2        | 2.53%   |
| Intel 200 Series PCH HD Audio                                              | 2        | 2.53%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 2        | 2.53%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2        | 2.53%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1        | 1.27%   |
| Plantronics Plantronics Blackwire 325.1                                    | 1        | 1.27%   |
| Nvidia High Definition Audio Controller                                    | 1        | 1.27%   |
| Nvidia GP108 High Definition Audio Controller                              | 1        | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1        | 1.27%   |
| Nvidia GP104 High Definition Audio Controller                              | 1        | 1.27%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1        | 1.27%   |
| Logitech HD Webcam C910                                                    | 1        | 1.27%   |
| Logitech HD Webcam C510                                                    | 1        | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 1        | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1        | 1.27%   |
| Hewlett-Packard E243m                                                      | 1        | 1.27%   |
| Creative Labs EMU10k2/CA0100/CA0102/CA10200 [Sound Blaster Audigy Series]  | 1        | 1.27%   |
| C-Media Electronics CM108 Audio Controller                                 | 1        | 1.27%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                        | 1        | 1.27%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1        | 1.27%   |
| C-Media Electronics Audio Adapter                                          | 1        | 1.27%   |
| BEHRINGER International UMC202HD 192k                                      | 1        | 1.27%   |
| AMD Wrestler HDMI Audio                                                    | 1        | 1.27%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1        | 1.27%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1        | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1        | 1.27%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                  | 1        | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 9        | 20.45%  |
| Samsung Electronics | 8        | 18.18%  |
| Crucial             | 8        | 18.18%  |
| Unknown             | 4        | 9.09%   |
| Team                | 3        | 6.82%   |
| Corsair             | 3        | 6.82%   |
| SK Hynix            | 2        | 4.55%   |
| Unknown             | 2        | 4.55%   |
| Transcend           | 1        | 2.27%   |
| Ramaxel Technology  | 1        | 2.27%   |
| Nanya Technology    | 1        | 2.27%   |
| Micron Technology   | 1        | 2.27%   |
| A-DATA Technology   | 1        | 2.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s     | 2        | 4.35%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s    | 2        | 4.35%   |
| Unknown                                                 | 2        | 4.35%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s             | 1        | 2.17%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 2.17%   |
| Unknown RAM Module 4GB DIMM 400MT/s                     | 1        | 2.17%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 1        | 2.17%   |
| Transcend RAM JM1333KSN-4G 4GB DIMM DDR3 1333MT/s       | 1        | 2.17%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s      | 1        | 2.17%   |
| SK Hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 2.17%   |
| SK Hynix RAM HMT451S6BCFR8A-PB 4GB DIMM DDR3            | 1        | 2.17%   |
| Samsung RAM Module 2GB DIMM DDR3 400MT/s                | 1        | 2.17%   |
| Samsung RAM Module 16GB DIMM DDR3 1333MT/s              | 1        | 2.17%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 1        | 2.17%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1        | 2.17%   |
| Samsung RAM M393B1K70DH0 8GB DIMM DDR3 1600MT/s         | 1        | 2.17%   |
| Samsung RAM M378B5773QB0-CK0 2GB DIMM DDR3 1600MT/s     | 1        | 2.17%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3              | 1        | 2.17%   |
| Samsung RAM M378B5173BH0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 2.17%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 1600MT/s     | 1        | 2.17%   |
| Ramaxel RAM RMR5030MN68F9F1600 4GB DIMM DDR3 1600MT/s   | 1        | 2.17%   |
| Nanya RAM M2F4G64CB8HG5N-CG 4GB DIMM DDR3 1333MT/s      | 1        | 2.17%   |
| Nanya RAM M2F2G64CB88G7N-CG 2GB DIMM DDR3 1333MT/s      | 1        | 2.17%   |
| Micron RAM 16KTF1G64HZ-1G6N1 8GB SODIMM DDR3 1600MT/s   | 1        | 2.17%   |
| Kingston RAM KHX3466C19D4/16G 16GB DIMM DDR4 3200MT/s   | 1        | 2.17%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s    | 1        | 2.17%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s       | 1        | 2.17%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2400MT/s | 1        | 2.17%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1600MT/s       | 1        | 2.17%   |
| Kingston RAM 99U5665-001.A00G 4GB DIMM DDR4 2400MT/s    | 1        | 2.17%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s   | 1        | 2.17%   |
| Kingston RAM 9905734-180.A00G 16GB DIMM DDR4 2666MT/s   | 1        | 2.17%   |
| Kingston RAM 9905665-020.A00G 4GB DIMM DDR4 2667MT/s    | 1        | 2.17%   |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s             | 1        | 2.17%   |
| Crucial RAM CT4G4DFS824A.C8FF 4GB DIMM DDR4 2667MT/s    | 1        | 2.17%   |
| Crucial RAM CT4G4DFS8213.C8FBD1 4GB DIMM DDR4 2133MT/s  | 1        | 2.17%   |
| Crucial RAM BLS8G4D240FSB.16FBD2 8GB DIMM DDR4 2400MT/s | 1        | 2.17%   |
| Crucial RAM BL8G32C16U4BL.M8FE 8GB DIMM DDR4 2667MT/s   | 1        | 2.17%   |
| Crucial RAM BL8G30C15U4B.M8FE 8GB DIMM DDR4 2666MT/s    | 1        | 2.17%   |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s    | 1        | 2.17%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 2133MT/s  | 1        | 2.17%   |
| Corsair RAM CMK16GX4M1A2400C14 16GB DIMM DDR4 2400MT/s  | 1        | 2.17%   |
| A-DATA RAM MI74C1C167HZ1 4GB SODIMM DDR3 1333MT/s       | 1        | 2.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 18       | 46.15%  |
| DDR3    | 16       | 41.03%  |
| Unknown | 2        | 5.13%   |
| SDRAM   | 1        | 2.56%   |
| DDR2    | 1        | 2.56%   |
| DDR     | 1        | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 34       | 87.18%  |
| SODIMM  | 4        | 10.26%  |
| FB-DIMM | 1        | 2.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 15       | 35.71%  |
| 4096  | 13       | 30.95%  |
| 16384 | 7        | 16.67%  |
| 2048  | 6        | 14.29%  |
| 32768 | 1        | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 11       | 26.83%  |
| 1333    | 7        | 17.07%  |
| 2667    | 6        | 14.63%  |
| 3200    | 4        | 9.76%   |
| 2400    | 4        | 9.76%   |
| 2666    | 2        | 4.88%   |
| 2133    | 2        | 4.88%   |
| 400     | 2        | 4.88%   |
| 1066    | 1        | 2.44%   |
| 667     | 1        | 2.44%   |
| Unknown | 1        | 2.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Lexmark International | 1        | 50%     |
| Brother Industries    | 1        | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Lexmark International SINDOH A603_A608 Print | 1        | 50%     |
| Brother DCP-J100                             | 1        | 50%     |

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
| Z-Star Microelectronics | 1        | 20%     |
| Logitech                | 1        | 20%     |
| IMC Networks            | 1        | 20%     |
| Hewlett-Packard         | 1        | 20%     |
| Chicony Electronics     | 1        | 20%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Z-Star A4 TECH USB2.0 PC Camera J | 1        | 20%     |
| Logitech Webcam C270              | 1        | 20%     |
| IMC Networks XHC Camera           | 1        | 20%     |
| HP Premium Starter Webcam         | 1        | 20%     |
| Chicony HP Display Camera         | 1        | 20%     |

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
| 1     | 18       | 47.37%  |
| 0     | 14       | 36.84%  |
| 2     | 5        | 13.16%  |
| 3     | 1        | 2.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 17       | 58.62%  |
| Net/wireless             | 6        | 20.69%  |
| Sound                    | 3        | 10.34%  |
| Net/ethernet             | 1        | 3.45%   |
| Firewire controller      | 1        | 3.45%   |
| Card reader              | 1        | 3.45%   |

