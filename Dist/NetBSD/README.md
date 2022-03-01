NetBSD - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for NetBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NetBSD/Desktop/README.md) and [notebooks](/Dist/NetBSD/Notebook/README.md).

Full-feature report is available here: https://bsd-hardware.info/?view=trends

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

| Vendor        | Model                    | Form-Factor | Probe                                                     | Date         |
|---------------|--------------------------|-------------|-----------------------------------------------------------|--------------|
| KLLISRE       | X99-B5 V1.0              | Desktop     | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| MiTAC         | 5033                     | Notebook    | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| ASRock        | X470 Gaming-ITX/ac       | Desktop     | [18eeaf2963](https://bsd-hardware.info/?probe=18eeaf2963) | Dec 29, 2021 |
| Unknown       | Unknown                  | Desktop     | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| ASRock        | 970 Extreme3             | Desktop     | [14907c62f1](https://bsd-hardware.info/?probe=14907c62f1) | Dec 04, 2021 |
| HP            | 3397                     | Desktop     | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| Lenovo        | ThinkPad T420 4236D26    | Notebook    | [5c64875424](https://bsd-hardware.info/?probe=5c64875424) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING  | Desktop     | [7259ec87e9](https://bsd-hardware.info/?probe=7259ec87e9) | Oct 05, 2021 |
| Unknown       | Unknown                  | Desktop     | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASUSTek       | PRIME A320M-K            | Desktop     | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING  | Desktop     | [b3a18fcab3](https://bsd-hardware.info/?probe=b3a18fcab3) | Sep 29, 2021 |
| Unknown       | Unknown                  | Desktop     | [2a56bcb7c1](https://bsd-hardware.info/?probe=2a56bcb7c1) | Sep 19, 2021 |
| Toshiba       | Satellite A100           | Notebook    | [9ccf97d62c](https://bsd-hardware.info/?probe=9ccf97d62c) | Sep 05, 2021 |
| MSI           | B450-A PRO MAX           | Desktop     | [4e3b1f226b](https://bsd-hardware.info/?probe=4e3b1f226b) | Jun 22, 2021 |
| Sony          | SVF1421DSGW              | Notebook    | [abadb65058](https://bsd-hardware.info/?probe=abadb65058) | Jun 01, 2021 |
| Unknown       | Unknown                  | Desktop     | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Unknown       | Unknown                  | Desktop     | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
| Unknown       | Unknown                  | Desktop     | [364a778de1](https://bsd-hardware.info/?probe=364a778de1) | May 14, 2021 |
| ASRock        | X470 Gaming-ITX/ac       | Desktop     | [82e63b3fb9](https://bsd-hardware.info/?probe=82e63b3fb9) | Apr 14, 2021 |
| Unknown       | Unknown                  | Desktop     | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown       | Unknown                  | Desktop     | [de8a18ca09](https://bsd-hardware.info/?probe=de8a18ca09) | Apr 08, 2021 |
| Unknown       | Unknown                  | Desktop     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| Unknown       | Unknown                  | Desktop     | [0541b120c2](https://bsd-hardware.info/?probe=0541b120c2) | Apr 02, 2021 |
| Unknown       | Unknown                  | Desktop     | [91dd02d436](https://bsd-hardware.info/?probe=91dd02d436) | Mar 30, 2021 |
| Unknown       | Unknown                  | Desktop     | [a1220fba93](https://bsd-hardware.info/?probe=a1220fba93) | Mar 24, 2021 |
| Unknown       | Unknown                  | Desktop     | [edea2d1a64](https://bsd-hardware.info/?probe=edea2d1a64) | Mar 18, 2021 |
| Apple         | MacBook2,1               | Notebook    | [360f29bf3b](https://bsd-hardware.info/?probe=360f29bf3b) | Mar 05, 2021 |
| Apple         | MacBook2,1               | Notebook    | [f6e7638f87](https://bsd-hardware.info/?probe=f6e7638f87) | Mar 05, 2021 |
| Unknown       | Unknown                  | Desktop     | [1afd7d4381](https://bsd-hardware.info/?probe=1afd7d4381) | Feb 27, 2021 |
| Unknown       | Unknown                  | Desktop     | [4c0171bc04](https://bsd-hardware.info/?probe=4c0171bc04) | Feb 25, 2021 |
| Unknown       | Unknown                  | Desktop     | [a5fa760573](https://bsd-hardware.info/?probe=a5fa760573) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG     | Notebook    | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG     | Notebook    | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Lenovo        | ThinkPad T430s 23564H3   | Notebook    | [eda02dc46b](https://bsd-hardware.info/?probe=eda02dc46b) | Dec 25, 2020 |
| Fujitsu Si... | AMILO L7310              | Notebook    | [0603b64315](https://bsd-hardware.info/?probe=0603b64315) | Dec 25, 2020 |
| ASRock        | N68-VS3 UCC              | Desktop     | [647ab5967e](https://bsd-hardware.info/?probe=647ab5967e) | Dec 22, 2020 |
| Unknown       | Unknown                  | Desktop     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| ASUSTek       | E45M1-I DELUXE           | Desktop     | [8e767b517d](https://bsd-hardware.info/?probe=8e767b517d) | Dec 16, 2020 |
| Unknown       | Unknown                  | Desktop     | [153be3caa3](https://bsd-hardware.info/?probe=153be3caa3) | Nov 28, 2020 |
| HP            | System Board R3A         | Desktop     | [80593fc3da](https://bsd-hardware.info/?probe=80593fc3da) | Nov 03, 2020 |
| Gigabyte      | Z170X-Gaming 3           | Desktop     | [615ac68e50](https://bsd-hardware.info/?probe=615ac68e50) | Oct 29, 2020 |
| Unknown       | Unknown                  | Desktop     | [d08d610bd0](https://bsd-hardware.info/?probe=d08d610bd0) | Oct 29, 2020 |
| Acer          | Aspire ES1-132           | Notebook    | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| ASUSTek       | B150M-K                  | Desktop     | [135db0e455](https://bsd-hardware.info/?probe=135db0e455) | Oct 22, 2020 |
| Unknown       | Unknown                  | Desktop     | [223aa9e0a3](https://bsd-hardware.info/?probe=223aa9e0a3) | Oct 22, 2020 |
| Gigabyte      | P75-D3                   | Desktop     | [980218cf46](https://bsd-hardware.info/?probe=980218cf46) | Oct 02, 2020 |
| ASUSTek       | H81M-D PLUS              | Desktop     | [95b75130f4](https://bsd-hardware.info/?probe=95b75130f4) | Sep 26, 2020 |
| Dell          | 0W7H8C A03               | Server      | [639b47e2ad](https://bsd-hardware.info/?probe=639b47e2ad) | Sep 21, 2020 |
| Unknown       | Unknown                  | Desktop     | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek       | H81M-D PLUS              | Desktop     | [036d9cfecb](https://bsd-hardware.info/?probe=036d9cfecb) | Sep 19, 2020 |
| ASUSTek       | H81M-D PLUS              | Desktop     | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| MSI           | KA790GX                  | Desktop     | [bba5499a4b](https://bsd-hardware.info/?probe=bba5499a4b) | Aug 29, 2020 |
| Lenovo        | ThinkPad T510 4313CTO    | Notebook    | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| eMachines     | eME642G                  | Notebook    | [42027dfbb9](https://bsd-hardware.info/?probe=42027dfbb9) | Jul 25, 2020 |
| Intel         | NUC7JYB J67969-404       | Mini pc     | [35c4a3608e](https://bsd-hardware.info/?probe=35c4a3608e) | Jul 19, 2020 |
| Unknown       | Unknown                  | Desktop     | [9fbca0a216](https://bsd-hardware.info/?probe=9fbca0a216) | Jun 17, 2020 |
| Lenovo        | G500 20236               | Notebook    | [99cf14c489](https://bsd-hardware.info/?probe=99cf14c489) | Jun 03, 2020 |
| ASUSTek       | PRIME A320M-K            | Desktop     | [a49cf5c20b](https://bsd-hardware.info/?probe=a49cf5c20b) | May 28, 2020 |
| Gigabyte      | H61M-S2PV                | Desktop     | [14e00aa09f](https://bsd-hardware.info/?probe=14e00aa09f) | May 25, 2020 |
| Intel         | DN2820FYK H24582-203     | Desktop     | [6cb240a9f6](https://bsd-hardware.info/?probe=6cb240a9f6) | May 25, 2020 |
| Unknown       | Unknown                  | Desktop     | [8ba62bd121](https://bsd-hardware.info/?probe=8ba62bd121) | May 25, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N | Notebook    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |
| Unknown       | Unknown                  | Desktop     | [d3ad2b17ed](https://bsd-hardware.info/?probe=d3ad2b17ed) | May 22, 2020 |
| Lenovo        | G570 20079               | Notebook    | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| ASUSTek       | A3L                      | Notebook    | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| Lenovo        | G570 20079               | Notebook    | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 35        | 76.09%  |
| i386   | 6         | 13.04%  |
| evbarm | 5         | 10.87%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 19        | 39.58%  |
| XFCE         | 10        | 20.83%  |
| helloDesktop | 4         | 8.33%   |
| Fluxbox      | 4         | 8.33%   |
| ctwm         | 3         | 6.25%   |
| MATE         | 2         | 4.17%   |
| dwm          | 2         | 4.17%   |
| Xfwm4        | 1         | 2.08%   |
| Ratpoison    | 1         | 2.08%   |
| PekWM        | 1         | 2.08%   |
| Awesome      | 1         | 2.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 31        | 67.39%  |
| Console | 15        | 32.61%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 41        | 89.13%  |
| XDM     | 2         | 4.35%   |
| GDM     | 2         | 4.35%   |
| LightDM | 1         | 2.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 34        | 72.34%  |
| en_US   | 7         | 14.89%  |
| ru_RU   | 2         | 4.26%   |
| fi_FI   | 2         | 4.26%   |
| hu_HU   | 1         | 2.13%   |
| en_GB   | 1         | 2.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 44        | 95.65%  |
| EFI  | 2         | 4.35%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 45        | 97.83%  |
| Unknown | 1         | 2.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 26        | 56.52%  |
| Unknown | 20        | 43.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 15        | 32.61%  |
| ASUSTek Computer    | 6         | 13.04%  |
| Lenovo              | 5         | 10.87%  |
| Gigabyte Technology | 3         | 6.52%   |
| ASRock              | 3         | 6.52%   |
| MSI                 | 2         | 4.35%   |
| Toshiba             | 1         | 2.17%   |
| Sony                | 1         | 2.17%   |
| MiTAC               | 1         | 2.17%   |
| KLLISRE             | 1         | 2.17%   |
| Intel               | 1         | 2.17%   |
| IBM                 | 1         | 2.17%   |
| Hewlett-Packard     | 1         | 2.17%   |
| Fujitsu Siemens     | 1         | 2.17%   |
| eMachines           | 1         | 2.17%   |
| Dell                | 1         | 2.17%   |
| Apple               | 1         | 2.17%   |
| Acer                | 1         | 2.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 15        | 32.61%  |
| ASUS PRIME A320M-K              | 2         | 4.35%   |
| Toshiba Satellite A100          | 1         | 2.17%   |
| Sony SVF1421DSGW                | 1         | 2.17%   |
| MSI MS-7B86                     | 1         | 2.17%   |
| MSI MS-7551                     | 1         | 2.17%   |
| MiTAC 5033                      | 1         | 2.17%   |
| Lenovo ThinkPad X240 20AMS0J01N | 1         | 2.17%   |
| Lenovo ThinkPad T510 4313CTO    | 1         | 2.17%   |
| Lenovo ThinkPad T430s 23564H3   | 1         | 2.17%   |
| Lenovo ThinkPad T420 4236D26    | 1         | 2.17%   |
| Lenovo G500 20236               | 1         | 2.17%   |
| KLLISRE X99-B5 V1.0             | 1         | 2.17%   |
| Intel DN2820FYK H24582-203      | 1         | 2.17%   |
| IBM ThinkPad R51 2887AVG        | 1         | 2.17%   |
| HP Vectra                       | 1         | 2.17%   |
| Gigabyte Z170X-Gaming 3         | 1         | 2.17%   |
| Gigabyte P75-D3                 | 1         | 2.17%   |
| Gigabyte H61M-S2PV              | 1         | 2.17%   |
| Fujitsu Siemens AMILO L7310     | 1         | 2.17%   |
| eMachines eME642G               | 1         | 2.17%   |
| Dell PowerEdge T320             | 1         | 2.17%   |
| ASUS E45M1-I DELUXE             | 1         | 2.17%   |
| ASUS B150M-K                    | 1         | 2.17%   |
| ASUS All Series                 | 1         | 2.17%   |
| ASUS A3L                        | 1         | 2.17%   |
| ASRock X470 Gaming-ITX/ac       | 1         | 2.17%   |
| ASRock N68-VS3 UCC              | 1         | 2.17%   |
| ASRock 970 Extreme3             | 1         | 2.17%   |
| Apple MacBook2,1                | 1         | 2.17%   |
| Acer Aspire ES1-132             | 1         | 2.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 15        | 32.61%  |
| Lenovo ThinkPad       | 4         | 8.7%    |
| ASUS PRIME            | 2         | 4.35%   |
| Toshiba Satellite     | 1         | 2.17%   |
| Sony SVF1421DSGW      | 1         | 2.17%   |
| MSI MS-7B86           | 1         | 2.17%   |
| MSI MS-7551           | 1         | 2.17%   |
| MiTAC 5033            | 1         | 2.17%   |
| Lenovo G500           | 1         | 2.17%   |
| KLLISRE X99-B5        | 1         | 2.17%   |
| Intel DN2820FYK       | 1         | 2.17%   |
| IBM ThinkPad          | 1         | 2.17%   |
| HP Vectra             | 1         | 2.17%   |
| Gigabyte Z170X-Gaming | 1         | 2.17%   |
| Gigabyte P75-D3       | 1         | 2.17%   |
| Gigabyte H61M-S2PV    | 1         | 2.17%   |
| Fujitsu Siemens AMILO | 1         | 2.17%   |
| eMachines eME642G     | 1         | 2.17%   |
| Dell PowerEdge        | 1         | 2.17%   |
| ASUS E45M1-I          | 1         | 2.17%   |
| ASUS B150M-K          | 1         | 2.17%   |
| ASUS All              | 1         | 2.17%   |
| ASUS A3L              | 1         | 2.17%   |
| ASRock X470           | 1         | 2.17%   |
| ASRock N68-VS3        | 1         | 2.17%   |
| ASRock 970            | 1         | 2.17%   |
| Apple MacBook2        | 1         | 2.17%   |
| Acer Aspire           | 1         | 2.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 13        | 28.26%  |
| 2013    | 7         | 15.22%  |
| 2020    | 5         | 10.87%  |
| 2017    | 3         | 6.52%   |
| 2011    | 3         | 6.52%   |
| 2018    | 2         | 4.35%   |
| 2014    | 2         | 4.35%   |
| 2010    | 2         | 4.35%   |
| 2005    | 2         | 4.35%   |
| 2021    | 1         | 2.17%   |
| 2019    | 1         | 2.17%   |
| 2016    | 1         | 2.17%   |
| 2015    | 1         | 2.17%   |
| 2007    | 1         | 2.17%   |
| 2006    | 1         | 2.17%   |
| 2001    | 1         | 2.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Desktop  | 31        | 67.39%  |
| Notebook | 14        | 30.43%  |
| Server   | 1         | 2.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 45        | 97.83%  |
| Yes  | 1         | 2.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 11        | 23.91%  |
| 3.01-4.0   | 9         | 19.57%  |
| 16.01-24.0 | 7         | 15.22%  |
| 8.01-16.0  | 5         | 10.87%  |
| 0.51-1.0   | 4         | 8.7%    |
| 1.01-2.0   | 3         | 6.52%   |
| 0.01-0.5   | 3         | 6.52%   |
| 32.01-64.0 | 1         | 2.17%   |
| 24.01-32.0 | 1         | 2.17%   |
| 0          | 1         | 2.17%   |
| Unknown    | 1         | 2.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| Unknown | 46        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 22        | 44.9%   |
| 0      | 15        | 30.61%  |
| 2      | 10        | 20.41%  |
| 3      | 2         | 4.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 95.65%  |
| Yes       | 2         | 4.35%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 82.61%  |
| No        | 8         | 17.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23        | 50%     |
| No        | 23        | 50%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 33        | 71.74%  |
| Yes       | 13        | 28.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Russia       | 10        | 21.74%  |
| USA          | 5         | 10.87%  |
| Italy        | 5         | 10.87%  |
| UK           | 4         | 8.7%    |
| Hungary      | 4         | 8.7%    |
| Saudi Arabia | 3         | 6.52%   |
| Germany      | 3         | 6.52%   |
| Finland      | 3         | 6.52%   |
| Vietnam      | 1         | 2.17%   |
| Spain        | 1         | 2.17%   |
| Romania      | 1         | 2.17%   |
| Poland       | 1         | 2.17%   |
| Latvia       | 1         | 2.17%   |
| India        | 1         | 2.17%   |
| Czechia      | 1         | 2.17%   |
| Canada       | 1         | 2.17%   |
| Brazil       | 1         | 2.17%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Ozersk                | 5         | 10.87%  |
| Rome                  | 4         | 8.7%    |
| Moscow                | 4         | 8.7%    |
| Riyadh                | 3         | 6.52%   |
| Gardony               | 3         | 6.52%   |
| Tampere               | 2         | 4.35%   |
| Washington            | 1         | 2.17%   |
| Urupes                | 1         | 2.17%   |
| Unterhaching          | 1         | 2.17%   |
| Ulan-Ude              | 1         | 2.17%   |
| Turin                 | 1         | 2.17%   |
| Turenki               | 1         | 2.17%   |
| Surrey                | 1         | 2.17%   |
| Stourbridge           | 1         | 2.17%   |
| Sopron                | 1         | 2.17%   |
| Royal Tunbridge Wells | 1         | 2.17%   |
| Riga                  | 1         | 2.17%   |
| Reno                  | 1         | 2.17%   |
| Prague                | 1         | 2.17%   |
| Poznan                | 1         | 2.17%   |
| Portland              | 1         | 2.17%   |
| Murcia                | 1         | 2.17%   |
| Ladbergen             | 1         | 2.17%   |
| Ho Chi Minh City      | 1         | 2.17%   |
| Hamilton              | 1         | 2.17%   |
| Fort Wayne            | 1         | 2.17%   |
| Bucharest             | 1         | 2.17%   |
| Bridgwater            | 1         | 2.17%   |
| Bloomsbury            | 1         | 2.17%   |
| Berlin                | 1         | 2.17%   |
| Ahmedabad             | 1         | 2.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 11     | 19.51%  |
| Samsung Electronics | 4         | 4      | 9.76%   |
| Kingston            | 4         | 4      | 9.76%   |
| Toshiba             | 3         | 4      | 7.32%   |
| Seagate             | 3         | 3      | 7.32%   |
| SanDisk             | 3         | 4      | 7.32%   |
| Intel               | 3         | 3      | 7.32%   |
| MAXTOR              | 2         | 2      | 4.88%   |
| Hitachi             | 2         | 3      | 4.88%   |
| SK Hynix            | 1         | 2      | 2.44%   |
| Lexar               | 1         | 1      | 2.44%   |
| JetFlash            | 1         | 1      | 2.44%   |
| HGST                | 1         | 1      | 2.44%   |
| Hewlett-Packard     | 1         | 1      | 2.44%   |
| Generic             | 1         | 1      | 2.44%   |
| Dell                | 1         | 2      | 2.44%   |
| Crucial             | 1         | 2      | 2.44%   |
| China               | 1         | 1      | 2.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB            | 3         | 7.14%   |
| Samsung HD103UJ 1TB               | 2         | 4.76%   |
| MAXTOR STM3250310AS 250GB         | 2         | 4.76%   |
| Kingston DataTraveler 3.0 32GB    | 2         | 4.76%   |
| WDC WDS240G2G0A-00JH30 240GB      | 1         | 2.38%   |
| WDC WDS120G2G0A-00JH30 120GB      | 1         | 2.38%   |
| WDC WD5003AZEX-00K3CA0 500GB      | 1         | 2.38%   |
| WDC WD5000AAKX-753CA1 500GB       | 1         | 2.38%   |
| WDC WD2502ABYS-01B7A0 256GB       | 1         | 2.38%   |
| WDC WD20EFRX-68EUZN0 2TB          | 1         | 2.38%   |
| WDC WD200EB-00BHF0 20GB           | 1         | 2.38%   |
| WDC WD1600BEVT-00A23T0 160GB      | 1         | 2.38%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1         | 2.38%   |
| SK Hynix HFS128G39TND-N210A 128GB | 1         | 2.38%   |
| Seagate ST500VT000-1DK142 500GB   | 1         | 2.38%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 2.38%   |
| Seagate ST380011A 80GB            | 1         | 2.38%   |
| SanDisk SDSSDH3512G 512GB         | 1         | 2.38%   |
| SanDisk Extreme SSD 250GB         | 1         | 2.38%   |
| SanDisk Cruzer Glide 16GB         | 1         | 2.38%   |
| Samsung SSD 860 EVO 500GB         | 1         | 2.38%   |
| Samsung HM080HC 80GB              | 1         | 2.38%   |
| Lexar USB Flash Drive 64GB        | 1         | 2.38%   |
| Kingston SA400S37240G 240GB       | 1         | 2.38%   |
| Kingston SA400S37120G 120GB       | 1         | 2.38%   |
| JetFlash Transcend 16GB           | 1         | 2.38%   |
| Intel SSDSC2KW120H6 120GB         | 1         | 2.38%   |
| Intel SSDSC2CW120A3 120GB         | 1         | 2.38%   |
| Intel SSDSC2BF180A4L 180GB        | 1         | 2.38%   |
| Hitachi HTS721060G9AT00 64GB      | 1         | 2.38%   |
| Hitachi HTS548040M9AT00 40GB      | 1         | 2.38%   |
| HGST HTS545050A7E680 500GB        | 1         | 2.38%   |
| HP v100w 8GB                      | 1         | 2.38%   |
| Generic Flash Disk 32GB           | 1         | 2.38%   |
| Dell PERC H710P 8TB               | 1         | 2.38%   |
| Crucial CT1000BX500SSD1 1TB       | 1         | 2.38%   |
| China SATA SSD 120GB              | 1         | 2.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 7         | 9      | 26.92%  |
| Toshiba             | 3         | 4      | 11.54%  |
| Seagate             | 3         | 3      | 11.54%  |
| Samsung Electronics | 3         | 3      | 11.54%  |
| MAXTOR              | 2         | 2      | 7.69%   |
| Hitachi             | 2         | 3      | 7.69%   |
| Lexar               | 1         | 1      | 3.85%   |
| JetFlash            | 1         | 1      | 3.85%   |
| HGST                | 1         | 1      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |
| Generic             | 1         | 1      | 3.85%   |
| Dell                | 1         | 2      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 4         | 4      | 25%     |
| SanDisk             | 3         | 4      | 18.75%  |
| Intel               | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| SK Hynix            | 1         | 2      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Crucial             | 1         | 2      | 6.25%   |
| China               | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 31     | 56.76%  |
| SSD  | 16        | 19     | 43.24%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 32        | 50     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 36     | 75%     |
| 0.51-1.0   | 8         | 10     | 20%     |
| 1.01-2.0   | 1         | 2      | 2.5%    |
| 4.01-10.0  | 1         | 2      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 15        | 32.61%  |
| 251-500        | 8         | 17.39%  |
| 51-100         | 7         | 15.22%  |
| 1-20           | 6         | 13.04%  |
| 501-1000       | 5         | 10.87%  |
| 21-50          | 2         | 4.35%   |
| 1001-2000      | 2         | 4.35%   |
| More than 3000 | 1         | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 34        | 69.39%  |
| 21-50          | 6         | 12.24%  |
| 51-100         | 4         | 8.16%   |
| 101-250        | 2         | 4.08%   |
| More than 3000 | 1         | 2.04%   |
| 1001-2000      | 1         | 2.04%   |
| 501-1000       | 1         | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB      | 1         | 1      | 10%     |
| WDC WD10EZEX-60WN4A0 1TB          | 1         | 1      | 10%     |
| SK Hynix HFS128G39TND-N210A 128GB | 1         | 1      | 10%     |
| Seagate ST500VT000-1DK142 500GB   | 1         | 1      | 10%     |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 10%     |
| Intel SSDSC2KW120H6 120GB         | 1         | 1      | 10%     |
| Intel SSDSC2CW120A3 120GB         | 1         | 1      | 10%     |
| Intel SSDSC2BF180A4L 180GB        | 1         | 1      | 10%     |
| Hitachi HTS721060G9AT00 64GB      | 1         | 1      | 10%     |
| Hitachi HTS548040M9AT00 40GB      | 1         | 2      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Intel    | 3         | 3      | 30%     |
| WDC      | 2         | 2      | 20%     |
| Seagate  | 2         | 2      | 20%     |
| Hitachi  | 2         | 3      | 20%     |
| SK Hynix | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| Hitachi | 2         | 3      | 40%     |
| WDC     | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 5         | 5      | 50%     |
| HDD  | 5         | 6      | 50%     |

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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 19        | 31     | 52.78%  |
| Malfunc  | 10        | 11     | 27.78%  |
| Detected | 7         | 8      | 19.44%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 30        | 58.82%  |
| AMD                 | 10        | 19.61%  |
| Silicon Motion      | 3         | 5.88%   |
| Sandisk             | 2         | 3.92%   |
| Samsung Electronics | 2         | 3.92%   |
| VIA Technologies    | 1         | 1.96%   |
| Nvidia              | 1         | 1.96%   |
| Broadcom / LSI      | 1         | 1.96%   |
| ASMedia Technology  | 1         | 1.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 8.47%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 8.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 6.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 5.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 5.08%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 5.08%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 3.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 3.39%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 3.39%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 3.39%   |
| AMD FCH SATA Controller D                                                        | 2         | 3.39%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.69%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.69%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.69%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.69%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.69%   |
| Intel 82801AA IDE Controller                                                     | 1         | 1.69%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 1.69%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 1         | 1.69%   |
| ASMedia ASM1061 SATA IDE Controller                                              | 1         | 1.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 35        | 64.81%  |
| IDE  | 11        | 20.37%  |
| NVMe | 7         | 12.96%  |
| RAID | 1         | 1.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 29        | 63.04%  |
| AMD          | 11        | 23.91%  |
| Unknown      | 3         | 6.52%   |
| Arm          | 2         | 4.35%   |
| 123456789ABC | 1         | 2.17%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 686-class                             | 10        | 21.74%  |
|                                             | 3         | 6.52%   |
| Arm Cortex-A53 r0p4 (v8-A)                  | 2         | 4.35%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz        | 1         | 2.17%   |
| Intel Xeon CPU E5-2450L 0 @ 1.80GHz         | 1         | 2.17%   |
| Intel Pentium M processor 1.60GHz           | 1         | 2.17%   |
| Intel Pentium M processor                   | 1         | 2.17%   |
| Intel Pentium III                           | 1         | 2.17%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 2.17%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 2.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 2.17%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 2.17%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 2.17%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 2.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 2.17%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1         | 2.17%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 1         | 2.17%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1         | 2.17%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 2.17%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 2.17%   |
| Intel Core 2 CPU T7                         | 1         | 2.17%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1         | 2.17%   |
| AMD Tillamook                               | 1         | 2.17%   |
| AMD Sempron 145 Processor                   | 1         | 2.17%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1         | 2.17%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1         | 2.17%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1         | 2.17%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 1         | 2.17%   |
| AMD Phenom II X6 1055T Processor            | 1         | 2.17%   |
| AMD Phenom II X4 965 Processor              | 1         | 2.17%   |
| AMD E-450 APU with Radeon HD Graphics       | 1         | 2.17%   |
| AMD Athlon II P340 Dual-Core Processor      | 1         | 2.17%   |
| AMD 686-class                               | 1         | 2.17%   |
| 123456789ABC Pentium 4                      | 1         | 2.17%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel 686-class   | 10        | 21.74%  |
| Other             | 7         | 15.22%  |
| Intel Core i5     | 5         | 10.87%  |
| Intel Core i7     | 3         | 6.52%   |
| Intel Xeon        | 2         | 4.35%   |
| Intel Pentium M   | 2         | 4.35%   |
| Intel Core i3     | 2         | 4.35%   |
| Intel Core 2      | 2         | 4.35%   |
| AMD Ryzen 5       | 2         | 4.35%   |
| AMD Ryzen 3       | 2         | 4.35%   |
| Intel Pentium III | 1         | 2.17%   |
| Intel Pentium     | 1         | 2.17%   |
| Intel Celeron     | 1         | 2.17%   |
| AMD Sempron       | 1         | 2.17%   |
| AMD Phenom II X6  | 1         | 2.17%   |
| AMD Phenom II X4  | 1         | 2.17%   |
| AMD E             | 1         | 2.17%   |
| AMD Athlon II     | 1         | 2.17%   |
| AMD 686-class     | 1         | 2.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 58.7%   |
| 2       | 9         | 19.57%  |
| 4       | 6         | 13.04%  |
| 8       | 2         | 4.35%   |
| 6       | 2         | 4.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 30        | 65.22%  |
| Unknown | 16        | 34.78%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 27        | 58.7%   |
| 2       | 12        | 26.09%  |
| 1       | 7         | 15.22%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 19        | 41.3%   |
| IvyBridge   | 4         | 8.7%    |
| SandyBridge | 3         | 6.52%   |
| P6          | 3         | 6.52%   |
| K10         | 3         | 6.52%   |
| Haswell     | 3         | 6.52%   |
| Zen         | 2         | 4.35%   |
| Core        | 2         | 4.35%   |
| Zen+        | 1         | 2.17%   |
| Zen 2       | 1         | 2.17%   |
| Skylake     | 1         | 2.17%   |
| Silvermont  | 1         | 2.17%   |
| KabyLake    | 1         | 2.17%   |
| Geode       | 1         | 2.17%   |
| Bobcat      | 1         | 2.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 24        | 51.06%  |
| AMD                        | 11        | 23.4%   |
| Nvidia                     | 9         | 19.15%  |
| VIA Technologies           | 1         | 2.13%   |
| Trident Microsystems       | 1         | 2.13%   |
| Matrox Electronics Systems | 1         | 2.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 8%      |
| Nvidia GF114 [GeForce GTX 560]                                                           | 2         | 4%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 4%      |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 4%      |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 4%      |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]                        | 1         | 2%      |
| Trident Microsystems TGUI 9660/938x/968x                                                 | 1         | 2%      |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 2%      |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 2%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 2%      |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 2%      |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 2%      |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1         | 2%      |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 2%      |
| Matrox Electronics Systems G200eR2                                                       | 1         | 2%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 2%      |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 2%      |
| Intel Iris Graphics 6100                                                                 | 1         | 2%      |
| Intel HD Graphics 630                                                                    | 1         | 2%      |
| Intel HD Graphics 5500                                                                   | 1         | 2%      |
| Intel HD Graphics 530                                                                    | 1         | 2%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 2%      |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 2%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 2%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 2%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 2%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 2%      |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 2%      |
| AMD Tonga PRO [Radeon R9 285/380]                                                        | 1         | 2%      |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 2%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 2%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 2%      |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 2%      |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 1         | 2%      |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 2%      |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 2%      |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 1         | 2%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 17        | 36.96%  |
| 1 x AMD                  | 8         | 17.39%  |
| 1 x Nvidia               | 7         | 15.22%  |
| Other                    | 5         | 10.87%  |
| 2 x Intel                | 2         | 4.35%   |
| Intel + Nvidia           | 2         | 4.35%   |
| 2 x AMD                  | 1         | 2.17%   |
| 1 x VIA                  | 1         | 2.17%   |
| 1 x Trident Microsystems | 1         | 2.17%   |
| 1 x Matrox               | 1         | 2.17%   |
| Intel + AMD              | 1         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 34        | 70.83%  |
| Unknown | 14        | 29.17%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 21        | 44.68%  |
| 1.01-2.0   | 10        | 21.28%  |
| 0.01-0.5   | 9         | 19.15%  |
| 3.01-4.0   | 4         | 8.51%   |
| 0.51-1.0   | 2         | 4.26%   |
| 7.01-8.0   | 1         | 2.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 4         | 19.05%  |
| Goldstar            | 4         | 19.05%  |
| LG Display          | 3         | 14.29%  |
| Chimei Innolux      | 2         | 9.52%   |
| Apple               | 2         | 9.52%   |
| ViewSonic           | 1         | 4.76%   |
| Unknown (CDD)       | 1         | 4.76%   |
| LG Philips          | 1         | 4.76%   |
| Lenovo              | 1         | 4.76%   |
| Impression          | 1         | 4.76%   |
| Acer                | 1         | 4.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 2         | 9.52%   |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch           | 1         | 4.76%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch              | 1         | 4.76%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch     | 1         | 4.76%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch  | 1         | 4.76%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch           | 1         | 4.76%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch           | 1         | 4.76%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 4.76%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 1         | 4.76%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 1         | 4.76%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1         | 4.76%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1         | 4.76%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 1         | 4.76%   |
| Goldstar LCD Monitor GSM5AB6 1920x1080 480x270mm 21.7-inch            | 1         | 4.76%   |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                  | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 4.76%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch       | 1         | 4.76%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                | 1         | 4.76%   |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                 | 1         | 4.76%   |
| Acer SB220Q ACR06AB 1920x1080 480x270mm 21.7-inch                     | 1         | 4.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 7         | 33.33%  |
| 1366x768 (WXGA)  | 6         | 28.57%  |
| 1440x900 (WXGA+) | 3         | 14.29%  |
| 1280x800 (WXGA)  | 2         | 9.52%   |
| 2560x1600        | 1         | 4.76%   |
| 2560x1080        | 1         | 4.76%   |
| 1600x900 (HD+)   | 1         | 4.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 5         | 23.81%  |
| 15     | 4         | 19.05%  |
| 19     | 3         | 14.29%  |
| 40     | 2         | 9.52%   |
| 23     | 2         | 9.52%   |
| 21     | 2         | 9.52%   |
| 52     | 1         | 4.76%   |
| 28     | 1         | 4.76%   |
| 12     | 1         | 4.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 7         | 33.33%  |
| 401-500     | 5         | 23.81%  |
| 201-300     | 3         | 14.29%  |
| 801-900     | 2         | 9.52%   |
| 501-600     | 2         | 9.52%   |
| 601-700     | 1         | 4.76%   |
| 1001-1500   | 1         | 4.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 14        | 66.67%  |
| 16/10 | 6         | 28.57%  |
| 21/9  | 1         | 4.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 5         | 23.81%  |
| 201-250        | 4         | 19.05%  |
| 151-200        | 3         | 14.29%  |
| 101-110        | 3         | 14.29%  |
| 501-1000       | 2         | 9.52%   |
| More than 1000 | 1         | 4.76%   |
| 61-70          | 1         | 4.76%   |
| 251-300        | 1         | 4.76%   |
| 91-100         | 1         | 4.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 10        | 47.62%  |
| 101-120 | 8         | 38.1%   |
| 1-50    | 1         | 4.76%   |
| 161-240 | 1         | 4.76%   |
| 121-160 | 1         | 4.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 26        | 55.32%  |
| 0     | 20        | 42.55%  |
| 2     | 1         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 35.48%  |
| Intel                    | 16        | 25.81%  |
| Qualcomm Atheros         | 9         | 14.52%  |
| Broadcom                 | 5         | 8.06%   |
| Huawei Technologies      | 3         | 4.84%   |
| VIA Technologies         | 1         | 1.61%   |
| Oculus VR                | 1         | 1.61%   |
| Netchip Technology       | 1         | 1.61%   |
| Mercucys                 | 1         | 1.61%   |
| Marvell Technology Group | 1         | 1.61%   |
| D-Link                   | 1         | 1.61%   |
| 3Com                     | 1         | 1.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 20        | 26.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 5         | 6.67%   |
| Huawei USB Composite Device                                                           | 3         | 4%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 2         | 2.67%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 2.67%   |
| Intel I211 Gigabit Network Connection                                                 | 2         | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 2.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 2.67%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 1.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 1.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 1.33%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.33%   |
| Oculus VR Rift S                                                                      | 1         | 1.33%   |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                                        | 1         | 1.33%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 1.33%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 1.33%   |
| Intel Wireless-AC 9260                                                                | 1         | 1.33%   |
| Intel Wireless 7260                                                                   | 1         | 1.33%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.33%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.33%   |
| Intel PRO/100 VE Network Connection                                                   | 1         | 1.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.33%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.33%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 1.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 1.33%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller                     | 1         | 1.33%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                                    | 1         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                                              | 1         | 1.33%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 1.33%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                                     | 1         | 1.33%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                      | 1         | 1.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                       | 1         | 1.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 1.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 1.33%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                         | 1         | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 13        | 50%     |
| Qualcomm Atheros      | 6         | 23.08%  |
| Broadcom              | 3         | 11.54%  |
| Realtek Semiconductor | 2         | 7.69%   |
| Mercucys              | 1         | 3.85%   |
| D-Link                | 1         | 3.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 7.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 7.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 7.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 3.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 3.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 3.85%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 3.85%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 3.85%   |
| Intel Wireless-AC 9260                                                                | 1         | 3.85%   |
| Intel Wireless 7260                                                                   | 1         | 3.85%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 3.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 3.85%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 3.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 3.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 3.85%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 3.85%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 3.85%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 3.85%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 3.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 3.85%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 3.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 48.89%  |
| Intel                    | 11        | 24.44%  |
| Qualcomm Atheros         | 3         | 6.67%   |
| Huawei Technologies      | 3         | 6.67%   |
| Broadcom                 | 3         | 6.67%   |
| VIA Technologies         | 1         | 2.22%   |
| Marvell Technology Group | 1         | 2.22%   |
| 3Com                     | 1         | 2.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 44.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 11.11%  |
| Huawei USB Composite Device                                       | 3         | 6.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 4.44%   |
| Intel I211 Gigabit Network Connection                             | 2         | 4.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 2.22%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.22%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.22%   |
| Intel PRO/100 VE Network Connection                               | 1         | 2.22%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.22%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 2.22%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.22%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.22%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 2.22%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.22%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1         | 2.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 41        | 58.57%  |
| WiFi     | 25        | 35.71%  |
| Modem    | 3         | 4.29%   |
| Unknown  | 1         | 1.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 73.08%  |
| WiFi     | 14        | 26.92%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 22        | 47.83%  |
| 1     | 16        | 34.78%  |
| 0     | 7         | 15.22%  |
| 3     | 1         | 2.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 40        | 85.11%  |
| Yes  | 7         | 14.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 6         | 46.15%  |
| Apple                   | 3         | 23.08%  |
| Realtek Semiconductor   | 1         | 7.69%   |
| IMC Networks            | 1         | 7.69%   |
| Cambridge Silicon Radio | 1         | 7.69%   |
| Broadcom                | 1         | 7.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 15.38%  |
| Realtek  Bluetooth 4.0 Adapter                      | 1         | 7.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 7.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 7.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 7.69%   |
| Intel Bluetooth wireless interface                  | 1         | 7.69%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 7.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 7.69%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 7.69%   |
| Apple Bluetooth Host Controller                     | 1         | 7.69%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 7.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 29        | 56.86%  |
| AMD                 | 13        | 25.49%  |
| Nvidia              | 5         | 9.8%    |
| Yamaha              | 1         | 1.96%   |
| VIA Technologies    | 1         | 1.96%   |
| Samsung Electronics | 1         | 1.96%   |
| Logitech            | 1         | 1.96%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 11.29%  |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 6.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 4.84%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 2         | 3.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 3.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 3.23%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 3.23%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 3.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 3.23%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 3.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 3.23%   |
| Yamaha AG06/AG03                                                                                  | 1         | 1.61%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 1.61%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                                        | 1         | 1.61%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.61%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.61%   |
| Logitech Zone Wired Earbuds                                                                       | 1         | 1.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.61%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.61%   |
| Intel 82801AA AC'97 Audio Controller                                                              | 1         | 1.61%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.61%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.61%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                                          | 1         | 1.61%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.61%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.61%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.61%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 1.61%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 1.61%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 1.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 8         | 25%     |
| Kingston            | 7         | 21.88%  |
| Crucial             | 4         | 12.5%   |
| Samsung Electronics | 3         | 9.38%   |
| Patriot             | 2         | 6.25%   |
| Micron Technology   | 2         | 6.25%   |
| SK Hynix            | 1         | 3.13%   |
| SHARETRONIC         | 1         | 3.13%   |
| Ramaxel Technology  | 1         | 3.13%   |
| Nanya Technology    | 1         | 3.13%   |
| G.Skill             | 1         | 3.13%   |
| A-DATA Technology   | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB DIMM 400MT/s                     | 1         | 2.86%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s               | 1         | 2.86%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR3                         | 1         | 2.86%   |
| Unknown RAM Module 256MB SODIMM DDR                        | 1         | 2.86%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 2.86%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 1         | 2.86%   |
| Unknown RAM Module 128MB DIMM DRAM                         | 1         | 2.86%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s             | 1         | 2.86%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 1         | 2.86%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1         | 2.86%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s      | 1         | 2.86%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s      | 1         | 2.86%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s      | 1         | 2.86%   |
| Samsung RAM M386B4G70DM0-YK03 32GB DIMM DDR3 1600MT/s      | 1         | 2.86%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 1         | 2.86%   |
| Patriot RAM PSD44G213382 4096MB DIMM DDR4 2133MT/s         | 1         | 2.86%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s             | 1         | 2.86%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 2.86%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s       | 1         | 2.86%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s     | 1         | 2.86%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s          | 1         | 2.86%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s        | 1         | 2.86%   |
| Kingston RAM ACR16D3LS1KFG/4G 4096MB DIMM DDR3 1600MT/s    | 1         | 2.86%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2048MB SODIMM DDR3 1600MT/s | 1         | 2.86%   |
| Kingston RAM 99U5701-077.A00G 16GB DIMM DDR4 2667MT/s      | 1         | 2.86%   |
| Kingston RAM 99U5471-028.A00LF 4GB DIMM DDR3 667MT/s       | 1         | 2.86%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1333MT/s      | 1         | 2.86%   |
| Kingston RAM 9905428-026.A02LF 2048MB SODIMM DDR3 1066MT/s | 1         | 2.86%   |
| G.Skill RAM F4-2800C17-8GVR 8192MB DIMM DDR4 2133MT/s      | 1         | 2.86%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s       | 1         | 2.86%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s      | 1         | 2.86%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s      | 1         | 2.86%   |
| Crucial RAM BLS4G4D240FSE.8FBD 4GB DIMM DDR4 2400MT/s      | 1         | 2.86%   |
| A-DATA RAM Module 8GB DIMM DDR4 2666MT/s                   | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 14        | 48.28%  |
| DDR4    | 8         | 27.59%  |
| DRAM    | 2         | 6.9%    |
| DDR2    | 2         | 6.9%    |
| SDRAM   | 1         | 3.45%   |
| DDR     | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 18        | 62.07%  |
| SODIMM | 11        | 37.93%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 9         | 30%     |
| 8192  | 7         | 23.33%  |
| 2048  | 6         | 20%     |
| 16384 | 2         | 6.67%   |
| 512   | 2         | 6.67%   |
| 32768 | 1         | 3.33%   |
| 1024  | 1         | 3.33%   |
| 256   | 1         | 3.33%   |
| 128   | 1         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 8         | 25%     |
| 2133    | 3         | 9.38%   |
| 1333    | 3         | 9.38%   |
| Unknown | 3         | 9.38%   |
| 2400    | 2         | 6.25%   |
| 1067    | 2         | 6.25%   |
| 2933    | 1         | 3.13%   |
| 2667    | 1         | 3.13%   |
| 2666    | 1         | 3.13%   |
| 1334    | 1         | 3.13%   |
| 1066    | 1         | 3.13%   |
| 800     | 1         | 3.13%   |
| 667     | 1         | 3.13%   |
| 533     | 1         | 3.13%   |
| 400     | 1         | 3.13%   |
| 266     | 1         | 3.13%   |
| 166     | 1         | 3.13%   |

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

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Chicony Electronics   | 4         | 33.33%  |
| Realtek Semiconductor | 2         | 16.67%  |
| Syntek                | 1         | 8.33%   |
| Silicon Motion        | 1         | 8.33%   |
| Lenovo                | 1         | 8.33%   |
| ARC International     | 1         | 8.33%   |
| ALi                   | 1         | 8.33%   |
| Acer                  | 1         | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony integrated camera            | 2         | 16.67%  |
| Syntek Lenovo EasyCamera             | 1         | 8.33%   |
| Silicon Motion 300k Pixel Camera     | 1         | 8.33%   |
| Realtek USB Camera                   | 1         | 8.33%   |
| Realtek Acer 640 x 480 laptop camera | 1         | 8.33%   |
| Lenovo Integrated Webcam [R5U877]    | 1         | 8.33%   |
| Chicony USB2.0 VGA UVC WebCam        | 1         | 8.33%   |
| Chicony Front Camera                 | 1         | 8.33%   |
| ARC International Camera             | 1         | 8.33%   |
| ALi Gateway Webcam                   | 1         | 8.33%   |
| Acer Integrated Camera               | 1         | 8.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 100%    |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 18        | 38.3%   |
| 1     | 16        | 34.04%  |
| 2     | 7         | 14.89%  |
| 3     | 3         | 6.38%   |
| 5     | 2         | 4.26%   |
| 4     | 1         | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 24        | 52.17%  |
| Net/wireless             | 10        | 21.74%  |
| Graphics card            | 4         | 8.7%    |
| Card reader              | 4         | 8.7%    |
| Wireless                 | 1         | 2.17%   |
| Storage                  | 1         | 2.17%   |
| Modem                    | 1         | 2.17%   |
| Bluetooth                | 1         | 2.17%   |

