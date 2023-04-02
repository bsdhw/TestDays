BSD in Austria - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for BSD in Austria.

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

Total: 42

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | [24544f4a94](https://bsd-hardware.info/?probe=24544f4a94) | Jan 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| Intel         | H81U                        | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Intel         | H81U                        | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Deciso        | NetBoard-A10                | [aefb2f4660](https://bsd-hardware.info/?probe=aefb2f4660) | Aug 24, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Fujitsu       | LIFEBOOK A555               | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| BESSTAR Te... | U820                        | [6f2aa2d02a](https://bsd-hardware.info/?probe=6f2aa2d02a) | May 07, 2022 |
| Lenovo        | ThinkPad T410 2537WEE       | [973ade9e4a](https://bsd-hardware.info/?probe=973ade9e4a) | Mar 07, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| Lenovo        | Y50-70 20378                | [1feb455e8c](https://bsd-hardware.info/?probe=1feb455e8c) | Jan 25, 2022 |
| Dell          | Precision 7530              | [498bfe852c](https://bsd-hardware.info/?probe=498bfe852c) | Jan 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| Unknown       | Unknown                     | [db4d12babd](https://bsd-hardware.info/?probe=db4d12babd) | Dec 23, 2021 |
| HP            | EliteBook Folio 9470m       | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| Unknown       | Unknown                     | [eab0d6c6d3](https://bsd-hardware.info/?probe=eab0d6c6d3) | Dec 12, 2021 |
| Unknown       | Unknown                     | [6d1fb7b4bb](https://bsd-hardware.info/?probe=6d1fb7b4bb) | Nov 27, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [087d40ba7c](https://bsd-hardware.info/?probe=087d40ba7c) | Oct 19, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [bf9b083102](https://bsd-hardware.info/?probe=bf9b083102) | Sep 08, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [62f9376847](https://bsd-hardware.info/?probe=62f9376847) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| HP            | EliteBook Folio 9470m       | [e1837571df](https://bsd-hardware.info/?probe=e1837571df) | Apr 15, 2021 |
| HP            | EliteBook Folio 9470m       | [57de8a523c](https://bsd-hardware.info/?probe=57de8a523c) | Mar 29, 2021 |
| Panasonic     | CF-30KTP48NL                | [119b4875e9](https://bsd-hardware.info/?probe=119b4875e9) | Mar 12, 2021 |
| Dell          | Vostro V131                 | [897616d9c8](https://bsd-hardware.info/?probe=897616d9c8) | Jan 31, 2021 |
| Dell          | Vostro V131                 | [630822a6a1](https://bsd-hardware.info/?probe=630822a6a1) | Jan 25, 2021 |
| HP            | ZBook 17 G4                 | [40ad0612de](https://bsd-hardware.info/?probe=40ad0612de) | Jan 02, 2021 |
| Lenovo        | ThinkPad T410 2537AT1       | [4e693bfcb2](https://bsd-hardware.info/?probe=4e693bfcb2) | Oct 29, 2020 |
| Dell          | Latitude E7440              | [acd2735dc4](https://bsd-hardware.info/?probe=acd2735dc4) | Aug 07, 2020 |
| HP            | EliteBook 840 G3            | [71c35a9cc2](https://bsd-hardware.info/?probe=71c35a9cc2) | Aug 06, 2020 |
| HP            | EliteBook 840 G3            | [6c7374d0ab](https://bsd-hardware.info/?probe=6c7374d0ab) | May 29, 2020 |
| Lenovo        | ThinkPad T60 2007J3G        | [ee60eb3dc8](https://bsd-hardware.info/?probe=ee60eb3dc8) | May 25, 2020 |
| Dell          | XPS 13 9360                 | [152f5cda4c](https://bsd-hardware.info/?probe=152f5cda4c) | May 23, 2020 |
| Dell          | XPS 13 9360                 | [d350b44569](https://bsd-hardware.info/?probe=d350b44569) | May 23, 2020 |
| Dell          | XPS 13 9360                 | [4199e37b56](https://bsd-hardware.info/?probe=4199e37b56) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| FreeBSD 13.1         | 4         | 12.5%   |
| FreeBSD 13.1-p5      | 3         | 9.38%   |
| OPNsense 21.7.7      | 2         | 6.25%   |
| FreeBSD 14.0-CURRENT | 2         | 6.25%   |
| FreeBSD 13.0-p4      | 2         | 6.25%   |
| FreeBSD 12.1-p8      | 2         | 6.25%   |
| FreeBSD 12.1-p5      | 2         | 6.25%   |
| OPNsense 22.7.9      | 1         | 3.13%   |
| OPNsense 22.4.3      | 1         | 3.13%   |
| OPNsense 22.1.6      | 1         | 3.13%   |
| OPNsense 22.1.2      | 1         | 3.13%   |
| OPNsense 21.7.6      | 1         | 3.13%   |
| OpenBSD 6.8          | 1         | 3.13%   |
| helloSystem 0.7.0    | 1         | 3.13%   |
| helloSystem 0.5.0    | 1         | 3.13%   |
| FreeBSD 13.0-CURRENT | 1         | 3.13%   |
| FreeBSD 13.0         | 1         | 3.13%   |
| FreeBSD 12.3         | 1         | 3.13%   |
| FreeBSD 12.2-p5      | 1         | 3.13%   |
| FreeBSD 12.2         | 1         | 3.13%   |
| FreeBSD 12.1-p4      | 1         | 3.13%   |
| FreeBSD 12.1-p10     | 1         | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 20        | 68.97%  |
| OPNsense    | 6         | 20.69%  |
| helloSystem | 2         | 6.9%    |
| OpenBSD     | 1         | 3.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 29        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| KDE5         | 8         | 26.67%  |
| Console      | 7         | 23.33%  |
| XFCE         | 3         | 10%     |
| Cinnamon     | 3         | 10%     |
| MATE         | 2         | 6.67%   |
| i3           | 2         | 6.67%   |
| helloDesktop | 2         | 6.67%   |
| LXQt         | 1         | 3.33%   |
| GNOME        | 1         | 3.33%   |
| fvwm         | 1         | 3.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 21        | 70%     |
| Console | 8         | 26.67%  |
| Wayland | 1         | 3.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 13        | 43.33%  |
| SDDM    | 11        | 36.67%  |
| SLiM    | 3         | 10%     |
| XDM     | 1         | 3.33%   |
| LightDM | 1         | 3.33%   |
| GDM     | 1         | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| C       | 11        | 35.48%  |
| Unknown | 11        | 35.48%  |
| en_US   | 5         | 16.13%  |
| cs_CZ   | 2         | 6.45%   |
| de_DE   | 1         | 3.23%   |
| de_AT   | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 25        | 86.21%  |
| BIOS | 4         | 13.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 20        | 68.97%  |
| Ufs  | 8         | 27.59%  |
| Ffs  | 1         | 3.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 27        | 93.1%   |
| MBR  | 2         | 6.9%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo          | 13        | 44.83%  |
| Hewlett-Packard | 5         | 17.24%  |
| Dell            | 4         | 13.79%  |
| TUXEDO          | 1         | 3.45%   |
| Panasonic       | 1         | 3.45%   |
| Intel           | 1         | 3.45%   |
| Fujitsu         | 1         | 3.45%   |
| Deciso          | 1         | 3.45%   |
| BESSTAR Tech    | 1         | 3.45%   |
| Unknown         | 1         | 3.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo ThinkPad T490 20N2CTO1WW      | 2         | 6.9%    |
| HP EliteBook 850 G7 Notebook PC      | 2         | 6.9%    |
| TUXEDO InfinityBook Pro 14 Gen6      | 1         | 3.45%   |
| Panasonic CF-30KTP48NL               | 1         | 3.45%   |
| Lenovo Y50-70 20378                  | 1         | 3.45%   |
| Lenovo ThinkPad X220 4291WF5         | 1         | 3.45%   |
| Lenovo ThinkPad T60 2007J3G          | 1         | 3.45%   |
| Lenovo ThinkPad T510 4384AJ6         | 1         | 3.45%   |
| Lenovo ThinkPad T410 2537WEE         | 1         | 3.45%   |
| Lenovo ThinkPad T410 2537AT1         | 1         | 3.45%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE | 1         | 3.45%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE | 1         | 3.45%   |
| Lenovo ThinkPad A485 20MVS0LG00      | 1         | 3.45%   |
| Lenovo IdeaPad 5 14ALC05 82LM        | 1         | 3.45%   |
| Lenovo IdeaPad 110S-11IBR 80WG       | 1         | 3.45%   |
| Intel H81U                           | 1         | 3.45%   |
| HP ZBook 17 G4                       | 1         | 3.45%   |
| HP EliteBook Folio 9470m             | 1         | 3.45%   |
| HP EliteBook 840 G3                  | 1         | 3.45%   |
| Fujitsu LIFEBOOK A555                | 1         | 3.45%   |
| Dell XPS 13 9360                     | 1         | 3.45%   |
| Dell Vostro V131                     | 1         | 3.45%   |
| Dell Precision 7530                  | 1         | 3.45%   |
| Dell Latitude E7440                  | 1         | 3.45%   |
| Deciso NetBoard-A10                  | 1         | 3.45%   |
| BESSTAR Tech U820                    | 1         | 3.45%   |
| Unknown                              | 1         | 3.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 10        | 34.48%  |
| HP EliteBook           | 4         | 13.79%  |
| Lenovo IdeaPad         | 2         | 6.9%    |
| TUXEDO InfinityBook    | 1         | 3.45%   |
| Panasonic CF-30KTP48NL | 1         | 3.45%   |
| Lenovo Y50-70          | 1         | 3.45%   |
| Intel H81U             | 1         | 3.45%   |
| HP ZBook               | 1         | 3.45%   |
| Fujitsu LIFEBOOK       | 1         | 3.45%   |
| Dell XPS               | 1         | 3.45%   |
| Dell Vostro            | 1         | 3.45%   |
| Dell Precision         | 1         | 3.45%   |
| Dell Latitude          | 1         | 3.45%   |
| Deciso NetBoard-A10    | 1         | 3.45%   |
| BESSTAR Tech U820      | 1         | 3.45%   |
| Unknown                | 1         | 3.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 6         | 20.69%  |
| 2022 | 4         | 13.79%  |
| 2021 | 4         | 13.79%  |
| 2018 | 3         | 10.34%  |
| 2010 | 3         | 10.34%  |
| 2017 | 2         | 6.9%    |
| 2011 | 2         | 6.9%    |
| 2020 | 1         | 3.45%   |
| 2016 | 1         | 3.45%   |
| 2015 | 1         | 3.45%   |
| 2009 | 1         | 3.45%   |
| 2006 | 1         | 3.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 29        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 29        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 11        | 37.93%  |
| 16.01-24.0  | 8         | 27.59%  |
| 32.01-64.0  | 4         | 13.79%  |
| 3.01-4.0    | 2         | 6.9%    |
| 2.01-3.0    | 2         | 6.9%    |
| 4.01-8.0    | 1         | 3.45%   |
| 64.01-256.0 | 1         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 12        | 41.38%  |
| 1.01-2.0 | 10        | 34.48%  |
| 0.51-1.0 | 5         | 17.24%  |
| 2.01-3.0 | 2         | 6.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 21        | 72.41%  |
| 2      | 3         | 10.34%  |
| 0      | 3         | 10.34%  |
| 3      | 2         | 6.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 96.55%  |
| Yes       | 1         | 3.45%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 75.86%  |
| No        | 7         | 24.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 93.1%   |
| No        | 2         | 6.9%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 76.67%  |
| No        | 7         | 23.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Austria | 29        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vienna           | 20        | 64.52%  |
| Graz             | 2         | 6.45%   |
| Wels             | 1         | 3.23%   |
| Weidlingbach     | 1         | 3.23%   |
| Vorchdorf        | 1         | 3.23%   |
| Parndorf         | 1         | 3.23%   |
| Maria Enzersdorf | 1         | 3.23%   |
| Linz             | 1         | 3.23%   |
| Innsbruck        | 1         | 3.23%   |
| Grosspertholz    | 1         | 3.23%   |
| Bruck an der Mur | 1         | 3.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 13     | 34.38%  |
| Intel               | 4         | 5      | 12.5%   |
| WDC                 | 3         | 3      | 9.38%   |
| Transcend           | 2         | 3      | 6.25%   |
| SK hynix            | 2         | 2      | 6.25%   |
| SanDisk             | 2         | 2      | 6.25%   |
| Kingston            | 2         | 5      | 6.25%   |
| Seagate             | 1         | 1      | 3.13%   |
| Intenso             | 1         | 1      | 3.13%   |
| Hitachi             | 1         | 1      | 3.13%   |
| HGST                | 1         | 1      | 3.13%   |
| Crucial             | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 2      | 3.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 5.88%   |
| Samsung MZALQ512HBLU-00BL1 512GB        | 2         | 5.88%   |
| Intel SSDPEKKF512G8L 512GB              | 2         | 5.88%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 2.94%   |
| WDC WD20SPZX-22CRAT0 2TB                | 1         | 2.94%   |
| WDC WD10JPLX-00MBPT0 1TB                | 1         | 2.94%   |
| Transcend TS2TMTE220S 2TB               | 1         | 2.94%   |
| Transcend TS256GMTE652T2 256GB          | 1         | 2.94%   |
| Seagate ST1000LX015-1U7172 1TB          | 1         | 2.94%   |
| SanDisk SSD PLUS 240GB                  | 1         | 2.94%   |
| SanDisk SD7TB3Q-128G-1006 128GB         | 1         | 2.94%   |
| Samsung SSD PM851 mSATA 256GB           | 1         | 2.94%   |
| Samsung SSD PM841 2.5-inch 7mm 256GB    | 1         | 2.94%   |
| Samsung SSD 980 500GB                   | 1         | 2.94%   |
| Samsung SSD 860 EVO 250GB               | 1         | 2.94%   |
| Samsung MZVLB256HAHQ-000L7 256GB        | 1         | 2.94%   |
| Samsung MZVKW512HMJP-000H1 512GB        | 1         | 2.94%   |
| Samsung MZALQ512HBLU-00BL2 512GB        | 1         | 2.94%   |
| Samsung MZ7TE512HMHP-000L2 512GB        | 1         | 2.94%   |
| Samsung HM320JI 320GB                   | 1         | 2.94%   |
| Kingston SUV500MS480G 480GB             | 1         | 2.94%   |
| Kingston SUV500MS120G 120GB             | 1         | 2.94%   |
| Kingston SKC600MS256G 256GB             | 1         | 2.94%   |
| Intenso JAJM600M256C 256GB              | 1         | 2.94%   |
| Intel SSDSCKKF256G8H 256GB              | 1         | 2.94%   |
| Intel SSDPEKNW020T8 2TB                 | 1         | 2.94%   |
| Hitachi HTS541040G9SA00 40GB            | 1         | 2.94%   |
| HGST HTS545050A7E680 500GB              | 1         | 2.94%   |
| Crucial CT275MX300SSD4 275GB            | 1         | 2.94%   |
| A-DATA SU650 240GB                      | 1         | 2.94%   |
| A-DATA SU630 240GB                      | 1         | 2.94%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 42.86%  |
| Seagate             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 33.33%  |
| SanDisk             | 2         | 2      | 16.67%  |
| Kingston            | 2         | 5      | 16.67%  |
| Intenso             | 1         | 1      | 8.33%   |
| Intel               | 1         | 2      | 8.33%   |
| Crucial             | 1         | 1      | 8.33%   |
| A-DATA Technology   | 1         | 2      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 12        | 16     | 41.38%  |
| SSD  | 11        | 17     | 37.93%  |
| HDD  | 6         | 7      | 20.69%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 14        | 24     | 53.85%  |
| NVMe | 12        | 16     | 46.15%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 12        | 20     | 75%     |
| 0.51-1.0   | 3         | 3      | 18.75%  |
| 1.01-2.0   | 1         | 1      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 12        | 41.38%  |
| 101-250    | 11        | 37.93%  |
| 21-50      | 2         | 6.9%    |
| 51-100     | 2         | 6.9%    |
| 1-20       | 1         | 3.45%   |
| 501-1000   | 1         | 3.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 24        | 80%     |
| 21-50   | 3         | 10%     |
| 251-500 | 1         | 3.33%   |
| 101-250 | 1         | 3.33%   |
| 51-100  | 1         | 3.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB   | 1         | 1      | 25%     |
| Intel SSDSCKKF256G8H 256GB    | 1         | 2      | 25%     |
| Hitachi HTS541040G9SA00 40GB  | 1         | 1      | 25%     |
| A-DATA Technology SU630 240GB | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 1         | 1      | 25%     |
| Intel             | 1         | 2      | 25%     |
| Hitachi           | 1         | 1      | 25%     |
| A-DATA Technology | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 3      | 50%     |
| HDD  | 2         | 2      | 50%     |

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


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 24        | 35     | 85.71%  |
| Malfunc | 4         | 5      | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 20        | 60.61%  |
| Samsung Electronics | 6         | 18.18%  |
| SK hynix            | 2         | 6.06%   |
| AMD                 | 2         | 6.06%   |
| Transcend           | 1         | 3.03%   |
| Toshiba             | 1         | 3.03%   |
| Silicon Motion      | 1         | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980                                                  | 4         | 10.81%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 8.11%   |
| SK hynix BC511                                                                   | 2         | 5.41%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 5.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 5.41%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 5.41%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 2.7%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 2.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 2.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 2.7%    |
| Intel SSD 660P Series                                                            | 1         | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 2.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 2.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 2.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.7%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.7%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 2.7%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 2.7%    |
| Unknown                                                                          | 1         | 2.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 17        | 50%     |
| NVMe | 13        | 38.24%  |
| IDE  | 4         | 11.76%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 82.76%  |
| AMD    | 5         | 17.24%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 10.34%  |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 6.9%    |
| Intel Core i5-10310U CPU @ 1.70GHz              | 2         | 6.9%    |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 2         | 6.9%    |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 3.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 3.45%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 3.45%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 3.45%   |
| Intel Core i5-8279U CPU @ 2.40GHz               | 1         | 3.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 3.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 3.45%   |
| Intel Core i5-4310U CPU @ 2.00GHz               | 1         | 3.45%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 3.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 3.45%   |
| Intel Core i5 CPU M 560 @ 2.67GHz               | 1         | 3.45%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 3.45%   |
| Intel Core 2 Duo CPU L9300 @ 1.60GHz            | 1         | 3.45%   |
| Intel Core 2 CPU                                | 1         | 3.45%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 3.45%   |
| Intel Celeron CPU 867 @ 1.30GHz                 | 1         | 3.45%   |
| Intel Celeron 2955U @ 1.40GHz                   | 1         | 3.45%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz         | 1         | 3.45%   |
| AMD Ryzen Embedded V1500B                       | 1         | 3.45%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1         | 3.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 11        | 37.93%  |
| Intel Core i7      | 6         | 20.69%  |
| Intel Celeron      | 3         | 10.34%  |
| AMD Ryzen 5        | 3         | 10.34%  |
| Other              | 1         | 3.45%   |
| Intel Core i3      | 1         | 3.45%   |
| Intel Core 2 Duo   | 1         | 3.45%   |
| Intel Core 2       | 1         | 3.45%   |
| AMD Ryzen Embedded | 1         | 3.45%   |
| AMD Ryzen 5 PRO    | 1         | 3.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 13        | 44.83%  |
| 4       | 8         | 27.59%  |
| 12      | 3         | 10.34%  |
| 8       | 2         | 6.9%    |
| Unknown | 2         | 6.9%    |
| 6       | 1         | 3.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 28        | 96.55%  |
| Unknown | 1         | 3.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 19        | 65.52%  |
| 1       | 8         | 27.59%  |
| Unknown | 2         | 6.9%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 8         | 27.59%  |
| Haswell     | 4         | 13.79%  |
| Westmere    | 3         | 10.34%  |
| Unknown     | 3         | 10.34%  |
| Zen         | 2         | 6.9%    |
| SandyBridge | 2         | 6.9%    |
| TigerLake   | 1         | 3.45%   |
| Skylake     | 1         | 3.45%   |
| Silvermont  | 1         | 3.45%   |
| Penryn      | 1         | 3.45%   |
| IvyBridge   | 1         | 3.45%   |
| Core        | 1         | 3.45%   |
| Broadwell   | 1         | 3.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 72.41%  |
| AMD    | 5         | 17.24%  |
| Nvidia | 3         | 10.34%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 10.34%  |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 10.34%  |
| AMD Lucienne                                                                             | 3         | 10.34%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 6.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 6.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 6.9%    |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 3.45%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 3.45%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 3.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 3.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 3.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 3.45%   |
| Intel HD Graphics 620                                                                    | 1         | 3.45%   |
| Intel HD Graphics 5500                                                                   | 1         | 3.45%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 3.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 3.45%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 3.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 3.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 19        | 65.52%  |
| 1 x AMD        | 5         | 17.24%  |
| 1 x Nvidia     | 2         | 6.9%    |
| Other          | 1         | 3.45%   |
| 2 x Intel      | 1         | 3.45%   |
| Intel + Nvidia | 1         | 3.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 26        | 89.66%  |
| Proprietary | 2         | 6.9%    |
| Unknown     | 1         | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 80.65%  |
| 0.51-1.0   | 2         | 6.45%   |
| 7.01-8.0   | 1         | 3.23%   |
| 3.01-4.0   | 1         | 3.23%   |
| 1.01-2.0   | 1         | 3.23%   |
| 0.01-0.5   | 1         | 3.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 25%     |
| LG Display          | 3         | 15%     |
| Lenovo              | 3         | 15%     |
| BOE                 | 3         | 15%     |
| Samsung Electronics | 2         | 10%     |
| Chimei Innolux      | 2         | 10%     |
| Unknown             | 1         | 5%      |
| Dell                | 1         | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C34J79x SAM0F1E 3440x1440 800x330mm 34.1-inch | 2         | 10%     |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch      | 2         | 10%     |
| AU Optronics LCD Monitor AUO2036 2560x1440 310x170mm 13.9-inch    | 2         | 10%     |
| Unknown LCD Monitor Sharp 3840x2160                               | 1         | 5%      |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch       | 1         | 5%      |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch           | 1         | 5%      |
| Lenovo LCD Monitor LEN4043 1400x1050 300x230mm 14.9-inch          | 1         | 5%      |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch           | 1         | 5%      |
| Dell P2719H DEL4185 1920x1080 600x340mm 27.2-inch                 | 1         | 5%      |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch   | 1         | 5%      |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch   | 1         | 5%      |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch             | 1         | 5%      |
| BOE LCD Monitor BOE0791 1920x1080 310x170mm 13.9-inch             | 1         | 5%      |
| BOE LCD Monitor BOE0714 1920x1080 310x170mm 13.9-inch             | 1         | 5%      |
| AU Optronics LCD Monitor AUO408D 1920x1080 310x170mm 13.9-inch    | 1         | 5%      |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch    | 1         | 5%      |
| AU Optronics LCD Monitor 1920x1080                                | 1         | 5%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 8         | 42.11%  |
| 1366x768 (WXGA)  | 3         | 15.79%  |
| 3440x1440        | 2         | 10.53%  |
| 2560x1440 (QHD)  | 2         | 10.53%  |
| 3840x2160 (4K)   | 1         | 5.26%   |
| 1600x900 (HD+)   | 1         | 5.26%   |
| 1440x900 (WXGA+) | 1         | 5.26%   |
| 1400x1050        | 1         | 5.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 8         | 40%     |
| 15      | 4         | 20%     |
| 34      | 2         | 10%     |
| 14      | 2         | 10%     |
| Unknown | 2         | 10%     |
| 27      | 1         | 5%      |
| 11      | 1         | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 60%     |
| 201-300     | 3         | 15%     |
| 701-800     | 2         | 10%     |
| Unknown     | 2         | 10%     |
| 501-600     | 1         | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 13        | 68.42%  |
| 21/9    | 2         | 10.53%  |
| Unknown | 2         | 10.53%  |
| 4/3     | 1         | 5.26%   |
| 16/10   | 1         | 5.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 9         | 45%     |
| 91-100         | 3         | 15%     |
| 351-500        | 2         | 10%     |
| 101-110        | 2         | 10%     |
| Unknown        | 2         | 10%     |
| 51-60          | 1         | 5%      |
| 301-350        | 1         | 5%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 10        | 50%     |
| 101-120 | 4         | 20%     |
| 161-240 | 2         | 10%     |
| 51-100  | 2         | 10%     |
| Unknown | 2         | 10%     |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 16        | 53.33%  |
| 0     | 11        | 36.67%  |
| 2     | 3         | 10%     |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 67.57%  |
| Realtek Semiconductor | 9         | 24.32%  |
| Hewlett-Packard       | 1         | 2.7%    |
| Dell                  | 1         | 2.7%    |
| AMD                   | 1         | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 12.96%  |
| Intel Wireless 7260                                               | 3         | 5.56%   |
| Intel I211 Gigabit Network Connection                             | 3         | 5.56%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 5.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 3.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 3.7%    |
| Intel Wireless-AC 9260                                            | 2         | 3.7%    |
| Intel Wireless 8265 / 8275                                        | 2         | 3.7%    |
| Intel Wireless 7265                                               | 2         | 3.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 3.7%    |
| Intel Centrino Ultimate-N 6300                                    | 2         | 3.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.85%   |
| Intel Wireless 8260                                               | 1         | 1.85%   |
| Intel WiFi Link 5100                                              | 1         | 1.85%   |
| Intel Wi-Fi 6 AX201                                               | 1         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 1         | 1.85%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.85%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.85%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.85%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.85%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 1         | 1.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 1         | 1.85%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 1.85%   |
| Intel Centrino Advanced-N 6200                                    | 1         | 1.85%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 1.85%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.85%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter           | 1         | 1.85%   |
| Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                | 1         | 1.85%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 1.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 82.14%  |
| Realtek Semiconductor | 4         | 14.29%  |
| Dell                  | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                      | 3         | 10.34%  |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter | 2         | 6.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter      | 2         | 6.9%    |
| Intel Wireless-AC 9260                                   | 2         | 6.9%    |
| Intel Wireless 8265 / 8275                               | 2         | 6.9%    |
| Intel Wireless 7265                                      | 2         | 6.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                        | 2         | 6.9%    |
| Intel Centrino Ultimate-N 6300                           | 2         | 6.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                 | 2         | 6.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter | 1         | 3.45%   |
| Intel Wireless 8260                                      | 1         | 3.45%   |
| Intel WiFi Link 5100                                     | 1         | 3.45%   |
| Intel Wi-Fi 6 AX201                                      | 1         | 3.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection    | 1         | 3.45%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]            | 1         | 3.45%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]             | 1         | 3.45%   |
| Intel Centrino Advanced-N 6235                           | 1         | 3.45%   |
| Intel Centrino Advanced-N 6200                           | 1         | 3.45%   |
| Dell Wireless 5550 HSPA+ Mini-Card Network Adapter       | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 66.67%  |
| Realtek Semiconductor | 7         | 29.17%  |
| AMD                   | 1         | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 29.17%  |
| Intel I211 Gigabit Network Connection                             | 3         | 12.5%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 8.33%   |
| Intel Ethernet Controller I225-V                                  | 1         | 4.17%   |
| Intel Ethernet Connection I219-V                                  | 1         | 4.17%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.17%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 4.17%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 4.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 4.17%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 4.17%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 4.17%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 27        | 54%     |
| Ethernet | 22        | 44%     |
| Modem    | 1         | 2%      |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 19        | 50%     |
| WiFi     | 18        | 47.37%  |
| Modem    | 1         | 2.63%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 17        | 58.62%  |
| 1     | 6         | 20.69%  |
| 3     | 3         | 10.34%  |
| 6     | 1         | 3.45%   |
| 5     | 1         | 3.45%   |
| 0     | 1         | 3.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 28        | 96.55%  |
| Yes  | 1         | 3.45%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 66.67%  |
| Broadcom              | 4         | 16.67%  |
| Realtek Semiconductor | 3         | 12.5%   |
| Alps Electric         | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 7         | 29.17%  |
| Realtek Bluetooth Adapter                        | 3         | 12.5%   |
| Intel AX201 Bluetooth                            | 3         | 12.5%   |
| Broadcom BCM2045B (BDC-2.1)                      | 3         | 12.5%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 2         | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 2         | 8.33%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 4.17%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 4.17%   |
| Broadcom BCM2035 Bluetooth dongle                | 1         | 4.17%   |
| Alps Electric UGTZ4 Bluetooth                    | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 24        | 72.73%  |
| AMD         | 5         | 15.15%  |
| Plantronics | 3         | 9.09%   |
| Nvidia      | 1         | 3.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 11.9%   |
| Plantronics Plantronics Blackwire 315.1                                                           | 3         | 7.14%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 7.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 7.14%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 7.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 7.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 7.14%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 4.76%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.76%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.38%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.38%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 39.39%  |
| SK hynix            | 6         | 18.18%  |
| Micron Technology   | 6         | 18.18%  |
| Kingston            | 3         | 9.09%   |
| Unknown             | 1         | 3.03%   |
| Transcend           | 1         | 3.03%   |
| Nanya Technology    | 1         | 3.03%   |
| Elpida              | 1         | 3.03%   |
| Corsair             | 1         | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                  | 2         | 5.56%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 2         | 5.56%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 5.56%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 5.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 5.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 2.78%   |
| Unknown RAM Module 1024MB SODIMM DDR2                          | 1         | 2.78%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 1         | 2.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 2.78%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s              | 1         | 2.78%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 2.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 2.78%   |
| Samsung RAM Module 8GB SODIMM DDR3 1067MT/s                    | 1         | 2.78%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                    | 1         | 2.78%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s          | 1         | 2.78%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 2.78%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 2.78%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.78%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 2.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 2.78%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s           | 1         | 2.78%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.78%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 1         | 2.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.78%   |
| Micron RAM 16JTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s         | 1         | 2.78%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s          | 1         | 2.78%   |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s              | 1         | 2.78%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s         | 1         | 2.78%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s          | 1         | 2.78%   |
| Corsair RAM CMSX64GX4M2A2666C18 32GB SODIMM DDR4 2667MT/s      | 1         | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 14        | 51.85%  |
| DDR3   | 11        | 40.74%  |
| LPDDR3 | 1         | 3.7%    |
| DDR2   | 1         | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 92.59%  |
| Row Of Chips | 2         | 7.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 12        | 40%     |
| 16384 | 6         | 20%     |
| 4096  | 5         | 16.67%  |
| 2048  | 5         | 16.67%  |
| 32768 | 1         | 3.33%   |
| 1024  | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 6         | 22.22%  |
| 2667    | 6         | 22.22%  |
| 1600    | 6         | 22.22%  |
| 2133    | 2         | 7.41%   |
| 1334    | 2         | 7.41%   |
| 1067    | 2         | 7.41%   |
| 1867    | 1         | 3.7%    |
| 1333    | 1         | 3.7%    |
| Unknown | 1         | 3.7%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 9         | 47.37%  |
| Microdia                               | 3         | 15.79%  |
| Realtek Semiconductor                  | 2         | 10.53%  |
| Lite-On Technology                     | 1         | 5.26%   |
| Lenovo                                 | 1         | 5.26%   |
| IMC Networks                           | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 5.26%   |
| Bison Electronics                      | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Realtek USB 2.0 PC Camera                                   | 2         | 10.53%  |
| Chicony ThinkPad T490 Webcam                                | 2         | 10.53%  |
| Chicony Integrated Camera                                   | 2         | 10.53%  |
| Chicony HP HD Camera                                        | 2         | 10.53%  |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 5.26%   |
| Microdia Integrated Webcam HD                               | 1         | 5.26%   |
| Microdia Integrated Webcam                                  | 1         | 5.26%   |
| Lite-On HP HD Camera                                        | 1         | 5.26%   |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 5.26%   |
| IMC Networks Integrated Camera                              | 1         | 5.26%   |
| Chicony Integrated IR Camera                                | 1         | 5.26%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 5.26%   |
| Chicony HP Universal Camera                                 | 1         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 5.26%   |
| Bison Lenovo EasyCamera                                     | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 30.77%  |
| Upek                       | 3         | 23.08%  |
| Synaptics                  | 3         | 23.08%  |
| Shenzhen Goodix Technology | 2         | 15.38%  |
| STMicroelectronics         | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 23.08%  |
| Validity Sensors VFS495 Fingerprint Reader               | 2         | 15.38%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 15.38%  |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 15.38%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 7.69%   |
| Validity Sensors VFS491                                  | 1         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 7.69%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 7.69%   |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 12        | 37.5%   |
| 3     | 8         | 25%     |
| 1     | 8         | 25%     |
| 4     | 2         | 6.25%   |
| 0     | 2         | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 21        | 38.18%  |
| Fingerprint reader       | 13        | 23.64%  |
| Bluetooth                | 8         | 14.55%  |
| Card reader              | 7         | 12.73%  |
| Firewire controller      | 3         | 5.45%   |
| Net/wireless             | 2         | 3.64%   |
| Graphics card            | 1         | 1.82%   |

