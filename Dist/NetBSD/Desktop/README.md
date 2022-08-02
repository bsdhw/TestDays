NetBSD - Tested Hardware & Statistics (Desktops)
------------------------------------------------

A project to collect tested hardware configurations for NetBSD.

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

Total: 46

| Vendor   | Model                   | Probe                                                     | Date         |
|----------|-------------------------|-----------------------------------------------------------|--------------|
| ASUSTek  | TUF B450-PLUS GAMING    | [aeee3a91e6](https://bsd-hardware.info/?probe=aeee3a91e6) | Jul 03, 2022 |
| Gigabyte | X570 AORUS PRO          | [4e7d57df3b](https://bsd-hardware.info/?probe=4e7d57df3b) | Apr 18, 2022 |
| Gigabyte | 970A-D3P                | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| KLLISRE  | X99-B5 V1.0             | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| ASRock   | X470 Gaming-ITX/ac      | [18eeaf2963](https://bsd-hardware.info/?probe=18eeaf2963) | Dec 29, 2021 |
| Acer     | Revo RN86               | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| ASRock   | 970 Extreme3            | [14907c62f1](https://bsd-hardware.info/?probe=14907c62f1) | Dec 04, 2021 |
| HP       | 3397                    | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| ASUSTek  | ROG STRIX X470-F GAMING | [7259ec87e9](https://bsd-hardware.info/?probe=7259ec87e9) | Oct 05, 2021 |
| ASUSTek  | PRIME A320M-K           | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASUSTek  | ROG STRIX X470-F GAMING | [b3a18fcab3](https://bsd-hardware.info/?probe=b3a18fcab3) | Sep 29, 2021 |
| Unknown  | Unknown                 | [2a56bcb7c1](https://bsd-hardware.info/?probe=2a56bcb7c1) | Sep 19, 2021 |
| MSI      | B450-A PRO MAX          | [4e3b1f226b](https://bsd-hardware.info/?probe=4e3b1f226b) | Jun 22, 2021 |
| Unknown  | Unknown                 | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Acer     | Revo RN86               | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
| Unknown  | Unknown                 | [364a778de1](https://bsd-hardware.info/?probe=364a778de1) | May 14, 2021 |
| ASRock   | X470 Gaming-ITX/ac      | [82e63b3fb9](https://bsd-hardware.info/?probe=82e63b3fb9) | Apr 14, 2021 |
| Unknown  | Unknown                 | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown  | Unknown                 | [de8a18ca09](https://bsd-hardware.info/?probe=de8a18ca09) | Apr 08, 2021 |
| Unknown  | Unknown                 | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| Unknown  | Unknown                 | [0541b120c2](https://bsd-hardware.info/?probe=0541b120c2) | Apr 02, 2021 |
| Unknown  | Unknown                 | [91dd02d436](https://bsd-hardware.info/?probe=91dd02d436) | Mar 30, 2021 |
| Unknown  | Unknown                 | [a1220fba93](https://bsd-hardware.info/?probe=a1220fba93) | Mar 24, 2021 |
| Unknown  | Unknown                 | [edea2d1a64](https://bsd-hardware.info/?probe=edea2d1a64) | Mar 18, 2021 |
| Unknown  | Unknown                 | [1afd7d4381](https://bsd-hardware.info/?probe=1afd7d4381) | Feb 27, 2021 |
| Unknown  | Unknown                 | [4c0171bc04](https://bsd-hardware.info/?probe=4c0171bc04) | Feb 25, 2021 |
| Unknown  | Unknown                 | [a5fa760573](https://bsd-hardware.info/?probe=a5fa760573) | Jan 02, 2021 |
| ASRock   | N68-VS3 UCC             | [647ab5967e](https://bsd-hardware.info/?probe=647ab5967e) | Dec 22, 2020 |
| Unknown  | Unknown                 | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| ASUSTek  | E45M1-I DELUXE          | [8e767b517d](https://bsd-hardware.info/?probe=8e767b517d) | Dec 16, 2020 |
| Unknown  | Unknown                 | [153be3caa3](https://bsd-hardware.info/?probe=153be3caa3) | Nov 28, 2020 |
| HP       | System Board R3A        | [80593fc3da](https://bsd-hardware.info/?probe=80593fc3da) | Nov 03, 2020 |
| Gigabyte | Z170X-Gaming 3          | [615ac68e50](https://bsd-hardware.info/?probe=615ac68e50) | Oct 29, 2020 |
| Unknown  | Unknown                 | [d08d610bd0](https://bsd-hardware.info/?probe=d08d610bd0) | Oct 29, 2020 |
| ASUSTek  | B150M-K                 | [135db0e455](https://bsd-hardware.info/?probe=135db0e455) | Oct 22, 2020 |
| Unknown  | Unknown                 | [223aa9e0a3](https://bsd-hardware.info/?probe=223aa9e0a3) | Oct 22, 2020 |
| Gigabyte | P75-D3                  | [980218cf46](https://bsd-hardware.info/?probe=980218cf46) | Oct 02, 2020 |
| ASUSTek  | H81M-D PLUS             | [95b75130f4](https://bsd-hardware.info/?probe=95b75130f4) | Sep 26, 2020 |
| Acer     | Revo RN86               | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek  | H81M-D PLUS             | [036d9cfecb](https://bsd-hardware.info/?probe=036d9cfecb) | Sep 19, 2020 |
| ASUSTek  | H81M-D PLUS             | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| MSI      | KA790GX                 | [bba5499a4b](https://bsd-hardware.info/?probe=bba5499a4b) | Aug 29, 2020 |
| ASUSTek  | PRIME A320M-K           | [a49cf5c20b](https://bsd-hardware.info/?probe=a49cf5c20b) | May 28, 2020 |
| Gigabyte | H61M-S2PV               | [14e00aa09f](https://bsd-hardware.info/?probe=14e00aa09f) | May 25, 2020 |
| Intel    | DN2820FYK H24582-203    | [6cb240a9f6](https://bsd-hardware.info/?probe=6cb240a9f6) | May 25, 2020 |
| Unknown  | Unknown                 | [d3ad2b17ed](https://bsd-hardware.info/?probe=d3ad2b17ed) | May 22, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| NetBSD 9.2        | 7        | 19.44%  |
| NetBSD 9.1        | 6        | 16.67%  |
| NetBSD 9.0_STABLE | 5        | 13.89%  |
| NetBSD 9.1_STABLE | 3        | 8.33%   |
| NetBSD 9.99.94    | 2        | 5.56%   |
| NetBSD 9.99.93    | 2        | 5.56%   |
| NetBSD 9.99.77    | 2        | 5.56%   |
| NetBSD 9.0        | 2        | 5.56%   |
| NetBSD 9.99.85    | 1        | 2.78%   |
| NetBSD 9.99.81    | 1        | 2.78%   |
| NetBSD 9.99.74    | 1        | 2.78%   |
| NetBSD 9.99.71    | 1        | 2.78%   |
| NetBSD 9.99.61    | 1        | 2.78%   |
| NetBSD 9.99.23    | 1        | 2.78%   |
| NetBSD 9.2_STABLE | 1        | 2.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| NetBSD | 32       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 26       | 81.25%  |
| evbarm | 5        | 15.63%  |
| i386   | 1        | 3.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 13       | 39.39%  |
| XFCE         | 6        | 18.18%  |
| helloDesktop | 6        | 18.18%  |
| Fluxbox      | 2        | 6.06%   |
| Xfwm4        | 1        | 3.03%   |
| Ratpoison    | 1        | 3.03%   |
| PekWM        | 1        | 3.03%   |
| MATE         | 1        | 3.03%   |
| DWM          | 1        | 3.03%   |
| CTWM         | 1        | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 21       | 65.63%  |
| Console | 11       | 34.38%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 29       | 90.63%  |
| XDM     | 1        | 3.13%   |
| LightDM | 1        | 3.13%   |
| GDM     | 1        | 3.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 24       | 72.73%  |
| en_US   | 3        | 9.09%   |
| ru_RU   | 2        | 6.06%   |
| fi_FI   | 2        | 6.06%   |
| hu_HU   | 1        | 3.03%   |
| en_GB   | 1        | 3.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 30       | 93.75%  |
| EFI  | 2        | 6.25%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 31       | 96.88%  |
| Unknown | 1        | 3.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 21       | 65.63%  |
| Unknown | 11       | 34.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 12       | 37.5%   |
| ASUSTek Computer    | 6        | 18.75%  |
| Gigabyte Technology | 5        | 15.63%  |
| ASRock              | 3        | 9.38%   |
| MSI                 | 2        | 6.25%   |
| KLLISRE             | 1        | 3.13%   |
| Intel               | 1        | 3.13%   |
| Hewlett-Packard     | 1        | 3.13%   |
| Acer                | 1        | 3.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 12       | 37.5%   |
| ASUS PRIME A320M-K         | 2        | 6.25%   |
| MSI MS-7B86                | 1        | 3.13%   |
| MSI MS-7551                | 1        | 3.13%   |
| KLLISRE X99-B5 V1.0        | 1        | 3.13%   |
| Intel DN2820FYK H24582-203 | 1        | 3.13%   |
| HP Vectra                  | 1        | 3.13%   |
| Gigabyte Z170X-Gaming 3    | 1        | 3.13%   |
| Gigabyte X570 AORUS PRO    | 1        | 3.13%   |
| Gigabyte P75-D3            | 1        | 3.13%   |
| Gigabyte H61M-S2PV         | 1        | 3.13%   |
| Gigabyte 970A-D3P          | 1        | 3.13%   |
| ASUS TUF B450-PLUS GAMING  | 1        | 3.13%   |
| ASUS E45M1-I DELUXE        | 1        | 3.13%   |
| ASUS B150M-K               | 1        | 3.13%   |
| ASUS All Series            | 1        | 3.13%   |
| ASRock X470 Gaming-ITX/ac  | 1        | 3.13%   |
| ASRock N68-VS3 UCC         | 1        | 3.13%   |
| ASRock 970 Extreme3        | 1        | 3.13%   |
| Acer Revo RN86             | 1        | 3.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Unknown               | 12       | 37.5%   |
| ASUS PRIME            | 2        | 6.25%   |
| MSI MS-7B86           | 1        | 3.13%   |
| MSI MS-7551           | 1        | 3.13%   |
| KLLISRE X99-B5        | 1        | 3.13%   |
| Intel DN2820FYK       | 1        | 3.13%   |
| HP Vectra             | 1        | 3.13%   |
| Gigabyte Z170X-Gaming | 1        | 3.13%   |
| Gigabyte X570         | 1        | 3.13%   |
| Gigabyte P75-D3       | 1        | 3.13%   |
| Gigabyte H61M-S2PV    | 1        | 3.13%   |
| Gigabyte 970A-D3P     | 1        | 3.13%   |
| ASUS TUF              | 1        | 3.13%   |
| ASUS E45M1-I          | 1        | 3.13%   |
| ASUS B150M-K          | 1        | 3.13%   |
| ASUS All              | 1        | 3.13%   |
| ASRock X470           | 1        | 3.13%   |
| ASRock N68-VS3        | 1        | 3.13%   |
| ASRock 970            | 1        | 3.13%   |
| Acer Revo             | 1        | 3.13%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 11       | 34.38%  |
| 2020    | 5        | 15.63%  |
| 2013    | 3        | 9.38%   |
| 2018    | 2        | 6.25%   |
| 2017    | 2        | 6.25%   |
| 2014    | 2        | 6.25%   |
| 2021    | 1        | 3.13%   |
| 2019    | 1        | 3.13%   |
| 2015    | 1        | 3.13%   |
| 2012    | 1        | 3.13%   |
| 2011    | 1        | 3.13%   |
| 2010    | 1        | 3.13%   |
| 2001    | 1        | 3.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 32       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 32       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 7        | 21.88%  |
| 4.01-8.0    | 6        | 18.75%  |
| 8.01-16.0   | 5        | 15.63%  |
| 32.01-64.0  | 3        | 9.38%   |
| 3.01-4.0    | 3        | 9.38%   |
| 1.01-2.0    | 2        | 6.25%   |
| 0.51-1.0    | 2        | 6.25%   |
| 0.01-0.5    | 2        | 6.25%   |
| 24.01-32.0  | 1        | 3.13%   |
| 64.01-256.0 | 1        | 3.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| Unknown | 32       | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 11       | 32.35%  |
| 0      | 11       | 32.35%  |
| 2      | 9        | 26.47%  |
| 3      | 2        | 5.88%   |
| 4      | 1        | 2.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 32       | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 25       | 78.13%  |
| No        | 7        | 21.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 71.88%  |
| Yes       | 9        | 28.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 25       | 78.13%  |
| Yes       | 7        | 21.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 7        | 21.88%  |
| USA          | 4        | 12.5%   |
| UK           | 3        | 9.38%   |
| Germany      | 3        | 9.38%   |
| Italy        | 2        | 6.25%   |
| Hungary      | 2        | 6.25%   |
| Finland      | 2        | 6.25%   |
| Spain        | 1        | 3.13%   |
| Saudi Arabia | 1        | 3.13%   |
| Romania      | 1        | 3.13%   |
| Poland       | 1        | 3.13%   |
| Netherlands  | 1        | 3.13%   |
| Latvia       | 1        | 3.13%   |
| Czechia      | 1        | 3.13%   |
| Brazil       | 1        | 3.13%   |
| Australia    | 1        | 3.13%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Ozersk                | 4        | 12.5%   |
| Tampere               | 2        | 6.25%   |
| Moscow                | 2        | 6.25%   |
| Urupes                | 1        | 3.13%   |
| Unterhaching          | 1        | 3.13%   |
| Ulan-Ude              | 1        | 3.13%   |
| Turin                 | 1        | 3.13%   |
| Sydney                | 1        | 3.13%   |
| Stourbridge           | 1        | 3.13%   |
| Sopron                | 1        | 3.13%   |
| Royal Tunbridge Wells | 1        | 3.13%   |
| Rome                  | 1        | 3.13%   |
| Riyadh                | 1        | 3.13%   |
| Riga                  | 1        | 3.13%   |
| Reno                  | 1        | 3.13%   |
| Prague                | 1        | 3.13%   |
| Poznan                | 1        | 3.13%   |
| Portland              | 1        | 3.13%   |
| Murcia                | 1        | 3.13%   |
| Hamilton              | 1        | 3.13%   |
| Gardony               | 1        | 3.13%   |
| Fort Wayne            | 1        | 3.13%   |
| Bucharest             | 1        | 3.13%   |
| Bloomsbury            | 1        | 3.13%   |
| Berlin                | 1        | 3.13%   |
| Amersfoort            | 1        | 3.13%   |
| Aachen                | 1        | 3.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 23.53%  |
| Toshiba             | 4        | 5      | 11.76%  |
| Samsung Electronics | 4        | 4      | 11.76%  |
| SanDisk             | 3        | 4      | 8.82%   |
| Kingston            | 3        | 3      | 8.82%   |
| Seagate             | 2        | 2      | 5.88%   |
| Maxtor              | 2        | 2      | 5.88%   |
| SK hynix            | 1        | 2      | 2.94%   |
| Lexar               | 1        | 1      | 2.94%   |
| JetFlash            | 1        | 1      | 2.94%   |
| Intenso             | 1        | 1      | 2.94%   |
| Hewlett-Packard     | 1        | 1      | 2.94%   |
| Generic             | 1        | 1      | 2.94%   |
| Crucial             | 1        | 2      | 2.94%   |
| China               | 1        | 1      | 2.94%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB            | 3        | 8.57%   |
| Samsung SSD 860 EVO 500GB         | 2        | 5.71%   |
| Samsung HD103UJ 1TB               | 2        | 5.71%   |
| Maxtor STM3250310AS 250GB         | 2        | 5.71%   |
| Kingston DataTraveler 3.0 32GB    | 2        | 5.71%   |
| WDC WDS240G2G0A-00JH30 240GB      | 1        | 2.86%   |
| WDC WDS120G2G0A-00JH30 120GB      | 1        | 2.86%   |
| WDC WD5003AZEX-00K3CA0 500GB      | 1        | 2.86%   |
| WDC WD5000AAKX-753CA1 500GB       | 1        | 2.86%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1        | 2.86%   |
| WDC WD2502ABYS-01B7A0 256GB       | 1        | 2.86%   |
| WDC WD20EFRX-68EUZN0 2TB          | 1        | 2.86%   |
| WDC WD200EB-00BHF0 20GB           | 1        | 2.86%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 2.86%   |
| Toshiba DT01ACA200 2TB            | 1        | 2.86%   |
| SK hynix HFS128G39TND-N210A 128GB | 1        | 2.86%   |
| Seagate ST380011A 80GB            | 1        | 2.86%   |
| Seagate ST2000DL003-9VT166 2TB    | 1        | 2.86%   |
| SanDisk SDSSDH3512G 512GB         | 1        | 2.86%   |
| SanDisk Extreme SSD 250GB         | 1        | 2.86%   |
| SanDisk Cruzer Glide 16GB         | 1        | 2.86%   |
| Lexar USB Flash Drive 64GB        | 1        | 2.86%   |
| Kingston SA400S37480G 480GB       | 1        | 2.86%   |
| JetFlash Transcend 16GB           | 1        | 2.86%   |
| Intenso Rainbow Line 8GB          | 1        | 2.86%   |
| HP v100w 8GB                      | 1        | 2.86%   |
| Generic Flash Disk 2GB            | 1        | 2.86%   |
| Crucial CT1000BX500SSD1 1TB       | 1        | 2.86%   |
| China SATA SSD 120GB              | 1        | 2.86%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 9      | 31.82%  |
| Toshiba             | 4        | 5      | 18.18%  |
| Seagate             | 2        | 2      | 9.09%   |
| Samsung Electronics | 2        | 2      | 9.09%   |
| Maxtor              | 2        | 2      | 9.09%   |
| Lexar               | 1        | 1      | 4.55%   |
| JetFlash            | 1        | 1      | 4.55%   |
| Intenso             | 1        | 1      | 4.55%   |
| Hewlett-Packard     | 1        | 1      | 4.55%   |
| Generic             | 1        | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 3        | 4      | 23.08%  |
| Kingston            | 3        | 3      | 23.08%  |
| WDC                 | 2        | 2      | 15.38%  |
| Samsung Electronics | 2        | 2      | 15.38%  |
| SK hynix            | 1        | 2      | 7.69%   |
| Crucial             | 1        | 2      | 7.69%   |
| China               | 1        | 1      | 7.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 25     | 57.14%  |
| SSD  | 12       | 16     | 42.86%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 22       | 41     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 27     | 67.74%  |
| 0.51-1.0   | 8        | 10     | 25.81%  |
| 1.01-2.0   | 2        | 4      | 6.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 12       | 37.5%   |
| 251-500    | 4        | 12.5%   |
| 1-20       | 4        | 12.5%   |
| 501-1000   | 4        | 12.5%   |
| 51-100     | 4        | 12.5%   |
| 1001-2000  | 2        | 6.25%   |
| 21-50      | 1        | 3.13%   |
| 2001-3000  | 1        | 3.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 23       | 65.71%  |
| 21-50     | 4        | 11.43%  |
| 51-100    | 3        | 8.57%   |
| 1001-2000 | 2        | 5.71%   |
| 251-500   | 1        | 2.86%   |
| 101-250   | 1        | 2.86%   |
| 501-1000  | 1        | 2.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB      | 1        | 1      | 25%     |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 1      | 25%     |
| SK hynix HFS128G39TND-N210A 128GB | 1        | 1      | 25%     |
| Seagate ST2000DL003-9VT166 2TB    | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| WDC      | 2        | 2      | 50%     |
| SK hynix | 1        | 1      | 25%     |
| Seagate  | 1        | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 2        | 2      | 50%     |
| HDD  | 2        | 2      | 50%     |

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
| Works    | 17       | 31     | 62.96%  |
| Detected | 6        | 6      | 22.22%  |
| Malfunc  | 4        | 4      | 14.81%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 14       | 37.84%  |
| AMD                 | 12       | 32.43%  |
| Silicon Motion      | 3        | 8.11%   |
| SanDisk             | 2        | 5.41%   |
| Samsung Electronics | 2        | 5.41%   |
| Phison Electronics  | 2        | 5.41%   |
| Nvidia              | 1        | 2.7%    |
| ASMedia Technology  | 1        | 2.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 15.56%  |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 8.89%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 8.89%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3        | 6.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 6.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 4.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2        | 4.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2        | 4.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 4.44%   |
| AMD FCH SATA Controller D                                                      | 2        | 4.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 2.22%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 2.22%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 2.22%   |
| Phison E12 NVMe Controller                                                     | 1        | 2.22%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 2.22%   |
| Nvidia MCP61 IDE                                                               | 1        | 2.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 2.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1        | 2.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1        | 2.22%   |
| Intel 82801AA IDE Controller                                                   | 1        | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 2.22%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 2.22%   |
| ASMedia ASM1061 SATA IDE Controller                                            | 1        | 2.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 25       | 64.1%   |
| NVMe | 9        | 23.08%  |
| IDE  | 5        | 12.82%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 15       | 46.88%  |
| AMD     | 12       | 37.5%   |
| Unknown | 3        | 9.38%   |
| Arm     | 2        | 6.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel 686-class                             | 7        | 21.88%  |
|                                             | 3        | 9.38%   |
| Arm Cortex-A53 r0p4 (v8-A)                  | 2        | 6.25%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz        | 1        | 3.13%   |
| Intel Pentium III                           | 1        | 3.13%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 3.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 3.13%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 3.13%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 3.13%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 3.13%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1        | 3.13%   |
| AMD Sempron 145 Processor                   | 1        | 3.13%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 3.13%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 3.13%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 3.13%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1        | 3.13%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 3.13%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 1        | 3.13%   |
| AMD Phenom II X6 1055T Processor            | 1        | 3.13%   |
| AMD Phenom II X4 965 Processor              | 1        | 3.13%   |
| AMD FX-8350 Eight-Core Processor            | 1        | 3.13%   |
| AMD E-450 APU with Radeon HD Graphics       | 1        | 3.13%   |
| AMD 686-class                               | 1        | 3.13%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel 686-class   | 7        | 21.88%  |
| Other             | 5        | 15.63%  |
| Intel Core i7     | 2        | 6.25%   |
| Intel Core i5     | 2        | 6.25%   |
| AMD Ryzen 5       | 2        | 6.25%   |
| AMD Ryzen 3       | 2        | 6.25%   |
| Intel Xeon        | 1        | 3.13%   |
| Intel Pentium III | 1        | 3.13%   |
| Intel Core i3     | 1        | 3.13%   |
| Intel Celeron     | 1        | 3.13%   |
| AMD Sempron       | 1        | 3.13%   |
| AMD Ryzen 9       | 1        | 3.13%   |
| AMD Ryzen 7       | 1        | 3.13%   |
| AMD Phenom II X6  | 1        | 3.13%   |
| AMD Phenom II X4  | 1        | 3.13%   |
| AMD FX            | 1        | 3.13%   |
| AMD E             | 1        | 3.13%   |
| AMD 686-class     | 1        | 3.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 56.25%  |
| 4       | 6        | 18.75%  |
| 8       | 3        | 9.38%   |
| 6       | 2        | 6.25%   |
| 2       | 2        | 6.25%   |
| 12      | 1        | 3.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 19       | 59.38%  |
| Unknown | 13       | 40.63%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 18       | 56.25%  |
| 2       | 8        | 25%     |
| 1       | 6        | 18.75%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 14       | 43.75%  |
| Zen+        | 2        | 6.25%   |
| Zen 2       | 2        | 6.25%   |
| Zen         | 2        | 6.25%   |
| K10         | 2        | 6.25%   |
| Haswell     | 2        | 6.25%   |
| Skylake     | 1        | 3.13%   |
| Silvermont  | 1        | 3.13%   |
| SandyBridge | 1        | 3.13%   |
| Piledriver  | 1        | 3.13%   |
| P6          | 1        | 3.13%   |
| KabyLake    | 1        | 3.13%   |
| IvyBridge   | 1        | 3.13%   |
| Bobcat      | 1        | 3.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 13       | 41.94%  |
| Intel  | 11       | 35.48%  |
| Nvidia | 7        | 22.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3        | 9.38%   |
| Nvidia GF114 [GeForce GTX 560]                                            | 2        | 6.25%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                      | 1        | 3.13%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1        | 3.13%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1        | 3.13%   |
| Nvidia G86 [GeForce 8500 GT]                                              | 1        | 3.13%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                   | 1        | 3.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 3.13%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 1        | 3.13%   |
| Intel Iris Graphics 6100                                                  | 1        | 3.13%   |
| Intel HD Graphics 630                                                     | 1        | 3.13%   |
| Intel HD Graphics 530                                                     | 1        | 3.13%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 1        | 3.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 3.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1        | 3.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1        | 3.13%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1        | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 3.13%   |
| AMD Wrestler [Radeon HD 6320]                                             | 1        | 3.13%   |
| AMD Tonga PRO [Radeon R9 285/380]                                         | 1        | 3.13%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                    | 1        | 3.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1        | 3.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1        | 3.13%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                            | 1        | 3.13%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 1        | 3.13%   |
| AMD Chelsea XT GL [FirePro M4000]                                         | 1        | 3.13%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 1        | 3.13%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                        | 1        | 3.13%   |
| AMD Caicos PRO [Radeon HD 7450]                                           | 1        | 3.13%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 10       | 31.25%  |
| 1 x Intel      | 8        | 25%     |
| 1 x Nvidia     | 6        | 18.75%  |
| Other          | 5        | 15.63%  |
| 2 x AMD        | 1        | 3.13%   |
| Intel + Nvidia | 1        | 3.13%   |
| Intel + AMD    | 1        | 3.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 21       | 61.76%  |
| Unknown | 13       | 38.24%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 57.58%  |
| 1.01-2.0   | 4        | 12.12%  |
| 3.01-4.0   | 3        | 9.09%   |
| 0.51-1.0   | 3        | 9.09%   |
| 0.01-0.5   | 3        | 9.09%   |
| 7.01-8.0   | 1        | 3.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 38.46%  |
| Goldstar            | 3        | 23.08%  |
| ViewSonic           | 1        | 7.69%   |
| Unknown (CDD)       | 1        | 7.69%   |
| Impression          | 1        | 7.69%   |
| Apple               | 1        | 7.69%   |
| Acer                | 1        | 7.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 2        | 15.38%  |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch           | 1        | 7.69%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch              | 1        | 7.69%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch  | 1        | 7.69%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch  | 1        | 7.69%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch     | 1        | 7.69%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1        | 7.69%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1        | 7.69%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 1        | 7.69%   |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                  | 1        | 7.69%   |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                 | 1        | 7.69%   |
| Acer SB220Q ACR06AB 1920x1080 480x270mm 21.7-inch                     | 1        | 7.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 7        | 53.85%  |
| 1440x900 (WXGA+) | 3        | 23.08%  |
| 2560x1600        | 1        | 7.69%   |
| 2560x1080        | 1        | 7.69%   |
| 1600x1200        | 1        | 7.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 19     | 3        | 23.08%  |
| 40     | 2        | 15.38%  |
| 23     | 2        | 15.38%  |
| 52     | 1        | 7.69%   |
| 28     | 1        | 7.69%   |
| 27     | 1        | 7.69%   |
| 21     | 1        | 7.69%   |
| 20     | 1        | 7.69%   |
| 13     | 1        | 7.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 5        | 38.46%  |
| 501-600     | 3        | 23.08%  |
| 801-900     | 2        | 15.38%  |
| 601-700     | 1        | 7.69%   |
| 201-300     | 1        | 7.69%   |
| 1001-1500   | 1        | 7.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 7        | 53.85%  |
| 16/10 | 4        | 30.77%  |
| 4/3   | 1        | 7.69%   |
| 21/9  | 1        | 7.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 4        | 30.77%  |
| 201-250        | 3        | 23.08%  |
| 501-1000       | 2        | 15.38%  |
| More than 1000 | 1        | 7.69%   |
| 81-90          | 1        | 7.69%   |
| 301-350        | 1        | 7.69%   |
| 251-300        | 1        | 7.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 76.92%  |
| 1-50    | 1        | 7.69%   |
| 161-240 | 1        | 7.69%   |
| 101-120 | 1        | 7.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 17       | 51.52%  |
| 1     | 15       | 45.45%  |
| 2     | 1        | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 18       | 48.65%  |
| Intel                 | 8        | 21.62%  |
| Qualcomm Atheros      | 3        | 8.11%   |
| Huawei Technologies   | 2        | 5.41%   |
| Broadcom              | 2        | 5.41%   |
| Oculus VR             | 1        | 2.7%    |
| Netchip Technology    | 1        | 2.7%    |
| Mercucys              | 1        | 2.7%    |
| 3Com                  | 1        | 2.7%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17       | 39.53%  |
| Intel I211 Gigabit Network Connection                             | 3        | 6.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 6.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 4.65%   |
| Huawei USB Composite Device                                       | 2        | 4.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 2.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 2.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 2.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.33%   |
| Oculus VR Rift S                                                  | 1        | 2.33%   |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                    | 1        | 2.33%   |
| Mercucys MERCUSYS Wireless USB Adapter                            | 1        | 2.33%   |
| Intel Wireless-AC 9260                                            | 1        | 2.33%   |
| Intel Wi-Fi 6 AX200                                               | 1        | 2.33%   |
| Intel Centrino Ultimate-N 6300                                    | 1        | 2.33%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1        | 2.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1        | 2.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1        | 2.33%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1        | 2.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 40%     |
| Realtek Semiconductor | 2        | 20%     |
| Broadcom              | 2        | 20%     |
| Qualcomm Atheros      | 1        | 10%     |
| Mercucys              | 1        | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH CNVi WiFi                                | 2        | 20%     |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 10%     |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 10%     |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 10%     |
| Mercucys MERCUSYS Wireless USB Adapter                         | 1        | 10%     |
| Intel Wireless-AC 9260                                         | 1        | 10%     |
| Intel Wi-Fi 6 AX200                                            | 1        | 10%     |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1        | 10%     |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1        | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 18       | 60%     |
| Intel                 | 6        | 20%     |
| Qualcomm Atheros      | 2        | 6.67%   |
| Huawei Technologies   | 2        | 6.67%   |
| Broadcom              | 1        | 3.33%   |
| 3Com                  | 1        | 3.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17       | 56.67%  |
| Intel I211 Gigabit Network Connection                             | 3        | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 10%     |
| Huawei USB Composite Device                                       | 2        | 6.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 3.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 3.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 3.33%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1        | 3.33%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1        | 3.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 67.5%   |
| WiFi     | 10       | 25%     |
| Modem    | 2        | 5%      |
| Unknown  | 1        | 2.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 25       | 92.59%  |
| WiFi     | 2        | 7.41%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 56.25%  |
| 2     | 7        | 21.88%  |
| 0     | 6        | 18.75%  |
| 3     | 1        | 3.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 27       | 81.82%  |
| Yes  | 6        | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3        | 42.86%  |
| Realtek Semiconductor | 2        | 28.57%  |
| Apple                 | 2        | 28.57%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2        | 28.57%  |
| Realtek  Bluetooth Adapter                     | 1        | 14.29%  |
| Realtek  Bluetooth 4.0 Adapter                 | 1        | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1        | 14.29%  |
| Apple Bluetooth Host Controller                | 1        | 14.29%  |
| Apple Apple Broadcom Built-in Bluetooth        | 1        | 14.29%  |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 15       | 39.47%  |
| AMD                 | 15       | 39.47%  |
| Nvidia              | 4        | 10.53%  |
| Yamaha              | 1        | 2.63%   |
| Samsung Electronics | 1        | 2.63%   |
| Native Instruments  | 1        | 2.63%   |
| Logitech            | 1        | 2.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 8.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4        | 8.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 8.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 6.12%   |
| Nvidia GF114 HDMI Audio Controller                                                | 2        | 4.08%   |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 4.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 2        | 4.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2        | 4.08%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 4.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 4.08%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 4.08%   |
| Yamaha AG06/AG03                                                                  | 1        | 2.04%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                        | 1        | 2.04%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 2.04%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1        | 2.04%   |
| Native Instruments Komplete Audio 1                                               | 1        | 2.04%   |
| Logitech Zone Wired Earbuds                                                       | 1        | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 2.04%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 2.04%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 2.04%   |
| Intel 82801AA AC'97 Audio Controller                                              | 1        | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1        | 2.04%   |
| AMD Wrestler HDMI Audio                                                           | 1        | 2.04%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                          | 1        | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 2.04%   |
| AMD High Definition Audio Controller                                              | 1        | 2.04%   |
| AMD Family 17h/19h HD Audio Controller                                            | 1        | 2.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1        | 2.04%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 1        | 2.04%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 2.04%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Kingston          | 5        | 23.81%  |
| Crucial           | 4        | 19.05%  |
| Unknown           | 3        | 14.29%  |
| G.Skill           | 3        | 14.29%  |
| Patriot           | 2        | 9.52%   |
| Corsair           | 2        | 9.52%   |
| Micron Technology | 1        | 4.76%   |
| A-DATA Technology | 1        | 4.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 8192MB DIMM 400MT/s                | 1        | 4.17%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 1        | 4.17%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                | 1        | 4.17%   |
| Unknown RAM Module 128MB DIMM DRAM                    | 1        | 4.17%   |
| Patriot RAM PSD44G213382 4096MB DIMM DDR4 2133MT/s    | 1        | 4.17%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s        | 1        | 4.17%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s  | 1        | 4.17%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s     | 1        | 4.17%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s   | 1        | 4.17%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB DIMM DDR3 1600MT/s  | 1        | 4.17%   |
| Kingston RAM 99U5701-077.A00G 16GB DIMM DDR4 2667MT/s | 1        | 4.17%   |
| Kingston RAM 99U5471-028.A00LF 4GB DIMM DDR3 667MT/s  | 1        | 4.17%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1333MT/s | 1        | 4.17%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s  | 1        | 4.17%   |
| G.Skill RAM F4-2800C17-8GVR 8192MB DIMM DDR4 2133MT/s | 1        | 4.17%   |
| G.Skill RAM F3-1600C11-8G 8GB DIMM DDR3 1600MT/s      | 1        | 4.17%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s  | 1        | 4.17%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s | 1        | 4.17%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s | 1        | 4.17%   |
| Crucial RAM BLS4G4D240FSE.8FBD 4GB DIMM DDR4 2400MT/s | 1        | 4.17%   |
| Corsair RAM CMV8GX3M1A160 8GB DIMM DDR3 800MT/s       | 1        | 4.17%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s | 1        | 4.17%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 2933MT/s | 1        | 4.17%   |
| A-DATA RAM Module 8GB DIMM DDR4 2666MT/s              | 1        | 4.17%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 10       | 50%     |
| DDR3    | 7        | 35%     |
| DRAM    | 1        | 5%      |
| DDR2    | 1        | 5%      |
| Unknown | 1        | 5%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 20       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 8        | 38.1%   |
| 4096  | 7        | 33.33%  |
| 16384 | 3        | 14.29%  |
| 2048  | 2        | 9.52%   |
| 128   | 1        | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 21.74%  |
| 2133    | 3        | 13.04%  |
| 3200    | 2        | 8.7%    |
| 2933    | 2        | 8.7%    |
| 2400    | 2        | 8.7%    |
| 1333    | 2        | 8.7%    |
| 800     | 2        | 8.7%    |
| 2667    | 1        | 4.35%   |
| 2666    | 1        | 4.35%   |
| 667     | 1        | 4.35%   |
| 400     | 1        | 4.35%   |
| Unknown | 1        | 4.35%   |

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

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 210 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Silicon Motion      | 1        | 33.33%  |
| Chicony Electronics | 1        | 33.33%  |
| ARC International   | 1        | 33.33%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Silicon Motion 300k Pixel Camera | 1        | 33.33%  |
| Chicony USB2.0 VGA UVC WebCam    | 1        | 33.33%  |
| ARC International Camera         | 1        | 33.33%  |

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
| 0     | 16       | 48.48%  |
| 1     | 11       | 33.33%  |
| 3     | 3        | 9.09%   |
| 2     | 2        | 6.06%   |
| 5     | 1        | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 13       | 52%     |
| Net/wireless             | 7        | 28%     |
| Wireless                 | 1        | 4%      |
| Storage                  | 1        | 4%      |
| Graphics card            | 1        | 4%      |
| Card reader              | 1        | 4%      |
| Bluetooth                | 1        | 4%      |

