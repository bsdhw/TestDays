MidnightBSD - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for MidnightBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MidnightBSD/Desktop/README.md) and [notebooks](/Dist/MidnightBSD/Notebook/README.md).

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

Total: 58

| Vendor     | Model                       | Form-Factor | Probe                                                     | Date         |
|------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASRock     | B550M Steel Legend          | Desktop     | [ffc50e224c](https://bsd-hardware.info/?probe=ffc50e224c) | Aug 01, 2023 |
| Supermicro | X9SCL/X9SCMA                | Desktop     | [cb87f3725f](https://bsd-hardware.info/?probe=cb87f3725f) | May 14, 2023 |
| ASUSTek    | TUF Gaming B560M-PLUS WI... | Desktop     | [50ff0c14dd](https://bsd-hardware.info/?probe=50ff0c14dd) | Apr 22, 2023 |
| ASUSTek    | A7VI-VM                     | Desktop     | [083714b968](https://bsd-hardware.info/?probe=083714b968) | Apr 07, 2023 |
| Supermicro | X9SCL/X9SCMA                | Desktop     | [31ed779fdc](https://bsd-hardware.info/?probe=31ed779fdc) | Mar 31, 2023 |
| ASRock     | B550M Steel Legend          | Desktop     | [06a2d12cbe](https://bsd-hardware.info/?probe=06a2d12cbe) | Mar 29, 2023 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | Desktop     | [2c6fc04801](https://bsd-hardware.info/?probe=2c6fc04801) | Mar 29, 2023 |
| HP         | Victus by Gaming Laptop ... | Notebook    | [b97af82e5c](https://bsd-hardware.info/?probe=b97af82e5c) | Feb 05, 2023 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | Desktop     | [e4af143188](https://bsd-hardware.info/?probe=e4af143188) | Jan 10, 2023 |
| Supermicro | X9SCL/X9SCMA                | Desktop     | [0b16265d11](https://bsd-hardware.info/?probe=0b16265d11) | Jan 10, 2023 |
| Lenovo     | B50-80 80EW                 | Notebook    | [b8f49b8d19](https://bsd-hardware.info/?probe=b8f49b8d19) | Jan 07, 2023 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | Desktop     | [4d9a4bfc40](https://bsd-hardware.info/?probe=4d9a4bfc40) | Dec 30, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [48d5feacf2](https://bsd-hardware.info/?probe=48d5feacf2) | Dec 08, 2022 |
| Dell       | Latitude D610               | Notebook    | [6ef8d8137b](https://bsd-hardware.info/?probe=6ef8d8137b) | Nov 24, 2022 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [b816902c0b](https://bsd-hardware.info/?probe=b816902c0b) | Oct 31, 2022 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [296e81dd9d](https://bsd-hardware.info/?probe=296e81dd9d) | Aug 21, 2022 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [b79fa4531e](https://bsd-hardware.info/?probe=b79fa4531e) | Aug 20, 2022 |
| HP         | Victus by Gaming Laptop ... | Notebook    | [e09aa880f9](https://bsd-hardware.info/?probe=e09aa880f9) | Aug 16, 2022 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [43d7380492](https://bsd-hardware.info/?probe=43d7380492) | Jun 15, 2022 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [a3e3500ca5](https://bsd-hardware.info/?probe=a3e3500ca5) | Jun 15, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [c6824c4f4a](https://bsd-hardware.info/?probe=c6824c4f4a) | Jun 11, 2022 |
| ASUSTek    | PRIME Z590-P                | Desktop     | [3ef083287f](https://bsd-hardware.info/?probe=3ef083287f) | May 28, 2022 |
| ASUSTek    | PRIME Z590-P                | Desktop     | [53cb90d2b7](https://bsd-hardware.info/?probe=53cb90d2b7) | May 28, 2022 |
| HP         | 8767 A                      | Desktop     | [ac8a395a20](https://bsd-hardware.info/?probe=ac8a395a20) | May 20, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [50d12f98fc](https://bsd-hardware.info/?probe=50d12f98fc) | Apr 08, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [ad0ab01ca8](https://bsd-hardware.info/?probe=ad0ab01ca8) | Apr 08, 2022 |
| Lenovo     | ThinkPad X1 Extreme 20MF... | Notebook    | [1af600b3ae](https://bsd-hardware.info/?probe=1af600b3ae) | Mar 24, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [a752b8b4d6](https://bsd-hardware.info/?probe=a752b8b4d6) | Mar 22, 2022 |
| ASRock     | B550M Steel Legend          | Desktop     | [ab838523ad](https://bsd-hardware.info/?probe=ab838523ad) | Jan 15, 2022 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [c13b78e6d5](https://bsd-hardware.info/?probe=c13b78e6d5) | Dec 23, 2021 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [7bf6ec598f](https://bsd-hardware.info/?probe=7bf6ec598f) | Dec 18, 2021 |
| HP         | 8767 A                      | Desktop     | [8bbd431806](https://bsd-hardware.info/?probe=8bbd431806) | Oct 14, 2021 |
| HP         | 8767 A                      | Desktop     | [6bc45054bb](https://bsd-hardware.info/?probe=6bc45054bb) | Oct 14, 2021 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [4b03ca3191](https://bsd-hardware.info/?probe=4b03ca3191) | Oct 03, 2021 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [9614fd11d7](https://bsd-hardware.info/?probe=9614fd11d7) | Aug 21, 2021 |
| ASUSTek    | TUF B350M-PLUS GAMING       | Desktop     | [bd63de17b0](https://bsd-hardware.info/?probe=bd63de17b0) | Jun 07, 2021 |
| ASRock     | B550M Steel Legend          | Desktop     | [308573e703](https://bsd-hardware.info/?probe=308573e703) | Jun 02, 2021 |
| ASUSTek    | TUF B350M-PLUS GAMING       | Desktop     | [ba938810b9](https://bsd-hardware.info/?probe=ba938810b9) | May 25, 2021 |
| ASRock     | B550M Steel Legend          | Desktop     | [29a31a7a93](https://bsd-hardware.info/?probe=29a31a7a93) | May 25, 2021 |
| HP         | 1589                        | Desktop     | [f97fc0533b](https://bsd-hardware.info/?probe=f97fc0533b) | Jan 02, 2021 |
| ASUSTek    | TUF B350M-PLUS GAMING       | Desktop     | [778268ad6f](https://bsd-hardware.info/?probe=778268ad6f) | Dec 30, 2020 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [a27f63a72c](https://bsd-hardware.info/?probe=a27f63a72c) | Dec 30, 2020 |
| ASRock     | B550M Steel Legend          | Desktop     | [78b6751c3f](https://bsd-hardware.info/?probe=78b6751c3f) | Dec 24, 2020 |
| ASUSTek    | TUF GAMING B450M-PLUS II    | Desktop     | [99fca48a73](https://bsd-hardware.info/?probe=99fca48a73) | Dec 06, 2020 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [86ba25be24](https://bsd-hardware.info/?probe=86ba25be24) | Nov 16, 2020 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [624be8f7d6](https://bsd-hardware.info/?probe=624be8f7d6) | Nov 16, 2020 |
| ASRock     | B550M Steel Legend          | Desktop     | [50ad3ee5fb](https://bsd-hardware.info/?probe=50ad3ee5fb) | Nov 16, 2020 |
| ASRock     | B550M Steel Legend          | Desktop     | [164670d170](https://bsd-hardware.info/?probe=164670d170) | Oct 29, 2020 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [4d2c24a0e3](https://bsd-hardware.info/?probe=4d2c24a0e3) | Sep 15, 2020 |
| ASRock     | B550M Steel Legend          | Desktop     | [b4663b7249](https://bsd-hardware.info/?probe=b4663b7249) | Aug 28, 2020 |
| ASUSTek    | TUF B350M-PLUS GAMING       | Desktop     | [53aa996eaa](https://bsd-hardware.info/?probe=53aa996eaa) | Jul 31, 2020 |
| Lenovo     | G570 20079                  | Notebook    | [7042848932](https://bsd-hardware.info/?probe=7042848932) | Jun 03, 2020 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [010db0aed4](https://bsd-hardware.info/?probe=010db0aed4) | May 22, 2020 |
| ASUSTek    | TUF B350M-PLUS GAMING       | Desktop     | [20fac3b208](https://bsd-hardware.info/?probe=20fac3b208) | May 22, 2020 |
| ASRock     | B550M Steel Legend          | Desktop     | [44681211ff](https://bsd-hardware.info/?probe=44681211ff) | May 22, 2020 |
| ASUSTek    | PRIME X370-PRO              | Desktop     | [7c311ee004](https://bsd-hardware.info/?probe=7c311ee004) | May 22, 2020 |
| Lenovo     | G570 20079                  | Notebook    | [112b83a485](https://bsd-hardware.info/?probe=112b83a485) | May 16, 2020 |
| Lenovo     | G570 20079                  | Notebook    | [eff0d8a3db](https://bsd-hardware.info/?probe=eff0d8a3db) | May 06, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| MidnightBSD 2.0.2 | 4         | 9.52%   |
| MidnightBSD 1.2   | 4         | 9.52%   |
| MidnightBSD 3.0.0 | 3         | 7.14%   |
| MidnightBSD 2.2.6 | 3         | 7.14%   |
| MidnightBSD 2.2.0 | 3         | 7.14%   |
| MidnightBSD 2.0.1 | 3         | 7.14%   |
| MidnightBSD 3.1.0 | 2         | 4.76%   |
| MidnightBSD 3.0.1 | 2         | 4.76%   |
| MidnightBSD 2.1.8 | 2         | 4.76%   |
| MidnightBSD 2.1.5 | 2         | 4.76%   |
| MidnightBSD 2.1.1 | 2         | 4.76%   |
| MidnightBSD 2.0.7 | 2         | 4.76%   |
| MidnightBSD 2.2.8 | 1         | 2.38%   |
| MidnightBSD 2.2.5 | 1         | 2.38%   |
| MidnightBSD 2.2.2 | 1         | 2.38%   |
| MidnightBSD 2.1.6 | 1         | 2.38%   |
| MidnightBSD 2.1.3 | 1         | 2.38%   |
| MidnightBSD 2.1.2 | 1         | 2.38%   |
| MidnightBSD 2.1.0 | 1         | 2.38%   |
| MidnightBSD 2.0   | 1         | 2.38%   |
| MidnightBSD 1.2.9 | 1         | 2.38%   |
| MidnightBSD 1.2.7 | 1         | 2.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| MidnightBSD | 17        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 15        | 88.24%  |
| i386  | 2         | 11.76%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| XFCE         | 9         | 45%     |
| Console      | 6         | 30%     |
| GNOME        | 4         | 20%     |
| Window Maker | 1         | 5%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 10        | 50%     |
| Console | 10        | 50%     |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 17        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 16        | 94.12%  |
| fi_FI.ISO8859-15 | 1         | 5.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 13        | 76.47%  |
| BIOS | 4         | 23.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 12        | 70.59%  |
| Ufs  | 5         | 29.41%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 16        | 94.12%  |
| MBR  | 1         | 5.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 7         | 41.18%  |
| Hewlett-Packard  | 3         | 17.65%  |
| ASRock           | 3         | 17.65%  |
| Lenovo           | 2         | 11.76%  |
| Supermicro       | 1         | 5.88%   |
| Dell             | 1         | 5.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS TUF GAMING B450M-PLUS II         | 2         | 11.76%  |
| ASRock B550M Steel Legend             | 2         | 11.76%  |
| Supermicro X9SCL/X9SCM                | 1         | 5.88%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS | 1         | 5.88%   |
| Lenovo ThinkPad A485 20MU000VUS       | 1         | 5.88%   |
| HP Z420 Workstation                   | 1         | 5.88%   |
| HP Victus by Gaming Laptop 15-fa0xxx  | 1         | 5.88%   |
| HP ENVY TE01-1xxx                     | 1         | 5.88%   |
| Dell Latitude D610                    | 1         | 5.88%   |
| ASUS TUF Gaming B560M-PLUS WIFI       | 1         | 5.88%   |
| ASUS TUF B350M-PLUS GAMING            | 1         | 5.88%   |
| ASUS PRIME Z590-P                     | 1         | 5.88%   |
| ASUS PRIME X370-PRO                   | 1         | 5.88%   |
| ASUS A7VI-VM                          | 1         | 5.88%   |
| ASRock X570 Steel Legend WiFi ax      | 1         | 5.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| ASUS TUF         | 4         | 23.53%  |
| Lenovo ThinkPad  | 2         | 11.76%  |
| ASUS PRIME       | 2         | 11.76%  |
| ASRock B550M     | 2         | 11.76%  |
| Supermicro X9SCL | 1         | 5.88%   |
| HP Z420          | 1         | 5.88%   |
| HP Victus        | 1         | 5.88%   |
| HP ENVY          | 1         | 5.88%   |
| Dell Latitude    | 1         | 5.88%   |
| ASUS A7VI-VM     | 1         | 5.88%   |
| ASRock X570      | 1         | 5.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 4         | 23.53%  |
| 2018 | 3         | 17.65%  |
| 2021 | 2         | 11.76%  |
| 2023 | 1         | 5.88%   |
| 2022 | 1         | 5.88%   |
| 2020 | 1         | 5.88%   |
| 2017 | 1         | 5.88%   |
| 2013 | 1         | 5.88%   |
| 2011 | 1         | 5.88%   |
| 2005 | 1         | 5.88%   |
| 2001 | 1         | 5.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 13        | 76.47%  |
| Notebook | 4         | 23.53%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 17        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 7         | 33.33%  |
| 64.01-256.0 | 7         | 33.33%  |
| 16.01-24.0  | 2         | 9.52%   |
| 8.01-16.0   | 2         | 9.52%   |
| 24.01-32.0  | 1         | 4.76%   |
| 2.01-3.0    | 1         | 4.76%   |
| 0.01-0.5    | 1         | 4.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 11        | 37.93%  |
| 32.01-64.0 | 3         | 10.34%  |
| 16.01-24.0 | 3         | 10.34%  |
| 0.51-1.0   | 3         | 10.34%  |
| 24.01-32.0 | 2         | 6.9%    |
| 2.01-3.0   | 2         | 6.9%    |
| Unknown    | 2         | 6.9%    |
| 4.01-8.0   | 1         | 3.45%   |
| 0.01-0.5   | 1         | 3.45%   |
| 0          | 1         | 3.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 7         | 29.17%  |
| 5      | 4         | 16.67%  |
| 3      | 3         | 12.5%   |
| 8      | 2         | 8.33%   |
| 7      | 2         | 8.33%   |
| 6      | 2         | 8.33%   |
| 2      | 2         | 8.33%   |
| 4      | 1         | 4.17%   |
| 0      | 1         | 4.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 15        | 78.95%  |
| Yes       | 4         | 21.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 58.82%  |
| No        | 7         | 41.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9         | 52.94%  |
| No        | 8         | 47.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| USA     | 15        | 88.24%  |
| Germany | 1         | 5.88%   |
| Finland | 1         | 5.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City        | Computers | Percent |
|-------------|-----------|---------|
| Ypsilanti   | 13        | 76.47%  |
| Wuppertal   | 1         | 5.88%   |
| Tampere     | 1         | 5.88%   |
| Los Angeles | 1         | 5.88%   |
| Fresno      | 1         | 5.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 44     | 20%     |
| Samsung Electronics | 7         | 48     | 17.5%   |
| WDC                 | 6         | 24     | 15%     |
| Intel               | 5         | 38     | 12.5%   |
| Toshiba             | 3         | 6      | 7.5%    |
| SanDisk             | 2         | 8      | 5%      |
| KIOXIA              | 2         | 3      | 5%      |
| SK hynix            | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 2      | 2.5%    |
| Maxtor              | 1         | 1      | 2.5%    |
| Lenovo              | 1         | 1      | 2.5%    |
| Hewlett-Packard     | 1         | 1      | 2.5%    |
| Crucial             | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 2      | 2.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                   | 5         | 7.81%   |
| Seagate ST8000VN0022-2EL112 8TB             | 3         | 4.69%   |
| Seagate ST8000VN0002-1Z8112 8TB             | 3         | 4.69%   |
| Samsung SSD 970 PRO 512GB                   | 3         | 4.69%   |
| Intel SSDSC2KG480G8 480GB                   | 3         | 4.69%   |
| Intel SSDPED1D480GA 480GB                   | 3         | 4.69%   |
| WDC WDS100T3X0C-00SJG0 1TB                  | 2         | 3.13%   |
| WDC WD60EFAX-68SHWN0 6TB                    | 2         | 3.13%   |
| Toshiba THNSNJ128GCSU 128GB                 | 2         | 3.13%   |
| Seagate ST16000NM001G-2KK103 16TB           | 2         | 3.13%   |
| Seagate ST10000VN0008-2PJ103 10TB           | 2         | 3.13%   |
| Seagate ST10000NE0008-2PL103 10TB           | 2         | 3.13%   |
| Seagate FireCuda 120 SSD ZA500GM10001 500GB | 2         | 3.13%   |
| Samsung SSD 870 EVO 1TB                     | 2         | 3.13%   |
| Samsung SSD 860 QVO 2TB                     | 2         | 3.13%   |
| Samsung SSD 860 EVO 1TB                     | 2         | 3.13%   |
| Samsung SSD 750 EVO 250GB                   | 2         | 3.13%   |
| KIOXIA KBG40ZNV1T02 1TB                     | 2         | 3.13%   |
| WDC WD5000LPLX-08ZNTT0 500GB                | 1         | 1.56%   |
| WDC WD30EZRX-00MMMB0 3TB                    | 1         | 1.56%   |
| WDC WD1003FZEX-00K3CA0 1TB                  | 1         | 1.56%   |
| Toshiba TL100 120GB                         | 1         | 1.56%   |
| SK hynix SHGP31-1000GM 1TB                  | 1         | 1.56%   |
| Seagate ST980210A 80GB                      | 1         | 1.56%   |
| Seagate ST5000DM000-1FK178 5TB              | 1         | 1.56%   |
| Seagate ST2000DM001-1CH164 2TB              | 1         | 1.56%   |
| Seagate IronWolf ZA1000NM10002-2ZG102 1TB   | 1         | 1.56%   |
| SanDisk Ultra 3D NVMe 1TB                   | 1         | 1.56%   |
| SanDisk SSD PLUS 240GB                      | 1         | 1.56%   |
| Micron MTFDKBA512TFH-1BC1AABHA 512GB        | 1         | 1.56%   |
| Maxtor STM3250310AS 250GB                   | 1         | 1.56%   |
| Lenovo LENSE30512GMSP34MEAT3TA 512GB        | 1         | 1.56%   |
| Intel SSDSC2KW480H6 480GB                   | 1         | 1.56%   |
| Intel SSDSC2BW240H6 240GB                   | 1         | 1.56%   |
| Intel SSDSA2CT040G3 40GB                    | 1         | 1.56%   |
| HP SSD S700 120GB                           | 1         | 1.56%   |
| Crucial CT500P2SSD8 500GB                   | 1         | 1.56%   |
| A-DATA SX6000NP 128GB                       | 1         | 1.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 19     | 45.45%  |
| Seagate | 5         | 38     | 45.45%  |
| Maxtor  | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 35     | 35.29%  |
| Toshiba             | 3         | 6      | 17.65%  |
| Seagate             | 3         | 6      | 17.65%  |
| Intel               | 3         | 29     | 17.65%  |
| SanDisk             | 1         | 4      | 5.88%   |
| Hewlett-Packard     | 1         | 1      | 5.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 12        | 81     | 40%     |
| NVMe | 10        | 41     | 33.33%  |
| HDD  | 8         | 58     | 26.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 15        | 139    | 60%     |
| NVMe | 10        | 41     | 40%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 14        | 64     | 50%     |
| 0.51-1.0   | 5         | 18     | 17.86%  |
| 1.01-2.0   | 3         | 6      | 10.71%  |
| 4.01-10.0  | 3         | 45     | 10.71%  |
| 10.01-20.0 | 2         | 5      | 7.14%   |
| 2.01-3.0   | 1         | 1      | 3.57%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 11        | 55%     |
| 501-1000   | 4         | 20%     |
| 101-250    | 3         | 15%     |
| 21-50      | 1         | 5%      |
| 51-100     | 1         | 5%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 12        | 52.17%  |
| 21-50   | 5         | 21.74%  |
| 51-100  | 3         | 13.04%  |
| 251-500 | 2         | 8.7%    |
| 101-250 | 1         | 4.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC WD60EFAX-68SHWN0 6TB  | 1         | 2      | 50%     |
| Intel SSDSC2KW480H6 480GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 2      | 50%     |
| Intel  | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 2      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 2      | 50%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 17        | 176    | 85%     |
| Malfunc  | 2         | 3      | 10%     |
| Detected | 1         | 1      | 5%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 9         | 26.47%  |
| AMD                       | 8         | 23.53%  |
| SanDisk                   | 4         | 11.76%  |
| Samsung Electronics       | 3         | 8.82%   |
| Realtek Semiconductor     | 2         | 5.88%   |
| KIOXIA                    | 2         | 5.88%   |
| VIA Technologies          | 1         | 2.94%   |
| SK hynix                  | 1         | 2.94%   |
| Silicon Image             | 1         | 2.94%   |
| Micron/Crucial Technology | 1         | 2.94%   |
| Micron Technology         | 1         | 2.94%   |
| Lenovo                    | 1         | 2.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 6         | 13.95%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 3         | 6.98%   |
| Intel Optane SSD 900P Series                                                  | 3         | 6.98%   |
| AMD 500 Series Chipset SATA Controller                                        | 3         | 6.98%   |
| AMD 400 Series Chipset SATA Controller                                        | 3         | 6.98%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 2         | 4.65%   |
| Realtek RTS5763DL x2 NVMe SSD Controller                                      | 2         | 4.65%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 2         | 4.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 4.65%   |
| AMD 300 Series Chipset SATA Controller                                        | 2         | 4.65%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1         | 2.33%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 1         | 2.33%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller              | 1         | 2.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 2.33%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD       | 1         | 2.33%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1         | 2.33%   |
| Micron 3400 NVMe SSD [Hendrix]                                                | 1         | 2.33%   |
| Lenovo LENSE30512GMSP34MEAT3TA                                                | 1         | 2.33%   |
| Intel SATA Controller [RAID mode]                                             | 1         | 2.33%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 1         | 2.33%   |
| Intel C600/X79 series chipset IDE-r Controller                                | 1         | 2.33%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 1         | 2.33%   |
| Intel 82801FBM (ICH6M) SATA Controller                                        | 1         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1         | 2.33%   |
| AMD X370 Series Chipset SATA Controller                                       | 1         | 2.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 12        | 40%     |
| SATA | 12        | 40%     |
| IDE  | 3         | 10%     |
| RAID | 2         | 6.67%   |
| SAS  | 1         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 9         | 52.94%  |
| Intel  | 8         | 47.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800X 8-Core Processor              | 3         | 14.29%  |
| AMD Ryzen 7 2700 Eight-Core Processor           | 3         | 14.29%  |
| AMD Ryzen 7 1700 Eight-Core Processor           | 2         | 9.52%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz                | 1         | 4.76%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz             | 1         | 4.76%   |
| Intel Pentium M                                 | 1         | 4.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 4.76%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1         | 4.76%   |
| Intel 12th Gen Core i5-12450H                   | 1         | 4.76%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz         | 1         | 4.76%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 1         | 4.76%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1         | 4.76%   |
| AMD Ryzen 7 5700X 8-Core Processor              | 1         | 4.76%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 4.76%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1         | 4.76%   |
| AMD Duron Processor                             | 1         | 4.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Computers | Percent |
|-----------------|-----------|---------|
| AMD Ryzen 7     | 7         | 38.89%  |
| Other           | 4         | 22.22%  |
| Intel Xeon      | 2         | 11.11%  |
| Intel Core i7   | 2         | 11.11%  |
| Intel Pentium M | 1         | 5.56%   |
| AMD Ryzen 9     | 1         | 5.56%   |
| AMD Ryzen 5 PRO | 1         | 5.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 8      | 11        | 50%     |
| 16     | 3         | 13.64%  |
| 6      | 2         | 9.09%   |
| 4      | 2         | 9.09%   |
| 1      | 2         | 9.09%   |
| 32     | 1         | 4.55%   |
| 12     | 1         | 4.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 17        | 94.44%  |
| 2      | 1         | 5.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 14        | 66.67%  |
| 1       | 6         | 28.57%  |
| Unknown | 1         | 4.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Zen+        | 4         | 19.05%  |
| Zen 3       | 4         | 19.05%  |
| Zen         | 3         | 14.29%  |
| Unknown     | 3         | 14.29%  |
| Zen 2       | 1         | 4.76%   |
| SandyBridge | 1         | 4.76%   |
| P6          | 1         | 4.76%   |
| KabyLake    | 1         | 4.76%   |
| K6          | 1         | 4.76%   |
| IvyBridge   | 1         | 4.76%   |
| CometLake   | 1         | 4.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 11        | 50%     |
| AMD                        | 6         | 27.27%  |
| Intel                      | 4         | 18.18%  |
| Matrox Electronics Systems | 1         | 4.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Nvidia GK208B [GeForce GT 710]                                   | 5         | 21.74%  |
| Nvidia GP108 [GeForce GT 1030]                                   | 2         | 8.7%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                               | 2         | 8.7%    |
| AMD Caicos PRO [Radeon HD 7450]                                  | 2         | 8.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                  | 1         | 4.35%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                       | 1         | 4.35%   |
| Matrox Electronics Systems MGA G200eW WPCM450                    | 1         | 4.35%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                        | 1         | 4.35%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                         | 1         | 4.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                        | 1         | 4.35%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                            | 1         | 4.35%   |
| AMD RV370/M22 [Mobility Radeon X300]                             | 1         | 4.35%   |
| AMD RV280 [Radeon 9200] (Secondary)                              | 1         | 4.35%   |
| AMD RV280 [Radeon 9200]                                          | 1         | 4.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 4.35%   |
| AMD Navi 21 [Radeon RX 6900 XT]                                  | 1         | 4.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Nvidia     | 9         | 45%     |
| 1 x AMD        | 5         | 25%     |
| Intel + Nvidia | 2         | 10%     |
| 1 x Intel      | 2         | 10%     |
| 2 x AMD        | 1         | 5%      |
| 1 x Matrox     | 1         | 5%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 13        | 65%     |
| Proprietary | 7         | 35%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 12        | 63.16%  |
| 1.01-2.0   | 2         | 10.53%  |
| 8.01-16.0  | 2         | 10.53%  |
| 0.01-0.5   | 2         | 10.53%  |
| 3.01-4.0   | 1         | 5.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| LG Electronics | 2         | 33.33%  |
| Goldstar       | 2         | 33.33%  |
| Chimei Innolux | 1         | 16.67%  |
| Acer           | 1         | 16.67%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| LG Electronics LCD Monitor LG ULTRAGEAR 2560x1440               | 1         | 14.29%  |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                | 1         | 14.29%  |
| Goldstar LG ULTRAGEAR GSM7765 2560x1440 700x390mm 31.5-inch     | 1         | 14.29%  |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch      | 1         | 14.29%  |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 310x170mm 13.9-inch | 1         | 14.29%  |
| Acer LCD Monitor EI342CKR 3440x1440                             | 1         | 14.29%  |
| Acer EI342CKR ACR0763 3440x1440 800x330mm 34.1-inch             | 1         | 14.29%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Computers | Percent |
|-----------------|-----------|---------|
| 3840x2160 (4K)  | 2         | 33.33%  |
| 2560x1440 (QHD) | 2         | 33.33%  |
| 3440x1440       | 1         | 16.67%  |
| 1366x768 (WXGA) | 1         | 16.67%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2         | 33.33%  |
| 34      | 1         | 16.67%  |
| 31      | 1         | 16.67%  |
| 27      | 1         | 16.67%  |
| 13      | 1         | 16.67%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 2         | 33.33%  |
| 701-800     | 1         | 16.67%  |
| 601-700     | 1         | 16.67%  |
| 501-600     | 1         | 16.67%  |
| 301-350     | 1         | 16.67%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3         | 50%     |
| Unknown | 2         | 33.33%  |
| 21/9    | 1         | 16.67%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 351-500        | 2         | 33.33%  |
| Unknown        | 2         | 33.33%  |
| 81-90          | 1         | 16.67%  |
| 301-350        | 1         | 16.67%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 2         | 33.33%  |
| Unknown | 2         | 33.33%  |
| 161-240 | 1         | 16.67%  |
| 51-100  | 1         | 16.67%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 13        | 65%     |
| 1     | 7         | 35%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 48.15%  |
| Realtek Semiconductor | 9         | 33.33%  |
| U-Blox                | 1         | 3.7%    |
| MediaTek              | 1         | 3.7%    |
| D-Link System         | 1         | 3.7%    |
| Broadcom              | 1         | 3.7%    |
| ASUSTek Computer      | 1         | 3.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 11.11%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 11.11%  |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 8.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 5.56%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 5.56%   |
| Intel I211 Gigabit Network Connection                             | 2         | 5.56%   |
| Intel Ethernet Controller X550                                    | 2         | 5.56%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 2         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 5.56%   |
| U-Blox [u-blox 7]                                                 | 1         | 2.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 2.78%   |
| Intel Wireless-AC 9260                                            | 1         | 2.78%   |
| Intel Wireless 8265 / 8275                                        | 1         | 2.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 2.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 2.78%   |
| Intel Ethernet Controller 10G X550T                               | 1         | 2.78%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 2.78%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 2.78%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 2.78%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 2.78%   |
| ASUS USB-AC53 Nano USB Wieless Adapter                            | 1         | 2.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 7         | 46.67%  |
| Realtek Semiconductor | 6         | 40%     |
| MediaTek              | 1         | 6.67%   |
| ASUSTek Computer      | 1         | 6.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 4         | 26.67%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 13.33%  |
| Intel Wi-Fi 6 AX200                                           | 2         | 13.33%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 1         | 6.67%   |
| Intel Wireless-AC 9260                                        | 1         | 6.67%   |
| Intel Wireless 8265 / 8275                                    | 1         | 6.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 1         | 6.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 6.67%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 6.67%   |
| ASUS USB-AC53 Nano USB Wieless Adapter                        | 1         | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 52.63%  |
| Realtek Semiconductor | 7         | 36.84%  |
| D-Link System         | 1         | 5.26%   |
| Broadcom              | 1         | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4         | 20%     |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 15%     |
| Intel I211 Gigabit Network Connection                             | 2         | 10%     |
| Intel Ethernet Controller X550                                    | 2         | 10%     |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 2         | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 10%     |
| Intel Ethernet Controller 10G X550T                               | 1         | 5%      |
| Intel Ethernet Connection (7) I219-V                              | 1         | 5%      |
| Intel 82574L Gigabit Network Connection                           | 1         | 5%      |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 5%      |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 1         | 5%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 17        | 60.71%  |
| WiFi     | 10        | 35.71%  |
| Modem    | 1         | 3.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 16        | 84.21%  |
| WiFi     | 3         | 15.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 10        | 55.56%  |
| 1     | 6         | 33.33%  |
| 3     | 2         | 11.11%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 16        | 94.12%  |
| Yes  | 1         | 5.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 7         | 58.33%  |
| Realtek Semiconductor   | 3         | 25%     |
| IMC Networks            | 1         | 8.33%   |
| Cambridge Silicon Radio | 1         | 8.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth 4.2 Adapter                       | 2         | 16.67%  |
| Intel AX200 Bluetooth                               | 2         | 16.67%  |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 8.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 8.33%   |
| Intel Bluetooth wireless interface                  | 1         | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 8.33%   |
| Intel AX210 Bluetooth                               | 1         | 8.33%   |
| Intel AX201 Bluetooth                               | 1         | 8.33%   |
| IMC Networks MediaTek Bluetooth Adapter             | 1         | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 8.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Nvidia           | 11        | 40.74%  |
| Intel            | 7         | 25.93%  |
| AMD              | 5         | 18.52%  |
| VIA Technologies | 1         | 3.7%    |
| SteelSeries ApS  | 1         | 3.7%    |
| Logitech         | 1         | 3.7%    |
| Creative Labs    | 1         | 3.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                                                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GK208 HDMI/DP Audio Controller                                                                                                                                                      | 5         | 16.67%  |
| Nvidia GP108 High Definition Audio Controller                                                                                                                                              | 2         | 6.67%   |
| Nvidia GP102 HDMI Audio Controller                                                                                                                                                         | 2         | 6.67%   |
| Intel Tiger Lake-H HD Audio Controller                                                                                                                                                     | 2         | 6.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                                                                                                                        | 2         | 6.67%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                                                                                                          | 2         | 6.67%   |
| VIA Technologies VT82C686 AC97 Audio Controller                                                                                                                                            | 1         | 3.33%   |
| SteelSeries ApS SteelSeries GameDAC GameDAC Hi-Res                                                                                                                                         | 1         | 3.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                                                                                                             | 1         | 3.33%   |
| Nvidia GP107GL High Definition Audio Controller                                                                                                                                            | 1         | 3.33%   |
| Logitech Blue Microphones Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone | 1         | 3.33%   |
| Intel Comet Lake PCH cAVS                                                                                                                                                                  | 1         | 3.33%   |
| Intel Cannon Lake PCH cAVS                                                                                                                                                                 | 1         | 3.33%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                                                                                                             | 1         | 3.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                                                                                                                    | 1         | 3.33%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                                                                                                           | 1         | 3.33%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                                                                                                         | 1         | 3.33%   |
| AMD Starship/Matisse HD Audio Controller                                                                                                                                                   | 1         | 3.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                                                                                                                        | 1         | 3.33%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                                                                                                                    | 1         | 3.33%   |
| AMD Family 17h/19h HD Audio Controller                                                                                                                                                     | 1         | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 21.43%  |
| G.Skill             | 5         | 17.86%  |
| Corsair             | 5         | 17.86%  |
| Unknown             | 2         | 7.14%   |
| Micron Technology   | 2         | 7.14%   |
| Kingston            | 2         | 7.14%   |
| Unknown             | 2         | 7.14%   |
| SK hynix            | 1         | 3.57%   |
| PNY                 | 1         | 3.57%   |
| Elpida              | 1         | 3.57%   |
| Crucial             | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| G.Skill RAM F4-3600C18-32GTZN 32GB DIMM DDR4 3600MT/s   | 4         | 13.79%  |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3200MT/s  | 3         | 10.34%  |
| Unknown                                                 | 2         | 6.9%    |
| Unknown RAM Module 64MB DIMM DRAM                       | 1         | 3.45%   |
| Unknown RAM CL18-22-22 D4-3600 16384MB DIMM 2667MT/s    | 1         | 3.45%   |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s              | 1         | 3.45%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s              | 1         | 3.45%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 3.45%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s  | 1         | 3.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s   | 1         | 3.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 1         | 3.45%   |
| Samsung RAM M391B5273DH0-CK0 4GB DIMM DDR3 1600MT/s     | 1         | 3.45%   |
| PNY RAM 16GU2X08QJLL42-12-K 16GB SODIMM DDR4 3200MT/s   | 1         | 3.45%   |
| Micron RAM Module 8GB DIMM DDR3 1600MT/s                | 1         | 3.45%   |
| Micron RAM 4ATF51264HZ-2G3B2 4GB SODIMM DDR4 2400MT/s   | 1         | 3.45%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s   | 1         | 3.45%   |
| Kingston RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s   | 1         | 3.45%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s   | 1         | 3.45%   |
| G.Skill RAM F4-4400C19-16GTZR 16GB DIMM DDR4 2667MT/s   | 1         | 3.45%   |
| Elpida RAM Module 8GB DIMM DDR3 1600MT/s                | 1         | 3.45%   |
| Crucial RAM CT16G4DFRA32A.M16FR 16GB DIMM DDR4 3200MT/s | 1         | 3.45%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s  | 1         | 3.45%   |
| Corsair RAM CMK16GX4M2Z2666C16 8GB DIMM DDR4 2666MT/s   | 1         | 3.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 13        | 72.22%  |
| DDR3 | 3         | 16.67%  |
| DRAM | 1         | 5.56%   |
| DDR  | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 13        | 72.22%  |
| SODIMM | 5         | 27.78%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 10        | 40%     |
| 32768 | 5         | 20%     |
| 8192  | 5         | 20%     |
| 4096  | 2         | 8%      |
| 1024  | 1         | 4%      |
| 256   | 1         | 4%      |
| 64    | 1         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 6         | 28.57%  |
| 3600    | 4         | 19.05%  |
| 2667    | 3         | 14.29%  |
| 1600    | 3         | 14.29%  |
| 3000    | 1         | 4.76%   |
| 2666    | 1         | 4.76%   |
| 2400    | 1         | 4.76%   |
| 667     | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

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


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Logitech                    | 4         | 57.14%  |
| Luxvisions Innotech Limited | 1         | 14.29%  |
| Chicony Electronics         | 1         | 14.29%  |
| Bison Electronics           | 1         | 14.29%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Logitech HD Pro Webcam C920                          | 2         | 28.57%  |
| Logitech C922 Pro Stream Webcam                      | 2         | 28.57%  |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 14.29%  |
| Chicony Integrated Camera (1280x720@30)              | 1         | 14.29%  |
| Bison Integrated Camera                              | 1         | 14.29%  |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Synaptics | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Synaptics Metallica MIS Touch Fingerprint Reader | 1         | 100%    |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 6         | 30%     |
| 3     | 4         | 20%     |
| 1     | 4         | 20%     |
| 4     | 2         | 10%     |
| 2     | 2         | 10%     |
| 6     | 1         | 5%      |
| 5     | 1         | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 9         | 33.33%  |
| Communication controller | 8         | 29.63%  |
| Bluetooth                | 4         | 14.81%  |
| Sound                    | 2         | 7.41%   |
| Card reader              | 2         | 7.41%   |
| Firewire controller      | 1         | 3.7%    |
| Fingerprint reader       | 1         | 3.7%    |

