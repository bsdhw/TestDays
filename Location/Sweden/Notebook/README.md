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

Total: 39

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo    | IdeaPad 3 14IML05 81WA      | [d04d402809](https://bsd-hardware.info/?probe=d04d402809) | Feb 21, 2023 |
| Apple     | MacBookAir6,1               | [96fa5325d1](https://bsd-hardware.info/?probe=96fa5325d1) | Feb 11, 2023 |
| HP        | Pavilion Laptop 14-bf0xx    | [a98d28355d](https://bsd-hardware.info/?probe=a98d28355d) | Feb 05, 2023 |
| Star Labs | StarBook                    | [d222f381b0](https://bsd-hardware.info/?probe=d222f381b0) | Jan 23, 2023 |
| Star Labs | StarBook                    | [045d4bb6e8](https://bsd-hardware.info/?probe=045d4bb6e8) | Jan 23, 2023 |
| Deciso    | NetBoard-A10                | [21c60a4db8](https://bsd-hardware.info/?probe=21c60a4db8) | Jan 04, 2023 |
| Lenovo    | IdeaPad L340-17IWL 81M0     | [22c4a06468](https://bsd-hardware.info/?probe=22c4a06468) | Dec 31, 2022 |
| Toshiba   | TECRA Z40-C-12Z             | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| HP        | Unknown                     | [7bd69ee984](https://bsd-hardware.info/?probe=7bd69ee984) | Aug 29, 2022 |
| HP        | ProBook 4730s               | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| ASUSTek   | UX305UA                     | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| Lenovo    | ThinkPad T460s 20FAS4KH0... | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| Lenovo    | V130-15IGM 81HL             | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| Lenovo    | ThinkPad T420 4236MBG       | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| ASUSTek   | K52Jc                       | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| ASUSTek   | K52Jc                       | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| Google    | Grunt                       | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Google    | Grunt                       | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| Google    | Grunt                       | [e6d4421a4d](https://bsd-hardware.info/?probe=e6d4421a4d) | Oct 16, 2021 |
| Google    | Grunt                       | [ee9b2d7ad3](https://bsd-hardware.info/?probe=ee9b2d7ad3) | Oct 15, 2021 |
| Google    | Grunt                       | [e76c73d9a3](https://bsd-hardware.info/?probe=e76c73d9a3) | Oct 11, 2021 |
| Acer      | Aspire A315-56              | [03ca802f4b](https://bsd-hardware.info/?probe=03ca802f4b) | Oct 02, 2021 |
| Dell      | Latitude E5530 non-vPro     | [bd4b0f0700](https://bsd-hardware.info/?probe=bd4b0f0700) | Aug 17, 2021 |
| Lenovo    | ThinkPad X250 20CLS4JH00    | [89a74889ae](https://bsd-hardware.info/?probe=89a74889ae) | Aug 02, 2021 |
| Lenovo    | ThinkPad T400 2767WSB       | [36ce1d1e00](https://bsd-hardware.info/?probe=36ce1d1e00) | Jul 24, 2021 |
| Lenovo    | ThinkPad T420 4236MBG       | [5b43300a93](https://bsd-hardware.info/?probe=5b43300a93) | Jul 13, 2021 |
| Sony      | SVP1322M1EBI                | [23316d0f2b](https://bsd-hardware.info/?probe=23316d0f2b) | May 29, 2021 |
| Dell      | Latitude 5500               | [2538b038ed](https://bsd-hardware.info/?probe=2538b038ed) | May 08, 2021 |
| Lenovo    | ThinkPad X395 20NL001SMX    | [cd016e96ee](https://bsd-hardware.info/?probe=cd016e96ee) | Mar 17, 2021 |
| Dell      | Latitude E7240              | [e42e579971](https://bsd-hardware.info/?probe=e42e579971) | Feb 22, 2021 |
| HP        | EliteBook 8440p             | [7968c7d2dd](https://bsd-hardware.info/?probe=7968c7d2dd) | Feb 16, 2021 |
| Lenovo    | Legion Y530-15ICH 81FV      | [f8bdec0105](https://bsd-hardware.info/?probe=f8bdec0105) | Feb 14, 2021 |
| ASUSTek   | S551LN                      | [42792115e3](https://bsd-hardware.info/?probe=42792115e3) | Feb 11, 2021 |
| Toshiba   | Satellite L450              | [eb44256bfe](https://bsd-hardware.info/?probe=eb44256bfe) | Feb 11, 2021 |
| Lenovo    | ThinkPad X201 3680FAG       | [1ba69078df](https://bsd-hardware.info/?probe=1ba69078df) | Dec 06, 2020 |
| HP        | Laptop 15-dw0xxx            | [547b36ea62](https://bsd-hardware.info/?probe=547b36ea62) | Aug 19, 2020 |
| Lenovo    | ThinkPad W520 4284GN2       | [acb3ad955f](https://bsd-hardware.info/?probe=acb3ad955f) | Aug 06, 2020 |
| Lenovo    | ThinkPad L560 20F10032MS    | [bf2b792b64](https://bsd-hardware.info/?probe=bf2b792b64) | Aug 06, 2020 |
| Lenovo    | ThinkPad L560 20F10032MS    | [0aa6a9a921](https://bsd-hardware.info/?probe=0aa6a9a921) | Aug 06, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.5.0    | 4         | 12.5%   |
| OpenBSD 7.0          | 3         | 9.38%   |
| helloSystem 0.8.0    | 3         | 9.38%   |
| OpenBSD 6.9          | 2         | 6.25%   |
| helloSystem 0.7.0    | 2         | 6.25%   |
| helloSystem 0.4.0    | 2         | 6.25%   |
| FreeBSD 13.1-p5      | 2         | 6.25%   |
| FreeBSD 12.1-p8      | 2         | 6.25%   |
| OPNsense 22.10       | 1         | 3.13%   |
| OPNsense 21.1        | 1         | 3.13%   |
| OpenBSD 7.2          | 1         | 3.13%   |
| OpenBSD 6.8          | 1         | 3.13%   |
| OpenBSD 6.7          | 1         | 3.13%   |
| GhostBSD 22.08.27    | 1         | 3.13%   |
| GhostBSD 21.08.27    | 1         | 3.13%   |
| GhostBSD 20.04.02    | 1         | 3.13%   |
| FreeBSD 14.0-CURRENT | 1         | 3.13%   |
| FreeBSD 13.0-p7      | 1         | 3.13%   |
| FreeBSD 13.0-p10     | 1         | 3.13%   |
| FreeBSD 13.0         | 1         | 3.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 11        | 35.48%  |
| FreeBSD     | 8         | 25.81%  |
| OpenBSD     | 7         | 22.58%  |
| GhostBSD    | 3         | 9.68%   |
| OPNsense    | 2         | 6.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 31        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 12        | 37.5%   |
| fvwm         | 6         | 18.75%  |
| Console      | 5         | 15.63%  |
| MATE         | 3         | 9.38%   |
| KDE5         | 2         | 6.25%   |
| i3           | 2         | 6.25%   |
| Mutter       | 1         | 3.13%   |
| LXQt         | 1         | 3.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 25        | 80.65%  |
| Console | 6         | 19.35%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 12        | 38.71%  |
| Console | 12        | 38.71%  |
| LightDM | 4         | 12.9%   |
| XDM     | 1         | 3.23%   |
| SDDM    | 1         | 3.23%   |
| GDM     | 1         | 3.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 12        | 38.71%  |
| Unknown | 9         | 29.03%  |
| C       | 6         | 19.35%  |
| sv_SE   | 1         | 3.23%   |
| sv      | 1         | 3.23%   |
| en_BE   | 1         | 3.23%   |
| en      | 1         | 3.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 25        | 78.13%  |
| BIOS | 7         | 21.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 19        | 61.29%  |
| Ffs    | 7         | 22.58%  |
| Cd9660 | 3         | 9.68%   |
| Ufs    | 2         | 6.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 28        | 84.85%  |
| MBR  | 5         | 15.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 12        | 38.71%  |
| Hewlett-Packard  | 5         | 16.13%  |
| Dell             | 3         | 9.68%   |
| ASUSTek Computer | 3         | 9.68%   |
| Toshiba          | 2         | 6.45%   |
| Star Labs        | 1         | 3.23%   |
| Sony             | 1         | 3.23%   |
| Google           | 1         | 3.23%   |
| Deciso           | 1         | 3.23%   |
| Apple            | 1         | 3.23%   |
| Acer             | 1         | 3.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Toshiba TECRA Z40-C-12Z          | 1         | 3.23%   |
| Toshiba Satellite L450           | 1         | 3.23%   |
| Star Labs StarBook               | 1         | 3.23%   |
| Sony SVP1322M1EBI                | 1         | 3.23%   |
| Lenovo V130-15IGM 81HL           | 1         | 3.23%   |
| Lenovo ThinkPad X395 20NL001SMX  | 1         | 3.23%   |
| Lenovo ThinkPad X250 20CLS4JH00  | 1         | 3.23%   |
| Lenovo ThinkPad X201 3680FAG     | 1         | 3.23%   |
| Lenovo ThinkPad W520 4284GN2     | 1         | 3.23%   |
| Lenovo ThinkPad T460s 20FAS4KH02 | 1         | 3.23%   |
| Lenovo ThinkPad T420 4236MBG     | 1         | 3.23%   |
| Lenovo ThinkPad T400 2767WSB     | 1         | 3.23%   |
| Lenovo ThinkPad L560 20F10032MS  | 1         | 3.23%   |
| Lenovo Legion Y530-15ICH 81FV    | 1         | 3.23%   |
| Lenovo IdeaPad L340-17IWL 81M0   | 1         | 3.23%   |
| Lenovo IdeaPad 3 14IML05 81WA    | 1         | 3.23%   |
| HP ProBook 4730s                 | 1         | 3.23%   |
| HP Pavilion Laptop 14-bf0xx      | 1         | 3.23%   |
| HP Laptop 15-dw0xxx              | 1         | 3.23%   |
| HP EliteBook 8440p               | 1         | 3.23%   |
| Google Grunt                     | 1         | 3.23%   |
| Dell Latitude E7240              | 1         | 3.23%   |
| Dell Latitude E5530 non-vPro     | 1         | 3.23%   |
| Dell Latitude 5500               | 1         | 3.23%   |
| Deciso NetBoard-A10              | 1         | 3.23%   |
| ASUS UX305UA                     | 1         | 3.23%   |
| ASUS S551LN                      | 1         | 3.23%   |
| ASUS K52Jc                       | 1         | 3.23%   |
| Apple MacBookAir6,1              | 1         | 3.23%   |
| Acer Aspire A315-56              | 1         | 3.23%   |
| Unknown                          | 1         | 3.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 8         | 25.81%  |
| Dell Latitude       | 3         | 9.68%   |
| Lenovo IdeaPad      | 2         | 6.45%   |
| Toshiba TECRA       | 1         | 3.23%   |
| Toshiba Satellite   | 1         | 3.23%   |
| Star Labs StarBook  | 1         | 3.23%   |
| Sony SVP1322M1EBI   | 1         | 3.23%   |
| Lenovo V130-15IGM   | 1         | 3.23%   |
| Lenovo Legion       | 1         | 3.23%   |
| HP ProBook          | 1         | 3.23%   |
| HP Pavilion         | 1         | 3.23%   |
| HP Laptop           | 1         | 3.23%   |
| HP EliteBook        | 1         | 3.23%   |
| Google Grunt        | 1         | 3.23%   |
| Deciso NetBoard-A10 | 1         | 3.23%   |
| ASUS UX305UA        | 1         | 3.23%   |
| ASUS S551LN         | 1         | 3.23%   |
| ASUS K52Jc          | 1         | 3.23%   |
| Apple MacBookAir6   | 1         | 3.23%   |
| Acer Aspire         | 1         | 3.23%   |
| Unknown             | 1         | 3.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 5         | 16.13%  |
| 2021 | 3         | 9.68%   |
| 2019 | 3         | 9.68%   |
| 2014 | 3         | 9.68%   |
| 2009 | 3         | 9.68%   |
| 2022 | 2         | 6.45%   |
| 2018 | 2         | 6.45%   |
| 2016 | 2         | 6.45%   |
| 2015 | 2         | 6.45%   |
| 2010 | 2         | 6.45%   |
| 2023 | 1         | 3.23%   |
| 2017 | 1         | 3.23%   |
| 2012 | 1         | 3.23%   |
| 2011 | 1         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 31        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 28        | 90.32%  |
| Yes  | 3         | 9.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 13        | 41.94%  |
| 4.01-8.0   | 10        | 32.26%  |
| 16.01-24.0 | 4         | 12.9%   |
| 32.01-64.0 | 2         | 6.45%   |
| 3.01-4.0   | 1         | 3.23%   |
| 24.01-32.0 | 1         | 3.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 22        | 70.97%  |
| 0.51-1.0 | 6         | 19.35%  |
| 1.01-2.0 | 2         | 6.45%   |
| 2.01-3.0 | 1         | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 25        | 80.65%  |
| 2      | 5         | 16.13%  |
| 3      | 1         | 3.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 21        | 67.74%  |
| Yes       | 10        | 32.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 24        | 77.42%  |
| No        | 7         | 22.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 29        | 93.55%  |
| No        | 2         | 6.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 20        | 62.5%   |
| No        | 12        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 31        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Stockholm      | 3         | 9.09%   |
| Malmo          | 3         | 9.09%   |
| Henan          | 3         | 9.09%   |
| VÃ¤sterÃ¥s | 2         | 6.06%   |
| Varekil        | 1         | 3.03%   |
| Trosa          | 1         | 3.03%   |
| Staffanstorp   | 1         | 3.03%   |
| Solna          | 1         | 3.03%   |
| Sollentuna     | 1         | 3.03%   |
| Sollebrunn     | 1         | 3.03%   |
| SkellefteÃ¥  | 1         | 3.03%   |
| OEvertornea    | 1         | 3.03%   |
| OEverlida      | 1         | 3.03%   |
| LuleÃ¥       | 1         | 3.03%   |
| Lidkoeping     | 1         | 3.03%   |
| Kungsbacka     | 1         | 3.03%   |
| Klagshamn      | 1         | 3.03%   |
| Hoeviksnaes    | 1         | 3.03%   |
| Hoerby         | 1         | 3.03%   |
| GГ¤vle       | 1         | 3.03%   |
| Falkenberg     | 1         | 3.03%   |
| Faergelanda    | 1         | 3.03%   |
| Eskilstuna     | 1         | 3.03%   |
| Enebyberg      | 1         | 3.03%   |
| Borensberg     | 1         | 3.03%   |
| Bastad         | 1         | 3.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 17.65%  |
| Seagate             | 5         | 5      | 14.71%  |
| WDC                 | 4         | 4      | 11.76%  |
| SanDisk             | 3         | 3      | 8.82%   |
| Kingston            | 3         | 3      | 8.82%   |
| Micron Technology   | 2         | 2      | 5.88%   |
| Intel               | 2         | 2      | 5.88%   |
| Transcend           | 1         | 1      | 2.94%   |
| Toshiba             | 1         | 1      | 2.94%   |
| Star Drive          | 1         | 1      | 2.94%   |
| SK hynix            | 1         | 1      | 2.94%   |
| NVMe                | 1         | 1      | 2.94%   |
| Hitachi             | 1         | 1      | 2.94%   |
| Crucial             | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB          | 2         | 5.88%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 2.94%   |
| WDC WD3200BEKT-08PVMT1 320GB         | 1         | 2.94%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 2.94%   |
| WDC PC SN520 NVMe 256GB              | 1         | 2.94%   |
| Transcend TS256GMTE652T2 256GB       | 1         | 2.94%   |
| Toshiba KSG60ZMV256G 256GB           | 1         | 2.94%   |
| Star Drive PCIe SSD 960GB            | 1         | 2.94%   |
| SK hynix HFS128G32TNF-N3A0A 128GB    | 1         | 2.94%   |
| Seagate ST9640320AS 640GB            | 1         | 2.94%   |
| Seagate ST9500420AS 500GB            | 1         | 2.94%   |
| Seagate ST9320423AS 320GB            | 1         | 2.94%   |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 2.94%   |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 2.94%   |
| SanDisk SDSSDHP256G 256GB            | 1         | 2.94%   |
| SanDisk SD8TN8U256G1001 256GB        | 1         | 2.94%   |
| SanDisk SD8SN8U-256G-1006 256GB      | 1         | 2.94%   |
| Samsung SSD PM851 mSATA 256GB        | 1         | 2.94%   |
| Samsung SSD 860 PRO 256GB            | 1         | 2.94%   |
| Samsung SSD 860 EVO 250GB            | 1         | 2.94%   |
| Samsung MZNTE128HMGR-000SO 128GB     | 1         | 2.94%   |
| Samsung MZNLN128HAHQ-000L2 128GB     | 1         | 2.94%   |
| Samsung Flash Drive FIT 32GB         | 1         | 2.94%   |
| NVMe INTEL SSDPEKNW51 512GB          | 1         | 2.94%   |
| Micron M600_MTFDDAV256MBF 256GB      | 1         | 2.94%   |
| Micron C400-MTFDDAK256MAM 256GB      | 1         | 2.94%   |
| Kingston SNV2S500G 500GB             | 1         | 2.94%   |
| Intel SSDSA2M080G2GC 80GB            | 1         | 2.94%   |
| Intel SSDPEKNW512G8 512GB            | 1         | 2.94%   |
| Hitachi HTS725025A9A364 250GB        | 1         | 2.94%   |
| Crucial CT1000MX500SSD1 1TB          | 1         | 2.94%   |
| Apple SSD SD0128F 121GB              | 1         | 2.94%   |
| A-DATA SX6000NP 128GB                | 1         | 2.94%   |

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
| Samsung Electronics | 5         | 5      | 27.78%  |
| SanDisk             | 3         | 3      | 16.67%  |
| Micron Technology   | 2         | 2      | 11.11%  |
| Kingston            | 2         | 2      | 11.11%  |
| Toshiba             | 1         | 1      | 5.56%   |
| SK hynix            | 1         | 1      | 5.56%   |
| NVMe                | 1         | 1      | 5.56%   |
| Intel               | 1         | 1      | 5.56%   |
| Crucial             | 1         | 1      | 5.56%   |
| Apple               | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 17        | 18     | 51.52%  |
| HDD  | 9         | 10     | 27.27%  |
| NVMe | 7         | 7      | 21.21%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 25        | 28     | 78.13%  |
| NVMe | 7         | 7      | 21.88%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20        | 22     | 76.92%  |
| 0.51-1.0   | 6         | 6      | 23.08%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 13        | 40.63%  |
| 1-20       | 7         | 21.88%  |
| 251-500    | 4         | 12.5%   |
| 501-1000   | 4         | 12.5%   |
| 51-100     | 3         | 9.38%   |
| 21-50      | 1         | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 29        | 93.55%  |
| 21-50   | 2         | 6.45%   |

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
| Works    | 24        | 26     | 72.73%  |
| Malfunc  | 8         | 8      | 24.24%  |
| Detected | 1         | 1      | 3.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 26        | 78.79%  |
| SanDisk                     | 2         | 6.06%   |
| Transcend                   | 1         | 3.03%   |
| Realtek Semiconductor       | 1         | 3.03%   |
| Phison Electronics          | 1         | 3.03%   |
| Marvell Technology Group    | 1         | 3.03%   |
| Kingston Technology Company | 1         | 3.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 5         | 13.16%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 7.89%   |
| Intel SSD 660P Series                                                        | 2         | 5.26%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 5.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 5.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 5.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 5.26%   |
| Unknown                                                                      | 2         | 5.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 2.63%   |
| SanDisk PC SN520 NVMe SSD                                                    | 1         | 2.63%   |
| Realtek NVMe Controller                                                      | 1         | 2.63%   |
| Phison E18 PCIe4 NVMe Controller                                             | 1         | 2.63%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                   | 1         | 2.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 2.63%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 2.63%   |
| Intel Comet Lake SATA AHCI Controller                                        | 1         | 2.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 2.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 1         | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 1         | 2.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 1         | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                   | 1         | 2.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 2.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 2.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 2.63%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 2.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 24        | 64.86%  |
| NVMe | 8         | 21.62%  |
| IDE  | 3         | 8.11%   |
| RAID | 2         | 5.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 90.32%  |
| AMD    | 3         | 9.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 6.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 6.45%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 6.45%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 2         | 6.45%   |
| Intel Pentium CPU 6405U @ 2.40GHz               | 1         | 3.23%   |
| Intel CPU Version                               | 1         | 3.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 3.23%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 3.23%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 3.23%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 3.23%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 3.23%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 3.23%   |
| Intel Core i5-4260U CPU @ 1.40GHz               | 1         | 3.23%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 3.23%   |
| Intel Core i5-3340M CPU @ 2.70GHz               | 1         | 3.23%   |
| Intel Core i5-2540M CPU @ 2.60GHz               | 1         | 3.23%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 3.23%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 3.23%   |
| Intel Core i3-7100U CPU @ 2.40GHz               | 1         | 3.23%   |
| Intel Core i3 CPU M 350 @ 2.27GH                | 1         | 3.23%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz            | 1         | 3.23%   |
| Intel Core 2 Duo CPU P9700 @ 2.80GHz            | 1         | 3.23%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 3.23%   |
| Intel 12th Gen Core i7-1260P                    | 1         | 3.23%   |
| AMD Ryzen Embedded V1500B                       | 1         | 3.23%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 1         | 3.23%   |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G   | 1         | 3.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 17        | 54.84%  |
| Intel Core i7      | 3         | 9.68%   |
| Other              | 2         | 6.45%   |
| Intel Core i3      | 2         | 6.45%   |
| Intel Core 2 Duo   | 2         | 6.45%   |
| Intel Pentium      | 1         | 3.23%   |
| Intel Celeron      | 1         | 3.23%   |
| AMD Ryzen Embedded | 1         | 3.23%   |
| AMD Ryzen 5 PRO    | 1         | 3.23%   |
| AMD A4             | 1         | 3.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 20        | 64.52%  |
| 4       | 5         | 16.13%  |
| 8       | 2         | 6.45%   |
| Unknown | 2         | 6.45%   |
| 16      | 1         | 3.23%   |
| 6       | 1         | 3.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 30        | 96.77%  |
| Unknown | 1         | 3.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 23        | 74.19%  |
| 1       | 6         | 19.35%  |
| Unknown | 2         | 6.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 6         | 19.35%  |
| Skylake       | 4         | 12.9%   |
| Haswell       | 4         | 12.9%   |
| Westmere      | 3         | 9.68%   |
| SandyBridge   | 3         | 9.68%   |
| Penryn        | 2         | 6.45%   |
| Zen+          | 1         | 3.23%   |
| Zen           | 1         | 3.23%   |
| IvyBridge     | 1         | 3.23%   |
| IceLake       | 1         | 3.23%   |
| Goldmont plus | 1         | 3.23%   |
| Excavator     | 1         | 3.23%   |
| Core          | 1         | 3.23%   |
| Broadwell     | 1         | 3.23%   |
| Unknown       | 1         | 3.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 27        | 79.41%  |
| Nvidia | 4         | 11.76%  |
| AMD    | 3         | 8.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 11.43%  |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 11.43%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 8.57%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 8.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 5.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 5.71%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 2.86%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 2.86%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 2.86%   |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 2.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 2.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 2.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 2.86%   |
| Intel HD Graphics 620                                                     | 1         | 2.86%   |
| Intel HD Graphics 5500                                                    | 1         | 2.86%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 2.86%   |
| Intel Comet Lake-U GT2 [UHD Graphics 620]                                 | 1         | 2.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 2.86%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 1         | 2.86%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 2.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 2.86%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 2.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 20        | 64.52%  |
| 2 x Intel      | 3         | 9.68%   |
| Intel + Nvidia | 3         | 9.68%   |
| 1 x AMD        | 2         | 6.45%   |
| Other          | 1         | 3.23%   |
| 1 x Nvidia     | 1         | 3.23%   |
| Intel + AMD    | 1         | 3.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 27        | 87.1%   |
| Unknown     | 3         | 9.68%   |
| Proprietary | 1         | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 93.55%  |
| 1.01-2.0   | 2         | 6.45%   |

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
| 1     | 23        | 71.88%  |
| 0     | 7         | 21.88%  |
| 3     | 1         | 3.13%   |
| 2     | 1         | 3.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 51.11%  |
| Realtek Semiconductor | 11        | 24.44%  |
| Qualcomm Atheros      | 4         | 8.89%   |
| Sierra Wireless       | 1         | 2.22%   |
| Ralink Technology     | 1         | 2.22%   |
| JMicron Technology    | 1         | 2.22%   |
| Google                | 1         | 2.22%   |
| Edimax Technology     | 1         | 2.22%   |
| Broadcom              | 1         | 2.22%   |
| AMD                   | 1         | 2.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                | Notebooks | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                    | 9         | 15%     |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 3         | 5%      |
| Intel Wireless 8260                                                                  | 3         | 5%      |
| Intel Wireless 7260                                                                  | 3         | 5%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 2         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 2         | 3.33%   |
| Intel Wireless 7265                                                                  | 2         | 3.33%   |
| Intel Ethernet Connection I219-LM                                                    | 2         | 3.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                      | 2         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 2         | 3.33%   |
| Intel Centrino Advanced-N 6200                                                       | 2         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                | 2         | 3.33%   |
| Intel 82577LM Gigabit Network Connection                                             | 2         | 3.33%   |
| Sierra Wireless EM7345 4G LTE                                                        | 1         | 1.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 1         | 1.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                | 1         | 1.67%   |
| Ralink RT5370 Wireless Adapter                                                       | 1         | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 1         | 1.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 1         | 1.67%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                               | 1         | 1.67%   |
| Intel Wireless-AC 9260                                                               | 1         | 1.67%   |
| Intel WiFi Link 5100                                                                 | 1         | 1.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 1         | 1.67%   |
| Intel I211 Gigabit Network Connection                                                | 1         | 1.67%   |
| Intel Ethernet Connection I219-V                                                     | 1         | 1.67%   |
| Intel Ethernet Connection I218-LM                                                    | 1         | 1.67%   |
| Intel Ethernet Connection (6) I219-LM                                                | 1         | 1.67%   |
| Intel Ethernet Connection (3) I218-LM                                                | 1         | 1.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 1         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                    | 1         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                             | 1         | 1.67%   |
| Intel 82567LM Gigabit Network Connection                                             | 1         | 1.67%   |
| Intel 82566MM Gigabit Network Connection                                             | 1         | 1.67%   |
| Google Pixel 6 Pro CDC Network Control Model (NCM) CDC Network Data CDC Network Data | 1         | 1.67%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]                       | 1         | 1.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 1         | 1.67%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0                            | 1         | 1.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 60.61%  |
| Realtek Semiconductor | 5         | 15.15%  |
| Qualcomm Atheros      | 4         | 12.12%  |
| Sierra Wireless       | 1         | 3.03%   |
| Ralink Technology     | 1         | 3.03%   |
| Edimax Technology     | 1         | 3.03%   |
| Broadcom              | 1         | 3.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 8.82%   |
| Intel Wireless 8260                                            | 3         | 8.82%   |
| Intel Wireless 7260                                            | 3         | 8.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 5.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 5.88%   |
| Intel Wireless 7265                                            | 2         | 5.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 5.88%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 5.88%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 2.94%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 2.94%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 2.94%   |
| Intel Wireless-AC 9260                                         | 1         | 2.94%   |
| Intel WiFi Link 5100                                           | 1         | 2.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 2.94%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 2.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 2.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 52%     |
| Realtek Semiconductor | 10        | 40%     |
| JMicron Technology    | 1         | 4%      |
| AMD                   | 1         | 4%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 9         | 36%     |
| Intel Ethernet Connection I219-LM                                 | 2         | 8%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 8%      |
| Intel 82577LM Gigabit Network Connection                          | 2         | 8%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 4%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 4%      |
| Intel I211 Gigabit Network Connection                             | 1         | 4%      |
| Intel Ethernet Connection I219-V                                  | 1         | 4%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 4%      |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 4%      |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 4%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 4%      |
| Intel 82566MM Gigabit Network Connection                          | 1         | 4%      |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 1         | 4%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 29        | 53.7%   |
| Ethernet | 24        | 44.44%  |
| Unknown  | 1         | 1.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 59.46%  |
| Ethernet | 15        | 40.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 20        | 64.52%  |
| 1     | 10        | 32.26%  |
| 5     | 1         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 31        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 11        | 55%     |
| Hewlett-Packard       | 2         | 10%     |
| Broadcom              | 2         | 10%     |
| Realtek Semiconductor | 1         | 5%      |
| Lite-On Technology    | 1         | 5%      |
| IMC Networks          | 1         | 5%      |
| Dell                  | 1         | 5%      |
| Apple                 | 1         | 5%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 6         | 30%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 2         | 10%     |
| Broadcom BCM2045B (BDC-2.1)                             | 2         | 10%     |
| Realtek Bluetooth Adapter                               | 1         | 5%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 5%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1         | 5%      |
| Intel Wireless-AC 3168 Bluetooth                        | 1         | 5%      |
| Intel AX210 Bluetooth                                   | 1         | 5%      |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 5%      |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 5%      |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 5%      |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 5%      |
| Apple Broadcom Built-in Bluetooth                       | 1         | 5%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 28        | 84.85%  |
| AMD    | 3         | 9.09%   |
| Nvidia | 1         | 3.03%   |
| Lenovo | 1         | 3.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 5         | 12.82%  |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 10.26%  |
| Intel 8 Series HD Audio Controller                                         | 4         | 10.26%  |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 7.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 7.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 5.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 5.13%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 2.56%   |
| Lenovo Realtek USB Audio                                                   | 1         | 2.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 2.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 2.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 2.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 2.56%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 2.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 1         | 2.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 2.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 2.56%   |
| AMD High Definition Audio Controller                                       | 1         | 2.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 8         | 25.81%  |
| SK hynix            | 7         | 22.58%  |
| Micron Technology   | 4         | 12.9%   |
| Kingston            | 3         | 9.68%   |
| Elpida              | 2         | 6.45%   |
| Unknown             | 1         | 3.23%   |
| Transcend           | 1         | 3.23%   |
| Toshiba             | 1         | 3.23%   |
| GSkill              | 1         | 3.23%   |
| Crucial             | 1         | 3.23%   |
| Corsair             | 1         | 3.23%   |
| Unknown             | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 2         | 5.88%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 2         | 5.88%   |
| Unknown RAM Module 2GB SODIMM DDR3                          | 1         | 2.94%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s         | 1         | 2.94%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s        | 1         | 2.94%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s         | 1         | 2.94%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 2.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 2.94%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s   | 1         | 2.94%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 1         | 2.94%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 1         | 2.94%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s       | 1         | 2.94%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 2.94%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 2.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s       | 1         | 2.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s | 1         | 2.94%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s       | 1         | 2.94%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s      | 1         | 2.94%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 1         | 2.94%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 2.94%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 1         | 2.94%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s      | 1         | 2.94%   |
| Micron RAM 16HTF25664HY-800J1 2GB SODIMM DDR2 800MT/s       | 1         | 2.94%   |
| Kingston RAM Module 4GB SODIMM DDR4 2667MT/s                | 1         | 2.94%   |
| Kingston RAM ASU1333D3S9DR8/2G 2GB SODIMM DDR3 1333MT/s     | 1         | 2.94%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s     | 1         | 2.94%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s       | 1         | 2.94%   |
| Elpida RAM Module 4GB SODIMM LPDDR3 1600MT/s                | 1         | 2.94%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s       | 1         | 2.94%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16GB SODIMM DDR4 2400MT/s  | 1         | 2.94%   |
| Corsair RAM CMSO8GX3M1A1333C9 8GB SODIMM DDR3 1333MT/s      | 1         | 2.94%   |
| Unknown                                                     | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 11        | 44%     |
| DDR3    | 11        | 44%     |
| LPDDR3  | 1         | 4%      |
| DDR2    | 1         | 4%      |
| Unknown | 1         | 4%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 92.59%  |
| Row Of Chips | 1         | 3.7%    |
| Chip         | 1         | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 10        | 37.04%  |
| 8192  | 8         | 29.63%  |
| 2048  | 5         | 18.52%  |
| 16384 | 4         | 14.81%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 7         | 25.93%  |
| 2667    | 6         | 22.22%  |
| 3200    | 3         | 11.11%  |
| 1333    | 3         | 11.11%  |
| 2400    | 2         | 7.41%   |
| 1334    | 2         | 7.41%   |
| 800     | 2         | 7.41%   |
| 2133    | 1         | 3.7%    |
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


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 9         | 37.5%   |
| Bison Electronics     | 4         | 16.67%  |
| Realtek Semiconductor | 2         | 8.33%   |
| Microdia              | 2         | 8.33%   |
| IMC Networks          | 2         | 8.33%   |
| Syntek                | 1         | 4.17%   |
| Suyin                 | 1         | 4.17%   |
| Quanta                | 1         | 4.17%   |
| Logitech              | 1         | 4.17%   |
| Lenovo                | 1         | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Bison Integrated Camera                  | 3         | 12.5%   |
| Syntek EasyCamera                        | 1         | 4.17%   |
| Suyin Asus Integrated Webcam             | 1         | 4.17%   |
| Realtek Integrated_Webcam_HD             | 1         | 4.17%   |
| Realtek Front Camera                     | 1         | 4.17%   |
| Quanta VGA WebCam                        | 1         | 4.17%   |
| Microdia REDRAGON  Live Camera           | 1         | 4.17%   |
| Microdia Integrated Webcam               | 1         | 4.17%   |
| Logitech Webcam C270                     | 1         | 4.17%   |
| Lenovo Integrated Webcam                 | 1         | 4.17%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 4.17%   |
| IMC Networks EasyCamera                  | 1         | 4.17%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 4.17%   |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 4.17%   |
| Chicony TOSHIBA Web Camera - FHD         | 1         | 4.17%   |
| Chicony ThinkPad T490 Webcam             | 1         | 4.17%   |
| Chicony Realtek DMFT RGB                 | 1         | 4.17%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 4.17%   |
| Chicony Integrated HP HD Webcam          | 1         | 4.17%   |
| Chicony Integrated Camera                | 1         | 4.17%   |
| Chicony Camera                           | 1         | 4.17%   |
| Bison ThinkPad P50 Integrated Camera     | 1         | 4.17%   |

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
| 2     | 17        | 53.13%  |
| 1     | 6         | 18.75%  |
| 3     | 4         | 12.5%   |
| 0     | 3         | 9.38%   |
| 5     | 1         | 3.13%   |
| 4     | 1         | 3.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 26        | 48.15%  |
| Fingerprint reader       | 7         | 12.96%  |
| Card reader              | 6         | 11.11%  |
| Net/wireless             | 4         | 7.41%   |
| Firewire controller      | 3         | 5.56%   |
| Bluetooth                | 3         | 5.56%   |
| Graphics card            | 2         | 3.7%    |
| Storage/ata              | 1         | 1.85%   |
| Sound                    | 1         | 1.85%   |
| Network                  | 1         | 1.85%   |

