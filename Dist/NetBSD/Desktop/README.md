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

Total: 49

| Vendor   | Model                   | Probe                                                     | Date         |
|----------|-------------------------|-----------------------------------------------------------|--------------|
| Acer     | Revo RN86               | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| Unknown  | Unknown                 | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Unknown  | Unknown                 | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| Unknown  | Unknown                 | [5e2f93a960](https://bsd-hardware.info/?probe=5e2f93a960) | Aug 06, 2022 |
| Unknown  | Unknown                 | [66fefba790](https://bsd-hardware.info/?probe=66fefba790) | Aug 06, 2022 |
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
| NetBSD 9.2        | 8        | 19.51%  |
| NetBSD 9.1        | 7        | 17.07%  |
| NetBSD 9.0_STABLE | 5        | 12.2%   |
| NetBSD 9.1_STABLE | 3        | 7.32%   |
| NetBSD 9.99.94    | 2        | 4.88%   |
| NetBSD 9.99.93    | 2        | 4.88%   |
| NetBSD 9.99.77    | 2        | 4.88%   |
| NetBSD 9.0        | 2        | 4.88%   |
| NetBSD 9.99.85    | 1        | 2.44%   |
| NetBSD 9.99.81    | 1        | 2.44%   |
| NetBSD 9.99.74    | 1        | 2.44%   |
| NetBSD 9.99.71    | 1        | 2.44%   |
| NetBSD 9.99.61    | 1        | 2.44%   |
| NetBSD 9.99.23    | 1        | 2.44%   |
| NetBSD 9.99.107   | 1        | 2.44%   |
| NetBSD 9.3_STABLE | 1        | 2.44%   |
| NetBSD 9.3        | 1        | 2.44%   |
| NetBSD 9.2_STABLE | 1        | 2.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| NetBSD | 35       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| amd64  | 29       | 82.86%  |
| evbarm | 5        | 14.29%  |
| i386   | 1        | 2.86%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 13       | 36.11%  |
| helloDesktop | 8        | 22.22%  |
| XFCE         | 7        | 19.44%  |
| Fluxbox      | 2        | 5.56%   |
| Xfwm4        | 1        | 2.78%   |
| Ratpoison    | 1        | 2.78%   |
| PekWM        | 1        | 2.78%   |
| MATE         | 1        | 2.78%   |
| DWM          | 1        | 2.78%   |
| CTWM         | 1        | 2.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 24       | 68.57%  |
| Console | 11       | 31.43%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 32       | 91.43%  |
| XDM     | 1        | 2.86%   |
| LightDM | 1        | 2.86%   |
| GDM     | 1        | 2.86%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 73.68%  |
| en_US   | 3        | 7.89%   |
| ru_RU   | 2        | 5.26%   |
| fi_FI   | 2        | 5.26%   |
| hu_HU   | 1        | 2.63%   |
| en_GB   | 1        | 2.63%   |
| C       | 1        | 2.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 33       | 94.29%  |
| EFI  | 2        | 5.71%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 34       | 97.14%  |
| Unknown | 1        | 2.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 24       | 68.57%  |
| Unknown | 11       | 31.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 15       | 42.86%  |
| ASUSTek Computer    | 6        | 17.14%  |
| Gigabyte Technology | 5        | 14.29%  |
| ASRock              | 3        | 8.57%   |
| MSI                 | 2        | 5.71%   |
| KLLISRE             | 1        | 2.86%   |
| Intel               | 1        | 2.86%   |
| Hewlett-Packard     | 1        | 2.86%   |
| Acer                | 1        | 2.86%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 15       | 42.86%  |
| ASUS PRIME A320M-K         | 2        | 5.71%   |
| MSI MS-7B86                | 1        | 2.86%   |
| MSI MS-7551                | 1        | 2.86%   |
| KLLISRE X99-B5 V1.0        | 1        | 2.86%   |
| Intel DN2820FYK H24582-203 | 1        | 2.86%   |
| HP Vectra                  | 1        | 2.86%   |
| Gigabyte Z170X-Gaming 3    | 1        | 2.86%   |
| Gigabyte X570 AORUS PRO    | 1        | 2.86%   |
| Gigabyte P75-D3            | 1        | 2.86%   |
| Gigabyte H61M-S2PV         | 1        | 2.86%   |
| Gigabyte 970A-D3P          | 1        | 2.86%   |
| ASUS TUF B450-PLUS GAMING  | 1        | 2.86%   |
| ASUS E45M1-I DELUXE        | 1        | 2.86%   |
| ASUS B150M-K               | 1        | 2.86%   |
| ASUS All Series            | 1        | 2.86%   |
| ASRock X470 Gaming-ITX/ac  | 1        | 2.86%   |
| ASRock N68-VS3 UCC         | 1        | 2.86%   |
| ASRock 970 Extreme3        | 1        | 2.86%   |
| Acer Revo RN86             | 1        | 2.86%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Unknown               | 15       | 42.86%  |
| ASUS PRIME            | 2        | 5.71%   |
| MSI MS-7B86           | 1        | 2.86%   |
| MSI MS-7551           | 1        | 2.86%   |
| KLLISRE X99-B5        | 1        | 2.86%   |
| Intel DN2820FYK       | 1        | 2.86%   |
| HP Vectra             | 1        | 2.86%   |
| Gigabyte Z170X-Gaming | 1        | 2.86%   |
| Gigabyte X570         | 1        | 2.86%   |
| Gigabyte P75-D3       | 1        | 2.86%   |
| Gigabyte H61M-S2PV    | 1        | 2.86%   |
| Gigabyte 970A-D3P     | 1        | 2.86%   |
| ASUS TUF              | 1        | 2.86%   |
| ASUS E45M1-I          | 1        | 2.86%   |
| ASUS B150M-K          | 1        | 2.86%   |
| ASUS All              | 1        | 2.86%   |
| ASRock X470           | 1        | 2.86%   |
| ASRock N68-VS3        | 1        | 2.86%   |
| ASRock 970            | 1        | 2.86%   |
| Acer Revo             | 1        | 2.86%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 14       | 40%     |
| 2020    | 5        | 14.29%  |
| 2013    | 3        | 8.57%   |
| 2018    | 2        | 5.71%   |
| 2017    | 2        | 5.71%   |
| 2014    | 2        | 5.71%   |
| 2021    | 1        | 2.86%   |
| 2019    | 1        | 2.86%   |
| 2015    | 1        | 2.86%   |
| 2012    | 1        | 2.86%   |
| 2011    | 1        | 2.86%   |
| 2010    | 1        | 2.86%   |
| 2001    | 1        | 2.86%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 35       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 35       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 8        | 22.86%  |
| 16.01-24.0  | 8        | 22.86%  |
| 8.01-16.0   | 5        | 14.29%  |
| 32.01-64.0  | 3        | 8.57%   |
| 3.01-4.0    | 3        | 8.57%   |
| 1.01-2.0    | 2        | 5.71%   |
| 0.51-1.0    | 2        | 5.71%   |
| 0.01-0.5    | 2        | 5.71%   |
| 24.01-32.0  | 1        | 2.86%   |
| 64.01-256.0 | 1        | 2.86%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| Unknown | 35       | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 0      | 15       | 39.47%  |
| 1      | 11       | 28.95%  |
| 2      | 9        | 23.68%  |
| 3      | 2        | 5.26%   |
| 4      | 1        | 2.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 35       | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 28       | 80%     |
| No        | 7        | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 23       | 65.71%  |
| Yes       | 12       | 34.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 27       | 77.14%  |
| Yes       | 8        | 22.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 7        | 20%     |
| USA          | 4        | 11.43%  |
| Germany      | 4        | 11.43%  |
| UK           | 3        | 8.57%   |
| Italy        | 2        | 5.71%   |
| Hungary      | 2        | 5.71%   |
| France       | 2        | 5.71%   |
| Finland      | 2        | 5.71%   |
| Spain        | 1        | 2.86%   |
| Saudi Arabia | 1        | 2.86%   |
| Romania      | 1        | 2.86%   |
| Poland       | 1        | 2.86%   |
| Netherlands  | 1        | 2.86%   |
| Latvia       | 1        | 2.86%   |
| Czechia      | 1        | 2.86%   |
| Brazil       | 1        | 2.86%   |
| Australia    | 1        | 2.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Ozersk                | 4        | 11.43%  |
| Tampere               | 2        | 5.71%   |
| Moscow                | 2        | 5.71%   |
| Lille                 | 2        | 5.71%   |
| Urupes                | 1        | 2.86%   |
| Unterhaching          | 1        | 2.86%   |
| Ulan-Ude              | 1        | 2.86%   |
| Turin                 | 1        | 2.86%   |
| Sydney                | 1        | 2.86%   |
| Stourbridge           | 1        | 2.86%   |
| Sopron                | 1        | 2.86%   |
| Royal Tunbridge Wells | 1        | 2.86%   |
| Rome                  | 1        | 2.86%   |
| Riyadh                | 1        | 2.86%   |
| Riga                  | 1        | 2.86%   |
| Reno                  | 1        | 2.86%   |
| Prague                | 1        | 2.86%   |
| Poznan                | 1        | 2.86%   |
| Portland              | 1        | 2.86%   |
| Murcia                | 1        | 2.86%   |
| Lohr a. Main          | 1        | 2.86%   |
| Hamilton              | 1        | 2.86%   |
| Gardony               | 1        | 2.86%   |
| Fort Wayne            | 1        | 2.86%   |
| Bucharest             | 1        | 2.86%   |
| Bloomsbury            | 1        | 2.86%   |
| Berlin                | 1        | 2.86%   |
| Amersfoort            | 1        | 2.86%   |
| Aachen                | 1        | 2.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 23.53%  |
| Toshiba             | 4        | 6      | 11.76%  |
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
| Toshiba             | 4        | 6      | 18.18%  |
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
| HDD  | 16       | 26     | 57.14%  |
| SSD  | 12       | 16     | 42.86%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 22       | 42     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 21       | 27     | 67.74%  |
| 0.51-1.0   | 8        | 11     | 25.81%  |
| 1.01-2.0   | 2        | 4      | 6.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 12       | 34.29%  |
| 251-500    | 5        | 14.29%  |
| 501-1000   | 5        | 14.29%  |
| 1-20       | 4        | 11.43%  |
| 51-100     | 4        | 11.43%  |
| 2001-3000  | 2        | 5.71%   |
| 1001-2000  | 2        | 5.71%   |
| 21-50      | 1        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 26       | 65%     |
| 21-50     | 6        | 15%     |
| 51-100    | 3        | 7.5%    |
| 1001-2000 | 2        | 5%      |
| 251-500   | 1        | 2.5%    |
| 101-250   | 1        | 2.5%    |
| 501-1000  | 1        | 2.5%    |

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
| Works    | 17       | 32     | 62.96%  |
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
| Intel               | 17       | 42.5%   |
| AMD                 | 12       | 30%     |
| Silicon Motion      | 3        | 7.5%    |
| SanDisk             | 2        | 5%      |
| Samsung Electronics | 2        | 5%      |
| Phison Electronics  | 2        | 5%      |
| Nvidia              | 1        | 2.5%    |
| ASMedia Technology  | 1        | 2.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 14.58%  |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4        | 8.33%   |
| AMD 400 Series Chipset SATA Controller                                         | 4        | 8.33%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3        | 6.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3        | 6.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 6.25%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2        | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 4.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2        | 4.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 4.17%   |
| AMD FCH SATA Controller D                                                      | 2        | 4.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 2.08%   |
| Samsung NVMe SSD Controller 980                                                | 1        | 2.08%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 2.08%   |
| Phison E12 NVMe Controller                                                     | 1        | 2.08%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 2.08%   |
| Nvidia MCP61 IDE                                                               | 1        | 2.08%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 2.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1        | 2.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1        | 2.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1        | 2.08%   |
| Intel 82801AA IDE Controller                                                   | 1        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1        | 2.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 2.08%   |
| ASMedia ASM1061 SATA IDE Controller                                            | 1        | 2.08%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 28       | 66.67%  |
| NVMe | 9        | 21.43%  |
| IDE  | 5        | 11.9%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 18       | 51.43%  |
| AMD     | 12       | 34.29%  |
| Unknown | 3        | 8.57%   |
| Arm     | 2        | 5.71%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel 686-class                             | 9        | 25%     |
|                                             | 3        | 8.33%   |
| Arm Cortex-A53 r0p4 (v8-A)                  | 2        | 5.56%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz        | 1        | 2.78%   |
| Intel Pentium III                           | 1        | 2.78%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 2.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 2.78%   |
| Intel Core i5-9400T CPU @ 1.80GHz           | 1        | 2.78%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1        | 2.78%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1        | 2.78%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1        | 2.78%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 2.78%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1        | 2.78%   |
| AMD Sempron 145 Processor                   | 1        | 2.78%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1        | 2.78%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1        | 2.78%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1        | 2.78%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1        | 2.78%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1        | 2.78%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 1        | 2.78%   |
| AMD Phenom II X6 1055T Processor            | 1        | 2.78%   |
| AMD Phenom II X4 965 Processor              | 1        | 2.78%   |
| AMD FX-8350 Eight-Core Processor            | 1        | 2.78%   |
| AMD E-450 APU with Radeon HD Graphics       | 1        | 2.78%   |
| AMD 686-class                               | 1        | 2.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel 686-class   | 9        | 25%     |
| Other             | 5        | 13.89%  |
| Intel Core i5     | 4        | 11.11%  |
| Intel Core i7     | 2        | 5.56%   |
| AMD Ryzen 5       | 2        | 5.56%   |
| AMD Ryzen 3       | 2        | 5.56%   |
| Intel Xeon        | 1        | 2.78%   |
| Intel Pentium III | 1        | 2.78%   |
| Intel Core i3     | 1        | 2.78%   |
| Intel Celeron     | 1        | 2.78%   |
| AMD Sempron       | 1        | 2.78%   |
| AMD Ryzen 9       | 1        | 2.78%   |
| AMD Ryzen 7       | 1        | 2.78%   |
| AMD Phenom II X6  | 1        | 2.78%   |
| AMD Phenom II X4  | 1        | 2.78%   |
| AMD FX            | 1        | 2.78%   |
| AMD E             | 1        | 2.78%   |
| AMD 686-class     | 1        | 2.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 58.33%  |
| 4       | 6        | 16.67%  |
| 8       | 3        | 8.33%   |
| 6       | 3        | 8.33%   |
| 2       | 2        | 5.56%   |
| 12      | 1        | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 20       | 55.56%  |
| Unknown | 16       | 44.44%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 21       | 58.33%  |
| 2       | 8        | 22.22%  |
| 1       | 7        | 19.44%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 17       | 47.22%  |
| Zen+        | 2        | 5.56%   |
| Zen 2       | 2        | 5.56%   |
| Zen         | 2        | 5.56%   |
| KabyLake    | 2        | 5.56%   |
| K10         | 2        | 5.56%   |
| Haswell     | 2        | 5.56%   |
| Skylake     | 1        | 2.78%   |
| Silvermont  | 1        | 2.78%   |
| SandyBridge | 1        | 2.78%   |
| Piledriver  | 1        | 2.78%   |
| P6          | 1        | 2.78%   |
| IvyBridge   | 1        | 2.78%   |
| Bobcat      | 1        | 2.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 14       | 41.18%  |
| AMD    | 13       | 38.24%  |
| Nvidia | 7        | 20.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3        | 8.57%   |
| Nvidia GF114 [GeForce GTX 560]                                            | 2        | 5.71%   |
| Intel HD Graphics 530                                                     | 2        | 5.71%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                      | 1        | 2.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1        | 2.86%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1        | 2.86%   |
| Nvidia G86 [GeForce 8500 GT]                                              | 1        | 2.86%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                   | 1        | 2.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 2.86%   |
| Intel JasperLake [UHD Graphics]                                           | 1        | 2.86%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 1        | 2.86%   |
| Intel Iris Graphics 6100                                                  | 1        | 2.86%   |
| Intel HD Graphics 630                                                     | 1        | 2.86%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 1        | 2.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 2.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1        | 2.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1        | 2.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1        | 2.86%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1        | 2.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1        | 2.86%   |
| AMD Wrestler [Radeon HD 6320]                                             | 1        | 2.86%   |
| AMD Tonga PRO [Radeon R9 285/380]                                         | 1        | 2.86%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                    | 1        | 2.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1        | 2.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1        | 2.86%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                            | 1        | 2.86%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 1        | 2.86%   |
| AMD Chelsea XT GL [FirePro M4000]                                         | 1        | 2.86%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 1        | 2.86%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                        | 1        | 2.86%   |
| AMD Caicos PRO [Radeon HD 7450]                                           | 1        | 2.86%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 11       | 31.43%  |
| 1 x AMD        | 10       | 28.57%  |
| 1 x Nvidia     | 6        | 17.14%  |
| Other          | 5        | 14.29%  |
| 2 x AMD        | 1        | 2.86%   |
| Intel + Nvidia | 1        | 2.86%   |
| Intel + AMD    | 1        | 2.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 23       | 62.16%  |
| Unknown | 14       | 37.84%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 20       | 55.56%  |
| 1.01-2.0   | 5        | 13.89%  |
| 3.01-4.0   | 4        | 11.11%  |
| 0.51-1.0   | 3        | 8.33%   |
| 0.01-0.5   | 3        | 8.33%   |
| 7.01-8.0   | 1        | 2.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 35.71%  |
| Goldstar            | 3        | 21.43%  |
| ViewSonic           | 1        | 7.14%   |
| Unknown (CDD)       | 1        | 7.14%   |
| LG Display          | 1        | 7.14%   |
| Impression          | 1        | 7.14%   |
| Apple               | 1        | 7.14%   |
| Acer                | 1        | 7.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 2        | 14.29%  |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch           | 1        | 7.14%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch              | 1        | 7.14%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch  | 1        | 7.14%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch  | 1        | 7.14%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch     | 1        | 7.14%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch           | 1        | 7.14%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1        | 7.14%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1        | 7.14%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 1        | 7.14%   |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                  | 1        | 7.14%   |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                 | 1        | 7.14%   |
| Acer SB220Q ACR06AB 1920x1080 480x270mm 21.7-inch                     | 1        | 7.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Desktops | Percent |
|------------------|----------|---------|
| 1920x1080 (FHD)  | 7        | 50%     |
| 1440x900 (WXGA+) | 3        | 21.43%  |
| 2560x1600        | 1        | 7.14%   |
| 2560x1080        | 1        | 7.14%   |
| 1600x1200        | 1        | 7.14%   |
| 1366x768 (WXGA)  | 1        | 7.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 19     | 3        | 21.43%  |
| 40     | 2        | 14.29%  |
| 23     | 2        | 14.29%  |
| 13     | 2        | 14.29%  |
| 52     | 1        | 7.14%   |
| 34     | 1        | 7.14%   |
| 27     | 1        | 7.14%   |
| 21     | 1        | 7.14%   |
| 20     | 1        | 7.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 5        | 35.71%  |
| 501-600     | 3        | 21.43%  |
| 801-900     | 2        | 14.29%  |
| 701-800     | 1        | 7.14%   |
| 301-350     | 1        | 7.14%   |
| 201-300     | 1        | 7.14%   |
| 1001-1500   | 1        | 7.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 8        | 57.14%  |
| 16/10 | 4        | 28.57%  |
| 4/3   | 1        | 7.14%   |
| 21/9  | 1        | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 4        | 28.57%  |
| 201-250        | 3        | 21.43%  |
| 81-90          | 2        | 14.29%  |
| 501-1000       | 2        | 14.29%  |
| More than 1000 | 1        | 7.14%   |
| 351-500        | 1        | 7.14%   |
| 301-350        | 1        | 7.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 10       | 71.43%  |
| 101-120 | 2        | 14.29%  |
| 1-50    | 1        | 7.14%   |
| 161-240 | 1        | 7.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 18       | 50%     |
| 1     | 17       | 47.22%  |
| 2     | 1        | 2.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 46.51%  |
| Intel                 | 11       | 25.58%  |
| Qualcomm Atheros      | 4        | 9.3%    |
| Huawei Technologies   | 2        | 4.65%   |
| Broadcom              | 2        | 4.65%   |
| Oculus VR             | 1        | 2.33%   |
| Netchip Technology    | 1        | 2.33%   |
| Mercucys              | 1        | 2.33%   |
| 3Com                  | 1        | 2.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 38%     |
| Intel I211 Gigabit Network Connection                             | 3        | 6%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 6%      |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 4%      |
| Huawei USB Composite Device                                       | 2        | 4%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1        | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 2%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1        | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1        | 2%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2%      |
| Oculus VR Rift S                                                  | 1        | 2%      |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                    | 1        | 2%      |
| Mercucys MERCUSYS Wireless USB Adapter                            | 1        | 2%      |
| Intel Wireless-AC 9260                                            | 1        | 2%      |
| Intel Wi-Fi 6 AX201 160MHz                                        | 1        | 2%      |
| Intel Wi-Fi 6 AX200                                               | 1        | 2%      |
| Intel Ethernet Connection I217-V                                  | 1        | 2%      |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2%      |
| Intel Centrino Ultimate-N 6300                                    | 1        | 2%      |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1        | 2%      |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 1        | 2%      |
| Broadcom BCM4331 802.11a/b/g/n                                    | 1        | 2%      |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1        | 2%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 5        | 38.46%  |
| Realtek Semiconductor | 3        | 23.08%  |
| Qualcomm Atheros      | 2        | 15.38%  |
| Broadcom              | 2        | 15.38%  |
| Mercucys              | 1        | 7.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Cannon Lake PCH CNVi WiFi                                | 2        | 15.38%  |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 7.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 7.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 7.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 7.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 7.69%   |
| Mercucys MERCUSYS Wireless USB Adapter                         | 1        | 7.69%   |
| Intel Wireless-AC 9260                                         | 1        | 7.69%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1        | 7.69%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 7.69%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1        | 7.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1        | 7.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 58.82%  |
| Intel                 | 8        | 23.53%  |
| Qualcomm Atheros      | 2        | 5.88%   |
| Huawei Technologies   | 2        | 5.88%   |
| Broadcom              | 1        | 2.94%   |
| 3Com                  | 1        | 2.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 19       | 55.88%  |
| Intel I211 Gigabit Network Connection                             | 3        | 8.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 8.82%   |
| Huawei USB Composite Device                                       | 2        | 5.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 2.94%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 2.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 2.94%   |
| Intel Ethernet Connection I217-V                                  | 1        | 2.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 2.94%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1        | 2.94%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1        | 2.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 30       | 65.22%  |
| WiFi     | 13       | 28.26%  |
| Modem    | 2        | 4.35%   |
| Unknown  | 1        | 2.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 27       | 93.1%   |
| WiFi     | 2        | 6.9%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 18       | 51.43%  |
| 2     | 8        | 22.86%  |
| 0     | 6        | 17.14%  |
| 3     | 3        | 8.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 29       | 80.56%  |
| Yes  | 7        | 19.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 4        | 50%     |
| Realtek Semiconductor | 2        | 25%     |
| Apple                 | 2        | 25%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3        | 37.5%   |
| Realtek  Bluetooth Adapter                     | 1        | 12.5%   |
| Realtek  Bluetooth 4.0 Adapter                 | 1        | 12.5%   |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 1        | 12.5%   |
| Apple Bluetooth Host Controller                | 1        | 12.5%   |
| Apple Apple Broadcom Built-in Bluetooth        | 1        | 12.5%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Intel               | 18       | 42.86%  |
| AMD                 | 15       | 35.71%  |
| Nvidia              | 4        | 9.52%   |
| Yamaha              | 1        | 2.38%   |
| Samsung Electronics | 1        | 2.38%   |
| Native Instruments  | 1        | 2.38%   |
| Logitech            | 1        | 2.38%   |
| ESS Technology      | 1        | 2.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 7.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4        | 7.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 7.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 5.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 3        | 5.56%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 5.56%   |
| Nvidia GF114 HDMI Audio Controller                                                | 2        | 3.7%    |
| Intel Cannon Lake PCH cAVS                                                        | 2        | 3.7%    |
| AMD Starship/Matisse HD Audio Controller                                          | 2        | 3.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2        | 3.7%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 3.7%    |
| Yamaha AG06/AG03                                                                  | 1        | 1.85%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                        | 1        | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 1        | 1.85%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1        | 1.85%   |
| Native Instruments Komplete Audio 1                                               | 1        | 1.85%   |
| Logitech Zone Wired Earbuds                                                       | 1        | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 1.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 1.85%   |
| Intel Jasper Lake HD Audio                                                        | 1        | 1.85%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 1.85%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 1.85%   |
| Intel 82801AA AC'97 Audio Controller                                              | 1        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1        | 1.85%   |
| ESS Technology ESS USB DAC                                                        | 1        | 1.85%   |
| AMD Wrestler HDMI Audio                                                           | 1        | 1.85%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                          | 1        | 1.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1        | 1.85%   |
| AMD High Definition Audio Controller                                              | 1        | 1.85%   |
| AMD Family 17h/19h HD Audio Controller                                            | 1        | 1.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1        | 1.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 1        | 1.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 1        | 1.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Kingston          | 6        | 27.27%  |
| Crucial           | 4        | 18.18%  |
| Unknown           | 3        | 13.64%  |
| G.Skill           | 3        | 13.64%  |
| Patriot           | 2        | 9.09%   |
| Corsair           | 2        | 9.09%   |
| Micron Technology | 1        | 4.55%   |
| A-DATA Technology | 1        | 4.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 8192MB DIMM 400MT/s                | 1        | 4%      |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 1        | 4%      |
| Unknown RAM Module 2048MB DIMM 400MT/s                | 1        | 4%      |
| Unknown RAM Module 128MB DIMM DRAM                    | 1        | 4%      |
| Patriot RAM PSD44G213382 4096MB DIMM DDR4 2133MT/s    | 1        | 4%      |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s        | 1        | 4%      |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s  | 1        | 4%      |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s     | 1        | 4%      |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s   | 1        | 4%      |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s | 1        | 4%      |
| Kingston RAM ACR16D3LS1KFG/4G 4GB DIMM DDR3 1600MT/s  | 1        | 4%      |
| Kingston RAM 99U5701-077.A00G 16GB DIMM DDR4 2667MT/s | 1        | 4%      |
| Kingston RAM 99U5471-028.A00LF 4GB DIMM DDR3 667MT/s  | 1        | 4%      |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1333MT/s | 1        | 4%      |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s  | 1        | 4%      |
| G.Skill RAM F4-2800C17-8GVR 8192MB DIMM DDR4 2133MT/s | 1        | 4%      |
| G.Skill RAM F3-1600C11-8G 8GB DIMM DDR3 1600MT/s      | 1        | 4%      |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s  | 1        | 4%      |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s | 1        | 4%      |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s | 1        | 4%      |
| Crucial RAM BLS4G4D240FSE.8FBD 4GB DIMM DDR4 2400MT/s | 1        | 4%      |
| Corsair RAM CMV8GX3M1A160 8GB DIMM DDR3 800MT/s       | 1        | 4%      |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s | 1        | 4%      |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s | 1        | 4%      |
| A-DATA RAM Module 8GB DIMM DDR4 2666MT/s              | 1        | 4%      |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 11       | 52.38%  |
| DDR3    | 7        | 33.33%  |
| DRAM    | 1        | 4.76%   |
| DDR2    | 1        | 4.76%   |
| Unknown | 1        | 4.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 20       | 95.24%  |
| SODIMM | 1        | 4.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 9        | 40.91%  |
| 4096  | 7        | 31.82%  |
| 16384 | 3        | 13.64%  |
| 2048  | 2        | 9.09%   |
| 128   | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 20.83%  |
| 2133    | 3        | 12.5%   |
| 3200    | 2        | 8.33%   |
| 2667    | 2        | 8.33%   |
| 2400    | 2        | 8.33%   |
| 1333    | 2        | 8.33%   |
| 800     | 2        | 8.33%   |
| 3000    | 1        | 4.17%   |
| 2933    | 1        | 4.17%   |
| 2666    | 1        | 4.17%   |
| 667     | 1        | 4.17%   |
| 400     | 1        | 4.17%   |
| Unknown | 1        | 4.17%   |

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
| Chicony Electronics | 2        | 50%     |
| Silicon Motion      | 1        | 25%     |
| ARC International   | 1        | 25%     |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Silicon Motion 300k Pixel Camera | 1        | 25%     |
| Chicony USB2.0 VGA UVC WebCam    | 1        | 25%     |
| Chicony HP HD Webcam [Fixed]     | 1        | 25%     |
| ARC International Camera         | 1        | 25%     |

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
| 0     | 16       | 44.44%  |
| 1     | 11       | 30.56%  |
| 3     | 5        | 13.89%  |
| 2     | 3        | 8.33%   |
| 5     | 1        | 2.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 15       | 46.88%  |
| Net/wireless             | 10       | 31.25%  |
| Card reader              | 2        | 6.25%   |
| Wireless                 | 1        | 3.13%   |
| Storage                  | 1        | 3.13%   |
| Net/ethernet             | 1        | 3.13%   |
| Graphics card            | 1        | 3.13%   |
| Bluetooth                | 1        | 3.13%   |

