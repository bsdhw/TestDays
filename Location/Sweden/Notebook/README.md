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

Total: 31

| Vendor  | Model                       | Probe                                                     | Date         |
|---------|-----------------------------|-----------------------------------------------------------|--------------|
| HP      | ProBook 4730s               | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| ASUSTek | UX305UA                     | [3fb1786193](https://bsd-hardware.info/?probe=3fb1786193) | Apr 04, 2022 |
| Lenovo  | ThinkPad T460s 20FAS4KH0... | [dbb0e378d5](https://bsd-hardware.info/?probe=dbb0e378d5) | Mar 17, 2022 |
| Lenovo  | V130-15IGM 81HL             | [e0e7b21668](https://bsd-hardware.info/?probe=e0e7b21668) | Jan 09, 2022 |
| Lenovo  | ThinkPad T420 4236MBG       | [0391bf9ea4](https://bsd-hardware.info/?probe=0391bf9ea4) | Nov 14, 2021 |
| ASUSTek | K52Jc                       | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| ASUSTek | K52Jc                       | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| Google  | Grunt                       | [aa07a1dd40](https://bsd-hardware.info/?probe=aa07a1dd40) | Nov 05, 2021 |
| Google  | Grunt                       | [c87e033731](https://bsd-hardware.info/?probe=c87e033731) | Nov 01, 2021 |
| Google  | Grunt                       | [259f96d9c8](https://bsd-hardware.info/?probe=259f96d9c8) | Oct 22, 2021 |
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
| helloSystem 0.5.0    | 4         | 16.67%  |
| OpenBSD 7.0          | 3         | 12.5%   |
| OpenBSD 6.9          | 2         | 8.33%   |
| helloSystem 0.7.0    | 2         | 8.33%   |
| helloSystem 0.4.0    | 2         | 8.33%   |
| FreeBSD 12.1-p8      | 2         | 8.33%   |
| OPNsense 21.1        | 1         | 4.17%   |
| OpenBSD 6.8          | 1         | 4.17%   |
| OpenBSD 6.7          | 1         | 4.17%   |
| GhostBSD 21.08.27    | 1         | 4.17%   |
| GhostBSD 20.04.02    | 1         | 4.17%   |
| FreeBSD 14.0-CURRENT | 1         | 4.17%   |
| FreeBSD 13.0-p7      | 1         | 4.17%   |
| FreeBSD 13.0-p10     | 1         | 4.17%   |
| FreeBSD 13.0         | 1         | 4.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 8         | 34.78%  |
| OpenBSD     | 6         | 26.09%  |
| FreeBSD     | 6         | 26.09%  |
| GhostBSD    | 2         | 8.7%    |
| OPNsense    | 1         | 4.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 23        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 8         | 33.33%  |
| fvwm         | 6         | 25%     |
| MATE         | 3         | 12.5%   |
| Console      | 3         | 12.5%   |
| i3           | 2         | 8.33%   |
| Mutter       | 1         | 4.17%   |
| KDE5         | 1         | 4.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 19        | 82.61%  |
| Console | 4         | 17.39%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 9         | 39.13%  |
| Console | 9         | 39.13%  |
| LightDM | 3         | 13.04%  |
| XDM     | 1         | 4.35%   |
| GDM     | 1         | 4.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 11        | 47.83%  |
| Unknown | 7         | 30.43%  |
| C       | 5         | 21.74%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 19        | 79.17%  |
| BIOS | 5         | 20.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 16        | 69.57%  |
| Ffs  | 6         | 26.09%  |
| Ufs  | 1         | 4.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 20        | 80%     |
| MBR  | 5         | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 10        | 43.48%  |
| Hewlett-Packard  | 3         | 13.04%  |
| Dell             | 3         | 13.04%  |
| ASUSTek Computer | 3         | 13.04%  |
| Toshiba          | 1         | 4.35%   |
| Sony             | 1         | 4.35%   |
| Google           | 1         | 4.35%   |
| Acer             | 1         | 4.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Toshiba Satellite L450           | 1         | 4.35%   |
| Sony SVP1322M1EBI                | 1         | 4.35%   |
| Lenovo V130-15IGM 81HL           | 1         | 4.35%   |
| Lenovo ThinkPad X395 20NL001SMX  | 1         | 4.35%   |
| Lenovo ThinkPad X250 20CLS4JH00  | 1         | 4.35%   |
| Lenovo ThinkPad X201 3680FAG     | 1         | 4.35%   |
| Lenovo ThinkPad W520 4284GN2     | 1         | 4.35%   |
| Lenovo ThinkPad T460s 20FAS4KH02 | 1         | 4.35%   |
| Lenovo ThinkPad T420 4236MBG     | 1         | 4.35%   |
| Lenovo ThinkPad T400 2767WSB     | 1         | 4.35%   |
| Lenovo ThinkPad L560 20F10032MS  | 1         | 4.35%   |
| Lenovo Legion Y530-15ICH 81FV    | 1         | 4.35%   |
| HP ProBook 4730s                 | 1         | 4.35%   |
| HP Laptop 15-dw0xxx              | 1         | 4.35%   |
| HP EliteBook 8440p               | 1         | 4.35%   |
| Google Grunt                     | 1         | 4.35%   |
| Dell Latitude E7240              | 1         | 4.35%   |
| Dell Latitude E5530 non-vPro     | 1         | 4.35%   |
| Dell Latitude 5500               | 1         | 4.35%   |
| ASUS UX305UA                     | 1         | 4.35%   |
| ASUS S551LN                      | 1         | 4.35%   |
| ASUS K52Jc                       | 1         | 4.35%   |
| Acer Aspire A315-56              | 1         | 4.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 8         | 34.78%  |
| Dell Latitude     | 3         | 13.04%  |
| Toshiba Satellite | 1         | 4.35%   |
| Sony SVP1322M1EBI | 1         | 4.35%   |
| Lenovo V130-15IGM | 1         | 4.35%   |
| Lenovo Legion     | 1         | 4.35%   |
| HP ProBook        | 1         | 4.35%   |
| HP Laptop         | 1         | 4.35%   |
| HP EliteBook      | 1         | 4.35%   |
| Google Grunt      | 1         | 4.35%   |
| ASUS UX305UA      | 1         | 4.35%   |
| ASUS S551LN       | 1         | 4.35%   |
| ASUS K52Jc        | 1         | 4.35%   |
| Acer Aspire       | 1         | 4.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 4         | 17.39%  |
| 2015 | 3         | 13.04%  |
| 2021 | 2         | 8.7%    |
| 2019 | 2         | 8.7%    |
| 2018 | 2         | 8.7%    |
| 2016 | 2         | 8.7%    |
| 2014 | 2         | 8.7%    |
| 2010 | 2         | 8.7%    |
| 2009 | 2         | 8.7%    |
| 2012 | 1         | 4.35%   |
| 2011 | 1         | 4.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 23        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 21        | 91.3%   |
| Yes  | 2         | 8.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 10        | 43.48%  |
| 4.01-8.0   | 7         | 30.43%  |
| 16.01-24.0 | 3         | 13.04%  |
| 32.01-64.0 | 1         | 4.35%   |
| 3.01-4.0   | 1         | 4.35%   |
| 24.01-32.0 | 1         | 4.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 16        | 69.57%  |
| 0.51-1.0 | 5         | 21.74%  |
| 2.01-3.0 | 1         | 4.35%   |
| 1.01-2.0 | 1         | 4.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 19        | 82.61%  |
| 2      | 3         | 13.04%  |
| 3      | 1         | 4.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 14        | 60.87%  |
| Yes       | 9         | 39.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 19        | 82.61%  |
| No        | 4         | 17.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 22        | 95.65%  |
| No        | 1         | 4.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 15        | 62.5%   |
| No        | 9         | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Sweden  | 23        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| VÃ¤sterÃ¥s | 2         | 8%      |
| Stockholm      | 2         | 8%      |
| Malmo          | 2         | 8%      |
| Henan          | 2         | 8%      |
| Trosa          | 1         | 4%      |
| Staffanstorp   | 1         | 4%      |
| Solna          | 1         | 4%      |
| Sollentuna     | 1         | 4%      |
| SkellefteÃ¥  | 1         | 4%      |
| OEvertornea    | 1         | 4%      |
| OEverlida      | 1         | 4%      |
| LuleÃ¥       | 1         | 4%      |
| Lidkoeping     | 1         | 4%      |
| Kungsbacka     | 1         | 4%      |
| Klagshamn      | 1         | 4%      |
| Hoeviksnaes    | 1         | 4%      |
| Hoerby         | 1         | 4%      |
| GГ¤vle       | 1         | 4%      |
| Falkenberg     | 1         | 4%      |
| Eskilstuna     | 1         | 4%      |
| Bastad         | 1         | 4%      |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 20%     |
| Samsung Electronics | 5         | 6      | 20%     |
| WDC                 | 4         | 4      | 16%     |
| SanDisk             | 2         | 2      | 8%      |
| Micron Technology   | 2         | 2      | 8%      |
| Intel               | 2         | 2      | 8%      |
| SK hynix            | 1         | 1      | 4%      |
| NVMe                | 1         | 1      | 4%      |
| Kingston            | 1         | 1      | 4%      |
| Hitachi             | 1         | 1      | 4%      |
| A-DATA Technology   | 1         | 1      | 4%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 4%      |
| WDC WD3200BEKT-08PVMT1 320GB         | 1         | 4%      |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 4%      |
| WDC PC SN520 NVMe 256GB              | 1         | 4%      |
| SK hynix HFS128G32TNF-N3A0A 128GB    | 1         | 4%      |
| Seagate ST9640320AS 640GB            | 1         | 4%      |
| Seagate ST9500420AS 500GB            | 1         | 4%      |
| Seagate ST9320423AS 320GB            | 1         | 4%      |
| Seagate ST750LM022 HN-M750MBB 752GB  | 1         | 4%      |
| Seagate ST1000LM049-2GH172 1TB       | 1         | 4%      |
| SanDisk SDSSDHP256G 256GB            | 1         | 4%      |
| SanDisk SD8TN8U256G1001 256GB        | 1         | 4%      |
| Samsung SSD PM851 mSATA 256GB        | 1         | 4%      |
| Samsung SSD 860 PRO 256GB            | 1         | 4%      |
| Samsung SSD 860 EVO 250GB            | 1         | 4%      |
| Samsung MZNTE128HMGR-000SO 128GB     | 1         | 4%      |
| Samsung Flash Drive FIT 32GB         | 1         | 4%      |
| NVMe INTEL SSDPEKNW51 512GB          | 1         | 4%      |
| Micron M600_MTFDDAV256MBF 256GB      | 1         | 4%      |
| Micron C400-MTFDDAK256MAM 256GB      | 1         | 4%      |
| Kingston SA400S37120G 120GB          | 1         | 4%      |
| Intel SSDSA2M080G2GC 80GB            | 1         | 4%      |
| Intel SSDPEKNW512G8 512GB            | 1         | 4%      |
| Hitachi HTS725025A9A364 250GB        | 1         | 4%      |
| A-DATA SX6000NP 128GB                | 1         | 4%      |

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
| Samsung Electronics | 4         | 4      | 33.33%  |
| SanDisk             | 2         | 2      | 16.67%  |
| Micron Technology   | 2         | 2      | 16.67%  |
| SK hynix            | 1         | 1      | 8.33%   |
| NVMe                | 1         | 1      | 8.33%   |
| Kingston            | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 12        | 12     | 48%     |
| HDD  | 9         | 10     | 36%     |
| NVMe | 4         | 4      | 16%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 20        | 22     | 83.33%  |
| NVMe | 4         | 4      | 16.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15        | 17     | 75%     |
| 0.51-1.0   | 5         | 5      | 25%     |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 10        | 41.67%  |
| 251-500    | 4         | 16.67%  |
| 1-20       | 4         | 16.67%  |
| 501-1000   | 3         | 12.5%   |
| 51-100     | 2         | 8.33%   |
| 21-50      | 1         | 4.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 21        | 91.3%   |
| 21-50   | 2         | 8.7%    |

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
| Works    | 16        | 17     | 64%     |
| Malfunc  | 8         | 8      | 32%     |
| Detected | 1         | 1      | 4%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 87.5%   |
| SanDisk               | 2         | 8.33%   |
| Realtek Semiconductor | 1         | 4.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 10.71%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 10.71%  |
| Intel SSD 660P Series                                                        | 2         | 7.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 7.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 7.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 7.14%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 3.57%   |
| SanDisk PC SN520 NVMe SSD                                                    | 1         | 3.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 1         | 3.57%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 3.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 3.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 1         | 3.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 3.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 1         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                   | 1         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 1         | 3.57%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 3.57%   |
| Unknown                                                                      | 1         | 3.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 18        | 66.67%  |
| NVMe | 5         | 18.52%  |
| RAID | 2         | 7.41%   |
| IDE  | 2         | 7.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 91.3%   |
| AMD    | 2         | 8.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 8.7%    |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 2         | 8.7%    |
| Intel CPU Version                               | 1         | 4.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 4.35%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 4.35%   |
| Intel Core i7-2760QM CPU @ 2.40GHz              | 1         | 4.35%   |
| Intel Core i5-8365U CPU @ 1.60GHz               | 1         | 4.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 1         | 4.35%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 4.35%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 4.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 4.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 1         | 4.35%   |
| Intel Core i5-3340M CPU @ 2.70GHz               | 1         | 4.35%   |
| Intel Core i5-2540M CPU @ 2.60GHz               | 1         | 4.35%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 1         | 4.35%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 4.35%   |
| Intel Core i3 CPU M 350 @ 2.27GH                | 1         | 4.35%   |
| Intel Core 2 Duo CPU P9700 @ 2.80GHz            | 1         | 4.35%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 1         | 4.35%   |
| AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx | 1         | 4.35%   |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G   | 1         | 4.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 14        | 60.87%  |
| Intel Core i7    | 3         | 13.04%  |
| Other            | 1         | 4.35%   |
| Intel Core i3    | 1         | 4.35%   |
| Intel Core 2 Duo | 1         | 4.35%   |
| Intel Celeron    | 1         | 4.35%   |
| AMD Ryzen 5 PRO  | 1         | 4.35%   |
| AMD A4           | 1         | 4.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 16        | 69.57%  |
| 4       | 4         | 17.39%  |
| 8       | 1         | 4.35%   |
| 6       | 1         | 4.35%   |
| Unknown | 1         | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 22        | 95.65%  |
| Unknown | 1         | 4.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 18        | 78.26%  |
| 1       | 4         | 17.39%  |
| Unknown | 1         | 4.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Westmere      | 3         | 13.04%  |
| Skylake       | 3         | 13.04%  |
| SandyBridge   | 3         | 13.04%  |
| KabyLake      | 3         | 13.04%  |
| Haswell       | 3         | 13.04%  |
| Penryn        | 2         | 8.7%    |
| Zen+          | 1         | 4.35%   |
| IvyBridge     | 1         | 4.35%   |
| IceLake       | 1         | 4.35%   |
| Goldmont plus | 1         | 4.35%   |
| Excavator     | 1         | 4.35%   |
| Broadwell     | 1         | 4.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 20        | 76.92%  |
| Nvidia | 3         | 11.54%  |
| AMD    | 3         | 11.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 11.54%  |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 11.54%  |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 11.54%  |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 7.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 7.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 7.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 3.85%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 3.85%   |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 3.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 3.85%   |
| Intel HD Graphics 5500                                                    | 1         | 3.85%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 1         | 3.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1         | 3.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 3.85%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 3.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1         | 3.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 15        | 65.22%  |
| 2 x Intel      | 2         | 8.7%    |
| Intel + Nvidia | 2         | 8.7%    |
| 1 x AMD        | 2         | 8.7%    |
| 1 x Nvidia     | 1         | 4.35%   |
| Intel + AMD    | 1         | 4.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 20        | 86.96%  |
| Unknown     | 2         | 8.7%    |
| Proprietary | 1         | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 91.3%   |
| 1.01-2.0   | 2         | 8.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 6         | 28.57%  |
| LG Display              | 5         | 23.81%  |
| Panasonic               | 1         | 4.76%   |
| Lenovo Group Limited    | 1         | 4.76%   |
| Lenovo                  | 1         | 4.76%   |
| InfoVision              | 1         | 4.76%   |
| Hewlett-Packard         | 1         | 4.76%   |
| Gigabyte Technology     | 1         | 4.76%   |
| Dell                    | 1         | 4.76%   |
| Chi Mei Optoelectronics | 1         | 4.76%   |
| AU Optronics            | 1         | 4.76%   |
| Ancor Communications    | 1         | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch             | 1         | 4.76%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 1         | 4.76%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch             | 1         | 4.76%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch              | 1         | 4.76%   |
| LG Display LCD Monitor LGD027B 1600x900 380x210mm 17.1-inch              | 1         | 4.76%   |
| LG Display LCD Monitor LGD0213 1600x900 310x170mm 13.9-inch              | 1         | 4.76%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch                  | 1         | 4.76%   |
| Lenovo Group Limited LCD Monitor 1920x1080                               | 1         | 4.76%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch              | 1         | 4.76%   |
| Hewlett-Packard E242 HWP326E 1920x1200 520x320mm 24.0-inch               | 1         | 4.76%   |
| Gigabyte Technology M28U GBT2800 3840x2160 630x360mm 28.6-inch           | 1         | 4.76%   |
| Dell U2718Q DELA0EC 3840x2160 610x350mm 27.7-inch                        | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch         | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 340x190mm 15.3-inch          | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15B1 1920x1080 340x190mm 15.3-inch         | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN1509 1920x1080 340x190mm 15.3-inch         | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN13A2 1920x1080 290x170mm 13.2-inch         | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 1         | 4.76%   |
| Chi Mei Optoelectronics LCD Monitor CMO1593 1366x768 340x190mm 15.3-inch | 1         | 4.76%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 340x190mm 15.3-inch            | 1         | 4.76%   |
| Ancor Communications VG248 ACI24A5 1920x1080 530x300mm 24.0-inch         | 1         | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 8         | 38.1%   |
| 1366x768 (WXGA)   | 5         | 23.81%  |
| 1600x900 (HD+)    | 3         | 14.29%  |
| 3840x2160 (4K)    | 2         | 9.52%   |
| 2880x1620         | 1         | 4.76%   |
| 1920x1200 (WUXGA) | 1         | 4.76%   |
| 1440x900 (WXGA+)  | 1         | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 9         | 42.86%  |
| 13      | 3         | 14.29%  |
| 24      | 2         | 9.52%   |
| 28      | 1         | 4.76%   |
| 27      | 1         | 4.76%   |
| 17      | 1         | 4.76%   |
| 14      | 1         | 4.76%   |
| 12      | 1         | 4.76%   |
| 11      | 1         | 4.76%   |
| Unknown | 1         | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 52.38%  |
| 201-300     | 4         | 19.05%  |
| 601-700     | 2         | 9.52%   |
| 501-600     | 2         | 9.52%   |
| 351-400     | 1         | 4.76%   |
| Unknown     | 1         | 4.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 15        | 83.33%  |
| 16/10   | 2         | 11.11%  |
| Unknown | 1         | 5.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 9         | 42.86%  |
| 81-90          | 3         | 14.29%  |
| 71-80          | 1         | 4.76%   |
| 61-70          | 1         | 4.76%   |
| 51-60          | 1         | 4.76%   |
| 351-500        | 1         | 4.76%   |
| 301-350        | 1         | 4.76%   |
| 251-300        | 1         | 4.76%   |
| 201-250        | 1         | 4.76%   |
| 121-130        | 1         | 4.76%   |
| Unknown        | 1         | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 11        | 55%     |
| 101-120 | 4         | 20%     |
| 161-240 | 2         | 10%     |
| 51-100  | 2         | 10%     |
| Unknown | 1         | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 18        | 78.26%  |
| 0     | 3         | 13.04%  |
| 3     | 1         | 4.35%   |
| 2     | 1         | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 17        | 53.13%  |
| Realtek Semiconductor | 8         | 25%     |
| Qualcomm Atheros      | 4         | 12.5%   |
| Sierra Wireless       | 1         | 3.13%   |
| JMicron Technology    | 1         | 3.13%   |
| Edimax Technology     | 1         | 3.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 15.56%  |
| Intel Wireless 7260                                               | 3         | 6.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 4.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 4.44%   |
| Intel Wireless 8260                                               | 2         | 4.44%   |
| Intel Wireless 7265                                               | 2         | 4.44%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 4.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 4.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 4.44%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 4.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 4.44%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 4.44%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                     | 1         | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 2.22%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 2.22%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2.22%   |
| Intel Wireless-AC 9260                                            | 1         | 2.22%   |
| Intel WiFi Link 5100                                              | 1         | 2.22%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.22%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 2.22%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 2.22%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2.22%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 1         | 2.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 64%     |
| Qualcomm Atheros      | 4         | 16%     |
| Realtek Semiconductor | 3         | 12%     |
| Sierra Wireless       | 1         | 4%      |
| Edimax Technology     | 1         | 4%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 3         | 11.54%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 7.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 7.69%   |
| Intel Wireless 8260                                            | 2         | 7.69%   |
| Intel Wireless 7265                                            | 2         | 7.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 7.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 7.69%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 7.69%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 1         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 3.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 3.85%   |
| Intel Wireless-AC 9260                                         | 1         | 3.85%   |
| Intel WiFi Link 5100                                           | 1         | 3.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 3.85%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 10        | 52.63%  |
| Realtek Semiconductor | 8         | 42.11%  |
| JMicron Technology    | 1         | 5.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7         | 36.84%  |
| Intel Ethernet Connection I219-LM                                 | 2         | 10.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 10.53%  |
| Intel 82577LM Gigabit Network Connection                          | 2         | 10.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 5.26%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 5.26%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 5.26%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 5.26%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 5.26%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 5.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 22        | 53.66%  |
| Ethernet | 19        | 46.34%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 20        | 60.61%  |
| Ethernet | 13        | 39.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 17        | 73.91%  |
| 1     | 6         | 26.09%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 23        | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel              | 8         | 53.33%  |
| Hewlett-Packard    | 2         | 13.33%  |
| Broadcom           | 2         | 13.33%  |
| Lite-On Technology | 1         | 6.67%   |
| IMC Networks       | 1         | 6.67%   |
| Dell               | 1         | 6.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 6         | 40%     |
| Broadcom BCM2045B (BDC-2.1)                             | 2         | 13.33%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 1         | 6.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 1         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1         | 6.67%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 6.67%   |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 6.67%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter              | 1         | 6.67%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module             | 1         | 6.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 21        | 84%     |
| AMD    | 2         | 8%      |
| Nvidia | 1         | 4%      |
| Lenovo | 1         | 4%      |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 3         | 10%     |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 10%     |
| Intel 8 Series HD Audio Controller                                         | 3         | 10%     |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 10%     |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 10%     |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 6.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 6.67%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 3.33%   |
| Lenovo Realtek USB Audio                                                   | 1         | 3.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 3.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 3.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 3.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 3.33%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 3.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1         | 3.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 3.33%   |
| AMD High Definition Audio Controller                                       | 1         | 3.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 3.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 6         | 25%     |
| Samsung Electronics | 6         | 25%     |
| Micron Technology   | 3         | 12.5%   |
| Kingston            | 3         | 12.5%   |
| Elpida              | 2         | 8.33%   |
| Unknown             | 1         | 4.17%   |
| Toshiba             | 1         | 4.17%   |
| Corsair             | 1         | 4.17%   |
| Unknown             | 1         | 4.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 7.69%   |
| Unknown RAM Module 2GB SODIMM DDR3                        | 1         | 3.85%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 800MT/s      | 1         | 3.85%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 800MT/s       | 1         | 3.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 3.85%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s | 1         | 3.85%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 3.85%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s     | 1         | 3.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 1         | 3.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 1         | 3.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s     | 1         | 3.85%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s     | 1         | 3.85%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s    | 1         | 3.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 1         | 3.85%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s             | 1         | 3.85%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 1         | 3.85%   |
| Micron RAM 16KTF51264HZ-1G4M1 4GB SODIMM DDR3 1333MT/s    | 1         | 3.85%   |
| Kingston RAM Module 4GB SODIMM DDR4 2667MT/s              | 1         | 3.85%   |
| Kingston RAM ASU1333D3S9DR8/2G 2GB SODIMM DDR3 1333MT/s   | 1         | 3.85%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s   | 1         | 3.85%   |
| Elpida RAM Module 4GB SODIMM LPDDR3 1600MT/s              | 1         | 3.85%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s     | 1         | 3.85%   |
| Corsair RAM CMSO8GX3M1A1333C9 8GB SODIMM DDR3 1333MT/s    | 1         | 3.85%   |
| Unknown                                                   | 1         | 3.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 10        | 55.56%  |
| DDR4    | 6         | 33.33%  |
| LPDDR3  | 1         | 5.56%   |
| Unknown | 1         | 5.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 18        | 94.74%  |
| Chip   | 1         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 8         | 40%     |
| 8192  | 6         | 30%     |
| 2048  | 4         | 20%     |
| 16384 | 2         | 10%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 6         | 31.58%  |
| 2667    | 4         | 21.05%  |
| 1333    | 4         | 21.05%  |
| 3200    | 1         | 5.26%   |
| 2133    | 1         | 5.26%   |
| 1334    | 1         | 5.26%   |
| 800     | 1         | 5.26%   |
| Unknown | 1         | 5.26%   |

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
| Chicony Electronics   | 7         | 36.84%  |
| Acer                  | 3         | 15.79%  |
| Realtek Semiconductor | 2         | 10.53%  |
| IMC Networks          | 2         | 10.53%  |
| Suyin                 | 1         | 5.26%   |
| Quanta                | 1         | 5.26%   |
| Microdia              | 1         | 5.26%   |
| Logitech              | 1         | 5.26%   |
| Lenovo                | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Suyin Asus Integrated Webcam             | 1         | 5.26%   |
| Realtek Integrated_Webcam_HD             | 1         | 5.26%   |
| Realtek Front Camera                     | 1         | 5.26%   |
| Quanta VGA WebCam                        | 1         | 5.26%   |
| Microdia Integrated Webcam               | 1         | 5.26%   |
| Logitech Webcam C270                     | 1         | 5.26%   |
| Lenovo Integrated Webcam                 | 1         | 5.26%   |
| IMC Networks HP TrueVision HD Camera     | 1         | 5.26%   |
| IMC Networks EasyCamera                  | 1         | 5.26%   |
| Chicony USB2.0 HD UVC WebCam             | 1         | 5.26%   |
| Chicony USB 2.0 VGA UVC WebCam           | 1         | 5.26%   |
| Chicony ThinkPad T490 Webcam             | 1         | 5.26%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 1         | 5.26%   |
| Chicony Integrated HP HD Webcam          | 1         | 5.26%   |
| Chicony Integrated Camera                | 1         | 5.26%   |
| Chicony Camera                           | 1         | 5.26%   |
| Acer ThinkPad P50 Integrated Camera      | 1         | 5.26%   |
| Acer Integrated Camera                   | 1         | 5.26%   |
| Acer EasyCamera                          | 1         | 5.26%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 28.57%  |
| Upek             | 2         | 28.57%  |
| Synaptics        | 1         | 14.29%  |
| Broadcom         | 1         | 14.29%  |
| AuthenTec        | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 2         | 28.57%  |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 14.29%  |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| AuthenTec AES2810                                                            | 1         | 14.29%  |

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
| 2     | 11        | 45.83%  |
| 1     | 6         | 25%     |
| 3     | 3         | 12.5%   |
| 0     | 2         | 8.33%   |
| 5     | 1         | 4.17%   |
| 4     | 1         | 4.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 20        | 48.78%  |
| Card reader              | 6         | 14.63%  |
| Fingerprint reader       | 5         | 12.2%   |
| Net/wireless             | 2         | 4.88%   |
| Graphics card            | 2         | 4.88%   |
| Firewire controller      | 2         | 4.88%   |
| Storage/ata              | 1         | 2.44%   |
| Sound                    | 1         | 2.44%   |
| Network                  | 1         | 2.44%   |
| Bluetooth                | 1         | 2.44%   |

