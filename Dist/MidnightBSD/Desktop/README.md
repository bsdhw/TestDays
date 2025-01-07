MidnightBSD - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for MidnightBSD.

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

Total: 55

| Vendor     | Model                       | Probe                                                     | Date         |
|------------|-----------------------------|-----------------------------------------------------------|--------------|
| ASUSTek    | TUF Gaming B560M-PLUS WI... | [e69f71eb23](https://bsd-hardware.info/?probe=e69f71eb23) | Dec 30, 2024 |
| MSI        | B650 GAMING PLUS WIFI       | [434fcb2264](https://bsd-hardware.info/?probe=434fcb2264) | Nov 17, 2024 |
| MSI        | B650 GAMING PLUS WIFI       | [7ae29d1e0f](https://bsd-hardware.info/?probe=7ae29d1e0f) | Nov 17, 2024 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | [8f87e1ac76](https://bsd-hardware.info/?probe=8f87e1ac76) | Nov 11, 2024 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | [07bdbdd1ec](https://bsd-hardware.info/?probe=07bdbdd1ec) | Aug 09, 2024 |
| HPE        | ProLiant MicroServer Gen... | [49344e8a17](https://bsd-hardware.info/?probe=49344e8a17) | Jun 30, 2024 |
| Supermicro | X9SCL/X9SCMA                | [53bdb73b74](https://bsd-hardware.info/?probe=53bdb73b74) | Feb 14, 2024 |
| ASRock     | B550M Steel Legend          | [fa494be63d](https://bsd-hardware.info/?probe=fa494be63d) | Jan 26, 2024 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | [eda92591b5](https://bsd-hardware.info/?probe=eda92591b5) | Jan 07, 2024 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | [12ff062207](https://bsd-hardware.info/?probe=12ff062207) | Jan 07, 2024 |
| ASRock     | B550M Steel Legend          | [d24b57f807](https://bsd-hardware.info/?probe=d24b57f807) | Jan 06, 2024 |
| ASRock     | X570 Steel Legend WiFi a... | [a98f0b3d67](https://bsd-hardware.info/?probe=a98f0b3d67) | Sep 03, 2023 |
| ASRock     | X570 Steel Legend WiFi a... | [d352ea60cf](https://bsd-hardware.info/?probe=d352ea60cf) | Sep 03, 2023 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | [1b53079f34](https://bsd-hardware.info/?probe=1b53079f34) | Aug 19, 2023 |
| ASRock     | B550M Steel Legend          | [ffc50e224c](https://bsd-hardware.info/?probe=ffc50e224c) | Aug 01, 2023 |
| Supermicro | X9SCL/X9SCMA                | [cb87f3725f](https://bsd-hardware.info/?probe=cb87f3725f) | May 14, 2023 |
| ASUSTek    | TUF Gaming B560M-PLUS WI... | [50ff0c14dd](https://bsd-hardware.info/?probe=50ff0c14dd) | Apr 22, 2023 |
| ASUSTek    | A7VI-VM                     | [083714b968](https://bsd-hardware.info/?probe=083714b968) | Apr 07, 2023 |
| Supermicro | X9SCL/X9SCMA                | [31ed779fdc](https://bsd-hardware.info/?probe=31ed779fdc) | Mar 31, 2023 |
| ASRock     | B550M Steel Legend          | [06a2d12cbe](https://bsd-hardware.info/?probe=06a2d12cbe) | Mar 29, 2023 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | [2c6fc04801](https://bsd-hardware.info/?probe=2c6fc04801) | Mar 29, 2023 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | [e4af143188](https://bsd-hardware.info/?probe=e4af143188) | Jan 10, 2023 |
| Supermicro | X9SCL/X9SCMA                | [0b16265d11](https://bsd-hardware.info/?probe=0b16265d11) | Jan 10, 2023 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | [4d9a4bfc40](https://bsd-hardware.info/?probe=4d9a4bfc40) | Dec 30, 2022 |
| ASRock     | B550M Steel Legend          | [48d5feacf2](https://bsd-hardware.info/?probe=48d5feacf2) | Dec 08, 2022 |
| ASRock     | B550M Steel Legend          | [c6824c4f4a](https://bsd-hardware.info/?probe=c6824c4f4a) | Jun 11, 2022 |
| ASUSTek    | PRIME Z590-P                | [3ef083287f](https://bsd-hardware.info/?probe=3ef083287f) | May 28, 2022 |
| ASUSTek    | PRIME Z590-P                | [53cb90d2b7](https://bsd-hardware.info/?probe=53cb90d2b7) | May 28, 2022 |
| HP         | 8767 A                      | [ac8a395a20](https://bsd-hardware.info/?probe=ac8a395a20) | May 20, 2022 |
| ASRock     | B550M Steel Legend          | [50d12f98fc](https://bsd-hardware.info/?probe=50d12f98fc) | Apr 08, 2022 |
| ASRock     | B550M Steel Legend          | [ad0ab01ca8](https://bsd-hardware.info/?probe=ad0ab01ca8) | Apr 08, 2022 |
| ASRock     | B550M Steel Legend          | [a752b8b4d6](https://bsd-hardware.info/?probe=a752b8b4d6) | Mar 22, 2022 |
| ASRock     | B550M Steel Legend          | [ab838523ad](https://bsd-hardware.info/?probe=ab838523ad) | Jan 15, 2022 |
| ASRock     | X570 Steel Legend WiFi a... | [c13b78e6d5](https://bsd-hardware.info/?probe=c13b78e6d5) | Dec 23, 2021 |
| ASRock     | X570 Steel Legend WiFi a... | [7bf6ec598f](https://bsd-hardware.info/?probe=7bf6ec598f) | Dec 18, 2021 |
| HP         | 8767 A                      | [8bbd431806](https://bsd-hardware.info/?probe=8bbd431806) | Oct 14, 2021 |
| HP         | 8767 A                      | [6bc45054bb](https://bsd-hardware.info/?probe=6bc45054bb) | Oct 14, 2021 |
| ASRock     | X570 Steel Legend WiFi a... | [9614fd11d7](https://bsd-hardware.info/?probe=9614fd11d7) | Aug 21, 2021 |
| ASUSTek    | TUF B350M-PLUS GAMING       | [bd63de17b0](https://bsd-hardware.info/?probe=bd63de17b0) | Jun 07, 2021 |
| ASRock     | B550M Steel Legend          | [308573e703](https://bsd-hardware.info/?probe=308573e703) | Jun 02, 2021 |
| ASUSTek    | TUF B350M-PLUS GAMING       | [ba938810b9](https://bsd-hardware.info/?probe=ba938810b9) | May 25, 2021 |
| ASRock     | B550M Steel Legend          | [29a31a7a93](https://bsd-hardware.info/?probe=29a31a7a93) | May 25, 2021 |
| HP         | 1589                        | [f97fc0533b](https://bsd-hardware.info/?probe=f97fc0533b) | Jan 02, 2021 |
| ASUSTek    | TUF B350M-PLUS GAMING       | [778268ad6f](https://bsd-hardware.info/?probe=778268ad6f) | Dec 30, 2020 |
| ASRock     | X570 Steel Legend WiFi a... | [a27f63a72c](https://bsd-hardware.info/?probe=a27f63a72c) | Dec 30, 2020 |
| ASRock     | B550M Steel Legend          | [78b6751c3f](https://bsd-hardware.info/?probe=78b6751c3f) | Dec 24, 2020 |
| ASUSTek    | TUF GAMING B450M-PLUS II    | [99fca48a73](https://bsd-hardware.info/?probe=99fca48a73) | Dec 06, 2020 |
| ASRock     | X570 Steel Legend WiFi a... | [86ba25be24](https://bsd-hardware.info/?probe=86ba25be24) | Nov 16, 2020 |
| ASRock     | B550M Steel Legend          | [50ad3ee5fb](https://bsd-hardware.info/?probe=50ad3ee5fb) | Nov 16, 2020 |
| ASRock     | B550M Steel Legend          | [164670d170](https://bsd-hardware.info/?probe=164670d170) | Oct 29, 2020 |
| ASRock     | B550M Steel Legend          | [b4663b7249](https://bsd-hardware.info/?probe=b4663b7249) | Aug 28, 2020 |
| ASUSTek    | TUF B350M-PLUS GAMING       | [53aa996eaa](https://bsd-hardware.info/?probe=53aa996eaa) | Jul 31, 2020 |
| ASUSTek    | TUF B350M-PLUS GAMING       | [20fac3b208](https://bsd-hardware.info/?probe=20fac3b208) | May 22, 2020 |
| ASRock     | B550M Steel Legend          | [44681211ff](https://bsd-hardware.info/?probe=44681211ff) | May 22, 2020 |
| ASUSTek    | PRIME X370-PRO              | [7c311ee004](https://bsd-hardware.info/?probe=7c311ee004) | May 22, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| MidnightBSD 2.0.2 | 4        | 9.3%    |
| MidnightBSD 3.1.0 | 3        | 6.98%   |
| MidnightBSD 2.0.1 | 3        | 6.98%   |
| MidnightBSD 1.2   | 3        | 6.98%   |
| MidnightBSD 3.2.0 | 2        | 4.65%   |
| MidnightBSD 3.0.1 | 2        | 4.65%   |
| MidnightBSD 3.0.0 | 2        | 4.65%   |
| MidnightBSD 2.2.8 | 2        | 4.65%   |
| MidnightBSD 2.2.6 | 2        | 4.65%   |
| MidnightBSD 2.2.0 | 2        | 4.65%   |
| MidnightBSD 2.1.8 | 2        | 4.65%   |
| MidnightBSD 2.0.7 | 2        | 4.65%   |
| MidnightBSD 3.2.1 | 1        | 2.33%   |
| MidnightBSD 3.1.6 | 1        | 2.33%   |
| MidnightBSD 3.1.4 | 1        | 2.33%   |
| MidnightBSD 3.1.3 | 1        | 2.33%   |
| MidnightBSD 3.1.1 | 1        | 2.33%   |
| MidnightBSD 2.2.5 | 1        | 2.33%   |
| MidnightBSD 2.1.6 | 1        | 2.33%   |
| MidnightBSD 2.1.5 | 1        | 2.33%   |
| MidnightBSD 2.1.3 | 1        | 2.33%   |
| MidnightBSD 2.1.2 | 1        | 2.33%   |
| MidnightBSD 2.1.1 | 1        | 2.33%   |
| MidnightBSD 2.1.0 | 1        | 2.33%   |
| MidnightBSD 1.2.9 | 1        | 2.33%   |
| MidnightBSD 1.2.7 | 1        | 2.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| MidnightBSD | 16       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 15       | 93.75%  |
| i386  | 1        | 6.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 9        | 42.86%  |
| XFCE         | 5        | 23.81%  |
| GNOME        | 5        | 23.81%  |
| Window Maker | 1        | 4.76%   |
| Cinnamon     | 1        | 4.76%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 12       | 60%     |
| X11     | 7        | 35%     |
| Wayland | 1        | 5%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 16       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 15       | 93.75%  |
| fi_FI.ISO8859-15 | 1        | 6.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 13       | 76.47%  |
| BIOS | 4        | 23.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| Zfs  | 12       | 70.59%  |
| Ufs  | 5        | 29.41%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 15       | 93.75%  |
| MBR  | 1        | 6.25%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| ASUSTek Computer | 8        | 50%     |
| ASRock           | 3        | 18.75%  |
| Hewlett-Packard  | 2        | 12.5%   |
| Supermicro       | 1        | 6.25%   |
| MSI              | 1        | 6.25%   |
| HPE              | 1        | 6.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS TUF Gaming B450M-PLUS II          | 3        | 18.75%  |
| ASRock B550M Steel Legend              | 2        | 12.5%   |
| Supermicro X9SCL/X9SCM                 | 1        | 6.25%   |
| MSI MS-7E26                            | 1        | 6.25%   |
| HPE ProLiant MicroServer Gen10 Plus v2 | 1        | 6.25%   |
| HP Z420 Workstation                    | 1        | 6.25%   |
| HP ENVY TE01-1xxx                      | 1        | 6.25%   |
| ASUS TUF Gaming B560M-PLUS WIFI        | 1        | 6.25%   |
| ASUS TUF B350M-PLUS GAMING             | 1        | 6.25%   |
| ASUS PRIME Z590-P                      | 1        | 6.25%   |
| ASUS PRIME X370-PRO                    | 1        | 6.25%   |
| ASUS A7VI-VM                           | 1        | 6.25%   |
| ASRock X570 Steel Legend WiFi ax       | 1        | 6.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| ASUS TUF         | 5        | 31.25%  |
| ASUS PRIME       | 2        | 12.5%   |
| ASRock B550M     | 2        | 12.5%   |
| Supermicro X9SCL | 1        | 6.25%   |
| MSI MS-7E26      | 1        | 6.25%   |
| HPE ProLiant     | 1        | 6.25%   |
| HP Z420          | 1        | 6.25%   |
| HP ENVY          | 1        | 6.25%   |
| ASUS A7VI-VM     | 1        | 6.25%   |
| ASRock X570      | 1        | 6.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 3        | 18.75%  |
| 2018 | 3        | 18.75%  |
| 2023 | 2        | 12.5%   |
| 2020 | 2        | 12.5%   |
| 2024 | 1        | 6.25%   |
| 2021 | 1        | 6.25%   |
| 2017 | 1        | 6.25%   |
| 2013 | 1        | 6.25%   |
| 2011 | 1        | 6.25%   |
| 2001 | 1        | 6.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 16       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 16       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 64.01-256.0 | 9        | 50%     |
| 32.01-64.0  | 5        | 27.78%  |
| 16.01-24.0  | 2        | 11.11%  |
| 24.01-32.0  | 1        | 5.56%   |
| 0.01-0.5    | 1        | 5.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 10       | 37.04%  |
| 32.01-64.0 | 3        | 11.11%  |
| 16.01-24.0 | 3        | 11.11%  |
| 0.51-1.0   | 3        | 11.11%  |
| 24.01-32.0 | 2        | 7.41%   |
| 2.01-3.0   | 2        | 7.41%   |
| Unknown    | 2        | 7.41%   |
| 4.01-8.0   | 1        | 3.7%    |
| 0          | 1        | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 5      | 6        | 25%     |
| 8      | 3        | 12.5%   |
| 3      | 3        | 12.5%   |
| 2      | 3        | 12.5%   |
| 1      | 3        | 12.5%   |
| 7      | 2        | 8.33%   |
| 6      | 2        | 8.33%   |
| 4      | 2        | 8.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 14       | 77.78%  |
| Yes       | 4        | 22.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 16       | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 9        | 56.25%  |
| Yes       | 7        | 43.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10       | 62.5%   |
| Yes       | 6        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| USA     | 15       | 93.75%  |
| Finland | 1        | 6.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| Ypsilanti   | 14       | 87.5%   |
| Tampere     | 1        | 6.25%   |
| Los Angeles | 1        | 6.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 9        | 52     | 20.93%  |
| Samsung Electronics | 9        | 67     | 20.93%  |
| Intel               | 7        | 48     | 16.28%  |
| WDC                 | 5        | 25     | 11.63%  |
| Toshiba             | 3        | 7      | 6.98%   |
| KIOXIA              | 3        | 4      | 6.98%   |
| SK hynix            | 2        | 2      | 4.65%   |
| SanDisk             | 1        | 5      | 2.33%   |
| Maxtor              | 1        | 1      | 2.33%   |
| HGST                | 1        | 2      | 2.33%   |
| Crucial             | 1        | 3      | 2.33%   |
| A-DATA Technology   | 1        | 2      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB                   | 5        | 6.76%   |
| Seagate ST8000VN0022-2EL112 8TB             | 4        | 5.41%   |
| Seagate ST8000VN0002-1Z8112 8TB             | 4        | 5.41%   |
| Samsung SSD 970 PRO 512GB                   | 4        | 5.41%   |
| Intel SSDSC2KG480G8 480GB                   | 4        | 5.41%   |
| Samsung SSD 870 EVO 1TB                     | 3        | 4.05%   |
| KIOXIA KBG40ZNV1T02 1TB                     | 3        | 4.05%   |
| Intel SSDPED1D480GA 480GB                   | 3        | 4.05%   |
| WDC WDS100T3X0C-00SJG0 1TB                  | 2        | 2.7%    |
| WDC WD60EFAX-68SHWN0 6TB                    | 2        | 2.7%    |
| Toshiba THNSNJ128GCSU 128GB                 | 2        | 2.7%    |
| SK hynix SHGP31-1000GM 1TB                  | 2        | 2.7%    |
| Seagate ST16000NM001G-2KK103 16TB           | 2        | 2.7%    |
| Seagate ST10000VN0008-2PJ103 10TB           | 2        | 2.7%    |
| Seagate ST10000NE0008-2PL103 10TB           | 2        | 2.7%    |
| Seagate IronWolf ZA1000NM10002-2ZG102 1TB   | 2        | 2.7%    |
| Seagate FireCuda 120 SSD ZA500GM10001 500GB | 2        | 2.7%    |
| Samsung SSD 860 QVO 2TB                     | 2        | 2.7%    |
| Samsung SSD 860 EVO 1TB                     | 2        | 2.7%    |
| Samsung SSD 750 EVO 250GB                   | 2        | 2.7%    |
| WDC WD30EZRX-00MMMB0 3TB                    | 1        | 1.35%   |
| WDC WD1003FZEX-00K3CA0 1TB                  | 1        | 1.35%   |
| Toshiba TL100 120GB                         | 1        | 1.35%   |
| Seagate ST5000DM000-1FK178 5TB              | 1        | 1.35%   |
| Seagate ST2000DM001-1CH164 2TB              | 1        | 1.35%   |
| SanDisk Ultra 3D NVMe 500GB                 | 1        | 1.35%   |
| Samsung SSD 990 EVO Plus 4TB                | 1        | 1.35%   |
| Samsung SSD 970 EVO Plus 2TB                | 1        | 1.35%   |
| Samsung SSD 870 EVO 500GB                   | 1        | 1.35%   |
| Samsung MZ7LM1T9HCJM-00003 1.9TB            | 1        | 1.35%   |
| Maxtor STM3250310AS 250GB                   | 1        | 1.35%   |
| Intel SSDSC2KW480H6 480GB                   | 1        | 1.35%   |
| Intel SSDSC2KB019T8 1.9TB                   | 1        | 1.35%   |
| Intel SSDSC2BW240H6 240GB                   | 1        | 1.35%   |
| Intel SSDSA2CT040G3 40GB                    | 1        | 1.35%   |
| Intel SSDPED1D280GA 280GB                   | 1        | 1.35%   |
| HGST HUH721212ALE601 12TB                   | 1        | 1.35%   |
| Crucial CT500P2SSD8 500GB                   | 1        | 1.35%   |
| Crucial CT4000P3SSD8 4TB                    | 1        | 1.35%   |
| A-DATA SX6000NP 128GB                       | 1        | 1.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 5        | 44     | 45.45%  |
| WDC     | 4        | 19     | 36.36%  |
| Maxtor  | 1        | 1      | 9.09%   |
| HGST    | 1        | 2      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 8        | 48     | 42.11%  |
| Seagate             | 4        | 8      | 21.05%  |
| Intel               | 4        | 37     | 21.05%  |
| Toshiba             | 3        | 7      | 15.79%  |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| NVMe | 12       | 52     | 40%     |
| SSD  | 11       | 100    | 36.67%  |
| HDD  | 7        | 66     | 23.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 14       | 166    | 53.85%  |
| NVMe | 12       | 52     | 46.15%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 12       | 65     | 40%     |
| 0.51-1.0   | 6        | 22     | 20%     |
| 1.01-2.0   | 4        | 19     | 13.33%  |
| 4.01-10.0  | 4        | 51     | 13.33%  |
| 10.01-20.0 | 3        | 8      | 10%     |
| 2.01-3.0   | 1        | 1      | 3.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 251-500    | 9        | 50%     |
| 501-1000   | 5        | 27.78%  |
| 101-250    | 3        | 16.67%  |
| 21-50      | 1        | 5.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 11       | 47.83%  |
| 21-50   | 5        | 21.74%  |
| 51-100  | 4        | 17.39%  |
| 251-500 | 2        | 8.7%    |
| 101-250 | 1        | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD60EFAX-68SHWN0 6TB        | 1        | 2      | 33.33%  |
| Seagate ST8000VN0022-2EL112 8TB | 1        | 1      | 33.33%  |
| Intel SSDSC2KW480H6 480GB       | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |
| Intel   | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 2      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 3      | 66.67%  |
| SSD  | 1        | 1      | 33.33%  |

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
| Works    | 15       | 213    | 78.95%  |
| Malfunc  | 3        | 4      | 15.79%  |
| Detected | 1        | 1      | 5.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 9        | 24.32%  |
| AMD                       | 9        | 24.32%  |
| Samsung Electronics       | 5        | 13.51%  |
| SanDisk                   | 4        | 10.81%  |
| KIOXIA                    | 3        | 8.11%   |
| SK hynix                  | 2        | 5.41%   |
| Realtek Semiconductor     | 2        | 5.41%   |
| VIA Technologies          | 1        | 2.7%    |
| Silicon Image             | 1        | 2.7%    |
| Micron/Crucial Technology | 1        | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 5        | 10.42%  |
| AMD FCH SATA Controller [AHCI mode]                                           | 5        | 10.42%  |
| Intel Optane SSD 900P Series                                                  | 4        | 8.33%   |
| AMD 400 Series Chipset SATA Controller                                        | 4        | 8.33%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 3        | 6.25%   |
| AMD 500 Series Chipset SATA Controller                                        | 3        | 6.25%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 2        | 4.17%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 2        | 4.17%   |
| Realtek RTS5763DL x2 NVMe SSD Controller                                      | 2        | 4.17%   |
| Intel SATA Controller [RAID mode]                                             | 2        | 4.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2        | 4.17%   |
| AMD 300 Series Chipset SATA Controller                                        | 2        | 4.17%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1        | 2.08%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller              | 1        | 2.08%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD       | 1        | 2.08%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)     | 1        | 2.08%   |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                | 1        | 2.08%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1        | 2.08%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 1        | 2.08%   |
| Intel C600/X79 series chipset IDE-r Controller                                | 1        | 2.08%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 1        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1        | 2.08%   |
| AMD X370 Series Chipset SATA Controller                                       | 1        | 2.08%   |
| AMD 600 Series Chipset SATA Controller                                        | 1        | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| NVMe | 13       | 40.63%  |
| SATA | 13       | 40.63%  |
| RAID | 3        | 9.38%   |
| IDE  | 2        | 6.25%   |
| SAS  | 1        | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 10       | 62.5%   |
| Intel  | 6        | 37.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| AMD Ryzen 7 5800X 8-Core Processor      | 3        | 14.29%  |
| AMD Ryzen 7 2700 Eight-Core Processor   | 3        | 14.29%  |
| Intel 11th Gen Core i9-11900K @ 3.50GHz | 2        | 9.52%   |
| AMD Ryzen 7 5700X 8-Core Processor      | 2        | 9.52%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 2        | 9.52%   |
| Intel Xeon E-2314 CPU @ 2.80GHz         | 1        | 4.76%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz        | 1        | 4.76%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz     | 1        | 4.76%   |
| Intel Core i7-10700 CPU @ 2.90GHz       | 1        | 4.76%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz  | 1        | 4.76%   |
| AMD Ryzen 9 7900 12-Core Processor      | 1        | 4.76%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 1        | 4.76%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 1        | 4.76%   |
| AMD Duron Processor                     | 1        | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model         | Desktops | Percent |
|---------------|----------|---------|
| AMD Ryzen 7   | 8        | 47.06%  |
| Other         | 3        | 17.65%  |
| Intel Xeon    | 3        | 17.65%  |
| AMD Ryzen 9   | 2        | 11.76%  |
| Intel Core i7 | 1        | 5.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 8      | 10       | 52.63%  |
| 16     | 4        | 21.05%  |
| 4      | 2        | 10.53%  |
| 32     | 1        | 5.26%   |
| 24     | 1        | 5.26%   |
| 1      | 1        | 5.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 16       | 94.12%  |
| 2      | 1        | 5.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 11       | 61.11%  |
| 1      | 7        | 38.89%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Zen 3       | 5        | 25%     |
| Zen+        | 4        | 20%     |
| Unknown     | 4        | 20%     |
| Zen         | 2        | 10%     |
| Zen 2       | 1        | 5%      |
| SandyBridge | 1        | 5%      |
| K6          | 1        | 5%      |
| IvyBridge   | 1        | 5%      |
| CometLake   | 1        | 5%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 11       | 52.38%  |
| AMD                        | 5        | 23.81%  |
| Intel                      | 3        | 14.29%  |
| Matrox Electronics Systems | 2        | 9.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Nvidia GK208B [GeForce GT 710]                | 6        | 27.27%  |
| Nvidia GP108 [GeForce GT 1030]                | 3        | 13.64%  |
| Nvidia GP102 [GeForce GTX 1080 Ti]            | 2        | 9.09%   |
| AMD Caicos PRO [Radeon HD 7450]               | 2        | 9.09%   |
| Matrox Electronics Systems MGA G200eW WPCM450 | 1        | 4.55%   |
| Matrox Electronics Systems MGA G200eH3        | 1        | 4.55%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]     | 1        | 4.55%   |
| Intel DG2 [Arc A750]                          | 1        | 4.55%   |
| Intel CometLake-S GT2 [UHD Graphics 630]      | 1        | 4.55%   |
| AMD RV280 [Radeon 9200] (Secondary)           | 1        | 4.55%   |
| AMD RV280 [Radeon 9200]                       | 1        | 4.55%   |
| AMD Raphael                                   | 1        | 4.55%   |
| AMD Navi 21 [Radeon RX 6900 XT]               | 1        | 4.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| 1 x Nvidia  | 11       | 55%     |
| 1 x AMD     | 3        | 15%     |
| 1 x Matrox  | 2        | 10%     |
| 1 x Intel   | 2        | 10%     |
| 2 x AMD     | 1        | 5%      |
| Intel + AMD | 1        | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 12       | 63.16%  |
| Proprietary | 7        | 36.84%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 13       | 72.22%  |
| 1.01-2.0   | 2        | 11.11%  |
| 8.01-16.0  | 2        | 11.11%  |
| 0.01-0.5   | 1        | 5.56%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| LG Electronics | 2        | 40%     |
| Goldstar       | 2        | 40%     |
| Acer           | 1        | 20%     |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440           | 1        | 16.67%  |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160            | 1        | 16.67%  |
| Goldstar LG ULTRAGEAR GSM7765 2560x1440 700x390mm 31.5-inch | 1        | 16.67%  |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch  | 1        | 16.67%  |
| Acer LCD Monitor EI342CKR 3440x1440                         | 1        | 16.67%  |
| Acer EI342CKR ACR0763 3440x1440 800x330mm 34.1-inch         | 1        | 16.67%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Desktops | Percent |
|-----------------|----------|---------|
| 3840x2160 (4K)  | 2        | 40%     |
| 2560x1440 (QHD) | 2        | 40%     |
| 3440x1440       | 1        | 20%     |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2        | 40%     |
| 34      | 1        | 20%     |
| 31      | 1        | 20%     |
| 27      | 1        | 20%     |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 2        | 40%     |
| 701-800     | 1        | 20%     |
| 601-700     | 1        | 20%     |
| 501-600     | 1        | 20%     |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2        | 40%     |
| Unknown | 2        | 40%     |
| 21/9    | 1        | 20%     |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 351-500        | 2        | 40%     |
| Unknown        | 2        | 40%     |
| 301-350        | 1        | 20%     |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| Unknown | 2        | 40%     |
| 161-240 | 1        | 20%     |
| 101-120 | 1        | 20%     |
| 51-100  | 1        | 20%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 13       | 72.22%  |
| 1     | 5        | 27.78%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 50%     |
| Realtek Semiconductor | 7        | 31.82%  |
| U-Blox                | 1        | 4.55%   |
| MediaTek              | 1        | 4.55%   |
| D-Link System         | 1        | 4.55%   |
| Broadcom              | 1        | 4.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 14.29%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2        | 7.14%   |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2        | 7.14%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 7.14%   |
| Intel I211 Gigabit Network Connection                                  | 2        | 7.14%   |
| Intel Ethernet Controller X550                                         | 2        | 7.14%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2        | 7.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 7.14%   |
| U-Blox [u-blox 7]                                                      | 1        | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 3.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1        | 3.57%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1        | 3.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1        | 3.57%   |
| Intel I350 Gigabit Network Connection                                  | 1        | 3.57%   |
| Intel Ethernet Controller 10G X550T                                    | 1        | 3.57%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 3.57%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 1        | 3.57%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1        | 3.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 50%     |
| Realtek Semiconductor | 3        | 37.5%   |
| MediaTek              | 1        | 12.5%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2        | 25%     |
| Intel Wi-Fi 6 AX200                                           | 2        | 25%     |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1        | 12.5%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 1        | 12.5%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 1        | 12.5%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1        | 12.5%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 10       | 55.56%  |
| Realtek Semiconductor | 6        | 33.33%  |
| D-Link System         | 1        | 5.56%   |
| Broadcom              | 1        | 5.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8125 2.5GbE Controller                                      | 4        | 21.05%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2        | 10.53%  |
| Intel I211 Gigabit Network Connection                                  | 2        | 10.53%  |
| Intel Ethernet Controller X550                                         | 2        | 10.53%  |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2        | 10.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2        | 10.53%  |
| Intel I350 Gigabit Network Connection                                  | 1        | 5.26%   |
| Intel Ethernet Controller 10G X550T                                    | 1        | 5.26%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 5.26%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 1        | 5.26%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1        | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 66.67%  |
| WiFi     | 7        | 29.17%  |
| Modem    | 1        | 4.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 16       | 94.12%  |
| WiFi     | 1        | 5.88%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 2     | 9        | 56.25%  |
| 1     | 5        | 31.25%  |
| 4     | 1        | 6.25%   |
| 3     | 1        | 6.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 15       | 83.33%  |
| Yes  | 3        | 16.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 57.14%  |
| Realtek Semiconductor | 2        | 28.57%  |
| MediaTek              | 1        | 14.29%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Bluetooth 4.2 Adapter    | 2        | 28.57%  |
| Intel AX200 Bluetooth            | 2        | 28.57%  |
| MediaTek RZ616 Bluetooth Adapter | 1        | 14.29%  |
| Intel AX210 Bluetooth            | 1        | 14.29%  |
| Intel AX201 Bluetooth            | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Nvidia                | 11       | 40.74%  |
| Intel                 | 5        | 18.52%  |
| AMD                   | 5        | 18.52%  |
| VIA Technologies      | 1        | 3.7%    |
| Texas Instruments     | 1        | 3.7%    |
| SteelSeries ApS       | 1        | 3.7%    |
| Realtek Semiconductor | 1        | 3.7%    |
| Logitech              | 1        | 3.7%    |
| Creative Labs         | 1        | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                                                                                                                      | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|---------|
| Nvidia GK208 HDMI/DP Audio Controller                                                                                                                                                      | 6        | 20%     |
| Nvidia GP108 High Definition Audio Controller                                                                                                                                              | 3        | 10%     |
| Nvidia GP102 HDMI Audio Controller                                                                                                                                                         | 2        | 6.67%   |
| Intel Tiger Lake-H HD Audio Controller                                                                                                                                                     | 2        | 6.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                                                                                                                        | 2        | 6.67%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                                                                                                          | 2        | 6.67%   |
| VIA Technologies VT82C686 AC97 Audio Controller                                                                                                                                            | 1        | 3.33%   |
| Texas Instruments PCM2902 Audio Codec                                                                                                                                                      | 1        | 3.33%   |
| SteelSeries ApS SteelSeries GameDAC GameDAC Hi-Res                                                                                                                                         | 1        | 3.33%   |
| Realtek Semiconductor USB Audio                                                                                                                                                            | 1        | 3.33%   |
| Logitech Blue Microphones Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone | 1        | 3.33%   |
| Intel DG2 Audio Controller                                                                                                                                                                 | 1        | 3.33%   |
| Intel Comet Lake PCH cAVS                                                                                                                                                                  | 1        | 3.33%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                                                                                                             | 1        | 3.33%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                                                                                                         | 1        | 3.33%   |
| AMD Starship/Matisse HD Audio Controller                                                                                                                                                   | 1        | 3.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                                                                                                                      | 1        | 3.33%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                                                                                                                    | 1        | 3.33%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                                                                                                                 | 1        | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 6        | 24%     |
| G.Skill                      | 5        | 20%     |
| Samsung Electronics          | 3        | 12%     |
| Unknown                      | 2        | 8%      |
| Kingston                     | 2        | 8%      |
| Unknown                      | 2        | 8%      |
| Patriot Memory (PDP Systems) | 1        | 4%      |
| Mushkin                      | 1        | 4%      |
| Micron Technology            | 1        | 4%      |
| Elpida                       | 1        | 4%      |
| Crucial                      | 1        | 4%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3600C18-32GTZN 32GB DIMM DDR4 3600MT/s                    | 4        | 15.38%  |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3200MT/s                   | 3        | 11.54%  |
| Unknown                                                                  | 2        | 7.69%   |
| Unknown RAM Module 64MB DIMM DRAM                                        | 1        | 3.85%   |
| Unknown RAM CL18-22-22 D4-3600 16384MB DIMM 2667MT/s                     | 1        | 3.85%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                               | 1        | 3.85%   |
| Samsung RAM M391B5273DH0-CK0 4GB DIMM DDR3 1600MT/s                      | 1        | 3.85%   |
| Samsung RAM M391A2G43BB2-CWE 16GB DIMM DDR4 3200MT/s                     | 1        | 3.85%   |
| Patriot Memory (PDP Systems) RAM 3200 C16 Series 32GB DIMM DDR4 2667MT/s | 1        | 3.85%   |
| Mushkin RAM MRX4U320GJJM32G 32GB DIMM DDR4 2400MT/s                      | 1        | 3.85%   |
| Micron RAM Module 8GB DIMM DDR3 1600MT/s                                 | 1        | 3.85%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s                    | 1        | 3.85%   |
| Kingston RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s                    | 1        | 3.85%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s                    | 1        | 3.85%   |
| G.Skill RAM F4-4400C19-16GTZR 16GB DIMM DDR4 2667MT/s                    | 1        | 3.85%   |
| Elpida RAM Module 8GB DIMM DDR3 1600MT/s                                 | 1        | 3.85%   |
| Crucial RAM CT16G4DFRA32A.M16FR 16GB DIMM DDR4 3200MT/s                  | 1        | 3.85%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s                   | 1        | 3.85%   |
| Corsair RAM CMK16GX4M2Z2666C16 8GB DIMM DDR4 2666MT/s                    | 1        | 3.85%   |
| Corsair RAM CMH64GX5M2B6000C40 32GB DIMM DDR5 4800MT/s                   | 1        | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| DDR4 | 12       | 75%     |
| DDR3 | 2        | 12.5%   |
| DRAM | 1        | 6.25%   |
| DDR5 | 1        | 6.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 16       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 16384 | 8        | 40%     |
| 32768 | 7        | 35%     |
| 8192  | 3        | 15%     |
| 256   | 1        | 5%      |
| 64    | 1        | 5%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 6        | 31.58%  |
| 3600    | 4        | 21.05%  |
| 2667    | 2        | 10.53%  |
| 1600    | 2        | 10.53%  |
| 4800    | 1        | 5.26%   |
| 3000    | 1        | 5.26%   |
| 2666    | 1        | 5.26%   |
| 2400    | 1        | 5.26%   |
| Unknown | 1        | 5.26%   |

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


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Logitech | 5        | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech C922 Pro Stream Webcam | 3        | 60%     |
| Logitech HD Pro Webcam C920     | 2        | 40%     |

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
| 0     | 7        | 41.18%  |
| 1     | 4        | 23.53%  |
| 2     | 3        | 17.65%  |
| 3     | 2        | 11.76%  |
| 4     | 1        | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 6        | 40%     |
| Communication controller | 5        | 33.33%  |
| Sound                    | 1        | 6.67%   |
| Net/ethernet             | 1        | 6.67%   |
| Firewire controller      | 1        | 6.67%   |
| Bluetooth                | 1        | 6.67%   |

