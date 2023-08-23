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

Total: 92

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Gigabyte      | A320M-H-CF                  | Desktop     | [d1a2b99edc](https://bsd-hardware.info/?probe=d1a2b99edc) | Jul 28, 2023 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [a2119ba1fe](https://bsd-hardware.info/?probe=a2119ba1fe) | Jul 10, 2023 |
| Lenovo        | ThinkPad T430 2347A45       | Notebook    | [6969cd9e1a](https://bsd-hardware.info/?probe=6969cd9e1a) | Jun 20, 2023 |
| Acer          | Revo RN86                   | Desktop     | [2e52c2b9b2](https://bsd-hardware.info/?probe=2e52c2b9b2) | May 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [d6f92a5ecc](https://bsd-hardware.info/?probe=d6f92a5ecc) | Apr 28, 2023 |
| Samsung       | DP700A3D-A05UK SEC_SW_RE... | All in one  | [5718d8d05e](https://bsd-hardware.info/?probe=5718d8d05e) | Apr 24, 2023 |
| HP            | Pavilion 17                 | Notebook    | [0f891b4377](https://bsd-hardware.info/?probe=0f891b4377) | Apr 21, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [f73cb94828](https://bsd-hardware.info/?probe=f73cb94828) | Apr 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [8c93a7e552](https://bsd-hardware.info/?probe=8c93a7e552) | Mar 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [85fdc49ec4](https://bsd-hardware.info/?probe=85fdc49ec4) | Mar 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [8ae1891a85](https://bsd-hardware.info/?probe=8ae1891a85) | Feb 16, 2023 |
| Lenovo        | ThinkPad 13 20GJCTO1WW      | Notebook    | [59713ca193](https://bsd-hardware.info/?probe=59713ca193) | Feb 15, 2023 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [5921937764](https://bsd-hardware.info/?probe=5921937764) | Feb 06, 2023 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [5f6f4145d4](https://bsd-hardware.info/?probe=5f6f4145d4) | Feb 06, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [ae05d4c6cd](https://bsd-hardware.info/?probe=ae05d4c6cd) | Feb 06, 2023 |
| Lenovo        | ThinkPad T460s 20FAS3L00... | Notebook    | [ef6972d07a](https://bsd-hardware.info/?probe=ef6972d07a) | Jan 03, 2023 |
| Acer          | Revo RN86                   | Desktop     | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Dell          | Precision M4500             | Notebook    | [ab63467f38](https://bsd-hardware.info/?probe=ab63467f38) | Nov 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| Unknown       | Unknown                     | Desktop     | [5e2f93a960](https://bsd-hardware.info/?probe=5e2f93a960) | Aug 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [66fefba790](https://bsd-hardware.info/?probe=66fefba790) | Aug 06, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [aeee3a91e6](https://bsd-hardware.info/?probe=aeee3a91e6) | Jul 03, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [4e7d57df3b](https://bsd-hardware.info/?probe=4e7d57df3b) | Apr 18, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [6bf51cc915](https://bsd-hardware.info/?probe=6bf51cc915) | Mar 28, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [57765224eb](https://bsd-hardware.info/?probe=57765224eb) | Mar 18, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [0394e3272e](https://bsd-hardware.info/?probe=0394e3272e) | Mar 03, 2022 |
| KLLISRE       | X99-B5 V1.0                 | Desktop     | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| MiTAC         | 5033                        | Notebook    | [54df5c9e9e](https://bsd-hardware.info/?probe=54df5c9e9e) | Feb 10, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [18eeaf2963](https://bsd-hardware.info/?probe=18eeaf2963) | Dec 29, 2021 |
| Acer          | Revo RN86                   | Desktop     | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [14907c62f1](https://bsd-hardware.info/?probe=14907c62f1) | Dec 04, 2021 |
| HP            | 3397                        | Desktop     | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| Lenovo        | ThinkPad T420 4236D26       | Notebook    | [5c64875424](https://bsd-hardware.info/?probe=5c64875424) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [7259ec87e9](https://bsd-hardware.info/?probe=7259ec87e9) | Oct 05, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [81dd2ba2f0](https://bsd-hardware.info/?probe=81dd2ba2f0) | Oct 02, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b3a18fcab3](https://bsd-hardware.info/?probe=b3a18fcab3) | Sep 29, 2021 |
| Unknown       | Unknown                     | Desktop     | [2a56bcb7c1](https://bsd-hardware.info/?probe=2a56bcb7c1) | Sep 19, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [9ccf97d62c](https://bsd-hardware.info/?probe=9ccf97d62c) | Sep 05, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [4e3b1f226b](https://bsd-hardware.info/?probe=4e3b1f226b) | Jun 22, 2021 |
| Sony          | SVF1421DSGW                 | Notebook    | [abadb65058](https://bsd-hardware.info/?probe=abadb65058) | Jun 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Acer          | Revo RN86                   | Desktop     | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [364a778de1](https://bsd-hardware.info/?probe=364a778de1) | May 14, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [82e63b3fb9](https://bsd-hardware.info/?probe=82e63b3fb9) | Apr 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [0541b120c2](https://bsd-hardware.info/?probe=0541b120c2) | Apr 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [91dd02d436](https://bsd-hardware.info/?probe=91dd02d436) | Mar 30, 2021 |
| Unknown       | Unknown                     | Desktop     | [a1220fba93](https://bsd-hardware.info/?probe=a1220fba93) | Mar 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [edea2d1a64](https://bsd-hardware.info/?probe=edea2d1a64) | Mar 18, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [360f29bf3b](https://bsd-hardware.info/?probe=360f29bf3b) | Mar 05, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [f6e7638f87](https://bsd-hardware.info/?probe=f6e7638f87) | Mar 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [1afd7d4381](https://bsd-hardware.info/?probe=1afd7d4381) | Feb 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [4c0171bc04](https://bsd-hardware.info/?probe=4c0171bc04) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [a5fa760573](https://bsd-hardware.info/?probe=a5fa760573) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [289177c624](https://bsd-hardware.info/?probe=289177c624) | Jan 02, 2021 |
| IBM           | ThinkPad R51 2887AVG        | Notebook    | [88d4fc2693](https://bsd-hardware.info/?probe=88d4fc2693) | Dec 30, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | Notebook    | [eda02dc46b](https://bsd-hardware.info/?probe=eda02dc46b) | Dec 25, 2020 |
| Fujitsu Si... | AMILO L7310                 | Notebook    | [0603b64315](https://bsd-hardware.info/?probe=0603b64315) | Dec 25, 2020 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [647ab5967e](https://bsd-hardware.info/?probe=647ab5967e) | Dec 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| ASUSTek       | E45M1-I DELUXE              | Desktop     | [8e767b517d](https://bsd-hardware.info/?probe=8e767b517d) | Dec 16, 2020 |
| Unknown       | Unknown                     | Desktop     | [153be3caa3](https://bsd-hardware.info/?probe=153be3caa3) | Nov 28, 2020 |
| HP            | System Board R3A            | Desktop     | [80593fc3da](https://bsd-hardware.info/?probe=80593fc3da) | Nov 03, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [615ac68e50](https://bsd-hardware.info/?probe=615ac68e50) | Oct 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [d08d610bd0](https://bsd-hardware.info/?probe=d08d610bd0) | Oct 29, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [a4e45f3551](https://bsd-hardware.info/?probe=a4e45f3551) | Oct 22, 2020 |
| ASUSTek       | B150M-K                     | Desktop     | [135db0e455](https://bsd-hardware.info/?probe=135db0e455) | Oct 22, 2020 |
| Unknown       | Unknown                     | Desktop     | [223aa9e0a3](https://bsd-hardware.info/?probe=223aa9e0a3) | Oct 22, 2020 |
| Gigabyte      | P75-D3                      | Desktop     | [980218cf46](https://bsd-hardware.info/?probe=980218cf46) | Oct 02, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [95b75130f4](https://bsd-hardware.info/?probe=95b75130f4) | Sep 26, 2020 |
| Dell          | 0W7H8C A03                  | Server      | [639b47e2ad](https://bsd-hardware.info/?probe=639b47e2ad) | Sep 21, 2020 |
| Acer          | Revo RN86                   | Desktop     | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| MSI           | KA790GX                     | Desktop     | [bba5499a4b](https://bsd-hardware.info/?probe=bba5499a4b) | Aug 29, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| eMachines     | eME642G                     | Notebook    | [42027dfbb9](https://bsd-hardware.info/?probe=42027dfbb9) | Jul 25, 2020 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [35c4a3608e](https://bsd-hardware.info/?probe=35c4a3608e) | Jul 19, 2020 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [9fbca0a216](https://bsd-hardware.info/?probe=9fbca0a216) | Jun 17, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [99cf14c489](https://bsd-hardware.info/?probe=99cf14c489) | Jun 03, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a49cf5c20b](https://bsd-hardware.info/?probe=a49cf5c20b) | May 28, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [14e00aa09f](https://bsd-hardware.info/?probe=14e00aa09f) | May 25, 2020 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [6cb240a9f6](https://bsd-hardware.info/?probe=6cb240a9f6) | May 25, 2020 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [8ba62bd121](https://bsd-hardware.info/?probe=8ba62bd121) | May 25, 2020 |
| Lenovo        | ThinkPad X240 20AMS0J01N    | Notebook    | [4df07718d1](https://bsd-hardware.info/?probe=4df07718d1) | May 23, 2020 |
| Unknown       | Unknown                     | Desktop     | [d3ad2b17ed](https://bsd-hardware.info/?probe=d3ad2b17ed) | May 22, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [3258f01592](https://bsd-hardware.info/?probe=3258f01592) | May 16, 2020 |
| ASUSTek       | A3L                         | Notebook    | [6b65fcf9c1](https://bsd-hardware.info/?probe=6b65fcf9c1) | May 15, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [cd45078232](https://bsd-hardware.info/?probe=cd45078232) | May 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| NetBSD 9.2        | 13        | 17.57%  |
| NetBSD 9.1        | 11        | 14.86%  |
| NetBSD 9.3        | 8         | 10.81%  |
| NetBSD 9.0_STABLE | 8         | 10.81%  |
| NetBSD 9.0        | 6         | 8.11%   |
| NetBSD 10.0_BETA  | 4         | 5.41%   |
| NetBSD 9.99.94    | 3         | 4.05%   |
| NetBSD 9.99.93    | 3         | 4.05%   |
| NetBSD 9.1_STABLE | 3         | 4.05%   |
| NetBSD 9.99.77    | 2         | 2.7%    |
| NetBSD 9.2_STABLE | 2         | 2.7%    |
| NetBSD 9.99.85    | 1         | 1.35%   |
| NetBSD 9.99.81    | 1         | 1.35%   |
| NetBSD 9.99.74    | 1         | 1.35%   |
| NetBSD 9.99.71    | 1         | 1.35%   |
| NetBSD 9.99.61    | 1         | 1.35%   |
| NetBSD 9.99.23    | 1         | 1.35%   |
| NetBSD 9.99.107   | 1         | 1.35%   |
| NetBSD 9.3_STABLE | 1         | 1.35%   |
| NetBSD 8.99.51    | 1         | 1.35%   |
| NetBSD 7.2        | 1         | 1.35%   |
| NetBSD 10.99.1    | 1         | 1.35%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| NetBSD | 65        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 53        | 81.54%  |
| i386   | 6         | 9.23%   |
| evbarm | 6         | 9.23%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 27        | 40.3%   |
| XFCE         | 13        | 19.4%   |
| helloDesktop | 9         | 13.43%  |
| Fluxbox      | 4         | 5.97%   |
| CTWM         | 4         | 5.97%   |
| MATE         | 2         | 2.99%   |
| DWM          | 2         | 2.99%   |
| Xfwm4        | 1         | 1.49%   |
| sdorfehs     | 1         | 1.49%   |
| Ratpoison    | 1         | 1.49%   |
| PekWM        | 1         | 1.49%   |
| LXQt         | 1         | 1.49%   |
| Awesome      | 1         | 1.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 48        | 73.85%  |
| Console | 17        | 26.15%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 59        | 90.77%  |
| XDM     | 2         | 3.08%   |
| GDM     | 2         | 3.08%   |
| SLiM    | 1         | 1.54%   |
| LightDM | 1         | 1.54%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 50        | 72.46%  |
| en_US   | 11        | 15.94%  |
| ru_RU   | 3         | 4.35%   |
| fi_FI   | 2         | 2.9%    |
| hu_HU   | 1         | 1.45%   |
| en_GB   | 1         | 1.45%   |
| C       | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 62        | 95.38%  |
| EFI  | 3         | 4.62%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 64        | 98.46%  |
| Unknown | 1         | 1.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 41        | 63.08%  |
| Unknown | 24        | 36.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 18        | 27.69%  |
| Lenovo                  | 8         | 12.31%  |
| ASUSTek Computer        | 8         | 12.31%  |
| Gigabyte Technology     | 6         | 9.23%   |
| Intel                   | 3         | 4.62%   |
| ASRock                  | 3         | 4.62%   |
| Acer                    | 3         | 4.62%   |
| MSI                     | 2         | 3.08%   |
| Hewlett-Packard         | 2         | 3.08%   |
| Dell                    | 2         | 3.08%   |
| Toshiba                 | 1         | 1.54%   |
| Sony                    | 1         | 1.54%   |
| Samsung Electronics     | 1         | 1.54%   |
| Raspberry Pi Foundation | 1         | 1.54%   |
| MiTAC                   | 1         | 1.54%   |
| KLLISRE                 | 1         | 1.54%   |
| IBM                     | 1         | 1.54%   |
| Fujitsu Siemens         | 1         | 1.54%   |
| eMachines               | 1         | 1.54%   |
| Apple                   | 1         | 1.54%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 18        | 27.69%  |
| ASUS PRIME A320M-K                          | 2         | 3.08%   |
| Toshiba Satellite A100                      | 1         | 1.54%   |
| Sony SVF1421DSGW                            | 1         | 1.54%   |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 1.54%   |
| RPi Raspberry Pi 4 Model B                  | 1         | 1.54%   |
| MSI MS-7B86                                 | 1         | 1.54%   |
| MSI MS-7551                                 | 1         | 1.54%   |
| MiTAC 5033                                  | 1         | 1.54%   |
| Lenovo ThinkPad X240 20AMS0J01N             | 1         | 1.54%   |
| Lenovo ThinkPad T510 4313CTO                | 1         | 1.54%   |
| Lenovo ThinkPad T460s 20FAS3L002            | 1         | 1.54%   |
| Lenovo ThinkPad T430s 23564H3               | 1         | 1.54%   |
| Lenovo ThinkPad T430 2347A45                | 1         | 1.54%   |
| Lenovo ThinkPad T420 4236D26                | 1         | 1.54%   |
| Lenovo ThinkPad 13 20GJCTO1WW               | 1         | 1.54%   |
| Lenovo G500 20236                           | 1         | 1.54%   |
| KLLISRE X99-B5 V1.0                         | 1         | 1.54%   |
| Intel NUC5PPYB H76558-102                   | 1         | 1.54%   |
| Intel NUC5i7RYB H73774-102                  | 1         | 1.54%   |
| Intel DN2820FYK H24582-203                  | 1         | 1.54%   |
| IBM ThinkPad R51 2887AVG                    | 1         | 1.54%   |
| HP Vectra                                   | 1         | 1.54%   |
| HP Pavilion 17                              | 1         | 1.54%   |
| Gigabyte Z170X-Gaming 3                     | 1         | 1.54%   |
| Gigabyte X570 AORUS PRO                     | 1         | 1.54%   |
| Gigabyte P75-D3                             | 1         | 1.54%   |
| Gigabyte H61M-S2PV                          | 1         | 1.54%   |
| Gigabyte A320M-H                            | 1         | 1.54%   |
| Gigabyte 970A-D3P                           | 1         | 1.54%   |
| Fujitsu Siemens AMILO L7310                 | 1         | 1.54%   |
| eMachines eME642G                           | 1         | 1.54%   |
| Dell Precision M4500                        | 1         | 1.54%   |
| Dell PowerEdge T320                         | 1         | 1.54%   |
| ASUS X555LJ                                 | 1         | 1.54%   |
| ASUS TUF B450-PLUS GAMING                   | 1         | 1.54%   |
| ASUS E45M1-I DELUXE                         | 1         | 1.54%   |
| ASUS B150M-K                                | 1         | 1.54%   |
| ASUS All Series                             | 1         | 1.54%   |
| ASUS A3L                                    | 1         | 1.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 18        | 27.69%  |
| Lenovo ThinkPad       | 7         | 10.77%  |
| ASUS PRIME            | 2         | 3.08%   |
| Acer Aspire           | 2         | 3.08%   |
| Toshiba Satellite     | 1         | 1.54%   |
| Sony SVF1421DSGW      | 1         | 1.54%   |
| Samsung DP700A3D      | 1         | 1.54%   |
| RPi Raspberry         | 1         | 1.54%   |
| MSI MS-7B86           | 1         | 1.54%   |
| MSI MS-7551           | 1         | 1.54%   |
| MiTAC 5033            | 1         | 1.54%   |
| Lenovo G500           | 1         | 1.54%   |
| KLLISRE X99-B5        | 1         | 1.54%   |
| Intel NUC5PPYB        | 1         | 1.54%   |
| Intel NUC5i7RYB       | 1         | 1.54%   |
| Intel DN2820FYK       | 1         | 1.54%   |
| IBM ThinkPad          | 1         | 1.54%   |
| HP Vectra             | 1         | 1.54%   |
| HP Pavilion           | 1         | 1.54%   |
| Gigabyte Z170X-Gaming | 1         | 1.54%   |
| Gigabyte X570         | 1         | 1.54%   |
| Gigabyte P75-D3       | 1         | 1.54%   |
| Gigabyte H61M-S2PV    | 1         | 1.54%   |
| Gigabyte A320M-H      | 1         | 1.54%   |
| Gigabyte 970A-D3P     | 1         | 1.54%   |
| Fujitsu Siemens AMILO | 1         | 1.54%   |
| eMachines eME642G     | 1         | 1.54%   |
| Dell Precision        | 1         | 1.54%   |
| Dell PowerEdge        | 1         | 1.54%   |
| ASUS X555LJ           | 1         | 1.54%   |
| ASUS TUF              | 1         | 1.54%   |
| ASUS E45M1-I          | 1         | 1.54%   |
| ASUS B150M-K          | 1         | 1.54%   |
| ASUS All              | 1         | 1.54%   |
| ASUS A3L              | 1         | 1.54%   |
| ASRock X470           | 1         | 1.54%   |
| ASRock N68-VS3        | 1         | 1.54%   |
| ASRock 970            | 1         | 1.54%   |
| Apple MacBook2        | 1         | 1.54%   |
| Acer Revo             | 1         | 1.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 17        | 26.15%  |
| 2013    | 8         | 12.31%  |
| 2020    | 7         | 10.77%  |
| 2014    | 4         | 6.15%   |
| 2021    | 3         | 4.62%   |
| 2018    | 3         | 4.62%   |
| 2017    | 3         | 4.62%   |
| 2011    | 3         | 4.62%   |
| 2010    | 3         | 4.62%   |
| 2019    | 2         | 3.08%   |
| 2016    | 2         | 3.08%   |
| 2015    | 2         | 3.08%   |
| 2007    | 2         | 3.08%   |
| 2005    | 2         | 3.08%   |
| 2022    | 1         | 1.54%   |
| 2012    | 1         | 1.54%   |
| 2006    | 1         | 1.54%   |
| 2001    | 1         | 1.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 39        | 60%     |
| Notebook       | 21        | 32.31%  |
| Mini pc        | 2         | 3.08%   |
| System on chip | 1         | 1.54%   |
| All in one     | 1         | 1.54%   |
| Server         | 1         | 1.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 64        | 98.46%  |
| Yes  | 1         | 1.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 19        | 29.23%  |
| 3.01-4.0    | 10        | 15.38%  |
| 16.01-24.0  | 10        | 15.38%  |
| 8.01-16.0   | 9         | 13.85%  |
| 0.51-1.0    | 4         | 6.15%   |
| 32.01-64.0  | 3         | 4.62%   |
| 1.01-2.0    | 3         | 4.62%   |
| 0.01-0.5    | 3         | 4.62%   |
| 24.01-32.0  | 1         | 1.54%   |
| 64.01-256.0 | 1         | 1.54%   |
| 0           | 1         | 1.54%   |
| Unknown     | 1         | 1.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| Unknown | 65        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 28        | 40.58%  |
| 0      | 28        | 40.58%  |
| 2      | 10        | 14.49%  |
| 3      | 2         | 2.9%    |
| 4      | 1         | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 62        | 95.38%  |
| Yes       | 3         | 4.62%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 84.62%  |
| No        | 10        | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 37        | 56.92%  |
| No        | 28        | 43.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 64.62%  |
| Yes       | 23        | 35.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Russia       | 12        | 18.46%  |
| USA          | 7         | 10.77%  |
| Italy        | 7         | 10.77%  |
| Germany      | 6         | 9.23%   |
| UK           | 5         | 7.69%   |
| Hungary      | 4         | 6.15%   |
| France       | 4         | 6.15%   |
| Saudi Arabia | 3         | 4.62%   |
| Finland      | 3         | 4.62%   |
| Spain        | 2         | 3.08%   |
| Romania      | 2         | 3.08%   |
| Vietnam      | 1         | 1.54%   |
| Poland       | 1         | 1.54%   |
| Norway       | 1         | 1.54%   |
| Netherlands  | 1         | 1.54%   |
| Latvia       | 1         | 1.54%   |
| India        | 1         | 1.54%   |
| Czechia      | 1         | 1.54%   |
| Canada       | 1         | 1.54%   |
| Brazil       | 1         | 1.54%   |
| Australia    | 1         | 1.54%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Ozersk                | 7         | 10.61%  |
| Rome                  | 6         | 9.09%   |
| Moscow                | 4         | 6.06%   |
| Riyadh                | 3         | 4.55%   |
| Lille                 | 3         | 4.55%   |
| Gardony               | 3         | 4.55%   |
| Tampere               | 2         | 3.03%   |
| Bucharest             | 2         | 3.03%   |
| Berlin                | 2         | 3.03%   |
| Washington            | 1         | 1.52%   |
| Urupes                | 1         | 1.52%   |
| Unterhaching          | 1         | 1.52%   |
| Ulan-Ude              | 1         | 1.52%   |
| Turin                 | 1         | 1.52%   |
| Turenki               | 1         | 1.52%   |
| Sydney                | 1         | 1.52%   |
| Surrey                | 1         | 1.52%   |
| Sun Prairie           | 1         | 1.52%   |
| Stourbridge           | 1         | 1.52%   |
| Sopron                | 1         | 1.52%   |
| Sandnes               | 1         | 1.52%   |
| Royal Tunbridge Wells | 1         | 1.52%   |
| Riga                  | 1         | 1.52%   |
| Reno                  | 1         | 1.52%   |
| Prague                | 1         | 1.52%   |
| Poznan                | 1         | 1.52%   |
| Portland              | 1         | 1.52%   |
| Murcia                | 1         | 1.52%   |
| London                | 1         | 1.52%   |
| Lohr a. Main          | 1         | 1.52%   |
| Ladbergen             | 1         | 1.52%   |
| Kalispell             | 1         | 1.52%   |
| Ho Chi Minh City      | 1         | 1.52%   |
| Hamilton              | 1         | 1.52%   |
| Genzano di Roma       | 1         | 1.52%   |
| Fort Wayne            | 1         | 1.52%   |
| Carry-le-Rouet        | 1         | 1.52%   |
| Bridgwater            | 1         | 1.52%   |
| Bormujos              | 1         | 1.52%   |
| Bloomsbury            | 1         | 1.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 12     | 17.65%  |
| Seagate             | 5         | 5      | 9.8%    |
| Samsung Electronics | 5         | 5      | 9.8%    |
| Kingston            | 5         | 5      | 9.8%    |
| Toshiba             | 4         | 6      | 7.84%   |
| SanDisk             | 4         | 5      | 7.84%   |
| Intel               | 3         | 3      | 5.88%   |
| Crucial             | 3         | 4      | 5.88%   |
| Maxtor              | 2         | 2      | 3.92%   |
| Hitachi             | 2         | 3      | 3.92%   |
| SK hynix            | 1         | 2      | 1.96%   |
| Lexar               | 1         | 1      | 1.96%   |
| JetFlash            | 1         | 1      | 1.96%   |
| Intenso             | 1         | 1      | 1.96%   |
| HGST                | 1         | 1      | 1.96%   |
| Hewlett-Packard     | 1         | 1      | 1.96%   |
| Generic             | 1         | 1      | 1.96%   |
| Dell                | 1         | 2      | 1.96%   |
| China               | 1         | 1      | 1.96%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB              | 3         | 5.77%   |
| SanDisk Extreme SSD 500GB           | 2         | 3.85%   |
| Samsung SSD 860 EVO 500GB           | 2         | 3.85%   |
| Samsung HD103UJ 1TB                 | 2         | 3.85%   |
| Maxtor STM3250310AS 250GB           | 2         | 3.85%   |
| Kingston DataTraveler 3.0 32GB      | 2         | 3.85%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1.92%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 1.92%   |
| WDC WD5003AZEX-00K3CA0 500GB        | 1         | 1.92%   |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 1.92%   |
| WDC WD5000AACS-00ZUB0 500GB         | 1         | 1.92%   |
| WDC WD2502ABYS-01B7A0 256GB         | 1         | 1.92%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 1.92%   |
| WDC WD200EB-00BHF0 20GB             | 1         | 1.92%   |
| WDC WD1600BEVT-00A23T0 160GB        | 1         | 1.92%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1.92%   |
| Toshiba DT01ACA200 2TB              | 1         | 1.92%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1.92%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1.92%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1.92%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1.92%   |
| Seagate ST380011A 80GB              | 1         | 1.92%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1.92%   |
| SanDisk SDSSDH3512G 512GB           | 1         | 1.92%   |
| SanDisk Cruzer Glide 16GB           | 1         | 1.92%   |
| Samsung HM080HC 80GB                | 1         | 1.92%   |
| Lexar USB Flash Drive 64GB          | 1         | 1.92%   |
| Kingston SA400S37480G 480GB         | 1         | 1.92%   |
| Kingston SA400S37240G 240GB         | 1         | 1.92%   |
| Kingston SA400S37120G 120GB         | 1         | 1.92%   |
| JetFlash Transcend 16GB             | 1         | 1.92%   |
| Intenso Rainbow Line 8GB            | 1         | 1.92%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1.92%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 1.92%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1.92%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1.92%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 1.92%   |
| HGST HTS545050A7E680 500GB          | 1         | 1.92%   |
| HP v100w 8GB                        | 1         | 1.92%   |
| Generic Flash Disk 2GB              | 1         | 1.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 10     | 25.81%  |
| Seagate             | 5         | 5      | 16.13%  |
| Toshiba             | 4         | 6      | 12.9%   |
| Samsung Electronics | 3         | 3      | 9.68%   |
| Maxtor              | 2         | 2      | 6.45%   |
| Hitachi             | 2         | 3      | 6.45%   |
| Lexar               | 1         | 1      | 3.23%   |
| JetFlash            | 1         | 1      | 3.23%   |
| Intenso             | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |
| Hewlett-Packard     | 1         | 1      | 3.23%   |
| Generic             | 1         | 1      | 3.23%   |
| Dell                | 1         | 2      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 23.81%  |
| SanDisk             | 4         | 5      | 19.05%  |
| Intel               | 3         | 3      | 14.29%  |
| Crucial             | 3         | 4      | 14.29%  |
| WDC                 | 2         | 2      | 9.52%   |
| Samsung Electronics | 2         | 2      | 9.52%   |
| SK hynix            | 1         | 2      | 4.76%   |
| China               | 1         | 1      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 37     | 55.56%  |
| SSD  | 20        | 24     | 44.44%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 61     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 43     | 75%     |
| 0.51-1.0   | 9         | 12     | 18.75%  |
| 1.01-2.0   | 2         | 4      | 4.17%   |
| 4.01-10.0  | 1         | 2      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 29.23%  |
| 251-500        | 13        | 20%     |
| 501-1000       | 9         | 13.85%  |
| 51-100         | 8         | 12.31%  |
| 1-20           | 7         | 10.77%  |
| 21-50          | 3         | 4.62%   |
| 2001-3000      | 3         | 4.62%   |
| 1001-2000      | 2         | 3.08%   |
| More than 3000 | 1         | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 66.2%   |
| 21-50          | 10        | 14.08%  |
| 51-100         | 6         | 8.45%   |
| 101-250        | 3         | 4.23%   |
| 1001-2000      | 2         | 2.82%   |
| More than 3000 | 1         | 1.41%   |
| 251-500        | 1         | 1.41%   |
| 501-1000       | 1         | 1.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1      | 8.33%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1      | 8.33%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1      | 8.33%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 8.33%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1      | 8.33%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 8.33%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1      | 8.33%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 8.33%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 1      | 8.33%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1      | 8.33%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 8.33%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 2      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 4      | 33.33%  |
| Intel    | 3         | 3      | 25%     |
| WDC      | 2         | 2      | 16.67%  |
| Hitachi  | 2         | 3      | 16.67%  |
| SK hynix | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 57.14%  |
| Hitachi | 2         | 3      | 28.57%  |
| WDC     | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 8      | 58.33%  |
| SSD  | 5         | 5      | 41.67%  |

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
| Works    | 23        | 38     | 52.27%  |
| Malfunc  | 12        | 13     | 27.27%  |
| Detected | 9         | 10     | 20.45%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 43        | 58.9%   |
| AMD                       | 16        | 21.92%  |
| Silicon Motion            | 3         | 4.11%   |
| SanDisk                   | 2         | 2.74%   |
| Samsung Electronics       | 2         | 2.74%   |
| Phison Electronics        | 2         | 2.74%   |
| VIA Technologies          | 1         | 1.37%   |
| Nvidia                    | 1         | 1.37%   |
| Micron/Crucial Technology | 1         | 1.37%   |
| Broadcom / LSI            | 1         | 1.37%   |
| ASMedia Technology        | 1         | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 9.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 7.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 7.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 4.82%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 4.82%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 3.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 3.61%   |
| AMD FCH SATA Controller D                                                        | 3         | 3.61%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.41%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 2.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 2.41%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 2.41%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.2%    |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.2%    |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 1.2%    |
| Phison E12 NVMe Controller                                                       | 1         | 1.2%    |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.2%    |
| Nvidia MCP61 IDE                                                                 | 1         | 1.2%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 1.2%    |
| Intel product 54d3                                                               | 1         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.2%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.2%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.2%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.2%    |
| Intel 82801AA IDE Controller                                                     | 1         | 1.2%    |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 54        | 70.13%  |
| IDE  | 12        | 15.58%  |
| NVMe | 10        | 12.99%  |
| RAID | 1         | 1.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 41        | 63.08%  |
| AMD          | 17        | 26.15%  |
| Unknown      | 3         | 4.62%   |
| Arm          | 2         | 3.08%   |
| Broadcom     | 1         | 1.54%   |
| 123456789ABC | 1         | 1.54%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel 686-class                       | 14        | 20.9%   |
|                                       | 3         | 4.48%   |
| Arm Cortex-A53 r0p4 (v8-A)            | 2         | 2.99%   |
| AMD 686-class                         | 2         | 2.99%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz  | 1         | 1.49%   |
| Intel Xeon CPU E5-2450L 0 @ 1.80GHz   | 1         | 1.49%   |
| Intel Pentium M processor 1.60GHz     | 1         | 1.49%   |
| Intel Pentium M processor             | 1         | 1.49%   |
| Intel Pentium III                     | 1         | 1.49%   |
| Intel Pentium CPU 2020M @ 2.40GHz     | 1         | 1.49%   |
| Intel N100                            | 1         | 1.49%   |
| Intel Core i7-6700K CPU @ 4.00GHz     | 1         | 1.49%   |
| Intel Core i7-5557U CPU @ 3.10GHz     | 1         | 1.49%   |
| Intel Core i7-5500U CPU @ 2.40GHz     | 1         | 1.49%   |
| Intel Core i7-3770 CPU @ 3.40GHz      | 1         | 1.49%   |
| Intel Core i7-3520M CPU @ 2.90GHz     | 1         | 1.49%   |
| Intel Core i7-2640M CPU @ 2.80GHz     | 1         | 1.49%   |
| Intel Core i5-9400T CPU @ 1.80GHz     | 1         | 1.49%   |
| Intel Core i5-7400 CPU @ 3.00GHz      | 1         | 1.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz     | 1         | 1.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz     | 1         | 1.49%   |
| Intel Core i5-4310M CPU @ 2.70GHz     | 1         | 1.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz     | 1         | 1.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz     | 1         | 1.49%   |
| Intel Core i5-2320 CPU @ 3.00GHz      | 1         | 1.49%   |
| Intel Core i5 CPU M 560 @ 2.67GH      | 1         | 1.49%   |
| Intel Core i5 CPU M 540 @ 2.53GHz     | 1         | 1.49%   |
| Intel Core i3-4150 CPU @ 3.50GHz      | 1         | 1.49%   |
| Intel Core i3-3220T CPU @ 2.80GHz     | 1         | 1.49%   |
| Intel Core i3-3217U CPU @ 1.80GHz     | 1         | 1.49%   |
| Intel Core 2 CPU T7200 @ 2.00GHz      | 1         | 1.49%   |
| Intel Core 2 CPU T7                   | 1         | 1.49%   |
| Intel Celeron CPU N2830 @ 2.16GHz     | 1         | 1.49%   |
| Broadcom BCM2711 (ARM Cortex-A72)     | 1         | 1.49%   |
| AMD Tillamook                         | 1         | 1.49%   |
| AMD Sempron 145 Processor             | 1         | 1.49%   |
| AMD Ryzen 9 3900X 12-Core Processor   | 1         | 1.49%   |
| AMD Ryzen 7 2700 Eight-Core Processor | 1         | 1.49%   |
| AMD Ryzen 5 3600 6-Core Processor     | 1         | 1.49%   |
| AMD Ryzen 5 2600 Six-Core Processor   | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel 686-class   | 14        | 20.9%   |
| Intel Core i5     | 10        | 14.93%  |
| Other             | 9         | 13.43%  |
| Intel Core i7     | 6         | 8.96%   |
| Intel Core i3     | 3         | 4.48%   |
| AMD Ryzen 3       | 3         | 4.48%   |
| Intel Xeon        | 2         | 2.99%   |
| Intel Pentium M   | 2         | 2.99%   |
| Intel Core 2      | 2         | 2.99%   |
| AMD Ryzen 5       | 2         | 2.99%   |
| AMD 686-class     | 2         | 2.99%   |
| Intel Pentium III | 1         | 1.49%   |
| Intel Pentium     | 1         | 1.49%   |
| Intel Celeron     | 1         | 1.49%   |
| AMD Sempron       | 1         | 1.49%   |
| AMD Ryzen 9       | 1         | 1.49%   |
| AMD Ryzen 7       | 1         | 1.49%   |
| AMD Phenom II X6  | 1         | 1.49%   |
| AMD Phenom II X4  | 1         | 1.49%   |
| AMD FX            | 1         | 1.49%   |
| AMD E             | 1         | 1.49%   |
| AMD Athlon II     | 1         | 1.49%   |
| AMD A10           | 1         | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 33        | 49.25%  |
| 2       | 16        | 23.88%  |
| 4       | 10        | 14.93%  |
| 8       | 4         | 5.97%   |
| 6       | 3         | 4.48%   |
| 12      | 1         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 45        | 67.16%  |
| Unknown | 22        | 32.84%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 33        | 49.25%  |
| 2       | 20        | 29.85%  |
| 1       | 14        | 20.9%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 27        | 40.3%   |
| IvyBridge   | 6         | 8.96%   |
| Zen+        | 3         | 4.48%   |
| Skylake     | 3         | 4.48%   |
| SandyBridge | 3         | 4.48%   |
| P6          | 3         | 4.48%   |
| K10         | 3         | 4.48%   |
| Haswell     | 3         | 4.48%   |
| Zen 2       | 2         | 2.99%   |
| Zen         | 2         | 2.99%   |
| Piledriver  | 2         | 2.99%   |
| KabyLake    | 2         | 2.99%   |
| Core        | 2         | 2.99%   |
| Broadwell   | 2         | 2.99%   |
| Westmere    | 1         | 1.49%   |
| Silvermont  | 1         | 1.49%   |
| Geode       | 1         | 1.49%   |
| Bobcat      | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 35        | 53.03%  |
| AMD                        | 17        | 25.76%  |
| Nvidia                     | 11        | 16.67%  |
| VIA Technologies           | 1         | 1.52%   |
| Trident Microsystems       | 1         | 1.52%   |
| Matrox Electronics Systems | 1         | 1.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 7.25%   |
| Intel HD Graphics 530                                                                    | 3         | 4.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 4.35%   |
| Nvidia GF114 [GeForce GTX 560]                                                           | 2         | 2.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 2.9%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.9%    |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 2.9%    |
| Intel Iris Graphics 6100                                                                 | 2         | 2.9%    |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 2.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.9%    |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]                        | 1         | 1.45%   |
| Trident Microsystems TGUI 9660/938x/968x                                                 | 1         | 1.45%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 1.45%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.45%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.45%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.45%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.45%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.45%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1         | 1.45%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.45%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 1.45%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.45%   |
| Intel HD Graphics 630                                                                    | 1         | 1.45%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.45%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.45%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.45%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.45%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 1         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.45%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 1.45%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.45%   |
| AMD Tonga PRO [Radeon R9 285/380]                                                        | 1         | 1.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 28        | 43.08%  |
| 1 x AMD                  | 14        | 21.54%  |
| 1 x Nvidia               | 8         | 12.31%  |
| Other                    | 6         | 9.23%   |
| 2 x Intel                | 2         | 3.08%   |
| Intel + Nvidia           | 2         | 3.08%   |
| 2 x AMD                  | 1         | 1.54%   |
| 1 x VIA                  | 1         | 1.54%   |
| 1 x Trident Microsystems | 1         | 1.54%   |
| 1 x Matrox               | 1         | 1.54%   |
| Intel + AMD              | 1         | 1.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 48        | 71.64%  |
| Unknown | 19        | 28.36%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 46.97%  |
| 1.01-2.0   | 12        | 18.18%  |
| 0.01-0.5   | 10        | 15.15%  |
| 3.01-4.0   | 7         | 10.61%  |
| 0.51-1.0   | 5         | 7.58%   |
| 7.01-8.0   | 1         | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 25.93%  |
| LG Display          | 6         | 22.22%  |
| Goldstar            | 4         | 14.81%  |
| Chimei Innolux      | 2         | 7.41%   |
| Apple               | 2         | 7.41%   |
| ViewSonic           | 1         | 3.7%    |
| Unknown (CDD)       | 1         | 3.7%    |
| LG Philips          | 1         | 3.7%    |
| Lenovo              | 1         | 3.7%    |
| Impression          | 1         | 3.7%    |
| Acer                | 1         | 3.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 2         | 7.41%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch         | 1         | 3.7%    |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch              | 1         | 3.7%    |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch  | 1         | 3.7%    |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch  | 1         | 3.7%    |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch     | 1         | 3.7%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 1         | 3.7%    |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch  | 1         | 3.7%    |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch           | 1         | 3.7%    |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch           | 1         | 3.7%    |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch          | 1         | 3.7%    |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch           | 1         | 3.7%    |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 3.7%    |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 1         | 3.7%    |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch           | 1         | 3.7%    |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 1         | 3.7%    |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1         | 3.7%    |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1         | 3.7%    |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 1         | 3.7%    |
| Goldstar LCD Monitor GSM5AB6 1920x1080 480x270mm 21.7-inch            | 1         | 3.7%    |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                  | 1         | 3.7%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 3.7%    |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch       | 1         | 3.7%    |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                | 1         | 3.7%    |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                 | 1         | 3.7%    |
| Acer SB220Q ACR06AB 1920x1080 480x270mm 21.7-inch                     | 1         | 3.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 9         | 33.33%  |
| 1366x768 (WXGA)  | 7         | 25.93%  |
| 1600x900 (HD+)   | 3         | 11.11%  |
| 1440x900 (WXGA+) | 3         | 11.11%  |
| 1280x800 (WXGA)  | 2         | 7.41%   |
| 2560x1600        | 1         | 3.7%    |
| 2560x1080        | 1         | 3.7%    |
| 1600x1200        | 1         | 3.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 8         | 29.63%  |
| 15     | 5         | 18.52%  |
| 19     | 3         | 11.11%  |
| 40     | 2         | 7.41%   |
| 23     | 2         | 7.41%   |
| 21     | 2         | 7.41%   |
| 52     | 1         | 3.7%    |
| 34     | 1         | 3.7%    |
| 27     | 1         | 3.7%    |
| 20     | 1         | 3.7%    |
| 12     | 1         | 3.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 40.74%  |
| 401-500     | 6         | 22.22%  |
| 501-600     | 3         | 11.11%  |
| 201-300     | 3         | 11.11%  |
| 801-900     | 2         | 7.41%   |
| 701-800     | 1         | 3.7%    |
| 1001-1500   | 1         | 3.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 19        | 70.37%  |
| 16/10 | 6         | 22.22%  |
| 4/3   | 1         | 3.7%    |
| 21/9  | 1         | 3.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 29.63%  |
| 201-250        | 4         | 14.81%  |
| 151-200        | 4         | 14.81%  |
| 101-110        | 3         | 11.11%  |
| 501-1000       | 2         | 7.41%   |
| 91-100         | 2         | 7.41%   |
| More than 1000 | 1         | 3.7%    |
| 61-70          | 1         | 3.7%    |
| 351-500        | 1         | 3.7%    |
| 301-350        | 1         | 3.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 12        | 44.44%  |
| 101-120 | 10        | 37.04%  |
| 121-160 | 3         | 11.11%  |
| 1-50    | 1         | 3.7%    |
| 161-240 | 1         | 3.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 37        | 56.06%  |
| 0     | 28        | 42.42%  |
| 2     | 1         | 1.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 32        | 35.96%  |
| Intel                             | 28        | 31.46%  |
| Qualcomm Atheros                  | 12        | 13.48%  |
| Broadcom                          | 5         | 5.62%   |
| Huawei Technologies               | 3         | 3.37%   |
| VIA Technologies                  | 1         | 1.12%   |
| TP-Link                           | 1         | 1.12%   |
| Oculus VR                         | 1         | 1.12%   |
| Netchip Technology                | 1         | 1.12%   |
| Mercucys                          | 1         | 1.12%   |
| Marvell Technology Group          | 1         | 1.12%   |
| Ericsson Business Mobile Networks | 1         | 1.12%   |
| D-Link                            | 1         | 1.12%   |
| 3Com                              | 1         | 1.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 29        | 25.66%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 6         | 5.31%   |
| Intel I211 Gigabit Network Connection                                                 | 3         | 2.65%   |
| Huawei USB Device                                                                     | 3         | 2.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 2         | 1.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 1.77%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 1.77%   |
| Intel Wireless-AC 9260                                                                | 2         | 1.77%   |
| Intel Wireless 8260                                                                   | 2         | 1.77%   |
| Intel Wireless 7265                                                                   | 2         | 1.77%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 2         | 1.77%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 2         | 1.77%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 1.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 1.77%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 0.88%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1         | 0.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.88%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.88%   |
| Oculus VR Rift S                                                                      | 1         | 0.88%   |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                                        | 1         | 0.88%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 0.88%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 0.88%   |
| Intel Wireless 7260                                                                   | 1         | 0.88%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 0.88%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 21        | 51.22%  |
| Qualcomm Atheros      | 9         | 21.95%  |
| Realtek Semiconductor | 5         | 12.2%   |
| Broadcom              | 3         | 7.32%   |
| TP-Link               | 1         | 2.44%   |
| Mercucys              | 1         | 2.44%   |
| D-Link                | 1         | 2.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 4.76%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 4.76%   |
| Intel Wireless-AC 9260                                                                | 2         | 4.76%   |
| Intel Wireless 8260                                                                   | 2         | 4.76%   |
| Intel Wireless 7265                                                                   | 2         | 4.76%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 2         | 4.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 4.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 4.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 2.38%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 2.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 2.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.38%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 2.38%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 2.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 2.38%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 2.38%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.38%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 2.38%   |
| Intel Wireless 7260                                                                   | 1         | 2.38%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 2.38%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 2.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 2.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.38%   |
| Intel CNVi: Wi-Fi                                                                     | 1         | 2.38%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.38%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 2.38%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 2.38%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 2.38%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 2.38%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 2.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 32        | 50%     |
| Intel                    | 20        | 31.25%  |
| Qualcomm Atheros         | 3         | 4.69%   |
| Huawei Technologies      | 3         | 4.69%   |
| Broadcom                 | 3         | 4.69%   |
| VIA Technologies         | 1         | 1.56%   |
| Marvell Technology Group | 1         | 1.56%   |
| 3Com                     | 1         | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 44.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 9.23%   |
| Intel I211 Gigabit Network Connection                             | 3         | 4.62%   |
| Huawei USB Device                                                 | 3         | 4.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 3.08%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 3.08%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.54%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.54%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.54%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.54%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.54%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.54%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.54%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.54%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.54%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 1.54%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.54%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.54%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.54%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.54%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1         | 1.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 59        | 57.28%  |
| WiFi     | 38        | 36.89%  |
| Modem    | 4         | 3.88%   |
| Unknown  | 2         | 1.94%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 48        | 70.59%  |
| WiFi     | 19        | 27.94%  |
| Unknown  | 1         | 1.47%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 32        | 49.23%  |
| 1     | 20        | 30.77%  |
| 0     | 9         | 13.85%  |
| 3     | 4         | 6.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 53        | 80.3%   |
| Yes  | 13        | 19.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 13        | 54.17%  |
| Apple                           | 3         | 12.5%   |
| Realtek Semiconductor           | 2         | 8.33%   |
| Broadcom                        | 2         | 8.33%   |
| Qualcomm Atheros Communications | 1         | 4.17%   |
| Lite-On Technology              | 1         | 4.17%   |
| IMC Networks                    | 1         | 4.17%   |
| Cambridge Silicon Radio         | 1         | 4.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 20.83%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 16.67%  |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 8.33%   |
| Realtek Bluetooth Adapter                           | 1         | 4.17%   |
| Realtek Bluetooth 4.0 Adapter                       | 1         | 4.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 4.17%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 4.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 4.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.17%   |
| Intel AX201 Bluetooth                               | 1         | 4.17%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 4.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.17%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 4.17%   |
| Apple Broadcom Built-in Bluetooth                   | 1         | 4.17%   |
| Apple Bluetooth Host Controller                     | 1         | 4.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 42        | 56%     |
| AMD                                          | 19        | 25.33%  |
| Nvidia                                       | 7         | 9.33%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.33%   |
| Yamaha                                       | 1         | 1.33%   |
| VIA Technologies                             | 1         | 1.33%   |
| Samsung Electronics                          | 1         | 1.33%   |
| Native Instruments                           | 1         | 1.33%   |
| Logitech                                     | 1         | 1.33%   |
| ESS Technology                               | 1         | 1.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 8.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 6.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 4.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 4.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 3.19%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.19%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 3.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.19%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 3.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.13%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 2         | 2.13%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.13%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 2.13%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.13%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 2.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 2.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.13%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 2.13%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 2.13%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 1.06%   |
| Yamaha AG06/AG03                                                                                  | 1         | 1.06%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 1.06%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                                        | 1         | 1.06%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.06%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.06%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.06%   |
| Native Instruments Komplete Audio 1                                                               | 1         | 1.06%   |
| Logitech Zone Wired Earbuds                                                                       | 1         | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.06%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.06%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 8         | 15.38%  |
| Kingston            | 8         | 15.38%  |
| Crucial             | 7         | 13.46%  |
| Samsung Electronics | 6         | 11.54%  |
| SK hynix            | 4         | 7.69%   |
| Micron Technology   | 4         | 7.69%   |
| G.Skill             | 3         | 5.77%   |
| A-DATA Technology   | 3         | 5.77%   |
| Ramaxel Technology  | 2         | 3.85%   |
| Patriot             | 2         | 3.85%   |
| Corsair             | 2         | 3.85%   |
| SHARETRONIC         | 1         | 1.92%   |
| Nanya Technology    | 1         | 1.92%   |
| Unknown             | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 2         | 3.57%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                     | 1         | 1.79%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s               | 1         | 1.79%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 1.79%   |
| Unknown RAM Module 2GB SODIMM DDR3                         | 1         | 1.79%   |
| Unknown RAM Module 256MB SODIMM DDR                        | 1         | 1.79%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 1.79%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 1         | 1.79%   |
| Unknown RAM Module 128MB DIMM DRAM                         | 1         | 1.79%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s             | 1         | 1.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 1.79%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.79%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 1         | 1.79%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 1.79%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s           | 1         | 1.79%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.79%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s      | 1         | 1.79%   |
| Samsung RAM M386B4G70DM0-YK03 32GB DIMM DDR3 1600MT/s      | 1         | 1.79%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 1         | 1.79%   |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s   | 1         | 1.79%   |
| Patriot RAM PSD44G213382 4096MB DIMM DDR4 2133MT/s         | 1         | 1.79%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s             | 1         | 1.79%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 1.79%   |
| Micron RAM Module 8GB Chip LPDDR4                          | 1         | 1.79%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s      | 1         | 1.79%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s       | 1         | 1.79%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s     | 1         | 1.79%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s          | 1         | 1.79%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s        | 1         | 1.79%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s      | 1         | 1.79%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB DIMM DDR3 1600MT/s       | 1         | 1.79%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s    | 1         | 1.79%   |
| Kingston RAM 99U5701-077.A00G 16GB DIMM DDR4 2667MT/s      | 1         | 1.79%   |
| Kingston RAM 99U5471-028.A00LF 4GB DIMM DDR3 667MT/s       | 1         | 1.79%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1333MT/s      | 1         | 1.79%   |
| Kingston RAM 9905428-026.A02LF 2048MB SODIMM DDR3 1066MT/s | 1         | 1.79%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s       | 1         | 1.79%   |
| G.Skill RAM F4-2800C17-8GVR 8192MB DIMM DDR4 2133MT/s      | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 21        | 47.73%  |
| DDR4    | 15        | 34.09%  |
| DRAM    | 2         | 4.55%   |
| DDR2    | 2         | 4.55%   |
| SDRAM   | 1         | 2.27%   |
| LPDDR4  | 1         | 2.27%   |
| DDR     | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 22        | 50%     |
| SODIMM | 20        | 45.45%  |
| Chip   | 2         | 4.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 16        | 34.78%  |
| 4096  | 13        | 28.26%  |
| 2048  | 7         | 15.22%  |
| 16384 | 4         | 8.7%    |
| 512   | 2         | 4.35%   |
| 32768 | 1         | 2.17%   |
| 1024  | 1         | 2.17%   |
| 256   | 1         | 2.17%   |
| 128   | 1         | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 25.49%  |
| 2133    | 5         | 9.8%    |
| 1333    | 4         | 7.84%   |
| Unknown | 4         | 7.84%   |
| 3200    | 3         | 5.88%   |
| 2667    | 3         | 5.88%   |
| 2400    | 2         | 3.92%   |
| 1867    | 2         | 3.92%   |
| 1334    | 2         | 3.92%   |
| 1067    | 2         | 3.92%   |
| 800     | 2         | 3.92%   |
| 3000    | 1         | 1.96%   |
| 2933    | 1         | 1.96%   |
| 2666    | 1         | 1.96%   |
| 1066    | 1         | 1.96%   |
| 667     | 1         | 1.96%   |
| 533     | 1         | 1.96%   |
| 400     | 1         | 1.96%   |
| 266     | 1         | 1.96%   |
| 166     | 1         | 1.96%   |

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
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 7         | 38.89%  |
| Silicon Motion                | 2         | 11.11%  |
| Realtek Semiconductor         | 2         | 11.11%  |
| Syntek                        | 1         | 5.56%   |
| Sunplus Innovation Technology | 1         | 5.56%   |
| Quanta                        | 1         | 5.56%   |
| Lenovo                        | 1         | 5.56%   |
| Bison Electronics             | 1         | 5.56%   |
| ARC International             | 1         | 5.56%   |
| ALi                           | 1         | 5.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 3         | 16.67%  |
| Syntek Lenovo EasyCamera             | 1         | 5.56%   |
| Sunplus Integrated Camera            | 1         | 5.56%   |
| Silicon Motion WebCam SC-10IRQ12340N | 1         | 5.56%   |
| Silicon Motion 300k Pixel Camera     | 1         | 5.56%   |
| Realtek USB Camera                   | 1         | 5.56%   |
| Realtek Acer 640 x 480 laptop camera | 1         | 5.56%   |
| Quanta VGA WebCam                    | 1         | 5.56%   |
| Lenovo Integrated Webcam [R5U877]    | 1         | 5.56%   |
| Chicony USB2.0 VGA UVC WebCam        | 1         | 5.56%   |
| Chicony Thinkpad T430 camera         | 1         | 5.56%   |
| Chicony HP HD Webcam [Fixed]         | 1         | 5.56%   |
| Chicony Front Camera                 | 1         | 5.56%   |
| Bison Integrated Camera              | 1         | 5.56%   |
| ARC International Camera             | 1         | 5.56%   |
| ALi Gateway Webcam                   | 1         | 5.56%   |

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
| 0     | 23        | 34.85%  |
| 1     | 20        | 30.3%   |
| 2     | 13        | 19.7%   |
| 3     | 6         | 9.09%   |
| 5     | 2         | 3.03%   |
| 4     | 2         | 3.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 35        | 47.95%  |
| Net/wireless             | 19        | 26.03%  |
| Card reader              | 7         | 9.59%   |
| Graphics card            | 5         | 6.85%   |
| Storage                  | 2         | 2.74%   |
| Net/ethernet             | 2         | 2.74%   |
| Wireless                 | 1         | 1.37%   |
| Modem                    | 1         | 1.37%   |
| Bluetooth                | 1         | 1.37%   |

