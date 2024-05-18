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

Total: 69

| Vendor     | Model                       | Form-Factor | Probe                                                     | Date         |
|------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [0323476838](https://bsd-hardware.info/?probe=0323476838) | Apr 28, 2024 |
| Supermicro | X9SCL/X9SCMA                | Desktop     | [53bdb73b74](https://bsd-hardware.info/?probe=53bdb73b74) | Feb 14, 2024 |
| ASRock     | B550M Steel Legend          | Desktop     | [fa494be63d](https://bsd-hardware.info/?probe=fa494be63d) | Jan 26, 2024 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | Desktop     | [eda92591b5](https://bsd-hardware.info/?probe=eda92591b5) | Jan 07, 2024 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | Desktop     | [12ff062207](https://bsd-hardware.info/?probe=12ff062207) | Jan 07, 2024 |
| ASRock     | B550M Steel Legend          | Desktop     | [d24b57f807](https://bsd-hardware.info/?probe=d24b57f807) | Jan 06, 2024 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [98663cbfef](https://bsd-hardware.info/?probe=98663cbfef) | Dec 22, 2023 |
| Lenovo     | ThinkPad A485 20MU000VUS    | Notebook    | [8f21b7d70f](https://bsd-hardware.info/?probe=8f21b7d70f) | Nov 24, 2023 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [a98f0b3d67](https://bsd-hardware.info/?probe=a98f0b3d67) | Sep 03, 2023 |
| ASRock     | X570 Steel Legend WiFi a... | Desktop     | [d352ea60cf](https://bsd-hardware.info/?probe=d352ea60cf) | Sep 03, 2023 |
| ASUSTek    | TUF Gaming B450M-PLUS II    | Desktop     | [1b53079f34](https://bsd-hardware.info/?probe=1b53079f34) | Aug 19, 2023 |
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
| MidnightBSD 3.1.0 | 5         | 10%     |
| MidnightBSD 2.0.2 | 4         | 8%      |
| MidnightBSD 1.2   | 4         | 8%      |
| MidnightBSD 3.0.0 | 3         | 6%      |
| MidnightBSD 2.2.6 | 3         | 6%      |
| MidnightBSD 2.2.0 | 3         | 6%      |
| MidnightBSD 2.0.1 | 3         | 6%      |
| MidnightBSD 3.0.1 | 2         | 4%      |
| MidnightBSD 2.1.8 | 2         | 4%      |
| MidnightBSD 2.1.5 | 2         | 4%      |
| MidnightBSD 2.1.1 | 2         | 4%      |
| MidnightBSD 2.0.7 | 2         | 4%      |
| MidnightBSD 3.2.0 | 1         | 2%      |
| MidnightBSD 3.1.4 | 1         | 2%      |
| MidnightBSD 3.1.3 | 1         | 2%      |
| MidnightBSD 3.1.2 | 1         | 2%      |
| MidnightBSD 3.1.1 | 1         | 2%      |
| MidnightBSD 2.2.8 | 1         | 2%      |
| MidnightBSD 2.2.5 | 1         | 2%      |
| MidnightBSD 2.2.2 | 1         | 2%      |
| MidnightBSD 2.1.6 | 1         | 2%      |
| MidnightBSD 2.1.3 | 1         | 2%      |
| MidnightBSD 2.1.2 | 1         | 2%      |
| MidnightBSD 2.1.0 | 1         | 2%      |
| MidnightBSD 2.0   | 1         | 2%      |
| MidnightBSD 1.2.9 | 1         | 2%      |
| MidnightBSD 1.2.7 | 1         | 2%      |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| MidnightBSD | 18        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 16        | 88.89%  |
| i386  | 2         | 11.11%  |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| XFCE         | 9         | 40.91%  |
| Console      | 7         | 31.82%  |
| GNOME        | 5         | 22.73%  |
| Window Maker | 1         | 4.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 11        | 52.38%  |
| X11     | 10        | 47.62%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 18        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 17        | 94.44%  |
| fi_FI.ISO8859-15 | 1         | 5.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 14        | 77.78%  |
| BIOS | 4         | 22.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 13        | 72.22%  |
| Ufs  | 5         | 27.78%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 17        | 94.44%  |
| MBR  | 1         | 5.56%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 8         | 44.44%  |
| Hewlett-Packard  | 3         | 16.67%  |
| ASRock           | 3         | 16.67%  |
| Lenovo           | 2         | 11.11%  |
| Supermicro       | 1         | 5.56%   |
| Dell             | 1         | 5.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS TUF GAMING B450M-PLUS II         | 3         | 16.67%  |
| ASRock B550M Steel Legend             | 2         | 11.11%  |
| Supermicro X9SCL/X9SCM                | 1         | 5.56%   |
| Lenovo ThinkPad X1 Extreme 20MF000BUS | 1         | 5.56%   |
| Lenovo ThinkPad A485 20MU000VUS       | 1         | 5.56%   |
| HP Z420 Workstation                   | 1         | 5.56%   |
| HP Victus by Gaming Laptop 15-fa0xxx  | 1         | 5.56%   |
| HP ENVY TE01-1xxx                     | 1         | 5.56%   |
| Dell Latitude D610                    | 1         | 5.56%   |
| ASUS TUF Gaming B560M-PLUS WIFI       | 1         | 5.56%   |
| ASUS TUF B350M-PLUS GAMING            | 1         | 5.56%   |
| ASUS PRIME Z590-P                     | 1         | 5.56%   |
| ASUS PRIME X370-PRO                   | 1         | 5.56%   |
| ASUS A7VI-VM                          | 1         | 5.56%   |
| ASRock X570 Steel Legend WiFi ax      | 1         | 5.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| ASUS TUF         | 5         | 27.78%  |
| Lenovo ThinkPad  | 2         | 11.11%  |
| ASUS PRIME       | 2         | 11.11%  |
| ASRock B550M     | 2         | 11.11%  |
| Supermicro X9SCL | 1         | 5.56%   |
| HP Z420          | 1         | 5.56%   |
| HP Victus        | 1         | 5.56%   |
| HP ENVY          | 1         | 5.56%   |
| Dell Latitude    | 1         | 5.56%   |
| ASUS A7VI-VM     | 1         | 5.56%   |
| ASRock X570      | 1         | 5.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 5         | 27.78%  |
| 2018 | 3         | 16.67%  |
| 2020 | 2         | 11.11%  |
| 2023 | 1         | 5.56%   |
| 2022 | 1         | 5.56%   |
| 2021 | 1         | 5.56%   |
| 2017 | 1         | 5.56%   |
| 2013 | 1         | 5.56%   |
| 2011 | 1         | 5.56%   |
| 2005 | 1         | 5.56%   |
| 2001 | 1         | 5.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 14        | 77.78%  |
| Notebook | 4         | 22.22%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 18        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 64.01-256.0 | 8         | 36.36%  |
| 32.01-64.0  | 7         | 31.82%  |
| 16.01-24.0  | 2         | 9.09%   |
| 8.01-16.0   | 2         | 9.09%   |
| 24.01-32.0  | 1         | 4.55%   |
| 2.01-3.0    | 1         | 4.55%   |
| 0.01-0.5    | 1         | 4.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 12        | 40%     |
| 32.01-64.0 | 3         | 10%     |
| 16.01-24.0 | 3         | 10%     |
| 0.51-1.0   | 3         | 10%     |
| 24.01-32.0 | 2         | 6.67%   |
| 2.01-3.0   | 2         | 6.67%   |
| Unknown    | 2         | 6.67%   |
| 4.01-8.0   | 1         | 3.33%   |
| 0.01-0.5   | 1         | 3.33%   |
| 0          | 1         | 3.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 7         | 26.92%  |
| 5      | 5         | 19.23%  |
| 8      | 3         | 11.54%  |
| 3      | 3         | 11.54%  |
| 7      | 2         | 7.69%   |
| 6      | 2         | 7.69%   |
| 2      | 2         | 7.69%   |
| 4      | 1         | 3.85%   |
| 0      | 1         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 16        | 80%     |
| Yes       | 4         | 20%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 18        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10        | 55.56%  |
| No        | 8         | 44.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9         | 50%     |
| No        | 9         | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| USA     | 16        | 88.89%  |
| Germany | 1         | 5.56%   |
| Finland | 1         | 5.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City        | Computers | Percent |
|-------------|-----------|---------|
| Ypsilanti   | 14        | 77.78%  |
| Wuppertal   | 1         | 5.56%   |
| Tampere     | 1         | 5.56%   |
| Los Angeles | 1         | 5.56%   |
| Fresno      | 1         | 5.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 50     | 20.93%  |
| Samsung Electronics | 8         | 58     | 18.6%   |
| WDC                 | 6         | 26     | 13.95%  |
| Intel               | 6         | 43     | 13.95%  |
| Toshiba             | 3         | 7      | 6.98%   |
| SanDisk             | 2         | 12     | 4.65%   |
| KIOXIA              | 2         | 3      | 4.65%   |
| SK hynix            | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 2      | 2.33%   |
| Maxtor              | 1         | 1      | 2.33%   |
| Lenovo              | 1         | 1      | 2.33%   |
| Hewlett-Packard     | 1         | 1      | 2.33%   |
| Crucial             | 1         | 3      | 2.33%   |
| A-DATA Technology   | 1         | 2      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                   | 5         | 7.04%   |
| Samsung SSD 970 PRO 512GB                   | 4         | 5.63%   |
| Intel SSDSC2KG480G8 480GB                   | 4         | 5.63%   |
| Seagate ST8000VN0022-2EL112 8TB             | 3         | 4.23%   |
| Seagate ST8000VN0002-1Z8112 8TB             | 3         | 4.23%   |
| Samsung SSD 870 EVO 1TB                     | 3         | 4.23%   |
| Intel SSDPED1D480GA 480GB                   | 3         | 4.23%   |
| WDC WDS100T3X0C-00SJG0 1TB                  | 2         | 2.82%   |
| WDC WD60EFAX-68SHWN0 6TB                    | 2         | 2.82%   |
| Toshiba THNSNJ128GCSU 128GB                 | 2         | 2.82%   |
| Seagate ST16000NM001G-2KK103 16TB           | 2         | 2.82%   |
| Seagate ST10000VN0008-2PJ103 10TB           | 2         | 2.82%   |
| Seagate ST10000NE0008-2PL103 10TB           | 2         | 2.82%   |
| Seagate IronWolf ZA1000NM10002-2ZG102 1TB   | 2         | 2.82%   |
| Seagate FireCuda 120 SSD ZA500GM10001 500GB | 2         | 2.82%   |
| Samsung SSD 860 QVO 2TB                     | 2         | 2.82%   |
| Samsung SSD 860 EVO 1TB                     | 2         | 2.82%   |
| Samsung SSD 750 EVO 250GB                   | 2         | 2.82%   |
| KIOXIA KBG40ZNV1T02 1TB                     | 2         | 2.82%   |
| WDC WD5000LPLX-08ZNTT0 500GB                | 1         | 1.41%   |
| WDC WD30EZRX-00MMMB0 3TB                    | 1         | 1.41%   |
| WDC WD1003FZEX-00K3CA0 1TB                  | 1         | 1.41%   |
| Toshiba TL100 120GB                         | 1         | 1.41%   |
| SK hynix SHGP31-1000GM 1TB                  | 1         | 1.41%   |
| Seagate ST980210A 80GB                      | 1         | 1.41%   |
| Seagate ST5000DM000-1FK178 5TB              | 1         | 1.41%   |
| Seagate ST2000DM001-1CH164 2TB              | 1         | 1.41%   |
| SanDisk Ultra 3D NVMe 500GB                 | 1         | 1.41%   |
| SanDisk SSD PLUS 240GB                      | 1         | 1.41%   |
| Samsung MZ7LM1T9HCJM-00003 1.9TB            | 1         | 1.41%   |
| Micron MTFDKBA512TFH-1BC1AABHA 512GB        | 1         | 1.41%   |
| Maxtor STM3250310AS 250GB                   | 1         | 1.41%   |
| Lenovo LENSE30512GMSP34MEAT3TA 512GB        | 1         | 1.41%   |
| Intel SSDSC2KW480H6 480GB                   | 1         | 1.41%   |
| Intel SSDSC2KB019T8 1.9TB                   | 1         | 1.41%   |
| Intel SSDSC2BW240H6 240GB                   | 1         | 1.41%   |
| Intel SSDSA2CT040G3 40GB                    | 1         | 1.41%   |
| HP SSD S700 120GB                           | 1         | 1.41%   |
| Crucial CT500P2SSD8 500GB                   | 1         | 1.41%   |
| Crucial CT4000P3SSD8 4TB                    | 1         | 1.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 20     | 45.45%  |
| Seagate | 5         | 43     | 45.45%  |
| Maxtor  | 1         | 1      | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 43     | 35%     |
| Seagate             | 4         | 7      | 20%     |
| Intel               | 4         | 33     | 20%     |
| Toshiba             | 3         | 7      | 15%     |
| SanDisk             | 1         | 7      | 5%      |
| Hewlett-Packard     | 1         | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 13        | 98     | 40.63%  |
| NVMe | 11        | 48     | 34.38%  |
| HDD  | 8         | 64     | 25%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 16        | 162    | 59.26%  |
| NVMe | 11        | 48     | 40.74%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 73     | 48.39%  |
| 0.51-1.0   | 6         | 22     | 19.35%  |
| 1.01-2.0   | 4         | 11     | 12.9%   |
| 4.01-10.0  | 3         | 49     | 9.68%   |
| 10.01-20.0 | 2         | 6      | 6.45%   |
| 2.01-3.0   | 1         | 1      | 3.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 251-500    | 12        | 57.14%  |
| 501-1000   | 4         | 19.05%  |
| 101-250    | 3         | 14.29%  |
| 21-50      | 1         | 4.76%   |
| 51-100     | 1         | 4.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 12        | 48%     |
| 21-50   | 6         | 24%     |
| 51-100  | 4         | 16%     |
| 251-500 | 2         | 8%      |
| 101-250 | 1         | 4%      |

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
| Works    | 18        | 206    | 85.71%  |
| Malfunc  | 2         | 3      | 9.52%   |
| Detected | 1         | 1      | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 9         | 25%     |
| AMD                       | 9         | 25%     |
| SanDisk                   | 4         | 11.11%  |
| Samsung Electronics       | 4         | 11.11%  |
| Realtek Semiconductor     | 2         | 5.56%   |
| KIOXIA                    | 2         | 5.56%   |
| VIA Technologies          | 1         | 2.78%   |
| SK hynix                  | 1         | 2.78%   |
| Silicon Image             | 1         | 2.78%   |
| Micron/Crucial Technology | 1         | 2.78%   |
| Micron Technology         | 1         | 2.78%   |
| Lenovo                    | 1         | 2.78%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 6         | 13.33%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 4         | 8.89%   |
| AMD 400 Series Chipset SATA Controller                                        | 4         | 8.89%   |
| Intel Optane SSD 900P Series                                                  | 3         | 6.67%   |
| AMD 500 Series Chipset SATA Controller                                        | 3         | 6.67%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD          | 2         | 4.44%   |
| Realtek RTS5763DL x2 NVMe SSD Controller                                      | 2         | 4.44%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                    | 2         | 4.44%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 4.44%   |
| AMD 300 Series Chipset SATA Controller                                        | 2         | 4.44%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                   | 1         | 2.22%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                          | 1         | 2.22%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller              | 1         | 2.22%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD       | 1         | 2.22%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                     | 1         | 2.22%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)          | 1         | 2.22%   |
| Micron 3400 NVMe SSD [Hendrix]                                                | 1         | 2.22%   |
| Lenovo LENSE30512GMSP34MEAT3TA                                                | 1         | 2.22%   |
| Intel SATA Controller [RAID mode]                                             | 1         | 2.22%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 1         | 2.22%   |
| Intel C600/X79 series chipset IDE-r Controller                                | 1         | 2.22%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                     | 1         | 2.22%   |
| Intel 82801FBM (ICH6M) SATA Controller                                        | 1         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller | 1         | 2.22%   |
| AMD X370 Series Chipset SATA Controller                                       | 1         | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 13        | 40.63%  |
| SATA | 13        | 40.63%  |
| IDE  | 3         | 9.38%   |
| RAID | 2         | 6.25%   |
| SAS  | 1         | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 10        | 55.56%  |
| Intel  | 8         | 44.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 7 5800X 8-Core Processor              | 3         | 13.64%  |
| AMD Ryzen 7 2700 Eight-Core Processor           | 3         | 13.64%  |
| AMD Ryzen 7 5700X 8-Core Processor              | 2         | 9.09%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 2         | 9.09%   |
| Intel Xeon CPU E5-2670 @ 2.60GHz                | 1         | 4.55%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz             | 1         | 4.55%   |
| Intel Pentium M                                 | 1         | 4.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 4.55%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 1         | 4.55%   |
| Intel 12th Gen Core i5-12450H                   | 1         | 4.55%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz         | 1         | 4.55%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz          | 1         | 4.55%   |
| AMD Ryzen 9 3950X 16-Core Processor             | 1         | 4.55%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 1         | 4.55%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1         | 4.55%   |
| AMD Duron Processor                             | 1         | 4.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model           | Computers | Percent |
|-----------------|-----------|---------|
| AMD Ryzen 7     | 8         | 42.11%  |
| Other           | 4         | 21.05%  |
| Intel Xeon      | 2         | 10.53%  |
| Intel Core i7   | 2         | 10.53%  |
| Intel Pentium M | 1         | 5.26%   |
| AMD Ryzen 9     | 1         | 5.26%   |
| AMD Ryzen 5 PRO | 1         | 5.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 8      | 11        | 47.83%  |
| 16     | 4         | 17.39%  |
| 6      | 2         | 8.7%    |
| 4      | 2         | 8.7%    |
| 1      | 2         | 8.7%    |
| 32     | 1         | 4.35%   |
| 12     | 1         | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 18        | 94.74%  |
| 2      | 1         | 5.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 14        | 63.64%  |
| 1       | 7         | 31.82%  |
| Unknown | 1         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Zen 3       | 5         | 22.73%  |
| Zen+        | 4         | 18.18%  |
| Zen         | 3         | 13.64%  |
| Unknown     | 3         | 13.64%  |
| Zen 2       | 1         | 4.55%   |
| SandyBridge | 1         | 4.55%   |
| P6          | 1         | 4.55%   |
| KabyLake    | 1         | 4.55%   |
| K6          | 1         | 4.55%   |
| IvyBridge   | 1         | 4.55%   |
| CometLake   | 1         | 4.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Nvidia                     | 12        | 52.17%  |
| AMD                        | 6         | 26.09%  |
| Intel                      | 4         | 17.39%  |
| Matrox Electronics Systems | 1         | 4.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Nvidia GK208B [GeForce GT 710]                                   | 6         | 25%     |
| Nvidia GP108 [GeForce GT 1030]                                   | 2         | 8.33%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                               | 2         | 8.33%   |
| AMD Caicos PRO [Radeon HD 7450]                                  | 2         | 8.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                  | 1         | 4.17%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                       | 1         | 4.17%   |
| Matrox Electronics Systems MGA G200eW WPCM450                    | 1         | 4.17%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                        | 1         | 4.17%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                         | 1         | 4.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                        | 1         | 4.17%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                            | 1         | 4.17%   |
| AMD RV370/M22 [Mobility Radeon X300]                             | 1         | 4.17%   |
| AMD RV280 [Radeon 9200] (Secondary)                              | 1         | 4.17%   |
| AMD RV280 [Radeon 9200]                                          | 1         | 4.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series] | 1         | 4.17%   |
| AMD Navi 21 [Radeon RX 6900 XT]                                  | 1         | 4.17%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Nvidia     | 10        | 47.62%  |
| 1 x AMD        | 5         | 23.81%  |
| Intel + Nvidia | 2         | 9.52%   |
| 1 x Intel      | 2         | 9.52%   |
| 2 x AMD        | 1         | 4.76%   |
| 1 x Matrox     | 1         | 4.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 13        | 61.9%   |
| Proprietary | 8         | 38.1%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 65%     |
| 1.01-2.0   | 2         | 10%     |
| 8.01-16.0  | 2         | 10%     |
| 0.01-0.5   | 2         | 10%     |
| 3.01-4.0   | 1         | 5%      |

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
| 0     | 14        | 66.67%  |
| 1     | 7         | 33.33%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 46.43%  |
| Realtek Semiconductor | 9         | 32.14%  |
| Broadcom              | 2         | 7.14%   |
| U-Blox                | 1         | 3.57%   |
| MediaTek              | 1         | 3.57%   |
| D-Link System         | 1         | 3.57%   |
| ASUSTek Computer      | 1         | 3.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4         | 10.81%  |
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 4         | 10.81%  |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 8.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 5.41%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 5.41%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 5.41%   |
| Intel Ethernet Controller X550                                         | 2         | 5.41%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2         | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 5.41%   |
| U-Blox [u-blox 7]                                                      | 1         | 2.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1         | 2.7%    |
| Intel Wireless 8265 / 8275                                             | 1         | 2.7%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1         | 2.7%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 1         | 2.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                         | 1         | 2.7%    |
| Intel Ethernet Controller 10G X550T                                    | 1         | 2.7%    |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 1         | 2.7%    |
| Intel 82574L Gigabit Network Connection                                | 1         | 2.7%    |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 1         | 2.7%    |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1         | 2.7%    |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 1         | 2.7%    |
| ASUS USB-AC53 Nano USB Wieless Adapter                                 | 1         | 2.7%    |

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
| Intel Wireless 8265 / 8275                                    | 1         | 6.67%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 1         | 6.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 1         | 6.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 6.67%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 6.67%   |
| ASUS USB-AC53 Nano USB Wieless Adapter                        | 1         | 6.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 50%     |
| Realtek Semiconductor | 7         | 35%     |
| Broadcom              | 2         | 10%     |
| D-Link System         | 1         | 5%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 4         | 19.05%  |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 14.29%  |
| Intel I211 Gigabit Network Connection                                  | 2         | 9.52%   |
| Intel Ethernet Controller X550                                         | 2         | 9.52%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                          | 2         | 9.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 9.52%   |
| Intel Ethernet Controller 10G X550T                                    | 1         | 4.76%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 4.76%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 4.76%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 1         | 4.76%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                     | 1         | 4.76%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 1         | 4.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 18        | 62.07%  |
| WiFi     | 10        | 34.48%  |
| Modem    | 1         | 3.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 17        | 85%     |
| WiFi     | 3         | 15%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 11        | 57.89%  |
| 1     | 6         | 31.58%  |
| 3     | 2         | 10.53%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 17        | 89.47%  |
| Yes  | 2         | 10.53%  |

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


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Nvidia                | 12        | 41.38%  |
| Intel                 | 7         | 24.14%  |
| AMD                   | 5         | 17.24%  |
| VIA Technologies      | 1         | 3.45%   |
| SteelSeries ApS       | 1         | 3.45%   |
| Realtek Semiconductor | 1         | 3.45%   |
| Logitech              | 1         | 3.45%   |
| Creative Labs         | 1         | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                                                                                                                      | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia GK208 HDMI/DP Audio Controller                                                                                                                                                      | 6         | 18.75%  |
| Nvidia GP108 High Definition Audio Controller                                                                                                                                              | 2         | 6.25%   |
| Nvidia GP102 HDMI Audio Controller                                                                                                                                                         | 2         | 6.25%   |
| Intel Tiger Lake-H HD Audio Controller                                                                                                                                                     | 2         | 6.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                                                                                                                        | 2         | 6.25%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                                                                                                          | 2         | 6.25%   |
| VIA Technologies VT82C686 AC97 Audio Controller                                                                                                                                            | 1         | 3.13%   |
| SteelSeries ApS SteelSeries GameDAC GameDAC Hi-Res                                                                                                                                         | 1         | 3.13%   |
| Realtek Semiconductor USB Audio                                                                                                                                                            | 1         | 3.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                                                                                                             | 1         | 3.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                                                                                                            | 1         | 3.13%   |
| Logitech Blue Microphones Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone Yeti Stereo Microphone | 1         | 3.13%   |
| Intel Comet Lake PCH cAVS                                                                                                                                                                  | 1         | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                                                                                                                                 | 1         | 3.13%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                                                                                                             | 1         | 3.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                                                                                                                    | 1         | 3.13%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                                                                                                           | 1         | 3.13%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                                                                                                         | 1         | 3.13%   |
| AMD Starship/Matisse HD Audio Controller                                                                                                                                                   | 1         | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                                                                                                                        | 1         | 3.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                                                                                                                    | 1         | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                                                                                                                                     | 1         | 3.13%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 20%     |
| G.Skill             | 5         | 16.67%  |
| Corsair             | 5         | 16.67%  |
| Unknown             | 3         | 10%     |
| Unknown             | 2         | 6.67%   |
| Micron Technology   | 2         | 6.67%   |
| Kingston            | 2         | 6.67%   |
| SK hynix            | 1         | 3.33%   |
| PNY                 | 1         | 3.33%   |
| Mushkin             | 1         | 3.33%   |
| Elpida              | 1         | 3.33%   |
| Crucial             | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| G.Skill RAM F4-3600C18-32GTZN 32GB DIMM DDR4 3600MT/s   | 4         | 12.9%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3200MT/s  | 3         | 9.68%   |
| Unknown                                                 | 3         | 9.68%   |
| Unknown RAM Module 64MB DIMM DRAM                       | 1         | 3.23%   |
| Unknown RAM CL18-22-22 D4-3600 16384MB DIMM 2667MT/s    | 1         | 3.23%   |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s              | 1         | 3.23%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s              | 1         | 3.23%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 3.23%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s  | 1         | 3.23%   |
| Samsung RAM M471A1K43EB1-CWE 16GB SODIMM DDR4 3200MT/s  | 1         | 3.23%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 1         | 3.23%   |
| Samsung RAM M391B5273DH0-CK0 4GB DIMM DDR3 1600MT/s     | 1         | 3.23%   |
| PNY RAM 16GU2X08QJLL42-12-K 16GB SODIMM DDR4 3200MT/s   | 1         | 3.23%   |
| Mushkin RAM MRX4U320GJJM32G 32GB DIMM DDR4 2400MT/s     | 1         | 3.23%   |
| Micron RAM Module 8GB DIMM DDR3 1600MT/s                | 1         | 3.23%   |
| Micron RAM 4ATF51264HZ-2G3B2 4GB SODIMM DDR4 2400MT/s   | 1         | 3.23%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s   | 1         | 3.23%   |
| Kingston RAM 9965525-138.A00LF 8GB DIMM DDR3 1600MT/s   | 1         | 3.23%   |
| Kingston RAM 9965525-116.A00LF 8GB DIMM DDR3 1600MT/s   | 1         | 3.23%   |
| G.Skill RAM F4-4400C19-16GTZR 16GB DIMM DDR4 2667MT/s   | 1         | 3.23%   |
| Elpida RAM Module 8GB DIMM DDR3 1600MT/s                | 1         | 3.23%   |
| Crucial RAM CT16G4DFRA32A.M16FR 16GB DIMM DDR4 3200MT/s | 1         | 3.23%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3000MT/s  | 1         | 3.23%   |
| Corsair RAM CMK16GX4M2Z2666C16 8GB DIMM DDR4 2666MT/s   | 1         | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| DDR4 | 14        | 73.68%  |
| DDR3 | 3         | 15.79%  |
| DRAM | 1         | 5.26%   |
| DDR  | 1         | 5.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 14        | 73.68%  |
| SODIMM | 5         | 26.32%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 16384 | 10        | 40%     |
| 32768 | 6         | 24%     |
| 8192  | 4         | 16%     |
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
| 3200    | 6         | 27.27%  |
| 3600    | 4         | 18.18%  |
| 2667    | 3         | 13.64%  |
| 1600    | 3         | 13.64%  |
| 2400    | 2         | 9.09%   |
| 3000    | 1         | 4.55%   |
| 2666    | 1         | 4.55%   |
| 667     | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

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
| 0     | 7         | 33.33%  |
| 3     | 4         | 19.05%  |
| 1     | 4         | 19.05%  |
| 4     | 2         | 9.52%   |
| 2     | 2         | 9.52%   |
| 6     | 1         | 4.76%   |
| 5     | 1         | 4.76%   |

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

