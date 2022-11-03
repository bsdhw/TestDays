NomadBSD 1.3.2 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for NomadBSD 1.3.2.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NomadBSD_1.3.2/Desktop/README.md) and [notebooks](/Dist/NomadBSD_1.3.2/Notebook/README.md).

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

Total: 67

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Apple         | MacBookPro8,1               | Notebook    | [d1aaeaad42](https://bsd-hardware.info/?probe=d1aaeaad42) | Apr 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0621acab4e](https://bsd-hardware.info/?probe=0621acab4e) | Apr 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [0dc468c860](https://bsd-hardware.info/?probe=0dc468c860) | Feb 22, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [fe7d72b06a](https://bsd-hardware.info/?probe=fe7d72b06a) | Feb 21, 2021 |
| Dell          | Latitude 3410               | Notebook    | [f81c1e338f](https://bsd-hardware.info/?probe=f81c1e338f) | Feb 07, 2021 |
| HP            | 0AACh                       | Desktop     | [b7cac343f6](https://bsd-hardware.info/?probe=b7cac343f6) | Jan 29, 2021 |
| HP            | 3399                        | Desktop     | [b11946a41a](https://bsd-hardware.info/?probe=b11946a41a) | Jan 13, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [8093f75ea2](https://bsd-hardware.info/?probe=8093f75ea2) | Jan 13, 2021 |
| Dell          | Latitude 5400               | Notebook    | [f242897c33](https://bsd-hardware.info/?probe=f242897c33) | Jan 13, 2021 |
| Dell          | Latitude 5490               | Notebook    | [3fba47b07f](https://bsd-hardware.info/?probe=3fba47b07f) | Jan 12, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ba45e27f88](https://bsd-hardware.info/?probe=ba45e27f88) | Jan 12, 2021 |
| ASUSTek       | N75SF                       | Notebook    | [7efb6557a2](https://bsd-hardware.info/?probe=7efb6557a2) | Jan 10, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [9ccf63e228](https://bsd-hardware.info/?probe=9ccf63e228) | Jan 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [e18df4623a](https://bsd-hardware.info/?probe=e18df4623a) | Jan 09, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [d894ae5d09](https://bsd-hardware.info/?probe=d894ae5d09) | Jan 07, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d54f451ea5](https://bsd-hardware.info/?probe=d54f451ea5) | Jan 07, 2021 |
| HP            | 3032h                       | Desktop     | [13648fd22d](https://bsd-hardware.info/?probe=13648fd22d) | Jan 07, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ee2d5f3289](https://bsd-hardware.info/?probe=ee2d5f3289) | Jan 07, 2021 |
| Dell          | 030VXY A01                  | Desktop     | [c117ffdc98](https://bsd-hardware.info/?probe=c117ffdc98) | Jan 07, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [cfc292e9e8](https://bsd-hardware.info/?probe=cfc292e9e8) | Jan 07, 2021 |
| Sony          | VPCM13M1R                   | Notebook    | [30bb4fc23c](https://bsd-hardware.info/?probe=30bb4fc23c) | Jan 06, 2021 |
| NEC Comput... | PC-GL186Y3AZ                | Notebook    | [b9f8e78467](https://bsd-hardware.info/?probe=b9f8e78467) | Jan 05, 2021 |
| Dell          | Latitude 5280               | Notebook    | [1ae6e6ee2d](https://bsd-hardware.info/?probe=1ae6e6ee2d) | Jan 05, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [cfd6a0ab4b](https://bsd-hardware.info/?probe=cfd6a0ab4b) | Jan 04, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [876f5d7b92](https://bsd-hardware.info/?probe=876f5d7b92) | Jan 02, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [889bba9dbc](https://bsd-hardware.info/?probe=889bba9dbc) | Dec 30, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a3e2c4eda1](https://bsd-hardware.info/?probe=a3e2c4eda1) | Dec 30, 2020 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [df9318dcea](https://bsd-hardware.info/?probe=df9318dcea) | Dec 27, 2020 |
| Dell          | Inspiron 5758               | Notebook    | [51ed7b02c2](https://bsd-hardware.info/?probe=51ed7b02c2) | Dec 21, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c8c11a071d](https://bsd-hardware.info/?probe=c8c11a071d) | Dec 14, 2020 |
| Acer          | Aspire V5-122               | Notebook    | [ce0c079fd5](https://bsd-hardware.info/?probe=ce0c079fd5) | Dec 14, 2020 |
| Apple         | MacBookPro11,3              | Notebook    | [26f15a2838](https://bsd-hardware.info/?probe=26f15a2838) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [21d88f733e](https://bsd-hardware.info/?probe=21d88f733e) | Dec 07, 2020 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [cdfcd11f7b](https://bsd-hardware.info/?probe=cdfcd11f7b) | Dec 07, 2020 |
| IBM           | 2647NG8                     | Notebook    | [a0f38de52f](https://bsd-hardware.info/?probe=a0f38de52f) | Nov 22, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [bf763e72ad](https://bsd-hardware.info/?probe=bf763e72ad) | Nov 13, 2020 |
| Acer          | Aspire E5-432               | Notebook    | [39fb05c049](https://bsd-hardware.info/?probe=39fb05c049) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [31f5a66353](https://bsd-hardware.info/?probe=31f5a66353) | Oct 25, 2020 |
| Acer          | Aspire V3-575G              | Notebook    | [1ff0e90d9d](https://bsd-hardware.info/?probe=1ff0e90d9d) | Oct 24, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [a1c6966373](https://bsd-hardware.info/?probe=a1c6966373) | Oct 21, 2020 |
| Google        | Chell                       | Notebook    | [4ffe68c199](https://bsd-hardware.info/?probe=4ffe68c199) | Oct 21, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [407652fc8d](https://bsd-hardware.info/?probe=407652fc8d) | Oct 05, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [36d0d99aa6](https://bsd-hardware.info/?probe=36d0d99aa6) | Oct 04, 2020 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1d227a9cd2](https://bsd-hardware.info/?probe=1d227a9cd2) | Oct 04, 2020 |
| Dell          | Precision 7530              | Notebook    | [717309ee39](https://bsd-hardware.info/?probe=717309ee39) | Sep 28, 2020 |
| Dell          | Precision 7530              | Notebook    | [6a2635237f](https://bsd-hardware.info/?probe=6a2635237f) | Sep 28, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | Notebook    | [f7d13e4696](https://bsd-hardware.info/?probe=f7d13e4696) | Sep 23, 2020 |
| Lenovo        | ThinkPad T530 24295VU       | Notebook    | [45f410f4e4](https://bsd-hardware.info/?probe=45f410f4e4) | Sep 23, 2020 |
| Lenovo        | ThinkPad T430 2347C32       | Notebook    | [339c63a941](https://bsd-hardware.info/?probe=339c63a941) | Sep 22, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [89bb299f1e](https://bsd-hardware.info/?probe=89bb299f1e) | Sep 22, 2020 |
| Foxconn       | Napa HP P/N                 | Desktop     | [2a7cb7b214](https://bsd-hardware.info/?probe=2a7cb7b214) | Sep 03, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [4d1897ed1f](https://bsd-hardware.info/?probe=4d1897ed1f) | Aug 29, 2020 |
| ASUSTek       | EMERY                       | Desktop     | [c93b86b3ba](https://bsd-hardware.info/?probe=c93b86b3ba) | Aug 27, 2020 |
| Lenovo        | ThinkPad T460 20FMS78014    | Notebook    | [d78837860f](https://bsd-hardware.info/?probe=d78837860f) | Aug 23, 2020 |
| ASUSTek       | V241ICR-R                   | All in one  | [f21adeb92c](https://bsd-hardware.info/?probe=f21adeb92c) | Aug 20, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [5ef34cd40f](https://bsd-hardware.info/?probe=5ef34cd40f) | Aug 20, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [6ca9384f34](https://bsd-hardware.info/?probe=6ca9384f34) | Aug 20, 2020 |
| HP            | 0A64h                       | Desktop     | [10c48336b0](https://bsd-hardware.info/?probe=10c48336b0) | Aug 20, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [78d714a1a3](https://bsd-hardware.info/?probe=78d714a1a3) | Aug 19, 2020 |
| ASUSTek       | X71SL                       | Notebook    | [a2ee0c9edb](https://bsd-hardware.info/?probe=a2ee0c9edb) | Aug 15, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [4b7eaf5a6a](https://bsd-hardware.info/?probe=4b7eaf5a6a) | Aug 12, 2020 |
| Dell          | Latitude 5480               | Notebook    | [907e0da9a4](https://bsd-hardware.info/?probe=907e0da9a4) | Aug 08, 2020 |
| HP            | EliteBook 820 G1            | Notebook    | [12ac8fc96f](https://bsd-hardware.info/?probe=12ac8fc96f) | Aug 07, 2020 |
| Google        | Lulu                        | Notebook    | [64aef60e6b](https://bsd-hardware.info/?probe=64aef60e6b) | Aug 02, 2020 |
| Lenovo        | ThinkPad T490s 20NX000DR... | Notebook    | [0919d8936f](https://bsd-hardware.info/?probe=0919d8936f) | Jul 27, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [15e87049a7](https://bsd-hardware.info/?probe=15e87049a7) | Jul 27, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8a3cb911c3](https://bsd-hardware.info/?probe=8a3cb911c3) | Jul 18, 2020 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 47        | 90.38%  |
| i386  | 5         | 9.62%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Openbox | 48        | 90.57%  |
| KDE5    | 2         | 3.77%   |
| GNUstep | 1         | 1.89%   |
| GNOME   | 1         | 1.89%   |
| filer   | 1         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 52        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 51        | 98.08%  |
| SDDM | 1         | 1.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 18        | 33.96%  |
| Unknown | 16        | 30.19%  |
| hu_HU   | 5         | 9.43%   |
| ru_RU   | 3         | 5.66%   |
| en_GB   | 3         | 5.66%   |
| it_IT   | 2         | 3.77%   |
| es_ES   | 2         | 3.77%   |
| de_DE   | 2         | 3.77%   |
| tr_TR   | 1         | 1.89%   |
| cs_CZ   | 1         | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 47        | 90.38%  |
| BIOS | 5         | 9.62%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Ufs  | 48        | 92.31%  |
| Zfs  | 4         | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 32        | 61.54%  |
| MBR  | 20        | 38.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 10        | 19.23%  |
| Dell                | 9         | 17.31%  |
| ASUSTek Computer    | 8         | 15.38%  |
| Hewlett-Packard     | 7         | 13.46%  |
| Acer                | 4         | 7.69%   |
| Apple               | 3         | 5.77%   |
| Google              | 2         | 3.85%   |
| Gigabyte Technology | 2         | 3.85%   |
| Sony                | 1         | 1.92%   |
| Samsung Electronics | 1         | 1.92%   |
| Pegatron            | 1         | 1.92%   |
| NEC Computers       | 1         | 1.92%   |
| IBM                 | 1         | 1.92%   |
| Foxconn             | 1         | 1.92%   |
| ASRock              | 1         | 1.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Sony VPCM13M1R                           | 1         | 1.92%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV  | 1         | 1.92%   |
| Pegatron Elite 7300 Series MT            | 1         | 1.92%   |
| NEC Computers PC-GL186Y3AZ               | 1         | 1.92%   |
| Lenovo ThinkPad X201 Tablet 311396U      | 1         | 1.92%   |
| Lenovo ThinkPad X1 Yoga 3rd 20LDS1CG00   | 1         | 1.92%   |
| Lenovo ThinkPad T530 24295VU             | 1         | 1.92%   |
| Lenovo ThinkPad T490s 20NX000DRT         | 1         | 1.92%   |
| Lenovo ThinkPad T490 20RYS06R00          | 1         | 1.92%   |
| Lenovo ThinkPad T460 20FMS78014          | 1         | 1.92%   |
| Lenovo ThinkPad T430 2347C32             | 1         | 1.92%   |
| Lenovo IdeaPad S145-15API 81UT           | 1         | 1.92%   |
| Lenovo G570 20079                        | 1         | 1.92%   |
| Lenovo G50-45 80E3                       | 1         | 1.92%   |
| IBM 2647NG8                              | 1         | 1.92%   |
| HP Spectre x360 Convertible 13-w0XX      | 1         | 1.92%   |
| HP ProBook 640 G1                        | 1         | 1.92%   |
| HP EliteBook 820 G1                      | 1         | 1.92%   |
| HP Compaq Elite 8300 Touch All-in-One PC | 1         | 1.92%   |
| HP Compaq dc7900 Convertible Minitower   | 1         | 1.92%   |
| HP Compaq dc7800p Convertible Minitower  | 1         | 1.92%   |
| HP Compaq dc5750 Microtower              | 1         | 1.92%   |
| Google Lulu                              | 1         | 1.92%   |
| Google Chell                             | 1         | 1.92%   |
| Gigabyte X570 AORUS PRO                  | 1         | 1.92%   |
| Gigabyte X570 AORUS MASTER               | 1         | 1.92%   |
| Foxconn Napa                             | 1         | 1.92%   |
| Dell Precision 7530                      | 1         | 1.92%   |
| Dell OptiPlex 780                        | 1         | 1.92%   |
| Dell OptiPlex 5260 AIO                   | 1         | 1.92%   |
| Dell Latitude 5490                       | 1         | 1.92%   |
| Dell Latitude 5480                       | 1         | 1.92%   |
| Dell Latitude 5400                       | 1         | 1.92%   |
| Dell Latitude 3410                       | 1         | 1.92%   |
| Dell Inspiron 5567                       | 1         | 1.92%   |
| Dell Inspiron 15-3567                    | 1         | 1.92%   |
| ASUS Z170-A                              | 1         | 1.92%   |
| ASUS X751LN                              | 1         | 1.92%   |
| ASUS X71SL                               | 1         | 1.92%   |
| ASUS V241ICR-R                           | 1         | 1.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 7         | 13.46%  |
| HP Compaq                  | 4         | 7.69%   |
| Dell Latitude              | 4         | 7.69%   |
| Acer Aspire                | 4         | 7.69%   |
| Gigabyte X570              | 2         | 3.85%   |
| Dell OptiPlex              | 2         | 3.85%   |
| Dell Inspiron              | 2         | 3.85%   |
| Sony VPCM13M1R             | 1         | 1.92%   |
| Samsung 300E5EV            | 1         | 1.92%   |
| Pegatron Elite             | 1         | 1.92%   |
| NEC Computers PC-GL186Y3AZ | 1         | 1.92%   |
| Lenovo IdeaPad             | 1         | 1.92%   |
| Lenovo G570                | 1         | 1.92%   |
| Lenovo G50-45              | 1         | 1.92%   |
| IBM 2647NG8                | 1         | 1.92%   |
| HP Spectre                 | 1         | 1.92%   |
| HP ProBook                 | 1         | 1.92%   |
| HP EliteBook               | 1         | 1.92%   |
| Google Lulu                | 1         | 1.92%   |
| Google Chell               | 1         | 1.92%   |
| Foxconn Napa               | 1         | 1.92%   |
| Dell Precision             | 1         | 1.92%   |
| ASUS Z170-A                | 1         | 1.92%   |
| ASUS X751LN                | 1         | 1.92%   |
| ASUS X71SL                 | 1         | 1.92%   |
| ASUS V241ICR-R             | 1         | 1.92%   |
| ASUS PRIME                 | 1         | 1.92%   |
| ASUS N75SF                 | 1         | 1.92%   |
| ASUS M5A97                 | 1         | 1.92%   |
| ASUS ER904AA-ABA           | 1         | 1.92%   |
| ASRock AB350               | 1         | 1.92%   |
| Apple MacBookPro8          | 1         | 1.92%   |
| Apple MacBookPro11         | 1         | 1.92%   |
| Apple MacBookAir7          | 1         | 1.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 11        | 21.15%  |
| 2019 | 6         | 11.54%  |
| 2016 | 4         | 7.69%   |
| 2014 | 4         | 7.69%   |
| 2013 | 4         | 7.69%   |
| 2018 | 3         | 5.77%   |
| 2017 | 3         | 5.77%   |
| 2015 | 3         | 5.77%   |
| 2011 | 3         | 5.77%   |
| 2008 | 3         | 5.77%   |
| 2010 | 2         | 3.85%   |
| 2009 | 2         | 3.85%   |
| 2012 | 1         | 1.92%   |
| 2007 | 1         | 1.92%   |
| 2006 | 1         | 1.92%   |
| 2004 | 1         | 1.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 34        | 65.38%  |
| Desktop     | 14        | 26.92%  |
| Convertible | 2         | 3.85%   |
| All in one  | 2         | 3.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 50        | 96.15%  |
| Yes  | 2         | 3.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 17        | 32.69%  |
| 4.01-8.0    | 15        | 28.85%  |
| 16.01-24.0  | 12        | 23.08%  |
| 32.01-64.0  | 2         | 3.85%   |
| 3.01-4.0    | 2         | 3.85%   |
| 0.51-1.0    | 2         | 3.85%   |
| 2.01-3.0    | 1         | 1.92%   |
| 64.01-256.0 | 1         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 30        | 57.69%  |
| 0.51-1.0  | 16        | 30.77%  |
| 2.01-3.0  | 3         | 5.77%   |
| 4.01-8.0  | 1         | 1.92%   |
| 1.01-2.0  | 1         | 1.92%   |
| 8.01-16.0 | 1         | 1.92%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 34        | 65.38%  |
| 2      | 11        | 21.15%  |
| 0      | 5         | 9.62%   |
| 3      | 2         | 3.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 62.26%  |
| Yes       | 20        | 37.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 88.46%  |
| No        | 6         | 11.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 75%     |
| No        | 13        | 25%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 61.54%  |
| No        | 20        | 38.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 10        | 19.23%  |
| France      | 10        | 19.23%  |
| Russia      | 9         | 17.31%  |
| Hungary     | 5         | 9.62%   |
| UK          | 3         | 5.77%   |
| Colombia    | 3         | 5.77%   |
| Italy       | 2         | 3.85%   |
| Germany     | 2         | 3.85%   |
| Argentina   | 2         | 3.85%   |
| Turkey      | 1         | 1.92%   |
| Serbia      | 1         | 1.92%   |
| Philippines | 1         | 1.92%   |
| Norway      | 1         | 1.92%   |
| Hong Kong   | 1         | 1.92%   |
| Czechia     | 1         | 1.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Moscow           | 6         | 11.32%  |
| Paris            | 5         | 9.43%   |
| Hodmezovasarhely | 5         | 9.43%   |
| Franconville     | 4         | 7.55%   |
| Woodland         | 2         | 3.77%   |
| St Petersburg    | 2         | 3.77%   |
| Rome             | 2         | 3.77%   |
| New Braunfels    | 2         | 3.77%   |
| Los Angeles      | 2         | 3.77%   |
| BogotГЎ        | 2         | 3.77%   |
| Wissen           | 1         | 1.89%   |
| Vladimir         | 1         | 1.89%   |
| Swindon          | 1         | 1.89%   |
| Southampton      | 1         | 1.89%   |
| Saint-Denis      | 1         | 1.89%   |
| Rionegro         | 1         | 1.89%   |
| Peoria           | 1         | 1.89%   |
| Pasig            | 1         | 1.89%   |
| Oslo             | 1         | 1.89%   |
| Nueve de Julio   | 1         | 1.89%   |
| Malton           | 1         | 1.89%   |
| London           | 1         | 1.89%   |
| Langen           | 1         | 1.89%   |
| Kowloon          | 1         | 1.89%   |
| Hranice          | 1         | 1.89%   |
| Duncan           | 1         | 1.89%   |
| CГіrdoba       | 1         | 1.89%   |
| Berkeley         | 1         | 1.89%   |
| Belgrade         | 1         | 1.89%   |
| BalД±kesir     | 1         | 1.89%   |
| Atlanta          | 1         | 1.89%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 14     | 21.05%  |
| Seagate             | 9         | 10     | 15.79%  |
| Toshiba             | 7         | 7      | 12.28%  |
| WDC                 | 6         | 8      | 10.53%  |
| Hitachi             | 4         | 4      | 7.02%   |
| SanDisk             | 3         | 4      | 5.26%   |
| Apple               | 3         | 4      | 5.26%   |
| SK hynix            | 2         | 2      | 3.51%   |
| OCZ                 | 2         | 2      | 3.51%   |
| ORICO               | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| Kingston            | 1         | 1      | 1.75%   |
| KingDian            | 1         | 1      | 1.75%   |
| Intel               | 1         | 1      | 1.75%   |
| HGST                | 1         | 1      | 1.75%   |
| Gigabyte Technology | 1         | 1      | 1.75%   |
| Fujitsu             | 1         | 1      | 1.75%   |
| Crucial             | 1         | 1      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 2         | 3.39%   |
| SanDisk pSSD 256GB                        | 2         | 3.39%   |
| Samsung MZVLB256HBHQ-000L7 256GB          | 2         | 3.39%   |
| WDC WD2500LPCX-24C6HT0 250GB              | 1         | 1.69%   |
| WDC WD2004FBYZ-01YCBB1 2TB                | 1         | 1.69%   |
| WDC WD10SPZX-00Z10T0 1TB                  | 1         | 1.69%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 1.69%   |
| WDC WD10EZRZ-00HTKB0 1TB                  | 1         | 1.69%   |
| WDC WD10EZRX-00L4HB0 1TB                  | 1         | 1.69%   |
| WDC WD10EFRX-68PJCN0 1TB                  | 1         | 1.69%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.69%   |
| Toshiba MK7575GSX 752GB                   | 1         | 1.69%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB       | 1         | 1.69%   |
| Toshiba DT01ACA100 1TB                    | 1         | 1.69%   |
| Toshiba DT01ABA300 3TB                    | 1         | 1.69%   |
| SK hynix SKHynix_HFS512GD9TNG-L5B0B 512GB | 1         | 1.69%   |
| SK hynix HFS128G39TND-N210A 128GB         | 1         | 1.69%   |
| Seagate ST9750423AS 752GB                 | 1         | 1.69%   |
| Seagate ST500LM021-1KJ152 500GB           | 1         | 1.69%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1.69%   |
| Seagate ST3500418AS 500GB                 | 1         | 1.69%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 1.69%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 1.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.69%   |
| Seagate ST1000DM003-1CH162 1TB            | 1         | 1.69%   |
| SanDisk SSD PLUS 120GB                    | 1         | 1.69%   |
| Samsung SSD 970 PRO 1TB                   | 1         | 1.69%   |
| Samsung SSD 970 EVO Plus 500GB            | 1         | 1.69%   |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 1.69%   |
| Samsung SSD 970 EVO 500GB                 | 1         | 1.69%   |
| Samsung SSD 850 EVO M.2 500GB             | 1         | 1.69%   |
| Samsung SSD 840 EVO 250GB                 | 1         | 1.69%   |
| Samsung SP2504C 250GB                     | 1         | 1.69%   |
| Samsung PM981 NVMe 256GB                  | 1         | 1.69%   |
| Samsung MZVLW512HMJP-000H1 512GB          | 1         | 1.69%   |
| Samsung MZMTD256HAGM-000L1 256GB          | 1         | 1.69%   |
| Samsung HD161HJ 160GB                     | 1         | 1.69%   |
| ORICO V500 1TB                            | 1         | 1.69%   |
| OCZ TRION150 240GB                        | 1         | 1.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 10     | 31.03%  |
| WDC                 | 6         | 8      | 20.69%  |
| Toshiba             | 6         | 6      | 20.69%  |
| Hitachi             | 4         | 4      | 13.79%  |
| Samsung Electronics | 2         | 2      | 6.9%    |
| HGST                | 1         | 1      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 4      | 15.79%  |
| Samsung Electronics | 3         | 3      | 15.79%  |
| Apple               | 3         | 4      | 15.79%  |
| OCZ                 | 2         | 2      | 10.53%  |
| Toshiba             | 1         | 1      | 5.26%   |
| SK hynix            | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| Kingston            | 1         | 1      | 5.26%   |
| KingDian            | 1         | 1      | 5.26%   |
| Intel               | 1         | 1      | 5.26%   |
| Gigabyte Technology | 1         | 1      | 5.26%   |
| Crucial             | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 32     | 50%     |
| SSD  | 18        | 21     | 33.33%  |
| NVMe | 9         | 11     | 16.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 53     | 82%     |
| NVMe | 9         | 11     | 18%     |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 29        | 33     | 63.04%  |
| 0.51-1.0   | 14        | 17     | 30.43%  |
| 1.01-2.0   | 2         | 2      | 4.35%   |
| 2.01-3.0   | 1         | 1      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 45        | 86.54%  |
| 101-250    | 4         | 7.69%   |
| 51-100     | 2         | 3.85%   |
| 501-1000   | 1         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 51        | 96.23%  |
| 21-50   | 2         | 3.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD10EFRX-68PJCN0 1TB                   | 1         | 2      | 11.11%  |
| Toshiba MQ01ABF050 500GB                   | 1         | 1      | 11.11%  |
| Toshiba MQ01ABD100 1TB                     | 1         | 1      | 11.11%  |
| Toshiba MK7575GSX 752GB                    | 1         | 1      | 11.11%  |
| Toshiba DT01ABA300 3TB                     | 1         | 1      | 11.11%  |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 11.11%  |
| Seagate ST500DM002-1BD142 500GB            | 1         | 1      | 11.11%  |
| Micron Technology MTFDDAK256MAM-1K12 256GB | 1         | 1      | 11.11%  |
| Hitachi HTS545032B9A302 320GB              | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 4         | 4      | 44.44%  |
| Seagate           | 2         | 2      | 22.22%  |
| WDC               | 1         | 2      | 11.11%  |
| Micron Technology | 1         | 1      | 11.11%  |
| Hitachi           | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 50%     |
| Seagate | 2         | 2      | 25%     |
| WDC     | 1         | 2      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 88.89%  |
| SSD  | 1         | 1      | 11.11%  |

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


| Status  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 41        | 54     | 82%     |
| Malfunc | 9         | 10     | 18%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 34        | 59.65%  |
| Samsung Electronics              | 10        | 17.54%  |
| AMD                              | 8         | 14.04%  |
| SK hynix                         | 1         | 1.75%   |
| Silicon Motion                   | 1         | 1.75%   |
| Silicon Integrated Systems [SiS] | 1         | 1.75%   |
| Nvidia                           | 1         | 1.75%   |
| ASMedia Technology               | 1         | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 8.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 8.7%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 8.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 4.35%   |
| Samsung SM951 AHCI                                                               | 2         | 2.9%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                             | 2         | 2.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 2.9%    |
| Intel 4 Series Chipset PT IDER Controller                                        | 2         | 2.9%    |
| SK hynix hynix unknown                                                           | 1         | 1.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.45%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 1.45%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 1.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.45%   |
| Samsung Apple PCIe SSD                                                           | 1         | 1.45%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                          | 1         | 1.45%   |
| Nvidia MCP73 IDE Controller                                                      | 1         | 1.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.45%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 1.45%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                             | 1         | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.45%   |
| Intel 82Q35 Express PT IDER Controller                                           | 1         | 1.45%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 1         | 1.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 1.45%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 1         | 1.45%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                     | 1         | 1.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.45%   |
| Intel 82801CAM IDE U100 Controller                                               | 1         | 1.45%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]    | 1         | 1.45%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile       | 1         | 1.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 1         | 1.45%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 1.45%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.45%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 1         | 1.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 31        | 53.45%  |
| IDE  | 12        | 20.69%  |
| NVMe | 9         | 15.52%  |
| RAID | 6         | 10.34%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 44        | 84.62%  |
| AMD    | 8         | 15.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 3.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz    | 2         | 3.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz    | 2         | 3.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 2         | 3.85%   |
| Intel Pentium III                    | 1         | 1.92%   |
| Intel Pentium D CPU 2.80GHz          | 1         | 1.92%   |
| Intel Pentium CPU N3700 @ 1.60GHz    | 1         | 1.92%   |
| Intel Pentium CPU 2117U @ 1.80GHz    | 1         | 1.92%   |
| Intel CPU Version                    | 1         | 1.92%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz     | 1         | 1.92%   |
| Intel Core i9-8950HK CPU @ 2.90GHz   | 1         | 1.92%   |
| Intel Core i7-8700 CPU @ 3.20GHz     | 1         | 1.92%   |
| Intel Core i7-8665U CPU @ 1.90GHz    | 1         | 1.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz    | 1         | 1.92%   |
| Intel Core i7-6700 CPU @ 3.40GHz     | 1         | 1.92%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz   | 1         | 1.92%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz   | 1         | 1.92%   |
| Intel Core i7-4600U CPU @ 2.10GHz    | 1         | 1.92%   |
| Intel Core i7-4510U CPU @ 2.00GHz    | 1         | 1.92%   |
| Intel Core i7-4500U CPU              | 1         | 1.92%   |
| Intel Core i7-2630QM CPU @ 2.00GHz   | 1         | 1.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz   | 1         | 1.92%   |
| Intel Core i7 CPU L 640 @ 2.13GHz    | 1         | 1.92%   |
| Intel Core i5-8350U CPU @ 1.70GHz    | 1         | 1.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz    | 1         | 1.92%   |
| Intel Core i5-5350U CPU @ 1.80GHz    | 1         | 1.92%   |
| Intel Core i5-4310M CPU @ 2.70GHz    | 1         | 1.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz     | 1         | 1.92%   |
| Intel Core i5-2500 CPU @ 3.30GHz     | 1         | 1.92%   |
| Intel Core i5-2430M CPU @ 2.40GHz    | 1         | 1.92%   |
| Intel Core i5-10310U CPU @ 1.70GHz   | 1         | 1.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz   | 1         | 1.92%   |
| Intel Core i3-6006U CPU @ 2.00GHz    | 1         | 1.92%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz | 1         | 1.92%   |
| Intel Core 2 Duo CPU E8600 @ 3.33GHz | 1         | 1.92%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz | 1         | 1.92%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz | 1         | 1.92%   |
| Intel Core 2 Duo                     | 1         | 1.92%   |
| Intel Celeron CPU 3215U @ 1.70GHz    | 1         | 1.92%   |
| Intel Atom CPU N470 @ 1.83GHz        | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 17        | 32.69%  |
| Intel Core i7     | 12        | 23.08%  |
| Intel Core 2 Duo  | 5         | 9.62%   |
| AMD Ryzen 5       | 3         | 5.77%   |
| Intel Pentium     | 2         | 3.85%   |
| Other             | 1         | 1.92%   |
| Intel Pentium III | 1         | 1.92%   |
| Intel Pentium D   | 1         | 1.92%   |
| Intel Core m5     | 1         | 1.92%   |
| Intel Core i9     | 1         | 1.92%   |
| Intel Core i3     | 1         | 1.92%   |
| Intel Celeron     | 1         | 1.92%   |
| Intel Atom        | 1         | 1.92%   |
| AMD Ryzen 7       | 1         | 1.92%   |
| AMD FX            | 1         | 1.92%   |
| AMD E1            | 1         | 1.92%   |
| AMD Athlon 64 X2  | 1         | 1.92%   |
| AMD A6            | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 25        | 48.08%  |
| 4       | 16        | 30.77%  |
| 6       | 3         | 5.77%   |
| Unknown | 3         | 5.77%   |
| 8       | 2         | 3.85%   |
| 16      | 1         | 1.92%   |
| 12      | 1         | 1.92%   |
| 1       | 1         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 51        | 98.08%  |
| 2      | 1         | 1.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 30        | 57.69%  |
| 1       | 18        | 34.62%  |
| Unknown | 4         | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 12        | 23.08%  |
| Skylake     | 6         | 11.54%  |
| Haswell     | 6         | 11.54%  |
| Penryn      | 5         | 9.62%   |
| IvyBridge   | 4         | 7.69%   |
| SandyBridge | 3         | 5.77%   |
| Zen+        | 2         | 3.85%   |
| Zen         | 2         | 3.85%   |
| Broadwell   | 2         | 3.85%   |
| Westmere    | 1         | 1.92%   |
| Silvermont  | 1         | 1.92%   |
| Puma        | 1         | 1.92%   |
| Piledriver  | 1         | 1.92%   |
| P6          | 1         | 1.92%   |
| NetBurst    | 1         | 1.92%   |
| K8 Hammer   | 1         | 1.92%   |
| Jaguar      | 1         | 1.92%   |
| Core        | 1         | 1.92%   |
| Bonnell     | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Intel       | 35        | 62.5%   |
| Nvidia      | 11        | 19.64%  |
| AMD         | 9         | 16.07%  |
| S3 Graphics | 1         | 1.79%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 6.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 6.9%    |
| Intel UHD Graphics 620                                                                   | 3         | 5.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 5.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 5.17%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 3.45%   |
| Intel HD Graphics 620                                                                    | 2         | 3.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 3.45%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 3.45%   |
| S3 Graphics SuperSavage IX/C SDR                                                         | 1         | 1.72%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 1.72%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 1.72%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 1.72%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 1         | 1.72%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.72%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 1.72%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 1.72%   |
| Nvidia G98M [GeForce 9300M GS]                                                           | 1         | 1.72%   |
| Nvidia G72 [GeForce 7300 LE]                                                             | 1         | 1.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.72%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.72%   |
| Intel HD Graphics 530                                                                    | 1         | 1.72%   |
| Intel HD Graphics 515                                                                    | 1         | 1.72%   |
| Intel HD Graphics                                                                        | 1         | 1.72%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.72%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 1         | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 1.72%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 1.72%   |
| AMD RV620 PRO [Radeon HD 3470]                                                           | 1         | 1.72%   |
| AMD RS482/RS485 [Radeon Xpress 1100/1150]                                                | 1         | 1.72%   |
| AMD RS480 [Radeon Xpress 1150] (Secondary)                                               | 1         | 1.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.72%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 29        | 55.77%  |
| 1 x Nvidia      | 7         | 13.46%  |
| 1 x AMD         | 7         | 13.46%  |
| Intel + Nvidia  | 4         | 7.69%   |
| 2 x Intel       | 2         | 3.85%   |
| 2 x AMD         | 1         | 1.92%   |
| 1 x S3 Graphics | 1         | 1.92%   |
| Intel + AMD     | 1         | 1.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 37        | 71.15%  |
| Unknown     | 9         | 17.31%  |
| Proprietary | 6         | 11.54%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 78.85%  |
| 1.01-2.0   | 5         | 9.62%   |
| 0.01-0.5   | 4         | 7.69%   |
| 5.01-6.0   | 2         | 3.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 6         | 13.04%  |
| Chimei Innolux          | 6         | 13.04%  |
| BOE                     | 6         | 13.04%  |
| Samsung Electronics     | 4         | 8.7%    |
| LG Display              | 3         | 6.52%   |
| Hewlett-Packard         | 3         | 6.52%   |
| Chi Mei Optoelectronics | 3         | 6.52%   |
| Philips                 | 2         | 4.35%   |
| Lenovo                  | 2         | 4.35%   |
| HannStar                | 2         | 4.35%   |
| Apple                   | 2         | 4.35%   |
| Vizio                   | 1         | 2.17%   |
| ViewSonic               | 1         | 2.17%   |
| Sharp                   | 1         | 2.17%   |
| LG Philips              | 1         | 2.17%   |
| Goldstar                | 1         | 2.17%   |
| BenQ                    | 1         | 2.17%   |
| AU Optronics            | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0671 1366x768 340x190mm 15.3-inch                      | 2         | 4.17%   |
| Vizio SV370XVT VIZ0057 1920x1080 820x460mm 37.0-inch                      | 1         | 2.08%   |
| ViewSonic VX910 VSC3C19 1280x1024 380x300mm 19.1-inch                     | 1         | 2.08%   |
| Sharp LCD Monitor SHP140E 2560x1440 290x170mm 13.2-inch                   | 1         | 2.08%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 410x260mm 19.1-inch       | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 290x160mm 13.0-inch     | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 310x170mm 13.9-inch      | 1         | 2.08%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 290x160mm 13.0-inch     | 1         | 2.08%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                   | 1         | 2.08%   |
| Philips 170S PHL0856 1280x1024 340x270mm 17.1-inch                        | 1         | 2.08%   |
| LG Philips LCD Monitor LPLA101 1440x900 370x230mm 17.2-inch               | 1         | 2.08%   |
| LG Display LCD Monitor LGD6301 1366x768 340x190mm 15.3-inch               | 1         | 2.08%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch               | 1         | 2.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch               | 1         | 2.08%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                   | 1         | 2.08%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                   | 1         | 2.08%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 340x270mm 17.1-inch                | 1         | 2.08%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch               | 1         | 2.08%   |
| Hewlett-Packard HPQ 8300 AiO HWP4212 1920x1080 510x290mm 23.1-inch        | 1         | 2.08%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch                 | 1         | 2.08%   |
| HannStar LCD Monitor HSD0013 1280x1024 380x300mm 19.1-inch                | 1         | 2.08%   |
| Goldstar 22MP55 GSM5A26 1920x1080 480x270mm 21.7-inch                     | 1         | 2.08%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                         | 1         | 2.08%   |
| Dell U2414H DELA0A2 1920x1080 530x300mm 24.0-inch                         | 1         | 2.08%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                         | 1         | 2.08%   |
| Dell P1917S DELD091 1280x1024 380x300mm 19.1-inch                         | 1         | 2.08%   |
| Dell LCD Monitor DEL93F2 1920x1080 480x270mm 21.7-inch                    | 1         | 2.08%   |
| Dell E2014H DELD03B 1600x900 430x240mm 19.4-inch                          | 1         | 2.08%   |
| Dell E1715S DELD062 1280x1024 340x270mm 17.1-inch                         | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch           | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14E1 1920x1080 310x170mm 13.9-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch          | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch           | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 310x170mm 13.9-inch           | 1         | 2.08%   |
| Chimei Innolux LCD Monitor CMN1367 1920x1080 290x170mm 13.2-inch          | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 380x210mm 17.1-inch | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 2.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 350x190mm 15.7-inch  | 1         | 2.08%   |
| BOE LCD Monitor BOE0812 1920x1080 340x190mm 15.3-inch                     | 1         | 2.08%   |
| BOE LCD Monitor BOE07E8 1366x768 310x170mm 13.9-inch                      | 1         | 2.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 14        | 29.79%  |
| 1366x768 (WXGA)   | 13        | 27.66%  |
| 1280x1024 (SXGA)  | 7         | 14.89%  |
| 1600x900 (HD+)    | 3         | 6.38%   |
| 1440x900 (WXGA+)  | 3         | 6.38%   |
| 1280x800 (WXGA)   | 2         | 4.26%   |
| 3200x1800 (QHD+)  | 1         | 2.13%   |
| 2880x1800         | 1         | 2.13%   |
| 2560x1440 (QHD)   | 1         | 2.13%   |
| 1920x1200 (WUXGA) | 1         | 2.13%   |
| 1024x600          | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 13        | 27.66%  |
| 15     | 9         | 19.15%  |
| 17     | 8         | 17.02%  |
| 19     | 5         | 10.64%  |
| 24     | 3         | 6.38%   |
| 21     | 3         | 6.38%   |
| 12     | 3         | 6.38%   |
| 37     | 1         | 2.13%   |
| 23     | 1         | 2.13%   |
| 10     | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 42.55%  |
| 201-300     | 10        | 21.28%  |
| 351-400     | 7         | 14.89%  |
| 401-500     | 5         | 10.64%  |
| 501-600     | 4         | 8.51%   |
| 801-900     | 1         | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 33        | 71.74%  |
| 5/4   | 7         | 15.22%  |
| 16/10 | 5         | 10.87%  |
| 3/2   | 1         | 2.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 19.15%  |
| 201-250        | 6         | 12.77%  |
| 91-100         | 6         | 12.77%  |
| 151-200        | 5         | 10.64%  |
| 71-80          | 4         | 8.51%   |
| 141-150        | 4         | 8.51%   |
| 61-70          | 3         | 6.38%   |
| 121-130        | 3         | 6.38%   |
| 101-110        | 3         | 6.38%   |
| 41-50          | 1         | 2.13%   |
| 251-300        | 1         | 2.13%   |
| 131-140        | 1         | 2.13%   |
| 501-1000       | 1         | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 17        | 36.17%  |
| 51-100        | 16        | 34.04%  |
| 121-160       | 9         | 19.15%  |
| 161-240       | 4         | 8.51%   |
| More than 240 | 1         | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 40        | 76.92%  |
| 0     | 10        | 19.23%  |
| 2     | 2         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 31        | 44.93%  |
| Realtek Semiconductor            | 14        | 20.29%  |
| Qualcomm Atheros                 | 10        | 14.49%  |
| Broadcom                         | 5         | 7.25%   |
| Qualcomm                         | 2         | 2.9%    |
| Silicon Integrated Systems [SiS] | 1         | 1.45%   |
| Ralink                           | 1         | 1.45%   |
| Nvidia                           | 1         | 1.45%   |
| Mellanox Technologies            | 1         | 1.45%   |
| Marvell Technology Group         | 1         | 1.45%   |
| JMicron Technology               | 1         | 1.45%   |
| Fibocom                          | 1         | 1.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 10.87%  |
| Intel Wireless 8265 / 8275                                        | 4         | 4.35%   |
| Intel Wireless 7260                                               | 4         | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 3.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.17%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 2.17%   |
| Intel Wireless 8260                                               | 2         | 2.17%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.17%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 2.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 2.17%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 2.17%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 2.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 2.17%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.09%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 1         | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.09%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1         | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 1.09%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.09%   |
| Nvidia MCP73 Ethernet                                             | 1         | 1.09%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 1         | 1.09%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 1.09%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 1.09%   |
| Intel Wireless 7265                                               | 1         | 1.09%   |
| Intel Wireless 3165                                               | 1         | 1.09%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.09%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 1         | 1.09%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 1.09%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.09%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 56.41%  |
| Qualcomm Atheros      | 9         | 23.08%  |
| Broadcom              | 4         | 10.26%  |
| Realtek Semiconductor | 3         | 7.69%   |
| Ralink                | 1         | 2.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                          | 4         | 9.76%   |
| Intel Wireless 7260                                                 | 4         | 9.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 3         | 7.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 2         | 4.88%   |
| Intel Wireless 8260                                                 | 2         | 4.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                   | 2         | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 2         | 4.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                            | 2         | 4.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 2         | 4.88%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                     | 1         | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 1         | 2.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1         | 2.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                           | 1         | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 1         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 1         | 2.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 1         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 1         | 2.44%   |
| Intel Wireless 7265                                                 | 1         | 2.44%   |
| Intel Wireless 3165                                                 | 1         | 2.44%   |
| Intel Wi-Fi 6 AX200                                                 | 1         | 2.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection       | 1         | 2.44%   |
| Intel Centrino Wireless-N 6150                                      | 1         | 2.44%   |
| Intel Centrino WiMAX 6150                                           | 1         | 2.44%   |
| Intel Centrino Advanced-N 6200                                      | 1         | 2.44%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                         | 1         | 2.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 1         | 2.44%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 23        | 47.92%  |
| Realtek Semiconductor            | 14        | 29.17%  |
| Broadcom                         | 3         | 6.25%   |
| Qualcomm Atheros                 | 2         | 4.17%   |
| Qualcomm                         | 2         | 4.17%   |
| Silicon Integrated Systems [SiS] | 1         | 2.08%   |
| Nvidia                           | 1         | 2.08%   |
| Marvell Technology Group         | 1         | 2.08%   |
| JMicron Technology               | 1         | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 10        | 20.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 6.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 6.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 6.12%   |
| Qualcomm ALCATEL Composite RNDIS Interface                        | 2         | 4.08%   |
| Intel I211 Gigabit Network Connection                             | 2         | 4.08%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 4.08%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 4.08%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 4.08%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 2.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 2.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 2.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.04%   |
| Nvidia MCP73 Ethernet                                             | 1         | 2.04%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 2.04%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 2.04%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 2.04%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 2.04%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 2.04%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 2.04%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller        | 1         | 2.04%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.04%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 2.04%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2.04%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 45        | 52.94%  |
| WiFi     | 38        | 44.71%  |
| Unknown  | 2         | 2.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 42        | 58.33%  |
| WiFi     | 28        | 38.89%  |
| Unknown  | 2         | 2.78%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 31        | 59.62%  |
| 1     | 20        | 38.46%  |
| 4     | 1         | 1.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 52        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 51.61%  |
| Lite-On Technology              | 3         | 9.68%   |
| Broadcom                        | 3         | 9.68%   |
| Apple                           | 3         | 9.68%   |
| Qualcomm Atheros Communications | 2         | 6.45%   |
| IMC Networks                    | 2         | 6.45%   |
| Realtek Semiconductor           | 1         | 3.23%   |
| ASUSTek Computer                | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 11        | 35.48%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 6.45%   |
| Intel AX201 Bluetooth                                       | 2         | 6.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 6.45%   |
| Apple Bluetooth Host Controller                             | 2         | 6.45%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 3.23%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 3.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 3.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 3.23%   |
| Lite-On Bluetooth USB Module                                | 1         | 3.23%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 3.23%   |
| Intel AX200 Bluetooth                                       | 1         | 3.23%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.1                 | 1         | 3.23%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 3.23%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 1         | 3.23%   |
| ASUS BT-253 Bluetooth Adapter                               | 1         | 3.23%   |
| Apple Apple Broadcom Built-in Bluetooth                     | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 40        | 66.67%  |
| AMD                              | 10        | 16.67%  |
| Nvidia                           | 6         | 10%     |
| Silicon Integrated Systems [SiS] | 1         | 1.67%   |
| Realtek Semiconductor            | 1         | 1.67%   |
| C-Media Electronics              | 1         | 1.67%   |
| Blue Microphones                 | 1         | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 13.89%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 5.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 4.17%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 4.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 4.17%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 2.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 2.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 2.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 2.78%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.78%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 2.78%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 2.78%   |
| AMD FCH Azalia Controller                                                                         | 2         | 2.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 2.78%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 1.39%   |
| Realtek Semiconductor Realtek USB Audio                                                           | 1         | 1.39%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 1.39%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.39%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.39%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 1         | 1.39%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 1.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.39%   |
| C-Media Electronics Audio Adapter                                                                 | 1         | 1.39%   |
| Blue Microphones Yeti Stereo Microphone                                                           | 1         | 1.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.39%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.39%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 1.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 20.69%  |
| SK hynix            | 11        | 18.97%  |
| Micron Technology   | 11        | 18.97%  |
| Unknown             | 5         | 8.62%   |
| Kingston            | 5         | 8.62%   |
| Elpida              | 3         | 5.17%   |
| Corsair             | 3         | 5.17%   |
| G.Skill             | 2         | 3.45%   |
| Crucial             | 2         | 3.45%   |
| A-DATA Technology   | 2         | 3.45%   |
| Nanya Technology    | 1         | 1.72%   |
| Magnum Tech         | 1         | 1.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s        | 3         | 4.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 2         | 3.28%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 2         | 3.28%   |
| Micron RAM ITC 4096MB DIMM DDR3 1066MT/s                      | 2         | 3.28%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                     | 1         | 1.64%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                     | 1         | 1.64%   |
| Unknown RAM Module 512MB SODIMM SDRAM                         | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                        | 1         | 1.64%   |
| Unknown RAM Module 128MB SODIMM SDRAM                         | 1         | 1.64%   |
| Unknown RAM Module 1024MB SODIMM RAM                          | 1         | 1.64%   |
| Unknown RAM Module 1024MB DIMM DDR2 533MT/s                   | 1         | 1.64%   |
| SK hynix RAM HMT125U6AFP8C-G7 2048MB DIMM DDR3 1066MT/s       | 1         | 1.64%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s    | 1         | 1.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s        | 1         | 1.64%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 1         | 1.64%   |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4096MB SODIMM LPDDR3 1867MT/s | 1         | 1.64%   |
| SK hynix RAM H5TC8G63AMR-PBA 4096MB 1600MT/s                  | 1         | 1.64%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 1         | 1.64%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.64%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.64%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.64%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.64%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 1         | 1.64%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.64%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s        | 1         | 1.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.64%   |
| Nanya RAM NT1GT64U88D0BY-AD 1024MB DIMM DDR2 800MT/s          | 1         | 1.64%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.64%   |
| Micron RAM Module 8192MB SODIMM DDR3 1600MT/s                 | 1         | 1.64%   |
| Micron RAM 8HTF12864AZ-800H1 1GB DIMM DDR2 800MT/s            | 1         | 1.64%   |
| Micron RAM 4KTF25664HZ-1G6E1 2048MB DDR3 1600MT/s             | 1         | 1.64%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 1         | 1.64%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s          | 1         | 1.64%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s        | 1         | 1.64%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s           | 1         | 1.64%   |
| Kingston RAM KHYXPX-MIE 8GB SODIMM DDR4 2667MT/s              | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 23        | 45.1%   |
| DDR4    | 16        | 31.37%  |
| DDR2    | 6         | 11.76%  |
| SDRAM   | 2         | 3.92%   |
| LPDDR3  | 2         | 3.92%   |
| RAM     | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 68%     |
| DIMM         | 13        | 26%     |
| Unknown      | 2         | 4%      |
| Row Of Chips | 1         | 2%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 20        | 33.9%   |
| 8192  | 17        | 28.81%  |
| 2048  | 9         | 15.25%  |
| 1024  | 6         | 10.17%  |
| 16384 | 4         | 6.78%   |
| 32768 | 1         | 1.69%   |
| 512   | 1         | 1.69%   |
| 128   | 1         | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 32.08%  |
| 2400    | 7         | 13.21%  |
| 2667    | 6         | 11.32%  |
| 800     | 4         | 7.55%   |
| 1333    | 3         | 5.66%   |
| Unknown | 3         | 5.66%   |
| 3200    | 2         | 3.77%   |
| 1867    | 2         | 3.77%   |
| 1066    | 2         | 3.77%   |
| 667     | 2         | 3.77%   |
| 3600    | 1         | 1.89%   |
| 2133    | 1         | 1.89%   |
| 1334    | 1         | 1.89%   |
| 1067    | 1         | 1.89%   |
| 533     | 1         | 1.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Dymo-CoStar | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Dymo-CoStar DYMO LabelWriter 450 DUO | 1         | 100%    |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 8         | 25%     |
| Chicony Electronics                    | 7         | 21.88%  |
| Sunplus Innovation Technology          | 4         | 12.5%   |
| Suyin                                  | 3         | 9.38%   |
| Logitech                               | 2         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 6.25%   |
| Silicon Motion                         | 1         | 3.13%   |
| Novatek Microelectronics               | 1         | 3.13%   |
| Microdia                               | 1         | 3.13%   |
| Lite-On Technology                     | 1         | 3.13%   |
| Apple                                  | 1         | 3.13%   |
| Acer                                   | 1         | 3.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Sunplus Integrated_Webcam_HD                        | 3         | 9.09%   |
| Realtek Realtek USB2.0 PC Camera                    | 2         | 6.06%   |
| Realtek Lenovo EasyCamera                           | 2         | 6.06%   |
| Chicony Integrated Camera                           | 2         | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 6.06%   |
| Suyin HD WebCam                                     | 1         | 3.03%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 3.03%   |
| Suyin Acer Crystal Eye webcam                       | 1         | 3.03%   |
| Sunplus Asus Webcam                                 | 1         | 3.03%   |
| Silicon Motion Realtek USB2.0 PC Camera             | 1         | 3.03%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 3.03%   |
| Realtek USB Camera                                  | 1         | 3.03%   |
| Realtek Integrated_Webcam_HD                        | 1         | 3.03%   |
| Realtek HD Webcam - Realtek                         | 1         | 3.03%   |
| Novatek HP High Definition 2MP Webcam               | 1         | 3.03%   |
| Microdia Integrated_Webcam_HD                       | 1         | 3.03%   |
| Logitech Webcam C270                                | 1         | 3.03%   |
| Logitech HD Pro Webcam C920                         | 1         | 3.03%   |
| Lite-On Integrated Camera                           | 1         | 3.03%   |
| Chicony Thinkpad T430 camera                        | 1         | 3.03%   |
| Chicony Realtek DMFT - IR                           | 1         | 3.03%   |
| Chicony Lenovo EasyCamera                           | 1         | 3.03%   |
| Chicony Integrated Camera [ThinkPad]                | 1         | 3.03%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 3.03%   |
| Chicony HD WebCam                                   | 1         | 3.03%   |
| Apple FaceTime HD Camera                            | 1         | 3.03%   |
| Acer NEC HD WebCam                                  | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 50%     |
| Synaptics        | 2         | 33.33%  |
| Upek             | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 33.33%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 16.67%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 16.67%  |

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
| 2     | 18        | 33.96%  |
| 1     | 13        | 24.53%  |
| 0     | 10        | 18.87%  |
| 3     | 5         | 9.43%   |
| 4     | 4         | 7.55%   |
| 7     | 1         | 1.89%   |
| 6     | 1         | 1.89%   |
| 5     | 1         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 36        | 43.37%  |
| Net/wireless             | 13        | 15.66%  |
| Bluetooth                | 11        | 13.25%  |
| Card reader              | 8         | 9.64%   |
| Firewire controller      | 6         | 7.23%   |
| Fingerprint reader       | 6         | 7.23%   |
| Storage/raid             | 1         | 1.2%    |
| Sound                    | 1         | 1.2%    |
| Network                  | 1         | 1.2%    |

