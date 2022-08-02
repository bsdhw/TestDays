NetBSD - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for NetBSD.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NetBSD/Desktop/README.md) and [notebooks](/Dist/NetBSD/Notebook/README.md).

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

Total: 72

| Vendor        | Model                    | Form-Factor | Probe                                                     | Date         |
|---------------|--------------------------|-------------|-----------------------------------------------------------|--------------|
| ASUSTek       | TUF B450-PLUS GAMING     | Desktop     | [aeee3a91e6](https://bsd-hardware.info/?probe=aeee3a91e6) | Jul 03, 2022 |
| Gigabyte      | X570 AORUS PRO           | Desktop     | [4e7d57df3b](https://bsd-hardware.info/?probe=4e7d57df3b) | Apr 18, 2022 |
| ASUSTek       | X555LJ                   | Notebook    | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| Acer          | Aspire A114-33           | Notebook    | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Gigabyte      | 970A-D3P                 | Desktop     | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B   | Soc         | [0394e3272e](https://bsd-hardware.info/?probe=0394e3272e) | Mar 03, 2022 |
| KLLISRE       | X99-B5 V1.0              | Desktop     | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| MiTAC         | 5033                     | Notebook    | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| ASRock        | X470 Gaming-ITX/ac       | Desktop     | [18eeaf2963](https://bsd-hardware.info/?probe=18eeaf2963) | Dec 29, 2021 |
| Acer          | Revo RN86                | Desktop     | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| ASRock        | 970 Extreme3             | Desktop     | [14907c62f1](https://bsd-hardware.info/?probe=14907c62f1) | Dec 04, 2021 |
| HP            | 3397                     | Desktop     | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| Lenovo        | ThinkPad T420 4236D26    | Notebook    | [5c64875424](https://bsd-hardware.info/?probe=5c64875424) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING  | Desktop     | [7259ec87e9](https://bsd-hardware.info/?probe=7259ec87e9) | Oct 05, 2021 |
| ASUSTek       | X555LJ                   | Notebook    | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASUSTek       | PRIME A320M-K            | Desktop     | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING  | Desktop     | [b3a18fcab3](https://bsd-hardware.info/?probe=b3a18fcab3) | Sep 29, 2021 |
| Unknown       | Unknown                  | Desktop     | [2a56bcb7c1](https://bsd-hardware.info/?probe=2a56bcb7c1) | Sep 19, 2021 |
| Toshiba       | Satellite A100           | Notebook    | [9ccf97d62c](https://bsd-hardware.info/?probe=9ccf97d62c) | Sep 05, 2021 |
| MSI           | B450-A PRO MAX           | Desktop     | [4e3b1f226b](https://bsd-hardware.info/?probe=4e3b1f226b) | Jun 22, 2021 |
| Sony          | SVF1421DSGW              | Notebook    | [abadb65058](https://bsd-hardware.info/?probe=abadb65058) | Jun 01, 2021 |
| Unknown       | Unknown                  | Desktop     | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Acer          | Revo RN86                | Desktop     | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
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
| Acer          | Revo RN86                | Desktop     | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek       | H81M-D PLUS              | Desktop     | [036d9cfecb](https://bsd-hardware.info/?probe=036d9cfecb) | Sep 19, 2020 |
| ASUSTek       | H81M-D PLUS              | Desktop     | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| MSI           | KA790GX                  | Desktop     | [bba5499a4b](https://bsd-hardware.info/?probe=bba5499a4b) | Aug 29, 2020 |
| Lenovo        | ThinkPad T510 4313CTO    | Notebook    | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| eMachines     | eME642G                  | Notebook    | [42027dfbb9](https://bsd-hardware.info/?probe=42027dfbb9) | Jul 25, 2020 |
| Intel         | NUC7JYB J67969-404       | Mini pc     | [35c4a3608e](https://bsd-hardware.info/?probe=35c4a3608e) | Jul 19, 2020 |
| Intel         | NUC5PPYB                 | Mini pc     | [9fbca0a216](https://bsd-hardware.info/?probe=9fbca0a216) | Jun 17, 2020 |
| Lenovo        | G500 20236               | Notebook    | [99cf14c489](https://bsd-hardware.info/?probe=99cf14c489) | Jun 03, 2020 |
| ASUSTek       | PRIME A320M-K            | Desktop     | [a49cf5c20b](https://bsd-hardware.info/?probe=a49cf5c20b) | May 28, 2020 |
| Gigabyte      | H61M-S2PV                | Desktop     | [14e00aa09f](https://bsd-hardware.info/?probe=14e00aa09f) | May 25, 2020 |
| Intel         | DN2820FYK H24582-203     | Desktop     | [6cb240a9f6](https://bsd-hardware.info/?probe=6cb240a9f6) | May 25, 2020 |
| Intel         | NUC5PPYB                 | Mini pc     | [8ba62bd121](https://bsd-hardware.info/?probe=8ba62bd121) | May 25, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N | Notebook    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |
| Unknown       | Unknown                  | Desktop     | [d3ad2b17ed](https://bsd-hardware.info/?probe=d3ad2b17ed) | May 22, 2020 |
| Lenovo        | G570 20079               | Notebook    | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| ASUSTek       | A3L                      | Notebook    | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| Lenovo        | G570 20079               | Notebook    | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| NetBSD 9.2        | 12        | 21.05%  |
| NetBSD 9.1        | 10        | 17.54%  |
| NetBSD 9.0_STABLE | 8         | 14.04%  |
| NetBSD 9.0        | 6         | 10.53%  |
| NetBSD 9.99.94    | 3         | 5.26%   |
| NetBSD 9.99.93    | 3         | 5.26%   |
| NetBSD 9.1_STABLE | 3         | 5.26%   |
| NetBSD 9.99.77    | 2         | 3.51%   |
| NetBSD 9.2_STABLE | 2         | 3.51%   |
| NetBSD 9.99.85    | 1         | 1.75%   |
| NetBSD 9.99.81    | 1         | 1.75%   |
| NetBSD 9.99.74    | 1         | 1.75%   |
| NetBSD 9.99.71    | 1         | 1.75%   |
| NetBSD 9.99.61    | 1         | 1.75%   |
| NetBSD 9.99.23    | 1         | 1.75%   |
| NetBSD 8.99.51    | 1         | 1.75%   |
| NetBSD 7.2        | 1         | 1.75%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| NetBSD | 51        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 39        | 76.47%  |
| i386   | 6         | 11.76%  |
| evbarm | 6         | 11.76%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 20        | 37.74%  |
| XFCE         | 11        | 20.75%  |
| helloDesktop | 7         | 13.21%  |
| Fluxbox      | 4         | 7.55%   |
| CTWM         | 3         | 5.66%   |
| MATE         | 2         | 3.77%   |
| DWM          | 2         | 3.77%   |
| Xfwm4        | 1         | 1.89%   |
| Ratpoison    | 1         | 1.89%   |
| PekWM        | 1         | 1.89%   |
| Awesome      | 1         | 1.89%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 36        | 70.59%  |
| Console | 15        | 29.41%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 46        | 90.2%   |
| XDM     | 2         | 3.92%   |
| GDM     | 2         | 3.92%   |
| LightDM | 1         | 1.96%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 71.15%  |
| en_US   | 8         | 15.38%  |
| ru_RU   | 3         | 5.77%   |
| fi_FI   | 2         | 3.85%   |
| hu_HU   | 1         | 1.92%   |
| en_GB   | 1         | 1.92%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 49        | 96.08%  |
| EFI  | 2         | 3.92%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 50        | 98.04%  |
| Unknown | 1         | 1.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 30        | 58.82%  |
| Unknown | 21        | 41.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 12        | 23.53%  |
| ASUSTek Computer        | 8         | 15.69%  |
| Lenovo                  | 5         | 9.8%    |
| Gigabyte Technology     | 5         | 9.8%    |
| ASRock                  | 3         | 5.88%   |
| Acer                    | 3         | 5.88%   |
| MSI                     | 2         | 3.92%   |
| Intel                   | 2         | 3.92%   |
| Toshiba                 | 1         | 1.96%   |
| Sony                    | 1         | 1.96%   |
| Raspberry Pi Foundation | 1         | 1.96%   |
| MiTAC                   | 1         | 1.96%   |
| KLLISRE                 | 1         | 1.96%   |
| IBM                     | 1         | 1.96%   |
| Hewlett-Packard         | 1         | 1.96%   |
| Fujitsu Siemens         | 1         | 1.96%   |
| eMachines               | 1         | 1.96%   |
| Dell                    | 1         | 1.96%   |
| Apple                   | 1         | 1.96%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 12        | 23.53%  |
| ASUS PRIME A320M-K              | 2         | 3.92%   |
| Toshiba Satellite A100          | 1         | 1.96%   |
| Sony SVF1421DSGW                | 1         | 1.96%   |
| RPi Raspberry Pi 4 Model B      | 1         | 1.96%   |
| MSI MS-7B86                     | 1         | 1.96%   |
| MSI MS-7551                     | 1         | 1.96%   |
| MiTAC 5033                      | 1         | 1.96%   |
| Lenovo ThinkPad X240 20AMS0J01N | 1         | 1.96%   |
| Lenovo ThinkPad T510 4313CTO    | 1         | 1.96%   |
| Lenovo ThinkPad T430s 23564H3   | 1         | 1.96%   |
| Lenovo ThinkPad T420 4236D26    | 1         | 1.96%   |
| Lenovo G500 20236               | 1         | 1.96%   |
| KLLISRE X99-B5 V1.0             | 1         | 1.96%   |
| Intel NUC5PPYB                  | 1         | 1.96%   |
| Intel DN2820FYK H24582-203      | 1         | 1.96%   |
| IBM ThinkPad R51 2887AVG        | 1         | 1.96%   |
| HP Vectra                       | 1         | 1.96%   |
| Gigabyte Z170X-Gaming 3         | 1         | 1.96%   |
| Gigabyte X570 AORUS PRO         | 1         | 1.96%   |
| Gigabyte P75-D3                 | 1         | 1.96%   |
| Gigabyte H61M-S2PV              | 1         | 1.96%   |
| Gigabyte 970A-D3P               | 1         | 1.96%   |
| Fujitsu Siemens AMILO L7310     | 1         | 1.96%   |
| eMachines eME642G               | 1         | 1.96%   |
| Dell PowerEdge T320             | 1         | 1.96%   |
| ASUS X555LJ                     | 1         | 1.96%   |
| ASUS TUF B450-PLUS GAMING       | 1         | 1.96%   |
| ASUS E45M1-I DELUXE             | 1         | 1.96%   |
| ASUS B150M-K                    | 1         | 1.96%   |
| ASUS All Series                 | 1         | 1.96%   |
| ASUS A3L                        | 1         | 1.96%   |
| ASRock X470 Gaming-ITX/ac       | 1         | 1.96%   |
| ASRock N68-VS3 UCC              | 1         | 1.96%   |
| ASRock 970 Extreme3             | 1         | 1.96%   |
| Apple MacBook2,1                | 1         | 1.96%   |
| Acer Revo RN86                  | 1         | 1.96%   |
| Acer Aspire ES1-132             | 1         | 1.96%   |
| Acer Aspire A114-33             | 1         | 1.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 12        | 23.53%  |
| Lenovo ThinkPad       | 4         | 7.84%   |
| ASUS PRIME            | 2         | 3.92%   |
| Acer Aspire           | 2         | 3.92%   |
| Toshiba Satellite     | 1         | 1.96%   |
| Sony SVF1421DSGW      | 1         | 1.96%   |
| RPi Raspberry         | 1         | 1.96%   |
| MSI MS-7B86           | 1         | 1.96%   |
| MSI MS-7551           | 1         | 1.96%   |
| MiTAC 5033            | 1         | 1.96%   |
| Lenovo G500           | 1         | 1.96%   |
| KLLISRE X99-B5        | 1         | 1.96%   |
| Intel NUC5PPYB        | 1         | 1.96%   |
| Intel DN2820FYK       | 1         | 1.96%   |
| IBM ThinkPad          | 1         | 1.96%   |
| HP Vectra             | 1         | 1.96%   |
| Gigabyte Z170X-Gaming | 1         | 1.96%   |
| Gigabyte X570         | 1         | 1.96%   |
| Gigabyte P75-D3       | 1         | 1.96%   |
| Gigabyte H61M-S2PV    | 1         | 1.96%   |
| Gigabyte 970A-D3P     | 1         | 1.96%   |
| Fujitsu Siemens AMILO | 1         | 1.96%   |
| eMachines eME642G     | 1         | 1.96%   |
| Dell PowerEdge        | 1         | 1.96%   |
| ASUS X555LJ           | 1         | 1.96%   |
| ASUS TUF              | 1         | 1.96%   |
| ASUS E45M1-I          | 1         | 1.96%   |
| ASUS B150M-K          | 1         | 1.96%   |
| ASUS All              | 1         | 1.96%   |
| ASUS A3L              | 1         | 1.96%   |
| ASRock X470           | 1         | 1.96%   |
| ASRock N68-VS3        | 1         | 1.96%   |
| ASRock 970            | 1         | 1.96%   |
| Apple MacBook2        | 1         | 1.96%   |
| Acer Revo             | 1         | 1.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 12        | 23.53%  |
| 2020    | 7         | 13.73%  |
| 2013    | 7         | 13.73%  |
| 2021    | 3         | 5.88%   |
| 2017    | 3         | 5.88%   |
| 2011    | 3         | 5.88%   |
| 2019    | 2         | 3.92%   |
| 2018    | 2         | 3.92%   |
| 2014    | 2         | 3.92%   |
| 2010    | 2         | 3.92%   |
| 2005    | 2         | 3.92%   |
| 2016    | 1         | 1.96%   |
| 2015    | 1         | 1.96%   |
| 2012    | 1         | 1.96%   |
| 2007    | 1         | 1.96%   |
| 2006    | 1         | 1.96%   |
| 2001    | 1         | 1.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 32        | 62.75%  |
| Notebook       | 16        | 31.37%  |
| System on chip | 1         | 1.96%   |
| Mini pc        | 1         | 1.96%   |
| Server         | 1         | 1.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 50        | 98.04%  |
| Yes  | 1         | 1.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 13        | 25.49%  |
| 3.01-4.0    | 9         | 17.65%  |
| 16.01-24.0  | 7         | 13.73%  |
| 8.01-16.0   | 5         | 9.8%    |
| 0.51-1.0    | 4         | 7.84%   |
| 32.01-64.0  | 3         | 5.88%   |
| 1.01-2.0    | 3         | 5.88%   |
| 0.01-0.5    | 3         | 5.88%   |
| 24.01-32.0  | 1         | 1.96%   |
| 64.01-256.0 | 1         | 1.96%   |
| 0           | 1         | 1.96%   |
| Unknown     | 1         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| Unknown | 51        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 24        | 44.44%  |
| 0      | 17        | 31.48%  |
| 2      | 10        | 18.52%  |
| 3      | 2         | 3.7%    |
| 4      | 1         | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 49        | 96.08%  |
| Yes       | 2         | 3.92%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 82.35%  |
| No        | 9         | 17.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 27        | 52.94%  |
| Yes       | 24        | 47.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 36        | 70.59%  |
| Yes       | 15        | 29.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Russia       | 11        | 21.57%  |
| Italy        | 6         | 11.76%  |
| USA          | 5         | 9.8%    |
| UK           | 4         | 7.84%   |
| Hungary      | 4         | 7.84%   |
| Germany      | 4         | 7.84%   |
| Saudi Arabia | 3         | 5.88%   |
| Finland      | 3         | 5.88%   |
| Vietnam      | 1         | 1.96%   |
| Spain        | 1         | 1.96%   |
| Romania      | 1         | 1.96%   |
| Poland       | 1         | 1.96%   |
| Netherlands  | 1         | 1.96%   |
| Latvia       | 1         | 1.96%   |
| India        | 1         | 1.96%   |
| Czechia      | 1         | 1.96%   |
| Canada       | 1         | 1.96%   |
| Brazil       | 1         | 1.96%   |
| Australia    | 1         | 1.96%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Ozersk                | 6         | 11.54%  |
| Rome                  | 5         | 9.62%   |
| Moscow                | 4         | 7.69%   |
| Riyadh                | 3         | 5.77%   |
| Gardony               | 3         | 5.77%   |
| Tampere               | 2         | 3.85%   |
| Washington            | 1         | 1.92%   |
| Urupes                | 1         | 1.92%   |
| Unterhaching          | 1         | 1.92%   |
| Ulan-Ude              | 1         | 1.92%   |
| Turin                 | 1         | 1.92%   |
| Turenki               | 1         | 1.92%   |
| Sydney                | 1         | 1.92%   |
| Surrey                | 1         | 1.92%   |
| Stourbridge           | 1         | 1.92%   |
| Sopron                | 1         | 1.92%   |
| Royal Tunbridge Wells | 1         | 1.92%   |
| Riga                  | 1         | 1.92%   |
| Reno                  | 1         | 1.92%   |
| Prague                | 1         | 1.92%   |
| Poznan                | 1         | 1.92%   |
| Portland              | 1         | 1.92%   |
| Murcia                | 1         | 1.92%   |
| Ladbergen             | 1         | 1.92%   |
| Ho Chi Minh City      | 1         | 1.92%   |
| Hamilton              | 1         | 1.92%   |
| Genzano di Roma       | 1         | 1.92%   |
| Fort Wayne            | 1         | 1.92%   |
| Bucharest             | 1         | 1.92%   |
| Bridgwater            | 1         | 1.92%   |
| Bloomsbury            | 1         | 1.92%   |
| Berlin                | 1         | 1.92%   |
| Amersfoort            | 1         | 1.92%   |
| Ahmedabad             | 1         | 1.92%   |
| Aachen                | 1         | 1.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 12     | 19.15%  |
| Samsung Electronics | 5         | 5      | 10.64%  |
| Kingston            | 5         | 5      | 10.64%  |
| Toshiba             | 4         | 5      | 8.51%   |
| Seagate             | 4         | 4      | 8.51%   |
| SanDisk             | 3         | 4      | 6.38%   |
| Intel               | 3         | 3      | 6.38%   |
| Maxtor              | 2         | 2      | 4.26%   |
| Hitachi             | 2         | 3      | 4.26%   |
| SK hynix            | 1         | 2      | 2.13%   |
| Lexar               | 1         | 1      | 2.13%   |
| JetFlash            | 1         | 1      | 2.13%   |
| Intenso             | 1         | 1      | 2.13%   |
| HGST                | 1         | 1      | 2.13%   |
| Hewlett-Packard     | 1         | 1      | 2.13%   |
| Generic             | 1         | 1      | 2.13%   |
| Dell                | 1         | 2      | 2.13%   |
| Crucial             | 1         | 2      | 2.13%   |
| China               | 1         | 1      | 2.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB            | 3         | 6.25%   |
| Samsung SSD 860 EVO 500GB         | 2         | 4.17%   |
| Samsung HD103UJ 1TB               | 2         | 4.17%   |
| Maxtor STM3250310AS 250GB         | 2         | 4.17%   |
| Kingston DataTraveler 3.0 32GB    | 2         | 4.17%   |
| WDC WDS240G2G0A-00JH30 240GB      | 1         | 2.08%   |
| WDC WDS120G2G0A-00JH30 120GB      | 1         | 2.08%   |
| WDC WD5003AZEX-00K3CA0 500GB      | 1         | 2.08%   |
| WDC WD5000AAKX-753CA1 500GB       | 1         | 2.08%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1         | 2.08%   |
| WDC WD2502ABYS-01B7A0 256GB       | 1         | 2.08%   |
| WDC WD20EFRX-68EUZN0 2TB          | 1         | 2.08%   |
| WDC WD200EB-00BHF0 20GB           | 1         | 2.08%   |
| WDC WD1600BEVT-00A23T0 160GB      | 1         | 2.08%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1         | 2.08%   |
| Toshiba DT01ACA200 2TB            | 1         | 2.08%   |
| SK hynix HFS128G39TND-N210A 128GB | 1         | 2.08%   |
| Seagate ST500VT000-1DK142 500GB   | 1         | 2.08%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 2.08%   |
| Seagate ST380011A 80GB            | 1         | 2.08%   |
| Seagate ST2000DL003-9VT166 2TB    | 1         | 2.08%   |
| SanDisk SDSSDH3512G 512GB         | 1         | 2.08%   |
| SanDisk Extreme SSD 250GB         | 1         | 2.08%   |
| SanDisk Cruzer Glide 16GB         | 1         | 2.08%   |
| Samsung HM080HC 80GB              | 1         | 2.08%   |
| Lexar USB Flash Drive 64GB        | 1         | 2.08%   |
| Kingston SA400S37480G 480GB       | 1         | 2.08%   |
| Kingston SA400S37240G 240GB       | 1         | 2.08%   |
| Kingston SA400S37120G 120GB       | 1         | 2.08%   |
| JetFlash Transcend 16GB           | 1         | 2.08%   |
| Intenso Rainbow Line 8GB          | 1         | 2.08%   |
| Intel SSDSC2KW120H6 120GB         | 1         | 2.08%   |
| Intel SSDSC2CW120A3 120GB         | 1         | 2.08%   |
| Intel SSDSC2BF180A4L 180GB        | 1         | 2.08%   |
| Hitachi HTS721060G9AT00 64GB      | 1         | 2.08%   |
| Hitachi HTS548040M9AT00 40GB      | 1         | 2.08%   |
| HGST HTS545050A7E680 500GB        | 1         | 2.08%   |
| HP v100w 8GB                      | 1         | 2.08%   |
| Generic Flash Disk 2GB            | 1         | 2.08%   |
| Dell PERC H710P 8TB               | 1         | 2.08%   |
| Crucial CT1000BX500SSD1 1TB       | 1         | 2.08%   |
| China SATA SSD 120GB              | 1         | 2.08%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 10     | 26.67%  |
| Toshiba             | 4         | 5      | 13.33%  |
| Seagate             | 4         | 4      | 13.33%  |
| Samsung Electronics | 3         | 3      | 10%     |
| Maxtor              | 2         | 2      | 6.67%   |
| Hitachi             | 2         | 3      | 6.67%   |
| Lexar               | 1         | 1      | 3.33%   |
| JetFlash            | 1         | 1      | 3.33%   |
| Intenso             | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |
| Hewlett-Packard     | 1         | 1      | 3.33%   |
| Generic             | 1         | 1      | 3.33%   |
| Dell                | 1         | 2      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 27.78%  |
| SanDisk             | 3         | 4      | 16.67%  |
| Intel               | 3         | 3      | 16.67%  |
| WDC                 | 2         | 2      | 11.11%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| SK hynix            | 1         | 2      | 5.56%   |
| Crucial             | 1         | 2      | 5.56%   |
| China               | 1         | 1      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 35     | 58.54%  |
| SSD  | 17        | 21     | 41.46%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 35        | 56     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 40     | 75%     |
| 0.51-1.0   | 8         | 10     | 18.18%  |
| 1.01-2.0   | 2         | 4      | 4.55%   |
| 4.01-10.0  | 1         | 2      | 2.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 17        | 33.33%  |
| 251-500        | 8         | 15.69%  |
| 51-100         | 8         | 15.69%  |
| 1-20           | 6         | 11.76%  |
| 501-1000       | 6         | 11.76%  |
| 21-50          | 2         | 3.92%   |
| 1001-2000      | 2         | 3.92%   |
| More than 3000 | 1         | 1.96%   |
| 2001-3000      | 1         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 36        | 65.45%  |
| 21-50          | 7         | 12.73%  |
| 51-100         | 5         | 9.09%   |
| 101-250        | 2         | 3.64%   |
| 1001-2000      | 2         | 3.64%   |
| More than 3000 | 1         | 1.82%   |
| 251-500        | 1         | 1.82%   |
| 501-1000       | 1         | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB      | 1         | 1      | 9.09%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1         | 1      | 9.09%   |
| SK hynix HFS128G39TND-N210A 128GB | 1         | 1      | 9.09%   |
| Seagate ST500VT000-1DK142 500GB   | 1         | 1      | 9.09%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 9.09%   |
| Seagate ST2000DL003-9VT166 2TB    | 1         | 1      | 9.09%   |
| Intel SSDSC2KW120H6 120GB         | 1         | 1      | 9.09%   |
| Intel SSDSC2CW120A3 120GB         | 1         | 1      | 9.09%   |
| Intel SSDSC2BF180A4L 180GB        | 1         | 1      | 9.09%   |
| Hitachi HTS721060G9AT00 64GB      | 1         | 1      | 9.09%   |
| Hitachi HTS548040M9AT00 40GB      | 1         | 2      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 3         | 3      | 27.27%  |
| Intel    | 3         | 3      | 27.27%  |
| WDC      | 2         | 2      | 18.18%  |
| Hitachi  | 2         | 3      | 18.18%  |
| SK hynix | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 50%     |
| Hitachi | 2         | 3      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 54.55%  |
| SSD  | 5         | 5      | 45.45%  |

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
| Works    | 21        | 35     | 52.5%   |
| Malfunc  | 11        | 12     | 27.5%   |
| Detected | 8         | 9      | 20%     |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 31        | 54.39%  |
| AMD                 | 13        | 22.81%  |
| Silicon Motion      | 3         | 5.26%   |
| SanDisk             | 2         | 3.51%   |
| Samsung Electronics | 2         | 3.51%   |
| Phison Electronics  | 2         | 3.51%   |
| VIA Technologies    | 1         | 1.75%   |
| Nvidia              | 1         | 1.75%   |
| Broadcom / LSI      | 1         | 1.75%   |
| ASMedia Technology  | 1         | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 7         | 10.61%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 7.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 7.58%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 6.06%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 4.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 4.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 3.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 3.03%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 3.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 3.03%   |
| AMD FCH SATA Controller D                                                        | 2         | 3.03%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.52%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.52%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 1.52%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.52%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.52%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.52%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 1         | 1.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.52%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.52%   |
| Intel 82801AA IDE Controller                                                     | 1         | 1.52%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 1         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 1.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 1.52%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 1         | 1.52%   |
| ASMedia ASM1061 SATA IDE Controller                                              | 1         | 1.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 39        | 65%     |
| IDE  | 11        | 18.33%  |
| NVMe | 9         | 15%     |
| RAID | 1         | 1.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 30        | 58.82%  |
| AMD          | 14        | 27.45%  |
| Unknown      | 3         | 5.88%   |
| Arm          | 2         | 3.92%   |
| Broadcom     | 1         | 1.96%   |
| 123456789ABC | 1         | 1.96%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 686-class                             | 11        | 21.15%  |
|                                             | 3         | 5.77%   |
| Arm Cortex-A53 r0p4 (v8-A)                  | 2         | 3.85%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz        | 1         | 1.92%   |
| Intel Xeon CPU E5-2450L 0 @ 1.80GHz         | 1         | 1.92%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.92%   |
| Intel Pentium M processor                   | 1         | 1.92%   |
| Intel Pentium III                           | 1         | 1.92%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 1.92%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 1.92%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.92%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.92%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.92%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 1.92%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.92%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1         | 1.92%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 1         | 1.92%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1         | 1.92%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.92%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.92%   |
| Intel Core 2 CPU T7                         | 1         | 1.92%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1         | 1.92%   |
| Broadcom BCM2711 (ARM Cortex-A72)           | 1         | 1.92%   |
| AMD Tillamook                               | 1         | 1.92%   |
| AMD Sempron 145 Processor                   | 1         | 1.92%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 1.92%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1         | 1.92%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1         | 1.92%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1         | 1.92%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1         | 1.92%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 1         | 1.92%   |
| AMD Phenom II X6 1055T Processor            | 1         | 1.92%   |
| AMD Phenom II X4 965 Processor              | 1         | 1.92%   |
| AMD FX-8350 Eight-Core Processor            | 1         | 1.92%   |
| AMD E-450 APU with Radeon HD Graphics       | 1         | 1.92%   |
| AMD Athlon II P340 Dual-Core Processor      | 1         | 1.92%   |
| AMD 686-class                               | 1         | 1.92%   |
| 123456789ABC Pentium 4                      | 1         | 1.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel 686-class   | 11        | 21.15%  |
| Other             | 8         | 15.38%  |
| Intel Core i5     | 5         | 9.62%   |
| Intel Core i7     | 4         | 7.69%   |
| Intel Xeon        | 2         | 3.85%   |
| Intel Pentium M   | 2         | 3.85%   |
| Intel Core i3     | 2         | 3.85%   |
| Intel Core 2      | 2         | 3.85%   |
| AMD Ryzen 5       | 2         | 3.85%   |
| AMD Ryzen 3       | 2         | 3.85%   |
| Intel Pentium III | 1         | 1.92%   |
| Intel Pentium     | 1         | 1.92%   |
| Intel Celeron     | 1         | 1.92%   |
| AMD Sempron       | 1         | 1.92%   |
| AMD Ryzen 9       | 1         | 1.92%   |
| AMD Ryzen 7       | 1         | 1.92%   |
| AMD Phenom II X6  | 1         | 1.92%   |
| AMD Phenom II X4  | 1         | 1.92%   |
| AMD FX            | 1         | 1.92%   |
| AMD E             | 1         | 1.92%   |
| AMD Athlon II     | 1         | 1.92%   |
| AMD 686-class     | 1         | 1.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 53.85%  |
| 2       | 10        | 19.23%  |
| 4       | 7         | 13.46%  |
| 8       | 4         | 7.69%   |
| 6       | 2         | 3.85%   |
| 12      | 1         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 35        | 67.31%  |
| Unknown | 17        | 32.69%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 28        | 53.85%  |
| 2       | 15        | 28.85%  |
| 1       | 9         | 17.31%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 21        | 40.38%  |
| IvyBridge   | 4         | 7.69%   |
| SandyBridge | 3         | 5.77%   |
| P6          | 3         | 5.77%   |
| K10         | 3         | 5.77%   |
| Haswell     | 3         | 5.77%   |
| Zen+        | 2         | 3.85%   |
| Zen 2       | 2         | 3.85%   |
| Zen         | 2         | 3.85%   |
| Core        | 2         | 3.85%   |
| Skylake     | 1         | 1.92%   |
| Silvermont  | 1         | 1.92%   |
| Piledriver  | 1         | 1.92%   |
| KabyLake    | 1         | 1.92%   |
| Geode       | 1         | 1.92%   |
| Broadwell   | 1         | 1.92%   |
| Bobcat      | 1         | 1.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 25        | 49.02%  |
| AMD                        | 14        | 27.45%  |
| Nvidia                     | 9         | 17.65%  |
| VIA Technologies           | 1         | 1.96%   |
| Trident Microsystems       | 1         | 1.96%   |
| Matrox Electronics Systems | 1         | 1.96%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 7.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 5.56%   |
| Nvidia GF114 [GeForce GTX 560]                                                           | 2         | 3.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 3.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 3.7%    |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.7%    |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]                        | 1         | 1.85%   |
| Trident Microsystems TGUI 9660/938x/968x                                                 | 1         | 1.85%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 1.85%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.85%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.85%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.85%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1         | 1.85%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.85%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 1.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1         | 1.85%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 1.85%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.85%   |
| Intel Iris Graphics 6100                                                                 | 1         | 1.85%   |
| Intel HD Graphics 630                                                                    | 1         | 1.85%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.85%   |
| Intel HD Graphics 530                                                                    | 1         | 1.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.85%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.85%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 1.85%   |
| AMD Tonga PRO [Radeon R9 285/380]                                                        | 1         | 1.85%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 1.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.85%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.85%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 1         | 1.85%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 1         | 1.85%   |
| AMD Chelsea XT GL [FirePro M4000]                                                        | 1         | 1.85%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 1.85%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 1         | 1.85%   |
| AMD Caicos PRO [Radeon HD 7450]                                                          | 1         | 1.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 18        | 35.29%  |
| 1 x AMD                  | 11        | 21.57%  |
| 1 x Nvidia               | 7         | 13.73%  |
| Other                    | 6         | 11.76%  |
| 2 x Intel                | 2         | 3.92%   |
| Intel + Nvidia           | 2         | 3.92%   |
| 2 x AMD                  | 1         | 1.96%   |
| 1 x VIA                  | 1         | 1.96%   |
| 1 x Trident Microsystems | 1         | 1.96%   |
| 1 x Matrox               | 1         | 1.96%   |
| Intel + AMD              | 1         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 37        | 69.81%  |
| Unknown | 16        | 30.19%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 48.08%  |
| 1.01-2.0   | 10        | 19.23%  |
| 0.01-0.5   | 9         | 17.31%  |
| 3.01-4.0   | 4         | 7.69%   |
| 0.51-1.0   | 3         | 5.77%   |
| 7.01-8.0   | 1         | 1.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 26.09%  |
| Goldstar            | 4         | 17.39%  |
| LG Display          | 3         | 13.04%  |
| Chimei Innolux      | 2         | 8.7%    |
| Apple               | 2         | 8.7%    |
| ViewSonic           | 1         | 4.35%   |
| Unknown (CDD)       | 1         | 4.35%   |
| LG Philips          | 1         | 4.35%   |
| Lenovo              | 1         | 4.35%   |
| Impression          | 1         | 4.35%   |
| Acer                | 1         | 4.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 2         | 8.7%    |
| ViewSonic LCD Monitor VSCD22B 1920x1080 520x290mm 23.4-inch           | 1         | 4.35%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch              | 1         | 4.35%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch  | 1         | 4.35%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch  | 1         | 4.35%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch     | 1         | 4.35%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch  | 1         | 4.35%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch           | 1         | 4.35%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch           | 1         | 4.35%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 4.35%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 1         | 4.35%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 1         | 4.35%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1         | 4.35%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1         | 4.35%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 1         | 4.35%   |
| Goldstar LCD Monitor GSM5AB6 1920x1080 480x270mm 21.7-inch            | 1         | 4.35%   |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                  | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 4.35%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch       | 1         | 4.35%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                | 1         | 4.35%   |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                 | 1         | 4.35%   |
| Acer SB220Q ACR06AB 1920x1080 480x270mm 21.7-inch                     | 1         | 4.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 8         | 34.78%  |
| 1366x768 (WXGA)  | 6         | 26.09%  |
| 1440x900 (WXGA+) | 3         | 13.04%  |
| 1280x800 (WXGA)  | 2         | 8.7%    |
| 2560x1600        | 1         | 4.35%   |
| 2560x1080        | 1         | 4.35%   |
| 1600x900 (HD+)   | 1         | 4.35%   |
| 1600x1200        | 1         | 4.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 5         | 21.74%  |
| 15     | 4         | 17.39%  |
| 19     | 3         | 13.04%  |
| 40     | 2         | 8.7%    |
| 23     | 2         | 8.7%    |
| 21     | 2         | 8.7%    |
| 52     | 1         | 4.35%   |
| 28     | 1         | 4.35%   |
| 27     | 1         | 4.35%   |
| 20     | 1         | 4.35%   |
| 12     | 1         | 4.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 7         | 30.43%  |
| 401-500     | 6         | 26.09%  |
| 501-600     | 3         | 13.04%  |
| 201-300     | 3         | 13.04%  |
| 801-900     | 2         | 8.7%    |
| 601-700     | 1         | 4.35%   |
| 1001-1500   | 1         | 4.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 15        | 65.22%  |
| 16/10 | 6         | 26.09%  |
| 4/3   | 1         | 4.35%   |
| 21/9  | 1         | 4.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 5         | 21.74%  |
| 201-250        | 4         | 17.39%  |
| 151-200        | 4         | 17.39%  |
| 101-110        | 3         | 13.04%  |
| 501-1000       | 2         | 8.7%    |
| More than 1000 | 1         | 4.35%   |
| 61-70          | 1         | 4.35%   |
| 301-350        | 1         | 4.35%   |
| 251-300        | 1         | 4.35%   |
| 91-100         | 1         | 4.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 12        | 52.17%  |
| 101-120 | 8         | 34.78%  |
| 1-50    | 1         | 4.35%   |
| 161-240 | 1         | 4.35%   |
| 121-160 | 1         | 4.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 28        | 53.85%  |
| 0     | 23        | 44.23%  |
| 2     | 1         | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 25        | 36.76%  |
| Intel                    | 19        | 27.94%  |
| Qualcomm Atheros         | 9         | 13.24%  |
| Broadcom                 | 5         | 7.35%   |
| Huawei Technologies      | 3         | 4.41%   |
| VIA Technologies         | 1         | 1.47%   |
| Oculus VR                | 1         | 1.47%   |
| Netchip Technology       | 1         | 1.47%   |
| Mercucys                 | 1         | 1.47%   |
| Marvell Technology Group | 1         | 1.47%   |
| D-Link                   | 1         | 1.47%   |
| 3Com                     | 1         | 1.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 23        | 28.4%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 5         | 6.17%   |
| Intel I211 Gigabit Network Connection                                                 | 3         | 3.7%    |
| Huawei USB Composite Device                                                           | 3         | 3.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 2         | 2.47%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 2.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 2.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 2.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 1.23%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 1.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 1.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 1.23%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 1.23%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.23%   |
| Oculus VR Rift S                                                                      | 1         | 1.23%   |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                                        | 1         | 1.23%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 1.23%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 1.23%   |
| Intel Wireless-AC 9260                                                                | 1         | 1.23%   |
| Intel Wireless 7265                                                                   | 1         | 1.23%   |
| Intel Wireless 7260                                                                   | 1         | 1.23%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 1.23%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.23%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.23%   |
| Intel PRO/100 VE Network Connection                                                   | 1         | 1.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 1.23%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.23%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 1.23%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 1.23%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 1.23%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller                     | 1         | 1.23%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                                    | 1         | 1.23%   |
| Intel 82577LM Gigabit Network Connection                                              | 1         | 1.23%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 1.23%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                                     | 1         | 1.23%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                      | 1         | 1.23%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                       | 1         | 1.23%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 1.23%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 1.23%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                                         | 1         | 1.23%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 15        | 53.57%  |
| Qualcomm Atheros      | 6         | 21.43%  |
| Broadcom              | 3         | 10.71%  |
| Realtek Semiconductor | 2         | 7.14%   |
| Mercucys              | 1         | 3.57%   |
| D-Link                | 1         | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 7.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 7.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 7.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 3.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1         | 3.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 3.57%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 3.57%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 3.57%   |
| Intel Wireless-AC 9260                                                                | 1         | 3.57%   |
| Intel Wireless 7265                                                                   | 1         | 3.57%   |
| Intel Wireless 7260                                                                   | 1         | 3.57%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 3.57%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 3.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 3.57%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 3.57%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 3.57%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 3.57%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 3.57%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 3.57%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 3.57%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 3.57%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 25        | 51.02%  |
| Intel                    | 12        | 24.49%  |
| Qualcomm Atheros         | 3         | 6.12%   |
| Huawei Technologies      | 3         | 6.12%   |
| Broadcom                 | 3         | 6.12%   |
| VIA Technologies         | 1         | 2.04%   |
| Marvell Technology Group | 1         | 2.04%   |
| 3Com                     | 1         | 2.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 23        | 46.94%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 10.2%   |
| Intel I211 Gigabit Network Connection                             | 3         | 6.12%   |
| Huawei USB Composite Device                                       | 3         | 6.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 4.08%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 2.04%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 2.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 2.04%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 2.04%   |
| Intel PRO/100 VE Network Connection                               | 1         | 2.04%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 2.04%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 2.04%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 2.04%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 2.04%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 2.04%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 2.04%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1         | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 45        | 60%     |
| WiFi     | 26        | 34.67%  |
| Modem    | 3         | 4%      |
| Unknown  | 1         | 1.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 42        | 75%     |
| WiFi     | 14        | 25%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 23        | 45.1%   |
| 1     | 19        | 37.25%  |
| 0     | 8         | 15.69%  |
| 3     | 1         | 1.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 82.69%  |
| Yes  | 9         | 17.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 8         | 50%     |
| Apple                   | 3         | 18.75%  |
| Realtek Semiconductor   | 2         | 12.5%   |
| IMC Networks            | 1         | 6.25%   |
| Cambridge Silicon Radio | 1         | 6.25%   |
| Broadcom                | 1         | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 18.75%  |
| Intel Bluetooth wireless interface                  | 2         | 12.5%   |
| Realtek  Bluetooth Adapter                          | 1         | 6.25%   |
| Realtek  Bluetooth 4.0 Adapter                      | 1         | 6.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 6.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 6.25%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 6.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 6.25%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 6.25%   |
| Apple Bluetooth Host Controller                     | 1         | 6.25%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 30        | 53.57%  |
| AMD                 | 16        | 28.57%  |
| Nvidia              | 5         | 8.93%   |
| Yamaha              | 1         | 1.79%   |
| VIA Technologies    | 1         | 1.79%   |
| Samsung Electronics | 1         | 1.79%   |
| Native Instruments  | 1         | 1.79%   |
| Logitech            | 1         | 1.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 10%     |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 7.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 5.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 4.29%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 2         | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.86%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.86%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 2.86%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.86%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 2.86%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 2.86%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 2.86%   |
| Yamaha AG06/AG03                                                                                  | 1         | 1.43%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 1.43%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                                        | 1         | 1.43%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 1.43%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.43%   |
| Native Instruments Komplete Audio 1                                                               | 1         | 1.43%   |
| Logitech Zone Wired Earbuds                                                                       | 1         | 1.43%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 1.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.43%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.43%   |
| Intel 82801AA AC'97 Audio Controller                                                              | 1         | 1.43%   |
| Intel 8 Series HD Audio Controller                                                                | 1         | 1.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.43%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 1.43%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                                          | 1         | 1.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 1.43%   |
| AMD High Definition Audio Controller                                                              | 1         | 1.43%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 1.43%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 1.43%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 1.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 8         | 20.51%  |
| Kingston            | 7         | 17.95%  |
| Samsung Electronics | 4         | 10.26%  |
| Micron Technology   | 4         | 10.26%  |
| Crucial             | 4         | 10.26%  |
| G.Skill             | 3         | 7.69%   |
| Patriot             | 2         | 5.13%   |
| Corsair             | 2         | 5.13%   |
| SK hynix            | 1         | 2.56%   |
| SHARETRONIC         | 1         | 2.56%   |
| Ramaxel Technology  | 1         | 2.56%   |
| Nanya Technology    | 1         | 2.56%   |
| A-DATA Technology   | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB DIMM 400MT/s                     | 1         | 2.33%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s               | 1         | 2.33%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 2.33%   |
| Unknown RAM Module 2GB SODIMM DDR3                         | 1         | 2.33%   |
| Unknown RAM Module 256MB SODIMM DDR                        | 1         | 2.33%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 2.33%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 1         | 2.33%   |
| Unknown RAM Module 128MB DIMM DRAM                         | 1         | 2.33%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s             | 1         | 2.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 1         | 2.33%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1         | 2.33%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s      | 1         | 2.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 2.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 1         | 2.33%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s      | 1         | 2.33%   |
| Samsung RAM M386B4G70DM0-YK03 32GB DIMM DDR3 1600MT/s      | 1         | 2.33%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 1         | 2.33%   |
| Patriot RAM PSD44G213382 4096MB DIMM DDR4 2133MT/s         | 1         | 2.33%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s             | 1         | 2.33%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 2.33%   |
| Micron RAM Module 8GB Chip LPDDR4                          | 1         | 2.33%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s      | 1         | 2.33%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s       | 1         | 2.33%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s     | 1         | 2.33%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s          | 1         | 2.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s        | 1         | 2.33%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB DIMM DDR3 1600MT/s       | 1         | 2.33%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2048MB SODIMM DDR3 1600MT/s | 1         | 2.33%   |
| Kingston RAM 99U5701-077.A00G 16GB DIMM DDR4 2667MT/s      | 1         | 2.33%   |
| Kingston RAM 99U5471-028.A00LF 4GB DIMM DDR3 667MT/s       | 1         | 2.33%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1333MT/s      | 1         | 2.33%   |
| Kingston RAM 9905428-026.A02LF 2048MB SODIMM DDR3 1066MT/s | 1         | 2.33%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s       | 1         | 2.33%   |
| G.Skill RAM F4-2800C17-8GVR 8192MB DIMM DDR4 2133MT/s      | 1         | 2.33%   |
| G.Skill RAM F3-1600C11-8G 8GB DIMM DDR3 1600MT/s           | 1         | 2.33%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s       | 1         | 2.33%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s      | 1         | 2.33%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s      | 1         | 2.33%   |
| Crucial RAM BLS4G4D240FSE.8FBD 4GB DIMM DDR4 2400MT/s      | 1         | 2.33%   |
| Corsair RAM CMV8GX3M1A160 8GB DIMM DDR3 800MT/s            | 1         | 2.33%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s      | 1         | 2.33%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 2933MT/s      | 1         | 2.33%   |
| A-DATA RAM Module 8GB DIMM DDR4 2666MT/s                   | 1         | 2.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 16        | 47.06%  |
| DDR4    | 10        | 29.41%  |
| DRAM    | 2         | 5.88%   |
| DDR2    | 2         | 5.88%   |
| SDRAM   | 1         | 2.94%   |
| LPDDR4  | 1         | 2.94%   |
| DDR     | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 21        | 61.76%  |
| SODIMM | 12        | 35.29%  |
| Chip   | 1         | 2.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 10        | 28.57%  |
| 4096  | 10        | 28.57%  |
| 2048  | 6         | 17.14%  |
| 16384 | 3         | 8.57%   |
| 512   | 2         | 5.71%   |
| 32768 | 1         | 2.86%   |
| 1024  | 1         | 2.86%   |
| 256   | 1         | 2.86%   |
| 128   | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 9         | 23.08%  |
| Unknown | 4         | 10.26%  |
| 2133    | 3         | 7.69%   |
| 1333    | 3         | 7.69%   |
| 3200    | 2         | 5.13%   |
| 2933    | 2         | 5.13%   |
| 2400    | 2         | 5.13%   |
| 1067    | 2         | 5.13%   |
| 800     | 2         | 5.13%   |
| 2667    | 1         | 2.56%   |
| 2666    | 1         | 2.56%   |
| 1867    | 1         | 2.56%   |
| 1334    | 1         | 2.56%   |
| 1066    | 1         | 2.56%   |
| 667     | 1         | 2.56%   |
| 533     | 1         | 2.56%   |
| 400     | 1         | 2.56%   |
| 266     | 1         | 2.56%   |
| 166     | 1         | 2.56%   |

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
| Chicony Electronics   | 4         | 30.77%  |
| Realtek Semiconductor | 2         | 15.38%  |
| Syntek                | 1         | 7.69%   |
| Silicon Motion        | 1         | 7.69%   |
| Quanta                | 1         | 7.69%   |
| Lenovo                | 1         | 7.69%   |
| ARC International     | 1         | 7.69%   |
| ALi                   | 1         | 7.69%   |
| Acer                  | 1         | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony integrated camera            | 2         | 15.38%  |
| Syntek Lenovo EasyCamera             | 1         | 7.69%   |
| Silicon Motion 300k Pixel Camera     | 1         | 7.69%   |
| Realtek USB Camera                   | 1         | 7.69%   |
| Realtek Acer 640 x 480 laptop camera | 1         | 7.69%   |
| Quanta VGA WebCam                    | 1         | 7.69%   |
| Lenovo Integrated Webcam [R5U877]    | 1         | 7.69%   |
| Chicony USB2.0 VGA UVC WebCam        | 1         | 7.69%   |
| Chicony Front Camera                 | 1         | 7.69%   |
| ARC International Camera             | 1         | 7.69%   |
| ALi Gateway Webcam                   | 1         | 7.69%   |
| Acer Integrated Camera               | 1         | 7.69%   |

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
| 0     | 21        | 40.38%  |
| 1     | 17        | 32.69%  |
| 2     | 7         | 13.46%  |
| 3     | 3         | 5.77%   |
| 5     | 2         | 3.85%   |
| 4     | 2         | 3.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 25        | 50%     |
| Net/wireless             | 11        | 22%     |
| Graphics card            | 5         | 10%     |
| Card reader              | 4         | 8%      |
| Storage                  | 2         | 4%      |
| Wireless                 | 1         | 2%      |
| Modem                    | 1         | 2%      |
| Bluetooth                | 1         | 2%      |

