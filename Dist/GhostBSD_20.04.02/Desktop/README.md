GhostBSD 20.04.02 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for GhostBSD 20.04.02.

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

Total: 56

| Vendor   | Model                       | Probe                                                     | Date         |
|----------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek  | PRIME B350-PLUS             | [0ee3fe080c](https://bsd-hardware.info/?probe=0ee3fe080c) | Aug 30, 2021 |
| MSI      | H81M-P33                    | [6dcb3aa559](https://bsd-hardware.info/?probe=6dcb3aa559) | Aug 05, 2021 |
| ASRock   | X570 Pro4                   | [011fb96fe0](https://bsd-hardware.info/?probe=011fb96fe0) | Aug 04, 2021 |
| ASRock   | Z77 Extreme6                | [2521c70747](https://bsd-hardware.info/?probe=2521c70747) | Aug 02, 2021 |
| ASUSTek  | PRIME B350M-E               | [bde8057846](https://bsd-hardware.info/?probe=bde8057846) | Jun 29, 2021 |
| ASUSTek  | PRIME A320M-A               | [10d9e99990](https://bsd-hardware.info/?probe=10d9e99990) | May 31, 2021 |
| Lenovo   | Board                       | [428f39cbff](https://bsd-hardware.info/?probe=428f39cbff) | May 21, 2021 |
| ASUSTek  | V-P7H55E                    | [7634d3b6ca](https://bsd-hardware.info/?probe=7634d3b6ca) | May 12, 2021 |
| ASUSTek  | V-P7H55E                    | [f2e42a5ca3](https://bsd-hardware.info/?probe=f2e42a5ca3) | May 10, 2021 |
| ASUSTek  | V-P7H55E                    | [0af6399c18](https://bsd-hardware.info/?probe=0af6399c18) | May 10, 2021 |
| Dell     | 0TP412                      | [1bc05b5951](https://bsd-hardware.info/?probe=1bc05b5951) | Apr 04, 2021 |
| Huanan   | X79 INTEL (INTEL Xeon E5... | [ec9e43382e](https://bsd-hardware.info/?probe=ec9e43382e) | Mar 25, 2021 |
| HP       | 1850                        | [3055c06d45](https://bsd-hardware.info/?probe=3055c06d45) | Mar 22, 2021 |
| ASRock   | X570 Phantom Gaming 4       | [a64a4e0792](https://bsd-hardware.info/?probe=a64a4e0792) | Mar 19, 2021 |
| ASUSTek  | ROG STRIX B450-F GAMING     | [39a46ce44e](https://bsd-hardware.info/?probe=39a46ce44e) | Mar 06, 2021 |
| Gigabyte | EG43M-S2H                   | [f6eaa55ada](https://bsd-hardware.info/?probe=f6eaa55ada) | Mar 06, 2021 |
| Acer     | Aspire XC-115               | [95f63df64d](https://bsd-hardware.info/?probe=95f63df64d) | Feb 21, 2021 |
| Lenovo   | Kabini CRB 31900058 STD     | [c08ca084b0](https://bsd-hardware.info/?probe=c08ca084b0) | Feb 21, 2021 |
| ASRock   | AB350 Pro4                  | [3680c4cd75](https://bsd-hardware.info/?probe=3680c4cd75) | Feb 20, 2021 |
| ASUSTek  | PRIME B450-PLUS             | [ade306695d](https://bsd-hardware.info/?probe=ade306695d) | Feb 20, 2021 |
| Acer     | WG43M                       | [28a6795710](https://bsd-hardware.info/?probe=28a6795710) | Feb 15, 2021 |
| MSI      | PRESTIGE X570 CREATION      | [e6fa5753b5](https://bsd-hardware.info/?probe=e6fa5753b5) | Feb 12, 2021 |
| MSI      | PRESTIGE X570 CREATION      | [fd798dae01](https://bsd-hardware.info/?probe=fd798dae01) | Feb 12, 2021 |
| Dell     | 030VXY A01                  | [23e7163f58](https://bsd-hardware.info/?probe=23e7163f58) | Feb 10, 2021 |
| ASUSTek  | TUF GAMING X570-PLUS        | [cf41f72474](https://bsd-hardware.info/?probe=cf41f72474) | Jan 31, 2021 |
| Dell     | 0NW6H5 A00                  | [f6df3820b5](https://bsd-hardware.info/?probe=f6df3820b5) | Jan 18, 2021 |
| MSI      | Z97 GAMING 5                | [9ef0da6093](https://bsd-hardware.info/?probe=9ef0da6093) | Jan 16, 2021 |
| Dell     | 0KC9NP A01                  | [a9228fa7c3](https://bsd-hardware.info/?probe=a9228fa7c3) | Jan 15, 2021 |
| Dell     | 030VXY A01                  | [5af442bf61](https://bsd-hardware.info/?probe=5af442bf61) | Jan 15, 2021 |
| Dell     | 0HY9JP A02                  | [b4d2af272e](https://bsd-hardware.info/?probe=b4d2af272e) | Jan 05, 2021 |
| ASUSTek  | Z170I PRO GAMING            | [5124b24d30](https://bsd-hardware.info/?probe=5124b24d30) | Jan 04, 2021 |
| Fujitsu  | D3617-A1 S26361-D3617-A1    | [2a0187ef7a](https://bsd-hardware.info/?probe=2a0187ef7a) | Jan 02, 2021 |
| ASUSTek  | PRIME A320M-C R2.0          | [4c24fe6fc4](https://bsd-hardware.info/?probe=4c24fe6fc4) | Dec 24, 2020 |
| HP       | 0B4Ch D                     | [bf0d7fe4f1](https://bsd-hardware.info/?probe=bf0d7fe4f1) | Dec 22, 2020 |
| Gigabyte | Z370 AORUS Ultra Gaming-... | [a3a96da3fb](https://bsd-hardware.info/?probe=a3a96da3fb) | Dec 19, 2020 |
| ASUSTek  | TUF GAMING B550M-PLUS       | [464223cefe](https://bsd-hardware.info/?probe=464223cefe) | Dec 07, 2020 |
| ASRock   | B450 Gaming-ITX/ac          | [53bf449015](https://bsd-hardware.info/?probe=53bf449015) | Dec 02, 2020 |
| Quanta   | 2AF5 011                    | [172f23efac](https://bsd-hardware.info/?probe=172f23efac) | Nov 29, 2020 |
| ASRock   | AB350 Gaming-ITX/ac         | [8afa16fc20](https://bsd-hardware.info/?probe=8afa16fc20) | Nov 29, 2020 |
| Gigabyte | X470 AORUS ULTRA GAMING-... | [5d5ecb38cd](https://bsd-hardware.info/?probe=5d5ecb38cd) | Nov 25, 2020 |
| MSI      | B450 GAMING PLUS            | [4cf3dd682b](https://bsd-hardware.info/?probe=4cf3dd682b) | Nov 24, 2020 |
| MSI      | B450 GAMING PLUS            | [edee76372b](https://bsd-hardware.info/?probe=edee76372b) | Nov 21, 2020 |
| ASRock   | X570 Phantom Gaming 4       | [cc075b3932](https://bsd-hardware.info/?probe=cc075b3932) | Nov 15, 2020 |
| ASRock   | X570 Phantom Gaming 4       | [6a0c640524](https://bsd-hardware.info/?probe=6a0c640524) | Nov 12, 2020 |
| ASRock   | X570 Phantom Gaming 4       | [6060033216](https://bsd-hardware.info/?probe=6060033216) | Nov 12, 2020 |
| Gigabyte | Z97-D3H-CF                  | [dc33c84287](https://bsd-hardware.info/?probe=dc33c84287) | Oct 22, 2020 |
| Fujitsu  | D2950-A1 S26361-D2950-A1    | [86e9866c03](https://bsd-hardware.info/?probe=86e9866c03) | Oct 02, 2020 |
| Fujitsu  | D2950-A1 S26361-D2950-A1    | [3b8f8a2033](https://bsd-hardware.info/?probe=3b8f8a2033) | Oct 02, 2020 |
| MSI      | H61M-P20                    | [fefac5637b](https://bsd-hardware.info/?probe=fefac5637b) | Aug 03, 2020 |
| Gigabyte | F2A68HM-DS2                 | [0073f8ff71](https://bsd-hardware.info/?probe=0073f8ff71) | Aug 02, 2020 |
| Gigabyte | H67A-UD3H-B3                | [aa29eb9c75](https://bsd-hardware.info/?probe=aa29eb9c75) | Aug 01, 2020 |
| Unknown  | SKYBAY                      | [34bb81770b](https://bsd-hardware.info/?probe=34bb81770b) | Jul 22, 2020 |
| ASRock   | X370 Gaming K4              | [4473708fd0](https://bsd-hardware.info/?probe=4473708fd0) | Jul 22, 2020 |
| ASRock   | X370 Gaming K4              | [174569bf55](https://bsd-hardware.info/?probe=174569bf55) | Jul 21, 2020 |
| ASRock   | A300M-STX                   | [f62a2ace5a](https://bsd-hardware.info/?probe=f62a2ace5a) | Jul 16, 2020 |
| Lenovo   | Win8 Pro DPK TPG            | [db7146b868](https://bsd-hardware.info/?probe=db7146b868) | Jul 14, 2020 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 45       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| MATE             | 34       | 73.91%  |
| XFCE             | 7        | 15.22%  |
| KDE5             | 2        | 4.35%   |
| openbox          | 1        | 2.17%   |
| Metacity (Marco) | 1        | 2.17%   |
| i3               | 1        | 2.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 45       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| LightDM | 44       | 97.78%  |
| SDDM    | 1        | 2.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 21       | 45.65%  |
| Unknown | 11       | 23.91%  |
| ru_RU   | 4        | 8.7%    |
| de_DE   | 3        | 6.52%   |
| fr_FR   | 2        | 4.35%   |
| C       | 2        | 4.35%   |
| sk_SK   | 1        | 2.17%   |
| en_GB   | 1        | 2.17%   |
| en_AU   | 1        | 2.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 34       | 75.56%  |
| BIOS | 11       | 24.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 42       | 93.33%  |
| Ufs  | 3        | 6.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 41       | 91.11%  |
| MBR  | 4        | 8.89%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 9        | 20%     |
| ASRock              | 7        | 15.56%  |
| MSI                 | 6        | 13.33%  |
| Gigabyte Technology | 6        | 13.33%  |
| Dell                | 5        | 11.11%  |
| Lenovo              | 3        | 6.67%   |
| Hewlett-Packard     | 2        | 4.44%   |
| Fujitsu             | 2        | 4.44%   |
| Acer                | 2        | 4.44%   |
| Quanta              | 1        | 2.22%   |
| Huanan              | 1        | 2.22%   |
| Unknown             | 1        | 2.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                                  | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| MSI MS-7B86                                                           | 2        | 4.44%   |
| Quanta 120-1333w                                                      | 1        | 2.22%   |
| MSI MS-7C36                                                           | 1        | 2.22%   |
| MSI MS-7917                                                           | 1        | 2.22%   |
| MSI MS-7817                                                           | 1        | 2.22%   |
| MSI MS-7788                                                           | 1        | 2.22%   |
| Lenovo ThinkStation S10 6483CTO                                       | 1        | 2.22%   |
| Lenovo ThinkCentre Edge72 3493DEG                                     | 1        | 2.22%   |
| Lenovo H515s 10126                                                    | 1        | 2.22%   |
| Huanan X79 INTEL (INTEL Xeon E5/Corei7 DMI2 - C600/C200 Cipset V2.49P | 1        | 2.22%   |
| HP Z400 Workstation                                                   | 1        | 2.22%   |
| HP Compaq Pro 6305 SFF                                                | 1        | 2.22%   |
| Gigabyte Z97-D3H                                                      | 1        | 2.22%   |
| Gigabyte Z370 AORUS Ultra Gaming                                      | 1        | 2.22%   |
| Gigabyte X470 AORUS ULTRA GAMING                                      | 1        | 2.22%   |
| Gigabyte H67A-UD3H-B3                                                 | 1        | 2.22%   |
| Gigabyte F2A68HM-DS2                                                  | 1        | 2.22%   |
| Gigabyte EG43M-S2H                                                    | 1        | 2.22%   |
| Fujitsu ESPRIMO P1500                                                 | 1        | 2.22%   |
| Fujitsu CELSIUS W580                                                  | 1        | 2.22%   |
| Dell Precision WorkStation T3400                                      | 1        | 2.22%   |
| Dell OptiPlex 9020                                                    | 1        | 2.22%   |
| Dell OptiPlex 790                                                     | 1        | 2.22%   |
| Dell OptiPlex 7050                                                    | 1        | 2.22%   |
| Dell OptiPlex 5060                                                    | 1        | 2.22%   |
| ASUS Z170I PRO GAMING                                                 | 1        | 2.22%   |
| ASUS TUF GAMING X570-PLUS                                             | 1        | 2.22%   |
| ASUS TUF GAMING B550M-PLUS                                            | 1        | 2.22%   |
| ASUS ROG STRIX B450-F GAMING                                          | 1        | 2.22%   |
| ASUS PRIME B450-PLUS                                                  | 1        | 2.22%   |
| ASUS PRIME B350M-E                                                    | 1        | 2.22%   |
| ASUS PRIME B350-PLUS                                                  | 1        | 2.22%   |
| ASUS PRIME A320M-C R2.0                                               | 1        | 2.22%   |
| ASUS PRIME A320M-A                                                    | 1        | 2.22%   |
| ASRock Z77 Extreme6                                                   | 1        | 2.22%   |
| ASRock X570 Pro4                                                      | 1        | 2.22%   |
| ASRock X570 Phantom Gaming 4                                          | 1        | 2.22%   |
| ASRock X370 Gaming K4                                                 | 1        | 2.22%   |
| ASRock B450 Gaming-ITX/ac                                             | 1        | 2.22%   |
| ASRock AB350 Gaming-ITX/ac                                            | 1        | 2.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 5        | 11.11%  |
| Dell OptiPlex         | 4        | 8.89%   |
| MSI MS-7B86           | 2        | 4.44%   |
| ASUS TUF              | 2        | 4.44%   |
| ASRock X570           | 2        | 4.44%   |
| Acer Aspire           | 2        | 4.44%   |
| Quanta 120-1333w      | 1        | 2.22%   |
| MSI MS-7C36           | 1        | 2.22%   |
| MSI MS-7917           | 1        | 2.22%   |
| MSI MS-7817           | 1        | 2.22%   |
| MSI MS-7788           | 1        | 2.22%   |
| Lenovo ThinkStation   | 1        | 2.22%   |
| Lenovo ThinkCentre    | 1        | 2.22%   |
| Lenovo H515s          | 1        | 2.22%   |
| Huanan X79            | 1        | 2.22%   |
| HP Z400               | 1        | 2.22%   |
| HP Compaq             | 1        | 2.22%   |
| Gigabyte Z97-D3H      | 1        | 2.22%   |
| Gigabyte Z370         | 1        | 2.22%   |
| Gigabyte X470         | 1        | 2.22%   |
| Gigabyte H67A-UD3H-B3 | 1        | 2.22%   |
| Gigabyte F2A68HM-DS2  | 1        | 2.22%   |
| Gigabyte EG43M-S2H    | 1        | 2.22%   |
| Fujitsu ESPRIMO       | 1        | 2.22%   |
| Fujitsu CELSIUS       | 1        | 2.22%   |
| Dell Precision        | 1        | 2.22%   |
| ASUS Z170I            | 1        | 2.22%   |
| ASUS ROG              | 1        | 2.22%   |
| ASRock Z77            | 1        | 2.22%   |
| ASRock X370           | 1        | 2.22%   |
| ASRock B450           | 1        | 2.22%   |
| ASRock AB350          | 1        | 2.22%   |
| ASRock A300M-STX      | 1        | 2.22%   |
| Unknown               | 1        | 2.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 11       | 24.44%  |
| 2019 | 6        | 13.33%  |
| 2012 | 6        | 13.33%  |
| 2020 | 4        | 8.89%   |
| 2014 | 3        | 6.67%   |
| 2013 | 3        | 6.67%   |
| 2008 | 3        | 6.67%   |
| 2017 | 2        | 4.44%   |
| 2015 | 2        | 4.44%   |
| 2021 | 1        | 2.22%   |
| 2016 | 1        | 2.22%   |
| 2011 | 1        | 2.22%   |
| 2010 | 1        | 2.22%   |
| 2009 | 1        | 2.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 45       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 45       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 15       | 33.33%  |
| 8.01-16.0   | 10       | 22.22%  |
| 4.01-8.0    | 9        | 20%     |
| 32.01-64.0  | 8        | 17.78%  |
| 64.01-256.0 | 2        | 4.44%   |
| 24.01-32.0  | 1        | 2.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.51-1.0 | 21       | 46.67%  |
| 0.01-0.5 | 15       | 33.33%  |
| 1.01-2.0 | 7        | 15.56%  |
| 3.01-4.0 | 2        | 4.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 17       | 36.96%  |
| 1      | 16       | 34.78%  |
| 3      | 4        | 8.7%    |
| 5      | 3        | 6.52%   |
| 4      | 3        | 6.52%   |
| 6      | 2        | 4.35%   |
| 7      | 1        | 2.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 55.56%  |
| Yes       | 20       | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 45       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 31       | 68.89%  |
| Yes       | 14       | 31.11%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 75.56%  |
| Yes       | 11       | 24.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 10       | 22.22%  |
| Germany     | 6        | 13.33%  |
| Russia      | 5        | 11.11%  |
| France      | 5        | 11.11%  |
| UK          | 4        | 8.89%   |
| Norway      | 2        | 4.44%   |
| Australia   | 2        | 4.44%   |
| Ukraine     | 1        | 2.22%   |
| Switzerland | 1        | 2.22%   |
| Spain       | 1        | 2.22%   |
| Netherlands | 1        | 2.22%   |
| Malaysia    | 1        | 2.22%   |
| Luxembourg  | 1        | 2.22%   |
| Japan       | 1        | 2.22%   |
| Hungary     | 1        | 2.22%   |
| Finland     | 1        | 2.22%   |
| Czechia     | 1        | 2.22%   |
| Canada      | 1        | 2.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Paris            | 3        | 6.67%   |
| Berlin           | 3        | 6.67%   |
| Obninsk          | 2        | 4.44%   |
| ЕЊta-ku        | 1        | 2.22%   |
| Washington       | 1        | 2.22%   |
| Vidnoye          | 1        | 2.22%   |
| Veenendaal       | 1        | 2.22%   |
| Truro            | 1        | 2.22%   |
| Sydney           | 1        | 2.22%   |
| St Petersburg    | 1        | 2.22%   |
| Riedstadt        | 1        | 2.22%   |
| Richmond         | 1        | 2.22%   |
| Prague           | 1        | 2.22%   |
| Phoenix          | 1        | 2.22%   |
| Palm Bay         | 1        | 2.22%   |
| Oslo             | 1        | 2.22%   |
| Omaha            | 1        | 2.22%   |
| Moncton          | 1        | 2.22%   |
| Madrid           | 1        | 2.22%   |
| Luxembourg       | 1        | 2.22%   |
| Lorient          | 1        | 2.22%   |
| London           | 1        | 2.22%   |
| Larnod           | 1        | 2.22%   |
| Kyiv             | 1        | 2.22%   |
| Kuala Lumpur     | 1        | 2.22%   |
| JyvГ¤skylГ¤  | 1        | 2.22%   |
| Huntingdon       | 1        | 2.22%   |
| Heilbronn        | 1        | 2.22%   |
| Hamilton         | 1        | 2.22%   |
| Eiken            | 1        | 2.22%   |
| Drammen          | 1        | 2.22%   |
| Denver           | 1        | 2.22%   |
| Delton           | 1        | 2.22%   |
| Dandenong        | 1        | 2.22%   |
| Dabas            | 1        | 2.22%   |
| Colorado Springs | 1        | 2.22%   |
| Cologne          | 1        | 2.22%   |
| Chelyabinsk      | 1        | 2.22%   |
| Banbury          | 1        | 2.22%   |
| Atascadero       | 1        | 2.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 21       | 29     | 23.86%  |
| Samsung Electronics | 15       | 19     | 17.05%  |
| Seagate             | 10       | 12     | 11.36%  |
| Crucial             | 7        | 8      | 7.95%   |
| Toshiba             | 5        | 5      | 5.68%   |
| Hitachi             | 4        | 4      | 4.55%   |
| SanDisk             | 3        | 3      | 3.41%   |
| Kingston            | 3        | 3      | 3.41%   |
| A-DATA Technology   | 3        | 3      | 3.41%   |
| Micron Technology   | 2        | 2      | 2.27%   |
| Maxtor              | 2        | 2      | 2.27%   |
| HGST                | 2        | 2      | 2.27%   |
| Transcend           | 1        | 1      | 1.14%   |
| SPCC                | 1        | 1      | 1.14%   |
| PNY                 | 1        | 3      | 1.14%   |
| Plextor             | 1        | 1      | 1.14%   |
| Phison              | 1        | 2      | 1.14%   |
| Patriot             | 1        | 1      | 1.14%   |
| OCZ                 | 1        | 1      | 1.14%   |
| LDLC                | 1        | 1      | 1.14%   |
| Intel               | 1        | 1      | 1.14%   |
| HPT                 | 1        | 4      | 1.14%   |
| AMD                 | 1        | 1      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| WDC WD40EFRX-68N32N0 4TB           | 2        | 2.04%   |
| WDC WD2000JS-55MHB0 192GB          | 2        | 2.04%   |
| WDC WD10EZEX-21M2NA0 1TB           | 2        | 2.04%   |
| Toshiba Q300 480GB                 | 2        | 2.04%   |
| Toshiba HDWD120 2TB                | 2        | 2.04%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 2.04%   |
| Samsung SSD 860 QVO 1TB            | 2        | 2.04%   |
| Maxtor STM3320613AS 320GB          | 2        | 2.04%   |
| Crucial CT250MX500SSD1 250GB       | 2        | 2.04%   |
| Crucial CT1000MX500SSD1 1TB        | 2        | 2.04%   |
| WDC WDS500G2B0A-00SM50 500GB       | 1        | 1.02%   |
| WDC WDS500G2B0A 500GB              | 1        | 1.02%   |
| WDC WDS100T3X0C-00SJG0 1TB         | 1        | 1.02%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 1        | 1.02%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1        | 1.02%   |
| WDC WD800BEVT-75ZCT2 80GB          | 1        | 1.02%   |
| WDC WD60EZRZ-00GZ5B1 6TB           | 1        | 1.02%   |
| WDC WD6003FFBX-68MU3N0 6TB         | 1        | 1.02%   |
| WDC WD5000LPLX-75ZNTT0 500GB       | 1        | 1.02%   |
| WDC WD5000AAVS-00ZTB0 500GB        | 1        | 1.02%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1        | 1.02%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1        | 1.02%   |
| WDC WD5000AAKS-60WWPA0 500GB       | 1        | 1.02%   |
| WDC WD2500AAJS-75M0A0 250GB        | 1        | 1.02%   |
| WDC WD20SPZX-22UA7T0 2TB           | 1        | 1.02%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 1        | 1.02%   |
| WDC WD10EALX-009BA0 1TB            | 1        | 1.02%   |
| Transcend TS120GMTS820S 120GB      | 1        | 1.02%   |
| Toshiba MQ01ABD100 1TB             | 1        | 1.02%   |
| SPCC Solid State Disk 240GB        | 1        | 1.02%   |
| Seagate ST3500312CS 500GB          | 1        | 1.02%   |
| Seagate ST31500541AS 1.5TB         | 1        | 1.02%   |
| Seagate ST31000528AS 1TB           | 1        | 1.02%   |
| Seagate ST2000NM0008-2F3100 2TB    | 1        | 1.02%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1.02%   |
| Seagate ST2000DM008-2FR102 2TB     | 1        | 1.02%   |
| Seagate ST1000VM002-1SD102 1TB     | 1        | 1.02%   |
| Seagate ST1000LM049-2GH172 1TB     | 1        | 1.02%   |
| Seagate ST1000DM003-1SB102 1TB     | 1        | 1.02%   |
| SanDisk SSD PLUS 240 GB            | 1        | 1.02%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 24     | 40.91%  |
| Seagate             | 10       | 12     | 22.73%  |
| Samsung Electronics | 4        | 5      | 9.09%   |
| Hitachi             | 4        | 4      | 9.09%   |
| Toshiba             | 3        | 3      | 6.82%   |
| Maxtor              | 2        | 2      | 4.55%   |
| HGST                | 2        | 2      | 4.55%   |
| HPT                 | 1        | 4      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 10       | 10     | 27.03%  |
| Crucial             | 6        | 7      | 16.22%  |
| SanDisk             | 3        | 3      | 8.11%   |
| A-DATA Technology   | 3        | 3      | 8.11%   |
| WDC                 | 2        | 2      | 5.41%   |
| Toshiba             | 2        | 2      | 5.41%   |
| Micron Technology   | 2        | 2      | 5.41%   |
| Kingston            | 2        | 2      | 5.41%   |
| Transcend           | 1        | 1      | 2.7%    |
| SPCC                | 1        | 1      | 2.7%    |
| PNY                 | 1        | 3      | 2.7%    |
| Plextor             | 1        | 1      | 2.7%    |
| Patriot             | 1        | 1      | 2.7%    |
| OCZ                 | 1        | 1      | 2.7%    |
| AMD                 | 1        | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 33       | 56     | 47.83%  |
| SSD  | 25       | 40     | 36.23%  |
| NVMe | 11       | 13     | 15.94%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 44       | 96     | 80%     |
| NVMe | 11       | 13     | 20%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 35       | 49     | 53.03%  |
| 0.51-1.0   | 17       | 27     | 25.76%  |
| 1.01-2.0   | 8        | 10     | 12.12%  |
| 3.01-4.0   | 4        | 4      | 6.06%   |
| 4.01-10.0  | 2        | 6      | 3.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 13       | 28.26%  |
| 101-250    | 12       | 26.09%  |
| 1-20       | 9        | 19.57%  |
| 51-100     | 5        | 10.87%  |
| 501-1000   | 3        | 6.52%   |
| Unknown    | 3        | 6.52%   |
| 1001-2000  | 1        | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 37       | 82.22%  |
| 21-50   | 5        | 11.11%  |
| Unknown | 3        | 6.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Maxtor STM3320613AS 320GB       | 2        | 2      | 20%     |
| WDC WD5000AAKS-60WWPA0 500GB    | 1        | 1      | 10%     |
| WDC WD10EZEX-21M2NA0 1TB        | 1        | 1      | 10%     |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 10%     |
| Seagate ST31500541AS 1.5TB      | 1        | 1      | 10%     |
| Samsung Electronics HD103SJ 1TB | 1        | 2      | 10%     |
| OCZ AGILITY3 240GB              | 1        | 1      | 10%     |
| Hitachi HTS547575A9E384 752GB   | 1        | 1      | 10%     |
| Hitachi HTS541680J9SA00 80GB    | 1        | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 20%     |
| Seagate             | 2        | 2      | 20%     |
| Maxtor              | 2        | 2      | 20%     |
| Hitachi             | 2        | 2      | 20%     |
| Samsung Electronics | 1        | 2      | 10%     |
| OCZ                 | 1        | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 22.22%  |
| Seagate             | 2        | 2      | 22.22%  |
| Maxtor              | 2        | 2      | 22.22%  |
| Hitachi             | 2        | 2      | 22.22%  |
| Samsung Electronics | 1        | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 8        | 10     | 88.89%  |
| SSD  | 1        | 1      | 11.11%  |

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
| Works    | 44       | 94     | 81.48%  |
| Malfunc  | 9        | 11     | 16.67%  |
| Detected | 1        | 4      | 1.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| AMD                           | 23       | 37.1%   |
| Intel                         | 22       | 35.48%  |
| Samsung Electronics           | 4        | 6.45%   |
| SanDisk                       | 2        | 3.23%   |
| ASMedia Technology            | 2        | 3.23%   |
| Silicon Motion                | 1        | 1.61%   |
| Phison Electronics            | 1        | 1.61%   |
| Nvidia                        | 1        | 1.61%   |
| Micron/Crucial Technology     | 1        | 1.61%   |
| Marvell Technology Group      | 1        | 1.61%   |
| Kingston Technology Company   | 1        | 1.61%   |
| Integrated Technology Express | 1        | 1.61%   |
| HighPoint Technologies        | 1        | 1.61%   |
| Adaptec                       | 1        | 1.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 19       | 24.36%  |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 7.69%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 6.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3        | 3.85%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 3.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2        | 2.56%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2        | 2.56%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 2        | 2.56%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2        | 2.56%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2        | 2.56%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 2.56%   |
| AMD FCH SATA Controller D                                                               | 2        | 2.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 1.28%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 1        | 1.28%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1        | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 1.28%   |
| Phison E12 NVMe Controller                                                              | 1        | 1.28%   |
| Nvidia GeForce 7100/nForce 630i SATA                                                    | 1        | 1.28%   |
| Micron/Crucial NVMe Storage Controller                                                  | 1        | 1.28%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 1.28%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 1.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1        | 1.28%   |
| Intel SSD 660P Series                                                                   | 1        | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 1        | 1.28%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 1.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1        | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1        | 1.28%   |
| Integrated Express IT8213 IDE Controller                                                | 1        | 1.28%   |
| HighPoint RocketRAID 230x 4 Port SATA-II Controller                                     | 1        | 1.28%   |
| AMD X370 Series Chipset SATA Controller                                                 | 1        | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                                  | 1        | 1.28%   |
| Adaptec AIC-7850T/7856T [AVA-2902/4/6 / AHA-2910]                                       | 1        | 1.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 35       | 58.33%  |
| NVMe | 11       | 18.33%  |
| IDE  | 7        | 11.67%  |
| RAID | 5        | 8.33%   |
| SCSI | 2        | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 23       | 51.11%  |
| Intel  | 22       | 48.89%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor             | 3        | 6.67%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 3        | 6.67%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 3        | 6.67%   |
| Intel Xeon CPU W3680 @ 3.33GHz                 | 1        | 2.22%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz             | 1        | 2.22%   |
| Intel Xeon                                     | 1        | 2.22%   |
| Intel Unknown                                  | 1        | 2.22%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz    | 1        | 2.22%   |
| Intel Pentium CPU G620 @ 2.60GHz               | 1        | 2.22%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 2.22%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 1        | 2.22%   |
| Intel Core i7-3770S CPU @ 3.10GHz              | 1        | 2.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 1        | 2.22%   |
| Intel Core i7-2600K CPU                        | 1        | 2.22%   |
| Intel Core i5-8600K CPU @ 3.60GHz              | 1        | 2.22%   |
| Intel Core i5-8400T CPU @ 1.70GHz              | 1        | 2.22%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 1        | 2.22%   |
| Intel Core i5-6600K CPU @ 3.50GHz              | 1        | 2.22%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 2.22%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 2.22%   |
| Intel Core i5-2500 CPU @ 3.30GH                | 1        | 2.22%   |
| Intel Core i3-7100U CPU @ 2.40GHz              | 1        | 2.22%   |
| Intel Core i3-4160 CPU @ 3.60GHz               | 1        | 2.22%   |
| Intel Core 2 Quad CPU Q9400                    | 1        | 2.22%   |
| Intel Core 2 Quad CPU                          | 1        | 2.22%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1        | 2.22%   |
| AMD Ryzen 5 3600XT 6-Core Processor            | 1        | 2.22%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1        | 2.22%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 1        | 2.22%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 1        | 2.22%   |
| AMD Ryzen 3 PRO 4350G with Radeon Graphics     | 1        | 2.22%   |
| AMD Ryzen 3 3100 4-Core Processor              | 1        | 2.22%   |
| AMD Ryzen 3 1200 Quad-Core Processor           | 1        | 2.22%   |
| AMD E2-6110 APU with AMD Radeon R2 Graphics    | 1        | 2.22%   |
| AMD E1-2500 APU with Radeon HD Graphics        | 1        | 2.22%   |
| AMD E1-1200 APU with Radeon HD Graphics        | 1        | 2.22%   |
| AMD Athlon X4 760K Quad Core Processor         | 1        | 2.22%   |
| AMD A6-6400K APU with Radeon HD Graphics       | 1        | 2.22%   |
| AMD A10-9700 RADEON R7, 10 COMPUTE CORES 4C+6G | 1        | 2.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 7        | 15.56%  |
| AMD Ryzen 5             | 7        | 15.56%  |
| AMD Ryzen 7             | 6        | 13.33%  |
| Intel Core i7           | 5        | 11.11%  |
| Intel Xeon              | 3        | 6.67%   |
| Intel Core i3           | 2        | 4.44%   |
| Intel Core 2 Quad       | 2        | 4.44%   |
| AMD Ryzen 3             | 2        | 4.44%   |
| AMD E1                  | 2        | 4.44%   |
| Other                   | 1        | 2.22%   |
| Intel Pentium Dual-Core | 1        | 2.22%   |
| Intel Pentium           | 1        | 2.22%   |
| AMD Ryzen 9             | 1        | 2.22%   |
| AMD Ryzen 3 PRO         | 1        | 2.22%   |
| AMD E2                  | 1        | 2.22%   |
| AMD Athlon X4           | 1        | 2.22%   |
| AMD A6                  | 1        | 2.22%   |
| AMD A10                 | 1        | 2.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 14       | 31.11%  |
| 2       | 8        | 17.78%  |
| 16      | 6        | 13.33%  |
| 12      | 6        | 13.33%  |
| 6       | 5        | 11.11%  |
| 8       | 3        | 6.67%   |
| Unknown | 2        | 4.44%   |
| 32      | 1        | 2.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 45       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 34       | 75.56%  |
| 2       | 9        | 20%     |
| Unknown | 2        | 4.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 2       | 7        | 15.56%  |
| Zen+        | 6        | 13.33%  |
| Penryn      | 5        | 11.11%  |
| KabyLake    | 5        | 11.11%  |
| SandyBridge | 4        | 8.89%   |
| Haswell     | 4        | 8.89%   |
| Zen         | 3        | 6.67%   |
| Piledriver  | 2        | 4.44%   |
| IvyBridge   | 2        | 4.44%   |
| Zen 3       | 1        | 2.22%   |
| Westmere    | 1        | 2.22%   |
| Skylake     | 1        | 2.22%   |
| Puma        | 1        | 2.22%   |
| Jaguar      | 1        | 2.22%   |
| Excavator   | 1        | 2.22%   |
| Bobcat      | 1        | 2.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 26       | 55.32%  |
| AMD    | 11       | 23.4%   |
| Intel  | 10       | 21.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 3        | 6.25%   |
| Nvidia GM206 [GeForce GTX 960]                                            | 3        | 6.25%   |
| Nvidia GK107 [GeForce GTX 650]                                            | 3        | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3        | 6.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3        | 6.25%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 2        | 4.17%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                        | 2        | 4.17%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 2        | 4.17%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 2        | 4.17%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                        | 1        | 2.08%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                     | 1        | 2.08%   |
| Nvidia TU104 [GeForce RTX 2080]                                           | 1        | 2.08%   |
| Nvidia GP107 [GeForce GTX 1050]                                           | 1        | 2.08%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 1        | 2.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                           | 1        | 2.08%   |
| Nvidia GM107 [GeForce GTX 745]                                            | 1        | 2.08%   |
| Nvidia GK107 [GeForce GT 740]                                             | 1        | 2.08%   |
| Nvidia GK107 [GeForce GT 640]                                             | 1        | 2.08%   |
| Nvidia GF108GL [Quadro 600]                                               | 1        | 2.08%   |
| Nvidia GF100GL [Quadro 4000]                                              | 1        | 2.08%   |
| Nvidia GA104 [GeForce RTX 3070]                                           | 1        | 2.08%   |
| Intel HD Graphics 630                                                     | 1        | 2.08%   |
| Intel HD Graphics 620                                                     | 1        | 2.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 2.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller | 1        | 2.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                     | 1        | 2.08%   |
| AMD Wrestler [Radeon HD 7310]                                             | 1        | 2.08%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 1        | 2.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1        | 2.08%   |
| AMD Mullins [Radeon R2 Graphics]                                          | 1        | 2.08%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                          | 1        | 2.08%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                   | 1        | 2.08%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                         | 1        | 2.08%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 1        | 2.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 23       | 51.11%  |
| 1 x AMD        | 10       | 22.22%  |
| 1 x Intel      | 8        | 17.78%  |
| 2 x Nvidia     | 1        | 2.22%   |
| 2 x Intel      | 1        | 2.22%   |
| Intel + Nvidia | 1        | 2.22%   |
| AMD + Nvidia   | 1        | 2.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Proprietary | 25       | 55.56%  |
| Free        | 20       | 44.44%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 28.89%  |
| 1.01-2.0   | 8        | 17.78%  |
| 7.01-8.0   | 7        | 15.56%  |
| 3.01-4.0   | 7        | 15.56%  |
| 0.51-1.0   | 6        | 13.33%  |
| 0.01-0.5   | 3        | 6.67%   |
| 2.01-3.0   | 1        | 2.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 6        | 13.33%  |
| Dell                 | 6        | 13.33%  |
| Samsung Electronics  | 4        | 8.89%   |
| Philips              | 3        | 6.67%   |
| BenQ                 | 3        | 6.67%   |
| ViewSonic            | 2        | 4.44%   |
| LG Electronics       | 2        | 4.44%   |
| Lenovo               | 2        | 4.44%   |
| Iiyama               | 2        | 4.44%   |
| Hewlett-Packard      | 2        | 4.44%   |
| AOC                  | 2        | 4.44%   |
| WYT                  | 1        | 2.22%   |
| Vizio                | 1        | 2.22%   |
| Toshiba              | 1        | 2.22%   |
| Pixio                | 1        | 2.22%   |
| OEM                  | 1        | 2.22%   |
| Idek Iiyama          | 1        | 2.22%   |
| HannStar             | 1        | 2.22%   |
| CHD                  | 1        | 2.22%   |
| ASUSTek Computer     | 1        | 2.22%   |
| Ancor Communications | 1        | 2.22%   |
| Acer                 | 1        | 2.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 2        | 4.08%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                   | 1        | 2.04%   |
| Vizio E320i-B2 VIZ1002 1360x768 700x400mm 31.7-inch                    | 1        | 2.04%   |
| ViewSonic VX3209-2K VSC328E 2560x1440 700x390mm 31.5-inch              | 1        | 2.04%   |
| ViewSonic LCD Monitor VA1938 Series                                    | 1        | 2.04%   |
| Toshiba TV TSB010F 1920x1080 890x500mm 40.2-inch                       | 1        | 2.04%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 480x270mm 21.7-inch     | 1        | 2.04%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 480x270mm 21.7-inch  | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1        | 2.04%   |
| Samsung Electronics LCD Monitor SAM02A4 1360x768                       | 1        | 2.04%   |
| Pixio PX247 PNS0247 1920x1080 520x310mm 23.8-inch                      | 1        | 2.04%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                | 1        | 2.04%   |
| Philips LCD Monitor PHL 240V5 1920x1080                                | 1        | 2.04%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 1        | 2.04%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                        | 1        | 2.04%   |
| LG Electronics LCD Monitor W1952 2806x900                              | 1        | 2.04%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                      | 1        | 2.04%   |
| Lenovo V20-10 LEN65DC 1600x900 430x240mm 19.4-inch                     | 1        | 2.04%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch               | 1        | 2.04%   |
| Iiyama PL2783Q IVM661F 2560x1440 600x340mm 27.2-inch                   | 1        | 2.04%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                   | 1        | 2.04%   |
| Idek Iiyama LCD Monitor PL3270Q 5120x1440                              | 1        | 2.04%   |
| Idek Iiyama LCD Monitor PL3270Q                                        | 1        | 2.04%   |
| Hewlett-Packard LCD Monitor HWP4218 1600x900 440x250mm 19.9-inch       | 1        | 2.04%   |
| Hewlett-Packard LA2205 HWP2848 1680x1050 470x300mm 22.0-inch           | 1        | 2.04%   |
| HannStar LCD Monitor HSD2469 1680x1050 470x300mm 22.0-inch             | 1        | 2.04%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                   | 1        | 2.04%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 1        | 2.04%   |
| Goldstar LG ULTRAWIDE GSM76FA 2560x1080 800x340mm 34.2-inch            | 1        | 2.04%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 1        | 2.04%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 1        | 2.04%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 1        | 2.04%   |
| Goldstar E2241 GSM5818 1920x1080 480x270mm 21.7-inch                   | 1        | 2.04%   |
| Dell S2417DG DELA0E7 2560x1440 530x300mm 24.0-inch                     | 1        | 2.04%   |
| Dell P2317H DEL40F2 1920x1080 510x290mm 23.1-inch                      | 1        | 2.04%   |
| Dell P1917S DELD092 1280x1024 380x300mm 19.1-inch                      | 1        | 2.04%   |
| Dell LCD Monitor U3818DW 3840x1600                                     | 1        | 2.04%   |
| Dell LCD Monitor 1908FP 3200x1080                                      | 1        | 2.04%   |
| Dell E1715S DELD062 1280x1024 340x270mm 17.1-inch                      | 1        | 2.04%   |
| CHD M27 CHD0270 1920x1080 530x290mm 23.8-inch                          | 1        | 2.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 17       | 34.69%  |
| 2560x1440 (QHD)    | 6        | 12.24%  |
| 3840x2160 (4K)     | 4        | 8.16%   |
| 2560x1080          | 3        | 6.12%   |
| 1600x900 (HD+)     | 3        | 6.12%   |
| 1280x1024 (SXGA)   | 3        | 6.12%   |
| Unknown            | 3        | 6.12%   |
| 1680x1050 (WSXGA+) | 2        | 4.08%   |
| 1360x768           | 2        | 4.08%   |
| 5120x1440          | 1        | 2.04%   |
| 3840x1600          | 1        | 2.04%   |
| 3200x1080          | 1        | 2.04%   |
| 2806x900           | 1        | 2.04%   |
| 1920x540           | 1        | 2.04%   |
| 1440x900 (WXGA+)   | 1        | 2.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 8        | 17.78%  |
| 27      | 7        | 15.56%  |
| 23      | 5        | 11.11%  |
| 21      | 5        | 11.11%  |
| 19      | 5        | 11.11%  |
| 24      | 3        | 6.67%   |
| 34      | 2        | 4.44%   |
| 31      | 2        | 4.44%   |
| 22      | 2        | 4.44%   |
| 65      | 1        | 2.22%   |
| 54      | 1        | 2.22%   |
| 40      | 1        | 2.22%   |
| 32      | 1        | 2.22%   |
| 17      | 1        | 2.22%   |
| 16      | 1        | 2.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 13       | 28.89%  |
| 401-500     | 11       | 24.44%  |
| Unknown     | 8        | 17.78%  |
| 601-700     | 4        | 8.89%   |
| 701-800     | 3        | 6.67%   |
| 301-350     | 2        | 4.44%   |
| 1001-1500   | 2        | 4.44%   |
| 801-900     | 1        | 2.22%   |
| 351-400     | 1        | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 28       | 65.12%  |
| Unknown | 6        | 13.95%  |
| 16/10   | 3        | 6.98%   |
| 5/4     | 2        | 4.65%   |
| 21/9    | 2        | 4.65%   |
| 6/5     | 1        | 2.33%   |
| 32/9    | 1        | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 15       | 33.33%  |
| Unknown        | 8        | 17.78%  |
| 301-350        | 7        | 15.56%  |
| 351-500        | 5        | 11.11%  |
| 151-200        | 5        | 11.11%  |
| More than 1000 | 2        | 4.44%   |
| 141-150        | 1        | 2.22%   |
| 131-140        | 1        | 2.22%   |
| 501-1000       | 1        | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 24       | 52.17%  |
| 101-120 | 8        | 17.39%  |
| Unknown | 8        | 17.39%  |
| 121-160 | 3        | 6.52%   |
| 1-50    | 2        | 4.35%   |
| 161-240 | 1        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 31       | 67.39%  |
| 2     | 9        | 19.57%  |
| 0     | 6        | 13.04%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 22       | 37.93%  |
| Intel                 | 20       | 34.48%  |
| Broadcom              | 5        | 8.62%   |
| Qualcomm Atheros      | 4        | 6.9%    |
| TP-Link               | 2        | 3.45%   |
| Ralink                | 1        | 1.72%   |
| Qualcomm              | 1        | 1.72%   |
| Nvidia                | 1        | 1.72%   |
| Microchip Technology  | 1        | 1.72%   |
| Aquantia              | 1        | 1.72%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17       | 26.56%  |
| Intel I211 Gigabit Network Connection                             | 8        | 12.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 4.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 4.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2        | 3.13%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 3.13%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 3.13%   |
| TP-Link Wireless USB Adapter                                      | 1        | 1.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1        | 1.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1        | 1.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 1.56%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1        | 1.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 1.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1        | 1.56%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1        | 1.56%   |
| Nvidia MCP73 Ethernet                                             | 1        | 1.56%   |
| Microchip HTC Hub Controller                                      | 1        | 1.56%   |
| Intel Wireless-AC 9260                                            | 1        | 1.56%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 1.56%   |
| Intel Ethernet Connection I217-V                                  | 1        | 1.56%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 1.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 1.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 1.56%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 1.56%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 1.56%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 1.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 1.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 1.56%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 1.56%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 1.56%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 1.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 35.71%  |
| Realtek Semiconductor | 3        | 21.43%  |
| Qualcomm Atheros      | 3        | 21.43%  |
| TP-Link               | 2        | 14.29%  |
| Ralink                | 1        | 7.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3        | 21.43%  |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2        | 14.29%  |
| TP-Link Wireless USB Adapter                                   | 1        | 7.14%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1        | 7.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 7.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 7.14%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 7.14%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1        | 7.14%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1        | 7.14%   |
| Intel Wireless-AC 9260                                         | 1        | 7.14%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 7.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 21       | 43.75%  |
| Intel                 | 18       | 37.5%   |
| Broadcom              | 5        | 10.42%  |
| Qualcomm Atheros      | 1        | 2.08%   |
| Qualcomm              | 1        | 2.08%   |
| Nvidia                | 1        | 2.08%   |
| Aquantia              | 1        | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17       | 34.69%  |
| Intel I211 Gigabit Network Connection                             | 8        | 16.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 6.12%   |
| Intel Ethernet Connection (2) I219-V                              | 2        | 4.08%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 4.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1        | 2.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.04%   |
| Qualcomm ALCATEL RNDIS Interface                                  | 1        | 2.04%   |
| Nvidia MCP73 Ethernet                                             | 1        | 2.04%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 1        | 2.04%   |
| Intel Ethernet Connection (7) I219-V                              | 1        | 2.04%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 2.04%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1        | 2.04%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 2.04%   |
| Intel 82567V-2 Gigabit Network Connection                         | 1        | 2.04%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1        | 2.04%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 2.04%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 2.04%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 1        | 2.04%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 45       | 75%     |
| WiFi     | 14       | 23.33%  |
| Modem    | 1        | 1.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 81.48%  |
| WiFi     | 10       | 18.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 32       | 71.11%  |
| 2     | 11       | 24.44%  |
| 3     | 2        | 4.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 45       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 4        | 40%     |
| Cambridge Silicon Radio  | 2        | 20%     |
| Broadcom                 | 2        | 20%     |
| HTC (High Tech Computer) | 1        | 10%     |
| ASUSTek Computer         | 1        | 10%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wireless-AC 3168 Bluetooth                                     | 3        | 30%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 2        | 20%     |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 20%     |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 1        | 10%     |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 10%     |
| ASUS Realtek Bluetooth 4.0 + High Speed Chip                         | 1        | 10%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Nvidia               | 26       | 31.71%  |
| AMD                  | 25       | 30.49%  |
| Intel                | 20       | 24.39%  |
| SteelSeries ApS      | 2        | 2.44%   |
| Logitech             | 2        | 2.44%   |
| VIA Technologies     | 1        | 1.22%   |
| Nam Tai E&E Products | 1        | 1.22%   |
| JMTek                | 1        | 1.22%   |
| Focusrite-Novation   | 1        | 1.22%   |
| Creative Technology  | 1        | 1.22%   |
| Creative Labs        | 1        | 1.22%   |
| C-Media Electronics  | 1        | 1.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 8        | 8.51%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 7        | 7.45%   |
| Nvidia GK107 HDMI Audio Controller                                                              | 5        | 5.32%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 4        | 4.26%   |
| Nvidia GP104 High Definition Audio Controller                                                   | 4        | 4.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 4        | 4.26%   |
| AMD FCH Azalia Controller                                                                       | 4        | 4.26%   |
| Nvidia GM206 High Definition Audio Controller                                                   | 3        | 3.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                   | 3        | 3.19%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                | 3        | 3.19%   |
| AMD Kabini HDMI/DP Audio                                                                        | 3        | 3.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 3        | 3.19%   |
| SteelSeries ApS SteelSeries Arctis 7 Arctis 7 Chat Arctis 7 Game SteelSeries Arctis 7           | 2        | 2.13%   |
| Nvidia GP108 High Definition Audio Controller                                                   | 2        | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                                      | 2        | 2.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                  | 2        | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 2        | 2.13%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 2        | 2.13%   |
| Intel 200 Series PCH HD Audio                                                                   | 2        | 2.13%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 2        | 2.13%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 2        | 2.13%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                     | 1        | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 1        | 1.06%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 1        | 1.06%   |
| Nvidia TU104 HD Audio Controller                                                                | 1        | 1.06%   |
| Nvidia MCP73 High Definition Audio                                                              | 1        | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 1        | 1.06%   |
| Nvidia GF100 High Definition Audio Controller                                                   | 1        | 1.06%   |
| Nvidia GA104 High Definition Audio Controller                                                   | 1        | 1.06%   |
| Nam Tai E&E Products Sony SingStar USBMIC                                                       | 1        | 1.06%   |
| Logitech Logitech USB Microphone                                                                | 1        | 1.06%   |
| Logitech HD Webcam C510                                                                         | 1        | 1.06%   |
| JMTek Sharkoon 7.1 Sound Extension                                                              | 1        | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 1        | 1.06%   |
| Intel Sunrise Point-LP HD Audio                                                                 | 1        | 1.06%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 1        | 1.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 1        | 1.06%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                                     | 1        | 1.06%   |
| Creative Technology Sound Blaster Omni Surround 5.1                                             | 1        | 1.06%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 10       | 19.61%  |
| G.Skill             | 10       | 19.61%  |
| Corsair             | 7        | 13.73%  |
| Samsung Electronics | 6        | 11.76%  |
| Unknown             | 5        | 9.8%    |
| SK hynix            | 5        | 9.8%    |
| Crucial             | 4        | 7.84%   |
| A-DATA Technology   | 2        | 3.92%   |
| S                   | 1        | 1.96%   |
| Nanya Technology    | 1        | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s    | 3        | 5.66%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s  | 3        | 5.66%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 1        | 1.89%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 1        | 1.89%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s              | 1        | 1.89%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 1        | 1.89%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 1        | 1.89%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 1.89%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s   | 1        | 1.89%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s   | 1        | 1.89%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 1.89%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s | 1        | 1.89%   |
| Samsung RAM M393B5170FH0 4GB DIMM DDR3 1600MT/s        | 1        | 1.89%   |
| Samsung RAM M391B5273DH0-CH9 4GB DIMM DDR3 1333MT/s    | 1        | 1.89%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 1        | 1.89%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 1.89%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 1        | 1.89%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s   | 1        | 1.89%   |
| S RAM Module 4GB DIMM DDR3 1600MT/s                    | 1        | 1.89%   |
| Nanya RAM NT2GT72U8PD0BY-3C 2GB DIMM DDR2 667MT/s      | 1        | 1.89%   |
| Kingston RAM Module 4GB DIMM DDR3 1600MT/s             | 1        | 1.89%   |
| Kingston RAM Module 2GB DIMM DDR3 1333MT/s             | 1        | 1.89%   |
| Kingston RAM KHX3000C15/16GX 16GB DIMM DDR4 2400MT/s   | 1        | 1.89%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 2667MT/s      | 1        | 1.89%   |
| Kingston RAM KHX2666C13/8GX 8GB DIMM DDR4 2400MT/s     | 1        | 1.89%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 2400MT/s    | 1        | 1.89%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s    | 1        | 1.89%   |
| Kingston RAM 99U5595-003.A00LF 2GB DIMM DDR3 1600MT/s  | 1        | 1.89%   |
| Kingston RAM 99P5474-013.A 4096MB DIMM DDR3 1600MT/s   | 1        | 1.89%   |
| Kingston RAM 9905625-062.A00G 8GB DIMM DDR4 2133MT/s   | 1        | 1.89%   |
| G.Skill RAM F4-3600C17-16GTZSW 16GB DIMM DDR4 3600MT/s | 1        | 1.89%   |
| G.Skill RAM F4-3600C16-8GTZ 8GB DIMM DDR4 2133MT/s     | 1        | 1.89%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s    | 1        | 1.89%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s   | 1        | 1.89%   |
| G.Skill RAM F4-2400C16-16GFT 16GB DIMM DDR4 2400MT/s   | 1        | 1.89%   |
| G.Skill RAM F4-2400C15-16GFT 16GB DIMM DDR4 2400MT/s   | 1        | 1.89%   |
| G.Skill RAM F3-1600C9-8GXM 8GB DIMM DDR3 1600MT/s      | 1        | 1.89%   |
| G.Skill RAM F3-1600C9-4GRSL 4GB SODIMM DDR3 1600MT/s   | 1        | 1.89%   |
| Crucial RAM CT8G4DFS824A.C8FE 8GB DIMM DDR4 2400MT/s   | 1        | 1.89%   |
| Crucial RAM CT8G4DFS824A.C8FBD1 8GB DIMM DDR4 2400MT/s | 1        | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 23       | 50%     |
| DDR3    | 18       | 39.13%  |
| DDR2    | 2        | 4.35%   |
| Unknown | 2        | 4.35%   |
| SDRAM   | 1        | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 41       | 91.11%  |
| SODIMM | 4        | 8.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 22       | 47.83%  |
| 4096  | 11       | 23.91%  |
| 16384 | 6        | 13.04%  |
| 2048  | 6        | 13.04%  |
| 32768 | 1        | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 15       | 30.61%  |
| 3200  | 9        | 18.37%  |
| 2400  | 7        | 14.29%  |
| 1333  | 5        | 10.2%   |
| 2667  | 3        | 6.12%   |
| 2133  | 2        | 4.08%   |
| 800   | 2        | 4.08%   |
| 3600  | 1        | 2.04%   |
| 3066  | 1        | 2.04%   |
| 2666  | 1        | 2.04%   |
| 1867  | 1        | 2.04%   |
| 1067  | 1        | 2.04%   |
| 667   | 1        | 2.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 1        | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                 | Desktops | Percent |
|-----------------------|----------|---------|
| HP Laser 107a Printer | 1        | 100%    |

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
| Xiongmai            | 1        | 25%     |
| Trust               | 1        | 25%     |
| Logitech            | 1        | 25%     |
| Chicony Electronics | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Xiongmai web camera                   | 1        | 25%     |
| Trust Trust USB Camera                | 1        | 25%     |
| Logitech Webcam C310                  | 1        | 25%     |
| Chicony HP High Definition 1MP Webcam | 1        | 25%     |

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
| 1     | 22       | 48.89%  |
| 0     | 15       | 33.33%  |
| 2     | 7        | 15.56%  |
| 3     | 1        | 2.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 14       | 36.84%  |
| Bluetooth                | 9        | 23.68%  |
| Firewire controller      | 6        | 15.79%  |
| Net/wireless             | 4        | 10.53%  |
| Card reader              | 3        | 7.89%   |
| Sound                    | 1        | 2.63%   |
| Modem                    | 1        | 2.63%   |

