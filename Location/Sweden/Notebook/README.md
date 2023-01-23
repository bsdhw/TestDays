BSD in Sweden - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Sweden.

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

Total: 34

| Vendor  | Model                       | Probe                                                     | Date         |
|---------|-----------------------------|-----------------------------------------------------------|--------------|
| Deciso  | NetBoard-A10                | [21c60a4db8](https://bsd-hardware.info/?probe=21c60a4db8) | Jan 04, 2023 |
| Lenovo  | IdeaPad L340-17IWL 81M0     | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| Toshiba | TECRA Z40-C-12Z             | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| HP      | Unknown                     | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| HP      | ProBook 4730s               | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| ASUSTek | UX305UA                     | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| Lenovo  | ThinkPad T460s 20FAS4KH0... | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| Lenovo  | V130-15IGM 81HL             | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| Lenovo  | ThinkPad T420 4236MBG       | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| ASUSTek | K52Jc                       | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| ASUSTek | K52Jc                       | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| Google  | Grunt                       | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Google  | Grunt                       | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| Google  | Grunt                       | [e6d4421a4d](https://bsd-hardware.info/?probe=e6d4421a4d) | Oct 16, 2021 |
| Google  | Grunt                       | [ee9b2d7ad3](https://bsd-hardware.info/?probe=ee9b2d7ad3) | Oct 15, 2021 |
| Google  | Grunt                       | [e76c73d9a3](https://bsd-hardware.info/?probe=e76c73d9a3) | Oct 11, 2021 |
| Acer    | Aspire A315-56              | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| Dell    | Latitude E5530 non-vPro     | [bd4b0f0700](https://bsd-hardware.info/?probe=bd4b0f0700) | Aug 17, 2021 |
| Lenovo  | ThinkPad X250 20CLS4JH00    | [89a74889ae](https://bsd-hardware.info/?probe=89a74889ae) | Aug 02, 2021 |
| Lenovo  | ThinkPad T400 2767WSB       | [36ce1d1e00](https://bsd-hardware.info/?probe=36ce1d1e00) | Jul 24, 2021 |
| Lenovo  | ThinkPad T420 4236MBG       | [5b43300a93](https://bsd-hardware.info/?probe=5b43300a93) | Jul 13, 2021 |
| Sony    | SVP1322M1EBI                | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| Dell    | Latitude 5500               | [2538b038ed](https://bsd-hardware.info/?probe=2538b038ed) | May 08, 2021 |
| Lenovo  | ThinkPad X395 20NL001SMX    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| Dell    | Latitude E7240              | [e42e579971](https://bsd-hardware.info/?probe=e42e579971) | Feb 22, 2021 |
| HP      | EliteBook 8440p             | [7968c7d2dd](https://bsd-hardware.info/?probe=7968c7d2dd) | Feb 16, 2021 |
| Lenovo  | Legion Y530-15ICH 81FV      | [f8bdec0105](https://bsd-hardware.info/?probe=f8bdec0105) | Feb 14, 2021 |
| ASUSTek | S551LN                      | [42792115e3](https://bsd-hardware.info/?probe=42792115e3) | Feb 11, 2021 |
| Toshiba | Satellite L450              | [eb44256bfe](https://bsd-hardware.info/?probe=eb44256bfe) | Feb 11, 2021 |
| Lenovo  | ThinkPad X201 3680FAG       | [1ba69078df](https://bsd-hardware.info/?probe=1ba69078df) | Dec 06, 2020 |
| HP      | Laptop 15-dw0xxx            | [547b36ea62](https://bsd-hardware.info/?probe=547b36ea62) | Aug 19, 2020 |
| Lenovo  | ThinkPad W520 4284GN2       | [acb3ad955f](https://bsd-hardware.info/?probe=acb3ad955f) | Aug 06, 2020 |
| Lenovo  | ThinkPad L560 20F10032MS    | [bf2b792b64](https://bsd-hardware.info/?probe=bf2b792b64) | Aug 06, 2020 |
| Lenovo  | ThinkPad L560 20F10032MS    | [0aa6a9a921](https://bsd-hardware.info/?probe=0aa6a9a921) | Aug 06, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.5.0    | 4         | 14.29%  |
| OpenBSD 7.0          | 3         | 10.71%  |
| OpenBSD 6.9          | 2         | 7.14%   |
| helloSystem 0.7.0    | 2         | 7.14%   |
| helloSystem 0.4.0    | 2         | 7.14%   |
| FreeBSD 12.1-p8      | 2         | 7.14%   |
| OPNsense 22.10       | 1         | 3.57%   |
| OPNsense 21.1        | 1         | 3.57%   |
| OpenBSD 6.8          | 1         | 3.57%   |
| OpenBSD 6.7          | 1         | 3.57%   |
| helloSystem 0.8.0    | 1         | 3.57%   |
| GhostBSD 22.08.27    | 1         | 3.57%   |
| GhostBSD 21.08.27    | 1         | 3.57%   |
| GhostBSD 20.04.02    | 1         | 3.57%   |
| FreeBSD 14.0-CURRENT | 1         | 3.57%   |
| FreeBSD 13.1-p5      | 1         | 3.57%   |
| FreeBSD 13.0-p7      | 1         | 3.57%   |
| FreeBSD 13.0-p10     | 1         | 3.57%   |
| FreeBSD 13.0         | 1         | 3.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 9         | 33.33%  |
| FreeBSD     | 7         | 25.93%  |
| OpenBSD     | 6         | 22.22%  |
| GhostBSD    | 3         | 11.11%  |
| OPNsense    | 2         | 7.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 27        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 9         | 32.14%  |
| fvwm         | 6         | 21.43%  |
| Console      | 4         | 14.29%  |
| MATE         | 3         | 10.71%  |
| KDE5         | 2         | 7.14%   |
| i3           | 2         | 7.14%   |
| Mutter       | 1         | 3.57%   |
| LXQt         | 1         | 3.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 22        | 81.48%  |
| Console | 5         | 18.52%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 10        | 37.04%  |
| Console | 10        | 37.04%  |
| LightDM | 4         | 14.81%  |
| XDM     | 1         | 3.7%    |
| SDDM    | 1         | 3.7%    |
| GDM     | 1         | 3.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 12        | 44.44%  |
| Unknown | 8         | 29.63%  |
| C       | 5         | 18.52%  |
| sv_SE   | 1         | 3.7%    |
| en_BE   | 1         | 3.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 21        | 75%     |
| BIOS | 7         | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 19        | 70.37%  |
| Ffs    | 6         | 22.22%  |
| Ufs    | 1         | 3.7%    |
| Cd9660 | 1         | 3.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 24        | 82.76%  |
| MBR  | 5         | 17.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 11        | 40.74%  |
| Hewlett-Packard  | 4         | 14.81%  |
| Dell             | 3         | 11.11%  |
| ASUSTek Computer | 3         | 11.11%  |
| Toshiba          | 2         | 7.41%   |
| Sony             | 1         | 3.7%    |
| Google           | 1         | 3.7%    |
| Deciso           | 1         | 3.7%    |
| Acer             | 1         | 3.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Toshiba TECRA Z40-C-12Z          | 1         | 3.7%    |
| Toshiba Satellite L450           | 1         | 3.7%    |
| Sony SVP1322M1EBI                | 1         | 3.7%    |
| Lenovo V130-15IGM 81HL           | 1         | 3.7%    |
| Lenovo ThinkPad X395 20NL001SMX  | 1         | 3.7%    |
| Lenovo ThinkPad X250 20CLS4JH00  | 1         | 3.7%    |
| Lenovo ThinkPad X201 3680FAG     | 1         | 3.7%    |
| Lenovo ThinkPad W520 4284GN2     | 1         | 3.7%    |
| Lenovo ThinkPad T460s 20FAS4KH02 | 1         | 3.7%    |
| Lenovo ThinkPad T420 4236MBG     | 1         | 3.7%    |
| Lenovo ThinkPad T400 2767WSB     | 1         | 3.7%    |
| Lenovo ThinkPad L560 20F10032MS  | 1         | 3.7%    |
| Lenovo Legion Y530-15ICH 81FV    | 1         | 3.7%    |
| Lenovo IdeaPad L340-17IWL 81M0   | 1         | 3.7%    |
| HP ProBook 4730s                 | 1         | 3.7%    |
| HP Laptop 15-dw0xxx              | 1         | 3.7%    |
| HP EliteBook 8440p               | 1         | 3.7%    |
| Google Grunt                     | 1         | 3.7%    |
| Dell Latitude E7240              | 1         | 3.7%    |
| Dell Latitude E5530 non-vPro     | 1         | 3.7%    |
| Dell Latitude 5500               | 1         | 3.7%    |
| Deciso NetBoard-A10              | 1         | 3.7%    |
| ASUS UX305UA                     | 1         | 3.7%    |
| ASUS S551LN                      | 1         | 3.7%    |
| ASUS K52Jc                       | 1         | 3.7%    |
| Acer Aspire A315-56              | 1         | 3.7%    |
| Unknown                          | 1         | 3.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 8         | 29.63%  |
| Dell Latitude       | 3         | 11.11%  |
| Toshiba TECRA       | 1         | 3.7%    |
| Toshiba Satellite   | 1         | 3.7%    |
| Sony SVP1322M1EBI   | 1         | 3.7%    |
| Lenovo V130-15IGM   | 1         | 3.7%    |
| Lenovo Legion       | 1         | 3.7%    |
| Lenovo IdeaPad      | 1         | 3.7%    |
| HP ProBook          | 1         | 3.7%    |
| HP Laptop           | 1         | 3.7%    |
| HP EliteBook        | 1         | 3.7%    |
| Google Grunt        | 1         | 3.7%    |
| Deciso NetBoard-A10 | 1         | 3.7%    |
| ASUS UX305UA        | 1         | 3.7%    |
| ASUS S551LN         | 1         | 3.7%    |
| ASUS K52Jc          | 1         | 3.7%    |
| Acer Aspire         | 1         | 3.7%    |
| Unknown             | 1         | 3.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 5         | 18.52%  |
| 2019 | 3         | 11.11%  |
| 2015 | 3         | 11.11%  |
| 2009 | 3         | 11.11%  |
| 2021 | 2         | 7.41%   |
| 2018 | 2         | 7.41%   |
| 2016 | 2         | 7.41%   |
| 2014 | 2         | 7.41%   |
| 2010 | 2         | 7.41%   |
| 2022 | 1         | 3.7%    |
| 2012 | 1         | 3.7%    |
| 2011 | 1         | 3.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 27        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 25        | 92.59%  |
| Yes  | 2         | 7.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 12        | 44.44%  |
| 4.01-8.0   | 8         | 29.63%  |
| 16.01-24.0 | 4         | 14.81%  |
| 32.01-64.0 | 1         | 3.7%    |
| 3.01-4.0   | 1         | 3.7%    |
| 24.01-32.0 | 1         | 3.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 19        | 70.37%  |
| 0.51-1.0 | 6         | 22.22%  |
| 2.01-3.0 | 1         | 3.7%    |
| 1.01-2.0 | 1         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 22        | 81.48%  |
| 2      | 4         | 14.81%  |
| 3      | 1         | 3.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 17        | 62.96%  |
| Yes       | 10        | 37.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 85.19%  |
| No        | 4         | 14.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 25        | 92.59%  |
| No        | 2         | 7.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 16        | 57.14%  |
| No        | 12        | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 27        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| VÃ¤sterÃ¥s | 2         | 6.9%    |
| Stockholm      | 2         | 6.9%    |
| Malmo          | 2         | 6.9%    |
| Henan          | 2         | 6.9%    |
| Trosa          | 1         | 3.45%   |
| Staffanstorp   | 1         | 3.45%   |
| Solna          | 1         | 3.45%   |
| Sollentuna     | 1         | 3.45%   |
| Sollebrunn     | 1         | 3.45%   |
| SkellefteÃ¥  | 1         | 3.45%   |
| OEvertornea    | 1         | 3.45%   |
| OEverlida      | 1         | 3.45%   |
| LuleÃ¥       | 1         | 3.45%   |
| Lidkoeping     | 1         | 3.45%   |
| Kungsbacka     | 1         | 3.45%   |
| Klagshamn      | 1         | 3.45%   |
| Hoeviksnaes    | 1         | 3.45%   |
| Hoerby         | 1         | 3.45%   |
| GГ¤vle       | 1         | 3.45%   |
| Falkenberg     | 1         | 3.45%   |
| Faergelanda    | 1         | 3.45%   |
| Eskilstuna     | 1         | 3.45%   |
| Enebyberg      | 1         | 3.45%   |
| Borensberg     | 1         | 3.45%   |
| Bastad         | 1         | 3.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 20%     |
| Seagate             | 5         | 5      | 16.67%  |
| WDC                 | 4         | 4      | 13.33%  |
| SanDisk             | 2         | 2      | 6.67%   |
| Micron Technology   | 2         | 2      | 6.67%   |
| Kingston            | 2         | 2      | 6.67%   |
| Intel               | 2         | 2      | 6.67%   |
| Transcend           | 1         | 1      | 3.33%   |
| Toshiba             | 1         | 1      | 3.33%   |
| SK hynix            | 1         | 1      | 3.33%   |
| NVMe                | 1         | 1      | 3.33%   |
| Hitachi             | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB          | 2         | 6.67%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 3.33%   |
| WDC WD3200BEKT-08PVMT1 320GB         | 1         | 3.33%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 3.33%   |
| WDC PC SN520 NVMe 256GB              | 1         | 3.33%   |
| Transcend TS256GMTE652T2 256GB       | 1         | 3.33%   |
| Toshiba KSG60ZMV256G 256GB           | 1         | 3.33%   |
| SK hynix HFS128G32TNF-N3A0A 128GB    | 1         | 3.33%   |
| Seagate ST9640320AS 640GB            | 1         | 3.33%   |
| Seagate ST9500420AS 500GB            | 1         | 3.33%   |
| Seagate ST9320423AS 320GB            | 1         | 3.33%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 3.33%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 3.33%   |
| SanDisk SDSSDHP256G 256GB            | 1         | 3.33%   |
| SanDisk SD8TN8U256G1001 256GB        | 1         | 3.33%   |
| Samsung SSD PM851 mSATA 256GB        | 1         | 3.33%   |
| Samsung SSD 860 PRO 256GB            | 1         | 3.33%   |
| Samsung SSD 860 EVO 250GB            | 1         | 3.33%   |
| Samsung MZNTE128HMGR-000SO 128GB     | 1         | 3.33%   |
| Samsung MZNLN128HAHQ-000L2 128GB     | 1         | 3.33%   |
| Samsung Flash Drive FIT 32GB         | 1         | 3.33%   |
| NVMe INTEL SSDPEKNW51 512GB          | 1         | 3.33%   |
| Micron M600_MTFDDAV256MBF 256GB      | 1         | 3.33%   |
| Micron C400-MTFDDAK256MAM 256GB      | 1         | 3.33%   |
| Intel SSDSA2M080G2GC 80GB            | 1         | 3.33%   |
| Intel SSDPEKNW512G8 512GB            | 1         | 3.33%   |
| Hitachi HTS725025A9A364 250GB        | 1         | 3.33%   |
| Crucial CT1000MX500SSD1 1TB          | 1         | 3.33%   |
| A-DATA SX6000NP 128GB                | 1         | 3.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 55.56%  |
| WDC                 | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 2      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 5      | 31.25%  |
| SanDisk             | 2         | 2      | 12.5%   |
| Micron Technology   | 2         | 2      | 12.5%   |
| Kingston            | 2         | 2      | 12.5%   |
| Toshiba             | 1         | 1      | 6.25%   |
| SK hynix            | 1         | 1      | 6.25%   |
| NVMe                | 1         | 1      | 6.25%   |
| Intel               | 1         | 1      | 6.25%   |
| Crucial             | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 15        | 16     | 51.72%  |
| HDD  | 9         | 10     | 31.03%  |
| NVMe | 5         | 5      | 17.24%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23        | 26     | 82.14%  |
| NVMe | 5         | 5      | 17.86%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 18        | 20     | 75%     |
| 0.51-1.0   | 6         | 6      | 25%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 11        | 39.29%  |
| 1-20       | 5         | 17.86%  |
| 251-500    | 4         | 14.29%  |
| 501-1000   | 4         | 14.29%  |
| 51-100     | 3         | 10.71%  |
| 21-50      | 1         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 25        | 92.59%  |
| 21-50   | 2         | 7.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST9640320AS 640GB                    | 1         | 1      | 12.5%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 12.5%   |
| Seagate ST9320423AS 320GB                    | 1         | 1      | 12.5%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 12.5%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 12.5%   |
| Samsung Electronics MZNTE128HMGR-000SO 128GB | 1         | 1      | 12.5%   |
| Intel SSDSA2M080G2GC 80GB                    | 1         | 1      | 12.5%   |
| Hitachi HTS725025A9A364 250GB                | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 62.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Intel               | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 83.33%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 75%     |
| SSD  | 2         | 2      | 25%     |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 20        | 22     | 68.97%  |
| Malfunc  | 8         | 8      | 27.59%  |
| Detected | 1         | 1      | 3.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 24        | 85.71%  |
| SanDisk               | 2         | 7.14%   |
| Transcend             | 1         | 3.57%   |
| Realtek Semiconductor | 1         | 3.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 4         | 12.12%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 9.09%   |
| Intel SSD 660P Series                                                        | 2         | 6.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 6.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 6.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 6.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 6.06%   |
| Unknown                                                                      | 2         | 6.06%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 3.03%   |
| SanDisk PC SN520 NVMe SSD                                                    | 1         | 3.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 3.03%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 3.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 3.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 3.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 3.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 3.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 1         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                   | 1         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 3.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 21        | 65.63%  |
| NVMe | 6         | 18.75%  |
| IDE  | 3         | 9.38%   |
| RAID | 2         | 6.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 88.89%  |
| AMD    | 3         | 11.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 7.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 7.41%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 7.41%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 2         | 7.41%   |
| Intel CPU Version                               | 1         | 3.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 3.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 3.7%    |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 3.7%    |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 3.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 3.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 3.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 3.7%    |
| Intel Core i5-3340M CPU @ 2.70GHz               | 1         | 3.7%    |
| Intel Core i5-2540M CPU @ 2.60GHz               | 1         | 3.7%    |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 3.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 3.7%    |
| Intel Core i3 CPU M 350 @ 2.27GH                | 1         | 3.7%    |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz            | 1         | 3.7%    |
| Intel Core 2 Duo CPU P9700 @ 2.80GHz            | 1         | 3.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 3.7%    |
| AMD Ryzen Embedded V1500B                       | 1         | 3.7%    |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 1         | 3.7%    |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G   | 1         | 3.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 16        | 59.26%  |
| Intel Core i7      | 3         | 11.11%  |
| Intel Core 2 Duo   | 2         | 7.41%   |
| Other              | 1         | 3.7%    |
| Intel Core i3      | 1         | 3.7%    |
| Intel Celeron      | 1         | 3.7%    |
| AMD Ryzen Embedded | 1         | 3.7%    |
| AMD Ryzen 5 PRO    | 1         | 3.7%    |
| AMD A4             | 1         | 3.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 17        | 62.96%  |
| 4       | 5         | 18.52%  |
| 8       | 2         | 7.41%   |
| Unknown | 2         | 7.41%   |
| 6       | 1         | 3.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 26        | 96.3%   |
| Unknown | 1         | 3.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 20        | 74.07%  |
| 1       | 5         | 18.52%  |
| Unknown | 2         | 7.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Skylake       | 4         | 14.81%  |
| KabyLake      | 4         | 14.81%  |
| Westmere      | 3         | 11.11%  |
| SandyBridge   | 3         | 11.11%  |
| Haswell       | 3         | 11.11%  |
| Penryn        | 2         | 7.41%   |
| Zen+          | 1         | 3.7%    |
| Zen           | 1         | 3.7%    |
| IvyBridge     | 1         | 3.7%    |
| IceLake       | 1         | 3.7%    |
| Goldmont plus | 1         | 3.7%    |
| Excavator     | 1         | 3.7%    |
| Core          | 1         | 3.7%    |
| Broadwell     | 1         | 3.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 23        | 76.67%  |
| Nvidia | 4         | 13.33%  |
| AMD    | 3         | 10%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 12.9%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 9.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 9.68%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 9.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 6.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 6.45%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 3.23%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 3.23%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 3.23%   |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 3.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 3.23%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 3.23%   |
| Intel HD Graphics 5500                                                    | 1         | 3.23%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 3.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 3.23%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 3.23%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 3.23%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 3.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 16        | 59.26%  |
| 2 x Intel      | 3         | 11.11%  |
| Intel + Nvidia | 3         | 11.11%  |
| 1 x AMD        | 2         | 7.41%   |
| Other          | 1         | 3.7%    |
| 1 x Nvidia     | 1         | 3.7%    |
| Intel + AMD    | 1         | 3.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 23        | 85.19%  |
| Unknown     | 3         | 11.11%  |
| Proprietary | 1         | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 92.59%  |
| 1.01-2.0   | 2         | 7.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 6         | 25%     |
| Chimei Innolux          | 6         | 25%     |
| AU Optronics            | 2         | 8.33%   |
| Samsung Electronics     | 1         | 4.17%   |
| Panasonic               | 1         | 4.17%   |
| Lenovo Group Limited    | 1         | 4.17%   |
| Lenovo                  | 1         | 4.17%   |
| InfoVision              | 1         | 4.17%   |
| Hewlett-Packard         | 1         | 4.17%   |
| Gigabyte Technology     | 1         | 4.17%   |
| Dell                    | 1         | 4.17%   |
| Chi Mei Optoelectronics | 1         | 4.17%   |
| Ancor Communications    | 1         | 4.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch     | 1         | 4.17%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 4.17%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 1         | 4.17%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch             | 1         | 4.17%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch             | 1         | 4.17%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch              | 1         | 4.17%   |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch              | 1         | 4.17%   |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch              | 1         | 4.17%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 4.17%   |
| Lenovo Group Limited LCD Monitor 1920x1080                               | 1         | 4.17%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 4.17%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch               | 1         | 4.17%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch           | 1         | 4.17%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                        | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 340x190mm 15.3-inch         | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch         | 1         | 4.17%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 4.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1593 1366x768 340x190mm 15.3-inch | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 340x190mm 15.3-inch            | 1         | 4.17%   |
| AU Optronics LCD Monitor AUO219E 1600x900 380x210mm 17.1-inch            | 1         | 4.17%   |
| Ancor Communications VG248 ACI24A5 1920x1080 530x300mm 24.0-inch         | 1         | 4.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 9         | 37.5%   |
| 1366x768 (WXGA)   | 6         | 25%     |
| 1600x900 (HD+)    | 4         | 16.67%  |
| 3840x2160 (4K)    | 2         | 8.33%   |
| 2880x1620         | 1         | 4.17%   |
| 1920x1200 (WUXGA) | 1         | 4.17%   |
| 1440x900 (WXGA+)  | 1         | 4.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 9         | 37.5%   |
| 13      | 4         | 16.67%  |
| 24      | 2         | 8.33%   |
| 17      | 2         | 8.33%   |
| 14      | 2         | 8.33%   |
| 28      | 1         | 4.17%   |
| 27      | 1         | 4.17%   |
| 12      | 1         | 4.17%   |
| 11      | 1         | 4.17%   |
| Unknown | 1         | 4.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 12        | 50%     |
| 201-300     | 5         | 20.83%  |
| 601-700     | 2         | 8.33%   |
| 501-600     | 2         | 8.33%   |
| 351-400     | 2         | 8.33%   |
| Unknown     | 1         | 4.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 17        | 80.95%  |
| 16/10   | 3         | 14.29%  |
| Unknown | 1         | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 9         | 37.5%   |
| 81-90          | 5         | 20.83%  |
| 121-130        | 2         | 8.33%   |
| 71-80          | 1         | 4.17%   |
| 61-70          | 1         | 4.17%   |
| 51-60          | 1         | 4.17%   |
| 351-500        | 1         | 4.17%   |
| 301-350        | 1         | 4.17%   |
| 251-300        | 1         | 4.17%   |
| 201-250        | 1         | 4.17%   |
| Unknown        | 1         | 4.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 12        | 52.17%  |
| 101-120 | 6         | 26.09%  |
| 161-240 | 2         | 8.7%    |
| 51-100  | 2         | 8.7%    |
| Unknown | 1         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 21        | 75%     |
| 0     | 5         | 17.86%  |
| 3     | 1         | 3.57%   |
| 2     | 1         | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 52.63%  |
| Realtek Semiconductor | 9         | 23.68%  |
| Qualcomm Atheros      | 4         | 10.53%  |
| Sierra Wireless       | 1         | 2.63%   |
| Ralink Technology     | 1         | 2.63%   |
| JMicron Technology    | 1         | 2.63%   |
| Edimax Technology     | 1         | 2.63%   |
| AMD                   | 1         | 2.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 15.09%  |
| Intel Wireless 8260                                               | 3         | 5.66%   |
| Intel Wireless 7260                                               | 3         | 5.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 3.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 3.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 3.77%   |
| Intel Wireless 7265                                               | 2         | 3.77%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 3.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 3.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 3.77%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 3.77%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 3.77%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                     | 1         | 1.89%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 1.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.89%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 1.89%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.89%   |
| Intel Wireless-AC 9260                                            | 1         | 1.89%   |
| Intel WiFi Link 5100                                              | 1         | 1.89%   |
| Intel I211 Gigabit Network Connection                             | 1         | 1.89%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.89%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.89%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.89%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 1.89%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.89%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.89%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 1         | 1.89%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 1.89%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 60.71%  |
| Realtek Semiconductor | 4         | 14.29%  |
| Qualcomm Atheros      | 4         | 14.29%  |
| Sierra Wireless       | 1         | 3.57%   |
| Ralink Technology     | 1         | 3.57%   |
| Edimax Technology     | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 3         | 10.34%  |
| Intel Wireless 7260                                            | 3         | 10.34%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 6.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 6.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 6.9%    |
| Intel Wireless 7265                                            | 2         | 6.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 6.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 6.9%    |
| Intel Centrino Advanced-N 6200                                 | 2         | 6.9%    |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 3.45%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 3.45%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 3.45%   |
| Intel Wireless-AC 9260                                         | 1         | 3.45%   |
| Intel WiFi Link 5100                                           | 1         | 3.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 3.45%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 3.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 54.17%  |
| Realtek Semiconductor | 9         | 37.5%   |
| JMicron Technology    | 1         | 4.17%   |
| AMD                   | 1         | 4.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 8         | 33.33%  |
| Intel Ethernet Connection I219-LM                                 | 2         | 8.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 8.33%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 8.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4.17%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 4.17%   |
| Intel I211 Gigabit Network Connection                             | 1         | 4.17%   |
| Intel Ethernet Connection I219-V                                  | 1         | 4.17%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 4.17%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 4.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 4.17%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 4.17%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 4.17%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 4.17%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 25        | 52.08%  |
| Ethernet | 23        | 47.92%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 21        | 58.33%  |
| Ethernet | 15        | 41.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 19        | 70.37%  |
| 1     | 7         | 25.93%  |
| 5     | 1         | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 27        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 8         | 50%     |
| Hewlett-Packard       | 2         | 12.5%   |
| Broadcom              | 2         | 12.5%   |
| Realtek Semiconductor | 1         | 6.25%   |
| Lite-On Technology    | 1         | 6.25%   |
| IMC Networks          | 1         | 6.25%   |
| Dell                  | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 6         | 37.5%   |
| Broadcom BCM2045B (BDC-2.1)                             | 2         | 12.5%   |
| Realtek  Bluetooth Adapter                              | 1         | 6.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1         | 6.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1         | 6.25%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 6.25%   |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 6.25%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 6.25%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 24        | 82.76%  |
| AMD    | 3         | 10.34%  |
| Nvidia | 1         | 3.45%   |
| Lenovo | 1         | 3.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 4         | 11.76%  |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 8.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 8.82%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 8.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 8.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 8.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 5.88%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 5.88%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 2.94%   |
| Lenovo Realtek USB Audio                                                   | 1         | 2.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 2.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.94%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.94%   |
| AMD High Definition Audio Controller                                       | 1         | 2.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 25%     |
| SK hynix            | 6         | 21.43%  |
| Micron Technology   | 4         | 14.29%  |
| Kingston            | 3         | 10.71%  |
| Elpida              | 2         | 7.14%   |
| Unknown             | 1         | 3.57%   |
| Transcend           | 1         | 3.57%   |
| Toshiba             | 1         | 3.57%   |
| Crucial             | 1         | 3.57%   |
| Corsair             | 1         | 3.57%   |
| Unknown             | 1         | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 2         | 6.67%   |
| Unknown RAM Module 2GB SODIMM DDR3                         | 1         | 3.33%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s        | 1         | 3.33%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s       | 1         | 3.33%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s        | 1         | 3.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 3.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 3.33%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s  | 1         | 3.33%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s    | 1         | 3.33%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s      | 1         | 3.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 3.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 3.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 1         | 3.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s      | 1         | 3.33%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s      | 1         | 3.33%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s     | 1         | 3.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 3.33%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s              | 1         | 3.33%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s       | 1         | 3.33%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s     | 1         | 3.33%   |
| Micron RAM 16HTF25664HY-800J1 2GB SODIMM DDR2 800MT/s      | 1         | 3.33%   |
| Kingston RAM Module 4GB SODIMM DDR4 2667MT/s               | 1         | 3.33%   |
| Kingston RAM ASU1333D3S9DR8/2G 2GB SODIMM DDR3 1333MT/s    | 1         | 3.33%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s    | 1         | 3.33%   |
| Elpida RAM Module 4GB SODIMM LPDDR3 1600MT/s               | 1         | 3.33%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s      | 1         | 3.33%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16GB SODIMM DDR4 2400MT/s | 1         | 3.33%   |
| Corsair RAM CMSO8GX3M1A1333C9 8GB SODIMM DDR3 1333MT/s     | 1         | 3.33%   |
| Unknown                                                    | 1         | 3.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 11        | 50%     |
| DDR4    | 8         | 36.36%  |
| LPDDR3  | 1         | 4.55%   |
| DDR2    | 1         | 4.55%   |
| Unknown | 1         | 4.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 22        | 95.65%  |
| Chip   | 1         | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 8         | 33.33%  |
| 4096  | 8         | 33.33%  |
| 2048  | 5         | 20.83%  |
| 16384 | 3         | 12.5%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 7         | 30.43%  |
| 2667    | 5         | 21.74%  |
| 1333    | 3         | 13.04%  |
| 1334    | 2         | 8.7%    |
| 800     | 2         | 8.7%    |
| 3200    | 1         | 4.35%   |
| 2400    | 1         | 4.35%   |
| 2133    | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

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


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 8         | 38.1%   |
| Acer                  | 3         | 14.29%  |
| Realtek Semiconductor | 2         | 9.52%   |
| IMC Networks          | 2         | 9.52%   |
| Syntek                | 1         | 4.76%   |
| Suyin                 | 1         | 4.76%   |
| Quanta                | 1         | 4.76%   |
| Microdia              | 1         | 4.76%   |
| Logitech              | 1         | 4.76%   |
| Lenovo                | 1         | 4.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Syntek EasyCamera                        | 1         | 4.76%   |
| Suyin Asus Integrated Webcam             | 1         | 4.76%   |
| Realtek Integrated_Webcam_HD             | 1         | 4.76%   |
| Realtek Front Camera                     | 1         | 4.76%   |
| Quanta VGA WebCam                        | 1         | 4.76%   |
| Microdia Integrated Webcam               | 1         | 4.76%   |
| Logitech Webcam C270                     | 1         | 4.76%   |
| Lenovo Integrated Webcam                 | 1         | 4.76%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 4.76%   |
| IMC Networks EasyCamera                  | 1         | 4.76%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 4.76%   |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 4.76%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 4.76%   |
| Chicony ThinkPad T490 Webcam             | 1         | 4.76%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 4.76%   |
| Chicony Integrated HP HD Webcam          | 1         | 4.76%   |
| Chicony Integrated Camera                | 1         | 4.76%   |
| Chicony Camera                           | 1         | 4.76%   |
| Acer ThinkPad P50 Integrated Camera      | 1         | 4.76%   |
| Acer Integrated Camera                   | 1         | 4.76%   |
| Acer EasyCamera                          | 1         | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 33.33%  |
| Upek             | 2         | 22.22%  |
| AuthenTec        | 2         | 22.22%  |
| Synaptics        | 1         | 11.11%  |
| Broadcom         | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 22.22%  |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 11.11%  |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| AuthenTec AES2810                                                            | 1         | 11.11%  |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 11.11%  |

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
| 2     | 13        | 46.43%  |
| 1     | 6         | 21.43%  |
| 3     | 4         | 14.29%  |
| 0     | 3         | 10.71%  |
| 5     | 1         | 3.57%   |
| 4     | 1         | 3.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 22        | 46.81%  |
| Fingerprint reader       | 7         | 14.89%  |
| Card reader              | 6         | 12.77%  |
| Net/wireless             | 3         | 6.38%   |
| Firewire controller      | 3         | 6.38%   |
| Graphics card            | 2         | 4.26%   |
| Storage/ata              | 1         | 2.13%   |
| Sound                    | 1         | 2.13%   |
| Network                  | 1         | 2.13%   |
| Bluetooth                | 1         | 2.13%   |

