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

Total: 49

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [8854b07e12](https://bsd-hardware.info/?probe=8854b07e12) | Nov 15, 2023 |
| Shuttle       | DS437                       | [45c2e3460c](https://bsd-hardware.info/?probe=45c2e3460c) | Oct 30, 2023 |
| Deciso        | NetBoard-A10                | [12b5a57360](https://bsd-hardware.info/?probe=12b5a57360) | Oct 10, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | [aedd3a8255](https://bsd-hardware.info/?probe=aedd3a8255) | Jun 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | [722403df31](https://bsd-hardware.info/?probe=722403df31) | Jun 15, 2023 |
| HP            | ProBook 640 G4              | [7b44e1591f](https://bsd-hardware.info/?probe=7b44e1591f) | Apr 29, 2023 |
| Shuttle       | DS437                       | [284decb573](https://bsd-hardware.info/?probe=284decb573) | Apr 25, 2023 |
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
| FreeBSD 13.1         | 4         | 10.26%  |
| FreeBSD 13.1-p5      | 3         | 7.69%   |
| OPNsense 21.7.7      | 2         | 5.13%   |
| FreeBSD 14.0-CURRENT | 2         | 5.13%   |
| FreeBSD 13.0-p4      | 2         | 5.13%   |
| FreeBSD 12.1-p8      | 2         | 5.13%   |
| FreeBSD 12.1-p5      | 2         | 5.13%   |
| OPNsense 23.7.8      | 1         | 2.56%   |
| OPNsense 23.7.7      | 1         | 2.56%   |
| OPNsense 23.7.5      | 1         | 2.56%   |
| OPNsense 23.1.6      | 1         | 2.56%   |
| OPNsense 23.1.10     | 1         | 2.56%   |
| OPNsense 22.7.9      | 1         | 2.56%   |
| OPNsense 22.4.3      | 1         | 2.56%   |
| OPNsense 22.1.6      | 1         | 2.56%   |
| OPNsense 22.1.2      | 1         | 2.56%   |
| OPNsense 21.7.6      | 1         | 2.56%   |
| OpenBSD 6.8          | 1         | 2.56%   |
| helloSystem 0.8.2    | 1         | 2.56%   |
| helloSystem 0.7.0    | 1         | 2.56%   |
| helloSystem 0.5.0    | 1         | 2.56%   |
| FreeBSD 13.2         | 1         | 2.56%   |
| FreeBSD 13.0-CURRENT | 1         | 2.56%   |
| FreeBSD 13.0         | 1         | 2.56%   |
| FreeBSD 12.3         | 1         | 2.56%   |
| FreeBSD 12.2-p5      | 1         | 2.56%   |
| FreeBSD 12.2         | 1         | 2.56%   |
| FreeBSD 12.1-p4      | 1         | 2.56%   |
| FreeBSD 12.1-p10     | 1         | 2.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 21        | 61.76%  |
| OPNsense    | 9         | 26.47%  |
| helloSystem | 3         | 8.82%   |
| OpenBSD     | 1         | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 34        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Console      | 10        | 28.57%  |
| KDE5         | 8         | 22.86%  |
| XFCE         | 4         | 11.43%  |
| helloDesktop | 3         | 8.57%   |
| Cinnamon     | 3         | 8.57%   |
| MATE         | 2         | 5.71%   |
| i3           | 2         | 5.71%   |
| LXQt         | 1         | 2.86%   |
| GNOME        | 1         | 2.86%   |
| fvwm         | 1         | 2.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 23        | 65.71%  |
| Console | 11        | 31.43%  |
| Wayland | 1         | 2.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 16        | 45.71%  |
| SDDM    | 11        | 31.43%  |
| SLiM    | 5         | 14.29%  |
| XDM     | 1         | 2.86%   |
| LightDM | 1         | 2.86%   |
| GDM     | 1         | 2.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 14        | 38.89%  |
| C       | 11        | 30.56%  |
| en_US   | 7         | 19.44%  |
| cs_CZ   | 2         | 5.56%   |
| de_DE   | 1         | 2.78%   |
| de_AT   | 1         | 2.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 30        | 88.24%  |
| BIOS | 4         | 11.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 22        | 64.71%  |
| Ufs  | 11        | 32.35%  |
| Ffs  | 1         | 2.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 32        | 94.12%  |
| MBR  | 2         | 5.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Lenovo          | 14        | 41.18%  |
| Hewlett-Packard | 6         | 17.65%  |
| Dell            | 4         | 11.76%  |
| Deciso          | 2         | 5.88%   |
| Unknown         | 2         | 5.88%   |
| TUXEDO          | 1         | 2.94%   |
| Shuttle         | 1         | 2.94%   |
| Panasonic       | 1         | 2.94%   |
| Intel           | 1         | 2.94%   |
| Fujitsu         | 1         | 2.94%   |
| BESSTAR Tech    | 1         | 2.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo ThinkPad T490 20N2CTO1WW      | 2         | 5.88%   |
| HP EliteBook 850 G7 Notebook PC      | 2         | 5.88%   |
| Unknown                              | 2         | 5.88%   |
| TUXEDO InfinityBook Pro 14 Gen6      | 1         | 2.94%   |
| Shuttle DS437                        | 1         | 2.94%   |
| Panasonic CF-30KTP48NL               | 1         | 2.94%   |
| Lenovo Y50-70 20378                  | 1         | 2.94%   |
| Lenovo ThinkPad X220 4291WF5         | 1         | 2.94%   |
| Lenovo ThinkPad T60 2007J3G          | 1         | 2.94%   |
| Lenovo ThinkPad T510 4384AJ6         | 1         | 2.94%   |
| Lenovo ThinkPad T480 20L6S2S800      | 1         | 2.94%   |
| Lenovo ThinkPad T410 2537WEE         | 1         | 2.94%   |
| Lenovo ThinkPad T410 2537AT1         | 1         | 2.94%   |
| Lenovo ThinkPad E15 Gen 3 20YG006GGE | 1         | 2.94%   |
| Lenovo ThinkPad E14 Gen 3 20Y7003SGE | 1         | 2.94%   |
| Lenovo ThinkPad A485 20MVS0LG00      | 1         | 2.94%   |
| Lenovo IdeaPad 5 14ALC05 82LM        | 1         | 2.94%   |
| Lenovo IdeaPad 110S-11IBR 80WG       | 1         | 2.94%   |
| Intel H81U                           | 1         | 2.94%   |
| HP ZBook 17 G4                       | 1         | 2.94%   |
| HP ProBook 640 G4                    | 1         | 2.94%   |
| HP EliteBook Folio 9470m             | 1         | 2.94%   |
| HP EliteBook 840 G3                  | 1         | 2.94%   |
| Fujitsu LIFEBOOK A555                | 1         | 2.94%   |
| Dell XPS 13 9360                     | 1         | 2.94%   |
| Dell Vostro V131                     | 1         | 2.94%   |
| Dell Precision 7530                  | 1         | 2.94%   |
| Dell Latitude E7440                  | 1         | 2.94%   |
| Deciso NetBoard-A10                  | 1         | 2.94%   |
| Deciso DEC2700 - OPNsense Appliance  | 1         | 2.94%   |
| BESSTAR Tech U820                    | 1         | 2.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 11        | 32.35%  |
| HP EliteBook           | 4         | 11.76%  |
| Lenovo IdeaPad         | 2         | 5.88%   |
| Unknown                | 2         | 5.88%   |
| TUXEDO InfinityBook    | 1         | 2.94%   |
| Shuttle DS437          | 1         | 2.94%   |
| Panasonic CF-30KTP48NL | 1         | 2.94%   |
| Lenovo Y50-70          | 1         | 2.94%   |
| Intel H81U             | 1         | 2.94%   |
| HP ZBook               | 1         | 2.94%   |
| HP ProBook             | 1         | 2.94%   |
| Fujitsu LIFEBOOK       | 1         | 2.94%   |
| Dell XPS               | 1         | 2.94%   |
| Dell Vostro            | 1         | 2.94%   |
| Dell Precision         | 1         | 2.94%   |
| Dell Latitude          | 1         | 2.94%   |
| Deciso NetBoard-A10    | 1         | 2.94%   |
| Deciso DEC2700         | 1         | 2.94%   |
| BESSTAR Tech U820      | 1         | 2.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 6         | 17.65%  |
| 2019 | 6         | 17.65%  |
| 2022 | 4         | 11.76%  |
| 2018 | 4         | 11.76%  |
| 2010 | 3         | 8.82%   |
| 2017 | 2         | 5.88%   |
| 2016 | 2         | 5.88%   |
| 2011 | 2         | 5.88%   |
| 2020 | 1         | 2.94%   |
| 2015 | 1         | 2.94%   |
| 2013 | 1         | 2.94%   |
| 2009 | 1         | 2.94%   |
| 2006 | 1         | 2.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 34        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 34        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 14        | 41.18%  |
| 16.01-24.0  | 8         | 23.53%  |
| 32.01-64.0  | 4         | 11.76%  |
| 4.01-8.0    | 2         | 5.88%   |
| 3.01-4.0    | 2         | 5.88%   |
| 2.01-3.0    | 2         | 5.88%   |
| 64.01-256.0 | 2         | 5.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 16        | 47.06%  |
| 1.01-2.0 | 11        | 32.35%  |
| 0.51-1.0 | 5         | 14.71%  |
| 2.01-3.0 | 2         | 5.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 73.53%  |
| 0      | 4         | 11.76%  |
| 2      | 3         | 8.82%   |
| 3      | 2         | 5.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 33        | 97.06%  |
| Yes       | 1         | 2.94%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 27        | 79.41%  |
| No        | 7         | 20.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 88.24%  |
| No        | 4         | 11.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 68.57%  |
| No        | 11        | 31.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Austria | 34        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vienna           | 24        | 64.86%  |
| Graz             | 2         | 5.41%   |
| Wels             | 1         | 2.7%    |
| Weidlingbach     | 1         | 2.7%    |
| Vorchdorf        | 1         | 2.7%    |
| Schörfling      | 1         | 2.7%    |
| Parndorf         | 1         | 2.7%    |
| Neulengbach      | 1         | 2.7%    |
| Maria Enzersdorf | 1         | 2.7%    |
| Linz             | 1         | 2.7%    |
| Innsbruck        | 1         | 2.7%    |
| Grosspertholz    | 1         | 2.7%    |
| Bruck an der Mur | 1         | 2.7%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 15     | 33.33%  |
| Intel               | 4         | 5      | 11.11%  |
| WDC                 | 3         | 3      | 8.33%   |
| Transcend           | 3         | 5      | 8.33%   |
| SanDisk             | 3         | 3      | 8.33%   |
| SK hynix            | 2         | 2      | 5.56%   |
| Kingston            | 2         | 5      | 5.56%   |
| Seagate             | 1         | 1      | 2.78%   |
| Intenso             | 1         | 1      | 2.78%   |
| Hitachi             | 1         | 1      | 2.78%   |
| HGST                | 1         | 1      | 2.78%   |
| FORESEE             | 1         | 1      | 2.78%   |
| Crucial             | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 2      | 2.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Transcend TS256GMTE652T2 256GB          | 2         | 5.13%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 5.13%   |
| SanDisk SSD PLUS 240GB                  | 2         | 5.13%   |
| Samsung MZALQ512HBLU-00BL1 512GB        | 2         | 5.13%   |
| Intel SSDPEKKF512G8L 512GB              | 2         | 5.13%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 2.56%   |
| WDC WD20SPZX-22CRAT0 2TB                | 1         | 2.56%   |
| WDC WD10JPLX-00MBPT0 1TB                | 1         | 2.56%   |
| Transcend TS2TMTE220S 2TB               | 1         | 2.56%   |
| Seagate ST1000LX015-1U7172 1TB          | 1         | 2.56%   |
| SanDisk SD7TB3Q-128G-1006 128GB         | 1         | 2.56%   |
| Samsung SSD PM851 mSATA 256GB           | 1         | 2.56%   |
| Samsung SSD PM841 2.5-inch 7mm 256GB    | 1         | 2.56%   |
| Samsung SSD 980 500GB                   | 1         | 2.56%   |
| Samsung SSD 860 EVO 250GB               | 1         | 2.56%   |
| Samsung SSD 850 EVO 250GB               | 1         | 2.56%   |
| Samsung MZVLB256HAHQ-000L7 256GB        | 1         | 2.56%   |
| Samsung MZVKW512HMJP-000H1 512GB        | 1         | 2.56%   |
| Samsung MZALQ512HBLU-00BL2 512GB        | 1         | 2.56%   |
| Samsung MZ7TE512HMHP-000L2 512GB        | 1         | 2.56%   |
| Samsung MZ7PA128HMCD-010H1 128GB        | 1         | 2.56%   |
| Samsung HM320JI 320GB                   | 1         | 2.56%   |
| Kingston SUV500MS480G 480GB             | 1         | 2.56%   |
| Kingston SUV500MS120G 120GB             | 1         | 2.56%   |
| Kingston SKC600MS256G 256GB             | 1         | 2.56%   |
| Intenso JAJM600M256C 256GB              | 1         | 2.56%   |
| Intel SSDSCKKF256G8H 256GB              | 1         | 2.56%   |
| Intel SSDPEKNW020T8 2TB                 | 1         | 2.56%   |
| Hitachi HTS541040G9SA00 40GB            | 1         | 2.56%   |
| HGST HTS545050A7E680 500GB              | 1         | 2.56%   |
| FORESEE 64GB SSD                        | 1         | 2.56%   |
| Crucial CT275MX300SSD4 275GB            | 1         | 2.56%   |
| A-DATA SU650 240GB                      | 1         | 2.56%   |
| A-DATA SU630 240GB                      | 1         | 2.56%   |

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
| Samsung Electronics | 5         | 6      | 33.33%  |
| SanDisk             | 3         | 3      | 20%     |
| Kingston            | 2         | 5      | 13.33%  |
| Intenso             | 1         | 1      | 6.67%   |
| Intel               | 1         | 2      | 6.67%   |
| FORESEE             | 1         | 1      | 6.67%   |
| Crucial             | 1         | 1      | 6.67%   |
| A-DATA Technology   | 1         | 2      | 6.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 14        | 21     | 42.42%  |
| NVMe | 13        | 18     | 39.39%  |
| HDD  | 6         | 7      | 18.18%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 17        | 28     | 56.67%  |
| NVMe | 13        | 18     | 43.33%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 24     | 78.95%  |
| 0.51-1.0   | 3         | 3      | 15.79%  |
| 1.01-2.0   | 1         | 1      | 5.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 14        | 41.18%  |
| 251-500    | 13        | 38.24%  |
| 51-100     | 3         | 8.82%   |
| 21-50      | 2         | 5.88%   |
| 1-20       | 1         | 2.94%   |
| 501-1000   | 1         | 2.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 29        | 82.86%  |
| 21-50   | 3         | 8.57%   |
| 251-500 | 1         | 2.86%   |
| 101-250 | 1         | 2.86%   |
| 51-100  | 1         | 2.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 16.67%  |
| SanDisk SSD PLUS 240GB                       | 1         | 1      | 16.67%  |
| Samsung Electronics MZ7PA128HMCD-010H1 128GB | 1         | 1      | 16.67%  |
| Intel SSDSCKKF256G8H 256GB                   | 1         | 2      | 16.67%  |
| Hitachi HTS541040G9SA00 40GB                 | 1         | 1      | 16.67%  |
| A-DATA Technology SU630 240GB                | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 16.67%  |
| SanDisk             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Intel               | 1         | 2      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |
| A-DATA Technology   | 1         | 1      | 16.67%  |

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
| SSD  | 4         | 5      | 66.67%  |
| HDD  | 2         | 2      | 33.33%  |

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
| Works   | 27        | 39     | 81.82%  |
| Malfunc | 6         | 7      | 18.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 24        | 63.16%  |
| Samsung Electronics | 6         | 15.79%  |
| Transcend           | 2         | 5.26%   |
| SK hynix            | 2         | 5.26%   |
| AMD                 | 2         | 5.26%   |
| Toshiba             | 1         | 2.63%   |
| Silicon Motion      | 1         | 2.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 9.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 3         | 7.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 3         | 7.14%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)      | 2         | 4.76%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 4.76%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 2         | 4.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 4.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 4.76%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 4.76%   |
| Toshiba XG4 NVMe SSD Controller                                                  | 1         | 2.38%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 2.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 2.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 2.38%   |
| Intel SSD 660P Series                                                            | 1         | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 2.38%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 2.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 2.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 2.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 2.38%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 2.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 2.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 2.38%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 2.38%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 2.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 2.38%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 2.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 53.85%  |
| NVMe | 14        | 35.9%   |
| IDE  | 4         | 10.26%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 82.35%  |
| AMD    | 6         | 17.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 8.82%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 5.88%   |
| Intel Core i5-10310U CPU @ 1.70GHz              | 2         | 5.88%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 2         | 5.88%   |
| AMD Ryzen Embedded V1500B                       | 2         | 5.88%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 2.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 2.94%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 2.94%   |
| Intel Core i7-3687U CPU @ 2.10GHz               | 1         | 2.94%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 1         | 2.94%   |
| Intel Core i5-8279U CPU @ 2.40GHz               | 1         | 2.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 1         | 2.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 1         | 2.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 2.94%   |
| Intel Core i5-4310U CPU @ 2.00GHz               | 1         | 2.94%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 2.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 1         | 2.94%   |
| Intel Core i5 CPU M 560 @ 2.67GHz               | 1         | 2.94%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 2.94%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 1         | 2.94%   |
| Intel Core 2 Duo CPU L9300 @ 1.60GHz            | 1         | 2.94%   |
| Intel Core 2 CPU                                | 1         | 2.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 1         | 2.94%   |
| Intel Celeron CPU 867 @ 1.30GHz                 | 1         | 2.94%   |
| Intel Celeron CPU 1037U @ 1.80GHz               | 1         | 2.94%   |
| Intel Celeron 2955U @ 1.40GHz                   | 1         | 2.94%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz         | 1         | 2.94%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 1         | 2.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 13        | 38.24%  |
| Intel Core i7      | 6         | 17.65%  |
| Intel Celeron      | 4         | 11.76%  |
| AMD Ryzen 5        | 3         | 8.82%   |
| Intel Core i3      | 2         | 5.88%   |
| AMD Ryzen Embedded | 2         | 5.88%   |
| Other              | 1         | 2.94%   |
| Intel Core 2 Duo   | 1         | 2.94%   |
| Intel Core 2       | 1         | 2.94%   |
| AMD Ryzen 5 PRO    | 1         | 2.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 15        | 44.12%  |
| 4       | 10        | 29.41%  |
| 12      | 3         | 8.82%   |
| 8       | 3         | 8.82%   |
| Unknown | 2         | 5.88%   |
| 6       | 1         | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 33        | 97.06%  |
| Unknown | 1         | 2.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 22        | 64.71%  |
| 1       | 10        | 29.41%  |
| Unknown | 2         | 5.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 10        | 29.41%  |
| Haswell     | 4         | 11.76%  |
| Zen         | 3         | 8.82%   |
| Westmere    | 3         | 8.82%   |
| SandyBridge | 3         | 8.82%   |
| Unknown     | 3         | 8.82%   |
| IvyBridge   | 2         | 5.88%   |
| TigerLake   | 1         | 2.94%   |
| Skylake     | 1         | 2.94%   |
| Silvermont  | 1         | 2.94%   |
| Penryn      | 1         | 2.94%   |
| Core        | 1         | 2.94%   |
| Broadwell   | 1         | 2.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 25        | 75.76%  |
| AMD    | 5         | 15.15%  |
| Nvidia | 3         | 9.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 9.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 9.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 9.09%   |
| AMD Lucienne                                                                             | 3         | 9.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 6.06%   |
| Intel UHD Graphics 620                                                                   | 2         | 6.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 6.06%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 6.06%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 3.03%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 3.03%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 3.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 3.03%   |
| Intel HD Graphics 620                                                                    | 1         | 3.03%   |
| Intel HD Graphics 5500                                                                   | 1         | 3.03%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 3.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 3.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 3.03%   |
| AMD RV515/M52 [Mobility Radeon X1300]                                                    | 1         | 3.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 3.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 23        | 67.65%  |
| 1 x AMD        | 5         | 14.71%  |
| Other          | 2         | 5.88%   |
| 1 x Nvidia     | 2         | 5.88%   |
| 2 x Intel      | 1         | 2.94%   |
| Intel + Nvidia | 1         | 2.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 30        | 88.24%  |
| Proprietary | 2         | 5.88%   |
| Unknown     | 2         | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 83.33%  |
| 0.51-1.0   | 2         | 5.56%   |
| 7.01-8.0   | 1         | 2.78%   |
| 3.01-4.0   | 1         | 2.78%   |
| 1.01-2.0   | 1         | 2.78%   |
| 0.01-0.5   | 1         | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 22.73%  |
| LG Display          | 3         | 13.64%  |
| Lenovo              | 3         | 13.64%  |
| Chimei Innolux      | 3         | 13.64%  |
| BOE                 | 3         | 13.64%  |
| Samsung Electronics | 2         | 9.09%   |
| Unknown             | 1         | 4.55%   |
| Dell                | 1         | 4.55%   |
| BenQ                | 1         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C34J79x SAM0F1E 3440x1440 800x330mm 34.1-inch | 2         | 9.09%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch      | 2         | 9.09%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 310x170mm 13.9-inch    | 2         | 9.09%   |
| Unknown LCD Monitor Sharp 3840x2160                               | 1         | 4.55%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch       | 1         | 4.55%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch           | 1         | 4.55%   |
| Lenovo LCD Monitor LEN4043 1400x1050 300x230mm 14.9-inch          | 1         | 4.55%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch           | 1         | 4.55%   |
| Dell P2719H DEL4185 1920x1080 600x340mm 27.2-inch                 | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch  | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch   | 1         | 4.55%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch   | 1         | 4.55%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch             | 1         | 4.55%   |
| BOE LCD Monitor BOE0791 1920x1080 310x170mm 13.9-inch             | 1         | 4.55%   |
| BOE LCD Monitor BOE0714 1920x1080 310x170mm 13.9-inch             | 1         | 4.55%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                 | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 310x170mm 13.9-inch    | 1         | 4.55%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch    | 1         | 4.55%   |
| AU Optronics LCD Monitor 1920x1080                                | 1         | 4.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 9         | 42.86%  |
| 2560x1440 (QHD)  | 3         | 14.29%  |
| 1366x768 (WXGA)  | 3         | 14.29%  |
| 3440x1440        | 2         | 9.52%   |
| 3840x2160 (4K)   | 1         | 4.76%   |
| 1600x900 (HD+)   | 1         | 4.76%   |
| 1440x900 (WXGA+) | 1         | 4.76%   |
| 1400x1050        | 1         | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 9         | 40.91%  |
| 15      | 4         | 18.18%  |
| 34      | 2         | 9.09%   |
| 27      | 2         | 9.09%   |
| 14      | 2         | 9.09%   |
| Unknown | 2         | 9.09%   |
| 11      | 1         | 4.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 59.09%  |
| 201-300     | 3         | 13.64%  |
| 701-800     | 2         | 9.09%   |
| 501-600     | 2         | 9.09%   |
| Unknown     | 2         | 9.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 14        | 70%     |
| 21/9    | 2         | 10%     |
| Unknown | 2         | 10%     |
| 4/3     | 1         | 5%      |
| 16/10   | 1         | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 10        | 45.45%  |
| 91-100         | 3         | 13.64%  |
| 351-500        | 2         | 9.09%   |
| 301-350        | 2         | 9.09%   |
| 101-110        | 2         | 9.09%   |
| Unknown        | 2         | 9.09%   |
| 51-60          | 1         | 4.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 11        | 50%     |
| 101-120 | 5         | 22.73%  |
| 161-240 | 2         | 9.09%   |
| 51-100  | 2         | 9.09%   |
| Unknown | 2         | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 17        | 48.57%  |
| 0     | 14        | 40%     |
| 2     | 4         | 11.43%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 67.44%  |
| Realtek Semiconductor | 10        | 23.26%  |
| AMD                   | 2         | 4.65%   |
| Hewlett-Packard       | 1         | 2.33%   |
| Dell                  | 1         | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8         | 12.7%   |
| Intel Wireless 8265 / 8275                                             | 4         | 6.35%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 6.35%   |
| Intel Wireless 7260                                                    | 3         | 4.76%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 4.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 3.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 3.17%   |
| Intel Wireless 7265                                                    | 2         | 3.17%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 3.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 3.17%   |
| Intel Centrino Ultimate-N 6300                                         | 2         | 3.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 3.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 3.17%   |
| AMD XGMAC 10GbE Controller                                             | 2         | 3.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 1         | 1.59%   |
| Intel Wireless 8260                                                    | 1         | 1.59%   |
| Intel WiFi Link 5100                                                   | 1         | 1.59%   |
| Intel Wi-Fi 6 AX201                                                    | 1         | 1.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 1         | 1.59%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 1.59%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.59%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.59%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.59%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.59%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1.59%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 1         | 1.59%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 1         | 1.59%   |
| Intel Centrino Advanced-N 6235                                         | 1         | 1.59%   |
| Intel Centrino Advanced-N 6200                                         | 1         | 1.59%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 1.59%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.59%   |
| HP hs2350 HSPA+ Mobile Broadband Module Network Adapter                | 1         | 1.59%   |
| Dell Wireless 5550 HSPA+ Mini-Card Network Adapter                     | 1         | 1.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 25        | 80.65%  |
| Realtek Semiconductor | 5         | 16.13%  |
| Dell                  | 1         | 3.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                               | 4         | 12.5%   |
| Intel Wireless 7260                                      | 3         | 9.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter | 2         | 6.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter      | 2         | 6.25%   |
| Intel Wireless 7265                                      | 2         | 6.25%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]  | 2         | 6.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                        | 2         | 6.25%   |
| Intel Centrino Ultimate-N 6300                           | 2         | 6.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                 | 2         | 6.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter | 1         | 3.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter               | 1         | 3.13%   |
| Intel Wireless 8260                                      | 1         | 3.13%   |
| Intel WiFi Link 5100                                     | 1         | 3.13%   |
| Intel Wi-Fi 6 AX201                                      | 1         | 3.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection    | 1         | 3.13%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]            | 1         | 3.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]             | 1         | 3.13%   |
| Intel Centrino Advanced-N 6235                           | 1         | 3.13%   |
| Intel Centrino Advanced-N 6200                           | 1         | 3.13%   |
| Dell Wireless 5550 HSPA+ Mini-Card Network Adapter       | 1         | 3.13%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 66.67%  |
| Realtek Semiconductor | 8         | 26.67%  |
| AMD                   | 2         | 6.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 8         | 26.67%  |
| Intel I211 Gigabit Network Connection                                  | 4         | 13.33%  |
| Intel 82577LM Gigabit Network Connection                               | 3         | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 6.67%   |
| AMD XGMAC 10GbE Controller                                             | 2         | 6.67%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 3.33%   |
| Intel Ethernet Controller I225-V                                       | 1         | 3.33%   |
| Intel Ethernet Connection I219-V                                       | 1         | 3.33%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 3.33%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 3.33%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 3.33%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 3.33%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 3.33%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 3.33%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 3.33%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 30        | 51.72%  |
| Ethernet | 27        | 46.55%  |
| Modem    | 1         | 1.72%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 23        | 52.27%  |
| WiFi     | 20        | 45.45%  |
| Modem    | 1         | 2.27%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 55.88%  |
| 1     | 6         | 17.65%  |
| 3     | 4         | 11.76%  |
| 6     | 2         | 5.88%   |
| 5     | 2         | 5.88%   |
| 0     | 1         | 2.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 33        | 94.29%  |
| Yes  | 2         | 5.71%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 68%     |
| Broadcom              | 4         | 16%     |
| Realtek Semiconductor | 3         | 12%     |
| Alps Electric         | 1         | 4%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 8         | 32%     |
| Realtek Bluetooth Adapter                        | 3         | 12%     |
| Intel AX201 Bluetooth                            | 3         | 12%     |
| Broadcom BCM2045B (BDC-2.1)                      | 3         | 12%     |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 2         | 8%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 2         | 8%      |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 4%      |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 4%      |
| Broadcom BCM2035 Bluetooth dongle                | 1         | 4%      |
| Alps Electric UGTZ4 Bluetooth                    | 1         | 4%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 26        | 70.27%  |
| AMD         | 6         | 16.22%  |
| Plantronics | 3         | 8.11%   |
| Nvidia      | 1         | 2.7%    |
| Lenovo      | 1         | 2.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 13.04%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 8.7%    |
| Plantronics Plantronics Blackwire 315.1                                                           | 3         | 6.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 6.52%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 6.52%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 6.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 6.52%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 6.52%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 4.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 4.35%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 2.17%   |
| Lenovo Realtek USB Audio                                                                          | 1         | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 2.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 2.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 2.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 2.17%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 2.17%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 2.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 34.21%  |
| SK hynix            | 6         | 15.79%  |
| Micron Technology   | 6         | 15.79%  |
| Kingston            | 5         | 13.16%  |
| Transcend           | 2         | 5.26%   |
| Crucial             | 2         | 5.26%   |
| Unknown             | 1         | 2.63%   |
| Nanya Technology    | 1         | 2.63%   |
| Elpida              | 1         | 2.63%   |
| Corsair             | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s            | 2         | 4.88%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                  | 2         | 4.88%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 2         | 4.88%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 4.88%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 4.88%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 2         | 4.88%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 2.44%   |
| Unknown RAM Module 1024MB SODIMM DDR2                          | 1         | 2.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 2.44%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s              | 1         | 2.44%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s         | 1         | 2.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 2.44%   |
| Samsung RAM Module 8GB SODIMM DDR3 1067MT/s                    | 1         | 2.44%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                    | 1         | 2.44%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s          | 1         | 2.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 2.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 1         | 2.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 2.44%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 2.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 2.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 2.44%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s           | 1         | 2.44%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 2.44%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 1         | 2.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.44%   |
| Micron RAM 16JTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s         | 1         | 2.44%   |
| Kingston RAM Module 8GB SODIMM DDR4 2400MT/s                   | 1         | 2.44%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s          | 1         | 2.44%   |
| Kingston RAM KCRXJ6-MIE 16GB SODIMM DDR4 2667MT/s              | 1         | 2.44%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s         | 1         | 2.44%   |
| Kingston RAM 99U5417-030.A00G 4GB SODIMM DDR3 1600MT/s         | 1         | 2.44%   |
| Elpida RAM EBJ21UE8BDS0-AE-F 2GB SODIMM DDR3 1067MT/s          | 1         | 2.44%   |
| Crucial RAM CT32G4SFD832A.C16FF 32GB SODIMM DDR4 3200MT/s      | 1         | 2.44%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 1         | 2.44%   |
| Corsair RAM CMSX64GX4M2A2666C18 32GB SODIMM DDR4 2667MT/s      | 1         | 2.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 17        | 53.13%  |
| DDR3   | 13        | 40.63%  |
| LPDDR3 | 1         | 3.13%   |
| DDR2   | 1         | 3.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 30        | 93.75%  |
| Row Of Chips | 2         | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 15        | 42.86%  |
| 16384 | 6         | 17.14%  |
| 4096  | 6         | 17.14%  |
| 2048  | 5         | 14.29%  |
| 32768 | 2         | 5.71%   |
| 1024  | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 8         | 25%     |
| 3200    | 7         | 21.88%  |
| 2667    | 7         | 21.88%  |
| 2133    | 2         | 6.25%   |
| 1334    | 2         | 6.25%   |
| 1067    | 2         | 6.25%   |
| 2400    | 1         | 3.13%   |
| 1867    | 1         | 3.13%   |
| 1333    | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

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
| Chicony Electronics                    | 9         | 42.86%  |
| Microdia                               | 3         | 14.29%  |
| Realtek Semiconductor                  | 2         | 9.52%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 9.52%   |
| Bison Electronics                      | 2         | 9.52%   |
| Lite-On Technology                     | 1         | 4.76%   |
| Lenovo                                 | 1         | 4.76%   |
| IMC Networks                           | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Realtek USB 2.0 PC Camera                                   | 2         | 9.52%   |
| Chicony ThinkPad T490 Webcam                                | 2         | 9.52%   |
| Chicony Integrated Camera                                   | 2         | 9.52%   |
| Chicony HP HD Camera                                        | 2         | 9.52%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 4.76%   |
| Microdia Integrated Webcam HD                               | 1         | 4.76%   |
| Microdia Integrated Webcam                                  | 1         | 4.76%   |
| Lite-On HP HD Camera                                        | 1         | 4.76%   |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 4.76%   |
| IMC Networks Integrated Camera                              | 1         | 4.76%   |
| Chicony Integrated IR Camera                                | 1         | 4.76%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 4.76%   |
| Chicony HP Universal Camera                                 | 1         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 1         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 4.76%   |
| Bison SunplusIT Integrated Camera                           | 1         | 4.76%   |
| Bison Lenovo EasyCamera                                     | 1         | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 33.33%  |
| Upek                       | 3         | 20%     |
| Synaptics                  | 3         | 20%     |
| Shenzhen Goodix Technology | 2         | 13.33%  |
| STMicroelectronics         | 1         | 6.67%   |
| Elan Microelectronics      | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 20%     |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 13.33%  |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 6.67%   |
| Validity Sensors VFS491                                  | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 6.67%   |
| Elan Fingerprint Sensor                                  | 1         | 6.67%   |

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
| 2     | 14        | 37.84%  |
| 1     | 10        | 27.03%  |
| 3     | 8         | 21.62%  |
| 0     | 3         | 8.11%   |
| 4     | 2         | 5.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 25        | 40.98%  |
| Fingerprint reader       | 15        | 24.59%  |
| Bluetooth                | 8         | 13.11%  |
| Card reader              | 7         | 11.48%  |
| Firewire controller      | 3         | 4.92%   |
| Net/wireless             | 2         | 3.28%   |
| Graphics card            | 1         | 1.64%   |

